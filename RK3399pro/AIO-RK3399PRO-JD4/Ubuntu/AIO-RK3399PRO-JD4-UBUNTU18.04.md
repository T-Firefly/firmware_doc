[TOC]


# Firmware update log


## 2020-9-3
**AIO-RK3399PRO-JD4-UBUNTU18.04-MINIMAL-GPT-20200903-1600.img.7z**

* NAME： AIO-RK3399PRO-JD4-UBUNTU18.04-MINIMAL-GPT-20200903-1600.img.7z
* COMMIT： f54cc370e4314de048aa5adaad1fe1f4144d88bf
* MD5： 826f5ad206327c0cfde5587d903be3f6
* FS: use ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

**Update content:**
* rootfs:
1. use ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

## 2020-05-25
**AIO-RK3399PRO-JD4-UBUNTU18.04-GPT-20200518-1503.img.7z**

* NAME： AIO-RK3399PRO-JD4-UBUNTU18.04-GPT-20200525-1613.img.7z
* COMMIT： e4e481e8d837d3ce842dd3e3b1f5d5dbc1b72e79
* MD5： 5007056abb1dd133d85d8dfcb0aef1c4
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**rockdev/AIO-RK3399PRO-JD4-LVDS-UBUNTU18.04-GPT-20200525-1634.img.7z**

* NAME： rockdev/AIO-RK3399PRO-JD4-LVDS-UBUNTU18.04-GPT-20200525-1634.img.7z
* COMMIT： bfea929f475879719eff0b4b309a4281
* MD5： 5007056abb1dd133d85d8dfcb0aef1c4
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**Update content:**
* kernel:
1. dts: Fixed an issue with ov13850 on the rk3399pro-firefly-aiojd4 board.
2. rk3399pro-firefly-aiojd4.dts: delete-property for OV13850_0
3. remove isp video device when no mipi camera connect


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
