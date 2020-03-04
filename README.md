# 4 位数码管显示模块 (TM1650)
makecode 4 位数码管显示 (TM1650) 的 microbit 软件包  

4 位数码管显示是由 4 个 7 段 LED 数码管组成，可以显示数字、时间、日期等。这个软件包支持使用了 I2C 接口的 TM1650 芯片。  

作者: chcyd  
日期: 2020年3月  

![](./icon.png)  

## 使用方法

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  

https://github.com/chcyd/TM1650_cn  

搜索后就可以添加并使用本软件包了。  

![](./4-LED.jpg)

## API

- **on()**  
打开显示功能。  

- **off()**  
关闭显示功能（不会影响显示内容）。  

- **clear()**  
清除显示的内容。  

- **digit(num: number, bit: number)**  
在指定位置显示一个数字，数字的范围是 0-15。  

- **showNumber(num: number)**  
显示一个整数，可以是负数。  

- **showHex(num: number)**  
以16进制方式显示整数。  

- **showDpAt(bit: number, show: boolean)**  
显示或隐藏小数点  
bit 代表小数点的位置, [0 - 3]  
show, 代表显示或隐藏, true时显示，false时隐藏  

- **setIntensity(dat: number)**  
设置显示亮度。  
dat 代表亮度，范围是 0 - 8，0代表关闭，8代表最亮。  

## 演示

![](./demo.jpg)

## 授权方式  

MIT

microbit

## 支持硬件

* for PXT/microbit
