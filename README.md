# PressureTestTree
压力测试技术研究


###数据构造平台
![](https://i.imgur.com/HYXguPc.png)

###全链路压测平台
![](https://i.imgur.com/6zw4S8a.png)

<pre>
全链路压测平台：

     全链路压测的流量平台是一个典型的master＋slave结构，master作为压测管控台管理着上千个
     slave节点；slave节点作为压测引擎，负责具体的请求发送。Master作为整个压测平台的大脑，
     负责的整个平台的运转控制、命令发送、数据收集、决策等。slave节点部署在全球各地的cdn节点
     上，从而模拟从全球各地过来的用户请求。整套全链路压测的流量平台在压测过程当中平稳输出
     1000w＋／s的用户请求、同时保持过亿的无线用户长链接。
</pre>