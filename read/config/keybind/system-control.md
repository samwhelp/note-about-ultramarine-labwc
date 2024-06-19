---
title: 系統操作
nav_order: 5001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統操作

* [重新載入設定](#重新載入設定)
* [登出](#登出)
* [關機](#關機)




## 重新載入設定

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L151-L153)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + c`  | 重新載入設定 | `Reconfigure` (labwc 內建) |




## 登出

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L154-L159)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + x`  | 顯示離開選單 | `wlogout` |
| `Alt + Ctrl + x`  | 登出 | `Exit` (labwc 內建) |




## 關機

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L160-L168)

| 按鍵組合           | 功能        | 執行指令             |
| ----------------- | ------------ | -------------------- |
| `Alt + Shift + z`  | 顯示離開選單 | `wlogout` |
| `Alt + Ctrl + z`  | 關機 | `systemctl -i poweroff` |
| `Alt + Ctrl + Delete`  | 重開機 | `systemctl -i reboot` |
