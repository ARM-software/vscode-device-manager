# Change Log

## [Unreleased]

## 1.13.2

- Switch to use serial monitor from https://github.com/eclipse-cdt-cloud/vscode-serial-monitor
- Fixed CMSIS pack listing when no local CMSIS pack cache is present
- Split device editing UI in to separate 'rename' and 'configure pack' actions
- Added better message when a device isn't selected

## 1.13.1
- Added `device-manager.getDeviceType`

## 1.13.0
- Updated underlying USB package and switched to libusb v1.0.27
- Fixed handling of pack path on Windows

## 1.12.1
- Help user configure device when unable to detect it's type
- Ship native binaries to support running on Windows on Arm
- Fix custom configuration for external probes

## 1.11.0
- Updated dependencies

## 1.10.0
- Detects ULINKpro and ULINKpro D devices
- Shows Output channel only when it has content
- Add command `device-manager.getBuildTargetName` to get connected target name

## 1.9.8
- Fixed issue where device list would not load on first invocation

## 1.9.7
- Fixed issue with vendor names containing spaces
- Switched to use cmsis.io for pack assets
- Documentation updates

## 1.9.2
- Fixed detection of older ST devices

## 1.9.1
- Fixed detection for NXP devices

## 1.9.0
- List packs when editing a device
- Prompt user to configure a device when required
- Better device list refreshing

## 1.8.0
- Non-preview release
- Add ability to edit device pack and pack device name
- Show contextual help link for connecting devices
- Show device VID/PID in hex format
- Better serial connection messaging
