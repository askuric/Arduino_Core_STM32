# STM32CubeU3 HAL Driver MCU Component

![latest tag](https://img.shields.io/github/v/tag/STMicroelectronics/stm32u3xx-hal-driver.svg?color=brightgreen)

## Overview

**STM32Cube** is an STMicroelectronics original initiative to ease the developers life by reducing efforts, time and cost.

**STM32Cube** covers the overall STM32 products portfolio. It includes a comprehensive embedded software platform, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio
   * The BSP Drivers of each evaluation, discovery or nucleo board provided by this STM32 series
   * A consistent set of middleware libraries such as ThreadX, FileX, USBX, NetDuoX, OpenBootloader, USBPD, trustedfirmware, MbedTLS, Network Library...
   * A full set of software projects (basic examples, applications and/or demonstrations) for each board provided for this STM32 series.
   * A new LPBAM utility which is a software helper that assists STM32U3 users in the elaboration of LPBAM scenarios.
   * A development with three Toolchains and Compilers (IAR Embedded Workbench for ARM (EWARM), RealView Microcontroller Development Kit (MDK-ARM), and STM32CubeIDE).

Two models of publication are proposed for the STM32Cube embedded software:
   * The monolithic **MCU Package** : all STM32Cube software modules of one STM32 series are present (Drivers, Middlewares, Projects, Utilities) in the repo (usual name **STM32Cubexx**, xx corresponding to the STM32 series)
   * The **MCU component** : each STM32Cube software module being part of the STM32Cube MCU Package, are delivered as an individual repo, allowing the user to select and get only the required software functions.

## Description

This **stm32u3xx_hal_driver** MCU component repo is one element of the STM32CubeU3 MCU embedded software package, providing the **HAL-LL Drivers** part.

## Release note

Details about the content of this release are available in the release note [here](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/stm32u3xx-hal-driver/blob/main/Release_Notes.html).


## Compatibility information

It is **crucial** that you use a consistent set of versions for the CMSIS Core - CMSIS Device - HAL, as mentioned in [this](https://htmlpreview.github.io/?https://github.com/STMicroelectronics/STM32CubeU3/blob/main/Release_Notes.html) release note.

The full **STM32CubeU3** MCU package is available [here](https://github.com/STMicroelectronics/STM32CubeU3).

## Troubleshooting

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) guide.
