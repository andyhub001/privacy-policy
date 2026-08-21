# Privacy Policy Pages

一个用于托管多个 App 隐私政策的纯静态 GitHub Pages 项目。

## 公网地址

- 政策目录：https://andyhub001.github.io/privacy-policy/
- 花间诗令隐私政策：https://andyhub001.github.io/privacy-policy/flying-flower/privacy.html
- 花间诗令应用支持：https://andyhub001.github.io/privacy-policy/flying-flower/support.html

## 目录

- `public/index.html`：全部 App 的公共目录。
- `public/flying-flower/privacy.html`：花间诗令 App 的当前有效隐私政策。
- `public/flying-flower/support.html`：花间诗令 App 的公开支持页面。
- `public/<app-slug>/privacy.html`：其他 App 的独立政策路径。
- `public/<app-slug>/support.html`：其他 App 的独立支持路径。
- `public/assets/privacy.css`：所有政策页面共享的响应式样式。
- GitHub 仓库根目录保留线上发布副本，提交后自动发布 GitHub Pages。

## 新增其他 App

复制现有 App 目录到：

```text
public/<app-slug>/
```

替换隐私政策与支持信息，并在 `public/index.html` 中增加对应 App 入口。每个 App 使用独立、稳定的 HTTPS 地址。
