# 《分布式系统开发实战》目录

第 1章　分布式系统概述　1

1.1　什么是分布式系统　1

1.2　分布式系统常用术语　2

1.3　集中式系统与分布式系统　3

1.4　分布式系统特征　4

1.5　设计分布式系统所面临的挑战　5

1.6　本章小结　6

1.7　习题　6

第　2章 节点　7

2.1　什么是线程　7

2.2　进程和线程　8

2.3　线程和纤程　8

2.4　编程语言中的线程对象　9

2.4.1　定义和启动一个线程　9

2.4.2　暂停线程执行　9

2.4.3　中断线程　10

2.4.4　等待另一个线程完成　11

2.5　节点之间的通信　11

2.5.1　消息丢失　11

2.5.2　消息乱序　12

2.5.3　数据错误　12

2.5.4　不可靠的TCP　12

2.6　本章小结　12

2.7　习题　13

第3章　通信　14

3.1　本地过程调用　14

3.1.1　本地过程调用的概念　14

3.1.2　本地过程调用的实现　14

3.2　远程过程调用　16

3.2.1　远程过程调用原理　16

3.2.2　如何实现远程过程调用　18

3.2.3　远程过程调用API　20

3.2.4　远程过程调用发展历程　20

3.3　常用网络I/O模型　21

3.3.1　阻塞I/O模型　21

3.3.2　非阻塞I/O模型　22

3.3.3　I/O复用模型　22

3.3.4　信号驱动I/O模型　23

3.3.5　异步I/O模型　23

3.3.6　几种I/O模型的比较　24

3.4　I/O操作中的常用术语　25

3.4.1　阻塞和非阻塞　25

3.4.2　同步与异步　25

3.4.3　总结　25

3.5　实战：在Java中实现常用网络I/O模型　26

3.5.1　Java OIO　26

3.5.2　Java NIO　29

3.5.3　Java AIO　33

3.6　事件驱动　37

3.6.1　事件驱动编程　37

3.6.2　事件循环的实现　38

3.6.3　Reactor模型　38

3.6.4　Proactor模型　40

3.7　本章小结　41

3.8　习题　41

第4章　并发与并行　42

4.1　并发与并行的区别　42

4.2　线程与并发　43

4.3　并发带来的风险　43

4.3.1　死锁　44

4.3.2　饥饿　45

4.3.3　活锁　45

4.4　解决并发风险　45

4.4.1　同步　45

4.4.2　原子访问　49

4.5　提升系统并发能力　49

4.5.1　无锁化设计提升并发能力　49

4.5.2　缓存提升并发能力　49

4.5.3　更细颗粒度的并发单元　50

4.6　本章小结　50

4.7　习题　50

第5章　面向对象的分布式架构　51

5.1　基于对象的分布式架构　51

5.2　常用的分布式对象系统　52

5.2.1　微软DCOM　52

5.2.2　CORBA　53

5.2.3　Java RMI　54

5.3　分布式对象系统优缺点　57

5.4　实战：基于Java RMI实现分布式对象通信　57

5.4.1　示例概述　57

5.4.2　编写RMI服务器　58

5.4.3　编写RMI客户端　60

5.4.4　运行　61

5.5　本章小结　61

5.6　习题　62

第6章　面向服务的分布式架构　63

6.1　什么是面向服务的架构　63

6.2　SOA的基本概念　64

6.3　基于Web服务的SOA　65

6.3.1　XML-RPC　66

6.3.2　SOAP　66

6.3.3　Microsoft .NET Remoting　69

6.3.4　Java中的XML Web服务　75

6.3.5　超越SOAP　75

6.3.6　SOA的演变　76

6.4　Web服务的分类　76

6.4.1　“大”Web服务　76

6.4.2　RESTful Web服务　77

6.4.3　Web服务技术选型　77

6.5　实战：基于JAX-WS实现Web服务　78

6.5.1　JAX-WS概述　78

6.5.2　创建Web服务器和客户端的基本步骤　78

6.5.3　JAX-WS终端要求　79

6.5.4　创建基于JAX-WS的服务器　79

6.5.5　创建基于JAX-WS的客户端　80

6.5.6　运行　80

6.6　本章小结　82

6.7　习题　82

第7章　面向消息的分布式架构　83

7.1　什么是面向消息的分布式架构　83

7.1.1　常用术语　83

7.1.2　使用场景　83

7.1.3　常用技术　84

7.2　常见消息中间件产品介绍　84

7.2.1　Apache ActiveMQ　84

7.2.2　RabbitMQ　85

