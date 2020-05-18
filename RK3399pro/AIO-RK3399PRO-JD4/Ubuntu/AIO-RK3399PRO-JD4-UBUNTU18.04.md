[TOC]


# Firmware update log

## 2020-05-16 
**AIO-RK3399PRO-JD4-UBUNTU18.04-GPT-20200518-1503.img.7z**

* NAME： AIO-RK3399PRO-JD4-UBUNTU18.04-GPT-20200518-1503.img.7z
* COMMIT： c37adabdd7124ea7c8f84c74f0c7ac76bd52ce5a
* MD5： c4f8e7476fb77f4b760df84909c41ee9
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

**AIO-RK3399PRO-JD4-LVDS-UBUNTU18.04-GPT-20200518-1550.img.7z**

* NAME： AIO-RK3399PRO-JD4-LVDS-UBUNTU18.04-GPT-20200518-1550.img.7z
* COMMIT： c37adabdd7124ea7c8f84c74f0c7ac76bd52ce5a
* MD5： ba3c960a6f93cf9aebe9183a35cb231d
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

**Update content:**
* kernel:
1. fix enable TXREQUESTCLKHS before dw mipi dsi transfer
2. enabled uboot logo for rk3399pro lvds
3. arm64: dts: Enable typec0 vbus

* FS:
1. Install libopencv-contrib-dev
2. Install firefly-multi-rtsp
3. Install firefly-3399pronpu-driver
4. Fix mipi camera preview issue
5. System startup related issues
