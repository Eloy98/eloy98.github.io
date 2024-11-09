---
title: Enter30构建指南
subtitle:
date: 2024-11-06T17:10:35+08:00
slug: ba41b4e
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
featuredImagePreview: "https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/c_crop,ar_16:9/v1730945913/keyboard/Enter30/B2F949AFC5ECBFA0092ABC305AD23D55_lxvequ.jpg"
tags:
  - 40%
  - qmk
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
## 一、组装
### 套件包含

>- 外壳*1
>- pcb*1
>- 夹心棉*1
>- 电池*1
>- usb小板（已安装到下壳）
>- 配件包

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.1_lcluc5.jpg">}}

### 需自备物品

> - 剪刀
> - 镊子
> - 轴体若干
> - 2u卫星轴*3

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.2_bubizh.jpg" caption="自备物品">}}

### 下盖处理
> [!todo]将配件包的棉条拿出，上下凸起处各贴4条，左右凸起处各1条（需自行剪开），如下图所示

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step2.2_q6q4yh.jpg" caption="下盖处理">}}

### 上盖处理（可选）
> [!todo]上盖对应凹槽处，贴对应数量的棉条

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step2.3_shqaad.jpg" caption="上盖处理">}}

### 插轴
> [!todo]将定位板、夹心棉和pcb（从上至下顺序）叠放在一起，插入轴体并安装卫星轴
 
{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.1_vkbygc.jpg" caption="插轴">}}


### 插线
> [!WARNING]将组好内胆翻转，插好usb线和电池线，接口顺序如下图所示

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.1_fbum9x.jpg" caption="电池接口方向">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.2_mgi3p6.jpg" caption="usb接口方向">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step3.2_lnsdsa.jpg" caption="插线">}}

### 组装上下盖
> [!todo]插好线之后，将内胆平放在下壳上，拿出上盖，与下壳压到一起

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.3_eoyli2.jpg" caption="组装上下盖">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.4_ydx8ko.jpg" caption="组装上下盖">}}

> [!todo]取出螺丝和螺丝刀，翻转键盘，拧好螺丝

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.5_ovcern.jpg" caption="拧螺丝">}}

## 二、设置蓝牙
> [!IMPORTANT]vial软件需要以下链接中的版本，其他版本会导致蓝牙相关键值乱码
### 软件下载
> [!todo]点击下方链接进入下载页面

{{< link "https://www.123684.com/s/WAltVv-1hZwh" "Vial_win" "Vial_win" true "fa-solid fa-download" >}}

### 软件操作
> [!todo]将键盘连接到电脑，打开vial软件

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.1_gsqxlu.png" caption="vial界面">}}

> [!todo]选择想要放置蓝牙配置的键盘层，下方选择Quantum选项卡，找到最下方的6个键值
>> - BLE0：蓝牙通道1
>> - BLE1：蓝牙通道2
>> - BLE2：蓝牙通道3
>> - BLE DEL；删除当前通道
>> - USB MODE: 切换键盘为usb模式
>> - RADIO MODE: 切换键盘为2.4G模式

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.2_ss7unl.png" caption="配置蓝牙按键">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.3_q4wtsh.png" caption="配置蓝牙按键">}}

> [!todo]返回第0层，设置一个切层按键，示例为切到第二层触发蓝牙

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.4_eg7vrb.png" caption="配置蓝牙按键">}}

### 蓝牙配对
> [!todo]拔出键盘usb线，打开电池开关，向上为打开，向下为关闭

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1730881618/keyboard/Enter30/step4.1_yviyuh.jpg" caption="蓝牙开关位置">}}

> [!todo]切层到蓝牙层，触发BLE0键值，此时键盘为蓝牙广播状态，打开电脑蓝牙，选择添加蓝牙设备

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.1_kws51d.png" caption="打开蓝牙">}}

> [!todo] 点击蓝牙

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.2_cj7zx8.png" caption="选择蓝牙">}}

> [!todo] 在蓝牙界面点击ENTER30_BLE_O

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.3_illkyz.png" caption="选择键盘">}}

> [!todo] 系统提示准备就绪之后，点击已完成

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.4_c07wzc.png" caption="完成配对">}}

### 蓝牙说明

> 1. Enter30一共支持3个蓝牙通道，对应的蓝牙设备名字为：**ENTER30_BLE_O**、**ENTER30_BLE_1**和**ENTER30_BLE_2**
> 2. Enter30从无线模式到有线模式，插线之后，需要触发**USB MODE**键值
> 3. Enter30从有线模式切换到无线模式，需要触发对应的通道键值
> 4. 如果当前通道需要绑定新设备，需要触发**BLE DEL**键值


