
## Source code directories

+ https://chromium.googlesource.com/external/webrtc/+/master/webrtc/sdk/android/api/org/webrtc
+ https://chromium.googlesource.com/external/webrtc/+/master/webrtc/sdk/android/src/java/org/webrtc
+ https://chromium.googlesource.com/external/webrtc/+/master/webrtc/rtc_base/java/src/org/webrtc
+ https://chromium.googlesource.com/external/webrtc/+/master/webrtc/modules/audio_device/android/java/src/org/webrtc/voiceengine
+ https://chromium.googlesource.com/external/webrtc/+/master/webrtc/examples/androidapp/

下载
===
如果不想自己编译，可直接下载apk进行测试：https://github.com/elesos/AppRTC-Android/raw/master/apprtc-release.apk


测试时，app设置的Room server url可以填写我搭建的webRTC服务器(有Room Server，Signal Server，TURN/STUN Server， ICE Server)地址：

room server:http://36.110.202.64:8080

ice server:http://36.110.202.64:3033/iceconfig

turn server:turn:36.110.202.64:3478

stun server:36.110.202.64:3478

signal server:http://36.110.202.64:8089/

web端地址是： http://36.110.202.64:8080

其它
==
自己开发的一对一视频聊天，直播连麦和im消息系统示例程序：

源码地址：https://github.com/starrtc/android-demo

[StarRTC_demo 安装包](https://github.com/starrtc/android-demo/raw/master/StarRTC_demo.apk)，注意需要2部手机都安装才能测试一对一通话，或者扫描下面二维码安装。

![StarRTC_demo 安装包](android.png)

IM测试时，除了app之间可以互发消息，app也可以和这个页面互发消息进行测试：

[Web IM](https://www.starrtc.com/demo/im)，源码地址：https://github.com/starrtc/webim-demo

一对一视频等功能也可以和这个页面测试：

[H5测试](https://www.starrtc.com/demo/h5/)，源码地址：https://github.com/starrtc/webrtc-demo

Contact
=====
QQ ： 2162-498-688

邮箱：<a href="mailto:support@starRTC.com">support@starRTC.com</a>

手机: 186-1294-6552

微信：starRTC
