# BigBaseV3
A mod menu base for Grand Theft Auto V.
Strictly for educational purposes.

## Features
* ImGui–based user interface
* Unloading at runtime
* Log console
* Script fibers
* Fiber pool
* Access to YSC script globals
* scrProgram–based native hook

## Building
To build Exelon you need:
* Visual Studio 2019
* [Premake 5.0](https://premake.github.io/download.html) in your PATH

To set up the build environment, run the following commands in a terminal:
```dos
git clone https://github.com/ihxzey/BigBaseV3.git --recurse-submodules
cd BigBaseV3
premake5 vs2019
```
Now, you will be able to open the solution, and simply build it in Visual Studio.
