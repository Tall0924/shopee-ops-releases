# shopee-ops-releases

ShopeeOps 桌面端热更新发布仓库。

- 仅存放安装包与版本元数据（latest.yml / blockmap）
- 源码不在本仓库
- 客户端通过 electron-updater 的 github provider 读取 releases.atom 与附件
