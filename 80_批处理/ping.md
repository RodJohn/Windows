
ICMP是:Internet 控制信息协议（ICMP）是 IP 组的一个整合部分。通过 IP 包传送的 ICMP 信息主要用于涉及网络操作或错误操作的不可达信息。
 ICMP 包发送是不可靠的，所以主机不能依靠接收 ICMP 包解决任何网络问题。ICMP不象TCP或UDP有端口，但它确实含有两个域：类型(type)和代码(code)。而且这些域的作用和端口也完全不同。
Ping用到的是ICMP协议。
