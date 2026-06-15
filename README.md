# 历史粘贴板 - 官方网站

## 文件结构

```
website/
├── index.html              # 网站首页（单页）
├── favicon.ico             # 网站图标
├── ClipboardHistory.exe    # 软件下载（42MB）
└── README.md               # 本文件
```

## 部署方式

### 方式一：GitHub Pages（免费）

1. 创建 GitHub 仓库
2. 将 `website/` 文件夹内所有内容上传到仓库根目录
3. Settings → Pages → Source: `main` branch → Save
4. 几分钟后即可通过 `https://你的用户名.github.io/仓库名/` 访问

### 方式二：本地预览

直接双击 `index.html` 即可在浏览器中查看。

### 方式三：任意静态托管

将 `website/` 文件夹内容上传到任意静态文件服务器即可（Nginx、OSS、Vercel、Netlify 等）。

## 注意事项

- `ClipboardHistory.exe` 文件较大（42MB），GitHub 单文件限制 100MB，在允许范围内
- 如果下载链接无法访问，请确保 exe 文件与 index.html 在同一目录下
- favicon.ico 为软件图标，出现在浏览器标签页上
