# 地球Online · 安装包分发

这个仓库只放两样东西：`update.json`（App 内「检查更新」读的清单）和每个版本 Release 里的 APK 附件。
源码在私有仓库 kkkty/earthOnline，不在这儿。

App 拉清单走 API 域名（这台网络下 raw.githubusercontent.com 常不通）：
`https://api.github.com/repos/kkkty/earthOnline-releases/contents/update.json`（`Accept: application/vnd.github.raw`）。

APK 是手动安装用的：下载后在手机上打开，允许「未知来源」即可覆盖安装，签名与 v1.0 起一致，数据不丢。
