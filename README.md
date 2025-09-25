
# 部署说明（GitHub Pages / Netlify）

## 方式 A：GitHub Pages（推荐，永久免费）
1. 新建一个 GitHub 仓库，例如 `happy-xiaoyang`。
2. 把本文件夹内的所有文件（尤其是 `index.html`）上传到仓库根目录（`main` 分支）。
3. 进仓库 Settings → Pages：
   - **Source** 选择 `Deploy from a branch`
   - **Branch** 选择 `main`，文件夹选择 `/ (root)`，保存。
4. 几十秒后会得到公开网址：`https://你的用户名.github.io/仓库名/`

## 方式 B：Netlify（零配置，拖拽上传）
1. 打开 https://app.netlify.com/drop
2. 把整个文件夹拖进去，等待部署完成。
3. Netlify 会给出一个公开子域名，形如 `https://xxx.netlify.app/`。

## 方式 C：Vercel（可选）
1. https://vercel.com 新建项目，导入 GitHub 仓库或直接上传。
2. 项目类型选择 `Other`（静态站点），根目录即当前文件夹。
3. 部署完成后获得 `https://xxx.vercel.app/`。

如需绑定自己的域名，以上平台都支持在控制台里设置自定义域名（需要解析 CNAME）。
