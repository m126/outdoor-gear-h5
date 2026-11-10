# 拾光山野Lab H5

纯静态 H5 装备管理应用。当前版本不接入服务端，数据保存在浏览器本地 IndexedDB。

## 部署

本仓库使用 Cloudflare Workers Static Assets：
- 静态资源目录：`public/`
- 入口：`public/index.html`
- 配置：`wrangler.toml`

在 Cloudflare Workers & Pages 中通过 GitHub 连接本仓库，使用 Wrangler 部署。首次连接完成后，push 到 `main` 可触发自动部署。

## 数据说明

应用不上传装备数据。不同浏览器/设备的数据不自动同步；清理站点数据前请先导出备份。
