# cat 的公益节点 · 静态站

纯静态版本，可直接托管在 GitHub Pages（或任何静态托管）。

## 文件
- `index.html` — 首页（含节点参数、使用说明、软件下载、推荐站点、隐私政策）
- `404.html` — 自定义404
- `.nojekyll` — 关闭 Jekyll 处理（重要，否则下划线目录会被吃掉）

## 部署到 GitHub Pages
1. 在 GitHub 新建仓库（Public）
2. 把本目录三个文件推到仓库根目录
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch` → 分支 `main` / 根目录
4. 等 1 分钟，访问 `https://<用户名>.github.io/<仓库名>/`

若仓库名就叫 `<用户名>.github.io`，访问地址是 `https://<用户名>.github.io/`。

## 自定义域名（可选）
在仓库根放一个 `CNAME` 文件，内容只写域名一行，例如：
```
cat.example.com
```
然后在域名商处把该域名 CNAME 到 `<用户名>.github.io`。
