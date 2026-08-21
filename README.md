# Privacy Policy Pages

一个用于托管多个 App 隐私政策的纯静态 GitHub Pages 项目。

## 公网地址

- 政策目录：https://andyhub001.github.io/privacy-policy/
- 飞花令隐私政策：https://andyhub001.github.io/privacy-policy/privacy.html

## 目录

- `public/index.html`：政策总目录。
- `public/privacy.html`：飞花令 App 的当前有效隐私政策。
- `public/apps/<app-slug>/privacy.html`：后续 App 的独立政策路径。
- `public/assets/privacy.css`：所有政策页面共享的响应式样式。
- GitHub 仓库根目录保留线上发布副本，提交后自动发布 GitHub Pages。

## 新增其他 App

复制 `public/privacy.html` 到：

```text
public/apps/<app-slug>/privacy.html
```

替换占位内容，并在 `public/index.html` 中增加对应入口。每个 App 使用独立、稳定的 HTTPS 地址。
