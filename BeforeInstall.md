# READ ME BEFORE YOU CONFIGURE YOUR OPENCORE!!!
# 看完这些内容再装黑苹果EFI！！！


## EN

Rename touchScreen.plist or trackPad.plist to config.plist as you want.

**Structure for your ESP partition:**
EFI
├── Boot
│   └── bootx64.efi
└── OC
    ├── ACPI
    │   └── ...
    ├── Drivers
    │   └── ...
    ├── Kexts
    │   └── ...
    ├── Resources
    │   └── ...
    ├── Tools
    │   └── ...
    ├── OpenCore.efi
    └── config.plist

**What's doesn't work with *trackPad.plist*:**
> Touch screen
> Stylus
> Trackpad gesture
> Battery management & info
> Volume + and - key
> Hibernate
> Camera
> Sidecar
> Universal control
> Airdrop

**What's working with *trackPad.plist*:**
> Microphone
> Siri
> iCloud
> USB (Only tested with USB-disk)
> Surface Keyboard (Include functional keys)
> 3.5mm audio jack
> Speaker
> Intel UHD 630 GPU
> WLAN (Only able for you to surf the internet)
> Bluetooth (Only tested for connecting with BT-speaker, BT-keyboard&mouse)


**What's doesn't work with *trackPad.plist*:**
> **Trackpad**
> Stylus
> Trackpad gesture (But you are able to use gestures on touchscreen)
> Battery management & info
> Volume + and - key
> Hibernate
> Camera
> Sidecar
> Universal control
> Airdrop

**What's working with *trackPad.plist*:**
> **Touch screen (*WITH GESTURE SUPPORT*, but it randomly failure while you are using)**
> System will crash while you plug or unplug surface keyboard
> Microphone
> Siri
> iCloud
> USB (Only tested with USB-disk)
> Surface Keyboard (Include functional keys)
> 3.5mm audio jack
> Speaker
> Intel UHD 630 GPU
> WLAN (Only able for you to surf the internet)
> Bluetooth (Only tested for connecting with BT-speaker, BT-keyboard&mouse)


## 中文/ ZH

根据需要将 touchScreen.plist 或 trackPad.plist 重命名为 config.plist。

 **最终你的 ESP 分区的结构必须是这样：**
 EFI
├── Boot
│   └── bootx64.efi
└── OC
    ├── ACPI
    │   └── ...
    ├── Drivers
    │   └── ...
    ├── Kexts
    │   └── ...
    ├── Resources
    │   └── ...
    ├── Tools
    │   └── ...
    ├── OpenCore.efi
    └── config.plist


 ***trackPad.plist*的bug：**
 > 触摸屏
 > 手写笔
 > 触控板手势
 > 电池管理信息
 > 音量 + 和 - 键
 > 休眠
 > 相机
 > 随航
 > 通用控制
 > 隔空投送

 ***trackPad.plist*可用的功能：**
 > 麦克风
 > Siri
 > iCloud
 > USB (只测试过U盘)
 > Surface 键盘（包括功能键）
 > 外星科技
 > 扬声器
 > UHD 630核显
 > WLAN（只能联WiFi上网）
 > 蓝牙（仅测试过蓝牙音箱和蓝牙键鼠）


 ***trackPad.plist*的bug：**
 > **触控板**
 > 插拔surface键盘的时候系统会崩溃
 > 手写笔
 > 触控板手势（但您可以在触摸屏上使用手势）
 > 电池管理信息
 > 音量 + 和 - 键
 > 休眠
 > 相机
 > 随航
 > 通用控制
 > 隔空投送

 ***trackPad.plist*可用的功能：**
 > **触摸屏（*有手势支持*，但它在您使用时随机失效）**
 > 麦克风
 > Siri
 > iCloud
 > USB (只测试过U盘)
 > Surface 键盘（包括功能键）
 > 外星科技
 > 扬声器
 > UHD630核显
 > WLAN（只能联WiFi上网）
 > 蓝牙（仅测试过蓝牙音箱和蓝牙键鼠）
