---
title: 工作空間切換
nav_order: 5040
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 工作空間切換

* [我個人定義的工作空間](#我個人定義的工作空間)
* [循環切換](#循環切換)




## 我個人定義的工作空間

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L102-L108)

| 工作空間 | 名稱  |
| -------- | ----- |
| 1        | File  |
| 2        | Edit  |
| 3        | Web   |
| 4        | Term  |
| 5        | Misc  |




## 循環切換

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L220-L225)


| 按鍵組合  | 功能                 | 執行指令                   |
| --------- | -------------------- | -------------------------- |
| `Alt + a` | 切換到上一個工作空間 | `GoToDesktop` `left` (labwc 內建) |
| `Alt + s` | 切換到下一個工作空間 | `GoToDesktop` `right` (labwc 內建) |


> 也可以在「桌面」，使用「滑鼠中鍵」，上下滾動，切換「工作空間」。
