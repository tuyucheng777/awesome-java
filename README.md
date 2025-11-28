# Java生态资源大全

这里汇总了Java生态圈中的各种框架、库、中间件，包括Web开发、大数据、桌面开发、机器学习、软件测试、物联网、Android等领域。

所有框架和库都是基于Java语言实现的，只有极少数是由Kotlin、Scala、Groovy等JVM系语言混合开发，并且也可以在Java中兼容使用。

## 目录

* [开发框架](#开发框架)
    * [Web框架](#Web框架)
    * [RPC框架](#RPC框架)
    * [JSF框架](#JSF框架)
    * [REST框架](#REST框架)
    * [WebService框架](#WebService框架)
    * [微服务框架](#微服务框架)
    * [Spring Cloud框架](#Spring-Cloud框架)
* [微服务库](#微服务库)
* [微服务治理](#微服务治理)
* [REST错误处理](#REST错误处理)
* [构建工具](#构建工具)
* [包管理器](#包管理器)
* [CI/CD](#CICD)
* [JDK](#JDK)
* [JVM实现](#JVM实现)
* [JVM语言](#JVM语言)
* [云原生](#云原生)
* [Serverless](#Serverless)
* [APM](#APM)
* [分布式跟踪](#分布式跟踪)
* [指标库](#指标库)
* [API网关](#API网关)
* [服务发现](#服务发现)
* [容错组件](#容错组件)
    * [限流/降级](#限流降级)
    * [重试](#重试)
    * [负载均衡](#负载均衡)
    * [健康检查](#健康检查)
    * [混沌引擎](#混沌引擎)
    * [优雅停机](#优雅停机)
* [大数据](#大数据)
    * [大数据框架](#大数据框架)
    * [大数据工具](#大数据工具)
    * [大数据组件](#大数据组件)
    * [数据目录](#数据目录)
    * [数据治理](#数据治理)
    * [查询引擎](#查询引擎)
    * [存储格式](#存储格式)
    * [存储系统](#存储系统)
    * [流处理平台](#流处理平台)
    * [ETL工具](#ETL工具)
    * [CDC组件](#CDC组件)
    * [连接器](#连接器)
    * [集群管理](#集群管理)
    * [调度系统](#调度系统)
    * [执行引擎](#执行引擎)
    * [OLAP引擎](#OLAP引擎)
    * [CEP引擎](#CEP引擎)
    * [监控工具](#监控工具)
    * [Notebook](#Notebook)
    * [数据湖框架](#数据湖框架)
    * [数据Shuffle](#数据Shuffle)
    * [时序数据分析](#时序数据分析)
* [进程间通信](#进程间通信)
    * [消息中间件](#消息中间件)
    * [事件总线](#事件总线)
    * [消息总线](#消息总线)
    * [应用总线](#应用总线)
    * [消息队列客户端](#消息队列客户端)
    * [Kafka](#Kafka)
* [分布式开发](#分布式开发)
    * [分布式锁](#分布式锁)
    * [分布式ID](#分布式ID)
    * [Session集群](#Session集群)
    * [Raft算法](#Raft算法)
    * [Paxos算法](#Paxos算法)
    * [Gossip算法](#Gossip算法)
* [数据库](#数据库)
    * [搜索引擎](#搜索引擎)
    * [图数据库](#图数据库)
    * [RDF数据库](#RDF数据库)
    * [键值存储](#键值存储)
    * [数据网格](#数据网格)
    * [时序数据库](#时序数据库)
    * [嵌入式数据库](#嵌入式数据库)
    * [关系型数据库](#关系型数据库)
    * [NoSQL数据库](#NoSQL数据库)
    * [OLAP数据库](#OLAP数据库)
    * [向量数据库](#向量数据库)
    * [对象数据库](#对象数据库)
    * [XML数据库](#XML数据库)
    * [Datalog数据库](#Datalog数据库)
    * [OLTP数据库](#OLTP数据库)
    * [其他数据库](#其他数据库)
* [数据库中间件](#数据库中间件)
    * [数据同步](#数据同步)
    * [分库分表](#分库分表)
    * [Binlog](#Binlog)
    * [灾难备份](#灾难备份)
* [网络编程](#网络编程)
    * [HTTP客户端](#HTTP客户端)
    * [HTTP路由](#HTTP路由)
    * [Web服务器](#Web服务器)
    * [应用服务器](#应用服务器)
    * [WebSocket](#WebSocket)
    * [FTP服务器](#FTP服务器)
    * [NIO框架](#NIO框架)
    * [网络库](#网络库)
    * [Socket](#Socket)
    * [TCP/UDP库](#TCPUDP库)
    * [Pcap](#Pcap)
    * [SSH库](#SSH库)
    * [DNS库](#DNS库)
    * [HTTP代理](#HTTP代理)
    * [内网穿透](#内网穿透)
    * [IO_Uring](#IO_Uring)
    * [网络监控](#网络监控)
    * [网络工具](#网络工具)
    * [端口转发](#端口转发)
    * [P2P](#P2P)
    * [SDN](#SDN)
    * [SMB](#SMB)
    * [KCP](#KCP)
    * [QUIC](#QUIC)
    * [SNMP](#SNMP)
    * [SOCKS](#SOCKS)
    * [Radius](#Radius)
    * [以太网](#以太网)
    * [IP库](#IP库)
* [工具库](#工具库)
* [Bean映射&复制](#Bean映射复制)
* [IoC](#IoC)
* [AOP](#AOP)
* [日志库](#日志库)
    * [日志采集](#日志采集)
    * [请求/响应记录](#请求响应记录)
    * [日志追踪](#日志追踪)
    * [日志分析](#日志分析)
    * [Logback Appender](#Logback-Appender)
    * [结构化日志](#结构化日志)
* [缓存库](#缓存库)
    * [本地缓存](#本地缓存)
    * [分布式缓存](#分布式缓存)
    * [缓存管理器](#缓存管理器)
* [批处理框架](#批处理框架)
* [并发编程](#并发编程)
    * [响应式](#响应式)
    * [Future扩展](#Future扩展)
    * [协程库](#协程库)
    * [Async/Await](#AsyncAwait)
    * [并行编排](#并行编排)
    * [线程库](#线程库)
    * [Channel](#Channel)
    * [线程池](#线程池)
    * [Actor库](#Actor库)
    * [ThreadLocal](#ThreadLocal)
    * [并发数据结构](#并发数据结构)
    * [竞争检测](#竞争检测)
* [功能切换](#功能切换)
* [人工智能](#人工智能)
    * [LLM框架](#LLM框架)
    * [LLM客户端](#LLM客户端)
    * [推理引擎](#推理引擎)
    * [MCP](#MCP)
    * [代理框架](#代理框架)
    * [AI智能体](#AI智能体)
    * [LLMOps](#LLMOps)
    * [AI Assistant](#AI-Assistant)
    * [机器学习](#机器学习)
    * [自然语言处理](#自然语言处理)
    * [分词器](#分词器)
    * [深度学习](#深度学习)
    * [模型训练](#模型训练)
    * [强化学习](#强化学习)
    * [贝叶斯推理](#贝叶斯推理)
    * [因果推理](#因果推理)
    * [语义解析](#语义解析)
    * [实体链接](#实体链接)
    * [信息提取](#信息提取)
    * [联邦学习](#联邦学习)
    * [推荐系统](#推荐系统)
    * [遗传算法](#遗传算法)
    * [专家系统](#专家系统)
    * [认知架构](#认知架构)
    * [约束编程](#约束编程)
    * [异常检测](#异常检测)
    * [逻辑编程](#逻辑编程)
    * [元启发式框架](#元启发式框架)
    * [计算机视觉](#计算机视觉)
    * [OCR](#OCR)
    * [人脸识别](#人脸识别)
    * [语音识别](#语音识别)
    * [语音合成](#语音合成)
* [数据科学](#数据科学)
    * [数据可视化](#数据可视化)
    * [数据挖掘](#数据挖掘)
    * [数据分析](#数据分析)
    * [实体解析](#实体解析)
    * [Dataframe](#Dataframe)
* [测试](docs/doc2.md#测试)
    * [单元测试](docs/doc2.md#单元测试)
    * [集成测试](docs/doc2.md#集成测试)
    * [接口测试](docs/doc2.md#接口测试)
    * [端到端测试](docs/doc2.md#端到端测试)
    * [功能测试](docs/doc2.md#功能测试)
    * [突变测试](docs/doc2.md#突变测试)
    * [模糊测试](docs/doc2.md#模糊测试)
    * [性能测试](docs/doc2.md#性能测试)
    * [基准测试](docs/doc2.md#基准测试)
    * [属性测试](docs/doc2.md#属性测试)
    * [验收测试](docs/doc2.md#验收测试)
    * [回归测试](docs/doc2.md#回归测试)
    * [A/B测试](docs/doc2.md#AB测试)
    * [流量回放](docs/doc2.md#流量回放)
    * [契约测试](docs/doc2.md#契约测试)
    * [渗透测试](docs/doc2.md#渗透测试)
    * [快照测试](docs/doc2.md#快照测试)
    * [断言库](docs/doc2.md#断言库)
    * [Mock框架](docs/doc2.md#Mock框架)
    * [接口Mock](docs/doc2.md#接口Mock)
    * [Mock库](docs/doc2.md#Mock库)
    * [数据Mock](docs/doc2.md#数据Mock)
    * [BDD框架](docs/doc2.md#BDD框架)
    * [测试生成器](docs/doc2.md#测试生成器)
    * [参数化测试](docs/doc2.md#参数化测试)
    * [Selenium库](docs/doc2.md#Selenium库)
    * [Cucumber库](docs/doc2.md#Cucumber库)
    * [自动化框架](docs/doc2.md#自动化框架)
    * [自动化工具](docs/doc2.md#自动化工具)
    * [QA自动化](docs/doc2.md#QA自动化)
    * [测试报告](docs/doc2.md#测试报告)
    * [多线程测试](docs/doc2.md#多线程测试)
    * [POJO测试](docs/doc2.md#POJO测试)
    * [日志测试](docs/doc2.md#日志测试)
    * [JUnit扩展](docs/doc2.md#JUnit扩展)
    * [测试运行器](docs/doc2.md#测试运行器)
    * [大数据测试](docs/doc2.md#大数据测试)
    * [其他测试库](docs/doc2.md#其他测试库)
    * [Spring测试](docs/doc2.md#Spring测试)
    * [测试套件](docs/doc2.md#测试套件)
    * [测试模板](docs/doc2.md#测试模板)
    * [测试异味](docs/doc2.md#测试异味)
    * [代码覆盖率](docs/doc2#代码覆盖率)
* [数据库开发](docs/doc2.md#数据库开发)
    * [数据库驱动](docs/doc2.md#数据库驱动)
    * [ORM框架](docs/doc2.md#ORM框架)
    * [JDBC框架](docs/doc2.md#JDBC框架)
    * [DAO框架](docs/doc2.md#DAO框架)
    * [持久层库](docs/doc2.md#持久层库)
    * [NoSQL库](docs/doc2.md#NoSQL库)
    * [事务](docs/doc2.md#事务)
    * [Mybatis库](docs/doc2.md#Mybatis库)
    * [Hibernate库](docs/doc2.md#Hibernate库)
    * [JPA库](docs/doc2.md#JPA库)
    * [数据库连接池](docs/doc2.md#数据库连接池)
    * [数据库迁移](docs/doc2.md#数据库迁移)
    * [数据源增强](docs/doc2.md#数据源增强)
    * [数据库工具](docs/doc2.md#数据库工具)
    * [存储过程](docs/doc2.md#存储过程)
    * [N+1检测](docs/doc2.md#N1检测)
    * [Redis库/工具](docs/doc2.md#Redis库工具)
    * [MongoDB库/工具](docs/doc2.md#MongoDB库工具)
    * [Cassandra库/工具](docs/doc2.md#Cassandra库工具)
    * [Memcached库/工具](docs/doc2.md#Memcached库工具)
    * [Zookeeper库/工具](docs/doc2.md#Zookeeper库工具)
    * [ClickHouse库/工具](docs/doc2.md#ClickHouse库工具)
    * [ElasticSearch库/工具](docs/doc2.md#ElasticSearch库工具)
    * [DynamoDB库/工具](docs/doc2.md#DynamoDB库工具)
    * [Neo4j库/工具](docs/doc2.md#Neo4j库工具)
    * [Etcd库/工具](docs/doc2.md#Etcd库工具)
    * [Milvus库/工具](docs/doc2.md#Milvus库工具)
    * [Vault库/工具](docs/doc2.md#Vault库工具)
* [安全](docs/doc2.md#安全)
    * [安全框架](docs/doc2.md#安全框架)
    * [JWT库](docs/doc2.md#JWT库)
    * [授权服务器](docs/doc2.md#授权服务器)
    * [OAuth库](docs/doc2.md#OAuth库)
    * [身份管理平台](docs/doc2.md#身份管理平台)
    * [单点登录](docs/doc2.md#单点登录)
    * [安全库](docs/doc2.md#安全库)
    * [LDAP](docs/doc2.md#LDAP)
    * [安全工具](docs/doc2.md#安全工具)
    * [漏洞工具](docs/doc2.md#漏洞工具)
    * [安全培训](docs/doc2.md#安全培训)
    * [自保护](docs/doc2.md#自保护)
    * [跨域身份管理](docs/doc2.md#跨域身份管理)
    * [加密库](docs/doc2.md#加密库)
    * [密码库](docs/doc2.md#密码库)
    * [加密算法](docs/doc2.md#加密算法)
    * [接口加密](docs/doc2.md#接口加密)
    * [数据脱敏](docs/doc2.md#数据脱敏)
    * [零知识证明](docs/doc2.md#零知识证明)
    * [XSS](docs/doc2.md#XSS)
    * [TLS/SSL](docs/doc2.md#TLSSSL)
    * [CORS](docs/doc2.md#CORS)
    * [ASN.1](docs/doc2.md#ASN1)
    * [证书颁发机构](docs/doc2.md#证书颁发机构)
    * [数据匿名化](docs/doc2.md#数据匿名化)
    * [电子签名](docs/doc2.md#电子签名)
* [序列化](docs/doc2.md#序列化)
    * [Protocol Buffer](docs/doc2.md#Protocol-Buffer)
    * [CBOR](docs/doc2.md#CBOR)
    * [TOON](docs/doc2.md#TOON)
* [JSON库](docs/doc2.md#JSON库)
    * [JSON Schema](docs/doc2.md#JSON-Schema)
    * [JsonPath](docs/doc2.md#JsonPath)
    * [JSON Patch](docs/doc2.md#JSON-Patch)
    * [JSON-LD](docs/doc2.md#JSON-LD)
    * [JSON-RPC](docs/doc2.md#JSON-RPC)
    * [JSON比较](docs/doc2.md#JSON比较)
* [配置管理](docs/doc2.md#配置管理)
    * [配置库](docs/doc2.md#配置库)
    * [分布式配置](docs/doc2.md#分布式配置)
    * [配置语言](docs/doc2.md#配置语言)
    * [YML库](docs/doc2.md#YML库)
    * [INI库](docs/doc2.md#INI库)
    * [ENV库](docs/doc2.md#ENV库)
    * [Toml库](docs/doc2.md#Toml库)
* [GraphQL](docs/doc2.md#GraphQL)
    * [GraphQL Spring](docs/doc2.md#GraphQL-Spring)
    * [模式优先](docs/doc2.md#模式优先)
    * [代码优先](docs/doc2.md#代码优先)
    * [GraphQL库](docs/doc2.md#GraphQL库)
    * [执行策略](docs/doc2.md#执行策略)
    * [GraphQL标量](docs/doc2.md#GraphQL标量)
* [日期时间](docs/doc2.md#日期时间)
    * [日历库](docs/doc2.md#日历库)
    * [日期/时间解析器](docs/doc2.md#日期时间解析器)
* [MATLAB](docs/doc2.md#MATLAB)
* [Jupyter](docs/doc2.md#Jupyter)
* [机器人开发](docs/doc2.md#机器人开发)
* [数学库](docs/doc2.md#数学库)
    * [线性代数](docs/doc2.md#线性代数)
    * [矩阵](docs/doc2.md#矩阵)
    * [多维数组](docs/doc2.md#多维数组)
    * [数值计算](docs/doc2.md#数值计算)
    * [多精度](docs/doc2.md#多精度)
    * [微分](docs/doc2.md#微分)
    * [Math扩展](docs/doc2.md#Math扩展)
    * [向量](docs/doc2.md#向量)
    * [统计](docs/doc2.md#统计)
    * [直方图](docs/doc2.md#直方图)
    * [运筹学](docs/doc2.md#运筹学)
* [图处理](docs/doc2.md#图处理)
* [本体库](docs/doc2.md#本体库)
    * [本体编辑器](docs/doc2.md#本体编辑器)
    * [本体推理机](docs/doc2.md#本体推理机)
    * [本体匹配](docs/doc2.md#本体匹配)
    * [本体转换](docs/doc2.md#本体转换)
    * [RDF库](docs/doc2.md#RDF库)
    * [语义Web](docs/doc2.md#语义Web)
    * [知识图谱](docs/doc2.md#知识图谱)
* [生物信息学](docs/doc2.md#生物信息学)
    * [生物工具](docs/doc2.md#生物工具)
    * [生物工作流](docs/doc2.md#生物工作流)
    * [基因组](docs/doc2.md#基因组)
    * [NGS](docs/doc2.md#NGS)
* [化学库](docs/doc2.md#化学库)
* [心理测量学](docs/doc2.md#心理测量学)
* [网络爬虫](docs/doc2.md#网络爬虫)
    * [爬虫库](docs/doc2.md#爬虫库)
    * [HTML提取](docs/doc2.md#HTML提取)
    * [爬虫平台](docs/doc2.md#爬虫平台)
    * [Youtube爬取](docs/doc2.md#Youtube爬取)
* [工作流](docs/doc2.md#工作流)
* [编排引擎](docs/doc2.md#编排引擎)
* [规则引擎](docs/doc2.md#规则引擎)
* [状态机](docs/doc2.md#状态机)
* [报表引擎](docs/doc2.md#报表引擎)
* [商业智能](docs/doc2.md#商业智能)
* [模板引擎](docs/doc2.md#模板引擎)
* [任务调度](docs/doc2.md#任务调度)
* [企业集成模式](docs/doc2.md#企业集成模式)
* [SMT求解器](docs/doc2.md#SMT求解器)
* [命令行开发](docs/doc2.md#命令行开发)
    * [CLI库](docs/doc2.md#CLI库)
    * [命令行参数解析](docs/doc2.md#命令行参数解析)
    * [ASCII艺术](docs/doc2.md#ASCII艺术)
    * [文本表](docs/doc2.md#文本表)
    * [进度条](docs/doc2.md#进度条)
* [控制台](docs/doc2.md#控制台)
* [版本控制系统](docs/doc2.md#版本控制系统)
    * [Git服务器](docs/doc2.md#Git服务器)
    * [Git工具](docs/doc2.md#Git工具)
    * [Git API](docs/doc2.md#Git-API)
    * [语义版本控制](docs/doc2.md#语义版本控制)
* [集合库](docs/doc2.md#集合库)
* [数组库](docs/doc2.md#数组库)
* [泛型库](docs/doc2.md#泛型库)
* [函数式编程](docs/doc2.md#函数式编程)
    * [函数式异常处理](docs/doc2.md#函数式异常处理)
    * [Stream工具库](docs/doc2.md#Stream工具库)
    * [Lambda扩展](docs/doc2.md#Lambda扩展)
    * [LINQ](docs/doc2.md#LINQ)
    * [模式匹配](docs/doc2.md#模式匹配)
    * [尾调用](docs/doc2.md#尾调用)
    * [定理证明](docs/doc2.md#定理证明)
* [字节码操作](docs/doc2.md#字节码操作)
* [字节码工具库](docs/doc2.md#字节码工具库)
* [反编译](docs/doc2.md#反编译)
* [代码混淆](docs/doc2.md#代码混淆)
* [逆向工程](docs/doc2.md#逆向工程)
* [反向移植](docs/doc2.md#反向移植)
* [图像处理](docs/doc2.md#图像处理)
    * [图像元数据](docs/doc2.md#图像元数据)
    * [图像比较](docs/doc2.md#图像比较)
    * [PNG库](docs/doc2.md#PNG库)
    * [SVG库](docs/doc2.md#SVG库)
    * [TIFF库](docs/doc2.md#TIFF库)
    * [验证码](docs/doc2.md#验证码)
    * [二维码库](docs/doc2.md#二维码库)
    * [条形码库](docs/doc2.md#条形码库)
    * [水印](docs/doc2.md#水印)
* [压缩库](docs/doc2.md#压缩库)
    * [数据压缩](docs/doc2.md#数据压缩)
    * [文件压缩](docs/doc2.md#文件压缩)
    * [图像压缩](docs/doc2.md#图像压缩)
* [反射库](docs/doc2.md#反射库)
* [注解库](docs/doc2.md#注解库)
* [接口文档](docs/doc2.md#接口文档)
    * [规范优先](docs/doc2.md#规范优先)
    * [接口优先](docs/doc2.md#接口优先)
    * [模式解析](docs/doc2.md#模式解析)
    * [模式比较](docs/doc2.md#模式比较)
    * [模式校验](docs/doc2.md#模式校验)
    * [规范转换](docs/doc2.md#规范转换)
* [API管理](docs/doc2.md#API管理)
* [技术文档](docs/doc2.md#技术文档)
* [Javadoc](docs/doc2.md#Javadoc)
* [文件操作](docs/doc2.md#文件操作)
    * [PDF库](docs/doc2.md#PDF库)
    * [Excel库](docs/doc2.md#Excel库)
    * [CSV库](docs/doc2.md#CSV库)
    * [Word库](docs/doc2.md#Word库)
    * [PPT库](docs/doc2.md#PPT库)
    * [ODS库](docs/doc2.md#ODS库)
    * [DBF库](docs/doc2.md#DBF库)
    * [Office库](docs/doc2.md#Office库)
    * [XML库](docs/doc2.md#XML库)
    * [HTML库](docs/doc2.md#HTML库)
    * [RTF库](docs/doc2.md#RTF库)
    * [EPUB库](docs/doc2.md#EPUB库)
    * [Outlook库](docs/doc2.md#Outlook库)
    * [License库](docs/doc2.md#License库)
    * [Markdown库](docs/doc2.md#Markdown库)
    * [EditorConfig库](docs/doc2.md#EditorConfig库)
    * [EDI库](docs/doc2.md#EDI库)
    * [OBJ库](docs/doc2.md#OBJ库)
    * [OFD库](docs/doc2.md#OFD库)
    * [文件库](docs/doc2.md#文件库)
    * [文件转换](docs/doc2.md#文件转换)
    * [Mime解析](docs/doc2.md#Mime解析)
    * [文件上传](docs/doc2.md#文件上传)
    * [文件比较](docs/doc2.md#文件比较)
    * [文件预览](docs/doc2.md#文件预览)
* [容器化工具](docs/doc2.md#容器化工具)
* [DevOps](docs/doc2.md#DevOps)
* [性能分析&调优](docs/doc2.md#性能分析调优)
    * [诊断工具](docs/doc2.md#诊断工具)
    * [Spring Boot仪表板](docs/doc2.md#Spring-Boot仪表板)
    * [GC日志分析](docs/doc2.md#GC日志分析)
    * [堆转储](docs/doc2.md#堆转储)
    * [线程转储](docs/doc2.md#线程转储)
    * [火焰图](docs/doc2.md#火焰图)
    * [对象测量](docs/doc2.md#对象测量)
* [软件质量](docs/doc2.md#软件质量)
    * [静态分析](docs/doc2.md#静态分析)
    * [编码规范](docs/doc2.md#编码规范)
    * [依赖分析](docs/doc2.md#依赖分析)
    * [迁移&重构](docs/doc2.md#迁移重构)
    * [污点分析](docs/doc2.md#污点分析)
    * [抄袭检测](docs/doc2.md#抄袭检测)
    * [代码属性图](docs/doc2.md#代码属性图)
* [软件工程](docs/doc2.md#软件工程)
    * [软件建模](docs/doc2.md#软件建模)
    * [铁路图生成器](docs/doc2.md#铁路图生成器)
    * [DDD框架](docs/doc2.md#DDD框架)
    * [CQRS框架](docs/doc2.md#CQRS框架)
* [设计模式](docs/doc2.md#设计模式)
    * [构建器模式](docs/doc2.md#构建器模式)
    * [代理模式](docs/doc2.md#代理模式)
    * [责任链模式](docs/doc2.md#责任链模式)
    * [中介器](docs/doc2.md#中介器)
* [审计框架](docs/doc2.md#审计框架)
* [原型工具](docs/doc2.md#原型工具)
* [工件仓库](docs/doc2.md#工件仓库)
* [打包](docs/doc2.md#打包)
* [部署](docs/doc2.md#部署)
* [运行](docs/doc2.md#运行)
* [REPL](docs/doc2.md#REPL)
* [Java Web Start](docs/doc2.md#Java-Web-Start)
* [RPM](docs/doc2.md#RPM)
* [Java环境管理](docs/doc2.md#Java环境管理)
* [API变更管理](docs/doc2.md#API变更管理)
* [源代码转换](docs/doc2.md#源代码转换)
* [源代码浏览器](docs/doc2.md#源代码浏览器)
* [企业软件开发](docs/doc2.md#企业软件开发)
    * [项目模板](docs/doc2.md#项目模板)
    * [脚手架](docs/doc2.md#脚手架)
    * [快速开发框架](docs/doc2.md#快速开发框架)
    * [后台管理系统](docs/doc2.md#后台管理系统)
    * [低代码](docs/doc2.md#低代码)
    * [权限管理系统](docs/doc2.md#权限管理系统)
    * [商城系统](docs/doc2.md#商城系统)
    * [秒杀系统](docs/doc2.md#秒杀系统)
    * [医疗系统](docs/doc2.md#医疗系统)
    * [项目管理](docs/doc2.md#项目管理)
    * [即时通讯](docs/doc2.md#即时通讯)
    * [问题跟踪系统](docs/doc2.md#问题跟踪系统)
    * [QA系统](docs/doc2.md#QA系统)
    * [CMS系统](docs/doc2.md#CMS系统)
    * [博客系统](docs/doc2.md#博客系统)
    * [论坛系统](docs/doc2.md#论坛系统)
    * [ERP系统](docs/doc2.md#ERP系统)
    * [CRM系统](docs/doc2.md#CRM系统)
    * [HRM系统](docs/doc2.md#HRM系统)
    * [AI系统](docs/doc2.md#AI系统)
    * [OA系统](docs/doc2.md#OA系统)
    * [DMS系统](docs/doc2.md#DMS系统)
    * [WMS系统](docs/doc2.md#WMS系统)
    * [MES系统](docs/doc2.md#MES系统)
    * [PMS系统](docs/doc2.md#PMS系统)
    * [PLM系统](docs/doc2.md#PLM系统)
    * [EMS系统](docs/doc2.md#EMS系统)
    * [云盘系统](docs/doc2.md#云盘系统)
    * [充电桩系统](docs/doc2.md#充电桩系统)
    * [数据中台](docs/doc2.md#数据中台)
    * [知识管理系统](docs/doc2.md#知识管理系统)
    * [SCRM系统](docs/doc2.md#SCRM系统)
    * [门户框架](docs/doc2.md#门户框架)
    * [教育软件](docs/doc2.md#教育软件)
    * [评测系统](docs/doc2.md#评测系统)
    * [理财系统](docs/doc2.md#理财系统)
    * [Data API](docs/doc2.md#Data-API)
    * [插件框架](docs/doc2.md#插件框架)
    * [POS](docs/doc2.md#POS)
    * [业务](docs/doc2.md#业务)
    * [电商](docs/doc2.md#电商)
* [支付](docs/doc2.md#支付)
    * [微信支付](docs/doc2.md#微信支付)
    * [支付宝](docs/doc2.md#支付宝)
    * [支付平台](docs/doc2.md#支付平台)
    * [支付网关](docs/doc2.md#支付网关)
    * [银行卡/信用卡](docs/doc2.md#银行卡信用卡)
* [云计算](docs/doc2.md#云计算)
    * [SaaS平台](docs/doc2.md#SaaS平台)
    * [BaaS平台](docs/doc2.md#BaaS平台)
    * [PaaS平台](docs/doc2.md#PaaS平台)
    * [IaaS平台](docs/doc2.md#IaaS平台)
    * [仿真框架](docs/doc2.md#仿真框架)
    * [边缘计算](docs/doc2.md#边缘计算)
* [云服务SDK](docs/doc2.md#云服务SDK)
* [微信开发](docs/doc2.md#微信开发)
* [推送SDK](docs/doc2.md#推送SDK)
* [异常通知](docs/doc2.md#异常通知)
* [APN](docs/doc2.md#APN)
* [Webhook](docs/doc2.md#Webhook)
* [API&客户端](docs/doc2.md#API客户端)
    * [Twitter](docs/doc2.md#Twitter)
    * [Facebook](docs/doc2.md#Facebook)
    * [Instagram](docs/doc2.md#Instagram)
    * [Telegram](docs/doc2.md#Telegram)
    * [Whatsapp](docs/doc2.md#Whatsapp)
    * [Slack](docs/doc2.md#Slack)
    * [Reddit](docs/doc2.md#Reddit)
    * [TikTok](docs/doc2.md#TikTok)
    * [Spotify](docs/doc2.md#Spotify)
    * [Notion](docs/doc2.md#Notion)
    * [JIRA](docs/doc2.md#JIRA)
    * [Jenkins](docs/doc2.md#Jenkins)
    * [Riot](docs/doc2.md#Riot)
    * [TheMovieDb](docs/doc2.md#TheMovieDb)
    * [TeamSpeak](docs/doc2.md#TeamSpeak)
    * [Mastodon](docs/doc2.md#Mastodon)
* [Docker客户端](docs/doc2.md#Docker客户端)
* [Consul客户端](docs/doc2.md#Consul客户端)
* [Kubernetes客户端](docs/doc2.md#Kubernetes客户端)
* [Web3](docs/doc2.md#Web3)
    * [区块链](docs/doc2.md#区块链)
    * [以太坊](docs/doc2.md#以太坊)
    * [比特币](docs/doc2.md#比特币)
    * [交易所](docs/doc2.md#交易所)
    * [区块链SDK](docs/doc2.md#区块链SDK)
    * [智能合约](docs/doc2.md#智能合约)
* [金融](docs/doc2.md#金融)
    * [金融API](docs/doc2.md#金融API)
    * [银行API](docs/doc2.md#银行API)
    * [量化交易](docs/doc2.md#量化交易)
    * [FIX引擎](docs/doc2.md#FIX引擎)
    * [订单匹配引擎](docs/doc2.md#订单匹配引擎)
    * [信用卡数据交换](docs/doc2.md#信用卡数据交换)
    * [金融信息交换](docs/doc2.md#金融信息交换)
    * [货币](docs/doc2.md#货币)
    * [FinTS](docs/doc2.md#FinTS)
    * [电子发票](docs/doc2.md#电子发票)
* [JavaCard](docs/doc2.md#JavaCard)
* [智能卡](docs/doc2.md#智能卡)
* [物联网](docs/doc2.md#物联网)
    * [物联网框架](docs/doc2.md#物联网框架)
    * [物联网平台](docs/doc2.md#物联网平台)
    * [智能家居](docs/doc2.md#智能家居)
    * [数字孪生](docs/doc2.md#数字孪生)
    * [物联网网关](docs/doc2.md#物联网网关)
    * [MQTT](docs/doc2.md#MQTT)
    * [车联网](docs/doc2.md#车联网)
    * [车载诊断](docs/doc2.md#车载诊断)
    * [嵌入式](docs/doc2.md#嵌入式)
    * [串口](docs/doc2.md#串口)
    * [Modbus](docs/doc2.md#Modbus)
    * [USB库](docs/doc2.md#USB库)
    * [XBee](docs/doc2.md#XBee)
* [短信](docs/doc2.md#短信)
* [邮件库](docs/doc2.md#邮件库)
* [邮件服务器](docs/doc2.md#邮件服务器)
* [DSL](docs/doc2.md#DSL)
* [JMX](docs/doc2.md#JMX)
* [RMI](docs/doc2.md#RMI)
* [gRPC](docs/doc2.md#gRPC)
* [对象池](docs/doc2.md#对象池)
* [幂等处理](docs/doc2.md#幂等处理)
* [数据字典](docs/doc2.md#数据字典)
* [Bot](docs/doc2.md#Bot)
    * [Discord机器人](docs/doc2.md#Discord机器人)
    * [Telegram机器人](docs/doc2.md#Telegram机器人)
    * [Facebook机器人](docs/doc2.md#Facebook机器人)
    * [QQ机器人](docs/doc2.md#QQ机器人)
    * [微信机器人](docs/doc2.md#微信机器人)
* [Android开发](docs/doc2.md#Android开发)
    * [Android框架](docs/doc2.md#Android框架)
    * [Android测试库](docs/doc2.md#Android测试库)
    * [Android UI库](docs/doc2.md#Android-UI库)
    * [ActionBar小部件](docs/doc2.md#ActionBar小部件)
    * [Activity小部件](docs/doc2.md#Activity小部件)
    * [Adapter](docs/doc2.md#Adapter)
    * [Android图表库](docs/doc2.md#Android图表库)
    * [Android日历库](docs/doc2.md#Android日历库)
    * [Android布局库](docs/doc2.md#Android布局库)
    * [Android富文本组件](docs/doc2.md#Android富文本组件)
    * [Android下拉刷新](docs/doc2.md#Android下拉刷新)
    * [Android项目模板](docs/doc2.md#Android项目模板)
    * [Android图像库](docs/doc2.md#Android图像库)
    * [Android ImageView](docs/doc2.md#Android-ImageView)
    * [Android选择器](docs/doc2.md#Android选择器)
    * [Android图片/视频选择器](docs/doc2.md#Android图片视频选择器)
    * [Android颜色选择器](docs/doc2.md#Android颜色选择器)
    * [Android日期/时间选择器](docs/doc2.md#Android日期时间选择器)
    * [Android文件/目录选择器](docs/doc2.md#Android文件目录选择器)
    * [Android国家选择器](docs/doc2.md#Android国家选择器)
    * [Android城市选择器](docs/doc2.md#Android城市选择器)
    * [Android位置选择器](docs/doc2.md#Android位置选择器)
    * [Android数字选择器](docs/doc2.md#Android数字选择器)
    * [Android滚动选择器](docs/doc2.md#Android滚动选择器)
    * [Android联系人选择器](docs/doc2.md#Android联系人选择器)
    * [Android更新库](docs/doc2.md#Android更新库)
    * [Android热修复](docs/doc2.md#Android热修复)
    * [Android运行时权限](docs/doc2.md#Android运行时权限)
    * [Android下载库](docs/doc2.md#Android下载库)
    * [Android评分库](docs/doc2.md#Android评分库)
    * [Android路由框架](docs/doc2.md#Android路由框架)
    * [Android导航库](docs/doc2.md#Android导航库)
    * [Android抽屉库](docs/doc2.md#Android抽屉库)
    * [Android动画库](docs/doc2.md#Android动画库)
    * [Android插件框架](docs/doc2.md#Android插件框架)
    * [Android WebView](docs/doc2.md#Android-WebView)
    * [Android加载库](docs/doc2.md#Android加载库)
    * [Android换肤框架](docs/doc2.md#Android换肤框架)
* [GUI开发/程序](docs/doc2.md#GUI开发程序)
    * [GUI框架](docs/doc2.md#GUI框架)
    * [移动开发框架](docs/doc2.md#移动开发框架)
    * [Swing](docs/doc2.md#Swing)
    * [Swing主题库](docs/doc2.md#Swing主题库)
    * [Swing UI库](docs/doc2.md#Swing-UI库)
    * [Swing组件库](docs/doc2.md#Swing组件库)
    * [Swing Dock库](docs/doc2.md#Swing-Dock库)
    * [Swing布局库](docs/doc2.md#Swing布局库)
    * [Swing选择器](docs/doc2.md#Swing选择器)
    * [Swing图表库](docs/doc2.md#Swing图表库)
    * [Swing测试库](docs/doc2.md#Swing测试库)
    * [JavaFX](docs/doc2.md#JavaFX)
    * [JavaFX主题库](docs/doc2.md#JavaFX主题库)
    * [JavaFX样式库](docs/doc2.md#JavaFX样式库)
    * [JavaFX组件库](docs/doc2.md#JavaFX组件库)
    * [JavaFX Dock库](docs/doc2.md#JavaFX-Dock库)
    * [JavaFX图表库](docs/doc2.md#JavaFX图表库)
    * [JavaFX图标库](docs/doc2.md#JavaFX图标库)
    * [JavaFX布局库](docs/doc2.md#JavaFX布局库)
    * [JavaFX动画库](docs/doc2.md#JavaFX动画库)
    * [JavaFX渲染库](docs/doc2.md#JavaFX渲染库)
    * [JavaFX项目模板](docs/doc2.md#JavaFX项目模板)
    * [键盘鼠标监听器](docs/doc2.md#键盘鼠标监听器)
    * [浏览器](docs/doc2.md#浏览器)
    * [JavaFX程序](docs/doc2.md#JavaFX程序)
    * [GUI程序](docs/doc2.md#GUI程序)
    * [IDE](docs/doc2.md#IDE)
    * [可视化编程](docs/doc2.md#可视化编程)
    * [文本编辑器](docs/doc2.md#文本编辑器)
    * [在线编辑器](docs/doc2.md#在线编辑器)
    * [数学软件](docs/doc2.md#数学软件)
    * [仿真软件](docs/doc2.md#仿真软件)
    * [UML工具](docs/doc2.md#UML工具)
    * [数电](docs/doc2.md#数电)
    * [数控](docs/doc2.md#数控)
    * [CAD](docs/doc2.md#CAD)
    * [办公软件](docs/doc2.md#办公软件)
    * [思维导图](docs/doc2.md#思维导图)
    * [音视频软件](docs/doc2.md#音视频软件)
    * [数据库软件](docs/doc2.md#数据库软件)
    * [数据库建模](docs/doc2.md#数据库建模)
    * [远程连接](docs/doc2.md#远程连接)
    * [终端模拟器](docs/doc2.md#终端模拟器)
    * [远程桌面控制](docs/doc2.md#远程桌面控制)
    * [Git客户端](docs/doc2.md#Git客户端)
    * [下载器](docs/doc2.md#下载器)
    * [MQTT客户端](docs/doc2.md#MQTT客户端)
    * [LaTeX编辑器](docs/doc2.md#LaTeX编辑器)
    * [字幕软件](docs/doc2.md#字幕软件)
* [游戏开发](docs/doc2.md#游戏开发)
    * [游戏引擎](docs/doc2.md#游戏引擎)
    * [Minecraft](docs/doc2.md#Minecraft)
    * [游戏服务器](docs/doc2.md#游戏服务器)
    * [游戏模拟器](docs/doc2.md#游戏模拟器)
    * [2D/3D渲染](docs/doc2.md#2D3D渲染)
    * [游戏开发库](docs/doc2.md#游戏开发库)
    * [碰撞检测](docs/doc2.md#碰撞检测)
    * [寻路算法](docs/doc2.md#寻路算法)
    * [实体框架](docs/doc2.md#实体框架)
    * [游戏编辑器](docs/doc2.md#游戏编辑器)
    * [开源游戏](docs/doc2.md#开源游戏)
    * [象棋引擎](docs/doc2.md#象棋引擎)
    * [游戏开发工具](docs/doc2.md#游戏开发工具)
    * [虚拟现实](docs/doc2.md#虚拟现实)
* [JVM代理](docs/doc2.md#JVM代理)
* [热加载](docs/doc2.md#热加载)
* [类加载](docs/doc2.md#类加载)
* [芯片模拟器](docs/doc2.md#芯片模拟器)
* [MIPS](docs/doc2.md#MIPS)
* [汇编](docs/doc2.md#汇编)
* [LLVM](docs/doc2.md#LLVM)
* [PC模拟器](docs/doc2.md#PC模拟器)
* [JavaME](docs/doc2.md#JavaME)
* [编译器](docs/doc2.md#编译器)
    * [内存中编译器](docs/doc2.md#内存中编译器)
    * [AOT编译器](docs/doc2.md#AOT编译器)
    * [编译器插件](docs/doc2.md#编译器插件)
* [AOT编译器](docs/doc2.md#AOT编译器)
* [语言服务器](docs/doc2.md#语言服务器)
* [元编程](docs/doc2.md#元编程)
* [对象存储](docs/doc2.md#对象存储)
* [文件系统](docs/doc2.md#文件系统)
* [音视频处理](docs/doc2.md#音视频处理)
    * [音频库](docs/doc2.md#音频库)
    * [视频库](docs/doc2.md#视频库)
    * [多媒体库](docs/doc2.md#多媒体库)
    * [视频通讯](docs/doc2.md#视频通讯)
    * [FFmpeg包装器](docs/doc2.md#FFmpeg包装器)
    * [音频编解码器](docs/doc2.md#音频编解码器)
    * [媒体服务器](docs/doc2.md#媒体服务器)
* [数据结构](docs/doc2.md#数据结构)
    * [树](docs/doc2.md#树)
    * [堆](docs/doc2.md#堆)
    * [图](docs/doc2.md#图)
    * [BitSet](docs/doc2.md#BitSet)
    * [队列](docs/doc2.md#队列)
    * [Map](docs/doc2.md#Map)
    * [List](docs/doc2.md#List)
    * [CRDT](docs/doc2.md#CRDT)
    * [布隆过滤器](docs/doc2.md#布隆过滤器)
    * [布谷鸟过滤器](docs/doc2.md#布谷鸟过滤器)
* [基本类型](docs/doc2.md#基本类型)
* [堆外内存库](docs/doc2.md#堆外内存库)
* [结构体](docs/doc2.md#结构体)
* [随机数生成器](docs/doc2.md#随机数生成器)
* [算法库](docs/doc2.md#算法库)
    * [字符串算法](docs/doc2.md#字符串算法)
    * [文本排序](docs/doc2.md#文本排序)
    * [聚类算法](docs/doc2.md#聚类算法)
    * [图算法](docs/doc2.md#图算法)
    * [随机流算法](docs/doc2.md#随机流算法)
    * [HyperLogLog算法](docs/doc2.md#HyperLogLog算法)
    * [Simhash算法](docs/doc2.md#Simhash算法)
    * [LSH算法](docs/doc2.md#LSH算法)
    * [LDA算法](docs/doc2.md#LDA算法)
    * [装箱算法](docs/doc2.md#装箱算法)
    * [下采样](docs/doc2.md#下采样)
    * [噪声库](docs/doc2.md#噪声库)
* [原生开发](docs/doc2.md#原生开发)
* [互操作](docs/doc2.md#互操作)
    * [Python](docs/doc2.md#Python)
    * [Swift](docs/doc2.md#Swift)
    * [Ruby](docs/doc2.md#Ruby)
    * [Rust](docs/doc2.md#Rust)
    * [R](docs/doc2.md#R)
    * [.NET](docs/doc2.md#NET)
* [操作系统信息](docs/doc2.md#操作系统信息)
* [外部进程执行](docs/doc2.md#外部进程执行)
* [守护进程](docs/doc2.md#守护进程)
* [COM桥](docs/doc2.md#COM桥)
* [GPU编程](docs/doc2.md#GPU编程)
* [硬件操作](docs/doc2.md#硬件操作)
* [操作系统](docs/doc2.md#操作系统)
* [运动规划](docs/doc2.md#运动规划)
* [自动规划](docs/doc2.md#自动规划)
* [电力系统](docs/doc2.md#电力系统)
* [量子计算](docs/doc2.md#量子计算)
* [IPFS](docs/doc2.md#IPFS)
* [地理空间](docs/doc2.md#地理空间)
    * [坐标库](docs/doc2.md#坐标库)
    * [经纬度库](docs/doc2.md#经纬度库)
    * [GIS系统](docs/doc2.md#GIS系统)
    * [GIS GUI](docs/doc2.md#GIS-GUI)
    * [大地测量](docs/doc2.md#大地测量)
* [路由引擎](docs/doc2.md#路由引擎)
* [GTFS](docs/doc2.md#GTFS)
* [几何学](docs/doc2.md#几何学)
* [航空航天](docs/doc2.md#航空航天)
* [天文学](docs/doc2.md#天文学)
* [水文学](docs/doc2.md#水文学)
* [地震学](docs/doc2.md#地震学)
* [物理库](docs/doc2.md#物理库)
* [无人机](docs/doc2.md#无人机)
* [AIS库](docs/doc2.md#AIS库)
* [转换库](docs/doc2.md#转换库)
* [IO库](docs/doc2.md#IO库)
* [文件监听](docs/doc2.md#文件监听)
* [目录库](docs/doc2.md#目录库)
* [RSS](docs/doc2.md#RSS)
* [SSE](docs/doc2.md#SSE)
* [EPC](docs/doc2.md#EPC)
* [FMI](docs/doc2.md#FMI)
* [OSGI](docs/doc2.md#OSGI)
* [RAML](docs/doc2.md#RAML)
* [OData](docs/doc2.md#OData)
* [海关](docs/doc2.md#海关)
* [蓝牙](docs/doc2.md#蓝牙)
* [校验](docs/doc2.md#校验)
* [IPP](docs/doc2.md#IPP)
* [OSC](docs/doc2.md#OSC)
* [CalDAV](docs/doc2.md#CalDAV)
* [WebDav](docs/doc2.md#WebDav)
* [AirPlay](docs/doc2.md#AirPlay)
* [Unicode](docs/doc2.md#Unicode)
* [表情库](docs/doc2.md#表情库)
* [字体库](docs/doc2.md#字体库)
* [语言库](docs/doc2.md#语言库)
* [敏感词过滤](docs/doc2.md#敏感词过滤)
* [国际化](docs/doc2.md#国际化)
* [翻译库](docs/doc2.md#翻译库)
* [字幕库](docs/doc2.md#字幕库)
* [字典库](docs/doc2.md#字典库)
* [颜色库](docs/doc2.md#颜色库)
* [短链接](docs/doc2.md#短链接)
* [单位库](docs/doc2.md#单位库)
* [调用图](docs/doc2.md#调用图)
* [语言检测](docs/doc2.md#语言检测)
* [解析库](docs/doc2.md#解析库)
    * [词法解析](docs/doc2.md#词法解析)
    * [表达式引擎](docs/doc2.md#表达式引擎)
    * [数学表达式](docs/doc2.md#数学表达式)
    * [正则表达式](docs/doc2.md#正则表达式)
    * [SQL解析器](docs/doc2.md#SQL解析器)
    * [解析器组合器](docs/doc2.md#解析器组合器)
    * [源代码解析](docs/doc2.md#源代码解析)
    * [手机号解析](docs/doc2.md#手机号解析)
    * [Cron解析](docs/doc2.md#Cron解析)
    * [Tree Sitter](docs/doc2.md#Tree-Sitter)
* [形式验证](docs/doc2.md#形式验证)
* [印章生成](docs/doc2.md#印章生成)
* [代码生成器](docs/doc2.md#代码生成器)
* [注解处理器](docs/doc2.md#注解处理器)
    * [访问器模式](docs/doc2.md#访问器模式)
    * [不可变模式](docs/doc2.md#不可变模式)
    * [配置对象模式](docs/doc2.md#配置对象模式)
    * [处理器测试](docs/doc2.md#处理器测试)
* [类路径扫描](docs/doc2.md#类路径扫描)
* [行为分析](docs/doc2.md#行为分析)
* [URL库](docs/doc2.md#URL库)
* [Expect库](docs/doc2.md#Expect库)
* [Wikipedia](docs/doc2.md#Wikipedia)
* [用户代理解析](docs/doc2.md#用户代理解析)
* [数字信号处理](docs/doc2.md#数字信号处理)
* [数字资产管理](docs/doc2.md#数字资产管理)
* [自动程序修复](docs/doc2.md#自动程序修复)
* [协议实现](docs/doc2.md#协议实现)
* [BitTorrent](docs/doc2.md#BitTorrent)
* [编解码](docs/doc2.md#编解码)
* [打印机](docs/doc2.md#打印机)
* [Web开发](docs/doc2.md#Web开发)
    * [WebAssembly](docs/doc2.md#WebAssembly)
    * [JavaScript引擎](docs/doc2.md#JavaScript引擎)
    * [GWT库](docs/doc2.md#GWT库)
    * [CSS库](docs/doc2.md#CSS库)
* [对象图导航](docs/doc2.md#对象图导航)
* [超媒体类型](docs/doc2.md#超媒体类型)
* [术语服务器](docs/doc2.md#术语服务器)
* [Maven插件](docs/doc2.md#Maven插件)
* [Gradle插件](docs/doc2.md#Gradle插件)
* [Intellij插件](docs/doc2.md#Intellij插件)
* [其他](docs/doc2.md#其他)
* [教程系列](docs/doc2.md#教程系列)
    * [Java教程](docs/doc2.md#Java教程)
    * [大数据教程](docs/doc2.md#大数据教程)
    * [Spring Boot教程](docs/doc2.md#Spring教程)
    * [算法和数据结构教程](docs/doc2.md#算法和数据结构教程)
    * [软件工程教程](docs/doc2.md#软件工程教程)
    * [Java安全教程](docs/doc2.md#Java安全教程)
    * [其他技术教程](docs/doc2.md#其他技术教程)
    * [源码分析](docs/doc2.md#源码分析)
    * [面试宝典](docs/doc2.md#面试宝典)

## 开发框架

这里列出了Java中的开发框架，包括Web、REST框架、微服务等。

#### Web框架

* [Jakarta Servlet](https://github.com/jakartaee/servlet)：Jakarta Servlet定义了用于处理HTTP请求和响应的服务器端API。
* [Spring Boot](https://github.com/spring-projects/spring-boot)：Spring Boot可帮助轻松创建由Spring驱动的生产级应用程序和服务，由Pivotal开源。
* [Apache Struts](https://github.com/apache/struts)：Struts是一个用于创建Java Web应用程序的免费开源解决方案。
* [GWT](https://github.com/gwtproject/gwt)：GWT是一个开发工具包，用于构建和优化复杂的基于浏览器的应用程序，由Google开源。
* [Solon](https://gitee.com/opensolon/solon)：Java新的应用开发框架，更小、更快、更简单。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序，由Lightbend开源。
* [Ring](https://github.com/ring-clojure/ring)：Ring是一个受Python的WSGI和Ruby的Rack启发的Clojure Web应用程序库。
* [Jodd](https://github.com/oblac/jodd)：Jodd是一组微框架和开发人员友好的工具和实用程序。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [Blade](https://github.com/lets-blade/blade)：Blade是一个追求简单、高效的Web框架。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web、ORM框架。
* [Grails](https://github.com/apache/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架，由Object Computing维护。
* [Javalin](https://github.com/javalin/javalin)：Javalin是一个非常轻量级的Kotlin和Java Web框架，支持WebSockets、HTTP2和异步请求。
* [Ninja](https://github.com/ninjaframework/ninja)：Ninja是Java的全栈Web框架，坚如磐石、快速且高效。
* [KVision](https://github.com/rjaros/kvision)：KVision是一个为Kotlin语言创建的开源Web框架，它允许开发人员使用Kotlin构建现代Web应用程序。
* [SOFABoot](https://github.com/sofastack/sofa-boot)：SOFABoot是一个基于Spring Boot的Java开发框架，由蚂蚁开源。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin允许你使用纯Java高效构建现代Web应用程序，而无需接触低级Web技术。
* [Jooby](https://github.com/jooby-project/jooby)：Jooby是一个现代、高性能且易于使用的Java和Kotlin Web框架上。
* [Elide](https://github.com/elide-dev/elide)：Elide是一个用于开发快速Web应用程序的云优先多语言运行时。
* [CabinJ](https://github.com/CabinJV/CabinJv)：CabinJ是一个使用Java NIO构建的高性能、轻量级HTTP服务器框架，可实现高效的非阻塞I/O操作。
* [JSweet](https://github.com/cincheo/jsweet)：JSweet利用TypeScript通过JavaScript库和框架用Java编写丰富且响应迅速的Web应用程序。
* [Wonder](https://github.com/wocommunity/wonder)：Wonder是最大的可重用WebObjects框架、应用程序和扩展的开源集合，最初由NeXT开发并由Apple维护。
* [Apache Flex](https://github.com/apache/flex-sdk)：Apache Flex是一个基于AdobeFlash平台用于开发和部署RIA的SDK，由Adobe维护。
* [Eclipse Krazo](https://github.com/eclipse-ee4j/krazo)：Eclipse Krazo是Jakarta MVC 2.0指定的基于操作的MVC实现。
* [Pippo](https://github.com/pippo-java/pippo)：Pippo是一个Java开源微型Web框架，具有最小的依赖性和快速的学习曲线。
* [Spark](https://github.com/perwendel/spark)：Spark是一个Java 8的小型Web框架。
* [Smart](https://gitee.com/huangyong/smart-framework)：Smart是一款轻量级Java Web框架，内置IoC、AOP、ORM、DAO、MVC等特性。
* [Citrus](https://github.com/webx/citrus)：Citrus是阿里开源的基于Java的Web框架。
* [Kobweb](https://github.com/varabyte/kobweb)：Kobweb是一个用于创建网站和Web应用程序的Kotlin框架，它建立在Compose HTML之上，并受到Next.js和Chakra UI的启发。
* [Apache Wicket](https://github.com/apache/wicket)：Wicket是一个开源、基于组件的Java Web应用程序框架。
* [RIFE2](https://github.com/rife2/rife2)：RIFE2是一个全栈、无声明的框架，可以使用现代Java快速、轻松地创建Web应用程序。
* [Apache Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架，专注于性能和开发人员生产力。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [ZK](https://github.com/zkoss/zk)：ZK是一个高效的Java框架，用于构建企业Web和移动应用程序。
* [FIT](https://github.com/ModelEngine-Group/fit-framework)：Java企业级AI开发框架，提供多语言函数引擎、流式编排引擎及Java生态的LangChain替代方案。
* [JVx](https://doc.sibvisions.com/jvx/home)：JVx是一个全栈应用程序框架，用于为不同的技术(Swing、Vaadin、React等)创建具有单一来源的多层应用程序，由SIB Visions公司开源。
* [Feat](https://gitee.com/smartboot/feat)：Feat是一个类似于Vert.x和Spring Boot的Java Web服务开发框架，专注于提供高性能、低资源消耗的解决方案。
* [Rose](https://github.com/paoding-code/paoding-rose)：Rose是由人人网、糯米网、小米提供的，基于Servlet规范的Web框架。
* [Lift](https://github.com/lift/framework)：Lift是一个强大、安全的Web框架。
* [Kora](https://github.com/kora-projects/kora)：Kora是一个用于编写Java/Kotlin应用程序的框架，重点关注性能、效率和透明度。
* [Duct](https://github.com/duct-framework/duct)：Duct是一个高度模块化的框架，用于使用数据驱动架构在Clojure中构建服务器端应用程序。
* [Oorian](https://oorian.com/)：Oorian是一个基于Java的框架，用于创建动态、交互式、数据驱动的Web应用程序。
* [JavaLite](https://github.com/javalite/javalite)：JavaLite是一个功能丰富的开发框架，包含Web、JDBC、Config等模块。
* [Vraptor4](https://github.com/caelum/vraptor4)：VRaptor是一个开源MVC框架，构建于CDI之上，由Caelum开源。
* [Scalatra](https://github.com/scalatra/scalatra)：Scalatra是一个小型、类似Sinatra的Scala Web框架。
* [Apache Cocoon](https://github.com/apache/cocoon)：Cocoon是围绕Pipeline，关注点分离和基于组件的Web开发的概念构建的Web应用程序框架。
* [AndServer](https://github.com/yanzhenjie/AndServer)：AndServer是Android平台的Web服务器和Web框架。
* [Takes](https://github.com/yegor256/takes)：Takes是一个真正的面向对象且不可变的Java Web开发框架。
* [Argo](https://github.com/58code/Argo)：Argo是起源于58同城的内部Web框架。
* [Kora](https://github.com/Tinkoff/kora)：Kora是一个基于JVM的框架，用于构建后端应用程序。
* [IGRP](https://github.com/NOSiCode-CV/IGRP-Framework)：IGRP是由美国NOSi开发的平台，用于创建Web应用程序，基于业务步骤、流程、自动代码生成和一次性原则的合并。
* [Klite](https://github.com/codeborne/klite)：Klite是一个适用于JVM上Kotlin协程的超轻量级非阻塞HTTP框架，由Codeborne开发。
* [Cicada](https://github.com/TogetherOS/cicada)：基于Netty的快速、轻量级Web框架。
* [Coody](https://gitee.com/coodyer/Coody-Framework)：Coody是一个国产IoC框架，轻量级、简单快速。
* [Skinny](https://github.com/skinny-framework/skinny-framework)：Skinny是一个用于构建Servlet应用程序的全栈Web应用程序框架。
* [Xitrum](https://github.com/xitrum-framework/xitrum)：Xitrum是一个基于Netty、Akka和Hazelcast的异步集群Scala Web框架。
* [Firefly](https://github.com/hypercube1024/firefly)：Firefly是一个异步Web框架，用于快速开发高性能Web应用程序。
* [Deft](https://github.com/rschildmeijer/deft)：Deft是一个在JVM上运行的单线程、异步、事件驱动的高性能Web服务器。
* [Alpas](https://github.com/alpas/alpas)：Alpas是一个基于Kotlin的Web框架，可让你简单、快速地创建Web应用程序和API。
* [Asta4D](https://github.com/astamuse/asta4d)：Asta4D是一个对设计人员友好、对开发人员灵活的Web应用程序框架。
* [FOXopen](https://github.com/Fivium/FOXopen)：FOXopen是一个基于Java的开源Web框架，能够快速开发基于安全工作流的Web系统，由英国能源与气候变化部开发。
* [Wasabi](https://github.com/wasabifx/wasabi)：为JVM定义一个简单、可扩展的HTTP框架，并使用Kotlin构建。
* [Java Express](https://github.com/simonwep/java-express)：基于Express.js的HTTP框架，无依赖，使用简单。
* [HappyX](https://github.com/HapticX/happyx)：HappyX是一个异步、面向宏、全栈支持的Web框架。
* [Jaggery](https://github.com/wso2/jaggery)：Jaggery是一个用于编写Web应用和基于HTTP的Web服务的框架，由WSO2开源。
* [Severell](https://github.com/severell/severell)：Severell是一个Web应用框架，旨在让Java Web应用开发变得轻松有趣。
* [PurpleJS](https://github.com/purplejs/purplejs)：PurpleJS是一个简单而强大的框架，无需脱离JavaScript即可创建高性能Web应用程序。
* [Pedestal](https://github.com/pedestal/pedestal)：Pedestal是一组用Clojure编写的库，旨在将语言及其原则引入服务器端开发。
* [CUBA Platform](https://github.com/cuba-platform/cuba)：CUBA Platform是一个高级框架，用于快速开发具有丰富Web界面的企业应用程序。
* [Tiny Framework](https://gitee.com/tinyframework/tiny)：企业级Java EE应用开发框架套件。
* [Minum](https://github.com/byronka/minum)：Minum是一个从头开始构建的最小Java Web框架，零依赖，使用虚拟线程。
* [TurboWeb](https://gitee.com/turboweb/turboweb)：TurboWeb是一个现代、高性能的Java Web框架，底层基于Netty，核心依托JDK 21虚拟线程，为高并发场景而生。
* [Dragome](https://www.dragome.com/)：Dragome是一个使用纯Java语言创建客户端Web应用程序的开源工具。
* [Atmosphere](https://github.com/Atmosphere/atmosphere)：Atmosphere框架包含用于构建异步Web应用程序的客户端和服务器端组件。
* [ACT Framework](https://gitee.com/actframework/actframework)：ACT是一个简洁易用，具有强大表达力的Java MVC全栈框架。
* [Hasor](https://gitee.com/clougence/hasor)：Hasor是一套基于Java语言的开发框架，可以和现有技术体系做到完美融合，由开云集致开源。
* [SiteMesh](https://github.com/sitemesh/sitemesh3)：SiteMesh是一个网页布局和装饰框架以及Web应用程序集成框架，可帮助创建由需要一致外观/感觉、导航和布局方案的页面组成的网站，由OpenSymphony开源。
* [Vert.x Web](https://github.com/vert-x3/vertx-web)：Vert.x Web是一套用于构建Web应用程序的构建块。
* [Objectos Way](https://github.com/objectos/objectos.way)：Objectos Way允许你仅使用Java编程语言来创建完整的Web应用程序。
* [Eclipse Scout](https://github.com/eclipse-scout/scout.rt)：Scout是一个成熟且开源的框架，适用于Web上的现代业务应用程序。
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next)：Cloudopt Next是一个非常轻量级、基于JVM的全栈Kotlin框架，支持Java、Kotlin语言，由最好的Java库和标准精心打造。
* [Errai Framework](https://github.com/errai/errai)：Errai是一个Java/GWT Web框架，用于构建富客户端Web应用程序，由RedHat开源。
* [Stripes](https://github.com/StripesFramework/stripes)：Stripes是一个Java Web框架，其目标是使Java中基于Servlet/JSP的Web开发尽可能简单、直观。
* [BBoss](https://github.com/bbossgroups/bboss)：BBoss是一个Java EE框架，包括AOP/IoC、MVC、持久层、RPC等。
* [Latke](https://github.com/88250/latke)：Latke是一个简单易用的Java Web应用开发框架，包含MVC、IoC、事件通知、ORM、插件等组件。
* [Nutz](https://github.com/nutzam/nutz)：面向所有Java开发人员的Web框架。
* [Kara](https://github.com/TinyMission/kara)：Kara是一个用Kotlin编写的JVM Web框架。
* [WebforJ](https://github.com/webforj/webforj)：WebforJ是一个强大且灵活的Web框架，可让你使用Java轻松创建现代且引人入胜的用户界面，由BASIS开源。
* [Albianj2](https://github.com/crosg/Albianj2)：Albianj是阅文集团设计并开发的一套分布式统一框架。
* [Restlight](https://github.com/esastack/esa-restlight)：Restlight是一个轻量级且面向REST的Web框架。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [Aspectran](https://github.com/aspectran/aspectran)：Aspectran是一个用于开发Java应用程序的框架，可用于构建简单的shell应用程序和大型企业Web应用程序。
* [Tentackle](https://bitbucket.org/krake-oss/tentackle)：Tentackle是一个开源Java框架，适用于在多个JVM上运行的分层应用程序，其灵感来自领域驱动设计的原理。
* [Astrix](https://github.com/AvanzaBank/astrix)：Astrix是一个Java框架，旨在简化微服务的开发和维护，由Avanza银行开源。
* [Uberfire](https://github.com/kiegroup/appformer)：Uberfire是一个Web框架，可在构建可扩展工作台和控制台类型应用程序方面提供卓越的体验，由JBoss社区开源。
* [TERASOLUNA](https://github.com/terasolunaorg/terasoluna-gfw)：TERASOLUNA是一种通过结合NTT Data的技术和知识来全面支持系统开发的解决方案。
* [Core NG](https://github.com/neowu/core-ng-project)：Core NG是专为长期可维护性和代码质量控制而设计和优化的Web框架。
* [AppFuse](https://github.com/appfuse/appfuse)：AppFuse是一个用于在JVM上构建Web应用程序的全栈框架。
* [Webery](https://github.com/wizzardo/webery)：基于Epoll的Java HTTP服务器。
* [HServer](https://gitee.com/HServer/HServer)：HServer是基于Netty开发的一个功能强大、资源丰富、开发灵活、轻量级、低入侵、高并发的新型Web开发框架。
* [YangMVC](https://gitee.com/yangtf/YangMVC)：YangMVC是一个现代化的Java Web框架，采用约定优于配置的设计理念，让Web开发变得简单高效。
* [YMP](https://gitee.com/suninformation/ymate-platform-v2)：YMP是一个非常简单、易用的轻量级Java应用开发框架，涵盖AOP、IoC、Web、ORM、Validation、Plugin、Serv、Cache等特性。
* [Efw](https://github.com/efwGrp/efw4.X)：EFW采用以目标为导向的方法，使用Ajax和服务器端JavaScript构建高速Web系统，由Escco开源。
* [JWt](https://github.com/emweb/jwt)：JWt是一个用于开发Web应用程序的Java库，它提供了一种纯Java组件驱动的方法来构建Web应用程序，并使用Ajax或纯HTML进行呈现。
* [Sumk](https://github.com/youtongluan/sumk)：Sumk的定位是为互联网公司提供一个快速开发、接口交互(RPC和HTTP)、数据缓存、读写分离、负载均衡、故障转移的框架。
* [TinyStruct](https://github.com/tinystruct/tinystruct)：TinyStruct是一个轻量级Java应用框架，设计用于构建从命令行工具到Web应用的各种应用程序。
* [Seasar2](https://github.com/seasarorg/seasar2)：Seasar2是一个为提高Java开发效率而开发的框架。
* [DataMill](https://github.com/rchodava/datamill)：DataMill是一个基于RxJava构建、采用函数式响应式风格的Web应用Java框架。
* [ServiceFramework](https://github.com/allwefantasy/ServiceFramework)：ServiceFramework是一个敏捷、快速、富领域模型的Java MVC框架。
* [Tio Boot](https://gitee.com/ppnt/tio-boot)：Tio Boot是新一代Java Web开发框架，更快、更小、更简单。
* [WComponents](https://github.com/BorderTech/wcomponents)：WComponents是一个用于为企业和政府构建可访问的Web应用程序的Java框架。
* [WebDSL](https://github.com/webdsl/webdsl)：WebDSL是一种用于使用丰富数据模型对Web应用程序进行建模的DSL，由代尔夫特理工大学开源。
* [Unify Framework](https://github.com/flowcentraltechnologies/unify-framework)：Unify Framework是一个基于服务器端组件的框架，用于在Java中开发Web应用程序。
* [Server Components](https://github.com/vadimv/server-components)：Server Components是一个Java Web服务器端渲染(SSR)框架，用于构建具有最少依赖的响应式UI。

#### RPC框架

* [Apache Dubbo](https://github.com/apache/dubbo)：Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [gRPC](https://github.com/grpc/grpc-java)：Google RPC的Java实现，基于HTTP/2的RPC。
* [Finagle](https://github.com/twitter/finagle)：Finagle是JVM的一个可扩展的RPC系统，用于构建高并发服务器，由Twitter开源。
* [Motan](https://github.com/weibocom/motan)：Motan是一个跨语言RPC框架，用于快速开发高性能分布式服务，由微博开源。
* [SOFARPC](https://github.com/sofastack/sofa-rpc)：SOFARPC是一个高性能、高扩展性、生产级的Java RPC框架，由蚂蚁开源。
* [RPC Framework](https://github.com/Snailclimb/guide-rpc-framework)：RPC Framework是一款基于Netty、Kyro、Zookeeper实现的自定义RPC框架。
* [Smithy](https://github.com/smithy-lang/smithy)：Smithy包含一种与协议无关的接口定义语言，用于生成客户端、服务器、文档和其他工件，由AWS开源。
* [Jupiter](https://github.com/fengjiachun/Jupiter)：Jupiter是一款性能非常不错、轻量级的分布式服务框架。
* [Pigeon](https://github.com/dianping/pigeon)：Pigeon是一个分布式RPC框架，在大众点评内部广泛使用。
* [Tars Java](https://github.com/TarsCloud/TarsJava)：Tars Java是腾讯Tars RPC框架的Java语言实现。
* [Apache Thrift](https://github.com/apache/thrift)：Thrift是一个轻量级、独立于语言的软件堆栈，用于点对点RPC实现，由Facebook开源。
* [OCTO-RPC](https://github.com/Meituan-Dianping/octo-rpc)：OCTO-RPC是支持Java和C++的企业级通信框架，在RPC服务之上扩展了丰富的服务治理功能，由美团开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint/tree/master/rpc)：Naver开源的RPC框架，服务于Pinpoint。
* [Protobuf RPC](https://github.com/baidu/Jprotobuf-rpc-socket)：Protobuf RPC是一种基于TCP协议的二进制RPC通信协议的Java实现，由百度开源。
* [Gaea](https://github.com/58code/Gaea)：Gaea是服务通讯框架，具有高并发、高性能、高可靠性，并提供异步、多协议、事件驱动的中间层服务框架，由58同城开源。
* [Joynr](https://github.com/bmwcarit/joynr)：Joynr是一个与传输协议无关(MQTT、HTTP、WebSockets等)、基于Franca IDL的通信框架，支持多种通信范例，由宝马开源。
* [DubboX](https://github.com/dangdangdotcom/dubbox)：DubboX在Dubbo框架中添加了RESTful远程处理、Kyro/FST序列化等功能，由当当开发。
* [NettyRPC](https://github.com/luxiaoxun/NettyRpc)：NettyRpc是一个基于Netty、ZooKeeper和Spring的简单RPC框架。
* [JoyRPC](https://github.com/jd-opensource/joyrpc)：JoyRPC是一款基于Java实现的RPC服务框架，由京东开源。
* [NettyRPC](https://github.com/tang-jie/NettyRPC)：NettyRPC是基于Netty的高性能Java RPC服务器，使用Kryo、Hessian、Protostuff支持消息序列化。
* [Koalas RPC](https://gitee.com/dromara/koalas-rpc)：Koalas是dromara社区开源的高可用、可拓展的RPC框架。
* [Kotlinx RPC](https://github.com/Kotlin/kotlinx-rpc)：Kotlinx RPC是一个Kotlin库，用于向应用程序添加RPC服务，由JetBrains开源。
* [IceRPC](https://github.com/zeroc-ice/ice)：IceRPC是一个新的开源RPC框架，可帮助你使用很少的代码构建速度极快的网络应用程序。
* [XXL-RPC](https://github.com/xuxueli/xxl-rpc)：XXL-RPC是一个分布式服务框架，提供稳定高性能的RPC远程服务调用功能。
* [Fluss RPC](https://github.com/apache/fluss/tree/main/fluss-rpc)：Fluss RPC框架及基于Netty的实现，由阿里开源。
* [gRPC Kotlin](https://github.com/grpc/grpc-kotlin)：Google gRPC的Kotlin/JVM实现，一个高性能、开源、通用的RPC框架。
* [Ob1k](https://github.com/outbrain-inc/ob1k)：Ob1k是一个异步轻量级RPC框架，用于快速开发异步、高性能微服务，由Outbrain开源。
* [RSocket RPC](https://github.com/rsocket/rsocket-rpc-java)：RSocket RPC是一个易于使用的RPC层，位于RSocket之上，由Netifi开源。
* [Sekiro](https://github.com/yint-tech/sekiro-open)：Sekiro是一个多语言、分布式、与网络拓扑无关的服务发布平台，由因体信息开源。
* [Hprose](https://github.com/hprose/hprose-java)：Hprose是一个高性能远程对象服务引擎。
* [HARPC](https://github.com/baifendian/harpc)：HARPC是基于Thrift的跨语言、高可用的RPC框架，由百分点科技开源。
* [Phantom](https://github.com/flipkart-incubator/phantom)：Phantom是一个用于访问分布式服务的高性能代理，是一个支持不同传输和协议的RPC系统，由Flipkart开源。
* [Remotely](https://github.com/Verizon/remotely)：Remotely是一个优雅、合理、纯函数式的远程系统，由Verizon开发。
* [Jenkins Remoting](https://github.com/jenkinsci/remoting)：Jenkins Remoting是一个库和可执行Java档案，它实现了Jenkins中的通信层。

#### JSF框架

* [Jakarta Faces](https://github.com/jakartaee/faces)：Jakarta Faces定义了一个MVC框架，用于构建Web应用程序的用户界面。
* [PrimeFaces](https://github.com/primefaces/primefaces)：PrimeFaces是Java EE生态系统中最受欢迎的UI库之一。
* [JoinFaces](https://github.com/joinfaces/joinfaces)：JoinFaces是一个致力于简化Spring Boot与JSF集成的开源框架。
* [IceFaces](https://www.icesoft.org/wiki/display/ICE/ICEfaces+Overview)：IceFaces是一个基于JSF标准的开源富互联网应用程序开发框架，由ICEsoft公司开源。
* [Omnifaces](https://github.com/omnifaces/omnifaces)：OmniFaces是Faces的实用程序库，专注于使用标准Faces API简化日常任务的实用程序。
* [Eclipse Mojarra](https://github.com/eclipse-ee4j/mojarra)：Mojarra是JSF标准的一个开源实现，由Oracle开发。
* [Apache MyFaces](https://github.com/apache/myfaces)：Apache基金会下的Jakarta Faces实现。
* [ButterFaces](https://github.com/butterfaces/butterfaces)：ButterFaces是一个轻量级响应式JSF框架，它结合了Bootstrap 4、jQuery 3和HTML 5的优点，可以使用JSF 2开发快速、简单且现代的Web应用程序。
* [RichFaces](https://github.com/richfaces/richfaces)：RichFaces项目是一个高级UI组件框架，可以使用JSF将Ajax功能轻松集成到业务应用程序中，由RedHat开源。
* [BootsFaces](https://github.com/TheCoder4eu/BootsFaces-OSP)：BootsFaces是一个基于Bootstrap 3和jQuery UI的强大且轻量级的JSF框架。
* [Reasonable ServerFaces](https://rsf.github.io/wiki/Wikib2ab.html)：Reasonable ServerFaces是一个用Java编写的开源Web编程框架，由剑桥大学教育技术应用研究中心开发。

#### REST框架

* [Jakarta REST](https://github.com/jakartaee/rest)：Jakarta RESTful Web Services提供了规范文档、TCK和基础API，以按照REST架构模式开发Web服务。
* [Rest.li](https://github.com/linkedin/rest.li)：Rest.li是一个开源REST框架，用于使用类型安全绑定和异步、非阻塞IO构建健壮、可扩展的RESTful架构，由LinkedIn开源。
* [Eclipse Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个REST框架，提供JAX-RS参考实现等，由Oracle开源。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [RESTEasy](https://github.com/resteasy/resteasy)：RESTEasy是一个JBoss项目，旨在为使用Java开发客户端和服务器RESTful应用程序和服务提供生产力框架，由RedHat开源。
* [Apache CXF](https://github.com/apache/cxf)：CXF是一个开源服务框架，可帮助你使用前端编程API(例如JAX-WS和JAX-RS)构建和开发服务，最初由IONA开发。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序，由ObjectStyle开源。
* [RESTX](https://github.com/restx/restx)：RESTX是一个完整的轻量级颠覆性堆栈，其中包括类似Swagger的UI并将REST规范测试视为文档。
* [Spray](https://github.com/spray/spray)：Spray是一套轻量级的Scala库，用于在Akka之上构建和使用RESTful Web服务。
* [Xenon](https://github.com/vmware-archive/xenon)：Xenon是一个用于编写小型REST服务的框架，由VMware开发。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Restlet框架帮助Java开发人员构建更好的遵循REST架构风格的Web API，由Talend开源。
* [RESTHeart](https://github.com/SoftInstigate/restheart)：RESTHeart是一个用于构建HTTP微服务的框架，旨在为开发人员提供开箱即用的直观API。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：Grumpyrest是一个Java REST服务器框架，不使用注解、自动依赖注入或响应流，并最大限度地减少反射的使用。
* [Resty](https://github.com/Dreampie/Resty)：Resty一款极简的RESTful轻量级的Web框架。
* [Airlift](https://github.com/airlift/airlift)：Airlift是一个用Java构建REST服务的框架，由Dropbox开源。
* [Apache Juneau](https://github.com/apache/juneau)：Juneau是一个强大的框架，用于简化构建和解析RESTful API的过程，由IBM开源。
* [Kanary](https://github.com/SeunAdelekan/Kanary)：用于在Kotlin/Java中构建REST API的简约Web框架。
* [Moqui Framework](https://github.com/moqui/moqui-framework)：Moqui是一个全功能、企业级应用开发框架，基于Groovy和Java语言。
* [Kilo](https://github.com/HTTP-RPC/Kilo)：Kilo是一个开源框架，用于在Java中创建和使用RESTful和类REST Web服务。
* [Cask](https://github.com/com-lihaoyi/cask)：Cask是一个简单的Scala Web框架，受到Python的Flask项目启发。
* [Crnk](https://github.com/crnk-project/crnk-framework)：Crnk是JSON API规范和建议的Java实现，旨在促进构建RESTful应用程序。
* [Chaos](https://github.com/d2iq-archive/chaos)：用Scala编写REST服务的轻量级框架，由Mesosphere开源。
* [Hammock](https://github.com/hammock-project/hammock)：Hammock是一个简单易用的框架，用于引导CDI、启动Web服务器并能够部署REST API。
* [Apache Sling](https://sling.apache.org/)：Sling是一个基于可扩展内容树的RESTful Web应用程序框架，由Adobe维护。
* [Apache Wink](https://wink.apache.org/)：Wink是一个简单而可靠的框架，用于构建RESTful Web服务。
* [Proteus](https://github.com/noboomu/proteus)：Proteus是一个极快的极简Java API服务器框架，构建于Undertow之上，用于开发后端应用程序和微服务。
* [Confluent REST Utils](https://github.com/confluentinc/rest-utils)：Confluence REST Utils提供了一个小型框架和实用程序，用于使用Jersey、Jackson、Jetty和Hibernate Validator编写Java REST API。
* [EverRest](https://github.com/codenvy/everrest)：EverRest是RESTful应用程序框架以及完整的JAX-RS实现。
* [Agrest](https://github.com/agrestio/agrest)：Agrest是一个灵活的模型驱动的REST数据服务框架，由ObjectStyle开源。
* [Lambada Framework](https://github.com/cagataygurturk/lambadaframework)：Lambada Framework是一个实现JAX-RS API的REST框架，可让你以Serverless方式将应用程序部署到AWS Lambda和API Gateway。
* [AceQL HTTP](https://github.com/kawansoft/aceql-http)：AceQL HTTP是一个类似REST的API库，允许你从任何支持HTTP的设备通过HTTP访问远程SQL数据库。
* [Utterlyidle](https://github.com/bodar/utterlyidle)：另一个受JSR 311优点启发的Java REST库。

#### WebService框架

* [JAX-WS](https://github.com/eclipse-ee4j/metro-jax-ws)：该项目包含Jakarta XML Web Service、Jakarta Web Services Metadata和Jakarta XML Web Services规范实现。
* [Apache WS](https://ws.apache.org/)：Apache WS汇聚了众多与Web Service相关的项目，涵盖从基础XML解析器到WS标准集的各种内容。
* [Apache CXF](https://github.com/apache/cxf)：CXF是一个开源服务框架，可帮助你使用前端编程API(例如JAX-WS和JAX-RS)构建和开发服务，最初由IONA开发。
* [Spring WS](https://github.com/spring-projects/spring-ws)：Spring Web Services是Spring社区的一款产品，专注于创建文档驱动的Web服务。
* [SOAP WS](https://github.com/reficio/soap-ws)：SOAP WS是一个轻量级且易于使用的Java库，它包装了Spring WS并支持在纯XML级别处理SOAP。
* [WSC](https://github.com/forcedotcom/wsc)：WSC是一个使用流式解析器实现的高性能Web Service客户端堆栈，由Salesforce开源。
* [Apache Axis2](https://github.com/apache/axis-axis2-java-core)：Apache Axis2是一个Web Services JSON/SOAP/WSDL引擎。

#### 微服务框架

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring Cloud为开发人员提供了快速构建分布式系统中一些常见模式的工具，由Pivotal开源。
* [Apache Dubbo](https://github.com/apache/dubbo)：Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [Jakarta EE](https://jakarta.ee/)：Jakarta EE为开发人员提供了一套全面的供应商中立的开放规范，用于从头开始开发现代云原生Java应用程序，由Eclipse基金会维护。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：Micronaut是一个基于JVM的现代全栈Java框架，旨在构建模块化、易于测试的JVM应用程序，由Object Computing开源。
* [Quarkus](https://github.com/quarkusio/quarkus)：Quarkus是一个用于编写Java应用程序的云原生容器优先框架，由RedHat开发。
* [Helidon](https://github.com/helidon-io/helidon)：Helidon是一组用于编写微服务的Java库，基于Java虚拟线程，由Oracle开发。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包，由RedHat开源。
* [Finatra](https://github.com/twitter/finatra)：Finatra是一个轻量级框架，用于在TwitterServer和Finagle之上构建快速、可测试的Scala应用程序，由Twitter开源。
* [tRPC](https://github.com/trpc-group/trpc-java)：tRPC Java作为tRPC的Java语言实现，是一个久经考验的微服务框架，由腾讯开源。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个用于创建微服务、Web应用程序等的异步框架，由Jetbrains开源。
* [ScaleCube](https://github.com/scalecube/scalecube-services)：ScaleCube是一个通过提供可嵌入的微服务库来简化响应式和分布式应用程序开发的项目。
* [ServiceTalk](https://github.com/apple/servicetalk)：ServiceTalk是一个JVM网络应用程序框架，具有针对特定协议(例如HTTP/1.x、HTTP/2.x等)定制的API，并支持多种编程范例，由Apple开源。
* [RestExpress](https://github.com/RestExpress/RestExpress)：RestExpress是用于快速创建可扩展、无容器、RESTful微服务的极简Java框架，由Facebook开源。
* [Apache ServiceComb](https://github.com/apache/servicecomb-java-chassis)：ServiceComb是一个用于用Java快速开发微服务的软件开发工具包，提供服务注册、服务发现、动态路由和服务管理功能，由华为开源。
* [Eclipse MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展，由IBM、RedHat、Oracle、Fujitsu、Microsoft等组织参与。
* [Axon](https://github.com/AxonFramework/AxonFramework)：Axon是一个基于DDD、CQRS和事件溯源原则构建渐进式事件驱动微服务系统的框架。
* [KivaKit](https://github.com/Telenav/kivakit)：KivaKit是一套用于日常开发的集成Java迷你框架，由Telenav开源。
* [Riposte](https://github.com/Nike-Inc/riposte)：Riposte是一个基于Netty的微服务框架，用于快速开发生产就绪的HTTP API，由Nike开源。
* [Lagom](https://github.com/lagom/lagom)：Lagom是一个开源框架，用于用Java或Scala构建响应式微服务系统，由Lightbend开源。
* [Apollo](https://github.com/spotify/apollo)：Apollo是Spotify编写微服务时使用的一组Java库，包含HTTP服务器和URI路由系统等模块，使得实现RESTful API服务变得轻而易举。
* [Armeria](https://github.com/line/armeria)：Armeria是适合任何情况的首选微服务框架，你可以利用自己喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Streams、Spring Boot和Dropwizard，由Line开源。
* [GreenLightning](https://oci-pronghorn.gitbook.io/greenlightning)：GreenLightning是一个可嵌入的高性能微服务框架，内置HTTP和MQTT支持。
* [Light-4J](https://github.com/networknt/light-4j)：Light-4J是快速、轻量级且更高效的微服务框架。
* [MSF4J](https://github.com/wso2/msf4j)：MSF4J是一个用于开发和运行微服务的轻量级高性能框架，由WSO2开源。
* [NutzBoot](https://gitee.com/nutz/nutzboot)：NutzBoot是可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、流控熔断、分布式事务等解决方案。
* [Starlight](https://github.com/baidu/starlight)：Starlight是一套面向云原生的微服务通信框架，兼容Spring生态，由百度开源。
* [KumuluzEE](https://github.com/kumuluz/kumuluzee)：KumuluzEE是一个轻量级框架，用于使用标准Java、Java EE/Jakarta EE技术开发微服务并将现有Java应用程序迁移到微服务，由SUNESIS公司开发。
* [Apache Meecrowave](https://github.com/apache/openwebbeans-meecrowave)：Meecrowave是Apache的一个轻量级微服务框架，能够与CDI、JAX-RS和JSON API完美兼容。
* [Ja-Micro](https://github.com/Sixt/ja-micro)：Ja-Micro是一个用于构建微服务的轻量级Java框架，由Sixt开发。
* [Colossus](https://github.com/tumblr/colossus)：Colossus是一个用来构建Scala微服务的轻量级I/O框架，由Tumblr开源。
* [JBoot](https://gitee.com/JbootProjects/jboot)：JBoot是一个基于JFinal、Dubbo、Seata、Sentinel、ShardingSphere、Nacos等开发的国产框架。
* [ActiveJ](https://github.com/activej/activej)：ActiveJ是适用于现代Web、云、高负载和微服务的Java框架。
* [Launcher](https://github.com/fujitsu/launcher)：Launcher是MicroProfile的一个实现，由Fujitsu开源。
* [Flower](https://github.com/zhihuili/flower)：Flower是一个构建在Akka上的响应式微服务框架。
* [Las2peer](https://github.com/rwth-acis/las2peer)：Las2peer是一个基于Java的服务器框架，用于在分布式点对点(P2P)环境中开发和部署微服务，由亚琛工业大学开发。
* [Dapeng SOA](https://github.com/dapeng-soa/dapeng-soa)：Dapeng SOA是一个轻量级、高性能的微服务框架，构建在Netty以及定制的精简版Thrift之上，大鹏开源。
* [Redkale](https://gitee.com/redkale/redkale)：Redkale是基于Java 11全新的微服务框架，包含HTTP、WebSocket、TCP/UDP、数据序列化、数据缓存、依赖注入等功能。
* [SeedStack](https://github.com/seedstack/seed)：SeedStack是一个固执己见、易于使用的Java开发堆栈。
* [Moleculer Java](https://github.com/moleculer-java/moleculer-java)：Moleculer Java是JVM的Moleculer微服务框架的实现。

#### Spring Cloud框架

* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix)：Spring Cloud Netflix项目为Spring Boot应用程序提供Netflix OSS集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：Spring Cloud AWS简化了在Spring和Spring Boot应用程序中使用AWS托管服务。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：Spring Cloud GCP项目使Spring框架成为Google Cloud Platform的一等公民。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是Microsoft开发的Spring Cloud框架，提供Spring与Azure服务的无缝集成。
* [Spring Cloud OCI](https://github.com/oracle/spring-cloud-oci)：Spring Cloud OCI在内部OCI Java SDK的帮助下简化了与Oracle OCI服务的集成。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：Spring Cloud Alibaba为分布式应用开发提供一站式解决方案。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是实现标准Spring Cloud SPI的一站式微服务解决方案，它将Spring Cloud与腾讯中间件集成，让微服务开发变得简单。
* [Spring Cloud Huawei](https://github.com/huaweicloud/spring-cloud-huawei)：Spring Cloud Huawei是一个让使用Spring Cloud开发微服务变得更加简单和高效的框架。
* [Spring Cloud Formula](https://gitee.com/baidu/spring-cloud-formula)：Spring Cloud Formula是百度云CNAP的面向客户提供的Java微服务框架设施。

## 微服务库

* [Dapr Java](https://github.com/dapr/java-sdk)：Dapr是Microsoft开源的一个可移植、事件驱动的运行时，用于跨云和边缘构建分布式应用程序。
* [CloudEvents Java](https://github.com/cloudevents/sdk-java)：CloudEvents是一种以通用格式描述事件数据的规范，以提供跨服务、平台和系统的互操作性。
* [Nepxion Discovery](https://github.com/Nepxion/Discovery)：Nepxion Discovery是专注于企业级云原生微服务开源解决方案。
* [Microserver](https://github.com/aol/micro-server)：Microserver是一个Java 8原生、零配置、基于标准、久经考验的库，可通过标准Java主类运行REST微服务，由AOL开源。
* [Eventuate Tram Core](https://github.com/eventuate-tram/eventuate-tram-core)：Eventuate Tram是一个解决微服务架构中固有的分布式数据管理问题的平台。
* [TAC](https://github.com/alibaba/tac)：TAC是与Tangram配套的服务端解决方案，由阿里提供。
* [QBit](https://github.com/advantageous/qbit)：QBit是一个用于构建微服务的响应式编程库。
* [Misk](https://github.com/cashapp/misk)：Misk是来自Cash App的开源微服务容器，它允许你使用Kotlin或Java快速创建微服务。
* [Stitch](https://github.com/twitter/stitch)：Stitch是一个Scala库，用于优雅高效地组合对服务的RPC调用，由Twitter开发。
* [Conjure](https://github.com/palantir/conjure)：Conjure是一个简单的工具链，用于定义一次API并生成多种语言的客户端/服务器接口，由Palantir开源。
* [Hexagon](https://github.com/hexagonkt/hexagon)：Hexagon是一个用Kotlin编写的微服务工具包，其目的是简化在云平台内运行的服务器应用程序的构建。
* [Mica](https://gitee.com/596392912/mica)：Spring Cloud微服务开发核心工具集，支持Web和WebFlux。
* [Baker](https://github.com/ing-bank/baker)：Baker是一个库，它提供了一种简单直观的方法来编排基于微服务的流程，由ING银行开源。
* [AdeptJ Runtime](https://github.com/AdeptJ/adeptj-runtime)：适用于RESTful API、微服务和Web应用的高性能、动态、模块化运行时。
* [Prana](https://github.com/Netflix/Prana)：用于基于Netflix OSS的服务的Sidecar，由Netflix开源。
* [Edison MicroService](https://github.com/otto-de/edison-microservice)：Spring Boot之上的独立库集合，可提供更快的JVM微服务设置。
* [Squbs](https://github.com/paypal/squbs)：Squbs是一套组件，可在大规模托管云环境中实现Akka和Akka HTTP应用程序/服务的标准化和可操作化，Paypal开源。
* [SIP Framework](https://github.com/IKOR-GmbH/sip-framework)：该框架能够使用微服务构建轻量级集成适配器，以实现系统的技术和非技术解耦，因此具有高度可扩展性。
* [Mats3](https://github.com/centiservice/mats3)：Mats3是一个Java库，可促进异步、无状态、多阶段、基于消息的服务的开发。
* [Mercury](https://github.com/Accenture/mercury)：Mercury是一个用于事件驱动编程的软件开发工具包，由Accenture开源。
* [Fluxzero](https://github.com/fluxzero-io/fluxzero-sdk-java)：Fluxzero是一个云运行时，用于构建后端，而无需基础设施开销。

## 微服务治理

* [Moss](https://github.com/GrailStack/Moss)：Moss是Spring Cloud体系的服务治理平台。
* [Femas](https://github.com/TencentFemas/femas)：Femas是腾讯云微服务平台TSF的开源产品形式，专注于微服务的运行状态，提供多框架统一服务发现、南北东西流量管理、服务可观测性、配置管理等一站式微服务管控能力。
* [Sermant](https://github.com/sermant-io/Sermant)：Sermant是基于Java字节码增强技术的无代理服务网格，其利用Java字节码增强技术为宿主应用程序提供服务治理功能，以解决大规模微服务体系结构中的服务治理问题，由华为开源。
* [ArchGuard](https://github.com/archguard/archguard)：ArchGuard是一个由Thoughtworks发起的面向微服务(分布式场景)下的开源架构治理平台。
* [OpenSergo](https://github.com/opensergo)：OpenSergo是一个开源、与语言无关、接近业务语义的云原生服务治理规范，在异构微服务系统场景下，企业可以通过这个统一的规范来管理不同语言、不同协议的服务，这是阿里联合B站、字节发起的项目。
* [Joylive](https://github.com/jd-opensource/joylive-agent)：基于字节码增强的面向应用多活和单元化的微服务流量治理框架，由京东开源。
* [Water](https://gitee.com/noear/water)：为Java服务开发和治理，提供一站式解决方案(可以理解为微服务架构支持套件)。
* [CoSky](https://gitee.com/AhooWang/CoSky)：CoSky是一个轻量级微服务治理平台，为分布式系统提供服务发现和配置管理功能。
* [DHorse](https://github.com/512team/dhorse)：DHorse是一个轻量级、简单易用的云应用管理平台，具有多云和多环境管理、应用管理和部署、服务治理等功能。

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
* [Spring REST Exception Handler](https://github.com/jirutka/spring-rest-exception-handler)：该项目的目标是为RESTful API提供一个方便的异常处理程序，以满足错误响应的最佳实践，而无需重复。
* [Unified Dispose Spring Boot](https://github.com/purgeteam/unified-dispose-springboot)：包含一些基础的异常处理以及返回包装功能。
* [Spring MVC REST Exhandler](https://github.com/stormpath/spring-mvc-rest-exhandler)：Spring MVC REST异常处理程序。

## 构建工具

* [Apache Maven](https://github.com/apache/maven)：Maven是一个软件项目管理和理解工具。
* [Gradle](https://github.com/gradle/gradle)：Gradle是一个构建工具，专注于构建自动化并支持多语言开发。
* [Bazel](https://github.com/bazelbuild/bazel)：Bazel是一个快速、多语言且可扩展的构建系统，由Google开发。
* [Apache Mvnd](https://github.com/apache/maven-mvnd)：Mvnd是Maven团队借鉴了Gradle和Takari后衍生出的更快的构建工具。
* [SBT](https://github.com/sbt/sbt)：SBT是一个适用于Scala、Java的构建工具。
* [Leiningen](https://github.com/technomancy/leiningen)：Leiningen是一种构建自动化和依赖管理工具，用于以Clojure编程语言编写的软件项目的简单配置。
* [Apache Ant](https://github.com/apache/ant)：Ant是一个基于Java的构建工具。
* [Buck](https://github.com/facebook/buck)：Buck是一个快速构建系统，鼓励在各种平台和语言上创建小型、可重用的模块，由Facebook开发。
* [Mill](https://github.com/com-lihaoyi/mill)：Mill是一个现代化的构建工具，支持Scala和Java项目的构建和管理。
* [Pants](https://github.com/pantsbuild/pants)：Pants是一个快速、可扩展、用户友好的构建系统，适用于各种规模的代码库，由Twitter开源。
* [Amper](https://github.com/JetBrains/amper)：Amper是一个项目配置工具，其目标是改善项目配置体验和工具性，即IDE内部的支持，同时还提供流畅的开箱即用体验，由JetBrains开源。
* [1JPM](https://github.com/Osiris-Team/1JPM)：1JPM是一种Maven/Gradle替代方案，但有所不同，它本身是一个Java文件，你应该编辑该文件来配置你的项目。
* [Bloop](https://github.com/scalacenter/bloop)：Bloop是一个构建服务器和CLI工具，可从任何编辑器或构建工具快速编译、测试和运行Scala。
* [Boot](https://github.com/boot-clj/boot)：Boot是一个Clojure构建框架和临时Clojure脚本评估器。
* [JeKa](https://github.com/jeka-dev/jeka)：JeKa是一个Java构建工具，用于直接从源代码构建或执行Java应用程序和脚本，由OW2开发。
* [BLD](https://github.com/rife2/bld)：BLD是一个新的构建系统，允许你用纯Java编写构建逻辑。
* [Pro](https://github.com/forax/pro)：Pro是与Java 9模块无缝协作的Java构建工具。
* [Fury](https://github.com/propensive/fury-old)：Fury是下一代构建工具，以解决在不断变化的环境中构建软件的最大挑战，同时保持构建的可预测性、可靠性和简单性。
* [Bach](https://github.com/sormuras/bach)：Bach是一个编排JDK工具以构建模块化Java项目的工具。
* [Savant](https://github.com/savant-build/savant-core)：Savant是一个用Java编写的构建工具，它使用Groovy DSL来构建文件，由Inversoft公司开源。
* [Saker.build](https://github.com/sakerbuild/saker.build)：Saker.build是一个与语言无关的构建系统，专注于可扩展性和可扩展的增量构建。
* [Kobalt](https://github.com/cbeust/kobalt)：Kobalt是一个受Gradle和Maven启发的构建系统。
* [Batect](https://github.com/batect/batect)：Batect允许你根据一个或多个Docker容器定义你的开发任务，在任何地方快速、一致地运行这些任务，并轻松地与你的团队共享。

## 包管理器

* [Coursier](https://github.com/coursier/coursier)：Coursier是Scala应用程序和工件管理器。
* [Apache Ivy](https://github.com/apache/ant-ivy)：Apache Ivy是一个用于管理项目依赖关系的工具。
* [Nuts](https://github.com/thevpc/nuts)：Nuts是一个Java包管理器，可帮助以简单直接的方式发现、下载、组装和执行本地和远程工件(包)。
* [JPM](https://github.com/codejive/java-jpm)：JPM是一个简单的命令行工具，用于管理不使用Maven或Gradle等构建系统的Java项目的Maven依赖。
* [Nix](https://github.com/fzakaria/mvn2nix)：Nix包管理器用于轻松打包Maven Java应用程序。

## CI/CD

* [Jenkins](https://github.com/jenkinsci/jenkins)：Jenkins是领先的开源自动化服务器，使用Java构建，提供超过2000个插件来支持几乎所有事情的自动化。
* [Spinnaker](https://github.com/spinnaker/spinnaker)：Spinnaker是一个开源持续交付平台，用于快速、可靠地发布软件变更，由Netflix和Google开源。
* [CloudBees](https://docs.cloudbees.com/)：CloudBees是一种功能齐全的云原生功能，可托管在本地或公共云中，用于大规模交付CI。
* [CircleCI](https://circleci.com/)：CircleCI是一个持续集成和持续交付平台，可用于实施DevOps实践。
* [TeamCity](https://www.jetbrains.com/teamcity/)：TeamCity是一个通用CI/CD软件平台，可实现灵活的工作流程、协作和开发实践，这是JetBrains的商业产品。
* [Bamboo](https://www.atlassian.com/software/bamboo)：Bamboo是一款持续集成构建服务器软件，Atlassian提供的商业软件，也有免费版本。
* [GoCD](https://github.com/gocd/gocd)：GoCD可帮助你自动化和简化构建-测试-发布周期，从而无忧、持续地交付产品，由ThoughtWork开源。
* [OneDev](https://github.com/theonedev/onedev)：OneDev是一个具有CI/CD、看板的自托管Git服务器。
* [FlowCI](https://github.com/FlowCI/flow-core-x)：FlowCI是一个开源CI/CD自动化服务器，旨在以最简单、最快、最轻松的方式建立自托管CI/CD服务。
* [BK CI](https://github.com/TencentBlueKing/bk-ci)：BlueKing是一个免费并开源的CI服务，可助你自动化构建-测试-发布工作流，持续、快速、高质量地交付你的产品，由腾讯开源。
* [JReleaser](https://github.com/jreleaser/jreleaser)：JReleaser是一个用于Java和非Java项目的自动化发布工具。
* [Hudson](https://github.com/hudson/hudson-2.x)：Hudson是用Java编写的一个持续集成工具，由Sun开源。
* [Arbess](https://github.com/tiklab-project/tiklab-arbess)：Arbess是一款强大的开源CI/CD工具，旨在帮助开发团队高效管理构建、测试和部署流程。
* [Apache Continuum](https://continuum.apache.org/)：Continuum是一款企业级持续集成服务器，具有自动构建、发布管理、基于角色的安全性以及与流行构建工具和源代码控制管理系统的集成等功能。
* [Harness CD Community Edition](https://github.com/harness/harness-core)：Harness CD是一种现代自助式持续交付解决方案，允许开发人员在他们选择的任何公共或私有云基础设施上部署、验证和自动回滚Kubernetes和其他云原生应用程序。
* [Bob](https://github.com/bob-cd/bob)：Bob允许你构建自己的自定义CI/CD基础设施，从而允许你将Bob用于各种不同的目的。
* [CruiseControl](https://cruisecontrol.sourceforge.net/)：CruiseControl既是一个持续集成工具，也是一个用于创建自定义持续构建流程的可扩展框架，由ThoughtWorks开源。

## JDK

* [Oracle OpenJDK](https://github.com/openjdk/jdk)：Oracle开源的OpenJDK官方版本。
* [Amazon Corretto](https://github.com/corretto/corretto-8)：Amazon Corretto是OpenJDK的免费、多平台、生产就绪发行版。
* [Eclipse Temurin](https://github.com/adoptium/temurin-build)：Eclipse基金会下的JDK版本，由Adoptium工作组开源。
* [BellSoft Liberica](https://github.com/bell-sw/Liberica)：Liberica JDK是由BellSoft出品的一款免费开源Java开发工具包。
* [GraalVM](https://github.com/oracle/graal)：GraalVM是Oracle开源的一个高性能JDK发行版，可提前将Java应用程序编译成独立的二进制文件。
* [Microsoft OpenJDK](https://github.com/microsoft/openjdk)：Microsoft OpenJDK是一个新的免费长期支持发行版。
* [Azul Zulu](https://www.azul.com/zh-hans/core/)：Azul Zulu是经过TCK测试和认证的开源OpenJDK构建版本。
* [IBM Semeru](https://www.ibm.com/support/pages/java-sdk-downloads)：IBM开源的JDK版本，基于OpenJ9构建。
* [RedHat JDK](https://developers.redhat.com/products/openjdk/download)：RedHat版本的OpenJDK是Java SE的开源实现。
* [JetBrains Runtime](https://github.com/JetBrains/JetBrainsRuntime)：JetBrains Runtime是OpenJDK的一个分支，适用于Windows、MacOS X和Linux。
* [OpenLogic](https://www.openlogic.com/openjdk-downloads)：Perforce公司开源的OpenLogic为Linux、Windows和MacOS提供免费的OpenJDK 8、11、17和21季度版本。
* [Axiom JDK](https://axiomjdk.ru/)：Axiom JDK是一个基于开源项目OpenJDK的俄罗斯可信Java开发和执行环境。
* [SapMachine](https://github.com/SAP/SapMachine)：SapMachine是SAP维护的OpenJDK的一个发行版。
* [Apache Harmony](https://harmony.apache.org/)：Apache Harmony旨在创建一个兼容Java SE 5和Java SE 6标准的完整、独立的Java运行时环境，主要由IBM开发。
* [Canonical OpenJDK](https://ubuntu.com/toolchains/java)：Canonical为Ubuntu构建的OpenJDK，提供长达12年的安全维护。
* [Alibaba Dragonwell](https://github.com/dragonwell-project/dragonwell8)：阿里巴巴Dragonwell是OpenJDK的下游版本，也是阿里内部的OpenJDK实现。
* [Tencent Kona](https://github.com/Tencent/TencentKona-8)：腾讯Kona是OpenJDK的免费、生产就绪发行版，提供长期支持和季度更新。
* [Huawei Bisheng](https://gitee.com/openeuler/bishengjdk-8)：毕昇JDK是华为内部OpenJDK定制版Huawei JDK的开源版本，是一个高性能、可用于生产环境的OpenJDK发行版。
* [CompoundVM](https://github.com/bytedance/CompoundVM)：CVM是一个旨在将高版本JVM的性能提升到低版本JDK的项目，你可以几乎零成本地升级项目，并在应用程序上运行高级JVM功能，由字节开发。
* [Loongson JDK](https://github.com/loongson/jdk)：龙芯平台Java环境是龙芯公司基于OpenJDK自主研发的MIPS版本。
* [RunSoon OpenJDK](https://clmarket.e-bridge.com.cn/clmarket/#/clmarket/index)：楠竹OpenJDK由神州数码提供支持，并拥有合同规定的SLA。
* [坤泽JDK](https://www.primeton.com/products/jdk/)：坤泽JDK是基于OpenJDK进行信创适配与增强、一款高性能、可用于生产环境的商业发行版，由普元提供。

## JVM实现

* [HotSpot](https://github.com/openjdk/jdk/tree/master/src/hotspot)：HotSpot是一款用于桌面和服务器计算机的Java虚拟机，由Sun开发。
* [DCEVM](https://github.com/dcevm/dcevm)：DCEVM是Java HotSpot VM的修改版，允许在运行时无限地重新定义已加载的类，由约翰普勒林茨大学开源。
* [LeJOS](https://lejos.sourceforge.io/)：LeJOS是乐高Mindstorms EV3、NXT和RCX积木的替换固件，你可以使用Java对乐高机器人进行编程，使用LeJOS开发的机器人曾在国际空间站上运行。
* [Jikes RVM](https://github.com/JikesRVM/JikesRVM)：Jikes RVM提供了一个灵活的开放式测试平台，可以对虚拟机技术进行原型设计并尝试多种设计方案，曾经为虚拟机技术前沿研究超过180篇出版物和36篇论文。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：OpenJ9是适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化，由IBM开发。
* [Avian](https://github.com/ReadyTalk/avian)：Avian是一个轻量级虚拟机和类库，旨在提供有用的Java功能子集，适合构建独立的应用程序。
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)：ParparVM是Codename One开发的VM，用于取代最初构建它时已失效的XMLVM。
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

## JVM语言

* [Java](https://www.oracle.com/java/)：Java是一种采用面向对象范式的通用编程语言，由Oracle领导。
* [Groovy](https://github.com/apache/groovy)：Groovy是一种适用于JVM平台的强大的多方面编程语言。
* [kotlin](https://github.com/JetBrains/kotlin)：kotlin是一种开源静态类型编程语言，由JetBrains和开源贡献者支持和开发。
* [Scala](https://github.com/scala/scala)：Scala是一门多范式的编程语言，设计初衷是要集成面向对象编程和函数式编程的各种特性，由洛桑联邦理工学院开源。
* [Clojure](https://github.com/clojure/clojure)：Clojure是一种动态的通用编程语言，它将脚本语言的易用性和交互式开发与高效、强大的多线程编程基础架构相结合。
* [Jython](https://github.com/jython/jython)：Jython是Python在Java中的实现。
* [JRuby](https://github.com/jruby/jruby)：JRuby是使用JVM的Ruby语言的实现。
* [DDlog](https://github.com/vmware/differential-datalog)：DDlog是一种用于增量计算的编程语言，它非常适合编写不断更新输出以响应输入变化的程序，由VMware开源。
* [Eta](https://github.com/typelead/eta)：Eta编程语言是Haskell的一种方言，运行在JVM上。
* [Lux](https://github.com/LuxLang/lux)：Lux编程语言是一个函数式、静态类型的Lisp，可以在多个平台上运行，例如JVM和JavaScript、Python、Lua或Ruby解释器。
* [Flix](https://github.com/flix/flix)：Flix是一种静态类型函数式、命令式和逻辑编程语言，由奥胡斯大学、滑铁卢大学开发。
* [Vale](https://github.com/ValeLang/Vale)：Vale是一种快速、安全且简单的编程语言。
* [Virgil](https://github.com/titzer/virgil)：Virgil是一种编程语言，旨在构建轻量级高性能系统，由CMU开源。
* [Eclipse Golo](https://github.com/eclipse-archived/golo-lang)：Golo是一种用于JVM的简单动态弱类型语言，由法国CITI实验室开源。
* [JPHP](https://github.com/jphp-group/jphp)：JPHP是使用JVM的PHP的新实现，支持PHP语言(7.1+)的许多功能。
* [JGO](https://github.com/thomasmodeneis/jgo)：Golang的Java编译器和运行时环境。
* [LuaJ](https://github.com/luaj/luaj)：为JME和JSE编写的轻量级、快速、以Java为中心的Lua解释器。
* [Enkel](https://github.com/JakubDziworski/Enkel-JVM-language)：Enkel是一种运行在JVM上的简单编程语言。
* [Yeti](https://github.com/mth/yeti)：Yeti是ML风格的函数式编程语言，在JVM上运行。
* [Wyvern](https://github.com/wyvernlang/wyvern)：Wyvern是一种新型通用编程语言，旨在支持适应性和可靠性，由CMU开源。
* [Genesis](https://github.com/elonlit/Genesis)：Genesis是一种解释性、过程性和图灵完备的古希伯来编程语言。
* [AgentLang](https://github.com/agentlang-ai/agentlang)：AgentLang是一种开源编程语言和框架，用于在人工智能代理的帮助下解决复杂的任务，由Fractl开源。
* [Concurnas](https://github.com/Concurnas/Concurnas)：Concurnas是一种开源JVM编程语言，旨在构建可靠、可扩展、高性能的并发、分布式和并行系统。
* [Ioke](https://github.com/olabini/ioke)：Ioke是一种强类型、动态、基于原型的编程语言。
* [Fantom](https://github.com/fantom-lang/fantom)：Fantom是一种在JVM和现代Web浏览器上运行的可移植语言。
* [Eclipse Ceylon](https://github.com/eclipse-archived/ceylon)：Ceylon是一种用于Java和JavaScript虚拟机的现代、模块化、静态类型编程语言，由RedHat创建。
* [Frege](https://github.com/Frege/frege)：Frege是JVM的Haskell，它将纯函数式编程引入了Java平台。
* [Renjin](https://github.com/bedatadriven/renjin)：Renjin是基于JVM的R语言解释器。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种针对集成进行了优化的开源云原生编程语言，它由WSO2开发和支持。
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
* [KamilaLisp](https://github.com/iczelia/kamilalisp)：一个功能强大、灵活简洁的Lisp语言，其灵感源自Haskell、APL等语言。
* [Hydra](https://github.com/CategoricalData/hydra)：Hydra是一种基于LambdaGraph数据模型的独特函数式编程语言。
* [Bosatsu](https://github.com/johnynek/bosatsu)：Bosatsu是一种简单、非图灵完备的语言，专为配置、查询和脚本编写而设计。
* [Idris JVM](https://github.com/mmhelloworld/idris-jvm)：Idris 2是一种纯函数式编程语言，该项目提供针对JVM字节码的Idris 2编译器，以便Idris 2程序可以在JVM上运行。
* [Redline Smalltalk](https://github.com/redline-smalltalk/redline-smalltalk)：Redline Smalltalk是JVM上的Smalltalk。
* [Fuzion](https://github.com/tokiwa-software/fuzion)：Fuzion是一种注重简单性、安全性和正确性的语言。
* [Snow](https://gitee.com/jcnc-org/snow)：Snow是一门面向AI时代的新型编程语言，灵感源自大模型的发展趋势。
* [Ixion](https://github.com/IxionLang/ixion-jvm)：适用于JVM平台的多范式编译型编程语言。

## 云原生

* [Linkerd](https://github.com/linkerd/linkerd)：Linkerd是一个提供弹性云端原生应用服务网格的开源项目，也是面向微服务的开源RPC代理。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种针对集成进行了优化的开源云原生编程语言，它由WSO2开发和支持。
* [Buildpacks](https://buildpacks.io)：Buildpacks可以将应用程序源代码转换为可以在任何云上运行的镜像。
* [Envoy Control](https://github.com/allegro/envoy-control)：Envoy Control是一个用于Service Mesh的生产就绪控制平面，基于与平台无关的Envoy Proxy数据平面，由Allegro开源。
* [Java Control Plane](https://github.com/envoyproxy/java-control-plane)：Envoy gRPC控制平面的Java实现。
* [JEAF](https://anaptecs.atlassian.net/wiki/spaces/JEAF/overview)：JEAF是一组框架、库和工具，支持开发基于Java的轻量级云原生企业应用程序。

## Serverless

* [Apache OpenWhisk](https://github.com/apache/openwhisk)：OpenWhisk是一个用于构建云应用程序的Serverless函数平台，由IBM开源。
* [Apache EventMesh](https://github.com/apache/eventmesh)：EventMesh是新一代Serverless事件中间件，用于构建分布式事件驱动应用程序，由微众银行开源。
* [Kotless](https://github.com/JetBrains/kotless)：Kotlin Serverless框架，由JetBrains开源。
* [Koupleless](https://github.com/koupleless/koupleless)：Koupleless是一种模块化的Serverless技术解决方案，它能让普通应用以比较低的代价演进为Serverless研发模式，由蚂蚁开源。
* [Apiary](https://github.com/DBOS-project/apiary)：Apiary是一个事务性功能即服务(FaaS)框架，用于构建面向数据库的应用程序，例如微服务和Web服务后端，这是MIT、斯坦福合作的一个研究项目。
* [Powertools Lambda Java](https://github.com/aws-powertools/powertools-lambda-java)：Powertools是一个开发工具包，用于实现Serverless最佳实践并提高开发人员速度。
* [Google App Engine](https://github.com/GoogleCloudPlatform/appengine-java-standard)：Google App Engine标准Java运行时：Prod运行时、本地devappserver、Cloud SDK Java组件、GAE API和GAE API模拟器。
* [Serverless Java Container](https://github.com/awslabs/aws-serverless-java-container)：Serverless Java Container让你可以在AWS Lambda中轻松运行使用Spring、Spring Boot、Struts、Jersey或Spark等框架编写的Java应用程序。
* [AWS Lambda Java Libraries](https://github.com/aws/aws-lambda-java-libs)：在AWS Lambda平台上运行Java的关键库。
* [Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function)：Spring Cloud Function是Pivotal开发的Spring项目，它致力于促进函数作为主要的开发单元。
* [Jerverless](https://github.com/jerverless/jerverless)：Jerverless是一个Serverless运行器，它将以Serverless函数的形式执行任何内容(二进制文件、命令或脚本)。
* [Pulumi AWS](https://github.com/pulumi/pulumi-aws)：Pulumi的AWS资源提供商允许你在云程序中使用AWS资源。
* [Open Runtimes](https://github.com/open-runtimes/open-runtimes)：适用于多种编程语言的Serverless云计算运行时环境，旨在为在容器化系统中编写云函数创建一致且可预测的开放标准。
* [Flink Stateful Functions](https://github.com/apache/flink-statefun)：Stateful Functions是一个API，它通过为Serverless架构构建的运行时来简化分布式有状态应用程序的构建。
* [Funktion](https://github.com/funktionio/funktion-connectors)：Funktion是一个基于Kubernetes的开源事件驱动的Lambda风格编程模型。
* [Cloudstate](https://github.com/cloudstateio/cloudstate)：Cloudstate是一个开源协议和参考实现，探索有状态无服务器的想法，最初由Lightbend开发。
* [Functions Framework Java](https://github.com/GoogleCloudPlatform/functions-framework-java)：用于编写可移植Java函数的开源FaaS框架，由Google Cloud Functions团队提供。
* [SwimOS](https://github.com/graphform/swim)：SwimOS是一个全栈应用程序平台，用于构建有状态的Web服务、流API和实时UI。
* [FDK Java](https://github.com/fnproject/fdk-java)：Fn项目是一个开源的容器原生Serverless平台，你可以在任何云或本地运行，由Oracle开发。

## APM

* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为开源。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [Dynatrace](https://www.dynatrace.com/)：Dynatrace是一个由Dynatrace公司开发的全栈智能可观测性与AIOps平台，广泛用于对云原生、微服务架构、传统应用、基础设施等进行监控、分析、自动化和优化。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为美团点评提供了全面的实时监控告警服务。
* [SPM](https://sematext.com/spm/)：SPM是一款全栈可观察性工具。
* [凤晴](http://www.uml.org.cn/wfw/202108185.asp)：凤睛是百度商业业务系统的APM，它侧重于对Java应用的监控，基本接入了百度绝大部分Java应用。
* [PFinder](https://developer.jdcloud.com/article/3821)：PFinder是京东UMP团队打造的新一代APM系统，集调用链追踪、应用拓扑、多维监控于一身。
* [OCI APM](https://www.oracle.com/manageability/application-performance-monitoring)：OCI APM是Oracle提供的应用程序性能分析和可观测性解决方案。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Matrix](https://github.com/Tencent/matrix)：Matrix是腾讯微信中使用的APM，用于监控、定位和分析性能问题。
* [SkyEye](https://github.com/JThink/SkyEye)：SkyEye是对Java、Scala等运行于JVM的程序进行实时日志采集、索引和可视化，对系统进行进程级别的监控的工具。
* [Hawkular](https://github.com/hawkular/hawkular-apm)：Hawkular是RedHat开源的应用程序性能管理解决方案。
* [Wavefront](https://docs.wavefront.com/)：Wavefront是一个高性能流分析平台，支持指标、计数器、直方图和跟踪/跨度的可观察性，由VMware维护。
* [Sentry Java](https://github.com/getsentry/sentry-java)：适用于Java、Android和其他JVM语言的Sentry SDK。
* [Hertzbeat](https://github.com/dromara/hertzbeat)：HertzBeat是一个开源的实时监控系统，具有自定义监控、高性能集群、Prometheus兼容和无代理功能，由dromara社区开源。
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM)：ArgusAPM是360开源的线上移动性能检测平台。
* [AndroidGodEye](https://github.com/Kyson/AndroidGodEye)：AndroidGodEye是一款Android性能监控工具(不仅限于性能数据)，你可以在电脑浏览器中轻松实时监控应用程序的性能。
* [Hypertrace](https://github.com/hypertrace/hypertrace)：Hypertrace是一个基于云原生分布式跟踪的可观测性平台，可让你了解开发和生产分布式系统，由Traceable开发。
* [Scouter](https://github.com/scouter-project/scouter)：SCOUTER是一个开源APM，类似于New Relic和AppDynamics，由LG开源。
* [MyPerf4J](https://github.com/LinShunKang/MyPerf4J)：MyPerf4J是一个针对高并发、低延迟应用设计的高性能Java性能监控和统计工具。
* [AppDynamics](https://www.appdynamics.com/)：AppDynamics是一款APM性能监控软件，可用于监控和管理服务器、虚拟机、数据库等运行情况，由Cisco提供。
* [Elastic APM](https://github.com/elastic/apm-agent-java)：Elastic APM Java代理。
* [FusionReactor](https://fusion-reactor.com/)：FusionReactor是一个具有AI增强功能的可观察性平台，可为开发人员、DevOps和支持团队提供前所未有的生产环境洞察，这是Intergral公司商业产品。
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor)：Stagemonitor是用于Java服务器应用程序性能监控的开源解决方案。
* [New Relic](https://newrelic.com/)：New Relic是一个很强大的服务器性能监控工具。
* [Glowroot](https://github.com/glowroot/glowroot)：Glowroot是一个易于使用，开销极低的Java APM。
* [Fiery](https://github.com/weiboad/fiery)：Fiery是用于PHP的APM工具，由微博开源。
* [OzHera](https://github.com/XiaoMi/ozhera)：OzHera是云原生时代的应用可观察平台，由小米中国区研发效率团队开源。
* [EasyAgent](https://github.com/megaease/easeagent)：EasyAgent是一个轻量级开放的云原生Java Agent及APM系统，MegaEase开源。
* [inspectIT](https://github.com/inspectIT/inspectIT)：ispectIT是领先的开源APM工具，用于监视和分析Java(EE)软件应用程序。
* [Lightrun](https://lightrun.com/)：Lightrun是一个面向开发人员的可观察性工具。
* [Kieker](https://github.com/kieker-monitoring/kieker)：Kieker提供动态分析功能，即监控和分析软件系统的运行时行为，从而实现应用程序性能监控和架构发现，由斯图加特大学和基尔大学开源。
* [BeeAPM](https://github.com/hao117/bee-apm)：BeeAPM是一个分布式跟踪和应用性能监控系统。
* [Digma](https://github.com/digma-ai/digma)：Digma是一个持续反馈平台，使可观察性与开发相关。
* [UAVStack](https://github.com/uavorg/uavstack)：UAVStack是智能化服务技术栈，是研发运维一体化的解决方案。

## 分布式跟踪

* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-java)：OpenTelemetry是一个与供应商无关的开源可观察性框架。
* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为开源。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [MTrace](https://tech.meituan.com/2016/10/14/mt-mtrace.html)：MTrace是美团内部的分布式会话跟踪系统，参考了Twitter的Zipkin以及阿里的鹰眼实现。
* [LTrace](https://www.infoq.cn/article/mcadu5wixiviyyx6uetj)：LTrace由链家开发，为链家提供分布式调用链追踪能力。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Watchman](https://www.infoq.cn/article/weibo-watchman/)：Watchman是微博的链路追踪及服务质量保障系统。
* [EagleEye](https://www.infoq.cn/article/jgzbemozgmbsukewff6j)：鹰眼是Google的分布式调用跟踪系统Dapper在淘宝的Java实现。
* [SOFATracer](https://github.com/sofastack/sofa-tracer)：SOFATracer是一个用于分布式系统调用跟踪的组件，由蚂蚁开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为大众点评提供了全面的实时监控告警服务。
* [Hiro](https://www.infoq.cn/article/suning-call-chain-monitoring-system-escort-818)：Hiro是苏宁易购开发的分布式跟踪系统。
* [Brave](https://github.com/openzipkin/brave)：Brave是一个分布式跟踪仪器库。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Haystack](https://github.com/ExpediaDotCom/haystack)：Haystack是一个由Expedia支持的开源分布式跟踪项目，旨在促进微服务和网站中问题的检测和修复。
* [Telemetry](https://github.com/yammer/telemetry)：Telemetry是由Yammer开源的受Dapper启发的分布式跟踪系统。
* [SQLCommenter](https://github.com/google/sqlcommenter)：SQLCommenter是一套中间件/插件，使你的ORM能够在执行之前扩充SQL语句，并使用包含有关导致其执行的代码的信息的注释，由Google开源。
* [Apache HTrace](https://github.com/apache/incubator-retired-htrace)：HTrace是一个用于分布式系统的跟踪框架，由Cloudera开源。
* [Spring Cloud Sleuth](https://github.com/spring-cloud/spring-cloud-sleuth)：Spring Cloud Sleuth为分布式跟踪提供Spring Boot自动配置。
* [ApplicationInsights](https://github.com/microsoft/ApplicationInsights-Java)：ApplicationInsights是Java的应用程序洞察工具，由Microsoft开源。
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
* [Tracing Java](https://github.com/palantir/tracing-java)：提供类似Zipkin跟踪功能的Java库，由Palantir开源。

## 指标库

* [Dropwizard Metrics](https://github.com/dropwizard/metrics)：Metrics提供了强大的工具包，可用于测量生产环境中关键组件的行为，由Yammer开源。
* [Prometheus Java](https://github.com/prometheus/client_java)：适用于JVM应用程序的Prometheus检测库。
* [OpenTelemetry Java Instrumentation](https://github.com/open-telemetry/opentelemetry-java-instrumentation)：该项目提供了一个Java代理JAR，可以附加到任何Java 8+应用程序，并动态注入字节码以从许多流行的库和框架捕获遥测数据。
* [Servo](https://github.com/Netflix/servo)：Servo提供了一个简单的接口，用于在Java中公开和发布应用程序指标，由Netflix开源。
* [Micrometer](https://github.com/micrometer-metrics/micrometer)：Micrometer为最流行的可观察性系统提供了一个门面，允许你在不锁定供应商的情况下检测基于JVM的应用程序代码，由VMware开源。
* [Oculus](https://github.com/etsy/oculus)：Oculus是Etsy Kale系统的异常关联组件。
* [CloudWatch Exporter](https://github.com/prometheus/cloudwatch_exporter)：适用于Amazon CloudWatch的Prometheus导出器。
* [Java Metrics](https://github.com/runtimetools/javametrics)：Java Metrics为Java运行时提供性能监控工具，通过其内置仪表板直观地提供监控数据，由IBM开源。
* [Metrics Spring](https://github.com/ryantenney/metrics-spring)：Metrics Spring将Dropwizard Metrics库与Spring集成，并提供XML和Java配置。
* [Spectator](https://github.com/Netflix/spectator)：用于记录维度时间序列的检测代码的简单库，由Netflix开源。
* [Alibaba Metrics](https://github.com/alibaba/metrics)：Alibaba Metrics是阿里内部广泛使用的度量埋点基础类库。
* [FFWD](https://github.com/spotify/ffwd)：FFWD是一种灵活的度量转发代理，旨在在系统本地运行并通过各种协议接收指标，然后将它们转发到TSDB，由Spotify开源。
* [Argus](https://github.com/salesforce/Argus)：Argus是一个时序监控和警报平台，它由离散服务组成，用于配置警报、摄取和转换指标和事件、发送通知、创建命名空间以及建立和实施策略和使用配额，由Salesforce开源。
* [Pollianna](https://github.com/apple/pollianna)：Pollianna是一个Java库和Java命令行代理，它通过用户确定的轮询区间累积JVM指标，并通过JMX进行公开，因此它们可以被Java和非Java遥测数据汇共享，由Apple开源。
* [SOFALookout](https://github.com/sofastack/sofa-lookout)：SOFALookout是一个利用多维度的Metrics对目标系统进行度量和监控的项目，由蚂蚁开源。
* [Ultrabrew Metrics](https://github.com/ultrabrew/metrics)：Ultrabrew Metrics是一个高性能的仪表库，专为大规模JVM应用而设计。
* [Blueflood](https://github.com/rax-maas/blueflood)：Blueflood是一个多租户、分布式度量处理系统，能够大规模地摄取、汇总和提供指标，由Rackspace开源。
* [PerfMon](https://github.com/undera/perfmon-agent)：用于访问远程计算机上的系统指标的代理应用程序。
* [Metriql](https://github.com/metriql/metriql)：Metriql是一个开源指标存储，允许公司将其指标定义为代码并轻松地在其BI和数据工具之间共享它们。
* [Pepper Metrics](https://github.com/zrbcool/pepper-metrics)：Pepper Metrics基于RED理论，即对每个服务进行RED指标收集，并持久化到数据库，并通过Dashboard进行展示，辅助进行性能趋势分析，由酷划在线开发。
* [Hawkular Metrics](https://github.com/hawkular/hawkular-metrics)：Hawkular Metrics是Hawkular社区的度量数据存储引擎部分。
* [Tritium](https://github.com/palantir/tritium)：Tritium是一个用于检测应用程序的库，以在运行时提供更好的可观察性，Palantir开源。
* [Jmxtrans](https://github.com/jmxtrans/jmxtrans)：Jmxtrans是一个工具，允许你连接到任意数量的JVM并查询它们的属性，而无需编写任何Java代码。
* [MetricsHub](https://github.com/MetricsHub/metricshub-community)：MetricsHub是OpenTelemetry的通用指标收集解决方案。
* [Java StatsD Client](https://github.com/tim-group/java-statsd-client)：用Java实现的StatsD客户端库。
* [Java DogStatsD Client](https://github.com/DataDog/java-dogstatsd-client)：用Java实现的DogStatsD客户端库，由DataDog开源。
* [Kafka StatsD Metrics](https://github.com/airbnb/kafka-statsd-metrics2)：将Kafka指标发送到StatsD，由Airbnb开源。

## API网关

* [Zuul](https://github.com/Netflix/zuul)：Zuul是一种网关服务，提供动态路由、监控、弹性、安全性等，由Netflix开源。
* [Apache ShenYu](https://github.com/apache/shenyu)：ShenYu是一个Java原生API网关，用于服务代理、协议转换和API治理，由dromara社区开源。
* [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)：Spring Cloud Gateway旨在提供一种简单而有效的方法来路由到API并为其提供横切关注点，由Pivotal开源。
* [FizzGate](https://github.com/fizzgate/fizz-gateway-node)：FizzGate是一个基于Java开发的微服务聚合网关，由正元信息开源。
* [Gateleen](https://github.com/swisspost/gateleen)：Gateleen是一个用于构建API网关的RESTful中间件工具包，瑞士邮政开源。
* [VX API Gateway](https://gitee.com/mirren/VX-API-Gateway)：VX API Gateway是基于Vert.x开发的一个全异步、高性能、可扩展、轻量级的API网关。
* [SIA Gateway](https://github.com/siaorg/sia-gateway)：SIA Gateway是基于Spring Cloud微服务生态体系下开发的一个分布式微服务网关系统，宜信开源。
* [Gravitee](https://github.com/gravitee-io/gravitee-api-management)：Gravitee是一个灵活且快速的开源API网关。
* [Zilla](https://github.com/aklivity/zilla)：Zilla是一个轻量级但功能丰富的代理，对HTTP、SSE、gRPC、MQTT和Kafka协议提供一流的支持。
* [Choreo Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、以开发人员为中心的API网关代理，由WSO2开源。
* [Heimdall](https://github.com/getheimdall/heimdall)：Heimdall是由Conductor Tecnologia SA开发的开源项目，旨在提供API编排解决方案。
* [DigiRunner](https://github.com/TPIsoftwareOSPO/digiRunner-Open-Source)：DigiRunner是一个应用层API网关，可充当微服务架构中客户端与后端服务之间通信的中央枢纽。
* [WAF](https://github.com/chengdedeng/waf)：WAF是使用Java开发的API Gateway，底层使用Netty。
* [Membrane](https://github.com/membrane/api-gateway)：Membrane是用Java编写的REST、OpenAPI、GraphQL和SOAP的API网关，由Predic8公司开源。
* [API Premium Gateway](https://github.com/Feynix2004/API-Premium-Gateway)：API Premium Gateway是一个轻量级的Java服务，旨在为你的分布式系统和应用提供强大的API高可用与智能调度能力。
* [Otoroshi](https://github.com/MAIF/otoroshi)：Otoroshi是一个轻量级API管理层，由MAIF团队开发，可以处理微服务之间的所有调用。
* [Okapi](https://github.com/folio-org/okapi)：Okapi是一个多租户API网关，由Open Library基金会开源。
* [CAPI](https://github.com/surisoft-io/capi)：由Apache Camel动态路由驱动的轻API网关/负载均衡器。
* [Janus](https://github.com/GrailStack/Janus)：Janus是Grail体系的一个组成模块，为各业务服务提供对外统一、高性能的HTTP网关。
* [Kaazing Gateway](https://github.com/kaazing/gateway)：Kaazing Gateway是一个网络网关，旨在为基于Web的实时协议提升提供单一接入点，支持负载均衡、集群和安全管理。
* [API ML](https://github.com/zowe/api-layer)：API ML为大型机服务REST API提供单一访问点，由IBM开源。
* [OWASP Application Gateway](https://github.com/The-OAG-Development-Project/Application-Gateway)：OWASP Application Gateway是一个HTTP反向代理，位于你的Web应用程序和客户端之间，负责处理Oauth2登录和会话管理。

## 服务发现

* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Eureka](https://github.com/Netflix/eureka)：Eureka是一项RESTful服务，主要用于AWS云中，用于中间层服务器的发现、负载均衡和故障转移，由Netflix开源。
* [Zookeeper](https://github.com/apache/zookeeper)：Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo开源。
* [Polaris Java](https://github.com/polarismesh/polaris-java)：腾讯Polaris注册中心Java SDK。
* [SOFARegistry](https://github.com/sofastack/sofa-registry)：SOFARegistry是蚂蚁金服开源的一个生产级、高时效、高可用的服务注册中心。
* [Pantheon](https://github.com/ProgrammerAnthony/Pantheon)：Pantheon是分布式微服务注册中心。
* [Artemis](https://github.com/ctripcorp/artemis)：Artemis是携程框架部门SOA服务注册表，包含服务自注册自发现、实例变更实时推送、服务分组路由功能。
* [Ranger](https://github.com/flipkart-incubator/ranger)：Ranger是一个基于Zookeeper构建的高级服务发现框架，由Flipkart开源。
* [Vert.x Service Discovery](https://github.com/vert-x3/vertx-service-discovery)：Vert.x Service Discovery提供发现基础设施来注册和发现微服务应用程序公开的服务。

## 容错组件

* [Neural](https://gitee.com/yu120/neural)：Neural是微服务架构中高并发和高可用的神经组织利刃，提供了分布式限流、降级、熔断、重试和隔离的容错特性。
* [Cohort](https://github.com/sksamuel/cohort)：Cohort是Ktor和Vertx的Spring Actuator风格的替代品。
* [SmallRye Fault Tolerance](https://github.com/smallrye/smallrye-fault-tolerance)：MicroProfile Fault Tolerance的SmallRye实现：隔离、断路器、回退、速率限制、重试、超时等。
* [Failover](https://github.com/societe-generale/failover)：Failover是用于管理外部引用服务故障转移的通用库，由法国兴业银行开源。
* [Discovery](https://github.com/Nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移。
* [BFT SMaRt](https://github.com/bft-smart/library)：BFT SMaRt是一个用Java开发的高性能拜占庭容错状态机复制库，以简单性和健壮性为首要要求，由里斯本大学开源。
* [ScalarDL](https://github.com/scalar-labs/scalardl)：ScalarDL是一种可扩展且实用的拜占庭故障检测中间件，适用于事务数据库系统，可实现正确性、可扩展性和数据库不可知性，由韩国Scalar公司维护。
* [MicroProfile Fault Tolerance](https://github.com/eclipse/microprofile-fault-tolerance)：MicroProfile中提供的容错组件。
* [PBScaler](https://github.com/WHU-AISE/PBScaler)：PBScaler是一个瓶颈感知自动扩展框架，旨在防止基于微服务的应用程序性能下降，由武汉大学开发。

#### 限流/降级

* [Sentinel](https://github.com/alibaba/Sentinel)：Sentinel是面向分布式、多语言异构化服务架构的流量治理组件，由阿里开源。
* [Hystrix](https://github.com/Netflix/Hystrix)：Hystrix是一个延迟和容错库，旨在隔离对远程系统、服务和第3方库的访问点，阻止级联故障，并在故障不可避免的复杂分布式系统中实现恢复能力，由Netflix开源。
* [Resilience4j](https://github.com/resilience4j/resilience4j)：Resilience4j是一个专为Java 8和函数式编程设计的容错库。
* [Bucket4j](https://github.com/bucket4j/bucket4j)：Bucket4j是一个Java限速库，主要基于令牌桶算法。
* [Failsafe](https://github.com/failsafe-lib/failsafe)：Failsafe是一个轻量级、零依赖库，用于处理Java 8+中的故障，具有用于处理日常用例的简洁API和处理其他所有内容的灵活性。
* [RateLimiter4j](https://github.com/wangzheng0822/ratelimiter4j)：RateLimiter4j是一个高度容错、低延迟、高性能的限流开发库/框架，提供了对HTTP接口的访问限流功能。
* [Concurrency Limits](https://github.com/Netflix/concurrency-limits)：Concurrency Limits实现并集成了从TCP拥塞控制到自动检测服务并发限制概念，可以以最佳延迟实现最佳吞吐量，由Netflix开源。
* [Amazon Route53 Infima](https://github.com/awslabs/route53-infima)：Amazon Route53 Infima是一个使用Amazon Route 53管理服务级故障隔离的库。
* [RateLimitJ](https://github.com/mokies/ratelimitj)：RateLimitJ是用于速率限制的Java库，提供可扩展的存储和应用程序框架适配器。
* [SDS](https://github.com/didi/sds)：SDS是一个基于Java开发的简单、易用、高性能的服务降级系统，支持限流、熔断和降级等功能，由滴滴开源。
* [Akali](https://gitee.com/dromara/Akali)：Akali是一个轻量级本地化热点检测/降级框架，适用于大流量场景，可轻松解决业务中超高流量的并发查询等场景，由dromara社区开源。
* [JRugged](https://github.com/Comcast/jrugged)：JRugged库实现了一些在Java中构建健壮、可用于生产环境的服务器代码所需的常用模式，由Comcast开源。
* [Spillway](https://github.com/coveooss/spillway)：Spillway可在公共API的软件级别添加分布式节流，由Coveo开源。
* [SnowJena](https://github.com/onblog/SnowJena)：SnowJena是基于令牌桶算法实现的分布式无锁限流框架，支持动态配置规则，支持可视化监控，开箱即用。
* [FastBreak](https://github.com/Nike-Inc/fastbreak)：FastBreak是一个简单的Java 8原生断路器，支持异步Future、阻塞和回调/手动模式，由Nike开源。
* [Duct Tape](https://github.com/rnorth/duct-tape)：Duct Tape是一个小型的Java 8库，提供对调用外部API的代码容错支持， 不可靠的组件，包括可能故障、超时或结果不一致的组件。
* [Token Bucket](https://github.com/bbeck/token-bucket)：该库提供了令牌桶算法的实现。
* [RateLimiter Spring Boot Starter](https://github.com/taptap/ratelimiter-spring-boot-starter)：基于Redis的偏业务应用的分布式限流组件，目前支持时间窗口、令牌桶两种限流算法，由Taptap开源。
* [Kanaloa](https://github.com/iheartradio/kanaloa)：Kanaloa是一个库，通过提供背压、断路器、负载均衡等功能来提高反向代理服务的弹性。
* [Distributed Rate Limiter](https://github.com/uppnrise/distributed-rate-limiter)：高性能、Redis支持的令牌桶速率限制器服务，带有REST API。

#### 重试

* [Easy Retry](https://github.com/alibaba/easy-retry)：Easy Retry是一种存储介质可扩展的持久化重试方案，由阿里开源。
* [Spring Retry](https://github.com/spring-projects/spring-retry)：Spring Retry提供了自动重新调用失败操作的能力。
* [Guava Retry](https://github.com/rholder/guava-retrying)：Guava Retry模块提供了一种通用方法，用于重试任意Java代码，具有特定的停止、重试和异常处理功能。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [Async Retry](https://github.com/nurkiewicz/async-retry)：Async Retry是用于Java 7/8的异步重试库。
* [Retry](https://github.com/softwaremill/retry)：由SoftwareMill开发的重试框架。
* [Retry4j](https://github.com/elennick/retry4j)：Retry4j是一个简单的Java库，可帮助重试瞬时故障情况或不可靠的代码。
* [Sisyphus](https://github.com/houbb/sisyphus)：Sisyphus是支持过程式编程和注解编程的Java重试框架。
* [Fast Retry](https://github.com/burukeYou/fast-retry)：Fast Retry是一个高性能任务重试框架，只需几个线程就可以支持到百万级别任务的并发重试处理。
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
* [Millau](https://github.com/codelev/millau)：Millau是一款免费的入口代理和负载均衡器，专为基于Docker Swarm构建的微服务架构而设计。
* [ModCluster](https://github.com/modcluster/mod_cluster)：ModCluster是一个基于Apache httpd和纯Java Undertow的智能原生负载均衡器。
* [Elastic Load Balancing](https://github.com/aws/elastic-load-balancing-tools)：ELB自动在Amazon EC2实例、容器或由IP地址标识的资源之间分配传入应用程序流量。
* [ExpressGateway](https://github.com/shieldblaze/ExpressGateway)：ShieldBlaze ExpressGateway是一种高性能、可扩展且高可用的负载均衡器。

#### 健康检查

* [Kardio](https://github.com/tmobile/kardio)：Kardio是一个简单的工具，可以配置为在任何端点上执行运行状况检查，由T-Mobile开源。
* [MicroProfile Health](https://github.com/microprofile/microprofile-health)：MicroProfile Health用于从另一台机器(即Kubernetes服务控制器)探测计算节点的状态。
* [SmallRye Health](https://github.com/smallrye/smallrye-health)：SmallRye Health是Eclipse MicroProfile Health的一个实现。
* [Health Check](https://github.com/Netflix/runtime-health)：HealthCheck公开一个REST端点，用于外部监控，由Netflix开源。
* [HeartBeat](https://gitee.com/mkk/HeartBeat)：心跳检测各类应用服务器(如Tomcat、Jetty)，Web服务器(如Apache、Nginx)的Java Web应用程序。

#### 混沌引擎

* [Simian Army](https://github.com/Netflix/SimianArmy)：Simian Army是一套工具，可让你的云保持最佳状态运行，由Netflix开源。
* [Mangle](https://github.com/vmware/mangle)：Mangle使你能够针对应用程序和基础设施组件无缝运行混沌工程实验，以评估弹性和容错能力，由VMware开源。
* [OpenChaos](https://github.com/openmessaging/openchaos)：OpenChaos为供应商提出了一个统一的API，为在云原生环境中执行混沌工程原理的各个方面提供解决方案，由阿里发起。
* [Chaos Monkey Spring Boot](https://github.com/codecentric/chaos-monkey-spring-boot)：该项目为Spring Boot应用程序提供了Chaos Monkey，并将尝试攻击你正在运行的Spring Boot应用程序。
* [Byte Monkey](https://github.com/mrwilson/byte-monkey)：Byte Monkey是一个小型Java库，用于测试JVM应用程序中的故障场景。
* [AWSSSMChaosRunner](https://github.com/amzn/awsssmchaosrunner)：AWSSSMChaosRunner是一个简化EC2和ECS的故障注入测试和混沌工程的库，由Amazon开源。
* [ChaosBlade Exec JVM](https://github.com/chaosblade-io/chaosblade-exec-jvm)：该项目是一个基于JVM-SandBox的ChaosBlade执行器，通过增强类来对Java应用程序进行混沌实验，阿里开源。
* [CloudRaider](https://github.com/intuit/CloudRaider)：CloudRaider是一个全新的测试框架，用于在AWS中执行“故障模式影响分析”(FMEA)测试，由Intuit开发。
* [Chaos Proxy](https://github.com/clusterfk/chaos-proxy)：Chaos Proxy是一款值得信赖的不可靠HTTP代理，专为微服务混沌测试而设计的轻量级工具。
* [Toxiproxy Java](https://github.com/trekawek/toxiproxy-java)：这是Toxiproxy的客户端库，Toxiproxy是一款模拟网络和系统状况的代理。
* [Cthulhu](https://github.com/xmatters/cthulhu-chaos-testing)：Cthulhu是一款混沌工程工具，用于评估微服务系统的弹性。
* [Chaos Engine](https://github.com/ThalesGroup/chaos-engine)：Chaos Engine是一款用于在云应用程序中创建随机混沌事件以测试弹性的应用程序，由Thales开源。
* [NetCrusher](https://github.com/NetCrusherOrg/netcrusher-java)：NetCrusher是Java的TCP/UDP代理框架和命令行工具，可以放置在任何客户端和服务器之间，并允许检查双方的故障转移。

#### 优雅停机

* [Spring Boot Graceful Shutdown](https://github.com/SchweizerischeBundesbahnen/springboot-graceful-shutdown)：Spring Boot Graceful Shutdown使你的Spring Boot应用程序能够在OpenShift上进行滚动部署，而无需任何停机，由瑞士联邦铁路开源。
* [Spring Boot Graceful Shutdown](https://github.com/timpeeters/spring-boot-graceful-shutdown)：该项目为Spring Boot添加了优雅关闭行为。
* [Spring Boot Graceful Shutdown](https://github.com/corentin59/spring-boot-graceful-shutdown)：该Starter公开了Spring Boot项目的端点以执行正常关闭。

## 大数据

这里列出了大数据领域相关Java框架、组件、工具。

#### 大数据框架

* [Apache Hadoop](https://github.com/apache/hadoop)：Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Hops](https://github.com/hopshadoop/hops)：Hops是Apache Hadoop的下一代发行版，具有可扩展、高可用和可定制的元数据。
* [Apache Spark](https://github.com/apache/spark)：Spark是一种多语言引擎，用于在单节点机器或集群上执行数据工程、数据科学和机器学习，由加州大学伯克利分校AMPLab开源。
* [Apache Pig](https://github.com/apache/pig)：Pig是一个用于处理非常大文件的数据流编程环境，由Yahoo开源。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：HBase是一个开源、分布式、版本化、面向列的存储，由Powerset开源。
* [Apache Wayang](https://github.com/apache/incubator-wayang)：Wayang是统一的数据处理框架，可无缝集成和编排多个数据平台，以提供无与伦比的性能和灵活性，由柏林工业大学开源。
* [Apache Nifi](https://github.com/apache/nifi)：NiFi是一个易于使用、功能强大且可靠的系统，用于处理和分发数据，由美国国家安全局开源。
* [Apache Linkis](https://github.com/apache/linkis)：Linkis是一种计算中间件，充当上层应用程序和底层引擎(例如Spark、Hive和Flink)之间的层，由微众开源。
* [Apache Drill](https://github.com/apache/drill)：Drill是一个分布式MPP查询层，支持针对NoSQL和Hadoop数据存储系统的SQL和替代查询语言，由LinkedIn、思科、威斯康星大学麦迪逊分校等开源。
* [Apache Mnemonic](https://github.com/apache/mnemonic)：Mnemonic是一个面向非易失性混合内存存储的库，由Intel开源。
* [Apache Kyuubi](https://github.com/apache/kyuubi)：Kyuubi是一个分布式多租户网关，用于在数据仓库和Lakehouse上提供Serverless SQL，由网易数帆开源。
* [Snowplow](https://github.com/snowplow/snowplow)：Snowplow是一个开发者优先的收集行为数据的引擎。
* [Piflow](https://github.com/cas-bigdatalab/piflow)：Piflow是一个易于使用、功能强大的大数据管道系统，由科学大数据社区开源。
* [Scio](https://github.com/spotify/scio)：Scio是一个适用于Beam和Google Cloud Dataflow的Scala API，由Spotify开源。
* [Batch Processing Gateway](https://github.com/apple/batch-processing-gateway)：批处理网关使在Kubernetes上运行Spark服务变得容易，它允许用户通过直观的API调用在Kubernetes上提交、检查和删除Spark应用程序，由Apple开源。
* [Venice](https://github.com/linkedin/venice)：Venice是一个衍生的数据存储平台，由LinkedIn开源。
* [DataWave](https://github.com/NationalSecurityAgency/datawave)：DataWave是一个基于Java的摄取和查询框架，它利用Accumulo提供对数据的快速、安全访问，由美国国家安全局开源。
* [Fire](https://gitee.com/fire-framework/fire)：Fire框架是由中通大数据自主研发并开源、专门用于进行Spark和Flink任务开发的大数据框架。
* [SuperSQL](https://my.oschina.net/u/4956788/blog/5510918)：天穹SuperSQL是腾讯自研、基于统一SQL语言模型、面向机器学习智能调优、提供虚拟化数据和开放式计算引擎的大数据智能融合平台。
* [Apache OODT](https://github.com/apache/oodt)：OODT可以实现数据库链接、工作流处理以及硬件/文件管理等功能，由NASA的喷气机推力研究室开源。
* [Apache Sedona](https://github.com/apache/sedona)：Sedona是一种空间计算引擎，使开发人员能够在Apache Spark和Apache Flink等现代集群计算系统中轻松处理任何规模的空间数据，由亚利桑那州立大学开源。
* [Pipes](https://github.com/tinkerpop/pipes)：Pipes是一个数据流框架，可实现数据从输入到输出的拆分、合并、过滤和转换，由斯阿拉莫斯国家实验室开源。
* [Transport](https://github.com/linkedin/transport)：Transport是一个用于编写高性能用户定义函数(UDF)的框架，这些函数可跨各种引擎(包括Spark、Hive和Trino)进行移植，由LinkedIn开发。

#### 大数据工具

* [Apache Bigtop](https://github.com/apache/bigtop)：Bigtop旨在为基础设施工程师和数据科学家寻找领先的开源大数据组件的全面打包、测试和配置。
* [Yanagishima](https://github.com/yanagishima/yanagishima)：Yanagishima是Trino、Hive和Spark的开源Web应用程序。
* [Elephant Bird](https://github.com/twitter/elephant-bird)：Elephant Bird是Twitter的开源库，包含LZO、Thrift和/或Protocol Buffer相关的Hadoop InputFormats、OutputFormats、Writables、Pig LoadFuncs、Hive SerDe、HBase杂项等。
* [Spark RAPIDS](https://github.com/NVIDIA/spark-rapids)：Spark的RAPIDS加速器利用GPU通过RAPIDS库加速处理，由NVIDIA开源。
* [BigQuery Utils](https://github.com/GoogleCloudPlatform/bigquery-utils)：BigQuery是一个Serverless、高度可扩展且经济高效的云数据仓库，内置内存BI引擎和机器学习，该库提供有用的实用程序来帮助你迁移和使用BigQuery，由Google开发。
* [DataGenerator](https://github.com/FINRAOS/DataGenerator)：DataGenerator是一个用于系统地生成大量数据的Java库，美国金融业监管局开源。
* [CloudEon](https://github.com/dromara/CloudEon)：CloudEon使用Kubernetes安装和部署开源大数据组件，实现开源大数据平台的容器化运行，dromara社区开源。
* [Lipstick](https://github.com/Netflix/Lipstick)：Lipstick将Pig工作流程的图形描述与作业执行时的相关信息结合起来，由Netflix开源。
* [Apache Livy](https://github.com/apache/incubator-livy)：Livy是一个开源REST接口，用于从任何地方与Spark交互，由Cloudera开源。
* [UberScriptQuery](https://github.com/uber/uberscriptquery)：UberScriptQuery是一个用于运行Spark SQL作业的脚本查询包装器，由Uber开源。
* [Spark JobServer](https://github.com/spark-jobserver/spark-jobserver)：Spark-JobServer提供了一个RESTful接口，用于提交和管理Spark作业、jar和作业上下文。
* [HbaseGUI](https://github.com/Observe-secretly/HbaseGUI)：HbaseGUI可视化工具，通过Hbase Client直接操作Hbase。
* [Bigdata File Viewer](https://github.com/Eugene-Mark/bigdata-file-viewer)：跨平台桌面应用程序，用于查看常见的大数据二进制格式，如Parquet、ORC、Avro等。
* [Scaleph](https://github.com/flowerfine/scaleph)：Scaleph是一个基于Flink和Kubernetes打造的开放数据平台，具备Flink和SeaTunnel任务管理能力，同时支持Doris集群在Kubernetes上的运维部署。
* [LemonGrenade](https://github.com/NationalSecurityAgency/lemongrenade)：LemonGrenade被设计为一个自动化系统，能够将系统、数据源或功能智能地链接在一起，而无需最终用户手动指定链接，由美国国家安全局开源。
* [DataFu](https://github.com/apache/datafu)：DataFu是用于处理Hadoop中的大规模数据的库集合，由LinkedIn开源。

#### 大数据组件

* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio)：DataSphere Studio是微众银行开发的一站式数据应用开发管理门户。
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)：Elasticsearch实时搜索和分析与Hadoop原生集成，支持Map/Reduce、Hive和Spark。
* [Secor](https://github.com/pinterest/secor)：Secor是一项将Kafka日志持久保存到Amazon S3、Google Cloud Storage、Microsoft Azure Blob Storage和Openstack Swift的服务，由Pinterest开源。
* [Apache Knox](https://github.com/apache/knox)：Knox是一个应用程序网关，用于以安全的方式与一个或多个Hadoop集群的REST API和用户界面进行交互。
* [Eclipse Connector](https://github.com/eclipse-edc/Connector)：EDC核心服务包括数据平面和控制平面。
* [Teiid](https://github.com/teiid/teiid)：Teiid是一个数据虚拟化系统，允许应用程序使用来自多个异构数据存储的数据，由RedHat主导。
* [Apache Ranger](https://github.com/apache/ranger)：Ranger是一个用在Hadoop平台上并提供操作、监控、管理综合数据安全的框架，由Hortonworks开源。
* [MR4C](https://github.com/google/mr4c)：MR4C是一个允许你在Hadoop执行框架内运行本机代码的框架，由Google开源。
* [Apache Tajo](https://github.com/apache/tajo)：Tajo是Hadoop的开源分布式数据仓库框架，最初由韩国基础设施公司Gruter开发。
* [Hydra](https://github.com/addthis/hydra)：Hydra是最初由AddThis开发的分布式数据处理和存储系统。
* [Conquery](https://github.com/ingef/conquery)：Conquery是一个强大的基于Web的工具，用于针对大型事件类数据集编写和执行查询。
* [Tempura](https://github.com/alibaba/cost-based-incremental-optimizer)：Tempura是一种基于成本的增量数据处理通用优化框架，由阿里开发。
* [SSM](https://github.com/Intel-bigdata/SSM)：大数据智能存储管理，全面的冷热数据优化解决方案，由Intel开源。

#### 数据目录

* [DataHub](https://github.com/datahub-project/datahub)：DataHub是现代数据堆栈的开源元数据平台，由LinkedIn开源。
* [Metacat](https://github.com/Netflix/metacat)：Metacat是一个联合的元数据API服务，可以访问Hive、RDS、Teradata、Redshift、S3和Cassandra，由Netflix开源。
* [Apache Polaris](https://github.com/apache/polaris)：Polaris是Iceberg的开源、功能齐全的目录，由Snowflake开发。
* [Apache Atlas](https://github.com/apache/atlas)：Atlas是一组可扩展的核心基础治理服务-使企业能够有效地满足Hadoop内的合规性要求，并允许与整个企业数据生态系统集成，由Hortonworks开源。
* [OpenMetadata](https://github.com/open-metadata/OpenMetadata)：OpenMetadata是一个开源元数据存储库，由Uber元数据基础架构背后的团队构建。
* [Open Data Discovery](https://github.com/opendatadiscovery/odd-platform)：Open Data Discovery是一款面向数据团队的开源数据发现和可观察性工具，由Provectus开源。
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog)：Unity Catalog是最开放、可互操作的数据和AI目录，由Databricks开源。
* [Apache Gravitino](https://github.com/apache/gravitino)：Gravitino是一个高性能、地理分布式、联合元数据湖，由Datastrato开源。
* [Magda](https://github.com/magda-io/magda)：Magda是适用于所有大数据和小数据的联合开源数据目录，由澳大利亚联邦科学与工业研究组织的Data61和澳大利亚总理及内阁部发起。
* [Lightning Catalog](https://github.com/zetaris/lightning-catalog)：Lightning Catalog是Zetaris开源的数据目录，用于在临时分析、数据仓库、Lake House和ML项目中准备任意规模的数据。
* [DDF](https://github.com/codice/ddf)：DDF是一个免费的开源通用数据层，它从底层数据结构中抽象出服务和业务逻辑，以便快速集成新的数据源，由Codice基金会开源。

#### 数据治理

* [OpenLineage](https://github.com/OpenLineage/openlineage)：OpenLineage是元数据和沿袭收集的开放标准，旨在在作业运行时对其进行检测。
* [Spline](https://github.com/AbsaOSS/spline)：Spline是适用于Apache Spark等数据处理框架的开源数据沿袭跟踪解决方案，由南非联合银行集团开源。
* [Legend](https://github.com/finos/legend)：Legend是一个数据平台，它提供了一个通过API或自助查询访问数据的单一位置，并具有内置治理功能，由金融科技开源基金会FINOS开源。
* [Marquez](https://github.com/MarquezProject/marquez)：Marquez是一种开源元数据服务，用于数据生态系统元数据的收集、聚合和可视化，由WeWork开源。
* [Data Platform Open](https://github.com/shaiwz/data-platform-open)：可视化拖拽式大数据集成平台、大数据平台、大数据，包含数据流、数据源、数据对齐、查询模板、完善的监控等。
* [XL-LightHouse](https://github.com/xl-xueling/xl-lighthouse)：XL-LightHouse是一套支持超大数据量、支持超高并发的通用型流式大数据统计系统。
* [BigQuery Data Lineage](https://github.com/GoogleCloudPlatform/bigquery-data-lineage)：使用审核日志、ZetaSQL和Dataflow对BigQuery进行实时数据沿袭跟踪的参考实现，由Google开源。
* [Egeria](https://github.com/odpi/egeria)：Egeria提供开放元数据和治理类型系统、框架、API、事件有效负载和交换协议，由IBM开源。
* [Apache Griffin](https://github.com/apache/griffin)：Griffin是一个面向大数据的开源数据质量解决方案，支持批处理和流式处理模式，由eBay开源。
* [Cloudbreak](https://github.com/hortonworks/cloudbreak)：部署在云服务上的集成分析和数据管理平台，它提供广泛的数据分析和人工智能功能以及安全的用户访问和数据治理功能，由Hortonworks开源。
* [Herd](https://github.com/FINRAOS/herd)：Herd是云的大数据治理，Herd统一数据目录有助于将云中的存储与计算分开，由美国金融业监管局开源。
* [Ground](https://github.com/ground-context/ground)：Ground是加州大学伯克利分校RISE实验室开发的开源数据上下文服务。
* [Dataverse](https://github.com/IQSS/dataverse)：Dataverse是一个用于共享、查找、引用和保存研究数据的开源软件平台，由哈佛大学定量社会科学研究所开源。
* [Superglue](https://github.com/intuit/superglue)：Superglue是一种谱系追踪工具，可帮助直观地了解数据在复杂管道中的传播，由Intuit开发。
* [FlinkSQL Lineage](https://github.com/HamaWhiteGG/flink-sql-lineage)：FlinkSQL的血缘分析系统，支持Watermark、UDTF、CEP、Windowing TVF、CTAS等高级语法。
* [HelloDATA BE](https://github.com/kanton-bern/hellodata-be)：HelloDATA BE是一个基于现代数据堆栈的开源工具构建的企业数据平台。
* [Qualitis](https://github.com/WeBankFinTech/Qualitis)：Qualitis是一个数据质量管理平台，支持各种数据源的质量验证、通知和管理，用于解决数据处理过程中引起的各种数据质量问题，由微众开源。
* [Apache AsterixDB](https://github.com/apache/asterixdb)：AsterixDB是一个大数据管理系统，具有丰富的功能集，由加利福尼亚大学欧文分校的Michael Carey发起。
* [Apache Falcon](http://falcon.apache.org/)：Falcon是一个Feed处理和Feed管理系统，旨在让最终消费者更轻松地在Hadoop集群上进行Feed处理和管理。
* [Beekeeper](https://github.com/ExpediaGroup/beekeeper)：Beekeeper是一个安排删除孤立路径和过期元数据的服务，由Expedia开源。
* [Base DMS](https://github.com/basedt/dms)：Base DMS是一个开源、免费且由AI驱动的智能数据管理系统。

#### 查询引擎

* [Apache Hive](https://github.com/apache/hive)：Hive是一种分布式容错数据仓库系统，可实现大规模分析，并有助于使用SQL读取、写入和管理分布式存储中的PB级数据，由Facebook开源。
* [Trino](https://github.com/trinodb/trino)：Trino是一个用于大数据分析的快速分布式SQL查询引擎，由Starburst开源。
* [Presto](https://github.com/prestodb/presto)：Presto是一个用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Amazon Athena](https://aws.amazon.com/cn/athena/)：Athena是一种交互式查询服务，可让你方便地使用标准SQL直接分析Amazon S3中的数据。
* [Apache Phoenix](https://github.com/apache/phoenix)：Phoenix是基于HBase的SQL皮肤，作为客户端嵌入的JDBC驱动程序提供，旨在针对HBase数据的低延迟查询，由Salesforce开源。
* [XSQL](https://github.com/Qihoo360/XSQL)：XSQL是一个多数据源查询引擎，设计简单易用，运行稳定，由360开源。
* [Blaze](https://github.com/kwai/blaze)：Blaze加速器利用本机矢量化执行来加速查询处理，由快手开源。
* [Coral](https://github.com/linkedin/coral)：Coral是一个SQL翻译、分析和重写引擎，由LinkedIn开源。
* [Gimel](https://github.com/paypal/gimel)：Gimel提供统一的数据API来访问来自任何存储的数据，由Paypal开源。
* [OpenHuFu](https://github.com/BUAA-BDA/OpenHuFu)：OpenHuFu是一个开源的数据联邦系统，支持多数据库协同查询，并具有安全保障，由清华大学开源。
* [OpenLooKeng](https://github.com/openlookeng/hetu-core)：OpenLooKeng是一个嵌入式引擎，可以对任何地方的任何数据进行现场分析，包括地理上远程的数据源，由华为开源。
* [TrainDB](https://github.com/traindb-project/traindb)：TrainDB是一个基于ML的近似查询处理引擎，旨在在几秒钟内回答耗时的分析查询，由延世大学、光云大学、ETRI、RealTimeTech、BI Matrix开源。
* [Quicksql](https://github.com/Qihoo360/Quicksql)：Quicksql是一款SQL查询产品，可用于特定数据存储查询或多个数据存储关联查询，由360开源。
* [RumbleDB](https://github.com/RumbleDB/rumble)：RumbleDB是一个查询引擎，可让你轻松高效地查询大型、混乱的数据集，由苏黎世联邦理工学院开源。
* [SquashQL](https://github.com/squashql/squashql)：SquashQL是一个开源SQL查询引擎，旨在简化构建多维查询的过程。
* [Luwak](https://github.com/flaxsearch/luwak)：Luwak基于开源Lucene搜索库，是一个高性能的存储查询引擎。
* [Squall](https://github.com/epfldata/squall)：Squall是一个构建在Storm之上的在线查询处理引擎，由洛桑联邦理工学院数据实验室开源。
* [Splice Machine](https://github.com/splicemachine/spliceengine)：Splice Machine是一个融合关系型数据库与大数据分析的平台，支持事务处理和分析查询。
* [Velox4J](https://github.com/velox4j/velox4j)：Velox是一个全新的C++矢量化数据库加速库，旨在优化查询引擎和数据处理系统，这是Velox的Java绑定。
* [Marble](https://github.com/51nb/marble)：Marble是一个基于Apache Calcite的高性能内存Hive SQL引擎，由51信用卡开源。
* [Myria](https://github.com/uwescience/myria)：Myria是华盛顿大学的分布式、无共享大数据管理系统和云服务。
* [DataCompare](https://gitee.com/dromara/data-compare)：DataCompare是一个大数据数据比对和数据探测平台，由dromara社区开源。
* [Quark](https://github.com/qubole/quark)：Quark是一个基于分析数据库的数据虚拟化引擎。

#### 存储格式

* [Apache CarbonData](https://github.com/apache/carbondata)：CarbonData是一种索引列式数据存储解决方案，用于在大数据平台上进行快速分析，例如Hadoop、Spark等，由华为开源。
* [Apache ORC](https://github.com/apache/orc)：ORC是一种自描述、类型感知的列式文件格式，专为Hadoop工作负载而设计，由Hortonworks和Facebook联合开发。
* [Arrow Java](https://github.com/apache/arrow-java)：Arrow是一种通用的列式格式和多语言工具箱，用于快速数据交换和内存分析。
* [Apache Parquet](https://github.com/apache/parquet-java)：Parquet是Hadoop生态系统中的任何项目都可以使用的列式存储格式，由Twitter和Cloudera共同开源。
* [Yosegi](https://github.com/yahoojapan/yosegi)：Yosegi是一种无模式的列式存储格式，提供像JSON一样灵活的表示和类似其他列式存储格式的高效读取，由Yahoo开源。
* [GraphAr](https://github.com/apache/incubator-graphar)：GraphAr是一个用于图数据存储和检索的开源标准数据文件格式，由阿里开源。
* [Apache TsFile](https://github.com/apache/tsfile)：TsFile是一种专为时序数据设计的列式存储文件格式，支持高效压缩、读写高吞吐，并且兼容Spark、Flink等多种框架，由清华大学开源。
* [IndexR](https://github.com/shunfei/indexr)：IndexR是HDFS上的超快速列式数据格式，专注于快速分析，既适用于海量静态(历史)数据，也适用于快速摄取实时数据，由舜飞开源。
* [TrinityLake](https://github.com/trinitylake-io/trinitylake)：TrinityLake格式定义了Lakehouse中的对象，并提供了一种一致且高效的方式来访问和操作这些对象。

#### 存储系统

* [Apache Bookkeeper](https://github.com/apache/bookkeeper)：BookKeeper是一种可扩展、容错和低延迟的存储服务，针对仅附加工作负载进行了优化，由雅虎研究院开发。
* [Apache Ozone](https://github.com/apache/ozone)：Ozone是适用于Hadoop和云原生环境的可扩展、冗余和分布式对象存储，由腾讯大数据团队开源。
* [TAPIR](https://github.com/UWSysLab/tapir)：TAPIR是一种用于线性化分布式事务的新协议，使用复制构建，没有一致性保证，由华盛顿大学CSE系统实验室开源。
* [Pocket](https://github.com/stanford-mast/pocket)：Pocket是一个专为临时数据共享而设计的存储系统，由斯坦福大学开源。
* [Apache Crail](https://github.com/apache/incubator-crail)：Apache Crail是一个快速的多层分布式存储系统，专为高性能网络和存储硬件而设计，由IBM开源。
* [DCache](https://github.com/dCache/dcache)：DCache是一个用于存储和检索分布在大量异构服务器节点中数据的系统，由德国电子同步加速器研究所、欧洲核子研究中心等机构开源。

#### 流处理平台

* [Apache Flink](https://github.com/apache/flink)：Flink是一个开源流处理框架，具有强大的流处理和批处理能力，由柏林工业大学发起。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：RocketMQ是一个分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：Kafka是一个开源分布式事件流平台，已被数千家公司用于高性能数据管道、流分析、数据集成和关键任务应用程序，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：Pulsar是一个分布式Pub-Sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API，由Yahoo开源。
* [Apache Storm](https://github.com/apache/storm)：Storm是一个免费开源的分布式实时计算系统，由Twitter开源。
* [Amazon Kinesis](https://github.com/awslabs/amazon-kinesis-client)：Amazon Kinesis是AWS提供的一系列服务，用于大规模处理和分析实时流数据。
* [Mantis](https://github.com/Netflix/mantis)：Mantis是一个用于构建流处理应用程序(作业)的平台，Netflix开源。
* [Apache Beam](https://github.com/apache/beam)：Beam是一个用于定义批处理和流数据并行处理管道的统一模型，由Google开源。
* [Hazelcast](https://github.com/hazelcast/hazelcast)：Hazelcast是一个实时流处理平台，可让你构建立即对数据采取操作的应用程序，由Hazelcast开源。
* [JStorm](https://github.com/alibaba/jstorm)：JStorm是参考Storm基于Java语言重写的实时流式计算系统框架，由阿里开源。
* [Onyx](https://github.com/onyx-platform/onyx)：Onyx是一个无主、云规模、容错、高性能分布式计算系统。
* [Dempsy](https://github.com/Dempsy/dempsy)：Dempsy是一个用于轻松编写分布式、动态可扩展应用程序的框架，用于处理无限量的(近)实时消息流。
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
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [FlinkStreamSQL](https://github.com/DTStack/flinkStreamSQL)：FlinkStreamSQL基于Flink对其实时SQL进行扩展，主要实现了流与维表的join，支持原生Flink SQL所有的语法，由袋鼠云开源。
* [Apache Samza](https://github.com/apache/samza)：Samza是一个分布式流处理框架，它使用Kafka进行消息传递，并使用Hadoop YARN提供容错、处理器隔离、安全性和资源管理，由LinkedIn开源。
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
* [Table Computing](https://github.com/alibaba/table-computing)：Table Computing是一个分布式轻量级、高性能、低延迟的流式处理和数据分析框架，由阿里开发。
* [Dagger](https://github.com/raystack/dagger)：Dagger是一个易于使用、通过代码进行配置的云原生框架，构建在Flink之上，用于实时流数据的状态处理。
* [S4](https://github.com/s4/core)：S4是一个通用、分布式、可扩展、部分容错、可插拔的平台，它允许程序员轻松开发用于处理连续无界数据流的应用程序，由Yahoo开源。

#### ETL工具

* [Airbyte](https://github.com/airbytehq/airbyte)：Airbyte是领先的数据集成平台，适用于从API、数据库和文件到数据仓库、数据湖和数据湖屋的ETL/ELT数据管道。
* [Logstash](https://github.com/elastic/logstash)：Logstash是免费且开源的服务器端数据处理管道，能够从多个来源采集数据，转换数据，然后将数据发送到你最喜欢的仓库中，由Elastic开源。
* [Apache Hop](https://github.com/apache/hop)：Hop编排平台旨在促进数据和元数据编排的各个方面，也是Kettle的前身。
* [Apache SeaTunnel](https://github.com/apache/seatunnel)：SeaTunnel是新一代高性能分布式数据集成工具，能够每天同步海量数据，由中国通信学会开源技术委员会发起的项目。
* [BitSail](https://github.com/bytedance/bitsail)：BitSail是字节开源的基于分布式架构、高性能的数据集成引擎。
* [Addax](https://github.com/wgzhao/Addax)：Addax是一个可扩展的ETL工具，支持超过20种SQL/NoSQL数据源，是阿里巴巴DataX的分支和演进版本。
* [TIS](https://github.com/datavane/tis)：TIS集成大数据领域优秀组件(FlinkX-CDC，Chunjun，DataX，Flink等)为你提供一站式、开箱即用的DataOps数据中台，大幅提高ETL实时数仓构建效率，由Datavane大数据组织开源。
* [Suro](https://github.com/Netflix/suro)：Suro是一种数据管道服务，用于收集、聚合和调度大量应用程序事件(包括日志数据)，由Netflix开发。
* [Marmaray](https://github.com/uber/marmaray)：Marmaray是一个通用的Hadoop数据摄取和分散框架和库，由Uber开源。
* [Exchangis](https://github.com/WeBankFinTech/Exchangis)：Exchangis是微众银行大数据平台与社区用户共同开发的新版数据交换工具，支持异构数据源之间结构化和非结构化数据的同步传输。
* [Smooks](https://github.com/smooks/smooks)：Smooks是一个可扩展的Java框架，用于构建基于XML和非XML数据(CSV、EDI、POJO等)的基于片段的应用程序。
* [Apache InLong](https://github.com/apache/inlong)：InLong是一站式、全场景的海量数据集成框架，支持数据摄取、数据同步和数据订阅，提供自动、安全、可靠的数据传输能力，由腾讯大数据团队开源。
* [WInte.r](https://github.com/olehmberg/winter)：WInte.r框架提供了端到端数据集成的方法，由曼海姆大学开源。
* [Yunque](https://gitee.com/LarkMidTable/yunque)：云雀是一款数据集成工具，实现异构数据源的整合，帮助企业构建数据仓库、数据湖等应用架构。
* [Embulk](https://github.com/embulk/embulk)：Embulk是一个并行批量数据加载器，有助于在各种存储、数据库、NoSQL和云服务之间传输数据。
* [DeltaFi](https://gitlab.com/deltafi/deltafi)：DeltaFi是一个灵活、轻量代码的数据转换和标准化平台。
* [Kafka Connect File Pulse](https://github.com/streamthoughts/kafka-connect-file-pulse)：Connect FilePulse是一种多用途、可扩展且可靠的Kafka连接器，可以轻松解析、转换任何格式的任何文件并将其流式传输到Kafka，由StreamThoughts开源。
* [Extract](https://github.com/ICIJ/extract)：Extract是用于并行、分布式内容提取的跨平台命令行工具，由国际调查记者联盟开源。
* [Bender](https://github.com/Nextdoor/bender)：该项目提供了一个可扩展的Java框架，用于在AWS Lambda上创建Serverless ETL函数，Bender处理复杂的管道并提供为ETL过程的各个方面构建模块所需的接口。
* [Orbital](https://github.com/orbitalapi/orbital)：Orbital是一个数据网关，可自动集成、转换和发现整个企业中数据源(API、数据库、消息代理)的数据。
* [ETLCloud](https://www.etlcloud.cn/)：ETLCloud是一款基于微服务架构技术开发的先进数据集成解决方案。
* [LinkMove](https://github.com/nhl/link-move)：LinkMove是一个模型驱动的动态可配置框架，用于从外部源获取数据并将其保存在数据库中，由北美职业冰球联盟开源。
* [Lithium](https://www.atlassian.com/blog/atlassian-engineering/lithium)：Lithium是Atlassian内部使用的ETL平台，旨在满足动态数据移动的要求。
* [SETL](https://github.com/SETL-Framework/setl)：SETL是一个由Apache Spark提供支持的Scala ETL框架，可帮助你构建Spark ETL项目、模块化数据转换逻辑并加快开发速度。
* [Envelope](https://github.com/cloudera-labs/envelope)：Envelope是Apache Spark的配置驱动框架，可以轻松开发基于Spark的数据处理管道，由Cloudera开发。
* [QStreaming](https://github.com/qiniu/QStreaming)：QStreaming是一个简化在Apache Spark上编写和执行ETL的框架，由七牛云开发。
* [Hydrograph](https://github.com/BitwiseInc/Hydrograph)：Hydrograph是一款功能强大的ETL工具，允许开发人员使用简单的拖放界面创建复杂的图表。
* [DataExpress](https://github.com/chop-dbhi/dataexpress)：DataExpress是一个简单、基于Scala的跨数据库ETL工具包，支持Postgres、MySql、Oracle、SQLServer和SQLite，由费城儿童医院开源。
* [Data Prepper](https://github.com/opensearch-project/data-prepper)：Data Prepper是OpenSearch项目的一个组件，可以大规模接收、过滤、转换、丰富和路由数据，由AWS开源。
* [LinkedPipes ETL](https://github.com/linkedpipes/etl)：LinkedPipes ETL是一个基于RDF的轻量级ETL工具。
* [FHIR Data Pipes](https://github.com/google/fhir-data-pipes)：该仓库包括使用FHIR格式将来自FHIR服务器(例如HAPI、GCP FHIR存储，甚至OpenMRS)的数据转换为基于Parquet文件或其他FHIR服务器的数据仓库的管道，由Google开源。
* [Talend Open Studio](https://github.com/Talend/tcommon-studio-se)：Talend Open Studio可以使你立即开始构建基本数据管道，从你控制的本地安装的开源环境中执行简单的ETL和数据集成任务，获取数据的图形配置文件并管理文件。
* [Kettle](https://github.com/pentaho/pentaho-kettle)：Kettle是一款开源的ETL工具，可以用它来对数据进行抽取、清洗和转换操作，主作者是Matt Casters。
* [FineDataLink](https://www.finedatalink.com/)：FineDataLink是一款低代码/高时效的企业级一站式数据集成平台，这是帆软的商业产品。
* [Scriptella](https://github.com/scriptella/scriptella-etl)：Scriptella是一个用Java编写的开源ETL和脚本执行工具。
* [Apatar](https://www.altoros.com/blog/tag/apatar/)：Apatar是一个开源的数据抽取、转换、装载(ETL)项目。
* [Flowman](https://github.com/dimajix/flowman)：Flowman是一个由Spark支持的ETL框架，简化了复杂数据管道的开发。
* [WhiteRabbit](https://github.com/OHDSI/WhiteRabbit)：WhiteRabbit是一个小型应用程序，可用于分析数据库的结构和内容，为设计ETL做准备，由OHDSI开源。
* [DataPull](https://github.com/homeaway/datapull)：DataPull是一种自助式分布式ETL工具，用于连接和转换来自异构数据存储的数据。
* [Metorikku](https://github.com/YotpoLtd/metorikku)：Metorikku是一个简化在Apache Spark上编写和执行ETL的库。
* [Wrangler](https://github.com/data-integrations/wrangler)：Wrangler是一组库、一个流水线插件和一个CDAP服务，用于使用一组数据操作指令执行数据清理、转换和过滤，由Google开源。
* [Ares](https://github.com/rewerma/ares)：Ares是一个基于PL-SQL语法的数据计算集成引擎，用于ETL、跨源计算、数据分析和存储计算分离。
* [DataFlow Engine](https://github.com/risesoft-y9/DataFlow-Engine)：数据流引擎是一款面向数据集成、数据同步、数据交换、数据共享、任务配置、任务调度的底层数据驱动引擎，由北京有生博大软件开源。
* [BBoss Datatran](https://gitee.com/bboss/bboss-elastic-tran)：BBoss Datatran是由BBoss开源的数据采集同步ETL工具。
* [Starlake](https://github.com/starlake-ai/starlake)：Starlake是一种基于声明性文本的工具，使分析师和工程师能够提取、加载、转换和协调他们的数据管道。
* [CDAP](https://github.com/cdapio/cdap)：CDAP是一个面向Hadoop生态系统的集成开源应用程序开发平台，为开发人员提供数据和应用程序抽象，由Google开源。
* [Lucille](https://github.com/kmwtechnology/lucille)：Lucille是一种生产级搜索ETL解决方案。
* [Firehose](https://github.com/raystack/firehose)：Firehose是一种可扩展、无代码、云原生服务，用于将实时流数据从Kafka加载到数据存储、数据湖和分析存储系统。
* [Clink](https://gitee.com/tenmg/Clink)：Clink为基于Java的Flink应用程序提供快速集成的能力，可通过Clink快速构建Flink流批一体应用程序，实现异构数据库实时同步和ETL。
* [Apache Sqoop](https://github.com/apache/sqoop)：Sqoop允许在数据库和HDFS之间轻松导入和导出数据集，Cloudera开源。
* [StreamSets](https://github.com/streamsets/datacollector-oss)：StreamSets Data Collector是一个企业级开源持续大数据采集平台。
* [Cascading](https://github.com/cwensel/cascading)：Cascading是一个功能丰富的API，用于在本地或集群上定义和执行复杂且容错的数据处理流。

#### CDC组件

* [Flink CDC](https://github.com/apache/flink-cdc)：Flink CDC是一个针对实时数据和批量数据的分布式数据集成工具，阿里开源。
* [Databus](https://github.com/linkedin/databus)：Databus是一个与源无关的分布式变更数据捕获系统，它是LinkedIn数据处理管道的组成部分。
* [Maxwell](https://github.com/zendesk/maxwell)：Maxwell是一个CDC应用程序，它读取MySQL二进制日志并将数据变更以JSON形式写入Kafka、Kinesis和其他流平台，由Zendesk开源。
* [Brooklin](https://github.com/linkedin/brooklin)：Brooklin是一个分布式系统，旨在在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，由LinkedIn开源。
* [Debezium](https://github.com/debezium/debezium)：Debezium是一个开源项目，为CDC提供低延迟数据流平台，由RedHat开源。
* [Oracdc](https://github.com/averemee-si/oracdc)：Oracdc是一个用于异构IT环境中近实时数据集成和复制的软件包，由Oracle开源。
* [DBus](https://github.com/BriData/DBus)：DBus专注于数据的收集及实时数据流计算，通过简单灵活的配置，无侵入的方式对源端数据进行采集。
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [SpinalTap](https://github.com/airbnb/SpinalTap)：SpinalTap是一种通用的CDC服务，能够跨不同数据源低延迟地检测数据突变，并将其作为标准化事件传播给下游消费者，由Airbnb开源。
* [ACDC](https://github.com/xdfdotcn/acdc)：ACDC是新东方集团架构部开源的数据平台产品。
* [SyncLite](https://github.com/syncliteio/SyncLite)：SyncLite是一个开源、低代码、全面的关系数据整合平台，可帮助开发人员快速构建用于边缘、桌面和移动环境的数据密集型应用程序。
* [PolarDB-X CDC](https://github.com/polardb/polardbx-cdc)：PolarDB-X CDC是PolarDB-X的核心组件，负责全局二进制日志的生成、发布和订阅，由阿里开源。

#### 连接器

* [Apache Cassandra Spark Connector](https://github.com/apache/cassandra-spark-connector)：该库允许你将Cassandra表公开为Spark RDD和Datasets/DataFrames，将Spark RDD和Datasets/DataFrames写入Cassandra表，并在Spark应用程序中执行任意CQL查询。
* [MongoDB Connector Hadoop](https://github.com/mongodb/mongo-hadoop)：MongoDB Connector Hadoop是一个库，它允许将MongoDB用作Hadoop MapReduce任务的输入源或输出目标。
* [Stream Reactor](https://github.com/lensesio/stream-reactor)：Lenses.io维护的开源Apache 2.0 Kafka连接器集合。
* [Spark Redis](https://github.com/RedisLabs/spark-redis)：Spark Redis提供对Redis的所有数据结构的访问，以RDD的形式从Spark进行。
* [MongoDB Spark Connector](https://github.com/mongodb/mongo-spark)：MongoDB Connector Spark提供MongoDB和Apache Spark之间的集成。
* [Kafka Spark Consumer](https://github.com/dibbhatt/kafka-spark-consumer)：用于Spark Streaming的高性能Kafka连接器。
* [Spark HBase Connector](https://github.com/hortonworks-spark/shc)：Spark HBase Connector是一个支持Spark访问HBase表作为外部数据源或接收器的库。
* [Flink ClickHouse Connector](https://github.com/itinycheng/flink-connector-clickhouse)：ClickHouse数据库的Flink SQL连接器，该项目由ClickHouse JDBC提供支持。
* [MongoDB Kafka Connector](https://github.com/mongodb/mongo-kafka)：MongoDB Kafka Connector是一款经过Confluent验证的连接器，它将来自Kafka主题的数据持久化为数据接收器保存到MongoDB中，并将更改作为数据源从MongoDB发布到Kafka主题。
* [Flink Doris Connector](https://github.com/apache/doris-flink-connector)：Apache Doris的Flink连接器。
* [Kafka Connect Oracle](https://github.com/erdemcer/kafka-connect-oracle)：Kafka Connect Oracle是一个Kafka源连接器，用于从Oracle数据库捕获所有基于行的DML更改并将这些更改流式传输到Kafka。
* [Neo4j Spark Connector](https://github.com/neo4j/neo4j-spark-connector)：Neo4j Spark Connector，使用Spark DataSource API提供从Spark到Neo4j的双向读/写访问。
* [Spark HBase Connector](https://github.com/nerdammer/spark-hbase-connector)：该库允许你的Apache Spark应用程序使用简单而优雅的API与Apache HBase交互。
* [Azure SQL Spark Connector](https://github.com/microsoft/sql-spark-connector)：适用于SQL Server和Azure SQL的Apache Spark连接器，由Microsoft开源。
* [Spark Atlas Connector](https://github.com/hortonworks-spark/spark-atlas-connector)：用于跟踪Spark SQL/DataFrame转换并将元数据更改推送到Apache Atlas的连接器，由Hortonworks开源。
* [Flink Connector Redis](https://github.com/jeff-zou/flink-connector-redis)：基于Lettuce的异步Flink连接器，支持SQL Join和Sink、查询缓存和调试。
* [HBase Connector](https://github.com/apache/hbase-connectors)：Apache HBase连接器。
* [Presto HBase Connector](https://github.com/analysys/presto-hbase-connector)：Presto HBase Connector基于Presto Connector接口规范实现，用于为Presto添加查询HBase的能力，由易观开源。
* [TiBigData](https://github.com/tidb-incubator/TiBigData)：适用于TiDB、Presto、Flink和MapReduce连接器的其他大数据组件。
* [Spark MongoDB](https://github.com/Stratio/Spark-MongoDB)：Spark MongoDB是一个库，允许用户使用Spark SQL从MongoDB集合读取数据/将数据写入MongoDB集合，由Stratio开源。
* [Spark ClickHouse Connector](https://github.com/ClickHouse/spark-clickhouse-connector)：Spark ClickHouse连接器基于DataSourceV2 API构建。
* [Deep](https://github.com/Stratio/deep-spark)：Deep是Apache Spark和多个NoSQL数据存储之间的薄集成层，由Stratio开源。
* [Flink HTTP Connector](https://github.com/getindata/flink-http-connector)：HTTP TableLookup连接器允许通过HTTP GET方法从外部系统提取数据，HTTP Sink允许通过HTTP请求将数据发送到外部系统。
* [ClickHouse Kafka Connect](https://github.com/ClickHouse/clickhouse-kafka-connect)：ClickHouse Kafka Connect是ClickHouse的官方Kafka Connect接收器连接器。
* [Neo4j Streams](https://github.com/neo4j-contrib/neo4j-streams)：该项目将Neo4j与Apache Kafka和Confluent平台集成在一起。
* [Couchbase Elasticsearch Connector](https://github.com/couchbase/couchbase-elasticsearch-connector)：Couchbase Elasticsearch Connector几乎实时地将你的文档从Couchbase Server复制到Elasticsearch。
* [Kafka Connect](https://github.com/jcustenborder/kafka-connect-spooldir)：Kafka Connect连接器提供监视文件目录并在将新文件写入输入目录时读取数据的功能。
* [Camel Kafka Connector](https://github.com/apache/camel-kafka-connector)：Camel Kafka Connector旨在提供一种用户友好的方式，在Kafka Connect中使用所有Apache Camel组件。
* [SingleStoreDB Spark Connector](https://github.com/memsql/singlestore-spark-connector)：SingleStore和Spark的连接器。
* [Snowflake Kafka Connector](https://github.com/snowflakedb/snowflake-kafka-connector)：Snowflake Kafka Connector是Apache Kafka Connect的一个插件，将数据从Kafka主题提取到Snowflake表。
* [Kafka Kinesis Connector](https://github.com/awslabs/kinesis-kafka-connector)：Kafka Kinesis Connector是一种与Kafka Connect一起使用的连接器，用于将消息从Kafka发布到Amazon Kinesis Streams或Amazon Kinesis Firehose。
* [Kafka Connect MongoDB](https://github.com/hpgrahsl/kafka-connect-mongodb)：这是适用于MongoDB的基本Apache Kafka Connect SinkConnector。
* [Kafka Connect BigQuery Connector](https://github.com/wepay/kafka-connect-bigquery)：这是基于Apache Kafka Connect构建的从Apache Kafka到Google BigQuery的接收器连接器的实现，由WePay开源。
* [Kafka Connect HTTP Connector](https://github.com/castorm/kafka-connect-http)：Kafka Connect连接器可将JSON/HTTP API中的变更数据捕获到Kafka中。
* [Kafka Connectors SAP](https://github.com/SAP/kafka-connect-sap)：Kafka Connect SAP是一组通用连接器，使用Apache Kafka Connect框架可靠地将Kafka与SAP系统连接起来。
* [Kafka HTTP Sink Connector](https://github.com/Aiven-Open/http-connector-for-apache-kafka)：这是一个接收器Apache Kafka Connect连接器，通过HTTP/S发送Kafka记录，由Aiven开源。
* [Pulsar Spark](https://github.com/streamnative/pulsar-spark)：Spark Connector，用于读取和写入Pulsar。
* [Trino Storage Connector](https://github.com/snowlift/trino-storage)：这是一个用于访问单个文件(例如CSV、TSV)的Trino连接器。
* [Stocator](https://github.com/CODAIT/stocator)：Stocator是Spark对象存储的高性能连接器，通过利用对象存储语义来实现性能，由IBM开源。
* [Kafka Connect IBM MQ](https://github.com/ibm-messaging/kafka-connect-mq-source)：Kafka Connect IBM MQ是一个Kafka Connect源连接器，用于将数据从IBM MQ复制到Apache Kafka。
* [Doris Spark Connector](https://github.com/apache/doris-spark-connector)：Spark Doris Connector可以支持通过Spark读取存储在Doris中的数据以及将数据写入Doris。
* [Splunk Connect Kafka](https://github.com/splunk/kafka-connect-splunk)：Splunk Connect Kafka是Splunk的Kafka Connect Sink。
* [Pravega Flink Connectors](https://github.com/pravega/flink-connectors)：Pravega Flink Connectors实现了使用Apache Flink流处理框架读取和写入Pravega Streams的连接器。

#### 集群管理

* [Apache Aurora](https://github.com/apache/aurora)：Aurora是一个用于长期运行服务和cron作业的Mesos框架，由Twitter开源。
* [Chronos](https://github.com/mesos/chronos)：Chronos是cron的替代品，它是一个分布式容错调度程序，运行在Mesos之上，可用于作业编排。
* [Sparrow](https://github.com/radlab/sparrow)：Sparrow是一个高吞吐量、低延迟、容错的分布式集群调度器，由加州大学伯克利分校开源。
* [Singularity](https://github.com/HubSpot/Singularity)：Singularity是一种API和Web应用程序，用于运行和调度Mesos任务，包括长时间运行的进程、计划作业和一次性任务。
* [OPENI](https://github.com/open-intelligence/OpenI-Octopus)：OPENI是一个集群管理工具和资源调度平台，最初由微软研究院、微软搜索技术中心、北京大学、西安交通大学、浙江大学和中国科学技术大学联合设计和开发。
* [Norbert](https://github.com/rhavyn/norbert)：Norbert是一个提供简单集群管理和集群感知客户端/服务器网络API的库，由Linkedin开源。
* [Apache Helix](https://github.com/apache/helix)：Helix是一个通用集群管理框架，用于自动管理节点集群上托管的分区、复制和分布式资源，由LinkedIn开源。
* [Apache Airavata](https://airavata.apache.org/)：Airavata是一个软件框架，用于在分布式计算资源(包括本地集群、超级计算机、国家电网、学术和商业云)上执行和管理计算作业，由印第安纳大学开源。
* [Fenzo](https://github.com/Netflix/Fenzo)：Fenzo是Apache Mesos框架的调度程序Java库，支持调度优化插件并促进集群自动扩展，由Netflix开源。
* [Apache REEF](https://github.com/apache/reef)：REEF是一个用于为集群资源管理器(例如Apache Hadoop YARN或Apache Mesos)开发可移植应用程序的库，由微软研究院开源。
* [Orion](https://github.com/pinterest/orion)：Orion是一个适用于有状态分布式系统的通用可插拔管理和自动化平台，由Pinterest开源。
* [Apache Myriad](https://github.com/apache/incubator-myriad)：Myriad是一个Mesos框架，旨在扩展Mesos上的YARN集群，由eBay、MapR和Mesosphere开源。
* [Declarative Cluster Management](https://github.com/vmware/declarative-cluster-management)：DCM使程序员能够使用高级声明性语言(SQL)构建调度程序和集群管理器，由VMware开源。
* [Marathon](https://github.com/mesosphere/marathon)：Marathon是经过生产验证的用于容器编排的Mesos框架，由Mesosphere开源。

#### 调度系统

* [Apache Oozie](https://github.com/apache/oozie)：Oozie是一个可扩展、可伸缩且可靠的系统，用于通过Web服务定义、管理、调度和执行复杂的Hadoop工作负载，由Yahoo开源。
* [Taier](https://github.com/DTStack/Taier)：太二是一个提交、调度、运维、指标信息展示的大数据开发平台，由袋鼠云开源。
* [Harrier](https://github.com/spdb-opensource/harrier)：Harrier是一个由上海浦东发展银行开源的海量作业调度系统，支持各类异构计算平台海量计算作业的配置、管理和监控功能。
* [Zeus](https://github.com/cloverfisher/zeus)：宙斯是阿里开源的一款分布式Hadoop作业调度平台，支持多机器的水平扩展。
* [Hera](https://github.com/scxwhite/hera)：Hera是一个分布式大数据任务调度系统。
* [Big Whale](https://gitee.com/meetyoucrop/big-whale)：巨鲸任务调度平台为美柚大数据研发的分布式计算任务调度系统，提供Spark、Flink等批处理任务的DAG调度和流处理任务的运行管理和状态监控。
* [Sylph](https://github.com/harbby/sylph)：Sylph是一个用于实时流计算的平台，核心是通过工作流描述构建分布式流计算应用程序。
* [Genie](https://github.com/Netflix/genie)：Genie是Netflix开发的联合大数据编排和执行引擎。

#### 执行引擎

* [Apache Calcite](https://github.com/apache/calcite)：Calcite是一个动态数据管理框架，由Hortonworks开源。
* [Apache Tez](https://github.com/apache/tez)：Tez是一个通用数据处理管道引擎，被设想为用于更高抽象的低级引擎，例如Hadoop Map-Reduce、Pig、Hive等，由IBM和Adobe开发。
* [Cubert](https://github.com/LinkedInAttic/Cubert)：Cubert是一种快速高效的批量计算引擎，用于对Hadoop上的海量数据集进行复杂分析和报告，由LinkedIn开源。
* [Apache Apex](https://github.com/apache/apex-core)：Apex是一个用于大数据流和批处理的统一平台，由DataTorrent开源。
* [Apache Gluten](https://github.com/apache/incubator-gluten)：Gluten是一个中间层，负责将基于JVM的SQL引擎的执行卸载到本机引擎，由Intel和Kyligence开源。
* [TiSpark](https://github.com/pingcap/tispark)：TiSpark是一个薄层，用于在TiDB/TiKV/TiFlash之上运行Spark，以回答复杂的OLAP查询，由PingCAP开发。
* [Apache DataFusion Comet](https://github.com/apache/datafusion-comet)：DataFusion Comet是一个Spark插件，它使用DataFusion作为本机运行时，以实现查询效率和查询运行时方面的改进，由Apple开源。

#### OLAP引擎

* [Apache Kylin](https://github.com/apache/kylin)：Kylin是一个面向Hadoop和云的统一且强大的OLAP平台，由eBay贡献。
* [MdRill](https://github.com/alibaba/mdrill)：MdRill作为数据在线分析处理软件，可以在几秒到几十秒的时间，分析百亿级别的任意组合维度的数据，由阿里开源。
* [Maha](https://github.com/yahoo/maha)：快速报告API开发的框架，开箱即用地支持Druid的高基数维度查找，由Yahoo开源。
* [Olap4j](https://github.com/olap4j/olap4j)：Olap4j是用于访问OLAP数据的开放Java API，Pentaho开源。
* [QinSQL](https://github.com/qinsql/QinSQL)：QinSQL是一个基于Lealone的可暂停的渐进式OLAP引擎。
* [COOL](https://github.com/COOL-cohort/COOL)：COOL是一种非常高效的OLAP引擎，用于对时序数据进行队列和OLAP分析，由新加坡国立大学开源。
* [Imhotep](https://github.com/indeedeng/imhotep)：Imhotep是Indeed打造的大型分析平台。
* [Mondrian](https://github.com/pentaho/mondrian)：Mondrian是一款OLAP服务器，使业务用户能够实时分析大量数据。

#### CEP引擎

* [Apache Drools](https://github.com/apache/incubator-kie-drools)：Drools是Java的规则引擎、DMN引擎和复杂事件处理(CEP)引擎，由RedHat开源。
* [Siddhi](https://github.com/siddhi-io/siddhi)：Siddhi是一个云原生流式处理和复杂事件处理引擎，由WSO2开源。
* [Esper](https://github.com/espertechinc/esper)：Esper是用于复杂事件处理(CEP)、流式SQL和事件系列分析的组件。
* [Kafka Streams CEP](https://github.com/fhussonnois/kafkastreams-cep)：该库可用于扩展Kafka Streams API，以便从流中选择复杂的事件序列。
* [Siddhi](https://github.com/haoch/flink-siddhi)：Siddhi CEP是一个轻量级且易于使用的开源复杂事件处理引擎。
* [Wayeb](https://github.com/ElAlev/Wayeb)：Wayeb是一个用Scala编写的复杂事件处理和预测(CEP/F)引擎。

#### 监控工具

* [Ambrose](https://github.com/twitter-archive/ambrose)：Ambrose是一个用于MapReduce数据工作流可视化和实时监控的平台，由Twitter开源。
* [Dr.Elephant](https://github.com/linkedin/dr-elephant)：Dr.Elephant是一款针对Hadoop和Spark的性能监控和调优工具，由LinkedIn开源。
* [Apache Ambari](https://github.com/apache/ambari)：Ambari是一个用于配置、管理和监控Hadoop集群的工具，由Hortonworks开源。
* [Apache Metron](https://github.com/apache/metron)：Metron集成了多种开源大数据技术，以提供集中的安全监控和分析工具，由Cisco开源。
* [Surus](https://github.com/Netflix/Surus)：Pig和Hive中的分析工具集合，Netflix开源。
* [Compass](https://github.com/cubefs/compass)：Compass是一个大数据任务诊断平台，由OPPO大数据团队开发。
* [Inviso](https://github.com/Netflix/inviso)：Inviso是一个轻量级工具，提供搜索Hadoop作业、可视化性能和查看集群利用率的功能，由Netflix开源。
* [DataSophon](https://github.com/iflytek/datasophon)：DataSophon是新一代云原生大数据管家，致力于帮助用户快速构建起稳定、高效、可弹性伸缩的大数据云原生平台，由科大讯飞开源。
* [DCMonitor](https://github.com/shunfei/DCMonitor)：DCMonitor是一个简单、轻量级的数据中心监控器，目前包含Zookeeper、Kafka和Druid，由舜飞开源。
* [Apache Eagle](https://github.com/apache/eagle)：Eagle是一种开源分析解决方案，用于在大数据平台上立即识别安全和性能问题，由eBay开源。
* [Flink Streaming Platform Web](https://github.com/zhp8341/flink-streaming-platform-web)：Flink Streaming Platform Web是基于Flink封装的一个可视化、轻量级的Flink Web客户端系统。
* [SparkMeasure](https://github.com/LucaCanali/sparkMeasure)：SparkMeasure是一款旨在简化Apache Spark作业性能测量和故障排除的工具和库。

#### Notebook

* [Polynote](https://github.com/polynote/polynote)：Polynote是一个实验性多语言笔记本环境，由Netflix开源。
* [Apache Zeppelin](https://github.com/apache/zeppelin)：Zeppelin是一款基于Web的笔记本，支持交互式数据分析，由韩国公司ZEPL开源。
* [Spark Notebook](https://github.com/spark-notebook/spark-notebook)：Spark Notebook是针对企业环境的开源笔记本，为数据科学家和数据工程师提供了一个基于Web的交互式编辑器。

#### 数据湖框架

* [Apache Hudi](https://github.com/apache/hudi)：Hudi是一个事务性数据湖平台，可为数据湖带来数据库和数据仓库功能，由Uber开源。
* [LakeSoul](https://github.com/lakesoul-io/LakeSoul)：LakeSoul是一个云原生Lakehouse框架，支持可扩展的元数据管理、ACID事务、高效灵活的更新插入操作、模式演化以及统一的流和批处理，由数元灵科技开源。
* [Apache Paimon](https://github.com/apache/paimon)：Paimon是一种Lake格式，可以使用Flink和Spark构建实时Lakehouse架构，以进行流式处理和批处理操作。
* [Apache Iceberg](https://github.com/apache/iceberg)：Iceberg是一种适用于大型分析表的高性能格式，由Netflix开源。
* [Delta](https://github.com/delta-io/delta)：Delta Lake是一个开源存储框架，支持使用Spark、PrestoDB、Flink、Trino和Hive等计算引擎以及Scala、Java、Rust、Ruby和Python的API构建Lakehouse架构，由Databricks开源。
* [Kylo](https://github.com/Teradata/kylo)：Kylo是一个企业级现代数据湖管理软件平台，适用于Teradata、Spark或Hadoop等大数据引擎，由Teradata开源。
* [Nessie](https://github.com/projectnessie/nessie)：Nessie使你能够维护数据的多个版本，并为你的数据湖利用类似Git的分支和标签，由Dremio团队开源。
* [Amoro](https://github.com/apache/amoro)：Amoro是一个基于开放数据湖格式构建的Lakehouse管理系统，由网易开源。
* [Dremio](https://github.com/dremio/dremio-oss)：Dremio是一个开源且简单的数据湖库，提供自助式SQL分析、数据仓库性能和功能以及涵盖所有数据的数据湖灵活性。
* [OpenHouse](https://github.com/linkedin/openhouse)：OpenHouse是一个开源控制平面，旨在高效管理开放数据Lakehouse部署中的表，由LinkedIn开源。
* [Pixels](https://github.com/pixelsdb/pixels)：Pixels的核心是专为数据湖和数据仓库设计的列式存储引擎，由中国人民大学开源。
* [Apache XTable](https://github.com/apache/incubator-xtable)：XTable是一种表格式的跨表转换器，可促进跨数据处理系统和查询引擎的全方位互操作性，由Onehouse开源。
* [RTF](https://github.com/jd-bigdata/rtf-lake)：京东RTF实时数据湖，是一个从底层重新构建的系统，解决了数据的接入、解析及清洗等ETL过程。
* [PuppetDB](https://github.com/puppetlabs/puppetdb)：PuppetDB是Puppet的快速、可扩展且可靠的数据仓库。

#### 数据Shuffle

* [Apache Celeborn](https://github.com/apache/incubator-celeborn)：Celeborn是一种弹性且高性能的服务，用于洗牌和溢出数据，由阿里云开源。
* [Apache Uniffle](https://github.com/apache/incubator-uniffle)：Uniffle是一种用于分布式计算引擎的高性能、通用远程洗牌服务，由腾讯开源。
* [Shuttle](https://github.com/cubefs/shuttle)：Shuttle提供远程Shuffle功能，可以按分区将Shuffle数据分组并转储到分布式文件系统中，由OPPO大数据团队开源。
* [Remote Shuffle Server](https://github.com/uber/RemoteShuffleService)：Uber Remote Shuffle Server为Spark应用程序提供了在远程服务器上存储Shuffle数据的功能。
* [Cloud Shuffle Service](https://github.com/bytedance/CloudShuffleService)：Cloud Shuffle Service是适用于计算引擎(包括Spark/Flink/MapReduce)的通用远程Shuffle解决方案，由字节开源。
* [Splash](https://github.com/MemVerge/splash)：Splash提供一个快速、灵活和可靠的Shuffle管理器，允许用户插入喜欢的后端存储和网络框架来保存和交换Shuffle数据。

#### 时序数据分析

* [Flint](https://github.com/twosigma/flint)：Apache Spark的时序库。
* [Spark TimeSeries](https://github.com/sryza/spark-timeseries)：用于与Apache Spark上的时序数据交互的Scala/Java/Python库。
* [SFA](https://github.com/patrickzib/SFA)：可扩展的时序数据分析，由柏林洪堡大学开发。
* [Chronicle TimeSeries](https://github.com/OpenHFT/Chronicle-TimeSeries)：多线程时序库。
* [GrammarViz](https://github.com/GrammarViz2/grammarviz2_src)：GrammarViz是一款具有GUI和CLI界面的时序探索性分析软件。

## 进程间通信

#### 消息中间件

* [Amazon SQS](https://aws.amazon.com/cn/sqs/)：Amazon SQS是亚马逊公司在2004年推出的分布式消息队列服务。
* [Apache Kafka](https://github.com/apache/kafka)：Kafka是一个开源分布式事件流平台，已被数千家公司用于高性能数据管道、流分析、数据集成和关键任务应用程序，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：Pulsar是一个分布式Pub-Sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API，由Yahoo开源。
* [Apache ActiveMQ](https://github.com/apache/activemq)：ActiveMQ是一个高性能的消息代理。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：RocketMQ是一个分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性，由阿里开源。
* [Apache ActiveMQ Artemis](https://github.com/apache/activemq-artemis)：ActiveMQ Artemis是Apache ActiveMQ的下一代消息代理。
* [Apache Camel](https://github.com/apache/camel)：Camel是一个开源集成框架，使你能够快速轻松地集成使用或生成数据的各种系统，由RedHat开源。
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
* [TxEventQ](https://www.oracle.com/database/advanced-queuing/)：TxEventQ是Oracle数据库中内置的消息传递平台，可用于应用程序工作流、微服务和事件触发的操作。
* [OpenMessaging](https://github.com/openmessaging/openmessaging-java)：OpenMessaging是由阿里发起，由Yahoo、滴滴、Streamlio、微众、Datapipeline等公司共同创建的分布式消息规范。
* [Metamorphosis](https://github.com/killme2008/Metamorphosis)：Metamorphosis是淘宝开源的一个Java消息中间件。
* [ElasticMQ](https://github.com/softwaremill/elasticmq)：ElasticMQ是一个消息队列系统，提供基于Actor的Scala和SQS兼容的REST接口，由SoftwareMill开源。
* [Hermes](https://github.com/ctripcorp/hermes)：携程异步消息队列解决方案。
* [Eclipse OpenMQ](https://github.com/eclipse-ee4j/openmq)：OpenMQ是一个完整的面向消息的中间件平台，提供高质量、企业级消息传递。
* [JORAM](https://joram.ow2.io/)：JORAM是JMS API规范的开源Java实现(符合Java 11至21以及JMS 1.1、2.0和3.0)，由格勒诺布尔大学开源。
* [Jafka](https://github.com/adyliu/jafka)：Jafka是从Apache Kafka克隆出来的分布式发布-订阅消息系统，由搜狐维护。
* [Hermes](https://github.com/allegro/hermes)：Hermes是一个构建在Kafka之上的异步消息代理，由波兰最大电商Allegro开源。
* [Apache Qpid](https://github.com/apache/qpid)：Qpid是一个功能强大的开源消息代理，由摩根大通开源。
* [Axon Server](https://github.com/AxonIQ/axon-server-se)：Axon Server是Axon定制的可扩展且高度可用的事件存储和消息传递系统。
* [MemQ](https://github.com/pinterest/memq)：MemQ是高效、可扩展的云原生PubSub系统，由Pinterest开源。
* [CMB](https://github.com/Comcast/cmb)：CMB是一款高可用性、水平可扩展的队列和通知服务，兼容AWS SQS和SNS，由Comcast开源。
* [Ytk-Mp4j](https://github.com/kanyun-inc/ytk-mp4j)：Ytk-Mp4j是一个快速、用户友好、跨平台、多进程、多线程的集体消息传递Java库，用于分布式机器学习，由看云控股技术团队开源。
* [FolkMQ](https://gitee.com/noear/folkmq)：FolkMQ内存型消息中间件，支持快照持久化和Broker集群模式。

#### 事件总线

* [EventBus](https://github.com/greenrobot/EventBus)：EventBus是适用于Android和Java的发布/订阅事件总线。
* [EventBus](https://github.com/MinecraftForge/EventBus)：EventBus是一个简单的订阅者-发布者框架。
* [MBassador](https://github.com/bennidi/mbassador)：MBassador是一个轻量级、高性能的事件总线，实现了发布订阅模式。
* [Otto](https://github.com/square/otto)：Otto是一种事件总线，旨在解耦应用程序的不同部分，同时仍然允许它们高效通信，由Square开源。
* [Alibaba RSocket Broker](https://github.com/alibaba/alibaba-rsocket-broker)：Alibaba RSocket Broker是一款基于RSocket协议的响应式对等通讯系统，为通讯多方构建分布式的RPC、Pub/Sub、Streaming等通讯支持。
* [RxBus](https://github.com/AndroidKnife/RxBus)：RxBus是一个事件总线，旨在让你的应用程序有效地进行通信。
* [Andromeda](https://github.com/iqiyi/Andromeda)：Andromeda为本地和远程服务提供模块之间的通信，由爱奇艺开源。
* [HermesEventBus](https://github.com/Xiaofei-it/HermesEventBus)：HermesEventBus是一个在进程之间使用EventBus的库，在IPC或插件开发中很有用。
* [AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)：AndroidEventBus是适用于Android的轻量级事件总线库，简化了Activity、Fragments、Threads、Services等之间的通信。
* [Nakadi](https://github.com/zalando/nakadi)：Nakadi是一个分布式事件总线代理，它在类似Kafka的队列之上实现了RESTful API抽象，可用于以可靠且高度可用的方式实时发送、接收和分析流数据，由Zalando开源。
* [Apollo](https://github.com/Sloaix/Apollo)：RxJava的事件总线。
* [TinyBus](https://github.com/sergejsha/tinybus)：TinyBus是Otto事件总线的更快实现，附加了你错过的额外功能。
* [xBus](https://github.com/mcxiaoke/xBus)：简洁的EventBus实现。
* [ElegantBus](https://github.com/codyer/ElegantBus)：ElegantBus是一款Android平台，基于LivaData的消息总线框架。
* [Router](https://github.com/SilenceDut/Router)：Router是类似事件总线的替代品，由动态代理实现。
* [Alpine](https://github.com/ZeroMemes/Alpine)：Alpine是适用于Java 8+的轻量级事件系统。
* [Broker](https://github.com/adrielcafe/broker)：Broker是一个使用Coroutines构建的适用于Android和JVM的发布-订阅库。
* [Events4J](https://github.com/PhilippHeuer/events4j)：Java事件调度程序/消费者。
* [DamiBus](https://gitee.com/noear/dami)：DamiBus专为本地多模块之间通讯解耦而设计。
* [IPC EventBus](https://github.com/Terracotta-OSS/ipc-eventbus)：IPC EventBus为JVM内和JVM外通信提供了一个简单的EventBus API。
* [FastCast](https://github.com/RuedigerMoeller/fast-cast)：FastCast是一个高速无代理消息传递库，涵盖从简单的共享内存到大型LAN集群应用程序的Java进程间通信。
* [Channel](https://github.com/liangjingkanji/Channel)：EventBus特性的事件总线框架。
* [Eventbus](https://github.com/likavn/eventbus)：Eventbus是基于Spring Boot Starter的分布式业务消息分发总线组件(发布/订阅模式)，支持延时消息。
* [Deezpatch](https://github.com/joel-jeremy/deezpatch)：Deezpatch是一个简单快速的库，用于将请求和事件分派到相应的处理程序。
* [Minibus](https://github.com/jneat/minibus)：Java应用实例的简单事件总线。

#### 消息总线

* [Chronicle Queue](https://github.com/OpenHFT/Chronicle-Queue)：Chronicle Queue是一个适用于高性能应用程序的持久低延迟消息传递框架，由Chronicle软件公司开源。
* [Aeron](https://github.com/real-logic/Aeron)：Aeron是一个开源高性能消息传输机制(单向)，支持高效可靠的UDP单播、UDP多播和IPC消息传输，由Adaptive公司开源。
* [LCM](https://github.com/lcm-proj/lcm)：LCM是一组用于消息传递和数据编组的库和工具，针对高带宽和低延迟至关重要的实时系统，由MIT开源。
* [DeFiBus](https://github.com/WeBankFinTech/DeFiBus)：DeFiBus是基于开源消息中间件打造的安全可控的分布式金融级消息总线，由微众开源。
* [ZBus](https://gitee.com/openforce/zbus)：ZBus致力于使消息队列和RPC变得快速、轻量级并且易于为许多不同的平台构建你自己的面向服务的架构，由开放金融技术开源。
* [Mappedbus](https://github.com/caplogic/Mappedbus)：Mappedbus是一种用于利用共享内存的Java微服务的低延迟消息总线。
* [Spring Cloud Stream](https://github.com/spring-cloud/spring-cloud-stream)：Spring Cloud Stream是一个用于构建与共享消息系统连接的高度可扩展的事件驱动微服务的框架，由Pivotal开发。
* [CoralSequencer](https://www.coralblocks.com/index.php/category/coralsequencer/)：CoralSequencer是一款功能齐全、超低延迟、全序消息传递中间件，适用于基于异步消息的分布式系统。
* [EBus](https://ebus.sourceforge.io/eBus)：EBus是一个Java中间件API，支持无代理、基于类型+主题的发布/订阅和请求/回复消息传递，用于应用程序内和应用程序间的对象级通信。
* [Spring Cloud Bus](https://github.com/spring-cloud/spring-cloud-bus)：Spring Cloud Bus是一种轻量级的消息代理，用于集成和传输微服务之间的消息。
* [LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)：LiveEventBus是一款Android消息总线，基于LiveData，具有生命周期感知能力，支持Sticky、AndroidX、款进程。
* [Varadhi](https://github.com/flipkart-incubator/varadhi)：Varadhi是具有REST接口的消息总线实现，由Flipkart开源。
* [Namastack](https://github.com/namastack/namastack-outbox)：Spring Boot的发件箱实现。
* [Low Level Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计，包括事件总线。
* [Flux Capacitor](https://github.com/flux-capacitor-io/flux-capacitor-client)：该仓库包含Flux Capacitor服务的官方Java客户端。

#### 应用总线

* [Apache Synapse](https://github.com/apache/synapse)：Synapse是一种轻量级高性能企业服务总线，由WSO2开源。
* [Plexus Interop](https://github.com/finos/plexus-interop)：Plexus Interop项目旨在定义桌面应用程序互操作性的开放标准，并提供该标准的参考实现，由金融科技基金会开源。
* [Apache ServiceMix](https://github.com/apache/servicemix)：ServiceMix是一个灵活的开源集成容器，它将ActiveMQ、Camel、CXF和Karaf的特性和功能成为一个强大的运行时平台，你可以使用它来构建自己的集成解决方案。它提供了一个完全由OSGi提供支持的企业级ESB。
* [Bus](https://github.com/839128/bus)：Bus是一个基础框架、服务套件，它基于Java 17编写，参考、借鉴了大量已有框架、组件的设计，可以作为后端服务的开发基础中间件。
* [JBoss Fuse](https://github.com/jboss-fuse/fuse)：JBoss Fuse是一个开源ESB，其功能基于Apache Camel、Apache CXF、Apache ActiveMQ、Apache Karaf和Fabric8，集成在一个发行版中。
* [Petals ESB](https://petals.linagora.com/)：Petals ESB是一个开源企业服务总线。

#### 消息队列客户端

* [RabbitMQ Java](https://github.com/rabbitmq/rabbitmq-java-client)：RabbitMQ Java客户端库。
* [Lyra](https://github.com/jhalterman/lyra)：Lyra是一个拥抱故障的RabbitMQ客户端，可在发生意外故障时自动恢复AMQP资源，帮助你实现服务的高可用性。
* [Hop](https://github.com/rabbitmq/hop)：适用于Java、Groovy和其他JVM语言的RabbitMQ HTTP API客户端。
* [SIA RabbitMQ Plus](https://github.com/siaorg/sia-rabbitmq-plus)：SIA RabbitMQ Plus是宜信开发的一个简单RabbitMQ客户端。
* [Spring AMQP](https://github.com/spring-projects/spring-amqp)：Spring AMQP项目将核心Spring概念应用于基于AMQP的消息传递解决方案的开发。
* [ReliableRMQ](https://github.com/levy-tech-spark/ReliableRMQ)：ReliableRMQ是一个Spring Boot框架，用于使用RabbitMQ的可靠消息传递实现分布式事务。
* [HiveMQ MQTT Client](https://github.com/hivemq/hivemq-mqtt-client)：MQTT 5.0和3.1.1兼容且功能丰富的高性能Java客户端库，具有不同的API风格和背压支持。
* [NSQ-J](https://github.com/sproutsocial/nsq-j)：NSQ实时分布式消息传递平台的Java客户端。
* [NATS Java](https://github.com/nats-io/nats.java)：NATS消息系统的Java客户端。
* [Amazon SQS Java Messaging Library](https://github.com/awslabs/amazon-sqs-java-messaging-lib)：Amazon SQS Java Messaging Library包含与JMS兼容的类，用于与Amazon SQS进行通信。
* [Java Pub/Sub](https://github.com/googleapis/java-pubsub)：Google Cloud Pub/Sub的Java惯用客户端。
* [Google Pub/Sub](https://github.com/GoogleCloudPlatform/pubsub)：Google Cloud Pub/Sub开源项目。
* [PSC](https://github.com/pinterest/psc)：PSC是一个通用且可扩展的客户端库，允许应用程序通过统一的接口与不同的后端PubSub系统进行交互，由Pinterest开发。
* [Async Google Pub/Sub Client](https://github.com/spotify/async-google-pubsub-client)：一个低级别的Pub/Sub客户端和一个并发的每主题批处理发布者，由Spotify开发。
* [OpenMAMA](https://github.com/finos/OpenMAMA)：OpenMAMA是一个高性能、与供应商无关的轻量级包装器，它为跨各种平台和语言的不同中间件和消息传递解决方案提供通用API接口，由金融科技基金会开源。

#### Kafka

* [CMAK](https://github.com/yahoo/CMAK)：CMAK是用于管理Kafka集群的工具，由Yahoo开源。
* [Kafka UI](https://github.com/provectus/kafka-ui)：用于管理Kafka集群的多功能、快速且轻量级的Web UI。
* [Spring Kafka](https://github.com/spring-projects/spring-kafka)：Spring Kafka项目将核心Spring概念应用于基于Kafka的消息传递解决方案的开发。
* [Confluent Parallel Consumer](https://github.com/confluentinc/parallel-consumer)：并行Apache Kafka客户端包装器，具有客户端排队功能、更简单的消费者/生产者API、关键并发性和可扩展的非阻塞IO处理。
* [KafkaUI Lite](https://gitee.com/freakchicken/kafka-ui-lite)：非常好用的Kafka UI客户端工具，同时支持Zookeeper、Redis。
* [uReplicator](https://github.com/uber/uReplicator)：uReplicator提供了高性能、可扩展、稳定的Kafka复制解决方案，由Uber开源。
* [AKHQ](https://github.com/tchiotludo/akhq)：用于Kafka的Kafka GUI，可以管理主题、主题数据、消费者组、模式注册表、连接等等。
* [Kouncil](https://github.com/Consdata/kouncil)：Kouncil让你可以使用现代Web界面监控和管理Apache Kafka集群。
* [Liiklus](https://github.com/bsideup/liiklus)：Liiklus是基于RSocket/gRPC的事件系统网关，防止那些认为Kafka过于低级的人。
* [Offset Explorer](https://www.kafkatool.com/index.html)：Offset Explorer是一个用于管理和使用Apache Kafka集群的GUI应用程序。
* [Confluent Platform](https://www.confluent.io/en-gb/product/confluent-platform/gui-driven-management-and-monitoring/)：Confluent Platform提供直观的GUI来管理和监控Apache Kafka，由Confluent开发。
* [Kpow](https://factorhouse.io/kpow/)：Kpow是Apache Kafka的监控和管理工具。
* [Lenses](https://lenses.io/)：Lenses是开发人员体验工具，可帮助企业在一个地方使用每个Apache Kafka。
* [KafkaEsque](https://github.com/patschuh/KafkaEsque)：KafkaEsque是一个用JavaFX开发的Kafka GUI工具。
* [KnowStreaming](https://github.com/didi/KnowStreaming)：Know Streaming是一套云原生的Kafka管控平台，脱胎于众多互联网内部多年的Kafka运营实践经验，专注于Kafka运维管控、监控告警、资源治理、多活容灾等核心场景，由滴滴开源。
* [EFAK](https://github.com/smartloli/EFAK)：EAFK是一个开源的Kafka集群管理和监控工具，旨在帮助用户更好地管理和监控其Kafka集群。
* [ZMS](https://github.com/ZTO-Express/zms)：ZMS是使用方与集群解耦，屏蔽各消息集群差异，并对消息集群进行安装、管理、监控、告警管理的平台，由中通开源。
* [KafkIO](https://kafkio.com/)：面向工程师和管理员的快速、简便的Apache Kafka GUI，适用于macOS、Windows和Linux，由Certak公司维护。
* [Kafka WebView](https://github.com/SourceLabOrg/kafka-webview)：Kafka WebView提供了一个易于使用的基于Web的界面，用于从Kafka主题中读取数据并提供基本的过滤和搜索功能。
* [Cruise Control](https://github.com/linkedin/cruise-control)：Cruise Control是一款帮助大规模运行Kafka集群的产品，由LinkedIn开源。
* [KCenter](https://github.com/xaecbd/KCenter)：KCenter是一个统一的Kafka集群管理维护、生产者/消费者监控、生态组件使用的一站式平台。
* [Kafka Map](https://github.com/dushixiang/kafka-map)：Kafka Map是使用Java 17和React开发的Kafka可视化工具。
* [Kstreamplify](https://github.com/michelin/kstreamplify)：Kstreamplify是一个Java库，使你能够快速创建基于Kafka Stream的应用程序，并提供许多附加高级功能，由米其林开源。
* [Kafka-Sprout](https://github.com/oslabs-beta/Kafka-Sprout)：Kafka Sprout是一个Web GUI，可以帮助你在本地计算机上快速启动Zookeeper和Kafka服务器，无需任何代码配置。
* [Xinfra Monitor](https://github.com/linkedin/kafka-monitor)：Xinfra Monitor是一个在真实集群中实现和执行长时间运行的kafka系统测试的框架，由LinkedIn开源。
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry)：Kafka的Confluence模式注册中心。
* [Kafdrop](https://github.com/HomeAdvisor/Kafdrop)：Kafdrop是一个用于监控Kafka集群的UI。
* [Mirus](https://github.com/salesforce/mirus)：Mirus是Kafka的跨数据中心数据复制工具，由Salesforce开源。
* [Kafdrop](https://github.com/obsidiandynamics/kafdrop)：Kafdrop是一个用于查看Kafka主题和浏览消费者组的Web UI。
* [Jikkou](https://github.com/streamthoughts/jikkou)：Jikkou是一款开源工具，旨在提供一种高效且简单的方法来管理、自动化和配置事件流平台上的资源。
* [Strimzi](https://github.com/strimzi/strimzi-kafka-operator)：Strimzi提供了一种在Kubernetes或OpenShift上以各种部署配置运行Kafka集群的方法，由RedHat开源。
* [Julie](https://github.com/kafka-ops/julie)：JulieOps帮助你自动化管理Kafka中的事物，从主题、配置到元数据，以及访问控制、模式。
* [Decaton](https://github.com/line/decaton)：Decaton是一个构建在Kafka之上的流式任务处理框架，由Line开源。
* [Kafka Console UI](https://gitee.com/xiaodong_xu/kafka-console-ui)：一款轻量级的kafka可视化管理平台，安装配置快捷、简单易用。
* [Kafka REST Proxy](https://github.com/confluentinc/kafka-rest)：Kafka REST Proxy为Kafka集群提供RESTful接口，它可以轻松地生成和消费数据、查看集群状态以及执行管理操作，而无需使用本机Kafka协议或客户端，由Confluent开源。
* [Reactor Kafka](https://github.com/reactor/reactor-kafka)：Reactor响应式Kafka驱动程序。
* [DoctorK](https://github.com/pinterest/DoctorK)：DoctorK是一个用于Kafka集群自动修复和工作负载均衡的服务，由Pinterest开源。
* [Kroxylicious](https://github.com/kroxylicious/kroxylicious)：Kroxylicious是Kafka协议代理，可解决加密、多租户和模式验证等用例
* [Chaperone](https://github.com/uber-archive/chaperone)：Chaperone作为Kafka审计系统，监控数据流的完整性和延迟，由Uber开源。
* [Azkarra Streams](https://github.com/streamthoughts/azkarra-streams)：Azkarra Streams是一个轻量级Java框架，可以轻松开发和操作Kafka Streams应用程序。
* [Kafka Helmsman](https://github.com/teslamotors/kafka-helmsman)：Kafka Helmsman是一个专注于自动化Kafka部署的工具，由特斯拉开源。
* [Kafbat UI](https://github.com/kafbat/kafka-ui)：Kafbat UI是一个免费的开源Web UI，用于监控和管理Kafka集群。
* [Klaw](https://github.com/Aiven-Open/klaw)：Klaw是一个自助式Kafka主题管理/治理工具/门户，由Aiven开源。
* [Astraea](https://github.com/opensource4you/astraea)：Astraea提供各式工具来降低Kafka使用门槛以及提高Kafka效能和资源使用率。
* [Kafka Web Console](https://github.com/cjmamo/kafka-web-console)：Kafka Web Console是一个用于监控Apache Kafka的Java Web应用程序。
* [Kafka Offset Monitor](https://github.com/Morningstar/kafka-offset-monitor)：这是一个用于监控Kafka消费者及其在日志中的位置(偏移量)的应用程序。

## 分布式开发

* [Waltz](https://github.com/wepay/waltz)：Waltz是一种基于仲裁的分布式预写日志，用于复制事务，由WePay开源。
* [Jepsen](https://github.com/jepsen-io/jepsen)：Jepsen致力于提高分布式数据库、队列、共识系统等的安全性。
* [Rapid](https://github.com/lalithsuresh/rapid)：Rapid是一种分布式成员服务，它允许一组进程轻松形成集群，并在成员资格发生变化时接收通知。
* [Low Level Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计。
* [Ordasity](https://github.com/boundary/ordasity)：Ordasity是Boundary用于在JVM上构建有状态集群服务的库。
* [Dhalion](https://github.com/microsoft/Dhalion)：Dhalion是一个用于自动扩展和调整分布式系统的框架，由Microsoft开源。
* [DSLabs](https://github.com/emichael/dslabs)：DSLabs是一个用于创建、测试、模型检查、可视化和调试分布式系统实验室作业的新框架，由华盛顿大学开发。
* [COMPSs](https://github.com/bsc-wdc/compss)：COMPSs是一种编程模型，旨在简化分布式基础设施(例如集群、网格和云)的应用程序开发，由巴塞罗那超级计算中心开源。
* [UNICORE](https://github.com/UNICORE-EU)：UNICORE是一个用于构建联合系统的软件套件，提供对高性能计算和数据资源的安全、无缝访问，由于利希研究中心开发。
* [Drasyl](https://github.com/drasyl/drasyl)：Drasyl是一个用于快速开发分布式应用程序的高性能框架，由汉堡大学开源。
* [Oracle Bedrock](https://github.com/coherence-community/oracle-bedrock)：Oracle Bedrock提供了一个通用Java框架，用于开发、编排和测试高度并发的分布式应用程序。
* [Apache Fluo](https://github.com/apache/fluo)：Fluo是一个分布式处理系统，允许用户对大型数据集进行增量更新，由美国国家安全局开源。
* [Fallout](https://github.com/datastax/fallout)：Fallout是一种用于运行本地或大规模远程分布式正确性、验证和性能测试的工具，由DataStax开源。
* [Narya](https://github.com/threerings/narya)：Narya提供了一个用于构建实时分布式系统的框架，重点支持多人在线游戏。

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
* [Jedis Lock](https://github.com/abelaska/jedis-lock)：Jedis Lock是一个使用Redis数据库和Jedis驱动实现的分布式锁，使用起来非常方便和简单。
* [Distributed Redis Tool](https://github.com/crossoverJie/distributed-redis-tool)：这是一个基于Redis的简单分布式工具。

#### 分布式ID

* [Snowflake](https://github.com/twitter-archive/snowflake)：Snowflake是一种网络服务，用于大规模生成唯一ID号并提供一些简单的保证，由Twitter开源。
* [Leaf](https://github.com/Meituan-Dianping/Leaf)：Leaf是美团开源的分布式ID生成服务。
* [Tinyid](https://github.com/didi/tinyid)：Tinyid是一个ID生成器服务，它提供了一个REST API和一个用于获取ids的Java客户端，由滴滴开源。
* [IdGenerator](https://github.com/yitter/IdGenerator)：IdGenerator是一个多语言的分布式ID生成库。
* [Icicle](https://github.com/intenthq/icicle)：Icicle是一个使用Redis的Lua脚本以分布式方式生成64位、可排序的唯一ID的项目，由Intent HQ开源。
* [Chronos](https://github.com/XiaoMi/chronos)：Chronos是实现高可用、高性能、提供全局唯一而且严格单调递增Timestamp的服务，由小米开源。
* [IdCenter](https://github.com/adyliu/idcenter)：IdCenter是用于生成唯一ID号的网络服务，由搜狐开源。
* [Sequence](https://gitee.com/yu120/sequence)：Sequence是一个高效GUID生成算法，基于Snowflake实现64位自增ID算法。
* [IDWorker](https://github.com/imadcn/idworker)：IDWorker是一个基于Zookeeper和雪花算法的分布式ID生成工具。
* [Redis ID Generator](https://github.com/hengyunabc/redis-id-generator)：基于Redis的分布式ID生成器。
* [UidGenerator](https://github.com/baidu/uid-generator)：UidGenerator是一个Java实现的、基于Snowflake的唯一ID生成器，由百度开源。
* [CosId](https://gitee.com/AhooWang/CosId)：CosId旨在提供通用、灵活、高性能的分布式ID生成器。
* [Cantor](https://github.com/ManbangGroup/cantor)：Cantor是一个全局序列生成器服务，具有分布式、无状态、高可用性，由满帮集团开源。
* [Java Snowflake](https://github.com/callicoder/java-snowflake)：基于雪花算法的分布式ID生成器。
* [SnowFlake](https://github.com/beyondfengyu/SnowFlake)：Twitter的雪花算法SnowFlake，使用Java语言实现。
* [Snowflake](https://github.com/downgoon/snowflake)：Twitter Snowflake的Java版本，一种用于大规模生成唯一ID号的Web服务，并具有一些简单的保证。
* [TSID Creator](https://github.com/f4b6a3/tsid-creator)：TSID Creator是用于生成TSID的Java库。
* [KSUID](https://github.com/ksuid/ksuid)：KSUID是一种生成全局唯一ID的方法，类似于RFC 4122 UUID。
* [Butterfly](https://github.com/simonalong/Butterfly)：Butterfly是一个超高性能的发号器框架。
* [Snowflake](https://github.com/relops/snowflake)：用于生成K阶唯一64位整数的Java库。
* [SnowflakeId](https://github.com/phxql/snowflake-id)：使用Java生成类似Twitter的Snowflake ID。

#### Session集群

* [Redis Session Manager](https://github.com/jcoleman/tomcat-redis-session-manager)：Session管理器实现，将Session存储在Redis中，以便在Tomcat服务器集群中轻松分发请求。
* [Mongo Tomcat Session Manager](https://github.com/simplicityitself/Mongo-Tomcat-Sessions)：这是一个Tomcat会话管理器，用于将会话保存到MongoDB中。
* [Spring Session](https://github.com/spring-projects/spring-session)：Spring Session提供了一个API和实现来管理用户的会话信息，同时也使得支持集群会话变得很简单，而无需绑定到应用程序容器特定的解决方案。
* [Memcached Session Manager](https://github.com/magro/memcached-session-manager)：Memcached Session Manager是一个Tomcat会话管理器，它将会话保存在Memcached或Redis中，以实现高可用性、可扩展性和容错性的Web应用程序。
* [Redis Session Manager](https://github.com/chexagon/redis-session-manager)：Tomcat 8会话管理器通过持久化到Redis提供会话复制。
* [Tomcat Clustering Redis Session Manager](https://github.com/ran-jit/tomcat-cluster-redis-session-manager)：Redis Session Manager是一个可插拔的管理器，它将会话存储到Redis中，以便轻松地在Tomcat服务器集群之间分发HTTP请求。
* [Mongo Tomcat Session Manager](https://github.com/simplicityitself/Mongo-Tomcat-Sessions)：这是一个Tomcat会话管理器，用于将会话保存到MongoDB中。
* [Jetty Session Redis](https://github.com/ovea-deprecated/jetty-session-redis)：使用Redis进行Jetty会话集群。
* [Amazon DynamoDB Session Manager](https://github.com/amazon-archives/aws-dynamodb-session-tomcat)：基于Amazon DynamoDB的Apache Tomcat会话存储。
* [Tomcat Session Manager](https://github.com/vmware-archive/session-managers)：Tomcat Session Manager的实现，将数据持久化到Redis中，由VMware开源。

#### Raft算法

* [KRaft](https://github.com/apache/kafka/tree/trunk/raft)：KRaft是基于Raft共识协议为Kafka量身定制的协议。
* [SOFAJRaft](https://github.com/sofastack/sofa-jraft)：SOFAJRaft是基于RAFT一致性算法的生产级高性能Java实现，支持MULTI-RAFT-GROUP，适用于高负载、低延迟的场景，由蚂蚁开源。
* [Raft Java](https://github.com/wenweihu86/raft-java)：Raft算法的简单Java实现。
* [Apache Ratis](https://github.com/apache/ratis)：Ratis是一个实现Raft协议的Java库。
* [Dledger](https://github.com/openmessaging/dledger)：Dledger是一个基于Raft的Java库，用于构建高可用、高持久、强一致的提交日志，由阿里开源。
* [Copycat](https://github.com/atomix/copycat)：Raft一致性算法的新颖实现，由Intel开源。
* [Gondola](https://github.com/YahooArchive/gondola)：Gondola是用Java编写的Raft协议的高性能实现，由Yahoo开源。
* [jGroups Raft](https://github.com/jgroups-extras/jgroups-raft)：jGroups Raft是Raft共识算法在JGroups中的实现。
* [xRaft](https://github.com/xnnyygn/xraft)：简单的Raft共识算法实现。
* [jRaft](https://github.com/datatechnology/jraft)：jRaft是Java中的Raft算法实现。
* [CKite](https://github.com/pablosmedina/ckite)：用Scala编写的Raft分布式共识算法的JVM实现。
* [Barge](https://github.com/mgodave/barge)：Raft共识协议的JVM实现。
* [LibRaft](https://github.com/allengeorge/libraft)：LibRaft是一个实现Raft分布式共识协议的Java库。
* [Dongting](https://github.com/dtprj/dongting)：Dongting项目是一个集成了Raft、配置服务器、消息队列、底层RPC的高性能引擎。
* [MicroRaft](https://github.com/MicroRaft/MicroRaft)：MicroRaft是Raft共识算法在Java中功能完整且稳定的开源实现。

#### Paxos算法

* [WPaxos](https://github.com/wuba/WPaxos)：WPaxos是Paxos一致性算法的生产级高性能Java实现，由58同城开源。
* [Essential Paxos](https://github.com/cocagne/paxos)：Essential Paxos提供了Paxos算法的基本实现。
* [Klein](https://github.com/shihuili1218/klein)：Klein是一个基于Paxos的分布式集合工具库，包括分布式缓存、分布式消息队列、分布式List、分布式Map、分布式锁等。
* [Paxos](https://github.com/jaksa76/paxos)：Paxos算法的Java实现。
* [Trex](https://github.com/trex-paxos/trex)：Trex是用于JVM的嵌入式Paxos引擎。
* [JPaxos](https://github.com/JPaxos/JPaxos)：JPaxos是一个Java库和运行时系统，用于构建高效的复制状态机，由洛桑联邦理工学院和波兹南理工大学开源。

#### Gossip算法

* [Apache Gossip](https://github.com/apache/incubator-retired-gossip)：Apache Gossip是一个基于Gossip协议的开源项目，旨在提供一个可靠、高效的分布式通信机制。
* [JGossip](https://github.com/monkeymq/jgossip)：Gossip协议的Java实现。
* [ScaleCube Cluster](https://github.com/scalecube/scalecube-cluster)：ScaleCube Cluster是一个轻量级的去中心化集群成员资格、故障检测和Gossip协议库。

## 数据库

这里包含使用Java编写的数据库软件。

#### 搜索引擎

* [ElasticSearch](https://github.com/elastic/elasticsearch)：Elasticsearch是一种分布式RESTful搜索引擎，针对生产规模工作负载的速度和相关性进行了优化。
* [Apache Lucene](https://github.com/apache/lucene)：Lucene是一个用Java编写的高性能、全功能的文本搜索引擎库。
* [Apache Solr](https://github.com/apache/solr)：Solr是一款流行、速度极快的开源搜索平台，基于Lucene构建。
* [OpenSearch](https://github.com/opensearch-project/OpenSearch)：OpenSearch是一个基于Lucene的分布式搜索和分析引擎，由Amazon主导。
* [EasySearch](https://infinilabs.cn/)：EasySearch是一个分布式的搜索数据库，实现非结构化数据检索、全文检索、向量检索、地理位置信息查询、组合索引查询、多语种支持、聚合分析等，由极限科技提供。
* [NixieSearch](https://github.com/nixiesearch/nixiesearch)：Nixiesearch是一个混合搜索引擎，可以根据你的数据进行微调，由Carrot Search开源。
* [Vespa](https://github.com/vespa-engine/vespa)：Vespa是一个开源的大规模分布式实时计算的向量和文本搜索引擎，Yahoo开发。
* [YaCy](https://github.com/yacy/yacy_search_server)：YaCy是一个完整的搜索引擎应用程序，包含托管搜索索引的服务器。
* [JVector](https://github.com/datastax/jvector)：JVector是一个纯Java嵌入式向量搜索引擎，由DataStax开源。
* [MarginaliaSearch](https://github.com/MarginaliaSearch/MarginaliaSearch)：Marginalia Search是一家瑞典运营的独立开源互联网搜索引擎。
* [Hibernate Search](https://github.com/hibernate/hibernate-search)：Hibernate Search自动从Hibernate ORM实体中提取数据，并将其推送到本地Apache Lucene索引或远程Elasticsearch/OpenSearch索引。
* [Linden](https://github.com/XiaoMi/linden)：Linden是一个构建在Lucene之上的分布式实时搜索系统，小米开源。
* [Fess](https://github.com/codelibs/fess)：Fess是一个非常强大且易于部署的企业搜索服务器，CodeLibs开源。
* [Zoie](https://github.com/senseidb/zoie)：Zoie是一个用Java编写的实时搜索/索引系统，由LinkedIn开源。
* [Scope](https://www.transwarp.cn/subproduct/scope)：Scope是星环第二代搜索引擎软件，可应用于表单、日志、视频、图像、文本文件等各类非结构化数据的对象存储与检索场景。
* [Cleo](https://github.com/LinkedInAttic/cleo)：Cleo是一个灵活的软件库，用于快速开发部分、无序和实时的预输入搜索，由LinkedIn开源。
* [OpenSearchServer](https://github.com/jaeksoft/opensearchserver)：OpenSearchServer是一款功能强大的、基于Lucene的企业级搜索引擎软件。
* [Bobo](https://github.com/senseidb/bobo)：Bobo是一个用Java编写的多面搜索引擎，由LinkedIn开源。
* [OpenK9](https://github.com/smclab/openk9)：OpenK9是一款完整的认知企业搜索解决方案，由SMC Treviso开源。
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
* [MG4J](https://mg4j.di.unimi.it/)：MG4J是一个用Java编写的免费全文搜索引擎，用于大型文档集合，由米兰大学开发。
* [Zulia](https://github.com/zuliaio/zuliasearch)：Zulia是一个实时分布式搜索和存储系统。
* [Egothor](https://egothor.sourceforge.net/)：Egothor是一个开源、高性能、功能齐全的文本搜索引擎，完全用Java编写。
* [Datafari](https://github.com/francelabs/datafari)：Datafari是一个开源企业搜索解决方案，由法国实验室开源。
* [Iveely](https://github.com/Fanping/iveely.search)：Iveely是纯Java实现的搜索引擎。

#### 图数据库

* [Neo4j](https://github.com/neo4j/neo4j)：Neo4j是世界领先的图数据库。
* [JanusGraph](https://github.com/JanusGraph/janusgraph)：JanusGraph是一个高度可扩展的图数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图进行了优化。
* [Apache HugeGraph](https://github.com/apache/incubator-hugegraph)：HugeGraph是一个速度快、高度可扩展的图数据库，该项目正在Apache基金会下孵化，最早由百度开源。
* [Titan](https://github.com/thinkaurelius/titan)：Titan是一个高度可扩展的图形数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图形进行了优化，由Aurelius开源。
* [Asami](https://github.com/threatgrid/asami)：用于Clojure和ClojureScript的图形数据库，由Cisco开发。
* [Amazon Neptune](https://aws.amazon.com/cn/neptune/)：Amazon Neptune是一个高性能图数据库，并对图的存储和查询进行了优化，可以存储数十亿个关系并将图形查询延迟降低到毫秒级。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型，被SAP收购。
* [Apache TinkerPop](https://github.com/apache/tinkerpop)：TinkerPop是一个面向实时事务处理(OLAP)以及批量、分析型图分析(OLTP)的图计算框架，诞生于洛斯阿拉莫斯国家实验室。
* [GraphDB](https://www.ontotext.com/)：GraphDB是一个企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：ArcadeDB多模型数据库，一种支持SQL、Cypher、Gremlin、HTTP/JSON、MongoDB和Redis的DBMS。
* [Stardog](https://www.stardog.com/)：Stardog是一款商业图数据库。
* [StellarDB](https://www.transwarp.cn/product/stellardb)：StellarDB是一款为企业级图应用而打造的分布式图数据库，由星环开发。
* [Apache Giraph](https://giraph.apache.org/)：Giraph是一个专为高可扩展性而构建的迭代图处理系统，Facebook基于Pregel思想的开源实现。
* [InfiniteGraph](http://www.objectivity.com/products/infinitegraph/)：InfiniteGraph是一个用Java和C++实现的分布式图数据库，这是Objectivity公司的产品。
* [AnzoGraph](https://cambridgesemantics.com/anzograph/)：AnzoGraph是为在线分析和数据协调而构建的水平可扩展图数据库。
* [Galaxybase](https://galaxybase.com/)：Galaxybase是浙江创邻科技公司研发的分布式图数据库产品。
* [YouTrackDB](https://github.com/JetBrains/youtrackdb)：YouTrackDB是一个面向对象的图数据库，支持文档、全文搜索、响应性和地理空间概念，由JetBrains开源。
* [BlazeGraph](https://github.com/blazegraph/database)：Blazegraph是一个超高性能图数据库，支持蓝图和RDF/SPARQL API。
* [Gaffer](https://github.com/gchq/Gaffer)：Gaffer是一个图数据库框架，它允许存储在节点和边上包含丰富属性的非常大的图，由英国政府通讯总部开源。
* [TypeDB](https://github.com/vaticle/typedb)：TypeDB是一个多态数据库，具有概念数据模型、强大的子类型系统、符号推理引擎和美观优雅的类型理论语言TypeQL，由Vaticle Ltd开发。
* [HyperGraphDB](https://github.com/hypergraphdb/hypergraphdb)：HyperGraphDB是专为人工智能和语义Web项目设计的图数据库，也可以用作各种规模项目的嵌入式面向对象数据库。
* [FlockDB](https://github.com/twitter-archive/flockdb)：FlockDB是一个用于存储邻接列表的分布式图数据库，由Twitter开源。
* [YangDB](https://github.com/YANG-DB/yang-db)：YangDB是一个开源、可扩展、非原生图数据库(由Elasticsearch提供支持)。
* [GalaxyBase](https://galaxybase.com/)：GalaxyBase国产的高性能图数据库。
* [ONgDB](https://github.com/graphfoundation/ongdb)：ONgDB是一个开源、高性能、原生图存储，由Graph基金会开发。
* [Bitsy](https://github.com/lambdazen/bitsy)：Bitsy是一个小型、快速、可嵌入、持久的内存图数据库，与Tinkerpop3兼容。
* [OverflowDB](https://github.com/ShiftLeftSecurity/overflowdb)：OverflowDB是一个低内存占用的内存图数据库，由ShiftLeft开源。
* [OhmDB](https://github.com/ohmdb/ohmdb)：OhmDB提供了关系数据库的强大功能和NoSQL数据库的灵活性。
* [Aerospike Graph](https://aerospike.com/products/graph-database/)：Aerospike Graph是一种高性能分布式图形数据库，商业软件。
* [AutomataLib](https://github.com/LearnLib/automatalib)：AutomataLib是一个免费的开源Java库，用于对自动机、图形和转换系统进行建模，由德国多特蒙德工业大学开发。
* [HGraphDB](https://github.com/rayokota/hgraphdb)：HGraphDB是使用HBase作为图数据库的客户端层。
* [StarGraph](https://github.com/Lambda-3/Stargraph)：StarGraph是一个用于查询大型知识图的图数据库，由帕绍大学开源。
* [Apache S2Graph](https://github.com/apache/incubator-s2graph)：S2Graph是一个基于HBase构建的分布式、可扩展的OLTP图数据库，支持超大图的快速遍历。
* [Fluree](https://github.com/fluree/db)：Fluree是一个不可变、时态、账本支持的语义图数据库，具有云原生架构。
* [Segrada](https://github.com/mkalus/segrada)：Segrada是一个用于研究和文献的语义图数据库。

#### RDF数据库

* [GraphDB](https://www.ontotext.com/)：GraphDB是一个企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。
* [BlazeGraph](https://github.com/blazegraph/database)：Blazegraph是一个超高性能图数据库，支持蓝图和RDF/SPARQL API。
* [AllegroGraph](https://allegrograph.com/)：AllegroGraph是一个闭源的三元组存储，也可用作文档存储，目前用于美国国防部项目。
* [qEndpoint](https://github.com/the-qa-company/qEndpoint)：qEndpoint是一个高度可扩展的三元存储，具有全文和GeoSPARQL支持。
* [Parliament](https://github.com/raytheonbbn/parliament)：Parliament是专为语义网设计的高性能三元存储和推理器，由雷神公司开源。
* [Apache Rya](https://github.com/apache/rya)：Rya是一个可扩展的RDF存储，它构建在列式索引存储(例如Accumulo)之上，它作为RDF4J的扩展来实现，以提供简单的查询机制(SPARQL、SERQL等)和RDF数据存储(RDF/XML、NTriples等)。
* [Halyard](https://github.com/Merck/Halyard)：Halyard是一个高度水平扩展的三元组存储系统，支持命名图，旨在集成超大规模语义数据模型，并存储和查询完整的关联数据宇宙快照，由默克公司开源。
* [ERGS](https://github.com/IBM/expressive-reasoning-graph-store)：ERGS是一个基于属性图架构构建的OWL推理器和RDF三元组存储，由IBM开源。
* [Strabon](https://strabon.di.uoa.gr/)：Strabon是一个完全实现的语义地理空间数据库系统，由雅典大学开源。
* [Mulgara](http://www.mulgara.org/)：Mulgara是一个完全用Java编写的快速RDF数据库。

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
* [KVDB](https://github.com/jd-opensource/jdchain-kvdb)：KVDB是一个简单的NoSQL数据库，支持简单的键值读写操作，由京东开源。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：LMDB是一种使用B+树的有序、嵌入式、持久的键值存储。
* [Doris](https://github.com/itisaid/Doris)：Doris是大规模分布式KV存储系统，由阿里开源。
* [Adama](https://github.com/mathgladiator/adama-lang)：Adama是一个开源、响应式、无服务器、隐私优先、面向文档、以计算为中心的键值存储系统。
* [PalDB](https://github.com/linkedin/PalDB)：PalDB是一个用Java编写的嵌入式一次性写入键值存储，由LinkedIn开源。
* [HaloDB](https://github.com/yahoo/HaloDB)：HaloDB是一个用Java编写的快速且简单的嵌入式键值存储，由Yahoo开源。
* [JustinDB](https://github.com/justin-db/JustinDB)：JustinDB是一个最终一致的键值数据库，有利于写入可用性。
* [Voldemort](https://github.com/voldemort/voldemort)：Voldemort是一个分布式键值存储系统，Amazon Dynamo的开源克隆，由LinkedIn开源。
* [SwayDB](https://github.com/simerplaha/SwayDB)：用于JVM的持久内存键值存储引擎，旨在实现高性能和资源效率。
* [BabuDB](https://github.com/xtreemfs/babudb)：BabuDB是一个嵌入式非关系型数据库系统，由柏林自由大学开源。
* [BBoxDB](https://github.com/jnidzwetzki/bboxdb)：BBoxDB是一个高可用的分布式存储管理器，旨在处理多维大数据。
* [CurioDB](https://github.com/stephenmcd/curiodb)：CurioDB是一个分布式持久Redis克隆，使用Scala和Akka构建。
* [TreodeDB](https://github.com/Treode/store)：TreodeDB是一个提供多行原子写入的分布式数据库，它专为RESTful服务而设计。
* [Hank](https://github.com/LiveRamp/hank)：Hank是LiveRamp构建和使用的一个非常快速且非常紧凑的分布式键值NoSQL数据库。
* [WaspDB](https://github.com/rehacktive/waspdb)：WaspDB是一个适用于Android的纯Java键值对数据库库。
* [FastKV](https://github.com/BillyWei01/FastKV)：FastKV是用Java编写的高效可靠的键值存储库，专为Android平台优化。
* [LSM Tree](https://github.com/indeedeng/lsmtree)：LSM Tree是一种快速键/值存储，对于大容量随机访问读写非常有效，由Indeed开发。
* [Distkv](https://github.com/distkv-project/distkv)：Distkv是一个具有表概念的轻量级分布式键值数据库系统。
* [Chronos](https://github.com/Txture/chronos)：该项目致力于为Java虚拟机提供高效易用的版本化数据库持久化解决方案。
* [Prithvi](https://github.com/psidh/Prithvi)：Prithvi是一个用Java从头构建的内存键值数据库，不依赖外部框架。
* [PufferDB](https://github.com/adrielcafe/pufferdb)：PufferDB是一个键值存储，由Protobuf和协程提供支持。
* [KVault](https://github.com/Liftric/KVault)：KVault是Kotlin多平台项目的安全键值存储。
* [Riffle](https://github.com/Factual/riffle)：Riffle是一种只读键/值存储格式。
* [HeftyDB](https://github.com/jordw/heftydb)：HeftyDB是一个适用于JVM的持久化、排序的键值对库。
* [Remember](https://github.com/tumblr/Remember)：适用于Android的由共享偏好支持的内存数据存储，由Tumblr开源。
* [MPH Table](https://github.com/indeedeng/mph-table)：MPH Table是一种不可变的键/值存储，具有高效的空间利用率和快速读取性能，由Indeed开源。
* [Lu Raft KV Storage](https://github.com/stateIs0/lu-raft-kv)：这是一个Java版本的Raft KV分布式存储实现。

#### 数据网格

* [GemFire](https://www.vmware.com/products/app-platform/tanzu-gemfire)：GemFire是一个分布式内存数据管理平台，专为高性能和低延迟的实时应用程序而设计，由VMware开发。
* [Apache Geode](https://github.com/apache/geode)：Geode是一个数据管理平台，可在广泛分布的云架构中提供对数据密集型应用程序的实时、一致的访问，由GemStone开源。
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
* [Timely](https://github.com/NationalSecurityAgency/timely)：Timely是一个时序数据库应用程序，可提供对时序数据的安全访问，由美国国家安全局开源。
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是一种物联网原生数据库，具有高性能的数据管理和分析能力，可部署在边缘和云端，该项目由清华大学主导。
* [Newts](https://github.com/OpenNMS/newts)：Newts是一个基于Cassandra的时序数据存储。
* [RRD4J](https://github.com/rrd4j/rrd4j)：RRD4J是一个用于时序数据的高性能数据记录和图形系统，用Java实现RRDTool的功能。
* [Heroic](https://github.com/spotify/heroic)：Heroic是一个开源监控系统，最初是在Spotify构建的，旨在解决大规模收集和近实时指标分析所面临的问题。
* [FiloDB](https://github.com/filodb/FiloDB)：FiloDB是一个开源分布式、实时、内存中、大规模可扩展、多模式时序/事件/操作数据库，具有Prometheus查询支持和一些Spark支持。
* [Khronus](https://github.com/khronus/khronus)：Khronus是一个开源、分布式且响应式的时序数据库，旨在存储、检索、分析和处理大量自定义指标，由Despegar开源。
* [Axibase](https://axibase.com/docs/atsd/finance/)：HBase之上的集成时序数据库，具有内置可视化、规则引擎和SQL支持。
* [TimeBase](https://github.com/finos/TimeBase-CE)：TimeBase是Deltix公司开发的高性能时序数据库。
* [ChronixDB](https://github.com/ChronixDB/chronix.server)：高效、快速的时序存储。
* [Warp 10](https://github.com/senx/warp10-platform)：Warp 10是一个专为物联网设计的模块化开源平台，可收集、存储并允许你分析传感器数据。
* [Yuvi](https://github.com/pinterest/yuvi)：Yuvi是一个用于存储近期时序指标数据的内存存储引擎，由Pinterest开源。

#### 嵌入式数据库

* [H2](https://github.com/h2database/h2database)：H2是一个用Java编写的嵌入式RDBMS。
* [Apache Derby](https://github.com/apache/derby)：Derby是一个开源的嵌入式关系型数据库，完全使用Java语言实现，由IBM开发。
* [HSQLDB](https://hsqldb.org/)：HSQLDB是领先的用Java编写的SQL关系数据库系统。
* [Chronicle](https://github.com/peter-lawrey/Java-Chronicle)：Chronicle是一个超低延迟、高吞吐量、持久化、消息传递和事件驱动的内存数据库。
* [QuickIO](https://github.com/artbits/quickio)：QuickIO是一个Java嵌入式数据库，底层基于LevelDB引擎和Java NIO设计，并使用Protostaff来序列化/反序列化数据。
* [Eclipse Store](https://github.com/eclipse-store/store)：EclipseStore是一个突破性的Java原生持久层，专为云原生微服务和Serverless应用程序而构建。
* [MapDB](https://github.com/jankotek/mapdb)：MapDB提供由磁盘存储或堆外内存支持的并发Map、Set、List和Queue，它是一个快速且易于使用的嵌入式Java数据库引擎。
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
* [Krati](https://github.com/jingwei/krati)：Krati是一个简单的持久数据存储，具有极低的延迟和高吞吐量。

#### 关系型数据库

* [PolarDB-X](https://github.com/polardb/polardbx-sql)：PolarDB-X是一款云原生分布式SQL数据库，专为高并发、海量存储、复杂查询场景而设计，由阿里开源。
* [Mycat](https://github.com/MyCATApache/Mycat-Server)：MyCAT是一个支持事务和ACID的MySQL替代型增强型数据库。
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db)：YugabyteDB是一个高性能、云原生、分布式SQL数据库，旨在支持所有PostgreSQL功能。
* [FoundationDB Record Layer](https://github.com/FoundationDB/fdb-record-layer)：Record Layer是一个Java API，在FoundationDB之上提供面向记录的存储，大致相当于一个简单的关系型数据库，由Apple开源。
* [VoltDB](https://www.voltactivedata.com/)：VoltDB是一种水平可扩展的内存中SQL RDBMS，专为具有极高读写吞吐量要求的应用程序而设计，这是MIT、斯坦福合作的一个研究项目。
* [NuoDB](https://www.3ds.com/nuodb-distributed-sql-database/)：NuoDB是一个分布式云原生数据库管理系统，具有丰富的SQL实现并完全支持兼容事务，由达索开发。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：ArcadeDB是一个多模型DBMS，能够在通用硬件上每秒处理数百万条记录，并使用最少的资源。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Deephaven Community](https://github.com/deephaven/deephaven-core)：Deephaven Community是一个实时、时序、面向列的分析引擎，具有关系型数据库功能。
* [KarelDB](https://github.com/rayokota/kareldb)：KarelDB是一个由Kafka支持的全功能关系型数据库。
* [SimpleDB](https://github.com/iamxpy/SimpleDB)：加州大学伯克利分校的数据库课程CS186实现。
* [Simple DB HW 2021](https://github.com/MIT-DB-Class/simple-db-hw-2021)：MIT数据库课程6.830实现。
* [TMDB](https://github.com/whu-totemdb/tmdb)：武汉大学移动端Totem数据库系统。
* [MYDB](https://github.com/senshinya/MYDB)：MYDB是一个Java实现的简单的数据库，部分原理参照自MySQL、PostgreSQL和SQLite。
* [AntsDB](https://github.com/waterguo/antsdb)：AntsDB是HBase的低延迟、高并发虚拟SQL层。
* [Wasp](https://github.com/alibaba/wasp)：Wasp是类Google MegaStore & F1的分布式关系型数据库，由阿里开源。
* [Sqlg](https://github.com/pietermartin/sqlg)：Sqlg是Tinkerpop3在RDBMS上的实现，支持H2、HSQLDB、Postgresql。
* [VanillaDB](https://github.com/vanilladb/vanillacore)：VanillaCore是一个单节点、多线程关系数据库引擎，部分支持SQL-92标准，并通过JDBC、嵌入或(基于Java的)存储过程提供连接。
* [SkinnerDB](https://github.com/cornelldbgroup/skinnerdb)：SkinnerDB是一个用于数据分析的关系型数据库管理系统，由康奈尔数据库小组开发。
* [CreatorDB](https://github.com/CreatorsStack/CreatorDB)：CreatorDB是一个DBMS数据库管理系统，包含存储、算子、优化、事务、索引等。
* [Interference](https://github.com/interference-project/interference)： Interference是一个简单的Java框架，它允许你在Java应用程序中启动分布式数据库和复杂的事件处理服务，并使用类似JPA的接口和注解进行结构映射和数据操作。

#### NoSQL数据库

* [Amazon DynamoDB](https://aws.amazon.com/dynamodb)：Amazon DynamoDB是一种无服务器、NoSQL、完全托管的数据库，在任何规模下都具有个位数毫秒的性能。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：HBase是一个开源、分布式、版本化、面向列的存储，这是Google Bigtable的开源版本。
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是时序数据的数据管理系统，为用户提供数据采集、存储、分析等特定服务，该项目由清华大学主导。
* [Apache Ignite](https://github.com/apache/ignite)：Ignite是一个分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是一个开源多模型NoSQL DBMS，支持原生图、文档、全文搜索、响应式、地理空间和面向对象的概念。
* [Oracle NoSQL](https://github.com/oracle/nosql)：Oracle NoSQL数据库让开发人员能够轻松使用文档、固定模式和键值数据库模型构建应用。
* [Paper](https://github.com/pilgr/Paper)：Paper是Android上Java/Kotlin对象的快速类NoSQL存储，具有自动模式迁移支持。
* [Lealone](https://github.com/lealone/Lealone)：Lealone是一个高性能的面向OLTP场景的关系型数据库，由阿里开源。
* [ToroDB](https://github.com/torodb/server)：ToroDB是一个运行在RDBMS之上的开源NoSQL数据库。
* [Concourse](https://github.com/cinchapi/concourse)：Concourse是一个分布式数据库仓库，用于跨时间的事务搜索和分析，由Cinchapi开源。
* [ElephantDB](https://github.com/nathanmarz/elephantdb)：ElephantDB是一个专门从Hadoop导出键/值数据的数据库。
* [Elassandra](https://github.com/strapdata/elassandra)：Elassandra是一个Cassandra发行版，包括Elasticsearch搜索引擎。
* [Sensei](https://github.com/LinkedInAttic/sensei)：Sensei是一个分布式、弹性的实时可搜索数据库，由LinkedIn开源。
* [Stampede](https://github.com/torodb/stampede)：Stampede是一个开源的高性能、分布式PostgreSQL兼容的JSON文档数据库。
* [LevelDB](https://github.com/dain/leveldb)：Java中LevelDB的重写，此目标是拥有一个功能完整的实现，其性能与C++原始版本的性能相差不超过10%，并生成C++代码的逐字节精确副本。
* [Eva](https://github.com/Workiva/eva)：Eva是一个分布式数据库系统，实现了时间感知、累积和原子一致的实体属性值数据模型，由Workiva开源。
* [CorfuDB](https://github.com/CorfuDB/CorfuDB)：Corfu是一个围绕共享日志抽象设计的一致性平台。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源数据网格平台和高度可扩展的NoSQL云数据存储，由RedHat开源。
* [BlobCityDB](https://github.com/blobcity/db)：BlobCityDB是一种一体化数据库，它支持本地存储17种不同格式的数据，包括JSON、XML、CSV、PDF、Word、Excel、Log、GIS、图像等。
* [EvitaDB](https://github.com/FgForrest/evitaDB)：EvitaDB是一个低延迟的NoSQL内存引擎，可以处理电子商务系统每天必须处理的所有复杂任务，由FG Forrest和赫拉德茨克拉洛韦大学开源。
* [Terrastore](https://code.google.com/archive/p/terrastore/)：Terrastore是一个现代文档存储，它提供先进的可扩展性和弹性功能，而不牺牲一致性。
* [JasDB](https://github.com/oberasoftware/jasdb)：JasDB是一款超快的多平台NoSQL数据库，可以嵌入到你的软件中或进行扩展，并且还具有完整的Android支持。
* [InfinityDB](https://boilerbay.com/infinitydb/manual/)：InfinityDB Embedded是一个Java NoSQL DBMS组件，其灵活性远超文档数据库，由加州大学开源。
* [Kronotop](https://github.com/kronotop/kronotop)：Kronotop是一个与Redis兼容的分布式事务文档数据库，由FoundationDB支持。
* [KitDB](https://github.com/frost373/KitDB)：KitDB是一个内嵌式持久型的高速NoSQL存储库，以jar包方式嵌入到应用中。
* [Android NoSQL](https://github.com/florent37/Android-NoSql)：适用于Android的轻量级、简单结构化的NoSQL数据库。
* [Kodein](https://github.com/kosi-libs/Kodein-DB)：多平台NoSQL数据库。

#### OLAP数据库

* [Apache Druid](https://github.com/apache/druid)：Druid是一个高性能、实时分析数据库，可在大规模和负载下对流式和批处理数据提供亚秒级查询，由MetaMarkets开源。
* [Apache Doris](https://github.com/apache/doris)：Doris是一个基于MPP架构的易于使用、高性能、实时分析的数据库，由百度开源。
* [StarRocks](https://github.com/StarRocks/starrocks)：StarRocks是下一代数据平台，旨在使数据密集型实时分析变得快速、轻松，由百度Doris团队成员开源。
* [Apache Pinot](https://github.com/apache/pinot)：Pinot是一种实时分布式OLAP数据存储，由LinkedIn开源。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Datacube](https://github.com/urbanairship/datacube)：具有数值数据汇总的多维数据存储，由Airship开源。

#### 向量数据库

* [Vespa](https://github.com/vespa-engine/vespa)：Vespa是一个开源的大规模分布式实时计算的向量和文本搜索引擎，Yahoo开发。
* [ObjectBox](https://github.com/objectbox/objectbox-java)：ObjectBox Java是一款轻量级但功能强大的设备端数据库和向量数据库，专为Java和Kotlin应用程序设计。
* [DingoDB](https://github.com/dingodb/dingo)：DingoDB是由DataCanvas设计和开发的开源分布式多模态向量数据库。
* [Simbase](https://github.com/guokr/simbase)：Simbase是一个类似Redis的向量相似度数据库，由果壳科技开源。
* [Cottontail](https://github.com/vitrivr/cottontaildb)：CottontailDB是一个旨在多媒体检索的列存储，它允许经典的布尔和向量空间检索，即相似性搜索中使用的最近邻查找，由巴塞尔大学开源。
* [VectoRex](https://gitee.com/giteeClass/VectoRex)：VectoRex是一个纯Java实现的高性能、可扩展的向量搜索引擎，专为现代AI和大数据应用设计。
* [Research4j](https://github.com/bhavuklabs/research4j)：Research4j是一个功能全面的Java库，它通过智能查询分析、动态引文获取、自适应推理策略以及无缝LLM集成来实现研究工作流程的自动化。

#### 对象数据库

* [Perst](https://www.mcobject.com/perst/)：Perst是McObject的开源、面向对象的嵌入式数据库系统。
* [ObjectDB](https://www.objectdb.com/)：ObjectDB是Java的对象数据库，可以在客户端-服务器模式和嵌入式模式下使用。
* [Atoti](https://www.atoti.io/)：Atoti是一个数据分析平台，集一流的计算引擎、可视化套件和实时OLAP多维数据集于一体，由ActiveViam开发。
* [ZooDB](https://github.com/tzaeschke/zoodb)：ZooDB是一个基于JDO 3.0标准的面向对象数据库。

#### XML数据库

* [EXistDB](https://github.com/eXist-db/exist)：EXistDB是一个高性能开源原生XML数据库，完全围绕XML技术构建的NoSQL文档数据库和应用程序平台。
* [BaseX](https://github.com/BaseXdb/basex)：BaseX是一款功能强大、性能卓越的XML数据库引擎，同时也是一款高度兼容的XQuery处理器，全面支持W3C更新和全文扩展。
* [Elemental](https://github.com/evolvedbinary/elemental)：Elemental是一个专为处理文档而设计的NoSQL数据库。

#### Datalog数据库

* [DataScript](https://github.com/tonsky/datascript)：Clojure和ClojureScript中的不可变内存数据库和Datalog查询引擎。
* [Datomic](https://www.datomic.com/)：Datomic是一个分布式数据库和Datalog的实现。
* [Datalevin](https://github.com/juji-io/datalevin)：Datalevin是一个简单持久的Datalog数据库。
* [Datahike](https://github.com/replikativ/datahike)：Datahike是一个持久的Datalog数据库，由高效的Datalog查询引擎提供支持。

#### OLTP数据库

* [H-Store](https://github.com/apavlo/h-store)：H-Store是一个实验性主存并行数据库管理系统，针对OLTP应用程序进行了优化，由MIT、布朗大学、CMU、耶鲁大学和英特尔合作开发。
* [FaunaDB](https://github.com/fauna/faunadb)：FaunaDB是一个强一致性OLTP数据库，具有可通过NoSQL查询语言(FQL)访问的混合文档关系数据模型。

#### 其他数据库

* [XTDB](https://github.com/xtdb/xtdb)：XTDB是一个具有双时态索引的通用数据库。
* [ArgoDB](https://www.transwarp.cn/product/argodb)：ArgoDB是星环科技研发的分布式数据库，融合了高并发事务处理和实时分析能力，横向灵活扩展满足业务的弹性变化需求。
* [JsonDB](https://github.com/Jsondb/jsondb-core)：JsonDB是一个纯Java数据库，它将数据存储为Json文件。
* [Cloudant Sync](https://github.com/cloudant/sync-android)：适用于Android应用程序的基于JSON的文档数据存储，由Cloudant开源。
* [Instant](https://github.com/instantdb/instant)：Instant是一个客户端数据库，可以轻松构建Notion或Figma等实时协作应用程序，由Facebook和Airbnb开源。
* [Astra DB](https://www.datastax.com/products/datastax-astra)：Astra DB为开发人员提供了创建强大AI应用程序所需的工具，包括API、实时数据处理和集成，由Datastax开发。
* [SnappyData](https://github.com/TIBCOSoftware/snappydata)：SnappyData是一个分布式、内存优化分析数据库。
* [VDJDB](https://github.com/antigenomics/vdjdb-db)：VDJDB是一个精选的具有已知抗原特异性的T细胞受体(TCR)序列数据库，最初由俄罗斯皮罗戈夫国立研究医科大学和中欧理工学院开源。
* [KSqlDB](https://github.com/confluentinc/ksql)：KSqlDB是一个用于在Kafka之上构建流处理应用程序的数据库，由Confluent开源。
* [Polypheny-DB](https://github.com/polypheny/Polypheny-DB)：Polypheny-DB是一种自适应Polystore，可提供对异构数据的成本和工作负载感知访问，最初是巴塞尔大学的一个研究项目。
* [EmoDB](https://github.com/bazaarvoice/emodb)：EmoDB是一个RESTful HTTP服务器，用于存储JSON对象并监视这些事件的更改，由Bazaarvoice开源。
* [RSQLDB](https://github.com/alibaba/rsqldb)：RSQLDB是一个基于RocketMQ的流处理数据库，由阿里开源。
* [Apollo Delphinius](https://github.com/salesforce/apollo)：Apollo Delphinius项目是一个实验性多租户分布式系统平台，由Salesforce开源。
* [GeoDesk](https://github.com/clarisma/geodesk)：GeoDesk是一个用于OpenStreetMap数据的快速且存储高效的地理空间数据库。
* [CubeDB](https://github.com/cubedb/cubedb)：CubeDB是一个简单、快速的内存多键计数器存储。

## 数据库中间件

这里列出数据库相关的中间件。

#### 数据同步

* [ChunJun](https://github.com/DTStack/chunjun)：ChunJun是基于Flink的批流统一打造的数据同步工具，可以实现各种异构数据源之间的数据同步和计算，由袋鼠云开源。
* [DataX](https://github.com/alibaba/DataX)：DataX是阿里云DataWorks数据集成的开源版本，在阿里内被广泛使用的离线数据同步工具/平台。
* [DataX Web](https://github.com/WeiYe-Jing/datax-web)：DataX Web是在DataX之上开发的分布式数据同步工具，提供简单易用的操作界面。
* [Porter](https://gitee.com/sxfad/porter)：Porter是一款数据同步中间件，主要用于解决同构/异构数据库之间的表级别数据同步问题，由随行付开源。
* [Tunnel](https://github.com/hellobike/tunnel)：Tunnel是一个将PostgreSQL的实时数据同步到ES或Kafka的服务，哈啰单车开源。
* [DBSyncer](https://gitee.com/ghi/dbsyncer)：DBSyncer是一款开源的数据同步中间件，提供MySQL、Oracle、SqlServer、PostgreSQL、ES、Kafka、File、SQL等同步场景。
* [Otter](https://github.com/alibaba/otter)：Otter是阿里开源的一个分布式数据库同步系统，尤其是在跨机房数据库同步方面有很强大的功能。
* [Puma](https://github.com/dianping/puma)：Puma可以获取数据库的变更并通过消息方式发布，并且可以实现数据库同步，由大众点评开源。
* [DRC](https://github.com/ctripcorp/drc)：DRC是携程框架架构研发部数据中心组推出的用于数据双向或多向复制的数据库中间件。
* [Morf](https://github.com/alfasoftware/morf)：Morf是一个用于跨平台演化关系型数据库机制、数据库访问和数据库成像/克隆的库，由Alfa开源。
* [ReplicaDB](https://github.com/osalvador/ReplicaDB)：ReplicaDB是用于数据库复制的开源工具，旨在在关系型数据库和NoSQL数据库之间高效传输批量数据。
* [Yugong](https://github.com/alibaba/yugong)：Yugong是阿里开源的去Oracle数据迁移同步工具。
* [Tapdata](https://github.com/tapdata/tapdata)：Tapdata是一个实时数据集成平台，可以实现数据库、SaaS服务、应用程序、文件等各种系统之间的数据实时同步，由钛铂数据开源。
* [SymmetricDS](https://github.com/JumpMind/symmetric-ds)：SymmetricDS是数据库复制和文件同步软件，它独立于平台、支持Web且与数据库无关，由JumpMind开源。
* [DataLink](https://github.com/ucarGroup/DataLink)：DataLink是一个满足各种异构数据源之间的实时增量同步、离线全量同步，分布式、可扩展的数据交换平台，由神州优车开源。
* [DBSwitch](https://gitee.com/dromara/dbswitch)：DBSwitch工具提供源端数据库向目的端数据库的批量迁移同步功能，支持数据的全量和增量方式同步，由dromara社区开源。
* [Mongeez](https://github.com/mongeez/mongeez)：Mongeez允许你管理Mongo文档的更改，并在执行部署时与代码更改同步传播这些更改。
* [DataLoader](https://github.com/forcedotcom/dataloader)：DataLoader是一个客户端应用程序，用于批量导入或导出数据，由Salesforce开源。
* [Redis Replicator](https://github.com/leonchen83/redis-replicator)：Redis Replicator是一个Redis复制工具，支持同步、psync、psync2，可以解析RDB、AOF、混合RDB和AOF文件。
* [RedisSyncer](https://github.com/TraceNature/redissyncer-server)：RedisSyncer是一个Redis多任务同步工具集，应用于Redis单实例及集群同步。
* [MyDataHarbor](https://gitee.com/mydataharbor/mydataharbor)：MyDataHarbor是一个致力于解决异构数据源之间的分布式、高扩展性、高性能、事务级的数据同步中间件。
* [Canal MySQL NoSQL Sync](https://github.com/liukelin/canal_mysql_nosql_sync)：基于Canal的MySQL、RabbitMQ、Redis/Memcached/MongoDB同步工具。
* [AMPLI SYNC](https://github.com/sqlite-sync/SQLite-sync.com)：AMPLI-SYNC是一个用于在Sqlite和MS SQL/MySQL/Oracle/PostgreSQL数据库之间同步数据的框架。
* [DatalinkX](https://gitee.com/atuptown/datalinkx)：基于Flink的异构数据源同步。
* [ReAir](https://github.com/airbnb/reair)：ReAir是一套易于使用的工具，用于在Hive数据仓库之间复制表和分区，由Airbnb开源。
* [Bireme](https://github.com/HashDataInc/bireme)：Bireme是Greenplum/HashData数据仓库的增量同步工具，目前支持MySQL、PostgreSQL和MongoDB数据源。
* [LinkUp](https://gitee.com/wei_fu_wan/link-up)：LinkUp是一款开箱即用的数据同步工具，深度集成Apache SeaTunnel，提供从自动建表、任务调度到日志监控的全链路能力，界面直观，非技术人员也能轻松上手。

#### 分库分表

* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：ShardingSphere是一种分布式SQL事务和查询引擎，允许在任何数据库上进行数据分片、扩展、加密等，由当当网开源。
* [Cobar](https://github.com/alibaba/cobar)：Cobar是分库分表的代理，兼容MySQL协议和MySQL SQL语法，底层存储仅支持MySQL，支持前台业务更简单、稳定、高效、安全，由阿里开源。
* [TSharding](https://github.com/baihui212/tsharding)：TSharding是蘑菇街交易平台使用的简单分片组件。
* [DBLE](https://github.com/actiontech/dble)：DBLE是由爱可生开发的一种高扩展性的MySQL分片中间件。
* [TDDL](https://github.com/alibaba/tb_tddl)：TDDL是一个分布式数据库中间件，主要是为了解决分布式数据库产生的相关问题，由阿里开源。
* [Gizzard](https://github.com/twitter-archive/gizzard)：Gizzard是用于创建最终一致的分布式数据存储的灵活分片框架，由Twitter开源。
* [Mycat2](https://github.com/MyCATApache/Mycat2)：Mycat2是Mycat社区开发的一款分布式关系型数据库中间件。
* [Heisenberg](https://github.com/brucexx/heisenberg)：Heisenberg是百度开源的一款基于MySQL协议之上的分库分表中间件，支持各种灵活的分库分表规则。
* [Zdal](https://github.com/xie-summer/zdal)：Zdal是支付宝自主研发的数据中间件产品，采用标准的JDBC规范。
* [Shark](https://github.com/gaoxianglong/shark)：Shark是一个分布式MySQL分库分表中间件。
* [Zebra](https://github.com/Meituan-Dianping/Zebra)：Zebra是一个基于JDBC API协议上开发出的高可用、高性能的数据库访问层解决方案，是美团点评内部使用的数据库访问层中间件。
* [Baymax](https://github.com/tongbanjie/baymax)：Baymax是铜板街开发的轻量级分库分表框架，支持多库多表。
* [Sharding Method](https://github.com/QNJR-GROUP/sharding-method)：Sharding Method是服务层Sharding框架，全SQL、全数据库兼容，由齐牛金融开源。
* [Compass](https://github.com/sogou-biztech/compass)：Compass是搜狗商业平台研发部开发的一套轻量级分布式数据库访问框架。
* [Oceanus](https://github.com/wuba/Oceanus)：58同城数据库中间件，功能简单、易于上手。

#### Binlog

* [Canal](https://github.com/alibaba/canal)：Canal是阿里开发的基于数据库增量日志解析，提供增量数据订阅&消费的中间件。
* [KKBinLog](https://gitee.com/kekingcn/kkbinlog)：KKBinLog旨在简化监听MySQL、MongoDB数据库的不同表的各种数据变动，由凯京科技开源。
* [Binlog4j](https://gitee.com/dromara/binlog4j)：Binlog4j是基于Java的轻量级MySQL Binlog客户端，由dromara社区开源。
* [MySQL BinLog Connector](https://github.com/shyiko/mysql-binlog-connector-java)：MySQL BinLog Connector是一个用Java编写的高性能MySQL Binlog解析器。
* [Open Replicator](https://github.com/whitesock/open-replicator)：Open Replicator是一个用Java编写的高性能MySQL Binlog解析器。
* [CDC](https://github.com/rong360/cdc)：CDC是一个MySQL Binlog解析器，它将Binlog事件转换为JSON格式的数据，并写入到RabbitMQ或其他MQ(例如Kafka)中，由融360开源。
* [Canal2SQL](https://github.com/zhuchao941/canal2sql)：用Java写的MySQL Binlog解析工具，底层依赖Canal。

#### 灾难备份

* [Dataflow Templates](https://github.com/GoogleCloudPlatform/DataflowTemplates)：Dataflow Templates旨在解决简单但大型的云内数据任务，包括数据导入/导出/备份/恢复和批量API操作，而无需开发环境，由Google开源。
* [Exhibitor](https://github.com/soabase/exhibitor)：ZooKeeper协同处理实例，例如监控、备份/恢复、清理和可视化，由Netflix开源。
* [Priam](https://github.com/Netflix/Priam)：Priam是一个与Cassandra一起运行的流程/工具，由Netflix开源。
* [Ptubes](https://github.com/meituan/ptubes)：Ptubes是一款基于PITR的数据库灾难恢复产品，可以用来将整个数据库恢复到特定时间点，美团开源。
* [Raigad](https://github.com/Netflix/Raigad)：Raigad是一个用于ElasticSearch备份/恢复、自动部署和集中配置管理的协同进程，由Netflix开源。
* [InnoDB Java Reader](https://github.com/alibaba/innodb-java-reader)：InnoDB Java Reader是一个直接访问MySQL InnoDB存储引擎文件的Java实现，由阿里开源。
* [FQLite](https://github.com/pawlaszczyk/fqlite)：FQLite是一款用于查找和恢复SQLite数据库中已删除记录的工具。

## 网络编程

这里列出了网络相关的库、软件、工具、服务器集合。

#### HTTP客户端

* [Apache HttpComponents](https://github.com/apache/httpcomponents-core)：HttpComponents项目负责创建和维护专注于HTTP和相关协议的低级Java组件工具集。
* [Apache HttpComponents Client](https://github.com/apache/httpcomponents-client)：Apache开源的HTTP客户端库，相比HttpComponents Core提供更流式的API。
* [Feign](https://github.com/OpenFeign/feign)：Feign是一个Java到HTTP客户端绑定器，其灵感来自于Retrofit、JAXRS-2.0和WebSocket，由Netflix开源。
* [OkHttp](https://github.com/square/okhttp)：Square为JVM、Android和GraalVM精心设计的HTTP客户端。
* [Fuel](https://github.com/kittinunf/fuel)：由Kotlinx Coroutines支持的最简单的Kotlin HTTP网络库。
* [Retrofit](https://github.com/square/retrofit)：Retrofit是适用于Android和JVM的类型安全HTTP客户端，由Square开源。
* [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client)：AsyncHttpClient库允许Java应用程序轻松执行HTTP请求并异步处理HTTP响应。
* [RxEasyHttp](https://github.com/zhou-you/RxEasyHttp)：本库是一款基于RxJava2、Retrofit2实现简单易用的网络请求框架。
* [Android Asynchronous HttpClient](https://github.com/android-async-http/android-async-http)：基于Apache HttpClient库的Android异步、基于回调的HTTP客户端。
* [Google HTTP Java Client](https://github.com/googleapis/google-http-java-client)：Google HTTP Client由Google开源，是一个灵活、高效且功能强大的Java库，用于通过HTTP访问网络上的任何资源。
* [Google API Java Client](https://github.com/googleapis/google-api-java-client)：Google API Java Client是一个灵活、高效且功能强大的Java客户端库，用于访问网络上任何基于HTTP的API。
* [HttpClientUtil](https://github.com/Arronlong/httpclientutil)：HttpClientUtil是基于HttpClient 4.4.1封装的工具类。
* [RoboSpice](https://github.com/stephanenicolas/robospice)：RoboSpice是一个模块化的Android库，可以轻松编写异步长时间运行的任务。
* [Http Request](https://github.com/kevinsawicki/http-request)：Http Request是一个简单的便利库，用于使用HttpURLConnection发出请求并访问响应。
* [HttpFetch](https://github.com/youzan/httpfetch)：HttpFetch用于对HTTP请求进行封装，通过对接口函数进行代理，实现优雅的HTTP调用，有赞开源。
* [EasyHttp](https://github.com/getActivity/EasyHttp)：Android网络请求框架，简单易用。
* [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)：OkGo基于HTTP协议，封装了OkHttp的网络请求框架。
* [Wasp](https://github.com/orhanobut/wasp)：紧凑且易于使用的“一体化”Android网络解决方案。
* [STTP](https://github.com/softwaremill/sttp)：STTP是SoftwareMill开源的库，它提供了一个干净的、程序员友好的API来描述HTTP请求以及如何处理响应。
* [Http4s](https://github.com/http4s/http4s)：Http4s是一个极简且符合Scala规范的HTTP服务接口。
* [Ktorfit](https://github.com/Foso/Ktorfit)：Ktorfit是一个适用于Kotlin多平台的HTTP客户端/Kotlin符号处理器，使用受Retrofit启发的KSP和Ktor客户端。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Java和Android的异步套接字、HTTP(s)和WebSocket库；基于NIO，而不是线程。
* [Chuck](https://github.com/jgilfelt/chuck)：Chuck是一个简单的应用内HTTP检查器，适用于Android OkHttp客户端。
* [NoHttp](https://github.com/yanzhenjie/NoHttp)：NoHttp是一个Android实现的HTTP标准协议框架，支持多种缓存模式，底层可动态切换OkHttp、URLConnection。
* [Volley](https://github.com/google/volley)：Volley是一个HTTP库，它使Android应用程序的网络变得更容易，Google开源。
* [RxVolley](https://github.com/kymjs/RxVolley)：RxVolley是Volley的修改版，移除了HttpClient，并支持RxJava。
* [Novate](https://github.com/Tamicer/Novate)：Novate是一款Android网络框架，基于Retrofit和RxJava打造的链式网络库。
* [Unirest](https://github.com/Kong/unirest-java)：Unirest是一个简化的轻量级HTTP客户端库。
* [RawHTTP](https://github.com/renatoathaydes/rawhttp)：一个Java库，可以轻松处理由RFC-7230定义的原始HTTP 1.1以及大部分HTTP 1.0(RFC-1945)。
* [HTTP Kit](https://github.com/http-kit/http-kit)：HTTP Kit是一个简约且高效的Clojure兼容环的HTTP客户端/服务器。
* [Forest](https://gitee.com/dromara/forest)：Forest是一个高层、极简的声明式HTTP调用API框架，由dromara社区开源。
* [Methanol](https://github.com/mizosoft/methanol)：Methanol是Java的轻量级HttpClient扩展。
* [Jodd HTTP](https://github.com/oblac/jodd-http)：Jodd HTTP是一个小型、原始的HTTP客户端。
* [REST Commander](https://github.com/eBay/restcommander)：REST Commander是一个快速并行异步HTTP/REST/SOAP客户端即服务，用于监视和管理数以万计的Web服务器，由eBay开源。
* [Avaje HttpClient](https://github.com/avaje/avaje-http)：JDK 11 HttpClient的轻量级包装器。
* [Jcabi HTTP](https://github.com/jcabi/jcabi-http)：Jcabi HTTP是流式的Java HTTP客户端。
* [Parallec](https://github.com/eBay/parallec)：Parallec是一个基于Akka的快速并行异步HTTP(S)/SSH/TCP/UDP/Ping客户端Java库，由eBay开源。
* [OkHttps](https://gitee.com/troyzhxu/okhttps)：OkHttps是对OkHttp3轻量封装的框架，包括异步预处理器，特色的标签，灵活的上传下载进度监听与过程控制功能。
* [RXHttp](https://github.com/liujingxing/rxhttp)：适用于Android的类型安全HTTP客户端，基于OkHttp。
* [HTTP4K](https://github.com/http4k/http4k)：HTTP4K是一个用纯Kotlin编写的轻量级但功能齐全的HTTP工具包，可以以功能一致的方式提供和使用HTTP服务。
* [LiteHTTP](https://github.com/litesuits/android-lite-http)：LiteHTTP是一个简单、智能且灵活的Android HTTP框架。
* [Communication](https://github.com/foundation-runtime/communication)：Communication包含与HTTP客户端和服务器通信相关的库，由Cisco开发。
* [Netty HTTP Client](https://github.com/timboudreau/netty-http-client)：Java中的异步HTTP客户端，具有干净、基于回调的API，基于Netty 4.x。
* [Jetty HttpClient](https://github.com/eclipse/jetty.project/tree/jetty-10.0.x/jetty-client)：Jetty中执行HTTP和HTTPS请求的模块。
* [HTTP4J](https://github.com/IntellectualSites/HTTP4J)：HTTP4J是Java HttpURLConnection的一个简单、轻量级且小型的包装器。
* [Donkey](https://github.com/AppsFlyer/donkey)：现代Clojure、Ring兼容的HTTP服务器和客户端，专为易用性和性能而设计。
* [HTTPBuilder](https://github.com/jgritman/httpbuilder)：Groovy的简单HTTP客户端。
* [HttpBuilder NG](https://github.com/http-builder-ng/http-builder-ng)：适用于Groovy、Java的简单HTTP客户端。
* [RestVolley](https://github.com/HujiangTechnology/RestVolley)：RestVolley是一个基于Volley和OkHttp的HTTP请求框架，由沪江科技开源。
* [King HttpClient](https://github.com/king/king-http-client)：支持SSE的异步HTTP客户端。
* [Smart HTTP](https://gitee.com/smartboot/smart-http)：Smart HTTP是一款可编程的HTTP应用微内核，方便用户根据自身需求进行服务端或客户端的应用开发。
* [cURL](https://github.com/libetl/curl)：在Java中使用cURL的库。
* [Java cURL](https://github.com/rockswang/java-curl)：Java cURL是一个基于标准JDK中的HttpURLConnection实现的纯Java HTTP实用程序。
* [JCurl](https://github.com/finos/JCurl)：Java中支持JSON的Curl，由金融科技基金会开源。
* [JQuickCurl](https://github.com/paohaijiao/jquick-curl)：JQuickCurl是一个面向Java开发者的高性能、易用HTTP客户端框架。

#### HTTP路由

* [Riptide](https://github.com/zalando/riptide)：Riptide是一个实现客户端响应路由的库，由Zalando开源。
* [Netty HTTP](https://github.com/cdapio/netty-http)：一个使用Netty开发HTTP服务的库，支持基于JAX-RS风格注解路由端点的功能，由Google开源。
* [Netty Router](https://github.com/sinetja/netty-router)：Netty Router是一个小型Java库，将HTTP请求路由到你的Netty处理程序。
* [Avaje Jex](https://github.com/avaje/avaje-jex)：Avaje Jex是一个轻量级的JDK内置HTTP Server API包装器，并进行了一些关键的增强。

#### Web服务器

* [Apache Tomcat](https://github.com/apache/tomcat)：Tomcat是Java Servlet、JavaServer Pages、Java EL和Java WebSocket技术的开源实现，最初由Sun开发。
* [Netty TCNative](https://github.com/netty/netty-tcnative)：Netty TCNative是Tomcat Native的一个分支，它包括Twitter贡献的一系列更改。
* [Apache TomEE](https://github.com/apache/tomee)：TomEE是一个轻量级但功能强大的JavaEE应用服务器，具有功能丰富的工具。
* [Helidon Nima](https://github.com/helidon-io/helidon/tree/helidon-3.x/webserver)：Helidon Níma是一个基于JDK虚拟线程的轻量级Web服务器，由Oracle开源。
* [Undertow](https://github.com/undertow-io/undertow)：Undertow是一个基于非阻塞IO的Java Web服务器，由RedHat开源。
* [Wildfly](https://github.com/wildfly/wildfly)：WildFly是一个功能强大、模块化且轻量级的应用程序服务器，由RedHat开源。
* [Oracle Weblogic](https://www.oracle.com/sg/java/weblogic/)：Oracle WebLogic Server是一个统一且可扩展的平台，用于在本地和云中开发、部署和运行Java等企业应用程序。
* [Payara](https://github.com/payara/Payara)：Payara Platform Community Edition提供用于开发项目的开源服务器运行时以及容器化Jakarta EE和MicroProfile应用程序
* [Eclipse Jetty](https://github.com/eclipse/jetty.project)：Jetty是一个轻量级、高度可扩展的基于Java的Web服务器和Servlet引擎。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现，由Oracle开源。
* [Apache Geronimo](https://github.com/apache/geronimo)：Geronimo是一组开源项目，专注于提供JavaEE/JakartaEE库和Microprofile实现。
* [Red5](https://github.com/Red5/red5-server)：Red5是一个用Java编写的开源Flash服务器。
* [Microhttp](https://github.com/ebarlas/microhttp)：Microhttp是一种快速、可扩展、事件驱动、独立的Java Web服务器。
* [Resin](https://caucho.com/products/resin)：Resin是Caucho公司的产品，它是一个非常流行的支持Servlet和JSP的服务器。
* [ZFoo](https://github.com/zfoo-project/zfoo)：ZFoo是一个极快的企业服务器框架，可用于RPC、游戏服务器、Web服务器。
* [Rupy](https://github.com/tinspin/rupy)：Rupy是一款节能、安全、高性能的HTTP应用服务器。
* [Jigsaw](https://www.w3.org/Jigsaw/)：Jigsaw是W3C领先的Web服务器平台，它基于Java实现的先进架构，提供了HTTP 1.1的示例实现以及各种其他功能。
* [Java HTTP](https://github.com/FusionAuth/java-http)：Java HTTP是一个轻量级、开源、零依赖的Java HTTP服务器。
* [HttpServer](https://github.com/robaho/httpserver)：JDK com.sun.net.httpserver.HttpServer规范的零依赖实现，具有一些显著的增强功能。
* [Reactor Netty](https://github.com/reactor/reactor-netty)：Reactor Netty提供基于Netty框架的非阻塞和背压就绪的TCP/HTTP/UDP/QUIC客户端和服务器。
* [Nettosphere](https://github.com/Atmosphere/nettosphere)：Nettosphere是由Atmosphere和Netty提供支持的Java WebSocket和HTTP服务器。
* [NanoHTTPD](https://github.com/NanoHttpd/nanohttpd)：NanoHTTPD是一个轻量级HTTP服务器，设计用于嵌入其他应用程序。
* [MiniCat](https://gitee.com/coodyer/minicat)：MiniCat是一款轻量化HTTP服务器，支持BIO、NIO两种模式。
* [Java NIO Server](https://github.com/jjenkov/java-nio-server)：一个始终使用非阻塞IO的Java NIO服务器。
* [AndServer](https://github.com/yanzhenjie/AndServer)：AndServer是Android平台的Web服务器和Web框架。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [Nginx Clojure](https://github.com/nginx-clojure/nginx-clojure)：Nginx Clojure是一个Nginx模块，用于嵌入Clojure或Java或Groovy程序，通常是那些基于Ring的处理程序。
* [Jibble](http://www.jibble.org/miniwebserver/)：Jibble是一个用Java编写的非常小的独立Web服务器，它打包在JAR文件中，也可以在你自己的Java程序中使用。
* [TorqueBox](https://github.com/torquebox/torquebox)：TorqueBox运行在JRuby之上，并基于一个全新的轻量级、可插拔、多语言服务器。
* [Android HTTP Server](https://github.com/piotrpolak/android-http-server)：完全用Java编写的小型但功能强大的多线程Web服务器。
* [MuServer](https://github.com/3redronin/mu-server)：MuServer是一个基于Netty的现代Java Web服务器。
* [Fluent HTTP](https://github.com/CodeStory/fluent-http)：Fluent HTTP是一个简单、快速、成熟的Web服务器。
* [JLHTTP](https://github.com/curtcox/JLHTTP)：JLHTTP是HTTP服务器的开源实现。
* [TJWS](https://tjws.sourceforge.net/)：TJWS是作为Servlet容器构建的，其中HTTPD Servlet提供标准Web服务器功能。
* [Aeromock](https://github.com/ca-archived/aeromock)：Aeromock是一个从模板文件和数据文件生成HTML的应用服务器。
* [SimpleWebServer](https://github.com/94fzb/simplewebserver)：SimpleWebServer是一款使用Java基于NIO编写的超轻量级开源Web应用服务器。
* [Magician](https://github.com/JMagician/Magician)：Magician是一个基于Netty的小型HTTP服务包，它使启动HTTP服务变得非常容易，并且还支持WebSocket。
* [Flupke](https://github.com/ptrd/flupke)：Flupke是一个100%纯Java HTTP3实现，运行在Kwik之上。

#### 应用服务器

* [Payara](https://github.com/payara/Payara)：Payara Server是一个开源中间件平台，支持在任何环境中可靠、安全地部署Java EE(Jakarta EE)和MicroProfile应用程序。
* [Apache TomEE](https://github.com/apache/tomee)：TomEE是一个轻量级但功能强大的JavaEE应用服务器，具有功能丰富的工具。
* [Piranha](https://github.com/piranhacloud/piranha)：Piranha项目提供云就绪容器和有用的附加/集成模块。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，它是IBM WebSphere Liberty的开源实现。
* [SAP AS](https://www.sap.com/products/technology-platform/netweaver.html)：SAP Web应用服务器是NetWeaver解决方案的一个组件。
* [WebObjects](https://wiki.wocommunity.org/xwiki/bin/view/WO/Home/)：WebObjects是一套集成的Java框架，用于快速开发可扩展、复杂的互联网和企业应用程序，最初由NeXT开发并由Apple维护。
* [AISWare FlyingServer](https://www.asiainfo.com/zh_cn/product_aisware_flyingServer.html)：FlyingServer是一款满足Java EE 8标准的国产化Web中间件软件，支持WAR，EAR，JAR等应用的部署，由亚信科技提供。
* [Apusic AAS](https://www.apusic.com/list-117.html)：金蝶Apusic应用服务器是一款标准、安全、高效、集成并具丰富功能的企业级应用服务器软件，全面支持Jakarta EE 8/9的技术规范。
* [Apache Geronimo](https://github.com/apache/geronimo)：Geronimo是一组开源项目，专注于提供JavaEE/JakartaEE库和Microprofile实现。
* [Adobe ColdFusion](https://www.adobe.com/products/coldfusion-family.html)：Adobe ColdFusion是一款久经考验的高性能应用程序服务器，可让程序员轻松进行Web开发。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现，由Oracle开源。
* [Fujitsu Software Enterprise Application Server](https://www.fujitsu.com/jp/products/software/middleware/business-middleware/middleware/applatform/)：Enterprise Application Server是一款云原生应用服务器，采用富士通专有技术增强Java的可靠性和可操作性，可在短时间内发布，并可用于企业用途。
* [InforSuite Application Server](https://www.inforbus.com/as.html)：中创应用服务器软件是国内通过Jakarta EE 9、8及Java EE 8、7、6完整兼容认证的企业级中间件，与国际主流产品最新版本保持规范一致，为应用运行提供高性能、高可用、高安全的支撑平台。
* [Resin](https://caucho.com/products/resin)：Resin是Caucho开发的Web服务器和Java应用服务器，有两个可用版本：Resin(可免费用于生产)和Resin Pro(需要支付许可费用)。
* [JBoss Enterprise Application Platform](https://www.redhat.com/en/technologies/jboss-middleware/application-platform)：RedHat JBoss企业应用平台可在任何环境中提供企业级安全性、性能和可扩展性。
* [Primeton AppServer](https://www.primeton.com/products/pas/)：Primeton AppServer提供了丰富的功能集，具备“立即部署”式Java EE容器的各种优点，由普元开发。
* [WildFly](https://github.com/wildfly/wildfly)：WildFly是一款功能强大、模块化且轻量级的应用程序服务器。
* [BES Application Server](https://www.bessystem.com/product/0ad9b8c4d6af462b8d15723a5f25a87d/info?p=101#page-2)：BES是一款遵循Java EE标准的面向Java应用的通用中间件，由宝兰德提供。
* [ManageFish Server](https://managecat.com/products/managed-glassfish)：ManageFish是GlassFish应用服务器版本的商业支持的发行版。
* [Oracle WebLogic](https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html)：WebLogic是Oracle出品的用于开发、集成、部署和管理大型分布式Web应用、网络应用和数据库应用的Java应用服务器。
* [RockyAS](https://rockyasfile.obs-cn-shenzhen.pinganyun.com/RockyAS.html)：Rocky是一款标准、安全、高效的Web应用服务器，为企业级应用系统的便捷开发、灵活部署、可靠运行、高效管理及快速集成提供关键支撑能力，由平安云开发。
* [Libercat](https://axiomjdk.ru/pages/libercat/)：Libercat是一款安全的俄罗斯制造的应用服务器，它基于Apache Tomcat和Apache TomEE，并实现了Jakarta EE规范。
* [TongWeb Application Server](https://www.tongtech.com/dft/pctype/25.html)：TongWeb是一款全面符合Java EE、Jakarta EE最新标准规范、轻量易于使用、性能强大、具有高可靠性和高安全性的应用服务器产品，由东方通开发。
* [JEUS](https://www.tmaxsoft.com/en/solution/view?solutionSeq=27)：JEUS是在Web环境中开发、运行、执行应用程序的平台，提供各种必要服务、符合Java标准的Web应用服务器，由韩国TmaxSoft公司开发。
* [AliEE](https://help.aliyun.com/zh/edas/product-overview/what-is-alibaba-cloud-application-server?spm=a2c4g.11186623.0.0.72385806mPZpST)：阿里云应用服务器是一款企业级Java EE的应用服务器软件，用于构建和部署企业级应用程序。
* [Cosminexus](https://www.hitachi.com/products/it/software/prod/cosminexus/)：Cosminexus是日立公司提供的用于构建和运行应用程序服务器的中间件产品。
* [WebOTX Application Server](https://jpn.nec.com/webotx/appserver/index.html)：WebOTX是一个Java应用程序执行平台，非常适合在从本地到云的各种IT资源中推广DX，这是日本电气公司的产品。
* [Xigema Application Server](http://www.vsettan.com.cn/7752.html)：XigemaAS是企业级应用服务器产品，完全符合Java EE 7规范， 产品架构基于OSGi内核，高模块化、高动态性、强扩展性、轻量且配置简单，为企业应用提供稳定、高效、安全的运行引擎和支撑平台，这是华胜信泰的产品。
* [Thunisoft Application Server](https://www.thunisoft.cn/col81/index)：Thunisoft是华宇自主研发的企业级中间件产品，符合Jakarta EE标准的轻量级服务器。
* [JOnAS](https://jonas.ow2.org/)：JOnAS是由Bull和OW2开发的领先的Java EE 6 Web Profile认证开源OSGi企业服务器。
* [Carbon](https://github.com/wso2/carbon-kernel)：Carbon是一个轻量级、通用的OSGi运行时，专门用于托管服务器，为服务器开发人员提供关键功能，由WSO2开源。
* [UseOpen Application Server](http://www.useopen.com/p/uoas/)：UOAS是一款永源开源的Java应用服务器产品，支持Jakarta EE Web Profile规范的应用服务器功能。
* [Smart Servlet](https://gitee.com/smartboot/smart-servlet)：Smart Servlet是一款实现了Servlet 4.0规范，支持多应用隔离部署的的Web容器。
* [Zhiqim Httpd](https://gitee.com/zhiqim/zhiqim_httpd)：Zhiqim Httpd WEB容器，纯Java开发，全面实现HTTP服务，比Tomcat/Jetty更轻便、配置更简单和规范。

#### WebSocket

* [Pushy](https://netflixtechblog.com/pushy-to-the-limit-evolving-netflixs-websocket-proxy-for-the-future-b468bc0ff658)：Pushy是Netflix的WebSocket服务器，可与运行Netflix应用程序的设备保持持久的WebSocket连接。
* [Java WebSocket](https://github.com/TooTallNate/Java-WebSocket)：该项目包含用纯Java编写的准系统WebSocket客户端和服务器实现。
* [Scarlet](https://github.com/Tinder/Scarlet)：Scarlet是受Retrofit启发的适用于Kotlin、Java和Android的WebSocket客户端，由Tinder开源。
* [SignalR](https://github.com/aspnet/SignalR)：SignalR是一个开源库，可简化向应用程序添加实时功能，由Microsoft开发。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：AndroidAsync是适用于Android的异步套接字、HTTP(s)客户端/服务器和WebSocket库，基于NIO而不是线程。
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：AsyncHttpClient是适用于Java的异步HTTP和WebSocket客户端库。
* [NV Websocket Client](https://github.com/TakahikoKawasaki/nv-websocket-client)：Java中的高质量WebSocket客户端实现。
* [WebSocket Android](https://github.com/codebutler/android-websockets)：一个非常简单的Android WebSocket客户端。
* [Kafka WebSocket](https://github.com/b/kafka-websocket)：kafka分布式消息代理的简单WebSocket服务器接口。
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
* [Jawampa](https://github.com/Matthias247/jawampa)：Jawampa是一个为Java提供对Web应用程序消息传递协议(WAMP)支持的库。
* [Eclipse Tyrus](https://github.com/eclipse-ee4j/tyrus)：Tyrus是开源JSR 356-WebSocket参考实现的Java API，可轻松开发WebSocket应用程序。
* [Socket.IO Java Client](https://github.com/Gottox/socket.io-java-client)：Java中的Socket.IO客户端实现。
* [Socket.IO Java](https://github.com/trinopoty/socket.io-server-java)：这是从JavaScript服务器移植的Java Socket.IO服务器库。
* [Babl WebSocket Server](https://github.com/babl-ws/babl)：Babl是一款高性能、可扩展的WebSocket服务器，专为低延迟应用程序而设计。
* [Socket.x](https://github.com/obsidiandynamics/socketx)：Socket.x是一个用于构建高性能、分布式WebSocket应用程序的库。
* [WebSocketDemo](https://github.com/0xZhangKe/WebSocketDemo)：用于简化WebSocket在Android平台使用的封装方法。
* [RxWebSocket](https://github.com/dhhAndroid/RxWebSocket)：RxWebSocket是一个基于Okhttp和RxJava封装的WebSocket客户端。
* [MOKO Socket.IO](https://github.com/icerockdev/moko-socket-io)：IceRock的MOKO Socket.IO是Socket.IO实现Kotlin多平台库。
* [Netty Socket.IO](https://github.com/socketio4j/netty-socketio)：基于Netty框架的Java Socket.IO服务器实现。
* [WebSocket Android Phonegap](https://github.com/anismiles/websocket-android-phonegap)：这是一个为Android平台实现Websocket API的Java库。
* [TubeSock](https://github.com/FirebaseExtended/TubeSock)：TubeSock是WebSocket协议客户端的Java实现，由Google开源。
* [Krossbow](https://github.com/joffrey-bion/krossbow)：Krossbow是一个Kotlin多平台STOMP 1.2客户端，具有基于协程的API。
* [Socket MQTT](https://github.com/daoshenzzg/socket-mqtt)：Socket MQTT是一个基于Netty、MQTT实现的推送基础框架。

#### FTP服务器

* [Apache FtpServer](https://mina.apache.org/ftpserver-project/)：FtpServer是一个100%纯Java FTP服务器。
* [MinimalFTP](https://github.com/Guichaguri/MinimalFTP)：一个轻量级、简单的FTP服务器。
* [Anomic](https://github.com/Orbiter/anomic_ftp_server)：Anomic是一个简单的FTP服务器。
* [SwiFTP](https://github.com/ppareit/swiftp)：Android设备的FTP服务器。
* [DrFTPD](https://github.com/drftpd-ng/drftpd)：DrFTPD是一个用Java编写的分布式FTP服务器。

#### NIO框架

* [Netty](https://github.com/netty/netty)：Netty是一个异步事件驱动的网络应用程序框架，用于快速开发可维护的高性能协议服务器和客户端。
* [Apache MINA](https://github.com/apache/mina)：MINA是一个网络应用框架，可以帮助用户开发高性能和高可扩展性的网络应用程序。
* [Eclipse Grizzly](https://github.com/eclipse-ee4j/grizzly)：Grizzly的目标是帮助开发人员使用NIO构建可扩展且强大的服务器，Oracle开源。
* [SOFABolt](https://github.com/sofastack/sofa-bolt)：SOFABolt是蚂蚁金融开发的一套基于Netty实现的网络通信框架。
* [Aleph](https://github.com/clj-commons/aleph)：Aleph是一个基于Netty构建的客户端和服务器网络编程库。
* [Voovan](https://gitee.com/helyho/Voovan)：Voovan是一个高性能异步网络框架和Web服务器框架。
* [T-IO](https://gitee.com/tywo45/t-io)：T-IO是基于Java开发的一款高性能网络编程框架，由钛特云开源。
* [JNet](https://gitee.com/eric_ds/jnet)：JNet框架是Java AIO接口的一层薄封装，仅进一步降低其编程复杂性，不提供额外的抽象。
* [XNIO](https://github.com/xnio/xnio)：XNIO是一个基于Java NIO的框架，支持阻塞和非阻塞IO，由RedHat开源。
* [Blaze](https://github.com/http4s/blaze)：Blaze是一个用于构建异步管道的Scala库，专注于网络IO。
* [SNF4J](https://github.com/snf4j/snf4j)：SNF4J是一个异步事件驱动的网络应用程序框架，用于快速轻松地开发网络应用程序。
* [One NIO](https://github.com/odnoklassniki/one-nio)：One NIO是一个用于构建高性能Java服务器的库，由Odnoklassniki开源。
* [Gecko](https://github.com/killme2008/gecko)：Gecko是一个Java NIO的通讯组件，它在一个轻量级的NIO框架的基础上提供了更高层次的封装和功能，由淘宝开发。
* [FireNio](https://github.com/FireNio/firenio)：FireNio是基于Java NIO开发的一款可快速构建网络通讯项目的异步IO框架。
* [Mycat NIO](https://github.com/MyCATApache/Mycat-NIO)：非常高性能又简单的NIO框架。
* [Acteur](https://github.com/timboudreau/acteur)：Acteur是一个使用Netty编写Web服务器应用程序的框架。
* [UberFire I/O](https://github.com/kiegroup/appformer/tree/main/uberfire-io)：NIO.2的实用程序/门面集。
* [Getty](https://gitee.com/kokjuis/getty)：Getty是完全基于Java NIO封装的高性能网络框架。

#### 网络库

* [TChannel](https://github.com/uber/tchannel)：TChannel是一种用于一般RPC的网络框架协议，支持无序响应，性能极高，中间人可以快速做出转发决策，由Uber开源。
* [Network Connection](https://github.com/facebookarchive/network-connection-class)：Network Connection是一个Android库，可让你了解当前用户的互联网连接质量，由Facebook开源。
* [Apache Commons Net](https://github.com/apache/commons-net)：Commons Net库包含网络实用程序和协议实现的集合。
* [Envoy Mobile](https://github.com/envoyproxy/envoy-mobile)：构建在Envoy项目的核心网络层上的多平台客户端HTTP/网络库。
* [JVM Libp2p](https://github.com/libp2p/jvm-libp2p)：用Kotlin编写的JVM的Libp2p实现。
* [Android Network Tools](https://github.com/stealthcopter/AndroidNetworkTools)：该项目是一组有用的Android网络工具库，例如端口扫描、ping等。
* [AdbLib](https://github.com/cgutman/AdbLib)：ADB网络协议的Java库实现。
* [COMSAT](https://github.com/puniverse/comsat)：COMSAT是一组开源库，将Quasar与各种Web或企业技术集成。
* [Infinileap](https://github.com/hhu-bsinfo/infinileap)：Infinileap是适用于Java 19+的基于ucx的现代网络框架，由杜塞尔多夫海因里希海涅大学计算机科学系操作系统小组开发。
* [TLS Channel](https://github.com/marianobarrios/tls-channel)：TLS Channel是一个通过TLS连接实现ByteChannel接口的库。
* [JXIO](https://github.com/accelio/JXIO)：JXIO是基于AccelIO(C库)的Java API。
* [Commons Networking](https://github.com/CiscoSE/commons-networking)：由Cisco开源的公共网络实用程序库。
* [DiSNI](https://github.com/zrlio/disni)：DiSNI是一个Java库，用于从用户空间直接存储和网络访问，它提供了一个RDMA接口来访问远程内存，由IBM开源。
* [Barchart UDT](https://github.com/barchart/barchart-udt)：Barchart UDT是原生C++ UDT协议的Java包装器。
* [URNLib](https://github.com/slub/urnlib)：用于表示、解析和编码RFC 2141和RFC 8141中指定的URN的Java库，由德累斯顿工业大学开源。
* [Jcabi URN](https://github.com/jcabi/jcabi-urn)：Jcabi URN是根据RFC 2141的URN的不可变实现。
* [JSTUN](https://github.com/tking/JSTUN)：JSTUN是基于Java的STUN(通过网络地址转换(NAT)简单遍历UDP)实现。
* [Jagornet DHCP](https://github.com/jagornet/dhcp)：用Java编写的开源DHCPv4/DHCPv6服务器。
* [Nmap4j](https://github.com/narkisr/nmap4j)：Java Nmap包装器。

#### Socket

* [Smart Socket](https://gitee.com/smartboot/smart-socket)：Smart Socket是一款极简、易用、高性能的AIO通信框架。
* [AndroidSocketClient](https://github.com/vilyever/AndroidSocketClient)：Socket客户端、服务器简单封装。
* [Jocket](https://github.com/pcdv/jocket)：Jocket是使用共享内存的低延迟Java套接字实现。
* [OkSocket](https://github.com/xuuhaoo/OkSocket)：OkSocket是一个Java库，旨在解决轻量级的Socket通信。
* [BizSocket](https://github.com/typ0520/bizsocket)：异步Socket，对一些业务场景做了支持。
* [EasySocket](https://github.com/jiusetian/EasySocket)：EasySocket是一个轻量级的Android端Socket框架，可快速实现客户端和服务端之间的TCP长连接通讯。
* [Socket.D](https://gitee.com/noear/socket.d)：Socket.D是基于事件和语义消息流的网络应用协议。
* [JUDS](https://github.com/mcfunley/juds)：JUDS提供类来满足Java中访问Unix域套接字的需求。
* [JUnixSocket](https://github.com/kohlschutter/junixsocket)：JUnixSocket是一个Java/JNI库，允许在Java中使用Unix域套接字(AF_UNIX套接字)和其他地址/协议系列(AF_TIPC、AF_VSOCK和AF_SYSTEM)。
* [JNR UnixSocket](https://github.com/jnr/jnr-unixsocket)：Java的本机I/O访问。
* [Epoll](https://github.com/wizzardo/epoll)：基于事件的套接字服务器，使用epoll。
* [JNanomsg](https://github.com/niwinz/jnanomsg)：用于Nanomsg的Clojure和Java绑定。
* [AIO Socket](https://gitee.com/starboot/aio-socket)：AIO Socket是Java AIO通讯内核，采用了内存池、线程池、对象池、缓存池以及插件化增添模块等思想进行设计。
* [IPC Socket](https://github.com/sbt/ipcsocket)：IPC Socket是使用java.net.ServerSocket和java.net.Socket作为API的进程间通信的Java包装器。
* [Socket](https://github.com/areong/Socket)：线程Java套接字服务器和客户端。

#### TCP/UDP库

* [KryoNet](https://github.com/EsotericSoftware/kryonet)：KryoNet是一个Java库，它提供了一个干净、简单的API，用于使用NIO进行高效的TCP和UDP客户端/服务器网络通信。
* [QuickServer](https://github.com/QuickServerLab/QuickServer-Main)：QuickServer是一个开源Java库/框架，用于快速创建强大的多客户端TCP服务器应用程序。
* [Chronicle Network](https://github.com/OpenHFT/Chronicle-Network)：Chronicle Network是一个高性能网络(TCP/IP)库。
* [CoralReactor](https://www.coralblocks.com/index.php/category/coralreactor/)：CoralReactor是一个功能强大、超低延迟、异步、非阻塞的网络I/O库，可通过简单的API提供高性能。
* [SimpleNet](https://github.com/jhg023/SimpleNet)：SimpleNet是一个用Java编写的简单的客户端/服务器框架。
* [Dragonite](https://github.com/dragonite-network/dragonite-java)：Dragonite是一种基于UDP的可靠应用级数据传输协议，针对有损和不稳定的网络进行了高度优化。
* [JBoss Remoting](https://github.com/jboss-remoting/jboss-remoting)：JBoss Remoting的目的是提供一个用于通过网络进行对称和非对称通信的通用框架，由RedHat开发。

#### Pcap

* [Pcap4J](https://github.com/kaitoy/pcap4j)：Pcap4J是一个用于捕获、制作和发送数据包的Java库。
* [Jpcap](https://github.com/jpcap/jpcap)：Jpcap是一组Java类，提供用于网络数据包捕获的接口和系统，由加州大学欧文分校开源。
* [Pkts](https://github.com/aboutsip/pkts)：Pkts是一个用于读取和写入pcap的纯Java库。
* [Pcap](https://github.com/ardikars/pcap)：Pcap提供了一个数据包处理库，可以在JVM语言之上进行快速开发。
* [jNetPcap](https://github.com/slytechs-repos/jnetpcap-wrapper)：jNetPcap是一个用Java编写的软件库，提供与流行的libpcap本机库类似的API。
* [Hadoop PCAP](https://github.com/RIPE-NCC/hadoop-pcap)：Hadoop PCAP用于并行地读取和分析数据包捕获文件，由欧洲IP网络协调中心开源。

#### SSH库

* [Apache MINA SSHD](https://github.com/apache/mina-sshd)：MINA SSHD是一个100%纯Java库，支持客户端和服务器端的SSH协议。
* [Trilead SSH](https://github.com/jenkinsci/trilead-ssh2)：Trilead SSH-2是一个用纯Java实现SSH-2协议的库。
* [Pty4J](https://github.com/JetBrains/pty4j)：Java中的伪终端实现，由JetBrains开源。
* [JSch](https://github.com/mwiede/jsch)：实现SSH功能的Java库，可用于连接SFTP服务器。
* [Jcabi SSH](https://github.com/jcabi/jcabi-ssh)：Java SSH客户端。
* [JSch](https://github.com/is/jsch)：JSch是SSH2的纯Java实现。
* [Maverick Synergy](https://github.com/sshtools/maverick-synergy)：Maverick Synergy是由JADAPTIVE开发的第三代Java SSH API。
* [SSHJ](https://github.com/hierynomus/sshj)：Java的SSH、SCP和SFTP库。
* [WebSSH](https://github.com/NoCortY/WebSSH)：纯Java实现的WebSSH。
* [SSH Proxy](http://github.com/cronn/ssh-proxy)：SSH端口隧道的纯Java实现，能够理解涉及多跳才能到达目标主机的OpenSSH配置。
* [SSHoogr](https://github.com/sshoogr/sshoogr)：SSHoogr是一个基于Groovy的DSL库，用于通过SSH连接远程服务器，由Aestas/IT开源。
* [Vngx JSch](https://github.com/vngx/vngx-jsch)：Vngx JSch是用纯Java编写的流行的JSch库的更新版本。
* [SSHLib](https://github.com/connectbot/sshlib)：ConnectBot的SSH库，它最初是Trilead SSH2库的延续。
* [Ganymed SSH-2](https://github.com/hudson/ganymed-ssh-2)：Ganymed SSH-2是一个用纯Java实现SSH-2协议的库。

#### DNS库

* [DNSJava](https://github.com/dnsjava/dnsjava)：DNSJava是DNS协议的Java实现。
* [DNS Proxy](https://github.com/mageddo/dns-proxy-server)：DPS是一种轻量级最终用户DNS服务器工具，可以轻松地在一个主机名可以根据配置的环境解析为不同IP的系统中进行开发。
* [MiniDNS](https://github.com/MiniDNS/minidns)：MiniDNS是适用于Android和Java SE的DNS库。
* [JmDNS](https://github.com/jmdns/jmdns)：JmDNS是多播DNS的Java实现，支持服务发现和注册，并与Apple的Bonjour完全兼容。
* [MDNS Java](https://github.com/posicks/mdnsjava)：Java中的多播DNS和基于DNS的服务发现。
* [Dns Cache Manipulator](https://github.com/alibaba/java-dns-cache-manipulator)：一个微小的0依赖线程安全Java库，用于以编程方式设置/查看DNS，无需接触host文件，使单元/集成测试可移植，由阿里开源。
* [Denominator](https://github.com/Netflix/denominator)：Denominator是一个用于操作DNS云的可移植Java库，由Netflix开源。
* [Happy DNS](https://github.com/qiniu/happy-dns-android)：用于Android的DNS库，由七牛云开源。
* [DNS Java](https://github.com/spotify/dns-java)：这个小型DNS包装器库提供了一些与SRV查找相关的有用功能，由Spotify开源。
* [DNS Cheater](https://gitee.com/matrixy/dns-cheater)：Java实现的DNS服务器，可通过Web管理界面随意设置灵活的解析规则。
* [VinylDNS](https://github.com/vinyldns/vinyldns)：VinylDNS是一个与供应商无关的前端平台，用于实现自助式DNS并简化DNS操作，由Comcast开发。
* [JDNSS](https://github.com/drsjb80/JDNSS)：JDNSS是一个仅权威、支持DNSSEC/TLS/DoH的Java叶DNS服务器。

#### HTTP代理

* [Decodo](https://github.com/Decodo/Decodo)：Decodo是一个轮换式住宅代理网络，允许用户使用超过1.15亿个IP地址池从网络收集数据。
* [Apache Guacamole](https://github.com/apache/guacamole-client)：Guacamole是一个无客户端远程桌面网关，它支持VNC、RDP和SSH等标准协议。
* [Proxyee](https://github.com/monkeyWie/proxyee)：Proxyee是一个Java编写的HTTP代理服务器库，支持HTTP、HTTPS、WebSocket协议，并支持MITM，可以捕获和篡改HTTP、HTTPS数据包。
* [HTTP Proxy Servlet](https://github.com/mitre/HTTP-Proxy-Servlet)：这是Java Servlet形式的HTTP代理，由MITRE公司开发。
* [Charon](https://github.com/mkopylec/charon-spring-boot-starter)：Charon是一个反向代理实现，它自动将HTTP请求从一个HTTP服务器转发到另一个HTTP服务器，并将收到的HTTP响应返回给客户端。
* [Suo5](https://github.com/zema1/suo5)：Suo5是一个高性能HTTP隧道代理工具，它基于双向的Chunked-Encoding构建。
* [Vert.x Http Proxy](https://github.com/eclipse-vertx/vertx-http-proxy)：Vert.x Http Proxy是基于Vert.x的反向代理，旨在实现可重用的反向代理逻辑以专注于更高的关注点。
* [BrowserUp Proxy](https://github.com/lightbody/browsermob-proxy)：BrowserMob Proxy允许你操作HTTP请求和响应、捕获HTTP内容以及将性能数据导出为HAR文件。
* [LittleProxy](https://github.com/adamfisk/LittleProxy)：LittleProxy是一个用Java编写的高性能HTTP代理。
* [PacketProxy](https://github.com/DeNA/PacketProxy)：PacketProxy是一个开源代理工具，可以拦截和检查TCP/UDP上的任何协议，而不仅限于HTTP/1.x、HTTP2或HTTPS，由DeNA开源。
* [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG)：OpenIG是一种高性能反向代理服务器，具有专门的会话管理和凭证重播功能。
* [PowerTunnel](https://github.com/krlvm/PowerTunnel)：PowerTunnel是一个构建在LittleProxy之上的可扩展代理服务器。
* [Styx](https://github.com/ExpediaGroup/styx)：Styx是用于JVM的可编程、异步、基于事件的反向代理，由Expedia开源。
* [Carapaceproxy](https://github.com/diennea/carapaceproxy)：Carapac是一个分布式Java反向代理。
* [Bouncer](https://github.com/ggrandes/bouncer)：Bouncer是一个开源Java网络代理。
* [Proxy Vole](https://github.com/MarkusBernhardt/proxy-vole)：Proxy Vole是一个用于自动检测平台网络代理设置的Java库。
* [Mallet](https://github.com/sensepost/mallet)：Mallet是一种用于创建任意协议代理的工具，类似于我们熟悉的拦截Web代理，只是更加通用。
* [WK Proxy](https://github.com/catas-w/WK-Proxy)：WK Proxy是一款用于HTTP代理和数据包捕获的开源桌面工具，可在Windows和macOS平台上使用。
* [ProxyChecker](https://github.com/faiqsohail/ProxyChecker)：一款易于使用的开源多线程代理检查器。
* [Tarmoqchi](https://github.com/floss-uz-community/tarmoqchi)：HTTP隧道工具。
* [OJP](https://github.com/Open-J-Proxy/ojp)：JDBC驱动程序和第7层代理服务器将应用程序与关系型数据库连接管理分离。

#### 内网穿透

* [Lanproxy](https://github.com/ffay/lanproxy)：Lanproxy是一个将局域网个人电脑、服务器代理到公网的内网穿透工具，支持TCP流量转发，可支持任何TCP上层协议。
* [Neo reGeorg](https://github.com/L-codes/Neo-reGeorg)：reGeorg是新一代内网穿透工具，这是该项目的重构版本。
* [Neutrino Proxy](https://gitee.com/dromara/neutrino-proxy)：Neutrino Proxy是一个基于Netty的开源Java内网穿透项目，由dromara社区开源。
* [Natcross2](https://github.com/Pluto-Whong/natcross2)：Natcross2是需要自己提供硬件支持、部署的内网穿透工具。
* [Venomous Sting](https://gitee.com/haojiangbo/venomous_sting)：基于Netty实现的高性能内网穿透，支持所有TCP上层协议的转发。
* [MagpieBridge](https://gitee.com/jiucheng_org/magpiebridge)：使用Java基于AIO/NIO实现的内网穿透工具。
* [Joggle](https://github.com/joggle-cn/joggle)：Joggle是基于Ngrok二开的开源内网穿透项目，多节点、私有部署、云服务。
* [LightTunnel](https://gitee.com/tuuzed/LightTunnel)：内网穿透工具，支持TCP、HTTP、HTTPS穿透。
* [Ngrok Spring Boot Starter](https://github.com/kilmajster/ngrok-spring-boot-starter)：Spring Boot集成Ngrok变得简单。
* [HP](https://gitee.com/HServer/hp)：内网穿透轻量版，支持HTTP、HTTPS、TCP、UDP，支持云端动态控制穿透配置。
* [Java Ngrok](https://github.com/alexdlaird/java-ngrok)：Java Ngrok是一个Ngrok包装器，用于管理自己的二进制文件，通过方便的Java提供应用程序接口。
* [NeoLink](https://github.com/NeoLinkProxy/NeoLink)：NeoLink是一个轻量级的内网穿透客户端，用于将本地TCP、UDP服务暴露给公网NeoServer。

#### IO_Uring

* [Jasyncfio](https://github.com/ikorennoy/jasyncfio)：Jasyncfio提供了基于Linux io_uring接口的异步文件I/O API。
* [NIO_Uring](https://github.com/bbeaupain/nio_uring)：NIO_Uring是一个Java I/O库，它在底层使用io_uring。
* [Netty io_uring](https://github.com/netty/netty-incubator-transport-io_uring)：Netty为io_uring提供的实验性支持。
* [PanamaUring](https://github.com/dreamlike-ocean/PanamaUring)：这是一个探索性质的项目，使用Java的新FFI为Java引入io_uring。
* [JUring](https://github.com/davidtos/JUring)：JUring是一个高性能Java库，它使用Java的FFM API提供与Linux的io_uring异步I/O接口的绑定。

#### 网络监控

* [NetXMS](https://github.com/netxms/netxms)：NetXMS是一款开源网络和基础设施监控和管理解决方案，为IT基础设施的所有层提供性能和可用性监控以及灵活的事件处理、警报、报告和图表。
* [OpenNMS](https://github.com/OpenNMS/opennms)：OpenNMS是一个开源网络监控平台，可帮助你可视化和监控本地和分布式网络上的所有内容。
* [SIP3](https://github.com/sip3io/sip3-ansible)：SIP3是一种端到端解决方案，用于实时监控、分析和排除大量流量下的网络性能故障。
* [Hyperic HQ](https://github.com/hyperic/hq)：Hyperic HQ是一个基于Java的软件资源监测和管理平台。
* [jNetMap](https://rakudave.ch/jnetmap/)：jNetMap是一个图形网络监控和文档工具，它会每x分钟ping所有注册的设备，并根据ping的结果更新状态。

#### 网络工具

* [Nomulus](https://github.com/google/nomulus)：Nomulus是一种开源、可扩展、基于云的服务，用于运营顶级域名(TLD)，由Google开源。
* [ONOS](https://github.com/opennetworkinglab/onos)：ONOS是一个开源SDN网络操作系统，主要面向服务提供商和企业骨干网，由Linux基金会开源。
* [OpenVirteX](https://github.com/os-libera/OpenVirteX)：OVX是一个网络管理程序，可以在单个物理基础设施之上创建多个虚拟和可编程网络。
* [Angry IP Scanner](https://github.com/angryip/ipscan)：Angry IP Scanner是适用于Windows、Linux和Mac的快速且友好的网络扫描器。
* [Discourse Network Analyzer](https://github.com/leifeld/dna)：Discourse Network Analyzer是一种具有网络导出功能的定性内容分析工具。
* [Batfish](https://github.com/batfish/batfish)：Batfish是一种网络验证工具，通过分析网络设备的配置，为安全性、可靠性和合规性提供正确性保证。
* [FDT](https://github.com/fast-data-transfer/fdt)：FDT是一种高效数据传输应用程序，能够通过广域网(使用标准TCP)以磁盘速度读写。
* [ANX](https://github.com/cisco-ie/anx)：适用于Java的高级NETCONF浏览器和NETCONF客户端库，Cisco开源。
* [WHOIS](https://github.com/RIPE-NCC/whois)：WHOIS是由RIPE NCC开源的一款WHOIS协议实现工具。

#### 端口转发

* [Cling](https://github.com/4thline/cling)：Cling致力于用Java创建一个兼容UPnP的软件栈。
* [UPnP PortMapper](https://github.com/kaklakariada/portmapper)：UPnP PortMapper是一个易于使用的程序，用于管理本地网络中启用UPnP的互联网网关设备的端口映射。
* [Port Mapper](https://github.com/offbynull/portmapper)：Port Mapper项目是一个Java库，可用于在启用NAT的路由器上转发端口。
* [WeUPnP](https://github.com/bitletorg/weupnp)：WeUPnP是用Java编写的小型UPnP客户端库。
* [Cybergarage UPnP](https://github.com/cybergarage/cybergarage-upnp)：Cybergarage UPnP是面向Java开发人员的UPnP开发包。
* [WaifUPnP](https://github.com/adolfintel/WaifUPnP)：WaifUPnP是UPnP的一个非常基本的实现。
* [HPPT](https://github.com/codingmiao/hppt)：HPPT是一款可通过任意协议转发TCP端口的工具。

#### P2P

* [I2P](https://github.com/i2p/i2p.i2p)：I2P是一个匿名网络，提供一个简单的层，身份敏感的应用程序可以使用该层进行安全通信。
* [Peergos](https://github.com/Peergos/Peergos)：Peergos是一个创新性的去中心化文件存储和协作平台，它致力于提供安全、私密和可验证的在线分享与交互体验，由牛津大学、墨尔本大学等开源。
* [Diztl](https://github.com/gravetii/diztl)：用于LAN的点对点文件发现和共享工具。
* [Nightweb](https://github.com/oakes/Nightweb)：Nightweb是一款适用于Android设备和PC的应用，可帮助你连接到匿名的点对点社交网络。
* [Xeres](https://github.com/zapek/Xeres)：Xeres是一款朋友之间、去中心化且安全的通信和共享应用程序。
* [Hive2Hive](https://github.com/Hive2Hive/Hive2Hive)：Hive2Hive是一个用Java编写的开源库，用于安全、分布式、基于P2P的文件同步和共享。
* [Near](https://github.com/adroitandroid/Near)：Near是适用于Android的P2P库，用于使用UDP在本地网络上进行发现，并使用TCP套接字进行传输。

#### SDN

* [OpenDaylight](https://github.com/opendaylight)：OpenDaylight由Linux基金会支持，其目标在于开发支援软件定义网络(SDN)的各种软件工具，建立网络功能虚拟化的基础。
* [Floodlight](https://github.com/floodlight/floodlight)：Floodlight是领先的开源OpenFlow控制器，由Cisco维护。
* [Lighty](https://github.com/PANTHEONtech/lighty)：Lighty是一个由OpenDaylight提供支持的SDK，用于支持、简化和加速Java中软件定义网络(SDN)解决方案的开发，由PANTHEON开源。

#### SMB

* [jCIFS  NG](https://github.com/AgNO3/jcifs-ng)：jCIFS库的清理和改进版本。
* [SMBJ](https://github.com/hierynomus/smbj)：Java中的服务器消息块(SMB2、SMB3)实现。
* [JCIFS](https://github.com/codelibs/jcifs)：JCIFS是一个开源客户端库，以纯Java实现CIFS/SMB网络协议。

#### KCP

* [Java KCP](https://gitee.com/344453111/java-Kcp)：基于Netty实现的可靠UDP网络库(kcp算法)，包含fec实现。
* [KCP Netty](https://github.com/szhnet/kcp-netty)：基于Netty的KCP的Java实现。
* [JKCP](https://github.com/beykery/jkcp)：JKCP直接构建于UDP之上并提供方便的编程接口，只需要继承相关的类即可。

#### QUIC

* [Kwik](https://github.com/ptrd/kwik)：Kwik是QUIC协议Java的实现，Kwik最初仅作为客户端，但自2021年5月起它支持客户端和服务器。
* [Quiche4j](https://github.com/kachayev/quiche4j)：QUIC传输协议和HTTP/3的Java实现。
* [Netty QUIC Codec](https://github.com/netty/netty-incubator-codec-quic)：这是利用quiche的Netty的新型实验性QUIC编解码器。
* [Quincy](https://github.com/protocol7/quincy)：Quincy是基于Netty框架的QUIC的Java实现。

#### SNMP

* [SNMP4J](https://www.snmp4j.org/)：SNMP4J是一种企业级、免费开源且最先进的Java SNMP v1/2c/v3实现。
* [Mibble](https://github.com/cederberg/mibble)：Mibble是一个开源的Java SNMP MIB解析器库。
* [Tnm4j](https://github.com/soulwing/tnm4j)：基于Tcl Tnm扩展，简化了Java的SNMP API。
* [NetSNMPj](https://netsnmpj.sourceforge.net/)：NetSNMPj是一个开源Java库，允许Java代码使用net-snmp库执行SNMP v1、v2c和v3操作。
* [SNMP API](https://ireasoning.com/snmpapi.shtml)：SNMP API是业界领先的SNMP库，它为构建网络管理应用程序提供了高性能、跨平台的SNMP Java API。
* [DynamicSNMP](https://monfox.com/dsnmp/java-snmp-agent-sdk.html)：DynamicSNMP提供了一组通用的高级Java API，可大大简化平台无关的Java SNMP v1、v2c和v3代理软件的开发。
* [SNMP Java](https://metricshub.org/snmp-java/)：Westhawk的轻量级SNMP协议栈，基于Java编写。

#### SOCKS

* [JSocks](https://github.com/ravn/jsocks)：JSocks是一个完全用Java编写的SOCKS服务器，同时支持SOCKS4和SOCKS5协议。
* [SocksLib](https://github.com/fengyouchao/sockslib)：SocksLib是一个针对SOCKS5协议的Java库。
* [Java SOCKS Proxy Server](https://github.com/bbottema/java-socks-proxy-server)：Java SOCKS Proxy Server是Java的SOCKS 4/5服务器。
* [FlyingSocks](https://github.com/abc123lzf/flyingsocks)：该项目是基于Java Netty开发的Socks5代理客户端/服务器。
* [JenTunnel](https://github.com/ggrandes/jentunnel)：JenTunnel是一个用Java编写、非常轻量级的SOCKS和HTTP代理服务器。

#### Radius

* [TinyRadius](https://github.com/ctran/TinyRadius)：TinyRadius是一个简单、小巧且快速的Java Radius库，能够发送和接收所有类型的Radius数据包。
* [JRadius](https://github.com/coova/jradius)：JRadius是一个用于客户端和服务器的Java Radius框架。
* [TinyRadius Netty](https://github.com/globalreachtech/tinyradius-netty)：TinyRadius Netty是一个Java Radius库。
* [AAA4j Radius](https://github.com/aaa4j/aaa4j-radius)：用于构建Radius客户端和Radius服务器的Java库。

#### 以太网

* [Nzyme](https://github.com/nzymedefense/nzyme)：借助Nzyme，你可以监控所有以太网和WiFi网络流量是否存在威胁、确认预期行为并有选择地将数据转发到你的SIEM或日志管理系统。
* [Etherip](https://github.com/ornl-epics/etherip)：用于通过以太网/IP协议在AllenBradley Control Logix或Compact Logix PLC上读取和写入标签的Java库，由橡树岭国家实验室开源。
* [EtherNet/IP](https://github.com/digitalpetri/ethernet-ip)：适用于Java的异步、非阻塞EtherNet/IP客户端实现。
* [CICFlowMeter](https://github.com/ahlashkari/CICFlowMeter)：CICFlowMeter是一种用于异常检测的以太网流量双向流生成器和分析器，由约克大学开发。

#### IP库

* [Ip2region](https://github.com/lionsoul2014/ip2region)：Ip2region是一个离线IP地址定位库和IP定位数据管理框架，提供了众多主流编程语言的xdb数据生成和查询客户端实现。
* [IPAddress](https://github.com/seancfoley/IPAddress)：IPAddress是用于处理IP地址和子网(IPv4和IPv6)的Java库。
* [Qqwry Java](https://github.com/jarod/qqwry-java)：读取QQWry IP数据库的Java库。
* [Commons IP Math](https://github.com/jgonian/commons-ip-math)：Commons IP Math提供了丰富、类型安全的API，用于处理对IP资源执行的最常见操作，例如解析、以多种表示法打印、检查范围是否重叠或可以合并等。
* [Java IPv6](https://github.com/janvanbesien/java-ipv6)：Java IPv6是一个用于IPv6相关概念的Java库，例如IPv6地址、网络掩码、地址池等。
* [IpDB Java](https://github.com/ipipdotnet/ipdb-java)：IPIP.net官方支持的IP数据库ipdb格式解析库。
* [IP Info](https://gitee.com/jthinking/ip-info)：IP地理位置获取，支持获取IPv4、IPv6地址信息。
* [Ineter](https://github.com/maltalex/ineter)：用于处理IP地址、范围和子网的快速Java库。

## 工具库

* [Guava](https://github.com/google/guava)：Guava是Google的一组核心Java库，其中包括新的集合类型、不可变集合、图库以及用于并发、I/O、哈希、原始类型、字符串等的实用程序。
* [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)：AndroidUtilCode是一个功能强大且易于使用的Android库，封装了Android开发中常用的函数。
* [Apache Commons Lang](https://github.com/apache/commons-lang)：Commons Lang是一个Java实用程序类包，用于java.lang层次结构中的类。
* [Hutool](https://github.com/dromara/hutool)：Hutool是一个功能丰富且易用的Java工具库，涵盖了字符串、数字、集合、编码、日期、文件、IO、加密、数据库JDBC、JSON、HTTP客户端等一系列操作，由dromara社区开源。
* [Cactoos](https://github.com/yegor256/cactoos)：Cactoos是面向对象的Java原始类型的集合。
* [JCommon](https://github.com/facebookarchive/jcommon)：JCommon是Facebook开源的Java工具库，含并发、集合、统计/分析、配置、测试等功能。
* [Jodd](https://github.com/oblac/jodd)：Jodd是一组微框架和开发人员友好的工具和实用程序。
* [X-Core](https://github.com/TGX-Android/X-Core)：X-Core是一组可在任何项目中使用的通用Java工具和接口，由Telegram开源。
* [Phrase](https://github.com/square/phrase)：Phrase是一个Android字符串资源模板库，由Square开源。
* [Essentials](https://github.com/greenrobot/essentials)：Essentials是适用于Android和Java的通用工具和哈希函数。
* [Intellij Util](https://github.com/JetBrains/intellij-community/tree/master/platform/util)：Intellij Util包含JetBrains基于Intellij IDE的通用工具库。
* [Android Common](https://github.com/Trinea/android-common)：包含与Android开发相关的工具类。
* [UltimateAndroid](https://github.com/cymcsg/UltimateAndroid)：UltimateAndroid是一个用于开发应用程序的快速开发框架。
* [Twitter Commons](https://github.com/twitter-archive/commons)：Twitter开源的JVM公共库，已弃用。
* [RxTool](https://github.com/Tamsiree/RxTool)：RxTool是用于Android开发各式各样的工具类集合。
* [Indeed Util](https://github.com/indeedeng/util)：由Indeed开发的通用Java工具类。
* [JUtils](https://github.com/chenssy89/jutils)：JUtils包含通用的Java工具类库。
* [VJTools](https://github.com/vipshop/vjtools)：VJTools是由唯品会开源的Java编码标准、库和工具。
* [DevUtils](https://github.com/afkT/DevUtils)：DevUtils是一个Android工具库，主要根据不同功能模块，封装快捷使用的工具类及API方法调用。
* [SOFA Common](https://github.com/sofastack/sofa-common-tools)：SOFA Common是蚂蚁为其他SOFA库提供一些实用功能的库。
* [Commons Core](https://github.com/ponfee/commons-core)：Java工具类库。
* [XXL TOOL](https://github.com/xuxueli/xxl-tool)：XXL-TOOL是一个Java工具类库，致力于让Java开发更高效。
* [Blade Tool](https://github.com/chillzhuang/blade-tool)：Spring Blade 3.0架构核心工具包。
* [ACS AEM Commons](https://github.com/Adobe-Consulting-Services/acs-aem-commons)：这是包含一组可重用组件和AEM开发工具包的项目，由Adobe开源。
* [Lazy](https://github.com/l123456789jy/Lazy)：Lazy包含一些常用的工具类。
* [Algs4](https://github.com/kevin-wayne/algs4)：该项目包含普林斯顿大学开源的200多个Java算法代码。
* [XUtils](https://github.com/wyouflf/xUtils3)：XUtils包含了ORM、HTTP、图片处理等工具类。
* [LogiCommon](https://github.com/didi/LogiCommon)：LogiCommon包含认证、鉴权、管理、任务调度通用功能组件，由滴滴开源。
* [Camellia](https://github.com/netease-im/camellia)：Camellia是网易云信开发的服务器基础组件。
* [CommonUtil](https://github.com/LJWLgl/CommonUtil)：CommonUtil是一个轻便简单的Java常用工具类库。
* [Ignition](https://github.com/mttkay/ignition)：Ignition提供即用型组件和实用程序类，封装了编写Android应用时所需的大量样板代码，帮助你快速上手开发Android应用。
* [JD Commons](https://mvnrepository.com/artifact/com.jd.utils)：京东开源的用于Java开发的公共库。
* [Shawn Common Utils](https://github.com/shawntime/shawn-common-utils)：Java整理的基础工具类项目。
* [Netflix Commons](https://github.com/Netflix/netflix-commons)：Netflix OSS项目的常用工具类。
* [Confluent Commons](https://github.com/confluentinc/common)：Confluent开源的包含指标、配置和工具类的通用库。
* [LinkedIn Utils](https://github.com/LinkedInAttic/linkedin-utils)：所有Linkedin开源项目共享的基础工具类。
* [Java Util](https://github.com/metamx/java-util)：Metamarkets开源的Java和基于JVM语言的工具类代码。
* [Plexus Utils](https://github.com/codehaus-plexus/plexus-utils)：各种工具类的集合，可轻松处理字符串、文件、命令行等。
* [Monasca Common](https://github.com/openstack/monasca-common)：Monasca Common是包含可重复使用的应用程序和平台代码的模块集合，用于构建监控相关服务，由惠普开源。
* [Android Utils](https://github.com/jingle1267/android-utils)：囊括了一大部分Android应用开发过程当中常用的工具类。
* [Desugar JDK Libs](https://github.com/google/desugar_jdk_libs)：该项目包含一小部分经过简化的OpenJDK库，可以在较旧的运行时上使用，由Google开源。
* [Triava](https://github.com/trivago/triava)：Triava项目包含几个trivago的基于Java项目的核心库：缓存、集合、注解、并发库等等。
* [Bus](https://github.com/aoju/bus)：Bus是一个基础框架、服务套件，基于Java 17+编写。
* [Java Util](https://github.com/jdereg/java-util)：Java Util提供非常多与其他工具库功能不同的实用程序。
* [SoftwareMill Common](https://github.com/softwaremill/scala-common)：SoftwareMill开发的一些通用工具类。
* [LiteCommon](https://github.com/litesuits/android-common)：LiteCommon是一个Android工具库。
* [Twitter Util](https://github.com/twitter/util)：由Twitter开源的惯用、小型、通用工具库。
* [EasyAndroid](https://github.com/easyandroidgroup/EasyAndroid)：一系列简单、轻量、方便的Android开发工具集合。
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
* [DroidParts](https://github.com/droidparts/droidparts)：精心设计的Android框架，包括DI、ORM、EventBus、JSON、Log、RESTClient。
* [LAMP Util](https://github.com/zuihou/lamp-util)：LAMP Util是一套兼顾Spring Boot和Spring Cloud项目的公共工具类。
* [Honoka SDK](https://github.com/kosaka-bun/honoka-sdk)：Honoka SDK是一款包含了各式各样实用工具的Java与Kotlin工具包。
* [Xpresso](https://github.com/WantedTechnologies/xpresso)：Xpresso在Java中实现了熟悉的Pythonic方法和编码范例。
* [MicroSphere](https://github.com/microsphere-projects/microsphere-java)：MicroSphere是一个模块化的Java实用程序库，提供反射、类加载、集合、网络和注解处理等基础功能。
* [LibCommon](https://github.com/saki4510t/libcommon)：LibCommon包含一些通用的Java、Android开发工具类。
* [Skrstop Components](https://github.com/skrstop/skrstop-components)：基于Spring Boot的常用功能封装，包括通用响应、通用异常、数据库、Redis、远程存储、常用自定义注解、多数据源等。
* [Legacy Lands Libaray](https://github.com/LegacyLands/legacy-lands-library)：Legacy Lands Libaray为现代Minecraft插件开发提供了必要的工具和实用程序。
* [Abacus Common](https://github.com/landawn/abacus-common)：Abacus Common是一个通用的Java编程库，它提供了一组丰富的实用程序、数据结构和函数API。
* [OstermillerUtils](https://ostermiller.org/utils/)：OstermillerUtils是一组开源的Java实用程序。

## Bean映射&复制

* [MapStruct](https://github.com/mapstruct/mapstruct)：MapStruct是一个Java注解处理器，用于为Java bean类生成类型安全且高性能的映射器。
* [MapStruct Plus](https://github.com/linpeilie/mapstruct-plus)：MapStruct Plus是对MapStruct框架的增强。
* [Dozer](https://github.com/DozerMapper/dozer)：Dozer是一种Java Bean到Java Bean映射器，它将数据从一个对象递归复制到另一个对象。
* [Tamper](https://github.com/alibaba/tamper)：Tamper是一款处理Bean/Map进行属性复制映射的工具，支持递归、集合等深度映射，由阿里开源。
* [ModelMapper](https://github.com/modelmapper/modelmapper)：ModelMapper是一个智能对象映射库，可以自动将对象相互映射。
* [Orika](https://github.com/orika-mapper/orika)：Orika是一种Java Bean映射框架，可将数据从一个对象递归复制到另一个对象。
* [EasyMapper](https://github.com/EasyMapper/EasyMapper)：EasyMapper是一个易于使用的Java对象映射库，旨在简化表示域中对象的模型之间映射值的过程。
* [JMapper](https://github.com/jmapper-framework/jmapper-core)：JMapper是集优雅、高性能和稳健性于一体的Java Bean映射器。
* [Apache Commons Beanutils](https://github.com/apache/commons-beanutils)：Commons BeanUtils提供了一个易于使用但灵活的反射和内省包装器。
* [Android Transformer](https://github.com/txusballesteros/android-transformer)：Android Transformer是一个Java库，用于管理POJO对象之间的对象转换。
* [Selma](https://github.com/xebia-france/selma)：可以在编译时生成Java代码处理字段到字段映射的注解处理器。
* [BeanMapper](https://github.com/42BV/beanmapper)：BeanMapper是一个Java库，用于将不同的Java类映射为相似的名称。
* [ReMap](https://github.com/remondis-it/remap)：ReMap简化了对象逐个字段的转换，并大大减少了单元测试映射器类的工作量。
* [Bull](https://github.com/ExpediaGroup/bull)：Bull是一种Java Bean到Java Bean转换器，通用、灵活、可重用、可配置，并且速度非常快，由Expedia开源。
* [dOOv](https://github.com/doov-org/doov)：dOOv是一个用于类型安全域模型验证和映射的流式API。
* [Datus](https://github.com/roookeee/datus)：Datus能够在流式的函数式API中定义两个数据结构之间的转换过程。
* [Mappie](https://github.com/Mr-Mappie/mappie)：Mappie是一款Kotlin多平台编译器插件，它可以生成代码来简化对象映射代码的开发。
* [Crane4j](https://github.com/opengoofy/crane4j)：一个简单易用的数据映射框架，通过简单的注解配置快速根据外键/编码值填充相关字段，支持字典、枚举、方法等多种数据源。
* [Cloning](https://github.com/kostaskougios/cloning)：Cloning是一个小型开源Java库，可深度克隆对象。
* [Konvert](https://github.com/mcarleio/konvert)：Konvert是一个使用KSP的映射代码生成器。
* [BeanUtils](https://github.com/yangtu222/BeanUtils)：BeanUtils库是一个Java bean复制实用程序，具有强大的功能和高性能。
* [ShapeShift](https://github.com/krud-dev/shapeshift)：ShapeShift是用于智能对象映射和对象之间转换的Kotlin/Java库。
* [EasyMapper](https://github.com/neoremind/easy-mapper)：EasyMapper是一个简单、轻量级、高性能的Java bean映射框架，百度开源。
* [BeanKnife](https://github.com/vipcxj/beanknife)：BeanKnife是用于自动生成DTO的注解处理器库。
* [DTOGen](https://github.com/manoelcampos/dtogen)：DTOGen是一个Java 21+库，它使用注解从给定的模型类/记录自动生成DTO记录。

## IoC

* [Spring](https://github.com/spring-projects/spring-framework)：Spring框架是Java平台的一个开源全栈应用程序框架和控制反转容器实现，由Pivotal开源。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：Micronaut是一个基于JVM的现代全栈Java框架，旨在构建模块化、易于测试的JVM应用程序，由Object Computing开源。
* [Guice](https://github.com/google/guice)：Guice是一个适用于Java 8及更高版本的轻量级依赖注入框架，由Google开源。
* [Dagger](https://github.com/google/dagger)：Dagger是一个用于依赖注入的编译时框架，它不使用反射或运行时字节码生成，在编译时进行所有分析，并生成纯Java源代码，由Square开源。
* [Koin](https://github.com/InsertKoinIO/koin)：Koin是一个面向Kotlin开发人员的实用轻量级依赖注入框架。
* [Motif](https://github.com/uber/motif)：Motif是一个DI库，提供针对嵌套作用域优化的简单API，由Uber开源。
* [Cooma](https://github.com/alibaba/cooma)：Cooma是一个简单、灵活的Java微容器实现，由阿里开发。
* [Anvil](https://github.com/square/anvil)：Anvil是一个Kotlin编译器插件，通过自动合并Dagger模块和组件接口，可以更轻松地使用Dagger进行依赖注入，由Square开发。
* [MacWire](https://github.com/softwaremill/macwire)：MacWire是SoftwareMill开源的轻量级、非侵入式Scala依赖注入库。
* [Kotlin Inject](https://github.com/evant/kotlin-inject)：Kotlin Inject是Kotlin的编译时依赖注入库。
* [PicoContainer](https://github.com/picocontainer/picocontainer)：PicoContainer是非常轻量级的IoC容器，提供依赖注入和对象生命周期管理的功能。
* [Avaje Inject](https://github.com/avaje/avaje-inject)：面向Java和Kotlin开发人员的快速、轻型依赖注入库。
* [HK2](https://github.com/eclipse-ee4j/glassfish-hk2)：HK2是Jakarta依赖注入的实现，由Oracle开发。
* [Apache DeltaSpike](https://github.com/apache/deltaspike)：DeltaSpike是一套可移植的CDI扩展，旨在使使用CDI和Java EE时的应用程序开发变得更加容易。
* [Javax Inject](https://github.com/javax-inject/javax-inject)：Javax Inject是JSR-330依赖注入标准。
* [Java IoC](https://github.com/ibm/java-ioc)：Java控制反转框架，由IBM开发。
* [Katana](https://github.com/rewe-digital/katana)：Katana是适用于JVM上的Kotlin的轻量级、简约的依赖注入库，专为Android而设计。
* [Scout](https://github.com/yandex/scout)：Scout是一个运行时依赖注入库，由Yandex开源。
* [Knit](https://github.com/tiktok/knit)：Knit是一个纯静态、编译时安全的DI框架，它利用Kotlin语言特性提供零中间依赖注入，并且非常易于使用，由Tiktok开发。
* [Fairy](https://github.com/FairyProject/fairy)：Fairy是一个针对跨平台大型Minecraft应用程序插件优化的框架。
* [Apache OpenEJB](https://openejb.apache.org/)：OpenEJB是一个开源、可嵌入、轻量级的EJB容器系统和EJB服务器。
* [Apache OpenWebBeans](https://github.com/apache/openwebbeans)：OpenWebBeans是CDI 2.0规范的实现，最初由OW2开发。
* [Eclipse Sisu](https://github.com/eclipse/sisu.inject)：Sisu是一个基于JSR330的模块化容器，支持类路径扫描、自动绑定和动态自动装配，由Sonatype开发。
* [Weld](https://github.com/weld/core)：Weld是CDI的参考实现，由RedHat开源。
* [Coody](https://gitee.com/coodyer/Coody-Framework)：Coody是一个国产IoC框架，轻量级、简单快速。
* [Grapht](https://github.com/grouplens/grapht)：Grapht是一个轻量级的依赖注入器，由明尼苏达大学开源。
* [Scaldi](https://github.com/scaldi/scaldi)：Scaldi提供了一种简单而优雅的方式在Scala中进行依赖注入。
* [Kodein](https://github.com/kosi-libs/Kodein)：Kodein是一个简单但非常有用的依赖项检索容器，使用和配置都很轻松。
* [Transfuse](https://github.com/johncarl81/transfuse)：Transfuse是一个专门针对Google Android API的Java依赖注入和集成库。
* [Governator](https://github.com/Netflix/governator)：Governator是一个扩展和工具库，可增强Google Guice以提供注入器生命周期，并通过@PostConstruct和@PreDestroy支持对象生命周期，由Netflix开源。
* [Toothpick](https://github.com/stephanenicolas/toothpick)：Toothpick是一个基于作用域树的Java依赖注入库。
* [Feather](https://github.com/zsoltherpai/feather)：Feather是一个适用于Java和Android的超轻量级依赖注入(JSR-330)库。
* [JayWire](https://github.com/vanillasource/jaywire)：JayWire是一个非常小、轻量级的Java 8依赖注入框架。
* [Mini Spring](https://github.com/DerekYRC/mini-spring)：Mini Spring是简化版的Spring框架，能帮助你快速熟悉Spring源码和掌握Spring的核心原理。
* [Tiny Spring](https://github.com/code4craft/tiny-spring)：Tiny Spring是为了学习Spring的而开发的，可以认为是一个Spring的精简版。
* [Metro](https://github.com/ZacSweers/metro)：适用于Kotlin的多平台编译时依赖注入框架。
* [Ulfberht](https://github.com/afollestad/ulfberht)：Ulfberht是一个小而强大且固执己见的DI库。
* [Yatagan](https://github.com/yandex/yatagan)：Yatagan是一个基于Google的Dagger2 API的快速依赖注入框架，由Yandex开源。
* [Whetstone](https://github.com/deliveryhero/whetstone)：Whetstone提供了一种将Dagger和Anvil合并到Android应用程序中的简化方法。
* [Kapsule](https://github.com/gouline/kapsule)：Kotlin的极简依赖注入库。
* [PopKorn](https://github.com/corbella83/PopKorn)：PopKorn是一款简单、功能强大且轻量级的Kotlin多平台依赖注入器。
* [Injekt](https://github.com/IVIanuu/injekt)：Kotlin的下一代依赖注入库。
* [Magnet](https://github.com/sergejsha/magnet)：Magnet是一个简洁、基于作用域树的依赖注入库，专为高度模块化的Android应用程序而设计。
* [OfficeFloor](https://github.com/officefloor/OfficeFloor)：OfficeFloor是一个IoC库，可以通过一流的程序构建应用程序。
* [Inverno](https://github.com/inverno-io/inverno-core)：Inverno项目为Java平台提供了控制反转和依赖注入框架，所有内容都在编译期间静态验证和完成。
* [JBoss MSC](https://github.com/jboss-msc/jboss-msc)：JBoss MSC是Java的轻量级高并发依赖注入容器。
* [SIRIUS Kernel](https://github.com/scireum/sirius-kernel)：提供通用核心类和依赖注入微内核，为所有SIRIUS应用程序提供支持。
* [Lightsaber](https://github.com/MichaelRocks/lightsaber)：Lightsaber的目标是提供闪电般快速的编译时依赖注入，同时不依赖APT。

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
* [Tinylog](https://github.com/tinylog-org/tinylog)：Tinylog是一个适用于Java、Kotlin、Scala和Android的轻量级日志框架。
* [Blitz4j](https://github.com/Netflix/blitz4j)：Blitz4j是一个构建在Log4j之上的日志框架，用于减少争用并实现高度可扩展的日志记录，而不会影响应用程序性能特征，由Netflix开源。
* [Kotlin Logging](https://github.com/oshai/kotlin-logging)：Kotlin的轻量级多平台日志框架，方便且高性能的日志记录门面。
* [Apache DistributedLog](https://github.com/twitter-archive/distributedlog)：DistributedLog是一种高吞吐量、低延迟的复制日志服务，提供持久性、复制和强一致性，由Twitter开发。
* [JBoss Logging](https://github.com/jboss-logging/jboss-logging)：JBoss Logging是一个日志门面，可以绑定到不同的日志管理器。
* [Scala Logging](https://github.com/lightbend-labs/scala-logging)：Scala Logging是一个包装SLF4J的方便快捷的日志库，由Lightbend开源。
* [Logger](https://github.com/orhanobut/logger)：简单、功能强大的Android日志记录器。
* [BqLog](https://github.com/Tencent/BqLog)：BqLog是一款轻量级、高性能的日志系统，应用于王者荣耀等项目中，由腾讯开源。
* [Timbre](https://github.com/taoensso/timbre)：Timbre是纯Clojure/Script日志记录库。
* [Google Cloud Logging](https://github.com/googleapis/java-logging)：用于Java的Google Cloud Logging客户端库。
* [GFLog](https://github.com/epam/gflog)：GFLog是适用于Java 8+的高效无垃圾日志记录框架，由EPAM开源。
* [Timber](https://github.com/JakeWharton/timber)：Timber是一个带有小型可扩展API的记录器，它在Android的普通Log类之上提供实用程序。
* [MinLog](https://github.com/EsotericSoftware/minlog)：MinLog一个小型Java日志库，其特点是零开销、极其轻便、简单高效。
* [XLog](https://github.com/elvishew/xLog)：XLog是适用于Android和Java的轻量、强大且灵活的记录器。
* [Hugo](https://github.com/JakeWharton/hugo)：用于调试版本的注解触发方法调用日志记录。
* [P6Spy](https://github.com/p6spy/p6spy)：P6Spy是一个框架，无需对应用程序进行任何代码更改即可无缝拦截和记录数据库数据。
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
* [LogUtils](https://github.com/pengwei1024/LogUtils)：更方便易用的Android日志管理器。
* [Logback Android](https://github.com/tony19/logback-android)：Logback Android是用于Android的精简版Logback。
* [Zerolog](https://github.com/obsidiandynamics/zerolog)：Zerolog是一个日志门面，适用于性能敏感应用程序。
* [Yolo](https://github.com/ustream/yolo)：Java中的日志尾随和解析框架，Ustream开源。
* [BizLog](https://github.com/mouzt/mzt-biz-log)：Spring Boot注解通用操作日志组件，美团员工开源。
* [Napier](https://github.com/AAkira/Napier)：Napier是Kotlin Multiplatform的记录器库。
* [KLogging](https://github.com/klogging/klogging)：KLogging是一个纯Kotlin日志库，它使用Kotlin习惯用法来创建记录器和发送日志事件。
* [Log4JDBC](https://github.com/arthurblake/log4jdbc)：Log4JDBC是一个Java JDBC驱动程序，可以使用SLF4J记录其他JDBC驱动程序的SQL和/或JDBC调用。
* [OWASP Security Logging](https://github.com/augustd/owasp-security-logging)：用于记录安全相关事件的标准Java API。
* [Rainbow Gum](https://github.com/jstachio/rainbowgum)：Rainbow Gum是一个快速、小型、JDK 21+、GraalVM原生友好的SLF4J日志框架。
* [LogEvents](https://github.com/jhannes/logevents)：LogEvents是一个小型日志记录框架，构建在SLF4J之上。
* [Scribe](https://github.com/outr/scribe)：Scribe从零开始构建，旨在在Scala、Scala.js和Scala Native中提供快速高效的日志记录。
* [Woof](https://github.com/LEGO/woof)：一个纯粹的Scala 3日志库，没有运行时反射，由乐高开源。
* [Log4k](https://github.com/smyrgeorge/log4k)：适用于Kotlin多平台的全面日志记录和跟踪解决方案。
* [Stream Log](https://github.com/GetStream/stream-log)：Stream Log是Kotlin Multiplatform的轻量级且可扩展的记录器库。
* [Kermit](https://github.com/touchlab/Kermit)：Touchlab的Kermit是一个Kotlin多平台集中式日志记录实用程序。

#### 日志采集

* [Timbermill](https://github.com/salesforce/Timbermill)：Timbermill是专为ElasticSearch构建的高级开源日志服务，Salesforce开源。
* [Apache Flume](https://github.com/apache/logging-flume)：Flume是一种分布式、可靠且可用的服务，用于高效收集、聚合和移动大量日志数据，由Cloudera开源。
* [Graylog](https://github.com/Graylog2/graylog2-server)：Graylog是一个免费开源的日志管理平台。
* [KnowAgent](https://github.com/didi/KnowAgent)：基于日志模板构建，采集任务动态管控、数据质量精确度量，一站式日志采集平台，由滴滴开源。
* [PlumeLog](https://gitee.com/plumeorg/plumelog)：PlumeLog是一个简单易用的Java分布式日志组件，由Plume社区开源。
* [JLog](https://gitee.com/jd-platform-opensource/jlog)：JLog是京东开源的海量日志搜集、传输、存储解决方案。
* [Fluent Logger](https://github.com/fluent/fluent-logger-java)：Fluent Logger是一个Java库，用于通过Fluentd从Java应用程序记录事件。
* [Syslog4j](https://github.com/syslog4j/syslog4j)：Syslog4j提供Syslog协议(RFC 3164)和结构化Syslog协议(RFC 5424)的客户端和服务器实现，由JetBrains开源。
* [Journal.IO](https://github.com/sbtourist/Journal.IO)：Journal.IO是一种轻量级、快速且易于使用的日志存储实现，基于仅追加旋转日志和校验和可变长度记录，支持并发读写、动态批处理、可调持久性和数据压缩。
* [Singer](https://github.com/pinterest/singer)：Singer是一个高性能日志代理，用于将日志上传到Kafka，由Pinterest开源。
* [Puree](https://github.com/cookpad/puree-android)：Puree是一个日志收集器，由Cookpad开源。
* [Fluency](https://github.com/komamitsu/fluency)：Fluentd和Fluent Bit(以及AWS S3和Treasure Data)的高吞吐量数据提取记录器。
* [Log4a](https://github.com/pqpo/Log4a)：Log4a是一个基于Mmap、高性能、高可用的Android日志收集框架。
* [LogWise](https://github.com/ds-horizon/logwise)：Logwise是一款轻量级、开源解决方案，旨在让日志管理更简洁、更快捷、更适合开发者，由Dream11开源。

#### 请求/响应记录

* [Logbook](https://github.com/zalando/logbook)：Logbook是一个可扩展的Java库，可为不同的客户端和服务器端技术启用完整的请求和响应日志记录，由Zalando开源。
* [Spring Boot Logging](https://github.com/piomin/spring-boot-logging)：用于记录Spring Boot应用程序的HTTP请求/响应以及与Elastic Stack集成的库。
* [Logging Interceptor](https://github.com/ihsanbal/LoggingInterceptor)：Logging Interceptor是一个OkHttp拦截器，具有漂亮的请求和响应记录器，以及Mock支持。
* [Repose](https://github.com/rackerlabs/repose)：Repose为API处理任务提供解决方案，例如身份验证、速率限制、API验证、HTTP请求日志记录等等。
* [OkLog](https://github.com/simonpercic/OkLog)：OkHttp的网络日志记录拦截器。

#### 日志追踪

* [TLog](https://gitee.com/dromara/TLog)：TLog是一个轻量级的分布式日志标记追踪神器，由dromara社区开源。
* [MinBox Logging](https://gitee.com/minbox-projects/minbox-logging)：MinBox Logging是一款分布式、零侵入式的链路日志分析框架。
* [Log Record](https://github.com/qqxx6661/log-record)：Log Record可以通过Java注解优雅的记录操作日志，并支持SpEL表达式、自定义上下文、自定义函数、实体类DIFF等功能。
* [Trace4j](https://github.com/husthuke/trace4j)：基于注解的轻量级Java流程跟踪工具。

#### 日志分析

* [OtrosLogViewer](https://github.com/otros-systems/otroslogviewer)：OtrosLogViewer是一款用于分析应用程序日志和堆栈跟踪的软件。
* [LogoRRR](https://github.com/rladstaetter/LogoRRR)：LogoRRR是一款跨平台日志分析工具，它提供了一种清晰、快速的方式来浏览大型文本文件，通过其交互式、用户友好的界面强调关键事件。
* [LogViewer](https://github.com/sevdokimov/log-viewer)：LogViewer是一个Web应用程序，用于在浏览器中实时监控服务器日志。
* [JLogViewer](http://jlogviewer.sourceforge.net)：JLogViewer是一个轻量级纯Java图形应用程序，可轻松查看和管理由“java.util.logging”包生成的日志文件。
* [Vigilog](https://vigilog.sourceforge.net/index.html)：Vigilog是一款易于使用的日志文件查看器，支持即时过滤、颜色过滤器等。
* [LogFX](https://github.com/renatoathaydes/LogFX)：LogFX是一个多平台、免费和开源的日志查看器，旨在处理非常大的文件而不影响性能。
* [LogMX](https://logmx.com/)：LogMX是一种直观的跨平台工具，供开发人员和管理员分析日志文件，由LightySoft软件公司提供。
* [Lilith](https://github.com/huxi/lilith)：Lilith是Logback、Log4j、Log4j2和JUL的日志和访问事件查看器。
* [Apache Chainsaw](https://github.com/apache/logging-chainsaw)：Apache Chainsaw是一个GUI日志文件查看器。
* [Miaocha](https://github.com/Hinadt-Inc/miaocha)：Miaocha是一款专为企业设计的开源日志分析平台。
* [LogParser](https://github.com/nielsbasjes/logparser)：Apache HTTPD和Nginx访问日志解析器。
* [Giant Log Viewer](https://github.com/sunny-chung/giant-log-viewer)：一款跨平台桌面便携应用程序，可在“less”不可用时立即查看任意大小的文本文件。

#### Logback Appender

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
* [Logback MDC TTL](https://github.com/ofpay/logback-mdc-ttl)：Logback扩展，支持跨线程池的MDC跟踪。

#### 结构化日志

* [Java Grok](https://github.com/thekrakken/java-grok)：使用Java Grok，你可以将非结构化日志和事件数据转换为结构化数据(JSON)。
* [ECS Logging Java](https://github.com/elastic/ecs-logging-java)：ECS Logging Java可帮助开发者轻松地实现结构化日志。
* [Structured Logging](https://github.com/dm-drogeriemarkt/structured-logging)：构化日志实用程序，设计用于与Logback和Logstash配合使用。
* [Penna](https://github.com/hkupty/penna)：Penna是SLF4j的一个后端，专注于以JSON格式将结构化日志记录到控制台。
* [Astra](https://github.com/slackhq/astra)：Astra是由Slack和Salesforce开发的结构化日志搜索和分析引擎。
* [Terse Logback](https://github.com/tersesystems/terse-logback)：Terse Logback是Logback扩展的集合，功能包括结构化日志记录、跟踪和可观察性。
* [CloudFoundry Java Logging](https://github.com/SAP/cf-java-logging-support)：CloudFoundry的Java日志记录支持，可以创建结构化日志消息和收集请求指标，由SAP开源。
* [Echopraxia](https://github.com/tersesystems/echopraxia)：Echopraxia是一个围绕结构化日志记录设计的Java API。
* [Structlog4j](https://github.com/jacek99/structlog4j)：基于SLF4J API的结构化日志Java。

## 缓存库

#### 本地缓存

* [Guava Cache](https://github.com/google/guava)：Google Guava库提供的Java本地缓存工具。
* [Caffeine](https://github.com/ben-manes/caffeine)：Caffeine是一个高性能、接近最佳的缓存库。
* [Ehcache](https://github.com/ehcache/ehcache3)：Ehcache是一种基于标准的开源缓存，可提高性能、减轻数据库负载并简化可扩展性，由Terracotta公司开源。
* [Hollow](https://github.com/Netflix/hollow)：Hollow是一个Java库和工具集，用于将内存数据集从单个生产者传播到许多消费者，以实现高性能只读访问，由Netflix开源。
* [DiskLruCache](https://github.com/JakeWharton/DiskLruCache)：基于磁盘的LRU缓存的Java实现，专门针对Android兼容性。
* [ASimpleCache](https://github.com/yangfuhai/ASimpleCache)：ASimpleCache是一个为Android制定的轻量级开源缓存框架。
* [RxCache](https://github.com/VictorAlbertos/RxCache)：RxCache是一个适用于Android和Java的响应式缓存库，可将你的缓存需求转化为接口。
* [Cache2K](https://github.com/cache2k/cache2k)：Cache2K是一个内存中高性能Java缓存库。
* [Store](https://github.com/nytimes/Store)：Store是用于异步数据加载和缓存的Java库，由纽约时报开源。
* [MicroStream](https://github.com/microstream-one/microstream)：MicroStream是一个突破性的Java原生对象图持久层，专为需要轻量级高性能持久层的微服务和Serverless函数而构建。
* [J2Cache](https://gitee.com/ld/J2Cache)：J2Cache是OSChina目前正在使用的二级缓存框架。
* [Cache4k](https://github.com/ReactiveCircus/cache4k)：Kotlin Multiplatform的内存缓存。
* [Reservoir](https://github.com/anupcowkur/Reservoir)：Reservoir是一个简单的Android库，允许你使用键/值对轻松序列化对象并将其缓存到磁盘。
* [LayerCache](https://github.com/appmattus/layercache)：使Android和Java的缓存变得简单。
* [Kache](https://github.com/MayakaApps/Kache)：Kache是一个轻量级的Kotlin Multiplatform缓存库，支持内存和持久缓存，并支持不同的驱逐策略。
* [OHC](https://github.com/snazy/ohc)：Java堆外缓存解决方案。
* [Cache](https://github.com/houbb/cache)：Cache用于实现一个可拓展的高性能本地缓存。
* [KCache](https://github.com/rayokota/kcache)：KCache是一个客户端库，它提供由Kafka中的压缩主题支持的内存缓存。
* [Cache4j](https://cache4j.sourceforge.net/)：Java对象的缓存，简单的API和快速的实现。
* [Imcache](https://github.com/Cetsoft/imcache)：Imcache是一个Java缓存库，旨在通过提供管理缓存数据的方法来加速应用程序。
* [JCache RI](https://github.com/jsr107/RI)：JCache的参考实现。
* [Xanthic](https://github.com/Xanthic/cache-api)：该库提供了一个简化的接口，用于与JVM上的内存缓存实现进行交互。
* [QuitNow Cache](https://github.com/fewlaps/quitnow-cache)：JVM应用的临时缓存。
* [OffHeap Store](https://github.com/Terracotta-OSS/offheap-store)：OffHeap Store是一个库，提供一组Map和缓存实现，用于在普通Java堆之外存储数据。
* [Apache DirectMemory](https://directmemory.apache.org/)：Apache DirectMemory是一种多层缓存实现，具有堆外内存存储，可在不降低JVM性能的情况下缓存Java对象。
* [DualCache](https://github.com/vincentbrison/dualcache)：DualCache库提供两层缓存，一层在RAM上，一个位于磁盘之上。
* [ObjectCache](https://github.com/iainconnor/ObjectCache)：Android中一个简单的对象缓存。
* [RxCache](https://github.com/fengzhizi715/RxCache)：RxCache是一款支持Java和Android的Local Cache，目前支持内存、堆外内存、磁盘缓存。
* [CarbonJ](https://github.com/salesforce/carbonj)：CarbonJ是Carbon Cache和Carbon Relay的直接替代品，它在设计时考虑了高性能读写吞吐量，由Salesforce开源。
* [RubiX](https://github.com/qubole/rubix)：RubiX是一个可供大数据引擎使用的轻量级数据缓存框架。
* [IgDiskCache](https://github.com/facebookarchive/ig-disk-cache)：IgDiskCache是一个容错的Android磁盘缓存库，由Instagram开源。
* [Fuse](https://github.com/kittinunf/Fuse)：适用于Android的简单通用LRU缓存。
* [Kotlin Cacheable](https://github.com/mori-atsushi/kotlin-cacheable)：Kotlin Cacheable是适用于Kotlin Multiplatform的基于注解的缓存库。

#### 分布式缓存

* [EVCache](https://github.com/Netflix/EVCache)：EVCache是一个基于Memcached和Spymemcached的缓存解决方案，主要用于AWS EC2基础设施来缓存常用数据，由Netflix开源。
* [Apache Commons JCS](https://github.com/apache/commons-jcs)：Commons JCS是一个分布式、多功能的缓存系统。
* [Carrot Cache](https://github.com/carrotdata/carrot-cache)：Carrot Cache项目旨在实现数据缓存的现代化，并允许用户通过CC框架内的可插拔组件构建自定义缓存解决方案。
* [TongRDS](https://www.tongtech.com/pctype/37.html)：TongRDS是一款高性能多并发分布式数据缓存中间件，这是东方通的商业产品。
* [ECFileCache](https://github.com/XiaoMi/ECFileCache)：ECFileCache是一个分布式文件缓存，基于纠删编码，使用Redis进行存储，由小米开发。
* [XXL-Cache](https://github.com/xuxueli/xxl-cache)：XXL-Cache是一个分布式缓存管理平台，其核心设计目标是让分布式缓存的接入和管理的更加的简洁和高效。
* [Layering Cache](https://github.com/xiaolyuh/layering-cache)：Layering Cache是一个支持分布式环境的多级缓存框架，主要解决在高并发下数据快速读取的问题。
* [L2Cache](https://github.com/ck-jesse/l2cache)：L2Cache是一个基于内存、Redis、Spring Cache实现的满足高并发场景下的分布式二级缓存框架。
* [BlazingCache](https://github.com/diennea/blazingcache)：BlazingCache是分布式Java应用程序的快速缓存。

#### 缓存管理器

* [JetCache](https://github.com/alibaba/jetcache)：JetCache是一种Java缓存抽象，它为不同的缓存解决方案提供统一的使用方式，由阿里开源。
* [AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache)：AutoLoadCache是基于AOP、注解等技术实现的高效的缓存管理解决方案。

## 批处理框架

* [Spring Batch](https://github.com/spring-projects/spring-batch)：Spring Batch是一个轻量级、全面的批处理框架，旨在支持开发对企业系统日常运营至关重要的健壮批处理应用程序。
* [Spring Cloud Data Flow](https://github.com/spring-cloud/spring-cloud-dataflow)：Spring Cloud Data Flow是一个基于微服务的工具包，用于在Cloud Foundry和Kubernetes中构建流式和批量数据处理管道。
* [Asakusa](https://github.com/asakusafw/asakusafw)：Asakusa是一个面向分布式/并行计算的全栈框架，提供了支持各种分布式/并行计算环境的开发平台和运行时库，例如Hadoop、Spark、用于批处理的M3等。
* [JBeret](https://github.com/jberet/jsr352)：JBeret是Jakarta Batch的实现，它还包含在WildFly中，以在Jakarta EE环境中提供便携式批处理支持。
* [JBatch](https://github.com/WASdev/standards.jsr352.jbatch)：JBatch是Jakarta Batch规范的兼容实现，由IBM开源。
* [Easy Batch](https://github.com/j-easy/easy-batch)：Easy Batch是一个旨在简化Java批处理的框架，它专为简单的单任务ETL作业而设计。
* [Spring Batch Plus](https://github.com/naver/spring-batch-plus)：Spring Batch Plus为Spring Batch提供了扩展功能，NAVER开源。
* [Spring Boot Batch Web](https://github.com/codecentric/spring-boot-starter-batch-web)：由Spring Boot提供支持的企业就绪、生产就绪的批处理应用程序。

## 并发编程

* [Concurrent Ruby](https://github.com/ruby-concurrency/concurrent-ruby)：Ruby的现代并发工具，可通过JRuby、TruffleRuby用于Java。
* [Lingua Franca](https://github.com/lf-lang/lingua-franca)：Lingua Franca是一种多语言协调语言，适用于并发且可能对时间敏感的应用程序，涵盖从低级嵌入式代码到分布式云和边缘应用程序，由加州大学伯克利分校开源。
* [ZIO](https://github.com/zio/zio)：ZIO是一个用于异步和并发编程的零依赖Scala库。
* [Concurrentli](https://github.com/linkedin/concurrentli)：Concurrentli扩展了java.util.concurrent的多线程类，为多线程Java程序增加了便利性、效率和新工具，由LinkedIn开源。
* [Menagerie](https://github.com/sfines/menagerie)：Menagerie是基于ZooKeeper的Java并发库。
* [PCDP](https://github.com/habanero-rice/PCDP)：PCDP是一个共享内存、教学型、并行编程框架，由佐治亚理工学院开源。
* [JCIP](https://github.com/jcip/jcip.github.com)：Java Concurrency in Practice配套代码提供的并发工具。
* [Chronicle Threads](https://github.com/OpenHFT/Chronicle-Threads)：该库提供高性能事件循环实现和实用函数来帮助处理线程和并发。
* [Atlassian Concurrent](https://bitbucket.org/atlassian/atlassian-util-concurrent)：该项目包含Atlassian内部各种产品和项目使用的并发实用程序类。
* [Conditional](https://github.com/line/conditional)：Conditional是一个超轻量级库，可帮助你组合多个条件表达式并使它们轻松异步，由Line开源。
* [High Scale Lib](https://github.com/boundary/high-scale-lib)：High Scale Lib是并发且高度可扩展的实用程序的集合，由BMC开源。
* [GPars](https://github.com/GPars/GPars)：GPars框架为Java开发人员提供了直观且安全的方法来同时处理Java或Groovy任务。
* [Async](https://github.com/OpenTSDB/async)：受Twisted API启发的异步Java处理构建块。
* [ConcurrentUtil](https://github.com/Tuinity/ConcurrentUtil)：适用于多线程安全编程的高性能实用程序。
* [AsyncService](https://github.com/JoanZapata/android-asyncservice)：AsyncService使用注解来缩短启动异步长时间任务并返回结果所需的代码。
* [Caesar](https://github.com/vbauer/caesar)：Caesar是一个小型的Java库，允许创建某个同步Bean的异步代理版本。

#### 响应式

* [RxJava](https://github.com/ReactiveX/RxJava)：RxJava是Reactive Extensions的JVM实现，由Netflix开源。
* [Reactor](https://github.com/reactor/reactor-core)：Reactor是第四代响应式库，基于Reactive Streams规范，用于在JVM上构建非阻塞应用程序，由Pivotal开源。
* [Spring Webflux](https://github.com/spring-projects/spring-framework/tree/main/spring-webflux)：Spring生态中基于Reactor的异步非阻塞Web框架。
* [Smallrye Mutiny](https://github.com/smallrye/smallrye-mutiny)：Mutiny是一个现代的Java响应式编程库，主要由RedHat维护。
* [Reactive Stream](https://github.com/reactive-streams/reactive-streams-jvm)：Reactive Streams是一项为具有非阻塞背压的异步流处理提供标准的举措，由Netflix、TypeSafe、Pivotal等公司发起。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包，由RedHat开源。
* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [Alpakka](https://github.com/akka/alpakka)：Alpakka是一个基于Reactive Streams和Akka的Java和Scala响应式企业集成库。
* [RSocket](https://github.com/rsocket/rsocket-java)：RSocket是一种二进制协议，用于字节流传输(例如TCP、WebSockets和Aeron)，由Facebook、Netflix、Pivotal等公司开源。
* [Agera](https://github.com/google/agera)：Agera是一组类和接口，可帮助为Android编写函数式、异步式和响应式应用程序，由Google开源。
* [Monix](https://github.com/monix/monix)：Monix是一个高性能Scala库，用于编写异步、基于事件的程序。
* [RD](https://github.com/JetBrains/rd)：适用于.NET、Kotlin和C++的响应式分布式通信框架，由Jetbrains开源。
* [Mobius](https://github.com/spotify/mobius)：Mobius是一个用于管理状态演化和副作用的函数响应式框架，具有用于连接Android UI和RxJava Observables的附加组件，由Spotify开源。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [REScala](https://github.com/rescala-lang/REScala)：REScala是JVM和Web上最先进的函数式响应式编程解决方案，由达姆施塔特工业大学开源。
* [Hibernate Reactive](https://github.com/hibernate/hibernate-reactive)：Hibernate ORM的响应式API，支持非阻塞数据库驱动程序以及与数据库的响应式交互。
* [Reactors.IO](https://github.com/reactors-io/reactors)：Reactors.IO是一个基于异步事件流的并发、分布式编程框架。
* [AutoDispose](https://github.com/uber/AutoDispose)：AutoDispose是一个RxJava 2+工具，用于通过处置/取消自动将RxJava流的执行绑定到提供的作用域，由Uber开源。
* [Electric](https://github.com/hyperfiddle/electric)：Electric是一种响应式和网络感知的Clojure/Script DSL，它在编程语言层完全抽象客户端/服务器状态同步，以便在动态Web应用程序中实现跨越前端/后端边界的强大组合。
* [Reaktive](https://github.com/badoo/Reaktive)：Reactive Extensions的Kotlin多平台实现。
* [Sodium](https://github.com/SodiumFRP/sodium)：面向多种语言的函数式响应式编程库。
* [Scala.Rx](https://github.com/lihaoyi/scala.rx)：Scala.Rx是Scala的变更传播库。
* [Reagent](https://github.com/JakeWharton/Reagent)：未来响应式库的实验。
* [RxNetty](https://github.com/ReactiveX/RxNetty)：RxNetty是Netty的Rx适配器。
* [Netty Reactive Streams](https://github.com/playframework/netty-reactive-streams)：Netty的Reactive Streams实现。
* [CohereFlux](https://github.com/pellse/cohereflux)：CohereFlux是一个响应式、函数式、类型安全和无状态的数据聚合框架，用于查询和合并来自多个数据源/服务的数据。
* [Reactive Commons](https://github.com/reactive-commons/reactive-commons-java)：Reactive Commons的目的是提供一组针对不同模式和实践的抽象和实现，这些模式和实践构成了响应式微服务架构的基础，由哥伦比亚银行维护。
* [Reakt](https://github.com/advantageous/reakt)：Reakt是Java的响应式接口。
* [IxJava](https://github.com/akarnokd/ixjava)：Java的Iterable Extensions，与RxJava类似。
* [Functional Reactive Lib](https://github.com/svenruppert/functional-reactive-lib)：仅使用核心Java的函数式响应库。

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
* [Vert.x Completable Future](https://github.com/cescoffier/vertx-completable-future)：Vert.x的CompletableFuture实现。

#### 协程库

* [Quasar](https://github.com/puniverse/quasar)：Quasar是一个为Java和Kotlin提供高性能轻量级线程、Actor以及其他异步编程工具的库。
* [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)：Kotlin多平台的协程支持库。
* [Kilim](https://github.com/kilim/kilim)：Kilim是一个Java消息传递框架，它提供超轻量级线程和在这些线程之间实现快速、安全、零复制消息传递的设施，由剑桥大学博士开源。
* [Coroutines](https://github.com/offbynull/coroutines)：Coroutines是一个Java工具包，允许你用Java编写协程。
* [Coroutines](https://github.com/esoco/coroutines)：该项目包含协程的纯Java实现。
* [Tascalate JavaFlow](https://github.com/vsilaev/tascalate-javaflow)：该项目包含使用Continuation开发Java应用程序的库和工具。
* [JavaCtrl](https://github.com/javactrl/javactrl)：JavaCtrl是使用字节码检测的JVM分隔Continuation的另一种实现。

#### Async/Await

* [EA Async](https://github.com/electronicarts/ea-async)：EA Async在JVM上实现Async/Await，允许程序员以顺序方式编写异步代码，由艺电开源。
* [Tascalate Async Await](https://github.com/vsilaev/tascalate-async-await)：Java版本8到17的Async/Await异步编程模型。
* [JAsync](https://github.com/vipcxj/jasync)：JAsync实现了类似es的Async-Await模式，允许开发人员以顺序方式编写异步代码。
* [Java Async-Await](https://github.com/AugustNagro/java-async-await)：Java的Async-Await支持。

#### 并行编排

* [AsyncTool](https://gitee.com/jd-platform-opensource/asyncTool)：AsyncTool是解决任意的多线程并行、串行、阻塞、依赖、回调的并行框架，由京东开源。
* [Bolts](https://github.com/BoltsFramework/Bolts-Android)：Bolts是一系列底层库的集合，旨在简化移动应用的开发，由Parse和Facebook设计。
* [JDeferred](https://github.com/jdeferred/jdeferred)：JDeferred是一个Java Deferred/Promise库，类似于JQuery的Deferred Object。
* [Gobrs Async](https://gitee.com/dromara/gobrs-async)：Gobrs Async是一款功能强大、配置灵活、带有全链路异常回调、内存优化、异常状态管理于一身的高性能多线程并发编程和动态编排框架，由dromara社区开源。
* [Trickle](https://github.com/spotify/trickle)：Trickle是一个用于编写异步代码的小型库，由Spotify开源。
* [TaskManager](https://github.com/iqiyi/TaskManager)：TaskManager是一种支持依赖关系、任务兜底策略的任务调度管理工具，由爱奇艺开源。
* [ParSeq](https://github.com/linkedin/parseq)：ParSeq是一个可以更轻松地用Java编写异步代码的框架，LinkedIn开源。
* [Nodes](https://github.com/twitter/nodes)：Nodes是一个用Java实现服务异步依赖图的库，由Twitter开源。
* [AsyncLoad](https://github.com/alibaba/asyncload)：AsyncLoad是阿里的异步并行加载工具。
* [Dexecutor](https://github.com/dexecutor/dexecutor-core)：Dexecutor是一个非常轻量级的框架，可以以可靠的方式执行依赖/独立任务，为此它提供了最少的API。
* [LiteAsync](https://github.com/litesuits/android-lite-async)：LiteAsync提供了SimpleTask、SafeTask、CachedTask等功能，方便快速开发。
* [BascomTask](https://github.com/eBay/bascomtask)：Java的轻量级、低摩擦进程内并行任务管理，由eBay开源。
* [TaskChain](https://github.com/aikar/TaskChain)：TaskChain是一个为游戏开发者设计的Java控制流程框架。
* [Spring Boot Data Aggregator](https://github.com/lvyahui8/spring-boot-data-aggregator)：Spring Boot并行数据聚合库。

#### 线程库

* [Thread Affinity](https://github.com/OpenHFT/Java-Thread-Affinity)：该库允许你将线程绑定到给定核心，这可以提高性能。
* [CoralThreads](https://www.coralblocks.com/index.php/category/coralthreads/)：CoralThreads允许你将Java线程固定到独立的CPU核心。
* [Jetlang](https://github.com/jetlang/core)：Jetlang提供了一个高性能的Java线程库。
* [JBoss Threads](https://github.com/jbossas/jboss-threads)：JBoss Threads是一个管理和执行Java线程的库。
* [IHMCRealtime](https://github.com/ihmcrobotics/ihmc-realtime)：IHMCRealtime提供JNI支持的线程库，用于将实时POSIX线程附加到正在运行的JVM进程，从而实现任务的确定性计算，由IHMC机器人实验室开源。

#### Channel

* [Ox](https://github.com/softwaremill/ox)：开发人员友好的JVM结构化并发库，基于Project Loom，由SoftwareMill开源。
* [Lois](https://github.com/flipkart-incubator/Lois)：Lois是一个Java库，提供类似GoLang的Channel抽象和实现，由Flipkart开源。
* [JOX](https://github.com/softwaremill/jox)：Java中的快速且可扩展的Channel，设计用于与Project Loom一起使用，由SoftwareMill开源。

#### 线程池

* [Hippo4j](https://github.com/opengoofy/hippo4j)：国产异步线程池框架，支持线程池动态变更、监控、报警。
* [Threadly](https://github.com/threadly/threadly)：协助安全并发Java开发的工具库，提供独特的基于优先级的线程池，以及安全分配线程工作的方法。
* [DynamicTp](https://github.com/dromara/dynamic-tp)：基于配置中心的轻量级动态线程池，内置监控告警功能，集成常用中间件线程池管理，可通过SPI自定义扩展实现，由美团开源。
* [Dirigiste](https://github.com/clj-commons/dirigiste)：Dirigiste提供了java.util.concurrent.ExecutorService的快速、功能丰富的检测版本，并提供了一种将该检测提供给控制机制的方法，该控制机制可以根据需要扩大或缩小池。
* [JADE](https://developer.jdcloud.com/article/4004)：JADE是由京东零售中台-研发架构组维护的线程池项目。
* [ThreadPool4j](https://github.com/aofeng/threadpool4j)：ThreadPool4j是一个实现多线程池的类。
* [HY.Common.TPool](https://github.com/HY-Org/hy.common.tpool)：线程池、任务、任务组、任务池，定时任务的类库。
* [ThreadDebugger](https://github.com/Jacksgong/ThreadDebugger)：线程监视器和线程池工厂。

#### Actor库

* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [Orbit](https://github.com/orbit/orbit)：Orbit是一个在JVM上使用虚拟Actor编写分布式系统的框架，由艺电开源。
* [Apache Pekko](https://github.com/apache/incubator-pekko)：Pekko是一个开源框架，用于构建并发、分布式、弹性的应用程序。
* [RACE](https://github.com/NASARace/race)：RACE是一种软件架构和框架，用于构建可配置、高度并发和分布式基于消息的系统，由NASA开源。
* [Fibry](https://github.com/lucav76/Fibry)：Fibry是一个实验性的Actor系统，其构建简单且灵活，也是第一个使用Project Loom中的虚拟线程的Java Actor系统。
* [XOOM Actor](https://github.com/vlingo/xoom-actors)：用于类型安全Actor模型的VLINGO XOOM平台SDK，使用Java和其他JVM语言提供响应式并发、高可扩展性、高吞吐量和弹性。
* [JActor](https://github.com/laforge49/JActor)：Java的Actor库。
* [Indigo](https://github.com/obsidiandynamics/indigo)：Indigo是下一代动态Actor模型框架，可以轻松编写异步和并发应用程序。
* [Proto.Actor](https://github.com/asynkron/protoactor-kotlin)：Proto.Actor是下一代Actor模型框架。
* [Pronghorn](https://github.com/oci-pronghorn/Pronghorn)：Pronghorn是一种基于Actor的框架的实用方法，它是一个用Java编写的分阶段事件驱动的单机嵌入式微框架，旨在无垃圾且内存占用小。
* [Kontraktor](https://github.com/RuedigerMoeller/kontraktor)：由分布式Actor模型提供支持的异步远程通信的无样板且一致的抽象。
* [Actr](https://github.com/zakgof/actr)：简单、快速且类型安全的Java Actor模型实现。
* [Ptolemy II](https://github.com/icyphy/ptII)：Ptolemy II是基于Actor的响应式Java框架，用于本地和分布式环境中的微服务，由加州大学伯克利分校开源。
* [ReActed](https://github.com/reacted-io/reacted)：ReActed是一个面向Actor的框架，用于创建响应式应用程序。
* [Elastic Actors](https://github.com/elasticsoftwarefoundation/elasticactors)：ElasticActors是一个Actor框架，它实现Actor模型并提供一些附加服务，例如持久性和可扩展性。

#### ThreadLocal

* [TransmittableThreadLocal](https://github.com/alibaba/transmittable-thread-local)：TransmittableThreadLocal提供一个增强的InheritableThreadLocal，即使使用线程池组件也可以在线程之间传输值，由阿里开源。
* [Context Propagation](https://github.com/talsma-ict/context-propagation)：将ThreadLocal值的快照传播到另一个线程。
* [Context Propagation](https://github.com/micrometer-metrics/context-propagation)：一个帮助跨不同类型的上下文机制(如ThreadLocal、Reactor Context等)传播上下文的库。
* [SmallRye Context Propagation](https://github.com/smallrye/smallrye-context-propagation)：MicroProfile上下文传播的SmallRye实现。

#### 并发数据结构

* [Disruptor](https://github.com/LMAX-Exchange/disruptor)：Disruptor是一个高性能线程间消息传递库，由英国外汇交易公司LMAX开发。
* [ExpiringMap](https://github.com/jhalterman/expiringmap)：ExpiringMap是一种高性能、低开销、零依赖、线程安全的ConcurrentMap实现，可让键值对过期。
* [JCTools](https://github.com/JCTools/JCTools)：JCTools旨在提供JDK目前缺少的一些并发数据结构。
* [ConcurrentLinkedHashMap](https://github.com/ben-manes/concurrentlinkedhashmap)：java.util.LinkedHashMap的高性能版本，用作软件缓存。
* [ConcurrencyFreaks](https://github.com/pramalhe/ConcurrencyFreaks)：并发数据结构和同步机制的库。
* [Java Concurrent Hash Trie Map](https://github.com/romix/java-concurrent-hash-trie-map)：这是Scala集合库中并发trie HashMap实现的Java端口。
* [Concurrent Trees](https://github.com/npgall/concurrent-trees)：Java的并发Radix和后缀树。
* [Weak Lock Free](https://github.com/raphw/weak-lock-free)：这是一个并发、无锁HashMap的微型实现，具有弱键，其中键尊重引用相等性。
* [Linked Blocking Multi Queue](https://github.com/marianobarrios/linked-blocking-multi-queue)：Linked Blocking Multi Queue是一个并发集合，它扩展了现有的Java并发集合库，提供了基于链接节点的可选有界阻塞“多队列”。
* [Evictor](https://github.com/stoyanr/Evictor)：Evictor是一个Java库，它提供了java.util.concurrent.ConcurrentMap的实现，支持定时条目驱逐缓存。
* [Low Latency Primitive ConcurrentQueues](https://github.com/RobAustin/low-latency-primitive-concurrent-queues)：低延迟、无锁、原始有界阻塞队列，由原始数组(如int[])支持。

#### 竞争检测

* [RAPID](https://github.com/focs-lab/rapid)：RAPID是一个用于实现动态竞争检测引擎的轻量级框架，由新加坡国立大学开源。
* [RoadRunner](https://github.com/stephenfreund/RoadRunner)：RoadRunner是一种精确而高效的动态竞争检测器，由威廉姆斯学院开源。
* [RV Predict](https://runtimeverification.com/predict)：RV-Predict是一款既可靠又极佳的动态数据竞争检测器。

## 功能切换

* [Togglz](https://github.com/togglz/togglz)：Togglz是Java功能切换模式的实现。
* [FeatureProbe](https://github.com/FeatureProbe/FeatureProbe)：FeatureProbe是一项开源功能管理服务，由滴滴开发。
* [FF4j](https://github.com/ff4j/ff4j)：FF4j是功能切换模式的实现。
* [Flagship4j](https://github.com/line/Flagship4j)：Flagship4j是一个Java库，提供多个API客户端SDK以与切换系统集成，并遵循Open-Feature规范，由Line开源。
* [Flips](https://github.com/Feature-Flip/flips)：Flips是Java的功能切换模式的一种实现。
* [Piranha](https://github.com/uber/piranha)：Piranha是一个轻量级代码转换工具集，用于自动化大规模更改，由Uber开源。
* [FeatureHub](https://github.com/featurehub-io/featurehub)：FeatureHub是一个云原生平台，可帮助软件团队管理其功能，从功能标记到A/B实验以及远程或集中配置。
* [Unleash Java](https://github.com/Unleash/unleash-client-java)：适用于Java的Unleash客户端SDK。
* [Izanami](https://github.com/MAIF/izanami)：Izanami是一款共享配置、功能翻转和A/B测试服务器，非常适合微服务架构实现。
* [LaunchDarkly Java](https://github.com/launchdarkly/java-server-sdk)：LaunchDarkly是一个功能管理平台，每天提供数万亿个功能标记，帮助团队更快地构建更好的软件。
* [OpenFeature](https://github.com/open-feature/java-sdk)：OpenFeature是一个开放规范，为功能标记提供与供应商无关、社区驱动的API，可与你最喜欢的功能标记管理工具配合使用。
* [Moirai](https://github.com/Nike-Inc/moirai)：Moirai是JVM的功能标记和资源重新加载库，由Nike开源。
* [Split Java](https://github.com/splitio/java-client)：该SDK旨在与Split(受控部署平台)配合使用，通过功能标志向用户提供功能，以管理完整的客户体验。
* [Flip](https://github.com/tacitknowledge/flip)：Flip让你能够轻松地在Java应用程序中使用功能切换。
* [Optimizely Java SDK](https://github.com/optimizely/java-sdk)：Optimizely Feature Experimentation是一款面向产品开发团队的A/B测试和功能管理工具。

## 人工智能

* [Artemis](https://github.com/ls1intum/Artemis)：Artemis通过对编程练习、测验、建模任务等的即时、个人反馈，将交互式学习带入生活，由慕尼黑工业大学开源。
* [AIMA Java](https://github.com/aimacode/aima-java)：Russell和Norvig的《人工智能-一种现代的方法》中算法的Java实现。
* [EdgeChains](https://github.com/arakoodev/EdgeChains)：EdgeChains.js是一种用于生产友好的生成式AI的语法。
* [CrowdOS](https://github.com/crowdosNWPU/CrowdOS)：CrowdOS是一个适用于众包和移动众包感知的通用操作系统，可以同时处理多种类型的众包问题，由西北工业大学开发。
* [Malmo](https://github.com/microsoft/malmo)：Malmo是一个建立在Minecraft之上的人工智能实验和研究平台，由Microsoft开源。
* [AI Descartes](https://github.com/IBM/AI-Descartes)：IBM开发的用于加速基本定律符号发现的开源包。
* [Baidu AIP SDK](https://github.com/Baidu-AIP/java-sdk)：百度AI开放平台Java SDK。
* [jAER](https://github.com/SensorsINI/jaer)：用于地址事件表示(AER)神经形态处理的Java工具，由苏黎世联邦理工学院开源。

#### LLM框架

* [LangChain4j](https://github.com/langchain4j/langchain4j)：LangChain4j的目标是简化将AI/LLM功能集成到Java应用程序中。
* [Semantic Kernel](https://github.com/microsoft/semantic-kernel-java)：Semantic Kernel是Microsoft开源的SDK，它将OpenAI、Azure OpenAI和Hugging Face等大语言模型(LLM)与C#、Python和Java等传统编程语言集成在一起。
* [Spring AI](https://github.com/spring-projects/spring-ai)：Spring AI项目为开发AI应用程序提供了Spring友好的API和抽象。
* [Spring AI Alibaba](https://github.com/alibaba/spring-ai-alibaba)：Spring AI Alibaba基于Spring AI构建，是阿里云通义系列模型及服务在Java AI应用开发领域的最佳实践。
* [Agents Flex](https://gitee.com/agents-flex/agents-flex)：Agents Flex是一个用Java开发的AI应用开发框架，旨在简化AI应用开发。
* [Solon AI](https://gitee.com/opensolon/solon-ai)：Solon AI是一个Java AI(智能体)全场景应用开发框架。
* [FIT Framework](https://github.com/ModelEngine-Group/fit-framework)：Java企业级AI开发框架，提供多语言函数引擎、流式编排引擎及Java生态的LangChain替代方案。
* [LangGraph4j](https://github.com/langgraph4j/langgraph4j)：Java版LangGraph，一个使用LLM构建有状态、多参与者应用程序的库。
* [LangChain Java](https://github.com/HamaWhiteGG/langchain-java)：LangChain的Java语言实现，它使得开发LLM驱动的应用程序变得尽可能简单。
* [Langtorch](https://github.com/Knowly-ai/langtorch)：Langtorch是一个Java库，可让你轻松构建可组合的LLM应用程序。
* [XEF](https://github.com/xebia-functional/xef)：XEF是一站式库，以LLM、图像生成等形式将现代AI的力量带入你的应用程序或服务，由Xebia开源。
* [LangStream](https://github.com/LangStream/langstream)：LangStream是一个用于构建和运行GenAI应用程序的框架，DataStax开源。
* [Java LangChain](https://github.com/Starcloud-Cloud/java-langchain)：Java LangChain是一个Java 8+的LangChain实现，在Java环境中构建强大的基于LLM的应用程序。
* [ChocoBuilder](https://github.com/unit-mesh/choco-builder)：ChocoBuilder是一款开源的LLM应用开发框架，旨在帮助你轻松打造强大的软件开发SDLC、LLM生成助手。
* [JBoltAI](https://jboltai.com/)：JBoltAI是Java企业级AI应用开发框架，旨在帮助Java系统快速接入大模型能力并开发具有AI能力的功能模块。
* [DriftKit](https://github.com/driftkit-ai/driftkit-framework)：DriftKit是适用于Java的生产级AI框架。

#### LLM客户端

* [OpenAI Java](https://github.com/openai/openai-java)：OpenAI API的官方Java库。
* [OpenAI Java](https://github.com/TheoKanning/openai-java)：用于使用OpenAI的GPT API的Java库，支持GPT-3、ChatGPT和GPT-4。
* [OpenAI Kotlin](https://github.com/Aallam/openai-kotlin)：OpenAI API的Kotlin客户端，具有多平台和协程功能。
* [ChatGPT Java](https://github.com/PlexPt/chatgpt-java)：ChatGPT Java SDK，支持GPT3.5、GPT4 API。
* [ChatGPT Java](https://github.com/Grt1228/chatgpt-java)：ChatGPT的Java客户端。
* [ChatGPT Java](https://github.com/arctisio/chatgpt-java)：使用逆向工程API的OpenAI ChatGPT的轻量级Java库。
* [ChatGPT Java](https://gitee.com/grt1228/chatgpt-java)：ChatGPT的Java客户端，OpenAI官方API的Java版SDK。
* [RunAnywhere SDK](https://github.com/RunanywhereAI/runanywhere-sdks)：隐私优先的设备上AI SDK，可将强大的语言模型直接引入你的iOS和Android应用程序。
* [OpenAI Java SDK](https://gitee.com/devlive-community/openai-java-sdk)：为Java开发人员提供方便易用的SDK来与OpenAI模型的API进行交互。
* [ChatGPT Spring Boot](https://github.com/linux-china/chatgpt-spring-boot-starter)：Spring Boot ChatGPT Starter，具有ChatGPT聊天和功能支持。
* [ChatGPT Spring Boot](https://github.com/flashvayne/chatgpt-spring-boot-starter)：基于OpenAI官方API的Spring Boot Starter。
* [EDDI](https://github.com/labsai/eddi)：EDDI是一个中间件，用于连接和管理LLM API机器人，为OpenAI ChatGPT、Facebook Hugging Face、Anthropic Claude、Google Gemini和Ollama等API提供高级提示和对话管理。
* [OpenAI4j](https://github.com/ai-for-java/openai4j)：这是一个非官方的Java客户端库，可帮助你的Java应用程序与OpenAI API连接。
* [Ollama4j](https://github.com/ollama4j/ollama4j)：用于与Ollama服务器交互的Java库。
* [OpenAi4J](https://github.com/Lambdua/openai4j)：OpenAi4J是一个非官方Java库，旨在促进与OpenAI的GPT模型的交互，包括GPT4-Turbo Vision、Assistant v2等最新功能。
* [Simple OpenAI](https://github.com/sashirestela/simple-openai)：Simple OpenAI是一个Java HTTP客户端库，用于向OpenAI API发送请求并接收响应。
* [Watson Java SDK](https://github.com/watson-developer-cloud/java-sdk)：用于使用IBM Watson服务的Java SDK。
* [ZhiPu SDK](https://github.com/MetaGLM/zhipuai-sdk-java-v4)：智谱开放平台大模型接口Java SDK。
* [DeepSeek4j](https://github.com/pig-mesh/deepseek4j)：DeepSeek4j是一个用于快速集成DeepSeek AI能力的Spring Boot Starter。
* [A2A Java](https://github.com/a2aproject/a2a-java)：A2A Java提供了A2A协议的Java服务器实现，由RedHat开发。
* [Google Gen AI Java SDK](https://github.com/googleapis/java-genai)：Gemini Developer API和Vertex AI API的Java惯用SDK。
* [Anthropic Java API](https://github.com/anthropics/anthropic-sdk-java)：Anthropic Java SDK提供了从用Java编写的应用程序方便访问Anthropic REST API的功能。
* [Qianfan SDK](https://github.com/baidubce/bce-qianfan-sdk)：百度千帆大模型平台SDK。
* [AI DIAL](https://github.com/epam/ai-dial-core)：AI DIAL为不同的聊天补全和嵌入模型、助手和应用程序提供统一的API。
* [AI4j](https://github.com/LnYo-Cly/ai4j)：用于快速接入AI大模型应用的Java SDK。
* [AI Java](https://github.com/mainpropath/AI-java)：AI Java旨在简化与各大模型API的交互。
* [Intelligent Java](https://github.com/intelligentnode/IntelliJava)：IntelliJava是使用Java与最新语言模型和深度学习框架集成的终极工具。

#### 推理引擎

* [JLama](https://github.com/tjake/Jlama)：JLama是Java的现代LLM推理引擎，由DataStax开发。
* [Llama3.java](https://github.com/mukel/llama3.java)：Java中的实用Llama 3推理。
* [GPULlama3](https://github.com/beehive-lab/GPULlama3.java)：使用原生Java编写的Llama3模型，通过TornadoVM在GPU上自动加速，由曼彻斯特大学开源。
* [UOLLM](http://www.useopen.com/p/uollm/)：UOLLM是一款使用Java语言开发AI应用的中间件产品，集成使用LLM大语言模型服务器和向量数据库，永源的商业产品。
* [LLama Java](https://github.com/kherud/java-llama.cpp)：Facebook LLama的Java绑定。
* [Triton](https://github.com/triton-inference-server/client)：Triton Python、C++和Java客户端库。
* [SD4J](https://github.com/oracle/sd4j)：此仓库包含在ONNX运行时之上运行的Stable Diffusion推理的实现，由Oracle开源。
* [Open NARS](https://github.com/opennars/opennars)：Open NARS是NARS的开源版本，NARS是一个通用AI系统，设计为推理系统框架。

#### MCP

* [MCP Java SDK](https://github.com/modelcontextprotocol/java-sdk)：适用于MCP服务器和客户端的官方Java SDK，由VMware开源。
* [Wren Engine](https://github.com/Canner/wren-engine)：Wren Engine被设计为独立的语义引擎，你可以轻松地使用任何AI代理实现它，可以将其用作语义层的通用语义。
* [OneMCP](https://github.com/Gentoro-OneMCP/onemcp)：OneMCP是一个开源运行时，使AI代理可以轻松准确高效地使用你的API。
* [Coral Server](https://github.com/Coral-Protocol/coral-server)：Coral协议的实现，充当MCP服务器，为代理提供相互通信的工具。

#### 代理框架

* [Embabel](https://github.com/embabel/embabel-agent)：Embabel是一个在JVM上编写代理流的框架，它将LLM触发的交互与代码和领域模型无缝融合。
* [Koog](https://github.com/JetBrains/koog)：Koog是一个基于Kotlin的框架，旨在完全使用惯用的Kotlin语言构建和运行AI代理，由JetBrains开源。
* [ADK Java](https://github.com/google/adk-java)：ADK是一个灵活的模块化框架，用于开发和部署AI代理，由Google开发。
* [AgentScope](https://github.com/agentscope-ai/agentscope-java)：AgentScope是一个由阿里开源的新一代多智能体应用开发框架。
* [Agentic ADK](https://github.com/AIDC-AI/Agentic-ADK)：Agentic ADK是阿里巴巴国际站AI事业部推出的Agent应用开发框架，基于Google ADK和Ali LangEngine。
* [Tools4AI](https://github.com/vishalmysore/Tools4AI)：Tools4AI是100%基于Java的Agentic框架，可用于构建基于Java的AI代理，以便与企业Java应用程序集成。
* [Arc](https://github.com/eclipse-lmos/arc)：Arc项目的目标是利用Kotlin DSL的强大功能来定义一种针对构建LLM驱动的AI代理解决方案而优化的语言，由德国电信股份公司开源。
* [Apache Flink Agents](https://github.com/apache/flink-agents)：Apache Flink Agents是一个基于Apache Flink的Agentic AI框架。
* [Mem4j](https://github.com/LangMem/mem4j)：Mem4j是一个Java库，为AI代理和应用程序提供长期记忆功能。

#### AI智能体

* [JoyAgent JDGenie](https://github.com/jd-opensource/joyagent-jdgenie)：JoyAgent JDGenie是端到端的多Agent产品，对于输入的查询或者任务，可以直接回答或者解决，由京东开源。
* [Astron](https://github.com/iflytek/astron-agent)：星辰Agent是一款面向AI开发者与中小企业的企业级Agent开发平台，由科大讯飞开源。
* [JManus](https://github.com/spring-ai-alibaba/JManus)：JManus是一个高确定性的无代码Agent开发框架，由阿里开源。
* [Coze Java](https://github.com/coze-dev/coze-java)：Coze API SDK Java是一款功能强大的工具，旨在将Coze的开放API无缝集成到你的项目中。
* [Dify Java Client](https://github.com/imfangs/dify-java-client)：Dify Java Client是一个用于与Dify平台进行交互的Java客户端库。
* [Tinyflow](https://gitee.com/tinyflow-ai/tinyflow)：Tinyflow是一个轻量的AI智能体流程编排解决方案。
* [Eclipse LMOS](https://github.com/eclipse-lmos)：LMOS是一个开源、自主、与供应商无关的平台，用于在云端或本地构建和运行企业级多智能体系统，由德国电信股份公司开源。
* [SparkX](https://gitee.com/shop-sparker/spark-x)：SparkX是Spring Boot 3、PgSQL、Vue 3开发，采用大语言模型和编排的AI智能体开发平台。
* [AgentX](https://github.com/lucky-aeon/AgentX)：AgentX是一个基于大模型和多能力平台的智能Agent构建平台。
* [Innospots](https://gitee.com/innospots/innospots)：Innospots是一款开箱即用的开源企业数字化智能决策解决方案。
* [AgC](https://github.com/masaic-ai-platform/AgC)：AgC是为Open Agentic Compute提供支持的开放核心期刊平台，Open Agentic Compute是一种新的计算基质，专为大规模部署、运行和编排AI代理而构建。
* [Agent O Rama](https://github.com/redplanetlabs/agent-o-rama)：Agent O Rama是一个端到端的LLM代理平台，用于构建、跟踪、测试和监控代理，具有集成存储和一键部署功能。

#### LLMOps

* [Opik](https://github.com/comet-ml/opik)：Opik是一个用于评估、测试和监控LLM应用程序的开源平台，由Comet开源。
* [Freeplay](https://freeplay.ai/)：Freeplay让产品团队能够为客户试验、测试、监控和优化AI功能，它是一个为整个团队管理端到端LLM产品开发生命周期的工具。
* [Starwhale](https://github.com/star-whale/starwhale)：Starwhale是一个MLOps/LLMOps平台，可让你的模型创建、评估和发布变得更加轻松，由星鲸科技开源。
* [Bella OpenAPI](https://github.com/LianjiaTech/bella-openapi)：Bella OpenAPI是一个提供了丰富的AI调用能力的API网关，由贝壳开源。
* [MaxKB4j](https://gitee.com/taisan/MaxKB4j)：MaxKB4j是一款基于Java语言开发的LLM工作流应用和RAG的开源LLMOps平台。
* [Wanaku](https://github.com/wanaku-ai/wanaku)：Wanaku是一款面向AI应用的路由器，采用MCP提供支持。

#### AI Assistant

* [Lucida](https://github.com/claritylab/lucida)：Lucida是一款基于语音和视觉的智能个人助理，由密歇根大学开源。
* [SUSI.AI Server](https://github.com/fossasia/susi_server)：SUSI.AI是一款智能开源个人助理，由FOSSASIA组织开源。
* [ECA](https://github.com/editor-code-assistant/eca)：编辑器代码助手，与编辑器无关的AI配对编程能力。
* [Brokk](https://github.com/BrokkAi/brokk)：Brokk是一个能够从语义上理解代码而非仅仅将其理解为文本块的代码助手。
* [Claudine](https://github.com/xemantic/claudine)：Claudine是一个AI助手。
* [PVA](https://github.com/Cyborgscode/Personal-Voice-Assistent)：PVA是一个开源的Linux/Unix语音辅助软件。
* [IBM Watsonx Assistant Toolkit](https://github.com/watson-developer-cloud/assistant-toolkit)：IBM Watsonx Assistant Toolkit旨在帮助使用IBM Watsonx助手的开发者和数据科学家构建、部署和维护更高效的AI解决方案，以实现业务需求。

#### 机器学习

* [Ray](https://github.com/ray-project/ray)：Ray是用于扩展AI和Python应用程序的统一框架，由加州大学伯克利分校开源。
* [Angel](https://github.com/Angel-ML/angel)：Angel是一个基于参数服务器理念的高性能分布式机器学习和图计算平台，由腾讯联合北京大学开源。
* [XGBoost](https://github.com/dmlc/xgboost)：XGBoost是一个优化的分布式梯度提升库，旨在高效、灵活和便携，由NVIDIA开源。
* [Spark MLlib](https://github.com/apache/spark/tree/master/mllib)：Spark的可扩展机器学习库。
* [Alluxio](https://github.com/Alluxio/alluxio)：Alluxio是一个面向基于云的数据分析和人工智能的数据编排技术，由加州大学伯克利分校AMP实验室开源。
* [Smile](https://github.com/haifengl/smile)：Smile是一个使用Java和Scala编写的快速且全面的机器学习、NLP、线性代数、图形、插值和可视化系统。
* [MediaPipe](https://github.com/google-ai-edge/mediapipe)：MediaPipe Solutions提供了一套库和工具，可让你在应用程序中快速应用人工智能和机器学习技术，由Google开源。
* [Flink ML](https://github.com/apache/flink-ml)：Flink ML是一个提供机器学习API和基础设施的库，可简化ML管道的构建。
* [Apache Mahout](https://github.com/apache/mahout)：Mahout的目标是构建一个用于快速创建可扩展、高性能机器学习应用程序的环境。
* [Alink](https://github.com/alibaba/Alink)：Alink是基于Flink的机器学习算法平台，由阿里计算平台PAI团队开发。
* [SynapseML](https://github.com/microsoft/SynapseML)：SynapseML是一个开源库，可简化大规模可扩展机器学习管道的创建，由Microsoft开源。
* [H2O](https://github.com/h2oai/h2o-3)：H2O是一个用于分布式、可扩展机器学习的内存平台，由Oxdata开源。
* [Apache Submarine](https://github.com/apache/submarine)：Submarine是一个端到端机器学习平台，允许数据科学家创建端到端机器学习工作流程。
* [EasyML](https://github.com/ICT-BDA/EasyML)：EasyML是一种基于数据流的通用系统，可简化将机器学习算法应用于现实世界任务的过程，由中科大数据研究院开源。
* [Oryx 2](https://github.com/OryxProject/oryx)：Oryx 2是基于Spark和Kafka构建的Lambda架构的实现，专门用于实时大规模机器学习，由Cloudera开源。
* [Seldon](https://github.com/SeldonIO/seldon-server)：Seldon Server是一个机器学习平台，可帮助你的数据科学团队将模型部署到生产中。
* [Tribuo](https://github.com/oracle/tribuo)：Tribuo是Java中的机器学习库，提供多类分类、回归、聚类、异常检测和多标签分类，Oracle开源。
* [Neural Networks](https://github.com/ivan-vasilev/neuralnetworks)：Neural Networks是一些用于训练深度神经网络的算法的Java实现。
* [ML Commons](https://github.com/opensearch-project/ml-commons)：ML Commons提供了一组常见的机器学习算法，例如K-Means或线性回归，以帮助开发人员在OpenSearch中构建ML相关功能，由AWS开源。
* [AeroSolve](https://github.com/airbnb/aerosolve)：AeroSolve是一个人性化机器学习库，由Airbnb开源。
* [Photon ML](https://github.com/linkedin/photon-ml)：Photon ML是一个基于Spark的机器学习库，由LinkedIn开源。
* [PSL](https://github.com/linqs/psl)：PSL是一种用于开发概率模型的机器学习框架，由马里兰大学和加州大学圣克鲁斯分校开发。
* [Cortex](https://github.com/originrose/cortex)：Cortex是Clojure中的神经网络、回归和特征学习框架，由ThinkTopic开源。
* [QuickML](https://github.com/sanity/quickml)：QuickML是一个易于使用、功能强大且快速的Java机器学习库。
* [BIDMach](https://github.com/BIDData/BIDMach)：BIDMach是伯克利BID实验室研发的一个开源机器学习框架。
* [Datumbox](https://github.com/datumbox/datumbox-framework)：Datumbox是一个用Java编写的开源机器学习框架，可以快速开发机器学习和统计应用程序。
* [Dagli](https://github.com/linkedin/dagli)：Dagli是一个机器学习框架，可以轻松地用Java 9+编写防错误、可读、高效、可维护且可轻松部署的模型，由LinkedIn开源。
* [MLeap](https://github.com/combust/mleap)：MLeap是机器学习管道的常见序列化格式和执行引擎。
* [Sandwood](https://github.com/oracle/sandwood)：Sandwood是一种基于JVM的概率模型的语言、编译器和运行时，由Oracle开源。
* [Ytk-Learn](https://github.com/kanyun-inc/ytk-learn)：Ytk-Learn是一个分布式机器学习库，它实现了大多数流行的机器学习算法，由看云控股技术团队开源。
* [Meka](https://github.com/Waikato/meka)：MEKA项目提供了多标签学习和评估方法的开源实现，由怀卡托大学开发。
* [MLKit](https://github.com/jenly1314/MLKit)：MLKit是一个能够将Google专业的机器学习知识带到应用中的极其简单易用的封装包。
* [Mallet](https://github.com/mimno/Mallet)：Mallet是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用，由马萨诸塞大学和宾夕法尼亚大学开发。
* [AMIDST](https://github.com/amidst/toolbox)：AMIDST是用于可扩展概率机器学习的Java工具包。
* [Conjecture](https://github.com/etsy/Conjecture)：Conjecture是一个使用Scalding DSL在Hadoop中构建机器学习模型的框架，由Etsy开源。
* [Metarank](https://github.com/metarank/metarank)：Metarank是一项开源排名服务，它可以帮助你构建个性化的语义/神经搜索和推荐。
* [MOA](https://github.com/Waikato/moa)：MOA是一个用于大数据流挖掘的开源框架，它包括一系列机器学习算法和评估工具，由怀卡托大学开发。
* [JGAAP](https://github.com/evllabs/JGAAP)：JGAAP是一种允许非专家使用尖端机器学习技术解决文本归因问题的工具，由杜肯大学开源。
* [Encog](https://github.com/jeffheaton/encog-java-core)：Encog是一个纯Java机器学习框架，用于支持遗传编程、NEAT/HyperNEAT和其他神经网络技术。
* [Neuroph](https://github.com/neuroph/neuroph)：Neuroph是一个开源Java神经网络框架和神经网络开发环境。
* [Astminer](https://github.com/JetBrains-Research/astminer)：用于挖掘基于路径的代码表示的库，由JetBrains开源。
* [SimpleDNN](https://github.com/KotlinNLP/SimpleDNN)：SimpleDNN是一个用Kotlin编写的机器学习轻量级开源库，旨在支持自然语言处理任务中的相关神经网络架构。
* [Apache PredictionIO](https://github.com/apache/predictionio)：PredictionIO是一个面向开发人员、数据科学家和最终用户的开源机器学习框架。
* [Voyager](https://github.com/spotify/voyager)：Voyager是一个适用于Python和Java的近似最近邻搜索库，注重易用性、简单性和可部署性，由Spotify开源。
* [TransmogrifAI](https://github.com/salesforce/TransmogrifAI)：TransmogrifAI是一个AutoML库，用于在Spark上构建模块化、可重用、强类型的机器学习工作流，由Salesforce开源。
* [JSAT](https://github.com/EdwardRaff/JSAT)：JSAT是一个用于快速入门机器学习问题的库。
* [JavaML](https://github.com/charliermarsh/java-ml)：用Java实现的一系列标准机器学习(分类)算法。
* [Brain4J](https://github.com/brain4j-org/brain4j)：Brain4J是一个用Java编写的开源机器学习框架，设计时考虑了速度和轻量级。
* [ABAGAIL](https://github.com/pushkar/ABAGAIL)：该库包含许多互连的Java包，用于实现机器学习和人工智能算法。
* [LearnLib](https://github.com/LearnLib/learnlib)：LearnLib是一个免费、开源的用于自动机学习算法的Java库，由德国多特蒙德工业大学开发。
* [Junto](https://github.com/parthatalukdar/junto)：该工具包由各种基于图的半监督学习(SSL)算法的实现组成，包含高斯随机场、吸附和修正吸附。
* [HTM.Java](https://github.com/numenta/htm.java)：Java中的分层临时内存实现-Numenta智能计算平台的官方社区驱动Java端口。
* [Libsvm](https://github.com/cjlin1/libsvm)：Libsvm是一款简单、易用、高效的SVM分类和回归软件，由台湾大学林智仁教授开发。
* [Elasticsearch Learning](https://github.com/o19s/elasticsearch-learning-to-rank)：Elasticsearch Learning插件使用机器学习来提高搜索相关性排名。
* [ModelDB](https://github.com/VertaAI/modeldb)：ModelDB是一个开源系统，用于对机器学习模型进行版本控制，并在整个模型生命周期中跟踪ML元数据，由Manasi Vartak在MIT博士研究期间创建。
* [FeatureFu](https://github.com/linkedin/FeatureFu)：FeatureFu项目旨在为大多数机器学习任务提供创造性和敏捷的特征工程，由LinkedIn开源。
* [Feathr](https://github.com/feathr-ai/feathr)：Feathr是一个数据和人工智能工程平台，在LinkedIn生产中广泛使用多年，并于2022年开源。
* [Byzer](https://github.com/byzer-org/byzer-lang)：Byzer是一种低代码、开源和分布式编程语言，用于以云原生方式进行数据管道、分析和人工智能。
* [Neureka](https://github.com/Gleethos/neureka)：Neureka是一个轻量级、独立于平台、OpenCL加速的ND数组/张量库。
* [Morel](https://github.com/hydromatic/morel)：Morel是一个标准ML解释器，具有关系扩展，用Java实现。
* [StackNet](https://github.com/kaz-Anova/StackNet)：StackNet是一个计算、可扩展和分析框架，类似于前馈神经网络，并在多个级别使用Wolpert的堆栈泛化来提高机器学习问题的准确性，由伦敦大学开源。
* [ML4AI](https://gitee.com/sleechengn/ml4ai)：机器学习、人工智能、张量库。
* [Eggroll](https://gitee.com/WeBank/eggroll)：Eggroll是用于机器学习的简单高性能计算框架，由微众开源。
* [MLReef](https://github.com/MLReef/mlreef)：MLReef是一个开源MLOps平台，可帮助你与数千名其他用户协作、复制和共享你的机器学习工作。
* [Fregata](https://github.com/TalkingData/Fregata)：Fregata是一个基于Spark的轻量级、超快速的大规模机器学习库，并在Scala中提供高级API，由TalkingData开源。
* [RuleKit](https://github.com/adaa-polsl/RuleKit)：RuleKit是一种用于规则学习的多功能工具，基于顺序覆盖归纳算法，它适用于分类、回归和生存问题，由西里西亚理工大学开源。
* [Foundry](https://github.com/algorithmfoundry/Foundry)：Cognitive Foundry是一个开源Java库，用于构建专注于机器学习的智能系统，由桑迪亚国家实验室领导。
* [Komputation](https://github.com/sekwiatkowski/komputation)：Komputation是一个用Kotlin和CUDA C编写的JVM神经网络框架。
* [Harness](https://github.com/actionml/harness)：Harness是一个机器学习/人工智能服务器，带有许多算法的插件，包括通用推荐器。
* [DL Learner](https://github.com/SmartDataAnalytics/DL-Learner)：DL Learner是一个使用OWL、RDF和描述逻辑进行监督机器学习的框架，由德累斯顿工业大学开源。
* [Word2VEC Java](https://github.com/NLPchina/Word2VEC_java)：Word2VEC Java版本的一个实现。
* [Word2VecJava](https://github.com/medallia/Word2VecJava)：Word2Vec Java移植。
* [ML Ease](https://github.com/linkedin/ml-ease)：ML Ease是LinkedIn开源的大规模机器学习库。
* [Apache Hivemall](https://github.com/apache/incubator-hivemall)：Apache Hivemall是一个可扩展的机器学习库，可在Hive、Spark和Pig上运行，由日本Treasure Data公司开源。
* [ModernMT](https://github.com/modernmt/modernmt)：ModernMT是一种基于Fairseq Transformer模型的上下文感知、增量和分布式通用神经机器翻译技术。

#### 自然语言处理

* [CoreNLP](https://github.com/stanfordnlp/CoreNLP)：CoreNLP是一套Java核心NLP工具，用于标记化、句子分段、NER、解析、共指、情感分析等，由斯坦福开源。
* [Apache OpenNLP](https://github.com/apache/opennlp)：OpenNLP库是一个基于机器学习的工具包，用于处理自然语言文本。
* [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)：CogCompNLP包含多个自然语言处理核心库，由宾夕法尼亚大学开源。
* [FNLP](https://github.com/FudanNLP/fnlp)：FNLP主要是为中文自然语言处理而开发的工具包，也包含为实现这些任务的机器学习算法和数据集，由复旦大学开源。
* [Lingua](https://github.com/pemistahl/lingua)：Lingua是一个准确的自然语言检测库，适用于长文本和短文本。
* [DKPro Core](https://github.com/dkpro/dkpro-core)：DKPro是基于UIMA框架的自然语言处理软件组件的集合，由德国达姆施塔特工业大学开源。
* [Mallet](https://github.com/mimno/Mallet)：Mallet是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用，由马萨诸塞大学和宾夕法尼亚大学开发。
* [S-Space](https://github.com/fozziethebeat/S-Space)：S-Space包是用于构建语义空间的算法的集合，也是用于设计新的分布式语义算法的高度可扩展的库，由加州大学洛杉矶分校开源。
* [Similarity](https://github.com/shibing624/similarity)：Similarity是由一系列算法组成的Java版相似度计算工具包，目标是传播自然语言处理中相似度计算方法。
* [Jcseg](https://gitee.com/lionsoul/jcseg)：Jcseg是一个用Java开发的轻量级NLP框架。
* [Duckling](https://github.com/facebookarchive/duckling_old)：Duckling是一个Clojure库，可将文本解析为结构化数据，Facebook开源。
* [Neo4j NLP](https://github.com/graphaware/neo4j-nlp)：Neo4j NLP是提供基于图的自然语言处理功能的Neo4j插件。
* [MiNLP](https://github.com/XiaoMi/MiNLP)：MiNLP具备词法、句法、语义分析等数十个功能模块，在小米内部广泛应用。
* [NLPLang](https://github.com/NLPchina/nlp-lang)：NLPLang是一个基本包，封装了大多数NLP项目中常用工具。
* [SmoothNLP](https://github.com/smoothnlp/SmoothNLP)：专注于可解释推理的NLP工具集。
* [SimpleNLG](https://github.com/simplenlg/simplenlg)：SimpleNLG是一个简单的Java API，旨在促进自然语言的生成，最初由阿伯丁大学开发。
* [MyNLP](https://github.com/jimichan/mynlp)：MyNLP是一个生产级、高性能、模块化、可扩展的中文NLP工具包，由上海万行公司开源。
* [Apache UIMA](https://github.com/apache/uima-uimaj)：UIMA是分析大量非结构化信息以发现与最终用户相关的知识的软件系统，由IBM开源。
* [Phrasal](https://github.com/stanfordnlp/phrasal)：Phrasal是用Java编写的大型统计机器翻译系统，由斯坦福开源。
* [Apache NLPCraft](https://github.com/apache/incubator-nlpcraft)：NLPraft是一个开源库，用于为现代应用程序添加自然语言接口。
* [HeidelTime](https://github.com/HeidelTime/heideltime)：HeidelTime是海德堡大学开发的多语言、领域敏感的时间标记器。
* [NLP4J](https://github.com/emorynlp/nlp4j)：NLP4J为JVM语言提供了一个NLP工具包，由埃默里大学NLP研究小组开发。
* [Apache Joshua](https://github.com/apache/joshua)：Joshua是一个开源统计机器翻译解码器，用于基于短语、分层和基于语法的机器翻译，由约翰霍普金斯大学人类语言技术卓越中心开发。
* [ClearTK](https://github.com/ClearTK/cleartk)：ClearTK提供了一个用Java开发统计自然语言处理组件的框架，并构建在UIMA之上，由科罗拉多大学博尔德分校开发。
* [Twitter NLP](https://github.com/brendano/ark-tweet-nlp)：Tweet NLP是一个快速而强大的基于Java的标记器和词性标记器，由CMU开源。
* [GATE](https://github.com/GateNLP/gate-core)：GATE是一个开源软件工具包，能够解决几乎所有文本处理问题，由谢菲尔德大学开发。
* [SemanticVectors](https://github.com/semanticvectors/semanticvectors)：SemanticVectors从自由自然语言文本创建语义WordSpace模型，由德克萨斯大学、昆士兰科技大学开源。
* [AmbiverseNLU](https://github.com/ambiverse-nlu/ambiverse-nlu)：AmbiverseNLU是马克斯普朗克信息学研究所的自然语言理解套件。
* [Processors](https://github.com/clulab/processors)：Processors是亚利桑那大学开源的自然语言处理器。
* [LAC](https://github.com/baidu/lac)：LAC是百度自然语言处理部研发的一款联合的词法分析工具，实现中文分词、词性标注、专名识别等功能。
* [Spark NLP](https://github.com/JohnSnowLabs/spark-nlp)：Spark NLP是一个构建在Spark之上的最先进的自然语言处理库。
* [Twitter Text](https://github.com/twitter/twitter-text)：Twitter使用此代码对文本进行标记和解析，以满足平台上可用内容的期望。
* [MetaMapLite](https://github.com/lhncbc/metamaplite)：MetaMapLite的主要目标是提供近乎实时的命名实体识别器，由利斯特山国家生物医学通讯中心开源。
* [VnCoreNLP](https://github.com/vncorenlp/VnCoreNLP)：VnCoreNLP是一个快速、准确的越南语NLP标注管道，通过分词、词性标注、命名实体识别和依存句法分析等关键NLP组件提供丰富的语言标注。
* [Zemberek NLP](https://github.com/ahmetaa/zemberek-nlp)：Zemberek NLP提供土耳其语自然语言处理工具。
* [FastText](https://github.com/ivanhk/fastText_java)：Facebook FastText的Java移植。
* [Jpostal](https://github.com/openvenues/jpostal)：Jpostal是libpostal的Java绑定，用于快速国际街道地址解析/规范化。
* [BerkeleyLM](https://github.com/adampauls/berkeleylm)：用于在内存中估算、存储大型N-Gram语言模型并高效访问它们，由伯克利开源。
* [BlackLab](https://github.com/instituutnederlandsetaal/BlackLab)：BlackLab是一个基于Apache Lucene构建的语料库检索引擎，由荷兰语言研究所开源。

#### 分词器

* [Ansj](https://github.com/NLPchina/ansj_seg)：Ansj是一个基于n-Gram、CRF、HMM的中文分词的Java实现。
* [NLPIR](https://github.com/NLPIR-team/NLPIR)：NLPIR是由中科院计算所开发的分词工具。
* [Jieba Analysis](https://github.com/huaban/jieba-analysis)：结巴分词Java版，由花瓣网开源。
* [Segmenter](https://nlp.stanford.edu/software/segmenter.shtml)：Segmenter用于对中文或阿拉伯语文本中的单词进行标记化或分段，由斯坦福开源。
* [Elasticsearch IK Analysis](https://github.com/infinilabs/analysis-ik)：IK Analysis插件集成了Lucene IK分析器，并支持自定义词典，由INFINI Labs维护。
* [Pinyin Analysis](https://github.com/infinilabs/analysis-pinyin)：Pinyin Analysis插件方便汉字与拼音之间的转换，由INFINI Labs维护。
* [Sudachi](https://github.com/WorksApplications/Sudachi)：Sudachi是日语形态分析器。
* [JTokkit](https://github.com/knuddelsgmbh/jtokkit)：JTokkit是一个专为与OpenAI模型一起使用而设计的Java分词器库。
* [Kuromoji](https://github.com/atilika/kuromoji)：Kuromoji是一个独立且非常易于使用的日语形态分析器，专为搜索而设计。
* [Word](https://github.com/ysc/word)：Word是一个Java实现的分布式中文分词组件，提供了多种基于词典的分词算法。
* [Segment](https://github.com/houbb/segment)：Segment是基于结巴分词词库实现的更加灵活、高性能的Java分词实现。
* [TextRazor](https://www.textrazor.com/docs/java)：TextRazor提供完整的云或自托管文本分词基础设施。
* [IK Analyzer Solr](https://github.com/magese/ik-analyzer-solr)：Solr 7.X-8.X的IK分词器。
* [Twitter Korean Text](https://github.com/twitter/twitter-korean-text)：Twitter创建的开源韩语处理器。
* [STConvert](https://github.com/infinilabs/analysis-stconvert)：STConvert是一款将中文字符在繁体和简体之间转换的分词器，由INFINI Labs维护。
* [ElasticSearch Analysis Vietnamese](https://github.com/duydo/elasticsearch-analysis-vietnamese)：ElasticSearch越南语分词插件。
* [ElasticSearch Analysis Ansj](https://github.com/NLPchina/elasticsearch-analysis-ansj)：ElasticSearch Analysis Ansj是一个基于Ansj分词算法的ElasticSearch中文分词插件。
* [IdeaSeg](https://gitee.com/indexea/ideaseg)：IdeaSeg是Indexea推出的一个基于最新的HanLP自然语言处理工具包实现的中文分词器。
* [THULAC](https://github.com/thunlp/THULAC-Java)：THULAC是由清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包，具有中文分词和词性标注功能。
* [THUCTC](https://github.com/thunlp/THUCTC)：THUCTC是由清华大学自然语言处理实验室推出的中文文本分类工具包，能够自动高效地实现用户自定义的文本分类语料的训练、评测、分类功能。
* [ElasticSearch BosonNLP Analysis](https://github.com/bosondata/elasticsearch-analysis-bosonnlp)：玻森数据开发的一款基于玻森中文分词的ElasticSearch插件。
* [ElasticSearch Analysis HanLP](https://github.com/KennFalcon/elasticsearch-analysis-hanlp)：此分词器基于HanLP，提供了HanLP中大部分的分词方式。
* [Ik Analyzer](https://github.com/blueshen/ik-analyzer)：支持Lucene 5/6/7/8/9+版本的分词器。
* [Elasticsearch Analysis Morfologik](https://github.com/allegro/elasticsearch-analysis-morfologik)：适用于ElasticSearch 8.x、7.x、6.x、5.x和2.x的波兰语插件，由Allegro开源。
* [MMSeg4j](https://github.com/chenlb/mmseg4j-core)：MMSeg4j是使用Chih-Hao Tsai的MMSeg算法实现的中文分词器。
* [Vitk](https://github.com/phuonglh/vn.vitk)：越南语文本处理工具包，由越南河内国立大学理学院开源。
* [KOMORAN](https://github.com/shineware/KOMORAN)：KOMORAN是一个用Java实现的韩语形态分析器，由Shineware开源。

#### 深度学习

* [Eclipse Deeplearning4J](https://github.com/deeplearning4j/deeplearning4j)：Deeplearning4j是一套用于在JVM上运行深度学习的工具，由Skymind开源。
* [EasyAI](https://gitee.com/dromara/easyAi)：EasyAI是一个原生Java人工智能算法框架，由dormara社区开源。
* [Deep Java Library](https://github.com/deepjavalibrary/djl)：DJL是一个开源、高级、与引擎无关的深度学习Java框架，由AWS开源。
* [BigDL](https://github.com/intel-analytics/BigDL-2.x)：BigDL是一个使用INT4/FP4/INT8/FP8在Intel XPU上运行LLM的库，延迟非常低，由Intel开源。
* [Hbox](https://github.com/Qihoo360/hbox)：Hbox是一个结合大数据和人工智能的便捷高效的调度平台，支持多种机器学习、深度学习框架，由360开源。
* [KotlinDL](https://github.com/Kotlin/kotlindl)：KotlinDL是一个用Kotlin编写的高级深度学习API，由JetBrains开源。
* [Apache MXNet](https://mxnet.apache.org/versions/1.9.1/api/java)：Apache MXNet是一个兼顾效率和灵活性的深度学习框架，由AWS开源。
* [TonY](https://github.com/tony-framework/TonY)：TonY是一个在Hadoop上本地运行深度学习作业的框架，由LinkedIn开源。
* [Porcupine](https://github.com/Picovoice/porcupine)：Porcupine是一款高精度且轻量级的唤醒词引擎。
* [FlexNeuART](https://github.com/oaqa/FlexNeuART)：FlexNeuART是一个轻量级模块化的信息检索框架，适用于研究、教育和评估，由CMU开源。
* [DeepLearning](https://github.com/ThoughtWorksInc/DeepLearning.scala)：DeepLearning是一个简单的库，用于从面向对象和函数式编程结构创建复杂的神经网络，由ThoughtWorks开源。
* [DL Inference](https://github.com/wuba/dl_inference)：DL Inference是58同城推出的通用深度学习推理工具。
* [OpenDL](https://github.com/guoding83128/OpenDL)：OpenDL是基于Spark框架的深度学习训练库。
* [Crossbow](https://github.com/lsds/Crossbow)：Crossbow是一个用于训练深度学习模型的多GPU系统，由伦敦理工帝国学院开源。
* [Deep Netts](https://www.deepnetts.com/)：Deep Netts是一个基于Java的深度学习开发平台。
* [TensorDash](https://github.com/CleanPegasus/TensorDash)：TensorDash是一款应用程序，可让你远程监控深度学习模型的指标，并在模型训练完成或崩溃时通知你。
* [OmegaAI](https://gitee.com/dromara/omega-ai)：OmegaAI是基于Java打造的深度学习框架，帮助你快速搭建神经网络，实现训练或测试模型，引擎支持自动求导，多线程与GPU运算。
* [ADAMS](https://adams.cms.waikato.ac.nz/)：ADAMS是专门针对Java的深度学习库，由怀卡托大学开发。
* [OpenLabeler](https://github.com/kinhong/OpenLabeler)：OpenLabeler是一个用于注释对象的开源应用程序，它可以生成PASCAL VOC格式的XML注释文件，用于人工智能和深度学习训练。
* [CaffeOnSpark](https://github.com/yahoo/CaffeOnSpark)：CaffeOnSpark将深度学习引入Hadoop和Spark集群，由Yahoo开源。
* [JDLL](https://github.com/bioimage-io/JDLL)：JDLL提供了一个用于运行深度学习模型的Java库，支持Java软件和各种深度学习框架之间的通信。
* [SmartJavaAI](https://gitee.com/dengwenjie/SmartJavaAI)：SmartJavaAI是专为Java开发者打造的一个功能丰富、开箱即用的AI算法工具包。

#### 模型训练

* [ONNX Runtime](https://github.com/microsoft/onnxruntime/tree/main/java)：ONNX Runtime是一个跨平台推理和训练机器学习加速器，由Microsoft开源。
* [Xtreme1](https://github.com/xtreme1-io/xtreme1)：Xtreme1是一个用于多模态训练数据的一体化开源平台，由倍赛开发。
* [TensorFlow Java](https://github.com/tensorflow/java)：TensorFlow可以在任何JVM上运行，用于构建、训练和运行机器学习模型，Google开源。
* [TorchServe](https://github.com/pytorch/serve)：TorchServe是一种灵活且易于使用的工具，用于在生产中提供和扩展PyTorch模型，由AWS和Facebook开源。
* [Chronon](https://github.com/airbnb/chronon)：Chronon是一个抽象出数据计算复杂性并为AI/ML应用程序提供服务的平台，由Airbnb开源。
* [DJL Serving](https://github.com/deepjavalibrary/djl-serving)：DJL Serving是由DJL提供支持的高性能通用独立模型服务解决方案，由AWS开源。
* [ModelMesh](https://github.com/kserve/modelmesh)：ModelMesh框架是一个成熟的通用模型，服务于管理层/路由层，专为高规模、高密度和频繁变化的模型用例而设计，由IBM开源。
* [OpenMLDB](https://github.com/4paradigm/OpenMLDB)：OpenMLDB是一个开源机器学习数据库，为训练和推理提供计算一致特征的特征平台，由4Paradigm开源。
* [DSSTNE](https://github.com/amazon-archives/amazon-dsstne/tree/master/java)：DSSTNE是一个软件库，用于训练和部署具有稀疏输入、全连接隐藏层和稀疏输出的推荐模型，由Amazon开发。
* [Zoltar](https://github.com/spotify/zoltar)：Zoltar是一个用于在生产环境中服务TensorFlow、XGBoost和Scikit Learn模型的通用库，由Spotify开源。
* [Mobius](https://github.com/ray-project/mobius)：Mobius是一个包括实时计算和训练的人工智能基础平台，由加州大学伯克利分校开源。
* [Aurora](https://github.com/AcaiSoftware/aurora)：Aurora是用于模型训练、评估、部署、调整和基准测试的Java机器学习框架。
* [KInference](https://github.com/JetBrains-Research/kinference)：KInference是一个库，它使得在Kotlin中执行复杂的ML模型成为可能，由JetBrains开源。
* [AI Serving](https://github.com/autodeployai/ai-serving)：AI Serving是一种灵活、高性能的推理系统，适用于机器学习和深度学习模型，专为生产环境而设计。
* [Deep Learning Flink](https://github.com/flink-extended/dl-on-flink)：Deep Learning Flink旨在集成Flink和深度学习框架，以在Flink集群上实现分布式深度学习训练和推理。
* [WekaDeeplearning4j](https://github.com/Waikato/wekaDeeplearning4j)：WekaDeeplearning4j让用户能够在Weka环境中训练和测试深度学习模型，由怀卡托大学开源。
* [OpenPAI](https://github.com/microsoft/pai)：OpenPAI是一个开源平台，提供完整的AI模型训练和资源管理能力，易于扩展并支持各种规模的本地、云和混合环境，由Microsoft开源。
* [Airy](https://github.com/airyhq/airy)：Airy是一个开源流应用程序框架，用于训练ML模型并向其提供历史和实时数据。
* [Primus](https://github.com/bytedance/primus)：Primus是用于机器学习应用程序的通用分布式调度框架，它管理TensorFlow等机器学习训练器的训练生命周期和数据分布，以执行大规模分布式训练，由字节开源。
* [Serenade](https://github.com/serenadeai/serenade)：该仓库包含Serenade客户端应用程序、在线服务(如语音引擎、代码引擎和核心应用程序)和模型训练的代码。
* [Multi Model Server](https://github.com/awslabs/multi-model-server)：MMS是一种灵活且易于使用的工具，用于为使用任何ML/DL框架训练的深度学习模型提供服务，由AWS开源。

#### 强化学习

* [Java Reinforcement Learning](https://github.com/chen0040/java-reinforcement-learning)：该软件包提供了强化学习算法的Java实现，例如Q-Learn、R-Learn、SARSA、Actor-Critic。
* [BURLAP](https://github.com/jmacglashan/burlap)：BURLAP是一个Java代码库，用于开发单智能体或多智能体规划与学习算法及其相关领域，由布朗大学开源。
* [JADE](https://jade.tilab.com/)：JADE是一个用Java实现的软件代理开发框架，由意大利电信开发。

#### 贝叶斯推理

* [Rainier](https://github.com/stripe/rainier)：Rainier通过马尔可夫链蒙特卡罗为贝叶斯推理提供了高性能Scala API，由Stripe开源。
* [BEAST 2](https://github.com/CompEvol/beast2)：BEAST是一个使用分子序列MCMC进行贝叶斯推理的跨平台程序，由奥克兰大学领导开发。
* [BEAST X](https://github.com/beast-dev/beast-mcmc)：BEAST X是一款跨平台的程序，使用MCMC对分子序列进行贝叶斯分析。
* [Keanu](https://github.com/improbable-research/keanu)：Keanu是一个通用的概率编程库，由Improbable的研究团队开发。

#### 因果推理

* [Fast Causal Inference](https://github.com/Tencent/fast-causal-inference)：Fast Causal Inference是腾讯开源的因果推理项目，它是一个基于OLAP的高性能因果推理(统计模型)计算库。
* [Causal Analysis](https://github.com/algorithm-tools/CausalAnalysis)：使用Java实现指标贡献分析和因果推断的算法，有助于快速找到指标的根本原因。
* [https://github.com/IDSIA/credici](https://github.com/IDSIA/credici)：Credici是一个开源库，允许使用Credal推理方法进行因果分析。

#### 语义解析

* [Cornell SPF](https://github.com/lil-lab/spf)：Cornell SPF是康奈尔大学开发的语义分析框架。
* [SEMPRE](https://github.com/percyliang/sempre)：SEMPRE是一个工具包，它使开发新任务的语义解析器变得容易，由斯坦福开源。
* [SEMAFOR](https://github.com/Noahs-ARK/semafor)：SEMAFOR是一个自动分析英文文本框架语义结构的工具，由CMU开源。

#### 实体链接

* [FEL](https://github.com/yahoo/FEL)：快速实体链接器工具包，用于训练模型将实体链接到文档和查询中的知识库，由Yahoo开源。
* [Dexter](https://github.com/dexter/dexter)：Dexter是一个框架，它实现了一些流行的算法，并提供了开发任何实体链接技术所需的所有工具，由HPC实验室开源。
* [Inception](https://github.com/inception-project/inception)：Inception提供了一个语义标注平台，提供智能标注帮助和知识管理，由达姆施塔特工业大学开源。

#### 信息提取

* [GROBID](https://github.com/kermitt2/grobid)：GROBID是一个机器学习库，用于提取、解析和重构原始文档(例如PDF)并将其转换为结构化的XML/TEI编码文档，尤其侧重于技术和科学出版物。
* [Apache Tika](https://github.com/apache/tika)：Tika是一个工具包，用于使用现有解析器库从各种文档中检测和提取元数据和结构化文本内容。
* [Docling Java](https://github.com/docling-project/docling-java)：Docling简化了文档处理，解析了多种格式，包括高级的PDF理解，并实现了与生成式AI生态系统的无缝集成。
* [ReVerb](https://github.com/knowitall/reverb)：ReVerb是一个自动识别和提取英语句子中二元关系的程序，专为网络规模的信息提取而设计，由华盛顿大学开源。
* [DeepDive](https://github.com/HazyResearch/deepdive)：DeepDive是斯坦福开发的信息抽取系统。
* [CERMINE](https://github.com/CeON/CERMINE)：CERMINE是一个Java库和一个Web服务，用于从包含学术出版物的PDF文件中提取元数据和内容，由华沙大学开源。
* [Apache cTAKES](https://github.com/apache/ctakes)：cTAKES专注于通过NLP技术从临床文本中提取知识，由美国国立卫生研究院开源。
* [FOX](https://github.com/dice-group/FOX)：FOX是一个集成Linked Data Cloud的框架，利用NLP算法的多样性从NL中提取高精度的RDF三元组，由帕德博恩大学开源。
* [Xponents](https://github.com/OpenSextant/Xponents)：Xponents是一组信息提取库，包括提取和规范化地理实体、日期/时间模式、关键字/分类法和各种模式。
* [Wandora](https://github.com/wandora-team/wandora)：Wandora是一个基于主题图和Java的通用信息提取、管理和发布应用程序。
* [Reach](https://github.com/clulab/reach)：Reach是一个面向生物医学领域的信息提取系统，旨在读取科学文献并提取癌症信号通路，由亚利桑那大学开源。
* [Palladian](https://github.com/palladian/palladian)：Palladian是一个基于Java的工具包，提供执行典型互联网信息检索任务的功能。
* [Minie](https://github.com/uma-pi1/minie)：提供简化提取的开放信息提取系统，由德国曼海姆大学开源。
* [Textricator](https://github.com/measuresforjustice/textricator)：Textricator是一种从文档中提取文本并生成结构化数据的工具。
* [Baleen](https://github.com/dstl/baleen)：Baleen是一个文本分析框架，允许从非结构化和半结构化数据中提取信息，由英国国防科学技术实验室开源。

#### 联邦学习

* [FATE](https://github.com/FederatedAI/FATE)：FATE是全球首个工业级联邦学习开源框架，使企业和机构能够在数据上进行协作，同时保护数据安全和隐私，由微众银行开源。
* [9nFL](https://github.com/jd-opensource/9n-mpc)：九数联邦学习整体解决方案，由京东开源。
* [WeFe](https://gitee.com/tianmiantech/WeFe)：WeFe是Welab汇立集团子公司天冕科技发起的开源项目，为联邦学习生态系统提供了一套好用、可靠的安全计算框架。
* [HIGHFLIP](https://github.com/baidu/highflip)：HIGHFLIP是一个顶层联邦学习互通服务，用于解决异构联邦平台间相互通信的问题，百度开源。
* [FATE Serving](https://github.com/FederatedAI/FATE-Serving)：FATE Serving是一个高性能、工业化的联邦学习模型服务系统，由微众开源。
* [PrimiHub Platform](https://github.com/primihub/primihub-platform)：PrimiHub Platform是一个面向MPC和FL点对点服务的多方计算和多方联邦任务安全调度平台。

#### 推荐系统

* [Twitter Recommendation Algorithm](https://github.com/twitter/the-algorithm)：Twitter的推荐算法是一组服务和作业，负责在所有Twitter产品界面(例如For You时间线、搜索、探索、通知)上提供推文和其他内容的提要。
* [LibRec](https://github.com/guoguibing/librec)：LibRec是一个用于推荐系统的Java库，它实现了一套最先进的推荐算法，旨在解决两个经典的推荐任务：评级预测和项目排名。
* [TagRec](https://github.com/learning-layers/TagRec)：TagRec的目的是为社区提供一个用Java编写的简单易用的通用标签推荐框架，以便使用一组众所周知的标准来评估新的标签推荐算法，由格拉茨技术大学开源。
* [SparrowRecSys](https://github.com/wzhe06/SparrowRecSys)：SparrowRecSys是一个电影推荐系统。
* [RankSys](https://github.com/RankSys/RankSys)：RankSys是一个用于实施和评估推荐算法和技术的新框架。
* [LensKit](https://github.com/lenskit/lenskit)：LensKit是协同过滤算法的实现，也是一组用于对算法进行基准测试的工具，由明尼苏达大学开源。
* [CARSKit](https://github.com/irecsys/CARSKit)：CARSKit是一款基于Java的开源上下文感知推荐引擎。
* [Neo4j Reco](https://github.com/graphaware/neo4j-reco)：GraphAware Neo4j推荐引擎是一个基于Neo4j构建高性能复杂推荐引擎的库。
* [Samantha](https://github.com/grouplens/samantha)：Samantha是用于离线机器学习和推荐建模以及快速在线生产服务的通用推荐器和预测器服务器，由明尼苏达大学开源。
* [Universal Recommender](https://github.com/actionml/universal-recommender)：Universal Recommender是一种新型的协同过滤推荐器，其基于一种能够利用各种用户偏好指标数据的算法-相关交叉出现算法。
* [CF4j](https://github.com/ferortega/cf4j)：Java的协同过滤库，用于开展基于协同过滤的推荐系统研究实验。
* [Sifarish](https://github.com/pranab/sifarish)：Sifarish是一套基于Hadoop和Storm实现的个性化推荐解决方案。

#### 遗传算法

* [Jenetics](https://github.com/jenetics/jenetics)：Jenetics是一个遗传算法、进化算法、语法进化、遗传编程和多目标优化库。
* [MOEA](https://github.com/MOEAFramework/MOEAFramework)：MOEA框架是一个免费开源Java库，用于开发和试验多目标进化算法(MOEA)和其他通用多目标优化算法。
* [Watchmaker](https://github.com/dwdyer/watchmaker)：Watchmaker框架是一个可扩展、高性能、面向对象的框架，用于在Java中实现独立于平台的进化/遗传算法。
* [ECJ 23](https://github.com/GMUEClab/ecj)：ECJ是一个用Java编写的进化计算框架，提供了许多流行的EC算法和EC算法约定的工具，由乔治梅森大学开源。
* [JavaGenes](https://data.nasa.gov/dataset/arc-code-ti-javagenes)：JavaGenes是一个用Java编写的通用进化软件系统，由NASA开源。
* [Evolving Protozoa](https://github.com/DylanCope/Evolving-Protozoa)：该项目的目的是创造一个环境，让原生动物类实体能够进化其行为和形态，以便生存和繁殖。
* [JGAP](https://sourceforge.net/projects/jgap/)：JGAP是用Java编写的遗传算法和遗传编程包，由惠灵顿维多利亚大学开源。
* [Opt4J](https://github.com/SDARG/opt4j)：Opt4J是一个基于Java的开源进化计算框架，它包含进化算法(包括SPEA2和NSGA2)、差分进化、粒子群优化、模拟退火等一组(多目标)优化算法。
* [Eva](https://github.com/decorators-squad/eva)：Eva是进化算法的Java OOP实现，这是来自人工智能领域的概念。
* [EARS](https://github.com/UM-LPM/EARS)：EARS是一个基于Java的免费开源框架，用于对单目标和多目标进化算法进行排名、开发和实验，由马里博尔大学开源。
* [Genetic Algorithms](https://github.com/lagodiuk/genetic-algorithm)：Java中遗传算法的通用实现。
* [MergeLife](https://github.com/jeffheaton/mergelife)：使用遗传算法演化复杂的元胞自动机。
* [JGEA](https://github.com/ericmedvet/jgea)：JGEA是一个用于实验进化计算的模块化Java框架。
* [Gin](https://github.com/gintool/gin)：Gin是一种基因改良(GI)工具。
* [JCLEC](https://sourceforge.net/projects/jclec)：JCLEC是一个用Java开发的通用进化计算框架，由科尔多瓦大学开源。
* [EasyOpt](http://www.iescm.com/easyopt/)：EasyOpt这是一个轻量级的Java库，提供了遗传算法、粒子群优化等常用启发式优化算法的实现，适用于快速原型设计和教学。
* [Chips-n-Salsa](https://github.com/cicirello/Chips-n-Salsa)：Chips-n-Salsa是一个可定制、可混合、迭代、并行、随机和自适应本地搜索算法的Java库。
* [NSGA-II](https://github.com/onclave/NSGA-II)：NSGA-II的Java实现。

#### 专家系统

* [Apache Jena](https://github.com/apache/jena)：Jena是一个免费的开源Java框架，用于构建语义Web和链接数据应用程序，最初由惠普实验室开发。
* [PowerLoom](https://www.isi.edu/isd/LOOM/PowerLoom/)：PowerLoom是Loom知识表示系统的后继者，它提供了用于构建智能、基于知识的应用程序的语言和环境，由南加州大学开源。
* [D3web](https://github.com/denkbares)：D3web是一个开源推理引擎，用于开发、测试问题解决知识并将其应用于给定的问题情况，其中已经包含许多算法。
* [EYE](https://github.com/eyereasoner/eye)：EYE是一个支持语义Web层并实现Notation3的推理引擎。
* [Tweety](https://github.com/TweetyProjectTeam/TweetyProject)：Tweety是用于人工智能和知识表示的逻辑方面的Java框架的集合。

#### 认知架构

* [JSoar](https://github.com/soartech/jsoar)：Soar认知架构的纯Java实现，由密歇根大学人工智能实验室开源。
* [CST](https://github.com/CST-Group/cst)：CST是一个基于Java的工具包，用于构建认知架构，由坎皮纳斯大学开源。

#### 约束编程

* [OptaPlanner](https://github.com/apache/incubator-kie-optaplanner)：OptaPlanner是一个轻量级、可嵌入的约束满足引擎，可优化规划问题，最初由RedHat开发。
* [Timefold](https://github.com/TimefoldAI/timefold-solver)：Timefold是开源AI求解器，用于优化Java、Python或Kotlin中的操作和调度。
* [Choco Solver](https://github.com/chocoteam/choco-solver)：Choco Solver是一个用于约束编程的开源Java库，由国立南特高等矿业学院开发。
* [ACE](https://github.com/xcsp3team/ACE)：ACE是用Java开发的开源约束求解器，由阿图瓦大学开源。
* [JaCoP](https://github.com/radsz/jacop)：JaCoP是基于Java的开源求解器，由瑞典隆德大学开发和维护。
* [OptaPy](https://github.com/optapy/optapy)：OptaPy是Python的人工智能约束求解器，可优化车辆路线问题、员工排班、维护计划、任务分配、学校时间表、云优化、会议安排、作业车间调度、装箱和更多规划问题。
* [JSprit](https://github.com/graphhopper/jsprit)：JSprit是一个基于Java的开源工具包，用于解决丰富的旅行商问题(TSP)和车辆路径问题(VRP)。
* [EasyCSP](https://github.com/cordisvictor/easycsp-lib)：EasyCSP是一个用于约束满足编程的开源Java库。
* [Kiwi](https://github.com/google/kiwi-solver)：Kiwi是一款专为教育设计的简约且可扩展的约束规划求解器，由Google开源。
* [Loco](https://github.com/aengelberg/loco)：Loco是Clojure的一个约束编程库。
* [OscaR](https://bitbucket.org/oscarlib/oscar)：OscaR是一个用于解决运筹学问题的Scala工具包，由鲁汶大学开发。
* [MaxiCP](https://github.com/aia-uclouvain/maxicp)：MaxiCP是一个基于Java的约束规划(CP)求解器，用于解决调度和车辆路线问题，由鲁汶天主教大学开源。
* [CPSolver](https://github.com/UniTime/cpsolver)：CPSolver库包含一个基于本地搜索的框架，允许使用约束编程原语(变量、值、约束)对问题进行建模。
* [JSolver](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=fff2046e43828a00c406835be84b571553b65087)：JSolver扩展了面向对象基于约束的声明式编程的Java编程范式，由香港城市大学开源。
* [JMiniZinc](https://github.com/siemens/JMiniZinc)：JMiniZinc是约束建模语言MiniZinc的Java接口，由西门子开发。
* [jConstraints](https://github.com/psycopaths/jconstraints)：jConstraints是一个用于建模表达式和与约束求解器交互的库，由NASA开源。
* [MiniCP](https://github.com/minicp/minicp)：MiniCP是一个用Java实现的轻量级CP求解器，由康涅狄格大学、鲁汶大学、佐治亚理工学院的三位教授共同开发。
* [EUROPA](https://github.com/nasa/europa)：EUROPA是一个用于建模和解决规划、调度和约束规划问题的框架，NASA艾姆斯研究中心开源。
* [Statix Solver](https://mvnrepository.com/artifact/org.metaborg/statix.solver)：由代尔夫特理工大学开源的约束求解器。

#### 异常检测

* [EGADS](https://github.com/yahoo/egads)：EGADS是一个开源Java包，用于自动检测大规模时序数据中的异常，由Yahoo开源。
* [ThirdEye](https://github.com/startreedata/thirdeye)：ThirdEye是一款用于实时监控时间序列和交互式根本原因分析的集成工具，最初由LinkedIn开源。
* [Sherlock](https://github.com/yahoo/sherlock)：Sherlock是一个构建在Druid之上的异常检测服务，由Yahoo开源。
* [Adaptive Alerting](https://github.com/ExpediaGroup/adaptive-alerting)：Adaptive Alerting通过自动模型选择和拟合进行流异常检测，由Expedia开源。
* [Random Cut Forest](https://github.com/aws/random-cut-forest-by-aws)：该仓库包含随机森林(RCF)概率数据结构的实现，由Amazon开发，用于流数据的非参数异常检测算法。
* [AnomalyDetection](https://github.com/JeemyJohn/AnomalyDetection)：Java实现的异常检测算法。
* [Isolation Forest](https://github.com/linkedin/isolation-forest)：这是孤立森林无监督异常值检测算法的分布式Scala/Spark实现，由LinkedIn开发。
* [Yurita](https://github.com/paypal/yurita)：Yurita是一个用于开发大规模异常检测模型的开源项目，由Paypal开发。

#### 逻辑编程

* [NeuraLogic](https://github.com/GustikS/NeuraLogic)：该框架的核心是一种自定义语言，你可以使用它来编写可微分程序来编码你的学习场景，类似于经典的深度学习框架。
* [Formulog](https://github.com/HarvardPL/formulog)：Formulog通过构建和推理SMT公式的机制以及一些一阶函数编程来扩展逻辑编程语言Datalog，由哈佛编程语言研究小组开源。
* [Alpha](https://github.com/alpha-asp/Alpha)：Alpha是一个答案集编程(ASP)系统：它读取逻辑程序(一组逻辑规则)并计算相应的答案集，由维也纳工业大学开源。
* [2P-Kt](https://github.com/tuProlog/2p-kt)：2P-Kt旨在为逻辑编程和人工智能提供一个通用、可扩展和可互操作的生态系统，由新墨西哥州立大学开源。
* [JIProlog](https://github.com/jiprolog/jiprolog)：JIProlog是一个Prolog解释器，100%纯Java，跨平台且开源。

#### 元启发式框架

* [Mork](https://github.com/mork-optimization/mork)：Mork是一个使用JVM开发NP-Hard问题方法的框架，由胡安卡洛斯国王大学开源。
* [jMetal](https://github.com/jMetal/jMetal)：jMetal是一个基于Java的框架，用于使用元启发式进行多目标优化，由马拉加大学开源。
* [SEAGE](https://github.com/seage/seage)：SEAGE是一个用于元启发式算法协作的超启发式框架，由捷克理工大学开源。
* [Isula](https://github.com/cptanalatriste/isula)：Isula是用于蚁群优化算法的Java框架。

#### 计算机视觉

* [OpenCV](https://github.com/opencv/opencv)：OpenCV是一个包含数百种计算机视觉算法的开源库，提供官方Java API，由Intel开发。
* [ImageJ](https://github.com/imagej/ImageJ)：ImageJ是用于处理和分析科学图像的公共领域软件，由美国国家卫生研究院开源。
* [OpenIMAJ](https://github.com/openimaj/openimaj)：OpenIMAJ是一个屡获殊荣的库和工具集合，用于多媒体(图像、文本、视频、音频等)内容分析和内容生成，由南安普顿大学开发。
* [OpenCV](https://github.com/openpnp/opencv)：OpenCV是一个跨平台的计算机视觉库，这是OpenCV的Java绑定。
* [JavaCV](https://github.com/bytedeco/javacv)：JavaCV包含OpenCV、FFmpeg等的Java接口。
* [BoofCV](https://github.com/lessthanoptimal/BoofCV)：BoofCV是一个开源实时计算机视觉库，功能包括低级图像处理、相机校准、特征检测/跟踪、运动结构、分类和识别。
* [Yolo ONNX Java](https://gitee.com/agricultureiot/yolo-onnx-java)：Java开发视觉智能识别项目，纯Java调用Yolo ONNX模型。
* [BGSLibrary](https://github.com/andrewssobral/bgslibrary)：BGSLibrary是一个全面的C++框架，专为计算机视觉应用中的背景减法而设计，尤其适用于检测视频流中的运动物体。
* [GRIP](https://github.com/WPIRoboticsProjects/GRIP)：GRIP是一款用于快速原型设计和部署计算机视觉算法的应用程序，主要用于机器人应用，由伍斯特理工学院开源。
* [Origami](https://github.com/hellonico/origami)：Origami是JVM上的图像处理、计算机视觉和神经网络库。
* [PaperVision](https://github.com/deltacv/PaperVision)：PaperVision旨在让计算机视觉更容易被使用。
* [OpenCV Processing](https://github.com/atduskgreg/opencv-processing)：OpenCV Processing基于OpenCV的官方Java绑定，为常见的OpenCV函数提供方便的包装器。
* [DataGym](https://github.com/datagym-ai/datagym-core)：DataGym是一个基于Web的现代工作台，用于标记图像和视频，它允许你管理项目和数据集、标记数据、控制质量并构建你自己的训练数据管道。
* [JavaVision](https://gitee.com/javpower/java-vision)：JavaVision是一个基于Java开发的全能视觉智能识别项目。
* [VisRec API](https://github.com/JavaVisRec/visrec-api)：Java视觉识别规范API。

#### OCR

* [Tess4j](https://github.com/nguyenq/tess4j)：Tesseract OCR API的Java JNA包装器。
* [C-OCR](https://github.com/ctripcorp/C-OCR)：C-OCR是携程自研的OCR项目，主要包括身份证、护照、火车票、签证等旅游相关证件、材料的识别。
* [Aspose.OCR](https://products.aspose.com/ocr/java/)：Aspose OCR是一种高效、用户友好且经济高效的OCR API。
* [Spire.OCR](https://www.e-iceblue.com/Introduce/ocr-for-java.html)：Spire.OCR是一个专业的OCR库，可从JPG、PNG、GIF、BMP和TIFF格式的图像中读取文本。
* [Image2LaTeX](https://github.com/blaisewang/img2latex-mathpix)：Image2LaTeX提供将图像转换为某些LaTeX方程格式和OCR的核心功能。
* [Tesseract4java](https://github.com/tesseract4java/tesseract4java)：Tesseract4java是用于Tesseract OCR的Java GUI和工具。
* [OCR4All](https://github.com/OCR4all/OCR4all)：OCR4All允许任何给定用户对各种历史印刷品独立执行OCR，并以合理的时间支出获得高质量的结果，由维尔茨堡大学开源。
* [EasyOCR](https://github.com/ushelp/EasyOCR)：EasyOCR是一个使用Java语言实现的OCR识别引擎，能自动完成图片清理、识别CAPTCHA验证码图片内容的一体化工作。
* [TreeHole OCR](https://github.com/AnyListen/tools-ocr)：TreeHole OCR是一款跨平台的OCR小工具，调用本地OCR进行识别，无需联网即可使用用到的技术和框架。
* [RapidOcr Java](https://github.com/MyMonsterCat/RapidOcr-Java)：Java代码实现调用RapidOCR。
* [Java OCR API](https://github.com/Asprise/java-ocr-api)：Java OCR允许你对图像(JPEG、PNG、TIFF、PDF等)执行OCR和条形码识别，并输出为纯文本、具有完整坐标的XML以及可搜索的PDF。
* [Ocular](https://github.com/tberg12/ocular)：Ocular是一款先进的历史OCR系统。
* [KanjiTomo OCR](https://github.com/sakarika/kanjitomo-ocr)：KanjiTomo OCR是一个用于从图像中识别日语字符的Java库。
* [MathOCR](https://github.com/chungkwong/MathOCR)：MathOCR是一个用Java语言编写的印刷体科技文档识别系统。
* [NewOCR](https://github.com/MSPaintIDE/NewOCR)：NewOCR是一款用Java制作的OCR，无需使用机器学习。

#### 人脸识别

* [CompreFace](https://github.com/exadel-inc/CompreFace)：Exadel CompreFace是一项免费的开源人脸识别服务，无需具备机器学习技能即可轻松集成到任何系统中。
* [ArcFace](https://github.com/itboyst/ArcSoftFaceDemo)：ArcFace 3.0免费离线人脸识别SDK。
* [Face Recognition](https://github.com/Qualeams/Android-Face-Recognition-with-Deep-Learning-Library)：Face Recognition是用于Android和Java的人脸识别库，由苏黎世应用科学大学开源。
* [FaceRecognition](https://github.com/wihoho/FaceRecognition)：FaceRecognition是使用PCA、LDA和LPP实现的人脸识别项目。
* [SeetafaceJNI](https://gitee.com/cnsugar/seetafaceJNI)：SeetafaceJNI是基于中科院Seetaface 2进行封装的Java人脸识别库。
* [FaceSearch](https://gitee.com/open-visual/face-search)：FaceSearch是阿里云视觉智能开放平台的人脸搜索M:N的开源替代。
* [FaceRecognition LivenessDetection Android](https://github.com/Faceplugin-ltd/FaceRecognition-LivenessDetection-Android)：适用于Android的本地人脸识别人脸活体检测SDK，由FacePlugIn开源。
* [Red5](https://gitee.com/endlesshh/red5-rtmp-push)：Java版天网人脸识别系统，可以获取视频流进行人脸识别后推送到流媒体服务器实时展示。
* [Qiansou Face SDK](https://gitee.com/qiansou/face-v4-java-sdk)：千搜科技第五代人脸识别引擎Java接口。

#### 语音识别

* [Vosk](https://github.com/alphacep/vosk-api)：Vosk是一款离线开源语音识别工具包。
* [Live Transcribe](https://github.com/google/live-transcribe-speech-engine)：Live Transcribe是一款Android应用，可为失聪或听力障碍人士提供实时字幕，包含与Google Cloud Speech API进行通信的客户端库，由Google开源。
* [Sphinx-4](https://github.com/cmusphinx/sphinx4)：Sphinx-4是一款先进、独立于说话人的连续语音识别系统，由CMU开发。
* [JARVIS Speech API](https://github.com/lkuza2/java-speech-api)：JARVIS Speech API的设计简洁高效，使用Google开发的语音引擎来提供部分API功能。
* [Alexa Skills Kit Java SDK](https://github.com/alexa/alexa-skills-kit-sdk-for-java)：Alexa是Amazon基于云的语音服务，可在亚马逊和第三方设备制造商的数亿台设备上使用。
* [OpenDial](https://github.com/plison/opendial)：OpenDial是一个基于Java、领域无关的工具包，用于开发语音对话系统，由奥斯陆大学开源。
* [Recognito](https://github.com/amaurycrickx/recognito)：Java中的文本独立说话人识别。
* [ElevateAI Java SDK](https://github.com/NICEElevateAI/ElevateAIJavaSDK)：ElevateAI提供了用于语音转文本、语音交互的行为分析和情感分析的API。
* [WhisperJNI](https://github.com/GiviMAD/whisper-jni)：whisper.cpp的JNI包装器，允许将语音转录为Java中的文本。

#### 语音合成

* [MaryTTS](https://github.com/marytts/marytts)：MaryTTS是一个用纯Java编写的开源、多语言文本到语音合成系统。
* [FreeTTS](https://freetts.sourceforge.io/)：FreeTTS是一个完全用Java编程语言编写的语音合成系统。
* [VeloVoice](https://github.com/Mai-Onsyn/VeloVoice)：一个用于解析中文小说并通过TTS转换为语音的JavaFX软件。
* [Java TTS](https://github.com/ikfly/java-tts)：参考其他语言版本写的Java版文字转语音，使用 Edge API。
* [Android Speech](https://github.com/gotev/android-speech)：轻松实现Android语音识别和文本转语音。
* [Java Google Speech API](https://github.com/goxr3plus/java-google-speech-api)：这是一个用Java编写的API，包含识别器、合成器和麦克风采集工具。
* [Voices](https://github.com/hcoles/voices)：适用于Java 17及更高版本的快速进程内文本转语音。

## 数据科学

* [Tablesaw](https://github.com/jtablesaw/tablesaw)：Tablesaw是一个DataFrame和可视化库，支持加载、清理、转换、过滤和汇总数据。
* [Luckysheet](https://github.com/dream-num/Luckysheet)：Luckysheet是一款类似Excel的在线电子表格，功能强大、配置简单。
* [OpenRefine](https://github.com/OpenRefine/OpenRefine)：OpenRefine是一个基于Java的强大工具，可让你加载数据、理解数据、清理数据、协调数据，并使用来自Web的数据对其进行扩充，由Google开源。
* [Apache SystemDS](https://github.com/apache/systemds)：SystemDS是一个开源ML系统，适用于端到端数据科学生命周期。
* [Incanter](https://github.com/incanter/incanter)：Incanter是一个基于Clojure、类似R的JVM统计计算和图形环境。
* [Hopsworks](https://github.com/logicalclocks/hopsworks)：Hopsworks是一个ML数据平台，具有以Python为中心的特征存储和MLOps功能，由Hopsworks开源。
* [ShinyProxy](https://github.com/openanalytics/shinyproxy)：ShinyProxy是用于Shiny和数据科学应用程序的开源企业部署软件。
* [Eclipse ICE](https://github.com/eclipse/ice)：ICE是一个科学工作台和工作流程环境，旨在改善计算科学家的用户体验。
* [RapidMiner](https://github.com/rapidminer/rapidminer-studio)：RapidMiner是一个数据科学平台，通过GUI和Java API提供各种机器学习算法。
* [Apache Commons Statistics](https://github.com/apache/commons-statistics)：Commons Statistics提供用于统计应用程序的工具，为常用的连续和离散分布提供支持。
* [JScience](https://github.com/javolution/jscience)：提供一组用于处理科学测量和单位的类。
* [DataMelt](https://datamelt.org/)：DataMelt是一款用于数值计算、统计、符号计算、数据分析和数据可视化的软件。
* [DataCleaner](https://github.com/datacleaner/DataCleaner)：DataCleaner是一个数据质量工具包，可让你分析、更正和丰富你的数据。
* [Featran](https://github.com/spotify/featran)：Featran是用于数据科学和机器学习的Scala特征转换库，由Spotify开源。
* [Datavines](https://github.com/datavane/datavines)：DataVines是一个易于使用的数据质量服务平台，支持多种指标，由Datavane大数据组织开源。
* [Koma](https://github.com/kyonifer/koma)：Koma是Kotlin的科学计算环境。
* [Classifai](https://github.com/CertifaiAI/classifai)：Classifai是最全面的开源数据标注平台之一。
* [DataSpread](https://github.com/dataspread/dataspread-web)：DataSpread是一个电子表格-数据库混合系统，包含电子表格前端和数据库后端，由伊利诺伊大学和加州大学伯克利分校开源。
* [Kandy](https://github.com/Kotlin/kandy)：Kandy是Kotlin的一个开源绘图库，它提供了用于创建图形的强大而灵活的DSL，并利用了各种流行的引擎，由JetBrains开源。
* [Kravis](https://github.com/holgerbrandl/kravis)：Kravis实现一种语法，使用一组标准化的动词来创建各种各样的图表。
* [ERDDAP](https://github.com/ERDDAP/erddap)：ERDDAP是一款科学数据服务器，它为用户提供了一种简单、一致的方式，可以下载常见文件格式的网格化和表格化科学数据集子集，并制作图表和地图，由美国国家海洋和大气管理局开源。
* [Javelit](https://github.com/javelit/javelit)：Javelit是一个Java闪电般快速的数据应用程序开发框架，深受Streamlit的启发。

#### 数据可视化

* [KNIME](https://github.com/knime/knime-core)：KNIME是由德国的康斯坦茨大学，一组研究制药应用的开发团队在2006年7月推出的一款针对大数据的软件。
* [Davinci](https://github.com/edp963/davinci)：Davinci是一个DVaaS平台解决方案，面向业务人员/数据工程师/数据分析师/数据科学家，致力于提供一站式数据可视化解决方案，由宜信开源。
* [DataCap](https://github.com/devlive-community/datacap)：DataCap是用于数据转换、集成和可视化的集成软件，由Devlive社区开源。
* [ECharts](https://gitee.com/free/ECharts)：ECharts是针对ECharts 2.X版本的Java类库，实现了所有ECharts中的JSON结构对应的Java对象，并且可以很方便的创建Option、Series等。
* [ECharts Java](https://github.com/ECharts-Java/ECharts-Java)：ECharts Java是一个轻量级但全面的库，供Java开发人员轻松使用JavaScript可视化库ECharts。
* [Mirador](https://github.com/mirador/mirador)：Mirador是一种通过视觉探索在复杂数据集中识别新假设的工具，由斯坦福联合哈佛大学、美国国家美术馆和其他几家世界各地的机构共同进行扩展开发。
* [Ananas](https://github.com/ananas-analytics/ananas-desktop)：Ananas是一款可破解的数据集成/分析工具，使非技术用户能够编辑数据处理作业并按需可视化数据。
* [Datart](https://github.com/running-elephant/datart)：Datart是新一代数据可视化开放平台，支持各类企业数据可视化场景需求，如创建和使用报表、仪表板和大屏，进行可视化数据分析，构建可视化数据应用等，由宜信开源。
* [Stroom](https://github.com/gchq/stroom)：Stroom是一个数据处理、存储和分析平台，由英国政府通讯总部开源。
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
* [Constellation](https://github.com/constellation-app/constellation)：Constellation是一款以图形为中心的数据可视化和交互式分析应用程序，支持跨大型复杂数据集的数据访问、联合和操作功能。

#### 数据挖掘

* [Weka](https://www.cs.waikato.ac.nz/ml/weka/)：Weka是用于数据挖掘任务的机器学习算法的集合，它包含用于数据准备、分类、回归、聚类、关联规则挖掘和可视化的工具，由新西兰怀卡托大学开发。
* [ELKI](https://github.com/elki-project/elki)：ELKI是一款用Java编写的开源数据挖掘软件，由德国多特蒙德大学开发。
* [StreamDM](https://github.com/huawei-noah/streamDM)：StreamDM是一款新的开源软件，用于使用Spark Streaming挖掘大数据流，由华为诺亚方舟实验室开源。
* [Apache Samoa](https://github.com/apache/incubator-samoa)：SAMOA是一个用于挖掘大数据流的平台，它是一个分布式流式机器学习框架，包含分布式流式机器学习算法的编程抽象，由Yahoo开源。
* [Shifu](https://github.com/ShifuML/shifu)：Shifu是一个构建在Hadoop之上的开源端到端机器学习和数据挖掘框架，由Paypal开发。
* [SessionAnalytics](https://github.com/Tencent/SessionAnalytics)：SessionAnalytics是一个基于互联网用户Session会话的用户路径分析和挖掘框架，由腾讯开源。

#### 数据分析

* [Enso](https://github.com/enso-org/enso)：Enso Analytics是一个专为数据团队设计的自助式数据准备和分析平台。
* [DataBand](https://gitee.com/475660/databand)：DataBand是一个轻量级一站式大数据分析平台。
* [Precog](https://github.com/precog/platform)：Precog是一款针对NoSQL数据的高级分析引擎，由SlamData开发。
* [MacroBase](https://github.com/stanford-futuredata/macrobase)：MacroBase是一种数据分析工具，它使用机器学习优先考虑大型数据集中的注意力，由斯坦福开源。
* [Apache Hama](http://hama.apache.org/)：Hama是一个基于批量同步并行(BSP)计算模型的大数据分析框架，由韩国首尔国立大学开发。
* [DnA](https://github.com/mercedes-benz/DnA)：DnA为分析领域的企业提供A-Z解决方案，从计划和正在进行的活动的透明度到提供实现这些活动的开源组件，由奔驰开源。
* [Fili](https://github.com/yahoo/fili)：Fili是一个基于Java的框架，可以轻松构建和维护用于时间序列报告和分析的RESTful Web服务，由Yahoo开源。
* [Texera](https://github.com/Texera/texera)：Texera是一个开源系统，它使用基于Web的工作流支持大规模协作数据科学，由美国加州大学尔湾分校开源。
* [Opaque](https://github.com/mc2-project/opaque-sql)：Opaque SQL是Apache Spark SQL的一个包，它支持使用OpenEnclave框架处理加密的DataFrame，由加州大学伯克利分校RISE实验室开发。
* [CIA](https://github.com/Hack23/cia)：CIA是一个由志愿者推动的开源情报(OSINT)项目，旨在对瑞典的政治活动进行全面分析。
* [Coral](https://github.com/coral-streaming/coral)：Coral是一个实时分析和数据科学平台，它通过RESTful API转换流事件并从数据中提取模式。
* [SANSA Stack](https://github.com/SANSA-Stack/SANSA-Stack)：SANSA是一个用于可扩展处理大规模RDF数据的大数据引擎，由德累斯顿工业大学开发。
* [SparkCube](https://github.com/alibaba/SparkCube)：SparkCube是一个用于极快OLAP数据分析的项目，由阿里开发。
* [Metanome](https://github.com/HPI-Information-Systems/Metanome)：Metanome是HPI和卡塔尔计算研究所之间的联合项目，通过开发高效算法并将其集成到通用工具中、扩展数据分析的功能以及解决大数据的性能和可扩展性问题，为数据分析提供了全新的视角。
* [Spatial Framework Hadoop](https://github.com/Esri/spatial-framework-for-hadoop)：Hadoop空间框架允许开发人员和数据科学家使用Hadoop数据处理系统进行空间数据分析。
* [ALITA](https://github.com/didi/ALITA)：ALITA是一个基于层的数据分析工具，由滴滴开源。

#### 实体解析

* [Zingg](https://github.com/zinggAI/zingg)：Zingg是一种基于ML的实体解析工具。
* [JedAI](https://github.com/scify/JedAIToolkit)：JedAI是一个开源、高可扩展性的Java实体解析工具包，由鲁汶大学、巴黎西岱大学、摩德纳雷焦艾米利亚大学开源。
* [Duke](https://github.com/larsga/Duke)：Duke是一款快速灵活的重复数据删除引擎。
* [Zentity](https://github.com/zentity-io/zentity)：Zentity是一个用于实时实体解析的Elasticsearch插件。
* [ReCiter](https://github.com/wcmc-its/ReCiter)：ReCiter是一个高度准确的系统，用于猜测某个人在PubMed上发表了哪些出版物，由康奈尔大学开源。

#### Dataframe

* [CUDF](https://github.com/rapidsai/cudf/tree/branch-24.08/java)：CUDF是一个GPU DataFrame库，用于加载、连接、聚合、过滤和以其他方式处理数据，由NVIDIA提供。
* [Dataframe](https://github.com/Kotlin/dataframe)：Dataframe旨在利用Kotlin语言的全部功能以及Jupyter Notebook和REPL中间歇性代码执行提供的机会，协调Kotlin的静态类型与数据的动态特性，JetBrains开源。
* [Morpheus](https://github.com/zavtech/morpheus-core)：Morpheus库旨在促进涉及大型数据集的高性能分析软件的开发，以便在JVM上进行离线和实时分析。
* [Krangl](https://github.com/holgerbrandl/krangl)：Krangl是一个用于数据处理的Kotlin库，通过使用现代函数式API实现数据操作语法，它允许过滤、转换、聚合和重塑表格数据。
* [TMD](https://github.com/techascent/tech.ml.dataset)：TMD是一个用于表格数据处理的Clojure库，类似于Python的Pandas或R的data.table。
* [DDF](https://github.com/ddf-project/DDF)：DDF旨在通过汇集R数据科学、RDBMS/SQL和大数据分布式处理的最佳思想，使大数据变得简单而强大。
* [JDFrame](https://github.com/burukeYou/JDFrame)：JDFrame是一个Java DataFrame的实现。
* [Joinery](https://github.com/cardillo/joinery)：Java的DataFrame。
* [DFLib](https://github.com/dflib/dflib)：DFLib是通用DataFrame数据结构的轻量级纯Java实现，由ObjectStyle开源。
* [Scala Polars](https://github.com/chitralverma/scala-polars)：Scala Polars将极其高速的Polars DataFrame库带入Scala和Java项目。
* [DataFrame EC](https://github.com/vmzakharov/dataframe-ec)：基于Eclipse Collections框架的表格数据结构。
* [Poppy](https://github.com/tenmax/poppy)：Poppy是Java的Dataframe库，它提供常见的SQL操作来在Java中处理数据，由TenMax开源。
* [Geni](https://github.com/zero-one-group/geni)：Geni是一个在Apache Spark上运行的Clojure Dataframe库。
* [Saddle](https://github.com/saddle/saddle)：Saddle是Scala的一个数据操作库，它提供基于数组、索引、一维和二维的数据结构，这些数据结构在JVM原始类型上经过精心设计，以避免装箱和拆箱的开销。

## [测试-面试宝典](docs/doc2.md)