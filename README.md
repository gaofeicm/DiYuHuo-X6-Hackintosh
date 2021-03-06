# DiYuHuo-X6-Hackintosh

火影地狱火X6 黑苹果EFI

## 20210604更新
*  1、11.0.1版本的EFI可直接使用，通过OTA从11.3.1（20E241）版本直接升级到11.4（20F71）版本，无需做任何修改，升级过程中会重启2～3次，属于正常情况。
*  2、未出现网上说的定制的USB驱动失效的问题，一个配置用半年，省心省力！
*  ![image](https://user-images.githubusercontent.com/25575562/120796845-e4765700-c56d-11eb-94b1-e77d48b954ec.png)
***

## 20210518更新
*  1、11.0.1版本的EFI可直接使用，通过OTA从11.2.1（20D75）版本直接升级到11.3.1（20E241）版本，无需做任何修改，升级过程中会重启2～3次，属于正常情况。
***

## 20210216更新
*  1、11.0.1版本的EFI可直接使用，通过OTA从11.1（20C69）版本直接升级到11.2.1（20D75）版本，无需做任何修改，升级过程中会重启2～3次，属于正常情况。
***

## 20201218更新
*  1、11.0.1版本的EFI可直接使用，通过OTA从11.0.1（20B50）版本直接升级到11.1（20C69）版本，无需做任何修改，升级过程中会重启2～3次，属于正常情况。
***

## 20201116更新
*  1、博通的网卡年后卖掉换回了原装的Intel AC 9462，没想到现在可以驱动了！
*  2、本次新增了Big Sur 11.0.1版本基于OC0.6.3版本引导的EFI，基本都正常了，具体信息参见文件夹内的使用说明文件。
***
## 以下是历史说明（各版本更新信息将写在各版本文件夹内）

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
*   `声卡`（ACL269,layoutId = 6,内建,切换正常）
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

***

## 有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(gaofeicm#qq.com, 把#换成@)

## 感激
感谢以下的项目,排名不分先后

* [黑果小兵的部落阁](https://blog.daliansky.net/)
* [远景论坛](http://bbs.pcbeta.com/)
* [tonymacx86](https://www.tonymacx86.com)
* [机械革命黑苹果](https://www.cmbs-soft.com/)

## 关于作者

```javascript
  CMS程序员一枚
```
