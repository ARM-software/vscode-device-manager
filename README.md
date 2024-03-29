# Arm Device Manager

## Overview

The complete [documentation](https://developer.arm.com/documentation/108029/latest/Extension-pack-and-extensions) for Arm® Device Manager and the other Keil® Studio extensions is available on Arm Developer.

The Device Manager extension allows you to manage hardware connections for Arm Cortex®-M based microcontrollers, development boards, and debug probes. You can install the extension individually or as part of the Arm Keil Studio Pack extension in Visual Studio Code Desktop.

We recommend installing the Keil Studio Pack for Visual Studio Code Desktop to quickly set up your environment. When you have installed the pack, read the documentation available on Arm Developer to get started. You can [import a csolution example from keil.arm.com](https://developer.arm.com/documentation/108029/latest/Get-started-with-an-example-project/Import-a-csolution-example), [download and convert a μVision project from keil.arm.com](https://developer.arm.com/documentation/108029/latest/Get-started-with-an-example-project/Download-and-convert-a-Keil--Vision-example), [create a csolution project from scratch](https://developer.arm.com/documentation/108029/latest/Arm-CMSIS-csolution-extension/Create-a-csolution-project), or [convert an existing μVision project](https://developer.arm.com/documentation/108029/latest/Arm-CMSIS-csolution-extension/Convert-a-Keil--Vision-project-to-a-csolution-project).

The Device Manager extension works with the Arm CMSIS csolution (Identifier: `arm.cmsis-csolution`) and Arm Debugger (Identifier: `arm.arm-debugger`) extensions to run and debug csolution projects.

## Intended use cases for the extensions

- **Embedded and IoT software development using CMSIS-Packs and csolution projects**: The Common Microcontroller Software Interface Standard (CMSIS) provides driver, peripheral, and middleware support for thousands of MCUs and hundreds of development boards. Using the csolution project format, you can incorporate any CMSIS-Pack based device, board, and software component into your application. For more information about supported hardware for CMSIS projects, go to the [Boards](https://www.keil.arm.com/boards/) and [Devices](https://www.keil.arm.com/devices/) pages on keil.arm.com. For information about CMSIS-Packs, go to [open-cmsis-pack.org](https://www.open-cmsis-pack.org/index.html).

- **Enhancement of a pre-existing Visual Studio Code embedded software development workflow**: You can adapt USB device management and embedded debug to other project formats (for example, CMake) and toolchains without additional overhead. This use case requires familiarity with Visual Studio Code to configure tasks. See the individual extensions for more details.

## Install the extension

We recommend installing the Keil Studio Pack. Follow this procedure if you want to install the extension as standalone.

1. In Visual Studio Code, go to the **Extensions** view.

1. Search for **Arm Device Manager**.

1. Click the **Install** button for the extension.

    Visual Studio Code installs the extension. It is now available in the **Extensions** view.

## Submit feedback

To submit feedback, please [see our support page](https://www.keil.arm.com/support/#:~:text=Connecting%20Hardware).