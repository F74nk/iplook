# IPLOOK · 多源 IP 出口检测

一个纯前端的 IP 诊断小站，访问 **https://iplook.ipv64.net**

## 功能

- **四路出口检测**：IPv4 出口 / IPv6 出口 / 国内接口 / 国际接口，多源交叉验证
- **出口一致性判定**：多源结果不一致时提示存在分流代理（这是纯前端站点最有价值的一条信息）
- **任意 IP / 域名反查**：域名走 Google DoH 解析后查归属地
- **本机环境**：UA / 语言 / 时区 / 分辨率 / 是否代理
- **地名中文化**：`China / Beijing` → `中国 / 北京`
- 一键复制 IP、移动端适配

## 数据来源

ip.sb · ipapi.is · ipinfo.io · ipip.net · freeipapi · ipify

全部请求由浏览器直接发起，本站不经过任何服务器中转，不记录、不存储访问者 IP。

## 说明

纯静态单文件（`index.html`），无构建步骤、无依赖。赞赏码已内联为 data URI，不需要额外图片文件。

## 部署

GitHub Pages，`main` 分支根目录。`CNAME` 已指向 `iplook.ipv64.net`，HTTPS 由 GitHub 自动签发。
