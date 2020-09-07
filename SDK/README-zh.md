# WeAct-ST7735 1.8-inch screen application

* [English](./README.md)

> 提供的代码仅适配本工作室的产品，其他的请自行设配

> 使用程序均在本工作室的产品所在的资料上，不单独提供，请谅解

> 代码仅设配1.8寸屏幕

## 使用说明

如果需要显示图片，Micropython开发需使用24位图片，C语言开发需使用16位图片。

C语言开发图片代码生成步骤

1. 首先需要一张对应屏幕的图片，例如128*160分辨率的24位bmp格式的图片

2. 使用当前文件夹下的转换软件`bmp24to16`,然后选择`RGB565`,最后转换

3. 使用当前文件夹下的C代码转换软件`Bin2C`,然后转换

## 源代码

STM32F103C8T6 C 语言HAL库开发使用代码 [F103-ST7735](https://gitee.com/WeActTC/BluePill-Plus/tree/master/SDK/STM32F103C8T6/HAL/F103_ST7735)

STM32F401CEU6 C 语言HAL库开发使用代码 [F401-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/STM32F401CEU6/HAL/06-F401_ST7735)

STM32F411CEU6 C 语言HAL库开发使用代码 [F411-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/STM32F411CEU6/HAL/F411_ST7735)

Micropython 开发使用代码 [micropython-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/MicroPython_Example/ST7735)
