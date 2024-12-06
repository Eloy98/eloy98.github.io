---
title: Enter30 Build Guide
subtitle:
date: 2024-11-06T17:10:41+08:00
slug: e543ce3
draft: false
type: posts
author:
  name:
  link:
  email:
  avatar:
description:
keywords:
license:
comment: false
weight: 1
featuredImagePreview: "https://res.cloudinary.com/dref0olos/image/upload/q_50/v1730945913/keyboard/Enter30/B2F949AFC5ECBFA0092ABC305AD23D55_lxvequ.jpg"
tags:
  - 40%
  - qmk
categories:
  - doc
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
## 一、Assembly
### Kit Includes

>- Shell *1
>- PCB *1
>- Foam *1
>- Battery *1
>- USB small board (pre-installed in the bottom shell)
>- Strap *1
>- Accessory pack

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.1_lcluc5.jpg">}}

### Items to Prepare

> - Scissors
> - Tweezers
> - Several switches
> - 2U satellite switches *3

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.2_bubizh.jpg" caption="Items to Prepare">}}

### Bottom Shell Processing
> [!todo]Take out the foam strips from the accessory pack, stick 4 strips on the top and bottom protrusions, and 1 strip on each side protrusion (need to cut them open yourself), as shown in the image below.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step2.2_q6q4yh.jpg" caption="Bottom Shell Processing">}}

### Top Shell Processing (Optional)
> [!todo]Stick the corresponding number of foam strips in the grooves on the top shell.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step2.3_shqaad.jpg" caption="Top Shell Processing">}}

### Insert Switches
> [!todo]Stack the positioning plate, foam, and PCB (in that order), insert the switches, and install the satellite switches.
 
{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.1_vkbygc.jpg" caption="Insert Switches">}}


### Connect Wires
> [!WARNING] Flip the assembled inner shell, connect the USB cable and battery cable, the interface order is as shown in the image below.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.1_fbum9x.jpg" caption="Battery Interface Direction">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.2_mgi3p6.jpg" caption="USB Interface Direction">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step3.2_lnsdsa.jpg" caption="Connect Wires">}}

### Assemble Top and Bottom Shells
> [!todo]After connecting the wires, lay the inner shell flat on the bottom shell, take out the top shell, and press it together with the bottom shell.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.3_eoyli2.jpg" caption="Assemble Top and Bottom Shells">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.4_ydx8ko.jpg" caption="Assemble Top and Bottom Shells">}}

> [!todo] Take out the screws and screwdriver, flip the keyboard over, and tighten the screws.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.5_ovcern.jpg" caption="Tighten Screws">}}

## 二、Set Up Bluetooth
> [!IMPORTANT] The Vial software requires the version from the link below; other versions may cause Bluetooth-related key values to be garbled.
### Software Download
> [!todo] Click the link below to access the download page.

{{< link "https://drive.google.com/drive/folders/1WWxKntgUshDlofq6pLYYpML3d8jF486k?usp=sharing" "Vial" "Vial" true "fa-solid fa-download" >}}

### Software Operation
> [!todo] Connect the keyboard to the computer and open the Vial software.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.1_gsqxlu.png" caption="Vial Interface">}}

> [!todo] Select the keyboard layer where you want to place the Bluetooth configuration, then select the Quantum tab below, and find the last 6 key values.
>> - BLE0：Bluetooth Channel 1
>> - BLE1：Bluetooth Channel 2
>> - BLE2：Bluetooth Channel 3
>> - BLE DEL；Delete the current channel
>> - USB MODE: Switch the keyboard to USB mode
>> - RADIO MODE: Switch the keyboard to 2.4G mode

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.2_ss7unl.png" caption="Configure Bluetooth Keys">}}

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.3_q4wtsh.png" caption="Configure Bluetooth Keys">}}

> [!todo] Return to layer 0, set a layer switch key, for example, to switch to the second layer to trigger Bluetooth.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.4_eg7vrb.png" caption="Configure Bluetooth Keys">}}

### Bluetooth Pairing
> [!todo]Unplug the keyboard USB cable, turn on the battery switch, up is on, down is off.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1730881618/keyboard/Enter30/step4.1_yviyuh.jpg" caption="Battery Switch Position">}}

> [!todo]Switch to the Bluetooth layer, trigger the BLE0 key value, at this point the keyboard is in Bluetooth broadcasting mode, open the computer Bluetooth settings, and select to add a Bluetooth device.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.1_kws51d.png" caption="Open Bluetooth">}}

> [!todo] Click on Bluetooth.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.2_cj7zx8.png" caption="Select Bluetooth">}}

> [!todo] Click on ENTER30_BLE_O in the Bluetooth interface.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.3_illkyz.png" caption="Select Keyboard">}}

> [!todo] After the system prompts that it is ready, click Complete.

{{< image src="https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.4_c07wzc.png" caption="Complete Pairing">}}

### Bluetooth Instructions

> 1. The Enter30 supports a total of 3 Bluetooth channels, corresponding Bluetooth device names are: **ENTER30_BLE_0**, **ENTER30_BLE_1**, and **ENTER30_BLE_2**.
> 2. To switch from wireless mode to wired mode, after plugging in the cable, you need to trigger the **USB MODE** key value.
> 3. To switch from wired mode to wireless mode, you need to trigger the corresponding channel key value.
> 4. If the current channel needs to bind a new device, you need to trigger the **BLE DEL** key value.