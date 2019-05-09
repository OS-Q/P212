# [LoRaWAN](https://github.com/OS-Q/D145) 
[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)
####  qitas@qitas.cn
#### 归属无线组网：[W21](https://github.com/OS-Q/W21)
#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)
Edge-Q -> 体系 Q[1,4] -> 节点 M[1,12] -> 平台 W[1,52] -> 设备 D[1,365]
### [设备描述](https://github.com/OS-Q/D145/wiki) 

LoRaWAN基于LoRa远距离通信网络设计的一套通讯协议和系统架构,按协议分层来说LoRaWAN就是MAC层,LoRa是物理层。LoRaWAN也被叫做LoRaMAC。

通过LoRaWAN定义协议完成自组网通信，LoRaWAN 将终端设备划分成A/B/C三类：

* Class A：双向通信终端设备。这一类的终端设备允许双向通信，每一个终端设备上行传输会伴随着两个下行接收窗口。终端设备的传输时隙是基于其自身通信需求，其微调基于ALOHA协议。
* Class B：具有预设接收时隙的双向通信终端设备。终端设备会在预设时间中开放多余的接收窗口，为了达到这一目的，终端设备会同步从网关接收一个Beacon，通过Beacon将基站与模块的时间进行同步。
* Class C：具有最大接收窗口的双向通信终端设备。这一类的终端设备持续开放接收窗口，只在传输时关闭。

### [设备资源](https://github.com/OS-Q/D145) 

* [文档](docs/)
* [资源](src/)
* [工程](LoRaWAN/)
	* [classA](LoRaWAN/classA/)
	* [classB](LoRaWAN/classB/)
	* [classC](LoRaWAN/classC/)


### [设备关联](https://github.com/OS-Q/D145) 

* W21：[无线组网](https://github.com/OS-Q/W21)
	* D141：[BLE Mesh](https://github.com/OS-Q/D141)
	* D142：[ZigBee](https://github.com/OS-Q/D142)
	* D143：[Thread](https://github.com/OS-Q/D143)
	* D144：[ANT](https://github.com/OS-Q/D144)
	* [D145：LoRaWAN](https://github.com/OS-Q/D145)
	* D146：[CLAA](https://github.com/OS-Q/D146)
	* D147：[NULL](https://github.com/OS-Q/D147)


### [OS-Q : Operation System for edge devices](http://www.OS-Q.com/Edge/D145)
####  2019-5-8
