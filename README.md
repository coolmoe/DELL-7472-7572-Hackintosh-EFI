# DELL-7472-7572-Hackintosh-EFI
Clover/OC驱动及配置文件
适用于DELL7472 Clover、OC配置文件及驱动（也可供7572机型参考，二者主要存在屏幕大小的区别）
安装使用黑苹果之前，需要在BIOS里面进行如下设置，3项设置缺一不可，都是必须要设置的，否则将会导致引导出现问题：
**1.关闭安全引导
2.开启AHCI
3.关闭Enable Legacy Option ROMs**
如果出现卡在进度条或者是报错：
例子1：HID：Legacy shim 2
例子2：Generation from SMC report as 2
例子3：Initializing
例子4：AGDCBacklightControl：Don't find DPMicro
**如果出现这些错误，可以尝试restart nvram 清除一下nvram。**
**如果安装好macOS出现无法正常睡眠唤醒或者盒盖后 开盖无法正常唤醒。可以刻录一个Ubuntu 系统到优盘里面去，然后U盘启动这个优盘，进安装界面（Ubuntu试用界面）之后重启即可。**
OC版本：OpenCore 0.6.8
注意：只在big sur 也就是macOS 11版本上测试，没有在10.X上测试，所以不保证是否可以正常使用。

**电脑配置**
**规格	 详细信息**
电脑型号	戴尔 Inspiron 7572 笔记本电脑
BIOS版本	 Inspiron_7472_7572_1.6.1
操作系统	macOS Big Sur 11.2.3/Windows 10 LTSC
处理器	     Intel Core i5-8250U @ 1.80GHz 四核八线程
内存	      16 GB ( 威刚 DDR4 2400MHz )
硬盘1	      金士顿 (512 GB 固态硬盘 )
显卡1	英特尔 HD Graphics 620 （保留2 GB显存）
显示器	LG FHD 1920x1080 (15.6 英寸)
声卡	ALC256 (layout-id:2/56)
网卡	A1820A
OpenCore版本	OpenCore-0.6.8-RELEASE
