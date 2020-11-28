# Hasee K650D-i5 D2
# 神舟K650D i5d2，完美支持安装 macOS10.15.X系统。

## 电脑配置

| 规格     | 详细信息                           |
| -------- | ---------------------------------- |
| 电脑型号 | 战神 K650D-i5 D2                   |
| 处理器   | Intel Core i5-4210M @ 2.60GHz 双核 |
| 显卡     | Intel HD Graphics 4600             |
| 显示器   | 三星 1920x1080 (15.6 英寸)         |
| 声卡     | VIA VT10802 (节点:3/33/65)            |
| 网卡     | 已驱动Intel网卡                    |
| 蓝牙     | 使用 BCM95352HMB                   |

## 正常工作的

- 系统：macOS Catalina 10.15.7
- 显卡 显示器内建、亮度调节（可用 `Fn + F8` 和 `Fn + F9` 调节 ）
- 音频
- USB
- 有线、Wifi
- 蓝牙
- 睡眠（鼠标、电源键唤醒正常）
- 电池显示
- 变频（看起来没什么问题）
- 触摸板

## 不能工作的

- 独显（无解，已屏蔽）

## 更新

更新 修复 USB 稳定性，电池显示，注入 PCI 属性

使用 AirportItlwm.kext 驱动Intel WiFi和蓝牙

更新 `AppleALC.kext` 到 `1.3.8` 后，可使用 layout-id 65



## 鸣谢

- [黑果小兵](https://github.com/daliansky/) 
- [ivothgle](https://github.com/ivothgle/)
