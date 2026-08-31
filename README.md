# Crosslink

客户台账。管理银行与交易员、记录应酬、按轮次看覆盖、每天攒周报素材。

纯前端单文件，无后端、无账号、无网络请求。**所有数据只存在你自己设备的浏览器里**（localStorage），不会上传到 GitHub 或任何服务器。

## 部署到 GitHub Pages

1. 新建一个仓库，例如 `crosslink`。
2. 把这四个文件传到仓库根目录：
   - `index.html`
   - `manifest.json`
   - `icon-192.png` `icon-512.png` `icon-180.png`（`favicon.png` 可选）
3. 仓库 → Settings → Pages → Source 选 `Deploy from a branch`，分支选 `main`、目录选 `/ (root)`，保存。
4. 等一两分钟，访问 `https://<你的用户名>.github.io/crosslink/`。

仓库设成 Private 也可以用 Pages（需要付费账户）；设成 Public 时**公开的只是代码，你录入的数据不在仓库里**。

## 装到手机主屏

- iPhone：Safari 打开网址 → 分享 → 添加到主屏幕。之后全屏运行，图标就是 Crosslink。
- 安卓：Chrome 打开 → 菜单 → 添加到主屏幕。

## 数据

- 存储上限约 5 MB，水单图片是唯一会撑爆它的东西（压缩后每张约 100–200 KB）。
- 设置里有存储用量条和「导出 JSON」。**每周导一次**，换手机或清缓存前必须导。
- 换设备：在旧设备导出 JSON，新设备打开同一网址，设置里导入。
