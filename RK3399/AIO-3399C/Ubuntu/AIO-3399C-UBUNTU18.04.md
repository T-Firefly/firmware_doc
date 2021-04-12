[TOC]


# Firmware update log

## 2021-04-12
**AIO-3399C-*.img.7z**
* NAME： AIO-3399C-*.img.7z
* MD5：
```
173d91712a660487abc61ae2de6182ef AIO-3399C-LVDS-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210412-1021.img.7z
257ee30a8ad0f9fb8a656e5e591b15b4 AIO-3399C-LVDS-UBUNTU-RK3399_UBUNTU_18.04_MINIAL-GPT-20210412-1030.img.7z
cfbc181df50a9679fa98712743913c74 AIO-3399C-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210412-1022.img.7z
718085c15891edfac0eb5c38a1f098d5 AIO-3399C-UBUNTU-RK3399_UBUNTU_18.04_MINIAL-GPT-20210412-1031.img.7z
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


## 2020-07-23

**AIO-3399C-UBUNTU18.04-MINIMAL-GPT-20200723-1649.img.7z**
* NAME： AIO-3399C-UBUNTU18.04-MINIMAL-GPT-20200723-1649.img.7z
* MD5： 8dc8b431f38245d4fe05a9d1f5656ffd
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

**AIO-3399C-UBUNTU18.04-GPT-20200715-1446.img.7z**
* NAME： AIO-3399C-UBUNTU18.04-GPT-20200715-1446.img.7z
* MD5： b55987afb364f20b9316315a36eb2352
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-1-g2ed565c_20200617-1042_DESKTOP.img +

**AIO-3399C-LVDS-UBUNTU18.04-GPT-20200715-1429.img.7z**
* NAME： AIO-3399C-LVDS-UBUNTU18.04-GPT-20200715-1429.img.7z
* MD5： 3a59286310476f61a817b29681be7360
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
**AIO-3399C-UBUNTU18.04-GPT-20200516-1524.img.7z**

* NAME： AIO-3399C-UBUNTU18.04-GPT-20200516-1524.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 4cbd50577d332aa982f5be72ded47ee8
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**AIO-3399C-LVDS-UBUNTU18.04-GPT-20200516-1541.img.7z**

* NAME： AIO-3399C-LVDS-UBUNTU18.04-GPT-20200516-1541.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： da1c3f01d7097254ad85f457bab9c51e
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
