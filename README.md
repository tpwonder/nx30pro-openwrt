# H3C NX30PRO OpenWrt 固件

基于 [immortalwrt-mt798x-6.6](https://github.com/padavanonly/immortalwrt-mt798x-6.6) 自动编译

## 设备信息
- **型号**: H3C Magic NX30 Pro
- **芯片**: MediaTek MT7981B (Filogic 820)
- **内存**: 256MB
- **Target**: mediatek/filogic

## 使用方法
1. Fork 本仓库
2. 进入仓库 -> Actions -> Build NX30PRO OpenWrt -> Run workflow
3. 等待编译完成(约2-3小时)
4. 在 Artifacts 中下载固件

## 包含插件
| 插件 | 说明 |
|------|------|
| luci-theme-argon | Argon 美化主题 |
| nlbwmon + luci-app | 网络数据流量监控 |
| ttyd | Web 终端 |
| zerotier | ZeroTier 组网 |
| reguard | re:Guard 网络守护 |
| upnp | UPnP 端口映射 |
| ipv6 | IPv6 完整支持 |
| cloudflared | Cloudflare Tunnel |
| vlmcsd | KMS 激活服务 |
| nano | 文本编辑器 |
| iperf3 | 网络测速 |
