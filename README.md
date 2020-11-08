# GrayPhotoFrame

## Overview
This program is gray scale digital photo frame for STM32.

## Hardware

* Nucleo-L431KC
* GDEW042T2 (Gray scale e-paper)
	http://www.e-paper-display.com/products_detail/productId=321.html
* DESPI-C02 (FPC convertor)
* BATT (Al AA battery x2)

## Software

* Image2lcd (for Windows)
	http://www.e-paper-display.com/download_list/downloadcategoryid%3d11%26isMode%3dfalse.html#

## How to BATT in to Nucleo-L431KC

* Disconnect JP1
* BATT at AVDD
* Pull up NRST with 1kohm
