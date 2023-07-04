# PVE

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FspiritLHLS%2Fpve&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

感谢 Proxmox VE 的免费订阅支持

如果有未适配的商家或机器欢迎联系[@spiritlhl_bot](https://t.me/spiritlhl_bot)，有空会尝试支持一下

待开发内容：

- 创建带IPV6独立地址的VM虚拟机或CT容器
- KVM模板加载部分自定义的限制，避免机器用于滥用发包
- 增加arm64架构的一键安装功能

## 更新

2023.07.02

- 修复部分机器的网络配置重复行的部分空格数量不一致导致未识别出重复的问题
- 修复部分网络配置的子目录有写但不使用的情况，这种情况就不需要合并配置文件了，修复了之前强制合并的问题
- 修复适配部分机器默认防火墙是开启且屏蔽了部分端口的情况

[更新日志](CHANGELOG.md)

## 说明文档

[virt.spiritlhl.net](https://virt.spiritlhl.net/) 中 Proxmox VE 分区内容

## Stargazers over time

[![Stargazers over time](https://starchart.cc/spiritLHLS/pve.svg)](https://starchart.cc/spiritLHLS/pve)

## 友链

VPS融合怪测评脚本

https://github.com/spiritLHLS/ecs
