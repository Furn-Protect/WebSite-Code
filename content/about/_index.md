---
title: "About"
description: "We team has 4 members in total, and we designed this project.\n Furniture protector is primarily designed for proactive identification and repelling of pet cats."
featured_image: '/images/5824d020d4e148d2a5dedc5bd30a1afe.jpg'
weight: 1

---
<!-- {{< figure src="/images/Victor_Hugo-Hunchback.jpg" title="Illustration from Victor Hugo et son temps (1881)" >}} -->

FurnProt(Furniture Protector) 由项目组的4为成员共同开发，成员分别为王麒舒，欧阳成来，欧阳晓怿和指导教师Alkdis Chen。

我们的项目目前的主要功能为，通过软件识别与硬件设备（行空板），实现主动识别猫咪，并进行驱赶。

具体地说，该方案包括以下几个方面：

1. 摄像头：我们使用了一款低清摄像头，尽管分辨率不高，但足以满足初期的监测需求。摄像头可以捕捉猫咪的动作，将视频数据传输到后续的处理环节。

2. Python脚本：我们编写了一个监控程序，用于实时监测猫咪抓沙发的情况。该程序通过读取摄像头采集的视频流，使用图像处理技术来分析视频中的猫咪是否在抓沙发。一旦发现猫咪抓沙发，程序就会立即向决策程序发送警报信号。

3. 决策程序：决策程序是整个项目的核心部分，它负责根据猫咪抓沙发的行为做出决策。例如，如果猫咪已经开始抓沙发，那么决策程序就会命令硬件运动模块执行驱赶猫咪的操作。决策程序的设计需要考虑各种情况下的猫咪抓沙发行为，并根据实际情况进行灵活调整。

4. 硬件运动模块：硬件运动模块包括舵机等组件，它们可以通过遥控器或自主控制器来控制它们的运动。在这个项目中，我们采用了逗猫棒来驱散猫咪，避免其继续抓沙发。逗猫棒可以通过手动控制或自动控制来移动，从而引导猫咪离开沙发区域。我们使用一个舵机来控制逗猫棒，使其能够根据视频监控和分析结果做出相应的运动，从而达到更好的逗猫效果。
