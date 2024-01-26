# Arm Device Manager

## Overview

The complete [documentation](https://developer.arm.com/documentation/108029/latest/Extension-pack-and-extensions) for Arm® Device Manager and the other Keil® Studio extensions is available on Arm Developer.

The Device Manager extension allows you to manage hardware connections for Arm Cortex®-M based microcontrollers, development boards and debug probes. It can be installed individually or as part of the Arm Keil Studio Pack extension in Visual Studio Code Desktop.

We recommend installing the Keil Studio Pack for Visual Studio Code Desktop to quickly set up your environment and start working with an example.

The Device Manager extension can work in combination with the Arm CMSIS csolution (Identifier: `arm.cmsis-csolution`) and Arm Embedded Debugger (Identifier: `arm.embedded-debug`) extensions to run and debug csolution projects.

## Intended use cases for the extensions

- **Embedded and IoT software development using CMSIS-Packs and csolution projects**: The "Common Microcontroller Software Interface Standard" (CMSIS) provides driver, peripheral and middleware support for thousands of MCUs and hundreds of development boards. Using the csolution project format, you can incorporate any CMSIS-Pack based device, board, and software component into your application. For more information about supported hardware for CMSIS projects, go to the [Boards](https://www.keil.arm.com/boards/) and [Devices](https://www.keil.arm.com/devices/) pages on keil.arm.com. For information about CMSIS-Packs, go to [open-cmsis-pack.org](https://www.open-cmsis-pack.org/index.html).

- **Enhancement of a pre-existing Visual Studio Code embedded software development workflow**: USB device management and embedded debug can be adapted to other project formats (for example CMake) and toolchains without additional overhead. This use case requires familiarity with Visual Studio Code to configure tasks. See the individual extensions for more details.

## Install the extension

1. In Visual Studio Code, go to the **Extensions** view.

1. Search for **Arm Device Manager**.

1. Click the **Install** button for the extension.

    Visual Studio Code installs the extension. It is now available in the **Extensions** view.

## Submit feedback

To submit feedback, please [see our support page](https://www.keil.arm.com/support/#:~:text=Connecting%20Hardware).