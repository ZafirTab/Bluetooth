# Bluetooth-学习指北

该篇是蓝牙部分的开篇,旨在从总体上了解蓝牙.

*是什么?*
## 蓝牙由来
蓝牙一词源于公元十世纪丹麦国王HaraldBlatand名字中的Blatand，Blatand的英文之意就是Blue tooth。这是因为这位让丹麦人引以为傲的国王酷爱吃蓝莓，
以至于牙龈每天都被染成蓝色。由于Blatand国王将现在的挪威、瑞典和丹麦统一了起来，因此，作为无线通信技术的一种，蓝牙技术取名Bluetooth可谓志向远大。

蓝牙的创始人是瑞典爱立信公司，爱立信早在1994年就已进行研发。1997年，爱立信与其他设备生产商联系，并激发了他们对该项技术的浓厚兴趣。 
1998年2月，5个跨国大公司，包括爱立信、诺基亚、IBM、东芝及Intel组成了一个特殊兴趣小组（SIG），他们共同的目标是建立一个全球性的小范围无线通信技术，
即现在的蓝牙。

## 蓝牙核心规范发展介绍
以core specification CORE SPECIFICATION CHANGE HISTORY内容为准
| 版本 | 规范发布日期 |速率 |增强功能|
| ------ | ------ | ------ |------ |
| 0.7 | 1998.10.19 |  | Baseband、LMP |
| 0.8 | 1999.1.12 |  | HCI、L2CAP、RFCOMM |
| 0.9 | 1999.4.30 |  |OBEX与IrDA的互通性 |
| 1.0 Draft | 1999.7.5 |  |SDP、TCS |
| 1.0 A| 1999.7.26 |  | 第一个正式版本 |
| 1.0 B | 2000.10.1 |  | 安全性，厂商设备之间连接兼容性 |
| 1.1 | 2001.2.22 |748-810Kbps  |IEEE 802.15.1 |
| 1.2 | 2003.11.5 |748-810Kbps  | 快速连接、自适应跳频、错误监测和流程控制、同步能力 |
| 2.0+EDR | 2004.11.9 |1.8Mbps-2.1Mbps  |EDR传输率提升至2-3Mbps |
| 2.1+EDR | 2007.7.26 |2.1Mbps  |扩展查询响应、简易安全配对、暂停和继续加密、sniff省电 |
| 3.0+HS | 2009.4.21 |24Mbps  |交替射频技术、802.11协议适配层、电源管理、取消了UMB的应用 |
| 4.0+BLE |2010.6.30 |  |低功耗物理层和链路层、AES加密、ATT、GATT、SM |
| 4.1 | 2013.12.6 |  |1）与4G不构成干扰    2）通过IPV6连接到网络   3）可同时发射和接收数据 |
| 4.2 | 2014.12.4 |  |FIPS加密、安全连接、物联网 |
| 5.0 | 2016年6月16日 |24Mbps  |Slot Availability Mask (SAM) & 2 Msym/s PHY for LE LE Long Range &  High Duty Cycle Non-Connectable Advertising &  LE Advertising Extensions |
| 5.1 |2019年1月29日 |  |Angle of Arrival (AoA) and Angle of Departure (AoD) & Advertising Channel Index & GATT Caching   |
| 5.2 | 2020年1月6日 |  |LE Isochronous Channels &  Enhanced Attribute Protocol & LE Power Control |
| 6.0 | is coming |  | |

*如何学?*
## 学习资料推荐
+ 官方文档

[蓝牙官网](https://www.bluetooth.com/)

+ 两本不错的LE相关的外文书籍,需要仔细品味

[Bluetooth Low Energy The Developer's Handbook(低功耗蓝牙开发权威指南英文版)](http://gen.lib.rus.ec/search.php?req=Bluetooth+Low+Energy+The+Developer%27s+Handbook&lg_topic=libgen&open=0&view=simple&res=25&phrase=1&column=def)

[Gupta, Naresh-Inside bluetooth low energy-Artech House (2016)](http://gen.lib.rus.ec/search.php?req=Inside+bluetooth+low+energy&open=0&res=25&view=simple&phrase=1&column=def)

+ 理论总是枯燥的,结合代码来分析会更香

[Android 蓝牙协议栈源码](https://cs.android.com/android/platform/superproject/+/master:system/bt/)
