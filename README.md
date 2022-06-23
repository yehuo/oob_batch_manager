# oob_batch_manager

使用Flask构建的带外管理接口的集中管理模块

## Functions

- 【电源管理】服务器批量关机、重启
- 【系统引导】设定Bios中boot_method为efi模式
- 【用户管理】从Vault中读取，并初始化ipmi用户、密码
- 【多平台】同时支持Dell、超微、浪潮服务器以解决底层平台不统一性

## No-Goals

- 【Raid】MagaCli的管理暂不列入支持范围
- 【动态可扩展】对于新节点的扩展和已有节点的扫面，暂不列入支持范围

## Dev Framework

- 前端：vue
- 后端：flask
- 数据库：mongodb
- 同步工具：ipmitool

## Support Machine

- Dell
- Supermicro
- Inspur