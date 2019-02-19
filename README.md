流量用于测试IDS协议识别

测试方法tcpreplay重放
```shell
#tcpreplay -i 接口 pcap文件
[root@localhost ~]# tcpreplay -i ens15f3 ICMP_across_dot1q.cap
```
![](https://ws1.sinaimg.cn/large/006tKfTcgy1g0bk8pkxepj311y0amgnn.jpg)
