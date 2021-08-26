# dell5557 配置
硬件  | 型号
---  | :--
处理器 | 英特尔酷睿 i5-6200U
显卡 |Intel HD Graphics 520
硬盘  |	 闪迪至尊 1T 
内存  |	三星 8GB DDR3 1600MHz x 2
无线 + 蓝牙 | BCM94360Z4 无线网卡
显示器 | 内置（15.6 英寸 ）
键盘  |	内置
鼠标  |	罗技 M220

注意：

1.解锁CfgLock的可以直接安装，没有解锁的，请在 Kernel->Quirks 勾选 AppleCpuCfgLock 和 AppleXcpmCfgLock。

2.BCM94360Z4 无线网卡，该网卡尺寸比网卡卡槽两边多出2mm，老版本解决方式是切边框，后续小兵会推出小尺寸版可以放下，请多多关注 BCM94360Z4 无线网卡 最新动态。

3.Mac15用0.6.8的引导。 

#BIOS设置：

General->Boot Sequence->Boot List Optiong->UEFI
  
General->Advanced Boot Options->Enable Legacy Option ROMs

System Configuration->SATA Operation->AHCI

Secure Boot->Secure Boot Enable->Disable

Intel@ Software Guard Extensions->Intel@ SGX Enable->Disable

Intel@ Software Guard Extensions->Enclave Memory Size->128MB



![截屏2021-04-10 14 43 22](https://user-images.githubusercontent.com/45564110/114261205-f0311b80-9a0b-11eb-8369-cd277fa743c9.png)
![截屏2021-06-09 12 01 34](https://user-images.githubusercontent.com/45564110/121291207-738ec080-c91a-11eb-8a7d-0131168324ba.png)
![截屏2021-04-10 14 45 25](https://user-images.githubusercontent.com/45564110/114261242-1656bb80-9a0c-11eb-9f7c-934361439670.png)
![截屏2021-04-10 14 45 20](https://user-images.githubusercontent.com/45564110/114261244-1b1b6f80-9a0c-11eb-9d0d-ad7ed3a6901f.png)
