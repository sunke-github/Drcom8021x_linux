Drcom8021x 软件是根据 EasyDrcom软件重构而来,该源码地址:https://github.com/coverxit/EasyDrcom .

本软件遵循GPL v3.0,使用本软件源码请注明原作者,来源和出处.


功能概述:

该软件可以实现 drcom的 802.1x 认证.适用于部分地区和学校. 省略原EasyDrcom 认证模式和注销功能. 


编译软件:

使用Linux 下的CDT 创建和编译该工程. 编译时请在 

工程->Properities->C/C++ Build->Settings->GCC C++ Compiler 中添加 -std=c++11

工程->Properities->C/C++ Build->Settings->GCC C++ Linker  Miscellaneous中 添加 -lpcap


免责声明:

该软件是做交流学习使用,请勿用作非法用途. 使用本软件带来的法律问题由使用者付全责与软件作者无关.