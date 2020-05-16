[TOC]


# Firmware update log

## 2020-05-16 
**ROC-RK3399-PC-EXP-UBUNTU18.04-GPT-20200516-1649.img.7z**

* NAME： ROC-RK3399-PC-EXP-UBUNTU18.04-GPT-20200516-1649.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： d580073ce9742d4c445850f726308e9d
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

**ROC-RK3399-PC-UBUNTU18.04-GPT-20200516-1644.img.7z**

* NAME： ROC-RK3399-PC-UBUNTU18.04-GPT-20200516-1644.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： cef45dfc27172a83d6a1a25d80ec1efb
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
