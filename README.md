# NTC
makecode 的 NTC温度传感器 microbit 软件包

* 作者: 朱林 
* 日期: 2018/4  

![image](https://github.com/zhuning239/NTC/blob/master/icon.png)


## 使用方法

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  

https://github.com/zhuning239/NTC/

搜索后就可以添加并使用本软件包了。  

![image](https://github.com/zhuning239/NTC/blob/master/sketch.jpg)


## API

- **set**(B: NTC_B)  
B 是 NTC 传感器的系数，这里可以选择 3380 或 3950。  

- **Temperature**(adc: number)  
adc 是模拟输入转换后的数值，返回值是按照摄氏度为单位的温度。  

## 演示

![image](https://github.com/zhuning239/NTC/blob/master/demo.jpg)

## 授权方式

* MIT
* 湖南创乐博智能科技有限公司

## 支持硬件

* for PXT/microbit

