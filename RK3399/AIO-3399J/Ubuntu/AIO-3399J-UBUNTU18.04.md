
[TOC]


# Firmware update log


## 2020-07-15

**AIO-3399J-UBUNTU18.04-GPT-20200715-0956.img.7z**
* NAME： AIO-3399J-UBUNTU18.04-GPT-20200715-0956.img.7z
* MD5： 6192d163c857b95fe7abef7c0c58341b
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-1-g2ed565c_20200617-1042_DESKTOP.img +

**AIO-3399J-LVDS-UBUNTU18.04-GPT-20200715-1033.img.7z**
* NAME： AIO-3399J-LVDS-UBUNTU18.04-GPT-20200715-1033.img.7z
* MD5： 4cc217ccd62fb87d0b881d02cb5fdc21
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-1-g2ed565c_20200617-1042_DESKTOP.img +


**Update content:**
1. Solve the lvds screen splash problem
1. kernel->spi: spi-wk2xxx: Fix the overflow problem of UART pressure test
1. fix enable TXREQUESTCLKHS before dw mipi dsi transfer
1. enable uboot logo for rk3399 lvds
1. rkisp update


## 2020-05-16
**AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： dac5c9a27c068630bdda1b5f026ed6e2
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**AIO-3399J-LVDS-UBUNTU18.04-GPT-20200516-1433.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 1700078d0ba45a2311b5b11838933501
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img

**Update content:**
* kernel:
1. remove isp video device when no mipi camera connect
2. enable framebuffer console

* FS:
1. Install libopencv-contrib-dev
2. Install firefly-multi-rtsp
3. Install firefly-3399pronpu-driver
4. Fix mipi camera preview issue
5. System startup related issues