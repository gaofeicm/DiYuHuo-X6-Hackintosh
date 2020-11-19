前言：本EFI基于机械革命Z2定制版EFI修改而来，感谢！地址：https://www.cmbs-soft.com/8th-9th-version

系统是由10.15.7（CLOVER引导）直接OTA升级上来的，升级过程重启过3-4次，只要确保配置正确，这都是正常过程

替换EFI后基本大部分正常，除了3个USB2.0接口（左2，右上1）无效外，视乎都完美了，因为第一次刚入OC，找不到人指导，只能自己摸索，后面花了一晚上时间还是把USB弄好了

本EFI基于OC0.6.3版本，包含内容如下：

1、核显（2048M）
2、音频AppleALC（ID:29）
3、USB驱动（定制USBPorts）
4、电池
5、亮度
6、有线网卡
7、无线网卡（Intel AC 9462，硬件id：02A48086）
8、蓝牙
9、触控板
10、休眠
11、三码
12、硬解

再次修改注意：SSDT-EC-USBX.aml包含电池补丁，SSDT-UIAC.aml包含USB补丁

USB端口映射关系如下：
USB2:HS08,HS07,HS03,HS12
USB3:SS05,SS06
Typec:SS01（反插无反应，但是有电压电流通过）
内建:HS06,HS13,HS14
SD卡:HS02