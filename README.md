# 基金投顾保有提升工作台

多人协作的基金投顾保有提升进度看板，单文件网页应用。

- 访问地址：https://adoradan.github.io/fund-baoyou-workbench/ （以实际 `gh` 返回为准）
- 数据默认保存在各填报人自己的浏览器 localStorage 中。
- 支持「复制数据包 / 粘贴数据包」离线互传合并；如需多人实时云端共享，请接入正式的云数据库（推荐腾讯云 CloudBase），不建议在公开页面内嵌可写令牌。

## 目录结构

- `index.html` —— 工作台应用（单文件）
- `data/shared.json` —— 共享数据文件占位（空 `{}`）

## 部署到 GitHub Pages

1. 本仓库 `main` 分支根目录即站点根目录。
2. 在仓库 Settings → Pages 选择 Deploy from a branch，分支 `main`、目录 `/（root）` 即可。