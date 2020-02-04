

## 从OpenCV4Android SDK 开始

1. 下载 OpenCV4Android SDK 

    打开 https://opencv.org/releases 找到 Android ，点击就可以下载了。
  
2. 编译 samples （介绍： https://opencv.org/opencv4android-samples/ ）

    2.1 下载下来是 opencv-4.2.0-android-sdk.zip ，解压这个包。
    
    2.2  解压后有两个文件夹，一个是 sdk, 一个是 samples.
    
    2.3 编译 samples ： 这里面有 8 个例子，编译脚本是用 gradle 管理的， 可以先编译一个 tutorial-1-camerapreview
    
    进入 samples 目录， 执行： **gradlew -p tutorial-1-camerapreview build**  ， 然后等待 ， 看到 BUILD SUCCESSFUL 就成功了。
    
    在samples\tutorial-1-camerapreview\build\outputs\apk 目录下就看到生产的 apk 了， 用 adb install 安装到手机上就可以跑这个 sample 了。
    
    
    
