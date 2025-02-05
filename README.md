# Java生态资源大全

这里汇总了Java生态圈中的各种框架、库、中间件，包括Web开发、大数据、桌面开发、机器学习、软件测试、物联网、Android等领域。

所有框架和库都是基于Java语言实现的，只有极少数是由Kotlin、Scala、Groovy等JVM系语言混合开发，并且也可以在Java中兼容使用。

## 目录

* [开发框架](#开发框架)
  * [Web框架](#Web框架)
  * [RPC框架](#RPC框架)
  * [JSF框架](#JSF框架)
  * [REST框架](#REST框架)
  * [ORM框架](#ORM框架)
  * [持久层库](#持久层库)
  * [应用框架](#应用框架)
  * [微服务框架](#微服务框架)
  * [Spring Cloud](#SpringCloud)
* [微服务工具](#微服务工具)
* [REST错误处理](#REST错误处理)
* [测试](#测试)
  * [单元测试](#单元测试)
  * [集成测试](#集成测试)
  * [接口测试](#接口测试)
  * [功能测试](#功能测试)
  * [突变测试](#突变测试)
  * [模糊测试](#模糊测试)
  * [性能测试](#性能测试)
  * [属性测试](#属性测试)
  * [A/B测试](#AB测试)
  * [验收测试](#验收测试)
  * [回归测试](#回归测试)
  * [契约测试](#契约测试)
  * [渗透测试](#渗透测试)
  * [快照测试](#快照测试)
  * [断言库](#断言库)
  * [Mock框架](#Mock框架)
  * [接口Mock](#接口Mock)
  * [Mock库](#Mock库)
  * [数据Mock](#数据Mock)
  * [BDD框架](#BDD框架)
  * [测试生成器](#测试生成器)
  * [Selenium生态](#Selenium生态)
  * [自动化框架](#自动化框架)
  * [自动化工具](#自动化工具)
  * [QA自动化](#QA自动化)
  * [测试报告](#测试报告)
  * [多线程测试](#多线程测试)
  * [JUnit扩展](#JUnit扩展)
  * [其他测试库](#其他测试库)
  * [测试套件](#测试套件)
* [代码覆盖率](#代码覆盖率)
* [构建工具](#构建工具)
* [包管理器](#包管理器)
* [CI/CD](#CICD)
* [工件仓库](#工件仓库)
* [静态分析](#静态分析)
* [Java环境管理](#Java环境管理)
* [JDK](#JDK)
* [JVM语言](#JVM语言)
* [JVM实现](#JVM实现)
* [IDE](#IDE)
* [在线编辑器](#在线编辑器)
* [项目管理](#项目管理)
* [原型工具](#原型工具)
* [云原生](#云原生)
* [云计算](#云计算)
* [Serverless](#Serverless)
* [容器化工具](#容器化工具)
* [DevOps](#DevOps)
* [云服务](#云服务)
* [APM](#APM)
* [分布式追踪](#分布式追踪)
* [指标报告](#指标报告)
* [API网关](#API网关)
* [服务发现](#服务发现)
* [容错组件](#容错组件)
  * [限流/降级](#限流降级)
  * [重试](#重试)
  * [负载均衡](#负载均衡)
* [混沌工程](#混沌工程)
* [流量回放](#流量回放)
* [大数据](#大数据)
  * [大数据框架](#大数据框架)
  * [大数据工具](#大数据工具)
  * [大数据组件](#大数据组件)
  * [数据可视化](#数据可视化)
  * [数据目录](#数据目录)
  * [查询引擎](#查询引擎)
  * [存储格式](#存储格式)
  * [流处理平台](#流处理平台)
  * [ETL工具](#ETL工具)
  * [CDC组件](#CDC组件)
  * [Notebook](#Notebook)
  * [数据同步](#数据同步)
  * [数据湖框架](#数据湖框架)
  * [数据Shuffle](#数据Shuffle)
* [进程间通信](#进程间通信)
  * [消息中间件](#消息中间件)
  * [事件总线](#事件总线)
  * [消息总线](#消息总线)
  * [应用总线](#应用总线)
* [分布式开发](#分布式开发)
  * [分布式组件](#分布式组件)
  * [分布式锁](#分布式锁)
  * [分布式事务](#分布式事务)
  * [分布式ID](#分布式ID)
  * [Raft算法](#Raft算法)
  * [Paxos算法](#Paxos算法)
* [数据库](#数据库)
  * [搜索引擎](#搜索引擎)
  * [图数据库](#图数据库)
  * [键值存储](#键值存储)
  * [数据网格](#数据网格)
  * [时序数据库](#时序数据库)
  * [嵌入式数据库](#嵌入式数据库)
  * [关系型数据库](#关系型数据库)
  * [NoSQL数据库](#NoSQL数据库)
  * [OLAP数据库](#OLAP数据库)
  * [向量数据库](#向量数据库)
  * [对象数据库](#对象数据库)
  * [Datalog数据库](#Datalog数据库)
  * [其他数据库](#其他数据库)
* [图处理](#图处理)
* [数据库中间件](#数据库中间件)
* [数据库连接池](#数据库连接池)
* [HTTP客户端](#HTTP客户端)
* [响应式](#响应式)
* [服务器](#服务器)
  * [Web服务器](#Web服务器)
  * [WebSocket服务器](#WebSocket服务器)
  * [FTP服务器](#FTP服务器)
* [Jakarta EE产品](#JakartaEE产品)
* [工具库](#工具库)
* [Bean映射&复制](#Bean映射复制)
* [IoC](#IoC)
* [AOP](#AOP)
* [日志库](#日志库)
* [Logback Appender](#LogbackAppender)
* [结构化日志](#结构化日志)
* [JSON库](#JSON库)
* [JsonPath](#JsonPath)
* [序列化](#序列化)
* [缓存库](#缓存库)
* [集合库](#集合库)
* [并发编程](#并发编程)
  * [Future扩展](#Future扩展)
  * [协程库](#协程库)
  * [Async/Await](#AsyncAwait)
  * [线程池](#线程池)
  * [Actor模型](#Actor模型)
  * [ThreadLocal](#ThreadLocal)
  * [并发数据结构](#并发数据结构)
  * [竞争检测](#竞争检测)
* [任务调度](#任务调度)
* [配置管理](#配置管理)
* [功能切换](#功能切换)
* [业务流](#业务流)
* [规则引擎](#规则引擎)
* [商业智能](#商业智能)
* [SMT求解器](#SMT求解器)
* [API管理](#API管理)
* [GraphQL](docs/doc2.md#GraphQL)
* [日期时间](docs/doc2.md#日期时间)
* [人工智能](docs/doc2.md#人工智能)
  * [LLM](docs/doc2.md#LLM)
  * [LLM客户端](docs/doc2.md#LLM客户端)
  * [机器学习](docs/doc2.md#机器学习)
  * [自然语言处理](docs/doc2.md#自然语言处理)
  * [深度学习](docs/doc2.md#深度学习)
  * [语义解析](docs/doc2.md#语义解析)
  * [信息提取](docs/doc2.md#信息提取)
  * [联邦学习](docs/doc2.md#联邦学习)
  * [遗传算法](docs/doc2.md#遗传算法)
  * [专家系统](docs/doc2.md#专家系统)
  * [约束编程](docs/doc2.md#约束编程)
  * [差分隐私](docs/doc2.md#差分隐私)
  * [计算机视觉](docs/doc2.md#计算机视觉)
  * [光学字符识别](docs/doc2.md#光学字符识别)
* [实体解析](docs/doc2.md#实体解析)
* [数据科学](docs/doc2.md#数据科学)
* [异常检测](docs/doc2.md#异常检测)
* [指纹识别](docs/doc2.md#指纹识别)
* [推荐系统](docs/doc2.md#推荐系统)
* [逻辑编程](docs/doc2.md#逻辑编程)
* [多智能体](docs/doc2.md#多智能体)
* [MATLAB](docs/doc2.md#MATLAB)
* [Jupyter](docs/doc2.md#Jupyter)
* [元启发式框架](docs/doc2.md#元启发式框架)
* [机器人开发](docs/doc2.md#机器人开发)
* [数学库](docs/doc2.md#数学库)
* [本体库](docs/doc2.md#本体库)
* [语义Web](docs/doc2.md#语义Web)
* [知识图谱](docs/doc2.md#知识图谱)
* [生物信息学](docs/doc2.md#生物信息学)
* [基因组学](docs/doc2.md#基因组学)
* [医疗平台](docs/doc2.md#医疗平台)
* [化学库](docs/doc2.md#化学库)
* [安全](docs/doc2.md#安全)
  * [身份认证和授权](docs/doc2.md#身份认证和授权)
  * [JWT库](docs/doc2.md#JWT库)
  * [OAuth库](docs/doc2.md#OAuth库)
  * [安全库](docs/doc2.md#安全库)
  * [安全工具](docs/doc2.md#安全工具)
  * [自保护](docs/doc2.md#自保护)
  * [跨域身份管理](docs/doc2.md#跨域身份管理)
  * [加密库](docs/doc2.md#加密库)
  * [密码库](docs/doc2.md#密码库)
  * [加密算法](docs/doc2.md#加密算法)
  * [接口加密](docs/doc2.md#接口加密)
* [模板引擎](docs/doc2.md#模板引擎)
* [应用分析与监控](docs/doc2.md#应用分析与监控)
  * [诊断工具](docs/doc2.md#诊断工具)
  * [性能分析](docs/doc2.md#性能分析)
  * [Spring Boot仪表板](docs/doc2.md#SpringBoot仪表板)
  * [日志分析](docs/doc2.md#日志分析)
  * [GC日志分析](docs/doc2.md#GC日志分析)
  * [堆转储](docs/doc2.md#堆转储)
  * [线程转储](docs/doc2.md#线程转储)
  * [对象测量](docs/doc2.md#对象测量)
  * [火焰图](docs/doc2.md#火焰图)
* [脚本](docs/doc2.md#脚本)
* [CLI工具](docs/doc2.md#CLI工具)
* [命令行参数解析](docs/doc2.md#命令行参数解析)
* [Git工具](docs/doc2.md#Git工具)
* [函数式编程](docs/doc2.md#函数式编程)
  * [函数式异常处理](docs/doc2.md#函数式异常处理)
  * [Stream工具库](docs/doc2.md#Stream工具库)
  * [Lambda扩展](docs/doc2.md#Lambda扩展)
  * [LINQ](docs/doc2.md#LINQ)
  * [模式匹配](docs/doc2.md#模式匹配)
  * [定理证明](docs/doc2.md#定理证明)
* [字节码操作](docs/doc2.md#字节码操作)
* [字节码工具库](docs/doc2.md#字节码工具库)
* [图像处理](docs/doc2.md#图像处理)
* [SVG库](docs/doc2.md#SVG库)
* [验证码](docs/doc2.md#验证码)
* [压缩库](docs/doc2.md#压缩库)
* [数组库](docs/doc2.md#数组库)
* [反射库](docs/doc2.md#反射库)
* [注解库](docs/doc2.md#注解库)
* [爬虫框架](docs/doc2.md#爬虫框架)
* [批处理框架](docs/doc2.md#批处理框架)
* [注解处理器](docs/doc2.md#注解处理器)
* [字符串工具库](docs/doc2.md#字符串工具库)
* [字符串插值](docs/doc2.md#字符串插值)
* [Java 9-22](docs/doc2.md#9-22特性)
* [接口文档](docs/doc2.md#接口文档)
* [技术文档](docs/doc2.md#技术文档)
* [Javadoc](docs/doc2.md#Javadoc)
* [文件解析](docs/doc2.md#文件解析)
  * [PDF库](docs/doc2.md#PDF库)
  * [Excel库](docs/doc2.md#Excel库)
  * [CSV库](docs/doc2.md#CSV库)
  * [Word库](docs/doc2.md#Word库)
  * [PPT库](docs/doc2.md#PPT库)
  * [Toml库](docs/doc2.md#Toml库)
  * [HTML库](docs/doc2.md#HTML库)
  * [XML库](docs/doc2.md#XML库)
  * [YML库](docs/doc2.md#YML库)
  * [Outlook库](docs/doc2.md#Outlook库)
  * [License库](docs/doc2.md#License库)
  * [Markdown库](docs/doc2.md#Markdown库)
  * [文件库](docs/doc2.md#文件库)
  * [文件转换](docs/doc2.md#文件转换)
* [集群管理](docs/doc2.md#集群管理)
* [软件质量](docs/doc2.md#软件质量)
* [编码规范](docs/doc2.md#编码规范)
* [依赖分析](docs/doc2.md#依赖分析)
* [污点分析](docs/doc2.md#污点分析)
* [审计框架](docs/doc2.md#审计框架)
* [代码属性图](docs/doc2.md#代码属性图)
* [API变更管理](docs/doc2.md#API变更管理)
* [源代码浏览器](docs/doc2.md#源代码浏览器)
* [脚手架](docs/doc2.md#脚手架)
* [低代码](docs/doc2.md#低代码)
* [Data API](docs/doc2.md#DataAPI)
* [POS](docs/doc2.md#POS)
* [业务](docs/doc2.md#业务)
* [电商](docs/doc2.md#电商)
* [支付](docs/doc2.md#支付)
* [云服务SDK](docs/doc2.md#云服务SDK)
* [微信开发](docs/doc2.md#微信开发)
* [推送SDK](docs/doc2.md#推送SDK)
* [API&客户端](docs/doc2.md#API客户端)
  * [Git](docs/doc2.md#Git)
  * [Twitter](docs/doc2.md#Twitter)
  * [Facebook](docs/doc2.md#Facebook)
  * [Instagram](docs/doc2.md#Instagram)
  * [Slack](docs/doc2.md#Slack)
  * [Reddit](docs/doc2.md#Reddit)
  * [TikTok](docs/doc2.md#TikTok)
  * [Spotify](docs/doc2.md#Spotify)
* [Docker客户端](docs/doc2.md#Docker客户端)
* [Consul客户端](docs/doc2.md#Consul客户端)
* [Kubernetes客户端](docs/doc2.md#Kubernetes客户端)
* [消息队列客户端](docs/doc2.md#消息队列客户端)
* [Etcd客户端](docs/doc2.md#Etcd客户端)
* [即时通讯](docs/doc2.md#即时通讯)
* [视频会议](docs/doc2.md#视频会议)
* [Web3](docs/doc2.md#Web3)
  * [区块链](docs/doc2.md#区块链)
  * [以太坊](docs/doc2.md#以太坊)
  * [比特币](docs/doc2.md#比特币)
  * [区块链SDK](docs/doc2.md#区块链SDK)
  * [智能合约](docs/doc2.md#智能合约)
* [物联网](docs/doc2.md#物联网)
  * [物联网框架/工具](docs/doc2.md#物联网框架工具)
  * [车联网](docs/doc2.md#车联网)
  * [嵌入式](docs/doc2.md#嵌入式)
  * [MQTT](docs/doc2.md#MQTT)
  * [串口](docs/doc2.md#串口)
  * [Modbus](docs/doc2.md#Modbus)
  * [USB库](docs/doc2.md#USB库)
* [金融](docs/doc2.md#金融)
* [电子发票](docs/doc2.md#电子发票)
* [短信](docs/doc2.md#短信)
* [DSL](docs/doc2.md#DSL)
* [JMX](docs/doc2.md#JMX)
* [RMI](docs/doc2.md#RMI)
* [gRPC](docs/doc2.md#gRPC)
* [对象池](docs/doc2.md#对象池)
* [CQRS框架](docs/doc2.md#CQRS框架)
* [DDD框架](docs/doc2.md#DDD框架)
* [软件工程](docs/doc2.md#软件工程)
* [设计模式](docs/doc2.md#设计模式)
* [幂等处理](docs/doc2.md#幂等处理)
* [数据字典](docs/doc2.md#数据字典)
* [迁移&重构](docs/doc2.md#迁移重构)
* [Bot](docs/doc2.md#Bot)
* [安卓库](docs/doc2.md#安卓库)
* [GUI开发/程序](docs/doc2.md#GUI开发程序)
  * [GUI框架](docs/doc2.md#GUI框架)
  * [Swing](docs/doc2.md#Swing)
  * [Swing主题库](docs/doc2.md#Swing主题库)
  * [Swing UI库](docs/doc2.md#SwingUI库)
  * [Swing组件库](docs/doc2.md#Swing组件库)
  * [Swing布局库](docs/doc2.md#Swing布局库)
  * [Swing选择器](docs/doc2.md#Swing选择器)
  * [Swing图表库](docs/doc2.md#Swing图表库)
  * [Swing测试库](docs/doc2.md#Swing测试库)
  * [JavaFX](docs/doc2.md#JavaFX)
  * [JavaFX主题库](docs/doc2.md#JavaFX主题库)
  * [JavaFX样式库](docs/doc2.md#JavaFX样式库)
  * [JavaFX组件库](docs/doc2.md#JavaFX组件库)
  * [JavaFX图表库](docs/doc2.md#JavaFX图表库)
  * [JavaFX图标库](docs/doc2.md#JavaFX图标库)
  * [JavaFX布局库](docs/doc2.md#JavaFX布局库)
  * [JavaFX渲染库](docs/doc2.md#JavaFX渲染库)
  * [浏览器](docs/doc2.md#浏览器)
  * [JavaFX小工具](docs/doc2.md#JavaFX小工具)
  * [GUI程序](docs/doc2.md#GUI程序)
  * [数学软件](docs/doc2.md#数学软件)
  * [UML工具](docs/doc2.md#UML工具)
  * [办公软件](docs/doc2.md#办公软件)
  * [思维导图](docs/doc2.md#思维导图)
  * [数据库软件](docs/doc2.md#数据库软件)
  * [数据库建模](docs/doc2.md#数据库建模)
  * [反编译](docs/doc2.md#反编译)
  * [代码混淆](docs/doc2.md#代码混淆)
  * [逆向工程](docs/doc2.md#逆向工程)
  * [文本编辑器](docs/doc2.md#文本编辑器)
* [游戏开发](docs/doc2.md#游戏开发)
  * [游戏引擎](docs/doc2.md#游戏引擎)
  * [游戏服务器](docs/doc2.md#游戏服务器)
  * [游戏开发库](docs/doc2.md#游戏开发库)
  * [寻路算法](docs/doc2.md#寻路算法)
  * [实体框架](docs/doc2.md#实体框架)
  * [游戏编辑器](docs/doc2.md#游戏编辑器)
  * [开源游戏](docs/doc2.md#开源游戏)
  * [游戏开发工具](docs/doc2.md#游戏开发工具)
* [2D/3D渲染](docs/doc2.md#2D3D渲染)
* [移动开发框架](docs/doc2.md#移动开发框架)
* [JVM代理](docs/doc2.md#JVM代理)
* [类加载](docs/doc2.md#类加载)
* [RISC-V](docs/doc2.md#RISC-V)
* [汇编](docs/doc2.md#汇编)
* [LLVM](docs/doc2.md#LLVM)
* [WebAssembly](docs/doc2.md#WebAssembly)
* [JavaScript](docs/doc2.md#JavaScript)
* [编译器&插件](docs/doc2.md#编译器插件)
* [语言服务器](docs/doc2.md#语言服务器)
* [数据库组件库](docs/doc3.md#数据库查询)
  * [数据库驱动](docs/doc3.md#数据库驱动)
  * [数据库迁移](docs/doc3.md#数据库迁移)
  * [数据源增强](docs/doc3.md#数据源增强)
  * [数据库工具](docs/doc3.md#数据库工具)
  * [存储过程](docs/doc3.md#存储过程)
  * [Redis库/工具](docs/doc3.md#Redis库工具)
  * [Kafka库/工具](docs/doc3.md#Kafka库工具)
  * [MongoDB库/工具](docs/doc3.md#MongoDB库工具)
  * [Cassandra库/工具](docs/doc3.md#Cassandra库工具)
  * [Memcached库/工具](docs/doc3.md#Memcached库工具)
  * [Zookeeper库/工具](docs/doc3.md#Zookeeper库工具)
  * [ClickHouse库/工具](docs/doc3.md#ClickHouse库工具)
  * [ElasticSearch库/工具](docs/doc3.md#ElasticSearch库工具)
  * [DynamoDB库/工具](docs/doc3.md#DynamoDB库工具)
* [Pub/Sub库](docs/doc2.md#PubSub库)
* [对象存储](docs/doc3.md#对象存储)
* [音视频处理](docs/doc3.md#音视频处理)
* [数据结构](docs/doc3.md#数据结构)
  * [树](docs/doc3.md#树)
  * [堆](docs/doc3.md#堆)
  * [图](docs/doc3.md#图)
  * [BitSet](docs/doc3.md#BitSet)
  * [队列](docs/doc3.md#队列)
  * [Map](docs/doc3.md#Map)
  * [List](docs/doc3.md#List)
  * [CRDT](docs/doc3.md#CRDT)
  * [布隆过滤器](docs/doc3.md#布隆过滤器)
  * [布谷鸟过滤器](docs/doc3.md#布谷鸟过滤器)
* [基本类型](docs/doc3.md#基本类型)
* [随机数生成器](docs/doc3.md#随机数生成器)
* [堆外内存管理](docs/doc3.md#堆外内存管理)
* [Struct](docs/doc3.md#Struct)
* [算法库](docs/doc3.md#算法库)
* [噪声库](docs/doc3.md#噪声库)
* [原生开发](docs/doc3.md#原生开发)
* [操作系统信息](docs/doc3.md#操作系统信息)
* [COM桥](docs/doc3.md#COM桥)
* [GPU编程](docs/doc3.md#GPU编程)
* [硬件操作](docs/doc3.md#硬件操作)
* [运动规划](docs/doc3.md#运动规划)
* [自动规划](docs/doc3.md#自动规划)
* [操作系统](docs/doc3.md#操作系统)
* [电力系统](docs/doc3.md#电力系统)
* [量子计算](docs/doc3.md#量子计算)
* [QA系统](docs/doc3.md#QA系统)
* [CMS系统](docs/doc3.md#CMS系统)
* [ERP系统](docs/doc3.md#ERP系统)
* [DMS系统](docs/doc3.md#DMS系统)
* [SCRM系统](docs/doc3.md#SCRM系统)
* [门户框架](docs/doc3.md#门户框架)
* [教育软件](docs/doc3.md#教育软件)
* [静态站点生成器](docs/doc3.md#静态站点生成器)
* [网络开发](docs/doc3.md#网络开发)
  * [网络库](docs/doc3.md#网络库)
  * [SSH工具](docs/doc3.md#SSH工具)
  * [DNS、内网穿透和代理](docs/doc3.md#DNS内网穿透和代理)
  * [IO_Uring](docs/doc3.md#IO_Uring)
  * [网络工具](docs/doc3.md#网络工具)
  * [SDN](docs/doc3.md#SDN)
  * [IP操作库](docs/doc3.md#IP操作库)
* [状态机](docs/doc3.md#状态机)
* [二维码生成器](docs/doc3.md#二维码生成器)
* [文件系统](docs/doc3.md#文件系统)
* [报表引擎](docs/doc3.md#报表引擎)
* [物流系统](docs/doc3.md#物流系统)
* [打包部署运行](docs/doc3.md#打包部署运行)
* [地理空间](docs/doc3.md#地理空间)
* [大地测量](docs/doc3.md#大地测量)
* [路由引擎](docs/doc3.md#路由引擎)
* [几何学](docs/doc3.md#几何学)
* [航空](docs/doc3.md#航空)
* [水文学](docs/doc3.md#水文学)
* [物理库](docs/doc3.md#物理库)
* [无人机](docs/doc3.md#无人机)
* [AIS库](docs/doc3.md#AIS库)
* [跨语言](docs/doc3.md#跨语言)
* [转换库](docs/doc3.md#转换库)
* [IO操作](docs/doc3.md#IO操作)
* [文件操作](docs/doc3.md#文件操作)
* [文件上传](docs/doc3.md#文件上传)
* [文件比较](docs/doc3.md#文件比较)
* [文件预览](docs/doc3.md#文件预览)
* [邮件操作](docs/doc3.md#邮件操作)
* [电子签名](docs/doc3.md#电子签名)
* [安全培训](docs/doc3.md#安全培训)
* [RSS](docs/doc3.md#RSS)
* [SSE](docs/doc3.md#SSE)
* [RPM](docs/doc3.md#RPM)
* [EPC](docs/doc3.md#EPC)
* [FMI](docs/doc3.md#FMI)
* [OSGI](docs/doc3.md#OSGI)
* [OData](docs/doc3.md#OData)
* [数控](docs/doc3.md#数控)
* [数电](docs/doc3.md#数电)
* [海关](docs/doc3.md#海关)
* [蓝牙](docs/doc3.md#蓝牙)
* [校验](docs/doc3.md#校验)
* [元编程](docs/doc3.md#元编程)
* [分词器](docs/doc3.md#分词器)
* [文本表](docs/doc3.md#文本表)
* [字体库](docs/doc3.md#字体库)
* [语言库](docs/doc3.md#语言库)
* [泛型库](docs/doc3.md#泛型库)
* [国际化](docs/doc3.md#国际化)
* [翻译库](docs/doc3.md#翻译库)
* [字典库](docs/doc3.md#字典库)
* [颜色库](docs/doc3.md#颜色库)
* [短链接](docs/doc3.md#短链接)
* [单位库](docs/doc3.md#单位库)
* [调用图](docs/doc3.md#调用图)
* [语言检测](docs/doc3.md#语言检测)
* [词法解析](docs/doc3.md#词法解析)
* [形式验证](docs/doc3.md#形式验证)
* [项目模板](docs/doc3.md#项目模板)
* [印章生成](docs/doc3.md#印章生成)
* [数据脱敏](docs/doc3.md#数据脱敏)
* [N+1问题](docs/doc3.md#N1问题)
* [敏感词过滤](docs/doc3.md#敏感词过滤)
* [正则表达式](docs/doc3.md#正则表达式)
* [代码生成器](docs/doc3.md#代码生成器)
* [类路径扫描](docs/doc3.md#类路径扫描)
* [目录服务](docs/doc3.md#目录服务)
* [表情处理](docs/doc3.md#表情处理)
* [行为分析](docs/doc3.md#行为分析)
* [ASCII艺术](docs/doc3.md#ASCII艺术)
* [Unicode](docs/doc3.md#Unicode)
* [URL操作](docs/doc3.md#URL操作)
* [WebRTC](docs/doc3.md#WebRTC)
* [Expect库](docs/doc3.md#Expect库)
* [JavaME](docs/doc3.md#JavaME)
* [JavaCard](docs/doc3.md#JavaCard)
* [Wikipedia](docs/doc3.md#Wikipedia)
* [WebService](docs/doc3.md#WebService)
* [银行账号操作](docs/doc3.md#银行账号操作)
* [用户代理解析](docs/doc3.md#用户代理解析)
* [语义发布工具](docs/doc3.md#语义发布工具)
* [数字信号处理](docs/doc3.md#数字信号处理)
* [企业集成模式](docs/doc3.md#企业集成模式)
* [数字资产管理](docs/doc3.md#数字资产管理)
* [文档管理系统](docs/doc3.md#文档管理系统)
* [数据匿名工具](docs/doc3.md#数据匿名工具)
* [外部进程执行](docs/doc3.md#外部进程执行)
* [苹果推送通知](docs/doc3.md#苹果推送通知)
* [自动程序修复](docs/doc3.md#自动程序修复)
* [Java服务包装器](docs/doc3.md#Java服务包装器)
* [守护进程](docs/doc3.md#守护进程)
* [协议实现](docs/doc3.md#协议实现)
* [BitTorrent](docs/doc3.md#BitTorrent)
* [编解码](docs/doc3.md#编解码)
* [打印机](docs/doc3.md#打印机)
* [Web资源](docs/doc3.md#Web资源)
* [Web开发库](docs/doc3.md#Web开发库)
* [Web过滤器](docs/doc3.md#Web过滤器)
* [Cron解析](docs/doc3.md#Cron解析)
* [手机号解析](docs/doc3.md#手机号解析)
* [表达式引擎](docs/doc3.md#表达式引擎)
* [数学表达式](docs/doc3.md#数学表达式)
* [SQL解析器](docs/doc3.md#SQL解析器)
* [解析器组合器](docs/doc3.md#解析器组合器)
* [源代码解析](docs/doc3.md#源代码解析)
* [对象图导航](docs/doc3.md#对象图导航)
* [超媒体类型](docs/doc3.md#超媒体类型)
* [术语服务器](docs/doc3.md#术语服务器)
* [Minecraft](docs/doc3.md#Minecraft)
* [Maven插件](docs/doc3.md#Maven插件)
* [Gradle插件](docs/doc3.md#Gradle插件)
* [Intellij插件](docs/doc3.md#Intellij插件)
* [Spring生态](docs/doc3.md#Spring生态)
* [Mybatis生态](docs/doc3.md#Mybatis生态)
* [JPA生态](docs/doc3.md#JPA生态)
* [其他](docs/doc3.md#其他)
* [教程系列](docs/doc3.md#教程系列)
  * [Java教程](docs/doc3.md#Java教程)
  * [大数据教程](docs/doc3.md#大数据教程)
  * [Spring Boot教程](docs/doc3.md#Spring生态教程)
  * [算法和数据结构教程](docs/doc3.md#算法和数据结构教程)
  * [软件工程教程](docs/doc3.md#软件工程教程)
  * [其他技术教程](docs/doc3.md#其他技术教程)
  * [秒杀系统](docs/doc3.md#秒杀系统)
  * [源码分析](docs/doc3.md#源码分析)
  * [面试宝典](docs/doc3.md#面试宝典)

## 开发框架

这里列出了Java中的开发框架，包括Web、REST框架、ORM框架、微服务等。

#### Web框架

* [Jakarta Servlet](https://github.com/jakartaee/servlet)：Jakarta Servlet定义了用于处理HTTP请求和响应的服务器端API。
* [Spring Boot](https://github.com/spring-projects/spring-boot)：Spring Boot可帮助轻松创建由Spring驱动的生产级应用程序和服务，由Pivotal开源。
* [Apache Struts](https://github.com/apache/struts)：Struts是一个用于创建Java Web应用程序的免费开源解决方案。
* [GWT](https://github.com/gwtproject/gwt)：GWT是一个开发工具包，用于构建和优化复杂的基于浏览器的应用程序，由Google开源。
* [Solon](https://gitee.com/noear/solon)：Java新的应用开发框架，更小、更快、更简单。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序，由Lightbend开源。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [Blade](https://github.com/lets-blade/blade)：Blade是一个追求简单、高效的Web框架。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web + ORM框架，其核心设计目标是开发迅速、代码量少、学习简单、功能强大、轻量级、易扩展、RESTful。
* [Grails](https://github.com/grails/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架，由Pivotal开源。
* [Javalin](https://github.com/javalin/javalin)：Javalin是一个非常轻量级的Kotlin和Java Web框架，支持WebSockets、HTTP2和异步请求。
* [Ninja](https://github.com/ninjaframework/ninja)：Ninja是Java的全栈Web框架，坚如磐石、快速且高效。
* [SOFABoot](https://github.com/sofastack/sofa-boot)：SOFABoot是一个基于Spring Boot的Java开发框架，由蚂蚁开源。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin允许你使用纯Java高效构建现代Web应用程序，而无需接触低级Web技术。
* [Jooby](https://github.com/jooby-project/jooby)：Jooby是一个现代、高性能且易于使用的Java和Kotlin Web框架上。
* [Elide](https://github.com/elide-dev/elide)：Elide是一个用于开发快速Web应用程序的云优先多语言运行时。
* [JSweet](https://github.com/cincheo/jsweet)：JSweet利用TypeScript通过JavaScript库和框架用Java编写丰富且响应迅速的Web应用程序。
* [Wonder](https://github.com/wocommunity/wonder)：Wonder是最大的可重用WebObjects框架、应用程序和扩展的开源集合，最初由NeXT开发并由Apple维护。
* [Apache Flex](https://github.com/apache/flex-sdk)：Apache Flex是一个基于AdobeFlash平台用于开发和部署RIA(Rich Internet Applications)的SDK，由Adobe维护。
* [Pippo](https://github.com/pippo-java/pippo)：Pippo是一个Java开源微型Web框架，具有最小的依赖性和快速的学习曲线。
* [Spark](https://github.com/perwendel/spark)：Spark是一个Java 8的小型Web框架。
* [Citrus](https://github.com/webx/citrus)：Citrus是阿里开源的基于Java的Web框架。
* [Apache Wicket](https://github.com/apache/wicket)：Wicket是一个开源、基于组件的Java Web应用程序框架。
* [RIFE2](https://github.com/rife2/rife2)：RIFE2是一个全栈、无声明的框架，可以使用现代Java快速、轻松地创建Web应用程序。
* [Apache Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架，专注于性能和开发人员生产力。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [ZK](https://github.com/zkoss/zk)：ZK是一个高效的Java框架，用于构建企业Web和移动应用程序。
* [Rose](https://github.com/XiaoMi/rose)：Rose是由人人网、糯米网、小米提供的，基于Servlet规范的Web框架。
* [Lift](https://github.com/lift/framework)：Lift是一个强大、安全的Web框架。
* [Kora](https://github.com/kora-projects/kora)：Kora是一个用于编写Java/Kotlin应用程序的框架，重点关注性能、效率和透明度。
* [JavaLite](https://github.com/javalite/javalite)：JavaLite是一个功能丰富的开发框架，包含Web、JDBC、Config等模块。
* [Vraptor4](https://github.com/caelum/vraptor4)：VRaptor是一个开源MVC框架，构建于CDI之上。
* [Apache Cocoon](https://github.com/apache/cocoon)：Cocoon是围绕Pipeline，关注点分离和基于组件的Web开发的概念构建的Web应用程序框架。
* [Apache Turbine](https://github.com/apache/turbine-core)：Turbine是一个基于Servlet的框架，允许Java开发人员快速构建Web应用程序。
* [Takes](https://github.com/yegor256/takes)：Takes是一个真正的面向对象且不可变的Java Web开发框架。
* [Argo](https://github.com/58code/Argo)：Argo是起源于58同城的内部Web框架。
* [Kora](https://github.com/Tinkoff/kora)：Kora是一个基于JVM的框架，用于构建后端应用程序。
* [IGRP](https://github.com/NOSiCode-CV/IGRP-Framework)：IGRP是由美国NOSi开发的平台，用于创建Web应用程序，基于业务步骤、流程、自动代码生成和一次性原则的合并。
* [Cicada](https://github.com/TogetherOS/cicada)：基于Netty的快速、轻量级Web框架。
* [HappyX](https://github.com/HapticX/happyx)：HappyX是一个异步、面向宏、全栈支持的Web框架。
* [CUBA Platform](https://github.com/cuba-platform/cuba)：CUBA Platform是一个高级框架，用于快速开发具有丰富Web界面的企业应用程序。
* [Tiny Framework](https://gitee.com/tinyframework/tiny)：企业级Java EE应用开发框架套件。
* [Minum](https://github.com/byronka/minum)：Minum是一个从头开始构建的最小Java Web框架，零依赖，使用虚拟线程。
* [Atmosphere](https://github.com/Atmosphere/atmosphere)：Atmosphere框架包含用于构建异步Web应用程序的客户端和服务器端组件。
* [ACT Framework](https://gitee.com/actframework/actframework)：ACT是一个简洁易用，具有强大表达力的Java MVC全栈框架。
* [Hasor](https://github.com/ClouGence/hasor)：Hasor是一套基于Java语言的开发框架，可以和现有技术体系做到完美融合，由开云集致开源。
* [SiteMesh](https://github.com/sitemesh/sitemesh3)：SiteMesh是一个网页布局和装饰框架以及Web应用程序集成框架，可帮助创建由需要一致外观/感觉、导航和布局方案的页面组成的网站，由OpenSymphony开源。
* [Eclipse Scout](https://github.com/eclipse-scout/scout.rt)：Scout是一个成熟且开源的框架，适用于Web上的现代业务应用程序。
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next)：Cloudopt Next是一个非常轻量级、基于JVM的全栈Kotlin框架，支持Java、Kotlin语言，由最好的Java库和标准精心打造。
* [Errai Framework](https://github.com/errai/errai)：Errai是一个Java/GWT Web框架，用于构建富客户端Web应用程序，由RedHat开源。
* [Stripes](https://github.com/StripesFramework/stripes)：Stripes是一个Java Web框架，其目标是使Java中基于Servlet/JSP的Web开发尽可能简单、直观。
* [BBoss](https://github.com/bbossgroups/bboss)：BBoss是一个Java EE框架，包括AOP/IoC、MVC、持久层、RPC等。
* [Latke](https://github.com/88250/latke)：Latke是一个简单易用的Java Web应用开发框架，包含MVC、IoC、事件通知、ORM、插件等组件。
* [NutzWk](https://github.com/Wizzercn/NutzWk)：NutzWk是基于国产框架NutzBoot开发的开源Java企业级Web框架。
* [Albianj2](https://github.com/crosg/Albianj2)：Albianj是阅文集团设计并开发的一套分布式统一框架。
* [Restlight](https://github.com/esastack/esa-restlight)：Restlight是一个轻量级且面向REST的Web框架。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [TeamApps](https://github.com/teamapps-org/teamapps)：TeamApps是一个Java Web应用程序框架。
* [DotWebStack](https://github.com/dotwebstack/dotwebstack-framework)：DotWebStack框架提供了一组标准化构建块，可以用最少的开发工作构建丰富的数据服务。
* [Prime MVC](https://github.com/prime-framework/prime-mvc)：Prime MVC是一个用Java构建的高性能模型视图控制器框架，由Inversoft公司开源。
* [Aspectran](https://github.com/aspectran/aspectran)：Aspectran是一个用于开发Java应用程序的框架，可用于构建简单的shell应用程序和大型企业Web应用程序。
* [Tentackle](https://bitbucket.org/krake-oss/tentackle)：Tentackle是一个开源Java框架，适用于在多个JVM上运行的分层应用程序，其灵感来自领域驱动设计的原理。
* [AppNG](https://github.com/appNG/appng)：AppNG是一个Web应用程序平台和Web应用程序框架，基于Tomcat和Spring框架。
* [Wisdom](https://github.com/wisdom-framework/wisdom)：模块化、动态的Web框架。
* [Nablarch](https://github.com/nablarch/nablarch)：Nablarch是一个基于中间件模式的Java应用程序框架。
* [Astrix](https://github.com/AvanzaBank/astrix)：Astrix是一个Java框架，旨在简化微服务的开发和维护，由Avanza银行开源。
* [Uberfire](https://github.com/kiegroup/appformer)：Uberfire是一个Web框架，可在构建可扩展工作台和控制台类型应用程序方面提供卓越的体验，由JBoss社区开源。
* [Spincast](https://github.com/spincast/spincast-framework)：Spincast是一个高度灵活的开源Java Web框架，基于Guice。
* [WComponents](https://github.com/bordertech/wcomponents)：WComponents是一个固执己见的Java框架，用于为企业和政府构建可访问的Web应用程序。
* [TERASOLUNA](https://github.com/terasolunaorg/terasoluna-gfw)：TERASOLUNA是一种通过结合NTT Data的技术和知识来全面支持系统开发的解决方案。
* [Core NG](https://github.com/neowu/core-ng-project)：Core NG是专为长期可维护性和代码质量控制而设计和优化的Web框架。
* [AppFuse](https://github.com/appfuse/appfuse)：AppFuse是一个用于在JVM上构建Web应用程序的全栈框架。
* [HServer](https://gitee.com/HServer/HServer)：HServer是一个基于Netty开发的一个功能强大、资源丰富、开发灵活、轻量级、低入侵、高并发的新型Web开发框架。
* [YMP](https://gitee.com/suninformation/ymate-platform-v2)：YMP是一个非常简单、易用的轻量级Java应用开发框架，涵盖AOP、IoC、Web、ORM、Validation、Plugin、Serv、Cache等特性。
* [Windward](https://github.com/Flmelody/windward)：Windward是一个Java轻量级Web框架。

#### RPC框架

* [Apache Dubbo](https://github.com/apache/dubbo)：Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [gRPC](https://github.com/grpc/grpc-java)：Google RPC的Java实现，基于HTTP/2的RPC。
* [Finagle](https://github.com/twitter/finagle)：Finagle是JVM的一个可扩展的RPC系统，用于构建高并发服务器，由Twitter开源。
* [Motan](https://github.com/weibocom/motan)：Motan是一个跨语言RPC框架，用于快速开发高性能分布式服务，由微博开源。
* [Smithy](https://github.com/smithy-lang/smithy)：Smithy包含一种与协议无关的接口定义语言(IDL)，用于生成客户端、服务器、文档和其他工件，由AWS开源。
* [SOFARPC](https://github.com/sofastack/sofa-rpc)：SOFARPC是一个高性能、高扩展性、生产级的Java RPC框架，由蚂蚁金服开源并广泛使用。
* [Pigeon](https://github.com/dianping/pigeon)：Pigeon是一个分布式RPC框架，在大众点评内部广泛使用。
* [Tars Java](https://github.com/TarsCloud/TarsJava)：Tars Java是腾讯Tars RPC框架的Java语言实现。
* [Apache Thrift](https://github.com/apache/thrift)：Thrift是一个轻量级、独立于语言的软件堆栈，用于点对点RPC实现，由Facebook开源。
* [OCTO-RPC](https://github.com/Meituan-Dianping/octo-rpc)：OCTO-RPC是支持Java和C++的企业级通信框架，在RPC服务之上扩展了丰富的服务治理功能，由美团开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint/tree/master/rpc)：Naver开源的RPC框架，服务于Pinpoint。
* [TChannel](https://github.com/uber/tchannel)：TChannel是一种用于一般RPC的网络框架协议，支持无序响应，性能极高，中间人可以快速做出转发决策，由Uber开源。
* [Protobuf RPC](https://github.com/baidu/Jprotobuf-rpc-socket)：Protobuf RPC是一种基于TCP协议的二进制RPC通信协议的Java实现，由百度开源。
* [Gaea](https://github.com/58code/Gaea)：Gaea是服务通讯框架，具有高并发、高性能、高可靠性，并提供异步、多协议、事件驱动的中间层服务框架，由58同城开源。
* [Joynr](https://github.com/bmwcarit/joynr)：Joynr是一个与传输协议无关(MQTT、HTTP、WebSockets等)、基于Franca IDL的通信框架，支持多种通信范例，由宝马开源。
* [DaRPC](https://github.com/zrlio/darpc)：DaRPC是一个Java库，为支持RDMA的网络接口提供超低延迟RPC，由IBM开源。
* [SCF](https://juejin.cn/post/7123035209565470728)：转转RPC框架SCF继承自58集团RPC框架。
* [DubboX](https://github.com/dangdangdotcom/dubbox)：DubboX在Dubbo框架中添加了RESTful远程处理、Kyro/FST序列化等功能，由当当开发。
* [DubboG](https://github.com/lenovoDTC/dubbo-G)：DubboG是联想基于Dubbo 2.5.3的二次开发版本。
* [NettyRPC](https://github.com/luxiaoxun/NettyRpc)：NettyRpc是一个基于Netty、ZooKeeper和Spring的简单RPC框架。
* [tRPC](https://github.com/trpc-group/trpc-java)：tRPC Java作为tRPC的Java语言实现，是一个久经考验的微服务框架，由腾讯开源。
* [JoyRPC](https://github.com/jd-opensource/joyrpc)：JoyRPC是一款基于Java实现的RPC服务框架，由京东开源。
* [Koalas RPC](https://gitee.com/dromara/koalas-rpc)：Koalas是dromara社区开源的高可用、可拓展的RPC框架。
* [Kotlinx RPC](https://github.com/Kotlin/kotlinx-rpc)：Kotlinx RPC是一个Kotlin库，用于向应用程序添加RPC服务，由JetBrains开源。
* [IceRPC](https://github.com/zeroc-ice/ice)：IceRPC是一个新的开源RPC框架，可帮助你使用很少的代码构建速度极快的网络应用程序。
* [ZBus](https://gitee.com/openforce/zbus)：ZBus致力于使消息队列和RPC变得快速、轻量级并且易于为许多不同的平台构建你自己的面向服务的架构，由开放金融技术开源。
* [XXL-RPC](https://github.com/xuxueli/xxl-rpc)：XXL-RPC是一个分布式服务框架，提供稳定高性能的RPC远程服务调用功能。
* [RSocket RPC](https://github.com/rsocket/rsocket-rpc-java)：RSocket RPC标准Java实现。
* [RPC Framework](https://github.com/Snailclimb/guide-rpc-framework)：RPC Framework是一款基于Netty、Kyro、Zookeeper实现的自定义RPC框架。
* [Sekiro](https://github.com/yint-tech/sekiro-open)：Sekiro是一个多语言、分布式、与网络拓扑无关的服务发布平台，由因体信息开源。
* [ONCRPC4J](https://github.com/dCache/oncrpc4j)：ONCRPC4J是ONCRPC/SUNRPC的纯Java实现，由费米实验室、德国电子加速器、北欧数据网格设施共同开源。
* [Hprose](https://github.com/hprose/hprose-java)：Hprose是一个高性能远程对象服务引擎。
* [Jupiter](https://github.com/fengjiachun/Jupiter)：Jupiter是一款性能非常不错的，轻量级的分布式服务框架。
* [NettyRPC](https://github.com/tang-jie/NettyRPC)：基于Netty的高性能Java RPC服务器，使用kryo、hessian、protostuff支持消息序列化。
* [Ob1k](https://github.com/outbrain/ob1k)：Ob1k是一个异步轻量级RPC框架，用于快速开发异步、高性能微服务，由Outbrain开源。

#### JSF框架

* [Jakarta Faces](https://github.com/jakartaee/faces)：Jakarta Faces定义了一个MVC框架，用于构建Web应用程序的用户界面。
* [PrimeFaces](https://github.com/primefaces/primefaces)：PrimeFaces是Java EE生态系统中最受欢迎的UI库之一。
* [JoinFaces](https://github.com/joinfaces/joinfaces)：JoinFaces是一个致力于简化Spring Boot与JSF集成的开源框架。
* [PrimeFaces Extensions](https://github.com/primefaces-extensions/primefaces-extensions)：PrimeFaces Extensions是一个社区驱动的开源项目，其目标是成为除PrimeFaces之外的轻量级且快速的Faces组件和实用程序库。
* [IceFaces](https://www.icesoft.org/wiki/display/ICE/ICEfaces+Overview)：IceFaces是一个基于JSF标准的开源富互联网应用程序开发框架，由ICEsoft公司开源。
* [Omnifaces](https://github.com/omnifaces/omnifaces)：OmniFaces是Faces的实用程序库，专注于使用标准Faces API简化日常任务的实用程序。
* [Adminfaces](https://github.com/adminfaces/admin-template)：Admin Template是一个基于Bootstrap和Admin LTE的完全响应式Java Server Faces管理模板。
* [Eclipse Mojarra](https://github.com/eclipse-ee4j/mojarra)：Mojarra是JSF标准的一个开源实现，由Oracle开发。
* [Apache MyFaces](https://github.com/apache/myfaces)：Apache基金会下的Jakarta Faces实现。
* [ButterFaces](https://github.com/butterfaces/butterfaces)：ButterFaces是一个轻量级响应式JSF框架，它结合了Bootstrap 4、jQuery 3和HTML 5的优点，可以使用JSF 2开发快速、简单且现代的Web应用程序。
* [RichFaces](https://github.com/richfaces/richfaces)：RichFaces项目是一个高级UI组件框架，可以使用JSF将Ajax功能轻松集成到业务应用程序中，由RedHat开源。
* [ChartistJSF](https://github.com/hatemalimam/ChartistJSF)：JavaServer Faces的高度可定制响应式图表。
* [BootsFaces](https://github.com/TheCoder4eu/BootsFaces-OSP)：BootsFaces是一个基于Bootstrap 3和jQuery UI的强大且轻量级的JSF框架。
* [AngularFaces](https://github.com/stephanrauh/AngularFaces)：AngularFaces是一个JSF组件库，旨在通过允许你用简单的AngularJS代码替换大量巧妙的AJAX代码来简化JSF开发。
* [Reasonable ServerFaces](https://rsf.github.io/wiki/Wikib2ab.html)：Reasonable ServerFaces是一个用Java编写的开源Web编程框架，由剑桥大学教育技术应用研究中心开发。

#### REST框架

* [Rest.li](https://github.com/linkedin/rest.li)：Rest.li是一个开源REST框架，用于使用类型安全绑定和异步、非阻塞IO构建健壮、可扩展的RESTful架构，由LinkedIn开源。
* [Eclipse Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个REST框架，提供JAX-RS参考实现等，由Oracle开源。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [RESTEasy](https://github.com/resteasy/resteasy)：RESTEasy是一个JBoss项目，旨在为使用Java开发客户端和服务器RESTful应用程序和服务提供生产力框架，由RedHat开源。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序，由ObjectStyle开源。
* [RESTX](https://github.com/restx/restx)：RESTX是一个完整的轻量级颠覆性堆栈，其中包括类似Swagger的UI并将REST规范测试视为文档。
* [Xenon](https://github.com/vmware-archive/xenon)：Xenon是一个用于编写小型REST服务的框架，由VMware开发。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Restlet框架帮助Java开发人员构建更好的遵循REST架构风格的Web API，由Talend开源。
* [Magic API](https://gitee.com/ssssssss-team/magic-api)：Magic API是一个基于Java的接口快速开发框架。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：Grumpyrest是一个Java REST服务器框架，不使用注解、自动依赖注入或响应流，并最大限度地减少反射的使用。
* [Resty](https://github.com/Dreampie/Resty)：Resty一款极简的RESTful轻量级的Web框架。
* [Airlift](https://github.com/airlift/airlift)：Airlift是一个用Java构建REST服务的框架，由Dropbox开源。
* [Apache Juneau](https://github.com/apache/juneau)：Juneau是一个强大的框架，用于简化构建和解析RESTful API的过程，由IBM开发。
* [Kanary](https://github.com/SeunAdelekan/Kanary)：用于在Kotlin/Java中构建REST API的简约Web框架。
* [Moqui Framework](https://github.com/moqui/moqui-framework)：Moqui是一个全功能、企业级应用开发框架，基于Groovy和Java语言。
* [Kilo](https://github.com/HTTP-RPC/Kilo)：Kilo是一个开源框架，用于在Java中创建和使用RESTful和类REST Web服务。
* [Crnk](https://github.com/crnk-project/crnk-framework)：Crnk是JSON API规范和建议的Java实现，旨在促进构建RESTful应用程序。
* [Hammock](https://github.com/hammock-project/hammock)：Hammock是一个简单易用的框架，用于引导CDI、启动Web服务器并能够部署REST API。
* [Apache Sling](https://sling.apache.org/)：Sling是一个基于可扩展内容树的RESTful Web应用程序框架。
* [Apache Wink](https://wink.apache.org/)：Wink是一个简单而可靠的框架，用于构建RESTful Web服务。
* [Rocket API](https://gitee.com/alenfive/rocket-api)：API敏捷开发框架，用于API接口功能的快速开发。
* [Proteus](https://github.com/noboomu/proteus)：Proteus是一个极快的极简Java API服务器框架，构建于Undertow之上，用于开发后端应用程序和微服务。
* [Confluent REST Utils](https://github.com/confluentinc/rest-utils)：Confluence REST Utils提供了一个小型框架和实用程序，用于使用Jersey、Jackson、Jetty和Hibernate Validator编写Java REST API。
* [EverRest](https://github.com/codenvy/everrest)：EverRest是RESTful应用程序框架以及完整的JAX-RS实现。
* [Agrest](https://github.com/agrestio/agrest)：Agrest是一个灵活的模型驱动的REST数据服务框架。
* [Lambada Framework](https://github.com/cagataygurturk/lambadaframework)：Lambada Framework是一个实现JAX-RS API的REST框架，可让你以Serverless方式将应用程序部署到AWS Lambda和API Gateway。
* [AceQL HTTP](https://github.com/kawansoft/aceql-http)：AceQL HTTP是一个类似REST的API库，允许你从任何支持HTTP的设备通过HTTP访问远程SQL数据库。
* [Conjure Java Runtime](https://github.com/palantir/conjure-java-runtime)：该项目提供了一组固定的库，用于定义和创建RESTish/RPC服务器和客户端，基于Feign作为客户端，以Dropwizard/Jersey和JAX-RS服务定义作为服务器，由Palantir开源。

#### ORM框架

* [Hibernate](https://github.com/hibernate/hibernate-orm)：Hibernate是一个强大的Java ORM解决方案，可以轻松地为应用程序、库和框架开发持久层逻辑，由RedHat开源。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring Data JPA是Spring Data系列的一部分，可以轻松实现基于JPA的Repository。
* [Mybatis](https://github.com/mybatis/mybatis-3)：MyBatis是一流的持久层框架，支持自定义SQL、存储过程和高级映射。
* [MybatisPlus](https://github.com/baomidou/mybatis-plus)：MyBatisPlus是MyBatis的一个强大的增强工具包，用于简化开发。
* [APIJSON](https://github.com/Tencent/APIJSON)：APIJSON是一种专为API而生的JSON网络传输协议以及基于这套协议实现的ORM库，由腾讯开源。
* [Exposed](https://github.com/JetBrains/Exposed)：Exposed是一个Kotlin SQL库，有两种风格：轻量级ORM(使用DAO)和类型安全SQL(使用DSL)，由JetBrains开发。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：EclipseLink为开发人员提供基于标准的对象关系持久性解决方案，并额外支持许多高级功能，Oracle开源。
* [GreenDAO](https://github.com/greenrobot/greenDAO)：GreenDAO是一个轻量且快速的Android ORM，可将对象映射到SQLite数据库。
* [Apache OpenJPA](https://github.com/apache/openjpa)：OpenJPA是Jakarta Persistence API 3.0规范的实现。
* [QueryDSL](https://github.com/querydsl/querydsl)：QueryDSL是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。
* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，以帮助你编写更好的SQL。
* [WCDB](https://github.com/Tencent/wcdb)：WCDB是腾讯微信应用中使用的高效、完整、易用的移动数据库框架。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean是一个纯Java实现的开源ORM框架，它被设计成比JPA更简单、容易理解和使用。
* [Komapper](https://github.com/komapper/komapper)：Komapper是服务器端Kotlin的ORM库。
* [Sugar ORM](https://github.com/chennaione/sugar)：Sugar ORM是一个Android ORM库，它提供了一种简单的方法来存储和检索数据。
* [ObjectiveSQL](https://github.com/braisdom/ObjectiveSql)：ObjectiveSQL是一个基于ActiveRecord模式的ORM框架，它鼓励快速开发和整洁，最少的代码，以及约定优于配置。
* [ORMLite](https://github.com/j256/ormlite-core)：ORMLite提供了一些简单、轻量级的功能，用于将Java对象持久保存到SQL数据库，同时避免更标准ORM包的复杂性和开销。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级ORM框架，由高盛银行开源。
* [Apache Gora](https://github.com/apache/gora)：Gora框架提供内存数据模型和大数据持久化。
* [Apache Cayenne](https://github.com/apache/cayenne)：Cayenne是一个开源持久层框架，提供ORM和远程处理服务，由ObjectStyle开源。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：Jimmer是一个针对Java和Kotlin的革命性ORM，以及一套基于它的完整的集成方案。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web、ORM框架。
* [LiteORM](https://github.com/litesuits/android-lite-orm)：LiteORM是一个小巧、强大、性能更好的Android ORM类库。
* [AnyLine](https://gitee.com/anyline/anyline)：AnyLine的核心是一个面向运行时的元数据动态ORM。
* [NgBatis](https://github.com/nebula-contrib/ngbatis)：NgBatis是一个可以使用类似MyBatis、MyBatisPlus的方式，操作NebulaGraph的Java ORM框架。
* [HsWeb-ORM](https://github.com/hs-web/hsweb-easy-orm)：简单的ORM工具，为动态表单而生。
* [Easy Query](https://github.com/xuejmnet/easy-query)：Easy Query是一款轻量级的ORM框架，无需任何第三方依赖。
* [Bee](https://github.com/automvc/bee)：Bee是一个人工智能、简单、高效的ORM框架，支持JDBC、Cassandra、MongoDB、Sharding。
* [Eloquent](https://github.com/gaarason/database-all)：Eloquent ORM提供一个美观、简单的与数据库打交道的ActiveRecord实现。
* [ActiveAndroid](https://github.com/pardom-zz/ActiveAndroid)：ActiveAndroid是一个Active Record风格的ORM。
* [Bean Searcher](https://github.com/troyzhxu/bean-searcher)：专注于高级查询的只读ORM，天然支持连接表，并且避免DTO/VO转换，使得一行代码实现复杂查询成为可能。
* [MicroStream](https://github.com/microstream-one/microstream)：MicroStream是一个突破性的Java原生对象图持久层，专为需要轻量级高性能持久层的微服务和Serverless函数而构建。
* [Speedment](https://github.com/speedment/speedment)：Speedment是一个开源Java Stream ORM工具包和运行时。
* [BeetlSQL](https://gitee.com/xiandafu/beetlsql)：BeetlSQL的目标是提供开发高效、维护高效、运行高效的数据库访问框架。
* [AFinal](https://github.com/yangfuhai/afinal)：AFinal是一个Android的SQLite ORM和IoC框架。
* [Sqli](https://github.com/x-ream/sqli)：ORM SQL查询构建器。
* [Persism](https://github.com/sproket/Persism)：Persism是一个轻量级、自动发现、自动配置和约定优于配置的ORM库。
* [SQLToy](https://github.com/sagframe/sagacity-sqltoy)：SQLToy是基于Java语言开发的，兼有Hibernate面向对象操作和MyBatis灵活查询的优点，同时更贴切项目、更贴切开发者的一个关系型数据库ORM框架。
* [Android Orma](https://github.com/maskarade/Android-Orma)：Orma是一个适用于Android SQLite数据库的ORM框架。
* [Norm](https://github.com/dieselpoint/norm)：Norm是一种访问JDBC数据库的简单方法，通常只需一行代码。

#### 持久层库

* [Eclipse JNoSQL](https://github.com/eclipse/jnosql)：JNoSQL是Jakarta NoSQL和Jakarta Data规范的兼容实现，可简化Java应用程序与NoSQL数据库的集成。
* [Jdbi](https://github.com/jdbi/jdbi)：Jdbi库提供了对Java和其他JVM语言中的关系数据库的便捷、惯用的访问。
* [SquiDB](https://github.com/yahoo/squidb)：SquiDB是适用于Android和iOS的跨平台SQLite数据库层，旨在尽可能轻松地使用SQLite数据库，由Yahoo开源。
* [Hypersistence Utils](https://github.com/vladmihalcea/hypersistence-utils)：Hypersistence Utils库提供Spring和Hibernate实用程序，可以帮助充分利用数据访问层。
* [Sql2o](https://github.com/aaberg/sql2o)：Sql2o是一个小型Java库，可以轻松地将SQL语句的结果转换为对象。
* [LitePal](https://github.com/guolindev/LitePal)：LitePal是一个开源Android库，可以让开发人员极其轻松地使用SQLite数据库。
* [Lightblue](https://github.com/lightblue-platform/lightblue-core)：Lightblue是基于文档的数据访问层框架，由RedHat开源。
* [Apache MetaModel](https://metamodel.apache.org/)：Metamodel是一个用于处理结构化数据的Java库，它提供了强大的元数据驱动的数据访问API，支持多种数据源，如关系数据库、CSV文件等。
* [Doma](https://github.com/domaframework/doma)：Doma是适用于Java 8+的面向DAO的数据库映射框架。
* [JINQ](https://github.com/my2iu/Jinq)：JINQ为开发人员提供了一种用Java编写数据库查询的简单而自然的方法。
* [Database](https://github.com/susom/database)：Database提供一种简化的数据库访问方式，它是JDBC驱动程序的包装器，由斯坦福开源。
* [Permazen](https://github.com/permazen/permazen)：Permazen是用于SQL、键值或内存数据库的持久层框架。
* [Carbonado](https://github.com/Carbonado/Carbonado)：Carbonado是Java应用程序的可扩展、高性能持久性抽象层，提供底层持久性技术的关系视图，由Amazon开源。
* [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)：SimpleFlatMapper提供了一个非常快速且易于使用的映射器。
* [DataNucleus](https://github.com/datanucleus/datanucleus-core)：DataNucleus是一个兼容各种标准(JDO1、JDO2、JDO2.1、JDO2.2、JDO2.3、和JPA1)的Java数据持久化框架。
* [Apache EmpireDB](https://github.com/apache/empire-db)：EmpireDB是一个轻量级的关系型数据库访问库，用于处理所有关系型数据的存储、操作、检索和建模方面。
* [DAS](https://github.com/ppdaicorp/das)：DAS是信也科技自研的数据库访问框架。
* [Dekaf](https://github.com/JetBrains/dekaf)：Dekaf是一个主要通过JDBC处理数据库的Java框架，由JetBrains开源。
* [Requery](https://github.com/requery/requery)：Requery是一个轻量级但功能强大的对象映射和SQL生成器，适用于Java/Kotlin/Android，支持RxJava和Java 8。
* [Apache Commons DbUtils](https://github.com/apache/commons-dbutils)：Commons DbUtils包是一组用于简化JDBC开发的Java工具类。
* [Jcabi JDBC](https://github.com/jcabi/jcabi-jdbc)：Jcabi JDBC是JDBC的一个方便、流式的包装器。
* [TorpedoQuery](https://github.com/xjodoin/torpedoquery)：类型安全的Hibernate查询生成器。
* [UroboroSQL](https://github.com/future-architect/uroborosql)：UroboroSQL是一个简单的SQL执行库，可以利用与Java 8兼容的2-way-SQL，由日本Future公司开源。
* [Japedo](https://www.logitags.com/japedo/)：Japedo是一个用于生成Java应用程序完整持久层文档的工具。
* [Apache JDO](https://github.com/apache/db-jdo)：JDO是访问数据库中持久数据的标准方法，使用POJO来表示持久数据。
* [Objectify](https://github.com/objectify/objectify)：Objectify是专门为Google Cloud Datastore设计的Java数据访问API。
* [JDBCX](https://github.com/jdbcx/jdbcx)：JDBCX通过支持SQL之外的其他数据格式、压缩算法、对象映射、类型转换和查询语言来增强JDBC驱动程序。
* [MiniDao](https://github.com/jeecgboot/MiniDao)：MiniDao是一款轻量级Java持久层框架，基于Spring JDBC\Freemarker实现，具备Mybatis一样的SQL分离和逻辑标签能力。
* [PulseDB](https://github.com/feedzai/pdb)：PulseDB是一个用Java编写的数据库映射软件库，它提供对各种数据库实现的透明访问和操作，由Feedzai开源。
* [MilvusPlus](https://gitee.com/dromara/MilvusPlus)：MilvusPlus是一个功能强大的Java库，旨在简化与Milvus向量数据库的交互，为开发者提供类似MyBatisPlus注解和方法调用风格的直观API，由dromara社区开源。
* [FluentJdbc](https://github.com/zsoltherpai/fluent-jdbc)：FluentJdbc是一个用于方便原生SQL查询的Java库。
* [Yank](https://github.com/knowm/Yank)：Yank是适用于Java应用程序的超轻量JDBC持久层。
* [Kundera](https://github.com/Impetus/kundera)：Kundera是一个带有JPA接口的多语言对象映射器。
* [Hibernate Hydrate](https://github.com/arey/hibernate-hydrate)：Hibernate Hydrate项目的主要目标是填充持久实体图，从而避免著名的LazyInitializationException。
* [Elsql](https://github.com/OpenGamma/ElSql)：ElSql允许SQL从Java应用程序外部化。
* [SqlRender](https://github.com/OHDSI/SqlRender)：这是一个R包和Java库，用于呈现参数化SQL，并将其转换为不同的SQL方言，由OHDSI开源。
* [DoytoQuery](https://github.com/doytowin/doyto-query)：DoytoQuery是一个功能强大且易于使用的对象SQL映射框架。

#### 应用框架

* [Jmix](https://github.com/jmix-framework/jmix)：Jmix是一组库和工具，用于加速Spring Boot以数据为中心的应用程序开发，由Haulmont开源。
* [Apache Usergrid](https://github.com/apache/usergrid)：Usergrid是一个基于RESTful API的用于Web和移动应用程序的多租户后端即服务堆栈。
* [Para](https://github.com/Erudika/para)：Para是一个可扩展的多租户后端服务器/框架，用于对象持久化和检索。
* [JVx](https://doc.sibvisions.com/jvx/home)：JVx是一个全栈应用程序框架，用于为不同的技术(Swing、Vaadin、React等)创建具有单一来源的多层应用程序，由SIB Visions公司开发。
* [Demoiselle 3](https://github.com/demoiselle/framework)：Demoiselle框架实现了集成框架的概念，其目标是通过最大限度地减少选择和集成专业框架的时间来促进应用程序的构建，从而提高生产力并保证系统的可维护性。
* [TwelveT](https://github.com/twelvet-projects/twelvet)：基于Spring Boot 3.X的Spring Cloud Alibaba/Spring Cloud Tencent + React的微服务框架。
* [Chronicle-Decentred](https://github.com/OpenHFT/Chronicle-Decentred)：Chronicle Decentred是一个用于在分布式账本技术上构建点对点安全可扩展微服务的框架。
* [BootDo](https://gitee.com/lcg0124/bootdo)：BootDo是高效率、低封装、面向学习型、微服务的开源Java EE开发框架。
* [JADA JEE Framework](https://github.com/consiglionazionaledellericerche/jada)：基于EJB3的应用程序的软件框架，它允许开发人员配置与数据呈现和持久层相关的方面，意大利国家研究委员会开源。
* [Apiary](https://github.com/DBOS-project/apiary)：Apiary是一个事务性功能即服务(FaaS)框架，用于构建面向数据库的应用程序，例如微服务和Web服务后端，这是MIT、斯坦福合作的一个研究项目。
* [Synapse](https://github.com/americanexpress/synapse)：Synapse是一组用于快速开发的轻量级基础框架模块，内置企业级成熟度和质量，由美国运通开源。
* [Salespoint Framework](https://github.com/st-tu-dresden/salespoint)：Salespoint是一个用于开发销售点应用程序的框架，由德累斯顿工业大学、慕尼黑联邦国防军大学共同开发。
* [Dynamo](https://github.com/opencirclesolutions/dynamo)：Dynamo是一个软件开发框架，最初由Open Circle Solutions开发，旨在通过使用约定优于配置、模型驱动开发和DRY等设计原则来提高生产力。
* [Continuum Framework](https://github.com/Kinotic-Foundation/continuum-framework)：Continuum Framework是由Kinotic Foundation开发的开源软件框架，旨在为开发人员提供一组强大的工具来快速高效地创建高性能软件解决方案。
* [KWai Business Extension Framework](https://github.com/kwai/kwai-business-extension-framwork)：KWai Business Extension Framework提供一套通用业务扩展框架，通过引入业务身份识别和可扩展的隔离架构，帮助业务搭建定制业务流程的架构标准、研发工具和运维体系，由快手开发。
* [KivaKit](https://github.com/Telenav/kivakit)：KivaKit是一套用于日常开发的集成Java迷你框架。
* [Las2peer](https://github.com/rwth-acis/las2peer)：Las2peer是一个基于Java的服务器框架，用于在分布式点对点(P2P)环境中开发和部署微服务，由亚琛工业大学开发。
* [Chill PL](https://github.com/bigskysoftware/chill)：Chill Platform是一个Java Web和云应用程序开发平台。

#### 微服务框架

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring Cloud为开发人员提供了快速构建分布式系统中一些常见模式的工具，由Pivotal开源。
* [Apache Dubbo](https://github.com/apache/dubbo)：Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [Jakarta EE](https://jakarta.ee/)：Jakarta EE为开发人员提供了一套全面的供应商中立的开放规范，用于从头开始开发现代云原生Java应用程序。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：Micronaut是一个基于JVM的现代全栈Java框架，旨在构建模块化、易于测试的JVM应用程序，由Object Computing开源。
* [Quarkus](https://github.com/quarkusio/quarkus)：Quarkus是一个用于编写Java应用程序的云原生容器优先框架，由RedHat开发。
* [Helidon](https://github.com/helidon-io/helidon)：Helidon是一组用于编写微服务的Java库，基于Java虚拟线程，由Oracle开发。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包，主要由RedHat开源。
* [Finatra](https://github.com/twitter/finatra)：Finatra是一个轻量级框架，用于在TwitterServer和Finagle之上构建快速、可测试的Scala应用程序，由Twitter开源。
* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个用于创建微服务、Web应用程序等的异步框架，由Jetbrains开源。
* [DevOps Boot](https://github.com/bkdevops-projects/devops-framework)：DevOps Boot是基于Spring Boot的微服务快速开发框架，由腾讯DevOps团队开发。
* [ServiceTalk](https://github.com/apple/servicetalk)：ServiceTalk是一个JVM网络应用程序框架，具有针对特定协议(例如HTTP/1.x、HTTP/2.x等)定制的API，并支持多种编程范例，由Apple开源。
* [RestExpress](https://github.com/RestExpress/RestExpress)：RestExpress是用于快速创建可扩展、无容器、RESTful微服务的极简Java框架，由Facebook开源。
* [Apache ServiceComb](https://github.com/apache/servicecomb-java-chassis)：ServiceComb是一个用于用Java快速开发微服务的软件开发工具包，提供服务注册、服务发现、动态路由和服务管理功能，由华为开源。
* [Eclipse MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展，由IBM、RedHat、Oracle、Fujitsu、Microsoft等组织参与。
* [Axon](https://github.com/AxonFramework/AxonFramework)：Axon是一个基于DDD、CQRS和事件溯源原则构建渐进式事件驱动微服务系统的框架。
* [Riposte](https://github.com/Nike-Inc/riposte)：Riposte是一个基于Netty的微服务框架，用于快速开发生产就绪的HTTP API，由Nike开源。
* [Lagom](https://github.com/lagom/lagom)：Lagom是一个开源框架，用于用Java或Scala构建响应式微服务系统，由Lightbend开源。
* [Apollo](https://github.com/spotify/apollo)：Apollo是Spotify编写微服务时使用的一组Java库，包含HTTP服务器和URI路由系统等模块，使得实现RESTful API服务变得轻而易举。
* [Armeria](https://github.com/line/armeria)：Armeria是适合任何情况的首选微服务框架，你可以利用自己喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Streams、Spring Boot和Dropwizard，由Line开源。
* [Light-4J](https://github.com/networknt/light-4j)：Light-4J是快速、轻量级且更高效的微服务框架。
* [MSF4J](https://github.com/wso2/msf4j)：MSF4J是一个用于开发和运行微服务的轻量级高性能框架，由WSO2开源。
* [NutzBoot](https://gitee.com/nutz/nutzboot)：NutzBoot是可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、流控熔断、分布式事务等解决方案。
* [Starlight](https://github.com/baidu/starlight)：Starlight是一套面向云原生的微服务通信框架，兼容Spring生态，由百度开源。
* [KumuluzEE](https://github.com/kumuluz/kumuluzee)：KumuluzEE是一个轻量级框架，用于使用标准Java、Java EE/Jakarta EE技术开发微服务并将现有Java应用程序迁移到微服务。
* [Ja-Micro](https://github.com/Sixt/ja-micro)：Ja-Micro是一个用于构建微服务的轻量级Java框架。
* [Colossus](https://github.com/tumblr/colossus)：Colossus是一个用来构建Scala微服务的轻量级I/O框架，由Tumblr开源。
* [JBoot](https://gitee.com/JbootProjects/jboot)：JBoot是一个基于JFinal、Dubbo、Seata、Sentinel、ShardingSphere、Nacos等开发的国产框架。
* [ActiveJ](https://github.com/activej/activej)：ActiveJ是适用于现代Web、云、高负载和微服务的Java 框架。
* [Flower](https://github.com/zhihuili/flower)：Flower是一个构建在Akka上的响应式微服务框架。
* [Dapeng SOA](https://github.com/dapeng-soa/dapeng-soa)：Dapeng SOA是一个轻量级、高性能的微服务框架，构建在Netty以及定制的精简版Thrift之上，大鹏开源。
* [Redkale](https://gitee.com/redkale/redkale)：Redkale是基于Java 11全新的微服务框架，包含HTTP、WebSocket、TCP/UDP、数据序列化、数据缓存、依赖注入等功能。
* [Open Capacity Platform](https://gitee.com/dromara/open-capacity-platform)：OCP是基于Spring Cloud的企业级微服务框架，其目标是帮助企业搭建一套类似百度能力开放平台的微服务框架，由dromara社区开源。
* [Zebra](https://gitee.com/gszebra/zebra)：Zebra是国信证券的微服务框架。
* [SeedStack](https://github.com/seedstack/seed)：SeedStack是一个固执己见、易于使用的Java开发堆栈。
* [Moleculer Java](https://github.com/moleculer-java/moleculer-java)：Moleculer Java是JVM的Moleculer微服务框架的实现。
* [Worker Framework](https://github.com/WorkerFramework/worker-framework)：Worker Framework为跨平台、云就绪、分布式数据处理微服务提供了基础。

#### Spring Cloud

* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix)：Spring Cloud Netflix项目为Spring Boot应用程序提供Netflix OSS集成。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：Spring Cloud Alibaba为分布式应用开发提供一站式解决方案。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：Spring Cloud GCP项目使Spring框架成为Google Cloud Platform的一等公民。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是实现标准Spring Cloud SPI的一站式微服务解决方案，它将Spring Cloud与腾讯中间件集成，让微服务开发变得简单。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是Microsoft开发的Spring Cloud框架，提供Spring与Azure服务的无缝集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：Spring Cloud AWS简化了在Spring和Spring Boot应用程序中使用AWS托管服务。
* [Spring Cloud Huawei](https://github.com/huaweicloud/spring-cloud-huawei)：Spring Cloud Huawei是一个让使用Spring Cloud开发微服务变得更加简单和高效的框架。
* [Spring Cloud Formula](https://gitee.com/baidu/spring-cloud-formula)：Spring Cloud Formula是百度云CNAP的面向客户提供的Java微服务框架设施。
* [Spring Cloud OCI](https://github.com/oracle/spring-cloud-oci)：Spring Cloud OCI在内部OCI Java SDK的帮助下简化了与Oracle OCI服务的集成。

## 微服务工具

* [Dapr Java](https://github.com/dapr/java-sdk)：Dapr是Microsoft开源的一个可移植、事件驱动的运行时，用于跨云和边缘构建分布式应用程序。
* [Nepxion Discovery](https://github.com/Nepxion/Discovery)：Nepxion Discovery是专注于企业级云原生微服务开源解决方案
* [Microserver](https://github.com/aol/micro-server)：Microserver是一个Java 8原生、零配置、基于标准、久经考验的库，可通过标准Java主类运行REST微服务，由AOL开源。
* [Eventuate Tram Core](https://github.com/eventuate-tram/eventuate-tram-core)：Eventuate Tram是一个解决微服务架构中固有的分布式数据管理问题的平台。
* [Femas](https://github.com/TencentFemas/femas)：Femas是腾讯云开源的云原生微服务一站式管理平台。
* [Moss](https://github.com/GrailStack/Moss)：Moss是Spring Cloud体系的服务治理平台。
* [Misk](https://github.com/cashapp/misk)：Misk是来自Cash App的开源微服务容器，它允许你使用Kotlin或Java快速创建微服务。
* [Stitch](https://github.com/twitter/stitch)：Stitch是一个Scala库，用于优雅高效地组合对服务的RPC调用，由Twitter开发。
* [Blade-Tool](https://github.com/chillzhuang/blade-tool)：Spring Blade 3.0架构核心工具包。
* [Conjure](https://github.com/palantir/conjure)：Conjure是一个简单的工具链，用于定义一次API并生成多种语言的客户端/服务器接口，由Palantir开源。
* [GreenLightning](https://github.com/oci-pronghorn/GreenLightning)：高性能微服务运行时。
* [Hexagon](https://github.com/hexagonkt/hexagon)：Hexagon是一个用Kotlin编写的微服务工具包，其目的是简化在云平台内运行的服务器应用程序的构建。
* [Mica](https://gitee.com/596392912/mica)：Spring Cloud微服务开发核心工具集，支持Web和WebFlux。
* [Baker](https://github.com/ing-bank/baker)：Baker是一个库，它提供了一种简单直观的方法来编排基于微服务的流程，由ING银行开源。
* [Uship](https://github.com/yupiik/uship)：Uship是一个适用于现代应用程序的轻量级微服务堆栈。
* [AdeptJ Runtime](https://github.com/AdeptJ/adeptj-runtime)：适用于RESTful API、微服务和Web应用的高性能、动态、模块化运行时。
* [Prana](https://github.com/Netflix/Prana)：用于基于Netflix OSS的服务的Sidecar，由Netflix开源。
* [Sermant](https://github.com/huaweicloud/Sermant)：Sermant是基于Java字节码增强技术的无代理服务网格，其利用Java字节码增强技术为宿主应用程序提供服务治理功能，以解决大规模微服务体系结构中的服务治理问题，由华为开源。
* [Water](https://gitee.com/noear/water)：为Java服务开发和治理，提供一站式解决方案(可以理解为微服务架构支持套件)。
* [Juggle](https://github.com/somta/Juggle)：Juggle是一个可用于接口编排、定制开发等场景的一套完整解决方案。
* [Edison-MicroService](https://github.com/otto-de/edison-microservice)：Spring Boot之上的独立库集合，可提供更快的JVM微服务设置。
* [Squbs](https://github.com/paypal/squbs)：Squbs是一套组件，可在大规模托管云环境中实现Akka和Akka HTTP应用程序/服务的标准化和可操作化，Paypal开源。
* [iBizLab-Runtime](https://gitee.com/ibizlab/ibizlab-runtime)：提供一个完整的微服务架构轻量级支撑运行时系统。
* [Infinitic](https://github.com/infiniticio/infinitic)：Infinitic是一个基于Pulsar的框架，可大大简化异步分布式应用程序的构建。
* [LittleHorse](https://github.com/littlehorse-enterprises/littlehorse)：LittleHorse是一个高性能的微服务编排引擎，允许开发人员构建可扩展、可维护和可观察的应用程序。
* [Oracle Bedrock](https://github.com/coherence-community/oracle-bedrock)：Oracle Bedrock提供了一个通用Java框架，用于开发、编排和测试高度并发的分布式应用程序。
* [SIP Framework](https://github.com/IKOR-GmbH/sip-framework)：该框架能够使用微服务构建轻量级集成适配器，以实现系统的技术和非技术解耦，因此具有高度可扩展性。
* [Mats3](https://github.com/centiservice/mats3)：Mats3是一个Java库，可促进异步、无状态、多阶段、基于消息的服务的开发。
* [Poseidon](https://github.com/flipkart-incubator/Poseidon)：Poseidon是一个用于构建API应用程序的平台，该应用程序必须以高效的方式聚合来自分布式服务的数据，由Flipkart开源。

## REST错误处理

* [Problem](https://github.com/zalando/problem)：Problem是一个实现application/problem+json的Java库，由Zalando开源。
* [Problem Spring Web](https://github.com/zalando/problem-spring-web)：用于从Spring应用程序生成application/problem+json响应，由Zalando开源。
* [EitherNet](https://github.com/slackhq/EitherNet)：EitherNet是一种多平台、可插入且密封的API结果类型，用于对Web API响应进行建模，由Slack开源。
* [Backstopper](https://github.com/Nike-Inc/backstopper)：Backstopper是一个与框架无关的API错误处理和模型验证解决方案，适用于Java 7及更高版本，由Nike开源。
* [Graceful Response](https://github.com/feiniaojin/graceful-response)：Graceful Response是一个Spring Boot技术栈下的优雅响应处理器，提供一站式统一返回值封装、全局异常处理、自定义异常错误码等功能。
* [JDoctor](https://github.com/melix/jdoctor)：JDoctor是一个用于设计良好错误消息的Java库。
* [ErrorHandler](https://github.com/Workable/java-error-handler)：适用于Android和Java的错误处理库。
* [Error Handling Spring Boot](https://github.com/wimdeblauwe/error-handling-spring-boot-starter)：该项目的目标是让使用Spring Boot构建的REST API能够轻松获得正确的错误响应。
* [Errors Spring Boot](https://github.com/alimate/errors-spring-boot-starter)：Errors Spring Boot Starter是Spring Boot的优雅错误处理库。
* [Spring Boot Problem Handler](https://github.com/officiallysingh/spring-boot-problem-handler)：用于处理Spring Boot应用程序中异常的通用库，实现HTTP API的Problem Details(RFC7807)规范。
* [Feign Reflection ErrorDecoder](https://github.com/coveooss/feign-error-decoder)：该库实现了ErrorDecoder，提供了一种简单的方法将API上返回的键映射到客户端接口上声明抛出的特定异常。
* [Result](https://github.com/leakyabstractions/result)：Result的目的是为可能成功或失败的操作结果提供类型安全的封装，而不是抛出异常。
* [Spring REST Exception handler](https://github.com/jirutka/spring-rest-exception-handler)：该项目的目标是为RESTful API提供一个方便的异常处理程序，以满足错误响应的最佳实践，而无需重复。

## 测试

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试、断言库、Mock框架等。

#### 单元测试

* [JUnit 4](https://github.com/junit-team/junit4)：JUnit是一个用于编写可重复测试的简单框架。
* [JUnit 5](https://github.com/junit-team/junit5)：JUnit 5是Java单元测试框架的最新版本，相较于JUnit 4，它引入了许多新的特性和改进。
* [TestNG](https://github.com/testng-team/testng)：TestNG是一个受JUnit启发的测试框架，但引入了一些新功能，使其更强大且更易于使用。
* [Spock](https://github.com/spockframework/spock)：Spock是一个用于Java和Groovy应用程序的BDD风格的开发人员测试和规范框架。
* [Kotest](https://github.com/kotest/kotest)：Kotest是一个灵活且全面的Kotlin测试工具，具有多平台支持。
* [Robolectric](https://github.com/robolectric/robolectric)：Robolectric是Android的行业标准单元测试框架。
* [uTest](https://github.com/com-lihaoyi/utest)：uTest是一个简单、直观的Scala测试库。

#### 集成测试

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：Testcontainers是一个支持JUnit测试的Java库，提供通用数据库、Selenium Web浏览器或任何其他可以在Docker容器中运行的东西的轻量级一次性实例。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：MicroShed Test提供了一种快速、简单的方法来为Java微服务应用程序编写和运行真正的生产集成测试。
* [Embedded Kafka](https://github.com/embeddedkafka/embedded-kafka)：提供内存中的Kafka实例来运行测试的库。
* [Embedded Redis](https://github.com/kstyrc/embedded-redis)：用于Java集成测试的Redis嵌入式服务器。
* [Embedded PostgreSQL](https://github.com/opentable/otj-pg-embedded)：允许使用Docker容器将PostgreSQL嵌入到Java应用程序代码中。
* [Embedded LDAP JUnit](https://github.com/zapodot/embedded-ldap-junit)：用于在JUnit测试中运行嵌入式LDAP服务器的JUnit Rule。
* [Embedded MySQL](https://github.com/wix-incubator/wix-embedded-mysql)：用于测试的嵌入式MySQL。
* [Embedded MongoDB](https://github.com/flapdoodle-oss/de.flapdoodle.embed.mongo)：Embedded MongoDB提供一种平台中立的方式在单元测试中运行MongoDB。
* [Embedded Postgres Binaries](https://github.com/zonkyio/embedded-postgres-binaries)：该项目提供了PostgreSQL二进制文件的轻量级捆绑包，大小更小，旨在用于测试目的。
* [Embedded Database](https://github.com/zonkyio/embedded-database-spring-test)：用于为Spring支持的集成测试创建隔离的嵌入式数据库的库。
* [Embedded ElasticSearch](https://github.com/allegro/embedded-elasticsearch)：简化使用Elasticsearch创建集成测试的工具，由Allegro开源。
* [Embedded Consul](https://github.com/pszymczyk/embedded-consul)：Embedded Consul提供了在集成测试中运行Consul的简单方法。
* [DbFit](https://github.com/dbfit/dbfit)：DbFit是一个数据库测试框架，支持对数据库代码进行简单的测试驱动开发。
* [DbUnit](https://www.dbunit.org/)：DbUnit是一个JUnit扩展，针对数据库驱动的项目。
* [DbSetup](https://github.com/Ninja-Squad/DbSetup)：DbSetup允许在执行自动化集成测试(通常是DAO/Repository自动化测试)之前填充数据库。
* [Kafka JUnit](https://github.com/salesforce/kafka-junit)：该库包装了Kafka的嵌入式测试集群，使你可以更轻松地使用JUnit针对在测试上下文中运行的真实kafka服务器创建和运行集成测试，由Salesforce开源。
* [Database Rider](https://github.com/database-rider/database-rider)：Database Rider集成了DBUnit和JUnit，使数据库测试变得轻而易举。
* [ElasticSearch Test](https://github.com/tlrx/elasticsearch-test)：一个让ElasticSearch单元测试变得轻而易举的框架。
* [LDAP Server](https://github.com/intoolswetrust/ldap-server)：用于测试目的的简单内存LDAP服务器。
* [Fongo](https://github.com/fakemongo/fongo)：Fongo是MongoDB的内存中Java实现，主要用途是轻量级集成测试，由Foursquare开源。
* [MongoDB Java Server](https://github.com/bwaldvogel/mongo-java-server)：MongoDB Java Server是用Java伪造核心MongoDB服务器的实现，可用于集成测试。
* [Testcontainers Spring Boot](https://github.com/PlaytikaOSS/testcontainers-spring-boot)：基于Spring Boot的集成测试的容器自动配置。
* [Embedded Process Util](https://github.com/flapdoodle-oss/de.flapdoodle.embed.process)：Embedded Process Util为在单元测试中运行流程提供一种平台中立的方式。
* [Embedded PostgreSQL Server](https://github.com/yandex-qatools/postgresql-embedded)：嵌入式PostgreSQL服务器提供了一种平台中立的方式来在单元测试中运行Postgres二进制文件。
* [Embedded Cassandra](https://github.com/nosan/embedded-cassandra)：Embedded Cassandra提供了一种启动和停止Cassandra的简单方法。
* [CassandraUnit](https://github.com/jsevellec/cassandra-unit)：CassandraUnit是一个Java测试工具，它可以用于测试使用Cassandra数据库后端创建的Java应用程序。
* [Alternator](https://github.com/mboudreau/Alternator)：用于测试目的在本地运行的模拟DynamoDB。
* [Keycloak Testcontainer](https://github.com/dasniko/testcontainers-keycloak)：Keycloak SSO的Testcontainers实现。
* [MongoUnit](https://github.com/mongounit/mongounit)：MongoUnit是一个数据驱动的集成测试框架，适用于使用MongoDB进行持久化的基于Spring Boot的应用程序。
* [Arquillian](https://github.com/arquillian/arquillian-core)：Arquillian是一个创新且高度可扩展的JVM测试平台，使开发人员能够轻松地为Java中间件创建自动化集成、功能和验收测试，由RedHat开源。
* [Kindcontainer](https://github.com/dajudge/kindcontainer)：基于Java的Testcontainers容器实现，为集成测试提供临时Kubernetes集群。
* [Embedded DB JUnit](https://github.com/zapodot/embedded-db-junit)：提供内存数据库的JUnit Rule(支持H2和HyperSQL)。
* [Nats Server Embedded](https://github.com/YunaBraska/nats-server-embedded)：用于测试的Nats服务器。

#### 接口测试

* [Rest Assured](https://github.com/rest-assured/rest-assured)：Rest Assured是用于轻松测试REST服务的Java DSL。
* [Wisdom](https://github.com/wisdom-projects/rest-client)：Wisdom可以自动化测试REST API并生成精美的测试报告，同时基于测试过的历史数据，可以生成精美的REST API文档。
* [Milkman](https://github.com/warmuuh/milkman)：Postman的可扩展替代方案，用于制作各种请求，不仅适用于gRPC，还适用于HTTP、SQL等。
* [CATS](https://github.com/Endava/cats)：CATS是一个REST API模糊器和OpenAPI端点的负面测试工具，由Endava开源。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [Stove](https://github.com/Trendyol/stove)：Stove是一个端到端测试框架，可以将物理依赖项和你的应用程序一起启动，由Trendyol开源。
* [Everest](https://github.com/RohitAwate/Everest)：Everest是一个用JavaFX编写的REST API测试客户端。
* [ACTS](https://github.com/sofastack/sofa-acts)：ACTS是一个基于数据模型驱动的白盒测试框架，由蚂蚁开源。
* [HybridTestFramework](https://github.com/dipjyotimetia/HybridTestFramework)：HybridTestFramework是一个全面而多功能的测试框架，旨在涵盖软件测试的各个方面。
* [RESTClient](https://github.com/wiztools/rest-client)：RESTClient是一个用于测试RESTful Web服务的Java应用程序，它可用于测试各种HTTP通信。
* [Rest Driver](https://github.com/rest-driver/rest-driver)：用于测试RESTful服务和客户端的工具。
* [Hikaku](https://github.com/codecentric/hikaku)：Hikaku可以测试REST-API实现是否满足其规范。
* [Cukes](https://github.com/ctco/cukes)：用于测试RESTful Web服务的Cucumber DSL。
* [Sakuli](https://github.com/ConSol/sakuli)：Sakuli是一款端到端测试和监控工具，适用于具有多个监控集成的网站和常见UI。
* [Citrus](https://github.com/citrusframework/citrus)：Citrus是一个用Java编写的测试框架，能够为企业SOA应用程序创建完全自动化的端到端用例测试。
* [ChocoTea](https://github.com/cleopatra27/chocotea)：Chocotea是一个从Java代码生成Postman集合、环境和集成测试的库。
* [Raml-Tester](https://github.com/nidi3/raml-tester)：测试请求/响应是否与给定的raml定义匹配。
* [Heat](https://github.com/ExpediaGroup/heat)：Heat是一个基于REST Assured框架的简单解决方案，由Expedia开源。
* [iTest](https://gitee.com/itestwork/itest)：iTest包含任务管理、测试管理、缺陷管理、测试环境管理、接口测试、接口Mock、压力测试。

#### 功能测试

* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [Galen](https://github.com/galenframework/galen)：Galen是一个开源工具，用于测试Web应用程序的布局和响应式设计，它也是一个强大的功能测试框架。
* [Markov](https://github.com/alibaba/intelligent-test-platform)：Markov是阿里开源的新一代功能测试平台，包含可视化用例编写管理、分布式的沙盒环境和测试数据构建、测试流程pipeline管理等优点。
* [Acai](https://github.com/google/acai)：Acai使你可以轻松地使用JUnit 4和Guice编写应用程序的功能测试，由Google开源。

#### 突变测试

* [Pitest](https://github.com/hcoles/pitest)：Pitest是最先进的Java和JVM突变测试系统。
* [Major](https://mutation-testing.org/)：Major是一个高效、灵活的突变分析框架。
* [Descartes](https://github.com/STAMP-project/pitest-descartes)：Descartes通过报告所覆盖代码中的弱点来支持开发人员改进他们的测试套件。
* [Judy](http://mutationtesting.org/judy2/)：Judy是一个用Java编写的突变测试器，由弗罗茨瓦夫理工大学开源。
* [Code Defenders](https://github.com/CodeDefenders/CodeDefenders)：突变测试的游戏化，由帕绍大学和莱斯特大学开发。
* [PG Index Health](https://github.com/mfvanek/pg-index-health)：PG Index Health是一个用于分析和维护PostgreSQL数据库中索引和表健康状况的Java库。

#### 模糊测试

* [SQLancer](https://github.com/sqlancer/sqlancer)：SQLancer是一个自动测试DBMS以发现其实现中的逻辑错误的工具。
* [Javafuzz](https://github.com/fuzzitdev/javafuzz)：Javafuzz是用于测试Java包的覆盖率引导模糊器。
* [JQF](https://github.com/rohanpadhye/JQF)：JQF是一个针对Java的反馈导向模糊测试平台。
* [Mu2](https://github.com/cmu-pasta/mu2)：Mu2是一个用于突变引导模糊测试的模糊测试平台，构建在用于模糊Java程序的JQF平台之上，由CMU程序分析、软件测试和应用实验室开发。
* [EvoMaster](https://github.com/WebFuzzing/EvoMaster)：EvoMaster是第一个开源AI驱动工具，可为Web/企业应用程序自动生成系统级测试用例。
* [Jazzer](https://github.com/CodeIntelligenceTesting/jazzer)：由Code Intelligence开发的适用于JVM平台的覆盖率引导的进程内模糊器，它基于libFuzzer，并将许多由仪器驱动的突变功能引入JVM。

#### 性能测试

* [Apache JMeter](https://github.com/apache/jmeter)：JMeter开源负载测试工具，用于分析和测量各种服务的性能。
* [NGrinder](https://github.com/naver/ngrinder)：NGrinder是一个压力测试平台，使你能够同时执行脚本创建、测试执行、监控和结果报告生成器，Naver开源。
* [Gatling](https://github.com/gatling/gatling)：Gatling是一个负载测试工具，它正式支持HTTP、WebSocket、Server-Sent-Events和JMS。
* [Grinder](https://grinder.sourceforge.net/)：Grinder是一个Java负载测试框架，可以使用许多负载注入器轻松运行分布式测试。
* [NeoLoad](https://www.tricentis.com/neoload-quick-links)：NeoLoad是一个自动化性能测试平台，适用于企业组织从API到应用程序的持续测试。
* [JMH](https://github.com/openjdk/jmh)：JMH是一个Java工具，用于构建、运行和分析用Java和其他针对JVM的语言编写的宏观基准测试，Oracle开源。
* [Lago](https://github.com/twitter-archive/iago)：Lago是一种负载生成工具，可针对给定目标重放生产或合成流量，由Twitter开源。
* [Perfidix](https://github.com/sebastiangraf/perfidix)：Perfidix是一个轻量级Java库，使用户能够对源代码进行基准测试，由康斯坦茨大学开源。
* [PerfCake](https://github.com/PerfCake/PerfCake)：轻量级性能测试框架和负载生成器。
* [Caliper](https://github.com/google/caliper)：Caliper是一个用于测量Java代码性能的工具，主要侧重于微基准测试，由Google开源。
* [Criterium](https://github.com/hugoduncan/criterium)：使用Clojure编写的用于JVM的基准测试库。
* [ScalaMeter](https://github.com/scalameter/scalameter)：适用于JVM平台的微基准测试和性能回归测试框架，ScalaMeter可以自动测量和收集程序的各种指标，然后生成漂亮的报告，或存储你的数据。
* [JLBH](https://github.com/OpenHFT/JLBH)：JLBH是一个可让你对在上下文中运行的代码进行基准测试(而不是在微基准测试中)的工具。
* [KoPeMe](https://github.com/DaGeRe/KoPeMe)：KoPeMe是一个用于在Java中进行性能测试的框架。
* [Hyperfoil](https://github.com/Hyperfoil/Hyperfoil)：Hyperfoil是面向微服务的分布式基准测试框架，解决了协调遗漏谬误。
* [JUnitPerf](https://github.com/houbb/junitperf)：JUnitPerf是一款为Java开发者设计的性能测试框架。
* [JPerf](https://github.com/AgilData/jperf)：JPerf是一个简单的Java性能和可扩展性测试框架。
* [kraken](https://github.com/OctoPerf/kraken)：Kraken是一个基于Gatling的负载测试IDE。
* [XLT](https://github.com/Xceptance/XLT)：XLT是由Xceptance开发和维护的广泛负载和性能测试工具。
* [Intuit Tank](https://github.com/intuit/Tank)：Intuit Tank是一个在云环境中运行的负载测试平台，它目前支持Amazon Web界面并利用EC2、S3、CloudWatch(日志/指标)的服务。
* [JUnitPerf](https://github.com/noconnor/JUnitPerf)：使用JUnit构建的API性能测试框架。

#### 属性测试

* [JUnit Quickcheck](https://github.com/pholser/junit-quickcheck)：JUnit Quickcheck是一个支持在JUnit中编写和运行基于属性的测试的库。
* [Jqwik](https://github.com/jqwik-team/jqwik)：Jqwik的主要目的是将基于属性的测试引入JVM。
* [ScalaCheck](https://github.com/typelevel/scalacheck)：ScalaCheck是一个用Scala编写的库，用于对Scala或Java程序进行基于属性的自动化测试。
* [QuickTheories](https://github.com/quicktheories/QuickTheories)：Java 8基于属性的测试。
* [JetCheck](https://github.com/JetBrains/jetCheck)：JetCheck是一个基于属性的Java 8+测试库，由JetBrains开源。
* [QuickPerf](https://github.com/quick-perf/quickperf)：QuickPerf是Java的一个测试库，用于快速评估和改进一些与性能相关的属性。
* [ScalaProps](https://github.com/scalaprops/scalaprops)：Scala基于属性的测试库。
* [Hypothesis-Java](https://github.com/HypothesisWorks/hypothesis-java)：Hypothesis是一个专为主流语言设计的基于属性的现代测试系统。

#### A/B测试

* [Wasabi](https://github.com/intuit/wasabi)：Wasabi A/B测试服务是一个实时、企业级、100% API驱动的项目。
* [Proctor](https://github.com/indeedeng/proctor)：Proctor是一个用Java编写的A/B测试框架，由Indeed开发并大量使用。
* [Sixpack Java](https://github.com/sixpack/sixpack-java)：Sixpack A/B测试框架的Java客户端。
* [PlanOut4J](https://github.com/Glassdoor/planout4j)：PlanOut4J是Facebook PlanOut的基于Java的实现，PlanOut是一个A/B测试框架，旨在在网络上进行大规模实验。
* [Izanami](https://github.com/MAIF/izanami)：Izanami是一款共享配置、功能翻转和A/B测试服务器，非常适合微服务架构实现。
* [Apache Unomi](https://github.com/apache/unomi)：Unomi存储用户个人资料信息，主要用于为A/B测试和个性化提供后端服务器，由Jahia开源。

#### 验收测试

* [FitNesse](https://github.com/unclebob/fitnesse)：FitNesse是一个完全集成的独立验收测试框架和wiki，由Uncle Bob开发。
* [Thucydides](https://github.com/thucydides-webtests/thucydides)：Thucydides是一个旨在使编写自动化验收测试变得更容易、更有趣的库。
* [Gwen](https://github.com/shazam/gwen)：Gwen是一个允许使用Give-When-Then语法编写验收测试的简单库。
* [JLineup](https://github.com/otto-de/jlineup)：JLineup是一个对于网页的自动视觉回归测试非常有用的工具，特别是在持续交付管道中，它可以用作简单的命令行工具或通过REST API控制的小型Web服务。
* [Simple-DSL](https://github.com/LMAX-Exchange/Simple-DSL)：Simple-DSL是LMAX Exchange使用的一种编写验收测试的风格，旨在平衡人类和机器的可读性。
* [RestFixture](https://github.com/smartrics/RestFixture)：RestFixture是一个FitNesse测试夹具，允许开发人员和/或产品所有者以简单的方式为REST服务编写测试夹具。
* [JWebUnit](https://github.com/JWebUnit/jwebunit)：JWebUnit是一个Java框架，有助于为Web应用程序创建验收测试。
* [Kensa](https://github.com/kensa-dev/kensa)：Kensa是一个验收测试工具，支持Java、Kotlin和JUnit 5。

#### 回归测试

* [ARA](https://github.com/Decathlon/ara)：ARA可以预先分析你的非回归测试运行、跟踪和跟踪问题、保留其历史记录，甚至在质量不满足的情况下破坏你的CI构建，从而帮助你对抗回归，由迪卡侬开源。
* [AREX](https://github.com/arextest/arex-agent-java)：Arex是一个围绕利用现实世界数据(即数据库记录、服务负载、缓存项等)进行回归测试的非常简单的原则设计的框架。
* [NoraUi](https://github.com/NoraUi/NoraUi)：用户界面的非回归自动化。
* [Diffy](https://github.com/opendiffy/diffy)：Diffy使用并排运行新代码和旧代码的实例来发现服务中的潜在错误，由Twitter开源。
* [Gojira](https://github.com/flipkart-incubator/gojira)：Gojira是一个基于记录和回放的回归测试工具，由Flipkart开源。
* [Unlogged Java SDK](https://github.com/unloggedio/unlogged-sdk)：Unlogged Java SDK支持以二进制格式记录代码执行。
* [Drill4J](https://github.com/Drill4J/drill4j)：Drill4J是一款开源工具，用于识别测试差距并减少回归测试所花费的时间。

#### 契约测试

* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [Spring Cloud Contract](https://github.com/spring-cloud/spring-cloud-contract)：Spring对消费者驱动契约的支持。
* [Stubby4j](https://github.com/azagniotov/stubby4j)：HTTP/1.1、HTTP/2和WebSocket存根服务器，用于在Docker和非容器化环境中存根分布式Web服务以进行契约测试。
* [Contract Test Runner](https://github.com/wso2/contract-test-runner)：用于契约测试的Java库，由WSO2开源。
* [ContractCase Contract Testing Framework](https://github.com/case-contract-testing/java-dsl)：这是ContractCase契约测试框架的Java绑定。
* [Specmatic](https://github.com/znsio/specmatic)：Specmatic通过利用API规范作为可执行合约来体现契约驱动开发(CDD)。
* [Cofoja](https://github.com/nhatminhle/cofoja)：Cofoja是一种Java契约编程框架和测试工具，它使用注解处理和字节码检测来提供运行时检查。

#### 渗透测试

* [Cobalt Strike](https://www.cobaltstrike.com/)：Cobalt Strike是一款基于Java的渗透测试神器。
* [TrackRay](https://github.com/iSafeBlue/TrackRay)：溯光是一个开源渗透测试框架，框架自身实现了漏洞扫描功能，集成了知名安全工具：Metasploit、Nmap、Sqlmap、AWVS、Burpsuite等。
* [Jackhammer](https://github.com/olacabs/jackhammer)：Jackhammer是一款协作工具，旨在弥合安全团队与开发团队、QA团队之间的差距，并成为TPM的促进者，以了解和跟踪投入生产的代码的质量。
* [WS-Attacker](https://github.com/RUB-NDS/WS-Attacker)：WS-Attacker是一个用于Web服务渗透测试的模块化框架，由波鸿鲁尔大学开发。

#### 快照测试

* [ApprovalTests](https://github.com/approvals/ApprovalTests.Java)：Java的ApprovalTest验证库。
* [Java Snapshot Testing](https://github.com/origin-energy/java-snapshot-testing)：Java测试的Facebook风格快照测试。
* [Selfie](https://github.com/diffplug/selfie)：快照测试是记录和指定系统及其组件行为的最快且最精确的机制。

#### 断言库

* [AssertJ](https://github.com/assertj/assertj)：AssertJ提供了一组丰富且直观的强类型断言，用于单元测试。
* [AssertJ Android](https://github.com/square/assertj-android)：一组用于测试Android的AssertJ断言。
* [JSONAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest是一个匹配器库，可以将其组合起来以在测试中创建灵活的意图表达。
* [Spotify Hamcrest](https://github.com/spotify/java-hamcrest)：这是一个用有用的匹配器扩展Hamcrest匹配库的库集合，由Spotify开源。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java Bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Deepdive是Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：FEST-Assert为断言提供了流式的接口。
* [Expekt](https://github.com/winterbe/expekt): Kotlin的BDD断言库。
* [AssertJ-DB](https://github.com/assertj/assertj-db)：Expekt是一个Kotlin BDD断言库，受到Chai.js的启发。
* [JFRUnit](https://github.com/moditect/jfrunit)：用于断言JFR事件的JUnit扩展。
* [ArchUnit](https://github.com/TNG/ArchUnit)：ArchUnit是一个免费、简单且可扩展的库，用于检查Java代码的架构。
* [Confidence](https://github.com/saynotobugsorg/confidence)：Confidence是一个声明式Java断言框架。
* [Power Assert](https://github.com/jkschneider/java-power-assert)：Power Assert通过条件评估过程中产生的值的信息来增强断言失败，并以易于理解的形式呈现它们。
* [Visible Assertions](https://github.com/rnorth/visible-assertions)：JUnit断言的替代方案，为你的测试提供更有洞察力的日志叙述。
* [LogCapture](https://github.com/jsalinaspolo/logcapture)：LogCapture是一个用于断言日志消息的测试库。
* [Log Capture](https://github.com/dm-drogeriemarkt/log-capture)：日志消息的简单断言。
* [Atrium](https://github.com/robstoll/atrium)：Atrium是一个针对Kotlin的开源多平台期望/断言库，支持JVM、JS和Android。
* [ModelAssert](https://github.com/webcompere/model-assert)：用于模型数据的断言库。
* [Valid4j](https://github.com/valid4j/valid4j)：Java的简单断言和验证库。
* [DataSource-Assert](https://github.com/ttddyy/datasource-assert)：DataSource-Assert为DataSource提供断言API以验证查询执行。
* [Strikt](https://github.com/robfletcher/strikt)：Strikt是Kotlin的断言库，旨在与JUnit、Minutest、Spek或KotlinTest等测试运行器一起使用。
* [NDD Check4J](https://gitlab.com/ndd-oss/java/ndd-check4j)：NDD Check4J通过流式或简洁的API提供简单的参数检查。
* [LambSpec](https://github.com/pholser/lambspec)：适用于Java 8的类似RSpec的断言库。
* [Hamcrest-JSON](https://github.com/hertzsprung/hamcrest-json)：用于比较JSON文档的Hamcrest匹配器。
* [Jcabi-Matchers](https://github.com/jcabi/jcabi-matchers)：一些方便的Hamcrest匹配器，主要用于XPath与XHTML以及JAXB中的字段。
* [Shazamcrest](https://github.com/shazam/shazamcrest)：适用于自动化测试的可重复使用的Hamcrest匹配器。
* [ReCheck](https://github.com/retest/recheck)：ReCheck是一个功能齐全的开源测试工具，允许替换手动断言并立即检查所有内容。

#### Mock框架

* [Mockito](https://github.com/mockito/mockito)：Mockito是Java中最流行的单元测试Mock框架。
* [PowerMock](https://github.com/powermock/powermock)：PowerMock是一个框架，它扩展了EasyMock等其他Mock库，使其具有更强大的功能。
* [TestableMock](https://github.com/alibaba/testable-mock)：TestableMock是一款轻量Mock工具，由阿里开源。
* [EasyMock](https://github.com/easymock/easymock)：EasyMock是一个Java库，它提供了一种在单元测试中使用Mock对象的简单方法。
* [Mockk](https://github.com/mockk/mockk)：用于Kotlin的Mock框架。
* [JMock](https://github.com/jmock-developers/jmock-library)：JMock是一个支持使用Mock对象进行Java代码测试驱动开发的库。
* [ScalaMock](https://github.com/paulbutcher/ScalaMock)：原生Scala Mock框架。
* [JMockit](https://github.com/jmockit/jmockit1)：JMockit是用于集成测试、Mock、伪造和代码覆盖率的高级Java库。
* [Mockrunner](https://github.com/mockrunner/mockrunner)：Mockrunner是用于企业级应用程序的Mock工具。

#### 接口Mock

* [Moco](https://github.com/dreamhead/moco)：Moco是一个易于设置的存根框架。
* [WireMock](https://github.com/wiremock/wiremock)：WireMock是一种流行的API Mock测试开源工具。
* [Microcks](https://github.com/microcks/microcks)：Microcks是用于API Mock和测试的开源云原生工具。
* [MockServer](https://github.com/mock-server/mockserver)：MockServer可以轻松模拟通过HTTP或HTTPS与用Java、JavaScript和Ruby编写的客户端集成的任何系统。
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver)：用于测试HTTP客户端的可编写脚本的Web服务器。
* [AnyMock](https://github.com/duxiaoman/AnyMock)：AnyMock是一个通用接口Mock平台，提供Mock配置和模拟响应的服务，由度小满开源。
* [Imposter](https://github.com/outofcoffee/imposter)：Imposter是REST API、OpenAPI规范、SOAP Web Services、Salesforce和HBase API的Mock服务器。
* [Flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的，由LinkedIn开源。
* [Mockey](https://github.com/clafonta/Mockey)：Mockey是一个用于测试通过HTTP的应用程序交互的工具，重点是测试Web服务，特别是使用XML、JSON和HTML的Web或原生应用程序。
* [SMockin](https://github.com/matthewgallina/smockin)：SMockin是一种用于动态模拟API端点、S3存储桶和电子邮件帐户的开发工具。
* [Betamax](https://github.com/betamaxteam/betamax)：Betamax是一个用于在测试中模拟外部HTTP资源的工具，该项目的灵感来自于Ruby的VCR库。
* [HttpMocker](https://github.com/speekha/httpmocker)：HttpMocker是一个非常轻量的Kotlin库，允许依赖OkHttp或Ktor客户端库来模拟HTTP调用。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [Restito](https://github.com/mkotsur/restito)：Restito是一个用于验证代码与REST服务交互的工具。
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP)：DeepfakeHTTP是一个使用HTTP转储作为响应源的Web服务器。
* [Jadler](https://github.com/jadler-mocking/jadler)：Jadler是一个Java库，用于以声明方式存根和模拟HTTP服务器和资源。
* [SpecMock](https://github.com/specmock/specmock)：SpecMock提供了各种规格的Mock Server，提供轻量、快速且易于使用的体验。
* [Logging Interceptor](https://github.com/ihsanbal/LoggingInterceptor)：Logging Interceptor是一个OkHttp拦截器，具有漂亮的请求和响应记录器，以及Mock支持。
* [ZeroMock](https://github.com/tonivade/zeromock)：零依赖的模拟HTTP Server。
* [OKHttp Client Mock](https://github.com/gmazzo/okhttp-client-mock)：一个简单的OKHttp客户端Mock，使用可编程请求拦截器。
* [OkReplay](https://github.com/airbnb/okreplay)：OkReplay旨在通过拦截应用程序发起的HTTP连接并重放之前记录的响应，由Airbnb开发。
* [RESTMock](https://github.com/andrzejchm/RESTMock)：RESTMock是一个建立在MockWebServer之上的库，它允许你指定Hamcrest匹配器来匹配HTTP请求并指定要返回的响应。

#### Mock库

* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ Java AMQP-Client的Mock库。
* [S3Mock](https://github.com/adobe/S3Mock)：S3Mock是一个轻量级服务器，它实现了部分Amazon S3 API，由Adobe开源。
* [S3Mock](https://github.com/findify/s3mock)：S3Mock是一个实现AWS S3 API的Web服务，可用于使用S3对代码进行本地测试。
* [S3Ninja](https://github.com/scireum/s3ninja)：S3Ninja模拟Amazon S3 API以用于开发和测试目的。
* [GreenMail](https://github.com/greenmail-mail-test/greenmail)：GreenMail是一个开源、直观且易于使用的电子邮件服务器测试套件。
* [DaggerMock](https://github.com/fabioCollini/DaggerMock)：用于轻松覆盖Dagger 2对象的JUnit Rule。
* [CouchbaseMock](https://github.com/couchbase/CouchbaseMock)：CouchbaseMock是一个测试Couchbase服务器。
* [Hoverfly](https://github.com/SpectoLabs/hoverfly-java)：Hoverfly的Java绑定，Hoverfly是一个允许你模拟HTTP服务的代理。
* [Keycloak Mock](https://github.com/TNG/keycloak-mock)：提供Keycloak测试支持的Java库。
* [gRPC Mock](https://github.com/Fadelis/grpcmock)：一个gRPC Java测试工具，可轻松Mock gRPC服务端点以进行集成测试或单元测试。
* [GwtMockito](https://github.com/google/gwtmockito)：GwtMockito是用于GWT应用程序的测试工具，由Google开源。
* [Mock-OAuth2-Server](https://github.com/navikt/mock-oauth2-server)：可编写脚本/可自定义的Web服务器，用于使用OAuth2/OpenID Connect测试HTTP客户端或依赖于正在运行的OAuth2服务器的应用程序。
* [Thrift Mock](https://github.com/didi/thrift-mock)：Thrift Mock是用于Thrift服务的轻量级Java单元测试库，由滴滴开源。
* [Spring Data Mock](https://github.com/mmnaseri/spring-data-mock)：Spring Data Repository的Mock工具。
* [MockFtpServer](https://github.com/dx42/MockFtpServer)：MockFtpServer项目提供模拟/虚拟FTP服务器实现来测试FTP客户端代码。
* [Odo](https://github.com/groupon/odo)：Odo是一个代理服务器，可以充当模拟服务器或允许操作实时数据。

#### 数据Mock

* [Java Faker](https://github.com/DiUS/java-faker)：Java Faker是Ruby的stympy/faker gem的Java端口，用于生成假数据。
* [Instancio](https://github.com/instancio/instancio)：Instancio是一个Java库，可以自动为单元测试创建和填充对象。
* [JUnit DataProvider](https://github.com/TNG/junit-dataprovider)：DataProvider类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：Datafaker是一个用于Java和Kotlin生成虚假数据的库。
* [EasyRandom](https://github.com/j-easy/easy-random)：Easy Random是一个生成随机Java对象的库。
* [MockNeat](https://github.com/nomemory/mockneat)：Mockneat是一个用Java编写的任意数据生成器开源库。
* [jFairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：Jmockdata是一款实现模拟Java类或对象的实例化并随机初始化对象的数据的工具框架。
* [Kotlin Faker](https://github.com/serpro69/kotlin-faker)：用Kotlin编写的流行Ruby faker gem的移植版。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：Fixture Monkey旨在轻松生成可控的任意实例，它允许你在多个测试中重复使用实例的相同配置，由Naver开源。
* [Burst](https://github.com/square/burst)：Burst是用于不同测试数据的单元测试库，由Square开源。
* [Log Synth](https://github.com/tdunning/log-synth)：Log Synth的主要用途是根据指定的模式生成数据。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。
* [Beanmother](https://github.com/keepcosmos/beanmother)：Beanmother有助于创建各种对象，可以非常轻松地使用用于测试的夹具。
* [Common Random](https://github.com/yindz/common-random)：Common Random是一个简单易用的随机数据生成器。
* [JFactory](https://github.com/leeonky/jfactory)：JFactory是通过工厂方法创建具有某些默认属性测试数据的工具库。
* [DataHelix](https://github.com/finos/datahelix)：DataHelix可以快速生成丰富且真实的数据用于模拟和测试。
* [Fixture Factory](https://github.com/six2six/fixture-factory)：Fixture Factory是一个帮助开发人员快速构建和组织假对象以进行单元测试的工具。
* [Wordnet Random Name](https://github.com/kohsuke/wordnet-random-name)：用于测试的人类友好随机名称生成器。
* [Podam](https://github.com/mtedone/podam)：Podam是一个Java测试工具，可以用虚构的数据自动填充POJO。
* [RandomData](https://github.com/ZieIony/RandomData)：RandomData自动用生成的随机名称、数字、图像等填充对象。
* [AutoParams](https://github.com/AutoParams/AutoParams)：AutoParams是一个专为Java参数化测试而设计的任意测试数据生成器。
* [Java Random](https://github.com/merkle-open/java-random)：Java Random提供了一种通用机制来创建Java对象的随机测试虚拟对象。
* [JFixture](https://github.com/FlexTradeUKLtd/jfixture)：JFixture是一个自动填充测试数据的Java库。
* [DataFactory](https://github.com/andygibson/datafactory)：用于生成测试数据的Java库。
* [Mock.java](https://gitee.com/ForteScarlet/Mock.java)：这是一个仿照Mock.js语法的Java语言使用的假数据生成工具框架。
* [Java Generator](https://github.com/binarywang/java-testdata-generator)：Java实现的各种随机测试数据生成器，包括身份证号码、银行卡号、姓名、汉字、手机号、电子邮箱地址等。
* [Test Data Supplier](https://github.com/sskorol/test-data-supplier)：该仓库包含TestNG DataProvider包装器，有助于以更灵活的方式提供测试数据。
* [Data Factory](https://github.com/houbb/data-factory)：Data Factory用于根据对象随机自动生成初始化信息。
* [Elmyr](https://github.com/xgouchet/Elmyr)：Elmyr是一个Kotlin库，提供生成随机值的工具。
* [EvoSQL](https://github.com/SERG-Delft/evosql)：EvoSQL是一种自动为SQL查询生成测试数据的工具，由代尔夫特理工大学开源。
* [RandomJson](https://github.com/mangatmodi/RandomJson)：RandomJson提供Kotlin/Java库来创建随机JSON字符串。
* [Nomen est Omen](https://github.com/igr/nomen-est-omen)：这个Java库有助于生成一些随机名称，你可以将它们用于某些唯一的ID或密码。
* [Model Citizen](https://github.com/mguymon/model-citizen)：Model Citizen是一个基于注解的Java模型工厂。
* [Test Arranger](https://github.com/ocadotechnology/test-arranger)：将测试数据排列为完全填充的对象。
* [Datagen](https://github.com/qala-io/datagen)：用于生成随机数据(数字、字符串、日期)的Java库-以便于随机测试。
* [Fabricator](https://github.com/azakordonets/fabricator)：Fabricator是随机字符串、数字等的极简生成器，有助于减少单调性。
* [Make It Easy](https://github.com/npryce/make-it-easy)：一个微型框架，可轻松用Java编写测试数据构建器。

#### BDD框架

* [Cucumber](https://github.com/cucumber/cucumber-jvm)：Cucumber是一个支持行为驱动开发(BDD)的工具。
* [Karate](https://github.com/karatelabs/karate)：Karate是将API测试自动化、Mock、性能测试甚至UI自动化整合到一个统一框架中的开源工具，由Intuit开源。
* [Quantum](https://github.com/Perfecto-Quantum/Quantum)：Quantum是一个由Perfecto设计的基于Java的开源BDD测试框架。
* [Spek](https://github.com/spekframework/spek)：Spek是Kotlin的规范框架。
* [Serenity BDD](https://github.com/serenity-bdd/serenity-core)：Serenity BDD是一个旨在使编写自动化验收测试变得更容易、更有趣的库。
* [Concordion](https://github.com/concordion/concordion)：Concordion是一个可执行规范的开源运行程序，可创建丰富的实时文档。
* [YAKS](https://github.com/citrusframework/yaks)：YAKS是一个在Kubernetes上启用云原生BDD测试的框架。
* [JBehave](https://github.com/jbehave/jbehave-core)：JBehave是一个适用于Java和所有JVM语言的BDD框架。
* [JGiven](https://github.com/TNG/JGiven)：JGiven是一个开发人员友好且实用的Java BDD工具。
* [Chorus](https://github.com/Chorus-bdd/Chorus)：Chorus是一个BDD测试解释器，具有用于测试分布式架构的额外功能。
* [ScalaTest](https://github.com/scalatest/scalatest)：ScalaTest是一个为Scala和Java程序员提供的免费开源测试工具包。
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Lambda Behave是Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：Spectrum受到BDD框架Jasmine和RSpec的启发，将它们的表达语法和功能风格引入Java测试。
* [Specs2](https://github.com/etorreborre/specs2)：Specs2是一个用于在Scala中编写可执行软件规范的库。
* [YatSpec](https://github.com/bodar/yatspec)：YatSpec是一个BDD测试框架，可以运行你的JUnit测试并生成人类可读的HTML报告。
* [SmartBDD](https://github.com/bit-smart-io/smart-bdd)：从Java代码创建交互式HTML文档/功能文件的BDD框架。
* [BDD Security](https://github.com/iriusrisk/bdd-security)：BDD Security是一个安全测试框架，它使用行为驱动开发概念来创建自我验证的安全规范。
* [J8Spec](https://github.com/j8spec/j8spec)：J8Spec是一个库，允许用Java编写的测试遵循RSpec和Jasmine引入的BDD风格。
* [Narrative](https://github.com/tim-group/narrative)：用于使用流式Java构建行为驱动测试的框架。
* [Wakamiti](https://github.com/iti-ict/wakamiti)：Wakamiti是一款受Cucumber启发的自动化测试工具，专注于使用自然语言进行黑盒测试，由瓦伦西亚理工大学开源。
* [Tiger](https://github.com/gematik/app-Tiger)：Tiger是一个接口驱动的BDD黑盒测试框架。
* [Akita](https://github.com/alfa-laboratory/akita)：基于Cucumber和Selenide的BDD测试步骤库。
* [Cuppa](https://github.com/cuppa-framework/cuppa)：Cuppa是Java 8的测试框架，它使编写测试变得高效且有趣。
* [JDave](https://github.com/jdave/JDave)：JDave是Java的BDD框架。

#### 测试生成器

* [Auto Unit Test Case Generator](https://github.com/traas-stack/auto-unit-test-case-generator)：Auto Unit Test Case Generator自动生成Java的高级代码覆盖JUnit测试套件，在蚂蚁中广泛使用。
* [Tcases](https://github.com/Cornutum/tcases)：Tcases是基于模型的测试用例生成器。
* [JCUnit](https://github.com/dakusui/jcunit)：JCUnit是一个基于模型的开源测试框架，由组合交互测试技术提供支持。
* [ChatUniTest](https://github.com/ZJU-ACES-ISE/chatunitest-core)：ChatUniTest是一个创新框架，旨在改进自动化单元测试生成，由浙江大学开源。
* [GraphWalker](https://github.com/GraphWalker/graphwalker-project)：GraphWalker是一个基于模型的测试工具，它以有向图的形式读取模型，并从这些图生成测试路径。
* [Randoop](https://github.com/randoop/randoop)：Randoop是Java的单元测试生成器，它会自动为你的类创建JUnit格式的单元测试。
* [DSpot](https://github.com/STAMP-project/dspot)：DSpot是一个在JUnit测试中生成缺失断言的工具。
* [Diffblue](https://www.diffblue.com/)：Diffblue Cover使用下一代自主AI来自动化单元测试，以便Java开发团队可以更快地构建更好的应用程序。
* [Squaretest](https://squaretest.com/)：Squaretest是一个自动为Java类生成单元测试的Intellij IDEA插件。
* [Symflower](https://symflower.com/en/)：Symflower是Java代码生成工具，旨在减少单元和集成测试的日常工作。
* [AgitarOne](http://www.agitar.com/solutions/products/agitarone.html)：用于生成Java代码测试用例的工具。
* [Jtest](https://www.parasoft.com/products/parasoft-jtest/)：通过AI优化的静态分析和AI支持的自动化单元测试加速Java软件开发，以提供可靠、安全且可维护的软件。
* [EvoSuite](https://github.com/EvoSuite/evosuite)：EvoSuite自动为Java类生成JUnit测试套件，针对代码覆盖率标准。
* [UTBotJava](https://github.com/UnitTestBot/UTBotJava)：UnitTestBot是用于自动化单元测试生成和精确代码分析的工具。
* [TestMe](https://github.com/wrdv/testme-idea)：自动为Java、Groovy、Scala生成测试用例的Intellij IDEA插件。

#### Selenium生态

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库，由ThoughtWork开源。
* [Selenium Jupiter](https://github.com/bonigarcia/selenium-jupiter)：Selenium Jupiter是一个开源Java库，它实现了用于开发Selenium WebDriver测试的JUnit 5扩展。
* [Zalenium](https://github.com/zalando/zalenium)：Zalenium是一个灵活且可扩展的基于容器的Selenium Grid，具有视频录制、实时预览、基本身份验证和仪表板，由Zalando开源。
* [Selenide](https://github.com/selenide/selenide)：Selenide是一个用Java编写易于阅读和易于维护的自动化测试的框架。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：WebDriverManager是一个开源Java库，用于对Selenium WebDriver所需的驱动程序(例如chromedriver、geckodriver、msedgedriver等)进行管理。
* [Selendroid](https://github.com/selendroid/selendroid)：Selendroid是一个测试自动化框架，它通过Selendroid驱动Android原生和混合应用程序以及移动Web的UI。
* [jBrowserDriver](https://github.com/MachinePublishers/jBrowserDriver)：与Selenium WebDriver规范兼容的可编程、可嵌入的Web浏览器驱动程序。
* [Html Elements](https://github.com/yandex-qatools/htmlelements)：Html Elements是一个Java框架，提供在网页测试中与网页元素交互的易于使用的方式。
* [FluentSelenium](https://github.com/SeleniumHQ/fluent-selenium)：FluentSelenium是Selenium 2+的包装器，添加了用于浏览器的流式界面样式，可以更轻松、更快速地编写Web UI测试。
* [Frameworkium](https://github.com/Frameworkium/frameworkium-core)：Frameworkium是用于Web、应用程序和API测试的快速启动自动化框架。
* [Aquality Selenium](https://github.com/aquality-automation/aquality-selenium-java)：Aquality Selenium是一个基于Selenium WebDriver工具构建的库，允许使用Web浏览器实现自动化工作。
* [Conductor](https://github.com/conductor-framework/conductor)：Selenium WebDriver API的包装器。
* [aShot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具，截图、裁剪、美化、比较。
* [Darcy](https://github.com/darcy-framework)：Darcy是一个开源Java 8框架，用于使用声明式、与自动化库无关的DSL将用户界面建模为页面对象，由RedHat开源。
* [HtmlUnitDriver](https://github.com/SeleniumHQ/htmlunit-driver)：HtmlUnitDriver是HtmlUnit无头浏览器的WebDriver兼容驱动程序。
* [Shutterbug](https://github.com/assertthat/selenium-shutterbug)：Selenium Shutterbug是一个用Java编写的实用程序库，用于使用Selenium WebDriver制作屏幕截图。
* [Selenium Cucumber](https://github.com/selenium-cucumber/selenium-cucumber-java)：Selenium Cucumber是一种BDD方法，用于编写自动化测试脚本来测试Web。
* [Selenese Runner Java](https://github.com/vmi/selenese-runner-java)：Selenium IDE原生格式(selenese和side)解释器。
* [UTAM Java](https://github.com/salesforce/utam-java)：UI测试自动化模型(UTAM)项目允许开发人员创建和使用页面对象，通过浏览器自动化网页，由Salesforce开源。
* [Atlas](https://github.com/qameta/atlas)：另一个WebDriver包装器。
* [Ghost Driver](https://github.com/detro/ghostdriver)：Ghost Driver是PhantomJS的WebDriver Wire协议的纯JavaScript实现，它是一个使用PhantomJS作为后端的远程WebDriver。
* [Healenium-Web](https://github.com/healenium/healenium-web)：用于Selenium基于Web的测试的自我修复库。
* [Pickleib](https://github.com/Umutayb/Pickleib)：Pickleib是一个用于软件自动化项目的实用程序库，它可以帮助你以简单有效的方式使用Selenium WebDriver设计和运行测试。
* [Selenium Foundation](https://github.com/sbabcoc/Selenium-Foundation)：Selenium Foundation是一个自动化框架，旨在扩展和增强Selenium WebDriver提供的功能。
* [Page Factory 2](https://github.com/sbtqa/page-factory-2)：Page-Factory-2是一个用于自动化测试的开源Java框架，允许你以BDD风格开发自动测试，重点是使用页面工厂模式。
* [Atlassian Selenium](https://bitbucket.org/atlassian/atlassian-selenium)：由Atlassian开源的项目，旨在促进Selenium/WebDriver库中功能测试的开发。
* [Jalenium](https://lkkushan.gitbook.io/jalenium)：Jalenium是一个Selenium Java包装器，使Selenium Java中的测试自动化更加简单。
* [Selenium Grid Extras](https://github.com/groupon/Selenium-Grid-Extras)：Selenium Grid Extras是一个帮助你设置和管理本地Selenium Grid的项目。
* [Selenium Grid Router](https://github.com/seleniumkit/gridrouter)：Selenium Grid Router是一个轻量级服务器，它将Selenium Webdriver请求路由和代理到多个Selenium集线器。
* [Testy](https://github.com/RWS/Testy)：Testy是用于Web应用程序的Selenium WebDriver测试框架。

#### 自动化框架

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库，由ThoughtWork开源。
* [Playwright](https://github.com/microsoft/playwright-java)：Playwright是一个Java库，可通过单个API实现Chromium、Firefox和WebKit的自动化，由Microsoft开源。
* [F2etest](https://github.com/alibaba/f2etest)：F2etest是一个面向前端、测试、产品等岗位的多浏览器兼容性测试整体解决方案，由阿里开源。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [SeLion](https://github.com/paypal/SeLion)：SeLion是Paypal开源的自动化测试工具。
* [Robotium](https://github.com/robotiumtech/robotium)：Robotium是一个Android测试自动化框架，完全支持原生和混合应用程序。
* [JDI Light](https://github.com/jdi-testing/jdi-light)：JDI Light是一个功能强大的测试自动化框架，有助于使你的测试快速、可持续，并提供明显且可预测的测试运行结果，由EPAM开源。
* [ZeroCode](https://github.com/authorjapps/zerocode)：ZeroCode是一个社区开发的免费开源自动化测试框架，用于微服务API、Kafka和负载测试。
* [Carina](https://github.com/zebrunner/carina)：Carina是一个基于Java的测试自动化框架。
* [Geb](https://github.com/geb/geb)：Geb是一种浏览器自动化解决方案，它汇集了WebDriver的强大功能、jQuery内容选择的优雅性、页面对象建模的稳健性以及Groovy语言的表现力。
* [Dagger](https://github.com/NetEase/Dagger)：Dagger是一个基于Selenium和TestNG的轻量级、健壮的Web UI自动测试框架，由网易开源。
* [RESTest](https://github.com/isa-group/RESTest)：RESTest是一个用于RESTful Web API自动化黑盒测试的框架，由塞维利亚大学开源。
* [RestTestGen](https://github.com/SeUniVr/RestTestGen)：RestTestGen是一个强大的工具和框架，专为RESTful Web API的自动化黑盒测试而设计，由维罗纳大学开源。
* [HBrowser](https://github.com/Osiris-Team/HBrowser)：无头/完整的Java浏览器，支持下载文件、使用Cookie、检索HTML和模拟真实用户输入。
* [ATS Framework](https://github.com/Axway/ats-framework)：ATS是内部开发的测试框架，广泛用于满足大多数Axway产品的测试需求。
* [Appium Client](https://github.com/appium/java-client)：用于编写符合WebDriver协议的Appium测试的Java语言绑定。
* [Ride](https://github.com/adobe/ride)：Ride是一个与服务无关、模块化、可扩展的Java REST API自动化框架，由Adobe开源。
* [Boyka Framework](https://github.com/BoykaFramework/boyka-framework)：测试自动化框架，可在任何平台上自动化任何应用程序。
* [Gepard](https://github.com/epam/Gepard)：Gepard是一个基于JUnit的测试自动化框架，由EPAM开源。
* [TestZeus](https://github.com/TestZeus/TestZeus)：TestZeus是专为Salesforce构建的开源自动化框架。
* [UI-Automation](https://github.com/mmarquee/ui-automation)：UI-Automation是一个用于自动化(通过MS UIAutomation库)基于Win32、WPF和其他Windows应用程序的富客户端应用程序的框架。
* [FastAutoTest](https://github.com/y-grey/FastAutoTest)：FastAutoTest是一个基于Appium的快速自动化框架。
* [Selcukes Java](https://github.com/selcukes/selcukes-java)：Selcukes是一个强大的开源测试库，适用于Web、移动、桌面应用程序和API端点，旨在创建可扩展的高质量自动化测试。
* [Smart Test Framework](https://github.com/HPInc/smart-test-framework)：Smart Test Framework是一个多用途测试框架，能够为网页、Web服务、桌面应用程序和移动应用程序创建自动化测试，由惠普开源。
* [TestHub](https://gitee.com/dromara/TestHub)：TestHub是一款基于流程编排的自动化测试工具，由dromara社区开源。
* [JSystem](https://github.com/Top-Q/jsystem)：JSystem是一个用于编写和管理自动化系统测试的专业开源框架。

#### 自动化工具

* [MeterSphere](https://github.com/metersphere/metersphere)：MeterSphere是一站式开源持续测试平台，涵盖测试跟踪、接口测试、UI测试和性能测试等功能，全面兼容JMeter、Selenium等主流开源标准，由飞致云开源。
* [Aqua](https://www.jetbrains.com/aqua/)：Aqua是一个专门为测试自动化创建的IDE，由JetBrains开发。
* [Sonic](https://github.com/SonicCloudOrg/sonic-server)：Sonic是一个集远程控制调试和移动设备自动化测试于一体的平台，致力于为全球开发者和测试工程师创造更好的使用体验。
* [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb)：LuckyFrame是一款免费开源的测试平台，最大的特点是全纬度覆盖了接口自动化、WEB UI自动化、APP自动化。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具，由阿里开源。
* [ReadyAPI](https://smartbear.com/product/ready-api/)：ReadyAPI是一个专业的API测试工具，支持Java集成和自动化测试，由SmartBear开发。
* [HydraLab](https://github.com/microsoft/HydraLab)：HydraLab是一个可以帮助你利用现有的测试设备/机器轻松构建云测试平台的框架，由Microsoft开源。
* [Hamibot](https://github.com/hamibot/hamibot)：Hamibot是一款Android平台JavaScript自动化工具，无需Root，基于Auto.js。
* [Testsigma](https://github.com/testsigmahq/testsigma)：Testsigma是一个开源、可扩展的测试自动化平台，开箱即用。
* [OpenTest](https://github.com/mcdcorp/opentest)：OpenTest是一款免费开源功能测试自动化工具，适用于Web应用程序、移动应用程序和API，麦当劳开源。
* [VIVIDUS](https://github.com/vividus-framework/vividus)：VIVIDUS是一种测试自动化工具，为测试最流行的应用程序类型提供已实施的解决方案。
* [Cerberus](https://github.com/cerberustesting/cerberus-core)：Cerberus Test是一个低代码测试自动化平台，支持测试Web、iOS、Android和API(REST、SOAP和Kafka)应用程序。
* [SHAFT](https://github.com/ShaftHQ/SHAFT_ENGINE)：SHAFT是一个统一的测试自动化引擎，由一流的框架提供支持，提供类似向导的语法来高效推动自动化、最大化你的投资回报率并最小化你的学习曲线。
* [AutoMeter](https://gitee.com/season-fan/autometer-api)：AutoMeter是一款针对分布式服务、微服务API做功能和性能一体化的自动化测试平台。
* [INGenious](https://github.com/ing-bank/INGenious)：INGenious提供了一种简单易行的方式来创建高度可靠的自动化测试，由ING银行开源。
* [AppiumTestDistribution](https://github.com/AppiumTestDistribution/AppiumTestDistribution)：一个用于跨设备并行运行Android和iOS Appium测试的工具。
* [Neodymium](https://github.com/Xceptance/neodymium-library)：Neodymium尝试通过结合JUnit、WebDriver、BDD/Cucumber和适当的报告来解决典型且最紧迫的UI测试自动化问题，由Xceptance开发。
* [Video Recorder](https://github.com/SergeyPirogov/video-recorder-java)：该库只需添加一些注解即可轻松录制UI测试的视频。
* [Step](https://github.com/exense/step)：Step是一个统一的软件自动化平台，可让你充分利用自动化工件，同时摆脱特定工具。
* [TESTAR](https://github.com/TESTARtool/TESTAR_dev)：TESTAR是一款能够在GUI级别对桌面、Web和移动应用程序进行无脚本自动化系统测试的工具，由瓦伦西亚理工大学、乌得勒支大学和荷兰开放大学等开发。
* [Testerra](https://github.com/telekom/testerra)：Testerra是一个用于自动测试(Web)应用程序的集成框架，由德国电信开源。
* [ReVoman](https://github.com/salesforce-misc/ReVoman)：ReVoman是一个JVM API自动化工具，它通过让你在JVM程序/测试中执行Postman集合来重新构想API自动化，由Salesforce开源。
* [BotCity Framework](https://github.com/botcity-dev/botcity-framework-core)：BotCity RPA模块提供识别UI元素并使用鼠标和键盘操作与其交互的功能。
* [Sahi](https://www.sahipro.com/)：Sahi是一个成熟、业务就绪的测试自动化平台，用于对UI密集型应用程序进行功能测试。
* [T-Plan](https://www.t-plan.com/)：T-Plan是一个机器人流程自动化和GUI测试自动化项目。
* [ATP](https://atestingp.sourceforge.net/)：ATP是一个自动化测试和分析工具，由西班牙马德里理工大学开源。
* [Maveryx](https://www.maveryx.com/)：Maveryx是一款专注于减少测试维护成本、适应动态UI的高效测试自动化工具。

#### QA自动化

* [Stevia](https://github.com/persado/stevia)：Stevia是Persado的开源QA自动化测试框架。
* [QMetry](https://github.com/qmetry/qaf)：使用Selenium、WebDriver、TestNG和Jersey的Web、MobileWeb移动原生和Rest Web服务的质量自动化框架。
* [AET](https://github.com/wttech/aet)：AET是一个检测网站上的视觉变化并执行基本页面健康检查(如W3C合规性、可访问性、HTTP状态码、JS错误检查等)的系统。

#### 测试报告

* [Allure](https://github.com/allure-framework/allure2)：Allure Report是一种灵活的多语言测试报告工具，可向你展示已测试内容的详细表示，并从日常测试执行中提取最大程度的信息。
* [Scott](https://github.com/dodie/scott)：Scott为Java测试提供了详细的失败消息，并且无需使用复杂的断言库。
* [ReportPortal](https://github.com/reportportal/reportportal)：ReportPortal是一项TestOps服务，它提供了增强的功能，通过使用内置分析功能来加速结果分析和报告。
* [Zebrunner Reporting](https://github.com/zebrunner/reporting)：Zebrunner Reporting是一种测试自动化管理工具，可累积并表示测试结果。
* [Difido Reports](https://github.com/Top-Q/difido-reports)：该项目旨在为各种功能测试自动化框架提供灵活、实时的HTML报告。
* [Cluecumber](https://github.com/trivago/cluecumber)：用于从Cucumber BDD、Karate和其他框架生成的Cucumber兼容JSON文件创建聚合测试报告。
* [Open Test Reporting](https://github.com/ota4j-team/open-test-reporting)：与语言无关的测试报告格式和工具。
* [Cucumber Reporting](https://github.com/damianszczepanik/cucumber-reporting)：这是一个Java报告发布器，主要用于在Jenkins构建服务器上发布Cucumber报告。
* [Java TestNG](https://github.com/reportportal/agent-java-testNG)：将结果上传到ReportPortal服务器的TestNG报告器。
* [Spock Reports](https://github.com/renatoathaydes/spock-reports)：该项目是Spock的全局扩展，用于创建测试报告。

#### 多线程测试

* [Awaitility](https://github.com/awaitility/awaitility)：Awaitility是一种DSL，允许你以简洁且易于阅读的方式表达对异步系统的期望。
* [Lincheck](https://github.com/JetBrains/lincheck)：Lincheck是一个实用且用户友好的框架，用于在JVM上测试并发算法，由JetBrains开源。
* [Vmlens](https://github.com/vmlens/vmlens)：Vmlens使在JVM上对多线程应用程序进行单元测试变得容易。
* [Thread Weaver](https://github.com/google/thread-weaver)：Weaver是一个用于测试多线程代码的Java框架，由Google开源。
* [JCStress](https://github.com/openjdk/jcstress)：JCStress是实验性工具和一套测试，用于帮助研究JVM、类库和硬件中并发支持的正确性，由Oracle开源。
* [MultithreadedTC](https://code.google.com/archive/p/multithreadedtc/)：MultithreadedTC是用于测试并发Java应用程序的框架，由Google开源。
* [ConcurrentUnit](https://github.com/jhalterman/concurrentunit)：ConcurrentUnit的创建是为了帮助开发人员测试多线程或异步代码。
* [Tempus Fugit](https://github.com/tobyweston/tempus-fugit)：用于编写和测试并发代码的小型库。
* [Concutest](https://www.concutest.org/)：Concutest是一套工具，旨在使并发Java程序的开发和测试更加轻松可靠，由莱斯大学开源。
* [Threads Collider](https://github.com/stawirej/threads-collider)：Threads Collider尝试在“完全相同”的时刻对多个线程执行所需的操作，以增加出现由竞争条件或死锁引起的问题的几率。
* [VerCors](https://github.com/utwente-fmt/vercors)：VerCors是一个用于验证并发和并行程序的工具集，由特文特大学开源。
* [ThreadPoster](https://github.com/techyourchance/thread-poster)：用于单元测试和富有表现力的多线程的轻量级库。

#### JUnit扩展

* [HiveRunner](https://github.com/HiveRunner/HiveRunner)：HiveRunner是基于JUnit 4和5的Hive查询开源单元测试框架。
* [ReRunner](https://github.com/artsok/rerunner-jupiter)：ReRunner是JUnit 5的扩展，可以立即重新运行失败的JUnit 5测试。
* [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer)：JUnit Pioneer为JUnit 5及其Jupiter API提供扩展。
* [JUnitParams](https://github.com/Pragmatists/JUnitParams)：JUnit 4的参数化测试扩展。
* [System Rules](https://github.com/stefanbirkner/system-rules)：System Rules是用于测试使用java.lang.System的代码的JUnit Rule集合。
* [System Lambda](https://github.com/stefanbirkner/system-lambda)：System Lambda是用于测试使用java.lang.System的代码的函数集合。
* [System Stubs](https://github.com/webcompere/system-stubs)：System Stubs用于测试依赖于java.lang.System中方法的代码。
* [JUnit5 System Exit](https://github.com/tginsberg/junit5-system-exit)：此JUnit 5扩展可帮助你为调用System.exit()的代码编写测试。
* [NoSQLUnit](https://github.com/lordofthejars/nosql-unit)：NoSQLUnit是一个JUnit扩展，可以更轻松地编写使用NoSQL后端的系统的单元和集成测试。
* [TagUnit](https://tagunit.sourceforge.net/)：TagUnit是一个用于测试JSP页面中的自定义标签的标签库。
* [JSPUnit](https://sourceforge.net/projects/jspunit/)：JSPUnit是JUnit的扩展，用于对JSP进行单元测试。
* [JSFUnit](https://jsfunit.jboss.org/)：JSFUnit是JSF应用程序的测试框架，由JBoss社区维护。
* [Docker Compose JUnit Rule](https://github.com/palantir/docker-compose-rule)：这是一个用于执行与Docker Compose托管容器交互的JUnit测试的库，由Palantir开源。
* [JUnit 5 FormattedSource](https://github.com/mikemybytes/junit5-formatted-source)：该库可以通过编写参数化测试的新方法对JUnit 5进行扩展。
* [TestParameterInjector](https://github.com/google/TestParameterInjector)：TestParameterInjector是JUnit 4和JUnit 5测试运行程序，它针对字段/参数值的不同组合运行其测试方法，由Google开源。
* [JGotesting](https://github.com/tastapod/jgotesting)：JGotesting是受Go测试包启发的JUnit兼容测试工具。
* [RandomizedTesting](https://github.com/randomizedtesting/randomizedtesting)：适用于JUnit、ANT和Maven的随机测试基础设施。
* [Kafka JUnit](https://github.com/charithe/kafka-junit)：Kafka JUnit提供了在测试期间启动和关闭Kafka 代理的工具程序。
* [Chronicle Test Framework](https://github.com/OpenHFT/Chronicle-Test-Framework)：该库提供了用于编写JUnit测试的支持类，支持JUnit 4和JUnit 5。
* [Loom-Unit](https://github.com/cescoffier/loom-unit)：用于检查虚拟线程是否固定载体线程的JUnit 5扩展。
* [JUnit Toolbox](https://github.com/MichaelTamm/junit-toolbox)：使用JUnit 4编写自动化测试的有用类。
* [Weld Testing](https://github.com/weld/weld-testing)：该项目的主要目标是为CDI单元/组件测试提供简单快速的工具，这些工具作为JUnit 4、JUnit 5和Spock扩展实现。
* [CDI-Unit](https://github.com/cdi-unit/cdi-unit)：CDI应用程序的单元测试库，支持Mockito来Mock依赖项。
* [Kafka JUnit](https://github.com/mguenther/kafka-junit)：Kafka JUnit使开发人员能够在JUnit测试中启动和停止由Kafka代理和分布式Kafka Connect Workers组成的完整Kafka集群。
* [JUnit JSON Params](https://github.com/joshka/junit-json-params)：一个JUnit 5库，提供在参数化测试中从JSON字符串或文件加载数据的注解。
* [FakeTime](https://github.com/faketime-java/faketime)：FakeTime使用原生Java代理将System.currentTimeMillis()实现替换为你可以使用系统属性控制的实现。

#### 其他测试库

* [JsonUnit](https://github.com/lukas-krecan/JsonUnit)：JsonUnit是一个简化测试中JSON比较的库。
* [EqualsVerifier](https://github.com/jqno/equalsverifier)：EqualsVerifier可用于Java单元测试，以验证类中equals和hashCode方法的约定是否得到满足。
* [OpenTest4J](https://github.com/ota4j-team/opentest4j)：该项目是JUnit 5团队倡议的成果。
* [HtmlUnit](https://github.com/HtmlUnit/htmlunit)：HtmlUnit是Java程序的无GUI浏览器。
* [Apache Commons Testing](https://github.com/apache/commons-testing)：用于测试的Java实用程序类包。
* [MUnit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。
* [NonDex](https://github.com/TestingResearchIllinois/NonDex)：NonDex是一个用于检测和调试对未确定的Java API的错误假设的工具，由伊利诺伊大学开源。
* [XmlUnit](https://github.com/xmlunit/xmlunit)：XMLUnit是一个支持以多种方式测试XML输出的库。
* [LogCaptor](https://github.com/Hakky54/log-captor)：LogCaptor是一个能够轻松捕获用于单元和集成测试目的的日志记录条目的库。
* [ConsoleCaptor](https://github.com/Hakky54/console-captor)：ConsoleCaptor是一个可让你轻松捕获控制台的输出以进行单元测试的库。
* [SikuliRobot](https://github.com/rainmanwy/robotframework-SikuliLibrary)：Sikuli机器人框架库为Robot Framework提供关键字，可以通过Sikuli测试UI。
* [Spring Addons](https://github.com/ch4mpy/spring-addons)：提供OAuth2资源服务器配置和测试的库。
* [Tzatziki](https://github.com/Decathlon/tzatziki)：该项目是一组现成的Cucumber步骤的集合，通过专注于由外向内的测试策略，可以轻松实现TDD Java微服务，由迪卡侬开源。
* [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector)：Mutability Detector旨在分析Java类并报告给定类的实例是否不可变。
* [OpenPojo](https://github.com/OpenPojo/openpojo)：用于简化POJO测试的库。
* [POJO-TESTER](https://github.com/sta-szek/pojo-tester)：POJO-TESTER是一个Java测试库，可以使POJO测试变得更加容易。
* [StackSrc](https://github.com/laech/java-stacksrc)：该项目的目标是修饰测试失败的堆栈跟踪，使其更有用。
* [Overcast](https://github.com/xebialabs/overcast)：用于针对云中的主机编写测试的Java工具类。
* [SQL Logic Test](https://github.com/hydromatic/sql-logic-test)：SQL Logic Test是一套包含超过700万个测试的套件，用于测试SQL的核心方面。
* [Specnaz](https://github.com/skinny85/specnaz)：用于用Java、Kotlin和Groovy编写漂亮的RSpec/Jasmine/Mocha/Jest风格规范的库。
* [Hsac-Fitnesse-Fixtures](https://github.com/fhoeben/hsac-fitnesse-fixtures)：该项目通过提供定义和运行测试的应用程序来协助测试Web Services和Web应用程序。
* [Courgette-JVM](https://github.com/prashant-ramcharan/courgette-jvm)：Courgette-JVM是Cucumber的扩展，增加了在功能级别或场景级别并行运行Cucumber测试的功能。
* [Oleaster](https://github.com/mscharhag/oleaster)：Oleaster允许你像编写Jasmine测试一样编写JUnit测试。
* [Freud](https://github.com/LMAX-Exchange/freud)：用于编写静态分析测试的框架，由英国外汇交易公司LMAX开发。
* [EasyTest](https://github.com/EaseTech/easytest-core)：EasyTest是一个用于在Java中执行数据驱动测试的库。
* [Karibu-Testing](https://github.com/mvysny/karibu-testing)：Vaadin服务器端无浏览器无容器单元测试。
* [SocketTest](https://github.com/akshath/SocketTest)：一个用于套接字测试的Java工具，它可用于测试任何使用TCP或UDP协议进行通信的服务器或客户端。
* [Component Test Framework](https://github.com/lydtechconsulting/component-test-framework)：允许对Spring Boot应用程序进行组件测试的库。
* [Skippy](https://github.com/skippy-io/skippy)：Skippy是JVM的测试影响分析和预测测试选择框架。
* [Taikai](https://github.com/enofex/taikai)：Taikai通过提供针对各种技术定制的一整套预定义规则来扩展流行的ArchUnit库的功能。

#### 测试套件

* [YCSB](https://github.com/brianfrankcooper/YCSB)：Yahoo云服务基准测试套件。
* [HiBench](https://github.com/Intel-bigdata/HiBench)：HiBench是一个大数据基准测试套件，可帮助评估不同大数据框架的速度、吞吐量和系统资源利用率，由Intel开源。
* [NDBench](https://github.com/Netflix/ndbench)：NDBench是一种可插拔的支持云的基准测试工具，可在任何数据存储系统中使用，由Netflix开源。
* [COSBench](https://github.com/intel-cloud/cosbench)：COSBench是一款用于衡量云对象存储服务性能的基准测试工具，由Intel开源。
* [BenchBase](https://github.com/cmu-db/benchbase)：BenchBase是一个通过JDBC的多DBMS SQL基准测试框架，由CMU开源。
* [LinkBench](https://github.com/facebookarchive/linkbench)：LinkBench是一个数据库基准测试，旨在评估类似于Facebook生产MySQL部署的工作负载的数据库性能。
* [Theodolite](https://github.com/cau-se/theodolite)：Theodolite是一个用于对Kubernetes中云原生应用程序的水平和垂直可扩展性进行基准测试的框架，由基尔大学开源。
* [Ant AST Benchmark](https://github.com/alipay/ant-application-security-testing-benchmark)：由蚂蚁安全团队联合浙江大学网络空间安全学院共同设计的xAST评价体系及其测试样本套件Benchmark。
* [Nexmark](https://github.com/nexmark/nexmark)：Nexmark是用于连续数据流查询的基准套件。
* [Spark Bench](https://github.com/CODAIT/spark-bench)：Apache Spark基准测试套件，IBM开源。
* [NoSQLBench](https://github.com/nosqlbench/nosqlbench)：NoSQLBench是一款针对NoSQL生态系统的严谨性能测试工具，由DataStax开源。
* [Industrial Benchmark](https://github.com/siemens/industrialbenchmark)：Industrial Benchmark是离线强化学习和在线强化学习的现实基准，用于寻找最适合实际应用的强化学习算法，由Siemens开源。
* [DaCapo Benchmark](https://github.com/dacapobench/dacapobench)：此基准测试套件旨在作为编程语言、内存管理和计算机架构社区对Java进行基准测试的工具，澳大利亚国立大学开源。
* [BenchmarkSQL](https://github.com/pingcap/benchmarksql)：BenchmarkSQL是一个易于使用的JDBC基准测试，由PingCAP维护。

## 代码覆盖率

* [JaCoCo](https://github.com/jacoco/jacoco)：JaCoCo是一个免费的Java代码覆盖率库。
* [Super JaCoCo](https://github.com/didi/super-jacoco)：Super-JaCoCo基于JaCoCo、Git二次开发打造的一站式Java代码全量/diff覆盖率收集平台，能够低成本、无侵入的收集代码覆盖率数据，由滴滴开源。
* [Kover](https://github.com/Kotlin/kotlinx-kover)：Kover是一组用于收集为JVM和Android平台编译的Kotlin代码的测试覆盖率的解决方案，由JetBrains开发。
* [Clover](https://bitbucket.org/atlassian/clover)：Atlassian开源的Java和Groovy代码覆盖率工具。
* [Cobertura](https://github.com/cobertura/cobertura)：Cobertura是一个免费的Java代码覆盖率报告工具。
* [JSCover](https://github.com/tntim96/JSCover)：JSCover是一个易于使用的JavaScript代码覆盖率测量工具。
* [EMMA](https://emma.sourceforge.net/)：EMMA是一个用于测量和报告Java代码覆盖率的开源工具包。
* [Codecov](https://about.codecov.io/)：Codecov是适用于任何测试套件的一体化代码覆盖率报告解决方案。
* [JCov](https://github.com/openjdk/jcov)：JCov开源项目用于收集与测试套件的生产相关的质量指标，Oracle开源。
* [Parasoft JTest](https://www.parasoft.com/)：包括多种现代QA工具，允许测量代码覆盖率，并对其进行静态和动态分析，这是一款商业工具。
* [OpenClover](https://github.com/openclover/clover)：OpenClover测量Java和Groovy的代码覆盖率并收集20多个代码指标。

## 构建工具

* [Apache Maven](https://github.com/apache/maven)：Maven是一个软件项目管理和理解工具。
* [Gradle](https://github.com/gradle/gradle)：Gradle是一个构建工具，专注于构建自动化并支持多语言开发。
* [Bazel](https://github.com/bazelbuild/bazel)：Bazel是一个快速、多语言且可扩展的构建系统，由Google开发。
* [SBT](https://github.com/sbt/sbt)：SBT是一个适用于Scala、Java的构建工具。
* [Leiningen](https://github.com/technomancy/leiningen)：Leiningen是一种构建自动化和依赖管理工具，用于以Clojure编程语言编写的软件项目的简单配置。
* [Apache Ant](https://github.com/apache/ant)：Ant是一个基于Java的构建工具。
* [Buck](https://github.com/facebook/buck)：Buck是一个快速构建系统，鼓励在各种平台和语言上创建小型、可重用的模块，由Facebook开发。
* [Mill](https://github.com/com-lihaoyi/mill)：Mill是一个现代化的构建工具，支持Scala和Java项目的构建和管理。
* [Pants](https://github.com/pantsbuild/pants)：Pants是一个快速、可扩展、用户友好的构建系统，适用于各种规模的代码库，由Twitter开源。
* [1JPM](https://github.com/Osiris-Team/1JPM)：1JPM是一种Maven/Gradle替代方案，但有所不同，它本身是一个Java文件，你应该编辑该文件来配置你的项目。
* [Apache Maven Daemon](https://github.com/apache/maven-mvnd)：Mvnd是Maven团队借鉴了Gradle和Takari后衍生出的更快的构建工具。
* [Boot](https://github.com/boot-clj/boot)：Boot是一个Clojure构建框架和临时Clojure脚本评估器。
* [JeKa](https://github.com/jeka-dev/jeka)：JeKa是一个Java构建工具，用于直接从源代码构建或执行Java应用程序和脚本。
* [Amper](https://github.com/JetBrains/amper)：Amper是一个项目配置工具，其目标是改善项目配置体验和工具性，即IDE内部的支持，同时还提供流畅的开箱即用体验，由JetBrains开源。
* [BLD](https://github.com/rife2/bld)：BLD是一个新的构建系统，允许你用纯Java编写构建逻辑。
* [Pro](https://github.com/forax/pro)：Pro是与Java 9模块无缝协作的Java构建工具。
* [Fury](https://github.com/propensive/fury-old)：Fury是下一代构建工具，以解决在不断变化的环境中构建软件的最大挑战，同时保持构建的可预测性、可靠性和简单性。
* [Savant](https://github.com/savant-build/savant-core)：Savant是一个用Java编写的构建工具，它使用Groovy DSL来构建文件，由Inversoft公司开源。
* [Saker.build](https://github.com/sakerbuild/saker.build)：Saker.build是一个与语言无关的构建系统，专注于可扩展性和可扩展的增量构建。

## 包管理器

* [Nuts](https://github.com/thevpc/nuts)：Nuts是一个Java包管理器，可帮助以简单直接的方式发现、下载、组装和执行本地和远程工件(包)。
* [Nix](https://github.com/fzakaria/mvn2nix)：Nix包管理器用于轻松打包Maven Java应用程序。
* [JPM4j](https://github.com/jpm4j)：JPM是Java包管理器，可以在JPM的帮助下轻松安装应用程序和库。

## CI/CD

* [Jenkins](https://github.com/jenkinsci/jenkins)：Jenkins是领先的开源自动化服务器，使用Java构建，提供超过2000个插件来支持几乎所有事情的自动化。
* [CircleCI](https://circleci.com/)：CircleCI是一个持续集成和持续交付平台，可用于实施DevOps实践。
* [TeamCity](https://www.jetbrains.com/teamcity/)：TeamCity是一个通用CI/CD软件平台，可实现灵活的工作流程、协作和开发实践，这是JetBrains的商业产品。
* [Bamboo](https://www.atlassian.com/software/bamboo)：Bamboo是一款持续集成构建服务器软件，Atlassian提供的商业软件，也有免费版本。
* [GoCD](https://github.com/gocd/gocd)：GoCD可帮助你自动化和简化构建-测试-发布周期，从而无忧、持续地交付产品，由ThoughtWork开源。
* [OneDev](https://github.com/theonedev/onedev)：OneDev是一个具有CI/CD、看板的自托管Git服务器。
* [FlowCI](https://github.com/FlowCI/flow-core-x)：FlowCI是一个开源CI/CD自动化服务器，旨在以最简单、最快、最轻松的方式建立自托管CI/CD服务。
* [BK CI](https://github.com/TencentBlueKing/bk-ci)：BlueKing是一个免费并开源的CI服务，可助你自动化构建-测试-发布工作流，持续、快速、高质量地交付你的产品，由腾讯开源。
* [Hudson](https://github.com/hudson/hudson-2.x)：Hudson是用Java编写的一个持续集成工具，由Sun开源。
* [Apache Continuum](https://continuum.apache.org/)：Continuum是一款企业级持续集成服务器，具有自动构建、发布管理、基于角色的安全性以及与流行构建工具和源代码控制管理系统的集成等功能。
* [Harness CD Community Edition](https://github.com/harness/harness-core)：Harness CD是一种现代自助式持续交付解决方案，允许开发人员在他们选择的任何公共或私有云基础设施上部署、验证和自动回滚Kubernetes和其他云原生应用程序。
* [Bob](https://github.com/bob-cd/bob)：Bob允许你构建自己的自定义CI/CD基础设施，从而允许你将Bob用于各种不同的目的。
* [CruiseControl](https://cruisecontrol.sourceforge.net/)：CruiseControl既是一个持续集成工具，也是一个用于创建自定义持续构建流程的可扩展框架，由ThoughtWorks开源。

## 工件仓库

* [Maven Central](https://central.sonatype.com/)：Maven Central是JVM语言最大的开源组件仓库。
* [JitPack](https://github.com/jitpack/jitpack.io)：JitPack是一个新颖的JVM和Android项目包仓库。
* [Artifactory](https://jfrog.com/artifactory/)：Artifactory是用于容纳和管理整个软件供应链中使用的所有工件、二进制文件、包、文件、容器和组件的单一解决方案。
* [Sonatype Nexus](https://github.com/sonatype/nexus-public)：Sonatype Nexus是一个由Sonatype开发的仓库管理工具，用于管理和托管各种软件构件。
* [Bintray](https://github.com/bintray)：Bintray是一个软件包分发平台，它提供了存储、发布和分发软件包的功能。
* [Indy](https://github.com/Commonjava/indy)：Indy是一个简单的仓库管理器，适用于Maven和其他使用Maven仓库格式的构建工具。
* [Artipie](https://github.com/artipie/artipie)：Artipie是一个二进制工件管理工具，类似于Artifactory、Nexus、Archiva、ProGet等。
* [BK Repo](https://github.com/Tencentblueking/bk-repo)：BK Repo是一个基于微服务架构设计的制品管理平台，由腾讯开源。
* [Cloudsmith](https://cloudsmith.io/)：完全托管的包管理SaaS，支持Maven/Gradle/SBT，并提供免费套餐。
* [Apache Archiva](https://github.com/apache/archiva)：Archiva是一个功能丰富的仓库管理器。
* [Strongbox](https://github.com/strongbox/strongbox)：Strongbox是一个现代OSS工件仓库管理器。
* [Reposilite](https://github.com/dzikoysk/reposilite)：Reposilite是Maven工件的轻量级仓库管理器，这是一个替代Nexus、Archiva或Artifactory等管理器的简单解决方案。
* [CloudRepo](https://cloudrepo.io/)：CloudRepo是管理、共享和分发私有Maven和Python仓库的简单选项。
* [PackageCloud](https://packagecloud.io)：Packagecloud为你的软件工件提供了一个统一、开发人员友好的包管理平台。
* [Repsy](https://repsy.io/)：Repsy是下一代通用包仓库。
* [Gemfury](https://gemfury.com/)：Gemfury是一项用于安全存储和部署代码包的托管服务。

## 静态分析

* [Checkstyle](https://github.com/checkstyle/checkstyle)：Checkstyle是一个用于检查Java源代码是否符合代码标准或验证规则集的工具。
* [Infer](https://github.com/facebook/infer)：Infer是一个针对Java、C++、Objective-C和C的静态分析工具，用OCaml编写，由Facebook开源。
* [Error Prone](https://github.com/google/error-prone)：Error Prone是一个Java静态分析工具，可以在编译时捕获常见的编程错误，由Google开源。
* [PMD](https://github.com/pmd/pmd)：PMD是一个源码分析器，它可以发现常见的编程缺陷，例如未使用的变量、空的catch块、不必要的对象创建等。
* [CodeQL](https://github.com/github/codeql)：CodeQL是GitHub开发的代码分析引擎，用于自动执行安全检查。
* [Qodana](https://www.jetbrains.com/qodana)：Qodana是JetBrains推出的代码质量检测工具。
* [SpotBugs](https://github.com/spotbugs/spotbugs)：SpotBugs是一种静态分析工具，用于查找Java代码中的错误。
* [Nullsafe](https://engineering.fb.com/2022/11/22/developer-tools/meta-java-nullsafe)：Nullsafe是一个静态分析工具，Meta使用它来检测Java代码中的NPE错误。
* [SonarJava](https://github.com/SonarSource/sonar-java)：用于Java代码质量和安全性的SonarSource静态分析器。
* [Spoon](https://github.com/INRIA/spoon)：Spoon是一个用于分析、重写、转换、转译Java源代码的开源库，由法国国家数字科学与技术研究所开源。
* [Detekt](https://github.com/detekt/detekt)：Detekt是一款适用于Kotlin编程语言的静态代码分析工具。
* [FindBugs](https://github.com/findbugsproject/findbugs)：FindBugs是一个使用静态分析来查找Java代码中的错误的程序，由马里兰大学开源。
* [DesigniteJava](https://github.com/tushartushar/DesigniteJava)：DesigniteJava是一个针对Java的代码质量评估工具。
* [jQAssistant](https://github.com/jQAssistant/jqassistant)：jQAssistant是一个开源工具，可帮助你分析和控制软件系统的质量。
* [Scavenger](https://github.com/naver/scavenger)：由Naver开源的运行时死代码分析工具。
* [WalkMod](https://github.com/walkmod/walkmod-core)：WalkMod是一个开源工具，通过自动快速修复编码风格问题来共享和应用代码约定。
* [Codekvast](https://github.com/crispab/codekvast)：Codekvast检测Java应用程序中的真正死代码。
* [TABBY](https://github.com/wh1t3p1g/tabby)：TABBY是一款针对Java语言的静态代码分析工具。
* [Kythe](https://github.com/kythe/kythe)：Kythe是一个可插拔、与语言无关的生态系统，用于构建与代码一起使用的工具，Google开源。
* [Semgrep](https://github.com/semgrep/semgrep)：Semgrep是一种快速、开源、静态分析工具，用于在编辑期、提交和CI时搜索代码、查找错误并强制执行代码标准。
* [CodeFuse-Query](https://github.com/codefuse-ai/CodeFuse-Query)：CodeFuse-Query是一种强大的静态代码分析平台，适合大规模、复杂的代码库分析场景，由蚂蚁CodeFuse团队开发。
* [Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs)：Find Security Bugs是用于Java Web应用程序安全审核的SpotBugs插件，由OWASP开源。
* [Tai-e](https://github.com/pascal-lab/Tai-e)：Tai-e是一个易于学习/使用的Java静态分析框架，由南京大学开源。
* [NullAway](https://github.com/uber/NullAway)：NullAway是一个帮助消除Java代码中的NPE的工具，由Uber开源。
* [CodeCompass](https://github.com/Ericsson/CodeCompass)：CodeCompass是一个用C/C++和Java编写的大型软件的软件理解工具，由爱立信开源。
* [JPlag](https://github.com/jplag/JPlag)：JPlag查找一组多个程序之间的成对相似性，它可以可靠地检测软件开发中的软件抄袭和共谋行为(即使是在混淆的情况下)，由卡尔斯鲁厄理工学院开源。
* [Eclipse Steady](https://github.com/eclipse/steady)：Steady分析你的Java应用程序是否存在已知漏洞的开源依赖，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性，由SAP开源。
* [Checker Framework](https://github.com/typetools/checker-framework)：Checker Framework增强了Java的类型系统，这使得软件开发人员能够检测并防止其Java程序中的错误，由华盛顿大学开源。
* [MobsfScan](https://github.com/MobSF/mobsfscan)：MobsfScan是一个静态分析工具，可以在Android和IOS源代码中查找不安全的代码模式。
* [CK](https://github.com/mauricioaniche/ck)：CK通过静态分析的方式(即不需要编译代码)计算Java项目中的类级和方法级代码度量。
* [LiSA](https://github.com/lisa-analyzer/lisa)：LiSA旨在简化基于抽象解释理论的静态分析器的创建和实现，由威尼斯大学开源。
* [JSpecify](https://github.com/jspecify/jspecify)：JSpecify是一个由明确指定的注解组成的工件，用于支持静态分析检查和JVM语言互操作，由Google领导。
* [FlowDroid](https://github.com/secure-software-engineering/FlowDroid)：FlowDroid静态计算Android应用程序和Java程序中的数据流，由帕德博恩大学开源。
* [OWASP Orizon](https://github.com/thesp0nge/owasp-orizon)：OWASP Orizon是一个源代码静态分析工具，旨在发现Java应用程序中的安全问题。
* [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)：识别并优先考虑Java代码库中你应该首先重构的上帝类和高度耦合类。
* [Qulice](https://github.com/yegor256/qulice)：Qulice是Java项目的静态分析质量控制工具，它结合了所有最好的静态分析工具并对其进行了预先配置，包括Checkstyle和PMD。
* [jPeek](https://github.com/cqfn/jpeek)：jPeek是Java代码指标的静态收集器。
* [Forbidden API](https://github.com/policeman-tools/forbidden-apis)：允许解析Java字节码以查找方法/类/字段签名的调用并失败构建。
* [WALA](https://github.com/wala/WALA)：WALA为Java字节码和相关语言以及JavaScript提供静态分析功能，由IBM开源。
* [Ultimate](https://github.com/ultimate-pa/ultimate)：Ultimate是一个程序分析框架，可执行程序分析的步骤，例如解析源代码、将程序从一种表示转换为另一种表示或分析程序，由弗莱堡大学开源。
* [Qilin](https://github.com/QilinPTA/Qilin)：Qilin是一个完全命令式的Java指针分析框架。
* [Code Asset](https://github.com/nidi3/code-assert)：断言项目的源代码满足某些规则。
* [Joern](https://github.com/joernio/joern)：Joern是一个用于分析源代码、字节码和二进制可执行文件的平台，由ShiftLeft开源。
* [Tailor](https://github.com/sleekbyte/tailor)：Tailor是一款跨平台静态分析和lint工具，用于使用Apple Swift编程语言编写的源代码。
* [JayHorn](https://github.com/jayhorn/jayhorn)：JayHorn是Java的软件模型检查工具。
* [CoraxJava](https://github.com/Feysh-Group/corax-community)：CoraxJava是一款针对Java项目的静态代码安全分析工具，由蜚语科技开源。
* [SootUp](https://github.com/soot-oss/SootUp)：SootUp是对优秀的旧静态分析框架Soot的彻底改造，由帕德博恩大学安全软件工程组开源。
* [Violations Lib](https://github.com/tomasbjerre/violations-lib)：这是一个用于解析报告文件(如静态代码分析)的Java库。
* [CPAchecker](https://github.com/sosy-lab/cpachecker)：CPAchecker是一个用于可配置软件验证的工具，由德国慕尼黑大学开源。
* [Codemodder](https://github.com/pixee/codemodder-java)：Codemodder是一个用于构建富有表现力的codemod的可插拔框架。
* [CodeScene](https://codescene.com/)：CodeScene是CodeScene AB开发的行为代码分析工具。
* [ConQAT](https://teamscale.com/)：ConQAT被设计为用于快速开发和执行软件质量分析的工具包，由慕尼黑工业大学开源。
* [JArchitect](https://www.jarchitect.com/)：JArchitect是用于Java代码的静态分析工具。
* [Snyk Code](https://snyk.io/product/snyk-code/)：使用由开发人员和为开发人员构建的静态应用程序安全测试，确保代码编写时的安全。
* [Squale](https://www.squale.org/)：Squale是一个质量测量平台，可以分析多语言软件应用程序，由雪铁龙、法国航空等组织开源。
* [CFLint](https://github.com/cflint/CFLint)：CFLint是CFML的静态代码分析工具。
* [Codyze](https://github.com/Fraunhofer-AISEC/codyze)：Codyze是一个基于代码属性图的Java、C、C++静态分析器，由弗劳恩霍夫应用与综合安全研究所开源。
* [Sonargraph](https://www.hello2morrow.com/products/sonargraph/explorer)：Sonargraph是一款免费的简单静态分析工具，专注于指标、周期组检测和简单的依赖分析。
* [AppMap](https://github.com/getappmap/appmap-java)：AppMap是一款多功能开源运行时代码分析工具。
* [Codety Scanner](https://github.com/codetyio/codety-scanner)：Codety Scanner是一款全面的代码扫描器，旨在检测30多种编程语言和IaC框架的代码问题，由Codety开源。
* [LitterBox](https://github.com/se2p/LitterBox)：LitterBox是一个用于检测Scratch项目中错误的静态代码分析工具，由德国帕绍大学开源。
* [TAJS](https://github.com/cs-au-dk/TAJS)：TAJS是一种JavaScript数据流分析，可以推断类型信息和调用图，由奥胡斯大学开源。
* [TIP](https://github.com/cs-au-dk/TIP)：TIP是一种小型命令式编程语言，旨在教授静态程序分析的基本概念，由奥胡斯大学开源。
* [ChanZi](https://github.com/Chanzi-keji/chanzi)：铲子是一款简单易用的Java SAST(静态应用程序安全测试)工具
* [Coverity](https://scan.coverity.com/)：Coverity是一种静态应用程序安全测试(SAST)和问题管理工具，最初由美国国土安全部开发。

## Java环境管理

* [SDKMAN](https://github.com/sdkman/sdkman-cli)：SDKMAN是一个用于在任何基于Unix的系统上管理多个软件开发套件的并行版本的工具。
* [jEnv](https://github.com/jenv/jenv)：Java环境管理器。
* [jEnv](https://github.com/linux-china/jenv)：jEnv是一个用于在任何系统(例如Linux、Mac和Windows)上管理Java开发套件并行版本的工具。
* [JC jEnv](https://github.com/chroblert/JC-jEnv)：Java版本切换工具，可以很方便的在Java的多个版本之间切换。
* [JEnv Windows](https://github.com/FelixSelter/JEnv-for-Windows)：只需一行命令即可更改当前的Java版本。
* [Jabba](https://github.com/shyiko/jabba)：Java版本管理工具，由Go语言开发。
* [IDE](https://github.com/devonfw/ide)：该工具旨在帮助开发人员设置开发环境，并能够在整个团队中共享相同的项目设置。
* [JVMS](https://github.com/ystyle/jvms)：适用于Windows的JDK版本管理器。

## JDK

* [Oracle OpenJDK](https://github.com/openjdk/jdk)：Oracle开源的OpenJDK官方版本。
* [Amazon Corretto](https://github.com/corretto/corretto-8)：Amazon Corretto是OpenJDK的免费、多平台、生产就绪发行版。
* [Eclipse Temurin](https://github.com/adoptium/temurin-build)：Eclipse基金会下的JDK版本，由Adoptium工作组开源。
* [BellSoft Liberica](https://github.com/bell-sw/Liberica)：BellSoft开源的JDK版本。
* [GraalVM](https://github.com/oracle/graal)：GraalVM是Oracle开源的一个高性能JDK发行版，可提前将Java应用程序编译成独立的二进制文件。
* [Microsoft JDK](https://github.com/microsoft/openjdk)：由微软开源的新的JDK免费长期支持发行版。
* [Azul Zulu](https://www.azul.com/zh-hans/core/)：Azul开源的JDK版本。
* [IBM Semeru](https://www.ibm.com/support/pages/java-sdk-downloads)：IBM开源的JDK版本，基于OpenJ9构建。
* [RedHat JDK](https://developers.redhat.com/products/openjdk/download)：RedHat版本的OpenJDK是Java SE的开源实现。
* [JetBrains Runtime](https://github.com/JetBrains/JetBrainsRuntime)：JetBrains开发的基于OpenJDK的运行时环境。
* [OpenLogic](https://www.openlogic.com/openjdk-downloads)：Perforce公司开源的OpenLogic为Linux、Windows和MacOS提供免费的OpenJDK 8、11、17和21季度版本。
* [VMS OpenJDK](https://vmssoftware.com/products/openjdk/)：VMS软件公司的OpenJDK免费开源实现。
* [SapMachine](https://github.com/SAP/SapMachine)：SapMachine是SAP维护的OpenJDK的一个发行版。
* [Alibaba Dragonwell](https://github.com/dragonwell-project/dragonwell8)：阿里开源的JDK版本。
* [Tencent Kona](https://github.com/Tencent/TencentKona-17)：腾讯开源的JDK版本。
* [Huawei Bisheng](https://gitee.com/openeuler/bishengjdk-8)：华为开源的JDK版本，代号毕昇。
* [Loongson JDK](https://github.com/loongson/jdk)：龙芯中科基于OpenJDK研制并发布的龙芯平台Java环境。
* [RunSoon OpenJDK](https://www.digitalchina.com/product/details10.html)：神州数码提供的基于OpenJDK的企业级JVM版本。
* [坤泽JDK](https://www.primeton.com/products/jdk/)：坤泽JDK是基于OpenJDK进行信创适配与增强、一款高性能、可用于生产环境的商业发行版，由普元提供。

## JVM语言

* [Java](https://www.oracle.com/java/)：Java是一种采用面向对象范式的通用编程语言，由Oracle领导。
* [Groovy](https://github.com/apache/groovy)：Groovy是一种适用于JVM平台的强大的多方面编程语言。
* [kotlin](https://github.com/JetBrains/kotlin)：kotlin是一种开源静态类型编程语言，由JetBrains和开源贡献者支持和开发。
* [Scala](https://github.com/scala/scala)：Scala是一门多范式的编程语言，设计初衷是要集成面向对象编程和函数式编程的各种特性。
* [Clojure](https://github.com/clojure/clojure)：Clojure是一种动态的通用编程语言，它将脚本语言的易用性和交互式开发与高效、强大的多线程编程基础架构相结合。
* [Jython](https://github.com/jython/jython)：Jython是Python在Java中的实现。
* [JRuby](https://github.com/jruby/jruby)：JRuby是使用JVM的Ruby语言的实现。
* [DDlog](https://github.com/vmware/differential-datalog)：DDlog是一种用于增量计算的编程语言，它非常适合编写不断更新输出以响应输入变化的程序，由VMware开源。
* [Eta](https://github.com/typelead/eta)：Eta编程语言是Haskell的一种方言，运行在JVM上。
* [Lux](https://github.com/LuxLang/lux)：Lux编程语言是一个函数式、静态类型的Lisp，可以在多个平台上运行，例如JVM和JavaScript、Python、Lua或Ruby解释器。
* [Flix](https://github.com/flix/flix)：Flix是一种静态类型函数式、命令式和逻辑编程语言，由奥胡斯大学、滑铁卢大学开发。
* [Vale](https://github.com/ValeLang/Vale)：Vale是一种快速、安全且简单的编程语言。
* [Virgil](https://github.com/titzer/virgil)：Virgil是一种编程语言，旨在构建轻量级高性能系统，由卡内基梅隆大学开源。
* [Eclipse Golo](https://github.com/eclipse-archived/golo-lang)：Golo是一种用于JVM的简单动态弱类型语言，由法国CITI实验室开源。
* [Rascal](https://github.com/usethesource/rascal)：Rascal是一个开源、基于Java的元编程库，由荷兰阿姆斯特丹自由大学的UseTheSource团队开发。
* [JPHP](https://github.com/jphp-group/jphp)：JPHP是使用JVM的PHP的新实现，支持PHP语言(7.1+)的许多功能。
* [JGO](https://github.com/thomasmodeneis/jgo)：Golang的Java编译器和运行时环境。
* [LuaJ](https://github.com/luaj/luaj)：为JME和JSE编写的轻量级、快速、以Java为中心的Lua解释器。
* [Enkel](https://github.com/JakubDziworski/Enkel-JVM-language)：Enkel是一种运行在JVM上的简单编程语言。
* [Yeti](https://github.com/mth/yeti)：Yeti是ML风格的函数式编程语言，在JVM上运行。
* [Genesis](https://github.com/elonlit/Genesis)：Genesis是一种解释性、过程性和图灵完备的古希伯来编程语言。
* [AgentLang](https://github.com/agentlang-ai/agentlang)：AgentLang是一种开源编程语言和框架，用于在人工智能代理的帮助下解决复杂的任务，由Fractl开源。
* [Concurnas](https://github.com/Concurnas/Concurnas)：Concurnas是一种开源JVM编程语言，旨在构建可靠、可扩展、高性能的并发、分布式和并行系统。
* [Ioke](https://github.com/olabini/ioke)：Ioke是一种强类型、动态、基于原型的编程语言。
* [Fantom](https://github.com/fantom-lang/fantom)：Fantom是一种在JVM和现代Web浏览器上运行的可移植语言。
* [Eclipse Ceylon](https://github.com/eclipse-archived/ceylon)：Ceylon是一种用于Java和JavaScript虚拟机的现代、模块化、静态类型编程语言，由RedHat创建。
* [Frege](https://github.com/Frege/frege)：Frege是JVM的Haskell，它将纯函数式编程引入了Java平台。
* [Renjin](https://github.com/bedatadriven/renjin)：Renjin是基于JVM的R语言解释器。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种针对集成进行了优化的开源云原生编程语言，它由WSO2开发和支持。
* [BeanShell](https://github.com/beanshell/beanshell)：Beanshell是一个小型、免费、可嵌入的Java源解释器，具有对象脚本语言功能。
* [Erjang](https://github.com/trifork/erjang)：Erjang是基于JVM的Erlang VM。
* [Jolie](https://github.com/jolie/jolie)：Jolie是一种面向服务的编程语言，旨在为微服务的开发提供本机抽象。
* [EOLang](https://github.com/objectionary/eo)：EO是一种基于𝜑微积分的面向对象编程语言。
* [Lucee](https://github.com/lucee/Lucee)：Lucee是一种基于Java的动态标签和脚本语言，用于快速Web应用程序开发。
* [Gosu](https://github.com/gosu-lang/gosu-lang)：Gosu是一种实用的JVM编程语言。
* [Panda](https://github.com/panda-lang/panda)：Panda是一种清晰、时尚的JVM编程语言。
* [Jactl](https://github.com/jaccomoc/jactl)：Jactl是一种用于JVM平台的强大脚本语言，其语法是Java、Groovy和Perl的位组合。
* [Venice](https://github.com/jlangch/venice)：Venice是受Clojure启发的沙盒Lisp方言，具有出色的Java互操作性。
* [Ecstasy](https://github.com/xtclang/xvm)：Ecstasy是一种新的通用编程语言，专为现代云架构而设计，并且明确用于安全的无服务器云。
* [BoxLang](https://github.com/ortus-boxlang/BoxLang)：BoxLang是一种现代动态JVM语言，可以部署在多个运行时上。
* [Swift/T](https://github.com/swift-lang/swift-t)：Swift/T是一种隐式并行编程语言，用于将外部函数和命令行可执行文件组合成大规模并行应用程序，由芝加哥大学开源。
* [SARL](https://github.com/sarl/sarl)：SARL是一种通用的面向代理的语言，由皇家墨尔本理工大学开源。

## JVM实现

* [DCEVM](https://github.com/dcevm/dcevm)：DCEVM是Java HotSpot VM的修改版，允许在运行时无限地重新定义已加载的类，由约翰普勒林茨大学开源。
* [LeJOS](https://lejos.sourceforge.io/)：LeJOS是乐高Mindstorms EV3、NXT和RCX积木的替换固件，你可以使用Java对乐高机器人进行编程，使用LeJOS开发的机器人曾在国际空间站上运行。
* [Jikes RVM](https://github.com/JikesRVM/JikesRVM)：Jikes RVM提供了一个灵活的开放式测试平台，可以对虚拟机技术进行原型设计并尝试多种设计方案，曾经为虚拟机技术前沿研究超过180篇出版物和36篇论文。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：OpenJ9是适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化，由IBM开发。
* [Avian](https://github.com/ReadyTalk/avian)：Avian是一个轻量级虚拟机和类库，旨在提供有用的Java功能子集，适合构建独立的应用程序。
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)：ParparVM是Codename One开发的VM，用于取代最初构建它时已失效的XMLVM。
* [RoboVM](https://github.com/MobiVM/robovm)：RoboVM是Java字节码的提前编译器，针对Linux、Mac OS X和iOS，由Xamarin维护。
* [Maxine VM](https://github.com/beehive-lab/Maxine-VM)：Maxine VM是Java中的元循环虚拟机，由曼彻斯特大学高级处理器技术小组开发。
* [Rembulan](https://github.com/mjanicek/rembulan)：Rembulan是JVM的Lua 5.3实现，用纯Java编写，依赖性最小。
* [JOE](https://github.com/joekoolade/JOE)：JOE是一个软件虚拟化工具，它通过用Java语言编写操作系统和硬件子系统，将操作系统合并到程序中。
* [Node JVM](https://github.com/YaroslavGaponov/node-jvm)：Node JVM是纯Node.js实现的Java虚拟机。
* [Metascala](https://github.com/lihaoyi/Metascala)：Metascala是一个用Scala编程语言编写的小型元循环Java虚拟机。
* [Archimedes JVM](https://github.com/archimedes-projects/archimedes-jvm)：阿基米德对JVM的实现。
* [JamVM](https://jamvm.sourceforge.net/)：JamVM是一个开源Java虚拟机，旨在支持最新版本的JVM规范，同时又紧凑且易于理解。
* [Kaffe](https://github.com/kaffe/kaffe)：Kaffe是一个允许执行Java代码的虚拟机。
* [Mika VM](https://github.com/kifferltd/open-mika)：Mika VM是JVM规范的开源实现，以及实现Java ME连接设备配置的类库。
* [SableVM](http://sablevm.org/)：SableVM是一个健壮、极其便携、高效且符合规范的Java虚拟机，旨在易于维护和扩展，由麦吉尔大学开源。
* [TakaTuka](https://sourceforge.net/projects/takatuka/)：TakaTuka是一款开源、高度可移植的JVM，适用于微型嵌入式设备和无线传感器网络，由弗莱堡大学开源。
* [JamaicaVM](https://www.aicas.com/wp/products-services/jamaicavm/)：JamaicaVM是一个基于Java的嵌入式系统软件开发套件和运行时，它使智能设备和车辆成为可能，由Aicas公司开发。
* [Bck2Brwsr](https://github.com/jtulach/bck2brwsr)：Bck2Brwsr VM是一个Java虚拟机，它能够获取字节码并将其转换为执行相同操作的适当JavaScript代码。
* [CACAO](http://www.cacaojvm.org/)：CACAO是一个Java虚拟机，它使用JIT编译来本机执行Java方法。
* [HaikuVM](https://github.com/chuckb/haikuVM)：这是一个针对Arduino兼容微控制器的小型Java虚拟机。
* [Jamiga](http://os4depot.net/?function=showfile&file=development/language/jamiga.lha)：JAmiga是AmigaOS的Java虚拟机。
* [Jelatine JVM](https://jelatine.sourceforge.net/)：Jelatine是一种新的Java虚拟机，其目标是Java 2 Micro Edition Connected Limited Device Configuration(J2ME CLDC)。
* [Multi-OS Engine](https://github.com/multi-os-engine/multi-os-engine)：Multi-OS Engine提供Java运行时和与iOS平台API的Java接口，以开发具有原生LAF、原生性能以及Android应用程序中常见Java逻辑模块的可移植性的原生iOS应用程序。
* [SSVM](https://github.com/xxDark/SSVM)：运行在JVM上的Java VM。
* [Mini JVM](https://github.com/se-tuebingen/mini-jvm)：该项目用Java实现了一个简化的JVM，由图宾根大学开源。
* [IKVM](https://github.com/ikvmnet/ikvm)：IKVM是Microsoft .NET平台的Java实现。
* [JVM.Go](https://github.com/zxh0/jvm.go)：JVM.Go是一个用Go编写的玩具JVM。
* [DoppioJVM](https://github.com/plasma-umass/doppio)：Doppio是一个兼容POSIX的运行时系统以及一个用TypeScript编写的JVM，也是马萨诸塞大学PLASMA小组的一个活跃的研究项目。
* [RJVM](https://github.com/andreabergia/rjvm)：该项目是一个Rust编写的最小JVM 7。
* [Mini JVM](https://github.com/guxingke/mini-jvm)：使用Java 8实现的JVM。
* [Jacobin](https://github.com/platypusguy/jacobin)：Jacobin是Java 17 JVM规范的实现，它完全用Go编写。
* [BicaVM](https://github.com/nurv/BicaVM)：该项目是JVM在JavaScript中的实现。
* [PHPJava](https://github.com/php-java/php-java)：PHPJava是一个实验性库，它模拟JVM并通过PHP编译中间代码。
* [Jainja](https://jainja.thenesis.org/home)：Jainja是一个用Java编写的JVM。

## IDE

* [IntelliJ IDEA](https://github.com/JetBrains/intellij-community)：IntelliJ IDEA是领先的Java和Kotlin IDE，由JetBrains开发。
* [Eclipse](https://github.com/eclipse-platform)：Eclipse是一个开源、基于Java的可扩展开发平台，由IBM开发。
* [Visual Studio Code](https://code.visualstudio.com)：Visual Studio Code是Microsoft开源的一个轻量级但功能强大的源代码编辑器，也支持作为IDE开发Java。
* [Android Studio](https://developer.android.com/studio)：Android Studio是用于开发Android应用的Google官方IDE，基于Intellij引擎。
* [Apache NetBeans](https://github.com/apache/netbeans)：NetBeans是一个开源开发环境、工具平台和应用程序框架，最初由Oracle开发。
* [JetBrains Fleet](https://www.jetbrains.com/fleet)：Fleet是JetBrains公司推出的一款下一代集成开发环境，使用Kotlin开发。
* [MyEclipse](https://www.genuitec.com/products/myeclipse)：MyEclipse是一个基于Eclipse平台构建的专有Java IDE，由Genuitec软件公司提供。
* [Spring Tools](https://github.com/spring-projects/sts4)：Spring官方出品的基于Eclipse的Java IDE。
* [JDeveloper](https://www.oracle.com/application-development/technologies/jdeveloper.html)：Oracle JDeveloper是一个免费的集成开发环境，可简化基于Java的应用程序的开发。
* [DevEco Studio](https://developer.huawei.com/consumer/cn/deveco-studio/)：DevEco Studio基于IntelliJ IDEA开源版本打造，为运行在HarmonyOS系统上的应用和元服务提供一站式的开发平台，由华为开发。
* [JBoss Developer Studio](https://devstudio.jboss.com/updates/)：JBoss Developer Studio是由RedHat和Exadel创建并开发的IDE。
* [HBuilder](https://www.dcloud.io/)：HBuilder是DCloud推出的一款支持HTML 5的Web开发IDE，本身由Java编写。
* [BlueJ](https://github.com/k-pet-group/BlueJ-Greenfoot)：BlueJ是Java编程语言的IDE，主要用于教育目的，但也适合小规模软件开发，最初由莫纳什大学开源，目前由伦敦国王学院维护。
* [GigaIDE](https://gitverse.ru/features/gigaide/)：GigaIDE是由俄罗斯公司研发的免费Spring IDE，旨在为开发者提供高效的Spring应用开发体验。
* [JBuilder](https://borland-jbuilder.software.informer.com/)：JBuilder是Borland公司出品的Java集成编程环境，有不同功能程度的多个版本。
* [Consulo](https://github.com/consulo/consulo)：Consulo是一个多语言IDE，基于Intellij引擎。
* [Codenvy](https://github.com/codenvy/codenvy)：Codenvy是一个基于云的IDE，支持Java和许多其他语言，由RedHat维护。
* [RapidClipse](https://rapidclipse.com/)：RapidClipse是一个免费的Eclipse发行版，用于使用Java进行快速跨平台开发，由XDEV软件公司提供。
* [Greenfoot](https://www.greenfoot.org/home)：Greenfoot是使用Java或Stride的集成开发环境，主要用于高中和本科生的教育目的，由坎特伯雷肯特大学开源。
* [DrJava](http://www.drjava.org/)：DrJava是一款轻量级的Java编程语言IDE，主要面向初学者设计，由莱斯大学开源。
* [AIDE](https://www.android-ide.com/)：AIDE是一个Android/Java IDE，可以在Android手机上进行Android软件和游戏的开发，由Appfour提供。
* [TIDE](https://sourceforge.net/projects/tide)：TIDE是一个小巧但功能强大且齐全的开源Java IDE。
* [FDT](https://fdt.powerflasher.com/)：FDT是一个基于Eclipse的IDE，适用于交互式开发人员、自由职业者和机构，由Powerflasher开发。
* [Flash Builder](https://en.wikipedia.org/wiki/Adobe_Flash_Builder)：Adobe Flash Builder是基于Eclipse平台构建的IDE，可加速富互联网应用程序和跨平台桌面应用程序的开发。
* [RStudio](https://github.com/rstudio/rstudio)：RStudio是R编程语言的集成开发环境，由Posit软件公司开源。
* [Aptana Studio 3](https://github.com/aptana/studio3)：Aptana Studio 3是一个Web开发IDE，由Axway开源。
* [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE)：AndroidIDE是一款适用于Android开发的IDE。
* [Cosmic IDE](https://github.com/Cosmic-Ide/Cosmic-IDE)：Cosmic是一款功能强大、丰富的IDE，适用于Android上的JVM开发。
* [JCreator](https://jcreator.en.softonic.com/)：JCreator是一款专有软件的Java编辑器，由Xinox公司制作。
* [PraxisLive](https://github.com/praxis-live/praxis-live)：PraxisLive是一种混合视觉实时编程Java IDE。
* [JGRASP](https://www.jgrasp.org/)：JGRASP是一个轻量级开发环境，专门用于提供软件可视化的自动生成，以提高软件的可理解性，由奥本大学开源。
* [FlowV](https://gitee.com/feisuanyz/java)：Java全自动开发工具，能快速创建微服务项目，由飞算云智开源。

## 在线编辑器

* [Online Java](https://www.online-java.com)：Online Java是一个基于Web的工具，它是快速、健壮、强大的Java语言在线编译器之一。
* [JDoodle](https://www.jdoodle.com/)：JDoodle是一款在线Java编译器IDE，它能够让你在浏览器中编写、运行和调试Java代码，无需在本地安装任何开发环境。
* [SnapCode](https://github.com/reportmill/SnapCode)：SnapCode使你可以在任何现代浏览器中快速轻松地开始编写Java代码。

## 项目管理

* [JIRA](https://www.atlassian.com/software/jira)：JIRA是一个Bug跟踪管理系统，为针对Bug管理、任务追踪和项目管理的商业性应用软件，由Atlassian开发。
* [YouTrack](https://www.jetbrains.com/youtrack/)：YouTrack是JetBrains开发的专有、基于商业浏览器的错误跟踪器、问题跟踪系统和项目管理软件。
* [MyCollab](https://github.com/MyCollab/mycollab)：MyCollab是免费的开源项目管理软件。
* [Teambition](https://www.teambition.com/)：阿里旗下数字化协作平台，提供项目管理、任务协同等解决方案。
* [GanttProject](https://github.com/bardsoftware/ganttproject)：GanttProject是一款免费的桌面项目管理应用程序，由BarD软件公司开源。
* [Atlassian Confluence](https://www.atlassian.com/zh/software)：Confluence是一个专业的企业知识管理与协同软件，也可以用于构建企业Wiki，由Atlassian开发。
* [Mone](https://github.com/XiaoMi/mone)：Mone是一个以微服务为核心的一站式企业协同研发平台，支持公有云、私有云、混合云等多种部署形态，由小米开源。
* [Lavagna](https://github.com/digitalfondue/lavagna)：Lavagna是一款小型且易于使用的问题/项目跟踪软件。
* [Yobi](https://github.com/yona-projects/yona)：Yobi是一个基于Web的项目托管软件，由Naver开源。
* [Codes](https://gitee.com/xiaoming1q/icodes)：Codes是一个高效、简洁、轻量的一站式研发项目管理平台，由四川无限智达公司开源。
* [Gerrit](https://github.com/GerritCodeReview/gerrit)：Gerrit是基于Git的项目的代码审查和项目管理工具，由Google开源。
* [Kooteam](https://gitee.com/sinbo/kooteam)：Kooteam是一款轻量级的在线团队协作工具，提供各类文档工具、在线思维导图、在线流程图、项目管理、任务分发，知识库管理等工具。
* [BugCatcher](https://github.com/youzan/bugCatcher)：BugCatcher是有赞开发的项目管理、测试用例管理、项目进度和质量监控工具。
* [LibrePlan](https://github.com/LibrePlan/libreplan)：LibrePlan是一款用于项目管理、监控和控制的免费软件Web应用程序。
* [ProjectForge](https://github.com/micromata/projectforge)：ProjectForge是一个基于Web的项目管理解决方案，包括时间跟踪、团队日历、甘特图、财务管理、问题管理、控制和管理工作分解结构(例如与JIRA一起作为问题管理系统)。
* [Naikan](https://github.com/enofex/naikan)：Naikan是一款开源软件库存管理工具，适用于由CI/CD管道驱动的开发团队。
* [TMS](https://gitee.com/xiweicheng/tms)：TMS是基于频道模式的团队沟通协作+轻量级任务看板，支持Markdown、富文本、在线表格和思维导图的团队博文wiki，i18n国际化翻译管理的响应式Web开源团队协作系统。
* [Rapla](https://github.com/rapla/rapla)：Rapla是一个灵活的多用户资源和活动规划系统，它具有多个日历视图、冲突管理、完全可配置的资源和事件类型以及许多导入/导出功能。
* [OpenFastTrace](https://github.com/itsallcode/openfasttrace)：OpenFastTrace是一个需求跟踪套件，可以帮助你跟踪是否真正实现了规范中计划的所有内容。
* [ProjectLibre](https://www.projectlibre.com/)：ProjectLibre是Microsoft Project的第一大替代品，ProjectLibre提供免费桌面和订阅云解决方案。
* [PNC](https://github.com/project-ncl/pnc)：用于管理、执行和跟踪跨平台构建的系统。
* [Plan](https://calligra.org/plan/)：Plan是一个项目管理应用程序，旨在管理具有多种资源的中等大型项目。
* [HeartBeat](https://github.com/thoughtworks/HeartBeat)：HeartBeat是一个用于跟踪项目交付指标的工具，可以帮助你更好地了解交付绩效，由ThoughtWorks开发。

## 原型工具

* [Penpot](https://github.com/penpot/penpot)：Penpot是第一个用于设计和代码协作的开源设计工具。
* [ForeUI](https://www.foreui.com/)：ForeUI是一款易于使用的UI原型工具，旨在为你想要的任何应用程序或网站创建模型/线框/原型。

## 云原生

* [Linkerd](https://github.com/linkerd/linkerd)：Linkerd是一个提供弹性云端原生应用服务网格的开源项目，也是面向微服务的开源RPC代理。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种针对集成进行了优化的开源云原生编程语言，它由WSO2开发和支持。
* [Buildpacks](https://buildpacks.io)：Buildpacks可以将应用程序源代码转换为可以在任何云上运行的镜像。
* [LINSTOR](https://github.com/LINBIT/linstor-server)：LINSTOR由LINBIT开发，是一款开源软件，用于管理一组计算机上的复制卷。
* [Mendmix](https://gitee.com/dromara/mendmix-cloud)：Mendmix是一站式分布式开发架构开源解决方案及云原生架构技术底座，由dromara社区开源。
* [DataSophon](https://github.com/datavane/datasophon)：DataSophon是新一代云原生大数据管家，致力于帮助用户快速构建起稳定、高效、可弹性伸缩的大数据云原生平台，由Datavane大数据组织开源。
* [Envoy Control](https://github.com/allegro/envoy-control)：Envoy Control是一个用于Service Mesh的生产就绪控制平面，基于与平台无关的Envoy Proxy数据平面，由Allegro开源。
* [Java Control Plane](https://github.com/envoyproxy/java-control-plane)：Envoy gRPC控制平面的Java实现。
* [Apache JClouds](https://github.com/apache/jclouds)：JClouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [Kogito](https://github.com/apache/incubator-kie-kogito-runtimes)：Kogito是专注于云原生开发、部署和执行的下一代业务自动化平台。
* [JEAF](https://anaptecs.atlassian.net/wiki/spaces/JEAF/overview)：JEAF是一组框架、库和工具，支持开发基于Java的轻量级云原生企业应用程序。
* [Micro Integrator](https://github.com/wso2/micro-integrator)：Micro Integrator是WSO2 Enterprise Integrator(EI)的集成运行时，后者是一个开源混合集成平台。
* [Mercury](https://github.com/Accenture/mercury)：用于构建“可组合架构和应用程序”的参考引擎，由Accenture开源。
* [Dagger](https://github.com/raystack/dagger)：Dagger是一个易于使用、通过代码进行配置的云原生框架，构建在Flink之上，用于实时流数据的状态处理。
* [GeoServer Cloud](https://github.com/geoserver/geoserver-cloud)：GeoServer Cloud是可以通过Docker化微服务在云中使用的GeoServer。
* [Simian Army](https://github.com/Netflix/SimianArmy)：Simian Army是一套工具，可让你的云保持最佳状态运行，由Netflix开源。
* [Autotune](https://github.com/kruize/autotune)：Kruize Autotune是Kubernetes的自主性能调优工具。
* [AlterShield](https://github.com/traas-stack/altershield)：AlterShield是一款能够有效进行变更风险防控，预防变更引发生产环境故障的变更管控解决方案，这是蚂蚁集团内部变更管控平台OpsCloud的开源版本。
* [OpenSergo](https://github.com/opensergo)：OpenSergo是一个开源、与语言无关、接近业务语义的云原生服务治理规范，在异构微服务系统场景下，企业可以通过这个统一的规范来管理不同语言、不同协议的服务，这是阿里联合B站、字节发起的项目。
* [OpenTOSCA Container](https://github.com/OpenTOSCA/container)：OpenTOSCA Container是基于Java/Maven的运行时，用于部署和管理基于TOSCA的应用程序。

## 云计算

* [Apache CloudStack](https://github.com/apache/cloudstack)：CloudStack是一款开源软件，旨在部署和管理大型虚拟机网络，是一种高可用性、高可扩展性的IaaS云计算平台，由Citrix开发。
* [OpenStack4j](https://github.com/openstack4j/openstack4j)：OpenStack4j是一个流式的OpenStack客户端，允许配置和控制OpenStack部署，华为开源。
* [CloudSim](https://github.com/Cloudslab/cloudsim)：CloudSim是一个云计算基础设施和服务的建模和仿真框架，由墨尔本大学开源。
* [PureEdgeSim](https://github.com/CharafeddineMechalikh/PureEdgeSim)：PureEdgeSim是用于云、边缘和雾计算环境性能评估的仿真框架。
* [CloudSimPlus](https://github.com/cloudsimplus/cloudsimplus)：CloudSim Plus是一个现代、最新、功能齐全且文档齐全的Java 17模拟框架，它易于使用和扩展，支持对云计算基础设施和应用服务进行建模、模拟和实验。
* [Eclipse ioFog](https://github.com/eclipse-iofog/Agent)：ioFog是一个开源的边缘计算平台，它提供了一套用于管理和编排边缘设备的工具和框架，由IBM开源。
* [ColocationSim](https://github.com/pku-finelab/ColocationSim)：ColocationSim通过先进的模拟技术，解决了混合部署在线与离线作业在真实环境中测试所带来的高成本、高风险以及长周期问题，北京大学开源。
* [Nimbus](https://github.com/nimbusproject/nimbus)：Nimbus是用于科学的云计算软件，由芝加哥大学开源。

## Serverless

* [Apache EventMesh](https://github.com/apache/eventmesh)：EventMesh是新一代Serverless事件中间件，用于构建分布式事件驱动应用程序，由微众银行开源。
* [Kotless](https://github.com/JetBrains/kotless)：Kotlin Serverless框架，由JetBrains开源。
* [Koupleless](https://github.com/koupleless/koupleless)：Koupleless是一种模块化的Serverless技术解决方案，它能让普通应用以比较低的代价演进为Serverless研发模式，由蚂蚁开源。
* [Powertools Lambda Java](https://github.com/aws-powertools/powertools-lambda-java)：Powertools是一个开发工具包，用于实现Serverless最佳实践并提高开发人员速度。
* [Serverless Java Container](https://github.com/awslabs/aws-serverless-java-container)：Serverless Java Container让你可以在AWS Lambda中轻松运行使用Spring、Spring Boot、Struts、Jersey或Spark等框架编写的Java应用程序。
* [AWS Lambda Java Libraries](https://github.com/aws/aws-lambda-java-libs)：在AWS Lambda平台上运行Java的关键库。
* [Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function)：基于Spring Boot的函数计算框架。
* [Apache OpenWhisk](https://github.com/apache/openwhisk)：OpenWhisk是一个用于构建云应用程序的Serverless函数平台，由IBM开源。
* [Joylive Agent](https://github.com/jd-opensource/joylive-agent)：用于多活(单元)场景下流量治理的Java字节码增强框架，由京东开源。
* [Pulumi AWS](https://github.com/pulumi/pulumi-aws)：Pulumi的AWS资源提供商允许你在云程序中使用AWS资源。
* [Open Runtimes](https://github.com/open-runtimes/open-runtimes)：适用于多种编程语言的Serverless云计算运行时环境，旨在为在容器化系统中编写云函数创建一致且可预测的开放标准。
* [Flink Stateful Functions](https://github.com/apache/flink-statefun)：Stateful Functions是一个API，它通过为Serverless架构构建的运行时来简化分布式有状态应用程序的构建。
* [Funktion](https://github.com/funktionio/funktion-connectors)：Funktion是一个基于Kubernetes的开源事件驱动的Lambda风格编程模型。
* [Cloudstate](https://github.com/cloudstateio/cloudstate)：Cloudstate是一个开源协议和参考实现，探索有状态无服务器的想法，最初由Lightbend开发。
* [Functions Framework Java](https://github.com/GoogleCloudPlatform/functions-framework-java)：用于编写可移植Java函数的开源FaaS框架，由Google Cloud Functions团队提供。
* [SwimOS](https://github.com/swimos/swim)：SwimOS是一个全栈应用程序平台，用于构建有状态的Web服务、流API和实时UI。
* [Blox](https://github.com/blox/blox)：Blox提供针对在Amazon ECS上运行应用程序进行优化的开源调度程序，由Amazon开源。
* [FDK Java](https://github.com/fnproject/fdk-java)：Java函数开发工具包可以轻松构建Java函数并将其部署到Fn，默认完全支持Java 11+。

## 容器化工具

* [Jib](https://github.com/GoogleContainerTools/jib)：Jib无需Docker守护进程即可为Java应用程序构建优化的Docker和OCI镜像，它可作为Maven和Gradle的插件以及Java库使用，由Google开源。
* [Dockerfile Maven](https://github.com/spotify/dockerfile-maven)：该库包含一组用于处理Dockerfile的Maven工具，由Spotify开源。
* [Docker Maven Plugin](https://github.com/spotify/docker-maven-plugin)：用于构建和推送Docker镜像的Maven插件，Spotify开源，该项目不再活跃。
* [Helios](https://github.com/spotify/helios)：Helios是一个Docker编排平台，用于跨整个服务器群部署和管理容器，由Spotify开源。
* [Docker Maven Plugin](https://github.com/fabric8io/docker-maven-plugin)：用于运行和创建Docker镜像的Maven插件。
* [Terrakube](https://github.com/AzBuilder/terrakube)：Terrakube是一个开源协作平台，用于使用Terraform或OpenTofu将远程基础设施作为代码操作运行。
* [Eclipse JKube](https://github.com/eclipse/jkube)：JKube是插件和库的集合，用于使用Docker、JIB或S2I构建策略构建容器镜像。
* [Cattle](https://github.com/rancher/cattle)：Cattle是为Rancher提供支持的编排引擎，它的主要作用是元数据管理和外部系统的编排。
* [Stargate](https://github.com/ppdaicorp/stargate)：Stargate是一个基于Kubernetes和Docker的应用发布平台，由信也科技开源。
* [HyScale](https://github.com/hyscale/hyscale)：HyScale是基于K8s的以应用程序为中心的抽象框架。
* [Styx](https://github.com/spotify/styx)：Styx是一项用于触发Docker容器定期调用的服务，由Spotify开源。
* [Haven](https://github.com/codeabovelab/haven-platform)：Haven是一个开源Docker容器管理系统，它将容器、应用程序、集群、镜像和注册表管理集成在一处。
* [StackGres](https://github.com/ongres/stackgres)：StackGres是Kubernetes的全栈PostgreSQL发行版，打包到一个简单的部署单元中，拥有一组精心挑选和调整的周边PostgreSQL组件。
* [Kubernetes Operators](https://github.com/operator-framework/java-operator-sdk)：Java Operator SDK是一个生产就绪的框架，可以轻松地在Java中实现Kubernetes Operator。
* [Dekorate](https://github.com/dekorateio/dekorate)：用于生成Kubernetes相关清单的工具。
* [KubeHelper](https://github.com/KubeHelper/kubehelper)：KubeHelper通过Web界面简化了许多日常Kubernetes集群任务，搜索、分析、运行命令、Cron作业、报告、过滤器、Git同步等等。
* [Titus](https://github.com/Netflix/titus-control-plane)：Titus是Netflix容器管理平台，用于管理容器并提供与基础设施生态系统的集成。

## DevOps

* [Ice](https://github.com/Teevity/ice)：Ice可以从使用情况和成本的角度鸟瞰庞大而复杂的云环境，由Netflix开源。
* [DHorse](https://github.com/512team/dhorse)：DHorse是一个轻量级、简单易用的云应用管理平台，具有多云和多环境管理、应用管理和部署、服务治理等功能。
* [MQCloud](https://github.com/sohutv/mqcloud)：RocketMQ企业级一站式服务平台，由搜狐开源。
* [EazyBuilder](https://github.com/iSoftStoneGroup/EazyBuilder)：EazyBuilder是一套完整的云原生架构下的DevOps平台项目，由软通动力开源。
* [OpsCloud4](https://github.com/ixrjog/opscloud4)：OpsCloud4是用于云上运维的工具，提供持续交付、多实例动态数据源、堡垒机等功能。
* [SREWorks](https://github.com/alibaba/SREWorks)：SREWorks专注于以应用为中心的开发模式，提供一站式云原生数智化运维SaaS管理套件，由阿里开源。
* [WGCLOUD](https://github.com/tianshiyeben/wgcloud)：WGCLOUD是Linux运维监控工具，支持系统硬件信息、内存、CPU、温度、磁盘空间及IO、硬盘smart、系统负载、网络流量等监控。
* [MoSKito](https://github.com/anotheria/moskito)：MoSKito是一个开源系统，用于监控Java Web应用程序的性能和行为。
* [Choerodon](https://gitee.com/choerodon/choerodon)：Choerodon数智化开发管理平台，提供体系化方法论和协作、测试、DevOps及容器工具，由甄知科技开源。
* [Dubbo Admin](https://github.com/apache/dubbo-admin)：Dubbo Admin是为了更好地可视化Dubbo服务而设计的控制台。
* [CloudExplorer Lite](https://github.com/CloudExplorer-Dev/CloudExplorer-Lite)：CloudExplorer Lite脱胎于飞致云创始软件产品CloudExplorer多云管理平台，支持对接纳管主流的公有云和私有云基础设施，提供开箱即用的云主机管理、云账单、运营分析和安全合规等基本功能。
* [Ward](https://github.com/Rudolf-Barbu/Ward)：Ward是一个简单简约的服务器监控工具，支持自适应设计系统。
* [DomeOS](https://github.com/domeos/server)：DomeOS是搜狐北京研发中心打造的一款基于Docker的企业级应用编排运维管理系统。
* [Kardio](https://github.com/tmobile/kardio)：Kardio是一个简单的工具，可以配置为在任何端点上执行运行状况检查，由T-Mobile开源。
* [Pallet](https://github.com/pallet/pallet)：Pallet用于在云和虚拟机基础设施上配置和维护服务器，旨在解决跨各种云提供一致配置的运行镜像的问题。
* [Orion Visor](https://gitee.com/dromara/orion-visor)：Orion Visor是一款高颜值、现代化的智能运维&轻量堡垒机平台，由dromara社区开源。
* [Rundeck](https://github.com/rundeck/rundeck)：Rundeck是一种开源自动化服务，具有Web控制台、命令行工具和Web API，它使你可以轻松地跨一组节点运行自动化任务。
* [Uyuni](https://github.com/uyuni-project/uyuni)：Uyuni是一个开源系统管理解决方案，源自Spacewalk。
* [WeCube](https://github.com/WeBankPartners/wecube-platform)：WeCube是一套开源、一站式IT架构管理和运维管理工具，主要用于简化分布式架构IT管理，并可以通过插件进行功能扩展，由微众开源。
* [MSEC](https://github.com/Tencent/MSEC)：MSEC由腾讯QQ团队开源，它是一个后端Devops引擎，包括RPC、名称查找、负载均衡、监控、发布和容量管理。
* [Phoenix](https://gitee.com/monitoring-platform/phoenix)：Phoenix是一个灵活可配置的开源监控平台，主要用于监控应用程序、服务器、Docker、数据库、网络、TCP端口和HTTP接口。
* [Frostmourne](https://github.com/AutohomeCorp/frostmourne)：Frostmourne是汽车之家经销商技术部监控系统的开源版本，用于帮助监控几乎所有数据库数据(包括Elasticsearch、Prometheus、SkyWalking、MySQL等等)。
* [Cubic](https://github.com/dromara/cubic)：Cubic一站式问题定位平台，分布式实例监控、线程栈监控、线程池监控、动态Arthas命令集、依赖分析等等，由dromara社区开源。
* [Suricate](https://github.com/michelin/suricate)：Suricate是一款开源应用程序，它允许IT团队通过由可在电视上显示的小部件组成的仪表板来监控其环境，由米其林开源。
* [UAVStack](https://github.com/uavorg/uavstack)：UAVStack是智能化服务技术栈，是研发运维一体化的解决方案。
* [Ovirt](https://github.com/oVirt/ovirt-engine)：Ovirt是一个开源的虚拟化管理平台，RedHat虚拟化管理平台RHEV的开源版本。
* [CloudUnit](https://github.com/end-of-game/cloudunit)：CloudUnit是Treeptik开源的DevOps平台。
* [OneOps](https://github.com/oneops/oneops)：OneOps是一个自动化运维开发的云管理平台，由沃尔玛赞助。
* [Jpom](https://gitee.com/dromara/Jpom)：Jpom是一款原生Ops软件，由dromara社区开源。
* [Nginx WebUI](https://gitee.com/cym1102/nginxWebUI)：Nginx WebUI是一款图形化管理Nginx配置的工具。
* [SimpleDocker](https://gitee.com/taoes_admin/SimpleDocker)：SimpleDocker是一个简单的Docker控制面板，可以让用户更方便、舒适的使用Docker，其界面简洁、操作便捷，功能强大，可以带来更好地运维体验。
* [Gitaction Board](https://github.com/otto-de/gitactionboard)：Github Actions的仪表板。
* [HeartBeat](https://gitee.com/mkk/HeartBeat)：心跳检测各类应用服务器(如Tomcat、Jetty)，Web服务器(如Apache、Nginx)的Java Web应用程序。
* [Bk Job](https://github.com/TencentBlueKing/bk-job)：蓝鲸作业平台是一套运维脚本管理系统，具备海量任务并发处理能力，腾讯开源。
* [DQOps](https://github.com/dqops/dqo)：DQOps是一款DataOps友好的数据质量监控工具，具有可定制的数据质量检查和数据质量仪表板。
* [OpenNMS](https://github.com/OpenNMS/opennms)：OpenNMS是一个开源网络监控平台，可帮助你可视化和监控本地和分布式网络上的所有内容。
* [Easy Manager Tool](https://gitee.com/aizuda/easy-manager-tool)：Easy Manager Tool集成各类工具的核心使用方法，打造集成化程度高且专业的开、测、维一体化管理工具，由爱组搭开源。
* [RackShift](https://github.com/fit2cloud/rackshift)：RackShift是开源的裸金属服务器管理平台，功能覆盖裸金属服务器的发现、带外管理、RAID配置、固件更新、操作系统安装等，由飞致云开源。
* [Hinemos](https://github.com/hinemos/hinemos)：Hinemos是一款开源集成系统管理软件，提供监控和作业管理(工作负载调度)功能，实现系统操作自动化，由NTT Data开源。
* [NeatLogic](https://gitee.com/neat-logic/neatlogic-itom-all)：NeatLogic是一套渐进式ITOM平台，致力为不同类型、不同规模用户提供完整的ITOM解决方案。
* [Hyperic HQ](https://github.com/hyperic/hq)：Hyperic HQ是一个基于Java的软件资源监测和管理平台。

## 云服务

* [Nomulus](https://github.com/google/nomulus)：Nomulus是一种开源、可扩展、基于云的服务，用于运营顶级域名(TLD)，由Google开源。
* [ZStack](https://github.com/zstackio/zstack)：ZStack是开源IaaS软件，旨在实现数据中心自动化，通过API管理计算、存储和网络资源，由云轴科技开源。
* [Gaia](https://github.com/gaia-app/gaia)：Gaia是一个用于Terraform模块和自助服务基础设施的Terraform UI。
* [AWS SaaS Boost](https://github.com/awslabs/aws-saas-boost)：AWS SaaS Boost为组织提供即用型核心软件元素，以便在云中成功运行SaaS工作负载，由Amazon开源。
* [Compute Nest SaaS Boost](https://github.com/aliyun/alibabacloud-compute-nest-saas-boost)：计算巢SaaS Boost是由阿里云推出的一款开发工具和框架，旨在帮助(SaaS)开发者快速构建、部署、扩展和售卖SaaS应用程序。
* [Wemirr Platform](https://gitee.com/battcn/wemirr-platform)：优秀、简单、漂亮的开源SaaS、多租户云平台架构。
* [HZERO](https://gitee.com/open-hand/hzero)：HZERO是基于微服务架构开源免费的企业级PaaS平台，由上海汉得公司开发。
* [J2PaaS](https://gitee.com/j2paas/j2paas-framework)：J2PaaS是一个集成开发平台，以参数驱动为核心，为开发者提供可视化、组件化、低代码、拖拽式在线敏捷开发平台，由吉鼎科技开源。
* [Apache Stratos](https://github.com/apache/stratos)：Stratos包括多语言和环境支持，以及在多个IaaS运行时上运行的能力。
* [Myria](https://github.com/uwescience/myria)：Myria是华盛顿大学的分布式、无共享大数据管理系统和云服务。
* [Eclipse Jemo](https://github.com/eclipse/jemo)：Jemo旨在为基于JVM的语言提供真正的多云FaaS实现。
* [Eclipse Dirigible](https://github.com/eclipse/dirigible)：Dirigible是一种高生产力PaaS，它提供了一个由预选执行引擎和内置Web开发工具组成的应用程序服务器，它也适合利用低代码/无代码技术来快速开发业务应用程序，由SAP开源。
* [Eucalyptus](https://github.com/eucalyptus/eucalyptus)：Eucalyptus是用于构建与Amazon Web Services兼容的私有云和混合云的开源软件。
* [Kalix](https://www.kalix.io/)：Kalix是一个PaaS平台，它抽象了事件驱动的微服务的复杂性，团队可以专注于构建应用程序背后的业务逻辑，由Lightbend开源。
* [Paladin Cloud](https://github.com/PaladinCloud/CE)：Paladin Cloud是一个免费的开源云安全平台，致力于帮助你发现云安全中的盲点。
* [Eclipse Winery](https://github.com/eclipse/winery)：Winery是一个基于Web的环境，用于以图形方式对TOSCA拓扑进行建模并计划管理这些拓扑。
* [Alfresco](https://github.com/Alfresco/alfresco-community-repo)：Alfresco平台提供全面的云原生内容服务。
* [XGVela](https://github.com/XGVela/XGVela)：XGVela是由中国移动主导发起的5G云原生PaaS平台开源项目。
* [Asgard](https://github.com/Netflix/asgard)：Asgard是一个基于Web的工具，用于管理基于云的应用程序和基础设施，由Netflix开源。
* [Poja](https://github.com/hei-school/poja)：Poja是一个完整的Java基础设施，由马达加斯加计算机科学高中开源。
* [Eclipse Xpanse](https://github.com/eclipse-xpanse/xpanse)：Xpanse是一个开源项目，允许在任何云服务提供商上轻松实施本机托管服务。

## APM

* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为开源。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为美团点评提供了全面的实时监控告警服务。
* [凤晴](http://www.uml.org.cn/wfw/202108185.asp)：凤睛是百度商业业务系统的APM，它侧重于对Java应用的监控，基本接入了百度绝大部分Java应用
* [PFinder](https://developer.jdcloud.com/article/3821)：PFinder是京东UMP团队打造的新一代APM系统，集调用链追踪、应用拓扑、多维监控于一身。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Matrix](https://github.com/Tencent/matrix)：Matrix是腾讯微信中使用的APM，用于监控、定位和分析性能问题。
* [SkyEye](https://github.com/JThink/SkyEye)：SkyEye是对Java、Scala等运行于JVM的程序进行实时日志采集、索引和可视化，对系统进行进程级别的监控的工具。
* [Hawkular](https://github.com/hawkular/hawkular-apm)：Hawkular是RedHat开源的应用程序性能管理解决方案。
* [Wavefront](https://docs.wavefront.com/)：Wavefront是一个高性能流分析平台，支持指标、计数器、直方图和跟踪/跨度的可观察性，由VMware维护。
* [Sentry Java](https://github.com/getsentry/sentry-java)：适用于Java、Android和其他JVM语言的Sentry SDK。
* [Hertzbeat](https://github.com/dromara/hertzbeat)：HertzBeat是一个开源的实时监控系统，具有自定义监控、高性能集群、Prometheus兼容和无代理功能，由dromara社区开源。
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM)：ArgusAPM是360开源的线上移动性能检测平台。
* [Hypertrace](https://github.com/hypertrace/hypertrace)：Hypertrace是一个基于云原生分布式跟踪的可观测性平台，可让你了解开发和生产分布式系统，由Traceable开发。
* [Scouter](https://github.com/scouter-project/scouter)：SCOUTER是一个开源APM，类似于New Relic和AppDynamics，由LG开源。
* [MyPerf4J](https://github.com/LinShunKang/MyPerf4J)：MyPerf4J是一个针对高并发、低延迟应用设计的高性能Java性能监控和统计工具。
* [AppDynamics](https://www.appdynamics.com/)：AppDynamics是一款APM性能监控软件，可用于监控和管理服务器、虚拟机、数据库等运行情况，由Cisco提供。
* [Elastic APM](https://github.com/elastic/apm-agent-java)：Elastic APM Java代理。
* [FusionReactor](https://fusion-reactor.com/)：FusionReactor是一个具有AI增强功能的可观察性平台，可为开发人员、DevOps和支持团队提供前所未有的生产环境洞察，这是Intergral公司商业产品。
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor)：Stagemonitor是用于Java服务器应用程序性能监控的开源解决方案。
* [New Relic Java](https://github.com/newrelic/newrelic-java-agent)：New Relic Java代理。
* [Glowroot](https://github.com/glowroot/glowroot)：Glowroot是一个易于使用，开销极低的Java APM。
* [Fiery](https://github.com/weiboad/fiery)：Fiery是用于PHP的APM工具，由微博开源。
* [OzHera](https://github.com/XiaoMi/ozhera)：OzHera是云原生时代的应用可观察平台，由小米中国区研发效率团队开源。
* [EasyAgent](https://github.com/megaease/easeagent)：面向云原生和APM系统的轻量级开源Java Agent，MegaEase开源。
* [inspectIT](https://github.com/inspectIT/inspectIT)：ispectIT是领先的开源APM工具，用于监视和分析Java(EE)软件应用程序。
* [Lightrun](https://lightrun.com/)：Lightrun是一个面向开发人员的可观察性工具。
* [BeeAPM](https://github.com/hao117/bee-apm)：BeeAPM是一个分布式跟踪和应用性能监控系统。
* [Digma](https://github.com/digma-ai/digma)：Digma是一个持续反馈平台，使可观察性与开发相关。

## 分布式追踪

* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为开源(吴晟)。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [MTrace](https://tech.meituan.com/2016/10/14/mt-mtrace.html)：MTrace是美团内部的分布式会话跟踪系统，参考了Twitter的Zipkin以及阿里的鹰眼实现。
* [LTrace](https://www.infoq.cn/article/mcadu5wixiviyyx6uetj)：LTrace由链家开发，为链家提供分布式调用链追踪能力。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Watchman](https://www.infoq.cn/article/weibo-watchman/)：Watchman是微博的链路追踪及服务质量保障系统。
* [EagleEye](https://www.infoq.cn/article/jgzbemozgmbsukewff6j)：鹰眼是Google的分布式调用跟踪系统Dapper在淘宝的Java实现。
* [CallGraph](https://www.51cto.com/article/528304.html)：京东的分布式跟踪解决方案。
* [SOFATracer](https://github.com/sofastack/sofa-tracer)：SOFATracer是一个用于分布式系统调用跟踪的组件，由蚂蚁开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为大众点评提供了全面的实时监控告警服务。
* [凤晴](http://www.uml.org.cn/wfw/202108185.asp)：凤睛是百度商业业务系统的APM，它侧重于对Java应用的监控，基本接入了百度绝大部分Java应用。
* [Hiro](https://www.infoq.cn/article/suning-call-chain-monitoring-system-escort-818)：Hiro是苏宁易购开发的分布式跟踪系统。
* [Brave](https://github.com/openzipkin/brave)：Brave是一个分布式跟踪仪器库。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Telemetry](https://github.com/yammer/telemetry)：Telemetry是由Yammer开源的受Dapper启发的分布式跟踪系统。
* [Apache HTrace](https://github.com/apache/incubator-retired-htrace)：HTrace是一个用于分布式系统的跟踪框架，由Cloudera开源。
* [Spring Cloud Sleuth](https://github.com/spring-cloud/spring-cloud-sleuth)：Spring Cloud Sleuth为分布式跟踪提供Spring Boot自动配置。
* [ApplicationInsights](https://github.com/microsoft/ApplicationInsights-Java)：ApplicationInsights是Java的应用程序洞察工具，由Microsoft开源。
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-java)：OpenTelemetry Java SDK。
* [Wingtips](https://github.com/Nike-Inc/wingtips)：Wingtips是基于谷歌Dapper论文的Java分布式跟踪解决方案，由Nike开源。
* [Micrometer Tracing](https://github.com/micrometer-metrics/tracing)：Micrometer Tracing是Micrometer应用程序跟踪门面，由VMware开源。
* [Hydra](https://github.com/odenny/hydra)：Hydra是京东开发的分布式跟踪系统。
* [Pylon](https://www.infoq.cn/article/NDa71WVNsCWwl1Tdc44Q)：Pylon由网易云开发，为业务提供服务监控、链路追踪、治理分析、问题诊断等能力。
* [Cicada](https://github.com/Yirendai/cicada)：Cicada是宜人贷开源的分布式跟踪系统，基于谷歌Dapper论文实现。
* [PerfMark](https://github.com/perfmark/perfmark)：PerfMark是一个低开销、手动检测的Java跟踪库。
* [Logbook](https://github.com/didi/logbook)：Logbook是一款面向ToB业务的服务端埋点方案，由滴滴开源。
* [Kamon](https://github.com/kamon-io/Kamon)：Kamon可以收集指标、跨线程和服务传播上下文并自动获取分布式跟踪。
* [Money](https://github.com/Comcast/money)：Money是一个模块化的分布式追踪平台，可以无缝地融入现代应用程序中，由Comcast开源。
* [DataDog Java](https://github.com/DataDog/dd-trace-java)：DadaDog分布式跟踪工具的Java客户端。

## 指标报告

* [Dropwizard Metrics](https://github.com/dropwizard/metrics)：Metrics提供了一个强大的工具包，其中包含衡量生产环境中关键组件行为的方法，由Yammer开源。
* [Prometheus Java](https://github.com/prometheus/client_java)：用于JVM应用程序的Prometheus检测库。
* [Servo](https://github.com/Netflix/servo)：Servo提供了一个简单的接口，用于在Java中公开和发布应用程序指标，由Netflix开源。
* [Oculus](https://github.com/etsy/oculus)：Oculus是Etsy Kale系统的异常关联组件。
* [Metrik](https://github.com/thoughtworks/metrik)：Metrik是一种自动化工具，可以从CD管道中提取数据并为交付团队分析四个关键指标趋势，由ThoughtWorks开发。
* [CloudWatch Exporter](https://github.com/prometheus/cloudwatch_exporter)：适用于Amazon CloudWatch的Prometheus导出器。
* [Java Metrics](https://github.com/runtimetools/javametrics)：Java Metrics为Java运行时提供性能监控工具，通过其内置仪表板直观地提供监控数据，由IBM开源。
* [Metrics Spring](https://github.com/ryantenney/metrics-spring)：Metrics Spring将Dropwizard Metrics库与Spring集成，并提供XML和Java配置。
* [Spectator](https://github.com/Netflix/spectator)：用于记录维度时间序列的检测代码的简单库，由Netflix开源。
* [Micrometer](https://github.com/micrometer-metrics/micrometer)：Micrometer为最流行的可观察性系统提供了一个门面，允许你在不锁定供应商的情况下检测基于JVM的应用程序代码，由VMware开源。
* [Alibaba Metrics](https://github.com/alibaba/metrics)：Alibaba Metrics是阿里内部广泛使用的度量埋点基础类库。
* [FFWD](https://github.com/spotify/ffwd)：FFWD是一种灵活的度量转发代理，旨在在系统本地运行并通过各种协议接收指标，然后将它们转发到TSDB，由Spotify开源。
* [Argus](https://github.com/salesforce/Argus)：Argus是一个时序监控和警报平台，它由离散服务组成，用于配置警报、摄取和转换指标和事件、发送通知、创建命名空间以及建立和实施策略和使用配额，由Salesforce开源。
* [SOFALookout](https://github.com/sofastack/sofa-lookout)：SOFALookout是一个利用多维度的Metrics对目标系统进行度量和监控的项目，由蚂蚁开源。
* [Blueflood](https://github.com/rax-maas/blueflood)：Blueflood是一个多租户、分布式度量处理系统，能够大规模地摄取、汇总和提供指标，由Rackspace开源。
* [PerfMon](https://github.com/undera/perfmon-agent)：用于访问远程计算机上的系统指标的代理应用程序。
* [Hawkular Metrics](https://github.com/hawkular/hawkular-metrics)：Hawkular Metrics是Hawkular社区的度量数据存储引擎部分。
* [Tritium](https://github.com/palantir/tritium)：Tritium是一个用于检测应用程序的库，以在运行时提供更好的可观察性，Palantir开源。
* [Jmxtrans](https://github.com/jmxtrans/jmxtrans)：Jmxtrans是一个工具，允许你连接到任意数量的JVM并查询它们的属性，而无需编写任何Java代码。

## API网关

* [Zuul](https://github.com/Netflix/zuul)：Zuul是一种网关服务，提供动态路由、监控、弹性、安全性等，由Netflix开源。
* [Apache ShenYu](https://github.com/apache/shenyu)：ShenYu是一个Java原生API网关，用于服务代理、协议转换和API治理，由dromara社区开源。
* [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)：Spring Cloud Gateway旨在提供一种简单而有效的方法来路由到API并为其提供横切关注点，由Pivotal开源。
* [FizzGate](https://github.com/fizzgate/fizz-gateway-node)：FizzGate是一个基于Java开发的微服务聚合网关，由正元信息公司提供。
* [有赞API网关](https://tech.youzan.com/api-gateway-in-practice/)：有赞API网关承载着微商城、零售、微小店、餐饮、美业、AppSDK、部分PC、三方开发者等多个业务的调用。
* [唯品会API网关](https://mp.weixin.qq.com/s/gREMe-G7nqNJJLzbZ3ed3A)：唯品会网关是基于Netty自研的API网关。
* [DAG](https://tech.dewu.com/article?id=98)：DAG是得物研发的内部API网关产品。
* [Shepherd](https://tech.meituan.com/2021/05/20/shepherd-api-gateway.html)：Shepherd是美团的高性能、高可用、可扩展的统一API网关解决方案。
* [携程API网关](https://www.51cto.com/article/776528.html)：携程研发的基于Netty的高性能网关。
* [Gateleen](https://github.com/swisspost/gateleen)：Gateleen是一个用于构建API网关的RESTFul中间件工具包，瑞士邮政开源。
* [VX API Gateway](https://gitee.com/mirren/VX-API-Gateway)：VX API Gateway是基于Vert.x开发的一个全异步、高性能、可扩展、轻量级的API网关。
* [SIA Gateway](https://github.com/siaorg/sia-gateway)：SIA Gateway是基于Spring Cloud微服务生态体系下开发的一个分布式微服务网关系统，宜信开源。
* [Gravitee](https://github.com/gravitee-io/gravitee-api-management)：Gravitee是一个灵活且快速的开源API网关。
* [Heimdall](https://github.com/getheimdall/heimdall)：Heimdall是由Conductor Tecnologia SA开发的开源项目，旨在提供API编排解决方案。
* [DigiRunner](https://github.com/TPIsoftwareOSPO/digiRunner-Open-Source)：DigiRunner是一个应用层API网关，可充当微服务架构中客户端与后端服务之间通信的中央枢纽。
* [Choreo Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、开源且以开发人员为中心的API网关代理，由WSO2开源。
* [Membrane](https://github.com/membrane/api-gateway)：Membrane是用Java编写的REST、OpenAPI、GraphQL和SOAP的API网关，由Predic8公司开源。
* [Okapi](https://github.com/folio-org/okapi)：Okapi是一个多租户API网关，由Open Library基金会开源。
* [Kaazing Gateway](https://github.com/kaazing/gateway)：Kaazing Gateway是一个网络网关，旨在为基于Web的实时协议提升提供单一接入点，支持负载均衡、集群和安全管理。
* [API ML](https://github.com/zowe/api-layer)：API ML为大型机服务REST API提供单一访问点。
* [OWASP Application Gateway](https://github.com/The-OAG-Development-Project/Application-Gateway)：OWASP Application Gateway是一个HTTP反向代理，位于你的Web应用程序和客户端之间，负责处理Oauth2登录和会话管理。

## 服务发现

* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Eureka](https://github.com/Netflix/eureka)：Eureka是一项RESTful服务，主要用于AWS云中，用于中间层服务器的发现、负载均衡和故障转移，由Netflix开源。
* [Zookeeper](https://github.com/apache/zookeeper)：Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo开源。
* [Polaris Java](https://github.com/polarismesh/polaris-java)：腾讯Polaris注册中心Java SDK。
* [SOFARegistry](https://github.com/sofastack/sofa-registry)：SOFARegistry是蚂蚁金服开源的一个生产级、高时效、高可用的服务注册中心。
* [Pantheon](https://github.com/ProgrammerAnthony/Pantheon)：Pantheon是分布式微服务注册中心。
* [Artemis](https://github.com/ctripcorp/artemis)：Artemis是携程框架部门SOA服务注册表，包含服务自注册自发现、实例变更实时推送、服务分组路由功能。
* [Vert.x Service Discovery](https://github.com/vert-x3/vertx-service-discovery)：Vert.x Service Discovery提供了一个发现基础设施来注册和发现微服务应用程序公开的服务。
* [SnoopEE](https://github.com/ivargrimstad/snoop)：SnoopEE是一个基于Java EE的微服务的实验性注册和发现服务。

## 容错组件

* [Neural](https://gitee.com/yu120/neural)：Neural是微服务架构中高并发和高可用的神经组织利刃，提供了分布式限流、降级、熔断、重试和隔离的容错特性。
* [Failover](https://github.com/societe-generale/failover)：Failover是用于管理外部引用服务故障转移的通用库，由法国兴业银行开源。
* [Discovery](https://github.com/Nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移。
* [BFT SMaRt](https://github.com/bft-smart/library)：BFT SMaRt是一个用Java开发的高性能拜占庭容错状态机复制库，以简单性和健壮性为首要要求，由里斯本大学开源。
* [ScalarDL](https://github.com/scalar-labs/scalardl)：ScalarDL是一种可扩展且实用的拜占庭故障检测中间件，适用于事务数据库系统，可实现正确性、可扩展性和数据库不可知性，由韩国Scalar公司维护。
* [MicroProfile Fault Tolerance](https://github.com/eclipse/microprofile-fault-tolerance)：MicroProfile中提供的容错组件。
* [Phantom](https://github.com/flipkart-incubator/phantom)：Phantom是一个用于访问分布式服务的高性能代理，是一个支持不同传输和协议的RPC系统，由Flipkart开源。

#### 限流/降级

* [Sentinel](https://github.com/alibaba/Sentinel)：Sentinel是面向分布式、多语言异构化服务架构的流量治理组件，由阿里开源。
* [Hystrix](https://github.com/Netflix/Hystrix)：Hystrix是一个延迟和容错库，旨在隔离对远程系统、服务和第3方库的访问点，阻止级联故障，并在故障不可避免的复杂分布式系统中实现恢复能力，由Netflix开源。
* [Resilience4j](https://github.com/resilience4j/resilience4j)：Resilience4j是一个专为Java 8和函数式编程设计的容错库。
* [Bucket4j](https://github.com/bucket4j/bucket4j)：Bucket4j是一个Java限速库，主要基于令牌桶算法。
* [Failsafe](https://github.com/failsafe-lib/failsafe)：Failsafe是一个轻量级、零依赖库，用于处理Java 8+中的故障，具有用于处理日常用例的简洁API和处理其他所有内容的灵活性。
* [RateLimiter4j](https://github.com/wangzheng0822/ratelimiter4j)：RateLimiter4j是一个高度容错、低延迟、高性能的限流开发库/框架，提供了对HTTP接口的访问限流功能。
* [Concurrency Limits](https://github.com/Netflix/concurrency-limits)：Concurrency Limits实现并集成了从TCP拥塞控制到自动检测服务并发限制概念，可以以最佳延迟实现最佳吞吐量，由Netflix开源。
* [Amazon Route53 Infima](https://github.com/awslabs/route53-infima)：Amazon Route53 Infima是一个使用Amazon Route 53管理服务级故障隔离的库。
* [RateLimitJ](https://github.com/mokies/ratelimitj)：RateLimitJ是用于速率限制的Java库，提供可扩展的存储和应用程序框架适配器，该项目不再活跃。
* [SDS](https://github.com/didi/sds)：SDS是一个基于Java开发的简单、易用、高性能的服务降级系统，支持限流、熔断和降级等功能，由滴滴开源。
* [Akali](https://gitee.com/dromara/Akali)：Akali是一个轻量级本地化热点检测/降级框架，适用于大流量场景，可轻松解决业务中超高流量的并发查询等场景，由dromara社区开源。
* [Spillway](https://github.com/coveooss/spillway)：Spillway可在公共API的软件级别添加分布式节流，由Coveo开源。
* [SnowJena](https://github.com/onblog/SnowJena)：SnowJena是基于令牌桶算法实现的分布式无锁限流框架，支持动态配置规则，支持可视化监控，开箱即用。
* [FastBreak](https://github.com/Nike-Inc/fastbreak)：FastBreak是一个简单的Java 8原生断路器，支持异步Future、阻塞和回调/手动模式，由Nike开源。
* [Token Bucket](https://github.com/bbeck/token-bucket)：该库提供了令牌桶算法的实现。
* [RateLimiter Spring Boot Starter](https://github.com/taptap/ratelimiter-spring-boot-starter)：基于Redis的偏业务应用的分布式限流组件，目前支持时间窗口、令牌桶两种限流算法，由Taptap开源。

#### 重试

* [Easy Retry](https://github.com/alibaba/easy-retry)：Easy Retry是一种存储介质可扩展的持久化重试方案，由阿里开源。
* [Spring Retry](https://github.com/spring-projects/spring-retry)：Spring Retry提供了自动重新调用失败操作的能力。
* [Guava Retry](https://github.com/rholder/guava-retrying)：Guava Retry模块提供了一种通用方法，用于重试任意Java代码，具有特定的停止、重试和异常处理功能。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [Async Retry](https://github.com/nurkiewicz/async-retry)：Async Retry是用于Java 7/8的异步重试库。
* [Retry4j](https://github.com/elennick/retry4j)：Retry4j是一个简单的Java库，可帮助重试瞬时故障情况或不可靠的代码。
* [Retry](https://github.com/softwaremill/retry)：Retry提供了在 Scala Futures上运行的常见重试策略的接口，由SoftwareMill开发。
* [Sisyphus](https://github.com/houbb/sisyphus)：Sisyphus是支持过程式编程和注解编程的Java重试框架。
* [Retrieval](https://gitee.com/spjich/retrieval)：Retrieval是一个精简的Java重试组件，支持同步，异步，以及制定时间内重试。

#### 负载均衡

* [Ribbon](https://github.com/Netflix/ribbon)：Ribbon是一个进程间通信库，具有内置的软件负载均衡器，由Netflix开源。
* [Concurrency LoadBalancer](https://github.com/uber/concurrency-loadbalancer)：Concurrency LoadBalancer是一个通用的负载均衡器库，旨在提高系统负载下的吞吐量和应用程序的延迟，防止服务降级导致的级联故障，由Uber开源。
* [SmallRye Stork](https://github.com/smallrye/smallrye-stork)：SmallRye Stork是一个服务发现和客户端负载均衡框架。
* [Neutrino](https://github.com/eBay/Neutrino)：Neutrino是基于Scala的软件负载均衡器，由eBay开发。
* [Appactive](https://github.com/alibaba/Appactive)：Appactive是阿里开源的一款标准、通用且功能强大，致力于构建应用多活架构的开源中间件。
* [Simple Failover](https://github.com/PhantomThief/simple-failover-java)：Simple Failover是一个简单的Java故障转移库。
* [Baragon](https://github.com/HubSpot/Baragon)：Baragon是一个用于自动更新负载均衡器配置的系统，由HubSpot开源。
* [Sarge](https://github.com/jhalterman/sarge)：Sarge创建受监督的对象，这些对象通过执行重试、状态重置和故障升级来自动处理发生故障时的情况，从而轻松实现简单而强大的容错能力。
* [Galeb](https://github.com/galeb/galeb)：Galeb是一个开源HTTP负载均衡服务。
* [MicroProfile Health](https://github.com/eclipse/microprofile-health)：MicroProfile Health用于从另一台机器(即Kubernetes服务控制器)探测计算节点的状态，主要目标是云基础设施环境，其中自动化进程维护计算节点的状态。
* [ModCluster](https://github.com/modcluster/mod_cluster)：ModCluster是一个基于Apache httpd和纯Java Undertow的智能原生负载均衡器。
* [Elastic Load Balancing](https://github.com/aws/elastic-load-balancing-tools)：ELB自动在Amazon EC2实例、容器或由IP地址标识的资源之间分配传入应用程序流量。

## 混沌工程

* [Mangle](https://github.com/vmware/mangle)：Mangle使你能够针对应用程序和基础设施组件无缝运行混沌工程实验，以评估弹性和容错能力，由VMware开源。
* [OpenChaos](https://github.com/openmessaging/openchaos)：OpenChaos为供应商提出了一个统一的API，为在云原生环境中执行混沌工程原理的各个方面提供解决方案，由阿里发起。
* [Byte Monkey](https://github.com/mrwilson/byte-monkey)：Byte Monkey是一个小型Java库，用于测试JVM应用程序中的故障场景。
* [AWSSSMChaosRunner](https://github.com/amzn/awsssmchaosrunner)：AWSSSMChaosRunner是一个简化EC2和ECS的故障注入测试和混沌工程的库，由Amazon开源。
* [ChaosBlade Exec JVM](https://github.com/chaosblade-io/chaosblade-exec-jvm)：该项目是一个基于JVM-SandBox的ChaosBlade执行器，通过增强类来对Java应用程序进行混沌实验，阿里开源。

## 流量回放

* [JVM-Sandbox-Repeater](https://github.com/alibaba/jvm-sandbox-repeater)：JVM-Sandbox-Repeater是阿里开源的基于JVM-Sandbox的录制/回放通用解决方案。
* [Conan](https://github.com/tal-tech/conan)：柯南平台开源版本，为用户提供流量回放全流程解决方案，由好未来开源。
* [Moonbox](https://github.com/vivo/MoonBox)：Moonbox是基于JVM-Sandbox-Repeater重新开发的一款流量回放平台产品，由Vivo开源。
* [MagicOTP](https://github.com/alibaba/online-test-platform)：MagicOTP是一个开源的线上测试平台，思想是通过回放大批量线上真实请求，并结合规则验证的形式对服务返回的结果进行校验，由阿里开源。

## 大数据

这里列出了大数据领域相关Java框架、组件、工具。

#### 大数据框架

* [Apache Hadoop](https://github.com/apache/hadoop)：Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Apache Spark](https://github.com/apache/spark)：Spark是一种多语言引擎，用于在单节点机器或集群上执行数据工程、数据科学和机器学习，由加州大学伯克利分校AMPLab开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：ZooKeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo研究院开发。
* [Apache Pig](https://github.com/apache/pig)：Pig是一个用于处理非常大文件的数据流编程环境，由Yahoo开源。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：HBase是一个开源、分布式、版本化、面向列的存储，由Powerset开源。
* [Apache Calcite](https://github.com/apache/calcite)：Calcite是一个动态数据管理框架。
* [Apache Nifi](https://github.com/apache/nifi)：NiFi是一个易于使用、功能强大且可靠的系统，用于处理和分发数据，由美国国家安全局开源。
* [Apache Linkis](https://github.com/apache/linkis)：Linkis是一种计算中间件，充当上层应用程序和底层引擎(例如Spark、Hive和Flink)之间的层，由微众开源。
* [Apache Flume](https://github.com/apache/logging-flume)：Flume是一种分布式、可靠且可用的服务，用于高效收集、聚合和移动大量日志数据，由Cloudera公司开源。
* [Apache Geode](https://github.com/apache/geode)：Geode是一个数据管理平台，可在广泛分布的云架构中提供对数据密集型应用程序的实时、一致的访问，由GemStone开源。
* [Apache Drill](https://github.com/apache/drill)：Drill是一个分布式MPP查询层，支持针对NoSQL和Hadoop数据存储系统的SQL和替代查询语言，由LinkedIn、思科、威斯康星大学麦迪逊分校等开源。
* [Apache Bookkeeper](https://github.com/apache/bookkeeper)：BookKeeper是一种可扩展、容错和低延迟的存储服务，针对仅附加工作负载进行了优化，由雅虎研究院开发。
* [Apache InLong](https://github.com/apache/inlong)：InLong是一站式、全场景的海量数据集成框架，支持数据摄取、数据同步和数据订阅，提供自动、安全、可靠的数据传输能力，由腾讯大数据团队开源。
* [Apache Oozie](https://github.com/apache/oozie)：Oozie是一个可扩展、可伸缩且可靠的系统，用于通过Web服务定义、管理、调度和执行复杂的Hadoop工作负载，由Cloudera开源。
* [Apache Ozone](https://github.com/apache/ozone)：Ozone是适用于Hadoop和云原生环境的可扩展、冗余和分布式对象存储，由腾讯大数据团队开源。
* [Apache CarbonData](https://github.com/apache/carbondata)：CarbonData是一种索引列式数据存储解决方案，用于在大数据平台上进行快速分析，例如Hadoop、Spark等，由华为开源。
* [Apache Kyuubi](https://github.com/apache/kyuubi)：Kyuubi是一个分布式多租户网关，用于在数据仓库和Lakehouse上提供Serverless SQL，由网易数帆开源。
* [Snowplow](https://github.com/snowplow/snowplow)：Snowplow是一个开发者优先的收集行为数据的引擎。
* [Piflow](https://github.com/cas-bigdatalab/piflow)：Piflow是一个易于使用、功能强大的大数据管道系统，由科学大数据社区开源。
* [Airbyte](https://github.com/airbytehq/airbyte)：Airbyte是领先的数据集成平台，适用于从API、数据库和文件到数据仓库、数据湖和数据湖屋的ETL/ELT数据管道。
* [Scio](https://github.com/spotify/scio)：Scio是一个适用于Beam和Google Cloud Dataflow的Scala API，由Spotify开源。
* [Batch Processing Gateway](https://github.com/apple/batch-processing-gateway)：批处理网关使在Kubernetes上运行Spark服务变得容易，它允许用户通过直观的API调用在Kubernetes上提交、检查和删除Spark应用程序，由Apple开源。
* [Genie](https://github.com/Netflix/genie)：Genie是Netflix开发的联合大数据编排和执行引擎。
* [Venice](https://github.com/linkedin/venice)：Venice是一个衍生的数据存储平台，由LinkedIn开源。
* [DataWave](https://github.com/NationalSecurityAgency/datawave)：DataWave是一个基于Java的摄取和查询框架，它利用Accumulo提供对数据的快速、安全访问，由美国国家安全局开源。
* [Taier](https://github.com/DTStack/Taier)：太二是一个提交、调度、运维、指标信息展示的大数据开发平台，由袋鼠云开源。
* [Fire](https://gitee.com/fire-framework/fire)：Fire框架是由中通大数据自主研发并开源的、专门用于进行Spark和Flink任务开发的大数据框架。
* [SuperSQL](https://my.oschina.net/u/4956788/blog/5510918)：天穹SuperSQL是腾讯自研、基于统一SQL语言模型、面向机器学习智能调优、提供虚拟化数据和开放式计算引擎的大数据智能融合平台。
* [Apache OODT](https://github.com/apache/oodt)：OODT可以实现数据库链接、工作流处理以及硬件/文件管理等功能，由NASA的喷气机推力研究室开源。
* [Apache Sedona](https://github.com/apache/sedona)：Sedona是一种空间计算引擎，使开发人员能够在Apache Spark和Apache Flink等现代集群计算系统中轻松处理任何规模的空间数据，由亚利桑那州立大学开源。
* [Pipes](https://github.com/tinkerpop/pipes)：Pipes是一个数据流框架，可实现数据从输入到输出的拆分、合并、过滤和转换，由斯阿拉莫斯国家实验室开源。
* [Scaleph](https://github.com/flowerfine/scaleph)：Scaleph是一个基于Flink和Kubernetes打造的开放数据平台，具备Flink和SeaTunnel任务管理能力，同时支持Doris集群在Kubernetes上的运维部署。
* [Transport](https://github.com/linkedin/transport)：Transport是一个用于编写高性能用户定义函数(UDF)的框架，这些函数可跨各种引擎(包括Spark、Hive和Trino)进行移植，由LinkedIn开发。

#### 大数据工具

* [Apache Crunch](https://crunch.apache.org/)：Crunch库提供了一个用于编写、测试和运行MapReduce管道的框架，由Google开源。
* [Apache MRUnit](https://mrunit.apache.org/)：MRUnit是一个Java库，可帮助开发人员对Hadoop MapReduce作业进行单元测试，由Cloudera开源。
* [Dataflow Templates](https://github.com/GoogleCloudPlatform/DataflowTemplates)：Dataflow Templates旨在解决简单但大型的云内数据任务，包括数据导入/导出/备份/恢复和批量API操作，而无需开发环境，由Google开源。
* [Ambrose](https://github.com/twitter-archive/ambrose)：Ambrose是一个用于MapReduce数据工作流可视化和实时监控的平台，由Twitter开源。
* [EGADS](https://github.com/yahoo/egads)：EGADS是一个开源Java包，用于自动检测大规模时序数据中的异常，由Yahoo开源。
* [Data Transfer Project](https://github.com/google/data-transfer-project)：Data Transfer Project使人们可以轻松地在在线服务提供商之间传输数据，由Google联合Facebook、Twitter、Apple、Microsoft等开发。
* [Yanagishima](https://github.com/yanagishima/yanagishima)：Yanagishima是Trino、Hive和Spark的开源Web应用程序。
* [Apache Ambari](https://github.com/apache/ambari)：Ambari是一个用于配置、管理和监控Hadoop集群的工具，由Hortonworks开源。
* [Elephant Bird](https://github.com/twitter/elephant-bird)：Elephant Bird是Twitter的开源库，包含LZO、Thrift和/或Protocol Buffer相关的Hadoop InputFormats、OutputFormats、Writables、Pig LoadFuncs、Hive SerDe、HBase杂项等。
* [Deequ](https://github.com/awslabs/deequ)：Deequ是一个构建在Spark之上的库，用于定义“数据单元测试”，测量大型数据集中的数据质量，由AWS开源。
* [Cloudbreak](https://github.com/hortonworks/cloudbreak)：部署在云服务上的集成分析和数据管理平台，它提供广泛的数据分析和人工智能功能以及安全的用户访问和数据治理功能，由Hortonworks开源。
* [Flink Spector](https://github.com/ottogroup/flink-spector)：该项目提供了一个框架来定义Flink数据流的单元测试。
* [CloudEon](https://github.com/dromara/CloudEon)：CloudEon使用Kubernetes安装和部署开源大数据组件，实现开源大数据平台的容器化运行，dromara社区开源。
* [Spark RAPIDS](https://github.com/NVIDIA/spark-rapids)：Spark的RAPIDS加速器利用GPU通过RAPIDS库加速处理，由NVIDIA开源。
* [BigQuery Utils](https://github.com/GoogleCloudPlatform/bigquery-utils)：BigQuery是一个Serverless、高度可扩展且经济高效的云数据仓库，内置内存BI引擎和机器学习，该库提供有用的实用程序来帮助你迁移和使用BigQuery，由Google开发。
* [Apache Metron](https://github.com/apache/metron)：Metron集成了多种开源大数据技术，以提供集中的安全监控和分析工具，由Cisco开源。
* [DataGenerator](https://github.com/FINRAOS/DataGenerator)：DataGenerator是一个用于系统地生成大量数据的Java库，美国金融业监管局开源。
* [Surus](https://github.com/Netflix/Surus)：Pig和Hive中的分析工具集合，Netflix开源。
* [Apache AsterixDB](https://github.com/apache/asterixdb)：AsterixDB是一个大数据管理系统，具有丰富的功能集，由加利福尼亚大学欧文分校的Michael Carey发起。
* [Hollow](https://github.com/Netflix/hollow)：Hollow是一个Java库和工具集，用于将内存数据集从单个生产者传播到许多消费者，以实现高性能只读访问，由Netflix开源。
* [Compass](https://github.com/cubefs/compass)：Compass是一个大数据任务诊断平台，由OPPO大数据团队开发。
* [Olap4j](https://github.com/olap4j/olap4j)：Olap4j是用于访问OLAP数据的开放Java API，Pentaho开源。
* [Dataverse](https://github.com/IQSS/dataverse)：Dataverse是一个用于共享、查找、引用和保存研究数据的开源软件平台，由哈佛大学定量社会科学研究所开源。
* [Apache Bigtop](https://github.com/apache/bigtop)：Bigtop旨在为基础设施工程师和数据科学家寻找领先的开源大数据组件的全面打包、测试和配置。
* [Apache Wayang](https://github.com/apache/incubator-wayang)：Wayang是统一的数据处理框架，可无缝集成和编排多个数据平台，以提供无与伦比的性能和灵活性，由柏林工业大学开源。
* [Metanome](https://github.com/HPI-Information-Systems/Metanome)：Metanome是HPI和卡塔尔计算研究所之间的联合项目，通过开发高效算法并将其集成到通用工具中、扩展数据分析的功能以及解决大数据的性能和可扩展性问题，为数据分析提供了全新的视角。
* [DataCompare](https://gitee.com/dromara/data-compare)：DataCompare是一个大数据数据比对和数据探测平台，由dromara社区开源。
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [Fast Causal Inference](https://github.com/Tencent/fast-causal-inference)：Fast Causal Inference是腾讯开源的因果推理项目，它是一个基于OLAP的高性能因果推理(统计模型)计算库，解决了现有统计模型库(R/Python)在大数据下的性能瓶颈，为秒级和亚级海量数据执行提供因果推理能力。
* [Flink Streaming Platform Web](https://github.com/zhp8341/flink-streaming-platform-web)：Flink Streaming Platform Web是基于Flink封装的一个可视化、轻量级的Flink Web客户端系统。
* [WInte.r](https://github.com/olehmberg/winter)：WInte.r框架提供了端到端数据集成的方法，该框架实现了众所周知的数据预处理、模式匹配、身份解析、数据融合和结果评估方法。
* [Inviso](https://github.com/Netflix/inviso)：Inviso是一个轻量级工具，提供搜索Hadoop作业、可视化性能和查看集群利用率的功能，由Netflix开源。
* [AGEIPort](https://github.com/alibaba/AGEIPort)：AGEIPort是数字供应链孵化并在阿里内广泛使用的一套性能卓越、稳定可靠、功能丰富、易于扩展、生态完整的数据导入导出方案，由阿里开源。
* [Apache Livy](https://github.com/apache/incubator-livy)：Livy是一个开源REST接口，用于从任何地方与Spark交互，由Cloudera开源。
* [ZMS](https://github.com/ZTO-Express/zms)：ZMS是使用方与集群解耦，屏蔽各消息集群差异，并对消息集群进行安装、管理、监控、告警管理的平台，由中通开源。
* [Squall](https://github.com/epfldata/squall)：Squall是一个构建在Storm之上的在线查询处理引擎，由洛桑联邦理工学院数据实验室开源。
* [Cascading](https://github.com/cwensel/cascading)：Cascading是一个功能丰富的API，用于在本地或集群上定义和执行复杂且容错的数据处理流。
* [UberScriptQuery](https://github.com/uber/uberscriptquery)：UberScriptQuery是一个用于运行Spark SQL作业的脚本查询包装器，由Uber开源。
* [Spark-JobServer](https://github.com/spark-jobserver/spark-jobserver)：Spark-JobServer提供了一个RESTful接口，用于提交和管理Spark作业、jar和作业上下文。
* [Apache Tephra](https://github.com/cdapio/tephra)：Tephra在HBase等分布式数据存储之上提供全局一致的事务，由Google开源。
* [Haeinsa](https://github.com/VCNC/haeinsa)：Haeinsa是HBase的线性可扩展的多行、多表事务库，由VCNC开源。
* [Lipstick](https://github.com/Netflix/Lipstick)：Lipstick将Pig工作流程的图形描述与作业执行时的相关信息结合起来，由Netflix开源。
* [StreamDM](https://github.com/huawei-noah/streamDM)：StreamDM是一款新的开源软件，用于使用Spark Streaming挖掘大数据流，由华为诺亚方舟实验室开源。
* [Marmaray](https://github.com/uber/marmaray)：Marmaray是一个通用的Hadoop数据摄取和分散框架和库，由Uber开源。

#### 大数据组件

* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio)：DataSphere Studio是微众银行开发的一站式数据应用开发管理门户。
* [Quicksql](https://github.com/Qihoo360/Quicksql)：Quicksql是一款SQL查询产品，可用于特定数据存储查询或多个数据存储关联查询，由360开源。
* [BitSail](https://github.com/bytedance/bitsail)：BitSail是字节开源的基于分布式架构、高性能的数据集成引擎。
* [Dr.Elephant](https://github.com/linkedin/dr-elephant)：Dr.Elephant是一款针对Hadoop和Spark的性能监控和调优工具，由LinkedIn开源。
* [CDAP](https://github.com/cdapio/cdap)：CDAP是一个面向Hadoop生态系统的集成开源应用程序开发平台，为开发人员提供数据和应用程序抽象，目前是Google云端项目。
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)：Elasticsearch实时搜索和分析与Hadoop原生集成，支持Map/Reduce、Hive和Spark。
* [Apache Sqoop](https://github.com/apache/sqoop)：Sqoop允许在数据库和HDFS之间轻松导入和导出数据集，Cloudera开源。
* [Cubert](https://github.com/LinkedInAttic/Cubert)：Cubert是一种快速高效的批量计算引擎，用于对Hadoop上的海量数据集进行复杂分析和报告，由LinkedIn开源。
* [Secor](https://github.com/pinterest/secor)：Secor是一项将Kafka日志持久保存到Amazon S3、Google Cloud Storage、Microsoft Azure Blob Storage和Openstack Swift的服务，由Pinterest开源。
* [Harrier](https://github.com/spdb-opensource/harrier)：Harrier是一个由上海浦东发展银行开源的海量作业调度系统，支持各类异构计算平台海量计算作业的配置、管理和监控功能。
* [DataBand](https://gitee.com/475660/databand)：轻量级一站式大数据分析平台。
* [Big Whale](https://gitee.com/meetyoucrop/big-whale)：美柚大数据研发的分布式计算任务调度系统，提供Spark、Flink等批处理任务的DAG调度和流处理任务的运行管理和状态监控，并具有Yarn应用管理、重复应用检测、大内存应用检测等功能。
* [Apache Fluo](https://github.com/apache/fluo)：Fluo是一个分布式处理系统，允许用户对大型数据集进行增量更新，Google Percolator的开源实现。
* [Fili](https://github.com/yahoo/fili)：Fili是一个基于Java的框架，可以轻松构建和维护用于时间序列报告和分析的RESTful Web服务，由Yahoo开源。
* [DBus](https://github.com/BriData/DBus)：DBus专注于数据的收集及实时数据流计算，通过简单灵活的配置，无侵入的方式对源端数据进行采集。
* [Hermes](https://www.infoq.cn/article/zx0g0ruv5nzxpfjdpvpr)：Hermes是腾讯数据平台部自研的实时分析平台。
* [Qualitis](https://github.com/WeBankFinTech/Qualitis)：Qualitis是一个数据质量管理平台，支持各种数据源的质量验证、通知和管理，用于解决数据处理过程中引起的各种数据质量问题，由微众开源。
* [Embulk](https://github.com/embulk/embulk)：Embulk是一个并行批量数据加载器，有助于在各种存储、数据库、NoSQL和云服务之间传输数据。
* [Stroom](https://github.com/gchq/stroom)：Stroom是一个数据处理、存储和分析平台，由英国政府通讯总部开源。
* [DnA](https://github.com/mercedes-benz/DnA)：DnA为分析领域的企业提供A-Z解决方案，从计划和正在进行的活动的透明度到提供实现这些活动的开源组件，由奔驰开源。
* [Rakam](https://github.com/rakam-io/rakam-api)：Rakam是一个分析平台，可让你创建分析服务。
* [TiSpark](https://github.com/pingcap/tispark)：TiSpark是一个薄层，用于在TiDB/TiKV/TiFlash之上运行Spark，以回答复杂的OLAP查询，由PingCAP开发。
* [Firehose](https://github.com/raystack/firehose)：Firehose是一种可扩展、无代码、云原生服务，用于将实时流数据从Kafka加载到数据存储、数据湖和分析存储系统。
* [DataFu](https://github.com/LinkedInAttic/datafu)：DataFu是用于处理Hadoop中的大规模数据的库集合，由LinkedIn开源。
* [Apache Hama](http://hama.apache.org/)：Hama是一个使用批量同步并行计算模型的大数据分析框架。
* [LemonGrenade](https://github.com/NationalSecurityAgency/lemongrenade)：LemonGrenade被设计为一个自动化系统，能够将系统、数据源或功能智能地链接在一起，而无需最终用户手动指定链接，由美国国家安全局开源。
* [Apache Tez](https://github.com/apache/tez)：Tez是一个通用数据处理管道引擎，被设想为用于更高抽象的低级引擎，例如Hadoop Map-Reduce、Pig、Hive等，由IBM和Adobe开发。
* [Esper](https://github.com/espertechinc/esper)：Esper是用于复杂事件处理(CEP)、流式SQL和事件系列分析的组件。
* [Apache Falcon](http://falcon.apache.org/)：Falcon是一个Feed处理和Feed管理系统，旨在让最终消费者更轻松地在Hadoop集群上进行Feed处理和管理。
* [Egeria](https://github.com/odpi/egeria)：Egeria提供开放元数据和治理类型系统、框架、API、事件有效负载和交换协议，由IBM开源。
* [BigQuery Data Lineage](https://github.com/GoogleCloudPlatform/bigquery-data-lineage)：使用审核日志、ZetaSQL和Dataflow对BigQuery进行实时数据沿袭跟踪的参考实现，由Google开源。
* [Suro](https://github.com/Netflix/suro)：Suro是一种数据管道服务，用于收集、聚合和调度大量应用程序事件(包括日志数据)，由Netflix开发。
* [MdRill](https://github.com/alibaba/mdrill)：MdRill作为数据在线分析处理软件，可以在几秒到几十秒的时间，分析百亿级别的任意组合维度的数据，由阿里开源。
* [Apache Apex](https://github.com/apache/apex-core)：Apex是一个用于大数据流和批处理的统一平台，由DataTorrent开源。
* [Apache Knox](https://github.com/apache/knox)：Knox是一个应用程序网关，用于以安全的方式与一个或多个Hadoop集群的REST API和用户界面进行交互。
* [Apache Hop](https://github.com/apache/hop)：Hop编排平台旨在促进数据和元数据编排的各个方面，也是Kettle的前身。
* [OpenHuFu](https://github.com/BUAA-BDA/OpenHuFu)：OpenHuFu是一个开源的数据联邦系统，支持多数据库协同查询，并具有安全保障，由清华大学开源。
* [Eclipse Connector](https://github.com/eclipse-edc/Connector)：EDC核心服务包括数据平面和控制平面。
* [OpenLooKeng](https://github.com/openlookeng/hetu-core)：OpenLooKeng是一个嵌入式引擎，可以对任何地方的任何数据进行现场分析，包括地理上远程的数据源，由华为开源。
* [Teiid](https://github.com/teiid/teiid)：Teiid是一个数据虚拟化系统，允许应用程序使用来自多个异构数据存储的数据，由RedHat主导。
* [GridGain Community Edition](https://github.com/gridgain/gridgain)：GridGain是一个强化的高性能开源内存计算平台。
* [Apache Griffin](https://github.com/apache/griffin)：Griffin是一个开源的大数据数据质量解决方案，由eBay开源，它支持批处理和流模式两种数据质量检测方式，是一个基于Hadoop和Spark建立的数据质量服务平台。
* [Apache Ranger](https://github.com/apache/ranger)：Ranger是一个用在Hadoop平台上并提供操作、监控、管理综合数据安全的框架，由Hortonworks开源。
* [Beekeeper](https://github.com/ExpediaGroup/beekeeper)：Beekeeper是一个安排删除孤立路径和过期元数据的服务，由Expedia开源。
* [Apache Mnemonic](https://github.com/apache/mnemonic)：Mnemonic是一个面向非易失性混合内存存储的库，它提出了非易失性/持久性Java对象模型和持久性计算服务，为显著提高海量实时数据处理/分析的性能带来了多种优势。
* [Stocator](https://github.com/CODAIT/stocator)：Stocator是Spark对象存储的高性能连接器，通过利用对象存储语义来实现性能，由IBM开源。
* [MR4C](https://github.com/google/mr4c)：MR4C是一个允许你在Hadoop执行框架内运行本机代码的框架，由Google开源。
* [Apache Tajo](https://github.com/apache/tajo)：Tajo是Hadoop的开源分布式数据仓库框架，最初由韩国基础设施公司Gruter开发。
* [Apache Airavata](https://github.com/apache/airavata)：Airavata是一个软件框架，用于在分布式计算资源(包括本地集群、超级计算机、国家电网、学术和商业云)上执行和管理计算性任务，最初由印第安纳大学开发。
* [LarkMidTable](https://gitee.com/LarkMidTable/LarkMidTable)：LarkMidTable是一站式开源的数据中台，实现元数据管理，数据仓库开发，数据质量管理，数据的可视化，实现高效赋能数据前台并提供数据服务的产品。
* [云雀](https://gitee.com/LarkMidTable/yunque)：云雀是一款数据集成工具，实现异构数据源的整合，帮助企业构建数据仓库、数据湖等应用架构。
* [DeltaFi](https://gitlab.com/deltafi/deltafi)：DeltaFi是一个灵活、轻量代码的数据转换和标准化平台。
* [Datacube](https://github.com/urbanairship/datacube)：具有数值数据汇总的多维数据存储，由Airship开源。
* [Apache Eagle](https://github.com/apache/eagle)：Eagle是一种开源分析解决方案，用于在大数据平台上立即识别安全和性能问题，由eBay开源。
* [Apache Gluten](https://github.com/apache/incubator-gluten)：Gluten是一个中间层，负责将基于JVM的SQL引擎的执行卸载到本机引擎，由Intel和Kyligence开源。
* [Maha](https://github.com/yahoo/maha)：快速报告API开发的框架，开箱即用地支持Druid的高基数维度查找，由Yahoo开源。
* [Hydra](https://github.com/addthis/hydra)：Hydra是最初由AddThis开发的分布式数据处理和存储系统。
* [Apache DataFusion Comet](https://github.com/apache/datafusion-comet)：DataFusion Comet是一个Spark插件，它使用DataFusion作为本机运行时，以实现查询效率和查询运行时方面的改进，由Apple开源。
* [XL-LightHouse](https://github.com/xl-xueling/xl-lighthouse)：XL-LightHouse是一套支持超大数据量、支持超高并发的通用型流式大数据统计系统。
* [Conquery](https://github.com/ingef/conquery)：Conquery是一个强大的基于Web的工具，用于针对大型事件类数据集编写和执行查询。
* [Apache Crail](https://github.com/apache/incubator-crail)：Apache Crail是一个快速的多层分布式存储系统，专为高性能网络和存储硬件而设计，由IBM开源。

#### 数据可视化

* [KNIME](https://github.com/knime/knime-core)：KNIME是由德国的康斯坦茨大学，一组研究制药应用的开发团队在2006年7月推出的一款针对大数据的软件。
* [Davinci](https://github.com/edp963/davinci)：Davinci是一个DVaaS平台解决方案，面向业务人员/数据工程师/数据分析师/数据科学家，致力于提供一站式数据可视化解决方案，由宜信开源。
* [DataCap](https://github.com/devlive-community/datacap)：DataCap是用于数据转换、集成和可视化的集成软件，由Devlive社区开源。
* [Prefuse](https://github.com/prefuse/Prefuse)：Prefuse是一个基于Java的工具包，用于构建交互式信息可视化应用程序，Prefuse支持一组丰富的数据建模、可视化和交互功能，由加州大学伯克利分校开源。
* [ECharts](https://gitee.com/free/ECharts)：ECharts是针对ECharts 2.X版本的Java类库，实现了所有ECharts中的JSON结构对应的Java对象，并且可以很方便的创建Option、Series等。
* [ECharts Java](https://github.com/ECharts-Java/ECharts-Java)：ECharts Java是一个轻量级但全面的库，供Java开发人员轻松使用JavaScript可视化库ECharts。
* [Mirador](https://github.com/mirador/mirador)：Mirador是一种通过视觉探索在复杂数据集中识别新假设的工具，由斯坦福联合哈佛大学、美国国家美术馆和其他几家世界各地的机构共同进行扩展开发。
* [Ananas](https://github.com/ananas-analytics/ananas-desktop)：Ananas是一款可破解的数据集成/分析工具，使非技术用户能够编辑数据处理作业并按需可视化数据。
* [Datart](https://github.com/running-elephant/datart)：Datart是新一代数据可视化开放平台，支持各类企业数据可视化场景需求,如创建和使用报表、仪表板和大屏，进行可视化数据分析，构建可视化数据应用等，由宜信开源。
* [Hillview](https://github.com/vmware-archive/hillview)：Hillview是一种基于云的服务，用于以交互方式可视化大型数据集，由VMWare开源。
* [DataEase](https://github.com/dataease/dataease)：DataEase是开源的数据可视化分析工具，帮助用户快速分析数据并洞察业务趋势，从而实现业务的改进与优化，由飞致云开源。
* [DataGear](https://gitee.com/datagear/datagear)：DataGear是一款开源免费的数据可视化分析平台，支持接入SQL、CSV、Excel、HTTP接口、JSON等多种数据源，由溪歌科技开源。
* [FlyFish](https://gitee.com/CloudWise/fly-fish)：FlyFish是一个数据可视化编码平台，通过简易的方式快速创建数据模型，通过拖拉拽的形式，快速生成一套数据可视化解决方案，云智慧开源。
* [Dex](https://github.com/PatMartin/Dex)：Dex是数据科学的强大工具，它是在JavaFX之上用Groovy和Java编写的数据可视化工具，能够进行强大的ETL和发布Web可视化。
* [LJV](https://github.com/atp-mipt/ljv)：LJV是使用Graphviz可视化Java数据结构的工具，由莫斯科物理技术学院开源。
* [Twig](https://github.com/gavalian/groot)：Twig是用纯Java编写的强大的数据分析和可视化工具。
* [Sigbla](https://github.com/sigbla/sigbla-app)：Sigbla是一个使用Kotlin编程语言处理表中数据的框架，它支持各种数据类型、响应式编程和事件、用户输入、图表等。
* [Lumify](https://github.com/lumifyio/lumify)：Lumify是一个开源大数据分析和可视化平台。
* [VisNow](https://gitlab.com/visnow.org/VisNow)：VisNow是Java中的通用可视化框架，由华沙大学开发，它是一个模块化数据流驱动平台，使用户能够创建数据可视化、可视化分析、数据处理和简单模拟的方案。
* [Moonbox](https://github.com/running-elephant/moonbox)：Moonbox基于“数据虚拟化”概念设计，旨在提供批量和交互式计算服务，由宜信开源。
* [Data2viz](https://github.com/data2viz/data2viz)：Data2viz是Kotlin多平台的数据可视化工具库。
* [McIDAS-V](https://www.ssec.wisc.edu/%7Ebillh/visad.html)：McIDAS-V是一款免费、开源、可视化和数据分析软件包，是SSEC 50年复杂McIDAS软件包历史中的下一代产品，由威斯康星大学麦迪逊分校开源。
* [TelemetryViewer](https://github.com/farrellf/TelemetryViewer)：TelemetryViewer是一个数据可视化工具。
* [MDSplus](https://github.com/MDSplus/mdsplus)：MDSplus是一套用于数据采集和存储的软件工具，以及管理复杂科学数据的方法，由麻省理工学院、意大利帕多瓦聚变研究小组和洛斯阿拉莫斯国家实验室联合开发。
* [AAChartCore](https://github.com/AAChartModel/AAChartCore)：AAChartCore是AAChartKit的Java语言版本，基于流行的开源前端图表库Highcharts的一套易于使用、极其优雅的图形绘制控件。
* [Super Mjograph](https://www.mjograph.net/)：Mjograph是一款在Mac OSX和Java上运行的XY(2D)图形编辑器，旨在为研究人员提供一种快速的方法来可视化数值数据并创建出版质量的绘图。
* [ALITA](https://github.com/didi/ALITA)：ALITA是一个基于层的数据分析工具，由滴滴开源。

#### 数据目录

* [DataHub](https://github.com/datahub-project/datahub)：DataHub是现代数据堆栈的开源元数据平台，由LinkedIn开源。
* [Metacat](https://github.com/Netflix/metacat)：Metacat是一个联合的元数据API服务，可以访问Hive、RDS、Teradata、Redshift、S3和Cassandra，由Netflix开源。
* [Apache Polaris](https://github.com/apache/polaris)：Polaris是Iceberg的开源、功能齐全的目录，由Snowflake开发。
* [Marquez](https://github.com/MarquezProject/marquez)：Marquez是一种开源元数据服务，用于数据生态系统元数据的收集、聚合和可视化，由WeWork开源。
* [Apache Atlas](https://github.com/apache/atlas)：Atlas是一组可扩展的核心基础治理服务-使企业能够有效地满足Hadoop内的合规性要求，并允许与整个企业数据生态系统集成，由Hortonworks开源。
* [OpenMetadata](https://github.com/open-metadata/OpenMetadata)：OpenMetadata是一个开源元数据存储库，由Uber元数据基础架构背后的团队构建。
* [Open Data Discovery](https://github.com/opendatadiscovery/odd-platform)：Open Data Discovery是一款面向数据团队的开源数据发现和可观察性工具，由Provectus开源。
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog)：Unity Catalog是最开放、可互操作的数据和AI目录，由Databricks开源。
* [Apache Gravitino](https://github.com/apache/gravitino)：Gravitino是一个高性能、地理分布式、联合元数据湖，由Datastrato开源。
* [Magda](https://github.com/magda-io/magda)：Magda是适用于所有大数据和小数据的联合开源数据目录，由澳大利亚联邦科学与工业研究组织的Data61和澳大利亚总理及内阁部发起。
* [Lightning Catalog](https://github.com/zetaris/lightning-catalog)：Lightning Catalog是Zetaris开源的数据目录，用于在临时分析、数据仓库、Lake House和ML项目中准备任意规模的数据。

#### 查询引擎

* [Apache Hive](https://github.com/apache/hive)：Hive是一种分布式容错数据仓库系统，可实现大规模分析，并有助于使用SQL读取、写入和管理分布式存储中的PB级数据，由Facebook开源。
* [Trino](https://github.com/trinodb/trino)：Trino是一个用于大数据分析的快速分布式SQL查询引擎，由Starburst开源。
* [Presto](https://github.com/prestodb/presto)：Presto是一个用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Apache Phoenix](https://github.com/apache/phoenix)：Phoenix是基于HBase的SQL皮肤，作为客户端嵌入的JDBC驱动程序提供，旨在针对HBase数据的低延迟查询，由Salesforce开源。
* [XSQL](https://github.com/Qihoo360/XSQL)：XSQL是一个多数据源查询引擎，设计简单易用，运行稳定，由360开源。
* [Blaze](https://github.com/kwai/blaze)：Blaze加速器利用本机矢量化执行来加速查询处理，由快手开源。
* [Gimel](https://github.com/paypal/gimel)：Gimel提供统一的数据API来访问来自任何存储的数据，由Paypal开源。
* [TrainDB](https://github.com/traindb-project/traindb)：TrainDB是一个基于ML的近似查询处理引擎，旨在在几秒钟内回答耗时的分析查询，由延世大学、光云大学、ETRI、RealTimeTech、BI Matrix开源。
* [RumbleDB](https://github.com/RumbleDB/rumble)：RumbleDB是一个查询引擎，可让你轻松高效地查询大型、混乱的数据集，由苏黎世联邦理工学院开源。
* [SquashQL](https://github.com/squashql/squashql)：SquashQL是一个开源SQL查询引擎，旨在简化构建多维查询的过程。
* [Luwak](https://github.com/flaxsearch/luwak)：Luwak基于开源Lucene搜索库，是一个高性能的存储查询引擎。
* [Splice Machine](https://github.com/splicemachine/spliceengine)：Splice Machine是一个融合关系型数据库与大数据分析的平台，支持事务处理和分析查询。

#### 存储格式

* [Apache ORC](https://github.com/apache/orc)：ORC是一种自描述、类型感知的列式文件格式，专为Hadoop工作负载而设计，由Hortonworks和Facebook联合开发。
* [Arrow Java](https://github.com/apache/arrow-java)：Arrow是一种通用的列式格式和多语言工具箱，用于快速数据交换和内存分析。
* [Apache Parquet](https://github.com/apache/parquet-java)：Parquet是Hadoop生态系统中的任何项目都可以使用的列式存储格式，由Twitter和Cloudera共同开源。
* [Yosegi](https://github.com/yahoojapan/yosegi)：Yosegi是一种无模式的列式存储格式，提供像JSON一样灵活的表示和类似其他列式存储格式的高效读取，由Yahoo开源。
* [GraphAr](https://github.com/apache/incubator-graphar)：GraphAr是一个用于图数据存储和检索的开源标准数据文件格式，由阿里开源。
* [Apache TsFile](https://github.com/apache/tsfile)：TsFile是一种专为时序数据设计的列式存储文件格式，支持高效压缩、读写高吞吐，并且兼容Spark、Flink等多种框架，由清华大学开源。
* [IndexR](https://github.com/shunfei/indexr)：IndexR是HDFS上的超快速列式数据格式，专注于快速分析，既适用于海量静态(历史)数据，也适用于快速摄取实时数据，由舜飞开源。
* [TrinityLake](https://github.com/trinitylake-io/trinitylake)：TrinityLake格式定义了Lakehouse中的对象，并提供了一种一致且高效的方式来访问和操作这些对象。

#### 流处理平台

* [Apache Flink](https://github.com/apache/flink)：Flink是一个开源流处理框架，具有强大的流处理和批处理能力，由柏林工业大学发起。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：RocketMQ是一个分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：Kafka是一个开源分布式事件流平台，已被数千家公司用于高性能数据管道、流分析、数据集成和关键任务应用程序，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：Pulsar是一个分布式Pub-Sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API，由Yahoo开源。
* [Apache Storm](https://github.com/apache/storm)：Storm是一个免费开源的分布式实时计算系统，由Twitter开源。
* [Mantis](https://github.com/Netflix/mantis)：Mantis是一个用于构建流处理应用程序(作业)的平台，Netflix开源。
* [Apache Beam](https://github.com/apache/beam)：Beam是一个用于定义批处理和流数据并行处理管道的统一模型，由Google开源。
* [Hazelcast](https://github.com/hazelcast/hazelcast)：Hazelcast是一个实时流处理平台，可让你构建立即对数据采取操作的应用程序，由Hazelcast开源。
* [JStorm](https://github.com/alibaba/jstorm)：JStorm是参考Storm基于Java语言重写的实时流式计算系统框架，由阿里开源。
* [Apache Heron](https://github.com/apache/incubator-heron)：Heron是Twitter开源的一个实时的、容错的、分布式的流数据处理系统。
* [Apache StreamPark](https://github.com/apache/incubator-streampark)：StreamPark是一个流处理开发框架和应用程序管理平台，由个人组织StreamXHub创建。
* [Dinky](https://github.com/DataLinkDC/dinky)：Dinky是一个开箱即用的一站式实时计算平台，致力于统一流批处理、统一数据湖和数据仓库的构建和实践。
* [JetStream](https://github.com/pulsarIO/jetstream)：JetStream是一种实时流处理系统，用于分析实时事件流，由eBay开源。
* [Summingbird](https://github.com/twitter/summingbird)：Summingbird是Twitter开源的一个库，可让你编写类似于原生Scala或Java集合转换的MapReduce程序，并在许多著名的分布式MapReduce平台(包括Storm和Scalding)上执行它们。
* [JournalKeeper](https://github.com/jd-opensource/journalkeeper)：JournalKeeper是一个高性能、高可靠、强一致的分布式流数据存储集群，京东开源。
* [Apache Gobblin](https://github.com/apache/gobblin)：Gobblin是一种分布式数据集成框架，可简化大数据集成的常见方面，例如流数据和批处理数据生态系统的数据摄取、复制、组织和生命周期管理，由LinkedIn开源。
* [Pravega](https://github.com/pravega/pravega)：Pravega是一种开源流存储系统，可实现流并充当用于存储或提供连续、无界数据的出色基元，由DELL开源。
* [AthenaX](https://github.com/uber-archive/AthenaX)：AthenaX是一个流分析平台，使用户能够使用SQL运行生产质量的大规模流分析，由Uber开源。
* [Jet](https://github.com/hazelcast/hazelcast-jet)：Jet是一个开源、内存中、分布式批处理和流处理引擎，由Hazelcast开源。
* [Fluss](https://github.com/alibaba/fluss)：Fluss是一个专为实时分析而构建的流存储，可以作为Lakehouse架构的实时数据层，由阿里开源。
* [Apama](https://cumulocity.com/apama/docs/latest/)：Apama是一个事件处理平台，它监控快速移动的事件流，检测和分析重要事件和事件模式，并根据你的规范立即对感兴趣的事件采取行动。
* [FlinkStreamSQL](https://github.com/DTStack/flinkStreamSQL)：FlinkStreamSQL基于Flink对其实时SQL进行扩展,主要实现了流与维表的join，支持原生Flink SQL所有的语法，由袋鼠云开源。
* [Apache Samza](https://github.com/apache/samza)：Samza是一个分布式流处理框架，它使用Kafka进行消息传递，并使用Hadoop YARN提供容错、处理器隔离、安全性和资源管理，由LinkedIn开源。
* [Siddhi](https://github.com/siddhi-io/siddhi)：Siddhi是一个云原生流式处理和复杂事件处理引擎。
* [StreamFlow](https://github.com/lmco/streamflow)：StreamFlow是一种流处理工具，旨在帮助构建和监控处理工作流，这是洛克希德马丁公司的开源项目。
* [Apache Nemo](https://github.com/apache/incubator-nemo)：Nemo是一个用于分布式数据流处理的优化框架，它为高性能提供了精细的控制，同时也确保了正确性，由首尔大学开源。
* [NeonBee](https://github.com/SAP/neonbee)：NeonBee是一个开源的响应式数据流引擎，是一个使用Vert.x的数据流处理框架，由SAP开源。
* [Streamis](https://github.com/WeBankFinTech/Streamis)：Streamis是微众银行、天翼云、仙翁科技和萨摩耶云联合共建的流式应用开发管理系统。
* [Wormhole](https://github.com/edp963/wormhole)：Wormhole是一个一站式流式处理云平台解决方案，由宜信开源。
* [LogIsland](https://github.com/Hurence/logisland)：LogIsland是一个事件挖掘可扩展平台，旨在处理高吞吐量的事件，由Hurence开源。
* [Stream Registry](https://github.com/ExpediaGroup/stream-registry)：Stream Registry是一个流发现和流编排服务，由Expedia开源。
* [Tigon](https://github.com/cdapio/tigon)：Tigon是一个开源、实时、低延迟、高吞吐量的流处理框架，由Google开源。
* [Sparta](https://github.com/Stratio/sparta)：Sparta是基于Spark Streaming的实时分析和数据管道，由Stratio开源。
* [Gearpump](https://github.com/gearpump/gearpump)：Gearpump是一个轻量级的实时大数据流引擎，由Intel开源。
* [BeepBeep](https://github.com/liflab/beepbeep-3)：BeepBeep是一个事件流查询引擎，由魁北克大学开源。
* [Cloudflow](https://github.com/lightbend/cloudflow)：Cloudflow使用户能够在Kubernetes上快速开发、编排和操作分布式流应用程序，由Lightbend开源。

#### ETL工具

* [Apache SeaTunnel](https://github.com/apache/seatunnel)：SeaTunnel是新一代高性能分布式数据集成工具，能够每天同步海量数据，由中国通信学会开源技术委员会发起的项目。
* [Addax](https://github.com/wgzhao/Addax)：Addax是一个异构数据源离线同步工具，最初来源于阿里的DataX ，致力于实现包括关系型数据库(MySQL、Oracle 等)、HDFS、Hive、HBase、FTP等各种异构数据源之间稳定高效的数据同步功能。
* [TIS](https://github.com/datavane/tis)：TIS集成大数据领域优秀组件(FlinkX-CDC，Chunjun，DataX，Flink等)为你提供一站式、开箱即用的DataOps数据中台，大幅提高ETL实时数仓构建效率，由Datavane大数据组织开源。
* [Exchangis](https://github.com/WeBankFinTech/Exchangis)：Exchangis是微众银行大数据平台与社区用户共同开发的新版数据交换工具，支持异构数据源之间结构化和非结构化数据的同步传输。
* [Smooks](https://github.com/smooks/smooks)：Smooks是一个可扩展的Java框架，用于构建基于XML和非XML数据(CSV、EDI、POJO等)的基于片段的应用程序。
* [Kafka Connect File Pulse](https://github.com/streamthoughts/kafka-connect-file-pulse)：Connect FilePulse是一种多用途、可扩展且可靠的Kafka连接器，可以轻松解析、转换任何格式的任何文件并将其流式传输到Kafka，由StreamThoughts开源。
* [Extract](https://github.com/ICIJ/extract)：Extract是用于并行、分布式内容提取的跨平台命令行工具，由国际调查记者联盟开源。
* [Bender](https://github.com/Nextdoor/bender)：该项目提供了一个可扩展的Java框架，用于在AWS Lambda上创建Serverless ETL函数，Bender处理复杂的管道并提供为ETL过程的各个方面构建模块所需的接口。
* [Orbital](https://github.com/orbitalapi/orbital)：Orbital是一个数据网关，可自动集成、转换和发现整个企业中数据源(API、数据库、消息代理)的数据。
* [LinkMove](https://github.com/nhl/link-move)：LinkMove是一个模型驱动的动态可配置框架，用于从外部源获取数据并将其保存在数据库中，由北美职业冰球联盟开源。
* [Lithium](https://www.atlassian.com/blog/atlassian-engineering/lithium)：Lithium是Atlassian内部使用的ETL平台，旨在满足动态数据移动的要求。
* [SETL](https://github.com/SETL-Framework/setl)：SETL是一个由Apache Spark提供支持的Scala ETL框架，可帮助你构建Spark ETL项目、模块化数据转换逻辑并加快开发速度。
* [Envelope](https://github.com/cloudera-labs/envelope)：Envelope是Apache Spark的配置驱动框架，可以轻松开发基于Spark的数据处理管道，由Cloudera开发。
* [PolarDB-X CDC](https://github.com/polardb/polardbx-cdc)：PolarDB-X CDC是PolarDB-X的核心组件，负责全局二进制日志的生成、发布和订阅，由阿里开源。
* [QStreaming](https://github.com/qiniu/QStreaming)：QStreaming是一个简化在Apache Spark上编写和执行ETL的框架，由七牛云开发。
* [Hydrograph](https://github.com/BitwiseInc/Hydrograph)：Hydrograph是一款功能强大的ETL工具，允许开发人员使用简单的拖放界面创建复杂的图表。
* [DataExpress](https://github.com/chop-dbhi/dataexpress)：DataExpress是一个简单、基于Scala的跨数据库ETL工具包，支持Postgres、MySql、Oracle、SQLServer和SQLite，由费城儿童医院开源。
* [LinkedPipes ETL](https://github.com/linkedpipes/etl)：LinkedPipes ETL是一个基于RDF的轻量级ETL工具。
* [FHIR Data Pipes](https://github.com/google/fhir-data-pipes)：该仓库包括使用FHIR格式将来自FHIR服务器(例如HAPI、GCP FHIR存储，甚至OpenMRS)的数据转换为基于Parquet文件或其他FHIR服务器的数据仓库的管道，由Google开源。
* [Talend Open Studio](https://github.com/Talend/tcommon-studio-se)：Talend Open Studio可以使你立即开始构建基本数据管道，从你控制的本地安装的开源环境中执行简单的ETL和数据集成任务，获取数据的图形配置文件并管理文件。
* [Kettle](https://github.com/pentaho/pentaho-kettle)：Kettle是一款开源的ETL工具，可以用它来对数据进行抽取、清洗和转换操作，主作者是Matt Casters。
* [Smart Kettle](https://gitee.com/yaukie/smartkettle)：Smart Kettle是基于开源Kettle自研的Kettle核心接口调用基础组件。
* [Scriptella](https://github.com/scriptella/scriptella-etl)：Scriptella是一个用Java编写的开源ETL和脚本执行工具。
* [Apatar](https://www.altoros.com/blog/tag/apatar/)：Apatar是一个开源的数据抽取、转换、装载(ETL)项目。
* [Flowman](https://github.com/dimajix/flowman)：Flowman是一个由Spark支持的ETL框架，简化了复杂数据管道的开发。
* [WhiteRabbit](https://github.com/OHDSI/WhiteRabbit)：WhiteRabbit是一个小型应用程序，可用于分析数据库的结构和内容，为设计ETL做准备，由OHDSI开源。
* [DataPull](https://github.com/homeaway/datapull)：DataPull是一种自助式分布式ETL工具，用于连接和转换来自异构数据存储的数据。
* [Metorikku](https://github.com/YotpoLtd/metorikku)：Metorikku是一个简化在Apache Spark上编写和执行ETL的库。

#### CDC组件

* [Flink CDC](https://github.com/apache/flink-cdc)：Flink CDC是一个针对实时数据和批量数据的分布式数据集成工具，阿里开源。
* [Databus](https://github.com/linkedin/databus)：Databus是一个与源无关的分布式变更数据捕获系统，它是LinkedIn数据处理管道的组成部分。
* [Maxwell](https://github.com/zendesk/maxwell)：Maxwell是一个CDC应用程序，它读取MySQL二进制日志并将数据变更以JSON形式写入Kafka、Kinesis和其他流平台，由Zendesk开源。
* [Debezium](https://github.com/debezium/debezium)：Debezium是一个开源项目，为CDC提供低延迟数据流平台，由RedHat开源。
* [Oracdc](https://github.com/averemee-si/oracdc)：Oracdc是一个用于异构IT环境中近实时数据集成和复制的软件包，由Oracle开源。
* [TiBigData](https://github.com/tidb-incubator/TiBigData)：适用于TiDB、Presto、Flink和MapReduce连接器的其他大数据组件。
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [SpinalTap](https://github.com/airbnb/SpinalTap)：SpinalTap是一种通用的CDC服务，能够跨不同数据源低延迟地检测数据突变，并将其作为标准化事件传播给下游消费者，由Airbnb开源。
* [ACDC](https://github.com/xdfdotcn/acdc)：ACDC是新东方集团架构部开源的数据平台产品。
* [SyncLite](https://github.com/syncliteio/SyncLite)：SyncLite是一个开源、低代码、全面的关系数据整合平台，可帮助开发人员快速构建用于边缘、桌面和移动环境的数据密集型应用程序。

#### Notebook

* [Polynote](https://github.com/polynote/polynote)：Polynote是一个实验性多语言笔记本环境，由Netflix开源。
* [Apache Zeppelin](https://github.com/apache/zeppelin)：Zeppelin是一款基于Web的笔记本，支持交互式数据分析，由韩国公司ZEPL开源。

#### 数据同步

* [ChunJun](https://github.com/DTStack/chunjun)：ChunJun是基于Flink的批流统一打造的数据同步工具，可以实现各种异构数据源之间的数据同步和计算，由袋鼠云开源。
* [DataX](https://github.com/alibaba/DataX)：DataX是阿里云DataWorks数据集成的开源版本，在阿里内被广泛使用的离线数据同步工具/平台。
* [DataX Web](https://github.com/WeiYe-Jing/datax-web)：DataX Web是在DataX之上开发的分布式数据同步工具，提供简单易用的操作界面。
* [Porter](https://gitee.com/sxfad/porter)：Porter是一款数据同步中间件，主要用于解决同构/异构数据库之间的表级别数据同步问题，由随行付开源。
* [Tunnel](https://github.com/hellobike/tunnel)：Tunnel是一个将PostgreSQL的实时数据同步到ES或Kafka的服务，哈啰单车开源。
* [DBSyncer](https://gitee.com/ghi/dbsyncer)：DBSyncer是一款开源的数据同步中间件，提供MySQL、Oracle、SqlServer、PostgreSQL、ES、Kafka、File、SQL等同步场景。
* [Otter](https://github.com/alibaba/otter)：Otter是阿里开源的一个分布式数据库同步系统，尤其是在跨机房数据库同步方面有很强大的功能。
* [Puma](https://github.com/dianping/puma)：Puma可以获取数据库的变更并通过消息方式发布，并且可以实现数据库同步，由大众点评开源。
* [Yugong](https://github.com/alibaba/yugong)：Yugong是阿里开源的去Oracle数据迁移同步工具。
* [Tapdata](https://github.com/tapdata/tapdata)：Tapdata是一个实时数据集成平台，可以实现数据库、SaaS服务、应用程序、文件等各种系统之间的数据实时同步，由钛铂数据开源。
* [SymmetricDS](https://github.com/JumpMind/symmetric-ds)：SymmetricDS是数据库复制和文件同步软件，它独立于平台、支持Web且与数据库无关，由JumpMind开源。
* [DataLink](https://github.com/ucarGroup/DataLink)：DataLink是一个满足各种异构数据源之间的实时增量同步、离线全量同步，分布式、可扩展的数据交换平台，由神州优车开源。
* [DBSwitch](https://gitee.com/dromara/dbswitch)：DBSwitch工具提供源端数据库向目的端数据库的批量迁移同步功能，支持数据的全量和增量方式同步，由dromara社区开源。
* [Mongeez](https://github.com/mongeez/mongeez)：Mongeez允许你管理Mongo文档的更改，并在执行部署时与代码更改同步传播这些更改。
* [Redis Replicator](https://github.com/leonchen83/redis-replicator)：Redis Replicator是一个Redis复制工具，支持同步、psync、psync2，可以解析RDB、AOF、混合RDB和AOF文件。
* [RedisSyncer](https://github.com/TraceNature/redissyncer-server)：RedisSyncer是一个Redis多任务同步工具集，应用于Redis单实例及集群同步。
* [MyDataHarbor](https://gitee.com/mydataharbor/mydataharbor)：MyDataHarbor是一个致力于解决异构数据源之间的分布式、高扩展性、高性能、事务级的数据同步中间件。
* [Canal MySQL NoSQL Sync](https://github.com/liukelin/canal_mysql_nosql_sync)：基于Canal的MySQL、RabbitMQ、Redis/Memcached/MongoDB同步工具。
* [AMPLI-SYNC](https://github.com/sqlite-sync/SQLite-sync.com)：AMPLI-SYNC是一个用于在Sqlite和MS SQL/MySQL/Oracle/PostgreSQL数据库之间同步数据的框架。
* [DatalinkX](https://github.com/SplitfireUptown/datalinkx)：基于Flink的异构数据源同步。

#### 数据湖框架

* [Apache Hudi](https://github.com/apache/hudi)：Hudi是一个事务性数据湖平台，可为数据湖带来数据库和数据仓库功能，由Uber开源。
* [LakeSoul](https://github.com/lakesoul-io/LakeSoul)：LakeSoul是一个云原生Lakehouse框架，支持可扩展的元数据管理、ACID事务、高效灵活的更新插入操作、模式演化以及统一的流和批处理，由数元灵科技开源。
* [Apache Paimon](https://github.com/apache/paimon)：Paimon是一种Lake格式，可以使用Flink和Spark构建实时Lakehouse架构，以进行流式处理和批处理操作。
* [Apache Iceberg](https://github.com/apache/iceberg)：Iceberg是一种适用于大型分析表的高性能格式，由Netflix开源。
* [Delta](https://github.com/delta-io/delta)：Delta Lake是一个开源存储框架，支持使用Spark、PrestoDB、Flink、Trino和Hive等计算引擎以及Scala、Java、Rust、Ruby和Python的API构建Lakehouse架构，由Databricks开源。
* [Kylo](https://github.com/Teradata/kylo)：Kylo是一个企业级现代数据湖管理软件平台，适用于Teradata、Spark或Hadoop等大数据引擎，由Teradata开源。
* [Nessie](https://github.com/projectnessie/nessie)：Nessie使你能够维护数据的多个版本，并为你的数据湖利用类似Git的分支和标签，由Dremio团队开源。
* [Amoro](https://github.com/apache/amoro)：Amoro是一个基于开放数据湖格式构建的Lakehouse管理系统，由网易开源。
* [Herd](https://github.com/FINRAOS/herd)：Herd是云的大数据治理，Herd统一数据目录有助于将云中的存储与计算分开，由美国金融业监管局开源。
* [Dremio](https://github.com/dremio/dremio-oss)：Dremio是一个开源且简单的数据湖库，提供自助式SQL分析、数据仓库性能和功能以及涵盖所有数据的数据湖灵活性。
* [OpenHouse](https://github.com/linkedin/openhouse)：OpenHouse是一个开源控制平面，旨在高效管理开放数据Lakehouse部署中的表，由LinkedIn开源。
* [Pixels](https://github.com/pixelsdb/pixels)：Pixels的核心是专为数据湖和数据仓库设计的列式存储引擎，由中国人民大学开源。
* [Apache XTable](https://github.com/apache/incubator-xtable)：XTable是一种表格式的跨表转换器，可促进跨数据处理系统和查询引擎的全方位互操作性，由Onehouse开源。
* [RTF](https://github.com/jd-bigdata/rtf-lake)：京东RTF实时数据湖，是一个从底层重新构建的系统，解决了数据的接入、解析及清洗等ETL过程。

#### 数据Shuffle

* [Apache Celeborn](https://github.com/apache/incubator-celeborn)：Celeborn是一种弹性且高性能的服务，用于洗牌和溢出数据，由阿里云开源。
* [Apache Uniffle](https://github.com/apache/incubator-uniffle)：Uniffle是一种用于分布式计算引擎的高性能、通用远程洗牌服务，由腾讯开源。
* [Shuttle](https://github.com/cubefs/shuttle)：Shuttle提供远程Shuffle功能，可以按分区将Shuffle数据分组并转储到分布式文件系统中，由OPPO大数据团队开源。
* [Remote Shuffle Server](https://github.com/uber/RemoteShuffleService)：Uber Remote Shuffle Server为Spark应用程序提供了在远程服务器上存储Shuffle数据的功能。
* [Cloud Shuffle Service](https://github.com/bytedance/CloudShuffleService)：Cloud Shuffle Service是适用于计算引擎(包括Spark/Flink/MapReduce)的通用远程Shuffle解决方案，由字节开源。

## 进程间通信

#### 消息中间件

* [Amazon SQS](https://aws.amazon.com/cn/sqs/)：Amazon SQS是亚马逊公司在2004年推出的分布式消息队列服务。
* [Apache Kafka](https://github.com/apache/kafka)：Kafka是一个开源分布式事件流平台，已被数千家公司用于高性能数据管道、流分析、数据集成和关键任务应用程序，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：Pulsar是一个分布式Pub-Sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API，由Yahoo开源。
* [Apache ActiveMQ](https://github.com/apache/activemq)：ActiveMQ是一个高性能的消息代理。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：RocketMQ是一个分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性，由阿里开源。
* [QMQ](https://github.com/qunarcorp/qmq)：QMQ是去哪儿网内部广泛使用的消息中间件。
* [PMQ](https://github.com/ppdaicorp/pmq)：PMQ是信也科技自研的一款轻量级分布式消息队列，能够保证消息的不丢失，具有部署和运维简单的特性。
* [IBM MQ](https://www.ibm.com/products/mq)：IBM MQ是一个中间件产品系列，用于点对点和发布-订阅消息传递。
* [JeroMQ](https://github.com/zeromq/jeromq)：JeroMQ是ZeroMQ的纯Java实现，由iMatix开源。
* [TubeMQ](https://github.com/apache/inlong/tree/master/inlong-tubemq)：TubeMQ是一个万亿级分布式消息中间件，由腾讯大数据团队开源。
* [AutoMQ](https://github.com/AutoMQ/automq)：AutoMQ是基于云原生重新设计的新一代Kafka发行版，由阿里提供。
* [DDMQ](https://github.com/didi/DDMQ)：DDMQ是滴滴基础设施团队基于RocketMQ打造的分布式消息产品。
* [PSMQ](https://bitbucket.org/atlassian/psmq)：PSMQ是一个非常简单的消息队列系统，由Atlassian开发。
* [Nydus](https://www.infoq.cn/article/2_d683szyss0pjmdkxg2)：Nydus是网易云基于RocketMQ开发的消息队列。
* [BifroMQ](https://github.com/baidu/bifromq)：BifroMQ是一种高性能、分布式MQTT代理实现，可无缝集成原生多租户支持，由百度开源。
* [JGroups](https://github.com/belaban/JGroups)：JGroups是一个用于可靠消息传递的工具包，它可用于创建节点可以相互发送消息的集群，由RedHat开源。
* [Kestrel](https://github.com/twitter-archive/kestrel)：Kestrel是一个简单分布式消息队列，增加了Actor和JVM提供的可扩展性，由Twitter开源。
* [JoyQueue](https://github.com/jd-opensource/joyqueue)：JoyQueue是一个性能卓越的云原生生产就绪消息平台，由京东开源。
* [HornetQ](https://github.com/hornetq/hornetq)：HornetQ是一个开源项目，用于构建多协议、可嵌入、高性能、集群、异步消息传递系统，由Redhat开发。
* [XXL-MQ](https://gitee.com/xuxueli0323/xxl-mq)：XXL-MQ是一款轻量级分布式消息队列，拥有水平扩展、高可用、海量数据堆积、单机TPS过10万、毫秒级投递等特性。
* [SwiftMQ](https://github.com/iitsoftware/swiftmq-ce)：SwiftMQ CE是一个功能齐全的企业消息传递系统。
* [OpenMessaging](https://github.com/openmessaging/openmessaging-java)：OpenMessaging是由阿里发起，由Yahoo、滴滴、Streamlio、微众、Datapipeline等公司共同创建的分布式消息规范。
* [Metamorphosis](https://github.com/killme2008/Metamorphosis)：Metamorphosis是淘宝开源的一个Java消息中间件。
* [ElasticMQ](https://github.com/softwaremill/elasticmq)：ElasticMQ是一个消息队列系统，提供基于Actor的Scala和SQS兼容的REST接口，由SoftwareMill开源。
* [Hermes](https://github.com/ctripcorp/hermes)：携程异步消息队列解决方案。
* [Eclipse OpenMQ](https://github.com/eclipse-ee4j/openmq)：OpenMQ是一个完整的面向消息的中间件平台，提供高质量、企业级消息传递。
* [JORAM](https://joram.ow2.io/)：JORAM是JMS API规范的开源Java实现(符合Java 11至21以及JMS 1.1、2.0和3.0)，由格勒诺布尔大学开源。
* [Hermes](https://github.com/allegro/hermes)：Hermes是一个构建在Kafka之上的异步消息代理，由波兰最大电商Allegro开源。
* [Apache Qpid](https://github.com/apache/qpid)：Qpid是一个功能强大的开源消息代理，由摩根大通开源。
* [Axon Server](https://github.com/AxonIQ/axon-server-se)：Axon Server是Axon定制的可扩展且高度可用的事件存储和消息传递系统。
* [MemQ](https://github.com/pinterest/memq)：MemQ是高效、可扩展的云原生PubSub系统，由Pinterest开源。
* [LCM](https://github.com/lcm-proj/lcm)：LCM是一组用于消息传递和数据编组的库和工具，针对高带宽和低延迟至关重要的实时系统，由MIT开源。
* [DeFiBus](https://github.com/WeBankFinTech/DeFiBus)：DeFiBus是基于开源消息中间件打造的安全可控的分布式金融级消息总线，由微众开源。
* [Ytk-mp4j](https://github.com/kanyun-inc/ytk-mp4j)：Ytk-mp4j是一个快速、用户友好、跨平台、多进程、多线程的集体消息传递Java库，用于分布式机器学习，由看云控股技术团队开源。
* [FolkMQ](https://gitee.com/noear/folkmq)：FolkMQ内存型消息中间件，支持快照持久化和Broker集群模式。

#### 事件总线

* [EventBus](https://github.com/greenrobot/EventBus)：EventBus是适用于Android和Java的发布/订阅事件总线。
* [WeEvent](https://github.com/WeBankBlockchain/WeEvent)：WeEvent是一套分布式事件驱动架构，实现了可信、可靠、高效的跨机构、跨平台事件通知机制，由微众银行开源。
* [EventBus](https://github.com/MinecraftForge/EventBus)：EventBus是一个简单的订阅者-发布者框架。
* [MBassador](https://github.com/bennidi/mbassador)：MBassador是一个轻量级、高性能的事件总线，实现了发布订阅模式。
* [Otto](https://github.com/square/otto)：Otto是一种事件总线，旨在解耦应用程序的不同部分，同时仍然允许它们高效通信，由Square开源。
* [RxBus](https://github.com/AndroidKnife/RxBus)：RxBus是一个事件总线，旨在让你的应用程序有效地进行通信。
* [HermesEventBus](https://github.com/Xiaofei-it/HermesEventBus)：HermesEventBus是一个在进程之间使用EventBus的库，在IPC或插件开发中很有用。
* [AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)：AndroidEventBus是适用于Android的轻量级事件总线库，简化了Activity、Fragments、Threads、Services等之间的通信。
* [Nakadi](https://github.com/zalando/nakadi)：Nakadi是一个分布式事件总线代理，它在类似Kafka的队列之上实现了RESTful API抽象，可用于以可靠且高度可用的方式实时发送、接收和分析流数据，由Zalando开源。
* [Alpine](https://github.com/ZeroMemes/Alpine)：Alpine是适用于Java 8+的轻量级事件系统。
* [Events4J](https://github.com/PhilippHeuer/events4j)：Java事件调度程序/消费者。
* [DamiBus](https://gitee.com/noear/dami)：DamiBus专为本地多模块之间通讯解耦而设计。
* [IPC EventBus](https://github.com/Terracotta-OSS/ipc-eventbus)：IPC EventBus为JVM内和JVM外通信提供了一个简单的EventBus API。

#### 消息总线

* [Chronicle Queue](https://github.com/OpenHFT/Chronicle-Queue)：Chronicle Queue是一个适用于高性能应用程序的持久低延迟消息传递框架，由Chronicle软件公司开源。
* [Aeron](https://github.com/real-logic/Aeron)：Aeron是一个开源高性能消息传输机制(单向)，支持高效可靠的UDP单播、UDP多播和IPC消息传输，由Adaptive公司开源。
* [Mappedbus](https://github.com/caplogic/Mappedbus)：Mappedbus是一种用于利用共享内存的Java微服务的低延迟消息总线。
* [CoralSequencer](https://www.coralblocks.com/index.php/category/coralsequencer/)：CoralSequencer是一款功能齐全、超低延迟、全序消息传递中间件，适用于基于异步消息的分布式系统。
* [EBus](https://ebus.sourceforge.io/eBus)：EBus是一个Java中间件API，支持无代理、基于类型+主题的发布/订阅和请求/回复消息传递，用于应用程序内和应用程序间的对象级通信。
* [Spring Cloud Bus](https://github.com/spring-cloud/spring-cloud-bus)：Spring Cloud Bus是一种轻量级的消息代理，用于集成和传输微服务之间的消息。
* [LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)：LiveEventBus是一款Android消息总线，基于LiveData，具有生命周期感知能力，支持Sticky、AndroidX、款进程。
* [Varadhi](https://github.com/flipkart-incubator/varadhi)：Varadhi是具有REST接口的消息总线实现，由Flipkart开源。
* [Low Level Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计，包括事件总线。
* [Flux Capacitor](https://github.com/flux-capacitor-io/flux-capacitor-client)：该仓库包含Flux Capacitor服务的官方Java客户端。

#### 应用总线

* [Apache Synapse](https://github.com/apache/synapse)：Synapse是一种轻量级高性能企业服务总线，由WSO2开源。
* [Bus](https://github.com/839128/bus)：Bus是一个基础框架、服务套件，它基于Java 17编写，参考、借鉴了大量已有框架、组件的设计，可以作为后端服务的开发基础中间件。
* [WSO2 ESB](https://github.com/wso2-attic/product-esb)：WSO2 ESB是一款轻量级、高性能、接近零延迟的产品，为SOAP、WS和REST等多种不同技术以及SAP或HL7等特定领域的解决方案和协议提供全面支持。

## 分布式开发

#### 分布式组件

* [Brooklin](https://github.com/linkedin/brooklin)：Brooklin是一个分布式系统，旨在在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，由LinkedIn开发。
* [Hive2Hive](https://github.com/Hive2Hive/Hive2Hive)：Hive2Hive是一个用Java编写的开源库，用于安全、分布式、基于P2P的文件同步和共享。
* [Waltz](https://github.com/wepay/waltz)：Waltz是一种基于仲裁的分布式预写日志，用于复制事务，由WePay开源。
* [Jepsen](https://github.com/jepsen-io/jepsen)：Jepsen致力于提高分布式数据库、队列、共识系统等的安全性。
* [Chronos](https://github.com/XiaoMi/chronos)：Chronos是实现高可用、高性能、提供全局唯一而且严格单调递增Timestamp的服务，由小米开源。
* [Sparrow](https://github.com/radlab/sparrow)：Sparrow是一个高吞吐量、低延迟、容错的分布式集群调度器，由加州大学伯克利分校开源。
* [Onyx](https://github.com/onyx-platform/onyx)：Onyx是一个无主、云规模、容错、高性能分布式计算系统。
* [Redis Session Manager](https://github.com/jcoleman/tomcat-redis-session-manager)：Session管理器实现，将Session存储在Redis中，以便在Tomcat服务器集群中轻松分发请求。
* [Octobot](https://github.com/cscotta/Octobot)：Octobot是一款任务队列工作程序，旨在实现可靠性、易用性和吞吐量。
* [DIZK](https://github.com/scipr-lab/dizk)：DIZK是一个用于分布式零知识证明系统的Java库，由SCIPR实验室开源。
* [Dhalion](https://github.com/microsoft/Dhalion)：Dhalion是一个用于自动扩展和调整分布式系统的框架，由Microsoft开源。
* [OpenMOLE](https://github.com/openmole/openmole)：OpenMOLE提供了利用分布式计算环境来运行、探索、诊断和优化数值模型的工具。
* [ModeShape](https://github.com/ModeShape/modeshape)：ModeShape是一种分布式、分层、事务性和一致的数据存储，支持查询、全文搜索、事件、版本控制、引用以及灵活的动态模式，由RedHat开源。
* [Dempsy](https://github.com/Dempsy/dempsy)：Dempsy是一个用于轻松编写分布式和动态可扩展应用程序的框架。
* [Nepxion Aquarius](https://github.com/Nepxion/Aquarius)：Nepxion Aquarius是一款基于Redis、Zookeeper的分布式应用组件集合，包含分布式锁，缓存，ID生成器，限速限流器。
* [Redis Session Manager](https://github.com/chexagon/redis-session-manager)：Tomcat 8会话管理器通过持久化到Redis提供会话复制。
* [DSLabs](https://github.com/emichael/dslabs)：DSLabs是一个用于创建、测试、模型检查、可视化和调试分布式系统实验室作业的新框架，由华盛顿大学开发。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：Distributor基于Redis实现常用的分布式组件，简单、可靠、开箱即用。
* [COMP Superscalar](https://github.com/bsc-wdc/compss)：COMP Superscalar(COMPS)是一种编程模型，旨在简化分布式基础设施(例如集群、网格和云)的应用程序开发，由巴塞罗那超级计算中心开源。
* [UNICORE](https://www.unicore.eu/)：UNICORE是一个用于构建联合系统的软件套件，提供对高性能计算和数据资源的安全、无缝访问，由于利希研究中心开发。
* [Imhotep](https://github.com/indeedeng/imhotep)：Imhotep是Indeed打造的大型分析平台。
* [Drasyl](https://github.com/drasyl/drasyl)：Drasyl是一个用于快速开发分布式应用程序的高性能框架，由汉堡大学开源。
* [ScaleCube Cluster](https://github.com/scalecube/scalecube-cluster)：ScaleCube Cluster是一个轻量级的去中心化集群成员资格、故障检测和八卦协议库。
* [Apache Gossip](https://github.com/apache/incubator-retired-gossip)：Apache Gossip是一个基于Gossip协议的开源项目，旨在提供一个可靠、高效的分布式通信机制。

#### 分布式锁

* [Redisson](https://github.com/redisson/redisson)：Redisson是一个具有内存数据网格功能的Redis Java客户端，包含实现分布式锁的功能。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：ShedLock确保你的计划任务最多同时执行一次。
* [KLock](https://github.com/kekingcn/spring-boot-klock-starter)：基于Redis的分布式锁组件，可以快捷的将分布式锁功能集成到项目中，凯京科技开源。
* [Apache Curator](https://github.com/apache/curator)：Curator是ZooKeeper的Java/JVM客户端库，由Netflix开源。
* [DLock](https://github.com/baidu/dlock)：DLock是Java实现、有效且可靠的分布式锁，由百度开源。
* [Distributed Kit](https://github.com/yujiasun/Distributed-Kit)：基于Redis和Zookeeper分布式工具集，包括分布式锁实现。
* [Lock4j](https://gitee.com/baomidou/lock4j)：Lock4j是一个分布式锁组件，其提供了多种不同的支持以满足不同性能和环境的需求，由baomidou社区开源。
* [Sherlock](https://github.com/coditory/sherlock-distributed-lock)：Sherlock是一个用于JVM项目的分布式锁库，它公开同步和响应式API，并使用数据库连接器来存储锁。
* [Amazon DynamoDB Lock Client](https://github.com/awslabs/amazon-dynamodb-lock-client)：Amazon DynamoDB Lock Client是构建在DynamoDB之上的通用分布式锁库，支持粗粒度和细粒度锁定。
* [Nepxion Aquarius](https://github.com/Nepxion/Aquarius)：Nepxion Aquarius是一款基于Redis、Zookeeper的分布式应用组件集合，包含分布式锁，缓存，ID生成器，限速限流器。
* [Redis Distributed Lock](https://github.com/TaXueWWL/redis-distributed-lock)：Redis分布式锁工具包，提供纯Java方式调用，支持传统Spring工程，也为Spring Boot应用提供了Starter。
* [Distributed Lock](https://github.com/alturkovic/distributed-lock)：使用Spring进行分布式锁的简单实现。
* [WLock](https://github.com/wuba/WLock)：WLock是一套基于一致性算法组件WPaxos实现的高可靠、高吞吐分布式锁服务，由58同城开源。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：Distributor基于Redis实现常用的分布式组件，简单、可靠、开箱即用。

#### 分布式事务

* [Seata](https://github.com/apache/incubator-seata)：Seata是一个易于使用、高性能、开源的分布式事务解决方案，由阿里开源。
* [SOFA DTX](https://mvnrepository.com/artifact/com.alipay.dtx/dtx-sofa)：DTX是蚂蚁研发的一款金融级分布式事务中间件。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：ShardingSphere是一种分布式SQL事务和查询引擎，允许在任何数据库上进行数据分片、扩展、加密等，由当当网开源。
* [ByteTCC](https://github.com/liuyangming/ByteTCC)：ByteTCC是分布式事务管理器的实现，基于TCC机制。
* [Atomikos](https://github.com/atomikos/transactions-essentials)：Atomikos是一个轻量级的分布式事务管理器，由Atomikos开源。
* [Narayana](https://github.com/jbosstm/narayana)：Narayana是一个事务工具包，为使用各种基于标准的事务协议开发的应用程序提供支持，JBoss开源。
* [Bitronix](https://github.com/scalar-labs/btm)：Bitronix是JTA 1.1的简单但完整的实现，目前由韩国Scalar公司维护。
* [EasyTransaction](https://github.com/QNJR-GROUP/EasyTransaction)：EasyTransaction是一个分布式事务解决方案，统一使用TCC、SAGA、FMT、可靠消息、补偿等，由齐牛金融开源。
* [AtlasDB](https://github.com/palantir/atlasdb)：AtlasDB是一个构建在任何通用键值存储之上的事务层，由Palantir开源。
* [Hmily](https://github.com/dromara/hmily)：Hmily是一个金融级分布式事务解决方案，由dromara社区开源。
* [TCC Transaction](https://github.com/changmingxie/tcc-transaction)：TCC Transaction是一款开源的微服务架构下的TCC型分布式事务解决方案，致力于提供高性能和简单易用的分布式事务服务。
* [Multiverse](https://github.com/pveentjer/Multiverse)：Multiverse是JVM的软件事务内存实现。
* [LCN](https://github.com/codingapi/tx-lcn)：LCN分布式事务框架，兼容Dubbo、Spring Cloud、Motan框架，支持各种关系数据库，由CodingAPI组织开源。
* [TAPIR](https://github.com/UWSysLab/tapir)：TAPIR是一种用于线性化分布式事务的新协议，使用复制构建，没有一致性保证，由华盛顿大学CSE系统实验室开源。
* [Apache ServiceComb Pack](https://github.com/apache/servicecomb-pack)：ServiceComb Pack是微服务应用程序的最终数据一致性解决方案，目前提供TCC和Saga分布式事务协调解决方案，使用Alpha作为事务协调器，Omega作为事务代理，由华为开源。
* [Raincat](https://github.com/dromara/raincat)：Raincat是强一致分布式事务框架，由dromara社区开源。
* [Scalardb](https://github.com/scalar-labs/scalardb)：ScalarDB是一个跨数据库HTAP引擎，由韩国Scalar公司维护。
* [Transaction Outbox](https://github.com/gruelbox/transaction-outbox)：Java Transaction Outbox模式的灵活实现，具有干净、可扩展的API，并且可以与各种数据库平台、事务管理方法和应用程序框架很好地配合。
* [ByteJTA](https://github.com/liuyangming/ByteJTA)：ByteJTA是分布式事务管理器的实现，基于XA/2PC机制。
* [Myth](https://github.com/dromara/myth)：Myth是采用消息队列解决分布式事务的开源框架，由dromara社区开源。
* [Acku](https://github.com/x-ream/acku)：MQ事务、TCC、最终一致性。
* [Eventuate Tram Sagas](https://github.com/eventuate-tram/eventuate-tram-sagas)：Eventuate Tram Sagas框架是一个适用于使用JDBC/JPA和Spring Boot/Micronaut的Java微服务的Saga框架。
* [Txle](https://github.com/actiontech/txle)：Txle是爱可生开发的分布式事务解决方案，可以保证业务数据的最终一致性。

#### 分布式ID

* [Snowflake](https://github.com/twitter-archive/snowflake)：Snowflake是一种网络服务，用于大规模生成唯一ID号并提供一些简单的保证，由Twitter开源。
* [Leaf](https://github.com/Meituan-Dianping/Leaf)：Leaf是美团开源的分布式ID生成服务。
* [Tinyid](https://github.com/didi/tinyid)：Tinyid是一个ID生成器服务，它提供了一个REST API和一个用于获取ids的Java客户端，由滴滴开源。
* [Icicle](https://github.com/intenthq/icicle)：Icicle是一个使用Redis的Lua脚本以分布式方式生成64位、可排序的唯一ID的项目，由Intent HQ开源。
* [IdCenter](https://github.com/adyliu/idcenter)：IdCenter是用于生成唯一ID号的网络服务，由搜狐开源。
* [Sequence](https://gitee.com/yu120/sequence)：Sequence是一个高效GUID生成算法，基于Snowflake实现64位自增ID算法。
* [IDWorker](https://github.com/imadcn/idworker)：IDWorker是一个基于Zookeeper和雪花算法的分布式ID生成工具。
* [Redis ID Generator](https://github.com/hengyunabc/redis-id-generator)：基于Redis的分布式ID生成器。
* [UidGenerator](https://github.com/baidu/uid-generator)：UidGenerator是一个Java实现的、基于Snowflake的唯一ID生成器，由百度开源。
* [CosId](https://gitee.com/AhooWang/CosId)：CosId旨在提供通用、灵活、高性能的分布式ID生成器。
* [Java Snowflake](https://github.com/callicoder/java-snowflake)：基于雪花算法的分布式ID生成器。
* [TSID Creator](https://github.com/f4b6a3/tsid-creator)：TSID Creator是用于生成TSID的Java库。
* [IdGenerator](https://github.com/yitter/IdGenerator)：IdGenerator是一个多语言的分布式ID生成库。
* [KSUID](https://github.com/ksuid/ksuid)：KSUID是一种生成全局唯一ID的方法，类似于RFC 4122 UUID。

#### Raft算法

* [KRaft](https://github.com/apache/kafka/tree/trunk/raft)：KRaft是基于Raft共识协议为Kafka量身定制的协议。
* [SOFAJRaft](https://github.com/sofastack/sofa-jraft)：SOFAJRaft是基于RAFT一致性算法的生产级高性能Java实现，支持MULTI-RAFT-GROUP，适用于高负载、低延迟的场景，由蚂蚁开源。
* [Raft Java](https://github.com/wenweihu86/raft-java)：Raft算法的简单Java实现。
* [Apache Ratis](https://github.com/apache/ratis)：Ratis是一个实现Raft协议的Java库。
* [Dledger](https://github.com/openmessaging/dledger)：Dledger是一个基于Raft的Java库，用于构建高可用、高持久、强一致的提交日志，由阿里开源。
* [Lu-Raft-KV-Storage](https://github.com/stateIs0/lu-raft-kv)：这是一个Java版本的Raft KV分布式存储实现。
* [Copycat](https://github.com/atomix/copycat)：Raft一致性算法的新颖实现，由Intel开源。
* [Gondola](https://github.com/YahooArchive/gondola)：Gondola是用Java编写的Raft协议的高性能实现，由Yahoo开源。
* [jGroups Raft](https://github.com/jgroups-extras/jgroups-raft)：jGroups Raft是Raft共识算法在JGroups中的实现。
* [xRaft](https://github.com/xnnyygn/xraft)：简单的Raft共识算法实现。
* [jRaft](https://github.com/datatechnology/jraft)：jRaft是Java中的Raft算法实现。
* [Barge](https://github.com/mgodave/barge)：Raft共识协议的JVM实现。
* [LibRaft](https://github.com/allengeorge/libraft)：LibRaft是一个实现Raft分布式共识协议的Java库。
* [Dongting](https://github.com/dtprj/dongting)：Dongting项目是一个集成了Raft、配置服务器、消息队列、底层RPC的高性能引擎。
* [MicroRaft](https://github.com/MicroRaft/MicroRaft)：MicroRaft是Raft共识算法在Java中功能完整且稳定的开源实现。

#### Paxos算法

* [WPaxos](https://github.com/wuba/WPaxos)：WPaxos是Paxos一致性算法的生产级高性能Java实现，由58同城开源。
* [WLock](https://github.com/wuba/WLock)：WLock是一套基于一致性算法组件WPaxos实现的高可靠、高吞吐分布式锁服务，由58同城开源。
* [Klein](https://github.com/shihuili1218/klein)：Klein是一个基于Paxos的分布式集合工具库，包括分布式缓存、分布式消息队列、分布式List、分布式Map、分布式锁等。
* [Paxos](https://github.com/jaksa76/paxos)：Paxos算法的Java实现。
* [Trex](https://github.com/trex-paxos/trex)：Trex是用于JVM的嵌入式Paxos引擎。

## 数据库

这里包含使用Java编写的数据库软件

#### 搜索引擎

* [ElasticSearch](https://github.com/elastic/elasticsearch)：Elasticsearch是一种分布式RESTful搜索引擎，针对生产规模工作负载的速度和相关性进行了优化。
* [Apache Lucene](https://github.com/apache/lucene)：Lucene是一个用Java编写的高性能、全功能的文本搜索引擎库。
* [Apache Solr](https://github.com/apache/solr)：Solr是一款流行、速度极快的开源搜索平台，基于Lucene构建。
* [OpenSearch](https://github.com/opensearch-project/OpenSearch)：OpenSearch是一个基于Lucene的分布式搜索和分析引擎，由Amazon主导。
* [EasySearch](https://infinilabs.cn/)：EasySearch是一个分布式的搜索数据库，实现非结构化数据检索、全文检索、向量检索、地理位置信息查询、组合索引查询、多语种支持、聚合分析等，由极限科技提供。
* [NixieSearch](https://github.com/nixiesearch/nixiesearch)：Nixiesearch是一个混合搜索引擎，可以根据你的数据进行微调，由Carrot Search开源。
* [Vespa](https://github.com/vespa-engine/vespa)：Vespa是一个开源的大规模分布式实时计算的向量和文本搜索引擎，Yahoo开发。
* [YaCy](https://github.com/yacy/yacy_search_server)：YaCy是一个完整的搜索引擎应用程序，包含托管搜索索引的服务器。
* [JVector](https://github.com/jbellis/jvector)：JVector是一个纯Java嵌入式矢量搜索引擎，由DataStax Astra DB和Cassandra使用。
* [Linden](https://github.com/XiaoMi/linden)：Linden是一个构建在Lucene之上的分布式实时搜索系统，小米开源。
* [Fess](https://github.com/codelibs/fess)：Fess是一个非常强大且易于部署的企业搜索服务器，CodeLibs开源。
* [Zoie](https://github.com/senseidb/zoie)：Zoie是一个用Java编写的实时搜索/索引系统，由LinkedIn开源。
* [Cleo](https://github.com/LinkedInAttic/cleo)：Cleo是一个灵活的软件库，用于快速开发部分、无序和实时的预输入搜索，由LinkedIn开源。
* [OpenSearchServer](https://github.com/jaeksoft/opensearchserver)：OpenSearchServer是一款功能强大的、基于Lucene的企业级搜索引擎软件。
* [Bobo](https://github.com/senseidb/bobo)：Bobo是一个用Java编写的多面搜索引擎，由LinkedIn开源。
* [Loklak](https://github.com/loklak/loklak_server)：Loklak是一个服务器应用程序，能够从各种来源收集消息，包括Twitter，服务器包含搜索索引和点对点索引共享接口。
* [Kooder](https://gitee.com/koode/kooder)：Kooder是Gitee团队开发的一个代码搜索系统，为Gitee/GitLab/Gitea提供代码搜索服务。
* [IndexTank](https://github.com/LinkedInAttic/indextank-engine)：该项目包含IndexTank搜索引擎实现，包括变量(提升)、类别、分面搜索、片段、自定义评分函数、建议和自动完成等功能，由LinkedIn开源。
* [SearchCode](https://github.com/boyter/searchcode-server)：SearchCode是一个功能强大的代码搜索引擎，具有时尚的Web用户界面。
* [Terrier](https://github.com/terrier-org/terrier-core)：Terrier是一个高度灵活、高效且有效的开源搜索引擎，可轻松部署在大规模文档集合上，由格拉斯哥大学开发。
* [Solandra](https://github.com/tjake/Solandra)：Solandra是一个基于Solr和Cassandra构建的实时分布式搜索引擎。
* [Indri](https://www.lemurproject.org/)：Indri是一款搜索引擎，可提供最先进的文本搜索和丰富的结构化查询语言，可搜索多达5000万个文档(单机)或5亿个文档(分布式)的文本集合，由马萨诸塞大学和CMU语言技术研究所发起。
* [Search Framework](https://gitee.com/oschina/search-framework)：Search Framework是OSChina网站的全文搜索框架源码。
* [TngouDB](https://gitee.com/397713572/TngouDB)：TngouDB是天狗网开发的中文搜索引擎数据库，用于天狗农业网的农业搜索引擎。
* [MontySolr](https://github.com/adsabs/montysolr)：MontySolr是天体物理数据系统背后的搜索引擎，由哈佛大学和NASA开源。
* [Astra](https://github.com/slackhq/astra)：Astra是一个用于日志、跟踪和审计数据的云原生搜索和分析引擎，由Slack开源。
* [MG4J](https://mg4j.di.unimi.it/)：MG4J是一个用Java编写的免费全文搜索引擎，用于大型文档集合，由米兰大学开发。
* [Zulia](https://github.com/zuliaio/zuliasearch)：Zulia是一个实时分布式搜索和存储系统。
* [Egothor](https://egothor.sourceforge.net/)：Egothor是一个开源、高性能、功能齐全的文本搜索引擎，完全用Java编写。
* [Datafari](https://github.com/francelabs/datafari)：Datafari是一个开源企业搜索解决方案，由法国实验室开源。

#### 图数据库

* [Neo4j](https://github.com/neo4j/neo4j)：Neo4j是世界领先的图数据库。
* [JanusGraph](https://github.com/JanusGraph/janusgraph)：JanusGraph是一个高度可扩展的图数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图进行了优化。
* [Apache HugeGraph](https://github.com/apache/incubator-hugegraph)：HugeGraph是一个速度快、高度可扩展的图数据库，该项目正在Apache基金会下孵化，最早由百度开源。
* [Titan](https://github.com/thinkaurelius/titan)：Titan是一个高度可扩展的图形数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图形进行了优化，由Aurelius开源。
* [Amazon Neptune](https://aws.amazon.com/cn/neptune/)：Amazon Neptune是一个高性能图数据库，并对图的存储和查询进行了优化，可以存储数十亿个关系并将图形查询延迟降低到毫秒级。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型，被SAP收购。
* [Apache TinkerPop](https://github.com/apache/tinkerpop)：TinkerPop是一个面向实时事务处理(OLAP)以及批量、分析型图分析(OLTP)的图计算框架，诞生于洛斯阿拉莫斯国家实验室。
* [GraphDB](https://www.ontotext.com/)：GraphDB是一个企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：ArcadeDB多模型数据库，一种支持SQL、Cypher、Gremlin、HTTP/JSON、MongoDB和Redis的DBMS。
* [Stardog](https://www.stardog.com/)：Stardog是一款商业图数据库。
* [Apache Giraph](https://giraph.apache.org/)：Giraph是一个专为高可扩展性而构建的迭代图处理系统，Facebook基于Pregel思想的开源实现。
* [InfiniteGraph](http://www.objectivity.com/products/infinitegraph/)：InfiniteGraph是一个用Java和C++实现的分布式图数据库，这是Objectivity公司的产品。
* [AnzoGraph](https://cambridgesemantics.com/anzograph/)：AnzoGraph是为在线分析和数据协调而构建的水平可扩展图数据库。
* [Galaxybase](https://galaxybase.com/)：Galaxybase是浙江创邻科技公司研发的分布式图数据库产品。
* [YouTrackDB](https://github.com/youtrackdb/youtrackdb)：YouTrackDB是一个面向对象的图数据库，支持文档、全文搜索、响应性和地理空间概念，由JetBrains开源。
* [BlazeGraph](https://github.com/blazegraph/database)：Blazegraph是一个超高性能图数据库，支持蓝图和RDF/SPARQL API。
* [AllegroGraph](https://allegrograph.com/)：AllegroGraph是一个闭源的三元组存储，也可用作文档存储，目前用于美国国防部项目。
* [Gaffer](https://github.com/gchq/Gaffer)：Gaffer是一个图数据库框架，它允许存储在节点和边上包含丰富属性的非常大的图，由英国政府通讯总部开源。
* [TypeDB](https://github.com/vaticle/typedb)：TypeDB是一个多态数据库，具有概念数据模型、强大的子类型系统、符号推理引擎和美观优雅的类型理论语言TypeQL，由Vaticle Ltd开发。
* [HyperGraphDB](https://github.com/hypergraphdb/hypergraphdb)：HyperGraphDB是专为人工智能和语义Web项目设计的图数据库，也可以用作各种规模项目的嵌入式面向对象数据库。
* [FlockDB](https://github.com/twitter-archive/flockdb)：FlockDB是一个用于存储邻接列表的分布式图数据库，由Twitter开源。
* [YangDB](https://github.com/YANG-DB/yang-db)：YangDB是一个开源、可扩展、非原生图数据库(由Elasticsearch提供支持)。
* [GalaxyBase](https://galaxybase.com/)：GalaxyBase国产的高性能图数据库。
* [ONgDB](https://github.com/graphfoundation/ongdb)：ONgDB是一个开源、高性能、原生图存储，由Graph基金会开发。
* [TuGraph Analytics](https://github.com/TuGraph-family/tugraph-analytics)：TuGraph Analytics是蚂蚁集团开发的开源OLAP图数据库。
* [Bitsy](https://github.com/lambdazen/bitsy)：Bitsy是一个小型、快速、可嵌入、持久的内存图数据库，与Tinkerpop3兼容。
* [OverflowDB](https://github.com/ShiftLeftSecurity/overflowdb)：OverflowDB是一个低内存占用的内存图数据库，由ShiftLeft开源。
* [OhmDB](https://github.com/ohmdb/ohmdb)：OhmDB提供了关系数据库的强大功能和NoSQL数据库的灵活性。
* [Aerospike Graph](https://aerospike.com/products/graph-database/)：Aerospike Graph是一种高性能分布式图形数据库，商业软件。
* [AutomataLib](https://github.com/LearnLib/automatalib)：AutomataLib是一个免费的开源Java库，用于对自动机、图形和转换系统进行建模，由德国多特蒙德工业大学开发。
* [HGraphDB](https://github.com/rayokota/hgraphdb)：HGraphDB是使用HBase作为图数据库的客户端层。
* [StarGraph](https://github.com/Lambda-3/Stargraph)：StarGraph是一个用于查询大型知识图的图数据库，由帕绍大学开源。
* [Apache S2Graph](https://github.com/apache/incubator-s2graph)：S2Graph是一个基于HBase构建的分布式、可扩展的OLTP图数据库，支持超大图的快速遍历。
* [Fluree](https://github.com/fluree/db)：Fluree是一个不可变、时态、账本支持的语义图数据库，具有云原生架构。

#### 键值存储

* [Apache Accumulo](https://github.com/apache/accumulo)：Accumulo是一种排序的分布式键/值存储，可提供强大、可扩展的数据存储和检索，由美国国家安全局开源。
* [Storehaus](https://github.com/twitter/storehaus)：Storehaus是一个可以轻松使用异步键值存储的库，由Twitter开源。
* [Oracle Berkeley DB](https://www.oracle.com/database/technologies/related/berkeleydb.html)：Berkeley DB是一个高效的嵌入式数据库和键值数据库，最初起源于伯克利加州大学，Oracle提供一个纯Java程序编写的Berkeley DB。
* [Hawk](https://github.com/orhanobut/hawk)：适用于Android的安全、简单的键值存储。
* [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map)：Chronicle Map是一种超快速、内存中、非阻塞键值存储，专为低延迟和/或多进程应用程序(例如交易和金融市场应用程序)而设计。
* [KVStore](https://github.com/ggrandes/kvstore)：KVStore是一个基于B+Tree的Java内存和磁盘键值存储。
* [SimpleStore](https://github.com/uber/simple-store)：SimpleStore旨在为开发人员提供极其强大且高性能的解决方案，用于在磁盘上异步存储键值数据，由Uber开源。
* [FireflyDB](https://github.com/godcrampy/fireflydb)：FireflyDB是一种快速、线程安全、基于JVM的键值存储引擎，具有微秒级延迟。
* [JDBM3](https://github.com/jankotek/JDBM3)：JDBM提供TreeMap、HashMap等由磁盘存储备份的集合。
* [Sparkey](https://github.com/spotify/sparkey-java)：Sparkey键值存储的Java实现，用作嵌入其他软件中的库，由Spotify开源。
* [ClauDB](https://github.com/tonivade/claudb)：ClauDB是Java中的Redis实现。
* [Pistachio](https://github.com/lyogavin/Pistachio)：Pistachio是Yahoo开源的KV存储引擎，非常适合存储用户配置文件系统。
* [TomP2P](https://github.com/tomp2p/TomP2P)：TomP2P是一个P2P库和分布式哈希表(DHT)实现，为分布式应用程序提供去中心化的键值基础架构。
* [Sleeper](https://github.com/gchq/sleeper)：Sleeper是一种Serverless、云原生、基于日志结构合并树的可扩展键值存储，由英国政府通讯总部开源。
* [Oak](https://github.com/yahoo/Oak)：OakMap是一个并发键值Map，它将所有键和值保留在堆外，由Yahoo开源。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：LMDB是一种使用B+树的有序、嵌入式、持久的键值存储。
* [PalDB](https://github.com/linkedin/PalDB)：PalDB是一个用Java编写的嵌入式一次性写入键值存储，由LinkedIn开源。
* [HaloDB](https://github.com/yahoo/HaloDB)：HaloDB是一个用Java编写的快速且简单的嵌入式键值存储，由Yahoo开源。
* [JustinDB](https://github.com/justin-db/JustinDB)：JustinDB是一个最终一致的键值数据库，有利于写入可用性。
* [Voldemort](https://github.com/voldemort/voldemort)：Voldemort是一个分布式键值存储系统，Amazon Dynamo的开源克隆，由LinkedIn开源。
* [SwayDB](https://github.com/simerplaha/SwayDB)：用于JVM的持久内存键值存储引擎，旨在实现高性能和资源效率。
* [BBoxDB](https://github.com/jnidzwetzki/bboxdb)：BBoxDB是一个高可用的分布式存储管理器，旨在处理多维大数据。
* [CurioDB](https://github.com/stephenmcd/curiodb)：CurioDB是一个分布式持久Redis克隆，使用Scala和Akka构建。
* [TreodeDB](https://github.com/Treode/store)：TreodeDB是一个提供多行原子写入的分布式数据库，它专为RESTful服务而设计。
* [Hank](https://github.com/LiveRamp/hank)：Hank是LiveRamp构建和使用的一个非常快速且非常紧凑的分布式键值NoSQL数据库。
* [LSM Tree](https://github.com/indeedeng/lsmtree)：LSM Tree是一种快速键/值存储，对于大容量随机访问读写非常有效，由Indeed开发。
* [Distkv](https://github.com/distkv-project/distkv)：Distkv是一个具有表概念的轻量级分布式键值数据库系统。

#### 数据网格

* [GemFire](https://www.vmware.com/products/app-platform/tanzu-gemfire)：GemFire是一个分布式内存数据管理平台，专为高性能和低延迟的实时应用程序而设计，由VMware开发。
* [Coherence](https://github.com/oracle/coherence)：Coherence是一个可扩展、容错、云就绪的分布式平台，用于构建基于网格的应用程序并可靠地存储数据，由Oracle开源。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源内存数据网格，提供灵活的部署选项和强大的数据存储、管理和处理功能，由RedHat开源。
* [Apache Ignite](https://github.com/apache/ignite)：Ignite是一个分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [GridGain](https://www.gridgain.com/)：GridGain是一个基于Apache Ignite的内存计算平台，旨在解决速度和规模挑战。
* [XAP](https://github.com/xap/xap)：XAP是一个分布式、高度可扩展的内存数据网格，由GigaSpaces开源。
* [Galaxy](https://github.com/puniverse/galaxy)：Galaxy是一个内存数据网格，它的主要功能是将数据对象分布在集群节点之间进行分布式处理。

#### 时序数据库

* [QuestDB](https://github.com/questdb/questdb)：QuestDB是一个开源时序数据库，可实现高吞吐量摄取和快速SQL查询，并且操作简单。
* [Apache Druid](https://github.com/apache/druid)：Druid是一个高性能、实时分析数据库，可在大规模和负载下对流式和批处理数据提供亚秒级查询，由MetaMarkets开源。
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb)：OpenTSDB是一个分布式、可扩展的时序数据库，基于HBase开发，由StumbleUpon开源。
* [KairosDB](https://github.com/kairosdb/kairosdb)：KairosDB是一个基于Cassandra编写的快速分布式可扩展时序数据库。
* [Atlas](https://github.com/Netflix/atlas)：Atlas由Netflix开发，用于管理多维时序数据，以获得近乎实时的运营洞察。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Timely](https://github.com/NationalSecurityAgency/timely)：Timely是一个时序数据库应用程序，可提供对时间序列数据的安全访问，由美国国家安全局开源。
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是一种物联网原生数据库，具有高性能的数据管理和分析能力，可部署在边缘和云端，该项目由清华大学主导。
* [Newts](https://github.com/OpenNMS/newts)：Newts是一个基于Cassandra的时序数据存储。
* [RRD4J](https://github.com/rrd4j/rrd4j)：RRD4J是一个用于时序数据的高性能数据记录和图形系统，用Java实现RRDTool的功能。
* [Chronicle TimeSeries](https://github.com/OpenHFT/Chronicle-TimeSeries)：多线程时序库。
* [Heroic](https://github.com/spotify/heroic)：Heroic是一个开源监控系统，最初是在Spotify构建的，旨在解决大规模收集和近实时指标分析所面临的问题。
* [FiloDB](https://github.com/filodb/FiloDB)：FiloDB是一个开源分布式、实时、内存中、大规模可扩展、多模式时序/事件/操作数据库，具有Prometheus查询支持和一些Spark支持。
* [Axibase](https://axibase.com/docs/atsd/finance/)：HBase之上的集成时序数据库，具有内置可视化、规则引擎和SQL支持。
* [TimeBase](https://github.com/finos/TimeBase-CE)：TimeBase是Deltix公司开发的高性能时序数据库。
* [ChronixDB](https://github.com/ChronixDB/chronix.server)：高效、快速的时序存储。
* [Warp 10](https://github.com/senx/warp10-platform)：Warp 10是一个专为物联网设计的模块化开源平台，可收集、存储并允许你分析传感器数据。

#### 嵌入式数据库

* [H2](https://github.com/h2database/h2database)：H2是一个用Java编写的嵌入式RDBMS。
* [Apache Derby](https://github.com/apache/derby)：Derby是一个开源的嵌入式关系型数据库，完全使用Java语言实现。
* [HSQLDB](https://hsqldb.org/)：HSQLDB是领先的用Java编写的SQL关系数据库系统。
* [Chronicle](https://github.com/peter-lawrey/Java-Chronicle)：Chronicle是一个超低延迟、高吞吐量、持久化、消息传递和事件驱动的内存数据库。
* [QuickIO](https://github.com/artbits/quickio)：QuickIO是一个Java嵌入式数据库，底层基于LevelDB引擎和Java NIO设计，并使用Protostaff来序列化/反序列化数据。
* [Eclipse Store](https://github.com/eclipse-store/store)：EclipseStore是一个突破性的Java原生持久层，专为云原生微服务和Serverless应用程序而构建。
* [MapDB](https://github.com/jankotek/mapdb)：MapDB提供由磁盘存储或堆外内存支持的并发Map、Set、List和Queue，它是一个快速且易于使用的嵌入式Java数据库引擎。
* [ObjectBox](https://github.com/objectbox/objectbox-java)：ObjectBox是一个简单但功能强大的数据库，专为Java和Kotlin设计。
* [Xodus](https://github.com/JetBrains/xodus)：JetBrains Xodus是一种用Java和Kotlin编写的事务型无模式嵌入式数据库。
* [SirixDB](https://github.com/sirixdb/sirix)：SirixDB是一个可嵌入、双时态、仅附加的数据库系统和事件存储，存储不可变的轻量级快照。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：LMDB是一种使用B+树的有序、嵌入式、持久的键值存储。
* [Nitrite](https://github.com/nitrite/nitrite-java)：Nitrite数据库是一个开源NoSQL嵌入式文档存储，它支持内存中和基于文件的持久存储。
* [YoctoDB](https://github.com/yandex/yoctodb)：YoctoDB是一个微型嵌入式Java引擎，用于极快的分区构建后不可变数据库，由Yandex开源。
* [HerdDB](https://github.com/diennea/herddb)：HerdDB是一个分布式嵌入式数据库，数据分布在服务器集群中，不需要共享存储。
* [PalDB](https://github.com/linkedin/PalDB)：PalDB是一个用Java编写的嵌入式一次性写入键值存储，由LinkedIn开源。
* [Realm](https://github.com/realm/realm-java)：Realm是一个直接在手机、平板电脑或可穿戴设备内运行的移动数据库。
* [HaloDB](https://github.com/yahoo/HaloDB)：HaloDB是一个用Java编写的快速且简单的嵌入式键值存储，由Yahoo开源。
* [MariaDB4j](https://github.com/MariaDB4j/MariaDB4j)：MariaDB4j是MariaDB的Java启动器，允许你从Java使用MariaDB，无需任何安装/外部依赖。
* [Couchbase Android](https://github.com/couchbase/couchbase-lite-android)：适用于Android的轻量级、嵌入式、可同步NoSQL数据库引擎。
* [Tupl](https://github.com/cojen/Tupl)：Tupl是一个高性能、并发、事务性、可扩展、低级嵌入式数据库。
* [Keva](https://github.com/keva-dev/keva)：Keva是一个开源、JVM堆外内存数据存储，用作数据库或缓存，可以直接替代Redis。

#### 关系型数据库

* [PolarDB-X](https://github.com/polardb/polardbx-sql)：PolarDB-X是一款云原生分布式SQL数据库，专为高并发、海量存储、复杂查询场景而设计，由阿里开源。
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db)：YugabyteDB是一个高性能、云原生、分布式SQL数据库，旨在支持所有PostgreSQL功能。
* [FoundationDB Record Layer](https://github.com/FoundationDB/fdb-record-layer)：Record Layer是一个Java API，在FoundationDB之上提供面向记录的存储，大致相当于一个简单的关系型数据库，由Apple开源。
* [VoltDB](https://github.com/VoltDB/voltdb)：VoltDB是一种水平可扩展的内存中SQL RDBMS，专为具有极高读写吞吐量要求的应用程序而设计。
* [NuoDB](https://www.3ds.com/nuodb-distributed-sql-database/)：NuoDB是一个分布式云原生数据库管理系统，具有丰富的SQL实现并完全支持兼容事务，由达索开发。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：ArcadeDB是一个多模型DBMS，能够在通用硬件上每秒处理数百万条记录，并使用最少的资源。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Deephaven Community](https://github.com/deephaven/deephaven-core)：Deephaven Community是一个实时、时序、面向列的分析引擎，具有关系型数据库功能。
* [KarelDB](https://github.com/rayokota/kareldb)：KarelDB是一个由Kafka支持的全功能关系型数据库。
* [H-Store](https://github.com/apavlo/h-store)：H-Store是一个实验性主存并行数据库管理系统，针对OLTP应用程序进行了优化，它是一个高度分布式、基于行存储的关系型数据库，这是麻省理工学院、布朗大学、卡内基梅隆大学、耶鲁大学和英特尔之间的合作项目。
* [SimpleDB](https://github.com/iamxpy/SimpleDB)：加州大学伯克利分校的数据库课程CS186实现。
* [Simple DB HW 2021](https://github.com/MIT-DB-Class/simple-db-hw-2021)：MIT数据库课程6.830实现。
* [TMDB](https://github.com/whu-totemdb/tmdb)：武汉大学移动端Totem数据库系统。
* [MYDB](https://github.com/CN-GuoZiyang/MYDB)：MYDB是一个Java实现的简单的数据库，部分原理参照自MySQL、PostgreSQL和SQLite。
* [AntsDB](https://github.com/waterguo/antsdb)：AntsDB是HBase的低延迟、高并发虚拟SQL层。
* [Wasp](https://github.com/alibaba/wasp)：Wasp是类Google MegaStore & F1的分布式关系型数据库，由阿里开源。
* [Sqlg](https://github.com/pietermartin/sqlg)：Sqlg是Tinkerpop3在RDBMS上的实现，支持H2、HSQLDB、Postgresql。
* [VanillaDB](https://github.com/vanilladb/vanillacore)：VanillaCore是一个单节点、多线程关系数据库引擎，部分支持SQL-92标准，并通过JDBC、嵌入或(基于Java的)存储过程提供连接。
* [CreatorDB](https://github.com/CreatorsStack/CreatorDB)：CreatorDB是一个DBMS数据库管理系统，包含存储、算子、优化、事务、索引等。

#### NoSQL数据库

* [Amazon DynamoDB](https://aws.amazon.com/dynamodb)：Amazon DynamoDB是一种无服务器、NoSQL、完全托管的数据库，在任何规模下都具有个位数毫秒的性能。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：HBase是一个开源、分布式、版本化、面向列的存储，这是Google Bigtable的开源版本。
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是时序数据的数据管理系统，为用户提供数据采集、存储、分析等特定服务，该项目由清华大学主导。
* [Apache Ignite](https://github.com/apache/ignite)：Ignite是一个分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是一个开源多模型NoSQL DBMS，支持原生图、文档、全文搜索、响应式、地理空间和面向对象的概念。
* [Paper](https://github.com/pilgr/Paper)：Paper是Android上Java/Kotlin对象的快速类NoSQL存储，具有自动模式迁移支持。
* [Lealone](https://github.com/lealone/Lealone)：Lealone是一个高性能的面向OLTP场景的关系数据库，由阿里开源。
* [ToroDB](https://github.com/torodb/server)：ToroDB Server是一个运行在RDBMS之上的开源NoSQL数据库。
* [Concourse](https://github.com/cinchapi/concourse)：Concourse是一个分布式数据库仓库，用于跨时间的事务搜索和分析，由Cinchapi开源。
* [ElephantDB](https://github.com/nathanmarz/elephantdb)：ElephantDB是一个专门从Hadoop导出键/值数据的数据库。
* [Elassandra](https://github.com/strapdata/elassandra)：Elassandra是一个Cassandra发行版，包括Elasticsearch搜索引擎。
* [Sensei](https://github.com/LinkedInAttic/sensei)：Sensei是一个分布式、弹性的实时可搜索数据库，由LinkedIn开源。
* [LevelDB](https://github.com/dain/leveldb)：Java中LevelDB的重写，此目标是拥有一个功能完整的实现，其性能与C++原始版本的性能相差不超过10%，并生成C++代码的逐字节精确副本。
* [EXistDB](https://github.com/eXist-db/exist)：EXistDB是一个高性能开源原生XML数据库，完全围绕XML技术构建的NoSQL文档数据库和应用程序平台。
* [Eva](https://github.com/Workiva/eva)：Eva是一个分布式数据库系统，实现了时间感知、累积和原子一致的实体属性值数据模型，由Workiva开源。
* [CorfuDB](https://github.com/CorfuDB/CorfuDB)：Corfu是一个围绕共享日志抽象设计的一致性平台。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源数据网格平台和高度可扩展的NoSQL云数据存储，由RedHat开源。
* [BlobCityDB](https://github.com/blobcity/db)：BlobCityDB是一种一体化数据库，它支持本地存储17种不同格式的数据，包括JSON、XML、CSV、PDF、Word、Excel、Log、GIS、图像等。
* [EvitaDB](https://github.com/FgForrest/evitaDB)：EvitaDB是一个低延迟的NoSQL内存引擎，可以处理电子商务系统每天必须处理的所有复杂任务，由FG Forrest和赫拉德茨克拉洛韦大学开源。
* [Terrastore](https://code.google.com/archive/p/terrastore/)：Terrastore是一个现代文档存储，它提供先进的可扩展性和弹性功能，而不牺牲一致性。
* [JasDB](https://github.com/oberasoftware/jasdb)：JasDB是一款超快的多平台NoSQL数据库，可以嵌入到你的软件中或进行扩展，并且还具有完整的Android支持。
* [InfinityDB](https://boilerbay.com/infinitydb/manual/)：InfinityDB Embedded是一个Java NoSQL DBMS组件，其灵活性远超文档数据库，由加州大学开源。
* [Kronotop](https://github.com/kronotop/kronotop)：Kronotop是一个与Redis兼容的分布式事务文档数据库，由FoundationDB支持。

#### OLAP数据库

* [Apache Druid](https://github.com/apache/druid)：Druid是一个高性能、实时分析数据库，可在大规模和负载下对流式和批处理数据提供亚秒级查询，由MetaMarkets开源。
* [Apache Doris](https://github.com/apache/doris)：Doris是一个基于MPP架构的易于使用、高性能、实时分析的数据库，由百度开源。
* [StarRocks](https://github.com/StarRocks/starrocks)：StarRocks是Linux基金会的一个项目，是下一代数据平台，旨在使数据密集型实时分析变得快速、轻松，由百度Doris团队成员开源。
* [Apache Pinot](https://github.com/apache/pinot)：Pinot是一种实时分布式OLAP数据存储，由LinkedIn开源。
* [Apache Kylin](https://github.com/apache/kylin)：Kylin是一个面向Hadoop和云的统一且强大的OLAP平台，由eBay贡献。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [COOL](https://github.com/COOL-cohort/COOL)：COOL是一种非常高效的OLAP引擎，用于对时序数据进行队列和OLAP分析。
* [QinSQL](https://github.com/qinsql/QinSQL)：QinSQL是一个基于Lealone的可暂停的渐进式OLAP引擎。

#### 向量数据库

* [Vespa](https://github.com/vespa-engine/vespa)：Vespa是一个开源的大规模分布式实时计算的向量和文本搜索引擎，Yahoo开发。
* [DingoDB](https://github.com/dingodb/dingo)：DingoDB是由DataCanvas设计和开发的开源分布式多模态向量数据库。
* [Simbase](https://github.com/guokr/simbase)：Simbase是一个类似Redis的向量相似度数据库，由果壳科技开源。
* [Cottontail DB](https://github.com/vitrivr/cottontaildb)：Cottontail DB是一个旨在多媒体检索的列存储，它允许经典的布尔和向量空间检索，即相似性搜索中使用的最近邻查找，由巴塞尔大学开源。
* [VectoRex](https://gitee.com/giteeClass/VectoRex)：VectoRex是一个纯Java实现的高性能、可扩展的向量搜索引擎，专为现代AI和大数据应用设计。

#### 对象数据库

* [ObjectDB](https://www.objectdb.com/)：ObjectDB是Java的对象数据库，可以在客户端-服务器模式和嵌入式模式下使用。
* [Atoti](https://www.atoti.io/)：Atoti是一个数据分析平台，集一流的计算引擎、可视化套件和实时OLAP多维数据集于一体，由ActiveViam开发。

#### Datalog数据库

* [DataScript](https://github.com/tonsky/datascript)：Clojure和ClojureScript中的不可变内存数据库和Datalog查询引擎。
* [Datomic](https://www.datomic.com/)：Datomic是一个分布式数据库和Datalog的实现。
* [Datalevin](https://github.com/juji-io/datalevin)：Datalevin是一个简单持久的Datalog数据库。
* [Datahike](https://github.com/replikativ/datahike)：Datahike是一个持久的Datalog数据库，由高效的Datalog查询引擎提供支持。

#### 其他数据库

* [XTDB](https://github.com/xtdb/xtdb)：XTDB是一个具有双时态索引的通用数据库。
* [JsonDB](https://github.com/Jsondb/jsondb-core)：JsonDB是一个纯Java数据库，它将数据存储为Json文件。
* [Instant](https://github.com/instantdb/instant)：Instant是一个客户端数据库，可以轻松构建Notion或Figma等实时协作应用程序，由Facebook和Airbnb开源。
* [Astra DB](https://www.datastax.com/products/datastax-astra)：Astra DB为开发人员提供了创建强大AI应用程序所需的工具，包括API、实时数据处理和集成，由Datastax开发。
* [SnappyData](https://github.com/TIBCOSoftware/snappydata)：SnappyData是一个分布式、内存优化分析数据库。
* [Whois](https://github.com/RIPE-NCC/whois)：RIPE NCC受RIPE社区委托维护互联网资源信息数据库。
* [VDJdb](https://github.com/antigenomics/vdjdb-db)：VDJdb是一个精选的具有已知抗原特异性的T细胞受体(TCR)序列数据库，最初由俄罗斯皮罗戈夫国立研究医科大学和中欧理工学院开源。
* [OpenLineage](https://github.com/OpenLineage/openlineage)：OpenLineage是元数据和沿袭收集的开放标准，旨在在作业运行时对其进行检测。
* [KSqlDB](https://github.com/confluentinc/ksql)：KSqlDB是一个用于在Kafka之上构建流处理应用程序的数据库，由Confluent开源。
* [Polypheny-DB](https://github.com/polypheny/Polypheny-DB)：Polypheny-DB是一种自适应Polystore，可提供对异构数据的成本和工作负载感知访问，最初是巴塞尔大学的一个研究项目。
* [EmoDB](https://github.com/bazaarvoice/emodb)：EmoDB是一个RESTful HTTP服务器，用于存储JSON对象并监视这些事件的更改，由Bazaarvoice开源。
* [RSQLDB](https://github.com/alibaba/rsqldb)：RSQLDB是一个基于RocketMQ的流处理数据库，由阿里开源。
* [Apollo Delphinius](https://github.com/salesforce/apollo)：Apollo Delphinius项目是一个实验性多租户分布式系统平台，由Salesforce开源。

## 图处理

* [JGraphT](https://github.com/jgrapht/jgrapht)：JGraphT是一个免费的Java类库，提供数学图论对象和算法。
* [GraphJet](https://github.com/twitter/GraphJet)：GraphJet是一个实时图处理库，由Twitter开源。
* [Graphviz Java](https://github.com/nidi3/graphviz-java)：将graphviz与纯Java一起使用，使用Java代码创建graphviz模型并将其转换为漂亮的图形。
* [Apache Commons Graph](https://github.com/apache/commons-graph)：Commons Graph是一个用于管理图和基于图的数据结构的工具包。
* [PGX](https://www.oracle.com/middleware/technologies/parallel-graph-analytix.html)：PGX是一个用于图分析的工具包，支持高效的图算法和快速的类似SQL的图模式匹配查询，由Oracle开发。
* [GraphChi](https://github.com/GraphChi/graphchi-java)：GraphChi是一个基于磁盘的大规模图计算系统，由CMU开源。
* [GraphFrames](https://github.com/graphframes/graphframes)：GraphFrames是一个基于DataFrame的图形包，由加州大学伯克利分校、MIT和Databricks开源。
* [Gradoop](https://github.com/dbs-leipzig/gradoop)：Gradoop是一个开源研究框架，用于构建在Flink之上的可扩展图分析，由莱比锡大学数据库研究组开发。
* [SociaLite](https://github.com/socialite-lang/socialite)：SociaLite是一种用于分布式图分析的高级查询语言，由斯坦福开源。
* [GraphScope](https://github.com/alibaba/GraphScope)：GraphScope是阿里巴巴达摩院智能计算实验室研发并开源的一站式图计算平台。
* [JUNG](https://github.com/jrtom/jung)：JUNG是一个软件库，它提供了一种通用且可扩展的语言，用于对可以表示为图形或网络的数据进行建模、分析和可视化。
* [PGQL](https://github.com/oracle/pgql-lang)：PGQL是一种基于SQL的属性图数据模型查询语言，为SQL和NoSQL用户带来图模式匹配功能，由Oracle开源。
* [Ant Graph Learning](https://github.com/TuGraph-family/TuGraph-AntGraphLearning)：Ant Graph Learning为工业规模的图学习任务提供了全面的解决方案，由蚂蚁开源。
* [GraphBuilder](https://github.com/intel/graphbuilder)：GraphBuilder库提供了构建大规模图的函数，由Intel开源。
* [GraphStream](https://github.com/graphstream/gs-core)：GraphStream项目是一个Java库，提供API来建模、分析和可视化图和动态图，由勒阿弗尔大学开源。
* [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)：Erdos是一个非常轻量、模块化且超级易于使用的Java现代图论算法框架。
* [Neo4j Graph Data Science](https://github.com/neo4j/graph-data-science)：GDS包括图算法、图转换和机器学习管道，通过Neo4j DBMS内的Cypher程序进行操作。
* [GraphTea](https://github.com/rostam/GraphTea)：GraphTea是一个用于处理图和社交网络的软件框架。

## 数据库中间件

* [Canal](https://github.com/alibaba/canal)：Canal是阿里开发的基于数据库增量日志解析，提供增量数据订阅&消费的中间件。
* [DRC](https://github.com/ctripcorp/drc)：DRC是携程框架架构研发部数据中心组推出的用于数据双向或多向复制的数据库中间件。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：ShardingSphere是一种分布式SQL事务和查询引擎，允许在任何数据库上进行数据分片、扩展、加密等，由当当网开源。
* [Cobar](https://github.com/alibaba/cobar)：Cobar是分库分表的代理，兼容MySQL协议和MySQL SQL语法，底层存储仅支持MySQL，支持前台业务更简单、稳定、高效、安全，由阿里开源。
* [TSharding](https://github.com/baihui212/tsharding)：TSharding是蘑菇街交易平台使用的简单分片组件。
* [DBLE](https://github.com/actiontech/dble)：DBLE是由爱可生开发的一种高扩展性的MySQL分片中间件。
* [Gizzard](https://github.com/twitter-archive/gizzard)：Gizzard是用于创建最终一致的分布式数据存储的灵活分片框架，由Twitter开源。
* [Mycat2](https://github.com/MyCATApache/Mycat2)：Mycat2是Mycat社区开发的一款分布式关系型数据库中间件。
* [Heisenberg](https://github.com/brucexx/heisenberg)：Heisenberg是百度开源的一款基于MySQL协议之上的分库分表中间件，支持各种灵活的分库分表规则。
* [DAL](https://github.com/ctripcorp/dal)：DAL是携程框架部开发的数据库访问框架，支持流行的分库分表操作。
* [Zdal](https://github.com/xie-summer/zdal)：Zdal是支付宝自主研发的数据中间件产品，采用标准的JDBC规范。
* [Shark](https://github.com/gaoxianglong/shark)：Shark是一个分布式MySQL分库分表中间件。
* [Oceanus](https://github.com/wuba/Oceanus)：58同城数据库中间件，功能简单、易于上手。
* [InnoDB Java Reader](https://github.com/alibaba/innodb-java-reader)：InnoDB Java Reader是一个直接访问MySQL InnoDB存储引擎文件的Java实现，由阿里开源。
* [MySQL BinLog Connector](https://github.com/shyiko/mysql-binlog-connector-java)：MySQL二进制日志连接器。
* [TDDL](https://github.com/alibaba/tb_tddl)：TDDL是一个分布式数据库中间件，主要是为了解决分布式数据库产生的相关问题，由阿里开源。
* [Zebra](https://github.com/Meituan-Dianping/Zebra)：Zebra是一个基于JDBC API协议上开发出的高可用、高性能的数据库访问层解决方案，是美团点评内部使用的数据库访问层中间件。
* [ToroDB Stampede](https://github.com/torodb/stampede)：Stampede可将NoSQL数据从MongoDB副本集转换为PostgreSQL中的关系数据库。
* [Sharding Method](https://github.com/QNJR-GROUP/sharding-method)：Sharding Method是分表分库的新思路-服务层Sharding框架，全SQL、全数据库兼容，由齐牛金融开源。
* [ReplicaDB](https://github.com/osalvador/ReplicaDB)：ReplicaDB是用于数据库复制的开源工具，旨在在关系型数据库和NoSQL数据库之间高效传输批量数据。
* [Ptubes](https://github.com/meituan/ptubes)：Ptubes是一款基于PITR的数据库灾难恢复产品，可以用来将整个数据库恢复到特定时间点，美团开源。
* [EsProc](https://github.com/SPLWare/esProc)：EsProc SPL是一种用于数据处理的脚本语言，具有精心设计的丰富的库函数和强大的语法，可以通过JDBC接口在Java程序中执行并独立计算。
* [Mondrian](https://github.com/pentaho/mondrian)：Mondrian是一款OLAP服务器，使业务用户能够实时分析大量数据。
* [Coral](https://github.com/linkedin/coral)：Coral是一个SQL翻译、分析和重写引擎，由LinkedIn开源。
* [Morf](https://github.com/alfasoftware/morf)：Morf是一个用于跨平台演化关系型数据库机制、数据库访问和数据库成像/克隆的库。
* [Binlog4j](https://gitee.com/dromara/binlog4j)：Binlog4j是基于Java的轻量级MySQL Binlog客户端，由dromara社区开源。
* [Compass](https://github.com/sogou-biztech/compass)：Compass是搜狗商业平台研发部开发的一套轻量级分布式数据库访问框架。
* [Open Replicator](https://github.com/whitesock/open-replicator)：Open Replicator是一个用Java编写的高性能MySQL binlog解析器。
* [DataSQRL](https://github.com/DataSQRL/sqrl)：DataSQRL将SQL编译为优化的数据管道和数据微服务，从而消除了集成和调整具有多个步骤或组件的数据架构的手动工作。
* [SQLCommenter](https://github.com/google/sqlcommenter)：SQLCommenter是一套中间件/插件，使你的ORM能够在执行之前扩充SQL语句，并使用包含有关导致其执行的代码的信息的注释，由Google开源。
* [KKBinLog](https://gitee.com/kekingcn/kkbinlog)：KKBinLog旨在简化监听MySQL、MongoDB数据库的不同表的各种数据变动，由凯京科技开源。

## 数据库连接池

* [Druid](https://github.com/alibaba/druid)：Druid是一个JDBC组件库，包含数据库连接池、SQL Parser等组件，由阿里云开源。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：HikariCP是一个零开销生产就绪的JDBC连接池。
* [Apache Commons DBCP](https://github.com/apache/commons-dbcp)：Commons DBCP软件实现数据库连接池。
* [C3P0](https://github.com/swaldman/c3p0)：C3P0是一个成熟、高并发的JDBC连接池库，支持PreparedStatements的缓存和重用。
* [BoneCP](https://github.com/wwadge/bonecp)：BoneCP是一种JDBC连接池实现，它通过最大限度地减少锁争用来实现高性能，从而为应用程序提供更大的吞吐量。
* [FlexyPool](https://github.com/vladmihalcea/flexy-pool)：可以向给定的连接池添加指标和故障转移策略，使其能够按需调整大小。
* [Agroal](https://github.com/agroal/agroal)：Agroal是一个小巧的数据库连接池。
* [Vibur DBCP](https://github.com/vibur/vibur-dbcp)：Vibur DBCP是并发、快速且功能齐全的JDBC连接池，它提供高级性能监控功能，包括慢SQL查询检测和日志记录、应用程序线程的非饥饿保证、语句缓存和Hibernate集成等功能。
* [Tomcat JDBC Pool](https://tomcat.apache.org/tomcat-7.0-doc/jdbc-pool.html)：Tomcat JDBC连接池。
* [R2DBC-Pool](https://github.com/r2dbc/r2dbc-pool)：用于响应式关系数据库连接的连接池。
* [BeeCP](https://gitee.com/Chris2018998/BeeCP)：BeeCP是一个小型的JDBC连接池：性能高，代码轻量，稳定性好。
* [SmartPool](https://smartpool.sourceforge.net/)：SmartPool是一个连接池组件，以应用程序服务器提供的池功能为模型。

## HTTP客户端

* [Apache HttpComponents](https://github.com/apache/httpcomponents-core)：HttpComponents项目负责创建和维护专注于HTTP和相关协议的低级Java组件工具集。
* [Apache HttpComponents Client](https://github.com/apache/httpcomponents-client)：Apache开源的HTTP客户端库，相比HttpComponents Core提供更流式的API。
* [Java 11 HttpClient](https://github.com/openjdk/jdk/tree/master/src/java.net.http/share/classes/java/net/http)：JDK提供的HTTP(版本1.1和2)高级客户端接口和WebSocket低级客户端接口。
* [Feign](https://github.com/OpenFeign/feign)：Feign是一个Java到HTTP客户端绑定器，其灵感来自于Retrofit、JAXRS-2.0和WebSocket，由Netflix开源。
* [OkHttp](https://github.com/square/okhttp)：Square为JVM、Android和GraalVM精心设计的HTTP客户端。
* [Fuel](https://github.com/kittinunf/fuel)：由Kotlinx Coroutines支持的最简单的Kotlin HTTP网络库。
* [Retrofit](https://github.com/square/retrofit)：Retrofit是适用于Android和JVM的类型安全HTTP客户端，由Square开源。
* [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client)：AsyncHttpClient库允许Java应用程序轻松执行HTTP请求并异步处理HTTP响应。
* [Android Asynchronous HttpClient](https://github.com/android-async-http/android-async-http)：基于Apache HttpClient库的Android异步、基于回调的HTTP客户端。
* [Google HTTP Java Client](https://github.com/googleapis/google-http-java-client)：Google HTTP Client由Google开源，是一个灵活、高效且功能强大的Java库，用于通过HTTP访问网络上的任何资源。
* [Google API Java Client](https://github.com/googleapis/google-api-java-client)：Google API Java Client是一个灵活、高效且功能强大的Java客户端库，用于访问网络上任何基于HTTP的API。
* [HttpClientUtil](https://github.com/Arronlong/httpclientutil)：HttpClientUtil是基于HttpClient 4.4.1封装的工具类。
* [RoboSpice](https://github.com/stephanenicolas/robospice)：RoboSpice是一个模块化的Android库，可以轻松编写异步长时间运行的任务。
* [Http Request](https://github.com/kevinsawicki/http-request)：Http Request是一个简单的便利库，用于使用HttpURLConnection发出请求并访问响应。
* [HttpFetch](https://github.com/youzan/httpfetch)：HttpFetch用于对HTTP请求进行封装，通过对接口函数进行代理，实现优雅的HTTP调用，有赞开源。
* [EasyHttp](https://github.com/getActivity/EasyHttp)：Android网络请求框架，简单易用。
* [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)：OkGo基于HTTP协议，封装了OkHttp的网络请求框架。
* [STTP](https://github.com/softwaremill/sttp)：STTP是SoftwareMill开源的库，它提供了一个干净的、程序员友好的API来描述HTTP请求以及如何处理响应。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Java和Android的异步套接字、HTTP(s)和WebSocket库；基于NIO，而不是线程。
* [Chuck](https://github.com/jgilfelt/chuck)：Chuck是一个简单的应用内HTTP检查器，适用于Android OkHttp客户端。
* [NoHttp](https://github.com/yanzhenjie/NoHttp)：NoHttp是一个Android实现的HTTP标准协议框架，支持多种缓存模式，底层可动态切换OkHttp、URLConnection。
* [Volley](https://github.com/google/volley)：Volley是一个HTTP库，它使Android应用程序的网络变得更容易，Google开源。
* [Novate](https://github.com/Tamicer/Novate)：Novate是一款Android网络框架，基于Retrofit和RxJava打造的链式网络库。
* [Unirest](https://github.com/Kong/unirest-java)：Unirest是一个简化的轻量级HTTP客户端库。
* [RawHTTP](https://github.com/renatoathaydes/rawhttp)：一个Java库，可以轻松处理由RFC-7230定义的原始HTTP 1.1以及大部分HTTP 1.0(RFC-1945)。
* [HTTP-Kit](https://github.com/http-kit/http-kit)：HTTP-Kit是一个简约且高效的Clojure兼容环的HTTP客户端+服务器。
* [Forest](https://gitee.com/dromara/forest)：Forest是一个高层、极简的声明式HTTP调用API框架，由dromara社区开源。
* [Jetty ReactiveStream HttpClient](https://github.com/jetty-project/jetty-reactive-httpclient)：Jetty HttpClient的响应流包装器。
* [Methanol](https://github.com/mizosoft/methanol)：Methanol是Java的轻量级HttpClient扩展。
* [Jodd HTTP](https://github.com/oblac/jodd-http)：Jodd HTTP是一个小型、原始的HTTP客户端。
* [REST Commander](https://github.com/eBay/restcommander)：REST Commander是一个快速并行异步HTTP/REST/SOAP客户端即服务，用于监视和管理数以万计的Web服务器，由eBay开源。
* [Avaje HttpClient](https://github.com/avaje/avaje-http)：JDK 11 HttpClient的轻量级包装器。
* [Jcabi HTTP](https://github.com/jcabi/jcabi-http)：Jcabi HTTP是流式的Java HTTP客户端。
* [ESA RestClient](https://github.com/esastack/esa-restclient)：ESA RestClient是一个基于Netty的异步事件驱动的HTTP客户端。
* [WeChatPay HttpClient](https://github.com/wechatpay-apiv3/wechatpay-apache-httpclient)：微信支付API v3的Apache HttpClient扩展，实现了请求签名的生成和应答签名的验证。
* [HBC](https://github.com/twitter/hbc)：HBC是用于使用Twitter标准Streaming API的Java HTTP客户端，由Twitter开源。
* [FusionAuth HTTPClient](https://github.com/FusionAuth/java-http)：完全用纯Java编写的全功能、独立、高性能HTTP服务器和客户端。
* [Parallec](https://github.com/eBay/parallec)：Parallec是一个基于Akka的快速并行异步HTTP(S)/SSH/TCP/UDP/Ping客户端Java库，由eBay开源。
* [OkHttps](https://gitee.com/troyzhxu/okhttps)：OkHttps是对OkHttp3轻量封装的框架，包括异步预处理器，特色的标签，灵活的上传下载进度监听与过程控制功能。
* [Riptide](https://github.com/zalando/riptide)：Riptide是一个实现客户端响应路由的库，由Zalando开源。
* [RXHttp](https://github.com/liujingxing/rxhttp)：适用于Android的类型安全HTTP客户端，基于OkHttp。
* [HTTP4K](https://github.com/http4k/http4k)：HTTP4K是一个用纯Kotlin编写的轻量级但功能齐全的HTTP工具包，可以以功能一致的方式提供和使用HTTP服务。
* [LiteHTTP](https://github.com/litesuits/android-lite-http)：LiteHTTP是一个简单、智能且灵活的Android HTTP框架。
* [Communication](https://github.com/foundation-runtime/communication)：Communication包含与HTTP客户端和服务器通信相关的库，由Cisco开发。
* [Netty HTTP Client](https://github.com/timboudreau/netty-http-client)：Java中的异步HTTP客户端，具有干净、基于回调的API，基于Netty 4.x。
* [Jetty HttpClient](https://github.com/eclipse/jetty.project/tree/jetty-10.0.x/jetty-client)：Jetty中执行HTTP和HTTPS请求的模块。
* [Apache HttpAsyncClient Wrapper](https://github.com/puppetlabs/clj-http-client)：这是Apache HttpAsyncClient库的包装器，提供一些额外的功能，用于以与Puppet兼容的方式配置SSL。
* [HTTP4J](https://github.com/IntellectualSites/HTTP4J)：HTTP4J是Java HttpURLConnection的一个简单、轻量级且小型的包装器。
* [Donkey](https://github.com/AppsFlyer/donkey)：现代Clojure、Ring兼容的HTTP服务器和客户端，专为易用性和性能而设计。
* [HTTPBuilder](https://github.com/jgritman/httpbuilder)：Groovy的简单HTTP客户端。
* [HttpBuilder NG](https://github.com/http-builder-ng/http-builder-ng)：适用于Groovy、Java的简单HTTP客户端。
* [RestVolley](https://github.com/HujiangTechnology/RestVolley)：RestVolley是一个基于Volley和OkHttp的HTTP请求框架，由沪江科技开源。
* [King HttpClient](https://github.com/king/king-http-client)：支持SSE的异步HTTP客户端。
* [Smart HTTP](https://gitee.com/smartboot/smart-http)：Smart HTTP是一款可编程的HTTP应用微内核，方便用户根据自身需求进行服务端或客户端的应用开发。

## 响应式

* [RxJava](https://github.com/ReactiveX/RxJava)：RxJava是Reactive Extensions的JVM实现，由Netflix开源。
* [Reactor](https://github.com/reactor/reactor-core)：Reactor是第四代响应式库，基于Reactive Streams规范，用于在JVM上构建非阻塞应用程序，由Pivotal开源。
* [Java 9 Flow](https://docs.oracle.com/javase/9/docs/api/java/util/concurrent/Flow.html)：Java 9 Flow是JDK中的响应式编程API。
* [Spring Webflux](https://github.com/spring-projects/spring-framework/tree/main/spring-webflux)：Spring生态中基于Reactor的异步非阻塞Web框架。
* [Reactive Stream](https://github.com/reactive-streams/reactive-streams-jvm)：Reactive Streams是一项为具有非阻塞背压的异步流处理提供标准的举措，由Netflix、TypeSafe、Pivotal等公司发起。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包。
* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [Alpakka](https://github.com/akka/alpakka)：Alpakka是一个基于Reactive Streams和Akka的Java和Scala响应式企业集成库。
* [RSocket](https://github.com/rsocket/rsocket-java)：RSocket是一种二进制协议，用于字节流传输(例如TCP、WebSockets和Aeron)，由Facebook、Netflix、Pivotal等公司开源。
* [Agera](https://github.com/google/agera)：Agera是一组类和接口，可帮助为Android编写函数式、异步式和响应式应用程序，由Google开源。
* [Monix](https://github.com/monix/monix)：Monix是一个高性能Scala库，用于编写异步、基于事件的程序。
* [Mobius](https://github.com/spotify/mobius)：Mobius是一个用于管理状态演化和副作用的函数响应式框架，具有用于连接Android UI和RxJava Observables的附加组件，由Spotify开源。
* [Smallrye Mutiny](https://github.com/smallrye/smallrye-mutiny)：Mutiny是一个现代的Java响应式编程库，主要由RedHat维护。
* [AutoDispose](https://github.com/uber/AutoDispose)：AutoDispose是一个RxJava 2+工具，用于通过处置/取消自动将RxJava流的执行绑定到提供的作用域，由Uber开源。
* [Store](https://github.com/nytimes/Store)：Store是用于异步数据加载和缓存的Java库。
* [Electric](https://github.com/hyperfiddle/electric)：Electric是一种响应式和网络感知的Clojure/Script DSL，它在编程语言层完全抽象客户端/服务器状态同步，以便在动态Web应用程序中实现跨越前端/后端边界的强大组合。
* [Reaktive](https://github.com/badoo/Reaktive)：Reactive Extensions的Kotlin多平台实现。
* [RSocket JVM](https://github.com/jauntsdn/rsocket-jvm)：RSocket JVM在JVM上提供非常快速的类gRPC和兼容gRPC的服务，并通过多种网络传输提供丰富的流模型。
* [Alibaba RSocket Broker](https://github.com/alibaba/alibaba-rsocket-broker)：Alibaba RSocket Broker是一款基于RSocket协议的响应式对等通讯系统，为通讯多方构建分布式的RPC、Pub/Sub、Streaming等通讯支持。
* [Sqlbrite](https://github.com/square/sqlbrite)：围绕SupportSQLiteOpenHelper和ContentResolver的轻量级包装器，它向查询引入了响应式流语义，由Square开源。
* [StorIO](https://github.com/pushtorefresh/storio)：SQLiteDatabase和ContentResolver的响应式API。
* [RxNetty](https://github.com/ReactiveX/RxNetty)：RxNetty是Netty的Rx适配器。
* [Netty Reactive Streams](https://github.com/playframework/netty-reactive-streams)：Netty的Reactive Streams实现。
* [Reactive gRPC](https://github.com/salesforce/reactive-grpc)：Reactive gRPC是一套将gRPC与Reactive Streams编程库结合使用的库，由Salesforce开源。
* [Reactive Wizard](https://github.com/FortnoxAB/reactive-wizard)：Reactive Wizard项目可以轻松构建利用Reactor和Netty强大功能的高性能且可扩展的Web应用程序，由Fortnox开源。
* [QBit](https://github.com/advantageous/qbit)：QBit是一个用于构建微服务的响应式编程库。
* [ScaleCube](https://github.com/scalecube/scalecube-services)：ScaleCube是一个通过提供可嵌入的微服务库来简化响应式和分布式应用程序开发的项目。
* [CohereFlux](https://github.com/pellse/cohereflux)：CohereFlux是一个响应式、函数式、类型安全和无状态的数据聚合框架，用于查询和合并来自多个数据源/服务的数据。
* [Reactive Commons](https://github.com/reactive-commons/reactive-commons-java)：Reactive Commons的目的是提供一组针对不同模式和实践的抽象和实现，这些模式和实践构成了响应式微服务架构的基础，由哥伦比亚银行维护。
* [Arez](https://github.com/arez/arez)：Arez是一个简单、高效且可扩展的客户端应用程序状态管理库。

## 服务器

这里列出了不同类型的服务器软件。

#### Web服务器

* [Apache Tomcat](https://github.com/apache/tomcat)：Tomcat是Java Servlet、JavaServer Pages、Jav EL和Java WebSocket技术的开源实现，最初由Sun开发。
* [Netty TCNative](https://github.com/netty/netty-tcnative)：Netty TCNative是Tomcat Native的一个分支，它包括Twitter贡献的一系列更改。
* [Apache TomEE](https://github.com/apache/tomee)：TomEE是一个轻量级但功能强大的JavaEE应用服务器，具有功能丰富的工具。
* [Helidon Nima](https://github.com/helidon-io/helidon/tree/helidon-3.x/webserver)：Helidon Níma是一个基于JDK虚拟线程的轻量级Web服务器，由Oracle开源。
* [Undertow](https://github.com/undertow-io/undertow)：Undertow是一个基于非阻塞IO的Java Web服务器，由RedHat开源。
* [Wildfly](https://github.com/wildfly/wildfly)：WildFly是一个功能强大、模块化且轻量级的应用程序服务器，由RedHat开源。
* [Oracle Weblogic](https://www.oracle.com/sg/java/weblogic/)：Oracle WebLogic Server是一个统一且可扩展的平台，用于在本地和云中开发、部署和运行Java等企业应用程序。
* [Payara](https://github.com/payara/Payara)：Payara Platform Community Edition提供用于开发项目的开源服务器运行时以及容器化Jakarta EE和MicroProfile应用程序
* [Eclipse Jetty](https://github.com/eclipse/jetty.project)：Jetty是一个轻量级、高度可扩展的基于Java的Web服务器和Servlet引擎。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现，由Oracle开源。
* [Apache Geronimo](https://github.com/apache/geronimo)：Apache基金会下开源的Java EE服务器。
* [Red5](https://github.com/Red5/red5-server)：Red5是一个用Java编写的开源Flash服务器。
* [Microhttp](https://github.com/ebarlas/microhttp)：Microhttp是一种快速、可扩展、事件驱动、独立的Java Web服务器。
* [Resin](https://caucho.com/products/resin)：Resin是Caucho公司的产品，它是一个非常流行的支持Servlet和JSP的服务器。
* [ZFoo](https://github.com/zfoo-project/zfoo)：ZFoo是一个极快的企业服务器框架，可用于RPC、游戏服务器、Web服务器。
* [Rupy](https://github.com/tinspin/rupy)：Rupy是一款节能、安全、高性能的HTTP应用服务器。
* [Reactor Netty](https://github.com/reactor/reactor-netty)：Reactor Netty提供基于Netty框架的非阻塞和背压就绪的TCP/HTTP/UDP/QUIC客户端和服务器。
* [Nettosphere](https://github.com/Atmosphere/nettosphere)：Nettosphere是由Atmosphere和Netty提供支持的Java WebSocket和HTTP服务器。
* [NanoHTTPD](https://github.com/NanoHttpd/nanohttpd)：NanoHTTPD是一个轻量级HTTP服务器，设计用于嵌入其他应用程序。
* [Java NIO Server](https://github.com/jjenkov/java-nio-server)：一个始终使用非阻塞IO的Java NIO服务器。
* [AndServer](https://github.com/yanzhenjie/AndServer)：AndServer是一个HTTP和反向代理服务器。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [Nginx Clojure](https://github.com/nginx-clojure/nginx-clojure)：Nginx Clojure是一个Nginx模块，用于嵌入Clojure或Java或Groovy程序，通常是那些基于Ring的处理程序。
* [Jibble](http://www.jibble.org/miniwebserver/)：Jibble是一个用Java编写的非常小的独立Web服务器，它打包在JAR文件中，也可以在你自己的Java程序中使用。
* [Android HTTP Server](https://github.com/piotrpolak/android-http-server)：完全用Java编写的小型但功能强大的多线程Web服务器。
* [MuServer](https://github.com/3redronin/mu-server)：MuServer是一个基于Netty的现代Java Web服务器。
* [Fluent HTTP](https://github.com/CodeStory/fluent-http)：Fluent HTTP是一个简单、快速、成熟的Web服务器。
* [JLHTTP](https://github.com/curtcox/JLHTTP)：JLHTTP是HTTP服务器的开源实现。
* [TJWS](https://tjws.sourceforge.net/)：TJWS是作为Servlet容器构建的，其中HTTPD Servlet提供标准Web服务器功能。

#### WebSocket服务器

* [Pushy](https://netflixtechblog.com/pushy-to-the-limit-evolving-netflixs-websocket-proxy-for-the-future-b468bc0ff658)：Pushy是Netflix的WebSocket服务器，可与运行Netflix应用程序的设备保持持久的WebSocket连接。
* [Java WebSocket](https://github.com/TooTallNate/Java-WebSocket)：该项目包含用纯Java编写的准系统WebSocket客户端和服务器实现。
* [Scarlet](https://github.com/Tinder/Scarlet)：Scarlet是受Retrofit启发的适用于Kotlin、Java和Android的WebSocket客户端。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：AndroidAsync是适用于Android的异步套接字、HTTP(s)客户端/服务器和WebSocket库。基于NIO而不是线程。
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：AsyncHttpClient是适用于Java的异步HTTP和WebSocket客户端库。
* [NV Websocket Client](https://github.com/TakahikoKawasaki/nv-websocket-client)：Java中的高质量WebSocket客户端实现。
* [WebSocket Android](https://github.com/codebutler/android-websockets)：一个非常简单的Android WebSocket客户端。
* [Kafka-WebSocket](https://github.com/b/kafka-websocket)：kafka分布式消息代理的简单WebSocket服务器接口。
* [Socket.IO Java](https://github.com/socketio/socket.io-client-java)：全功能的Java Socket.IO客户端库，与Socket.IO v1.0及更高版本兼容。
* [EzyFox](https://github.com/youngmonkeys/ezyfox-server)：EzyFox支持企业产品开发的各种基本组件，包括TCP、UDP、WebSocket、HTTP RESTful API、RPC协议、数据库交互、内存缓存和消息队列。
* [Pusher Java Client](https://github.com/pusher/pusher-websocket-java)：适用于Java的Pusher Channels客户端库，面向Java和Android。
* [Socket.IO](https://github.com/scalecube/socketio)：ScaleCube Socket.IO是基于Netty框架的Socket.IO Java服务器的轻量级实现
* [JavaWebsocketClient](https://github.com/jacek-marchwicki/JavaWebsocketClient)：JavaWebsocketClient库是用于Java和Android的RX中Websocket连接的简单库，它被设计为快速且容错。
* [Qonduit](https://github.com/NationalSecurityAgency/qonduit)：Accumulo的安全WebSocket代理，由美国国家安全局开源。
* [Netty Socket.IO](https://github.com/mrniko/netty-socketio)：该项目是Socket.IO服务器的开源Java实现，基于Netty服务器框架。
* [wAsync](https://github.com/Atmosphere/wasync)：wAsync是一个基于Java的库，允许与任何支持WebSocket或HTTP协议的Web服务器进行异步通信。
* [Java/Android WebSocket Client](https://github.com/gusavila92/java-android-websocket-client)：一个非常轻量级的WebSocket客户端库，适用于基于JVM的客户端或Android，旨在实现RFC 6455中定义的WebSocket协议。
* [Netty WebSocket Spring Boot Starter](https://github.com/YeautyYE/netty-websocket-spring-boot-starter)：轻量级、高性能的WebSocket框架。
* [Webbit](https://github.com/webbit/webbit)：Webbit是基于Java事件的WebSocket和HTTP服务器。
* [Autobahn](https://github.com/crossbario/autobahn-java)：Autobahn是适用于Android和Java 8的Java中的WebSocket和WAMP。
* [Eclipse Tyrus](https://github.com/eclipse-ee4j/tyrus)：Tyrus是开源JSR 356-WebSocket参考实现的Java API，可轻松开发WebSocket应用程序。
* [Socket.IO Java Client](https://github.com/Gottox/socket.io-java-client)：Java中的Socket.IO客户端实现。
* [Socket.IO Java](https://github.com/trinopoty/socket.io-server-java)：这是从JavaScript服务器移植的Java Socket.IO服务器库。
* [Babl WebSocket Server](https://github.com/babl-ws/babl)：Babl是一款高性能、可扩展的WebSocket服务器，专为低延迟应用程序而设计。
* [Socket.x](https://github.com/obsidiandynamics/socketx)：Socket.x是一个用于构建高性能、分布式WebSocket应用程序的库。

#### FTP服务器

* [Apache FtpServer](https://mina.apache.org/ftpserver-project/)：FtpServer是一个100%纯Java FTP服务器。
* [MinimalFTP](https://github.com/Guichaguri/MinimalFTP)：一个轻量级、简单的FTP服务器。
* [Anomic](https://github.com/Orbiter/anomic_ftp_server)：Anomic是一个简单的FTP服务器。
* [SwiFTP](https://github.com/ppareit/swiftp)：Android设备的FTP服务器。
* [DrFTPD](https://github.com/drftpd-ng/drftpd)：DrFTPD是一个用Java编写的分布式FTP服务器。

## JakartaEE产品

* [Payara](https://github.com/payara/Payara)：Payara Platform Community Edition提供用于开发项目的开源服务器运行时以及容器化Jakarta EE和MicroProfile应用程序。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Piranha](https://github.com/piranhacloud/piranha)：Piranha项目提供云就绪容器和有用的附加/集成模块。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，它是IBM WebSphere Liberty的开源实现。
* [SAP AS](https://www.sap.com/products/technology-platform/netweaver.html)：SAP Web应用服务器是NetWeaver解决方案的一个组件。
* [AISWare FlyingServer](https://www.asiainfo.com/zh_cn/product_aisware_flyingServer.html)：FlyingServer是一款满足Java EE 8标准的国产化Web中间件软件，支持WAR，EAR，JAR等应用的部署，由亚信科技提供。
* [Apusic AAS](https://www.apusic.com/list-117.html)：金蝶Apusic应用服务器是一款标准、安全、高效、集成并具丰富功能的企业级应用服务器软件，全面支持Jakarta EE 8/9的技术规范。
* [Apache Geronimo](https://github.com/apache/geronimo)：Apache基金会下开源的Java EE服务器。
* [Adobe ColdFusion](https://www.adobe.com/products/coldfusion-family.html)：Adobe ColdFusion是一款久经考验的高性能应用程序服务器，可让程序员轻松进行Web开发。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现，由Oracle开源。
* [Fujitsu Software Enterprise Application Server](https://www.fujitsu.com/jp/products/software/middleware/business-middleware/middleware/applatform/)：Enterprise Application Server是一款云原生应用服务器，采用富士通专有技术增强Java的可靠性和可操作性，可在短时间内发布，并可用于企业用途。
* [Fujitsu Software Interstage Application Server](https://www.fujitsu.com/jp/products/software/middleware/business-middleware/interstage/products/apserver/)：Interstage Application Server是基于核心系统培育的标准技术和高可靠高性能技术，实现高开放性业务应用稳定运行的应用服务器。
* [IBM WebSphere Liberty](https://www.ibm.com/support/pages/node/6250961#asset/runtimes-wlp-javaee8)：IBM WebSphere是由IBM遵照开放标准，例如Java EE、XML及Web Services开发并发行的一种应用服务器。
* [InforSuite Application Server](https://www.inforbus.com/as.html)：中创应用服务器软件是国内通过Jakarta EE 9、8及Java EE 8、7、6完整兼容认证的企业级中间件，与国际主流产品最新版本保持规范一致，为应用运行提供高性能、高可用、高安全的支撑平台。
* [Resin](https://caucho.com/products/resin)：Resin是Caucho开发的Web服务器和Java应用服务器，有两个可用版本：Resin(可免费用于生产)和Resin Pro(需要支付许可费用)。
* [JBoss Enterprise Application Platform](https://www.redhat.com/en/technologies/jboss-middleware/application-platform)：RedHat JBoss企业应用平台可在任何环境中提供企业级安全性、性能和可扩展性。
* [Primeton AppServer](https://www.primeton.com/products/pas/)：Primeton AppServer提供了丰富的功能集，具备“立即部署”式Java EE容器的各种优点，由普元开发。
* [WildFly](https://www.wildfly.org/downloads/)：WildFly是一款功能强大、模块化且轻量级的应用程序服务器。
* [BES Application Server](https://www.bessystem.com/product/0ad9b8c4d6af462b8d15723a5f25a87d/info?p=101#page-2)：一款遵循Java EE标准的面向Java应用的通用中间件，由宝兰德提供。
* [ManageFish Server](https://managecat.com/products/managed-glassfish)：ManageFish是GlassFish应用服务器版本的商业支持的发行版。
* [Oracle WebLogic](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)：WebLogic是Oracle出品的用于开发、集成、部署和管理大型分布式Web应用、网络应用和数据库应用的Java应用服务器。
* [RockyAS](https://rockyasfile.obs-cn-shenzhen.pinganyun.com/RockyAS.html)：Rocky是一款标准、安全、高效的Web应用服务器，为企业级应用系统的便捷开发、灵活部署、可靠运行、高效管理及快速集成提供关键支撑能力，由平安云开发。
* [TongWeb Application Server](https://www.tongtech.com/dft/pctype/25.html)：TongWeb是一款全面符合Java EE、Jakarta EE最新标准规范、轻量易于使用、性能强大、具有高可靠性和高安全性的应用服务器产品，由东方通开发。
* [JEUS](https://www.tmaxsoft.com/en/solution/view?solutionSeq=27)：JEUS是在Web环境中开发、运行、执行应用程序的平台，提供各种必要服务、符合Java标准的Web应用服务器，由韩国TmaxSoft公司开发。
* [WebOTX Application Server](https://jpn.nec.com/webotx/appserver/index.html)：WebOTX是一个Java应用程序执行平台，非常适合在从本地到云的各种IT资源中推广DX，这是日本电气公司的产品。
* [Xigema Application Server](http://www.vsettan.com.cn/7752.html)：XigemaAS是企业级应用服务器产品，完全符合Java EE 7规范， 产品架构基于OSGi内核，高模块化、高动态性、强扩展性、轻量且配置简单，为企业应用提供稳定、高效、安全的运行引擎和支撑平台，这是华胜信泰的产品。
* [Thunisoft Application Server](https://www.thunisoft.cn/col81/index)：Thunisoft是华宇自主研发的企业级中间件产品，符合Jakarta EE标准的轻量级服务器。
* [JOnAS](https://jonas.ow2.org/)：JOnAS是由Bull和OW2开发的领先的Java EE 6 Web Profile认证开源OSGi企业服务器。
* [UseOpen Application Server](http://www.useopen.com/p/uoas/)：UOAS是一款永源开源的Java应用服务器产品，支持Jakarta EE Web Profile规范的应用服务器功能。
* [Smart Servlet](https://gitee.com/smartboot/smart-servlet)：Smart Servlet是一款实现了Servlet 4.0规范，支持多应用隔离部署的的Web容器。

## 工具库

* [Guava](https://github.com/google/guava)：Guava是Google的一组核心Java库，其中包括新的集合类型、不可变集合、图库以及用于并发、I/O、哈希、原始类型、字符串等的实用程序。
* [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)：AndroidUtilCode是一个功能强大且易于使用的Android库，封装了Android开发中常用的函数。
* [Apache Commons Lang](https://github.com/apache/commons-lang)：Commons Lang是一个Java实用程序类包，用于java.lang层次结构中的类。
* [Hutool](https://github.com/dromara/hutool)：Hutool是一个功能丰富且易用的Java工具库，涵盖了字符串、数字、集合、编码、日期、文件、IO、加密、数据库JDBC、JSON、HTTP客户端等一系列操作，由dromara社区开源。
* [Cactoos](https://github.com/yegor256/cactoos)：Cactoos是面向对象的Java原始类型的集合。
* [JCommon](https://github.com/facebookarchive/jcommon)：JCommon是Facebook开源的Java工具库，含并发、集合、统计/分析、配置、测试等功能。
* [Jodd](https://github.com/oblac/jodd)：Jodd是一组微框架和开发人员友好的工具和实用程序。
* [X-Core](https://github.com/TGX-Android/X-Core)：X-Core是一组可在任何项目中使用的通用Java工具和接口，由Telegram开源。
* [Essentials](https://github.com/greenrobot/essentials)：Essentials是适用于Android和Java的通用工具和哈希函数。
* [Intellij Util](https://github.com/JetBrains/intellij-community/tree/master/platform/util)：Intellij Util包含JetBrains基于Intellij IDE的通用工具库。
* [Android Common](https://github.com/Trinea/android-common)：包含与Android开发相关的工具类。
* [Twitter Commons](https://github.com/twitter-archive/commons)：Twitter开源的JVM公共库，已弃用。
* [RxTool](https://github.com/Tamsiree/RxTool)：RxTool是用于Android开发各式各样的工具类集合。
* [Indeed Util](https://github.com/indeedeng/util)：由Indeed开发的通用Java工具类。
* [JUtils](https://github.com/chenssy89/jutils)：JUtils包含通用的Java工具类库。
* [VJTools](https://github.com/vipshop/vjtools)：VJTools是由唯品会开源的Java编码标准、库和工具。
* [DevUtils](https://github.com/afkT/DevUtils)：DevUtils是一个Android工具库，主要根据不同功能模块，封装快捷使用的工具类及API方法调用。
* [SOFA Common](https://github.com/sofastack/sofa-common-tools)：SOFA Common是蚂蚁为其他SOFA库提供一些实用功能的库。
* [Commons Core](https://github.com/ponfee/commons-core)：Java工具类库。
* [XXL-TOOL](https://github.com/xuxueli/xxl-tool)：XXL-TOOL是一个Java工具类库，致力于让Java开发更高效。
* [ACS AEM Commons](https://github.com/Adobe-Consulting-Services/acs-aem-commons)：这是包含一组可重用组件和AEM开发工具包的项目，由Adobe开源。
* [Lazy](https://github.com/l123456789jy/Lazy)：Lazy包含一些常用的工具类。
* [XUtils](https://github.com/wyouflf/xUtils3)：XUtils包含了ORM、HTTP、图片处理等工具类。
* [LogiCommon](https://github.com/didi/LogiCommon)：LogiCommon包含认证、鉴权、管理、任务调度通用功能组件，由滴滴开源。
* [Camellia](https://github.com/netease-im/camellia)：Camellia是网易云信开发的服务器基础组件。
* [CommonUtil](https://github.com/LJWLgl/CommonUtil)：CommonUtil是一个轻便简单的Java常用工具类库。
* [JD Commons](https://mvnrepository.com/artifact/com.jd.utils)：京东开源的用于Java开发的公共库。
* [Shawn Common Utils](https://github.com/shawntime/shawn-common-utils)：Java整理的基础工具类项目。
* [Netflix Commons](https://github.com/Netflix/netflix-commons)：Netflix OSS项目的常用工具类。
* [Confluent Commons](https://github.com/confluentinc/common)：Confluent开源的包含指标、配置和工具类的通用库。
* [LinkedIn Utils](https://github.com/LinkedInAttic/linkedin-utils)：所有Linkedin开源项目共享的基础工具类。
* [Java Util](https://github.com/metamx/java-util)：Metamarkets开源的Java和基于JVM语言的工具类代码。
* [Plexus Utils](https://github.com/codehaus-plexus/plexus-utils)：各种工具类的集合，可轻松处理字符串、文件、命令行等。
* [Android Utils](https://github.com/jingle1267/android-utils)：囊括了一大部分Android应用开发过程当中常用的工具类。
* [Desugar JDK Libs](https://github.com/google/desugar_jdk_libs)：该项目包含一小部分经过简化的OpenJDK库，可以在较旧的运行时上使用，由Google开源。
* [Triava](https://github.com/trivago/triava)：Triava项目包含几个trivago的基于Java项目的核心库：缓存、集合、注解、并发库等等。
* [Bus](https://github.com/aoju/bus)：Bus是一个基础框架、服务套件，基于Java 17+编写。
* [Java Util](https://github.com/jdereg/java-util)：Java Util提供非常多与其他工具库功能不同的实用程序。
* [SoftwareMill Common](https://github.com/softwaremill/scala-common)：SoftwareMill开发的一些通用工具类。
* [LiteCommon](https://github.com/litesuits/android-common)：LiteCommon是一个Android工具库。
* [Twitter Util](https://github.com/twitter/util)：由Twitter开源的惯用、小型、通用工具库。
* [KillBill Commons](https://github.com/killbill/killbill-commons)：KillBill的可重用Java组件。
* [SonarQube Commons](https://github.com/SonarSource/sonar-scanner-commons)：该项目是许多SonarScanner使用的通用Java库。
* [IU Java Util](https://github.com/indiana-university/iu-java-util)：印第安纳大学开源的Java项目工具库。
* [CTS Common](https://bitbucket.org/UVM-BIRD/ccts-common)：CTS Common是佛蒙特大学临床和转化科学中心开发的项目中使用的一组通用库。
* [JTOpen](https://github.com/IBM/JTOpen)：JTOpen提供了一组Java类，使应用程序能够与IBM集成。
* [Scar](https://github.com/EsotericSoftware/scar)：Scar是一个实用程序集合，可让你更轻松地使用Java代码执行构建相关任务。
* [Nrich](https://github.com/croz-ltd/nrich)：Nrich是CROZ开发的一个Java库，其目的是使JVM上的应用程序开发更加容易。
* [IEP](https://github.com/Netflix/iep)：IEP是由Netflix的Insight工程团队使用的一组基础库，用于支持需要在内部和外部运行的应用程序。
* [XWiki Commons](https://github.com/xwiki/xwiki-commons)：XWiki Commons是其他几个顶级XWiki项目通用的技术库。
* [CommonUtilLibrary](https://github.com/AbrahamCaiJin/CommonUtilLibrary)：CommonUtilLibrary包含大量的Java工具类。

## Bean映射&复制

* [MapStruct](https://github.com/mapstruct/mapstruct)：MapStruct是一个Java注解处理器，用于为Java bean类生成类型安全且高性能的映射器。
* [MapStruct Plus](https://github.com/linpeilie/mapstruct-plus)：MapStruct Plus是对MapStruct框架的增强。
* [Dozer](https://github.com/DozerMapper/dozer)：Dozer是一种Java Bean到Java Bean映射器，它将数据从一个对象递归复制到另一个对象。
* [ModelMapper](https://github.com/modelmapper/modelmapper)：ModelMapper是一个智能对象映射库，可以自动将对象相互映射。
* [Orika](https://github.com/orika-mapper/orika)：Orika是一种Java Bean映射框架，可将数据从一个对象递归复制到另一个对象。
* [EasyMapper](https://github.com/EasyMapper/EasyMapper)：EasyMapper是一个易于使用的Java对象映射库，旨在简化表示域中对象的模型之间映射值的过程。
* [JMapper](https://github.com/jmapper-framework/jmapper-core)：JMapper是集优雅、高性能和稳健性于一体的Java Bean映射器。
* [Apache Commons Beanutils](https://github.com/apache/commons-beanutils)：Commons BeanUtils提供了一个易于使用但灵活的反射和内省包装器。
* [Apache Commons BeanUtils2](https://commons.apache.org/sandbox/commons-beanutils2/)：BeanUtils2是Commons BeanUtils库的完全重写，它被设计为一种流式的API。
* [Selma](https://github.com/xebia-france/selma)：可以在编译时生成Java代码处理字段到字段映射的注解处理器。
* [BeanMapper](https://github.com/42BV/beanmapper)：Beanmapper是一个Java库，用于将不同的Java类映射为相似的名称。
* [Tamper](https://github.com/alibaba/tamper)：Tamper是一款处理Bean/Map进行属性复制映射的工具，支持递归、集合等深度映射，由阿里开源。
* [ReMap](https://github.com/remondis-it/remap)：ReMap简化了对象逐个字段的转换，并大大减少了单元测试映射器类的工作量。
* [Bull](https://github.com/ExpediaGroup/bull)：Bull是一种Java Bean到Java Bean转换器，通用、灵活、可重用、可配置，并且速度非常快，由Expedia开源。
* [Datus](https://github.com/roookeee/datus)：Datus能够在流式的函数式API中定义两个数据结构之间的转换过程。
* [Crane4j](https://github.com/opengoofy/crane4j)：一个简单易用的数据映射框架，通过简单的注解配置快速根据外键/编码值填充相关字段，支持字典、枚举、方法等多种数据源。
* [Cloning](https://github.com/kostaskougios/cloning)：Cloning是一个小型开源Java库，可深度克隆对象。
* [BeanUtils](https://github.com/yangtu222/BeanUtils)：BeanUtils库是一个Java bean复制实用程序，具有强大的功能和高性能。
* [ShapeShift](https://github.com/krud-dev/shapeshift)：ShapeShift是用于智能对象映射和对象之间转换的Kotlin/Java库。
* [EasyMapper](https://github.com/neoremind/easy-mapper)：EasyMapper是一个简单、轻量级、高性能的Java bean映射框架，百度开源。

## IoC

* [Spring](https://github.com/spring-projects/spring-framework)：Spring框架是Java平台的一个开源全栈应用程序框架和控制反转容器实现，由Pivotal开源。
* [Guice](https://github.com/google/guice)：Guice是一个适用于Java 8及更高版本的轻量级依赖注入框架，由Google开源。
* [Dagger](https://github.com/google/dagger)：Dagger是一个用于依赖注入的编译时框架，它不使用反射或运行时字节码生成，在编译时进行所有分析，并生成纯Java源代码，由Square开源。
* [Koin](https://github.com/InsertKoinIO/koin)：Koin是一个面向Kotlin开发人员的实用轻量级依赖注入框架。
* [Motif](https://github.com/uber/motif)：Motif是一个DI库，提供针对嵌套作用域优化的简单API，由Uber开源。
* [MacWire](https://github.com/softwaremill/macwire)：MacWire是SoftwareMill开源的轻量级、非侵入式Scala依赖注入库。
* [Kotlin Inject](https://github.com/evant/kotlin-inject)：Kotlin Inject是Kotlin的编译时依赖注入库。
* [PicoContainer](https://github.com/picocontainer/picocontainer)：PicoContainer是非常轻量级的IoC容器，提供依赖注入和对象生命周期管理的功能。
* [Avaje Inject](https://github.com/avaje/avaje-inject)：面向Java和Kotlin开发人员的快速、轻型依赖注入库。
* [GlassFish HK2](https://github.com/eclipse-ee4j/glassfish-hk2)：GlassFish HK2是Jakarta依赖注入的实现。
* [Micronaut Inject](https://github.com/micronaut-projects/micronaut-core/tree/4.6.x/inject)：Micronaut框架核心依赖注入和控制反转模块。
* [Apache DeltaSpike](https://github.com/apache/deltaspike)：DeltaSpike是一套可移植的CDI扩展，旨在使使用CDI和Java EE时的应用程序开发变得更加容易。
* [Javax Inject](https://github.com/javax-inject/javax-inject)：Javax Inject是JSR-330依赖注入标准。
* [CDI](https://www.cdi-spec.org/)：Java的上下文和依赖注入规范。
* [Java IoC](https://github.com/ibm/java-ioc)：由IBM开发的Java控制反转框架。
* [Apache OpenEJB](https://openejb.apache.org/)：OpenEJB是一个开源、可嵌入、轻量级的EJB容器系统和EJB服务器。
* [Apache OpenWebBeans](https://github.com/apache/openwebbeans)：OpenWebBeans是CDI 2.0规范的实现。
* [Eclipse Sisu](https://github.com/eclipse/sisu.inject)：Sisu是一个基于JSR330的模块化容器，支持类路径扫描、自动绑定和动态自动装配。
* [Weld](https://github.com/weld/core)：Weld是CDI的参考实现，由RedHat开源。
* [Coody](https://gitee.com/coodyer/Coody-Framework)：Coody是一个国产IoC框架，轻量级、简单快速。
* [Scaldi](https://github.com/scaldi/scaldi)：Scaldi提供了一种简单而优雅的方式在Scala中进行依赖注入。
* [Kodein](https://github.com/kosi-libs/Kodein)：Kodein是一个简单但非常有用的依赖项检索容器，使用和配置都很轻松。
* [Transfuse](https://github.com/johncarl81/transfuse)：Transfuse是一个专门针对Google Android API的Java依赖注入和集成库。
* [Governator](https://github.com/Netflix/governator)：Governator是一个扩展和工具库，可增强Google Guice以提供注入器生命周期，并通过@PostConstruct和@PreDestroy支持对象生命周期，由Netflix开源。
* [Toothpick](https://github.com/stephanenicolas/toothpick)：Toothpick是一个基于作用域树的Java依赖注入库。
* [Feather](https://github.com/zsoltherpai/feather)：Feather是一个适用于Java和Android的超轻量级依赖注入(JSR-330)库。
* [JayWire](https://github.com/vanillasource/jaywire)：JayWire是一个非常小、轻量级的Java 8依赖注入框架。
* [Unnamed Inject](https://github.com/unnamed/inject)：Unnamed Inject是一个零依赖、轻量级、快速的运行时依赖注入库，基于Guice。
* [Mini Spring](https://github.com/DerekYRC/mini-spring)：Mini Spring是简化版的Spring框架，能帮助你快速熟悉Spring源码和掌握Spring的核心原理。
* [Tiny Spring](https://github.com/code4craft/tiny-spring)：Tiny Spring是为了学习Spring的而开发的，可以认为是一个Spring的精简版。
* [OfficeFloor](https://github.com/officefloor/OfficeFloor)：OfficeFloor是一个IoC库，可以通过一流的程序构建应用程序。
* [Inverno](https://github.com/inverno-io/inverno-core)：Inverno项目为Java平台提供了控制反转和依赖注入框架，所有内容都在编译期间静态验证和完成。
* [JBoss MSC](https://github.com/jboss-msc/jboss-msc)：JBoss MSC是Java的轻量级高并发依赖注入容器。
* [SIRIUS Kernel](https://github.com/scireum/sirius-kernel)：提供通用核心类和依赖注入微内核，为所有SIRIUS应用程序提供支持。

## AOP

* [AspectJ](https://github.com/eclipse-aspectj/aspectj)：AspectJ是一个面向切面的框架，它扩展了Java语言。
* [JVM SandBox](https://github.com/alibaba/jvm-sandbox)：JVM SandBox是一种JVM的非侵入式运行期AOP解决方案，由阿里开源。
* [JBoss AOP](https://jbossaop.jboss.org/)：JBoss AOP是一个100%纯Java面向切面的框架，可在任何编程环境中使用或与我们的应用程序服务器紧密集成。
* [Apache Commons Weaver](https://github.com/apache/commons-weaver)：Commons Weaver提供了一种通过生成(“织入”)字节码到这些类中来增强已编译Java类的简单方法。
* [FastAOP](https://github.com/fast-light/fastaop)：FastAOP是一款基于Java注解处理器的轻量级高性能AOP框架。
* [Lancet](https://github.com/eleme/lancet)：Lancet是一个轻量级的Android AOP框架，由饿了么开源。
* [Jcabi Aspects](https://github.com/jcabi/jcabi-aspects)：Jcabi Aspects是有用的AspectJ切面和注解的集合。
* [AspectJX](https://github.com/HujiangTechnology/gradle_plugin_android_aspectjx)：AspectJX是基于AspectJ的AOP框架，同时支持Kotlin应用，由沪江科技开源。
* [Proxy](https://github.com/Ericsson/proxy)：Proxy是一个小而强大的拦截库，可以让你在运行时操作现有的对象和类行为，由爱立信开源。
* [CaesarJ](https://caesarj.org/)：CaesarJ是一种基于Java的新编程语言，它有助于实现更好的模块化和可重用组件的开发，由达姆城工业大学开源。
* [Matrix](https://github.com/Nepxion/Matrix)：Matrix是一款集成Spring AutoProxy，Spring Registrar和Spring Import Selector三种机制的AOP框架。

## 日志库

* [Apache Log4j](https://github.com/apache/logging-log4j1)：Log4j的初始版本，已经停止维护。
* [Apache Log4j2](https://github.com/apache/logging-log4j2)：Log4j2是一个多功能的工业级Java日志记录框架。
* [Logback](https://github.com/qos-ch/logback)：Logback是一个可靠、通用、快速且灵活的Java日志记录框架。
* [Apache Commons Logging](https://github.com/apache/commons-logging)：Commons Logging是一个瘦适配器，允许可配置地桥接到其他的日志系统。
* [Slf4j](https://github.com/qos-ch/slf4j)：SLF4J用作各种日志框架(例如JUL、Logback、Reload4j、Log4j2)的简单门面或抽象，允许最终用户在部署时插入所需的日志框架。
* [JUL](https://github.com/openjdk/jdk/tree/master/src/java.logging/share/classes/java/util/logging)：JUL提供Java平台核心日志记录工具的类和接口。
* [Flogger](https://github.com/google/flogger)：Flogger是一个流式的Java日志记录API，它支持多种功能，由Google开发。
* [Logstash](https://github.com/elastic/logstash)：Logstash是免费且开源的服务器端数据处理管道，能够从多个来源采集数据，转换数据，然后将数据发送到你最喜欢的仓库中。
* [Tinylog](https://github.com/tinylog-org/tinylog)：Tinylog是一个适用于Java、Kotlin、Scala和Android的轻量级日志框架。
* [Graylog](https://github.com/Graylog2/graylog2-server)：Graylog是一个免费开源的日志管理平台。
* [Blitz4j](https://github.com/Netflix/blitz4j)：Blitz4j是一个构建在Log4j之上的日志框架，用于减少争用并实现高度可扩展的日志记录，而不会影响应用程序性能特征，由Netflix开源。
* [Kotlin Logging](https://github.com/oshai/kotlin-logging)：Kotlin的轻量级多平台日志框架，方便且高性能的日志记录门面。
* [Apache DistributedLog](https://github.com/twitter-archive/distributedlog)：DistributedLog是一种高吞吐量、低延迟的复制日志服务，提供持久性、复制和强一致性，由Twitter开发。
* [JBoss Logging](https://github.com/jboss-logging/jboss-logging)：JBoss Logging是一个日志门面，可以绑定到不同的日志管理器。
* [Timbermill](https://github.com/salesforce/Timbermill)：Timbermill是专为ElasticSearch构建的高级开源日志服务，Salesforce开源。
* [Scala Logging](https://github.com/lightbend-labs/scala-logging)：Scala Logging是一个包装SLF4J的方便快捷的日志库，由Lightbend开源。
* [Logger](https://github.com/orhanobut/logger)：简单、功能强大的Android日志记录器。
* [BqLog](https://github.com/Tencent/BqLog)：BqLog是一款轻量级、高性能的日志系统，应用于《王者荣耀》等项目中，由腾讯开源。
* [Timbre](https://github.com/taoensso/timbre)：Timbre是纯Clojure/Script日志记录库。
* [Google Cloud Logging](https://github.com/googleapis/java-logging)：用于Java的Google Cloud Logging客户端库。
* [GFLog](https://github.com/epam/gflog)：GFLog是适用于Java 8+的高效无垃圾日志记录框架，由EPAM开源。
* [Timber](https://github.com/JakeWharton/timber)：Timber是一个带有小型可扩展API的记录器，它在Android的普通Log类之上提供实用程序。
* [MinLog](https://github.com/EsotericSoftware/minlog)：MinLog一个小型Java日志库，其特点是零开销、极其轻便、简单高效。
* [PlumeLog](https://gitee.com/plumeorg/plumelog)：PlumeLog是一个简单易用的Java分布式日志组件，由Plume社区开源。
* [Logbook](https://github.com/zalando/logbook)：Logbook是一个可扩展的Java库，可为不同的客户端和服务器端技术启用完整的请求和响应日志记录，由Zalando开源。
* [XLog](https://github.com/elvishew/xLog)：XLog是适用于Android和Java的轻量、强大且灵活的记录器。
* [TLog](https://gitee.com/dromara/TLog)：TLog是一个轻量级的分布式日志标记追踪神器，由dromara社区开源。
* [JLog](https://gitee.com/jd-platform-opensource/jlog)：JLog是京东开源的海量日志搜集、传输、存储解决方案。
* [P6Spy](https://github.com/p6spy/p6spy)：P6Spy是一个框架，无需对应用程序进行任何代码更改即可无缝拦截和记录数据库数据。
* [Fluent Logger](https://github.com/fluent/fluent-logger-java)：Fluent Logger是一个Java库，用于通过Fluentd从Java应用程序记录事件。
* [Chronicle Logger](https://github.com/OpenHFT/Chronicle-Logger)：Chronicle Logger是一个亚微秒Java记录器，支持标准日志记录API，例如SLF4j和Log4J。
* [CoralLog](https://www.coralblocks.com/index.php/category/corallog/)：CoralLog是一个非侵入式、无垃圾且超低延迟的异步Java日志记录/事件源库，可实现极高的吞吐量，而不会给应用程序执行增加延迟或差异。
* [Jcabi Log](https://github.com/jcabi/jcabi-log)：SLF4J的静态包装器，无需在每个Java类中创建静态LOGGER实例。
* [PLog](https://github.com/JumeiRdGroup/Android-PLog)：PLog项目是一个专为Android应用程序设计的开源日志封装库，由聚美优品开源。
* [PL4J](https://github.com/ludovicianul/pl4j)：PL4J是一个SLF4j包装器，可以通过jansi使用ANSI格式进行漂亮打印。
* [ObjectLogger](https://github.com/yeecode/ObjectLogger)：ObjectLogger是一个功能强大且易于使用的对象日志系统，支持对象属性变化的写入和查询。
* [Trojan](https://github.com/eleme/Trojan)：Trojan是一款稳定、高效的移动端轻量级日志SDK，饿了么开源。
* [AutoLog4j](https://github.com/AutohomeCorp/autolog4j)：AutoLog4j是汽车之家经销商技术部日志类库相关扩展。
* [Sensitive](https://github.com/houbb/sensitive)：Sensitive是基于注解的Java日志脱敏工具框架。
* [Spotify Logging](https://github.com/spotify/logging-java)：以Spotify兼容方式设置日志记录的工具类。
* [MinBox Logging](https://gitee.com/minbox-projects/minbox-logging)：MinBox Logging是一款分布式、零侵入式的链路日志分析框架。
* [LogUtils](https://github.com/pengwei1024/LogUtils)：更方便易用的Android日志管理器。
* [Singer](https://github.com/pinterest/singer)：Singer是一个高性能日志代理，用于将日志上传到Kafka，由Pinterest开源。
* [Log Record](https://github.com/qqxx6661/log-record)：Log Record可以通过Java注解优雅的记录操作日志，并支持SpEL表达式、自定义上下文、自定义函数、实体类DIFF等功能。
* [Logback Android](https://github.com/tony19/logback-android)：Logback Android是用于Android的精简版Logback。
* [Zerolog](https://github.com/obsidiandynamics/zerolog)：Zerolog是一个日志门面，适用于性能敏感应用程序。
* [Yolo](https://github.com/ustream/yolo)：Java中的日志尾随和解析框架，Ustream开源。
* [BizLog](https://github.com/mouzt/mzt-biz-log)：Spring Boot注解通用操作日志组件，美团员工开源。
* [Napier](https://github.com/AAkira/Napier)：Napier是Kotlin Multiplatform的记录器库。
* [KLogging](https://github.com/klogging/klogging)：KLogging是一个纯Kotlin日志库，它使用Kotlin习惯用法来创建记录器和发送日志事件。
* [Syslog4j](https://github.com/syslog4j/syslog4j)：Syslog4j提供Syslog协议(RFC 3164)和结构化Syslog协议(RFC 5424)的客户端和服务器实现，由JetBrains开源。
* [Log4JDBC](https://github.com/arthurblake/log4jdbc)：Log4JDBC是一个Java JDBC驱动程序，可以使用SLF4J记录其他JDBC驱动程序的SQL和/或JDBC调用。
* [OWASP Security Logging](https://github.com/augustd/owasp-security-logging)：用于记录安全相关事件的标准Java API。
* [TNT4J](https://github.com/Nastel/TNT4J)：TNT4J旨在通过易于使用的API来跟踪应用程序、活动、事务、行为和性能，其行为非常类似于日志记录框架。
* [Rainbow Gum](https://github.com/jstachio/rainbowgum)：Rainbow Gum是一个快速、小型、JDK 21+、GraalVM原生友好的SLF4J日志框架。
* [LogEvents](https://github.com/jhannes/logevents)：LogEvents是一个小型日志记录框架，构建在SLF4J之上。
* [Journal.IO](https://github.com/sbtourist/Journal.IO)：Journal.IO是一种轻量级、快速且易于使用的日志存储实现，基于仅追加旋转日志和校验和可变长度记录，支持并发读写、动态批处理、可调持久性和数据压缩。

## Logback Appender

* [Logback Elasticsearch Appender](https://github.com/internetitem/logback-elasticsearch-appender)：将日志事件直接从Logback发送到Elasticsearch。
* [Logstash Logback Encoder](https://github.com/logfellow/logstash-logback-encoder)：Logback JSON编码器和附加器。
* [Loki4j](https://github.com/loki4j/loki-logback-appender)：Loki4j的目标是成为Grafana Loki最快、最轻量级的Logback Appender实现。
* [Log4j2 ElasticSearch](https://github.com/rfoltyns/log4j2-elasticsearch)：这是Log4j2 Appender插件的父项目，能够将日志批量推送到Elasticsearch集群。
* [Splunk Logging](https://github.com/splunk/splunk-library-javalogging)：适用于流行Java日志框架的Splunk日志Appender。
* [Logback More Appender](https://github.com/sndyuk/logback-more-appenders)：Logback的附加Appender，可以毫无顾虑地提供更好的性能和数据一致性。
* [Logback Redis Appender](https://github.com/kmtong/logback-redis-appender)：将日志记录到Redis的Logback Appender。
* [Logback Kafka Appender](https://github.com/danielwegener/logback-kafka-appender)：此附加程序允许你的应用程序将日志直接发布到Apache Kafka。
* [Aliyun Log Logback Appender](https://github.com/aliyun/aliyun-log-logback-appender)：Aliyun Log Logback Appender可以将日志的目的地设置为阿里云日志服务。
* [Logback Elasticsearch Appender](https://github.com/agido-malter/logback-elasticsearch-appender)：直接从Logback发送日志事件到Elasticsearch。
* [Logback GELF](https://github.com/osiegmar/logback-gelf)：用于发送GELF消息的Logback Appender。
* [Logstash GELF](https://github.com/mp911de/logstash-gelf)：Graylog扩展日志格式(GELF)在Java中实现，适用于所有主要日志记录框架。
* [Logback Slack Appender](https://github.com/maricn/logback-slack-appender)：Slack通讯器的Logback附加器。
* [Tjahzi](https://github.com/tkowalcz/tjahzi)：Tjahzi是一组用于记录日志到Grafana Loki的Java工具和附加器。
* [GELFJ](https://github.com/t0xa/gelfj)：GELFJ是Java中非常简单的GELF实现，带有Log4j附加程序和JDK日志处理程序。

## 结构化日志

* [Java Grok](https://github.com/thekrakken/java-grok)：使用Java Grok，你可以将非结构化日志和事件数据转换为结构化数据(JSON)。
* [ECS Logging Java](https://github.com/elastic/ecs-logging-java)：ECS Logging Java可帮助开发者轻松地实现结构化日志。
* [Structured Logging](https://github.com/dm-drogeriemarkt/structured-logging)：构化日志实用程序，设计用于与Logback和Logstash配合使用。
* [Penna](https://github.com/hkupty/penna)：Penna是SLF4j的一个后端，专注于以JSON格式将结构化日志记录到控制台。
* [Terse Logback](https://github.com/tersesystems/terse-logback)：Terse Logback是Logback扩展的集合，功能包括结构化日志记录、跟踪和可观察性。
* [CloudFoundry Java Logging](https://github.com/SAP/cf-java-logging-support)：CloudFoundry的Java日志记录支持，可以创建结构化日志消息和收集请求指标，由SAP开源。
* [Echopraxia](https://github.com/tersesystems/echopraxia)：Echopraxia是一个围绕结构化日志记录设计的Java API。

## JSON库

* [Jackson](https://github.com/FasterXML/jackson)：Jackson是Java中使用最广泛的JSON库。
* [Gson](https://github.com/google/gson)：Gson是一个Java库，可用于将Java对象转换为其JSON表示形式，由Google开源。
* [Fastjson](https://github.com/alibaba/fastjson)：Fastjson是一个Java库，可用于将Java对象转换为其JSON表示形式，由阿里开源。
* [Fastjson 2](https://github.com/alibaba/fastjson2)：Fastjson 2是一个性能极致并且简单易用的Java JSON库，由阿里开源。
* [Moshi](https://github.com/square/moshi)：Moshi是一个适用于Android、Java和Kotlin的现代JSON库，由Square开源。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：适用于Android的最快JSON解析和序列化库。
* [JSON-Java](https://github.com/stleary/JSON-java)：JSON-Java包是一个参考实现，可以将JSON文档解析为Java对象以及从Java类生成新的JSON文档。
* [Flexjson](https://flexjson.sourceforge.net/)：Flexjson是一个轻量级库，用于将Java对象序列化为JSON。
* [Circe](https://github.com/circe/circe)：Circe是Scala的JSON库。
* [Klaxon](https://github.com/cbeust/klaxon)：Klaxon是一个在Kotlin中解析JSON的库。
* [JSON4S](https://github.com/json4s/json4s)：JSON4S旨在提供一个可供其他Scala JSON库使用的单一AST。
* [JSON-lib](https://json-lib.sourceforge.net/)：JSON-lib是一个Java库，用于将Bean、Map、集合、Java数组和XML转换为JSON，然后再转换回Bean。
* [JSON.Simple](https://github.com/fangyidong/json-simple)：JSON.Simple是一个简单的JSON Java工具包。
* [JSON Schema Validator](https://github.com/everit-org/json-schema)：用于Java的JSON模式验证器，基于org.json API。
* [Jakarta JSON Processing](https://github.com/jakartaee/jsonp-api)：Jakarta JSON Processing提供可移植的API来解析、生成、转换和查询JSON文档。
* [Eclipse Yasson](https://github.com/eclipse-ee4j/yasson)：Yasson是一个Java框架，它在Java类和JSON文档之间提供标准绑定层。
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON)：HikariJSON是一个高性能JSON解析器。
* [Eclipse Parsson](https://github.com/eclipse-ee4j/parsson)：Parsson是Jakarta JSON-P规范的实现。
* [JsonLube](https://github.com/alibaba/JsonLube)：JsonLube可以在编译期自动生成JSON解析代码，用户使用方式更简单，同时能收获原生解析的性能，由阿里开发。
* [JSON-IO](https://github.com/jdereg/json-io)：小巧、轻量级的JSON和Java对象转换库。
* [Jsoniter](https://github.com/json-iterator/java)：Jsoniter是Java中可用的快速灵活的JSON解析器。
* [Event Ruler](https://github.com/aws/event-ruler)：Event Ruler是一个Java库，允许每秒将数千个事件与任意数量的富有表现力和复杂的规则相匹配，由Amazon开源。
* [Genson](https://github.com/owlike/genson)：Genson是一个完整的JSON Java转换库，提供完整的数据绑定、流媒体等等。
* [Jsonschema2Pojo](https://github.com/joelittlejohn/jsonschema2pojo)：Jsonschema2Pojo从JSON或JSON Schema生成Java类型，并标注这些类型以与Jackson、Gson等进行数据绑定。
* [DSL-JSON](https://github.com/ngs-doo/dsl-json)：最快的JVM JSON库，具有高级编译时数据绑定支持。
* [Ason](https://github.com/afollestad/ason)：Ason旨在使JSON非常容易在Java中进行交互。
* [JSONLD-Java](https://github.com/jsonld-java/jsonld-java)：这是JSON-LD 1.0规范和JSON-LD-API 1.0规范的Java实现。
* [Instagram JSON Parser](https://github.com/Instagram/ig-json-parser)：用于Java项目的快速JSON解析器，由Instagram开源。
* [Minimal JSON](https://github.com/ralfstx/minimal-json)：Minimal Json是用于Java的快速且最小的JSON解析器和编写器。
* [JSON Patch](https://github.com/java-json-tools/json-patch)：这是用Java编写的RFC 6902(JSON Patch)和RFC 7386(JSON Merge Patch)的实现。
* [Json-Smart](https://github.com/netplex/json-smart-v2)：Json-Smart是一个高性能JSON处理器库。
* [JSON Sanitizer](https://github.com/OWASP/json-sanitizer)：JSON Sanitizer可以将类似JSON的内容转换为有效的JSON，由OWASP开源。
* [CodeJson](https://gitee.com/eric_ds/jfire-codejson)：CodeJson是性能非常高的JSON序列化和反序列化库。
* [Sawmill](https://github.com/logzio/sawmill)：Sawmill是一个JSON转换Java库。
* [Katharsis](https://github.com/katharsis-project/katharsis-framework)：Katharsis实现了JSON API标准，引入了一致的REST接口定义，可以通过统一的机制轻松地与其他系统集成。
* [JSON Schema Validator](https://github.com/networknt/json-schema-validator)：这是用于JSON模式校验的JSON Schema Core Draft规范的Java实现。
* [Apache Johnzon](https://github.com/apache/johnzon)：Johnzon提供JSON P实现和该规范的一组有用扩展。
* [JsonBeans](https://github.com/EsotericSoftware/jsonbeans)：JsonBeans是一个轻量级库，可轻松将Java对象图序列化为JSON或从JSON反序列化。
* [SIMDJson Java](https://github.com/simdjson/simdjson-java)：simdjson的官方Java版本-使用SIMD指令的JSON解析器。
* [JSON Schema Validator](https://github.com/java-json-tools/json-schema-validator)：Java中的纯JSON模式验证实现，具有可靠的正确性和性能。
* [Jolt](https://github.com/bazaarvoice/jolt)：使用Java编写的JSON到JSON转换库，由Bazaarvoice开源。
* [Boon](https://github.com/boonproject/boon)：Boon是一个简单的基于Java的JSON工具包，你可以使用Boon以高效且快速的方式对JSON数据进行编码或解码。
* [Hjson Java](https://github.com/hjson/hjson-java)：Hjson格式的Java实现。
* [Avaje JsonB](https://github.com/avaje/avaje-jsonb)：通过APT源代码生成进行快速、无反射的JSON绑定的Java库。
* [JSON-RPC](https://github.com/briandilley/jsonrpc4j)：该项目旨在为Java编程语言提供轻松实现JSON-RPC的工具。
* [NanoJson](https://github.com/mmastrac/nanojson)：NanoJson是一个小型、兼容的Java JSON解析器和写入器。
* [JSON Schema Generator](https://github.com/victools/jsonschema-generator)：用于从Java类创建JSON模式(Draft 6、Draft 7、Draft 2019-09或Draft 2020-12)。
* [JSON Flattener](https://github.com/wnameless/json-flattener)：JSON Flattener可以扁平化嵌套的JSON对象，反之亦然。
* [JSLT](https://github.com/schibsted/jslt)：JSLT是一种完整的JSON查询和转换语言。
* [ZJSONPatch](https://github.com/flipkart-incubator/zjsonpatch)：这是用Java编写的RFC 6902 JSON Patch的实现，由Flipkart开源。
* [JSON Data Generator](https://github.com/everwatchsolutions/json-data-generator)：一个强大、通用的流式随机JSON数据生成器。
* [BSON4Jackson](https://github.com/michel-kraemer/bson4jackson)：该库向Jackson JSON处理器添加了对BSON的支持。
* [Jackson-JQ](https://github.com/eiiches/jackson-jq)：Jackson JSON处理器的纯Java jq实现。
* [Json Comparison](https://github.com/eBay/json-comparison)：强大的JSON比较工具，用于识别JSON文件中的所有更改，由eBay开源。
* [EasyJSON](https://github.com/bes2008/easyjson)：EasyJSON是一个JSON门面库，就像SLF4j一样。
* [Titanium JSON-LD](https://github.com/filip26/titanium-json-ld)：JSON-LD 1.1处理器和API。
* [JSON-Lib](https://github.com/kordamp/json-lib)：JSON-Lib是一个Java库，用于将Bean、Map、集合、Java数组和XML转换为JSON，然后再转换回Bean和DynaBeans。
* [Justify](https://github.com/leadpony/justify)：Justify是一个基于JSON模式规范和Jakarta JSON-P的JSON验证器。
* [Noggit](https://github.com/yonik/noggit)：Noggit是一个极快的Java流式JSON解析器。
* [JSONata4Java](https://github.com/IBM/JSONata4Java)：JSONata的开源Java版本，由IBM提供。
* [Actson](https://github.com/michel-kraemer/actson)：Actson是一个响应式JSON解析器。
* [JSONCoder](https://github.com/eBay/jsonex)：Jsonex JSONCoder是一个轻量级通用对象序列化/反序列化库，该库多年来已在各种eBay项目中广泛使用。
* [Functional JSON](https://github.com/MAIF/functional-json)：以函数式方式解析和写入JSON。
* [JSON Masker](https://github.com/Breus/json-masker)：Java中的高性能JSON掩码库，无运行时依赖。
* [StAXON](https://github.com/beckchr/staxon)：StAXON允许你使用javax.xml.stream读取和写入JSON。
* [JDocs](https://github.com/americanexpress/unify-jdocs)：JDocs是一个JSON操作库，它完全消除了对模型/POJO类的需要，而是直接在JSON文档上工作，由美国运通开源。
* [Hope](https://github.com/santanusinha/hope)：Hope是一种用Java编写的用于对JSON进行谓词评估的高级语言。
* [JSON Canonicalization](https://github.com/cyberphone/json-canonicalization)：JSON Canonicalization Scheme的Java实现。
* [JSON Compare](https://github.com/fslev/json-compare)：用于比较JSON的Java库。
* [JSONx Java](https://github.com/jsonx-org/java)：JSONx Java为JSON模式定义语言处理器、验证器和运行时API提供参考实现。
* [Squiggly](https://github.com/bohnman/squiggly)：Squiggly是一个Jackson JSON PropertyFilter，它使用Facebook Graph API过滤语法的子集选择对象/列表/映射的属性。

## JsonPath

* [JsonPath](https://github.com/json-path/JsonPath)：JsonPath的实现版本，用于读取JSON文档的Java DSL。
* [Snack3](https://gitee.com/noear/snack3)：Snack3是一个高性能的JsonPath框架，支持序列化反序列化、解析和转换、构建、查找、JsonPath查询。
* [JsonSurfer](https://github.com/wanglingsong/JsonSurfer)：Java中的流式JsonPath处理器。
* [JMESPath Java](https://github.com/burtcorp/jmespath-java)：这是JMESPath的Java实现。
* [Vert.x JsonPath](https://github.com/NoEnv/vertx-jsonpath)：Vert.x JsonPath是使用Vert.x的JsonObject和JsonArray对JsonPath的一个非常基本的实现。

## 序列化

* [Hessian](http://hessian.caucho.com/)：Hessian是一种基于二进制的轻量级网络传输协议，用于在不同的应用程序之间进行远程过程调用，由Caucho开源。
* [FlatBuffers](https://github.com/google/flatbuffers)：FlatBuffers是一个跨平台序列化库，旨在实现最大内存效率，由Google开源。
* [Ysoserial](https://github.com/frohoff/ysoserial)：Ysoserial是一种概念验证工具，用于生成利用不安全的Java对象反序列化的有效负载。
* [Apache Avro](https://github.com/apache/avro)：Avro是一个数据序列化系统。
* [Protostuff](https://github.com/protostuff/protostuff)：Protostuff是一个Java序列化库，内置对向前向后兼容性(模式演化)和验证的支持。
* [Apache Fury](https://github.com/apache/incubator-fury)：Fury是一种速度极快的多语言序列化框架，由JIT和零拷贝提供支持，可提供高达170倍的性能和终极易用性，阿里开源。
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：完全兼容JDK序列化协议的Java序列化框架，在序列化速度上能达到JDK的10倍。
* [MessagePack](https://github.com/msgpack/msgpack-java)：Java的MessagePack序列化器实现。
* [Serial](https://github.com/twitter/Serial)：Serial是一种自定义序列化实现，旨在提高性能并增加开发人员对对象序列化的可见性和控制，由Twitter开源。
* [Swift](https://github.com/facebookarchive/swift)：Swift是一个易于使用、基于注解的Java库，用于创建Thrift可序列化类型和服务，由Facebook开源。
* [Ion Java](https://github.com/amazon-ion/ion-java)：Ion数据表示法的Java实现，由Amazon开源。
* [SOFA Hessian](https://github.com/sofastack/sofa-hessian)：SOFA Hessian基于原生Hessian v4.0.51进行改进，目前已在蚂蚁金服内部稳定运行多年。
* [Colfer](https://github.com/pascaldekloe/colfer)：Colfer是一种针对速度和大小进行优化的二进制序列化格式。
* [Chronicle Wire](https://github.com/OpenHFT/Chronicle-Wire)：支持多种格式的低垃圾Java序列化库。
* [Bond](https://github.com/microsoft/bond)：Bond是一个用于处理模式化数据的跨平台框架，支持跨语言反/序列化和强大的通用机制，可有效地操作数据，Microsoft开源。
* [Kryo](https://github.com/EsotericSoftware/kryo)：Kryo是一个快速高效的Java二进制对象图序列化框架。
* [CoralProto](https://github.com/coralblocks/CoralProto)：一种快速、二进制、无垃圾的序列化框架，具有简单、紧凑和简洁的非XML模式定义语言，支持可选字段、重复组、嵌套重复组、枚举、模式演变等。
* [OpenRTB](https://github.com/google/openrtb)：该库支持OpenRTB规范，为所有protobuf支持的语言提供绑定，并为Java提供额外支持，例如JSON序列化和验证，由Google开源。
* [uPickle](https://github.com/com-lihaoyi/upickle)：uPickle是一个简单、快速、无依赖的Scala JSON和二进制(MessagePack)序列化库。
* [Reservoir](https://github.com/anupcowkur/Reservoir)：Reservoir是一个简单的Android库，允许你使用键/值对轻松序列化对象并将其缓存到磁盘。
* [Eclipse Serializer](https://github.com/eclipse-serializer/serializer)：Serializer项目可以对任何Java对象进行(反)序列化，而无需生成代码的注解、超类或接口或数据模式。
* [VelocyPack Java](https://github.com/arangodb/java-velocypack)：VelocyPack(用于序列化和存储的快速而紧凑的格式)的Java实现。
* [Kryo Serializers](https://github.com/magro/kryo-serializers)：一个为某些JDK类型和一些外部库(例如JodaTime)提供Kryo(v2、v3、v4)序列化器的项目。
* [Fast Binary Encoding](https://github.com/chronoxor/FastBinaryEncoding)：Fast Binary Encoding是适用于C++、C#、Go、Java、JavaScript、Kotlin、Python、Ruby、Swift的超快速通用序列化解决方案。
* [Fressian](https://github.com/Datomic/fressian)：Fressian是一种可扩展的二进制数据表示法。
* [Zserio](https://github.com/ndsev/zserio)：Zserio是一个以紧凑、高效、低开销的方式序列化结构化数据的框架。
* [Chill](https://github.com/twitter/chill)：Kryo序列化库的扩展，包括序列化器和一组类，以简化Hadoop、Storm、Akka等系统中Kryo的配置，由Twitter开源。
* [ProtoStream](https://github.com/infinispan/protostream)：ProtoStream是一个基于Protobuf数据格式的序列化库。

## 缓存库

* [Guava Cache](https://github.com/google/guava/tree/master/guava/src/com/google/common/cache)：Google Guava库提供的Java本地缓存工具。
* [Caffeine](https://github.com/ben-manes/caffeine)：Caffeine是一个高性能、接近最佳的缓存库。
* [Ehcache](https://github.com/ehcache/ehcache3)：Ehcache是一种基于标准的开源缓存，可提高性能、减轻数据库负载并简化可扩展性，由Terracotta公司开源。
* [Apache Commons JCS](https://github.com/apache/commons-jcs)：Commons JCS是一个分布式、多功能的缓存系统。
* [JetCache](https://github.com/alibaba/jetcache)：JetCache是一种Java缓存抽象，它为不同的缓存解决方案提供统一的使用方式，由阿里开源。
* [DiskLruCache](https://github.com/JakeWharton/DiskLruCache)：基于磁盘的LRU缓存的Java实现，专门针对Android兼容性。
* [ASimpleCache](https://github.com/yangfuhai/ASimpleCache)：ASimpleCache是一个为Android制定的轻量级开源缓存框架。
* [RxCache](https://github.com/VictorAlbertos/RxCache)：适用于Android和Java的响应式缓存库。
* [EVCache](https://github.com/Netflix/EVCache)：EVCache是一个基于Memcached和Spymemcached的缓存解决方案，主要用于AWS EC2基础设施来缓存常用数据，由Netflix开源。
* [Cache2K](https://github.com/cache2k/cache2k)：Cache2K是一个内存中高性能Java缓存库。
* [HotKey](https://gitee.com/jd-platform-opensource/hotkey)：京东App后台中间件，毫秒级探测热点数据，毫秒级推送至服务器集群内存，大幅降低热key对数据层查询压力。
* [MicroStream](https://github.com/microstream-one/microstream)：MicroStream是一个突破性的Java原生对象图持久层，专为需要轻量级高性能持久层的微服务和Serverless函数而构建。
* [ECFileCache](https://github.com/XiaoMi/ECFileCache)：ECFileCache是一个分布式文件缓存，基于Erasure Code，使用Redis进行存储，由小米开发。
* [AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache)：AutoLoadCache是基于AOP、注解等技术实现的高效的缓存管理解决方案。
* [J2Cache](https://gitee.com/ld/J2Cache)：J2Cache是OSChina目前正在使用的二级缓存框架。
* [XXL-Cache](https://github.com/xuxueli/xxl-cache)：XXL-Cache是一个分布式缓存管理平台，其核心设计目标是让分布式缓存的接入和管理的更加的简洁和高效。
* [OHC](https://github.com/snazy/ohc)：Java堆外缓存解决方案。
* [KCache](https://github.com/rayokota/kcache)：KCache是一个客户端库，它提供由Kafka中的压缩主题支持的内存缓存。
* [Cache4j](https://cache4j.sourceforge.net/)：Java对象的缓存，简单的API和快速的实现。
* [Imcache](https://github.com/Cetsoft/imcache)：Imcache是一个Java缓存库，旨在通过提供管理缓存数据的方法来加速应用程序。
* [JCache RI](https://github.com/jsr107/RI)：JCache的参考实现。
* [Xanthic](https://github.com/Xanthic/cache-api)：该库提供了一个简化的接口，用于与JVM上的内存缓存实现进行交互。
* [OffHeap Store](https://github.com/Terracotta-OSS/offheap-store)：OffHeap Store是一个库，提供一组Map和缓存实现，用于在普通Java堆之外存储数据。
* [Apache DirectMemory](https://directmemory.apache.org/)：DirectMemory是JVM的堆外缓存。
* [CarbonJ](https://github.com/salesforce/carbonj)：CarbonJ是Carbon-cache和Carbon-relay的直接替代品，它在设计时考虑了高性能读写吞吐量，支持写入数百万个指标数据点，并以低查询延迟每分钟提供数百万个指标数据点。
* [BlazingCache](https://github.com/diennea/blazingcache)：BlazingCache是分布式Java应用程序的快速缓存。

## 集合库

* [Apache Commons Collections](https://github.com/apache/commons-collections)：Commons Collections包含扩展和增强Java集合框架的类型。
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections)：Eclipse Collections是一个综合性的Java集合库，通过提供一组富有表现力且高效的API和类型来提高生产力和性能，由高盛银行开源。
* [Fastutil](https://github.com/vigna/fastutil)：Fastutil通过提供特定类型的Map、Set、List和Queue来扩展Java集合框架，由米兰大学开发。
* [HPPC](https://github.com/carrotsearch/hppc)：HPPC使用特化版本实现典型集合(List、Deque、Set、Map)，这些版本存储原始类型而不将它们装箱为对象。
* [PCollections](https://github.com/hrldcpr/pcollections)：PCollections充当Java集合框架的持久且不可变的类似物。
* [CQEngine](https://github.com/npgall/cqengine)：CQEngine是一个高性能Java集合，可以使用类似SQL的查询进行搜索，并且延迟极低。
* [Agrona](https://github.com/real-logic/agrona)：Agrona提供了一个数据结构和实用方法库，这是用Java构建高性能应用程序时常见的需求。
* [Koloboke](https://github.com/leventov/Koloboke)：Koloboke是精心设计的Java集合框架扩展，具有原始类型特化等功能。
* [Javolution](https://github.com/javolution/javolution)：用于实时和嵌入式系统的Java核心库。
* [Trove](https://bitbucket.org/trove4j/trove/src/master/)：Trove库为Java提供高速对象和原始集合。
* [Yammer Collections](https://github.com/yammer/yammer-collections)：Yammer使用的集合工具库，建立在Guava和标准集合库之上。
* [Dexx Collections](https://github.com/andrewoma/dexx)：Dexx Collections是Scala不可变、持久集合类到纯Java的移植。
* [Primitive Collections](https://github.com/Speiger/Primitive-Collections)：Primitive Collections是一个原始集合库，可减少内存使用并提高性能。
* [Capsule](https://github.com/usethesource/capsule)：Capsule旨在成为Java 11+的成熟不可变集合库。
* [LMAX Collections](https://github.com/LMAX-Exchange/LMAXCollections)：由英国外汇交易公司LMAX开发的高性能集合库。
* [Paguro](https://github.com/GlenKPeterson/Paguro)：JVM的泛型、空安全、不可变集合和函数式转换。
* [LambdaJ](https://github.com/mariofusco/lambdaj)：LambdaJ允许以伪函数和静态类型的方式操作集合。
* [Persistent Collections](https://github.com/pmem/pcj)：Java的持久集合库。
* [Jcabi Immutable](https://github.com/jcabi/jcabi-immutable)：该模块包含真正不可变的对象集合，包括Array、ArraySet和ArrayMap。

## 并发编程

* [AsyncTool](https://gitee.com/jd-platform-opensource/asyncTool)：AsyncTool是解决任意的多线程并行、串行、阻塞、依赖、回调的并行框架，来自于京东主App后台。
* [ZIO](https://github.com/zio/zio)：ZIO是一个用于异步和并发编程的零依赖Scala库。
* [Trickle](https://github.com/spotify/trickle)：Trickle是一个用于编写异步代码的小型库，由Spotify开源。
* [JDeferred](https://github.com/jdeferred/jdeferred)：JDeferred是一个Java Deferred/Promise库，类似于JQuery的Deferred Object。
* [Concurrentli](https://github.com/linkedin/concurrentli)：Concurrentli扩展了java.util.concurrent的多线程类，为多线程Java程序增加了便利性、效率和新工具，由LinkedIn开源。
* [Menagerie](https://github.com/sfines/menagerie)：Menagerie是基于ZooKeeper的Java并发库。
* [PCDP](https://github.com/habanero-rice/PCDP)：PCDP是一个共享内存、教学型、并行编程框架，由佐治亚理工学院开源。
* [Thread Affinity](https://github.com/OpenHFT/Java-Thread-Affinity)：该库允许你将线程绑定到给定核心，这可以提高性能。
* [CoralThreads](https://www.coralblocks.com/index.php/category/coralthreads/)：CoralThreads允许你将Java线程固定到独立的CPU核心。
* [Chronicle Threads](https://github.com/OpenHFT/Chronicle-Threads)：该库提供高性能事件循环实现和实用函数来帮助处理线程和并发。
* [Atlassian Concurrent](https://bitbucket.org/atlassian/atlassian-util-concurrent)：该项目包含Atlassian内部各种产品和项目使用的并发实用程序类。
* [TaskManager](https://github.com/iqiyi/TaskManager)：TaskManager是一种支持依赖关系、任务兜底策略的任务调度管理工具，由爱奇艺开发。
* [Gobrs-Async](https://gitee.com/dromara/gobrs-async)：Gobrs-Async是一款功能强大、配置灵活、带有全链路异常回调、内存优化、异常状态管理于一身的高性能多线程并发编程和动态编排框架，由dromara社区开源。
* [ParSeq](https://github.com/linkedin/parseq)：ParSeq是一个可以更轻松地用Java编写异步代码的框架，LinkedIn开源。
* [Conditional](https://github.com/line/conditional)：Conditional是一个超轻量级库，可帮助你组合多个条件表达式并使它们轻松异步，由Line开源。
* [BascomTask](https://github.com/eBay/bascomtask)：Java的轻量级、低摩擦进程内并行任务管理，由eBay开源。
* [High Scale Lib](https://github.com/boundary/high-scale-lib)：High Scale Lib是并发且高度可扩展的实用程序的集合，由BMC开源。
* [GPars](https://github.com/GPars/GPars)：GPars框架为Java开发人员提供了直观且安全的方法来同时处理Java或Groovy任务。
* [Nodes](https://github.com/twitter/nodes)：Nodes是一个用Java实现服务异步依赖图的库，由Twitter开源。
* [AsyncLoad](https://github.com/alibaba/asyncload)：AsyncLoad是阿里的异步并行加载工具。
* [Ox](https://github.com/softwaremill/ox)：开发人员友好的JVM结构化并发库，基于Project Loom。
* [Lois](https://github.com/flipkart-incubator/Lois)：Lois是一个Java库，提供类似GoLang的Channel抽象和实现，由Flipkart开源。
* [Jetlang](https://github.com/jetlang/core)：Jetlang提供了一个高性能的Java线程库。
* [JOX](https://github.com/softwaremill/jox)：Java中的快速且可扩展的Channel，设计用于与Project Loom一起使用。
* [Async](https://github.com/OpenTSDB/async)：受Twisted API启发的异步Java处理构建块。
* [TwTasks](https://github.com/transferwise/tw-tasks-executor)：一个以分布式方式执行任意异步代码并具有完全一致性保证的框架。
* [Dexecutor](https://github.com/dexecutor/dexecutor-core)：Dexecutor是一个非常轻量级的框架，可以以可靠的方式执行依赖/独立任务，为此它提供了最少的API。
* [Rqueue](https://github.com/sonus21/rqueue)：Rqueue是一个为Spring框架构建的异步任务执行器，基于Redis支持的Spring框架的消息传递库。
* [JBoss Threads](https://github.com/jbossas/jboss-threads)：JBoss Threads是一个管理和执行Java线程的库。
* [ConcurrentUtil](https://github.com/Tuinity/ConcurrentUtil)：适用于多线程安全编程的高性能实用程序。

#### Future扩展

* [OPEL](https://github.com/allegro/opel)：OPEL旨在让你编写简单、简短的异步表达式，它使用Parboiled作为语言语法引擎和通用的Java 8 CompletableFuture，由Allegro开源。
* [Tascalate Concurrent](https://github.com/vsilaev/tascalate-concurrent)：该库提供了CompletionStage接口和相关类的实现，旨在支持长时间运行的阻塞任务(通常是I/O绑定)。
* [Completable Futures](https://github.com/spotify/completable-futures)：Completable Futures是一组实用函数，用于简化Java 8中异步代码的使用，由Spotify开源。
* [Async Util](https://github.com/IBM/java-async-util)：Async Util是一个用于处理Java 8 CompletionStages的库，由IBM开源。
* [Futurity](https://github.com/Spikhalskiy/futurity)：Futurity是一个简单的工具，用于将普通的旧Java Future转换为CompletableFuture。
* [CompletableFuture Fu](https://github.com/foldright/cffu)：CompletableFuture Fu是一个CompletableFuture辅助增强库，提升CF使用体验并减少误用。
* [Futuristic Feline](https://github.com/spotify/futuristic-feline)：Futuristic Feline是一个用于在运行时检测阻塞Java Future的库，由Spotify开源。
* [Future](https://github.com/traneio/future)：JVM的高性能Future实现。
* [Futures Extra](https://github.com/spotify/futures-extra)：Futures Extra是一组小型实用函数，用于简化Guava的ListenableFuture类的使用，由Spotify开源。
* [Future Converter](https://github.com/lukas-krecan/future-converter)：Future Converter可用于各种Future类型之间执行转换。

#### 协程库

* [Loom](https://github.com/openjdk/loom)：JDK实现的虚拟线程、结构化并发项目，Oracle开源。
* [Quasar](https://github.com/puniverse/quasar)：Quasar是一个为Java和Kotlin提供高性能轻量级线程、Actor以及其他异步编程工具的库。
* [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)：Kotlin多平台的协程支持库。
* [Kilim](https://github.com/kilim/kilim)：Kilim是一个Java消息传递框架，它提供超轻量级线程和在这些线程之间实现快速、安全、零复制消息传递的设施，由剑桥大学博士开源。
* [Coroutines](https://github.com/offbynull/coroutines)：Coroutines是一个Java工具包，允许你用Java编写协程。
* [Coroutines](https://github.com/esoco/coroutines)：该项目包含协程的纯Java实现。
* [Tascalate JavaFlow](https://github.com/vsilaev/tascalate-javaflow)：该项目包含使用Continuation开发Java应用程序的库和工具。

#### Async/Await

* [EA Async](https://github.com/electronicarts/ea-async)：EA Async在JVM上实现Async/Await，允许程序员以顺序方式编写异步代码，由艺电开源。
* [Tascalate Async Await](https://github.com/vsilaev/tascalate-async-await)：Java版本8到17的Async/Await异步编程模型。
* [JAsync](https://github.com/vipcxj/jasync)：JAsync实现了类似es的Async-Await模式，允许开发人员以顺序方式编写异步代码。
* [Java Async-Await](https://github.com/AugustNagro/java-async-await)：Java的Async-Await支持。

#### 线程池

* [Hippo4j](https://github.com/opengoofy/hippo4j)：国产异步线程池框架，支持线程池动态变更、监控、报警。
* [Threadly](https://github.com/threadly/threadly)：协助安全并发Java开发的工具库，提供独特的基于优先级的线程池，以及安全分配线程工作的方法。
* [DynamicTp](https://github.com/dromara/dynamic-tp)：基于配置中心的轻量级动态线程池，内置监控告警功能，集成常用中间件线程池管理，可通过SPI自定义扩展实现，由美团开源。
* [Dirigiste](https://github.com/clj-commons/dirigiste)：Dirigiste提供了java.util.concurrent.ExecutorService的快速、功能丰富的检测版本，并提供了一种将该检测提供给控制机制的方法，该控制机制可以根据需要扩大或缩小池。
* [JADE](https://developer.jdcloud.com/article/4004)：JADE是由京东零售中台-研发架构组维护的线程池项目。
* [ThreadPool4j](https://github.com/aofeng/threadpool4j)：ThreadPool4j是一个实现多线程池的类。
* [Executor Service](https://github.com/vmlens/executor-service)：支持多个写入和单个读取线程的ExecutorService。

#### Actor模型

* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [RACE](https://github.com/NASARace/race)：RACE是一种软件架构和框架，用于构建可配置、高度并发和分布式基于消息的系统，由NASA开源。
* [Fibry](https://github.com/lucav76/Fibry)：Fibry是一个实验性的Actor系统，其构建简单且灵活，也是第一个使用Project Loom中的虚拟线程的Java Actor系统。
* [XOOM Actor](https://github.com/vlingo/xoom-actors)：用于类型安全Actor模型的VLINGO XOOM平台SDK，使用Java和其他JVM语言提供响应式并发、高可扩展性、高吞吐量和弹性。
* [JActor](https://github.com/laforge49/JActor)：Java的Actor库。
* [Pronghorn](https://github.com/oci-pronghorn/Pronghorn)：Pronghorn是一种基于Actor的框架的实用方法，它是一个用Java编写的分阶段事件驱动的单机嵌入式微框架，旨在无垃圾且内存占用小。
* [Kontraktor](https://github.com/RuedigerMoeller/kontraktor)：由分布式Actor模型提供支持的异步远程通信的无样板且一致的抽象。
* [Actr](https://github.com/zakgof/actr)：简单、快速且类型安全的Java Actor模型实现。
* [Ptolemy II](https://github.com/icyphy/ptII)：由一组支持异构并发建模和设计的Java包组成。
* [ReActed](https://github.com/reacted-io/reacted)：Ptolemy II是基于Actor的响应式Java框架，用于本地和分布式环境中的微服务，由加州大学伯克利分校开源。
* [Orbit](https://github.com/orbit/orbit)：用于构建分布式系统的虚拟Actor框架，由艺电开源。
* [Apache Pekko](https://github.com/apache/incubator-pekko)：Pekko是一个开源框架，用于构建并发、分布式、弹性的应用程序。
* [PraxisCore](https://github.com/praxis-live/praxiscore)：PraxisCore是用于网络物理编程的模块化JVM运行时，支持实时系统的实时编码。
* [Elastic Actors](https://github.com/elasticsoftwarefoundation/elasticactors)：ElasticActors是一个Actor框架，它实现Actor模型并提供一些附加服务，例如持久性和可扩展性。

#### ThreadLocal

* [TransmittableThreadLocal](https://github.com/alibaba/transmittable-thread-local)：TransmittableThreadLocal提供一个增强的InheritableThreadLocal，即使使用线程池组件也可以在线程之间传输值，由阿里开源。
* [Context Propagation](https://github.com/talsma-ict/context-propagation)：将ThreadLocal值的快照传播到另一个线程。
* [Context Propagation](https://github.com/micrometer-metrics/context-propagation)：一个帮助跨不同类型的上下文机制(如ThreadLocal、Reactor Context等)传播上下文的库。
* [SmallRye Context Propagation](https://github.com/smallrye/smallrye-context-propagation)：MicroProfile上下文传播的SmallRye实现。

#### 并发数据结构

* [Disruptor](https://github.com/LMAX-Exchange/disruptor)：Disruptor是一个高性能线程间消息传递库，由英国外汇交易公司LMAX开发。
* [ExpiringMap](https://github.com/jhalterman/expiringmap)：一种高性能、低开销、零依赖、线程安全的ConcurrentMap实现，可让键值对过期。
* [JCTools](https://github.com/JCTools/JCTools)：JCTools旨在提供JDK目前缺少的一些并发数据结构。
* [ConcurrentLinkedHashMap](https://github.com/ben-manes/concurrentlinkedhashmap)：java.util.LinkedHashMap的高性能版本，用作软件缓存。
* [ConcurrencyFreaks](https://github.com/pramalhe/ConcurrencyFreaks)：并发数据结构和同步机制的库。
* [Java Concurrent Hash Trie Map](https://github.com/romix/java-concurrent-hash-trie-map)：这是Scala集合库中并发trie HashMap实现的Java端口。
* [Concurrent Trees](https://github.com/npgall/concurrent-trees)：Java的并发Radix和后缀树。
* [Weak Lock Free](https://github.com/raphw/weak-lock-free)：这是一个并发、无锁HashMap的微型实现，具有弱键，其中键尊重引用相等性。
* [Linked Blocking Multi Queue](https://github.com/marianobarrios/linked-blocking-multi-queue)：Linked Blocking Multi Queue是一个并发集合，它扩展了现有的Java并发集合库，提供了基于链接节点的可选有界阻塞“多队列”。

#### 竞争检测

* [RAPID](https://github.com/focs-lab/rapid)：RAPID是一个用于实现动态竞争检测引擎的轻量级框架，由新加坡国立大学开源。
* [RoadRunner](https://github.com/stephenfreund/RoadRunner)：RoadRunner是一种精确而高效的动态竞争检测器，由威廉姆斯学院开源。
* [RV Predict](https://runtimeverification.com/predict)：RV-Predict是一款既可靠又极佳的动态数据竞争检测器。

## 任务调度

* [XXL-JOB](https://github.com/xuxueli/xxl-job)：XXL-JOB是一个分布式任务调度平台，其核心设计目标是开发迅速、学习简单、轻量级、易扩展。
* [Quartz](https://github.com/quartz-scheduler/quartz)：Quartz是一个功能丰富的开源任务调度库，几乎可以集成在任何Java应用程序中，由Terracotta公司开源。
* [Apache ElasticJob](https://github.com/apache/shardingsphere-elasticjob)：ElasticJob是一个轻量级、去中心化的解决方案，提供分布式任务分片服务，由当当网开源。
* [PowerJob](https://github.com/PowerJob/PowerJob)：PowerJob是全新一代分布式任务调度与计算框架。
* [Spring Scheduler](https://docs.spring.io/spring-framework/reference/integration/scheduling.html)：Spring框架通过TaskExecutor和TaskScheduler接口提供了异步执行和任务调度的抽象。
* [JobRunr](https://github.com/jobrunr/jobrunr)：JobRunr提供了一个统一的编程模型，以可靠的方式处理后台任务。
* [SchedulerX](https://www.aliyun.com/aliware/schedulerx)：SchedulerX是阿里自研的分布式任务调度平台，支持Cron定时、一次性任务、工作流任务编排、分布式跑批，具有高可用、可视化、低延时等能力。
* [DisJob](https://github.com/dromara/disjob)：DisJob是一款分布式的任务调度及分布式计算框架，由dromara社区开源。
* [Dynein](https://github.com/airbnb/dynein)：Dynein是Airbnb的开源分布式延迟作业排队系统。
* [Saturn](https://github.com/vipshop/Saturn)：Saturn是唯品会打造的一个提供分布式、容错、高可用的作业调度服务的平台。
* [Dyno Queues](https://github.com/Netflix/dyno-queues)：Dyno Queues在Dynomite之上提供了基于Java的队列配方，由Netflix开源。
* [DB Scheduler](https://github.com/kagkarlsson/db-scheduler)：适用于Java的持久集群友好调度程序。
* [OpenJob](https://github.com/open-job/openjob)：Openjob是一个分布式高性能任务调度框架，支持多个cronjob、延迟任务、工作流，轻量级分布式计算，无限水平扩展，具有高扩展性和容错能力。
* [PlumeJob](https://gitee.com/plumeorg/plumejob)：PlumeJob是一个去中心化的分布式调度系统，集成简单易用，由plume组织开源。
* [TBSchedule](https://github.com/nmyphp/tbschedule)：TBSchedule是一个由阿里开源的支持分布式的调度框架。
* [Sundial](https://github.com/knowm/Sundial)：Sundial是一个轻量级的Java任务调度框架。
* [Kob](https://github.com/LianjiaTech/kob)：Kob是中心化的作业调度系统，定义了任务调度模型，实现了任务调度的统一管理和监控，由链家开源。
* [Wisp](https://github.com/Coreoz/Wisp)：Wisp是一个用于管理重复性Java作业执行的库。
* [Android Job](https://github.com/Evernote/android-job)：用于在后台处理作业的Android库，由Evernote开源。
* [FlowJob](https://github.com/limbo-world/flowjob)：FlowJob主要用于搭建统一的任务调度平台，方便各个业务方进行接入使用。
* [Cron4j](http://www.sauronsoftware.it/projects/cron4j/)：Cron4j是Java平台的调度程序，与UNIX cron守护程序非常相似。
* [Legends](https://github.com/tongbanjie/legends)：Legends是Java开发的一个任务调度框架，可以远程执行一次性或重复性的Job，查看任务的执行状态以及任务结果，由铜板街开源。
* [Job-Dispatcher](https://gitee.com/daye_daye/job-dispatcher)：国产的基于事件的流程编排和调度引擎。
* [Atlassian Schedule](https://bitbucket.org/atlassian/atlassian-schedule)：Atlassian Schedule库是一个用于在Atlassian应用程序中创建计划任务的API。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [Workhorse](https://github.com/coodoo-io/workhorse)：用于后台作业和业务关键任务的Java EE作业引擎。
* [SIA-TASK](https://github.com/siaorg/sia-task)：SIA-TASK是任务调度的一体式解决方案，简单易用，由宜信开源。
* [Jobs](https://gitee.com/baomidou/jobs)：baomidou社区开源的分布式任务调度组件。
* [JobX](https://github.com/datavane/jobx)：JobX是一个功能完善真正通用的Linux定时任务调度系统，由Datavane大数据组织开源。
* [BigBen](https://github.com/walmartlabs/bigben)：BigBen是一个基于Cassandra和Hazelcast的通用、多租户、基于时间的事件调度程序和Cron调度框架，由沃尔玛开源。
* [Light Task Scheduler](https://github.com/ltsopensource/light-task-scheduler)：LTS主要用于解决分布式任务调度问题，支持实时任务、定时任务和Cron任务。
* [CronMan](https://github.com/smmdwa/CronMan)：CronMan是一款轻量级的分布式任务调度系统。
* [Chronus](https://github.com/360digitech/chronus)：Chronus是360数科技术团队基于阿里开源项目TBSchedule重写的分布式调度。
* [ChronosQ](https://github.com/flipkart-incubator/chronosq)：ChronosQ是一个调度程序，当对象在注入时的特定时间过期时，它会在特定对象上运行客户端特定任务，由Flipkart开源。
* [Earth-Frost](https://gitee.com/justlive1/earth-frost)：Earth-Frost是一个轻量级分布式任务调度框架。
* [Schedulix](https://github.com/schedulix/schedulix)：Schedulix是一个开源企业作业调度系统。
* [Hodor](https://github.com/dromara/hodor)：Hodor是一个专注于任务调度以及任务编排的一站式分布式任务调度系统，由dromara社区开源。
* [TASKANA](https://github.com/Taskana/taskana)：TASKANA是一个任务管理组件开源库，它可以嵌入到你的应用程序中，也可以在适当的情况下独立运行。
* [Juice](https://github.com/HujiangTechnology/Juice)：Juice是沪江学习系统项目组所开发的一套基于Mesos Framework的分布式任务调度云系统。
* [JS7 JobScheduler](https://github.com/sos-berlin/js7)：JS7是下一代开源作业调度程序，专为性能、弹性和安全性而设计，适用于本地和云环境中的操作。
* [JQM](https://github.com/enioka-Haute-Couture/jqm)：JQM是一个任务队列管理器。
* [Database Queue](https://github.com/yoomoney/db-queue)：该库在Java和数据库之上提供了工作队列实现，由YooMoney开源。

## 配置管理

* [Pkl](https://github.com/apple/pkl)：Pkl是一种用于生成配置的编程语言，由Apple开源。
* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo研究院开发。
* [Typesafe Config](https://github.com/lightbend/config)：使用HOCON文件的JVM语言的配置库，由Lightbend开源。
* [Microconfig](https://github.com/microconfig/microconfig)：Microconfig的目的是让管理微服务的配置变得简单、方便，并重用公共部分。
* [Spring Cloud Config](https://github.com/spring-cloud/spring-cloud-config)：Spring Cloud Config为分布式系统中的外部化配置提供服务器端和客户端支持。
* [Apollo](https://github.com/apolloconfig/apollo)：Apollo是一个可靠的配置管理系统，适用于微服务配置管理场景，由携程开源。
* [Disconf](https://github.com/knightliao/disconf)：专注于各种分布式系统配置管理的通用组件和通用平台，提供统一的配置管理服务。
* [BRCC](https://github.com/baidu/brcc)：BRCC是一个分布式配置中心，用于统一管理应用服务的配置信息，简化资源配置的维护成本，由百度开源。
* [Central Dogma](https://github.com/line/centraldogma)：Central Dogma是一个基于Git、ZooKeeper和HTTP/2的开源、高可用、版本控制的服务配置仓库，由Line开源。
* [XXL-Conf](https://gitee.com/xuxueli0323/xxl-conf)：XXL-CONF是一个轻量级分布式配置管理平台，拥有轻量级、秒级动态推送、多环境、跨语言、跨机房、配置监听、权限控制、版本回滚等特性。
* [Archaius](https://github.com/Netflix/archaius)：Archaius是一个配置库，用于将静态和动态配置的混合作为单个配置单元进行访问，由Netflix开源。
* [Cerberus](https://github.com/Nike-Inc/cerberus)：Cerberus API是一个云原生、可扩展的Spring Boot应用程序，可以安全地存储应用程序属性和文件，并具有强大的审核功能，Nike开源。
* [Apache Commons Configuration](https://github.com/apache/commons-configuration)：Commons Configuration库提供了一个通用配置接口，使Java应用程序能够从各种源读取配置数据。
* [QConfig](https://github.com/qunarcorp/qconfig)：QConfig中心式配置中心，提供高可用的配置托管/动态热更新服务，由去哪儿开源。
* [Hoplite](https://github.com/sksamuel/hoplite)：Hoplite是一个Kotlin库，用于以非样板方式将配置文件加载到类型安全类中。
* [Diamond](https://github.com/takeseem/diamond)：Diamond是一个持久配置管理中心，核心功能是使应用在运行中感知配置数据的变化，由淘宝开发。
* [NightConfig](https://github.com/TheElectronWill/night-config)：NightConfig是一个功能强大且易于使用的Java配置库，用Java 8编写。
* [Config Toolkit](https://github.com/dangdangdotcom/config-toolkit)：Config Toolkit用于简化从本地配置文件到Zookeeper的迁移，由当当开源。
* [CFG4J](https://github.com/cfg4j/cfg4j)：CFG4J是用Java编写的分布式应用程序的现代配置库。
* [ConfigMe](https://github.com/AuthMe/ConfigMe)：ConfigMe是一个开箱即用的配置管理库，支持YAML。
* [Configurate](https://github.com/SpongePowered/Configurate)：Configurate是一个用于Java应用程序的简单配置库，它提供基于节点的数据表示，能够处理各种配置格式。
* [Avaje Config](https://github.com/avaje/avaje-config)：Avaje Config为JVM应用程序提供外部配置，可以通过YAML或Properties文件提供配置，并使用命令行参数和资源指定要加载的文件。
* [Waterfall Config](https://github.com/Accenture/waterfall-config)：一个简单的Java配置库，很大程度上基于Typesafe Config，并具有一些附加的固执己见的功能，由Accenture开源。
* [ScaleCube Config](https://github.com/scalecube/scalecube-config)：ScaleCube Config是一个基于JVM的分布式应用程序的配置管理库。
* [OWNER](https://github.com/matteobaccan/owner)：OWNER是一个Java库，其目标是最大限度地减少通过Java properties处理应用程序配置所需的代码。
* [Konf](https://github.com/uchuhimo/konf)：Konf是一个适用于Kotlin/Java/Android的类型安全的级联配置库，支持大多数配置格式。
* [Gestalt](https://github.com/gestalt-config/gestalt)：Gestalt是一个功能强大的Java配置库，旨在简化你在软件项目中处理和管理配置的方式。
* [Spring Fu](https://github.com/spring-projects-experimental/spring-fu)：Spring Fu是JaFu和KoFu的孵化器，旨在以声明式方式使用代码显式配置Spring Boot。
* [Config Magic](https://github.com/brianm/config-magic)：Java的便捷配置库。
* [Jeesuite](https://gitee.com/vakinge/jeesuite-config)：功能齐全、适合二开的配置中心，由dromara社区开源。
* [ConfigKeeper](https://gitee.com/sxfad/config-keeper)：ConfigKeeper是由随行付基于Spring Cloud研发的分布式配置中心。
* [JadConfig](https://github.com/Graylog2/JadConfig)：JadConfig是一个最小依赖的Java的简约注解驱动配置解析框架。
* [Sjsonnet](https://github.com/databricks/sjsonnet)：Jsonnet配置语言的JVM实现，由Databricks开源。
* [Fig](https://github.com/theapache64/fig)：使用Google Sheet作为远程配置。
* [Baigan](https://github.com/zalando-incubator/baigan-config)：是一个易于使用的基于Spring应用程序的配置框架，由Zalando开源。

## 功能切换

* [Togglz](https://github.com/togglz/togglz)：Togglz是Java功能切换模式的实现。
* [FeatureProbe](https://github.com/FeatureProbe/FeatureProbe)：FeatureProbe是一项开源功能管理服务，由滴滴开发。
* [FF4j](https://github.com/ff4j/ff4j)：FF4j是功能切换模式的实现。
* [Flips](https://github.com/Feature-Flip/flips)：Flips是Java的功能切换模式的一种实现。
* [Piranha](https://github.com/uber/piranha)：Piranha是一个轻量级代码转换工具集，用于自动化大规模更改，由Uber开源。
* [FeatureHub](https://github.com/featurehub-io/featurehub)：FeatureHub是一个云原生平台，可帮助软件团队管理其功能，从功能标记到A/B实验以及远程或集中配置。
* [Unleash Java](https://github.com/Unleash/unleash-client-java)：适用于Java的Unleash客户端SDK。
* [LaunchDarkly Java](https://github.com/launchdarkly/java-server-sdk)：LaunchDarkly是一个功能管理平台，每天提供数万亿个功能标记，帮助团队更快地构建更好的软件。
* [OpenFeature](https://github.com/open-feature/java-sdk)：OpenFeature是一个开放规范，为功能标记提供与供应商无关、社区驱动的API，可与你最喜欢的功能标记管理工具配合使用。
* [Moirai](https://github.com/Nike-Inc/moirai)：Moirai是JVM的功能标记和资源重新加载库，由Nike开源。
* [Split Java](https://github.com/splitio/java-client)：该SDK旨在与Split(受控部署平台)配合使用，通过功能标志向用户提供功能，以管理完整的客户体验。

## 业务流

* [Camunda](https://github.com/camunda/camunda-bpm-platform)：Camunda Platform是一个灵活的工作流程和流程自动化框架，其核心是在JVM内运行的原生BPMN 2.0流程引擎。
* [Activiti](https://github.com/Activiti/Activiti)：Activiti是一个轻量级工作流程和BPM平台，面向业务人员、开发人员和系统管理员，由Alfresco开源。
* [Flowable](https://github.com/flowable/flowable-engine)：Flowable为开发人员、系统管理员和业务用户提供紧凑且高效的工作流程和BPM平台。
* [Conductor](https://github.com/conductor-oss/conductor)：Conductor是Netflix创建的一个平台，用于编排微服务和事件。
* [jBPM](https://github.com/kiegroup/jbpm)：jBPM是一个用于构建业务应用程序以帮助自动化业务流程和决策的工具包，JBoss社区开源。
* [jDMN](https://github.com/goldmansachs/jdmn)：jDMN为DMN中指定的决策模型提供执行引擎，这些决策可以解释或翻译为Java并在JVM上执行，由高盛银行开源。
* [ActiveMatrix BPM](https://docs.tibco.com/products/tibco-activematrix-bpm-4-3-0)：TIBCO ActiveMatrix BPM用于开发、部署、执行和管理以业务流程管理为中心的应用程序。
* [Apache DolphinScheduler](https://github.com/apache/dolphinscheduler)：DolphinScheduler是现代数据编排平台，以低代码敏捷创建高性能工作流程，由易观开源。
* [Piper](https://github.com/runabol/piper)：Piper是一个基于Spring Boot构建的开源分布式工作流引擎，设计非常简单。
* [Kestra](https://github.com/kestra-io/kestra)：Kestra是一个通用的开源编排器，可以简化计划和事件驱动的工作流程。
* [Maestro](https://github.com/Netflix/maestro)：Maestro是一款通用工作流编排器，为Netflix的数据平台用户提供完全托管的工作流即服务(WAAS)。
* [Maestro](https://github.com/lucidity-labs/maestro)：Maestro是一个简单但功能强大、持久的工作流库。
* [ByteChef](https://github.com/bytechefhq/bytechef)：ByteChef是一个开源、低代码、可扩展的API集成和工作流自动化平台。
* [Compileflow](https://github.com/alibaba/compileflow)：Compileflow是一个非常轻量级、高性能、可集成和可扩展的流程引擎，由阿里开源。
* [SmartEngine](https://github.com/alibaba/SmartEngine)：SmartEngine是一个轻量级的业务编排引擎，在阿里内部广泛使用，可以用于在微服务架构中编排多个服务，也可以用于传统的流程审批场景。
* [Azkaban](https://github.com/azkaban/azkaban)：Azkaban是LinkedIn创建的批处理工作流作业调度程序，用于运行Hadoop作业。
* [Apromore](https://github.com/apromore/ApromoreCore)：Apromore用于流程挖掘和预测流程分析，由墨尔本大学、塔尔图大学等开源。
* [Turbo](https://github.com/didi/turbo)：Turbo是一款轻量级流程引擎服务框架，可作为底层服务支持各类流程设计、低代码设计、工作流、服务编排等场景，由滴滴开源。
* [JEHC-BPM](https://gitee.com/jehc/JEHC-BPM)：JEHC-BPM是小诗科技公司研发的一套开源工作流平台。
* [Bulbasaur](https://github.com/alibaba/bulbasaur)：Bulbasaur是阿里开源的可插拔精简流程引擎，可快速实现流程、审批、业务失败重试等场景。
* [Imixs-Workflow](https://github.com/imixs/imixs-workflow)：Imixs-Workflow是一个开源工作流引擎，用于在灵活而强大的框架上构建以人为中心的工作流应用程序。
* [Bonita](https://github.com/bonitasoft/bonita-engine)：部署、执行、管理使用Bonita Studio或通过Engine API制作的基于流程的应用程序。
* [JFlow](https://gitee.com/opencc/JFlow)：Java版驰骋BPM系统。
* [WINGS](https://github.com/KnowledgeCaptureAndDiscovery/wings)：WINGS是一个语义工作流系统，可帮助科学家设计计算实验，由南加州大学开源。
* [行云流程引擎](https://gitee.com/bestfeng/oa_git_free)：行云流程引擎具备Activiti的常用功能，上手更容易。
* [Emissary](https://github.com/NationalSecurityAgency/emissary)：Emissary是一种基于P2P的数据驱动工作流引擎，运行在异构的、可能广泛分散的多层P2P计算资源网络中，由美国国家安全局开源。
* [Digdag](https://github.com/treasure-data/digdag)：简单、开源、多云工作流程引擎。
* [Cadence](https://github.com/uber/cadence-java-client)：Cadence是分布式、可扩展、持久且高度可用的编排引擎，用于以可扩展和弹性的方式执行异步长时间运行的业务逻辑，由Uber开发。
* [AgileBPM](https://gitee.com/agile-bpm/agile-bpm-basic)：快速、简洁且强大的低代码流程开发平台，国产开源。
* [Schedulis](https://github.com/WeBankFinTech/Schedulis)：Schedulis是一个基于LinkedIn的开源项目Azkaban开发的工作流任务调度系统，由微众开源。
* [UFLO2](https://github.com/youseries/uflo)：UFLO是一款基于Spring的纯Java流程引擎，支持并行、动态并行、串行、会签等各种流转方式。
* [nFlow](https://github.com/NitorCreations/nflow)：nFlow是一种经过验证的用于编排业务流程的解决方案，它可以用作微服务编排器(Saga模式)、业务流程引擎或持久有限状态机。
* [Flowret](https://github.com/americanexpress/unify-flowret)：Flowret是一个基于Java的轻量级编排引擎，由美国运通开源。
* [FlowLong](https://gitee.com/aizuda/flowlong)：由爱组搭开源的工作流引擎。
* [Nextflow](https://github.com/nextflow-io/nextflow)：Nextflow是一个工作流程系统，用于创建可扩展、可移植和可重复的工作流程，由西班牙巴塞罗那的生物医学和基因组学研究中心CRG开发。
* [Concord](https://github.com/walmartlabs/concord)：Concord是一个工作流服务器，它是使用用户创建的场景和插件将不同系统连接在一起的编排引擎，由沃尔玛开源。
* [Radar](https://github.com/wfh45678/radar)：Radar是一款使用Spring Boot、MongoDB、Groovy、ES等框架搭建的轻量级实时风控引擎。
* [CloudSlang](https://github.com/CloudSlang/cloud-slang)：CloudSlang是一种基于YAML的语言，用于为CloudSlang Orchestration Engine编写人类可读的工作流。
* [DataBuilder](https://github.com/flipkart-incubator/databuilderframework)：DataBuilder框架是一个高级逻辑执行引擎，可用于执行多步骤工作流，该引擎目前为Flipkart的结账系统以及诊断和其他工作流提供支持。
* [RuoYi Activiti](https://gitee.com/shenzhanwang/RuoYi-activiti)：基于Activiti 6.0，集流程设计、流程部署、流程执行、任务办理、流程监控于一体的开源工作流开发平台。
* [F2BPM](https://www.f2bpm.com/)：F2BPM是一款纯国产工作流引擎，遵循WFMC/BPMN2.0的规范。
* [盘古BPM](https://gitee.com/pangu-dm/pangubpm-dmn)：盘古BPM工作流平台是国内首款开源的互联网决策引擎系统，拥有独立的DMN1.3标准设计器、解析器、决策引擎、支持决策表、DRD、DRG。
* [JsonFlow](https://gitee.com/jackrolling/jsonflow-ui)：简单但强大易用易扩展且适应复杂场景的中国式审批的工作流引擎系统。
* [Smart Flow](https://gitee.com/smartboot/smart-flow)：SmartFlow是一个轻量、灵活的业务流程编排框架，支持业务流程中常见的条件分支控制、子流程、业务组件异步和降级等功能。
* [COPPER](https://github.com/copper-engine/copper-engine)：COPPER是一个开源、强大、轻量且易于配置的工作流引擎，它使用Java作为工作流的描述语言。
* [FlyFlow](https://gitee.com/junyue/flyflow)：FlyFlow借鉴了钉钉与飞书的界面设计理念，致力于打造一款用户友好、快速上手的工作流程工具。
* [JDEasyFlow](https://github.com/JDEasyFlow/jd-easyflow)：JDEasyFlow是京东开源的一个通用流程编排组件，适用于服务编排、工作流、审计等，具有易用、灵活、易扩展的特点。
* [Easy Flows](https://github.com/j-easy/easy-flows)：Easy Flows是Java的工作流引擎，它提供简单的API和构建块，使创建和运行可组合工作流程变得轻松。
* [FoxBPM](https://github.com/FoxBPM/FoxBPM)：FoxBPM是一款开源的基于BPMN 2.0标准的工作流引擎，引擎底层直接支持BPMN 2.0国际标准。
* [Score](https://github.com/CloudSlang/score)：Score是一个通用编排引擎，它是基于流程的、可嵌入的、轻量级的、可扩展的和多语言的。
* [Yaoqiang BPMN Editor](https://bpmn.sourceforge.net/)：Yaoqiang BPMN Editor是一款开源的业务流程图图形编辑器，符合OMG规范(BPMN 2.0)。
* [Rill Flow](https://github.com/weibocom/rill-flow)：Rill Flow是一种高性能、可扩展的分布式工作流编排服务，由微博开源。
* [WarmFlow](https://gitee.com/dromara/warm-flow)：此项目是极其简单的工作流，没有太多设计，代码量少，并且只有6张表。
* [ProActive Workflows](https://github.com/ow2-proactive/scheduling)：多平台调度和工作流程引擎。
* [Titanoboa](https://github.com/commsor/titanoboa)：Titanoboa是一个面向JVM的低代码工作流编排平台。
* [Automatiko](https://github.com/automatiko-io/automatiko-engine)：Automatiko是一个工具包，它利用成熟且已知的语言来构建自包含服务。
* [Kstry](https://gitee.com/kstry/kstry-core)：Kstry可以将原本存在于代码中错综复杂的方法调用关系以可视化流程图的形式更直观的展示出来。
* [Application Engine](https://github.com/netgrif/application-engine)：Application Engine是一个完全支持低代码语言Petriflow的工作流管理系统。
* [Flux](https://github.com/flipkart-incubator/flux)：Flux是一个异步、可扩展、可选的多租户、分布式且可靠的基于状态机的编排器，由Flipkart开源。
* [Fixflow](https://github.com/fixteam/fixflow)：Fixflow是一款开源的基于BPMN2.0标准的工作流引擎，由北京百特云享公司开发。
* [HelloDATA BE](https://github.com/kanton-bern/hellodata-be)：HelloDATA BE是一个基于现代数据堆栈的开源工具构建的企业数据平台。
* [Operaton](https://github.com/operaton/operaton)：Operaton是一个原生的BPMN 2.0流程引擎，运行在Java虚拟机中。

## 规则引擎

* [Apache Drools](https://github.com/apache/incubator-kie-drools)：Drools是Java的规则引擎、DMN引擎和复杂事件处理(CEP)引擎，由JBoss社区开源。
* [Easy Rules](https://github.com/j-easy/easy-rules)：Easy Rules是一个简单但功能强大的Java规则引擎。
* [Liteflow](https://gitee.com/dromara/liteFlow)：LiteFlow是一个轻量且强大的国产规则引擎框架，可用于复杂的组件化业务的编排领域，由dromara社区开源。
* [RuleBook](https://github.com/deliveredtechnologies/rulebook)：RuleBook提供了一个简单但强大且灵活的规则抽象，其学习曲线非常短。
* [Nected](https://www.nected.ai/)：Nected通过用户友好的界面和声明性规则语言简化了规则表示。
* [RuleEngine](https://github.com/Hale-Lee/RuleEngine)：非常好用的规则引擎，可以直接使用SQL语句定义规则，简化了编码的负荷，也可以使用XML、drl文件配置规则，还支持drools文件导入。
* [Evrete](https://github.com/evrete/evrete)：Evrete是一个前向链接Java规则引擎，它实现RETE算法并完全符合Java规则引擎规范(JSR 94)。
* [OpenL Tablets](https://github.com/openl-tablets/openl-tablets)：OpenL Tablets是一个用于Java的开源业务规则和决策管理系统。
* [ICE](https://github.com/zjn-zjn/ice)：Java规则引擎，针对复杂/灵活变动业务，提供一个新的抽象编排解决方案，轻量级、高性能并提供可视化操作页面。
* [Jess](http://alvarestech.com/temp/fuzzyjess/Jess60/Jess70b7/docs/index.html)：Jess是最早能够轻松与Java集成的规则引擎之一，由桑迪亚国家实验室开源。
* [RuleEngine](https://gitee.com/aizuda/rule-engine-open)：RuleEngine基于Web可视化配置，简单高效快捷，爱组搭开源。
* [JRuleEngine](https://jruleengine.sourceforge.net/)：JRuleEngine是一个Java规则引擎，基于JSR 94，版本1.1。
* [URule](https://github.com/youseries/urule)：URule是一款基于RETE算法的纯Java规则引擎，提供规则集、决策表、决策树、评分卡、规则流等各种规则表现工具及基于网页的可视化设计器。
* [DataFrames](https://github.com/databrickslabs/dataframe-rules-engine)：用于自定义数据框/数据集验证的可扩展规则引擎。
* [JVS-Rules](https://gitee.com/software-minister/jvs-rules)：本项目是基于JVS逻辑引擎构建的规则引擎，将JVS低代码开发平台的逻辑引擎简化，交互优化，从而形成侧重于金融风控、场景规则计算、在线决策的JVS-Rules。
* [YARE](https://github.com/SabreOSS/yare)：YARE是一个用Java编写的规则引擎。

## 商业智能

* [Metabase](https://github.com/metabase/metabase)：Metabase是一个开源的商业智能工具，你可以通过它理解数据、分析数据，进行数据查询并获取格式化结果，以数据驱动决策。
* [Poli](https://github.com/shzlw/poli)：Poli是一款易于使用的SQL报告应用程序，专为SQL爱好者打造。
* [FineBI](https://www.finebi.com/)：FineBI是帆软公司推出的一款商业智能产品。
* [SuperSonic](https://github.com/tencentmusic/supersonic)：SuperSonic是下一代LLM支持的数据分析平台，集成了ChatBI和HeadlessBI，由腾讯音乐娱乐开源。
* [CBoard](https://gitee.com/tuiqiao/CBoard)：CBoard由上海楚果信息技术有限公司主导开源，它不仅仅是一款自助BI数据分析产品，还是开放的BI产品开发平台。
* [DataRoom](https://gitee.com/gcpaas/DataRoom)：DataRoom是一款基于SpringBoot、MyBatis Plus、Vue、ElementUI、G2Plot、Echarts等技术栈的大屏设计器，由科大国创云网科技公司开源。
* [BI Platform](https://github.com/baidu/BIPlatform)：百度开源，业内领先的Holap敏捷BI分析平台，提供高性能、准实时、可扩展的、一站式的BI建模、分析平台。
* [Abixen Platform](https://github.com/abixen/abixen-platform)：Abixen是一个基于微服务的软件平台，用于构建企业应用程序，通过创建特定的微服务并通过提供的CMS集成来提供功能。
* [Helical Insight](https://github.com/helicalinsight/helicalinsight)：Helical Insight是世界上第一个开源商业智能框架，可以帮助你从一个或多个数据源中获取见解。
* [Wren Engine](https://github.com/Canner/wren-engine)：Wren Engine被设计为独立的语义引擎，你可以轻松地使用任何AI代理实现它，可以将其用作语义层的通用语义引擎。
* [Guitar](https://github.com/iflytek/Guitar)：Guitar是一款简单、高效的分布式多维BI报表分析引擎，由科大讯飞开源。
* [LinceBI](https://github.com/LinceBI/lincebi)：LinceBI是一个完整的商业智能解决方案，包括ETL、元数据、大数据和机器学习等模块。
* [Knowage](https://github.com/KnowageLabs/Knowage-Server)：Knowage是开源分析和商业智能套件，可让你将传统数据和大/云数据源组合成有价值且有意义的信息，由OW2开源。
* [Datafor](https://datafor.com.cn/)：Datafor是一款自助式敏捷BI工具，旨在为用户提供直观易用的数据可视化和探索式分析功能，帮助用户快速进行数据探索、分析和决策。
* [JRelax-BI](https://gitee.com/zengchao/JRelax-BI)：BI商业智能，自定义表单+自定义流程+自定义报表。
* [ART](https://art.sourceforge.net/)：ART是一种报告和商业智能解决方案，它可以快速部署SQL查询结果，支持表格报告、图表、仪表板、调度。
* [FusionView](https://gitee.com/hitsoft1995/fusion-view)：富表智能数据可视化平台是一款面向企业和行业级别的用户，具有AI特色的可视化与BI商业智能敏捷分析的平台。
* [ReportServer](https://github.com/infofabrik/reportserver)：ReportServer是一个现代、多功能的开源商业智能(BI)平台，具有强大的报告功能，由ReportServer公司开发。
* [Logi Analytics](https://insightsoftware.com/logi-analytics/)：Logi Analytics提供具有自助分析功能的商业智能和数据发现平台，这是InsightSoftware公司的商业产品。

## SMT求解器

* [Alloy](https://github.com/AlloyTools/org.alloytools.alloy)：Alloy是一个独立的可执行文件，其中包括Kodkod模型查找器和各种SAT求解器，由MIT开源。
* [Sat4j](https://gitlab.ow2.org/sat4j/sat4j)：Sat4j是一个用于解决布尔满足和优化问题的Java库，它可以解决SAT、MAXSAT、伪布尔、最小不可满足子集问题，由阿图瓦大学开源。
* [DuaLip](https://github.com/linkedin/DuaLip)：DuaLip是一种基于Spark的超大规模线性规划(LP)求解器，由LinkedIn开发。
* [EUROPA](https://github.com/nasa/europa)：EUROPA是一个用于建模和解决规划、调度和约束规划问题的框架，NASA艾姆斯研究中心开源。
* [CVC5](https://github.com/cvc5/cvc5)：CVC5是一种用于确定一阶公式对一阶理论(或此类理论的组合)的可满足性的工具，由伯克利大学和三星研究院开发。
* [MiniCP](https://github.com/minicp/minicp)：MiniCP是一个用Java实现的轻量级CP求解器，由康涅狄格大学、鲁汶大学、佐治亚理工学院的三位教授共同开发。
* [JavaSMT](https://github.com/sosy-lab/java-smt)：JavaSMT是用于访问各种SMT求解器的通用API层，由德国慕尼黑大学开源。
* [SMTInterpol](https://github.com/ultimate-pa/smtinterpol)：SMTInterpol是弗莱堡大学开发的插值SMT求解器。
* [Statix Solver](https://mvnrepository.com/artifact/org.metaborg/statix.solver)：由代尔夫特理工大学开源的约束求解器。
* [JSCIPOpt](https://github.com/scipopt/JSCIPOpt)：SCIP是目前混合整数规划(MIP)和混合整数非线性规划(MINLP)最快的非商业求解器之一，由柏林自由大学开源。
* [CLP Java](https://github.com/quantego/clp-java)：CLP线性求解器的Java接口，针对快速模型构建和快速解析进行了优化。
* [KSMT](https://github.com/UnitTestBot/ksmt)：满足各种SMT求解器的统一Kotlin/Java API。

## API管理

* [RAP](https://github.com/thx/RAP)：RAP是一种Web工具，允许开发人员快速定义和记录在典型的基于RESTful API的Web应用程序中使用的Web API，阿里开源。
* [Yaade](https://github.com/EsperoTech/yaade)：Yaade是一个开源、自托管、协作式API开发环境。
* [AgileTC](https://github.com/didi/AgileTC)：AgileTC是一个基于思维导图的具有多实时协作能力的测试用例管理平台，由滴滴开源。
* [CrapApi](https://gitee.com/CrapApi/CrapApi)：CrapApi是完全开源、免费使用的API接口管理系统、BUG管理系统。
* [XXL-API](https://github.com/xuxueli/xxl-api)：XXL-API是一个强大易用的API管理平台，提供API的管理、文档、Mock和测试等功能。
* [WSO2 API Manager](https://github.com/wso2/product-apim)：WSO2 API Manager是一个用于创建、管理、使用和监控Web API的强大平台。
* [Apiman](https://github.com/apiman/apiman)：Apiman是一个灵活的开源API管理平台，由RedHat开源。
* [Repose](https://github.com/rackerlabs/repose)：Repose为API处理任务提供解决方案，例如身份验证、速率限制、API验证、HTTP请求日志记录等等。
* [EasyOpen](https://gitee.com/durcframework/easyopen)：EasyOpen是一个简单易用的接口开放平台，平台封装了常用的参数校验、结果返回等功能。
* [Torna](https://gitee.com/durcframework/torna)：Torna是一个接口文档解决方案，目标是让接口文档管理变得更加方便、快捷。
* [Gravitee](https://github.com/gravitee-io/gravitee-api-management)：Gravitee是一种灵活、轻量级且速度极快的开源解决方案，可帮助你的组织控制用户访问API的人员、时间和方式。
* [Apicurio Studio](https://github.com/Apicurio/apicurio-studio)：Apicurio Studio项目是一个独立的API设计工具，可用于创建新的或编辑现有的API设计(使用OpenAPI或AsyncAPI规范)，由RedHat开源。
* [Apicurio Registry](https://github.com/Apicurio/apicurio-registry)：Apicurio Registry使你能够使用远程REST API在存储中添加、更新和删除工件，由RedHat开源。
* [APK](https://github.com/wso2/apk)：APK即Kubernetes API平台，这是一种尖端的API管理解决方案，旨在利用Kubernetes的强大功能来实现无缝且可扩展的部署，WSO2开源。
* [Otoroshi](https://github.com/MAIF/otoroshi)：Otoroshi是一个轻量级API管理层，由MAIF OSS团队开发，可以处理微服务之间的所有调用，无需服务定位器，并允许你在运行时动态更改配置。
* [RESTFiddle](https://github.com/AnujaK/restfiddle)：适用于团队的企业级API管理平台，RESTFiddle帮助你设计、开发、测试和发布API。

## [本体库-音视频处理](docs/doc2.md)

## [数据结构-面试宝典](docs/doc3.md)