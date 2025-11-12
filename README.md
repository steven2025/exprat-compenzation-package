# 外派人员薪酬包设计（GitHub Pages 版本）

这是一个可直接部署到 GitHub Pages 的最小站点。

## 使用方法
1. 新建或打开一个 GitHub 仓库。
2. 上传本文件夹内的所有文件（`index.html`、`README.md`）。
3. 进入仓库 **Settings → Pages**：
   - **Source** 选择 **Deploy from a branch**；
   - **Branch** 选择 `main`（或你正在使用的分支），文件夹选择 `/ (root)`；
   - 保存生效。
4. 等待 1-2 分钟，访问 Pages 提供的网址即可打开页面。

> 说明：
> - 本页面依赖的 JS 均走 CDN（Chart.js 和 chartjs-plugin-datalabels），无需额外资源。
> - 若你希望通过仓库根路径直接访问，请保持文件名为 `index.html`；
> - 若你打算与其他页面共存，也可将文件改名为 `expat.html`，并从 `index.html` 链接过去。

