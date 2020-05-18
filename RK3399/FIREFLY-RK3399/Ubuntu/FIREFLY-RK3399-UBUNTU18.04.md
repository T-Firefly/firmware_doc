[TOC]


# Firmware update log

## 2020-05-16 
**FIREFLY-RK3399-UBUNTU18.04-GPT-20200518-1020.img.7z**

* NAME： FIREFLY-RK3399-UBUNTU18.04-GPT-20200518-1020.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： c8e18232bba43846f2420c5c28237795
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

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
