---
title: 音量控制
nav_order: 5052
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 音量控制

* [pamixer 版本](#pamixer-版本)
* [amixer 版本](#amixer-版本)




## pamixer 版本


* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L285-L293)

| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86_AudioMute (XF86AudioMute)`        | 音量切換成靜音 | `pamixer --toggle-mute`     |
| `XF86_AudioLowerVolume (XF86AudioLowerVolume)` | 減小音量       | `pamixer -d 5` |
| `XF86_AudioRaiseVolume (XF86AudioRaiseVolume)` | 增加音量       | `pamixer -i 5` |



* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L180-L182)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + v` | 開啟音量控制面板 | `mate-volume-control`                       |


* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L294-L308)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + m`         | 音量切換成靜音   | `amixer -q -D pulse sset Master toggle`     |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Ctrl + ,`  | 緩慢地減小音量   | `pamixer -d 5` |
| `Alt + Ctrl + .`  | 緩慢地增加音量   | `pamixer -i 5` |




> TODO: Fix Not Work!

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Shift + <` | 減小音量         | `pamixer -d 10` |
| `Alt + Shift + >` | 增加音量         | `pamixer -i 10` |








## amixer 版本


* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L269-L268)

| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86_AudioMute (XF86AudioMute)`        | 音量切換成靜音 | `amixer -q -D pulse sset Master toggle`     |
| `XF86_AudioLowerVolume (XF86AudioLowerVolume)` | 減小音量       | `amixer -q -D pulse sset Master 5%- unmute` |
| `XF86_AudioRaiseVolume (XF86AudioRaiseVolume)` | 增加音量       | `amixer -q -D pulse sset Master 5%+ unmute` |



* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L180-L182)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Shift + v` | 開啟音量控制面板 | `mate-volume-control`                       |


* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L268-L283)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + m`         | 音量切換成靜音   | `amixer -q -D pulse sset Master toggle`     |


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Ctrl + ,`  | 緩慢地減小音量   | `amixer -q -D pulse sset Master 1%- unmute` |
| `Alt + Ctrl + .`  | 緩慢地增加音量   | `amixer -q -D pulse sset Master 1%+ unmute` |




> TODO: Fix Not Work!

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- |
| `Alt + Shift + <` | 減小音量         | `amixer -q -D pulse sset Master 5%- unmute` |
| `Alt + Shift + >` | 增加音量         | `amixer -q -D pulse sset Master 5%+ unmute` |




## 用法對照

* [螢幕亮度控制](https://samwhelp.github.io/note-about-labwc/read/config/keybind/monitor-brightness-control.html)
