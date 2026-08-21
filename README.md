# 重庆绿所报考指南

中国科学院重庆绿色智能技术研究院智能技术方向独立报考指南站点，对应域名 `cigit.cskaoyan.cn`。

## 本地预览

页面是纯静态站点，不需要安装依赖或构建。在仓库根目录启动 HTTP 服务后访问首页即可。

```bash
python -m http.server 4174
```

## 部署

站点可以部署到 GitHub Pages、Cloudflare Pages 或其他静态托管平台。先取得平台提供的默认地址，再请 `cskaoyan.cn` 的域名管理员为 `cigit` 添加 CNAME 记录：GitHub Pages 指向实际仓库所有者的 `<owner>.github.io`，Cloudflare Pages 指向对应的 `<project>.pages.dev`，均不要附加协议或路径。

如果使用 GitHub Pages，仓库根目录的 `CNAME` 已配置为 `cigit.cskaoyan.cn`。仓库不必强制归属 `ucas-cskaoyan-web`；是否移入该组织由维护者决定。

主导航站 `cskaoyan-cn` 中的重庆绿所入口应指向 `https://cigit.cskaoyan.cn/`。旧地址 `https://cskaoyan.cn/cqigit/` 保留跳转，避免已有链接失效。建议先确认独立站默认地址可访问，再配置子域，最后合并主站入口修改。
