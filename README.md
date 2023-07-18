<h1 align="Center">Lenovo Xiaoxin-15ARE 2020 Hackintosh</h1>



<h5 align = "Center">作者：Zrc00.</h5>

#### 设备信息:

![sysinfo](./img/sysinfo.png)

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

#### 需要的工具

适用于Windows，macOS，Linux的Config.plist编辑工具OCAT：https://githubfast.com/ic005k/OCAuxiliaryTools/releases

适用于macOS的配置查看，补丁工具Hackintool：https://githubfast.com/benbaker76/Hackintool

适用于Windows，macOS，Linux的macOS三码生成工具GenSMBIOS：https://githubfast.com/corpnewt/GenSMBIOS

DiskGenius专业版，MD5校验工具已经放于“Tools”文件夹内，需要自行下载。

注意：EFI已经抹除三码信息，请自行生成三码，机型使用MacBook Pro 16,3。

![threema](./img/threema.png)
<p>对上述内容有疑问，请发送至邮箱:**wishyou2023@outlook.com**</p>
**非必要请勿打扰。**
