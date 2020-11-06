# Gigabyte Z390 Gaming X and i5-9600K Hackintosh

## 硬件配置

| 类型 | 型号 |
| :----:| :----:|
| 主板 | 技嘉z390 Gaming X |
| CPU | i5-9600K 6核6线程 |
| 显卡 | 蓝宝石 Radeon RX 580 2304SP |
| 内存 | 英睿达（Crucial）8GB DDR4 2666频率x2 |
| 无线网卡、蓝牙 |奋威（fenvi）FV-T919(BCM94360CD) |
| 固态 | 西部数据M.2 500G SSD |
| 电源 | 振华 GX550W 半模组 |  

## EFI 版本

OpenCore 0.6.3

## SMBIOS ID 

iMac19,1 / 27 寸

## BIOS 配置

- BIOS Q-Flash 升级为 10h (BETA)
- Advanced Mode > Settings > IO Ports > Initial Display Output > PCIe 1 Slot
- Advanced Mode > Settings > IO Ports > Above 4G Decoding > Enabled
- Advanced Mode > Settings > IO Ports > USB Configuration > XHCI Hand-off > Enabled
- Advanced Mode > Boot > CSM Support > Disabled
- Advanced Mode > Settings > IO Ports > Internal Graphics > Enabled
- Advanced Mode > Settings > IO Ports > DVMT Pre-Allocated > 128M (此配置只在启用Internal Graphics后出现)
- Advanced Mode > Power Management > ERP > Enabled
- Boot > CFG Lock > Disabled

CFG 必须禁用才能启用 NVRAM

# Credits

- https://github.com/wqh0109663/Gigabyte-Z390-Gaming-X-Hackintosh

