# cartographer_rosinstall

[![Build Status](https://travis-ci.com/ros-perception/slam_gmapping.svg?branch=melodic-devel)](https://travis-ci.org/ros-perception/slam_gmapping)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](./LICENSE)
[![Release](https://img.shields.io/badge/release-v1.0-blue)](https://github.com/JoveH-H/cartographer_rosinstall/releases/tag/v1.0)
[![Author](https://img.shields.io/badge/Author-Jove-%2300a8ff)](https://github.com/JoveH-H)
===
使用wstool工具下载cartographer软件包
```
wstool init src
wstool merge -t src https://gitcode.net/qq_32618327/cartographer_rosinstall/raw/main/cartographer_ros.rosinstall
wstool update -t src
``` 
详情参考：[《SLAM Cartographer（1）框架与安装》](https://joveh-h.blog.csdn.net/article/details/123045666)
