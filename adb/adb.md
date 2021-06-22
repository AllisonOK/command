###adb wifi调试
```
adb tcpip 5555
adb connect 手机ip（如adb connect 192.168.1.101）
adb devices验证是否连接成功
给指定的手机安装程序
adb -s 手机编码 install xx.apk
```

