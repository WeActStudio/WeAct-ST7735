# WeAct-ST7735 1.8寸屏 使用程序

* [中文版本](./README-zh.md)

> The code provided is only suitable for the products of WeAct studio, others should be provided by yourself

> Please understand that the use procedures are not provided separately on the materials where the products are located in the studio

> The code is equipped with a 1.8-inch screen only

## Instructions for use

If you need to display images, Micropython development use 24-bit images and C language development use 16-bit images.

C language development picture code generation steps

1. First, we need a picture corresponding to the screen, such as a picture in the format of 24-bit BMP with 128*160 resolution
2. Use the conversion software `BMP24TO16` under the current folder, then select `RGB565`, and finally convert
3. Use the C code conversion software `Bin2C` under the current folder, and then convert

STM32F103C8T6 C HAL library development use code [F103-ST7735](https://gitee.com/WeActTC/BluePill-Plus/tree/master/SDK/STM32F103C8T6/HAL/F103_ST7735)

STM32F401CEU6 C HAL library development use code [F401-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/STM32F401CEU6/HAL/06-F401_ST7735)

STM32F411CEU6 C HAL library development use code [F411-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/STM32F411CEU6/HAL/F411_ST7735)

Micropython development use code [micropython-ST7735](https://github.com/WeActTC/MiniF4-STM32F4x1/tree/master/SDK/MicroPython_Example/ST7735)
