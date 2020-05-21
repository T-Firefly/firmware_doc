[TOC]


# Firmware update log

## 2020-05-16 
**AIO-RK3399PROC-UBUNTU18.04-GPT-20200518-1406.img.7z**

* NAME： AIO-RK3399PROC-UBUNTU18.04-GPT-20200518-1406.img.7z
* COMMIT： c37adabdd7124ea7c8f84c74f0c7ac76bd52ce5a
* MD5： 210a5e5ed0e626e11790e6c34ed6b7a4
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

**AIO-RK3399PROC-LVDS-UBUNTU18.04-GPT-20200518-1439.img.7z**

* NAME： AIO-RK3399PROC-LVDS-UBUNTU18.04-GPT-20200518-1439.img.7z
* COMMIT： c37adabdd7124ea7c8f84c74f0c7ac76bd52ce5a
* MD5： c14cfdc0733a5589cf7263e5f5446866
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
