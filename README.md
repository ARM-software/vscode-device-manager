# Arm Device Manager

- [Overview](#overview)
- [Connect your hardware](#connect-your-hardware)
- [Edit your hardware](#edit-your-hardware)
- [Open a serial monitor](#open-a-serial-monitor)
- [Submit feedback or report issues](#submit-feedback-or-report-issues)

## Overview

The Device Manager extension allows you to manage hardware connections for Arm-based microcontrollers, development boards, and debug probes. You can install the extension individually or as part of the Arm Debugger extension pack.

## Connect your hardware

This section describes how to connect your hardware for the first time.

1. Click **Device Manager** ![Device Manager icon](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/device-manager-icon.png) in the Activity Bar.

1. Connect your hardware to your computer over a USB connection.

    The Device Manager detects the hardware and a pop-up message displays in the bottom right-hand corner.

1. Click **OK** to use the hardware.

    Alternatively, click **Add Device** ![Add Device button](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/add-device-button.png) and select your hardware in the drop-down list that displays at the top of the window.

    You can now use your hardware to run and debug a project.

To add more hardware, click **Add Device** ![Add icon](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/add-device-icon.png) in the top right-hand corner.

## Edit your hardware

If the Device Manager cannot detect your hardware or if you are using an external debug probe, you can edit the hardware entry. You can specify a Device Family Pack (DFP) and a device name retrieved from the pack to be able to work with your hardware. DFPs handle device support.

1. Move your cursor over the hardware that you want to edit and click **Configure Pack** ![Configure Pack icon](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/configure-pack-icon.png).

1. Select a DFP for your hardware in the drop-down list.

1. Select a device name in the drop-down list.

1. To change the name of the hardware, click **Rename Device** ![Rename Device icon](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/rename-device-icon.png), then rename your hardware and press **Enter**.

## Open a serial monitor

Open a serial monitor. The serial output shows the output of your board. You can use the serial output as a debugging tool or to communicate directly with your board.

1. Move your cursor over the hardware for which you want to open a serial monitor and click **Open Serial** ![Open Serial icon](https://github.com/ARM-software/vscode-device-manager/raw/main/docs/images/open-serial-icon.png).

    A drop-down list displays at the top of the window where you can select a baud rate. The baud rate is the data rate in bits per second between your computer and your hardware. To view the output of your hardware correctly, you must select an appropriate baud rate. The baud rate that you select must be the same as the baud rate of your active project.

1. Select a baud rate.

    A **Terminal** tab opens with the baud rate selected.

## Submit feedback or report issues

To submit feedback or report issues on the Device Manager extension, please use [GitHub issues](https://github.com/Arm-Software/vscode-device-manager/issues) in the extension repository.
