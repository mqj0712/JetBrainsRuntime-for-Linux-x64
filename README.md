# JetBrainsRuntime-for-Linux-x64  
利用 Github Actions 每月 1 号定时对 [JetBrainsRuntime](https://github.com/JetBrains/JetBrainsRuntime) 打[社区大佬的补丁](https://github.com/prehonor/myJetBrainsRuntime)进行改进并针对 Linux x64 平台提供编译产物。  

## 说明  
1. 解决在 Linux x64 操作系统环境下，使用 JetBrains 系 IDE 存在的两个问题： 
    - fcitx 输入法候选框不跟随光标  
    - Markdown 文件无法正常预览  

2. 使用方法（激进）：  
    - 直接替换 IDE 安装目录下的 jbr 目录  

3. 特别提醒：
    - 由于是使用 master 分支的代码进行编译，如没有特殊需要**不建议使用 Pre-release 的包**，推荐使用已测试过的 [Latest-release](https://github.com/RikudouPatrickstar/JetBrainsRuntime-for-Linux-x64/releases/latest)

## 参考  
* [idea 中文输入法定位不准问题修复(fcitx框架输入法)](https://blog.csdn.net/u011166277/article/details/106287587)  
* [BUG解决之路-1 Linux下fcitx输入法候选框在IDEA等JetBrains系列IDE中不跟随光标（JetBrains Runtime版本：11.0.7）](https://blog.csdn.net/qq_41859728/article/details/109187748)  

## 已经不需要这个patch
* [JBR17的release里面已经包含了JBR-2460 ](https://github.com/JetBrains/JetBrainsRuntime/releases/tag/jbr-release-17.0.9b1087.9)https://github.com/JetBrains/JetBrainsRuntime/releases/tag/jbr-release-17.0.9b1087.9)
