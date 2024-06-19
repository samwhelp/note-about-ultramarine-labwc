---
title: 螢幕截圖
nav_order: 5051
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 螢幕截圖

* [截圖](#截圖)
* [grimshot 用法](#grimshot-用法)




## 截圖

* [設定片段](https://github.com/samwhelp/ultramarine-labwc-adjustment/blob/main/prototype/main/labwc-config/Main/asset/overlay/etc/skel/.config/labwc/rc.xml#L343-L354)

| 按鍵組合      | 功能                 | 執行指令   |
| ------------- | -------------------- | ---------- |
| `Print`       | 螢幕截圖             | `grimshot save screen`    |
| `Alt + Print` | 選取目標物件截圖      | `grimshot save anything` |
| `Win + Print` | 目前聚焦視窗截圖      | `grimshot save active` |
| `Ctrl + Print` | 選取螢幕畫面區塊截圖  | `grimshot save area` |




## grimshot 用法

執行

``` sh
grimshot usage
```

顯示

```
Usage:
  grimshot [--notify] [--cursor] [--wait N] (copy|save) [active|screen|output|area|window|anything] [FILE|-]
  grimshot check
  grimshot usage

Commands:
  copy: Copy the screenshot data into the clipboard.
  save: Save the screenshot to a regular file or '-' to pipe to STDOUT.
  savecopy: Save the screenshot to a regular file and copy the data into the clipboard.
  check: Verify if required tools are installed and exit.
  usage: Show this message and exit.

Targets:
  active: Currently active window.
  screen: All visible outputs.
  output: Currently active output.
  area: Manually select a region.
  window: Manually select a window.
  anything: Manually select an area, window, or output.
```
