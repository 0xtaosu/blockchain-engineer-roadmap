# 区块链工程师路线图
### 入门

1. Go

|  知识点  |                             内容                             |                         里程碑                         | 
| :------: | :----------------------------------------------------------: | :----------------------------------------------------: |
| 基本语法 |             [Go语言之旅](https://tour.go-zh.org)             |             用842-BCD码编写一个呱呱呱程序              | 
| 数据结构 |                         算法图解.pdf                         | 使用Go实现：二叉树、图、队列、堆和栈、快速排序和堆排序 |  
|    IO    | [Go并发编程中的那些事](https://github.com/xitu/gold-miner/blob/master/TODO/concurrent-programming.md) |                   实现一个贪吃蛇游戏                   |  

2. 操作系统

|  知识点  |                             内容                             |         里程碑          | 
| :------: | :----------------------------------------------------------: | :---------------------: | :------: |
| 文件系统 | [学习 Shell Scripts](http://linux.vbird.org/linux_basic/0340bashshell-scripts.php) |  使用shell实现一个bash  |  
| 进程管理 | [进程管理](http://wuchong.me/blog/2014/07/24/linux-process-manage/) |                         |  
| 系统调用 | [Linux 系统调用权威指南](https://arthurchiao.github.io/blog/system-call-definitive-guide-zh/) | 使用shell实现一个docker |   
3. 计算机网络

|  知识点   |         内容          |           里程碑           | 
| :-------: | :-------------------: | :------------------------: | 
| TCP和UDP  | TCP和UDP的区别和联系  |                            |  
|  IP和MAC  |  IP和MAC的区别和联系  |                            |  
| HTTP和P2P | HTTP和P2P的区别和联系 | 使用Go实现一个HTTP&P2P服务 |   

4. 数据库

|  知识点  | 内容 |                   里程碑                   | 
| :------: | :--: | :----------------------------------------: | 
|   SQL    |      |                                            |  
| MongoDB  |      |                                            |    
|  Redis   |      |                                            |    
| RabbitMQ |      |                                            |   
|  Kafka   |      | 利用数据库和MQ，实现一个多机的交易撮合系统 |   



### 进阶

1. 分布式

|         知识点          |                             内容                             |                      里程碑                      | 
| :---------------------: | :----------------------------------------------------------: | :----------------------------------------------: | 
|           RPC           | [远程过程调用(RPC)详解](https://waylau.com/remote-procedure-calls/) | 编写一个程序，能够用一种接口完成调用BTC和ETH转账 | 
|     分布式文件系统      | [分布式存储系统知识体系](http://wuchong.me/blog/2014/08/07/distributed-storage-system-knowledge/) |                                                  |  
|      Lamport时间戳      | [分布式系统：Lamport 逻辑时钟](https://blog.xiaohansong.com/lamport-logic-clock.html) |                                                  |  
| distributed replication | [寻找一种易于理解的一致性算法](https://github.com/maemual/raft-zh_cn) |                                                  |    
|         BFT协议         | [拜占庭共识算法之PBFT](https://www.jianshu.com/p/fb5edf031afd) |                                                  |   
|      匿名路由协议       | [Tor: 洋葱服务协议](https://www.skactor.tk/2018/04/11/tor-洋葱服务协议/) |                                                  |  

2. 密码学

|      知识点      |                             内容                             |             里程碑             | 
| :--------------: | :----------------------------------------------------------: | :----------------------------: | 
|     数论基础     | [现代密码学中的数论基础知识梳理](https://www.cnblogs.com/qcblog/p/8976017.html) |                                |    
|     RSA算法      | [RSA算法原理](http://www.ruanyifeng.com/blog/2013/06/rsa_algorithm_part_one.html) |   实现一个 RSA 消息加密系统    |    
| 签名或多签名算法 | [数字签名是什么](http://www.ruanyifeng.com/blog/2011/08/what_is_a_digital_signature.html) | 用OpenPGP 发送一封有签名的邮件 |  
|    零知识证明    | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) |                                | 
|       VRF        |                         RSA VRF.pdf                          |                                |   

3. 比特币和以太坊

|        知识点        |                             内容                             |                            里程碑                            |
| :------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | 
|      比特币基础      | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) | 编译BTC;用Go语言编写一个交易的编码程序(把交易编码成BTC的数据格式) |   
| 区块和交易的数据结构 | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) |                 用Go语言实现一个区块解码程序                 |   
|     Merkle Tree      | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) |                         编写一个MKT                          |   
|       PoW算法        | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) |                         编写一个PoW                          |   
|       支付脚本       | [精通比特币](http://ibloodline.com/articles/2018/01/26/master-bitcoin.html) |                  如何用支付脚本实现隔离见证                  |  
|         EVM          | - [以太坊虚拟机EVM执行原理](http://www.jouypub.com/2018/e7837187669426cba873450586b4a368/) |                                                              |    
|       Solidity       | [根据例子学习Solidity](https://solidity-cn.readthedocs.io/zh/develop/solidity-by-example.html) |     根据教程运行并dump EVM code;实现一个ETH上的Dice游戏      |  
|         POS          | [共识算法的比较：Casper vs Tendermint](https://lilymoana.github.io/ConsensusCompare.html) |                                                              |   
|    君士坦丁堡分叉    |                                                              |                                                              |    

### 专家

|       知识点       |                             内容                             | 里程碑 |
| :----------------: | :----------------------------------------------------------: | :----: |
|    BFT算法家族     |                         BFT家族.pptx                         |        |  
|    VRF与安全性     | Algorand Scaling Byzantine Agreements for Cryptocurrencies.pdf |        |  
| Zcash和零知识证明  |                  zkSNARKs in a Nutshell.pdf                  |        |   
|   分片和可拓展性   |           On Scaling Decentralized Blockchains.pdf           |        |  
