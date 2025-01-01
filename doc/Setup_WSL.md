# Development toolchain on WSL2 (Ubuntu 20.04)
This document captures the process to set up the development tool chain for MetriCode on WSL2 (Ubuntu 20.04).
## Installation
### Install WSL2
Follow the instructions [here](https://docs.microsoft.com/en-us/windows/wsl/install-win10) to install WSL2.
### Install Ubuntu 20.04
Follow the instructions [here](https://docs.microsoft.com/en-us/windows/wsl/install-win10#install-your-linux-distribution-of-choice) to install Ubuntu 20.04.

### Update the Linux paackage repositories 

```
sudo apt-get update
```
### Install Core C++ Development Tools

```
sudo apt-get install cmake
cmake --version
sudo apt-get install build-essential gdb
sudo apt-get install valgrind
sudo apt-get install binutils
sudo apt-get install gprof
sudo apt-get install build-essential libgl1-mesa-dev
```
### Install Qt6 Liraries and Tools
sudo apt install -y libqt6core6t64
sudo apt install -y qt6-base-dev qt6-base-dev-tools qt6-base-doc qt6-base-doc-dev
sudo apt install x11-apps -y
xeyes
