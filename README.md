### ASUS-B365m-PIXIU-Hackintosh-opencore    华硕B365m-PIXIU  OC配置

#### 主机配置：

CPU：i5 9400F

主板：华硕B365M-PIXIU

显卡：华擎RX560 4G

无线网卡：BCM94360CD

硬盘：tigo nvme固态256G+金士顿240G SSD

#### 各硬盘系统分布：

nvme 固态256G：Windows 10 1809 --UEFI引导

金士顿240G固态：big sur 11.3.1 --opencore引导

OC正常引导2个系统

#### 引导工作情况：

注意：必须添加三码才可使用！！！！方法在下面！！！

无核显（9400F），config未配置核显

#### 正常工作的硬件：

WiFi蓝牙正常

有线网卡正常

独显正常

睡眠正常

唤醒正常

HEVC/H264双硬解正常

FaceTime/短信正常

USB已定制，机型为iMacPro1,1，修改机型请去掉USBPorts.kext， 改用USBInjectAll.kext，否则可能导致开机键鼠不能使用！

#### 机型修改说明：

GenSMBIOS生成的信息对应填入PlatformInfo--Generic下，对应关系如下：

SystemProductName ------ Type

SystemSerialNumber ----- Serial

MLB -------------------- Board Serial

SystemUUID ------------- SmUUID

主题说明：config已开启本人修改的官方主题
