# Ripes
[![Build Status](https://travis-ci.org/mortbopet/Ripes.svg?branch=master)](https://travis-ci.org/mortbopet/Ripes/)
[![Gitter](https://badges.gitter.im/Ripes-VSRTL/Ripes.svg)](https://gitter.im/Ripes-VSRTL/)

Ripes is a visual computer architecture simulator and assembly code editor built for the [RISC-V instruction set architecture](https://content.riscv.org/wp-content/uploads/2017/05/riscv-spec-v2.2.pdf).

You can support [this project on Patreon](https://www.patreon.com/mbpetersen).  
Got questions or comments? Head over to the Ripes [Gitter chat](https://gitter.im/Ripes-VSRTL/).  
Report bugs, issues or feature requests at https://github.com/mortbopet/Ripes/issues.

<p align="center">
    <img src="https://github.com/mortbopet/Ripes/blob/master/resources/images/animation.gif?raw=true" />
</p>

## Usage
Ripes may be used to explore concepts such as:
- How machine code is executed on a variety of microarchitectures
- How different cache designs influence performance
- How assembly code is assembled to executable machine code

If this is your first time using Ripes, please refer to the [introduction](https://github.com/mortbopet/Ripes/wiki/Ripes-Introduction).  
For further information, please refer to the [Ripes wiki](https://github.com/mortbopet/Ripes/wiki).

## Downloading & Installation
Prebuilt binaries are available for Linux, Windows & Mac through the [Releases page](https://github.com/mortbopet/Ripes/releases).  

### Linux
Releases for Linux are distributed in the AppImage format. To run an AppImage:
* Run `chmod a+x` on the AppImage file
* Run the file!
The AppImage for Linux should be compatible with most Linux distributions.

### Windows
For Windows, the C++ runtime library must be available (if not, a msvcp140.dll error will be produced). You most likely already have this installed, but if this is not the case, you download it [here](https://www.microsoft.com/en-us/download/details.aspx?id=48145).

## Building
Initially, the following dependencies must be made available:
- A recent (5.10+) version of [Qt](https://www.qt.io/download) + Qt Charts (**not** bundled with Qt by default, but can be selected during Qt installation)
- [CMake](https://cmake.org/)

Then, Ripes can be checked out and built as a standard CMake project:
```
git clone --recursive https://github.com/mortbopet/Ripes.git
cd Ripes/
cmake .
Unix:               Windows:
make                jom.exe / nmake.exe / ...
```
Note, that you must have Qt available in your `CMAKE_PREFIX_PATH`. For further information on building Qt projects with CMake, refer to [Qt: Build with CMake](https://doc.qt.io/qt-5/cmake-manual.html).

---
Icons kindly provided by Flaticon authors: [Smashicons](https://www.flaticon.com/authors/smashicons), [Freepik](https://www.flaticon.com/authors/freepik), [Vectors Market](https://www.flaticon.com/authors/vectors-market) & [Pixel Buddha](https://www.flaticon.com/authors/pixel-buddha).

<a href="https://www.qt.io/">
    <img src="https://github.com/mortbopet/Ripes/blob/master/resources/images/QtIcon.png" width="60" height="60" />
</a>
