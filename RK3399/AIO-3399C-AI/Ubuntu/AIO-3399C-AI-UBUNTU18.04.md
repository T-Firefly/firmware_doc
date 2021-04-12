
[TOC]


# Firmware update log

## 2021-04-12
**AIO-3399C-AI-*.img.7z**
* NAME： AIO-3399C-AI-*.img.7z
* MD5：
```
155bce53713020bce8a5c4baf5f7c087 AIO-3399C-AI-LVDS-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210412-1018.img.7z
0b7287da5182c89df492b0ce15191efc AIO-3399C-AI-LVDS-UBUNTU-RK3399_UBUNTU_18.04_MINIAL-GPT-20210412-1026.img.7z
4c36199463644e349b805ce4f0cdc050 AIO-3399C-AI-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210412-1020.img.7z
991baf26c6e60304b811f1ead7ebaba4 AIO-3399C-AI-UBUNTU-RK3399_UBUNTU_18.04_MINIAL-GPT-20210412-1029.img.7z
```
* COMMIT：
    * kernel: 84223e13aa4344080ca3adeba1f2e7dd45951010
* FS:
    ubuntu_18.04_arm64_ext4_v2.03-28-g6eebc47_20201204-0941_MINIMAL.img
    ubuntu_18.04_arm64_ext4_v2.04-1-g618089a_20210316-1035_DESKTOP.img

**Update content:**
1. Fix the problem that the delay time of the network gmac node does not match
2. Fix the file system audio and video dependency problem
3. Fix some problems with the camera


## 2020-05-16
**AIO-3399C-AI-UBUNTU18.04-GPT-20200516-1556.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 1a9ff82d7194820fec9c1186e1890c5e
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**AIO-3399C-AI-LVDS-UBUNTU18.04-GPT-20200516-1601.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 944f014c16ea9ba01c6d00720281a8f8
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