# I3-8100_HD7850_Catalina_10.15.3_EFI
## 配置
| CPU | 主板 | 内存 | 显卡 | 网卡 |
|  ----  | ----  | ----  | ----  | ---- |
| i3-8100 | 铭瑄H110M | 2*8GDDR3-1333专用条 | 迪兰HD7850-2G | RTL8100 |

EFI十分稳定，升级自行更新CLover

### 目前已知问题

* 睡眠未测试

### 使用须知

* 铭瑄H110M网卡内核替换为RTL8100，其他主板自行替换 RTL8111.kext;
* 蓝牙是某宝20元买的4.0 直插免驱
* 不使用Wi-Fi 可以自行购买蓝牙WI-FI二合一免驱网卡
* 非铭瑄H110M声卡请自行查询注入ID； [AppleALC支持的Codecs](https://blog.daliansky.net/AppleALC-Supported-codecs.html)

### 打赏

| 微信 | 支付宝 | 
|  ----  | ----  |
| ![微信打赏码](https://raw.githubusercontent.com/plusl894860970/k480d-i5-d1-hackintosh/master/image/wechat.png) | ![支付宝打赏码](https://raw.githubusercontent.com/plusl894860970/k480d-i5-d1-hackintosh/master/image/alipay.png) | 


### 截图

![关于本机]](https://raw.githubusercontent.com/plusl894860970/I3-8100_HD7850_Catalina_10.15.3_EFI/master/screenshots/About.png)
![声卡]](https://raw.githubusercontent.com/plusl894860970/I3-8100_HD7850_Catalina_10.15.3_EFI/master/screenshots/Audio.png)
![蓝牙]](https://raw.githubusercontent.com/plusl894860970/I3-8100_HD7850_Catalina_10.15.3_EFI/master/screenshots/Bluetooth.png)
![网络]](https://raw.githubusercontent.com/plusl894860970/I3-8100_HD7850_Catalina_10.15.3_EFI/master/screenshots/Network.png)

## 各平台免驱卡列表 
默认使用ATI显卡，不同平台显卡请自行修改config.plist

### Intel
英特尔® 超核芯显卡 630
我的H110M主板只有DVI接口，不考虑核显

### ATI
- Vega FE
- Vega 64
- Vega 56
- Vega Nano
- Pro SSG
- WX 9100
- WX 8200
- RX 590
- RX 580
- RX 570
- RX 560
- RX 560D
- RX 480
- RX 470
- RX 470D
- RX 460
- WX 7100
- WX 5100
- WX 4100
- Pro Duo (Fiji)
- W9100
- W9100 32GB
- W9000
- W8100
- W8000
- W7100
- W7000
- W5100
- W5000
- R9 Fury
- R9 Fury X
- R9 Nano
- R9 380
- R9 280X
- R9 280
- R9 370X
- R9 270X
- HD7990
- HD7970
- HD7950
- HD7870
- HD7850

### Nvidia
- GTXTitan
- GTXTitan Z
- GTX Titan Black
- GTX690
- GTX680
- GTX760
- GTX770
- GTX780
- GTX780Ti
- GTX650
- GTX650Ti
- GT640
- GT710
- GT740
- K6000
- K5200
- K5000
- K4000
- K4200
- K2000
- K2000D
- K600
- K420
