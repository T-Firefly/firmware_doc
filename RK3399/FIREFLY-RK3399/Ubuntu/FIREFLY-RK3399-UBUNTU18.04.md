[TOC]


# Firmware update log


## 2021-04-12
**FIREFLY-RK3399-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210408-1811.img.7z**
* NAME： FIREFLY-RK3399-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210408-1811.img.7z
* MD5：
```
adfcd9074cc2cf0e55fb5499fcea39ce FIREFLY-RK3399-UBUNTU-RK3399_UBUNTU_18.04_DESKTOP-GPT-20210408-1811.img.7z
```
* COMMIT：
    * kernel: 84223e13aa4344080ca3adeba1f2e7dd45951010
* FS:
    ubuntu_18.04_arm64_ext4_v2.04-1-g618089a_20210316-1035_DESKTOP.img

**Update content:**
1. Fix the problem that the delay time of the network gmac node does not match
2. Fix the file system audio and video dependency problem
3. Fix some problems with the camera


**FIREFLY-RK3399-UBUNTU18.04-MINIMAL-GPT-20200723-1629.img.7z**
* NAME： FIREFLY-RK3399-UBUNTU18.04-MINIMAL-GPT-20200723-1629.img.7z
* MD5： 48b7fae6571d8f62ea9a175fe47330e2
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

**FIREFLY-RK3399-UBUNTU18.04-GPT-20200714-1510.img.7z**
* NAME： FIREFLY-RK3399-UBUNTU18.04-GPT-20200714-1510.img.7z
* MD5： 967e6ba504b5d54439360f8660d2bdb3
* COMMIT：
    * kernel: f3ff609bcd46a36219a7865b0425b4eab990000d
    * rk3399-linux-bundle: 2b9f1109910a5c1e968994cb8edcd9b593233aed
* FS: ubuntu_18.04_arm64_ext4_v2.03-1-g2ed565c_20200617-1042_DESKTOP.img +

**Update content:**
1. Solve the lvds screen splash problem
2. kernel->spi: spi-wk2xxx: Fix the overflow problem of UART pressure test
3. fix enable TXREQUESTCLKHS before dw mipi dsi transfer
4. enable uboot logo for rk3399 lvds
5. rkisp update


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
