# Stavona R V2 使用指南/Guide
[V1更换IO板戳我](https://github.com/HajiAIqaq/Stavona-R-Guide/blob/main/%E6%9B%B4%E6%8D%A2IO%E6%9D%BF/Stavona%20R%20V1%20%E6%9B%B4%E6%8D%A2IO%E6%9D%BF%E8%AF%A6%E7%BB%86%E6%8C%87%E5%8D%97.md)
### 特点/Features

- 独有的外壳设计，外形更加炫酷
- USB Type-B 接口，连接更加坚固稳定
- 多次迭代的触摸算法，与Ground Slider同样的触发检测
- 结实的内部结构，保证了游玩时的低噪音和稳定性

## 简易安装游玩教程

1. 开箱并组装手台
2. 调节手台软件设置
3. 游戏软件设置

## 开箱并组装手台/Unbox & Mount

首先从包装箱里取出控制器，平放到桌面上。取出两个高度感应器，将触摸板部分的扎带取下，小心的将连接线卡入槽中，听到“咔”的一声即为安装到位，并将长出来的部分连接线塞回控制器内。使用附送的手拧螺丝将高度感应器固定在控制器上，通过Type-B线材连接至您的电脑
<img src="Air连接.jpg">



> [!WARNING]
>
> 如果您是**台式机**，请将手台连接到主板后的USB接口
>
> 如果您是**笔记本**，请将手台连接到笔记本原有的USB接口，不要使用拓展坞
>
> 良好的连接是您保证游玩体验的基础，请确保控制器的供电和通信良好！

## 调节手台软件设置/Settings

Stavona R V2已支持WebHID控制中心

[Stavona R 控制中心](https://terminal.kairotech.net/stavona-r)

请通过网页控制中心调节所需模式

<img src="控制中心.png">

**键盘模式**支持设置键盘映射以支持多种节奏游戏，**HID模式**是专属于CHUNITHM的游玩模式

## 游戏软件设置/Game settings

如果您还没下载游戏

[Performai Manual](https://performai.evilleaker.com/manual/)

假设您已经下载好游戏并完成了键盘操作的基本启动设置，请于Release下载最新的StavonaIO.dll，并在控制中心中将手台的操作模式调节至HID

以下是segatools.ini设置

```
[chuniio]
; If you wish to sideload a different chuniio, specify the DLL path here
path=StavonaIO.dll
[StavonaIO]
reportTime=20
```

> [!NOTE]
>
> 适用于"V1触摸算法"的额外设置



打开游戏，按手台功能区的第一个按钮进入Test模式，通过功能区按钮或触摸板，在游戏的测试选项中选择メインデバイス設定

<img src="游戏测试01.png">

调节しきい值为40

<img src="游戏测试02.png">

选择終了，返回游戏开始页面，Enjoy your controller！



CHUNITHM及其商标**®**版权应于SEGA所有，对其软件的使用，修改等行为具有法律风险，软件仅供学习交流使用
