# [Hackintosh_9400f_b360_RX590(opencore)](https://github.com/happyendingll/Hackintosh_9400f_b360_RX590-opencore-.git)

## 配置：

| 硬件 | 型号                                      |
| ---- | ----------------------------------------- |
| 主板 | 华硕 Asus TUF B360M-PLUS GAMING S         |
| CPU  | INTEL i5-9400F (6核6线程)                 |
| 显卡 | 蓝宝石  AMD RX590                         |
| 内存 | 金士顿（Kingston）FURY内存 DDR4 2666 8G*2 |
| 固态 | 西部数据 250GB SSD固态                    |
| 网卡 | BCM94360CD黑苹果免驱网卡                  |
| 机箱 | Tt（Thermaltake）启航者F1 白色 Mini小机箱 |

## 版本状态：

系统版本：macOS Big Sur 12.2.1

SMBIOS：iMac Pro 1.1

## 说明

配置参考于[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) 

一切功能正常。

## 请自行 config 添加三码

```
<dict>
	<key>AdviseWindows</key>
	<false/>
	<key>MLB</key>
	<string>请修改我</string>
	<key>ProcessorType</key>
	<integer>0</integer>
	<key>SystemMemoryStatus</key>
	<string>Auto</string>
	<key>ROM</key>
	<data></data>
	<key>SpoofVendor</key>
	<true/>
	<key>SystemProductName</key>
	<string>iMacPro1,1</string>
	<key>SystemSerialNumber</key>
	<string>请修改我</string>
	<key>SystemUUID</key>
	<string>请修改我</string>
</dict>
```