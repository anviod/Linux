# 服务器 基本要求
* 1 供电：【24小时不间断供电 （推荐双路供电）】
* 2 网络：【提供固定IP地址, 开放端口：21 22 5555 6666 7777 8888 8090 9999 3306 4501 公网上行带宽要求:20Mbps下行带宽100Mbps以上；内网带宽:1000Mbps以上】
* 3 硬件：【内存 8GB , 硬盘 2*500GB 磁盘阵列 Raid 1, 处理器：Intel Xeon E3 以上】
* 4 操作系统: 【Windows Server 2012 或者 Linux ： CentOS 7.0  内核4.0 以上版本】
* 5 维护：【允许远程桌面 自定义远程端口。或者Linux 提供  SSH】  

## 【实体服务器方案】

> 基本选型：
* 	服务器最大并发：5 000 台以内 
* 	参考单价：6000元   
* 	参考机型：联想ThinkStation P300(处理器:Xeon E3-1231v3/内存:8GB/硬盘:2*500GB/磁盘阵列:Raid 1) （塔式）或者 联想ThinkServer RS240(G3260/8GB/2*300GB SATA/Raid 1)（机架式）
* 	需要服务器数量：1台

> 中级选型：
*	服务器最大并发：5 000--20 000台  
*	参考单价：8000元 
*	参考机型：联想ThinkStation P410(Xeon E5-1603/8GB/4*500GB/Raid 10)（塔式）或者 联想ThinkServer RD340(Xeon E5-2407v2/8G/4*300G SATA/Raid 10）（机架式）
*	需要服务器数量：2台 （设备处于同一局域网内并支持千兆网）

> 高级选型：
*	服务器最大并发：20 000--100 000台   
*	参考单价：15000元 
*	参考机型：联想ThinkStation P500(Xeon E5-1620v3/8GB/4*500GB/Raid 10)（塔式）
				或者 联想ThinkServer RD450(Xeon E5-26209v3/8G/4*300G SATA/Raid 10)（机架式）
*	需要服务器数量：3台 （设备处于同一局域网内并支持千兆网）



## 【虚拟化或云主机方案】

> 1基本选型:服务器最大并发5 000 台以内
*	1.ECS:2核 4GB 带宽 5Mbps 数量：1台 参考价 3000元/年 （ Linux 服务器数量 >= 1 台）
*	2.MySql数据库   数量：1台 参考价 1000元/年

> 2中级选型:服务器最大并发5 000--20 000台
*	1.ECS:2核 8GB 带宽 5Mbps  数量：2台 参考价 3500元/年 （ Linux 服务器数量 >= 1 台）
*	2.MySql数据库  数量：1台  参考价 1000元/年
*	3.负载均衡 SLB或者 LVS 参考价 300元/年

> 3高级选型:服务器最大并发20 000--100 000台
*	1.ECS:4核 8GB 带宽 10Mbps  数量：3台    参考价 8000元/年 （ Linux 服务器数量 >= 1 台）
*	2.MySql数据库  数量：1台   参考价 2000元/年
*	3.负载均衡 SLB或者 LVS 参考价 1000元/年
