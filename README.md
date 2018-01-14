# mod_rtsp for freeswitch v1.8
1.源码放在endpoints目录下，添加mod_rtsp模块
2.sudo make mod_rtsp-install
3.freeswitch: load　mod_rtsp
4.show application 能看到play_rtsp这个app
5.originate user/1009 &play_rtsp(rtsp://xxxxx)
6.程序还有问题
