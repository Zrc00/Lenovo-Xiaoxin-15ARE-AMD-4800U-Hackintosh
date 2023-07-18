<h1 align="Center">Lenovo Xiaoxin-15ARE 2020 Hackintosh</h1>



<h5 align = "Center">作者：Zrc.</h5>

#### 设备信息:

![sysinfo](.\img\sysinfo.png)

<p align="Center">[图]系统信息</p>

某些与本机配置接近的小新笔记本也适用于本EFI。

#### macOS版本选择:

|    系统版本    |        特点        |
| :------------: | :----------------: |
| macOS Big Sur  | 最为稳定，最为推荐 |
| macOS Monterey |      未经测试      |
| macOS Ventura  |  不稳定，有时卡死  |
|  macOS Sonoma  |  测试版本，不稳定  |

#### 详细配置表：

| 硬件类型 |                    硬件名称                    | 是否驱动 |      备注      |
| :------: | :--------------------------------------------: | :------: | :------------: |
|  处理器  |           1.80 GHz AMD Ryzen 7 4800U           |    ✔     |                |
|   显卡   |            AMD Radeon Graphics 2GB             |    ✔     | Nootedred.kext |
|   网卡   | Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC |    ❌     |  需要更换网卡  |
|   硬盘   |                 Lexar 1TB SSD                  |    ✔     |                |
|   键盘   |                       /                        |    ✔     |                |
|   声卡   |         Realtek High Definition Audio          |    ✔     |                |
|  麦克风  |                 Realtek Audio                  |    ❌     |    无法使用    |
|  摄像头  |               Integrated Camera                |    ✔     |                |
|   内存   |               16GB DDR4 3200MHz                |    ✔     |                |
|   USB    |                       /                        |    ✔     |                |
|  触控板  |             符合 HID 标准的触摸板              |    ✔     |                |

注意：EFI已经抹除三码信息，请自行生成三码，机型使用MacBook Pro 16,3。
