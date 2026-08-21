# Privacy Policy Pages

用于托管多个 App 隐私政策的纯 HTML 静态网站，作为 Apple App Store Connect 的 Privacy Policy URL。

## 公网地址

- 政策目录：https://andyhub001.github.io/privacy-policy/
- 占位政策：https://andyhub001.github.io/privacy-policy/privacy.html

## 文件结构

- `index.html`：隐私政策目录。
- `privacy.html`：首个 App 的可配置占位政策。
- `assets/privacy.css`：响应式页面样式。
- `404.html`：无效地址提示页。

## 完善政策

在 `privacy.html` 中搜索并替换以下占位内容：

- `XXX App`
- `[开发者名称待填写]`
- `[联系邮箱待填写]`
- `[生效日期待填写]`
- SDK、数据处理和设备权限说明

## 增加其他 App

可创建 `apps/<app-slug>/privacy.html`，并在 `index.html` 添加入口。每个 App 使用独立且稳定的 HTTPS 地址。

GitHub Pages 从 `main` 分支根目录自动发布，不需要后端、数据库或自定义域名。
