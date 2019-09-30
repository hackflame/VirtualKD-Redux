# VirtualKD-Redux

VirtualKD-Redux is a fork of Sysprogs' VirtualKD.

## Features

* Support for the latest VMware Workstation (Currently 15.5.0)
* Support for the latest Windows 10 (Currently 1903)
* Toolchain modernization. Builds with Visual Studio 2017
* Significantly simplified the build system

## Downloads

[Download the latest VirtualKD-Redux release](https://github.com/4d61726b/VirtualKD-Redux/releases)

## Build Instructions
### Prerequisites
* Visual Studio 2017
* Windows Driver Kit 7.1.0
### Steps
1. Set WDK7_PATH to the WDK 7.1.0 install path
2. Edit make.bat to modify VS150COMNTOOLS path if needed
3. Run make.bat
4. Use binaries produced in Bundle directory
## Documentation
* Consult the documentation for VirtualKD (http://sysprogs.com/legacy/virtualkd/).