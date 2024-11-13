---
title: "Cocot46p构建指南"
subtitle: ""
date: 2024-11-13T11:29:34+08:00
slug: 5rer4g
draft: false
type: posts
author:
  name: xiix
  link:
  email: eloy1172240653@gmail.com
  avatar: 
description:
keywords:
license:
comment: false
weight: 1
featuredImagePreview: "https://res.cloudinary.com/dref0olos/image/upload/q_50/v1731469274/keyboard/Cocot46/sample2_cawd0q.jpg"
tags:
  - 40%
  - zmk
  - ortho
  - trackball
categories:
  - 教程
hiddenFromHomePage: false
hiddenFromSearch: false
hiddenFromRelated: false
hiddenFromFeed: false
summary:
resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: false
lightgallery: true
password:
message:
repost:
  enable: true
  url:
# See details front matter: https://fixit.lruihao.cn/documentation/content-management/introduction/#front-matter
---  
<!--more-->

# 一、使用介绍
### 硬件
> [!IMPORTANT] Cocot46采用zmk固件，电池开关在typeC右侧，往左是关闭，往右是开启

> [!IMPORTANT] 充电提示灯在typeC左侧，充电需打开电池开关，正在充电为常亮，充满熄灭

### 软件
> [!todo] 改键之前，需要fork键盘仓库，以下是仓库链接

{{< link "https://github.com/Eloy98/zmk-for-cocot46p" "cocot46仓库" "cocot46仓库" true "fa-solid fa-link" >}}

>[!todo] 如何进行绑定仓库和常规改键，请参考下面的文档

{{< link "https://www.123684.com/s/WAltVv-uAZwh" "zmk文档" "zmk文档" true "fa-solid fa-download" >}}

>[!todo] 软重启，由于重置按钮在背面，zmk需要频繁刷写固件，默认为如下键位触发刷机模式，如需更改键值，请在改键网站中修改*&bootloader*的位置即可

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/q_50/v1731490037/keyboard/Cocot46/bl_c2bete.png" caption="软重启">}}

>[!todo] 默认键位

{{< image src="/images/cocot46p.svg" caption="默认键位">}}

# 二、轨迹球配置说明
> [!todo] 默认DPI设置，默认为800，如需修改，请修改以下配置

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.conf
...
#PMW3610 的默认CPI为800, 区间：200~3200，步长200，依次为200,400,600，...
CONFIG_PMW3610_CPI=800
...
```

> [!todo] 滚轮模拟，默认开启，启动层为Lower层，如需修改触发层，请修改以下配置

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.overlay
...
/*scroll_layer*/
/*default is <1>~<4>*/
scroll-layers = <1>;
...
```

> [!todo]球动层动，默认关闭，开启之后，可以实现轨迹球滚动过程中，键盘自动切到特定层，如需开启，取消如下的代码注释

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.overlay
...
/*default is <1>~<4>*/
/*automouse-layer = <2>;*/ => automouse-layer = <2>
...

```

>[!todo] 球动层动停留时间，默认为400ms，如需修改时长，请修改以下配置

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.conf
...
#使用轨迹球后鼠标层将保持活动的毫秒数
CONFIG_PMW3610_AUTOMOUSE_TIMEOUT_MS=400
...
```

>[!todo] 狙击层设置，默认开启，可以实现触发到特定层，DPI降速，已达到更加精确的点击。启动层为Snipe层，如需修改触发层，请修改以下配置

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.overlay
...
/*snipe_layer*/
/*default is <1>~<4>*/
snipe-layers = <4>;
...

```

>[!todo] 狙击层DPI设置，默认为200，如需修改，请修改以下配置

``` {data-open=false}
#/config/boards/shields/cocot46p/cocot46p.conf
...
# 配置狙击层CPI
CONFIG_PMW3610_SNIPE_CPI=200
...
```