# about lmse

单页静态网站，通过 B 站官方播放器展示作品集。

- 视频：https://www.bilibili.com/video/BV1nqe766EBq/
- 固定入口：https://about.lmse.design/
- 源码：https://github.com/LiminSE/ta-portfolio
- 托管：GitHub Pages，`main` 分支根目录。

当前主页仅包含标题 `about lmse`、小字 `主页锐意制作中` 和 B 站视频播放器。

## 修改页面

直接编辑 `index.html`，无需安装依赖或构建。更换视频时，同时更新播放器的 `bvid` / `cid` 。

## 自定义域名

仓库 Settings → Pages 已绑定 `about.lmse.design`。DNS 已配置记录：

| 类型 | 主机记录 | 记录值 |
| --- | --- | --- |
| CNAME | about | liminse.github.io |

证书可用后开启 Enforce HTTPS。现有主域名 `lmse.design` 保持原配置。

## 后续扩展

可以在这个仓库继续增加项目详情与其他页面，保持自定义域名不变。视频保存在 B 站，仓库只包含网页。
