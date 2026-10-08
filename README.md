# denymosh.github.io

sicaper.net 的导航页。SICAPER = SI（超级智能）+ Caper（探索）。

- `index.html`：导航页，单文件，无构建步骤。
- `fonts/zendots.woff2`：标题字体 Zen Dots（拉丁字符子集），SIL Open Font License 1.1，许可证见 `fonts/OFL.txt`。中文用系统字体。
- `CNAME`：自定义域名 `sicaper.net`。

## 部署

Pages 设为从 `main` 分支根目录发布，推送到 `main` 即上线。

其他开了 Pages 的仓库会自动出现在 `sicaper.net/<仓库名>/` 下，例如 [ndx100](https://sicaper.net/ndx100/)。新增项目时，在 `index.html` 的 `.cards` 里照现有卡片加一张，顶部 `nav` 也可加一个入口。
