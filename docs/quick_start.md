# Quick Start

**This document is intended to help you set up the software environment(<mark>Arudino</mark>, <mark>MicroPython</mark>) for development of M5Stack. Through a simple example we would like to illustrate how to develop M5Stack boards, firmware(<mark>Arduino</mark>) or source files(<mark>MicroPython</mark>) download to M5Stack boards.**

## Introduction

**M5 stack is a modular stackable development device. The M stands for Modular and 5 stands for the the units compact 5 x 5 cm size.**


## What You Need

To develop applications for M5Stack Core you need:

* **PC** loaded with either Windows, Linux or Mac operating system
* a **Type-C** cable

Before setting development environment, the step below you need to follow:

1. Establish **serial** connection

  [How to Establish serial connection](related_documents\establish_serial_connection)

## Your Boards/Modules

!> **Notice** Make sure you have installed USB driver so that your board can establish serial connection with PC. If not, please view this article [How to Establish serial connection](related_documents\establish_serial_connection) for connection.

At the first time, you need to burn the specific firmware file(.bin) to your board following this article [How to burn firmware](related_documents\how_to_connect_wifi_using_core) befor developing it.

If you have one of ESP32 development boards listed below, click the corresponding one to start your development.

<img src="assets/img/getting_started_pics/m5stack_core.png"> | <img src="assets/img/getting_started_pics/m5camera.jpg">  | <img src="assets/img/getting_started_pics/M5Bala.jpg">
---|---|---
[M5StackCore](quick_start/m5core/m5stack_core_quick_start) | [M5Camera](quick_start/m5camera/m5camera_quick_start) | [M5BALA](quick_start/bala/bala_quick_start)



## Practice

**For being familiar with the programming mode you lik, We suggest you following the corresponding option to do more practices.**


<img src="assets/img/getting_started_pics/programming_mode_arduino.png"> | <img src="assets/img/getting_started_pics/programming_mode_blockly.png">  | <img src="assets/img/getting_started_pics/programming_mode_micropython.png">
---|---|---
[Arduino](practice\practice_arduino) | [M5Flow-Blockly](practice\practice_blockly) | [M5Flow-MicroPython](practice\practice_micropython)

## Related Documents

  - [establish_serial_connection](related_documents/establish_serial_connection)
  - [how_to_burn_firmware_en](related_documents/how_to_burn_firmware_en)
  - [how_to_connect_wifi_using_core](related_documents/how_to_connect_wifi_using_core)
  - [upgrade_m5stack_lib](related_documents/upgrade_m5stack_lib)