# ROG Ally 声音修复dkms补丁

## 源码获取打包方式
```
# 下载valve内核源码
git clone https://gitlab.com/evlaV/linux-integration.git -b 6.1.12-valve2

# 打包声音相关代码
cd linux-integration
tar -zcvf drivers-bluetooth.tar.gz drivers/bluetooth/{btusb.c,btintel.h,btbcm.h,btrtl.h,btmtk.h,Makefile}

```