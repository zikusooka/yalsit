![Twitter](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40jzikusooka)](https://twitter.com/jzikusooka)
![alt text](screenshots/yalsit.png "Yet Another Linux System Information Tool (YALSIT)")
![alt text](screenshots/yalsit.jpg "YALSIT")

Introduction
------------
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40jzikusooka)](https://twitter.com/jzikusooka)

Here's Yet Another Linux System Information Tool (YALSIT) I wrote for
our Linux based Jambula smart home hub systems. 

Use it on any Linux system to generate system information such as: System Model/Serial Number, Kernel Software Version, Hardware (CPU, GPU, Memory, Disks), Networking information, Current WiFi/Internet status, GeoLocation, etc.

Prerequisites: 
* systemd 
* dmidecode

* Available on most major Linux distributions


Usage:
Please run as root. i.e. sudo ./yalsit


**NOTE:** This script was tested using Fedora Linux distro

For updates to this, and other CLI tools, please follow me on twitter: **[@jzikusooka](@jzikusooka)** or email me at *josephzik AT gmail.com*

Your contributions are welcome.  For bug fixes, please open an issue


Devices known to work
---------------------
(Tested)
- Huawei E5373s-155
- Huawei B529s-23a

(Not yet Tested)
- Huawei B310s

Supported Platforms
-------------------
- Linux
- Mac OS
- FreeBSD? (Not yet tested)

Requirements
------------
1. coreutils 8+ packages with base64 and sha256sum utilities


Usage
------
Usage: ./query_huawei_wifi_router.sh [IP_ADDRESS] [LOGIN_USER] [LOGIN_PASSWORD][TASK (Optional)]

  e.g. ./query_huawei_wifi_router.sh 192.168.8.1 admin secret info_all

Tasks
-----
info_all

battery

data

users

sms_read

sms_send [NUMBER] [MESSAGE]

reboot