7.2.3　Apache RocketMQ　86

7.3　消息通信常用模式　88

7.3.1　工作队列　88

7.3.2　发布/订阅　89

7.3.3　路由　90

7.3.4　主题　91

7.3.5　RPC　92

7.4　了解JMS规范　94

7.4.1　JMS消息风格　94

7.4.2　JMS接口　95

7.5　实战：基于JMS的消息发送和接收　96

7.5.1　项目概述　96

7.5.2　项目配置　97

7.5.3　编码实现　99

7.5.4　运行　104

7.6　本章小结　107

7.7　习题　108

第8章　REST风格的架构　109

8.1　什么是REST　109

8.2　REST设计原则　110

8.3　成熟度模型　111

8.3.1　第0级：使用HTTP作为传输方式　111

8.3.2　第 1级：引入了资源的概念　113

8.3.3　第 2级：根据语义使用HTTP动词　113

8.3.4　第3级：使用HATEOAS　114

8.4　REST API管理　116

8.5　常用技术　118

8.5.1　JAX-RS规范　118

8.5.2　Jersey　123

8.5.3　Apache CXF　123

8.5.4　Spring Web MVC　124

8.6　实战：基于Java实现REST API　124

8.6.1　基于Jersey来构建REST服务　124

8.6.2　基于Apache CXF来构建REST服务　131

8.6.3　基于Spring Web MVC来构建REST服务　140

8.7　本章小结　145

8.8　习题　145

第9章　微服务架构　146

9.1　什么是微服务架构　146

9.2　微服务架构与SOA架构的区别　147

9.2.1　单体架构的例子　147

9.2.2　微服务架构的例子　148

9.3　何时采用微服务架构　150

9.4　常用技术　150

9.4.1　Jetty HTTP Server　151

9.4.2　构建REST程序　151

9.4.3　运行　153

9.5　实战：基于Spring Boot实现微服务　153

9.5.1　配置环境　153

9.5.2　REST API设计　154

9.5.3　编写程序代码　155

9.5.4　安装REST客户端　159

9.5.5　运行、测试程序　160

9.6　微服务与通信　160

9.6.1　HTTP通信　161

9.6.2　消息通信　161

9.6.3　事件驱动的通信　161

9.7　了解CQRS　162

9.7.1　CQRS概述　162

9.7.2　CQRS与Event Sourcing的关系　163

9.7.3　CQRS好处　164

9.8　实战：基于CQRS微服务通信　164

9.8.1　配置　165

9.8.2　Aggregate　165

9.8.3　Command　168

9.8.4　Event　169

9.8.5　测试　170

9.9　本章小结　171

9.10　习题　171

第　10章 Serverless架构　172

10.1　什么是Serverless架构　172

10.2　Serverless架构的典型应用　173

10.2.1　UI驱动的应用　173

10.2.2　消息驱动的应用　174

10.3　常见的Serverless架构　175

10.3.1　AWS Lambda　175

10.3.2　Google Cloud Functions　175

10.3.3　Iron.io　175

10.3.4　IBM OpenWhisk　175

10.3.5　Serverless Framework　176

10.3.6　Azure WebJobs　176

10.4　Serverless架构原则　176

10.4.1　根据需要使用计算服务执行代码　177

10.4.2　编写单一用途的无状态函数　177

10.4.3　设计基于推送的、事件驱动的管道　177

10.4.4　创建更粗实、更强大的前端　177

10.4.5　拥抱第三方服务　178

10.5　实战：使用AWS平台实现Serverless架构　178

10.6　本章小结　182

10.7　习题　182

第　11章 Cloud Native架构　183

11.1　Cloud Native概述　183

11.1.1　软件需求的发展　183

11.1.2　开发方式的巨变　184

11.1.3　云是大势所趋　185

11.2　Cloud Native特性　185

11.2.1　以云为基础架构　186

11.2.2　云服务　186

11.2.3　无服务　186

11.2.4　可扩展　187

11.2.5　高可用　189

11.2.6　敏捷　190

11.2.7　云优先　190

11.3　12-Factor　191

11.3.1　基准代码　192

11.3.2　依赖　192

11.3.3　配置　193

11.3.4　后端服务　193

11.3.5　构建、发布、运行　193

11.3.6　进程　194

11.3.7　端口绑定　194

11.3.8　并发　195

11.3.9　易处理　196

11.3.10　开发环境与线上环境等价　196

11.3.11　日志　196

11.3.12　管理进程　197

11.4　Cloud Native成功案例分析　197

11.4.1　Amazon　197

11.4.2　Netflix　198

