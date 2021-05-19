# AndroidRomTampering:

The patch file is mainly used to remove 
a variety of interaction that hinder automatic test.

## Features:

| # | Description |  test case   | Status |
| :----: |  :----  |  :----:  | :----: |
|1| auto grant permission | - | DONE |
|2| remove the annoying message: This app was built for an older version of Android and may not work properly. Try checking for updates or contact the developer. | - | DONE |
|3| bypass these use WindowManager.LayoutParams.FLAG_SECURE to prevent taking snapshot. | - | DONE |
|4| bypass root detector | 1 | DONE |
|5| remove system prompt | 2 | DONE |
|6| remove footer and header | - | DONE |
|7| turn off screen saver | - | DONE |
|8| INSTALL_FAILED_NO_MATCHING_ABIS: Failed to extract native libraries, res=-113 | 3 | |
|9| remove Toast window | - | DONE |
|10| allow screenshots | - | DONE |

## Howto: 

1. follow the instruction of `https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/`, use branch `android-11.0.0_r27`, e.g., `repo init -u http://mirrors.tuna.tsinghua.edu.cn/git/AOSP/platform/manifest -b android-11.0.0_r27`

2. apply the patch `android-11.0.0_r27.diff` or modify the source follows `android-11.0.0_r27.diff`.
