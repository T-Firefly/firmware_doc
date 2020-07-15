[TOC]

# Firmware update log


## 2020-07-15

**AIO-3399-JD4-LVDS-UBUNTU18.04-GPT-20200715-1205.img.7z**
* NAME： AIO-3399-JD4-LVDS-UBUNTU18.04-GPT-20200715-1205.img.7z
* MD5： 5854805763f668c7f12c5266f54276a8
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-1-g2ed565c_20200617-1042_DESKTOP.img +

**AIO-3399-JD4-UBUNTU18.04-GPT-20200715-1154.img.7z**
* NAME： AIO-3399-JD4-UBUNTU18.04-GPT-20200715-1154.img.7z
* MD5： b3b7b8ff9f0ff649aac7c5ac23014ee4
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



## 2020-05-21
**AIO-3399-JD4-UBUNTU18.04-GPT-20200520-1740.img.7z**

* NAME： AIO-3399-JD4-UBUNTU18.04-GPT-20200520-1740.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 8241c310ca005a9f90b0cf7cbbb9b6e5
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**Update content:**
1. add npu_5801_power shell


# Firmware update log

## 2020-05-16
**AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 56711587d3cd42ca92bce3270c890452
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**AIO-3399-JD4-LVDS-UBUNTU18.04-GPT-20200516-1623.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 55295c8bf70770d97719fc5e9cde2e26
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