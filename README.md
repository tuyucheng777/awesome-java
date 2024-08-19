# Java生态资源大全

这里汇总了Java生态圈中的各种框架、库、中间件，包括Web开发、大数据、桌面开发、机器学习、软件测试、物联网、Android等领域。

所有框架和库都是基于Java语言实现的，只有极少数是由Kotlin、Scala、Groovy等JVM系语言混合开发，并且也可以在Java中兼容使用。

## 目录

- [Web框架](#Web框架)
- [JSF框架](#JSF框架)
- [REST框架](#REST框架)
- [ORM框架](#ORM框架)
- [持久层库](#持久层库)
- [Mybatis生态](#Mybatis生态)
- [应用框架](#应用框架)
- [微服务框架](#微服务框架)
- [Spring Cloud生态](#SpringCloud生态)
- [微服务工具](#微服务工具)
- [单元测试](#单元测试)
- [集成测试](#集成测试)
- [接口测试](#接口测试)
- [功能测试](#功能测试)
- [突变测试](#突变测试)
- [模糊测试](#模糊测试)
- [性能测试](#性能测试)
- [属性测试](#属性测试)
- [A/B测试](#AB测试)
- [验收测试](#验收测试)
- [回归测试](#回归测试)
- [契约测试](#契约测试)
- [渗透测试](#渗透测试)
- [快照测试](#快照测试)
- [黑盒&白盒测试](#黑盒白盒测试)
- [断言库](#断言库)
- [Mock框架](#Mock框架)
- [Mock工具](#Mock工具)
- [测试数据生成器](#测试数据生成器)
- [BDD框架](#BDD框架)
- [测试生成器](#测试生成器)
- [Selenium生态](#Selenium生态)
- [自动化框架](#自动化框架)
- [测试报告](#测试报告)
- [QA自动化](#QA自动化)
- [自动化工具](#自动化工具)
- [多线程测试](#多线程测试)
- [JUnit扩展](#JUnit扩展)
- [其他测试库](#其他测试库)
- [代码覆盖率](#代码覆盖率)
- [构建工具](#构建工具)
- [包管理器](#包管理器)
- [CI/CD](#CICD)
- [发布工具](#发布工具)
- [Java环境管理](#Java环境管理)
- [JDK](#JDK)
- [JVM语言](#JVM语言)
- [JVM实现](#JVM实现)
- [IDE](#IDE)
- [项目管理](#项目管理)
- [原型工具](#原型工具)
- [云原生](#云原生)
- [云计算](#云计算)
- [Serverless](#Serverless)
- [容器化工具](#容器化工具)
- [Docker客户端](#Docker客户端)
- [DevOps](#DevOps)
- [云服务](#云服务)
- [APM](#APM)
- [分布式追踪](#分布式追踪)
- [指标报告](#指标报告)
- [注册中心](#注册中心)
- [容错组件](#容错组件)
- [混沌工程](#混沌工程)
- [流量回放](#流量回放)
- [API网关](#API网关)
- [大数据框架](#大数据框架)
- [大数据工具](#大数据工具)
- [大数据组件](#大数据组件)
- [数据可视化](#数据可视化)
- [数据目录](#数据目录)
- [流处理平台](#流处理平台)
- [图处理](#图处理)
- [ETL工具](#ETL工具)
- [CDC组件](#CDC组件)
- [数据库中间件](#数据库中间件)
- [数据湖框架](#数据湖框架)
- [消息中间件](#消息中间件)
- [Kafka生态](#Kafka生态)
- [分布式组件](#分布式组件)
- [分布式锁](#分布式锁)
- [分布式事务](#分布式事务)
- [ID生成器](#ID生成器)
- [搜索引擎](#搜索引擎)
- [图数据库](#图数据库)
- [键值存储](#键值存储)
- [时序数据库](#时序数据库)
- [嵌入式数据库](#嵌入式数据库)
- [关系型数据库](#关系型数据库)
- [NoSQL数据库](#NoSQL数据库)
- [OLAP数据库](#OLAP数据库)
- [对象数据库](#对象数据库)
- [Datalog数据库](#Datalog数据库)
- [其他数据库](#其他数据库)
- [存储引擎](#存储引擎)
- [数据库连接池](#数据库连接池)
- [HTTP客户端](#HTTP客户端)
- [RPC框架](#RPC框架)
- [响应式](#响应式)
- [WebServer](#WebServer)
- [WebSocket](#WebSocket)
- [Jakarta EE产品](#JakartaEE产品)
- [工具库](#工具库)
- [Bean映射&复制](#Bean映射复制)
- [IoC](#IoC)
- [AOP](#AOP)
- [日志库](#日志库)
- [JSON库](#JSON库)
- [JsonPath](#JsonPath)
- [缓存库](#缓存库)
- [集合库](#集合库)
- [协程库](#协程库)
- [并发编程](#并发编程)
- [Actor模型](#Actor模型)
- [GraphQL](#GraphQL)
- [任务调度](#任务调度)
- [配置管理](#配置管理)
- [业务流](#业务流)
- [规则引擎](#规则引擎)
- [API管理](#API管理)
- [反射库](#反射库)
- [日期时间](#日期时间)
- [人工智能](#人工智能)
- [LLM](#LLM)
- [ChatGPT客户端](#ChatGPT客户端)
- [机器学习](#机器学习)
- [自然语言处理](#自然语言处理)
- [深度学习](#深度学习)
- [遗传算法](#遗传算法)
- [专家系统](#专家系统)
- [约束求解](#约束求解)
- [实体解析](#实体解析)
- [数据科学](#数据科学)
- [异常检测](#异常检测)
- [商业智能](#商业智能)
- [指纹识别](#指纹识别)
- [推荐系统](#推荐系统)
- [逻辑编程](#逻辑编程)
- [多智能体](#多智能体)
- [MATLAB](#MATLAB)
- [Jupyter](#Jupyter)
- [元启发式框架](#元启发式框架)
- [机器人开发](#机器人开发)
- [数学库](#数学库)
- [本体库](#本体库)
- [语义Web](#语义Web)
- [知识图谱](#知识图谱)
- [生物信息学](#生物信息学)
- [基因组学](#基因组学)
- [医疗平台](#医疗平台)
- [化学领域](#化学领域)
- [安全库](#安全库)
- [安全工具](#安全工具)
- [自保护](#自保护)
- [身份认证和授权](#身份认证和授权)
- [JWT库](#JWT库)
- [OAuth库](#OAuth库)
- [跨域身份管理](#跨域身份管理)
- [加密库](#加密库)
- [密码库](#密码库)
- [加密算法](#加密算法)
- [模板引擎](#模板引擎)
- [诊断工具](#诊断工具)
- [性能分析](#性能分析)
- [GC日志分析](#GC日志分析)
- [堆转储](#堆转储)
- [线程转储](#线程转储)
- [对象测量](#对象测量)
- [火焰图](#火焰图)
- [脚本](#脚本)
- [CLI工具](#CLI工具)
- [命令行参数解析](#命令行参数解析)
- [SSH工具](#SSH工具)
- [DNS、内网穿透和代理](#DNS内网穿透和代理)
- [Git工具](#Git工具)
- [函数式编程](#函数式编程)
- [Stream工具库](#Stream工具库)
- [字节码操作](#字节码操作)
- [图像处理](#图像处理)
- [计算机视觉](#计算机视觉)
- [光学字符识别](#光学字符识别)
- [SVG库](#SVG库)
- [验证码](#验证码)
- [压缩库](#压缩库)
- [爬虫框架](#爬虫框架)
- [批处理框架](#批处理框架)
- [注解处理器](#注解处理器)
- [字符串工具库](#字符串工具库)
- [Java 9-22](#9-22特性)
- [消息/事件总线](#消息事件总线)
- [接口文档](#接口文档)
- [技术文档](#技术文档)
- [Javadoc](#Javadoc)
- [PDF库](#PDF库)
- [Excel库](#Excel库)
- [CSV库](#CSV库)
- [Word库](#Word库)
- [Toml库](#Toml库)
- [HTML库](#HTML库)
- [XML库](#XML库)
- [YML库](#YML库)
- [文件库](#文件库)
- [License库](#License库)
- [Markdown库](#Markdown库)
- [集群管理](#集群管理)
- [静态分析](#静态分析)
- [软件质量](#软件质量)
- [编码规范](#编码规范)
- [依赖分析](#依赖分析)
- [污点分析](#污点分析)
- [审计框架](#审计框架)
- [代码属性图](#代码属性图)
- [API变更管理](#API变更管理)
- [源代码浏览器](#源代码浏览器)
- [脚手架](#脚手架)
- [低代码](#低代码)
- [Data API](#DataAPI)
- [POS](#POS)
- [业务](#业务)
- [电商](#电商)
- [支付](#支付)
- [SDK](#SDK)
- [微信开发](#微信开发)
- [推送SDK](#推送SDK)
- [API&客户端](#API客户端)
- [中间件客户端](#中间件客户端)
- [游戏服务器](#游戏服务器)
- [即时通讯](#即时通讯)
- [视频会议](#视频会议)
- [FTP服务器](#FTP服务器)
- [区块链](#区块链)
- [以太坊](#以太坊)
- [比特币](#比特币)
- [物联网](#物联网)
- [车联网](#车联网)
- [嵌入式](#嵌入式)
- [MQTT](#MQTT)
- [金融](#金融)
- [短信](#短信)
- [DSL](#DSL)
- [JMX](#JMX)
- [RMI](#RMI)
- [gRPC](#gRPC)
- [Raft算法](#Raft算法)
- [Paxos算法](#Paxos算法)
- [对象池](#对象池)
- [CQRS框架](#CQRS框架)
- [DDD框架](#DDD框架)
- [软件工程](#软件工程)
- [设计模式](#设计模式)
- [幂等处理](#幂等处理)
- [数据字典](#数据字典)
- [迁移&重构](#迁移重构)
- [Bot](#Bot)
- [安卓库](#安卓库)
- [GUI框架](#GUI框架)
- [Swing](#Swing)
- [Swing主题库](#Swing主题库)
- [Swing UI库](#SwingUI库)
- [Swing组件库](#Swing组件库)
- [Swing布局库](#Swing布局库)
- [Swing选择器](#Swing选择器)
- [Swing图表库](#Swing图表库)
- [Swing测试库](#Swing测试库)
- [JavaFX](#JavaFX)
- [JavaFX主题库](#JavaFX主题库)
- [JavaFX样式库](#JavaFX样式库)
- [JavaFX组件库](#JavaFX组件库)
- [JavaFX图表库](#JavaFX图表库)
- [JavaFX图标库](#JavaFX图标库)
- [JavaFX布局库](#JavaFX布局库)
- [JavaFX渲染库](#JavaFX渲染库)
- [浏览器](#浏览器)
- [JavaFX小工具](#JavaFX小工具)
- [GUI程序](#GUI程序)
- [数学软件](#数学软件)
- [UML工具](#UML工具)
- [办公软件](#办公软件)
- [数据库工具](#数据库工具)
- [数据库建模](#数据库建模)
- [字节码工具](#字节码工具)
- [字节码混淆工具](#字节码混淆工具)
- [游戏开发](#游戏开发)
- [2D/3D渲染](#2D3D渲染)
- [移动开发框架](#移动开发框架)
- [JVM代理](#JVM代理)
- [类加载](#类加载)
- [RISC-V](#RISC-V)
- [汇编](#汇编)
- [LLVM](#LLVM)
- [WebAssembly](#WebAssembly)
- [JavaScript](#JavaScript)
- [编译器&插件](#编译器插件)
- [语言服务器](#语言服务器)
- [数据库驱动](#数据库驱动)
- [数据库迁移](#数据库迁移)
- [数据源增强](#数据源增强)
- [对象存储](#对象存储)
- [音视频处理](#音视频处理)
- [数据结构](#数据结构)
- [基本类型](#基本类型)
- [堆外内存管理](#堆外内存管理)
- [布隆过滤器](#布隆过滤器)
- [算法库](#算法库)
- [噪声库](#噪声库)
- [原生开发](#原生开发)
- [COM桥](#COM桥)
- [GPU编程](#GPU编程)
- [硬件操作](#硬件操作)
- [运动规划](#运动规划)
- [自动规划](#自动规划)
- [操作系统](#操作系统)
- [逆向工程](#逆向工程)
- [电力系统](#电力系统)
- [量子计算](#量子计算)
- [QA系统](#QA系统)
- [CMS系统](#CMS系统)
- [ERP系统](#ERP系统)
- [DMS系统](#DMS系统)
- [SCRM系统](#SCRM系统)
- [门户框架](#门户框架)
- [教育软件](#教育软件)
- [网络库](#网络库)
- [状态机](#状态机)
- [二维码生成器](#二维码生成器)
- [文件系统](#文件系统)
- [报表引擎](#报表引擎)
- [物流系统](#物流系统)
- [打包部署运行](#打包部署运行)
- [地理空间](#地理空间)
- [路由引擎](#路由引擎)
- [几何学](#几何学)
- [航空](#航空)
- [水文学](#水文学)
- [物理库](#物理库)
- [无人机](#无人机)
- [AIS库](#AIS库)
- [跨语言](#跨语言)
- [序列化](#序列化)
- [IO操作](#IO操作)
- [文件操作](#文件操作)
- [文件上传](#文件上传)
- [文件比较](#文件比较)
- [邮件操作](#邮件操作)
- [电子签名](#电子签名)
- [安全培训](#安全培训)
- [RSS](#RSS)
- [SSE](#SSE)
- [RPM](#RPM)
- [EMF](#EMF)
- [EPC](#EPC)
- [FMI](#FMI)
- [OSGI](#OSGI)
- [数控](#数控)
- [数电](#数电)
- [工业](#工业)
- [海关](#海关)
- [蓝牙](#蓝牙)
- [校验](#校验)
- [元编程](#元编程)
- [分词器](#分词器)
- [文本表](#文本表)
- [语言库](#语言库)
- [泛型库](#泛型库)
- [国际化](#国际化)
- [翻译库](#翻译库)
- [字典库](#字典库)
- [短链接](#短链接)
- [单位库](#单位库)
- [词法解析](#词法解析)
- [形式验证](#形式验证)
- [项目模板](#项目模板)
- [印章生成](#印章生成)
- [N+1问题](#N1问题)
- [敏感词过滤](#敏感词过滤)
- [正则表达式](#正则表达式)
- [代码生成器](#代码生成器)
- [目录服务](#目录服务)
- [错误处理](#错误处理)
- [功能切换](#功能切换)
- [表情处理](#表情处理)
- [行为分析](#行为分析)
- [ASCII艺术](#ASCII艺术)
- [URL操作](#URL操作)
- [WebRTC](#WebRTC)
- [Expect库](#Expect库)
- [JavaME](#JavaME)
- [JavaCard](#JavaCard)
- [WebService](#WebService)
- [银行账号操作](#银行账号操作)
- [用户代理解析](#用户代理解析)
- [语义发布工具](#语义发布工具)
- [数字信号处理](#数字信号处理)
- [企业集成模式](#企业集成模式)
- [数字资产管理](#数字资产管理)
- [文档管理系统](#文档管理系统)
- [数据匿名工具](#数据匿名工具)
- [外部进程执行](#外部进程执行)
- [苹果推送通知](#苹果推送通知)
- [Java服务包装器](#Java服务包装器)
- [守护进程](#守护进程)
- [协议实现](#协议实现)
- [BitTorrent](#BitTorrent)
- [编解码](#编解码)
- [Web资源](#Web资源)
- [Web开发库](#Web开发库)
- [手机号解析](#手机号解析)
- [表达式引擎](#表达式引擎)
- [数学表达式](#数学表达式)
- [SQL解析器](#SQL解析器)
- [对象图导航](#对象图导航)
- [超媒体类型](#超媒体类型)
- [术语服务器](#术语服务器)
- [解析&转换](#解析转换)
- [Minecraft](#Minecraft)
- [Maven插件](#Maven插件)
- [Gradle插件](#Gradle插件)
- [Intellij插件](#Intellij插件)
- [Spring生态](#Spring生态)
- [其他](#其他)
- [教程系列](#教程系列)
- [Java教程](#Java教程)
- [大数据教程](#大数据教程)
- [Spring Boot教程](#Spring生态教程)
- [算法和数据结构教程](#算法和数据结构教程)
- [软件工程教程](#软件工程教程)
- [其他技术教程](#其他技术教程)
- [秒杀系统](#秒杀系统)
- [源码分析](#源码分析)
- [面试宝典](#面试宝典)

## Web框架

* [Spring Boot](https://github.com/spring-projects/spring-boot)：Spring Boot可帮助轻松创建由Spring驱动的生产级应用程序和服务，由Pivotal开源。
* [Apache Struts](https://github.com/apache/struts)：Apache Struts是一个用于创建Java Web应用程序的免费开源解决方案。
* [GWT](https://github.com/gwtproject/gwt)：GWT是一个开发工具包，用于构建和优化复杂的基于浏览器的应用程序，由Google开源。
* [Solon](https://gitee.com/noear/solon)：Java新的应用开发框架，更小、更快、更简单。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [Blade](https://github.com/lets-blade/blade)：Blade是一个追求简单、高效的Web框架。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web + ORM框架，其核心设计目标是开发迅速、代码量少、学习简单、功能强大、轻量级、易扩展、RESTful。
* [Javalin](https://github.com/javalin/javalin)：Javalin是一个非常轻量级的Kotlin和Java Web框架，支持WebSockets、HTTP2和异步请求。
* [Ninja](https://github.com/ninjaframework/ninja)：Ninja是Java的全栈Web框架，坚如磐石、快速且高效。
* [SOFABoot](https://github.com/sofastack/sofa-boot)：SOFABoot是一个基于Spring Boot的Java开发框架，由蚂蚁开源。
* [Grails](https://github.com/grails/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin允许你使用纯Java高效构建现代Web应用程序，而无需接触低级Web技术。
* [Jooby](https://github.com/jooby-project/jooby)：Jooby是一个现代、高性能且易于使用的Java和Kotlin Web框架上。
* [Pippo](https://github.com/pippo-java/pippo)：Pippo是一个Java开源微型Web框架，具有最小的依赖性和快速的学习曲线。
* [Spark](https://github.com/perwendel/spark)：Spark是一个Java 8的小型Web框架。
* [Citrus](https://github.com/webx/citrus)：Citrus是阿里开源的基于Java的Web框架。
* [Apache Wicket](https://github.com/apache/wicket)：Apache Wicket是一个开源、基于组件的Java Web应用程序框架。
* [RIFE2](https://github.com/rife2/rife2)：RIFE2是一个全栈、无声明的框架，可以使用现代Java快速、轻松地创建Web应用程序。
* [Apache Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架，专注于性能和开发人员生产力。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [ZK](https://github.com/zkoss/zk)：ZK是一个高效的Java框架，用于构建企业Web和移动应用程序。
* [Rose](https://github.com/XiaoMi/rose)：Rose是由人人网、糯米网、小米提供的，基于Servlet规范的Web框架。
* [JavaLite](https://github.com/javalite/javalite)：JavaLite是一个功能丰富的开发框架，包含Web、JDBC、Config等模块。
* [Vraptor4](https://github.com/caelum/vraptor4)：VRaptor是一个开源MVC框架，构建于CDI之上。
* [Apache Cocoon](https://github.com/apache/cocoon)：Apache Cocoon是围绕Pipeline，关注点分离和基于组件的Web开发的概念构建的Web应用程序框架。
* [Apache Turbine](https://github.com/apache/turbine-core)：Apache Turbine是一个基于Servlet的框架，允许Java开发人员快速构建Web应用程序。
* [Takes](https://github.com/yegor256/takes)：Takes是一个真正的面向对象且不可变的Java Web开发框架。
* [Argo](https://github.com/58code/Argo)：Argo是起源于58同城的内部Web框架。
* [Kora](https://github.com/Tinkoff/kora)：Kora是一个基于JVM的框架，用于构建后端应用程序。
* [IGRP](https://github.com/NOSiCode-CV/IGRP-Framework)：IGRP是由美国NOSi开发的平台，用于创建Web应用程序，基于业务步骤、流程、自动代码生成和一次性原则的合并。
* [Cicada](https://github.com/TogetherOS/cicada)：基于Netty的快速、轻量级Web框架。
* [CUBA Platform](https://github.com/cuba-platform/cuba)：CUBA Platform是一个高级框架，用于快速开发具有丰富Web界面的企业应用程序。
* [Tiny Framework](https://gitee.com/tinyframework/tiny)：企业级Java EE应用开发框架套件。
* [Minum](https://github.com/byronka/minum)：一个从头开始构建的最小Java Web框架，零依赖，使用虚拟线程。
* [ACT Framework](https://gitee.com/actframework/actframework)：ACT Framework是一个简洁易用，具有强大表达力的Java MVC全栈框架。
* [Hasor](https://github.com/ClouGence/hasor)：Hasor是一套基于Java语言的开发框架，可以和现有技术体系做到完美融合，由开云集致开源。
* [Eclipse Scout](https://github.com/eclipse-scout/scout.rt)：Eclipse Scout是一个成熟且开源的框架，适用于Web上的现代业务应用程序。
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next)：Cloudopt Next是一个非常轻量级、基于JVM的全栈Kotlin框架，支持Java、Kotlin语言，由最好的Java库和标准精心打造。
* [Errai Framework](https://github.com/errai/errai)：Errai是一个Java/GWT Web框架，用于构建富客户端Web应用程序，由RedHat开源。
* [Stripes](https://github.com/StripesFramework/stripes)：Stripes是一个Java Web框架，其目标是使Java中基于Servlet/JSP的Web开发尽可能简单、直观。
* [BBoss](https://github.com/bbossgroups/bboss)：BBoss是一个Java EE框架，包括AOP/IoC、MVC、持久层、RPC等。
* [Latke](https://github.com/88250/latke)：Latke是一个简单易用的Java Web应用开发框架，包含MVC、IoC、事件通知、ORM、插件等组件。
* [NutzWk](https://github.com/Wizzercn/NutzWk)：开源企业级Java Web开发框架。
* [Restlight](https://github.com/esastack/esa-restlight)：Restlight是一个轻量级且面向REST的Web框架。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [Vert.x-Web](https://github.com/vert-x3/vertx-web)：Vert.x-Web是一组用于使用Vert.x构建Web应用程序的构建块。
* [TeamApps](https://github.com/teamapps-org/teamapps)：TeamApps是一个Java Web应用程序框架。
* [DotWebStack](https://github.com/dotwebstack/dotwebstack-framework)：DotWebStack框架提供了一组标准化构建块，可以用最少的开发工作构建丰富的数据服务。
* [Aspectran](https://github.com/aspectran/aspectran)：Aspectran是一个用于开发Java应用程序的框架，可用于构建简单的shell应用程序和大型企业Web应用程序。
* [Tentackle](https://bitbucket.org/krake-oss/tentackle/src/master/)：Tentackle是一个开源Java框架，适用于在多个JVM上运行的分层应用程序，其灵感来自领域驱动设计的原理。
* [appNG](https://github.com/appNG/appng)：appNG是一个Web应用程序平台和Web应用程序框架，基于Apache Tomcat和Spring框架。
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
* [Kora](https://github.com/kora-projects/kora)：Kora是一个用于编写Java/Kotlin应用程序的框架，重点关注性能、效率和透明度。

## JSF框架

* [PrimeFaces](https://github.com/primefaces/primefaces)：PrimeFaces是Java EE生态系统中最受欢迎的UI库之一。
* [JoinFaces](https://github.com/joinfaces/joinfaces)：该项目允许在Spring Boot应用程序中使用JSF。
* [PrimeFaces Extensions](https://github.com/primefaces-extensions/primefaces-extensions)：PrimeFaces Extensions项目是一个社区驱动的开源项目，其目标是成为除PrimeFaces之外的轻量级且快速的Faces组件和实用程序库。
* [Omnifaces](https://github.com/omnifaces/omnifaces)：OmniFaces是Faces的实用程序库，专注于使用标准Faces API简化日常任务的实用程序。
* [Adminfaces](https://github.com/adminfaces/admin-template)：Admin Template是一个基于Bootstrap和Admin LTE的完全响应式Java Server Faces管理模板。
* [Eclipse Mojarra](https://github.com/eclipse-ee4j/mojarra)：Eclipse基金会下的Jakarta Faces实现。
* [Apache MyFaces](https://github.com/apache/myfaces)：Apache基金会下的Jakarta Faces实现。
* [ButterFaces](https://github.com/butterfaces/butterfaces)：ButterFaces是一个轻量级响应式JSF框架，它结合了Bootstrap 4、jQuery 3和HTML 5的优点，可以使用JSF 2开发快速、简单且现代的Web应用程序。
* [RichFaces](https://github.com/richfaces/richfaces)：RichFaces项目是一个高级UI组件框架，可以使用JSF将Ajax功能轻松集成到业务应用程序中，由RedHat开源。
* [ChartistJSF](https://github.com/hatemalimam/ChartistJSF)：JavaServer Faces的高度可定制响应式图表。
* [BootsFaces](https://github.com/TheCoder4eu/BootsFaces-OSP)：这是下一代JSF框架，它充分利用了Bootstrap 3和jQuery UI，让你可以快速轻松地开发前端企业应用程序。

## REST框架

* [Rest.li](https://github.com/linkedin/rest.li)：Rest.li是一个开源REST框架，用于使用类型安全绑定和异步、非阻塞IO构建健壮、可扩展的RESTful架构，由LinkedIn开源。
* [Eclipse Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个REST框架，提供JAX-RS参考实现等。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：Dropwizard是一个Java框架，用于开发操作友好、高性能、RESTful Web Service，由Yammer开源。
* [RESTEasy](https://github.com/resteasy/resteasy)：RESTEasy是一个JBoss项目，旨在为使用Java开发客户端和服务器RESTful应用程序和服务提供生产力框架，由JBoss社区开源。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序。
* [RESTX](https://github.com/restx/restx)：RESTX是一个完整的轻量级颠覆性堆栈，其中包括类似Swagger的UI并将REST规范测试视为文档。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Restlet框架帮助Java开发人员构建更好的遵循REST架构风格的Web API，由Talend开源。
* [Magic API](https://gitee.com/ssssssss-team/magic-api)：Magic API是一个基于Java的接口快速开发框架，通过Magic API提供的UI界面完成编写接口，无需定义Controller、Service、Dao、Mapper、XML、VO等Java对象即可完成常见的HTTP API接口开发。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：Grumpyrest是一个Java REST服务器框架，不使用注解、自动依赖注入或响应流，并最大限度地减少反射的使用。
* [Resty](https://github.com/Dreampie/Resty)：Resty一款极简的RESTful轻量级的Web框架。
* [Airlift](https://github.com/airlift/airlift)：Airlift是一个用Java构建REST服务的框架。
* [Apache Juneau](https://github.com/apache/juneau)：一个使用通用框架将POJO编组到各种内容类型的工具包，并可以使用非常少的代码创建复杂的自记录REST接口和微服务。
* [Kanary](https://github.com/SeunAdelekan/Kanary)：用于在Kotlin/Java中构建REST API的简约Web框架。
* [RestExpress](https://github.com/RestExpress/RestExpress)：RestExpress是JBOSS Netty HTTP堆栈上的瘦包装器，提供一种简单易用的方法来使用Java创建支持大规模互联网规模和性能的RESTful服务。
* [Moqui Framework](https://github.com/moqui/moqui-framework)：Moqui是一个全功能、企业级应用开发框架，基于Groovy和Java语言。
* [Kilo](https://github.com/HTTP-RPC/Kilo)：Kilo是一个开源框架，用于在Java中创建和使用RESTful和类REST Web服务。
* [Crnk](https://github.com/crnk-project/crnk-framework)：Crnk是JSON API规范和建议的Java实现，旨在促进构建RESTful应用程序。
* [Hammock](https://github.com/hammock-project/hammock)：Hammock是一个简单易用的框架，用于引导CDI、启动Web服务器并能够部署REST API。
* [Apache Sling](https://sling.apache.org/)：Apache Sling是一个基于可扩展内容树的RESTful Web应用程序框架。
* [Apache Wink](https://wink.apache.org/)：Apache Wink是一个简单而可靠的框架，用于构建RESTful Web服务。
* [Rocket API](https://gitee.com/alenfive/rocket-api)：API敏捷开发框架，用于API接口功能的快速开发。
* [Proteus](https://github.com/noboomu/proteus)：Proteus是一个极快的极简Java API服务器框架，构建于Undertow之上，用于开发后端应用程序和微服务。
* [Confluent REST Utils](https://github.com/confluentinc/rest-utils)：Confluence REST Utils提供了一个小型框架和实用程序，用于使用Jersey、Jackson、Jetty和Hibernate Validator编写Java REST API。
* [EverRest](https://github.com/codenvy/everrest)：EverRest是RESTful应用程序框架以及完整的JAX-RS实现。
* [Agrest](https://github.com/agrestio/agrest)：Agrest是一个灵活的模型驱动的REST数据服务框架。
* [Lambada Framework](https://github.com/cagataygurturk/lambadaframework)：Lambada Framework是一个实现JAX-RS API的REST框架，可让你以Serverless方式将应用程序部署到AWS Lambda和API Gateway。
* [AceQL HTTP](https://github.com/kawansoft/aceql-http)：AceQL HTTP是一个类似REST的API库，允许你从任何支持HTTP的设备通过HTTP访问远程SQL数据库。
* [Conjure Java Runtime](https://github.com/palantir/conjure-java-runtime)：该项目提供了一组固定的库，用于定义和创建RESTish/RPC服务器和客户端，基于Feign作为客户端，以Dropwizard/Jersey和JAX-RS服务定义作为服务器，由Palantir开源。

## ORM框架

* [Hibernate](https://github.com/hibernate/hibernate-orm)：Hibernate是一个强大的Java ORM解决方案，可以轻松地为应用程序、库和框架开发持久层逻辑，由RedHat开源。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring Data JPA是Spring Data系列的一部分，可以轻松实现基于JPA的Repository。
* [Mybatis](https://github.com/mybatis/mybatis-3)：MyBatis是一流的持久层框架，支持自定义SQL、存储过程和高级映射。
* [Mybatis Plus](https://github.com/baomidou/mybatis-plus)：MyBatis Plus是MyBatis的一个强大的增强工具包，用于简化开发。
* [APIJSON](https://github.com/Tencent/APIJSON)：APIJSON是一种专为API而生的JSON网络传输协议以及基于这套协议实现的ORM库，由腾讯开源。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：EclipseLink为开发人员提供基于标准的对象关系持久性解决方案，并额外支持许多高级功能，Oracle开源。
* [greenDAO](https://github.com/greenrobot/greenDAO)：greenDAO是一个轻量且快速的Android ORM，可将对象映射到SQLite数据库。
* [Apache OpenJPA](https://github.com/apache/openjpa)：Apache OpenJPA是Jakarta Persistence API 3.0规范的实现。
* [QueryDSL](https://github.com/querydsl/querydsl)：QueryDSL是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。
* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，以帮助你编写更好的SQL。
* [WCDB](https://github.com/Tencent/wcdb)：WCDB是腾讯微信应用中使用的高效、完整、易用的移动数据库框架。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean是一个纯Java实现的开源ORM框架，它被设计成比JPA更简单、容易理解和使用。
* [Sugar ORM](https://github.com/chennaione/sugar)：Sugar ORM是一个Android ORM库，它提供了一种简单的方法来存储和检索数据。
* [ObjectiveSQL](https://github.com/braisdom/ObjectiveSql)：ObjectiveSQL是一个基于ActiveRecord模式的ORM框架，它鼓励快速开发和整洁，最少的代码，以及约定优于配置。
* [ORMLite](https://github.com/j256/ormlite-core)：ORMLite提供了一些简单、轻量级的功能，用于将Java对象持久保存到SQL数据库，同时避免更标准ORM包的复杂性和开销。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级ORM框架，由高盛银行开源。
* [Apache Gora](https://github.com/apache/gora)：Apache Gora框架提供内存数据模型和大数据持久化。
* [Apache Cayenne](https://github.com/apache/cayenne)：Apache Cayenne是一个开源持久层框架，提供对象关系映射(ORM)和远程处理服务。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：Jimmer是一个针对Java和Kotlin的革命性ORM，以及一套基于它的完整的集成方案。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web、ORM框架。
* [AnyLine](https://gitee.com/anyline/anyline)：AnyLine的核心是一个面向运行时的元数据动态ORM。
* [HsWeb-ORM](https://github.com/hs-web/hsweb-easy-orm)：简单的ORM工具，为动态表单而生。
* [Easy Query](https://github.com/xuejmnet/easy-query)：Easy Query是一款轻量级的ORM框架，无需任何第三方依赖。
* [Bee](https://github.com/automvc/bee)：Bee是一个人工智能、简单、高效的ORM框架，支持JDBC、Cassandra、Mongodb、Sharding。
* [Bean Searcher](https://github.com/troyzhxu/bean-searcher)：专注于高级查询的只读ORM，天然支持连接表，并且避免DTO/VO转换，使得一行代码实现复杂查询成为可能。
* [MicroStream](https://github.com/microstream-one/microstream)：MicroStream是一个突破性的Java原生对象图持久层，专为需要轻量级高性能持久层的微服务和Serverless函数而构建。
* [Speedment](https://github.com/speedment/speedment)：Speedment是一个开源Java Stream ORM工具包和运行时。
* [Beetl](https://gitee.com/xiandafu/beetlsql)：BeetlSQL的目标是提供开发高效、维护高效、运行高效的数据库访问框架。
* [Mars](https://github.com/whaleal/mars)：用于Java的MongoDB ORM/ODM框架，由上海锦木信息技术有限公司与中国东方航空公司共同开发。
* [AFinal](https://github.com/yangfuhai/afinal)：AFinal是一个Android的SQLite ORM和IoC框架。
* [Sqli](https://github.com/x-ream/sqli)：ORM SQL查询构建器。
* [Persism](https://github.com/sproket/Persism)：Persism是一个轻量级、自动发现、自动配置和约定优于配置的ORM库。
* [SQLToy](https://github.com/sagframe/sagacity-sqltoy)：SQLToy是基于Java语言开发的，兼有Hibernate面向对象操作和MyBatis灵活查询的优点，同时更贴切项目、更贴切开发者的一个关系型数据库ORM框架。
* [Android Orma](https://github.com/maskarade/Android-Orma)：Orma是一个适用于Android SQLite数据库的ORM框架。
* [Ebatis](https://github.com/ymm-tech/ebatis)：Ebatis是一个声明式ElasticSearch ORM框架。
* [Norm](https://github.com/dieselpoint/norm)：Norm是一种访问JDBC数据库的简单方法，通常只需一行代码。

## 持久层库

* [Eclipse JNoSQL](https://github.com/eclipse/jnosql)：JNoSQL是Jakarta NoSQL和Jakarta Data规范的兼容实现，可简化Java应用程序与NoSQL数据库的集成。
* [Jdbi](https://github.com/jdbi/jdbi)：Jdbi库提供了对Java和其他JVM技术(例如Kotlin、Clojure或Scala)中的关系数据库的便捷、惯用的访问。
* [Eclipse Store](https://github.com/eclipse-store/store)：EclipseStore是一个突破性的Java原生持久层，专为云原生微服务和Serverless应用程序而构建。
* [Hypersistence Utils](https://github.com/vladmihalcea/hypersistence-utils)：Hypersistence Utils库提供Spring和Hibernate实用程序，可以帮助充分利用数据访问层。
* [Sql2o](https://github.com/aaberg/sql2o)：Sql2o是一个小型Java库，可以轻松地将SQL语句的结果转换为对象。
* [LitePal](https://github.com/guolindev/LitePal)：LitePal是一个开源Android库，可以让开发人员极其轻松地使用SQLite数据库。
* [Morphia](https://github.com/MorphiaOrg/morphia)：基于Java的MongoDB对象-文档映射器。
* [Easy-ES](https://gitee.com/dromara/easy-es)：Easy-ES是一款简化ElasticSearch搜索引擎操作的开源框架，全自动智能索引托管。
* [ESClientRHL](https://gitee.com/zxporz/ESClientRHL)：EsClientRHL是一个可基于Spring Boot的ElasticSearch客户端调用封装工具。
* [Apache MetaModel](https://metamodel.apache.org/)：Apache Metamodel是一个用于处理结构化数据的Java库，它提供了强大的元数据驱动的数据访问API，支持多种数据源，如关系数据库、CSV文件等。
* [Doma](https://github.com/domaframework/doma)：Doma是适用于Java 8+的面向DAO的数据库映射框架。
* [Jinq](https://github.com/my2iu/Jinq)：Jinq为开发人员提供了一种用Java编写数据库查询的简单而自然的方法。
* [Permazen](https://github.com/permazen/permazen)：用于SQL、键值或内存数据库的持久层框架。
* [Spring JDBC Plus](https://github.com/naver/spring-jdbc-plus)：Spring JDBC Plus提供基于Spring Data JDBC的扩展，由Naver开源。
* [RSQL-JPA](https://github.com/tennaito/rsql-jpa)：该库提供了RSQL表达式到JPA Criteria Query(JPQL的对象表示)的转换器。
* [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)：SimpleFlatMapper提供了一个非常快速且易于使用的映射器。
* [QueryStream](https://github.com/querystream/querystream)：QueryStream允许你使用类似Stream的API执行JPA查询。
* [DataNucleus](https://github.com/datanucleus/datanucleus-core)：DataNucleus是一个兼容各种标准的Java数据持久化框架，完全兼容JDO1、JDO2、JDO2.1、JDO2.2、JDO2.3、和JPA1等Java标准。
* [Mongojack](https://github.com/mongojack/mongojack)：Mongojack将Java对象映射到MongoDB文档。
* [Apache EmpireDB](https://github.com/apache/empire-db)：Empire-DB是一个轻量级的关系型数据库访问库，用于处理所有关系型数据的存储、操作、检索和建模方面。
* [Kundera](https://github.com/Impetus/kundera)：Kundera是一个带有JPA接口的“多语言对象映射器”。
* [DAS](https://github.com/ppdaicorp/das)：DAS是信也科技自研的数据库访问框架。
* [Requery](https://github.com/requery/requery)：一个轻量级但功能强大的对象映射和SQL生成器，适用于Java/Kotlin/Android，支持RxJava和Java 8。
* [Apache Commons DbUtils](https://github.com/apache/commons-dbutils)：Apache Commons DbUtils包是一组用于简化JDBC开发的Java工具类。
* [FluentJPA](https://github.com/streamx-co/FluentJPA)：FluentJPA是一种用于关系型数据库和JPA的语言集成查询(LINQ)技术，它允许你通过直接集成到Java语言中来编写强类型查询。
* [Blaze Persistence](https://github.com/Blazebit/blaze-persistence)：Blaze Persistence是面向JPA提供程序的丰富Criteria API。
* [JPA Streamer](https://github.com/speedment/jpa-streamer)：JPA Streamer是一个轻量级库，用于将JPA查询表达为Java Stream。
* [Jcabi JDBC](https://github.com/jcabi/jcabi-jdbc)：流式的面向对象的JDBC包装器。
* [MongoPlus](https://gitee.com/aizuda/mongo-plus)：使用MyBatisPlus的方式，优雅的操作MongoDB，由爱组搭开源。
* [ActiveJPA](https://github.com/ActiveJpa/activejpa)：ActiveJPA是一个试图在JPA之上实现活动记录模式的Java库，该库的目标是消除创建DAO或Repository类的需要，并使DAL编程更加简单。
* [TorpedoQuery](https://github.com/xjodoin/torpedoquery)：类型安全的Hibernate查询生成器。
* [UroboroSQL](https://github.com/future-architect/uroborosql)：UroboroSQL是一个简单的SQL执行库，可以利用与Java 8兼容的2-way-SQL。
* [Hibernate Hydrate](https://github.com/arey/hibernate-hydrate)：Hibernate Hydrate项目的主要目标是填充持久实体图，从而避免著名的LazyInitializationException。
* [OData](https://github.com/RWS/odata)：这是基于OData标准的Tridion开放数据框架，完全用Java实现。
* [Japedo](https://www.logitags.com/japedo/)：Japedo是一个用于生成Java应用程序完整持久层文档的工具。
* [Apache JDO](https://github.com/apache/db-jdo)：Apache JDO是访问数据库中持久数据的标准方法，使用普通旧式Java对象(POJO)来表示持久数据。
* [Objectify](https://github.com/objectify/objectify)：Objectify是专门为Google Cloud Datastore设计的Java数据访问API。
* [EsearchX](https://gitee.com/noear/esearchx)：基于Okhttp + Snack3开发，是一个代码直白和简单的Elasticsearch ORM框架。
* [JDBCX](https://github.com/jdbcx/jdbcx)：JDBCX通过支持SQL之外的其他数据格式、压缩算法、对象映射、类型转换和查询语言来增强JDBC驱动程序。
* [Spring Filter](https://github.com/turkraft/springfilter)：使用用户友好的查询语法动态过滤JPA实体和Mongo集合。
* [Fenix](https://github.com/blinkfox/fenix)：Fenix是一个为了解决复杂动态SQL(JPQL)而生的Spring Data JPA扩展库。
* [MiniDao](https://github.com/jeecgboot/MiniDao)：MiniDao是一款轻量级Java持久层框架，基于Spring JDBC + Freemarker实现，具备Mybatis一样的SQL分离和逻辑标签能力。
* [PulseDB](https://github.com/feedzai/pdb)：PulseDB是一个用Java编写的数据库映射软件库，它提供对各种数据库实现的透明访问和操作，由Feedzai开源。
* [MilvusPlus](https://gitee.com/dromara/MilvusPlus)：MilvusPlus是一个功能强大的Java库，旨在简化与Milvus向量数据库的交互，为开发者提供类似MyBatisPlus注解和方法调用风格的直观API，由dromara社区开源。
* [FluentJdbc](https://github.com/zsoltherpai/fluent-jdbc)：FluentJdbc是一个用于方便原生SQL查询的Java库。
* [Elsql](https://github.com/OpenGamma/ElSql)：ElSql允许SQL从Java应用程序外部化。
* [Yank](https://github.com/knowm/Yank)：适用于Java应用程序的超轻量JDBC持久层。
* [SqlRender](https://github.com/OHDSI/SqlRender)：这是一个R包和Java库，用于呈现参数化SQL，并将其转换为不同的SQL方言，由OHDSI开源。

## Mybatis生态

* [Mybatis Plus](https://github.com/baomidou/mybatis-plus)：MyBatis Plus是MyBatis的一个强大的增强工具包，用于简化开发。
* [Mybatis Flex](https://github.com/mybatis-flex/mybatis-flex)：Mybatis Flex是一个优雅的Mybatis增强框架。
* [Fluent Mybatis](https://github.com/atool/fluent-mybatis)：Fluent MyBatis是一个MyBatis增强工具。
* [MybatisPlus Ext](https://gitee.com/dromara/mybatis-plus-ext)：MybatisPlus Ext对MybatisPlus做了进一步的拓展封装，即保留原功能，又添加了更多有用便捷的功能。
* [Mybatis PageHelper](https://github.com/pagehelper/Mybatis-PageHelper)：Mybatis通用分页插件。
* [Mapper](https://github.com/abel533/Mapper)：易于使用的Mybatis通用Mapper。
* [Mapper](https://gitee.com/free/Mapper)：极其方便的使用Mybatis单表的增删改查工具。
* [MyBatis-Plus-Join](https://gitee.com/best_handsome/mybatis-plus-join)：对MyBatis-Plus多表查询的扩展。
* [Mybatis Generator](https://github.com/mybatis/generator)：用于Mybatis的代码生成器。
* [MybatisPlus Generator](https://github.com/baomidou/generator)：用于MybatisPlus的代码生成器。
* [Mybatis Mate](https://gitee.com/baomidou/mybatis-mate-examples)：Mybatis-Mate为MP企业级模块，支持分库分表，数据审计、数据敏感词过滤(AC算法)，字段加密，字典回写(数据绑定)，数据权限，表结构自动生成SQL维护，支持国密SM2、SM3、SM4加密算法等。
* [MyBatis Generator UI](https://github.com/zouzg/mybatis-generator-gui)：MyBatis Generator UI是基于MyBatis Generator开发一款界面工具。
* [MyBatis Generator Plugin](https://github.com/itfsw/mybatis-generator-plugin)：Mybatis Generator代码生成插件拓展。
* [MyBatis Plus Generator UI](https://github.com/davidfantasy/mybatis-plus-generator-ui)：提供交互式的Web UI用于生成兼容Mybatis Plus框架的相关功能代码。
* [MybatisPlus Code Generator](https://github.com/fengwenyi/mybatis-plus-code-generator)：MyBatisPlus代码生成器。

## 应用框架

* [SiteMesh 3](https://github.com/sitemesh/sitemesh3)：SiteMesh是一个网页布局和装饰框架以及Web应用程序集成框架，可帮助创建由需要一致外观/感觉、导航和布局方案的页面组成的网站。
* [Gaea](https://github.com/58code/Gaea)：Gaea是服务通讯框架，支持跨平台，具有高并发、高性能、高可靠性，并提供异步、多协议、事件驱动的中间层服务框架，由58同城开源。
* [Jmix](https://github.com/jmix-framework/jmix)：Jmix是一组库和工具，用于加速Spring Boot以数据为中心的应用程序开发。
* [Apache Usergrid](https://github.com/apache/usergrid)：Usergrid是一个基于RESTful API的用于Web和移动应用程序的多租户后端即服务堆栈。
* [Para](https://github.com/Erudika/para)：Para是一个可扩展的多租户后端服务器/框架，用于对象持久化和检索。
* [Demoiselle 3](https://github.com/demoiselle/framework)：Demoiselle框架实现了集成框架的概念，其目标是通过最大限度地减少选择和集成专业框架的时间来促进应用程序的构建，从而提高生产力并保证系统的可维护性。
* [TwelveT](https://github.com/twelvet-projects/twelvet)：基于Spring Boot 3.X的Spring Cloud Alibaba/Spring Cloud Tencent + React的微服务框架。
* [Chronicle-Decentred](https://github.com/OpenHFT/Chronicle-Decentred)：Chronicle Decentred是一个用于在分布式账本技术上构建点对点安全可扩展微服务的框架。
* [BootDo](https://gitee.com/lcg0124/bootdo)：BootDo是高效率、低封装、面向学习型、微服务的开源Java EE开发框架。
* [JADA JEE Framework](https://github.com/consiglionazionaledellericerche/jada)：基于EJB3的应用程序的软件框架，它允许开发人员配置与数据呈现和持久层相关的方面，意大利国家研究委员会开源。
* [Apiary](https://github.com/DBOS-project/apiary)：Apiary是一个事务性功能即服务(FaaS)框架，用于构建面向数据库的应用程序，例如微服务和Web服务后端，这是MIT、斯坦福合作的一个研究项目。
* [Synapse](https://github.com/americanexpress/synapse)：Synapse是一组用于快速开发的轻量级基础框架模块，内置企业级成熟度和质量，由美国运通开源。
* [Salespoint Framework](https://github.com/st-tu-dresden/salespoint)：一个用于开发销售点应用程序的框架，由德累斯顿工业大学开源。
* [Dynamo](https://github.com/opencirclesolutions/dynamo)：Dynamo是一个软件开发框架，最初由Open Circle Solutions开发，旨在通过使用约定优于配置、模型驱动开发和DRY等设计原则来提高生产力。
* [Continuum Framework](https://github.com/Kinotic-Foundation/continuum-framework)：Continuum Framework是由Kinotic Foundation开发的开源软件框架，旨在为开发人员提供一组强大的工具来快速高效地创建高性能软件解决方案。
* [KivaKit](https://github.com/Telenav/kivakit)：KivaKit是一套用于日常开发的集成Java迷你框架。
* [Las2peer](https://github.com/rwth-acis/las2peer)：Las2peer是一个基于Java的服务器框架，用于在分布式点对点(P2P)环境中开发和部署微服务，由亚琛工业大学开发。
* [Chill PL](https://github.com/bigskysoftware/chill)：Chill Platform是一个Java Web和云应用程序开发平台。

## 微服务框架

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring Cloud为开发人员提供了快速构建分布式系统中一些常见模式的工具(例如配置管理、服务发现、断路器、智能路由、微代理、控制总线、短命微服务和契约测试)，由VMware(Pivotal)开源。
* [Apache Dubbo](https://github.com/apache/dubbo)：Apache Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [Jakarta EE](https://jakarta.ee/)：Jakarta EE为开发人员提供了一套全面的供应商中立的开放规范，用于从头开始开发现代云原生Java应用程序。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：Micronaut是一个基于JVM的现代全栈Java框架，旨在构建模块化、易于测试的JVM应用程序，由Object Computing开源。
* [Quarkus](https://github.com/quarkusio/quarkus)：Quarkus是一个用于编写Java应用程序的云原生容器优先框架，由RedHat开发。
* [Helidon](https://github.com/helidon-io/helidon)：Helidon是一组用于编写微服务的Java库，基于Java虚拟线程，由Oracle开发。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包。
* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个用于创建微服务、Web应用程序等的异步框架，由Jetbrains开源。
* [ServiceTalk](https://github.com/apple/servicetalk)：ServiceTalk是一个JVM网络应用程序框架，具有针对特定协议(例如HTTP/1.x、HTTP/2.x等)定制的API，并支持多种编程范例，由Apple开源。
* [Nepxion Discovery](https://github.com/Nepxion/Discovery)：Nepxion Discovery是专注于企业级云原生微服务开源解决方案。
* [Apache ServiceComb](https://github.com/apache/servicecomb-java-chassis)：Apache ServiceComb是一个用于用Java快速开发微服务的软件开发工具包，提供服务注册、服务发现、动态路由和服务管理功能，由华为开源。
* [Eclipse MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展，由IBM、RedHat、Oracle、Fujitsu、Microsoft等组织参与。
* [Axon](https://github.com/AxonFramework/AxonFramework)：Axon是一个基于DDD、CQRS和事件溯源原则构建渐进式事件驱动微服务系统的框架。
* [Misk](https://github.com/cashapp/misk)：Misk是来自Cash App的开源微服务容器，它允许你使用Kotlin或Java快速创建微服务，并提供用于常见问题的库，例如服务端点、缓存、队列、持久性、分布式租赁和集群。
* [Riposte](https://github.com/Nike-Inc/riposte)：Riposte是一个基于Netty的微服务框架，用于快速开发生产就绪的HTTP API，由Nike开源。
* [Lagom](https://github.com/lagom/lagom)：JVM平台上的响应式微服务框架，由Lightbend开源。
* [Armeria](https://github.com/line/armeria)：Armeria是适合任何情况的首选微服务框架，你可以利用自己喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Streams、Spring Boot和Dropwizard，由Line开源。
* [Light-4J](https://github.com/networknt/light-4j)：Light-4J是快速、轻量级且更高效的微服务框架。
* [Ballerina](https://github.com/ballerina-platform/ballerina-lang)：Ballerina是一种针对集成进行了优化的开源云原生编程语言，它由WSO2开发和支持。
* [Apache JClouds](https://github.com/apache/jclouds)：Apache JClouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [WSO2 Microservices Framework](https://github.com/wso2/msf4j)：MSF4J是一个用于开发和运行微服务的轻量级高性能框架，由WSO2开源。
* [NutzBoot](https://github.com/nutzam/nutzboot)：NutzBoot是可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、服务治理、负载均衡、Hystrix、RPC等解决方案。
* [Ja-Micro](https://github.com/Sixt/ja-micro)：Ja-Micro是一个用于构建微服务的轻量级Java框架。
* [JBoot](https://gitee.com/JbootProjects/jboot)：JBoot是一个基于JFinal、Dubbo、Seata、Sentinel、ShardingSphere、Nacos等开发的国产框架。
* [ActiveJ](https://github.com/activej/activej)：适用于现代Web、云、高负载和微服务解决方案的Java框架。
* [Flower](https://github.com/zhihuili/flower)：Flower是一个构建在Akka上的响应式微服务框架。
* [Dapeng-SOA](https://github.com/dapeng-soa/dapeng-soa)：Dapeng-SOA是一个轻量级、高性能的微服务框架，构建在Netty以及定制的精简版Thrift之上，大鹏开源。
* [Redkale](https://gitee.com/redkale/redkale)：Redkale是基于Java 11全新的微服务框架，包含HTTP、WebSocket、TCP/UDP、数据序列化、数据缓存、依赖注入等功能。
* [Atmosphere](https://github.com/Atmosphere/atmosphere)：Atmosphere框架包含用于构建异步Web应用程序的客户端和服务器端组件。
* [Finatra](https://github.com/twitter/finatra)：Finatra是一个轻量级框架，用于在TwitterServer和Finagle之上构建快速、可测试的Scala应用程序，由Twitter开源。
* [Open Capacity Platform](https://gitee.com/dromara/open-capacity-platform)：OCP是基于Spring Cloud的企业级微服务框架，其目标是帮助企业搭建一套类似百度能力开放平台的微服务框架，由dromara社区开源。
* [Fusion](https://github.com/yupiik/fusion)：Fusion框架旨在提供一个非常轻量级的Java框架和Graal Native。
* [Zebra](https://gitee.com/gszebra/zebra)：Zebra是国信证券的微服务框架。
* [SeedStack](https://github.com/seedstack/seed)：SeedStack是一个固执己见、易于使用的Java开发堆栈。
* [Moleculer Java](https://github.com/moleculer-java/moleculer-java)：Moleculer Java是JVM的Moleculer微服务框架的实现。
* [Worker Framework](https://github.com/WorkerFramework/worker-framework)：Worker Framework为跨平台、云就绪、分布式数据处理微服务提供了基础。

## Spring Cloud生态

* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix)：该项目通过自动配置和绑定到Spring Environment和其他Spring编程模型习惯用法，为Spring Boot应用程序提供Netflix OSS集成。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：Spring Cloud Alibaba为分布式应用开发提供一站式解决方案。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：Spring Cloud GCP项目使Spring Framework成为Google Cloud Platform(GCP)的一等公民。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是实现标准Spring Cloud SPI的一站式微服务解决方案，它将Spring Cloud与腾讯中间件集成，让微服务开发变得简单。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是微软开发的Spring Cloud框架，提供Spring与Azure服务的无缝集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：Spring Cloud AWS简化了在Spring和Spring Boot应用程序中使用AWS托管服务。
* [Spring Cloud Huawei](https://github.com/huaweicloud/spring-cloud-huawei)：Spring Cloud Huawei是一个让使用Spring Cloud开发微服务变得更加简单和高效的框架。
* [Spring Cloud Formula](https://gitee.com/baidu/spring-cloud-formula)：基于Spring Boot兼容Spring Cloud生态开发的微服务框架，是百度云CNAP(Cloud-Native Application Platform)的面向客户提供的Java微服务框架设施。
* [Spring Cloud OCI](https://github.com/oracle/spring-cloud-oci)：Spring Cloud OCI在内部OCI Java SDK的帮助下简化了与OCI服务的集成，Oracle开源。
* [Spring Cloud Services Starters](https://github.com/pivotal-cf/spring-cloud-services-starters)：Spring Cloud Services Starters是一组精选的依赖项，可在Pivotal Cloud Foundry环境中与Spring Cloud Services一起使用。

## 微服务工具

* [Apollo](https://github.com/spotify/apollo)：Apollo是Spotify编写微服务时使用的一组Java库，包含HTTP服务器和URI路由系统等模块，使得实现RESTful API服务变得轻而易举。
* [Microserver](https://github.com/aol/micro-server)：Microserver是一个Java 8原生、零配置、基于标准、久经考验的库，可通过标准Java主类运行REST微服务。
* [Eventuate Tram Core](https://github.com/eventuate-tram/eventuate-tram-core)：Eventuate Tram是一个解决微服务架构中固有的分布式数据管理问题的平台。
* [Femas](https://github.com/TencentFemas/femas)：Femas是腾讯云开源的云原生微服务一站式管理平台。
* [Moss](https://github.com/GrailStack/Moss)：Moss是Spring Cloud体系的服务治理平台。
* [Blade-Tool](https://github.com/chillzhuang/blade-tool)：Spring Blade 3.0架构核心工具包。
* [Conjure](https://github.com/palantir/conjure)：Conjure是一个简单的工具链，用于定义一次API并生成多种语言的客户端/服务器接口，由Palantir开源。
* [GreenLightning](https://github.com/oci-pronghorn/GreenLightning)：高性能微服务运行时。
* [Hexagon](https://github.com/hexagonkt/hexagon)：Hexagon是一个用Kotlin编写的微服务工具包，其目的是简化在云平台内运行的服务器应用程序的构建。
* [Mica](https://gitee.com/596392912/mica)：Spring Cloud微服务开发核心工具集，支持Web和WebFlux。
* [Uship](https://github.com/yupiik/uship)：Uship是一个适用于现代应用程序的轻量级微服务堆栈。
* [AdeptJ Runtime](https://github.com/AdeptJ/adeptj-runtime)：适用于RESTful API、微服务和Web应用的高性能、动态、模块化运行时。
* [Prana](https://github.com/Netflix/Prana)：用于基于Netflix OSS的服务的Sidecar，由Netflix开源。
* [Sermant](https://github.com/huaweicloud/Sermant)：Sermant是基于Java字节码增强技术的无代理服务网格，其利用Java字节码增强技术为宿主应用程序提供服务治理功能，以解决大规模微服务体系结构中的服务治理问题，由华为开源。
* [Water](https://gitee.com/noear/water)：为Java服务开发和治理，提供一站式解决方案(可以理解为微服务架构支持套件)。
* [Juggle](https://github.com/somta/Juggle)：Juggle是一个可用于接口编排、定制开发等场景的一套完整解决方案。
* [Edison-MicroService](https://github.com/otto-de/edison-microservice)：Spring Boot之上的独立库集合，可提供更快的JVM微服务设置。
* [Squbs](https://github.com/paypal/squbs)：Squbs是一套组件，可在大规模托管云环境中实现Akka和Akka HTTP应用程序/服务的标准化和可操作化，Paypal开源。
* [iBizLab-Runtime](https://gitee.com/ibizlab/ibizlab-runtime)：提供一个完整的微服务架构轻量级支撑运行时系统。
* [Infinitic](https://github.com/infiniticio/infinitic)：Infinitic是一个基于Apache Pulsar的框架，可大大简化异步分布式应用程序的构建。
* [LittleHorse](https://github.com/littlehorse-enterprises/littlehorse)：LittleHorse是一个高性能的微服务编排引擎，允许开发人员构建可扩展、可维护和可观察的应用程序。
* [Oracle Bedrock](https://github.com/coherence-community/oracle-bedrock)：Oracle Bedrock提供了一个通用Java框架，用于开发、编排和测试高度并发的分布式应用程序。
* [SIP Framework](https://github.com/IKOR-GmbH/sip-framework)：该框架能够使用微服务构建轻量级集成适配器，以实现系统的技术和非技术解耦，因此具有高度可扩展性。
* [Mats3](https://github.com/centiservice/mats3)：Mats3是一个Java库，可促进异步、无状态、多阶段、基于消息的服务的开发。

## 测试

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试、断言库、Mock框架等。

#### 单元测试

* [JUnit 4](https://github.com/junit-team/junit4)：JUnit是一个用于编写可重复测试的简单框架。
* [JUnit 5](https://github.com/junit-team/junit5)：用于Java和JVM的测试框架的第五个主要版本。
* [TestNG](https://github.com/testng-team/testng)：TestNG是一个受JUnit启发的测试框架，但引入了一些新功能，使其更强大且更易于使用。
* [Spock](https://github.com/spockframework/spock)：Spock是一个用于Java和Groovy应用程序的BDD风格的开发人员测试和规范框架。
* [Robolectric](https://github.com/robolectric/robolectric)：Robolectric是Android的行业标准单元测试框架。
* [Kotest](https://github.com/kotest/kotest)：Kotest是一个灵活且全面的Kotlin测试工具，具有多平台支持。
* [ScalaTest](https://github.com/scalatest/scalatest)：ScalaTest是一个为Scala和Java程序员提供的免费开源测试工具包。
* [uTest](https://github.com/com-lihaoyi/utest)：uTest是一个简单、直观的Scala测试库。
* [Flow](https://github.com/Mastercard/flow)：Mastercard开源的测试框架。
* [MUnit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。
* [Unitils](http://www.unitils.org/summary.html)：Unitils是一个开源库，旨在使单元和集成测试变得简单且可维护。
* [Eclipse Xpect](https://github.com/eclipse/Xpect)：Xpect是一个单元测试和集成测试框架，可将测试数据存储在任何类型的文本文件中，并且基于JUnit。

#### 集成测试

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：Testcontainers是一个支持JUnit测试的Java库，提供通用数据库、Selenium Web浏览器或任何其他可以在Docker容器中运行的东西的轻量级一次性实例。
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
* [Testcontainers Spring Boot](https://github.com/PlaytikaOSS/testcontainers-spring-boot)：基于Spring Boot的集成测试的容器自动配置。
* [Embedded Process Util](https://github.com/flapdoodle-oss/de.flapdoodle.embed.process)：Embedded Process Util为在单元测试中运行流程提供一种平台中立的方式。
* [Embedded PostgreSQL Server](https://github.com/yandex-qatools/postgresql-embedded)：嵌入式PostgreSQL服务器提供了一种平台中立的方式来在单元测试中运行Postgres二进制文件。
* [Embedded Cassandra](https://github.com/nosan/embedded-cassandra)：Embedded Cassandra提供了一种启动和停止Apache Cassandra的简单方法。
* [CassandraUnit](https://github.com/jsevellec/cassandra-unit)：CassandraUnit是一个Java测试工具，它可以用于测试使用Cassandra数据库后端创建的Java应用程序。
* [Alternator](https://github.com/mboudreau/Alternator)：用于测试目的在本地运行的模拟DynamoDB。
* [Keycloak Testcontainer](https://github.com/dasniko/testcontainers-keycloak)：Keycloak SSO的Testcontainers实现。
* [MongoUnit](https://github.com/mongounit/mongounit)：MongoUnit是一个数据驱动的集成测试框架，适用于使用MongoDB进行持久化的基于Spring Boot的应用程序。
* [Arquillian](https://github.com/arquillian/arquillian-core)：提供了用于集成测试的组件模型，其中包括依赖注入和容器生命周期管理。
* [Kindcontainer](https://github.com/dajudge/kindcontainer)：基于Java的Testcontainers容器实现，为集成测试提供临时Kubernetes集群。
* [Embedded DB JUnit](https://github.com/zapodot/embedded-db-junit)：提供内存数据库的JUnit Rule(支持H2和HyperSQL)。
* [Nats Server Embedded](https://github.com/YunaBraska/nats-server-embedded)：用于测试的Nats服务器。

#### 接口测试

* [Rest Assured](https://github.com/rest-assured/rest-assured)：Rest Assured是用于轻松测试REST服务的Java DSL。
* [Wisdom](https://github.com/wisdom-projects/rest-client)：Wisdom可以自动化测试REST API并生成精美的测试报告，同时基于测试过的历史数据，可以生成精美的REST API文档。
* [CATS](https://github.com/Endava/cats)：CATS是一个REST API模糊器和OpenAPI端点的负面测试工具。
* [AgileTC](https://github.com/didi/AgileTC)：AgileTC是一个基于思维导图的具有多实时协作能力的测试用例管理平台，由滴滴开源。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [Stove](https://github.com/Trendyol/stove)：Stove是一个端到端测试框架，可以将物理依赖项和你的应用程序一起启动，由Trendyol开源。
* [HybridTestFramework](https://github.com/dipjyotimetia/HybridTestFramework)：Web、API、云、事件和安全性的端到端测试框架。
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
* [Arquillian Graphene](https://github.com/arquillian/arquillian-graphene)：利用WebDriver和简洁的AJAX就绪API进行强大的功能测试。
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

* [Apache JMeter](https://github.com/apache/jmeter)：Apache JMeter开源负载测试工具，用于分析和测量各种服务的性能。
* [NGrinder](https://github.com/naver/ngrinder)：NGrinder是一个压力测试平台，使你能够同时执行脚本创建、测试执行、监控和结果报告生成器，Naver开源。
* [Gatling](https://github.com/gatling/gatling)：Gatling是一个负载测试工具，它正式支持HTTP、WebSocket、Server-Sent-Events和JMS。
* [Grinder](https://grinder.sourceforge.net/)：Grinder是一个Java负载测试框架，可以使用许多负载注入器轻松运行分布式测试。
* [JMH](https://github.com/openjdk/jmh)：JMH是一个Java工具，用于构建、运行和分析用Java和其他针对JVM的语言编写的宏观基准测试，Oracle开源。
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
* [Apache Unomi](https://github.com/apache/unomi)：Apache Unomi存储用户个人资料信息，主要用于为A/B测试和个性化提供后端服务器，由Jahia开源。

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
* [Unlogged Java SDK](https://github.com/unloggedio/unlogged-sdk)：Unlogged Java SDK支持以二进制格式记录代码执行。
* [Drill4J](https://github.com/Drill4J/drill4j)：Drill4J是一款开源工具，用于识别测试差距并减少回归测试所花费的时间。

#### 契约测试

* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [Spring Cloud Contract](https://github.com/spring-cloud/spring-cloud-contract)：Spring对消费者驱动契约的支持。
* [Stubby4j](https://github.com/azagniotov/stubby4j)：HTTP/1.1、HTTP/2和WebSocket存根服务器，用于在Docker和非容器化环境中存根分布式Web服务以进行契约测试。
* [Contract Test Runner](https://github.com/wso2/contract-test-runner)：用于契约测试的Java库，由WSO2开源。
* [ContractCase Contract Testing Framework](https://github.com/case-contract-testing/java-dsl)：这是ContractCase契约测试框架的Java绑定。
* [Specmatic](https://github.com/znsio/specmatic)：Specmatic通过利用API规范作为可执行合约来体现契约驱动开发(CDD)。

#### 渗透测试

* [Cobalt Strike](https://www.cobaltstrike.com/)：Cobalt Strike是一款基于Java的渗透测试神器。
* [TrackRay](https://github.com/iSafeBlue/TrackRay)：溯光是一个开源渗透测试框架，框架自身实现了漏洞扫描功能，集成了知名安全工具：Metasploit、Nmap、Sqlmap、AWVS、Burpsuite等。
* [Jackhammer](https://github.com/olacabs/jackhammer)：Jackhammer是一款协作工具，旨在弥合安全团队与开发团队、QA团队之间的差距，并成为TPM的促进者，以了解和跟踪投入生产的代码的质量。
* [WS-Attacker](https://github.com/RUB-NDS/WS-Attacker)：WS-Attacker是一个用于Web服务渗透测试的模块化框架，由波鸿鲁尔大学开发。

#### 快照测试

* [ApprovalTests](https://github.com/approvals/ApprovalTests.Java)：Java的ApprovalTest验证库。
* [Java Snapshot Testing](https://github.com/origin-energy/java-snapshot-testing)：Java测试的Facebook风格快照测试。
* [Selfie](https://github.com/diffplug/selfie)：快照测试是记录和指定系统及其组件行为的最快且最精确的机制。

#### 黑盒&白盒测试

* [RESTest](https://github.com/isa-group/RESTest)：RESTest是一个用于RESTful Web API自动化黑盒测试的框架。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：MicroShed Test提供了一种快速、简单的方法来为Java微服务应用程序编写和运行真正的生产集成测试。
* [ACTS](https://github.com/sofastack/sofa-acts)：ACTS是一个基于数据模型驱动的白盒测试框架，由蚂蚁开源。

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
* [MockFramework](https://www.sapient.ai/blog/mockframework-java-mocking-frameworks)：MockFramework可用于创建用于测试Java应用程序的模拟对象。
* [Mock-Box](https://github.com/mock-box/mock-box)：一个轻量级且功能强大的支持测试的Mock库。

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
* [Betamax](https://github.com/betamaxteam/betamax)：Betamax是一个用于在测试中模拟外部HTTP资源的工具，该项目的灵感来自于Ruby的VCR库。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [Restito](https://github.com/mkotsur/restito)：Restito是一个用于验证代码与REST服务交互的工具。
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP)：DeepfakeHTTP是一个使用HTTP转储作为响应源的Web服务器。
* [Jadler](https://github.com/jadler-mocking/jadler)：Jadler是一个Java库，用于以声明方式存根和模拟HTTP服务器和资源。
* [SpecMock](https://github.com/specmock/specmock)：SpecMock提供了各种规格的Mock Server，提供轻量、快速且易于使用的体验。
* [ZeroMock](https://github.com/tonivade/zeromock)：零依赖的模拟HTTP Server。
* [OKHttp Client Mock](https://github.com/gmazzo/okhttp-client-mock)：一个简单的OKHttp客户端Mock，使用可编程请求拦截器。
* [OkReplay](https://github.com/airbnb/okreplay)：OkReplay旨在通过拦截应用程序发起的HTTP连接并重放之前记录的响应，由Airbnb开发。
* [RESTMock](https://github.com/andrzejchm/RESTMock)：RESTMock是一个建立在MockWebServer之上的库，它允许你指定Hamcrest匹配器来匹配HTTP请求并指定要返回的响应。

#### Mock工具

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

#### 测试数据生成器

* [Java Faker](https://github.com/DiUS/java-faker)：Java Faker是Ruby的stympy/faker gem的Java端口，用于生成假数据。
* [Instancio](https://github.com/instancio/instancio)：Instancio是一个Java库，可以自动为单元测试创建和填充对象。
* [JUnit DataProvider](https://github.com/TNG/junit-dataprovider)：类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：Datafaker是一个用于Java和Kotlin生成虚假数据的库。
* [EasyRandom](https://github.com/j-easy/easy-random)：Easy Random是一个生成随机Java对象的库。
* [MockNeat](https://github.com/nomemory/mockneat)：Mockneat是一个用Java编写的任意数据生成器开源库。
* [jFairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：Jmockdata是一款实现模拟Java类或对象的实例化并随机初始化对象的数据的工具框架。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：Fixture Monkey旨在轻松生成可控的任意实例，它允许你在多个测试中重复使用实例的相同配置，由Naver开源。
* [Burst](https://github.com/square/burst)：Burst是用于不同测试数据的单元测试库，由Square开源。
* [Log Synth](https://github.com/tdunning/log-synth)：Log Synth的主要用途是根据指定的模式生成数据。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。
* [Beanmother](https://github.com/keepcosmos/beanmother)：Beanmother有助于创建各种对象，可以非常轻松地使用用于测试的夹具。
* [Common-Random](https://github.com/yindz/common-random)：用于测试目的的简单易用随机数据生成器。
* [JFactory](https://github.com/leeonky/jfactory)：通过工厂方法创建具有某些默认属性测试数据的工具库。
* [DataHelix](https://github.com/finos/datahelix)：DataHelix可以快速生成丰富且真实的数据用于模拟和测试。
* [Fixture Factory](https://github.com/six2six/fixture-factory)：Fixture Factory是一个帮助开发人员快速构建和组织假对象以进行单元测试的工具。
* [Wordnet Random Name](https://github.com/kohsuke/wordnet-random-name)：用于测试的人类友好随机名称生成器。
* [Podam](https://github.com/mtedone/podam)：Podam是一个Java测试工具，可以用虚构的数据自动填充POJO。
* [AutoParams](https://github.com/AutoParams/AutoParams)：AutoParams是一个专为Java参数化测试而设计的任意测试数据生成器，其灵感来自AutoFixture。
* [Java Random](https://github.com/merkle-open/java-random)：该模块提供了一种通用机制来创建Java对象的随机测试虚拟对象。
* [JFixture](https://github.com/FlexTradeUKLtd/jfixture)：JFixture是一个自动填充测试数据的Java库。
* [DataFactory](https://github.com/andygibson/datafactory)：用于生成测试数据的Java库。
* [Mock.java](https://gitee.com/ForteScarlet/Mock.java)：这是一个仿照Mock.js语法的Java语言使用的假数据生成工具框架。
* [Java-Generator](https://github.com/binarywang/java-testdata-generator)：Java实现的各种随机测试数据生成器，包括身份证号码、银行卡号、姓名、汉字、手机号、电子邮箱地址和生成insert sql参数列表字符串等。
* [Test Data Supplier](https://github.com/sskorol/test-data-supplier)：该仓库包含TestNG DataProvider包装器，有助于以更灵活的方式提供测试数据。
* [Data-Factory](https://github.com/houbb/data-factory)：Data-Factory用于根据对象随机自动生成初始化信息。
* [Elmyr](https://github.com/xgouchet/Elmyr)：Elmyr是一个Kotlin库，提供生成随机值的工具。
* [EvoSQL](https://github.com/SERG-Delft/evosql)：EvoSQL是一种自动为SQL查询生成测试数据的工具，由代尔夫特理工大学开源。
* [RandomJson](https://github.com/mangatmodi/RandomJson)：RandomJson提供Kotlin/Java库来创建随机JSON字符串。
* [Nomen est Omen](https://github.com/igr/nomen-est-omen)：这个Java库有助于生成一些随机名称，你可以将它们用于某些唯一的ID或密码。
* [Model Citizen](https://github.com/mguymon/model-citizen)：Model Citizen是一个基于注解的Java模型工厂。
* [Test Arranger](https://github.com/ocadotechnology/test-arranger)：将测试数据排列为完全填充的对象。
* [Datagen](https://github.com/qala-io/datagen)：用于生成随机数据(数字、字符串、日期)的Java库-以便于随机测试。
* [Fabricator](https://github.com/azakordonets/fabricator)：Fabricator是随机字符串、数字等的极简生成器，有助于减少单调性。

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
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Lambda Behave是Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：Spectrum受到BDD框架Jasmine和RSpec的启发，将它们的表达语法和功能风格引入Java测试。
* [Specs2](https://github.com/etorreborre/specs2)：Specs2是一个用于在Scala中编写可执行软件规范的库。
* [YatSpec](https://github.com/bodar/yatspec)：YatSpec是一个BDD测试框架，可以运行你的JUnit测试并生成人类可读的HTML报告。
* [SmartBDD](https://github.com/bit-smart-io/smart-bdd)：从Java代码创建交互式HTML文档/功能文件的BDD框架。
* [BDD Security](https://github.com/iriusrisk/bdd-security)：BDD Security是一个安全测试框架，它使用行为驱动开发概念来创建自我验证的安全规范。
* [J8Spec](https://github.com/j8spec/j8spec)：J8Spec是一个库，允许用Java编写的测试遵循RSpec和Jasmine引入的BDD风格。
* [Narrative](https://github.com/tim-group/narrative)：用于使用流式Java构建行为驱动测试的框架。
* [Wakamiti](https://github.com/iti-ict/wakamiti)：Wakamiti是一款受Cucumber启发的自动化测试工具，专注于使用自然语言进行黑盒测试，由瓦伦西亚理工大学开源。
* [Akita](https://github.com/alfa-laboratory/akita)：基于Cucumber和Selenide的BDD测试步骤库。
* [Cuppa](https://github.com/cuppa-framework/cuppa)：Cuppa是Java 8的测试框架，它使编写测试变得高效且有趣。
* [JDave](https://github.com/jdave/JDave)：JDave是Java的BDD框架。

#### 测试生成器

* [Auto Unit Test Case Generator](https://github.com/traas-stack/auto-unit-test-case-generator)：Auto Unit Test Case Generator自动生成Java的高级代码覆盖JUnit测试套件，在蚂蚁中广泛使用。
* [Tcases](https://github.com/Cornutum/tcases)：Tcases是基于模型的测试用例生成器。
* [JCUnit](https://github.com/dakusui/jcunit)：JCUnit是一个基于模型的开源测试框架，由组合交互测试技术提供支持。
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

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库。
* [Selenium Jupiter](https://github.com/bonigarcia/selenium-jupiter)：Selenium Jupiter是一个开源Java库，它实现了用于开发Selenium WebDriver测试的JUnit 5扩展。
* [Zalenium](https://github.com/zalando/zalenium)：Zalenium是一个灵活且可扩展的基于容器的Selenium Grid，具有视频录制、实时预览、基本身份验证和仪表板，由Zalando开源。
* [Selenide](https://github.com/selenide/selenide)：Selenide是一个用Java编写易于阅读和易于维护的自动化测试的框架。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：WebDriverManager是一个开源Java库，用于对Selenium WebDriver所需的驱动程序(例如chromedriver、geckodriver、msedgedriver等)进行管理。
* [Selendroid](https://github.com/selendroid/selendroid)：Selendroid是一个测试自动化框架，它通过Selendroid驱动Android原生和混合应用程序以及移动Web的UI。
* [jBrowserDriver](https://github.com/MachinePublishers/jBrowserDriver)：与Selenium WebDriver规范兼容的可编程、可嵌入的Web浏览器驱动程序。
* [Html Elements](https://github.com/yandex-qatools/htmlelements)：Html Elements是一个Java框架，提供在网页测试中与网页元素交互的易于使用的方式。
* [FluentSelenium](https://github.com/SeleniumHQ/fluent-selenium)：FluentSelenium是Selenium 2+的包装器，添加了用于浏览器的流式界面样式，可以更轻松、更快速地编写Web UI测试。
* [Frameworkium](https://github.com/Frameworkium/frameworkium-core)：Frameworkium是用于Web、应用程序和API测试的快速启动自动化框架。
* [Conductor](https://github.com/conductor-framework/conductor)：Selenium WebDriver API的包装器。
* [aShot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具，截图、裁剪、美化、比较。
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
* [Atlassian Selenium](https://bitbucket.org/atlassian/atlassian-selenium/src/master/)：由Atlassian开源的项目，旨在促进Selenium/WebDriver库中功能测试的开发。
* [Jalenium](https://lkkushan.gitbook.io/jalenium)：Jalenium是一个Selenium Java包装器，使Selenium Java中的测试自动化更加简单。
* [Selenium Grid Extras](https://github.com/groupon/Selenium-Grid-Extras)：Selenium Grid Extras是一个帮助你设置和管理本地Selenium Grid的项目。
* [Selenium Grid Router](https://github.com/seleniumkit/gridrouter)：Selenium Grid Router是一个轻量级服务器，它将Selenium Webdriver请求路由和代理到多个Selenium集线器。
* [Testy](https://github.com/RWS/Testy)：Testy是用于Web应用程序的Selenium WebDriver测试框架。

#### 自动化框架

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库。
* [Playwright](https://github.com/microsoft/playwright-java)：Playwright是一个Java库，可通过单个API实现Chromium、Firefox和WebKit的自动化，由Microsoft开源。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [SeLion](https://github.com/paypal/SeLion)：SeLion是Paypal开源的自动化测试工具。
* [Robotium](https://github.com/robotiumtech/robotium)：Robotium是一个Android测试自动化框架，完全支持原生和混合应用程序。
* [JDI Light](https://github.com/jdi-testing/jdi-light)：JDI Light是一个功能强大的测试自动化框架，有助于使你的测试快速、可持续，并提供明显且可预测的测试运行结果，由EPAM开源。
* [ZeroCode](https://github.com/authorjapps/zerocode)：ZeroCode是一个社区开发的免费开源自动化测试框架，用于微服务API、Kafka和负载测试。
* [Carina](https://github.com/zebrunner/carina)：Carina是一个基于Java的测试自动化框架。
* [Geb](https://github.com/geb/geb)：Geb是一种浏览器自动化解决方案，它汇集了WebDriver的强大功能、jQuery内容选择的优雅性、页面对象建模的稳健性以及Groovy语言的表现力。
* [HBrowser](https://github.com/Osiris-Team/HBrowser)：无头/完整的Java浏览器，支持下载文件、使用Cookie、检索HTML和模拟真实用户输入。
* [ATS Framework](https://github.com/Axway/ats-framework)：Axway自动化测试系统(ATS)是内部开发的测试框架，广泛用于满足大多数Axway产品的测试需求。
* [Appium Client](https://github.com/appium/java-client)：用于编写符合WebDriver协议的Appium测试的Java语言绑定。
* [Ride](https://github.com/adobe/ride)：Ride是一个与服务无关、模块化、可扩展的Java REST API自动化框架，由Adobe开源。
* [Boyka Framework](https://github.com/BoykaFramework/boyka-framework)：测试自动化框架，可在任何平台上自动化任何应用程序。
* [Gepard](https://github.com/epam/Gepard)：Gepard是一个基于JUnit的测试自动化框架，由EPAM开源。
* [TestZeus](https://github.com/TestZeus/TestZeus)：TestZeus是专为Salesforce构建的开源自动化框架。
* [UI-Automation](https://github.com/mmarquee/ui-automation)：UI-Automation是一个用于自动化(通过MS UIAutomation库)基于Win32(包括Delphi)、WPF和其他Windows应用程序(包括Java SWT)的富客户端应用程序的框架。
* [FastAutoTest](https://github.com/y-grey/FastAutoTest)：FastAutoTest是一个基于Appium的快速自动化框架。
* [Selcukes Java](https://github.com/selcukes/selcukes-java)：Selcukes是一个强大的开源测试库，适用于Web、移动、桌面应用程序和API端点，旨在创建可扩展的高质量自动化测试。
* [Smart Test Framework](https://github.com/HPInc/smart-test-framework)：Smart Test Framework是一个多用途测试框架，能够为网页、Web服务、桌面应用程序和移动应用程序创建自动化测试，由惠普开源。
* [TestHub](https://gitee.com/dromara/TestHub)：TestHub是一款基于流程编排的自动化测试工具，由dromara社区开源。
* [JSystem](https://github.com/Top-Q/jsystem)：JSystem是一个用于编写和管理自动化系统测试的专业开源框架。

#### 测试报告

* [Allure](https://github.com/allure-framework/allure2)：Allure Report是一种灵活的多语言测试报告工具，可向你展示已测试内容的详细表示，并从日常测试执行中提取最大程度的信息。
* [Scott](https://github.com/dodie/scott)：获取非常详细的测试失败消息，无需断言库、额外配置或对现有测试进行更改。
* [ReportPortal](https://github.com/reportportal/reportportal)：ReportPortal是一项TestOps服务，它提供了增强的功能，通过使用内置分析功能来加速结果分析和报告。
* [Zebrunner Reporting](https://github.com/zebrunner/reporting)：Zebrunner Reporting是一种测试自动化管理工具，可累积并表示测试结果。
* [Difido Reports](https://github.com/Top-Q/difido-reports)：该项目旨在为各种功能测试自动化框架提供灵活、实时的HTML报告。
* [Cluecumber](https://github.com/trivago/cluecumber)：用于从Cucumber BDD、Karate和其他框架生成的Cucumber兼容JSON文件创建聚合测试报告。
* [Open Test Reporting](https://github.com/ota4j-team/open-test-reporting)：与语言无关的测试报告格式和工具。
* [Cucumber Reporting](https://github.com/damianszczepanik/cucumber-reporting)：这是一个Java报告发布器，主要用于在Jenkins构建服务器上发布Cucumber报告。
* [Java TestNG](https://github.com/reportportal/agent-java-testNG)：将结果上传到ReportPortal服务器的TestNG报告器。
* [Spock Reports](https://github.com/renatoathaydes/spock-reports)：该项目是Spock的全局扩展，用于创建测试报告。

#### QA自动化

* [Stevia](https://github.com/persado/stevia)：Stevia是Persado的开源QA自动化测试框架。
* [QMetry](https://github.com/qmetry/qaf)：使用Selenium、WebDriver、TestNG和Jersey的Web、MobileWeb移动原生和Rest Web服务的质量自动化框架。
* [AET](https://github.com/wttech/aet)：AET是一个检测网站上的视觉变化并执行基本页面健康检查(如W3C合规性、可访问性、HTTP状态码、JS错误检查等)的系统。

#### 自动化工具

* [MeterSphere](https://github.com/metersphere/metersphere)：MeterSphere是一站式开源持续测试平台，涵盖测试跟踪、接口测试、UI测试和性能测试等功能，全面兼容JMeter、Selenium等主流开源标准，由飞致云开源。
* [Sonic](https://github.com/SonicCloudOrg/sonic-server)：Sonic是一个集远程控制调试和移动设备自动化测试于一体的平台，致力于为全球开发者和测试工程师创造更好的使用体验。
* [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb)：LuckyFrame是一款免费开源的测试平台，最大的特点是全纬度覆盖了接口自动化、WEB UI自动化、APP自动化。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具，由阿里开源。
* [HydraLab](https://github.com/microsoft/HydraLab)：HydraLab是一个可以帮助你利用现有的测试设备/机器轻松构建云测试平台的框架，由微软开源。
* [Hamibot](https://github.com/hamibot/hamibot)：Hamibot是一款Android平台JavaScript自动化工具，无需Root，基于Auto.js。
* [Testsigma](https://github.com/testsigmahq/testsigma)：Testsigma是一个开源、可扩展的测试自动化平台，开箱即用。
* [OpenTest](https://github.com/mcdcorp/opentest)：OpenTest是一款免费开源功能测试自动化工具，适用于Web应用程序、移动应用程序和API，麦当劳开源。
* [VIVIDUS](https://github.com/vividus-framework/vividus)：VIVIDUS是一种测试自动化工具，为测试最流行的应用程序类型提供已实施的解决方案。
* [Cerberus](https://github.com/cerberustesting/cerberus-core)：Cerberus Test是一个低代码测试自动化平台，支持测试Web、iOS、Android和API(REST、SOAP和Kafka)应用程序。
* [SHAFT](https://github.com/ShaftHQ/SHAFT_ENGINE)：SHAFT是一个统一的测试自动化引擎，由一流的框架提供支持，提供类似向导的语法来高效推动自动化、最大化你的投资回报率并最小化你的学习曲线。
* [AutoMeter](https://gitee.com/season-fan/autometer-api)：AutoMeter是一款针对分布式服务、微服务API做功能和性能一体化的自动化测试平台。
* [AppiumTestDistribution](https://github.com/AppiumTestDistribution/AppiumTestDistribution)：一个用于跨设备并行运行Android和iOS Appium测试的工具。
* [Neodymium](https://github.com/Xceptance/neodymium-library)：Neodymium尝试通过结合JUnit、WebDriver、BDD/Cucumber和适当的报告来解决典型且最紧迫的UI测试自动化问题。
* [Video Recorder](https://github.com/SergeyPirogov/video-recorder-java)：该库只需添加一些注解即可轻松录制UI测试的视频。
* [Step](https://github.com/exense/step)：Step是一个统一的软件自动化平台，可让你充分利用自动化工件，同时摆脱特定工具。
* [TESTAR](https://github.com/TESTARtool/TESTAR_dev)：TESTAR是一款能够在GUI级别对桌面、Web和移动应用程序进行无脚本自动化系统测试的工具，由瓦伦西亚理工大学、乌得勒支大学和荷兰开放大学等开发。
* [Testerra](https://github.com/telekom/testerra)：Testerra是一个用于自动测试(Web)应用程序的集成框架，由德国电信开源。
* [ReVoman](https://github.com/salesforce-misc/ReVoman)：ReVoman是一个JVM API自动化工具，它通过让你在JVM程序/测试中执行Postman集合来重新构想API自动化，由Salesforce开源。

#### 多线程测试

* [Awaitility](https://github.com/awaitility/awaitility)：Awaitility是一种 DSL，允许你以简洁且易于阅读的方式表达对异步系统的期望。
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

## 代码覆盖率

* [JaCoCo](https://github.com/jacoco/jacoco)：JaCoCo是一个免费的Java代码覆盖率库。
* [Eclipse EclEmma](https://github.com/eclipse-eclemma/eclemma)：Eclipse EclEmma是Eclipse IDE的Java代码覆盖率工具。
* [Super JaCoCo](https://github.com/didi/super-jacoco)：Super-JaCoCo基于JaCoCo、Git二次开发打造的一站式Java代码全量/diff覆盖率收集平台，能够低成本、无侵入的收集代码覆盖率数据，由滴滴开源。
* [Clover](https://bitbucket.org/atlassian/clover)：Atlassian开源的Java和Groovy代码覆盖率工具。
* [Cobertura](https://github.com/cobertura/cobertura)：Cobertura是一个免费的Java代码覆盖率报告工具。
* [JSCover](https://github.com/tntim96/JSCover)：JSCover是一个易于使用的JavaScript代码覆盖率测量工具。
* [EMMA](https://emma.sourceforge.net/)：EMMA是一个用于测量和报告Java代码覆盖率的开源工具包。
* [Codecov](https://about.codecov.io/)：Codecov是适用于任何测试套件的一体化代码覆盖率报告解决方案。
* [JCov](https://github.com/openjdk/jcov)：JCov开源项目用于收集与测试套件的生产相关的质量指标，Oracle开源。
* [Parasoft JTest](https://www.parasoft.com/)：包括多种现代QA工具，允许测量代码覆盖率，并对其进行静态和动态分析，这是一款商业工具。
* [IntelliJ IDEA Coverage](https://github.com/JetBrains/intellij-coverage)：JVM代码覆盖率引擎，支持分支覆盖率和每次测试覆盖率跟踪。
* [OpenClover](https://github.com/openclover/clover)：OpenClover测量Java和Groovy的代码覆盖率并收集20多个代码指标。

## 构建工具

* [Apache Maven](https://github.com/apache/maven)：Apache Maven是一个软件项目管理和理解工具。
* [Apache Mvnd](https://github.com/apache/maven-mvnd)：Mvnd是Apache Maven团队借鉴了Gradle和Takari后衍生出的更快的构建工具。
* [Gradle](https://github.com/gradle/gradle)：Gradle是一个构建工具，专注于构建自动化并支持多语言开发。
* [Bazel](https://github.com/bazelbuild/bazel)：Bazel是一个快速、多语言且可扩展的构建系统，由Google开发。
* [Apache Ant](https://github.com/apache/ant)：Apache Ant是一个基于Java的构建工具。
* [Buck](https://github.com/facebook/buck)：Buck是一个快速构建系统，鼓励在各种平台和语言上创建小型、可重用的模块，由Facebook开发。
* [SBT](https://github.com/sbt/sbt)：SBT是一个适用于Scala、Java的构建工具。
* [Mill](https://github.com/com-lihaoyi/mill)：Mill是一个现代化的构建工具，支持Scala和Java项目的构建和管理。
* [Pants](https://github.com/pantsbuild/pants)：Pants是一个快速、可扩展、用户友好的构建系统，适用于各种规模的代码库，由Twitter开源。
* [1JPM](https://github.com/Osiris-Team/1JPM)：1JPM是一种Maven/Gradle替代方案，但有所不同，它本身是一个Java文件，你应该编辑该文件来配置你的项目。
* [Boot](https://github.com/boot-clj/boot)：Boot是一个Clojure构建框架和临时Clojure脚本评估器。
* [JeKa](https://github.com/jeka-dev/jeka)：JeKa是一个Java构建工具，用于直接从源代码构建或执行Java应用程序和脚本。
* [Apache Ivy](https://github.com/apache/ant-ivy)：Apache Ivy是一个用于管理(记录、跟踪、解决和报告)项目依赖关系的工具，具有很高的灵活性和可配置性，并且与Ant紧密集成。
* [Leiningen](https://github.com/technomancy/leiningen)：Leiningen是一种构建自动化和依赖管理工具，用于以Clojure编程语言编写的软件项目的简单配置。
* [Maven Wrapper](https://github.com/takari/maven-wrapper)：Gradle Wrapper的Maven类似物，允许在不安装Maven的情况下构建项目。
* [BLD](https://github.com/rife2/bld)：BLD是一个新的构建系统，允许你用纯Java编写构建逻辑。
* [Pro](https://github.com/forax/pro)：Pro是与Java 9模块无缝协作的Java构建工具。
* [Fury](https://github.com/propensive/fury-old)：Fury是下一代构建工具，以解决在不断变化的环境中构建软件的最大挑战，同时保持构建的可预测性、可靠性和简单性。
* [Saker.build](https://github.com/sakerbuild/saker.build)：Saker.build是一个与语言无关的构建系统，专注于可扩展性和可扩展的增量构建。

## 包管理器

* [Nuts](https://github.com/thevpc/nuts)：Nuts是一个Java包管理器，可帮助以简单直接的方式发现、下载、组装和执行本地和远程工件(包)。
* [Nix](https://github.com/fzakaria/mvn2nix)：Nix包管理器用于轻松打包Maven Java应用程序。
* [JPM4j](https://github.com/jpm4j)：JPM是Java包管理器，可以在JPM的帮助下轻松安装应用程序和库。

## CI/CD

* [Jenkins](https://github.com/jenkinsci/jenkins)：Jenkins是领先的开源自动化服务器，使用Java构建，提供超过2000个插件来支持几乎所有事情的自动化。
* [TeamCity](https://www.jetbrains.com/teamcity/)：TeamCity是一个通用CI/CD软件平台，可实现灵活的工作流程、协作和开发实践，这是JetBrains的商业产品。
* [Bamboo](https://www.atlassian.com/software/bamboo)：Bamboo是一款持续集成构建服务器软件，Atlassian提供的商业软件，也有免费版本。
* [GoCD](https://github.com/gocd/gocd)：GoCD可帮助你自动化和简化构建-测试-发布周期，从而无忧、持续地交付产品，由ThoughtWork开源。
* [OneDev](https://github.com/theonedev/onedev)：具有CI/CD、看板的自托管Git服务器。
* [FlowCI](https://github.com/FlowCI/flow-core-x)：FlowCI是一个开源CI/CD自动化服务器，旨在以最简单、最快、最轻松的方式建立自托管CI/CD服务。
* [蓝鲸持续集成平台](https://github.com/TencentBlueKing/bk-ci)：BlueKing是一个免费并开源的CI服务，可助你自动化构建-测试-发布工作流，持续、快速、高质量地交付你的产品，由腾讯开源。
* [Hudson](https://github.com/hudson/hudson-2.x)：持续集成服务器，Jenkins的前身。
* [Apache Continuum](https://continuum.apache.org/)：Apache Continuum是一款企业级持续集成服务器，具有自动构建、发布管理、基于角色的安全性以及与流行构建工具和源代码控制管理系统的集成等功能。
* [Harness CD Community Edition](https://github.com/harness/harness-core)：Harness CD是一种现代自助式持续交付解决方案，允许开发人员在他们选择的任何公共或私有云基础设施上部署、验证和自动回滚Kubernetes和其他云原生应用程序。
* [Bob](https://github.com/bob-cd/bob)：Bob允许你构建自己的自定义CI/CD基础设施，从而允许你将Bob用于各种不同的目的。
* [CruiseControl](https://cruisecontrol.sourceforge.net/)：CruiseControl既是一个持续集成工具，也是一个用于创建自定义持续构建流程的可扩展框架。
* [Blazar](https://github.com/HubSpot/Blazar-Archive)：Blazar是一种持续集成工具，旨在与GitHub和Singularity集成，由HubSpot开源。

## 发布工具

* [JitPack](https://github.com/jitpack/jitpack.io)：JitPack是一个新颖的JVM和Android项目包仓库，它按需构建Git项目并为你提供即用型工件(jar、aar)。
* [Sonatype Nexus](https://github.com/sonatype/nexus-public)：支持代理和缓存功能的二进制管理工具。
* [Bintray](https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/)：发布二进制文件版本控制工具，可以与Maven或Gradle一起配合使用，提供开源免费版本和几种商业收费版本。
* [Indy](https://github.com/Commonjava/indy)：Indy是一个简单的仓库管理器，适用于Apache Maven和其他使用Maven仓库格式的构建工具。
* [Maven Central](https://central.sonatype.com/)：最大的二进制组件仓库，面向开源社区提供免费服务。
* [Cloudsmith](https://cloudsmith.io/)：完全托管的包管理SaaS，支持Maven/Gradle/SBT，并提供免费套餐。
* [Apache Archiva](https://github.com/apache/archiva)：可扩展的仓库管理软件，可帮助管理你自己的个人或企业范围的构建工件仓库。
* [Apache Rat](https://github.com/apache/creadur-rat)：Rat是一个在检查发布时提高准确性和效率的工具。
* [Strongbox](https://github.com/strongbox/strongbox)：Strongbox是一个现代OSS工件仓库管理器。
* [Reposilite](https://github.com/dzikoysk/reposilite)：轻量级且易于使用的存储库管理器，用于JVM生态系统中基于Maven的工件。
* [CloudRepo](https://cloudrepo.io/)：基于云的私有和公共、Maven和PyPi仓库，对于开源项目免费。
* [Cloudsmith](https://cloudsmith.io/user/login/)：适用于Java/Maven、RedHat、Debian、Python、Ruby、Vagrant等的简单、安全且集中的仓库服务，免费开源。
* [PackageCloud](https://packagecloud.io/users/new?plan=free_usage_plan)：易于使用的Maven、RPM、DEB、PyPi、NPM和RubyGem包的仓库托管。
* [Repsy](https://repsy.io/)：1GB免费的私有/公共Maven仓库。
* [Gemfury](https://gemfury.com/)：Maven、PyPi、NPM、Go Module、Nuget、APT和RPM仓库的私有和公共工件仓库，免费用于公共项目。

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
* [AWS Corretto](https://github.com/corretto/corretto-8)：Amazon Corretto是OpenJDK的免费、多平台、生产就绪发行版。
* [Eclipse Temurin](https://github.com/adoptium/temurin-build)：Eclipse基金会下的JDK版本。
* [Bellsoft Liberica](https://github.com/bell-sw/Liberica)：BellSoft开源的JDK版本。
* [GraalVM](https://github.com/oracle/graal)：Oracle开源的一个高性能JDK发行版，旨在加速用Java和其他JVM语言编写的应用程序的执行，并支持JavaScript、Ruby、Python和许多其他流行语言。
* [Mandrel](https://github.com/graalvm/mandrel)：Mandrel是GraalVM社区版的下游发行版，由Redhat提供，Mandrel的主要目标是提供专门支持Quarkus的原生镜像版本。
* [Microsoft JDK](https://github.com/microsoft/openjdk)：微软开源的JDK构建版本。
* [Azul Zulu](https://www.azul.com/zh-hans/core/)：Azul开源的JDK版本。
* [IBM Semeru](https://www.ibm.com/support/pages/java-sdk-downloads)：IBM开源的JDK版本。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化，由IBM开发。
* [Redhat JDK](https://developers.redhat.com/products/openjdk/download)：Redhat开源的JDK版本。
* [JetBrains JDK](https://github.com/JetBrains/JetBrainsRuntime)：JetBrains开发的基于OpenJDK的运行时环境。
* [OpenLogic](https://www.openlogic.com/openjdk-downloads)：Openlogic开源的JDK版本。
* [VMS Software OpenJDK](https://vmssoftware.com/products/openjdk/)：VMS软件公司的OpenJDK免费开源实现。
* [SapMachine](https://github.com/SAP/SapMachine)：由SAP维护和支持的OpenJDK版本。
* [Trava OpenJDK](https://github.com/TravaOpenJDK/trava-jdk-11-dcevm)：Trava OpenJDK是面向开发人员的OpenJDK，它基于dcevm并使用集成的HotswapAgent，因此允许通过方法和字段添加或在运行时更新来高级热交换类。
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
* [Virgil](https://github.com/titzer/virgil)：Virgil是一种编程语言，旨在构建轻量级高性能系统，由卡内基梅隆大学开源。
* [Processing](https://github.com/processing/processing)：Processing是一本灵活的软件速写本，也是一种用于学习编码的语言。
* [Eclipse Golo](https://github.com/eclipse-archived/golo-lang)：Golo是一种用于JVM的简单动态弱类型语言，由法国CITI实验室开源。
* [Rascal](https://github.com/usethesource/rascal)：Rascal是一个开源、基于Java的元编程库，由荷兰阿姆斯特丹自由大学的UseTheSource团队开发。
* [JPHP](https://github.com/jphp-group/jphp)：JPHP是使用JVM的PHP的新实现，支持PHP语言(7.1+)的许多功能。
* [JGO](https://github.com/thomasmodeneis/jgo)：Golang的Java编译器和运行时环境。
* [LuaJ](https://github.com/luaj/luaj)：为JME和JSE编写的轻量级、快速、以Java为中心的Lua解释器。
* [Enkel](https://github.com/JakubDziworski/Enkel-JVM-language)：Enkel是一种运行在JVM上的简单编程语言。
* [Yeti](https://github.com/mth/yeti)：Yeti是ML风格的函数式编程语言，在JVM上运行。
* [Genesis](https://github.com/elonlit/Genesis)：Genesis是一种解释性、过程性和图灵完备的古希伯来编程语言。
* [Concurnas](https://github.com/Concurnas/Concurnas)：Concurnas是一种开源JVM编程语言，旨在构建可靠、可扩展、高性能的并发、分布式和并行系统。
* [Ioke](https://github.com/olabini/ioke)：Ioke是一种强类型、动态、基于原型的编程语言。
* [Fantom](https://github.com/fantom-lang/fantom)：Fantom是一种在JVM和现代Web浏览器上运行的可移植语言。
* [Eclipse Ceylon](https://github.com/eclipse-archived/ceylon)：Ceylon是一种用于Java和JavaScript虚拟机的现代、模块化、静态类型编程语言，由Red Hat创建。
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
* [Eclipse Epsilon](https://github.com/eclipse/epsilon)：Epsilon是一系列基于Java的脚本语言，用于自动执行常见的基于模型的软件工程任务，例如代码生成、模型到模型转换和模型验证。
* [BoxLang](https://github.com/ortus-boxlang/BoxLang)：BoxLang是一种现代动态JVM语言，可以部署在多个运行时上。
* [Swift/T](https://github.com/swift-lang/swift-t)：Swift/T是一种隐式并行编程语言，用于将外部函数和命令行可执行文件组合成大规模并行应用程序，由芝加哥大学开源。

## JVM实现

* [DCEVM](https://github.com/dcevm/dcevm)：Java 7/8的动态代码演化VM。
* [LeJOS](https://lejos.sourceforge.io/)：乐高开发的JVM，基于leJOS开发的机器人曾经在国际空间站上运行。
* [Jikes RVM](https://github.com/JikesRVM/JikesRVM)：一个由Java开发的虚拟机，曾经为虚拟机技术前沿研究超过180篇出版物和36篇论文。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化，由IBM开发。
* [Avian](https://github.com/ReadyTalk/avian)：Avian是一个轻量级虚拟机和类库，旨在提供有用的Java功能子集，适合构建独立的应用程序。
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm)：用于iOS原生开发的开源Java字节码到C转换器，设计为CodenameOne WORA移动项目的一部分。
* [RoboVM](https://github.com/MobiVM/robovm)：针对iOS、Mac OSX和Linux的JVM字节码AOT编译器。
* [Maxine VM](https://github.com/beehive-lab/Maxine-VM)：Java中的元循环虚拟机，由曼彻斯特大学高级处理器技术小组开发。
* [Rembulan](https://github.com/mjanicek/rembulan)：Java虚拟机的Lua 5.3实现。
* [JOE](https://github.com/joekoolade/JOE)：JOE是一个软件虚拟化工具，它通过用Java语言编写操作系统和硬件子系统，将操作系统合并到程序中。
* [Node JVM](https://github.com/YaroslavGaponov/node-jvm)：纯Node.js中的Java虚拟机。
* [Metascala](https://github.com/lihaoyi/Metascala)：Metascala是一个用Scala编程语言编写的小型元循环Java虚拟机。
* [Archimedes JVM](https://github.com/archimedes-projects/archimedes-jvm)：阿基米德对JVM的实现。
* [JamVM](https://jamvm.sourceforge.net/)：JamVM是一个开源Java虚拟机，旨在支持最新版本的JVM规范，同时又紧凑且易于理解。
* [Mika VM](https://github.com/kifferltd/open-mika)：Mika VM是JVM规范的开源实现，以及实现Java ME连接设备配置的类库。
* [SableVM](http://sablevm.org/)：SableVM是一个健壮、极其便携、高效且符合规范的Java虚拟机，旨在易于维护和扩展，由麦吉尔大学开源。
* [TakaTuka](https://sourceforge.net/projects/takatuka/)：TakaTuka是一款开源、高度可移植的JVM，适用于微型嵌入式设备和无线传感器网络，由弗莱堡大学开源。
* [JamaicaVM](https://www.aicas.com/wp/products-services/jamaicavm/)：JamaicaVM是一个基于Java的嵌入式系统软件开发套件和运行时，它使智能设备和车辆成为可能，由aicas公司开发。
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

## IDE

* [IntelliJ IDEA](https://github.com/JetBrains/intellij-community)：IntelliJ IDEA是领先的Java和Kotlin IDE，由JetBrains开发。
* [Eclipse](https://github.com/eclipse-platform)：Eclipse是一个开源、基于Java的可扩展开发平台，由IBM开发。
* [Visual Studio Code](https://code.visualstudio.com)：Visual Studio Code是一个轻量级但功能强大的源代码编辑器，也支持作为IDE开发Java。
* [Android Studio](https://developer.android.com/studio)：Android Studio是用于开发Android应用的Google官方IDE，基于Intellij引擎。
* [Apache NetBeans](https://github.com/apache/netbeans)：Apache NetBeans是一个开源开发环境、工具平台和应用程序框架，最初由Oracle开发。
* [JetBrains Fleet](https://www.jetbrains.com/fleet)：Fleet是JetBrains公司推出的一款下一代集成开发环境，使用Kotlin开发。
* [MyEclipse](https://www.genuitec.com/products/myeclipse)：MyEclipse是一个基于Eclipse平台构建的专有Java IDE。
* [Spring Tools](https://github.com/spring-projects/sts4)：Spring官方出品的基于Eclipse的Java IDE。
* [JDeveloper](https://www.oracle.com/application-development/technologies/jdeveloper.html)：Oracle开发的Java IDE。
* [Eclipse Open VSX](https://github.com/eclipse/openvsx)：Open VSX是Visual Studio Marketplace的供应商中立开源替代品，它提供了一个在数据库中管理VS Code扩展的服务器应用程序、一个类似于VS Code Marketplace的Web应用程序以及一个类似于vsce的用于发布扩展的命令行工具。
* [HBuilder](https://www.dcloud.io/)：DCloud推出的一款支持HTML5的Web开发IDE，本身由Java编写。
* [BlueJ](https://github.com/k-pet-group/BlueJ-Greenfoot)：专为初学者设计的免费Java开发环境。
* [JBuilder](https://borland-jbuilder.software.informer.com/)：Borland软件公司出品的Java集成编程环境，有不同功能程度的多个版本。
* [Consulo](https://github.com/consulo/consulo)：Consulo是一个多语言IDE，基于Intellij引擎。
* [RapidClipse](https://rapidclipse.com/)：RapidClipse是一个免费的Eclipse发行版，用于使用Java进行快速跨平台开发。
* [Greenfoot](https://www.greenfoot.org/home)：免费的Java集成开发环境。
* [DrJava](http://www.drjava.org/)：一个简单、轻量级、交互式Java IDE，由莱斯大学开源。
* [Codenvy](https://github.com/codenvy/codenvy)：一个云IDE引擎，为开发者提供了一种方法让其能够开发、测试、运行工具插件和应用程序。
* [RStudio](https://github.com/rstudio/rstudio)：RStudio是R编程语言的集成开发环境。
* [Aptana Studio 3](https://github.com/aptana/studio3)：Aptana Studio 3是一个开源Web开发IDE。
* [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE)：AndroidIDE是一款适用于Android的IDE，用于开发功能齐全的Android应用程序。
* [Cosmic IDE](https://github.com/Cosmic-Ide/Cosmic-IDE)：Cosmic IDE是一款功能丰富的IDE，适用于Android上的JVM开发。
* [SnapCode](https://github.com/reportmill/SnapCode)：在浏览器中运行的现代Java IDE，用于教育目的。
* [JCreator](https://jcreator.en.softonic.com/)：JCreator是另一个简单的Java IDE，非常适合想要学习Java的初学者。
* [PraxisLIVE](https://github.com/praxis-live/praxis-live)：PraxisLIVE是一种混合视觉实时编程IDE。
* [JDoodle](https://www.jdoodle.com/)：JDoodle是一款在线Java编译器IDE，它能够让你在浏览器中编写、运行和调试Java代码，无需在本地安装任何开发环境。
* [jGRASP](https://www.jgrasp.org/)：jGRASP是一个轻量级开发环境，专门用于提供软件可视化的自动生成，以提高软件的可理解性。
* [Online Java](https://www.online-java.com)：Online Java是一个基于Web的工具，它是快速、健壮、强大的Java语言在线编译器之一。
* [Java ADT](https://gitee.com/feisuanyz/java)：Java自动化开发工具。

## 项目管理

* [JIRA](https://www.atlassian.com/software/jira)：JIRA是一个Bug跟踪管理系统，为针对Bug管理、任务追踪和项目管理的商业性应用软件，由Atlassian开发。
* [MyCollab](https://github.com/MyCollab/mycollab)：MyCollab是免费的开源项目管理软件。
* [Teambition](https://www.teambition.com/)：阿里旗下数字化协作平台，提供项目管理、任务协同等解决方案。
* [GanttProject](https://github.com/bardsoftware/ganttproject)：GanttProject是一款免费的桌面项目管理应用程序。
* [Atlassian Confluence](https://www.atlassian.com/zh/software)：Confluence是一个专业的企业知识管理与协同软件，也可以用于构建企业Wiki，由澳洲软件公司Atlassian所开发。
* [Mone](https://github.com/XiaoMi/mone)：Mone是一个以微服务为核心的一站式企业协同研发平台，支持公有云、私有云、混合云等多种部署形态，由小米开源。
* [Lavagna](https://github.com/digitalfondue/lavagna)：Lavagna是一款小型且易于使用的问题/项目跟踪软件。
* [Yobi](https://github.com/yona-projects/yona)：Yobi是一个基于Web的项目托管软件，由Naver开源。
* [Gerrit](https://github.com/GerritCodeReview/gerrit)：Gerrit是基于Git的项目的代码审查和项目管理工具，由Google开源。
* [Kooteam](https://gitee.com/sinbo/kooteam)：Kooteam是一款轻量级的在线团队协作工具，提供各类文档工具、在线思维导图、在线流程图、项目管理、任务分发，知识库管理等工具。
* [BugCatcher](https://github.com/youzan/bugCatcher)：方便产品、开发、测试三方协同管理、测试、监控项目进度和质量，以持续交付，由有赞开源。
* [LibrePlan](https://github.com/LibrePlan/libreplan)：LibrePlan是一款用于项目管理、监控和控制的免费软件Web应用程序。
* [Apache Yetus](https://github.com/apache/yetus)：Apache Yetus是一个库和工具的集合，支持软件项目的贡献和发布过程。
* [ProjectForge](https://github.com/micromata/projectforge)：ProjectForge是一个基于Web的项目管理解决方案，包括时间跟踪、团队日历、甘特图、财务管理、问题管理、控制和管理工作分解结构(例如与JIRA一起作为问题管理系统)。
* [Naikan](https://github.com/enofex/naikan)：Naikan是一款开源软件库存管理工具，适用于由CI/CD管道驱动的开发团队。
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

* [Spring Cloud Kubernetes](https://github.com/spring-cloud/spring-cloud-kubernetes)：Spring Cloud Kubernetes提供了消费Kubernetes原生服务的Spring Cloud通用接口实现。
* [Buildpacks](https://buildpacks.io)：Buildpacks可以将应用程序源代码转换为可以在任何云上运行的镜像。
* [LINSTOR](https://github.com/LINBIT/linstor-server)：LINSTOR由LINBIT开发，是一款开源软件，用于管理一组计算机上的复制卷。
* [Mendmix](https://gitee.com/dromara/mendmix-cloud)：Mendmix是一站式分布式开发架构开源解决方案及云原生架构技术底座，由dromara社区开源。
* [DataSophon](https://github.com/datavane/datasophon)：DataSophon是新一代云原生大数据管家，致力于帮助用户快速构建起稳定、高效、可弹性伸缩的大数据云原生平台。
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
* [Linkerd](https://github.com/linkerd/linkerd)：Linkerd充当透明的HTTP/gRPC/thrift/etc代理，通常可以通过最少的配置放入现有应用程序中，无论它们是用什么语言编写的。
* [OpenTOSCA Container](https://github.com/OpenTOSCA/container)：OpenTOSCA Container是基于Java/Maven的运行时，用于部署和管理基于TOSCA的应用程序。
* [Theodolite](https://github.com/cau-se/theodolite)：Theodolite是一个用于对Kubernetes中云原生应用程序的水平和垂直可扩展性进行基准测试的框架，由基尔大学开源。

## 云计算

* [Apache CloudStack](https://github.com/apache/cloudstack)：Apache CloudStack是一款开源软件，旨在部署和管理大型虚拟机网络，是一种高可用性、高可扩展性的IaaS云计算平台，由Citrix开源。
* [CloudSim](https://github.com/Cloudslab/cloudsim)：CloudSim是一个云计算基础设施和服务的建模和仿真框架，由墨尔本大学开源。
* [iFogSim2](https://github.com/Cloudslab/iFogSim)：用于物联网、边缘和雾计算环境中资源管理技术建模和仿真的工具包，由墨尔本大学开源。
* [PureEdgeSim](https://github.com/CharafeddineMechalikh/PureEdgeSim)：PureEdgeSim是用于云、边缘和雾计算环境性能评估的仿真框架。
* [CloudSimPlus](https://github.com/cloudsimplus/cloudsimplus)：CloudSim Plus是一个现代、最新、功能齐全且文档齐全的Java 17模拟框架，它易于使用和扩展，支持对云计算基础设施和应用服务进行建模、模拟和实验。
* [DLSF](https://github.com/Cloudslab/DLSF)：用于随机雾云计算环境的基于深度学习的调度程序，由墨尔本大学开源。

## Serverless

* [Apache EventMesh](https://github.com/apache/eventmesh)：Apache EventMesh是新一代Serverless事件中间件，用于构建分布式事件驱动应用程序，由微众银行开源。
* [Kotless](https://github.com/JetBrains/kotless)：Kotlin Serverless框架，由JetBrains开源。
* [Powertools Lambda Java](https://github.com/aws-powertools/powertools-lambda-java)：Powertools是一个开发工具包，用于实现Serverless最佳实践并提高开发人员速度。
* [SOFAServerless](https://github.com/sofastack/sofa-serverless)：SOFAServerless是一种模块化的应用架构模式，能够帮助大中小企业低成本地实现极速研发、运维、微服务演进和人员协作，从而为企业实现降本增效，由蚂蚁开源。
* [Serverless Java Container](https://github.com/awslabs/aws-serverless-java-container)：Serverless Java Container让你可以在AWS Lambda中轻松运行使用Spring、Spring Boot、Apache Struts、Jersey或Spark等框架编写的Java应用程序。
* [Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function)：基于Spring Boot的函数计算框架。
* [Apache OpenWhisk](https://github.com/apache/openwhisk)：OpenWhisk是一个用于构建云应用程序的Serverless函数平台，由IBM开源。
* [Pulumi AWS](https://github.com/pulumi/pulumi-aws)：Pulumi的AWS资源提供商允许你在云程序中使用AWS资源。
* [Open Runtimes](https://github.com/open-runtimes/open-runtimes)：适用于多种编程语言的Serverless云计算运行时环境，旨在为在容器化系统中编写云函数创建一致且可预测的开放标准。
* [Flink Stateful Functions](https://github.com/apache/flink-statefun)：Stateful Functions是一个API，它通过为Serverless架构构建的运行时来简化分布式有状态应用程序的构建。
* [Funktion](https://github.com/funktionio/funktion-connectors)：Funktion是一个基于Kubernetes的开源事件驱动的Lambda风格编程模型。
* [Cloudstate](https://github.com/cloudstateio/cloudstate)：Cloudstate是一个开源协议和参考实现，探索有状态无服务器的想法，最初由Lightbend开发。
* [Functions Framework Java](https://github.com/GoogleCloudPlatform/functions-framework-java)：用于编写可移植Java函数的开源FaaS框架，由Google Cloud Functions团队提供。
* [SwimOS](https://github.com/swimos/swim)：SwimOS是一个全栈应用程序平台，用于构建有状态的Web服务、流API和实时UI。
* [Koupleless](https://github.com/koupleless/koupleless)：Koupleless是一种模块化的Serverless技术解决方案，它能让普通应用以比较低的代价演进为Serverless研发模式。
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

## Docker客户端

* [Docker Java](https://github.com/docker-java/docker-java)：Java Docker官方客户端。
* [Spotify Docker Client](https://github.com/spotify/docker-client)：这是一个用Java编写的Docker客户端，之前被用于Spotify的许多关键生产系统。
* [Docker Java API](https://github.com/amihaiemil/docker-java-api)：另一个轻量级的Docker客户端库。
* [Docker Client](https://github.com/gesellix/docker-client)：用Groovy编写的JVM的Docker HTTP客户端。

## DevOps

* [CacheCloud](https://github.com/sohutv/cachecloud)：CacheCloud是一个Redis云管理平台，支持Redis多种架构高效管理、有效降低大规模Redis运维成本，提升资源管控能力和利用率，由搜狐开源。
* [DHorse](https://github.com/512team/dhorse)：DHorse是一个轻量级、简单易用的云应用管理平台，具有多云和多环境管理、应用管理和部署、服务治理等功能。
* [MQCloud](https://github.com/sohutv/mqcloud)：RocketMQ企业级一站式服务平台，由搜狐开源。
* [EazyBuilder](https://github.com/iSoftStoneGroup/EazyBuilder)：EazyBuilder是一套完整的云原生架构下的DevOps平台项目，由软通动力开源。
* [OpsCloud4](https://github.com/ixrjog/opscloud4)：OpsCloud4是用于云上运维的工具，提供持续交付、多实例动态数据源、堡垒机等功能。
* [SREWorks](https://github.com/alibaba/SREWorks)：SREWorks专注于以应用为中心的开发模式，提供一站式云原生数智化运维SaaS管理套件，由阿里开源。
* [WGCLOUD](https://github.com/tianshiyeben/wgcloud)：WGCLOUD式Linux运维监控工具，支持系统硬件信息、内存、CPU、温度、磁盘空间及IO、硬盘smart、系统负载、网络流量等监控。
* [MoSKito](https://github.com/anotheria/moskito)：MoSKito是一个开源系统，用于监控Java Web应用程序的性能和行为。
* [Choerodon](https://gitee.com/choerodon/choerodon)：Choerodon数智化开发管理平台，提供体系化方法论和协作、测试、DevOps及容器工具，由甄知科技开源。
* [Dubbo Admin](https://github.com/apache/dubbo-admin)：Dubbo Admin是为了更好地可视化Dubbo服务而设计的控制台，它提供对Dubbo 3的支持，并兼容2.7.x、2.6.x和2.5.x。
* [CloudExplorer Lite](https://github.com/CloudExplorer-Dev/CloudExplorer-Lite)：CloudExplorer Lite脱胎于飞致云创始软件产品CloudExplorer多云管理平台，支持对接纳管主流的公有云和私有云基础设施，提供开箱即用的云主机管理、云账单、运营分析和安全合规等基本功能。
* [Ward](https://github.com/Rudolf-Barbu/Ward)：Ward是一个简单简约的服务器监控工具，支持自适应设计系统。
* [Kardio](https://github.com/tmobile/kardio)：Kardio是一个简单的工具，可以配置为在任何端点上执行运行状况检查，由T-Mobile开源。
* [Pallet](https://github.com/pallet/pallet)：Pallet用于在云和虚拟机基础设施上配置和维护服务器，旨在解决跨各种云提供一致配置的运行镜像的问题。
* [Orion Visor](https://gitee.com/dromara/orion-visor)：Orion Visor是一款高颜值、现代化的智能运维&轻量堡垒机平台，由dromara社区开源。
* [Rundeck](https://github.com/rundeck/rundeck)：Rundeck是一种开源自动化服务，具有Web控制台、命令行工具和Web API，它使你可以轻松地跨一组节点运行自动化任务。
* [Uyuni](https://github.com/uyuni-project/uyuni)：Uyuni是一个开源系统管理解决方案，源自Spacewalk。
* [WeCube](https://github.com/WeBankPartners/wecube-platform)：WeCube是一套开源、一站式IT架构管理和运维管理工具，主要用于简化分布式架构IT管理，并可以通过插件进行功能扩展，由微众开源。
* [MSEC](https://github.com/Tencent/MSEC)：MSEC由腾讯QQ团队开源，它是一个后端Devops引擎，包括RPC、名称查找、负载均衡、监控、发布和容量管理。
* [Mantis](https://github.com/Netflix/mantis)：Mantis使开发人员可以轻松构建实时、经济高效、以运营为中心的应用程序，Netflix开源。
* [Phoenix](https://gitee.com/monitoring-platform/phoenix)：Phoenix是一个灵活可配置的开源监控平台，主要用于监控应用程序、服务器、Docker、数据库、网络、TCP端口和HTTP接口。
* [KnowSearch](https://github.com/didi/KnowSearch)：KnowSearch是面向Elasticsearch研发与运维人员，围绕集群、索引构建的零侵入、多租户的Elasticsearch GUI管控平台，由滴滴开源。
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

## 云服务

* [Nomulus](https://github.com/google/nomulus)：Nomulus是一种开源、可扩展、基于云的服务，用于运营顶级域名(TLD)，由Google开源。
* [ZStack](https://github.com/zstackio/zstack)：ZStack是开源IaaS软件，旨在实现数据中心自动化，通过API管理计算、存储和网络资源，由云轴科技开源。
* [Gaia](https://github.com/gaia-app/gaia)：Gaia是一个用于Terraform模块和自助服务基础设施的Terraform UI。
* [AWS SaaS Boost](https://github.com/awslabs/aws-saas-boost)：AWS SaaS Boost为组织提供即用型核心软件元素，以便在云中成功运行SaaS工作负载，由Amazon开源。
* [Wemirr Platform](https://gitee.com/battcn/wemirr-platform)：优秀、简单、漂亮的开源SaaS、多租户云平台架构。
* [HZERO](https://gitee.com/open-hand/hzero)：HZERO是基于微服务架构开源免费的企业级PaaS平台，由上海汉得公司开发。
* [J2PaaS](https://gitee.com/j2paas/j2paas-framework)：J2PaaS是一个集成开发平台，以参数驱动为核心，为开发者提供可视化、组件化、低代码、拖拽式在线敏捷开发平台，由吉鼎科技开源。
* [Apache Stratos](https://github.com/apache/stratos)：Apache Stratos包括多语言和环境支持，以及在多个IaaS运行时上运行的能力。
* [Myria](https://github.com/uwescience/myria)：Myria是华盛顿大学的分布式、无共享大数据管理系统和云服务。
* [Eclipse Jemo](https://github.com/eclipse/jemo)：Jemo旨在为基于JVM的语言提供真正的多云FaaS实现。
* [Eclipse Dirigible](https://github.com/eclipse/dirigible)：Eclipse Dirigible是一种高生产力PaaS，它提供了一个由预选执行引擎和内置Web开发工具组成的应用程序服务器，它也适合利用低代码/无代码技术来快速开发业务应用程序，由SAP开源。
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

* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为(吴晟)开源。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为美团点评提供了全面的实时监控告警服务。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Matrix](https://github.com/Tencent/matrix)：Matrix是腾讯微信中使用的APM，用于监控、定位和分析性能问题。
* [SkyEye](https://github.com/JThink/SkyEye)：SkyEye是对Java、Scala等运行于JVM的程序进行实时日志采集、索引和可视化，对系统进行进程级别的监控的工具。
* [Hertzbeat](https://github.com/dromara/hertzbeat)：HertzBeat是一个开源的实时监控系统，具有自定义监控、高性能集群、Prometheus兼容和无代理功能，由dromara社区开源。
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM)：ArgusAPM是360开源的线上移动性能检测平台。
* [Hypertrace](https://github.com/hypertrace/hypertrace)：Hypertrace是一个基于云原生分布式跟踪的可观测性平台，可让你了解开发和生产分布式系统，由Traceable开发。
* [Scouter](https://github.com/scouter-project/scouter)：SCOUTER是一个开源APM，类似于New Relic和AppDynamics。
* [MyPerf4J](https://github.com/LinShunKang/MyPerf4J)：MyPerf4J是一个针对高并发、低延迟应用设计的高性能Java性能监控和统计工具。
* [Elastic APM](https://github.com/elastic/apm-agent-java)：Elastic APM Java代理。
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor)：Stagemonitor是用于Java服务器应用程序性能监控的开源解决方案。
* [New Relic Java](https://github.com/newrelic/newrelic-java-agent)：New Relic Java代理。
* [Glowroot](https://github.com/glowroot/glowroot)：Glowroot是一个易于使用，开销极低的Java APM。
* [Fiery](https://github.com/weiboad/fiery)：Fiery是用于PHP的APM工具，由微博开源。
* [OzHera](https://github.com/XiaoMi/ozhera)：OzHera是云原生时代的应用可观察平台，由小米中国区研发效率团队开源。
* [EasyAgent](https://github.com/megaease/easeagent)：面向云原生和APM系统的轻量级开源Java Agent，MegaEase开源。
* [inspectIT](https://github.com/inspectIT/inspectIT)：ispectIT是领先的开源APM工具，用于监视和分析Java(EE)软件应用程序。
* [XXL-APM](https://github.com/xuxueli/xxl-apm)：分布式APM平台，XXL社区开源。
* [Lightrun](https://lightrun.com/)：Lightrun是一个面向开发人员的可观察性工具。
* [BeeAPM](https://github.com/hao117/bee-apm)：BeeAPM是一个分布式跟踪和应用性能监控系统。
* [Digma](https://github.com/digma-ai/digma)：Digma是一个持续反馈平台，使可观察性与开发相关。

## 分布式追踪

* [Apache SkyWalking](https://github.com/apache/skywalking)：SkyWalking是一个开源的APM系统，为云原生架构中的分布式系统提供监控、跟踪和诊断功能，由华为开源(吴晟)。
* [Zipkin](https://github.com/openzipkin/zipkin)：Zipkin是一个分布式追踪系统，由Twitter开源。
* [MTrace](https://tech.meituan.com/2016/10/14/mt-mtrace.html)：美团点评内部的分布式会话跟踪系统，参考了Twitter的Zipkin以及阿里的鹰眼实现。
* [HoloInsight](https://github.com/traas-stack/holoinsight)：HoloInsight是一个云原生可观测平台，重点专注于实时日志分析和人工智能集成，这是蚂蚁集团观测平台AntMonitor的开源版本。
* [Watchman](https://www.infoq.cn/article/weibo-watchman/)：微博平台的链路追踪及服务质量保障系统。
* [EagleEye](https://www.infoq.cn/article/jgzbemozgmbsukewff6j)：鹰眼是Google的分布式调用跟踪系统Dapper在淘宝的Java实现。
* [CallGraph](https://cread.jd.com/read/startRead.action?bookId=30388376&readType=1)：京东的分布式跟踪解决方案。
* [SOFATracer](https://github.com/sofastack/sofa-tracer)：用于分布式系统调用跟踪的组件，由蚂蚁开源。
* [Cat](https://github.com/dianping/cat)：CAT是基于Java开发的实时应用监控平台，为美团点评提供了全面的实时监控告警服务。
* [Brave](https://github.com/openzipkin/brave)：Brave是一个分布式跟踪仪器库。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：Pinpoint是一个用Java编写的大型分布式系统的APM工具，由韩国Naver研发团队开源。
* [Spring Cloud Sleuth](https://github.com/spring-cloud/spring-cloud-sleuth)：Spring Cloud Sleuth为分布式跟踪提供Spring Boot自动配置。
* [ApplicationInsights](https://github.com/microsoft/ApplicationInsights-Java)：Java应用程序洞察工具，由微软开源。
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-java)：OpenTelemetry Java SDK。
* [Wingtips](https://github.com/Nike-Inc/wingtips)：Wingtips是基于谷歌Dapper论文的Java分布式跟踪解决方案，由Nike开源。
* [Micrometer Tracing](https://github.com/micrometer-metrics/tracing)：Micrometer应用程序跟踪门面。
* [Hydra](https://github.com/odenny/hydra)：Hydra是京东开发的分布式跟踪系统。
* [Cicada](https://github.com/Yirendai/cicada)：宜人贷分布式跟踪系统，基于谷歌Dapper论文实现。
* [PerfMark](https://github.com/perfmark/perfmark)：PerfMark是一个低开销、手动检测的Java跟踪库。
* [Logbook](https://github.com/didi/logbook)：Logbook是一款面向ToB业务的服务端埋点方案，由滴滴开源。
* [Kamon](https://github.com/kamon-io/Kamon)：Kamon是一组用于检测在JVM上运行的应用程序的库。

## 指标报告

* [Dropwizard Metrics](https://github.com/dropwizard/metrics)：Metrics提供了一个强大的工具包，其中包含衡量生产环境中关键组件行为的方法。
* [Prometheus Java](https://github.com/prometheus/client_java)：用于JVM应用程序的Prometheus检测库。
* [Servo](https://github.com/Netflix/servo)：Servo提供了一个简单的接口，用于在Java中公开和发布应用程序指标，由Netflix开源。
* [OpenMessaging Java](https://github.com/openmessaging/openmessaging-java)：Java的OpenMessaging运行时接口。
* [Oculus](https://github.com/etsy/oculus)：Oculus是Etsy Kale系统的异常关联组件。
* [Metrics Spring](https://github.com/ryantenney/metrics-spring)：Metrics Spring将Dropwizard Metrics库与Spring集成，并提供XML和Java配置。
* [Spectator](https://github.com/Netflix/spectator)：用于记录维度时间序列的检测代码的简单库，由Netflix开源。
* [Micrometer](https://github.com/micrometer-metrics/micrometer)：Micrometer为最流行的可观察性系统提供了一个门面，允许你在不锁定供应商的情况下检测基于JVM的应用程序代码。
* [Dubbo Metrics](https://github.com/alibaba/metrics)：Metrics是阿里内部广泛使用的度量埋点基础类库。
* [Argus](https://github.com/salesforce/Argus)：Argus是一个时序监控和警报平台，它由离散服务组成，用于配置警报、摄取和转换指标和事件、发送通知、创建命名空间以及建立和实施策略和使用配额，由Salesforce开源。
* [Keycloak Metrics](https://github.com/aerogear/keycloak-metrics-spi)：向Keycloak添加指标端点的SPI，端点返回可供Prometheus抓取的指标数据。
* [SOFALookout](https://github.com/sofastack/sofa-lookout)：SOFALookout是一个利用多维度的Metrics对目标系统进行度量和监控的项目，由蚂蚁开源。
* [Blueflood](https://github.com/rax-maas/blueflood)：Blueflood是一个多租户、分布式度量处理系统，能够大规模地摄取、汇总和提供指标，由Rackspace开源。
* [PerfMon](https://github.com/undera/perfmon-agent)：用于访问远程计算机上的系统指标的代理应用程序。
* [InfluxDB Metrics](https://github.com/davidB/metrics-influxdb)：向InfluxDB服务器公布度量结果的指标报告器。
* [ElasticSearch Metrics](https://github.com/elastic/elasticsearch-metrics-reporter-java)：向ElasticSearch服务器公布度量结果的指标报告器。
* [Hawkular Metrics](https://github.com/hawkular/hawkular-metrics)：Hawkular Metrics是Hawkular社区的度量数据存储引擎部分。
* [Tritium](https://github.com/palantir/tritium)：Tritium是一个用于检测应用程序的库，以在运行时提供更好的可观察性，Palantir开源。
* [Jmxtrans](https://github.com/jmxtrans/jmxtrans-agent)：基于Java代理的JMX指标导出器。

## 注册中心

* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：Apache Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务。
* [Eureka](https://github.com/Netflix/eureka)：Eureka是一项RESTful服务，主要用于AWS云中，用于中间层服务器的发现、负载平衡和故障转移，由Netflix开源。
* [Pantheon](https://github.com/ProgrammerAnthony/Pantheon)：Pantheon是分布式微服务注册中心。
* [SOFARegistry](https://github.com/sofastack/sofa-registry)：SOFARegistry是蚂蚁金服开源的一个生产级、高时效、高可用的服务注册中心。
* [JHipster Registry](https://github.com/jhipster/jhipster-registry)：这是JHipster注册中心服务，基于Spring Cloud Netflix Eureka和Spring Cloud Config。
* [SnoopEE](https://github.com/ivargrimstad/snoop)：SnoopEE是一个基于Java EE的微服务的实验性注册和发现服务。

## 容错组件

* [Sentinel](https://github.com/alibaba/Sentinel)：Sentinel是面向分布式、多语言异构化服务架构的流量治理组件，由阿里开源。
* [Hystrix](https://github.com/Netflix/Hystrix)：Hystrix是一个延迟和容错库，旨在隔离对远程系统、服务和第3方库的访问点，阻止级联故障，并在故障不可避免的复杂分布式系统中实现恢复能力，由Netflix开源。
* [Resilience4j](https://github.com/resilience4j/resilience4j)：Resilience4j是一个专为Java 8和函数式编程设计的容错库。
* [Bucket4j](https://github.com/bucket4j/bucket4j)：Bucket4j是一个Java限速库，主要基于令牌桶算法。
* [Failsafe](https://github.com/failsafe-lib/failsafe)：Failsafe是一个轻量级、零依赖库，用于处理Java 8+中的故障，具有用于处理日常用例的简洁API和处理其他所有内容的灵活性。
* [RateLimiter4j](https://github.com/wangzheng0822/ratelimiter4j)：RateLimiter是一个高度容错、低延迟、高性能的限流开发库/框架，提供了对HTTP接口的访问限流功能。
* [Concurrency Limits](https://github.com/Netflix/concurrency-limits)：实现并集成了从TCP拥塞控制到自动检测服务并发限制概念的Java库，可以以最佳延迟实现最佳吞吐量，由Netflix开源。
* [RateLimitJ](https://github.com/mokies/ratelimitj)：用于速率限制的Java库，提供可扩展的存储和应用程序框架适配器，该项目不再活跃。
* [SDS](https://github.com/didi/sds)：SDS是一个基于Java开发的简单、易用、高性能的服务降级系统，支持限流、熔断和降级等功能，由滴滴开源。
* [Fastbreak](https://github.com/Nike-Inc/fastbreak)：Fastbreak是一个简单的Java 8原生断路器，支持异步Future、阻塞和回调/手动模式，由Nike开源。
* [Token-Bucket](https://github.com/bbeck/token-bucket)：该库提供了令牌桶算法的实现。
* [Neural](https://gitee.com/yu120/neural)：Neural是微服务架构中高并发和高可用的神经组织利刃，提供了分布式限流、降级、熔断、重试和隔离的容错特性。
* [Discovery](https://github.com/Nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移。
* [SnowJena](https://github.com/onblog/SnowJena)：基于令牌桶算法实现的分布式无锁限流框架，支持动态配置规则，支持可视化监控，开箱即用。
* [BFT-SMaRt](https://github.com/bft-smart/library)：BFT-SMaRt是一个用Java开发的高性能拜占庭容错状态机复制库，以简单性和健壮性为首要要求，由里斯本大学开源。
* [Easy Retry](https://github.com/alibaba/easy-retry)：Easy Retry是一种存储介质可扩展的持久化重试方案，由阿里开源。
* [MicroProfile Fault Tolerance](https://github.com/eclipse/microprofile-fault-tolerance)：MicroProfile中提供的容错组件。
* [Spring Retry](https://github.com/spring-projects/spring-retry)：Spring Retry提供了自动重新调用失败操作的能力。
* [Guava Retry](https://github.com/rholder/guava-retrying)：Guava Retry模块提供了一种通用方法，用于重试任意Java代码，具有特定的停止、重试和异常处理功能。
* [Async Retry](https://github.com/nurkiewicz/async-retry)：用于Java 7/8的异步重试库。
* [Retry4j](https://github.com/elennick/retry4j)：Retry4j是一个简单的Java库，可帮助重试瞬时故障情况或不可靠的代码。
* [Sisyphus](https://github.com/houbb/sisyphus)：Sisyphus是支持过程式编程和注解编程的Java重试框架。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [Vert.x Circuit Breaker](https://github.com/vert-x3/vertx-circuit-breaker)：Vert.x的断路器模式实现。
* [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker)：Dropwizard的断路器库。
* [Retrieval](https://gitee.com/spjich/retrieval)：Retrieval是一个精简的Java重试组件，支持同步，异步，以及制定时间内重试。
* [Ribbon](https://github.com/Netflix/ribbon)：Ribbon是一个进程间通信库，具有内置的软件负载均衡器，由Netflix开源。
* [SmallRye Stork](https://github.com/smallrye/smallrye-stork)：SmallRye Stork是一个服务发现和客户端负载均衡框架。
* [Neutrino](https://github.com/eBay/Neutrino)：Neutrino是基于Scala的软件负载均衡器，由eBay开发。
* [Appactive](https://github.com/alibaba/Appactive)：Appactive是阿里开源的一款标准、通用且功能强大，致力于构建应用多活架构的开源中间件。
* [Simple Failover](https://github.com/PhantomThief/simple-failover-java)：Simple Failover是一个简单的Java故障转移库。
* [Akali](https://gitee.com/dromara/Akali)：Akali是一个轻量级本地化热点检测/降级框架，适用于大流量场景，可轻松解决业务中超高流量的并发查询等场景，由dromara社区开源。
* [Baragon](https://github.com/HubSpot/Baragon)：Baragon是一个用于自动更新负载均衡器配置的系统，由HubSpot开源。
* [Sarge](https://github.com/jhalterman/sarge)：Sarge创建受监督的对象，这些对象通过执行重试、状态重置和故障升级来自动处理发生故障时的情况，从而轻松实现简单而强大的容错能力。

## 混沌工程

* [Mangle](https://github.com/vmware/mangle)：Mangle使你能够针对应用程序和基础设施组件无缝运行混沌工程实验，以评估弹性和容错能力，由VMware开源。
* [OpenChaos](https://github.com/openmessaging/openchaos)：OpenChaos为供应商提出了一个统一的API，为在云原生环境中执行混沌工程原理的各个方面提供解决方案，由阿里发起。
* [Byte Monkey](https://github.com/mrwilson/byte-monkey)：Byte Monkey是一个小型Java库，用于测试JVM应用程序中的故障场景。
* [ChaosBlade Exec JVM](https://github.com/chaosblade-io/chaosblade-exec-jvm)：该项目是一个基于JVM-SandBox的ChaosBlade执行器，通过增强类来对Java应用程序进行混沌实验，阿里开源。

## 流量回放

* [JVM-Sandbox-Repeater](https://github.com/alibaba/jvm-sandbox-repeater)：JVM-Sandbox-Repeater是阿里开源的基于JVM-Sandbox的录制/回放通用解决方案。
* [Conan](https://github.com/tal-tech/conan)：柯南平台开源版本，为用户提供流量回放全流程解决方案，由好未来开源。
* [Moonbox](https://github.com/vivo/MoonBox)：Moonbox是基于JVM-Sandbox-Repeater重新开发的一款流量回放平台产品，由Vivo开源。

## API网关

* [Zuul](https://github.com/Netflix/zuul)：Zuul是一种网关服务，提供动态路由、监控、弹性、安全性等，由Netflix开源。
* [Apache ShenYu](https://github.com/apache/shenyu)：Apache ShenYu是一个Java原生API网关，用于服务代理、协议转换和API治理，由dromara社区开源。
* [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)：Spring Cloud Gateway旨在提供一种简单而有效的方法来路由到API并为其提供横切关注点。
* [FizzGate](https://github.com/fizzgate/fizz-gateway-node)：FizzGate是一个基于Java开发的微服务聚合网关。
* [Gateleen](https://github.com/swisspost/gateleen)：Gateleen是一个用于构建API网关的RESTFul中间件工具包，瑞士邮政开源。
* [VX API Gateway](https://gitee.com/mirren/VX-API-Gateway)：VX-API-Gateway是基于Vert.x开发的API网关，是一个全异步、高性能、可扩展、轻量级的API网关。
* [SIA Gateway](https://github.com/siaorg/sia-gateway)：SIA-Gateway是基于Spring Cloud微服务生态体系下开发的一个分布式微服务网关系统，宜信开源。
* [Gravitee](https://github.com/gravitee-io/gravitee-api-management)：Gravitee是一个灵活且快速的开源API网关。
* [Choreo Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、开源且以开发人员为中心的API网关代理，由WSO2开源。
* [Membrane](https://github.com/membrane/api-gateway)：Membrane是用Java编写的REST、OpenAPI、GraphQL和SOAP的API网关。
* [Okapi](https://github.com/folio-org/okapi)：Okapi是一个多租户API网关。
* [Janus](https://github.com/GrailStack/Janus)：Janus为RESTful、RPC提供对外统一，高性能的HTTP网关。
* [Kaazing Gateway](https://github.com/kaazing/gateway)：Kaazing Gateway是一个网络网关，旨在为基于Web的实时协议提升提供单一接入点，支持负载均衡、集群和安全管理。
* [API ML](https://github.com/zowe/api-layer)：API ML为大型机服务REST API提供单点访问。

## 大数据框架

* [Apache Hadoop](https://github.com/apache/hadoop)：Apache Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Apache Spark](https://github.com/apache/spark)：Apache Spark是一种多语言引擎，用于在单节点机器或集群上执行数据工程、数据科学和机器学习，由加州大学柏克莱分校AMPLab开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：ZooKeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo研究院开发。
* [Apache Pig](https://github.com/apache/pig)：Pig是一个用于处理非常大文件的数据流编程环境，由Yahoo开源。
* [Apache Storm](https://github.com/apache/storm)：Apache Storm是一个免费开源的分布式实时计算系统，由Twitter开源。
* [Apache Cassandra](https://github.com/apache/cassandra)：Apache Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache Hive](https://github.com/apache/hive)：Apache Hive是一种分布式容错数据仓库系统，可实现大规模分析，并有助于使用SQL读取、写入和管理分布式存储中的PB级数据，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，由Powerset开源。
* [Apache Doris](https://github.com/apache/doris)：Apache Doris是一个基于MPP架构的易于使用、高性能、实时分析的数据库，由百度开源。
* [Apache Calcite](https://github.com/apache/calcite)：Apache Calcite是一个动态数据管理框架。
* [Apache Nifi](https://github.com/apache/nifi)：Apache NiFi是一个易于使用、功能强大且可靠的系统，用于处理和分发数据，由美国国家安全局开源。
* [Apache Kylin](https://github.com/apache/kylin)：Apache Kylin是一个面向Hadoop和云的统一且强大的OLAP平台，由eBay贡献。
* [Apache Linkis](https://github.com/apache/linkis)：Linkis是一种计算中间件，充当上层应用程序和底层引擎(例如Spark、Hive和Flink)之间的层，由微众开源。
* [Apache Flume](https://github.com/apache/logging-flume)：Apache Flume是一种分布式、可靠且可用的服务，用于高效收集、聚合和移动大量日志数据，由Cloudera公司开源。
* [Apache Geode](https://github.com/apache/geode)：Geode是一个数据管理平台，可在广泛分布的云架构中提供对数据密集型应用程序的实时、一致的访问，由GemStone开源。
* [Apache Parquet](https://github.com/apache/parquet-mr)：Parquet是Hadoop生态系统中的任何项目都可以使用的列式存储格式，由Twitter和Cloudera共同开源。
* [Apache Drill](https://github.com/apache/drill)：Apache Drill是一个分布式MPP查询层，支持针对NoSQL和Hadoop数据存储系统的SQL和替代查询语言，由LinkedIn、思科、威斯康星大学麦迪逊分校等开源。
* [Apache Bookkeeper](https://github.com/apache/bookkeeper)：Apache BookKeeper是一种可扩展、容错和低延迟的存储服务，针对仅附加工作负载进行了优化，由雅虎研究院开发。
* [Apache InLong](https://github.com/apache/inlong)：Apache InLong是一站式、全场景的海量数据集成框架，支持数据摄取、数据同步和数据订阅，提供自动、安全、可靠的数据传输能力，由腾讯大数据团队开源。
* [Apache Accumulo](https://github.com/apache/accumulo)：Accumulo是一种排序的分布式键/值存储，可提供强大、可扩展的数据存储和检索，由美国国家安全局开源。
* [Apache Phoenix](https://github.com/apache/phoenix)：Apache Phoenix是基于HBase的SQL皮肤，作为客户端嵌入的JDBC驱动程序提供，旨在针对HBase数据的低延迟查询，由Salesforce开源。
* [Apache Oozie](https://github.com/apache/oozie)：Oozie是一个可扩展、可伸缩且可靠的系统，用于通过Web服务定义、管理、调度和执行复杂的Hadoop工作负载，由Cloudera开源。
* [Apache Ozone](https://github.com/apache/ozone)：Ozone是适用于Hadoop和云原生环境的可扩展、冗余和分布式对象存储，由腾讯大数据团队开源。
* [Apache Celeborn](https://github.com/apache/incubator-celeborn)：Apache Celeborn是一种弹性且高性能的服务，用于洗牌和溢出数据，由阿里云开源。
* [Apache CarbonData](https://github.com/apache/carbondata)：Apache CarbonData是一种索引列式数据存储解决方案，用于在大数据平台上进行快速分析，例如Apache Hadoop、Apache Spark等，由华为开源。
* [Apache Kyuubi](https://github.com/apache/kyuubi)：Kyuubi是一个分布式多租户网关，用于在数据仓库和Lakehouse上提供Serverless SQL，由网易数帆开源。
* [Snowplow](https://github.com/snowplow/snowplow)：Snowplow是一个开发者优先的收集行为数据的引擎。
* [Piflow](https://github.com/cas-bigdatalab/piflow)：Piflow是一个易于使用、功能强大的大数据管道系统，由科学大数据社区开源。
* [Airbyte](https://github.com/airbytehq/airbyte)：Airbyte是领先的数据集成平台，适用于从API、数据库和文件到数据仓库、数据湖和数据湖屋的ETL/ELT数据管道。
* [Scio](https://github.com/spotify/scio)：Scio是一个适用于Beam和Google Cloud Dataflow的Scala API，由Spotify开源。
* [Batch Processing Gateway](https://github.com/apple/batch-processing-gateway)：批处理网关使在Kubernetes上运行Spark服务变得容易，它允许用户通过直观的API调用在Kubernetes上提交、检查和删除Spark应用程序，由苹果开源。
* [Genie](https://github.com/Netflix/genie)：Genie是Netflix开发的联合大数据编排和执行引擎。
* [Venice](https://github.com/linkedin/venice)：Venice是一个衍生的数据存储平台，由LinkedIn开源。
* [DataWave](https://github.com/NationalSecurityAgency/datawave)：DataWave是一个基于Java的摄取和查询框架，它利用Accumulo提供对数据的快速、安全访问，由美国国家安全局开源。
* [Taier](https://github.com/DTStack/Taier)：太二是一个提交、调度、运维、指标信息展示的大数据开发平台，由袋鼠云开源。
* [Fire](https://gitee.com/fire-framework/fire)：Fire框架是由中通大数据自主研发并开源的、专门用于进行Spark和Flink任务开发的大数据框架。
* [Apache OODT](https://github.com/apache/oodt)：Apache OODT可以实现数据库链接、工作流处理以及硬件/文件管理等功能，由NASA的喷气机推力研究室开源。
* [Apache Sedona](https://github.com/apache/sedona)：Apache Sedona是一种空间计算引擎，使开发人员能够在Apache Spark和Apache Flink等现代集群计算系统中轻松处理任何规模的空间数据，由亚利桑那州立大学开源。
* [Presto](https://github.com/prestodb/presto)：Presto是一个用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Trino](https://github.com/trinodb/trino)：Trino是一个用于大数据分析的快速分布式SQL查询引擎，由Starburst开源。
* [SquashQL](https://github.com/squashql/squashql)：SquashQL是一个开源SQL查询引擎，旨在简化构建多维查询的过程。
* [Pipes](https://github.com/tinkerpop/pipes)：Pipes是一个数据流框架，可实现数据从输入到输出的拆分、合并、过滤和转换，由斯阿拉莫斯国家实验室开源。
* [Scaleph](https://github.com/flowerfine/scaleph)：Scaleph是一个基于Flink和Kubernetes打造的开放数据平台，具备Flink和SeaTunnel任务管理能力，同时支持Doris集群在Kubernetes上的运维部署。
* [Transport](https://github.com/linkedin/transport)：Transport是一个用于编写高性能用户定义函数(UDF)的框架，这些函数可跨各种引擎(包括Apache Spark、Apache Hive和Trino)进行移植，由LinkedIn开发。

## 大数据工具

* [HiBench](https://github.com/Intel-bigdata/HiBench)：HiBench是一个大数据基准测试套件，可帮助评估不同大数据框架的速度、吞吐量和系统资源利用率，由Intel开源。
* [Apache Crunch](https://crunch.apache.org/)：Apache Crunch库提供了一个用于编写、测试和运行MapReduce管道的框架，由Google开源。
* [Apache MRUnit](https://mrunit.apache.org/)：Apache MRUnit是一个Java库，可帮助开发人员对Apache Hadoop MapReduce作业进行单元测试，由Cloudera开源。
* [Ambrose](https://github.com/twitter-archive/ambrose)：Ambrose是一个用于MapReduce数据工作流可视化和实时监控的平台，由Twitter开源。
* [EGADS](https://github.com/yahoo/egads)：EGADS是一个开源Java包，用于自动检测大规模时序数据中的异常，由Yahoo开源。
* [Data Transfer Project](https://github.com/google/data-transfer-project)：Data Transfer Project使人们可以轻松地在在线服务提供商之间传输数据，由Google联合Facebook、Twitter、Apple、Microsoft等开发。
* [Yanagishima](https://github.com/yanagishima/yanagishima)：Yanagishima是Trino、Hive和Spark的开源Web应用程序。
* [Apache Ambari](https://github.com/apache/ambari)：Apache Ambari是一个用于配置、管理和监控Apache Hadoop集群的工具，由Hortonworks开源。
* [Elephant Bird](https://github.com/twitter/elephant-bird)：Elephant Bird是Twitter的开源库，包含LZO、Thrift和/或Protocol Buffer相关的Hadoop InputFormats、OutputFormats、Writables、Pig LoadFuncs、Hive SerDe、HBase杂项等。
* [Priam](https://github.com/Netflix/Priam)：Priam是一个与Apache Cassandra一起运行的流程/工具，这是一个高度可用的、面向列的数据库，由Netflix开源。
* [Deequ](https://github.com/awslabs/deequ)：Deequ是一个构建在Apache Spark之上的库，用于定义“数据单元测试”，测量大型数据集中的数据质量，由AWS开源。
* [Cloudbreak](https://github.com/hortonworks/cloudbreak)：部署在云服务上的集成分析和数据管理平台，它提供广泛的数据分析和人工智能功能以及安全的用户访问和数据治理功能，由Hortonworks开源。
* [YCSB](https://github.com/brianfrankcooper/YCSB)：雅虎云服务基准测试框架。
* [Flink Spector](https://github.com/ottogroup/flink-spector)：该项目提供了一个框架来定义Apache Flink数据流的单元测试。
* [CloudEon](https://github.com/dromara/CloudEon)：CloudEon使用Kubernetes安装和部署开源大数据组件，实现开源大数据平台的容器化运行，dromara社区开源。
* [Exhibitor](https://github.com/soabase/exhibitor)：ZooKeeper协同处理实例，例如监控、备份/恢复、清理和可视化，由Netflix开源。
* [Spark RAPIDS](https://github.com/NVIDIA/spark-rapids)：Apache Spark的RAPIDS加速器利用GPU通过RAPIDS库加速处理，由NVIDIA开源。
* [BigQuery Utils](https://github.com/GoogleCloudPlatform/bigquery-utils)：BigQuery是一个Serverless、高度可扩展且经济高效的云数据仓库，内置内存BI引擎和机器学习，该库提供有用的实用程序来帮助你迁移和使用BigQuery，由Google开发。
* [Apache Metron](https://github.com/apache/metron)：Metron集成了多种开源大数据技术，以提供集中的安全监控和分析工具，由Cisco开源。
* [DataGenerator](https://github.com/FINRAOS/DataGenerator)：DataGenerator是一个用于系统地生成大量数据的Java库，美国金融业监管局开源。
* [Cassandra Reaper](https://github.com/thelastpickle/cassandra-reaper)：Reaper是一种集中式、有状态且高度可配置的工具，用于针对单站点或多站点集群运行Apache Cassandra修复，由DataStax开源。
* [Surus](https://github.com/Netflix/Surus)：Pig和Hive中的分析工具集合，Netflix开源。
* [Apache AsterixDB](https://github.com/apache/asterixdb)：AsterixDB是一个大数据管理系统，具有丰富的功能集，由加利福尼亚大学欧文分校的Michael Carey发起。
* [Hollow](https://github.com/Netflix/hollow)：Hollow是一个Java库和工具集，用于将内存数据集从单个生产者传播到许多消费者，以实现高性能只读访问，由Netflix开源。
* [Compass](https://github.com/cubefs/compass)：Compass是一个大数据任务诊断平台，由OPPO大数据团队开发。
* [Olap4j](https://github.com/olap4j/olap4j)：Olap4j是用于访问OLAP数据的开放Java API，Pentaho开源。
* [Dataverse](https://github.com/IQSS/dataverse)：Dataverse是一个用于共享、查找、引用和保存研究数据的开源软件平台，由哈佛大学定量社会科学研究所开源。
* [Apache Bigtop](https://github.com/apache/bigtop)：Bigtop旨在为基础设施工程师和数据科学家寻找领先的开源大数据组件的全面打包、测试和配置。
* [Apache Wayang](https://github.com/apache/incubator-wayang)：Wayang是统一的数据处理框架，可无缝集成和编排多个数据平台，以提供无与伦比的性能和灵活性，由柏林工业大学开源。
* [Metanome](https://github.com/HPI-Information-Systems/Metanome)：Metanome是HPI和卡塔尔计算研究所之间的联合项目，通过开发高效算法并将其集成到通用工具中、扩展数据分析的功能以及解决大数据的性能和可扩展性问题，为数据分析提供了全新的视角。
* [GraphAr](https://github.com/alibaba/GraphAr)：用于图数据存储和检索的开源标准数据文件格式，由阿里开源。
* [KNIME](https://github.com/knime/knime-core)：KNIME是由德国的康斯坦茨大学，一组研究制药应用的开发团队在2006年7月推出的一款针对大数据的软件。
* [DataCompare](https://gitee.com/dromara/data-compare)：DataCompare是一个大数据数据比对和数据探测平台，由dromara社区开源。
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [Apache TsFile](https://github.com/apache/tsfile)：TsFile是一种专为时序数据设计的列式存储文件格式，支持高效压缩、读写高吞吐，并且兼容Spark、Flink等多种框架。
* [Fast Causal Inference](https://github.com/Tencent/fast-causal-inference)：Fast Causal Inference是腾讯开源的因果推理项目，它是一个基于OLAP的高性能因果推理(统计模型)计算库，解决了现有统计模型库(R/Python)在大数据下的性能瓶颈，为秒级和亚级海量数据执行提供因果推理能力。
* [Flink Streaming Platform Web](https://github.com/zhp8341/flink-streaming-platform-web)：Flink Streaming Platform Web是基于Apache Flink封装的一个可视化、轻量级的Flink Web客户端系统。
* [WInte.r](https://github.com/olehmberg/winter)：WInte.r框架提供了端到端数据集成的方法，该框架实现了众所周知的数据预处理、模式匹配、身份解析、数据融合和结果评估方法。
* [Inviso](https://github.com/Netflix/inviso)：Inviso是一个轻量级工具，提供搜索Hadoop作业、可视化性能和查看集群利用率的功能，由Netflix开源。
* [AGEIPort](https://github.com/alibaba/AGEIPort)：AGEIPort是数字供应链孵化并在阿里内广泛使用的一套性能卓越、稳定可靠、功能丰富、易于扩展、生态完整的数据导入导出方案，由阿里开源。
* [ES-Fastloader](https://github.com/didi/ES-Fastloader)：ES-Fastloader利用Hadoop的容错性和并行性，在多个reducer节点中构建单独的ElasticSearch分片，然后将分片传输到ElasticSearch集群进行服务，由滴滴开源。
* [Apache Livy](https://github.com/apache/incubator-livy)：Apache Livy是一个开源REST接口，用于从任何地方与Apache Spark交互，由Cloudera开源。
* [ZMS](https://github.com/ZTO-Express/zms)：ZMS是使用方与集群解耦，屏蔽各消息集群差异，并对消息集群进行安装、管理、监控、告警管理的平台，由中通开源。
* [Squall](https://github.com/epfldata/squall)：Squall是一个构建在Storm之上的在线查询处理引擎，由洛桑联邦理工学院数据实验室开源。
* [Cascading](https://github.com/cwensel/cascading)：Cascading是一个功能丰富的API，用于在本地或集群上定义和执行复杂且容错的数据处理流。
* [UberScriptQuery](https://github.com/uber/uberscriptquery)：UberScriptQuery是一个用于运行Spark SQL作业的脚本查询包装器，由Uber开源。
* [Spark-JobServer](https://github.com/spark-jobserver/spark-jobserver)：Spark-JobServer提供了一个RESTful接口，用于提交和管理Apache Spark作业、jar和作业上下文。
* [Apache Tephra](https://github.com/cdapio/tephra)：Apache Tephra在Apache HBase等分布式数据存储之上提供全局一致的事务，由Google开源。
* [Haeinsa](https://github.com/VCNC/haeinsa)：Haeinsa是HBase的线性可扩展的多行、多表事务库，由VCNC开源。
* [Lipstick](https://github.com/Netflix/Lipstick)：Lipstick将Pig工作流程的图形描述与作业执行时的相关信息结合起来，由Netflix开源。
* [StreamDM](https://github.com/huawei-noah/streamDM)：StreamDM是一款新的开源软件，用于使用Spark Streaming挖掘大数据流，由华为诺亚方舟实验室开源。

## 大数据组件

* [ChunJun](https://github.com/DTStack/chunjun)：ChunJun是基于Flink的批流统一打造的数据同步工具，可以实现各种异构数据源之间的数据同步和计算，由袋鼠云开源。
* [DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio)：DataSphere Studio是微众银行开发的一站式数据应用开发管理门户。
* [Quicksql](https://github.com/Qihoo360/Quicksql)：Quicksql是一款SQL查询产品，可用于特定数据存储查询或多个数据存储关联查询，由360开源。
* [BitSail](https://github.com/bytedance/bitsail)：BitSail是字节开源的基于分布式架构、高性能的数据集成引擎。
* [Dr.Elephant](https://github.com/linkedin/dr-elephant)：Dr.Elephant是一款针对Hadoop和Spark的性能监控和调优工具，由LinkedIn开源。
* [CDAP](https://github.com/cdapio/cdap)：CDAP是一个面向Hadoop生态系统的集成开源应用程序开发平台，为开发人员提供数据和应用程序抽象，目前是Google云端项目。
* [Elasticsearch Hadoop](https://github.com/elastic/elasticsearch-hadoop)：Elasticsearch实时搜索和分析与Hadoop原生集成，支持Map/Reduce、Hive和Spark。
* [Apache Uniffle](https://github.com/apache/incubator-uniffle)：Uniffle是一种用于分布式计算引擎的高性能、通用远程洗牌服务，由腾讯开源。
* [Cubert](https://github.com/LinkedInAttic/Cubert)：Cubert是一种快速高效的批量计算引擎，用于对Hadoop上的海量数据集进行复杂分析和报告，由LinkedIn开源。
* [Apache ORC](https://github.com/apache/orc)：ORC是一种自描述、类型感知的列式文件格式，专为Hadoop工作负载而设计，由Hortonworks和Facebook联合开发。
* [Secor](https://github.com/pinterest/secor)：Secor是一项将Kafka日志持久保存到Amazon S3、Google Cloud Storage、Microsoft Azure Blob Storage和Openstack Swift的服务，由Pinterest开源。
* [DataBand](https://gitee.com/475660/databand)：轻量级一站式大数据分析平台。
* [Big Whale](https://gitee.com/meetyoucrop/big-whale)：美柚大数据研发的分布式计算任务调度系统，提供Spark、Flink等批处理任务的DAG调度和流处理任务的运行管理和状态监控，并具有Yarn应用管理、重复应用检测、大内存应用检测等功能。
* [DataCap](https://github.com/devlive-community/datacap)：DataCap是用于数据转换、集成和可视化的集成软件，由Devlive社区开源。
* [Fili](https://github.com/yahoo/fili)：Fili是一个基于Java的框架，可以轻松构建和维护用于时间序列报告和分析的RESTful Web服务，由Yahoo开源。
* [DBus](https://github.com/BriData/DBus)：DBus专注于数据的收集及实时数据流计算，通过简单灵活的配置，无侵入的方式对源端数据进行采集。
* [Qualitis](https://github.com/WeBankFinTech/Qualitis)：Qualitis是一个数据质量管理平台，支持各种数据源的质量验证、通知和管理，用于解决数据处理过程中引起的各种数据质量问题，由微众开源。
* [Embulk](https://github.com/embulk/embulk)：Embulk是一个并行批量数据加载器，有助于在各种存储、数据库、NoSQL和云服务之间传输数据。
* [Stroom](https://github.com/gchq/stroom)：Stroom是一个数据处理、存储和分析平台，由英国政府通讯总部开源。
* [DnA](https://github.com/mercedes-benz/DnA)：DnA为分析领域的企业提供A-Z解决方案，从计划和正在进行的活动的透明度到提供实现这些活动的开源组件，由奔驰开源。
* [Rakam](https://github.com/rakam-io/rakam-api)：Rakam是一个分析平台，可让你创建分析服务。
* [Shuttle](https://github.com/cubefs/shuttle)：Shuttle提供远程shuffle功能，可以按分区将shuffle数据分组并转储到分布式文件系统中，由OPPO大数据团队开源。
* [Firehose](https://github.com/raystack/firehose)：Firehose是一种可扩展、无代码、云原生服务，用于将实时流数据从Kafka加载到数据存储、数据湖和分析存储系统。
* [IndexR](https://github.com/shunfei/indexr)：IndexR是HDFS上的超快速列式数据格式，专注于快速分析，既适用于海量静态(历史)数据，也适用于快速摄取实时数据，由舜飞开源。
* [DataFu](https://github.com/LinkedInAttic/datafu)：DataFu是用于处理Hadoop中的大规模数据的库集合，由LinkedIn开源。
* [Apache Hama](http://hama.apache.org/)：Apache Hama是一个使用批量同步并行(BSP)计算模型的大数据分析框架。
* [LemonGrenade](https://github.com/NationalSecurityAgency/lemongrenade)：LemonGrenade被设计为一个自动化系统，能够将系统、数据源或功能智能地链接在一起，而无需最终用户手动指定链接，由美国国家安全局开源。
* [XPipe](https://github.com/ctripcorp/x-pipe)：X-Pipe是由携程框架部门研发的Redis多数据中心复制管理系统。
* [Apache Tez](https://github.com/apache/tez)：Apache Tez是一个通用数据处理管道引擎，被设想为用于更高抽象的低级引擎，例如Hadoop Map-Reduce、Pig、Hive等，由IBM和Adobe开发。
* [Esper](https://github.com/espertechinc/esper)：Esper是用于复杂事件处理(CEP)、流式SQL和事件系列分析的组件。
* [Apache Falcon](http://falcon.apache.org/)：Falcon是一个Feed处理和Feed管理系统，旨在让最终消费者更轻松地在Hadoop集群上进行Feed处理和管理。
* [Egeria](https://github.com/odpi/egeria)：Egeria提供开放元数据和治理类型系统、框架、API、事件有效负载和交换协议，由IBM开源。
* [BigQuery Data Lineage](https://github.com/GoogleCloudPlatform/bigquery-data-lineage)：使用审核日志、ZetaSQL和Dataflow对BigQuery进行实时数据沿袭跟踪的参考实现，由Google开源。
* [Suro](https://github.com/Netflix/suro)：Suro是一种数据管道服务，用于收集、聚合和调度大量应用程序事件(包括日志数据)，由Netflix开发。
* [Maxwell](https://github.com/zendesk/maxwell)：Maxwell是一个变更数据捕获应用程序，它读取MySQL二进制日志并将数据变更以JSON形式写入Kafka、Kinesis和其他流平台，由Zendesk开源。
* [MdRill](https://github.com/alibaba/mdrill)：MdRill作为数据在线分析处理软件，可以在几秒到几十秒的时间，分析百亿级别的任意组合维度的数据，由阿里开源。
* [Apache Apex](https://github.com/apache/apex-core)：Apex是一个用于大数据流和批处理的统一平台，由DataTorrent开源。
* [Apache Knox](https://github.com/apache/knox)：Knox是一个应用程序网关，用于以安全的方式与一个或多个Hadoop集群的REST API和用户界面进行交互。
* [Apache Hop](https://github.com/apache/hop)：Hop编排平台旨在促进数据和元数据编排的各个方面，也是Kettle的前身。
* [OpenHuFu](https://github.com/BUAA-BDA/OpenHuFu)：OpenHuFu是一个开源的数据联邦系统，支持多数据库协同查询，并具有安全保障，由清华大学开源。
* [Eclipse Connector](https://github.com/eclipse-edc/Connector)：EDC核心服务包括数据平面和控制平面。
* [OpenLooKeng](https://github.com/openlookeng/hetu-core)：OpenLooKeng是一个嵌入式引擎，可以对任何地方的任何数据进行现场分析，包括地理上远程的数据源，由华为开源。
* [Teiid](https://github.com/teiid/teiid)：Teiid是一个数据虚拟化系统，允许应用程序使用来自多个异构数据存储的数据，由RedHat主导。
* [XAP](https://github.com/xap/xap)：分布式、高度可扩展的内存数据网格，由GigaSpaces开源。
* [GridGain Community Edition](https://github.com/gridgain/gridgain)：GridGain是一个强化的高性能开源内存计算平台。
* [Apache Griffin](https://github.com/apache/griffin)：Griffin是一个开源的大数据数据质量解决方案，由eBay开源，它支持批处理和流模式两种数据质量检测方式，是一个基于Hadoop和Spark建立的数据质量服务平台。
* [Apache Ranger](https://github.com/apache/ranger)：Apache Ranger是一个用在Hadoop平台上并提供操作、监控、管理综合数据安全的框架，由Hortonworks开源。
* [Beekeeper](https://github.com/ExpediaGroup/beekeeper)：Beekeeper是一个安排删除孤立路径和过期元数据的服务，由Expedia开源。
* [Apache Mnemonic](https://github.com/apache/mnemonic)：Apache Mnemonic是一个面向非易失性混合内存存储的库，它提出了非易失性/持久性Java对象模型和持久性计算服务，为显著提高海量实时数据处理/分析的性能带来了多种优势。
* [Stocator](https://github.com/CODAIT/stocator)：Stocator是Apache Spark对象存储的高性能连接器，通过利用对象存储语义来实现性能，由IBM开源。
* [MR4C](https://github.com/google/mr4c)：MR4C是一个允许你在Hadoop执行框架内运行本机代码的框架，由Google开源。
* [Apache Tajo](https://github.com/apache/tajo)：Apache Tajo是Hadoop的开源分布式数据仓库框架，最初由韩国基础设施公司Gruter开发。
* [Apache Airavata](https://github.com/apache/airavata)：Apache Airavata是一个软件框架，用于在分布式计算资源(包括本地集群、超级计算机、国家电网、学术和商业云)上执行和管理计算性任务，最初由印第安纳大学开发。
* [LarkMidTable](https://gitee.com/LarkMidTable/LarkMidTable)：LarkMidTable是一站式开源的数据中台，实现元数据管理，数据仓库开发，数据质量管理，数据的可视化，实现高效赋能数据前台并提供数据服务的产品。
* [云雀](https://gitee.com/LarkMidTable/yunque)：云雀是一款数据集成工具，实现异构数据源的整合，帮助企业构建数据仓库、数据湖等应用架构。
* [DeltaFi](https://gitlab.com/deltafi/deltafi)：DeltaFi是一个灵活、轻量代码的数据转换和标准化平台。
* [Datacube](https://github.com/urbanairship/datacube)：具有数值数据汇总的多维数据存储，由Airship开源。
* [Apache Eagle](https://github.com/apache/eagle)：Apache Eagle是一种开源分析解决方案，用于在大数据平台上立即识别安全和性能问题，由eBay开源。
* [TrainDB](https://github.com/traindb-project/traindb)：TrainDB是一个基于ML的近似查询处理引擎，旨在在几秒钟内回答耗时的分析查询，由延世大学、光云大学、ETRI、RealTimeTech、BI Matrix开源。
* [Apache Gluten](https://github.com/apache/incubator-gluten)：Gluten是一个中间层，负责将基于JVM的SQL引擎的执行卸载到本机引擎，由Intel和Kyligence开源。
* [Maha](https://github.com/yahoo/maha)：快速报告API开发的框架，开箱即用地支持Druid的高基数维度查找，由Yahoo开源。
* [Apache DataFusion Comet](https://github.com/apache/datafusion-comet)：Apache DataFusion Comet是一个Apache Spark插件，它使用Apache DataFusion作为本机运行时，以实现查询效率和查询运行时方面的改进，由Apple开源。
* [XL-LightHouse](https://github.com/xl-xueling/xl-lighthouse)：XL-LightHouse是一套支持超大数据量、支持超高并发的通用型流式大数据统计系统。
* [Conquery](https://github.com/ingef/conquery)：Conquery是一个强大的基于Web的工具，用于针对大型事件类数据集编写和执行查询。

## 数据可视化

* [Davinci](https://github.com/edp963/davinci)：Davinci面向产品经理、业务人员、数据工程师、数据分析师、数据科学家等，旨在提供一站式数据可视化解决方案，既可以独立作为公有云/私有云使用，也可以集成到第三方云中，由宜信开源。
* [Prefuse](https://github.com/prefuse/Prefuse)：Prefuse是一个基于Java的工具包，用于构建交互式信息可视化应用程序，Prefuse支持一组丰富的数据建模、可视化和交互功能，由加州大学伯克利分校开源。
* [ECharts Java](https://github.com/ECharts-Java/ECharts-Java)：ECharts Java是一个轻量级但全面的库，供Java开发人员轻松使用JavaScript可视化库Apache ECharts。
* [Mirador](https://github.com/mirador/mirador)：Mirador是一种通过视觉探索在复杂数据集中识别新假设的工具，由斯坦福联合哈佛大学、美国国家美术馆和其他几家世界各地的机构共同进行扩展开发。
* [Ananas](https://github.com/ananas-analytics/ananas-desktop)：一种可破解的数据集成和分析工具，使非技术用户能够编辑数据处理作业并按需可视化数据。
* [DataEase](https://github.com/dataease/dataease)：开源的数据可视化分析工具，帮助用户快速分析数据并洞察业务趋势，从而实现业务的改进与优化，由飞致云开源。
* [DataGear](https://gitee.com/datagear/datagear)：DataGear是一款开源免费的数据可视化分析平台，支持接入SQL、CSV、Excel、HTTP接口、JSON等多种数据源。
* [FlyFish](https://gitee.com/CloudWise/fly-fish)：飞鱼是一个数据可视化编码平台。通过简易的方式快速创建数据模型，通过拖拉拽的形式，快速生成一套数据可视化解决方案，云智慧开源。
* [Dex](https://github.com/PatMartin/Dex)：Dex是数据科学的强大工具，它是在JavaFX之上用Groovy和Java编写的数据可视化工具，能够进行强大的ETL和发布Web可视化。
* [LJV](https://github.com/atp-mipt/ljv)：LJV是使用Graphviz可视化Java数据结构的工具，由莫斯科物理技术学院开源。
* [Sigbla](https://github.com/sigbla/sigbla-app)：Sigbla是一个使用Kotlin编程语言处理表中数据的框架，它支持各种数据类型、响应式编程和事件、用户输入、图表等。
* [VisNow](https://gitlab.com/visnow.org/VisNow)：VisNow是Java中的通用可视化框架，由华沙大学开发，它是一个模块化数据流驱动平台，使用户能够创建数据可视化、可视化分析、数据处理和简单模拟的方案。
* [Moonbox](https://github.com/running-elephant/moonbox)：Moonbox基于“数据虚拟化”概念设计，旨在提供批量和交互式计算服务。
* [CKibana](https://github.com/TongchengOpenSource/ckibana)：CKibana是一项使用原生Kibana方便分析ClickHouse数据的服务，由携程开源。
* [Data2viz](https://github.com/data2viz/data2viz)：Data2viz是Kotlin多平台的数据可视化工具库。
* [McIDAS-V](https://www.ssec.wisc.edu/%7Ebillh/visad.html)：McIDAS-V是一款免费、开源、可视化和数据分析软件包，是SSEC 50年复杂McIDAS软件包历史中的下一代产品，由威斯康星大学麦迪逊分校开源。
* [TelemetryViewer](https://github.com/farrellf/TelemetryViewer)：数据可视化工具。
* [MDSplus](https://github.com/MDSplus/mdsplus)：MDSplus是一套用于数据采集和存储的软件工具，以及管理复杂科学数据的方法，由麻省理工学院、意大利帕多瓦聚变研究小组和洛斯阿拉莫斯国家实验室联合开发。
* [AAChartCore](https://github.com/AAChartModel/AAChartCore)：极其精美而又强大的Android数据可视化图表框架，支持柱状图、条形图、折线图、曲线图。
* [Super Mjograph](https://www.mjograph.net/)：Mjograph是一款在Mac OSX和Java上运行的XY(2D)图形编辑器，旨在为研究人员提供一种快速的方法来可视化数值数据并创建出版质量的绘图。

## 图处理

* [JGraphT](https://github.com/jgrapht/jgrapht)：JGraphT是一个免费的Java类库，提供数学图论对象和算法。
* [Graphviz Java](https://github.com/nidi3/graphviz-java)：将graphviz与纯Java一起使用，使用Java代码创建graphviz模型并将其转换为漂亮的图形。
* [Apache Commons Graph](https://github.com/apache/commons-graph)：Apache Commons Graph是一个用于管理图和基于图的数据结构的工具包。
* [PGX](https://www.oracle.com/middleware/technologies/parallel-graph-analytix.html)：PGX是一个用于图分析的工具包，支持高效的图算法和快速的类似SQL的图模式匹配查询，由Oracle开发。
* [Gradoop](https://github.com/dbs-leipzig/gradoop)：Gradoop是一个开源研究框架，用于构建在Apache Flink之上的可扩展图分析，由莱比锡大学数据库研究组开发。
* [SociaLite](https://github.com/socialite-lang/socialite)：SociaLite是一种用于分布式图分析的高级查询语言，由斯坦福开源。
* [JUNG](https://github.com/jrtom/jung)：JUNG是一个软件库，它提供了一种通用且可扩展的语言，用于对可以表示为图形或网络的数据进行建模、分析和可视化。
* [PGQL](https://github.com/oracle/pgql-lang)：PGQL是一种基于SQL的属性图数据模型查询语言，为SQL和NoSQL用户带来图模式匹配功能，由Oracle开源。
* [Ant Graph Learning](https://github.com/TuGraph-family/TuGraph-AntGraphLearning)：Ant Graph Learning为工业规模的图学习任务提供了全面的解决方案，由蚂蚁开源。
* [GraphBuilder](https://github.com/intel/graphbuilder)：GraphBuilder库提供了构建大规模图的函数，由Intel开源。
* [GraphStream](https://github.com/graphstream/gs-core)：GraphStream项目是一个Java库，提供API来建模、分析和可视化图和动态图，由勒阿弗尔大学开源。
* [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)：Erdos是一个非常轻量、模块化且超级易于使用的Java现代图论算法框架。
* [Neo4j Graph Data Science](https://github.com/neo4j/graph-data-science)：GDS包括图算法、图转换和机器学习管道，通过Neo4j DBMS内的Cypher程序进行操作。

## 数据目录

* [DataHub](https://github.com/datahub-project/datahub)：DataHub是现代数据堆栈的开源元数据平台，由LinkedIn开源。
* [Metacat](https://github.com/Netflix/metacat)：Metacat是一个联合的元数据API服务，可以访问Hive、RDS、Teradata、Redshift、S3和Cassandra，由Netflix开源。
* [Polaris](https://github.com/polaris-catalog/polaris)：Polaris是Apache Iceberg的开源、功能齐全的目录，由Snowflake开发。
* [Marquez](https://github.com/MarquezProject/marquez)：Marquez是一种开源元数据服务，用于数据生态系统元数据的收集、聚合和可视化，由WeWork开源。
* [Apache Atlas](https://github.com/apache/atlas)：Apache Atlas是一组可扩展的核心基础治理服务-使企业能够有效地满足Hadoop内的合规性要求，并允许与整个企业数据生态系统集成，由Hortonworks开源。
* [OpenMetadata](https://github.com/open-metadata/OpenMetadata)：OpenMetadata是一个开源元数据存储库，由Uber元数据基础架构背后的团队构建。
* [Open Data Discovery](https://github.com/opendatadiscovery/odd-platform)：Open Data Discovery是一款面向数据团队的开源数据发现和可观察性工具，由Provectus开源。
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog)：Unity Catalog是最开放、可互操作的数据和AI目录，由Databricks开源。
* [Apache Gravitino](https://github.com/apache/gravitino)：Gravitino是一个高性能、地理分布式、联合元数据湖，由Datastrato开源。
* [Magda](https://github.com/magda-io/magda)：Magda是适用于所有大数据和小数据的联合开源数据目录，由澳大利亚联邦科学与工业研究组织的Data61和澳大利亚总理及内阁部发起。

## 流处理平台

* [Apache Flink](https://github.com/apache/flink)：一个开源流处理框架，具有强大的流处理和批处理能力，由柏林工业大学发起的项目。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：云原生消息传递和流媒体平台，可以轻松构建事件驱动的应用程序，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：使用最广泛的分布式流平台，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：新一代云原生分布式消息流平台，由Yahoo开源。
* [Storm](https://github.com/nathanmarz/storm)：分布式和容错实时计算：流处理、连续计算、分布式RPC等。
* [Apache Beam](https://github.com/apache/beam)：用于批处理和流数据处理的统一编程模型，由Google开源。
* [Apache SeaTunnel](https://github.com/apache/seatunnel)：下一代超高性能、分布式、海量数据集成工具，由中国通信学会开源技术委员会发起的项目。
* [Hazelcast](https://github.com/hazelcast/hazelcast)：一个实时流处理平台，可让你构建立即对数据采取操作的应用程序，由Hazelcast开源。
* [JStorm](https://github.com/alibaba/jstorm)：一个分布式、容错的实时计算系统，受Storm启发并由阿里重写开源。
* [Apache Heron](https://github.com/apache/incubator-heron)：Twitter的实时、分布式、容错流处理引擎。
* [Apache StreamPark](https://github.com/apache/incubator-streampark)：流处理开发框架和专业管理平台，由个人组织StreamXHub创建。
* [Dinky](https://github.com/DataLinkDC/dinky)：Dinky是一个开箱即用的一站式实时计算平台，致力于统一流批处理、统一数据湖和数据仓库的构建和实践。
* [Summingbird](https://github.com/twitter/summingbird)：Summingbird是Twitter开源的一个库，可让你编写类似于原生Scala或Java集合转换的MapReduce程序，并在许多著名的分布式MapReduce平台(包括Storm和Scalding)上执行它们。
* [Apache Gobblin](https://github.com/apache/gobblin)：用于流数据和批处理数据生态系统的分布式大数据集成框架，由LinkedIn开源。
* [Pravega](https://github.com/pravega/pravega)：Pravega是一种开源流存储系统，可实现流并充当用于存储或提供连续、无界数据的出色基元，由Dell开源。
* [AthenaX](https://github.com/uber-archive/AthenaX)：基于SQL的大规模流分析平台，由Uber开源。
* [Jet](https://github.com/hazelcast/hazelcast-jet)：开源、内存中、分布式批处理和流处理引擎，由Hazelcast开源。
* [FlinkStreamSQL](https://github.com/DTStack/flinkStreamSQL)：基于开源的Flink，对其实时SQL进行扩展；主要实现了流与维表的join，支持原生Flink SQL所有的语法，由袋鼠云开源。
* [Apache Samza](https://github.com/apache/samza)：Samza是一个分布式流处理框架，它使用Kafka进行消息传递，并使用Hadoop YARN提供容错、处理器隔离、安全性和资源管理，由LinkedIn开源。
* [Siddhi](https://github.com/siddhi-io/siddhi)：一个云原生流式处理和复杂事件处理引擎。
* [StreamFlow](https://github.com/lmco/streamflow)：StreamFlow是一种流处理工具，旨在帮助构建和监控处理工作流，这是洛克希德马丁公司的开源项目。
* [Apache Nemo](https://github.com/apache/incubator-nemo)：Apache Nemo是一个用于分布式数据流处理的优化框架，它为高性能提供了精细的控制，同时也确保了正确性，由首尔大学开源。
* [NeonBee](https://github.com/SAP/neonbee)：NeonBee是一个开源的响应式数据流引擎，是一个使用Vert.x的数据流处理框架，由SAP开源。
* [Streamis](https://github.com/WeBankFinTech/Streamis)：Streamis是微众银行联合天翼云、仙翁科技和萨摩耶云联合共建的流式应用开发管理系统。
* [Wormhole](https://github.com/edp963/wormhole)：Wormhole面向大数据流式处理项目的开发管理运维人员，致力于提供统一抽象的概念体系，直观可视化的操作界面，简单流畅的配置管理流程，由宜信开源。
* [LogIsland](https://github.com/Hurence/logisland)：LogIsland是一个事件挖掘可扩展平台，旨在处理高吞吐量的事件。
* [Stream Registry](https://github.com/ExpediaGroup/stream-registry)：流发现和流编排服务，由Expedia开源。
* [Tigon](https://github.com/cdapio/tigon)：Tigon是一个开源、实时、低延迟、高吞吐量的流处理框架，由Google开源。
* [Gearpump](https://github.com/gearpump/gearpump)：Gearpump是一个轻量级的实时大数据流引擎，由Intel开源。
* [BeepBeep](https://github.com/liflab/beepbeep-3)：BeepBeep是一个事件流查询引擎，由魁北克大学开源。

## ETL工具

* [Addax](https://github.com/wgzhao/Addax)：一款多功能开源ETL工具，可以在各种RDBMS和NoSQL数据库之间无缝传输数据，使其成为数据迁移的理想解决方案，最初来源于阿里的DataX。
* [TIS](https://github.com/datavane/tis)：支持基于Flink、DataX和Flink-CDC的敏捷DataOps，Chunjun具有Web-UI，由Datavane大数据组织开源。
* [Exchangis](https://github.com/WeBankFinTech/Exchangis)：微众银行大数据平台WeDataSphere与社区用户共同开发的新版数据交换工具，支持异构数据源之间结构化和非结构化数据的同步传输。
* [Smooks](https://github.com/smooks/smooks)：Smooks是一个可扩展的Java框架，用于构建基于XML和非XML数据(CSV、EDI、POJO等)的基于片段的应用程序。
* [Kafka Connect File Pulse](https://github.com/streamthoughts/kafka-connect-file-pulse)：Connect FilePulse是一种多用途、可扩展且可靠的Kafka连接器，可以轻松解析、转换任何格式的任何文件并将其流式传输到Apache Kafka，由StreamThoughts开源。
* [Extract](https://github.com/ICIJ/extract)：用于并行、分布式内容提取的跨平台命令行工具。
* [Bender](https://github.com/Nextdoor/bender)：该项目提供了一个可扩展的Java框架，用于在AWS Lambda上创建Serverless ETL函数，Bender处理复杂的管道并提供为ETL过程的各个方面构建模块所需的接口。
* [Orbital](https://github.com/orbitalapi/orbital)：Orbital是一个数据网关，可自动集成、转换和发现整个企业中数据源(API、数据库、消息代理)的数据。
* [LinkMove](https://github.com/nhl/link-move)：LinkMove是一个模型驱动的动态可配置框架，用于从外部源获取数据并将其保存在数据库中，由北美职业冰球联盟开源。
* [Hydrograph](https://github.com/BitwiseInc/Hydrograph)：Hydrograph是一款功能强大的ETL工具，允许开发人员使用简单的拖放界面创建复杂的图表。
* [LinkedPipes ETL](https://github.com/linkedpipes/etl)：LinkedPipes ETL是一个基于RDF的轻量级ETL工具。
* [FHIR Data Pipes](https://github.com/google/fhir-data-pipes)：该仓库包括使用FHIR格式将来自FHIR服务器(例如HAPI、GCP FHIR存储，甚至OpenMRS)的数据转换为基于Apache Parquet文件或其他FHIR服务器的数据仓库的管道，由Google开源。
* [Talend Open Studio](https://github.com/Talend/tcommon-studio-se)：借助Talend Open Studio，你可以立即开始构建基本数据管道，从你控制的本地安装的开源环境中执行简单的ETL和数据集成任务，获取数据的图形配置文件并管理文件。
* [Kettle](https://github.com/pentaho/pentaho-kettle)：一款开源的ETL工具，可以用它来对数据进行抽取、清洗和转换操作，主作者是Matt Casters。
* [Smart Kettle](https://gitee.com/yaukie/smartkettle)：本产品是基于开源Kettle自研的Kettle核心接口调用基础组件。
* [Scriptella](https://github.com/scriptella/scriptella-etl)：Scriptella是一个用Java编写的开源ETL和脚本执行工具。
* [Apatar](https://www.altoros.com/blog/tag/apatar/)：Apatar是一个开源的数据抽取、转换、装载(ETL)项目。
* [Flowman](https://github.com/dimajix/flowman)：Flowman是一个由Apache Spark支持的ETL框架，简化了复杂数据管道的开发。
* [WhiteRabbit](https://github.com/OHDSI/WhiteRabbit)：WhiteRabbit是一个小型应用程序，可用于分析数据库的结构和内容，为设计ETL做准备，由OHDSI开源。
* [DataPull](https://github.com/homeaway/datapull)：DataPull是一种自助式分布式ETL工具，用于连接和转换来自异构数据存储的数据。

## CDC组件

* [Debezium](https://github.com/debezium/debezium)：Debezium是一个开源项目，为CDC提供低延迟数据流平台，由RedHat开源。
* [Flink CDC Connectors](https://github.com/ververica/flink-cdc-connectors)：CDC Connectors是Flink的一组源连接器，使用CDC从不同数据库中获取变更。
* [Oracdc](https://github.com/averemee-si/oracdc)：Oracdc是一个用于异构IT环境中近实时数据集成和复制的软件包。
* [TiBigData](https://github.com/tidb-incubator/TiBigData)：适用于TiDB、Presto、Flink和MapReduce连接器的其他大数据组件。
* [Hoptimator](https://github.com/linkedin/Hoptimator)：Hoptimator是一个基于SQL的复杂数据管道控制平面，由LinkedIn开源。
* [SpinalTap](https://github.com/airbnb/SpinalTap)：SpinalTap是一种通用的CDC服务，能够跨不同数据源低延迟地检测数据突变，并将其作为标准化事件传播给下游消费者，由Airbnb开源。

## 数据库中间件

* [DataX](https://github.com/alibaba/DataX)：DataX是阿里云DataWorks数据集成的开源版本，在阿里巴巴集团内被广泛使用的离线数据同步工具/平台。
* [Databus](https://github.com/linkedin/databus)：Databus是一个与源无关的分布式变更数据捕获系统，它是LinkedIn数据处理管道的组成部分。
* [Canal](https://github.com/alibaba/canal)：阿里开发的基于数据库增量日志解析，提供增量数据订阅&消费的中间件。
* [Otter](https://github.com/alibaba/otter)：阿里开源的一个分布式数据库同步系统，尤其是在跨机房数据库同步方面，有很强大的功能。
* [DRC](https://github.com/ctripcorp/drc)：DRC(Data Replicate Center)是携程框架架构研发部数据中心组推出的用于数据双向或多向复制的数据库中间件。
* [Puma](https://github.com/dianping/puma)：获取数据库的变更并通过消息方式发布，并且可以实现数据库同步，由大众点评开源。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：Apache ShardingSphere是一种分布式SQL事务和查询引擎，允许在任何数据库上进行数据分片、扩展、加密等，由当当网开源。
* [Cobar](https://github.com/alibaba/cobar)：Cobar是分库分表的代理，兼容MySQL协议和MySQL SQL语法，底层存储仅支持MySQL，支持前台业务更简单、稳定、高效、安全，由阿里开源。
* [TSharding](https://github.com/baihui212/tsharding)：TSharding是蘑菇街交易平台使用的简单分片组件。
* [DBLE](https://github.com/actiontech/dble)：DBLE是由爱可生开发的一种高扩展性的MySQL分片中间件。
* [Gizzard](https://github.com/twitter-archive/gizzard)：用于创建最终一致的分布式数据存储的灵活分片框架，由Twitter开源。
* [Mycat2](https://github.com/MyCATApache/Mycat2)：Mycat2是Mycat社区开发的一款分布式关系型数据库(中间件)。
* [Heisenberg](https://github.com/brucexx/heisenberg)：Heisenberg是百度开源的一款基于MySQL协议之上的分库分表中间件，支持各种灵活的分库分表规则。
* [Ctrip DAL](https://github.com/ctripcorp/dal)：Ctrip DAL是携程框架部开发的数据库访问框架，支持代码生成和水平扩展。
* [Oceanus](https://github.com/wuba/Oceanus)：58同城数据库中间件，功能简单、易于上手。
* [MySQL Binary Log Connector](https://github.com/shyiko/mysql-binlog-connector-java)：MySQL二进制日志连接器。
* [TDDL](https://github.com/alibaba/tb_tddl)：TDDL是一个分布式数据库中间件，主要是为了解决分布式数据库产生的相关问题，由阿里开源。
* [Elasticsearch JDBC](https://github.com/jprante/elasticsearch-jdbc)：JDBC导入器允许从JDBC源获取数据以索引到Elasticsearch中。
* [Zebra](https://github.com/Meituan-Dianping/Zebra)：Zebra是一个基于JDBC API协议上开发出的高可用、高性能的数据库访问层解决方案，是美团点评内部使用的数据库访问层中间件。
* [ToroDB Stampede](https://github.com/torodb/stampede)：Stampede可将NoSQL数据从MongoDB副本集转换为PostgreSQL中的关系数据库。
* [Sharding Method](https://github.com/QNJR-GROUP/sharding-method)：分表分库的新思路-服务层Sharding框架，全SQL、全数据库兼容，由齐牛金融开源。
* [Redis Replicator](https://github.com/leonchen83/redis-replicator)：Redis复制工具，支持同步、psync、psync2，可以解析RDB、AOF、混合RDB和AOF文件。
* [Yugong](https://github.com/alibaba/yugong)：阿里巴巴去Oracle数据迁移同步工具。
* [ReplicaDB](https://github.com/osalvador/ReplicaDB)：ReplicaDB是用于数据库复制的开源工具，旨在在关系型数据库和非关系型数据库之间高效传输批量数据。
* [Ptubes](https://github.com/meituan/ptubes)：一款基于PITR的数据库容灾产品，可以用来将整个数据库恢复到特定时间点，美团开源。
* [Tapdata](https://github.com/tapdata/tapdata)：Tapdata是一个实时数据集成平台，可以实现数据库、SaaS服务、应用程序、文件等各种系统之间的数据实时同步，由钛铂数据开源。
* [esProc](https://github.com/SPLWare/esProc)：esProc SPL是一种用于数据处理的脚本语言，具有精心设计的丰富的库函数和强大的语法，可以通过JDBC接口在Java程序中执行并独立计算。
* [Mondrian](https://github.com/pentaho/mondrian)：Mondrian是一款在线分析处理(OLAP)服务器，使业务用户能够实时分析大量数据。
* [Coral](https://github.com/linkedin/coral)：Coral是一个SQL翻译、分析和重写引擎，由LinkedIn开源。
* [Elasticsearch SQL](https://github.com/NLPchina/elasticsearch-sql)：使用SQL查询Elasticsearch。
* [Porter](https://github.com/sxfad/porter)：Porter是一款数据同步中间件，主要用于解决同构/异构数据库之间的表级别数据同步问题，由随行付开源。
* [SymmetricDS](https://github.com/JumpMind/symmetric-ds)：SymmetricDS是数据库复制和文件同步软件，它独立于平台、支持Web且与数据库无关。
* [Stargate](https://github.com/stargate/stargate)：Stargate是部署在客户端应用程序和Cassandra数据库之间的数据网关，DataStax开源。
* [Tunnel](https://github.com/hellobike/tunnel)：Tunnel是一个将PostgreSQL的实时数据同步到ES或Kafka的服务，哈啰单车开源。
* [DataLink](https://github.com/ucarGroup/DataLink)：DataLink是一个满足各种异构数据源之间的实时增量同步、离线全量同步，分布式、可扩展的数据交换平台，由神州优车开源。
* [DBSyncer](https://gitee.com/ghi/dbsyncer)：DBSyncer是一款开源的数据同步中间件，提供MySQL、Oracle、SqlServer、PostgreSQL、Elasticsearch(ES)、Kafka、File、SQL等同步场景。
* [DBSwitch](https://gitee.com/dromara/dbswitch)：DBSwitch工具提供源端数据库向目的端数据库的批量迁移同步功能，支持数据的全量和增量方式同步，由dromara社区开源。
* [Mongeez](https://github.com/mongeez/mongeez)：Mongeez允许你管理Mongo文档的更改，并在执行部署时与代码更改同步传播这些更改。
* [Raigad](https://github.com/Netflix/Raigad)：用于ElasticSearch备份/恢复、自动部署和集中配置管理的协同进程，由Netflix开源。
* [Morf](https://github.com/alfasoftware/morf)：Morf是一个用于跨平台演化关系型数据库机制、数据库访问和数据库成像/克隆的库。
* [Binlog4j](https://gitee.com/dromara/binlog4j)：基于Java的轻量级MySQL(Mariadb) Binlog客户端，由dromara社区开源。
* [Compass](https://github.com/sogou-biztech/compass)：Compass是搜狗商业平台研发部开发的一套轻量级的分布式数据库访问框架。
* [Open Replicator](https://github.com/whitesock/open-replicator)：Open Replicator是一个用Java编写的高性能MySQL binlog解析器。
* [DataSQRL](https://github.com/DataSQRL/sqrl)：DataSQRL将SQL编译为优化的数据管道和数据微服务，从而消除了集成和调整具有多个步骤或组件的数据架构的手动工作。
* [SQLCommenter](https://github.com/google/sqlcommenter)：SQLCommenter是一套中间件/插件，使你的ORM能够在执行之前扩充SQL语句，并使用包含有关导致其执行的代码的信息的注释，由Google开源。

## 数据湖框架

* [Apache Hudi](https://github.com/apache/hudi)：Apache Hudi是一个事务性数据湖平台，可为数据湖带来数据库和数据仓库功能，由Uber开源。
* [LakeSoul](https://github.com/lakesoul-io/LakeSoul)：LakeSoul是一个云原生Lakehouse框架，支持可扩展的元数据管理、ACID事务、高效灵活的更新插入操作、模式演化以及统一的流和批处理，由数元灵科技开源。
* [Apache Paimon](https://github.com/apache/incubator-paimon)：Apache Paimon是一种Lake格式，可以使用Flink和Spark构建实时Lakehouse架构，以进行流式处理和批处理操作。
* [Apache Iceberg](https://github.com/apache/iceberg)：Iceberg是一种适用于大型分析表的高性能格式，由Netflix开源。
* [Delta](https://github.com/delta-io/delta)：Delta Lake是一个开源存储框架，支持使用Spark、PrestoDB、Flink、Trino和Hive等计算引擎以及Scala、Java、Rust、Ruby和Python的API构建Lakehouse架构，由Databricks开源。
* [Kylo](https://github.com/Teradata/kylo)：Kylo是一个企业级现代数据湖管理软件平台，适用于Teradata、Apache Spark或Hadoop等大数据引擎，由Teradata开源。
* [Nessie](https://github.com/projectnessie/nessie)：Nessie使你能够维护数据的多个版本，并为你的数据湖利用类似Git的分支和标签，由Dremio团队开源。
* [Amoro](https://github.com/apache/amoro)：Apache Amoro是一个基于开放数据湖格式构建的Lakehouse管理系统，由网易开源。
* [Herd](https://github.com/FINRAOS/herd)：Herd是云的大数据治理，Herd统一数据目录有助于将云中的存储与计算分开，由美国金融业监管局开源。
* [Dremio](https://github.com/dremio/dremio-oss)：Dremio是一个开源且简单的数据湖库，提供自助式SQL分析、数据仓库性能和功能以及涵盖所有数据的数据湖灵活性。
* [OpenHouse](https://github.com/linkedin/openhouse)：OpenHouse是一个开源控制平面，旨在高效管理开放数据Lakehouse部署中的表，由LinkedIn开源。
* [Pixels](https://github.com/pixelsdb/pixels)：Pixels的核心是专为数据湖和数据仓库设计的列式存储引擎。
* [Apache XTable](https://github.com/apache/incubator-xtable)：Apache XTable是一种表格式的跨表转换器，可促进跨数据处理系统和查询引擎的全方位互操作性，由Onehouse开源。

## 消息中间件

* [Apache Kafka](https://github.com/apache/kafka)：Apache Kafka是一个开源分布式事件流平台，已被数千家公司用于高性能数据管道、流分析、数据集成和关键任务应用程序，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：Apache Pulsar是一个分布式Pub-Sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API，由Yahoo开源。
* [Apache ActiveMQ](https://github.com/apache/activemq)：Apache ActiveMQ是一个高性能的消息代理。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：Apache RocketMQ是一个分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性，由阿里开源。
* [QMQ](https://github.com/qunarcorp/qmq)：QMQ是去哪儿网内部广泛使用的消息中间件。
* [PMQ](https://github.com/ppdaicorp/pmq)：PMQ是信也科技自研的一款轻量级分布式消息队列，能够保证消息的不丢失，具有部署和运维简单的特性。
* [JeroMQ](https://github.com/zeromq/jeromq)：JeroMQ是ZeroMQ的纯Java实现，由iMatix开源。
* [TubeMQ](https://github.com/apache/inlong/tree/master/inlong-tubemq)：TubeMQ是一个万亿级分布式消息中间件，由腾讯大数据团队开源。
* [AutoMQ](https://github.com/AutoMQ/automq)：AutoMQ是基于云原生重新设计的新一代Kafka发行版，由阿里提供。
* [DDMQ](https://github.com/didi/DDMQ)：DDMQ是滴滴基础设施团队基于Apache RocketMQ打造的分布式消息产品。
* [BifroMQ](https://github.com/baidu/bifromq)：BifroMQ是一种高性能、分布式MQTT代理实现，可无缝集成原生多租户支持，由百度开源。
* [JGroups](https://github.com/belaban/JGroups)：JGroups是一个用于可靠消息传递的工具包，它可用于创建节点可以相互发送消息的集群，由RedHat开源。
* [Kestrel](https://github.com/twitter-archive/kestrel)：Kestrel是一个简单分布式消息队列，增加了Actor和JVM提供的可扩展性，由Twitter开源。
* [JoyQueue](https://github.com/jd-opensource/joyqueue)：JoyQueue是一个性能卓越的云原生生产就绪消息平台，由京东开源。
* [HornetQ](https://github.com/hornetq/hornetq)：HornetQ是一个开源项目，用于构建多协议、可嵌入、高性能、集群、异步消息传递系统，由JBoss社区开发。
* [XXL-MQ](https://gitee.com/xuxueli0323/xxl-mq)：XXL-MQ是一款轻量级分布式消息队列，拥有水平扩展、高可用、海量数据堆积、单机TPS过10万、毫秒级投递等特性。
* [SwiftMQ](https://github.com/iitsoftware/swiftmq-ce)：SwiftMQ CE是一个功能齐全的企业消息传递系统。
* [Metamorphosis](https://github.com/killme2008/Metamorphosis)：Metamorphosis是淘宝开源的一个Java消息中间件。
* [ElasticMQ](https://github.com/softwaremill/elasticmq)：ElasticMQ是一个消息队列系统，提供基于Actor的Scala和SQS兼容的REST接口，由SoftwareMill开源。
* [Hermes](https://github.com/ctripcorp/hermes)：携程异步消息队列解决方案。
* [Eclipse OpenMQ](https://github.com/eclipse-ee4j/openmq)：Eclipse OpenMQ是一个完整的面向消息的中间件平台，提供高质量、企业级消息传递。
* [JORAM](https://joram.ow2.io/)：JORAM是JMS API规范的开源Java实现(符合Java 11至21以及JMS 1.1、2.0和3.0)，由格勒诺布尔大学开源。
* [Hermes](https://github.com/allegro/hermes)：Hermes是一个构建在Kafka之上的异步消息代理，由波兰最大电商Allegro开源。
* [Apache Qpid](https://github.com/apache/qpid)：Apache Qpid是一个功能强大的开源消息代理，由摩根大通开源。
* [MemQ](https://github.com/pinterest/memq)：MemQ是高效、可扩展的云原生PubSub系统，由Pinterest开源。
* [LCM](https://github.com/lcm-proj/lcm)：LCM是一组用于消息传递和数据编组的库和工具，针对高带宽和低延迟至关重要的实时系统，由MIT开源。
* [DeFiBus](https://github.com/WeBankFinTech/DeFiBus)：DeFiBus是基于开源消息中间件打造的安全可控的分布式金融级消息总线，由微众开源。
* [Ytk-mp4j](https://github.com/kanyun-inc/ytk-mp4j)：Ytk-mp4j是一个快速、用户友好、跨平台、多进程、多线程的集体消息传递Java库，用于分布式机器学习，由看云控股技术团队开源。
* [FolkMQ](https://gitee.com/noear/folkmq)：FolkMQ内存型消息中间件，支持快照持久化和Broker集群模式。

## Kafka生态

* [CMAK](https://github.com/yahoo/CMAK)：CMAK是用于管理Apache Kafka集群的工具，由Yahoo开源。
* [Kafka-UI](https://github.com/provectus/kafka-ui)：用于管理Apache Kafka集群的多功能、快速且轻量级的Web UI。
* [uReplicator](https://github.com/uber/uReplicator)：uReplicator提供了高性能、可扩展、稳定的Kafka复制解决方案，由Uber开源。
* [AKHQ](https://github.com/tchiotludo/akhq)：用于Apache Kafka的Kafka GUI，可以管理主题、主题数据、消费者组、模式注册表、连接等等。
* [KnowStreaming](https://github.com/didi/KnowStreaming)：Know Streaming是一套云原生的Kafka管控平台，脱胎于众多互联网内部多年的Kafka运营实践经验，专注于Kafka运维管控、监控告警、资源治理、多活容灾等核心场景，由滴滴开源。
* [EFAK](https://github.com/smartloli/EFAK)：EAFK是一个开源的Kafka集群管理和监控工具，旨在帮助用户更好地管理和监控其Kafka集群。
* [Cruise-control](https://github.com/linkedin/cruise-control)：Cruise Control是一款帮助大规模运行Apache Kafka集群的产品，由LinkedIn开源。
* [KCenter](https://github.com/xaecbd/KCenter)：KCenter是一个统一的Apache Kafka集群管理维护、生产者/消费者监控、生态组件使用的一站式平台。
* [Kstreamplify](https://github.com/michelin/kstreamplify)：Kstreamplify是一个Java库，使你能够快速创建基于Kafka Stream的应用程序，并提供许多附加高级功能，由米其林开源。
* [Kafka-Sprout](https://github.com/oslabs-beta/Kafka-Sprout)：Kafka Sprout是一个Web GUI，可以帮助你在本地计算机上快速启动Zookeeper和Kafka服务器，无需任何代码配置。
* [Xinfra-Monitor](https://github.com/linkedin/kafka-monitor)：Xinfra Monitor是一个在真实集群中实现和执行长时间运行的kafka系统测试的框架，由LinkedIn开源。
* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry)：Kafka的Confluence模式注册中心。
* [Kafdrop](https://github.com/HomeAdvisor/Kafdrop)：Kafdrop是一个用于监控Apache Kafka集群的UI。
* [Mirus](https://github.com/salesforce/mirus)：Mirus是Apache Kafka的跨数据中心数据复制工具，由Salesforce开源。
* [Kafdrop](https://github.com/obsidiandynamics/kafdrop)：Kafdrop是一个用于查看Kafka主题和浏览消费者组的Web UI。
* [Jikkou](https://github.com/streamthoughts/jikkou)：Jikkou是一款开源工具，旨在提供一种高效且简单的方法来管理、自动化和配置事件流平台上的资源。
* [Strimzi](https://github.com/strimzi/strimzi-kafka-operator)：Strimzi提供了一种在Kubernetes或OpenShift上以各种部署配置运行Kafka集群的方法，由RedHat开源。
* [Julie](https://github.com/kafka-ops/julie)：JulieOps帮助你自动化管理Apache Kafka中的事物，从主题、配置到元数据，以及访问控制、模式。
* [Decaton](https://github.com/line/decaton)：Decaton是一个构建在Apache Kafka之上的流式任务处理框架，由Line开源。
* [Kafka REST Proxy](https://github.com/confluentinc/kafka-rest)：Kafka REST Proxy为Kafka集群提供RESTful接口，它可以轻松地生成和消费数据、查看集群状态以及执行管理操作，而无需使用本机Kafka协议或客户端，由Confluent开源。
* [Reactor Kafka](https://github.com/reactor/reactor-kafka)：Reactor响应式Kafka驱动程序。
* [DoctorK](https://github.com/pinterest/DoctorK)：DoctorK是一个用于Kafka集群自动修复和工作负载平衡的服务，由Pinterest开源。
* [Kroxylicious](https://github.com/kroxylicious/kroxylicious)：Kroxylicious是Kafka协议代理，可解决加密、多租户和模式验证等用例。
* [Zilla](https://github.com/aklivity/zilla)：Zilla将Apache Kafka抽象为Web应用程序、物联网客户端和微服务。
* [Chaperone](https://github.com/uber-archive/chaperone)：Chaperone作为Kafka审计系统，监控数据流的完整性和延迟，由Uber开源。
* [Azkarra Streams](https://github.com/streamthoughts/azkarra-streams)：Azkarra Streams是一个轻量级Java框架，可以轻松开发和操作Kafka Streams应用程序。
* [Kafka-Helmsman](https://github.com/teslamotors/kafka-helmsman)：Kafka-Helmsman是一个专注于自动化Kafka部署的工具，由特斯拉开源。
* [Kafbat UI](https://github.com/kafbat/kafka-ui)：Kafbat UI是一个免费的开源Web UI，用于监控和管理Apache Kafka集群。
* [Klaw](https://github.com/Aiven-Open/klaw)：Klaw是一个自助式Apache Kafka主题管理/治理工具/门户，由Aiven开源。

## 分布式组件

* [Oracle Coherence Community Edition](https://github.com/oracle/coherence)：Coherence是一个可扩展、容错、云就绪的分布式平台，用于构建基于网格的应用程序并可靠地存储数据，由Oracle开源。
* [Brooklin](https://github.com/linkedin/brooklin)：Brooklin是一个分布式系统，旨在在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，由LinkedIn开发。
* [Hive2Hive](https://github.com/Hive2Hive/Hive2Hive)：Hive2Hive是一个用Java编写的开源库，用于安全、分布式、基于P2P的文件同步和共享。
* [Waltz](https://github.com/wepay/waltz)：Waltz是一种基于仲裁的分布式预写日志，用于复制事务，由WePay开源。
* [Dynein](https://github.com/airbnb/dynein)：Airbnb开源的分布式延迟作业排队系统。
* [Sparrow](https://github.com/radlab/sparrow)：Sparrow是一个高吞吐量、低延迟、容错的分布式集群调度器，由加州大学伯克利分校开源。
* [Concourse](https://github.com/cinchapi/concourse)：Concourse是一个分布式数据库仓库，用于跨时间的事务搜索和分析。
* [Onyx](https://github.com/onyx-platform/onyx)：分布式、无主、高性能、容错数据处理。
* [Apache Fluo](https://github.com/apache/fluo)：一个分布式处理系统，允许用户对大型数据集进行增量更新，谷歌Percolator的开源实现。
* [XXL-DEEP](https://github.com/xuxueli/xxl-deep)：分布式企业开发平台，提供整套开箱即用的基础模块。
* [Redis Session Manager](https://github.com/jcoleman/tomcat-redis-session-manager)：Session管理器实现，将Session存储在Redis中，以便在Tomcat服务器集群中轻松分发请求。
* [dCache](https://github.com/dCache/dcache)：dCache是一个用于存储和检索大量数据的系统，这些数据分布在大量异构服务器节点中，在具有多种标准访问方法的单个虚拟文件系统树下。
* [Octobot](https://github.com/cscotta/Octobot)：专为吞吐量、并行性和集群而设计的分布式任务队列工作线程。
* [DIZK](https://github.com/scipr-lab/dizk)：DIZK是一个用于分布式零知识证明系统的Java库。
* [ModeShape](https://github.com/ModeShape/modeshape)：ModeShape是一种分布式、分层、事务性和一致的数据存储，支持查询、全文搜索、事件、版本控制、引用以及灵活的动态模式，由RedHat开源。
* [Dempsy](https://github.com/Dempsy/dempsy)：分布式弹性消息处理系统。
* [Redis Session Manager](https://github.com/chexagon/redis-session-manager)：Tomcat 8会话管理器通过持久化到Redis提供会话复制。
* [Apache HTrace](https://github.com/apache/incubator-retired-htrace)：HTrace是一个用于分布式系统的跟踪框架，由Cloudera开源。
* [DSLabs](https://github.com/emichael/dslabs)：DSLabs是一个用于创建、测试、模型检查、可视化和调试分布式系统实验室作业的新框架，由华盛顿大学开发。
* [Galaxy](https://github.com/puniverse/galaxy)：Galaxy是一个内存数据网格，它的主要功能是将数据对象(存储为简单的字节数组)分布在集群节点之间进行分布式处理。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：Distributor基于Redis实现常用的分布式组件，简单、可靠、开箱即用。
* [Nepxion Aquarius](https://github.com/Nepxion/Aquarius)：Nepxion Aquarius是一款基于Redis + Zookeeper的分布式应用组件集合，包含分布式锁，缓存，ID生成器，限速限流器。
* [COMP Superscalar](https://github.com/bsc-wdc/compss)：COMP Superscalar(COMPS)是一种编程模型，旨在简化分布式基础设施(例如集群、网格和云)的应用程序开发，由巴塞罗那超级计算中心开源。
* [UNICORE](https://www.unicore.eu/)：UNICORE提供了一个可立即运行的系统，使分布式计算和数据资源能够在内联网和互联网上以无缝且安全的方式可用。
* [Imhotep](https://github.com/indeedeng/imhotep)：Imhotep是Indeed打造的大型分析平台。
* [Drasyl](https://github.com/drasyl/drasyl)：Drasyl是一个用于快速开发分布式应用程序的高性能框架，由汉堡大学开源。
* [Hydra](https://github.com/addthis/hydra)：Hydra是最初由AddThis开发的分布式数据处理和存储系统。

## 分布式锁

* [Redisson](https://github.com/redisson/redisson)：Redisson是一个具有内存数据网格功能的Redis Java客户端，包含实现分布式锁的功能。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：ShedLock确保你的计划任务最多同时执行一次。
* [KLock](https://github.com/kekingcn/spring-boot-klock-starter)：基于Redis的分布式锁组件，可以快捷的将分布式锁功能集成到项目中，凯京科技开源。
* [Apache Curator](https://github.com/apache/curator)：Apache Curator是Apache ZooKeeper(分布式协调服务)的Java/JVM客户端库，由Netflix开源。
* [DLock](https://github.com/baidu/dlock)：DLock是Java实现、有效且可靠的分布式锁，由百度开源。
* [Distributed Kit](https://github.com/yujiasun/Distributed-Kit)：基于Redis和Zookeeper分布式工具集，包括分布式锁实现。
* [Lock4j](https://gitee.com/baomidou/lock4j)：Lock4j是一个分布式锁组件，其提供了多种不同的支持以满足不同性能和环境的需求，由baomidou社区开源。
* [Sherlock](https://github.com/coditory/sherlock-distributed-lock)：Sherlock是一个用于JVM项目的分布式锁库，它公开同步和响应式API，并使用数据库连接器来存储锁。
* [Amazon DynamoDB Lock Client](https://github.com/awslabs/amazon-dynamodb-lock-client)：Amazon DynamoDB Lock Client是构建在DynamoDB之上的通用分布式锁库，支持粗粒度和细粒度锁定。
* [Nepxion Aquarius](https://github.com/Nepxion/Aquarius)：Nepxion Aquarius是一款基于Redis + Zookeeper的分布式应用组件集合，包含分布式锁，缓存，ID生成器，限速限流器。
* [Redis Distributed Lock](https://github.com/TaXueWWL/redis-distributed-lock)：Redis分布式锁工具包，提供纯Java方式调用，支持传统Spring工程，也为Spring Boot应用提供了Starter。
* [Distributed Lock](https://github.com/alturkovic/distributed-lock)：使用Spring进行分布式锁的简单实现。
* [WLock](https://github.com/wuba/WLock)：WLock是一套基于一致性算法组件WPaxos实现的高可靠、高吞吐分布式锁服务，由58同城开源。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：Distributor基于Redis实现常用的分布式组件，简单、可靠、开箱即用。

## 分布式事务

* [Seata](https://github.com/apache/incubator-seata)：Seata是一个易于使用、高性能、开源的分布式事务解决方案，由阿里开源。
* [ByteTCC](https://github.com/liuyangming/ByteTCC)：ByteTCC是分布式事务管理器的实现，基于尝试-确认-取消(TCC)机制。
* [Atomikos](https://github.com/atomikos/transactions-essentials)：Java的分布式事务管理库。
* [Narayana](https://github.com/jbosstm/narayana)：Narayana是一个事务工具包，为使用各种基于标准的事务协议开发的应用程序提供支持，JBoss开源。
* [Bitronix](https://github.com/bitronix/btm)：Bitronix是Java Transaction API(JTA) 1.1的简单但完整的实现。
* [EasyTransaction](https://github.com/QNJR-GROUP/EasyTransaction)：EasyTransaction是一个分布式事务解决方案，统一使用TCC、SAGA、FMT、可靠消息、补偿等，由齐牛金融开源。
* [AtlasDB](https://github.com/palantir/atlasdb)：AtlasDB是一个构建在任何通用键值存储之上的事务层，由Palantir开源。
* [Hmily](https://github.com/dromara/hmily)：金融级分布式事务解决方案，由dromara社区开源。
* [TCC Transaction](https://github.com/changmingxie/tcc-transaction)：TCC-Transaction是一款开源的微服务架构下的TCC型分布式事务解决方案，致力于提供高性能和简单易用的分布式事务服务。
* [Multiverse](https://github.com/pveentjer/Multiverse)：JVM的软件事务内存实现。
* [LCN](https://github.com/codingapi/tx-lcn)：LCN分布式事务框架，兼容Dubbo、Spring Cloud、Motan框架，支持各种关系数据库，由CodingAPI组织开源。
* [TAPIR](https://github.com/UWSysLab/tapir)：TAPIR是一种用于线性化分布式事务的新协议，使用复制构建，没有一致性保证，由华盛顿大学CSE系统实验室开源。
* [Apache ServiceComb Pack](https://github.com/apache/servicecomb-pack)：Apache ServiceComb Pack是微服务应用程序的最终数据一致性解决方案，目前提供TCC和Saga分布式事务协调解决方案，使用Alpha作为事务协调器，Omega作为事务代理，由华为开源。
* [Raincat](https://github.com/dromara/raincat)：强一致分布式事务框架，由dromara社区开源。
* [Scalardb](https://github.com/scalar-labs/scalardb)：ScalarDB是一个通用事务管理器。
* [Transaction Outbox](https://github.com/gruelbox/transaction-outbox)：Java Transaction Outbox模式的灵活实现，具有干净、可扩展的API，依赖极少，并且可以与各种数据库平台、事务管理方法和应用程序框架很好地配合。
* [ByteJTA](https://github.com/liuyangming/ByteJTA)：ByteJTA是分布式事务管理器的实现，基于XA/2PC机制。
* [Myth](https://github.com/dromara/myth)：采用消息队列解决分布式事务的开源框架，由dromara社区开源。
* [Eventuate Tram Sagas](https://github.com/eventuate-tram/eventuate-tram-sagas)：使用JDBC/JPA和Spring Boot/Micronaut的Java微服务的Saga框架。
* [Txle](https://github.com/actiontech/txle)：Txle是爱可生开发的分布式事务解决方案，可以保证业务数据的最终一致性。

## ID生成器

* [Leaf](https://github.com/Meituan-Dianping/Leaf)：分布式ID生成服务，由美团开源。
* [Tinyid](https://github.com/didi/tinyid)：Tinyid是一个ID生成器服务，它提供了一个REST API和一个用于获取ids的Java客户端，由滴滴开源。
* [Icicle](https://github.com/intenthq/icicle)：Icicle是一个使用Redis的Lua脚本以分布式方式生成64位、可排序的唯一ID的项目。
* [Sequence](https://gitee.com/yu120/sequence)：高效GUID生成算法，基于Snowflake实现64位自增ID算法。
* [IDWorker](https://github.com/imadcn/idworker)：IDWorker是一个基于Zookeeper和雪花算法的分布式ID生成工具。
* [Redis ID Generator](https://github.com/hengyunabc/redis-id-generator)：基于Redis的分布式ID生成器。
* [UidGenerator](https://github.com/baidu/uid-generator)：UidGenerator是一个Java实现的、基于Snowflake的唯一ID生成器，由百度开源。
* [JNanoId](https://github.com/aventrix/jnanoid)：Java的唯一字符串ID生成器。
* [CosId](https://gitee.com/AhooWang/CosId)：CosId旨在提供通用、灵活、高性能的分布式ID生成器。
* [UUID-Creator](https://github.com/f4b6a3/uuid-creator)：这是一个用于生成通用唯一标识符的Java库。
* [ULID-Creator](https://github.com/f4b6a3/ulid-creator)：这是一个用于生成通用唯一词典可排序标识符的Java库。
* [Java-Snowflak](https://github.com/callicoder/java-snowflake)：基于雪花算法的分布式ID生成器。
* [Apache Commons RNG](https://github.com/apache/commons-rng)：Apache Commons RNG项目提供伪随机生成器的纯Java实现。
* [Java Uuid Generator](https://github.com/cowtowncoder/java-uuid-generator)：JUG是一组用于处理UUID的Java类：使用任何标准方法生成UUID、高效输出、排序等。
* [TSID Creator](https://github.com/f4b6a3/tsid-creator)：用于生成按时间排序的唯一标识符(TSID)的Java库。
* [FastUUID](https://github.com/jchambers/fast-uuid)：FastUUID是一个用于快速有效地解析和写入UUID的Java库。
* [IdGenerator](https://github.com/yitter/IdGenerator)：雪花算法中非常好用的数字ID生成器。
* [FriendlyID](https://github.com/Devskiller/friendly-id)：FriendlyID库将给定的UUID(36个字符)转换为基于Base62(最多22个字符)的URL友好ID。
* [KSUID](https://github.com/ksuid/ksuid)：这是一种生成全局唯一ID的方法，类似于RFC 4122 UUID，但包含时间组件，因此可以按创建时间“粗略”排序它们。
* [Juniper](https://github.com/tommyettinger/juniper)：具有最小依赖的Java伪随机数生成库。
* [ULIDJ](https://github.com/azam/ulidj)：Java的ULID生成器和解析器。
* [Sqids Java](https://github.com/sqids/sqids-java)：Sqids是一个小型库，可让你从数字生成唯一的ID。

## 数据库

这里包含使用Java编写的数据库软件

#### 搜索引擎

* [ElasticSearch](https://github.com/elastic/elasticsearch)：Elasticsearch是一种分布式RESTful搜索引擎，针对生产规模工作负载的速度和相关性进行了优化。
* [Apache Lucene](https://github.com/apache/lucene)：Apache Lucene是一个用Java编写的高性能、全功能的文本搜索引擎库。
* [Apache Solr](https://github.com/apache/solr)：Solr是一款流行、速度极快的开源搜索平台，基于Apache Lucene构建。
* [OpenSearch](https://github.com/opensearch-project/OpenSearch)：OpenSearch是一个基于Apache Lucene的分布式搜索和分析引擎，由Amazon主导。
* [Vespa](https://github.com/vespa-engine/vespa)：Yahoo开源的大数据服务引擎，在服务时存储、搜索、组织大数据并进行机器学习推理。
* [YaCy](https://github.com/yacy/yacy_search_server)：YaCy是一个开源的基于P2P的分布式网页搜索引擎系统，任何人都可以用YaCy为自己建立个人的搜索门户，以实现信息的自由共享。
* [JVector](https://github.com/jbellis/jvector)：JVector是一个纯Java嵌入式矢量搜索引擎，由DataStax Astra DB和Apache Cassandra使用。
* [Linden](https://github.com/XiaoMi/linden)：Linden是一个构建在Lucene之上的分布式实时搜索系统，在小米中被广泛使用。
* [Fess](https://github.com/codelibs/fess)：Fess是一个非常强大且易于部署的企业搜索服务器。
* [Zoie](https://github.com/senseidb/zoie)：Zoie是一个用Java编写的实时搜索/索引系统，由LinkedIn开源。
* [Cleo](https://github.com/LinkedInAttic/cleo)：Cleo是一个灵活的软件库，用于快速开发部分、无序和实时的预输入搜索，由LinkedIn开源。
* [OpenSearchServer](https://github.com/jaeksoft/opensearchserver)：OpenSearchServer是一款功能强大的、基于Lucene的企业级搜索引擎软件。
* [Bobo](https://github.com/senseidb/bobo)：Bobo是一个用Java编写的多面搜索引擎，由LinkedIn开源。
* [Loklak](https://github.com/loklak/loklak_server)：Loklak是一个服务器应用程序，能够从各种来源收集消息，包括Twitter，服务器包含搜索索引和点对点索引共享接口。
* [Kooder](https://gitee.com/koode/kooder)：Kooder是Gitee团队开发的一个代码搜索系统，为Gitee/GitLab/Gitea提供代码搜索服务。
* [IndexTank Engine](https://github.com/LinkedInAttic/indextank-engine)：该项目包含IndexTank搜索引擎实现，包括变量(提升)、类别、分面搜索、片段、自定义评分函数、建议和自动完成等功能，由LinkedIn开源。
* [Anserini](https://github.com/castorini/anserini)：Anserini是一个用于可重复信息检索研究的Lucene工具包。
* [SearchCode](https://github.com/boyter/searchcode-server)：SearchCode是一个功能强大的代码搜索引擎，具有时尚的Web用户界面。
* [Terrier](https://github.com/terrier-org/terrier-core)：Terrier是一个高度灵活、高效且有效的开源搜索引擎，可轻松部署在大规模文档集合上，由格拉斯哥大学计算机科学学院的信息检索小组开发。
* [Indexer4j](https://github.com/haeungun/indexer4j)：Java的简单全文索引和搜索库。
* [Solandra](https://github.com/tjake/Solandra)：Solandra是一个基于Apache Solr和Apache Cassandra构建的实时分布式搜索引擎。
* [Lemur Project](https://www.lemurproject.org/)：Lemur项目开发搜索引擎、浏览器工具栏、文本分析工具和数据资源，以支持信息检索和文本挖掘软件的研究和开发，由马萨诸塞大学阿默斯特分校智能信息检索中心(CIIR)和卡内基梅隆大学语言技术研究所(LTI)发起。
* [Search Framework](https://gitee.com/oschina/search-framework)：这是OSChina网站的全文搜索框架源码。
* [TngouDB](https://gitee.com/397713572/TngouDB)：TngouDB是天狗网开发的中文搜索引擎数据库，用于天狗农业网的农业搜索引擎。
* [Querqy](https://github.com/querqy/querqy)：Querqy是一个在基于Java的搜索引擎中进行查询预处理的框架。
* [MontySolr](https://github.com/adsabs/montysolr)：MontySolr是天体物理数据系统背后的搜索引擎，由哈佛大学和NASA开源。
* [Astra](https://github.com/slackhq/astra)：Astra是一个用于日志、跟踪和审计数据的云原生搜索和分析引擎，由Slack开源。
* [MG4J](https://mg4j.di.unimi.it/)：MG4J是一个用Java编写的免费全文搜索引擎，用于大型文档集合。
* [Zulia](https://github.com/zuliaio/zuliasearch)：Zulia是一个实时分布式搜索和存储系统。
* [Datafari](https://github.com/francelabs/datafari)：Datafari是一个开源企业搜索解决方案，由法国实验室开源。

#### 图数据库

* [Neo4j](https://github.com/neo4j/neo4j)：Neo4j是世界领先的图数据库。
* [JanusGraph](https://github.com/JanusGraph/janusgraph)：JanusGraph是一个高度可扩展的图数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图进行了优化。
* [Apache HugeGraph](https://github.com/apache/incubator-hugegraph)：HugeGraph是一个速度快、高度可扩展的图数据库，该项目正在Apache基金会下孵化，最早由百度开源。
* [Titan](https://github.com/thinkaurelius/titan)：Titan是一个高度可扩展的图形数据库，针对存储和查询分布在多机集群上的数十亿个顶点和边的大型图形进行了优化，由Aurelius开源。
* [Amazon Neptune](https://aws.amazon.com/cn/neptune/)：Amazon Neptune是一个高性能图数据库，并对图的存储和查询进行了优化，可以存储数十亿个关系并将图形查询延迟降低到毫秒级。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型。
* [Apache TinkerPop](https://github.com/apache/tinkerpop)：TinkerPop是一个面向实时事务处理(OLAP)以及批量、分析型图分析(OLTP)的图计算框架，诞生于洛斯阿拉莫斯国家实验室。
* [GraphJet](https://github.com/twitter/GraphJet)：GraphJet是一个实时图处理库，由Twitter开源。
* [GraphDB](https://www.ontotext.com/)：企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。它还支持通过SPARQL对知识图和GraphQL进行SQL JDBC访问。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：支持SQL、Cypher、Gremlin、HTTP/JSON、MongoDB和Redis的多模型DBMS。
* [Stardog](https://www.stardog.com/)：一款商业图数据库。
* [Apache Giraph](https://giraph.apache.org/)：Giraph是一个专为高可扩展性而构建的迭代图处理系统，Facebook基于Pregel思想的开源实现。
* [InfiniteGraph](http://www.objectivity.com/products/infinitegraph/)：InfiniteGraph是一个用Java和C++实现的分布式图数据库，这是Objectivity公司的产品。
* [AnzoGraph](https://cambridgesemantics.com/anzograph/)：AnzoGraph是为在线分析和数据协调而构建的水平可扩展图数据库。
* [Galaxybase](https://galaxybase.com/)：Galaxybase是浙江创邻科技公司研发的分布式图数据库产品。
* [BlazeGraph](https://github.com/blazegraph/database)：Blazegraph是一个超高性能图数据库，支持蓝图和RDF/SPARQL API。
* [AllegroGraph](https://allegrograph.com/)：AllegroGraph是一个闭源的三元组存储，也可用作文档存储，目前用于美国国防部项目。
* [Gaffer](https://github.com/gchq/Gaffer)：Gaffer是一个图数据库框架，它允许存储在节点和边上包含丰富属性的非常大的图，由英国政府通讯总部开源。
* [TypeDB](https://github.com/vaticle/typedb)：TypeDB是一个多态数据库，具有概念数据模型、强大的子类型系统、符号推理引擎和美观优雅的类型理论语言TypeQL，由Vaticle Ltd开发。
* [HyperGraphDB](https://github.com/hypergraphdb/hypergraphdb)：专为人工智能和语义Web项目设计的图数据库，也可以用作各种规模项目的嵌入式面向对象数据库。
* [FlockDB](https://github.com/twitter-archive/flockdb)：FlockDB是一个用于存储邻接列表的分布式图数据库，由Twitter开源。
* [YangDB](https://github.com/YANG-DB/yang-db)：YangDB是一个开源、可扩展、非原生图数据库(由Elasticsearch提供支持)。
* [GalaxyBase](https://galaxybase.com/)：国产高性能图数据库。
* [ONgDB](https://github.com/graphfoundation/ongdb)：一个开源、高性能、原生图存储，包括高可用性集群、ACID事务和Geequel(一种直观的、以模式为中心的图形查询语言)。
* [TuGraph Analytics](https://github.com/TuGraph-family/tugraph-analytics)：TuGraph Analytics是蚂蚁集团开发的开源OLAP图数据库。
* [Bitsy](https://github.com/lambdazen/bitsy)：Bitsy是一个小型、快速、可嵌入、持久的内存图数据库，与Tinkerpop3兼容。
* [OverflowDB](https://github.com/ShiftLeftSecurity/overflowdb)：具有低内存占用的内存图数据库。
* [OhmDB](https://github.com/ohmdb/ohmdb)：OhmDB提供了关系数据库的强大功能和NoSQL数据库的灵活性。
* [Aerospike Graph](https://aerospike.com/products/graph-database/)：用于实时数据的可扩展图数据库，商业软件。
* [AutomataLib](https://github.com/LearnLib/automatalib)：AutomataLib是一个免费的开源Java库，用于对自动机、图形和转换系统进行建模，由德国多特蒙德工业大学开发。
* [GraphScope](https://github.com/alibaba/GraphScope)：GraphScope是阿里巴巴达摩院智能计算实验室研发并开源的一站式图计算平台。
* [HGraphDB](https://github.com/rayokota/hgraphdb)：HGraphDB是使用HBase作为图数据库的客户端层。
* [StarGraph](https://github.com/Lambda-3/Stargraph)：StarGraph是一个用于查询大型知识图的图数据库，由帕绍大学开源。
* [Apache S2Graph](https://github.com/apache/incubator-s2graph)：S2Graph是一个基于Apache HBase构建的分布式、可扩展的OLTP图数据库，支持超大图的快速遍历。
* [Fluree](https://github.com/fluree/db)：Fluree是一个不可变、时态、账本支持的语义图数据库，具有云原生架构。

#### 键值存储

* [Storehaus](https://github.com/twitter/storehaus)：Storehaus是一个可以轻松使用异步键值存储的库，由Twitter开源。
* [Oracle Berkeley DB](https://www.oracle.com/database/technologies/related/berkeleydb.html)：Berkeley DB是一个高效的嵌入式数据库和键值数据库，最初起源于伯克利加州大学，Oracle提供一个纯Java程序编写的Berkeley DB。
* [Hawk](https://github.com/orhanobut/hawk)：适用于Android的安全、简单的键值存储。
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map)：Chronicle Map是一种超快速、内存中、非阻塞键值存储，专为低延迟和/或多进程应用程序(例如交易和金融市场应用程序)而设计。
* [KVStore](https://github.com/ggrandes/kvstore)：KVStore是一个基于B+Tree的Java内存和磁盘键值存储。
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
* [Voldemort](https://github.com/voldemort/voldemort)：Voldemort是一个分布式键值存储系统，Amazon Dynamo的开源克隆，由LinkedIn开源。
* [SwayDB](https://github.com/simerplaha/SwayDB)：用于JVM的持久内存键值存储引擎，旨在实现高性能和资源效率。
* [BBoxDB](https://github.com/jnidzwetzki/bboxdb)：BBoxDB是一个高可用的分布式存储管理器，旨在处理多维大数据。
* [CurioDB](https://github.com/stephenmcd/curiodb)：CurioDB是一个分布式持久Redis克隆，使用Scala和Akka构建。
* [TreodeDB](https://github.com/Treode/store)：TreodeDB是一个提供多行原子写入的分布式数据库，它专为RESTful服务而设计。

#### 时序数据库

* [QuestDB](https://github.com/questdb/questdb)：QuestDB是一个开源时序数据库，可实现高吞吐量摄取和快速SQL查询，并且操作简单。
* [Apache Druid](https://github.com/apache/druid)：Druid是一个高性能、实时分析数据库，可在大规模和负载下对流式和批处理数据提供亚秒级查询，由MetaMarkets开源。
* [OpenTSDB](https://github.com/OpenTSDB/opentsdb)：OpenTSDB是一个分布式、可扩展的时序数据库，基于HBase开发，由StumbleUpon开源。
* [KairosDB](https://github.com/kairosdb/kairosdb)：KairosDB是一个基于Cassandra编写的快速分布式可扩展时序数据库。
* [Atlas](https://github.com/Netflix/atlas)：Atlas由Netflix开发，用于管理多维时序数据，以获得近乎实时的运营洞察。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Timely](https://github.com/NationalSecurityAgency/timely)：Timely是一个时序数据库应用程序，可提供对时间序列数据的安全访问，由美国国家安全局开源。
* [Apache IoTDB](https://github.com/apache/iotdb)：Apache IoTDB是一种物联网原生数据库，具有高性能的数据管理和分析能力，可部署在边缘和云端，该项目由清华大学主导。
* [Newts](https://github.com/OpenNMS/newts)：Newts是一个基于Apache Cassandra的时序数据存储。
* [RRD4J](https://github.com/rrd4j/rrd4j)：RRD4J是一个用于时序数据的高性能数据记录和图形系统，用Java实现RRDTool的功能。
* [Chronicle-TimeSeries](https://github.com/OpenHFT/Chronicle-TimeSeries)：多线程时序库。
* [Heroic](https://github.com/spotify/heroic)：Heroic是一个开源监控系统，最初是在Spotify构建的，旨在解决大规模收集和近实时指标分析所面临的问题。
* [FiloDB](https://github.com/filodb/FiloDB)：FiloDB是一个开源分布式、实时、内存中、大规模可扩展、多模式时序/事件/操作数据库，具有Prometheus查询支持和一些Spark支持。
* [Axibase](https://axibase.com/docs/atsd/finance/)：HBase之上的集成时序数据库，具有内置可视化、规则引擎和SQL支持。
* [TimeBase](https://github.com/finos/TimeBase-CE)：TimeBase是Deltix公司开发的高性能时序数据库。
* [ChronixDB](https://github.com/ChronixDB/chronix.server)：高效、快速的时序存储。
* [Warp 10](https://github.com/senx/warp10-platform)：Warp 10是一个专为物联网设计的模块化开源平台，可收集、存储并允许你分析传感器数据。

#### 嵌入式数据库

* [H2](https://github.com/h2database/h2database)：H2是一个用Java编写的嵌入式RDBMS。
* [Apache Derby](https://github.com/apache/derby)：Apache Derby是一个开源的嵌入式关系型数据库，完全使用Java语言实现。
* [HSQLDB](https://hsqldb.org/)：HSQLDB是领先的用Java编写的SQL关系数据库系统。
* [QuickIO](https://github.com/artbits/quickio)：QuickIO是一个Java嵌入式数据库，底层基于LevelDB引擎和Java NIO设计，并使用Protostaff来序列化/反序列化数据。
* [MapDB](https://github.com/jankotek/mapdb)：MapDB提供由磁盘存储或堆外内存支持的并发Map、Set、List和Queue，它是一个快速且易于使用的嵌入式Java数据库引擎。
* [ObjectBox](https://github.com/objectbox/objectbox-java)：ObjectBox是一个简单但功能强大的数据库，专为Java和Kotlin设计。
* [Xodus](https://github.com/JetBrains/xodus)：JetBrains Xodus是一种用Java和Kotlin编写的事务型无模式嵌入式数据库。
* [SirixDB](https://github.com/sirixdb/sirix)：SirixDB是一个可嵌入、双时态、仅附加的数据库系统和事件存储，存储不可变的轻量级快照。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：LMDB是一种使用B+树的有序、嵌入式、持久的键值存储。
* [Nitrite](https://github.com/nitrite/nitrite-java)：Nitrite数据库是一个开源NoSQL嵌入式文档存储，它支持内存中和基于文件的持久存储。
* [JDBM3](https://github.com/jankotek/JDBM3)：JDBM提供TreeMap、HashMap等由磁盘存储备份的集合。
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
* [VoltDB](https://github.com/VoltDB/voltdb)：VoltDB是一种水平可扩展的内存中SQL RDBMS，专为具有极高读写吞吐量要求的应用程序而设计。
* [NuoDB](https://www.3ds.com/nuodb-distributed-sql-database/)：NuoDB是一个分布式云原生数据库管理系统，具有丰富的SQL实现并完全支持兼容事务，由达索开发。
* [ArcadeDB](https://github.com/ArcadeData/arcadedb)：ArcadeDB是一个多模型DBMS，能够在通用硬件上每秒处理数百万条记录，并使用最少的资源。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [Deephaven Community](https://github.com/deephaven/deephaven-core)：Deephaven Community是一个实时、时序、面向列的分析引擎，具有关系型数据库功能。
* [KarelDB](https://github.com/rayokota/kareldb)：KarelDB是一个由Apache Kafka支持的全功能关系型数据库。
* [H-Store](https://github.com/apavlo/h-store)：H-Store是一个实验性主存并行数据库管理系统，针对OLTP应用程序进行了优化，它是一个高度分布式、基于行存储的关系型数据库，这是麻省理工学院、布朗大学、卡内基梅隆大学、耶鲁大学和英特尔之间的合作项目。
* [SimpleDB](https://github.com/iamxpy/SimpleDB)：加州大学伯克利分校的数据库课程CS186实现。
* [Simple-DB-HW-2021](https://github.com/MIT-DB-Class/simple-db-hw-2021)：MIT数据库课程6.830实现。
* [AntsDB](https://github.com/waterguo/antsdb)：AntsDB是HBase的低延迟、高并发虚拟SQL层。
* [Wasp](https://github.com/alibaba/wasp)：Wasp是类Google MegaStore & F1的分布式关系型数据库，由阿里开源。
* [Sqlg](https://github.com/pietermartin/sqlg)：Sqlg是Tinkerpop3在RDBMS上的实现，支持H2、HSQLDB、Postgresql。
* [VanillaDB](https://github.com/vanilladb/vanillacore)：VanillaCore是一个单节点、多线程关系数据库引擎，部分支持SQL-92标准，并通过JDBC、嵌入或(基于Java的)存储过程提供连接。
* [CreatorDB](https://github.com/CreatorsStack/CreatorDB)：CreatorDB是一个DBMS数据库管理系统，包含存储、算子、优化、事务、索引等。

#### NoSQL数据库

* [Apache Cassandra](https://github.com/apache/cassandra)：Apache Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，这是Google Bigtable的开源版本。
* [Apache IoTDB](https://github.com/apache/iotdb)：Apache IoTDB是时序数据的数据管理系统，为用户提供数据采集、存储、分析等特定服务，该项目由清华大学主导。
* [Apache Ignite](https://github.com/apache/ignite)：Apache Ignite是一个分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是一个开源多模型NoSQL DBMS，支持原生图、文档、全文搜索、响应式、地理空间和面向对象的概念。
* [Paper](https://github.com/pilgr/Paper)：Paper是Android上Java/Kotlin对象的快速类NoSQL存储，具有自动模式迁移支持。
* [Lealone](https://github.com/lealone/Lealone)：Lealone是一个高性能的面向OLTP场景的关系数据库，由阿里开源。
* [DingoDB](https://github.com/dingodb/dingo)：DingoDB是一个分布式多模态向量数据库，它结合了数据湖和矢量数据库的功能，允许存储任何类型的数据，由九章云极开源。
* [ToroDB](https://github.com/torodb/server)：ToroDB Server是一个运行在RDBMS之上的开源NoSQL数据库。
* [ElephantDB](https://github.com/nathanmarz/elephantdb)：ElephantDB是一个专门从Hadoop导出键/值数据的数据库。
* [Elassandra](https://github.com/strapdata/elassandra)：Elassandra是一个Apache Cassandra发行版，包括Elasticsearch搜索引擎。
* [Sensei](https://github.com/LinkedInAttic/sensei)：Sensei是一个分布式、弹性的实时可搜索数据库，由LinkedIn开源。
* [LevelDB](https://github.com/dain/leveldb)：Java中LevelDB的重写，此目标是拥有一个功能完整的实现，其性能与C++原始版本的性能相差不超过10%，并生成C++代码的逐字节精确副本。
* [EXistDB](https://github.com/eXist-db/exist)：EXistDB是一个高性能开源原生XML数据库，完全围绕XML技术构建的NoSQL文档数据库和应用程序平台。
* [CorfuDB](https://github.com/CorfuDB/CorfuDB)：Corfu是一个围绕共享日志抽象设计的一致性平台。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源数据网格平台和高度可扩展的NoSQL云数据存储，由RedHat开源。
* [Datomic](https://www.datomic.com/)：Datomic是一个分布式数据库和Datalog的实现。
* [BlobCityDB](https://github.com/blobcity/db)：BlobCityDB是一种一体化数据库，它支持本地存储17种不同格式的数据，包括JSON、XML、CSV、PDF、Word、Excel、Log、GIS、图像等。
* [EvitaDB](https://github.com/FgForrest/evitaDB)：EvitaDB是一个低延迟的NoSQL内存引擎，可以处理电子商务系统每天必须处理的所有复杂任务，由FG Forrest和赫拉德茨克拉洛韦大学开源。
* [Terrastore](https://code.google.com/archive/p/terrastore/)：Terrastore是一个现代文档存储，它提供先进的可扩展性和弹性功能，而不牺牲一致性。
* [JasDB](https://github.com/oberasoftware/jasdb)：JasDB是一款超快的多平台NoSQL数据库，可以嵌入到你的软件中或进行扩展，并且还具有完整的Android支持。
* [InfinityDB](https://boilerbay.com/infinitydb/manual/)：InfinityDB Embedded是一个Java NoSQL DBMS组件，其灵活性远超文档数据库，由加州大学开源。

#### OLAP数据库

* [Apache Druid](https://github.com/apache/druid)：Druid是一个高性能、实时分析数据库，可在大规模和负载下对流式和批处理数据提供亚秒级查询，由MetaMarkets开源。
* [Apache Doris](https://github.com/apache/doris)：Apache Doris是一个基于MPP架构的易于使用、高性能、实时分析的数据库，由百度开源。
* [StarRocks](https://github.com/StarRocks/starrocks)：StarRocks是Linux基金会的一个项目，是下一代数据平台，旨在使数据密集型实时分析变得快速、轻松，由百度Doris团队成员开源。
* [Apache Pinot](https://github.com/apache/pinot)：Apache Pinot是一种实时分布式OLAP数据存储，由领英开源。
* [Apache Kylin](https://github.com/apache/kylin)：Apache Kylin是一个面向Hadoop和云的统一且强大的OLAP平台，由eBay贡献。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式SQL数据库，可以轻松地实时存储和分析大量数据。
* [COOL](https://github.com/COOL-cohort/COOL)：COOL是一种非常高效的OLAP引擎，用于对时序数据进行队列和OLAP分析。

#### 对象数据库

* [ObjectDB](https://www.objectdb.com/)：ObjectDB是Java的对象数据库，可以在客户端-服务器模式和嵌入式模式下使用。
* [Atoti](https://www.atoti.io/)：Atoti是一个数据分析平台，集一流的计算引擎、可视化套件和实时OLAP多维数据集于一体，由ActiveViam开发。

#### Datalog数据库

* [DataScript](https://github.com/tonsky/datascript)：Clojure和ClojureScript中的不可变内存数据库和Datalog查询引擎。
* [Datalevin](https://github.com/juji-io/datalevin)：Datalevin是一个简单持久的Datalog数据库。
* [Datahike](https://github.com/replikativ/datahike)：Datahike是一个持久的Datalog数据库，由高效的Datalog查询引擎提供支持。

#### 其他数据库

* [XTDB](https://github.com/xtdb/xtdb)：XTDB是一个具有双时态索引的通用数据库。
* [Simbase](https://github.com/guokr/simbase)：Simbase是一个类似Redis的向量相似度数据库，由果壳科技开源。
* [JsonDB](https://github.com/Jsondb/jsondb-core)：JsonDB是一个纯Java数据库，它将数据存储为Json文件。
* [SnappyData](https://github.com/TIBCOSoftware/snappydata)：SnappyData是一个分布式、内存优化分析数据库。
* [Whois](https://github.com/RIPE-NCC/whois)：RIPE NCC受RIPE社区委托维护互联网资源信息数据库。
* [OpenLineage](https://github.com/OpenLineage/openlineage)：OpenLineage是元数据和沿袭收集的开放标准，旨在在作业运行时对其进行检测。
* [KSqlDB](https://github.com/confluentinc/ksql)：KSqlDB是一个用于在Kafka之上构建流处理应用程序的数据库，由Confluent开源。
* [Polypheny-DB](https://github.com/polypheny/Polypheny-DB)：Polypheny-DB是一种自适应Polystore，可提供对异构数据的成本和工作负载感知访问，最初是巴塞尔大学的一个研究项目。
* [EmoDB](https://github.com/bazaarvoice/emodb)：EmoDB是一个RESTful HTTP服务器，用于存储JSON对象并监视这些事件的更改，由Bazaarvoice开源。
* [RSQLDB](https://github.com/alibaba/rsqldb)：RSQLDB是一个基于RocketMQ的流处理数据库，由阿里开源。
* [Apollo Delphinius](https://github.com/salesforce/apollo)：Apollo Delphinius项目是一个实验性多租户分布式系统平台，由Salesforce开源。
* [Cottontail DB](https://github.com/vitrivr/cottontaildb)：Cottontail DB是一个旨在多媒体检索的列存储，它允许经典的布尔和向量空间检索，即相似性搜索中使用的最近邻查找，由巴塞尔大学开源。

## 存储引擎

* [PL/Java](https://github.com/tada/pljava)：PL/Java是一个免费的附加模块，它将Java存储过程、触发器和函数引入PostgreSQL后端。
* [SPAN](https://github.com/americanexpress/SPAN)：SPAN是一个Java框架，它可以帮助开发人员通过提供配置和POJO详细信息来连接存储过程，由美国运通开源。

## 数据库连接池

* [Druid](https://github.com/alibaba/druid)：Druid是一个JDBC组件库，包含数据库连接池、SQL Parser等组件，由阿里云开源。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：HikariCP是一个零开销生产就绪的JDBC连接池。
* [Apache Commons DBCP](https://github.com/apache/commons-dbcp)：Apache下开源的数据库连接池。
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

* [Apache HttpComponents](https://github.com/apache/httpcomponents-core)：Apache HttpComponents项目负责创建和维护专注于HTTP和相关协议的低级Java组件工具集。
* [Apache HttpComponents Client](https://github.com/apache/httpcomponents-client)：Apache开源的HTTP客户端库，相比HttpComponents Core提供更流式的API。
* [Java 11 HttpClient](https://github.com/openjdk/jdk/tree/master/src/java.net.http/share/classes/java/net/http)：JDK提供的HTTP(版本1.1和2)高级客户端接口和WebSocket低级客户端接口。
* [Feign](https://github.com/OpenFeign/feign)：Feign是一个Java到HTTP客户端绑定器，其灵感来自于Retrofit、JAXRS-2.0和WebSocket，由Netflix开源。
* [OkHttp](https://github.com/square/okhttp)：Square为JVM、Android和GraalVM精心设计的HTTP客户端。
* [Retrofit](https://github.com/square/retrofit)：适用于Android和JVM的类型安全HTTP客户端，由Square开源。
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client)：AsyncHttpClient库允许Java应用程序轻松执行HTTP请求并异步处理HTTP响应，该库还支持WebSocket协议。
* [Android Asynchronous HttpClient](https://github.com/android-async-http/android-async-http)：基于Apache HttpClient库的Android异步、基于回调的HTTP客户端。
* [Google HTTP Client](https://github.com/googleapis/google-http-java-client)：Google HTTP Client由Google开源，是一个灵活、高效且功能强大的Java库，用于通过HTTP访问网络上的任何资源。
* [HttpClientUtil](https://github.com/Arronlong/httpclientutil)：该项目是基于HttpClient 4.4.1封装的工具类。
* [Http Request](https://github.com/kevinsawicki/http-request)：一个简单的便利库，用于使用HttpURLConnection发出请求并访问响应。
* [HttpFetch](https://github.com/youzan/httpfetch)：对HTTP请求进行封装，通过对接口函数进行代理，实现优雅的HTTP调用，有赞开源。
* [EasyHttp](https://github.com/getActivity/EasyHttp)：Android网络请求框架，简单易用。
* [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)：基于HTTP协议，封装了OkHttp的网络请求框架，比Retrofit更简单易用。
* [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Java和Android的异步套接字、HTTP(s)和WebSocket库；基于NIO，而不是线程。
* [Chuck](https://github.com/jgilfelt/chuck)：Chuck是一个简单的应用内HTTP检查器，适用于Android OkHttp客户端。
* [Unirest](https://github.com/Kong/unirest-java)：Unirest是一个简化的轻量级HTTP客户端库。
* [HTTP-Kit](https://github.com/http-kit/http-kit)：HTTP-Kit是一个简约且高效的Clojure兼容环的HTTP客户端+服务器。
* [Forest](https://gitee.com/dromara/forest)：Forest是一个高层、极简的声明式HTTP调用API框架，由dromara社区开源。
* [Jetty ReactiveStream HttpClient](https://github.com/jetty-project/jetty-reactive-httpclient)：Jetty HttpClient的响应流包装器。
* [Methanol](https://github.com/mizosoft/methanol)：Java的轻量级HttpClient扩展。
* [Jodd HTTP](https://github.com/oblac/jodd-http)：Jodd HTTP是一个小型、原始的HTTP客户端，但又简单又方便。
* [REST Commander](https://github.com/eBay/restcommander)：REST Commander是一个快速并行异步HTTP/REST/SOAP客户端即服务，用于监视和管理数以万计的Web服务器，由eBay开源。
* [Avaje Http Client](https://github.com/avaje/avaje-http/tree/master/http-client)：JDK 11 HttpClient的轻量级包装器。
* [Jcabi HTTP](https://github.com/jcabi/jcabi-http)：流式的Java HTTP客户端。
* [ESA RestClient](https://github.com/esastack/esa-restclient)：ESA RestClient是一个基于Netty的异步事件驱动的HTTP客户端。
* [Hosebird Client](https://github.com/twitter/hbc)：用于使用Twitter标准Streaming API的Java HTTP客户端，由Twitter开源。
* [FusionAuth HTTP Client](https://github.com/FusionAuth/java-http)：完全用纯Java编写的全功能、独立、高性能HTTP服务器和客户端。
* [Parallec](https://github.com/eBay/parallec)：Parallec是一个基于Akka的快速并行异步HTTP(S)/SSH/TCP/UDP/Ping客户端Java库，由eBay开源。
* [OkHttps](https://gitee.com/troyzhxu/okhttps)：OkHttps是对OkHttp3轻量封装的框架，包括异步预处理器，特色的标签，灵活的上传下载进度监听与过程控制功能。
* [Riptide](https://github.com/zalando/riptide)：Riptide是一个实现客户端响应路由的库，由Zalando开源。
* [RXHttp](https://github.com/liujingxing/rxhttp)：适用于Android的类型安全HTTP客户端，基于OkHttp。
* [HTTP4K](https://github.com/http4k/http4k)：HTTP4K是一个用纯Kotlin编写的轻量级但功能齐全的HTTP工具包，可以以功能一致的方式提供和使用HTTP服务。
* [Netty HTTP Client](https://github.com/timboudreau/netty-http-client)：Java中的异步HTTP客户端，具有干净、基于回调的API，基于Netty 4.x。
* [Jetty HttpClient](https://github.com/eclipse/jetty.project/tree/jetty-10.0.x/jetty-client)：Jetty中执行HTTP和HTTPS请求的模块。
* [Apache HttpAsyncClient Wrapper](https://github.com/puppetlabs/clj-http-client)：这是Apache HttpAsyncClient库的包装器，提供一些额外的功能，用于以与Puppet兼容的方式配置SSL。
* [HTTP4J](https://github.com/IntellectualSites/HTTP4J)：这是Java HttpURLConnection的一个简单、轻量级且小型的包装器。
* [Donkey](https://github.com/AppsFlyer/donkey)：现代Clojure、Ring兼容的HTTP服务器和客户端，专为易用性和性能而设计。
* [HTTPBuilder](https://github.com/jgritman/httpbuilder)：Groovy的简单HTTP客户端。
* [HttpBuilder-NG](https://github.com/http-builder-ng/http-builder-ng)：适用于Groovy(和Java)的简单HTTP客户端。
* [RestVolley](https://github.com/HujiangTechnology/RestVolley)：一个基于Volley和OkHttp的HTTP请求框架，由沪江科技开源。
* [King HttpClient](https://github.com/king/king-http-client)：支持SSE的异步HTTP客户端。
* [Smart HTTP](https://gitee.com/smartboot/smart-http)：Smart HTTP是一款可编程的HTTP应用微内核，方便用户根据自身需求进行服务端或客户端的应用开发。

## RPC框架

* [Apache Dubbo](https://github.com/apache/dubbo)：Apache Dubbo是一个高性能、基于Java的开源RPC框架，由阿里开源。
* [gRPC](https://github.com/grpc/grpc-java)：Google RPC的Java实现，基于HTTP/2的RPC。
* [Finagle](https://github.com/twitter/finagle)：Finagle是JVM的一个可扩展的RPC系统，用于构建高并发服务器，由Twitter开源。
* [Motan](https://github.com/weibocom/motan)：Motan是一个跨语言RPC框架，用于快速开发高性能分布式服务，由微博开源。
* [SOFARPC](https://github.com/sofastack/sofa-rpc)：SOFARPC是一个高性能、高扩展性、生产级的Java RPC框架，由蚂蚁金服开源并广泛使用。
* [Pigeon](https://github.com/dianping/pigeon)：Pigeon是一个分布式RPC框架，在大众点评内部广泛使用。
* [tRPC Java](https://github.com/trpc-group/trpc-java)：tRPC-Java作为tRPC的Java语言实现，是一个久经考验的微服务框架，由腾讯开源。
* [Apache Thrift](https://github.com/apache/thrift)：Thrift是一个轻量级、独立于语言的软件堆栈，用于点对点RPC实现，由Facebook开源。
* [OCTO-RPC](https://github.com/Meituan-Dianping/octo-rpc)：OCTO-RPC是支持Java和C++的企业级通信框架，在RPC服务之上扩展了丰富的服务治理功能，由美团开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint/tree/master/rpc)：Naver开源的RPC框架，服务于Pinpoint。
* [TChannel](https://github.com/uber/tchannel-java)：TChannel协议的Java实现，由Uber开源。
* [Protobuf RPC](https://github.com/baidu/Jprotobuf-rpc-socket)：Protobuf RPC是一种基于TCP协议的二进制RPC通信协议的Java实现，由百度开源。
* [Starlight](https://github.com/baidu/starlight)：Starlight是一套面向云原生的微服务通信框架，兼容Spring生态，由百度开源。
* [NettyRPC](https://github.com/luxiaoxun/NettyRpc)：NettyRpc是一个基于Netty、ZooKeeper和Spring的简单RPC框架。
* [Koalas RPC](https://gitee.com/dromara/koalas-rpc)：dromara社区开源的高可用、可拓展的RPC框架。
* [Kotlinx RPC](https://github.com/Kotlin/kotlinx-rpc)：Kotlinx RPC是一个Kotlin库，用于向应用程序添加RPC服务，由JetBrains开源。
* [IceRPC](https://github.com/zeroc-ice/ice)：IceRPC是一个新的开源RPC框架，可帮助你使用很少的代码构建速度极快的网络应用程序。
* [XXL-RPC](https://github.com/xuxueli/xxl-rpc)：XXL-RPC是一个分布式服务框架，提供稳定高性能的RPC远程服务调用功能。
* [RPC-Framework](https://github.com/Snailclimb/guide-rpc-framework)：RPC-Framework是一款基于Netty + Kyro + Zookeeper实现的自定义RPC框架。
* [JoyRPC](https://github.com/jd-opensource/joyrpc)：JoyRPC是一款基于Java实现的RPC服务框架，由京东开源。
* [Thunder](https://github.com/Nepxion/Thunder)：多协议、多组件、多序列化的分布式RPC调用框架。
* [Sekiro](https://github.com/yint-tech/sekiro-open)：Sekiro是一个RPC框架，主要用于将内网环境的一个API功能发布到公开的外网环境，作为一个RPC API应用市场资源被其他业务方调用，由因体信息开源。
* [ONCRPC4J](https://github.com/dCache/oncrpc4j)：ONCRPC/SUNRPC的纯Java实现。
* [Hprose](https://github.com/hprose/hprose-java)：Hprose是一个高性能远程对象服务引擎。
* [Jupiter](https://github.com/fengjiachun/Jupiter)：Jupiter是一款性能非常不错的，轻量级的分布式服务框架。
* [NettyRPC](https://github.com/tang-jie/NettyRPC)：基于Netty的高性能Java RPC服务器，使用kryo、hessian、protostuff支持消息序列化。

## 响应式

* [RxJava](https://github.com/ReactiveX/RxJava)：RxJava是Reactive Extensions(一个使用可观察序列编写异步和基于事件的程序的库)的JVM实现，由Netflix开源。
* [Project Reactor](https://github.com/reactor/reactor-core)：Reactor是第四代响应式库，基于Reactive Streams规范，用于在JVM上构建非阻塞应用程序。
* [Java 9 Flow](https://docs.oracle.com/javase/9/docs/api/java/util/concurrent/Flow.html)：Java 9中新增的响应式编程API。
* [Spring Webflux](https://github.com/spring-projects/spring-framework/tree/main/spring-webflux)：Spring生态中基于Reactor的异步非阻塞Web框架。
* [Reactive Stream](https://github.com/reactive-streams/reactive-streams-jvm)：Reactive Streams是一项为具有非阻塞背压的异步流处理提供标准的举措。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：Vert.x是一个用于在JVM上构建响应式应用程序的工具包。
* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [Alpakka](https://github.com/akka/alpakka)：Alpakka是一个基于Reactive Streams和Akka的Java和Scala响应式企业集成库。
* [RSocket](https://github.com/rsocket/rsocket-java)：RSocket是一种二进制协议，用于字节流传输，例如TCP、WebSockets和Aeron。
* [Agera](https://github.com/google/agera)：Agera是一组类和接口，可帮助为Android编写函数式、异步式和响应式应用程序，由Google开源。
* [Mobius](https://github.com/spotify/mobius)：Mobius是一个用于管理状态演化和副作用的函数响应式框架，具有用于连接Android UI和RxJava Observables的附加组件，由Spotify开源。
* [Smallrye Mutiny](https://github.com/smallrye/smallrye-mutiny)：Mutiny是一个现代的Java响应式编程库。
* [AutoDispose](https://github.com/uber/AutoDispose)：AutoDispose是一个RxJava 2+工具，用于通过处置/取消自动将RxJava流的执行绑定到提供的作用域，由Uber开源。
* [Store](https://github.com/nytimes/Store)：Store是用于异步数据加载和缓存的Java库。
* [Reaktive](https://github.com/badoo/Reaktive)：Reactive Extensions的Kotlin多平台实现。
* [RSocket JVM](https://github.com/jauntsdn/rsocket-jvm)：RSocket JVM在JVM上提供非常快速的类gRPC和兼容gRPC的服务，并通过多种网络传输提供丰富的流模型。
* [Alibaba RSocket Broker](https://github.com/alibaba/alibaba-rsocket-broker)：Alibaba RSocket Broker是一款基于RSocket协议的响应式对等通讯系统，为通讯多方构建分布式的RPC、Pub/Sub、Streaming等通讯支持。
* [Sqlbrite](https://github.com/square/sqlbrite)：围绕SupportSQLiteOpenHelper和ContentResolver的轻量级包装器，它向查询引入了响应式流语义，由Square开源。
* [StorIO](https://github.com/pushtorefresh/storio)：SQLiteDatabase和ContentResolver的响应式API。
* [RxNetty](https://github.com/ReactiveX/RxNetty)：Netty响应式扩展适配器。
* [Reactive gRPC](https://github.com/salesforce/reactive-grpc)：Reactive gRPC是一套将gRPC与Reactive Streams编程库结合使用的库，由Salesforce开源。
* [QBit](https://github.com/advantageous/qbit)：QBit是一个用于构建微服务的响应式编程库。
* [ScaleCube](https://github.com/scalecube/scalecube-services)：ScaleCube是一个通过提供可嵌入的微服务库来简化响应式和分布式应用程序开发的项目。
* [Reactive-Audit](https://github.com/octo-online/reactive-audit)：旨在为项目实施中使用响应式架构提供帮助的审计工具。
* [CohereFlux](https://github.com/pellse/cohereflux)：CohereFlux是一个响应式、函数式、类型安全和无状态的数据聚合框架，用于查询和合并来自多个数据源/服务的数据。
* [Reactive-Commons](https://github.com/reactive-commons/reactive-commons-java)：Reactive-Commons的目的是提供一组针对不同模式和实践的抽象和实现，这些模式和实践构成了响应式微服务架构的基础。
* [Arez](https://github.com/arez/arez)：Arez是一个简单、高效且可扩展的客户端应用程序状态管理库。

## WebServer

* [Netty](https://github.com/netty/netty)：Netty是一个异步事件驱动的网络应用程序框架，用于快速开发可维护的高性能协议服务器和客户端。
* [Apache Tomcat](https://github.com/apache/tomcat)：Apache Tomcat是Java Servlet、JavaServer Pages、Jav EL和Java WebSocket技术的开源实现。
* [Apache TomEE](https://github.com/apache/tomee)：Apache TomEE是一个轻量级但功能强大的JavaEE应用服务器，具有功能丰富的工具。
* [Helidon Nima](https://github.com/helidon-io/helidon/tree/helidon-3.x/webserver)：Helidon Níma是一个基于JDK虚拟线程的轻量级Web服务器，由Oracle开源。
* [Undertow](https://github.com/undertow-io/undertow)：Undertow是一个基于非阻塞IO的Java Web服务器，由RedHat开源。
* [Wildfly](https://github.com/wildfly/wildfly)：WildFly是一个功能强大、模块化且轻量级的应用程序服务器，由RedHat开源。
* [Oracle Weblogic](https://www.oracle.com/sg/java/weblogic/)：Oracle WebLogic Server是一个统一且可扩展的平台，用于在本地和云中开发、部署和运行Java等企业应用程序。
* [Payara](https://github.com/payara/Payara)：Payara Platform Community Edition提供用于开发项目的开源服务器运行时以及容器化Jakarta EE和MicroProfile应用程序
* [Eclipse Jetty](https://github.com/eclipse/jetty.project)：Eclipse Jetty是一个轻量级、高度可扩展的基于Java的Web服务器和Servlet引擎。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：Eclipse GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现，由Oracle开源。
* [Apache Geronimo](https://github.com/apache/geronimo)：Apache基金会下开源的Java EE服务器。
* [Red5](https://github.com/Red5/red5-server)：Red5是一个用Java编写的开源Flash服务器。
* [Microhttp](https://github.com/ebarlas/microhttp)：Microhttp是一种快速、可扩展、事件驱动、独立的Java Web服务器。
* [Apache MINA](https://github.com/apache/mina)：Apache MINA是一个网络应用框架，可以帮助用户开发高性能和高可扩展性的网络应用程序。
* [Resin](https://caucho.com/products/resin)：Resin是Caucho公司的产品，它是一个非常流行的支持Servlet和JSP的服务器。
* [ZFoo](https://github.com/zfoo-project/zfoo)：极快的企业服务器框架，可用于RPC、游戏服务器、Web服务器。
* [Eclipse Grizzly](https://github.com/eclipse-ee4j/grizzly)：Grizzly的目标是帮助开发人员使用NIO构建可扩展且强大的服务器，并提供扩展框架组件。
* [Reactor Netty](https://github.com/reactor/reactor-netty)：Reactor Netty提供基于Netty框架的非阻塞和背压就绪的TCP/HTTP/UDP/QUIC客户端和服务器。
* [Nettosphere](https://github.com/Atmosphere/nettosphere)：由Atmosphere和Netty提供支持的Java WebSocket和HTTP服务器。
* [NanoHTTPD](https://github.com/NanoHttpd/nanohttpd)：NanoHTTPD是一个轻量级HTTP服务器，设计用于嵌入其他应用程序。
* [Java NIO Server](https://github.com/jjenkov/java-nio-server)：一个始终使用非阻塞IO的Java NIO服务器。
* [AndServer](https://github.com/yanzhenjie/AndServer)：AndServer是一个HTTP和反向代理服务器。
* [Rapidoid](https://github.com/rapidoid/rapidoid)：Rapidoid是一款速度极快的HTTP服务器和现代Java Web框架/应用程序容器，重点关注高生产率和高性能。
* [Quixote](https://github.com/io7m/quixote)：用于单元测试的小型嵌入式HTTP服务器。
* [Nginx-Clojure](https://github.com/nginx-clojure/nginx-clojure)：Nginx-Clojure是一个Nginx模块，用于嵌入Clojure或Java或Groovy程序，通常是那些基于Ring的处理程序。
* [Jibble](http://www.jibble.org/miniwebserver/)：用Java编写的非常小的独立Web服务器，它打包在JAR文件中，也可以在你自己的Java程序中使用。
* [Acteur](https://github.com/timboudreau/acteur)：Acteur是一个使用Netty编写Web服务器应用程序的框架。
* [QuickServer](https://github.com/QuickServerLab/QuickServer-Main)：QuickServer是一个开源Java库/框架，用于快速创建强大的多客户端TCP服务器应用程序。
* [Android HTTP Server](https://github.com/piotrpolak/android-http-server)：完全用Java SE编写的小型但功能强大的多线程Web服务器。
* [MuServer](https://github.com/3redronin/mu-server)：一个基于Netty的现代Java Web服务器。
* [Fluent-HTTP](https://github.com/CodeStory/fluent-http)：Fluent-HTTP是一个简单、快速、成熟的Web服务器。
* [Webpieces](https://github.com/deanhiller/webpieces)：包含用于创建Web服务器的所有Web部分的项目。

## WebSocket

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

## JakartaEE产品

* [Payara](https://github.com/payara/Payara)：Payara Platform Community Edition提供用于开发项目的开源服务器运行时以及容器化Jakarta EE和MicroProfile应用程序。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Piranha](https://github.com/piranhacloud/piranha)：Piranha项目提供云就绪容器和有用的附加/集成模块。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，它是IBM WebSphere Liberty的开源实现。
* [KumuluzEE](https://github.com/kumuluz/kumuluzee)：轻量级开源框架，用于使用标准Jakarta EE技术开发微服务并将Jakarta EE迁移到云原生架构。
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
* [Resin](https://caucho.com/products/resin)：Resin是Caucho开发的Web服务器和Java应用服务器，有两个可用版本：Resin（可免费用于生产）和Resin Pro（需要支付许可费用）。
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
* [Apache Commons Lang](https://github.com/apache/commons-lang)：Apache Commons Lang是一个Java实用程序类包，用于java.lang层次结构中的类。
* [Hutool](https://github.com/dromara/hutool)：Hutool是一个功能丰富且易用的Java工具库，涵盖了字符串、数字、集合、编码、日期、文件、IO、加密、数据库JDBC、JSON、HTTP客户端等一系列操作，由dromara社区开源。
* [Cactoos](https://github.com/yegor256/cactoos)：Cactoos是面向对象的Java原始类型的集合。
* [JCommon](https://github.com/facebookarchive/jcommon)：JCommon是Facebook开源的Java工具库，含并发、集合、统计/分析、配置、测试等功能。
* [Jodd](https://github.com/oblac/jodd)：Jodd是一组微框架和开发人员友好的工具和实用程序。
* [Ph-Commons](https://github.com/phax/ph-commons)：包含所有项目所需的大量工具类的Java 11库。
* [X-Core](https://github.com/TGX-Android/X-Core)：X-Core是一组可在任何项目中使用的通用Java工具和接口，由Telegram开源。
* [Essentials](https://github.com/greenrobot/essentials)：Essentials是适用于Android和Java的通用工具和哈希函数。
* [Twitter Commons](https://github.com/twitter-archive/commons)：Twitter的JVM公共库，已弃用。
* [RxTool](https://github.com/Tamsiree/RxTool)：RxTool是用于Android开发各式各样的工具类集合。
* [Cloudhopper Commons](https://github.com/twitter/cloudhopper-commons)：Twitter的Cloudhopper系列移动消息应用程序使用的通用Java库。
* [Indeed Util](https://github.com/indeedeng/util)：由Indeed开发的通用Java工具类。
* [JUtils](https://github.com/chenssy89/jutils)：通用的Java工具类库。
* [VJTools](https://github.com/vipshop/vjtools)：唯品会的Java编码标准、库和工具。
* [SOFA-Common](https://github.com/sofastack/sofa-common-tools)：SOFA-Common是蚂蚁为其他SOFA库提供一些实用功能的库。
* [Annotations](https://github.com/JetBrains/java-annotations)：Annotations是一组可在基于JVM的语言中使用的Java注解，由JetBrains开源。
* [Commons Core](https://github.com/ponfee/commons-core)：Java工具类库。
* [XXL-TOOL](https://github.com/xuxueli/xxl-tool)：包含集合、缓存、并发、字符串、IO、Excel、Emoji等数十个模块的工具类库。
* [xUtils](https://github.com/wyouflf/xUtils3)：xUtils包含了ORM、HTTP、图片处理等工具类。
* [LogiCommon](https://github.com/didi/LogiCommon)：LogiCommon包含认证、鉴权、管理、任务调度通用功能组件，由滴滴开源。
* [Camellia](https://github.com/netease-im/camellia)：网易云信开发的服务器基础组件库。
* [CommonUtil](https://github.com/LJWLgl/CommonUtil)：轻便简单的Java常用工具类库。
* [Shawn Common Utils](https://github.com/shawntime/shawn-common-utils)：Java整理的基础工具类项目。
* [Netflix Commons](https://github.com/Netflix/netflix-commons)：Netflix OSS项目的常用工具类。
* [Confluent Commons](https://github.com/confluentinc/common)：Confluent开源的包含指标、配置和工具类的通用库。
* [LinkedIn Utils](https://github.com/LinkedInAttic/linkedin-utils)：所有Linkedin开源项目共享的基础工具类。
* [Java Util](https://github.com/metamx/java-util)：Metamarkets开源的Java和基于JVM的语言的工具类代码。
* [Plexus Utils](https://github.com/codehaus-plexus/plexus-utils)：各种工具类的集合，可轻松处理字符串、文件、命令行等。
* [Triava](https://github.com/trivago/triava)：Triava项目包含几个trivago的基于Java项目的核心库：缓存、集合、注解、并发库等等。
* [Bus](https://github.com/aoju/bus)：包含大量工具的基础框架、服务套件，基于Java 17编写。
* [Java Util](https://github.com/jdereg/java-util)：提供非常多与其他工具库功能不同的实用程序。
* [Twitter Util](https://github.com/twitter/util)：一堆惯用的、小型的、通用的工具，该项目在Twitter(以及许多其他组织)的生产中使用。
* [KillBill-Commons](https://github.com/killbill/killbill-commons)：Kill Bill的可重用Java组件。
* [SonarQube Scanner Commons](https://github.com/SonarSource/sonar-scanner-commons)：许多SonarScanner使用的通用Java库。
* [IU Java Util](https://github.com/indiana-university/iu-java-util)：印第安纳大学开源的Java项目工具库。
* [JTOpen](https://github.com/IBM/JTOpen)：JTOpen提供了一组Java类，使应用程序能够与IBM集成。
* [Scar](https://github.com/EsotericSoftware/scar)：Scar是一个实用程序集合，可让你更轻松地使用Java代码执行构建相关任务。
* [Nrich](https://github.com/croz-ltd/nrich)：Nrich是CROZ开发的一个Java库，其目的是使JVM上的应用程序开发更加容易。
* [Insight Engineering Platform](https://github.com/Netflix/iep)：主要由Netflix的Insight工程团队使用的一组基础库，用于支持需要在内部和外部运行的应用程序。
* [XWiki Commons](https://github.com/xwiki/xwiki-commons)：XWiki Commons是其他几个顶级XWiki项目通用的技术库。

## Bean映射&复制

* [MapStruct](https://github.com/mapstruct/mapstruct)：MapStruct是一个Java注解处理器，用于为Java bean类生成类型安全且高性能的映射器。
* [MapStruct Plus](https://github.com/linpeilie/mapstruct-plus)：MapStruct Plus是对MapStruct框架的增强。
* [Dozer](https://github.com/DozerMapper/dozer)：Dozer是一种Java Bean到Java Bean映射器，它将数据从一个对象递归复制到另一个对象。
* [ModelMapper](https://github.com/modelmapper/modelmapper)：ModelMapper是一个智能对象映射库，可以自动将对象相互映射。
* [Orika](https://github.com/orika-mapper/orika)：Orika是一种Java Bean映射框架，可将数据从一个对象递归复制到另一个对象。
* [EasyMapper](https://github.com/EasyMapper/EasyMapper)：EasyMapper是一个易于使用的Java对象映射库，旨在简化表示域中对象的模型之间映射值的过程。
* [JMapper](https://github.com/jmapper-framework/jmapper-core)：JMapper是集优雅、高性能和稳健性于一体的Java Bean映射器。
* [Apache Commons Beanutils](https://github.com/apache/commons-beanutils)：Apache Commons BeanUtils提供了一个易于使用但灵活的反射和内省包装器。
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
* [EasyMapper](https://github.com/neoremind/easy-mapper)：EasyMapper是一个简单、轻量级、高性能的Java bean映射框架。

## IoC

* [Spring](https://github.com/spring-projects/spring-framework)：Spring框架是Java平台的一个开源全栈应用程序框架和控制反转容器实现。
* [Guice](https://github.com/google/guice)：Guice是一个适用于Java 8及更高版本的轻量级依赖注入框架，由Google开源。
* [Dagger](https://github.com/google/dagger)：Dagger是一个用于依赖注入的编译时框架，它不使用反射或运行时字节码生成，在编译时进行所有分析，并生成纯Java源代码，由Square开源。
* [Koin](https://github.com/InsertKoinIO/koin)：Koin是一个面向Kotlin开发人员的实用轻量级依赖注入框架。
* [Motif](https://github.com/uber/motif)：Motif是一个DI库，提供针对嵌套作用域优化的简单API，由Uber开源。
* [PicoContainer](https://github.com/picocontainer/picocontainer)：PicoContainer是非常轻量级的IoC容器，提供依赖注入和对象生命周期管理的功能。
* [Avaje-Inject](https://github.com/avaje/avaje-inject)：面向Java和Kotlin开发人员的快速、轻型依赖注入库。
* [GlassFish HK2](https://github.com/eclipse-ee4j/glassfish-hk2)：Eclipse GlassFish HK2是Jakarta依赖注入的实现。
* [Micronaut Inject](https://github.com/micronaut-projects/micronaut-core/tree/4.6.x/inject)：Micronaut框架核心依赖注入和控制反转模块。
* [Apache DeltaSpike](https://github.com/apache/deltaspike)：Apache DeltaSpike是一套可移植的CDI扩展，旨在使使用CDI和Java EE时的应用程序开发变得更加容易。
* [Javax-Inject](https://github.com/javax-inject/javax-inject)：JSR-330依赖注入标准。
* [CDI](https://www.cdi-spec.org/)：CDI规范，定义了一组强大的补充服务。
* [Apache OpenEJB](https://openejb.apache.org/)：OpenEJB是一个开源、可嵌入、轻量级的EJB容器系统和EJB服务器。
* [Apache OpenWebBeans](https://github.com/apache/openwebbeans)：Apache OpenWebBeans是CDI 2.0规范的实现。
* [Eclipse Sisu](https://github.com/eclipse/sisu.inject)：Sisu是一个基于JSR330的模块化容器，支持类路径扫描、自动绑定和动态自动装配。
* [Weld](https://github.com/weld/core)：Weld是CDI的参考实现。
* [Coody](https://gitee.com/coodyer/Coody-Framework)：Coody是一个国产IoC框架，轻量级、简单快速。
* [Scaldi](https://github.com/scaldi/scaldi)：Scaldi提供了一种简单而优雅的方式在Scala中进行依赖注入。
* [Kodein](https://github.com/kosi-libs/Kodein)：Kodein是一个简单但非常有用的依赖项检索容器，使用和配置都很轻松。
* [Transfuse](https://github.com/johncarl81/transfuse)：Transfuse是一个专门针对Google Android API的Java依赖注入和集成库。
* [Governator](https://github.com/Netflix/governator)：Governator是一个扩展和工具库，可增强Google Guice以提供注入器生命周期，并通过@PostConstruct和@PreDestroy支持对象生命周期，由Netflix开源。
* [Toothpick](https://github.com/stephanenicolas/toothpick)：Toothpick是一个基于作用域树的Java依赖注入库。
* [Feather](https://github.com/zsoltherpai/feather)：Feather是一个适用于Java和Android的超轻量级依赖注入(JSR-330)库。
* [JayWire](https://github.com/vanillasource/jaywire)：JayWire是一个非常小、轻量级的Java 8依赖注入框架。
* [Tiny-Spring](https://github.com/code4craft/tiny-spring)：Tiny-Spring是为了学习Spring的而开发的，可以认为是一个Spring的精简版。
* [OfficeFloor](https://github.com/officefloor/OfficeFloor)：OfficeFloor是一个IoC库，可以通过一流的程序构建应用程序。
* [Inverno](https://github.com/inverno-io/inverno-core)：Inverno项目为Java平台提供了控制反转和依赖注入框架，它的特殊之处在于不使用反射进行对象实例化和依赖项注入，所有内容都在编译期间静态验证和完成。
* [Mikron](https://github.com/reevik/mikron)：用于依赖注入和外部化配置管理的简约IoC容器。
* [JBoss MSC](https://github.com/jboss-msc/jboss-msc)：JBoss MSC是Java的轻量级高并发依赖注入容器。
* [SIRIUS Kernel](https://github.com/scireum/sirius-kernel)：提供通用核心类和依赖注入微内核，为所有SIRIUS应用程序提供支持。

## AOP

* [AspectJ](https://github.com/eclipse-aspectj/aspectj)：AspectJ是一个面向切面的框架，它扩展了Java语言。
* [JVM-SandBox](https://github.com/alibaba/jvm-sandbox)：JVM SandBox是一种JVM的非侵入式运行期AOP解决方案，由阿里开源。
* [JBossAop](https://jbossaop.jboss.org/)：JBoss AOP是一个100%纯Java面向切面的框架，可在任何编程环境中使用或与我们的应用程序服务器紧密集成。
* [Apache Commons Weaver](https://github.com/apache/commons-weaver)：Apache Commons Weaver提供了一种通过生成(“织入”)字节码到这些类中来增强已编译Java类的简单方法。
* [FastAOP](https://github.com/fast-light/fastaop)：FastAOP是一款基于Java注解处理器的轻量级高性能AOP框架，类似于Lombok。
* [Alliance](https://aopalliance.sourceforge.net/)：Alliance项目是几个对AOP和Java感兴趣的软件工程人员联合发起的开源项目。
* [Lancet](https://github.com/eleme/lancet)：Lancet是一个轻量级的Android AOP框架，由饿了么开源。
* [Jcabi Aspects](https://github.com/jcabi/jcabi-aspects)：AspectJ Java切面的集合，促进面向切面的编程模式：日志记录、缓存、验证等。
* [AspectwerkZ](https://github.com/jboner/aspectwerkz)：简单、动态、轻量级、高性能的Java AOP框架。
* [AspectJX](https://github.com/HujiangTechnology/gradle_plugin_android_aspectjx)：一个基于AspectJ并在此基础上扩展出来可应用于Android开发平台的AOP框架，可作用于Java源码，class文件及jar包，同时支持Kotlin应用，由沪江科技开源。
* [Proxy](https://github.com/Ericsson/proxy)：一个小而强大的拦截库，可以让你在运行时操作现有的对象和类行为，由爱立信开源。
* [CaesarJ](https://caesarj.org/)：CaesarJ是一种基于Java的新编程语言，它有助于实现更好的模块化和可重用组件的开发，由达姆城工业大学开源。
* [Nepxion Matrix](https://github.com/Nepxion/Matrix)：Nepxion Matrix是一款集成Spring AutoProxy，Spring Registrar和Spring Import Selector三种机制的AOP框架。

## 日志库

* [Apache Log4j](https://github.com/apache/logging-log4j1)：Apache Log4j的初始版本，已经停止维护。
* [Apache Log4j2](https://github.com/apache/logging-log4j2)：Apache Log4j是一个多功能的工业级Java日志记录框架，由API、其实现和组件组成。
* [Logback](https://github.com/qos-ch/logback)：Logback是一个可靠、通用、快速且灵活的Java日志记录框架。
* [Apache Commons Logging](https://github.com/apache/commons-logging)：Apache Commons Logging是一个瘦适配器，允许可配置地桥接到其他众所周知的日志系统。
* [Slf4j](https://github.com/qos-ch/slf4j)：SLF4J用作各种日志框架(例如JUL、Logback、Reload4j、Log4j 2)的简单门面或抽象，允许最终用户在部署时插入所需的日志框架。
* [JUL](https://github.com/openjdk/jdk/tree/master/src/java.logging/share/classes/java/util/logging)：JUL提供Java平台核心日志记录工具的类和接口。
* [Flogger](https://github.com/google/flogger)：Flogger是一个流式的Java日志记录API，它支持多种功能，并且比现有的日志记录API具有许多优势，由Google开发。
* [Logstash](https://github.com/elastic/logstash)：Logstash是免费且开源的服务器端数据处理管道，能够从多个来源采集数据，转换数据，然后将数据发送到你最喜欢的“存储库”中。
* [Twitter Logging](https://github.com/twitter/util/tree/develop/util-logging)：Twitter开发的日志工具库。
* [Tinylog](https://github.com/tinylog-org/tinylog)：Tinylog是一个适用于Java、Kotlin、Scala和Android的轻量级日志框架。
* [Graylog](https://github.com/Graylog2/graylog2-server)：Graylog是一个免费开源的日志管理平台。
* [Blitz4j](https://github.com/Netflix/blitz4j)：Blitz4j是一个构建在Log4j之上的日志框架，用于减少争用并实现高度可扩展的日志记录，而不会影响应用程序性能特征，由Netflix开源。
* [Kotlin Logging](https://github.com/oshai/kotlin-logging)：Kotlin的轻量级多平台日志框架。
* [Apache DistributedLog](https://github.com/twitter-archive/distributedlog)：Apache DistributedLog是一种高吞吐量、低延迟的复制日志服务，提供持久性、复制和强一致性，由Twitter开发。
* [JBoss Logging](https://github.com/jboss-logging/jboss-logging)：JBoss Logging是一个日志门面，可以绑定到不同的日志管理器。
* [Timbermill](https://github.com/salesforce/Timbermill)：Timbermill是专为Elasticsearch构建的高级开源日志服务，Salesforce开源。
* [Scala Logging](https://github.com/lightbend-labs/scala-logging)：Scala Logging是一个包装SLF4J的方便快捷的日志库。
* [Logger](https://github.com/orhanobut/logger)：简单、功能强大的Android日志记录器。
* [GELFJ](https://github.com/t0xa/gelfj)：Java中的Graylog扩展日志格式实现和Log4j Appender。
* [BqLog](https://github.com/Tencent/BqLog)：BqLog是一款轻量级、高性能的日志系统，应用于《王者荣耀》等项目中，由腾讯开源。
* [Google Cloud Logging](https://github.com/googleapis/java-logging)：用于Java的Google Cloud Logging客户端库。
* [GFLog](https://github.com/epam/gflog)：GFLog是适用于Java 8+的高效无垃圾日志记录框架。
* [Timber](https://github.com/JakeWharton/timber)：具有小型可扩展API的日志记录器。
* [MinLog](https://github.com/EsotericSoftware/minlog)：MinLog一个小型Java日志库，其特点是零开销、极其轻便、简单高效。
* [PlumeLog](https://gitee.com/plumeorg/plumelog)：PlumeLog是一个简单易用的Java分布式日志组件，由Plume社区开源。
* [Logbook](https://github.com/zalando/logbook)：Logbook是一个可扩展的Java库，可为不同的客户端和服务器端技术启用完整的请求和响应日志记录，由Zalando开源。
* [XLog](https://github.com/elvishew/xLog)：XLog是适用于Android和Java的轻量、强大且灵活的记录器。
* [TLog](https://gitee.com/dromara/TLog)：TLog是一个轻量级的分布式日志标记追踪神器，由dromara社区开源。
* [JLog](https://gitee.com/jd-platform-opensource/jlog)：JLog是京东开源的海量日志搜集、传输、存储解决方案。
* [P6Spy](https://github.com/p6spy/p6spy)：P6Spy是一个框架，无需对应用程序进行任何代码更改即可无缝拦截和记录数据库数据。
* [Aliyun Log](https://github.com/aliyun/aliyun-log-java-sdk)：阿里云日志服务Java SDK。
* [Fluent Logger](https://github.com/fluent/fluent-logger-java)：Fluent Logger是一个Java库，用于通过Fluentd从Java应用程序记录事件。
* [Chronicle Logger](https://github.com/OpenHFT/Chronicle-Logger)：Chronicle Logger是一个亚微秒Java记录器，支持标准日志记录API，例如SLF4j和Log4J。
* [Jcabi Log](https://github.com/jcabi/jcabi-log)：SLF4J的静态包装器，无需在每个Java类中创建静态LOGGER实例。
* [PLog](https://github.com/JumeiRdGroup/Android-PLog)：PLog项目是一个专为Android应用程序设计的开源日志封装库，由聚美优品开源。
* [PL4J](https://github.com/ludovicianul/pl4j)：PL4J是一个SLF4j包装器，可以通过jansi使用ANSI格式进行漂亮打印。
* [ObjectLogger](https://github.com/yeecode/ObjectLogger)：ObjectLogger是一个功能强大且易于使用的对象日志系统，支持对象属性变化的写入和查询。
* [Trojan](https://github.com/eleme/Trojan)：Trojan是一款稳定、高效的移动端轻量级日志SDK，饿了么开源。
* [AutoLog4j](https://github.com/AutohomeCorp/autolog4j)：AutoLog4j是汽车之家经销商技术部日志类库相关扩展。
* [Sensitive](https://github.com/houbb/sensitive)：Sensitive项目提供基于注解的方式，并且内置了常见的脱敏方式，便于开发。
* [Yupiik Logging](https://github.com/yupiik/yupiik-logging)：Yupiik提供了一个Graal友好的JUL LogManager，你可以在运行时重新配置JUL记录器以及一些实用程序，例如更高级的格式化程序或处理程序。
* [Spotify Logging](https://github.com/spotify/logging-java)：以Spotify兼容方式设置日志记录的工具类。
* [MinBox Logging](https://gitee.com/minbox-projects/minbox-logging)：MinBox Logging是一款分布式、零侵入式的链路日志分析框架。
* [LogUtils](https://github.com/pengwei1024/LogUtils)：更方便易用的Android日志管理器。
* [Singer](https://github.com/pinterest/singer)：Singer是一个高性能日志代理，用于将日志上传到Kafka，由Pinterest开源。
* [Log Record](https://github.com/qqxx6661/log-record)：Log Record可以通过Java注解优雅的记录操作日志，并支持SpEL表达式、自定义上下文、自定义函数、实体类DIFF等功能。
* [Elf4j Engine](https://github.com/elf4j/elf4j-engine)：Elf4j是一个独立的异步Java日志引擎。
* [Logback Android](https://github.com/tony19/logback-android)：适用于Android的可靠、通用、快速且灵活的日志记录框架。
* [Zerolog](https://github.com/obsidiandynamics/zerolog)：Zerolog是一个日志门面，适用于性能敏感应用程序。
* [Penna](https://github.com/hkupty/penna)：Penna是SLF4j的一个后端，专注于以JSON格式将结构化日志记录到控制台。
* [BizLog](https://github.com/mouzt/mzt-biz-log)：Spring Boot注解通用操作日志组件，美团员工开源。
* [Yolo](https://github.com/ustream/yolo)：Java中的日志尾随和解析框架，Ustream开源。
* [Klogging](https://github.com/klogging/klogging)：Klogging是一个纯Kotlin日志库，它使用Kotlin习惯用法来创建记录器和发送日志事件。
* [Echopraxia](https://github.com/tersesystems/echopraxia)：Echopraxia是一个围绕结构化日志记录设计的Java日志记录API。
* [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox)：OpenTracing Toolbox是构建在OpenTracing之上的库的集合，并为现有仪器提供扩展和插件，由Zalando开源。
* [OWASP Security Logging](https://github.com/augustd/owasp-security-logging)：用于记录安全相关事件的标准Java API，由OWASP开源。
* [Logstash Logback Encoder](https://github.com/logfellow/logstash-logback-encoder)：Logback JSON编码器和附加器。
* [LogViewer](https://github.com/sevdokimov/log-viewer)：LogViewer是一个Web应用程序，用于在浏览器中实时监控服务器日志。
* [Logback GELF](https://github.com/osiegmar/logback-gelf)：用于发送GELF消息的Logback Appender。
* [Terse Logback](https://github.com/tersesystems/terse-logback)：Terse Logback是Logback扩展的集合，功能包括结构化日志记录、跟踪和可观察性。
* [Log4j2-ElasticSearch](https://github.com/rfoltyns/log4j2-elasticsearch)：这是Log4j2 Appender插件的父项目，能够将日志批量推送到Elasticsearch集群。
* [Logback Extensions](https://github.com/qos-ch/logback-extensions)：Logback Extensions项目为Logback日志框架提供社区支持的扩展。
* [Splunk Logging](https://github.com/splunk/splunk-library-javalogging)：适用于流行Java日志框架的Splunk日志Appender。
* [Logback More Appender](https://github.com/sndyuk/logback-more-appenders)：Logback的附加Appender，可以毫无顾虑地提供更好的性能和数据一致性。
* [Logback Redis Appender](https://github.com/kmtong/logback-redis-appender)：将日志记录到Redis的Logback Appender。
* [Cloud Foundry Java Logging](https://github.com/SAP/cf-java-logging-support)：Cloud Foundry的Java日志记录支持，可以创建结构化日志消息和收集请求指标，由SAP开源。
* [TNT4J](https://github.com/Nastel/TNT4J)：TNT4J旨在通过易于使用的API来跟踪应用程序、活动、事务、行为和性能，其行为非常类似于日志记录框架。
* [Rainbow Gum](https://github.com/jstachio/rainbowgum)：Rainbow Gum是一个快速、小型、JDK 21+、GraalVM原生友好的Slf4j日志框架。
* [LogEvents](https://github.com/jhannes/logevents)：LogEvents是一个小型日志记录框架，构建在SLF4J之上。

## JSON库

* [Jackson](https://github.com/FasterXML/jackson)：Jackson是Java中使用最广泛的JSON库，也是Spring默认的JSON处理器。
* [Gson](https://github.com/google/gson)：Gson是一个Java库，可用于将Java对象转换为其JSON表示形式，由Google开源。
* [Fastjson](https://github.com/alibaba/fastjson)：Fastjson是一个Java库，可用于将Java对象转换为其JSON表示形式，由阿里开源。
* [Fastjson 2](https://github.com/alibaba/fastjson2)：Fastjson 2是一个性能极致并且简单易用的Java JSON库，由阿里开源。
* [Moshi](https://github.com/square/moshi)：Moshi是一个适用于Android、Java和Kotlin的现代JSON库。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：适用于Android的最快JSON解析和序列化库。
* [JSON-Java](https://github.com/stleary/JSON-java)：JSON-Java包是一个参考实现，可以将JSON文档解析为Java对象以及从Java类生成新的JSON文档。
* [Flexjson](https://flexjson.sourceforge.net/)：Flexjson是一个轻量级库，用于将Java对象序列化为JSON。
* [JSON-lib](https://json-lib.sourceforge.net/)：JSON-lib是一个Java库，用于将Bean、Map、集合、Java数组和XML转换为JSON，然后再转换回Bean。
* [JSON.Simple](https://github.com/fangyidong/json-simple)：JSON.Simple是一个简单的JSON Java工具包。
* [JSON Schema Validator](https://github.com/everit-org/json-schema)：用于Java的JSON模式验证器，基于org.json API。
* [Jakarta JSON Processing](https://github.com/jakartaee/jsonp-api)：Jakarta JSON Processing提供可移植的API来解析、生成、转换和查询JSON文档。
* [Eclipse Yasson](https://github.com/eclipse-ee4j/yasson)：Yasson是一个Java框架，它在Java类和JSON文档之间提供标准绑定层。
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON)：高性能JSON解析器。
* [Eclipse Parsson](https://github.com/eclipse-ee4j/parsson)：Eclipse Parsson是Jakarta JSON Processing规范的实现。
* [JsonLube](https://github.com/alibaba/JsonLube)：JsonLube可以在编译期自动生成JSON解析代码，用户使用方式更简单，同时能收获原生解析的性能，由阿里开发。
* [JSON-IO](https://github.com/jdereg/json-io)：小巧、轻量级的JSON和Java对象转换库。
* [Jsoniter](https://github.com/json-iterator/java)：Jsoniter是Java和Go中可用的快速灵活的JSON解析器。
* [Genson](https://github.com/owlike/genson)：Genson是一个完整的JSON Java转换库，提供完整的数据绑定、流媒体等等。
* [Jsonschema2Pojo](https://github.com/joelittlejohn/jsonschema2pojo)：Jsonschema2Pojo从JSON或JSON Schema生成Java类型，并标注这些类型以与Jackson、Gson等进行数据绑定。
* [DSL-JSON](https://github.com/ngs-doo/dsl-json)：最快的JVM JSON库，具有高级编译时数据绑定支持。
* [Ason](https://github.com/afollestad/ason)：该库旨在使JSON非常容易在Java中进行交互。
* [JSONLD-Java](https://github.com/jsonld-java/jsonld-java)：这是JSON-LD 1.0规范和JSON-LD-API 1.0规范的Java实现。
* [Instagram JSON Parser](https://github.com/Instagram/ig-json-parser)：用于Java项目的快速JSON解析器，由Instagram开源。
* [Minimal Json](https://github.com/ralfstx/minimal-json)：用于Java的快速且最小的JSON解析器和编写器。
* [JSON Patch](https://github.com/java-json-tools/json-patch)：这是用Java编写的RFC 6902(JSON Patch)和RFC 7386(JSON Merge Patch)的实现，其核心使用Jackson。
* [Json-Smart](https://github.com/netplex/json-smart-v2)：注重性能的JSON处理器库。
* [JSON Sanitizer](https://github.com/OWASP/json-sanitizer)：给定类似JSON的内容，JSON Sanitizer会将其转换为有效的JSON，由OWASP开源。
* [Jfire-CodeJson](https://gitee.com/eric_ds/jfire-codejson)：性能非常高的JSON序列化和反序列化库。
* [Sawmill](https://github.com/logzio/sawmill)：Sawmill是一个JSON转换Java库。
* [Katharsis](https://github.com/katharsis-project/katharsis-framework)：Katharsis实现了JSON API标准，引入了一致的REST接口定义，可以通过统一的机制轻松地与其他系统集成。
* [JSON Schema Validator](https://github.com/networknt/json-schema-validator)：这是用于JSON模式校验的JSON Schema Core Draft规范的Java实现。
* [Apache Johnzon](https://github.com/apache/johnzon)：提供JSON Processing(又名JSR-353)实现和该规范的一组有用扩展的项目。
* [SIMDJson-Java](https://github.com/simdjson/simdjson-java)：simdjson的Java版本-使用SIMD指令的JSON解析器。
* [JSON Schema Validator](https://github.com/java-json-tools/json-schema-validator)：Java中的纯JSON模式验证实现，具有可靠的正确性和性能。
* [Jolt](https://github.com/bazaarvoice/jolt)：使用Java编写的JSON到JSON转换库，由Bazaarvoice开源。
* [Boon](https://github.com/boonproject/boon)：Boon是一个简单的基于Java的JSON工具包，你可以使用Boon JSON以高效且快速的方式对JSON数据进行编码或解码。
* [Hjson Java](https://github.com/hjson/hjson-java)：人类的配置文件格式，宽松的语法，更少的错误，更多的注释。
* [Avaje JsonB](https://github.com/avaje/avaje-jsonb)：通过APT源代码生成进行快速、无反射的JSON绑定的Java库。
* [JSON-RPC](https://github.com/briandilley/jsonrpc4j)：该项目旨在为Java编程语言提供轻松实现JSON-RPC的工具。
* [NanoJson](https://github.com/mmastrac/nanojson)：一个小型、兼容的Java JSON解析器和写入器。
* [JSON Schema Generator](https://github.com/victools/jsonschema-generator)：用于从Java类创建JSON模式(Draft 6、Draft 7、Draft 2019-09或Draft 2020-12)。
* [JSON-Flattener](https://github.com/wnameless/json-flattener)：旨在扁平化嵌套的JSON对象，甚至可以将它们恢复扁平化。
* [JSLT](https://github.com/schibsted/jslt)：JSLT是一种完整的JSON查询和转换语言，语言设计的灵感来自jq、XPath和XQuery。
* [ZJSONPatch](https://github.com/flipkart-incubator/zjsonpatch)：这是用Java编写的RFC 6902 JSON Patch的实现。
* [JMESPath-Java](https://github.com/burtcorp/jmespath-java)：这是JMESPath的Java实现。
* [JSON-Data-Generator](https://github.com/everwatchsolutions/json-data-generator)：一个强大的、通用的、流式随机JSON数据生成器。
* [BSON4Jackson](https://github.com/michel-kraemer/bson4jackson)：该库向Jackson JSON处理器添加了对BSON的支持。
* [Jackson-JQ](https://github.com/eiiches/jackson-jq)：Jackson JSON处理器的纯Java jq实现。
* [Json Comparison](https://github.com/eBay/json-comparison)：强大的JSON比较工具，用于识别JSON文件中的所有更改，由eBay开源。
* [EasyJSON](https://github.com/bes2008/easyjson)：提供一个JSON门面库，就像SLF4j一样。
* [Titanium JSON-LD](https://github.com/filip26/titanium-json-ld)：JSON-LD 1.1处理器和API。
* [JSON-Lib](https://github.com/kordamp/json-lib)：JSON-Lib是一个Java库，用于将Bean、Map、集合、Java数组和XML转换为JSON，然后再转换回Bean和DynaBeans。
* [OpenAPI4j](https://github.com/openapi4j/openapi4j)：OpenAPI 3解析器、JSON模式和请求验证器。
* [Justify](https://github.com/leadpony/justify)：Justify是一个基于JSON模式规范和Jakarta JSON-P的JSON验证器。
* [Noggit](https://github.com/yonik/noggit)：Noggit是一个极快的Java流式JSON解析器。
* [JSONata4Java](https://github.com/IBM/JSONata4Java)：JSONata的开源Java版本，由IBM提供。
* [Actson](https://github.com/michel-kraemer/actson)：Actson是一个响应式JSON解析器。
* [JSONCoder](https://github.com/eBay/jsonex)：Jsonex JSONCoder是一个轻量级通用对象序列化/反序列化库，该库多年来已在各种eBay项目中广泛使用。
* [Functional JSON](https://github.com/MAIF/functional-json)：以函数式方式解析和写入JSON。
* [JSON Masker](https://github.com/Breus/json-masker)：Java中的高性能JSON掩码库，无运行时依赖。
* [Amplafi-JSON](https://github.com/amplafi/amplafi-json)：原始json.org代码的分支。
* [StAXON](https://github.com/beckchr/staxon)：StAXON允许你使用javax.xml.stream读取和写入JSON。
* [JRedisJSON](https://github.com/RedisJSON/JRedisJSON)：Redis RedisJSON的Java客户端。
* [JDocs](https://github.com/americanexpress/unify-jdocs)：JDocs(JSON Document)是一个JSON操作库，它完全消除了对模型/POJO类的需要，而是直接在JSON文档上工作，由美国运通开源。
* [Hope](https://github.com/santanusinha/hope)：Hope是一种用Java编写的用于对JSON进行谓词评估的高级语言。
* [JSON Canonicalization](https://github.com/cyberphone/json-canonicalization)：JSON Canonicalization Scheme的Java实现。
* [JSON Compare](https://github.com/fslev/json-compare)：用于比较JSON的Java库。
* [JSONx Java](https://github.com/jsonx-org/java)：JSONx Java为JSON模式定义语言(JSD)处理器、验证器和运行时API提供参考实现，JSD是一种JSON模式语言，其设计与XML Schema规范非常相似。

## JsonPath

* [JsonPath](https://github.com/json-path/JsonPath)：JsonPath的实现版本，用于读取JSON文档的Java DSL。
* [Snack3](https://gitee.com/noear/snack3)：一个高性能的JsonPath框架，支持序列化反序列化、解析和转换、构建、查找、JsonPath查询。
* [JsonSurfer](https://github.com/wanglingsong/JsonSurfer)：Java中的流式JsonPath处理器。

## 缓存库

* [Guava Cache](https://github.com/google/guava/tree/master/guava/src/com/google/common/cache)：Google Guava库提供的Java本地缓存工具。
* [Caffeine](https://github.com/ben-manes/caffeine)：Caffeine是一个高性能、接近最佳的缓存库。
* [Infinispan](https://github.com/infinispan/infinispan)：Infinispan是一个开源内存数据网格，提供灵活的部署选项和强大的数据存储、管理和处理功能，由RedHat开源。
* [Apache Ignite](https://github.com/apache/ignite)：Apache Ignite是一个分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [Ehcache](https://github.com/ehcache/ehcache3)：Ehcache是一种基于标准的开源缓存，可提高性能、减轻数据库负载并简化可扩展性。
* [Apache Commons JCS](https://github.com/apache/commons-jcs)：Apache Commons JCS是一个分布式、多功能的缓存系统。
* [JetCache](https://github.com/alibaba/jetcache)：JetCache是一种Java缓存抽象，它为不同的缓存解决方案提供统一的使用方式，由阿里开源。
* [DiskLruCache](https://github.com/JakeWharton/DiskLruCache)：基于磁盘的LRU缓存的Java实现，专门针对Android兼容性。
* [ASimpleCache](https://github.com/yangfuhai/ASimpleCache)：ASimpleCache是一个为Android制定的轻量级开源缓存框架。
* [RxCache](https://github.com/VictorAlbertos/RxCache)：适用于Android和Java的响应式缓存库。
* [EVCache](https://github.com/Netflix/EVCache)：EVCache是一个基于Memcached和Spymemcached的缓存解决方案，主要用于AWS EC2基础设施来缓存常用数据，由Netflix开源。
* [Cache2K](https://github.com/cache2k/cache2k)：Cache2K是一个内存中高性能Java缓存库。
* [HotKey](https://gitee.com/jd-platform-opensource/hotkey)：京东App后台中间件，毫秒级探测热点数据，毫秒级推送至服务器集群内存，大幅降低热key对数据层查询压力。
* [MicroStream](https://github.com/microstream-one/microstream)：MicroStream是一个突破性的Java原生对象图持久层，专为需要轻量级高性能持久层的微服务和Serverless函数而构建。
* [AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache)：AutoLoadCache是基于AOP+注解等技术实现的高效的缓存管理解决方案。
* [J2Cache](https://gitee.com/ld/J2Cache)：J2Cache是OSChina目前正在使用的二级缓存框架。
* [RedisCache](https://gitee.com/darkidiot/RedisCache)：RedisCache是基于Jedis的SDK。
* [XXL-Cache](https://github.com/xuxueli/xxl-cache)：XXL-Cache是一个分布式缓存管理平台，其核心设计目标是让分布式缓存的接入和管理的更加的简洁和高效。
* [OHC](https://github.com/snazy/ohc)：Java堆外缓存解决方案。
* [KCache](https://github.com/rayokota/kcache)：KCache是一个客户端库，它提供由Kafka中的压缩主题支持的内存缓存。
* [Cache4j](https://cache4j.sourceforge.net/)：Java对象的缓存，简单的API和快速的实现。
* [Imcache](https://github.com/Cetsoft/imcache)：Imcache是一个Java缓存库，旨在通过提供管理缓存数据的方法来加速应用程序。
* [JCache RI](https://github.com/jsr107/RI)：JCache的参考实现。
* [Xanthic](https://github.com/Xanthic/cache-api)：该库提供了一个简化的接口，用于与JVM上的内存缓存实现进行交互。
* [ExpiringMap](https://github.com/jhalterman/expiringmap)：一种高性能、低开销、零依赖、线程安全的ConcurrentMap实现，可让键值对过期。
* [OffHeap Store](https://github.com/Terracotta-OSS/offheap-store)：OffHeap Store是一个库，提供一组Map和缓存实现，用于在普通Java堆之外存储数据。
* [Apache DirectMemory](https://directmemory.apache.org/)：Apache DirectMemory是JVM的堆外缓存。
* [CarbonJ](https://github.com/salesforce/carbonj)：CarbonJ是Carbon-cache和Carbon-relay的直接替代品，它在设计时考虑了高性能读写吞吐量，支持写入数百万个指标数据点，并以低查询延迟每分钟提供数百万个指标数据点。
* [BlazingCache](https://github.com/diennea/blazingcache)：BlazingCache是分布式Java应用程序的快速缓存。

## 集合库

* [Apache Commons Collections](https://github.com/apache/commons-collections)：Apache Commons Collections包含扩展和增强Java集合框架的类型。
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections)：Eclipse Collections是一个综合性的Java集合库，通过提供一组富有表现力且高效的API和类型来提高生产力和性能，由高盛银行开源。
* [Fastutil](https://github.com/vigna/fastutil)：Fastutil通过提供特定类型的Map、Set、List和Queue来扩展Java集合框架。
* [HPPC](https://github.com/carrotsearch/hppc)：HPPC使用专门版本实现典型集合(列表、双端队列、集合、映射)，这些版本存储原始类型而不将它们装箱为对象。
* [PCollections](https://github.com/hrldcpr/pcollections)：PCollections充当Java集合框架的持久且不可变的类似物。
* [CQEngine](https://github.com/npgall/cqengine)：CQEngine是一个高性能Java集合，可以使用类似SQL的查询进行搜索，并且延迟极低。
* [Agrona](https://github.com/real-logic/agrona)：Agrona提供了一个数据结构和实用方法库，这是用Java构建高性能应用程序时常见的需求。
* [Koloboke](https://github.com/leventov/Koloboke)：精心设计的Java集合框架扩展，具有原始类型特化等功能。
* [Javolution](https://github.com/javolution/javolution)：用于实时和嵌入式系统的Java核心库。
* [Trove](https://bitbucket.org/trove4j/trove/src/master/)：Trove库为Java提供高速对象和原始集合。
* [Primitive Collections](https://github.com/Speiger/Primitive-Collections)：一个原始集合库，可减少内存使用并提高性能。
* [Capsule](https://github.com/usethesource/capsule)：Capsule旨在成为Java 11+的成熟(不可变)集合库，完全围绕持久尝试构建。
* [Glazed Lists](https://github.com/glazedlists/glazedlists)：Java的开源列表转换。
* [LMAX Collections](https://github.com/LMAX-Exchange/LMAXCollections)：高性能集合库，由英国外汇交易公司LMAX开发。
* [Paguro](https://github.com/GlenKPeterson/Paguro)：JVM的泛型、空安全、不可变集合和函数式转换。
* [Persistent Collections](https://github.com/pmem/pcj)：Java的持久集合库。
* [Zero-Allocation Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing)：用于对Java中的任何字节序列进行哈希处理，包括各种原始数组、缓冲区、CharSequence等。
* [Jcabi-Immutable](https://github.com/jcabi/jcabi-immutable)：原始Java不可变集合，如Array、ArraySet等。
* [LambdaJ](https://github.com/mariofusco/lambdaj)：以伪函数和静态类型的方式操作集合的Java库。
* [GlueList](https://github.com/ertugrulcetin/GlueList)：GlueList是一个全新的List实现，它比ArrayList和LinkedList快得多。
* [TinyMap](https://github.com/intelie/tinymap)：内存高效的不可变HashMap/HashSet。
* [CompactHashMap](https://github.com/vlsi/compactmap)：这是HashMap的内存高效替代方案。
* [PauselessHashMap](https://github.com/giltene/PauselessHashMap)：java.util.HashMap兼容的Map，在调整大小时不会停止put或get。
* [SmoothieMap](https://github.com/TimeAndSpaceIO/SmoothieMap)：SmoothieMap是Java的Map实现，具有最低的内存使用率并且不存在重哈希延迟峰值。

## 协程库

* [Loom](https://github.com/openjdk/loom)：JDK实现的虚拟线程、结构化并发项目，Oracle开源。
* [Quasar](https://github.com/puniverse/quasar)：Quasar是一个为Java和Kotlin提供高性能轻量级线程、Actor以及其他异步编程工具的库。
* [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)：Kotlin多平台的协程支持库。
* [Kilim](https://github.com/kilim/kilim)：Kilim是一个Java消息传递框架，它提供超轻量级线程和在这些线程之间实现快速、安全、零复制消息传递的设施，由剑桥大学博士开源。
* [EA Async](https://github.com/electronicarts/ea-async)：EA Async在JVM上实现Async/Await，允许程序员以顺序方式编写异步代码，由艺电开源。
* [Coroutines](https://github.com/offbynull/coroutines)：Coroutines是一个Java工具包，允许你用Java编写协程。
* [Coroutines](https://github.com/esoco/coroutines)：该项目包含协程的纯Java实现。
* [Tascalate JavaFlow](https://github.com/vsilaev/tascalate-javaflow)：该项目包含使用Continuation开发Java应用程序的库和工具。

## 并发编程

* [Disruptor](https://github.com/LMAX-Exchange/disruptor)：Disruptor是一个高性能线程间消息传递库，由英国外汇交易公司LMAX开发。
* [JCTools](https://github.com/JCTools/JCTools)：JCTools旨在提供JDK目前缺少的一些并发数据结构。
* [AsyncTool](https://gitee.com/jd-platform-opensource/asyncTool)：JCTools是解决任意的多线程并行、串行、阻塞、依赖、回调的并行框架，来自于京东主App后台。
* [ZIO](https://github.com/zio/zio)：ZIO是一个用于异步和并发编程的零依赖Scala库。
* [TransmittableThreadLocal](https://github.com/alibaba/transmittable-thread-local)：TransmittableThreadLocal提供一个增强的InheritableThreadLocal，即使使用线程池组件也可以在线程之间传输值，由阿里开源。
* [ConcurrentLinkedHashMap](https://github.com/ben-manes/concurrentlinkedhashmap)：java.util.LinkedHashMap的高性能版本，用作软件缓存。
* [Trickle](https://github.com/spotify/trickle)：Trickle是一个用于编写异步代码的小型库，由Spotify开源。
* [JDeferred](https://github.com/jdeferred/jdeferred)：JDeferred是一个Java Deferred/Promise库，类似于JQuery的Deferred Object。
* [Concurrentli](https://github.com/linkedin/concurrentli)：Concurrentli扩展了java.util.concurrent的多线程类，为多线程Java程序增加了便利性、效率和新工具，由LinkedIn开源。
* [Menagerie](https://github.com/sfines/menagerie)：Menagerie是基于ZooKeeper的Java并发库。
* [Thread Affinity](https://github.com/OpenHFT/Java-Thread-Affinity)：该库允许你将线程绑定到给定核心，这可以提高性能。
* [OPEL](https://github.com/allegro/opel)：OPEL旨在让你编写简单、简短的异步表达式，它使用Parboiled作为语言语法引擎和通用的Java 8 CompletableFuture，由Allegro开源。
* [Chronicle Threads](https://github.com/OpenHFT/Chronicle-Threads)：该库提供高性能事件循环实现和实用函数来帮助处理线程和并发。
* [Tascalate Concurrent](https://github.com/vsilaev/tascalate-concurrent)：该库提供了CompletionStage接口和相关类的实现，旨在支持长时间运行的阻塞任务(通常是I/O绑定)。
* [Completable Futures](https://github.com/spotify/completable-futures)：Completable Futures是一组实用函数，用于简化Java 8中异步代码的使用，由Spotify开源。
* [DynamicTp](https://github.com/dromara/dynamic-tp)：基于配置中心的轻量级动态线程池，内置监控告警功能，集成常用中间件线程池管理，可通过SPI自定义扩展实现，由美团开源。
* [Async Util](https://github.com/IBM/java-async-util)：提供异步协调工具，包括CompletionStages的迭代生产/消费和非阻塞异步互斥支持，由IBM开源。
* [TaskManager](https://github.com/iqiyi/TaskManager)：TaskManager是一种支持依赖关系、任务兜底策略的任务调度管理工具，由爱奇艺开发。
* [Hippo4j](https://github.com/opengoofy/hippo4j)：国产异步线程池框架，支持线程池动态变更、监控、报警。
* [Gobrs-Async](https://gitee.com/dromara/gobrs-async)：Gobrs-Async是一款功能强大、配置灵活、带有全链路异常回调、内存优化、异常状态管理于一身的高性能多线程并发编程和动态编排框架，由dromara社区开源。
* [ParSeq](https://github.com/linkedin/parseq)：ParSeq是一个可以更轻松地用Java编写异步代码的框架，LinkedIn开源。
* [Threadly](https://github.com/threadly/threadly)：协助安全并发Java开发的工具库，提供独特的基于优先级的线程池，以及安全分配线程工作的方法。
* [Conditional](https://github.com/line/conditional)：Conditional是一个超轻量级库，可帮助你组合多个条件表达式并使它们轻松异步，由Line开源。
* [CompletableFuture Fu](https://github.com/foldright/cffu)：CompletableFuture Fu是一个CompletableFutureCF辅助增强库，提升CF使用体验并减少误用。
* [BascomTask](https://github.com/eBay/bascomtask)：Java的轻量级、低摩擦进程内并行任务管理，由eBay开源。
* [Tascalate Async Await](https://github.com/vsilaev/tascalate-async-await)：Java版本8到17的Async/Await异步编程模型。
* [Futuristic-Feline](https://github.com/spotify/futuristic-feline)：Futuristic-Feline是一个用于在运行时检测阻塞Java Future的库，由Spotify开源。
* [GPars](https://github.com/GPars/GPars)：GPars框架为Java开发人员提供了直观且安全的方法来同时处理Java或Groovy任务。
* [Nodes](https://github.com/twitter/nodes)：Nodes是一个用Java实现服务异步依赖图的库，由Twitter开源。
* [Future](https://github.com/traneio/future)：JVM的高性能Future实现。
* [Dirigiste](https://github.com/clj-commons/dirigiste)：Dirigiste提供了java.util.concurrent.ExecutorService的快速、功能丰富的检测版本，并提供了一种将该检测提供给控制机制的方法，该控制机制可以根据需要扩大或缩小池。
* [Futures-Extra](https://github.com/spotify/futures-extra)：Futures-Extra是一组小型实用函数，用于简化Guava的ListenableFuture类的使用，由Spotify开源。
* [Ox](https://github.com/softwaremill/ox)：开发人员友好的JVM结构化并发库，基于Project Loom。
* [Jetlang](https://github.com/jetlang/core)：Jetlang提供了一个高性能的Java线程库。
* [Executor-Service](https://github.com/vmlens/executor-service)：支持多个写入和单个读取线程的ExecutorService
* [JOX](https://github.com/softwaremill/jox)：Java中的快速且可扩展的Channel，设计用于与Project Loom一起使用。
* [Async](https://github.com/OpenTSDB/async)：受Twisted API启发的异步Java处理构建块。
* [Java Async-Await](https://github.com/AugustNagro/java-async-await)：Java的Async-Await支持。
* [TwTasks](https://github.com/transferwise/tw-tasks-executor)：一个以分布式方式执行任意异步代码并具有完全一致性保证的框架。
* [ConcurrencyFreaks](https://github.com/pramalhe/ConcurrencyFreaks)：并发数据结构和同步机制的库。
* [Dexecutor](https://github.com/dexecutor/dexecutor-core)：Dexecutor是一个非常轻量级的框架，可以以可靠的方式执行依赖/独立任务，为此它提供了最少的API。
* [Rqueue](https://github.com/sonus21/rqueue)：Rqueue是一个为Spring框架构建的异步任务执行器，基于Redis支持的Spring框架的消息传递库。
* [JBoss Threads](https://github.com/jbossas/jboss-threads)：JBoss Threads是一个管理和执行Java线程的库。

## Actor模型

* [Akka](https://github.com/akka/akka)：Akka是一个免费开源的软件工具包，使用Akka可以很容易的在JVM上构建高并发和分布式的应用程序，由Lightbend开源。
* [Fibry](https://github.com/lucav76/Fibry)：Fibry是一个实验性的Actor系统，其构建简单且灵活，也是第一个使用Project Loom中的虚拟线程的Java Actor系统。
* [XOOM Actor](https://github.com/vlingo/xoom-actors)：用于类型安全Actor模型的VLINGO XOOM平台SDK，使用Java和其他JVM语言提供响应式并发、高可扩展性、高吞吐量和弹性。
* [JActor](https://github.com/laforge49/JActor)：Java的Actor库。
* [Kontraktor](https://github.com/RuedigerMoeller/kontraktor)：由分布式Actor模型提供支持的异步远程通信的无样板且一致的抽象。
* [Actr](https://github.com/zakgof/actr)：简单、快速且类型安全的Java Actor模型实现。
* [Ptolemy II](https://github.com/icyphy/ptII)：由一组支持异构并发建模和设计的Java包组成。
* [ReActed](https://github.com/reacted-io/reacted)：Ptolemy II是基于Actor的响应式Java框架，用于本地和分布式环境中的微服务，由加州大学伯克利分校开源。
* [Orbit](https://github.com/orbit/orbit)：用于构建分布式系统的虚拟Actor框架。
* [Apache Pekko](https://github.com/apache/incubator-pekko)：Apache Pekko是一个开源框架，用于构建并发、分布式、弹性的应用程序。
* [PraxisCORE](https://github.com/praxis-live/praxiscore)：PraxisCORE是用于网络物理编程的模块化JVM运行时，支持实时系统的实时编码。
* [Elastic Actors](https://github.com/elasticsoftwarefoundation/elasticactors)：ElasticActors是一个Actor框架，它实现Actor模型并提供一些附加服务，例如持久性和可扩展性。

## GraphQL

* [GraphQL Java](https://github.com/graphql-java/graphql-java)：GraphQL Java实现。
* [DGS-Framework](https://github.com/netflix/dgs-framework)：DGS Framework是由Netflix开发的Spring Boot的GraphQL服务器框架。
* [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin)：Apollo Kotlin是一个GraphQL客户端，可根据GraphQL查询生成Kotlin和Java模型。
* [Rejoiner](https://github.com/google/rejoiner)：用于从gRPC微服务和其他Protobuf源生成统一的GraphQL模式，由Google开发。
* [Spring GraphQL](https://github.com/spring-projects/spring-graphql)：Spring GraphQL为基于GraphQL Java构建的Spring应用程序提供支持。
* [GraphQL Kotlin](https://github.com/ExpediaGroup/graphql-kotlin)：GraphQL Kotlin构建在GraphQL Java之上，可简化在Kotlin中运行GraphQL客户端和服务器，由Expedia开源。
* [GraphQL SPQR](https://github.com/leangen/graphql-spqr)：GraphQL SPQR是一个简单易用的库，用于在Java中快速开发GraphQL API。
* [GraphQL SPQR Starter](https://github.com/leangen/graphql-spqr-spring-boot-starter)：由GraphQL SPQR提供支持的Spring Boot Starter。
* [GraphQL Spring Boot](https://github.com/graphql-java-kickstart/graphql-spring-boot)：集成GraphQL Java和Spring Boot的库。
* [Elide](https://github.com/yahoo/elide)：Elide是一个Java库，可以轻松设置模型驱动的GraphQL或JSON API Web服务，由Yahoo开源。
* [Lacinia](https://github.com/walmartlabs/lacinia)：Lacinia是一个实现GraphQL规范的Clojure库，由沃尔玛开源。
* [Sangria](https://github.com/sangria-graphql/sangria)：Sangria是一个Scala GraphQL库。
* [GraphQL Java Annotations](https://github.com/Enigmatis/graphql-java-annotations)：该库为GraphQL模式定义提供基于注解的语法。
* [KGraphQL](https://github.com/aPureBase/KGraphQL)：KGraphQL是GraphQL的Kotlin实现。
* [GraphQL-Calculator](https://github.com/graphql-calculator/graphql-calculator)：GraphQL Calculator是一个轻量级的GraphQL查询计算引擎。
* [Microprofile GraphQL](https://github.com/eclipse/microprofile-graphql)：MicroProfile框架中用于构建GraphQL应用程序的GraphQL服务器和客户端规范。
* [Nodes](https://github.com/americanexpress/nodes)：Nodes是一个GraphQL客户端，旨在根据标准模型定义构建查询，由美国运通开源。
* [GraphQL Java Generator](https://github.com/graphql-java-generator/graphql-maven-plugin-project)：GraphQL Java Generator可以轻松地以模式优先的方式在Java中使用GraphQL。
* [GraphQL Codegen](https://github.com/kobylynskyi/graphql-java-codegen)：GraphQL Java Codegen可以轻松地让你的Java应用程序遵循模式优先的方法，无论它是服务器应用程序还是客户端应用程序。
* [GraphQL JPA Query](https://github.com/introproventures/graphql-jpa-query)：GraphQL JPA Query库使用JPA规范为你的JPA实体Java类使用GraphQL Java派生和构建GraphQL API。
* [HyperGraphQL](https://github.com/hypergraphql/hypergraphql)：HyperGraphQL是一个GraphQL接口，用于在Web上查询和提供链接数据。
* [GraphQL Java Tools](https://github.com/graphql-java-kickstart/graphql-java-tools)：该库允许使用GraphQL模式语言来构建GraphQL Java模式。
* [Mocca](https://github.com/paypal/mocca)：Mocca是JVM语言的GraphQL客户端，其目标是易于使用、灵活和模块化，由Paypal开源。
* [GraphQL-APIGen](https://github.com/Distelli/graphql-apigen)：使用GraphQL模式生成Java API，促进“模式优先”开发。
* [RDBMS To GraphQL](https://github.com/ebridges/rdbms-to-graphql)：这是一个命令行工具，可用于从RDBMS数据库生成GraphQL模式，目前它可以与MySQL和PostgreSQL配合使用。
* [GraphQL Schema From Introspection Generator](https://github.com/mstachniuk/graphql-schema-from-introspection-generator)：该库可帮助你基于内省查询响应生成GraphQL模式。
* [GraphQL-Braid](https://bitbucket.org/atlassian/graphql-braid/src/master/)：模式拼接-将GraphQL后端合并到一个模式中。
* [Lilo](https://github.com/friatech/lilo)：Lilo是一个超快的GraphQL拼接库，该项目受到Atlassian Braid的启发。
* [GraphQL Orchestrator Java](https://github.com/graph-quilt/graphql-orchestrator-java)：GraphQL-Orchestrator-Java通过提供统一的GraphQL模式，简化了从各种GraphQL微服务访问数据的过程。
* [Test GraphQL Java](https://github.com/vimalrajselvam/test-graphql-java)：用于简化GraphQL测试的Java库。
* [Spring GraphQL Common](https://github.com/yandooo/spring-graphql-common)：Spring框架GraphQL库。
* [GraphQL JPA](https://github.com/jcrygier/graphql-jpa)：这是一个简单的项目，用于扩展GraphQL-Java并让它从JPA模型派生模式。
* [GraphKool](https://github.com/beyondeye/graphkool)：Kotlin中的GraphQl-Java实用程序。
* [SchemaGen-GraphQL](https://github.com/bpatters/schemagen-graphql)：GraphQL-Java插件，增加了对企业级应用程序的模式生成和执行的支持。
* [GraphQL EMF](https://github.com/hallvard/graphql-emf)：支持EMF模型和数据。
* [Vertx-GraphQL-Client](https://github.com/graphqly/vertx-graphql-client)：代码优先GraphQL客户端的优雅实现。
* [Federation JVM](https://github.com/apollographql/federation-jvm)：Graphql-Java的Apollo Federation规范的实现。
* [GraphQL Java Servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet)：GraphQL Java的Servlet端口。
* [GraphQL JPA Spring Boot](https://github.com/timtebeek/graphql-jpa-spring-boot-starter)：GraphQL JPA的Spring Boot Starter；使用GraphQL公开JPA实体。
* [Light4j-GraphQL](https://github.com/networknt/light-graphql-4j)：基于Light-4j的GraphQL实现。
* [Gorm GraphQL](https://github.com/grails/gorm-graphql)：GORM的自动GraphQL模式生成器。
* [GraphQL Java Extended Validation](https://github.com/graphql-java/graphql-java-extended-validation)：该库为Graphql-Java提供了字段和字段参数的扩展验证。
* [GraphQL Java DataLoader](https://github.com/graphql-java/java-dataloader)：这个小而简单的实用程序库是Facebook DataLoader的纯Java 8端口。
* [GraphQL Java Extended Scalars](https://github.com/graphql-java/graphql-java-extended-scalars)：Graphql-Java的扩展标量库。
* [GraphQL Java DateTime](https://github.com/tailrocks/graphql-java-datetime)：一组与Graphql-Java一起使用的符合RFC 3339的日期/时间标量类型。
* [Nadel](https://github.com/atlassian-labs/nadel)：Nadel是一个将多个GraphQL服务组合在一起的Kotlin库，由Atlassian开源。
* [Multipart Spring GraphQL](https://github.com/nkonev/multipart-spring-graphql)：Spring GraphQL的Multipart支持库。
* [GraphQL Filter Java](https://github.com/intuit/graphql-filter-java)：该库可帮助GraphQL开发人员构建具有细粒度过滤支持的出色API。

## 任务调度

* [XXL-JOB](https://github.com/xuxueli/xxl-job)：XXL-JOB是一个分布式任务调度平台，其核心设计目标是开发迅速、学习简单、轻量级、易扩展。
* [Quartz](https://github.com/quartz-scheduler/quartz)：Quartz是一个功能丰富的开源任务调度库，几乎可以集成在任何Java应用程序中，由Terracotta公司开源。
* [Apache ElasticJob](https://github.com/apache/shardingsphere-elasticjob)：ElasticJob是一个轻量级、去中心化的解决方案，提供分布式任务分片服务，由当当网开源。
* [PowerJob](https://github.com/PowerJob/PowerJob)：PowerJob是一个开源的分布式计算和作业调度框架，它允许开发人员轻松地在自己的应用程序中调度任务。
* [Spring Scheduler](https://docs.spring.io/spring-framework/reference/integration/scheduling.html)：Spring框架提供的任务调度功能。
* [Jobrunr](https://github.com/jobrunr/jobrunr)：一种在Java中执行后台处理的极其简单的方法，由持久存储支持。
* [SchedulerX](https://www.aliyun.com/aliware/schedulerx)：SchedulerX是阿里自研的基于Akka架构的分布式任务调度平台，支持Cron定时、一次性任务、任务编排、分布式数据处理，具有高可用、可视化、可运维、低延时等能力。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：ShedLock确保你的计划任务最多同时执行一次。
* [DisJob](https://github.com/dromara/disjob)：DisJob是一款分布式的任务调度及分布式计算框架，由dromara社区开源。
* [Saturn](https://github.com/vipshop/Saturn)：Saturn是唯品会打造的一个提供分布式、容错、高可用的作业调度服务的平台。
* [Cron Utils](https://github.com/jmrozanec/cron-utils)：Cron-Utils是一个Java库，用于定义、解析、验证、迁移cron以及获取人类可读的描述。
* [Apache Aurora](https://github.com/apache/aurora)：Apache Aurora允许你使用Apache Mesos集群作为私有云，它支持运行长时间运行的服务、cron作业和临时任务。
* [DB Scheduler](https://github.com/kagkarlsson/db-scheduler)：适用于Java的持久集群友好调度程序。
* [OpenJob](https://github.com/open-job/openjob)：Openjob是一个分布式高性能任务调度框架，支持多个cronjob、延迟任务、工作流，轻量级分布式计算，无限水平扩展，具有高扩展性和容错能力。
* [PlumeJob](https://gitee.com/plumeorg/plumejob)：PlumeJob是一个去中心化的分布式调度系统，集成简单易用，由plume组织开源。
* [TBSchedule](https://github.com/nmyphp/tbschedule)：TBSchedule是一个由阿里开源的支持分布式的调度框架。
* [Sundial](https://github.com/knowm/Sundial)：Sundial是一个轻量级的Java任务调度框架。
* [Kob](https://github.com/LianjiaTech/kob)：中心化的作业调度系统，定义了任务调度模型，实现了任务调度的统一管理和监控，由链家开源。
* [Wisp](https://github.com/Coreoz/Wisp)：Wisp是一个用于管理重复性Java作业执行的库。
* [Android Job](https://github.com/Evernote/android-job)：用于在后台处理作业的Android库，由Evernote开源。
* [FlowJob](https://github.com/limbo-world/flowjob)：FlowJob主要用于搭建统一的任务调度平台，方便各个业务方进行接入使用。
* [Cron4j](http://www.sauronsoftware.it/projects/cron4j/)：Cron4j是Java平台的调度程序，与UNIX cron守护程序非常相似。
* [Legends](https://github.com/tongbanjie/legends)：使用Java开发的一个任务调度框架，可以远程执行一次性或重复性的Job，查看任务的执行状态以及任务结果，由铜板街开源。
* [Job-Dispatcher](https://gitee.com/daye_daye/job-dispatcher)：国产的基于事件的流程编排和调度引擎。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [Workhorse](https://github.com/coodoo-io/workhorse)：用于后台作业和业务关键任务的Java EE作业引擎。
* [SIA-TASK](https://github.com/siaorg/sia-task)：SIA-TASK是任务调度的一体式解决方案，简单易用，由宜信开源。
* [Jobs](https://gitee.com/baomidou/jobs)：baomidou社区开源的分布式任务调度组件。
* [Light Task Scheduler](https://github.com/ltsopensource/light-task-scheduler)：LTS主要用于解决分布式任务调度问题，支持实时任务、定时任务和Cron任务。
* [CronMan](https://github.com/smmdwa/CronMan)：CronMan是一款轻量级的分布式任务调度系统。
* [Chronus](https://github.com/360digitech/chronus)：Chronus是360数科技术团队基于阿里开源项目TBSchedule重写的分布式调度。
* [Earth-Frost](https://gitee.com/justlive1/earth-frost)：Earth-Frost是一个轻量级分布式任务调度框架。
* [Schedulix](https://github.com/schedulix/schedulix)：Schedulix是一个开源企业作业调度系统。
* [Hodor](https://github.com/dromara/hodor)：Hodor是一个专注于任务调度以及任务编排的一站式分布式任务调度系统，由dromara社区开源。
* [TASKANA](https://github.com/Taskana/taskana)：TASKANA是一个任务管理组件开源库，它可以嵌入到你的应用程序中，也可以在适当的情况下独立运行。
* [Juice](https://github.com/HujiangTechnology/Juice)：Juice是沪江学习系统项目组所开发的一套基于Mesos Framework的分布式任务调度云系统，基于此系统，可以实现任何作业型任务的调度工作。
* [JS7 JobScheduler](https://github.com/sos-berlin/js7)：JS7是下一代开源作业调度程序，专为性能、弹性和安全性而设计，适用于本地和云环境中的操作。
* [JQM](https://github.com/enioka-Haute-Couture/jqm)：JQM是一个任务队列管理器。

## 配置管理

* [Pkl](https://github.com/apple/pkl)：Pkl是一种用于生成配置的编程语言，由Apple开源。
* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：Apache Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo研究院开发。
* [Typesafe Config](https://github.com/lightbend/config)：使用HOCON文件的JVM语言的配置库，由Lightbend开源。
* [Microconfig](https://github.com/microconfig/microconfig)：Microconfig的目的是让管理微服务的配置变得简单、方便，并重用公共部分。
* [Spring Cloud Config](https://github.com/spring-cloud/spring-cloud-config)：Spring Cloud Config为分布式系统中的外部化配置提供服务器端和客户端支持。
* [Apollo](https://github.com/apolloconfig/apollo)：Apollo是一个可靠的配置管理系统，适用于微服务配置管理场景，由携程开源。
* [Disconf](https://github.com/knightliao/disconf)：专注于各种分布式系统配置管理的通用组件和通用平台，提供统一的配置管理服务。
* [BRCC](https://github.com/baidu/brcc)：BRCC是一个分布式配置中心，用于统一管理应用服务的配置信息，简化资源配置的维护成本，由百度开源。
* [Amper](https://github.com/JetBrains/amper)：Amper是一个项目配置工具，其目标是改善项目配置体验和工具性，即IDE内部的支持，同时还提供流畅的开箱即用体验，由JetBrains开源。
* [Central Dogma](https://github.com/line/centraldogma)：Central Dogma是一个基于Git、ZooKeeper和HTTP/2的开源、高可用、版本控制的服务配置仓库，由Line开源。
* [XXL-Conf](https://gitee.com/xuxueli0323/xxl-conf)：XXL-CONF是一个轻量级分布式配置管理平台，拥有轻量级、秒级动态推送、多环境、跨语言、跨机房、配置监听、权限控制、版本回滚等特性。
* [Archaius](https://github.com/Netflix/archaius)：Archaius是一个配置库，用于将静态和动态配置的混合作为单个配置单元进行访问，由Netflix开源。
* [Cerberus](https://github.com/Nike-Inc/cerberus)：Cerberus API是一个云原生、可扩展的Spring Boot应用程序，可以安全地存储应用程序属性和文件，并具有强大的审核功能，Nike开源。
* [Apache Commons Configuration](https://github.com/apache/commons-configuration)：Apache Commons Configuration库提供了一个通用配置接口，使Java应用程序能够从各种源读取配置数据。
* [QConfig](https://github.com/qunarcorp/qconfig)：QConfig中心式配置中心，提供高可用的配置托管/动态热更新服务，由去哪儿开源。
* [NightConfig](https://github.com/TheElectronWill/night-config)：NightConfig是一个功能强大且易于使用的Java配置库，用Java 8编写。
* [Config Toolkit](https://github.com/dangdangdotcom/config-toolkit)：Config Toolkit用于简化从本地配置文件到Zookeeper的迁移，由当当开源。
* [CFG4J](https://github.com/cfg4j/cfg4j)：CFG4J是用Java编写的分布式应用程序的现代配置库。
* [ConfigMe](https://github.com/AuthMe/ConfigMe)：ConfigMe是一个开箱即用的配置管理库，支持YAML。
* [Configurate](https://github.com/SpongePowered/Configurate)：Configurate是一个用于Java应用程序的简单配置库，它提供基于节点的数据表示，能够处理各种配置格式。
* [Avaje Config](https://github.com/avaje/avaje-config)：Avaje Config为JVM应用程序提供外部配置，可以通过YAML或Properties文件提供配置，并使用命令行参数和资源指定要加载的文件。
* [Shepher](https://github.com/XiaoMi/shepher)：Shepher是ZooKeeper的管理工具，在小米作为配置管理中心使用。
* [Waterfall Config](https://github.com/Accenture/waterfall-config)：一个简单的Java配置库，很大程度上基于Typesafe Config，并具有一些附加的固执己见的功能，由Accenture开源。
* [SmallRye Config](https://github.com/smallrye/smallrye-config)：SmallRye Config是一个库，提供了配置应用程序、框架和容器的方法。
* [OWNER](https://github.com/matteobaccan/owner)：OWNER是一个Java库，其目标是最大限度地减少通过Java properties处理应用程序配置所需的代码。
* [Konf](https://github.com/uchuhimo/konf)：Konf是一个适用于Kotlin/Java/Android的类型安全的级联配置库，支持大多数配置格式。
* [Gestalt](https://github.com/gestalt-config/gestalt)：Gestalt是一个功能强大的Java配置库，旨在简化你在软件项目中处理和管理配置的方式。
* [Simple YAML](https://github.com/Carleslc/Simple-YAML)：Simple-YAML是一个旨在为你的程序、工具和插件创建配置文件的库。
* [Spring Fu](https://github.com/spring-projects-experimental/spring-fu)：Spring Fu是JaFu(Java DSL)和KoFu(Kotlin DSL)的孵化器，旨在以声明式方式使用代码显式配置Spring Boot，并得益于自动完成功能而具有出色的可发现性。
* [Config-Magic](https://github.com/brianm/config-magic)：Java的便捷配置库。
* [MicroProfile Config](https://github.com/eclipse/microprofile-config)：MicroProfile配置功能。
* [Jeesuite](https://gitee.com/vakinge/jeesuite-config)：功能齐全、适合二开的配置中心，由dromara社区开源。
* [ConfigKeeper](https://gitee.com/sxfad/config-keeper)：ConfigKeeper是由随行付基于Spring Cloud研发的分布式配置中心。
* [JadConfig](https://github.com/Graylog2/JadConfig)：JadConfig是一个最小依赖的Java的简约注解驱动配置解析框架。
* [Sjsonnet](https://github.com/databricks/sjsonnet)：Jsonnet配置语言的JVM实现，由Databricks开源。

## 业务流

* [Camunda](https://github.com/camunda/camunda-bpm-platform)：Camunda Platform是一个灵活的工作流程和流程自动化框架，其核心是在JVM内运行的原生BPMN 2.0流程引擎。
* [Activiti](https://github.com/Activiti/Activiti)：Activiti是一个轻量级工作流程和BPM平台，面向业务人员、开发人员和系统管理员，由Alfresco开源。
* [Flowable](https://github.com/flowable/flowable-engine)：Flowable为开发人员、系统管理员和业务用户提供紧凑且高效的工作流程和BPM平台。
* [Conductor](https://github.com/conductor-oss/conductor)：Conductor是Netflix创建的一个平台，用于编排微服务和事件。
* [jBPM](https://github.com/kiegroup/jbpm)：jBPM是一个用于构建业务应用程序以帮助自动化业务流程和决策的工具包，JBoss社区开源。
* [jDMN](https://github.com/goldmansachs/jdmn)：jDMN为DMN中指定的决策模型提供执行引擎，这些决策可以解释或翻译为Java并在JVM上执行，由高盛银行开源。
* [Apache DolphinScheduler](https://github.com/apache/dolphinscheduler)：Apache DolphinScheduler是现代数据编排平台，以低代码敏捷创建高性能工作流程，由易观开源。
* [Piper](https://github.com/runabol/piper)：Piper是一个基于Spring Boot构建的开源分布式工作流引擎，设计非常简单。
* [Kestra](https://github.com/kestra-io/kestra)：Kestra是一个通用的开源编排器，可以简化计划和事件驱动的工作流程。
* [Maestro](https://github.com/Netflix/maestro)：Maestro是一款通用工作流编排器，为Netflix的数据平台用户提供完全托管的工作流即服务(WAAS)。
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
* [RuoYi Activiti](https://gitee.com/shenzhanwang/RuoYi-activiti)：基于Activiti 6.0，集流程设计、流程部署、流程执行、任务办理、流程监控于一体的开源工作流开发平台。
* [F2BPM](https://www.f2bpm.com/)：F2BPM是一款纯国产工作流引擎，遵循WFMC/BPMN2.0的规范。
* [盘古BPM](https://gitee.com/pangu-dm/pangubpm-dmn)：盘古BPM工作流平台是国内首款开源的互联网决策引擎系统，拥有独立的DMN1.3标准设计器、解析器、决策引擎、支持决策表、DRD、DRG。
* [JsonFlow](https://gitee.com/jackrolling/jsonflow-ui)：简单但强大易用易扩展且适应复杂场景的中国式审批的工作流引擎系统。
* [Smart Flow](https://gitee.com/smartboot/smart-flow)：SmartFlow是一个轻量、灵活的业务流程编排框架，支持业务流程中常见的条件分支控制、子流程、业务组件异步和降级等功能。
* [COPPER](https://github.com/copper-engine/copper-engine)：COPPER是一个开源、强大、轻量且易于配置的工作流引擎，它使用Java作为工作流的描述语言。
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

## API管理

* [Yaade](https://github.com/EsperoTech/yaade)：Yaade是一个开源、自托管、协作式API开发环境。
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

## 反射库

* [Reflections](https://github.com/ronmamo/reflections)：Reflections会扫描项目的类路径元数据并为其建立索引，从而允许在运行时对类型系统进行反向传递查询。
* [jOOR](https://github.com/jOOQ/jOOR)：jOOR是用于反射的流式API库，可以以更直观的方式访问Class类结构。
* [ReflectASM](https://github.com/EsotericSoftware/reflectasm)：ReflectASM是一个非常小的Java库，它通过使用代码生成来提供高性能反射。
* [Objenesis](https://github.com/easymock/objenesis)：Objenesis是一个专门用于在创建对象时绕过构造函数的库。
* [Mirror](https://github.com/Genymobile/mirror)：Java和Android的轻松反射。
* [Apache Commons ClassScan](https://commons.apache.org/sandbox/commons-classscan)：ClassScan可以提供有关运行时可用的所有类的信息，无论该类是否已加载。
* [FEST-Reflect](https://github.com/alexruiz/fest-reflect)：FEST-Reflect提供了直观、紧凑且类型安全的流式API，使Java反射非常易于使用：不再需要强制转换、检查异常、PriviledgedActions或setAccessible调用。
* [Lambda-Factory](https://github.com/Hervian/lambda-factory)：Lambda-Factory是一个Java实用程序项目，它提供了基于反射的方法调用的快速替代方案。
* [Mirror](http://projetos.vidageek.net/mirror/mirror/)：Mirror的创建是为了解决一个简单的问题，通常命名为ReflectionUtil，它几乎适用于所有依赖反射来完成高级任务的项目。
* [Jandex](https://github.com/smallrye/jandex)：Jandex是一个节省空间的Java类文件索引器和离线反射库。
* [Reflection Util](https://github.com/cronn/reflection-util)：简化Java反射常见用例的工具类。
* [Paranamer](https://github.com/paul-hammant/paranamer)：Paranamer是一个允许在运行时访问非私有方法和构造函数的参数名称的库。
* [Mirror](https://github.com/vidageek/mirror)：Java反射API上的简单DSL层。
* [Jeflect](https://github.com/RomanQed/jeflect)：一组旨在与反射交互并加速反射的实用程序。
* [Reflecto](https://github.com/cariochi/reflecto)：Reflecto是一个功能强大的Java反射库，旨在简化深度反射任务。

## 日期时间

* [Joda-Time](https://github.com/JodaOrg/joda-time)：Joda-Time提供了Java日期和时间类的优质替代品。
* [Prettytime](https://github.com/ocpsoft/prettytime)：Java的社交风格日期和时间格式。
* [Time4J](https://github.com/MenoData/Time4J)：Time4J是围绕Date、Calendar和SimpleDateFormat的旧Java类的完整且高端的替代品。
* [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra)：ThreeTen-Extra提供了额外的日期时间类来补充JDK 8中的类。
* [XK-Time](https://gitee.com/xkzhangsan/xk-time)：XK-Time包含时间转换、时间计算、时间格式化、时间解析、日历、时间Cron表达式和时间NLP等工具。
* [Date4j](https://github.com/IanDarwin/date4j)：Date4j是Java内置日期类的轻量级替代品。
* [ThreeTen](https://github.com/ThreeTen/threetenbp)：ThreeTen-Backport提供Java 8日期时间类到Java 6和7的向后移植。
* [Jollyday](https://github.com/svendiedrichsen/jollyday)：确定给定年份、国家/名称以及最终州/地区的假期。
* [Jollyday](https://github.com/focus-shift/jollyday)：Jollyday是一个查询公共假期的Java库，目前支持70多个国家/地区。
* [iCal4j](https://github.com/ical4j/ical4j)：iCal4j是一个Java库，用于读取和写入RFC2445中定义的iCalendar数据流。
* [TimeAgo](https://github.com/marlonlom/timeago)：一个简单的Java库，用于将日期显示为相对时间之前的语言。
* [Biweekly](https://github.com/mangstadt/biweekly)：Biweekly是一个用Java编写的iCalendar库。
* [Clocks](https://github.com/tim-group/clocks)：用于测试和Joda-Time集成的java.time.Clock实现。
* [Zmanim](https://github.com/KosherJava/zmanim)：Zmanim库是一个特殊日历的API，可以计算不同的天文时间，包括日出和日落以及犹太zmanim或祈祷和其他犹太宗教职责的宗教时间。
* [Adhan Kotlin](https://github.com/batoulapps/adhan-kotlin)：Adhan是一个经过充分测试和记录良好的库，用于计算伊斯兰祈祷时间。
* [TimeFlow](https://github.com/stawirej/timeflow)：提供Java时钟，可以在测试中调整，无需使用依赖注入。
* [GoodTimes](https://github.com/bdkosher/goodtimes)：Groovy的Java 8日期/时间API增强功能。
* [DateParser](https://github.com/sisyphsu/dateparser)：DateParser是一个智能且高性能的日期时间解析器库，它支持数百种不同的模式。
* [Internet Time Utility](https://github.com/ethlo/itu)：ISO格式日期时间的极快解析器和格式化程序。
* [Chronos](https://github.com/XiaoMi/chronos)：提供全局严格单调递增时间戳的网络服务，由小米开源。
* [Lib-Recur](https://github.com/dmfs/lib-recur)：该库解析RFC 5545和RFC 2445中定义的重复字符串并迭代实例，此外，它还可以用来以方便的方式构建有效的重复字符串。
* [BusinessCalendar4J](https://github.com/yusuke/businessCalendar4J)：BusinessCalendar4J是一个100%纯Java业务日历库，没有额外的依赖项。
* [TickTock](https://github.com/ZacSweers/ticktock)：TickTock是一个时区数据管理库，适用于JVM和Android，针对Java 8或更高版本中的java.time.* API。
* [Sunrise/SunsetLib Java](https://github.com/mikereedell/sunrisesunsetlib-java)：用于计算给定纬度/经度和日期组合的当地日出和日落的Java库。
* [Tyme4j](https://github.com/6tail/tyme4j)：Tyme4j是一个非常强大的日历工具库，可以看作Lunar的升级版，拥有更优的设计和扩展性，支持公历和农历、星座、干支、生肖、节气、法定假日等。
* [Business Hours Java](https://github.com/dhatim/business-hours-java)：这个Java库有助于处理工作时间，例如“周一到周五上午9点到下午6点，周六上午9点到中午12点”。

## 人工智能

* [FATE](https://github.com/FederatedAI/FATE)：FATE是全球首个工业级联邦学习开源框架，使企业和机构能够在数据上进行协作，同时保护数据安全和隐私，由微众银行开源。
* [Artemis](https://github.com/ls1intum/Artemis)：Artemis通过对编程练习、测验、建模任务等的即时、个人反馈，将交互式学习带入生活，由慕尼黑工业大学开源。
* [Lucida](https://github.com/claritylab/lucida)：Lucida是一款基于语音和视觉的智能个人助理，灵感来自Sirius。
* [SUSI.AI Server](https://github.com/fossasia/susi_server)：SUSI.AI是一款智能开源个人助理，它能够通过使用API来执行诸如音乐播放、制作待办事项列表、设置闹钟、流播客、播放有声读物以及提供天气、交通和其他实时信息等操作，从而进行聊天和语音交互，由FOSSASIA组织开源。
* [GDX AI](https://github.com/libgdx/gdx-ai)：GDX AI是一个高性能框架，提供游戏行业使用的一些最常见的AI技术。
* [AIMA Java](https://github.com/aimacode/aima-java)：Russell和Norvig的《人工智能-一种现代的方法》中算法的Java实现。
* [EdgeChains](https://github.com/arakoodev/EdgeChains)：EdgeChains.js是一种用于生产友好的生成式AI的语法。
* [AIAS](https://gitee.com/mymagicpower/AIAS)：人工智能加速器套件，提供SDK、平台引擎、场景套件。
* [Dubhe](https://gitee.com/zhijiangtianshu/Dubhe)：之江天枢人工智能开源平台是由之江实验室牵头，联合国内顶尖科研力量共同打造的国产化自主可控的人工智能开源平台。
* [AllData](https://github.com/alldatacenter/alldata)：AllData大数据产品是可定义数据中台，以数据平台为底座、数据中台为桥梁，以机器学习平台、GPT平台为框架，提供全链路数字化解决方案。
* [Hbox](https://github.com/Qihoo360/XLearning)：Hbox是一个结合大数据和人工智能的便捷高效的调度平台，支持多种机器学习、深度学习框架，由360开源。
* [ModernMT](https://github.com/modernmt/modernmt)：ModernMT是一种基于Fairseq Transformer模型的上下文感知、增量和分布式通用神经机器翻译技术。
* [Malmo](https://github.com/microsoft/malmo)：Malmo是一个建立在Minecraft之上的人工智能实验和研究平台，由Microsoft开源。
* [XEF](https://github.com/xebia-functional/xef)：XEF是一站式库，以LLM、图像生成等形式将现代AI的力量带入你的应用程序或服务，由Xebia开源。
* [Baidu AIP SDK](https://github.com/Baidu-AIP/java-sdk)：百度AI开放平台Java SDK。
* [Xtreme1](https://github.com/xtreme1-io/xtreme1)：Xtreme1是一款用于多模态数据训练的一体化数据标记和注释平台，支持3D LiDAR点云、图像和LLM。
* [Starwhale](https://github.com/star-whale/starwhale)：Starwhale是一个MLOps/LLMOps平台，可让你的模型创建、评估和发布变得更加轻松，由星鲸科技开源。
* [Intelligent Java](https://github.com/intelligentnode/IntelliJava)：IntelliJava是使用Java与最新语言模型和深度学习框架集成的终极工具。
* [SD4J](https://github.com/oracle-samples/sd4j)：此仓库包含在ONNX运行时之上运行的Stable Diffusion推理的实现，由Oracle开源。
* [jAER](https://github.com/SensorsINI/jaer)：用于地址事件表示(AER)神经形态处理的Java工具，由苏黎世联邦理工学院开源。
* [Serenade](https://github.com/serenadeai/serenade)：该仓库包含Serenade客户端应用程序、在线服务(如语音引擎、代码引擎和核心应用程序)和模型训练的代码。

#### LLM

* [LangChain4j](https://github.com/langchain4j/langchain4j)：LangChain4j的目标是简化将AI/LLM功能集成到Java应用程序中。
* [Semantic Kernel](https://github.com/microsoft/semantic-kernel)：Semantic Kernel是微软开源的SDK，它将OpenAI、Azure OpenAI和Hugging Face等大语言模型(LLM)与C#、Python和Java等传统编程语言集成在一起。
* [Spring AI](https://github.com/spring-projects-experimental/spring-ai)：Spring AI项目为开发AI应用程序提供了Spring友好的API和抽象。
* [LangChain Java](https://github.com/HamaWhiteGG/langchain-java)：Java版LangChain，同时赋能LLM大数据。
* [TorchV](https://torchv.com/)：TorchV AI是一款基于LLM、RAG和Agent技术的人工智能PaaS产品，目标是帮助企业快速建立AI应用。
* [UseOpen LLM Server](http://www.useopen.com/p/uollm/)：UOLLM是一款使用Java语言开发AI应用的中间件产品，集成使用LLM大语言模型服务器和向量数据库，这是永源的产品。
* [JBoltAI](https://jboltai.com/)：基于JBolt平台底座打造的AI数智化应用极速开发平台，AI辅助数据库设计，可视化代码生成与模块构建，零代码AI知识库应用开发。
* [Freeplay](https://freeplay.ai/)：Freeplay让产品团队能够为客户试验、测试、监控和优化AI功能，它是一个为整个团队管理端到端LLM产品开发生命周期的工具。
* [LangStream](https://github.com/LangStream/langstream)：LangStream是一个用于构建和运行GenAI应用程序的框架，DataStax开源。
* [Agents-Flex](https://gitee.com/agents-flex/agents-flex)：Agents-Flex是一个用Java开发的AI应用开发框架，旨在简化AI应用开发。
* [Jlama](https://github.com/tjake/Jlama)：Jlama是Java的现代LLM推理引擎。
* [Langtorch](https://github.com/Knowly-ai/langtorch)：Langtorch是一个Java库，可让你轻松构建可组合的LLM应用程序。
* [Java-LangChain](https://github.com/Starcloud-Cloud/java-langchain)：Java-LangChain是一个Java 8+的LangChain实现，在Java环境中构建强大的基于LLM的应用程序。
* [CodeMind](https://github.com/Intelligent-CAT-Lab/CodeMind)：CodeMind是一个用于评估LLMs归纳代码推理的通用框架，它配备了静态分析组件，可以对结果进行深入分析，由伊利诺伊大学香槟分校开源。
* [HugAi](https://github.com/TouShang6015/Hugai-chatgpt)：HugAi是由Spring Boot集成Open AI SDK开发的一套智能AI知识库，支持GPT对话，AI绘图Midjourney、Stable Diffusion、Open AI。

#### ChatGPT客户端

* [OpenAI Java](https://github.com/TheoKanning/openai-java)：用于使用OpenAI的GPT API的Java库，支持GPT-3、ChatGPT和GPT-4。
* [OpenAI Kotlin](https://github.com/Aallam/openai-kotlin)：OpenAI API的Kotlin客户端，具有多平台和协程功能。
* [ChatGPT Java](https://github.com/PlexPt/chatgpt-java)：ChatGPT Java SDK，支持GPT3.5、GPT4 API。
* [ChatGPT Java](https://github.com/Grt1228/chatgpt-java)：ChatGPT的Java客户端。
* [ChatGPT-Java](https://github.com/AcaiSoftware/chatgpt-java)：非官方逆向工程ChatGPT API的Java包装器。
* [ChatGPT-Java](https://gitee.com/grt1228/chatgpt-java)：ChatGPT的Java客户端，OpenAI官方API的Java版SDK。
* [OpenAI-Java-SDK](https://gitee.com/devlive-community/openai-java-sdk)：为Java开发人员提供方便易用的SDK来与OpenAI模型的API进行交互。
* [EDDI](https://github.com/labsai/eddi)：EDDI是一个中间件，用于连接和管理LLM API机器人，为OpenAI ChatGPT、Facebook Hugging Face、Anthropic Claude、Google Gemini和Ollama等API提供高级提示和对话管理。
* [Easy OpenAI](https://github.com/namankhurpia/Easy-open-ai)：该仓库包含社区维护的Java中OpenAI API库，这是在应用程序中使用GPT 3/4的最简单方法。
* [Ollama4j](https://github.com/amithkoujalgi/ollama4j)：用于与Ollama服务器交互的Java库。
* [Google-Bard](https://github.com/LarryDpk/Google-Bard)：用于Google Bard提出问题并接收答案的Java库。
* [OpenAi4J](https://github.com/Lambdua/openai4j)：OpenAi4J是一个非官方Java库，旨在促进与OpenAI的GPT模型的交互，包括gpt4-turbo Vision、assistant-v2等最新功能。
* [Watson Java SDK](https://github.com/watson-developer-cloud/java-sdk)：用于使用IBM Watson服务的Java SDK。

#### 机器学习

* [Angel](https://github.com/Angel-ML/angel)：Angel是一个基于参数服务器理念的高性能分布式机器学习和图计算平台，由腾讯联合北京大学开源。
* [Spark-MLlib](https://github.com/apache/spark/tree/master/mllib)：Spark的可扩展机器学习库。
* [Alluxio](https://github.com/Alluxio/alluxio)：用于云中分析和机器学习的数据编排，由李浩源于2013年在加州大学伯克利分校AMP实验室创建。
* [Smile](https://github.com/haifengl/smile)：Smile是一个使用Java和Scala编写的快速且全面的机器学习、NLP、线性代数、图形、插值和可视化系统。
* [Flink ML](https://github.com/apache/flink-ml)：Flink ML是一个提供机器学习API和基础设施的库，可简化ML管道的构建。
* [Apache Mahout](https://github.com/apache/mahout)：Apache Mahout项目的目标是构建一个用于快速创建可扩展、高性能机器学习应用程序的环境。
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/)：Weka是用于数据挖掘任务的机器学习算法的集合，它包含用于数据准备、分类、回归、聚类、关联规则挖掘和可视化的工具，由新西兰怀卡托大学开发。
* [Breeze](https://github.com/scalanlp/breeze)：Breeze是一组用于机器学习和数值计算的库。
* [TorchServe](https://github.com/pytorch/serve)：TorchServe是一种灵活且易于使用的工具，用于在生产中提供和扩展PyTorch模型。
* [Apache Samoa](https://github.com/apache/incubator-samoa)：Apache SAMOA是一个用于挖掘大数据流的平台，它是一个分布式流式机器学习框架，包含分布式流式机器学习算法的编程抽象，由Yahoo开源。
* [Alink](https://github.com/alibaba/Alink)：Alink是基于Flink的机器学习算法平台，由阿里巴巴计算平台PAI团队开发。
* [SynapseML](https://github.com/microsoft/SynapseML)：SynapseML是一个开源库，可简化大规模可扩展机器学习管道的创建，由微软开源。
* [H2O](https://github.com/h2oai/h2o-3)：H2O是一个用于分布式、可扩展机器学习的内存平台。
* [Apache Submarine](https://github.com/apache/submarine)：Apache Submarine是一个端到端机器学习平台，允许数据科学家创建端到端机器学习工作流程。
* [GROBID](https://github.com/kermitt2/grobid)：GROBID是一个机器学习库，用于提取、解析PDF等原始文档并将其重新构建为结构化XML/TEI编码文档，重点关注技术和科学出版物。
* [EasyML](https://github.com/ICT-BDA/EasyML)：EasyML是一种基于数据流的通用系统，可简化将机器学习算法应用于现实世界任务的过程。
* [DeepDive](https://github.com/HazyResearch/deepdive)：斯坦福大学开发的信息抽取系统。
* [Oryx 2](https://github.com/OryxProject/oryx)：Apache Spark、Apache Kafka上的Lambda架构，用于实时大规模机器学习。
* [Seldon](https://github.com/SeldonIO/seldon-server)：基于Kubernetes构建的机器学习平台和推荐引擎。
* [Tribuo](https://github.com/oracle/tribuo)：Tribuo是Java中的机器学习库，提供多类分类、回归、聚类、异常检测和多标签分类，Oracle开源。
* [OpenMLDB](https://github.com/4paradigm/OpenMLDB)：OpenMLDB是一个开源机器学习数据库，为训练和推理提供计算一致特征的特征平台，由4Paradigm开源。
* [AeroSolve](https://github.com/airbnb/aerosolve)：一个从头开始设计的人性化机器学习库，由Airbnb开源。
* [Apache SystemDS](https://github.com/apache/systemds)：用于端到端数据科学生命周期的开源机器学习系统。
* [PSL](https://github.com/linqs/psl)：PSL是一种用于开发概率模型的机器学习框架，由马里兰大学和加州大学圣克鲁斯分校开发。
* [QuickML](https://github.com/sanity/quickml)：一个易于使用、功能强大且快速的Java机器学习库。
* [Datumbox](https://github.com/datumbox/datumbox-framework)：Datumbox是一个用Java编写的开源机器学习框架，可以快速开发机器学习和统计应用程序。
* [Dagli](https://github.com/linkedin/dagli)：Dagli是一个机器学习框架，可以轻松地用Java 9+编写防错误、可读、高效、可维护且可轻松部署的模型，由LinkedIn开源。
* [Sandwood](https://github.com/oracle/sandwood)：Sandwood是一种基于JVM的概率模型的语言、编译器和运行时，由Oracle开源。
* [Ytk-learn](https://github.com/kanyun-inc/ytk-learn)：Ytk-learn是一个分布式机器学习库，它实现了大多数流行的机器学习算法。
* [CERMINE](https://github.com/CeON/CERMINE)：CERMINE是一个Java库和一个Web服务，用于从包含学术出版物的PDF文件中提取元数据和内容。CERMINE是在华沙大学数学和计算建模跨学科中心的开放科学中心用Java编写的。
* [FATE-Serving](https://github.com/FederatedAI/FATE-Serving)：FATE-Serving是一个高性能、工业化的联邦学习模型服务系统，专为生产环境而设计。
* [Meka](https://github.com/Waikato/meka)：MEKA项目提供了多标签学习和评估方法的开源实现，由怀卡托大学开发。
* [TensorFlow Java](https://github.com/tensorflow/java)：TensorFlow的Java绑定。
* [Mallet](https://github.com/mimno/Mallet)：MALLET是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用。
* [Primus](https://github.com/bytedance/primus)：Primus是用于机器学习应用程序的通用分布式调度框架，它管理TensorFlow等机器学习训练器的训练生命周期和数据分布，以执行大规模分布式训练，由字节开源。
* [AMIDST](https://github.com/amidst/toolbox)：用于可扩展概率机器学习的Java工具包。
* [Metarank](https://github.com/metarank/metarank)：Metarank是一项开源排名服务，它可以帮助你构建个性化的语义/神经搜索和推荐。
* [ModelMesh](https://github.com/kserve/modelmesh)：ModelMesh框架是一个成熟的通用模型，服务于管理层/路由层，专为高规模、高密度和频繁变化的模型用例而设计，由IBM开源。
* [RapidMiner](https://rapidminer.com/)：RapidMiner是一个数据科学平台，通过GUI和Java API提供各种机器学习算法。
* [MOA](https://github.com/Waikato/moa)：MOA是一个用于大数据流挖掘的开源框架，它包括一系列机器学习算法(分类、回归、聚类、异常值检测、概念漂移检测和推荐系统)和评估工具，由怀卡托大学开发。
* [Encog](https://github.com/jeffheaton/encog-java-core)：Encog是一个纯Java机器学习框架，用于支持遗传编程、NEAT/HyperNEAT和其他神经网络技术。
* [Neuroph](https://github.com/neuroph/neuroph)：Neuroph是一个开源Java神经网络框架和神经网络开发环境。
* [SimpleDNN](https://github.com/KotlinNLP/SimpleDNN)：SimpleDNN是一个用Kotlin编写的机器学习轻量级开源库，旨在支持自然语言处理任务中的相关神经网络架构。
* [Apache PredictionIO](https://github.com/apache/predictionio)：Apache PredictionIO是一个面向开发人员、数据科学家和最终用户的开源机器学习框架。
* [Voyager](https://github.com/spotify/voyager)：Voyager是一个适用于Python和Java的近似最近邻搜索库，注重易用性、简单性和可部署性，由Spotify开源。
* [TransmogrifAI](https://github.com/salesforce/TransmogrifAI)：TransmogrifAI是一个AutoML库，用于在Spark上构建模块化、可重用、强类型的机器学习工作流，只需最少的手动调整，由Salesforce开源。
* [JSAT](https://github.com/EdwardRaff/JSAT)：JSAT是一个用于快速入门机器学习问题的库。
* [Java-ML](https://github.com/charliermarsh/java-ml)：用Java实现的一系列标准机器学习(分类)算法。
* [HTM.Java](https://github.com/numenta/htm.java)：Java中的分层临时内存实现-Numenta智能计算平台的官方社区驱动Java端口。
* [Libsvm](https://github.com/cjlin1/libsvm)：一款简单、易用、高效的SVM分类和回归软件。它可以解决C-SVM分类、nu-SVM分类、一类SVM、epsilon-SVM回归和nu-SVM回归问题，由台湾大学林智仁教授开发。
* [Elasticsearch Learning](https://github.com/o19s/elasticsearch-learning-to-rank)：用于将机器学习与Elasticsearch集成的插件。
* [ModelDB](https://github.com/VertaAI/modeldb)：用于机器学习模型版本控制、元数据和实验管理的开源系统，由Verta首席执行官Manasi Vartak在麻省理工学院进行博士研究期间创建。
* [FeatureFu](https://github.com/linkedin/FeatureFu)：FeatureFu项目旨在为大多数机器学习任务(例如统计建模(分类、聚类和回归)和基于规则的决策引擎)提供创造性和敏捷的特征工程，由LinkedIn开源。
* [Feathr](https://github.com/feathr-ai/feathr)：Feathr是一个数据和人工智能工程平台，在LinkedIn生产中广泛使用多年，并于2022年开源。
* [Shifu](https://github.com/ShifuML/shifu)：Shifu是一个构建在Hadoop之上的开源端到端机器学习和数据挖掘框架。
* [Byzer](https://github.com/byzer-org/byzer-lang)：Byzer是一种低代码、开源和分布式编程语言，用于以云原生方式进行数据管道、分析和人工智能。
* [Neureka](https://github.com/Gleethos/neureka)：一个轻量级、独立于平台、OpenCL加速的nd数组/张量库。
* [Morel](https://github.com/hydromatic/morel)：标准ML解释器，具有关系扩展，用Java实现。
* [Aurora](https://github.com/AcaiSoftware/aurora)：用于模型训练、评估、部署、调整和基准测试的Java机器学习框架。
* [StackNet](https://github.com/kaz-Anova/StackNet)：StackNet是一个计算、可扩展和分析框架，类似于前馈神经网络，并在多个级别使用Wolpert的堆栈泛化来提高机器学习问题的准确性，由伦敦大学开源。
* [ML4AI](https://gitee.com/sleechengn/ml4ai)：机器学习、人工智能、张量库。
* [Eggroll](https://gitee.com/WeBank/eggroll)：用于机器学习的简单高性能计算框架，由微众开源。
* [9nFL](https://github.com/jd-opensource/9n-mpc)：九数联邦学习整体解决方案，由京东开源。
* [WeFe](https://gitee.com/tianmiantech/WeFe)：WeFe是Welab汇立集团子公司天冕科技发起的开源项目，为联邦学习生态系统提供了一套好用的可靠的安全计算框架。
* [MacroBase](https://github.com/stanford-futuredata/macrobase)：MacroBase是一种数据分析工具，它使用机器学习优先考虑大型数据集中的注意力，由斯坦福开源。
* [MLReef](https://github.com/MLReef/mlreef)：MLReef是一个开源ML-Ops平台，可帮助你与数千名其他用户协作、复制和共享你的机器学习工作。
* [Fregata](https://github.com/TalkingData/Fregata)：Fregata是一个基于Apache Spark的轻量级、超快速的大规模机器学习库，并在Scala中提供高级API，由TalkingData开源。
* [RuleKit](https://github.com/adaa-polsl/RuleKit)：RuleKit是一种用于规则学习的多功能工具，基于顺序覆盖归纳算法，它适用于分类、回归和生存问题，由西里西亚理工大学开源。
* [Chronon](https://github.com/airbnb/chronon)：Chronon是一个平台，它消除了数据计算的复杂性并为AI/ML应用程序提供服务，由Airbnb开源。
* [BEAST](https://github.com/beast-dev/beast-mcmc)：BEAST是一个使用MCMC对分子序列进行贝叶斯分析的跨平台程序。
* [BEAST 2](https://github.com/CompEvol/beast2)：BEAST是一个使用分子序列MCMC进行贝叶斯推理的跨平台程序，由奥克兰大学领导开发。

#### 自然语言处理

* [CoreNLP](https://github.com/stanfordnlp/CoreNLP)：CoreNLP是一套Java核心NLP工具，用于标记化、句子分段、NER、解析、共指、情感分析等，由斯坦福开源。
* [Apache OpenNLP](https://github.com/apache/opennlp)：Apache OpenNLP库是一个基于机器学习的工具包，用于处理自然语言文本。
* [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)：CogComp包括词形还原器、ner、pos、prep-srl、量词、问题类型、关系提取、相似性、时间标准化器、分词器、音译、动词意义等，由宾夕法尼亚大学开源。
* [FNLP](https://github.com/FudanNLP/fnlp)：FNLP主要是为中文自然语言处理而开发的工具包，也包含为实现这些任务的机器学习算法和数据集，由复旦大学开源。
* [Lingua](https://github.com/pemistahl/lingua)：适用于Java和JVM的最准确的自然语言检测库，适用于长文本和短文本。
* [DKPro Core](https://github.com/dkpro/dkpro-core)：DKPro Core是基于Apache UIMA框架的自然语言处理软件组件的集合，由德国达姆施塔特工业大学开源。
* [Mallet](https://github.com/mimno/Mallet)：Mallet是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用，由马萨诸塞大学和宾夕法尼亚大学开发。
* [Similarity](https://github.com/shibing624/similarity)：Similarity是由一系列算法组成的Java版相似度计算工具包，目标是传播自然语言处理中相似度计算方法。
* [Jcseg](https://gitee.com/lionsoul/jcseg)：Jcseg是基于mmseg算法的一个轻量级中文分词器，同时集成了关键字提取，关键短语提取，关键句子提取和文章自动摘要等功能，并且提供了一个基于Jetty的Web服务器。
* [Neo4j NLP](https://github.com/graphaware/neo4j-nlp)：提供基于图的自然语言处理功能的Neo4j插件。
* [MiNLP](https://github.com/XiaoMi/MiNLP)：小米自然语言处理平台(MiNLP)具备词法、句法、语义分析等数十个功能模块，在小米内部广泛应用。
* [NLP-Lang](https://github.com/NLPchina/nlp-lang)：这个项目是一个基本包，封装了大多数NLP项目中常用工具。
* [SimpleNLG](https://github.com/simplenlg/simplenlg)：SimpleNLG是一个简单的Java API，旨在促进自然语言的生成，最初由阿伯丁大学开发。
* [MyNLP](https://github.com/mayabot/mynlp)：MyNLP是一个生产级、高性能、模块化、可扩展的中文NLP工具包，由上海万行公司开源。
* [Apache UIMA](https://github.com/apache/uima-uimaj)：UIMA是分析大量非结构化信息以发现与最终用户相关的知识的软件系统，由IBM开源。
* [Apache cTAKES](https://github.com/apache/ctakes)：Apache cTAKES是一个用于临床文本的自然语言处理平台。
* [Phrasal](https://github.com/stanfordnlp/phrasal)：Phrasal是用Java编写的大型统计机器翻译系统，由斯坦福开源。
* [Apache NLPCraft](https://github.com/apache/incubator-nlpcraft)：Apache NLPraft是一个开源库，用于为现代应用程序添加自然语言接口。
* [EasyAI](https://gitee.com/dromara/easyAi)：通过简单的API调用就可以实现常用的图像内物体的识别，定位等图像AI服务，及自然语言分类处理服务，由dormara社区开源。
* [HeidelTime](https://github.com/HeidelTime/heideltime)：海德堡大学数据库系统研究小组开发的多语言、跨域时间标记器。
* [Hawking](https://github.com/zoho/hawking)：自然语言日期时间解析器，可以从具有上下文的文本中提取日期和时间并解析为所需的格式。
* [LingPipe](https://www.alias-i.com/)：用于从POS标记到情感分析等任务的工具包。
* [NLP4J](https://github.com/emorynlp/nlp4j)：NLP4J项目(以前称为ClearNLP)为JVM语言提供了一个NLP工具包，该项目目前由埃默里大学NLP研究小组开发。
* [Joshua](http://joshua-decoder.org/)：Joshua是一个开源统计机器翻译解码器，用于基于短语、分层和基于语法的机器翻译，由约翰霍普金斯大学人类语言技术卓越中心开发。
* [Z-MERT](http://cs.jhu.edu/~ozaidan/zmert/)：用于机器翻译系统最小错误率训练的软件工具，由约翰霍普金斯大学开发。
* [AIKA](https://github.com/aika-algorithm/aika)：AIKA是一种新型人工神经网络，旨在更紧密地模仿生物大脑的行为，并弥补与经典人工智能的差距。
* [ClearTK](https://github.com/ClearTK/cleartk)：ClearTK提供了一个用Java开发统计自然语言处理组件的框架，并构建在Apache UIMA之上，它由科罗拉多大学博尔德分校计算语言和教育研究中心开发。
* [ARK Twitter NLP](https://github.com/brendano/ark-tweet-nlp)：CMU ARK Twitter词性标注器。
* [GATE](https://github.com/GateNLP/gate-core)：GATE是一个开源软件工具包，能够解决几乎所有文本处理问题，由谢菲尔德大学开发。
* [SemanticVectors](https://github.com/semanticvectors/semanticvectors)：SemanticVectors从自由自然语言文本创建语义WordSpace模型。
* [AmbiverseNLU](https://github.com/ambiverse-nlu/ambiverse-nlu)：AmbiverseNLU是马克斯普朗克信息学研究所的自然语言理解套件。
* [Processors](https://github.com/clulab/processors)：亚利桑那大学计算语言理解(CLU)实验室开源的自然语言处理器。
* [Cornell SPF](https://github.com/lil-lab/spf)：康奈尔大学语义分析框架。
* [JStarCraft NLP](https://github.com/HongZhaoHua/jstarcraft-nlp)：JStarCraft NLP是一个面向自然语言处理领域的轻量级引擎。
* [LAC](https://github.com/baidu/lac)：LAC是百度自然语言处理部研发的一款联合的词法分析工具，实现中文分词、词性标注、专名识别等功能。
* [Spark NLP](https://github.com/JohnSnowLabs/spark-nlp)：Spark NLP是一个构建在Apache Spark之上的最先进的自然语言处理库。
* [NLP API](https://gitee.com/stonedtx/free-nlp-api)：免费的自然语言处理、情感分析、实体识别、图像识别与分类、OCR识别、语音识别接口，由思通数科开源。
* [Twitter Text](https://github.com/twitter/twitter-text)：Twitter文本库，Twitter使用此代码对文本进行标记和解析，以满足平台上可用内容的期望。
* [MetaMapLite](https://github.com/lhncbc/metamaplite)：MetaMapLite的主要目标是提供近乎实时的命名实体识别器，它不像MetaMap那样严格，但速度更快，同时允许用户针对特定目的自定义和增强其行为，由利斯特山国家生物医学通讯中心开源。
* [VnCoreNLP](https://github.com/vncorenlp/VnCoreNLP)：VnCoreNLP是一个快速、准确的越南语NLP标注管道，通过分词、词性标注、命名实体识别(NER)和依存句法分析等关键NLP组件提供丰富的语言标注。
* [Zemberek-NLP](https://github.com/ahmetaa/zemberek-nlp)：Zemberek-NLP提供土耳其语自然语言处理工具。

#### 深度学习

* [Eclipse Deeplearning4J](https://github.com/deeplearning4j/deeplearning4j)：Eclipse Deeplearning4j是一套用于在JVM上运行深度学习的工具。
* [Deep Java Library](https://github.com/deepjavalibrary/djl)：DJL是一个开源、高级、与引擎无关的深度学习Java框架，由AWS开源。
* [KotlinDL](https://github.com/Kotlin/kotlindl)：KotlinDL是一个用Kotlin编写的高级深度学习API，受到Keras的启发。
* [Multi Model Server](https://github.com/awslabs/multi-model-server)：MMS是一种灵活且易于使用的工具，用于为使用任何ML/DL框架训练的深度学习模型提供服务，由AWS开源。
* [Neural Networks](https://github.com/ivan-vasilev/neuralnetworks)：这是一些用于训练深度神经网络的算法的Java实现。
* [TonY](https://github.com/tony-framework/TonY)：TonY是一个在Apache Hadoop上本地运行深度学习作业的框架。
* [Porcupine](https://github.com/Picovoice/porcupine)：Porcupine是一款高精度且轻量级的唤醒词引擎。
* [DL Inference](https://github.com/wuba/dl_inference)：通用深度学习推理工具，可在生产环境中快速上线由TensorFlow、PyTorch、Caffe框架训练出的深度学习模型，由58同城开源。
* [Deep Learning Flink](https://github.com/flink-extended/dl-on-flink)：Deep Learning Flink旨在集成Flink和深度学习框架(例如TensorFlow、PyTorch等)，以在Flink集群上实现分布式深度学习训练和推理。
* [OpenDL](https://github.com/guoding83128/OpenDL)：Spark上的深度学习训练框架。
* [Deep Netts](https://github.com/deepnetts/deepnetts-communityedition)：一个基于Java的深度学习开发平台，提供Deep Netts深度学习引擎的纯Java、开源社区版本。
* [TensorDash](https://github.com/CleanPegasus/TensorDash)：TensorDash是一款应用程序，可让你远程监控深度学习模型的指标，并在模型训练完成或崩溃时通知你。
* [Omega-AI](https://gitee.com/iangellove/omega-ai)：基于Java打造的深度学习框架，帮助你快速搭建神经网络，实现训练或测试模型，引擎支持自动求导，多线程与GPU运算。
* [ADAMS](https://adams.cms.waikato.ac.nz/)：专门针对Java的深度学习库，由怀卡托大学开发。
* [OpenLabeler](https://github.com/kinhong/OpenLabeler)：OpenLabeler是一个用于注释对象的开源应用程序，它可以生成PASCAL VOC格式的XML注释文件，用于人工智能和深度学习训练。
* [CaffeOnSpark](https://github.com/yahoo/CaffeOnSpark)：CaffeOnSpark将深度学习引入Hadoop和Spark集群，由Yahoo开源。
* [JDLL](https://github.com/bioimage-io/JDLL)：该项目提供了一个用于运行深度学习模型的Java库，支持Java软件和各种深度学习框架(引擎)之间的通信。

#### 遗传算法

* [Jenetics](https://github.com/jenetics/jenetics)：Jenetics是一个遗传算法、进化算法、语法进化、遗传编程和多目标优化库，用现代Java编写。
* [MOEAFramework](https://github.com/MOEAFramework/MOEAFramework)：MOEA框架是一个免费开源Java库，用于开发和试验多目标进化算法(MOEA)和其他通用多目标优化算法。
* [Watchmaker](https://github.com/dwdyer/watchmaker)：Watchmaker框架是一个可扩展、高性能、面向对象的框架，用于在Java中实现独立于平台的进化/遗传算法。
* [ECJ 23](https://github.com/GMUEClab/ecj)：ECJ是一个用Java编写的进化计算框架，提供了许多流行的EC算法和EC算法约定的工具，但特别强调遗传编程，由乔治梅森大学开源。
* [Evolving-Protozoa](https://github.com/DylanCope/Evolving-Protozoa)：该项目的目的是创造一个环境，让原生动物类实体能够进化其行为和形态，以便生存和繁殖。
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

#### 专家系统

* [Apache Jena](https://github.com/apache/jena)：Apache Jena是一个免费的开源Java框架，用于构建语义Web和链接数据应用程序，最初由惠普实验室开发。
* [PowerLoom](https://www.isi.edu/isd/LOOM/PowerLoom/)：PowerLoom是Loom知识表示系统的后继者，它提供了用于构建智能、基于知识的应用程序的语言和环境，由南加州大学开源。
* [D3web](https://github.com/denkbares)：D3web是一个开源推理引擎，用于开发、测试问题解决知识并将其应用于给定的问题情况，其中已经包含许多算法。
* [EYE](https://github.com/eyereasoner/eye)：EYE是一个支持语义Web层并实现Notation3的推理引擎。
* [Tweety](https://github.com/TweetyProjectTeam/TweetyProject)：Tweety是用于人工智能和知识表示的逻辑方面的Java框架的集合。

## 约束求解

* [OptaPlanner](https://github.com/apache/incubator-kie-optaplanner)：OptaPlanner是一个轻量级、可嵌入的约束满足引擎，可优化规划问题，最初由RedHat开发。
* [Choco Solver](https://github.com/chocoteam/choco-solver)：Choco-Solver是一个用于约束编程的开源Java库，由国立南特高等矿业学院开发。
* [JaCoP](https://github.com/radsz/jacop)：JaCoP求解器是基于Java的开源求解器，主要由瑞典隆德大学开发和维护。
* [Sat4j](https://gitlab.ow2.org/sat4j/sat4j)：Sat4j是一个用于解决布尔满足和优化问题的Java库，它可以解决SAT、MAXSAT、伪布尔、最小不可满足子集问题，由阿图瓦大学开源。
* [Timefold](https://github.com/TimefoldAI/timefold-solver)：Timefold是开源AI求解器，用于优化Java、Python或Kotlin中的操作和调度。
* [ACE](https://github.com/xcsp3team/ACE)：ACE是Christophe Lecoutre(CRIL)用Java开发的开源约束求解器，由阿图瓦大学开源。
* [OptaPy](https://github.com/optapy/optapy)：OptaPy是Python的人工智能约束求解器，可优化车辆路线问题、员工排班、维护计划、任务分配、学校时间表、云优化、会议安排、作业车间调度、装箱和更多规划问题。
* [JSolver](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=fff2046e43828a00c406835be84b571553b65087)：JSolver扩展了面向对象基于约束的声明式编程的Java编程范式，由香港城市大学开源。
* [JSprit](https://github.com/graphhopper/jsprit)：JSprit是一个基于Java的开源工具包，用于解决丰富的旅行商问题(TSP)和车辆路径问题(VRP)。
* [MiniCP](https://github.com/minicp/minicp)：MiniCP是一个用Java实现的轻量级CP求解器，由康涅狄格大学、鲁汶大学、佐治亚理工学院的三位教授共同开发。
* [JavaSMT](https://github.com/sosy-lab/java-smt)：JavaSMT是用于访问各种SMT求解器的通用API层，由德国慕尼黑大学开源。
* [CPSolver](https://github.com/UniTime/cpsolver)：CPSolver库包含一个基于本地搜索的框架，允许使用约束编程原语(变量、值、约束)对问题进行建模。
* [Kiwi-Solver](https://github.com/google/kiwi-solver)：Kiwi是一款专为教育设计的简约且可扩展的约束规划求解器，由Google开源。
* [SMTInterpol](https://github.com/ultimate-pa/smtinterpol)：SMTInterpol是弗莱堡大学开发的插值SMT求解器。
* [Statix Solver](https://mvnrepository.com/artifact/org.metaborg/statix.solver)：由代尔夫特理工大学开源的约束求解器。
* [JSCIPOpt](https://github.com/scipopt/JSCIPOpt)：SCIP是目前混合整数规划(MIP)和混合整数非线性规划(MINLP)最快的非商业求解器之一，由柏林自由大学开源。
* [CLP Java](https://github.com/quantego/clp-java)：CLP线性求解器的Java接口，针对快速模型构建和快速解析进行了优化。

## 实体解析

* [Zingg](https://github.com/zinggAI/zingg)：Zingg是一种基于ML的实体解析工具。
* [JedAI](https://github.com/scify/JedAIToolkit)：JedAI是一个开源、高可扩展性的Java实体解析工具包，由鲁汶大学、巴黎西岱大学、摩德纳雷焦艾米利亚大学开源。
* [Zentity](https://github.com/zentity-io/zentity)：Zentity是一个用于实时实体解析的Elasticsearch插件。
* [ReCiter](https://github.com/wcmc-its/ReCiter)：ReCiter是一个高度准确的系统，用于猜测某个人在PubMed上发表了哪些出版物，由康奈尔大学开源。

## 数据科学

* [CUDF](https://github.com/rapidsai/cudf/tree/branch-24.08/java)：该项目为CUDF提供了Java绑定，以便能够在GPU上处理大量数据，由NVIDIA提供。
* [Tablesaw](https://github.com/jtablesaw/tablesaw)：Tablesaw是一个数据框架和可视化库，支持加载、清理、转换、过滤和汇总数据。
* [OpenRefine](https://github.com/OpenRefine/OpenRefine)：OpenRefine是一个基于Java的强大工具，可让你加载数据、理解数据、清理数据、协调数据，并使用来自Web的数据对其进行扩充，由Google开源。
* [Enso](https://github.com/enso-org/enso)：Enso是一种屡获殊荣的交互式编程语言，具有双重视觉和文本表示形式。
* [XChart](https://github.com/knowm/XChart)：XChart是一个轻量且方便的数据绘制库，旨在在尽可能短的时间内从数据到图表，并消除自定义图表样式时的猜测工作。
* [Incanter](https://github.com/incanter/incanter)：Incanter是一个基于Clojure、类似R的JVM统计计算和图形环境。
* [RumbleDB](https://github.com/RumbleDB/rumble)：RumbleDB是一个查询引擎，可让你轻松高效地查询大型、混乱的数据集，由苏黎世联邦理工学院开源。
* [Hopsworks](https://github.com/logicalclocks/hopsworks)：Hopsworks是一个ML数据平台，具有以Python为中心的特征存储和MLOps功能，由Hopsworks开源。
* [Eclipse ICE](https://github.com/eclipse/ice)：Eclipse ICE是一个科学工作台和工作流程环境，旨在改善计算科学家的用户体验。
* [Morpheus](https://github.com/zavtech/morpheus-core)：Morpheus库旨在促进涉及大型数据集的高性能分析软件的开发，以便在JVM上进行离线和实时分析。
* [Apache Commons Statistics](https://github.com/apache/commons-statistics)：Apache Commons Statistics提供用于统计应用程序的工具，为常用的连续和离散分布提供支持。
* [JScience](https://github.com/javolution/jscience)：提供一组用于处理科学测量和单位的类。
* [JFreeChart](https://github.com/jfree/jfreechart)：JFreeChart是一个适用于Java平台的综合免费图表库，可在客户端(JavaFX和Swing)或服务器端使用。
* [DataMelt](https://datamelt.org/)：DataMelt是一款用于数值计算、统计、符号计算、数据分析和数据可视化的软件。
* [Dataframe](https://github.com/Kotlin/dataframe)：Dataframe旨在利用Kotlin语言的全部功能以及Jupyter Notebook和REPL中间歇性代码执行提供的机会，协调Kotlin的静态类型与数据的动态特性，JetBrains开源。
* [Krangl](https://github.com/holgerbrandl/krangl)：Krangl是一个用于数据处理的Kotlin库，通过使用现代函数式API实现数据操作语法，它允许过滤、转换、聚合和重塑表格数据。
* [ELKI](https://github.com/elki-project/elki)：ELKI是一款用Java编写的开源数据挖掘软件，由德国多特蒙德大学开发。
* [DataCleaner](https://github.com/datacleaner/DataCleaner)：DataCleaner是一个数据质量工具包，可让你分析、更正和丰富你的数据。
* [Featran](https://github.com/spotify/featran)：Featran是用于数据科学和机器学习的Scala特征转换库，由Spotify开源。
* [Datavines](https://github.com/datavane/datavines)：DataVines是一个易于使用的数据质量服务平台，支持多种指标。
* [TMD](https://github.com/techascent/tech.ml.dataset)：tech.ml.dataset(TMD)是一个用于表格数据处理的Clojure库，类似于Python的Pandas或R的data.table。
* [Joinery](https://github.com/cardillo/joinery)：Java的DataFrame。
* [JDFrame](https://github.com/burukeYou/JDFrame)：JDFrame是一个Java DataFrame的实现。
* [DFLib](https://github.com/dflib/dflib)：DFLib是通用DataFrame数据结构的轻量级纯Java实现。
* [Classifai](https://github.com/CertifaiAI/classifai)：Classifai是最全面的开源数据标注平台之一。

## 异常检测

* [ThirdEye](https://github.com/startreedata/thirdeye)：ThirdEye是一款用于实时监控时间序列和交互式根本原因分析的集成工具，最初由LinkedIn开源。
* [Adaptive Alerting](https://github.com/ExpediaGroup/adaptive-alerting)：Adaptive Alerting通过自动模型选择和拟合进行流异常检测，由Expedia开源。
* [Random Cut Forest](https://github.com/aws/random-cut-forest-by-aws)：该仓库包含随机森林(RCF)概率数据结构的实现，由Amazon开发，用于流数据的非参数异常检测算法。
* [AnomalyDetection](https://github.com/JeemyJohn/AnomalyDetection)：Java实现的异常检测算法。

## 商业智能

* [Poli](https://github.com/shzlw/poli)：Poli是一款易于使用的SQL报告应用程序，专为SQL爱好者打造。
* [SuperSonic](https://github.com/tencentmusic/supersonic)：SuperSonic是下一代LLM支持的数据分析平台，集成了ChatBI和HeadlessBI，由腾讯音乐娱乐开源。
* [CBoard](https://gitee.com/tuiqiao/CBoard)：由上海楚果信息技术有限公司主导开源，它不仅仅是一款自助BI数据分析产品，还是开放的BI产品开发平台。
* [Abixen Platform](https://github.com/abixen/abixen-platform)：Abixen是一个基于微服务的软件平台，用于构建企业应用程序，通过创建特定的微服务并通过提供的CMS集成来提供功能。
* [Helical Insight](https://github.com/helicalinsight/helicalinsight)：Helical Insight是世界上第一个开源商业智能框架，可以帮助你从一个或多个数据源中获取见解。
* [Wren Engine](https://github.com/Canner/wren-engine)：Wren Engine被设计为独立的语义引擎，你可以轻松地使用任何AI代理实现它，可以将其`用作语义层的通用语义引擎。
* [Guitar](https://github.com/iflytek/Guitar)：Guitar是一款简单、高效的分布式多维BI报表分析引擎，由科大讯飞开源。
* [KNOWAGE](https://github.com/KnowageLabs/Knowage-Server)：KNOWAGE是开源分析和商业智能套件，可让你将传统数据和大/云数据源组合成有价值且有意义的信息，由OW2开源。
* [JRelax-BI](https://gitee.com/zengchao/JRelax-BI)：BI商业智能，自定义表单+自定义流程+自定义报表。
* [ART](https://art.sourceforge.net/)：ART是一种报告和商业智能解决方案，它可以快速部署SQL查询结果，支持表格报告、图表、仪表板、调度。
* [富表低代码可视化大屏工具](https://gitee.com/hitsoft1995/fusion-view)：富表智能数据可视化平台是一款面向企业和行业级别的用户，具有AI特色的可视化与BI商业智能敏捷分析的平台。

## 指纹识别

* [Soter](https://github.com/Tencent/soter)：腾讯主导的Android下安全、快速的生物识别认证标准及平台。
* [SourceAFIS](https://github.com/robertvazan/sourceafis-java)：SourceAFIS Java是SourceAFIS(一种用于识别人类指纹的算法)的纯Java端口，它可以1:1比较两个指纹或1:N在大型数据库中搜索匹配的指纹。
* [FingerprintIdentify](https://github.com/uccmawei/FingerprintIdentify)：Android指纹验证SDK。
* [Android-Goldfinger](https://github.com/infinum/Android-Goldfinger)：用于简化生物识别身份验证实施的Android库。

## 推荐系统

* [Twitter Recommendation Algorithm](https://github.com/twitter/the-algorithm)：Twitter的推荐算法是一组服务和作业，负责在所有Twitter产品界面(例如For You时间线、搜索、探索、通知)上提供推文和其他内容的提要。
* [RankSys](https://github.com/RankSys/RankSys)：RankSys是一个用于实施和评估推荐算法和技术的新框架。
* [LibRec](https://github.com/guoguibing/librec)：LibRec是一个用于推荐系统的Java库，它实现了一套最先进的推荐算法，旨在解决两个经典的推荐任务：评级预测和项目排名。
* [LensKit](https://github.com/lenskit/lenskit)：LensKit是协同过滤算法的实现，也是一组用于对算法进行基准测试的工具，由明尼苏达大学开源。

## 逻辑编程

* [LogicNG](https://github.com/logic-ng/LogicNG)：LogicNG是一个用于创建、操作和求解布尔和伪布尔公式的Java库，它包括MiniSAT、Glucose、PBLib或OpenWBO等流行工具的纯Java实现。
* [NeuraLogic](https://github.com/GustikS/NeuraLogic)：该框架的核心是一种自定义语言，你可以使用它来编写可微分程序来编码你的学习场景，类似于经典的深度学习框架。
* [Formulog](https://github.com/HarvardPL/formulog)：Formulog通过构建和推理SMT公式的机制以及一些一阶函数编程来扩展逻辑编程语言Datalog，由哈佛编程语言研究小组开源。
* [Alpha](https://github.com/alpha-asp/Alpha)：Alpha是一个答案集编程(ASP)系统：它读取逻辑程序(一组逻辑规则)并计算相应的答案集，由维也纳工业大学开源。

## 多智能体

* [Jason](https://github.com/jason-lang/jason)：Jason是AgentSpeak扩展版本的成熟解释器，AgentSpeak是一种面向BDI代理的逻辑编程语言，由圣卡塔琳娜联邦大学开源。
* [JaCaMo](https://github.com/jacamo-lang/jacamo)：JaCaMo项目旨在通过提供一个集成工具和语言的开发平台来推广面向多智能体编程(MAOP)方法。
* [Yggdrasil](https://github.com/Interactions-HSG/yggdrasil)：使用Vert.x构建的超媒体多代理系统(MAS)平台，由圣加仑大学交互研究团队开源。

## MATLAB

* [Dimple](https://github.com/analog-garage/dimple)：Dimple是一款用于概率建模、推理和学习的开源软件工具。
* [MFL](https://github.com/HebiRobotics/MFL)：MFL是一个Java库，用于读取和写入与MATLAB的MAT文件格式兼容的MAT文件，由CMU机器人研究所开源。
* [MatFileRW](https://github.com/diffplug/matfilerw)：MatFileRW是一个允许读取和写入MAT文件的库。
* [MatConsoleCtl](https://github.com/diffplug/matconsolectl)：MatConsoleCtl是一个Java API，允许从Java调用MATLAB。

## Jupyter

* [Rapaio-Jupyter-Kernel](https://github.com/padreati/rapaio-jupyter-kernel)：基于JShell的Java语言Jupyter内核。
* [Kotlin-Jupyter](https://github.com/Kotlin/kotlin-jupyter)：该内核是一个强大的引擎，旨在增强你的Kotlin REPL体验；它提供对执行代码单元、提供基本代码完成和分析错误的支持。
* [Ganymede](https://github.com/allen-ball/ganymede)：Ganymede是基于Java Shell工具JShell的Jupyter Notebook Java内核。
* [Almond](https://github.com/almond-sh/almond)：Jupyter的Scala内核。
* [Apache Toree](https://github.com/apache/incubator-toree)：Apache Toree是Juypter Notebook内核，主要目标是为使用Scala语言连接和使用Apache Spark的交互式应用程序提供基础。
* [IJava](https://github.com/SpencerPark/IJava)：用于执行Java代码的Jupyter内核。
* [SciJava Kernel](https://github.com/scijava/scijava-jupyter-kernel)：基于BeakerX的已失效内核。
* [BeakerX](https://github.com/twosigma/beakerx)：BeakerX是JVM内核和交互式小部件的集合，用于绘图、表格、自动翻译以及Jupyter Notebook和Jupyter Lab版本1.2.x和2.x的其他扩展。
* [JVM Repr](https://github.com/jupyter/jvm-repr)：用于将JVM对象转换为MIME类型表示的API，适用于Jupyter生态系统。
* [JVM Magics](https://github.com/jupyter/jvm-magics)：用于跨JVM内核实现魔法函数的插件系统。
* [JNotebook](https://github.com/cyrilou242/jnotebook)：JNotebook是一个现代的Java Notebook系统，JNotebook解释Java JShell文件并将它们呈现为笔记本。
* [Apache Zeppelin](https://github.com/apache/zeppelin)：基于Web的笔记本，支持使用SQL、Scala等进行数据驱动、交互式数据分析和协作文档。

## 元启发式框架

* [Mork](https://github.com/mork-optimization/mork)：Mork是一个使用JVM开发NP-Hard问题方法的框架，由胡安卡洛斯国王大学开源。
* [jMetal](https://github.com/jMetal/jMetal)：jMetal是一个基于Java的框架，用于使用元启发式进行多目标优化，由马拉加大学开源。
* [SEAGE](https://github.com/seage/seage)：SEAGE是一个用于元启发式算法协作的超启发式框架，由捷克理工大学开源。

## 机器人开发

* [WPILib](https://github.com/wpilibsuite/allwpilib)：该仓库包含HAL、WPILibJ和WPILibC项目，这些是为roboRIO创建机器人程序的核心库，由伍斯特理工学院开源。
* [GRIP](https://github.com/WPIRoboticsProjects/GRIP)：GRIP是一款用于快速原型设计和部署计算机视觉算法的应用程序，主要用于机器人应用，由伍斯特理工学院开源。
* [FlashLib](https://github.com/Flash3388/FlashLib)：FlashLib是一个Java机器人软件开发库，最初旨在改进和帮助FRC团队，但现在旨在支持非FRC机器人甚至其他用途。
* [OpenTCS](https://github.com/openTCS/opentcs)：OpenTCS是一个用于控制自动引导车辆(AGV)和移动机器人车队的免费平台，由弗劳恩霍夫物流研究所维护。
* [PathPlanner](https://github.com/mjansen4857/pathplanner)：PathPlanner是3015团队创建的FRC机器人运动轨迹生成器。
* [IHMC Open Robotics Software](https://github.com/ihmcrobotics/ihmc-open-robotics-software)：机器人软件具有腿式运动算法和基于动量的优化控制器核心；世界级机器人的支持软件，包括人形、跑鸟、外骨骼、机甲等，由IHMC机器人实验室开源。
* [MyRobotLab](https://github.com/MyRobotLab/myrobotlab)：用于机器人和创意机器控制的开源Java框架。
* [Bag Database](https://github.com/swri-robotics/bag-database)：Bag Database是一个基于Web的应用程序，可监视ROS bag文件的目录、解析其元数据，并提供友好的Web界面来搜索包、下载包以及在其上运行后处理脚本，由美国西南研究所开源。
* [ROS 2 Java](https://github.com/ros2-java/ros2_java)：这是一组使开发人员能够为JVM和Android编写ROS 2应用程序的项目。
* [YAGSL](https://github.com/BroncBotz3481/YAGSL)：YAGSL是一个由现任和前任BroncBotz导师为所有FRC团队开发的转向库。
* [JBullet](http://jbullet.advel.cz/)：JBullet是Bullet物理库的Java端口。
* [Robot Overlord](https://github.com/MarginallyClever/Robot-Overlord-App)：Robot Overlord是一款机器人3D控制软件，由Marginally Clever Robots开源。
* [BowlerStudio](https://github.com/CommonWealthRobotics/BowlerStudio)：BowlerStudio是一款机器人开发应用程序，它将脚本和设备管理与强大的控制和处理功能结合在一起。
* [EV3Dev-lang-Java](https://github.com/ev3dev-lang-java/ev3dev-lang-java)：EV3Dev-lang-Java是一个学习Java并使用EV3Dev和LeJOS方式支持的硬件为Mindstorms机器人创建软件的项目。
* [Firmata4j](https://github.com/kurbatov/firmata4j)：Firmata4j是用Java编写的Firmata客户端库，该库允许从你的Java程序控制运行Firmata协议的Arduino。
* [StuyLib](https://github.com/StuyPulse/StuyLib)：StuyLib是一个FRC库/工具包，其中包括许多不同的编程实用程序；它包括游戏手柄库、Limelight库、数字滤波器/流库以及许多其他与数学和编程相关的实用程序，由史岱文森高中的FIRST机器人团队开发。
* [GradleRIO](https://github.com/wpilibsuite/GradleRIO)：GradleRIO是一个功能强大的Gradle插件，允许参加FIRST机器人竞赛的团队生成和构建他们的代码，由伍斯特理工学院开源。
* [PhotonVision](https://github.com/PhotonVision/photonvision)：PhotonVision是FIRST机器人竞赛的免费、快速且易于使用的计算机视觉解决方案。
* [EasyOpenCV](https://github.com/OpenFTC/EasyOpenCV)：在FTC机器人上使用OpenCV的简单方法。
* [AdvantageKit](https://github.com/Mechanical-Advantage/AdvantageKit)：AdvantageKit是由Team 6328开发的日志记录、遥测和重放框架。
* [Robo4J](https://github.com/Robo4J/robo4j)：Robo4J提供了一种简单的方法来开始构建自定义硬件并为其创建在JVM上运行的软件。
* [Makelangelo](https://github.com/MarginallyClever/Makelangelo-software)：Makelangelo软件是一个Java程序，可为CNC绘图仪准备艺术品，最初是为Makelangelo艺术机器人设计的。
* [FTCLib](https://github.com/FTCLib/FTCLib)：FTCLib是一个旨在成为FTC编程所需的唯一库的库。
* [MuJoCo-Java](https://github.com/CommonWealthRobotics/mujoco-java)：MuJoCo物理系统的Java JNI绑定。
* [Road Runner](https://github.com/acmerobotics/road-runner)：一个简单的Kotlin库，用于规划专为FTC设计的2D移动机器人路径和轨迹。
* [FtcRobotController](https://github.com/FIRST-Tech-Challenge/FtcRobotController)：该仓库包含用于构建Android应用程序以控制FIRST Tech Challenge竞赛机器人的源代码。
* [IIWA STACK](https://github.com/IFL-CAMP/iiwa_stack)：适用于KUKA LBR IIWA R800/R820(7/14公斤)的ROS Indigo/Kinetic元包。
* [MASON](https://github.com/eclab/mason)：MASON是一个基于Java的快速代理模拟库核心，旨在成为大型定制Java模拟的基础，并为许多轻量级模拟需求提供足够的功能，由乔治梅森大学开源。
* [VirtualRoBot](https://github.com/Beta8397/virtual_robot)：VirtualRoBot是一款2D机器人模拟器，帮助初学者学习FTC Robotics的Java编程，由FTC Team 8397 Beta开源。

## 数学库

* [SuanShu](https://github.com/aaiyer/SuanShu)：SuanShu是一个Java数学库，用于数值分析、统计、求根、线性代数、优化等。
* [Colt](https://dst.lbl.gov/ACSSoftware/colt/)：Java中用于高性能科学计算的库，它包含用于数据分析、线性代数、多维数组、傅里叶变换、统计和直方图的有效算法，由欧洲核子研究中心开发。
* [Apache Commons Math](https://github.com/apache/commons-math)：Apache Commons Math是一个开源的数学库，提供了一系列基础数学算法和高级数学功能。
* [Apache Commons Numbers](https://github.com/apache/commons-numbers)：Apache Commons Numbers提供数字类型和实用程序的实现。
* [Eclipse January](https://github.com/eclipse/january)：Eclipse January是一组用于在Java中处理数值数据的库，它部分受到NumPy的启发，旨在提供类似的功能。
* [ELEFUNT](http://www.math.utah.edu/~beebe/software/java/)：ELEFUNT附带了一个扩展了java.lang.Math的新类库，以及用于数字输出格式化的新类库，由犹他大学开源。
* [JNT](https://math.nist.gov/jnt/)：JNT包含计算内核的坚实基础，可以帮助引导开发Java中复杂数值应用程序的工作，由美国国家标准与技术研究院开源。
* [JUMP](https://sourceforge.net/projects/jump-math/)：JUMP是一个基于Java的可扩展高精度数学包，包括对基于分数的计算的支持，支持转换为浮点数和BigDecimal。
* [JSci](https://jsci.sourceforge.net/)：JSci是一组免费的Java包，目的是以最自然的方式概括科学方法/原理，由杜伦大学开源。
* [Jampack](https://math.nist.gov/pub/Jampack/Jampack/AboutJampack.html)：Jampack是一个协作类的集合，旨在在Java应用程序中执行矩阵计算，由马里兰大学和美国国家标准与技术研究院开发。
* [JAMA](https://math.nist.gov/javanumerics/jama/)：JAMA是Java的基本线性代数包，它提供了用于构造和操作真实的稠密矩阵的用户级类，由马里兰大学和美国国家标准与技术研究院开发。
* [Symja](https://github.com/axkr/symja_android_library)：Symja是计算机代数语言和符号数学库，用纯Java实现的流行算法的集合。
* [Ojalgo](https://github.com/optimatika/ojAlgo)：ojAlgo是用于数学、线性代数和优化的开源Java代码。
* [KotlinGrad](https://github.com/breandan/kotlingrad)：JVM的类型安全符号微分，由蒙特利尔大学开源。
* [Apfloat](https://github.com/mtommila/apfloat)：Apfloat是一个高性能任意精度算术库，你可以用它进行数百万位精度的计算。
* [Cojac](https://github.com/Cojac/Cojac)：Cojac旨在提高Java数字的算术能力，由弗里堡大学开源。
* [BigDecimalMath](https://github.com/eobermuhlner/big-math)：使用任意精度的高级Java BigDecimal数学函数库。
* [UnCommons-Maths](https://github.com/dwdyer/uncommons-maths)：Java的随机数生成器、概率分布、组合学和统计库。
* [NM Dev](https://nm.dev/)：NM Dev是一个数值库，涵盖了广泛的算法，例如线性代数、微积分、微分方程、无约束和约束优化、统计学和极值理论。
* [EJML](https://github.com/lessthanoptimal/ejml)：EJML是一个用Java编写的快速且易于使用的线性代数库，适用于稠密、稀疏、实数和复杂矩阵。
* [La4j](https://github.com/vkostyukov/la4j)：La4j是一个开源的100% Java库，提供线性代数基元(矩阵和向量)和算法。
* [Neanderthal](https://github.com/uncomplicate/neanderthal)：Neanderthal是一个用于快速矩阵和线性代数计算的Clojure库，基于针对CPU和GPU的高度优化的BLAS和LAPACK计算例程的原生库。
* [Hacktoberfest-Mathematics](https://github.com/BaReinhard/Hacktoberfest-Mathematics)：数学公式和函数的脚本和/或程序库。
* [Decimal4j](https://github.com/tools4j/decimal4j)：用于基于长整型的快速定点算术的Java库，支持最多18位小数。
* [DSI Utils](https://github.com/vigna/dsiutils)：DSI Utils是过去20年在米兰大学信息科学系开发的项目中积累的类的混杂。
* [KMath](https://github.com/SciProgCentre/kmath)：Kotlin数学扩展库。
* [ParallelColt](https://github.com/rwl/ParallelColt)：Parallel Colt是Colt的多线程版本，由欧洲核子研究组织开源。
* [LIBLINEAR](https://github.com/bwaldvogel/liblinear-java)：LIBLINEAR的Java版本，LIBLINEAR是一个用于解决大规模正则化线性问题分类、回归和异常值检测的简单包。
* [JTransforms](https://github.com/wendykierp/JTransforms)：JTransforms是第一个用纯Java编写的开源多线程FFT库。
* [Jblas](https://github.com/jblas-project/jblas)：Jblas是一个Java矩阵库，它使用现有的高性能BLAS和LAPACK库(如ATLAS)，由柏林工业大学开源。
* [SymJava](https://github.com/yuemingl/SymJava)：SymJava是一个用于符号数值计算的Java库。
* [JAutoDiff](https://github.com/uniker9/JAutoDiff)：JAutoDiff是一个用100%纯Java编写的自动微分库。
* [Hipparchus](https://github.com/Hipparchus-Math/hipparchus)：Hiparchus项目是一个轻量级、独立的数学和统计组件库，可解决Java编程语言中无法解决的最常见问题。
* [Universal Java Matrix Package](https://github.com/ujmp/universal-java-matrix-package)：UJMP是一个开源库，用于Java中的密集和稀疏矩阵计算以及线性代数。
* [SSJ](https://github.com/umontreal-simul/ssj)：SSJ是一个用于随机模拟的Java库，由蒙特利尔大学开发。
* [OwlPack](https://www.cs.rice.edu/%7Ezoran/OwlPack/)：OwlPack是一个多态、面向对象风格的Java通用线性代数库，基于标准Fortran LINPACK库，由莱斯大学开源。
* [Java Algebra System](https://github.com/kredel/java-algebra-system)：Java代数库，由曼海姆大学开源。
* [Matrix-Toolkits-Java](https://github.com/fommil/matrix-toolkits-java)：MTJ是一个用于开发线性代数应用程序的高性能库。
* [NetLib-Java](https://github.com/fommil/netlib-java)：NetLib-Java是低级BLAS、LAPACK和ARPACK的包装器，其执行速度与带有纯JVM回退的C/Fortran接口一样快。
* [BigInt](https://github.com/tbuktu/bigint)：这是java.math.BigInteger的改进版本，它使用快速算法来乘除大数。
* [Vectorz](https://github.com/mikera/vectorz)：用于Java的快速双精度向量和矩阵数学库，基于N维数组的概念。
* [BigDecimal Utils](https://github.com/mortezaadi/bigdecimal-utils)：用于比较BigDecimal的工具库。
* [FastDoubleParser](https://github.com/wrandelshofer/FastDoubleParser)：该项目提供了double、float、BigDecimal和BigInteger值的解析器，double和float解析器针对最常见输入的速度进行了优化。
* [Tensorics](https://github.com/tensorics/tensorics-core)：Tensorics是一个用于多维数据处理的Java框架。
* [GLPK](https://winglpk.sourceforge.net/)：GLPK软件包提供了用于大规模线性规划(LP)和混合整数规划(MIP)的求解器。
* [Jape](https://github.com/RBornat/jape)：Jape是一个可配置的证明计算器，支持推理系统中形式证明的交互式发现。
* [Math](https://github.com/SpongePowered/math)：用于Java的不可变数学库，提供数学类型、快速三角函数、向量、矩阵、复数、四元数和操作链之间的轻松转换，重点关注游戏和计算机图形。
* [F2J](https://sourceforge.net/projects/f2j)：F2J项目的目标是为最初用Fortran编写的数值库(特别是BLAS和LAPACK)提供Java API，由田纳西大学开源。
* [Netlib](https://github.com/luhenry/netlib)：该项目提供了BLAS、LAPACK和ARPACK子例程的多个Java实现，支持Java 8+，它通过OpenBLAS和Intel MKL等本机实现提供BLAS、LAPACK和ARPACK的硬件加速。
* [DDoggeg](https://github.com/lessthanoptimal/ddogleg)：DDoggeg是一个高性能Java库，用于非线性优化、稳健模型拟合、多项式求根、排序等。
* [Catalano](https://github.com/DiegoCatalano/Catalano-Framework)：Catalano框架是一个用于Java和Android的科学计算框架。
* [Shared Scientific Toolbox](https://carsomyr.github.io/shared/)：SST是基础科学库的集合，其主要目的是充当所涉及的科学计算的高度特定需求与Java编程语言的更传统方面之间的桥梁。
* [Jspline+](https://www.mathematik.hu-berlin.de/~lamour/software/JAVA/J_Spline/overview-summary.html)：Jspline+是新西伯利亚计算数学和数学地球物理研究所开发的Java样条逼近库，它包含离散网格上的单变量和多元样条近似的类，以及核心矩阵和线性系统解类。
* [JLargeArrays](https://gitlab.com/visnow.org/JLargeArrays)：JLargeArrays是一个纯Java的一维数组库，最多可以存储2的63次方个元素，由华沙大学开源。
* [DynaHist](https://github.com/dynatrace-oss/dynahist)：Java动态直方图库。
* [Curves API](https://github.com/virtuald/curvesapi)：实现在一组控制点上定义自身的各种数学曲线。
* [NdArray Java](https://github.com/tensorflow/java-ndarray)：NdArray公开了用于在Java中操作N维空间中的数据的实用程序，由Tensorflow开源。
* [Histogram](https://github.com/bigmlcom/histogram)：该项目是Ben-Haim的流式并行决策树中描述的流式一次性直方图的实现。

## 本体库

* [WebProtégé](https://github.com/protegeproject/webprotege)：WebProtégé是一个免费、开源的协作本体开发环境，由斯坦福开发。
* [OWLAPI](https://github.com/owlcs/owlapi)：OWL API是用于创建、操作和序列化OWL本体的Java API，由曼彻斯特大学开源。
* [Apache Jena](https://github.com/apache/jena)：Apache Jena是一个免费的开源Java框架，用于构建语义Web和链接数据应用程序，最初由惠普实验室开发。
* [Karma](https://github.com/usc-isi-i2/Web-Karma)：Karma是一种信息集成工具，使用户能够快速轻松地集成来自各种数据源的数据，包括数据库、电子表格、分隔文本文件、XML、JSON、KML和Web API，由南加州大学信息科学研究所开源。
* [Widoco](https://github.com/dgarijo/Widoco)：WIDOCO是一个带有本体文档的HTML模板逐步生成器，它使用LODE环境来创建部分模板，由芬欧汇川大学本体工程组开发。
* [Ontop](https://github.com/ontop/ontop)：Ontop是一个虚拟知识图谱系统，它将任意关系数据库的内容公开为知识图，由博尔扎诺自由大学开源。
* [Scowl](https://github.com/phenoscape/scowl)：Scowl提供了Scala DSL，允许使用OWL API以声明式方法编写OWL表达式和公理。
* [DL-Learner](https://github.com/SmartDataAnalytics/DL-Learner)：DL-Learner是一个用于执行丰富语义背景知识的机器学习框架，由德累斯顿工业大学开源。
* [ROBOT](https://github.com/ontodev/robot)：ROBOT是一个用于自动化本体开发任务的命令行工具和库，重点是开放生物和生物医学本体。
* [SciGraph](https://github.com/SciGraph/SciGraph)：SciGraph旨在将本体和使用本体描述的数据表示为Neo4j图。
* [OWL2VOWL](https://github.com/VisualDataWeb/OWL2VOWL)：转换WebVOWL的本体。
* [LogMap](https://github.com/ernestojimenezruiz/logmap-matcher)：LogMap是一个高度可扩展的本体匹配系统，具有“内置”推理和不一致修复功能，由伦敦大学城市学院开源。
* [Openllet](https://github.com/Galigator/openllet)：Openllet提供了检查本体一致性、计算分类层次结构、解释推论以及回答SPARQL查询的功能，由巴黎第十一大学开源。
* [ELK](https://github.com/liveontologies/elk-reasoner)：ELK是一个本体推理器，旨在支持OWL 2 EL配置文件，由乌尔姆大学人工智能研究所和牛津大学计算机科学系知识表示和推理小组开发。
* [AMIE](https://github.com/dig-team/amie)：AMIE是一个在知识库上挖掘Horn规则的系统，由巴黎电信学院开源。
* [OWLTools](https://github.com/owlcollab/owltools)：OWLTools是OWL API之上的便捷Java API。
* [Slib](https://github.com/sharispe/slib)：Slib是一个致力于基于文本和/或本体处理的语义数据挖掘的Java库。
* [OBOGraphs](https://github.com/geneontology/obographs)：该仓库包含用于本体交换的JSON/YAML格式规范，以及参考Java对象模型和OWL转换器。
* [Ontmalizer](https://github.com/srdc/ontmalizer)：Ontmalizer自动执行XML模式(XSD)和XML数据到RDF/OWL的全面转换。
* [O'FAIRe](https://github.com/agroportal/fairness)：O'FAIRe是一种开源公平性评估方法和工具，适用于D2KAB和FooSIN项目中开发的本体、词汇和语义资源，由蒙彼利埃大学开源。
* [LODE](https://github.com/essepuntato/LODE)：实时OWL文档环境，用于将OWL本体转换为HTML人类可读页面，由博洛尼亚大学开源。
* [OWL-CLI](https://github.com/atextor/owl-cli)：用于本体工程的命令行工具(图表生成、读/写各种格式的文档和OWL DL推理)。
* [CEL](https://github.com/julianmendez/cel)：CEL是一种用于大规模生物医学本体的轻量级描述逻辑推理器。
* [JCEL](https://github.com/julianmendez/jcel)：JCEL是描述逻辑EL+的推理器，它使用OWL API，可以用作Protege的插件。
* [Racer](https://github.com/ha-mo-we/Racer)：Racer是一个知识表示系统，它为描述逻辑SRIQ(D)实现了高度优化的表格演算。
* [Pellet](https://github.com/stardog-union/pellet)：Pellet是Java中的OWL 2推理机，提供开源和商业许可、商业支持，由Complexible开发。
* [OPPL 2](https://sourceforge.net/projects/oppl2/)：OPPL 2是OPPL(本体预处理语言)的第二个版本，它是一种旨在修改OWL本体的语言。
* [RDF Toolkit](https://github.com/edmcouncil/rdf-toolkit)：RDF Toolkit是一个用于读写多种格式的RDF文件的工具。
* [IDMP](https://github.com/edmcouncil/idmp)：该项目包含基于药品识别ISO标准构建的OWL本体。
* [OntoBrowser](https://github.com/Novartis/ontobrowser)：OntoBrowser是一个基于Web的应用程序，用于管理本体。
* [OntoGraph](https://github.com/NinePts/OntoGraph)：OWL本体绘图程序。
* [Ontology Modeling Language](https://github.com/opencaesar/oml)：该仓库用于OML抽象语法、文本语法、图形语法、API和规范。
* [ONT-API](https://github.com/owlcs/ont-api)：ONT-API是一个以RDF为中心的Java库，可与OWL2配合使用，由曼彻斯特大学开源。
* [Phenol](https://github.com/monarch-initiative/phenol)：表型组学和基因组学本体库。
* [STATO](https://github.com/ISA-tools/stato)：STATO是一个通用的统计本体，由牛津大学开源。
* [Sigma](https://github.com/ontologyportal/sigmakee)：Sigma是逻辑理论的集成开发环境，扩展了建议的上层合并本体(SUMO)。
* [IFCtoLBD](https://github.com/jyrkioraskari/IFCtoLBD)：IFCtoLBD将IFC STEP格式的文件转换为链接建筑数据本体。
* [MELT](https://github.com/dwslab/melt)：MELT是一个强大的Maven框架，用于开发、调整、评估和打包本体匹配系统，由德国曼海姆大学开源。
* [JOPA](https://github.com/kbss-cvut/jopa)：JOPA是一个Java OWL持久层框架，旨在以Java方式高效地以编程方式访问OWL2本体和RDF图，由布拉格捷克技术大学开源。
* [KOMMA](https://github.com/komma/komma)：KOMMA是一个RDF对象映射器，也是一个用于管理和编辑RDF、RDFS和OWL的框架，由弗劳恩霍夫机床和成形技术研究所开源。
* [ZOOMA](https://github.com/EBISPOT/zooma)：ZOOMA是一款用于发现最佳本体映射的应用程序，由欧洲分子生物学实验室开发。

## 语义Web

* [Eclipse RDF4J](https://github.com/eclipse-rdf4j/rdf4j)：Eclipse RDF4J是一个强大的Java框架，用于处理RDF数据，这包括使用RDF和链接数据创建、解析、可扩展存储、推理和查询。
* [VIVO](https://github.com/vivo-project/VIVO)：VIVO是一个可扩展的语义Web应用程序，用于研究发现和展示学术工作。
* [SPARQL](https://github.com/SPARQL-Anything/sparql.anything)：SPARQL Anything是一个用于语义Web重新设计的系统，允许用户使用SPARQL查询任何内容。
* [Strabon](https://strabon.di.uoa.gr/)：Strabon是一个完全实现的语义地理空间数据库系统，由雅典大学开源。
* [LinkedGeoData](https://github.com/GeoKnow/LinkedGeoData)：LinkedGeoData致力于向数据网/语义网添加空间维度，LinkedGeoData使用OpenStreetMap项目收集的信息，并根据关联数据原则将其作为RDF知识库提供，由莱比锡大学开源。
* [Ripple](https://github.com/joshsh/ripple)：Ripple是一种基于堆栈的函数式查询语言，适用于关联数据和其他RDF数据源。
* [Vitro](https://github.com/vivo-project/Vitro)：Vitro是一个通用的基于Web的本体和实例编辑器，具有可定制的公共浏览功能。
* [Apache Commons RDF](https://github.com/apache/commons-rdf)：Commons RDF旨在为RDF 1.1提供一个通用库，并实现常见Java RDF框架(如RDF4J、Jena)以及其他库(如OWLAPI、Clerezza和其他JVM语言)的实现。
* [Corese](https://github.com/Wimmics/corese)：Corese是一个实现和扩展语义网标准的软件平台，它允许创建、操作、解析、序列化、查询、推理和验证RDF数据。
* [NeoSemantics](https://github.com/neo4j-labs/neosemantics)：NeoSemantics是一个允许在Neo4j中使用RDF的插件。
* [Wikidata Toolkit](https://github.com/Wikidata/Wikidata-Toolkit)：Wikidata Toolkit是一个用于访问Wikidata和其他Wikibase安装的Java库。
* [D2RQ](https://github.com/d2rq/d2rq)：D2RQ平台是一个用于以虚拟只读RDF图形式访问关系数据库的系统，由约翰开普勒林茨大学、HP实验室等组织开源。
* [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN)：HeFQUIN是一种用于图数据源异构联合的查询联合引擎，目前由林雪平大学开发。
* [RDFUnit](https://github.com/AKSW/RDFUnit)：RDFUnit在测试驱动数据验证本体之上实现，旨在读取和生成仅符合该本体的RDF，由莱比锡大学开源。
* [RDF-File](https://github.com/alipay/rdf-file)：RDF-File是一个处理结构化文本文件的工具组件，由支付宝开源。
* [LodView](https://github.com/LodLive/LodView)：LodView是一个基于Spring和Jena的Java Web应用程序，它是一个能够提供符合W3C标准的IRI解引用的工具。
* [Empire](https://github.com/mhgrove/Empire)：Empire使用SPARQL为RDF数据库提供标准JPA风格的接口。
* [HDT](https://github.com/rdfhdt/hdt-java)：HDT-lib是一个Java库，它实现了RDF HDT(标头-字典-三元组)二进制格式的W3C提交。
* [CARML](https://github.com/carml/carml)：CARML是一个Java库，根据RML规范，将结构化源转换为RDF，如RML映射中声明的那样。
* [JSON2RDF](https://github.com/AtomGraph/JSON2RDF)：流式的通用JSON到RDF转换器。
* [Trellis](https://github.com/trellis-ldp/trellis)：Trellis是一个用于构建可扩展的关联数据应用程序的平台。
* [Apache Rya](https://github.com/apache/rya)：Apache Rya是一个可扩展的RDF存储，它构建在列式索引存储(例如Accumulo)之上，它作为RDF4J的扩展来实现，以提供简单的查询机制(SPARQL、SERQL等)和RDF数据存储(RDF/XML、NTriples等)。
* [ESMF SDK](https://github.com/eclipse-esmf/esmf-sdk)：ESMF SDK包含旨在使用、扩展语义切面元模型(SAMM)或与语义切面元模型集成的所有各方(例如解决方案开发人员、领域专家或OEM)的工件和资源。
* [Pinto](https://github.com/stardog-union/pinto)：Pinto是一个Java框架，用于将JavaBean转换为RDF。
* [Asquare](https://github.com/cognizone/asquare)：语义开发库。
* [FOX](https://github.com/dice-group/FOX)：FOX是一个集成Linked Data Cloud的框架，利用NLP算法的多样性从NL中提取高精度的RDF三元组，由帕德博恩大学开源。
* [qEndpoint](https://github.com/the-qa-company/qEndpoint)：qEndpoint是一个高度可扩展的三重存储，具有全文和GeoSPARQL支持。
* [Parliament](https://github.com/raytheonbbn/parliament)：Parliament是专为语义网设计的高性能三重存储和推理器，由雷神公司开源。
* [jRDF2Vec](https://github.com/dwslab/jRDF2Vec)：jRDF2Vec是RDF2Vec的Java实现，它支持多线程、内存中(或基于磁盘访问)的步行生成和训练，由德国曼海姆大学开源。
* [Mobi](https://github.com/inovexcorp/mobi)：Mobi是一个协作知识图谱平台，供团队和社区开发和发布语义数据和模型。

## 知识图谱

* [DMX](https://github.com/dmx-systems/dmx-platform)：DMX是一个知识构建平台。
* [OpenSPG](https://github.com/OpenSPG/openspg)：OpenSPG是蚂蚁集团与OpenKG合作开发的基于SPG(语义增强可编程图)框架的知识图引擎。
* [Wandora](https://github.com/wandora-team/wandora)：Wandora是一个基于主题图和Java的通用信息提取、管理和发布应用程序。
* [LinkedDataHub](https://github.com/AtomGraph/LinkedDataHub)：LinkedDataHub是一款开源软件，可用于管理数据、创建可视化以及在RDF知识图上构建应用程序。

## 生物信息学

* [Nextflow](https://github.com/nextflow-io/nextflow)：Nextflow是一个工作流程系统，用于创建可扩展、可移植和可重复的工作流程，由西班牙巴塞罗那的生物医学和基因组学研究中心CRG开发。
* [Cromwell](https://github.com/broadinstitute/cromwell)：Cromwell是一个用于生物信息学的开源工作流程管理系统，由麻省理工学院和哈佛大学布罗德研究所开源。
* [GATK](https://github.com/broadinstitute/gatk)：由麻省理工学院和哈佛大学布罗德研究所开源的下一代基因组分析工具包。
* [BioJava](https://github.com/biojava/biojava)：BioJava是一个开源项目，致力于提供处理生物数据的Java框架。
* [ADAM](https://github.com/bigdatagenomics/adam)：ADAM是一个库和命令行工具，支持使用Apache Spark跨集群/云计算环境并行进行基因组数据分析，由加州大学伯克利分校、西奈山伊坎医学院、微软研究院等开源。
* [WDL](https://github.com/openwdl/wdl)：WDL是一种开放标准，用于使用人类可读和可写的语法来描述数据处理工作流，最初由布罗德研究所开发。
* [Jvarkit](https://github.com/lindenb/jvarkit)：用于生物信息学的Java实用程序。
* [Picard](https://github.com/broadinstitute/picard)：一组用于操作高通量测序(HTS)数据和格式的Java命令行工具，由麻省理工学院和哈佛大学布罗德研究所开源。
* [CDK](https://github.com/cdk/cdk)：CDK是一个用于化学信息学和生物信息学的开源Java库。
* [InterMine](https://github.com/intermine/intermine)：InterMine是一个强大的开源数据仓库系统，允许用户以最少的努力集成不同的数据源，InterMine为生命科学领域一些最大的数据仓库提供支持，由剑桥大学开源。
* [BBMap](https://github.com/BioInfoTools/BBMap)：用于DNA/RNAseq的BBMap短读对齐器和其他生物信息学工具。
* [Pegasus](https://github.com/pegasus-isi/pegasus)：Pegasus是一个可配置系统，用于在各种计算基础设施上映射和执行科学工作流程，由南加州大学信息科学研究所、威斯康星大学麦迪逊分校开源。
* [GloBI](https://github.com/globalbioticinteractions/globalbioticinteractions)：GloBI提供对现有物种相互作用数据集的访问。
* [MOLGENIS](https://github.com/molgenis/molgenis)：MOLGENIS是一个协作开源项目，其目的是为生命科学研究生成出色的软件基础设施，由格罗宁根大学开源。
* [SIRIUS](https://github.com/sirius-ms/sirius)：SIRIUS是一款使用串联质谱法从头鉴定代谢物的软件，由耶拿大学开源。
* [LibLevenshtein](https://github.com/universal-automata/liblevenshtein-java)：有关Levenshtein传感器的各种实用程序。
* [Jannovar](https://github.com/charite/jannovar)：Java中的功能变体文件注释，Jannovar提供了一个用于VCF文件注释的程序，并通过库API公开其功能，由柏林计算生物学开源。
* [PeptideShaker](https://github.com/compomics/peptide-shaker)：PeptideShaker是一个独立于搜索引擎的平台，用于解释来自多个搜索和de novo引擎的蛋白质组学鉴定结果，由根特大学开源。
* [OME](https://github.com/ome/openmicroscopy)：OME开发用于存储和操作生物光学显微镜数据的开源软件和数据格式标准，是欧洲和美国大学、研究机构和行业之间的联合项目。
* [SearchGUI](https://github.com/compomics/searchgui)：SearchGUI是一个高度适应性的开源通用界面，用于配置和运行蛋白质组学搜索和de novo引擎，由根特大学开源。
* [Bio-Formats](https://github.com/ome/bioformats)：Bio-Formats是一个独立的Java库，用于读取和写入生命科学图像文件格式，由开放显微镜环境联盟开发，其中包括威斯康星大学麦迪逊分校、邓迪大学等开发团队。
* [Bio4j](https://github.com/bio4j/bio4j)：Bio4j是一个生物信息学图数据平台，集成了Uniprot KB(SwissProt+Trembl)、Gene Ontology、UniRef(50,90,100)、NCBI Taxonomy和Expasy Enzyme DB中的大部分可用数据。
* [PathVisio](https://github.com/PathVisio/pathvisio)：PathVisio是一款免费的开源通路分析和绘图软件，可以绘制、编辑和分析生物通路，由马斯特里赫特大学和格莱斯顿研究所开发。
* [LibSBOLj](https://github.com/SynBioDex/libSBOLj)：LibSBOLj为合成生物学开放语言(SBOL)提供核心Java接口及其实现。
* [GBIF IPT](https://github.com/gbif/ipt)：IPT是由全球生物多样性信息设施(GBIF)提供的免费开源软件工具，用于通过GBIF网络发布和共享生物多样性数据集。
* [Tetrad](https://github.com/cmu-phil/tetrad)：Tetrad是一款拥有30年历史的免费工具，用于分析因果系统，根据已知的数据和因果操作推断“什么导致什么”。由CMU大学哲学系开发，并在美国国立卫生研究院与匹兹堡大学生物信息学系的支持下进行了改进。
* [MZmine 3](https://github.com/mzmine/mzmine3)：MZmine是一款用于质谱数据处理的开源软件，由芬兰VTT技术研究中心、图尔库生物技术中心开源。
* [Eclipse ChemClipse](https://github.com/eclipse/chemclipse)：Eclipse ChemClipse项目提供化学信息学和生物信息学领域的数据读取和处理功能，由Eclipse科学工作组开源。
* [JNBIS](https://github.com/mhshams/jnbis)：JNBIS是一个用Java编写的库，用于提取和解码NIST(美国国家标准与技术研究所)压缩文件和WSQ(小波标量量化)图像。
* [MesquiteCore](https://github.com/MesquiteProject/MesquiteCore)：Mesquite是一款模块化、可扩展的进化生物学软件，旨在帮助生物学家组织和分析有关生物体的比较数据。
* [Bacting](https://github.com/egonw/bacting)：Bacting是一个基于Bioclipse的化学和生物信息学开源平台，它定义了许多公共领域对象并包装了公共功能，提供了一个独立于工具包的、可编写脚本的解决方案来处理来自生命科学的数据。
* [BridgeDb](https://github.com/bridgedb/BridgeDb)：BridgeDb是一个在各种生物数据库和相关资源之间映射标识符的框架，由曼彻斯特大学、赫瑞瓦特大学、马斯特里赫特大学开源。
* [Wildbook](https://github.com/WildMeOrg/Wildbook)：Wildbook是一个开源软件框架，支持标记重新捕获、分子生态学和社会生态学研究。
* [JSBML](https://github.com/sbmlteam/jsbml)：JSBML是一个社区驱动的项目，旨在创建一个免费、开源、纯Java库，用于读取、写入和操作SBML文件和数据流。
* [BBTools](https://jgi.doe.gov/data-and-tools/software-tools/bbtools/)：BBTools是一套快速、多线程生物信息学工具，专为分析DNA和RNA序列数据而设计。
* [Dockstore](https://github.com/dockstore/dockstore)：Dockstore是一个免费的开源平台，用于共享可重用且可扩展的分析工具和工作流程，由癌症基因组合作实验室开源
* [BioFormats2Raw](https://github.com/glencoesoftware/bioformats2raw)：Bio-Formats图像文件格式到原始格式转换器。
* [Icy](https://gitlab.pasteur.fr/bia/icy)：Icy是一款图像分析软件，主要面向生物图像的分析，由巴斯德研究所开源。
* [OpenChrom](https://github.com/Openchrom/openchrom)：OpenChrom是Lablicate GmbH开发的一款用于分析和可视化质谱和色谱数据的开源工具。
* [MOLGENIS](https://github.com/molgenis/systemsgenetics)：MOLGENIS是一个协作开源项目，其使命是为生命科学研究生成出色的软件基础设施，由格罗宁根大学开源。
* [Micro-Manager](https://github.com/micro-manager/micro-manager)：Micro-Manager是一个控制显微镜硬件的应用程序，例如相机、xy平台、滤光轮等，由加利福尼亚大学旧金山分校开源。
* [FairSIM](https://github.com/fairSIM/fairSIM)：结构照明显微镜(SIM)为荧光显微镜提供了一种快速、温和的超分辨率方法，FairSIM项目旨在为使用SIM的科学家提供一系列免费开源工具和资源，由比勒费尔德大学开源。
* [GC4S](https://github.com/sing-group/GC4S)：GC4S是一个开源库，为Swing提供面向生物信息学的GUI组件集合，由维戈大学开源。
* [VCell](https://github.com/virtualcell/vcell)：VCell是一个建立在中央数据库之上并以Web应用程序形式传播的用于建模细胞生物系统的综合平台，由康涅狄格大学开源。
* [Eoulsan](https://github.com/GenomiqueENS/eoulsan)：Eoulsan是一个基于MapReduce算法的Hadoop实现的多功能框架，致力于分布式计算机上的高吞吐量测序数据分析，由巴黎高等师范学院生物研究所开源。
* [Opal](https://github.com/obiba/opal)：Opal是OBiBa用于生物样本库或流行病学研究的核心数据库应用程序。

## 基因组学

* [cBioPortal](https://github.com/cBioPortal/cbioportal)：cBioPortal提供大规模癌症基因组学数据集的可视化、分析和下载，由纪念斯隆-凯特琳癌症中心、丹娜法伯癌症研究院、毕尔肯大学、多伦多玛格丽特公主癌症中心等组织开源。
* [DNAnalyzer](https://github.com/VerisimilitudeX/DNAnalyzer)：致力于彻底改变DNA分析领域，目标是使DNA分析工具的使用更加民主化。
* [IGV](https://github.com/igvteam/igv)：用于Mac、Windows和Linux的桌面基因组可视化工具，由加州大学圣地亚哥分校、麻省理工学院和哈佛大学开源。
* [HTSJDK](https://github.com/samtools/htsjdk)：HTSJDK是统一Java库的实现，用于访问用于高通量测序数据的常见文件格式，例如SAM和VCF，由哈佛医学院开源。
* [GRIDSS](https://github.com/PapenfussLab/gridss)：GRIDSS是一个模块软件套件，包含可用于检测基因组重排的工具，由沃尔特和伊丽莎·霍尔医学研究所开源。
* [Artemis](https://github.com/sanger-pathogens/Artemis)：Artemis软件是一套用于基因组浏览和注释的软件工具，由威康桑格研究所开源。
* [MISO](https://github.com/miso-lims/miso-lims)：MISO是一个开源实验室信息管理系统(LIMS)，始于厄勒姆研究所，最近由安大略癌症研究所开发，专门用于跟踪下一代测序实验。
* [P2Rank](https://github.com/rdk/p2rank)：P2Rank是一个独立的命令行程序，可根据蛋白质结构预测配体结合口袋。
* [Apollo](https://github.com/GMOD/Apollo)：Apollo是一个基于Web的协作、实时基因组注释编辑器。
* [OpenCGA](https://github.com/opencb/opencga)：OpenCGA是一个开源项目，旨在为数百TB甚至PB级的基因组规模数据分析提供大数据存储引擎和分析框架，由剑桥大学计算生物学开源。
* [GORpipe](https://github.com/gorpipe/gor)：GORpipe是一种基于基因组有序关系架构的工具，允许在并行执行引擎中使用声明性查询语言分析大量基因组和表型表格数据，由Genuity Science开发。
* [Exomiser](https://github.com/exomiser/Exomiser)：Exomiser是一个Java程序，可以从全外显子组或全基因组测序数据中查找潜在的致病变异，由柏林夏里特大学、桑格研究所开发。
* [HMFTools](https://github.com/hartwigmedical/hmftools)：该存储库包含哈特维格医学基金会全基因组、靶向DNA和全转录组分析流程中使用的工具套件。
* [Cytoscape](https://cytoscape.org/)：Cytoscape是一个开源的生物信息学软件平台，用于可视化分子相互作用网络并与基因表达谱和其他状态数据集成，最初由西雅图系统生物学研究所开发。
* [BioTapestry](https://biotapestry.systemsbiology.net/)：BioTapestry是一种交互式工具，用于通过网络构建、可视化和共享基因调控网络模型，由西雅图系统生物学研究所与加州理工学院戴维森实验室合作创建。
* [Cloud-Pipeline](https://github.com/epam/cloud-pipeline)：与云无关的基因组学分析、科学计算和存储平台。
* [IRIDA](https://github.com/phac-nml/irida)：IRIDA是加拿大基因组流行病学综合快速传染病分析平台。
* [SnpEff](https://github.com/pcingola/SnpEff)：基因组变异注释和功能效果预测工具包。
* [PharmCAT](https://github.com/PharmGKB/PharmCAT)：一种从遗传数据集(以VCF文件表示)中提取所有CPIC指南基因变异、解释变异等位基因并生成报告的工具，由斯坦福大学和宾夕法尼亚大学维护。
* [NGB](https://github.com/epam/NGB)：NGB是一种基于Web的NGS数据查看器，具有独特的结构变异(SV)可视化功能、高性能、可扩展性和云数据支持。
* [Cellbase](https://github.com/opencb/cellbase)：Cellbase是一个集中式数据库，集成了来自多个主要基因组和生物数据库的大量信息，用于基因组注释和临床变异优先级排序，由剑桥大学计算生物学开源。
* [VarSim](https://github.com/bioinform/varsim)：VarSim是用于癌症应用的高通量基因组测序的高保真模拟验证框架，由罗氏开源。
* [FastQC](https://github.com/s-andrews/FastQC)：FastQC是一个旨在发现高通量测序数据集中潜在问题的程序，由巴布拉汉姆研究所生物信息学小组开源。
* [Osprey](https://github.com/donaldlab/OSPREY3)：OSPREY软件包提供了蛋白质设计工具，这是连续灵活性建模、集成建模和具有可证明保证的算法的独特组合，由杜克大学开源。
* [FragPipe](https://github.com/Nesvilab/FragPipe)：FragPipe是一个Java GUI，用于一套计算工具，可对基于质谱的蛋白质组数据进行全面分析，由密歇根大学开源。
* [NGSEP](https://github.com/NGSEP/NGSEPcore)：NGSEP提供了一个对象模型来支持不同类型的DNA高通量测序(HTS)数据分析。
* [GEDCOM X Java](https://github.com/FamilySearch/gedcomx-java)：该项目托管GEDCOM X项目的Java实现，并作为GEDCOM X的参考实现，由FamilySearch开源。
* [GeneMANIA](https://github.com/GeneMANIA/genemania)：GeneMANIA可以帮助你预测你最喜欢的基因和基因组的功能，由多伦多大学开源。
* [Compomics Utilities](https://github.com/compomics/compomics-utilities)：用于计算蛋白质组学的开源Java库，由根特大学开源。
* [PIA](https://github.com/medbioinf/pia)：PIA是一个用于基于MS的蛋白质推断和识别分析的工具箱，由波鸿鲁尔大学开源。

## 医疗平台

* [HAPI FHIR](https://github.com/hapifhir/hapi-fhir)：HAPI FHIR是HL7 FHIR标准的完整实现，用于Java中的医疗保健互操作性。
* [Mirth Connect](https://github.com/nextgenhealthcare/connect)：Mirth Connect是一个基于开源标准的医疗保健集成引擎，它通过接受传入的信息包并根据你提供的规则处理它们来实现两个系统之间的互操作性。
* [Open Hospital](https://github.com/informatici/openhospital)：Open Hospital是一款免费的开源健康信息管理系统(HIMS)软件应用程序。
* [Clinical Quality Language](https://github.com/cqframework/clinical_quality_language)：CQL是用于表达临床知识的HL7标准，可在广泛的临床领域中使用，包括临床决策支持(CDS)和临床质量测量(CQM)。
* [IPF](https://github.com/oehf/ipf)：Camel路由和中介引擎的扩展，为医疗保健领域的消息处理和连接信息系统提供全面支持。
* [HMIS](https://github.com/hmislk/hmis)：HMIS是一个医院信息管理系统，自2004年推出以来一直积极为40多家医疗机构提供服务。
* [HAPI FHIR Core](https://github.com/hapifhir/org.hl7.fhir.core)：适用于FHIR规范的Java核心对象处理代码，带有实用程序(包括验证器)。
* [OpenMRS](https://github.com/openmrs/openmrs-core)：OpenMRS是一个基于患者的医疗记录系统，专注于为提供商提供免费的可定制电子医疗记录系统(EMR)。
* [DCM4che](https://github.com/dcm4che/dcm4che)：Java中的DICOM实现。
* [Synthea](https://github.com/synthetichealth/synthea)：Synthea是一款合成患者群体模拟器，目标是以各种格式输出合成的、真实的(但不是真实的)患者数据和相关的健康记录。
* [Weasis](https://github.com/nroduit/Weasis)：Weasis是一款独立的基于网络的软件，用于可视化从医疗成像设备获得的图像。
* [OpenICE](https://github.com/mdpnp/mdpnp)：OpenICE是一项旨在创建集成临床环境的社区实施的倡议，该计划不仅包括软件实现，还包括更广泛的临床生态系统的架构，以实现临床研究的新途径。
* [Dicoogle](https://github.com/bioinformatics-ua/dicoogle)：Dicoogle是一款可扩展、独立于平台的开源PACS归档软件，它以更敏捷的索引和检索机制取代了传统的集中式数据库，由阿威罗大学开源。
* [Phoenix CTMS](https://github.com/phoenixctms/ctsms)：Phoenix CTMS是一款大型Web应用程序，将临床研究中使用的数据库软件的功能结合在一个模块化系统中。
* [SIMRS Khanza](https://github.com/mas-elkhanza/SIMRS-Khanza)：适用于医院、诊所、保健中心、私人医生的软件，已在印度尼西亚1000多家医院使用。
* [OpenELIS Global 2](https://github.com/I-TECH-UW/OpenELIS-Global-2)：OpenELIS Global是专为公共卫生实验室量身定制的开放式企业级实验室信息系统软件，由华盛顿大学开源。
* [LinuxForHealth FHIR](https://github.com/LinuxForHealth/FHIR)：LinuxForHealth FHIR服务器(以前称为IBM FHIR服务器)是HL7 FHIR规范的模块化Java实现，支持版本R4和R4B，重点关注性能和可配置性。
* [Pathling](https://github.com/aehrc/pathling)：Pathling是一组工具，可让你在健康数据分析中更轻松地使用FHIR和临床术语，由澳大利亚电子健康研究中心开源。

## 化学领域

* [CDK](https://github.com/cdk/cdk)：CDK是一个用于化学信息学和生物信息学的开源Java库。
* [Eclipse ChemClipse](https://github.com/eclipse/chemclipse)：Eclipse ChemClipse项目提供化学信息学和生物信息学领域的数据读取和处理功能，由Eclipse科学工作组开源。
* [JChemPaint](https://github.com/JChemPaint/jchempaint)：JChemPaint是使用CDK开发的2D化学结构编辑器和查看器。
* [OpenChemLib](https://github.com/Actelion/openchemlib)：OpenChemLib是基于Java的框架，提供化学信息学核心功能和用户界面组件。
* [ChemicalTagger](https://github.com/BlueObelisk/chemicaltagger)：ChemicalTagger是化学领域语义文本挖掘的工具。
* [JMol](https://github.com/BobHanson/Jmol-SwingJS)：JMol是一个开源Java/SwingJS应用程序，用于可视化和分析具有化学品特征的3D分子结构、晶体、材料和生物分子。
* [Toxtree](https://toxtree.sourceforge.net/)：Toxtree是一个功能齐全、灵活、用户友好的开源应用程序，它能够通过应用决策树方法来估计毒性危害。
* [OPSIN](https://github.com/dan2097/opsin)：OPSIN是一个用于IUPAC名称到结构转换的Java库，可为有机化学命名法提供高召回率和精确度，由剑桥大学化学系开源。
* [MolVec](https://github.com/ncats/molvec)：NCATS(化学) OCR引擎，可以将化学图像矢量化为化学对象，并尽可能保留2D布局，由国家转化科学促进中心开源。
* [DataWarrior](https://github.com/thsa/datawarrior)：DataWarrior是一个用于交互式数据分析和可视化的程序。

## 安全

这里列出了安全相关的库、框架、组件，例如JWT、OAuth和CAS。

#### 安全库

* [Passay](https://github.com/vt-middleware/passay)：Passay是Java的密码策略实现，由弗吉尼亚理工大学开源。
* [PicketLink](https://github.com/picketlink/picketlink)：PicketLink是一个用于保护Java EE应用程序的安全框架。
* [SSLContext Kickstart](https://github.com/Hakky54/sslcontext-kickstart)：SSLContext Kickstart是一个高级库，用于配置HTTP客户端通过SSL/TLS进行通信以进行单向身份验证或双向身份验证。
* [OWASP ESAPI Java](https://github.com/ESAPI/esapi-java-legacy)：OWASP ESAPI是一个免费、开源的Web应用程序安全控制库，使程序员可以更轻松地编写风险较低的应用程序。
* [Auth0 Java](https://github.com/auth0/auth0-java)：Auth0平台的Java客户端库。
* [Shaun](https://gitee.com/baomidou/shaun)：Shaun是基于pac4j-jwt的WEB安全组件。
* [Spring Session](https://github.com/spring-projects/spring-session)：Spring Session提供了一个API和实现来管理用户的会话信息，同时也使得支持集群会话变得很简单，而无需绑定到应用程序容器特定的解决方案。
* [Microsoft Authentication Library](https://github.com/AzureAD/microsoft-authentication-library-for-java)：MSAL4J使应用程序能够与Microsoft身份平台集成。
* [PowerAuth](https://github.com/wultra/powerauth-crypto)：PowerAuth是一种用于密钥交换和后续请求签名的协议，专为具有高安全性要求的应用程序(例如银行应用程序或身份管理应用程序)而设计。
* [TLS-Attacker](https://github.com/tls-attacker/TLS-Attacker)：TLS-Attacker是一个基于Java的框架，用于分析TLS库。
* [SecurityBuilders](https://github.com/tersesystems/securitybuilder)：该库为java.security类实现了一组流式的API构建器，并提供了类型更安全、更直观的API来访问信任存储、密钥存储和密钥。
* [Java Certificado](https://github.com/Samuel-Oliveira/Java_Certificado)：Java数字证书管理项目。
* [OpenJSSE](https://github.com/openjsse/openjsse)：OpenJSSE是支持TLS 1.3 的JSSE提供程序。
* [RhizobiaJ](https://github.com/momosecurity/rhizobia_J)：Java安全SDK及编码规范，由陌陌安全团队开源。
* [NTRU](https://github.com/tbuktu/ntru)：NTRUEncrypt和NTRUSign的Java实现。
* [Nmap4j](https://github.com/narkisr/nmap4j)：Java Nmap包装器。
* [OpenAS2](https://github.com/OpenAS2/OpenAs2App)：OpenAS2是EDIINT AS2标准的基于Java的实现，它旨在用作服务器，它的可配置性极强，支持多种签名和加密算法。
* [Soteria](https://github.com/eclipse-ee4j/soteria)：Soteria是Jakarta Security的实现。
* [AntiSamy](https://github.com/nahsra/antisamy)：AntiSamy是一个用于快速、可配置地清理来自不受信任来源的HTML的库。
* [Fosstars Rating Core](https://github.com/SAP/fosstars-rating-core)：这是一个用于定义和计算开源项目评级的框架，由SAP开源。
* [RFC3161 Timestamping Server](https://github.com/elbosso/rfc3161timestampingserver)：该项目提供了一个符合RFC 3161的时间戳权威/服务器。

#### 安全工具

* [ZAP](https://github.com/zaproxy/zaproxy)：ZAP是世界上最受欢迎的免费安全工具之一，它可以帮助你在开发和测试应用程序时自动查找Web应用程序中的安全漏洞。
* [Nzyme](https://github.com/nzymedefense/nzyme)：借助Nzyme，你可以监控所有以太网和WiFi网络流量是否存在威胁、确认预期行为并有选择地将数据转发到你的SIEM或日志管理系统。
* [PacBot](https://github.com/tmobile/pacbot)：PacBot是一个用于云持续合规性监控、合规性报告和安全自动化的平台，由T-Mobile开源。
* [APIKit](https://github.com/API-Security/APIKit)：APIKit可以主动/被动扫描发现应用泄露的API文档，并将API文档解析成BurpSuite中的数据包用于API安全测试，由APISecurity社区开发。
* [Tsunami](https://github.com/google/tsunami-security-scanner)：Tsunami是一款通用网络安全扫描器，具有可扩展的插件系统，可高置信度地检测高严重性漏洞，由Google开源。
* [jSQL Injection](https://github.com/ron190/jsql-injection)：jSQL Injection是一个轻量级应用程序，用于从服务器查找数据库信息。
* [Mariana Trench](https://github.com/facebook/mariana-trench)：Mariana Trench是一个针对Android的专注于安全的静态分析平台，由Facebook开源。
* [CTFCrackTools](https://github.com/0Chencc/CTFCrackTools)：中国国内首个CTF工具框架，旨在帮助CTFer快速攻克难关。
* [HaE](https://github.com/gh0stkey/HaE)：HaE是一款网络安全、领域下的辅助型框架式项目，旨在实现对HTTP消息(包含WebSocket)的高亮标记和信息提取。
* [Keywhiz](https://github.com/square/keywhiz)：Keywhiz是一个用于分发和管理密钥的系统，由Square开源。
* [Janssen](https://github.com/JanssenProject/jans)：Janssen是一个可扩展的开源数字身份平台，是基于标准、开发人员友好的组件的软件发行版，这些组件经过精心设计，可以在任何云中协同工作。
* [Peergos](https://github.com/Peergos/Peergos)：Peergos是一个创新性的去中心化文件存储和协作平台，它致力于提供安全、私密和可验证的在线分享与交互体验，由牛津大学、墨尔本大学等开源。
* [RiskScanner](https://github.com/fit2cloud/riskscanner)：RiskScanner是飞致云开源的多云安全合规扫描平台，基于Cloud Custodian、Prowler和Nuclei引擎，实现对主流公(私)有云资源的安全合规扫描和漏洞扫描。
* [SecHub](https://github.com/mercedes-benz/sechub)：SecHub提供了一个中央API，可以使用不同的安全工具来测试软件，由奔驰开源。
* [Firing Range](https://github.com/google/firing-range)：Firing Range是Web应用程序安全扫描器的测试台，为一系列漏洞提供综合、广泛的覆盖，由Google开源。
* [Portecle](https://github.com/scop/portecle)：Portecle是一个用户友好的GUI应用程序，用于创建、管理和检查密钥库、密钥、证书、证书请求、证书吊销列表等。
* [HummerRisk](https://github.com/HummerRisk/HummerRisk)：HummerRisk是开源的云原生安全平台，以非侵入的方式解决云原生的安全和治理问题，由北京瀚马科技开源。
* [KeyStore Explorer](https://github.com/kaikramer/keystore-explorer)：KeyStore Explorer是Java命令行实用程序keytool和jarsigner的免费GUI替代品。
* [UTMStack](https://github.com/utmstack/UTMStack)：UTMStack是一个统一的威胁管理平台，融合了SIEM(安全信息和事件管理)和XDR(扩展检测和响应)技术。
* [Magpie](https://github.com/openraven/magpie)：Magpie是一个免费的开源框架和社区开发的插件集合，可用于构建完整的端到端安全工具，例如CSPM或云安全态势管理器。

#### 自保护

* [OpenRASP](https://github.com/baidu/openrasp)：OpenRASP是百度安全推出的一款免费、开源的应用运行时自我保护产品。
* [JRASP-Agent](https://github.com/jvm-rasp/jrasp-agent)：专注于JVM的运行时防御系统RASP。
* [Hdiv](https://github.com/hdiv/hdiv)：Hdiv是实时、自我保护应用程序开源软件的领先提供商。

#### 身份认证和授权

* [Spring Security](https://github.com/spring-projects/spring-security)：Spring Security为Spring IO Platform提供安全服务。
* [Apache Shiro](https://github.com/apache/shiro)：Apache Shiro是一个功能强大且易于使用的Java安全框架，可以执行身份验证、授权、加密和会话管理。
* [Apereo CAS](https://github.com/apereo/cas)：CAS是一个企业多语言单点登录解决方案和网络身份提供商，并试图成为满足你的身份验证和授权需求的综合平台。
* [AndOTP](https://github.com/andOTP/andOTP)：AndOTP是适用于Android的开源双因素身份验证。
* [Kisso](https://gitee.com/baomidou/kisso)：Kisso是基于Cookie的SSO中间件，它是一把快速开发Java Web登录系统(SSO)的瑞士军刀。
* [GoogleAuth](https://github.com/wstrange/GoogleAuth)：GoogleAuth是一个Java服务器库，它实现RFC 6238中指定的基于时间的一次性密码(TOTP)算法。
* [Sa-Token](https://gitee.com/dromara/sa-token)：Sa-Token是一个轻量级Java权限认证框架，主要解决登录认证、权限认证、单点登录、OAuth 2.0、分布式Session会话、微服务网关鉴权等一系列权限相关问题，由dromara社区开源。
* [Athenz](https://github.com/AthenZ/athenz)：Athenz是一个开源平台，用于动态基础设施中基于X.509证书的服务身份验证和细粒度访问控制，由Yahoo开源。
* [Sureness](https://github.com/dromara/sureness)：Sureness是一个简单高效的开源安全框架，专注于REST API的保护，由dromara社区开源。
* [WSO2 Identity Server](https://github.com/wso2/product-is)：WSO2 Identity Server是一种开源身份和访问管理解决方案，跨企业和云服务环境联合和管理身份。
* [Akto](https://github.com/akto-api-security/akto)：Akto是一个即时、开源API安全、API发现、自动化业务逻辑测试和运行时检测。
* [UAF](https://github.com/eBay/UAF)：UAF强身份验证框架使在线服务和网站能够透明地利用最终用户计算设备的本机安全功能进行强用户身份验证，并减少与创建和记住许多在线凭据相关的问题，由eBay开源。
* [Aegis](https://github.com/beemdevelopment/Aegis)：Aegis Authenticator是一款免费、安全且开源的Android 2FA应用程序。
* [SocialAuth](https://github.com/3pillarlabs/socialauth)：用于在Google、Yahoo、Facebook、Twitter、LinkedIn和许多其他提供商上进行身份验证、获取个人资料、联系人和更新状态的Java库。
* [Apache Syncope](https://github.com/apache/syncope)：Apache Syncope是一个用于管理企业环境中的数字身份的开源系统，采用Java EE技术实现。
* [MidPoint](https://github.com/Evolveum/midpoint)：MidPoint是一个综合性身份治理和管理(IGA)平台。
* [Vertx-Auth](https://github.com/eclipse-vertx/vertx-auth)：包含Vert.x和常见身份验证接口的身份验证实现。
* [jCasbin](https://github.com/casbin/jcasbin)：jCasbin是一个强大且高效的Java项目开源访问控制库，它为基于各种访问控制模型的强制授权提供支持。
* [OACC](https://github.com/acciente/oacc-core)：OACC是一个功能齐全的API，可强制执行和管理应用程序的身份验证和授权需求。
* [AuthzForce](https://github.com/authzforce/core)：AuthzForce项目提供了一个符合OASIS XACML标准v3.0的基于属性的访问控制(ABAC)框架，主要由授权策略引擎和RESTful授权服务器组成。
* [Waffle](https://github.com/Waffle/waffle)：Waffle是一个原生Windows身份验证框架，执行与Windows身份验证相关的功能，支持Negotiate、NTLM和Kerberos。
* [JustAuth](https://github.com/justauth/JustAuth)：JustAuth是一个第三方授权登录的工具类库，它可以让我们脱离繁琐的第三方登录SDK。
* [Easy Security](https://gitee.com/aizuda/easy-security)：Easy Security是基于过滤器实现的一款配合Spring快速开发的安全认证框架，由爱组搭开源。
* [OpenIDM](https://www.forgerock.com)：OpenIDM是一个用Java编程语言编写的身份管理系统。
* [WebAuthn4J](https://github.com/webauthn4j/webauthn4j)：WebAuthn4J是一个用于WebAuthn和Apple App Attest服务器端验证的可移植Java库。
* [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)：OpenAM是一种访问管理解决方案，包括身份验证、SSO、授权、联合、权利和Web服务安全。
* [Google Auth Library](https://github.com/googleapis/google-auth-library-java)：Google提供的Java开源身份验证客户端库。
* [XXL-SSO](https://gitee.com/xuxueli0323/xxl-sso)：XXL-SSO是一个分布式单点登录框架。
* [Java-TOTP](https://github.com/samdjstevens/java-totp)：一个Java库，可帮助生成和验证基于时间的一次性密码以进行多重身份验证。
* [Java Webauthn Server](https://github.com/Yubico/java-webauthn-server)：Java的服务器端Web身份验证库，提供服务器支持Web身份验证(包括密钥身份验证)所需的依赖方操作的实现。
* [Mujina](https://github.com/OpenConext/Mujina)：Mujina是一个SAML2身份和服务提供商(IdP&SP)。
* [SAML-Client](https://github.com/coveooss/saml-client)：该库实现了一个非常简单的SAML 2.0客户端，允许使用HTTP POST绑定从合规身份提供商检索经过身份验证的身份。
* [SAML Java](https://github.com/SAML-Toolkits/java-saml)：此库可以向Java应用程序添加SAML支持。
* [Topaz](https://www.topaz.sh/)：Topaz是一种开源授权服务，为应用程序和API提供细粒度、实时、基于策略的访问控制。
* [Iridium](https://github.com/IridiumIdentity/iridium)：Iridium是一个符合OAuth 2.x的客户身份和访问管理(CIAM)系统。
* [OpenID4Java](https://github.com/jbufu/openid4java)：该库允许你为Java Web应用程序启用OpenID。
* [S3Auth](https://github.com/yegor256/s3auth)：Amazon S3 HTTP基本身份验证网关。
* [Line FIDO2 Server](https://github.com/line/line-fido2-server)：FIDO是在线身份验证的开放标准，这是Line开源的经过FIDO联盟和依赖方示例的正式认证的实现。
* [AuthX](https://gitee.com/devlive-community/authx)：AuthX是一个简单、易用的开源权限管理平台，旨在帮助开发者轻松地实现基于角色的访问控制(RBAC)和权限管理。
* [PowerAuth Server](https://github.com/wultra/powerauth-server)：PowerAuth Server是实现PowerAuth协议加密的核心后端应用程序，它负责设备注册、激活生命周期、应用程序管理和集成安全。
* [LoopAuth](https://gitee.com/lucky-color/loop-auth)：一款Java Web鉴权框架，同时支持RBAC、ABAC，并提供会话管理等功能。
* [Authsaur](https://github.com/authsaur/authsaur)：Authsaur帮助更多企业统一和构建标准化的用户身份体系，以数十年优秀开源产品CAS为内核，打造开箱即用的企业级单点登录系统。
* [Biscuit Java](https://github.com/biscuit-auth/biscuit-java)：Biscuit的Java库实现。
* [OpenUnison](https://github.com/TremoloSecurity/OpenUnison)：OpenUnison是一个统一身份管理平台。

#### JWT库

* [JJWT](https://github.com/jwtk/jjwt)：JJWT旨在成为最易于使用和理解的库，用于在JVM和Android上创建和验证JWT和JWK。
* [Java-JWT](https://github.com/auth0/java-jwt)：JWT的Java实现。
* [Pac4j](https://github.com/pac4j/pac4j)：Pac4j是一个简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [JWT-Starter](https://github.com/bfwg/springboot-jwt-starter)：适用于无状态和基于令牌的身份验证应用程序的Spring Boot JWT Starter套件。
* [Jose4j](https://bitbucket.org/b_c/jose4j/src/master/)：Jose4j库是IETF JOSE工作组的JWS、JWE、JWA和JWK的开源实现，它是用Java编写的，并且仅依赖于JCA API进行加密。
* [Nimbus-JOSE-JWT](https://connect2id.com/products/nimbus-jose-jwt)：适用于Java和Android的JWT库。
* [FusionAuth JWT](https://github.com/FusionAuth/fusionauth-jwt)：一个简单易用的Java 8 JWT库，全天验证、签名、编码、解码。
* [Vert.x Auth](https://github.com/vert-x3/vertx-auth)：Vertx框架提供JWT集成的库。
* [Inverno](https://github.com/inverno-io/inverno-mods/tree/master/inverno-security-jose)：Inverno框架提供JWT库，提供JSON对象签名和加密RFC规范的完整实现。
* [JWT](https://github.com/PhilJay/JWT)：轻量级Kotlin JWT实现。
* [JWT-Java](https://github.com/BastiaanJansen/jwt-java)：使用流式的API轻松创建和解析JWT并创建自定义JWT验证器。
* [JWT-Resource-Server](https://github.com/entur/jwt-resource-server)：用于依赖使用Access Tokens进行授权的同步(基于Servlet)OpenID资源服务器的工具。

#### OAuth库

* [Keycloak](https://github.com/keycloak/keycloak)：适用于现代应用程序和服务的开源身份和访问管理解决方案，由RedHat基金会开源。
* [SuperTokens](https://github.com/supertokens/supertokens-core)：Auth0/Firebase Auth/AWS Cognito的开源替代品。
* [ScribeJava](https://github.com/scribejava/scribejava)：适用于Java的简单OAuth库。
* [Spring Authorization Server](https://github.com/spring-projects/spring-authorization-server)：Spring Authorization Server是一个框架，提供OAuth 2.1和OpenID Connect 1.0规范以及其他相关规范的实现。
* [Pac4j](https://github.com/pac4j/pac4j)：Pac4j是一个简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [UAA](https://github.com/cloudfoundry/uaa)：UAA是一种多租户身份管理服务，在Cloud Foundry中使用，但也可用作独立的OAuth2服务器。
* [MaxKey](https://gitee.com/dromara/MaxKey)：MaxKey是业界领先的IAM-IDaas身份管理和认证产品，支持OAuth 2.x/OpenID Connect、SAML 2.0、JWT、CAS、SCIM等标准协议，由dromara社区开源。
* [Play Authenticate](https://github.com/joscha/play-authenticate)：Play框架2.x的身份验证插件。
* [OAuth-Apis](https://github.com/OAuth-Apis/apis)：该项目提供了一个OAuth 2.0授权服务器，可用于配置API身份验证，目前不再维护。
* [Google OAuth Client](https://github.com/googleapis/google-oauth-java-client)：由Google编写的一个功能强大且易于使用的Java库，适用于OAuth 1.0和OAuth 2.0授权标准。
* [OxAuth](https://github.com/GluuFederation/oxAuth)：OxAuth是一个开源OpenID Connect提供商(OP)和UMA授权服务器(AS)。
* [Java Authorization Server](https://github.com/authlete/java-oauth-server)：这是Java中的授权服务器实现，支持OAuth 2.0和OpenID Connect。
* [JOAuth](https://github.com/twitter/joauth)：使用OAuth验证HTTP请求的Java库，由Twitter开源。
* [MITREid-Connect](https://github.com/mitreid-connect/OpenID-Connect-Java-Spring-Server)：该服务器可用作OpenID Connect身份提供商以及通用OAuth 2.0授权服务器。
* [OAuth2-Essentials](https://github.com/dmfs/oauth2-essentials)：基于Http-Client-Essentials的OAuth2客户端实现。
* [Tokens](https://github.com/zalando/tokens)：Tokens是一个用于验证和存储OAuth 2.0服务访问令牌的Java库，它具有弹性、可配置且经过生产测试，并且适用于所有JVM语言，由Zalando开源。
* [Smart-SSO](https://github.com/a466350665/smart-sso)：Spring Boot SSO单点登录，OAuth2实现，支持APP登录、分布式。
* [JustAuthPlus](https://gitee.com/fujieid/jap)：JAP是一款开源的登录认证中间件，基于模块化设计，为所有需要登录认证的Web应用提供一套标准的技术解决方案。
* [AppAuth](https://github.com/openid/AppAuth-Android)：用于与OAuth 2.0和OIDC提供商进行通信的Android客户端SDK。
* [Signpost](https://github.com/mttkay/signpost)：Signpost是一种简单直观的解决方案，用于在Java平台上签署符合OAuth Core 1.0a标准的HTTP消息。
* [Light-OAuth2](https://github.com/networknt/light-oauth2)：一个快速、轻量级、云原生的OAuth 2.0服务器，构建在Light-4j框架之上。
* [CredentialManager](https://github.com/PhilippHeuer/credential-manager)：一个简单的OAuth客户端和CredentialManager库，支持多个存储后端。
* [Apache Oltu](https://github.com/apache/oltu)：Apache Oltu是OAuth协议的Java语言实现。
* [TOPIAM](https://gitee.com/topiam/eiam)：基于Spring Boot 3开源的IDaas/IAM平台，用于管理企业内员工账号、权限、身份认证、应用访问。

#### 跨域身份管理

* [OSIAM](https://github.com/osiam/osiam)：OSIAM是一种安全身份管理解决方案，提供基于REST的身份验证和授权服务。
* [SCIMano](https://github.com/SAP/scimono)：SAP SCIMano是用于身份管理的SCIM 2.0行业标准的Java参考实现。
* [UnboundID SCIM 2 SDK](https://github.com/pingidentity/scim2)：适用于Java的UnboundID SCIM 2.0 SDK。
* [SCIM-SDK](https://github.com/Captain-P-Goldfish/SCIM-SDK)：这是RFC7643和RFC7644定义的SCIM(跨域身份管理系统)协议的开源实现。
* [INDIGO IAM](https://github.com/indigo-iam/iam)：INDIGO IAM是一项身份和访问管理服务，最初是在INDIGO-Datacloud Horizon 2020项目背景下开发的，目前由INFN维护和开发。
* [WSO2 Charon](https://github.com/wso2/charon)：WSO2 Charon是SCIM协议的开源实现，SCIM协议是身份配置的开放标准。
* [SCIM](https://github.com/GluuFederation/scim)：SCIM服务器/客户端。

#### 加密库

* [Tink](https://github.com/google/tink)：一个多语言、跨平台库，提供安全、易于正确使用且难以误用的加密API，由Google开源。
* [BouncyCastle Java](https://github.com/bcgit/bc-java)：BouncyCastle Java发行版。
* [Apache Commons Crypto](https://github.com/apache/commons-crypto)：Apache Commons Crypto是一个使用AES-NI优化的加密库，它提供了密码级别和Java流级别的Java API。
* [Themis](https://github.com/cossacklabs/themis)：Themis是一个开源高级加密服务库，用于在身份验证、存储、消息传递、网络交换等过程中保护数据。
* [Jasypt](https://github.com/jasypt/jasypt)：Jasypt是一个Java库，允许开发人员以最小的努力向项目添加基本的加密功能，而无需深入了解密码学的工作原理。
* [Cryptomator](https://github.com/cryptomator/cryptomator)：Cryptomator为云中的文件提供多平台透明客户端加密。
* [Cryptacular](https://github.com/vt-middleware/cryptacular)：对Java版BouncyCastle加密API的友好补充。
* [Wycheproof](https://github.com/google/wycheproof)：Wycheproof项目针对已知攻击测试加密库，由Google开源。
* [I2P](https://github.com/i2p/i2p.i2p)：一个匿名网络，提供一个简单的层，身份敏感的应用程序可以使用它来安全地通信。
* [Cipher.so](https://github.com/linisme/Cipher.so)：将密码等安全数据加密到本机.so库中的简单方法。
* [CredHub](https://github.com/cloudfoundry/credhub)：CredHub提供了一个API，可以安全地存储、生成、检索和删除各种类型的凭据。
* [Encrypt](https://github.com/GcsSloop/encrypt)：适用于Java和Android的加解密工具库。
* [Java-AES-Crypto](https://github.com/tozny/java-aes-crypto)：一个简单的Android库，用于加密和解密字符串，旨在避免大多数此类类所遭受的经典错误。
* [EncryptedPreferences](https://github.com/PDDStudio/EncryptedPreferences)：适用于Java和Android的AES-256加密SharedPreferences。
* [Conscrypt](https://github.com/google/conscrypt)：Conscrypt是一个Java安全提供程序，它实现了部分Java加密扩展和Java安全套接字扩展，由Google开源。
* [KeePassJava2](https://github.com/jorabin/KeePassJava2)：KeePass密码数据库的Java API。
* [Themis](https://github.com/cossacklabs/themis)：易于使用的数据保护加密框架，具有前向保密和安全数据存储的安全消息传递，由小米开源。
* [Password4j](https://github.com/Password4j/password4j)：Password4j是一个Java用户友好的加密库，用于使用不同的密钥派生函数(KDF)和加密哈希函数(CHF)来加密和验证密码。
* [Lazysodium](https://github.com/terl/lazysodium-java)：Libsodium加密库的Java实现。
* [XiPKI](https://github.com/xipki/xipki)：XiPKI是一个高度可扩展和高性能的开源PKI(CA和OCSP响应器)。
* [Keyczar](https://github.com/google/keyczar)：易于使用的加密工具包，由Google开源。
* [AES](https://github.com/mervick/aes-everywhere)：AES是跨语言加密库，它提供了在不同编程语言和不同平台上使用单一算法加密和解密数据的能力。
* [AWS Encryption SDK](https://github.com/aws/aws-encryption-sdk-java)：AWS加密SDK。
* [JNCryptor](https://github.com/RNCryptor/JNCryptor)：RNCryptor的Java实现。
* [Clusion](https://github.com/encryptedsystems/Clusion)：来自布朗大学加密系统实验室的可搜索加密库。
* [Encryptor4j](https://github.com/martinwithaar/Encryptor4j)：Encryptor4j由一组包装器和实用程序类组成，使你可以更轻松地在应用程序中利用加密技术。
* [EJBCA](https://github.com/Keyfactor/ejbca-ce)：开源公钥基础设施(PKI)和证书颁发机构(CA)软件。
* [MPC4j](https://github.com/alibaba-edu/mpc4j)：MPC4j是一个高效且易于使用的安全多方计算(MPC)和差分隐私(DP)库，阿里开源。
* [FRESCO](https://github.com/aicis/fresco)：FRESCO是一个高效、安全的计算框架，用Java编写。
* [PrimiHub Platform](https://github.com/primihub/primihub-platform)：PrimiHub Platform是一个多方计算和多方联合任务安全调度平台，用于MPC和FL点对点服务。
* [ACME4J](https://github.com/shred/acme4j)：这是RFC 8555中指定的ACME协议的Java客户端。
* [IDMask](https://github.com/patrickfav/id-mask)：IDMask是一个Java库，用于在需要公开发布内部ID(例如来自数据库的ID)以隐藏其实际值并防止伪造时屏蔽内部ID。

#### 密码库

* [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)：Nbvcxz是一个密码强度估计器。
* [Zxcvbn4j](https://github.com/nulab/zxcvbn4j)：这是zxcvbn的Java端口，zxcvbn是一个JavaScript密码强度估计器。
* [Google Authenticator](https://github.com/google/google-authenticator)：包括针对多个移动平台的一次性密码生成器的实现，由Google开源。
* [OTP-Java](https://github.com/BastiaanJansen/OTP-Java)：一款小型且易于使用的Java一次性密码生成器，实现RFC 4226和RFC 6238。
* [Java-OTP](https://github.com/jchambers/java-otp)：Java-OTP是一个用于生成HOTP(RFC 4226)或TOTP(RFC 6238)一次性密码的Java库。
* [OneTrickPony](https://github.com/Osmerion/OneTrickPony)：OneTrickPony是一个现代Java库，它实现了对一次性密码(OTP)的支持。
* [1Time](https://github.com/atlassian/1time)：RFC-6238和RFC-4226的Java/Kotlin轻量级实现，用于生成和验证基于时间的一次性密码(TOTP)，Atlassian开源。
* [RandPassGenerator](https://github.com/nsacyber/RandPassGenerator)：RandPassGenerator是一个简单的命令行实用程序，用于生成随机密码、密码短语和原始密钥，由美国国家安全局网络安全局开源。

#### 加密算法

* [Kalium](https://github.com/abstractj/kalium)：网络和密码学(NaCl)库的Java绑定。
* [GM-JSSE](https://github.com/aliyun/gm-jsse)：开源国密通信纯Java JSSE实现，由阿里开源。
* [SM-Crypto](https://github.com/antherd/sm-crypto)：国密算法SM2、SM3和SM4的Java版。
* [GMHelper](https://github.com/ZZMarquis/gmhelper)：国密SM2/SM3/SM4算法简单封装。
* [EdDSA-Java](https://github.com/str4d/ed25519-java)：这是EdDSA在Java中的实现。
* [Dilithium](https://github.com/mthiim/dilithium-java)：后量子加密算法Dilithium的实验性Java实现。
* [jBCrypt](https://github.com/jeremyh/jBCrypt)：jBCrypt是OpenBSD Blowfish密码哈希算法的Java实现。
* [SM2Java](https://github.com/PopezLotado/SM2Java)：国密SM2、SM3 Java实现。
* [Cat](https://gitee.com/bat/cat)：一款小巧的Java加密与解密算法调用工具包。
* [Bcrypt](https://github.com/patrickfav/bcrypt)：bcrypt密码哈希函数的Java独立实现。
* [Argon2-JVM](https://github.com/phxql/argon2-jvm)：JVM的Argon2绑定。
* [2FA](https://github.com/j256/two-factor-auth)：2因素身份验证Java代码，使用基于时间的一次性密码(TOTP)算法。
* [XXTEA-Java](https://github.com/xxtea/xxtea-java)：XXTEA是一种快速且安全的加密算法，这是一个用于Java的XXTEA库。
* [Tencent Kona SM Suite](https://github.com/Tencent/TencentKonaSMSuite)：腾讯Kona SM Suite是一套Java安全提供程序，支持算法SM2、SM3和SM4，以及协议TLCP/GMSSL、TLS 1.3和TLS 1.2。
* [Chronicle-Salt](https://github.com/OpenHFT/Chronicle-Salt)：NaCl库的Chronicle包装器。
* [Tongsuo-Java-SDK](https://github.com/Tongsuo-Project/tongsuo-java-sdk)：Tongsuo-Java-SDK是一个Java安全提供程序，它实现了部分Java加密扩展和Java安全套接字扩展。
* [SMCryptoj](https://github.com/zhuobie/smcryptoj)：SM国密算法的Java绑定。
* [Hash4j](https://github.com/dynatrace-oss/hash4j)：Hash4j是Dynatrace的一个Java库，其中包括基于高质量哈希函数的各种非加密哈希算法和数据结构。
* [Homomorphic Encryption](https://github.com/adwise-fiu/Homomorphic_Encryption)：包含ElGamal、Paillier、Goldweiser-Micali和DGK同态加密系统的软件包，由佛罗里达国际大学开源。
* [GmSSL-Java](https://github.com/GmSSL/GmSSL-Java)：本项目是GmSSL密码库的Java语言封装，可以用于Java环境和Android系统上的应用开发。

## 模板引擎

* [Thymeleaf](https://github.com/thymeleaf/thymeleaf)：Thymeleaf是一个现代服务器端Java模板引擎，适用于Web和独立环境。
* [JSP](https://www.oracle.com/java/technologies/jspt.html)：Java应用程序最流行的视图技术之一，也是内置的模板引擎。
* [Apache FreeMarker](https://github.com/apache/freemarker)：FreeMarker是一个基于模板生成文本输出(从HTML到自动生成源代码的任何内容)的通用工具。
* [Pebble](https://github.com/PebbleTemplates/pebble)：Pebble是一个受Twig启发的Java模板引擎，带有内置的自动转义功能以确保安全，并且包括对国际化的集成支持。
* [Groovy](http://groovy-lang.org/templating.html#_the_markuptemplateengine)：Groovy提供Markup模板引擎，该引擎基于构建器语法，可用于生成任何文本格式。
* [Apache Velocity](https://github.com/apache/velocity-engine)：Apache Velocity是一个用Java编写的通用模板引擎。
* [Mustache](https://github.com/spullara/mustache.java)：支持许多其他编程语言的模板引擎。
* [Apache Tiles](https://github.com/apache/tiles)：适用于现代Java应用程序的免费开源模板框架。
* [EscapeVelocity](https://github.com/google/escapevelocity)：EscapeVelocity是一个可以在Java中使用的模板引擎，它是Apache Velocity功能子集的重新实现，由Google开源。
* [Jade4j](https://github.com/neuland/jade4j)：用Java编写的jade实现，现在改成pug4j。
* [Handlebars.java](https://github.com/jknack/handlebars.java)：使用Java的无逻辑和语义Mustache模板。
* [Beetl](https://github.com/javamonkey/beetl2.0)：Beetl是新一代的模板引擎，更简单易用。
* [Rocker](https://github.com/fizzed/rocker)：Rocker是一个Java 8+优化、近乎零拷贝渲染的快速模板引擎，可生成静态类型、纯Java对象模板，并与项目的其余部分一起编译。
* [Jinja](https://github.com/HubSpot/jinjava)：基于Django模板语法的基于Java的模板引擎，适用于渲染Jinja模板。
* [HTTL](https://github.com/httl/httl)：HTTL是一个高性能的开源Java模板引擎，适用于动态HTML页面输出，可替代JSP页面，指令和Velocity相似。
* [HtmlFlow](https://github.com/xmlet/HtmlFlow)：HtmlFlow是一种Java DSL，可以以流式的方式编写类型安全的HTML文档。
* [Chunk](https://github.com/tomj74/chunk-templates)：Chunk是一个Java模板引擎，适用于服务HTML或XML的应用程序。
* [Trimou](https://github.com/trimou/trimou)：Java中的Mustache/Handlebars模板引擎。
* [Rythm](https://github.com/rythmengine/rythmengine)：类似Razor、功能丰富、高性能且易于使用的Java模板引擎。
* [Liqp](https://github.com/bkiers/Liqp)：基于ANTLR的“Liquid模板”解析器和渲染引擎。
* [StringTemplate](https://github.com/antlr/stringtemplate4)：StringTemplate是一个Java模板引擎，用于生成源代码、网页、电子邮件或任何其他格式化文本输出。
* [JTE](https://github.com/casid/jte)：JTE是一个适用于Java和Kotlin的安全且快速的模板。
* [Jamal](https://github.com/verhas/jamal)：嵌入到Maven/JavaDoc中的可扩展模板引擎，支持多种扩展(Groovy、Ruby、JavaScript、JShell、PlantUml)，并支持片段处理。
* [JStachio](https://github.com/jstachio/jstachio)：类型安全的Java Mustache模板引擎。
* [Jtwig](https://github.com/jtwig/jtwig)：模块化、可配置且经过全面测试的模板引擎。
* [JMustache](https://github.com/samskivert/jmustache)：这是Mustache模板语言的Java实现。
* [Enjoy](https://gitee.com/jfinal/enjoy)：Enjoy是基于Java语言的极轻量极模板引擎。
* [Pug4j](https://github.com/neuland/pug4j)：Pug4j的目的是能够在不需要JavaScript环境的情况下处理Java中的pug模板，同时与原始pug语法完全兼容。
* [JMTE](https://code.google.com/archive/p/jmte/)：JMTE旨在填补使用String.format等基本Java类的简单字符串格式化与Velocity或StringTemplate等复杂模板解决方案之间的空白。

## 诊断工具

* [VisualVM](https://github.com/oracle/visualvm)：VisualVM是一个集成了命令行JDK工具和轻量级分析功能的可视化工具，Oracle开源。
* [Arthas](https://github.com/alibaba/arthas)：Arthas是阿里开源的Java诊断工具。
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：JProfiler直观的UI帮助你解决性能瓶颈，确定内存泄漏并了解线程问题。
* [YourKit](https://www.yourkit.com/features/)：YourKit是业界领先的Java剖析工具。
* [AppDynamics](https://www.appdynamics.com/)：AppDynamics是一款APM性能监控软件，可用于监控和管理服务器、虚拟机、数据库等运行情况。
* [Async Profiler](https://github.com/async-profiler/async-profiler)：该项目是一个低开销的Java采样分析器，不会遇到安全点偏差问题。
* [JVM Profiler](https://github.com/uber-common/jvm-profiler)：JVM Profiler提供了一个Java Agent，以分布式方式收集Hadoop/Spark JVM进程的各种指标和堆栈跟踪，例如CPU/内存/IO指标，由Uber开源。
* [TProfiler](https://github.com/alibaba/TProfiler)：TProfiler是一个可以在生产环境长期使用的性能分析工具，由阿里开源。
* [NetBeans Profiler](https://github.com/apache/netbeans/tree/master/profiler)：NetBeans IDE的内置分析器。
* [Greys](https://github.com/oldmanpushcart/greys-anatomy)：国产Java线上问题诊断工具。
* [Bistoury](https://github.com/qunarcorp/bistoury)：Bistoury是去哪儿开源的一个对应用透明、无侵入的Java应用诊断工具，用于提升开发人员的诊断效率和能力。
* [Mission Control](https://github.com/openjdk/jmc)：Mission Control是一个用于Java的开源生产时间分析和诊断工具，由Oracle开源。
* [Honest Profiler](https://github.com/jvm-profiling-tools/honest-profiler)：没有安全点样本偏差的JVM采样分析器。
* [Statsd JVM Profiler](https://github.com/etsy/statsd-jvm-profiler)：Statsd JVM Profiler是一个JVM代理分析器，它将分析数据发送到StatsD。
* [SJK](https://github.com/aragozin/jvm-tools)：SJK是一个用于JVM诊断、故障排除和分析的命令行工具。
* [Jvmtop](https://github.com/patric-r/jvmtop)：Jvmtop是一个轻量级控制台应用程序，用于监视计算机上所有可访问的、正在运行的JVM。
* [Aprof](https://github.com/devexperts/aprof)：Aprof是一个Java内存分配分析器，对分析的应用程序的性能影响非常低。
* [Sniffy](https://github.com/sniffy/sniffy)：Sniffy是一个Java分析器，它直接在浏览器中显示结果。
* [Spf4j](https://github.com/zolyfarkas/spf4j)：Spf4j库是旨在提高Java应用程序的可观察性和性能的组件集合。
* [JavaMelody](https://github.com/javamelody/javamelody)：JavaMelody的目标是监控QA和生产环境中的Java或Java EE应用程序。
* [Automon](https://github.com/stevensouza/automon)：Automon将AOP的强大功能与已使用的监视或日志记录工具相结合，以声明方式监视Java代码、JDK和第三方库。
* [JCoz](https://github.com/Decave/JCoz)：JCoz是世界上第一个针对Java程序的因果分析器。
* [LeakCanary](https://github.com/square/leakcanary)：LeakCanary是一个Android内存泄漏检测库，由Square开源。
* [XRebel](https://www.jrebel.com/products/xrebel)：XRebel是不间断运行在Web应用的交互式分析器。
* [JVM-Mon](https://github.com/ajermakovics/jvm-mon)：基于控制台的JVM监控工具。
* [New Relic](https://newrelic.com/)：New Relic是一个很强大的服务器性能监控工具。
* [SPM](https://sematext.com/spm/)：商业性能监视器，可为JVM应用程序提供分布式事务跟踪。
* [Riemann JVM Profiler](https://github.com/riemann/riemann-jvm-profiler)：Riemann JVM Profiler是一个JVM代理，将功能级探查器遥测数据发送到Riemann服务器以进行分析、可视化和存储。
* [Perf Map Agent](https://github.com/jvm-profiling-tools/perf-map-agent)：一个Java代理，用于生成与Linux perf工具一起使用的方法映射。
* [MAT](https://eclipse.dev/mat/)：Eclipse Memory Analyzer是一款快速且功能丰富的Java堆分析器，可帮助你查找内存泄漏并减少内存消耗。
* [Heapster](https://github.com/mariusae/heapster)：Heapster提供了一个代理库，用于对JVM进程进行堆分析，其输出与Google perftools兼容。
* [PSI Probe](https://github.com/psi-probe/psi-probe)：Apache Tomcat的高级管理器和监视器。
* [Jarboot](https://gitee.com/majz0908/jarboot)：Jarboot是一个Java进程启停、管理、诊断的平台，可以管理、守护、监控及诊断本地和远程的Java进程。
* [Gradle Profiler](https://github.com/gradle/gradle-profiler)：一种自动收集Gradle构建的分析和基准测试信息的工具。
* [Perfino](https://www.ej-technologies.com/products/perfino/overview.html)：Perfino是一款JVM监测工具，有虚拟机管理、商业交易策略、跨虚拟机追踪、遥测数据、末端用户体验检测等实用功能。
* [HeapStats](https://github.com/HeapStats/heapstats)：HeapStats是Java故障排除工具。

## 性能分析

* [BTrace](https://github.com/btraceio/btrace)：BTrace是一个用于Java平台的安全、动态跟踪工具。
* [jHiccup](https://github.com/giltene/jHiccup)：提供平台中JVM暂停的日志和记录，由Azul开源。
* [Kamon](https://github.com/kamon-io/Kamon)：Kamon是一组用于检测在JVM上运行的应用程序的库。
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：用于延迟测量和报告的工具。
* [JOL](https://github.com/openjdk/jol)：JOL是用于分析JVM中对象布局的微型工具箱，Oracle开源。
* [Cornerstone](https://github.com/ctripcorp/vi)：Cornerstone是携程框架部门研发的内部可视化组件VI的开源版本，VI主要是一个应用及应用相关环境的可视化工具，和应用健康状态及启动管理的工具。
* [HdrHistogram](https://github.com/HdrHistogram/HdrHistogram)：HdrHistogram支持在可配置的整数值范围内记录和分析采样数据值计数，并在该范围内具有可配置的值精度。
* [JMX Exporter](https://github.com/prometheus/jmx_exporter)：通过HTTP公开JMX Bean供Prometheus使用的工具。
* [Sidekick](https://github.com/runsidekick/sidekick)：Sidekick是一个开源实时应用程序调试器。
* [MySQL Performance Analyzer](https://github.com/yahoo/mysql_perf_analyzer)：一个用于MySQL性能监控和分析的开源项目，由Yahoo开源。
* [Spring Boot Startup Report](https://github.com/maciejwalkowiak/spring-boot-startup-report)：Spring Boot启动报告库生成交互式Spring Boot应用程序启动报告，让你了解影响应用程序启动时间的因素，并可能有助于优化它。
* [Spring Startup Ananlyzer](https://github.com/linyimin0812/spring-startup-analyzer)：Spring Startup Analyzer生成交互式Spring应用程序启动报告，让你了解影响应用程序启动时间的因素并帮助优化它。
* [Takin](https://github.com/shulieTech/Takin)：Takin是一个基于Java的开源系统，旨在用于全链路，特别是微服务的在线测量或测试环境性能测试，由数列科技开源。
* [PerfJ](https://github.com/coderplay/perfj)：PerfJ是Java程序的Linux Perf的包装器。
* [Hawtio](https://github.com/hawtio/hawtio)：Hawtio是一个轻量级、模块化的Web控制台，用于管理Java应用程序，由IBM开源。
* [Cryostat](https://github.com/cryostatio/cryostat-legacy)：用于从云工作负载中生成、分析和检索JDK Flight Recorder数据。
* [Instrumental](https://www.expectedbehavior.com/products/instrumental/)：实时Java应用程序性能监控，具有免费开发帐户的商业服务。
* [Jolokia](https://github.com/jolokia/jolokia)：Jolokia是一个JMX-HTTP桥接器，提供JSR-160连接器的替代方案。
* [Nudge4j](https://github.com/lorenzoongithub/nudge4j)：通过字节码注入从Java 8浏览器远程开发控制台。
* [Sysmon](https://github.com/palantir/Sysmon)：Sysmon是一个用于JVM的轻量级平台监控工具，由Palantir开源。
* [Microservice Monitoring](https://github.com/xeraa/microservice-monitoring)：监控分布式(微)服务的日志、指标、ping和跟踪。
* [KoTime](https://github.com/huoyo/ko-time)：KoTime是一个轻量级的Spring Boot项目性能分析工具，通过追踪方法调用链路以及对应的运行时长快速定位性能瓶颈。
* [Djigger](https://github.com/exense/djigger)：Djigger是一个用于Java应用程序的生产就绪性能分析和监控解决方案，主要依赖于先进的全天候采样器和仪器代理模式。
* [Eclipse Trace Compass](https://git.eclipse.org/r/plugins/gitiles/tracecompass/org.eclipse.tracecompass)：Eclipse Trace Compass是一个开源应用程序，通过读取和分析系统的日志或跟踪来解决性能和可靠性问题。
* [JRat](https://jrat.sourceforge.net/)：JRat是一个低开销、易于使用的Java平台开源性能分析器。
* [RemoraJ](https://github.com/Nastel/remoraj)：RemoraJ是一个可扩展的Java分析代理，它使用字节码检测以最小的开销拦截Java IPC调用。
* [JETM](https://github.com/frenchc/jetm)：JETM是一个用于编程或声明式性能监控的Java库。
* [DiSL](https://gitlab.ow2.org/disl/disl)：DiSL是一个Java字节码检测框架，旨在观察Java虚拟机中执行的程序。
* [Kieker](https://github.com/kieker-monitoring/kieker)：Kieker提供动态分析功能，即监控和分析软件系统的运行时行为，从而实现应用程序性能监控和架构发现，由斯图加特大学和基尔大学开源。

## GC日志分析

* [GCeasy](https://gceasy.io/)：GCeasy是业界首款机器学习引导的垃圾收集日志分析工具。
* [GCGC](https://github.com/apple/GCGC)：GCGC使用Jupyter Notebook界面来分析GC日志文件，由Apple开源。
* [Sematext Logs](https://sematext.com/logsene/)：Sematext Logs是一种日志集中解决方案，针对各种以日志为中心的用例。
* [GCViewer](https://github.com/chewiebug/GCViewer)：GCViewer是一个小工具，可以可视化Sun/Oracle、IBM、HP和BEA Java虚拟机生成的详细GC输出。
* [GCPlot](https://github.com/GCPlot/gcplot)：GCPlot是一个Java垃圾收集器(GC)日志分析器。
* [GCProf](https://github.com/twitter-archive/jvmgcprof)：GCProf是一个简单的实用程序，用于JVM中的配置文件分配和垃圾收集活动，Twitter开源。
* [GarbageCat](https://github.com/mgm3746/garbagecat)：GarbageCat是一个命令行工具，可解析Java GC日志记录并进行分析，以支持OpenJDK和Oracle JDK的JVM调整和故障排除。
* [Heapothesys](https://github.com/corretto/heapothesys)：Heapothesys是由Amazon Corretto团队开发的JVM垃圾回收工作负载的集合。
* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)：Java HotSpot JIT编译器的日志分析器/可视化器。
* [Eclipse Jifa](https://github.com/eclipse/jifa)：Eclipse Jifa是一款在线分析工具，支持分析Java堆转储、GC日志、线程转储以及JFR文件，由阿里开源。
* [JVM GC Logs Analyzer](https://github.com/krzysztofslusarski/jvm-gc-logs-analyzer)：该项目是一个Java虚拟机和GC日志分析器，它专用于JVM 11及更高版本。
* [GCToolkit](https://github.com/microsoft/gctoolkit)：GCToolkit是一组用于分析HotSpot Java GC日志文件的库，由Microsoft开源。
* [Gchisto](https://github.com/jewes/gchisto)：Hotspot JVM垃圾收集日志可视化工具。

## 堆转储

* [Heap Dump Tool](https://github.com/paypal/heap-dump-tool)：Heap Dump Tool可以捕获，更重要的是，可以清理Java堆转储中的敏感数据，由Paypal开源。
* [JDumpSpider](https://github.com/whwlsfb/JDumpSpider)：HeapDump敏感信息提取工具。
* [Eclipse Memory Analyzer](https://git.eclipse.org/r/plugins/gitiles/mat/org.eclipse.mat)：Eclipse Memory Analyzer提供了一个通用工具包来分析Java堆转储。

## 线程转储

* [FastThread](https://fastthread.io/)：Java线程转储分析器。
* [Java Thread Dump Analyzer](https://github.com/spotify/threaddump-analyzer)：这是一个用Javascript编写的Java线程转储分析器，由Spotify开源。
* [TDA](https://github.com/irockel/tda)：TDA是一个小型Swing GUI，用于分析Java VM生成的线程转储和堆信息。
* [MJProf](https://github.com/AdoptOpenJDK/mjprof)：MJProf是一个单子线程转储分析工具集，它使用一系列简单的可组合构建块(monad)来分析jstack输出。

## 对象测量

* [Jamm](https://github.com/jbellis/jamm)：Jamm提供MemoryMeter，这是一个适用于所有Java版本的Java代理，用于测量实际对象内存使用情况，包括JVM开销。
* [Sizeof](https://github.com/ehcache/sizeof)：该库允许你以字节为单位获取Java对象实例的大小。
* [Sizeofag](https://github.com/fracpete/sizeofag)：Sizeofag是一个Java代理，允许你在运行时确定JVM内Java对象的大小。

## 火焰图

* [JFR-Flame-Graph](https://github.com/chrishantha/jfr-flame-graph)：这是一个简单的应用程序，用于从Java Flight Recorder转储中读取方法分析示例，并将这些堆栈跟踪转换为FlameGraph兼容格式。
* [Flamegrapher](https://github.com/flamegrapher/flamegrapher)：Flamegrapher是Java Flight Recorder的前端，允许你启动、转储、停止、保存以及从浏览器下载JFR记录。
* [JavaFlame](https://github.com/beothorn/javaflame)：Java的简单易用的火焰图，无需服务器或打开连接，只需插入代理并获取结果。

## 脚本

* [Blaze](https://github.com/fizzed/blaze)：用于JVM的快速、灵活、通用脚本和应用程序启动堆栈。
* [Apache Commons BSF](https://github.com/apache/commons-bsf)：BSF是一组Java类，它在Java应用程序中提供脚本语言支持，并通过脚本语言访问Java对象和方法，IBM开源。
* [Nicobar](https://github.com/Netflix/Nicobar)：Nicobar是一个Java动态脚本框架，由基于JBoss Modules的强大模块加载系统驱动，Netflix开源。

## CLI工具

* [Picocli](https://github.com/remkop/picocli)：Picocli是一个现代框架，用于轻松构建功能强大、用户友好、支持GraalVM的命令行应用程序。
* [SDKMAN](https://github.com/sdkman/sdkman-cli)：SDKMAN是一个用于在任何基于Unix的系统上管理多个软件开发套件的并行版本的工具。
* [JBang](https://github.com/jbangdev/jbang)：JBang是一个命令行开发工具，用于以脚本形式运行Java程序。
* [Apache Commons CLI](https://github.com/apache/commons-cli)：Apache Commons CLI提供了一个简单的API，用于呈现、处理和验证命令行界面。
* [Spring Shell](https://github.com/spring-projects/spring-shell)：Spring Shell可帮助你创建基于Spring的、针对CLI空间的生产级应用程序。
* [Babun](https://github.com/babun/babun)：Babun是Windows上类似Linux的控制台。
* [Just](https://github.com/maciejwalkowiak/just)：Just是一个智能零配置命令行接口，用于在开发模式下运行Spring Boot应用程序。
* [Signal CLI](https://github.com/AsamK/signal-cli)：Signal CLI是Signal Messenger的命令行界面，它支持注册、验证、发送和接收消息。
* [Open PDF Sign](https://github.com/open-pdf-sign/open-pdf-sign)：Open PDF Sign CLI应用程序允许从命令行轻松签署PDF文件，签名可以是不可见的(默认)或可见的(可以自定义)。
* [JReleaser](https://github.com/jreleaser/jreleaser)：JReleaser是一个用于Java和非Java项目的自动化发布工具。
* [Crash](https://github.com/crashub/crash)：CRaSH是一个为扩展Java程序和Java虚拟机而设计的shell。
* [MCS](https://github.com/mthmulders/mcs)：MCS是一个小型CLI，用于从命令行查询Maven Central。
* [JD-CLI](https://github.com/intoolswetrust/jd-cli)：JD-CLI是JD-Core项目的简单命令行包装器。
* [Airline](https://github.com/rvesse/airline)：Airline是一个Java库，提供基于注解的框架来解析命令行接口。
* [JLine](https://github.com/jline/jline3)：JLine是一个用于处理控制台输入的Java库。
* [Text-IO](https://github.com/beryx/text-io)：Text-IO是一个用于创建Java控制台应用程序的库，它可用于需要读取用户交互式输入的应用程序。
* [Unix4j](https://github.com/tools4j/unix4j)：Unix4j是Unix命令行工具的Java实现，你可以在Java程序中使用你在Unix中了解的命令。
* [RSC](https://github.com/making/rsc)：RSC是一个RSocket的curl工具。
* [JeeSh](https://github.com/jeeshell/je2sh)：JeeSh代表“JVM可扩展和可嵌入Shell“。
* [Progressbar](https://github.com/ctongfei/progressbar)：Progressbar是一个基于控制台的Java进度条。
* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer)：该库实现了一个基于文本的窗口系统。
* [SQLLine](https://github.com/julianhyde/sqlline)：SQLLine是一个用于通过JDBC向关系型数据库发出SQL的命令行Shell。
* [JMXTerm](https://github.com/jiaqi/jmxterm)：Jmxterm是一个用Java编写的基于开源命令行的交互式JMX客户端。
* [cURL](https://github.com/libetl/curl)：在Java中使用cURL的库。
* [Certificate Ripper](https://github.com/Hakky54/certificate-ripper)：用于提取服务器证书的CLI工具。
* [Barclay](https://github.com/broadinstitute/barclay)：Barclay是一组用于注释、解析、验证和生成命令行选项文档的类，由麻省理工学院和哈佛大学布罗德研究所开源。

## 命令行参数解析

* [JCommander](https://github.com/cbeust/jcommander)：JCommander是一个非常小的Java框架，可以轻松解析命令行参数。
* [Args4j](https://github.com/kohsuke/args4j)：Args4j是一个小型Java类库，可以轻松解析CUI应用程序中的命令行选项/参数。
* [Aesh](https://github.com/aeshell/aesh)：Aesh是一个用于处理控制台输入的Java库。
* [Cloud](https://github.com/Incendo/cloud)：Cloud是一个通用Java命令调度程序和框架，它允许程序员定义命令链，然后从用户提供的字符串输入中解析和调用这些命令链，以执行预定义的操作。
* [JOpt Simple](https://github.com/jopt-simple/jopt-simple)：JOpt Simple是一个用于解析命令行选项的Java库。
* [Argparse4j](https://github.com/argparse4j/argparse4j)：Argparse4j是一个基于Python argparse模块的Java命令行参数解析器库。
* [JaCoLine](https://github.com/chriswhocodes/JaCoLine)：为开发人员提供有用的工具来理解和验证他们的Java命令行选项。
* [Docopt.Java](https://github.com/docopt/docopt.java)：Docopt的Java移植版本，Docopt是一个命令行参数解析库。
* [CLI Parser](https://github.com/spullara/cli-parser)：CLI Parser是一个小型、超级易于使用的库，用于解析各种命令行参数或属性列表。
* [JewelCLI](https://github.com/lexicalscope/jewelcli)：JewelCli使用带注解的接口或类定义来自动解析和呈现命令行参数。
* [CmdOption](https://github.com/ToToTec/CmdOption)：CmdOption是一个简单的注解驱动的命令行解析器工具包，适用于通过注解配置的Java 6+应用程序。
* [JBock](https://github.com/jbock-java/jbock)：JBock是一个命令行解析器。
* [Google Options](https://github.com/pcj/google-options)：这是Bazel项目的命令行参数解析器。
* [RecordArgs](https://github.com/nipafx/record-args)：RecordArgs是一个简单的命令行参数解析器，适用于依赖记录和密封接口的Java应用程序。

## SSH工具

* [Bastillion](https://github.com/bastillion-io/Bastillion)：基于Web的SSH控制台，可集中管理对系统的管理访问。
* [ConnectBot](https://github.com/connectbot/connectbot)：适用于Android的安全Shell客户端，可让你通过加密安全链接连接到远程服务器。
* [Snowflake](https://github.com/subhra74/snowflake)：图形化SFTP客户端和终端仿真器以及有用的实用程序。
* [Apache MINA SSHD](https://github.com/apache/mina-sshd)：用于客户端和服务器端SSH的综合Java库。
* [Pty4J](https://github.com/JetBrains/pty4j)：Java中的伪终端实现。
* [JediTerm](https://github.com/JetBrains/jediterm)：纯Java终端模拟器，适用于SSH和PTY，由JetBrains开源。
* [JSch](https://github.com/mwiede/jsch)：实现SSH功能的Java库，可用于连接SFTP服务器。
* [Jcabi-SSH](https://github.com/jcabi/jcabi-ssh)：Java SSH客户端。
* [JSch](https://github.com/is/jsch)：JSch是SSH2的纯Java实现。
* [Maverick Synergy](https://github.com/sshtools/maverick-synergy)：下一代Java SSH API。
* [SSHJ](https://github.com/hierynomus/sshj)：以编程方式使用SSH、SCP或SFTP。
* [WebSSH](https://github.com/NoCortY/WebSSH)：纯Java实现的WebSSH。
* [T-Shell](https://github.com/TheBlindM/T-Shell)：T-Shell是一个可配置命令提示的终端模拟器和SSH客户端，目前只支持Windows。

## DNS、内网穿透和代理

* [DNS66](https://github.com/julian-klode/dns66)：这是一款适用于Android的基于DNS的主机拦截器。
* [DNSJava](https://github.com/dnsjava/dnsjava)：DNSJava是DNS协议的Java实现。
* [Neo-reGeorg](https://github.com/L-codes/Neo-reGeorg)：reGeorg是新一代内网穿透工具，这是该项目的重构版本。
* [Suo5](https://github.com/zema1/suo5)：Suo5是一个高性能HTTP隧道代理工具，它基于双向的Chunked-Encoding构建。
* [Neutrino-Proxy](https://gitee.com/dromara/neutrino-proxy)：Neutrino-Proxy是一个基于Netty的开源Java内网穿透项目，由dromara社区开源。
* [BrowserUp Proxy](https://github.com/lightbody/browsermob-proxy)：BrowserMob Proxy允许你操作HTTP请求和响应、捕获HTTP内容以及将性能数据导出为HAR文件。
* [DNS Proxy](https://github.com/mageddo/dns-proxy-server)：DPS是一种轻量级最终用户DNS服务器工具，可以轻松地在一个主机名可以根据配置的环境解析为不同IP的系统中进行开发。
* [DNS Proxy](https://github.com/mageddo/dns-proxy-server)：DPS是一种轻量级最终用户DNS服务器工具，可以轻松地在一个主机名可以根据配置的环境解析为不同IP的系统中进行开发。
* [Apache Guacamole](https://github.com/apache/guacamole-client)：Apache Guacamole是一个无客户端远程桌面网关，它支持VNC、RDP和SSH等标准协议。
* [Dns Cache Manipulator](https://github.com/alibaba/java-dns-cache-manipulator)：一个微小的0依赖线程安全Java库，用于以编程方式设置/查看DNS，无需接触host文件，使单元/集成测试可移植，由阿里开源。
* [Denominator](https://github.com/Netflix/denominator)：Denominator是一个用于操作DNS云的可移植Java库，由Netflix开源。
* [Happy DNS](https://github.com/qiniu/happy-dns-android)：用于Android的DNS库，由七牛云开源。
* [DNS-Java](https://github.com/spotify/dns-java)：这个小型DNS包装器库提供了一些与SRV查找相关的有用功能，由Spotify开源。
* [DNS-Cheater](https://gitee.com/matrixy/dns-cheater)：Java实现的DNS服务器，可通过Web管理界面随意设置灵活的解析规则。
* [MagpieBridge](https://gitee.com/jiucheng_org/magpiebridge)：使用Java基于AIO/NIO实现的内网穿透工具。
* [PacketProxy](https://github.com/DeNA/PacketProxy)：PacketProxy是一个开源代理工具，可以拦截和检查TCP/UDP上的任何协议，而不仅限于HTTP/1.x、HTTP2或HTTPS，由DeNA开源。
* [Proxyee](https://github.com/monkeyWie/proxyee)：Proxyee是一个Java编写的HTTP代理服务器库，支持HTTP、HTTPS、WebSocket协议，并支持MITM，可以捕获和篡改HTTP、HTTPS数据包。
* [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG)：OpenIG是一种高性能反向代理服务器，具有专门的会话管理和凭证重播功能。
* [NoPE Proxy](https://github.com/summitt/Burp-Non-HTTP-Extension)：Burp Suite的非HTTP协议扩展代理和DNS。
* [HTTP Proxy Servlet](https://github.com/mitre/HTTP-Proxy-Servlet)：这是Java Servlet形式的HTTP代理。
* [Lanproxy](https://github.com/ffay/lanproxy)：Lanproxy是一个将局域网个人电脑、服务器代理到公网的内网穿透工具，支持TCP流量转发，可支持任何TCP上层协议。
* [S3Proxy](https://github.com/gaul/s3proxy)：S3Proxy实现S3 API和代理请求，支持多种用例。
* [PowerTunnel](https://github.com/krlvm/PowerTunnel)：PowerTunnel是一个构建在LittleProxy之上的可扩展代理服务器。
* [Styx](https://github.com/ExpediaGroup/styx)：Styx是用于JVM的可编程、异步、基于事件的反向代理，由Expedia开源。
* [LittleProxy](https://github.com/adamfisk/LittleProxy)：LittleProxy是一个用Java编写的高性能HTTP代理。
* [Joggle](https://github.com/joggle-cn/joggle)：Joggle是基于Ngrok二开的开源内网穿透项目，多节点、私有部署、云服务。
* [Carapaceproxy](https://github.com/diennea/carapaceproxy)：Carapac是一个分布式Java反向代理。

## Git工具

* [Eclipse JGit](https://eclipse.dev/jgit/)：JGit是一个纯Java类库，实现了Git版本控制系统。
* [GitBucket](https://github.com/gitbucket/gitbucket)：GitBucket是由Scala提供支持的Git平台，具有易于安装、高扩展性和GitHub API兼容性。
* [Gitblit](https://github.com/gitblit-org/gitblit)：Gitblit是一个开源、纯Java Git解决方案，用于管理、查看和服务Git仓库。
* [Gitiles](https://github.com/google/gitiles)：Gitiles是一个简单的Git仓库浏览器，基于JGit构建，由Google开源。
* [Agit](https://github.com/rtyley/agit)：Agit是适用于Android设备的开源Git客户端，允许你查看任何Git仓库的完整历史记录、查看更改并存储以进行完全离线访问。
* [Copybara](https://github.com/google/copybara)：Copybara是Google内部使用的工具，用于在仓库之间转换和移动代码。
* [BFG Repo-Cleaner](https://github.com/rtyley/bfg-repo-cleaner)：BFG是git-filter-branch的更简单、更快速的替代方案，用于清除Git仓库历史记录中的不良数据。
* [Jcabi-Github](https://github.com/jcabi/jcabi-github)：GitHub API的Java面向对象包装器，带有整个GitHub API的假实现。
* [RepoSense](https://github.com/reposense/RepoSense)：RepoSense是Git仓库的贡献分析工具。
* [Git Commit Id Maven Plugin](https://github.com/git-commit-id/git-commit-id-maven-plugin)：可以将构建时Git仓库信息包含到POJO/properties文件中的Maven插件。
* [GitLab4J](https://github.com/gitlab4j/gitlab4j-api)：GitLab4J API提供了功能齐全且易于使用的Java库，用于通过GitLab REST API使用GitLab仓库。
* [GitSolo](https://gitee.com/zhiqim/gitsolo)：GitSolo是知启蒙团队开源的极简Git服务器，纯Java开发。
* [Github Java API](https://github.com/hub4j/github-api)：该库定义了GitHub API的面向对象表示。
* [Github Java Client](https://github.com/spotify/github-java-client)：Spotify开源的Github API的Java客户端。
* [MeGit](https://github.com/eclipsesource/megit)：基于EGit的独立Git GUI。
* [Tea4j](https://codeberg.org/gitnex/tea4j-autodeploy)：适用于Gitea API的Java SDK。
* [Giter8](https://github.com/foundweekends/giter8)：Giter8是一个命令行工具，用于从GitHub或任何其他Git仓库上发布的模板生成文件和目录。
* [GitHub Search](https://github.com/seart-group/ghs)：用于从GitHub爬取、存储和呈现项目以及与其相关的任何统计信息的平台，由瑞士卢加诺的意大利大学软件研究所开源。
* [Coming](https://github.com/SpoonLabs/coming)：Coming是一个用于挖掘Git仓库的工具，由法国国立计算机及自动化研究院、里尔大学开源。
* [SCM Manager](https://github.com/scm-manager/scm-manager)：共享和管理Git、Mercurial和Subversion仓库的最简单方法。
* [Git Changelog Lib](https://github.com/tomasbjerre/git-changelog-lib)：该库可以从Git仓库生成变更日志或发行说明，并且可以根据自上次发布以来的提交格式确定下一个版本。
* [JGitFS](https://github.com/centic9/JGitFS)：JGitFS提供对Git分支/标签/提交的访问，就像它们通过FUSE用户层文件系统是单独的目录一样。

## 函数式编程

* [Vavr](https://github.com/vavr-io/vavr)：Vavr是Java 8的对象功能语言扩展，旨在减少代码行数并提高代码质量。
* [jOOL](https://github.com/jOOQ/jOOL)：jOOL为Java 8 Lambda提供了一些有用的扩展。
* [JavaTuples](https://github.com/javatuples/javatuples)：JavaTuples提供一组允许你使用元组的Java类。
* [Functional Java](https://github.com/functionaljava/functionaljava)：Function Java是一个促进Java函数式编程的开源库。
* [Apache Commons Functor](https://github.com/apache/commons-functor)：Apache Commons Functor库定义了通用函子和函子相关的接口、实现和实用程序。
* [Throwing Function](https://github.com/pivovarit/throwing-function)：支持受检异常的Java 8函数接口+适配器。
* [Cyclops](https://github.com/aol/cyclops)：用于构建现代Java 8应用程序的强大流和函数数据类型。
* [Linq4j](https://github.com/julianhyde/linq4j)：LINQ的Java实现库。
* [Functions](https://github.com/mintern-java/functions)：Functions为每个可能的0到3个参数的函数提供@FunctionalInterface。
* [Functional](https://github.com/io-fairy/functional)：Functional提供更简单、更好用的Java函数式编程接口。
* [NoException](https://github.com/robertvazan/noexception)：用于以简洁、统一且架构干净的方式处理异常的Java库。
* [Totallylazy](https://github.com/bodar/totallylazy)：TotallyLazy补充了标准库，如持久数据结构、解析器组合器等。
* [Retrolambda](https://github.com/luontola/retrolambda)：Retrolambda允许你在Java 7、6或5上运行带有Lambda表达式、方法引用和try-with-resources语句的Java 8代码。
* [Fugue](https://bitbucket.org/atlassian/fugue/src/master/)：Fugue提供补充Google Guava库的函数结构，包括Option、Either、Pair和其他类似有用的类。
* [Lambda](https://github.com/palatable/lambda)：Lambda的诞生是因为希望使用其他语言中惯用的一些相同的规范函数和函数模式，并使它们可用于Java。
* [Underscore Java](https://github.com/javadev/underscore-java)：Underscore.js的Java版本。
* [LINQ](https://github.com/timandy/linq)：LINQ到对象转换的Java库。
* [More Lambdas](https://github.com/PhantomThief/more-lambdas-java)：Java 8的一些有用的Lambda实现。
* [Purefun](https://github.com/tonivade/purefun)：Java函数式编程库。
* [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)：SneakyThrow是一个用于忽略受检异常的Java库。
* [DataEnum](https://github.com/spotify/dataenum)：DataEnum允许你在Java中使用代数数据类型，由Spotify开源。
* [Either.Java](https://github.com/spencerwi/Either.java)：Java的“Either a b”的右偏实现，使用Java 8进行映射/折叠和类型推断。
* [Ambivalence](https://github.com/poetix/ambivalence)：Java 8的Either类型。
* [Pragmatic](https://github.com/siy/pragmatica)：在实践中应用实用函数式Java方法所需的最小Java类集。
* [Typeof](https://github.com/nurkiewicz/typeof)：Java 8中的instanceof运算符和访问者模式替代品。
* [Tail](https://github.com/nrktkt/tail)：使用尾调用优化启用无限递归。
* [HighJ](https://github.com/highj/highj)：HighJ试图克服Java缺乏高阶类型多态性的问题，并将几个众所周知的类型类(包括Applicative、Monad和Foldable)和数据结构从Haskell转换为Java。
* [Vallang](https://github.com/usethesource/vallang)：Vallang是JVM上高度集成且大部分封闭的相互递归基本数据类型的集合。
* [Try](https://github.com/lambdista/try)：Java的Try-Success-Failure Scala API的实现。
* [JPML](https://github.com/klappdev/jpml)：JPML是一个Java模式匹配库。
* [Motif](https://github.com/johnlcox/motif)：Motif在Java 8中提供类似Scala的模式匹配。
* [Procrastination](https://github.com/gdejohn/procrastination)：Procrastination是一个小型、简单的库，将函数式编程的优势引入Java 11。
* [KamilaLisp](https://github.com/kspalaiologos/kamilalisp)：受Haskell和APL等启发的实用、灵活且简洁的Lisp。
* [Fluent](https://github.com/rogerkeays/fluent)：Fluent允许你像调用对象方法一样调用静态Java方法。
* [Unchecked](https://github.com/rogerkeays/unchecked)：Unchecked允许你将Java的受检异常视为非受检异常。
* [Jamaica](https://www.patreon.com/Jamaica440)：Java的一种方言，添加了被Oracle拒绝的流行功能。
* [JKScope](https://github.com/evpl/jkscope)：受Kotlin启发的Java作用域函数。
* [Arend](https://github.com/JetBrains/arend-lib)：Arend是一个基于同伦类型论的定理证明者，由JetBrains开源。

## Stream工具库

* [StreamEx](https://github.com/amaembo/streamex)：StreamEx是对Java Stream API的增强库。
* [Parallel Collector](https://github.com/pivovarit/parallel-collectors)：Parallel Collectors是一个工具包，可使用Stream API简化Java中的并行收集处理。
* [StreamSupport](https://github.com/stefan-zobel/streamsupport)：StreamSupport是适用于Android和Java 6或7用户的Java 8 java.util.function和java.util.stream API的向后移植。
* [Lightweight Stream API](https://github.com/aNNiMON/Lightweight-Stream-API)：Java 8中的Stream API在Java 7及更低版本的迭代器上重写。
* [Kool](https://github.com/davidmoten/kool)：java.util.stream.Stream替代方案(仅同步)，可重用、更快、更多操作符、更易于使用。
* [Streams Utils](https://github.com/JosePaumard/streams-utils)：Streams Utils是一组基于Java 8 Stream编写的操作，它允许一些Java 8中不可用的基本操作。
* [Streams](https://github.com/palantir/streams)：用于处理Java 8 Stream的实用程序，Palantir开源。
* [Protonpack](https://github.com/poetix/protonpack)：Java Stream API的实用工具库。
* [Mug](https://github.com/google/mug)：Google开源的一个小型Java 8工具库，与Guava(BiStream、Substring、MoreStreams、Parallelizer)互补。
* [CombinatoricsLib 3](https://github.com/dpaukov/combinatoricslib3)：适用于Java 8+的组合对象流生成器。
* [Stream Utils](https://github.com/Conductor/stream-utils)：该库包含处理Stream的常用实用程序。

## 字节码操作

* [ASM](https://gitlab.ow2.org/asm/asm)：ASM是一个Java字节码操作框架，它能用来动态生成类或者增强既有类的功能。
* [Byte Buddy](https://github.com/raphw/byte-buddy)：Byte Buddy是一个代码生成和操作库，用于在Java应用程序运行时创建和修改Java类，而无需编译器的帮助。
* [JDK ClassFile](https://openjdk.org/jeps/457)：JDK提供的用于解析、生成和转换Java字节码文件的标准API。
* [Byteman](https://github.com/bytemanproject/byteman)：Byteman是一个可以轻松跟踪、监视和测试Java应用程序和JDK运行时代码的行为的工具，由JBoss社区开源。
* [Apache Commons BCEL](https://github.com/apache/commons-bcel)：Apache Commons BCEL旨在为用户提供一种便捷的方式来分析、创建和操作Java字节码文件。
* [Javassist](https://github.com/jboss-javassist/javassist)：Javassist使Java字节码操作变得简单，它是Java中用于编辑字节码的类库，由东京⼯业⼤学开源。
* [CGLIB](https://github.com/cglib/cglib)：CGLIB是一个功能强大、高性能和高质量的代码生成库。
* [ByteX](https://github.com/bytedance/ByteX)：ByteX是一个基于Android Gradle Transform API和ASM的字节码插件平台，由字节开源。
* [Allocation Instrumenter](https://github.com/google/allocation-instrumenter)：Allocation Instrumenter是使用java.lang.instrument API和ASM编写的Java代理，由Google开源。
* [Soot](https://github.com/soot-oss/soot)：Soot是一个Java优化框架，提供了多种用于分析和转换Java字节码的中间表示形式，由麦吉尔大学开源。
* [Mixin](https://github.com/SpongePowered/Mixin)：Mixin是一个使用ASM的Java特征/混合框架，并通过一组可插入的内置或用户提供的服务挂钩到运行时类加载过程。
* [ByteKit](https://github.com/alibaba/bytekit)：Java字节码工具包，由阿里开发。
* [ProGuard](https://github.com/Guardsquare/proguard-core)：ProGuard是一个免费的库，用于读取、分析、修改和写入Java字节码文件，由GuardSquare开源。
* [DroidAssist](https://github.com/didi/DroidAssist)：DroidAssist是一个轻量级的Android字节码编辑插件，基于Javassist对字节码操作，由滴滴开源。
* [Jitescript](https://github.com/qmx/jitescript)：用于字节码生成的Java API。
* [InjKit](https://github.com/facebookincubator/InjKit)：InjKit是一个基于ASM库的字节码操作框架，由Facebook开发。
* [Perses](https://github.com/nick-kanakis/perses)：Perses允许你在字节码级别动态注入故障/延迟，无需添加任何依赖项或重新启动/部署目标应用程序。
* [Maker](https://github.com/cojen/maker)：Maker库是一个轻量级、功能齐全的低级动态Java字节码生成器，其设计易于使用。
* [Ja-Netfilter](https://gitee.com/ja-netfilter/ja-netfilter)：Java Instrumentation框架。
* [Bytecode](https://github.com/airlift/bytecode)：Bytecode是一个用于生成JVM字节码的高级Java库。
* [AsmTools](https://wiki.openjdk.org/display/CodeTools/asmtools)：AsmTools项目是用于生成正确和不正确的Java class文件的工具。
* [Serp](https://serp.sourceforge.net/)：Serp是一个用于操作Java字节码的开源框架。

## 图像处理

* [Thumbnailator](https://github.com/coobird/thumbnailator)：Thumbnailator是一个Java缩略图生成库。
* [Pngtastic](https://github.com/depsypher/pngtastic)：Pngtastic是一个纯Java PNG图像优化和操作库。
* [Grid](https://github.com/guardian/grid)：Grid是卫报的图像管理系统，它提供了访问组织的媒体的通用且快速的体验，并以经济实惠的方式使用它来生成高质量的内容。
* [Apache Commons Imaging](https://github.com/apache/commons-imaging)：Apache Commons Imaging是一个纯Java图像库。
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)：TwelveMonkeys ImageIO通过javax.imageio.*包的插件为Java平台提供扩展图像文件格式支持。
* [ImgLib2](https://github.com/imglib/imglib2)：ImgLib2是一个通用的多维图像处理库。
* [ImgScalr](https://github.com/rkalla/imgscalr)：ImgScalr是一个简单高效(硬件加速)的图片缩放“最佳实践”类库，纯Java 2D实现。
* [Marvin](https://github.com/gabrielarchanjo/marvin-framework)：Marvin图像处理框架提供实时处理图像和视频的功能。
* [Picasso](https://github.com/square/picasso)：Picasso是一个强大的Android图像下载和缓存库，由Square开源。
* [EasyImage](https://github.com/aviyehuda/EasyImage)：EasyImage可让你执行所有基本图像操作-转换、裁剪、调整大小、旋转、翻转等。
* [JMagick](https://github.com/techblue/jmagick)：JMagick是ImageMagick的开源Java接口。
* [Jrawio](https://github.com/tidalwave-it/jrawio-src)：Java Image I/O API的服务提供者，用来处理数码相机拍摄的RAW格式的图片，包括NEF、CRW、CR2、PEF、SRF、MRW。
* [JJIL](https://github.com/litmanowicziv/jjil)：JJIL是一个Java图像处理库，它包括图像处理架构和60多个用于各种图像处理任务的例程。
* [ICAFE](https://github.com/dragon66/icafe)：用于读取、写入、转换和操作图像和元数据的Java库。
* [JAI ImageIO](https://github.com/jai-imageio/jai-imageio-core)：Java高级图像I/O工具项目。
* [LEADTOOLS](https://www.leadtools.com/sdk/java)：LEADTOOLS是一个Java图像处理库，提供了文档清理、医学图像增强、边缘检测、颜色转换和校正、降噪等功能。
* [SimpleImage](https://github.com/alibaba/simpleimage)：SimpleImage是阿里开源的一个Java图片处理的类库，可以实现图片缩略、水印等处理。
* [Image Comparison](https://github.com/romankh3/image-comparison)：Image Comparison可以比较2个相同大小的图像，并通过绘制矩形直观地显示差异。
* [Scrimage](https://github.com/sksamuel/scrimage)：Scrimage是一个用于图像操作的不可变、函数式、高性能的JVM库。
* [CV4j](https://github.com/imageprocessor/cv4j)：CV4j是用纯Java实现的高质量、实时的图像处理和机器学习库。
* [ImgLib](https://github.com/nackily/imglib)：ImgLib是一个轻量级的Java图像处理库，致力于简化对图像的常见处理。
* [AndroidLibyuvImageUtils](https://github.com/myrao/AndroidLibyuvImageUtils)：Android上的图像处理库。
* [ImageCombiner](https://gitee.com/dromara/image-combiner)：ImageCombiner是一个专门用于Java服务端图片合成的工具，由dromara社区开源。
* [ImageTool](https://gitee.com/xshuai/imagetool)：一个简单的图片处理工具，支持图片压缩、图片水印、图片裁剪、图片旋转、图片格式转换等功能。
* [LIRE](https://github.com/dermotte/LIRE)：LIRE是一个用于基于内容的图像检索的开源库，这意味着你可以使用LIRE来实现搜索看起来相似的图像的应用程序。
* [Fiji](https://github.com/fiji/fiji)：Fiji是一个图像处理包，捆绑了许多有助于科学图像分析的插件，由威斯康星大学麦迪逊分校等机构开源。
* [CognitiveJ](https://github.com/CognitiveJ/cognitivej)：CognitiveJ是一个开源流式Java API，可管理和编排Java应用程序与Microsoft的Cognitive(牛津项目)机器学习和图像处理库之间的交互，并允许你查询和分析图像。
* [JImageHash](https://github.com/KilianB/JImageHash)：JImageHash是一个完全用Java编写的高性能感知图像指纹库。
* [Image Scaling](https://github.com/mortennobel/java-image-scaling)：该库的目的是提供更好的图像缩放选项。
* [Eclipse ImageN](https://github.com/eclipse/imagen)：Eclipse ImageN项目提供了一个可扩展的按需图像处理库，对光栅大小或波段数量没有人为限制。
* [Blurry](https://github.com/wasabeef/Blurry)：Blurry是一个简单的Android模糊库。
* [Cantaloupe](https://github.com/cantaloupe-project/cantaloupe)：Cantaloupe是一个开源动态图像服务器，用于按需生成高分辨率源图像的衍生品。
* [Open Imaging](https://github.com/DhyanB/Open-Imaging)：Open Imaging是用于图像创建和处理的工具和库。
* [ImageIO-Ext](https://github.com/geosolutions-it/imageio-ext)：ImageIO-Ext是一个开源项目，为标准Oracle Java Image I/O项目提供扩展、修复和改进。
* [SCIFIO](https://github.com/scifio/scifio)：SCIFIO是一个可扩展的Java框架，用于读取和写入图像，特别是N维科学图像。
* [Kim](https://github.com/Ashampoo/kim)：Kim是一个用于读取和写入图像元数据的Kotlin多平台库。
* [Java Image Filters](http://www.jhlabs.com/ip/filters/index.html)：Java Image Filters是由Jhlabs开发的一组用来处理Java图像的类库，提供各种常用的图像处理效果，例如反转色、扭曲、水波纹、凹凸、黑白效果等等数十种效果。

## 计算机视觉

* [ImageJ](https://github.com/imagej/ImageJ)：ImageJ是用于处理和分析科学图像的公共领域软件，由美国国家卫生研究院开源。
* [OpenIMAJ](https://github.com/openimaj/openimaj)：OpenIMAJ是一个屡获殊荣的库和工具集合，用于多媒体(图像、文本、视频、音频等)内容分析和内容生成。
* [OpenCV](https://github.com/openpnp/opencv)：OpenCV是一个跨平台的计算机视觉库。
* [JavaCV](https://github.com/bytedeco/javacv)：OpenCV、FFmpeg等的Java接口。
* [ImageJ2](https://github.com/imagej/imagej2)：Image的重写版本，其中心目标是拓宽ImageJ的范式，超越原始ImageJ应用程序的限制，以支持更广泛的多维科学图像数据。
* [BoofCV](https://github.com/lessthanoptimal/BoofCV)：BoofCV是一个开源实时计算机视觉库，功能包括低级图像处理、相机校准、特征检测/跟踪、运动结构、分类和识别。
* [Origami](https://github.com/hellonico/origami)：JVM上图像处理、计算机视觉和神经网络的最低进入门槛。
* [SikuliX](https://github.com/RaiMan/SikuliX1)：SikuliX可以自动化你在运行Windows、Mac或某些Linux/Unix的台式计算机屏幕上看到的任何内容，它使用由OpenCV提供支持的图像识别来识别GUI组件，并可以通过鼠标和键盘操作对其进行操作。
* [PNG Upscale](https://github.com/Araxeus/PNG-Upscale)：使用预训练模型来升级图像的小工具。
* [OpenCV Processing](https://github.com/atduskgreg/opencv-processing)：OpenCV计算机视觉库的处理库。
* [DataGym.ai](https://github.com/datagym-ai/datagym-core)：DataGym.ai是一个基于Web的现代工作台，用于标记图像和视频，它允许你管理项目和数据集、标记数据、控制质量并构建您自己的训练数据管道。

## 光学字符识别

* [C-OCR](https://github.com/ctripcorp/C-OCR)：C-OCR是携程自研的OCR项目，主要包括身份证、护照、火车票、签证等旅游相关证件、材料的识别。
* [CompreFace](https://github.com/exadel-inc/CompreFace)：Exadel CompreFace是一项免费的开源人脸识别服务，无需具备机器学习技能即可轻松集成到任何系统中。
* [Face Recognition](https://github.com/Qualeams/Android-Face-Recognition-with-Deep-Learning-Library)：用于Android和Java的人脸识别库，其中包含多种人脸识别方法，由苏黎世应用科学大学开源。
* [FaceRecognition](https://github.com/wihoho/FaceRecognition)：使用PCA、LDA和LPP实现的人脸识别。
* [SeetafaceJNI](https://gitee.com/cnsugar/seetafaceJNI)：基于中科院Seetaface 2进行封装的Java人脸识别库，支持人脸识别、1:1比对、1:N比对。
* [FaceSearch](https://gitee.com/open-visual/face-search)：本项目是阿里云视觉智能开放平台的人脸搜索M:N的开源替代，项目中使用的模型均为开源模型，项目支持OpenSearch、Milvus和Proxima向量存储库，并具有较高的自定义能力。
* [Red5](https://gitee.com/endlesshh/red5-rtmp-push)：Java版天网人脸识别系统，可以获取视频流进行人脸识别后推送到流媒体服务器实时展示。
* [Qiansou Face SDK](https://gitee.com/qiansou/face-v4-java-sdk)：第5代深度学习人脸识别引擎Java SDK，由千搜科技开源。
* [OCR4all](https://github.com/OCR4all/OCR4all)：OCR4all允许任何给定用户对各种历史印刷品独立执行OCR，并以合理的时间支出获得高质量的结果，由维尔茨堡大学开源。
* [EasyOCR](https://github.com/ushelp/EasyOCR)：EasyOCR是一个使用Java语言实现的OCR识别引擎，能自动完成图片清理、识别CAPTCHA验证码图片内容的一体化工作。
* [MLKit](https://github.com/jenly1314/MLKit)：MLKit是一个能够将谷歌专业的机器学习知识带到应用中的极其简单易用的封装包。
* [Scanner](https://github.com/shouzhong/Scanner)：这里有你常用的二维码/条码识别，还有你可能用到的身份证识别、银行卡识别、车牌识别、图片文字识别、驾驶证识别等。
* [树洞OCR](https://github.com/AnyListen/tools-ocr)：一款跨平台的OCR小工具，调用本地OCR进行识别，无需联网即可使用用到的技术和框架。
* [Tess4j](https://github.com/nguyenq/tess4j)：Tesseract OCR API的Java JNA包装器。

## SVG库

* [JFreeSVG](https://github.com/jfree/jfreesvg)：JFreeSVG是一个用于Java平台的图形库，允许你使用标准Java2D绘图API生成SVG格式的内容。
* [Apache Batik](https://github.com/apache/xmlgraphics-batik)：Apache Batik是一个基于Java的工具包，适用于处理SVG格式的图像各种目的，例如观看、生成或操纵。
* [SVG Salamander](https://github.com/blackears/svgSalamander)：SVG Salamander是一个用于Java的SVG引擎，设计小巧、速度快。
* [VectorGraphics2D](https://github.com/eseifert/vectorgraphics2d)：VectorGraphics2D提供Java Graphics2D接口的实现，并以各种矢量文件格式导出图形。
* [JSVG](https://github.com/weisJ/jsvg)：JSVG是一个使用AWT图形的SVG用户代理。
* [WebVector](https://github.com/radkovo/WebVector)：WebVector是一个HTML到SVG、PDF或PNG转换器。
* [WMF2SVG](https://github.com/hidekatsu-izuno/wmf2svg)：适用于Java的WMF到SVG转换工具和库。
* [Safe SVG](https://github.com/bgalek/safe-svg)：简单且轻量级的库，有助于以安全方式验证SVG文件。

## 验证码

* [AJ-Captcha](https://gitee.com/anji-plus/captcha)：AJ-Captcha行为验证码，包含滑动拼图、文字点选两种方式，UI支持弹出和嵌入两种方式。
* [Captcha-Killer-Modified](https://github.com/f0ng/captcha-killer-modified)：captcha-killer的修改版，支持关键词识别Base64编码的图片，添加免费OCR库，用于验证码爆破，适配新版Burpsuite。
* [EasyCaptcha](https://gitee.com/ele-admin/EasyCaptcha)：Java图形验证码，支持GIF、中文、算术等类型，可用于Java Web、Java SE等项目。
* [Tianai-Captcha](https://gitee.com/tianai/tianai-captcha)：非常好用的开源行为验证码(滑块验证码、点选验证码、行为验证码、旋转验证码， 滑动验证码)。
* [Kaptcha Spring Boot Starter](https://gitee.com/baomidou/kaptcha-spring-boot-starter)：简单快速集成Google Kaptcha验证码的库，由baomidou社区开源。
* [Happy-Captcha](https://gitee.com/ramostear/Happy-Captcha)：Happy Captcha是一款易于使用的Java验证码软件包。
* [Kaptcha](https://github.com/penggle/kaptcha)：Kaptcha是一个可高度配置的实用验证码生成工具。
* [JCaptcha](https://mvnrepository.com/artifact/com.octo.captcha/jcaptcha/1.0)：一个可以生成图片、声音式验证码的Java库。

## 压缩库

* [CompressHelper](https://github.com/nanchen2251/CompressHelper)：文件、图片压缩工具类。
* [AdvancedLuban](https://github.com/shaohui10086/AdvancedLuban)：AdvancedLuban是一个方便简单的Android图像压缩工具库。
* [Zstd](https://github.com/luben/zstd-jni)：Zstd是一种新的无损压缩算法，它可以为你的标准压缩需求提供良好的压缩比和速度。
* [Archive Patcher](https://github.com/google/archive-patcher)：Archive Patcher是一个开源项目，允许对zip存档进行节省空间的修补，由Google开源。
* [Apache Commons Compress](https://github.com/apache/commons-compress)：Apache Commons Compress定义了一个用于处理压缩和存档格式的API。
* [LZF Compressor](https://github.com/ning/compress)：LZF Compressor是一个用于编码和解码LZF格式数据的Java库。
* [JZlib](http://www.jcraft.com/jzlib/)：zlib在纯Java中的重新实现。
* [Snappy Java](https://github.com/xerial/snappy-java)：Snappy的Java移植版，Snappy是Google开发的快速C++压缩器/解压缩器。
* [LZMA](https://github.com/jponge/lzma-java)：该库为在Java平台上运行的应用程序提供LZMA压缩。
* [LZO](https://github.com/shevek/lzo-java)：liblzo2 LZO压缩算法的纯Java实现。
* [LZ4](https://github.com/lz4/lz4-java)：用于Java的LZ4压缩库。
* [Compress](https://gitee.com/yu120/compress)：基于gzip、deflate、lz4、snappy、lzo等算法实现数据压缩，主要用于RPC通讯数据的压缩。
* [Zip4j](https://github.com/srikanth-lingala/zip4j)：Zip4j是最全面的zip文件或流Java库。
* [JavaFastPFOR](https://github.com/lemire/JavaFastPFOR)：Java中的一个简单的整数压缩库。
* [ZT ZIP](https://github.com/zeroturnaround/zt-zip)：Java zip库，构建于java.util.zip包之上。
* [ZIP Forge](https://github.com/helpermethod/zip-forge)：一个小型的、格式化程序友好的Java DSL，用于创建ZIP文件。
* [AirCompressor](https://github.com/airlift/aircompressor)：该库包含用纯Java编写的Zstandard(Zstd)、LZ4、Snappy和LZO的实现，它们通常比原生库的JNI包装器快10-40%。
* [Junrar](https://github.com/junrar/junrar)：纯Java解压缩库。
* [LLJ-ZIP](https://github.com/Col-E/LL-Java-Zip)：LLJ-ZIP是一个用于可查找文件的zip格式读取器，可以容忍前导和尾随垃圾，并容忍针对前导垃圾调整内部偏移。
* [Brotli4j](https://github.com/hyperxpro/Brotli4j)：Brotli4j为Java提供Brotli压缩和解压缩。
* [Bit-Lib4j](https://github.com/devnied/Bit-lib4j)：Bit-Lib4j是一个用于在Java中处理字节或位的库。
* [WebGraph](https://github.com/vigna/webgraph)：WebGraph是一个旨在研究网络图的图压缩框架，它利用现代压缩技术提供了管理非常大的图形的简单方法。
* [Qat-Java](https://github.com/intel/qat-java)：Qat-Java库使用英特尔QuickAssist技术QATzip库提供加速压缩和解压缩。
* [XZ Java](https://github.com/tukaani-project/xz-java)：XZ Java是纯Java中XZ数据压缩的完整实现。

## 爬虫框架

* [Crawler4j](https://github.com/yasserg/crawler4j)：Crawler4j是一个开源的Java网络爬虫库，它提供了一个用于爬虫的简单界面，由加州大学欧文分校开源。
* [Apache Nutch](https://github.com/apache/nutch)：Apache Nutch是一个可扩展的爬虫库。
* [Jsoup](https://github.com/jhy/jsoup)：Java HTML解析器，专为HTML编辑、清理、抓取和XSS安全而构建。
* [StormCrawler](https://github.com/DigitalPebble/storm-crawler)：StormCrawler是一个开源框架，用于在Apache Storm上构建低延迟、可扩展的网络爬虫。
* [Sparkler](https://github.com/USCDataScience/sparkler)：在Spark上运行的类似Nutch的爬虫库，由南加州大学开源。
* [Spider Flow](https://github.com/ssssssss-team/spider-flow)：新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫。
* [WebMagic](https://github.com/code4craft/webmagic)：可扩展的爬虫框架，它涵盖了爬虫的整个生命周期：下载、URL管理、内容提取和持久化。
* [Heritrix](https://github.com/internetarchive/heritrix3)：Heritrix是互联网档案馆的开源、可扩展、网络规模、档案质量的网络爬虫项目。
* [Gecco](https://github.com/xtuhcy/gecco)：Gecco集成了Jsoup、HttpClient、FastJson、Spring、HtmlUnit、Redission框架，让你只需要配置一些JQuery风格的选择器就可以非常快速的编写一个爬虫。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler)：SeimiCrawler是一个敏捷、独立部署、支持分布式的Java爬虫框架。
* [NewPipe Extractor](https://github.com/TeamNewPipe/NewPipeExtractor)：NewPipe Extractor是一个用于从流媒体站点中提取内容的库。
* [Apache ManifoldCF](https://github.com/apache/manifoldcf)：Apache ManifoldCF是一个多仓库爬虫框架，具有多个连接器。
* [FS-Crawler](https://github.com/dadoonet/fscrawler)：该爬虫有助于索引二进制文档，例如PDF、Open Office、MS Office。
* [WebCollector](https://github.com/CrawlScript/WebCollector)：WebCollector是一个基于Java的开源网络爬虫框架，它提供了一些简单的网络爬虫接口。
* [XXL-Crawler](https://github.com/xuxueli/xxl-crawler)：XXL社区开源的Java分布式爬虫框架。
* [Jvppeteer](https://github.com/fanyong920/jvppeteer)：方便使用Java操控Chrome或Chromium的库，Puppeteer的Java实现。
* [NetDiscovery](https://github.com/fengzhizi715/NetDiscovery)：NetDiscovery是一款基于Vert.x、RxJava 2等框架实现的通用爬虫框架/中间件。
* [Spiderman](https://gitee.com/l-weiwei/spiderman)：Spiderman是一个垂直领域的爬虫，可用于抓取特定目标网页的内容，并且解析为所需要的业务数据，整个过程追求无需任何编码就能实现。
* [MongooCrawler](https://gitee.com/coliza/MongooCrawler)：一款低入侵分布式爬虫框架，仅仅依赖少量第三方包，具有多进程多线程，集成反爬、验证码破解方案等特性。
* [XueQiuSuperSpider](https://github.com/decaywood/XueQiuSuperSpider)：雪球超级爬虫是基于雪球网、东方财富和同花顺实现的股票数据爬虫程序。
* [Anthelion](https://github.com/YahooArchive/anthelion)：Anthelion是Apache Nutch的一个插件，用于抓取HTML页面中的语义注释，由Yahoo开源。
* [Crawljax](https://github.com/crawljax/crawljax)：自动爬取和测试现代Web应用程序的工具。
* [ACHE](https://github.com/VIDA-NYU/ache)：ACHE是一个专注的网络爬虫，它收集满足某些特定标准的网页，例如属于给定域或包含用户指定模式的页面。
* [Spiderman2](https://gitee.com/l-weiwei/Spiderman2)：Spiderman的升级版，在性能、架构、易用性上有提升，支持分布式。
* [Jaunt](https://jaunt-api.com/)：Jaunt是一个用于Web抓取、Web自动化和JSON查询的Java库。
* [Jauntium](https://jauntium.com/)：使用Jauntium，Java程序可以在完全支持JavaScript的情况下执行Web抓取和Web自动化。
* [YayCrawler](https://gitee.com/shentong_012/YayCrawler)：分布式爬虫系统，使用简单，高级配置。
* [NewCrawler](https://github.com/speed/newcrawler)：鸟巢采集器是一款Web版的网页数据采集工具，拥有强大的内容采集和数据过滤功能，能将你采集的数据发布到远程服务器。
* [HtmlCleaner](https://htmlcleaner.sourceforge.net/)：HtmlCleaner是一个用Java编写的开源HTML解析器。
* [Crawler-Commons](https://github.com/crawler-commons/crawler-commons)：Crawler-Commons是一组可重用的Java组件，可实现任何网络爬虫的通用功能。
* [Norconex HTTP Collector](https://github.com/Norconex/collector-http)：Norconex HTTP Collector是一个功能齐全的爬虫库，可以操作收集的数据并将其存储到你选择的仓库(例如搜索引擎)中。
* [Phoneutria](https://sourceforge.net/projects/phoneutria/)：可用于对任何Web或企业网站进行爬取和索引，并且可通过XML配置文件进行配置。
* [CrawlerDemon](https://gitee.com/spirit_demon/CrawlerDemon)：基于Akka的高性能分布式爬虫框架。
* [Nokogiri](https://github.com/sparklemotion/nokogiri)：HTML、XML、SAX和Reader解析器，支持XPath和CSS选择器。
* [VSCrawler](https://gitee.com/virjar/vscrawler)：适合抓取封堵的爬虫框架。
* [Crawler](https://github.com/vidageek/crawler)：简单的Java网络爬虫库。
* [Fess Crawler](https://github.com/codelibs/fess-crawler)：Fess Crawler是一个用于爬取网站和文件系统的爬虫库。
* [URL Frontier](https://github.com/crawler-commons/url-frontier)：URL Frontier项目的目标是开发一个爬虫/语言中立的API，用于网络爬虫在与网络前沿通信时执行的操作。

## 批处理框架

* [Spring Batch](https://github.com/spring-projects/spring-batch)：Spring Batch是一个轻量级、全面的批处理框架，旨在支持开发对企业系统日常运营至关重要的健壮批处理应用程序。
* [Spring Cloud Data Flow](https://github.com/spring-cloud/spring-cloud-dataflow)：Spring Cloud Data Flow是一个基于微服务的工具包，用于在Cloud Foundry和Kubernetes中构建流式和批量数据处理管道。
* [Asakusa](https://github.com/asakusafw/asakusafw)：Asakusa是一个面向分布式/并行计算的全栈框架，提供了支持各种分布式/并行计算环境的开发平台和运行时库，例如Hadoop、Spark、用于批处理的M3等。
* [Spring Cloud Task](https://github.com/spring-cloud/spring-cloud-task)：Spring Cloud Task允许用户使用Spring Cloud开发和运行短期微服务，并在本地、云中甚至在Spring Cloud Data Flow上运行它们。
* [JBeret](https://github.com/jberet/jsr352)：JBeret是Jakarta Batch的实现，它还包含在WildFly中，以在Jakarta EE环境中提供便携式批处理支持。
* [Easy Batch](https://github.com/j-easy/easy-batch)：Easy Batch是一个旨在简化Java批处理的框架，它专为简单的单任务ETL作业而设计。

## 注解处理器

* [Lombok](https://github.com/projectlombok/lombok)：Lombok是对Java语法非常有用的补充，消除大量样板代码。
* [Immutables](https://github.com/immutables/immutables)：Immutables是用于创建不可变对象和构建器的注解处理器。
* [Derive4j](https://github.com/derive4j/derive4j)：Derive4j是一个Java 8注解处理器，用于派生代数数据类型构造函数、模式匹配等。
* [AndroidAnnotations](https://github.com/androidannotations/androidannotations)：AndroidAnnotations是一个开源框架，可加速Android开发。
* [DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch)：DeepLinkDispatch提供了一个声明式的、基于注解的API来定义应用程序深度链接，由Airbnb开源。
* [Compile Testing](https://github.com/google/compile-testing)：javac和注解处理器的测试工具，由Google开源。
* [PaperParcel](https://github.com/grandstaish/paperparcel)：PaperParcel可以自动生成Java和Kotlin的Parcelable实现。
* [RecordBuilder](https://github.com/Randgalt/record-builder)：RecordBuilder是用于Java记录的记录构建器。
* [RAVE](https://github.com/uber-archive/rave)：使用Java注解处理器的数据模型验证框架，Uber开源。
* [PojoBuilder](https://github.com/mkarneim/pojobuilder)：PojoBuilder是一个符合Java 6的注解处理器，可为POJO生成流式的构建器类。
* [Annotation Command Framework](https://github.com/aikar/commands)：ACF是一个极其强大的命令框架，它几乎采用了命令处理程序中常见的样板代码的所有概念，并将它们抽象到注解后面。
* [Hugo](https://github.com/JakeWharton/hugo)：调试版本的注解触发方法调用日志记录。
* [Jackdaw](https://github.com/vbauer/jackdaw)：Jackdaw是一个Java注解处理器，可以简化Java/Android开发并防止编写繁琐的代码。
* [ParcelablePlease](https://github.com/sockeqwe/ParcelablePlease)：ParcelablePlease是用于生成Android Parcelable样板代码的注解处理器。
* [BeanKnife](https://github.com/vipcxj/beanknife)：BeanKnife是用于自动生成DTO的注解处理器库。
* [Rest.Vertx](https://github.com/zandero/rest.vertx)：类似JAX-RS的注解处理器，适用于Vert.x Vertical。
* [FreeBuilder](https://github.com/inferred/FreeBuilder)：FreeBuilder可以自动生成Java的Builder模式。
* [Airline](https://github.com/airlift/airline)：Airline是一个基于Java注解的框架，用于解析类似命令行结构的Git。
* [Config-Builder](https://github.com/TNG/config-builder)：Config-Builder使用注解和反射来构建自定义类的配置实例。
* [CallBuilder](https://github.com/google/CallBuilder)：CallBuilder是一个Java代码生成器，可以使创建构建器类变得容易，由Google开源。
* [Better Strings](https://github.com/antkorwin/better-strings)：Better Strings是用于Java字符串插值的插件。
* [Domino-Jackson](https://github.com/DominoKit/domino-jackson)：Domino-Jackson是一个基于注解处理器的JSON映射器。
* [Domino-Rest](https://github.com/DominoKit/domino-rest)：Domino-Rest是一个用于从JaxRs兼容接口生成REST客户端的库。
* [Duzzt](https://github.com/misberner/duzzt)：Duzzt是一个Java注解处理器(库)，可轻松生成Java的嵌入式DSL。
* [Gson Path](https://github.com/LachlanMcKee/gsonpath)：一个注解处理器库，在编译时生成Gson类型适配器，也使用基本的JsonPath功能。
* [Pojo Analyzer](https://github.com/almogtavor/pojo-analyzer)：Pojo Analyzer是一个Java库，旨在为POJO的每个字段生成包含Getter、Setter和字符串名称的List或Map。
* [Sundrio](https://github.com/sundrio/sundrio)：一系列基于APT的代码生成工具，包括高级生成器生成器、DSL生成器、Velocity转换器等。
* [Viper](https://github.com/civitz/viper)：用于通过Java EE的CDI注入配置的生成器和框架。
* [APTK](https://github.com/toolisticon/aptk)：APTK可帮助你以更有效的方式构建注解处理器的工具包。
* [Elementary](https://github.com/Pante/elementary)：Elementary是一套可简化注解处理器的创建和单元测试的库。
* [AutoMatter](https://github.com/danielnorberg/auto-matter)：AutoMatter用于从定义为最小接口的值类型具体化值类和构建器。
* [Jilt](https://github.com/skinny85/jilt)：Jilt是一个Java注解处理器，用于自动生成实现Builder设计模式的类。
* [Deoplice](https://github.com/chriskiehl/Deoplice)：Deoplice是一个Java库，它会自动生成用于转换不可变POJO的API。
* [Kotlin Compile Testing](https://github.com/tschuchortdev/kotlin-compile-testing)：用于测试Kotlin和Java注解处理器、编译器插件和代码生成的库。
* [DistributeMe](https://github.com/anotheria/distributeme)：DistributeMe是一个自动分发Java代码的框架，DistributeMe直接操作你的Java代码，带注解的接口由DistributeMe apt预处理器处理，生成分发相关代码。
* [Cute](https://github.com/toolisticon/cute)：Java编译测试库，允许你测试注解处理器。
* [Coat](https://github.com/poiu-de/coat)：Coat是一个注解处理器，用于生成用于将配置值读取到类型安全对象中的类。

## 字符串工具库

* [Joda-Convert](https://github.com/JodaOrg/joda-convert)：Joda-Convert是一个小型的、高度集中的库，提供对象和字符串之间的往返转换。
* [Java String Similarity](https://github.com/tdebatty/java-string-similarity)：各种字符串相似度和距离算法的实现：Levenshtein、Jaro-winkler、n-Gram、Q-Gram、Jaccard索引、最长公共子序列编辑距离、余弦相似度。
* [Apache Commons Text](https://github.com/apache/commons-text)：Apache Commons Text是一个专注于字符串算法的库。
* [Aho-Corasick](https://github.com/robert-bor/aho-corasick)：用于高效字符串匹配的Aho-Corasick算法的Java实现。
* [Type Parser](https://github.com/drapostolos/type-parser)：解析字符串并将其转换为另一种类型，支持所有适用的Java库类。
* [String Format](https://github.com/JoanZapata/string-format)：当涉及大字符串时，String.format()的替代方案。

## 9-22特性

* [Bach](https://github.com/sormuras/bach)：Bach是一个编排JDK工具以构建模块化Java项目的工具。
* [ModiTect](https://github.com/moditect/moditect)：ModiTect项目旨在提供使用Java模块系统的生产力工具。
* [OpenWebStart](https://github.com/karakun/OpenWebStart)：OpenWebStart提供了一个用户友好的安装程序，可以在更高的Java版本中使用Web Start/JNLP功能。
* [IcedTeaWeb](https://github.com/AdoptOpenJDK/IcedTea-Web)：IcedTeaWeb是JSR-56(Java Web Start)的开源实现。
* [Jabel](https://github.com/bsideup/jabel)：可在Java 8上使用现代Java 9-14语法。
* [Permit Reflection](https://github.com/nqzero/permit-reflect)：用于使用Java 11模块的实用程序。
* [Reified](https://github.com/Auties00/Reified)：用于在Java 11及更高版本中实现具体化。
* [Java REPL](https://github.com/albertlatacz/java-repl)：Java语言的简单REPL，考虑到Java 9已经包含，因此不再维护。
* [InvokeBinder](https://github.com/headius/invokebinder)：用于绑定方法处理的Java DSL向前移植。
* [Virtual Thread Bridge](https://github.com/thunkware/virtual-threads-bridge)：该库允许你在Java 8+中使用Java 21的虚拟线程API。
* [JvmDowngrader](https://github.com/unimined/JvmDowngrader)：将现代Java字节码降级为旧版本。
* [JDK Classfile Preview](https://github.com/dmlloyd/jdk-classfile-preview)：这是JDK 21及更高版本中新ClassFile API到JDK 17的非官方向后移植。

## 消息/事件总线

* [Chronicle Queue](https://github.com/OpenHFT/Chronicle-Queue)：Chronicle Queue是一个适用于高性能应用程序的持久低延迟消息传递框架。
* [Aeron](https://github.com/real-logic/Aeron)：Aeron是一个开源高性能消息传输机制(单向)，支持高效可靠的UDP单播、UDP多播和IPC消息传输。
* [Mappedbus](https://github.com/caplogic/Mappedbus)：Mappedbus是一种用于利用共享内存的Java微服务的低延迟消息总线。
* [eBus](https://sourceforge.net/projects/ebus/)：eBus是一个Java中间件API，支持无代理、基于类型+主题的发布/订阅和请求/回复消息传递，用于应用程序内和应用程序间的对象级通信。
* [EventBus](https://github.com/greenrobot/EventBus)：EventBus是适用于Android和Java的发布/订阅事件总线。
* [MBassador](https://github.com/bennidi/mbassador)：MBassador是一个轻量级、高性能的事件总线，实现了发布订阅模式。
* [Otto](https://github.com/square/otto)：Otto是一种事件总线，旨在解耦应用程序的不同部分，同时仍然允许它们高效通信。
* [Event Ruler](https://github.com/aws/event-ruler)：Event Ruler是一个Java库，允许每秒将数千个事件与任意数量的富有表现力和复杂的规则相匹配，由亚马逊开源。
* [Spring Cloud Bus](https://github.com/spring-cloud/spring-cloud-bus)：Spring Cloud事件总线。
* [LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)：LiveEventBus是一款Android消息总线，基于LiveData，具有生命周期感知能力，支持Sticky、AndroidX、款进程。
* [ZBUS](https://gitee.com/openforce/zbus)：轻量级服务总线，面向高性能、低时延、高可用特性调优，支持RPC，消息队列服务。
* [RxBus](https://github.com/AndroidKnife/RxBus)：RxJava的事件总线。
* [HermesEventBus](https://github.com/Xiaofei-it/HermesEventBus)：HermesEventBus是一个在进程之间使用EventBus的库，在IPC或插件开发中很有用。
* [Apache Synapse](https://github.com/apache/synapse)：Apache Synapse是一种轻量级高性能企业服务总线，由WSO2开源。
* [AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)：适用于Android的轻量级事件总线库，简化了Activity、Fragments、Threads、Services等之间的通信。
* [Nakadi](https://github.com/zalando/nakadi)：Nakadi是一个分布式事件总线代理，它在类似Kafka的队列之上实现了RESTful API抽象，可用于以可靠且高度可用的方式实时发送、接收和分析流数据，由Zalando开源。
* [Low-Level-Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计，包括事件总线。
* [Alpine](https://github.com/ZeroMemes/Alpine)：适用于Java 8+的轻量级事件系统。
* [Flux Capacitor Java Client](https://github.com/flux-capacitor-io/flux-capacitor-client)：该仓库包含Flux Capacitor服务的官方Java客户端。
* [Events4J](https://github.com/PhilippHeuer/events4j)：Java事件调度程序/消费者。
* [DamiBus](https://gitee.com/noear/dami)：DamiBus专为本地多模块之间通讯解耦而设计。
* [Fahrschein](https://github.com/zalando-nakadi/fahrschein)：Nakadi事件总线的Java客户端。
* [IPC EventBus](https://github.com/Terracotta-OSS/ipc-eventbus)：IPC EventBus为JVM内和JVM外通信提供了一个简单的EventBus API。

## 接口文档

* [Swagger Core](https://github.com/swagger-api/swagger-core)：Swagger Core是OpenAPI规范的Java实现。
* [Knife4j](https://gitee.com/xiaoym/knife4j)：Knife4j是一个集Swagger 2和OpenAPI 3为一体的增强解决方案。
* [Springfox](https://github.com/springfox/springfox)：Springfox库旨在自动生成使用Spring系列项目编写的JSON API的机器和人类可读规范。
* [Swagger Parser](https://github.com/swagger-api/swagger-parser)：Swagger Parser可以将JSON或YAML格式的OpenAPI定义解析为Java POJO的swagger-core表示形式，返回任何验证警告/错误。
* [SpringDoc OpenAPI](https://github.com/springdoc/springdoc-openapi)：SpringDoc OpenAPI库有助于使用Spring Boot项目自动生成API文档。
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)：OpenAPI Generator允许在给定OpenAPI规范的情况下自动生成API客户端库(SDK生成)、服务器存根、文档和配置。
* [Spring Boot Starter Swagger](https://github.com/SpringForAll/spring-boot-starter-swagger)：该项目主要利用Spring Boot的自动配置特性来实现快速的将Swagger 2引入Spring Boot应用来生成API文档，简化原生使用Swagger 2的整合代码。
* [JApiDocs](https://github.com/YeDaxia/JApiDocs)：JApiDocs是一个Spring Boot无注解API文档生成器。
* [Swagger2Word](https://github.com/JMCuixy/swagger2word)：一个Swagger API文档转Word文档的工具项目。
* [Spring REST Docs](https://github.com/spring-projects/spring-restdocs)：该项目的主要目标是通过将使用Asciidoctor手写的内容与使用Spring MVC测试框架生成的自动生成的示例相结合，轻松记录RESTful服务。
* [Spring Auto REST Docs](https://github.com/ScaCap/spring-auto-restdocs)：Spring REST Docs的扩展。
* [KaiZen OpenApi Parser](https://github.com/RepreZen/KaiZen-OpenApi-Parser)：KaiZen OpenApi Parser是一个基于Java的OpenAPI 3.0验证解析器，提供高度统一的读/写编程API。
* [OpenAPI-diff](https://github.com/OpenAPITools/openapi-diff)：用于比较两个OpenAPI规范的实用程序。
* [SwaggerSocket](https://github.com/swagger-api/swagger-socket)：SwaggerSocket协议允许在WebSocket协议之上执行任何现有的REST资源。
* [Swagger-Play](https://github.com/swagger-api/swagger-play)：这是一个在Play框架控制器中支持Swagger注解的模块。
* [Swagger Validator Badge](https://github.com/swagger-api/validator-badge)：该项目在网站上显示“valid swagger”徽章，支持Swagger/OpenAPI 2.0和OpenAPI 3.x规范。
* [OpenAPI Style Validator](https://github.com/OpenAPITools/openapi-style-validator)：可定制的样式验证器，可确保你的OpenAPI规范遵循你组织的标准。
* [Smart-Doc](https://gitee.com/TongchengOpenSource/smart-doc)：一款同时支持Java REST API和Dubbo RPC接口文档生成的工具，由同程开源。
* [Doc APIs](https://gitee.com/easy-es/doc-apis)：Doc APIs是一款零侵入接口文档生成工具，由dromara社区开源。
* [Zally](https://github.com/zalando/zally)：Zally是一个简约、易于使用的OpenAPI 2和3 linter。
* [Swagger-Coverage](https://github.com/viclovsky/swagger-coverage)：基于OAS(Swagger) v2和v3生成API测试覆盖率全貌的工具。
* [Swagger Maven Plugin](https://github.com/kongchen/swagger-maven-plugin)：该插件使你的Swagger注解项目能够在Maven构建阶段生成Swagger规范和可定制的模板化静态文档。
* [Swagger2Markup](https://github.com/Swagger2Markup/swagger2markup)：Swagger到AsciiDoc或Markdown转换器，通过将手写文档与自动生成的API文档相结合，简化最新RESTful API文档的生成。
* [AssertJ-Swagger](https://github.com/RobWin/assertj-swagger)：AssertJ-Swagger是一个AssertJ库，它将契约优先的Swagger YAML/JSON文件与代码优先的Swagger JSON输出进行比较。
* [OpenAPI JSON Schema Generator](https://github.com/openapi-json-schema-tools/openapi-json-schema-generator)：OpenAPI JSON Schema Generator允许自动生成API客户端库，重点关注给定OpenAPI文档的JSON模式。
* [OpenAPI v3 Generator Spring Boot](https://github.com/qaware/openapi-generator-for-spring)：该库在运行时自动为Spring Boot应用程序生成OpenApi v3规范。
* [Springdoc-OpenAPI Maven Plugin](https://github.com/springdoc/springdoc-openapi-maven-plugin)：该插件的目的是在运行时生成JSON和YAML OpenAPI描述。
* [xDoc](https://gitee.com/treeleaf/xDoc)：基于Java注释生成接口文档，对代码无侵入，无需注解，纯代码注释。
* [Apigen](https://github.com/apiaddicts/apigen.springboot)：Apigen允许使用OpenAPI文件作为OpenAPI定义和数据库之间的映射工具来生成Spring Boot原型。
* [AutoRest Java](https://github.com/Azure/autorest.java)：用于生成Java代码的AutoRest扩展。
* [Swagger Brake](https://github.com/redskap/swagger-brake)：Swagger-Brake是一个简单的工具，可以验证新版本的API是否会破坏现有版本。

## 技术文档

* [AsciidoctorJ](https://github.com/asciidoctor/asciidoctorj)：AsciidoctorJ是在JVM上运行Asciidoctor的官方库，使用AsciidoctorJ，你可以转换AsciiDoc内容或分析来自Java和其他JVM语言的已解析AsciiDoc文档的结构。
* [DocToolchain](https://github.com/docToolchain/docToolchain)：DocToolchain是一个脚本集合，可以轻松创建和维护强大的技术文档。
* [DITA-OT](https://github.com/dita-ot/dita-ot)：DITA-OT是一个开源发布引擎，用于在Darwin信息类型架构中创作的内容。

## Javadoc

* [Markdown Doclet](https://github.com/Abnaxos/markdown-doclet)：Markdown Doclet允许在Javadoc注释中使用Markdown的Doclet。
* [UMLDoclet](https://github.com/talsma-ict/umldoclet)：UMLDoclet可以在Javadoc中自动生成PlantUML图。
* [Asciidoclet](https://github.com/asciidoctor/asciidoclet)：Asciidoclet是一个基于Asciidoctor的Javadoc Doclet，它允许你使用AsciiDoc语法编写Javadoc。
* [Multiline](https://github.com/benelog/multiline)：使用Javadoc注释在Java中实现多行字符串文本。
* [TherAPI Runtime Javadoc](https://github.com/dnault/therapi-runtime-javadoc)：该库可以在运行时读取Javadoc注释。
* [Javadoc Themer](https://github.com/nisrulz/javadoc-themer)：Javadoc Themer用于为Javadoc着色。
* [Codesnippet Javadoc Doclet](https://github.com/jtulach/codesnippet4javadoc)：Codesnippet Doclet可帮助你在文档中包含真实的代码片段，确保它们始终可编译。
* [Deploy Publish JavaDoc](https://github.com/MathieuSoysal/Javadoc-publisher.yml)：自动从Java项目生成Javadoc并将其发布到GitHub Page。

## 文件解析

#### PDF库

* [Apache PDFBox](https://github.com/apache/pdfbox)：Apache PDFBox库是一个用于处理PDF文档的开源Java工具。
* [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)：这是一个强大的本地托管基于Web的PDF操作工具，允许对PDF文件执行各种操作，例如拆分合并、转换、重新组织、添加图像、旋转、压缩等。
* [iText](https://github.com/itext/itext7)：iText是一个经过考验的高性能库，可创建、改编、检查和维护PDF文档。
* [OpenPDF](https://github.com/LibrePDF/OpenPDF)：OpenPDF是一个用于PDF文件的开源Java库。
* [X-EasyPDF](https://gitee.com/dromara/x-easypdf)：X-EasyPDF是一个基于PDFBox/FOP二次封装的框架，由dromara社区开源。
* [PDFsam](https://github.com/torakiki/pdfsam)：PDFsam是一款用于拆分、合并、混合、旋转PDF文件和提取页面的桌面应用程序。
* [PDF2JSON](https://github.com/modesty/pdf2json)：PDF2JSON是一个PDF文件解析器，可将PDF二进制文件转换为基于文本的JSON。
* [OPENHTMLTOPDF](https://github.com/danfickle/openhtmltopdf)：OPENHTMLTOPDF是一个纯Java库，用于使用CSS 2.1进行布局和格式化，输出为PDF或图像，呈现格式良好的XML/XHTML的合理子集。
* [Tabula](https://github.com/tabulapdf/tabula-java)：Tabula是一个用于从PDF文件中提取表格的库。
* [PDFLayoutTextStripper](https://github.com/JonathanLink/PDFLayoutTextStripper)：将PDF文件转换为文本文件，同时保留原始PDF的布局。
* [Apache FOP](https://xmlgraphics.apache.org/fop/)：Apache FOP是由XSL-FO驱动的打印格式化程序和独立于输出的格式化程序。
* [PdfCompare](https://github.com/red6/pdfcompare)：一个简单的Java库，用于比较两个PDF文件。
* [Boxable](https://github.com/dhorions/boxable)：Boxable是一个可用于轻松在PDF文档中创建表格的库。
* [PDF Studio Viewer](https://www.qoppa.com/pdfstudioviewer/)：PDF Studio Viewer是一款可靠且易于使用的跨平台PDF阅读器。
* [Java WkHtmlToPdf Wrapper](https://github.com/jhonnymertz/java-wkhtmltopdf-wrapper)：WkHtmlToPdf命令行工具的基于Java的包装器。
* [EasyTable](https://github.com/vandeseer/easytable)：这是一个基于Apache PDFBox构建的小项目，允许你以相当简单的方式创建表格。
* [Sejda](https://github.com/torakiki/sejda)：Sejda SDK是一个用Java编写的面向任务的PDF编辑SDK库。
* [Pdf2Dom](https://github.com/radkovo/Pdf2Dom)：Pdf2Dom是一个PDF解析器，可将文档转换为HTML DOM表示形式。
* [TrapRange](https://github.com/thoqbk/traprange)：TrapRange是一种可用于检测表格内容并将其提取到PDF文件中的数据方法。
* [HTMLToPDF](https://github.com/wooio/htmltopdf-java)：该项目基于WkHtmlToPdf，它将HTML文档转换为PDF。
* [PDF-Util](https://github.com/vinsguru/pdf-util)：PDF比较工具库。
* [JSignPdf](https://github.com/intoolswetrust/jsignpdf)：JSignPdf是一个为PDF文档添加数字签名的Java应用程序。
* [Briss](https://github.com/mbaeuerle/Briss-2.0)：Briss是一个用于裁剪PDF文件的小型应用程序。
* [PDFrenderer](https://github.com/katjas/PDFrenderer)：使用Java2D将PDF文档渲染到屏幕的Java库。
* [Staplr](https://github.com/pridiltal/staplr)：该库提供了操作PDF文件的函数。
* [VeraPDF](https://github.com/veraPDF/veraPDF-library)：行业支持的开源PDF/A验证库。
* [PDF Converter](https://github.com/jmrozanec/pdf-converter)：一个Java库，用于将.pdf文件转换为.epub、.txt、.png、.jpg、.zip格式。
* [ICEpdf](https://github.com/pcorless/icepdf)：ICEpdf是一个纯Java PDF文档渲染和查看解决方案。
* [OrsonPDF](https://github.com/jfree/orsonpdf)：OrsonPDF是一个适用于Java平台的PDF生成库，允许你使用标准Java2D绘图API(Graphics2D)创建PDF格式的内容。
* [ComPDFKit](https://github.com/ComPDFKit/compdfkit-api-java)：ComPDFKit提供强大稳定的PDF库和完整的PDF功能来构建PDF查看器和编辑器，允许预览、编辑、注释、签名、加密和解密PDF文件。
* [PDF Test](https://github.com/codeborne/pdf-test)：PDF测试库。

#### Excel库

* [Apache POI](https://github.com/apache/poi)：Apache POI是用于读写Office二进制和OOXML文件格式的Java库。
* [EasyExcel](https://github.com/alibaba/easyexcel)：EasyExcel是一个基于Java的、快速、简洁、解决大文件内存溢出的Excel处理工具，由阿里开源。
* [Docx4j](https://github.com/plutext/docx4j)：Docx4j是一个开源库，用于创建、编辑和保存OpenXML“包”，包括docx、pptx和xslx。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入导出、加密Excel等多项功能的工具包。
* [EasyPOI](https://gitee.com/lemur/easypoi)：EasyPOI是一个POI工具库，提供了Excel的快速导入导出、Excel模板导出、Word模板导出。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：Excel4j是基于POI的Excel和Commons-CSV的CSV操作组件。
* [FastExcel](https://github.com/dhatim/fastexcel)：FastExcel可用于快速生成和读取大Excel文件。
* [JXLS](https://github.com/jxlsteam/jxls)：Jxls是一个小型且易于使用的Java库，用于使用Excel模板文件生成Excel报告。
* [Poiji](https://github.com/ozlerhakan/poiji)：Poiji是一个小型线程安全Java库，提供从Excel工作表到Java类的一种映射方式。
* [AutoPOI](https://github.com/jeecgboot/autopoi)：AutoPOI是Excel和Word的简易工具类。
* [XresLoader](https://github.com/xresloader/xresloader)：XresLoader是一组用于把Excel数据结构化并导出为程序可读的数据文件的导表工具集。
* [AutoExcel](https://github.com/feng-haitao/auto-excel)：AutoExcel是Excel的快速导入和导出工具。
* [Excel Streaming Reader](https://github.com/monitorjbl/excel-streaming-reader)：使用Apache POI的流式Excel读取器的易于使用的实现。
* [ZeroCell](https://github.com/creditdatamw/zerocell)：ZeroCell提供了一个简单的API，用于使用注解将Excel中的数据加载到POJO中，将Excel中的列映射到Java类中的字段。
* [EEC](https://github.com/wangguanquan/eec)：EEC是一款轻量且高效的Excel读写工具，它具有包体小、接入代码量少和运行时消耗资源少等优点。
* [ExcelKit](https://gitee.com/wuwenze/ExcelKit)：简单、好用且轻量级的海量Excel文件导入导出解决方案。
* [ExcelUtil](https://github.com/SargerasWang/ExcelUtil)：用于导入导出Excel的Util包，基于Java的POI。
* [POI-Excel](https://gitee.com/stupid1t/poi-excel)：POI-Excel是一个基于Apache POI的Java工具，旨在简化新手在处理Excel表格时的操作。
* [ExcelCompare](https://github.com/na-ka-na/ExcelCompare)：ExcelCompare是一个命令行工具，用于比较Excel/Open document(ods)电子表格。
* [ZK Spreadsheet](https://github.com/zkoss/zkspreadsheet)：ZK Spreadsheet是一个开源的、可嵌入的、基于Web的在线电子表格，它使用纯Java在浏览器中提供Excel的丰富功能。
* [ToolGood.Algorithm](https://github.com/toolgood/ToolGood.Algorithm)：ToolGood.Algorithm是一个功能强大、轻量级、兼容Excel公式的算法类库，旨在提高开发人员在不同业务场景中的生产力。
* [Keikai](https://github.com/keikai/dev-ref)：Keikai是一个轻松构建电子表格驱动的Web应用程序。
* [Xcelite](https://github.com/eBay/xcelite)：Xcelite是一个类似ORM的Java库，它允许你轻松地将Java Bean序列化到Excel电子表格或从Excel电子表格反序列化Java Bean，由eBay开源。
* [Java Excel API](https://jexcelapi.sourceforge.net/)：Java Excel API是一个成熟的开源Java API，使开发人员能够动态读取、写入和修改Excel电子表格。
* [HY Common Report](https://github.com/HY-Org/hy.common.report)：报表、Excel操作类库。
* [DsExcel Java](https://github.com/GrapeCity/DsExcel-Java)：高速Java Excel电子表格API库。
* [Excel Boot](https://github.com/programmeres/excel-boot)：Excel-Boot是一款Excel导入导出解决方案组成的轻量级开源组件。
* [MemPOI](https://github.com/firegloves/MemPOI)：使用Apache POI简化从数据库导出到Excel文件的库。

#### CSV库

* [Apache Commons CSV](https://github.com/apache/commons-csv)：Apache Commons CSV库提供了一个简单的接口，用于读取和写入各种类型的CSV文件。
* [AdaptiveTableLayout](https://github.com/Cleveroad/AdaptiveTableLayout)：可以读取、编辑和写入CSV文件的库。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入导出、加密Excel等多项功能的工具包，支持CSV文件。
* [Super CSV](https://github.com/super-csv/super-csv)：Super CSV是一个快速、程序员友好的开源库，用于使用Java读写CSV文件。
* [FastCSV](https://github.com/osiegmar/FastCSV)：FastCSV是一个快如闪电、无依赖的Java CSV库，符合RFC标准。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：Excel4j是基于POI的Excel和Commons-CSV的CSV操作组件。
* [Charred](https://github.com/cnuernber/charred)：Charred是针对CSV和JSON格式的高效基于字符的文件解析库。
* [Jackson Dataformats Text](https://github.com/FasterXML/jackson-dataformats-text)：支持通过Jackson抽象读取和写入CSV编码数据。
* [UniVocity Parsers](https://github.com/uniVocity/univocity-parsers)：UniVocity Parsers是速度最快功能最全的CSV开发库之一，同时支持CSV与固定宽度记录的读写。
* [Scala CSV](https://github.com/tototoshi/scala-csv)：用于Scala的CSV读写库。
* [OpenCSV](https://opencsv.sourceforge.net/)：OpenCSV是一个易于使用的Java CSV解析器库。
* [kotlin CSV](https://github.com/doyaaaaaken/kotlin-csv)：纯Kotlin CSV读写库。
* [FlatPack](https://flatpack.sourceforge.net/)：FlatPack是一个Java文件解析器，用于处理CSV、固定长度和自定义分隔符。
* [CSVeed](https://github.com/42BV/CSVeed)：CSVeed是一个Java库，用于CSV文件并将其公开为行或Java Bean。
* [Java CSV](http://sourceforge.net/projects/javacsv)：Java CSV是一个小型快速开源Java库，用于读写CSV和纯分隔文本文件。
* [DeCS](https://github.com/diergo/decs)：DeCS是一个简单的Java 8 CSV解析器和生成器。
* [Daff](https://github.com/paulfitz/daff)：这是一个用于比较表格、生成其差异摘要并将此类摘要用作补丁文件的库。
* [CSV Utils](https://ostermiller.org/utils/CSV.html)：用于读取和写入CSV文本文件的工具类。
* [CsvJdbc](https://github.com/simoc/csvjdbc)：CsvJdbc是一个只读JDBC驱动程序，它使用CSV文件或DBF文件作为数据库表，非常适合编写数据导入程序或分析日志文件。
* [Deephaven CSV](https://github.com/deephaven/deephaven-csv)：Deephaven CSV库是一个高性能、面向列、类型推断的CSV解析器。

#### Word库

* [POI-TL](https://github.com/Sayi/poi-tl)：POI-TL是一个Word模板引擎，可以根据Word模板和数据生成新文档。
* [Documents4j](https://github.com/documents4j/documents4j)：Documents4j是一个用于将文档转换为另一种文档格式的Java库。
* [Docx4j](https://github.com/plutext/docx4j)：Docx4j是一个开源库，用于创建、编辑和保存OpenXML“包”，包括docx、pptx和xslx。
* [Docx Stamper](https://github.com/thombergs/docx-stamper)：Docx Stamper是一个用于docx文档的Java模板引擎。
* [WordGO](https://github.com/qrpcode/wordgo)：让Java生成word文档更容易。
* [Mammoth](https://github.com/mwilliamson/java-mammoth)：Mammoth旨在转换.docx文档，例如由Microsoft Word、Google Docs和LibreOffice创建的文档，并将其转换为HTML。

#### Toml库

* [TomlJ](https://github.com/tomlj/tomlj)：TomlJ是一个完整的TOML解析器。
* [Toml4j](https://github.com/mwanji/toml4j)：Toml4j是一个用于Java的TOML 0.4.0解析器。

#### HTML库

* [JFiveParse](https://github.com/digitalfondue/jfiveparse)：一个符合Java HTML 5的解析器。
* [JsoupXpath](https://github.com/zhegexiaohuozi/JsoupXpath)：纯Java实现的支持W3C Xpath 1.0标准语法的HTML解析器。
* [JTidy](https://github.com/jtidy/jtidy)：JTidy是HTML Tidy的Java端口，一个HTML语法检查器和漂亮的打印机。
* [OWASP Java HTML Sanitizer](https://github.com/owasp/java-html-sanitizer)：一个用Java编写的快速且易于配置的HTML Sanitizer，可让你在Web应用程序中包含第三方编写的HTML，同时防止XSS，由OWASP开源。
* [J2Html](https://github.com/tipsy/j2html)：Java到HTML生成器。
* [Jspoon](https://github.com/DroidsOnRoids/jspoon)：Jspoon是一个Java库，它提供基于CSS选择器将HTML解析为Java对象的功能。
* [NekoHTML](https://github.com/codelibs/nekohtml)：HTML解析器和标签平衡器。
* [Fruit](https://github.com/graycreate/Fruit)：Fruit是一个Java库，可用于将HTML转换为Java对象。
* [CSSBox](https://github.com/radkovo/CSSBox)：CSSBox是一个用纯Java编写的(X)HTML/CSS渲染引擎。
* [HTMLParser](https://github.com/validator/htmlparser)：Validator.nu HTML解析器是HTML解析算法的Java实现。
* [jWebForm](https://github.com/jochen777/jWebForm)：jWebForm可以以简洁的方式定义HTML表单，用请求变量填充它们，验证并从中构建HTML。
* [AttoParser](https://github.com/attoparser/attoparser)：AttoParser是一个用于XML和HTML标签的Java解析器。
* [RenderSnake](https://github.com/emicklei/rendersnake)：RenderSnake是一个Java库，用于创建仅使用Java生成HTML的组件和页面。

#### XML库

* [FlyingSaucer](https://github.com/flyingsaucerproject/flyingsaucer)：一个用于使用CSS 2.1进行布局和格式化、输出到Swing面板、PDF和图像来呈现任意格式良好的XML(或XHTML)的纯Java库。
* [XDocReport](https://github.com/opensagres/xdocreport)：用于将使用Office或OpenOffice、LibreOffice创建的XML文档与Java模型合并，以生成报告并在需要时将其转换为其他格式(PDF、XHTML等)。
* [Dom4j](https://github.com/dom4j/dom4j)：Dom4j是一个处理XML的开源框架，它与XPath集成，完全支持DOM、SAX、JAXP和Java平台(例如Java 2 Collections)。
* [XStream](https://github.com/x-stream/xstream)：用于Java和XML相互转换的库。
* [BaseX](https://github.com/BaseXdb/basex)：一个XML数据库，用来存储紧缩的XML数据，提供了高效的XPath和XQuery的实现。
* [Apache Commons JXPath](https://github.com/apache/commons-jxpath)：XPath 1.0的基于Java的实现，除了XML处理之外，还可以检查/修改Java对象图，甚至混合Java/XML结构。
* [XmlToJson](https://github.com/smart-fun/XmlToJson)：用于将XML转换为JSON以及将JSON转换为XML的Android库。
* [Jackson-XML](https://github.com/FasterXML/jackson-dataformat-xml)：Jackson JSON处理器的扩展，增加了对POJO序列化为XML(以及从XML反序列化)的支持，作为JSON的替代方案。
* [jOOX](https://github.com/jOOQ/jOOX)：org.w3c.dom包的简单包装器，允许在需要DOM但过于冗长的情况下流式地创建和操作XML文档。
* [Apache Commons SCXML](https://github.com/apache/commons-scxml)：状态图XML引擎的Java实现。
* [Apache Commons Digester](https://github.com/apache/commons-digester)：Apache Commons Digester包允许你配置XML到Java对象映射模块，每当识别出嵌套XML元素的特定模式时，该模块就会触发称为规则的某些操作。
* [TikXML](https://github.com/Tickaroo/tikxml)：适用于Java和Android的快速XML解析器。
* [JAXB Tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [JDOM](https://github.com/hunterhacker/jdom)：可以让Java操作XML变得容易。
* [Aalto-XML](https://github.com/FasterXML/aalto-xml)：超高性能的下一代Stax XML处理器实现，实现了基本的Stax API(javax.xml.stream)和Stax2 API扩展(org.codehaus.woodstox.stax2)。
* [Xembly](https://github.com/yegor256/xembly)：一种类似于汇编的命令式编程语言，用于XML文档中的数据操作。
* [GsonXml](https://github.com/stanfy/gson-xml)：一个小型库，允许使用Google Gson库进行XML反序列化。
* [Woodstox](https://github.com/FasterXML/woodstox)：Stax XML API(javax.xml.stream)实现。
* [Apache Santuario](https://github.com/apache/santuario-xml-security-java)：Santuario项目旨在提供XML主要安全标准的实现。
* [Jaxb RI](https://github.com/eclipse-ee4j/jaxb-ri)：JAXB的Eclipse实现。
* [SitemapGen4j](https://github.com/dfabulich/sitemapgen4j)：一个用Java生成XML站点地图的库。
* [Jaxen](https://github.com/jaxen-xpath/jaxen)：用于Java的XPath引擎。
* [Jettison](https://github.com/jettison-json/jettison)：一个用于在StAX的帮助下将XML和JSON相互转换的Java库，它实现XMLStreamWriter和XMLStreamReader并支持Mapped和BadgerFish约定。
* [Simple-XMl](http://simple.sourceforge.net)：一个高性能的Java XML序列化和配置框架。
* [Apache Xalan](https://xalan.apache.org/xalan-j/)：用Java编写的XSLT处理器。
* [Apache Xerces](http://xerces.apache.org/xerces2-j/)：用Java编写的验证XML解析器。
* [Apache XML Graphics](https://xmlgraphics.apache.org/)：从XML到图形输出的转换工具。
* [Apache VXQuery](https://vxquery.apache.org/)：并行XML查询处理器。
* [XSoup](https://github.com/code4craft/xsoup)：基于JSoup的XPath选择器。
* [XMLBeam](https://github.com/SvenEwald/xmlbeam)：通过在代码中使用注解或XPath来处理XML。
* [Jcabi-XML](https://github.com/jcabi/jcabi-xml)：Java XML解析、转换、打印和校验库。
* [Java-XMLBuilder](https://github.com/jmurty/java-xmlbuilder)：XML Builder是一个实用程序，允许使用相对稀疏的Java代码构建简单的XML文档。
* [XMLResolver](https://github.com/xmlresolver/xmlresolver)：XMLResolver项目提供了SAX EntityResolver、Transformer URIResolver和新的NamespaceResolver的高级实现。
* [Xjx](https://github.com/jonas-grgt/xjx)：Java的轻量级XML序列化和反序列化库。
* [Validator](https://github.com/itplr-kosit/validator)：Validator是一个XML验证引擎，用于验证和处理各种格式的XML文件。
* [Json2Xml](https://github.com/lukas-krecan/json2xml)：Json2Xml项目是JSON到XML转换的简单实现。
* [XsdParser](https://github.com/xmlet/XsdParser)：XsdParser是一个将XML定义文件(.xsd)解析为Java对象列表的库。
* [SimpleXml](https://github.com/codemonstur/simplexml)：独立的Java XML解析器和序列化器。

#### YML库

* [EO-YAML](https://github.com/decorators-squad/eo-yaml)：适用于Java 8及更高版本的YAML库。
* [SnakeYAML](https://bitbucket.org/asomov/snakeyaml/overview)：YAML解析库。
* [YamlBeans](https://github.com/EsotericSoftware/yamlbeans)：YamlBeans可以轻松地将Java对象图与YAML进行序列化和反序列化。
* [BoostedYAML](https://github.com/dejvokep/boosted-yaml)：一个简单易用的独立Java库，在处理YAML文档时提供增强的体验。
* [Psych](https://github.com/ruby/psych)：Psych是一个YAML解析器和发射器。
* [JYaml](https://jyaml.sourceforge.net/)：JYaml是一个用于处理Yaml文件格式的Java库。

#### 文件库

* [ini4j](https://github.com/facebookarchive/ini4j)：简单的Java API Windows风格.ini文件处理。
* [Epublib](https://github.com/psiegman/epublib)：用于读写操作epub文件的Java库。
* [EPUBCheck](https://github.com/w3c/epubcheck)：EPUBCheck是EPUB出版物的官方一致性检查器，由W3C开源。
* [LibPST](https://github.com/rjohnsondev/java-libpst)：用Java读取PST文件的库。
* [jOpenDocument](https://www.jopendocument.org/)：用于OASIS Open Document文件操作的纯Java库。
* [CDC](https://gitlab.com/cdc-java/cdc-office)：与Office文档相关的工具类。
* [PPTShow](https://github.com/qrpcode/pptshow)：Java生成PPT文档工具包，支持2010版PPTX新功能。
* [DotEnv](https://github.com/cdimascio/dotenv-java)：Ruby DotEnv项目的无依赖、纯Java端口，用于从.env文件加载环境变量。
* [Dotenv Kotlin](https://github.com/cdimascio/dotenv-kotlin)：用于Java和Kotlin的Ruby dotenv项目的端口。
* [HWPLib](https://github.com/neolord0/hwplib)：Java的HWP库。
* [MPXJ](https://github.com/joniles/mpxj)：该库使您能够从各种文件格式和数据库中读取项目计划(有时称为进度表或项目集)，还可以将该信息写入各种文件格式。
* [JavaDBF](https://github.com/albfernandez/javadbf)：用于读写Xbase(dBase/DBF)文件的Java库。
* [WaveAccess](https://github.com/sintrb/WaveAccess)：波形文件(.wav)的Java读写操作库。
* [JPMML-Evaluator](https://github.com/jpmml/jpmml-evaluator)：用于生成和使用PMML文档的Java库。
* [Org-Java](https://github.com/orgzly/org-java)：Org模式文件Java解析器。
* [Apache Tika](https://github.com/apache/tika)：Apache Tika是一个工具包，用于使用现有解析器库从各种文档中检测和提取元数据和结构化文本内容。
* [JElf](https://github.com/fornwall/jelf)：用于解析ELF文件的Java库。
* [JDBF](https://github.com/iryndin/jdbf)：用于读写DBF文件的Java实用程序。
* [OST2PST](https://github.com/mkorthof/ost2pst)：将Outlook OST文件转换为PST格式。
* [ODF Toolkit](https://github.com/tdf/odftoolkit)：ODF Toolkit是一组Java模块，允许以编程方式创建、扫描和操作ODF文档。
* [OFDRW](https://gitee.com/ofdrw/ofdrw)：开源的OFD处理库，支持文档生成、数字签名、文档保护、文档合并、转换、导出等功能。
* [TIFF Java](https://github.com/ngageoint/tiff-java)：TIFF是一个用于读写标记图像文件格式文件的Java库，由美国国家地理空间情报局开源。
* [AlgART-TIFF](https://github.com/Daniel-Alievsky/algart-tiff)：AlgART-TIFF是一个Java库，提供TIFF文件的完整读/写支持。
* [Java-Date-Front](https://github.com/mokiat/java-data-front)：用于读取Wavefront 3D模型资源(OBJ、MTL)的Java库。
* [jHDF](https://github.com/jamesmudd/jhdf)：该项目是用于访问HDF5文件的纯Java实现。
* [MSLinks](https://github.com/DmitriiShamrikov/mslinks)：用于解析和创建Windows快捷方式文件(.lnk)的库。
* [HCL4j](https://github.com/bertramdev/hcl4j)：HCL4j是JVM上Hashicorp配置语言的解析器。
* [Apron](https://github.com/poiu-de/apron)：Apron是一个用于读写Java .properties文件的小型库。
* [SODS](https://github.com/miachm/SODS)：Java中用于处理ODS文件的简单库。
* [Obj](https://github.com/javagl/Obj)：Obj是一个简单的Wavefront OBJ文件加载器和写入器。
* [JglTF](https://github.com/javagl/JglTF)：与glTF相关的Java库。
* [LASzip4j](https://github.com/mreutegg/laszip4j)：LASzip库的Java移植。
* [Java netCDF](https://github.com/Unidata/netcdf-java)：netCDF Java库提供了科学数据访问的接口，它可用于从各种文件格式读取科学数据，包括netCDF、HDF、GRIB、BUFR等，由美国国家科学基金会开源。
* [DD PList](https://github.com/3breadt/dd-plist)：一个Java库，提供对ASCII、XML和二进制属性列表的支持。
* [Fugerit Doc](https://github.com/fugerit-org/fj-doc)：从XML文档元模型开始生成不同输出格式的文档的框架。
* [Silencio](https://github.com/damianszczepanik/silencio)：Silencio是一个用于转换XML、JSON、YAML、Properties和其他格式的Java库。
* [JODConverter](https://github.com/jodconverter/jodconverter)：JODConverter使用LibreOffice或Apache OpenOffice自动执行文档转换。
* [Meico](https://github.com/cemfi/meico)：Meico是MEI文件的转换器框架，由帕德博恩大学开源。
* [Jcabi Manifests](https://github.com/jcabi/jcabi-manifests)：用于方便读取类路径中可用的MANIFEST.MF文件的Java库。

#### License库

* [TrueLicense](https://github.com/christian-schlichtherle/truelicense)：用于JVM上许可证管理的开源引擎。
* [FOSSLight](https://github.com/fosslight/fosslight)：FOSSLight Hub通过管理开源、许可证和漏洞，帮助你合规、安全地使用开源软件。
* [Licensius](https://github.com/decebals/licensius)：Java微型许可框架。
* [HawkEye](https://github.com/korandoru/hawkeye)：简单的许可证头检查器和格式化程序，有多种分发形式。
* [License3j](https://github.com/verhas/License3j)：License3j是一个免费开源Java库，用于管理需要技术许可证管理强制支持的Java程序中的许可证文件。
* [License](https://github.com/kobeyk/license)：软件许可证书生成+验证。
* [Candlepin](https://github.com/candlepin/candlepin)：Candlepin是一个开源订阅和授权引擎，旨在从供应商和客户的角度管理软件订阅。
* [Solicitor](https://github.com/devonfw/solicitor)：Solicitor是一款能够管理软件依赖项许可证的工具。
* [Smart License](https://gitee.com/smartboot/smart-license)：Smart-License是一款用于安全加固的开源项目，主要服务于非开源产品、商业软件、具备试用功能的付费软件等，为软件提供授权制的使用方式。

#### Markdown库

* [Txtmark](https://github.com/rjeschke/txtmark)：Java Markdown处理器。
* [MarkdownJ](https://github.com/myabc/markdownj)：MarkdownJ是Markdown(John Gruber编写的文本到HTML转换工具)的纯Java端口。
* [Markwon](https://github.com/noties/Markwon)：Android Markdown库。
* [MarkedJ](https://github.com/gitbucket/markedj)：优雅Markdown处理器marked.js的JVM端口。
* [Commonmark-Java](https://github.com/commonmark/commonmark-java)：用于根据CommonMark规范解析和渲染Markdown文本的Java库。
* [Java Markdown Generator](https://github.com/Steppschuh/Java-Markdown-Generator)：用于生成Markdown的Java库。
* [Pegdown](https://github.com/sirthias/pegdown)：基于parboiled PEG解析器的纯Java Markdown处理器，支持多种扩展。
* [Intellij-Markdown](https://github.com/JetBrains/markdown)：用Kotlin编写的多平台Markdown处理器。
* [MarkupDocBuilder](https://github.com/Swagger2Markup/markup-document-builder)：一个支持AsciiDoc、Markdown和Confluence Wiki的标签文档生成器。
* [Nutz](https://github.com/sangupta/nutz)：JVM的Markdown处理器，手工编码的解析器生成AST，并允许轻松添加扩展。
* [MarkdownPapers](https://github.com/lruiz/MarkdownPapers)：用Java实现的Markdown解析器和转换器。
* [Markdown To AsciiDoc](https://github.com/markdown-asciidoc/markdown-to-asciidoc)：一个小型、轻量级的Markdown到AsciiDoc转换器，用Java编写，基于Pegdown。
* [MDTool](https://github.com/cevin15/MDTool)：一个可以将Markdown转换为HTML的工具。
* [KeenWrite](https://gitlab.com/DaveJarvis/KeenWrite)：免费、开源、跨平台桌面Markdown文本编辑器，具有实时预览、字符串插值和数学功能。

## 集群管理

* [Apache Aurora](https://github.com/apache/aurora)：Aurora是一个用于长期运行服务和cron作业的Mesos框架，由Twitter开源。
* [Chronos](https://github.com/mesos/chronos)：Chronos是cron的替代品，它是一个分布式容错调度程序，运行在Apache Mesos之上，可用于作业编排。
* [Singularity](https://github.com/HubSpot/Singularity)：Singularity是一种API和Web应用程序，用于运行和调度Apache Mesos任务，包括长时间运行的进程、计划作业和一次性任务。
* [Haven](https://github.com/codeabovelab/haven-platform)：Haven是一个Docker集群管理系统，用户可以通过用户友好且功能强大的用户界面和命令行工具控制整个平台。
* [Apache Helix](https://github.com/apache/helix)：Helix是一个通用集群管理框架，用于自动管理节点集群上托管的分区、复制和分布式资源，由LinkedIn开源。
* [Apache Airavata](https://airavata.apache.org/)：用于在分布式计算资源(包括本地集群、超级计算机、国家电网、学术和商业云)上执行和管理计算作业和工作流程的软件框架。
* [Fenzo](https://github.com/Netflix/Fenzo)：适用于Mesos框架的调度程序Java库，支持调度优化插件并促进集群自动扩展，由Netflix开源。
* [Apache REEF](https://github.com/apache/reef)：用于为集群资源管理器(例如Hadoop YARN或Mesos)开发可移植应用程序的库。例如，Microsoft Azure流分析是基于REEF和Hadoop构建的。
* [Orion](https://github.com/pinterest/orion)：适用于有状态分布式系统的通用可插拔管理和自动化平台，由Pinterest开源。
* [Apache Myriad](https://github.com/apache/incubator-myriad)：Myriad是一个Mesos框架，旨在扩展Mesos上的YARN集群，由eBay、MapR和Mesosphere开源。
* [Declarative Cluster Management](https://github.com/vmware/declarative-cluster-management)：使用约束编程的声明式集群管理，其中约束使用SQL进行描述，由VMware开源。
* [Marathon](https://github.com/mesosphere/marathon)：Marathon是经过生产验证的用于容器编排的Apache Mesos框架。

## 静态分析

* [Checkstyle](https://github.com/checkstyle/checkstyle)：Checkstyle是一个用于检查Java源代码是否符合代码标准或验证规则集的工具。
* [Infer](https://github.com/facebook/infer)：Infer是一个针对Java、C++、Objective-C和C的静态分析工具，用OCaml编写，由Facebook开源。
* [Error Prone](https://github.com/google/error-prone)：Error Prone是一个Java静态分析工具，可以在编译时捕获常见的编程错误，由Google开源。
* [Error Prone Support](https://github.com/PicnicSupermarket/error-prone-support)：Error Prone Support是Google Error Prone的扩展，它旨在提高代码质量，重点关注可维护性、一致性和避免常见陷阱。
* [PMD](https://github.com/pmd/pmd)：PMD是一个源码分析器，它可以发现常见的编程缺陷，例如未使用的变量、空的catch块、不必要的对象创建等。
* [Qodana](https://www.jetbrains.com/qodana)：Qodana是JetBrains推出的代码质量检测工具。
* [SpotBugs](https://github.com/spotbugs/spotbugs)：SpotBugs是一种静态分析工具，用于查找Java代码中的错误。
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
* [Semgrep](https://github.com/semgrep/semgrep)：Semgrep是一种快速、开源、静态分析工具，用于在编辑期、提交和CI时搜索代码、查找错误并强制执行代码标准。
* [CodeFuse-Query](https://github.com/codefuse-ai/CodeFuse-Query)：CodeFuse-Query是一种强大的静态代码分析平台，适合大规模、复杂的代码库分析场景，由蚂蚁CodeFuse团队开发。
* [Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs)：Find Security Bugs是用于Java Web应用程序安全审核的SpotBugs插件，由OWASP开源。
* [Tai-e](https://github.com/pascal-lab/Tai-e)：Tai-e是一个易于学习/使用的Java静态分析框架，由南京大学开源。
* [NullAway](https://github.com/uber/NullAway)：NullAway是一个帮助消除Java代码中的NPE的工具，由Uber开源。
* [JPlag](https://github.com/jplag/JPlag)：JPlag查找一组多个程序之间的成对相似性，它可以可靠地检测软件开发中的软件抄袭和共谋行为(即使是在混淆的情况下)，由卡尔斯鲁厄理工学院开源。
* [Java CallGraph](https://github.com/gousiosg/java-callgraph)：一套用于在Java中生成静态和动态调用图的程序。
* [Eclipse Steady](https://github.com/eclipse/steady)：Steady分析你的Java应用程序是否存在已知漏洞的开源依赖，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性，由SAP开源。
* [Checker Framework](https://github.com/typetools/checker-framework)：Checker Framework增强了Java的类型系统，这使得软件开发人员能够检测并防止其Java程序中的错误。
* [MobsfScan](https://github.com/MobSF/mobsfscan)：MobsfScan是一个静态分析工具，可以在Android和IOS源代码中查找不安全的代码模式。
* [CK](https://github.com/mauricioaniche/ck)：CK通过静态分析的方式(即不需要编译代码)计算Java项目中的类级和方法级代码度量。
* [LiSA](https://github.com/lisa-analyzer/lisa)：LiSA旨在简化基于抽象解释理论的静态分析器的创建和实现，由威尼斯大学开源。
* [JSpecify](https://github.com/jspecify/jspecify)：JSpecify是一个由明确指定的注解组成的工件，用于支持静态分析检查和JVM语言互操作，由Google领导。
* [FlowDroid](https://github.com/secure-software-engineering/FlowDroid)：FlowDroid静态计算Android应用程序和Java程序中的数据流，由帕德博恩大学开源。
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
* [Astor](https://github.com/SpoonLabs/astor)：Astor是Java的自动软件修复框架，由法国国立计算机及自动化研究院、里尔大学、法兰西理工大学和皇家理工学院共同开发。
* [CodeScene](https://codescene.com/)：CodeScene是CodeScene AB开发的行为代码分析工具。
* [ConQAT](https://teamscale.com/)：ConQAT被设计为用于快速开发和执行软件质量分析的工具包，由慕尼黑工业大学开源。
* [JArchitect](https://www.jarchitect.com/)：JArchitect是用于Java代码的静态分析工具。
* [Snyk Code](https://snyk.io/product/snyk-code/)：使用由开发人员和为开发人员构建的静态应用程序安全测试，确保代码编写时的安全。
* [Squale](https://www.squale.org/)：Squale是一个质量测量平台，可以分析多语言软件应用程序，由雪铁龙、法国航空等组织开源。
* [CFLint](https://github.com/cflint/CFLint)：CFLint是CFML的静态代码分析工具。
* [Codyze](https://github.com/Fraunhofer-AISEC/codyze)：Codyze是一个基于代码属性图的Java、C、C++静态分析器，由弗劳恩霍夫应用与综合安全研究所开源。
* [Sonargraph](https://www.hello2morrow.com/products/sonargraph/explorer)：Sonargraph是一款免费的简单静态分析工具，专注于指标、周期组检测和简单的依赖分析。
* [AppMap](https://github.com/getappmap/appmap-java)：AppMap是一款多功能开源运行时代码分析工具。

## 软件质量

* [Stan4j](http://stan4j.com/)：STAN是领先的基于Eclipse的Java结构分析工具，以自然的方式将开发和质量保证结合在一起。
* [Socomo](https://github.com/gdela/socomo)：Socomo是一个简单的工具，可以可视化源代码的组成，并在你的Java项目开发过程中跟踪组成的更改。
* [Structure101](https://structure101.com/)：Structure101是一个敏捷体系结构开发环境，它允许软件开发团队组织代码库，这是一个收费软件。
* [Lattix](https://www.lattix.com/)：Lattix使你能够快速识别和修复架构问题。
* [JDepend](https://github.com/clarkware/jdepend)：JDepend遍历Java类和源文件目录，并为每个Java包生成设计质量指标。
* [Macker](https://innig.net/macker/)：Macker是一个为Java开发人员提供的构建时架构规则检查实用程序。
* [Architexa](https://www.architexa.com/)：Architexa帮助你理解和记录大型/复杂的代码库。
* [USL4j](https://github.com/codahale/usl4j)：USL4j是Neil Gunther博士的通用可扩展性定律的Java建模器。

## 编码规范

* [Google Java Format](https://github.com/google/google-java-format)：一个重新格式化Java源代码以符合Google Java风格的程序。
* [Spring Java Format](https://github.com/spring-io/spring-javaformat)：一组可应用于任何Java项目以提供一致的Spring风格的插件。
* [Square Java Code Style](https://github.com/square/java-code-styles)：Square的Java和Android项目的IntelliJ IDEA代码样式设置。
* [Spotless](https://github.com/diffplug/spotless)：Spotless是支持多种语言的代码格式化工具。
* [Prettier Java](https://github.com/jhipster/prettier-java)：Prettier是一个代码格式化程序，它通过解析代码并使用自己的规则重新打印代码来强制执行一致的样式。
* [P3C](https://github.com/alibaba/p3c)：阿里巴巴Java编码指南PMD实现和IDE插件。
* [Cornell Java Code Style](https://www.cs.cornell.edu/courses/JavaAndDS/JavaStyle.html)：康奈尔大学Java编程风格指南。
* [Oracle Java Code Convention](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html)：Oracle官方Java代码约定。
* [Android AOSP Style Guide](https://source.android.com/docs/setup/contribute/code-style?hl=zh-cn)：面向贡献者的AOSP Java代码样式指南。
* [Twitter Java Code Style](https://github.com/twitter-archive/commons/blob/master/src/java/com/twitter/common/styleguide.md)：Twitter提供的一组鼓励优秀代码的约定。
* [JavaRanch Style Guide](https://coderanch.com/wiki/718799/Style)：Oracle编码风格的替代方案。
* [GVSU Java Coding Style](https://www.gvsu.edu/computing/java-coding-style-guide-37.htm)：大峡谷州立大学的Java编码规范。
* [CMU Java Code Style](https://www.cs.cmu.edu/~rdriley/121/resources/styleguide/)：CMU 15-121源代码编码标准的完整定义。
* [Chromium Java Style Guide](https://chromium.googlesource.com/chromium/src/+/HEAD/styleguide/java/java.md)：Chromium Java编码风格指南。
* [CIS Java Style Guide]()：CIS 120 Java风格指南。
* [Palantir Java Format](https://github.com/palantir/palantir-java-format)：一个现代、Lambda友好、120个字符的Java格式化器。
* [CodingStyle](https://github.com/uhafner/codingstyle)：慕尼黑应用科技大学使用的Java编码风格和模板项目。

## 依赖分析

* [DependencyCheck](https://github.com/jeremylong/DependencyCheck)：OWASP DependencyCheck是一种软件组合分析实用程序，可检测应用程序依赖中公开披露的漏洞。
* [Depends](https://github.com/multilang-depends/depends)：Depends是一个源代码依赖提取工具，旨在从各种编程语言推断源代码实体(例如文件和方法)之间的语法关系。
* [Jarviz](https://github.com/ExpediaGroup/jarviz)：专为Java应用程序设计的依赖分析和可视化工具，由Expedia开源。
* [Classycle](https://classycle.sourceforge.net/)：Classycle可以分析Java应用程序或库中的静态类和包依赖关系。
* [DepAn](https://github.com/google/depan)：DepAn是一个直接操作工具，用于可视化、分析和重构大型应用程序中的依赖关系，Google开源。
* [JDependency](https://github.com/tcurdt/jdependency)：可帮助分析类级别依赖关系、冲突和缺失的类。
* [Dependency-Track](https://github.com/DependencyTrack/dependency-track)：Dependency-Track是一个智能组件分析平台，允许组织识别并降低软件供应链中的风险，由OWASP开源。
* [Degraph](https://github.com/riy/degraph)：Degraph是一个用于可视化和测试JVM应用程序中的类和包依赖关系的工具。
* [Depgraph Maven Plugin](https://github.com/ferstl/depgraph-maven-plugin)：该Maven插件在单个模块上生成依赖关系图，或者在多模块项目上以聚合形式生成依赖关系图。
* [FASTEN](https://github.com/fasten-project/fasten)：在调用图级别分析包依赖网络的工具。
* [MissingLink](https://github.com/spotify/missinglink)：用于检测Java项目中链接问题的构建时工具，由Spotify开源。
* [JResolve-CLI](https://github.com/bowbahdoe/jresolve-cli)：用于解决JVM依赖的命令行工具。
* [Dependency-Analysis](https://github.com/project-ncl/dependency-analysis)：该项目是一项服务，它提供有关已构建工件的信息并分析项目的依赖关系。
* [OSS Review Toolkit](https://github.com/oss-review-toolkit/ort)：OSS Review Toolkit是一个FOSS策略自动化和编排工具包，你可以使用它以战略、安全和高效的方式管理你的软件依赖项。

## 污点分析

* [Gadget Inspector](https://github.com/JackOfMostTrades/gadgetinspector)：GadgetInspector是一个自动化反序列化链挖掘工具，它通过对字节码形式的Java项目进行污点分析，挖掘可能存在的反序列化链。
* [Phosphor](https://github.com/gmu-swe/phosphor)：Phosphor是一个在JVM和商用JVM上执行动态污点跟踪的系统。

## 审计框架

* [Audit4j](https://github.com/audit4j/audit4j-core)：Audit4j是一个开源审计框架，专门设计用于捕获整个企业应用程序中各个组件生成和触发的审计事件。
* [JaVers](https://github.com/javers/javers)：Java的对象审计和差异框架。

## 代码属性图

* [Code Property Graph](https://github.com/ShiftLeftSecurity/codepropertygraph)：CPG是一种可扩展且与语言无关的程序代码表示形式，专为增量和分布式代码分析而设计。
* [Plume](https://github.com/plume-oss/plume)：Plume是一个代码表示基准测试库，可以选择从Java字节码中提取AST并将结果存储在各种图形数据库中，由Amazon开源。

## API变更管理

* [Revapi](https://github.com/revapi/revapi)：Revapi是一个用于API分析和变更跟踪的工具。
* [Japicmp](https://github.com/siom79/japicmp)：Japicmp是一个比较Jar存档的两个版本的工具。
* [Clirr](https://clirr.sourceforge.net/)：Clirr是一个检查Java库与旧版本的二进制和源代码兼容性的工具。
* [@API Guardian](https://github.com/apiguardian-team/apiguardian)：提供@API注解的库，用于标注框架或应用程序中的公共类型、方法、构造函数和字段，以便发布它们的状态和稳定性级别，并指示它们的使用者如何使用API。

## 源代码浏览器

* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)：Sourcetrail是一个免费的开源跨平台源代码浏览器，可帮助你高效地处理不熟悉的源代码。
* [OpenGrok](https://github.com/oracle/opengrok)：OpenGrok是一个快速且可用的源代码搜索和交叉引用引擎，可以帮助你搜索、交叉引用和导航源树，由Oracle开源。
* [PySonar2](https://github.com/yinwang0/pysonar2)：PySonar2是Python的语义索引器库，专为大型代码库的批处理而设计，生成的索引可用于构建代码浏览器和代码搜索引擎。

## 脚手架

* [Pig](https://gitee.com/log4j/pig)：基于Spring Boot 3.0、Spring Cloud 2022 & Alibaba、SAS OAuth2的微服务RBAC权限管理系统。
* [RuoYi](https://gitee.com/zhijiantianya/ruoyi-vue-pro)：基于Spring Boot + MyBatisPlus + Vue实现的后台管理系统、微信小程序。
* [RuoYi Cloud](https://gitee.com/zhijiantianya/yudao-cloud)：基于Spring Cloud Alibaba、Gateway、Nacos、RocketMQ、Vue实现的后台管理系统+用户小程序。
* [Zheng](https://gitee.com/shuzheng/zheng)：基于Spring + Spring MVC+ Mybatis分布式敏捷开发系统架构，提供整套公共微服务模块。
* [Cloud Platform](https://gitee.com/geek_qi/cloud-platform)：Spring Cloud微服务化RBAC的管理平台。
* [SpringBlade](https://gitee.com/smallc/SpringBlade)：提供基于React和Vue的两个前端框架用于快速搭建企业级的SaaS多租户微服务平台。
* [JeeSpringCloud](https://gitee.com/JeeHuangBingGui/jeeSpringCloud)：基于Spring Boot 2.0的后台权限管理系统界面简洁美观敏捷开发系统架构。
* [Hope Boot](https://github.com/java-aodeng/hope-boot)：一款现代化的脚手架项目。
* [Spring Boot Plus](https://github.com/geekidea/spring-boot-plus)：一个简单易用、高速、高效、功能丰富的开源Spring Boot脚手架。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：一个轻量级的Java快速开发平台。
* [Lenosp](https://gitee.com/zzdevelop/lenosp)：基于Spring Boot的脚手架。
* [SpringCloud](https://github.com/zhoutaoo/SpringCloud)：基于Spring Cloud 2.1的微服务开发脚手架。
* [Liugh](https://github.com/qq53182347/liugh-parent)：实现RESTful快速开发的后端脚手架。
* [ES](https://github.com/zhangkaitao/es)：Java EE项目开发脚手架。
* [BallCat](https://github.com/ballcat-projects/ballcat)：一个快速开发脚手架，快速搭建企业级后台管理系统，并提供多种便捷starter进行功能扩展。
* [Mall-Tiny](https://github.com/macrozheng/mall-tiny)：一款基于Spring Boot + MyBatisPlus的快速开发脚手架。
* [AgileBoot](https://github.com/valarchie/AgileBoot-Back-End)：规范易于二开的全栈基础快速开发脚手架。
* [Spring Boot API Project Seed](https://github.com/lihengming/spring-boot-api-project-seed)：一个基于Spring Boot、MyBatis的种子项目，用于快速构建中小型API、RESTful API项目。
* [Vole](https://github.com/gavenwangcn/vole)：Spring Cloud微服务商业脚手架。
* [SpringBoot_v2](https://gitee.com/bdj/SpringBoot_v2)：Spring Boot项目开发脚手架。
* [Slife](https://gitee.com/jamen/slife)：Spring Boot搭建的一个企业级快速开发脚手架。
* [Vhr](https://gitee.com/lenve/vhr)：Spring Boot + Vue前后端分离的人力资源管理项目，可做常规企业级应用脚手架。
* [Maozi](https://github.com/1095071913/maozi-cloud-parent)：基于Spring Cloud Alibaba、Dubbo二开封装。
* [JBone](https://github.com/417511458/jbone)：JBone基于Spring Cloud框架开发，旨在为中小企业提供稳定的微服务解决方案，为开发人员提供基础开发骨架。
* [HsWeb](https://github.com/hs-web/hsweb-framework)：一个基于Spring Boot开发，使用全响应式编程的企业级后台管理系统基础项目。
* [Source-Vue](https://gitee.com/open-source-byte/source-vue)：基于Spring Boot + Vue前后端分离的Java快速开发框架。
* [Pangu](https://gitee.com/pulanos/pangu-framework)：盘古开发框架是一套轻量稳健的工业级前、中、后台三维多端行业数字化赋能开发基座。
* [Sa-plus](https://gitee.com/click33/sa-plus)：Sa-plus是一个基于Spring Boot的快速开发框架，内置代码生成器。
* [JavaFX-Falsework](https://gitee.com/lwdillon/fx-falsework)：基于JavaFX、Spring Boot开发的客户端与服务端系统开发脚手架。
* [XBoot](https://github.com/Exrick/xboot)：基于Spring Boot 2.x的一站式前后端分离快速开发平台。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：一个轻量级的快速开发平台，能快速开发项目并交付。
* [RenRen Security](https://gitee.com/renrenio/renren-security)：采用Spring Boot、MyBatisPlus、Shiro、Vue 3、ElementPlus等框架开发的一套权限系统。
* [Snowy](https://gitee.com/xiaonuobase/snowy)：国内首个国密前后端分离快速开发平台，集成国密加解密插件，软件层面完全符合等保测评要求，同时实现国产化机型、中间件、数据库适配。
* [FCat](https://gitee.com/softnetcat/FCat)：企业级基础功能框架，软件巢工作室出品。
* [AXBoot Framework](https://github.com/axboot/ax-boot-framework)：使用Java和HTML5的全栈Java Web应用程序框架。
* [Essencium Backend](https://github.com/Frachtwerk/essencium-backend)：Essencium Backend是一个构建在Spring Boot之上的软件库，允许开发人员快速开始新的软件项目。
* [J2EEFAST](https://gitee.com/dromara/J2EEFAST)：J2eeFAST是一个Java EE企业级快速开发平台，致力于打造中小企业最好用的开源免费的后台框架平台，由dromara社区开源。
* [JVS](https://gitee.com/software-minister/jvs)：JVS是企业级应用构建的基础脚手架，提供开箱即用的基础功能集成，其中集成了账户管理、租户管理、用户权限体系、三方登录、环境配置、各种业务日志等功能，还提供了对接低代码、数据中台的能力。
* [VBoot-Java](https://gitee.com/zsvg/vboot-java)：一个开箱即用的快速开发平台Java版。
* [LikeAdmin](https://gitee.com/likeadmin/likeadmin_java)：LikeAdmin是一套快速开发管理后台，使用Spring Boot 2.5、MyBatis Plus、TypeScript、Vue 3、Vite 2、Element Plus 1.2。
* [Hawaii Framework](https://github.com/hawaiifw/hawaii-framework)：Hawaii Framework是一个用于开发基于Spring的应用程序的Java框架，由ilionx开源。
* [Pear Admin Boot](https://gitee.com/pear-admin/Pear-Admin-Boot)：基于Spring Boot生态、权限、工作流的开发平台。
* [金合技术中台](https://gitee.com/ikingtech/iking-platform)：现代化的下一代企业级技术中台，简洁、高效、稳定、开源。
* [MLDong](https://gitee.com/mldong/mldong)：Spring Boot + Vue 3快速开发平台、自研工作流引擎。
* [ContiNew Admin](https://github.com/continew-org/continew-admin)：ContiNew Admin持续迭代优化的前后端分离中后台管理系统框架。

## 低代码

* [JeeSite](https://gitee.com/thinkgem/jeesite4)：JeeSite快速开发平台，不仅仅是一个后台开发框架，它是一个企业级快速开发解决方案。
* [Guns](https://gitee.com/stylefeng/guns)：Guns是一个现代化的Java应用开发框架，基于主流技术Spring Boot 2 + Vue 3。
* [MakuBoot](https://gitee.com/makunet/maku-boot)：MakuBoot是采用Spring Boot 3.1、Spring Security 6.1、MybatisPlus等框架开发的一套Spring Boot低代码开发平台。
* [MateCloud](https://gitee.com/matevip/matecloud)：MateCloud是一款基于Spring Cloud Alibaba的微服务架构，支持多租户的低代码平台。
* [JeecgBoot](https://gitee.com/jeecg/jeecg-boot)：JeecgBoot是一款基于代码生成器的低代码开发平台，前后端分离架构Spring Boot 2.x、Spring Cloud、Ant Design & Vue、MybatisPlus、Shiro、JWT，支持微服务。
* [DiBoot](https://gitee.com/dibo_software/diboot)：为开发人员打造的低代码开发平台。
* [OPSLI](https://github.com/hiparker/opsli-boot)：OPSLI是一款快速的低代码平台，零代码开发，致力于做更简洁的后台管理系统。
* [RESTHeart](https://github.com/SoftInstigate/restheart)：RESTHeart是一个用于构建HTTP微服务的框架，旨在为开发人员提供开箱即用的直观API。
* [Structr](https://github.com/structr/structr)：Structr是一个使用图数据库的集成低代码开发和运行时环境，使用Structr，可以比传统开发方法更快地构建企业Web应用程序。
* [DBAPI](https://gitee.com/freakchicken/db-api)：DBAPI是一个面向数仓开发人员的低代码工具，只需在页面上编写SQL，并配置好参数，就可以自动生成HTTP接口。
* [Citrus](https://github.com/Yiuman/citrus)：低代码快速开发脚手架，灵活、高效。
* [Convertigo](https://github.com/convertigo/convertigo)：Convertigo是一个开源低代码平台，包括用于全栈移动和Web应用程序开发的无代码应用程序构建器。
* [Orienteer](https://github.com/OrienteerBAP/Orienteer)：Orienteer是一个灵活的业务应用平台，它可以让你构建功能齐全的专用企业应用程序，例如CRM、ERP、供应链管理应用程序等。
* [Open Lowcode](https://github.com/openlowcode/Open-Lowcode)：特定企业软件快速开发解决方案。
* [LAMP Cloud](https://github.com/dromara/lamp-cloud)：LAMP Cloud基于JDK 11、Spring Cloud、Spring Boot开发的微服务中后台快速开发平台，专注于多租户(SaaS架构)解决方案，由dromara社区开源。
* [Portofino](https://github.com/ManyDesigns/Portofino)：Portofino是一个低代码工具，用于构建模型驱动的REST API和Web应用程序。
* [Jianmu](https://gitee.com/jianmu-dev/jianmu)：建木是一个面向DevOps领域的极易扩展的开源无代码(图形化)/低代码(GitOps)工具。
* [Skyeye](https://gitee.com/doc_wei01/skyeye)：智能制造一体化，采用Spring Boot + WinUI的低代码平台开发模式。
* [Erupt](https://gitee.com/erupt/erupt)：Erupt是一个低代码全栈类框架，使用Java注解动态生成页面以及增删改查、权限控制等后台功能。
* [ApiBoot](https://gitee.com/minbox-projects/api-boot)：ApiBoot是接口服务的落地解决方案，提供了一系列开箱即用的组件，通过封装来简化主流第三方框架的集成。
* [Appsmith](https://github.com/appsmithorg/appsmith)：用于构建管理面板、内部工具和仪表板的平台。
* [Openkoda](https://github.com/openkoda/openkoda)：即用型开发平台，可加速构建业务应用程序和内部工具的过程。
* [VLife](https://gitee.com/wwwlike/vlife)：VLife是一套采用前后端分离(Java + React)架构的企业级低代码研发平台。
* [Skyve](https://github.com/skyvers/skyve)：Skyve是一个开源低代码平台，可让你访问构建复杂、强大且可扩展的云解决方案所需的所有关键功能。
* [WaveMaker](https://www.wavemaker.com/)：WaveMaker是一个基于Java的低代码开发平台。
* [SmartAdmin](https://gitee.com/lab1024/smart-admin)：SmartAdmin是1024创新实验室使用Spring Boot 2和Vue 3开发出的一套简洁、易用的低代码中后台解决方案。
* [EOVA](https://gitee.com/eova/eova)：国产开源的简单快速开发平台。
* [Dashjoin](https://github.com/dashjoin/platform)：Dashjoin是一个开源和云原生低代码开发和集成平台，可帮助团队更快地交付应用程序。
* [悟空无代码平台](https://github.com/WuKongOpenSource/Wukong_nocode)：通过悟空无代码平台开发工具，企业可自主地快速开发出适合企业需要的信息化系统，开发过程只需要业务人员参与，开发效率极高，维护性很强。
* [EasyTrans](https://gitee.com/dromara/easy_trans)：EasyTrans是一款用于做数据翻译的代码辅助插件，由dromara社区开源。
* [Nop-Entropy](https://gitee.com/canonical-entropy/nop-entropy)：Nop Platform 2.0是基于可逆计算理论实现的采用面向语言编程范式的新一代低代码开发平台。
* [Orange Admin](https://gitee.com/orangeform/orange-admin)：橙单中台化低代码生成器，可完整支持多应用、多租户、多渠道、工作流、在线表单、自定义数据同步、自定义Job、多表关联、跨服务多表关联、框架技术栈自由组合等。
* [Entfrm](https://gitee.com/entfrm/entfrm-boot)：Entfrm是一个以模块化为核心的无代码开发平台。
* [NBCIO](https://gitee.com/nbacheng/nbcio-boot)：亿事达企业管理平台后端代码。
* [Joget](https://github.com/jogetworkflow/jw-community)：Joget是下一代开源无代码/低代码应用程序平台，可实现更快、更简单的数字化转型(DX)。
* [心通达OA](https://gitee.com/xtdoa/xtdoa)：心通达低代码开发平台，由北京高速波软件公司开源。
* [LsFusion](https://github.com/lsfusion/platform)：LsFusion是一个免费的开源平台，用于基于同名第五代编程语言的信息系统开发。
* [JECloud](https://gitee.com/ketr/jecloud)：JECloud平台后端采用微服务架构，前端采用微应用架构，可做到不同服务使用不同数据库独立运行，由北京凯特伟业公司开源。
* [Bsin-PaaS](https://gitee.com/s11e-DAO/bsin-paas-all-in-one)：Bsin-PaaS是一套企业级的低代码、零代码去中心化应用搭建平台，可帮助企业快速搭建基于云原生的有竞争力的业务中台、流程中台、业务前台。
* [PagePlug](https://github.com/cloudtogo/pageplug)：PagePlug是Appsmith的中国化项目，是一个开源、声明式、可视化的前端低代码框架，可以用来制作Web应用、微信小程序。
* [Crabc](https://gitee.com/linebyte/crabc)：Crabc是低代码接口开发平台，企业级API管理系统，深度整合Spring Boot和Mybatis实现动态数据源和动态SQL。
* [iPLAss](https://github.com/dentsusoken/iPLAss)：iPLAss是一个基于Java的低代码开发平台，主要目的是提高企业级系统开发的生产力，由电通综合研究所开源。
* [Dont-code](https://dont-code.net/)：Dont-code是一个低代码/无代码平台，允许用户基于IT开发的完整功能集创建自己的应用程序。
* [Nussknacker](https://github.com/TouK/nussknacker)：Nussknacker是一款低代码可视化工具，可供领域专家构建、运行和监控实时决策算法，而不是在代码中实现它们。

## Data API

* [DB2Rest](https://github.com/kdhrubo/db2rest)：DB2Rest是一个现代低代码REST Data API平台，可以轻松构建智能应用程序。
* [Spring Data REST](https://github.com/spring-projects/spring-data-rest)：该项目的目标是提供一种灵活且可配置的机制来编写可以通过HTTP公开的简单服务。

## POS

* [uniCenta oPOS](https://github.com/poolborges/unicenta-pos)：uniCenta oPOS是一款多语言(17种语言)商业级POS(销售点)软件。
* [MinPOS](https://sourceforge.net/projects/minpos/)：
* [Floreant POS](https://floreant.org/)：Floreant POS是一个用Java编写的独立于平台的销售点应用程序。
* [Openbravo POS](https://github.com/iMartinezMateu/openbravo-pos)：一款全面、灵活且用户友好的基于云的零售POS软件。
* [POSper](https://sourceforge.net/projects/posper/)：POSper是专为小型企业设计的销售点系统。
* [SmartPOS](https://sourceforge.net/projects/smart-pos/)：SmartPOS是一个完整的ERP + POS，它具有ERP的所有功能，但创建了一个直观、敏捷且易于学习的销售点100% Web。

## 业务

* [CDM](https://github.com/microsoft/CDM)：CDM是一种声明性规范，是标准实体的定义，代表业务和生产力应用程序中常用的概念和活动，并且也正在扩展到观察和分析数据，由Microsoft开源。
* [EventHub](https://github.com/Codecademy/EventHub)：EventHub使公司能够进行跨设备事件跟踪。
* [Apache ODE](https://ode.apache.org/)：Apache ODE是一个WS-BPEL兼容的Web服务编配引擎，它可以使开发人员根据以BPEL XML语法写成的过程描述来编配Web服务。
* [Spring Web Flow](https://github.com/spring-projects/spring-webflow)：Spring Web Flow有助于构建需要引导导航的Web应用程序-例如购物车、航班登记、贷款申请等等。
* [EZ-vCard](https://github.com/mangstadt/ez-vcard)：EZ-vCard是一个用于Java的vCard解析器库。
* [SCMR1](https://github.com/doublechaintech/scm-biz-suite)：供应链中台系统基础版，集成零售管理、电子商务、供应链管理、财务管理、订单管理等，由成都双链科技开源。
* [OpenXava](https://sourceforge.net/projects/openxava/)：用于快速将业务应用程序推向市场的Java平台。
* [eXo Platform](https://github.com/exoplatform/platform-public-distributions)：eXo Platform是面向成长型团队和企业的开源数字工作场所解决方案。
* [Lattice](https://github.com/hiforce/lattice)：Lattice是一个强大、轻量级的业务扩展调用框架。

## 电商

* [Broadleaf Commerce](https://github.com/BroadleafCommerce/BroadleafCommerce)：Broadleaf Commerce CE是一个完全用Java编写并利用Spring框架的电子商务框架。
* [SAP Commerce](https://www.sap.com/products/crm/commerce-cloud.html)：SAP Commerce是一个使用Java、基于Spring MVC框架的电子商务平台。
* [Q-Calculator](https://github.com/CyrilFeng/Q-calculator)：Stateless高性能优惠叠加计算框架。
* [Shopizer](https://github.com/shopizer-ecommerce/shopizer)：Java开源电子商务软件。
* [Axelor Open Platform](https://github.com/axelor/axelor-open-suite)：Axelor开放平台是一个开源Java框架，用于创建现代商业应用程序。
* [Scipio ERP](https://github.com/ilscipio/scipio-erp)：Scipio ERP是一个基于Java 11+和内置Tomcat应用服务器的开源业务应用程序工具包。
* [YesCart](https://github.com/inspire-software/yes-cart)：YesCart是一个使用Java技术构建的电子商务平台。
* [NFE](https://github.com/wmixvideo/nfe)：Java中的电子发票。
* [Qalingo](https://github.com/qalingo/qalingo-engine)：Qalingo是一个为B2C和B2B业务开发的开源Java电子商务平台。
* [Mayocat](https://github.com/jvelo/mayocat-shop)：Mayocat是一个Java开源市场和电子商务平台。
* [Kadro Merchant](https://kadro.com/ecommerce/)：Kadro Merchant是一个基于Java的全功能电子商务框架，专为电子商务业务生命周期的任何阶段而设计。
* [SoftSlate](https://www.softslate.com/)：SoftSlate是一个开源Java购物车，提供全套电子商务功能以及高性能。
* [Avetti Commerce](https://avetticommerce.com/)：Avetti Commerce是一个可靠的基于Java的电子商务解决方案，它具有针对B2C和B2B业务以及多商店电子商务的一系列深入功能。
* [Elastic Path](https://www.elasticpath.com/products/architecture/technologies/java-ecommerce)：基于Spring、Apache OpenJPA、Eclipse、Apache Solr、Apache Velocity、Groovy、jQuery等开源技术的Java电子商务平台。
* [JadaSite](https://jadasite.com/)：JadaSite是一个基于Java、开源、易于使用且功能丰富的内容管理和电子商务系统。
* [KonaKart](https://www.konakart.com/)：KonaKart是一个针对大中型在线零售商的Java电子商务系统。
* [ShoppingCart](https://github.com/ikismail/ShoppingCart)：基于Spring MVC和多模块开发的一个端到端电子商务Web应用程序。
* [POP Commerce](https://github.com/moqui/PopCommerce)：POP Commerce是一个简单的电子商务应用程序和一个管理应用程序。

## 支付

* [WxJava](https://gitee.com/binary/weixin-java-tools)：微信开发Java SDK，支持微信支付、开放平台、公众号、企业号/企业微信、小程序等的后端开发。
* [Jeepay](https://gitee.com/jeequan/jeepay)：Jeepay是一套适合互联网企业使用的开源支付系统，支持多渠道服务商和普通商户模式。
* [IJPay](https://gitee.com/javen205/IJPay)：封装了微信支付、QQ支付、支付宝支付、京东支付、银联支付、PayPal支付等常用的支付方式以及各种常用的接口。
* [Roncoo-Pay](https://gitee.com/roncoocom/roncoo-pay)：龙果支付系统是国内首款开源的互联网支付系统，拥有独立的账户体系、用户体系、支付接入体系、支付交易体系、对账清结算体系。
* [Pay-Java](https://gitee.com/egzosn/pay-java-parent)：全能第三方支付对接Java开发工具包。
* [Pay-SDK](https://github.com/Pay-Group/best-pay-sdk)：支付宝、微信支付SDK。
* [PayPal](https://github.com/paypal/PayPal-Android-SDK)：接入PayPal支付的Android SDK。
* [KillBill](https://github.com/killbill/killbill)：KillBill在过去10年中一直是领先的开源订阅计费和支付平台，该平台的存在是为了帮助扩展计费和支付基础设施并发展业务。
* [微信支付Java SDK](https://github.com/YClimb/wxpay-sdk)：最新最全微信支付集成SDK，一行代码调用微信支付，包含基础支付功能。
* [微信支付API v3](https://github.com/wechatpay-apiv3/wechatpay-java)：微信支付API v3的官方Java SDK。
* [Paypal](https://github.com/paypal/Checkout-Java-SDK)：PayPal结账Java SDK。
* [Alipay](https://github.com/alipay/alipay-easysdk)：支付宝开放平台服务端SDK。
* [YunGouOS-PAY-SDK](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK)：微信/支付宝官方服务商接口(支持个人、个体户、企业)签约开通。
* [Payment-Spring-Boot](https://gitee.com/dromara/payment-spring-boot)：Java微信支付V3支付Spring Boot Starter，支持微信优惠券，代金券、商家转账到零钱、公众号支付、微信小程序支付、电商收付通等全部微信支付功能API，由dromara社区开源。
* [EMV-NFC-Paycard-Enrollment](https://github.com/devnied/EMV-NFC-Paycard-Enrollment)：用于从NFC EMV信用卡读取和提取公共数据的Java库。
* [Alipay Java SDK](https://github.com/alipay/alipay-sdk-java-all)：支付宝开放平台Java SDK。
* [XPay](https://github.com/Exrick/xpay)：XPay个人收款支付系统。
* [J2PAY](https://github.com/tranxactive/J2PAY)：J2Pay是一个用于Java的开源多网关支付处理库。
* [Braintree Java](https://github.com/braintree/braintree_java)：Braintree Java库提供对Braintree网关的集成访问。
* [Adyen Java API](https://github.com/Adyen/adyen-java-api-library)：官方支持使用Adyen API的Java库。
* [WXPay-SDK](https://github.com/jkrains/wxpay-sdk-v3)：实现了微信支付V3版本的SDK，包括命令式和异步编程SDK。
* [Easy-Pay](https://github.com/easy-pay/easy-pay)：一行代码解决支付宝和微信的二维码生成，支付回调、退款、H5支付等功能。
* [Wallee Java SDK](https://github.com/wallee-payment/java-sdk)：Wallee Java库封装了wallee API，该库方便你与各种服务(例如交易、帐户和订阅)进行交互。
* [Razorpay Java SDK](https://github.com/razorpay/razorpay-java)：Razorpay API的官方Java绑定。
* [DaxPay](https://gitee.com/bootx/dax-pay)：DaxPay是一套基于Bootx-Platform脚手架构建的一套开源支付网关系统，已经对接支付宝、微信支付相关的接口，以及扩展了钱包支付、储值卡支付、现金支付等新的支付方式。

## SDK

* [Aliyun Java SDK](https://github.com/aliyun/aliyun-openapi-java-sdk)：阿里云Java SDK。
* [Azure Java SDK](https://github.com/Azure/azure-sdk-for-java)：Azure Java SDK。
* [Azure IoT SDK Java](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [Tencent SDK Java](https://github.com/TencentCloud/tencentcloud-sdk-java)：腾讯云API 3.0 Java SDK。
* [Kubernetes Operator](https://github.com/operator-framework/java-operator-sdk)：用于构建Kubernetes Operator的Java SDK。
* [Aliyun ODPS Java SDK](https://github.com/aliyun/aliyun-odps-java-sdk)：面向Java开发者的ODPS SDK。
* [Volcengine Java SDK](https://github.com/volcengine/volcengine-java-sdk)：火山引擎Java SDK。
* [AWS Java SDK](https://github.com/aws/aws-sdk-java-v2)：AWS官方的Java SDK。
* [AWS IoT](https://github.com/aws/aws-iot-device-sdk-java)：用于从设备连接到AWS IoT的Java SDK。
* [AWS X-Ray](https://github.com/aws/aws-xray-sdk-java)：适用于Java的官方AWS X-Ray记录器SDK。
* [AWS C3R](https://github.com/aws/c3r)：C3R加密客户端和SDK。
* [Huawei SDK Java](https://github.com/huaweicloud/huaweicloud-sdk-java-v3)：华为云Java SDK。
* [Google App Engine](https://github.com/GoogleCloudPlatform/appengine-java-standard)：Google App Engine标准Java运行时：Prod运行时、本地devappserver、Cloud SDK Java组件、GAE API和GAE API模拟器。
* [DataflowTemplates](https://github.com/GoogleCloudPlatform/DataflowTemplates)：这些数据流模板旨在解决简单但大型的云内数据任务，包括数据导入/导出/备份/恢复和批量API操作，而无需开发环境，由Google开源。
* [Google Pub/Sub](https://github.com/GoogleCloudPlatform/pubsub)：Google Cloud Pub/Sub开源项目。
* [Google Cloud Java](https://github.com/googleapis/google-cloud-java)：适用于Java的Google Cloud客户端库。
* [Google APIs Client](https://github.com/googleapis/google-api-java-client)：适用于Java的Google API客户端库。
* [Google Cloud BigQuery Java](https://github.com/googleapis/java-bigquery)：Cloud BigQuery的Java客户端。
* [Google Map](https://github.com/googlemaps/android-maps-utils)：Android地图SDK工具类库。
* [Slack Java SDK](https://github.com/slackapi/java-slack-sdk)：适用于任何JVM语言的Slack开发套件。
* [React-Native](https://github.com/facebookarchive/react-native-fbsdk)：针对Android和iOS的Facebook SDK的React Native包装器。
* [CloudEvents Java](https://github.com/cloudevents/sdk-java)：CloudEvents是一种以通用格式描述事件数据的规范，以提供跨服务、平台和系统的互操作性。
* [Firebase Android](https://github.com/firebase/firebase-android-sdk)：Firebase安卓SDK。
* [Wizcorp Phonegap](https://github.com/Wizcorp/phonegap-facebook-plugin)：Cordova/PhoneGap中Facebook的官方插件。
* [Ice](https://github.com/Teevity/ice)：AWS使用工具，由Netflix开源。
* [Dapr Java SDK](https://github.com/dapr/java-sdk)：Dapr的Java SDK。
* [OCI Java SDK](https://github.com/oracle/oci-java-sdk)：用于Java的Oracle云基础设施SDK。
* [SA Java SDK](https://github.com/sensorsdata/sa-sdk-java)：神策数据官方Java埋点SDK，是一款轻量级用于Java端的数据采集埋点SDK。
* [BCE SDK Java](https://github.com/baidubce/bce-sdk-java)：百度云Java语言版SDK，可基于该SDK使用Java语言接入百度云的各项产品。
* [Microsoft Graph Java SDK](https://github.com/microsoftgraph/msgraph-sdk-java)：适用于Java的Microsoft Graph SDK。

## 微信开发

* [Weixin SDK](https://github.com/borball/weixin-sdk)：Weixin SDK是对微信公众平台(订阅号、服务号、企业号、小程序)、微信开放平台和微信支付的Java版封装。
* [WxJava](https://github.com/Wechat-Group/WxJava)：微信开发Java SDK，支持包括微信支付、开放平台、小程序、企业微信、公众号等的后端开发。
* [Weixin Java Tools](https://github.com/chanjarster/weixin-java-tools)：微信公众号、企业号Java SDK。
* [JFinal Weixin](https://gitee.com/jfinal/jfinal-weixin)：JFinal Weixin是基于JFinal的微信公众号极速开发SDK，只需浏览Demo代码即可进行极速开发。
* [Java Wechaty](https://github.com/wechaty/java-wechaty)：Java Wechaty是一个用Kotlin编写的聊天机器人开发者对话式SDK。
* [FastBootWeixin](https://gitee.com/kingshine/FastBootWeixin)：基于Spring Boot的注解驱动式公众号极速开发框架，用注解重新定义公众号开发。
* [Weixin Popular](https://github.com/liyiorg/weixin-popular)：微信Java SDK(公众平台、开放平台、商户平台、服务商平台)。
* [WeiXin4j](https://github.com/foxinmy/weixin4j)：WeiXin4j是一个用Java编写针对微信开发的工具包。
* [WX Dump4j](https://github.com/xuchengsheng/wx-dump-4j)：WX Dump4j是一款基于Java开发的微信数据分析工具。
* [JEEWX-API](https://github.com/jeecgboot/jeewx-api)：JEEWX-API是一款Java版的微信开发SDK，支持微信公众号、小程序、微信企业号、支付宝生活号SDK和微博SDK。
* [QYWX](https://github.com/shuaidd/qywx)：企业微信API封装。
* [ItChat4j](https://github.com/yaphone/itchat4j)：ItChat4j提供了简单易用的API，可以很方便地对个人微信号进行扩展，实现自动回复，微信挂机机器人等。
* [WeChat-API](https://github.com/hellokaton/wechat-api)：WeChat-API是微信个人号的Java版本API，让个人号具备更多能力，提供方便的接口调用。
* [WeCOM SDK](https://gitee.com/felord/wecom-sdk)：WeCOM SDK是开源的企业微信开放API的Java实现。

## 推送SDK

* [Austin](https://gitee.com/zhongfucheng/austin)：统一的接口发送各种类型消息，对消息生命周期全链路追踪。
* [JPush API Java](https://github.com/jpush/jpush-api-java-client)：极光官方支持的Java版本服务器端SDK。
* [个推PUSH Java SDK](https://github.com/GetuiLaboratory/getui-pushapi-java-client-v2)：个推官方提供的推送服务端SDK，基于全新的REST API V2接口。
* [WxPusher](https://github.com/wxpusher/wxpusher-sdk-java)：微信消息实时推送服务，可以通过API实时给个人微信推送消息。
* [Deliver](https://gitee.com/OS-Zero/deliver)：Deliver是一个面向企业的全面消息推送平台，旨在提供企业内部沟通和协作的便捷解决方案。
* [Message Gateway](https://github.com/openMF/message-gateway)：Message Gateway是Fineract提供商的推送消息服务，可以轻松地通过短信和电子邮件推送通知。

## API&客户端

* [Twitter4J](https://github.com/Twitter4J/Twitter4J)：Twitter4J是Twitter API的100%纯Java库，没有外部依赖。
* [JTwitter](https://github.com/winterstein/JTwitter)：JTwitter是一个强大且易于使用的Twitter库。
* [Twittered](https://github.com/redouane59/twittered)：面向Java开发人员的Twitter API客户端。
* [Spring Social](https://github.com/spring-attic/spring-social)：Spring Social是Spring框架的扩展，可帮助你将应用程序与Facebook和Twitter等SaaS提供商连接起来。
* [Twitter API Java Client](https://github.com/twitterdev/twitter-api-java-sdk)：Java版Twitter API客户端库。
* [RestFB](https://github.com/restfb/restfb)：RestFB是一个纯Java Facebook Graph API客户端，没有外部依赖。
* [Facebook4J](https://github.com/roundrop/facebook4j)：Facebook4J是Java语言的Facebook Graph API绑定库。
* [Facebook Business SDK](https://github.com/facebook/facebook-java-business-sdk)：用于Meta营销API的Java SDK。
* [Instagram4j](https://github.com/instagram4j/instagram4j)：使用OkHttpClient作为Instagram私有API的Java包装器。
* [JInstagram](https://github.com/sachin-handiekar/jInstagram)：Instagram API的Java库。
* [Instagram Java Scraper](https://github.com/postaddictme/instagram-java-scraper)：Instagram Java Scraper可以获取Instagram帐户信息、照片、视频和评论。
* [DyJava](https://gitee.com/sxwdmjy/dy-java)：DyJava是一款功能强大的抖音Java开发工具包，支持多种抖音开发功能模块的后端开发，包括但不限于移动/网站应用、开放平台、抖店和小程序等。
* [TikTok4j](https://github.com/cyrus07424/tiktok4j)：Java版非官方TikTok/DouYin API。
* [Slack-Client](https://github.com/HubSpot/slack-client)：Slack Web API的异步HTTP客户端，由HubSpot开源。
* [Simple Slack API](https://github.com/Itiviti/simple-slack-api)：该库允许应用程序连接到Slack以从任何通道接收和发送消息。
* [REST Countries](https://github.com/apilayer/restcountries)：REST Countries服务通过REST API提供有关国家/地区的通用信息。
* [JIRA Client](https://github.com/bobcarroll/jira-client)：JIRA Client是一个简单的Java JIRA REST客户端。
* [Twitch4j](https://github.com/twitch4j/twitch4j)：模块化异步/同步/响应式Twitch API客户端/IRC客户端。
* [JRAW](https://github.com/mattbdean/JRAW)：JRAW是JVM的Reddit API包装器。
* [Reddit4J](https://github.com/masecla22/Reddit4J)：Reddit4J是一个全面覆盖Reddit API的库。
* [CatNip](https://github.com/mewna/catnip)：Java中的Discord API包装器，完全异步/响应式，构建在RxJava之上。
* [Spotify Web API Java](https://github.com/spotify-web-api-java/spotify-web-api-java)：这是Spotify Web API的Java包装器/客户端。
* [Google Maps Services Java](https://github.com/googlemaps/google-maps-services-java)：Google Maps API Web服务的Java客户端库。
* [Apple App Store Server Java Library](https://github.com/apple/app-store-server-library-java)：App Store Server API和App Store Server Notifications的Java服务器库。
* [Spring Social Google](https://github.com/spring-social/spring-social-google)：Spring Social扩展，具有连接支持和Google API绑定。
* [Java Youtube Downloader](https://github.com/sealedtx/java-youtube-downloader)：用于检索Youtube视频元数据的简单Java解析器。
* [Gerrit Java Client](https://github.com/uwolfer/gerrit-rest-java-client)：用于Gerrit代码审查的Java REST客户端。
* [JOSS](https://github.com/javaswift/joss)：JOSS是OpenStack存储组件REST接口的Java客户端。
* [JWiki](https://github.com/fastily/jwiki)：用于轻松与Wikipedia/MediaWiki交互的库。
* [Jenkins Java Client](https://github.com/jenkinsci/java-client-api)：适用于Java的Jenkins API客户端。
* [Pterodactyl4J](https://github.com/mattmalec/Pterodactyl4J)：P4J致力于为Java提供干净且完整的Pterodactyl REST API包装。
* [Cobalt](https://github.com/Auties00/Cobalt)：适用于Java和Kotlin的独立非官方全功能Whatsapp Web和移动API。
* [ARI4Java](https://github.com/ari4java/ari4java)：Java的Asterisk REST接口(ARI)绑定。
* [Bitbucket REST](https://github.com/cdancy/bitbucket-rest)：使用Bitbucket REST API的客户端库。
* [Artifactory Java Client](https://github.com/jfrog/artifactory-client-java)：Artifactory Java客户端在你的Java代码中提供简单而强大的Artifactory连接和管理。

## 中间件客户端

* [NATS Java Client](https://github.com/nats-io/nats.java)：NATS消息系统的Java客户端。
* [RabbitMQ Java Client](https://github.com/rabbitmq/rabbitmq-java-client)：RabbitMQ Java客户端。
* [Lyra](https://github.com/jhalterman/lyra)：Lyra是一个拥抱故障的RabbitMQ客户端，可在发生意外故障时自动恢复AMQP资源，帮助你实现服务的高可用性。
* [Hop](https://github.com/rabbitmq/hop)：适用于Java、Groovy和其他JVM语言的RabbitMQ HTTP API客户端。
* [Eclipse Paho](https://github.com/eclipse/paho.mqtt.java)：Paho Java MQTT客户端库，Paho是一个Eclipse IoT项目。
* [Amazon Kinesis Client](https://github.com/awslabs/amazon-kinesis-client)：适用于Java的Amazon Kinesis客户端库。
* [HiveMQ MQTT Client](https://github.com/hivemq/hivemq-mqtt-client)：MQTT 5.0和3.1.1兼容且功能丰富的高性能Java客户端库，具有不同的API风格和背压支持。
* [Consul](https://github.com/Ecwid/consul-api)：Consul的Java客户端。
* [Grafana OpenTelemetry Starter](https://github.com/grafana/grafana-opentelemetry-starter)：用于OpenTelemetry的Spring Boot Starter。
* [Sentry SDK](https://github.com/getsentry/sentry-java/)：适用于Java、Android和其他JVM语言的Sentry SDK。
* [TarsJava](https://github.com/TarsCloud/TarsJava)：Java语言框架RPC源码实现，在Tars基金会下开源。
* [JEtcd](https://github.com/etcd-io/jetcd)：Java官方etcd客户端。
* [Etcd-Java](https://github.com/IBM/etcd-java)：IBM开源的etcd3 Java客户端库。
* [JEtcd](https://github.com/justinsb/jetcd)：etcd客户端库。
* [Milvus Java SDK](https://github.com/milvus-io/milvus-sdk-java)：Milvus的Java SDK。
* [Polaris Java](https://github.com/polarismesh/polaris-java)：用作无代理服务治理的轻量级Java SDK。
* [Kubernetes Java](https://github.com/kubernetes-client/java)：kubernetes的官方Java客户端库。
* [Kubernetes & OpenShift Client](https://github.com/fabric8io/kubernetes-client)：适用于Kubernetes和OpenShift的Java客户端。
* [OpenShift Java](https://github.com/openshift/openshift-restclient-java)：基于Kubernetes的OpenShift版本3架构的Java REST客户端。
* [DataDog](https://github.com/DataDog/dd-trace-java)：DadaDog分布式跟踪工具的Java客户端。
* [OpenStack4j](https://github.com/openstack4j/openstack4j)：OpenStack4j是一个流式的OpenStack客户端，允许配置和控制OpenStack部署。
* [TiKV Java Client](https://github.com/tikv/client-java)：TiKV的Java客户端。

## 游戏服务器

* [NettyGameServer](https://github.com/jwpttcg66/NettyGameServer)：使用Netty 4.X实现的手机游戏分布式服务器，支持TCP、UDP、HTTP、WebSocket链接。
* [JetServer](https://github.com/menacher/java-game-server)：JetServer是一个基于高速NIO套接字的多人Java游戏服务器，使用Netty和Jetlang编写。
* [Game Server](https://github.com/jzyong/game-server)：分布式Java游戏服务器，包括集群管理服务器、网关服务器、大厅服务器、游戏逻辑服务器。
* [Summer](https://github.com/SwingFrog/Summer)：Summer是一个轻量级、一站式的Java游戏服务器框架，也可用于开发简单的Web服务。
* [Mmorpg](https://github.com/kingston-csj/mmorpg)：Mmorpg是一个用Java编写的分布式高性能mmorpg手游服务端框架。
* [GameServer4j](https://github.com/jzyong/GameServer4j)：分布式Java游戏服务器，包括登录、网关、游戏演示。
* [ZFoo](https://github.com/zfoo-project/zfoo)：极快的企业服务器框架，可用于RPC、游戏服务器、Web服务器。
* [IoGame](https://gitee.com/game-town/ioGame)：IoGame是一个轻量级的网络编程框架，适用于网络游戏服务器、物联网、内部系统及各种需要长连接的场景。
* [Socket.IO](https://github.com/scalecube/socketio)：基于Netty的Socket.IO Java服务器，为了满足游戏性能要求而创建的。
* [Apollo](https://github.com/apollo-rsps/apollo)：Apollo是一个高性能、模块化的RuneScape模拟器，具有一系列用于管理数据文件和插件的实用程序。
* [Noark](https://gitee.com/xiaoe/noark3)：Noark是一个游戏服务器端框架，可快速开发出一个易维护、易扩展且稳定高能的游戏服务器。
* [Carmelo](https://github.com/needmorecode/carmelo)：Carmelo是一个快速、可扩展的Java服务器框架，专为在线游戏而设计。
* [Okra](https://github.com/ogcs/Okra)：Okra是一个简单的使用Java开发的高性能、高扩展、高并发、低延迟的服务器框架。
* [Gamioo](https://github.com/jiangguilong2000/gamioo)：游戏服务器框架，基于此框架，可以快速实现一个高可用、易维护、稳定、高性能的游戏服务器。
* [TenIO](https://github.com/congcoi123/tenio)：TenIO是一个用于创建多人在线游戏的开源项目，其中包括专门为多人游戏设计的基于Java NIO的服务器。
* [Avalon](https://gitee.com/codeborker/Avalon)：基于Akka的高性能可伸缩的Java网络游戏服务器，简单的单服务器开发与集群开发的切换。

## 即时通讯

* [Signal Server](https://github.com/signalapp/Signal-Server)：Signal是一款开源、端到端加密的通讯应用程序，可用于发送文本、语音、图片和视频等多种形式的消息。
* [TIMSDK](https://github.com/TencentCloud/TIMSDK)：腾讯云聊天拥有全球接入、一对一聊天、群聊、消息推送、档案和关系链托管、账户认证等一整套解决方案。
* [CIM](https://github.com/crossoverJie/cim)：CIM是一款面向开发者的IM(即时通讯)系统，同时提供了一些组件帮助开发者构建一款属于自己可水平扩展的IM。
* [野火IM](https://github.com/wildfirechat/im-server)：野火IM是专业级的即时通讯和实时音视频整体解决方案，由北京野火无限网络科技有限公司维护和支持。
* [Actor Platform](https://github.com/actorapp/actor-platform)：Actor是一个即时通讯平台。
* [MPush](https://github.com/mpusher/mpush)：MPush是一款开源实时消息推送系统。
* [NettyChat](https://github.com/FreddyChen/NettyChat)：基于Netty + TCP + Protobuf实现的Android IM库。
* [Turms](https://github.com/turms-im/turms)：Turms是全球最先进的开源即时通讯引擎，支持100K~10M并发用户。
* [InChat](https://github.com/AwakenCN/InChat)：InChat是一个轻量级、高效、分布式的异步通信框架，支持聊天和物联网。
* [Smack](https://github.com/igniterealtime/Smack)：Smack是一个开源、高度模块化、易于使用的XMPP客户端库，用Java编写，适用于兼容Java SE的JVM和Android。
* [J-IM](https://gitee.com/xchao/j-im)：J-IM是用Java语言开发的轻量、高性能、单机支持几十万至百万在线用户IM。
* [Openfire](https://github.com/igniterealtime/Openfire)：Openfire是一个即时通信和群聊服务器，它是使用Java编写的XMPP服务器。
* [CIM](https://gitee.com/farsunset/cim)：CIM是一套完善的消息推送框架，可应用于信令推送，即时聊天，移动设备指令推送等领域。
* [MobileIMSDK](https://github.com/JackJiang2011/MobileIMSDK)：MobileIMSDK是一个原创多端IM通信层框架，轻量级、高度提炼，支持UDP + TCP + WebSocket三种协议。
* [OIM](https://gitee.com/oimchat/oim-fx)：OIM是一套即时通讯的聊天系统，可以用于公司内网、外网通讯、客服系统等。
* [CometD](https://github.com/cometd/cometd)：用于网络消息传递的可扩展Comet(服务器推送)实现。
* [云信IM](https://github.com/netease-kit/nim-uikit-android)：云信IM UIKit基于网易云信IM SDK开发的一款即时通讯UI组件库，包括聊天、会话、圈组、搜索、群管理等组件。
* [QIQIIM](https://gitee.com/qiqiim/qiqiim-server)：QIQIIM提供简单快捷的IM方案，可用于公司内网、外网通讯，客服系统等。
* [Spark](https://github.com/igniterealtime/Spark)：Spark是一款针对企业和组织进行优化的开源跨平台IM客户端。
* [Gifsockets](https://github.com/videlalvaro/gifsockets)：使用Gif动画作为传输的实时通信库。
* [RongCloud Server SDK](https://github.com/rongcloud/server-sdk-java)：Java版融云即时通讯服务器SDK。
* [SONA](https://github.com/BixinTech/sona)：SONA是一个由比心语音技术团队开发，用于快速搭建语音房产品的全端解决方案，支撑了比心聊天室、直播、游戏房等业务。
* [Tencent Cloud IM Server SDK](https://github.com/doocs/qcloud-im-server-sdk-java)：腾讯云IM服务端SDK Java版。
* [Ant Media Server](https://github.com/ant-media/Ant-Media-Server)：Ant Media Server是一款直播流引擎软件，通过使用WebRTC技术提供自适应、超低延迟流媒体，延迟约为0.5秒。
* [Conversations](https://codeberg.org/iNPUTmice/Conversations)：Conversations是适用于Android的开源XMPP/Jabber客户端。
* [Xiaper](https://github.com/xiaper/xiaper)：Xiaper是一款开源企业IM解决方案。
* [盒子IM](https://gitee.com/bluexsx/box-im)：盒子IM是一个仿微信实现的网页版聊天软件，不依赖任何第三方收费组件。

## 视频会议

* [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)：BigBlueButton是一个开源虚拟教室，旨在帮助教师教学和学习者学习。
* [Apache OpenMeetings](https://github.com/apache/openmeetings)：Openmeetings提供视频会议、即时消息、白板、协作文档编辑和其他群件工具。
* [OpenVidu Call](https://github.com/OpenVidu/openvidu-call)：OpenVidu是一个方便在Web或移动应用程序中添加视频通话的平台。

## FTP服务器

* [MinimalFTP](https://github.com/Guichaguri/MinimalFTP)：一个轻量级、简单的FTP服务器。
* [Anomic](https://github.com/Orbiter/anomic_ftp_server)：一个简单的FTP服务器。
* [Primitive FTPd](https://github.com/wolpi/prim-ftpd)：适用于Android的FTP服务器应用程序。
* [SwiFTP](https://github.com/ppareit/swiftp)：Android设备的FTP服务器。

## 区块链

* [Web3j](https://github.com/web3j/web3j)：Web3j是一个轻量级、高度模块化、响应式、类型安全的Java和Android库，用于处理智能合约并与以太坊网络上的客户端(节点)集成。
* [Token Core](https://github.com/consenlabs/token-core-android)：TokenCore是一个区块链库，提供了相对一致的API，允许你同时管理钱包并在BTC、ETH和EOS链上签署交易。
* [Waves](https://github.com/wavesplatform/Waves)：Waves是一个基于社区的去中心化开源技术堆栈，用于构建可扩展、用户友好的应用程序。
* [NEM](https://github.com/NemProject/nem)：该项目包含NEM基础设施服务器及其所有依赖项。
* [MD BlockChain](https://gitee.com/tianyalei/md_blockchain)：开源Java区块链平台，可做联盟链、私链使用，不适用于公链。
* [FingerNFT](https://github.com/fingerchar/fingernft)：FingerNFT是一款开源NFT市场，兼容Opensea、Rarible。
* [Arbitrader](https://github.com/agonyforge/arbitrader)：市场中立的加密货币交易机器人。
* [Apache Tuweni](https://github.com/apache/incubator-tuweni)：Tuweni是一组库和其他工具，可帮助使用Java和其他JVM语言开发区块链和其他去中心化软件。
* [FundRequest](https://github.com/FundRequest/platform)：FundRequest平台代码。
* [Blockj](https://gitee.com/blackfox/blockj)：Java实现的一个简易区块链(联盟链)项目，包括加密工具、钱包、P2P传输、区块同步、网络共识等基础实现。
* [JD Chain](https://gitee.com/jdchain/jdchain)：京东区块链是一个企业级的区块链框架系统，具有简洁、易用、可扩展和高性能的特点。
* [J2Chain](https://gitee.com/ld/J2Chain)：Java开发区块链的开源项目。
* [FexCoin](https://gitee.com/koch/fex-wallet-app)：加密货币钱包，数字货币交易所，区块链数字资产管理工具。
* [Fabric SDK Java](https://github.com/hyperledger/fabric-sdk-java)：该项目提供了一个用于与Hyperledger Fabric区块链网络交互的低级API。
* [WeIdentity](https://github.com/WeBankBlockchain/WeIdentity)：WeIdentity是一套分布式多中心的技术解决方案，可承载实体对象(人或者物)的现实身份与链上身份的可信映射、以及实现实体对象之间安全的访问授权与数据交换，由微众银行开源。
* [WeEvent](https://github.com/WeBankBlockchain/WeEvent)：WeEvent是一套分布式事件驱动架构，实现了可信、可靠、高效的跨机构、跨平台事件通知机制，由微众银行开源。
* [WeBASE](https://github.com/WeBankBlockchain/WeBASE)：微众银行区块链应用软件扩展。
* [WeCross](https://github.com/WeBankBlockchain/WeCross)：WeCross是由微众银行开源的区块链跨链协作平台，致力于促进跨行业、机构和地域的跨区块链信任传递和商业合作。
* [TokenCore](https://github.com/GalaxySciTech/tokencore)：Tokencore是区块链钱包后端的核心组件，支持多种区块链地址生成和离线签名。
* [Nuls-v1](https://github.com/nuls-io/nuls-v1)：Nuls是一个全球区块链开源项目，是一个高度可定制的模块化区块链基础设施。
* [Nuls-v2](https://github.com/nuls-io/nuls-v2)：NULS协议的官方Java实现。
* [RepChain](https://gitee.com/BTAJL/repchain)：第一款采用响应式编程实现的自主可控的区块链基础组件，由广州软件应用技术研究院、中国科学院软件所、贵阳信息技术研究院、中科智城信息科技有限公司、中科软科技股份有限公司和北京连琪科技有限公司共同研发。
* [Aion](https://github.com/aionnetwork/aion)：Aion网络Java实现。
* [Blockchain](https://github.com/Will1229/Blockchain)：区块链的Java简单实现。
* [TRON](https://github.com/tronprotocol/java-tron)：Tron白皮书的Java实现。
* [Hyperledger Quilt](https://github.com/hyperledger-archives/quilt)：Quilt是Interledger协议的Java实现。
* [SimBlock](https://github.com/dsg-titech/simblock)：开SimBlock 是一款开源区块链网络模拟器，由东京工业大学分布式系统组开发。
* [Universa](https://github.com/UniversaBlockchain/universa)：Universa网络、节点、客户端和API。
* [Sun Network](https://github.com/tronprotocol/sun-network)：Sun Network是一个致力于构建TRON区块链可信去中心化侧链的项目。
* [Neow3j](https://github.com/neow3j/neow3j)：Neow3j是一个开发工具包，提供简单可靠的工具来使用Java平台(Java、Kotlin、Android)构建Neo dApp和智能合约。
* [COTI Node](https://github.com/coti-io/coti-node)：COTI是第一个基于DAG的链协议，针对企业和稳定币进行了优化。
* [EOSIO](https://github.com/EOSIO/eosio-java)：用于与基于EOSIO的区块链集成的API。
* [Cardano](https://github.com/bloxbean/cardano-client-lib)：Java中的Cardano客户端库。
* [Thunder](https://github.com/blockchain/thunder)：使用智能合约进行链下比特币支付。
* [Web3signer](https://github.com/Consensys/web3signer)：一种开源签名服务，能够使用存储在外部保管库中或加密在磁盘上的私钥在多个平台(Ethereum1和2、Filecoin)上进行签名。
* [Hedera Services](https://github.com/hashgraph/hedera-services)：Hedera公共账本的加密货币、代币、共识、文件和智能合约服务。
* [SmartJ](https://github.com/signum-network/signum-smartj)：Signum的Java智能合约。
* [Tessera](https://github.com/Consensys/tessera)：Tessera是一个开源私有Quoru事务管理器，用Java编写。
* [Hashgraph Java SDK](https://github.com/hashgraph/hedera-sdk-java)：适用于Java的Hedera Hashgraph SDK。
* [Universal Resolver](https://github.com/decentralized-identity/universal-resolver)：通用解析器实现和驱动程序。
* [X-Road](https://github.com/nordic-institute/X-Road)：X-Road是开源软件和生态系统解决方案，可在组织之间提供统一且安全的数据交换。
* [Minima](https://github.com/minima-global/Minima)：Minima是一个新的区块链，强调每个用户都能够运行完整的节点。
* [OmniJ](https://github.com/OmniLayer/OmniJ)：Omni Layer的Java/JVM实现，Omni Layer是一个基于比特币区块链构建的开源、完全去中心化的资产创建平台。
* [XDAGJ](https://github.com/XDagger/xdagj)：XDAGJ是XDAG在Java中的实现。
* [Hildr](https://github.com/optimism-java/hildr)：Hildr是一个用Java 21编写、原生GraalVM的OP Stack服务。
* [Corda](https://github.com/corda/corda)：Corda是一个开源区块链项目。
* [Sol4k](https://github.com/sol4k/sol4k)：Sol4k是Solana的Kotlin客户端，可与Java或任何其他JVM语言以及Android一起使用。
* [AuthentiFi](https://github.com/kylelobo/AuthentiFi)：基于区块链的产品所有权管理系统，用于邮政供应链中的防伪。
* [Convex](https://github.com/Convex-Dev/convex)：Convex是价值互联网的去中心化网络和执行引擎。
* [Semux](https://github.com/semuxproject/semux-core)：Semux是一个实验性高性能区块链平台，为去中心化应用程序提供支持。
* [Apollo](https://github.com/ApolloFoundation/Apollo)：该仓库包含Apollo区块链平台的核心类和Apollo区块链组件的主要可执行文件。
* [Java4Ever](https://github.com/deplant/java4ever-framework)：Java4Ever是一个功能丰富的框架，用于智能合约开发、测试和访问TVM兼容的区块链，例如Everscale、Venom、GOSH等。

## 以太坊

* [Ethereumj](https://github.com/ethereum/ethereumj)：以太坊黄皮书的Java实现。
* [Besu](https://github.com/hyperledger/besu)：Besu是一个兼容MainNet的、用Java编写的以太坊客户端。
* [Teku](https://github.com/Consensys/teku)：以太坊2.0信标链的Java实现。
* [AlphaWallet](https://github.com/AlphaWallet/alpha-wallet-android)：AlphaWallet是一个开源可编程区块链应用程序平台。
* [Eventeum](https://github.com/eventeum/eventeum)：弹性以太坊事件监听器，可连接你的智能合约事件和后端微服务。
* [Presto Ethereum Connector](https://github.com/xiaoyao1991/presto-ethereum)：这是连接以太坊区块链数据的Presto连接器，有了这个连接器，就可以开始进行以太坊区块链分析工作，而无需知道如何使用Javascript API的细节。
* [Trust](https://github.com/trustwallet/trust-wallet-android-source)：Android版以太坊钱包。
* [ETHWallet](https://github.com/DwyaneQ/ETHWallet)：一款模仿imToken实现的ETH钱包。
* [Securify](https://github.com/eth-sri/securify)：以太坊智能合约安全扫描器。
* [BitcoinWallet](https://github.com/terryjiao/BitcoinWallet)：比特币和以太坊钱包。
* [EtherJar](https://github.com/emeraldpay/etherjar)：适用于以太坊区块链的框架无关的模块化Java 17+集成库。
* [Wuhan Chain](https://github.com/BSN-DDC/wuhanchain)：BSN官方DDC智能合约和SDK基于开放许可的区块链-武汉链(以太坊)。

## 比特币

* [Bitcoinj](https://github.com/bitcoinj/bitcoinj)：Bitcoinj库是比特币协议的Java实现，它允许它维护钱包并发送/接收交易，而不需要Bitcoin Core的本地副本。
* [Bisq](https://github.com/bisq-network/bisq)：去中心化的比特币交易网络。
* [XChange](https://github.com/knowm/XChange)：一个Java库，提供简化的API，用于与60多个比特币和山寨币交易所进行交互，为交易和访问市场数据提供一致的接口。
* [Bitcoin Wallet](https://github.com/bitcoin-wallet/bitcoin-wallet)：适用于Android设备的比特币钱包应用程序。
* [Exchange-core](https://github.com/exchange-core/exchange-core)：使用Java编写的超快速匹配引擎，基于LMAX Disruptor、Eclipse Collections、Agrona、OpenHFT、LZ4 Java和Adaptive Radix Trees。
* [Crypto-Exchange](https://github.com/jammy928/CoinExchange_CryptoExchange_Java)：基于Spring Cloud微服务开发，可用于数字货币交易所的搭建和二次开发。
* [OBAndroid](https://github.com/omnilaboratory/OBAndroid)：适用于Android设备的自我托管OmniBOLT闪电钱包。
* [Sparrow](https://github.com/sparrowwallet/sparrow)：Sparrow是一款现代桌面比特币钱包应用程序，支持大多数硬件钱包，并基于PSBT等通用标准构建，强调透明度和可用性。
* [Drongo](https://github.com/sparrowwallet/drongo)：一个Java比特币库。
* [BX-bot](https://github.com/gazbert/bxbot)：用Java编写的简单比特币交易机器人。
* [Mycelium Bitcoin Wallet](https://github.com/mycelium-com/wallet-android)：Android版Mycelium比特币钱包。
* [DiabloMiner](https://github.com/Diablo-D3/DiabloMiner)：比特币OpenCL矿工。
* [Bither](https://github.com/bither/bither-android)：简单安全的比特币钱包。
* [Warp Exchange](https://github.com/michaelliao/warpexchange)：简单、超快的7 x 24交易。
* [Boilr](https://github.com/drpout/boilr)：比特币、加密货币、加密资产、期货和期权的价格警报。
* [CoinExchange](https://gitee.com/cexchange/CoinExchange)：开源数字货币合约交易所，基于Java开发的比特币交易所、BTC交易所、ETH交易所、数字货币交易所、交易平台、撮合交易引擎。
* [CoinGecko-Java](https://github.com/Philipinho/CoinGecko-Java)：CoinGecko API的Java包装器。
* [GitBitEX](https://github.com/gitbitex/gitbitex-new)：GitBitEX是一个开源的加密货币交易所。
* [Haveno](https://github.com/haveno-dex/haveno)：Haveno是一个开源平台，用于将Monero兑换为美元、欧元和英镑等法定货币或BTC、ETH和BCH等其他加密货币。

## 物联网

* [ThingsBoard](https://github.com/thingsboard/thingsboard)：ThingsBoard是一个开源物联网平台，用于数据收集、处理、可视化和设备管理。
* [JetLinks](https://gitee.com/jetlinks/jetlinks-community)：JetLinks是一个开箱即用，可二次开发的企业级物联网基础平台。
* [Eclipse Milo](https://github.com/eclipse/milo)：Milo是OPC UA的开源实现，它包括高性能堆栈(通道、序列化、数据结构、安全性)以及构建在堆栈顶部的客户端和服务器SDK。
* [Apache PLC4X](https://github.com/apache/plc4x)：Apache PLC4X致力于创建一组库，用于以统一的方式与工业级可编程逻辑控制器(PLC)进行通信。
* [Eclipse SmartHome](https://github.com/eclipse-archived/smarthome)：旨在创建一个构建智能家居解决方案的框架，其重点是异构环境，即各种协议和标准集成。
* [OpenRemote](https://github.com/openremote/openremote)：OpenRemote是一个直观、用户友好的100%开源物联网平台。
* [OpenHAB](https://github.com/openhab/openhab-core)：OpenHAB是一个开源、与技术无关的家庭自动化平台，作为智能家居的中心运行。
* [SmartThings](https://www.samsung.com/us/smartthings/)：SmartThings是一款免费应用程序，它使用Wi-Fi连接基于Matter协议的智能设备，无论其制造商是哪家公司，这是三星的产品。
* [FastBee](https://gitee.com/kerwincui/wumei-smart)：FastBee开源物联网平台，简单易用，更适合中小企业和个人学习使用。适用于智能家居、智慧办公、智慧社区、农业监测、水利监测、工业控制等。
* [Eclipse Californium](https://github.com/eclipse-californium/californium)：Eclipse Californium是RFC7252(物联网云服务的约束应用协议)的Java实现。
* [Zeus IoT](https://github.com/zmops/zeus-iot)：Zeus IoT是一个分布式物联网采集、分析、存储平台，是全球第一个基于zabbix二次开发的物联网开源平台。
* [Eclipse Leshan](https://github.com/eclipse-leshan/leshan)：Eclipse Leshan是OMA轻量级M2M服务器和客户端Java实现。
* [Groza](https://github.com/IoT-Technology/Groza)：开源物联网平台-物联网解决方案的设备管理、数据收集、处理。
* [SiteWhere](https://github.com/sitewhere/sitewhere)：SiteWhere是一个具有工业实力的开源物联网应用支持平台，可促进大规模物联网设备数据的摄取、存储、处理和集成。
* [SolarNode](https://github.com/SolarNetwork/solarnetwork-node)：SolarNode是用于收集数据和控制设备的分布式SolarNetwork组件。
* [ThingLinks](https://gitee.com/mqttsnet/thinglinks)：采用Spring Cloud微服务架构，一款高性能、高吞吐量、高扩展性的物联网平台。
* [Eclipse Ditto](https://github.com/eclipse-ditto/ditto)：Eclipse Ditto是物联网中的一项技术，实现了一种称为“数字孪生”的软件模式。
* [Eclipse Kura](https://github.com/eclipse/kura)：Eclipse Kura是一个多功能软件框架，旨在增强你的边缘设备的性能。
* [IoTLink](https://gitee.com/sdyunze/iotlink)：IoTLink是一个基于Spring Boot、Vue、Mybatis、RabbitMQ、MySQK、Redis等开发的物联网平台，支持对物联网卡、物联网模组以及卡+模组的融合管理。
* [Apache StreamPipes](https://github.com/apache/streampipes)：StreamPipes是一个自助物联网工具箱，使非技术用户能够连接、分析和探索物联网数据流。
* [Eclipse HawkBit](https://github.com/eclipse/hawkbit)：Eclipse hawkBit是一个独立于域的后端解决方案，用于向受限边缘设备以及连接到基于IP的网络基础设施的更强大的控制器和网关推出软件更新。
* [DeviceHive](https://github.com/devicehive/devicehive-java-server)：DeviceHive将任何连接的设备变成物联网的一部分。它提供通信层、控制软件和多平台库，以引导智能能源、家庭自动化、遥感、遥测、远程控制和监控软件等的开发。
* [Freedomotic](https://github.com/freedomotic/freedomotic)：Freedomotic是一个开源、灵活、安全的IoT应用程序框架，可用于构建和管理现代智能空间。
* [Tigase Server](https://github.com/tigase/tigase-server)：Tigase XMPP Server是用Java编写的高度优化、高度模块化且非常灵活的XMPP/Jabber服务器。
* [Eclipse Vorto](https://github.com/eclipse/vorto)：Eclipse Vorto提供了一种用于描述IoT数字孪生模型和接口的语言。
* [IoT DC3](https://gitee.com/pnoker/iot-dc3)：基于Spring Cloud的开源、分布式的IoT平台，用于快速开发物联网项目和管理物联设备，是一整套物联系统解决方案。
* [S7Connector](https://github.com/s7connector/s7connector)：用于Java的S7 PLC连接器。
* [Eclipse Tahu](https://github.com/eclipse/tahu)：Eclipse Tahu提供各种语言和各种设备的客户端库和参考实现，以显示设备/远程应用程序必须如何使用下面解释的Sparkplug规范连接和断开与MQTT服务器的连接。
* [NetXMS](https://github.com/netxms/netxms)：NetXMS是一款开源网络和基础设施监控和管理解决方案，为IT基础设施的所有层提供性能和可用性监控以及灵活的事件处理、警报、报告和图表。
* [World Avatar](https://github.com/cambridge-cares/TheWorldAvatar)：基于知识图谱的世界数字孪生，由新加坡剑桥高级研究与教育中心开源。
* [OpenIita](https://gitee.com/open-iita/iotkit-parent)：铱塔智联开源平台是一个开源的物联网基础开发平台，提供了物联网及相关业务开发的常见基础功能，能帮助你快速搭建自己的物联网相关业务平台。
* [HA-Bridge](https://github.com/bwssytems/ha-bridge)：将Philips Hue API模拟到其他家庭自动化网关，例如Amazon Echo/Dot或支持Philips Hue本地网络发现的其他系统。
* [OpenHAB Add-ons](https://github.com/openhab/openhab-addons)：该库包含在OpenHAB核心API之上实现的官方附加组件集。
* [Amazon Echo Bridge](https://github.com/armzilla/amazon-echo-ha-bridge)：Amazon Echo Bridge允许你快速模拟Phillips Hue桥，从而能够将Amazon Echo无缝集成到各种家庭自动化系统中。
* [Eclipse Kapua](https://github.com/eclipse/kapua)：Kapua是一个模块化平台，提供管理物联网网关和智能边缘设备所需的服务。
* [Eclipse Hono](https://github.com/eclipse-hono/hono)：Eclipse Hono提供统一(远程)服务接口，用于将大量IoT设备连接到(云)后端。
* [Azure IoT SDK](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [IOTGate](https://gitee.com/willbeahero/IOTGate)：Java版基于Netty的物联网高并发智能网关。
* [Indriya](https://github.com/unitsofmeasurement/indriya)：JSR 385参考实现。
* [SteVe](https://github.com/steve-community/steve)：SteVe于2013年在亚琛工业大学成立，提供了管理充电点、用户数据和用于用户身份验证的RFID卡的基本功能，并已在运行中进行了成功测试。
* [Sentilo](https://github.com/sentilo/sentilo)：Sentilo是一个架构，它隔离了为利用“城市生成”的信息而开发的应用程序和部署在城市各处以收集和广播该信息的传感器层。
* [WSO2 IoT Server](https://github.com/wso2/product-iots)：WSO2 IoT Server是一个完整的解决方案，使设备制造商和企业能够连接和管理其设备、构建应用程序、管理事件、保护设备和数据以及以可扩展的方式可视化传感器数据。
* [MyController](https://github.com/mycontroller-org/mycontroller-v1-legacy)：MyController是一个适用于家庭、办公室或任何地方的物联网自动化控制器。
* [IoT-Ucy](https://gitee.com/iteaj/iot)：IoT-Ucy是使用Java开发的物联网网络中间件，支持udp、tcp、串口通讯等底层协议和http、mqtt、websocket、modbus(tcp,rtu)、plc、dtu等上层协议。
* [ESPlorer](https://github.com/4refr0nt/ESPlorer)：面向ESP8266开发人员的集成开发环境。
* [Eclipse BaSyx](https://github.com/eclipse-basyx)：Eclipse BaSyx是下一代自动化的开源平台，它实现了工业4.0平台定义的关键概念，例如作为标准化数字孪生的资产管理shell。
* [Eclipse AAS4J](https://github.com/eclipse-aas4j/aas4j)：Eclipse AAS4J实现了Asset Administration Shell(AAS)的规范，例如基于AAS规范的元模型、子模型、序列化和反序列化模块、验证器和转换库。
* [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN)：GRASSMARLIN提供工业控制系统以及监控和数据采集(SCADA)网络的IP网络态势感知，以支持网络安全，由美国国家安全局网络安全局开源。
* [Scada-LTS](https://github.com/SCADA-LTS/Scada-LTS)：Scada-LTS是一个基于Web的开源多平台解决方案，用于构建你自己的SCADA(监控和数据采集)系统。
* [Apache Edgent](https://github.com/apache/incubator-retired-edgent)：Apache Edgent是一种适用于边缘设备的开源编程模型和运行时，使你能够分析设备上的数据和事件。
* [Grid eXchange Fabric](https://github.com/OSGP/open-smart-grid-platform)：GXF是一个软件平台，可在公共空间中实现硬件监控和控制。
* [Aura Tower](https://github.com/blumek/aura-tower)：Aura Tower是一个开源项目，旨在通过直观的仪表板控制和监控物联网设备。

## 车联网

* [JT808 Server](https://github.com/yezhihao/jt808-server)：JT808、JT808协议解析；支持TCP、UDP，实时兼容2011、2013、2019版本协议，支持分包。
* [JT Framework](https://github.com/hylexus/jt-framework)：基于Spring Boot的JT-808协议服务端。
* [Eclipse MOSAIC](https://github.com/eclipse/mosaic)：Eclipse MOSAIC是智能互联移动领域的多尺度仿真框架，它允许将来自不同领域的模拟器耦合到综合模拟工具。
* [JTT1078 Video Server](https://gitee.com/matrixy/jtt1078-video-server)：基于JT/T 1078协议实现的视频转播服务器。

## 嵌入式

* [Arduino](https://github.com/arduino/Arduino)：Arduino是一个开源嵌入式硬件平台，用来供用户制作可交互式的嵌入式项目。
* [CocktailPi](https://github.com/alex9849/CocktailPi)：基于树莓派的DIY鸡尾酒制作机的Web界面和控制软件。
* [Pi4J](https://github.com/Pi4J/pi4j-v1)：适用于Raspberry Pi的Java I/O库。
* [Ardulink 2](https://github.com/Ardulink/Ardulink-2)：Ardulink 2是一个完整的开源Java解决方案，用于控制和协调Arduino板。
* [Diozero](https://github.com/mattjlewis/diozero)：用Java编写的设备I/O库，为连接到单板计算机(如Raspberry Pi)的一系列GPIO/I2C/SPI设备(LED、按钮、传感器、电机、显示器等)提供面向对象的接口。

## MQTT

* [Moquette](https://github.com/moquette-io/moquette)：Moquette的目标是成为符合MQTT标准的Broker，代理支持QoS 0、QoS 1和QoS 2。
* [BifroMQ](https://github.com/baidu/bifromq)：BifroMQ是一种高性能、分布式MQTT代理实现，可无缝集成原生多租户支持，由百度开源。
* [MQTT-Client](https://github.com/fusesource/mqtt-client)：MQTT-Client为MQTT提供API，如果发生任何网络故障，它会自动重新连接到MQTT服务器并恢复客户端会话。
* [AndrOBD](https://github.com/fr3ts0n/AndrOBD)：AndrOBD允许你的Android设备通过任何ELM327兼容的OBD适配器连接到汽车的车载诊断系统，显示各种信息并执行操作。
* [HiveMQ](https://github.com/hivemq/hivemq-community-edition)：HiveMQ CE是HiveMQ企业连接和消息传递平台的基础，并实现所有MQTT功能。
* [ActiveMQ Artemis](https://github.com/apache/activemq-artemis)：ActiveMQ Artemis是ActiveMQ的下一代消息代理。
* [Mica-MQTT](https://gitee.com/596392912/mica-mqtt)：低延迟、高性能的MQTT物联网组件。
* [SMQTT](https://github.com/quickmsg/smqtt)：开源MQTT服务器(基于Reactor-Netty实现高性能的、可扩展、支持千万级设备接入集群)，支持MQTT 3.1.1、MQTT 5等协议。
* [MqttWk](https://github.com/Wizzercn/MqttWk)：Java + Netty实现的高并发高可用MQTT服务Broker。
* [Jmqtt](https://github.com/Cicizz/jmqtt)：一个MQTT Broker，由Java和Netty实现，支持持久化和集群。
* [TBMQ](https://github.com/thingsboard/tbmq)：开源MQTT Broker-促进MQTT客户端连接、消息发布和订阅者之间的分发。
* [Joynr](https://github.com/bmwcarit/joynr)：Joynr是一个基于Web的通信框架，适用于希望与其他应用程序交互的Java、C++和JavaScript应用程序，无论它们是部署在消费设备、车辆、后端基础设施上还是在云中，由宝马开源。
* [MoP](https://github.com/streamnative/mop)：MoP是为了在Pulsar上原生支持MQTT协议而开发的。
* [EnMasse](https://github.com/EnMasseProject/enmasse)：EnMasse在Kubernetes和OpenShift上提供了一个自助消息传递平台，具有统一的界面来管理不同的消息传递基础设施。
* [Smart MQTT](https://gitee.com/smartboot/smart-mqtt)：一款开源的云原生分布式MQTT Broker服务器，支持海量物联网设备互联互通。
* [RocketMQ MQTT](https://github.com/apache/rocketmq-mqtt)：全新的MQTT协议架构模型，基于该模型RocketMQ可以更好地支持来自物联网设备、手机APP等终端的消息。
* [HelloIoT](https://github.com/adrianromero/helloiot)：HelloIoT是一个MQTT仪表板应用程序，你可以使用HelloIoT作为MQTT客户端应用程序来发布和订阅主题，也可以使用HelloIoT作为客户端平台来创建自己的仪表板。
* [SMQTTX](https://gitee.com/quickmsg/smqttx)：基于Java实现的物联网分布式MQTT消息代理服务器。
* [WeMQ](https://gitee.com/dromara/WeMQ)：WeMQ是一款面向物联网设备运营商的开源物联网设备调试系统，提供完整的物联网设备调试方案，集成设备管理、MQTT服务器管理、客户管理等功能，由dormara社区开源。

## 金融

* [Apache Fineract](https://github.com/apache/fineract)：Fineract是一个具有开放API的成熟平台，可为金融机构提供可靠、强大且价格实惠的核心银行解决方案，为全球30亿银行服务不足和无银行账户的人口提供服务。
* [Portfolio](https://github.com/portfolio-performance/portfolio)：Portfolio是一个开源程序，用于根据实时加权回报率和内部回报率计算整个投资组合(跨不同投资组合和账户)的绩效。
* [Northstar](https://gitee.com/dromara/northstar)：这是一个面向程序员的专业级量化交易软件，用于期货、股票、外汇、炒币等多种交易场景，实现自动交易，由dromara社区开源。
* [OBP-API](https://github.com/OpenBankProject/OBP-API)：OBP是一个面向银行的开源API，使账户持有人能够使用更广泛的应用程序和服务与银行进行交互。
* [Strata](https://github.com/OpenGamma/Strata)：Strata是OpenGamma的开源分析和市场风险库。
* [JavaMoney](https://github.com/JavaMoney/javamoney-lib)：JavaMoney提供基于JSR 354(兼容实现)构建的扩展和库。
* [QuickFIX/J](https://github.com/quickfix-j/quickfixj)：QuickFIX/J是适用于FIX协议的全功能消息传递引擎。
* [CDM](https://github.com/finos/common-domain-model)：CDM是金融产品、这些产品的交易以及这些交易的生命周期事件的模型，由金融科技开源基金会FINOS托管。
* [Moneta](https://github.com/JavaMoney/jsr354-ri)：Moneta是JSR 354货币API的参考实现。
* [Ta4j](https://github.com/ta4j/ta4j)：Ta4j是一个用于技术分析的开源Java库，它提供了创建、评估和执行交易策略的基本组件。
* [DROP](https://github.com/lakshmiDRIP/DROP)：DROP实现的库针对固定收益、信贷、商品、股票、外汇和结构性产品内部和之间的分析/风险、交易成本分析、资产负债分析、资本、风险敞口和保证金分析、估值调整分析和投资组合构建分析。
* [Stripe](https://github.com/stripe/stripe-java)：Stripe API的Java库。
* [Philadelphia](https://github.com/paritytrading/philadelphia)：Philadelphia是一个用于JVM的快速FIX协议库。
* [Parity](https://github.com/paritytrading/parity)：Parity是一个用于交易场所的开源软件平台，它可用于运行金融市场、开发算法交易代理或研究市场微观结构。
* [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot)：Cassandre交易机器人框架允许你在多个加密货币交易所快速创建和执行交易策略。
* [Open Banking](https://github.com/wso2/financial-open-banking)：WSO2开放银行加速器是一系列技术的集合，可提高开放银行合规性的速度并降低其复杂性。
* [Joda-Money](https://github.com/JodaOrg/joda-money)：Joda-Money提供了一个类库来存储大量资金。
* [Prowide ISO 20022](https://github.com/prowide/prowide-iso20022)：Prowide ISO 20022是一个用于管理ISO 20022消息的开源Java框架。
* [Prowide](https://github.com/prowide/prowide-core)：Prowide Core是一个用于管理SWIFT FIN消息的开源Java框架。
* [Artio](https://github.com/real-logic/artio)：Artio是高性能FIX和FIXP网关。
* [jPOS](https://github.com/jpos/jPOS)：jPOS是一个开源的Java平台，用于构建和部署高度可扩展、事务处理、基于ISO-8583标准的金融交易处理系统。
* [Sailfish](https://github.com/exactpro/sailfish-core)：Sailfish是一个测试自动化工具，其主要目的是测试分布式交易平台和市场数据交付系统中的双向消息流。
* [Plaid-Java](https://github.com/plaid/plaid-java)：Plaid API的Java绑定。
* [Bateman](https://github.com/fearofcode/bateman)：Bateman是一个非常简单的交易系统，旨在筛选美国股票市场的子集。
* [Open Banking Gateway](https://github.com/adorsys/open-banking-gateway)：提供RESTful API、工具、适配器和连接器，用于透明访问开放银行API(适用于支持PSD2和XS2A以及HBCI/FinTS的银行)。
* [Finance Quotes API](https://github.com/sstrickx/yahoofinance-api)：该库提供了一些方法，可以轻松地与Yahoo Finance API进行通信，它允许你请求股票的详细信息、一些统计数据和历史报价。
* [ISO8583 Message Client](https://github.com/imohsenb/ISO8583-Message-Client-java)：一个轻量级ISO8583库，适用于Java和Android，基于构建器模式。
* [JReactive-8583](https://github.com/kpavlov/jreactive-8583)：适用于ISO8583和Netty的Kotlin/Java客户端和服务器。
* [J8583](https://bitbucket.org/chochos/j8583)：J8583是ISO8583协议的Java实现。
* [SubMicroTrading](https://github.com/Richard-Rose/SubMicroTrading)：SubMicroTrading是一个高度并发的基于组件的算法交易框架。
* [Accounting](https://github.com/Nick-Triller/accounting)：Accounting是一个用Java编写的内存中复式记账组件。
* [JBanking](https://github.com/marcwrobel/jbanking)：JBanking是一个帮助开发银行功能的实用程序库，专注但不限于欧洲银行业。
* [Alpaca Java](https://github.com/Petersoj/alpaca-java)：这是Alpaca API的Java实现，Alpaca让你可以使用算法进行交易、与应用程序连接并通过免佣金的股票交易API构建服务。
* [IBC](https://github.com/IbcAlpha/IBC)：IBC可以自动化运行盈透证券交易者工作站和网关的许多方面。
* [Billy](https://github.com/premium-minds/billy)：Billy是一个应用程序计费库，为应用程序提供创建、管理和存储计费工件(例如发票和贷方票据)的能力。
* [Mustang](https://github.com/ZUGFeRD/mustangproject)：Mustang使你能够读取、写入和验证(例如重新计算)机器可读的发票、订单或交货通知。
* [Java_NFe](https://github.com/Samuel-Oliveira/Java_NFe)：用于使用NFe/NFCe WebService的Java库。

## 短信

* [Twilio Java](https://github.com/twilio/twilio-java)：用于与Twilio REST API通信并生成TwiML的Java库。
* [SMS4J](https://gitee.com/dromara/sms4j)：SMS4J为短信聚合框架，可以轻松集成多家短信服务，解决接入多个短信SDK的繁琐流程。
* [Guerlab](https://gitee.com/guerlab_net/guerlab-sms)：基于Spring Boot的短信服务支持，通过引用不同的Starter启用不同的短信通道支持，支持多通道下的负载均衡，支持同步/异步方式发送。
* [SMSGate](https://github.com/Lihuanghe/SMSGate)：在Netty 4框架下实现的三网合一短信网关核心框架。
* [SMSCGateway](https://github.com/RestComm/smscgateway)：SMSC用于向移动运营商网络(GSM、SS7 MAP)、SMS聚合器(SMPP)和互联网电话服务提供商(SIP、SMPP)发送/接收SMS。
* [SMS](https://github.com/yunpian/sms)：云通讯、国际短信、短信SDK。

## DSL

* [Eclipse Xtend](https://github.com/eclipse/xtext-xtend)：Eclipse Xtext是一个用于开发编程语言和DSL的框架。
* [MyBatis Dynamic SQL](https://github.com/mybatis/mybatis-dynamic-sql)：适用于Kotlin和Java的SQL DSL，支持MyBatis或Spring JdbcTemplate的渲染。
* [JMeter DSL](https://github.com/abstracta/jmeter-java-dsl)：使用JMeter作为引擎，以Git和程序员友好的方式运行性能测试的简单Java API。
* [ElasticSearch SQL](https://github.com/iamazy/elasticsearch-sql)：使用Antlr4将SQL解析为ElasticSearch DSL。
* [JBBP](https://github.com/raydac/java-binary-block-parser)：在Java和Android中处理二进制数据的最舒适和动态的方式。
* [Neo4j Cypher DSL](https://github.com/neo4j-contrib/cypher-dsl)：用于Cypher查询语言的Java DSL。
* [Structurizr DSL](https://github.com/structurizr/dsl)：此项目包含Structurizr DSL的实现-一种使用DSL基于C4 Model创建Structurizr软件架构模型的方法。
* [DeepDSL](https://github.com/deepdsl/deepdsl)：DeepDSL是一种嵌入在Scala中的DSL，用于编写深度学习网络应用程序。
* [MontiCore](https://github.com/MontiCore/monticore)：MontiCore是一个用于高效开发DSL的语言工作，它处理定义DSL的扩展语法格式并生成用于处理DSL文档的Java组件。
* [Rosetta](https://github.com/REGnosys/rosetta-dsl)：Rosetta是一种DSL，支持金融市场行业的操作流程建模。
* [WebDSL](https://github.com/webdsl/webdsl)：WebDSL是一种特定于领域的语言，用于使用丰富的数据模型对Web应用程序进行建模。

## JMX

* [Simple JMX](https://github.com/j256/simplejmx)：JMX Java库可帮助使用JMX和Web发布对象。
* [JMXUtils](https://github.com/martint/jmxutils)：让导出JMX mbean变得容易。

## RMI

* [Dirmi](https://github.com/cojen/Dirmi)：Dirmi是Java RMI的替代品，支持双向远程对象。
* [JrPip](https://github.com/goldmansachs/jrpip)：JrPip使用Java二进制序列化协议提供远程方法调用，由高盛银行开源。
* [SerializationDumper](https://github.com/NickstaDB/SerializationDumper)：一种以更易于理解的形式转储和重建Java序列化流和Java RMI数据包内容的工具。

## gRPC

* [Wire](https://github.com/square/wire)：适用于Android、Kotlin、Swift和Java的gRPC和协议缓冲区，Square开源。
* [JProtobuf](https://github.com/jhunters/jprotobuf)：JProtobuf是针对Java程序开发的一套简易类库，目的是简化Java语言对protobuf类库的使用，百度开源。
* [Polyglot](https://github.com/grpc-ecosystem/polyglot)：Polyglot是一个gRPC客户端，可以与任何gRPC服务器通信。
* [Milkman](https://github.com/warmuuh/milkman)：Postman的可扩展替代方案，用于制作各种请求，不仅适用于gRPC，还适用于HTTP、SQL等。
* [Gatling-gRPC](https://github.com/phiSgr/gatling-grpc)：gRPC的Gating负载测试插件
* [Karate-gRPC](https://github.com/pecker-io/karate-grpc)：提供使用Karate测试gRPC的通用方法。
* [gRPC-Swagger](https://github.com/grpc-swagger/grpc-swagger)：使用Swagger-UI调试gRPC应用程序。
* [Mediator](https://github.com/ButterCam/Mediator)：gRPC调试代理跨平台GUI。
* [Google API Extensions Java](https://github.com/googleapis/gax-java)：适用于Java的Google API扩展。
* [gRPC-Java-Contrib](https://github.com/salesforce/grpc-java-contrib)：grpc-java库的有用扩展。
* [QuickBuffers](https://github.com/HebiRobotics/QuickBuffers)：QuickBuffers是Google Protocol Buffers的Java实现，专为零分配环境中的低延迟用例而开发。
* [Sisyphus](https://github.com/ButterCam/sisyphus)：基于JVM的现代gRPC后端开发框架。
* [nrtSearch](https://github.com/Yelp/nrtsearch)：基于Apache Lucene的高性能gRPC服务器。

## Raft算法

* [KRaft](https://github.com/apache/kafka/tree/trunk/raft)：KRaft是基于Raft共识协议为Apache Kafka量身定制的协议。
* [SOFAJRaft](https://github.com/sofastack/sofa-jraft)：SOFAJRaft是基于RAFT一致性算法的生产级高性能Java实现，支持MULTI-RAFT-GROUP，适用于高负载、低延迟的场景，由蚂蚁开源。
* [Raft Java](https://github.com/wenweihu86/raft-java)：Raft算法的简单Java实现。
* [Apache Ratis](https://github.com/apache/ratis)：Apache Ratis是一个实现Raft协议的Java库。
* [Dledger](https://github.com/openmessaging/dledger)：Dledger是一个基于Raft的Java库，用于构建高可用、高持久、强一致的提交日志。
* [Lu-Raft-KV-Storage](https://github.com/stateIs0/lu-raft-kv)：这是一个Java版本的Raft KV分布式存储实现。
* [Copycat](https://github.com/atomix/copycat)：Raft一致性算法的新颖实现。
* [jGroups Raft](https://github.com/jgroups-extras/jgroups-raft)：jGroups Raft是Raft共识算法在JGroups中的实现。
* [xRaft](https://github.com/xnnyygn/xraft)：简单的Raft共识算法实现。
* [jRaft](https://github.com/datatechnology/jraft)：简单的Raft共识算法实现。
* [Barge](https://github.com/mgodave/barge)：Raft共识协议的JVM实现。
* [LibRaft](https://github.com/allengeorge/libraft)：LibRaft是一个实现Raft分布式共识协议的Java库。
* [MicroRaft](https://github.com/MicroRaft/MicroRaft)：MicroRaft是Raft共识算法在Java中功能完整且稳定的开源实现。

## Paxos算法

* [WPaxos](https://github.com/wuba/WPaxos)：Paxos共识算法的生产级Java实现，由58同城开源。
* [WLock](https://github.com/wuba/WLock)：基于共识算法组件WPaxos的高可靠、高吞吐量的分布式锁服务，由58同城开源。
* [Klein](https://github.com/shihuili1218/klein)：Klein是一个基于Paxos的分布式集合工具库，包括分布式Cache、分布式消息队列、分布式List、分布式Map、分布式Lock等。
* [Paxos](https://github.com/jaksa76/paxos)：Paxos算法的Java实现。
* [URingPaxos](https://github.com/sambenz/URingPaxos)：高吞吐量原子多播协议。
* [PaxosImpl](https://github.com/hellolinjx/PaxosImpl)：Paxos算法的多线程实现。

## 对象池

* [Stormpot](https://github.com/chrisvest/stormpot)：Stormpot是一个Java对象池库。
* [Apache Commons Pool](https://github.com/apache/commons-pool)：Apache Commons Pool库提供了对象池API和许多对象池实现。
* [Fast Object Pool](https://github.com/DanielYWoo/fast-object-pool)：FOP是一个针对并发访问进行优化的轻量级高性能对象池。
* [PooledJMS](https://github.com/messaginghub/pooled-jms)：用于消息传递应用程序的JMS连接池，为JMS连接、会话和消息生产者提供池化。
* [Vibur Object Pool](https://github.com/vibur/vibur-object-pool)：Vibur对象池是一个通用并发Java对象池，完全使用标准Java并发实用程序构建，不使用任何同步块或方法，并且没有任何外部依赖项。
* [LitePool](https://github.com/nextopcn/lite-pool)：由Java编写的精简版快速对象池。

## CQRS框架

* [JdonFramework](https://github.com/banq/jdonframework)：JdonFramework是一个支持Pub-Sub异步编程模型的领域事件框架。
* [Reveno](https://github.com/dmart28/reveno)：Reveno是一款彻底的、快如闪电、耐用且简单的基于JVM的异步事务处理框架。
* [Splitet](https://github.com/Splitet/SplitetFramework)：Splitet是一个基于Java的事件溯源框架，计划以最小的学习曲线和易于适应的方式进行CQRS转换的团队可以从中受益。
* [Loom](https://github.com/loom/loom-java)：Loom是一组用于实现分布式消息传递和事件源模式的框架。
* [Sourcerer](https://github.com/elder-oss/sourcerer)：Sourcerer是一个固执己见、功能性且与存储无关的框架，用于使用事件源在Java 8中实现CQRS架构。
* [Apache Polygene](https://github.com/apache/polygene-java)：Java平台上的面向组合编程。
* [Dewdrop](https://github.com/matsientst/dewdrop)：Dewdrop是一个固执己见、简单而强大的框架，用于在Java中实现事件源。
* [ES4j](https://github.com/eventsourcing/es4j)：Java的事件捕获和查询框架。
* [PipelinR](https://github.com/sizovs/pipelinr)：用于通过管道使用处理程序和命令的小型实用程序库。
* [Assembler](https://github.com/pellse/assembler)：Assembler是一个响应式、函数式、类型安全和无状态的数据聚合框架，用于查询和合并来自多个数据源/服务的数据。
* [Occurrent](https://github.com/johanhaleby/occurrent)：Occurrent是一个基于云事件规范的事件溯源库。
* [Concursus](https://github.com/opencredo/concursus)：Concursus是一个Java 8框架，用于构建使用CQRS和事件源模式以及Cassandra事件日志实现的应用程序。
* [Thoth](https://github.com/MAIF/thoth)：Thoth是一个Java库，它提供了在应用程序中实现事件源的工具包。
* [Fluxtion](https://github.com/v12technology/fluxtion)：Fluxtion是一种Java开发生产力工具，使编写和维护事件驱动的业务逻辑变得更便宜、更快捷。
* [Synapse](https://github.com/otto-de/synapse)：实现事件溯源微服务的库。
* [Wow](https://github.com/Ahoo-Wang/Wow)：现代响应式CQRS架构，基于DDD和事件溯源的微服务开发框架。
* [Deezpatch](https://github.com/joel-jeremy/deezpatch)：简单、轻量级且高性能的调度库，用于解耦消息(请求和事件)和消息处理程序。
* [FactCast](https://github.com/factcast/factcast)：基于PostgreSQL的简单EventStore。

## DDD框架

* [Axon](https://github.com/AxonFramework/AxonFramework)：Axon是一个基于DDD、CQRS和事件溯源原则构建渐进式事件驱动微服务系统的框架。
* [Library](https://github.com/ddd-by-examples/library)：全面的领域驱动设计示例，包含问题空间战略分析和各种战术模式。
* [DDDplus](https://github.com/funkygao/cp-ddd-framework)：DDDplus是一个轻量级的DDD正向/逆向业务建模增强框架，支持复杂的系统架构演进。
* [Dante Cloud](https://gitee.com/dromara/dante-cloud)：Dante Cloud是企业级微服务架构和服务能力开发平台。
* [ContextMapper](https://github.com/ContextMapper/context-mapper-dsl)：ContextMapper是一个开源项目，为战略领域驱动设计、上下文映射、有界上下文建模和服务分解提供领域特定语言和工具。
* [Apache Causeway](https://github.com/apache/causeway)：Apache Causeway是一个用Java快速开发领域驱动应用程序的框架。
* [DDDLib](https://github.com/dayatang/dddlib)：DDDLib是一个领域驱动设计类库。
* [DDD Base](https://github.com/linux-china/ddd-base)：Java领域驱动设计基础包。
* [Spine Event Engine](https://github.com/SpineEventEngine/core-java)：Spine Event Engine是一个Java框架，用于构建事件源和CQRS应用程序。
* [Jexxa](https://github.com/jexxa-projects/Jexxa)：Jexxa是一个轻量级框架，可使用DDD来简化持久业务应用程序的实现。
* [SpringBoot-DDD](https://github.com/codingapi/springboot-framework)：基于Spring Boot为提供领域驱动设计与事件风暴开发落地，提供的范式开源框架。
* [Cheddar](https://github.com/travel-cloud/Cheddar)：Cheddar是一个Java框架，适用于AWS上的企业应用程序，使用域驱动设计(DDD)。
* [ZenWave SDK](https://github.com/ZenWave360/zenwave-sdk)：ZenWave SDK是一个用于DDD和API优先的可配置且可扩展的工具包，可以从不同模型的组合生成代码。

## 软件工程

* [COLA](https://github.com/alibaba/COLA)：COLA代表整洁面向对象分层架构，由阿里开源。
* [jMolecules](https://github.com/xmolecules/jmolecules)：可帮助开发人员以无干扰、简单的旧式Java实现域模型的一组库。
* [Rosie](https://github.com/Karumi/Rosie)：Rosie是一个Android框架，用于创建遵循清洁架构原则的应用程序。
* [Eclipse Capella](https://github.com/eclipse/capella)：Eclipse Capella是一款全面、可扩展且经过现场验证的MBSE工具和方法，可用于成功设计系统架构，由Thales开源。
* [Structurizr](https://c4model.com/)：Structurizr打破了架构图编辑器(例如UML)的传统拖放方法，并允许我们使用我们最了解的工具Java来描述我们的架构工件。
* [Spring Modulith](https://github.com/spring-projects/spring-modulith)：Spring Modulith允许开发人员构建结构良好的Spring Boot应用程序，并指导开发人员查找和使用由领域驱动的应用程序模块。
* [Moduliths](https://github.com/moduliths/moduliths)：Moduliths是用于构建模块化、整体式Spring Boot应用程序的框架。
* [ArchGuard](https://github.com/archguard/archguard)：ArchGuard是一个针对于微服务下的架构工作台/治理工具，它可以帮助架构师、开发人员进行架构自助，自定义架构的洞察、分析系统间的远程服务依赖情况、数据库依赖、API依赖等。
* [Structurizr Java](https://github.com/structurizr/java)：Structurizr基于“图即代码”构建，允许你从单个模型创建多个软件架构图。
* [JRugged](https://github.com/Comcast/jrugged)：JRugged库实现了用Java构建健壮的、可用于生产的服务器代码所需的一些常见模式，由Comcast开源。
* [RR](https://github.com/GuntherRademacher/rr)：RR是语法图生成器(也称为铁路图)，它是一个独立的工具，具有基于浏览器的GUI和批处理模式。
* [JIG](https://github.com/dddjava/jig)：JIG是一个支持代码设计的工具。
* [RRDiagram](https://github.com/Chrriis/RRDiagram)：RR图是一个Java库，可从代码或BNF表示法生成铁路图。
* [VMF](https://github.com/miho/VMF)：VMF是一个轻量级的建模框架，它可以方便地将带注解的Java接口转换为功能强大的实现。
* [Umple](https://github.com/umple/umple)：Umple是一种面向模型的编程技术，允许开发人员在传统代码中嵌入建模概念(例如UML 关联、状态机)、模式、生成模板和其他抽象，反之亦然，由渥太华大学开源。
* [Lowfer](https://github.com/mbouchenoire/lowfer)：Lowfer是一个简单的工具，可以帮助软件工程师和架构师记录、讨论和分析软件设计和架构。
* [FJage](https://github.com/org-arl/fjage)：FJage为Java和Groovy中面向代理的软件开发提供了一个轻量级且易于学习的平台，由新加坡国立大学开源。
* [JSyntrax](https://github.com/atp-mipt/jsyntrax)：JSyntrax是一个铁路图生成器，它创建了用于编程语言的语法的直观说明，由莫斯科物理技术学院开源。

## 设计模式

* [Apache Commons Chain](https://github.com/apache/commons-chain)：GoF责任链模式的实现。
* [Apache Commons Proxy](https://github.com/apache/commons-proxy)：用于动态代理的Java库。
* [Decorator](https://github.com/eyeem/decorator)：动态继承库，装饰器模式的实现。
* [AutoProxy](https://github.com/OleksandrKucherenko/autoproxy)：在接口/抽象类之上生成代理类，允许拦截调用。

## 幂等处理

* [Idempotent](https://github.com/it4alla/idempotent)：幂等处理方案。
* [Idempotent Spring Boot Starter](https://github.com/pig-mesh/idempotent-spring-boot-starter)：对原有idempotent代码重构和功能增强。
* [Jdempotent](https://github.com/Trendyol/Jdempotent)：轻松使你的端点幂等，由Trendyol开源。
* [Idempotence4j](https://github.com/transferwise/idempotence4j)：Idempotence4j是一个轻量级库，为处理幂等操作提供支持。
* [Quidem](https://github.com/julianhyde/quidem)：Quidem是一个幂等查询执行器。
* [Tomato](https://github.com/lxchinesszz/tomato)：Tomato是一款专门为Spring Boot项目设计的幂等组件。

## 数据字典

* [Dict Trans](https://gitee.com/aizuda/dict-trans)：由爱组搭开源的简单字典翻译组件。
* [Transformer](https://github.com/luo-zhan/Transformer)：Transformer是一款功能全面的字段转换工具，只需要几个简单的注解，让开发更简单。

## 迁移&重构

* [EMT4J](https://github.com/adoptium/emt4j)：EMT4J是一个旨在简化Java版本迁移的项目，由阿里开源。
* [Rewrite](https://github.com/openrewrite/rewrite)：OpenRewrite项目是一个源代码自动重构生态系统，使开发人员能够有效消除其仓库中的技术债务，由Netflix开源。
* [Spring Boot Migrator](https://github.com/spring-projects-experimental/spring-boot-migrator)：Spring Boot Migrator旨在通过提供自动迁移的方法来帮助开发人员升级或迁移到Spring Boot。
* [Windup](https://github.com/windup/windup)：Windup是一个工具集，支持跨广泛转换和用例的大规模Java应用程序现代化和迁移项目，由RedHat开源。
* [Jakarta Migration](https://github.com/apache/tomcat-jakartaee-migration)：该工具的目的是自动对为Java EE 8编写并在Tomcat 9上运行的Web应用程序进行转换，以便可以在实现Jakarta EE 9的Tomcat 10上运行。
* [Scientist4J](https://github.com/rawls238/Scientist4J)：Github重构工具Scientist的Java移植。
* [RefactoringMiner](https://github.com/tsantalis/RefactoringMiner)：RefactoringMiner是一个用Java编写的库/API，可以检测Java项目历史中应用的重构。
* [Eclipse Transformer](https://github.com/eclipse/transformer)：Eclipse Transformer提供了转换Java二进制文件的工具和运行时组件，将更改映射到Java包、类名称和相关资源名称，由Open Liberty团队开源。
* [Butterfly](https://github.com/paypal/butterfly)：Butterfly是一种应用程序代码转换工具，通常用于执行自动化应用程序迁移、升级以及源代码和配置更改，由Paypal开源。
* [MigrationMiner](https://github.com/hussien89aa/MigrationMiner)：MigrationMiner是检测两个Java第三方库之间迁移代码的工具。
* [Astra](https://github.com/alfasoftware/astra)：Astra是一个用于分析和重构Java源代码的Java工具。

## Bot

* [JMusicBot](https://github.com/jagrosh/MusicBot)：JMusicBot是一个可以轻松设置和运行的Discord音乐机器人。
* [Mirai](https://github.com/mamoe/mirai)：Mirai是一个在全平台下运行，提供QQ Android协议支持的高效率机器人库。
* [OpenShamrock](https://github.com/whitechi73/OpenShamrock)：OpenShamrock是基于Xposed实现OneBot标准的QQ机器人框架。
* [TelegramBots](https://github.com/rubenlagus/TelegramBots)：使用Telegram Bots API创建机器人的Java库。
* [JDA](https://github.com/discord-jda/JDA)：该开源库旨在使用实时网关和REST API在Discord上实现机器人。
* [Discord4J](https://github.com/Discord4J/Discord4J)：Discord4J是一个快速、强大、无偏见的响应式库，可使用官方Discord Bot API快速轻松地开发适用于Java、Kotlin和其他JVM语言的Discord机器人。
* [Java Telegram Bot API](https://github.com/pengrad/java-telegram-bot-api)：用于Java的Telegram Bot API。
* [JBot](https://github.com/rampatra/jbot)：JBot是一个Java框架，可在几分钟内创建Slack和Facebook机器人。
* [Tock](https://github.com/theopenconversationkit/tock)：Tock是一个完整且开放的平台，用于构建对话代理(也称为机器人)。
* [R-Bot](https://github.com/semicons/java_oci_manage)：应用于甲骨文云/Azure云的一些快捷操作。
* [Javacord](https://github.com/Javacord/Javacord)：一个易于使用的多线程库，用于在Java中创建Discord机器人。
* [PhantomBot](https://github.com/PhantomBot/PhantomBot)：PhantomBot是一款积极开发的开源交互式Twitch机器人。
* [GiveawayBot](https://github.com/jagrosh/GiveawayBot)：在Discord服务器上快速轻松地保存赠品。
* [Line Message SDK](https://github.com/line/line-bot-sdk-java)：适用于Java的LINE Messaging API SDK可以轻松使用LINE Messaging API开发机器人，并且可以在几分钟内创建示例机器人。
* [BotLibre](https://github.com/BotLibre/BotLibre)：适用于人工智能、聊天机器人、虚拟代理、社交媒体自动化和实时聊天自动化的开放平台。
* [Vortex](https://github.com/jagrosh/Vortex)：Discord审核机器人。
* [Jeeves](https://github.com/kanjielu/jeeves)：一个智能微信机器人。
* [Repairnator](https://github.com/eclipse/repairnator)：Github上的软件机器人开源平台。
* [EDDI](https://github.com/labsai/EDDI)：用于对话式AI API(例如ChatGPT)的提示和对话管理中间件。
* [MantaroBot](https://github.com/Mantaro/MantaroBot)：使用JDA用Java制作的多用途Discord机器人。
* [TradeBot](https://github.com/markusaksli/TradeBot)：使用Binance API的加密货币交易机器人。
* [WeChat Robot](https://gitee.com/hellokaton/wechat-robot)：Java版微信普通号机器人。
* [dwBot](https://gitee.com/dullwolf/dwBot)：一款可以实现指令读取的QQ机器人。
* [Sokobot](https://github.com/PolyMarsDev/Sokobot)：一个可以玩推箱子的Discord机器人。
* [AIODE](https://github.com/robinfriedli/aiode)：可播放Spotify曲目和YouTube视频或任何URL(包括Soundcloud链接和Twitch流)的Discord机器人。
* [JDA-Utilities](https://github.com/JDA-Applications/JDA-Utilities)：JDA协助创建机器人的一系列工具和实用程序。
* [Messenger4j](https://github.com/messenger4j/messenger4j)：用于在Facebook Messenger平台上构建聊天机器人的Java库。
* [TDLight Java](https://github.com/tdlight-team/tdlight-java)：基于TDLib的完整Bot和Userbot Telegram库。
* [春松客服](https://github.com/cskefu/cskefu)：春松客服是开源的智能客服系统。
* [Microsoft Bot Framework Java SDK](https://github.com/microsoft/botbuilder-java)：Microsoft Bot Framework提供了构建和连接智能机器人所需的功能，无论用户在哪里交谈，这些机器人都可以自然地交互，从文本/短信到Skype、Slack、Office 365邮件和其他流行服务。
* [Chuu](https://github.com/ishwi/Chuu)：一个Discord机器人，将Last.fm与Discord集成。
* [Mutters](https://github.com/rabidgremlin/Mutters)：构建机器人大脑的框架。
* [WeChatBotEngine](https://github.com/moontide/WeChatBotEngine)：基于微信网页版HTTP协议的机器人引擎。
* [FeishuBot](https://github.com/rawchen/FeishuBot)：飞书群聊/私聊ChatGPT机器人。
* [PokuBot](https://github.com/norecha/pokubot)：部落冲突机器人。
* [Command-Flow](https://github.com/FixedDev/command-flow)：适用于Java 8+的灵活且与平台无关的命令框架。
* [Ree6](https://github.com/Ree6-Applications/Ree6)：Ree6是一款由Presti维护的一体化Discord机器人。
* [Spectra](https://github.com/jagrosh/Spectra)：Spectra是一款私人、多用途、娱乐性和实用性的Discord机器人。
* [Shiro](https://github.com/MisakaTAT/Shiro)：基于OneBot协议的QQ机器人快速开发框架。
* [Simple Robot](https://github.com/simple-robot/simpler-robot)：Simple Robot是一个基于Kotlin协程的多平台Bot风格高性能异步事件调度框架，异步高效、Java友好。

## 安卓库

* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)：强大的Android图表视图/图形视图库，支持折线图、饼图、雷达图、气泡图和烛台图以及缩放、平移和动画。
* [Lottie](https://github.com/airbnb/lottie-android)：适用于Android和iOS的移动库，它可以解析使用Bodymovin导出为JSON的Adobe After Effects动画，并在移动设备上本地渲染它们，由Airbnb开源。
* [VasDolly](https://github.com/Tencent/VasDolly)：VasDolly是一种快速多渠道打包工具，同时支持基于V1签名和V2、V3签名进行多渠道打包，由腾讯开源。
* [Glide](https://github.com/bumptech/glide)：快速高效的Android开源媒体管理和图像加载框架，它将媒体解码、内存和磁盘缓存以及资源池封装到一个简单易用的界面中。
* [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)：该库封装了Android开发中常用的功能，有完整的Demo和单元测试。
* [Butter Knife](https://github.com/JakeWharton/butterknife)：将Android视图和回调绑定到字段和方法。
* [MIT App Inventor](https://github.com/mit-cml/appinventor-sources)：App Inventor是一款Google开发的手机编程软件，现由MIT开发维护。
* [NewPipe](https://github.com/TeamNewPipe/NewPipe)：适用于Android的自由轻量级流媒体前端。
* [Termux](https://github.com/termux/termux-app)：Android终端应用程序和Linux环境。
* [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)：SmartRefreshLayout以打造一个强大、稳定、成熟的下拉刷新框架为目标，并集成各种的炫酷、多样、实用、美观的Header和Footer。
* [Freeline](https://github.com/alibaba/freeline)：Android超快速构建工具，Instant Run的替代品，由阿里开源。
* [Signal Android](https://github.com/signalapp/Signal-Android)：简单、强大且安全的信使。
* [Telegram](https://github.com/DrKLO/Telegram)：一款注重速度和安全性的消息应用程序。
* [ExoPlayer](https://github.com/google/ExoPlayer)：适用于Android的可扩展媒体播放器，由Google开源。
* [RxAndroid](https://github.com/ReactiveX/RxAndroid)：适用于Android的RxJava绑定。
* [DoKit](https://github.com/didi/DoKit)：一款面向泛前端产品研发全生命周期的效率平台，由滴滴开源。
* [Walle](https://github.com/Meituan-Dianping/walle)：Android Signature V2 Scheme签名下的新一代渠道包打包神器，由美团开源。
* [Telescope](https://github.com/mattprecious/telescope)：一个简单的工具，可以在你的应用程序中轻松捕获错误报告。
* [PhotoView](https://github.com/Baseflow/PhotoView)：Android版ImageView的实现，支持通过各种触摸手势进行缩放。
* [ApkAnalyser](https://github.com/sonyxperiadev/ApkAnalyser)：ApkAnalyser是一种静态虚拟分析工具，用于检查和验证Android应用程序的开发工作，由索尼开源。
* [Fresco](https://github.com/facebook/fresco)：用于管理图像及其使用的内存的Android库，由Facebook开源。
* [Tinker](https://github.com/Tencent/tinker)：Android的热修复解决方案库，它支持dex、库和资源更新，无需重新安装apk，由腾讯开源。
* [Material Components Android](https://github.com/material-components/material-components-android)：适用于Android的模块化和可定制的Material Design UI组件。
* [VirtualXposed](https://github.com/android-hacker/VirtualXposed)：无需Root即可使用Xpose，解锁引导加载程序或修改系统镜像等。
* [CircleImageView](https://github.com/hdodenhof/CircleImageView)：快速的圆形ImageView，非常适合个人资料图像。
* [ARouter](https://github.com/alibaba/ARouter)：帮助Android APP进行组件化改造的路由框架，由阿里开源。
* [QMUI_Android](https://github.com/Tencent/QMUI_Android)：提高Android UI开发效率的UI库，由腾讯开源。
* [StringFog](https://github.com/MegatronKing/StringFog)：一款自动对字节码中的字符串进行加密Android插件工具。
* [JsBridge](https://github.com/lzyzsd/JsBridge)：Android Java和JavaScript的桥梁。
* [Phrase](https://github.com/square/phrase)：Android字符串资源模板库。
* [Stetho](https://github.com/facebookarchive/stetho)：Android应用程序的调试桥，支持强大的Chrome开发者工具等，由Facebook开源。
* [SmartTube](https://github.com/yuliskov/SmartTubeNext)：适用于运行Android操作系统的机顶盒和电视的高级播放器。
* [Matisse](https://github.com/zhihu/Matisse)：精心设计的Android本地图像和视频选择器，由知乎开源。
* [QtScrcpy](https://github.com/barry-ran/QtScrcpy)：Android实时显示控制软件。
* [LSPosed](https://github.com/LSPosed/LSPosed)：Xpose是一个模块框架，可以在不接触任何APK的情况下更改系统和应用程序的行为。
* [VasSonic](https://github.com/Tencent/VasSonic)：腾讯VAS团队开发的一款轻量级、高性能的Hybrid框架，旨在加速Android和iOS平台上的网站首屏速度。
* [uCrop](https://github.com/Yalantis/uCrop)：Android图像裁剪库。
* [Dex2Jar](https://github.com/pxb1988/dex2jar)：用于处理Android .dex和Java .class文件的工具。
* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)：用于处理Android运行时权限的声明式API。
* [DanmakuFlameMaster](https://github.com/bilibili/DanmakuFlameMaster)：Android上开源弹幕解析绘制引擎项目，由B站开发。
* [APK Parser](https://github.com/hsiafan/apk-parser)：APK解析库，用于解码二进制XML文件，获取APK元信息。
* [Epoxy](https://github.com/airbnb/epoxy)：用于在RecyclerView中构建复杂的屏幕，由Airbnb开源。
* [Atlas](https://github.com/alibaba/atlas)：一个强大的Android动态组件框架，由阿里开源。
* [Litho](https://github.com/facebook/litho)：用于在Android上构建高效UI的声明式框架，由Facebook开源。
* [RePlugin](https://github.com/Qihoo360/RePlugin)：一个灵活、稳定、易用的Android插件框架，由360开源。
* [Shadow](https://github.com/Tencent/Shadow)：零反射全动态Android插件框架，由腾讯开源。
* [Robust](https://github.com/Meituan-Dianping/Robust)：一款高兼容性、高稳定性的Android HotFix解决方案，由美团开源。
* [MagicaSakura](https://github.com/bilibili/MagicaSakura)：Android多主题框架，由B站开源。
* [Bundletool](https://github.com/google/bundletool)：操作Android App Bundle和Android SDK Bundle的工具，由Google开源。
* [Andromeda](https://github.com/iqiyi/Andromeda)：Andromeda为本地和远程服务提供模块之间的通信，由爱奇艺开发。

## GUI开发工具

这里列出了Java中常用的Swing、JavaFX开发库，以及一些Java开发的GUI工具和游戏引擎。

#### GUI框架

* [Swing](https://docs.oracle.com/en/java/javase/21/docs/api/java.desktop/javax/swing/package-summary.html)：Swing提供一组轻量级组件，可以在所有平台上以相同的方式工作。
* [OpenJFX](https://github.com/openjdk/jfx)：OpenJFX是一个开源的客户端应用程序平台，适用于基于Java SE的桌面、移动和嵌入式系统，Oracle开源。
* [Eclipse SWT](https://github.com/eclipse-platform/eclipse.platform.swt)：SWT是一个用于Java的开源小部件工具包，由IBM开源。
* [AWT](https://docs.oracle.com/en/java/javase/21/docs/api/java.desktop/java/awt/package-summary.html)：AWT是Java最初的依赖于平台的窗口、图形和用户界面小部件工具包，早于Swing。
* [Yoga](https://github.com/facebook/yoga)：Yoga是一个可嵌入的高性能Flexbox布局引擎，具有多种语言的绑定，由Facebook开源。
* [SwingX](https://github.com/arotenberg/swingx)：基于Swing，其使命是为Swing创建丰富的组件。
* [TotalCross](https://github.com/TotalCross/totalcross)：TotalCross是一款帮助跨平台应用程序开发的工具包。
* [NetBeans Platform](https://netbeans.apache.org/tutorial/main/kb/docs/platform/)：NetBeans Platform是一个广泛的Java框架，可以在其上构建大型桌面应用程序。
* [JGoodies](https://www.jgoodies.com/)：JGoodies提供免费软件、产品、设计和服务，帮助你高效地使用Java桌面。
* [QtJambi](https://github.com/OmixVisualization/qtjambi)：QtJambi是Java编程语言的Qt绑定，最初由Qt公司的前身Trolltech开发。
* [Apache Pivot](https://github.com/apache/pivot)：Apache Pivot是一个用Java构建丰富互联网应用程序的平台，其中WTK工具包是它的图形组件，由VMware开源。
* [TeaVM-Flavour](https://github.com/konsoletyper/teavm-flavour)：使用TeaVM编写客户端应用程序的框架。

#### Swing

* [Lanterna](https://github.com/mabe02/lanterna)：Lanterna是一个Java库，允许你在纯文本环境中编写简单的半图形用户界面，与C库curses非常相似，但具有更多功能。
* [RSyntaxTextArea](https://github.com/bobbylight/RSyntaxTextArea)：RSyntaxTextArea是一个用于Java Swing应用程序的可定制的语法突出显示文本组件。
* [Radiance](https://github.com/kirill-grouchnikov/radiance)：Radiance是一个库集合，用于基于Ephemeral设计系统编写现代、优雅且快速的Swing应用程序。
* [JxCapture](https://teamdev.com/jxcapture/)：JxCapture是一种跨平台、能Java应用程序提供综合屏幕抓取API的库程序。
* [SystemTray](https://github.com/dorkbox/SystemTray)：对Java 8+上的Swing/AWT、GtkStatusIcon和AppIndicator提供专业、跨平台的SystemTray支持。
* [DJ Native Swing](https://github.com/Chrriis/DJ-Native-Swing)：DJ Native Swing库允许将一些原生组件轻松集成到Swing应用程序中，并提供一些本机实用程序来增强Swing的API。
* [AutoComplete](https://github.com/bobbylight/AutoComplete)：AutoComplete是Swing JTextComponents的代码完成库，具有可用于RSyntaxTextArea实例的增强功能。
* [Chromium](https://github.com/equodev/chromium)：Equo Chromium Community小部件是一个跨平台浏览器，允许用户在Java应用程序内创建和呈现基于Web的现代UI。
* [jSystemThemeDetector](https://github.com/Dansoftowner/jSystemThemeDetector)：用于检测(桌面)操作系统是否使用深色UI主题的Java库。
* [Sierra](https://github.com/HTTP-RPC/Sierra)：Sierra是一个用于简化Java Swing应用程序开发的开源框架。
* [Cinch](https://github.com/palantir/Cinch)：管理MVC模式的组件操作/事件绑定的Java库，由Palantir开源。
* [jGAF](https://github.com/pgdurand/jGAF)：jGAF是一个旨在促进为Java平台创建跨平台图形应用程序的库。
* [Projector Server](https://github.com/JetBrains/projector-server)：用于远程运行Swing应用程序的服务器端库，由JetBrains开源。
* [ReflectionUI](https://github.com/dotxyteam/ReflectionUI)：基于Java反射的GUI构建器/生成器。

#### Swing主题库

* [FlatLaf](https://github.com/JFormDesigner/FlatLaf)：FlatLaf是Java Swing桌面应用程序的现代开源跨平台LaF。
* [BeautyEye](https://github.com/JackJiang2011/beautyeye)：BeautyEye是一款Java Swing跨平台外观实现。
* [Jewel](https://github.com/JetBrains/jewel)：Jewel旨在在Compose Desktop中重新创建IntelliJ平台的新UI Swing LaF，提供桌面优化的主题和组件集，由JetBrains开源。
* [WebLaf](https://github.com/mgarin/weblaf)：WebLaf是一个完全开源的外观和组件库，用纯Java编写，用于跨平台桌面Swing应用程序。
* [Darklaf](https://github.com/weisJ/darklaf)：Darklaf是基于Darcula-Laf的主题LaF。
* [VAqua](https://github.com/violetlib/vaqua)：VAqua是一种Java Swing外观，在macOS上运行，模拟标准macOS UI组件的外观和行为。
* [KControls](https://github.com/k33ptoo/KControls)：用于美化用户界面并赋予UI现代化的外观。
* [VTerminal](https://github.com/Valkryst/VTerminal)：用于Java的新LaF，允许基于网格显示具有自定义前景色/背景色、字体大小和伪着色器的Unicode字符。
* [Darcula](https://github.com/bulenkov/Darcula)：Darcula是Java桌面应用程序的LaF和代码编辑器主题。
* [Synthetica](https://www.jyloo.com/)：Synthetica是Swing的LaF，基于Synth，通过主题为Swing的核心组件提供了许多不同的外观，包括圆形边框、阴影弹出菜单和漂亮的图标。

#### Swing UI库

* [Material-UI-Swing](https://github.com/atarw/material-ui-swing)：适用于Java Swing的现代Material Design UI。
* [Swing9patch](https://github.com/JackJiang2011/Swing9patch)：Swing9patch工程是一组很酷的Java Swing可重用组件或UI效果。
* [SnapKit](https://github.com/reportmill/SnapKit)：SnapKit是一个现代Java UI库和工具，用于创建丰富的Java客户端应用程序。
* [ImGui](https://github.com/kotlin-graphics/imgui)：这是ImGui的Kotlin重写，一个用于C++的无膨胀图形用户界面库。
* [Lemur](https://github.com/jMonkeyEngine-Contributions/Lemur)：Lemur是用于在jMonkeyEngine应用程序中制作用户界面的GUI工具包。
* [Griffon](https://github.com/griffon/griffon)：Griffon是JVM的桌面应用程序开发平台，受Grails的启发，Griffon利用了约定优于配置、模块化和选择自由等概念。
* [JGoodies](https://www.jgoodies.com/downloads/libraries/)：JGoodies可帮助美化桌面应用程序并更快地构建设计良好、一致的视图。
* [Eclipse Nebula](https://github.com/eclipse/nebula)：该项目包含大量UI元素，可在基于Java和SWT的胖或瘦客户端应用程序中使用。
* [JIDE](https://github.com/jidesoft/jide-oss)：JIDE提供专业的Java UI组件，专注于为软件开发人员提供富客户端应用程序。

#### Swing组件库

* [SwingBits](https://github.com/eugener/oxbow)：SwingBits是Java Swing Toolkit的有用组件和实用程序的集合。
* [UiBooster](https://github.com/Milchreis/UiBooster)：UiBooster是一个精益库，用于为实用工具创建快速且简单的对话框。
* [JXMapViewer2](https://github.com/msteiger/jxmapviewer2)：该项目基于SwingX-WS的JXMapViewer组件。
* [HMeter](https://sourceforge.net/projects/hasnatmeter/)：HMeter是一个高度可定制的Java Swing小部件，旨在直观地显示水平进度。
* [Notify](https://github.com/dorkbox/Notify)：适用于Java 8+的桌面和应用程序的Linux、MacOS或Windows弹出窗口。
* [Two Slices](https://github.com/sshtools/two-slices)：用于Windows、Mac OS X和Linux上的Java桌面通知的简单库。
* [Swing Console](https://github.com/mikera/swing-console)：Swing文本控制台组件，可用于提供类似于Java中的终端的功能。
* [JTouchBar](https://github.com/Thizzer/jtouchbar)：用于在受支持的MacBook上使用touchbar API的Java库。
* [JSplitButton](https://github.com/rhwood/jsplitbutton)：Java Swing的分割按钮控件的简单实现。
* [JTreeTable](https://github.com/javagl/JTreeTable)：JTreeTable实现。
* [File Manager](https://github.com/javadev/file-manager)：Java/Swing基本文件管理器。
* [Fireplace](https://github.com/bric3/fireplace)：Java Swing火焰图组件。
* [JInputValidator](https://github.com/rhwood/jinputvalidator)：Java Swing的InputVerifier，在验证组件的右侧显示验证状态。
* [ModernDocking](https://github.com/andrewauclair/ModernDocking)：Modern Docking是一个简单的框架，旨在为Java Swing应用程序添加程序坞功能。

#### Swing布局库

* [TableLayout](https://github.com/EsotericSoftware/tablelayout)：TableLayout是一个轻量级Java库，用于使用逻辑表(类似于HTML表格)设置UI小部件的位置和大小。
* [SlidingLayout](https://github.com/AurelienRibon/sliding-layout)：功能强大的Java Swing面板/布局，具有涉及滑动子面板的炫酷过渡。
* [Swing Library](https://github.com/oliverwatkins/swing_library)：该库包含许多Java Swing框架所缺少的高级组件和布局管理器。
* [PanelMatic](https://github.com/codeworth-gh/PanelMatic)：PanelMatic是一个成熟的Swing工具库，旨在轻松创建复杂的高质量布局。

#### Swing选择器

* [LGoodDatePicker](https://github.com/LGoodDatePicker/LGoodDatePicker)：Java Swing日期选择器，易于使用、美观、功能强大且本地化。
* [Swing Datetime Picker](https://github.com/DJ-Raven/swing-datetime-picker)：使用Java Swing的简单日期时间选择器实现。
* [JDatePicker](https://github.com/JDatePicker/JDatePicker)：JDatePicker和JDatePanel是一组用于Java Swing应用程序的高级DatePicker控件。
* [ColorPick](https://github.com/dheid/colorpicker)：一个使用Java Swing的漂亮颜色选择器，包含可视颜色选择和用于手动输入RGB和HSB值的输入框。
* [JnaFileChooser](https://github.com/steos/jnafilechooser)：使用Windows原生对话框的Java文件选择器API。

#### Swing图表库

* [JFreeChart](https://github.com/jfree/jfreechart)：JFreeChart是一个适用于Java平台的综合免费图表库，可在客户端(JavaFX和Swing)或服务器端使用。
* [Orson Charts](https://github.com/jfree/orson-charts)：Orson Charts是一个用于Java平台的3D图表库，可以生成各种3D图表，用于客户端应用程序(JavaFX和Swing)和服务器端应用程序(导出为PDF、SVG、PNG和JPEG)。
* [Matplotlib4j](https://github.com/sh0nk/matplotlib4j)：Matplotlib4j是一个用于Java、Scala和Kotlin的简单绘图库。
* [Ardor3D](https://github.com/Renanse/Ardor3D)：Ardor3D是一个基于Java的免费、面向专业的开源3D图形引擎。
* [JGraphX](https://github.com/jgraph/jgraphx)：JGraphX是一个Java Swing图表库。
* [Three Kt](https://github.com/markaren/three.kt)：流行的Three.js 3D库的Kotlin/JVM端口。
* [Java-GTK](https://github.com/bailuk/java-gtk)：Java的GTK 4绑定。

#### Swing测试库

* [SwingLibrary](https://github.com/robotframework/SwingLibrary)：SwingLibrary是一个用于测试Java Swing应用程序的机器人框架库。
* [AssertJ Swing](https://github.com/assertj/assertj-swing)：该项目提供了一个简单直观的API，用于Swing用户界面的功能测试。
* [FEST-Swing](https://github.com/alexruiz/fest-swing-1.x)：该项目为Swing用户界面的功能测试提供了一个简单直观的API，从而使测试变得紧凑、易于编写和阅读，就像规范一样。
* [UISpec4J](https://github.com/UISpec4J/UISpec4J)：UISpec4J是一个开源功能和/或单元测试库，用于基于Swing的Java应用程序。

#### JavaFX

* [JFoenix](https://github.com/sshahine/JFoenix)：JFoenix是一个开源Java库，它使用Java组件实现Google Material Design。
* [Tray Notification](https://github.com/PlusHaze/TrayNotification)：Tray Notification是JavaFX的一个库，为台式计算机添加了易于使用的托盘通知。
* [MaterialFX](https://github.com/palexdev/MaterialFX)：MaterialFX是一个开源Java库，为JavaFX提供材料设计组件。
* [FXLauncher](https://github.com/edvin/fxlauncher)：JavaFX应用程序的自动更新启动器。
* [Scene Builder](https://github.com/gluonhq/scenebuilder)：Scene Builder是一款拖放式UI设计工具，可实现快速桌面和移动应用程序开发。
* [RxJavaFX](https://github.com/ReactiveX/RxJavaFX)：RxJavaFX是一个轻量级库，用于将JavaFX事件转换为RxJava Observables/Flowables，反之亦然。
* [WorkbenchFX](https://github.com/dlsc-software-consulting-gmbh/WorkbenchFX)：用于JavaFX应用程序的轻量级RCP框架。
* [MVVMFX](https://github.com/sialcasa/mvvmFX)：MVVMFX是一个应用程序框架，它为你提供使用JavaFX实现MVVM模式所需的组件。
* [JWM](https://github.com/HumbleUI/JWM)：JWM是一个跨平台的Java窗口管理和操作系统集成库。
* [ReactFX](https://github.com/TomasMikula/ReactFX)：ReactFX是对JavaFX响应式编程技术的补充。
* [Substrate](https://github.com/gluonhq/substrate)：Gluon Substrate是一款将JavaFX客户端应用程序转换为桌面、移动和嵌入式设备的本机可执行文件的工具。
* [WebFX](https://github.com/webfx-project/webfx)：WebFX是一个由GWT提供支持的JavaFX应用程序转译器，它可以将JavaFX应用程序转换为传统的独立纯JavaScript Web应用程序(在浏览器中执行不需要插件或服务器)。
* [TestFX](https://github.com/TestFX/TestFX)：TestFX是一个用于简单、干净地测试JavaFX应用程序和组件的库。
* [TornadoFX](https://github.com/edvin/tornadofx)：TornadoFX是一个适用于Kotlin编程语言的小型轻量级JavaFX框架。
* [ValidatorFX](https://github.com/effad/ValidatorFX)：ValidatorFX是JavaFX的表单验证库。
* [EasyBind](https://github.com/TomasMikula/EasyBind)：EasyBind在创建自定义绑定时利用Lambda来减少样板文件，为Bindings.select*方法提供类型安全的替代方案，并向ObservableValue添加单子操作。
* [Gluon Maps](https://github.com/gluonhq/maps)：Gluon Maps提供了一种将OpenStreetMaps集成到JavaFX应用程序中的简单方法，它速度极快，并提供图层叠加、多个图块集等等。
* [LibRawFX](https://github.com/lanthale/LibRawFX)：集成适用于所有主要操作系统(Linux、Windows、OSX)的JavaFX的LibRaw库。
* [UpdateFX](https://github.com/vinumeris/updatefx)：UpdateFX是一个小型、简单的JavaFX应用程序自动在线更新框架。
* [ReduxFX](https://github.com/netopyr/reduxfx)：ReduxFX是一组库，使你能够在JavaFX应用程序中使用函数式响应式编程。
* [EasyFXML](https://github.com/Tristan971/EasyFXML)：EasyFXML是一组固执己见的工具，旨在简化健壮且模块化的JavaFX应用程序的开发。
* [JRebirth](https://github.com/JRebirth/JRebirth)：JRebirth是一个JavaFX应用程序框架。
* [JPro](https://www.jpro.one/)：用于在浏览器中运行Java的工具平台。
* [JavaFX-Plus](https://gitee.com/Biubiuyuyu/JavaFX-Plus)：简化开发步骤和提高开发效率的JavaFX框架。
* [SupernautFX](https://github.com/SupernautApp/SupernautFX)：Supernaut.FX是一个用于JavaFX应用程序的轻量级依赖注入框架。

#### JavaFX主题库

* [AtlantaFX](https://github.com/mkpaz/atlantafx)：现代JavaFX CSS主题集合，带有附加控件。
* [NSMenuFX](https://github.com/0x4a616e/NSMenuFX)：一个用于自定义macOS菜单栏的简单库，为你的JavaFX应用程序提供更原生的LaF。
* [JFXtras Styles](https://github.com/JFXtras/jfxtras-styles)：Java、JavaFX主题或LaF，目前包含JMetro主题。
* [JBootX](https://github.com/dicolar/jbootx)：JavaFX Bootstrap主题库。
* [BootstrapFX](https://github.com/kordamp/bootstrapfx)：BootstrapFX是Twitter Bootstrap的部分移植，它主要提供与原始样式非常相似的CSS样式表，同时针对JavaFX独特的CSS风格进行定制。
* [Transit](https://github.com/dukke/Transit)：Transit是一个现代JavaFX主题/风格，可用于为应用程序提供不同的LaF。

#### JavaFX样式库

* [ControlsFX](https://github.com/controlsfx/controlsfx)：ControlsFX是JavaFX的一个开源项目，旨在提供真正高质量的UI控件和其他工具来补充核心JavaFX发行版。
* [AnimateFX](https://github.com/Typhon0/AnimateFX)：包含70多个即用型JavaFX动画的库。
* [PreferencesFX](https://github.com/dlsc-software-consulting-gmbh/PreferencesFX)：用于轻松创建应用程序设置/首选项UI的框架。
* [CustomStage](https://github.com/Oshan96/CustomStage)：CustomStage是一个JavaFX Undecorated Stage，它包含默认JavaFX Decorated Stage的原生行为，并且完全可设计样式。
* [CSSFX](https://github.com/McFoggy/cssfx)：CSSFX通过在运行的应用程序中提供CSS重新加载功能来提高开发人员的工作效率。
* [Animated](https://github.com/iamgio/animated)：Animated引入了隐式动画，这是JavaFX中的一个全新概念，受到Flutter动画和运动小部件的强烈启发。
* [FXSkins](https://github.com/dukke/FXSkins)：现有JavaFX控件的新外观集合，这些皮肤将为应用程序中使用的控件添加更多功能，几乎不需要更改代码。
* [JSilhouette](https://github.com/kordamp/jsilhouette)：JSilhouette为Java应用程序提供了额外的形状，目前支持JavaFX。
* [MDFX](https://github.com/JPro-one/markdown-javafx-renderer)：MDFX是一个简单的JavaFX Markdown渲染器。
* [Actlist](https://github.com/actlist/actlist)：Actlist是一个实用平台，可以轻松简单地执行你自己的行为列表。
* [Tornado FXControls](https://github.com/edvin/tornadofx-controls)：JavaFX的CSS样式控件库。
* [FX-BorderlessScene](https://github.com/goxr3plus/FX-BorderlessScene)：未修饰的JavaFX场景，实现了移动、调整大小、最小化、最大化、关闭和Windows Aero Snap控件。
* [LitFX](https://github.com/Birdasaur/LitFX)：LitFX可以将其效果作为透明覆盖层应用到你的JavaFX GUI，这样效果就可以与你的各种节点进行交互，而无需先验了解你的布局。

#### JavaFX组件库

* [RichTextFX](https://github.com/FXMisc/RichTextFX)：RichTextFX为JavaFX提供了一个节省内存的TextArea，允许开发人员设置文本范围的样式、内联显示自定义对象(不再需要HTMLEditor)，并仅在必要时覆盖特定的默认行为。
* [JFXtras](https://github.com/JFXtras/jfxtras)：JavaFX的支持库，包含工具程序类、扩展布局、控件和其他有趣的小部件。
* [DashboardFx](https://github.com/gleidsonmt/DashboardFx)：该项目是为JavaFX创建的自定义组件集的一部分。
* [GemsFX](https://github.com/dlsc-software-consulting-gmbh/GemsFX)：用于渲染SVG图像文件的控件，利用jsvg库，即使在缩放时也能确保高清质量。
* [CalendarFX](https://github.com/dlsc-software-consulting-gmbh/CalendarFX)：用于创建基于JavaFX的复杂日历视图的Java框架。
* [RXControls](https://github.com/leewyatt/rxcontrols)：RXControls是一个JavaFX自定义组件库，密码可见组件、轮播图组件、动态按钮组件等。
* [PDFViewFX](https://github.com/dlsc-software-consulting-gmbh/PDFViewFX)：允许应用程序显示PDF文件的自定义控件。
* [UnitFX](https://github.com/dlsc-software-consulting-gmbh/UnitFX)：UnitFX是一个轻量级框架，用于创建基于UOM的文本字段输入控件。
* [AnchorFX](https://github.com/alexbodogit/AnchorFX)：AnchorFX是JavaFX的免费开源库，用于创建具有Dock功能的图形界面。
* [PhoneNumberFX](https://github.com/dlsc-software-consulting-gmbh/PhoneNumberFX)：该仓库包含一个控件，用于输入世界上任何国家/地区的有效电话号码。
* [Monocle](https://github.com/TestFX/Monocle)：Monocle是针对嵌入式系统的JavaFX Glass窗口组件的实现。
* [JavaFXSVG](https://github.com/codecentric/javafxsvg)：用于向JavaFX添加SVG支持，允许像任何其他图像类型一样使用SVG图形。
* [FormsFX](https://github.com/dlsc-software-consulting-gmbh/FormsFX)：用于轻松创建JavaFX UI表单的框架。
* [FXParallax](https://github.com/dukke/FXParallax)：用于为Java添加视差效果的控件。
* [DockFX](https://github.com/RobertBColton/DockFX)：该库是为了填补JavaFX RIA平台中可用的Dock框架的空白，其目的是为你提供一个功能齐全的Dock库。
* [FxDock](https://github.com/andy-goryachev/FxDock)：JavaFX Dock框架。
* [FXRibbon](https://github.com/dukke/FXRibbon)：Java的Ribbon控件，使用JavaFX框架，基于Microsoft Ribbon。
* [DesktopPaneFX](https://github.com/kordamp/desktoppanefx)：DesktopPaneFX是Swing JDesktopPane的JavaFX版本，它可以用作类似于JInternalFrames的单个“子”容器。
* [KeyboardFX](https://github.com/dlsc-software-consulting-gmbh/KeyboardFX)：JavaFX应用程序的屏幕键盘。
* [TiwulFX](https://github.com/panemu/tiwulfx-dock)：TiwulFX-Dock提供增强的JavaFX TabPane，支持选项卡重新排序、分离和对接。
* [FXFileChooser](https://github.com/Oliver-Loeffler/FXFileChooser)：自定义JavaFX文件选择器，允许快速手动过滤，允许添加路径谓词作为过滤器。

#### JavaFX图表库

* [JFreeChart](https://github.com/jfree/jfreechart)：JFreeChart是一个适用于Java平台的综合免费图表库，可在客户端(JavaFX和Swing)或服务器端使用。
* [TilesFX](https://github.com/HanSolo/tilesfx)：包含可用于仪表板的图块的JavaFX库。
* [Medusa](https://github.com/HanSolo/medusa)：用于仪表的JavaFX库，该项目的主要重点是提供可以多种方式配置的仪表。
* [Charts](https://github.com/HanSolo/charts)：JavaFX中的科学图表库。
* [ChartFX](https://github.com/fair-acc/chart-fx)：ChartFX是GSI为FAIR开发的一个科学图表库，专注于以25Hz更新速率对数字信号处理应用中常见的具有数万到500万个数据点的数据集进行性能优化的实时数据可视化。
* [GMapsFX](https://github.com/dlsc-software-consulting-gmbh/GMapsFX)：纯JavaFX API，允许你将Google地图添加到JavaFX应用程序，而无需与底层Google地图JavaScript API交互。
* [FXForm2](https://github.com/dooApp/FXForm2)：FXForm2是一个提供自动JavaFX表单生成的库。
* [Piccolo2D](https://github.com/piccolo2d/piccolo2d.java)：Piccolo2D是一种在Java创建强大、功能齐全的图形应用程序的方式，具有诸如缩放和多重表示等引人注目的功能。
* [VWorkflows](https://github.com/miho/VWorkflows)：用于构建特定领域的可视化编程环境的交互式流/图形可视化。
* [FXGraphics2D](https://github.com/jfree/fxgraphics2d)：FXGraphics2D是针对JavaFX Canvas的Java Graphics2D API的实现。
* [FlexGanttFX](https://dlsc.com/products/flexganttfx)：FlexGanttFX是目前可用于Java的最先进的基于JavaFX的甘特图框架。
* [FXyz](https://github.com/FXyz/FXyz)：JavaFX 3D可视化和组件库。
* [yFiles](https://www.yworks.com/products/yfiles-for-java)：yFiles是业界领先的图形可视化、编辑和分析软件库。
* [JView](https://www.perforce.com/products/visualization)：JViews提供先进的行业特定可视化。
* [Countries](https://github.com/HanSolo/countries)：Countries是一个JavaFX库，其中包含有关国家/地区的信息，例如形状、GPS坐标、城市和机场。
* [JFreePDF](https://github.com/jfree/jfreepdf)：JFreePDF是Java平台的一个库模块，允许你使用标准Java2D绘图API(Graphics2D)以Adobe的可移植文档格式(PDF)创建内容。
* [Graph Editor](https://github.com/eckig/graph-editor)：用于在JavaFX中创建和编辑类似图形的图表的库。
* [Eclipse SWTChart](https://github.com/eclipse/swtchart)：Eclipse SWTChart允许创建不同类型的图表。
* [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)：该项目提供了一个通用JavaFX图形可视化库，可以通过力导向算法实时自动排列顶点的位置。

#### JavaFX图标库

* [Ikonli](https://github.com/kordamp/ikonli)：Ikonli提供可在Java应用程序中使用的图标包，目前支持Swing和JavaFX UI工具包。
* [FXTrayIcon](https://github.com/dustinkredmond/FXTrayIcon)：用于JavaFX应用程序的库，可以更轻松地添加系统托盘图标。
* [jIconFont-Swing](https://github.com/jIconFont/jiconfont-swing)：jIconFont-Swing是一个API，用于提供由任何IconFont生成的图标。
* [Icon Generator](https://github.com/sshtools/icon-generator)：一个简单的库，用于在Java中生成Java2D(Swing/AWT)、JavaFX和SWT图标。

#### JavaFX布局库

* [MiGLayout](https://github.com/mikaelgrev/miglayout)：MigLayout是一个功能极其丰富的JavaFX/SWT/Swing布局管理器，它使布局问题变得微不足道。
* [Flowless](https://github.com/FXMisc/Flowless)：JavaFX的高效VirtualFlow，VirtualFlow是一个布局容器，可在垂直或水平流中布局单元格。

#### JavaFX渲染库

* [DriftFX](https://github.com/eclipse-efx/efxclipse-drift)：DriftFX允许你将任何OpenGL内容直接渲染到JavaFX节点中。
* [NativeFX](https://github.com/miho/NativeFX)：JavaFX的原生渲染集成。
* [JFXShader](https://github.com/Teragam/JFXShader)：允许在JavaFX中使用OpenGL(GLSL)或DirectX(HLSL)自定义效果着色器。

#### 浏览器

* [WebBrowser](https://github.com/goxr3plus/JavaFX-Web-Browser)：用Java和JavaFX制作的Web浏览器。
* [Wolvic XR Browser](https://github.com/Igalia/wolvic)：Wolvic是一个开源浏览器，包括XR构建的沉浸式游戏、视频和环境。
* [JCEF](https://github.com/chromiumembedded/java-cef)：JCEF是一个简单的框架，用于使用Java编程语言将基于Chromium的浏览器嵌入到其他应用程序中。
* [GNGR](https://github.com/gngrOrg/gngr)：这是一款支持隐私的新型跨平台浏览器，GNGR是纯Java的Web标准的独立实现。
* [JxBrowser](https://teamdev.com/jxbrowser/)：将Chromium Web浏览器添加到你的Java应用程序中。
* [Gophie](https://github.com/jankammerath/gophie)：Gophie是“The Internet Gopher”的现代图形跨平台客户端或浏览器。
* [Lobo Evolution](https://github.com/LoboEvolution/LoboEvolution)：Lobo Evolution是一个可扩展的全Java Web浏览器和RIA平台。
* [Easy Browser](https://gitee.com/fhs-opensource/easy-browser)：Java开源浏览器，基于JxBrowser实现，已经包含了绝大多数的浏览器基础功能。
* [Webicity](https://github.com/WebicityBrowser/Webicity)：Webicity是一个简单的Web浏览器。
* [JFX-Browser](https://github.com/badarshahzad/Jfx-Browser)：JFX Browser是一个多选项卡浏览器。

#### JavaFX小工具

* [JabRef](https://github.com/JabRef/jabref)：用于管理BibTeX和biblatex(.bib)数据库的图形化Java应用程序。
* [AsciidocFX](https://github.com/asciidocfx/AsciidocFX)：使用JavaFX 19编写的Asciidoc编辑器和工具链(构建PDF、Epub、Mobi和HTML书籍、文档和幻灯片)。
* [Fofa Viewer](https://github.com/wgpsec/fofa_viewer)：用JavaFX编写的简单FOFA客户端。
* [QuPath](https://github.com/qupath/qupath)：QuPath是用于生物图像分析的开源软件，由英国女王大学开源。
* [Phoenicis](https://github.com/PhoenicisOrg/phoenicis)：Phoenicis是PlayOnLinux和PlayOnMac 4的指定继承者，允许你在您喜欢的操作系统上安装和使用非本机应用程序。
* [XPipe](https://github.com/xpipe-io/xpipe)：全新的Shell连接集线器和远程文件管理器。
* [XR3Player](https://github.com/goxr3plus/XR3Player)：最先进的JavaFX媒体播放器。
* [Artillery](https://github.com/Weik1/Artillery)：Java插件化漏洞扫描器，GUI基于JavaFX。
* [DrawingBotV3](https://github.com/SonarSonic/DrawingBotV3)：一款将图像转换为矢量艺术的软件。
* [LaTeXDraw](https://github.com/latexdraw/latexdraw)：LaTeX的矢量绘图编辑器。
* [JDKMon](https://github.com/HanSolo/JDKMon)：一个用JavaFX编写的小工具，用于监视已安装的JDK并通知你有关更新的信息。
* [MQTT.fx](https://www.softblade.de/)：MQTT.fx是开发和生产中测试物联网路由的工具。
* [CorreoMQTT](https://github.com/EXXETA/correomqtt)：CorreoMQTT是使用HiveMQ客户端库的现代图形MQTT客户端。
* [TerminalFX](https://github.com/javaterminal/TerminalFX)：JavaFX终端模拟器。
* [Binjr](https://github.com/binjr/binjr)：时序数据浏览器。
* [SQLucky](https://github.com/tenie/SQLucky)：跨平台数据库可视化操作工具。
* [Quelea](https://github.com/quelea-projection/Quelea)：适用于教堂的开源投影软件。
* [Image2LaTeX](https://github.com/blaisewang/img2latex-mathpix)：Image2LaTeX提供将图像转换为某些LaTeX方程格式和OCR的核心功能。
* [FakeImageDetection](https://github.com/afsalashyana/FakeImageDetection)：使用机器学习检测虚假图像。
* [OwlPlug](https://github.com/DropSnorz/OwlPlug)：音频插件管理器，用于在Windows、MacOS和Linux上管理VST/AU/LV2插件的小工具。
* [LogFX](https://github.com/renatoathaydes/LogFX)：简单的日志阅读器，支持颜色突出显示并能够处理巨型文件。
* [JMetro](https://pixelduke.com/java-javafx-theme-jmetro/)：JavaFX应用程序的现代主题，具有浅色和深色风格。
* [Object Graph Visualizer](https://github.com/Nurtak/ObjectGraphVisualization)：对象图可视化工具。
* [Everest](https://github.com/RohitAwate/Everest)：一个漂亮的跨平台REST客户端。
* [Flow](https://github.com/eclab/flow)：Flow是一款完全模块化的多音色和复调加法软件合成器，由乔治梅森大学开源。
* [Scenic View](https://github.com/JonathanGiles/scenic-view)：Scenic View是一个JavaFX应用程序，旨在让你轻松了解应用程序场景图的当前状态，并且还可以轻松操作场景图的属性，而无需继续编辑代码。
* [Usagi](https://github.com/OHDSI/Usagi)：Usagi是一个帮助创建编码系统和词汇标准概念之间映射的应用程序，由OHDSI开源。
* [Trinity](https://github.com/Birdasaur/Trinity)：Trinity提供性能分析和XAI工具，非常适合深度学习系统或执行复杂分类或解码的其他模型。
* [LogoRRR](https://github.com/rladstaetter/LogoRRR)：LogoRRR是一款跨平台日志分析工具，它提供了一种清晰、快速的方式来浏览大型文本文件，通过其交互式、用户友好的界面强调关键事件。

#### GUI程序

* [LanguageTool](https://github.com/languagetool-org/languagetool)：LanguageTool是一款开源校对软件，适用于英语、西班牙语、法语、德语、葡萄牙语、波兰语、荷兰语和其他20多种语言，它可以发现许多简单的拼写检查器无法检测到的错误。
* [FinalShell](https://www.hostbuf.com/)：FinalShell是一款一体化的服务器，网络管理软件。
* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [Protege](https://github.com/protegeproject/protege)：Protege是一个免费的开源本体编辑器，支持最新的OWL 2.0标准，由斯坦福开发。
* [JISA](https://github.com/OE-FET/JISA)：JISA是一个用Java编写的库，旨在用作为常见实验室仪器创建实验控制系统的方法，由剑桥大学开源。
* [Piped](https://github.com/TeamPiped/Piped)：Piped是另一种隐私友好的YouTube前端，设计高效。
* [Sonarqube](https://github.com/SonarSource/sonarqube)：SonarQube是一个开源的代码质量管理系统。
* [TempestSDR](https://github.com/martinmarinov/TempestSDR)：该项目是一个软件工具包，用于使用软件定义无线电(SDR)接收器远程窃听视频监视器。
* [SDRTrunk](https://github.com/DSheirer/sdrtrunk)：SDRTrunk是一个跨平台Java应用程序，用于使用软件定义无线电(SDR)解码、监控、记录和流式传输集群移动和相关无线电协议。
* [Proxyee Down](https://github.com/proxyee-down-org/proxyee-down)：Proxyee Down是一款开源的免费HTTP高速下载器，底层使用Netty开发，支持自定义HTTP请求下载且支持扩展功能，可以通过安装扩展实现特殊的下载需求。
* [Cyberduck](https://github.com/iterate-ch/cyberduck)：Cyberduck是一款适用于Mac和Windows的自由FTP、SFTP、WebDAV、Amazon S3、Backblaze B2、Microsoft Azure和OneDrive以及OpenStack Swift文件传输客户端。
* [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)：ST公司推出的一种自动创建单片机工程及初始化代码的工具。
* [BIMserver](https://github.com/opensourceBIM/BIMserver)：BIMserver使你能够存储和管理建筑(或其他建筑相关)项目的信息，由荷兰国家应用科学院和埃因霍芬理工大学开发。
* [ImageJ](https://imagej.net/ij/index.html)：ImageJ是一个基于Java的公共图像处理软件，由美国国立卫生研究院开发。
* [EtherPad](https://github.com/ether/pad)：Etherpad Lite是一种更简单、更快、更轻的协作编辑解决方案。
* [Wordfast](https://www.wordfast.com/)：Wordfast是一款翻译记忆软件，它为自由译者、语言服务供应者与跨国公司提供了翻译记忆独立平台的解决方案。
* [Pure Writer](https://github.com/PureWriter/desktop)：Pure Writer是一个开源编辑器。
* [OpenRocket](https://github.com/openrocket/openrocket)：OpenRocket是一款免费、功能齐全的模型火箭模拟器，可让你在实际建造和飞行火箭之前设计和模拟火箭。
* [Vivado](https://www.xilinx.com/products/design-tools/vivado.html)：Vivado是赛灵思开发的用于HDL设计的合成和分析的软件套件，具有用于片上系统开发和高级综合的附加功能。
* [Citespace](https://citespace.podia.com/)：CiteSpace是一个免费的Java应用程序，用于可视化和分析科学文献中的趋势和模式。
* [ArcTime](https://arctime.org/)：ArcTime是一个易用、强大、高效的字幕制作软件，由南京亿铭科技开发。
* [RapidWright](https://github.com/Xilinx/RapidWright)：RapidWright是AMD的一个开源项目，它通过DCP文件为Vivado提供了一个新的桥梁。
* [Unidata AWIPS](https://github.com/Unidata/awips2)：AWIPS是一个气象软件包，它用于解码、显示和分析数据，最初由雷神公司为国家气象局(NWS)开发。
* [ThinkPHP](https://github.com/Lotus6/ThinkphpGUI)：Thinkphp漏洞利用工具，支持各版本TP漏洞检测、命令执行、getshell。
* [JMRI](https://github.com/JMRI/JMRI)：JMRI是一个模型铁路数字指挥与控制软件。
* [Particle Life](https://github.com/tom-mohr/particle-life-app)：Particle Life的GUI，这是一个显示逼真行为的粒子系统。
* [jExifToolGUI](https://github.com/hvdwolf/jExifToolGUI)：jExifToolGUI是一个多平台Java/Swing图形前端，由Phil Harvey开发，用于优秀的命令行ExifTool应用程序。
* [WePush](https://github.com/rememberber/WePush)：专注批量推送的小而美的工具，目前支持：模板消息-公众号、模板消息-小程序、微信客服消息等。
* [BlobSaver](https://github.com/airsquared/blobsaver)：用于自动保存SHSH blob的跨平台GUI和CLI应用程序。
* [BiglyBT](https://github.com/BiglySoftware/BiglyBT)：基于Azureus开源项目的功能齐全的Bittorrent客户端。
* [Gephi](https://github.com/gephi/gephi/)：Gephi是适用于各种图形和网络的领先可视化和探索软件。
* [MooInfo](https://github.com/rememberber/MooInfo)：OSHI的可视化实现，用于查看有关系统和硬件的信息。
* [Freenet](https://github.com/hyphanet/fred)：Freenet是一个抗审查通信和发布平台，它是一种点对点软件，提供分布式、加密、去中心化的数据存储，起源于爱丁堡大学。
* [Datashare](https://github.com/ICIJ/datashare)：由国际调查记者联盟(ICIJ)开发的自托管文档搜索引擎。
* [RuneLite](https://github.com/runelite/runelite)：RuneLite是一个免费、开源的OldSchool RuneScape客户端。
* [Chatty](https://github.com/chatty/chatty)：Chatty是一款用Java编写的Twitch桌面聊天客户端，具有许多Twitch特定功能。
* [Moneydance](https://infinitekind.com/moneydance)：Moneydance是一款易于使用且功能齐全的个人理财应用程序。
* [Bits N Picas](https://github.com/kreativekorp/bitsnpicas)：Bits N Picas是一组用于创建和转换位图和表情符号字体的工具。
* [jEdit](https://www.jedit.org/)：jEdit是一个用Java语言开发的文本编辑器。
* [Bad Peggy](https://www.malavida.com/en/soft/bad-peggy/)：Bad Peggy会分析你的文件夹以查找损坏的JPEG图像。
* [TeXtidote](https://github.com/sylvainhalle/textidote)：LaTeX文档和其他格式的修正工具。
* [Live2D](https://www.live2d.com/)：Live2D是一种应用于电子游戏的绘图渲染技术，由日本Cybernoids公司开发。
* [Vuze](https://www.vuze.com/)：Vuze是一个用Java编写的BitTorrent客户端，且支持I2P和Tor匿名网络协议。
* [JDemetra+](https://github.com/jdemetra/jdemetra-app)：JDemetra+是比利时国家银行(NBB)与德意志联邦银行和欧盟统计局根据欧洲统计系统(ESS)指南合作开发的季节性调整(SA)新工具。
* [Bitwig Studio](https://www.bitwig.com/)：Bitwig Studio是由Bitwig公司开发的专有数字音频工作站。
* [Archi](https://github.com/archimatetool/archi)：Archi是一款免费、开源、跨平台的工具和编辑器，用于创建ArchiMate模型。
* [TuxGuitar](https://github.com/helge17/tuxguitar)：TuxGuitar是一个用Java编写的开源多轨指法谱编辑器和播放器。
* [DocFetcher](https://github.com/docfetcher/DocFetcher)：DocFetcher是一个开源桌面搜索应用程序，它允许你搜索计算机上的文件内容。
* [PIPE](https://github.com/sarahtattersall/PIPE)：平台独立的Petri网编辑器。
* [MuCommander](https://github.com/mucommander/mucommander)：MuCommander是一款轻量级、跨平台的文件管理器，具有双窗格界面。
* [Open Visual Traceroute](https://github.com/leolewis/openvisualtraceroute)：Open Visual Traceroute是一款提供视觉化的路由追踪工具。
* [Plot Digitizer](https://plotdigitizer.sourceforge.net/)：Plot Digitizer是一个Java程序，用于对功能数据的扫描图进行数字化。
* [RipMe](https://github.com/RipMeApp/ripme)：RipMe是一个适用于各种网站的专辑翻录工具。
* [FileBot](https://www.filebot.net/)：FileBot是重命名和组织电影、电视节目和动漫的终极工具。
* [KSar](https://github.com/vlsi/ksar)：KSar是一个sar图形工具，可以绘制Linux、Mac和Solaris sar输出的图形。
* [Pixelitor](https://github.com/lbalazscs/Pixelitor)：Pixelitor是一个高级Java图像编辑器，具有图层、图层蒙版、文本图层、110多个图像滤镜和颜色调整、多重撤消等。
* [Archimedes](https://github.com/ArchimedesCAD/Archimedes)：Archimedes是一款免费开源CAD软件。
* [BT747](https://www.bt747.org/)：BT747是一款基于MTK芯片组控制GPS数据记录器的应用程序。
* [TreeForm](https://github.com/frekky/TreeForm)：TreeForm语法树绘图软件是一个语言语法/语义树绘图编辑器。
* [FullSync](https://github.com/fullsync/fullsync)：FullSync是一个功能强大的工具，可帮助你保持各种数据的多个副本同步。
* [Shutter Encoder](https://github.com/paulpacifico/shutter-encoder)：Shutter Encoder是最好的视频转换器软件之一，它还可以处理图像和音频。
* [Java Modelling Tools](https://jmt.sourceforge.net/)：JMT是由米兰理工大学和伦敦帝国理工学院开发的一套应用程序，旨在为性能评估、使用分析和模拟技术的系统建模、容量规划和工作负载特征研究提供全面的框架。
* [Whole Platform](https://github.com/wholeplatform/whole)：Whole Platform是一种用于工程软件生产的开源技术。
* [MyTourbook](https://github.com/mytourbook/mytourbook)：MyTourbook是一款免费软件，用于可视化和分析由GPS设备、自行车或运动电脑和测力计记录的行程。
* [Virtual Satellite](https://github.com/virtualsatellite/VirtualSatellite4-Core)：Virtual Satellite是一款DLR开源软件，用于基于模型的系统工程MBSE。
* [Sweet Home 3D](http://www.sweethome3d.com/)：Sweet Home 3D是一款免费的室内设计应用程序，它可以帮助你绘制房屋平面图、在其上布置家具并以3D形式查看结果。
* [Autopsy](https://github.com/sleuthkit/autopsy)：Autopsy是Sleuth Kit和其他开源数字取证工具的图形界面。
* [Rachota](https://rachota.sourceforge.net/en/index.html)：Rachota是一款用于跟踪不同项目时间的便携式应用程序。
* [JMSToolBox](https://github.com/jmstoolbox/jmstoolbox)：JMSToolBox是一个“通用”JMS客户端，能够以一致的方式与市场上数量最多的队列管理器/队列提供程序进行交互。
* [MSPaintIDE](https://github.com/MSPaintIDE/MSPaintIDE)：这个应用程序给MS Paint带来了提升，可以让MS Paint突出显示、编译和执行代码。
* [JDiskReport](https://www.jgoodies.com/freeware/jdiskreport/)：JDiskReport使你能够了解文件和目录在磁盘驱动器上占用了多少空间，并帮助你找到过时的文件和文件夹。
* [Freerouting](https://github.com/freerouting/freerouting)：Freerouting是一款先进的自动布线器，适用于所有支持标准Specctra或Electra DSN接口的PCB程序。
* [Paintera](https://github.com/saalfeldlab/paintera)：Paintera是一种通用可视化工具，用于3D体积数据和分割/重建中的校对，主要关注连接组学中电子显微照片的神经元重建，由Saalfeld实验室开源。
* [Mars Simulation](https://github.com/mars-sim/mars-sim)：Mars Simulation是一个基于Java的开源项目，它模拟火星上最初定居者的任务操作和活动，其建模和模拟细节的保真度比大多数经典模拟游戏更高。
* [ELamX2](https://github.com/AndiMb/eLamX2)：ELamX²是一款用Java编写的开源复合计算器，由德累斯顿工业大学航空航天工程学院飞机工程系主任开发。

#### 数学软件

* [MATLAB](https://www.mathworks.com/products/matlab.html)：MATLAB是一种用于算法开发、数据可视化、数据分析以及数值计算的高级技术计算语言和交互式环境，其GUI部分由Java开发，这是MathWorks公司的商业软件。
* [GeoGebra](https://github.com/geogebra/geogebra)：GeoGebra是一款动态数学软件，于2001年由Markus Hohenwarter在奥地利萨尔茨堡大学制作。
* [Scilab](https://gitlab.com/scilab/scilab)：Scilab是用于数值计算的免费开源软件，为工程和科学应用提供强大的计算环境，由法国国立计算机及自动化研究院和法国国立桥梁学院开源。
* [MagicPlot](https://www.magicplot.com/)：MagicPlot是一款技术绘图、曲线拟合和数据分析应用程序，这是一个商业软件。
* [SmartPLS](https://www.smartpls.com/)：SmartPLS是用于使用偏最小二乘(PLS)路径建模方法进行基于方差的结构方程建模(SEM)的软件。
* [CaR](http://car.rene-grothmann.de/doc_en/index.html)：CaR是动态几何程序，它模拟计算机上的指南针和尺子结构，由艾希施泰特天主教大学开源。
* [CARMetal](https://carmetal.en.uptodown.com/windows)：CARMetal是动态几何程序C.a.R.的改编版本。
* [Hodoku](https://github.com/PseudoFish/Hodoku)：HoDoKu是一个用Java编写的数独助手，有英语和德语版本。

#### UML工具

* [StarUML](https://staruml.io/)：StarUML是一个开源的UML工具列表软件，由韩国MKLabs公司开源。
* [ArgoUML](https://github.com/argouml-tigris-org/argouml)：ArgoUML是领先的开源UML建模工具，支持所有标准UML 1.4图。
* [PlantUML](https://github.com/plantuml/plantuml)：PlantUML是一个允许你通过简单的文本描述创建各种UML图的组件。
* [IBM Rational Rose](https://www.ibm.com/docs/en/rational-soft-arch/9.7.0?topic=migration-rational-rose-model)：Rational Rose是统一建模语言的开发环境，这是IBM的商业产品。
* [Visual Paradigm](https://www.visual-paradigm.com/cn/)：Visual Paradigm是一款功能强大的UML工具，适用于不同层次的用户，从初学者到专家。
* [Astah](https://astah.net/)：Astah是由日本公司Change Vision创建的UML建模工具。
* [Eclipse Papyrus](https://eclipse.dev/papyrus/)：Eclipse Papyrus是一个工业级的开源基于模型的工程工具。
* [Modelio](https://github.com/ModelioOpenSource/Modelio)：Modelio是一种建模解决方案，提供基于企业架构、软件开发和系统工程常用标准的广泛功能。
* [MagicDraw](https://www.3ds.com/products/catia/no-magic/magicdraw)：MagicDraw是一款出色的建模工具，这是达索的商业工具。
* [Violet](https://github.com/violetumleditor/violetumleditor)：Violet是一个UML编辑器，易于学习和使用、可以画出漂亮的图表、完全免费跨平台。
* [JetUML](https://github.com/prmr/JetUML)：JetUML支持以最少的麻烦来绘制软件设计思想的草图，由麦吉尔大学教授开源。
* [UMLet](https://github.com/umlet/umlet)：UMLet是一个开源UML工具，具有简单的用户界面。
* [TinyUML](https://sourceforge.net/projects/tinyuml/)：TinyUML是一款免费软件工具，可轻松快速地创建UML 2图。

#### 办公软件

* [LibreOffice](https://github.com/LibreOffice/core)：LibreOffice是一款免费且功能强大的办公套件，是OpenOffice的继承者。
* [ThinkFree Office](https://thinkfree.com/)：ThinkFree Office是一款廉价却高效的Microsoft Office替代品。
* [OpenOffice](https://www.openoffice.org/)：OpenOffice是一个开源的办公包软件，起源于Sun公司从StarDivision收购的StarOffice。
* [永中Office](https://www.yozosoft.com/index.html)：永中Office是由永中科技公司用Java语言开发的一个可以在Windows、Linux等多个不同操作系统上运行的办公软件，与微软Microsoft Office相似。
* [泰山Office](http://web.ts-it.cn/index.html)：泰山Office采用Java开发，深度优化JVM，全面兼容国产CPU(龙芯、飞腾、鲲鹏、兆芯、申威)、国产操作系统(UOS、中标麒麟、银河麒麟、深度等)，是一款完全自主可控、安全可靠的国产基础办公软件。
* [Hancom Office](https://www.hancom.com/main/main.do)：Hancom Office是一款专有办公套件，其中包括文字处理器、电子表格软件、演示软件和PDF编辑器以及可通过互联网浏览器访问的在线版本，由韩国Hancom公司开发。
* [HCL Notes](https://www.hcl-software.com/domino)：HCL Notes是由HCLTech销售的适用于Unix、IBM i、Windows、Linux和macOS的专有协作软件平台。

#### 思维导图

* [Freeplane](https://github.com/freeplane/freeplane)：Freeplane是一款免费的开源软件应用程序，支持在工作、学校和家庭中思考、共享信息、完成工作。
* [Xmind](https://xmind.app/)：XMind是一个由香港XMind公司开发的脑力激荡法和心智图的软件工具，其主要用途为帮助用户捕捉想法，组织各类报表。
* [FreeMind](https://freemind.sourceforge.io/)：FreeMind是一款跨平台、用Java编写的绘制思维导图的软件。
* [VUE](https://github.com/VUE/VUE)：VUE是一个用Java编写的免费开源概念图应用程序，由塔夫茨大学学术技术小组开发。
* [CompendiumNG](https://github.com/compendiumng/compendiumng)：CompendiumNG是一个功能强大的应用程序，可让你使用节点和链接结构创建广泛的地图，由英国开放大学开源。

#### 数据库工具

* [DBeaver](https://github.com/dbeaver/dbeaver)：DBeaver是一款免费的跨平台数据库工具。
* [Chat2DB](https://github.com/chat2db/Chat2DB)：Chat2DB是一款AI first的数据管理、开发、分析工具，由阿里开源。
* [CloudDM](https://www.clougence.com/clouddm-personal)：CloudDM是ClouGence公司推出的一款一站式多数据源开发管理工具。
* [MDUT](https://github.com/SafeGroceryStore/MDUT)：MDUT是一款集成了多种主流数据库类型的中文数据库跨平台利用工具。
* [Jailer](https://github.com/Wisser/Jailer)：数据库子集和关系数据浏览工具。
* [Airpal](https://github.com/airbnb/airpal)：Airpal是一种基于Web的查询执行工具，它利用Facebook的PrestoDB使用户可以轻松编写查询和检索结果，由Airbnb开源。
* [Variety](https://github.com/variety/variety)：Variety是MongoDB的模式分析器。
* [ChartSQL](https://docs.chartsql.com/)：ChartSQL是一种嵌入SQL脚本中的可视化语言，由Sales Insights开源。
* [RedisClient](https://github.com/caoxinyu/RedisClient)：基于Java SWT和Jedis编写的Redis客户端GUI工具。
* [Redis-Admin](https://github.com/mauersu/redis-admin)：基于Java EE和Jedis编写的Redis客户端Web工具。
* [RedisDesktopClient](https://gitee.com/RedisDesktopClient/redis-desktop-client)：一款颜值较高、使用方便的Redis客户端工具。
* [RedisPlus](https://gitee.com/MaxBill/RedisPlus)：RedisPlus是为Redis可视化管理开发的一款开源免费的桌面客户端软件，支持Windows、Linux、Mac三大系统平台。
* [Redis-Admin](https://gitee.com/xuebusi/redis-admin)：一个简单好用的Redis缓存图形化管理工具，包含Redis的5种数据类型的CRUD操作。
* [RedisFront](https://gitee.com/dromara/RedisFront)：dromara社区开源的跨平台Redis桌面客户端工具，支持单机模式、集群模式、哨兵模式以及SSH隧道连接。
* [PrettyZoo](https://github.com/vran-dev/PrettyZoo)：Zookeeper GUI，支持Win/Mac/Linux平台。
* [ZkUI](https://github.com/DeemOpen/zkui)：允许在Zookeeper上进行CRUD操作的UI仪表板。
* [ZkClient](https://github.com/sgroschupf/zkclient)：Zookeeper客户端库。
* [Taokeeper](https://github.com/alibaba/taokeeper)：Java中Zookeeper的监视器，由阿里开源。
* [kafkaUI-lite](https://gitee.com/freakchicken/kafka-ui-lite)：非常好用的Kafka UI客户端工具，同时支持Zookeeper、Redis。
* [Shepher](https://gitee.com/zhannngchen/shepher)：一款ZooKeeper的管理工具。
* [Zookeeper-Visualizer](https://github.com/xin497668869/zookeeper-visualizer)：Zookeeper的可视化管理工具。
* [Redis Manager](https://github.com/ngbdf/redis-manager)：Redis一站式管理平台，支持集群的监控、安装、管理、告警以及基本的数据操作。
* [SchemaSpy](https://github.com/schemaspy/schemaspy)：SchemaSpy是一个数据库元数据分析器，它可以帮助你的数据库管理员和开发人员可视化、导航和理解你的数据模型。
* [UMONGO](https://github.com/agirbal/umongo)：用于浏览和管理MongoDB集群的桌面应用程序。
* [SQL Workbench](https://codeberg.org/sql-workbench/workbench)：SQL Workbench/J是一个独立于DBMS的跨平台SQL查询工具。
* [SQuirreL SQL](https://github.com/squirrel-sql-client/squirrel-sql-code)：SQuirrel SQL是一个用Java写的数据库管理工具。
* [Screw](https://gitee.com/leshalv/screw)：简洁好用的数据库表结构文档生成器。
* [DBM](https://gitee.com/devlive-community/dbm)：全平台数据库管理工具，支持ClickHouse、Presto、Trino、MySQL、PostgreSQL、Apache Druid、ElasticSearch等。
* [DBEdit 2](https://dbedit2.sourceforge.net/)：DBEdit 2是一个数据库编辑器，适合作为所有关系型数据库的前端。
* [SQLeo](https://github.com/ojwanganto/SQLeo)：一个强大的SQL工具，可将复杂查询(由OBIEE、Microstrategy、Cognos、Hyperion、Pentaho...生成)转换或反转为图表，以简化可视化和分析。
* [brModelo](https://github.com/chcandido/brModelo)：用于数据库ER模型的工具，由圣卡塔琳娜联邦大学和安第列斯-圭亚那大学联合开发。
* [Databench-T](https://gitee.com/caict-bigdata/databench-t)：Databench-T是面向金融核心业务系统场景的事务型数据库性能测试工具，2018年由中国信通院云计算与大数据研究所联合北京银行、建设银行等企业共同设计开发。
* [CloudBeaver](https://github.com/dbeaver/cloudbeaver)：CloudBeaver是一个云数据库管理器，提供丰富的Web界面。
* [PGCodeKeeper](https://github.com/pgcodekeeper/pgcodekeeper)：PGCodeKeeper是一个PostgreSQL模式管理工具。
* [EXperDB-Management](https://github.com/experdb/eXperDB-Management)：EXperDB-Management是一款PostgreSQL管理工具。
* [Rel](https://reldb.org/c/)：Rel是用于创建和管理数据库的软件。
* [qStudio](https://github.com/timeseries/qstudio)：qStudio是一个免费的SQL GUI，它允许运行SQL脚本、轻松浏览表格、绘制图表和导出结果。
* [SQL Analysis](https://github.com/jd-opensource/sql-analysis)：针对大促、日常系统稳定性隐患-慢SQL的预防和排查，基于Mybatis插件设计的一款慢SQL分析组件，区别于主流的基于慢SQL日志分析和预警，实时根据Explain分析结果分析，由京东开源。
* [RCT](https://github.com/xaecbd/RCT)：RCT是通过解析RDB文件进行Redis内存结构分析的一站式平台。

#### 数据库建模

* [Open ModelSphere](http://www.modelsphere.com/org/index.html)：Open ModelSphere是一个强大的数据、流程和UML建模工具。
* [PDManer](https://gitee.com/robergroup/pdmaner)：PDManer元数建模，是一款多操作系统开源免费的桌面版关系数据库模型建模工具，相对于PowerDesigner，他具备界面简洁美观，操作简单，上手容易等特点。
* [CHINER](https://gitee.com/robergroup/chiner)：CHINER元数建模，一款丰富数据库生态、独立于具体数据库之外的、数据库关系模型设计平台。
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler)：SchemaCrawler是一个免费的数据库模式发现和理解工具。
* [FML](https://github.com/alibaba/fast-modeling-language)：FML是一种专为维度建模而设计的类似SQL的语言，由阿里开源。

#### 字节码工具

* [JD-GUI](https://github.com/java-decompiler/jd-gui)：Java反编译器GUI。
* [Recaf](https://github.com/Col-E/Recaf)：现代Java字节码编辑器。
* [ClassyShark](https://github.com/google/android-classyshark)：Android和Java字节码查看器，由Google开源。
* [JClasslib](https://github.com/ingokegel/jclasslib)：JClasslib是一个工具，可以可视化已编译的Java类文件和所包含的字节码的各个方面。
* [GDA](https://github.com/charles2gan/GDA-android-reversing-Tool)：最快、最强大的Android反编译器，适用于APK、DEX、ODEX、OAT、JAR、AAR和CLASS文件。
* [Luyten](https://github.com/deathmarine/Luyten)：Procyon的开源Java反编译器GUI。
* [Classpy](https://github.com/zxh0/classpy)：Classpy是一个GUI工具，用于研究Java类文件、Lua二进制块、Wasm二进制代码和其他二进制文件格式。
* [Jar-Analyzer](https://github.com/4ra1n/jar-analyzer-gui)：一个用于分析Jar包的GUI工具，可以用多种方式搜索你想要的信息，自动构建方法调用关系，支持分析Spring框架。
* [ClassViewer](https://github.com/ClassViewer/ClassViewer)：轻量级的Java字节码文件查看器，仅依赖于JDK和JavaFX。
* [JD-Core](https://github.com/java-decompiler/jd-core)：用Java编写的Java反编译器。
* [JADXecute](https://github.com/LaurieWired/JADXecute)：用于动态反编译器操作的JADX-GUI脚本插件。
* [Decompiler](https://github.com/sotasan/decompiler)：小巧的Java反编译器GUI。
* [Vineflower](https://github.com/Vineflower/vineflower)：一种现代通用JVM语言反编译器，专注于提供最佳的质量、速度和可用性。
* [Fernflower](https://github.com/fesh0r/fernflower)：Java反编译器。
* [JD-Core-Java](https://github.com/nviennot/jd-core-java)：Java反编译器JD-Core库。
* [Friday](https://github.com/zifeihan/friday)：Java实时反编译工具。
* [CFR](https://github.com/leibnitz27/cfr)：可以很好地将class文件从其他JVM语言转回Java。
* [JD-Eclipse](https://github.com/java-decompiler/jd-eclipse)：Java反编译器Eclipse插件。
* [ClassGraph](https://github.com/classgraph/classgraph)：超快速并行Java类路径扫描器和模块扫描器。
* [JDart](https://github.com/psycopaths/jdart)：JDart是一个在Java程序上执行一致执行的工具，它是作为NASA Java Pathfinder(JPF)的扩展编写的。
* [UnLuac](https://github.com/HansWessels/unluac)：UnLuac是Lua 5.1的反编译器，它在使用标准Lua编译器编译的Lua块上运行。
* [JADX](https://github.com/skylot/jadx)：Dex到Java反编译器。
* [Class Visualizer](https://github.com/jonatan-kazmierczak/class-visualizer)：免费交互式类图生成器。
* [Serianalyzer](https://github.com/mbechler/serianalyzer)：Serianalyzer是一个静态字节码分析器，跟踪反序列化期间调用的方法进行的原生方法调用。

#### 字节码混淆工具

* [ProGuard](https://github.com/Guardsquare/proguard)：ProGuard是一个免费的Java字节码收缩器、优化器、混淆器和预验证器。
* [Simplify](https://github.com/CalebFenton/simplify)：Android虚拟机和反混淆器。
* [ClassFinal](https://gitee.com/roseboy/classfinal)：ClassFinal是一款Java class文件安全加密工具，支持直接加密jar包或war包，无需修改任何项目代码，兼容Spring框架；可避免源码泄漏或字节码被反编译。
* [AabResGuard](https://github.com/bytedance/AabResGuard)：AabResGuard是一款由抖音Android团队提供支持的资源混淆工具。
* [Deobfuscator](https://github.com/java-deobfuscator/deobfuscator)：该项目旨在对大多数商用Java混淆器进行反混淆。
* [DashO](https://www.preemptive.com/products/dasho/)：DashO的目标是让混淆和应用程序强化变得比以往更容易。
* [Black Obfuscator](https://github.com/CodingGay/BlackObfuscator)：Black Obfuscator是一款针对Android APK DexFile的混淆器，它可以帮助开发者通过控制流扁平化来保护源代码，并使分析实际程序控制流变得困难。
* [Skidfuscator](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator)：Skidfuscator是一个概念验证混淆工具，旨在利用SSA形式来优化和混淆Java字节码代码流。
* [Native-Obfuscator](https://github.com/radioegor146/native-obfuscator)：用于JNI的Java class到cpp转换器。
* [Radon](https://github.com/ItzSomebody/radon)：磨损的Java字节码混淆器。
* [yGuard](https://github.com/yWorks/yGuard)：yGuard是yWorks推出的与Ant和Gradle配合使用的开源Java混淆工具。
* [Caesium](https://github.com/sim0n/Caesium)：Cesium是一个强大的Java字节码混淆器。
* [dProtect](https://github.com/open-obfuscator/dProtect)：dProtect是Proguard的扩展，具有增强的代码混淆功能。
* [Bozar](https://github.com/vimasig/Bozar)：带GUI的Java字节码混淆器。
* [Threadtear](https://github.com/GraxCode/threadtear)：Threadtear是一个多功能的Java反混淆工具。
* [SpecialSource](https://github.com/md-5/SpecialSource)：jar混淆映射的自动生成器和重命名器。
* [Allatori](https://allatori.com/)：Allatori是第二代Java混淆器，它为你的知识产权提供全方位的保护。
* [Simple String obfuscator](https://github.com/shamanland/simple-string-obfuscator)：Java的简单字符串混淆器。
* [Enigma](https://github.com/christopherney/Enigma)：混淆器字符串加密。
* [BisGuard](https://www.bisguard.com/)：商业的Java反混淆工具。
* [Branchlock](https://branchlock.net/)：Branchlock为Java桌面应用程序、Android应用程序以及Kotlin和Groovy等JVM语言的二进制文件提供混淆。
* [ClassGuard](https://zenofx.com/classguard/)：ClassGuard是一个防止Java反编译的工具。
* [SandMark](http://sandmark.cs.arizona.edu/)：SandMark是亚利桑那大学开发的一款工具，用于Java字节码的软件水印、防篡改和代码混淆。
* [Stringer](https://jfxstore.com/stringer/)：Stringer可保护Java应用程序二进制文件(JAR、Java 9模块、OSGI、WAR、EAR、Eclipse RCP)免遭逆向工程和修改。
* [CAFED00D](https://github.com/Col-E/CAFED00D)：混淆弹性Java class读取器/写入器。
* [Obfuscator](https://github.com/superblaubeere27/obfuscator)：GUI Java混淆器。
* [JObfuscator](https://www.pelock.com/products/jobfuscator)：JObfuscator是Java语言的源代码混淆器。
* [Enigma](https://github.com/FabricMC/Enigma)：Enigma是用于Java字节码反混淆的工具。
* [Jar Protect](https://gitee.com/chejiangyi/jar-protect)：jar加密加壳工具，对class文件进行加密防护，对properties、yml等配置文件进行加密，避免反编译破解。

#### 游戏开发

* [LibGDX](https://github.com/libgdx/libgdx)：LibGDX是一个基于OpenGL的跨平台Java游戏开发框架，专为Windows、Linux、macOS、Android、Web浏览器和iOS设计。
* [Mindustry](https://github.com/Anuken/Mindustry)：Mindustry是一款2D游戏，其玩法融合塔防、工厂自动化、沙盒与即时战略。
* [Lila](https://github.com/lichess-org/lila)：Lila是一款免费的在线国际象棋游戏服务器，专注于实时游戏玩法和易用性。
* [LWJGL](https://github.com/LWJGL/lwjgl3)：LWJGL是一个Java库，支持跨平台访问流行的原生API，可用于图形(OpenGL、Vulkan、bgfx)、音频(OpenAL、Opus)、并行计算(OpenCL、CUDA)和XR(OpenVR、LibOVR、OpenXR)应用程序。
* [Grasscutter](https://github.com/Grasscutters/Grasscutter)：Grasscutter是一个实验性游戏服务器，旨在模拟玩某个动漫游戏的体验。
* [FXGL](https://github.com/AlmasB/FXGL)：Java/JavaFX/Kotlin游戏引擎库。
* [KTX](https://github.com/libktx/ktx)：KTX是一个扩展LibGDX的Kotlin游戏框架。
* [Spine](https://github.com/EsotericSoftware/spine-runtimes)：Spine是一款针对游戏开发的2D骨骼动画编辑工具，旨在提供更高效和简洁的工作流程，以创建游戏所需的动画。
* [Terasology](https://github.com/MovingBlocks/Terasology)：Terasology项目诞生于受Minecraft启发的技术演示，并正在成为体素世界中各种类型游戏设置的稳定平台。
* [jMonkeyEngine](https://github.com/jMonkeyEngine/jmonkeyengine)：jMonkeyEngine是一款适合富有冒险精神的Java开发人员的3D游戏引擎。
* [Unciv](https://github.com/yairm210/Unciv)：Civ V的开源、注重可修改性的Android和桌面重制版，使用LibGDX制作。
* [KorGE](https://github.com/korlibs/korge)：KorGE是Kotlin的现代多平台游戏引擎。
* [JBox2d](https://github.com/jbox2d/jbox2d)：JBox2d是C++物理引擎LiquidFun和Box2d的Java端口。
* [AndEngine](https://github.com/nicolasgramlich/AndEngine)：免费Android 2D OpenGL游戏引擎。
* [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon)：Shattered Pixel Dungeon是一款传统的Roguelike地下城探索角色扮演游戏。
* [Pixel Dungeon](https://github.com/watabou/pixel-dungeon)：Pixel Dungeon是一款传统的Roguelike游戏，具有像素艺术图形和简单的界面，适用于Android、iOS、Windows、Mac和Linux。
* [PretendYoureXyzzy](https://github.com/ajanata/PretendYoureXyzzy)：反人类卡牌克隆、服务器和Web客户端。
* [LunarCore](https://github.com/Melledy/LunarCore)：某回合制动漫游戏的游戏服务器重新实现。
* [XMage](https://github.com/magefree/mage)：XMage允许你与一名或多名在线玩家或电脑对手玩万智牌。
* [OpenRTS](https://github.com/methusalah/OpenRTS)：OpenRTS是一个3D即时战略游戏引擎。
* [JForGame](https://github.com/kingston-csj/jforgame)：JForGame是一个用Java编写的轻量级高性能手游服务端框架，包含游戏服、跨服、匹配服、后台管理系统等模块。
* [ByteLegend](https://github.com/ByteLegend/ByteLegend)：ByteLegend是一款免费、开源的MMORPG游戏，你可以在其中获得现实世界的高薪编程技能。
* [FriceEngine](https://github.com/icela/FriceEngine)：FriceEngine是一个简单、轻量级的原生游戏引擎，主要运行在JVM上。
* [TripleA](https://github.com/triplea-game/triplea)：TripleA是一款回合制策略游戏和棋盘游戏引擎，类似于Axis & Allies或Risk。
* [Delver](https://github.com/Interrupt/delverengine)：Delver游戏引擎和编辑器。
* [Zircon](https://github.com/Hexworks/zircon)：Zircon是一个可扩展且用户友好的多平台图块引擎。
* [Litiengine](https://github.com/gurkenlabs/litiengine)：LITIENGINE是一个免费且开源的Java 2D游戏引擎，它提供了一个全面的Java库和一个专用的地图编辑器来创建基于图块的2D游戏。
* [Artemis ODB](https://github.com/junkdog/artemis-odb)：Artemis ODB是一个基于Java的高性能实体组件系统框架。
* [Bladecoder Adventure](https://github.com/bladecoder/bladecoder-adventure-engine)：Bladecoder Adventure引擎是一组用于创建交互式图形冒险(经典点击游戏)的工具。
* [Mini2Dx](https://github.com/mini2Dx/mini2Dx)：Mini2Dx的主要目标是提供一个初学者友好、精通的框架，用于用Java快速原型设计和构建2D游戏。
* [LGame](https://github.com/cping/LGame)：一个跨平台的Java游戏引擎，支持JavaFX/Android/IOS/HTML5/Linux/MAC/Windows。
* [Forge](https://github.com/Card-Forge/forge)：世界上最伟大的纸牌游戏的非官方规则引擎。
* [LionEngine](https://github.com/b3dgs/lionengine)：LionEngine是专为Lionheart Remake项目开发的游戏引擎，可轻松与Java一起使用。
* [SilenceEngine](https://github.com/sriharshachilakapati/SilenceEngine)：SilenceEngine是一款2D/3D游戏引擎，可以为你处理游戏开发的低级方面，如图形、输入处理、资源加载和碰撞检测。
* [PlayN](https://github.com/playn/playn)：PlayN是一个用Java编写的跨平台Java游戏开发库，面向HTML5浏览器、桌面JVM、Android和iOS设备。
* [DimensioneX](https://www.dimensionex.net/)：DimensioneX是一款简单、免费的多人(MMORPG)游戏引擎。
* [Jake2](https://bytonic.de/html/jake2.html)：Quake II游戏引擎的Java端口。
* [Ashley](https://github.com/libgdx/ashley)：用Java编写的小型实体框架，它的灵感来自于Ash和Artemis等框架。
* [Slick2D](https://slick.ninjacave.com/)：Slick2D是一组易于使用的工具和实用程序，围绕LWJGL OpenGL绑定，使2D Java游戏开发变得更加容易。
* [Dyn4j](https://github.com/dyn4j/dyn4j)：纯Java 2D碰撞检测和物理引擎，旨在快速、稳定、可扩展且易于使用。
* [SquidLib](https://github.com/yellowstonegames/SquidLib)：SquidLib是一个功能非常齐全的库，部分目标是制作传统Roguelike和类似类型的游戏。
* [VASSAL](https://github.com/vassalengine/vassal)：VASSAL是一个游戏引擎，用于构建和玩在线改编的棋盘游戏和纸牌游戏。
* [Recast4j](https://github.com/ppiastucki/recast4j)：Recast和Detour导航网格工具集的Java端口。
* [ODE4j](https://github.com/tzaeschke/ode4j)：ODE是一个用于模拟刚体动力学的开源高性能库。
* [Libbulletjme](https://github.com/stephengold/Libbulletjme)：BulletPhysics和V-HACD的JNI接口。
* [Env3D](https://sourceforge.net/projects/env3d/)：用Java编写的3D引擎，面向计算机科学专业的学生。
* [JInput](https://github.com/jinput/jinput)：用于访问输入设备的库，由Sun公司游戏技术小组发起。
* [FastJ](https://github.com/fastjengine/FastJ)：FastJ是一个免费开源的基于Java的2D游戏引擎和框架，它旨在使用Java(和JVM语言)提供最佳的2D游戏制作体验。
* [Baritone](https://github.com/cabaletta/baritone)：Baritone是Impact从4.4版本开始使用的寻路系统。
* [SGDK](https://github.com/Stephane-D/SGDK)：适用于Sega Mega Drive的免费开源开发套件。
* [Kool](https://github.com/fabmax/kool)：Kool是一个多平台OpenGL/WebGPU/Vulkan游戏引擎，适用于桌面Java、Android和浏览器。
* [Alice](https://github.com/TheAliceProject/alice3)：Alice是一个基于块的创新编程环境，可以轻松创建动画、构建交互式叙述或以3D方式编写简单游戏，由CMU开源。
* [Talos](https://github.com/rockbite/talos)：基于节点的开源VFX编辑器，具有强大的界面和随时可用的LibGDX运行时。
* [Overlap2D](https://github.com/UnderwaterApps/overlap2d)：Overlap2D是一款2D关卡和UI编辑器，具有与引擎无关的游戏开发理念。
* [OpenRSC](https://github.com/Open-RSC/Core-Framework)：该仓库包含Open RuneScape Classic游戏框架。

## 2D/3D渲染

* [JMathPlot](https://github.com/yannrichet/jmathplot)：Java交互式2D和3D绘图。
* [VTM](https://github.com/mapsforge/vtm)：OpenGL矢量地图库-在 Android、iOS、桌面和浏览器上运行。
* [Constellation](https://github.com/constellation-app/constellation)：Constellation是一款以图形为中心的数据可视化和交互式分析应用程序，支持跨大型复杂数据集的数据访问、联合和操作功能。
* [Skija](https://github.com/JetBrains/skija)：Skia是一个开源2D图形库，提供可跨各种硬件和软件平台工作的通用API，Skija是Skia的高质量Java绑定，由JetBrains开源。
* [Jzy3d](https://github.com/jzy3d/jzy3d-api)：Jzy3d是一个用Java轻松绘制3D和2D图表的框架，使用快速原生GPU渲染或基于CPU的渲染来增强跨OS/JVM/GPU组合的可移植性。
* [Marlin](https://github.com/bourgesl/marlin-renderer)：Marlin是一个开源Java 2D渲染引擎，基于OpenJDK的Pisces实现，针对性能进行了优化(改进了内存使用和占用空间、更好的多线程)和更好的视觉质量。
* [Oreon](https://github.com/fynnfluegge/oreon-engine)：OpenGL/Vulkan Java 3D引擎。
* [LEGUI](https://github.com/SpinyOwl/legui)：Java OpenGL GUI库，专为与最新的LWJGL(LWJGL 3)一起使用而创建。
* [ImGui-Java](https://github.com/SpaiR/imgui-java)：ImGui基于JNI的绑定。
* [GraphicsFuzz](https://github.com/google/graphicsfuzz)：GraphicsFuzz提供了自动查找和简化图形驱动程序中的错误的工具，由Google开源。
* [ModernUI](https://github.com/BloCamLimb/ModernUI)：从低级3D图形API到高级视图模型的现代桌面框架，用于开发2D/3D渲染软件或游戏引擎，具有国际化支持和许多新技术。
* [Art of Illusion](https://github.com/ArtOfIllusion/ArtOfIllusion)：Art of Illusion是一个免费、开源的3D建模和渲染软件。
* [Scenery](https://github.com/scenerygraphics/scenery)：由Kotlin和Vulkan提供支持的JVM上体积和几何数据的灵活VR可视化。
* [Grafx](https://grafx.sourceforge.net/)：Grafx是一个开源Java库，用于使用浮点端点坐标绘制线条和填充多边形。

## 移动开发框架

* [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform)：Compose Multiplatform是一个声明式框架，用于使用Kotlin跨多个平台共享UI，由JetBrains开发。
* [React Native](https://github.com/facebook/react-native)：使用React构建原生应用程序的框架，由Facebook开源。
* [Hippy](https://github.com/Tencent/Hippy)：Hippy是一个跨平台的开发框架，旨在帮助开发者一次编写，在多个平台(iOS、Android、Web等)上运行，由腾讯开源。
* [CodenameOne](https://github.com/codenameone/CodenameOne)：Codename One是面向Java和Kotlin开发人员的移动优先跨平台环境。
* [DSBridge Android](https://github.com/wendux/DSBridge-Android)：一个现代的跨平台JavaScript桥梁，通过它你可以在JavaScript和Native之间同步或异步调用彼此的函数。
* [RIBs](https://github.com/uber/RIBs)：RIB是Uber的跨平台移动架构框架。
* [Multi-OS Engine](https://multi-os-engine.org/)：用于开发原生移动(iOS、Android等)应用程序的开源跨平台引擎。
* [MobileUI](https://mobileui.dev/)：MobileUI是第一个适用于iOS和Android的基于Java的原生UI框架。
* [Hummer](https://github.com/didi/Hummer)：Hummer是一套高性能高可用的跨端开发框架，一套代码可以同时支持开发Android和iOS应用，由滴滴开源。

## JVM代理

* [Spring-Loaded](https://github.com/spring-projects/spring-loaded)：Spring Loaded是一个JVM代理，用于在JVM运行时重新加载class文件更改。
* [Hotswap Agent](https://github.com/HotswapProjects/HotswapAgent)：Java无限运行时类和资源重定义。
* [BlockHound](https://github.com/reactor/BlockHound)：用于检测来自非阻塞线程的阻塞调用的Java代理。
* [One Java Agent](https://github.com/alibaba/one-java-agent)：One Java Agent提供插件化支持，统一管理众多的Java Agent，由阿里开源。
* [Dongtai-agent-java](https://github.com/HXSecurity/DongTai-agent-java)：DongTai Agent是针对Java应用程序的数据采集工具，由火线安全开源。
* [KnowAgent](https://github.com/didi/KnowAgent)：基于日志模板构建，采集任务动态管控、数据质量精确度量，一站式日志采集平台，由滴滴开源。
* [JRebel](http://zeroturnaround.com/software/jrebel/)：用于Java的热部署工具。
* [JADE](https://jade.tilab.com/)：用于构建和调试多代理系统的框架和环境。
* [Fakereplace](https://github.com/fakereplace/fakereplace)：该项目提供了一个JavaAgent和一个客户端，用于在标准JDK热交换提供的基础上热替换JVM中的类。
* [RR4J](https://github.com/Kartikvk1996/RR4J)：RR4J是一个记录Java字节码执行情况并允许开发人员在本地重放的工具。
* [AgentSmith](https://github.com/ffissore/agentsmith)：AgentSmith是一个Java代理，可以在应用程序运行时重新加载类。
* [Zorka](https://github.com/jitlogic/zorka)：Zorka是一个用于Java应用程序的可编程通用监控代理。
* [JVMQuake](https://github.com/Netflix-Skunkworks/jvmquake)：一个JVMTI代理，它附加到你的JVM，并在程序变得不稳定时自动发出信号并终止它，由Netflix开源。
* [Java-Debug-Tool](https://github.com/pandening/Java-debug-tool)：Java-Debug-Tool是一个动态调试工具，它提供了一些调试命令来在运行时调试你的代码。
* [inspectIT Ocelot](https://github.com/inspectIT/inspectit-ocelot)：inspectIT Ocelot是一个零配置Java代理，用于基于OpenCensus库动态收集应用程序性能、跟踪和行为数据。
* [LinkAgent](https://github.com/shulieTech/LinkAgent)：LinkAgent是一个基于Java的开源代理，旨在通过JVM字节码收集Java应用程序的数据和控制功能，而无需修改应用程序代码。
* [Joylive Agent](https://github.com/jd-opensource/joylive-agent)：用于多活(单元)场景下流量治理的Java字节码增强框架，由京东开源。
* [RelProxy](https://github.com/jmarranz/relproxy)：RelProxy是一个简单的Java和Groovy热类重加载器，适用于Java和Groovy，提供透明的动态编译和类重新加载，以及纯Java代码的脚本支持和Shell。
* [File Leak Detector](https://github.com/jenkinsci/lib-file-leak-detector)：File Leak Detector是一个小型Java代理，可以跟踪在JVM中打开文件的位置/时间/人员。

## 类加载

* [SOFAArk](https://github.com/sofastack/sofa-ark)：SOFAArk是一款基于Java实现的动态热部署和轻量级类隔离框架，由蚂蚁集团开源贡献，主要提供应用模块的动态热部署和类隔离能力。
* [JCL](https://github.com/kamranzafar/JCL)：JCL是一个可配置、动态且可扩展的自定义类加载器，可以直接从Jar文件和其他源加载Java类。
* [Java Dynamic Load Jar](https://github.com/Trinea/java-dynamic-load-jar)：解决在不同JAR中加载相同类时的类加载器隔离问题。
* [ModRun](https://github.com/nanosai/modrun)：ModRun可以直接从Maven仓库加载和运行类，并在运行时解决依赖关系。
* [Land](https://github.com/oldratlee/land)：Land是一个通过类加载器实现的简单Java依赖隔离容器。
* [JuShaTa](https://github.com/didi/JuShaTa)：JuShaTa是一个Java容器，提供模块隔离及模块热加载能力，由滴滴开源。
* [JBoss Modules](https://github.com/jboss-modules/jboss-modules)：JBoss Modules是Java模块化(非分层)类加载和执行环境的独立实现。
* [Classloader Leak Prevention](https://github.com/mjiderhamn/classloader-leak-prevention)：类加载器泄漏预防库。
* [Plexus Classworlds](https://github.com/codehaus-plexus/plexus-classworlds)：Plexus Classworlds是一个为需要复杂操作Java类加载器的容器开发人员提供的框架。
* [Cytodynamics](https://github.com/linkedin/Cytodynamics)：Cytodynamics是一个使JVM上的动态JAR加载和类加载器隔离变得简单的Java库，由LinkedIn开源。
* [XJar](https://github.com/core-lib/xjar)：Spring Boot JAR安全加密运行工具，同时支持的原生JAR。

## RISC-V

* [XiangShan](https://github.com/OpenXiangShan/XiangShan)：XiangShan是一款开源的高性能RISC-V处理器，中国科学院计算技术研究所开发。
* [RISC-V BOOM](https://github.com/riscv-boom/riscv-boom)：BOOM是一个可综合且可参数化的开源RV64GC RISC-V内核，采用Chisel硬件构造语言编写，由加州大学伯克利分校开源。
* [RARS](https://github.com/TheThirdOne/rars)：RISC-V汇编器和运行时模拟器。
* [Sedna](https://github.com/fnuecke/sedna)：Sedna是一个用Java编写的64位RISC-V模拟器，它实现了被视为“通用”所需的所有扩展以及管理模式，这意味着它可以引导Linux。
* [NutShell](https://github.com/OSCPU/NutShell)：NutShell是由OSCPU(大学开源芯片项目)团队开发的处理器。
* [Ventus(乘影) GPGPU](https://github.com/THU-DSP-LAB/ventus-gpgpu)：支持RISCV-V扩展的GPGPU处理器，使用Chisel HDL开发，由清华大学开源。

## 汇编

* [Jasmin](https://github.com/Sable/jasmin)：Jasmin是一个Java汇编器接口，由麦吉尔大学开源。
* [Iced](https://github.com/icedland/iced)：适用于Rust、.NET、Java、Python、Lua的快速且正确的x86/x64反汇编器、汇编器、解码器、编码器。
* [Smali](https://github.com/JesusFreke/smali)：Smali是Dalvik使用的dex格式的汇编器/反汇编器。
* [Krakatau](https://github.com/Storyyeller/Krakatau)：Krakatau提供了Java字节码的汇编器和反汇编器，它允许你将二进制class文件转换为人类可读的文本格式，进行更改，然后将其转换回class文件，甚至对于混淆的代码也是如此。
* [JASM](https://github.com/roscopeco/jasm)：现代JVM汇编器。

## LLVM

* [JLang](https://github.com/polyglot-compiler/JLang)：JLang向Polyglot编译器添加了LLVM后端，将Java转换为LLVM IR，由康奈尔大学开源。
* [LLFI](https://github.com/DependableSystemsLab/LLFI)：LLFI是一个基于LLVM的故障注入工具，它将故障注入到应用程序源代码的LLVM IR中，由不列颠哥伦比亚大学开源。
* [Maple-IR](https://github.com/LLVM-but-worse/maple-ir)：Maple-IR是一个基于工业IR的Java字节码静态分析框架。
* [Masxinlingvonta](https://github.com/superblaubeere27/masxinlingvonta)：将Java字节码编译为LLVM IR和本机代码。
* [JDA](https://github.com/LLVM-but-worse/java-disassembler)：JDA提供强大的静态分析工具，例如控制和数据流分析，以及使用自定义IL构建的代码简化。

## WebAssembly

* [Bytecoder](https://github.com/mirkosertic/Bytecoder)：用于将JVM字节码解释和转换为JavaScript、OpenCL或WebAssembly的框架。
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly)：Java字节码到WebAssembly的编译器。
* [TeaVM](https://github.com/konsoletyper/teavm)：用于将Java字节码编译为JavaScript、WebAssembly和C。
* [DoppioJVM](https://github.com/plasma-umass/doppio)：Doppio是一个兼容POSIX的运行时系统以及一个用TypeScript编写的JVM，也是马萨诸塞大学PLASMA小组的一个活跃的研究项目。
* [Asmble](https://github.com/cretz/asmble)：Asmble是一个将WebAssembly代码编译为JVM字节码的编译器，它还包含一个解释器和实用程序，用于从命令行和JVM语言处理WASM代码。
* [Wasmtime-Java](https://github.com/kawamuray/wasmtime-java)：Wasmtime的Java语言绑定。
* [CheerpJ](https://github.com/leaningtech/cheerpj-meta)：CheerpJ是一个基于WebAssembly的浏览器JVM，它与Java 8兼容，并提供完整的运行时环境，无需插件即可在浏览器中运行Java应用程序、Applet、库和Java Web Start/JNLP应用程序。
* [Chicory](https://github.com/dylibso/chicory)：Chicory是JVM原生WebAssembly运行时，它允许你以零本机依赖或JNI运行WebAssembly程序。
* [Wasmer](https://github.com/wasmerio/wasmer-java)：Java的WebAssembly运行时。

## JavaScript

* [Google Closure Compiler](https://github.com/google/closure-compiler)：Closure Compiler是一个使JavaScript下载和运行速度更快的工具，由Google开源。
* [GraalJS](https://github.com/oracle/graaljs)：JavaScript编程语言的高性能实现，由Oracle实验室基于GraalVM构建。
* [J2CL](https://github.com/google/j2cl)：J2CL是一个功能强大、简单且轻量级的从Java到Closure风格JavaScript的转译器，由Google开源。
* [Nashorn](https://github.com/openjdk/nashorn)：Nashorn的目标是使用原生JVM在Java中实现轻量级高性能JavaScript运行时。
* [Grakkit](https://github.com/grakkit/grakkit)：Minecraft的现代JavaScript开发环境。
* [Javet](https://github.com/caoccao/Javet)：在Java中嵌入Node.js和V8的绝佳方式。
* [Rhino](https://github.com/mozilla/rhino)：Rhino是完全用Java编写的JavaScript的开源实现，Mozilla开源。
* [PurpleJS](https://github.com/purplejs/purplejs)：PurpleJS是一个简单而强大的框架，用于在不离开JavaScript的情况下创建高性能的Web应用程序。
* [RingoJS](https://github.com/ringo/ringojs)：Ringo是一个基于JVM构建的JavaScript平台，并针对服务器端应用程序进行了优化。
* [Dynjs](https://github.com/dynjs/dynjs)：JVM的ECMAScript运行时。
* [Nodyn](https://github.com/nodyn/nodyn)：Nodyn是JVM上的Node.js兼容框架。
* [J2V8](https://github.com/eclipsesource/j2v8)：J2V8是V8的一组Java绑定，注重性能以及与V8的紧密集成。
* [LebJS](https://github.com/LebsterFace/LebJS)：LebJS是用Java编写的JavaScript引擎。

## 编译器&插件

* [VirtualAPK](https://github.com/didi/VirtualAPK)：VirtualAPK是一个强大而轻量级的Android插件框架，由滴滴开源。
* [Janin](https://github.com/janino-compiler/janino)：Janino是一个超小、超快的Java编译器。
* [BugVM](https://github.com/ibinti/bugvm)：BugVM使用独立的JVM将字节码编译为二进制代码。
* [RoboVM](https://github.com/robovm/robovm)：RoboVM编译器将Java字节码转换为本机ARM或x86代码，应用程序直接在CPU上运行，不涉及解释器或虚拟机。
* [Jarslink](https://github.com/sofastack/sofa-jarslink)：Jarslink是SOFABoot官方基于SOFAArk开发的功能插件，负责管理多应用在SOFAArk容器之上的合并部署，由蚂蚁开源。
* [Chronicle Runtime Compiler](https://github.com/OpenHFT/Java-Runtime-Compiler)：Java运行时编译器。
* [Java-OO](https://github.com/amelentev/java-oo)：Java-OO是Java编译器和IDE的模块化扩展，用于支持运算符重载(类似Scala)。
* [Manifold](https://github.com/manifold-systems/manifold)：Manifold是一个Java编译器插件，其功能包括元编程、属性、扩展方法、运算符重载、模板、预处理器等。
* [DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin)：DroidPlugin是一个新的插件框架，它使宿主应用程序无需安装、修改和重新打包即可运行任何第三方APK。
* [PF4J](https://github.com/pf4j/pf4j)：PF4J是一个开源的轻量级Java插件框架。
* [JTransc](https://github.com/jtransc/jtransc)：JTransc是一个AOT，它将.class和.jar文件编译为目标编程语言/可执行文件，将所有必需的依赖项捆绑在单个文件或文件夹中，无需抖动或外部运行时。
* [Apache Commons JCI](https://github.com/apache/commons-jci)：Apache Commons JCI是一个Java编译器接口，它可用于编译Java本身，或任何其他可编译为Java类的语言(例如Groovy或JavaScript)。
* [Deptitive](https://github.com/moditect/deptective)：Deptitive是javac的一个插件，它根据允许的依赖的描述来验证项目包之间的依赖关系，并在检测到任何无意的依赖关系时使编译失败。
* [Polyglot](https://github.com/polyglot-compiler/polyglot)：Polyglot是Java编程语言的高度可扩展的编译器前端，由康奈尔大学开源。
* [Jikes](https://jikes.sourceforge.net/)：Jikes是一个编译器，它将Java语言规范中定义的Java源文件转换为Java虚拟机规范中定义的字节码指令集和二进制格式，由IBM开源。
* [Qbicc](https://github.com/qbicc/qbicc)：Qbicc是一个实验性的Java原生镜像编译器。
* [Java Comment Preprocessor](https://github.com/raydac/java-comment-preprocessor)：具有类似C注释格式的计算机语言预处理器。
* [Apache Royale Compiler](https://github.com/apache/royale-compiler)：Apache Royale编译器将ActionScript 3.0和MXML代码编译为SWF或JavaScript。

## 语言服务器

* [JDT Language Server](https://github.com/eclipse-jdtls/eclipse.jdt.ls)：JDT语言服务器是语言服务器协议的Java语言特定实现，可以与支持该协议的任何编辑器一起使用，为Java语言提供良好的支持。
* [Smithy](https://github.com/smithy-lang/smithy)：一种与协议无关的接口定义语言和一组工具，用于为任何编程语言生成客户端、服务器和文档。
* [Eclipse LSP4J](https://github.com/eclipse-lsp4j/lsp4j)：语言服务器协议的Java实现，旨在由用Java实现的工具和语言服务器使用。
* [Language Server](https://github.com/georgewfraser/java-language-server)：基于协议v3.0并使用Java编译器API实现的Java语言服务器。
* [Eclipse LemMinX](https://github.com/eclipse/lemminx)：语言服务器协议的XML语言特定实现，可以与支持该协议的任何编辑器一起使用，为XML语言提供良好的支持。
* [Groovy Language Server](https://github.com/GroovyLanguageServer/groovy-language-server)：Groovy的语言服务器。
* [Lsp4IntelliJ](https://github.com/ballerina-platform/lsp4intellij)：Lsp4IntelliJ是一个客户端库，为IntelliJ IDEA和其他Jetbrains IDE提供语言服务器支持。
* [Build Server Protocol](https://github.com/build-server-protocol/build-server-protocol)：该项目致力于改进语言服务器/编辑器和构建工具之间的集成，由Scala中心和JetBrains领导。
* [BSL Language Server](https://github.com/1c-syntax/bsl-language-server)：BSL语言服务器协议的实现。

## 数据库驱动

* [MongoDB](https://github.com/mongodb/mongo-java-driver)：适用于Java、Kotlin和Scala的官方MongoDB驱动程序。
* [Postgresql](https://github.com/pgjdbc/pgjdbc)：Postgresql JDBC驱动程序。
* [Postgresql R2DBC](https://github.com/pgjdbc/r2dbc-postgresql)：Postgresql R2DBC驱动程序。
* [MySQL](https://github.com/mysql/mysql-connector-j)：MySQL JDBC驱动程序。
* [AWS MySQL JDBC](https://github.com/awslabs/aws-mysql-jdbc)：AWS MySQL Driver是一个使应用程序能够充分利用集群MySQL数据库功能的驱动程序。
* [Oracle](https://www.oracle.com/database/technologies/maven-central-guide.html)：Oracle JDBC驱动程序。
* [Oracle R2DBC](https://github.com/oracle/oracle-r2dbc)：Oracle数据库的R2DBC驱动程序。
* [SqlServer](https://github.com/microsoft/mssql-jdbc)：SqlServer JDBC驱动程序。
* [R2DBC MySQL](https://github.com/mirromutth/r2dbc-mysql)：该项目包含R2DBC SPI的MySQL实现。
* [R2DBC SPI](https://github.com/r2dbc/r2dbc-spi)：R2DBC实现的SPI。
* [R2DBC MSSQL](https://github.com/r2dbc/r2dbc-mssql)：使用TDS协议的SQLServer的R2DBC驱动程序。
* [MariaDB R2DBC](https://github.com/mariadb-corporation/mariadb-connector-r2dbc)：非阻塞MariaDB和MySQL客户端。
* [ElasticSearch](https://github.com/elastic/elasticsearch-java)：Elasticsearch官方Java客户端。
* [Jest](https://github.com/searchbox-io/Jest)：Jest是ElasticSearch的Java HTTP REST客户端。
* [Bboss](https://github.com/bbossgroups/bboss-elasticsearch)：ElasticSearch高级Java REST客户端API。
* [Flummi](https://github.com/otto-de/flummi)：Flummi是ElasticSearch的客户端库，提供了全面的Java查询DSL API，并通过HTTP/JSON与ElasticSearch集群进行通信。
* [Redisson](https://github.com/redisson/redisson)：Redisson是一个具有内存数据网格功能的Redis Java客户端。
* [Jedis](https://github.com/redis/jedis)：Redis的Java客户端，旨在提高性能和易用性。
* [Lettuce](https://github.com/lettuce-io/lettuce-core)：高级Java Redis客户端，用于线程安全同步、异步和响应式使用。支持集群、哨兵、管道和编解码器。
* [Influx4j](https://github.com/brettwooldridge/influx4j)：适用于InfluxDB的高性能、零垃圾Java客户端/驱动程序。
* [JRedis](https://github.com/alphazero/jredis)：Redis的Java客户端和连接器。
* [Redis Protocol](https://github.com/spullara/redis-protocol)：Redis的Java客户端和服务端实现。
* [OceanBase Client](https://github.com/oceanbase/obconnector-j)：兼容JDBC 4.2的OceanBase Java驱动程序。
* [DataStax Java Driver](https://github.com/datastax/java-driver)：适用于Cassandra的DataStax Java驱动程序。
* [Astyanax](https://github.com/Netflix/astyanax)：Cassandra Java客户端库，由Netflix开源。
* [Folsom](https://github.com/spotify/folsom)：Java的异步Memcache客户端库，由Spotify开源。
* [SQLite JDBC](https://github.com/xerial/sqlite-jdbc)：用于在Java中访问和创建SQLite数据库文件的库。
* [Couchbase](https://github.com/couchbase/couchbase-java-client)：Couchbase Server的官方Java客户端。
* [InfluxDB Java](https://github.com/influxdata/influxdb-java)：InfluxDB的官方Java客户端库。
* [InfluxDB2 Java](https://github.com/influxdata/influxdb-client-java)：适用于JVM的InfluxDB 2客户端。
* [XMemcached](https://github.com/killme2008/xmemcached)：Java中的高性能、易于使用的多线程Memcached客户端。
* [ClickHouse Java](https://github.com/ClickHouse/clickhouse-java)：用于连接ClickHouse并处理各种格式数据的Java库。
* [Neo4j Java Driver](https://github.com/neo4j/neo4j-java-driver)：Neo4j的官方Java驱动程序。
* [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client)：用Java编写的高性能响应式SQL客户端。
* [Hibernate Reactive](https://github.com/hibernate/hibernate-reactive)：Hibernate ORM的响应式API，支持非阻塞数据库驱动程序以及与数据库的响应式交互。
* [Snowflake JDBC Driver](https://github.com/snowflakedb/snowflake-jdbc)：Snowflake JDBC驱动程序。
* [JAsync-SQL](https://github.com/jasync-sql/jasync-sql)：JAsync-SQL是一个使用Kotlin编写的简单、基于Netty、异步、高性能且可靠的PostgreSQL和MySQL数据库驱动程序。
* [Cassandra Java Driver](https://github.com/apache/cassandra-java-driver)：Apache Cassandra的Java驱动程序。
* [ClickHouse Native JDBC](https://github.com/housepower/ClickHouse-Native-JDBC)：用于在Java 中访问ClickHouse的原生JDBC库，还提供用于与Apache Spark集成的库。
* [VtDriver](https://github.com/jd-opensource/vtdriver)：VtDriver是一套基于分布式数据库Vitess而开发的Vitess Java客户端解决方案，由京东开源。
* [Aerospike Java Client](https://github.com/aerospike/aerospike-client-java)：Aerospike数据库的Java客户端库。
* [OpenGauss JDBC](https://gitee.com/opengauss/openGauss-connector-jdbc)：OpenGauss JDBC驱动程序。
* [Jackcess](https://github.com/jahlborn/jackcess)：Jackcess是一个纯Java库，用于读取和写入MS Access数据库。
* [Nebula Java](https://github.com/vesoft-inc/nebula-java)：Nebula Graph的Java客户端和数据导入器。

## 数据库迁移

* [Liquibase](https://github.com/liquibase/liquibase)：Liquibase是一种数据库模式变更管理解决方案，使你能够更快、更安全地修改和发布从开发到生产的数据库变更。
* [Flyway](https://github.com/flyway/flyway)：Flyway是一款开源的数据库版本管理工具，它更倾向于规约优于配置的方式。
* [Obevo](https://github.com/goldmansachs/obevo)：Obevo是一种数据库部署工具，可处理企业规模的架构和复杂性，由高盛银行开源。
* [Mybatis Migrations](https://github.com/mybatis/migrations)：命令行数据库迁移工具。
* [Cassandra Migration](https://github.com/Contrast-Security-OSS/cassandra-migration)：一个简单且轻量级的Apache Cassandra数据库迁移工具，基于Flyway项目。
* [Cassandra Schema Migration](https://github.com/patka/cassandra-migration)：该库可用于在Java应用程序内实现Cassandra数据库模式的迁移。
* [Mongolastic](https://github.com/ozlerhakan/mongolastic)：Mongolastic使你能够将数据集从MongoDB节点迁移到ElasticSearch节点，反之亦然。
* [Datafall](https://github.com/forcedotcom/Data-Migration-Tool)：Datafall 是一种将数据从一个Salesforce组织迁移到另一个Salesforce组织的工具。
* [Neo4j-Migrations](https://github.com/michael-simons/neo4j-migrations)：Neo4j-Migrations是一种数据库迁移和重构工具，允许以受控且可重复的方式针对一个或多个Neo4j数据库运行Cypher脚本和编程重构。
* [Cassandra Migration](https://github.com/smartcat-labs/cassandra-migration-tool-java)：适用于Java的Cassandra模式迁移工具。
* [COS Migration](https://github.com/tencentyun/cos_migrate_tool_v5)：COS Migration是一个集成了COS数据迁移功能的一体化工具，由腾讯开源。
* [OSSImport](https://help.aliyun.com/zh/data-online-migration/user-guide/ossimport-overview)：OSSImport是阿里的一款将数据迁移至OSS的商业工具。
* [Celesta](https://github.com/CourseOrchestra/celesta)：Java的数据库迁移、SQL和测试工具。
* [Elasticsearch-Evolution](https://github.com/senacor/elasticsearch-evolution)：用于迁移Elasticsearch映射的库。
* [Migrate2Postgres](https://github.com/isapir/Migrate2Postgres)：该工具允许你轻松地将数据库从其他兼容JDBC的DBMS迁移到Postgres。
* [CQLMigrate](https://github.com/sky-uk/cqlmigrate)：CQLMigrate是一个用于在Cassandra集群上执行模式迁移的库。
* [Couchmove](https://github.com/tchlyah/couchmove)：Couchmove是Couchbase的开源Java迁移工具。
* [MongoBee](https://github.com/mongobee/mongobee)：Java版MongoDB数据迁移工具。
* [Mongock](https://github.com/mongock/mongock)：Mongock是一个基于Java的迁移工具，作为应用程序代码的一部分。
* [Solidbase](https://github.com/gitbucket/solidbase)：基于Liquibase的RDBMS和其他资源的通用迁移工具。
* [R2DBC Migration](https://github.com/nkonev/r2dbc-migrate)：R2DBC数据库迁移库。

## 数据源增强

* [Dynamic-DataSource](https://github.com/baomidou/dynamic-datasource)：Dynamic-DataSource是一个基于Spring Boot的快速集成多数据源的Starter。
* [DataSource-Proxy](https://github.com/jdbc-observations/datasource-proxy)：DataSource-Proxy提供简单的API来拦截JDBC交互，并允许用户在查询或方法执行之前/之后执行自己的逻辑。

## 对象存储

* [Aliyun OSS](https://github.com/aliyun/aliyun-oss-java-sdk)：Aliyun OSS的Java SDK。
* [Aliyun OSS Android](https://github.com/aliyun/aliyun-oss-android-sdk)：阿里云对象存储服务Android SDK。
* [Ambry](https://github.com/linkedin/ambry)：Ambry是一个分布式对象存储，支持存储数万亿个小型不可变对象(50K-100K)以及数十亿个大型对象，由LinkedIn开发。
* [MinIO](https://github.com/minio/minio-java)：用于Java的MinIO客户端SDK。
* [X File Storage](https://gitee.com/dromara/x-file-storage)：将文件存储到各种云平台的Spring Boot库。
* [OSS Spring Boot](https://github.com/pig-mesh/oss-spring-boot-starter)：兼容S3协议的通用文件存储工具类。
* [Syncany](https://github.com/syncany/syncany)：Syncany是一款云存储和文件共享应用程序，重点关注存储的安全性和抽象性。
* [Qiniu Resource Storage SDK](https://github.com/qiniu/java-sdk)：七牛资源存储Java SDK。
* [KSAN](https://github.com/infinistor/ksan)：KSAN是一个软件定义的对象存储系统，旨在可靠、高效地提供大规模对象存储服务。
* [Huawei OBS](https://github.com/huaweicloud/huaweicloud-sdk-java-obs)：用于访问对象存储服务的OBS Java SDK。

## 音视频处理

* [Jitsi](https://github.com/jitsi/jitsi)：Jitsi Desktop是一款免费的开源音频/视频和聊天通信器，支持SIP、XMPP/Jabber、IRC等协议和许多其他有用的功能。
* [Sndcpy](https://github.com/rom1v/sndcpy)：Android音频转发工具。
* [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor)：Metadata Extractor是一个用于从媒体文件中读取元数据的Java库。
* [Horizon](https://github.com/Yalantis/Horizon)：Horizon是适用于Android的简单视觉均衡器。
* [RxAndroidAudio](https://github.com/Piasy/RxAndroidAudio)：Android音频封装库，部分Rx支持。
* [Airsonic](https://github.com/airsonic/airsonic)：Airsonic是一款免费的基于网络的媒体流媒体，可让你随时随地访问音乐。
* [TarsosDSP](https://github.com/JorenSix/TarsosDSP)：TarsosDSP是一个用于音频处理的Java库，其目的是为实用的音乐处理算法提供一个易于使用的接口。
* [FFmpeg CLI Wrapper](https://github.com/bramp/ffmpeg-cli-wrapper)：用于从Java运行FFmpeg的流式接口。
* [WaveInApp](https://github.com/Cleveroad/WaveInApp)：可以从任何来源(音频播放器、流、语音输入)获取音频，并以高帧速率为其制作动画。
* [Alexa Skills Kit Java SDK](https://github.com/alexa/alexa-skills-kit-sdk-for-java)：Alexa是Amazon基于云的语音服务，可在亚马逊和第三方设备制造商的数亿台设备上使用。
* [OpenAudible](https://github.com/openaudible/openaudible)：用于下载和管理Audible有声读物的跨平台桌面应用程序。
* [LiveBox](https://github.com/parzulpan/livebox)：LiveBox是一个跨平台的网络媒体聚合应用，支持直播视频、高清电视和广播电台的在线观看或收听。
* [Phon](https://github.com/phon-ca/phon)：Phon是一个软件程序，可以极大地促进与基于转录和声学测量的语音数据分析相关的许多任务，由纽芬兰纪念大学开源。
* [JAVE2](https://github.com/a-schild/jave2)：JAVE库是ffmpeg项目的Java包装器。
* [JCodec](https://github.com/jcodec/jcodec)：JCodec是视频/音频编解码器的纯Java实现。
* [Opencast](https://github.com/opencast/opencast)：Opencast是一个灵活、可靠、可扩展的开源视频管理系统，适用于学术机构，由来自全球领先大学和组织的开发人员社区构建。
* [LavaPlayer](https://github.com/sedmelluq/lavaplayer)：LavaPlayer是一个用Java编写的音频播放器库，它可以从各种源加载音轨并将其转换为Opus帧流，专为Discord机器人使用而设计。
* [Quick Media](https://github.com/liuyueyi/quick-media)：多媒体处理Web服务。
* [OmRecorder](https://github.com/kailash09dabhi/OmRecorder)：一个简单的Pcm/Wav录音机。
* [Sphinx-4](https://github.com/cmusphinx/sphinx4)：纯Java语音识别库，由美国卡内基梅隆大学开发。
* [Photon](https://github.com/Netflix/photon)：Photon是IMF标准的Java实现，由Netflix开源。
* [Concentus](https://github.com/lostromb/concentus)：Opus音频编解码器的纯可移植C#和Java实现。
* [WVP-GB28181](https://github.com/648540858/wvp-GB28181-pro)：Web Video Platform是一个基于GB28181-2016标准实现的开箱即用的网络视频平台，负责实现核心信令与设备管理后台部分，支持NAT穿透，支持海康、大华、宇视等品牌的IPC、NVR接入。
* [Minim](https://github.com/ddf/Minim)：一个Java音频库，设计用于与Processing一起使用。
* [Audiveris](https://github.com/Audiveris/audiveris)：Audiveris是一款开源光学音乐识别(OMR)软件，它用于扫描乐谱并将其转换为机器可读的格式，例如MusicXML或MIDI。
* [libjitsi](https://github.com/jitsi/libjitsi)：用于安全实时音频/视频通信的高级Java媒体库。
* [MP4 Parser](https://github.com/sannies/mp4parser)：用于读取、写入和创建MP4容器的Java API，操作容器与编码和解码视频和音频不同。
* [LiTr](https://github.com/linkedin/LiTr)：适用于Android的轻量级硬件加速视频/音频转码器。
* [AudioBookConverter](https://github.com/yermak/AudioBookConverter)：基于freeipod软件版本改进的AudioBookConverter(mp3到m4b转换器)。
* [Echoprint Server](https://github.com/spotify/echoprint-server)：Echoprint音频指纹系统服务器，由Spotify开源。
* [Monte Media Library](http://www.randelshofer.ch/monte/)：Monte Media Library是一个用于处理媒体数据的Java库，支持的媒体格式包括静态图像、视频、音频和元数据。
* [jPSXdec](https://github.com/m35/jpsxdec)：一款现代的跨平台PlayStation 1音频/视频转换器。
* [Beat-Link](https://github.com/Deep-Symmetry/beat-link)：一个Java库，用于与Pioneer DJ Link设备的节拍同步，并查找有关正在播放的曲目的详细信息。
* [JJazzLab-X](https://github.com/jjazzboss/JJazzLab-X)：一个完整的基于Midi的自动背景音乐生成框架。
* [OSCI Render](https://github.com/jameshball/osci-render)：用于通过使用音频输出在示波器上绘制对象、文本和图像来制作音乐的合成器。
* [Humble Video](https://github.com/artclarke/humble-video)：HumbleVideo允许JVM语言对音频和视频数据进行解码、分析/修改和编码为数百种不同格式(例如H264、AAC、MP3、FLV等)。
* [Supersonic](https://github.com/Mach5/supersonic)：基于网络的开源媒体流媒体和点唱机分支Subsonic，支持MP3、OGG、AAC等流媒体音视频格式。
* [Jave](https://github.com/dadiyang/jave)：音频转码工具，主要用于将微信语音amr格式转换为mp3格式以便在H5的audio标签中进行播放。
* [JSyn](https://github.com/philburk/jsyn)：Java模块化音频合成器。
* [JLayer](https://github.com/umjammer/jlayer)：为Java平台实时解码/播放/转换MPEG 1/2/2.5 Layer 1/2/3(即MP3)的库。
* [Jaudiotagger](https://bitbucket.org/ijabz/jaudiotagger)：Jaudiotagger是音频标记库，用于标记音频文件中的数据。
* [MaryTTS](https://github.com/marytts/marytts)：MaryTTS是一个用纯Java编写的开源、多语言文本到语音合成系统。
* [Universal Media Server](https://github.com/UniversalMediaServer/UniversalMediaServer)：Universal Media Server是兼容DLNA的UPnP媒体服务器，它能够在大多数现代设备之间共享视频、音频和图像。
* [Smallville](https://github.com/nickm980/smallville)：生成代理是虚拟角色，可以存储记忆并对环境做出动态反应。
* [Rebound](https://github.com/facebookarchive/rebound)：Rebound是一个模拟弹簧动力学的Java库，由Facebook开源。
* [Vlcj](https://github.com/caprica/vlcj)：vlc媒体播放器的Java框架。
* [MP3agic](https://github.com/mpatric/mp3agic)：用于读取MP3文件和读取/操作ID3标签(ID3v1和ID3v2.2到ID3v2.4)的Java库。
* [Jaffree](https://github.com/kokorin/Jaffree)：Jaffree代表Java FFmpeg和FFprobe FREE命令行包装器。
* [Processing Video](https://github.com/processing/processing-video)：基于GStreamer的视频处理库。
* [M3U8-Parser](https://github.com/carlanton/m3u8-parser)：适用于Java的简单HLS播放列表解析器。
* [Panako](https://github.com/JorenSix/Panako)：Panako是一种声学指纹识别系统，该系统能够从音频流中提取指纹，并将这些指纹存储在数据库中，或者在提取的指纹和存储的指纹之间找到匹配。
* [JNAJack](https://github.com/jaudiolibs/jnajack)：JACK音频连接套件的Java绑定。
* [FFmpeg4j](https://github.com/Manevolent/ffmpeg4j)：FFmpeg4j是一个Java库，它封装了FFmpeg库的功能。
* [WhisperJNI](https://github.com/GiviMAD/whisper-jni)：whisper.cpp的JNI包装器，允许将语音转录为Java中的文本。
* [XYScope](https://github.com/ffd8/xyscope)：XYScope是一个处理库，用于通过将图形转换为音频来在矢量显示器(示波器、激光)上渲染图形。
* [SoundLibs](https://github.com/pdudits/soundlibs)：Java声音库的Maven工件。
* [RootEncoder](https://github.com/pedroSG94/RootEncoder)：RootEncoder是一个流编码器，使用RTMP、RTSP和SRT协议将视频/音频推送到媒体服务器。
* [FreeTTS](https://freetts.sourceforge.io/)：FreeTTS是一个完全用Java编程语言编写的语音合成系统。
* [LibSDL4J](https://github.com/libsdl4j/libsdl4j)：LibSDL4J是SDL2 API到Java的映射。
* [GStreamer 1.x Java Core](https://github.com/gstreamer-java/gst1-java-core)：这是GStreamer 1.x的一组Java绑定，GStreamer是一个用C语言编写的开源、基于管道的多媒体框架。
* [Video4j](https://github.com/metaloom/video4j)：Video4j是org.openpnp:opencv之上的高级库，它提供API在Java中处理视频媒体。
* [ZLM4J](https://gitee.com/aizuda/zlm4j)：本项目是对ZLMediaKit提供的C API的Java封装，由爱组搭开源。
* [Tracker](https://github.com/OpenSourcePhysics/tracker)：基于开源物理(OSP)框架构建的视频分析和建模工具。

## 数据结构

* [Cassovary](https://github.com/twitter/cassovary)：Cassovary是一个简单的JVM大图处理库，由Twitter开源。
* [T-Digest](https://github.com/tdunning/t-digest)：一种新的数据结构，用于准确在线累积基于排名的统计数据，例如分位数和修剪平均值。
* [Bifurcan](https://github.com/lacuna/bifurcan)：该库提供了可变和不可变数据结构的高质量Java实现，每个实现都共享一个通用API。
* [RTree](https://github.com/davidmoten/rtree)：使用响应式API在Java中实现不可变的内存中R树和R*树。
* [Tree](https://github.com/Scalified/tree)：该库包含树数据结构的不同实现，例如K进制、二叉树、表达式树等。
* [BTree4j](https://github.com/myui/btree4j)：Btree4j是一个用纯Java编写的基于磁盘的B+树。
* [Sux4J](https://github.com/vigna/Sux4J)：Sux4J提供了许多相关数据结构的实现，涵盖位数组、压缩列表和最小完美哈希函数的排名/选择。
* [Conversant](https://github.com/conversant/disruptor)：Conversant Disruptor是环形缓冲区中性能最高的实现，它几乎没有开销，并且采用了特别简单的设计。
* [NetflixGraph](https://github.com/Netflix/netflix-graph)：NetflixGraph是一种紧凑的内存数据结构，用于表示有向图数据，由Netflix开源。
* [BPlusTree](https://github.com/andylamp/BPlusTree)：一种高效、简洁、简单的纯磁盘B+Tree数据结构实现。
* [NetworkAnalysis](https://github.com/CWTSLeiden/networkanalysis)：该库提供了用于网络分析的算法和数据结构，专注于网络的聚类(或社区检测)和布局(或映射)。
* [Time-Utilities](https://github.com/Breinify/brein-time-utilities)：包含多个时间相关数据和索引结构(例如IntervalTree、BucketTimeSeries)以及算法的库。
* [Lin-Check](https://github.com/devexperts/lin-check)：Lin-Check是一个用于测试并发数据结构正确性的框架，Devexperts开源。
* [Funcj](https://github.com/typemeta/funcj)：用于Java的面向函数的数据结构、算法和库的集合。
* [Athena](https://github.com/sanity/Athena)：支持任意布尔查询的高效内存数据结构。
* [SparseBitSet](https://github.com/brettwooldridge/SparseBitSet)：Java的高效稀疏位集实现。
* [Agrona](https://github.com/real-logic/Agrona)：Agrona提供了一个数据结构和实用方法库，这是用Java构建高性能应用程序时常见的需求。
* [Concurrent Trees](https://github.com/npgall/concurrent-trees)：Java的并发Radix和后缀树。
* [Apache Commons Flatfile](https://commons.apache.org/sandbox/commons-flatfile)：Commons Flatfile是一个用于处理平面数据结构的Java库。
* [Tape](https://github.com/square/tape)：Android和Java中与队列相关的类的集合。
* [JUnion](https://github.com/TehLeo/junion)：为Java编程语言提供结构类型。
* [Big Queue](https://github.com/bulldog2011/bigqueue)：基于内存映射文件的大、快速且持久的队列。
* [Low GC MemBuffers](https://github.com/cowtowncoder/low-gc-membuffers)：用于创建内存循环缓冲区的库，该缓冲区使用直接ByteBuffer来最大限度地减少GC开销。
* [LMDB JNI](https://github.com/deephacks/lmdbjni)：LMDB JNI为LMDB提供Java API，LMDB是Symas为OpenLDAP项目开发的超快速、超紧凑的键值嵌入式数据存储。
* [Stream Lib](https://github.com/addthis/stream-lib)：一个Java库，用于汇总无法存储所有事件的流中的数据。
* [Trie4J](https://github.com/takawitter/trie4j)：Trie4J是各种trie实现的排序集合。
* [CuckooFilter4J](https://github.com/MGunlogson/CuckooFilter4J)：Cuckoo过滤器的高性能Java实现。
* [HyperMinHash-Java](https://github.com/LiveRamp/HyperMinHash-java)：用于计算对数空间中的并集、交集和集合基数的概率数据结构。
* [Dictomaton](https://github.com/danieldk/dictomaton)：该Java库实现存储在有限状态自动机中的字典。
* [PH-Tree](https://github.com/tzaeschke/phtree)：PH-Tree是一种多维索引和存储结构，默认情况下，它存储由k个64位整数组成的k维键(点)。
* [Suffix Tree](https://github.com/abahgat/suffixtree)：使用Ukkonen算法的广义后缀树的Java实现。
* [Chronicle-Values](https://github.com/OpenHFT/Chronicle-Values)：通过接口生成Bean的堆上实现。
* [Java-Concurrent-Hash-Trie-Map](https://github.com/romix/java-concurrent-hash-trie-map)：这是来自Scala集合库的并发trie HashMap实现的Java端口。
* [TinSpin Indexes](https://github.com/tzaeschke/tinspin-indexes)：TinSpin Indexes是一个内存索引库。
* [Chronicle](https://github.com/peter-lawrey/Java-Chronicle)：Chronicle是一个超低延迟、高吞吐量、持久化、消息传递和事件驱动的内存数据库。
* [LSM-Tree](https://github.com/tomfran/LSM-Tree)：Java中日志结构合并树(LSM Tree)数据结构的实现。
* [JavaEWAH](https://github.com/lemire/javaewah)：Java BitSet类的压缩替代方案。
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap)：Java中更好的压缩位集。
* [Setfilters](https://github.com/google/setfilters)：该仓库包含集合过滤器数据结构的集合的实现，通常也称为近似成员资格查询数据结构，由Google开源。
* [Wurmloch CRDT](https://github.com/netopyr/wurmloch-crdt)：JVM无冲突复制数据类型(CRDT)的实验实现。

## 基本类型

* [jOOU](https://github.com/jOOQ/jOOU)：jOOU为四种Java整数类型byte、short、int和long提供无符号整数版本。
* [Primitive](https://github.com/mintern-java/primitive)：Primitive提供与基本类型相关的功能的实用方法，包括基于自定义比较器的排序和搜索。

## 堆外内存管理

* [Unsafe Tool](https://github.com/alexkasko/unsafe-tools)：使用sun.misc.Unsafe处理堆外内存的工具。
* [LLPL](https://github.com/pmem/llpl)：LLPL是一个Java库，提供对堆外持久性内存的访问。
* [Slice](https://github.com/airlift/slice)：用于高效处理堆内存和堆外内存的Java库。
* [Externalsortinginjava](https://github.com/lemire/externalsortinginjava)：Java中的外部内存排序。
* [FastTuple](https://github.com/boundary/fasttuple)：在堆内和堆外内存中相邻布置的集合。
* [Chronicle Core](https://github.com/OpenHFT/Chronicle-Core)：Chronicle Core是一个先进的低级库，为开发人员提供了与操作系统交互、管理内存、处理资源等功能强大的工具。
* [DataSketches Java Memory Component](https://github.com/apache/datasketches-memory)：Java的高性能本机内存访问库。
* [LArray](https://github.com/xerial/larray)：一个用于管理大型堆外数组的库，可以在Java和Scala中容纳超过2G(2^31)的条目。

## 布隆过滤器

* [Orestes Bloomfilter](https://github.com/Baqend/Orestes-Bloomfilter)：Java中不同布隆过滤器的库，具有可选的Redis支持、计数和许多哈希选项。
* [inbloom](https://github.com/EverythingMe/inbloom)：跨语言布隆过滤器实现。
* [JRedisBloom](https://github.com/RedisBloom/JRedisBloom)：RedisBloom概率模块的Java客户端。
* [Bloom Filter Scala](https://github.com/alexandrnikitin/bloom-filter-scala)：Scala的布隆过滤器。
* [Greplin Bloom Filter](https://github.com/Cue/greplin-bloom-filter)：概率集合数据结构的Java实现。
* [PDD](https://github.com/jparkie/PDD)：基于高级布隆过滤器的算法，可在流中实现高效的近似数据去重复。
* [Minperf](https://github.com/thomasmueller/minperf)：极小的完美哈希函数库。
* [Bloofi](https://github.com/lemire/bloofi)：多维布隆过滤器的Java实现。

## 算法库

* [TLAPlus](https://github.com/tlaplus/tlaplus)：TLC是一个显式状态模型检查器，用于检查以TLA+编写的规范，TLA+Toolbox是TLA+的IDE。
* [Hashids.java](https://github.com/yomorun/hashids-java)：Hashids算法Java实现。
* [AhoCorasickDoubleArrayTrie](https://github.com/hankcs/AhoCorasickDoubleArrayTrie)：基于双数组Trie结构的Aho-Corasick算法的极快实现。
* [Apache DataSketches](https://github.com/apache/datasketches-java)：Yahoo开源的随机流算法软件库。
* [Graph Neo4j](https://github.com/neo4j-contrib/neo4j-graph-algorithms)：Neo4j的高效图算法。
* [JavaWuzzy](https://github.com/xdrop/fuzzywuzzy)：FuzzyWuzzy模糊字符串匹配算法的Java实现。
* [Carrot2](https://github.com/carrot2/carrot2)：用于聚类文本的编程库。
* [Mathematical Finance Library](https://github.com/finmath/finmath-lib)：提供了与数学金融相关的方法的JVM实现。
* [Java-LSH](https://github.com/tdebatty/java-LSH)：局部敏感哈希(LSH)的Java实现。
* [Viterbi](https://github.com/hankcs/Viterbi)：通用的维特比算法实现。
* [3d-bin-container-packing](https://github.com/skjolber/3d-bin-container-packing)：最大区域拟合优先算法+暴力算法的变体。
* [Hipster4j](https://github.com/citiususc/hipster)：一个轻量级且功能强大的Java和Android启发式搜索库，它包含常见的、完全可定制的算法，例如Dijkstra、A*、DFS、BFS、Bellman-Ford等。
* [Java HyperLogLog](https://github.com/aggregateknowledge/java-hll)：HyperLogLog算法的Java库。
* [Min2phase](https://github.com/cs0x7f/min2phase)：Kociemba两阶段算法的优化实现。
* [k-NN](https://github.com/opendistro-for-elasticsearch/k-NN)：一个机器学习插件，支持Open Distro的近似k-NN搜索算法。
* [ABAGAIL](https://github.com/pushkar/ABAGAIL)：该库包含许多互连的Java包，用于实现机器学习和人工智能算法。
* [JWave](https://github.com/graetz23/JWave)：离散傅里叶变换、快速小波变换和小波包变换算法的Java实现。
* [Dexter](https://github.com/dexter/dexter)：Dexter是一个框架，它实现了一些流行的算法，并提供了开发任何实体链接技术所需的所有工具。
* [ASTRAL](https://github.com/smirarab/ASTRAL)：一种在给定一组无根基因树的情况下估计无根物种树的工具。
* [Shamir](https://github.com/codahale/shamir)：Shamir的秘密共享算法在GF(256)上的Java实现。
* [TarsosLSH](https://github.com/JorenSix/TarsosLSH)：一个实现次线性最近邻搜索算法的Java库，它包含近似搜索算法和精确搜索算法。
* [RendezvousHash](https://github.com/clohfink/RendezvousHash)：基于环的一致哈希的替代方案，这是Rendezvous(最高随机权重，HRW)哈希的快速线程安全实现。
* [T-SNE-Java](https://github.com/lejon/T-SNE-Java)：Van Der Maaten和Hinton的t-SNE聚类算法的纯Java实现。
* [Streaminer](https://github.com/mayconbordin/streaminer)：用于挖掘数据流的算法集合，包括频繁项集、分位数、采样、移动平均、集合成员资格和基数。
* [Patricia-Trie](https://github.com/rkapsi/patricia-trie)：检索以字母数字编码的信息的实用算法。
* [LearnLib](https://github.com/LearnLib/learnlib)：一个免费的开源Java库，用于自动机学习算法。
* [Simhash Java](https://github.com/sing1ee/simhash-java)：Simhash算法的Java简单实现。
* [Junto](https://github.com/parthatalukdar/junto)：该工具包由各种基于图的半监督学习(SSL)算法的实现组成，包含高斯随机场、吸附和修正吸附。
* [Clust4j](https://github.com/tgsmith61591/clust4j)：一组基于Java的分类聚类算法。
* [ZetaSketch](https://github.com/google/zetasketch)：用于单通道、分布式、近似聚合和草图绘制算法的库集合，由Google开源。
* [Strman](https://github.com/shekhargulati/strman-java)：Java 8字符串操作库。
* [Dijkstras Algorithm](https://github.com/mburst/dijkstras-algorithm)：Dijkstra最短路径算法的不同语言实现。
* [Java-String-Similarity](https://github.com/rrice/java-string-similarity)：一个实现了多种计算字符串之间相似度算法的Java库。
* [Jbsdiff](https://github.com/malensek/jbsdiff)：bsdiff算法的Java实现。
* [SZZ Unleashed](https://github.com/wogscpar/SZZUnleashed)：SZZ Unleashed是SZZ算法的实现，这是一种识别引入错误的提交的方法。
* [Hilbert Curve](https://github.com/davidmoten/hilbert-curve)：用于将沿N维希尔伯特曲线的距离转换为点并返回的Java实用程序。
* [Chronicle-Algorithms](https://github.com/OpenHFT/Chronicle-Algorithms)：用于哈希、BitSet操作、访问数据类型的原始字节、堆外锁定的零分配，高效算法。
* [Sketches-Java](https://github.com/DataDog/sketches-java)：分布式分位数草图算法DDSketch的Java实现。
* [FastFilter](https://github.com/FastFilter/fastfilter_java)：Java中的快速近似成员资格过滤器。
* [LensKit](https://github.com/lenskit/lenskit)：LensKit是协作过滤算法的实现以及一组用于对其进行基准测试的工具。
* [Compression](https://github.com/lichess-org/compression)：lichess.org的国际象棋时钟和着法压缩算法。
* [Timeseries-Forecast](https://github.com/Workday/timeseries-forecast)：这是一个Java开源库，提供时序预测功能。
* [Graphulo](https://github.com/Accla/graphulo)：Graphulo是一个用于Apache Accumulo数据库的Java库，提供服务器端稀疏矩阵数学原语，支持更高级别的图形算法和分析，MIT开源。
* [Delaunay Triangulation](https://github.com/jdiemke/delaunay-triangulator)：增量2D Delaunay三角剖分算法的简单Java实现。
* [JavaReedSolomon](https://github.com/Backblaze/JavaReedSolomon)：这是一个简单而高效的Java Reed-Solomon实现。
* [Hnswlib](https://github.com/jelmerk/hnswlib)：用于执行近似最近邻搜索的分层可导航小世界图(HNSW)算法的Java实现。
* [Fuzzy-Matcher](https://github.com/intuit/fuzzy-matcher)：一个基于Java的库，用于对文档集合中的“相似”元素进行匹配和分组。
* [LattiCG](https://github.com/mjtb49/LattiCG)：反转Java的java.util.Random类的可能内部种子，并以各种Random调用的不等式系统的形式给出其输出信息。
* [LightGBM4j](https://github.com/metarank/lightgbm4j)：LightGBM4j是LightGBM项目的零依赖Java包装器。
* [TreeLayout](https://github.com/abego/treelayout)：TreeLayout可以为任意树创建树布局。

## 噪声库

* [Noise](https://github.com/SpongePowered/noise)：Java噪声生成库，基于Jason Bevins的libnoise C++库。
* [JNoise](https://github.com/Articdive/JNoise)：JNoise是一个简单易用的Java库，用于在Java中生成噪声(包括梯度噪声)。
* [FastNoise Lite](https://github.com/Auburn/FastNoiseLite)：FastNoise Lite是一个极其便携的开源噪声生成库，具有大量噪声算法可供选择。
* [OpenSimplex2](https://github.com/KdotJPG/OpenSimplex2)：OpenSimplex Noise的后继者，以及更新的OpenSimplex。

## 原生开发

* [JNI](https://docs.oracle.com/javase/8/docs/technotes/guides/jni/)：JNI是一个标准编程接口，用于编写Java本机方法并将Java虚拟机嵌入到本机应用程序中。
* [Project Panama](https://github.com/openjdk/panama-foreign)：Project Panama旨在提高Java编程语言和本机库之间的互操作性的更改。
* [JNA](https://github.com/java-native-access/jna)：JNA使Java程序可以轻松访问原生共享库，而无需编写Java代码之外的任何内容-不需要JNI或原生代码。
* [JavaCPP](https://github.com/bytedeco/javacpp)：JavaCPP提供了对Java内部原生C++的高效访问。
* [JNR-FFI](https://github.com/jnr/jnr-ffi)：JNR-FFI是一个Java库，用于加载本机库，无需手动编写JNI代码或使用SWIG等工具。
* [ReLinker](https://github.com/KeepSafe/ReLinker)：适用于Android的强大原生库加载器。
* [SoLoader](https://github.com/facebook/SoLoader)：SoLoader是Android的本机代码加载器，Facebook开源。
* [JNIWrapper](https://teamdev.com/jniwrapper/)：该库可以在没有JNI的情况下在Java中使用本机代码。
* [JniHelpers](https://github.com/spotify/JniHelpers)：JniHelpers是一个旨在方便使用C++编写JNI代码的库，Spotify开源。
* [Spring Native](https://github.com/spring-attic/spring-native)：Spring Native提供了使用GraalVM本机镜像编译器将Spring应用程序编译为本机可执行文件的beta支持。
* [JavaCPP-Presets](https://github.com/bytedeco/javacpp-presets)：JavaCPP Presets包含广泛使用的C/C++库的Java配置和接口类。
* [JNAerator](https://github.com/nativelibs4java/JNAerator)：JNAerator为C、C++和Objective-C库生成完整的本机绑定，针对BridJ、JNA或Node.js运行时。
* [Nalim](https://github.com/apangin/nalim)：Nalim是一个使用JVMCI(JVM编译器接口)将Java方法链接到本机函数的库。
* [Native-Utils](https://github.com/adamheinrich/native-utils)：一个简单的工具库，用于加载存储在JAR存档中的动态库。
* [Jextract](https://github.com/openjdk/jextract)：Jextract是一个从本机库头自动生成Java绑定的工具，Oracle开发。
* [BridJ](https://github.com/nativelibs4java/BridJ)：BridJ是一个Java/原生互操作性库，专注于速度和易用性。
* [HawtJNI](https://github.com/fusesource/hawtjni)：基于Eclipse SWT中使用的JNI生成器的JNI代码生成器。
* [FastFFI](https://github.com/alibaba/fastFFI)：适用于Java和C++的现代高效FFI，由阿里开源。
* [Native-Library-Loader](https://github.com/scijava/native-lib-loader)：用于从Java中提取和加载本机库的本机库加载器。
* [Jssembly](https://github.com/dvx/jssembly)：Jssembly是一个库，允许你通过JNI桥从Java执行本机汇编。
* [Facebook JNI](https://github.com/facebookincubator/fbjni)：Facebook JNI工具库旨在简化Java JNI的使用。
* [JFFI](https://github.com/jnr/jffi)：libffi的Java绑定。
* [GlueGen](https://github.com/sgothel/gluegen)：GlueGen是一个用于函数和数据结构声明的编译器，可在编译时离线生成Java和JNI C代码，并允许在Java应用程序中使用本机库。

## COM桥

* [ComfyJ](https://teamdev.com/comfyj/)：ComfyJ是一款双向Java-COM桥接工具，用于提供COM到Java和Java到COM的交互连接。
* [Jacob](https://github.com/freemansoft/jacob-project)：Jacob是一个Java库，允许Java应用程序与Microsoft Windows DLL或COM库进行通信。
* [Com4j](https://github.com/kohsuke/com4j)：类型安全的Java/COM绑定。
* [J-Integra](https://j-integra.intrinsyc.com/)：J-Integra是一个高性能中间件软件桥，可实现Java COM互操作性。
* [JacoZoom](https://jacozoom.software.informer.com/)：JacoZoom是一个Java类库，它允许你通过Java使用ActiveX控件和ActiveX服务器(COM/DCOM/自动化)。

## GPU编程

* [TornadoVM](https://github.com/beehive-lab/TornadoVM)：TornadoVM是OpenJDK和GraalVM的插件，允许程序员在异构硬件上自动运行Java程序，这是曼彻斯特大学高级处理器技术小组的研究项目。
* [JCuda](https://github.com/jcuda/jcuda)：CUDA的Java绑定。
* [Aparapi](https://github.com/Syncleus/aparapi)：Aparapi允许开发人员通过在运行时动态地将Java字节代码转换为OpenCL内核来编写能够直接在显卡GPU上执行的本机Java代码。
* [JOML](https://github.com/JOML-CI/JOML)：用于OpenGL渲染计算的Java数学库。
* [JOGL](https://github.com/sgothel/jogl)：OpenGL API的Java绑定。
* [PixelFlow](https://github.com/diwi/PixelFlow)：用于高性能GPU计算处理的Java库。
* [JavaCL](https://github.com/nativelibs4java/JavaCL)：Java的OpenCL绑定。
* [ArrayFire Java](https://github.com/arrayfire/arrayfire-java)：ArrayFire的Java包装器。
* [JOCL](https://github.com/gpu/JOCL)：OpenCL的Java绑定。
* [JOAL](https://github.com/sgothel/joal)：JOAL项目托管OpenAL API的Java绑定的参考实现，旨在为用Java编写的应用程序提供硬件支持的3D空间化音频。
* [grCUDA](https://github.com/NVIDIA/grcuda)：GraalVM的多语言CUDA集成，由英伟达开源。
* [CLIJ2](https://github.com/clij/clij2)：CLIJ2是一个适用于ImageJ/Fiji、Icy、Matlab和Java的GPU加速图像处理库，由萨塞克斯大学、荷兰癌症研究所、剑桥大学、牛津大学、悉尼大学等组织共同开发。
* [PanamaGL](https://gitlab.com/jzy3d/panama-gl)：PanamaGL旨在使用适用于JDK 22及更高版本的FFM API提供与OpenGL的多平台绑定。
* [Beehive LevelZero JNI](https://github.com/beehive-lab/levelzero-jni)：该项目是针对Intel LevelZero的Java本机接口(JNI)绑定，由曼彻斯特大学开源。

## 硬件操作

* [OpenPnP](https://github.com/openpnp/openpnp)：OpenPnP是一种开源SMT拾放系统，包括可立即运行的软件以及可以构建和修改的硬件设计。
* [JNativeHook](https://github.com/kwhat/jnativehook)：JNativeHook是一个为Java提供全局键盘和鼠标监听器的库。
* [OSHI](https://github.com/oshi/oshi)：OSHI是一个免费的基于JNA的Java操作系统和硬件信息库，提供跨平台实现来检索系统信息，例如操作系统版本、进程、内存和CPU使用情况、磁盘和分区、设备、传感器等。
* [JCgroup](https://github.com/haosdent/jcgroup)：JCgroup是JVM上的Cgroup包装器，你可以使用该库来限制线程的CPU份额、磁盘I/O速度、网络带宽等。
* [Repeat](https://github.com/repeats/Repeat)：跨平台鼠标/键盘记录/重播和自动化热键/宏创建，以及更高级的自动化功能。
* [System-Hook](https://github.com/kristian/system-hook)：Java System Hook为Java提供了一个非常轻量级的全局键盘和鼠标监听器。
* [Chisel](https://github.com/chipsalliance/chisel)：Chisel是一种开源硬件描述语言(HDL)，用于在寄存器传输级别描述数字电子设备和电路，从而促进ASIC和FPGA数字逻辑的高级电路生成和设计重用设计，由伯克利大学开源。
* [NaturalMouseMotion](https://github.com/JoonasVali/NaturalMouseMotion)：该库提供了一种将光标可靠地移动到屏幕上指定坐标的方法，同时随机形成弧线，看起来就像真手使用鼠标将其移动到那里。
* [USB4Java](https://github.com/usb4java/usb4java)：该库可用于在Java中访问USB设备。
* [Webcam Capture](https://github.com/sarxos/webcam-capture)：该库允许你直接从Java使用内置或外部网络摄像头，它旨在抽象常用的相机功能并支持各种捕获框架。
* [JavaSysMon](https://github.com/jezhumble/javasysmon)：JavaSysMon旨在提供一种独立于操作系统的方式来管理操作系统进程并获取实时系统性能信息(例如CPU和内存使用情况)，并作为单个jar文件分发。
* [PixelController](https://github.com/neophob/PixelController)：该应用程序的主要目标是创建一个易于使用的矩阵控制器软件。
* [R2Cloud](https://github.com/dernasherbrezon/r2cloud)：R2Cloud可以跟踪和解码来自卫星的各种无线电信号。
* [S-Tools](https://github.com/naman14/S-Tools)：跟踪CPU和传感器以及拾色器、指南针和设备信息等有用功能。
* [Stream-Pi Client](https://github.com/stream-pi/client)：免费、开源、模块化、跨平台和可编程宏垫。
* [JIntellitype](https://github.com/melloware/jintellitype)：JIntellitype是一个Java API，用于与Microsoft Intellitype命令交互以及在Java应用程序中注册全局热键。
* [Zebra-zpl](https://github.com/w3blogfr/zebra-zpl)：用于生成通用ZPL命令以使用Java在Zebra打印机上打印标签的库。
* [Java HID-API](https://github.com/nyholku/purejavahidapi)：HID-API是一个跨平台API，用于从Java访问USB HID设备。
* [Cups4j](https://github.com/harwey/cups4j)：CUPS的Java打印库。
* [JavaDoesUSB](https://github.com/manuelbl/JavaDoesUSB)：Java does USB是一个用于处理USB设备的Java库，它允许查询有关所有连接的USB设备的信息，并使用自定义/供应商特定协议与USB设备进行通信。
* [EDSDK4J](https://github.com/kritzikratzi/edsdk4j)：这是Canon EOS数字软件开发套件EDSDK的Java包装器，可让你在Windows上完全访问Canon SLR相机。
* [ModbusPal](https://github.com/zeelos/ModbusPal)：ModbusPal是MODBUS从站模拟器，其目的是提供一个易于使用的界面，能够重现复杂且真实的MODBUS环境。
* [ProviewR](http://www.proview.se/v3/)：ProviewR可能是世界上第一个用于过程控制和自动化的开源系统。
* [KWSwitch](https://gitee.com/kerwincui/kwswitch)：智能开关平台，包含服务端、硬件端、安卓端和前端。
* [Mixly](https://gitee.com/mixlyplus/Mixly)：Mixly是一款面向初学者、硬件编程爱好者的图形化编程工具。
* [Attach](https://github.com/gluonhq/attach)：Gluon Attach是一个解决端到端Java Mobile解决方案中与低级平台API集成的组件。
* [Hid4Java](https://github.com/gary-rowe/hid4java)：libusb/hidapi库的跨平台JNA包装器，在Windows/Mac/Linux上开箱即用。
* [Java Grinder](https://github.com/mikeakohn/java_grinder)：将Java字节码编译为微控制器程序集。
* [JKeyMaster](https://github.com/tulskiy/jkeymaster)：用于使用JNA在Java中注册全局热键的库，目标是支持基于X11的平台、Windows和MacOSX。
* [XBee Java](https://github.com/digidotcom/xbee-java)：这是一个用Java开发的易于使用的API，允许你与Digi International的XBee射频(RF)模块进行交互。
* [ZSmartSystems](https://github.com/zsmartsystems/com.zsmartsystems.zigbee)：该项目旨在提供一个用Java编写并与Android兼容的ZigBee兼容框架。
* [VisiCut](https://github.com/t-oster/VisiCut)：VisiCut是一个用户友好、独立于平台的工具，用于准备、保存作业并将其发送到激光切割机。

## 运动规划

* [OWL](https://github.com/idsc-frazzoli/owl)：Java中的运动规划库，由苏黎世联邦理工学院开源。
* [RVO2-Java](https://github.com/snape/RVO2-Java)：最佳相互避免碰撞(ORCA)算法的Java实现，由北卡罗来纳大学开源。

## 自动规划

* [PDDL4J](https://github.com/pellierd/pddl4j)：PDDL4J的目的是促进基于PDDL语言(规划域描述语言)的自动化规划Java工具的开发，格勒诺布尔计算机科学实验室开源。
* [Neptus](https://github.com/LSTS/neptus)：Neptus是用于操作所有类型无人驾驶车辆的分布式指挥和控制基础设施，由波尔图大学开源。

## 操作系统

* [JOS](https://sourceforge.net/projects/jos/)：一个免费且开源的基于Java的操作系统。
* [JNode](https://github.com/jnode/jnode)：JNode是一个开源项目以创建一个Java平台的操作系统。
* [JX](https://github.com/mczero80/jx)：JX是一个Java操作系统，专注于灵活和健壮的操作系统架构。
* [JavaOS](https://zh.wikipedia.org/zh-cn/JavaOS)：JavaOS是一套操作系统，以JVM与一些基础软件组件所构成，由SUN公司开发。

## 逆向工程

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra)：Ghidra是一个由美国国家安全局研究局创建和维护的软件逆向工程框架。
* [Apktool](https://github.com/iBotPeaches/Apktool)：Apktool是一款用于对第三方、封闭式、二进制Android应用程序进行逆向工程的工具。
* [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer)：Bytecode Viewer是一个轻量级用户友好的Java/Android字节码查看器、反编译器等。
* [BinAbsInspector](https://github.com/KeenSecurityLab/BinAbsInspector)：BinAbsInspector是一款用于自动化逆向工程和扫描二进制文件漏洞的静态分析器，是腾讯科恩实验室孵化的长期研究项目。
* [JByteMod](https://github.com/GraxCode/JByteMod-Beta)：JByteMod是一个多功能字节码编辑器，具有语法突出显示、实时反编译和方法绘图功能。
* [BinDiff](https://github.com/google/bindiff)：BinDiff是一款开源的二进制文件比较工具，可以帮助漏洞研究人员和工程师快速找到反汇编代码中的差异和相似之处，由Google开源。
* [Super JADX](https://github.com/pkilller/super-jadx)：添加逆向工程的新功能，例如：类、字段、方法、变量、引用图等的重命名。
* [BinNavi](https://github.com/google/binnavi)：BinNavi是一个二进制分析IDE，允许检查、导航、编辑和注释控制流图以及反汇编代码的调用图，由Google开源。
* [Helios](https://github.com/helios-decompiler/standalone-app)：Helios是一款一体化Java逆向工程工具，它具有与最新反编译器集成的功能。
* [Kaiju](https://github.com/cmu-sei/kaiju)：Kaiju是Ghidra软件逆向工程套件的二进制分析框架扩展，由卡内基梅隆大学开源。
* [SkidSuite](https://github.com/GenericException/SkidSuite)：SkidSuite 3是与Java应用程序逆向工程相关的有用工具的集合。

## 电力系统

* [PowSyBl](https://github.com/powsybl/powsybl-core)：PowSyBl是一个用Java编写的开源框架，可以轻松编写用于电力系统仿真和分析的复杂软件。
* [SIMONA](https://github.com/ie3-institute/simona)：SIMONA提供了一个仿真工具箱，用于运行和实施大规模基于代理的电网仿真，重点关注配电网，由多特蒙德工业大学开源。
* [j60870](https://github.com/gythialy/j60870)：j60870是一个实现IEC 60870-5-104通信标准的库。
* [OperatorFabric](https://github.com/opfab/operatorfabric-core)：OperatorFabric是一个模块化、可扩展、工业强度的平台，用于电力、水和其他公用事业运营。
* [JoularJX](https://github.com/joular/joularjx)：JoularJX是一个基于Java的源代码级别电源监控代理，支持现代Java版本和多操作系统，以监控硬件和软件的功耗，由波城大学开源。

## 量子计算

* [Strange](https://github.com/redfx-quantum/strange)：该项目定义了一个可用于创建量子程序的Java API。
* [iQuantum](https://github.com/Cloudslab/iQuantum)：iQuantum是用于量子计算环境建模和仿真的工具包，由墨尔本大学开源。
* [JQuantLib](https://github.com/frgomes/jquantlib)：JQuantLib是一个免费、开源、全面的量化金融框架，100%用Java编写。

## QA系统

* [TDuck](https://gitee.com/TDuckApp/tduck-platform)：TDuck是国内首批基于Vue开源的问卷/表单收集工具。
* [QuestionAnsweringSystem](https://github.com/ysc/QuestionAnsweringSystem)：QuestionAnsweringSystem是一个Java实现的人机问答系统，能够自动分析问题并给出候选答案，这是IBM Watson的Java开源实现。
* [Qanary](https://github.com/WDAqua/Qanary)：Qanary是一种创建问答系统的方法。
* [YodaQA](https://github.com/brmson/yodaqa)：YodaQA是一个开源Factoid问答系统，可以使用即时信息提取从数据库和文本语料库中生成答案。
* [OpenQA](https://bitbucket.org/emarx/openqa/src/master/)：OpenQA是一个用于问答开发和发布的框架和平台。
* [Openauth](https://gitee.com/yubaolee/openauth.qa)：Openauth是一个简洁实用的问答网站。

## CMS系统

* [Halo](https://github.com/halo-dev/halo)：强大易用的开源建站工具。
* [Novel](https://github.com/201206030/novel)：一套基于时下最新Java技术栈Spring Boot 3 + Vue 3开发的前后端分离学习型小说项目。
* [MCMS](https://gitee.com/mingSoft/MCMS)：免费可商用的开源Java CMS内容管理系统。
* [JPress](https://gitee.com/JPressProjects/jpress)：一个完整的Java CMS网站管理系统。
* [师说CMS](https://gitee.com/shishuo/CMS_old)：一款使用Java语言开发的CMS，使用了Spring MVC、Spring、MyBatis等流行框架，提供首页大图管理、目录管理、文章管理和管理员管理等功能。
* [VBlog](https://github.com/lenve/VBlog)：Vue + Spring Boot实现的多用户博客管理平台。
* [JFinal-CMS](https://gitee.com/jflyfox/jfinal_cms)：Java开发的功能强大的信息咨询网站，采用了简洁强大的JFinal作为Web框架。
* [FastCMS](https://gitee.com/dianbuapp_admin/fastcms)：基于Spring Boot前后端分离技术，且具有插件化架构的CMS系统。
* [蘑菇博客](https://github.com/moxi624/mogu_blog_v2)：一个基于微服务架构的前后端分离博客系统。
* [DotCMS](https://github.com/dotCMS/core)：适用于企业的无头/混合内容管理系统。
* [Novel-Plus](https://github.com/201206030/novel-plus)：一个多端(PC、WAP)阅读，功能完善的原创文学CMS系统。
* [White-Jotter](https://github.com/Antabot/White-Jotter)：Spring Boot和Vue.js开发的一个简单的CMS。
* [PublicCMS](https://github.com/sanluan/PublicCMS)：PublicCMS是2023年采用主流技术开发的开源Java CCMS系统。
* [Scoold](https://github.com/Erudika/scoold)：面向团队的问答和知识共享平台。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、wiki、讨论等。由Spring Boot提供支持的云原生应用程序。
* [Apache Roller](https://github.com/apache/roller)：基于Java的全功能、多用户和群组博客服务器，适用于大大小小的博客网站。
* [XWiki Platform](https://github.com/xwiki/xwiki-platform)：一个通用的wiki平台，为构建在其之上的应用程序提供运行时服务。
* [Tianti](https://github.com/xujeff/tianti)：一款使用Java编写的免费的轻量级CMS系统，目前提供了从后台管理到前端展现的整体解决方案。
* [巡云轻论坛系统](https://github.com/diyhi/bbs)：包含论坛、问答模块，采用Java+MySQL架构。
* [Lin-CMS](https://github.com/TaleLin/lin-cms-spring-boot)：基于Spring Boot的CMS/DMS/管理系统开发框架。
* [JPress](https://github.com/JPressProjects/jpress)：一个使用Java开发、类似WordPress的产品，支持多站点、多语种自动切换等。
* [Ametys](https://www.ametys.org/community/en/index.html)：Ametys是一个用Java编写的免费开源内容管理系统。
* [网市场CMS](https://gitee.com/mail_osc/wangmarket)：私有化部署自己的SAAS云建站系统，跟可通过后台任意开通多个网站，每个网站使用自己的账号进行独立管理。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、wiki、讨论等，由Spring Boot提供支持的云原生应用程序。
* [FlyCms](https://github.com/sunkaifei/FlyCms)：类似知乎以问答为基础的完全开源的Java语言开发的社交网络建站程序。
* [Gentics-Mesh](https://github.com/gentics/mesh)：为开发人员提供的开源无头CMS。
* [JBake](https://github.com/jbake-org/jbake)：面向开发人员和设计人员的基于Java的开源静态站点/博客生成器。
* [Orchid](https://github.com/orchidhq/Orchid)：Orchid是一个用于生成具有所有功能的项目文档网站的框架。
* [Tale Blog](https://github.com/otale/tale)：Tale使用轻量级的MVC框架Blade进行开发，默认主题使用pinghsu。
* [ThinkItCMS](https://gitee.com/slfj/ThinkItCMS)：ThinkItCMS是一款面向模板开发，支持静态生成的CMS系统。
* [Nuxeo Platform](https://github.com/nuxeo/nuxeo)：构建现代商业应用的内容管理平台。
* [IceCMS](https://github.com/Thecosy/IceCMS)：基于Spring Boot + Vue前后端分离的内容管理系统。
* [Apache JSPWiki](https://github.com/apache/jspwiki)：领先的开源Wiki引擎，功能丰富且围绕标准JEE组件(Java、Servlet、JSP)构建。
* [Apache Jackrabbit Oak](https://github.com/apache/jackrabbit-oak)：Jackrabbit Oak是一个可扩展、高性能的分层内容仓库，旨在用作现代世界级网站和其他要求高的内容应用程序的基础。
* [菠萝博客](https://github.com/adlered/bolo-solo)：专为程序员设计的精致Java博客系统。
* [Brix](https://github.com/brix-cms/brix-cms)：基于Wicket和JCR，是当今最好的基于Wicket的CMS框架。
* [ForestBlog](https://github.com/saysky/ForestBlog)：一个简单漂亮的SSM博客系统。
* [Apache Stanbol](https://stanbol.apache.org/)：Apache Stanbol提供了一组用于语义内容管理的可重用组件。
* [Solo](https://github.com/88250/solo)：B3log分布式社区的Java博客端节点系统。
* [Jease](https://jease.org/)：Jease是一个由Java驱动的开源CMS。
* [Quanta](https://github.com/Clay-Ferguson/quantizr)：Quanta是一种新型内容管理平台，具有强大的功能。
* [WallRide](https://github.com/tagbangers/wallride)：WallRide是一个多语言、易于定制的开源CMS。
* [My Blog](https://github.com/ZHENFENG13/My-Blog)：由SpringBoot + Mybatis + Thymeleaf等技术实现的Java博客系统。
* [Magnolia CMS](https://www.magnolia-cms.com/)：Magnolia是一个开源CMS，由总部位于瑞士巴塞尔的Magnolia International Ltd开发。
* [瀑布CMS](https://gitee.com/LinZhaoguan/pb-cms)：采用Spring Boot + Apache Shiro + Mybatis Plus + Thymeleaf实现的CMS(附带权限管理)。
* [Znai](https://github.com/testingisdocumenting/znai)：使用Znai可构建实用、可维护、美观的用户指南。
* [OpooPress](https://github.com/opoo/opoopress)：OpooPress框架是一个完全灵活、完全可扩展的基于Java的静态站点生成器。
* [Jspxcms](https://gitee.com/jspxcms/Jspxcms)：Jspxcms是灵活的、易扩展的开源网站CMS，支持多组织、多站点、独立管理的网站群。
* [UJCMS](https://gitee.com/ujcms/ujcms)：Java开源内容管理系统，使用Spring Boot、MyBatis、Spring Security、Lucene、FreeMarker、TypeScript、Vue3、ElementPlus等技术开发。
* [TMS](https://gitee.com/xiweicheng/tms)：TMS是基于频道模式的团队沟通协作+轻量级任务看板，支持Markdown、富文本、在线表格和思维导图的团队博文wiki，i18n国际化翻译管理的响应式Web开源团队协作系统。
* [OpenCms](https://github.com/alkacon/opencms-core)：Alkacon Software的Java开源内容管理系统。
* [Dreamer-CMS](https://gitee.com/iteachyou/dreamer_cms)：Dreamer-CMS采用流行的Spring Boot搭建，支持静态化、标签化建站。
* [Blossom](https://github.com/blossom-editor/blossom)：Blossom是一个支持私有部署的云端双链笔记软件，你可以将你的笔记，图片，个人计划安排保存在自己的服务器中，并在任意设备之间实时同步。
* [OneBlog](https://gitee.com/yadong.zhang/DBlog)：一个简洁美观、功能强大并且自适应的Java博客。
* [Symphony](https://gitee.com/dl88250/symphony)：一款用Java实现的现代化社区(论坛/问答/BBS/社交网络/博客)系统平台。
* [MBlog](https://gitee.com/mtons/mblog)：开源免费的博客系统，支持MySQL/H2数据库，采用Spring Boot、JPA、Shiro、Bootstrap等流行框架开发。
* [NemakiWare](https://github.com/aegif/NemakiWare)：NemakiWare是一个开源企业内容管理系统。
* [Grain](https://github.com/sysgears/grain)：Grain是一个轻量级框架和一个非常强大的静态网站生成器，用Groovy编写，可帮助使网站创建直观且愉快。
* [WebSight](https://www.websight.io/)：WebSight是一个容器化内容管理系统，与StreamX数字体验服务网格进行原生集成。
* [Lutece](https://github.com/lutece-platform/lutece-core)：Lutece是一个开放平台，使城市政府能够共享、重复使用和改编其他城市创建的数字服务。
* [Antville](https://github.com/antville/antville)：Antville是一个开源项目，提供高性能、功能丰富的博客托管软件。

## ERP系统

* [华夏ERP](https://gitee.com/jishenghua/JSH_ERP)：基于Spring Boot框架和SaaS模式开源的ERP软件，目前专注进销存、财务、生产功能。
* [赤龙ERP](https://gitee.com/redragon/redragon-erp)：一款免费开源、业务闭环、灵活稳定的企业级ERP系统。
* [Metasfresh](https://github.com/metasfresh/metasfresh)：一个响应迅速、免费且开源的ERP系统。
* [REBUILD](https://gitee.com/getrebuild/rebuild)：REBUILD通过创新的业务流程引擎帮助你快速搭建各类企业管理系统，全图形化配置无需了解技术。
* [OMS](https://github.com/FJ-OMS/oms-erp)：一站式全渠道业务中台系统，包括订单管理系统OMS/电商ERP、库存WMS统一管理系统和SAP财务管理系统等。
* [ADempiere](https://github.com/adempiere/adempiere)：ADempiere Business Suite ERP/CRM/MFG/SCM/POS以开放且不减的方式实现了Bazaar方式。
* [Apache OFBiz](https://github.com/apache/ofbiz-framework)：用于企业流程自动化的开源产品，它包括ERP、CRM、电子商务/电子商务、供应链管理和制造资源规划的框架组件和业务应用程序。
* [iDempiere](https://github.com/idempiere/idempiere)：完全开源商务套件ERP/CRM/MFG/SCM/POS。
* [ERP-Pro](https://gitee.com/doc_wei01/erp-pro)：基于Spring Boot框架，为中小企业打造的开源好用ERP软件。
* [MyCompany](https://github.com/lsfusion-solutions/mycompany)：适用于小型企业的ERP系统。
* [悟空CRM](https://github.com/WuKongOpenSource/WukongCRM-11.0-JAVA)：基于Spring Cloud Alibaba微服务架构 + Vue ElementUI的前后端分离CRM系统。
* [iBizEHR](https://gitee.com/ibizlab/iBizEHR)：iBizEHR是一套可满足万人应用的高性能人力资源管理软件，埃毕致开源。
* [Saas ERP](https://gitee.com/hy417393356/saas-java)：基于Spring Boot 2.2.0、Mybatis、JWT、Redis、Vue + Element-UI的前后端分离的Saas平台后台管理系统。
* [星云ERP](https://gitee.com/lframework/xingyun)：基于Spring Boot框架，为中小企业提供完全开源、永久免费、用户体验好的进销存ERP系统。
* [Qcadoo MES](https://github.com/qcadoo/mes)：Qcadoo MES是一款针对中小企业的生产管理互联网应用，它结合了大型ERP系统的功能，适应中小企业的具体特点。
* [Wimoor ERP](https://github.com/wimoor-erp/wimoor)：Wimoor ERP是国内首款百分百开源、支持商用的亚马逊ERP系统。
* [CalLite CRM](https://www.callite.it/)：CalLite是市场上功能最丰富、速度最快的呼叫中心软件，它可以让你消除用户时间的浪费(操作员、代理、主管、协调员等)，从而实现收益最大化。
* [Compiere](https://www.aptean.com/en-US/solutions/erp/products/aptean-compiere-erp)：Compiere是一款开源ERP和CRM业务解决方案，适用于分销、零售、服务和制造领域的中小型企业。
* [Libertya](https://github.com/Disytel-Consulting-SA/libertya)：Libertya是一款综合管理管理软件，无需许可费用且完全免费使用，专为在任何类型的公司中快速实施和启动而设计。
* [BlueSeer ERP](https://github.com/BlueSeerERP/blueseer)：BlueSeer ERP是一个免费的开源多语言ERP软件包。

## DMS系统

* [Teedy](https://github.com/sismics/docs)：Teedy是一个面向个人和企业的开源、轻量级文档管理系统。
* [OpenKM Community Edition](https://github.com/openkm/document-management-system)：OpenKM文档管理系统允许企业控制电子文档的制作、存储、管理和分发，从而提高效率以及重用信息和控制文档流的能力。
* [LogicalDOC Community Edition](https://github.com/logicaldoc/community)：LogicalDOC社区版是一款开源文档管理软件。
* [FormKiQ](https://github.com/formkiq/formkiq-core)：灵活的文档管理系统。
* [ECMS](https://github.com/exoplatform/ecms)：eXo的组合ECM(文档)和CMS管理系统。
* [瀚为云文档协作平台](https://github.com/honvay/hdms-community)：瀚为云文档协作平台是一款面向企业的文档协作平台，着力于满足企业文档管理中统一管理、安全存储、共享协作、权限控制等需求。
* [CrafterCMS](https://github.com/craftercms/craftercms)：CrafterCMS是一个现代内容管理平台，用于构建数字体验应用程序。

## SCRM系统

* [LinkWeChat](https://gitee.com/LinkWeChat/link-wechat)：LinkWeChat是基于企业微信的开源SCRM系统，是企业私域流量管理与营销的综合解决方案。
* [源雀SCRM](https://gitee.com/iyque/iYqueCode)：源雀SCRM是完全开源的私域数智化营销解决方案。
* [MarketGo](https://github.com/marketgo-scrm/MarketGo-SCRM)：MarketGo是一个营销引擎，通过提供的标准化功能和基础能力，让开发者能快速搭建适合自己企业的营销系统。
* [EasyLink](https://github.com/lianluoyi/easyink_System)：EasyLink是基于企业微信生态的一站式私域流量运营平台。
* [Pumplabs SCRM](https://github.com/Pumplabs/scrm)：Pumplabs SCRM是一款开源、基于企业微信、简洁便捷、高效协作的CRM应用，主要面向一定售周期的业务，如家装、汽车服务、保险、IT、美容、教培等。
* [MoChat](https://gitee.com/mochat/mochat-java)：MoChat是基于企业微信的开源应用开发框架&引擎，也是一套通用的企业私域流量管理系统。

## 门户框架

* [Apache Protals](http://portals.apache.org/)：Apache Portals项目提供各种软件产品，包括Jetspeed-2、Pluto和Portals Applications。
* [Liferay Portal](https://github.com/liferay/liferay-portal)：Liferay是一个现成的，即开即用的，功能完备的门户网站。
* [Apereo uPortal](https://github.com/uPortal-Project/uPortal)：uPortal是由高等教育界构建并为其服务的领先开源企业门户框架。

## 教育软件

* [TEAMMATES](https://github.com/TEAMMATES/teammates)：TEAMMATES是一个免费的在线工具，用于管理学生的同行评估和其他反馈路径，由新加坡国立大学开源。
* [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)：BigBlueButton是一个开源虚拟教室，旨在帮助教师教学和学习者学习。
* [Sakai](https://github.com/sakaiproject/sakai)：Sakai是一个免费提供的、功能丰富的技术解决方案，用于学习、教学、研究和协作，由美国印第安纳大学、密西根大学、斯坦福大学和麻省理工学院于2004年发起。
* [OpenOLAT](https://github.com/OpenOLAT/OpenOLAT)：OpenOlat是一个基于Web的电子学习平台，用于教学、学习、评估和交流，是一个LMS、一个学习管理系统。
* [SkillTree](https://github.com/NationalSecurityAgency/skills-service)：SkillTree是一个微型学习游戏化平台，提供开箱即用的UI可视化、方便的客户端集成库以及用于管理游戏化培训档案创建和管理的仪表板，由美国国家安全局开源。

## 网络库

* [T-IO](https://gitee.com/tywo45/t-io)：T-IO是基于Java开发的一款高性能网络编程框架。
* [SOFABolt](https://github.com/sofastack/sofa-bolt)：SOFABolt是蚂蚁金融开发的一套基于Netty实现的网络通信框架。
* [Network-Connection](https://github.com/facebookarchive/network-connection-class)：Network Connection是一个Android库，可让你了解当前用户的互联网连接质量，由Facebook开源。
* [ONOS](https://github.com/opennetworkinglab/onos)：ONOS是唯一支持从传统“棕地”网络向SDN“绿地”网络过渡的SDN控制器平台，由Linux基金会开源。
* [SNF4J](https://github.com/snf4j/snf4j)：SNF4J是一个异步事件驱动的网络应用程序框架，用于快速轻松地开发网络应用程序。
* [Smart Socket](https://gitee.com/smartboot/smart-socket)：Smart-Socket是一款极简、易用、高性能的AIO通信框架。
* [One-NIO](https://github.com/odnoklassniki/one-nio)：One-NIO是一个用于构建高性能Java服务器的库，它具有操作系统功能和JDK内部API，对于使高负载应用程序充分利用底层系统至关重要。
* [Apache Commons Net](https://github.com/apache/commons-net)：Apache Commons Net库包含网络实用程序和协议实现的集合，支持的协议包括：Echo、Finger、FTP、NNTP、NTP、POP3(S)、SMTP(S)、Telnet、Whois。
* [Envoy Mobile](https://github.com/envoyproxy/envoy-mobile)：基于适用于iOS、Android等的Envoy项目的客户端HTTP和网络库。
* [Ip2region](https://github.com/lionsoul2014/ip2region)：Ip2region是一个离线IP地址定位库和IP定位数据管理框架，提供了众多主流编程语言的xdb数据生成和查询客户端实现。
* [AdbLib](https://github.com/cgutman/AdbLib)：ADB网络协议的Java库实现。
* [Jpcap](https://github.com/jpcap/jpcap)：Jpcap是一组Java类，提供用于网络数据包捕获的接口和系统。
* [Chronicle Network](https://github.com/OpenHFT/Chronicle-Network)：Chronicle Network是一个高性能网络(TCP/IP)库。
* [KryoNet](https://github.com/EsotericSoftware/kryonet)：KryoNet是一个Java库，它提供了一个干净、简单的API，用于使用NIO进行高效的TCP和UDP客户端/服务器网络通信。
* [COMSAT](https://github.com/puniverse/comsat)：将标准Java Web相关API与Quasar纤程和Actor集成。
* [Infinileap](https://github.com/hhu-bsinfo/infinileap)：适用于Java 19+的基于ucx的现代网络框架，由杜塞尔多夫海因里希海涅大学计算机科学系操作系统小组开发。
* [TLS Channel](https://github.com/marianobarrios/tls-channel)：TLS Channel是一个通过TLS连接实现ByteChannel接口的库。
* [Voovan](https://gitee.com/helyho/Voovan)：Voovan是高性能异步通信、HTTP服务器和客户端通信、动态编译支持、数据库操作帮助类等工具的框架。
* [IPAddress](https://github.com/seancfoley/IPAddress)：用于处理IP地址和子网(IPv4和IPv6)的Java库。
* [Commons IP Math](https://github.com/jgonian/commons-ip-math)：该库提供了丰富、类型安全的API，用于处理对IP资源执行的最常见操作，例如解析、以多种表示法打印、检查范围是否重叠或可以合并等。
* [Java IPv6](https://github.com/janvanbesien/java-ipv6)：用于IPv6相关概念的Java库，例如IPv6地址、网络掩码、地址池等。
* [JUnixSocket](https://github.com/kohlschutter/junixsocket)：JUnixSocket是一个Java/JNI库，允许使用Java中的Unix域套接字(AF_UNIX套接字)和其他地址/协议系列(例如AF_TIPC、AF_VSOCK和AF_SYSTEM)。
* [Pcap4J](https://github.com/kaitoy/pcap4j)：Pcap4J是一个用于捕获、制作和发送数据包的Java库。
* [K3PO](https://github.com/k3po/k3po)：能够创建任意网络流量和行为，并验证网络端点在遭受该行为时是否行为正确。
* [XNIO](https://github.com/xnio/xnio)：XNIO是一个简化的低级I/O层，可以在当今使用NIO的任何地方使用，这是JBoss社区项目。
* [JXIO](https://github.com/accelio/JXIO)：JXIO是基于AccelIO(C库)的Java API。
* [SNMP4J](https://www.snmp4j.org/)：SNMP4J是一个用Java来实现SNMP(简单网络管理协议)协议的开源项目，它支持以命令行的形式进行管理与响应。
* [Commons-Networking](https://github.com/CiscoSE/commons-networking)：公共网络实用程序库，由Cisco开源。
* [URNLib](https://github.com/slub/urnlib)：用于表示、解析和编码RFC 2141和RFC 8141中指定的URN的Java库，由德累斯顿工业大学开源。
* [OpenSky API](https://github.com/openskynetwork/opensky-api)：OpenSky网络REST API的Python和Java绑定。
* [SimpleNet](https://github.com/jhg023/SimpleNet)：SimpleNet是一个用Java编写的简单的客户端/服务器框架。
* [DiSNI](https://github.com/zrlio/disni)：DiSNI是一个Java库，用于从用户空间直接存储和网络访问，它提供了一个RDMA接口来访问远程内存。
* [Fluency](https://github.com/komamitsu/fluency)：Fluentd和Fluent Bit的高吞吐量数据摄取记录器。
* [Jcabi-URN](https://github.com/jcabi/jcabi-urn)：根据RFC 2141的URN的不可变实现。
* [Barchart-UDT](https://github.com/barchart/barchart-udt)：原生C++ UDT协议的Java包装。
* [WeUPnP](https://github.com/bitletorg/weupnp)：用Java编写的小型UPnP客户端库。
* [Dragonite](https://github.com/dragonite-network/dragonite-java)：Dragonite是一种基于UDP的可靠应用级数据传输协议，针对有损和不稳定的网络进行了高度优化。
* [OkSocket](https://github.com/xuuhaoo/OkSocket)：Android应用程序的阻塞套接字客户端。
* [ZugServ](https://github.com/JohnChernoff/ZugServ)：简单的Java网络库。
* [OpenVirteX](https://github.com/os-libera/OpenVirteX)：OVX是一个网络管理程序，可以在单个物理基础设施之上创建多个虚拟和可编程网络。
* [Java-KCP](https://gitee.com/344453111/java-Kcp)：基于Netty实现的可靠UDP网络库(kcp算法)，包含fec实现，可用于游戏，视频，加速等业务。
* [Angry IP Scanner](https://github.com/angryip/ipscan)：Angry IP Scanner是适用于Windows、Linux和Mac的快速且友好的网络扫描器。
* [UPnP PortMapper](https://github.com/kaklakariada/portmapper)：UPnP PortMapper是一个易于使用的程序，用于管理本地网络中启用UPnP的互联网网关设备(路由器)的端口映射(端口转发)。
* [jNetMap](https://rakudave.ch/jnetmap/)：jNetMap是一个图形网络监控和文档工具，它会每x分钟ping所有注册的设备，并根据ping的结果更新状态。
* [Untangle](https://sourceforge.net/projects/untangle/)：Untangle是一款基于Linux的网络网关，具有可插拔模块，适用于垃圾邮件拦截、网页过滤、防病毒、反间谍软件、入侵防御、带宽控制、强制门户、VPN、防火墙等网络应用程序。
* [Discourse Network Analyzer](https://github.com/leifeld/dna)：Discourse Network Analyzer是一种具有网络导出功能的定性内容分析工具。
* [Socket.D](https://gitee.com/noear/socket.d)：基于事件和语义消息流的网络应用协议。
* [Drift](https://github.com/airlift/drift)：Drift是一个易于使用、基于注解的Java库，用于创建Thrift客户端和可序列化类型。
* [Batfish](https://github.com/batfish/batfish)：Batfish是一种网络验证工具，通过分析网络设备的配置，为安全性、可靠性和合规性提供正确性保证。
* [PraxisCORE](https://github.com/praxis-live/praxiscore)：PraxisCORE是一个模块化JVM运行时，用于网络物理编程，支持实时系统的实时编码。

## 状态机

* [Squirrel](https://github.com/hekailiang/squirrel)：Squirrel为Java提供了一个易于使用、类型安全且高度可扩展的状态机实现。
* [Spring Statemachine](https://github.com/spring-projects/spring-statemachine)：Spring Statemachine项目提供了一个通用的基础设施来在Spring应用程序中使用状态机概念。
* [Stateless4j](https://github.com/stateless4j/stateless4j)：轻量级Java状态机。
* [EasyFlow](https://github.com/Beh01der/EasyFlow)：EasyFlow是一个简单且轻量级的Java有限状态机。
* [Easy States](https://github.com/j-easy/easy-states)：Easy States是Java中事件驱动的确定性有限自动机实现。
* [StatefulJ](https://github.com/statefulj/statefulj)：StatefulJ是一个轻量级、开源的Java事件驱动有限状态机(FSM)和一个完整的基于Spring Data的框架，可让你轻松定义状态机并将其集成到你的应用程序中。
* [nFlow](https://github.com/NitorCreations/nflow)：nFlow是一种经过验证的用于编排业务流程的解决方案。
* [State-Machine](https://github.com/davidmoten/state-machine)：Java的有限状态机类生成器。
* [Makina](https://github.com/clnhlzmn/makina)：Makina是一个分层状态机源到源转换器，它将状态机描述作为输入并生成这些状态机的C语言实现。
* [JState](https://github.com/UnquietCode/JState)：Java中的高级状态机。
* [State Machine Compiler](https://smc.sourceforge.net/)：SMC最大限度地利用了状态模式，允许你的对象处理意外事件、恢复并继续提供服务(而不是崩溃)的转换。
* [Morfologik Stemming](https://github.com/morfologik/morfologik-stemming)：用于有限状态自动机构建和基于字典的形态词典的工具。
* [TSM4j](https://github.com/weilueluo/tsm4j)：Java的类型化状态机。
* [Dk.Brics.Automaton](https://github.com/cs-au-dk/dk.brics.automaton)：Java的有限状态自动机和正则表达式，由奥胡斯大学开源。

## 二维码生成器

* [ZXing](https://github.com/zxing/zxing)：适用于Java、Android的ZXing条码扫描库。
* [QR-Code-Generator](https://github.com/nayuki/QR-Code-generator)：Java、TypeScript/JavaScript、Python、Rust、C++、C语言的高质量QR码生成器库。
* [ZXingLite](https://github.com/jenly1314/ZXingLite)：ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。
* [QArt4J](https://github.com/dieforfree/qart4j)：一个QR码生成器，可提供ASCII Art输出图像。
* [Barbecue](https://barbecue.sourceforge.net/)：一个开源Java库，支持广泛的一维条形码格式。
* [Barcode4J](https://barcode4j.sourceforge.net/)：提供二维条形码格式(例如DataMatrix和PDF417)以及更多输出格式。
* [QRGen](https://github.com/kenglxn/QRGen)：一个基于ZXING构建的简单的Java二维码生成API。
* [Java-OCR-API](https://github.com/Asprise/java-ocr-api)：Java OCR允许你对图像(JPEG、PNG、TIFF、PDF等)执行OCR和条形码识别，并输出为纯文本、具有完整坐标的XML以及可搜索的PDF。
* [ZXingGenerator](https://github.com/vivian8725118/ZXingGenerator)：花式二维码生成库，提供了6种样式。
* [React-QR-Code](https://github.com/rosskhanas/react-qr-code)：用于React和React Native的QR代码生成器。
* [Visual-QR-Code](https://gitee.com/boat824109722/visual-qr-code)：可以创建出设置了虚拟背景图片的二维码。
* [QRext4j](https://gitee.com/BYSRepo/qrext4j)：一个简单易用的二维码生成工具，可自定义二维码颜色和码眼样式。
* [FiwanQRCode](https://gitee.com/frogchou/FiwanQRCode)：飞网开发的二维码生成工具。
* [QRCode Generator](https://github.com/kazuhikoarase/qrcode-generator)：以JavaScript、Java等语言实现的QR码生成器。
* [QRGenerator](https://github.com/androidmads/QRGenerator)：二维码生成器库。
* [QRCode-Utils](https://github.com/binarywang/qrcode-utils)：二维码生成工具。
* [Okapi Barcode](https://github.com/woo-j/OkapiBarcode)：Okapi Barcode是一款完全用Java编写的开源条形码生成器，支持50多种编码标准，包括所有ISO标准。
* [EMV QRCode](https://github.com/mvallim/emv-qrcode)：基于Java的EMV二维码生成器和解析器(MPM、CPM)。
* [Barcode Java](https://github.com/barnhill/barcode-java)：该库旨在为开发人员提供一个简单的类，供开发人员在需要从一串数据生成条形码图像时使用。

## 文件系统

* [HDFS](https://github.com/apache/hadoop)：Apache Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Jimfs](https://github.com/google/jimfs)：Jimfs是Java 8及更高版本的内存文件系统，实现了java.nio.file抽象文件系统API，由Google开源。
* [XtreemFS](https://github.com/xtreemfs/xtreemfs)：XtreemFS是一个用于联合IT基础设施的分布式、可复制和容错的文件系统，由柏林自由大学开源。
* [Memory File System](https://github.com/marschall/memoryfilesystem)：用于测试目的的JSR-203文件系统的内存实现。
* [RubiX](https://github.com/qubole/rubix)：RubiX是一个可供大数据引擎使用的轻量级数据缓存框架。
* [ADFS](https://github.com/taobao/ADFS)：ADFS是Hadoop的演进版本，提供高可用性、自动重启等特性，由阿里开源。
* [TngouFS](https://gitee.com/397713572/tngouFS)：TngouFS是天狗网用于该网站的图片存储。
* [Apache Commons VFS](https://github.com/apache/commons-vfs)：Apache Commons VFS是一个虚拟文件系统库。
* [FastDFS Client](https://github.com/happyfish100/fastdfs-client-java)：FastDFS Java客户端SDK。
* [FastDFS Client](https://github.com/tobato/FastDFS_Client)：FastDFS的Java客户端。
* [JNR FUSE](https://github.com/SerCeMan/jnr-fuse)：JNR FUSE是使用Java Native Runtime的Java中的FUSE实现。
* [NFS4J](https://github.com/dCache/nfs4j)：NFS服务器版本3、4.0和4.1的纯Java实现，包括带有nfs4.1-files和flex-files布局类型的pNFS扩展。
* [JavaFS](https://github.com/puniverse/javafs)：Java文件系统，由FUSE提供支持。
* [ParallelGit](https://github.com/freelunchcap/ParallelGit)：适用于Git的高性能Java 7 NIO内存文件系统。
* [Amazon S3 FileSystem NIO2](https://github.com/Upplication/Amazon-S3-FileSystem-NIO2)：适用于Java 7(NIO2)的Amazon AWS S3文件系统提供程序。
* [Google NIO Filesystem](https://github.com/googleapis/java-storage-nio)：用于Google Cloud Storage的NIO文件系统提供程序的Java客户端。
* [FUSE-Java](https://github.com/EtiennePerot/fuse-jna)：使用JNA的Java FUSE绑定
* [JSR-203 Hadoop](https://github.com/damiencarol/jsr203-hadoop)：Hadoop分布式文件系统的JSR 203实现。
* [S3FS NIO](https://github.com/carlspring/s3fs-nio)：这是使用Java 8的JSR-203的Amazon AWS S3文件系统提供程序的实现。
* [Hadoop-COS](https://github.com/tencentyun/hadoop-cos)：Hadoop-COS实现了以腾讯云COS作为底层文件系统运行上层计算任务的功能，支持使用Hadoop、Spark以及Tez等处理存储在腾讯云COS对象存储系统上的数据。
* [Hadoop-20](https://github.com/facebookarchive/hadoop-20)：Facebook基于Hadoop 0.20-append的实时分布式FS。
* [SDFS](https://github.com/opendedup/sdfs)：一种去重文件系统，可以将数据存储在对象存储或块存储中。

## 报表引擎

* [JimuReport](https://github.com/jeecgboot/JimuReport)：一款免费的数据可视化报表，含报表和大屏设计，功能涵盖数据报表、打印设计、图表报表、大屏设计等。
* [UReport2](https://github.com/youseries/ureport)：UReport2是一个基于Spring架构的高性能纯Java报表引擎，可以通过迭代单元格来准备复杂的中式报表和报表。
* [EasyReport](https://github.com/xianrendzw/EasyReport)：EasyReport是一个简单易用的Web报表工具，它的主要功能是把SQL语句查询出的行列结构转换成HTML表格，并支持表格的跨行与跨列。
* [BI Platform](https://github.com/baidu/BIPlatform)：百度开源，业内领先的Holap敏捷BI分析平台，提供高性能、准实时、可扩展的、一站式的BI建模、分析平台。
* [JasperReports](https://github.com/TIBCOSoftware/jasperreports)：JasperReports库是世界上最流行的开源报告引擎，由TIBCO软件公司开源。
* [Eclipse BIRT](https://github.com/eclipse-birt/birt)：BIRT是商业智能报告工具，可以从许多不同的数据源(数据库、文件、Java、Javascript、Web服务等)提取和组合数据，并将这些数据用于报告和图表，由安讯公司开源。
* [YARG](https://github.com/cuba-platform/yarg)：YARG是一个Java开源报告库，由Haulmont开发。
* [Pentaho](https://github.com/pentaho/pentaho-reporting)：Pentaho是用于生成报告的Java类库，它使用来自多个来源的数据提供灵活的报告和打印功能，并支持输出到显示设备、打印机、PDF、Excel、XHTML、纯文本、XML和CSV文件。
* [DynamicJasper](https://github.com/intive-FDV/DynamicJasper)：DynamicJasper是一个隐藏JasperReports复杂性的API，它可以帮助开发人员在设计简单/中等复杂性报表时节省时间，自动生成报表元素的布局。
* [ExtentReports](https://github.com/extent-framework/extentreports-java)：使用ExtentReports库，可以为你的测试创建美观、交互式且详细的报告。
* [FineReport](https://www.finereport.com/en/)：一款商业的BI报告和仪表板软件。
* [Logi Report](https://devnet.logianalytics.com/hc/en-us/categories/1500001227442-Logi-Report)：Logi Report被设计为作为独立服务器执行，但可以将其集成到现有WAR项目中。
* [Report Mill](http://www.reportmill.com/product/)：ReportMill可以平滑地嵌入到每个Java应用程序中，此外，与BIRT一样它非常灵活：可以在运行时自定义报告。
* [iReport](https://community.jaspersoft.com/project/ireport-designer)：一个开源报表设计器，对于JasperReports库和JasperReports服务器免费。
* [OpenReports](https://sourceforge.net/projects/oreports/)：基于Web的报告解决方案，允许用户通过浏览器动态查看XLS、HTML或PDF格式创建的报告。
* [AJ-Report](https://gitee.com/anji-plus/report)：AJ-Report是一个完全开源，拖拽编辑的可视化设计工具。
* [R3-Query](https://gitee.com/aagagagag/R3-Query)：R3 Query整合了企业报表领域各个周期的支持，其中包括报表设计、报表发布、报表生成、报表管理、订阅发布和报表监控等报表的整个生命周期的步骤。
* [Pentaho Platform](https://github.com/pentaho/pentaho-platform)：该项目构成了Pentaho的核心平台和业务分析服务器。
* [UReport-kepp](https://gitee.com/summer-T/ureport-keep)：UReport的替代项目。
* [Skyeye Report](https://gitee.com/doc_wei01/skyeye-report)：Skyeye Report是一款高性能的Java报表引擎，提供完善的基于网页的报表设计器，可快速做出各种复杂的中式报表。
* [Dynamic Reports](https://github.com/dynamicreports/dynamicreports)：DynamicReports是一个基于JasperReports的开源Java报表库，它允许创建动态报表设计，并且不需要可视化报表设计器。

## 物流系统

* [RinSim](https://github.com/rinde/RinSim)：RinSim是一个用Java编写的物流模拟器，支持动态取货和送货问题的(去)中心化算法，由比利时鲁汶大学计算机科学系部门的imec-DistriNet小组开发。
* [OpenWMS](https://github.com/openwms/org.openwms)：OpenWMS是一个免费使用且可扩展的仓库管理系统(WMS)，带有适用于自动和手动仓库的物料流控制(MFC)系统。
* [Deer WMS](https://gitee.com/deerwms/deer-wms-2)：Deer WMS是基于自动化输送线、机械臂、点数机、提升机、堆垛机等自动化设备和现代化仓储精益管理思想开发出来的仓库管理系统，由南京大鹿智造开发。
* [myWMS](https://github.com/wms2/mywms)：myWMS LOS是开源仓库管理系统WMS，它在工业24/7环境中运行并支持所有基本流程。
* [OpenBoxes](https://github.com/openboxes/openboxes)：OpenBoxes是一个开源供应链管理系统，用于管理医疗机构和救灾工作的物资和药物。

## 打包部署运行

* [OneinStack](https://github.com/oneinstack/oneinstack)：OneinStack是一个PHP/Java部署工具。
* [Capsule](https://github.com/puniverse/capsule)：Capsule是JVM应用程序的打包和部署工具。
* [ShinyProxy](https://github.com/openanalytics/shinyproxy)：用于Shiny和数据科学应用程序的开源企业部署。
* [Rultor](https://github.com/yegor256/rultor)：Rultor是一个DevOps团队助理，它通过易于使用的直观聊天机器人界面帮助你自动执行日常操作(合并、部署和发布)。
* [jDeploy](https://github.com/shannah/jdeploy)：jDeploy Github Action允许你在Github工作流中为Java项目生成本机桌面安装程序。
* [JReleaser](https://github.com/jreleaser/jreleaser)：JReleaser是一个用于Java和非Java项目的自动化发布工具。
* [Stork](https://github.com/fizzed/stork)：Stork是一个轻量级实用程序的集合，用于通过填补Java构建系统和执行之间的空白来优化“构建后”工作流程。
* [WinRun4j](https://github.com/poidasmith/winrun4j)：WinRun4j是适用于Windows的Java启动器。
* [Linux Deploy](https://github.com/meefik/linuxdeploy)：可在Android设备上快速轻松地安装操作系统GNU/Linux。
* [Artipie](https://github.com/artipie/artipie)：Artipie是一个二进制工件管理工具，类似于Artifactory、Nexus、Archiva、ProGet等。
* [CloudCaptain](https://cloudcaptain.sh/)：使用不可变基础设施的原则将JVM应用程序部署到AWS。
* [Getdown](https://github.com/threerings/getdown)：Getdown是一个用于将Java应用程序部署到最终用户计算机并保持这些应用程序最新的系统。
* [JavaPackager](https://github.com/fvarrui/JavaPackager)：JavaPackager是Maven和Gradle的混合插件，它提供了一种在本机Windows、MacOS或GNU/Linux可执行文件中打包Java应用程序并为其生成安装程序的简单方法。
* [JPackage](https://github.com/Akman/jpackage-maven-plugin)：JPackage插件允许你使用Java 14中引入的jpackage工具创建自定义运行时镜像/安装程序。
* [JVMKill](https://github.com/airlift/jvmkill)：JVMKill是一个简单的JVMTI代理，当JVM无法分配内存或创建线程时，它会强制终止JVM。
* [Drip](https://github.com/ninjudd/drip)：Drip是Java虚拟机的启动器，它提供比java命令更快的启动时间。
* [Teletraan](https://github.com/pinterest/teletraan)：Teletraan是Pinterest的部署系统。
* [Kayenta](https://github.com/spinnaker/kayenta)：Kayenta是一个自动金丝雀分析(ACA)平台。
* [Spring Boot Thin Launcher](https://github.com/spring-projects-experimental/spring-boot-thin-launcher)：用于Java应用程序的瘦JAR启动器。
* [JApp](https://github.com/Glavo/japp)：Java程序的新打包格式。
* [JLink.Online](https://github.com/AdoptOpenJDK/jlink.online)：JLink.Online是一个HTTP微服务，可动态构建优化/最小化的Java运行时。
* [Badass](https://github.com/beryx/badass-runtime-plugin)：创建非模块化应用程序的自定义运行时镜像。
* [Layrry](https://github.com/moditect/layrry)：Layrry是一个启动器和Java API，用于执行模块化Java应用程序。
* [Nailgun](https://github.com/facebookarchive/nailgun)：Nailgun是一个客户端、协议和服务器，用于从命令行运行Java程序，而不会产生JVM启动开销，由Facebook开源。
* [SlimFast](https://github.com/HubSpot/SlimFast)：SlimFast是Java应用程序的一个工具，可帮助它们停止构建用于部署的fat jar，由HubSpot开源。
* [Jar Jar Links](https://github.com/google/jarjar)：Jar Jar Links是一个实用程序，可以轻松地重新打包Java库并将它们嵌入到你自己的发行版中。
* [ExeBuilder](https://gitee.com/qsyan/ExeBuilder)：ExeBuilder是一款利用JDK模块化的特性帮你把jar打包成独立exe的工具，它支持GUI和控制台应用程序的创建。
* [IzPack](https://github.com/izpack/izpack)：IzPack是一种广泛使用的工具，用于将Java平台上的应用程序打包为跨平台安装程序。
* [Packr](https://github.com/libgdx/packr)：用于打包JAR、资源和JVM，以便在Windows、Linux和Mac OS X上分发。
* [Update4j](https://github.com/update4j/update4j)：Update4j是第一个专为Java 9+设计的自动更新和启动器库。
* [Install4j](https://www.ej-technologies.com/products/install4j/overview.html)：Install4j是一个功能强大的多平台Java安装程序生成器，可生成Java应用程序的本机安装程序和应用程序启动器。
* [JWrapper](https://www.jwrapper.com/)：JWrapper是一款高端现代Java安装程序，可用于部署Java应用程序。
* [InstallAnywhere](https://www.revenera.com/install/products/installanywhere)：InstallAnywhere使开发人员可以轻松创建具有相同功能的专业安装软件-无论平台是什么。

## 地理空间

* [GeoTools](https://github.com/geotools/geotools)：GeoTools是一个开源Java库，它提供符合标准的方法来操作地理空间数据，例如实现地理信息系统(GIS)，由英国利兹大学开源。
* [Open Location Code](https://github.com/google/open-location-code)：Open Location Code是一种将位置编码为比纬度和经度更易于使用的形式的技术，由Google开源。
* [Gisgraphy](https://github.com/gisgraphy/gisgraphy)：Gisgraphy提供正向和反向地理编码、地理定位和车辆跟踪Web服务。
* [MeteoInfo](https://github.com/meteoinfo/MeteoInfo)：MeteoInfo是GIS应用(MeteoInfoMap)、科学计算和可视化环境(MeteoInfoLab)的集成框架，特别适合气象界，由中国气象科学研究院开源。
* [Apache SIS](https://github.com/apache/sis)：Apache SIS是一个用于开发地理空间应用程序的Java语言库。
* [Geo Assist](https://github.com/thegeekyasian/geo-assist)：Geo Assist是一个开源Java库，旨在简化空间数据的处理过程。
* [Proj4J](https://github.com/locationtech/proj4j)：Proj4J是一个用于在不同地理空间坐标参考系之间转换坐标的Java库，这是一个Eclipse基金会项目。
* [GeoMesa](https://github.com/locationtech/geomesa)：GeoMesa是一套开源工具，可在分布式计算系统上进行大规模地理空间查询和分析。
* [Barefoot](https://github.com/bmwcarit/barefoot)：Barefoot是一个宝马开源的Java库，用于与OpenStreetMap进行在线和离线地图匹配。
* [Deegree](https://github.com/deegree/deegree3)：Deegree是用于空间数据基础设施和地理空间网络的开源软件，Deegree包含地理空间数据管理组件，包括数据访问、可视化、发现和安全性，由德国波恩大学地理系开发。
* [Mapsforge](https://github.com/mapsforge/mapsforge)：Mapsforge是一个Android、Java平台可用的地图库，支持OpenStreetMap地图数据的离线呈现。
* [SeaRoute](https://github.com/eurostat/searoute)：SeaRoute可以计算两个地点之间的最短海上路线，由欧盟统计局开源。
* [GAMA](https://github.com/gama-platform/gama.old)：GAMA是一个易于使用的开源建模和仿真环境，用于创建基于代理的空间显式仿真。
* [MrGeo](https://github.com/ngageoint/mrgeo)：MrGeo是一个地理空间工具包，旨在提供可大规模执行的基于栅格的地理空间功能，由美国国家地理空间情报局与DigitalGlobe合作开发。
* [Tinfour](https://github.com/gwlucastrig/Tinfour)：Tinfour是一个用Java编写的软件库，提供了用于构建和应用符合Delaunay准则的不规则三角网络(TIN)的工具。
* [NoiseModelling](https://github.com/Universite-Gustave-Eiffel/NoiseModelling)：NoiseModelling是一个能够生成噪声图的库，由古斯塔夫埃菲尔大学开源。
* [Spatial4j](https://github.com/locationtech/spatial4j)：Spatial4j是一个通用空间/地理空间开源Java库，其核心功能有三重：提供常见的地理空间感知形状，提供距离计算和其他数学运算，以及读取形状并将其写入字符串。
* [geOrchestra](https://github.com/georchestra/georchestra)：geOrchestra是一个完整的空间数据基础设施解决方案。
* [OrbisGIS](https://github.com/orbisgis/orbisgis)：OrbisGIS是一个跨平台开源地理信息系统(GIS)，由法国Lab-STICC实验室内的CNRS领导。
* [GeoServer](https://github.com/geoserver/geoserver)：GeoServer是一个用Java编写的开源软件服务器，允许用户共享和编辑地理空间数据。
* [Geohash Java](https://github.com/kungfoo/geohash-java)：Geohashes的纯Java实现。
* [GeoIP2 Java](https://github.com/maxmind/GeoIP2-java)：用于GeoIP2 Web服务客户端和数据库读取器的Java API。
* [GeoFire Java](https://github.com/firebase/geofire-java)：GeoFire是一个Java开源库，允许你根据地理位置存储和查询一组密钥，由Google开源。
* [GeoWave](https://github.com/locationtech/geowave)：GeoWave在Accumulo、HBase、BigTable、Cassandra、Kudu、Redis、RocksDB和DynamoDB之上提供地理空间和时间索引。
* [Geo Platform](https://github.com/geosdi/geo-platform)：Geo-Plaform是一个开发富Web GIS应用程序的框架，由意大利国家研究委员会开源。
* [Geotoolkit](https://github.com/Geomatys/geotoolkit)：Geotoolkit是一个开源库，提供了操作制图数据的工具。
* [Photon](https://github.com/komoot/photon)：Photon是一个为OpenStreetMap数据构建的开源地理编码器。
* [Geo](https://github.com/davidmoten/geo)：用于地理哈希的Java实用方法。
* [SEPAL](https://github.com/openforis/sepal)：SEPAL是一个用于地理数据处理的云计算平台。
* [GeoPackage Java](https://github.com/ngageoint/geopackage-java)：GeoPackage是开放地理空间联盟GeoPackage规范的Java实现，由美国国家地理空间情报局开源。
* [GeoGig](https://github.com/locationtech/geogig)：GeoGig是一个地理空间分布式版本控制系统。
* [GeoWebCache](https://github.com/GeoWebCache/geowebcache)：GeoWebCache是一个用Java实现的图块缓存服务器，提供各种图块缓存服务，如WMS-C、TMS、WMTS、谷歌Maps、MS Bing等。
* [CLAVIN](https://github.com/Novetta/CLAVIN)：CLAVIN是一个开源软件包，用于文档地理解析和地理分辨率，采用基于上下文的地理实体分辨率。
* [GeoNetwork](https://github.com/geonetwork/core-geonetwork)：GeoNetwork是一个用于管理空间参考资源的目录应用程序，它提供强大的元数据编辑和搜索功能以及交互式Web地图查看器，由OSGeo开源。
* [DHIS 2](https://github.com/dhis2/dhis2-core)：DHIS 2是一个灵活、基于Web的开源信息系统，具有出色的可视化功能，包括GIS、图表和数据透视表，由奥斯陆大学HISP中心开发。
* [地图瓦片图下载器](https://gitee.com/CrimsonHu/java_map_download)：使用Java开发的地图瓦片图下载工具，支持OpenStreetMap、天地图、谷歌地图、高德地图、腾讯地图、必应地图的XYZ瓦片图下载与合并。
* [GAF](https://gitee.com/supermapgaf/GAF)：SuperMap GAF基于SuperMap GIS基础软件进行研发，是连接GIS基础软件与行业应用的重要纽带。
* [JPX](https://github.com/jenetics/jpx)：JPX是一个Java库，用于创建、读取和写入GPX格式的GPS数据。
* [GeoDesk](https://github.com/clarisma/geodesk)：GeoDesk是一个用于OpenStreetMap数据的快速且存储高效的地理空间数据库。
* [Timeshape](https://github.com/RomanIakovlev/timeshape)：Timeshape是一个Java库，可用于确定给定地理坐标属于哪个时区。
* [Traccar](https://github.com/traccar/traccar)：Traccar是一个开源GPS跟踪系统，支持200多种GPS协议和2000多种GPS跟踪设备型号。
* [Apache Sedona](https://github.com/apache/sedona)：Apache Sedona是一种空间计算引擎，使开发人员能够在Apache Spark和Apache Flink等现代集群计算系统中轻松处理任何规模的空间数据，由亚利桑那州立大学开源。
* [H3-Java](https://github.com/uber/h3-java)：该库为H3核心库提供Java绑定，由Uber开源。
* [Planetiler](https://github.com/onthegomap/planetiler)：Planetiler是一种从OpenStreetMap等地理数据源生成矢量切片的工具。
* [ElasticGeo](https://github.com/ngageoint/elasticgeo)：ElasticGeo提供了一个GeoTools数据存储，允许使用GeoServer通过OGC服务发布Elasticsearch索引中的地理空间特征，由美国国家地理空间情报局开源。
* [Unfolding](https://github.com/tillnagel/unfolding)：Unfolding是一个用Processing和Java创建交互式地图和地理可视化的库。
* [H2GIS](https://github.com/orbisgis/h2gis)：H2数据库的空间扩展，由法国Lab-STICC实验室内CNRS的GIS和信息科学领域的科学家和工程师领导。
* [Jgeohash](https://github.com/astrapi69/jgeohash)：一个易于实现的库，可以帮助Java开发人员使用GeoHash算法来创建基于自定义纬度和经度值的地理编码。
* [Geodesy](https://github.com/mgavaghan/geodesy)：这是实现Thaddeus Vincenty算法的Java源代码，用于解决正向和逆向大地测量问题。
* [OSHDB](https://github.com/GIScience/oshdb)：OpenStreetMap全历史数据的高性能时空数据分析平台，由海德堡大学开源。
* [Proj4J](https://github.com/Proj4J/proj4j)：Proj4J是一个Java库，用于将点坐标从一个地理坐标系转换到另一个地理坐标系，包括基准面转换。
* [OpenJUMP](https://github.com/openjump-gis/openjump)：OpenJUMP诞生于JUMP，JUMP是一个开源GIS，最初由Vividsolutions用Java开发，并由不列颠哥伦比亚省(加拿大)自然资源部资助。
* [Nunaliit](https://github.com/GCRC/nunaliit)：Nunaliit是一个用于创建交互式、数据驱动的网络地图集的系统，支持用户编辑文档和几何图形、集成多媒体、文档关系、灵活的数据模式、自我复制、动态推送更新到浏览器以获取新对象，以及基于平板电脑的在线/离线编辑和同步；由卡尔顿大学地理信息学和制图研究中心(GCRC)的一个团队开发。
* [Apache Baremaps](https://github.com/apache/incubator-baremaps)：Apache Baremaps是一个工具包和一组用于创建、发布和操作在线地图的基础设施组件。
* [Wilayah Indonesia](https://github.com/yusufsyaifudin/wilayah-indonesia)：印度尼西亚行政地图。
* [SimpleLatLng](https://github.com/JavadocMD/simplelatlng)：SimpleLatLng提供了一个简单、轻量级的库，可满足Java中常见的纬度和经度计算需求。
* [CityGML4j](https://github.com/citygml4j/citygml4j)：CityGML4j是OGC CityGML的开源Java库和API。
* [GeoAPI](https://github.com/opengeospatial/geoapi)：GeoAPI为地理空间应用程序提供了一组Java和Python语言编程接口。
* [THREDDS Data Server](https://github.com/Unidata/tds)：TDS提供对科学数据集的元数据和数据访问，由美国国家科学基金会开源。
* [Xponents](https://github.com/OpenSextant/Xponents)：Xponents是一组信息提取库，包括提取和规范化地理实体、日期/时间模式、关键字/分类法和各种模式。
* [JGiscoTools](https://github.com/eurostat/JGiscoTools)：JGiscoTools是一个用于操作地理空间和统计数据的Java库，重点关注Eurostat和Eurostat-GISCO生成的欧洲数据，由欧盟统计局开源。
* [Time Zone Map](https://github.com/dustin-johnson/timezonemap)：用于将位置或地区映射到时区的Java/Kotlin库。
* [OpenMap](https://github.com/OpenMap-java/openmap)：OpenMap是一个基于Java Beans的工具包，用于构建需要地理信息的应用程序和Applet，由雷神公司开源。
* [MapLibre Tiles](https://github.com/maplibre/maplibre-tile-spec)：下一代矢量切片格式。
* [Mago 3DTiler](https://github.com/Gaia3D/mago-3d-tiler)：Mago 3DTiler是一款OGC 3D Tiles工具，由Gaia3D开源。
* [Maxent](https://github.com/mrmaxent/Maxent)：Maxent是一个独立的Java应用程序，用于对物种地理分布进行建模，由美国自然历史博物馆开源。
* [CTS](https://github.com/orbisgis/cts)：CTS是一个为使用众所周知的大地测量算法和参数集执行坐标变换而开发的库，由法国Lab-STICC实验室开源。

## 路由引擎

* [GraphHopper](https://github.com/graphhopper/graphhopper)：OpenStreetMap的开源路由引擎，可以将其用作Java库或独立的Web服务器。
* [Openrouteservice](https://github.com/GIScience/openrouteservice)：具有大量功能的开源路线规划器API，由海德堡大学开源。
* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner)：OpenTripPlanner是一款开源多模式旅行规划器，专注于通过定期公共交通结合自行车、步行和移动服务(包括自行车共享和叫车)出行，由俄勒冈州波特兰市交通机构TriMet开源。
* [R5](https://github.com/conveyal/r5)：R5是Conveyal的路线引擎，Conveyal是一个基于Web的系统，允许用户创建交通场景并根据累积机会可达性指标对其进行评估。
* [Public Transport Enabler](https://github.com/schildbach/public-transport-enabler)：这是一个Java库，允许你从公共交通提供商获取数据。
* [OneBusAway](https://github.com/OneBusAway/onebusaway-application-modules)：OneBusAway应用程序套件的主要功能是通过各种界面与乘客共享实时公共交通信息。
* [MovSim](https://github.com/movsim/movsim)：MovSim是一款基于微观车道的交通模拟器，具有基于XML的配置和CSV文本输出。
* [MATSim](https://github.com/matsim-org/matsim-libs)：MATSim提供了一个工具箱来运行和实施大规模基于代理的运输模拟，由柏林工业大学开源。
* [EqaSim](https://github.com/eqasim-org/eqasim-java)：EqaSim包是用于基于代理和基于活动的传输模拟框架MATSim的准备运行的高质量场景的集合。
* [OpenTrafficSim](https://github.com/averbraeck/opentrafficsim)：OpenTrafficSim是一个多级交通模拟器，由代尔夫特理工大学开源。

## 几何学

* [Apache Commons Geometry](https://github.com/apache/commons-geometry)：Apache Commons Geometry项目提供几何类型和实用程序。
* [S2 Geometry Library](https://github.com/google/s2-geometry-library-java)：这是一个Google开源的用于操作几何形状的包，S2主要设计用于处理球面几何，即在球体上而不是在平面2D地图上绘制的形状。
* [Geolatte-geom](https://github.com/GeoLatte/geolatte-geom)：符合OGC SQL简单功能规范的几何模型。
* [JGEX](https://github.com/yezheng1981/Java-Geometry-Expert)：JGEX是一款结合了动态几何软件、自动几何定理证明器(GTP)和视觉动态证明呈现方法的软件，由威奇托州立大学开源。
* [JTS](https://github.com/locationtech/jts)：JTS Topology是一个用于创建和操作向量几何的Java库。
* [Geometry API](https://github.com/Esri/geometry-api-java)：Esri几何API可用于在第三方数据处理解决方案中启用空间数据处理。
* [JCSG](https://github.com/miho/JCSG)：基于BSP的CSG(构造实体几何)的Java实现。
* [Campskeleton](https://github.com/twak/campskeleton)：Java中的加权直骨架实现。
* [GeoRegression](https://github.com/lessthanoptimal/GeoRegression)：GeoRegression是一个基于Java的免费几何库，用于机器人和计算机视觉等领域的科学计算，重点关注2D/3D空间。

## 航空

* [SeNtinel Application Platform](https://github.com/senbox-org/snap-engine)：SNAP是欧洲航天局(ESA)为Sentinel-1、Sentinel-2和Sentinel-3任务的科学开发而开发的三个Sentinel工具箱的通用软件平台。
* [Sentinel-1 Toolbox](https://github.com/senbox-org/s1tbx)：Sentinel-1 Toolbox是由欧空局开发的一款界面友好的开源SAR图像处理软件，它能够处理1级以及更高级的SAR数据。
* [Sentinel-2 Toolbox](https://github.com/senbox-org/s2tbx)：ESA Sentinel-2卫星上的MSI仪器的工具箱。
* [Sentinel-3 Toolbox](https://github.com/senbox-org/s3tbx)：用于ESA Sentinel-3卫星上的OLCI和SLSTR仪器的工具箱。
* [NanoSat MO Framework](https://github.com/esa/nanosat-mo-framework)：NanoSat MO是基于CCSDS任务运营服务的纳米卫星软件框架，由格拉茨科技大学与欧洲航天局合作开发。
* [GUSTO](https://github.com/esa/GUSTO)：GUSTO包含赫歇尔空间天文台科学任务规划软件的组件，该软件用于天文观测的交互式调度，由欧洲航天局开源。
* [SBMT](https://sbmt.jhuapl.edu/)：SBMT是一种搜索、访问和分析小天体航天器数据的简单方法，由约翰霍普金斯大学应用物理实验室开发。
* [DERT](https://github.com/nasa/DERT)：DERT是一款开源软件工具，用于探索NASA的3D数字地形模型。
* [CCDD](https://github.com/nasa/CCDD)：CCDD是一款用于管理CFS和CFS应用程序的命令和遥测数据的软件工具。
* [WorldWind Java](https://github.com/NASAWorldWind/WorldWindJava)：美国国家航空航天局发布的一个开源的地理科普软件，由NASA Research开发。它是一个可视化地球仪，将NASA、USGS以及其它WMS服务商提供的图像通过一个三维的地球模型展现。
* [SNAP Desktop](https://github.com/senbox-org/snap-desktop)：SNAP是欧洲航天局(ESA)为光学和微波任务的科学开发而开发的三个工具箱的通用软件平台。
* [Orekit](https://github.com/CS-SI/Orekit)：Orekit是一个用Java编写的免费低级空间动力学库，它提供了基本元素(轨道、日期、姿态、框架...)以及处理它们的各种算法，由CS GROUP开发。
* [JMARS](https://jmars.mars.asu.edu/)：JMARS是由亚利桑那州立大学火星太空飞行设施开发的地理空间信息系统，旨在为NASA科学家、仪器团队成员、各个年龄段的学生和公众提供任务规划和数据分析工具。
* [EarthSci](https://github.com/GeoscienceAustralia/earthsci)：用于地球科学可视化的Eclipse RCP平台，基于NASA WorldWind Java SDK构建。
* [SolarPositioning](https://github.com/klausbrunner/solarpositioning)：SolarPositioning是一个用于查找地心太阳坐标的Java库。
* [Nom.Tam.Fits](https://github.com/nom-tam-fits/nom-tam-fits)：用于读写FITS文件的全功能100% Java库，最初起源于NASA，目前由哈佛大学维护。
* [Astro4j](https://github.com/melix/astro4j)：用于Java中天文图像处理的库和应用程序的集合。
* [AstroImageJ](https://github.com/AstroImageJ/astroimagej)：提供了一个天文特定的图像显示环境和工具，用于天文特定的图像校准和数据缩减。
* [Predict4Java](https://github.com/davidmoten/predict4java)：Predict4Java提供实时卫星跟踪和轨道预测信息。
* [Gaia Sky](https://codeberg.org/gaiasky/gaiasky)：适用于桌面和VR的开源3D宇宙模拟器，支持超过10亿个对象，由海德堡大学开源。
* [JSOFA](https://github.com/Javastro/jsofa)：JSOFA是国际天文学联合会的C SOFA软件库的纯Java版本。
* [AstroLib](https://mhuss.com/AstroLib/docs/Overview.html)：一个Java天文算法库。
* [JPARSEC](https://arxiv.org/abs/1806.03088)：经过十二年开发和使用的天文学Java包。
* [DSTE](https://ai-solutions.com/dste/)：DSTE是一个交互式软件包，具有创新可视化功能的多体轨迹设计技术，可显著减少轨迹设计所花费的时间，被约翰逊航天中心用作设计工具。
* [JHelioviewer](https://github.com/Helioviewer-Project/JHelioviewer-SWHV)：JHelioviewer是基于JPEG 2000图像压缩标准的太阳物理数据可视化工具，由ESA/NASA开源。
* [Commons-Suncalc](https://github.com/shred/commons-suncalc)：用于计算太阳和月亮位置和相位的Java库。
* [Debian Astro Java](https://blends.debian.org/astro/tasks/java)：用于天文学的Java包集合。
* [Starlink Java](https://github.com/Starlink/starjava)：星链项目是一个长期运行的英国项目，支持天文数据处理。它于2005年关闭，但该软件继续在联合天文中心开发，直到2015年3月，现在由东亚天文台维护。
* [Java Astrodynamics Toolkit](https://sourceforge.net/projects/jat/)：JAT是一个开源软件组件库，用于用Java或Matlab编写的航天应用程序，该软件由NASA使用，是德克萨斯大学计算机科学系的主要合作项目。
* [JSky](https://jsky.sourceforge.net/)：JSky项目的目标是构建一系列可重用的Java组件以用于天文学，最初源于ESO的Skycat应用程序的开发。
* [IDV](https://github.com/Unidata/IDV)：IDV是一个用于分析和显示地球科学数据的框架，由美国国家科学基金会Unidata开源。
* [Mars-SIM](https://github.com/mars-sim/mars-sim)：Mars-SIM被设计为一个通用模拟器，描绘火星上人类住区的早期发展。
* [Simple-Astronomy-Lib](https://github.com/SimpleAstronomy/simple-astronomy-lib)：一个简单的天文学库，用于计算月相、日食等。
* [Aerie](https://github.com/NASA-AMMOS/aerie)：Aerie是一个用于航天器建模的软件框架，NASA开源。
* [Geocalc](https://github.com/grumlimited/geocalc)：Geocalc是一个简单的Java库，旨在使用地球坐标进行算术运算。
* [Orbdetpy](https://github.com/ut-astria/orbdetpy)：Orbdetpy是一个Python轨道确定库，航天先进科学技术研究(ASTRIA)开源。
* [Yamcs](https://github.com/yamcs/yamcs)：Yamcs是一个用Java开发的任务控制框架。
* [CCSDS](https://github.com/dariol83/ccsds)：基于Java 11的CCSDS协议和格式的开源实现。

## 水文学

* [SOS](https://github.com/52North/SOS)：SOS提供了一个可互操作的基于Web的界面，用于插入和查询传感器数据和传感器描述。
* [OpenDCS](https://github.com/opendcs/opendcs)：水文/气象数据开放数据采集系统。
* [Vortex](https://github.com/HydrologicEngineeringCenter/Vortex)：Vortex是针对水文工程中心应用程序的数据处理实用程序的集合，例如HEC-HMS、HEC-RAS。

## 物理库

* [FreeHEP](https://java.freehep.org/)：FreeHEP库的目标是鼓励高能物理领域Java代码的共享和重用，由SLAC国家加速器实验室开源。

## 无人机

* [RosettaDrone](https://github.com/RosettaDrone/rosettadrone)：RosettaDrone是一个用于开发和测试DJI无人机软件的框架。
* [MAVGCL](https://github.com/ecmnet/MAVGCL)：这个基于JavaFX的工具使PX4用户能够根据PX4Logs或ULogs记录和分析飞行期间或离线时通过UDP发布的数据。
* [MAVLink](https://github.com/dronefleet/mavlink)：用于MAVLink通信的Java API。
* [OpenAMASE](https://github.com/afrl-rq/OpenAMASE)：OpenAMASE是用于模拟多无人机任务的项目，由空军研究实验室、航空航天系统局、动力和控制部门开发。
* [MAVLinkJava](https://github.com/ghelle/MAVLinkJava)：用于MAVLink的Java代码生成器和Java库。
* [MAVLink Kotlin](https://github.com/divyanshupundir/mavlink-kotlin)：适用于Kotlin多平台的现代MAVLink库。

## AIS库

* [AISmessages](https://github.com/tbsalling/aismessages)：AISmessages是一种基于Java的轻量级、零依赖、超高效消息解码器，用于符合ITU 1371(NMEA装甲AIS消息)的海上导航和安全消息。
* [AisLib](https://github.com/dma-ais/AisLib)：AisLib是一个用于处理AIS消息的Java库，由丹麦海事局开源。
* [Java Marine API](https://github.com/ktuukkan/marine-api)：Java Marine API是一个NMEA 0183解析器库，用于对各种电子海洋设备(例如GPS、回声测深仪和气象仪器)提供的数据进行解码和编码。
* [Risky](https://github.com/amsa-code/risky)：用于分析带有时间戳的位置数据的工具，例如来自AIS的船舶位置报告。

## 跨语言

* [Py4J](https://github.com/py4j/py4j)：Py4J使Python程序能够动态访问任意Java对象。
* [Jep](https://github.com/ninia/jep)：通过JNI将CPython嵌入到Java中。
* [RJava](https://github.com/s-u/rJava)：R/Java接口允许在R中使用Java以及将R嵌入到Java中(通过JRI)。
* [RCaller](https://github.com/jbytecode/rcaller)：RCaller是一个软件库，旨在简化从Java调用R的过程，由伊斯坦布尔大学数值方法教授开源。
* [LuaJava](https://github.com/jasonsantos/luajava)：LuaJava是一个Java脚本编写工具，该工具的目标是允许用Lua编写的脚本操作用Java开发的组件。
* [Rococoa](https://github.com/iterate-ch/rococoa)：Rococoa是绑定到Mac Objective-C对象系统的通用Java，它允许在Java中创建和使用Objective-C对象，以及在Java中实现Objective-C接口。
* [J4RS](https://github.com/astonbitecode/j4rs)：J4RS允许从Rust轻松调用Java代码，反之亦然。
* [SwiftJava](https://github.com/SwiftJava/SwiftJava)：SwiftJava是一个Swift代码生成器，以及一个支持用Swift 3.0的Xcode beta6版本编写的代码的小框架。
* [DWR](https://github.com/directwebremoting/dwr)：DWR是一个Java库，它使服务器上的Java和浏览器中的JavaScript能够尽可能简单地交互和调用。
* [JTcl](https://github.com/jtcl-project/jtcl)：JTcl是用Java编写的Tcl(工具命令语言)的实现。
* [JNI4NET](https://github.com/jni4net/jni4net)：JVM和CLR之间的快速、面向对象、进程内桥梁。
* [Trireme](https://github.com/apigee/trireme)：Trireme在JVM内运行Node.js脚本。
* [Javonet](https://www.javonet.com/)：Javonet是一个高级库，可以在任何编程语言和模块之间进行直接方法调用，从而无需集成层。

## 序列化

* [Hessian](http://hessian.caucho.com/)：Hessian是一种基于二进制的轻量级网络传输协议，用于在不同的应用程序之间进行远程过程调用，由Caucho开源。
* [FlatBuffers](https://github.com/google/flatbuffers)：FlatBuffers是一个跨平台序列化库，旨在实现最大内存效率，由Google开源。
* [Ysoserial](https://github.com/frohoff/ysoserial)：Ysoserial是一种概念验证工具，用于生成利用不安全的Java对象反序列化的有效负载。
* [Apache Avro](https://github.com/apache/avro)：Apache Avro是一个数据序列化系统。
* [Protostuff](https://github.com/protostuff/protostuff)：Protostuff是一个Java序列化库，内置对向前向后兼容性(模式演化)和验证的支持。
* [Apache Fury](https://github.com/apache/incubator-fury)：Apache Fury是一种速度极快的多语言序列化框架，由JIT和零拷贝提供支持，可提供高达170倍的性能和终极易用性，阿里开源。
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：完全兼容JDK序列化协议的Java序列化框架，在序列化速度上能达到JDK的10倍。
* [MessagePack](https://github.com/msgpack/msgpack-java)：Java的MessagePack序列化器实现。
* [Serial](https://github.com/twitter/Serial)：Serial是一种自定义序列化实现，旨在提高性能并增加开发人员对对象序列化的可见性和控制，由Twitter开源。
* [Swift](https://github.com/facebookarchive/swift)：Swift是一个易于使用、基于注解的Java库，用于创建Thrift可序列化类型和服务，由Facebook开源。
* [Ion Java](https://github.com/amazon-ion/ion-java)：Ion数据表示法的Java实现，由Amazon开源。
* [SOFA-Hessian](https://github.com/sofastack/sofa-hessian)：SOFA-Hessian基于原生Hessian v4.0.51进行改进，目前已在蚂蚁金服内部稳定运行多年。
* [Colfer](https://github.com/pascaldekloe/colfer)：Colfer是一种针对速度和大小进行优化的二进制序列化格式。
* [Chronicle Wire](https://github.com/OpenHFT/Chronicle-Wire)：支持多种格式的低垃圾Java序列化库。
* [Bond](https://github.com/microsoft/bond)：Bond是一个用于处理模式化数据的跨平台框架，支持跨语言反/序列化和强大的通用机制，可有效地操作数据，微软开源。
* [Kryo](https://github.com/EsotericSoftware/kryo)：Kryo是一个快速高效的Java二进制对象图序列化框架。
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

## IO操作

* [Apache Commons IO](https://github.com/apache/commons-io)：Apache Commons IO库包含实用程序类、流实现、文件过滤器、文件比较器、字节序转换类等等。
* [Okio](https://github.com/square/okio)：Okio是一个补充java.io和java.nio的库，使你可以更轻松地访问、存储和处理数据，由Square开源。
* [UberFire I/O](https://github.com/kiegroup/appformer/tree/main/uberfire-io)：NIO.2的实用程序/门面集。
* [JNR-UnixSocket](https://github.com/jnr/jnr-unixsocket)：Java的本机I/O访问。
* [Plexus IO](https://github.com/codehaus-plexus/plexus-io)：Plexus IO是一组Plexus组件，设计用于I/O操作。
* [Jaydio](https://github.com/smacke/jaydio)：Jaydio是一个Java库，可让程序员更好地控制文件I/O，部分方法是绕过操作系统缓冲区高速缓存。
* [JTar](https://github.com/kamranzafar/jtar)：JTar是一个简单的Java Tar库，它提供了一种使用IO流创建和读取tar文件的简单方法。
* [jMimeMagic](https://github.com/arimus/jmimemagic)：jMimeMagic是一个用于确定文件或流的MIME类型的Java库。
* [SimpleMagic](https://github.com/j256/simplemagic)：简单的文件幻数和内容类型库，提供文件和字节数组的MIME类型确定。
* [NIO_Uring](https://github.com/bbeaupain/nio_uring)：NIO_Uring是一个Java I/O库，它在底层使用io_uring。
* [MimeCraft](https://github.com/square/mimecraft)：用于创建符合RFC要求的Multipart和表单编码HTTP请求主体的实用程序。
* [Ballerina MIME](https://github.com/ballerina-platform/module-ballerina-mime)：该库提供了一组用于处理消息的API，这些API遵循RFC 2045标准中指定的多用途Internet邮件扩展规范。
* [Apache MIME4J](https://github.com/apache/james-mime4j)：Mime4j可用于解析纯rfc822和MIME格式的电子邮件消息流，并构建电子邮件消息的树表示形式。
* [MIME Type](https://github.com/overview/mime-types)：用于检测文件MIME类型的Java库。
* [Modbus](https://github.com/digitalpetri/modbus)：适用于Java的高性能、非阻塞、零缓冲区复制Modbus。
* [Chronicle Bytes](https://github.com/OpenHFT/Chronicle-Bytes)：Chronicle Bytes的用途与Java的NIO ByteBuffer类似，但具有一些附加功能。
* [Kdio](https://github.com/lexburner/kdio)：一个使用非常简单的Java Direct IO框架。
* [FastJavaIO](https://github.com/williamfiset/FastJavaIO)：非常快的Java输入读取器。
* [Rsync4j](https://github.com/fracpete/rsync4j)：适用于Linux、OSX和Windows的rsync的简单Java包装器。
* [Jayo](https://github.com/jayo-projects/jayo)：Jayo是一个基于java.io的JVM同步I/O库，这会产生简单、可读和可调试的代码，就像标准的阻塞程序一样，但它在幕后执行非阻塞I/O。

## 文件操作

* [AppDirs](https://github.com/harawata/appdirs)：AppDirs是一个小型Java库，它提供了平台相关的特殊文件夹/目录的路径。
* [FSWatch](https://github.com/vorburger/ch.vorburger.fswatch)：用于基于java.nio.file.WatchService监视目录或单个文件的Java库。
* [Wildcard](https://github.com/EsotericSoftware/wildcard)：Wildcard是一个小型Java库，用于执行文件和目录的高效模式匹配。
* [Directories](https://github.com/dirs-dev/directories-jvm)：Directories是一个提供配置/缓存/数据路径的小型库，遵循Linux、MacOS、BSD和Windows上的相应约定。
* [Directory Watcher](https://github.com/gmethvin/directory-watcher)：适用于JDK 8+的目录监视实用程序，旨在为Linux、macOS和Windows提供准确且高效的递归监视。

## 文件上传

* [Apache Commons FileUpload](https://github.com/apache/commons-fileupload)：Apache Commons FileUpload组件提供了一种简单而灵活的方法来向Servlet和Web应用程序添加对分段文件上传功能的支持。
* [FastUpload](https://sourceforge.net/projects/fastupload/)：该组件基于RFC1867，它使用高性能的字节搜索算法来解析提交的请求，然后将数据保存到文件系统中；此外，它还提供了一个智能解决方案来解决上传文本文件的编码问题。
* [MinIO Plus](https://gitee.com/lxp135/minio-plus)：MinIO-Plus是一个MinIO的二次封装与增强工具。
* [Upload Parser](https://github.com/Elopteryx/upload-parser)：Upload Parser是一个用于Servlet和Web应用程序的文件上传库。
* [Phloc FileUpload](https://mvnrepository.com/artifact/com.phloc/phloc-fileupload/1.0.2)：用于在Web应用程序中扩展文件上传处理的库。
* [Fulcrum Upload](https://turbine.apache.org/fulcrum/fulcrum-upload/)：处理来自Servlet和Portlet的POST请求的multi-part/form-data解析，使multi-part文件可从内存或文件系统上的指定位置获取。
* [AWS S3 OutputStream](https://github.com/CI-CMG/aws-s3-outputstream)：AWS S3 OutputStream项目允许通过java.io.OutputStream分段上传到AWS S3存储桶。
* [NIO-Multipart](https://github.com/synchronoss/nio-multipart)：NIO Multipart项目包含一个轻量级通用Java库，用于以非阻塞方式处理Multipart请求和响应，并具有可配置但恒定的内存占用。

## 文件比较

* [GumTree](https://github.com/GumTreeDiff/gumtree)：GumTree是一个代码区分工具。
* [DiffPlug](https://www.diffplug.com/)：DiffPlug是免费的文本编辑器/差异和图像查看器/差异。
* [Diff Utils](https://github.com/java-diff-utils/java-diff-utils)：Diff Utils库是一个开源库，用于执行文本之间的比较操作：计算差异、应用补丁、生成统一差异或解析它们、生成差异输出以方便将来显示(如并排视图)等。

## 邮件操作

* [Simple Java Mail](https://github.com/bbottema/simple-java-mail)：最简单的Java轻量级邮件库，同时能够发送复杂的电子邮件，包括CLI支持、附件、嵌入图像、自定义标头和属性、强大的地址验证、构建模式甚至DKIM签名、S/MIME支持和具有属性覆盖的外部配置文件、Spring支持和电子邮件转换工具。
* [FakeSMTP](https://github.com/Nilhcem/FakeSMTP)：FakeSMTP是一个带有GUI的免费虚拟SMTP服务器，可轻松测试应用程序中的电子邮件。
* [Apache James](https://github.com/apache/james-project)：具有基于丰富的现代高效组件的模块化架构，最终提供在JVM上运行的完整、稳定、安全和可扩展的邮件服务器。
* [Mail Utils](https://github.com/hellokaton/oh-my-email)：非常轻量的Java邮件发送类库，支持抄送、附件、模板等功能。
* [SendGrid](https://github.com/sendgrid/sendgrid-java)：该库允许你通过Java快速轻松地使用Twilio SendGrid Web API v3。
* [Fake SMTP Server](https://github.com/gessnerfl/fake-smtp-server)：Fake SMTP Server是一个简单的SMTP服务器，专为开发目的而设计。
* [Mailgun](https://github.com/sargue/mailgun)：这是一个小型Java库，可以使用出色的Mailgun服务轻松发送电子邮件。
* [Apache Commons Email](https://github.com/apache/commons-email)：Apache Commons Email提供用于发送电子邮件的API，它构建在JavaMail API之上，旨在简化JavaMail API。
* [JMail](https://github.com/RohanNagar/jmail)：一个现代、快速、零依赖的库，用于在Java中处理电子邮件地址并执行电子邮件地址验证。
* [SubEtha SMTP](https://github.com/voodoodyne/subethasmtp)：SubEtha SMTP是一个Java库，它允许你的应用程序通过简单、易于理解的API接收SMTP邮件。
* [Jakarta Mail](https://github.com/jakartaee/mail-api)：Jakarta Mail定义了一个独立于平台和协议的框架来构建邮件和消息传递应用程序。
* [Eclipse Angus Mail](https://github.com/eclipse-ee4j/angus-mail)：该项目提供了Jakarta Mail规范2.1+的实现。
* [TrashEmail](https://github.com/rosehgal/TrashEmail)：TrashEmail是托管的Telegram机器人，它可以通过提供一次性电子邮件地址来保存你的私人电子邮件地址，它可以创建、管理一次性电子邮件地址并将其与你的Telegram机器人聊天链接。
* [ExJello](https://code.google.com/archive/p/exjello/)：ExJello是一个连接到Microsoft Exchange服务器的JavaMail提供程序，它被设计为标准POP3和SMTP提供商的直接替代品。
* [DKIM](https://www.agitos.de/dkim-for-javamail/)：允许你使用DKIM对邮件进行签名的开源库。
* [Jack Mail](https://sourceforge.net/projects/jackmailclient/)：一个简单的邮件客户端，可以以最少的配置使用任何邮件服务器。
* [Aspirin](https://github.com/masukomi/aspirin)：Aspirin是一个供Java开发人员使用的嵌入式仅发送SMTP服务器。
* [Yawebmail](https://yawebmail.sourceforge.net/)：Yawebmail是一个用Java编写的Web邮件客户端，它支持SMTP(包括SMTP身份验证)、POP3和IMAP。
* [JMBox](https://sourceforge.net/projects/jmbox/)：JMBox是JavaMail的本地存储提供程序，使开发人员能够使用JavaMail API来管理存储在本地仓库(如Outlook Express、Outlook、Mozilla、Netscape等)中的邮件。
* [JavaMail Crypto](http://javamail-crypto.sourceforge.net/)：这是JavaMail API的一个补充，它使用S/MIME和/或OpenPGP提供简单的电子邮件加密和解密。
* [Jcabi-Email](https://github.com/jcabi/jcabi-email)：面向对象的电子邮件Java SDK。
* [Spring Boot Email Tools](https://github.com/ozimov/spring-boot-email-tools)：一组使用模板引擎在Spring Boot 1.5.x应用程序中发送电子邮件的服务和工具。
* [Email-RFC2822-Validator](https://github.com/bbottema/email-rfc2822-validator)：基于Java且符合RFC2822标准的电子邮件地址验证器和解析器。
* [Mailjet Java Wrapper](https://github.com/mailjet/mailjet-apiv3-java)：Mailjet Java API包装器，Mailjet是法国的电子邮件营销平台。
* [Email4J](https://github.com/juandesi/email4j)：Email4J是一个构建在javax.mail API之上的高级Java库，用于管理和发送电子邮件，无需了解底层传输的任何规范。
* [ErmesMail](https://github.com/SoftInstigate/ermes-mail)：ErmesMail是一个用于异步发送电子邮件的Java库和命令行接口。
* [ePADD](https://github.com/ePADD/epadd)：ePADD是由斯坦福大学特殊馆藏和大学档案馆开发的软件包，支持围绕电子邮件档案的评估、摄取、处理、发现和交付的档案流程。
* [MsgViewer](https://github.com/lolo101/MsgViewer)：MsgViewer是用于.msg电子邮件消息的电子邮件查看器实用程序，以纯Java实现。
* [Email Template Builder](https://github.com/rocketbase-io/email-template-builder)：该库可以以流式的方式构建HTML/文本电子邮件。
* [Outlook Message Parser](https://github.com/bbottema/outlook-message-parser)：Outlook Message Parser是一个小型开源Java库，用于解析Outlook .msg文件。

## 电子签名

* [XAdES4j](https://github.com/luisgoncalves/xades4j)：XAdES4j是XML高级电子签名(XAdES 1.3.2和1.4.1)的高级、可配置和可扩展的Java实现。
* [DigiDoc4j](https://github.com/open-eid/digidoc4j)：DigiDoc4j是一个Java库，用于对文档进行数字签名并创建签名文档的数字签名容器。
* [El Cliente @firma](https://github.com/ctt-gob-es/clienteafirma)：El Cliente @firma是自由软件(EUPLv1.1 + GPLv2)电子签名应用程序的集合，它允许在不同的操作环境中创建不同格式的电子签名。
* [DSS](https://github.com/esig/dss)：DSS是一个用于电子签名创建和验证的开源软件库，由欧盟委员会开源。
* [JHOVE](https://github.com/openpreserve/jhove)：JHOVE是一个可扩展的软件框架，用于执行数字对象的格式识别、验证和表征，由哈佛大学开发。
* [SignServer Community](https://github.com/Keyfactor/signserver-ce)：SignServer是基于PKI的开源签名软件，用于签署代码、文档、时间戳等。
* [Apache Santuario](https://github.com/apache/santuario-xml-security-java)：Apache Santuario是实现XML数字签名规范和XML加密规范的库。

## 安全培训

* [CRAPI](https://github.com/OWASP/crAPI)：CRAPI在设计上很容易受到攻击，但你将能够安全地运行它来教育/培训自己，由OWASP开源。
* [WebGoat](https://github.com/WebGoat/WebGoat)：WebGoat是由OWASP维护的故意不安全的Web应用程序，旨在教授Web应用程序安全课程。
* [BodgeIt](https://github.com/psiinon/bodgeit)：BodgeIt Store是一个易受攻击的Web应用程序，目前针对渗透测试的新手。
* [OWASP Benchmark](https://github.com/OWASP-Benchmark/BenchmarkJava)：OWASP Benchmark项目是一个Java测试套件，旨在验证漏洞检测工具的速度和准确性。
* [OWASP Security Shepherd](https://github.com/OWASP/SecurityShepherd)：OWASP Security Shepherd项目是一个Web和移动应用程序安全培训平台，旨在培养和提高不同技能人群的安全意识。
* [MASTG Hacking Playground](https://github.com/OWASP/MASTG-Hacking-Playground)：MASTG Hacking Playground是一系列教育性iOS和Android移动应用程序，这些应用程序故意构建为不安全的，以便为开发人员、安全研究人员和渗透测试人员提供实用指导。

## RSS

* [ROME](https://github.com/rometools/rome)：ROME是一个用于RSS和Atom提要的Java框架。
* [Huntly](https://github.com/lcomplete/huntly)：Huntly是一个信息管理工具，它不仅可以自托管，也可以通过客户端在本地运行。
* [CommaFeed](https://github.com/Athou/commafeed)：受Google Reader启发而开发的自托管RSS阅读器，基于Dropwizard和React/TypeScript。
* [Android-RSS](https://github.com/ahorn/android-rss)：用于解析RSS 2.0提要的轻量级Android库。
* [Sismics Reader](https://github.com/sismics/reader)：一个开源、基于Web的内容聚合器，由Web Feeds(RSS、Atom)提供服务。
* [RSSOwl](https://github.com/rssowl/RSSOwl)：一个功能强大的应用程序，可以以舒适的方式组织、搜索和阅读RSS、RDF和Atom新闻源。
* [RSS Reader](https://github.com/w3stling/rssreader)：一个简单的Java库，用于读取RSS和Atom提要。
* [Makagiga](https://github.com/kdt/makagiga)：Makagiga是一款开源、易于使用的便携式应用程序，用于执行各种任务，例如待办事项列表、文本编辑或RSS阅读。
* [RSS Parser](https://github.com/prof18/RSS-Parser)：RSS Parser是一个用于解析RSS和Atom提要的Kotlin多平台库，支持Android、iOS和JVM。

## SSE

* [Okhttp-EventSource](https://github.com/launchdarkly/okhttp-eventsource)：基于OkHttp的Java SSE客户端实现。
* [OkSse](https://github.com/heremaps/oksse)：OkSse是OkHttp的扩展库，用于创建SSE客户端。
* [Turbine](https://github.com/Netflix/Turbine)：Turbine是一种用于将SSE JSON数据流聚合到单个流中的工具，由Netflix开源。
* [SSE-EventBus](https://github.com/ralscha/sse-eventbus)：EventBus库，用于使用SSE将事件从Spring应用程序发送到Web浏览器。

## RPM

* [Redline](https://github.com/craigwblake/redline)：Redline是一个纯Java库，用于操作RPM包。
* [Eclipse Packager](https://github.com/eclipse/packager)：Eclipse Packager项目提供了一组核心功能，可在纯Java中使用RPM和Debian包文件。

## EMF

* [Eclipse EMF Client Platform](https://git.eclipse.org/r/plugins/gitiles/emfclient/org.eclipse.emf.ecp.core)：Eclipse EMF Client Platform是用于构建基于EMF的客户端应用程序的框架。
* [NeoEMF](https://github.com/atlanmod/NeoEMF)：NeoEMF是Eclipse建模框架(EMF)的持久层，支持不同的NoSQL数据库Neo4j、BerkeleyDB、MongoDB等。

## EPC

* [EPCIS](https://github.com/JaewookByun/epcis)：Oliot EPCIS 2.2.0是电子产品代码信息服务(EPCIS) v2.0的原型实现，能够捕获和共享GS1批准的标准化事件/主数据，由韩国世宗大学开源。
* [OpenEPCIS](https://github.com/openepcis)：OpenEPCIS是GS1 EPCIS标准的开源完全兼容实现，它还提供了许多开源项目、工具和工件。
* [EPCtagCoder](https://github.com/jlcout/epctagcoder)：EPCtagCoder是一个极其直观、小型且超快的Java EPC编码和解码库。

## FMI

* [FMI4j](https://github.com/NTNU-IHB/FMI4j)：FMI4j是一个用Kotlin编写的软件包，用于处理功能模型单元(FMU)，由挪威科技大学开源。
* [JavaFMI](https://bitbucket.org/siani/javafmi)：JavaFMI是一组与功能模型接口FMI配合使用的组件。

## OSGI

* [Distributed Data Framework](https://github.com/codice/ddf)：DDF是一个开源、模块化的集成框架。
* [Apache ServiceMix](https://github.com/apache/servicemix)：一个灵活的开源集成容器，它将ActiveMQ、Camel、CXF和Karaf的特性和功能成为一个强大的运行时平台，你可以使用它来构建自己的集成解决方案。它提供了一个完全由OSGi提供支持的企业级ESB。
* [Apache Karaf](https://github.com/apache/karaf)：Karaf提供了一个轻量级的OSGi容器，可以用于部署各种组件。
* [OPS4j Pax Web](https://github.com/ops4j/org.ops4j.pax.web)：Pax Web通过更好的Servlet支持、过滤器、监听器、错误页面和JSP等扩展了OSGi HTTP服务，以满足最新版本的Servlet规范。
* [Bnd](https://github.com/bndtools/bnd)：用于构建OSGi包的工具，包括Eclipse、Maven和Gradle插件。
* [OSGi enRoute](https://github.com/osgi/osgi.enroute)：OSGi enRoute项目提供了OSGi应用程序的编程模型，该项目包含为OSGi enRoute基本配置文件提供API的捆绑包和用于OSGi enRoute项目的捆绑包。
* [Apache ACE](https://ace.apache.org/)：一个软件分发框架，允许你集中管理软件组件、配置数据和其他工件并将其分发到目标系统。它是使用OSGi构建的，可以部署在不同的拓扑中。
* [Apache Aries](https://github.com/apache/aries)：Aries项目由一组可插拔Java组件组成，支持企业OSGi应用程序编程模型。
* [Eclipse Kura](https://github.com/eclipse/kura)：基于OSGi的M2M服务网关应用程序框架。
* [Apache Felix](https://github.com/apache/felix-dev)：OSGi框架实现及相关技术。
* [Eclipse Equinox](https://eclipse.dev/equinox/)：Equinox是OSGi核心框架规范的实现，这是一组实现各种可选OSGi服务和其他用于运行基于OSGi的系统的基础设施的捆绑包。
* [Eclipse Virgo](https://projects.eclipse.org/projects/rt.virgo)：基于OSGI的服务器，旨在运行企业Java应用程序和Spring支持的应用程序。
* [OSGi Testing](https://github.com/osgi/osgi-test)：该项目提供了一组捆绑包，其中包含用于测试OSGi API的有用类。
* [Eclipse Tycho](https://github.com/eclipse-tycho/tycho)：Eclipse Tycho是使用Maven构建Eclipse平台插件/OSGi捆绑包、功能、更新站点/p2仓库和Eclipse RCP应用程序的清单优先方式。
* [PAX-Logging](https://github.com/ops4j/org.ops4j.pax.logging)：OSGi日志框架实现，支持SLF4J、LOG4J、JCL等。

## 数控

* [Universal G-Code Sender](https://github.com/winder/Universal-G-Code-Sender)：Universal G-Code Sender是一个基于Java的跨平台G-Code发送器，与GRBL、TinyG、g2core和Smoothieware兼容。
* [CNC-GCode-Controller](https://github.com/im-pro-at/cncgcodecontroller)：在CNC机器上使用rerap控制器。
* [GCode Sender](https://github.com/SourceRabbit/gcode-sender)：跨平台3轴数控机床控制软件。

## 数电

* [Workcraft](https://github.com/workcraft/workcraft)：Workcraft是一个跨平台工具集，用于捕获、模拟、合成和验证图形模型。
* [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)：Logisim-evolution是用于设计和模拟数字逻辑电路的教育软件。
* [Digital](https://github.com/hneemann/Digital)：Digital是一款易于使用的数字逻辑设计器和电路模拟器，专为教育目的而设计。
* [Cello](https://github.com/CIDARLAB/cello)：遗传电路设计自动化，由CIDAR实验室开发。
* [Logisim](https://github.com/Logisim-Ita/Logisim)：Logisim是一个数字电路模拟器。
* [CircuitJS1](https://github.com/sharpie7/circuitjs1)：CircuitJS1是一个在浏览器中运行的电子电路模拟器。

## 工业

* [RXTX](https://github.com/rxtx/rxtx)：RXTX是Java中串口的本机接口。
* [JLibModbus](https://github.com/kochedykov/jlibmodbus)：JLibModbus是Modbus协议的Java语言实现。
* [jSSC](https://github.com/scream3r/java-simple-serial-connector)：Java中用于使用串行端口的库。
* [SerialPundit](https://github.com/RishiGupta12/SerialPundit)：SerialPundit是一个用于串行端口和HID通信的SDK。
* [PureJavaComm](https://github.com/nyholku/purejavacomm)：用于从Java访问串行端口的API。
* [jSerialComm](https://github.com/Fazecast/jSerialComm)：一个独立于平台的Java串行端口访问库。
* [NRJavaSerial](https://github.com/NeuronRobotics/nrjavaserial)：Java串行端口系统，这是RXTX项目的一个分支，用于本地代码的jar加载。
* [jRxTx](https://github.com/openmuc/jrxtx)：jRxTx是一个Java串行通信库，它可用于使用众所周知的基于UART的串行协议进行通信。

## 海关

* [GTAS](https://github.com/US-CBP/GTAS)：GTAS是用于提高边境安全的网络应用程序，它使政府机构能够在高风险航空旅客计划旅行之前自动识别他们，由美国海关和边境保护局开源。
* [China E-Port Data Signature](https://github.com/Weasley-J/chinaport-data-signature)：该项目为中国电子口岸海关总署XML报文和海关179数据上报加签服务，提供一站式的免费解决方案，开箱即用。

## 蓝牙

* [Bluetooth Manager](https://github.com/sputnikdev/bluetooth-manager)：用于管理蓝牙适配器、蓝牙设备、GATT服务和特性的库/框架。
* [BlueCove](https://sourceforge.net/projects/bluecove/)：Bluecove是Java的跨平台蓝牙库，最初由英特尔研究院开发。

## 校验

* [Jakarta Validation](https://github.com/jakartaee/validation)：Jakarta Validation为JavaBean和方法验证定义了元数据模型和API。
* [Hibernate Validator](https://github.com/hibernate/hibernate-validator)：Hibernate Validator是Jakarta Bean Validation的参考实现。
* [Apache BVal](https://github.com/apache/bval)：这是Jakarta EE和Java SE的Java Bean Validation(JSR 303、349、380)规范的实现。
* [Fluent Validator](https://github.com/neoremind/fluent-validator)：Fluent Validator通过利用流式接口风格和JSR 303 Bean Validation规范，提供了轻松支持验证的功能。
* [YAVI](https://github.com/making/yavi)：YAVI是一种基于Lambda的Java类型安全验证框架。
* [Apache Commons Validator](https://github.com/apache/commons-validator)：Apache Commons Validator为客户端验证和服务器端数据验证提供构建块。
* [Java Fluent Validator](https://github.com/mvallim/java-fluent-validator)：Java Fluent Validator在Java语言中定义了一个内部DSL供程序员使用。
* [Coody Verification](https://gitee.com/coodyer/coody-verification)：Coody Verification是一款参数自动化校验工具。
* [JBVE](https://github.com/nomemory/java-bean-validation-extension)：JBVE是一个小型工具库，它通过额外注解扩展了Java Bean Validation规范。
* [Collection Validator](https://github.com/jirutka/validator-collection)：该库可以轻松地为任何验证约束创建“伪约束”来标注简单类型的集合，而无需为每个集合编写额外的验证器或不必要的包装类。
* [dOOv](https://github.com/doov-org/doov)：dOOv是一个用于类型安全域模型验证和映射的流式API。
* [Avaje Validator](https://github.com/avaje/avaje-validator)：通过APT源代码生成进行无反射POJO验证的Java库。
* [OVal](https://github.com/sebthom/oval)：OVal是一个实用且可扩展的验证框架，适用于任何类型的Java对象，可以使用注解(@NotNull、@MaxLength)、POJO或XML来声明约束。
* [Functional Validation](https://github.com/MAIF/functional-validation)：该库提供了工具来验证Bean并组合验证堆栈错误。
* [Vador](https://github.com/salesforce-misc/Vador)：Vador是一个现代验证框架，旨在简化和提高REST API验证，由Salesforce开源。

## 元编程

* [JParsec](https://github.com/jparsec/jparsec)：Jparsec是一个为Java编写的递归下降解析器组合器框架。
* [Parboiled](https://github.com/sirthias/parboiled)：Parboiled是一个混合Java/Scala库，提供基于解析表达式语法(PEG)的轻量级且易于使用但功能强大且优雅的任意输入文本解析。
* [Eclipse Xtext](https://github.com/eclipse/xtext)：Eclipse Xtext是一个用于开发编程语言和特定领域语言的框架。
* [MPS](https://github.com/JetBrains/MPS)：JetBrains元编程系统。
* [GenSym](https://github.com/Generative-Program-Analysis/GenSym)：GenSym是LLVM IR的高性能并行符号执行引擎。
* [Rascal](https://github.com/usethesource/rascal)：Rascal是一个开源、基于Java的元编程库，由荷兰阿姆斯特丹自由大学的UseTheSource团队开发。
* [Procyon](https://github.com/mstrobel/procyon)：Procyon是一套专注于代码生成和分析的Java元编程工具。
* [JNI Bind](https://github.com/google/jni-bind)：JNI Bind是一个新的元编程库，为C++ => Java/Kotlin提供语法糖，Google开源。
* [JBSE](https://github.com/pietrobraione/jbse)：JBSE是一个用于自动程序分析、验证和测试生成的符号Java虚拟机。
* [Symbolic Java PathFinder](https://github.com/SymbolicPathFinder/jpf-symbc)：此JPF扩展为Java字节码提供符号执行，由NASA开源。

## 分词器

* [Jieba Analysis](https://github.com/huaban/jieba-analysis)：结巴分词Java版。
* [Elasticsearch IK Analysis](https://github.com/medcl/elasticsearch-analysis-ik)：IK分词插件可将Lucene IK分词器集成到ElasticSearch中，支持自定义字典。
* [Sudachi](https://github.com/WorksApplications/Sudachi)：Sudachi是日本形态分析仪。
* [JTokkit](https://github.com/knuddelsgmbh/jtokkit)：JTokkit是一个专为与OpenAI模型一起使用而设计的Java分词器库。
* [Kuromoji](https://github.com/atilika/kuromoji)：Kuromoji是一个独立且非常易于使用的日语形态分析器，专为搜索而设计。
* [Word](https://github.com/ysc/word)：Word分词是一个Java实现的分布式的中文分词组件，提供了多种基于词典的分词算法。
* [Segment](https://github.com/houbb/segment)：Segment是基于结巴分词词库实现的更加灵活，高性能的Java分词实现。
* [IK Analyzer Solr](https://github.com/magese/ik-analyzer-solr)：Solr 7.X-8.X的IK分词器。
* [ElasticSearch Analysis Vietnamese](https://github.com/duydo/elasticsearch-analysis-vietnamese)：用于ElasticSearch的越南语分词插件。
* [IdeaSeg](https://gitee.com/indexea/ideaseg)：IdeaSeg是Indexea推出的一个基于最新的HanLP自然语言处理工具包实现的中文分词器。
* [THULAC](https://github.com/thunlp/THULAC-Java)：THULAC是由清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包，具有中文分词和词性标注功能。
* [THUCTC](https://github.com/thunlp/THUCTC)：THUCTC是由清华大学自然语言处理实验室推出的中文文本分类工具包，能够自动高效地实现用户自定义的文本分类语料的训练、评测、分类功能。
* [ElasticSearch BosonNLP Analysis](https://github.com/bosondata/elasticsearch-analysis-bosonnlp)：玻森数据开发的一款基于玻森中文分词的ElasticSearch插件。
* [Ansj中文分词](https://github.com/NLPchina/ansj_seg)：这是一个基于n-Gram+CRF+HMM的中文分词的Java实现。
* [Ik Analyzer](https://github.com/blueshen/ik-analyzer)：支持Lucene 5/6/7/8/9+版本的分词器。
* [Elasticsearch Analysis Morfologik](https://github.com/allegro/elasticsearch-analysis-morfologik)：适用于ElasticSearch 8.x、7.x、6.x、5.x和2.x的Morfologik(波兰语)插件，由Allegro开源。
* [MMSeg4j](https://github.com/chenlb/mmseg4j-core)：MMSeg4j是使用Chih-Hao Tsai的MMSeg算法实现的中文分词器。

## 文本表

* [Picnic Tables](https://github.com/JakeWharton/picnic)：Kotlin DSL和Java/Kotlin构建器API，用于构建可呈现为文本的类似HTML的表格。
* [Flip Tables](https://github.com/JakeWharton/flip-tables)：用于在Java中打印漂亮的文本表。
* [ASCII Table](https://github.com/vdmeer/asciitable)：ASCII Table是一个简单的工具，用于格式化表格，具有缩进、缩进字符、对齐、填充、填充字符和行内空白字符的各种行/列选项。
* [ASCII-Data](https://github.com/MitchTalmadge/ASCII-Data)：一个小型Java库，用于生成漂亮的基于文本的线图和表格。
* [Ascii-Art-Table](https://github.com/klaus31/ascii-art-table)：通过Java将数据打印到Ascii表的简单库。
* [ASCII Tables](https://github.com/freva/ascii-table)：使用Java轻松创建和自定义简单的ASCII表。

## 语言库

* [TinyPinyin](https://github.com/promeG/TinyPinyin)：适用于Java和Android的快速、低内存占用的汉字转拼音库。
* [Elasticsearch Pinyin Analysis](https://github.com/infinilabs/analysis-pinyin)：该拼音分析插件用于进行汉字与拼音之间的转换。
* [Pinyin4j](https://github.com/belerweb/pinyin4j)：支持汉字(简体和繁体)到最流行的拼音系统，包括汉语拼音、通用拼音、Wade-Giles、MPS2、Yale和Gwoyeu Romatzyh。
* [Pinyin](https://github.com/houbb/pinyin)：Java高性能中文转拼音工具，支持同音字。
* [Pinyin Plus](https://github.com/taptap/pinyin-plus)：汉字转拼音库，支持多音字，由Taptap开源。
* [Bopomofo4j](https://gitee.com/rnkrsoft/Bopomofo4j)：零依赖，纯Java开发的汉字转拼音库。
* [JPinyin](https://github.com/qzw1210/jpinyin)：JPinyin是一个汉字转拼音的Java开源类库，在PinYin4j的功能基础上做了一些改进。
* [Moji4J](https://github.com/andree-surya/moji4j)：Moji4J是一个开源Java库，用于在日语平假名、片假名和罗马字脚本之间进行转换。
* [Myanmar Tools](https://github.com/google/myanmar-tools)：该项目包括用于处理缅甸使用的字体编码的工具，目前支持广泛的Zawgyi-One字体编码，由Google开源。
* [BadWordFiltering](https://github.com/VaneProject/bad-word-filtering)：这是一个检查和处理脏话的库。

## 泛型库

* [TypeTools](https://github.com/jhalterman/typetools)：一个用于处理类型的简单、零依赖库，支持Java 1.6+和Android。
* [ClassMate](https://github.com/FasterXML/java-classmate)：ClassMate是一个零依赖Java库，用于准确内省类型信息，包括可靠解析类(“类型”)和成员(字段、方法和构造函数)的泛型类型声明。
* [Generics-Resolver](https://github.com/xvik/generics-resolver)：Java泛型运行时解析器。
* [GeantyRef](https://github.com/leangen/geantyref)：用于Java的泛型类型反射库。

## 国际化

* [Unicode CLDR](https://github.com/unicode-org/cldr)：Unicode CLDR为支持世界语言的软件提供了关键构建块，并拥有最大、最广泛的可用语言环境数据标准存储库。
* [L10nMessages](https://github.com/pinterest/l10nmessages)：L10nMessages是一个使Java应用程序的国际化(i18n)和本地化(l10n)变得简单且安全的库，由Pinterest开源。
* [NV-1i8n](https://github.com/TakahikoKawasaki/nv-i18n)：支持国际化的包，包含ISO 3166-1国家代码枚举、ISO 639-1语言代码枚举、ISO 15924脚本代码枚举等。
* [Mojito](https://github.com/box/mojito)：Mojito是一个持续本地化平台，依靠持续集成将所有软件字符串收集到一处，实时查看哪些产品需要本地化。
* [Tradukisto](https://github.com/allegro/tradukisto)：用于将数字转换为其单词表示形式的Java库，由Allegro开源。
* [Kilt](https://github.com/hupfdule/kilt)：Kilt是一组小工具，用于简化Java i18n资源包的处理。
* [ICU4j](https://github.com/unicode-org/icu)：为软件应用提供Unicode和国际化支持，由Unicode Consortium开源。
* [Gettext](https://github.com/jgettext/gettext-commons)：Gettext Commons项目为国际化(i18n)通过GNU gettext和Java实现资源包。
* [Cosmopolitan](https://github.com/rodionmoiseev/c10n)：一个Java库，专注于使国际化更加模块化、更易于发展和维护、易于更改且IDE友好，无需过多的外部工具。
* [Easy I18N](https://github.com/awkay/easy-i18n)：这是一个Java库，旨在使创建国际化程序变得更加容易。
* [Resource4j](https://github.com/resource4j/resource4j)：Resource4j库是Java ResourceBundle机制的替代品，支持大型和遗留应用程序的复杂i18n场景，并提供对键/值应用程序配置和任意资源文件的安全访问。
* [Loc4J](https://loc4j.sourceforge.net/)：Loc4J是一个Java库，可帮助本地化应用程序。
* [Language Detector](https://github.com/optimaize/language-detector)：Java语言检测库。
* [I18n](https://github.com/vidageek/i18n)：在Java Web应用程序上使用i18n的简单方法。
* [Lokalized](https://github.com/lokalized/lokalized-java)：Lokalized有助于在JVM上进行听起来自然的软件翻译。
* [OmegaT](https://github.com/omegat-org/omegat)：OmegaT是一款免费开源多平台计算机辅助翻译工具，具有模糊匹配、翻译记忆库、关键字搜索、术语表以及翻译到更新项目中的功能。
* [Singleton](https://github.com/vmware/singleton)：Singleton是一个用于简化软件全球化的开源应用程序，由VMWare开源。
* [CLDR](https://github.com/unicode-org/cldr)：CLDR为支持世界语言的软件提供了关键构建块，拥有最大、最广泛的可用区域设置数据标准存储库，由Unicode Consortium开源。
* [Kilt](https://github.com/poiu-de/kilt)：Kilt是一组小工具，用于简化Java i18n资源包的处理。

## 翻译库

* [MTrans](https://github.com/hujingshuang/MTrans)：MTrans提供了集多种主流的在线翻译及TTS功能于一身的轻量级服务。
* [Zanata](https://github.com/zanata/zanata-platform)：Zanata是一个基于Web的系统，供翻译人员使用Web浏览器在线翻译文档和软件。
* [Translator](https://github.com/therealbush/translator)：适用于Kotlin/JVM和Java的简单且免费的Google翻译库。

## 字典库

* [Mdict Java](https://github.com/KnIfER/mdict-java)：用于Java的Mdict字典文件格式的查询库。
* [ExtJWNL](https://github.com/extjwnl/extjwnl)：ExtJWNL是一个用于创建、读取和更新WordNet格式词典的Java API。
* [Stardict4j](https://codeberg.org/miurahr/stardict4j)：Stardict4j是Java版StarDict词典文件的访问库。

## 短链接

* [ShortLink](https://github.com/Enndfp/short-link)：SaaS短链接系统，为企业和个人用户提供了一个高效、安全和可靠的短链接管理平台。
* [URLShorter](https://gitee.com/tinyframework/urlshorter)：满足多种场景下的短链接生成需求。

## 单位库

* [UnitOf](https://github.com/Digidemic/UnitOf)：适用于Java、JavaScript和C#的测量和数据类型转换库。
* [Unit API](https://github.com/unitsofmeasurement/unit-api)：Unit API提供了一组用于处理单位和数量的Java语言编程接口。
* [Measured](https://github.com/nacular/measured)：Measured提供了一种安全且简单的使用测量单位的方法。
* [QUDTLib](https://github.com/qudtlib/qudtlib-java)：QUDTLib为Java提供单位转换及相关功能。

## 词法解析

* [ANTLR](https://github.com/antlr/antlr4)：ANTLR是一个强大的解析器生成器，用于读取、处理、执行或翻译结构化文本或二进制文件。
* [JavaParser](https://github.com/javaparser/javaparser)：该项目包含一组实现具有高级分析功能的Java 1.0 - Java 17解析器的库。
* [Flexmark Java](https://github.com/vsch/flexmark-java)：Flexmark Java是CommonMark(规范0.28)解析器的Java实现，使用块优先、内联后Markdown解析架构。
* [Kotlinx.AST](https://github.com/kotlinx/ast)：Kotlinx.AST是一个通用的AST解析库，Kotlin是目前唯一支持的语言。
* [PartiQL Lang Kotlin](https://github.com/partiql/partiql-lang-kotlin)：PartiQL是一种富有表现力的、与SQL兼容的查询语言，可以访问关系型、半结构化和嵌套数据，由Amazon开源。
* [Gumtree Spoon AST Diff](https://github.com/SpoonLabs/gumtree-spoon-ast-diff)：使用Gumtree算法计算两个Spoon抽象语法树之间的AST差异。
* [JavaCC](https://github.com/javacc/javacc)：JavaCC是用于Java应用程序的最流行的解析器生成器。
* [JFlex](https://github.com/jflex-de/jflex)：JFlex是Java的词法分析器生成器(也称为扫描器生成器)。
* [RSQL Parser](https://github.com/jirutka/rsql-parser)：RSQL是一种用于对RESTful API中的条目进行参数化过滤的查询语言。
* [Parboiled](https://github.com/sirthias/parboiled)：Parboiled是一个混合Java/Scala库，提供基于解析表达式语法(PEG)的轻量级且易于使用但功能强大且优雅的任意输入文本解析。
* [Parrot](https://github.com/daniellansun/groovy-parser)：Parrot可以解析Groovy源代码并构造相关的AST，与旧解析器生成的AST几乎相同。
* [Java Tree Sitter](https://github.com/serenadeai/java-tree-sitter)：Tree-Sitter是一个解析器生成工具和增量解析库。
* [Canopy](https://github.com/jcoglan/canopy)：Canopy是一个针对Java、JavaScript、Python和Ruby的解析器编译器。

## 形式验证

* [CATG](https://github.com/ksen007/janala2)：Concolic单元测试引擎，使用形式化方法自动生成单元测试。
* [Checker Framework](https://checkerframework.org/)：可插拔类型系统，包括空类型、物理单位、不变性类型等等。
* [Daikon](https://github.com/codespecs/daikon)：检测可能的程序不变量并根据这些不变量生成JML规范，由华盛顿大学开源。
* [Java PathFinder](https://github.com/javapathfinder/jpf-core)：JVM形式验证工具，包含模型检查器等，由NASA开源。
* [JmlOk2](https://massoni.computacao.ufcg.edu.br/home/jmlok)：通过反馈引导的随机测试生成来检测代码和JML规范之间的不一致，并建议检测到的每个不符合项的可能原因，由大坎皮纳联邦大学开发。
* [jCUTE](https://github.com/osl/jcute)：jCUTE自动生成Java程序的单元测试，Concolic执行将随机具体执行与符号执行和自动约束求解相结合。
* [KeY](https://github.com/KeYProject/key)：形式化软件开发工具，旨在尽可能无缝地集成面向对象软件的设计、实现、形式化规范和形式化验证，由卡尔斯鲁厄理工学院开源。
* [OpenJML](https://github.com/OpenJML/OpenJML)：Java程序的程序验证工具，可让你检查以Java建模语言注释的程序规范。
* [Java Modeling Language](https://www.cs.ucf.edu/~leavens/JML/index.shtml)：JML是一种行为接口规范语言，可用于指定Java模块的行为，佛罗里达大学开发。
* [Theta](https://github.com/ftsrg/theta)：Theta是布达佩斯技术经济大学关键系统研究组开发的通用、模块化和可配置的模型检查框架，旨在支持基于抽象细化的算法的设计和评估，以进行各种形式主义的可达性分析。

## 项目模板

* [JBoss Forge](https://github.com/forge/core)：JBoss Forge是一款软件开发工具，可扩展你的Java IDE，为不同的技术和解决方案提供向导和扩展。
* [PLMCodeTemplate](https://github.com/xwjie/PLMCodeTemplate)：Spring开发代码模板。
* [AWS CloudFormation Template](https://github.com/widdix/aws-cf-templates)：AWS CloudFormation的免费模板。
* [React Native Template TypeScript](https://github.com/react-native-community/react-native-template-typescript)：干净且简约的React Native模板，可快速开始使用TypeScript。
* [Selenium Maven Template](https://github.com/Ardesco/Selenium-Maven-Template)：快速搭建Selenium项目的Maven模板。
* [Spring Boot Template](https://github.com/hmcts/spring-boot-template)：该模板的目的是加快新Spring应用程序的创建速度，并帮助在多个团队之间保持相同的标准，由英国法院及审裁处事务局开源。
* [AEM Project Archetype](https://github.com/adobe/aem-project-archetype)：Maven模板，创建一个最小的、基于最佳实践的Adobe Experience Manager(AEM)项目作为你网站的起点。
* [Spring MVC Quickstart Maven Archetype](https://github.com/kolorobot/spring-mvc-quickstart-archetype)：该项目是Spring MVC Web应用程序的Maven原型。
* [Spring Boot Starter](https://github.com/ericus20/spring-boot-starter)：一个高度固执且完整的Spring Boot生产就绪项目的Starter。
* [Spring Boot Starter-kit](https://github.com/khandelwal-arpit/springboot-starterkit)：适用于Spring Boot应用程序的生产就绪入门套件。
* [Spring Boot Boilerplate](https://github.com/Genc/spring-boot-boilerplate)：Spring Boot Boilerplate是一个Starter套件，该项目包括Spring Boot(v 2.7.10)、Spring Data JPA、Spring Validation、Spring Security + JWT Token、PostgreSQL、Mapstruct、Lombok、Swagger。
* [Spring Boot Supabase](https://github.com/ChangeNode/spring-boot-supabase)：现代Java Web应用程序入门模板。

## 印章生成

* [SealKit](https://gitee.com/liuzy1988/SealKit)：印章生成工具。
* [SealUtil](https://github.com/localhost02/SealUtil)：印章生成工具，使用Java Graphics2D生成各类圆形/椭圆公章、私章图片。
* [开放签](https://gitee.com/kaifangqian/kaifangqian-base)：开放签提供企业印章制作、证书签发、文件签署API接口服务。

## N+1问题

* [DBUtil](https://github.com/vladmihalcea/db-util)：该工具可以在测试期间自动检测N+1查询问题。
* [JPlusOne](https://github.com/adgadev/jplusone)：JPlusOne是用于自动检测和断言基于JPA的Spring Boot Java应用程序中发生的“N+1问题”并查找JPA发出的SQL语句的一般来源的工具。
* [Spring Hibernate Query Utils](https://github.com/yannbriancon/spring-hibernate-query-utils)：该库提供了检测N+1查询并对Spring和Hibernate生成的查询进行计数的工具。

## 敏感词过滤

* [Sensitive-Word](https://github.com/houbb/sensitive-word)：基于DFA算法实现的高性能敏感词工具。
* [Sensitive-Word-Filter](https://github.com/hailin0/sensitive-word-filter)：简易敏感词处理器，支持返回敏感词、高亮敏感词、替换敏感词等操作。
* [Sensitive-Words-Filter](https://github.com/hooj0/sensitive-words-filter)：敏感词过滤项目，提供TTMP、DFA、DAT、Hash Bucket、Tire算法支持过滤。

## 正则表达式

* [RegexGenerator](https://github.com/MaLeLabTs/RegexGenerator)：该项目包含用于生成文本提取正则表达式的工具的源代码。
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)：VerbalExpressions是一个Java库，可帮助构建困难的正则表达式。
* [Generex](https://github.com/mifmif/Generex)：用于生成与给定正则表达式匹配的字符串的Java库。
* [RE2/J](https://github.com/google/re2j)：一个正则表达式引擎，其运行时间与输入大小成线性关系，由Google开源。
* [Joni](https://github.com/jruby/joni)：Oniguruma正则表达式库的Java端口。
* [Hyperscan-Java](https://github.com/gliwka/hyperscan-java)：Hyperscan是一个高性能的多正则表达式匹配库。
* [DRegex](https://github.com/marianobarrios/dregex)：DRegex是一个Java库，它使用确定性有限自动机(DFA)实现正则表达式引擎。
* [Readable Regex](https://github.com/ricoapon/readable-regex)：使用这个库，可以以可读的方式创建正则表达式。
* [Readable Regex](https://github.com/codebox/readable-regex)：该库提供了一种使Java代码中的复杂正则表达式更具可读性的方法。
* [RgxGen](https://github.com/curious-odd-man/RgxGen)：根据正则表达式模式生成匹配和不匹配的字符串。

## 代码生成器

* [Auto](https://github.com/google/auto)：一系列用于Java的源代码生成器，由Google开发。
* [Joda-Beans](https://github.com/JodaOrg/joda-beans)：Joda-Beans提供了一个向Java添加属性的小型框架，极大地增强了Java Bean。
* [Burningwave](https://github.com/burningwave/core)：一个先进且高度优化的Java库，用于构建框架：它对于扫描类路径、在运行时生成类、促进反射的使用、扫描文件系统、执行字符串化源代码等等很有用。
* [JavaPoet](https://github.com/square/javapoet)：用于生成.java源文件的Java API。
* [Java::Geci](https://github.com/verhas/javageci)：Java::Geci是一个用于生成Java代码的库，可以使用Java::Geci执行代码生成程序来生成新的源代码或修改现有的Java源文件。
* [Avaje-HTTP](https://github.com/avaje/avaje-http)：Javalin、Helidon SE的控制器生成器。
* [Fulib](https://github.com/fujaba/fulib)：Fulib是一个为UML类模型和一些模型管理功能提供代码生成的库，使用Java API提供的特定于域的语言，它允许你定义类、属性以及与元模型的关联。
* [ADT4J](https://github.com/sviperll/adt4j)：该库为Java实现了代数数据类型。
* [AutoRecord](https://github.com/pawellabaj/auto-record)：AutoRecord是一个代码生成器，可以帮助你轻松生成Java记录。
* [MAKU](https://gitee.com/makunet/maku-generator)：一款低代码生成器，可根据自定义模板内容，快速生成代码，可实现项目的快速开发、上线，减少重复的代码编写。
* [Sculptor](https://github.com/sculptor/sculptor)：Sculptor是一个代码生成器，应用了领域驱动设计和领域特定语言的概念。
* [Bootify](https://bootify.io/)：使用JPA模型和REST API生成基于浏览器的Spring Boot应用程序，商业项目。
* [Scrooge](https://github.com/twitter/scrooge)：Scrooge是一个用Scala编写的thrift代码生成器，目前可以为Scala、Java、Cocoa、Android和Lua生成代码，Twitter开源。
* [SourceBuddy](https://github.com/sourcebuddy/sourcebuddy)：SourceBuddy是一个Java库，可用于在程序中编译和加载动态生成的Java源代码。
* [Code Gen](https://gitee.com/durcframework/code-gen)：一款代码生成工具，可自定义模板生成不同的代码，支持MySQL、Oracle、SQL Server、PostgreSQL。
* [AiCode](https://gitee.com/lemur/aicode)：新一代代码生成器，根据模板配置生成代码。
* [Jeddict](https://github.com/jeddict/jeddict)：Jakarta EE 10和MicroProfile应用程序生成器和建模器。
* [Generator-SpringBoot](https://github.com/sivaprasadreddy/generator-springboot)：用于生成Spring Boot微服务的Yeoman生成器。
* [Enunciate](https://github.com/stoicflame/enunciate)：Enunciate是一个构建时Web服务增强工具，可应用于基于Java的项目，以便从Web服务端点的源代码生成大量很酷的工件。
* [Telosys](https://github.com/telosys-tools-bricks/telosys-cli)：简单而轻量的代码生成器，可作为Eclipse插件和CLI使用。
* [Magic Bean](https://github.com/bowbahdoe/magic-bean)：一个生成Getter和Setter的非常基本的库。
* [Parceler](https://github.com/johncarl81/parceler)：Parceler是一个代码生成库，可生成Android Parcelable样板源代码。
* [JCodeModel](https://github.com/phax/jcodemodel)：Java代码生成库。
* [Spring Boot Code Generator](https://github.com/moshowgame/SpringBootCodeGenerator)：基于Spring Boot 2 + Freemarker的Java代码生成器。
* [Spring Roo](https://github.com/spring-attic/spring-roo)：Spring Roo是面向Java开发人员的快速应用程序开发(RAD)工具，它允许我们使用简单易用的命令为Spring应用程序生成样板代码和项目结构。
* [Acceleo](https://eclipse.dev/acceleo/)：Acceleo是Eclipse的开源代码生成器，可从任何元模型(UML、SysML等)定义的EMF模型生成代码。

## 目录服务

* [PWM](https://github.com/pwm-project/pwm)：PWM是一个用于LDAP目录的开源密码自助服务应用程序。
* [DavMail](https://github.com/mguessan/davmail)：POP/IMAP/SMTP/Caldav/Carddav/LDAP Exchange和Office 365网关。
* [Spring LDAP](https://github.com/spring-projects/spring-ldap)：Spring LDAP是一个用于简化Java LDAP编程的库，其构建原理与Spring JDBC相同。
* [UnboundID LDAP SDK](https://github.com/pingidentity/ldapsdk)：UnboundID LDAP SDK是一个快速、功能强大、用户友好且完全免费的开源Java库，用于与LDAP目录服务器进行通信。
* [Apache DS](https://github.com/apache/directory-server)：DS是一个完全用Java编写的可扩展、可嵌入的目录服务器，已通过Open Group认证，兼容LDAPv3。
* [OpenDJ Community Edition](https://github.com/ForgeRock/opendj-community-edition)：OpenDJ是一个目录服务器，它实现了广泛的轻量级目录访问协议和相关标准，包括完全符合LDAPv3，而且还支持目录服务标记语言。
* [Apache Directory Kerby](https://github.com/apache/directory-kerby)：Directory子项目，是Java Kerberos绑定。它提供了丰富、直观且可互操作的实现、库、KDC和各种设施，根据云、Hadoop和移动等现代环境的需要集成了PKI、OTP和令牌。
* [Apache Directory Studio](https://github.com/apache/directory-studio)：Directory Studio是一个完整的目录工具平台，旨在与任何LDAP服务器一起使用，但它是专门为与ApacheDS一起使用而设计的。
* [Rogue JNDI](https://github.com/veracode-research/rogue-jndi)：用于JNDI注入攻击的恶意LDAP服务器。
* [Spring Data LDAP](https://github.com/spring-projects/spring-data-ldap)：Spring Data LDAP项目旨在为Spring LDAP提供熟悉且一致的存储库抽象。
* [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)：OpenDJ是一种兼容LDAPv3的目录服务，专为Java平台开发，可为组织管理的身份提供高性能、高可用性且安全的存储。
* [LDAP Synchronization Connector](https://github.com/lsc-project/lsc)：LDAP同步连接器从任何数据源(包括数据库、LDAP目录或文件)读取数据，并转换此数据并将其与LDAP目录进行比较。
* [JXplorer](https://github.com/pegacat/jxplorer)：JXplorer是一个跨平台的LDAP浏览器和编辑器。
* [Ldaptive](https://github.com/vt-middleware/ldaptive)：用于与LDAP服务器交互的简单、可扩展的Java API。

## 错误处理

* [Problem](https://github.com/zalando/problem)：Problem是一个实现application/problem+json的Java库，由Zalando开源。
* [EitherNet](https://github.com/slackhq/EitherNet)：用于对Web API响应进行建模的多平台、可插入且密封的API结果类型，由Slack开源。
* [Feign Reflection ErrorDecoder](https://github.com/coveooss/feign-error-decoder)：根据错误码映射异常。
* [JDoctor](https://github.com/melix/jdoctor)：用于设计良好错误消息的Java库。
* [ErrorHandler](https://github.com/Workable/java-error-handler)：适用于Android和Java的错误处理库。
* [Error Handling Spring Boot](https://github.com/wimdeblauwe/error-handling-spring-boot-starter)：可配置的REST API错误处理。
* [Errors Spring Boot](https://github.com/alimate/errors-spring-boot-starter)：Spring Boot的优雅错误处理。
* [Faux Pas](https://github.com/zalando/faux-pas)：一个简化Java函数式编程错误处理的库，由Zalando开源。
* [Backstopper](https://github.com/Nike-Inc/backstopper)：Backstopper是一个与框架无关的API错误处理和模型验证解决方案，适用于Java 7及更高版本，由Nike开源。
* [Either](https://github.com/jbock-java/either)：Java的函数式错误处理库。
* [Catch-Exception](https://github.com/Codearte/catch-exception)：该库在单行代码中捕获异常，并使它们可用于进一步分析。
* [Graceful Response](https://github.com/feiniaojin/graceful-response)：Graceful Response是一个Spring Boot技术栈下的优雅响应处理器，提供一站式统一返回值封装、全局异常处理、自定义异常错误码等功能。
* [Maybe](https://github.com/JoseLion/maybe)：Maybe是一个类似于java.util.Optional的单子包装器，但意图不同。
* [Result](https://github.com/leakyabstractions/result)：该库的目的是为可能成功或失败的操作结果提供类型安全的封装，而不是抛出异常。

## 功能切换

* [Togglz](https://github.com/togglz/togglz)：Togglz是Java功能切换模式的实现。
* [FF4j](https://github.com/ff4j/ff4j)：Java中功能切换模式的实现。
* [FeatureHub](https://github.com/featurehub-io/featurehub)：FeatureHub是一个云原生平台，可帮助软件团队管理其功能，从功能标记到A/B实验以及远程或集中配置。
* [Unleash Java Client](https://github.com/Unleash/unleash-client-java)：适用于Java的Unleash客户端SDK。
* [LaunchDarkly Java SDK](https://github.com/launchdarkly/java-server-sdk)：LaunchDarkly是一个功能管理平台，每天提供数万亿个功能标记，帮助团队更快地构建更好的软件。
* [Piranha](https://github.com/uber/piranha)：用于重构与功能标志API相关的代码的工具，由Uber开源。
* [OpenFeature](https://github.com/open-feature/java-sdk)：OpenFeature是一个开放规范，为功能标记提供与供应商无关、社区驱动的API，可与你最喜欢的功能标记管理工具配合使用。
* [Split Java SDK](https://github.com/splitio/java-client)：该SDK旨在与Split(受控部署平台)配合使用，通过功能标志向用户提供功能，以管理完整的客户体验。

## 表情处理

* [Emoji](https://github.com/delight-im/Emoji)：对Java和Android的表情符号支持。
* [Emoji-Java](https://github.com/vdurmont/emoji-java)：Emoji-Java是一个轻量级的Java库，可帮助你在Java应用程序中使用表情符号。
* [Emoji4j](https://github.com/kcthota/emoji4j)：用于将短代码、HTML实体转换为表情符号的Java库，还支持解析表情符号、代理HTML实体。
* [Java Emoji Converter](https://github.com/binarywang/java-emoji-converter)：Emoji转换工具，便于各种规格客户端生成的Emoji字符串转换成另外一种格式。
* [Emoji](https://github.com/vanniktech/Emoji)：一个Kotlin多平台库，用于向Android应用程序/JVM后端添加表情符号支持。
* [Emoji-Java](https://github.com/coding/emoji-java)：一个轻量级的Java库，可帮助你在Java应用程序中使用表情符号，由Coding开源。
* [JEmoji](https://github.com/felldo/JEmoji)：JEmoji是一个轻量级且快速的Java表情符号库，包含来自unicode联盟的所有表情符号的完整列表。
* [EmojiReader](https://github.com/YvesCheung/EmojiReader)：EmojiReader是一个能在字符串中识别出Emoji的简单工具。

## 行为分析

* [小象用户行为分析平台](https://gitee.com/xiaoxiangopen/analysis)：商用产品开源，包括用户埋点数据采集、用户标签分群和画像、智慧运营、营销等。
* [ClkLog](https://gitee.com/clklog/clklog)：ClkLog是一款记录用户行为分析和画像的免费可商用开源软件，技术人员可快速搭建私有的应用系统。

## ASCII艺术

* [Jansi](https://github.com/fusesource/jansi)：Jansi是一个小型Java库，允许使用ANSI转义序列来格式化控制台输出，甚至可以在Windows上运行。
* [Java ASCII Render](https://github.com/indvd00m/java-ascii-render)：纯Java的ASCII渲染器，没有外部依赖，支持图形基元/元素、图层、上下文、画布。
* [ConsoleUI](https://github.com/awegmann/consoleui)：微型Java库，可在基于ANSI控制台的终端上启用简单的UI元素。
* [Jfiglet](https://github.com/lalyos/jfiglet)：FIGfonts的Java实现，用于创建Ascii横幅。
* [Java-Ascii-Table](https://github.com/nedtwigg/asciitable)：Java中用于ASCII表的简单库。
* [JColor](https://github.com/dialex/JColor)：JColor提供了一种简单的语法，可以在终端上以彩色字体或背景打印消息。
* [Colorized Java](https://github.com/vieitesss/colorize-Java)：在Java控制台中打印彩色文本的小型库。
* [Asciimg](https://github.com/korhner/asciimg)：Asciimg是一个用Java编写的可扩展Ascii艺术生成器。

## URL操作

* [Url Detector](https://github.com/linkedin/URL-Detector)：Url Detector是由LinkedIn安全团队创建的一个库，用于检测和提取长文本中的URL。
* [Slugify](https://github.com/slugify/slugify)：用于生成语音URL的小型工具类库。
* [Unbescape](https://github.com/unbescape/unbescape)：Unbescape是一个Java库，旨在执行功能齐全且高性能的转义和取消转义操作。
* [Java URLBuilder](https://github.com/mikaelhg/urlbuilder)：无运行时依赖的URL构建器。
* [AutoLink Java](https://github.com/robinst/autolink-java)：用于从纯文本中提取URL和电子邮件地址等链接的Java库。
* [Rewrite](https://github.com/ocpsoft/rewrite)：适用于Java EE 6+和Servlet 2.5+应用程序的高度可配置的URL重写工具。
* [Galimatias](https://github.com/smola/galimatias)：Galimatias是一个用Java编写的URL解析和规范化库。
* [JURL](https://github.com/anthonynsimon/jurl)：快速简单的Java URL解析库，支持UTF-8和路径解析。
* [Handy URI Templates](https://github.com/damnhandy/Handy-URI-Templates)：实现RFC6570的Java URI模板处理器。
* [UrlRewriteFilter](https://github.com/paultuckey/urlrewritefilter)：具有类似于Apache的mod_rewrite功能的Java Web过滤器。
* [URLCanon](https://github.com/iipc/urlcanon)：适用于Python和Java的URL规范化库，由国际互联网保护联盟开源。

## WebRTC

* [OpenVidu](https://github.com/OpenVidu/openvidu)：OpenVidu是一个方便在Web或移动应用程序中添加视频通话的平台，它提供了完整的技术堆栈，非常容易集成到你的应用程序中。
* [WebRTC Java](https://github.com/devopvoid/webrtc-java)：基于免费、开源的WebRTC项目的Java原生接口实现。
* [RestComm SIP Servlet](https://github.com/RestComm/sip-servlets)：RestComm SIP Servlet是SIP、IMS和WebRTC应用服务器。
* [NextRTC](https://github.com/mslosarz/nextrtc-signaling-server)：NextRTC是用Java编写的简单WebRTC信令服务器，它提供信号交换和易于集成的API。
* [Kurento](https://github.com/Kurento/kurento)：Kurento Media Server负责媒体传输、处理、加载和记录。
* [BulletJournal](https://github.com/singerdmx/BulletJournal)：BulletJournal是一个开源平台，用于笔记本保存、账本管理、任务/项目管理和协调，擅长个人组织、日程安排、提醒、待办事项列表、笔记共享、多人账本和团队项目协作。
* [OnChat](https://github.com/onch-at/onchat)：一个简单、美观、移动优先的即时消息渐进式Web应用程序。
* [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)：Jitsi Videobridge是一个兼容WebRTC的选择性转发单元(SFU)，即多媒体路由器。

## Expect库

* [ExpectIt](https://github.com/agavrilov76/ExpectIt)：Expect工具的另一个纯Java 1.6+实现。
* [Expect4J](https://github.com/cverges/expect4j)：用Java重写Expect并提供与TclJava解释器的绑定。
* [ExpectJ](https://expectj.sourceforge.net/)：Unix Expect实用程序的Java实现。
* [Expect-Java](https://github.com/ronniedong/Expect-for-Java)：Expect工具的纯Java实现。
* [Expect4Java](https://github.com/iTransformers/expect4java)：Java的Expect语言实现，使用Java 8闭包。

## JavaME

* [MicroEmu](https://code.google.com/archive/p/microemu/)：MicroEmu是Java ME的纯Java实现。
* [J2ME-Loader](https://github.com/nikita36078/J2ME-Loader)：J2ME-Loader是适用于Android的J2ME模拟器，它支持大多数2D和3D游戏(包括Mascot Capsule 3D游戏)。
* [SquirrelJME](https://github.com/SquirrelJME/SquirrelJME)：SquirrelJME是用于嵌入式和物联网设备的Java ME 8虚拟机，它的最终目标是与Java ME标准99.9%兼容。
* [FreeJ2ME](https://github.com/hex007/freej2me)：包含libretro、awt和sdl2前端的免费J2ME模拟器。
* [PluotSorbet](https://github.com/mozilla/pluotsorbet)：PluotSorbet是一个用JavaScript编写的兼容J2ME的虚拟机，由Mozilla开源。

## JavaCard

* [Java Card](https://www.oracle.com/java/technologies/javacard-sdk-downloads.html)：Java Card开发工具包是一套工具，用于设计Java Card技术的实现并根据Java Card API规范开发小应用程序。
* [GlobalPlatformPro](https://github.com/martinpaljak/GlobalPlatformPro)：GlobalPlatformPro允许在兼容的JavaCard智能卡上加载和管理小程序。
* [Ant JavaCard](https://github.com/martinpaljak/ant-javacard)：Ant JavaCard是一个易于使用的Ant任务，用于构建JavaCard Classic小程序(2.1.1至3.1.0)。
* [jCardSim](https://github.com/licel/jcardsim)：jCardSim是Java Card的开源模拟器。
* [vJCRE](https://github.com/martinpaljak/vJCRE)：vJCRE是一个虚拟Java Card运行时环境，允许在标准桌面Java虚拟机内运行针对智能卡平台的Java代码，非常适合快速开发、测试或实验。
* [Gradle JavaCard](https://github.com/fidesmo/gradle-javacard)：该插件允许将编译的class文件转换为转换后的存档格式，这些文件可用于安装在支持SUN/Oracle JavaCard技术的智能卡和SIM卡上。
* [Apdu4j](https://github.com/martinpaljak/apdu4j)：Apdu4j是一些命令行工具和有用的Java类库，用于通过JSR 268处理智能卡和智能卡读卡器。
* [JNASmartCardIO](https://github.com/jnasmartcardio/jnasmartcardio)：javax.smartcardio API的重新实现，它允许你从Java内部与智能卡(在APDU级别)进行通信。
* [Keycard](https://github.com/status-im/status-keycard)：Keycard是在JavaCard 3.0.4+上运行的BIP-32 HD钱包的实现。
* [SmartPGP](https://github.com/github-af/SmartPGP)：SmartPGP是JavaCard中OpenPGP卡3.4规范的免费开源实现。
* [IsoApplet](https://github.com/philipWendland/IsoApplet)：旨在符合ISO 7816标准的Java Card PKI Applet。
* [JCAlgTest](https://github.com/crocs-muni/JCAlgTest)：一种针对具有JavaCard平台的特定智能卡支持的密码算法的自动化测试工具，由马萨里克大学开源。
* [PivApplet](https://github.com/arekinath/PivApplet)：适用于JavaCard 2.2.2和3.0.4+的PIV小程序，具有完整的ECDSA/ECDH支持。
* [JCMathLib](https://github.com/OpenCryptoProject/JCMathLib)：JCMathLib是JavaCard平台的开源库，旨在实现标准JavaCard API中不可用的低级加密计算。
* [JMultiCard](https://github.com/ctt-gob-es/jmulticard)：100% Java智能卡访问抽象层。
* [OpenJavaCard Tools](https://github.com/OpenJavaCard/openjavacard-tools)：该项目是一个用于JavaCard开发和配置的工具包。
* [EMV-Card-Simulator](https://github.com/mrautio/emv-card-simulator)：用于支付终端功能和安全测试/模糊测试的EMV卡的JavaCard实现。

## WebService

* [Apache CXF](https://github.com/apache/cxf)： CXF提供了用于方便地构建和开发Web Service的可靠基础架构。
* [Spring WS](https://github.com/spring-projects/spring-ws)：Spring Web Services是Spring社区的一个产品，专注于创建文档驱动的Web服务。
* [Apache Axis2](https://axis.apache.org/axis2/java/core/index.html)：Apache Axis2是一个Web Services JSON/SOAP/WSDL引擎，是广泛使用的Apache Axis SOAP堆栈的继承者。
* [Apache Axiom](https://ws.apache.org/axiom/)：Apache Axiom库提供了符合XML Infoset的对象模型实现，支持按需构建对象树。
* [Apache Woden](https://ws.apache.org/woden/)：Apache Woden库是作为Apache Web Services项目的子项目开发的，提供用于读取、操作、创建和编写WSDL文档的Java API。
* [Libre-wsdl4j](https://github.com/librewsdl4j/libre-wsdl4j)：Libre-wsdl4j是WSDL4J 1.6.3的一个分支，WSDL4j是WSDL的Java存根生成器。
* [WSDL2REST](https://github.com/jboss-fuse/wsdl2rest)：一种允许从现有JAX-WS服务快速迁移到REST服务的工具。
* [SOA Model](https://github.com/membrane/soa-model)：SOA Model是一个开源工具包和用于WSDL、XML Schema的Java API。
* [jPasskit](https://github.com/drallgood/jpasskit)：jPasskit是Apple PassKit Web Service的Java实现。
* [OpenMRS REST Web Services](https://github.com/openmrs/openmrs-module-webservices.rest)：为OpenMRS提供RESTful Web服务。
* [Apache WSS4J](https://github.com/apache/ws-wss4j)：Apache WSS4J项目提供了Web Services主要安全标准的Java实现，即OASIS Web Services Security(WS-Security)规范。

## 银行账号操作

* [BankCardUtils](https://github.com/nanchen2251/BankCardUtils)：根据银行卡号获取银行卡类型、银行名称和银行编码，自动格式化银行卡号、手机号、身份证号输入的工具类。
* [Java-IBAN](https://github.com/barend/java-iban)：用于处理国际银行帐号(IBAN)的小型Java库。
* [IBAN4j](https://github.com/arturmkrtchyan/iban4j)：用于生成和验证国际银行帐号(IBAN ISO_13616)和企业标识符代码(BIC ISO_9362)的Java库。
* [Bank4j](https://github.com/inisos/bank4j)：生成ISO 20022 XML传输并提供IBAN和BIC验证。

## 用户代理解析

* [User Agent Utils](https://github.com/HaraldWalker/user-agent-utils)：用于处理用户代理字符串的实用程序，可用于实时处理HTTP请求或分析日志文件。
* [HTTPRequest](https://github.com/Konloch/HTTPRequest)：HTTPRequest是一个易于使用的零依赖Java包装器，用于从URL读取Cookie、代理、UserAgent、发布数据等。
* [BrowsCap Java](https://github.com/blueconic/browscap-java)：一个基于BrowsCap CSV源文件的速度极快且内存高效的Java客户端。
* [Yauaa](https://github.com/nielsbasjes/yauaa)：这是一个Java库，可以解析和分析useragent字符串(以及可用的User-Agent客户端提示)提取尽可能多的相关属性。
* [Salvation](https://github.com/shapesecurity/salvation)：这是一个用于处理内容安全策略策略的通用库。

## 语义发布工具

* [JSemVer](https://github.com/zafarkhaja/jsemver)：Java SemVer是语义版本控制规范的Java实现。
* [Semver4j](https://github.com/vdurmont/semver4j)：一个处理版本的轻量级Java库，它遵循语义版本控制规范的规则，提供多种版本控制模式。
* [Semver4j](https://github.com/semver4j/semver4j)：Semver4j是一个轻量级Java库，可帮助你处理版本，它遵循语义版本控制规范的规则。
* [Nyx](https://github.com/mooltiverse/nyx)：Nyx是一个强大、灵活且可配置性极高的语义发布工具。
* [Semantic Versioning](https://github.com/jeluard/semantic-versioning)：Semantic Versioning是一个Java库，允许验证(使用字节码检查)库版本号是否遵循语义版本控制定义的语义版本控制原则。
* [Reckon](https://github.com/ajoberstar/reckon)：用于从Git仓库推断下一个版本的API。

## 数字信号处理

* [JDSP](https://github.com/psambit9791/jdsp)：JDSP是一个信号处理工具库，旨在提供MATLAB或Python的scipy-signal包中可用的功能。
* [IIRJ](https://github.com/berndporr/iirj)：用Java编写的高效IIR滤波器库。
* [Mines JTK](https://github.com/MinesJTK/jtk)：Mines Java Toolkit是一组用于科学和工程的Java包和原生软件库，目前的应用包括数字信号处理、线性代数、优化、网格划分、插值以及2D和3D图形。
* [JRadio](https://github.com/dernasherbrezon/jradio)：用Java编写的软件无线电解码，这个项目的想法是从gnuradio获取块并用Java实现它们。

## 企业集成模式

* [Mule](https://github.com/mulesoft/mule)：Mule是一个轻量级集成平台，可让你在任何地方连接任何东西。
* [Apache Camel](https://github.com/apache/camel)：Apache Camel是一个开源集成框架，使你能够快速轻松地集成使用或生成数据的各种系统。
* [Spring Integration](https://github.com/spring-projects/spring-integration)：Spring Integration提供了Spring编程模型的扩展，以支持众所周知的企业集成模式。
* [WSO2 Enterprise Integrator](https://github.com/wso2/product-ei)：WSO2 Enterprise Integrator是一个开源、快速、云原生且可扩展的集成解决方案，是WSO2集成敏捷平台的核心。
* [Syndesis](https://github.com/syndesisio/syndesis)：Syndesis是一个灵活且可定制的开源平台，以服务形式提供核心集成功能，由Fuse Online开源。
* [Metl](https://github.com/JumpMind/metl)：Metl是一个简单、基于Web的集成平台，允许多种不同类型的数据集成，包括消息传递、基于文件的ETL以及通过Web Service的远程过程调用。
* [Frank!Framework](https://github.com/frankframework/frankframework)：Frank!Framework是一个易于使用的无状态集成框架，允许在不同系统之间修改和交换(事务)消息。
* [RACE](https://github.com/aegisql/conveyor)：RACE是一个可扩展的异步企业集成和创建型Java框架。
* [Ikasan](https://github.com/ikasanEIP/ikasan)：开源企业集成平台。

## 数字资产管理

* [DSpace](https://github.com/DSpace/DSpace)：DSpace是一个专门的数字资产管理系统，它管理和发布由数字文件或“位流”组成的数字条目，并且允许创建、索引和搜索相关的元数据以便定位和存取该条目，由麻省理工学院联合美国惠普公司实验室开源。
* [Cudami](https://github.com/dbmdz/cudami)：Cudami是一个编辑后台，用于管理网站、文章、数字化对象、数字原生对象和实体等文化数字资产，由巴伐利亚国立图书馆开源。
* [DuraCloud](https://github.com/duracloud/duracloud)：DuraCloud是一种开源托管数字保存服务，它将灵活的存储选项与强大的工具相结合，以简化你的保存工作流程。
* [Goobi](https://github.com/intranda/goobi-workflow)：Goobi是一款用于数字化项目的开源软件应用程序，它允许你对可自由定义的生产流程进行建模、管理和监督，并且许多机构每天都使用它来处理创建数字图书馆或博物馆所涉及的所有步骤。
* [Kitodo](https://www.kitodo.org/)：Kitodo是一款开源软件套件，用于对大大小小的图书馆、档案馆、博物馆和文献中心的文化资产进行数字化。
* [MyCoRe](https://github.com/MyCoRe-Org/mycore)：MyCoRe是一个开源仓库软件框架，用于构建学科或机构存储库、数字档案、数字图书馆和科学期刊。
* [MARC4J](https://github.com/marc4j/marc4j)：MARC4J的目标是提供一个易于使用的API，以便在Java中使用MARC和MARCXML。
* [Kitodo.Production](https://github.com/kitodo/kitodo-production)：Kitodo.Production是一种用于大规模数字化的工作流程管理工具，是Kitodo数字图书馆套件的一部分。
* [Fedora](https://github.com/fcrepo/fcrepo)：Fedora是一个强大、模块化、开源存储库系统，用于管理和传播数字内容，它特别适合数字图书馆和档案馆的访问和保存。

## 文档管理系统

* [kkFileView](https://gitee.com/kekingcn/file-online-preview)：基于Spring Boot的通用文件在线预览项目。
* [JVS-Knowledge](https://gitee.com/software-minister/jvs-knowledge-ui)：企业级在线文档，解决企业内部文档编辑、知识沉淀、知识协同等痛点。
* [Zyplayer DOC](https://gitee.com/dromara/zyplayer-doc)：Zyplayer DOC是一款适合团队和个人使用的WIKI文档管理工具，同时还包含数据库文档、API接口文档，由dromara社区开源。
* [APIManager](https://gitee.com/zhoujingjie/apiManager)：小幺鸡文档管理工具，支持富文本、Markdown、HTTP、WebSocket及其在线测试。
* [WCP](https://gitee.com/macplus/WCP)：WCP是一套BS架构的开源知识管理系统、知识库系统，由太原扁舟科技开源。
* [科亿知识库KYKMS](https://gitee.com/kyxxjs/km_community)：基于Elasticsearch的文件管理系统/知识管理系统，由广州科亿信息开源。
* [DocPreview](https://gitee.com/hcwdc/docpreview)：文件在线预览模块，支持多格式转PDF文件，由华创数字云开源。
* [WDA](https://gitee.com/macplus/WDA)：配合OpenOffice实现文档的在线预览、本地文档添加、文档转换为HTML，文档HTML方式预览，由太原扁舟科技开源。
* [WPS View](https://gitee.com/mose-x/wps-view-java)：基于WPS在线编辑、在线预览后台服务。
* [Hackpad](https://github.com/dropbox/hackpad)：Hackpad是一个基于Web的实时Wiki，基于开源EtherPad协作文档编辑器。
* [InfoSphere](https://gitee.com/devlive-community/incubator-infosphere)：InfoSphere是一款面向企业和个人的开源Wiki系统，旨在提供简单而强大的知识管理解决方案，由Devlive社区开源。

## 数据匿名工具

* [ARX](https://github.com/arx-deidentifier/arx)：ARX是一款用于对敏感个人数据进行匿名化的综合开源软件，由德国慕尼黑工业大学开发。
* [DataDefender](https://github.com/armenak/DataDefender)：敏感数据管理：数据发现和匿名化工具包。
* [Anonymouth](https://github.com/psal/anonymouth)：Anonymouth是一个基于Java的应用程序，旨在为用户提供开始对其编写的文档进行匿名化所需的工具和知识，由德雷塞尔大学开源。
* [Anonymouse](https://github.com/CaravanaCloud/Anonymouse)：数据库匿名化工具。
* [Anonimatron](https://github.com/realrolfje/anonimatron)：Anonimatron是一个免费、可扩展、开源数据匿名化工具。
* [Rapiddweller Benerator](https://github.com/rapiddweller/rapiddweller-benerator-ce)：Rapiddweller Benerator是一个功能强大的软件解决方案，用于开发、测试和培训目的的数据生成、混淆和迁移。

## 外部进程执行

* [NuProcess](https://github.com/brettwooldridge/NuProcess)：Java的低开销、非阻塞I/O、外部进程执行实现，它是java.lang.ProcessBuilder和java.lang.Process的替代品。
* [Apache Commons Exec](https://github.com/apache/commons-exec)：Apache Commons Exec是一个从JVM内可靠地执行外部进程的库。
* [Ch.Vorburger.Exec](https://github.com/vorburger/ch.vorburger.exec)：这是一个小型库，允许在后台从Java代码启动外部进程。
* [JProc](https://github.com/fleipold/jproc)：用于运行外部进程的Java库。
* [Overthere](https://github.com/xebialabs/overthere)：Overthere是一个Java库，用于在远程主机上操作文件和执行进程。
* [ZT-EXEC](https://github.com/zeroturnaround/zt-exec)：Java进程执行库。
* [ZT-Process-Killer](https://github.com/zeroturnaround/zt-process-killer)：停止从Java启动的进程或通过PID的系统进程。
* [Winrm4j](https://github.com/cloudsoft/winrm4j)：Winrm4j是一个使Java应用程序能够使用WinRM在远程Windows服务器上执行批处理或PowerShell命令的项目。
* [JNR Process](https://github.com/jnr/jnr-process)：JNR Process库提供了JDK ProcessBuilder API的直接替代品，但它不是线程泵填充程序，而是围绕posix_spawn C API的直接抽象，并提供可选择的in、out和err通道。
* [WinP](https://github.com/jenkinsci/winp)：该项目可以让你更好地控制Windows进程，超越JDK中的可用功能。

## 苹果推送通知

* [Pushy](https://github.com/jchambers/pushy)：Pushy是一个用于发送APN(iOS、macOS和Safari)推送通知的Java库。
* [Java-Apns](https://github.com/notnoop/java-apns)：Java-Apns是Apple推送通知服务(APN)的Java客户端，该库旨在为Apple服务器提供高度可扩展的接口，同时保持简单和模块化。
* [DBay-APNS-Java](https://github.com/RamosLi/dbay-apns-for-java)：APNS的高性能Java客户端。
* [APNS-HTTP2](https://github.com/CleverTap/apns-http2)：用于使用Apple的新HTTP/2 API通过APNS发送通知的Java库。
* [Apns4j](https://github.com/teaey/apns4j)：Apple推送通知服务Java实现。
* [JavaAPNS-JDK16](https://github.com/fernandospr/javapns-jdk16)：适用于Java的Apple推送通知服务提供程序。

## Java服务包装器

* [YAJSW](https://github.com/yajsw/yajsw)：YAJSW是tanuki的Java服务包装器(JSW)的以Java为中心的实现。
* [Java Service Wrapper](https://wrapper.tanukisoftware.org/doc/english/home.html)：Java Service Wrapper是一种经过验证的企业级解决方案，已被数千家公司和开发人员使用，它极大地简化了Java应用程序在各种平台上的部署、启动和监控。
* [Apache Commons Daemon](https://github.com/apache/commons-daemon)：Apache Commons Daemon是一组实用程序和Java支持类，用于将Java应用程序作为服务器进程运行。
* [Launch4j](https://launch4j.sourceforge.net/)：Launch4j是一个跨平台工具，用于将作为jar分发的Java应用程序包装在轻量级Windows本机可执行文件中。
* [JSmooth](https://github.com/BrunoReX/jsmooth)：JSmooth是一个Java可执行包装器，可构建启动Java应用程序的标准Windows可执行二进制文件(.exe)。

## 守护进程

* [Termd](https://github.com/termd/termd)：一个开源终端守护程序库，提供Java终端处理。
* [Akuma](https://github.com/kohsuke/akuma)：这是一个Java库，你可以在应用程序中使用它来支持Unix守护进程。
* [SDNotify](https://github.com/faljse/SDNotify)：SDNotify在Java中实现了systemd通知协议。

## 协议实现

* [Modbus4j](https://github.com/MangoAutomation/modbus4j)：Java编写的Modbus协议的高性能且易于使用的实现。
* [RskJ](https://github.com/rsksmart/rskj)：RSK协议的Java实现。
* [Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP)：Open Charge-Point协议的客户端和服务器库。
* [ICE4j](https://github.com/jitsi/ice4j)：ICE协议的Java实现。
* [SMBJ](https://github.com/hierynomus/smbj)：Java中的服务器消息块(SMB2、SMB3)实现。
* [Sardine](https://github.com/lookfirst/sardine)：一个易于使用的Java webdav客户端。
* [JCIFS](https://github.com/codelibs/jcifs)：JCIFS是一个开源客户端库，以纯Java实现CIFS/SMB网络协议。
* [Cling](https://github.com/4thline/cling)：适用于Java和Android的UPnP/DLNA库。
* [JSIP](https://github.com/usnistgov/jsip)：Java SIP规范参考实现，由美国国家标准技术研究院开源。
* [IRI](https://github.com/iotaledger/iri)：IOTA参考实现。
* [jSMPP](https://github.com/opentelecoms-org/jsmpp)：jSMPP是SMPP协议的Java实现，它提供与消息中心或ESME通信的接口，并且能够处理每秒3000-5000条消息的流量。
* [PircBotX](https://github.com/pircbotx/pircbotx)：PircBotX是一个强大的Java IRC客户端库，适用于机器人和用户客户端。
* [HBCI4Java](https://github.com/hbci4j/hbci4java)：基于Java的FinTS协议实现，支持所有功能（chipTAN、pushTAN、HHD、SEPA、PSD2)。
* [Jscep](https://github.com/jscep/jscep)：Jscep是SCEP协议的Java实现。
* [CBOR-Java](https://github.com/c-rack/cbor-java)：RFC 7049的Java实现。
* [Oxalis](https://github.com/OxalisCommunity/oxalis)：Oxalis是AS4规范的领先开源软件实现。
* [Kwik](https://github.com/ptrd/kwik)：Kwik是QUIC协议Java的实现，Kwik最初仅作为客户端，但自2021年5月起它支持客户端和服务器。
* [JavaOSC](https://github.com/hoijui/JavaOSC)：JavaOSC赋予JVM语言程序以OSC内容格式序列化、解析、发送和接收数据的能力。
* [CalDAV4j](https://github.com/caldav4j/caldav4j)：CalDAV4j是一个实现CalDAV协议的Java库。
* [Open-AirPlay](https://github.com/openairplay/open-airplay)：Apple的AirPlay协议的库集合。
* [Kitteh IRC Client Lib](https://github.com/KittehOrg/KittehIRCClientLib)：KICL是一个功能强大的现代Java IRC库，使用Netty库构建，以最大限度地提高性能和可扩展性。
* [DBus Java](https://github.com/hypfvieh/dbus-java)：该库是D-Bus协议的原生Java实现。
* [JIPP](https://github.com/HPInc/jipp)：IPP的Java兼容实现，由惠普开源。
* [HAP-Java](https://github.com/hap-java/HAP-Java)：HAP-Java是HomeKit附件协议的Java实现。
* [Calimero-Core](https://github.com/calimero-project/calimero-core)：Calimero-Core提供(安全)KNX通信协议、KNX数据点和属性访问以及管理功能。
* [Bacnet4J Wrapper](https://github.com/Code-House/bacnet4j-wrapper)：Bacnet4j是bacnet协议的Java实现，这是Bacnet4j API的简单门面。
* [JSocks](https://github.com/ravn/jsocks)：JSocks是一个完全用Java编写的SOCKS服务器，同时支持SOCKS4和SOCKS5协议。

## BitTorrent

* [Bt](https://github.com/atomashpolskiy/bt)：BitTorrent库和客户端，具有DHT、磁力链接、加密等功能。
* [Ttorrent](https://github.com/mpetazzoni/ttorrent)：BitTorrent协议的Java实现。
* [FrostWire JLibTorrent](https://github.com/frostwire/frostwire-jlibtorrent)：FrostWire为libtorrent提供的swig Java接口。
* [Libtorrent4j](https://github.com/aldenml/libtorrent4j)：Libtorrent的swig Java接口。
* [FrostWire](https://github.com/frostwire/frostwire)：FrostWir是BitTorrent网络的媒体播放器和点对点(P2P)信息共享客户端。

## 编解码

* [Apache Commons Codec](https://github.com/apache/commons-codec)：Apache Commons Codec包含各种格式(例如Base64和十六进制)的简单编码器和解码器。
* [OWASP Java Encoder](https://github.com/OWASP/owasp-java-encoder)：OWASP Java Encoder是一个简单易用的嵌入式高性能编码器类，没有依赖且包袱很少，由OWASP开源。
* [Simple Binary Encoding](https://github.com/real-logic/simple-binary-encoding)：SBE是OSI第6层表示，用于对低延迟金融应用程序的二进制应用程序消息进行编码和解码。
* [Bytes](https://github.com/patrickfav/bytes-java)：Bytes是一个实用程序库，可以轻松地在Java中创建、解析、转换、验证和转换字节数组。
* [Juniversalchardet](https://github.com/albfernandez/juniversalchardet)：Juniversalchardet是universalchardet的Java端口，universalchardet是Mozilla的编码检测器库。
* [PETSCII BBS Builder](https://github.com/sblendorio/petscii-bbs)：一个Java框架，用于构建高度可定制的PETSCII(和ASCII)支持的BBS，可从8位Commodore计算机访问。
* [FastProto](https://github.com/indunet/fastproto)：FastProto是一个功能强大的二进制数据处理工具，旨在简化Java环境中的二进制数据编码和解码。

## Web资源

* [YUI Compressor](https://github.com/yui/yuicompressor)：YUI Compressor是一个JavaScript压缩器，除了删除注释和空格之外，它还使用尽可能小的变量名称来混淆局部变量，该库由Yahoo开源。
* [GWT Bootstrap](https://github.com/gwtbootstrap/gwt-bootstrap)：提供了简单灵活的组件来表示Bootstrap组件、样式和插件，由Twitter开源。
* [CSSEmbed](https://github.com/nzakas/cssembed)：用于在CSS文件中嵌入数据URI的工具。
* [WebJars](https://github.com/webjars/webjars)：打包到JAR中的客户端Web库。
* [Caja](https://github.com/googlearchive/caja)：Caja是一个用于在你的网站中安全嵌入第三方HTML、CSS和JavaScript的工具，由Google开源。
* [Wro4j](https://github.com/wro4j/wro4j)：Wro4j是一个免费的开源Java项目，可以帮助缩短Web应用程序页面加载时间。
* [Closure Stylesheets](https://github.com/google/closure-stylesheets)：一个CSS+转译器，可进行Lints、优化和国际化，由Google开源。
* [CSS Validator](https://github.com/w3c/css-validator)：W3C CSS验证服务。
* [Ph-CSS](https://github.com/phax/ph-css)：Java CSS 2和CSS 3解析器和构建器。
* [Closure Templates](https://github.com/google/closure-templates)：客户端和服务器端模板系统，可帮助您动态构建可重用的HTML和UI元素，由Google开源。
* [Chart.java](https://github.com/mdewilde/chart)：Chart.java可以在Java应用程序中与优秀的Chart.js库集成。
* [ECharts](https://gitee.com/free/ECharts)：这是一个针对ECharts 2.X版本的Java类库，实现了所有ECharts中的JSON结构对应的Java对象，并且可以很方便的创建Option、Series等。
* [LESS Engine](https://github.com/asual/lesscss-engine)：LESS引擎提供对核心LESS功能的基本访问。
* [LESS CSS Compiler](https://github.com/marceloverdijk/lesscss-java)：LESS CSS Compiler是一个将LESS源代码编译为CSS样式表的库。
* [JLessC](https://github.com/i-net-software/jlessc)：JLessC是一个完全用Java编写的Less CSS编译器。

## Web开发库

* [Uap-Java](https://github.com/ua-parser/uap-java)：这是ua-parser的Java实现。
* [BaasBox](https://github.com/baasbox/baasbox)：BaasBox是一个开源项目，旨在为移动和Web应用程序提供后端。
* [Gargl](https://github.com/jodoglevy/gargl)：记录发生的Web请求，并将其转换为任何编程语言的可重用代码。
* [Elemento](https://github.com/hal/elemento)：Elemento可以简化GWT Elemental2的使用。
* [Elemental](https://github.com/google/elemental2)：Elemental2为Java代码提供对所有浏览器API的类型检查访问，由Google开源。
* [Boilerplate](https://github.com/kohlschutter/boilerpipe)：Boilerplate库提供了算法来检测和删除网页主要文本内容周围多余的“混乱”(样板、模板)。
* [Stapler](https://github.com/jenkinsci/stapler)：Stapler是一个将应用程序对象“装订”到URL的库，使编写Web应用程序变得更加容易，由Jenkins组织开源。
* [Nu Html Checker](https://github.com/validator/validator)：Nu Html Checker可帮助你发现HTML、CSS和SVG中的意外错误。
* [Yoga](https://github.com/skyscreamer/yoga)：Yoga扩展了JAX-RS和Spring MVC RESTful服务器，以提供GData和LinkedIn风格的字段选择器。
* [AngularGWT](https://github.com/cromwellian/angulargwt)：这是一个能够用Java为AngularJS编写组件或完整的应用程序的库。
* [HAR Reader](https://github.com/sdstoehr/har-reader)：用于使用Java访问HTTP存档(HAR)的库。
* [WebMVC](https://github.com/beangle/webmvc)：Web模型-视图-控制器库。
* [AutoREST](https://github.com/intendia-oss/autorest)：GWT自动RESTful服务代理生成器。
* [Wicket Stuff](https://github.com/wicketstuff/core)：Wicket Stuff是由Wicket社区创建和维护的Apache Wicket Web框架的开源项目集合。
* [ORCID-Source](https://github.com/ORCID/ORCID-Source)：ORCID Source是一组使用Java构建的Web应用程序和库，使用Spring Web MVC和Postgres数据库提供的持久性。
* [JBossWS-CXF](https://github.com/jbossws/jbossws-cxf)：JBossWS-CXF堆栈，与Apache CXF集成。
* [Domino-UI](https://github.com/DominoKit/domino-ui)：类型安全且功能丰富的UI组件库，供Java开发人员使用流式API，并且不依赖于外部JavaScript。
* [J4TS](https://github.com/j4ts/j4ts)：J4TS基于GWT的JRE模拟库的一个分支，用Java编写，并使用JSweet转译器转译为TypeScript/JavaScript。
* [Mateu](https://github.com/miguelperezcolom/mateu)：Mateu是一个用于以光速从Java创建出色的响应式Web应用程序的框架。
* [PatternFly Java](https://github.com/patternfly-java/patternfly-java)：PatternFly Java是基于GWT/J2CL和Elemento的PatternFly 5的Java实现，由RedHat开源。
* [AngularBeans](https://github.com/bessemHmidi/AngularBeans)：AngularBeans是一个框架，其目的是将Java EE 7(更准确地说是CDI规范)与AngularJS结合使用。
* [React4j](https://github.com/react4j/react4j)：该项目的目标是能够从GWT无缝使用React的组件模型，并利用React开发支持工具(例如React的Devtools)生态系统。
* [DnComponents](https://dncomponents.com/index.html)：客户端Java UI框架，用于使用GWT编译器和Elemental2浏览器API纯粹使用Java语言构建丰富的Web应用程序，无需任何外部JS库。
* [GWT Material](https://github.com/GwtMaterialDesign/gwt-material)：GWT的Google Material Design包装器。
* [Vue GWT](https://github.com/VueGWT/vue-gwt)：Vue GWT使用JsInterop和Elemental2将Vue.js与GWT 2.9集成，它允许你用Java编写Vue组件。
* [GwtBootstrap3](https://github.com/gwtbootstrap3/gwtbootstrap3)：GWTBootstrap3是Twitter Bootstrap的包装器，可帮助你使用Java和GWT在Web上开发响应式、移动优先的HTML、CSS和JS项目。
* [SwellRT](https://github.com/SwellRT/swellrt)：SwellRT是一个开源后端即服务，它提供预构建的功能来加速协作Web应用程序的开发。
* [N2O Framework](https://github.com/i-novus-llc/n2o-framework)：N2O Framework是一个用Java和ReactJS编写的库，允许你创建具有复杂用户界面的Web应用程序，而无需深入了解Web技术和前端框架。
* [ApexCharts Flow](https://github.com/appreciated/apexcharts-flow)：Vaadin平台的ApexCharts.js包装器。
* [JWt](https://github.com/emweb/jwt)：JWt是一个用于开发Web应用程序的Java库，它提供了一种纯Java组件驱动的方法来构建Web应用程序，并使用Ajax或纯HTML进行呈现。
* [Charba](https://github.com/pepstock-org/Charba)：基于Chart.js的J2CL和GWT图表库。
* [Nalu](https://github.com/NaluKit/nalu)：Nalu是一个微型框架，可帮助你轻松创建基于GWT的应用程序。
* [Project Wonder](https://github.com/wocommunity/wonder)：Project Wonder是最大的可重用WebObjects框架、应用程序和扩展的开源集合。
* [LightAdmin](https://github.com/la-team/light-admin)：该项目的主要目标是通过为基于JPA的应用程序引入可插入的完全可操作的数据管理后端来加速应用程序开发。
* [WebforJ](https://github.com/webforj/webforj)：WebforJ是一个强大且灵活的Web框架，可让你使用Java轻松创建现代且引人入胜的用户界面。
* [Fastball](https://github.com/fastball-projects/fastball)：Fastball是一套面向后端、声明式界面开发框架。

## 手机号解析

* [LibPhoneNumber](https://github.com/google/libphonenumber)：Google的通用Java、C++和JavaScript库，用于解析、格式化和验证国际电话号码。
* [PhoneNumber-Geo](https://github.com/fengjiajie/phone-number-geo)：手机号码归属地本地解析Java实现。
* [PhoneNumber-Geo](https://github.com/EeeMt/phone-number-geo)：根据手机号确定手机号运营商即归属地，支持包括虚拟运营商的中国大陆手机号查询。
* [PhoneNumber](https://github.com/xdtianyu/PhoneNumber)：一个获取号码归属地和其他信息(诈骗、骚扰等)的开源库。
* [PhoneNumber Normalizer](https://github.com/telekom/phonenumber-normalizer)：使用PhoneNumber Normalizer库，你可以将电话号码标准化为E164格式和国家格式，同时考虑到德国号码计划的特定复杂性，由德国电信开源。

## 表达式引擎

* [Aviator](https://code.google.com/archive/p/aviator/)：Aviator是一个高性能、轻量级的基于Java实现的表达式引擎，它动态地将String类型的表达式编译成Java字节码并交给JVM执行，Google开源。
* [AviatorScript](https://github.com/killme2008/aviatorscript)：AviatorScript是一门高性能、轻量级寄宿于JVM(包括Android平台)之上的脚本语言。
* [JSEL](https://code.google.com/archive/p/lite/wikis/JSEL.wiki)：JSEL是一个兼容JavaScript运算规则的简单表达式解释引擎。
* [IK Expression](https://code.google.com/archive/p/ik-expression/)：IK Expression是一个开源、可扩展、基于Java语言开发的一个超轻量级的公式化语言解析执行工具包。
* [FastEL](https://github.com/dbcxy/fast-el)：轻量级的高效表达式计算引擎。
* [QLExpress](https://github.com/alibaba/QLExpress)：QLExpress是一种强大的、轻量级的、动态的Java平台语言，旨在提高开发人员在不同业务场景中的生产力，阿里开源。
* [MVEL](https://github.com/mvel/mvel)：MVEL是一种混合动态/静态类型、可嵌入的表达式语言和Java平台运行时。
* [OGNL](https://github.com/orphan-oss/ognl)：OGNL代表对象图导航语言，它是一种用于获取和设置Java对象属性的表达式语言。
* [Formula](https://github.com/salesforce/formula-engine)：可重用公式引擎的实现，具有JavaScript和SQL生成以及Salesforce批准的语法。
* [SpEL](https://github.com/spring-projects/spring-framework)：SpEL是一种功能强大的表达式语言，支持在运行时查询和操作对象图。
* [Janino](https://github.com/janino-compiler/janino)：Janino是一个超小、超快的Java编译器。
* [JUEL](https://github.com/beckchr/juel)：JUEL是统一表达语言(EL)的实现，指定为JSP 2.1标准(JSR-245)的一部分，已在JEE5中引入。
* [Apache Commons JEXL](https://github.com/apache/commons-jexl)：Apache Commons JEXL库是Java共生表达式语言的实现。
* [CEL Java](https://github.com/google/cel-java)：CEL是一种非图灵完备语言，旨在简单、快速、安全和可移植，由Google开发。
* [Java PetitParser](https://github.com/petitparser/java-petitparser)：PetitParser结合了无扫描器解析、解析器组合器、解析表达式语法(PEG)和Packrat解析器的思想，将语法和解析器建模为可以动态重新配置的对象。
* [Grammaticus](https://github.com/salesforce/grammaticus)：Grammaticus是一个语法引擎，允许用户重命名名词，同时保持内容的语法正确，由Salesforce开源。
* [CEL-Java](https://github.com/projectnessie/cel-java)：通用表达式语言的Java实现。
* [Eclipse Expressly](https://github.com/eclipse-ee4j/expressly)：Eclipse Expressly实现了Jakarta Expression Language，这是一种用于Java应用程序的表达式语言。
* [JFireEL](https://gitee.com/eric_ds/jfireEL)：快速的EL表达式解析器，支持丰富的EL表达式。
* [Crunch](https://github.com/boxbeam/Crunch)：快速的Java表达式编译器/评估器。

## 数学表达式

* [Exp4j](https://github.com/fasseg/exp4j)：Exp4j是用于Java编程语言的小型数学表达式计算器。
* [Keval](https://github.com/notKamui/Keval)：用于数学表达式字符串求值的Kotlin迷你库。
* [ExprK](https://github.com/Keelar/ExprK)：ExprK是一个用于Kotlin和Java的简单数学表达式评估器。
* [EvalEx](https://github.com/ezylang/EvalEx)：EvalEx是一个方便的Java表达式计算器，它允许评估简单的数学和布尔表达式。
* [Javaluator](https://github.com/fathzer/javaluator)：Javaluator是一个简单、功能强大的Java中缀表达式计算器。
* [Parsington](https://github.com/scijava/parsington)：Parsington是一个中缀到后缀和中缀到语法树表达式解析器，用于用Java编写的数学表达式。
* [MathParser](https://github.com/mariuszgromada/MathParser.org-mXparser)：MathParser是一个超级简单、丰富且高度灵活的数学表达式解析器库，适用于Java、Android、.NET、TypeScript和JavaScript。
* [Parsii](https://github.com/scireum/parsii)：用Java编写的数学表达式的超级快速且简单的计算器。
* [ParserNG](https://github.com/gbenroscience/ParserNG)：ParserNG是一个功能强大的开源数学工具，可以解析和评估代数表达式。

## SQL解析器

* [SQLSolver](https://github.com/SJTU-IPADS/SQLSolver)：SQLSolver是一个查询等效性验证器，由上海交通大学、耶鲁大学、纽约大学和普林斯顿大学的研究人员开发。
* [JSqlParser](https://github.com/JSQLParser/JSqlParser)：JSqlParser是一个与RDBMS无关的SQL语句解析器，它将SQL语句转换为可遍历的Java类层次结构。

## 对象图导航

* [Apache Commons OGNL](https://github.com/apache/commons-ognl)：OGNL代表对象图导航语言；它是一种表达式语言，用于获取和设置Java对象的属性，以及其他附加功能，例如列表投影和选择以及Lambda表达式。
* [OGNL](https://github.com/orphan-oss/ognl)：对象图导航库。
* [OGNL Expression](https://mvnrepository.com/artifact/marmalade/marmalade-el-ognl)：OGNL表达式库。

## 超媒体类型

* [Spring HATEOAS](https://github.com/spring-projects/spring-hateoas)：该项目提供了一些API来简化创建在使用Spring时遵循HATEOAS原则的REST表示。
* [Hate](https://github.com/blackdoor/hate)：根据HAL规范构建超媒体友好的对象。
* [Siren4J](https://github.com/eserating-chwy/siren4j)：Siren规范库。
* [Spring HATEOAS JSON API](https://github.com/toedter/spring-hateoas-jsonapi)：这是与Spring HATEOAS集成的媒体类型application/vnd.api+json(JSON:API)的实现。
* [Edison HAL](https://github.com/otto-de/edison-hal)：使用Jackson生成和使用REST资源的application/hal+json表示的库。
* [REST-Shell](https://github.com/spring-attic/rest-shell)：用于与Spring HATEOAS兼容的REST资源交互的命令行shell。

## 术语服务器

* [Snow Owl](https://github.com/b2ihealthcare/snow-owl)：Snow Owl是一款高度可扩展的开源术语服务器，具有修订控制功能和协作创作平台功能。
* [Snowstorm](https://github.com/IHTSDO/snowstorm)：Snowstorm是一个开源术语服务器，特别支持SNOMED CT。

## 解析&转换

* [J2ObjC](https://github.com/google/j2objc)：J2ObjC是Google的开源命令行工具，可将Java源代码转换为适用于iOS(iPhone/iPad)平台的Objective-C。
* [JSweet](https://github.com/cincheo/jsweet)：JSweet利用TypeScript通过JavaScript库和框架用Java编写丰富且响应迅速的Web应用程序。
* [Roaster](https://github.com/forge/roaster)：Roaster是一个可以轻松解析和格式化Java源文件的库。
* [Apache Commons Convert](https://commons.apache.org/sandbox/commons-convert)：Convert是一个专用于将一种类型的对象转换为另一种类型的库。
* [Smail2Java](https://github.com/demitsuri/smali2java)：Java转换工具。
* [QDox](https://github.com/paul-hammant/qdox)：QDox是一个高速、占用空间小的解析器，用于完全提取类/接口/方法定义(包括注解、参数、参数名称)。
* [TypeScript-Generator](https://github.com/vojtechhabarta/typescript-generator)：TypeScript-Generator是一个用于从Java JSON类生成TypeScript定义文件(.d.ts)的工具。
* [JRecordBind](https://github.com/ffissore/jrecordbind)：小型且超快的定长文件读取器/解析器。
* [Evo Inflector](https://github.com/atteo/evo-inflector)：单复数英语单词转换器。
* [AnyAscii](https://github.com/anyascii/anyascii)：AnyAscii为几乎所有Unicode字符提供纯ASCII替换字符串。
* [JUnidecode](https://github.com/gcardone/junidecode)：Unicode转换到ASCII的Java库。
* [J2C](https://github.com/arnetheduck/j2c)：J2C可以将Java代码转换为可编译的C++(11)代码。
* [LibNumberText](https://github.com/Numbertext/libnumbertext)：C++、Java、JavaScript和Python中的数字到数字名称和金钱文本转换库。

## Minecraft

* [Paper](https://github.com/PaperMC/Paper)：使用最广泛的高性能Minecraft服务器，旨在修复游戏玩法和机制的不一致问题。
* [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge)：一个免费的开源模组API，所有常见模组都在使用。
* [HMCL](https://github.com/huanghongxun/HMCL)：一款多功能、跨平台、流行的Minecraft桌面。
* [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)：基于Boardwalk的Minecraft：适用于Android和iOS的Java版启动器。
* [Sodium](https://github.com/CaffeineMC/sodium-fabric)：旨在提高帧速率并减少微卡顿的Fabric模组。
* [Geyser](https://github.com/GeyserMC/Geyser)：允许使用Minecraft基岩版连接到Minecraft Java版服务器的桥接器。
* [Brigadier](https://github.com/Mojang/brigadier)：一个命令解析器和调度器，专为Minecraft Java版设计和开发。
* [WorldEdit](https://github.com/EngineHub/WorldEdit)：Minecraft地图编辑器和模组。
* [Iris](https://github.com/IrisShaders/Iris)：Minecraft的现代着色器模组，旨在与现有的OptiFine着色器包兼容。
* [MCA Selector](https://github.com/Querz/mcaselector)：一种从Minecraft世界中选择块进行删除或导出的工具。
* [Bukkit](https://github.com/Bukkit/Bukkit)：Minecraft服务器API。
* [Create](https://github.com/Creators-of-Create/Create)：一个为建筑、装饰和美学自动化提供各种工具和模块的模组。
* [Amidst](https://github.com/toolbox4minecraft/amidst)：用于显示Minecraft世界概览的工具，而无需实际创建它。
* [Minestom](https://github.com/Minestom/Minestom)：1.19.3轻量级Minecraft服务器。
* [Dynmap](https://github.com/webbukkit/dynmap)：一组Minecraft模组，为各种Minecraft服务器实现提供基于Web的实时地图系统。
* [Fabric](https://github.com/FabricMC/fabric)：Fabric mods的基本钩子和互操作机制的库。
* [Glowstone](https://github.com/GlowstoneMC/Glowstone)：一个快速、可定制且兼容的Minecraft Java版开源服务器。
* [CatServer](https://github.com/Luohuayu/CatServer)：高性能和高兼容性的1.12.2/1.16.5/1.18.2版本Forge + Bukkit + Spigot服务端。
* [LuckPerms](https://github.com/LuckPerms/LuckPerms)：Minecraft服务器的权限插件。
* [Lithium](https://github.com/CaffeineMC/lithium-fabric)：免费开源的Minecraft模组，可优化游戏的许多领域，以提供更好的整体性能。
* [Essentials](https://github.com/EssentialsX/Essentials)：用于Spigot和Paper的现代Essentials套件。
* [Meteor](https://github.com/MeteorDevelopment/meteor-client)：基础Minecraft实用程序模组。
* [BungeeCord](https://github.com/SpigotMC/BungeeCord)：一个复杂的代理和API，主要设计用于在多个Minecraft服务器之间传送玩家。
* [BlueMap](https://github.com/BlueMap-Minecraft/BlueMap)：一款Minecraft地图工具，可创建Minecraft世界的3D模型并将其显示在Web查看器中。
* [Velocity](https://github.com/PaperMC/Velocity)：下一代Minecraft服务器代理。
* [FarPlaneTwo](https://github.com/PorkStudios/FarPlaneTwo)：Minecraft中的细节层次渲染器，允许渲染数百万个块的距离。
* [Applied Energistics 2](https://github.com/AppliedEnergistics/Applied-Energistics-2)：一个关于物质、能量并利用它们征服世界的模组。
* [Botania](https://github.com/VazkiiMods/Botania)：以自然和植物生命的魔力为主题的Minecraft技术模组。
* [SpongeAPI](https://github.com/SpongePowered/SpongeAPI)：成熟的Minecraft插件API，不包括实现。
* [Nukkit](https://github.com/CloudburstMC/Nukkit)：Minecraft基岩版的核动力服务器软件。
* [SpongeForge](https://github.com/SpongePowered/SpongeForge)：一个实现SpongeAPI的Forge模组。
* [Adventure](https://github.com/KyoriPowered/adventure)：Minecraft Java版的服务器端用户界面库。
* [BuildCraft](https://github.com/BuildCraft/BuildCraft)：Minecraft模组。
* [MultiPaper](https://github.com/MultiPaper/MultiPaper)：多服务器、单一世界papermc实现。

## Maven插件

* [Frontend Maven Plugin](https://github.com/eirslett/frontend-maven-plugin)：该插件会在你的项目本地下载/安装Node和NPM，运行npm install，然后运行Bower、Grunt、Gulp、Jspm、Karma或Webpack的任意组合。
* [Android Maven Plugin](https://github.com/simpligility/android-maven-plugin)：用于Android应用程序开发等的Maven插件。
* [JavaFX Maven Plugin](https://github.com/javafx-maven-plugin/javafx-maven-plugin)：JavaFX Maven插件提供了一种从Maven内组装JavaFX应用程序(8+)分发包的方法。
* [SonarQube Maven Plugin](https://github.com/SonarSource/sonar-scanner-maven)：用于Maven的SonarQube扫描器。
* [Nexus Maven Plugin](https://github.com/sonatype/nexus-maven-plugins)：支持Nexus Suite的Apache Maven插件集合。
* [Scala Maven Plugin](https://github.com/davidB/scala-maven-plugin)：Scala Maven插件用于在Maven中编译/测试/运行/记录Scala代码。
* [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin)：能够在构建过程中运行JMeter测试的Maven插件。
* [Polyglot Maven](https://github.com/takari/polyglot-maven)：Polyglot Maven是Maven 3.3.1+的一组扩展，允许使用XML以外的方言编写POM模型。
* [JAXB Tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [Aadarchi](https://github.com/Riduidel/aadarchi)：Aadarchi是一个Maven原型，可轻松生成项目，允许使用C4、敏捷架构、Asciidoc和PlantUML的组合进行架构描述。
* [DepClean](https://github.com/ASSERT-KTH/depclean)：DepClean自动检测并删除Maven项目中未使用的依赖，由瑞士皇家理工学院开源。
* [Maven Javadoc Plugin](https://github.com/apache/maven-javadoc-plugin)：Javadoc插件使用Javadoc工具为指定项目生成javadoc。
* [GitFlow Helper Maven Plugin](https://github.com/egineering-llc/gitflow-helper-maven-plugin)：一个构建扩展和插件，可帮助Maven与gitflow项目、CI服务器和本地开发完美配合。
* [Modernizer Maven Plugin](https://github.com/gaul/modernizer-maven-plugin)：Modernizer Maven插件检测现代Java版本取代的遗留API的使用。
* [JavaFX Maven Plugin](https://github.com/openjfx/javafx-maven-plugin)：用于运行JavaFX 11+应用程序的Maven插件。
* [Versions Maven Plugin](https://github.com/mojohaus/versions)：当你想要管理项目POM中的工件版本时，可以使用Versions插件。
* [Asciidoctor Maven Plugin](https://github.com/asciidoctor/asciidoctor-maven-plugin)：通过JRuby使用Asciidoctor来处理项目内的AsciiDoc源文件的Maven插件。
* [Fmt Maven Plugin](https://github.com/spotify/fmt-maven-plugin)：格式化Java代码的固定Maven插件，由Spotify开源。
* [OS Maven Plugin](https://github.com/trustin/os-maven-plugin)：用于设置从${os.name}和${os.arch}属性检测到的各种有用属性的Maven插件。
* [Native Build Tools](https://github.com/graalvm/native-build-tools)：包含用于与GraalVM Native Image互操作的构建工具插件的仓库。
* [Azure Maven Plugin](https://github.com/microsoft/azure-maven-plugins)：该仓库包含Microsoft Azure服务的所有Maven插件。
* [Protoc-Jar Maven Plugin](https://github.com/os72/protoc-jar-maven-plugin)：简单的Maven插件，使用protoc-jar嵌入式protoc编译器编译.proto文件，提供跨主要平台的可移植性。
* [License Maven Plugin](https://github.com/mathieucarbou/license-maven-plugin)：用于管理源文件中许可证标头的Maven插件。
* [Appbundle Maven Plugin](https://github.com/federkasten/appbundle-maven-plugin)：可为OS X创建包含所有项目依赖项和必要元数据的应用程序包的Maven插件。
* [Duplicate-Finder Maven Plugin](https://github.com/basepom/duplicate-finder-maven-plugin)：用于查找并标记Java类路径上重复的类和资源的Maven插件。
* [GluonFX Maven Plugin](https://github.com/gluonhq/gluonfx-maven-plugin)：简化为Java/JavaFX Maven项目创建本机镜像的插件。
* [Tomcat Maven Plugin](https://github.com/apache/tomcat-maven-plugin)：在构建期间启动Tomcat服务器的Maven插件。
* [Exec Maven Plugin](https://github.com/mojohaus/exec-maven-plugin)：该插件提供了2个目标来帮助执行系统和Java程序。
* [GWT Maven Plugin](https://github.com/tbroyer/gwt-maven-plugin)：该插件旨在通过提供两个特定的包gwt-lib和gwt-app，使使用Maven构建GWT项目变得更容易。
* [JShell Maven Plugin](https://github.com/johnpoth/jshell-maven-plugin)：Java Shell工具(JShell)的Maven插件。
* [Cucable Maven Plugin](https://github.com/trivago/cucable-plugin)：简化并行运行Cucumber场景的Maven插件。
* [Web3j Maven Plugin](https://github.com/web3j/web3j-maven-plugin)：Web3j Maven插件用于根据Solidity合约文件创建Java类。
* [AspectJ Maven Plugin](https://github.com/mojohaus/aspectj-maven-plugin)：该插件使用AspectJ编译器ajc将AspectJ切面编织到类中。
* [Google App Engine Maven plugin](https://github.com/GoogleCloudPlatform/app-maven-plugin)：该Maven插件提供了构建和部署Google App Engine应用程序的目标。
* [Mosec Maven Plugin](https://github.com/momosecurity/mosec-maven-plugin)：用于检测Maven项目的第三方依赖组件是否存在安全漏洞。
* [Rewrite Maven Plugin](https://github.com/openrewrite/rewrite-maven-plugin)：OpenRewrite的Maven插件，将Rewrite检查和修复任务应用为构建任务。
* [Allure Maven Plugin](https://github.com/allure-framework/allure-maven)：该插件在Maven构建过程中通过现有XML文件生成Allure报告。
* [Heroku Maven Plugin](https://github.com/heroku/heroku-maven-plugin)：用于将Java应用程序直接部署到Heroku，而无需推送到Git仓库。
* [Cargo Maven Plugin](https://github.com/codehaus-cargo/cargo)：Cargo是一个瘦Java包装器，允许你以标准方式操作各种类型的应用程序容器(J2EE、Java EE、Jakarta EE等)。
* [Maven IT Extension](https://github.com/khmarbaise/maven-it-extension)：实验性JUnit Jupiter扩展，用于为Maven插件/Maven扩展/Maven核心编写集成测试。
* [Maven PlantUML Plugin](https://github.com/arnaudroques/maven-plantuml-plugin)：一个使用PlantUML语法生成UML图的Maven插件。
* [Helm Maven Plugin](https://github.com/kokuwaio/helm-maven-plugin)：这是一个用于测试、打包和上传HELM图表的Maven插件。
* [Maven Download Plugin](https://github.com/maven-download-plugin/maven-download-plugin)：该插件可帮助Maven用户在Maven构建过程中下载不同协议上的不同文件。
* [Yeoman Maven Plugin](https://github.com/trecloux/yeoman-maven-plugin)：使用此插件可以将yeoman构建集成到你的Maven构建中。
* [Maven Dependency Plugin](https://github.com/apache/maven-dependency-plugin)：Dependency插件提供了操作工件的能力，它可以将工件从本地或远程仓库复制和/或解压到指定位置。
* [Spring MVC-RAML Plugin](https://github.com/phoenixnap/springmvc-raml-plugin)：Spring MVC-RAML项目旨在为使用Spring MVC框架的项目强制实施契约优先方法。
* [Git Build Hook Maven Plugin](https://github.com/rudikershaw/git-build-hook)：一个用于添加配置、安装git hooks以及初始化本地项目的git仓库的Maven插件。
* [Libsass Maven Plugin](https://github.com/warmuuh/libsass-maven-plugin)：Libsass Maven插件使用libsass编译sass文件。
* [Lombok Maven Plugin](https://github.com/awhitford/lombok.maven)：Lombok项目的Maven插件。
* [Prettier Maven Plugin](https://github.com/HubSpot/prettier-maven-plugin)：用于在构建期间运行prettier-java的Maven插件。
* [ArchUnit Maven plugin](https://github.com/societe-generale/arch-unit-maven-plugin)：ArchUnit Maven插件是ArchUnit的简单Maven包装器，使你能够轻松确保所有项目都遵循相同的架构规则。
* [Maven Release Plugin](https://github.com/apache/maven-release)：Maven Release提供了使用Maven发布项目的工具。
* [Build Helper Maven Plugin](https://github.com/mojohaus/build-helper-maven-plugin)：Build Helper包含多个目标来支持完成不同类型的任务，例如解析版本信息、向Maven项目添加补充源/测试文件夹或附加补充工件。
* [Rust Maven Plugin](https://github.com/questdb/rust-maven-plugin)：在Java Maven项目中构建Rust Cargo crates。
* [Gatling AWS Maven Plugin](https://github.com/electronicarts/gatling-aws-maven-plugin)：Gatling AWS Maven插件消除了扩展Gatling测试的痛苦，它在可配置数量的EC2实例上运行负载测试，聚合单个负载测试报告，并将结果上传到S3。
* [Maven Surefire JUnit5 TreeView Extension](https://github.com/fabriciorby/maven-surefire-junit5-tree-reporter)：Maven Surefire JUnit5插件的树视图控制台报告。
* [License Maven Plugin](https://github.com/mojohaus/license-maven-plugin)：用于从项目依赖项下载和收集许可证文件的Maven插件。
* [Jaxb2 Maven Plugin](https://github.com/mojohaus/jaxb2-maven-plugin)：从XML模式(以及可选的绑定文件)生成Java类以及从带注解的Java类创建XML模式的Maven插件。
* [Elasticsearch Maven Plugin](https://github.com/alexcojocaru/elasticsearch-maven-plugin)：一个用于在构建的集成测试阶段运行Elasticsearch版本5+实例的Maven插件。
* [Mojo Executor](https://github.com/mojo-executor/mojo-executor)：Mojo Executor提供了一种在Maven插件中执行其他Mojo(插件)的方法，允许你轻松创建由其他插件组成的Maven插件。
* [Maven Compiler Plugin](https://github.com/apache/maven-compiler-plugin)：Compiler插件用于编译Java源代码。
* [VisualEE](https://github.com/Thomas-S-B/visualee)：一个用于可视化Java EE项目的Maven插件。
* [Maven Golang](https://github.com/raydac/mvn-golang)：用于自动化GoSDK加载和构建项目的Maven插件。
* [Go Offline Maven Plugin](https://github.com/qaware/go-offline-maven-plugin)：用于下载Maven构建所需的所有依赖项和插件的Maven插件，这样构建之后可以在没有互联网连接的情况下运行。
* [Maven Shade Plugin](https://github.com/apache/maven-shade-plugin)：该插件提供了将工件打包在uber-jar中的功能，包括其依赖项，并遮蔽(即重命名)某些依赖项的包。
* [Maven Enforcer Plugin](https://github.com/apache/maven-enforcer)：Enforcer插件提供了控制某些环境约束的目标，例如Maven版本、JDK版本和操作系统系列，以及更多内置规则和用户创建的规则。
* [JasperReports Maven Plugin](https://github.com/alexnederlof/Jasper-report-maven-plugin)：这个Maven插件会将JasperReport报告文件编译到target目录。
* [Maven Archetype Plugin](https://github.com/apache/maven-archetype)：Archetype是一个Maven项目模板工具包。
* [Takari Maven Plugin](https://github.com/takari/takari-maven-plugin)：用于安装Maven Wrapper的Maven插件。
* [Really Executable Jars Maven Plugin](https://github.com/brianm/really-executable-jars-maven-plugin)：用于制作chmod +x jar文件的Maven插件。
* [Multi Module Maven Release Plugin](https://github.com/danielflower/multi-module-maven-release-plugin)：一个快速的Maven发布插件，不添加额外的提交，并且可以很好地与单个或多个模块配合使用。
* [Liberty Maven Plugin](https://github.com/OpenLiberty/ci.maven)：Liberty Maven插件支持Liberty运行时和服务器的安装和操作控制。
* [NAR Maven Plugin](https://github.com/maven-nar/nar-maven-plugin)：这个插件允许你在许多不同的架构上以及使用许多不同的编译器/链接器编译本机代码生成的输出包含在本机存档文件中。
* [JSass](https://github.com/bit3/jsass)：jsass是一个模块化的Java sass编译器。
* [P2 Maven Plugin](https://github.com/reficio/p2-maven-plugin)：这是一个易于使用的Maven插件，负责Eclipse RCP环境中第三方依赖管理的自动化。
* [Minify Maven Plugin](https://github.com/samaxes/minify-maven-plugin)：Minify Maven插件组合并最小化你的CSS和JavaScript文件，以加快页面加载速度。
* [Grunt Maven Plugin](https://github.com/allegro/grunt-maven-plugin)：Grunt Maven插件允许你将Grunt任务集成到Maven构建过程中。
* [Formatter Maven Plugin](https://github.com/revelc/formatter-maven-plugin)：该项目提供了一种在Maven构建期间自动重新格式化Maven项目或验证其格式的机制。
* [CycloneDX Maven Plugin](https://github.com/CycloneDX/cyclonedx-maven-plugin)：CycloneDX Maven插件生成CycloneDX软件BOM，其中包含项目的所有直接和传递依赖项的聚合。
* [Clojure Maven Plugin](https://github.com/talios/clojure-maven-plugin)：该插件旨在使在混合语言企业项目中工作时尽可能轻松地使用Clojure。
* [Confluence Publisher](https://github.com/confluence-publisher/confluence-publisher)：Confluence Publisher允许用AsciiDoc编写并直接使用要发布到Confluence空间的文档代码库进行版本控制的文档。
* [Flatten Maven Plugin](https://github.com/mojohaus/flatten-maven-plugin)：该插件会生成pom.xml的扁平化版本，并让Maven来安装和部署该版本，而不是原始的pom.xml。
* [Git Code Format Maven Plugin](https://github.com/Cosium/git-code-format-maven-plugin)：一个可自动将代码格式化程序部署为预提交git hook的Maven插件。
* [BuildNumber Maven Plugin](https://github.com/mojohaus/buildnumber-maven-plugin)：这个Mojo旨在为你每次构建项目时获取唯一的构建号。
* [GitHub Maven Plugins](https://github.com/github/maven-plugins)：与GitHub集成的Maven插件集合，这些插件通过GitHub Java库构建在API v3之上。
* [ProGuard Maven Plugin](https://github.com/wvengen/proguard-maven-plugin)：ProGuard Maven插件支持模块化ProGuard包。
* [Git-Flow Maven Plugin](https://github.com/aleksandr-m/gitflow-maven-plugin)：Git-Flow Maven插件支持各种Git工作流，包括GitFlow和GitHub Flow，该插件从命令行运行Git和Maven命令。
* [Java Debian Package](https://github.com/tcurdt/jdeb)：该库提供了一个Ant任务和一个Maven插件，可以以真正跨平台的方式从Java构建创建Debian软件包。
* [Launch4j Maven Plugin](https://github.com/orphan-oss/launch4j-maven-plugin)：一个包装Launch4j的Maven插件。
* [Coveralls Maven Plugin](https://github.com/trautonen/coveralls-maven-plugin)：用于向Coveralls Web服务提交Java代码覆盖率报告的Maven插件。
* [Sortpom Maven Plugin](https://github.com/Ekryd/sortpom)：通过格式化XML并按预定义的顺序组织XML部分来帮助用户对pom.xml进行排序的Maven插件。
* [Jasmine Maven Plugin](https://github.com/searls/jasmine-maven-plugin)：用于执行Jasmine Specs的Maven插件。
* [GMavenPlus](https://github.com/groovy/GMavenPlus)：GMavenPlus是GMaven的重写版本，GMaven是一个Maven插件，允许你将Groovy集成到Maven项目中。
* [Mvnpm](https://github.com/mvnpm/mvnpm)：Mvnpm允许直接从Maven或Gradle项目使用NPM Registry包作为依赖。

## Gradle插件

* [Gradle Retrolambda](https://github.com/evant/gradle-retrolambda)：用于在Java 6、7和Android中获取Java Lambda支持。
* [Dexcount Gradle Plugin](https://github.com/KeepSafe/dexcount-gradle-plugin)：用于报告每次构建时APK中方法引用的数量。
* [Hunter](https://github.com/Leaking/Hunter)：一个快速、增量、并发的框架，用于开发Android项目的编译插件来操作字节码。
* [Gradle Shadow](https://github.com/johnrengelman/shadow)：Gradle插件，用于创建fat/uber JAR，支持包重定位。
* [Gradle Docker Plugin](https://github.com/bmuschko/gradle-docker-plugin)：用于管理Docker镜像和容器的Gradle插件。
* [Dependency Management Plugin](https://github.com/spring-gradle-plugins/dependency-management-plugin)：提供类似Maven的依赖管理功能。
* [Gradle Test Logger Plugin](https://github.com/radarsh/gradle-test-logger-plugin)：用于在运行测试时在控制台上打印漂亮日志的Gradle插件。
* [JavaFX Gradle Plugin](https://github.com/FibreFoX/javafx-gradle-plugin)：用于JavaFX的Gradle插件。
* [Google Play Gradle Plugin](https://github.com/google/play-services-plugins)：帮助使用Google Play服务SDK的插件。
* [Clean Architecture Gradle Plugin](https://github.com/bancolombia/scaffold-clean-architecture)：用于按照最佳实践创建基于Clean Architecture的Java和Kotlin应用程序的Gradle插件，由哥伦比亚银行开源。
* [WSDL2Java Gradle Plugin](https://github.com/nilsmagnus/wsdl2java)：用于从WSDL文件生成Java源代码的Gradle插件。
* [Git-Version Gradle Plugin](https://github.com/palantir/gradle-git-version)：使用git describe生成版本字符串的Gradle插件。
* [Gradle Avro Plugin](https://github.com/davidmc24/gradle-avro-plugin)：允许轻松执行Avro的Java代码生成的Gradle插件。
* [Gradle Baseline Plugin](https://github.com/palantir/gradle-baseline)：为开发人员配置默认的代码质量工具。
* [Gradle AWS Plugin](https://github.com/classmethod/gradle-aws-plugin)：用于管理Amazon Web Services的Gradle插件。
* [Gradle Modules Plugin](https://github.com/java9-modularity/gradle-modules-plugin)：这个Gradle插件有助于使用Java 9平台模块系统。
* [Android SVG Drawable](https://github.com/avianey/androidsvgdrawable-plugin)：可在Android项目构建时从SVG文件生成合格的、特定于密度的PNG绘图。
* [OkBuck Gradle Plugin](https://github.com/uber/okbuck)：OkBuck是一个Gradle插件，允许开发人员在Gradle项目上使用Buck构建系统，由Uber开源。
* [Gradle Dependency Graph Generator Plugin](https://github.com/vanniktech/gradle-dependency-graph-generator-plugin)：可让你在图表中可视化依赖关系的Gradle插件。
* [Gradle Graal](https://github.com/palantir/gradle-graal)：一个Gradle插件，添加了下载、提取任务以及与GraalVM工具交互的任务。

## Intellij插件

* [Translation](https://github.com/YiiGuxing/TranslationPlugin)：基于IntelliJ的IDE/Android Studio的翻译插件。
* [IdeaVim](https://github.com/JetBrains/ideavim)：IdeaVim是适用于JetBrains IDE的Vim引擎。
* [Golang Plugin](https://github.com/go-lang-plugin-org/go-lang-idea-plugin)：用于IntelliJ的Go插件。
* [Rainbow Brackets](https://github.com/izhangzhihao/intellij-rainbow-brackets)：适用于基于IntelliJ的IDE/Android Studio/HUAWEI DevEco Studio的Rainbow Brackets插件。
* [EasyCode](https://gitee.com/makejava/EasyCode)：EasyCode是基于IntelliJ IDEA开发的一个代码生成插件，主要通过自定义模板(基于Velocity)来生成各种你想要的代码。
* [Leetcode Editor](https://github.com/shuzijun/leetcode-editor)：在JetBrains IDE中练习LeetCode的插件。
* [Lombok Intellij Plugin](https://github.com/mplushnikov/lombok-intellij-plugin)：提供对Lombok注解的支持。
* [Key Promoter X](https://github.com/halirutan/IntelliJ-Key-Promoter-X)：用于学习快捷方式的现代IntelliJ插件。
* [Flutter Plugin](https://github.com/flutter/flutter-intellij)：用于Flutter开发的IntelliJ插件。
* [EmmyLua](https://github.com/EmmyLua/IntelliJ-EmmyLua)：IntelliJ IDEA的Lua IDE/调试器插件。
* [EasyDoc](https://github.com/starcwang/easy_javadoc)：IntelliJ IDEA插件，自动生成JavaDoc文档注释。
* [AutoDev](https://github.com/unit-mesh/auto-dev)：人工智能驱动的编码向导，具有多语言支持、自动代码生成，以及有用的错误消除助手，由UnitMesh开源。
* [Elixir](https://github.com/KronicDeth/intellij-elixir)：适用于JetBrain IntelliJ平台(包括Rubymine)的Elixir插件。
* [Haskell](https://github.com/rikvdkleij/intellij-haskell)：用于Haskell的IntelliJ插件。
* [WakaTime](https://github.com/wakatime/jetbrains-wakatime)：WakaTime是一个开源Jetbrains插件，用于根据你的编程活动自动生成指标、见解和时间跟踪。
* [Mybatislog](https://github.com/Link-Kou/intellij-mybaitslog)：Mybatislog是基于Intellij开发的插件项目，用来格式化输出Mybatis的SQL。
* [GsonFormat](https://github.com/zzz40500/GsonFormat)：这是一个可以从JSON字符串生成JSON模型的插件。
* [MinecraftDev](https://github.com/minecraft-dev/MinecraftDev)：IntelliJ IDEA插件，为Minecraft模组项目提供特殊支持。
* [GitIgnore](https://github.com/JetBrains/idea-gitignore)：.ignore IntelliJ IDEA支持插件。
* [Intellij Swagger](https://github.com/zalando/intellij-swagger)：可帮助你在IntelliJ IDEA中轻松编辑Swagger和OpenAPI规范文件。
* [Scala Plugin](https://github.com/JetBrains/intellij-scala)：IntelliJ IDEA的Scala插件。
* [CheckStyle IDEA](https://github.com/jshiell/checkstyle-idea)：IntelliJ IDEA的CheckStyle插件。
* [Android Parcelable](https://github.com/mcharmas/android-parcelable-intellij-plugin)：用于Android Parcelable样板代码生成的IntelliJ插件。
* [IntelliJ Plugins](https://github.com/JetBrains/intellij-plugins)：IntelliJ IDEA Ultimate和其他基于IntelliJ平台的IDE发行版中包含的开源插件。
* [PHP Inspections](https://github.com/kalessil/phpinspectionsea)：PHP静态代码分析器。
* [Restful Fast Request](https://github.com/dromara/fast-request)：Restful Fast Request是Postman的Intellij IDEA版本，它是一个强大的RESTful API工具包插件，由dromara社区开源。

## Spring生态

* [Spring Boot Admin](https://github.com/codecentric/spring-boot-admin)：该项目为公开Actuator端点的Spring Boot Web应用程序提供了一个管理界面。
* [MyBatis Spring Boot](https://github.com/mybatis/spring-boot-starter)：MyBatis与Spring Boot集成。
* [Spring Initializr](https://github.com/spring-io/initializr)：Spring项目的快速生成器。
* [gRPC Spring Boot](https://github.com/yidongnan/grpc-spring-boot-starter)：gRPC框架的Spring Boot Starter模块。
* [gRPC Spring Boot](https://github.com/LogNet/grpc-spring-boot-starter)：gRPC的Spring Boot Starter模块。
* [gRPC Spring Boot](https://github.com/grpc-ecosystem/grpc-spring)：gRPC框架的Spring Boot Starter库。
* [Retrofit Spring Boot](https://github.com/LianjiaTech/retrofit-spring-boot-starter)：适用于Retrofit的Spring Boot Starter，支持快速集成和功能增强，由链家开源。
* [Spring Cloud Zuul RateLimit](https://github.com/marcosbarbero/spring-cloud-zuul-ratelimit)：用于在Netflix Zuul中启用每个服务的速率限制的模块。
* [Spring Boot DataSource Decorator](https://github.com/gavlyukovskiy/spring-boot-data-source-decorator)：Spring Boot与p6spy、datasource-proxy、flexy-pool和spring-cloud-sleuth集成。
* [ChatGPT Spring Boot](https://github.com/linux-china/chatgpt-spring-boot-starter)：Spring Boot ChatGPT Starter。
* [ChatGPT Spring Boot](https://github.com/flashvayne/chatgpt-spring-boot-starter)：基于OpenAI官方API的Spring Boot Starter。
* [Wavefront Spring Boot Starter](https://github.com/wavefrontHQ/wavefront-spring-boot)：该项目为Wavefront提供了Spring Boot 3 Starter。
* [Spring Boot Dubbo](https://github.com/apache/dubbo-spring-boot-project)：Dubbo Spring Boot项目可以轻松使用Dubbo作为RPC框架创建Spring Boot应用程序。
* [Spring Boot Jasypt](https://github.com/ulisesbocchio/jasypt-spring-boot)：Jasypt Spring Boot为Spring Boot应用程序中的属性源提供加密支持。
* [Spring Data JPA EntityGraph](https://github.com/Cosium/spring-data-jpa-entity-graph)：Spring Data JPA扩展允许在Repository上完全动态使用EntityGraph。
* [Spring Search](https://github.com/sipios/spring-search)：Spring Search提供了一种简单的查询语言来对JPA实体执行高级搜索。
* [Okta Spring Boot](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter。
* [Chaos Monkey Spring Boot](https://github.com/codecentric/chaos-monkey-spring-boot)：该项目为Spring Boot应用程序提供了Chaos Monkey，并将尝试攻击你正在运行的Spring Boot应用程序。
* [Spring Content](https://github.com/paulcwarren/spring-content)：Spring的云原生存储和企业内容服务。
* [Spring Boot Logging](https://github.com/piomin/spring-boot-logging)：用于记录Spring Boot应用程序的HTTP请求/响应以及与Elastic Stack集成的库。
* [Spring Boot Starter Calma](https://github.com/marvinSpring/spring-boot-starter-calma)：异常通知框架。
* [Spring Boot HTMX](https://github.com/wimdeblauwe/htmx-spring-boot)：用于使用htmx的Spring Boot和Thymeleaf助手。
* [Spring Batch Plus](https://github.com/naver/spring-batch-plus)：Spring Batch Plus为Spring Batch提供了扩展功能，NAVER开源。
* [WireMock Spring Boot](https://github.com/maciejwalkowiak/wiremock-spring-boot)：WireMock Spring Boot极大地简化了基于Spring Boot和Junit 5的集成测试中的HTTP客户端测试。
* [DJL Spring Boot](https://github.com/deepjavalibrary/djl-spring-boot-starter)：DJL Spring Boot Starter。
* [Spring ViewComponent](https://github.com/tschuehly/spring-view-component)：使用Spring创建服务器端ViewComponent的库。
* [Narayana Spring Boot](https://github.com/snowdrop/narayana-spring-boot)：Narayana Spring Boot自动配置和Starter。
* [Spring DBUnit](https://github.com/springtestdbunit/spring-test-dbunit)：Spring测试框架和DBUnit之间的集成。
* [Alibaba Spring Boot](https://github.com/alibaba/aliyun-spring-boot)：阿里云服务Spring Boot Starter。
* [Springwolf](https://github.com/springwolf/springwolf-core)：使用Spring Boot构建的异步API的自动化文档。
* [Camel Spring Boot](https://github.com/apache/camel-spring-boot)：Camel Spring Boot支持。
* [Wicket Spring Boot](https://github.com/MarcGiffing/wicket-spring-boot)：Wicket的Spring Boot Starter。
* [Bitcoin Spring Boot](https://github.com/theborakompanioni/bitcoin-spring-boot-starter)：使用Spring Boot编写企业比特币应用程序的工具。
* [Spring Boot Bucket4j](https://github.com/MarcGiffing/bucket4j-spring-boot-starter)：Bucket4j的Spring Boot Starter。
* [Camunda Spring Boot](https://github.com/camunda/camunda-bpm-spring-boot-starter)：Camunda的Spring Boot Starter。
* [Charon Spring Boot](https://github.com/mkopylec/charon-spring-boot-starter)：以Spring Boot Starter形式的反向代理实现。
* [Desensitization Spring Boot](https://github.com/allurx/desensitization-spring-boot)：脱敏库与Spring Boot集成。
* [reCAPTCHA Spring Boot](https://github.com/mkopylec/recaptcha-spring-boot-starter)：Google reCAPTCHA的Spring Boot Starter。
* [RocketMQ Spring](https://github.com/apache/rocketmq-spring)：该项目旨在帮助开发者快速将RocketMQ与Spring Boot集成。
* [PageHelper Spring Boot](https://github.com/pagehelper/pagehelper-spring-boot)：Mybatis分页插件与Spring Boot的集成。
* [Pug4j Spring Boot](https://github.com/domix/jade4j-spring-boot-starter)：Spring Boot Jade4j Starter。
* [RESTEasy Spring Boot](https://github.com/resteasy/resteasy-spring-boot)：RESTEasy Spring Boot Starter。
* [CXF Spring Boot](https://github.com/codecentric/cxf-spring-boot-starter)：由Spring Boot和CXF提供支持的企业和生产就绪SOAP Web Service。
* [Spring Boot Batch Web](https://github.com/codecentric/spring-boot-starter-batch-web)：由Spring Boot提供支持的企业就绪、生产就绪的批处理应用程序。
* [Problem Spring Web](https://github.com/zalando/problem-spring-web)：用于从Spring应用程序生成application/problem+json响应，由Zalando开源。
* [SnapAdmin](https://github.com/aileftech/snap-admin)：Spring Boot数据库管理面板。
* [Ostara](https://github.com/krud-dev/ostara)：Ostara是一款开源桌面应用程序，旨在简化Spring Boot应用程序的管理和监控。
* [Trampoline](https://github.com/ErnestOrt/Trampoline)：Trampoline是一个开源项目，可帮助你在开发阶段启动和停止基于Spring Boot的服务。
* [RateLimiter Spring Boot Starter](https://github.com/taptap/ratelimiter-spring-boot-starter)：基于Redis的偏业务应用的分布式限流组件，目前支持时间窗口、令牌桶两种限流算法，由Taptap开源。
* [Specification Arg Resolver](https://github.com/tkaczmarzyk/specification-arg-resolver)：用于使用Spring MVC和Spring Data JPA过滤数据的替代API。
* [Spring-Dotenv](https://github.com/paulschwarz/spring-dotenv)：为Spring提供Dotenv属性源。
* [Spring Boot TestJars](https://github.com/spring-projects-experimental/spring-boot-testjars)：该项目允许用户通过将外部Spring Boot应用程序创建为Bean来轻松启动它。
* [Infobip Spring Data Querydsl](https://github.com/infobip/infobip-spring-data-querydsl)：Infobip Spring Data Querydsl使用户能够在Spring Data Repository之上利用Querydsl API的全部功能。
* [Spring Boot Graceful Shutdown](https://github.com/SchweizerischeBundesbahnen/springboot-graceful-shutdown)：Spring Boot Graceful Shutdown使你的Spring Boot应用程序能够在OpenShift上进行滚动部署，而无需任何停机，由瑞士联邦铁路开源。
* [Assistant](https://github.com/Geniusay/Assistant)：Assistant是一个基于Spring Boot框架的后端开发工具。
* [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions)：Spring Data JPA MongoDB Expressions是一个允许你使用MongoDB查询语言查询Spring Data JPA Repository的库。

## 其他

* [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition)：FizzBuzz是一款作为编程作业而广受欢迎的游戏，用于在工作面试期间淘汰非程序员。
* [Jpostal](https://github.com/openvenues/jpostal)：Jpostal是libpostal的Java绑定，用于快速国际街道地址解析/规范化。
* [Gurux.DLMS](https://github.com/Gurux/gurux.dlms.java)：Gurux.DLMS库是一个高性能Java组件，可帮助你读取DLMS/COSEM兼容的电表、燃气表或水表。
* [FlowGate](https://github.com/vmware/flowgate)：FlowGate是一个与供应商无关的开源项目，可帮助企业集成设施系统数据和IT数据，形成其运营的单一整体视图，由VMWare开源。
* [RepRap](https://sourceforge.net/projects/reprap/)：RepRap是一种三维打印机原型机，它具有一定程度的自我复制能力，能够打印出大部分其自身的塑料组件，由英国巴斯大学开发。
* [ALARA](https://github.com/svalinn/ALARA)：ALARA的主要目的是计算整个核系统(包括裂变反应堆、聚变反应堆和加速器)中子辐射引起的诱导活化，由威斯康星大学麦迪逊分校开源。
* [OpenLCA](https://github.com/GreenDelta/olca-app)：OpenLCA是一款用于可持续性和生命周期评估的开源免费软件。
* [XraysLib](https://github.com/tschoonj/xraylib)：用于X射线荧光应用的X射线物质相互作用截面库。
* [PRISM](https://github.com/prismmodelchecker/prism)：PRISM是一种概率模型检查器，是一种对表现出随机或概率行为的系统进行形式建模和分析的工具。
* [Portico](https://github.com/openlvc/portico)：Portico是一个开源HLA运行时基础设施(RTI)实现，它旨在确保开源和免费访问驱动HLA联盟所需的必要基础设施。
* [K Framework](https://github.com/runtimeverification/k)：K Framework是一种用于设计和建模编程语言和软件/硬件系统的工具。
* [OpenWayback](https://github.com/iipc/openwayback)：OpenWayback是全球网络档案馆用来在用户浏览器中“回放”存档网站的关键软件，由国际互联网保护联盟开源。
* [Alf.io](https://github.com/alfio-event/alf.io)：Alf.io是一款免费开源活动出席管理系统，专为关心客户隐私、安全和公平定价政策的活动组织者而开发。
* [Alchemist](https://github.com/AlchemistSimulator/Alchemist)：Alchemist是一个用于普适性、聚合性和受自然启发的计算的模拟器。
* [NeqSim](https://github.com/equinor/neqsim)：NeqSim是一个用于估计流体特性和流程设计的Java库，由挪威科技大学开源。
* [AsTeRICS](https://github.com/asterics/AsTeRICS)：AsTeRICS是一个用于辅助技术的免费开源图形构建集。
* [JIDT](https://github.com/jlizier/jidt)：JIDT提供了复杂系统中分布式计算的信息论测量的独立、开源代码Java实现。
* [Mil Sym Java](https://github.com/missioncommand/mil-sym-java)：Mil Sym Java是一组陈旧的Java库，已在美国陆军任务指挥软件中使用多年。
* [Metis](https://github.com/europeana/metis-framework)：Metis是数据发布框架，包括客户端应用程序和许多数据处理服务，由欧洲数位图书馆开源。

## 教程系列

这里包含不同领域的教程项目。

#### Java教程

* [JavaGuide](https://github.com/Snailclimb/JavaGuide)：一份涵盖大部分Java程序员所需要掌握的核心知识。
* [Advanced Java](https://github.com/doocs/advanced-java)：本项目大部分内容来自中华石杉，内容涵盖高并发、分布式、高可用、微服务、海量数据处理等领域知识。
* [Java Family](https://github.com/AobingJava/JavaFamily)：一份涵盖大部分Java程序员所需要掌握的核心知识。
* [Tutorials](https://github.com/eugenp/tutorials)：该项目是小型且重点突出的教程的集合，每个教程都涵盖Java生态系统中一个明确定义的开发领域。
* [IntelliJ IDEA Tutorial](https://github.com/judasn/IntelliJ-IDEA-Tutorial)：IntelliJ IDEA简体中文专题教程。
* [Java 8 Tutorial](https://github.com/winterbe/java8-tutorial)：本教程将逐步指导你了解所有新的语言功能。
* [Java](https://github.com/DuGuQiuBai/Java)：学习Java的基础仓库。
* [ToBeBetterJavaer](https://github.com/itwanger/toBeBetterJavaer)：一份通俗易懂、风趣幽默的Java学习指南，内容涵盖Java基础、Java并发编程、Java虚拟机、Java企业级开发、Java面试等核心知识点。
* [JVM](https://github.com/doocs/jvm)：Java虚拟机底层原理知识总结。
* [JavaTutorial](https://github.com/h2pl/JavaTutorial)：本仓库涵盖大部分Java程序员所需要掌握的核心知识，整合了互联网上的很多优质Java技术文章。
* [Athena](https://github.com/ZhongFuCheng3y/athena)：Java后端知识图谱。
* [On Java 8](https://github.com/lingcoder/OnJava8)：《On Java 8》中文版。
* [JGrowing](https://github.com/javagrowing/JGrowing)：Java学习路线仓库。
* [Concurrent](https://github.com/RedSpider1/concurrent)：这是RedSpider社区成员原创与维护的Java多线程系列文章。
* [Blog Demo](https://github.com/zq2599/blog_demos)：这里有六百多篇原创文章的详细分类和汇总，以及对应的源码，内容涉及Java、Docker、Kubernetes、DevOps等方面。
* [Tech Weekly](https://github.com/mercyblitz/tech-weekly)：小马哥技术周报。
* [Code Guide](https://github.com/fuzhengwei/CodeGuide)：本代码库是Java开发的学习历程技术汇总，旨在为大家提供一个清晰详细的学习教程，侧重点更倾向编写Java核心内容。
* [Effective Java Third Edition](https://github.com/jbloch/effective-java-3e-source-code)：来自《Effective Java》第三版的源代码，根据需要进行了少量添加以使其可运行。
* [Technology Talk](https://github.com/aalansehaiyang/technology-talk)：一份Java程序员需要的技术指南，这里有面试题、系统架构、职场锦囊、主流中间件等。
* [Learning Notes](https://github.com/francistao/LearningNotes)：Java学习笔记。
* [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap)：2024年成为Java开发人员的路线图。
* [JavaCore](https://github.com/dunwu/javacore)：JavaCore是对Java核心技术的经验总结。
* [BookSource](https://github.com/guolindev/booksource)：《第一行代码 第2版》全书源代码。
* [On Java 8 Examples](https://github.com/BruceEckel/OnJava8-Examples)：《On Java 8》一书的代码示例。
* [Java Practice](https://github.com/HelloWorld521/Java)：Java项目实战练习。
* [Code Examples](https://github.com/thombergs/code-examples)：该仓库包含示例项目，展示如何使用不同的Java技术。
* [Learn Java Bug](https://github.com/threedr3am/learnjavabug)：Java安全相关的漏洞和技术Demo。
* [30 Seconds Of Java 8](https://github.com/hellokaton/30-seconds-of-java8)：你可以在30秒或更短时间内收集有用的Java 8代码片段。
* [Note](https://github.com/scalad/Note)：常规Java工具、算法、加密、数据库、面试题、源代码分析、解决方案。
* [Java Lambda Internals](https://github.com/CarpenterLee/JavaLambdaInternals)：深入理解Java函数式编程和Streams API。
* [Java Learning](https://github.com/brianway/java-learning)：旨在打造在线最佳的Java学习笔记，含博客讲解和源码实例，包括Java SE和Java Web。
* [Java Tutorial](https://github.com/dunwu/java-tutorial)：Java Tutorial是一个Java教程。
* [Java Keeper](https://github.com/Jstarfish/JavaKeeper)：Java工程师必备架构体系知识总结：涵盖分布式、微服务、RPC等互联网公司常用架构，以及数据存储、缓存、搜索等必备技能。
* [Java 8 Lambdas Exercises](https://github.com/RichardWarburton/java-8-lambdas-exercises)：该仓库包含Java 8 Lambdas书籍的支持材料。
* [Six Finger](https://github.com/bin392328206/six-finger)：从Java基础、Java Web基础到常用的框架再到面试题、微服务、分布式、大数据都有完整的教程，几乎涵盖了Java必备的知识点。
* [WhatsMars](https://github.com/javahongxi/whatsmars)：Java生态研究(Spring Boot + Redis + Dubbo + RocketMQ + ElasticSearch)。

#### 大数据教程

* [BigData-Notes](https://github.com/heibaiying/BigData-Notes)：大数据入门指南。
* [Flink Learning](https://github.com/zhisheng17/flink-learning)：含Flink入门、概念、原理、实战、性能调优、源码解析等内容。
* [Flink Recommand System Demo](https://github.com/will-che/flink-recommandSystem-demo)：基于Flink实现的商品实时推荐系统。
* [DB Tutorial](https://github.com/dunwu/db-tutorial)：DB Tutorial是一个数据库教程。
* [Movie Recommend](https://github.com/LuckyZXL2016/Movie_Recommend)：基于Spark的电影推荐系统，包含爬虫项目、Web网站、后台管理系统以及Spark推荐系统。
* [BigData Guide](https://github.com/MoRan1607/BigDataGuide)：大数据学习指南，从零开始学习大数据开发，包含大数据学习各个阶段资汇总。
* [Learning Spark](https://github.com/databricks/learning-spark)：Learning Spark书中的示例。
* [Spark Doc Zh](https://github.com/apachecn/spark-doc-zh)：Apache Spark官方文档中文版。
* [Coolplay Spark](https://github.com/lw-lin/CoolplaySpark)：Coolplay Spark包含Spark源代码解析、Spark类库、Spark代码等。

#### Spring生态教程

* [Spring Boot Demo](https://github.com/xkcoding/spring-boot-demo)：Spring Boot Demo是一个用来深度学习并实战Spring Boot的项目。
* [Spring Boot Examples](https://github.com/ityouknow/spring-boot-examples)：Spring Boot使用的各种示例，以最简单、最实用为标准，此开源项目中的每个示例都以最小依赖，最简单为标准，帮助初学者快速掌握Spring Boot各组件的使用。
* [SpringAll](https://github.com/wuyouzhuguli/SpringAll)：循序渐进，学习Spring Boot、Spring Batch、Spring Cloud、Spring Cloud Alibaba、Spring Security。
* [Spring Boot Reference Guide](https://github.com/qibaoguang/Spring-Boot-Reference-Guide)：Spring Boot Reference Guide中文翻译。
* [SpringBoot Labs](https://github.com/yudaocode/SpringBoot-Labs)：一个涵盖六个专栏：Spring Boot 2.X、Spring Cloud、Spring Cloud Alibaba、Dubbo、分布式消息队列、分布式事务的仓库。
* [Spring Cloud Learning](https://github.com/forezp/SpringCloudLearning)：史上最简单的Spring Cloud教程源码。
* [Spring Boot Learning Example](https://github.com/JeffLi1993/springboot-learning-example)：Spring Boot实践学习案例，是Spring Boot初学者及核心技术巩固的最佳实践。
* [SpringBoot-Learning](https://github.com/dyc87112/SpringBoot-Learning)：打造全网内容最全，比收费教程更好的Spring Boot免费教程。
* [Paas Cloud](https://github.com/paascloud/paascloud-master)：Spring Cloud + Vue + OAuth2.0全家桶实战，前后端分离模拟商城，完整的购物流程、后端运营平台，可以实现快速搭建企业级微服务项目。
* [SpringCloud-Learning](https://github.com/dyc87112/SpringCloud-Learning)：本项目内容为Spring Cloud教程的程序样例。
* [SpringBoot](https://github.com/527515025/springBoot)：Spring Boot框架与其它组件结合如JPA、MyBatis、WebSocket、Security、Shiro、Cache等的教程。
* [Spring Cloud Examples](https://github.com/ityouknow/spring-cloud-examples)：Spring Cloud使用的各种示例，以最简单、最实用为标准。
* [Spring Cloud Learning](https://github.com/macrozheng/springcloud-learning)：一套涵盖大部分核心组件使用的Spring Cloud教程，包括Spring Cloud Alibaba及分布式事务Seata，基于Spring Cloud Greenwich及Spring Boot 2.1.7。
* [JavaEE Test](https://github.com/lenve/JavaEETest)：Spring、Spring MVC、MyBatis、Spring Boot案例。
* [SSM](https://github.com/liyifeng1994/ssm)：手把手教你整合最优雅SSM框架：Spring MVC + Spring + MyBatis。
* [Spring Boot Vulnerability Exploit](https://github.com/LandGrey/SpringBootVulExploit)：Spring Boot相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估check list。
* [Spring Boot Projects](https://github.com/ZHENFENG13/spring-boot-projects)：该仓库中主要是Spring Boot的入门学习教程以及一些常用的Spring Boot实战项目教程。
* [Spring Data Examples](https://github.com/spring-projects/spring-data-examples)：该仓库包含不同Spring Data模块的示例项目，以展示API以及如何使用模块提供的功能。
* [Spring Boot Guide](https://github.com/CodingDocs/springboot-guide)：Spring Boot 2.0+从入门到实战。
* [Spring MVC Showcase](https://github.com/spring-attic/spring-mvc-showcase)：通过小而简单的示例演示Spring MVC Web框架的功能。
* [Spring Boot In Action](https://github.com/hansonwang99/Spring-Boot-In-Action)：Spring Boot系列实战合集。
* [Small Spring](https://github.com/fuzhengwei/small-spring)：该项目以Spring源码学习为目的，通过手写简化版Spring框架，了解Spring核心原理。
* [Spring Boot Best Practice](https://github.com/javastacks/spring-boot-best-practice)：Spring Boot最佳实践，包括自动配置、核心原理、源码分析、国际化支持、调试、日志集成、热部署等。
* [SSM](https://github.com/crossoverJie/SSM)：从0开始构建SSM和分布式微服务。
* [MyBatis Spring Boot](https://github.com/abel533/MyBatis-Spring-Boot)：Spring Boot集成MyBatis的基础项目。
* [JWT Spring Security Demo](https://github.com/szerhusenBC/jwt-spring-security-demo)：将JWT与Spring Security和Spring Boot 2结合使用的演示。
* [SpringMVC MyBatis Learning](https://github.com/brianway/springmvc-mybatis-learning)：Spring MVC和MyBatis学习笔记，搭配示例，主要讲解一些基础的概念、用法和配置。
* [Spring Boot NoteBook](https://github.com/chengxy-nds/Springboot-Notebook)：Spring Boot整合各种技术的学习项目。
* [Spring Boot Socks](https://github.com/yizhiwazi/springboot-socks)：Spring Boot基础教程。
* [Spring Cloud REST TCC](https://github.com/prontera/spring-cloud-rest-tcc)：以Spring Cloud Netflix作为服务治理基础, 展示基于TCC思想所实现的分布式事务解决方案。
* [Spring Boot Quick](https://github.com/vector4wang/spring-boot-quick)：基于Spring Boot的快速学习示例。
* [Spring Boot Learning](https://github.com/forezp/SpringBootLearning)：Spring Boot教程源码。
* [SpringBoot](https://github.com/lxy-go/SpringBoot)：这是一个SpringBoot的从入门程序集锦。
* [Spring Boot Cloud](https://github.com/zhangxd1989/spring-boot-cloud)：基于Spring Boot、Spring Cloud、Spring Oauth2和Spring Cloud Netflix等框架构建的微服务项目。
* [Spring Boot Learning](https://github.com/ityouknow/spring-boot-leaning)：Spring Boot 2.X最全课程代码。
* [Spring Guide](https://github.com/cheese10yun/spring-guide)：Spring实用指南。
* [SpringCloud](https://github.com/yinjihuan/spring-cloud)：《Spring Cloud微服务-全栈技术与案例解析》和《Spring Cloud微服务入门实战与进阶》配套源码。
* [Spring Cloud Code](https://github.com/SpringCloud/spring-cloud-code)：《重新定义Spring Cloud实战》实体书对应源码。
* [Spring Boot Vue](https://github.com/boylegu/SpringBoot-vue)：基于Spring Boot和Vue.js 2.x + Webpack 2.x作为Java全栈Web实践的示例演示。
* [Spring Security OAuth](https://github.com/Baeldung/spring-security-oauth)：致力于探索Spring Security 5中的新OAuth2堆栈。
* [Spring Boot Vue.js](https://github.com/jonashackt/spring-boot-vuejs)：展示如何构建一个使用Vue.js提供GUI的Spring Boot应用程序的示例项目。
* [Thinking In Spring Boot Samples](https://github.com/mercyblitz/thinking-in-spring-boot-samples)：《Spring Boot编程思想》示例工程。
* [Staffjoy](https://github.com/spring2go/staffjoy)：微服务和云原生架构教学案例项目，基于Spring Boot和Kubernetes技术栈。

#### 算法和数据结构教程

* [LeetCode Animation](https://github.com/MisterBooo/LeetCodeAnimation)：用动画的形式呈现解LeetCode题目的思路。
* [Hello Algo](https://github.com/krahets/hello-algo)：动画图解、一键运行的数据结构与算法教程。
* [The Algorithms](https://github.com/TheAlgorithms/Java)：所有算法的Java实现。
* [LeetCode Master](https://github.com/youngyangyang04/leetcode-master)：《代码随想录》LeetCode刷题攻略：200道经典题目刷题顺序，共60w字的详细图解，视频难点剖析，50余张思维导图。
* [Hello Algorithm](https://github.com/geekxh/hello-algorithm)：一套针对小白的完整的算法训练流程。
* [LeetCode](https://github.com/doocs/leetcode)：本项目包含LeetCode、《剑指Offer(第2版)》、《剑指Offer(专项突击版)》、《程序员面试金典(第6版)》等题目的相关题解。
* [Algorithms](https://github.com/williamfiset/Algorithms)：该仓库的目标是演示如何以最简单、最优雅的方式正确实现常见的数据结构和算法。
* [Awesome Java LeetCode](https://github.com/Blankj/awesome-java-leetcode)：LeetCode算法与Java解决方案。
* [Algs4](https://github.com/kevin-wayne/algs4)：该仓库包含Robert Sedgewick和Kevin Wayne编写的教科书《算法》第4版中的算法和客户端的Java源代码。
* [LeetCode](https://github.com/yuanguangxin/LeetCode)：LeetCode题目分类与面试问题整理。
* [JS Sorting Algorithm](https://github.com/hustcc/JS-Sorting-Algorithm)：一本关于排序算法的GitBook在线书籍《十大经典排序算法》，多语言实现。
* [LeetCode](https://github.com/awangdev/leet-code)：Java LintCode/LeetCode问题解决方案。
* [Java Algorithms Implementation](https://github.com/phishman3579/java-algorithms-implementation)：算法和数据结构的Java实现。
* [Algorithm Base](https://github.com/chefyuan/algorithm-base)：用动画将算法说的通俗易懂。
* [LeetCode Book](https://github.com/krahets/LeetCode-Book)：《剑指Offer》 Python、Java、C++解题代码，LeetBook《图解算法数据结构》配套代码仓库。
* [LeetCode](https://github.com/fishercoder1534/Leetcode)：LeetCode问题的解决方案，每日更新。
* [Play With Algorithms](https://github.com/liuyubobobo/Play-with-Algorithms)：慕课网上的课程《算法与数据结构》示例代码，包括C++和Java版本。
* [AlgoDS](https://github.com/sherxon/AlgoDS)：这是算法、数据结构和面试问题及其解决方案的集合。
* [LeetCode](https://github.com/gouthampradhan/leetcode)：针对一些常见LeetCode面试问题的解决方案。
* [Data Structures](https://github.com/williamfiset/DEPRECATED-data-structures)：强大的数据结构集合。
* [LeetCode Solutions In Good Style](https://github.com/liweiwei1419/LeetCode-Solutions-in-Good-Style)：这是一个《算法与数据结构》的入门级教程，适用于算法零基础的小白。
* [Algorithms](https://github.com/pedrovgs/Algorithms)：用Java编写的一些常见算法问题的解决方案。
* [Play With Data Structures](https://github.com/liuyubobobo/Play-with-Data-Structures)：慕课网上的课程《Java语言玩转数据结构》示例代码。
* [Algorithms Sedgewick](https://github.com/aistrate/AlgorithmsSedgewick)：《算法》(第四版)一书的代码。
* [Algorithms](https://github.com/jimmysuncpt/Algorithms)：这个项目包含《算法(第4版)》书中的代码和对部分课后练习的解答。
* [Algorithms](https://github.com/reneargento/algorithms-sedgewick-wayne)：《算法(第4版)》一书的练习题答案。
* [DataMining Algorithm](https://github.com/linyiqun/DataMiningAlgorithm)：数据挖掘18大算法实现以及其他相关经典DM算法。
* [HackerRank Solutions](https://github.com/RodneyShag/HackerRank_solutions)：317个HackerRank问题的有效解决方案。

#### 软件工程教程

* [Java Design Patterns](https://github.com/iluwatar/java-design-patterns)：用Java实现的设计模式教程。
* [ITStack Demo Design](https://github.com/fuzhengwei/itstack-demo-design)：《重学Java设计模式》是一本互联网真实案例实践书籍。
* [Awesome Architect](https://github.com/xingshaocheng/architect-awesome)：后端架构师技术图谱。
* [DesignPattern](https://github.com/youlookwhat/DesignPattern)：Java 23种设计模式全归纳。
* [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples)：这是Vaughn Vernon所著的《实现领域驱动设计》一书中的限界上下文示例。
* [Migration](https://github.com/phodal/migration)：《系统重构与迁移指南》手把手教你分析、评估现有系统、制定重构策略、探索可行重构方案、搭建测试防护网、进行系统架构重构、服务架构重构、模块重构、代码重构、数据库重构、重构后的架构守护。
* [FTGO Example Application](https://github.com/microservices-patterns/ftgo-application)：这是《微服务模式》一书的示例代码。
* [Head First Design Patterns](https://github.com/bethrobson/Head-First-Design-Patterns)：《Head First设计模式》一书代码。
* [Buckpal](https://github.com/thombergs/buckpal)：这个仓库以六角形架构风格实现了一个小型Web应用程序。
* [Three High Import](https://github.com/qiurunze123/threadandjuc)：高并发、高可靠、高性能导入系统-高并发多线程进阶。

#### 其他技术教程

* [RabbitMQ Tutorials](https://github.com/rabbitmq/rabbitmq-tutorials)：该项目包含RabbitMQ教程的代码及其对各种语言的移植。
* [API Samples](https://github.com/youtube/api-samples)：YouTube API的代码示例，包括YouTube Data API、YouTube Analytics API和YouTube Live Streaming API。
* [RxJava Samples](https://github.com/rengwuxian/RxJavaSamples)：RxJava 2和Retrofit结合使用的几个最常见使用方式举例。
* [Vert.x 4 examples](https://github.com/vert-x3/vertx-examples)：该仓库包含一系列Vert.x 4示例。
* [RxJava2 Examples](https://github.com/nanchen2251/RxJava2Examples)：从RxJava 1跳到RxJava 2(学习RxJava2 )的例子Demo。
* [Intro to RxJava](https://github.com/Froussios/Intro-To-RxJava)：本指南旨在向初学者响应式程序员介绍RxJava实现JVM响应式编程的完整功能。
* [Java EE 7 Samples](https://github.com/javaee-samples/javaee7-samples)：该仓库由Java EE 7示例和单元测试组成。
* [AWS Lambda Developer Guide](https://github.com/awsdocs/aws-lambda-developer-guide)：该仓库包含AWS Lambda开发人员指南的其他资源。
* [Netty Learning Example](https://github.com/sanshengshui/netty-learning-example)：Netty实践学习案例。
* [Netty in Action](https://github.com/normanmaurer/netty-in-action)：该仓库包含《Netty in Action》一书所有章节的源代码。
* [Netty Demos](https://github.com/waylau/netty-4-user-guide-demos)：《Netty 4.x用户指南》/《Netty原理解析与开发实战》文中用到的例子源码。
* [MyBatis-Plus Samples](https://github.com/baomidou/mybatis-plus-samples)：MyBatis Plus示例代码。
* [Kafka Streams Examples](https://github.com/confluentinc/kafka-streams-examples)：该项目包含演示如何使用Apache Kafka的Streams API实现实时应用程序和事件驱动的微服务的代码示例。
* [MIT Deep Learning Book](https://github.com/janishar/mit-deep-learning-book-pdf)：麻省理工学院深度学习书籍PDF格式。
* [Deeplearning4J Examples](https://github.com/deeplearning4j/deeplearning4j-examples)：Deeplearning4j示例(DL4J、DL4J Spark、DataVec)。
* [DeepLearning](https://github.com/yusugomori/DeepLearning)：深度学习教程(Python、C、C++、Java、Scala、Go)。
* [Quarkus QuickStarts](https://github.com/quarkusio/quarkus-quickstarts)：该仓库包含一组Quarkus框架的快速入门。
* [LWJGL Basics](https://github.com/mattdesl/lwjgl-basics)：LibGDX/LWJGL教程和示例。
* [DevOps For Beginners](https://github.com/in28minutes/devops-master-class)：DevOps初学者教程-学习Docker、Kubernetes、Terraform、Ansible、Jenkins和Azure Devops。
* [Ninety-Nine Problems](https://github.com/shekhargulati/99-problems)：这是瑞士伯尔尼伯尔尼应用科学大学Werner Hett撰写的《九十九个Prolog问题》的改编版。

#### 秒杀系统

* [Miaosha](https://github.com/qiurunze123/miaosha)：秒杀系统设计与实现，互联网工程师进阶与分析。
* [Spring Boot Seckill](https://github.com/zaiyunduan123/springboot-seckill)：基于Spring Boot + MySQL + Redis + RabbitMQ + Guava开发的高并发商品限时秒杀系统。
* [Seckill](https://github.com/codingXiaxw/seckill)：Java高并发秒杀系统API。

#### 源码分析

* [Source Code Hunter](https://github.com/doocs/source-code-hunter)：从源码层面，剖析挖掘互联网行业主流技术的底层实现原理。
* [Spring Analysis](https://github.com/seaswalker/spring-analysis)：Spring相关组件阅读笔记。
* [Mybatis](https://github.com/tuguangquan/mybatis)：Mybatis源码中文注释。
* [Spring Reading](https://github.com/xuchengsheng/spring-reading)：涵盖了Spring框架的核心概念和关键功能，包括控制反转容器的使用，面向切面编程的原理与实践。
* [IoT Technical Guide](https://github.com/IoT-Technology/IoT-Technical-Guide)：从零搭建高性能物联网平台及物联网解决方案和Thingsboard源码分析。
* [Java Source Code Learning](https://github.com/coderbruis/JavaSourceCodeLearning)：Java流行框架源码分析，学习以及总结。
* [Netty Learning](https://github.com/code4craft/netty-learning)：本系列文章是Netty的源码导读。
* [JDK Source Code Analysis](https://github.com/seaswalker/jdk-sourcecode-analysis)：JDK源码阅读笔记。

#### 面试宝典

* [Interviews](https://github.com/kdn251/interviews)：你的软件工程技术面试个人指南。
* [ToBeTopJavaer](https://github.com/hollischuang/toBeTopJavaer)：一份Java面试宝典。
* [Tech Interview](https://github.com/gyoogle/tech-interview-for-developer)：新开发者主要知识技能面试百科。
* [DSA Bootcamp Java](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java)：该仓库包含WeMakeDevs的Java数据结构和算法+面试准备训练营的代码示例、作业和注释。
* [CtCI-6th-Edition](https://github.com/careercup/CtCI-6th-Edition)：破解编码面试第六版的解决方案。
* [Interview](https://github.com/mission-peace/interview)：面试问题。
* [FullStack Tutorial](https://github.com/frank-lam/fullstack-tutorial)：后台技术栈/架构师之路/全栈开发社区，春招/秋招/校招/面试。
* [Java Eight Part](https://github.com/CoderLeixiaoshuai/java-eight-part)：Java八股文仓库。
* [SDE-Interview-Questions](https://github.com/twowaits/SDE-Interview-Questions)：从Geeksforgeeks、CareerCup和Glassdoor中抓取的最全面的技术面试问题列表。
* [Learning Note](https://github.com/rbmonster/learning-note)：Java开发及面试(个人面试、工作总结、资料收集站)。
* [Interview Guide](https://github.com/NotFound9/interviewGuide)：包括Java基础、JVM、数据库、MySQL、Redis、计算机网络、算法、数据结构、操作系统、设计模式、系统设计、框架原理。
* [Internet Architect](https://github.com/bjmashibing/InternetArchitect)：互联网架构师课程文档及源码。
* [Java Notes](https://github.com/DreamCats/java-notes)：秋招经历、牛客面经问题按照频率总结、Java系列知识、数据库、分布式、微服务、前端、技术面试、每日文章等。
* [System Design Interview](https://github.com/DreamOfTheRedChamber/system-design-interviews)：系统设计面试。
