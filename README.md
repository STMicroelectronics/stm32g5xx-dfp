# STM32G5xx DFP Software Pack

![tag](https://img.shields.io/badge/tag-2.0.0-brightgreen.svg)
[![release note](https://img.shields.io/badge/release_note-view_html-gold.svg)](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/stm32g5xx-dfp/blob/main/Release_Notes.html)

## Overview

**STM32G5xx DFP** contains essential information and files for IDEs, toolchains and software applications to support STM32G5xx devices.

## Description and Usage

This DFP includes the following components

* **Documentation**
  * Device documentation (Reference Manuals, Datasheets, ...) links are provided in the DFP Pack description file (`STMicroelectronics.stm32g5xx_dfp.pdsc` file)
  * Readme
  * Release Notes
* **CMSIS-Core Device Files**
  * `startup_stm32g5xxxx.c` : device startup file (should be compiled with C compiler)
  * `system_stm32g5xx.{c|h}` : device system configuration files
  * `stm32g5xxxx.h` : device header file
  * `partition_stm32g5xx.h`: TrustZone setup (initial setup of the TrustZone hardware in an Armv8-M system.)
  * `stm32g5xxxx.{ld|sct|icf}` device linker configuration file
* **IDE/Tools Device Support Files**
  * `Flash/*.xldr` : Flash Programming Algorithms for erasing and downloading code into on-chip Flash
  * `SVD/*.svd` : System View Description Files describing the programmer's view of the device's peripherals
  * `Descriptors` : Device descriptor files (clock, peripherals pinout, ...)
  * `IDEs_patches/EWARM` : needed patches to add STM32G5xx devices support in IAR Embedded Workbench for ARM