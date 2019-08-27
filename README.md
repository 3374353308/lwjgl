LWJGL -  轻量级Java游戏库(for aarch64)
======

> **警告**

> 这是原始LWJGL的存储库，不再主动维护。除非您发布了使用LWJGL 2.x的产品，否则您可能应该关注LWJGL 3。
> 这只能适用于aarch64

轻量级Java游戏库（LWJGL）是一种直接面向专业和业余Java程序员的解决方案，可以用Java编写商业级游戏。LWJGL为开发人员提供了对高性能跨平台库的访问，例如OpenGL（开放图形库），OpenCL（开放计算语言）和OpenAL（开放音频库），允许最先进的3D游戏和3D声音。此外，LWJGL还可以访问控制台，如游戏手柄，方向盘和操纵杆。全部采用简单直接的API。

依赖
-----------
gcc
xorg-dev
build-essential
libgl1-mesa-dev
libglu1-mesa-dev
freeglut3-dev

编译
-----------

这仅适用于aarch64架构

* ant generate-all
* ant compile
* ant compile_native
