## 自由网络相关的工具

- ### singbox-openwrt 目录

为 openwrt 下 使用原生 singbox 相关配置文件，，

目前还需要配合 homeproxy 来配合使用。。。后续完全独立使用

- #### singbox 目录

为项目 https://github.com/haierkeys/singbox-subscribe-convert 中使用的 节点订阅地址 和 转换模板。。

主要功能为 singbox 远端配置二次聚合转换，

主要解决为了避免使用P核 等各类 singbox 版本带来的版本 节点配置 碎片化问题

实现最终一个订阅地址 多端多个 singbox 版本使用

推荐使用 https://github.com/sub-store-org/Sub-Store 来做  机场 / 节点 初次转换，

再使用 `singbox-subscribe-convert` 生成最终的订阅地址， 目前功能还比较简陋， 欢迎建议增加新功能