11.4.3　淘宝网　199

11.5　Cloud Native与微服务架构的关系　201

11.6　Cloud Native与Serverless架构的关系　201

11.7　Cloud Native的优点及面临的挑战　201

11.7.1　Cloud Native优点　201

11.7.2　Cloud Native不是“银弹”　202

11.7.3　面临的挑战　203

11.8　本章小结　203

11.9　习题　203

第　12章 虚拟化与容器技术　204

12.1　虚拟化技术　204

12.2　容器与虚拟机　204

12.2.1　成熟度方面的比较　205

12.2.2　启动速度的比较　205

12.2.3　安全方面的比较　205

12.2.4　性能方面的比较　206

12.3　基于容器的持续部署　206

12.3.1　持续部署管道　207

12.3.2　测试　207

12.3.3　构建　208

12.3.4　部署　209

12.3.5　蓝－绿部署　209

12.3.6　运行预集成以及集成后测试　210

12.3.7　回滚与清理　211

12.3.8　决定每个步骤的执行环境　212

12.3.9　完成整个持续部署流　212

12.4　容器技术与微服务架构　212

12.4.1　基于Google Kubernetes架构　213

12.4.2　基于DaoCloud DCE架构　213

12.5　容器技术与Cloud Native架构　213

12.6　实战：基于Docker发布微服务　214

12.6.1　创建微服务　214

12.6.2　微服务容器化　214

12.6.3　使用Gradle来构建Docker image　215

12.6.4　运行image　216

12.6.5　访问应用　217

12.6.6　关闭容器　217

12.6.7　Docker发布微服务　217

12.7　本章小结　217

12.8　习题　217

第　13章 分布式计算　218

13.1　分布式计算概述　218

13.2　分布式计算应用场景　218

13.3　分布式计算常用技术　219

13.3.1　MapReduce　219

13.3.2　Apache Hadoop　221

13.3.3　Apache Spark　222

13.4　实战：基于Spark词频统计　223

13.4.1　项目概述　224

13.4.2　项目配置　224

13.4.3　编码实现　224

13.4.4　运行　225

13.5　本章小结　227

13.6　习题　227

第　14章 分布式存储　228

14.1　分布式存储概述　228

14.2　分布式存储应用场景　228

14.3　分布式存储常用技术　229

14.3.1　Bigtable　229

14.3.2　Apache HBase　231

14.3.3　Apache Cassandra　233

14.3.4　Memcached　235

14.3.5　Redis　237

14.3.6　MongoDB　237

14.4　实战：基于MongoDB文件服务器　239

14.4.1　文件服务器的需求　239

14.4.2　所需技术　239

14.4.3　文件服务器的实现　241

14.4.4　运行　247

14.4.5　其他配置项　247

14.5　本章小结　248

14.6　习题　248

第　15章 分布式监控　249

15.1　分布式监控概述　249

15.2　分布式监控应用场景　249

15.3　分布式监控常用技术　249

15.3.1　Nagios　250

15.3.2　Zabbix　250

15.3.3　Consul　253

15.3.4　ZooKeeper　255

15.4　实战：基于ZooKeeper的服务注册和发现　258

15.4.1　项目概述　258

15.4.2　项目配置　258

15.4.3　编码实现　259

15.4.4　运行　262

15.5　本章小结　264

15.6　习题　264

第　16章 分布式版本控制　265

16.1　版本控制系统简史　265

16.2　集中式与分布式版本控制系统　265

16.3　常用技术　266

16.3.1　Bazaar　266

16.3.2　Mercurial　266

16.3.3　Git　267

16.4　了解Git Flow　269

16.4.1　分支定义　269

16.4.2　新功能开发工作流　269

16.4.3　Bug修复工作流　270

16.4.4　版本发布工作流　270

16.5　本章小结　271

16.6　习题　271

第　17章 数据一致性　272

17.1　什么是CAP理论　272

17.2　为什么CAP只能三选二　273

17.3　CAP常见模型　274

17.3.1　牺牲分区容错性（CA模型）　274

17.3.2　牺牲可用性（CP模型）　274

17.3.3　牺牲一致性（AP模型）　274

17.4　CAP的意义及发展　275

17.4.1　CAP最新发展　275

17.4.2　BASE　275

17.5　以数据为中心的一致性模型　276

17.5.1　严格一致性　276

17.5.2　持续一致性　276

17.5.3　顺序一致性　276

17.5.4　因果一致性　276

17.5.5　入口一致性　276

17.6　以客户为中心的一致性模型　277

17.6.1　单调读一致性　277

