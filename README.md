# 给你的粒子宇宙

一个可以公网分享的静态网页。部署后不需要电脑一直开着，摄像头手势在 HTTPS 域名下可用。

## 推荐部署

### Cloudflare Pages（最稳，适合直接分享）

1. 登录 Cloudflare Dashboard。
2. 进入 Workers & Pages -> Pages -> Create using direct upload。
3. 上传整个 `交互` 文件夹。
4. 部署完成后复制 Cloudflare 给出的 HTTPS 链接。

### GitHub Pages（稳定，适合长期保留）

1. 创建一个公开 GitHub 仓库。
2. 上传本文件夹内的 `index.html`、`.nojekyll` 和 `vendor/`。
3. 在仓库 Settings -> Pages 中选择 `Deploy from a branch`。
4. 分支选 `main`，目录选 `/root`，保存后等待生成 HTTPS 链接。

## 手势

- 张开手：星球
- 比耶：情话文字
- 握拳：圆环
- 竖食指：星星
- 点赞：爱心
- 拇指和食指捏合：花

## 注意

- 摄像头手势需要 HTTPS，Cloudflare Pages、GitHub Pages、Vercel、Netlify 都满足。
- 文件已经本地化依赖，公网部署后不需要实时访问 unpkg。
- 如果摄像头被浏览器拒绝，页面底部按钮仍然可以手动演示。
