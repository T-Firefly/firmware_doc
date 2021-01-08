[TOC]


# Firmware update log


## 2021-1-8
**AIO-RK3399PROC-UBUNTU-MINIMAL-PYTHON3.5-RKNN-OPENCV-20210108-1500.img.7z**

* NAME： AIO-RK3399PROC-UBUNTU-MINIMAL-PYTHON3.5-RKNN-OPENCV-20210108-1500.img.7z
* KERNEL COMMIT： c29a5d0ea411a8689febcfb055ba0b341d03d59a
* MD5： 91a653f3e857672c9f3825574fe77be8
* FS: Firefly_Ubuntu_18.04.5_LTS_MINIMAL_ext4_202012301242_PYTHON3.5-RKNN-OPENCV.img

* kernel:
1. update

* FS:
1. Install PYTHON3.5 RKNN OPENCV


## 2021-1-8
**AIO-RK3399PROC-UBUNTU-PYTHON3.5-RKNN-OPENCV-20210108-1442.img.7z**

* NAME： AIO-RK3399PROC-UBUNTU-PYTHON3.5-RKNN-OPENCV-20210108-1442.img.7z
* KERNEL COMMIT： c29a5d0ea411a8689febcfb055ba0b341d03d59a
* MD5： bfa832fd984da3afe4caabb8be6b8433
* FS: Firefly_Ubuntu_18.04.5_LTS_DESKTOP_ext4_202012301242_PYTHON3.5-RKNN-OPENCV.img

* kernel:
1. update

* FS:
1. Install PYTHON3.5 RKNN OPENCV

## 2020-9-3
**AIO-RK3399PROC-UBUNTU18.04-MINIMAL-GPT-20200903-1549.img.7z**

* NAME： AIO-RK3399PROC-UBUNTU18.04-MINIMAL-GPT-20200903-1549.img.7z
* COMMIT： f54cc370e4314de048aa5adaad1fe1f4144d88bf
* MD5： 4a8de115d9219503f31507c5e2d0853d
* FS: use ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

**Update content:**
* rootfs:
1. use ubuntu_18.04_arm64_ext4_v2.03-10-g4c3ee72_20200717-1422_MINIMAL.img

## 2020-05-25

**AIO-RK3399PROC-UBUNTU18.04-GPT-20200525-1016.img.7z**

* NAME： AIO-RK3399PROC-UBUNTU18.04-GPT-20200525-1016.img.7z
* COMMIT： f54cc370e431
* MD5： 54ce92c5e6c70da02465664417f36c32
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img +

**Update content:**
* kernel:
1. rk3399pro-firefly-aiojd4.dts: delete-property for OV13850_0
2. firefly: remove isp video device when no mipi camera connect

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
