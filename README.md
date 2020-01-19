# DiYuHuo-X6-Hackintosh

火影地狱火X6 黑苹果EFI

## 重要说明
*  把以前分散的仓库整合成单个仓库管理
*  提交上来的EFI都是经过本人测试能正常使用的
*  大部分主要的硬件都已驱动，具体驱动硬件见每个EFI压缩包内的详细信息
*  硬件相似的也可以拿去使用看看
*  以下只是大概说明，具体驱动情况以每个EFI里面的说明及config文件为准，这个仓库的EFI都是基本硬件都驱动了才会传上来

## 主要硬件预览
*    H370 + i7-8750H + GTX1060 + ACL269 + BCM94352Z)
*   `主板` H370（USB2.0\*4 + USB3.1\*2 + TYPE-C\*1:非全功能 + HDMI\*1 + RJ45\*1）
*   `CPU` i7-8750H（6C 12T）
*   `核显` Intel UHD Graphics 630
*   `独显` GTX1060（三星6GB）
*   `声卡` ACL269
*   `无线网卡` 联想BCM94352Z

##  已驱动
*   `核显`（UHD 630,VRAM=2048M）
*   `声卡`（ACL269,layoutId = 6,内建,切换正常,10.15以上的系统,注入id为12,6已经被删除了）
*   `网卡`（RealtekRTL8111 + BCM94352Z）
*   `蓝牙`（USB2.0通道,index=14）
*   `USB定制`（导出USBPorts.kexts,去除USBInjectAll,USB3.0识别正常,速度满速,睡眠完全睡死）
*   `传感器`（温度，转速等）
*   `亮度调节`（！无法保存上次亮度！）
*   `电池信息`（充电断电正常识别）
*   `变频正常`
*   `硬解正常`
*   `Cinebench R15`跑分正常(分数1048)
*   `iMessage,FaceTime`等苹果应用正常，iTunes打开正常，不卡顿
*   `SMBIOS`信息注入，可到苹果官网查到机器信息。

##  未驱动
*   `独显`（GTX 1066(三星)）

## 有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(gaofeicm#qq.com, 把#换成@)

## 感激
感谢以下的项目,排名不分先后

* [黑果小兵的部落阁](https://blog.daliansky.net/)
* [远景论坛](http://bbs.pcbeta.com/)
* [tonymacx86](https://www.tonymacx86.com)

## 关于作者

```javascript
  CMS程序员一枚
```
