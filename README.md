# Unibombepe
[![Build Status](https://travis-ci.org/nholthaus/notebook.svg?branch=master)](https://travis-ci.org/nholthaus/notebook) [![Build Status](https://ci.appveyor.com/api/projects/status/github/nholthaus/notebook?branch=master&svg=true)](https://ci.appveyor.com/project/nholthaus/gtest-gui) ![license](https://img.shields.io/badge/license-MIT-orange.svg) ![copyright](https://img.shields.io/badge/%C2%A9-Nic_Holthaus-orange.svg) ![language](https://img.shields.io/badge/language-c++-blue.svg) ![c++](https://img.shields.io/badge/std-c++14-blue.svg) ![Qt](https://img.shields.io/badge/Qt-5-blue.svg)<br>![msvc2013](https://img.shields.io/badge/MSVC-2013-ff69b4.svg) ![msvc2015](https://img.shields.io/badge/MSVC-2015-ff69b4.svg) ![gcc-4.9.3](https://img.shields.io/badge/GCC-4.9.3-ff69b4.svg) ![gcc-5.4.0](https://img.shields.io/badge/GCC-5.4.0-ff69b4.svg)


A Qt5 based automated test-runner and Graphical User Interface for Google Test unit tests

# Table of Contents

<!-- TOC -->

- [notebook](#notebook)
- [Table of Contents](#table-of-contents)
- [Light Theme](#light-theme)
- [Dark Theme](#dark-theme)
- [Features](#features)
- [Supported Platforms](#supported-platforms)
- [Installers](#installers)
	- [Windows](#windows)
	- [Ubuntu](#ubuntu)
	- [Other Linux Distributions](#other-linux-distributions)
- [Build Instructions](#build-instructions)

<!-- /TOC -->

# Light Theme
![Light Theme Screenshot](resources/screenshots/screen.png)

# Dark Theme
![Dark Theme Screenshot](resources/screenshots/screen2.png)

# Features

`notebook` is an automated test runner that will ensure you are always looking at the latest test results, whenever you build a gtest executable. Check the [features guide](FEATURES.md) to see what else `notebook` is capable of.

# Supported Platforms

To date, notebook has been tested on:
- Windows 10/7
- Ubuntu 16.04/15.10/14.04
- CentOS 7

# Installers

## Windows

Visit the [Latest release page](https://github.com/nholthaus/notebook/releases) for binary installers. 

Since version 1.1.2, all Windows binaries are signed.

## Ubuntu

Binary packages are available through the [notebook PPA](https://launchpad.net/~nholthaus/+archive/ubuntu/notebook) for many versions of Ubuntu. To install notebook via the PPA, type the following commands:

```bash
sudo add-apt-repository ppa:nholthaus/notebook
sudo apt-get update
sudo apt-get install notebook
```

Of course, you can also [build notebook from source](BUILD.md).

## Other Linux Distributions

Please see the instructions on [how to build notebook from source](BUILD.md).

# Build Instructions

See the [Build Instructions](BUILD.md) for information on how to build notebook from source on your platform.
