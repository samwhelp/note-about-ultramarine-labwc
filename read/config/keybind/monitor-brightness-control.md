---
title: 螢幕亮度控制
nav_order: 5053
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 螢幕亮度控制

* [亮度控制](#亮度控制)




## 亮度控制

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L325-L330)


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `XF86_MonBrightnessDown (XF86MonBrightnessDown)` | 減少螢幕亮度         | `brightnessctl set 5%-` |
| `XF86_MonBrightnessUp (XF86MonBrightnessUp)` | 增加螢幕亮度         | `brightnessctl set +5%` |


* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L331-L342)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Ctrl + [` | 減少螢幕亮度         | `brightnessctl set 1%-` |
| `Alt + Ctrl + ]` | 增加螢幕亮度         | `brightnessctl set +1%` |




| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + [` | 減少螢幕亮度         | `brightnessctl set 5%-` |
| `Alt + Shift + ]` | 增加螢幕亮度         | `brightnessctl set +5%` |




## 用法對照

* [音量控制](https://samwhelp.github.io/note-about-labwc/read/config/keybind/volume-control.html)