17.6.2　单调写一致性　277

17.6.3　读写一致性　277

17.6.4　写读一致性　277

17.7　本章小结　278

17.8　习题　278

第　18章 分布式事务　279

18.1　本地事务　279

18.1.1　一个银行转账的例子　279

18.1.2　事务隔离级别　280

18.2　分布式事务面临的挑战　282

18.3　节点复制　283

18.3.1　Master-Slave复制　283

18.3.2　Master-Master多主复制　283

18.4　两阶段提交　283

18.4.1　准备阶段　284

18.4.2　提交阶段　284

18.4.3　两阶段提交状态机　284

18.4.4　两阶段提交的缺陷　285

18.5　三阶段提交　285

18.5.1　CanCommit　285

18.5.2　PreCommit　286

18.5.3　DoCommit　286

18.5.4　三阶段提交状态机　286

18.5.5　三阶段提交的缺陷　287

18.6　Paxos算法　287

18.6.1　问题描述　287

18.6.2　提案的选定　288

18.6.3　获取被选定的提案值　289

18.6.4　进展性　290

18.6.5　实现　290

18.6.6　总结　291

18.6.7　缺陷　292

18.7　Raft算法　292

18.7.1　Raft概述　293

18.7.2　复制状态机　293

18.7.3　Raft算法基础　294

18.7.4　Raft算法Leader选举　296

18.7.5　Raft算法日志同步　297

18.7.6　Raft算法安全性　299

18.7.7　处理Follower和Candidate异常　302

18.7.8　时间要求及可用性　302

18.7.9　集群成员关系变更　303

18.7.10　日志压缩　305

18.7.11　客户端交互　306

18.7.12　总结　307

18.8　消息　307

18.8.1　本地消息表　308

18.8.2　事务消息　308

18.8.3　如何保障幂等性　309

18.8.4　总结　310

18.9　本章小结　310

18.10　习题　310

第　19章 安全性　311

19.1　基本概念　311

19.1.1　安全威胁、策略和机制　311

19.1.2　密码与数字签名　312

19.2　加密算法　313

19.2.1　对称加密　313

19.2.2　使用对称密钥加密的数字签名　313

19.2.3　非对称加密　314

19.2.4　使用公钥加密的数字签名　315

19.3　安全通道　315

19.3.1　SSL/TLS　315

19.3.2　SSL握手过程　316

19.3.3　HTTPS　318

19.4　访问控制　318

19.4.1　防火墙　319

19.4.2　堡垒机　319

19.4.3　拒绝服务　319

19.4.4　访问控制的模型　320

19.5　实战：基于Spring Security实现安全认证　320

19.5.1　添加依赖　321

19.5.2　添加业务代码　322

19.5.3　配置消息转换器　322

19.5.4　配置Spring Security　323

19.5.5　创建应用配置类　324

19.5.6　创建内嵌Jetty的服务器　324

19.5.7　应用启动器　325

19.5.8　运行应用　326

19.6　本章小结　327

19.7　习题　327

第　20章 可用性　328

20.1　故障不可避免　328

20.2　使用冗余提升系统可用性　328

20.3　常用副本控制协议　329

20.3.1　中心化副本控制协议　329

20.3.2　primary-secondary协议　329

20.3.3　去中心化副本控制协议　331

20.4　负载均衡技术　332

20.4.1　客户端发现模式　332

20.4.2　服务端发现模式　333

20.5　实战：基于NGINX实现服务高可用　334

20.5.1　配置负载均衡　334

20.5.2　负载均衡常用算法　335

20.5.3　实现Web服务的高可用　336

20.5.4　运行　336

20.6　本章小结　337

20.7　习题　337

第　21章 综合实战：基于Spring Cloud的微服务架构设计与实现　338

21.1　Spring Cloud概述　338

21.1.1　什么是Spring Cloud　338

21.1.2　Spring Cloud与Spring Boot的关系　339

21.2　Spring Cloud入门配置　339

21.2.1　Maven配置　339

21.2.2　Gradle配置　340

21.2.3　声明式方法　340

21.3　Spring Cloud的子项目介绍　341

21.3.1　Spring Cloud子项目的组成　341

21.3.2　Spring Cloud组件的版本　342

21.4　实现微服务的注册与发现　343

21.4.1　服务发现的意义　343

21.4.2　如何集成Eureka Server　343

21.4.3　如何集成Eureka Client　347

21.4.4　实现服务的注册与发现　347

21.5　本章小结　348

21.6　习题　348

附录　本书所涉及的软件及相关版本　349

参考文献　350