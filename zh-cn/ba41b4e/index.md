# Enter30构建指南


&lt;!--more--&gt;
## 一、组装
### 套件包含

&gt;- 外壳*1
&gt;- pcb*1
&gt;- 夹心棉*1
&gt;- 电池*1
&gt;- usb小板（已安装到下壳）
&gt;- 配件包

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.1_lcluc5.jpg&#34;&gt;}}

### 需自备物品

&gt; - 剪刀
&gt; - 镊子
&gt; - 轴体若干
&gt; - 2u卫星轴*3

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881529/keyboard/Enter30/step1.2_bubizh.jpg&#34; caption=&#34;自备物品&#34;&gt;}}

### 下盖处理
&gt; [!todo]将配件包的棉条拿出，上下凸起处各贴4条，左右凸起处各1条（需自行剪开），如下图所示

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step2.2_q6q4yh.jpg&#34; caption=&#34;下盖处理&#34;&gt;}}

### 上盖处理（可选）
&gt; [!todo]上盖对应凹槽处，贴对应数量的棉条

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step2.3_shqaad.jpg&#34; caption=&#34;上盖处理&#34;&gt;}}

### 插轴
&gt; [!todo]将定位板、夹心棉和pcb（从上至下顺序）叠放在一起，插入轴体并安装卫星轴
 
{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.1_vkbygc.jpg&#34; caption=&#34;插轴&#34;&gt;}}


### 插线
&gt; [!WARNING]将组好内胆翻转，插好usb线和电池线，接口顺序如下图所示

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.1_fbum9x.jpg&#34; caption=&#34;电池接口方向&#34;&gt;}}

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881610/keyboard/Enter30/step5.2_mgi3p6.jpg&#34; caption=&#34;usb接口方向&#34;&gt;}}

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881611/keyboard/Enter30/step3.2_lnsdsa.jpg&#34; caption=&#34;插线&#34;&gt;}}

### 组装上下盖
&gt; [!todo]插好线之后，将内胆平放在下壳上，拿出上盖，与下壳压到一起

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.3_eoyli2.jpg&#34; caption=&#34;组装上下盖&#34;&gt;}}

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881612/keyboard/Enter30/step3.4_ydx8ko.jpg&#34; caption=&#34;组装上下盖&#34;&gt;}}

&gt; [!todo]取出螺丝和螺丝刀，翻转键盘，拧好螺丝

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/c_fit,q_50,w_1200/v1730881613/keyboard/Enter30/step3.5_ovcern.jpg&#34; caption=&#34;拧螺丝&#34;&gt;}}

## 二、设置蓝牙
&gt; [!IMPORTANT]vial软件需要以下链接中的版本，其他版本会导致蓝牙相关键值乱码
### 软件下载
&gt; [!todo]点击下方链接进入下载页面

{{&lt; link &#34;https://www.123684.com/s/WAltVv-1hZwh&#34; &#34;Vial_win&#34; &#34;Vial_win&#34; true &#34;fa-solid fa-download&#34; &gt;}}

### 软件操作
&gt; [!todo]将键盘连接到电脑，打开vial软件

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.1_gsqxlu.png&#34; caption=&#34;vial界面&#34;&gt;}}

&gt; [!todo]选择想要放置蓝牙配置的键盘层，下方选择Quantum选项卡，找到最下方的6个键值
&gt;&gt; - BLE0：蓝牙通道1
&gt;&gt; - BLE1：蓝牙通道2
&gt;&gt; - BLE2：蓝牙通道3
&gt;&gt; - BLE DEL；删除当前通道
&gt;&gt; - USB MODE: 切换键盘为usb模式
&gt;&gt; - RADIO MODE: 切换键盘为2.4G模式

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.2_ss7unl.png&#34; caption=&#34;配置蓝牙按键&#34;&gt;}}

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.3_q4wtsh.png&#34; caption=&#34;配置蓝牙按键&#34;&gt;}}

&gt; [!todo]返回第0层，设置一个切层按键，示例为切到第二层触发蓝牙

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731054755/keyboard/Enter30/key1.4_eg7vrb.png&#34; caption=&#34;配置蓝牙按键&#34;&gt;}}

### 蓝牙配对
&gt; [!todo]拔出键盘usb线，打开电池开关，向上为打开，向下为关闭

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1730881618/keyboard/Enter30/step4.1_yviyuh.jpg&#34; caption=&#34;蓝牙开关位置&#34;&gt;}}

&gt; [!todo]切层到蓝牙层，触发BLE0键值，此时键盘为蓝牙广播状态，打开电脑蓝牙，选择添加蓝牙设备

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.1_kws51d.png&#34; caption=&#34;打开蓝牙&#34;&gt;}}

&gt; [!todo] 点击蓝牙

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.2_cj7zx8.png&#34; caption=&#34;选择蓝牙&#34;&gt;}}

&gt; [!todo] 在蓝牙界面点击ENTER30_BLE_O

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.3_illkyz.png&#34; caption=&#34;选择键盘&#34;&gt;}}

&gt; [!todo] 系统提示准备就绪之后，点击已完成

{{&lt; image src=&#34;https://res.cloudinary.com/dref0olos/image/upload/v1731056134/keyboard/Enter30/bl1.4_c07wzc.png&#34; caption=&#34;完成配对&#34;&gt;}}

### 蓝牙说明

&gt; 1. Enter30一共支持3个蓝牙通道，对应的蓝牙设备名字为：**ENTER30_BLE_O**、**ENTER30_BLE_1**和**ENTER30_BLE_2**
&gt; 2. Enter30从无线模式到有线模式，插线之后，需要触发**USB MODE**键值
&gt; 3. Enter30从有线模式切换到无线模式，需要触发对应的通道键值
&gt; 4. 如果当前通道需要绑定新设备，需要触发**BLE DEL**键值




---

> 作者: xiix  
> URL: http://localhost:1313/zh-cn/ba41b4e/  

