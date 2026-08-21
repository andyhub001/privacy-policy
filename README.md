# Privacy Policy Pages

一个用于托管多个 App 隐私政策的纯静态 GitLab Pages 项目。

## 目录

- `public/index.html`：政策总目录。
- `public/privacy.html`：首个 App 的可配置占位政策。
- `public/apps/<app-slug>/privacy.html`：后续 App 的独立政策路径。
- `public/assets/privacy.css`：所有政策页面共享的响应式样式。
- `.gitlab-ci.yml`：默认分支提交后自动发布 GitLab Pages。

## 完善首个政策

在 `public/privacy.html` 中搜索以下占位符并替换：

- `[App 名称待填写]`
- `[开发者名称待填写]`
- `[联系邮箱待填写]`
- `[生效日期待填写]`
- `[SDK 使用情况待确认]`
- `[数据与权限使用情况待确认]`

修改后提交到默认分支，GitLab CI/CD 会自动重新发布。

## 新增其他 App

复制 `public/privacy.html` 到：

```text
public/apps/<app-slug>/privacy.html
```

替换占位内容，并在 `public/index.html` 中增加对应入口。每个 App 使用独立、稳定的 HTTPS 地址。

