### 设备号定义

see [Documentation/admin-guide/devices.txt](https://github.com/torvalds/linux/blob/master/Documentation/admin-guide/devices.txt)

### 字符设备(chardev)

#### 混杂设备(miscdevice)

共享主设备号(10), 次设备号不同

e.g. /dev/kvm:major=10, minor=232

```
#注册函数
misc_register()
```

### 块设备(blockdev)

