## 测试

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试、断言库、Mock框架等。

#### 单元测试

* [JUnit 4](https://github.com/junit-team/junit4)：JUnit是一个用于编写可重复测试的简单框架。
* [JUnit 5](https://github.com/junit-team/junit5)：JUnit 5是Java单元测试框架的最新版本，相较于JUnit 4，它引入了许多新的特性和改进。
* [TestNG](https://github.com/testng-team/testng)：TestNG是一个受JUnit启发的测试框架，但引入了一些新功能，使其更强大且更易于使用。
* [Spock](https://github.com/spockframework/spock)：Spock是一个用于Java和Groovy应用程序的BDD风格的开发人员测试和规范框架。
* [Kotest](https://github.com/kotest/kotest)：Kotest是一个灵活且全面的Kotlin测试工具，具有多平台支持。
* [ScalaTest](https://github.com/scalatest/scalatest)：ScalaTest是一个为Scala和Java程序员提供的免费开源测试工具包。
* [Midje](https://github.com/marick/Midje)：Midje是一个Clojure测试框架。
* [UTest](https://github.com/com-lihaoyi/utest)：UTest是一个简单、直观的Scala测试库。
* [MUnit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。
* [MiniTest](https://github.com/monix/minitest)：Scala和Scala.js的超轻量级测试库。
* [Verify](https://github.com/eed3si9n/verify)：Verify是一个极简的单元测试框架。
* [JsUnit](https://github.com/vmware-archive/jsunit)：JavaScript的原始单元测试框架，由VMware开源。
* [Cobol Check](https://github.com/openmainframeproject/cobol-check)：Cobol Check为Cobol提供了细粒度的单元测试/检查。

#### 集成测试

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：Testcontainers是一个支持JUnit测试的Java库，提供通用数据库、Selenium Web浏览器或任何其他可以在Docker容器中运行的东西的轻量级一次性实例。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：MicroShed Test提供了一种快速、简单的方法来为Java微服务应用程序编写和运行真正的生产集成测试。
* [Embedded Kafka](https://github.com/embeddedkafka/embedded-kafka)：提供内存中的Kafka实例来运行测试的库。
* [Scalatest Embedded Kafka](https://github.com/manub/scalatest-embedded-kafka)：一个提供内存Kafka实例来运行测试的库。
* [Kafka Unit](https://github.com/chbatey/kafka-unit)：允许你启动和停止Kafka代理、ZooKeeper实例，以对与Kafka通信的应用程序进行单元测试。
* [Mocked Streams](https://github.com/jpzk/mockedstreams)：Mocked Streams是Scala 2.12和2.13的一个库，它允许你在没有Zookeeper和Kafka Brokers的情况下对Kafka Streams应用程序的处理拓扑进行单元测试。
* [Fluent Kafka Streams Tests](https://github.com/bakdata/fluent-kafka-streams-tests)：使用Java进行流式的Kafka Streams测试。
* [Embedded Redis](https://github.com/kstyrc/embedded-redis)：用于Java集成测试的Redis嵌入式服务器。
* [Redis Mock](https://github.com/microwww/redis-mock)：纯Java实现的Redis Server，单元测试时嵌入Redis服务。
* [Embedded PostgreSQL](https://github.com/opentable/otj-pg-embedded)：允许使用Docker容器将PostgreSQL嵌入到Java应用程序代码中。
* [Embedded LDAP JUnit](https://github.com/zapodot/embedded-ldap-junit)：用于在JUnit测试中运行嵌入式LDAP服务器的JUnit Rule。
* [Embedded MySQL](https://github.com/wix-incubator/wix-embedded-mysql)：用于测试的嵌入式MySQL。
* [Embedded MongoDB](https://github.com/flapdoodle-oss/de.flapdoodle.embed.mongo)：Embedded MongoDB提供一种平台中立的方式在单元测试中运行MongoDB。
* [Embedded Postgres Binaries](https://github.com/zonkyio/embedded-postgres-binaries)：该项目提供了PostgreSQL二进制文件的轻量级捆绑包，大小更小，旨在用于测试目的。
* [Embedded Database](https://github.com/zonkyio/embedded-database-spring-test)：用于为Spring支持的集成测试创建隔离的嵌入式数据库的库。
* [Embedded ElasticSearch](https://github.com/allegro/embedded-elasticsearch)：简化使用Elasticsearch创建集成测试的工具，由Allegro开源。
* [Embedded Consul](https://github.com/pszymczyk/embedded-consul)：Embedded Consul提供了在集成测试中运行Consul的简单方法。
* [Embedded RabbitMQ](https://github.com/AlejandroRivera/embedded-rabbitmq)：使用RabbitMQ作为嵌入式服务的JVM库。
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
* [Embedded Process Util](https://github.com/flapdoodle-oss/de.flapdoodle.embed.process)：Embedded Process Util为在单元测试中运行进程提供一种平台中立的方式。
* [Embedded PostgreSQL Server](https://github.com/yandex-qatools/postgresql-embedded)：嵌入式PostgreSQL服务器提供了一种平台中立的方式来在单元测试中运行Postgres二进制文件，由Yandex开源。
* [Embedded Cassandra](https://github.com/nosan/embedded-cassandra)：Embedded Cassandra提供了一种启动和停止Cassandra的简单方法。
* [CassandraUnit](https://github.com/jsevellec/cassandra-unit)：CassandraUnit是一个Java测试工具，它可以用于测试使用Cassandra数据库后端创建的Java应用程序。
* [Alternator](https://github.com/mboudreau/Alternator)：用于测试目的在本地运行的模拟DynamoDB。
* [Keycloak Testcontainer](https://github.com/dasniko/testcontainers-keycloak)：Keycloak SSO的Testcontainers实现。
* [MongoUnit](https://github.com/mongounit/mongounit)：MongoUnit是一个数据驱动的集成测试框架，适用于使用MongoDB进行持久化的基于Spring Boot的应用程序。
* [Arquillian](https://github.com/arquillian/arquillian-core)：Arquillian是一个创新且高度可扩展的JVM测试平台，使开发人员能够轻松地为Java中间件创建自动化集成、功能和验收测试，由RedHat开源。
* [Kindcontainer](https://github.com/dajudge/kindcontainer)：基于Java的Testcontainers容器实现，为集成测试提供临时Kubernetes集群。
* [Embedded DB JUnit](https://github.com/zapodot/embedded-db-junit)：提供内存数据库的JUnit Rule(支持H2和HyperSQL)。
* [Nats Server Embedded](https://github.com/YunaBraska/nats-server-embedded)：用于测试的Nats服务器。
* [PelicanDT](https://github.com/alibaba/PelicanDT)：PelicanDT是阿里云提供的一款Linux系统远程控制利器，是主要针对分布式应用提供的集成测试解决方案，用于帮助开发者简单、高效地测试分布式应用。
* [Lowkey Vault](https://github.com/nagyesta/lowkey-vault)：Lowkey Vault是一个测试替身，旨在与Azure Key Vault REST API兼容。
* [Docker IT Scala](https://github.com/whisklabs/docker-it-scala)：一组实用程序类，可轻松进行与Scala中的Docker化服务的集成测试。
* [DbSandboxer](https://github.com/misirio/dbsandboxer)：DbSandboxer通过为集成测试创建沙盒数据库实例来为Spring Boot应用程序提供测试隔离。

#### 接口测试

* [Rest Assured](https://github.com/rest-assured/rest-assured)：Rest Assured是用于轻松测试REST服务的Java DSL。
* [Wisdom](https://github.com/wisdom-projects/rest-client)：Wisdom可以自动化测试REST API并生成精美的测试报告，同时基于测试过的历史数据，可以生成精美的REST API文档。
* [Milkman](https://github.com/warmuuh/milkman)：Postman的可扩展替代方案，用于制作各种请求，不仅适用于gRPC，还适用于HTTP、SQL等。
* [CATS](https://github.com/Endava/cats)：CATS是一个REST API模糊器和OpenAPI端点的负面测试工具，由Endava开源。
* [Dochia](https://github.com/dochia-dev/dochia-cli)：Dochia会自动生成并执行负面测试和边界测试，让你专注于创造性地解决问题。
* [Everest](https://github.com/RohitAwate/Everest)：Everest是一个用JavaFX编写的REST API测试客户端。
* [ACTS](https://github.com/sofastack/sofa-acts)：ACTS是一个基于数据模型驱动的白盒测试框架，由蚂蚁开源。
* [RESTClient](https://github.com/wiztools/rest-client)：RESTClient是一个用于测试RESTful Web服务的Java应用程序，它可用于测试各种HTTP通信。
* [EasyPostman](https://github.com/lakernote/EasyPostman)：EasyPostman是一款高仿Postman、简易版JMeter的开源接口调试与压测工具。
* [Rest Driver](https://github.com/rest-driver/rest-driver)：用于测试RESTful服务和客户端的工具。
* [Hikaku](https://github.com/codecentric/hikaku)：Hikaku可以测试REST API实现是否满足其规范。
* [Hiroaki](https://github.com/JorgeCastilloPrz/hiroaki)：Hiroaki的目的是利用Kotlin的强大功能，以惯用的方式实现API集成测试的清晰度。
* [RESTest](https://github.com/isa-group/RESTest)：RESTest是一个用于RESTful Web API自动化黑盒测试的框架，由塞维利亚大学开源。
* [Cornichon](https://github.com/agourlay/cornichon)：用于测试JSON HTTP API的可扩展Scala DSL。
* [ChocoTea](https://github.com/cleopatra27/chocotea)：Chocotea是一个从Java代码生成Postman集合、环境和集成测试的库。
* [Heat](https://github.com/ExpediaGroup/heat)：Heat是一个基于REST Assured框架的简单解决方案，由Expedia开源。
* [Hrun4j](https://github.com/lematechvip/hrun4j)：Hrun4j是由乐马技术推出的开源一站式接口测试解决方案。
* [Hsac Fitnesse Fixtures](https://github.com/fhoeben/hsac-fitnesse-fixtures)：该项目通过提供定义和运行测试的应用程序来协助测试Web Services和Web应用程序。
* [Hello HTTP](https://github.com/sunny-chung/hello-http)：Hello HTTP是一个跨平台的便携式HTTP客户端桌面应用程序，用于测试HTTP和REST API、WebSocket、GraphQL和gRPC端点。
* [Restfuse](https://github.com/eclipsesource/restfuse)：Restfuse是一个用于自动化REST/HTTP集成测试的库。
* [WSPerfLab](https://github.com/Netflix-Skunkworks/WSPerfLab)：用于测试Web服务实现的项目，由Netflix开源。
* [RestCLI](https://github.com/restcli/restcli)：用于执行Intellij HTTP客户端文件的命令行应用程序。
* [HttpX](https://github.com/servicex-sh/httpx)：HttpX是一个用于执行来自JetBrains Http File的请求的CLI。

#### 端到端测试

* [Maestro](https://github.com/mobile-dev-inc/Maestro)：Maestro是最简单、最强大、最值得信赖的移动和Web应用程序端到端测试平台。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [KITE](https://github.com/webrtc/KITE)：KITE是一个用于测试跨浏览器WebRTC互操作性的测试引擎。
* [Stove](https://github.com/Trendyol/stove)：Stove是一个端到端测试框架，可以将物理依赖项和你的应用程序一起启动，由Trendyol开源。
* [Citrus](https://github.com/citrusframework/citrus)：Citrus是一个用Java编写的测试框架，能够为企业SOA应用程序创建完全自动化的端到端用例测试，由RedHat开发。
* [Testlum](https://github.com/TestlumFramework/Testlum)：无代码端到端测试框架，让你的测试更加轻松。
* [Sakuli](https://github.com/ConSol/sakuli)：Sakuli是一款端到端测试和监控工具，适用于具有多个监控集成的网站和常见UI。
* [HybridTestFramework](https://github.com/dipjyotimetia/HybridTestFramework)：HybridTestFramework是一个全面而多功能的测试框架，旨在涵盖软件测试的各个方面。
* [Protractor](https://github.com/paul-hammant/ngWebDriver)：AngularJS和WebDriver的Java部分(Protractor的端口)。
* [Spectrum](https://github.com/giulong/spectrum)：Spectrum是一个JUnit 6和Selenium 4框架，旨在简化E2E测试的编写。

#### 功能测试

* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [Galen](https://github.com/galenframework/galen)：Galen是一个开源工具，用于测试Web应用程序的布局和响应式设计，它也是一个强大的功能测试框架。
* [Markov](https://github.com/alibaba/intelligent-test-platform)：Markov是阿里开源的新一代功能测试平台，包含可视化用例编写管理、分布式的沙盒环境和测试数据构建、测试流程pipeline管理等优点。
* [Acai](https://github.com/google/acai)：Acai使你可以轻松地使用JUnit 4和Guice编写应用程序的功能测试，由Google开源。
* [Bobcat](https://github.com/wttech/bobcat)：Bobcat是一个用于Web应用程序功能测试的自动化测试框架。

#### 突变测试

* [Pitest](https://github.com/hcoles/pitest)：Pitest是最先进的Java和JVM突变测试系统。
* [Major](https://mutation-testing.org/)：Major是一个高效、灵活的突变分析框架。
* [Stryker4s](https://github.com/stryker-mutator/stryker4s)：Stryker4s是Scala的突变测试框架。
* [Descartes](https://github.com/STAMP-project/pitest-descartes)：Descartes通过报告所覆盖代码中的弱点来支持开发人员改进他们的测试套件。
* [Judy](http://mutationtesting.org/judy2/)：Judy是一个用Java编写的突变测试器，由弗罗茨瓦夫理工大学开源。
* [Mutandis](https://github.com/saltlab/mutandis)：Mutandis是一个JavaScript突变测试工具，由不列颠哥伦比亚大学开源。
* [PG Index Health](https://github.com/mfvanek/pg-index-health)：PG Index Health是一个用于分析和维护PostgreSQL数据库中索引和表健康状况的Java库。
* [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector)：Mutability Detector旨在分析Java类并报告给定类的实例是否不可变。

#### 模糊测试

* [Jazzer](https://github.com/CodeIntelligenceTesting/jazzer)：由Code Intelligence开发的适用于JVM平台的覆盖率引导的进程内模糊器，它基于libFuzzer，并将许多由仪器驱动的突变功能引入JVM。
* [Kelinci](https://github.com/isstac/kelinci)：用于在Java程序上运行AFL的接口，由CMU开源。
* [Kotlinx Fuzz](https://github.com/JetBrains-Research/kotlinx.fuzz)：Kotlinx Fuzz是一个适用于Kotlin的通用模糊测试库，由JetBrains开源。
* [SQLancer](https://github.com/sqlancer/sqlancer)：SQLancer是一个自动测试DBMS以发现其实现中的逻辑错误的工具。
* [Javafuzz](https://github.com/fuzzitdev/javafuzz)：Javafuzz是用于测试Java包的覆盖率引导模糊器。
* [JQF](https://github.com/rohanpadhye/JQF)：JQF是一个针对Java的反馈导向模糊测试平台。
* [Mu2](https://github.com/cmu-pasta/mu2)：Mu2是一个用于突变引导模糊测试的模糊测试平台，构建在用于模糊Java程序的JQF平台之上，由CMU程序分析、软件测试和应用实验室开发。
* [Snodge](https://github.com/npryce/snodge)：一个小型、可扩展的Kotlin库，用于随机变异JSON和XML文档、文本和二进制数据，适用于模糊测试。

#### 性能测试

* [Apache JMeter](https://github.com/apache/jmeter)：JMeter开源负载测试工具，用于分析和测量各种服务的性能。
* [NGrinder](https://github.com/naver/ngrinder)：NGrinder是一个压力测试平台，使你能够同时执行脚本创建、测试执行、监控和结果报告生成器，Naver开源。
* [Gatling](https://github.com/gatling/gatling)：Gatling是一个负载测试工具，它正式支持HTTP、WebSocket、SSE和JMS。
* [Grinder](https://grinder.sourceforge.net/)：Grinder是一个Java负载测试框架，可以使用许多负载注入器轻松运行分布式测试。
* [NeoLoad](https://www.tricentis.com/neoload-quick-links)：NeoLoad是一个自动化性能测试平台，适用于企业组织从API到应用程序的持续测试。
* [Lago](https://github.com/twitter-archive/iago)：Lago是一种负载生成工具，可针对给定目标重放生产或合成流量，由Twitter开源。
* [PerfCake](https://github.com/PerfCake/PerfCake)：轻量级性能测试框架和负载生成器。
* [Swingbench](https://github.com/domgiles/swingbench-public)：Swingbench是一款专为Oracle数据库设计的开源负载生成器及基准测试工具。
* [RabbitMQ Performance Testing Tool](https://github.com/rabbitmq/rabbitmq-perf-test)：RabbitMQ性能测试工具，由Broadcom的RabbitMQ团队维护。
* [KoPeMe](https://github.com/DaGeRe/KoPeMe)：KoPeMe是一个用于在Java中进行性能测试的框架。
* [Trombi](https://github.com/mhjort/trombi)：使用Clojure进行负载测试，并以Clojure数据或图表的形式获取结果。
* [JBender](https://github.com/pinterest/jbender)：JBender让你能够轻松地为使用HTTP、Thrift等协议的服务构建负载测试器，由Pinterest开源。
* [Hyperfoil](https://github.com/Hyperfoil/Hyperfoil)：Hyperfoil是面向微服务的分布式基准测试框架，解决了协调遗漏谬误。
* [JUnitPerf](https://github.com/houbb/junitperf)：JUnitPerf是一款为Java开发者设计的性能测试框架。
* [JPerf](https://github.com/AgilData/jperf)：JPerf是一个简单的Java性能和可扩展性测试框架。
* [kraken](https://github.com/OctoPerf/kraken)：Kraken是一个基于Gatling的负载测试IDE。
* [XLT](https://github.com/Xceptance/XLT)：XLT是由Xceptance开发和维护的广泛负载和性能测试工具。
* [Tank](https://github.com/intuit/Tank)：Tank是一个在云环境中运行的负载测试平台，它目前支持Amazon Web界面并利用EC2、S3、CloudWatch(日志/指标)的服务，由Intuit开源。
* [JUnitPerf](https://github.com/noconnor/JUnitPerf)：JUnitPerf为JUnit 4和JUnit 5框架提供了扩展，允许将单元测试扩展为性能评估测试。
* [JPoolRunner](https://github.com/faisalbahadurhu/jpoolrunner)：基于客户端-服务器的线程池系统可扩展性能测试模拟工具。
* [Faban](https://github.com/akara/faban)：Faban是用于开发和运行工作负载驱动程序和性能测试的基础设施。
* [Spark Perf](https://github.com/databricks/spark-perf)：这是Apache Spark 1.0+的性能测试框架，由Databricks开源。
* [MongoDB Performance Test](https://github.com/idealo/mongodb-performance-test)：多线程测试工具，用于测试MongoDB性能，例如吞吐量和延迟。
* [Locust4j](https://github.com/myzhan/locust4j)：Locust4j是一个用Java编写的Locust负载生成器。

#### 基准测试

* [JMH](https://github.com/openjdk/jmh)：JMH是一个Java工具，用于构建、运行和分析用Java和其他针对JVM的语言编写的宏观基准测试，Oracle开源。
* [Caliper](https://github.com/google/caliper)：Caliper是一个用于测量Java代码性能的工具，主要侧重于微基准测试，由Google开源。
* [Criterium](https://github.com/hugoduncan/criterium)：Criterium测量表达式的计算时间，它旨在解决基准测试中的一些缺陷。
* [ScalaMeter](https://github.com/scalameter/scalameter)：JVM平台的微基准测试和性能回归测试框架，由洛桑联邦理工学院开源。
* [Kotlinx Benchmark](https://github.com/Kotlin/kotlinx-benchmark)：Kotlinx Benchmark是一个工具包，用于为用Kotlin编写的多平台代码运行基准测试。
* [Yardstick](https://github.com/gridgain/yardstick)：Yardstick是一个用于编写基准测试的框架，由GridGain开源。
* [Perfidix](https://github.com/sebastiangraf/perfidix)：Perfidix是一个轻量级Java库，使用户能够对源代码进行基准测试，由康斯坦茨大学开源。
* [JLBH](https://github.com/OpenHFT/JLBH)：JLBH是一个可让你对在上下文中运行的代码进行基准测试(而不是在微基准测试中)的工具。

#### 属性测试

* [JUnit Quickcheck](https://github.com/pholser/junit-quickcheck)：JUnit Quickcheck是一个支持在JUnit中编写和运行基于属性的测试的库。
* [Jqwik](https://github.com/jqwik-team/jqwik)：Jqwik的主要目的是将基于属性的测试引入JVM。
* [ScalaCheck](https://github.com/typelevel/scalacheck)：ScalaCheck是一个用Scala编写的库，用于对Scala或Java程序进行基于属性的自动化测试。
* [QuickTheories](https://github.com/quicktheories/QuickTheories)：Java 8基于属性的测试。
* [JetCheck](https://github.com/JetBrains/jetCheck)：JetCheck是一个基于属性的Java 8+测试库，由JetBrains开源。
* [Hedgehog](https://github.com/hedgehogqa/scala-hedgehog)：Hedgehog是一个现代的基于属性的测试系统。
* [QuickPerf](https://github.com/quick-perf/quickperf)：QuickPerf是Java的一个测试库，用于快速评估和改进一些与性能相关的属性。
* [ScalaProps](https://github.com/scalaprops/scalaprops)：Scala基于属性的测试库。
* [Hypothesis Java](https://github.com/HypothesisWorks/hypothesis-java)：Hypothesis是一个专为主流语言设计的基于属性的现代测试系统。

#### 验收测试

* [FitNesse](https://github.com/unclebob/fitnesse)：FitNesse是一个完全集成的独立验收测试框架和wiki，由Uncle Bob开发。
* [Thucydides](https://github.com/thucydides-webtests/thucydides)：Thucydides是一个旨在使编写自动化验收测试变得更容易、更有趣的库。
* [Gwen](https://github.com/shazam/gwen)：Gwen是一个简单的库，允许使用Given/When/Then语法编写验收测试。
* [JLineup](https://github.com/otto-de/jlineup)：JLineup是一个对于网页的自动视觉回归测试非常有用的工具，特别是在持续交付管道中，它可以用作简单的命令行工具或通过REST API控制的小型Web服务。
* [Simple DSL](https://github.com/LMAX-Exchange/Simple-DSL)：Simple DSL是LMAX Exchange使用的一种编写验收测试的风格，旨在平衡人类和机器的可读性。
* [RestFixture](https://github.com/smartrics/RestFixture)：RestFixture是一个FitNesse测试夹具，允许开发人员和/或产品所有者以简单的方式为REST服务编写测试夹具。
* [JWebUnit](https://github.com/JWebUnit/jwebunit)：JWebUnit是一个Java框架，有助于为Web应用程序创建验收测试。

#### 回归测试

* [ARA](https://github.com/Decathlon/ara)：ARA可以预先分析你的非回归测试运行、跟踪和跟踪问题、保留其历史记录，甚至在质量不满足的情况下破坏你的CI构建，从而帮助你对抗回归，由迪卡侬开源。
* [AREX](https://github.com/arextest/arex-agent-java)：Arex是一个围绕利用现实世界数据(即数据库记录、服务负载、缓存项等)进行回归测试的非常简单的原则设计的框架。
* [VisualReview](https://github.com/xebia/VisualReview)：VisualReview的目标是提供高效且人性化的工作流程，用于测试和审查你的Web应用程序布局是否存在任何回归。
* [NoraUi](https://github.com/NoraUi/NoraUi)：用户界面的非回归自动化。
* [Diffy](https://github.com/opendiffy/diffy)：Diffy使用并排运行新代码和旧代码的实例来发现服务中的潜在错误，由Twitter开源。
* [Gojira](https://github.com/flipkart-incubator/gojira)：Gojira是一个基于记录和回放的回归测试工具，由Flipkart开源。
* [Unlogged Java SDK](https://github.com/unloggedio/unlogged-sdk)：Unlogged Java SDK支持以二进制格式记录代码执行。
* [Drill4J](https://github.com/Drill4J/drill4j)：Drill4J是一款开源工具，用于识别测试差距并减少回归测试所花费的时间。

#### A/B测试

* [Wasabi](https://github.com/intuit/wasabi)：Wasabi A/B测试服务是一个实时、企业级、100% API驱动的项目，由Intuit开发。
* [Proctor](https://github.com/indeedeng/proctor)：Proctor是一个用Java编写的A/B测试框架，由Indeed开发并大量使用。
* [Apache Unomi](https://github.com/apache/unomi)：Unomi存储用户个人资料信息，主要用于为A/B测试和个性化提供后端服务器，由Jahia开源。
* [Touchstone](https://github.com/taoensso/touchstone)：Touchstone尝试为任何Clojure Web应用程序带来极其简单、高效的拆分测试。
* [Sixpack Java](https://github.com/sixpack/sixpack-java)：Sixpack A/B测试框架的Java客户端。
* [PlanOut4J](https://github.com/Glassdoor/planout4j)：Facebook PlanOut A/B测试系统的Java端口，具有附加功能。
* [Vamp](https://github.com/CircleCI-Archived/vamp)：Vamp是一款非常出色的微服务平台，核心功能包括平台无关的微服务DSL、轻松的A-B测试/金丝雀发布，以及一个深度可扩展的指标引擎。

#### 流量回放

* [JVM Sandbox Repeater](https://github.com/alibaba/jvm-sandbox-repeater)：JVM Sandbox Repeater是阿里开源的基于JVM-Sandbox的录制/回放通用解决方案。
* [Conan](https://github.com/tal-tech/conan)：柯南平台开源版本，为用户提供流量回放全流程解决方案，由好未来开源。
* [Moonbox](https://github.com/vivo/MoonBox)：Moonbox是基于JVM Sandbox Repeater重新开发的一款流量回放平台产品，由Vivo开源。
* [MagicOTP](https://github.com/alibaba/online-test-platform)：MagicOTP是一个开源的线上测试平台，思想是通过回放大批量线上真实请求，并结合规则验证的形式对服务返回的结果进行校验，由阿里开源。
* [Wiresham](https://github.com/abstracta/wiresham)：简单的TCP Mock工具，用于重放tcpdump或Wireshark捕获的服务或客户端流量。
* [HRRS](https://github.com/vy/hrrs)：HRRS是一组工具，你可以利用它在使用Java 8或更高版本编写的Java EE和Spring Web应用程序中记录、转换和重放HTTP请求。

#### 契约测试

* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [Spring Cloud Contract](https://github.com/spring-cloud/spring-cloud-contract)：Spring对消费者驱动契约的支持。
* [Contract Test Runner](https://github.com/wso2/contract-test-runner)：用于契约测试的Java库，由WSO2开源。
* [Specmatic](https://github.com/znsio/specmatic)：Specmatic通过利用API规范作为可执行合约来体现契约驱动开发(CDD)。
* [Cofoja](https://github.com/nhatminhle/cofoja)：Cofoja是一种Java契约编程框架和测试工具，它使用注解处理和字节码检测来提供运行时检查。

#### 渗透测试

* [PETEP](https://github.com/Warxim/petep)：PETEP是一款开源Java应用程序，用于使用TCP/UDP代理进行流量分析和修改。
* [BerylEnigma](https://github.com/ffffffff0x/BerylEnigma)：BerylEnigma是一款CTF+渗透测试工具包，主要实现一些常见的加密编码功能。
* [Cobalt Strike](https://www.cobaltstrike.com/)：Cobalt Strike是一款基于Java的渗透测试神器。
* [TrackRay](https://github.com/iSafeBlue/TrackRay)：溯光是一个开源渗透测试框架，框架自身实现了漏洞扫描功能，集成了知名安全工具：Metasploit、Nmap、Sqlmap、AWVS、Burpsuite等。
* [Jackhammer](https://github.com/olacabs/jackhammer)：Jackhammer是一款协作工具，旨在弥合安全团队与开发团队、QA团队之间的差距，并成为TPM的促进者，以了解和跟踪投入生产的代码的质量。
* [WS Attacker](https://github.com/RUB-NDS/WS-Attacker)：WS Attacker是一个用于Web服务渗透测试的模块化框架，由波鸿鲁尔大学开发。
* [DELTA](https://github.com/seungsoo-lee/DELTA)：DELTA是一个渗透测试框架，用于为各种测试用例重生成已知的攻击场景。

#### 快照测试

* [ApprovalTests](https://github.com/approvals/ApprovalTests.Java)：Java的ApprovalTest验证库。
* [Java Snapshot Testing](https://github.com/origin-energy/java-snapshot-testing)：Java的Facebook风格快照测试。
* [Selfie](https://github.com/diffplug/selfie)：快照测试是记录和指定系统及其组件行为的最快且最精确的机制。
* [Snapshot4s](https://github.com/siriusxm/snapshot4s)：Snapshot4s自动化了编写和更新测试的过程，减轻了开发人员的维护负担。

#### 断言库

* [AssertJ](https://github.com/assertj/assertj)：AssertJ提供了一组丰富且直观的强类型断言，用于单元测试。
* [JSONAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest是一个匹配器库，可以将其组合起来以在测试中创建灵活的意图表达。
* [Spotify Hamcrest](https://github.com/spotify/java-hamcrest)：这是一个用有用的匹配器扩展Hamcrest匹配库的库集合，由Spotify开源。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java Bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Deepdive是Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：FEST-Assert为断言提供了流式的接口。
* [Expekt](https://github.com/winterbe/expekt)：Expekt是一个基于Kotlin的BDD断言库，灵感源自Chai.js。
* [Assertk](https://github.com/assertk-org/assertk)：Assertk是一个流式的Kotlin断言库，灵感来自AssertJ。
* [Kluent](https://github.com/markusamshove/Kluent)：Kluent是一个专门为Kotlin编写的流式断言库。
* [JSON Assert](https://github.com/marcingrzejszczak/jsonassert)：简单的库，提供流式的JSON断言接口。
* [AssertJ DB](https://github.com/assertj/assertj-db)：AssertJ DB提供断言来测试数据库中的值。
* [ArchUnit](https://github.com/TNG/ArchUnit)：ArchUnit是一个免费、简单且可扩展的库，用于检查Java代码的架构。
* [Confidence](https://github.com/saynotobugsorg/confidence)：Confidence是一个声明式Java断言框架。
* [Power Assert](https://github.com/jkschneider/java-power-assert)：Power Assert通过条件评估过程中产生的值的信息来增强断言失败，并以易于理解的形式呈现它们。
* [Visible Assertions](https://github.com/rnorth/visible-assertions)：JUnit断言的替代方案，为你的测试提供更有洞察力的日志叙述。
* [LogCapture](https://github.com/jsalinaspolo/logcapture)：LogCapture是一个用于断言日志消息的测试库。
* [Log Capture](https://github.com/dm-drogeriemarkt/log-capture)：日志消息的简单断言。
* [Atrium](https://github.com/robstoll/atrium)：Atrium是一个针对Kotlin的开源多平台期望/断言库，支持JVM、JS和Android。
* [Truthish](https://github.com/varabyte/truthish)：受Google Truth启发的测试API，但从头开始用Kotlin重写。
* [ModelAssert](https://github.com/webcompere/model-assert)：用于模型数据的断言库。
* [Valid4j](https://github.com/valid4j/valid4j)：Java的简单断言和验证库。
* [DataSource-Assert](https://github.com/ttddyy/datasource-assert)：DataSource-Assert为DataSource提供断言API以验证查询执行。
* [Strikt](https://github.com/robfletcher/strikt)：Strikt是Kotlin的断言库，旨在与JUnit、Minutest、Spek或KotlinTest等测试运行器一起使用。
* [NDD Check4J](https://gitlab.com/ndd-oss/java/ndd-check4j)：NDD Check4J通过流式或简洁的API提供简单的参数检查。
* [LambSpec](https://github.com/pholser/lambspec)：适用于Java 8的类似RSpec的断言库。
* [Jcabi-Matchers](https://github.com/jcabi/jcabi-matchers)：一些方便的Hamcrest匹配器，主要用于XPath与XHTML以及JAXB中的字段。
* [Shazamcrest](https://github.com/shazam/shazamcrest)：Shazamcrest是一个扩展Hamcrest功能的库。
* [ReCheck](https://github.com/retest/recheck)：ReCheck是一个功能齐全的开源测试工具，允许替换手动断言并立即检查所有内容。

#### Mock框架

* [Mockito](https://github.com/mockito/mockito)：Mockito是Java中最流行的单元测试Mock框架。
* [PowerMock](https://github.com/powermock/powermock)：PowerMock是一个框架，它扩展了EasyMock等其他Mock库，使其具有更强大的功能。
* [TestableMock](https://github.com/alibaba/testable-mock)：TestableMock是一款轻量Mock工具，由阿里开源。
* [EasyMock](https://github.com/easymock/easymock)：EasyMock是一个Java库，它提供了一种在单元测试中使用Mock对象的简单方法。
* [Mockk](https://github.com/mockk/mockk)：用于Kotlin的Mock框架。
* [JMock](https://github.com/jmock-developers/jmock-library)：JMock是一个支持使用Mock对象进行Java代码测试驱动开发的库。
* [ScalaMock](https://github.com/scalamock/scalamock)：ScalaMock是原生的Scala Mock框架。
* [JMockit](https://github.com/jmockit/jmockit1)：JMockit是用于集成测试、Mock、伪造和代码覆盖率的高级Java库。
* [Jukito](https://github.com/ArcBees/Jukito)：JUnit、Guice和Mockito的强强联手。
* [Mokkery](https://github.com/lupuuss/Mokkery)：Kotlin Multiplatform的Mock库，易于使用、无样板且由编译器插件驱动。
* [Expectations](https://github.com/clojure-expectations/expectations)：Expectations是一个经典的期望库。
* [Mockative](https://github.com/mockative/mockative)：使用KSP实现Kotlin/Native和Kotlin Multiplatform的Mock。
* [Mockrunner](https://github.com/mockrunner/mockrunner)：Mockrunner是用于企业级应用程序的Mock工具。
* [Bond](https://github.com/circleci/bond)：Bond是一个监视和存根库，主要用于测试。

#### 接口Mock

* [Moco](https://github.com/dreamhead/moco)：Moco是一个易于设置的存根框架。
* [WireMock](https://github.com/wiremock/wiremock)：WireMock是一种流行的API Mock测试开源工具。
* [Microcks](https://github.com/microcks/microcks)：Microcks是用于API Mock和测试的开源云原生工具。
* [MockServer](https://github.com/mock-server/mockserver)：MockServer可以轻松模拟通过HTTP或HTTPS与用Java、JavaScript和Ruby编写的客户端集成的任何系统。
* [MockServer NeoLight](https://github.com/xdev-software/mockserver-neolight)：对废弃的MockServer项目进行轻量级重写，重点关注简单性、可维护性和测试容器。
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver)：用于测试HTTP客户端的可编写脚本的Web服务器，由Square开源。
* [AnyMock](https://github.com/duxiaoman/AnyMock)：AnyMock是一个通用接口Mock平台，提供Mock配置和模拟响应的服务，由度小满开源。
* [Hoverfly](https://github.com/SpectoLabs/hoverfly-java)：Hoverfly的Java绑定，Hoverfly是一个允许你模拟HTTP服务的代理。
* [Imposter](https://github.com/imposter-project/imposter-jvm-engine)：Imposter是REST API、OpenAPI规范、SOAP Web Services、Salesforce和HBase API的Mock服务器。
* [Flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的，由LinkedIn开源。
* [Mockey](https://github.com/clafonta/Mockey)：Mockey是一个用于测试通过HTTP的应用程序交互的工具，重点是测试Web服务，特别是使用XML、JSON和HTML的Web或原生应用程序。
* [SMockin](https://github.com/matthewgallina/smockin)：SMockin是一种用于动态模拟API端点、S3存储桶和电子邮件帐户的开发工具。
* [Betamax](https://github.com/betamaxteam/betamax)：Betamax是一个用于在测试中模拟外部HTTP资源的工具，该项目的灵感来自于Ruby的VCR库。
* [Stubby4j](https://github.com/azagniotov/stubby4j)：HTTP/1.1、HTTP/2和WebSocket存根服务器，用于在Docker和非容器化环境中存根分布式Web服务以进行契约测试。
* [HttpMocker](https://github.com/speekha/httpmocker)：HttpMocker是一个非常轻量的Kotlin库，允许依赖OkHttp或Ktor客户端库来模拟HTTP调用。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [Restito](https://github.com/mkotsur/restito)：Restito是一个用于验证代码与REST服务交互的工具。
* [MockNet](https://github.com/5A59/MockNet)：MockNet用于快速搭建本地服务器，方便开发和测试接口。
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP)：DeepfakeHTTP是一个使用HTTP转储作为响应源的Web服务器。
* [Jadler](https://github.com/jadler-mocking/jadler)：Jadler是一个Java库，用于以声明方式存根和模拟HTTP服务器和资源。
* [SpecMock](https://github.com/specmock/specmock)：SpecMock提供了各种规格的Mock Server，提供轻量、快速且易于使用的体验。
* [ZeroMock](https://github.com/tonivade/zeromock)：零依赖的模拟HTTP Server。
* [OKHttp Client Mock](https://github.com/gmazzo/okhttp-client-mock)：一个简单的OKHttp客户端Mock，使用可编程请求拦截器。
* [OkReplay](https://github.com/airbnb/okreplay)：OkReplay旨在通过拦截应用程序发起的HTTP连接并重放之前记录的响应，由Airbnb开发。
* [RESTMock](https://github.com/andrzejchm/RESTMock)：RESTMock是一个建立在MockWebServer之上的库，它允许你指定Hamcrest匹配器来匹配HTTP请求并指定要返回的响应。
* [Mokksy](https://github.com/mokksy/ai-mocks)：Mokksy是一个用Kotlin和Ktor构建的Mock HTTP服务器。
* [Ersatz](https://github.com/cjstehno/ersatz)：Ersatz是一个HTTP客户端测试工具，允许以灵活的方式配置请求/响应预期。
* [MockHttpServer](https://github.com/kristofa/mock-http-server)：MockHttpServer用于促进依赖外部HTTP服务的Java应用程序的集成测试。
* [Java Httpbin](https://github.com/gaul/java-httpbin)：基于Java的HTTP服务器，可让你使用httpbin.org的端点在本地测试HTTP客户端、重试逻辑、流行为、超时等。
* [Mock API](https://github.com/shanbay/mock-api)：适用于Android的JSON API Mock框架。
* [OkHttp JSON Mock](https://github.com/mirrajabi/okhttp-json-mock)：OkHttp JSON Mock可以帮助你在短短几步内Mock使用OkHttp、Retrofit的JSON格式的数据。
* [Moclojer](https://github.com/moclojer/moclojer)：Moclojer是一个简单高效的HTTP Mock服务器，可帮助你Mock用于开发、测试和原型设计的API。
* [Retromock](https://github.com/infinum/Retromock)：用于Mock Retrofit服务中的响应的库，由Infinum开源。
* [Mockinizer](https://github.com/donfuxx/Mockinizer)：Mockinizer帮助Android开发者通过MockWebServer快速模拟部分Web API响应，构建使用OkHttpClient/RetroFit的Web API调用应用。
* [Mockery](https://github.com/VictorAlbertos/Mockery)：Android和Java库，用于模拟和测试网络层，内置支持Retrofit。
* [Play MockWS](https://github.com/leanovate/play-mockws)：Play MockWS是一款适用于Play Framework的Mock WS客户端。
* [V-Mock](https://gitee.com/vtDev/v-mock)：V-Mock是一个小巧的接口响应Mock系统。

#### Mock库

* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ Java AMQP-Client的Mock库。
* [S3Mock](https://github.com/adobe/S3Mock)：S3Mock是一个轻量级服务器，它实现了部分Amazon S3 API，由Adobe开源。
* [S3Mock](https://github.com/findify/s3mock)：S3Mock是一个实现AWS S3 API的Web服务，可用于使用S3对代码进行本地测试。
* [S3Ninja](https://github.com/scireum/s3ninja)：S3Ninja模拟Amazon S3 API以用于开发和测试目的。
* [LocalS3](https://github.com/Robothy/local-s3)：LocalS3是用于测试和本地开发的Amazon S3 Mock服务。
* [GreenMail](https://github.com/greenmail-mail-test/greenmail)：GreenMail是一个开源、直观且易于使用的电子邮件服务器测试套件。
* [DaggerMock](https://github.com/fabioCollini/DaggerMock)：用于轻松覆盖Dagger 2对象的JUnit Rule。
* [CouchbaseMock](https://github.com/couchbase/CouchbaseMock)：CouchbaseMock是一个测试Couchbase服务器。
* [Keycloak Mock](https://github.com/TNG/keycloak-mock)：提供Keycloak测试支持的Java库。
* [gRPC Mock](https://github.com/Fadelis/grpcmock)：一个gRPC Java测试工具，可轻松Mock gRPC服务端点以进行集成测试或单元测试。
* [GwtMockito](https://github.com/google/gwtmockito)：GwtMockito是用于GWT应用程序的测试工具，由Google开源。
* [Mock OAuth2 Server](https://github.com/navikt/mock-oauth2-server)：可编写脚本/可自定义的Web服务器，用于使用OAuth2/OpenID Connect测试HTTP客户端或依赖于正在运行的OAuth2服务器的应用程序。
* [Thrift Mock](https://github.com/didi/thrift-mock)：Thrift Mock是用于Thrift服务的轻量级Java单元测试库，由滴滴开源。
* [Spring Data Mock](https://github.com/mmnaseri/spring-data-mock)：Spring Data Repository的Mock工具。
* [MockFtpServer](https://github.com/dx42/MockFtpServer)：MockFtpServer项目提供模拟/虚拟FTP服务器实现来测试FTP客户端代码。
* [AWS Mock](https://github.com/treelogic-swe/aws-mock)：使用与语言无关的AWS Mock轻松自动地测试基本AWS服务。

#### 数据Mock

* [Java Faker](https://github.com/DiUS/java-faker)：Java Faker是Ruby的stympy/faker gem的Java端口，用于生成假数据。
* [Instancio](https://github.com/instancio/instancio)：Instancio是一个Java库，可以自动为单元测试创建和填充对象。
* [JUnit DataProvider](https://github.com/TNG/junit-dataprovider)：DataProvider类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：Datafaker是一个用于Java和Kotlin生成虚假数据的库。
* [EasyRandom](https://github.com/j-easy/easy-random)：EasyRandom是一个生成随机Java对象的库。
* [MockNeat](https://github.com/nomemory/mockneat)：Mockneat是一个用Java编写的任意数据生成器开源库。
* [jFairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [Fakeit](https://github.com/thisisqubika/fakeit)：该库是Ruby Faker的移植版本。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：Jmockdata是一款实现模拟Java类或对象的实例化并随机初始化对象的数据的工具框架。
* [Kotlin Faker](https://github.com/serpro69/kotlin-faker)：用Kotlin编写的流行Ruby faker gem的移植版。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：Fixture Monkey旨在轻松生成可控的任意实例，它允许你在多个测试中重复使用实例的相同配置，由Naver开源。
* [Specmonstah](https://github.com/reifyhealth/specmonstah)：Specmonstah可让你编写清晰、简洁且易于维护的测试夹具。
* [KotlinFixture](https://github.com/appmattus/kotlinfixture)：一种根据约束非确定性思想生成明确定义但本质上随机的输入的工具。
* [Burst](https://github.com/square/burst)：Burst是用于不同测试数据的单元测试库，由Square开源。
* [Nyaya](https://github.com/japgolly/nyaya)：Nyaya是一个Scala/Scala.JS库，用于使用随机数据测试属性。
* [Log Synth](https://github.com/tdunning/log-synth)：Log Synth的主要用途是根据指定的模式生成数据。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。
* [Beanmother](https://github.com/keepcosmos/beanmother)：Beanmother有助于创建各种对象，可以非常轻松地使用用于测试的夹具。
* [Common Random](https://github.com/yindz/common-random)：Common Random是一个简单易用的随机数据生成器。
* [JFactory](https://github.com/leeonky/jfactory)：JFactory是通过工厂方法创建具有某些默认属性测试数据的工具库。
* [DataHelix](https://github.com/finos/datahelix)：DataHelix可以快速生成丰富且真实的数据用于模拟和测试，由金融科技基金会开源。
* [Fixture Factory](https://github.com/six2six/fixture-factory)：Fixture Factory是一个帮助开发人员快速构建和组织假对象以进行单元测试的工具。
* [Wordnet Random Name](https://github.com/kohsuke/wordnet-random-name)：用于测试的人类友好随机名称生成器。
* [Podam](https://github.com/mtedone/podam)：Podam是一个Java测试工具，可以用虚构的数据自动填充POJO。
* [RandomData](https://github.com/ZieIony/RandomData)：RandomData自动用生成的随机名称、数字、图像等填充对象。
* [AutoParams](https://github.com/AutoParams/AutoParams)：AutoParams是一个专为Java参数化测试而设计的任意测试数据生成器。
* [Java Random](https://github.com/merkle-open/java-random)：Java Random提供了一种通用机制来创建Java对象的随机测试虚拟对象。
* [JFixture](https://github.com/FlexTradeUKLtd/jfixture)：JFixture是一个自动填充测试数据的Java库。
* [JavaFixture](https://github.com/Nylle/JavaFixture)：JavaFixture旨在将AutoFixture的极致易用性引入Java世界。
* [DataFactory](https://github.com/andygibson/datafactory)：DataFactory能让你轻松生成测试数据。
* [Mock.java](https://gitee.com/ForteScarlet/Mock.java)：这是一个仿照Mock.js语法的Java语言使用的假数据生成工具框架。
* [Java Test Data Generator](https://github.com/binarywang/java-testdata-generator)：Java实现的各种随机测试数据生成器，包括身份证号码、银行卡号、姓名、汉字、手机号、电子邮箱地址等。
* [Test Data Supplier](https://github.com/sskorol/test-data-supplier)：该仓库包含TestNG DataProvider包装器，有助于以更灵活的方式提供测试数据。
* [Data Factory](https://github.com/houbb/data-factory)：Data Factory用于根据对象随机自动生成初始化信息。
* [Elmyr](https://github.com/xgouchet/Elmyr)：Elmyr是一个Kotlin库，提供生成随机值的工具。
* [EvoSQL](https://github.com/SERG-Delft/evosql)：EvoSQL是一种自动为SQL查询生成测试数据的工具，由代尔夫特理工大学开源。
* [RandomJson](https://github.com/mangatmodi/RandomJson)：RandomJson提供Kotlin/Java库来创建随机JSON字符串。
* [JSON Data Generator](https://github.com/everwatchsolutions/json-data-generator)：一个强大、通用的流式随机JSON数据生成器。
* [JSON Data Generator](https://github.com/vincentrussell/json-data-generator)：JSON Data Generator可帮助你构建测试所需的JSON数据。
* [Nomen est Omen](https://github.com/igr/nomen-est-omen)：这个Java库有助于生成一些随机名称，你可以将它们用于某些唯一的ID或密码。
* [Model Citizen](https://github.com/mguymon/model-citizen)：Model Citizen是一个基于注解的Java模型工厂。
* [Test Arranger](https://github.com/ocadotechnology/test-arranger)：将测试数据排列为完全填充的对象。
* [Datagen](https://github.com/qala-io/datagen)：用于生成随机数据(数字、字符串、日期)的Java库-以便于随机测试。
* [Fabricator](https://github.com/azakordonets/fabricator)：Fabricator是随机字符串、数字等的极简生成器，有助于减少单调性。
* [Make It Easy](https://github.com/npryce/make-it-easy)：一个微型框架，可轻松用Java编写测试数据构建器。
* [JMock](https://github.com/xcancloud/JMock)：JMock是一个用Java实现的高性能数据生成和仿真组件库。
* [Faker](https://github.com/blocoio/faker)：Faker Ruby Gem的一个Kotlin和Android兼容移植版本。
* [Ranger](https://github.com/smartcat-labs/ranger)：Ranger是一个上下文数据生成器，用于为集成测试生成合理数据或在数据库中使用。
* [FactoryPal](https://github.com/mgonto/factory_pal)：FactoryPal是一个Scala框架，可让你创建对象作为测试数据。
* [Randomizer](https://github.com/android-Infoedge/randomizer)：基于注解的库，用于生成随机数据。
* [Random Data Generator](https://github.com/DanielaSfregola/random-data-generator)：用于测试目的生成随机数据的库。
* [Build Test Data](https://github.com/longwa/build-test-data)：通过自动检查约束，轻松创建测试数据。
* [Pairwise](https://github.com/RetailMeNot/pairwise)：Pairwise是一个用于生成数据集的开源库，最常用于测试。
* [Spock Genesis](https://github.com/Bijnagte/spock-genesis)：Spock Genesis提供了各种继承自Generator并满足该接口的类。
* [Instantiator](https://github.com/sockeqwe/Instantiator)：Instantiator可以为你创建任意类的实例，让你可以专注于编写测试，而无需花费时间和精力设置测试数据。
* [Genesis](https://github.com/ThisIsLibra/genesis)：Genesis是一个框架，允许用户创建自己的测试用例，并在生成过程中进行混淆处理。
* [Arbitrater](https://github.com/tyro/arbitrater)：Arbitrater是一个通过反射创建任意类实例的库。

#### BDD框架

* [Cucumber](https://github.com/cucumber/cucumber-jvm)：Cucumber是一个支持行为驱动开发(BDD)的工具。
* [Karate](https://github.com/karatelabs/karate)：Karate是将API测试自动化、Mock、性能测试甚至UI自动化整合到一个统一框架中的开源工具，由Intuit开源。
* [Spek](https://github.com/spekframework/spek)：Spek是Kotlin的规范框架。
* [Serenity BDD](https://github.com/serenity-bdd/serenity-core)：Serenity BDD是一个旨在使编写自动化验收测试变得更容易、更有趣的库。
* [Concordion](https://github.com/concordion/concordion)：Concordion是一个可执行规范的开源运行程序，可创建丰富的实时文档。
* [BDD Security](https://github.com/iriusrisk/bdd-security)：BDD Security是一个安全测试框架，它使用行为驱动开发概念来创建自我验证的安全规范。
* [JBehave](https://github.com/jbehave/jbehave-core)：JBehave是一个适用于Java和所有JVM语言的BDD框架。
* [JGiven](https://github.com/TNG/JGiven)：JGiven是一个开发人员友好且实用的Java BDD工具。
* [Chorus](https://github.com/Chorus-bdd/Chorus)：Chorus是一个BDD测试解释器，具有用于测试分布式架构的额外功能。
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Lambda Behave是Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：Spectrum受到BDD框架Jasmine和RSpec的启发，将它们的表达语法和功能风格引入Java测试。
* [Specs2](https://github.com/etorreborre/specs2)：Specs2是一个用于在Scala中编写可执行软件规范的库。
* [J8Spec](https://github.com/j8spec/j8spec)：J8Spec是一个库，允许用Java编写的测试遵循RSpec和Jasmine引入的BDD风格。
* [Oleaster](https://github.com/mscharhag/oleaster)：Oleaster允许你像编写Jasmine测试一样编写JUnit测试。
* [Wakamiti](https://github.com/iti-ict/wakamiti)：Wakamiti是一款受Cucumber启发的自动化测试工具，专注于使用自然语言进行黑盒测试，由瓦伦西亚理工大学开源。
* [Cuppa](https://github.com/cuppa-framework/cuppa)：Cuppa是Java 8的测试框架，它使编写测试变得高效且有趣。
* [Narrative](https://github.com/tim-group/narrative)：一个使用流式Java构建行为驱动测试的框架。
* [YatSpec](https://github.com/bodar/yatspec)：YatSpec是一个BDD测试框架。
* [Tiger](https://github.com/gematik/app-Tiger)：Tiger是一个用于接口驱动的BDD黑盒测试的框架。
* [BDD For All](https://github.com/Accenture/bdd-for-all)：灵活且易用的库，使你的BDD团队能够轻松协作，同时推动自动化、透明度和报告，由Accenture开源。

#### 测试生成器

* [Auto Unit Test Case Generator](https://github.com/traas-stack/auto-unit-test-case-generator)：Auto Unit Test Case Generator自动生成Java的高级代码覆盖JUnit测试套件，在蚂蚁中广泛使用。
* [Tcases](https://github.com/Cornutum/tcases)：Tcases是基于模型的测试用例生成器。
* [JCUnit](https://github.com/dakusui/jcunit)：JCUnit是一个基于模型的开源测试框架，由组合交互测试技术提供支持。
* [EvoMaster](https://github.com/WebFuzzing/EvoMaster)：EvoMaster是第一个开源AI驱动工具，可为Web/企业应用程序自动生成系统级测试用例。
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
* [GramTest](https://github.com/codelion/gramtest)：GramTest允许你根据任意用户定义的语法生成测试用例。
* [Testrecorder](https://github.com/almondtools/testrecorder)：Testrecorder通过记录正在运行的系统的交互，提供了一种生成特征单元测试的简单方法。

#### 参数化测试

* [Burst](https://github.com/cashapp/burst)：Burst是一个用于参数化单元测试的库。
* [JUnitParams](https://github.com/Pragmatists/JUnitParams)：JUnitParams项目为JUnit添加了一个新的运行器，提供了更容易、更易读的参数化测试。
* [TestParameterInjector](https://github.com/google/TestParameterInjector)：TestParameterInjector是JUnit 4和JUnit 5测试运行程序，它针对字段/参数值的不同组合运行其测试方法，由Google开源。
* [JUnit 5 FormattedSource](https://github.com/mikemybytes/junit5-formatted-source)：该库可以通过编写参数化测试的新方法对JUnit 5进行扩展。
* [JUnit JSON Params](https://github.com/joshka/junit-json-params)：JUnit 5 JSON参数化测试库。
* [Spockito](https://github.com/tools4j/spockito)：一个简单的Java库，用于以类似表格的方式定义数据。
* [EasyTest](https://github.com/EaseTech/easytest-core)：EasyTest是一个用于在Java中执行数据驱动测试的库。
* [TableTest](https://github.com/nchaugen/tabletest)：TableTest通过简洁的表格格式扩展了JUnit用于数据驱动测试。

#### Selenium库

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库，由ThoughtWork开源。
* [Selenium Jupiter](https://github.com/bonigarcia/selenium-jupiter)：Selenium Jupiter是一个开源Java库，它实现了用于开发Selenium WebDriver测试的JUnit 5扩展。
* [Zalenium](https://github.com/zalando/zalenium)：Zalenium是一个灵活且可扩展的基于容器的Selenium Grid，具有视频录制、实时预览、基本身份验证和仪表板，由Zalando开源。
* [Selenide](https://github.com/selenide/selenide)：Selenide是一个用Java编写易于阅读和易于维护的自动化测试的框架，由Codeborne开发。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：WebDriverManager是一个开源Java库，用于对Selenium WebDriver所需的驱动程序(例如chromedriver、geckodriver、msedgedriver等)进行管理。
* [jBrowserDriver](https://github.com/hollingsworthd/jBrowserDriver)：与Selenium WebDriver规范兼容的可编程、可嵌入的Web浏览器驱动程序。
* [Html Elements](https://github.com/yandex-qatools/htmlelements)：Html Elements是一个Java框架，提供在网页测试中与网页元素交互的易于使用的方式，由Yandex开源。
* [FluentSelenium](https://github.com/SeleniumHQ/fluent-selenium)：FluentSelenium是Selenium 2+的包装器，添加了用于浏览器的流式界面样式，可以更轻松、更快速地编写Web UI测试。
* [Frameworkium](https://github.com/Frameworkium/frameworkium-core)：Frameworkium是用于Web、应用程序和API测试的快速启动自动化框架。
* [Aquality Selenium](https://github.com/aquality-automation/aquality-selenium-java)：Aquality Selenium是一个基于Selenium WebDriver工具构建的库，允许使用Web浏览器实现自动化工作。
* [Conductor](https://github.com/conductor-framework/conductor)：Selenium WebDriver API的包装器。
* [aShot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具，截图、裁剪、美化、比较。
* [Darcy](https://github.com/darcy-framework)：Darcy是一个开源Java 8框架，用于使用声明式、与自动化库无关的DSL将用户界面建模为页面对象，由RedHat开源。
* [HtmlUnitDriver](https://github.com/SeleniumHQ/htmlunit-driver)：HtmlUnitDriver是HtmlUnit无头浏览器的WebDriver兼容驱动程序。
* [Shutterbug](https://github.com/assertthat/selenium-shutterbug)：Selenium Shutterbug是一个用Java编写的实用程序库，用于使用Selenium WebDriver制作屏幕截图。
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
* [iOS Driver](https://github.com/ios-driver/ios-driver)：Selenium服务器，用于测试iOS上的原生、混合和Web应用。
* [Inproctester](https://github.com/aharin/inproctester)：Inproctester提供HtmlUnit和WebDriver扩展以实现进程内Web应用程序测试，由ThoughtWorks开源。
* [WebDriver Extensions](https://github.com/webdriverextensions/webdriverextensions)：WebDriver Extensions旨在简化基于Java的Selenium/WebDriver测试。
* [Coteafs Selenium](https://github.com/WasiqB/coteafs-selenium)：Java中的Selenium WebDriver包装框架，用于干净且可维护的测试。
* [Playwrightium](https://github.com/britka/playwrightium)：Playwrightium是Webdriver接口与Playwright Java内部的实现。
* [Selenium Grid Extensions](https://github.com/sterodium/selenium-grid-extensions)：Selenium Grid扩展，用于更好的UI测试。
* [VertxUI](https://github.com/nielsbaloe/vertxui)：纯100% Java响应式客户端网页，具有POJO流量、JUnit GUI测试、声明式模型视图、自动浏览器重新加载等。
* [Docker Maven Chrome](https://github.com/markhobson/docker-maven-chrome)：用于Java自动化UI测试的Docker镜像。
* [Kdriver](https://github.com/cdpdriver/kdriver)：Kdriver是一个极快、协程优先、无法检测的Kotlin网页抓取/浏览器自动化库。

#### Cucumber库

* [Tzatziki](https://github.com/Decathlon/tzatziki)：该项目是一组现成的Cucumber步骤的集合，通过专注于由外向内的测试策略，可以轻松实现TDD Java微服务，由迪卡侬开源。
* [Courgette JVM](https://github.com/prashant-ramcharan/courgette-jvm)：Courgette JVM是Cucumber的扩展，增加了在功能级别或场景级别并行运行Cucumber测试的功能。
* [Cukedoctor](https://github.com/rmpestano/cukedoctor)：基于Cucumber JSON执行输出，使用Cucumber和Asciidoctor的BDD活动文档。
* [Cukes](https://github.com/ctco/cukes)：用于测试RESTful Web服务的Cucumber DSL。
* [Akita](https://github.com/alfa-laboratory/akita)：基于Cucumber和Selenide的BDD测试步骤库。
* [Cluecumber](https://github.com/trivago/cluecumber)：针对Cucumber BDD和Karate JSON结果格式的清晰简洁的JVM和Maven报告。
* [Cucumber Reporting](https://github.com/mkolisnyk/cucumber-reports)：Cucumber Reporting库是一组Cucumber扩展，用于生成额外的HTML报告并扩展现有的Cucumber运行器功能。
* [Cucumber Reporting](https://github.com/damianszczepanik/cucumber-reporting)：这是一个Java报告发布器，主要用于在Jenkins构建服务器上发布Cucumber报告。
* [Serenity Cucumber Starter](https://github.com/serenity-bdd/serenity-cucumber-starter)：Serenity BDD和Cucumber JVM的骨架项目。
* [Maven Cucumber Reporting](https://github.com/damianszczepanik/maven-cucumber-reporting)：用于Cucumber报告的Maven Mojo。
* [Cucable Maven Plugin](https://github.com/trivago/cucable-plugin)：Cucable是适用于Cucumber场景的Maven插件，可简化细粒度和高效的并行测试运行。
* [Cucumber JVM Parallel Plugin](https://github.com/temyers/cucumber-jvm-parallel-plugin)：Maven插件帮助并行运行Cucumber功能。
* [Cucumber Sandwich](https://github.com/damianszczepanik/cucumber-sandwich)：该项目可以动态生成漂亮的Cucumber HTML报告。
* [Pandaria](https://github.com/JakimLi/pandaria)：Pandaria是基于Cucumber JVM编写的DSL，旨在简化HTTP/GraphQL API测试，所有Cucumber功能依然有效。

#### 自动化框架

* [Selenium](https://github.com/SeleniumHQ/selenium)：Selenium是一个伞式项目，封装了各种支持Web浏览器自动化的工具和库，由ThoughtWork开源。
* [Playwright](https://github.com/microsoft/playwright-java)：Playwright是一个Java库，可通过单个API实现Chromium、Firefox和WebKit的自动化，由Microsoft开源。
* [F2etest](https://github.com/alibaba/f2etest)：F2etest是一个面向前端、测试、产品等岗位的多浏览器兼容性测试整体解决方案，由阿里开源。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [JDI Light](https://github.com/jdi-testing/jdi-light)：JDI Light是一个功能强大的测试自动化框架，有助于使你的测试快速、可持续，并提供明显且可预测的测试运行结果，由EPAM开源。
* [ZeroCode](https://github.com/authorjapps/zerocode)：ZeroCode是一个社区开发的免费开源自动化测试框架，用于微服务API、Kafka和负载测试。
* [Carina](https://github.com/zebrunner/carina)：Carina是一个基于Java的测试自动化框架。
* [Geb](https://github.com/geb/geb)：Geb是一种浏览器自动化解决方案，它汇集了WebDriver的强大功能、jQuery内容选择的优雅性、页面对象建模的稳健性以及Groovy语言的表现力。
* [Dagger](https://github.com/NetEase/Dagger)：Dagger是一个基于Selenium和TestNG的轻量级、健壮的Web UI自动测试框架，由网易开源。
* [Kdriver](https://github.com/cdpdriver/kdriver)：Kdriver是一个速度超快、协程优先、不可检测的Kotlin网页抓取/浏览器自动化库。
* [Chrome DevTools Java Client](https://github.com/kklisura/chrome-devtools-java-client)：Chrome DevTools Java Client是DevTools的一个Java客户端。
* [RestTestGen](https://github.com/SeUniVr/RestTestGen)：RestTestGen是一个强大的工具和框架，专为RESTful Web API的自动化黑盒测试而设计，由维罗纳大学开源。
* [HBrowser](https://github.com/Osiris-Team/HBrowser)：无头/完整的Java浏览器，支持下载文件、使用Cookie、检索HTML和模拟真实用户输入。
* [ATS](https://github.com/Axway/ats-framework)：ATS是内部开发的测试框架，广泛用于满足大多数Axway产品的测试需求。
* [Appium Client](https://github.com/appium/java-client)：用于编写符合WebDriver协议的Appium测试的Java语言绑定。
* [Ride](https://github.com/adobe/ride)：Ride是一个与服务无关、模块化、可扩展的Java REST API自动化框架，由Adobe开源。
* [Boyka](https://github.com/BoykaFramework/boyka-framework)：测试自动化框架，可在任何平台上自动化任何应用程序。
* [Gepard](https://github.com/epam/Gepard)：Gepard是一个基于JUnit的测试自动化框架，由EPAM开源。
* [Autest](https://gitee.com/pyqone/autest)：Autest是一个测试辅助工具集，包括UI自动化工具、测试用例生成工具、接口测试工具以及数据生成和数据处理工具等。
* [TestZeus](https://github.com/TestZeus/TestZeus)：TestZeus是专为Salesforce构建的开源自动化框架。
* [UI Automation](https://github.com/mmarquee/ui-automation)：UI Automation是一个用于自动化(通过MS UIAutomation库)基于Win32、WPF和其他Windows应用程序的富客户端应用程序的框架。
* [FastAutoTest](https://github.com/y-grey/FastAutoTest)：FastAutoTest是一个基于Appium的快速自动化框架。
* [Selcukes Java](https://github.com/selcukes/selcukes-java)：Selcukes是一个强大的开源测试库，适用于Web、移动、桌面应用程序和API端点，旨在创建可扩展的高质量自动化测试。
* [Smart Test Framework](https://github.com/HPInc/smart-test-framework)：Smart Test Framework是一个多用途测试框架，能够为网页、Web服务、桌面应用程序和移动应用程序创建自动化测试，由惠普开源。
* [JSystem](https://github.com/Top-Q/jsystem)：JSystem是一个用于编写和管理自动化系统测试的专业开源框架。
* [Ellithium](https://github.com/Abdelrhman-Ellithy/Ellithium)：Ellithium是一个统一、强大、灵活且可扩展的测试自动化框架，旨在简化和增强测试流程。
* [Sakura](https://github.com/SakuraTechy/sakura-selenium)：Sakura是一个基于Selenium改造过后的新一代Web自动化测试框架，主要用于Web应用程序的自动化测试。

#### 自动化工具

* [MeterSphere](https://github.com/metersphere/metersphere)：MeterSphere是一站式开源持续测试平台，涵盖测试跟踪、接口测试、UI测试和性能测试等功能，全面兼容JMeter、Selenium等主流开源标准，由飞致云开源。
* [Aqua](https://www.jetbrains.com/aqua/)：Aqua是一个专门为测试自动化创建的IDE，由JetBrains开发。
* [Sonic](https://github.com/SonicCloudOrg/sonic-server)：Sonic是一个集远程控制调试和移动设备自动化测试于一体的平台，致力于为全球开发者和测试工程师创造更好的使用体验。
* [SeLion](https://github.com/paypal/SeLion)：SeLion是Paypal开源的自动化测试工具。
* [SikuliX](https://github.com/RaiMan/SikuliX1)：SikuliX可以自动化你在运行Windows、Mac或某些Linux/Unix系统的台式电脑屏幕上看到的任何内容，由MIT开源。
* [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb)：LuckyFrame是一款免费开源的测试平台，最大的特点是全纬度覆盖了接口自动化、Web UI自动化、APP自动化。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具，由阿里开源。
* [ReadyAPI](https://smartbear.com/product/ready-api/)：ReadyAPI是一个专业的API测试工具，支持Java集成和自动化测试，由SmartBear开发。
* [HydraLab](https://github.com/microsoft/HydraLab)：HydraLab是一个可以帮助你利用现有的测试设备/机器轻松构建云测试平台的框架，由Microsoft开源。
* [Testsigma](https://github.com/testsigmahq/testsigma)：Testsigma是一个开源、可扩展的测试自动化平台，开箱即用。
* [Katalon Studio](https://github.com/katalon-studio/katalon-studio)：Katalon Studio是一款智能、强大且可扩展的自动化解决方案，专为世界各地的初学者和专家测试人员打造。
* [OpenTest](https://github.com/mcdcorp/opentest)：OpenTest是一款免费开源功能测试自动化工具，适用于Web应用程序、移动应用程序和API，麦当劳开源。
* [VIVIDUS](https://github.com/vividus-framework/vividus)：VIVIDUS是一种测试自动化工具，为测试最流行的应用程序类型提供已实施的解决方案。
* [TestHub](https://gitee.com/dromara/TestHub)：TestHub是一款基于流程编排的自动化测试工具，由dromara社区开源。
* [Cerberus](https://github.com/cerberustesting/cerberus-core)：Cerberus Test是一个低代码测试自动化平台，支持测试Web、iOS、Android和API(REST、SOAP和Kafka)应用程序。
* [SHAFT](https://github.com/ShaftHQ/SHAFT_ENGINE)：SHAFT是一个统一的测试自动化引擎，由一流的框架提供支持，提供类似向导的语法来高效推动自动化、最大化你的投资回报率并最小化你的学习曲线。
* [Arctic](https://github.com/corretto/arctic)：Arctic是一款由Amazon Corretto团队开发的开源多平台工具，用于自动化交互式UI测试。
* [AutoMeter](https://gitee.com/season-fan/autometer-api)：AutoMeter是一款针对分布式服务、微服务API做功能和性能一体化的自动化测试平台。
* [INGenious](https://github.com/ing-bank/INGenious)：INGenious提供了一种简单易行的方式来创建高度可靠的自动化测试，由ING银行开源。
* [AngusTester](https://github.com/xcancloud/AngusTester)：AngusTester旨在协助软件开发团队高效、持续地开展软件开发和测试活动，同时满足用户的敏捷开发和测试需求，由晓蚕云公司开发。
* [Neodymium](https://github.com/Xceptance/neodymium-library)：Neodymium尝试通过结合JUnit、WebDriver、BDD/Cucumber和适当的报告来解决典型且最紧迫的UI测试自动化问题，由Xceptance开发。
* [Video Recorder](https://github.com/SergeyPirogov/video-recorder-java)：该库只需添加一些注解即可轻松录制UI测试的视频。
* [Step](https://github.com/exense/step)：Step是一个统一的软件自动化平台，可让你充分利用自动化工件，同时摆脱特定工具。
* [TESTAR](https://github.com/TESTARtool/TESTAR_dev)：TESTAR是一款能够在GUI级别对桌面、Web和移动应用程序进行无脚本自动化系统测试的工具，由瓦伦西亚理工大学、乌得勒支大学和荷兰开放大学等开发。
* [Testerra](https://github.com/telekom/testerra)：Testerra是一个用于自动测试(Web)应用程序的集成框架，由德国电信开源。
* [ReVoman](https://github.com/salesforce-misc/ReVoman)：ReVoman是一个JVM API自动化工具，它通过让你在JVM程序/测试中执行Postman集合来重新构想API自动化，由Salesforce开源。
* [BotCity](https://github.com/botcity-dev/botcity-framework-core)：BotCity RPA模块提供识别UI元素并使用鼠标和键盘操作与其交互的功能。
* [Sahi](https://www.sahipro.com/)：Sahi是一个成熟、业务就绪的测试自动化平台，用于对UI密集型应用程序进行功能测试。
* [T-Plan](https://www.t-plan.com/)：T-Plan是一个机器人流程自动化和GUI测试自动化项目。
* [ATP](https://atestingp.sourceforge.net/)：ATP是一个自动化测试和分析工具，由西班牙马德里理工大学开源。
* [Nexial](https://github.com/nexiality/nexial-core)：Nexial的主要动机是提供一套用于软件测试的自动化功能。
* [Maveryx](https://www.maveryx.com/)：Maveryx是一款专注于减少测试维护成本、适应动态UI的高效测试自动化工具。
* [TestHubo](https://github.com/tiklab-project/tiklab-testhubo)：全栈式测试管理工具，涵盖功能测试、接口测试、Web测试、App测试及性能测试等，全面覆盖各种测试场景。
* [Online Inspection Tracker](https://github.com/TheCoolQATeam/online-inspection-tracker)：Online Inspection Tracker是一个线上UI自动化巡检工具，旨在帮助开发人员和测试人员快速、高效地检测线上Web应用的UI界面是否存在异常。
* [BitDive](https://bitdive.io/)：BitDive是零代码集成测试平台，可根据运行时应用程序行为生成测试用例。
* [MasterYi](https://gitee.com/xuwangcheng/masteryi-automated-testing)：专注于接口自动化测试的管理平台。

#### QA自动化

* [Stevia](https://github.com/persado/stevia)：Stevia是Persado的开源QA自动化测试框架。
* [QMetry](https://github.com/qmetry/qaf)：使用Selenium、WebDriver、TestNG和Jersey的Web、MobileWeb移动原生和Rest Web服务的质量自动化框架。
* [AET](https://github.com/wttech/aet)：AET是一个检测网站上的视觉变化并执行基本页面健康检查(如W3C合规性、可访问性、HTTP状态码、JS错误检查等)的系统。
* [Tanaguru](https://github.com/Tanaguru/Tanaguru)：Tanaguru是一款开源网站评估工具。

#### 测试报告

* [Allure](https://github.com/allure-framework/allure2)：Allure Report是一种灵活的多语言测试报告工具，可向你展示已测试内容的详细表示，并从日常测试执行中提取最大程度的信息。
* [ReportPortal](https://github.com/reportportal/reportportal)：ReportPortal是一项TestOps服务，它提供了增强的功能，通过使用内置分析功能来加速结果分析和报告。
* [Scott](https://github.com/dodie/scott)：Scott为Java测试提供了详细的失败消息，并且无需使用复杂的断言库。
* [Arrow](https://github.com/NetEase/arrow)：Arrow是一个TestNG插件，主要为QA工程师提供一些有趣的功能，由网易开源。
* [FACTION](https://github.com/factionsecurity/faction)：渗透测试报告生成与评估协作。
* [ChainTest](https://github.com/anshooarora/chaintest)：超级全面的报告框架，支持多种输出类型和实时历史分析。
* [Allure Server](https://github.com/kochetkov-ma/allure-server)：Allure Server用于存储/汇总/管理Allure结果，并生成/管理Allure报告。
* [Zebrunner Reporting](https://github.com/zebrunner/reporting)：Zebrunner Reporting是一种测试自动化管理工具，可累积并表示测试结果。
* [Difido Reports](https://github.com/Top-Q/difido-reports)：该项目旨在为各种功能测试自动化框架提供灵活、实时的HTML报告。
* [Open Test Reporting](https://github.com/ota4j-team/open-test-reporting)：与语言无关的测试报告格式和工具。
* [Spock Reports](https://github.com/renatoathaydes/spock-reports)：该项目是Spock的全局扩展，用于创建测试报告。
* [Projektor](https://github.com/craigatk/projektor)：Projektor可以快速轻松地查看和分享你的测试报告。
* [Scenarioo](https://github.com/scenarioo/scenarioo)：Scenarioo是一种利用UI测试功能的工具，可将其作为软件系统的文档提供给参与软件系统设计、开发、测试、操作和管理的所有人。

#### 多线程测试

* [Awaitility](https://github.com/awaitility/awaitility)：Awaitility是一种DSL，允许你以简洁且易于阅读的方式表达对异步系统的期望。
* [Lincheck](https://github.com/JetBrains/lincheck)：Lincheck是一个实用且用户友好的框架，用于在JVM上测试并发算法，由JetBrains开源。
* [Lin Check](https://github.com/devexperts/lin-check)：Lin Check是一个用于测试并发数据结构正确性的框架，由Devexperts开源。
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
* [Fray](https://github.com/cmu-pasta/fray)：Fray是Java的一个并发测试工具，可以帮助你查找和调试表现为断言违规、运行时异常或死锁的棘手竞争条件，由CMU开源。

#### POJO测试

* [OpenPojo](https://github.com/OpenPojo/openpojo)：用于简化POJO测试的库。
* [POJO TESTER](https://github.com/sta-szek/pojo-tester)：POJO-TESTER是一个Java测试库，可以使POJO测试变得更加容易。
* [BoundBox](https://github.com/stephanenicolas/boundbox)：BoundBox提供了一种简单的方法来测试对象，即通过访问对象的所有字段、构造函数和方法。

#### 日志测试

* [LogCaptor](https://github.com/Hakky54/log-captor)：LogCaptor是一个能够轻松捕获用于单元和集成测试目的的日志记录条目的库。
* [ConsoleCaptor](https://github.com/Hakky54/console-captor)：ConsoleCaptor是一个可让你轻松捕获控制台的输出以进行单元测试的库。
* [LogUnit](https://github.com/netmikey/logunit)：用于单元测试日志记录的Java库。

#### JUnit扩展

* [ReRunner](https://github.com/artsok/rerunner-jupiter)：ReRunner是JUnit 5的扩展，可以立即重新运行失败的JUnit 5测试。
* [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer)：JUnit Pioneer为JUnit 5及其Jupiter API提供扩展。
* [JUnitParams](https://github.com/Pragmatists/JUnitParams)：JUnitParams项目为JUnit添加了一个新的运行器，提供了更容易、更易读的参数化测试。
* [System Rules](https://github.com/stefanbirkner/system-rules)：System Rules是用于测试使用java.lang.System的代码的JUnit Rule集合。
* [System Lambda](https://github.com/stefanbirkner/system-lambda)：System Lambda是用于测试使用java.lang.System的代码的函数集合。
* [System Stubs](https://github.com/webcompere/system-stubs)：System Stubs用于测试依赖于java.lang.System中方法的代码。
* [JUnit5 System Exit](https://github.com/tginsberg/junit5-system-exit)：此JUnit 5扩展可帮助你为调用System.exit()的代码编写测试。
* [NoSQLUnit](https://github.com/lordofthejars/nosql-unit)：NoSQLUnit是一个JUnit扩展，可以更轻松地编写使用NoSQL后端的系统的单元和集成测试。
* [TagUnit](https://tagunit.sourceforge.net/)：TagUnit是一个用于测试JSP页面中的自定义标签的标签库。
* [JSPUnit](https://sourceforge.net/projects/jspunit/)：JSPUnit是JUnit的扩展，用于对JSP进行单元测试。
* [JSFUnit](https://jsfunit.jboss.org/)：JSFUnit是JSF应用程序的测试框架，由JBoss社区维护。
* [JFRUnit](https://github.com/moditect/jfrunit)：JfrUnit允许断言应用程序发出的JFR事件。
* [Docker Compose JUnit Rule](https://github.com/palantir/docker-compose-rule)：这是一个用于执行与Docker Compose托管容器交互的JUnit测试的库，由Palantir开源。
* [JGotesting](https://github.com/tastapod/jgotesting)：JGotesting是受Go测试包启发的JUnit兼容测试工具。
* [RandomizedTesting](https://github.com/randomizedtesting/randomizedtesting)：JUnit测试运行器和用于运行JUnit测试的插件，具有伪随机性。
* [Pesticide](https://github.com/uberto/pesticide)：Pesticide是一个用Kotlin编写的领域驱动测试库。
* [Kafka JUnit](https://github.com/charithe/kafka-junit)：Kafka JUnit提供了在测试期间启动和关闭Kafka代理的工具程序。
* [Chronicle Test Framework](https://github.com/OpenHFT/Chronicle-Test-Framework)：该库提供了用于编写JUnit测试的支持类，支持JUnit 4和JUnit 5。
* [Loom-Unit](https://github.com/cescoffier/loom-unit)：用于检查虚拟线程是否固定载体线程的JUnit 5扩展。
* [JUnit Toolbox](https://github.com/MichaelTamm/junit-toolbox)：使用JUnit 4编写自动化测试的有用类。
* [Weld Testing](https://github.com/weld/weld-testing)：该项目的主要目标是为CDI单元/组件测试提供简单快速的工具，这些工具作为JUnit 4、JUnit 5和Spock扩展实现。
* [CDI-Unit](https://github.com/cdi-unit/cdi-unit)：CDI应用程序的单元测试库，支持Mockito来Mock依赖项。
* [Kafka JUnit](https://github.com/mguenther/kafka-junit)：Kafka JUnit使开发人员能够在JUnit测试中启动和停止由Kafka代理和分布式Kafka Connect Workers组成的完整Kafka集群。
* [FakeTime](https://github.com/faketime-java/faketime)：FakeTime使用原生Java代理将System.currentTimeMillis()实现替换为你可以使用系统属性控制的实现。
* [JUnit Insights](https://github.com/adessoSE/junit-insights)：JUnit Insights是JUnit的扩展，为上下文、类和方法的运行时提供见解。
* [Specnaz](https://github.com/skinny85/specnaz)：使用Java、Kotlin和Groovy编写漂亮的RSpec/Jasmine/Mocha/Jest风格规范的库。
* [Tablasco](https://github.com/goldmansachs/tablasco)：Tablasco是一款用于表格数据集的快照测试实用程序，由高盛银行开源。

#### 测试运行器

* [Kaocha](https://github.com/lambdaisland/kaocha)：功能齐全的下一代Clojure测试运行器。
* [Infinitest](https://github.com/infinitest/infinitest)：Infinitest是Eclipse和IntelliJ的持续测试运行器插件。
* [Eftest](https://github.com/weavejester/eftest)：Eftest是一个快速且漂亮的Clojure测试运行器。
* [Jumi](https://github.com/luontola/jumi)：JVM的通用测试运行器，原生支持并行运行测试。

#### 大数据测试

* [Deequ](https://github.com/awslabs/deequ)：Deequ是一个构建在Spark之上的库，用于定义“数据单元测试”，测量大型数据集中的数据质量，由AWS开源。
* [HiveRunner](https://github.com/HiveRunner/HiveRunner)：HiveRunner是基于JUnit 4和5的Hive查询开源单元测试框架。
* [Spark Testing Base](https://github.com/holdenk/spark-testing-base)：使用Spark编写测试时使用的基类。
* [Apache Crunch](https://crunch.apache.org/)：Crunch库提供了一个用于编写、测试和运行MapReduce管道的框架，由Google开源。
* [Apache MRUnit](https://mrunit.apache.org/)：MRUnit是一个Java库，可帮助开发人员对Hadoop MapReduce作业进行单元测试，由Cloudera开源。
* [Spark Fast Tests](https://github.com/mrpowers-io/spark-fast-tests)：Apache Spark测试助手。
* [Flink Spector](https://github.com/ottogroup/flink-spector)：该项目提供了一个框架来定义Flink数据流的单元测试。
* [DynoYARN](https://github.com/linkedin/dynoyarn)：DynoYARN是一种用于启动按需YARN集群并运行模拟YARN工作负载以进行规模测试的工具，由LinkedIn开源。
* [Hive Test](https://github.com/edwardcapriolo/hive_test)：Hive Test提供了一个嵌入式Hive，其中包括一个嵌入式Derby数据库和一个本地HiveThriftService。
* [Dynamometer](https://github.com/linkedin/dynamometer)：Dynamometer是一个用于测试Hadoop的HDFS NameNode性能的工具，由LinkedIn开源。
* [Validatar](https://github.com/yahoo/validatar)：Validatar是一个大数据功能测试框架，由Yahoo开源。
* [Hazelcast Simulator](https://github.com/hazelcast/hazelcast-simulator)：Hazelcast Simulator是一个生产模拟器，用于在集群环境中测试Hazelcast和基于Hazelcast的应用程序。
* [Hadoop Mini Clusters](https://github.com/sakserv/hadoop-mini-clusters)：Hadoop Mini Clusters提供了一种在IDE中直接测试Hadoop项目的简便方法。

#### 其他测试库

* [EqualsVerifier](https://github.com/jqno/equalsverifier)：EqualsVerifier可用于Java单元测试，以验证类中equals和hashCode方法的约定是否得到满足。
* [OpenTest4J](https://github.com/ota4j-team/opentest4j)：用于表示测试失败的常见Java异常类，由JUnit团队维护。
* [XmlUnit](https://github.com/xmlunit/xmlunit)：XMLUnit是一个支持以多种方式测试XML输出的库。
* [SikuliRobot](https://github.com/rainmanwy/robotframework-SikuliLibrary)：Sikuli机器人框架库为Robot Framework提供关键字，可以通过Sikuli测试UI。
* [StackSrc](https://github.com/laech/java-stacksrc)：该项目的目标是修饰测试失败的堆栈跟踪，使其更有用。
* [Overcast](https://github.com/xebialabs/overcast)：用于针对云中的主机编写测试的Java工具类。
* [SQL Logic Test](https://github.com/hydromatic/sql-logic-test)：SQL Logic Test是一套包含超过700万个测试的套件，用于测试SQL的核心方面。
* [SocketTest](https://github.com/akshath/SocketTest)：一个用于套接字测试的Java工具，它可用于测试任何使用TCP或UDP协议进行通信的服务器或客户端。
* [Skippy](https://github.com/skippy-io/skippy)：Skippy是JVM的测试影响分析和预测测试选择框架。
* [Taikai](https://github.com/enofex/taikai)：Taikai通过提供针对各种技术定制的一整套预定义规则来扩展流行的ArchUnit库的功能。
* [Minutest](https://github.com/dmcg/minutest)：在JVM上对Kotlin进行简单、富有表现力、可扩展的测试。
* [GWT Test Utils](https://github.com/gwt-test-utils/gwt-test-utils)：GWT Test Utils是用于GWT应用程序的Java测试框架。
* [Karibu Testing](https://github.com/mvysny/karibu-testing)：Vaadin服务器端无浏览器无容器单元测试。

#### Spring测试

* [Spring Addons](https://github.com/ch4mpy/spring-addons)：提供OAuth2资源服务器配置和测试的库。
* [Spring Test Smart Context](https://github.com/seregamorph/spring-test-smart-context)：提高Spring Boot测试效率。
* [Spring Test Profiler](https://github.com/PragmaTech-GmbH/spring-test-profiler)：Spring Test实用程序为Spring Test执行提供可视化和洞察，重点关注Spring上下文缓存统计。
* [Component Test Framework](https://github.com/lydtechconsulting/component-test-framework)：允许对Spring Boot应用程序进行组件测试的库。
* [Spring Boot TestJars](https://github.com/spring-projects-experimental/spring-boot-testjars)：该项目允许用户通过将外部Spring Boot应用程序创建为Bean来轻松启动它。
* [Mock In Bean](https://github.com/antoinemeyer/mock-in-bean)：@MockInBean和@SpyInBean是Spring Boot Test的@MockBean和@SpyBean的替代品。

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
* [OWASP Benchmark](https://github.com/OWASP-Benchmark/BenchmarkJava)：OWASP Benchmark项目是一个Java测试套件，旨在验证漏洞检测工具的速度和准确性。

#### 测试模板

* [Selenium Java Lean Test Architecture](https://github.com/eliasnogueira/selenium-java-lean-test-architecture)：该项目使用最佳框架和实践为你的Web测试提供完整的精益测试架构。
* [Selenium Maven Template](https://github.com/Ardesco/Selenium-Maven-Template)：适用于Selenium 4的Maven模板，包含最新的依赖项。
* [Selenium Cucumber](https://github.com/selenium-cucumber/selenium-cucumber-java)：Selenium Cucumber是一种BDD方法，用于编写自动化测试脚本来测试Web。
* [Cucumber TestNG Java](https://github.com/gauravkarvir/cucumber_testng_java)：该项目是一个模板测试自动化框架，它提供了跨项目创建GUI、移动和API级别测试自动化测试脚本的结构化和标准方法。
* [Cucumber Java Skeleton](https://github.com/cucumber/cucumber-java-skeleton)：这是使用Java搭建Cucumber最简单的方法。
* [Selenium Java Test Automation Architecture](https://github.com/Tahanima/selenium-java-test-automation-architecture)：使用Java和Selenium WebDriver的即用型UI测试自动化架构。
* [Selenium OSTAF](https://github.com/Infosys/Selenium-Testing-Automation-Framework)：Selenium OSTAF是一个框架，它可以帮助测试人员自动执行Web应用程序的测试，而无需记录或编写Selenium脚本，由Infosys开源。
* [Playwright Java Test Automation Architecture](https://github.com/Tahanima/playwright-java-test-automation-architecture)：使用Java和Playwright的即用型UI测试自动化架构。
* [Quantum Starter Kit](https://github.com/Perfecto-Quantum/Quantum-Starter-Kit)：Quantum Starter Kit旨在让你通过几个简单的步骤使用Quantum框架启动和运行，并使你能够开始使用简单的Cucumber编写测试。
* [Selenium Tests Framework](https://github.com/tarun3kumar/seleniumtestsframework)：Selenium Tests Framework是一个用于桌面Web、移动网站和移动应用程序自动化测试的测试自动化框架。

#### 测试异味

* [Test Smell Detector](https://github.com/TestSmells/TestSmellDetector)：该项目旨在帮助开发人员了解在编写单元测试时通常会引入或遇到的单元测试异味类型。
* [JNose](https://github.com/arieslab/jnose)：JNose Test是一种用于自动检测测试代码中的测试异味并收集覆盖率指标的工具，由巴伊亚联邦大学、拉夫拉斯联邦大学和巴伊亚州立大学共同开发。
* [JSNose](https://github.com/saltlab/JSNose)：JSNose是一个用Java编写的JavaScript代码异味检测工具，由不列颠哥伦比亚大学开源。

#### 代码覆盖率

* [JaCoCo](https://github.com/jacoco/jacoco)：JaCoCo是一个免费的Java代码覆盖率库。
* [Super JaCoCo](https://github.com/didi/super-jacoco)：Super-JaCoCo基于JaCoCo、Git二次开发打造的一站式Java代码全量/diff覆盖率收集平台，能够低成本、无侵入的收集代码覆盖率数据，由滴滴开源。
* [Kover](https://github.com/Kotlin/kotlinx-kover)：Kover是一组用于收集为JVM和Android平台编译的Kotlin代码的测试覆盖率的解决方案，由JetBrains开发。
* [Clover](https://bitbucket.org/atlassian/clover)：Atlassian开源的Java和Groovy代码覆盖率工具。
* [Cobertura](https://github.com/cobertura/cobertura)：Cobertura是一个免费的Java代码覆盖率报告工具。
* [JSCover](https://github.com/tntim96/JSCover)：JSCover是一个易于使用的JavaScript代码覆盖率测量工具。
* [EMMA](https://emma.sourceforge.net/)：EMMA是一个用于测量和报告Java代码覆盖率的开源工具包。
* [Cloverage](https://github.com/cloverage/cloverage)：Clojure测试覆盖率工具。
* [Codecov](https://about.codecov.io/)：Codecov是适用于任何测试套件的一体化代码覆盖率报告解决方案。
* [Parasoft JTest](https://www.parasoft.com/)：包括多种现代QA工具，允许测量代码覆盖率，并对其进行静态和动态分析，这是一款商业工具。
* [OpenClover](https://github.com/openclover/clover)：OpenClover测量Java和Groovy的代码覆盖率并收集20多个代码指标。

## 数据库开发

这里列出了常用数据库开发库、ORM框架、JDBC框架、工具等。

#### 数据库驱动

* [Postgresql](https://github.com/pgjdbc/pgjdbc)：Postgresql JDBC驱动程序。
* [PGJDBC NG](https://github.com/impossibl/pgjdbc-ng)：PostgreSQL的新JDBC驱动程序，旨在支持JDBC和Postgres的高级功能。
* [Postgresql R2DBC](https://github.com/pgjdbc/r2dbc-postgresql)：Postgresql R2DBC驱动程序。
* [PostgreSQL Async](https://github.com/mauricio/postgresql-async)：用Scala编写的异步、基于Netty的PostgreSQL和MySQL数据库驱动程序。
* [Postgres Async Driver](https://github.com/alaisi/postgres-async-driver)：Postgres Async Driver是PostgreSQL的非阻塞Java驱动程序。
* [MySQL](https://github.com/mysql/mysql-connector-j)：MySQL JDBC驱动程序。
* [AWS MySQL JDBC](https://github.com/awslabs/aws-mysql-jdbc)：AWS MySQL Driver是一个使应用程序能够充分利用集群MySQL数据库功能的驱动程序。
* [AWS JDBC Driver](https://github.com/aws/aws-advanced-jdbc-wrapper)：该包装器是对现有JDBC驱动程序的补充，旨在扩展驱动程序的功能，使应用程序能够充分利用Amazon Aurora等集群数据库的功能。
* [MariaDB Java Connector](https://github.com/mariadb-corporation/mariadb-connector-j)：MariaDB Java Connector是一个与JDBC 4.2兼容的驱动程序，用于将用Java开发的应用程序连接到MariaDB和MySQL数据库。
* [Oracle](https://www.oracle.com/database/technologies/maven-central-guide.html)：Oracle JDBC驱动程序。
* [Oracle R2DBC](https://github.com/oracle/oracle-r2dbc)：Oracle数据库的R2DBC驱动程序。
* [SqlServer](https://github.com/microsoft/mssql-jdbc)：SqlServer JDBC驱动程序。
* [R2DBC MySQL](https://github.com/mirromutth/r2dbc-mysql)：该项目包含R2DBC SPI的MySQL实现。
* [R2DBC SPI](https://github.com/r2dbc/r2dbc-spi)：R2DBC实现的SPI。
* [R2DBC MySQL](https://github.com/asyncer-io/r2dbc-mysql)：该项目包含R2DBC SPI的MySQL实现。
* [R2DBC MSSQL](https://github.com/r2dbc/r2dbc-mssql)：使用TDS协议的SQLServer的R2DBC驱动程序。
* [MariaDB R2DBC](https://github.com/mariadb-corporation/mariadb-connector-r2dbc)：非阻塞MariaDB和MySQL客户端。
* [Influx4j](https://github.com/brettwooldridge/influx4j)：适用于InfluxDB的高性能、零垃圾Java客户端/驱动程序。
* [OceanBase Client](https://github.com/oceanbase/obconnector-j)：兼容JDBC 4.2的OceanBase Java驱动程序。
* [SQLite JDBC](https://github.com/xerial/sqlite-jdbc)：用于在Java中访问和创建SQLite数据库文件的库。
* [Couchbase](https://github.com/couchbase/couchbase-java-client)：Couchbase Server的官方Java客户端。
* [InfluxDB Java](https://github.com/influxdata/influxdb-java)：InfluxDB的官方Java客户端库。
* [InfluxDB2 Java](https://github.com/influxdata/influxdb-client-java)：适用于JVM的InfluxDB 2客户端。
* [RxJava JDBC](https://github.com/davidmoten/rxjava2-jdbc)：RxJava 2与JDBC集成，包括非阻塞连接池。
* [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client)：用Java编写的高性能响应式SQL客户端。
* [Snowflake JDBC Driver](https://github.com/snowflakedb/snowflake-jdbc)：Snowflake JDBC驱动程序。
* [JAsync-SQL](https://github.com/jasync-sql/jasync-sql)：JAsync-SQL是一个使用Kotlin编写的简单、基于Netty、异步、高性能且可靠的PostgreSQL和MySQL数据库驱动程序。
* [TiKV Java](https://github.com/tikv/client-java)：TiKV的Java客户端库。
* [VtDriver](https://github.com/jd-opensource/vtdriver)：VtDriver是一套基于分布式数据库Vitess而开发的Vitess Java客户端解决方案，由京东开源。
* [Aerospike Java Client](https://github.com/aerospike/aerospike-client-java)：Aerospike数据库的Java客户端库。
* [OpenGauss JDBC](https://gitee.com/opengauss/openGauss-connector-jdbc)：OpenGauss JDBC驱动程序。
* [Jackcess](https://github.com/jahlborn/jackcess)：Jackcess是一个纯Java库，用于读取和写入MS Access数据库。
* [Dgraph4j](https://github.com/dgraph-io/dgraph4j)：Java 1.8及更高版本的Dgraph客户端的最小实现。
* [Nebula Java](https://github.com/vesoft-inc/nebula-java)：Nebula Graph的Java客户端和数据导入器。
* [Meilisearch Java](https://github.com/meilisearch/meilisearch-java)：Meilisearch是一个开源搜索引擎。
* [ArangoDB Java Driver](https://github.com/arangodb/arangodb-java-driver)：官方ArangoDB Java驱动程序。
* [Avatica](https://github.com/apache/calcite-avatica)：Avatica是一个用于构建数据库驱动程序的框架。

#### ORM框架

* [Hibernate](https://github.com/hibernate/hibernate-orm)：Hibernate是一个强大的Java ORM解决方案，可以轻松地为应用程序、库和框架开发持久层逻辑，由RedHat开源。
* [Jakarta Data](https://github.com/jakartaee/data)：Jakarta Data规范提供了一个API，可以更轻松地访问各种数据库类型的数据。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring Data JPA是Spring Data系列的一部分，可以轻松实现基于JPA的Repository。
* [Mybatis](https://github.com/mybatis/mybatis-3)：MyBatis是一流的持久层框架，支持自定义SQL、存储过程和高级映射。
* [Mybatis Plus](https://github.com/baomidou/mybatis-plus)：MyBatis Plus是MyBatis的一个强大的增强工具包，用于简化开发。
* [APIJSON](https://github.com/Tencent/APIJSON)：APIJSON是一种专为API而生的JSON网络传输协议以及基于这套协议实现的ORM库，由腾讯开源。
* [Exposed](https://github.com/JetBrains/Exposed)：Exposed是一个Kotlin SQL库，有两种风格：轻量级ORM(使用DAO)和类型安全SQL(使用DSL)，由JetBrains开发。
* [Prisma](https://github.com/prisma/prisma1)：Prisma是一个Scala ORM，具有直观的数据模型、自动迁移、类型安全和自动完成功能。
* [LitePal](https://github.com/guolindev/LitePal)：LitePal是一个开源Android库，可以让开发人员极其轻松地使用SQLite数据库。
* [Apache JDO](https://github.com/apache/db-jdo)：JDO是访问数据库中持久数据的标准方法，使用POJO来表示持久数据。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：EclipseLink为开发人员提供基于标准的对象关系持久性解决方案，并额外支持许多高级功能，Oracle开源。
* [GreenDAO](https://github.com/greenrobot/greenDAO)：GreenDAO是一个轻量且快速的Android ORM，可将对象映射到SQLite数据库。
* [Micronaut Data](https://github.com/micronaut-projects/micronaut-data)：Micronaut Data是一个数据库访问工具包，它使用AoT编译来预先计算存储库接口的查询，然后由轻量级的运行时层执行。
* [Apache OpenJPA](https://github.com/apache/openjpa)：OpenJPA是Jakarta Persistence API 3.0规范的实现。
* [WCDB](https://github.com/Tencent/wcdb)：WCDB是腾讯微信应用中使用的高效、完整、易用的移动数据库框架。
* [GORM](https://gorm.grails.org/)：适用于JVM的强大的基于Groovy的数据访问工具包，由Object Computing开源。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean是一个纯Java实现的开源ORM框架，它被设计成比JPA更简单、容易理解和使用。
* [DBFlow](https://github.com/agrosner/DBFlow)：DBFlow是基于SQLite为Android构建的快速、高效且功能丰富的Kotlin数据库库。
* [Komapper](https://github.com/komapper/komapper)：Komapper是服务器端Kotlin的ORM库。
* [Permazen](https://github.com/permazen/permazen)：Permazen是用于SQL、键值或内存数据库的持久层框架。
* [Sugar ORM](https://github.com/chennaione/sugar)：Sugar ORM是一个Android ORM库，它提供了一种简单的方法来存储和检索数据。
* [ObjectiveSQL](https://github.com/braisdom/ObjectiveSql)：ObjectiveSQL是一个基于ActiveRecord模式的ORM框架，它鼓励快速开发和整洁，最少的代码，以及约定优于配置。
* [ORMLite](https://github.com/j256/ormlite-core)：ORMLite提供了一些简单、轻量级的功能，用于将Java对象持久保存到SQL数据库，同时避免更标准ORM包的复杂性和开销。
* [Ktorm](https://github.com/kotlin-orm/ktorm)：Ktorm是一个直接基于纯JDBC的轻量级、高效的Kotlin ORM框架。
* [Querulous](https://github.com/nkallen/querulous)：Querulous是一个与数据库交互的库，由Twitter开源。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级ORM框架，由高盛银行开源。
* [SQLDelight](https://github.com/sqldelight/sqldelight)：SQLDelight会根据你的SQL语句生成类型安全的Kotlin API，由Square开发。
* [Apache Cayenne](https://github.com/apache/cayenne)：Cayenne是一个开源持久层框架，提供ORM和远程处理服务，由ObjectStyle开源。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：Jimmer是一个针对Java和Kotlin的革命性ORM，以及一套基于它的完整的集成方案。
* [JFinal](https://gitee.com/jfinal/jfinal)：JFinal是基于Java语言的极速Web、ORM框架。
* [SQLlin](https://github.com/ctripcorp/SQLlin)：SQLlin是一个基于DSL和KSP的Kotlin Multiplatform ORM库，由携程开发。
* [LiteORM](https://github.com/litesuits/android-lite-orm)：LiteORM是一个小巧、强大、性能更好的Android ORM类库。
* [ActiveJDBC](https://github.com/javalite/javalite/tree/master/activejdbc)：ActiveJDBC是一个轻量级的ORM库，适用于Java。
* [AnyLine](https://gitee.com/anyline/anyline)：AnyLine的核心是一个面向运行时的元数据动态ORM。
* [NgBatis](https://github.com/nebula-contrib/ngbatis)：NgBatis是一个可以使用类似MyBatis、MyBatisPlus的方式，操作NebulaGraph的Java ORM框架。
* [HsWeb ORM](https://github.com/hs-web/hsweb-easy-orm)：简单的ORM工具，为动态表单而生。
* [Easy Query](https://github.com/dromara/easy-query)：Easy Query是一款轻量级的ORM框架，无需任何第三方依赖。
* [Bee](https://github.com/automvc/bee)：Bee是一个人工智能、简单、高效的ORM框架，支持JDBC、Cassandra、MongoDB、Sharding。
* [JINQ](https://github.com/my2iu/Jinq)：JINQ为开发人员提供了一种用Java编写数据库查询的简单而自然的方法。
* [Mango](https://github.com/jfaster/mango)：Mango是一个高性能的分布式ORM框架。
* [Slick](https://github.com/slick/slick)：Slick是Scala的一个高级、全面的数据库访问库，具有强类型、高度可组合的API，由Lightbend开发。
* [Anima](https://github.com/hellokaton/anima)：Anima允许你采用简单的DSL语法查询数据库。
* [Eloquent](https://github.com/gaarason/database-all)：Eloquent ORM提供一个美观、简单的与数据库打交道的ActiveRecord实现。
* [ActiveAndroid](https://github.com/pardom-zz/ActiveAndroid)：ActiveAndroid是一个Active Record风格的ORM。
* [Bean Searcher](https://github.com/troyzhxu/bean-searcher)：专注于高级查询的只读ORM，天然支持连接表，并且避免DTO/VO转换，使得一行代码实现复杂查询成为可能。
* [Speedment](https://github.com/speedment/speedment)：Speedment是一个开源Java Stream ORM工具包和运行时。
* [BeetlSQL](https://gitee.com/xiandafu/beetlsql)：BeetlSQL的目标是提供开发高效、维护高效、运行高效的数据库访问框架。
* [AFinal](https://github.com/yangfuhai/afinal)：AFinal是一个Android的SQLite ORM和IoC框架。
* [Sqli](https://github.com/x-ream/sqli)：ORM SQL查询构建器。
* [Persism](https://github.com/sproket/Persism)：Persism是一个轻量级、自动发现、自动配置和约定优于配置的ORM库。
* [SQLToy](https://github.com/sagframe/sagacity-sqltoy)：SQLToy是基于Java语言开发的，兼有Hibernate面向对象操作和MyBatis灵活查询的优点，同时更贴切项目、更贴切开发者的一个关系型数据库ORM框架。
* [Android Orma](https://github.com/maskarade/Android-Orma)：Orma是一个适用于Android SQLite数据库的ORM框架。
* [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)：SimpleFlatMapper提供了一个非常快速且易于使用的映射器。
* [Sprinkles](https://github.com/emilsjolander/sprinkles)：Sprinkles是一个用于处理Android应用中数据库的简化库。
* [ORMAN](https://github.com/ahmetb/orman)：ORMAN是一个简约轻量的Java ORM框架，它可以处理常见的数据库使用，而无需编写SQL。
* [SimpleMybatis](https://github.com/zhangchuangiie/SimpleMybatis)：SimpleMybatis是一个基于Mybatis封装的类JdbcTemplate风格的ORM工具。
* [Ollie](https://github.com/pardom-zz/Ollie)：Android的编译时Active Record ORM。
* [Freezer](https://github.com/florent37/Freezer)：Freezer是一个简洁流式的Android ORM。
* [Scala ActiveRecord](https://github.com/aselab/scala-activerecord)：Scala ActiveRecord是Scala的ORM库。
* [ScalaSql](https://github.com/com-lihaoyi/scalasql)：ScalaSql是一个Scala ORM库，它允许对SQL数据库进行类型安全的低样板查询。
* [Entity SQL](https://github.com/wb04307201/entity-sql)：Entity SQL是一个轻量级的Java ORM工具库。
* [Kotysa](https://github.com/ufoss-org/kotysa)：轻量级ORM，提供为JVM和Android编写Kotlin类型安全SQL的惯用方法。
* [VeasionDB](https://github.com/veasion/veasion-db)：VeasionDB是一个轻量级持久层ORM框架。
* [Squeryl](https://github.com/squeryl/squeryl)：Squeryl是一个Scala DSL，用于与数据库通信，内容繁琐最少，类型安全最大化。
* [FastSQL](https://github.com/fast-sql/FastSQL)：FastSQL是一个基于Spring JDBC的简单ORM框架。
* [Wood](https://gitee.com/noear/wood)：微型ORM框架，无依赖。
* [SansOrm](https://github.com/brettwooldridge/SansOrm)：SansOrm是无ORM的Java到SQL/SQL到Java对象映射库。
* [Requery](https://github.com/requery/requery)：Requery是一个轻量级但功能强大的对象映射和SQL生成器，适用于Java/Kotlin/Android，支持RxJava和Java 8。
* [DataNucleus](https://github.com/datanucleus/datanucleus-core)：DataNucleus是一个兼容各种标准(JDO1、JDO2、JDO2.1、JDO2.2、JDO2.3、和JPA1)的Java数据持久化框架。

#### JDBC框架

* [Spring JDBC](https://github.com/spring-projects/spring-framework)：Spring JDBC是Spring框架提供的一个基于JDBC之上的用于操作关系型数据库的模块。
* [Jdbi](https://github.com/jdbi/jdbi)：Jdbi库提供了对Java和其他JVM语言中的关系数据库的便捷、惯用的访问。
* [Sql2o](https://github.com/aaberg/sql2o)：Sql2o是一个小型Java库，可以轻松地将SQL语句的结果转换为对象。
* [Doobie](https://github.com/typelevel/doobie)：Doobie是Scala的纯函数式JDBC层。
* [Database](https://github.com/susom/database)：Database提供一种简化的数据库访问方式，它是JDBC驱动程序的包装器，由斯坦福开源。
* [ScalikeJDBC](https://github.com/scalikejdbc/scalikejdbc)：ScalikeJDBC无缝包装JDBC API，提供直观且高度灵活的功能。
* [Krush](https://github.com/TouK/krush)：Krush是基于Exposed SQL DSL的Kotlin轻量级持久层。
* [Dekaf](https://github.com/JetBrains/dekaf)：Dekaf是一个主要通过JDBC处理数据库的Java框架，由JetBrains开源。
* [Apache Commons DbUtils](https://github.com/apache/commons-dbutils)：Commons DbUtils包是一组用于简化JDBC开发的Java工具类。
* [Jcabi JDBC](https://github.com/jcabi/jcabi-jdbc)：Jcabi JDBC是JDBC的一个方便、流式的包装器。
* [FluentJdbc](https://github.com/zsoltherpai/fluent-jdbc)：FluentJdbc是一个用于方便原生SQL查询的Java库。
* [Yank](https://github.com/knowm/Yank)：Yank是适用于Java应用程序的超轻量JDBC持久层。
* [Norm](https://github.com/dieselpoint/norm)：Norm是一种访问JDBC数据库的简单方法，通常只需一行代码。
* [Iciql](https://github.com/gitblit/iciql)：Iciql是一个基于模型的JDBC数据库访问包装器。
* [JDBCX](https://github.com/jdbcx/jdbcx)：JDBCX通过支持SQL之外的其他数据格式、压缩算法、对象映射、类型转换和查询语言来增强JDBC驱动程序。
* [Relate](https://github.com/lucidsoftware/relate)：Relate是Scala上一个轻量级、极其快速的数据库访问层，它抽象了JDBC的独特特性，同时完全控制了SQL，由Lucid开源。
* [GyJdbc](https://github.com/SpringStudent/GyJdbc)：GyJdbc基于JdbcTemplate的类似JPA的持久层框架封装。
* [SQLLine](https://github.com/julianhyde/sqlline)：SQLLine是一个用于通过JDBC向关系型数据库发出SQL的命令行Shell。
* [Carbonado](https://github.com/Carbonado/Carbonado)：Carbonado是Java应用程序的可扩展、高性能持久性抽象层，提供底层持久性技术的关系视图，由Amazon开源。
* [SQLBuilder](https://github.com/jkrasnay/sqlbuilder)：该包包含许多实用程序类，以简化SQL的使用。
* [Quill](https://github.com/zio/zio-quill)：Quill提供了一种引用领域特定语言，以在Scala中表达查询并以目标语言执行它们。
* [RxJava JDBC](https://github.com/davidmoten/rxjava-jdbc)：使用JDBC和RxJava Observables高效执行和功能组合数据库调用。
* [Anorm](https://github.com/playframework/anorm)：Anorm是一个简单的数据访问层，它使用纯SQL与数据库交互，并提供API来解析和转换结果数据集。
* [Eql](https://github.com/bingoohuang/eql)：Eql是一个简单，轻量的数据持久层的框架，可以用于代替Mybatis。
* [Spring JDBC Plus](https://github.com/naver/spring-jdbc-plus)：Spring JDBC Plus提供基于Spring Data JDBC的扩展，由Naver开源。
* [Spring Data JDBC Repository](https://github.com/nurkiewicz/spring-data-jdbc-repository)：该项目的目的是提供基于Spring框架的JdbcTemplate的关系数据库的通用、轻量级且易于使用的DAO实现，并与Spring Data项目范围兼容。
* [KotliQuery](https://github.com/seratch/kotliquery)：KotliQuery是一个为Kotlin开发者设计的实用RDB客户端库。
* [DBVisitor](https://gitee.com/zycgit/dbvisitor)：DBVisitor提供Java对关系数据库更加自然的访问。

#### DAO框架

* [DAL](https://github.com/ctripcorp/dal)：DAL是携程框架部开发的数据库访问框架，支持流行的分库分表操作。
* [Doma](https://github.com/domaframework/doma)：Doma是适用于Java 8+的面向DAO的数据库映射框架。
* [Dynamic SQL2](https://github.com/pengweizhong/dynamic-sql2)：Dynamic SQL2是一个灵活、安全的Java动态SQL构建框架，提供简洁的DSL风格接口，帮助开发者动态构建SQL查询。
* [MiniDao](https://github.com/jeecgboot/MiniDao)：MiniDao是一款轻量级Java持久层框架，基于Spring JDBC\Freemarker实现，具备Mybatis一样的SQL分离和逻辑标签能力，由北京国炬公司开发。
* [DAS](https://github.com/ppdaicorp/das)：DAS是信也科技自研的数据库访问框架。
* [DAOMedge](https://medge.id.au/medge/daomedge/)：DaoMerge是一个简单易用、文档齐全的数据库访问对象库，并带有代码生成器。
* [UroboroSQL](https://github.com/future-architect/uroborosql)：UroboroSQL是一个简单的SQL执行库，可以利用与Java 8兼容的2-way-SQL，由日本Future公司开源。
* [WestDAO](https://github.com/westwong/westDao)：基于Spirng JPA JPQL，借鉴MyBatis Plus的全新DAO框架。

#### 持久层库

* [SquiDB](https://github.com/yahoo/squidb)：SquiDB是适用于Android和iOS的跨平台SQLite数据库层，旨在尽可能轻松地使用SQLite数据库，由Yahoo开源
* [SQL Brite](https://github.com/square/sqlbrite)：一个轻量级的SQLiteOpenHelper包装器，为SQL作引入了响应式流语义，由Square开源。
* [StorIO](https://github.com/pushtorefresh/storio)：SQLiteDatabase和ContentResolver的响应式API。
* [Apache MetaModel](https://metamodel.apache.org/)：Metamodel是一个用于处理结构化数据的Java库，它提供了强大的元数据驱动的数据访问API，支持多种数据源，如关系数据库、CSV文件等。
* [Apache EmpireDB](https://github.com/apache/empire-db)：EmpireDB是一个轻量级的关系型数据库访问库，用于处理所有关系型数据的存储、操作、检索和建模方面。
* [Japedo](https://www.logitags.com/japedo/)：Japedo是一个用于生成Java应用程序完整持久层文档的工具。
* [Objectify](https://github.com/objectify/objectify)：Objectify是专门为Google Cloud Datastore设计的Java数据访问API。
* [PulseDB](https://github.com/feedzai/pdb)：PulseDB是一个用Java编写的数据库映射软件库，它提供对各种数据库实现的透明访问和操作，由Feedzai开源。
* [Elsql](https://github.com/OpenGamma/ElSql)：ElSql允许SQL从Java应用程序外部化。
* [SqlRender](https://github.com/OHDSI/SqlRender)：这是一个R包和Java库，用于呈现参数化SQL，并将其转换为不同的SQL方言，由OHDSI开源。
* [Cantor](https://github.com/salesforce/cantor)：Cantor是一个数据服务层，它为各种存储解决方案(例如MySQL和S3)之上的多种基本数据结构提供持久化，由Salesforce开源。
* [AutoTable](https://gitee.com/dromara/auto-table)：根据Java实体，自动映射成数据库的表结构，由dromara社区开发。
* [Apache Gora](https://github.com/apache/gora)：Gora框架提供内存数据模型和大数据持久化。
* [MySQL Backup4j](https://github.com/SeunMatt/mysql-backup4j)：MySQL Backup4j是一个用于以编程方式导出MySQL数据库并将压缩转储发送到电子邮件、Amazon S3、Google Drive或任何其他选择的云存储的库。
* [Ektorp](https://github.com/helun/Ektorp)：Ektorp是一个使用CouchDB作为存储引擎的持久层API。
* [PgBulkInsert](https://github.com/PgBulkInsert/PgBulkInsert)：PgBulkInsert是一个使用二进制复制协议向PostgreSQL进行批量插入的Java库。
* [Infobip Spring Data Querydsl](https://github.com/infobip/infobip-spring-data-querydsl)：Infobip Spring Data Querydsl使用户能够在Spring Data Repository之上利用Querydsl API的全部功能。
* [SQLHelper](https://github.com/bes2008/sqlhelper)：基于Java的SQL工具。
* [Uni Pagination](https://github.com/taoganio/uni-pagination)：Uni Pagination是一个基于Java的通用分页框架，它通过抽象化的设计，为不同数据源提供统一的分页查询接口。
* [DTT](https://github.com/julxxy/dtt-spring-boot-parent)：DTT是一个面向对象的Java框架，使开发者能够通过注解驱动的开发，基于领域模型自动创建数据库表。

#### 查询构建器

* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，以帮助你编写更好的SQL。
* [QueryDSL](https://github.com/querydsl/querydsl)：QueryDSL是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。

#### NoSQL库

* [Eclipse JNoSQL](https://github.com/eclipse-jnosql/jnosql)：JNoSQL是Jakarta NoSQL和Jakarta Data规范的兼容实现，可简化Java应用程序与NoSQL数据库的集成。
* [Kundera](https://github.com/Impetus/kundera)：Kundera是一个带有JPA接口的多语言对象映射器。
* [Lightblue](https://github.com/lightblue-platform/lightblue-core)：Lightblue是基于文档的数据访问层框架，由RedHat开源。
* [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL)：一个适用于Android的简单NoSQL客户端。
* [Hibernate OGM](https://github.com/hibernate/hibernate-ogm)：Hibernate OGM使用Hibernate ORM引擎将数据存储在NoSQL数据网格中。

#### 事务

* [Seata](https://github.com/apache/incubator-seata)：Seata是一个易于使用、高性能、开源的分布式事务解决方案，由阿里开源。
* [SOFA DTX](https://mvnrepository.com/artifact/com.alipay.dtx/dtx-sofa)：DTX是蚂蚁研发的一款金融级分布式事务中间件。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：ShardingSphere是一种分布式SQL事务和查询引擎，允许在任何数据库上进行数据分片、扩展、加密等，由当当网开源。
* [Eventuate Tram Core](https://github.com/eventuate-tram/eventuate-tram-core)：Eventuate Tram是一个解决微服务架构中固有的分布式数据管理问题的平台。
* [Namastack](https://github.com/namastack/namastack-outbox)：Spring Boot的发件箱实现。
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
* [CAP4j](https://github.com/netcorepal/cap4j)：CAP4j是一个基于最终一致性的微服务分布式事务解决方案。
* [TAPIR](https://github.com/UWSysLab/tapir)：TAPIR是一种用于线性化分布式事务的新协议，使用复制构建，没有一致性保证，由华盛顿大学CSE系统实验室开源。
* [Apache Tephra](https://github.com/cdapio/tephra)：Tephra在HBase等分布式数据存储之上提供全局一致的事务，由Google开源。
* [Haeinsa](https://github.com/VCNC/haeinsa)：Haeinsa是HBase的线性可扩展的多行、多表事务库，由VCNC开源。
* [Apache ServiceComb Pack](https://github.com/apache/servicecomb-pack)：ServiceComb Pack是微服务应用程序的最终数据一致性解决方案，目前提供TCC和Saga分布式事务协调解决方案，使用Alpha作为事务协调器，Omega作为事务代理，由华为开源。
* [Raincat](https://github.com/dromara/raincat)：Raincat是强一致分布式事务框架，由dromara社区开源。
* [Scalardb](https://github.com/scalar-labs/scalardb)：ScalarDB是一个跨数据库HTAP引擎，由韩国Scalar公司维护。
* [Transaction Outbox](https://github.com/gruelbox/transaction-outbox)：Java Transaction Outbox模式的灵活实现，具有干净、可扩展的API，并且可以与各种数据库平台、事务管理方法和应用程序框架很好地配合。
* [Apache Omid](https://github.com/apache/phoenix-omid)：Apache Omid是一个灵活、可靠、高性能和可扩展的事务框架，允许大数据应用程序在MVCC键/值NoSQL数据存储之上执行ACID事务，由Yahoo开发。
* [ByteJTA](https://github.com/liuyangming/ByteJTA)：ByteJTA是分布式事务管理器的实现，基于XA/2PC机制。
* [Myth](https://github.com/dromara/myth)：Myth是采用消息队列解决分布式事务的开源框架，由dromara社区开源。
* [Acku](https://github.com/x-ream/acku)：MQ事务、TCC、最终一致性。
* [Eventuate Tram Sagas](https://github.com/eventuate-tram/eventuate-tram-sagas)：Eventuate Tram Sagas框架是一个适用于使用JDBC/JPA和Spring Boot/Micronaut的Java微服务的Saga框架。
* [Txle](https://github.com/actiontech/txle)：Txle是爱可生开发的分布式事务解决方案，可以保证业务数据的最终一致性。
* [Zeze](https://github.com/e2wugui/zeze)：Zeze是一个基于一致性缓存的分布式事务应用框架。
* [Transactional Outbox](https://github.com/tomorrow-one/transactional-outbox)：该库是Kafka事务发件箱模式的实现。

## Mybatis库

* [Mybatis Plus](https://github.com/baomidou/mybatis-plus)：MyBatis Plus是MyBatis的一个强大的增强工具包，用于简化开发。
* [Mybatis Flex](https://github.com/mybatis-flex/mybatis-flex)：Mybatis Flex是一个优雅的Mybatis增强框架。
* [Fluent Mybatis](https://gitee.com/fluent-mybatis/fluent-mybatis)：Fluent MyBatis是一个MyBatis增强工具。
* [MybatisPlus Ext](https://gitee.com/dromara/mybatis-plus-ext)：MybatisPlus Ext对MybatisPlus做了进一步的拓展封装，即保留原功能，又添加了更多有用便捷的功能。
* [Xbatis](https://gitee.com/xbatis/xbatis)：Xbatis是一款基于Mybatis的ORM框架。
* [Mybatis PageHelper](https://github.com/pagehelper/Mybatis-PageHelper)：Mybatis通用分页插件。
* [Mapper](https://github.com/abel533/Mapper)：易于使用的Mybatis通用Mapper。
* [Mapper](https://gitee.com/free/Mapper)：极其方便的使用Mybatis单表的增删改查工具。
* [MyBatis Mapper](https://github.com/mybatis-mapper/mapper)：这是一个不需要任何配置就可以直接使用的通用Mapper。
* [FastMybatis](https://gitee.com/durcframework/fastmybatis)：FastMybatis是一个Mybatis开发框架，其宗旨为简单、快速、有效。
* [MyBatis Plus Join](https://gitee.com/best_handsome/mybatis-plus-join)：对MyBatis Plus多表查询的扩展。
* [MyBatis Dynamic SQL](https://github.com/mybatis/mybatis-dynamic-sql)：适用于Kotlin和Java的SQL DSL，支持MyBatis或Spring JdbcTemplate的渲染。
* [Mybatis Generator](https://github.com/mybatis/generator)：用于Mybatis的代码生成器。
* [MybatisPlus Generator](https://github.com/baomidou/generator)：用于MybatisPlus的代码生成器。
* [Mybatis Mate](https://gitee.com/baomidou/mybatis-mate-examples)：Mybatis-Mate为MP企业级模块，支持分库分表，数据审计、数据敏感词过滤(AC算法)，字段加密，字典回写(数据绑定)，数据权限，表结构自动生成SQL维护，支持国密SM2、SM3、SM4加密算法等。
* [SQL Analysis](https://github.com/jd-opensource/sql-analysis)：SQL Analysis是基于Mybatis插件设计的一款慢SQL分析组件，由京东开源。
* [MyBatis Generator UI](https://github.com/zouzg/mybatis-generator-gui)：MyBatis Generator UI是基于MyBatis Generator开发一款界面工具。
* [MyBatis Generator Plugin](https://github.com/itfsw/mybatis-generator-plugin)：Mybatis Generator代码生成插件拓展。
* [MyBatis Plus Generator UI](https://github.com/davidfantasy/mybatis-plus-generator-ui)：提供交互式的Web UI用于生成兼容Mybatis Plus框架的相关功能代码。
* [MybatisPlus Code Generator](https://github.com/fengwenyi/mybatis-plus-code-generator)：MyBatisPlus代码生成器。
* [PNDao](https://gitee.com/piaoniu/pndao)：一个非常简单的MyBatis辅助工具，可以基于DAO的命名约定帮你生成并维护SQL语句，由票牛开源。
* [Stream Query](https://gitee.com/dromara/stream-query)：Stream Query允许完全摆脱Mapper的Mybatis Plus体验。
* [OpenScope](https://gitee.com/mofum/open-scope)：OpenScope是一种轻量级、易维护的数据权限的解决方案，它能处理比较复杂的权限操作逻辑。
* [Spring Data MyBatis](https://github.com/easybest/spring-data-mybatis)：该模块提供对基于MyBatis的数据访问层的增强支持。
* [Easyquery](https://github.com/wwtg99/easyquery)：Easyquery可以通过定义查询对象和自动构建查询SQL来快速轻松地构建查询请求，例如过滤、搜索和排序，无需手动拼接SQL或组装查询代码。
* [MyBatis R2DBC](https://github.com/linux-china/mybatis-r2dbc)：将MyBatis Reactive化，底层的JDBC替换为R2DBC。
* [A.CTable](https://gitee.com/sunchenbin/mybatis-enhance)：A.CTable是一个基于Spring和Mybatis的Maven项目，通过配置Model注解的方式来创建表，修改表结构，提供通用的单表CUDR工具。

## Hibernate库

* [Hypersistence Utils](https://github.com/vladmihalcea/hypersistence-utils)：Hypersistence Utils库提供Spring和Hibernate实用程序，可以帮助充分利用数据访问层。
* [HibernatePlus](https://gitee.com/baomidou/hibernate-plus)：Hibernate增强工具包，只做增强不做改变，更加精简持久层CRUD操作。
* [TorpedoQuery](https://github.com/xjodoin/torpedoquery)：类型安全的Hibernate查询生成器。
* [Hibernate Hydrate](https://github.com/arey/hibernate-hydrate)：Hibernate Hydrate项目的主要目标是填充持久实体图，从而避免著名的LazyInitializationException。
* [Hibernate Redis](https://github.com/debop/hibernate-redis)：使用Redis的Hibernate二级缓存权限。
* [SQLite Dialect](https://github.com/gwenn/sqlite-dialect)：受NHibernate启发的SQLite的Hibernate方言。

## JPA库

* [JPA Spec](https://github.com/wenhao/jpa-spec)：JPA按Specification查询框架。
* [RSQL JPA](https://github.com/tennaito/rsql-jpa)：该库提供了RSQL表达式到JPA Criteria Query(JPQL的对象表示)的转换器。
* [Kotlin JDSL](https://github.com/line/kotlin-jdsl)：Kotlin JDSL是一个Kotlin库，它简化了查询的构建和执行，由Line开源。
* [RSQL JPA Specification](https://github.com/perplexhub/rsql-jpa-specification)：将RSQL查询转换为org.springframework.data.jpa.domain.Specification或com.querydsl.core.types.Predicate并支持实体关联查询。
* [FluentJPA](https://github.com/streamx-co/FluentJPA)：FluentJPA是一种用于关系型数据库和JPA的语言集成查询(LINQ) 技术，它允许你通过直接集成到Java语言中来编写强类型查询。
* [Blaze Persistence](https://github.com/Blazebit/blaze-persistence)：Blaze Persistence是面向JPA提供程序的丰富Criteria API。
* [JPAStreamer](https://github.com/speedment/jpa-streamer)：JPAStreamer是一个轻量级库，用于将JPA查询表达为Java Stream。
* [ActiveJPA](https://github.com/ActiveJpa/activejpa)：ActiveJPA是一个试图在JPA之上实现ActiveRecord模式的Java库。
* [QueryStream](https://github.com/querystream/querystream)：QueryStream允许你使用类似Stream的API执行JPA查询。
* [Spring Filter](https://github.com/turkraft/springfilter)：使用用户友好的查询语法动态过滤JPA实体和Mongo集合。
* [Fenix](https://github.com/blinkfox/fenix)：Fenix是一个为了解决复杂动态SQL(JPQL)而生的Spring Data JPA扩展库。
* [Spring Data JPA EntityGraph](https://github.com/Cosium/spring-data-jpa-entity-graph)：Spring Data JPA扩展允许在Repository上完全动态使用EntityGraph。
* [Spring Data JPA DataTables](https://github.com/darrachequesne/spring-data-jpa-datatables)：该项目是Spring Data JPA项目的扩展，以便于与启用了服务器端处理的jQuery插件DataTables一起使用。
* [Spring Search](https://github.com/sipios/spring-search)：Spring Search提供了一种简单的查询语言来对JPA实体执行高级搜索。
* [Specification Arg Resolver](https://github.com/tkaczmarzyk/specification-arg-resolver)：用于使用Spring MVC和Spring Data JPA过滤数据的替代API。
* [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions)：Spring Data JPA MongoDB Expressions是一个允许你使用MongoDB查询语言查询Spring Data JPA Repository的库。
* [Spring Data JPA Extra](https://github.com/slyak/spring-data-jpa-extra)：Spring Data JPA带模板动态查询功能(例如FreeMarker、Velocity等)，类似MyBatis。
* [Spring Data Generator](https://github.com/cmeza20/spring-data-generator)：用于JPA Repository和管理器的Spring Data Generator。
* [Kotlin JPA Specification DSL](https://github.com/consoleau/kotlin-jpa-specification-dsl)：该库提供了一个流式的DSL，用于使用Spring Data规范(即JPA Criteria API)查询Spring Data JPA Repository，而无需样板代码或生成的元模型。
* [Querity](https://github.com/queritylib/querity)：Querity是一个可扩展的查询构建器，用于在Java应用程序中创建和运行数据库查询。
* [JPA Entity Generator](https://github.com/smartnews/jpa-entity-generator)：这是一个生成Lombok连接的JPA实体源代码的Java库。
* [Thymeleaf Spring Data Dialect](https://github.com/jpenren/thymeleaf-spring-data-dialect)：这是一种Thymeleaf的方言，提供了一些属性，用于创建分页和排序元素。 

#### 数据库连接池

* [Druid](https://github.com/alibaba/druid)：Druid是一个JDBC组件库，包含数据库连接池、SQL Parser等组件，由阿里云开源。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：HikariCP是一个零开销生产就绪的JDBC连接池。
* [Apache Commons DBCP](https://github.com/apache/commons-dbcp)：Commons DBCP软件实现数据库连接池。
* [C3P0](https://github.com/swaldman/c3p0)：C3P0是一个成熟、高并发的JDBC连接池库，支持PreparedStatements的缓存和重用。
* [BoneCP](https://github.com/wwadge/bonecp)：BoneCP是一种JDBC连接池实现，它通过最大限度地减少锁争用来实现高性能，从而为应用程序提供更大的吞吐量。
* [FlexyPool](https://github.com/vladmihalcea/flexy-pool)：FlexyPool库为给定的连接池添加了指标和灵活的策略，使其能够根据需要调整大小。
* [Agroal](https://github.com/agroal/agroal)：Agroal是一个小巧的数据库连接池。
* [Vibur DBCP](https://github.com/vibur/vibur-dbcp)：Vibur DBCP是并发、快速且功能齐全的JDBC连接池，它提供高级性能监控功能，包括慢SQL查询检测和日志记录、应用程序线程的非饥饿保证、语句缓存和Hibernate集成等功能。
* [Tomcat JDBC Pool](https://tomcat.apache.org/tomcat-7.0-doc/jdbc-pool.html)：Tomcat JDBC连接池。
* [R2DBC Pool](https://github.com/r2dbc/r2dbc-pool)：用于响应式关系数据库连接的连接池。
* [BeeCP](https://gitee.com/Chris2018998/BeeCP)：BeeCP是一个小型的JDBC连接池：性能高，代码轻量，稳定性好。
* [SmartPool](https://smartpool.sourceforge.net/)：SmartPool是一个连接池组件，以应用程序服务器提供的池功能为模型。

#### 数据库迁移

* [Liquibase](https://github.com/liquibase/liquibase)：Liquibase是一种数据库模式变更管理解决方案，使你能够更快、更安全地修改和发布从开发到生产的数据库变更。
* [Flyway](https://github.com/flyway/flyway)：Flyway是一款开源的数据库版本管理工具，它更倾向于规约优于配置的方式。
* [Obevo](https://github.com/goldmansachs/obevo)：Obevo是一种数据库部署工具，可处理企业规模的架构和复杂性，由高盛银行开源。
* [Flamingock](https://github.com/flamingock/flamingock-java)：Flamingock将代码变更(CaC)引入到你的整个技术栈。
* [GreenDaoUpgradeHelper](https://github.com/yuweiguocn/GreenDaoUpgradeHelper)：GreenDaoUpgradeHelper是GreenDao的数据库升级助手。
* [Mybatis Migrations](https://github.com/mybatis/migrations)：命令行数据库迁移工具。
* [Mongolastic](https://github.com/ozlerhakan/mongolastic)：Mongolastic使你能够将数据集从MongoDB节点迁移到ElasticSearch节点，反之亦然。
* [Datafall](https://github.com/forcedotcom/Data-Migration-Tool)：Datafall是一种将数据从一个Salesforce组织迁移到另一个Salesforce组织的工具。
* [Neo4j-Migrations](https://github.com/michael-simons/neo4j-migrations)：Neo4j-Migrations是一种数据库迁移和重构工具，允许以受控且可重复的方式针对一个或多个Neo4j数据库运行Cypher脚本和编程重构。
* [COS Migration](https://github.com/tencentyun/cos_migrate_tool_v5)：COS Migration是一个集成了COS数据迁移功能的一体化工具，由腾讯开源。
* [OSSImport](https://help.aliyun.com/zh/data-online-migration/user-guide/ossimport-overview)：OSSImport是阿里的一款将数据迁移至OSS的商业工具。
* [Celesta](https://github.com/CourseOrchestra/celesta)：Java的数据库迁移、SQL和测试工具。
* [Elasticsearch Evolution](https://github.com/senacor/elasticsearch-evolution)：用于迁移Elasticsearch映射的库。
* [Migrate2Postgres](https://github.com/isapir/Migrate2Postgres)：该工具允许你轻松地将数据库从其他兼容JDBC的DBMS迁移到Postgres。
* [Couchmove](https://github.com/tchlyah/couchmove)：Couchmove是Couchbase的开源Java迁移工具。
* [Mongock](https://github.com/mongock/mongock)：Mongock是一个基于Java的迁移工具，作为应用程序代码的一部分。
* [Solidbase](https://github.com/gitbucket/solidbase)：基于Liquibase的RDBMS和其他资源的通用迁移工具。
* [R2DBC Migration](https://github.com/nkonev/r2dbc-migrate)：R2DBC数据库迁移库。
* [QuantumDB](https://github.com/quantumdb/quantumdb)：QuantumDB是一种用于演进SQL数据库模式的方法，它不会妨碍SQL客户端的访问，也不需要停机。
* [Data Transfer Project](https://github.com/google/data-transfer-project)：Data Transfer Project使人们可以轻松地在在线服务提供商之间传输数据，由Google联合Facebook、Twitter、Apple、Microsoft等开发。
* [SchemaDiff](https://github.com/Rhythm-Byte/SchemaDiff)：SchemaDiff是一款强大的工具，旨在比较和分析数据库模式之间的差异，使管理和迁移不同环境中的数据库变得更为便捷。

#### 数据源增强

* [Dynamic DataSource](https://github.com/baomidou/dynamic-datasource)：Dynamic DataSource是一个基于Spring Boot的快速集成多数据源的Starter。
* [DataSource Proxy](https://github.com/jdbc-observations/datasource-proxy)：DataSource Proxy提供简单的API来拦截JDBC交互，并允许用户在查询或方法执行之前/之后执行自己的逻辑。
* [Spring Boot Dynamic DataSource](https://github.com/helloworlde/SpringBoot-DynamicDataSource)：Spring Boot多数据源、动态数据源配置。

#### 数据库工具

* [Screw](https://gitee.com/leshalv/screw)：Screw是一个简洁好用的数据库表结构文档生成器。
* [APGDiff](https://github.com/fordfrog/apgdiff)：APGDiff是免费的PostgreSQL diff工具，可用于比较/差异数据库模式。
* [Kviklet](https://github.com/kviklet/kviklet)：Kviklet采用四眼原则和高度可配置性，允许单个SQL语句或数据库会话使用类似拉取请求的审查和批准流程。
* [Databasir](https://github.com/vran-dev/databasir)：Databasir是面向团队的关系型数据库模型文档管理平台。
* [Databench-T](https://gitee.com/caict-bigdata/databench-t)：Databench-T是面向金融核心业务系统场景的事务型数据库性能测试工具，由中国信通院云计算与大数据研究所联合北京银行、建设银行等企业共同设计开发。
* [SQL Formatter](https://github.com/vertical-blank/sql-formatter)：仅依赖Java标准库的SQL格式化程序。
* [SQL Relay](https://sqlrelay.sourceforge.net/)：SQL Relay是一个数据库代理和数据库连接管理解决方案。
* [ConceptBase](https://conceptbase.sourceforge.net/)：ConceptBase是一个多用户演绎数据库系统，具有面向对象的数据模型和无限的分类级别，使其成为元建模和定制建模语言工程的强大工具，由斯科夫德大学和亚琛大学开发。
* [Database Export](https://gitee.com/pomz/database-export)：Database Export是一款多线程生成数据库结构文档的开源Spring Boot工程。

#### 存储过程

* [PL/Java](https://github.com/tada/pljava)：PL/Java是一个免费的附加模块，它将Java存储过程、触发器和函数引入PostgreSQL后端。
* [SPAN](https://github.com/americanexpress/SPAN)：SPAN是一个Java框架，它可以帮助开发人员通过提供配置和POJO详细信息来连接存储过程，由美国运通开源。

#### N+1检测

* [DBUtil](https://github.com/vladmihalcea/db-util)：该工具可以在测试期间自动检测N+1查询问题。
* [JPlusOne](https://github.com/adgadev/jplusone)：JPlusOne是用于自动检测和断言基于JPA的Spring Boot Java应用程序中发生的“N+1问题”并查找JPA发出的SQL语句的一般来源的工具。
* [Spring Hibernate Query Utils](https://github.com/yannbriancon/spring-hibernate-query-utils)：该库提供了检测N+1查询并对Spring和Hibernate生成的查询进行计数的工具。
* [JPA N+1 Detector](https://github.com/joon6093/jpa-nplus1-detector)：检测JPA应用中的N+1查询问题。

#### Redis库/工具

* [Redisson](https://github.com/redisson/redisson)：Redisson是一个具有内存数据网格功能的Redis Java客户端。
* [Jedis](https://github.com/redis/jedis)：Jedis是Redis的Java客户端，旨在提高性能和易用性。
* [Tedis](https://github.com/justified/tedis)：Tedis是另一个Redis的Java客户端，阿里开源。
* [Lettuce](https://github.com/lettuce-io/lettuce-core)：Lettuce是一个可扩展的线程安全Redis客户端，适用于同步、异步和响应式使用。
* [Spring Data Redis](https://github.com/spring-projects/spring-data-redis)：Spring Data Redis提供从Spring应用程序轻松配置和访问Redis的功能。
* [RedisCache](https://gitee.com/darkidiot/RedisCache)：RedisCache是基于Jedis的SDK。
* [JRedis](https://github.com/alphazero/jredis)：JRedis是Redis的Java客户端和连接器。
* [Redis Protocol](https://github.com/spullara/redis-protocol)：RedisClient是Redis的Java客户端和服务端实现。
* [Carmine](https://github.com/taoensso/carmine)：Carmine是Clojure的成熟Redis客户端，提供惯用的Clojure API，速度快、功能强大且易于使用。
* [Vert.x Redis Client](https://github.com/vert-x3/vertx-redis-client)：Vert.x Redis客户端提供异步API来与Redis数据结构服务器交互。
* [Jesque](https://github.com/gresrun/jesque)：Jesque是Resque在Java中的实现。
* [JOhm](https://github.com/xetorthio/johm)：JOhm是一个速度超快的Java对象哈希映射库。
* [RedisScala](https://github.com/etaty/rediscala)：RedisScala是具有非阻塞和异步I/O操作的Scala Redis客户端。
* [Valkey GLIDE](https://github.com/valkey-io/valkey-glide)：Valkey GLIDE是一个开源Valkey客户端库，Valkey是Redis的开源fork版本，由AWS开源。
* [JRedisJSON](https://github.com/RedisJSON/JRedisJSON)：Redis RedisJSON的Java客户端。
* [Redis OM Spring](https://github.com/redis/redis-om-spring)：Redis OM Spring扩展了Spring Data Redis，以充分利用Redis和Redis Stack。
* [Kreds](https://github.com/crackthecodeabhi/kreds)：Kreds是一个线程安全、惯用、基于协程的Redis客户端。
* [Jodis](https://github.com/CodisLabs/jodis)：Jodis是一个基于Jedis和Curator的Codis Java客户端。
* [Redisun](https://gitee.com/smartboot/redisun)：Redisun是一个基于Smart Socket开发的轻量级Redis客户端。
* [RedisUtil](https://github.com/iyayu/RedisUtil)：Java操作Redis的工具类，使用StringRedisTemplate实现。
* [RedisClient](https://github.com/caoxinyu/RedisClient)：RedisClient是一个基于Java SWT和Jedis编写的Redis客户端GUI工具。
* [HotKey](https://gitee.com/jd-platform-opensource/hotkey)：京东App后台中间件，毫秒级探测热点数据，毫秒级推送至服务器集群内存，大幅降低热key对数据层查询压力。
* [Redis Admin](https://github.com/mauersu/redis-admin)：Redis Admin是一个基于Java EE和Jedis编写的Redis客户端Web工具。
* [Redis Desktop Client](https://gitee.com/RedisDesktopClient/redis-desktop-client)：Redis Desktop Client是一款颜值较高、使用方便的redis客户端工具。
* [RedisPlus](https://gitee.com/MaxBill/RedisPlus)：RedisPlus是为Redis可视化管理开发的一款开源免费的桌面客户端软件。
* [Redis Admin](https://gitee.com/xuebusi/redis-admin)：Redis Admin是一个简单好用的Redis缓存图形化管理工具，包含Redis的5种数据类型的CRUD操作。
* [RedisFront](https://gitee.com/dromara/RedisFront)：RedisFront是一款开源跨平台Redis桌面客户端工具，支持单机模式、集群模式、哨兵模式以及SSH隧道连接，由dromara社区开源。
* [Redis Manager](https://github.com/ngbdf/redis-manager)：Redis Manager是Redis一站式管理平台，支持集群的监控、安装、管理、告警以及基本的数据操作功能。
* [XPipe](https://github.com/ctripcorp/x-pipe)：X-Pipe是由携程框架部门研发的Redis多数据中心复制管理系统。
* [CacheCloud](https://github.com/sohutv/cachecloud)：CacheCloud是一个Redis云管理平台，支持Redis多种架构高效管理、有效降低大规模Redis运维成本，提升资源管控能力和利用率，由搜狐开源。
* [Cymbal](https://github.com/dangdangdotcom/cymbal)：Cymbal是当当开源的Redis PaaS平台，目标是帮助技术团队以简单、低成本的方式管理大规模Redis集群。
* [RCT](https://github.com/xaecbd/RCT)：RCT是通过解析RDB文件进行Redis内存结构分析的一站式平台。
* [Redis RDB CLI](https://github.com/leonchen83/redis-rdb-cli)：Redis RDB CLI是一个可以解析、过滤、拆分、合并RDB以及离线分析内存使用情况的工具。
* [RIOT](https://github.com/redis/riot)：RIOT是一个命令行实用程序，旨在帮助你将数据输入和输出Redis。
* [RedisDesktopManagerFX](https://github.com/tanhuang2016/RedisDesktopManagerFX)：这是一个基于Jedis，使用JavaFX开发的Redis GUI工具。
* [RedisLettuceClient](https://gitee.com/tyanzhe/RedisLettuceClient)：RedisLettuceClient是一款基于Java Swing的跨平台的Redis桌面管理工具，支持单机、集群模式连接。
* [RedisFX](https://github.com/tanhuang2016/RedisFX)：RedisFX是一个轻量级、现代主题的Redis GUI工具，使用JavaFX开发。

#### MongoDB库/工具

* [MongoDB](https://github.com/mongodb/mongo-java-driver)：适用于Java、Kotlin和Scala的官方MongoDB驱动程序。
* [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb)：Spring Data MongoDB项目旨在为新数据存储提供熟悉且一致的基于Spring的编程模型，同时保留特定于存储的特性和功能。
* [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo)：ReactiveMongo是一个Scala驱动程序，提供完全非阻塞和异步I/O操作。
* [Mars](https://github.com/whaleal/mars)：Mars是用于Java的MongoDB ORM/ODM框架，由上海锦木信息技术有限公司与中国东方航空公司共同开发。
* [Jongo](https://github.com/bguerout/jongo)：Jongo是Mongo查询语言可在Java中使用。
* [Morphia](https://github.com/MorphiaOrg/morphia)：Morphia是基于Java的MongoDB对象-文档映射器。
* [Mongojack](https://github.com/mongojack/mongojack)：Mongojack将Java对象映射到MongoDB文档。
* [MongoPlus](https://gitee.com/aizuda/mongo-plus)：MongoPlus可以使用MyBatisPlus的方式优雅的操作MongoDB，由爱组搭开源。
* [Morphium](https://github.com/sboesebeck/morphium)：Morphium是唯一一款内置MongoDB消息队列的Java ODM。
* [Casbah](https://github.com/mongodb/casbah)：Casbah是MongoDB的一个遗留接口，设计目的是提供更灵活的Java和Scala访问。
* [MongoDB Plugin](https://github.com/T-baby/MongoDB-Plugin)：MongoDB Plugin是实时跟进官方版本的ORM，让你更加舒适地使用MongoDB。
* [Variety](https://github.com/variety/variety)：Variety是MongoDB的模式分析器。
* [UMongo](https://github.com/agirbal/umongo)：UMongo是用于浏览和管理MongoDB集群的桌面应用程序。
* [Studio 3T](https://studio3t.com/)：Studio 3T是MongoDB的专业图形用户界面。
* [MongoBee](https://github.com/mongobee/mongobee)：MongoBee是一个Java工具，可帮助你管理MongoDB中的更改并将其与你的应用程序同步。
* [Mongo Lambda Query](https://github.com/DarMi7/mongo-lambda-query)：基于Lambda表达式，且面向对象的Mongo数据库查询插件。
* [MongoHelper](https://gitee.com/cym1102/mongoHelper)：Spring Data MongoDB增强工具包，简化CRUD操作，提供类Mybatis Plus的数据库操作体验。
* [POCDriver](https://github.com/johnlpage/POCDriver)：POCDriver是一个单一的JAR文件，允许你从命令行轻松指定和运行多个不同的工作负载。
* [Tayra](https://github.com/EqualExperts/Tayra)：MongoDB的增量备份工具。
* [MongoDB Slow Operations Profiler](https://github.com/idealo/mongodb-slow-operations-profiler)：这款Java Web应用程序收集并存储来自一个或多个MongoDB系统的慢速操作，以便对其进行可视化和分析。
* [SQL To MongoDB Query Converter](https://github.com/vincentrussell/sql-to-mongo-db-query-converter)：SQL To MongoDB Query Converter帮助你根据SQL中提供的查询为MongoDb构建查询。

#### Cassandra库/工具

* [Cassandra Java Driver](https://github.com/apache/cassandra-java-driver)：Cassandra的Java驱动程序。
* [DataStax Java Driver](https://github.com/datastax/java-driver)：适用于Cassandra的DataStax Java驱动程序。
* [Cassandra JDBC Wrapper](https://github.com/ing-bank/cassandra-jdbc-wrapper)：这是Apache Cassandra Java驱动程序的JDBC包装器，它提供了一个简单的JDBC兼容API来与CQL3协同工作，由ING银行开源。
* [Phantom](https://github.com/outworkers/phantom)：Phantom是适用于Cassandra/Datastax Enterprise的响应式类型安全Scala驱动程序。
* [Astyanax](https://github.com/Netflix/astyanax)：Astyanax是Netflix开源的Cassandra Java客户端库。
* [Spring Data Cassandra](https://github.com/spring-projects/spring-data-cassandra)：Spring Data Cassandra为Cassandra提供Spring Data模块熟悉的接口。
* [Hector](https://github.com/hector-client/hector)：Hector是Cassandra的高级客户端库。
* [Cassie](https://github.com/twitter-archive/cassie)：Cassie是一个小型、轻量级的Cassandra客户端，基于Finagle构建，由Twitter开源。
* [Achilles](https://github.com/doanduyhai/Achilles)：Achilles是Apache Cassandra的一个开源高级对象映射器。
* [Stargate](https://github.com/stargate/stargate)：Stargate是部署在客户端应用程序和Cassandra数据库之间的数据网关，DataStax开源。
* [Cassandra Reaper](https://github.com/thelastpickle/cassandra-reaper)：Reaper是一种集中式、有状态且高度可配置的工具，用于针对单站点或多站点集群运行Cassandra修复，由DataStax开源。
* [Aegisthus](https://github.com/Netflix/aegisthus)：Aegisthus是Cassandra的批量数据管道，由Netflix开源。
* [Cassandra Schema Migration](https://github.com/patka/cassandra-migration)：该库可用于在Java应用程序内实现Cassandra数据库模式的迁移。
* [Cassandra Migration](https://github.com/smartcat-labs/cassandra-migration-tool-java)：适用于Java的Cassandra模式迁移工具。
* [Cassandra Migration](https://github.com/Contrast-Security-OSS/cassandra-migration)：Cassandra Migration是一个简单且轻量级的Cassandra数据库迁移工具，基于Flyway项目，由Contrast开源。
* [CQLMigrate](https://github.com/sky-uk/cqlmigrate)：CQLMigrate是一个用于在Cassandra集群上执行模式迁移的库，由英国天空公司开源。

#### Memcached库/工具

* [Folsom](https://github.com/spotify/folsom)：Folsom是Java的异步Memcached客户端库，由Spotify开源。
* [XMemcached](https://github.com/killme2008/xmemcached)：XMemcached是一个高性能、易于使用的Java阻塞多线程Memcached客户端。
* [Spymemcached](https://github.com/dustin/java-memcached-client)：Spymemcached是一个用Java编写的简单、异步、单线程Memcached客户端。

#### Zookeeper库/工具

* [Apache Curator](https://github.com/apache/curator)：Curator是ZooKeeper的Java/JVM客户端库，由Netflix开源。
* [ZkClient](https://github.com/sgroschupf/zkclient)：ZkClient是Zookeeper的客户端库，由Datameer开源。
* [ZKClient](https://github.com/adyliu/zkclient)：一个简单有效的Zookeeper Java客户端，由搜狐维护。
* [PrettyZoo](https://github.com/vran-dev/PrettyZoo)：PrettyZoo是由JavaFX和Apache Curator创建的Zookeeper GUI。
* [ZkUI](https://github.com/DeemOpen/zkui)：ZkUI是允许在Zookeeper上进行CRUD操作的UI仪表板。
* [ZkWeb](https://github.com/zhitom/zkweb)：ZkWeb是用于管理和监控Zookeeper集群的Zookeeper Web应用，内置H2数据库。
* [Taokeeper](https://github.com/alibaba/taokeeper)：Taokeeper是Zookeeper的监视器，由阿里开源。
* [Shepher](https://github.com/XiaoMi/shepher)：Shepher是ZooKeeper的管理工具，在小米作为配置管理中心使用。
* [KafkaUI Lite](https://gitee.com/freakchicken/kafka-ui-lite)：非常好用的Kafka UI客户端工具，同时支持Zookeeper、Redis。
* [Zookeeper Visualizer](https://github.com/xin497668869/zookeeper-visualizer)：Zookeeper的可视化管理工具。
* [ZKCopy](https://github.com/ksprojects/zkcopy)：用于在不同集群之间快速复制ZooKeeper数据的工具。
* [ZooInspector](https://github.com/zzhang5/zooinspector)：Zookeeper加强版管理面板。

#### ClickHouse库/工具

* [ClickHouse Java](https://github.com/ClickHouse/clickhouse-java)：用于连接ClickHouse并处理各种格式数据的Java库。
* [Clickhouse4j](https://github.com/Blynk-Technologies/clickhouse4j)：Clickhouse4j是官方ClickHouse JDBC驱动程序的更轻更快的替代品。
* [ClickHouse Native JDBC](https://github.com/housepower/ClickHouse-Native-JDBC)：用于在Java中访问ClickHouse的原生JDBC库，还提供用于与Spark集成的库。
* [Clickhouse Scala](https://github.com/crobox/clickhouse-scala-client)：Clickhouse Scala客户端，以响应式方式访问Clickhouse数据库。
* [CKibana](https://github.com/TongchengOpenSource/ckibana)：CKibana是一项使用原生Kibana方便分析ClickHouse数据的服务，由同程旅行开源。
* [Graphhouse](https://github.com/ClickHouse/graphouse)：Graphhouse允许你使用ClickHouse作为Graphite存储。
* [ClickHouse Client](https://github.com/Ecwid/clickhouse-client)：ClickHouse的Java/Kotlin客户端。

#### ElasticSearch库/工具

* [ElasticSearch Java](https://github.com/elastic/elasticsearch-java)：ElasticSearch官方Java客户端。
* [Jest](https://github.com/searchbox-io/Jest)：Jest是ElasticSearch的Java HTTP REST客户端。
* [Bboss](https://github.com/bbossgroups/bboss-elasticsearch)：Bboss是一个很好的ElasticSearch Java REST客户端，它操作和访问ElasticSearch的方式与MyBatis类似。
* [Flummi](https://github.com/otto-de/flummi)：Flummi是ElasticSearch的客户端库，提供了全面的Java查询DSL API，并通过HTTP/JSON与ElasticSearch集群进行通信。
* [Pallas](https://github.com/vipshop/pallas)：Pallas是唯品会的统一搜索平台，建立在ElasticSearch之上，旨在解决各种搜索问题。
* [Easy ES](https://gitee.com/dromara/easy-es)：Easy ES是一款简化ElasticSearch搜索引擎操作的开源框架，全自动智能索引托管，由dromara社区开源。
* [Spring Data Jest](https://github.com/VanRoy/spring-data-jest)：基于Jest Rest客户端的ElasticSearch的Spring Data实现。
* [Spring Data Elasticsearch](https://github.com/spring-projects/spring-data-elasticsearch)：Spring Data Elasticsearch项目提供与Elasticsearch搜索引擎的集成。
* [ESClientRHL](https://gitee.com/zxporz/ESClientRHL)：EsClientRHL是一个可基于Spring Boot的ElasticSearch客户端调用封装工具。
* [EsearchX](https://gitee.com/noear/esearchx)：EsearchX基于OkHttp、Snack3开发，是一个代码直白和简单的Elasticsearch ORM框架。
* [Elastic4s](https://github.com/Philippus/elastic4s)：Elastic4s是一个简洁、惯用、响应式、类型安全的Elasticsearch Scala客户端。
* [Ebatis](https://github.com/ymm-tech/ebatis)：Ebatis是一个声明式ElasticSearch ORM框架。
* [Querqy](https://github.com/querqy/querqy)：Querqy是一个在基于Java的搜索引擎中进行查询预处理的框架。
* [Anserini](https://github.com/castorini/anserini)：Anserini是一个用于可重复信息检索研究的Lucene工具包，由滑铁卢大学开源。
* [ES Fastloader](https://github.com/didi/ES-Fastloader)：ES Fastloader利用Hadoop的容错性和并行性，在多个reducer节点中构建单独的ElasticSearch分片，然后将分片传输到ElasticSearch集群进行服务，由滴滴开源。
* [Elasticsearch JDBC](https://github.com/jprante/elasticsearch-jdbc)：JDBC导入器允许从JDBC源获取数据以索引到Elasticsearch中。
* [Elasticsearch SQL](https://github.com/NLPchina/elasticsearch-sql)：使用此插件，你可以使用熟悉的SQL语法查询Elasticsearch。
* [Luke](https://github.com/DmitryKey/luke)：Luke是一个用于检查Lucene/Solr/Elasticsearch索引的GUI工具。
* [KnowSearch](https://github.com/didi/KnowSearch)：KnowSearch是面向Elasticsearch研发与运维人员，围绕集群、索引构建的零侵入、多租户的Elasticsearch GUI管控平台，由滴滴开源。
* [SQL4ES](https://github.com/Anchormen/sql4es)：SQL4ES是适用于Elasticsearch 6.3.2的JDBC 4.1驱动程序，它实现了大多数JDBC接口。

#### DynamoDB库/工具

* [Jcabi DynamoDB](https://github.com/jcabi/jcabi-dynamo)：AWS DynamoDB SDK的面向对象包装器。
* [Tempest](https://github.com/cashapp/tempest)：适用于Kotlin和Java的类型安全DynamoDB。
* [DynamoDB Transactions](https://github.com/awslabs/dynamodb-transactions)：DynamoDB Transactions在DynamoDB中提供原子性、一致性、隔离性和持久性(ACID)，使你能够更轻松地维护应用程序中的数据正确性。
* [DynamoDB Geo](https://github.com/amazon-archives/dynamodb-geo)：Amazon DynamoDB的地理库使Java开发人员能够轻松创建和查询地理空间数据。
* [Spring Data DynamoDB](https://github.com/michaellavelle/spring-data-dynamodb)：该模块提供对基于AWS DynamoDB构建的数据访问层的增强支持。
* [Amazon DynamoDB Encryption Java](https://github.com/aws/aws-dynamodb-encryption-java)：适用于Java的Amazon DynamoDB加密客户端。
* [Dynamoit](https://github.com/bykka/dynamoit)：这是一个用JavaFX编写的简单的DynamoDB图形客户端。

#### Neo4j库/工具

* [Neo4j Java Driver](https://github.com/neo4j/neo4j-java-driver)：Neo4j的官方Java驱动程序。
* [Spring Data Neo4j](https://github.com/spring-projects/spring-data-neo4j)：Spring Data Neo4j支持从Spring应用程序轻松配置和访问Neo4j图数据库。
* [Neo4j GraphQL](https://github.com/neo4j-graphql/neo4j-graphql)：这是Neo4j的GraphQL Endpoint扩展。
* [Neo4j OGM](https://github.com/neo4j/neo4j-ogm)：Neo4j OGM是Neo4j的快速对象图映射库，针对利用Cypher的基于服务器的安装进行了优化。
* [NeoTypes](https://github.com/neotypes/neotypes)：用于Neo4j的Scala轻量级、类型安全、异步驱动程序。

#### Etcd库/工具

* [JEtcd](https://github.com/etcd-io/jetcd)：JEtcd是etcd v3的官方Java客户端。
* [Boon Etcd](https://github.com/boonproject/boon/tree/master/etcd)：Boon etcd是etcd的Java客户端。
* [Etcd Java](https://github.com/IBM/etcd-java)：IBM开源的etcd v3 Java客户端库。
* [JEtcd](https://github.com/justinsb/jetcd)：一个简单的Java etcd客户端库。
* [Etcd4j](https://github.com/jurmous/etcd4j)：Etcd4j是etcd的客户端库。

#### Milvus库/工具

* [Milvus Java SDK](https://github.com/milvus-io/milvus-sdk-java)：Milvus的Java SDK。
* [MilvusPlus](https://gitee.com/dromara/MilvusPlus)：MilvusPlus是一个功能强大的Java库，旨在简化与Milvus向量数据库的交互，为开发者提供类似MyBatis Plus注解和方法调用风格的直观API，由dromara社区开源。

#### Vault库/工具

* [Vault Java Driver](https://github.com/BetterCloud/vault-java-driver)：HashiCorp的Vault机密管理解决方案的零依赖Java客户端。
* [Spring Vault](https://github.com/spring-projects/spring-vault)：Spring Vault提供客户端访问、存储和撤销机密信息的支持。

## 安全

这里列出了安全相关的库、框架、组件，例如JWT、OAuth和CAS。

#### 安全框架

* [JAAS](https://docs.oracle.com/en/java/javase/11/security/java-authentication-and-authorization-service-jaas-reference-guide.html)：JAAS实现了标准可插拔身份验证模块(PAM)框架的Java版本，由Oracle开发。
* [Spring Security](https://github.com/spring-projects/spring-security)：Spring Security是一个功能强大且高度可定制的身份验证和访问控制框架，由VMware开源。
* [Jakarta Security](https://github.com/jakartaee/security)：Jakarta Security提供了一组必需的安全功能，包括身份验证、授权、数据完整性和传输安全。
* [Apache Shiro](https://github.com/apache/shiro)：Shiro是一个功能强大且易于使用的Java安全框架，可以执行身份验证、授权、加密和会话管理。
* [Sa-Token](https://gitee.com/dromara/sa-token)：Sa-Token是一个轻量级Java权限认证框架，由dromara社区开源。
* [JustAuth](https://github.com/justauth/JustAuth)：JustAuth是一个第三方授权登录的工具类库，它可以让我们脱离繁琐的第三方登录SDK。
* [Sureness](https://gitee.com/dromara/sureness)：Sureness是一个简单高效的开源安全框架，专注于REST API的保护，由dromara社区开源。
* [SuperTokens](https://github.com/supertokens/supertokens-core)：Auth0/Firebase Auth/AWS Cognito的开源替代品。
* [Pac4j](https://github.com/pac4j/pac4j)：Pac4j是一个简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [UAF](https://github.com/eBay/UAF)：UAF是eBay开源的通用身份验证框架。
* [SocialAuth](https://github.com/3pillarlabs/socialauth)：SocialAuth是一个适用于Java和Android的流行社交(OAuth1/OAuth2/混合)身份验证库。
* [Apache Syncope](https://github.com/apache/syncope)：Syncope是一个用于管理企业环境中的数字身份的开源系统。
* [Vertx Auth](https://github.com/eclipse-vertx/vertx-auth)：包含Vert.x和常见身份验证接口的身份验证实现。
* [jCasbin](https://github.com/casbin/jcasbin)：jCasbin是一个强大且高效的Java项目开源访问控制库，它为基于各种访问控制模型的强制授权提供支持。
* [Elytron](https://github.com/wildfly-security/wildfly-elytron)：Elytron是一组用于应用服务器和客户端安全的Java API和SPI，由RedHat开源。
* [OACC](https://github.com/acciente/oacc-core)：OACC是一个功能齐全的API，可强制执行和管理应用程序的身份验证和授权需求。
* [Easy Security](https://gitee.com/aizuda/easy-security)：Easy Security是基于过滤器实现的一款配合Spring快速开发的安全认证框架，由爱组搭开源。
* [WebAuthn4J](https://github.com/webauthn4j/webauthn4j)：WebAuthn4J是一个用于WebAuthn和Apple App Attest服务器端验证的可移植Java库。
* [Google Auth Library](https://github.com/googleapis/google-auth-library-java)：Google提供的Java开源身份验证客户端库。
* [Java Webauthn Server](https://github.com/Yubico/java-webauthn-server)：Java的服务器端Web身份验证库，提供服务器支持Web身份验证(包括密钥身份验证)所需的依赖方操作的实现，由Yubico公司开源。
* [APL](https://github.com/intuit/identity-authz-apl)：APL是一种用于编写授权策略的轻量级高性能语言，由Intuit开发。
* [SAML Client](https://github.com/justinbleach/saml-client)：该库实现了一个非常简单的SAML 2.0客户端，允许使用HTTP POST绑定从合规身份提供商检索经过身份验证的身份。
* [SAML Java](https://github.com/SAML-Toolkits/java-saml)：SAML Java工具包允许你将Java应用程序转变为可连接到IdP(身份提供商)的SP(服务提供商)。
* [LoopAuth](https://gitee.com/lucky-color/loop-auth)：一款Java Web鉴权框架，同时支持RBAC、ABAC，并提供会话管理等功能。
* [Cedar](https://github.com/cedar-policy/cedar-java)：Cedar是一种开源策略语言和评估引擎，使开发人员能够将细粒度的权限表达为在其应用程序中强制执行的易于理解的策略，并将访问控制与应用程序逻辑分离，由AWS开源。
* [SAPL](https://github.com/heutelbeck/sapl-policy-engine)：SAPL是一种用于实现ABAC的强大的策略语言和引擎。
* [PicketLink](https://github.com/picketlink/picketlink)：PicketLink是一个用于保护Java EE应用程序的安全框架，由RedHat开发。
* [OWASP ESAPI Java](https://github.com/ESAPI/esapi-java-legacy)：OWASP ESAPI是一个免费、开源的Web应用程序安全控制库，使程序员可以更轻松地编写风险较低的应用程序。
* [Netryx](https://github.com/OWASP/www-project-netryx)：Netryx是由OWASP exploit小组领导的高级Java安全框架。
* [Soteria](https://github.com/eclipse-ee4j/soteria)：Soteria是Jakarta Security的实现，由Oracle开源。
* [SimpleAuth](https://github.com/jaychang0917/SimpleAuth)：SimpleAuth是一个易于使用的社交身份验证安卓库。

#### JWT库

* [JJWT](https://github.com/jwtk/jjwt)：JJWT旨在成为最易于使用和理解的库，用于在JVM和Android上创建和验证JWT和JWK。
* [Java JWT](https://github.com/auth0/java-jwt)：JWT的Java实现。
* [Pac4j](https://github.com/pac4j/pac4j)：Pac4j是一个简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [Jose4j](https://bitbucket.org/b_c/jose4j/src/master/)：Jose4j库是IETF JOSE工作组的JWS、JWE、JWA和JWK的开源实现，它是用Java编写的，并且仅依赖于JCA API进行加密。
* [Nimbus JOSE JWT](https://bitbucket.org/connect2id/nimbus-jose-jwt)：适用于Java和Android的JWT库，由Connect2id开源。
* [FusionAuth JWT](https://github.com/FusionAuth/fusionauth-jwt)：一个简单易用的Java 8 JWT库，全天验证、签名、编码、解码。
* [Vert.x Auth](https://github.com/vert-x3/vertx-auth)：Vertx框架提供JWT集成的库。
* [Inverno](https://github.com/inverno-io/inverno-mods/tree/master/inverno-security-jose)：Inverno框架提供JWT库，提供JSON对象签名和加密RFC规范的完整实现。
* [JWT](https://github.com/PhilJay/JWT)：轻量级Kotlin JWT实现。
* [JWT Java](https://github.com/BastiaanJansen/jwt-java)：使用流式的API轻松创建和解析JWT并创建自定义JWT验证器。
* [JWT Resource Server](https://github.com/entur/jwt-resource-server)：用于依赖使用Access Tokens进行授权的同步(基于Servlet)OpenID资源服务器的工具。
* [JWTDecode](https://github.com/auth0/JWTDecode.Android)：JWTDecode是一个帮助你解码JWT的库。
* [JWKS RSA Java](https://github.com/auth0/jwks-rsa-java)：一个用于从JWKS端点获取JSON Web Key的Java库。
* [Okta JWT Verifier Java](https://github.com/okta/okta-jwt-verifier-java)：Java版Okta JWT验证器。
* [JWT Scala](https://github.com/jwt-scala/jwt-scala)：Scala的JWT支持库。

#### 授权服务器

* [Spring Authorization Server](https://github.com/spring-projects/spring-authorization-server)：Spring Authorization Server是一个框架，提供OAuth 2.1和OpenID Connect 1.0规范以及其他相关规范的实现。
* [UAA](https://github.com/cloudfoundry/uaa)：UAA是一种多租户身份管理服务，在Cloud Foundry中使用，但也可用作独立的OAuth2服务器。
* [OAuth Apis](https://github.com/OAuth-Apis/apis)：该项目提供了一个OAuth 2.0授权服务器，可用于配置API身份验证，目前不再维护。
* [OxAuth](https://github.com/GluuFederation/oxAuth)：OxAuth是一个开源OpenID Connect提供商(OP)和UMA授权服务器(AS)。
* [Java Authorization Server](https://github.com/authlete/java-oauth-server)：这是Java中的授权服务器实现，支持OAuth 2.0和OpenID Connect。
* [MITREid Connect](https://github.com/mitreid-connect/OpenID-Connect-Java-Spring-Server)：该服务器可用作OpenID Connect身份提供商以及通用OAuth 2.0授权服务器，由MITRE公司和麻省理工学院开源。
* [JAP](https://gitee.com/fujieid/jap)：JAP是一款开源的登录认证中间件，基于模块化设计，为所有需要登录认证的Web应用提供一套标准的技术解决方案。
* [Light OAuth2](https://github.com/networknt/light-oauth2)：一个快速、轻量级、云原生的OAuth 2.0服务器，构建在Light-4j框架之上。
* [Apache Oltu](https://github.com/apache/oltu)：Oltu是OAuth协议的Java语言实现。
* [OAuth2 Server](https://github.com/yoichiro/oauth2-server)：该项目是用Java编写的OAuth2.0的实现。
* [Scala OAuth2 Provider](https://github.com/nulab/scala-oauth2-provider)：用Scala编写的OAuth 2.0服务器端实现。
* [Kotlin OAuth2 Server](https://github.com/myndocs/kotlin-oauth2-server)：灵活的OAuth2服务器库，支持多种框架。
* [OAuth2 Server](https://github.com/jobmission/oauth2-server)：Spring Boot OAuth2服务器。
* [MyOIDC](https://gitee.com/mkk/MyOIDC)：基于OIDC协议的参考实现。
* [Auth](https://github.com/dustlight-cn/auth)：Auth是一个前后端分离的OAuth 2.0授权中心与用户中心，适用于微服务鉴权、单点登录、企业开放平台等场景。
* [Janssen](https://github.com/JanssenProject/jans)：Janssen旨在促进企业数字身份和访问管理基础设施的发展，由Janssen社区开源。
* [IAM](https://iam.tf/)：简化身份认证和访问。
* [WSO2 Identity Server](https://github.com/wso2/product-is)：WSO2 Identity Server是一种开源身份和访问管理解决方案，跨企业和云服务环境联合和管理身份。
* [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)：OpenAM是一种访问管理解决方案，包括身份验证、SSO、授权、联合、权利和Web服务安全，由ForegeRock公司发起。
* [WrenIDM](https://github.com/WrenSecurity/wrenidm)：WrenIDM是一个由社区开发的身份管理系统，具有灵活的数据模型、丰富的扩展点以及JavaScript和Groovy等脚本支持。
* [AuthzForce](https://github.com/authzforce/core)：AuthzForce项目提供了一个符合OASIS XACML标准v3.0的基于属性的访问控制(ABAC)框架，主要由授权策略引擎和RESTful授权服务器组成，由OW2开发。
* [Ego](https://github.com/overture-stack/ego)：Ego是支持多个OpenID身份提供者的OAuth 2.0授权服务，由安大略癌症研究所开源。
* [OAuth2 Server](https://github.com/clouway/oauth2-server)：OAuth2服务器库。
* [PAuth](https://github.com/FinVolution/pauth)：PAuth实现了OAuth2的四种授权模式，用于应用的单点登录、按领域进行划分的用户+角色+应用、资源访问的权限控制等各个功能，由信也科技开源。

#### OAuth库

* [ScribeJava](https://github.com/scribejava/scribejava)：适用于Java的简单OAuth库。
* [Google OAuth Client](https://github.com/googleapis/google-oauth-java-client)：由Google编写的一个功能强大且易于使用的Java库，适用于OAuth 1.0和OAuth 2.0授权标准。
* [JOAuth](https://github.com/twitter/joauth)：使用OAuth验证HTTP请求的Java库，由Twitter开源。
* [Authing Java SDK](https://github.com/Authing/authing-java-sdk)：Authing可以快速实现任何Web、App和企业软件的身份认证和用户管理，由北京蒸汽记忆科技公司开发。
* [OAuth2 Essentials](https://github.com/dmfs/oauth2-essentials)：基于Http Client Essentials的OAuth2客户端实现。
* [Tokens](https://github.com/zalando/tokens)：Tokens是一个用于验证和存储OAuth 2.0服务访问令牌的Java库，它具有弹性、可配置且经过生产测试，并且适用于所有JVM语言，由Zalando开源。
* [AppAuth](https://github.com/openid/AppAuth-Android)：用于与OAuth 2.0和OIDC提供商进行通信的Android客户端SDK。
* [Signpost](https://github.com/mttkay/signpost)：Signpost是一种简单直观的解决方案，用于在Java平台上签署符合OAuth Core 1.0a标准的HTTP消息。
* [CredentialManager](https://github.com/PhilippHeuer/credential-manager)：一个简单的OAuth客户端和CredentialManager库，支持多个存储后端。
* [Okta Spring Boot](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter，使你的Spring Boot应用程序能够通过OAuth 2.0/OIDC 与Okta协同工作。
* [Retroauth](https://github.com/andretietz/retroauth)：一个基于Retrofit构建的库，便于简单处理认证请求。

#### 身份管理平台

* [TOPIAM](https://gitee.com/topiam/eiam)：TOPIAM是一款开源的身份管理与访问控制系统，广泛应用于政府、企业内部、教育机构等身份认证场景。
* [FusionAuth](https://fusionauth.io/)：FusionAuth是一个现代化的客户身份和访问管理(CIAM)平台。
* [MaxKey](https://gitee.com/dromara/MaxKey)：MaxKey是业界领先的IAM-IDaas身份管理和认证产品，支持OAuth 2.x/OpenID Connect、SAML 2.0、JWT、CAS、SCIM等标准协议，由dromara社区开源。
* [Athenz](https://github.com/AthenZ/athenz)：Athenz是一个开源平台，用于动态基础设施中基于X.509证书的服务身份验证和细粒度访问控制，由Yahoo开源。
* [Akto](https://github.com/akto-api-security/akto)：Akto是一个即时开源API安全平台。
* [MOSIP](https://www.mosip.io/#1)：MOSIP是一款开源软件，可供政府或国际组织作为核心构建基础数字身份系统，由班加罗尔国际信息技术学院开发。
* [Guardian](https://github.com/ds-horizon/guardian)：Guardian是一款专为现代应用程序设计的强大开源身份验证和授权解决方案，由Dream11开源。
* [MidPoint](https://github.com/Evolveum/midpoint)：MidPoint是一个综合性身份治理和管理(IGA)平台。
* [OpenIDM](https://www.forgerock.com)：OpenIDM是一个用Java编程语言编写的身份管理系统。
* [Mujina](https://github.com/OpenConext/Mujina)：Mujina是一个SAML2身份和服务提供商(IdP&SP)。
* [Topaz](https://www.topaz.sh/)：Topaz是一种开源授权服务，为应用程序和API提供细粒度、实时、基于策略的访问控制。
* [Iridium](https://github.com/IridiumIdentity/iridium)：Iridium是一个符合OAuth 2.x的客户身份和访问管理(CIAM)系统。
* [OpenID4Java](https://github.com/jbufu/openid4java)：该库允许你为Java Web应用程序启用OpenID。
* [Line FIDO2 Server](https://github.com/line/line-fido2-server)：FIDO是在线身份验证的开放标准，这是Line开源的经过FIDO联盟和依赖方示例的正式认证的实现。
* [FIDO](https://www.strongkey.com/products/software/fido-strong-authentication)：FIDO2协议的开源实现，支持使用公钥加密的无密码强身份验证，由StrongKey开源。
* [PowerAuth Server](https://github.com/wultra/powerauth-server)：PowerAuth Server是实现PowerAuth协议加密的核心后端应用程序，它负责设备注册、激活生命周期、应用程序管理和集成安全。
* [Biscuit Java](https://github.com/biscuit-auth/biscuit-java)：Biscuit是一个开源、基于令牌的授权系统。
* [OpenUnison](https://github.com/TremoloSecurity/OpenUnison)：OpenUnison是一个统一身份管理平台。
* [Perun](https://github.com/CESNET/perun)：Perun是一个主要面向学术环境的身份和访问管理系统，由马萨里克大学开源。
* [Grouper](https://github.com/Internet2/grouper)：Grouper是针对高校常见的高度分布式管理环境和异构信息技术环境而设计的企业级访问管理系统。

#### 单点登录

* [Keycloak](https://github.com/keycloak/keycloak)：适用于现代应用程序和服务的开源身份和访问管理解决方案，由RedHat开源。
* [Apereo CAS](https://github.com/apereo/cas)：CAS是一个企业多语言单点登录解决方案和网络身份提供商，由耶鲁大学开源。
* [Smart SSO](https://github.com/a466350665/smart-sso)：Spring Boot SSO单点登录，OAuth2实现，支持APP登录、分布式。
* [XXL-SSO](https://gitee.com/xuxueli0323/xxl-sso)：XXL-SSO是一个分布式单点登录框架。
* [SSO](https://github.com/kawhii/sso)：CAS单点登录系统，其中包括CAS认证服务、配置中心、监控平台，服务管理的高可用项目。
* [TKey](https://gitee.com/cdk8s/tkey)：TKey以OAuth 2.0标准为接口设计原则的单点登录系统。
* [Kisso](https://gitee.com/baomidou/kisso)：Kisso是基于Cookie的SSO中间件。
* [Waffle](https://github.com/Waffle/waffle)：为流行的Java Web服务器启用嵌入式Windows单点登录。
* [Jeesuite Passport](https://github.com/vakinge/jeesuite-passport)：Jeesuite Passport是面向企业级单点登录、统一认证的一站式解决方案。
* [Authsaur](https://github.com/authsaur/authsaur)：Authsaur帮助更多企业统一和构建标准化的用户身份体系，以数十年优秀开源产品CAS为内核，打造开箱即用的企业级单点登录系统。
* [Ki4so](https://gitee.com/ywbrj042/ki4so)：Ki4so是一个简约、无状态、易扩展、易伸缩的适合于大型互联网Web应用场景的单点登录系统。
* [Jespa](https://www.ioplex.com/)：Jespa是一个纯Java软件库，它直接实现了将Java应用程序轻松高效地集成到Windows环境中所需的Microsoft Windows协议和逻辑。
* [UniAuth](https://github.com/dianrong/UniAuth)：UniAuth是一个统一登录、鉴权、权限管理的综合系统，由点融科技开源。
* [Simple SSO](https://github.com/sheefee/simple-sso)：一个基于Java的简单SSO项目。

#### 安全库

* [Auth0 Java](https://github.com/auth0/auth0-java)：Auth0平台的Java客户端库。
* [Shaun](https://gitee.com/baomidou/shaun)：Shaun是基于pac4j-jwt的WEB安全组件。
* [Message Security Layer](https://github.com/Netflix/msl)：MSL是一种可扩展且灵活的安全消息传递框架，可用于在两个或多个通信实体之间传输数据，由Netflix开源。
* [Microsoft Authentication Library](https://github.com/AzureAD/microsoft-authentication-library-for-java)：MSAL4J使应用程序能够与Microsoft身份平台集成。
* [PipelineDP4j](https://github.com/google/differential-privacy/tree/main/pipelinedp4j)：PipelineDP4j是适用于JVM的端到端差分隐私解决方案，支持各种分布式数据处理框架，由Google开源。
* [KK Anti Reptile](https://gitee.com/kekingcn/kk-anti-reptile)：KK Anti Reptile是凯京科技研发的适用于基于Spring Boot开发的分布式系统反爬虫、防接口盗刷组件。
* [SecurityBuilders](https://github.com/tersesystems/securitybuilder)：该库为java.security类实现了一组流式的API构建器，并提供了类型更安全、更直观的API来访问信任存储、密钥存储和密钥。
* [Java Certificado](https://github.com/Samuel-Oliveira/Java_Certificado)：Java数字证书管理项目。
* [RhizobiaJ](https://github.com/momosecurity/rhizobia_J)：Java安全SDK及编码规范，由陌陌安全团队开源。
* [NTRU](https://github.com/tbuktu/ntru)：NTRUEncrypt和NTRUSign的Java实现。
* [Seckit](https://github.com/alibaba/seckit)：Seckit提供多种安全防护功能，帮助开发者防范常见的安全漏洞，由阿里开源。
* [Fosstars Rating Core](https://github.com/SAP/fosstars-rating-core)：这是一个用于定义和计算开源项目评级的框架，由SAP开源。
* [CSRFGuard](https://github.com/aramrami/OWASP-CSRFGuard)：CSRFGuard是一个实现同步器令牌模式变体的库，用于减轻CSRF攻击的风险，由OWASP开源。
* [reCAPTCHA Spring Boot](https://github.com/mkopylec/recaptcha-spring-boot-starter)：Google reCAPTCHA的Spring Boot Starter。
* [ClamAV Java](https://github.com/solita/clamav-java)：简单的ClamAV Java客户端。

#### LDAP

* [PWM](https://github.com/pwm-project/pwm)：PWM是一个用于LDAP目录的开源密码自助服务应用程序。
* [DavMail](https://github.com/mguessan/davmail)：POP/IMAP/SMTP/Caldav/Carddav/LDAP Exchange和Office 365网关。
* [Spring LDAP](https://github.com/spring-projects/spring-ldap)：Spring LDAP是一个用于简化Java LDAP编程的库，其构建原理与Spring JDBC相同。
* [UnboundID LDAP SDK](https://github.com/pingidentity/ldapsdk)：UnboundID LDAP SDK是一个快速、功能强大、用户友好且完全免费的开源Java库，用于与LDAP目录服务器进行通信。
* [Apache DS](https://github.com/apache/directory-server)：DS是一个完全用Java编写的可扩展、可嵌入的目录服务器，已通过Open Group认证，兼容LDAPv3。
* [Apache Directory Kerby](https://github.com/apache/directory-kerby)：Directory子项目，是Java Kerberos绑定。它提供了丰富、直观且可互操作的实现、库、KDC和各种设施，根据云、Hadoop和移动等现代环境的需要集成了PKI、OTP和令牌。
* [Apache Directory Studio](https://github.com/apache/directory-studio)：Directory Studio是一个完整的目录工具平台，旨在与任何LDAP服务器一起使用，但它是专门为与ApacheDS一起使用而设计的。
* [Spring Data LDAP](https://github.com/spring-projects/spring-data-ldap)：Spring Data LDAP项目旨在为Spring LDAP提供熟悉且一致的存储库抽象。
* [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)：OpenDJ是一种兼容LDAPv3的目录服务，专为Java平台开发，可为组织管理的身份提供高性能、高可用性且安全的存储。
* [LDAP Synchronization Connector](https://github.com/lsc-project/lsc)：LDAP同步连接器从任何数据源(包括数据库、LDAP目录或文件)读取数据，并转换此数据并将其与LDAP目录进行比较，由OW2开发。
* [JXplorer](https://github.com/pegacat/jxplorer)：JXplorer是一个跨平台的LDAP浏览器和编辑器。
* [Ldaptive](https://github.com/vt-middleware/ldaptive)：用于与LDAP服务器交互的简单、可扩展的Java API。
* [Domain Directory Controller](https://github.com/imperva/domain-directory-controller)：DDC是一个Active Directory Java SDK，旨在简化小型、中型和大型项目的AD交互。

#### 安全工具

* [Tsunami](https://github.com/google/tsunami-security-scanner)：Tsunami是一款通用网络安全扫描器，具有可扩展的插件系统，可高置信度地检测高严重性漏洞，由Google开源。
* [PacBot](https://github.com/tmobile/pacbot)：PacBot是一个用于云持续合规性监控、合规性报告和安全自动化的平台，由T-Mobile开源。
* [Wycheproof](https://github.com/google/wycheproof)：Wycheproof项目针对已知攻击测试加密库，由Google开源。
* [Paladin Cloud](https://github.com/PaladinCloud/CE)：Paladin Cloud是一个免费的开源云安全平台，致力于帮助你发现云安全中的盲点。
* [APIKit](https://github.com/API-Security/APIKit)：APIKit可以主动/被动扫描发现应用泄露的API文档，并将API文档解析成BurpSuite中的数据包用于API安全测试，由APISecurity社区开发。
* [TheHive](https://github.com/TheHive-Project/TheHive)：一个可扩展、开源且免费的安全事件响应平台。
* [Ortelius](https://github.com/ortelius/ortelius)：Ortelius是一种专为解耦架构设计的开源持续安全智能解决方案。
* [OpenBAS](https://github.com/OpenBAS-Platform/openbas)：OpenBAS是一个开源平台，允许组织规划、安排和进行网络对手模拟活动和测试，由Filigran公司开源。
* [CloudRec](https://github.com/antgroup/CloudRec)：CloudRec是一个开源的多云安全态势管理(CSPM)平台，旨在帮助企业提升其云环境的安全性，由蚂蚁开发。
* [jSQL Injection](https://github.com/ron190/jsql-injection)：jSQL Injection是一个轻量级应用程序，用于从服务器查找数据库信息。
* [Mariana Trench](https://github.com/facebook/mariana-trench)：Mariana Trench是一个针对Android的专注于安全的静态分析平台，由Facebook开源。
* [CTFCrackTools](https://github.com/0Chencc/CTFCrackTools)：中国国内首个CTF工具框架，旨在帮助CTFer快速攻克难关。
* [Zen](https://github.com/AikidoSec/firewall-java)：Zen是一个嵌入式的Web应用防火墙，能够自主保护你的Java应用免受常见且关键的攻击。
* [HaE](https://github.com/gh0stkey/HaE)：HaE是一款网络安全、领域下的辅助型框架式项目，旨在实现对HTTP消息(包含WebSocket)的高亮标记和信息提取。
* [Zest](https://github.com/zaproxy/zest)：Zest是一种专门的脚本语言，由Mozilla安全团队开发，旨在用于面向Web的安全工具。
* [Keywhiz](https://github.com/square/keywhiz)：Keywhiz是一个用于分发和管理密钥的系统，由Square开源。
* [Mixeway](https://github.com/mixeway/mixewayhub)：Mixeway是一款开源软件，旨在简化使用CICD程序实施的项目的安全保证过程。
* [SecHub](https://github.com/mercedes-benz/sechub)：SecHub提供了一个中央API，可以使用不同的安全工具来测试软件，由奔驰开源。
* [Portecle](https://github.com/scop/portecle)：Portecle是一个用户友好的GUI应用程序，用于创建、管理和检查密钥库、密钥、证书、证书请求、证书吊销列表等。
* [HummerRisk](https://github.com/HummerRisk/HummerRisk)：HummerRisk是开源的云原生安全平台，以非侵入的方式解决云原生的安全和治理问题，由北京瀚马科技开源。
* [KeyStore Explorer](https://github.com/kaikramer/keystore-explorer)：KeyStore Explorer是Java命令行实用程序keytool和jarsigner的免费GUI替代品。
* [UTMStack](https://github.com/utmstack/UTMStack)：UTMStack是一个统一的威胁管理平台，融合了SIEM(安全信息和事件管理)和XDR(扩展检测和响应)技术。
* [Magpie](https://github.com/openraven/magpie)：Magpie是一个免费的开源框架和社区开发的插件集合，可用于构建完整的端到端安全工具，例如CSPM或云安全态势管理器。
* [Siembol](https://github.com/G-Research/siembol)：Siembol基于开源大数据技术提供了可扩展的、先进的安全分析框架，由G-Research开源。
* [PortEx](https://github.com/struppigel/PortEx)：PortEx是一个用于对可移植可执行文件进行静态恶意软件分析的Java库。
* [Vega](https://github.com/subgraph/Vega)：Vega是一个用于测试Web应用程序安全性的平台。
* [X-Road](https://github.com/nordic-institute/X-Road)：X-Road是一种开源软件和生态系统解决方案，可为组织之间提供统一、安全的数据交换，由北欧互操作性解决方案研究所开发。

#### 漏洞工具

* [ZAP](https://github.com/zaproxy/zaproxy)：ZAP是世界上最受欢迎的免费安全工具之一，它可以帮助你在开发和测试应用程序时自动查找Web应用程序中的安全漏洞，由OWASP开源。
* [Burp Suite](https://portswigger.net/burp)：Burp Suite是一个用于测试网络应用程序安全性的图形化工具，由PortSwigger开发。
* [Super Xray](https://github.com/4ra1n/super-xray)：Web漏洞扫描工具Xray的GUI启动器。
* [Woodpecker](https://github.com/woodpecker-framework/woodpecker-framework-release)：Woodpecker是一款漏洞精准检测深度利用框架。
* [ThinkPHP](https://github.com/Lotus6/ThinkphpGUI)：Thinkphp漏洞利用工具，支持各版本TP漏洞检测、命令执行、getshell。
* [RiskScanner](https://github.com/fit2cloud/riskscanner)：RiskScanner是飞致云开源的多云安全合规扫描平台，基于Cloud Custodian、Prowler和Nuclei引擎，实现对主流公(私)有云资源的安全合规扫描和漏洞扫描。
* [NacosExploitGUI](https://github.com/charonlight/NacosExploitGUI)：Nacos漏洞综合利用GUI工具，集成了默认口令漏洞、SQL注入漏洞、身份认证绕过漏洞、反序列化漏洞的检测及其利用。
* [Fiora](https://github.com/bit4woo/Fiora)：漏洞PoC框架Nuclei的图形版。
* [Poc2jar](https://github.com/f0ng/poc2jar)：Java编写，Python作为辅助依赖的漏洞验证、利用工具。
* [Hyacinth](https://github.com/pureqh/Hyacinth)：一款Java漏洞集合工具。
* [ThreadFix](https://github.com/denimgroup/threadfix)：ThreadFix是一个软件漏洞管理平台。
* [Artillery](https://github.com/Weik1/Artillery)：Java插件化漏洞扫描器，GUI基于JavaFX，POC目前集成WebLogic、Tomcat、Shiro、Spring。
* [JavaSecLab](https://github.com/whgojp/JavaSecLab)：JavaSecLab是一款综合型Java漏洞平台，提供相关漏洞缺陷代码、修复代码、漏洞场景、审计SINK点、安全编码规范、漏洞流量分析，覆盖多种漏洞场景。
* [Oday](https://github.com/Janhsu/oday)：JavaFX编写的POC管理和漏洞扫描小工具。
* [CaA](https://github.com/gh0stkey/CaA)：CaA是一款网络安全(漏洞挖掘)领域下的辅助型项目，主要用于分析、拆解HTTP协议报文，提取HTTP协议报文中的参数、路径、文件、参数值等信息。
* [Godzilla](https://github.com/BeichenDream/Godzilla)：哥斯拉WebShell管理工具。
* [BlueTeamTools](https://github.com/abc123info/BlueTeamTools)：蓝队分析研判工具箱，功能包括内存马反编译分析、各种代码格式化、网空资产测绘功能、溯源辅助、解密冰蝎流量、解密哥斯拉流量等。
* [Nuclei](https://github.com/Yong-An-Dang/nuclei-plus)：基于Nuclei的功能增强。
* [RexHa](https://github.com/zangcc/Aazhen-RexHa)：RexHa是一款JavaFX图形化漏洞扫描工具。
* [ShiroAttack2](https://github.com/SummerSec/ShiroAttack2)：Shiro550反序列化漏洞利用工具。
* [ShiroExploit](https://github.com/feihong-cs/ShiroExploit-Deprecated)：Shiro550/Shiro721一键化利用工具，支持多种回显方式。
* [Behinder](https://github.com/rebeyond/Behinder)：冰蝎动态二进制加密网站管理客户端。
* [MemShellParty](https://github.com/ReaJason/MemShellParty)：MemShellParty是一款专注于主流Web中间件的内存马快速生成工具，致力于简化安全研究人员和红队成员的工作流程，提升攻防效率。
* [Ysoserial](https://github.com/frohoff/ysoserial)：Ysoserial是一种概念验证工具，用于生成利用不安全的Java对象反序列化的有效负载。
* [Ysomap](https://github.com/wh1t3p1g/ysomap)：Ysomap是一款适配于各类实际复杂环境的Java反序列化利用框架，可动态配置具备不同执行效果的Java反序列化利用链Payload。
* [JYso](https://github.com/qi4L/JYso)：可以同时当做Ysoserial与JNDIExploit使用的工具，同时具备多种JNDI高版本、WAF、RASP的Bypass功能。
* [Rogue JNDI](https://github.com/veracode-research/rogue-jndi)：针对JNDI注入攻击的恶意LDAP服务器。
* [JNDI Injection Exploit](https://github.com/welk1n/JNDI-Injection-Exploit)：JNDI Injection Exploit是一个生成可用JNDI链接并通过启动RMI服务器、LDAP服务器和HTTP服务器提供后台服务的工具。
* [MarshalSec](https://github.com/mbechler/marshalsec)：Java Unmarshaller安全性，将数据转化为代码执行。
* [JNDIMap](https://github.com/X1r0z/JNDIMap)：JNDIMap是一个强大的JNDI注入利用框架，支持RMI、LDAP和LDAPS协议，包含多种高版本JDK绕过方式。
* [PPPYSO](https://github.com/Whoopsunix/PPPYSO)：PPPYSO是一个Java反序列化概念验证框架，仅为安全防护研究提供参考。
* [JavaRce](https://github.com/Whoopsunix/JavaRce)：实战场景较通用的Java Rce相关漏洞的利用方式。
* [MySQL Fake Server](https://github.com/4ra1n/mysql-fake-server)：用于渗透测试过程中的假MySQL服务器。
* [Ysogate](https://github.com/H4cking2theGate/ysogate)：Ysogate是一个Java综合利用工具，支持JNDI注入相关利用，包含多种高版本JDK绕过方式，且支持片段化Gadget生成和组合。
* [JNDIEXP](https://github.com/Bl0omZ/JNDIEXP)：JNDI在Java高版本的利用工具。
* [JNDInjector](https://github.com/rebeyond/JNDInjector)：一个高度可定制化的JNDI和Java反序列化利用工具。
* [Java Memshell Generator](https://github.com/pen4uin/java-memshell-generator)：一款支持高度自定义的Java内存马生成工具。
* [Java Echo Generator](https://github.com/pen4uin/java-echo-generator)：一款支持高度自定义的Java回显载荷生成工具。
* [SerializationDumper](https://github.com/NickstaDB/SerializationDumper)：一种以更易于理解的形式转储和重建Java序列化流和Java RMI数据包内容的工具。
* [JNDI Injection Exploit Plus](https://github.com/cckuailong/JNDI-Injection-Exploit-Plus)：JNDI Injection Exploit Plus是一个用于生成可工作的JNDI链接并通过启动RMI服务器、LDAP服务器和HTTP服务器提供后台服务的工具。
* [Java Chains](https://github.com/vulhub/java-chains)：Java Chains是一个Java Payload生成与漏洞利用Web平台。
* [WSMemShell](https://github.com/veo/wsMemShell)：WebSocket内存马/Webshell，一种新型内存马/WebShell技术。
* [Java MemShell Scanner](https://github.com/c0ny1/java-memshell-scanner)：通过JSP脚本扫描并查杀各类中间件内存马。
* [MemShell](https://github.com/rebeyond/memShell)：驻留在Java Web服务器的内存中的WebShell。
* [MemShellGene](https://github.com/suizhibo/MemShellGene)：一款Java内存马生成、测试工具。
* [Firing Range](https://github.com/google/firing-range)：Firing Range是Web应用程序安全扫描器的测试台，为一系列漏洞提供综合、广泛的覆盖，由Google开源。
* [Shell Analyzer](https://github.com/4ra1n/shell-analyzer)：通过Java Agent查杀内存马，提供简易方便的GUI界面。
* [Code Inspector](https://github.com/4ra1n/code-inspector)：Code Inspector是一个Java自动代码审计工具，尤其针对Spring Boot框架。
* [ShiroScan](https://github.com/fupinglee/ShiroScan)：ShiroScan用于检测存在Shiro反序列化漏洞的Key值。
* [Serianalyzer](https://github.com/mbechler/serianalyzer)：Serianalyzer是一个静态字节码分析器，跟踪反序列化期间调用的方法进行的原生方法调用。

#### 安全培训

* [CRAPI](https://github.com/OWASP/crAPI)：CRAPI在设计上很容易受到攻击，但你将能够安全地运行它来教育/培训自己，由OWASP开源。
* [WebGoat](https://github.com/WebGoat/WebGoat)：WebGoat是由OWASP维护的故意不安全的Web应用程序，旨在教授Web应用程序安全课程。
* [BodgeIt](https://github.com/psiinon/bodgeit)：BodgeIt Store是一个易受攻击的Web应用程序，目前针对渗透测试的新手。
* [OWASP Security Shepherd](https://github.com/OWASP/SecurityShepherd)：OWASP Security Shepherd项目是一个Web和移动应用程序安全培训平台，旨在培养和提高不同技能人群的安全意识。
* [MASTG Hacking Playground](https://github.com/OWASP/MASTG-Hacking-Playground)：MASTG Hacking Playground是一系列教育性iOS和Android移动应用程序，这些应用程序故意构建为不安全的，以便为开发人员、安全研究人员和渗透测试人员提供实用指导。

#### 自保护

* [OpenRASP](https://github.com/baidu/openrasp)：OpenRASP是百度安全推出的一款免费、开源的应用运行时自我保护产品。
* [JRASP Agent](https://github.com/jvm-rasp/jrasp-agent)：专注于JVM的运行时防御系统RASP。
* [Hdiv](https://github.com/hdiv/hdiv)：Hdiv是实时、自我保护应用程序开源软件的领先提供商。

#### 跨域身份管理

* [OSIAM](https://github.com/osiam/osiam)：OSIAM是一种安全身份管理解决方案，提供基于REST的身份验证和授权服务。
* [Apache SCIMple](https://github.com/apache/directory-scimple)：Apache SCIMple是SCIM 2.0规范的实现，由宾夕法尼亚州立大学开源。
* [SCIMano](https://github.com/SAP/scimono)：SAP SCIMano是用于身份管理的SCIM 2.0行业标准的Java参考实现。
* [UnboundID SCIM 2 SDK](https://github.com/pingidentity/scim2)：适用于Java的UnboundID SCIM 2.0 SDK。
* [SCIM SDK](https://github.com/Captain-P-Goldfish/SCIM-SDK)：这是RFC7643和RFC7644定义的SCIM(跨域身份管理系统)协议的开源实现。
* [INDIGO IAM](https://github.com/indigo-iam/iam)：INDIGO IAM是一项身份和访问管理服务，最初是在INDIGO-Datacloud Horizon 2020项目背景下开发的，目前由INFN维护和开发。
* [WSO2 Charon](https://github.com/wso2/charon)：WSO2 Charon是SCIM协议的开源实现，SCIM协议是身份配置的开放标准。
* [SCIM](https://github.com/GluuFederation/scim)：SCIM服务器/客户端。

#### 加密库

* [Tink](https://github.com/google/tink)：Tink是一个多语言、跨平台的开源库，它提供安全、易于正确使用且难以被滥用的加密API，由Google开发。
* [Conceal](https://github.com/facebookarchive/conceal)：Conceal提供了一组Java API来在Android上执行加密，由Facebook开源。
* [BouncyCastle Java](https://github.com/bcgit/bc-java)：BouncyCastle Java发行版。
* [Apache Commons Crypto](https://github.com/apache/commons-crypto)：Commons Crypto是一个使用AES-NI优化的加密库，它提供了密码级别和Java流级别的Java API。
* [LibSignal Protocol Java](https://github.com/signalapp/libsignal-protocol-java)：一种可在同步和异步消息传递环境中工作的棘轮前向保密协议，由Open Whisper Systems开发。
* [Amazon Corretto Crypto Provider](https://github.com/corretto/amazon-corretto-crypto-provider)：Amazon Corretto Crypto Provider是通过标准JCA/JCE接口公开的高性能加密实现的集合。
* [Dragonwell Security Provider](https://github.com/dragonwell-project/alibaba-dragonwell-security-provider)：Dragonwell Security Provider是一个Java安全提供程序，它实现了Java加密扩展(JCE)和Java安全套接字扩展(JSSE)的部分内容，由阿里开源。
* [BGMProvider](https://gitee.com/openeuler/bgmprovider)：BGMProvider目标是提供一个完整的GMTLS Java实现，由华为开发。
* [Themis](https://github.com/cossacklabs/themis)：Themis是一个开源高级加密服务库，用于在身份验证、存储、消息传递、网络交换等过程中保护数据。
* [Jasypt](https://github.com/jasypt/jasypt)：Jasypt是一个Java库，允许开发人员以最小的努力向项目添加基本的加密功能，而无需深入了解密码学的工作原理。
* [Enigma](https://github.com/mikepound/enigma)：Enigma的Java实现，以及解密它的现代攻击。
* [Cryptomator](https://github.com/cryptomator/cryptomator)：Cryptomator为云中的文件提供多平台透明客户端加密。
* [Cryptacular](https://github.com/vt-middleware/cryptacular)：对Java版BouncyCastle加密API的友好补充。
* [Cipher.so](https://github.com/linisme/Cipher.so)：将密码等安全数据加密到本机.so库中的简单方法。
* [Encrypt](https://github.com/GcsSloop/encrypt)：适用于Java和Android的加解密工具库。
* [Java AES Crypto](https://github.com/tozny/java-aes-crypto)：一个简单的Android库，用于加密和解密字符串，旨在避免大多数此类类所遭受的经典错误。
* [Conscrypt](https://github.com/google/conscrypt)：Conscrypt是一个Java安全提供程序，它实现了部分Java加密扩展和Java安全套接字扩展，由Google开源。
* [Themis](https://github.com/cossacklabs/themis)：易于使用的数据保护加密框架，具有前向保密和安全数据存储的安全消息传递，由小米开源。
* [Password4j](https://github.com/Password4j/password4j)：Password4j是一个Java用户友好的加密库，用于使用不同的密钥派生函数(KDF)和加密哈希函数(CHF)来加密和验证密码。
* [Lazysodium](https://github.com/terl/lazysodium-java)：Libsodium加密库的Java实现。
* [Libsodium JNI](https://github.com/joshjdevl/libsodium-jni)：Android NaCL JNI封装。
* [Jscep](https://github.com/seize-the-dave/jscep)：Jscep是SCEP协议的Java实现。
* [Noise Java](https://github.com/rweather/noise-java)：Noise Java是Noise协议的纯Java实现。
* [Keyczar](https://github.com/google/keyczar)：易于使用的加密工具包，由Google开源。
* [AES](https://github.com/mervick/aes-everywhere)：AES是跨语言加密库，它提供了在不同编程语言和不同平台上使用单一算法加密和解密数据的能力。
* [AWS Encryption SDK](https://github.com/aws/aws-encryption-sdk-java)：AWS加密SDK。
* [JNCryptor](https://github.com/RNCryptor/JNCryptor)：RNCryptor的Java实现。
* [Clusion](https://github.com/encryptedsystems/Clusion)：来自布朗大学加密系统实验室的可搜索加密库。
* [Encryptor4j](https://github.com/martinwithaar/Encryptor4j)：Encryptor4j由一组包装器和实用程序类组成，使你可以更轻松地在应用程序中利用加密技术。
* [IDMask](https://github.com/patrickfav/id-mask)：IDMask是一个Java库，用于在需要公开发布内部ID(例如来自数据库的ID)以隐藏其实际值并防止伪造时屏蔽内部ID。
* [HTTP Signatures Java Client](https://github.com/tomitribe/http-signatures-java)：HTTP签名提供了一种机制，通过该机制可以使用共享密钥对HTTP消息进行数字“签名”，以验证发送者的身份并验证消息在传输过程中未被篡改。
* [Ed25519](https://github.com/RubyCrypto/ed25519)：Ed25519高性能公钥签名系统作为RubyGem(MRI C扩展和JRuby Java扩展)。
* [Hiss](https://github.com/Tap30/hiss)：Hiss是一个Java/Kotlin字段级加密和哈希库，允许你加密并计算对象中选定(带注解)字段的哈希值。
* [Datasafe](https://github.com/adorsys/datasafe)：Datasafe是一个专为开发者和企业量身定制的强大库，提供加密和版本化的数据存储。
* [Bouncy GPG](https://github.com/neuhalje/bouncy-gpg)：将Bouncy Castle和OpenGPG一起使用。
* [PGPainless](https://github.com/pgpainless/pgpainless)：PGPainless是一个易于使用的OpenPGP库，适用于Java和Android应用程序。
* [OpenPGP API](https://github.com/open-keychain/openpgp-api)：OpenPGP API提供了一些方法，用于执行OpenPGP操作，例如签名、加密、解密、验证等。
* [CloudCrypto](https://github.com/liuweiran900217/CloudCrypto)：用于云存储应用程序的加密原语实现的库，由北京航空航天大学开源。
* [ART](https://github.com/facebookresearch/asynchronousratchetingtree)：ART是一种端到端加密群组消息协议，它旨在提供可扩展的群组消息传递，同时保持强大的安全保障，由Facebook开源。
* [Scytale](https://github.com/yakivmospan/scytale)：一个管理Android不同API上密钥生成、密钥存储和加密的工具。
* [OpenJCEPlus](https://github.com/IBM/OpenJCEPlus)：OpenJCEPlus加密提供程序是JCE API的实现，由IBM开源。
* [Cryptography Kotlin](https://github.com/whyoleg/cryptography-kotlin)：Kotlin的类型安全多平台密码库。

#### 密码库

* [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)：Nbvcxz是一个密码强度估计器。
* [Scrypt](https://github.com/wg/scrypt)：scrypt密钥派生函数的纯Java实现以及C实现的JNI接口，包括SSE2优化版本。
* [Passay](https://github.com/vt-middleware/passay)：Passay是Java的密码策略实现，由弗吉尼亚理工大学开源。
* [GoogleAuth](https://github.com/wstrange/GoogleAuth)：GoogleAuth是一个Java服务器库，它实现RFC 6238中指定的基于时间的一次性密码(TOTP)算法。
* [Zxcvbn4j](https://github.com/nulab/zxcvbn4j)：这是zxcvbn的Java端口，zxcvbn是一个JavaScript密码强度估计器。
* [Java TOTP](https://github.com/samdjstevens/java-totp)：用于实现基于时间的多重身份验证一次性密码的Java库。
* [Google Authenticator](https://github.com/google/google-authenticator)：包括针对多个移动平台的一次性密码生成器的实现，由Google开源。
* [OTP Java](https://github.com/BastiaanJansen/OTP-Java)：一款小型且易于使用的Java一次性密码生成器，实现RFC 4226和RFC 6238。
* [Java OTP](https://github.com/jchambers/java-otp)：Java-OTP是一个用于生成HOTP(RFC 4226)或TOTP(RFC 6238)一次性密码的Java库。
* [OneTrickPony](https://github.com/Osmerion/OneTrickPony)：OneTrickPony是一个现代Java库，它实现了对一次性密码(OTP)的支持。
* [Recceda OTP](https://github.com/mikechiloane/recceda-otp)：Recceda OTP是一个简单、安全且可配置的Java一次性密码生成与验证库。
* [OpenKeepass](https://github.com/cternes/openkeepass)： OpenKeepass是一个用于读取和写入KeePass数据库的Java库。
* [KeePassJava2](https://github.com/jorabin/KeePassJava2)：KeePass密码数据库的Java API。
* [1Time](https://github.com/atlassian/1time)：RFC-6238和RFC-4226的Java/Kotlin轻量级实现，用于生成和验证基于时间的一次性密码(TOTP)，Atlassian开源。
* [JHash](https://github.com/amdelamar/jhash)：Java中的密码哈希实用程序，支持PBKDF2 hmac SHA1/SHA256/SHA512、BCRYPT和SCRYPT，它会自动加盐，并具有Pepper选项。
* [RandPassGenerator](https://github.com/nsacyber/RandPassGenerator)：RandPassGenerator是一个简单的命令行实用程序，用于生成随机密码、密码短语和原始密钥，由美国国家安全局网络安全局开源。
* [Aerogear OTP Java](https://github.com/aerogear-attic/aerogear-otp-java)：根据RFC 4226生成一次性密码的Java库。
* [JSS](https://github.com/dogtagpki/jss)：NSS是一组库，旨在支持跨平台开发启用安全性的客户端和服务器应用程序。
* [Strongbox](https://github.com/schibsted/strongbox)：Strongbox是AWS的秘钥管理器。

#### 加密算法

* [Kalium](https://github.com/abstractj/kalium)：网络和密码学(NaCl)库的Java绑定。
* [GM JSSE](https://github.com/aliyun/gm-jsse)：开源国密通信纯Java JSSE实现，由阿里开源。
* [SM Crypto](https://github.com/antherd/sm-crypto)：国密算法SM2、SM3和SM4的Java版。
* [GMHelper](https://github.com/ZZMarquis/gmhelper)：国密SM2/SM3/SM4算法简单封装。
* [EdDSA Java](https://github.com/str4d/ed25519-java)：这是EdDSA在Java中的实现。
* [Dilithium](https://github.com/mthiim/dilithium-java)：后量子加密算法Dilithium的实验性Java实现。
* [JPBC](https://github.com/junwei-wang/cpabe)：该库是密文策略属性加密(CP-ABE)的Java实现，由斯坦福开源。
* [jBCrypt](https://github.com/jeremyh/jBCrypt)：jBCrypt是OpenBSD Blowfish密码哈希算法的Java实现。
* [SM2Java](https://github.com/PopezLotado/SM2Java)：国密SM2、SM3 Java实现。
* [GMSM Java](https://gitee.com/cn-openjava/gmsm-java)：国密算法Java版，包含非对称算法SM2、对称算法SM4、摘要算法SM3。
* [SM2/SM3/SM4 Encrypt](https://github.com/xjfuuu/SM2_SM3_SM4Encrypt)：基于Java语言的国密SM2/SM3/SM4算法库，包含加密/解密、签名/验签、摘要算法的实现。
* [HSD Cipher SM](https://github.com/gotoworld/hsd-cipher-sm)：国密算法SM2、SM3、SM4实现。
* [Cat](https://gitee.com/bat/cat)：一款小巧的Java加密与解密算法调用工具包。
* [Bcrypt](https://github.com/patrickfav/bcrypt)：bcrypt密码哈希函数的Java独立实现。
* [Shamir](https://github.com/codahale/shamir)：Shamir的秘密共享算法在GF(256)上的Java实现。
* [Argon2 JVM](https://github.com/phxql/argon2-jvm)：JVM的Argon2绑定。
* [Argon2Kt](https://github.com/lambdapioneer/argon2kt)：Argon2Kt是Argon2密码哈希的绑定，允许在Android上轻松安全地进行内存硬密码哈希处理。
* [Jargon2](https://github.com/kosprov/jargon2-api)：Jargon2是一个类似构建器的API，用于配置和使用Hasher和Verifier API来计算和验证密码哈希值。
* [2FA](https://github.com/j256/two-factor-auth)：2因素身份验证Java代码，使用基于时间的一次性密码(TOTP)算法。
* [XXTEA Java](https://github.com/xxtea/xxtea-java)：XXTEA是一种快速且安全的加密算法，这是一个用于Java的XXTEA库。
* [Tencent Kona SM Suite](https://github.com/Tencent/TencentKonaSMSuite)：腾讯Kona SM Suite是一套Java安全提供程序，支持算法SM2、SM3和SM4，以及协议TLCP/GMSSL、TLS 1.3和TLS 1.2。
* [Chronicle Salt](https://github.com/OpenHFT/Chronicle-Salt)：NaCl库的Chronicle包装器。
* [Tongsuo Java SDK](https://github.com/Tongsuo-Project/tongsuo-java-sdk)：Tongsuo-Java-SDK是一个Java安全提供程序，它实现了部分Java加密扩展和Java安全套接字扩展。
* [SMCryptoj](https://github.com/zhuobie/smcryptoj)：SM国密算法的Java绑定。
* [Homomorphic Encryption](https://github.com/adwise-fiu/Homomorphic_Encryption)：包含ElGamal、Paillier、Goldweiser-Micali和DGK同态加密系统的软件包，由佛罗里达国际大学开源。
* [GmSSL Java](https://github.com/GmSSL/GmSSL-Java)：本项目是GmSSL密码库的Java语言封装，可以用于Java环境和Android系统上的应用开发。
* [Java FPE](https://github.com/mysto/java-fpe)：NIST批准的FF3和FF3-1格式保留加密(FPE)算法在Java中的实现。
* [Murmur](https://github.com/sangupta/murmur)：Murmur是所有Murmur哈希的纯Java实现。
* [Curve25519](https://github.com/signalapp/curve25519-java)：Curve25519的Java实现，在原生代码可用时由原生代码支持，由Open Whisper Systems开发。
* [Format Preserving Encryption Java](https://github.com/idealista/format-preserving-encryption-java)：NIST批准的格式保留加密(FPE)在Java中的实现。
* [Whitebox Crypto AES Java](https://github.com/ph4r05/Whitebox-crypto-AES-java)：Java中的白盒AES实现。
* [Javallier](https://github.com/n1analytics/javallier)：Paillier部分同态加密的Java库。
* [KyberJCE](https://github.com/fisherstevenk/kyberJCE)：Kyber后量子IND-CCA2 KEM的纯Java实现。
* [Blake2b](https://github.com/alphazero/Blake2b)：Blake2b是BLAKE2b加密哈希函数的高性能Java实现。
* [AES GCM SIV](https://github.com/line/aes-gcm-siv)：AES GCM SIV是一种经过认证的加密算法，旨在提供抗随机数滥用的能力，由Line开源。
* [SecretsShare](https://github.com/timtiemens/secretshare)：《应用密码学》中描述的Shamir秘密共享算法的Java实现。

#### 接口加密

* [Client Encryption Java](https://github.com/Mastercard/client-encryption-java)：符合Mastercard API的有效负载加密/解密库。
* [Monkey API Encrypt](https://github.com/yinjihuan/monkey-api-encrypt)：Monkey API Encrypt是对基于Servlet的Web框架API请求进行统一加解密操作的框架。
* [Encrypt Body Spring Boot Starter](https://github.com/Licoy/encrypt-body-spring-boot-starter)：Spring Boot控制器统一的响应体编码/加密与请求体解密的注解处理方式，支持MD5/SHA/AES/DES/RSA。
* [RSA Encrypt Body Spring Boot](https://gitee.com/isuperag/rsa-encrypt-body-spring-boot)：Spring Boot接口加密，可以对返回值、参数值通过注解的方式自动加解密。

#### 数据脱敏

* [eJMask](https://github.com/eBay/ejmask)：eJMask是一个基于JVM的屏蔽库，它提供了一个易于使用的API来屏蔽Java应用程序中的敏感数据，由eBay开源。
* [DeSensitization](https://github.com/allurx/desensitization)：Blur是一个Java库，用于屏蔽和混淆任何数据结构中的敏感数据。
* [Data Mask](https://github.com/bancolombia/data-mask)：与Jackson一起使用的实用程序库，旨在通过使用额外的加密/解密进行屏蔽来保护敏感数据，由哥伦比亚银行开源。
* [Chlorine Finder](https://github.com/dataApps/chlorine-finder)：Chlorine Finder是一个用于检测文本中敏感元素的开源库。
* [Rpamis Security](https://github.com/rpamis/rpamis-security)：Rpamis Security项目是一个基于Mybatis插件开发的安全组件，旨在提供更优于市面上组件的脱敏、加解密落库等企业数据安全解决方案。

#### 零知识证明

* [DIZK](https://github.com/scipr-lab/dizk)：DIZK是一个用于分布式零知识证明系统的Java库，由SCIPR实验室开源。
* [BulletProofLib](https://github.com/bbuenz/BulletProofLib)：无需可信设置即可生成非交互式零知识证明的库，由斯坦福大学开源。
* [JSnark](https://github.com/akosba/jsnark)：这是一个用于构建预处理zk-SNARK电路的Java库。
* [xJsnark](https://github.com/akosba/xjsnark)：xJsnark是一个用于开发zk-SNARK应用程序的高级框架。

#### XSS

* [OWASP Java HTML Sanitizer](https://github.com/owasp/java-html-sanitizer)：一个用Java编写的快速且易于配置的HTML Sanitizer，可让你在Web应用程序中包含第三方编写的HTML，同时防止XSS，由OWASP开源。
* [Lucy XSS Filter](https://github.com/naver/lucy-xss-servlet-filter)：该库是一个基于Java Servlet过滤器的库，为了解决XSS攻击问题而开发，由Naver开源。
* [Coverity Security Library](https://github.com/coverity/coverity-security-library)：Coverity Security Library是一组轻量级的转义例程，用于修复Java Web应用程序中的XSS、SQL注入和其他安全缺陷。
* [XSS HTML Filter](https://github.com/finn-no/xss-html-filter)：开源的Java HTML过滤工具，用于解析用户提交的输入，并对其进行过滤，防止潜在的跨站脚本攻击、恶意HTML或格式错误的HTML。
* [Snuck](https://github.com/mauro-g/snuck)：Snuck是一款自动化工具，能够有效帮助用户查找Web应用程序中的XSS漏洞。
* [XssRequestFilter](https://github.com/techguy-bhushan/XssRequestFilters)：XssRequestFilter是一个基于Spring的库，只需使用一个简单的@XssFilter注解，即可过滤@Controller/@RestController请求中的跨站脚本。
* [AntiSamy](https://github.com/nahsra/antisamy)：AntiSamy是一个用于快速、可配置地清理来自不受信任来源的HTML的库。

#### TLS/SSL

* [Ayza](https://github.com/Hakky54/ayza)：Ayza是一个高级库，用于配置HTTP客户端通过SSL/TLS进行通信以进行单向身份验证或双向身份验证。
* [OpenJSSE](https://github.com/openjsse/openjsse)：OpenJSSE是支持TLS 1.3的JSSE提供程序。
* [TLS Attacker](https://github.com/tls-attacker/TLS-Attacker)：TLS Attacker是一个基于Java的TLS库分析框架。
* [WolfSSL JNI](https://github.com/wolfSSL/wolfssljni)：该包为WolfSSL嵌入式SSL/TLS库提供Java支持，使应用程序能够支持高达当前TLS 1.3协议级别的SSL/TLS。
* [jSSLKeyLog](https://github.com/jsslkeylog/jsslkeylog)：Java代理库将SSL会话密钥记录到Wireshark的文件中。

#### CORS

* [Akka HTTP CORS](https://github.com/lomigmegard/akka-http-cors)：这是针对Akka HTTP库的服务器端的Scala/Java实现。
* [CORS Filter](https://github.com/eBay/cors-filter)：CORS Filter是用于Java Web容器的服务器端CORS的Java Servlet Filter实现，由eBay开源。

#### ASN.1

* [Signum](https://github.com/a-sit-plus/signum)：Kotlin多平台加密/PKI库和ASN1解析器、编码器。
* [ASN1bean](https://github.com/beanit/asn1bean)：ASN1bean是一个Java ASN.1 BER和DER编码/解码库。
* [ASN One](https://github.com/hierynomus/asn-one)：ASN One是ASN.1编码器和解码器的纯Java实现。
* [ASN.1 Datatypes](https://github.com/alexvoronov/gcdc-asn1)：ASN.1数据类型和UPER编码器/解码器。

#### 证书颁发机构

* [XiPKI](https://github.com/xipki/xipki)：XiPKI是一个高度可扩展和高性能的开源PKI(CA和OCSP响应器)。
* [EJBCA](https://github.com/Keyfactor/ejbca-ce)：开源公钥基础设施(PKI)和证书颁发机构(CA)软件。
* [Dogtag PKI](https://github.com/dogtagpki/pki)：Dogtag证书系统是一个企业级开源证书颁发机构(CA)。
* [ACME4J](https://github.com/shred/acme4j)：ACME Java客户端。

#### 数据匿名化

* [ARX](https://github.com/arx-deidentifier/arx)：ARX是一款用于对敏感个人数据进行匿名化的综合开源软件，由德国慕尼黑工业大学开发。
* [DataDefender](https://github.com/armenak/DataDefender)：敏感数据管理，数据发现和匿名化工具包。
* [Anonymouth](https://github.com/psal/anonymouth)：Anonymouth是一个基于Java的应用程序，旨在为用户提供开始对其编写的文档进行匿名化所需的工具和知识，由德雷塞尔大学开源。
* [Anonimatron](https://github.com/realrolfje/anonimatron)：Anonimatron是一个免费、可扩展、开源数据匿名化工具。
* [Rapiddweller Benerator](https://github.com/rapiddweller/rapiddweller-benerator-ce)：Benerator是一个功能强大的软件解决方案，用于开发、测试和培训目的的数据生成、混淆和迁移。
* [Cinnamon](https://github.com/KI-AIM/Cinnamon)：Cinnamon是一个模块化应用程序，旨在为数据匿名化、合成和评估提供强大的功能，由德国联邦教育与研究部开发。
* [Data Privacy Toolkit](https://github.com/IBM/data-privacy-toolkit)：Data Privacy Toolkit是一个用于数据类型识别、隐私风险评估、数据屏蔽和数据匿名化的工具包，以Java/Scala库和REST API的形式公开，由IBM开源。
* [Jstylo](https://github.com/psal/jstylo)：JStylo是作者归属和作者匿名化框架，由德雷塞尔大学开源。

#### 电子签名

* [XAdES4j](https://github.com/luisgoncalves/xades4j)：XAdES4j是XML高级电子签名(XAdES 1.3.2和1.4.1)的高级、可配置和可扩展的Java实现。
* [Jsign](https://github.com/ebourg/jsign)：Jsign是一种多功能代码签名工具，允许你对Windows可执行文件、安装程序包和脚本进行签名和时间戳。
* [DigiDoc4j](https://github.com/open-eid/digidoc4j)：DigiDoc4j是一个Java库，用于对文档进行数字签名并创建签名文档的数字签名容器。
* [El Cliente @firma](https://github.com/ctt-gob-es/clienteafirma)：El Cliente @firma是自由软件电子签名应用程序的集合，它允许在不同的操作环境中创建不同格式的电子签名。
* [DSS](https://github.com/esig/dss)：DSS是一个用于电子签名创建和验证的开源软件库，由欧盟委员会开源。
* [JHOVE](https://github.com/openpreserve/jhove)：JHOVE是一个可扩展的软件框架，用于执行数字对象的格式识别、验证和表征，由哈佛大学开发。
* [SignServer Community](https://github.com/Keyfactor/signserver-ce)：SignServer是基于PKI的开源签名软件，用于签署代码、文档、时间戳等。
* [NCANode](https://github.com/ncanode-kz/NCANode)：哈萨克斯坦共和国电子数字签名服务器应用程序。
* [Signer](https://github.com/demoiselle/signer)：包含有助于实施ICP-BRASIL标准中的数字签名的组件的存储库。
* [Autogram](https://github.com/slovensko-digital/autogram)：Autogram是一个多平台桌面JavaFX应用程序，用于根据欧洲eIDAS法规签署和验证文件。

## 序列化

* [Protocol Buffers](https://github.com/protocolbuffers/protobuf)：Protocol Buffers是Google开发的用于序列化结构化数据的机制，它与语言和平台无关，并且可扩展。
* [Hessian](http://hessian.caucho.com/)：Hessian是一种基于二进制的轻量级网络传输协议，用于在不同的应用程序之间进行远程过程调用，由Caucho开源。
* [FlatBuffers](https://github.com/google/flatbuffers)：FlatBuffers是一个跨平台序列化库，旨在实现最大内存效率，由Google开源。
* [Apache Avro](https://github.com/apache/avro)：Avro是一个数据序列化系统。
* [Protostuff](https://github.com/protostuff/protostuff)：Protostuff是一个Java序列化库，内置对向前向后兼容性(模式演化)和验证的支持。
* [Apache Fory](https://github.com/apache/fory)：Fory是一种速度极快的多语言序列化框架，由JIT和零拷贝提供支持，可提供高达170倍的性能和终极易用性，阿里开源。
* [FST](https://github.com/RuedigerMoeller/fast-serialization)：完全兼容JDK序列化协议的Java序列化框架，在序列化速度上能达到JDK的10倍。
* [MessagePack](https://github.com/msgpack/msgpack-java)：Java的MessagePack序列化器实现。
* [DataFixerUpper](https://github.com/Mojang/DataFixerUpper)：DataFixerUpper是一组用于增量构建、合并和优化数据转换的实用程序，由Mojang开源。
* [Serial](https://github.com/twitter/Serial)：Serial是一种自定义序列化实现，旨在提高性能并增加开发人员对对象序列化的可见性和控制，由Twitter开源。
* [Swift](https://github.com/facebookarchive/swift)：Swift是一个易于使用、基于注解的Java库，用于创建Thrift可序列化类型和服务，由Facebook开源。
* [Thrifty](https://github.com/microsoft/thrifty)：Thrifty是Apache Thrift软件堆栈的一个实现，它使用了Thrift编译器所采用的1/4方法数，由Microsoft开源。
* [Transit](https://github.com/cognitect/transit-format)：Transit是一种用于在不同编程语言编写的应用程序之间传递值的格式和库集合。
* [Ion Java](https://github.com/amazon-ion/ion-java)：Ion数据表示法的Java实现，由Amazon开源。
* [SOFA Hessian](https://github.com/sofastack/sofa-hessian)：SOFA Hessian基于原生Hessian v4.0.51进行改进，目前已在蚂蚁金服内部稳定运行多年。
* [Kotlin Serialization](https://github.com/Kotlin/kotlinx.serialization)：Kotlin Serialization由一个编译器插件组成，它为可序列化的类生成访问者代码，具有核心序列化API的运行时库以及具有各种序列化格式的支持库。
* [Nippy](https://github.com/taoensso/nippy)：Clojure的快速序列化库。
* [BooPickle](https://github.com/suzaku-io/boopickle)：BooPickle是速度最快、体积最高效的序列化库，适用于Scala和Scala.js。
* [Colfer](https://github.com/pascaldekloe/colfer)：Colfer是一种针对速度和大小进行优化的二进制序列化格式。
* [CapnProto](https://github.com/capnproto/capnproto-java)：Cap'n Proto是一种极其高效的数据和功能共享协议。
* [Chronicle Wire](https://github.com/OpenHFT/Chronicle-Wire)：支持多种格式的低垃圾Java序列化库。
* [Bond](https://github.com/microsoft/bond)：Bond是一个用于处理模式化数据的跨平台框架，支持跨语言反/序列化和强大的通用机制，可有效地操作数据，Microsoft开源。
* [Zeno](https://github.com/Netflix/zeno)：Zeno是Netflix的内存数据传输框架。
* [Kryo](https://github.com/EsotericSoftware/kryo)：Kryo是一个快速高效的Java二进制对象图序列化框架。
* [JBBP](https://github.com/raydac/java-binary-block-parser)：在Java和Android中处理二进制数据舒适且动态的方式。
* [CoralProto](https://github.com/coralblocks/CoralProto)：一种快速、二进制、无垃圾的序列化框架，具有简单、紧凑和简洁的非XML模式定义语言，支持可选字段、重复组、嵌套重复组、枚举、模式演变等。
* [Eclipse Serializer](https://github.com/eclipse-serializer/serializer)：Serializer项目可以对任何Java对象进行(反)序列化，而无需生成代码的注解、超类或接口或数据模式。
* [VelocyPack Java](https://github.com/arangodb/java-velocypack)：VelocyPack(用于序列化和存储的快速而紧凑的格式)的Java实现。
* [Kryo Serializers](https://github.com/magro/kryo-serializers)：一个为某些JDK类型和一些外部库(例如JodaTime)提供Kryo(v2、v3、v4)序列化器的项目。
* [Fast Binary Encoding](https://github.com/chronoxor/FastBinaryEncoding)：Fast Binary Encoding是适用于C++、C#、Go、Java、JavaScript、Kotlin、Python、Ruby、Swift的超快速通用序列化解决方案。
* [Fressian](https://github.com/Datomic/fressian)：Fressian是一种可扩展的二进制数据表示法。
* [Zserio](https://github.com/ndsev/zserio)：Zserio是一个以紧凑、高效、低开销的方式序列化结构化数据的框架。
* [Chill](https://github.com/twitter/chill)：Kryo序列化库的扩展，包括序列化器和一组类，以简化Hadoop、Storm、Akka等系统中Kryo的配置，由Twitter开源。
* [Opack](https://github.com/realtimetech-solution/opack)：Opack是一个Java库，可以实现Java对象与普通对象之间的序列化/反序列化，由韩国公司Realtime开源。
* [Fse](https://gitee.com/eric_ds/fse)：高性能Java序列化框架，可以任意Java对象序列化为字节数组并且完成反序列化。
* [Avro4s](https://github.com/sksamuel/avro4s)：Avro4s是一个用Scala编写的Avro模式/类生成及序列化/反序列化库。
* [Salat](https://github.com/salat/salat)：Salat是一个简单的案例类序列化库。
* [Protobuf Java Format](https://github.com/bivas/protobuf-java-format)：基于谷歌的Protobuf Message，提供不同格式的序列化和反序列化。
* [SerialWriter](https://github.com/QAX-A-Team/SerialWriter)：SerialWriter是Java序列化的一个不完整的实现，用于研究Java反序列化的漏洞。
* [ActiveJ Serializer](https://activej.io/serializer)：ActiveJ Serializer是最快的Java序列化器。
* [Jackson Dataformat Binary](https://github.com/FasterXML/jackson-dataformats-binary)：这是一个针对Jackson标准二进制数据格式后端的多模块总项目。
* [FastProto](https://github.com/indunet/fastproto)：FastProto是一个功能强大的二进制数据处理工具，旨在简化Java环境中的二进制数据编码和解码。
* [RxStore](https://github.com/Gridstone/RxStore)：一个小型库，可帮助使用RxJava将对象保存到磁盘和从磁盘恢复对象。
* [KStore](https://github.com/xxfast/KStore)：一个小型的Kotlin多平台库，使用kotlinx.coroutines、kotlinx.serialization和kotlinx.io辅助在磁盘上保存和恢复对象。
* [Pherialize](https://github.com/kayahr/pherialize)：Pherialize是一个小型库，允许将Java对象序列化为PHP序列化格式，并将数据从该格式反序列化回Java对象。
* [SerialKiller](https://github.com/ikkisoft/SerialKiller)：SerialKiller是一个易于使用的前瞻Java反序列化库，用于保护应用程序免受不受信任的输入。
* [Blixtser](https://github.com/Mojang/blixtser)：Blixtser是一款快速高效的Java序列化工具，由Mojang开源。
* [JBoss Marshalling](https://github.com/jboss-remoting/jboss-marshalling)：JBoss Marshalling是WildFly项目使用的替代序列化API。
* [MyraCodec](https://github.com/mvp-express/myra-codec)：MYRA Codec是一个高性能的二进制序列化库，采用模式优先设计。

#### Protocol Buffer

* [Wire](https://github.com/square/wire)：Wire是适用于Android、Kotlin、Swift和Java的gRPC和协议缓冲区，Square开源。
* [ScalaPB](https://github.com/scalapb/ScalaPB)：ScalaPB是Scala的Protobuf编译器插件。
* [ProtoStream](https://github.com/infinispan/protostream)：ProtoStream是一个基于Protobuf数据格式的序列化库，由RedHat开源。
* [Kroto Plus](https://github.com/marcoferrer/kroto-plus)：gRPC Kotlin协程，Protobuf DSL，Protoc脚本。
* [Muduo Protorpc](https://github.com/chenshuo/muduo-protorpc)：基于Muduo的Protobuf RPC。
* [Protokt](https://github.com/open-toast/protokt)：Kotlin的Protocol Buffer编译器和运行时。
* [KrotoDC](https://github.com/mscheong01/krotoDC)：KrotoDC是一个protoc插件，用于从.proto输入生成Kotlin数据类和gRPC服务/存根。
* [Connect Kotlin](https://github.com/connectrpc/connect-kotlin)：Connect Kotlin是一个精简的库，用于生成、类型安全且习语化Kotlin客户端通过Protobuf与你的应用服务器通信。
* [Protop](https://github.com/protop-io/protop)：Protop是一个开源Protobuf包管理器。
* [Protobuf4j](https://github.com/roastedroot/protobuf4j)：Protobuf4j是以纯Java字节码运行的Protobuf。
* [PBJ](https://github.com/hashgraph/pbj)：PBJ是一个替代的Google Protobuf代码生成器、解析器和Gradle模块。
* [OpenRTB](https://github.com/google/openrtb)：该库支持OpenRTB规范，为所有protobuf支持的语言提供绑定，并为Java提供额外支持，例如JSON序列化和验证，由Google开源。
* [Pbandk](https://github.com/streem/pbandk)：Pbandk是Protocol Buffers的Kotlin多平台代码生成器和运行时。
* [QuickBuffers](https://github.com/HebiRobotics/QuickBuffers)：QuickBuffers是Google Protocol Buffers的Java实现，专为零分配环境中的低延迟用例而开发，由CMU生物机器人实验室开发。
* [JProtobuf](https://github.com/jhunters/jprotobuf)：JProtobuf是针对Java程序开发的一套简易类库，目的是简化Java语言对Protobuf类库的使用，百度开源。
* [Jackson Datetype Protocol](https://github.com/HubSpot/jackson-datatype-protobuf)：增加了对Google Protocol Buffers与JSON之间的序列化和反序列化支持的Jackson模块。
* [Protobuf Dynamic](https://github.com/os72/protobuf-dynamic)：用于简化Protocol Buffers反射机制的库，无需protoc编译器。
* [Protobuf Converter](https://github.com/rgushel/protobuf-converter)：Protobuf Converter是一个用于将你的域模型对象转换为Google Protobuf消息以及反之亦然的库。
* [ModernProtobuf](https://github.com/Auties00/ModernProtobuf)：ModernProtobuf是针对Java 21及以后版本的Protobuf规范的现代实现。

#### CBOR

* [CBOR Java](https://github.com/c-rack/cbor-java)：RFC 7049的Java实现。
* [CBOR Java](https://github.com/peteroupc/CBOR-Java)：CBOR的Java实现。
* [Kripton](https://github.com/xcesco/kripton)：Kripton是一个适用于Android平台的Java库，它提供了一种简单统一的方法，通过注解和接口来管理不同Java类的持久性。
* [CborTree](https://github.com/google/cbortree)：CborTree是一个Java库，用于将CBOR数据项编码/解码为方便的对象表示，Google开发。
* [Borer](https://github.com/sirthias/borer)：适用于Scala的高效CBOR和JSON(反)序列化。
* [CBOR](https://github.com/authlete/cbor)：这是一个适用于CBOR、COSE、CWT和mdoc的Java库。

#### TOON

* [JToon](https://github.com/felipestanzani/JToon)：Java面向Token的对象表示法，用于LLM的JSON，Token成本仅为一半。
* [TOON Java](https://github.com/wuahhh/toon-java)：面向LLM的高效数据序列化库。
* [TOON4s](https://github.com/vim89/toon4s)：TOON4s是Scala的TOON惯用实现。
* [Toon4j](https://github.com/ricken07/Toon4j)：TOON的Java实现。

## JSON库

* [Jackson](https://github.com/FasterXML/jackson)：Jackson是Java中使用最广泛的JSON库。
* [Gson](https://github.com/google/gson)：Gson是一个Java库，可用于将Java对象转换为其JSON表示形式，由Google开源。
* [Fastjson](https://github.com/alibaba/fastjson)：Fastjson是一个Java库，可用于将Java对象转换为其JSON表示形式，由阿里开源。
* [Fastjson 2](https://github.com/alibaba/fastjson2)：Fastjson2是一个性能极致并且简单易用的Java JSON库，由阿里开源。
* [Moshi](https://github.com/square/moshi)：Moshi是一个适用于Android、Java和Kotlin的现代JSON库，由Square开源。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：适用于Android的最快JSON解析和序列化库。
* [JSON-Java](https://github.com/stleary/JSON-java)：JSON-Java包是一个参考实现，可以将JSON文档解析为Java对象以及从Java类生成新的JSON文档。
* [Flexjson](https://flexjson.sourceforge.net/)：Flexjson是一个轻量级库，用于将Java对象序列化为JSON。
* [Circe](https://github.com/circe/circe)：Circe是Scala的JSON库。
* [Klaxon](https://github.com/cbeust/klaxon)：Klaxon是一个在Kotlin中解析JSON的库。
* [JSON4S](https://github.com/json4s/json4s)：JSON4S旨在提供一个可供其他Scala JSON库使用的单一AST。
* [JSON Lib](https://github.com/kordamp/json-lib)：JSON-Lib是一个Java库，用于将Bean、Map、集合、Java数组和XML转换为JSON，然后再转换回Bean和DynaBeans。
* [JSON.Simple](https://github.com/fangyidong/json-simple)：JSON.Simple是一个简单的JSON Java工具包。
* [Jakarta JSON Processing](https://github.com/jakartaee/jsonp-api)：Jakarta JSON Processing提供可移植的API来解析、生成、转换和查询JSON文档。
* [Eclipse Yasson](https://github.com/eclipse-ee4j/yasson)：Yasson是一个Java框架，它在Java类和JSON文档之间提供标准绑定层。
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON)：HikariJSON是一个高性能JSON解析器。
* [Eclipse Parsson](https://github.com/eclipse-ee4j/parsson)：Parsson是Jakarta JSON-P规范的实现。
* [JsonLube](https://github.com/alibaba/JsonLube)：JsonLube可以在编译期自动生成JSON解析代码，用户使用方式更简单，同时能收获原生解析的性能，由阿里开发。
* [JSON-IO](https://github.com/jdereg/json-io)：JSON-IO是一个强大而轻量的Java库，它简化了JSON序列化和反序列化，同时轻松处理复杂的对象图。
* [Jsoniter](https://github.com/json-iterator/java)：Jsoniter是Java中可用的快速灵活的JSON解析器。
* [Event Ruler](https://github.com/aws/event-ruler)：Event Ruler是一个Java库，允许每秒将数千个事件与任意数量的富有表现力和复杂的规则相匹配，由Amazon开源。
* [Genson](https://github.com/owlike/genson)：Genson是一个完整的JSON Java转换库，提供完整的数据绑定、流媒体等等。
* [DSL-JSON](https://github.com/ngs-doo/dsl-json)：最快的JVM JSON库，具有高级编译时数据绑定支持。
* [Ason](https://github.com/afollestad/ason)：Ason旨在使JSON非常容易在Java中进行交互。
* [QSON](https://github.com/quarkusio/qson)：QSON是一个对象到JSON的映射器，由Quarkus使用。
* [Play JSON](https://github.com/playframework/play-json)：Play JSON是一个功能强大的Scala JSON库，最初由Play团队开发，用于Play框架。
* [Instagram JSON Parser](https://github.com/Instagram/ig-json-parser)：用于Java项目的快速JSON解析器，由Instagram开源。
* [JsonToKotlinClass](https://github.com/wuseal/JsonToKotlinClass)：JsonToKotlinClass是一个从JSON字符串生成Kotlin的插件。
* [Spray JSON](https://github.com/spray/spray-json)：Spray JSON是Scala中轻量级、干净且高效的JSON实现。
* [Minimal JSON](https://github.com/ralfstx/minimal-json)：Minimal Json是用于Java的快速且最小的JSON解析器和编写器。
* [Json Smart](https://github.com/netplex/json-smart-v2)：Json Smart是一个高性能JSON处理器库。
* [JSON Sanitizer](https://github.com/OWASP/json-sanitizer)：JSON Sanitizer可以将类似JSON的内容转换为有效的JSON，由OWASP开源。
* [CodeJson](https://gitee.com/eric_ds/jfire-codejson)：CodeJson是性能非常高的JSON序列化和反序列化库。
* [Sawmill](https://github.com/logzio/sawmill)：Sawmill是一个JSON转换Java库。
* [Apache Johnzon](https://github.com/apache/johnzon)：Johnzon提供JSON P实现和该规范的一组有用扩展。
* [JsonBeans](https://github.com/EsotericSoftware/jsonbeans)：JsonBeans是一个轻量级库，可轻松将Java对象图序列化为JSON或从JSON反序列化。
* [SIMDJson Java](https://github.com/simdjson/simdjson-java)：simdjson的官方Java版本，使用SIMD指令的JSON解析器。
* [Jolt](https://github.com/bazaarvoice/jolt)：使用Java编写的JSON到JSON转换库，由Bazaarvoice开源。
* [Boon](https://github.com/boonproject/boon)：Boon是一个简单的基于Java的JSON工具包，你可以使用Boon以高效且快速的方式对JSON数据进行编码或解码。
* [ZSON](https://github.com/zhangfei19841004/zson)：专为测试人员打造的JSON解析器。
* [Stag](https://github.com/vimeo/stag-java)：Stag通过自动生成无反射TypeAdapters来提升Gson的性能。
* [Hjson Java](https://github.com/hjson/hjson-java)：Hjson格式的Java实现。
* [Avaje JsonB](https://github.com/avaje/avaje-jsonb)：通过APT源代码生成进行快速、无反射的JSON绑定的Java库。
* [NanoJson](https://github.com/mmastrac/nanojson)：NanoJson是一个小型、兼容的Java JSON解析器和写入器。
* [JSON Flattener](https://github.com/wnameless/json-flattener)：JSON Flattener可以扁平化嵌套的JSON对象，反之亦然。
* [JParse](https://github.com/nats-io/jparse)：JParse是一款创新的JVM JSON解析器，通过索引覆盖机制提供极速解析速度。
* [uPickle](https://github.com/com-lihaoyi/upickle)：uPickle是一个简单、快速、无依赖的Scala JSON和二进制(MessagePack)序列化库。
* [BSON4Jackson](https://github.com/michel-kraemer/bson4jackson)：该库向Jackson JSON处理器添加了对BSON的支持。
* [Jackson-JQ](https://github.com/eiiches/jackson-jq)：Jackson JSON处理器的纯Java jq实现。
* [EasyJSON](https://github.com/bes2008/easyjson)：EasyJSON是一个JSON门面库，就像SLF4j一样。
* [Noggit](https://github.com/yonik/noggit)：Noggit是一个极快的Java流式JSON解析器。
* [JSONata4Java](https://github.com/IBM/JSONata4Java)：JSONata的开源Java版本，由IBM提供。
* [Actson](https://github.com/michel-kraemer/actson)：Actson是一个响应式JSON解析器。
* [JSONCoder](https://github.com/eBay/jsonex)：Jsonex JSONCoder是一个轻量级通用对象序列化/反序列化库，该库多年来已在各种eBay项目中广泛使用。
* [Functional JSON](https://github.com/MAIF/functional-json)：以函数式方式解析和写入JSON。
* [JSON Masker](https://github.com/Breus/json-masker)：JSON Masker库允许高度灵活地屏蔽JSON中的敏感数据。
* [StAXON](https://github.com/beckchr/staxon)：StAXON允许你使用javax.xml.stream读取和写入JSON。
* [Hope](https://github.com/santanusinha/hope)：Hope是一种用Java编写的用于对JSON进行谓词评估的高级语言。
* [JSON Canonicalization](https://github.com/cyberphone/json-canonicalization)：JSON Canonicalization Scheme的Java实现。
* [Squiggly](https://github.com/bohnman/squiggly)：Squiggly是一个Jackson JSON PropertyFilter，它使用Facebook Graph API过滤语法的子集选择对象/列表/映射的属性。
* [JsonPullParser](https://github.com/vvakame/JsonPullParser)：JsonPullParser是Java的JSON-POJO映射库。
* [JSON Discoverer](https://github.com/SOM-Research/jsonDiscoverer)：JSON Discoverer是一款可让你获取JSON文档隐式架构的工具，由加泰罗尼亚开放大学开源。
* [Jsonista](https://github.com/metosin/jsonista)：用于快速JSON编码和解码的Clojure库，由Metosin开源。
* [JSONAPI Converter](https://github.com/jasminb/jsonapi-converter)：JSONAPI Converter是一个提供使用JSON API规范与服务集成的方法的库。
* [Jackson Datatype Money](https://github.com/zalando/jackson-datatype-money)：Jackson Datatype Money是一个Jackson模块，用于支持JavaMoney数据类型的JSON序列化和反序列化，由Zalando开源。
* [Json Wikipedia](https://github.com/diegoceccarelli/json-wikipedia)：Json Wikipedia包含将Wikipedia XML转储转换为JSON或Avro转储的代码。
* [JsonLogic Java](https://github.com/jamsesso/json-logic-java)：不使用Nashorn JS引擎的纯Java实现JsonLogic。
* [JsonTemplate](https://github.com/json-template/JsonTemplate)：一个生成JSON字符串的Java工具。
* [xJsonKit](https://gitee.com/troyzhxu/xjsonkit)：xJsonKit是一个超轻量级JSON/JSONB/XML/YAML解析门面API。
* [Tethys](https://github.com/tethys-json/tethys)：Tethys是用于Scala的无AST JSON库。
* [JsonPathKt](https://github.com/eygraber/JsonPathKt)：Kotlin Multiplatform中更轻量级、更高效的JsonPath实现。
* [JSON Repair](https://github.com/HAibiiin/json-repair)：JSON Repair是一个Java库，用于修复由大语言模型在不同应用层生成的异常JSON。
* [ZIO Json](https://github.com/zio/zio-json)：ZIO Json是一个快速且安全的JSON库。

#### JSON Schema

* [Jsonschema2Pojo](https://github.com/joelittlejohn/jsonschema2pojo)：Jsonschema2Pojo从JSON或JSON Schema生成Java类型，并标注这些类型以与Jackson、Gson等进行数据绑定。
* [JSON Schema Validator](https://github.com/everit-org/json-schema)：用于Java的JSON模式验证器，基于org.json API。
* [JSON Schema Validator](https://github.com/networknt/json-schema-validator)：这是用于JSON模式校验的JSON Schema Core Draft规范的Java实现。
* [JSON Schema Validator](https://github.com/java-json-tools/json-schema-validator)：Java中的纯JSON模式验证实现，具有可靠的正确性和性能。
* [JSON Schema Generator](https://github.com/victools/jsonschema-generator)：用于从Java类创建JSON模式(Draft 6、Draft 7、Draft 2019-09或Draft 2020-12)。
* [Jackson JSON Schema Module](https://github.com/FasterXML/jackson-module-jsonSchema)：用于从POJO生成JSON Schema(v3)定义的模块。
* [JSON Schema Inferrer](https://github.com/saasquatch/json-schema-inferrer)：根据示例JSON推断JSON模式的Java库。
* [JJSchema](https://github.com/reinert/JJSchema)：使用Jackson将Java类型转换为JSON Schema的生成器。
* [Justify](https://github.com/leadpony/justify)：Justify是一个基于JSON模式规范和Jakarta JSON-P的JSON验证器。
* [JSONS2XSD](https://github.com/ethlo/jsons2xsd)：用Java编写的JSON模式到XML模式转换器。
* [JDocs](https://github.com/americanexpress/unify-jdocs)：JDocs是一个JSON操作库，它完全消除了对模型/POJO类的需要，而是直接在JSON文档上工作，由美国运通开源。
* [Snowy](https://github.com/ssilverman/snowy-json)：Snowy是一个功能齐全的JSON Schema验证器。
* [Kotlinx Schema](https://github.com/Kotlin/kotlinx-schema)：Kotlin多平台库，通过KSP在编译时和运行时通过反射生成JSON Schema。
* [JSONSchemaFriend](https://github.com/jimblackler/jsonschemafriend)：JSONSchemaFriend是一个基于JSON Schema的数据验证器，以Java库的形式提供。
* [JSONx Java](https://github.com/jsonx-org/java)：JSONx Java为JSON模式定义语言处理器、验证器和运行时API提供参考实现。
* [JSON Schema](https://github.com/harrel56/json-schema)：实现JSON模式规范的Java库。
* [Jackson JsonSchema Generator](https://github.com/mbknor/mbknor-jackson-jsonSchema)：使用Jackson注解生成具有多态性的JSON模式。
* [JSON Kotlin Schema](https://github.com/pwall567/json-kotlin-schema)：JSON Schema的Kotlin实现。
* [CZML Writer](https://github.com/AnalyticalGraphicsInc/czml-writer)：该项目提供.NET和Java库，用于写入与Cesium一起使用的CZML内容。
* [Json SKema](https://github.com/erosb/json-sKema)：Json SKema是一个用于JVM的Json Schema验证器库。
* [Vert.x JSON Schema](https://github.com/eclipse-vertx/vertx-json-schema)：Vert.x Json Schema为Json Schema规范提供了可扩展且异步的实现。

#### JsonPath

* [JsonPath](https://github.com/json-path/JsonPath)：JsonPath的实现版本，用于读取JSON文档的Java DSL。
* [Snack3](https://gitee.com/noear/snack3)：Snack3是一个高性能的JsonPath框架，支持序列化反序列化、解析和转换、构建、查找、JsonPath查询。
* [JsonSurfer](https://github.com/wanglingsong/JsonSurfer)：Java中的流式JsonPath处理器。
* [JMESPath Java](https://github.com/burtcorp/jmespath-java)：这是JMESPath的Java实现。
* [Vert.x JsonPath](https://github.com/NoEnv/vertx-jsonpath)：Vert.x JsonPath是使用Vert.x的JsonObject和JsonArray对JsonPath的一个非常基本的实现。
* [JSLT](https://github.com/schibsted/jslt)：JSLT是一种完整的JSON查询和转换语言。

#### JSON Patch

* [JSON Patch](https://github.com/java-json-tools/json-patch)：这是用Java编写的RFC 6902(JSON Patch)和RFC 7386(JSON Merge Patch)的实现。
* [ZJSONPatch](https://github.com/flipkart-incubator/zjsonpatch)：这是用Java编写的RFC 6902 JSON Patch的实现，由Flipkart开源。
* [Diffson](https://github.com/gnieh/diffson)：RFC-6901、RFC-6902和RFC-7396的Scala实现。
* [BSONPatch](https://github.com/eBay/bsonpatch)：RFC 6902的BSON实现，用于计算两个BSON文档之间的差异，由eBay开源。

#### JSON-LD

* [JSONLD-Java](https://github.com/jsonld-java/jsonld-java)：这是JSON-LD 1.0规范和JSON-LD-API 1.0规范的Java实现。
* [Titanium JSON-LD](https://github.com/filip26/titanium-json-ld)：JSON-LD 1.1处理器和API。
* [Schema.org Java](https://github.com/google/schemaorg-java)：用于处理JSON-LD格式的Schema.org数据的Java实用程序，由Google开发。
* [Schema.org Java](https://github.com/Kobee1203/schema-org-java)：Schema-org Java是一个用于创建schema.org实体的库。
* [JB4JSON-LD](https://github.com/kbss-cvut/jb4jsonld)：JB4JSON-LD是一个简单的库，用于将Java对象序列化为JSON-LD，由布拉格捷克技术大学开源。
* [Hydra Java](https://github.com/dschulten/hydra-java)：标注你的Java Bean并使用Hydra将它们序列化为JSON LD。

#### JSON-RPC

* [JSON-RPC](https://github.com/briandilley/jsonrpc4j)：该项目旨在为Java编程语言提供轻松实现JSON-RPC的工具。
* [Dubbo JSONRPC](https://github.com/apache/dubbo-rpc-jsonrpc)：Dubbo项目的JSON RPC模块。
* [Simple JSON-RPC](https://github.com/arteam/simple-json-rpc)：用于将JSON-RPC 2.0协议简单集成到Java应用程序的库。
* [Triaina](https://github.com/mixi-inc/triaina)：Triaina在Web客户端和本机客户端之间提供基于JSON-RPC的通信协议。

#### JSON比较

* [JsonUnit](https://github.com/lukas-krecan/JsonUnit)：JsonUnit是一个简化测试中JSON比较的库。
* [Json Comparison](https://github.com/eBay/json-comparison)：强大的JSON比较工具，用于识别JSON文件中的所有更改，由eBay开源。
* [JSON Compare](https://github.com/fslev/json-compare)：用于比较JSON的Java库。
* [JsonDiff](https://gitee.com/codeleep/json-diff)：一款高性能且功能强大的JSON差异发现工具。
* [Hamcrest JSON](https://github.com/hertzsprung/hamcrest-json)：用于比较JSON文档的Hamcrest匹配器。
* [JsonDiff](https://github.com/LianjiaTech/json-diff)：JsonDiff提供了对JSON通用的Diff能力，支持JSON字符串的深度比较、支持无序数组比较、内含多种算法模型满足对JSON比较时各种需求，由贝壳开源。
* [Jazon](https://github.com/zendesk/jazon)：一个用于测试JSON负载断言的库。

## 配置管理

这里列出来项目配置相关的库、工具。

#### 配置库

* [Typesafe Config](https://github.com/lightbend/config)：使用HOCON文件的JVM语言的配置库，由Lightbend开源。
* [Archaius](https://github.com/Netflix/archaius)：Archaius是一个配置库，用于将静态和动态配置的混合作为单个配置单元进行访问，由Netflix开源。
* [Cerberus](https://github.com/Nike-Inc/cerberus)：Cerberus API是一个云原生、可扩展的Spring Boot应用程序，可以安全地存储应用程序属性和文件，并具有强大的审核功能，Nike开源。
* [PureConfig](https://github.com/pureconfig/pureconfig)：PureConfig是一个用于加载配置文件的Scala库。
* [Apache Commons Configuration](https://github.com/apache/commons-configuration)：Commons Configuration库提供了一个通用配置接口，使Java应用程序能够从各种源读取配置数据。
* [Hoplite](https://github.com/sksamuel/hoplite)：Hoplite是一个Kotlin库，用于以非样板方式将配置文件加载到类型安全类中。
* [Konfig](https://github.com/npryce/konfig)：Konfig为从多个来源收集的配置属性提供了可扩展、类型安全的API。
* [NightConfig](https://github.com/TheElectronWill/night-config)：NightConfig是一个功能强大且易于使用的Java配置库，用Java 8编写。
* [ConfigMe](https://github.com/AuthMe/ConfigMe)：ConfigMe是一个开箱即用的配置管理库，支持YAML。
* [Configurate](https://github.com/SpongePowered/Configurate)：Configurate是一个用于Java应用程序的简单配置库，它提供基于节点的数据表示，能够处理各种配置格式。
* [Avaje Config](https://github.com/avaje/avaje-config)：Avaje Config为JVM应用程序提供外部配置，可以通过YAML或Properties文件提供配置，并使用命令行参数和资源指定要加载的文件。
* [SmallRye Config](https://github.com/smallrye/smallrye-config)：SmallRye Config是一个提供配置应用程序、框架和容器的方法的库。
* [Waterfall Config](https://github.com/Accenture/waterfall-config)：一个简单的Java配置库，很大程度上基于Typesafe Config，并具有一些附加的固执己见的功能，由Accenture开源。
* [OWNER](https://github.com/matteobaccan/owner)：OWNER是一个Java库，其目标是最大限度地减少通过Java properties处理应用程序配置所需的代码。
* [Konf](https://github.com/uchuhimo/konf)：Konf是一个适用于Kotlin/Java/Android的类型安全的级联配置库，支持大多数配置格式。
* [Gestalt](https://github.com/gestalt-config/gestalt)：Gestalt是一个功能强大的Java配置库，旨在简化你在软件项目中处理和管理配置的方式。
* [Spring Fu](https://github.com/spring-projects-experimental/spring-fu)：Spring Fu是JaFu和KoFu的孵化器，旨在以声明式方式使用代码显式配置Spring Boot。
* [Config Magic](https://github.com/brianm/config-magic)：Java的便捷配置库。
* [JadConfig](https://github.com/Graylog2/JadConfig)：JadConfig是一个最小依赖的Java的简约注解驱动配置解析框架。
* [Baigan](https://github.com/zalando-incubator/baigan-config)：Baigan是一个易于使用的基于Spring应用程序的配置框架，由Zalando开源。
* [Constretto](https://github.com/constretto/constretto-core)：Constretto是Java应用程序的配置管理框架。
* [Apron](https://github.com/poiu-de/apron)：Apron是一个用于读写Java .properties文件的小型库。
* [Spring Boot Dynamic Config](https://github.com/Code2Life/spring-boot-dynamic-config)：一个注解实现Spring Boot应用的动态配置，配置热重载最简洁的方案。
* [Configured](https://github.com/CarmJos/configured)：Configured是一个简单、易于使用的通用解决方案，用于管理、加载、读取、 以及更新配置文件。
* [SConfig](https://github.com/ekrich/sconfig)：支持Scala、Java、Scala.js和Scala Native的HOCON配置库。
* [Simple YAML](https://github.com/Carleslc/Simple-YAML)：Simple YAML是一个设计用于为你的程序、工具和插件创建配置文件的库。
* [Okaeri Configs](https://github.com/OkaeriPoland/okaeri-configs)：Okaeri Configs是一个强大、轻量级的Java配置库。
* [OneConfig](https://github.com/Polyfrost/OneConfig)：OneConfig是由Polyfrost开发的一个免费开源配置库。
* [Tamaya](https://github.com/apache/incubator-retired-tamaya)：Tamaya是一个非常强大但灵活的配置方案。
* [ConfigLib](https://github.com/Exlll/ConfigLib)：ConfigLib是一个用于保存、加载、更新和注释YAML配置文件的Minecraft库。

#### 分布式配置

* [Nacos](https://github.com/alibaba/nacos)：Nacos是一个易于使用的平台，专为动态服务发现、配置和服务管理而设计，由阿里开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：Zookeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务，由Yahoo研究院开发。
* [Microconfig](https://github.com/microconfig/microconfig)：Microconfig的目的是让管理微服务的配置变得简单、方便，并重用公共部分。
* [Spring Cloud Config](https://github.com/spring-cloud/spring-cloud-config)：Spring Cloud Config为分布式系统中的外部化配置提供服务器端和客户端支持。
* [Apollo](https://github.com/apolloconfig/apollo)：Apollo是一个可靠的配置管理系统，适用于微服务配置管理场景，由携程开源。
* [Disconf](https://github.com/knightliao/disconf)：专注于各种分布式系统配置管理的通用组件和通用平台，提供统一的配置管理服务，由百度开源。
* [BRCC](https://github.com/baidu/brcc)：BRCC是一个分布式配置中心，用于统一管理应用服务的配置信息，简化资源配置的维护成本，由百度开源。
* [Central Dogma](https://github.com/line/centraldogma)：Central Dogma是一个基于Git、ZooKeeper和HTTP/2的开源、高可用、版本控制的服务配置仓库，由Line开源。
* [XXL-Conf](https://gitee.com/xuxueli0323/xxl-conf)：XXL-CONF是一个轻量级分布式配置管理平台，拥有轻量级、秒级动态推送、多环境、跨语言、跨机房、配置监听、权限控制、版本回滚等特性。
* [Nacos Plus](https://github.com/dylan-tao/nacos-plus)：Nacos Plus为国产数据库提供支持。
* [QConfig](https://github.com/qunarcorp/qconfig)：QConfig中心式配置中心，提供高可用的配置托管/动态热更新服务，由去哪儿开源。
* [Diamond](https://github.com/takeseem/diamond)：Diamond是一个持久配置管理中心，核心功能是使应用在运行中感知配置数据的变化，由淘宝开发。
* [Config Toolkit](https://github.com/dangdangdotcom/config-toolkit)：Config Toolkit用于简化从本地配置文件到Zookeeper的迁移，由当当开源。
* [CFG4J](https://github.com/cfg4j/cfg4j)：CFG4J是用Java编写的分布式应用程序的现代配置库。
* [ScaleCube Config](https://github.com/scalecube/scalecube-config)：ScaleCube Config是一个基于JVM的分布式应用程序的配置管理库。
* [Jeesuite](https://gitee.com/vakinge/jeesuite-config)：功能齐全、适合二开的配置中心，由dromara社区开源。
* [ConfigKeeper](https://gitee.com/sxfad/config-keeper)：ConfigKeeper是由随行付基于Spring Cloud研发的分布式配置中心。
* [Fig](https://github.com/theapache64/fig)：使用Google Sheet作为远程配置。
* [Duic](https://github.com/zhudyos/duic)：Duic是采用Kotlin与Spring Webflux开发的配置中心。
* [Diablo](https://github.com/ihaolin/diablo)：轻量的分布式配置管理平台。
* [CredHub](https://github.com/cloudfoundry/credhub)：CredHub提供了一个API，可以安全地存储、生成、检索和删除各种类型的凭据。

#### 配置语言

* [Pkl](https://github.com/apple/pkl)：Pkl是一种用于生成配置的编程语言，由Apple开源。
* [Sjsonnet](https://github.com/databricks/sjsonnet)：Jsonnet配置语言的JVM实现，由Databricks开源。
* [Dhallj](https://github.com/travisbrown/dhallj)：该项目是JVM的Dhall配置语言的实现。
* [HCL4j](https://github.com/bertramdev/hcl4j)：HCL4j是JVM上Hashicorp配置语言的解析器。
* [KSON](https://github.com/kson-org/kson)：KSON结合了JSON和YAML的优点，像JSON一样稳健高效，像YAML一样干净易读。

#### YML库

* [EO-YAML](https://github.com/decorators-squad/eo-yaml)：适用于Java 8及更高版本的YAML库。
* [SnakeYAML](https://bitbucket.org/asomov/snakeyaml/overview)：YAML解析库。
* [YamlBeans](https://github.com/EsotericSoftware/yamlbeans)：YamlBeans可以轻松地将Java对象图与YAML进行序列化和反序列化。
* [BoostedYAML](https://github.com/dejvokep/boosted-yaml)：一个简单易用的独立Java库，在处理YAML文档时提供增强的体验。
* [Psych](https://github.com/ruby/psych)：Psych是一个YAML解析器和发射器。
* [JYaml](https://jyaml.sourceforge.net/)：JYaml是一个用于处理Yaml文件格式的Java库。
* [YamlPath](https://github.com/yaml-path/YamlPath)：用于读取YAML文档并替换值的Java DSL。
* [YamlConfiguration](https://github.com/bspfsystems/YamlConfiguration)：YamlConfiguration是一个用于创建和编辑Java程序中使用的配置YAML文件的库。

#### INI库

* [Ini4j](https://github.com/facebookarchive/ini4j)：Ini4j是一个简单的Java API，用于处理Windows .ini格式的配置文件，由Facebook开发。
* [JIniFile](https://github.com/SubZane/JIniFile)：JIniFile从INI文件中存储和检索特定于应用程序的信息和设置。
* [Java INI Parser](https://github.com/vincentrussell/java-ini-parser)：Java INI Parser帮助你在Java中解析ini文件。

#### ENV库

* [DotEnv](https://github.com/cdimascio/dotenv-java)：Ruby DotEnv项目的无依赖、纯Java端口，用于从.env文件加载环境变量。
* [Dotenv Kotlin](https://github.com/cdimascio/dotenv-kotlin)：用于Java和Kotlin的Ruby dotenv项目的端口。
* [Spring Dotenv](https://github.com/paulschwarz/spring-dotenv)：为Spring提供Dotenv属性源。

#### Toml库

* [TomlJ](https://github.com/tomlj/tomlj)：TomlJ是一个完整的TOML解析器。
* [Toml4j](https://github.com/mwanji/toml4j)：Toml4j是一个用于Java的TOML 0.4.0解析器。
* [KToml](https://github.com/orchestr7/ktoml)：完全原生且跨平台的Kotlin序列化库，用于序列化/反序列化Toml格式。
* [JToml](https://github.com/agrison/jtoml)：这是使用Java的TOML标记语言的解析器。
* [Tomlkt](https://github.com/Peanuuutz/tomlkt)：内置支持kotlinx.serialization的多平台TOML库。

## GraphQL

* [GraphQL Java](https://github.com/graphql-java/graphql-java)：GraphQL Java实现。
* [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin)：Apollo Kotlin是一个GraphQL客户端，可根据GraphQL查询生成Kotlin和Java模型。
* [Lacinia](https://github.com/walmartlabs/lacinia)：Lacinia是一个实现GraphQL规范的Clojure库，由沃尔玛开源。
* [Sangria](https://github.com/sangria-graphql/sangria)：Sangria是一个Scala GraphQL库。
* [KGraphQL](https://github.com/aPureBase/KGraphQL)：KGraphQL是GraphQL的Kotlin实现。
* [GraphQL Clj](https://github.com/tendant/graphql-clj)：提供GraphQL实现的Clojure库。
* [Nodes](https://github.com/americanexpress/nodes)：Nodes是一个GraphQL客户端，旨在根据标准模型定义构建查询，由美国运通开源。
* [Mocca](https://github.com/paypal/mocca)：Mocca是JVM语言的GraphQL客户端，其目标是易于使用、灵活和模块化，由Paypal开源。

#### GraphQL Spring

* [Spring GraphQL](https://github.com/spring-projects/spring-graphql)：Spring GraphQL为基于GraphQL Java构建的Spring应用程序提供支持。
* [DGS Framework](https://github.com/netflix/dgs-framework)：DGS Framework是由Netflix开发的Spring Boot的GraphQL服务器框架。
* [GraphQL Spring Boot](https://github.com/graphql-java-kickstart/graphql-spring-boot)：集成GraphQL Java和Spring Boot的库。
* [GraphQL Spring Boot Starter](https://github.com/merapar/graphql-spring-boot-starter)：这是GraphQL Java项目的Spring boot Starter。
* [GraphQL Java Spring](https://github.com/graphql-java/graphql-java-spring)：GraphQL Java Spring和Spring Boot集成。
* [GraphQL Spring Starter](https://github.com/yandooo/graphql-spring-boot)：GraphQL和GraphiQL Spring Starter。

#### 模式优先

* [GraphQL Java Generator](https://github.com/graphql-java-generator/graphql-maven-plugin-project)：GraphQL Java Generator可以轻松地以模式优先的方式在Java中使用GraphQL。
* [GraphQL APIGen](https://github.com/Distelli/graphql-apigen)：使用GraphQL模式生成Java API，促进模式优先开发。
* [Specmatic](https://github.com/specmatic/specmatic)：Specmatic是一个合约驱动的开发工具，它允许我们将合约转化为可执行规范。
* [GraphQL Java Tools](https://github.com/graphql-java-kickstart/graphql-java-tools)：该库允许使用GraphQL模式语言来构建GraphQL Java模式。
* [GraphQL Codegen](https://github.com/kobylynskyi/graphql-java-codegen)：GraphQL Codegen可以轻松地让你的Java应用程序遵循模式优先的方法。
* [Lilo](https://github.com/friatech/lilo)：Lilo是一个超快的GraphQL拼接库，该项目受到Atlassian Braid的启发。
* [GraphQL Orchestrator Java](https://github.com/graph-quilt/graphql-orchestrator-java)：GraphQL Orchestrator Java通过提供统一的GraphQL模式，简化了从各种GraphQL微服务访问数据的过程。
* [Kobby](https://github.com/ermadmi78/kobby)：Kobby是一个基于GraphQL Schema的Kotlin DSL客户端代码生成插件。
* [GraphQLJavaGen](https://github.com/Shopify/graphql_java_gen)：为提供查询构建器和响应类的特定GraphQL模式生成代码，由Shopify开源。
* [DGS Code Generation Plugin](https://github.com/Netflix/dgs-codegen)：DGS Code Generation Plugin根据你的GraphQL模式文件在项目构建过程中生成代码，由Netflix开源。。
* [GraphQL Codegen Maven Plugin](https://github.com/deweyjose/graphqlcodegen)：这个Maven插件是Gradle的Netflix Codegen插件的移植版。
* [Graphitron](https://github.com/sikt-no/graphitron)：Graphitron是一款代码生成工具，它通过将GraphQL模式链接到底层数据库模型来创建源代码。

#### 代码优先

* [GraphQL SPQR](https://github.com/leangen/graphql-spqr)：GraphQL SPQR是一个简单易用的库，用于在Java中快速开发GraphQL API。
* [Rejoiner](https://github.com/google/rejoiner)：Rejoiner可用于从gRPC微服务和其他Protobuf源生成统一的GraphQL模式，由Google开发。
* [Graphcool](https://github.com/Graphcool/graphcool-framework)：Graphcool是一个开源后端开发框架，用于开发和部署GraphQL API。
* [Caliban](https://github.com/ghostdogpr/caliban)：Caliban是一个纯函数库，用于在Scala中构建GraphQL服务器和客户端。
* [GraphQL Java Annotations](https://github.com/Enigmatis/graphql-java-annotations)：该库为GraphQL模式定义提供基于注解的语法。
* [GraphQL Kotlin](https://github.com/ExpediaGroup/graphql-kotlin)：GraphQL Kotlin构建在GraphQL Java之上，可简化在Kotlin中运行GraphQL客户端和服务器，由Expedia开源。
* [Spring GraphQL Common](https://github.com/yandooo/spring-graphql-common)：简化在Spring框架中使用GraphQL的库。
* [GraphQL JPA Query](https://github.com/introproventures/graphql-jpa-query)：GraphQL JPA Query库使用JPA规范为你的JPA实体Java类使用GraphQL Java派生和构建GraphQL API。
* [GraphQL JPA](https://github.com/jcrygier/graphql-jpa)：这是一个简单的项目，用于扩展GraphQL Java并让它从JPA模型派生模式。
* [Elide](https://github.com/yahoo/elide)：Elide是一个Java库，可以轻松设置模型驱动的GraphQL或JSON API Web服务，由Yahoo开源。
* [SchemaGen GraphQL](https://github.com/bpatters/schemagen-graphql)：GraphQL Java插件，增加了对企业级应用程序的模式生成和执行的支持。
* [Vertx GraphQL Client](https://github.com/graphqly/vertx-graphql-client)：代码优先GraphQL客户端的优雅实现。
* [Microprofile GraphQL](https://github.com/microprofile/microprofile-graphql)：代码优先Java GraphQL服务的开放规范。
* [SmallRye GraphQL](https://github.com/smallrye/smallrye-graphql)：MicroProfile GraphQL的实现。
* [GraphQLize](https://github.com/graphqlize/graphqlize)：GraphQLize是一个开源Clojure(JVM)库，用于从现有的PostgreSQL和MySQL数据库即时开发GraphQL API。

#### GraphQL库

* [Test GraphQL Java](https://github.com/vimalrajselvam/test-graphql-java)：用于简化GraphQL测试的Java库。
* [Federation JVM](https://github.com/apollographql/federation-jvm)：Graphql Java的Apollo Federation规范的实现。
* [GraphQL Java Extended Validation](https://github.com/graphql-java/graphql-java-extended-validation)：该库为Graphql Java提供了字段和字段参数的扩展验证。
* [GraphQL Java DataLoader](https://github.com/graphql-java/java-dataloader)：这个小而简单的实用程序库是Facebook DataLoader的纯Java 8端口。
* [Nadel](https://github.com/atlassian-labs/nadel)：Nadel是一个将多个GraphQL服务组合在一起的Kotlin库，由Atlassian开源。
* [GraphQL Filter Java](https://github.com/intuit/graphql-filter-java)：该库可帮助GraphQL开发人员构建具有细粒度过滤支持的出色API，由Intuit开发。
* [GraphQL Calculator](https://github.com/graphql-calculator/graphql-calculator)：GraphQL Calculator是一个轻量级的GraphQL查询计算引擎。
* [HyperGraphQL](https://github.com/hypergraphql/hypergraphql)：HyperGraphQL是一个GraphQL接口，用于在Web上查询和提供链接数据。
* [GraphQL Java Servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet)：GraphQL Java的Servlet端口。
* [Light4j GraphQL](https://github.com/networknt/light-graphql-4j)：基于Light-4j的GraphQL实现。

#### 执行策略

* [GraphQL RxJava](https://github.com/nfl/graphql-rxjava)：这是GraphQL Java的一个执行策略，可以更轻松地使用RxJava的Observable。
* [GraphQL Java Reactive](https://github.com/bsideup/graphql-java-reactive)：基于Reactive Streams的GraphQL Java执行策略。

#### GraphQL标量

* [GraphQL Java Extended Scalars](https://github.com/graphql-java/graphql-java-extended-scalars)：该库为GraphQL Java提供扩展标量。
* [GraphQL Java DateTime](https://github.com/tailrocks/graphql-java-datetime)：GraphQL ISO Date是一组与GraphQL Java一起使用的符合RFC 3339的日期/时间标量类型。

## 日期时间

* [Joda Time](https://github.com/JodaOrg/joda-time)：Joda Time提供了Java日期和时间类的优质替代品。
* [Prettytime](https://github.com/ocpsoft/prettytime)：Java的社交风格日期和时间格式。
* [Time4J](https://github.com/MenoData/Time4J)：Time4J是围绕Date、Calendar和SimpleDateFormat的旧Java类的完整且高端的替代品。
* [ThreeTen Extra](https://github.com/ThreeTen/threeten-extra)：ThreeTen Extra提供了额外的日期时间类来补充JDK 8中的类。
* [XK-Time](https://gitee.com/xkzhangsan/xk-time)：XK-Time包含时间转换、时间计算、时间格式化、时间解析、日历、时间Cron表达式和时间NLP等工具。
* [Date4j](https://github.com/IanDarwin/date4j)：Date4j是Java内置日期类的轻量级替代品。
* [Time](https://github.com/kizitonwose/Time)：Kotlin中类型安全的时间计算，由泛型代码驱动。
* [Jollyday](https://github.com/svendiedrichsen/jollyday)：Jollyday可以确定给定年份、国家/名称以及最终州/地区的假期。
* [TrueTime](https://github.com/instacart/truetime-android)：Android NTP时间库，获取真实的当前时间，不受设备时钟时间变化的影响。
* [Jollyday](https://github.com/focus-shift/jollyday)：Jollyday是一个查询公共假期的Java库，目前支持70多个国家/地区。
* [Holiday](https://github.com/Haoshenqi0123/holiday)：获取中国法定节假日API。
* [TimeAgo](https://github.com/marlonlom/timeago)：一个简单的Java库，用于将日期显示为相对时间之前的语言。
* [Adhan Kotlin](https://github.com/batoulapps/adhan-kotlin)：Adhan是一个经过充分测试和记录良好的库，用于计算伊斯兰祈祷时间。
* [ITL Java](https://github.com/fikr4n/itl-java)：ITL Java是一个用于计算祈祷时间、朝拜方向和伊斯兰回历日期的Java库。
* [Lib Recur](https://github.com/dmfs/lib-recur)：该库解析RFC 5545和RFC 2445中定义的重复字符串并迭代实例。
* [TickTock](https://github.com/ZacSweers/ticktock)：TickTock是一个时区数据管理库，适用于JVM和Android，针对Java 8或更高版本中的java.time.* API。
* [Business Hours Java](https://github.com/dhatim/business-hours-java)：这个Java库有助于处理工作时间，例如“周一到周五上午9点到下午6点，周六上午9点到中午12点”。

#### 日历库

* [Lunar](https://gitee.com/6tail/lunar-java)：Lunar是一个支持阳历、阴历、佛历和道历的日历工具库。
* [LunarCalendar](https://github.com/XhinLiang/LunarCalendar)：Java版中国农历日历库。
* [UmmAl-Qura Calendar](https://github.com/msarhan/ummalqura-calendar)：Umm Al-Qura日历系统的java.util.Calendar实现。
* [LunarCalendar](https://github.com/heqiao2010/LunarCalendar)：中国农历的Java实现，支持约300年公历范围：1850-02-12到2150-12-31。
* [Tyme4j](https://github.com/6tail/tyme4j)：Tyme4j是一个非常强大的日历工具库，可以看作Lunar的升级版，拥有更优的设计和扩展性，支持公历和农历、星座、干支、生肖、节气、法定假日等。
* [BusinessCalendar4J](https://github.com/yusuke/businessCalendar4J)：BusinessCalendar4J是一个100%纯Java业务日历库。
* [Zmanim](https://github.com/KosherJava/zmanim)：Zmanim库是一个特殊日历的API，可以计算不同的天文时间，包括日出和日落以及犹太zmanim或祈祷和其他犹太宗教职责的宗教时间。
* [Biweekly](https://github.com/mangstadt/biweekly)：Biweekly是一个用Java编写的iCalendar库。
* [iCal4j](https://github.com/ical4j/ical4j)：iCal4j是一个Java库，用于读取和写入RFC2445中定义的iCalendar数据流。

#### 日期/时间解析器

* [DateTimeUtils](https://github.com/thunder413/DateTimeUtils)：这个库是一个函数包，可以让你操作对象和/或Java日期字符串。
* [DateParser](https://github.com/sisyphsu/dateparser)：DateParser是一个智能且高性能的日期时间解析器库，它支持数百种不同的模式。
* [Internet Time Utility](https://github.com/ethlo/itu)：ISO格式日期时间的极快解析器和格式化程序。
* [Human Duration](https://bitbucket.org/atlassian/humanduration)：该库允许从人类可读的字符串(如2分39秒、2m 39s等)解析Java 8的Duration时间，由Atlassian开源。
* [Natty](https://github.com/joestelmach/natty)：Natty是一个用Java编写的自然语言日期解析器。
* [JChronic](https://github.com/samtingleff/jchronic)：Java中的自然语言日期解析器，作为Ruby Chronic的直接移植。
* [Hawking](https://github.com/zoho/hawking)：Hawking是一个自然语言日期时间解析器，可以从具有上下文的文本中提取日期和时间并解析为所需的格式。

## MATLAB

* [Dimple](https://github.com/analog-garage/dimple)：Dimple是一款用于概率建模、推理和学习的开源软件工具。
* [MFL](https://github.com/HebiRobotics/MFL)：MFL是一个Java库，用于读取和写入与MATLAB的MAT文件格式兼容的MAT文件，由CMU机器人研究所开源。
* [MatFileRW](https://github.com/diffplug/matfilerw)：MatFileRW是一个允许读取和写入MAT文件的库。
* [MatConsoleCtl](https://github.com/diffplug/matconsolectl)：MatConsoleCtl是一个Java API，允许从Java调用MATLAB。
* [JMatIO](https://github.com/gradusnikov/jmatio)：JMatIO是一个Java库，用于读取/写入/操作Matlab二进制MAT文件。

## Jupyter

* [Rapaio Jupyter Kernel](https://github.com/padreati/rapaio-jupyter-kernel)：基于JShell的Java语言Jupyter内核。
* [Kotlin Jupyter](https://github.com/Kotlin/kotlin-jupyter)：Kotlin Jupyter是一个强大的引擎，旨在增强你的Kotlin REPL体验；它提供对执行代码单元、提供基本代码完成和分析错误的支持。
* [Ganymede](https://github.com/allen-ball/ganymede)：Ganymede是基于Java Shell工具JShell的Jupyter Notebook Java内核。
* [Almond](https://github.com/almond-sh/almond)：Almond是Jupyter的Scala内核。
* [Apache Toree](https://github.com/apache/incubator-toree)：Toree是Juypter Notebook内核，主要目标是为使用Scala语言连接和使用Spark的交互式应用程序提供基础。
* [IJava](https://github.com/SpencerPark/IJava)：用于执行Java代码的Jupyter内核。
* [JJava](https://github.com/dflib/jjava)：JJava是由DFLib社区维护的Jupyter Java内核。
* [SciJava Kernel](https://github.com/scijava/scijava-jupyter-kernel)：基于BeakerX的已失效内核。
* [BeakerX](https://github.com/twosigma/beakerx)：BeakerX是JVM内核和交互式小部件的集合，用于绘图、表格、自动翻译以及Jupyter Notebook和Jupyter Lab版本1.2.x和2.x的其他扩展。
* [Jupyter Kernel JSR223](https://github.com/fiber-space/jupyter-kernel-jsr223)：该项目是Jupyter消息传递协议的Java实现，适用于实现JSR223 ScriptEngine规范的JVM语言。

## 机器人开发

* [WPILib](https://github.com/wpilibsuite/allwpilib)：该仓库包含HAL、WPILibJ和WPILibC项目，这些是为roboRIO创建机器人程序的核心库，由伍斯特理工学院开源。
* [GRIP](https://github.com/WPIRoboticsProjects/GRIP)：GRIP是一款用于快速原型设计和部署计算机视觉算法的应用程序，主要用于机器人应用，由伍斯特理工学院开源。
* [FlashLib](https://github.com/Flash3388/FlashLib)：FlashLib是一个Java机器人软件开发库，最初旨在改进和帮助FRC团队，但现在旨在支持非FRC机器人甚至其他用途。
* [OpenTCS](https://github.com/openTCS/opentcs)：OpenTCS是一个用于控制自动引导车辆(AGV)和移动机器人车队的免费平台，由弗劳恩霍夫物流研究所维护。
* [PathPlanner](https://github.com/mjansen4857/pathplanner)：PathPlanner是3015团队创建的FRC机器人运动轨迹生成器。
* [IHMC Open Robotics Software](https://github.com/ihmcrobotics/ihmc-open-robotics-software)：机器人软件具有腿式运动算法和基于动量的优化控制器核心；世界级机器人的支持软件，包括人形、跑鸟、外骨骼、机甲等，由IHMC机器人实验室开源。
* [MyRobotLab](https://github.com/MyRobotLab/myrobotlab)：Myrobotlab是一个基于Java服务的开源机器人和创意机器控制框架。
* [Bag Database](https://github.com/swri-robotics/bag-database)：Bag Database是一个基于Web的应用程序，可监视ROS bag文件的目录、解析其元数据，由美国西南研究所开源。
* [Astrobee](https://github.com/nasa/astrobee_android)：Astrobee机器人软件公开了一个Java API，以便与基于ROS的机器人内部消息系统进行交互，由NASA开发。
* [JOpenShowVar](https://github.com/aauc-mechlab/JOpenShowVar)：JOpenShowVar是一个Java开源跨平台Kuka机器人通信接口，允许读写受控机械手的变量和数据结构，由奥勒松大学学院开源。
* [EV3Dev Lang Java](https://github.com/ev3dev-lang-java/ev3dev-lang-java)：EV3Dev Lang Java是一个学习Java并使用EV3Dev和LeJOS方式支持的硬件为Mindstorms机器人创建软件的项目。
* [IHMC ROS 2 Library](https://github.com/ihmcrobotics/ihmc-ros2-library)：Java中与ROS2兼容的通信库，使用Fast-DDS。
* [ROS 2 Java](https://github.com/ros2-java/ros2_java)：这是一组使开发人员能够为JVM和Android编写ROS 2应用程序的项目。
* [JROS2](https://github.com/ihmcrobotics/jros2)：一个Java版ROS 2库，使用Fast-DDS中间件。
* [jAER](https://github.com/SensorsINI/jaer)：用于地址事件表示(AER)神经形态处理的Java工具，由苏黎世联邦理工学院开源
* [ROSJava](https://github.com/rosjava/rosjava_core)：ROSJava是ROS的第一个纯Java实现。
* [OpenTCS NeNa](https://github.com/nielstiben/openTCS-NeNa)：OpenTCS-NeNa软件是一款OpenTCS车辆驱动程序，用于连接ROS2机器人和OpenTCS车队管理器，由萨克逊大学开源。
* [DARP](https://github.com/athakapo/DARP)：用于最优多机器人覆盖路径规划的划分区域算法。
* [YAGSL](https://github.com/BroncBotz3481/YAGSL)：YAGSL是一个由现任和前任BroncBotz导师为所有FRC团队开发的转向库。
* [Caliko](https://github.com/FedUni/caliko)：Caliko库是Java语言FABRIK逆运动学(IK)算法的实现，由澳大利亚联邦大学开源。
* [FTCVision](https://github.com/lasarobotics/FTCVision)：FTCVision是基于OpenCV的FTC计算机视觉库，由FRC 418团队开源。
* [Maple SIM](https://github.com/Shenzhen-Robotics-Alliance/maple-sim)：利用物理引擎将FRC Java机器人模拟提升到新水平，由深圳市机器人产业联盟开源。
* [JROSBridge](https://github.com/rctoris/jrosbridge)：原生Java EE ROSBridge客户端，由伍斯特理工学院开源。
* [Robot Overlord](https://github.com/MarginallyClever/Robot-Overlord-App)：Robot Overlord是一款机器人3D控制软件，由Marginally Clever Robots开源。
* [BowlerStudio](https://github.com/CommonWealthRobotics/BowlerStudio)：BowlerStudio是一款机器人开发应用程序，它将脚本和设备管理与强大的控制和处理功能结合在一起。
* [Firmata4j](https://github.com/kurbatov/firmata4j)：Firmata4j是用Java编写的Firmata客户端库，该库允许从你的Java程序控制运行Firmata协议的Arduino。
* [StuyLib](https://github.com/StuyPulse/StuyLib)：StuyLib是一个FRC库/工具包，其中包括许多不同的编程实用程序；它包括游戏手柄库、Limelight库、数字滤波器/流库以及许多其他与数学和编程相关的实用程序，由史岱文森高中的FIRST机器人团队开发。
* [PhotonVision](https://github.com/PhotonVision/photonvision)：PhotonVision是FIRST机器人竞赛的免费、快速且易于使用的计算机视觉解决方案。
* [EasyOpenCV](https://github.com/OpenFTC/EasyOpenCV)：EasyOpenCV是OpenFTC提供的一个库，简化了在FTC中使用OpenCV进行计算机视觉处理的过程。
* [AdvantageKit](https://github.com/Mechanical-Advantage/AdvantageKit)：AdvantageKit是由Team 6328开发的日志记录、遥测和重放框架。
* [Robo4J](https://github.com/Robo4J/robo4j)：Robo4J提供了一种简单的方法来开始构建自定义硬件并为其创建在JVM上运行的软件。
* [Makelangelo](https://github.com/MarginallyClever/Makelangelo-software)：Makelangelo软件是一个Java程序，可为CNC绘图仪准备艺术品，最初是为Makelangelo艺术机器人设计的。
* [FTCLib](https://github.com/FTCLib/FTCLib)：FTCLib是一个旨在成为FTC编程所需的唯一库的库。
* [MuJoCo Java](https://github.com/CommonWealthRobotics/mujoco-java)：MuJoCo物理系统的Java JNI绑定。
* [Road Runner](https://github.com/acmerobotics/road-runner)：一个简单的Kotlin库，用于规划专为FTC设计的2D移动机器人路径和轨迹。
* [FtcRobotController](https://github.com/FIRST-Tech-Challenge/FtcRobotController)：该仓库包含用于构建Android应用程序以控制FIRST Tech Challenge竞赛机器人的源代码。
* [IIWA STACK](https://github.com/IFL-CAMP/iiwa_stack)：适用于KUKA LBR IIWA R800/R820(7/14公斤)的ROS Indigo/Kinetic元包。
* [MASON](https://github.com/eclab/mason)：MASON是一个基于Java的快速代理模拟库核心，旨在成为大型定制Java模拟的基础，并为许多轻量级模拟需求提供足够的功能，由乔治梅森大学开源。
* [VirtualRoBot](https://github.com/Beta8397/virtual_robot)：VirtualRoBot是一款2D机器人模拟器，帮助初学者学习FTC Robotics的Java编程，由FTC Team 8397 Beta开源。
* [Pedro Pathing](https://github.com/Pedro-Pathing/PedroPathing)：Pedro Pathing是一种先进的反应矢量跟随器，由FTC团队10158开发，旨在彻底改变机器人的自主导航。
* [Third Coast](https://github.com/strykeforce/thirdcoast)：适用于FRC机器人的Third Coast转向驱动和遥测API，由Stryke Force FRC 2767机器人团队开发。
* [MAPF](https://github.com/J-morag/MAPF)：几种MAPF算法的Java实现。
* [Meanlib](https://github.com/TeamMeanMachine/meanlib)：Meanlib是由Team 2471 Mean Machine制作的Kotlin FRC机器人实用程序库。

## 数学库

* [SuanShu](https://github.com/aaiyer/SuanShu)：SuanShu是一个Java数学库，用于数值分析、统计、求根、线性代数、优化等。
* [JSci](https://jsci.sourceforge.net/)：JSci是一组免费的Java包，目的是以最自然的方式概括科学方法/原理，由杜伦大学开源。
* [JavaPlex](https://github.com/appliedtopology/javaplex)：JavaPlex库实现了计算和应用拓扑中的持久同源性和相关技术，由斯坦福大学开源。
* [JLaTeXMath](https://github.com/opencollab/jlatexmath)：JLaTeXMath是显示LaTeX代码的最佳Java库。
* [JMathTeX](https://jmathtex.sourceforge.net/)：JMathTeX库提供了一组Java类，用于将数学公式作为Java应用程序的一部分显示。
* [JBibTeX](https://github.com/jbibtex/jbibtex)：Java BibTeX和LaTeX解析器和格式化程序库。
* [Ryu](https://github.com/ulfjack/ryu)：该项目包含使用最短、固定%f和科学%e格式将IEEE-754浮点数转换为十进制字符串的例程。
* [Hacktoberfest Mathematics](https://github.com/BaReinhard/Hacktoberfest-Mathematics)：数学公式和函数的脚本和/或程序库。
* [JTransforms](https://github.com/wendykierp/JTransforms)：JTransforms是第一个用纯Java编写的开源多线程FFT库。
* [SSJ](https://github.com/umontreal-simul/ssj)：SSJ是一个用于随机模拟的Java库，由蒙特利尔大学开发。
* [DDoggeg](https://github.com/lessthanoptimal/ddogleg)：DDoggeg是一个高性能Java库，用于非线性优化、稳健模型拟合、多项式求根、排序等。
* [Catalano](https://github.com/DiegoCatalano/Catalano-Framework)：Catalano是一个用于Java和Android的科学计算框架。
* [Curves API](https://github.com/virtuald/curvesapi)：实现各种基于一组控制点定义的数学曲线。
* [Java Math Library](https://github.com/TilmanNeumann/java-math-library)：专注于数论和整数分解的Java数学库。
* [MorphoLibJ](https://github.com/ijpb/MorphoLibJ)：MorphoLibJ是ImageJ的数学形态学方法和插件的集合，由INRA-IJPB建模和数字成像实验室创建。
* [Rings](https://github.com/PoslavskySV/rings)：Rings是一个高效的轻量级交换代数库。
* [JPOP](https://www5.cs.fau.de/research/software/java-parallel-optimization-package/)：JPOP是一个开源软件库，允许最小化非线性函数，由斯坦福大学开源。
* [MathEngine](https://github.com/raharrison/MathEngine)：一个数学库，配备高级表达式解析器，带有自定义函数，并支持向量和矩阵。

#### 线性代数

* [Breeze](https://github.com/scalanlp/breeze)：Breeze是一组用于机器学习和数值计算的库。
* [JAMA](https://math.nist.gov/javanumerics/jama/)：JAMA是Java的基本线性代数包，它提供了用于构造和操作真实的稠密矩阵的用户级类，由马里兰大学和美国国家标准与技术研究院开发。
* [JOML](https://github.com/JOML-CI/JOML)：JOML的目标是提供易于使用、功能丰富且高效的线性代数运算，以满足任何三维应用的需求。
* [ND4j](https://github.com/deeplearning4j/deeplearning4j/tree/master/nd4j)：通用线性代数库，包含500多个数学、线性代数和深度学习运算。
* [Symja](https://github.com/axkr/symja_android_library)：Symja是计算机代数语言和符号数学库，用纯Java实现的流行算法的集合。
* [JAS](https://github.com/kredel/java-algebra-system)：JAS是一种面向对象、类型安全且多线程的计算机代数方法，由曼海姆大学开源。
* [Scalala](https://github.com/scalala/Scalala)：Scalala是一个高性能Scala数值线性代数库，具有丰富的类似Matlab的向量和矩阵运算符，由斯坦福开源。
* [Mines JTK](https://github.com/MinesJTK/jtk)：Mines Java Toolkit是一组用于科学和工程的Java包和原生软件库，目前的应用包括数字信号处理、线性代数、优化、网格划分、插值以及2D和3D图形，由科罗拉多矿业学院开发。
* [Ojalgo](https://github.com/optimatika/ojAlgo)：Ojalgo是用于数学、线性代数和优化的开源Java代码。
* [EJML](https://github.com/lessthanoptimal/ejml)：EJML是一个用Java编写的快速且易于使用的线性代数库，适用于稠密、稀疏、实数和复杂矩阵。
* [La4j](https://github.com/vkostyukov/la4j)：La4j是一个开源的Java库，提供线性代数基元(矩阵和向量)和算法。
* [NetLib Java](https://github.com/fommil/netlib-java)：NetLib Java是低级BLAS、LAPACK和ARPACK的包装器，其执行速度与带有纯JVM回退的C/Fortran接口一样快。
* [OwlPack](https://www.cs.rice.edu/%7Ezoran/OwlPack/)：OwlPack是一个多态、面向对象风格的Java通用线性代数库，基于标准Fortran LINPACK库，由莱斯大学开源。
* [Matrix Toolkits Java](https://github.com/fommil/matrix-toolkits-java)：MTJ是一个用于开发线性代数应用程序的高性能库。
* [GLPK](https://winglpk.sourceforge.net/)：GLPK软件包提供了用于大规模线性规划(LP)和混合整数规划(MIP)的求解器。
* [LAML](https://sites.google.com/site/qianmingjie/home/toolkits/laml)：LAML是一个独立的纯Java线性代数和机器学习库。
* [JLinAlg](https://github.com/JLinAlg/JLinAlg)：JLinAlg是一个开源且易于使用的线性代数Java库。
* [Orbital](https://github.com/LS-Lab/orbital)：Orbital是一个Java类库，为逻辑、数学和计算机科学提供面向对象的表示和算法，由卡尔斯鲁厄理工学院开源。
* [Ptolemaeus](https://gitlab.com/lmco/ptolemaeus)：为实数和复数值线性代数、非线性优化、超维计算几何、动力系统等开发的Java数学库，由洛克希德马丁公司开发。
* [Keigen](https://github.com/paramsen/Keigen)：Keigen是Eigen的Kotlin包装器，Eigen是一个用C++编写的线性代数库。

#### 矩阵

* [Colt](https://dst.lbl.gov/ACSSoftware/colt/)：Java中用于高性能科学计算的库，它包含用于数据分析、线性代数、多维数组、傅里叶变换、统计和直方图的有效算法，由欧洲核子研究中心开发。
* [ParallelColt](https://github.com/rwl/ParallelColt)：Parallel Colt是Colt的多线程版本，由欧洲核子研究组织开源。
* [Jampack](https://math.nist.gov/pub/Jampack/Jampack/AboutJampack.html)：Jampack是一个协作类的集合，旨在在Java应用程序中执行矩阵计算，由马里兰大学和美国国家标准与技术研究院开发。
* [Jeigen](https://github.com/hughperkins/jeigen)：Jeigen提供了高性能C++矩阵库Eigen的包装器。
* [Graphulo](https://github.com/Accla/graphulo)：Graphulo是一个用于Accumulo数据库的Java库，提供服务器端稀疏矩阵数学原语，支持更高级别的图形算法和分析，MIT开源。
* [Neanderthal](https://github.com/uncomplicate/neanderthal)：Neanderthal是一个用于快速矩阵和线性代数计算的Clojure库，基于针对CPU和GPU的高度优化的BLAS和LAPACK计算例程的原生库。
* [Jblas](https://github.com/jblas-project/jblas)：Jblas是一个Java矩阵库，它使用现有的高性能BLAS和LAPACK库(如ATLAS)，由柏林工业大学开源。
* [Marlin](https://github.com/PasaLab/marlin)：在Spark之上构建的分布式矩阵运算库，由南京大学开发。
* [UJMP](https://github.com/ujmp/universal-java-matrix-package)：UJMP是一个开源库，用于Java中的密集和稀疏矩阵计算以及线性代数。
* [Vectorz](https://github.com/mikera/vectorz)：Vectorz是Java的快速双精度向量和矩阵数学库。
* [Math](https://github.com/SpongePowered/math)：用于Java的不可变数学库，提供数学类型、快速三角函数、向量、矩阵、复数、四元数和操作链之间的轻松转换。
* [F2J](https://sourceforge.net/projects/f2j)：F2J项目的目标是为最初用Fortran编写的数值库(特别是BLAS和LAPACK)提供Java API，由田纳西大学开源。
* [Jspline+](https://www.mathematik.hu-berlin.de/~lamour/software/JAVA/J_Spline/overview-summary.html)：Jspline+实现了各种样条函数，这些样条函数可通过在一维或多维散点网格上进行函数测量来构造，由新西伯利亚计算中心开源。
* [BIDMat](https://github.com/BIDData/BIDMat)：BIDMat是一个非常快速的矩阵代数库，由伯克利BID实验室研发。
* [YiShape Math](https://github.com/ScaleFree-Tech/yishape-math)：YiShape Math是一个基于Java开发的数学计算库，提供向量&矩阵运算、数据可视化、统计学、最优化、时间序列、信号处理、音频分析、图像处理和机器学习等核心功能，由电子科技大学开源。

#### 多维数组

* [Eclipse January](https://github.com/eclipse/january)：January是一组用于在Java中处理数值数据的库，它部分受到NumPy的启发，旨在提供类似的功能。
* [NumJ](https://github.com/J-Libraries/numJ)：NumJ是一个受NumPy启发的Java库，提供对多维数组和数学运算的支持。
* [Tensorics](https://github.com/tensorics/tensorics-core)：Tensorics是一个用于多维数据处理的Java框架。
* [NdArray Java](https://github.com/tensorflow/java-ndarray)：NdArray公开了用于在Java中操作N维空间中的数据的实用程序，由Tensorflow开源。
* [Shared Scientific Toolbox](https://carsomyr.github.io/shared/)：SST是基础科学库的集合，其主要目的是充当所涉及的科学计算的高度特定需求与Java编程语言的更传统方面之间的桥梁。
* [Multik](https://github.com/Kotlin/multik)：Kotlin的多维数组库。

#### 数值计算

* [JNT](https://math.nist.gov/jnt/)：JNT包含计算内核的坚实基础，可以帮助引导开发Java中复杂数值应用程序的工作，由美国国家标准与技术研究院开源。
* [SymJava](https://github.com/yuemingl/SymJava)：SymJava是一个用于符号数值计算的Java库。
* [Maja](https://github.com/iczelia/Maja)：Maja是一个精巧的面向数值的Java数学库。
* [Apache Commons Numbers](https://github.com/apache/commons-numbers)：Commons Numbers提供数字类型和实用程序的实现。
* [IMSL](https://www.perforce.com/products/imsl)：IMSL是一套跨平台数值库，可用于Fortran、C、Java和Python。
* [Dtype Next](https://github.com/cnuernber/dtype-next)：Dtype Next为处理原始数据类型(例如int和float)的连续容器提供了统一的途径。

#### 多精度

* [JUMP](https://sourceforge.net/projects/jump-math/)：JUMP是一个基于Java的可扩展高精度数学包，包括对基于分数的计算的支持，支持转换为浮点数和BigDecimal。
* [JNA GMP](https://github.com/square/jna-gmp)：GNU多精度算术库的Java JNA包装器，由Square开源。
* [Apfloat](https://github.com/mtommila/apfloat)：Apfloat是一个高性能任意精度算术库，你可以用它进行数百万位精度的计算。
* [Cojac](https://github.com/Cojac/Cojac)：Cojac旨在提高Java数字的算术能力，由弗里堡大学开源。
* [BigDecimalMath](https://github.com/eobermuhlner/big-math)：使用任意精度的高级Java BigDecimal数学函数库。
* [Decimal4j](https://github.com/tools4j/decimal4j)：用于基于长整型的快速定点算术的Java库，支持最多18位小数。
* [Huldra](https://github.com/bwakell/Huldra)：该项目旨在提供高效的Java原语，主要涉及任意精度整数运算。
* [Kotlin MP BigNum](https://github.com/ionspin/kotlin-multiplatform-bignum)：Kotlin MP BigNum库是一个纯Kotlin实现的任意精度算术运算。

#### 微分

* [KotlinGrad](https://github.com/breandan/kotlingrad)：JVM的类型安全符号微分，由蒙特利尔大学开源。
* [JAutoDiff](https://github.com/uniker9/JAutoDiff)：JAutoDiff是一个用100%纯Java编写的自动微分库。
* [NM Dev](https://nm.dev/)：NM Dev是一个数值库，涵盖了广泛的算法，例如线性代数、微积分、微分方程、无约束和约束优化、统计学和极值理论。

#### Math扩展

* [ELEFUNT](http://www.math.utah.edu/~beebe/software/java/)：ELEFUNT附带了一个扩展了java.lang.Math的新类库，以及用于数字输出格式化的新类库，由犹他大学开源。
* [BigInt](https://github.com/tbuktu/bigint)：这是java.math.BigInteger的改进版本，它使用快速算法来乘除大数。
* [Jafama](https://github.com/jeffhain/jafama)：Jafama是一个Java库，旨在提供更快版本的java.lang.Math处理，最终代价是1e-15ish精度误差，但仍能正确处理特殊情况。
* [KMath](https://github.com/SciProgCentre/kmath)：Kotlin数学扩展库，由莫斯科物理技术学院开源。
* [BigDecimal Utils](https://github.com/mortezaadi/bigdecimal-utils)：用于比较BigDecimal的工具库。
* [Apache Commons Math](https://github.com/apache/commons-math)：Commons Math是一个开源的数学库，提供了一系列基础数学算法和高级数学功能。
* [FastDoubleParser](https://github.com/wrandelshofer/FastDoubleParser)：该项目提供了double、float、BigDecimal和BigInteger值的解析器，double和float解析器针对最常见输入的速度进行了优化。

#### 向量

* [LIBLINEAR](https://github.com/bwaldvogel/liblinear-java)：LIBLINEAR的Java版本，LIBLINEAR是一个用于解决大规模正则化线性问题分类、回归和异常值检测的简单包。
* [Prim](https://github.com/mgormley/prim)：Prim是一个类似于Trove的Java原始类型库，重点关注向量和矩阵的稀疏表示，由约翰霍普金斯大学开发。
* [Euclid](https://github.com/ihmcrobotics/euclid)：Euclid是一个解决向量数学和几何问题的通用库，由IHMC机器人实验室开源。
* [Vectorz Clj](https://github.com/mikera/vectorz-clj)：Clojure的快速向量和矩阵库，基于Vectorz库构建。

#### 统计

* [UnCommons Maths](https://github.com/dwdyer/uncommons-maths)：Java的随机数生成器、概率分布、组合学和统计库。
* [Hipparchus](https://github.com/Hipparchus-Math/hipparchus)：Hiparchus项目是一个轻量级、独立的数学和统计组件库，可解决Java编程语言中无法解决的最常见问题。
* [JMSL](http://www.aertia.com/en/productos.asp?pid=238)：JMSL是全面的Java数学、统计、金融、数据挖掘和图表类库。
* [JDistlib](https://jdistlib.sourceforge.net/)：JDistlib是一个提供各种统计分布例程的Java包。

#### 直方图

* [HdrHistogram](https://github.com/HdrHistogram/HdrHistogram)：HdrHistogram支持在可配置的整数值范围内记录和分析采样数据值计数，并在该范围内具有可配置的值精度。
* [DynaHist](https://github.com/dynatrace-oss/dynahist)：此Java库包含直方图实现。
* [Histogram](https://github.com/bigmlcom/histogram)：该项目是Ben-Haim的流式并行决策树中描述的流式一次性直方图的实现。
* [Hist4J](https://github.com/flaptor/hist4j)：Hist4J是一个简单的高性能值聚合器。

#### 运筹学

* [OR-Tools](https://github.com/google/or-tools)：OR-Tools是一款用于解决组合优化问题的开源、快速且可移植的软件套件，由Google开源。
* [jORLib](https://github.com/coin-or/jorlib)：jORLib是一个Java类库，提供运筹学问题的实现。

## 图处理

* [GraphX](https://github.com/apache/spark/tree/master/graphx)：Spark GraphX是一个分布式图处理框架，它是基于Spark平台提供对图计算和图挖掘简洁易用的而丰富的接口。
* [GeaFlow](https://github.com/apache/geaflow)：GeaFlow是蚂蚁集团的流图计算引擎。
* [GraphJet](https://github.com/twitter/GraphJet)：GraphJet是一个用Java编写的实时图处理库，由Twitter开源。
* [GoldenOrb](https://github.com/jzachr/goldenorb)：GoldenOrb是Google图处理框架Pregel的开源实现。
* [Graphviz Java](https://github.com/nidi3/graphviz-java)：将Graphviz与纯Java一起使用，使用Java代码创建Graphviz模型并将其转换为漂亮的图形。
* [GraphChi](https://github.com/GraphChi/graphchi-java)：GraphChi是一个基于磁盘的大规模图计算系统，由CMU开源。
* [LynxKite](https://github.com/lynxkite/lynxkite)：LynxKite是一个完整的图数据科学平台，适用于超大型图和其他数据集。
* [GraphFrames](https://github.com/graphframes/graphframes)：GraphFrames是一个基于DataFrame的图包，由加州大学伯克利分校、MIT和Databricks开源。
* [Gradoop](https://github.com/dbs-leipzig/gradoop)：Gradoop是一个开源研究框架，用于构建在Flink之上的可扩展图分析，由莱比锡大学数据库研究组开发。
* [SociaLite](https://github.com/socialite-lang/socialite)：SociaLite是一种用于分布式图分析的高级查询语言，由斯坦福开源。
* [GraphScope](https://github.com/alibaba/GraphScope)：GraphScope是阿里巴巴达摩院智能计算实验室研发并开源的一站式图计算平台。
* [JUNG](https://github.com/jrtom/jung)：JUNG是一个软件库，它提供了一种通用且可扩展的语言，用于对可以表示为图形或网络的数据进行建模、分析和可视化。
* [PGQL](https://github.com/oracle/pgql-lang)：PGQL是一种基于SQL的属性图数据模型查询语言，为SQL和NoSQL用户带来图模式匹配功能，由Oracle开源。
* [Ant Graph Learning](https://github.com/TuGraph-family/TuGraph-AntGraphLearning)：Ant Graph Learning为工业规模的图学习任务提供了全面的解决方案，由蚂蚁开源。
* [GraphBuilder](https://github.com/intel/graphbuilder)：GraphBuilder库提供了构建大规模图的函数，由Intel开源。
* [GraphStream](https://github.com/graphstream/gs-core)：GraphStream项目是一个Java库，提供API来建模、分析和可视化图和动态图，由勒阿弗尔大学开源。
* [Erdos](https://github.com/Erdos-Graph-Framework/Erdos)：Erdos是一个非常轻量、模块化且超级易于使用的Java现代图论算法框架。
* [Signal/Collect](https://github.com/uzh/signal-collect)：Signal/Collect是一个用于大型图计算的框架，由苏黎世大学开源。
* [Neo4j Graph Data Science](https://github.com/neo4j/graph-data-science)：GDS包括图算法、图转换和机器学习管道，通过Neo4j DBMS内的Cypher程序进行操作。
* [GraphTea](https://github.com/rostam/GraphTea)：GraphTea是一个用于处理图和社交网络的软件框架。

## 本体库

* [OWLAPI](https://github.com/owlcs/owlapi)：OWL API是用于创建、操作和序列化OWL本体的Java API，由曼彻斯特大学开源。
* [Apache Jena](https://github.com/apache/jena)：Jena是一个免费的开源Java框架，用于构建语义Web和链接数据应用程序，最初由惠普实验室开发。
* [Widoco](https://github.com/dgarijo/Widoco)：WIDOCO是一个带有本体文档的HTML模板逐步生成器，它使用LODE环境来创建部分模板，由芬欧汇川大学本体工程组开发。
* [ROBOT](https://github.com/ontodev/robot)：ROBOT是一个用于自动化本体开发任务的命令行工具和库，专注于开放生物和生物医学本体。
* [SciGraph](https://github.com/SciGraph/SciGraph)：SciGraph旨在将本体和使用本体描述的数据表示为Neo4j图。
* [OWLTools](https://github.com/owlcollab/owltools)：OWLTools是OWL API之上的便捷Java API。
* [Slib](https://github.com/sharispe/slib)：Slib是一个致力于基于文本和/或本体处理的语义数据挖掘的Java库。
* [OLGA](https://github.com/EcoStruxure/OLGA)：OLGA是一种通用工具，旨在加速开发人员采用标准W3C语义技术，由施耐德电气开源。
* [OBOGraphs](https://github.com/geneontology/obographs)：该仓库包含用于本体交换的JSON/YAML格式规范，以及参考Java对象模型和OWL转换器。
* [O'FAIRe](https://github.com/agroportal/fairness)：O'FAIRe是一种开源公平性评估方法和工具，适用于D2KAB和FooSIN项目中开发的本体、词汇和语义资源，由蒙彼利埃大学开源。
* [OPPL 2](https://sourceforge.net/projects/oppl2/)：OPPL 2是OPPL(本体预处理语言)的第二个版本，它是一种旨在修改OWL本体的语言。
* [Ontology Modeling Language](https://github.com/opencaesar/oml)：OML语言支持定义系统工程词汇并使用它们来描述系统，由加州理工学院开源。
* [Phenol](https://github.com/monarch-initiative/phenol)：Phenol是一个现代Java库，用于处理表型本体和其他属性本体。
* [STATO](https://github.com/ISA-tools/stato)：STATO是一个通用的统计本体，由牛津大学开源。
* [JOPA](https://github.com/kbss-cvut/jopa)：JOPA是一个Java OWL持久层框架，旨在以Java方式高效地以编程方式访问OWL2本体和RDF图，由布拉格捷克技术大学开源。
* [ZOOMA](https://github.com/EBISPOT/zooma)：ZOOMA是一款用于发现最佳本体映射的应用程序，由欧洲分子生物学实验室开发。

#### 本体编辑器

* [Protege](https://github.com/protegeproject/protege)：Protege是一个免费的开源本体编辑器，支持最新的OWL 2.0标准，由斯坦福开源。
* [WebProtégé](https://github.com/protegeproject/webprotege)：WebProtégé是一个免费的开源协作本体开发环境，由斯坦福开源。
* [Tawny OWL](https://github.com/phillord/tawny-owl)：Tawny OWL允许在评估性、功能性和完全编程性的环境中构建OWL本体，由纽卡斯尔大学开源。
* [OntoBrowser](https://github.com/Novartis/ontobrowser)：OntoBrowser是一个基于Web的应用程序，用于管理本体。
* [OntoGraph](https://github.com/NinePts/OntoGraph)：OWL本体绘图程序。
* [Sigma](https://github.com/ontologyportal/sigmakee)：Sigma是一个用于扩展建议上层合并本体(SUMO)的逻辑理论集成开发环境。
* [Vitro](https://github.com/vivo-project/Vitro)：Vitro是一个通用的基于Web的本体和实例编辑器，具有可定制的公共浏览功能，由康奈尔大学开源。

#### 本体推理机

* [Pellet](https://github.com/stardog-union/pellet)：Pellet是Java中的OWL 2推理机，由Complexible开发。
* [HermiT](https://github.com/phillord/hermit-reasoner)：HermiT是一个符合OWL 2 DL标准的推理器，使用直接语义，由牛津大学开源。
* [Openllet](https://github.com/Galigator/openllet)：Openllet是一个用Java编写的OWL 2推理器，建立在Pellet之上，由巴黎第十一大学开源。
* [FaCT++](https://github.com/tilde-lab/pyfactxx)：FaCT++是一款经过良好优化的开源推理器，用于SROIQ描述逻辑，由曼彻斯特大学开源。
* [ELK Reasoner](https://github.com/liveontologies/elk-reasoner)：ELK是一个本体推理器，旨在支持OWL 2 EL配置文件，由乌尔姆大学人工智能研究所和牛津大学计算机科学系知识表示和推理小组开源。
* [Aristotle](https://github.com/arachne-framework/aristotle)：Clojure的RDF/OWL库，为Apache Jena提供面向数据的包装器。

#### 本体匹配

* [LogMap](https://github.com/ernestojimenezruiz/logmap-matcher)：LogMap是一个高度可扩展的本体匹配系统，具有内置推理和不一致修复功能，由牛津大学、伦敦城市大学开源。
* [MELT](https://github.com/dwslab/melt)：MELT是一个强大的Maven框架，用于开发、调整、评估和打包本体匹配系统，由德国曼海姆大学开源。
* [AgreementMaker](https://github.com/agreementmaker/agreementmaker)：AgreementMaker是一个本体匹配系统，由伊利诺伊大学芝加哥分校开源。

#### 本体转换

* [Ontmalizer](https://github.com/srdc/ontmalizer)：Ontmalizer自动执行XML模式(XSD)和XML数据到RDF/OWL的全面转换。
* [Snomed OWL Toolkit](https://github.com/IHTSDO/snomed-owl-toolkit)：一个开源工具包，使SNOMED CT到OWL的转换和分类变得简单。
* [OWL2VOWL](https://github.com/VisualDataWeb/OWL2VOWL)：OWL2VOWL是一个用于将给定本体转换为JSON格式的工具。
* [LODE](https://github.com/essepuntato/LODE)：实时OWL文档环境，用于将OWL本体转换为HTML人类可读页面，由博洛尼亚大学开源。
* [IFCtoLBD](https://github.com/jyrkioraskari/IFCtoLBD)：IFCtoLBD将IFC STEP格式的文件转换为链接建筑数据本体。

#### RDF库

* [Apache Jena](https://github.com/apache/jena)：Jena是一个免费的开源Java框架，用于构建语义Web和链接数据应用程序，最初由惠普实验室开发。
* [Eclipse RDF4J](https://github.com/eclipse-rdf4j/rdf4j)：RDF4J是一个强大的Java框架，用于处理RDF数据，这包括使用RDF和链接数据创建、解析、可扩展存储、推理和查询。
* [Apache Commons RDF](https://github.com/apache/commons-rdf)：Commons RDF旨在为RDF 1.1提供一个通用库，并实现常见Java RDF框架(如RDF4J、Jena)以及其他库(如OWLAPI、Clerezza和其他JVM语言)的实现。
* [RDF Toolkit](https://github.com/edmcouncil/rdf-toolkit)：RDF Toolkit是一个用于读写多种格式的RDF文件的工具。
* [Ripple](https://github.com/joshsh/ripple)：Ripple是一种基于堆栈的函数式查询语言，适用于关联数据和其他RDF数据源。
* [ONT API](https://github.com/owlcs/ont-api)：ONT API是一个以RDF为中心的Java库，可与OWL2配合使用，由曼彻斯特大学开源。
* [KOMMA](https://github.com/komma/komma)：KOMMA是一个RDF对象映射器，也是一个用于管理和编辑RDF、RDFS和OWL的框架，由弗劳恩霍夫机床和成形技术研究所开源。
* [Apache Clerezza](https://github.com/apache/clerezza)：Apache Clerezza是一组用于管理语义链接数据的Java库。
* [Corese](https://github.com/Wimmics/corese)：Corese是一个实现和扩展语义网标准的软件平台，它允许创建、操作、解析、序列化、查询、推理和验证RDF数据，由蔚蓝海岸大学开源。
* [Wikidata Toolkit](https://github.com/Wikidata-Toolkit/Wikidata-Toolkit)：Wikidata Toolkit是一个用于访问Wikidata和其他Wikibase的Java库。
* [RDFUnit](https://github.com/AKSW/RDFUnit)：RDFUnit在测试驱动数据验证本体之上实现，旨在读取和生成仅符合该本体的RDF，由莱比锡大学开源。
* [RDF File](https://github.com/alipay/rdf-file)：RDF File是一个处理结构化文本文件的工具组件，由支付宝开源。
* [Empire](https://github.com/mhgrove/Empire)：Empire使用SPARQL为RDF数据库提供标准JPA风格的接口。
* [HDT](https://github.com/rdfhdt/hdt-java)：HDT-Lib是一个Java库，它实现了RDF HDT(标头-字典-三元组)二进制格式的W3C提案。
* [RMLMapper](https://github.com/RMLio/rmlmapper-java)：RMLMapper执行RML规则来生成关联数据，由根特大学开源。
* [CARML](https://github.com/carml/carml)：CARML是一个Java库，它根据RML规范将结构化源转换为RML映射中声明的RDF。
* [JSON2RDF](https://github.com/AtomGraph/JSON2RDF)：流式的通用JSON到RDF转换器。
* [Pinto](https://github.com/stardog-union/pinto)：Pinto是一个Java框架，用于将JavaBean转换为RDF。
* [jRDF2Vec](https://github.com/dwslab/jRDF2Vec)：jRDF2Vec是RDF2Vec的Java实现，它支持多线程、内存中(或基于磁盘访问)的步行生成和训练，由德国曼海姆大学开源。
* [Jelly](https://github.com/Jelly-RDF/jelly-jvm)：Jelly是一种用于RDF知识图谱的高性能二进制序列化格式和流式传输协议。
* [RDFstarTools](https://github.com/RDFstar/RDFstarTools)：该软件包提供了一组命令行工具和Java库来处理RDF\*数据和SPARQL\*查询。
* [Tarql](https://github.com/tarql/tarql)：Tarql是一个命令行工具，使用SPARQL 1.1语法将CSV文件转换为RDF。
* [Sparqlify](https://github.com/Scaseco/Sparqlify)：Sparqlify是一个SPARQL-SQL重写器，它允许用户在关系型数据库上定义RDF视图并使用SPARQL进行查询。
* [Elda](https://github.com/epimorphics/elda)：Elda是Linked Data API的Java实现，它提供了一种可配置的方式，使用简单的RESTful URL访问RDF数据，这些URL被转换为对SPARQL端点的查询。

#### 语义Web

* [VIVO](https://github.com/vivo-project/VIVO)：VIVO是一个可扩展的语义Web应用程序，用于研究发现和展示学术工作。
* [Karma](https://github.com/usc-isi-i2/Web-Karma)：Karma是一种信息集成工具，使用户能够快速轻松地集成来自各种数据源的数据，由南加州大学信息科学研究所开源。
* [SPARQL](https://github.com/SPARQL-Anything/sparql.anything)：SPARQL Anything是一个用于语义Web重新设计的系统，允许用户使用SPARQL查询任何内容。
* [LinkedGeoData](https://github.com/GeoKnow/LinkedGeoData)：LinkedGeoData致力于向数据网/语义网添加空间维度，由莱比锡大学开源。
* [YAGO](https://github.com/yago-naga/yago3)：YAGO是一个大型语义知识库，包含有关人物、城市、国家、电影和组织的一般知识，由巴黎高科电信大学、马克斯普朗克信息研究所以及Ambiverse联合开发。
* [D2RQ](https://github.com/d2rq/d2rq)：D2RQ平台是一个用于以虚拟只读RDF图形式访问关系数据库的系统，由约翰开普勒林茨大学、HP实验室等组织开源。
* [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN)：HeFQUIN是一种用于图数据源异构联合的查询联合引擎，目前由林雪平大学开发。
* [LodView](https://github.com/LodLive/LodView)：LodView是一个基于Spring和Jena的Java Web应用程序，它是一个能够提供符合W3C标准的IRI解引用的工具。
* [Trellis](https://github.com/trellis-ldp/trellis)：Trellis是一个用于构建可扩展的关联数据应用程序的平台。
* [SHACL](https://github.com/TopQuadrant/shacl)：基于Apache Jena的W3C形状约束语言(SHACL)的开源实现。
* [Racer](https://github.com/ha-mo-we/Racer)：Racer是一个知识表示系统，它为描述逻辑SRIQ(D)实现了高度优化的表格演算。
* [Bio2RDF](https://github.com/bio2rdf/bio2rdf-scripts)：Bio2RDF是一个开源项目，它使用语义网技术构建并提供生命科学领域最大的关联数据网络。

#### 知识图谱

* [Ontop](https://github.com/ontop/ontop)：Ontop是一个虚拟知识图谱系统，它将任意关系数据库的内容公开为知识图，由博尔扎诺自由大学开源。
* [Athens](https://github.com/athensresearch/athens)：Athens是一个开源的协作知识图谱。
* [Mobi](https://github.com/inovexcorp/mobi)：Mobi是一个协作知识图谱平台，供团队和社区开发和发布语义数据和模型。
* [DMX](https://github.com/dmx-systems/dmx-platform)：DMX是一个知识构建平台。
* [Renku](https://github.com/SwissDataScienceCenter/renku)：Renku是一个将各种工具捆绑在一起的平台，用于可重复和协作的数据分析项目，由瑞士数据科学中心开源。
* [Nexus](https://github.com/BlueBrain/nexus)：Blue Brain Nexus是一个生态系统，它允许你通过知识图谱来组织和更好地利用数据，由洛桑联邦理工学院开源。
* [OpenSPG](https://github.com/OpenSPG/openspg)：OpenSPG是蚂蚁集团与OpenKG合作开发的基于SPG(语义增强可编程图)框架的知识图引擎。
* [LinkedDataHub](https://github.com/AtomGraph/LinkedDataHub)：LinkedDataHub是一款开源软件，可用于管理数据、创建可视化以及在RDF知识图上构建应用程序。
* [AMIE](https://github.com/dig-team/amie)：AMIE是一个在知识库上挖掘Horn规则的系统，由巴黎电信学院开源。
* [CM-Well](https://github.com/CM-Well/CM-Well)：CM-Well是一个开源、可写入的链接数据存储库，由汤森路透和路孚特开发，并用作其核心知识图谱数据库。
* [K#](https://github.com/Samsung/KnowledgeSharingPlatform)：K#旨在利用各种大规模数据源构建复杂的企业知识图谱，由三星开源。
* [Semantic Synchrony](https://github.com/synchrony/smsn)：Semantic Synchrony让任何人都能编辑和使用知识图谱。

## 生物信息学

* [BioJava](https://github.com/biojava/biojava)：BioJava是一个开源项目，致力于提供处理生物数据的Java框架。
* [Bioinf Commons](https://github.com/JetBrains-Research/bioinf-commons)：Kotlin中的生物信息学库，由JetBrains开源。
* [Bio Formats](https://github.com/ome/bioformats)：Bio Formats是一个独立的Java库，用于读取和写入生命科学图像文件格式，由开放显微镜环境联盟开发。
* [OME](https://github.com/ome/openmicroscopy)：OME致力于开发用于存储和处理生物光学显微镜数据的开源软件和数据格式标准，是欧洲和美国大学、研究机构和行业之间的联合项目。
* [CDK](https://github.com/cdk/cdk)：CDK是一个用于化学信息学和生物信息学的开源Java库。
* [Bio4j](https://github.com/bio4j/bio4j)：Bio4j是一个生物信息学图数据平台，集成了Uniprot KB、Gene Ontology、UniRef、NCBI Taxonomy和Expasy Enzyme DB中的大部分可用数据。
* [BioScala](https://github.com/bioscala/bioscala)：BioScala项目的目标是创建一个可扩展且功能齐全的生物信息学库，该库可在Scala、Java、JRuby、Jython 和Clojure中使用。
* [Jvarkit](https://github.com/lindenb/jvarkit)：用于生物信息学的Java实用程序，由法国南特胸腔研究所开源。
* [InterMine](https://github.com/intermine/intermine)：InterMine是一个强大的开源数据仓库系统，允许用户以最少的努力集成不同的数据源，由剑桥大学开源。
* [Jannovar](https://github.com/charite/jannovar)：Jannovar提供了一个用于VCF文件注释的程序，并通过库API公开其功能，由柏林计算生物学开源。
* [LibSBOLj](https://github.com/SynBioDex/libSBOLj)：LibSBOLj为合成生物学开放语言(SBOL)提供核心Java接口及其实现。
* [Bacting](https://github.com/egonw/bacting)：Bacting是一个基于Bioclipse的化学和生物信息学开源平台，它定义了许多常见的领域对象并包装了常见的功能，提供了一个独立于工具包的、可编写脚本的解决方案来处理生命科学数据。
* [BridgeDb](https://github.com/bridgedb/BridgeDb)：BridgeDb是一个在各种生物数据库和相关资源之间映射标识符的框架，由曼彻斯特大学、马斯特里赫特大学开源。
* [JSBML](https://github.com/sbmlteam/jsbml)：JSBML是一个社区驱动的项目，旨在创建一个免费、开源、纯Java库，用于读取、写入和操作SBML文件和数据流。
* [GloBI](https://github.com/globalbioticinteractions/globalbioticinteractions)：GloBI提供对现有物种相互作用数据集的访问。
* [LibLevenshtein](https://github.com/universal-automata/liblevenshtein-java)：有关Levenshtein传感器的各种实用程序。
* [JNBIS](https://github.com/mhshams/jnbis)：JNBIS是一个用Java编写的库，用于提取和解码NIST(美国国家标准与技术研究所)压缩文件和WSQ(小波标量量化)图像。
* [BioData](https://github.com/opencb/biodata)：BioData是一个Java库，它以生物信息学中常用的不同文件格式对生物实体及其等价物进行建模，由剑桥大学计算生物学开源。
* [MSDK](https://github.com/msdk/msdk)：MSDK是一个用于处理质谱数据的Java算法库。
* [Jstacs](https://github.com/Jstacs/Jstacs)：Jstacs包含序列数据的有效表示，并提供了多种统计模型的实现，由马丁路德大学哈勒维滕贝格分校开源。

#### 生物工具

* [QuPath](https://github.com/qupath/qupath)：QuPath是用于生物图像分析的开源软件，由英国女王大学开源。
* [AliView](https://github.com/AliView/AliView)：AliView是用于对齐、查看和编辑DNA/氨基酸序列的软件，由乌普萨拉大学开源。
* [SIRIUS](https://github.com/sirius-ms/sirius)：SIRIUS是一个基于Java的软件框架，用于分析代谢物和其他生物相关小分子的液相色谱串联质谱(LC-MS/MS)数据，由耶拿大学开源。
* [PathVisio](https://github.com/PathVisio/pathvisio)：PathVisio是一款免费的开源通路分析和绘图软件，可以绘制、编辑和分析生物通路，由马斯特里赫特大学和格莱斯顿研究所开发。
* [Tetrad](https://github.com/cmu-phil/tetrad)：Tetrad是一款拥有30年历史的免费工具，用于分析因果系统，根据已知的数据和因果操作推断“什么导致什么”，由CMU大学哲学系开发。
* [DeconvolutionLab2](https://github.com/Biomedical-Imaging-Group/DeconvolutionLab2)：DeconvolutionLab2是开源的3D反卷积显微镜，由洛桑联邦理工学院开源。
* [MesquiteCore](https://github.com/MesquiteProject/MesquiteCore)：Mesquite是一款模块化、可扩展的进化生物学软件，旨在帮助生物学家组织和分析有关生物体的比较数据。
* [Bioclipse](https://www.bioclipse.net/)：Bioclipse项目是一个基于Java的开源可视化化学和生物信息学平台，由瑞典乌普萨拉大学、欧洲生物信息学研究所以及莱顿大学合作开发。
* [Eclipse ChemClipse](https://github.com/eclipse/chemclipse)：Eclipse ChemClipse项目提供化学信息学和生物信息学领域的数据读取和处理功能，由Eclipse科学工作组开源。
* [Icy](https://gitlab.pasteur.fr/bia/icy)：Icy是一款图像分析软件，主要面向生物图像的分析，由巴斯德研究所开源。
* [OpenChrom](https://github.com/Openchrom/openchrom)：OpenChrom是Lablicate GmbH开发的一款用于分析和可视化质谱和色谱数据的开源工具。
* [Caleydo](https://github.com/Caleydo/caleydo)：Caleydo是一个分子生物学数据可视化框架，旨在分析多个异构但相关的表格数据集、这些数据集中的分层或聚类及其与生物学通路的关系，由格拉茨技术大学。
* [MZmine 3](https://github.com/mzmine/mzmine3)：MZmine是一款用于质谱数据处理的开源软件，由芬兰VTT技术研究中心、图尔库生物技术中心开源。
* [Mastodon](https://github.com/mastodon-sc/mastodon)：Mastodon是一个用于大型多视图图像的大规模跟踪和轨迹编辑框架。
* [Micro Manager](https://github.com/micro-manager/micro-manager)：Micro Manager是一个控制显微镜硬件的应用程序，由加利福尼亚大学旧金山分校开源。
* [VCell](https://github.com/virtualcell/vcell)：VCell是一个全面的细胞生物学建模和模拟框架，涵盖从生物通路到细胞生物物理学的各个方面，由康涅狄格大学开源。
* [RNArtist](https://github.com/fjossinet/RNArtist)：RNArtist是构建和管理RNA二维结构集合的交互式工具。
* [FastQC](https://github.com/s-andrews/FastQC)：FastQC是一个旨在发现高通量测序数据集中潜在问题的程序，由巴布拉汉姆研究所生物信息学小组开源。
* [IGV](https://github.com/igvteam/igv)：IGV是适用于Mac、Windows和Linux的桌面基因组可视化工具，由加州大学圣地亚哥分校、麻省理工学院和哈佛大学开源。
* [Tablet](https://github.com/cropgeeks/tablet)：Tablet是一款轻量级、高性能的图形查看器，用于下一代序列组装和比对，由詹姆斯赫顿研究所开源。
* [Juicebox](https://github.com/aidenlab/Juicebox)：Juicebox是一款Hi-C数据可视化软件，由贝勒医学院开源。
* [BioTapestry](https://biotapestry.systemsbiology.net/)：BioTapestry是一种交互式工具，用于通过网络构建、可视化和共享基因调控网络模型，由西雅图系统生物学研究所与加州理工学院戴维森实验室合作创建。
* [Cytoscape](https://cytoscape.org/)：Cytoscape是一个开源的生物信息学软件平台，用于可视化分子相互作用网络并与基因表达谱和其他状态数据集成，最初由西雅图系统生物学研究所开发。
* [FragPipe](https://github.com/Nesvilab/FragPipe)：FragPipe是一个Java GUI，用于一套计算工具，可对基于质谱的蛋白质组数据进行全面分析，由密歇根大学开源。
* [Osprey](https://github.com/donaldlab/OSPREY3)：OSPREY软件包提供了蛋白质设计工具，这是连续灵活性建模、集成建模和具有可证明保证的算法的独特组合，由杜克大学开源。
* [PeptideShaker](https://github.com/compomics/peptide-shaker)：PeptideShaker是一个独立于搜索引擎的平台，用于解释来自多个搜索和de novo引擎的蛋白质组学鉴定结果，由根特大学开源。
* [SearchGUI](https://github.com/compomics/searchgui)：SearchGUI是一个高度适应性的开源通用界面，用于配置和运行蛋白质组学搜索和de novo引擎，由根特大学开源。
* [BioMedICUS](https://github.com/nlpie/biomedicus)：BioMedICUS是一个用于生物医学和临床报告的大规模文本分析和处理的系统，由明尼苏达大学开发。
* [MPI Bioinformatics Toolkit](https://github.com/proteinevolution/Toolkit)：MPI生物信息学工具包是一个集成了多种蛋白质序列分析工具的平台，由图宾根马克斯普朗克生物研究所开源。
* [PharmCAT](https://github.com/PharmGKB/PharmCAT)：PharmCAT是一种生物信息学工具，可分析基因变异以预测药物反应并根据个体患者的基因图谱定制医疗方案，由斯坦福大学和宾夕法尼亚大学维护。
* [Apollo](https://github.com/GMOD/Apollo)：Apollo是一个基于Web的协作、实时基因组注释编辑器。
* [Exomiser](https://github.com/exomiser/Exomiser)：Exomiser是一个Java程序，可以从全外显子组或全基因组测序数据中查找潜在的致病变异，由柏林夏里特大学、桑格研究所开发。
* [IRIDA](https://github.com/phac-nml/irida)：IRIDA是加拿大基因组流行病学综合快速传染病分析平台。
* [Wildbook](https://github.com/WildMeOrg/Wildbook)：Wildbook是一个开源软件框架，支持标记重新捕获、分子生态学和社会生态学研究。
* [GeneMANIA](https://github.com/GeneMANIA/genemania)：GeneMANIA可以帮助你预测你最喜欢的基因和基因组的功能，由多伦多大学开源。
* [MOLGENIS](https://github.com/molgenis/molgenis)：MOLGENIS是一个协作开源项目，其目的是为生命科学研究生成出色的软件基础设施，由格罗宁根大学开源。
* [Opal](https://github.com/obiba/opal)：Opal是OBiBa用于生物样本库或流行病学研究的核心数据库应用程序。
* [GBIF IPT](https://github.com/gbif/ipt)：IPT是由全球生物多样性信息设施(GBIF)提供的免费开源软件工具，用于通过GBIF网络发布和共享生物多样性数据集。
* [Picard](https://github.com/broadinstitute/picard)：Picard是一组用于操作高通量测序(HTS)数据以及SAM/BAM/CRAM和VCF等格式的命令行工具，由麻省理工学院和哈佛大学布罗德研究所开源。
* [BBMap](https://github.com/BioInfoTools/BBMap)：用于DNA/RNAseq的BBMap短读对齐器和其他生物信息学工具，由加州大学伯克利分校开源。
* [Bpipe](https://github.com/ssadedin/bpipe)：Bpipe提供了一个运行数据分析工作流的平台。
* [VDJtools](https://github.com/mikessh/vdjtools)：VDJtools是一个基于Java/Groovy的开源框架，旨在简化免疫组库测序(RepSeq)数据的分析。
* [MinCED](https://github.com/ctSkennerton/minced)：MinCED是一款用于在全基因组或环境数据集中查找成簇的规律间隔短回文重复序列的程序。
* [DNAnalyzer](https://github.com/VerisimilitudeX/DNAnalyzer)：致力于彻底改变DNA分析领域，目标是使DNA分析工具的使用更加民主化。
* [GRIDSS](https://github.com/PapenfussLab/gridss)：GRIDSS是一个模块软件套件，包含可用于检测基因组重排的工具，由沃尔特和伊丽莎·霍尔医学研究所开源。
* [Artemis](https://github.com/sanger-pathogens/Artemis)：Artemis软件是一套用于基因组浏览和注释的软件工具，由威康桑格研究所开源。
* [P2Rank](https://github.com/rdk/p2rank)：P2Rank是一个独立的命令行程序，可以根据蛋白质结构快速准确地预测配体结合位点。
* [GORpipe](https://github.com/gorpipe/gor)：GORpipe是一种基于基因组有序关系架构的工具，允许在并行执行引擎中使用声明性查询语言分析大量基因组和表型表格数据，由Genuity Science开发。
* [SnpEff](https://github.com/pcingola/SnpEff)：基因组变异注释和功能效果预测工具包。
* [NGSEP](https://github.com/NGSEP/NGSEPcore)：NGSEP提供了一个对象模型来支持不同类型的DNA高通量测序(HTS)数据分析。
* [PIA](https://github.com/medbioinf/pia)：PIA是一个用于基于MS的蛋白质推断和识别分析的工具箱，由波鸿鲁尔大学开源。
* [ASTRAL](https://github.com/smirarab/ASTRAL)：ASTRAL是一个用于在给定一组无根基因树的情况下估算无根物种树的工具。
* [BioFormats2Raw](https://github.com/glencoesoftware/bioformats2raw)：Bio Formats图像文件格式到原始格式转换器。

#### 生物工作流

* [Nextflow](https://github.com/nextflow-io/nextflow)：Nextflow是一个工作流程系统，用于创建可扩展、可移植和可重复的工作流程，由西班牙巴塞罗那的生物医学和基因组学研究中心CRG开发。
* [Pegasus](https://github.com/pegasus-isi/pegasus)：Pegasus是一个可配置系统，用于在各种计算基础设施上映射和执行科学工作流程，由南加州大学信息科学研究所、威斯康星大学麦迪逊分校开源。
* [Cromwell](https://github.com/broadinstitute/cromwell)：Cromwell是一个用于生物信息学的开源工作流程管理系统，由麻省理工学院和哈佛大学布罗德研究所开源。
* [OpenMOLE](https://github.com/openmole/openmole)：OpenMOLE提供了利用分布式计算环境来运行、探索、诊断和优化数值模型的工具，由法国国家科学研究院开源。
* [Dockstore](https://github.com/dockstore/dockstore)：Dockstore是一个免费的开源平台，用于共享可重用且可扩展的分析工具和工作流程，由癌症基因组合作实验室开源。
* [WDL](https://github.com/openwdl/wdl)：WDL是一种开放标准，用于使用人类可读和可写的语法来描述数据处理工作流，最初由布罗德研究所开发。

#### 基因组

* [cBioPortal](https://github.com/cBioPortal/cbioportal)：cBioPortal提供大规模癌症基因组学数据集的可视化、分析和下载，由纪念斯隆-凯特琳癌症中心、丹娜法伯癌症研究院、毕尔肯大学、多伦多玛格丽特公主癌症中心等组织开源。
* [Compomics Utilities](https://github.com/compomics/compomics-utilities)：用于计算蛋白质组学的开源Java库，由根特大学开源。
* [GKL](https://github.com/Intel-HLS/GKL)：GKL包含GATK和HTSJDK等基因组学应用程序中使用的计算内核的优化版本，由Intel开源。
* [ADAM](https://github.com/bigdatagenomics/adam)：ADAM是一个库和命令行工具，支持使用Spark跨集群/云计算环境并行进行基因组数据分析，由加州大学伯克利分校、西奈山伊坎医学院、微软研究院等开源。
* [FUNGA](https://github.com/bxx2004/FUNGA)：FUNGA是一个利用人工智能技术挖掘基因功能的平台。
* [OpenCGA](https://github.com/opencb/opencga)：OpenCGA是一个开源项目，旨在为数百TB甚至PB级的基因组规模数据分析提供大数据存储引擎和分析框架，由剑桥大学计算生物学开源。
* [HMFTools](https://github.com/hartwigmedical/hmftools)：该存储库包含全基因组、靶向DNA和全转录组分析流程中使用的工具套件，WiGiTS是一套通用的开源基因组和转录组分析工具，用于癌症研究和诊断，由哈特维格医学基金会开源。
* [Drop-seq](https://github.com/broadinstitute/Drop-seq)：用于分析Drop-seq数据的Java和R工具，由麻省理工学院和哈佛大学布罗德研究所开源。
* [InterProScan](https://github.com/ebi-pf-team/interproscan)：InterPro通过将蛋白质归类为家族并预测域和重要位点来提供蛋白质的功能分析，由欧洲分子生物学实验室开源。
* [Cloud Pipeline](https://github.com/epam/cloud-pipeline)：与云无关的基因组学分析、科学计算和存储平台，由EPAM开源。
* [Cellbase](https://github.com/opencb/cellbase)：Cellbase是一个集中式数据库，集成了来自多个主要基因组和生物数据库的大量信息，用于基因组注释和临床变异优先级排序，由剑桥大学计算生物学开源。
* [VarSim](https://github.com/bioinform/varsim)：VarSim是用于癌症应用的高通量基因组测序的高保真模拟验证框架，由罗氏开源。
* [Glow](https://github.com/projectglow/glow)：Glow是一个开源工具包，用于实现生物库规模及更大范围的生物信息学，由Regeneron开发。
* [GEDCOM X Java](https://github.com/FamilySearch/gedcomx-java)：该项目托管GEDCOM X项目的Java实现，并作为GEDCOM X的参考实现，由FamilySearch开源。
* [Systems Genetics](https://github.com/molgenis/systemsgenetics)：通用Java基因型读取器/写入器、QTL映射软件、链比对工具，由格罗宁根大学开源。

#### NGS

* [GATK](https://github.com/broadinstitute/gatk)：由麻省理工学院和哈佛大学布罗德研究所开源的下一代基因组分析工具包。
* [MiXCR](https://github.com/milaboratory/mixcr)：MiXCR是一款通用软件，可快速准确地分析原始T细胞或B细胞受体组测序数据。
* [FgBio](https://github.com/fulcrumgenomics/fgbio)：FgBio是一个用于处理基因组数据尤其是下一代测序数据的命令行工具包。
* [HTSJDK](https://github.com/samtools/htsjdk)：HTSJDK是统一Java库的实现，用于访问用于高通量测序数据的常见文件格式，例如SAM和VCF，由哈佛医学院开源。
* [MISO](https://github.com/miso-lims/miso-lims)：MISO是一个开源实验室信息管理系统(LIMS)，始于厄勒姆研究所，专门用于跟踪下一代测序实验。
* [NGB](https://github.com/epam/NGB)：NGB是一种基于Web的NGS数据查看器，具有独特的结构变异(SV)可视化功能、高性能、可扩展性和云数据支持，由EPAM开源。
* [Eoulsan](https://github.com/GenomiqueENS/eoulsan)：Eoulsan是一个基于MapReduce算法的Hadoop实现的多功能框架，致力于分布式计算机上的高吞吐量测序数据分析，由巴黎高等师范学院生物研究所开源。
* [AdamaJava](https://github.com/AdamaJava/adamajava)：AdamaJava包含与新一代测序(NGS)分析相关的变异调用程序和流程工具的代码，由昆士兰医学研究院伯格霍夫医学研究所的基因组信息学小组开发和维护。
* [Trimmomatic](https://github.com/usadellab/Trimmomatic)：由Usadel实验室开发的基于Java的Illumina NGS测序数据处理和修剪工具，能够处理单端和双端读取。

## 化学库

* [CDK](https://github.com/cdk/cdk)：CDK是一个用于化学信息学和生物信息学的开源Java库。
* [Eclipse ChemClipse](https://github.com/eclipse/chemclipse)：Eclipse ChemClipse项目提供化学信息学和生物信息学领域的数据读取和处理功能，由Eclipse科学工作组开源。
* [JChemPaint](https://github.com/JChemPaint/jchempaint)：JChemPaint是使用CDK开发的2D化学结构编辑器和查看器。
* [OpenChemLib](https://github.com/Actelion/openchemlib)：OpenChemLib是基于Java的框架，提供化学信息学核心功能和用户界面组件。
* [ChemicalTagger](https://github.com/BlueObelisk/chemicaltagger)：ChemicalTagger是化学领域语义文本挖掘的工具。
* [JMol](https://github.com/BobHanson/Jmol-SwingJS)：JMol是一个开源Java/SwingJS应用程序，用于可视化和分析具有化学品特征的3D分子结构、晶体、材料和生物分子。
* [SMSD](https://github.com/asad/smsd)：SMSD是一个基于Java的软件库，用于查找小分子之间的最大公共子图(MCS)/子结构，由欧洲生物信息学研究所开源。
* [MORTAR](https://github.com/FelixBaensch/MORTAR)：MORTAR是一款免费的开源图形桌面应用程序，支持分子计算机碎片化和子结构分析，由德国威斯特伐利亚应用技术大学开源。
* [Indigo](https://github.com/epam/Indigo)：通用化学信息学工具包、实用程序和数据库搜索工具。
* [LaMa4J](https://lama4j.di.unimi.it/)：LaMa4J是一组实现许多晶格和晶格运算的Java类。
* [Toxtree](https://toxtree.sourceforge.net/)：Toxtree是一个功能齐全、灵活、用户友好的开源应用程序，它能够通过应用决策树方法来估计毒性危害。
* [OPSIN](https://github.com/dan2097/opsin)：OPSIN是一个用于IUPAC名称到结构转换的Java库，可为有机化学命名法提供高召回率和精确度，由剑桥大学化学系开源。
* [MolVec](https://github.com/ncats/molvec)：NCATS(化学) OCR引擎，可以将化学图像矢量化为化学对象，并尽可能保留2D布局，由国家转化科学促进中心开源。
* [AMBIT](https://ambit.sourceforge.net/)：AMBIT为化学物质、结构和纳米材料提供化学信息学数据管理。
* [DataWarrior](https://github.com/thsa/datawarrior)：DataWarrior是一个用于交互式数据分析和可视化的程序。
* [Patent Reaction Extractor](https://github.com/dan2097/patent-reaction-extraction)：化学反应的文本挖掘，由剑桥大学开源。
* [DENOPTIM](https://github.com/denoptim-project/DENOPTIM)：DENOPTIM是一款用于功能化合物从头设计和虚拟筛选的软件。

## 心理测量学

* [Psychometrics](https://github.com/meyerjp3/psychometrics)：一个用于心理测量分析的Java库。
* [jMetrik](https://itemanalysis.com/jmetrik-download)：jMetrik是一款免费开源的心理测量软件。

## 网络爬虫

这里列出来网络爬虫相关的库、软件、工具。

#### 爬虫库

* [Crawler4j](https://github.com/yasserg/crawler4j)：Crawler4j是一个开源的Java网络爬虫库，它提供了一个用于爬虫的简单界面，由加州大学欧文分校开源。
* [Apache Nutch](https://github.com/apache/nutch)：Nutch是一个高度可扩展、成熟、可用于生产的网络爬虫，它支持细粒度配置并适应各种数据采集任务。
* [Jsoup](https://github.com/jhy/jsoup)：Jsoup是一个Java HTML解析器，专为HTML编辑、清理、抓取和XSS安全而构建。
* [Salyut](https://github.com/taofen8/salyut)：Salyut是基于标记语言的开源爬虫框架，由淘粉吧开源。
* [StormCrawler](https://github.com/DigitalPebble/storm-crawler)：StormCrawler是一个开源框架，用于在Storm上构建低延迟、可扩展的网络爬虫。
* [Sparkler](https://github.com/USCDataScience/sparkler)：Sparkler是在Spark上运行的类似Nutch的爬虫库，由南加州大学开源。
* [WebMagic](https://github.com/code4craft/webmagic)：WebMagic是一个简单灵活的Java爬虫框架。
* [Venom](https://github.com/PreferredAI/venom)：Venom是一个速度极快、完全可定制、功能强大且简单易用的爬虫，由PreferredAI开发。
* [HtmlUnit](https://github.com/HtmlUnit/htmlunit)：HtmlUnit是Java程序的无GUI浏览器。
* [Gecco](https://github.com/xtuhcy/gecco)：Gecco集成了Jsoup、HttpClient、FastJson、Spring、HtmlUnit、Redission框架，让你只需要配置一些JQuery风格的选择器就可以非常快速的编写一个爬虫。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler)：SeimiCrawler是一个敏捷、独立部署、支持分布式的Java爬虫框架。
* [NewPipe Extractor](https://github.com/TeamNewPipe/NewPipeExtractor)：NewPipe Extractor是一个用于从流媒体站点中提取内容的库。
* [Apache ManifoldCF](https://github.com/apache/manifoldcf)：ManifoldCF是一个多仓库爬虫框架，具有多个连接器。
* [WebCollector](https://github.com/CrawlScript/WebCollector)：WebCollector是一个基于Java的开源网络爬虫框架，它提供了一些简单的网络爬虫接口，由合肥工业大学开源。
* [XXL-Crawler](https://github.com/xuxueli/xxl-crawler)：XXL-Crawler是一个分布式爬虫框架。
* [Jvppeteer](https://github.com/fanyong920/jvppeteer)：Jvppeteer通过DevTools and WebDriver-bidi控制Chrome或Firefox。
* [NetDiscovery](https://github.com/fengzhizi715/NetDiscovery)：NetDiscovery是一款基于Vert.x、RxJava 2等框架实现的通用爬虫框架/中间件。
* [Spiderman](https://gitee.com/l-weiwei/spiderman)：Spiderman是一个垂直领域的爬虫，可用于抓取特定目标网页的内容，并且解析为所需要的业务数据，整个过程追求无需任何编码就能实现。
* [MongooCrawler](https://gitee.com/coliza/MongooCrawler)：MongooCrawler是一款低入侵分布式爬虫框架，仅仅依赖少量第三方包，具有多进程多线程，集成反爬、验证码破解方案等特性。
* [XueQiuSuperSpider](https://github.com/decaywood/XueQiuSuperSpider)：雪球超级爬虫是基于雪球网、东方财富和同花顺实现的股票数据爬虫程序。
* [Crawljax](https://github.com/crawljax/crawljax)：Crawljax是一个自动爬取和测试现代Web应用程序的工具。
* [Spiderman2](https://gitee.com/l-weiwei/Spiderman2)：Spiderman的升级版，在性能、架构、易用性上有提升，支持分布式。
* [Jaunt](https://jaunt-api.com/)：Jaunt是一个用于Web抓取、Web自动化和JSON查询的Java库。
* [Jauntium](https://jauntium.com/)：Jauntium是一个新的免费Java库，可让你轻松自动化Chrome、Firefox、Safari、Edge、IE和其他现代Web浏览器。
* [Crawler Commons](https://github.com/crawler-commons/crawler-commons)：Crawler Commons是一组可重用的Java组件，可实现任何网络爬虫的通用功能。
* [Norconex HTTP Collector](https://github.com/Norconex/crawlers)：Norconex是一个功能齐全的爬虫库，可以操作收集的数据并将其存储到你选择的仓库(例如搜索引擎)中。
* [CrawlerDemon](https://gitee.com/spirit_demon/CrawlerDemon)：基于Akka的高性能分布式爬虫框架。
* [Nokogiri](https://github.com/sparklemotion/nokogiri)：HTML、XML、SAX和Reader解析器，支持XPath和CSS选择器。
* [VSCrawler](https://gitee.com/virjar/vscrawler)：适合抓取封堵的爬虫框架。
* [Crawler](https://github.com/vidageek/crawler)：简单的Java网络爬虫库。
* [Fess Crawler](https://github.com/codelibs/fess-crawler)：Fess Crawler是一个用于爬取网站和文件系统的爬虫库。
* [URL Frontier](https://github.com/crawler-commons/url-frontier)：URL Frontier项目的目标是开发一个爬虫/语言中立的API，用于网络爬虫在与网络前沿通信时执行的操作。
* [Skraper](https://github.com/sokomishalov/skraper)：Kotlin/Java库和CLI工具，用于从各种来源抓取帖子和媒体，无需授权也无需整页渲染。
* [Google Play Crawler Java API](https://github.com/Akdeniz/google-play-crawler)：Google Play Crawler用于在GooglePlay上搜索Android应用程序并下载它们。
* [Elves](https://github.com/hellokaton/elves)：一个轻量级的爬虫框架设计与实现。
* [VIPS](https://github.com/tpopela/vips_java)：用Java实现基于视觉的页面分割算法。
* [Website Crawler](https://github.com/pc8544/Website-Crawler)：Website Crawler API允许开发者通过四个简单端点程序爬取网站并访问结构化元数据。
* [EasyBook](https://github.com/Zzzia/EasyBook)：Java/Android多站点小说爬虫库。

#### HTML提取

* [Goose](https://github.com/GravityLabs/goose)：Goose是一个用Scala编写的文章提取器。
* [Crux](https://github.com/chimbori/crux)：Crux提供灵活的基于插件的API和实现，用于从网页中提取元数据。
* [Snacktory](https://github.com/karussell/snacktory)：Java的Readability克隆。
* [JReadability](https://github.com/wuman/JReadability)：JReadability是一个Java库，它将HTML作为输入进行解析并返回干净、易读的文本。
* [Readability4J](https://github.com/dankito/Readability4J)：Readability4J是Mozilla的Readability.js的Kotlin端口。
* [Java Readability](https://github.com/basis-technology-corp/Java-readability)：Readability包的Java移植。
* [ReadabilityBundle](https://github.com/srijiths/readabilityBUNDLE)：用Java编写的HTML主内容提取工具。
* [Skrapt](https://github.com/skrapeit/skrape.it)：Skrape是一个基于Kotlin的HTML/XML测试和Web抓取库。
* [HtmlCleaner](https://htmlcleaner.sourceforge.net/)：HtmlCleaner是一个用Java编写的开源HTML解析器。
* [HtmlExtractor](https://github.com/ysc/HtmlExtractor)：HtmlExtractor是一个Java实现的基于模板的网页结构化信息精准抽取组件。
* [Essence](https://github.com/cdimascio/essence)：Kotlin和Java的自动网页内容提取器。
* [ContentExtractor](https://github.com/hfut-dmic/ContentExtractor)：ContentExtractor是一个开源的网页正文抽取工具，具有非常高的抽取精度，由合肥工业大学开源。

#### 爬虫平台

* [SpiderFlow](https://github.com/ssssssss-team/spider-flow)：SpiderFlow是新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫。
* [Heritrix](https://github.com/internetarchive/heritrix3)：Heritrix是互联网档案馆的开源、可扩展、网络规模、档案质量的网络爬虫项目。
* [TemplateSpider](https://gitee.com/mail_osc/templatespider)：TemplateSpider是一款用于从各种网站收集模板的开源工具。
* [FSCrawler](https://github.com/dadoonet/fscrawler)：该爬虫有助于索引二进制文档，例如PDF、Open Office、MS Office。
* [PulsarRPA](https://github.com/platonai/PulsarRPA)：PulsarRPA是一个高性能、分布式、开源的机器人流程自动化(RPA)框架。
* [GitHub Crawler](https://github.com/societe-generale/github-crawler)：Github Crawler旨在通过GitHub API爬取组织的仓库，从而实现信息收集的自动化，由法国兴业银行开源。
* [Anthelion](https://github.com/YahooArchive/anthelion)：Anthelion是Nutch的一个插件，用于抓取HTML页面中的语义注释，由Yahoo开源。
* [ACHE](https://github.com/VIDA-NYU/ache)：ACHE是一个专注的网络爬虫，它收集满足某些特定标准的网页，例如属于给定域或包含用户指定模式的页面，由纽约大学开源。
* [Kspider](https://github.com/kkangert/kspider)：Kspider是一个爬虫平台，以图形化方式定义爬虫流程，无需代码即可实现一个爬虫流程。
* [YayCrawler](https://gitee.com/shentong_012/YayCrawler)：YayCrawler是一个分布式爬虫系统，使用简单，高级配置。
* [NewCrawler](https://github.com/speed/newcrawler)：鸟巢采集器是一款Web版的网页数据采集工具，拥有强大的内容采集和数据过滤功能，能将你采集的数据发布到远程服务器。
* [Phoneutria](https://sourceforge.net/projects/phoneutria/)：可用于对任何Web或企业网站进行爬取和索引，并且可通过XML配置文件进行配置。
* [ISpider](https://github.com/xpleaf/ispider)：由Java设计的分布式爬虫系统。

#### Youtube爬取

* [Java Youtube Downloader](https://github.com/sealedtx/java-youtube-downloader)：用于检索Youtube视频元数据的简单Java解析器。
* [YoutubeJExtractor](https://github.com/antonyhaman/youtube-jextractor)：YoutubeJExtractor是Android提取器库，允许从任何YouTube视频中提取视频和音频以及一些其他数据，例如视频标题、描述、作者、缩略图等。
* [YouTube Scraper](https://github.com/oxylabs/youtube-scraper)：YouTube Scraper可以轻松无阻地收集公开的YouTube数据。
* [YoutubeDl Java](https://github.com/sapher/youtubedl-java)：YoutubeDl可执行文件的简单Java包装器。
* [GDownloader](https://github.com/hstr0100/GDownloader)：GDownloader是用Java编写的Yt Dlp、Gallery Dl和SpotDL用户友好的GUI。
* [JavaTube](https://github.com/felipeucelli/JavaTube)：JavaTube是一个基于pytube库的YouTube视频下载库。
* [YouTube Comment Suite](https://github.com/mattwright324/youtube-comment-suite)：YouTube Comment Suite可让你汇总来自众多视频、播放列表和频道的YouTube评论，以便存档、常规搜索和显示活动。
* [MediaServiceCore](https://github.com/yuliskov/MediaServiceCore)：YouTube的非官方Java API。

## 工作流

* [Camunda](https://github.com/camunda/camunda-bpm-platform)：Camunda Platform是一个灵活的工作流程和流程自动化框架，其核心是在JVM内运行的原生BPMN 2.0流程引擎。
* [Activiti](https://github.com/Activiti/Activiti)：Activiti是一个轻量级工作流程和BPM平台，面向业务人员、开发人员和系统管理员，由Alfresco开源。
* [Flowable](https://github.com/flowable/flowable-engine)：Flowable为开发人员、系统管理员和业务用户提供紧凑且高效的工作流程和BPM平台。
* [jBPM](https://github.com/kiegroup/jbpm)：jBPM是一个用于构建业务应用程序以帮助自动化业务流程和决策的工具包，JBoss社区开源。
* [jDMN](https://github.com/goldmansachs/jdmn)：jDMN为DMN中指定的决策模型提供执行引擎，这些决策可以解释或翻译为Java并在JVM上执行，由高盛银行开源。
* [DBOS](https://github.com/dbos-inc/dbos-transact-java)：DBOS提供轻量级、持久耐用且由Postgres支持的工作流。
* [JDEasyFlow](https://github.com/JDEasyFlow/jd-easyflow)：JDEasyFlow是京东开源的一个通用流程编排组件，适用于服务编排、工作流、审计等，具有易用、灵活、易扩展的特点。
* [ActiveMatrix BPM](https://docs.tibco.com/products/tibco-activematrix-bpm-4-3-0)：TIBCO ActiveMatrix BPM用于开发、部署、执行和管理以业务流程管理为中心的应用程序。
* [Piper](https://github.com/runabol/piper)：Piper是一个基于Spring Boot构建的开源分布式工作流引擎，设计非常简单。
* [Maestro](https://github.com/lucidity-labs/maestro)：Maestro是一个简单但功能强大、持久的工作流库。
* [ByteChef](https://github.com/bytechefhq/bytechef)：ByteChef是一个开源、低代码、可扩展的API集成和工作流自动化平台。
* [Infinitic](https://github.com/infiniticio/infinitic)：Infinitic是一个开源框架，使应用程序团队能够构建、测试和发布可用于生产的工作流程，而无需配置或管理后端工具。
* [Compileflow](https://github.com/alibaba/compileflow)：Compileflow是一个非常轻量级、高性能、可集成和可扩展的流程引擎，由阿里开源。
* [Temporal Java SDK](https://github.com/temporalio/sdk-java)：Temporal提供了一个开源的持久执行平台，抽象化了构建可扩展、可靠分布式系统的复杂性，由Uber开源。
* [Azkaban](https://github.com/azkaban/azkaban)：Azkaban是LinkedIn创建的批处理工作流作业调度程序，用于运行Hadoop作业。
* [Apromore](https://github.com/apromore/ApromoreCore)：Apromore用于流程挖掘和预测流程分析，由墨尔本大学、塔尔图大学等开源。
* [Turbo](https://github.com/didi/turbo)：Turbo是一款轻量级流程引擎服务框架，可作为底层服务支持各类流程设计、低代码设计、工作流、服务编排等场景，由滴滴开源。
* [Amazon SWF](https://aws.amazon.com/swf)：Amazon SWF可帮助开发人员构建、运行和扩展具有并行或连续步骤的后台作业。
* [JEHC BPM](https://gitee.com/jehc/JEHC-BPM)：JEHC BPM是小诗科技公司研发的一套开源工作流平台。
* [Kogito](https://github.com/apache/incubator-kie-kogito-runtimes)：Kogito是专注于云原生开发、部署和执行的下一代业务自动化平台，由RedHat开源。
* [OpenBPM](https://openbpm.io/)：OpenBPM是一个面向软件工程师的开源业务流程自动化平台。
* [Bulbasaur](https://github.com/alibaba/bulbasaur)：Bulbasaur是阿里开源的可插拔精简流程引擎，可快速实现流程、审批、业务失败重试等场景。
* [Imixs Workflow](https://github.com/imixs/imixs-workflow)：Imixs Workflow是一个开源工作流引擎，用于在灵活而强大的框架上构建以人为中心的工作流应用程序。
* [Bonita](https://github.com/bonitasoft/bonita-engine)：部署、执行、管理使用Bonita Studio或通过Engine API制作的基于流程的应用程序。
* [JFlow](https://gitee.com/opencc/JFlow)：基于AI的低代码BPM开发平台，由济南驰骋公司开发。
* [WINGS](https://github.com/KnowledgeCaptureAndDiscovery/wings)：WINGS是一个语义工作流系统，可帮助科学家设计计算实验，由南加州大学开源。
* [BAMOE](https://github.com/IBM/bamoe)：IBM BAMOE是用于工作流和决策管理的企业自动化软件。
* [TFlow](https://gitee.com/bestfeng/oa_git_free)：行云流程引擎具备Activiti的常用功能，上手更容易。
* [Emissary](https://github.com/NationalSecurityAgency/emissary)：Emissary是一种基于P2P的数据驱动工作流引擎，运行在异构的、可能广泛分散的多层P2P计算资源网络中，由美国国家安全局开源。
* [Digdag](https://github.com/treasure-data/digdag)：Digdag是一款简单的工具，可帮助你构建、运行、调度和监控复杂的任务流水线。
* [AgileBPM](https://gitee.com/agile-bpm/agile-bpm-basic)：快速、简洁且强大的低代码流程开发平台，国产开源。
* [Schedulis](https://github.com/WeBankFinTech/Schedulis)：Schedulis是一个基于LinkedIn的开源项目Azkaban开发的工作流任务调度系统，由微众开源。
* [UFLO2](https://github.com/youseries/uflo)：UFLO是一款基于Spring的纯Java流程引擎，支持并行、动态并行、串行、会签等各种流转方式。
* [NFlow](https://github.com/NitorCreations/nflow)：NFlow是一种经过验证的用于编排业务流程的解决方案，它可以用作微服务编排器(Saga模式)、业务流程引擎或持久有限状态机。
* [WFlow](http://wflow.willianfu.top/)：WFlow工作流是一个简单易用，面向普通用户的工作流系统。
* [FlowLong](https://gitee.com/aizuda/flowlong)：由爱组搭开源的工作流引擎
* [Concord](https://github.com/walmartlabs/concord)：Concord是一个工作流服务器，它是使用用户创建的场景和插件将不同系统连接在一起的编排引擎，由沃尔玛开源。
* [DataBuilder](https://github.com/flipkart-incubator/databuilderframework)：DataBuilder框架是一个高级逻辑执行引擎，可用于执行多步骤工作流，该引擎目前为Flipkart的结账系统以及诊断和其他工作流提供支持。
* [RuoYi Activiti](https://gitee.com/shenzhanwang/RuoYi-activiti)：基于Activiti 6.0，集流程设计、流程部署、流程执行、任务办理、流程监控于一体的开源工作流开发平台。
* [RuoYi Flowable](https://gitee.com/tony2y/RuoYi-flowable)：基于RuoYi Vue、Flowable 6.8.x的工作流管理平台。
* [RuoYi Vue Activiti](https://gitee.com/smell2/ruoyi-vue-activiti)：前端采用Vue、Element UI，后端采用Spring Boot、Spring Security的前后端分离工作流脚手架。
* [Yaoqiang BPMN Editor](https://bpmn.sourceforge.net/)：Yaoqiang BPMN Editor是一款开源的业务流程图图形编辑器，符合OMG规范(BPMN 2.0)。
* [F2BPM](https://www.f2bpm.com/)：F2BPM是一款纯国产工作流引擎，遵循WFMC/BPMN2.0的规范，由致博软件公司开发。
* [盘古BPM](https://gitee.com/pangu-dm/pangubpm-dmn)：盘古BPM工作流平台是国内首款开源的互联网决策引擎系统，拥有独立的DMN1.3标准设计器、解析器、决策引擎、支持决策表、DRD、DRG。
* [Y9 WorkFlow](https://github.com/risesoft-y9/WorkFlow-Engine)：基于Spring Boot、Vue前后端分离的Java国产信创工作流引擎，由北京有生博大软件开发。
* [JsonFlow](https://gitee.com/jackrolling/jsonflow-ui)：JsonFlow工作流是一个100%纯国产自研的分布式流程引擎系统。
* [Smart Flow](https://gitee.com/smartboot/smart-flow)：SmartFlow是一个轻量、灵活的业务流程编排框架，支持业务流程中常见的条件分支控制、子流程、业务组件异步和降级等功能。
* [COPPER](https://github.com/copper-engine/copper-engine)：COPPER是一个开源、强大、轻量且易于配置的工作流引擎，它使用Java作为工作流的描述语言。
* [FlyFlow](https://gitee.com/junyue/flyflow)：FlyFlow借鉴了钉钉与飞书的界面设计理念，致力于打造一款用户友好、快速上手的工作流程工具。
* [Easy Flows](https://github.com/j-easy/easy-flows)：Easy Flows是Java的工作流引擎，它提供简单的API和构建块，使创建和运行可组合工作流程变得轻松。
* [FoxBPM](https://github.com/FoxBPM/FoxBPM)：FoxBPM是一款开源的基于BPMN 2.0标准的工作流引擎，引擎底层直接支持BPMN 2.0国际标准。
* [Taverna](https://github.com/apache/incubator-taverna-engine)：Taverna是一个用于设计和执行工作流的开源软件工具，最初由曼彻斯特大学创建。
* [Flo](https://github.com/spotify/flo)：Flo是一个轻量级的工作流定义库，由Spotify开发。
* [AntFlow](https://gitee.com/tylerzhou/Antflow)：AntFlow是一款基于Activiti、久经生产环境考验的企业级低代码工作流引擎平台。
* [Workflows4s](https://github.com/business4s/workflows4s)：Scala的简单、可组合、面向业务的工作流库。
* [JWorkflow](https://github.com/danielgerlag/jworkflow)：JWorkflow是一个轻量级的Java工作流库，它支持可插拔的持久性和并发性提供程序，以支持多节点集群。
* [YAWL](https://github.com/yawlfoundation/yawl)：YAWL是一个BPM/工作流系统，基于简洁而强大的建模语言，可处理复杂的数据转换，并与组织资源和外部Web服务完全集成。
* [WarmFlow](https://gitee.com/dromara/warm-flow)：此项目是极其简单的工作流，没有太多设计，代码量少，并且只有6张表，由dromara社区开发。
* [Titanoboa](https://github.com/commsor/titanoboa)：Titanoboa是一个面向JVM的低代码工作流编排平台。
* [WorkfliwSim](https://github.com/WorkflowSim/WorkflowSim-1.0)：WorkflowSim是一个工作流程模拟器，支持大规模调度、集群和配置研究，由南加州大学开源。
* [Automatiko](https://github.com/automatiko-io/automatiko-engine)：Automatiko可以帮助你基于以众所周知的标准表达的工作流程和决策构建更好的服务和功能。
* [Application Engine](https://github.com/netgrif/application-engine)：Application Engine是一个完全支持低代码语言Petriflow的工作流管理系统。
* [Fixflow](https://github.com/fixteam/fixflow)：Fixflow是一款开源的基于BPMN2.0标准的工作流引擎，由北京百特云享公司开发。
* [Operaton](https://github.com/operaton/operaton)：Operaton是一个原生的BPMN 2.0流程引擎，运行在Java虚拟机中。
* [ZephFlow](https://github.com/fleaktech/zephflow-core)：ZephFlow是一个精简的框架，旨在使无状态数据处理变得简单、可靠和高效。
* [EximeeBPMS](https://github.com/EximeeBPMS/eximeebpms)：EximeeBPMS是一个灵活的工作流和流程自动化框架。
* [Captain](https://github.com/LiveRamp/captain)：Captain是一个分布式、轻量级的Java工作流引擎，专为微服务架构而设计。
* [JRoadFlow](https://www.roadflow.cn/)：JRoadFlow是一款集成工作流引擎的Java快速开发框架。
* [MLDong](https://gitee.com/mldong/mldong)：MLDong是基于Spring Boot、Vue 3的快速开发平台、自研工作流引擎。
* [Snaker](https://github.com/snakerflow/snakerflow)：Snaker是一个基于Java的轻量级工作流引擎，适用于企业应用中常见的业务流程。
* [Nirmata Workflow](https://github.com/nirmata/workflow)：Nirmata Workflow是一个基于Java ZooKeeper和Curator的库，支持分布式任务工作流。
* [Neuro4j](https://github.com/eternita/workflow)：Neuro4j是一款轻量级的Java工作流引擎，基于Eclipse开发环境。
* [CIB Seven](https://github.com/cibseven/cibseven)：CIB Seven是一个灵活的工作流和流程自动化框架。
* [Kikwiflow](https://github.com/atoxfy/kikwiflow)：Kikwiflow是一个从零开始构建的流程编排引擎，旨在解决传统平台的长期痛点。
* [Serverless Workflow](https://github.com/serverlessworkflow/sdk-java)：Serverless Workflow是一个开源、供应商中立且社区驱动的项目，它通过其高级DSL重新定义了工作流创建。
* [Quarkus Flow](https://github.com/quarkiverse/quarkus-flow)：Quarkus Flow是一款轻量级、低依赖性、生产级工作流引擎，基于CNCF Serverless Workflow规范构建。
* [Fluxnova](https://github.com/finos/fluxnova-bpm-platform)：Fluxnova是一个灵活的工作流程和流程自动化框架，由金融科技开源基金会FINOS开源。

## 编排引擎

* [Conductor](https://github.com/conductor-oss/conductor)：Conductor是Netflix创建的一个平台，用于编排微服务和事件。
* [Kestra](https://github.com/kestra-io/kestra)：Kestra是一个通用的开源编排器，可以简化计划和事件驱动的工作流程。
* [Apache DolphinScheduler](https://github.com/apache/dolphinscheduler)：DolphinScheduler是现代数据编排平台，以低代码敏捷创建高性能工作流程，由易观开源。
* [Maestro](https://github.com/Netflix/maestro)：Maestro是一款通用工作流编排器，为Netflix的数据平台用户提供完全托管的工作流即服务(WAAS)。
* [SmartEngine](https://github.com/alibaba/SmartEngine)：SmartEngine是一个轻量级的业务编排引擎，在阿里内部广泛使用，可以用于在微服务架构中编排多个服务，也可以用于传统的流程审批场景。
* [Cadence](https://github.com/uber/cadence-java-client)：Cadence是分布式、可扩展、持久且高度可用的编排引擎，用于以可扩展和弹性的方式执行异步长时间运行的业务逻辑，由Uber开发。
* [Flowret](https://github.com/americanexpress/unify-flowret)：Flowret是一个基于Java的轻量级编排引擎，由美国运通开源。
* [CloudSlang](https://github.com/CloudSlang/cloud-slang)：CloudSlang是一种基于YAML的语言，用于为CloudSlang编排引擎编写易于理解的工作流。
* [LittleHorse](https://github.com/littlehorse-enterprises/littlehorse)：LittleHorse是一个高性能的微服务编排引擎，允许开发人员构建可扩展、可维护和可观察的应用程序。
* [Rill Flow](https://github.com/weibocom/rill-flow)：Rill Flow是一种高性能、可扩展的分布式工作流编排服务，由微博开源。
* [ProActive Workflows](https://github.com/ow2-proactive/scheduling)：ProActive是一款功能全面的开源作业调度和编排器，同时还具备工作流和资源管理功能，由Activeeon开发。
* [Kstry](https://gitee.com/kstry/kstry-core)：Kstry可以将原本存在于代码中错综复杂的方法调用关系以可视化流程图的形式更直观的展示出来。
* [Baker](https://github.com/ing-bank/baker)：Baker是一个库，它提供了一种简单直观的方法来编排基于微服务的流程，由ING银行开源。
* [Flux](https://github.com/flipkart-incubator/flux)：Flux是一个异步、可扩展、可选的多租户、分布式且可靠的基于状态机的编排器，由Flipkart开源。
* [Solon Flow](https://gitee.com/opensolon/solon-flow)：Java Flow通用流编排应用开发框架，支持已知流编排的各种场景。

## 规则引擎

* [Apache Drools](https://github.com/apache/incubator-kie-drools)：Drools是Java的规则引擎、DMN引擎和复杂事件处理(CEP)引擎，由RedHat开源。
* [Easy Rules](https://github.com/j-easy/easy-rules)：Easy Rules是一个简单但功能强大的Java规则引擎。
* [Radar](https://gitee.com/freshday/radar)：Radar是一款使用Spring Boot、MongoDB、Groovy、ES等框架搭建的轻量级实时风控引擎。
* [Liteflow](https://gitee.com/dromara/liteFlow)：LiteFlow是一个轻量且强大的国产规则引擎框架，可用于复杂的组件化业务的编排领域，由dromara社区开源。
* [Forge](https://github.com/Card-Forge/forge)：Forge是一款专为万智牌爱好者量身定制的动态开源规则引擎。
* [RuleEngine](https://gitee.com/aizuda/rule-engine-open)：RuleEngine基于Web可视化配置，简单高效快捷，爱组搭开源。
* [RuleBook](https://github.com/deliveredtechnologies/rulebook)：RuleBook提供了一个简单但强大且灵活的规则抽象，其学习曲线非常短。
* [Clara](https://github.com/oracle-samples/clara-rules)：Clara是一个用Clojure(Script)编写并具有Java互操作性的前向链接规则引擎，由Oracle开发。
* [Nected](https://www.nected.ai/)：Nected通过用户友好的界面和声明性规则语言简化了规则表示。
* [RuleEngine](https://github.com/Hale-Lee/RuleEngine)：非常好用的规则引擎，可以直接使用SQL语句定义规则，简化了编码的负荷，也可以使用XML、drl文件配置规则，还支持drools文件导入。
* [Evrete](https://github.com/evrete/evrete)：Evrete是一个前向链接Java规则引擎，它实现RETE算法并完全符合Java规则引擎规范(JSR 94)。
* [OpenL Tablets](https://github.com/openl-tablets/openl-tablets)：OpenL Tablets是一个用于Java的开源业务规则和决策管理系统。
* [ICE](https://github.com/zjn-zjn/ice)：Java规则引擎，针对复杂/灵活变动业务，提供一个新的抽象编排解决方案，轻量级、高性能并提供可视化操作页面。
* [Jess](http://alvarestech.com/temp/fuzzyjess/Jess60/Jess70b7/docs/index.html)：Jess是最早能够轻松与Java集成的规则引擎之一，由桑迪亚国家实验室开源。
* [Higson](https://www.higson.io/)：Higson是一个帮助组织从集中式平台管理、执行和优化其业务规则的系统。
* [JRuleEngine](https://jruleengine.sourceforge.net/)：JRuleEngine是一个Java规则引擎，基于JSR 94，版本1.1。
* [URule](https://github.com/youseries/urule)：URule是一款基于RETE算法的纯Java规则引擎，提供规则集、决策表、决策树、评分卡、规则流等各种规则表现工具及基于网页的可视化设计器。
* [Together](http://rongtek.com/col.jsp?id=115)：你可以通过Together规则引擎构建你的决策模型并将其打包成可独立运行的迷你jar包，快速部署到需要的任何IT环境中。
* [DataFrames](https://github.com/databrickslabs/dataframe-rules-engine)：用于自定义数据框/数据集验证的可扩展规则引擎。
* [JVS Rules](https://gitee.com/software-minister/jvs-rules)：本项目是基于JVS逻辑引擎构建的规则引擎。
* [YARE](https://github.com/SabreOSS/yare)：YARE是一个用Java编写的规则引擎。
* [Naga](https://github.com/threatgrid/naga)：Naga是一个在图数据库上执行规则的库。
* [Rule Engine](https://github.com/jetlinks/rule-engine)：基于流程的流式规则引擎。
* [Power Flows DMN](https://github.com/powerflows/powerflows-dmn)：Power Flows DMN是一个强大的决策引擎。
* [Rulette](https://github.com/kislayverma/Rulette)：Rulette是一个轻量级、与领域无关的规则建模、存储和评估引擎。
* [Dyna Guard](https://gitee.com/vd3/dyna-guard)：Dyna Guard是一个基于Java的动态校验框架。
* [OpenRules](https://openrulesdecisionmanager.com/)：OpenRules是一个具有强大规则引擎的业务规则管理系统。
* [Visual Rules](https://flagleader.com/list.php?pid=1&ty=8&tty=34)：旗正规则引擎是由国家科技部和财政部的创新基金支持开发的一款业务规则管理系统(BRMS)产品。
* [Dataframe Rules Engine](https://github.com/databrickslabs/dataframe-rules-engine)：用于自定义数据帧/数据集验证的可扩展规则引擎，由Databricks开源。
* [Liudao](https://github.com/ysrc/Liudao)：六道实时业务风控系统，由同程安全开源。

## 状态机

* [Squirrel](https://github.com/hekailiang/squirrel)：Squirrel为Java提供了一个易于使用、类型安全且高度可扩展的状态机实现。
* [Spring Statemachine](https://github.com/spring-projects/spring-statemachine)：Spring Statemachine项目提供了一个通用的基础设施来在Spring应用程序中使用状态机概念。
* [Stateless4j](https://github.com/stateless4j/stateless4j)：轻量级Java状态机。
* [StateMachine](https://github.com/Tinder/StateMachine)：Kotlin和Swift中的状态机库，由Tinder开源。
* [EasyFlow](https://github.com/Beh01der/EasyFlow)：EasyFlow是一个简单且轻量级的Java有限状态机。
* [KStateMachine](https://github.com/KStateMachine/kstatemachine)：KStateMachine是一个强大的Kotlin多平台库，具有清晰的DSL语法，用于创建由Kotlin Coroutines驱动的复杂状态机和状态图。
* [Easy States](https://github.com/j-easy/easy-states)：Easy States是Java中事件驱动的确定性有限自动机实现。
* [StatefulJ](https://github.com/statefulj/statefulj)：StatefulJ是一个轻量级、开源的Java事件驱动有限状态机(FSM)和一个完整的基于Spring Data的框架，可让你轻松定义状态机并将其集成到你的应用程序中。
* [nFlow](https://github.com/NitorCreations/nflow)：nFlow是一种经过验证的用于编排业务流程的解决方案。
* [Mensa](https://github.com/QSFT/Mensa)：Mensa是一种通用、灵活、增强且高效的模式匹配状态机的Java实现，由Dell开源。
* [Winder](https://github.com/eBay/Winder)：Winder是一个基于Quartz的简单状态机，由eBay开源。
* [StateSmith](https://github.com/StateSmith/StateSmith)：StateSmith是一个跨平台、免费/开源的工具，用于生成多种编程语言的状态机。
* [State Machine](https://github.com/davidmoten/state-machine)：Java的有限状态机类生成器。
* [Makina](https://github.com/clnhlzmn/makina)：Makina是一个分层状态机源到源转换器，它将状态机描述作为输入并生成这些状态机的C语言实现。
* [JState](https://github.com/UnquietCode/JState)：Java中的高级状态机。
* [State Machine Compiler](https://smc.sourceforge.net/)：SMC最大限度地利用了状态模式，允许你的对象处理意外事件、恢复并继续提供服务(而不是崩溃)的转换。
* [Morfologik Stemming](https://github.com/morfologik/morfologik-stemming)：用于有限状态自动机构建和基于字典的形态词典的工具。
* [TSM4j](https://github.com/weilueluo/tsm4j)：Java的类型化状态机。
* [Dk.Brics.Automaton](https://github.com/cs-au-dk/dk.brics.automaton)：Java的有限状态自动机和正则表达式，由奥胡斯大学开源。
* [Redux Java](https://github.com/glung/redux-java)：Redux的Java版本，应用程序的可预测状态容器。
* [Bansa](https://github.com/brianegan/bansa)：受Redux和Elm启发的Java和Kotlin状态容器。
* [Grox](https://github.com/groupon/grox)：Grox有助于维护Java/Android应用程序的状态。
* [Simple Statemachine](https://github.com/mapteb/simple-state-machine)：用于Spring Boot项目的简单Java状态机。

## 报表引擎

* [JimuReport](https://github.com/jeecgboot/JimuReport)：积木报表是一款免费的数据可视化报表，含报表、打印、大屏和仪表盘，由北京国炬公司开发。
* [UReport2](https://github.com/youseries/ureport)：UReport2是一个基于Spring架构的高性能纯Java报表引擎，可以通过迭代单元格来准备复杂的中式报表和报表。
* [AJ-Report](https://gitee.com/anji-plus/report)：AJ-Report是一个完全开源，拖拽编辑的可视化设计工具。
* [EasyReport](https://github.com/xianrendzw/EasyReport)：EasyReport是一个简单易用的Web报表工具，它的主要功能是把SQL语句查询出的行列结构转换成HTML表格，并支持表格的跨行与跨列。
* [SpringReport](https://gitee.com/springreport/springreport)：SpringReport是一款企业级的报表系统，支持在线设计报表，并绑定动态数据源，无需写代码即可快速生成想要的报表。
* [VeryReport](https://www.veryreport.com/)：VeryReport是专业级企业Web报表软件，易学易用，轻松解决中国式复杂报表，这是中创微软件公司的商业产品。
* [JasperReports](https://github.com/TIBCOSoftware/jasperreports)：JasperReports库是世界上最流行的开源报告引擎，由TIBCO软件公司开源。
* [Eclipse BIRT](https://github.com/eclipse-birt/birt)：BIRT是商业智能报告工具，可以从许多不同的数据源(数据库、文件、Java、Javascript、Web服务等)提取和组合数据，并将这些数据用于报告和图表，由安讯公司开源。
* [Reports.Java](https://www.stimulsoft.com/en/products/reports-java)：Stimulsoft Reports.Java是一款报表工具，旨在帮助你在Java应用程序中实现业务报表的交互和运行。
* [Ferris Wheel](https://github.com/littleorca/ferris-wheel)：Ferris Wheel是一个很棒的电子表格框架，由携程开发。
* [YARG](https://github.com/cuba-platform/yarg)：YARG是一个Java开源报告库，由Haulmont开发。
* [Pentaho](https://github.com/pentaho/pentaho-reporting)：Pentaho是用于生成报告的Java类库，它使用来自多个来源的数据提供灵活的报告和打印功能，并支持输出到显示设备、打印机、PDF、Excel、XHTML、纯文本、XML和CSV文件。
* [DynamicJasper](https://github.com/intive-FDV/DynamicJasper)：DynamicJasper是一个隐藏JasperReports复杂性的API，它可以帮助开发人员在设计简单/中等复杂性报表时节省时间，自动生成报表元素的布局。
* [ExtentReports](https://github.com/extent-framework/extentreports-java)：ExtentReports是一个用于自动化测试的日志记录器样式的报告库。
* [FineReport](https://www.finereport.com/)：FineReport是一款用于报表制作，分析和展示的工具，这是帆软公司的商业产品。
* [Logi Report](https://devnet.logianalytics.com/hc/en-us/categories/1500001227442-Logi-Report)：Logi Report被设计为作为独立服务器执行，但可以将其集成到现有WAR项目中。
* [Report Mill](http://www.reportmill.com/product/)：ReportMill可以平滑地嵌入到每个Java应用程序中，此外，与BIRT一样它非常灵活：可以在运行时自定义报告。
* [iReport](https://community.jaspersoft.com/project/ireport-designer)：一个开源报表设计器，对于JasperReports库和JasperReports服务器免费。
* [R3-Query](https://gitee.com/aagagagag/R3-Query)：R3 Query整合了企业报表领域各个周期的支持，其中包括报表设计、报表发布、报表生成、报表管理、订阅发布和报表监控等报表的整个生命周期的步骤。
* [UReport Kepp](https://gitee.com/summer-T/ureport-keep)：UReport Kepp是UReport的替代项目。
* [Skyeye Report](https://gitee.com/doc_wei01/skyeye-report)：Skyeye Report是一款高性能的Java报表引擎，提供完善的基于网页的报表设计器，可快速做出各种复杂的中式报表。
* [Dynamic Reports](https://github.com/dynamicreports/dynamicreports)：DynamicReports是一个基于JasperReports的开源Java报表库，它允许创建动态报表设计，并且不需要可视化报表设计器。
* [Clear Reports](https://www.inetsoftware.de/products/clear-reports)：Clear Reports是一种灵活且功能强大的报告解决方案，可用于多种不同用途。
* [Wang Template](https://github.com/52jing/wang-template-backend)：该系统是一个从实际生产平台提取的报表渲染模块，作为独立的报表生成系统。
* [Report Engine](https://reportengine.sourceforge.net/)：Report Engine是一套Java代码，支持列、分组、总计/小计的报表类和数据透视表。
* [XMReport](https://www.xmreport.com/index.html)：XMReport是一款轻便但非常灵活且可扩展的模板打印设计器和引擎，你可以轻松构建复杂布局的模板。
* [Java Report Engine](https://response-systems.com/composer-suite/java-report-engine/)：Java Report Engine是一款运行时软件产品，能够生成和交付使用Gen和Report Composer设计的网页报告。
* [OpenReports](https://oreports.com/)：OpenReports是一款强大、灵活且易用的开源Web报告解决方案。

## 商业智能

* [Metabase](https://github.com/metabase/metabase)：Metabase是一个开源的商业智能工具，你可以通过它理解数据、分析数据，进行数据查询并获取格式化结果，以数据驱动决策。
* [Poli](https://github.com/shzlw/poli)：Poli是一款易于使用的SQL报告应用程序，专为SQL爱好者打造。
* [FineBI](https://www.finebi.com/)：FineBI是帆软公司推出的一款商业智能产品。
* [SuperSonic](https://github.com/tencentmusic/supersonic)：SuperSonic是下一代LLM支持的数据分析平台，集成了ChatBI和HeadlessBI，由腾讯音乐娱乐开源。
* [CBoard](https://gitee.com/tuiqiao/CBoard)：CBoard由上海楚果信息技术有限公司主导开源，它不仅仅是一款自助BI数据分析产品，还是开放的BI产品开发平台。
* [DataRoom](https://gitee.com/gcpaas/DataRoom)：DataRoom是一款基于Spring Boot、MyBatis Plus、Vue、ElementUI、G2Plot、Echarts等技术栈的大屏设计器，由科大国创云网科技公司开源。
* [BI Platform](https://github.com/baidu/BIPlatform)：百度开源，业内领先的Holap敏捷BI分析平台，提供高性能、准实时、可扩展的、一站式的BI建模、分析平台。
* [Abixen Platform](https://github.com/abixen/abixen-platform)：Abixen是一个基于微服务的软件平台，用于构建企业应用程序，通过创建特定的微服务并通过提供的CMS集成来提供功能。
* [Helical Insight](https://github.com/helicalinsight/helicalinsight)：Helical Insight是世界上第一个开源商业智能框架，可以帮助你从一个或多个数据源中获取见解。
* [Guitar](https://github.com/iflytek/Guitar)：Guitar是一款简单、高效的分布式多维BI报表分析引擎，由科大讯飞开源。
* [LinceBI](https://github.com/LinceBI/lincebi)：LinceBI是一个完整的商业智能解决方案，包括ETL、元数据、大数据和机器学习等模块。
* [Knowage](https://github.com/KnowageLabs/Knowage-Server)：Knowage是开源分析和商业智能套件，可让你将传统数据和大/云数据源组合成有价值且有意义的信息，由OW2开源。
* [Datafor](https://datafor.com.cn/)：Datafor是一款自助式敏捷BI工具，旨在为用户提供直观易用的数据可视化和探索式分析功能，帮助用户快速进行数据探索、分析和决策。
* [JRelax-BI](https://gitee.com/zengchao/JRelax-BI)：BI商业智能，自定义表单+自定义流程+自定义报表。
* [ART](https://art.sourceforge.net/)：ART是一种报告和商业智能解决方案，它可以快速部署SQL查询结果，支持表格报告、图表、仪表板、调度。
* [FusionView](https://gitee.com/hitsoft1995/fusion-view)：富表智能数据可视化平台是一款面向企业和行业级别的用户，具有AI特色的可视化与BI商业智能敏捷分析的平台。
* [ReportServer](https://github.com/infofabrik/reportserver)：ReportServer是一个现代、多功能的开源商业智能(BI)平台，具有强大的报告功能，由ReportServer公司开发。
* [Logi Analytics](https://insightsoftware.com/logi-analytics/)：Logi Analytics提供具有自助分析功能的商业智能和数据发现平台，这是InsightSoftware公司的商业产品。
* [睿思BI](https://gitee.com/ruisibi/rsbi-pom)：睿思BI是由成都睿思商智公司研发的企业数据分析系统。
* [Rakam](https://github.com/rakam-io/rakam-api)：Rakam是一个分析平台，可让你创建分析服务。
* [Oceanus.BI](https://github.com/hf200012/oceanus.bi)：Oceanus是一个可自由拖拽的BI可视化系统。
* [EazyBI](https://eazybi.com/)：EazyBI是一款功能强大的工具，提供易于使用的拖放式创建自定义报告、图表和仪表板小工具。
* [BambooBSC](https://github.com/billchen198318/bamboobsc)：BambooBSC是一个开源的平衡计分卡商业智能系统。
* [Tahopen](https://github.com/tahopen/tahopen-platform)：Tahopen是一个强大的开源商业分析平台，由Pentaho分支而来。

## 模板引擎

* [Thymeleaf](https://github.com/thymeleaf/thymeleaf)：Thymeleaf是一个现代服务器端Java模板引擎，适用于Web和独立环境。
* [JSP](https://www.oracle.com/java/technologies/jspt.html)：Java应用程序最流行的视图技术之一，也是内置的模板引擎。
* [Apache FreeMarker](https://github.com/apache/freemarker)：FreeMarker是一个基于模板生成文本输出(从HTML到自动生成源代码的任何内容)的通用工具。
* [Pebble](https://github.com/PebbleTemplates/pebble)：Pebble是一个受Twig启发的Java模板引擎，带有内置的自动转义功能以确保安全，并且包括对国际化的集成支持。
* [Groovy](http://groovy-lang.org/templating.html#_the_markuptemplateengine)：Groovy提供Markup模板引擎，该引擎基于构建器语法，可用于生成任何文本格式。
* [Apache Velocity](https://github.com/apache/velocity-engine)：Velocity是一个用Java编写的通用模板引擎。
* [Mustache](https://github.com/spullara/mustache.java)：Mustache模板引擎Java实现。
* [Apache Tiles](https://github.com/apache/tiles)：Apache Tiles是一个Java EE应用的页面布局框架。
* [EscapeVelocity](https://github.com/google/escapevelocity)：EscapeVelocity是一个可以在Java中使用的模板引擎，它是Velocity功能子集的重新实现，由Google开源。
* [Jade4j](https://github.com/neuland/jade4j)：Jade4j的目的是能够在Java中处理jade模板，而不需要JavaScript环境，同时完全兼容原始jade语法。
* [Handlebars.java](https://github.com/jknack/handlebars.java)：Handlebars.java是Handlebars的Java端口。
* [Beetl](https://github.com/javamonkey/beetl2.0)：Beetl是新一代的模板引擎，更简单易用。
* [Twirl](https://github.com/playframework/twirl)：Twirl是Play的默认模板引擎。
* [Rocker](https://github.com/fizzed/rocker)：Rocker是一个Java 8+优化、近乎零拷贝渲染的快速模板引擎，可生成静态类型、纯Java对象模板，并与项目的其余部分一起编译，由Fizzed开源。
* [Jinja](https://github.com/HubSpot/jinjava)：基于Django模板语法的基于Java的模板引擎，适用于渲染Jinja模板，由HubSpot开源。
* [HTTL](https://github.com/httl/httl)：HTTL是一个高性能的开源Java模板引擎，适用于动态HTML页面输出，可替代JSP页面，指令和Velocity相似。
* [Qute](https://cn.quarkus.io/guides/qute)：Qute是专为Quarkus开发的模板引擎。
* [JetBrick](https://github.com/subchen/jetbrick-template-2x)：JetBrick是一个新一代Java模板引擎，具有高性能和高扩展性。
* [HtmlFlow](https://github.com/xmlet/HtmlFlow)：HtmlFlow是一种Java DSL，可以以流式的方式编写类型安全的HTML文档。
* [Scalate](https://github.com/scalate/scalate)：Scalate是一个基于Scala的模板引擎，支持HAML、Mustache以及JSP、Erb和Velocity风格的语法。
* [Beard](https://github.com/zalando/beard)：Beard是一个无逻辑的模板引擎，用Scala编写，灵感来自Mustache，由Zalando开源。
* [Chunk](https://github.com/tomj74/chunk-templates)：Chunk是一个Java模板引擎，适用于服务HTML或XML的应用程序。
* [Trimou](https://github.com/trimou/trimou)：Java中的Mustache/Handlebars模板引擎。
* [Rythm](https://github.com/rythmengine/rythmengine)：类似Razor、功能丰富、高性能且易于使用的Java模板引擎。
* [Liqp](https://github.com/bkiers/Liqp)：Liquid模板引擎的Java实现，由ANTLR语法支持。
* [StringTemplate](https://github.com/antlr/stringtemplate4)：StringTemplate是一个Java模板引擎，用于生成源代码、网页、电子邮件或任何其他格式化文本输出。
* [JTE](https://github.com/casid/jte)：JTE是一个适用于Java和Kotlin的安全且快速的模板。
* [Jamal](https://github.com/verhas/jamal)：嵌入到Maven/JavaDoc中的可扩展模板引擎，支持多种扩展(Groovy、Ruby、JavaScript、JShell、PlantUml)，并支持片段处理。
* [JStachio](https://github.com/jstachio/jstachio)：JStachio是一种类型安全的Java Mustache模板引擎。
* [Jtwig](https://github.com/jtwig/jtwig)：模块化、可配置且经过全面测试的模板引擎。
* [JMustache](https://github.com/samskivert/jmustache)：JMustache是Mustache模板语言的Java实现。
* [Enjoy](https://gitee.com/jfinal/enjoy)：Enjoy是基于Java语言的极轻量极模板引擎。
* [Pug4j](https://github.com/neuland/pug4j)：Pug4j的目的是能够在不需要JavaScript环境的情况下处理Java中的pug模板，同时与原始pug语法完全兼容。
* [JMTE](https://code.google.com/archive/p/jmte/)：JMTE旨在填补使用String.format等基本Java类的简单字符串格式化与Velocity或StringTemplate等复杂模板解决方案之间的空白。
* [Jamon](http://www.jamon.org/index.html)：Jamon是一个Java文本模板引擎，用于生成动态HTML、XML或任何基于文本的内容。
* [FreshMarker](https://gitlab.com/schegge/freshmarker)：FreshMarker是一个简单的嵌入式Java 21模板引擎，其灵感来自FreeMarker。
* [ZML](https://gitee.com/zhiqim/zhiqim_zml)：ZML是知启蒙定义的、类似于Java、Javascript语法的语句和表达式，通常和XML/HTML混编在一起形成的一种新的标记语言。
* [Japid](https://github.com/branaway/Japid)：Japid是一个基于Java的动态内容渲染模板系统。
* [Spring Boot HTMX](https://github.com/wimdeblauwe/htmx-spring-boot)：该项目简化了HTMX与Spring Boot/Spring Web MVC应用程序的集成。
* [Spring ViewComponent](https://github.com/tschuehly/spring-view-component)：使用Spring创建服务器端ViewComponent的库。
* [Squarespace Template](https://github.com/Squarespace/template-compiler)：Squarespace Template是Squarespace网站构建平台的核心模板编译引擎。

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
* [PlumeJob](https://gitee.com/plumeorg/plumejob)：PlumeJob是一个去中心化的分布式调度系统，集成简单易用，由Plume组织开源。
* [TBSchedule](https://github.com/nmyphp/tbschedule)：TBSchedule是一个由阿里开源的支持分布式的调度框架。
* [Sundial](https://github.com/knowm/Sundial)：Sundial是一个轻量级的Java任务调度框架。
* [Kob](https://github.com/LianjiaTech/kob)：Kob是中心化的作业调度系统，定义了任务调度模型，实现了任务调度的统一管理和监控，由贝壳开源。
* [Wisp](https://github.com/Coreoz/Wisp)：Wisp是一个用于管理重复性Java作业执行的库。
* [Android Job](https://github.com/Evernote/android-job)：用于在后台处理作业的Android库，由Evernote开源。
* [FlowJob](https://github.com/limbo-world/flowjob)：FlowJob主要用于搭建统一的任务调度平台，方便各个业务方进行接入使用。
* [BatchMan](https://github.com/flipkart-incubator/batchman)：BatchMan是一个Android库实现，负责根据客户端完成的配置对事件进行批处理，并将批处理返回给客户端，由Flipkart开源。
* [Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue)：Priority Job Queue是专门为Android编写的作业队列的实现，可轻松安排在后台运行的作业，从而提高用户体验和应用程序稳定性。
* [Firebase JobDispatcher](https://github.com/googlearchive/firebase-jobdispatcher-android)：Firebase JobDispatcher是一个用于在Android应用中调度后台作业的库，由Google开发。
* [Cron4j](http://www.sauronsoftware.it/projects/cron4j/)：Cron4j是Java平台的调度程序，与UNIX Cron守护程序非常相似。
* [Legends](https://github.com/tongbanjie/legends)：Legends是Java开发的一个任务调度框架，可以远程执行一次性或重复性的Job，查看任务的执行状态以及任务结果，由铜板街开源。
* [Job Dispatcher](https://gitee.com/daye_daye/job-dispatcher)：国产的基于事件的流程编排和调度引擎。
* [Snail Job](https://gitee.com/aizuda/snail-job)：Snail Job是一个功能强大的分布式重试和任务调度平台，为支持提高分布式业务系统一致性和分布式任务调度而设计，由爱组搭开源。
* [SIA-TASK](https://github.com/siaorg/sia-task)：SIA-TASK是任务调度的一体式解决方案，简单易用，由宜信开源。
* [Jobs](https://gitee.com/baomidou/jobs)：baomidou社区开源的分布式任务调度组件。
* [JobX](https://github.com/datavane/jobx)：JobX是一个功能完善真正通用的Linux定时任务调度系统，由Datavane大数据组织开源。
* [BigBen](https://github.com/walmartlabs/bigben)：BigBen是一个基于Cassandra和Hazelcast的通用、多租户、基于时间的事件调度程序和Cron调度框架，由沃尔玛开源。
* [Rqueue](https://github.com/sonus21/rqueue)：Rqueue是一个为Spring框架构建的异步任务执行器，基于Redis支持的Spring框架的消息传递库。
* [Light Task Scheduler](https://github.com/ltsopensource/light-task-scheduler)：LTS主要用于解决分布式任务调度问题，支持实时任务、定时任务和Cron任务。
* [Atlassian Scheduler](https://bitbucket.org/atlassian/atlassian-scheduler)：Atlassian Scheduler库是用于在Atlassian应用程序中创建调度任务的API。
* [CronMan](https://github.com/smmdwa/CronMan)：CronMan是一款轻量级的分布式任务调度系统。
* [Chronus](https://github.com/360digitech/chronus)：Chronus是360数科技术团队基于阿里开源项目TBSchedule重写的分布式调度。
* [Earth Frost](https://gitee.com/justlive1/earth-frost)：Earth Frost是一个轻量级分布式任务调度框架。
* [Schedulix](https://github.com/schedulix/schedulix)：Schedulix是一个开源企业作业调度系统。
* [Hodor](https://github.com/dromara/hodor)：Hodor是一个专注于任务调度以及任务编排的一站式分布式任务调度系统，由dromara社区开源。
* [TASKANA](https://github.com/Taskana/taskana)：TASKANA是一个任务管理组件开源库，它可以嵌入到你的应用程序中，也可以在适当的情况下独立运行。
* [Juice](https://github.com/HujiangTechnology/Juice)：Juice是沪江学习系统项目组所开发的一套基于Mesos Framework的分布式任务调度云系统。
* [JQM](https://github.com/enioka-Haute-Couture/jqm)：JQM是一个任务队列管理器。
* [Database Queue](https://github.com/yoomoney/db-queue)：该库在Java和数据库之上提供了工作队列实现，由YooMoney开源。
* [TinyTask](https://github.com/inaka/TinyTask)：一个用于创建异步后台任务的小型Android库，由Inaka开发。
* [Hashed Wheel Timer](https://github.com/ifesdjeen/hashed-wheel-timer)：与ScheduledExecutorService兼容的高性能计时器/调度程序库。
* [LogiCommon](https://github.com/didi/LogiCommon)：LogiCommon包含认证、鉴权、管理、任务调度通用功能组件，由滴滴开源。
* [Persistasaurus](https://github.com/gunnarmorling/persistasaurus)：Persistasaurus是一个基于SQLite的极简Java持久化执行库。
* [Quartz Manager](https://github.com/fabioformosa/quartz-manager)：Quartz Manager是一个Java库，你可以导入Spring Web应用中，用于运行定时作业、启动和停止它们并获取作业结果。
* [Octobot](https://github.com/cscotta/Octobot)：Octobot是一个任务队列工作器，旨在实现可靠性、易用性和高吞吐量。

## 企业集成模式

* [Mule](https://github.com/mulesoft/mule)：Mule是一个轻量级集成平台，可让你在任何地方连接任何东西。
* [Apache Camel](https://github.com/apache/camel)：Camel是一个开源集成框架，使你能够快速轻松地集成使用或生成数据的各种系统，由RedHat开源。
* [Spring Integration](https://github.com/spring-projects/spring-integration)：Spring Integration提供了Spring编程模型的扩展，以支持众所周知的企业集成模式。
* [WSO2 Enterprise Integrator](https://github.com/wso2/product-ei)：WSO2 Enterprise Integrator是一个开源、快速、云原生且可扩展的集成解决方案，是WSO2集成敏捷平台的核心。
* [Syndesis](https://github.com/syndesisio/syndesis)：Syndesis是一个灵活且可定制的开源平台，以服务形式提供核心集成功能，由Fuse Online开源。
* [Metl](https://github.com/JumpMind/metl)：Metl是一个简单、基于Web的集成平台，允许多种不同类型的数据集成，包括消息传递、基于文件的ETL以及通过Web Service的远程过程调用。
* [Frank](https://github.com/frankframework/frankframework)：Frank是一个易于使用的无状态集成框架，允许在不同系统之间修改和交换(事务)消息，由WeAreFrank开源。
* [RACE](https://github.com/aegisql/conveyor)：RACE是一个可扩展的异步企业集成和创建型Java框架。
* [Ikasan](https://github.com/ikasanEIP/ikasan)：开源企业集成平台。

## SMT求解器

* [Alloy](https://github.com/AlloyTools/org.alloytools.alloy)：Alloy是一个独立的可执行文件，其中包括Kodkod模型查找器和各种SAT求解器，由MIT开源。
* [Sat4j](https://gitlab.ow2.org/sat4j/sat4j)：Sat4j是一个用于解决布尔满足和优化问题的Java库，它可以解决SAT、MAXSAT、伪布尔、最小不可满足子集问题，由阿尔多瓦大学和法国国家科学研究院开发。
* [DuaLip](https://github.com/linkedin/DuaLip)：DuaLip是一种基于Spark的超大规模线性规划(LP)求解器，由LinkedIn开发。
* [CVC5](https://github.com/cvc5/cvc5)：CVC5是一种用于确定一阶公式对一阶理论(或此类理论的组合)的可满足性的工具，由伯克利大学和三星研究院开发。
* [JavaSMT](https://github.com/sosy-lab/java-smt)：JavaSMT是用于访问各种SMT求解器的通用API层，由德国慕尼黑大学开源。
* [SMTInterpol](https://github.com/ultimate-pa/smtinterpol)：SMTInterpol是弗莱堡大学开发的插值SMT求解器。
* [JSCIPOpt](https://github.com/scipopt/JSCIPOpt)：SCIP是目前混合整数规划(MIP)和混合整数非线性规划(MINLP)最快的非商业求解器之一，由柏林自由大学开源。
* [CLP Java](https://github.com/quantego/clp-java)：CLP线性求解器的Java接口，针对快速模型构建和快速解析进行了优化。
* [LINE](https://line-solver.sourceforge.net/)：LINE是一个开源软件包，用于通过分析方法或模拟来分析排队模型，由伦敦帝国理工学院的QORE实验室开发。
* [KSMT](https://github.com/UnitTestBot/ksmt)：满足各种SMT求解器的统一Kotlin/Java API。
* [LogicNG](https://github.com/logic-ng/LogicNG)：LogicNG是一个用于创建、操作和求解布尔和伪布尔公式的Java库，它包括MiniSAT、Glucose、PBLib或OpenWBO等流行工具的纯Java实现。
* [LPSolve](https://lpsolve.sourceforge.net/)：LPSolve是一个开源的线性(整数)规划求解器，基于修正单纯形法和整数的分支定界法。

## 命令行开发

#### CLI库

* [Picocli](https://github.com/remkop/picocli)：Picocli是一个现代框架，用于轻松构建功能强大、用户友好、支持GraalVM的命令行应用程序。
* [Clikt](https://github.com/ajalt/clikt)：Clikt是一个多平台Kotlin库，它使编写命令行界面变得简单直观。
* [Apache Commons CLI](https://github.com/apache/commons-cli)：Commons CLI提供了一个简单的API，用于呈现、处理和验证命令行界面。
* [Spring Shell](https://github.com/spring-projects/spring-shell)：Spring Shell可帮助你创建基于Spring的、针对CLI空间的生产级应用程序。
* [Airline](https://github.com/rvesse/airline)：Airline是一个Java库，提供基于注解的命令行接口解析框架。
* [JLine](https://github.com/jline/jline3)：JLine是一个用于处理控制台输入的Java库。
* [Kotlinx CLI](https://github.com/Kotlin/kotlinx-cli)：通用命令行解析器的纯Kotlin实现，由JetBrains开发。
* [Lamp](https://github.com/Revxrsal/Lamp)：Lamp是一个多功能且强大的命令框架，专为现代Java和Kotlin应用设计。
* [Kotlin Inquirer](https://github.com/kotlin-inquirer/kotlin-inquirer)：受Inquirer.js启发编写的常见交互式命令行用户界面集合。
* [W2J CLI](https://github.com/frost373/w2j-cli)：Java Web命令行框架，帮助你轻松构建命令行Java Web系统。
* [Clamshell Cli](https://github.com/vladimirvivien/clamshell-cli)：Clamshell Cli是一个用Java构建基于控制台的命令行应用程序的框架。
* [Kotter](https://github.com/varabyte/kotter)：Kotter旨在成为一个相对精简、声明式且符合Kotlin语法的API，提供实用的功能，助你轻松编写赏心悦目的控制台应用程序。
* [Text-IO](https://github.com/beryx/text-io)：Text-IO是一个用于创建Java控制台应用程序的库，它可用于需要读取用户交互式输入的应用程序。
* [Clique](https://github.com/kusoroadeolu/Clique)：Clique是无依赖迷你CLI框架，旨在美化Java中的CLI应用程序。

#### TUI

* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer)：该库实现了一个基于文本的窗口系统。
* [TUI Scala](https://github.com/oyvindberg/tui-scala)：TUI Scala是用于构建富终端用户界面和仪表盘的Scala库。
* [Casciian](https://github.com/crramirez/casciian)：Java文本用户界面库。
* [Text UI](https://github.com/alibaba/text-ui)：阿里开源的文本用户界面库。

#### 命令行参数解析

* [JCommander](https://github.com/cbeust/jcommander)：JCommander是一个非常小的Java框架，可以轻松解析命令行参数。
* [Args4j](https://github.com/kohsuke/args4j)：Args4j是一个小型Java类库，可以轻松解析CUI应用程序中的命令行选项/参数。
* [Aesh](https://github.com/aeshell/aesh)：Aesh是一个用于处理控制台输入的Java库。
* [JArgs](https://github.com/purcell/jargs)：JArgs是一个命令行参数解析库。
* [Cloud](https://github.com/Incendo/cloud)：Cloud是一个通用Java命令调度程序和框架，它允许程序员定义命令链，然后从用户提供的字符串输入中解析和调用这些命令链，以执行预定义的操作。
* [JOpt Simple](https://github.com/jopt-simple/jopt-simple)：JOpt Simple是一个用于解析命令行选项的Java库。
* [Argparse4j](https://github.com/argparse4j/argparse4j)：Argparse4j是一个基于Python argparse模块的Java命令行参数解析器库。
* [Kotlin ArgParser](https://github.com/xenomachina/kotlin-argparser)：这是一个用于解析命令行参数的库。
* [MainArgs](https://github.com/com-lihaoyi/mainargs)：MainArgs是一个小型、无依赖的Scala命令行参数解析库。
* [JaCoLine](https://github.com/chriswhocodes/JaCoLine)：为开发人员提供有用的工具来理解和验证他们的Java命令行选项。
* [Docopt.Java](https://github.com/docopt/docopt.java)：Docopt的Java移植版本，Docopt是一个命令行参数解析库。
* [CLI Parser](https://github.com/spullara/cli-parser)：CLI Parser是一个小型、超级易于使用的库，用于解析各种命令行参数或属性列表。
* [JewelCLI](https://github.com/lexicalscope/jewelcli)：JewelCli使用带注解的接口或类定义来自动解析和呈现命令行参数。
* [CmdOption](https://github.com/ToToTec/CmdOption)：CmdOption是一个简单的注解驱动的命令行解析器工具包，适用于通过注解配置的Java 6+应用程序。
* [JBock](https://github.com/jbock-java/jbock)：JBock是一个命令行解析器。
* [Google Options](https://github.com/pcj/google-options)：这是Bazel项目的命令行参数解析器，由Google开发。
* [RecordArgs](https://github.com/nipafx/record-args)：RecordArgs是一个简单的命令行参数解析器，适用于依赖记录和密封接口的Java应用程序。
* [Rop](https://github.com/ryenus/rop)：用Java编写的轻量级命令行参数解析器。
* [Lanat](https://github.com/darvil82/lanat)：Lanat是Java 17的命令行参数解析器，具有易用性和高度可定制性。
* [Barclay](https://github.com/broadinstitute/barclay)：Barclay是一组用于注释、解析、验证和生成命令行选项文档的类，由麻省理工学院和哈佛大学布罗德研究所开源。

#### ASCII艺术

* [Jansi](https://github.com/fusesource/jansi)：Jansi是一个小型Java库，允许使用ANSI转义序列来格式化控制台输出，甚至可以在Windows上运行。
* [DITAA](https://github.com/stathissideris/ditaa)：DITAA是一个小型命令行工具，可以将使用ASCII艺术绘制的图，转换为合适的位图图形。
* [Mordant](https://github.com/ajalt/mordant)：Mordant是一个多平台库，用于在终端中渲染样式文本。
* [Java ASCII Render](https://github.com/indvd00m/java-ascii-render)：纯Java的ASCII渲染器，没有外部依赖，支持图形基元/元素、图层、上下文、画布。
* [ConsoleUI](https://github.com/awegmann/consoleui)：微型Java库，可在基于ANSI控制台的终端上启用简单的UI元素。
* [Jfiglet](https://github.com/lalyos/jfiglet)：FIGfonts的Java实现，用于创建Ascii横幅。
* [Java-Ascii-Table](https://github.com/nedtwigg/asciitable)：Java中用于ASCII表的简单库。
* [JColor](https://github.com/dialex/JColor)：JColor提供了一种简单的语法，可以在终端上以彩色字体或背景打印消息。
* [Colorized Java](https://github.com/vieitesss/colorize-Java)：在Java控制台中打印彩色文本的小型库。
* [Asciimg](https://github.com/korhner/asciimg)：Asciimg是一个用Java编写的可扩展Ascii艺术生成器。
* [Crossword](https://github.com/JakeWharton/crossword)：用于渲染文本的2D画布，通常用于控制台应用程序。
* [Pretty Print](https://github.com/snowe2010/pretty-print)：JVM的漂亮打印模块。
* [Kolor](https://github.com/ziggy42/kolor)：Kolor是一个使用Kotlin打印彩色字符串的库。
* [Tree Printer](https://github.com/davidsusu/tree-printer)：用于在命令行中可视化树结构的简单Java库。
* [PrettyPrintTree](https://github.com/AharonSambol/PrettyPrintTreeJava)：该包允许你以可读的方式打印树数据结构。
* [Chalk](https://github.com/tomas-langer/chalk)：Chalk专注于Java中的跨平台标准输出着色。
* [ASCII Graphs](https://github.com/mdr/ascii-graphs)：一个用于图的ASCII艺术图库，它支持解析现有图解和将图渲染成ASCII图。

#### 文本表

* [Picnic Tables](https://github.com/JakeWharton/picnic)：Kotlin DSL和Java/Kotlin构建器API，用于构建可呈现为文本的类似HTML的表格。
* [Flip Tables](https://github.com/JakeWharton/flip-tables)：用于在Java中打印漂亮的文本表。
* [ASCII Table](https://github.com/vdmeer/asciitable)：ASCII Table是一个简单的工具，用于格式化表格，具有缩进、缩进字符、对齐、填充、填充字符和行内空白字符的各种行/列选项。
* [ASCII Data](https://github.com/MitchTalmadge/ASCII-Data)：ASCII Data是一个小型Java库，用于生成美观的ASCII线图和表格。
* [Ascii Art Table](https://github.com/klaus31/ascii-art-table)：通过Java将数据打印到Ascii表的简单库。
* [ASCII Tables](https://github.com/freva/ascii-table)：使用Java轻松创建和自定义简单的ASCII表。
* [Java Text Tables](https://github.com/iNamik/java_text_tables)：Java中的文本表库。

#### 进度条

* [Progressbar](https://github.com/ctongfei/progressbar)：Progressbar是一个基于控制台的Java进度条。
* [ProgressBar](https://github.com/raszi/java-progressbar)：这是一个简单的Java控制台进度条，它可以在CLI程序中用于显示耗时任务的进度。

## 控制台

* [Babun](https://github.com/babun/babun)：Babun是Windows上类似Linux的控制台。
* [Bastillion](https://github.com/bastillion-io/Bastillion)：Bastillion是一个基于Web的SSH控制台，可集中管理系统的管理访问。

## 版本控制系统

* [Eclipse JGit](https://eclipse.dev/jgit/)：JGit是一个纯Java类库，实现了Git版本控制系统。
* [Gitective](https://github.com/kevinsawicki/gitective)：Gitective是一个基于JGit构建的Java库，它使得调查Git仓库变得更简单、更容易。
* [Git Changelog Lib](https://github.com/tomasbjerre/git-changelog-lib)：该库可以从Git仓库生成变更日志或发行说明，并且可以根据自上次发布以来的提交格式确定下一个版本。
* [JGitFS](https://github.com/centic9/JGitFS)：JGitFS提供对Git分支/标签/提交的访问，就像它们通过FUSE用户层文件系统是单独的目录一样。
* [Jagged](https://github.com/ethomson/jagged)：Jagged为libgit2(一种原生Git实现)提供Java语言绑定。
* [RepoDriller](https://github.com/mauricioaniche/repodriller)：RepoDriller是一个Java框架，可帮助开发人员挖掘软件仓库。

#### Git服务器

* [GitBucket](https://github.com/gitbucket/gitbucket)：GitBucket是由Scala提供支持的Git平台，具有易于安装、高扩展性和GitHub API兼容性。
* [GitSolo](https://gitee.com/zhiqim/gitsolo)：GitSolo是知启蒙团队开源的极简Git服务器，纯Java开发。
* [Gitblit](https://github.com/gitblit-org/gitblit)：Gitblit是一个开源、纯Java Git解决方案，用于管理、查看和服务Git仓库。

#### Git工具

* [Gitiles](https://github.com/google/gitiles)：Gitiles是一个简单的Git仓库浏览器，基于JGit构建，由Google开源。
* [Copybara](https://github.com/google/copybara)：Copybara是Google内部使用的工具，用于在仓库之间转换和移动代码。
* [BFG Repo-Cleaner](https://github.com/rtyley/bfg-repo-cleaner)：BFG是git-filter-branch的更简单、更快速的替代方案，用于清除Git仓库历史记录中的不良数据。
* [RepoSense](https://github.com/reposense/RepoSense)：RepoSense是Git仓库的贡献分析工具。
* [Giter8](https://github.com/foundweekends/giter8)：Giter8是一个命令行工具，用于从GitHub或任何其他Git仓库上发布的模板生成文件和目录。
* [GitHub Search](https://github.com/seart-group/ghs)：用于从GitHub爬取、存储和呈现项目以及与其相关的任何统计信息的平台，由瑞士卢加诺的意大利大学软件研究所开源。
* [Coming](https://github.com/SpoonLabs/coming)：Coming是一个用于挖掘Git仓库的工具，由法国国立计算机及自动化研究院、里尔大学开源。
* [SCM Manager](https://github.com/scm-manager/scm-manager)：共享和管理Git、Mercurial和Subversion仓库的最简单方法。
* [MOE](https://github.com/google/MOE)：MOE是一个用于同步、翻译和清理源代码仓库的系统，由Google开源。

#### Git API

* [Github Java Client](https://github.com/spotify/github-java-client)：Spotify开源的Github API的Java客户端。
* [Jcabi Github](https://github.com/jcabi/jcabi-github)：GitHub API的Java面向对象包装器，带有整个GitHub API的假实现。
* [GitLab4J](https://github.com/gitlab4j/gitlab4j-api)：GitLab4J API提供了功能齐全且易于使用的Java库，用于通过GitLab REST API使用GitLab仓库。
* [Github Java API](https://github.com/hub4j/github-api)：该库定义了GitHub API的面向对象表示。
* [Java Gitlab API](https://github.com/timols/java-gitlab-api)：用Java编写的Gitlab API包装器。
* [Tea4j](https://codeberg.org/gitnex/tea4j-autodeploy)：适用于Gitea API的Java SDK。
* [Bitbucket REST](https://github.com/cdancy/bitbucket-rest)：使用Bitbucket REST API的客户端库。

#### 语义版本控制

* [JSemVer](https://github.com/zafarkhaja/jsemver)：Java SemVer是语义版本控制规范的Java实现。
* [Semver4j](https://github.com/vdurmont/semver4j)：一个处理版本的轻量级Java库，它遵循语义版本控制规范的规则，提供多种版本控制模式。
* [Semver4j](https://github.com/semver4j/semver4j)：Semver4j是一个轻量级Java库，可帮助你处理版本，它遵循语义版本控制规范的规则。
* [Kotlin Semver](https://github.com/z4kn4fein/kotlin-semver)：适用于Kotlin Multiplatform的语义版本控制库。
* [JGitVer](https://github.com/jgitver/jgitver)：基于JGit的库，用于从Git树计算SemVer兼容版本。
* [Version Compare](https://github.com/G00fY2/version-compare)：适用于Android、Java和Kotlin的轻量级库，用于比较版本字符串。
* [Semantic Version](https://github.com/skuzzle/semantic-version)：Java的快速单类语义版本实现。
* [Nyx](https://github.com/mooltiverse/nyx)：Nyx是一个强大、灵活且可配置性极高的语义发布工具。
* [Semantic Versioning](https://github.com/jeluard/semantic-versioning)：Semantic Versioning是一个Java库，允许验证(使用字节码检查)库版本号是否遵循语义版本控制定义的语义版本控制原则。
* [Reckon](https://github.com/ajoberstar/reckon)：用于从Git仓库推断下一个版本的API。

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
* [Yammer Collections](https://github.com/yammer/yammer-collections)：Yammer开发的集合工具库，建立在Guava和标准集合库之上。
* [Dexx Collections](https://github.com/andrewoma/dexx)：Dexx Collections是Scala不可变、持久集合类到纯Java的移植。
* [Primitive Collections](https://github.com/Speiger/Primitive-Collections)：Primitive Collections是一个原始集合库，可减少内存使用并提高性能。
* [Capsule](https://github.com/usethesource/capsule)：Capsule旨在成为Java 11+的成熟不可变集合库。
* [LMAX Collections](https://github.com/LMAX-Exchange/LMAXCollections)：由英国外汇交易公司LMAX开发的高性能集合库。
* [Paguro](https://github.com/GlenKPeterson/Paguro)：JVM的泛型、空安全、不可变集合和函数式转换。
* [LambdaJ](https://github.com/mariofusco/lambdaj)：LambdaJ允许以伪函数和静态类型的方式操作集合。
* [Persistent Collections](https://github.com/pmem/pcj)：Java的持久集合库，由Intel开发。
* [Jcabi Immutable](https://github.com/jcabi/jcabi-immutable)：该模块包含真正不可变的对象集合，包括Array、ArraySet和ArrayMap。
* [IceFig](https://github.com/WorksApplications/icefig)：受到Ruby和Scala等其他流行语言的启发，IceFig旨在弥补缺失的功能。
* [KeptCollections](https://github.com/anthonyu/KeptCollections)：KeptCollections是一个Java Collections框架中数据结构的直接替代库。
* [Coollection](https://github.com/19WAS85/coollection)：一种在Java中操作集合的很酷的方法。
* [Pure4J](https://github.com/pure4j/pure4j)：Java语言的编译时纯度和不变性语义。
* [Exchange Collections](https://github.com/exchange-core/collections)：Exchange Collections是一个开源高性能Java集合项目。
* [Solid](https://github.com/konmik/solid)：Solid是一个用于数据处理的Android库。

## 数组库

* [Bytes](https://github.com/patrickfav/bytes-java)：Bytes是一个实用程序库，可以轻松地在Java中创建、解析、转换、验证和转换字节数组。
* [Viktor](https://github.com/JetBrains-Research/viktor)：Viktor使用Java Vector API在Kotlin中实现了NumPy Ndarray功能的受限子集，由JetBrains开源。
* [Hiphip](https://github.com/plumatic/hiphip)：Hiphip是Clojure的一个数组库，提供了优雅的原始数组的快速数学方法。
* [JLargeArrays](https://gitlab.com/visnow.org/JLargeArrays)：JLargeArrays是一个纯Java的一维数组库，最多可以存储2的63次方个元素，由华沙大学开源。

## 泛型库

* [TypeTools](https://github.com/jhalterman/typetools)：一个简单、零依赖的类型处理库，支持Java 1.6+和Android。
* [ClassMate](https://github.com/FasterXML/java-classmate)：ClassMate是一个零依赖Java库，用于准确内省类型信息，包括可靠解析类(“类型”)和成员(字段、方法和构造函数)的泛型类型声明。
* [Generics Resolver](https://github.com/xvik/generics-resolver)：Java泛型运行时解析器。
* [GeantyRef](https://github.com/leangen/geantyref)：Java中与泛型相关的反射的小型库。
* [TypeBuilder](https://github.com/ikidou/TypeBuilder)：TypeBuilder是一个用于生成泛型的简易构建器。
* [Reified](https://github.com/Auties00/Reified)：Reified是Java 11及更高版本的注解，受到Kotlin中的reified关键字的启发。

## 函数式编程

* [Vavr](https://github.com/vavr-io/vavr)：Vavr是Java 8的对象功能语言扩展，旨在减少代码行数并提高代码质量。
* [Arrow](https://github.com/arrow-kt/arrow)：Arrow是Kotlin中类型化函数式编程的库。
* [JavaTuples](https://github.com/javatuples/javatuples)：JavaTuples提供一组允许你使用元组的Java类。
* [Functional Java](https://github.com/functionaljava/functionaljava)：Function Java是一个促进Java函数式编程的开源库。
* [Apache Commons Functor](https://github.com/apache/commons-functor)：Commons Functor库定义了通用函子和函子相关的接口、实现和实用程序。
* [Cyclops](https://github.com/aol/cyclops)：用于构建现代Java 8应用程序的强大流和函数数据类型，由AOL开源。
* [Totallylazy](https://github.com/bodar/totallylazy)：TotallyLazy补充了标准库，如持久数据结构、解析器组合器等。
* [Underscore Java](https://github.com/javadev/underscore-java)：Underscore.js的Java版本。
* [Purefun](https://github.com/tonivade/purefun)：Java函数式编程库。
* [DataEnum](https://github.com/spotify/dataenum)：DataEnum允许你在Java中使用代数数据类型，由Spotify开源。
* [Pragmatic](https://github.com/siy/pragmatica)：在实践中应用实用函数式Java方法所需的最小Java类集。
* [HighJ](https://github.com/highj/highj)：HighJ试图克服Java缺乏高阶类型多态性的问题，并将几个众所周知的类型类(包括Applicative、Monad和Foldable)和数据结构从Haskell转换为Java。
* [Vallang](https://github.com/usethesource/vallang)：Vallang是JVM上高度集成且大部分封闭的相互递归基本数据类型的集合。
* [Fluent](https://github.com/rogerkeays/fluent)：Fluent允许你像调用对象方法一样调用静态Java方法。
* [Jamaica](https://www.patreon.com/Jamaica440)：Java的一种方言，添加了被Oracle拒绝的流行功能。
* [JKScope](https://github.com/evpl/jkscope)：受Kotlin启发的Java作用域函数。
* [KindedJ](https://github.com/KindedJ/KindedJ)：KindedJ提供一组通用接口，为使用JVM中基于证据的高级类型模拟的所有项目提供跨库和跨语言支持。
* [Functional Utils](https://github.com/solita/functional-utils)：Java的函数工具库。

#### 函数式异常处理

* [Throwing Function](https://github.com/pivovarit/throwing-function)：支持受检异常的Java 8函数接口+适配器。
* [Kotlin Result](https://github.com/michaelbull/kotlin-result)：一个多平台的结果单子，用于建模成功或失败。
* [Result4j](https://github.com/sviperll/result4j)：Result4j提供了类似于Rust中的Result类型的Result类，允许返回成功结果或返回某种错误。
* [Fluent Result](https://github.com/gorandalum/fluent-result)：一个Java结果库，帮助你摆脱异常，实现更流式的编码风格。
* [Result](https://github.com/leakyabstractions/result)：Result的目的是为可能成功或失败的操作结果提供类型安全的封装，而不是抛出异常。
* [Fugue](https://bitbucket.org/atlassian/fugue)：Fugue提供补充Google Guava库的函数结构，包括Option、Either、Pair和其他类似有用的类，由Atlassian开源。
* [NoException](https://github.com/robertvazan/noexception)：NoException是Java异常处理程序的函数式编程库。
* [Try](https://github.com/lambdista/try)：Java的Try-Success-Failure Scala API的实现。
* [Unchecked](https://github.com/rogerkeays/unchecked)：Unchecked允许你将Java的受检异常视为非受检异常。
* [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow)：SneakyThrow是一个用于忽略受检异常的Java库。
* [Faux Pas](https://github.com/zalando/faux-pas)：Faux Pas是一个简化Java函数式编程错误处理的库，由Zalando开源。
* [Either](https://github.com/jbock-java/either)：Java的函数式错误处理库。
* [RxEither](https://github.com/eleventigers/rxeither)：RxJava的Either类型。
* [Catch Exception](https://github.com/Codearte/catch-exception)：Catch Exception库在单行代码中捕获异常，并使它们可用于进一步分析。
* [Maybe](https://github.com/JoseLion/maybe)：Maybe是一个类似于java.util.Optional的单子包装器，但意图不同。
* [Dichotomy](https://github.com/xyzsd/dichotomy)：Java的Result、Either、Try和Maybe类型的单子类型。
* [Either.Java](https://github.com/spencerwi/Either.java)：Java的“Either a b”的右偏实现，使用Java 8进行映射/折叠和类型推断。
* [Ambivalence](https://github.com/poetix/ambivalence)：Java 8的Either类型。
* [Better Java Monads](https://github.com/jasongoodwin/better-java-monads)：这个库是在Java 8成为GA之后立即构建的，以帮助填补一些空白(Try、Futures.sequence)。
* [Throwing Lambdas](https://github.com/fge/throwing-lambdas)：用于在函数式接口中使用的方法/接口/Lambda的包装器，抛出受检异常。
* [ThrowingStream](https://github.com/JeffFaer/ThrowingStream)：该项目是java.util.stream及其各种支持接口的替代API，允许抛出受检异常。

#### Stream工具库

* [StreamEx](https://github.com/amaembo/streamex)：StreamEx是对Java Stream API的增强库。
* [Parallel Collector](https://github.com/pivovarit/parallel-collectors)：Parallel Collectors是一个工具包，可使用Stream API简化Java中的并行收集处理。
* [Lightweight Stream API](https://github.com/aNNiMON/Lightweight-Stream-API)：Java 8中的Stream API在Java 7及更低版本的迭代器上重写。
* [Kool](https://github.com/davidmoten/kool)：java.util.stream.Stream替代方案(仅同步)，可重用、更快、更多操作符、更易于使用。
* [Streams Utils](https://github.com/JosePaumard/streams-utils)：Streams Utils是一组基于Java 8 Stream编写的操作，它允许一些Java 8中不可用的基本操作。
* [Streams](https://github.com/palantir/streams)：用于处理Java 8 Stream的实用程序，Palantir开源。
* [Protonpack](https://github.com/poetix/protonpack)：Java Stream API的实用工具库。
* [Mug](https://github.com/google/mug)：Google开源的一个小型Java 8工具库，与Guava(BiStream、Substring、MoreStreams、Parallelizer)互补。
* [CombinatoricsLib 3](https://github.com/dpaukov/combinatoricslib3)：适用于Java 8+的组合对象流生成器。
* [Stream Utils](https://github.com/Conductor/stream-utils)：该库包含处理Stream的常用实用程序。
* [Gatherers4j](https://github.com/tginsberg/gatherers4j)：适用于Java 23+的有用的流收集器(自定义中间操作)库。
* [More Gatherers](https://github.com/pivovarit/more-gatherers)：此库旨在通过提供一组Gatherers来更灵活地从流中收集数据。
* [Packrat](https://github.com/jhspetersson/packrat)：Packrat是一个Java库，它为Stream API提供了各种Gatherer实现。
* [Streamplify](https://github.com/beryx/streamplify)：该库的目标是提供有用的Java 8流并帮助你构建允许高效并行处理的新流。
* [Seq](https://github.com/wolray/seq)：提供一个强大而完备的流式编程API，并为Java添加类似生成器的编程机制。
* [StreamLine](https://github.com/YunaBraska/streamline)：StreamLine是一种增强型Java Stream API，针对并发处理进行了优化，充分利用了Project Loom虚拟线程的强大功能。
* [UnixStream](https://github.com/fmbenhassine/unix-stream)：UnixStream是Java 8 Stream API的扩展，用于以Unix方式处理数据管道。
* [LazySeq](https://github.com/nurkiewicz/LazySeq)：Java 8的惰性序列实现。

#### Lambda扩展

* [jOOL](https://github.com/jOOQ/jOOL)：jOOL为Java 8 Lambda提供了一些有用的扩展。
* [Bijection](https://github.com/twitter/bijection)：Bijection是一种可逆函数，可以在两种类型之间来回转换，并约定通过双射进行往返将带回原始对象，由Twitter开发。
* [Functions](https://github.com/mintern-java/functions)：Functions为每个可能的0到3个参数的函数提供@FunctionalInterface。
* [Functional](https://github.com/io-fairy/functional)：Functional提供更简单、更好用的Java函数式编程接口。
* [Lambda](https://github.com/palatable/lambda)：Lambda的诞生是因为希望使用其他语言中惯用的一些相同的规范函数和函数模式，并使它们可用于Java。
* [More Lambdas](https://github.com/PhantomThief/more-lambdas-java)：Java 8的一些有用的Lambda实现。
* [Koryphe](https://github.com/gchq/koryphe)：Koryphe是一个可扩展函数库，用于基于Java Function API过滤、聚合和转换数据，由英国政府通讯总部开源。
* [FunctionalJ](https://github.com/NawaMan/FunctionalJ)：FunctionalJ是一个用Java编写函数式代码的库。

#### LINQ

* [LINQ](https://github.com/timandy/linq)：LINQ到对象转换的Java库。
* [ExoQuery](https://github.com/ExoQuery/ExoQuery)：Kotlin多平台语言集成查询。
* [JINQ](https://github.com/vivekragunathan/JINQ)：JINQ是一个极简的Java库，模仿.NET LINQ。
* [Jpropel](https://github.com/nicholas22/jpropel-light)：Jpropel Light是一个Java库，具有完整的LINQ支持、具体化的泛型集合和简洁的单行代码。
* [Linq4j](https://github.com/julianhyde/linq4j)：LINQ的Java实现库。
* [Android LINQ](https://github.com/zbra-dev/android-linq)：Android LINQ是受C# LINQ库启发的集合操作实用程序的一小部分。
* [Linq.J](https://github.com/erupts/Linq.J)：Linq.J是一个基于Linq理念的Java库。

#### 模式匹配

* [Derive4j](https://github.com/derive4j/derive4j)：Derive4j是一个Java 8注解处理器，用于派生代数数据类型构造函数、模式匹配等。
* [JPML](https://github.com/klappdev/jpml)：JPML是一个Java模式匹配库。
* [ADT4J](https://github.com/sviperll/adt4j)：该库为Java实现了代数数据类型。
* [Motif](https://github.com/johnlcox/motif)：Motif在Java 8中提供类似Scala的模式匹配。
* [Typeof](https://github.com/nurkiewicz/typeof)：Java 8中的instanceof运算符和访问者模式替代品。
* [SuitCase](https://github.com/d-plaindoux/suitcase)：SuitCase是一个方便的Java库，专用于使用模式匹配机制进行对象操作。
* [Procrastination](https://github.com/gdejohn/procrastination)：Procrastination是一个小型、简单的库，将函数式编程的优势引入Java 11。

#### 尾调用

* [JVM Tail Recursion](https://github.com/Sipkab/jvm-tail-recursion)：Java字节码中尾递归调用的优化器库。
* [Tail](https://github.com/nrktkt/tail)：Java的简单尾调用优化。

#### 定理证明

* [Aya](https://github.com/aya-prover/aya-dev)：Aya是一种编程语言和交互式证明助手，专为类型导向编程和形式化数学而设计。
* [Arend](https://github.com/JetBrains/arend-lib)：Arend是一个基于同伦类型论的定理证明器，由JetBrains开源。
* [Jape](https://github.com/RBornat/jape)：Jape是一个可配置的证明计算器，支持推理系统中形式证明的交互式发现。

## 字节码操作

* [ASM](https://gitlab.ow2.org/asm/asm)：ASM是一个Java字节码操作框架，它能用来动态生成类或者增强既有类的功能。
* [Byte Buddy](https://github.com/raphw/byte-buddy)：Byte Buddy是一个代码生成和操作库，用于在Java应用程序运行时创建和修改Java类，而无需编译器的帮助。
* [JDK ClassFile](https://openjdk.org/jeps/457)：JDK提供的用于解析、生成和转换Java字节码文件的标准API。
* [Apache Commons BCEL](https://github.com/apache/commons-bcel)：Commons BCEL旨在为用户提供一种便捷的方式来分析、创建和操作Java字节码文件。
* [Javassist](https://github.com/jboss-javassist/javassist)：Javassist使Java字节码操作变得简单，它是Java中用于编辑字节码的类库，由东京⼯业⼤学开源。
* [CGLIB](https://github.com/cglib/cglib)：CGLIB是一个功能强大、高性能和高质量的代码生成库。
* [ByteX](https://github.com/bytedance/ByteX)：ByteX是一个基于Android Gradle Transform API和ASM的字节码插件平台，由字节开源。
* [Dexmaker](https://github.com/linkedin/dexmaker)：Dexmaker是用于针对Android的Dalvik VM进行编译或运行时代码生成的实用程序，由LinkedIn开源。
* [Allocation Instrumenter](https://github.com/google/allocation-instrumenter)：Allocation Instrumenter是使用java.lang.instrument API和ASM编写的Java代理，由Google开源。
* [Mixin](https://github.com/SpongePowered/Mixin)：Mixin是一个使用ASM的Java特征/混合框架，并通过一组可插入的内置或用户提供的服务挂钩到运行时类加载过程。
* [ByteKit](https://github.com/alibaba/bytekit)：Java字节码工具包，由阿里开发。
* [ProGuard](https://github.com/Guardsquare/proguard-core)：ProGuard是一个免费的库，用于读取、分析、修改和写入Java字节码文件，由GuardSquare开源。
* [Titan Dex](https://github.com/baidu/titan-dex)：Titan-Dex是面向Android Dalvik(ART)字节码格式的操纵框架，可以在二进制格式下实现修改已有的类，或者动态生成新的类，由百度开源。
* [DroidAssist](https://github.com/didi/DroidAssist)：DroidAssist是一个轻量级的Android字节码编辑插件，基于Javassist对字节码操作，由滴滴开源。
* [Jitescript](https://github.com/qmx/jitescript)：用于字节码生成的Java API。
* [InjKit](https://github.com/facebookincubator/InjKit)：InjKit是一个基于ASM库的字节码操作框架，由Facebook开发。
* [Perses](https://github.com/nick-kanakis/perses)：Perses允许你在字节码级别动态注入故障/延迟，无需添加任何依赖项或重新启动/部署目标应用程序。
* [Maker](https://github.com/cojen/maker)：Maker库是一个轻量级、功能齐全的低级动态Java字节码生成器，其设计易于使用。
* [Ja Netfilter](https://gitee.com/ja-netfilter/ja-netfilter)：Java Instrumentation框架。
* [Bytecode](https://github.com/airlift/bytecode)：Bytecode是一个用于生成JVM字节码的高级Java库。
* [Serp](https://serp.sourceforge.net/)：Serp是一个用于操作Java字节码的开源框架。
* [Gizmo](https://github.com/quarkusio/gizmo)：Gizmo旨在简化字节码生成，Quarkus大量使用它。
* [ClassTransform](https://github.com/Lenni0451/ClassTransform)：ClassTransform是一个使用ASM的轻量级注入库。
* [YABR](https://github.com/Tonic-Box/YABR)：ASM、Javassist及其他字节码库的全面替代方案。

## 反编译

* [JADX](https://github.com/skylot/jadx)：JADX是一个Dex到Java反编译器。
* [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer)：Bytecode Viewer是一个轻量级用户友好的Java/Android字节码查看器、反编译器等。
* [JD GUI](https://github.com/java-decompiler/jd-gui)：JD GUI是一个独立的图形实用程序，可从class文件中显示Java源代码。
* [Recaf](https://github.com/Col-E/Recaf)：Recaf是一个易于使用的现代Java字节码编辑器，可以抽象出Java程序的复杂性。
* [ClassyShark](https://github.com/google/android-classyshark)：ClassyShark是一款面向Android开发人员的独立二进制检查工具，由Google开源。
* [JClasslib](https://github.com/ingokegel/jclasslib)：JClasslib是一个工具，可以可视化已编译的Java类文件和所包含的字节码的各个方面。
* [GDA](https://github.com/charles2gan/GDA-android-reversing-Tool)：GDA是一款强大的Dalvik字节码反编译器。
* [Luyten](https://github.com/deathmarine/Luyten)：Procyon的开源Java反编译器GUI。
* [JDecode](http://www.jdecode.net/)：国产Java反编译工具，高达99%以上的反编成功率，最全面的Java语法特性支持。
* [Classpy](https://github.com/zxh0/classpy)：Classpy是一个GUI工具，用于研究Java类文件、Lua二进制块、Wasm二进制代码和其他二进制文件格式。
* [JD Core](https://github.com/java-decompiler/jd-core)：JD Core是一个独立的Java库，包含Java Decompiler项目的Java反编译器。
* [JD Core Java](https://github.com/nviennot/jd-core-java)：Java反编译器JD Core库。
* [JD CLI](https://github.com/intoolswetrust/jd-cli)：JD CLI是JD Core项目的简单命令行包装器。
* [Jar Analyzer](https://github.com/jar-analyzer/jar-analyzer)：Jar Analyzer是一个分析Jar文件的GUI工具。
* [ClassViewer](https://github.com/ClassViewer/ClassViewer)：ClassViewer是一个轻量级的Java类文件查看器。
* [Jar Explorer](https://github.com/javalite/jar-explorer)：这是一个桌面Swing应用程序，它将递归扫描目录并一次性索引大量JAR文件。
* [JADXecute](https://github.com/LaurieWired/JADXecute)：JADXecute是JADX的一个插件，通过添加动态代码执行功能来增强其功能。
* [Decompiler](https://github.com/sotasan/decompiler)：Decompiler是一个GUI应用程序，允许你使用各种反编译器浏览Java包。
* [Vineflower](https://github.com/Vineflower/vineflower)：Vineflower是一种现代通用JVM语言反编译器，专注于提供最佳的质量、速度和可用性。
* [Fernflower](https://github.com/JetBrains/fernflower)：Fernflower是第一个实际工作的Java分析反编译器，也可能是一般高级编程语言的分析反编译器，由JetBrains开源。
* [Friday](https://github.com/zifeihan/friday)：Friday是一个Java实时反编译工具。
* [Class Visualizer](https://github.com/jonatan-kazmierczak/class-visualizer)：Class Visualizer是一个免费交互式类图生成器。
* [JODE](https://jode.sourceforge.io/)：JODE是一个包含Java反编译器和优化器的Java包。
* [Malimite](https://github.com/LaurieWired/Malimite)：Malimite是一款iOS反编译器，旨在帮助研究人员分析和解码IPA文件。
* [ABC Decompiler](https://github.com/ohos-decompiler/abc-decompiler)：ABC Decompiler是基于JADX和ABCDE实现的鸿蒙abc/方舟字节码反编译工具。
* [Jar Explorer](http://dst.in.ua/jarexp/index.html?l=en)：Jar Explorer是一个用于浏览Java库(称为JAR、WAR、EAR、APK、AAR和ZIP文件)的GUI工具。
* [Classyshark Bytecode Viewer](https://github.com/borisf/classyshark-bytecode-viewer)：Java/Kotlin编译代码查看器。
* [CFR](https://github.com/leibnitz27/cfr)：CFR可以很好地将class文件从其他JVM语言转回Java。
* [UnLuac](https://github.com/HansWessels/unluac)：UnLuac是Lua 5.1的反编译器，它在使用标准Lua编译器编译的Lua块上运行。
* [MinecraftDecompiler](https://github.com/MaxPixelStudios/MinecraftDecompiler)：MinecraftDecompiler是一个有用的工具/库，可以通过流行的映射和各种反编译器来解混淆和反编译Minecraft(或任何jar文件)。
* [JStudio](https://github.com/Tonic-Box/JStudio)：JStudio是一个用于分析、反编译和转换Java字节码的Java逆向工程和静态分析IDE。

## 代码混淆

* [ProGuard](https://github.com/Guardsquare/proguard)：ProGuard是一个免费的Java字节码收缩器、优化器、混淆器和预验证器。
* [Simplify](https://github.com/CalebFenton/simplify)：Simplify是一个Android虚拟机和反混淆器。
* [ClassFinal](https://gitee.com/roseboy/classfinal)：ClassFinal是一款Java class文件安全加密工具，支持直接加密jar包或war包，无需修改任何项目代码，兼容Spring框架；可避免源码泄漏或字节码被反编译。
* [Deobfuscator](https://github.com/java-deobfuscator/deobfuscator)：Deobfuscator旨在对大多数商用Java混淆器进行反混淆。
* [DashO](https://www.preemptive.com/products/dasho/)：DashO的目标是让混淆和应用程序强化变得比以往更容易。
* [Zelix](https://zelix.com/)：Zelix可保护你的Java代码免遭反编译和逆向工程。
* [JBCO](http://www.sable.mcgill.ca/JBCO/)：JBCO是一款Java字节码混淆器，由麦吉尔大学开源。
* [Black Obfuscator](https://github.com/CodingGay/BlackObfuscator)：Black Obfuscator是一款针对Android APK Dex文件的混淆器，它可以帮助开发者通过控制流扁平化来保护源代码，并使分析实际程序控制流变得困难。
* [Skidfuscator](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator)：Skidfuscator是一个概念验证混淆工具，旨在利用SSA形式来优化和混淆Java字节码代码流。
* [Radon](https://github.com/ItzSomebody/radon)：Radon是一个磨损的Java字节码混淆器。
* [Caesium](https://github.com/sim0n/Caesium)：Cesium是一个强大的Java字节码混淆器。
* [Avaj](https://github.com/cg-dot/avaj)：Avaj是一个Java混淆器。
* [Paramorphism](https://paramorphism.dev/)：Paramorphism是一个快速、现代的混淆器，支持Java 8到13、Kotlin和其他JVM语言。
* [YGuard](https://github.com/yWorks/yGuard)：YGuard是yWorks推出的与Ant和Gradle配合使用的开源Java混淆工具。
* [CAFEDOOD](https://github.com/Col-E/CAFED00D)：CAFEDOOD是一个专注于混淆支持的类库。
* [Jar Protect](https://gitee.com/chejiangyi/jar-protect)：Jar Protect是一个jar加密加壳工具，对class文件进行加密防护，对Properties、YAML等配置文件进行加密，避免反编译破解。
* [Simple String Obfuscator](https://github.com/shamanland/simple-string-obfuscator)：Simple String Obfuscator可以隐藏真实的字符串常量以防止反编译。
* [Branchlock](https://branchlock.net/)：Branchlock为Java桌面应用程序、Android应用程序以及Kotlin和Groovy等JVM语言的二进制文件提供混淆。
* [Allatori](https://allatori.com/)：Allatori是第二代Java混淆器，它为你的知识产权提供全方位的保护。
* [SpecialSource](https://github.com/md-5/SpecialSource)：SpecialSource是jar混淆映射的自动生成器和重命名器。
* [AabResGuard](https://github.com/bytedance/AabResGuard)：AabResGuard是一款由抖音Android团队提供支持的资源混淆工具。
* [Native Obfuscator](https://github.com/radioegor146/native-obfuscator)：用于JNI的Java class到cpp转换器。
* [DProtect](https://github.com/open-obfuscator/dProtect)：DProtect是Proguard的扩展，具有增强的代码混淆功能。
* [Bozar](https://github.com/vimasig/Bozar)：Bozar是一个带GUI的Java字节码混淆器。
* [Threadtear](https://github.com/GraxCode/threadtear)：Threadtear是一个多功能的Java反混淆工具。
* [QProtect](https://mdma.dev/)：QProtect是第一个提供自定义变压器支持的混淆器。
* [BisGuard](https://www.bisguard.com/)：BisGuard是一个商业的Java反混淆工具。
* [ClassGuard](https://zenofx.com/classguard/)：ClassGuard是一个防止Java反编译的工具，由Zenofx开发。
* [SandMark](http://sandmark.cs.arizona.edu/)：SandMark是亚利桑那大学开发的一款工具，用于Java字节码的软件水印、防篡改和代码混淆。
* [Stringer](https://jfxstore.com/stringer/)：Stringer可保护Java应用程序二进制文件(JAR、Java 9模块、OSGI、WAR、EAR、Eclipse RCP)免遭逆向工程和修改。
* [Obfuscator](https://github.com/superblaubeere27/obfuscator)：Obfuscator是一个GUI Java混淆器。
* [JObfuscator](https://www.pelock.com/products/jobfuscator)：JObfuscator是Java语言的源代码混淆器。
* [Enigma](https://github.com/FabricMC/Enigma)：Enigma是用于Java字节码反混淆的工具。
* [JMD](https://github.com/yocontra/JMD)：JMD是一个通用的Java字节码反混淆工具。
* [Gruntpocalypse](https://github.com/SpartanB312/Grunt)：Gruntpocalypse是一个用Kotlin编写的JVM字节码混淆器，具有30多种功能。
* [Java Obfuscator](https://github.com/alpheratzteam/obfuscator)：用于保护Java应用程序的混淆器。
* [Deobfuscator](https://github.com/narumii/Deobfuscator)：Java反混淆器。
* [Jar Obfuscator](https://github.com/jar-analyzer/jar-obfuscator)：Jar Obfuscator是一个Jar/Class文件混淆工具。
* [JNIC](https://jnic.dev/)：强大的Java原生混淆器。
* [JNT2](https://exile.club/product/jnt)：JNT2是一个功能强大的软件，它使用Java本机接口将JVM字节码转换为C。
* [Masxinlingvonta](https://github.com/superblaubeere27/masxinlingvonta)：将Java字节码编译为LLVM IR和本机代码。
* [Protector4J](https://protector4j.com)：保护Java代码免于反编译，这是VLINX公司的商业产品。
* [qProtect](https://qtechnologies.dev/)：提供自定义转换器支持的Java混淆器。
* [Class Obfuscator](https://github.com/4ra1n/class-obf)：Class Obf是一个Class文件混淆工具，支持方法名/字段名/参数名引用分析和重命名混淆方式。
* [Java Humanify](https://github.com/Initial-One/Java-humanify)：使用LLM对Java代码进行反混淆。
* [Paranoid](https://github.com/MichaelRocks/paranoid)：适用于安卓应用的字符串混淆器。
* [JSource Obfuscator](https://github.com/luelueking/JSource-Obfuscator)：Java源代码混淆器。
* [McDeob](https://github.com/ShaneBeeStudios/McDeob)：McDeob是一款用于Minecraft服务器/客户端jar的重新映射和去混淆工具。
* [Class Winter](https://github.com/Dulcinea-J/class-winter-master)：Class Winter是一款Java字节码文件安全加密工具。

## 逆向工程

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra)：Ghidra是一个由美国国家安全局研究局创建和维护的软件逆向工程框架。
* [JEB Community Edition](https://www.pnfsoftware.com/jeb/community-edition)：JEB是一款针对Android应用程序和本机机器代码的反汇编和反编译软件。
* [Apktool](https://github.com/iBotPeaches/Apktool)：Apktool是一款用于对第三方、封闭式、二进制Android应用程序进行逆向工程的工具。
* [BinAbsInspector](https://github.com/KeenSecurityLab/BinAbsInspector)：BinAbsInspector是一款用于自动化逆向工程和扫描二进制文件漏洞的静态分析器，是腾讯科恩实验室孵化的长期研究项目。
* [JByteMod](https://github.com/GraxCode/JByteMod-Beta)：JByteMod是一个多功能字节码编辑器，具有语法突出显示、实时反编译和方法绘图功能。
* [BinDiff](https://github.com/google/bindiff)：BinDiff是一款开源的二进制文件比较工具，可以帮助漏洞研究人员和工程师快速找到反汇编代码中的差异和相似之处，由Google开源。
* [Cafebabe](https://github.com/GraxCode/Cafebabe)：Cafebabe是一款用户友好的Java字节码编辑器，适合字节码爱好者和专业人士。
* [Super JADX](https://github.com/pkilller/super-jadx)：Super JADX是一个JADX插件，添加了逆向工程的新功能。
* [BinNavi](https://github.com/google/binnavi)：BinNavi是一个二进制分析IDE，允许检查、导航、编辑和注释控制流图以及反汇编代码的调用图，由Google开源。
* [Helios](https://github.com/helios-decompiler/standalone-app)：Helios是一款一体化Java逆向工程工具，它具有与最新反编译器集成的功能。
* [Kaiju](https://github.com/cmu-sei/kaiju)：Kaiju是Ghidra软件逆向工程套件的二进制分析框架扩展，由CMU开源。
* [ABCDE](https://github.com/Yricky/abcde)：ABCDE是一个使用Kotlin编写的OpenHarmony逆向工具包。
* [SkidSuite](https://github.com/GenericException/SkidSuite)：SkidSuite 3是与Java应用程序逆向工程相关的有用工具的集合。
* [Java Disassembler](https://github.com/LLVM-but-worse/java-disassembler)：JDA是一款专注、轻量且功能强大的Java静态反汇编器。

## 反向移植

* [Retrolambda](https://github.com/luontola/retrolambda)：Retrolambda允许你在Java 7、6或5上运行使用Lambda表达式、方法引用和Try-With-Resources语句的Java 8代码。
* [Jabel](https://github.com/bsideup/jabel)：以Java 8为目标时使用现代Java 9-14语法。
* [JvmDowngrader](https://github.com/unimined/JvmDowngrader)：将现代Java字节码降级为旧版本。
* [Virtual Thread Bridge](https://github.com/thunkware/virtual-threads-bridge)：该库允许你在Java 8+中使用Java 21的虚拟线程API。
* [JDK Classfile Preview](https://github.com/dmlloyd/jdk-classfile-preview)：JDK Classfile API非官方反向移植到Java 17。
* [ThreeTen](https://github.com/ThreeTen/threetenbp)：ThreeTen Backport提供Java 8日期时间类到Java 6和7的向后移植。
* [ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP)：针对Android的JSR-310反向移植的改编版。
* [StreamSupport](https://github.com/stefan-zobel/streamsupport)：StreamSupport是适用于Android和Java 6或7用户的Java 8 java.util.function和java.util.stream API的向后移植。

## 图像处理

* [Thumbnailator](https://github.com/coobird/thumbnailator)：Thumbnailator是一个Java缩略图生成库。
* [Thumbnails4j](https://github.com/elastic/thumbnails4j)：使用JVM生成文件缩略图的项目，由Elastic开源。
* [Aspose.Imaging](https://products.aspose.com/imaging/java/)：Aspose.Imaging是一个库，为你提供用于图像和照片处理的高级工具。
* [Grid](https://github.com/guardian/grid)：Grid是卫报的图像管理系统，它提供了访问组织的媒体的通用且快速的体验，并以经济实惠的方式使用它来生成高质量的内容。
* [Apache Commons Imaging](https://github.com/apache/commons-imaging)：Commons Imaging是一个纯Java图像库。
* [SmartCropper](https://github.com/pqpo/SmartCropper)：SmartCropper是一个简单易用的智能图片裁剪库，适用于身份证，名片，文档等照片的裁剪。
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)：TwelveMonkeys ImageIO通过javax.imageio.*包的插件为Java平台提供扩展图像文件格式支持。
* [ImgLib2](https://github.com/imglib/imglib2)：ImgLib2是一个通用的多维图像处理库。
* [ImgScalr](https://github.com/rkalla/imgscalr)：ImgScalr是一个简单高效(硬件加速)的图片缩放最佳实践类库，纯Java 2D实现。
* [Marvin](https://github.com/gabrielarchanjo/marvin-framework)：Marvin图像处理框架提供实时处理图像和视频的功能。
* [Picasso](https://github.com/square/picasso)：Picasso是一个强大的Android图像下载和缓存库，由Square开源。
* [EasyImage](https://github.com/aviyehuda/EasyImage)：EasyImage可让你执行所有基本图像操作-转换、裁剪、调整大小、旋转、翻转等。
* [JMagick](https://github.com/techblue/jmagick)：JMagick是ImageMagick的开源Java接口。
* [Jrawio](https://github.com/tidalwave-it/jrawio-src)：Java Image I/O API的服务提供者，用来处理数码相机拍摄的RAW格式的图片，包括NEF、CRW、CR2、PEF、SRF、MRW。
* [JJIL](https://github.com/litmanowicziv/jjil)：JJIL是一个Java图像处理库，它包括图像处理架构和60多个用于各种图像处理任务的例程。
* [JDeli](https://www.idrsolutions.com/jdeli/)：JDeli是一个企业级Java图像库，可以轻松地在Java中读取、写入、转换、操作和处理HEIC和其他图像文件格式，这是IDRsolutions的商业产品。
* [Image4j](https://github.com/imcdonagh/image4j)：Image4j库允许你以100%纯Java读取和写入某些图像格式。
* [Pollexor](https://github.com/square/pollexor)：Thumbor图像服务的Java客户端，允许你使用流式的API以富有表现力的方式构建URI，由Square开源。
* [JAI ImageIO](https://github.com/jai-imageio/jai-imageio-core)：Java高级图像I/O工具项目。
* [LEADTOOLS](https://www.leadtools.com/sdk/java)：LEADTOOLS是一个Java图像处理库，提供了文档清理、医学图像增强、边缘检测、颜色转换和校正、降噪等功能。
* [SimpleImage](https://github.com/alibaba/simpleimage)：SimpleImage是阿里开源的一个Java图片处理的类库，可以实现图片缩略、水印等处理。
* [OptimizedImageEnhance](https://github.com/26hzhang/OptimizedImageEnhance)：该库包含一组由Java实现的图像/视频增强方法，用于解决一些常见任务，例如去雾、去噪、水下后向散射消除、低照度增强、特征化、平滑等。
* [Scrimage](https://github.com/sksamuel/scrimage)：Scrimage是一个用于图像操作的不可变、函数式、高性能的JVM库。
* [CV4j](https://github.com/imageprocessor/cv4j)：CV4j是用纯Java实现的高质量、实时的图像处理和机器学习库。
* [ImgLib](https://github.com/nackily/imglib)：ImgLib是一个轻量级的Java图像处理库，致力于简化对图像的常见处理。
* [SimpleITK](https://simpleitk.org/)：SimpleITK是一个图像分析工具包，拥有大量支持常规过滤操作、图像分割和配准的组件。
* [GIFEncoder](https://github.com/square/gifencoder)：GIFEncoder是一个实现GIF89a规范的纯Java库，由Square开源。
* [AndroidLibyuvImageUtils](https://github.com/myrao/AndroidLibyuvImageUtils)：Android上的图像处理库。
* [ImageCombiner](https://gitee.com/dromara/image-combiner)：ImageCombiner是一个专门用于Java服务端图片合成的工具，由dromara社区开源。
* [ImageTool](https://gitee.com/xshuai/imagetool)：一个简单的图片处理工具，支持图片压缩、图片水印、图片裁剪、图片旋转、图片格式转换等功能。
* [LIRE](https://github.com/dermotte/LIRE)：LIRE是一个用于基于内容的图像检索的开源库，这意味着你可以使用LIRE来实现搜索看起来相似的图像的应用程序。
* [Fiji](https://github.com/fiji/fiji)：Fiji是一个图像处理包，捆绑了许多有助于科学图像分析的插件，由威斯康星大学麦迪逊分校等机构开源。
* [CognitiveJ](https://github.com/CognitiveJ/cognitivej)：CognitiveJ是一个开源流式Java API，可管理和编排Java应用程序与Microsoft的Cognitive机器学习和图像处理库之间的交互，并允许你查询和分析图像。
* [JImageHash](https://github.com/KilianB/JImageHash)：JImageHash是一个完全用Java编写的高性能感知图像指纹库。
* [Image Scaling](https://github.com/mortennobel/java-image-scaling)：该库的目的是提供更好的图像缩放选项。
* [Eclipse ImageN](https://github.com/eclipse/imagen)：ImageN项目提供了一个可扩展的按需图像处理库，对光栅大小或波段数量没有人为限制。
* [Blurry](https://github.com/wasabeef/Blurry)：Blurry是一个简单的Android模糊库。
* [Cantaloupe](https://github.com/cantaloupe-project/cantaloupe)：Cantaloupe是一个开源动态图像服务器，用于按需生成高分辨率源图像的衍生品。
* [Open Imaging](https://github.com/DhyanB/Open-Imaging)：Open Imaging是用于图像创建和处理的工具和库。
* [ImageIO Ext](https://github.com/geosolutions-it/imageio-ext)：ImageIO Ext是一个开源项目，为标准Oracle Java Image I/O项目提供扩展、修复和改进。
* [SCIFIO](https://github.com/scifio/scifio)：SCIFIO是一个可扩展的Java框架，用于读取和写入图像，特别是N维科学图像。
* [Java Image Filters](http://www.jhlabs.com/ip/filters/index.html)：Java Image Filters是由Jhlabs开发的一组用来处理Java图像的类库，提供各种常用的图像处理效果，例如反转色、扭曲、水波纹、凹凸、黑白效果等等数十种效果。
* [JAI EXT](https://github.com/geosolutions-it/jai-ext)：JAI EXT是一个开源项目，旨在扩展JAI API，由GeoSolutions开源。
* [Animated GIF Library](https://github.com/rtyley/animated-gif-lib-for-java)：Java的动画GIF库。
* [Color Thief](https://github.com/SvenWoltmann/color-thief-java)：从图像中抓取主色或代表性调色板。
* [WebP ImageIO](https://github.com/sejda-pdf/webp-imageio)：适用于Google WebP图像格式的Java Image I/O读取器和写入器。
* [Vips FFM](https://github.com/lopcode/vips-ffm)：用于Java/JVM项目中图像处理的快速、安全、完整的libvips绑定。
* [JVips](https://github.com/criteo/JVips)：JVips是使用JNI的libvips的Java包装器。
* [Sand](https://github.com/Jomes/sand)：Sand是Android库，它使用JNI实现Sobel算子图像边缘检测。
* [NightMonkeys](https://github.com/gotson/NightMonkeys)：ImageIO插件集合，新增对较新图像格式的支持。
* [Blurhash](https://github.com/vanniktech/blurhash)：Kotlin多平台库，可在你的Android应用程序、iOS/Mac应用程序和JVM后端中使用Blurhash。
* [AVIF/HEIF Coder](https://github.com/awxkee/avif-coder)：该库提供了简单的接口来为Android解码或编码(创建)AVIF和HEIF图像。
* [OpenSlide](https://github.com/openslide/openslide-java)：OpenSlide是一个用于读取整张幻灯片图像文件的C库，这是OpenSlide的Java绑定。
* [Lept4J](https://github.com/nguyenq/lept4j)：Leptonica图像处理库的JNA Java包装器。
* [Identicon](https://github.com/donpark/identicon)：原始Identicon Java和Canvas实现。

#### 图像元数据

* [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor)：Metadata Extractor是一个用于从媒体文件中读取元数据的Java库。
* [ICAFE](https://github.com/dragon66/icafe)：用于读取、写入、转换和操作图像和元数据的Java库。
* [Kim](https://github.com/Ashampoo/kim)：Kim是一个用于读取和写入图像元数据的Kotlin多平台库。

#### 图像比较

* [Image Comparison](https://github.com/romankh3/image-comparison)：Image Comparison可以比较2个相同大小的图像，并通过绘制矩形直观地显示差异。
* [Image Similarity](https://github.com/nivance/image-similarity)：计算图片之间的相似度。

#### PNG库

* [Pngtastic](https://github.com/depsypher/pngtastic)：Pngtastic是一个纯Java PNG图像优化和操作库。
* [PNGJ](https://github.com/leonbloy/pngj)：PNGJ是一个纯Java库，用于高性能读写PNG图像。

#### SVG库

* [JFreeSVG](https://github.com/jfree/jfreesvg)：JFreeSVG是一个用于Java平台的图形库，允许你使用标准Java2D绘图API生成SVG格式的内容。
* [Apache Batik](https://github.com/apache/xmlgraphics-batik)：Batik是一个基于Java的工具包，适用于处理SVG格式的图像各种目的，例如观看、生成或操纵。
* [SVG Salamander](https://github.com/blackears/svgSalamander)：SVG Salamander是一个用于Java的SVG引擎，设计小巧、速度快。
* [VectorGraphics2D](https://github.com/eseifert/vectorgraphics2d)：VectorGraphics2D提供Java Graphics2D接口的实现，并以各种矢量文件格式导出图形。
* [JSVG](https://github.com/weisJ/jsvg)：JSVG是一个使用AWT图形的SVG用户代理。
* [WebVector](https://github.com/radkovo/WebVector)：WebVector是一个HTML到SVG、PDF或PNG转换器。
* [WMF2SVG](https://github.com/hidekatsu-izuno/wmf2svg)：适用于Java的WMF到SVG转换工具和库。
* [Safe SVG](https://github.com/bgalek/safe-svg)：简单且轻量级的库，有助于以安全方式验证SVG文件。

#### TIFF库

* [TIFF Java](https://github.com/ngageoint/tiff-java)：TIFF是一个用于读写标记图像文件格式文件的Java库，由美国国家地理空间情报局开源。
* [AlgART TIFF](https://github.com/Daniel-Alievsky/algart-tiff)：AlgART TIFF是一个Java库，提供TIFF文件的完整读/写支持。

#### 验证码

* [AJ Captcha](https://gitee.com/anji-plus/captcha)：AJ-Captcha行为验证码，包含滑动拼图、文字点选两种方式，UI支持弹出和嵌入两种方式。
* [EasyCaptcha](https://gitee.com/ele-admin/EasyCaptcha)：Java图形验证码，支持GIF、中文、算术等类型，可用于Java Web、Java SE等项目。
* [Tianai Captcha](https://gitee.com/tianai/tianai-captcha)：非常好用的开源行为验证码(滑块验证码、点选验证码、行为验证码、旋转验证码， 滑动验证码)。
* [Happy Captcha](https://gitee.com/ramostear/Happy-Captcha)：Happy Captcha是一款易于使用的Java验证码软件包。
* [Kaptcha](https://github.com/penggle/kaptcha)：Kaptcha是一个可高度配置的实用验证码生成工具。
* [JCaptcha](https://mvnrepository.com/artifact/com.octo.captcha/jcaptcha/1.0)：一个可以生成图片、声音式验证码的Java库。
* [Captcha Plus](https://github.com/xingyuv/captcha-plus)：Captcha Plus行为验证码，包含滑动拼图、文字点选两种方式，UI支持弹出和嵌入两种方式。
* [NanoCaptcha](https://github.com/logicsquad/nanocaptcha)：NanoCaptcha是一个用于生成图像和音频验证码的Java库。

#### 二维码库

* [QR Code Generator](https://github.com/nayuki/QR-Code-generator)：Java、TypeScript/JavaScript、Python、Rust、C++、C语言的高质量QR码生成器库。
* [AwesomeQRCode](https://github.com/sumimakito/AwesomeQRCode)：适用于Android的超棒二维码生成器。
* [QArt4J](https://github.com/dieforfree/qart4j)：提供ASCII Art输出图像的QR码生成器。
* [QRGen](https://github.com/kenglxn/QRGen)：基于ZXING构建的简单的Java二维码生成API。
* [ZXingGenerator](https://github.com/vivian8725118/ZXingGenerator)：花式二维码生成库，提供了6种样式。
* [Visual QR Code](https://gitee.com/boat824109722/visual-qr-code)：Visual QR Code可以创建出设置了虚拟背景图片的二维码。
* [QRext4j](https://gitee.com/BYSRepo/qrext4j)：QRext4j是一个简单易用的二维码生成工具，可自定义二维码颜色和码眼样式。
* [QRCode Kotlin](https://github.com/g0dkar/qrcode-kotlin)：QRCode Kotlin旨在提供一种简单、直接且可自定义的二维码创建方式，尤其是在后端。
* [FiwanQRCode](https://gitee.com/frogchou/FiwanQRCode)：飞网QR二维码生成器，用户可以通过这个工具生成QR码。
* [WeChatQRCode](https://github.com/jenly1314/WeChatQRCode)：WeChatQRCode是一个基于OpenCV开源的微信二维码引擎移植封装的二维码识别库。
* [QRCode Generator](https://github.com/kazuhikoarase/qrcode-generator)：以JavaScript、Java等语言实现的QR码生成器。
* [QRGenerator](https://github.com/androidmads/QRGenerator)：QR生成器库并将QR码保存为图像。
* [QRCode Utils](https://github.com/binarywang/qrcode-utils)：二维码生成工具。
* [EMV QRCode](https://github.com/mvallim/emv-qrcode)：基于Java的EMV二维码生成器和解析器(MPM、CPM)。
* [SwissQRBill](https://github.com/manuelbl/SwissQRBill)：用于生成和解码瑞士二维码钞票的开源Java库。

#### 条形码库

* [ZXing](https://github.com/zxing/zxing)：ZXing是一个用Java实现的开源、多格式1D/2D条形码图像处理库。
* [ZXingLite](https://github.com/jenly1314/ZXingLite)：ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。
* [Aspose.BarCode](https://products.aspose.com/barcode/java/)：Aspose.BarCode是一个强大且可靠的API，为Java应用程序提供条形码生成和识别功能。
* [Spire.Barcode](https://www.e-iceblue.com/Introduce/barcode-for-java.html)：Spire.Barcode是一款专业的条形码组件，专为开发人员在Java应用程序上生成、读取和扫描1D和2D条形码而设计。
* [Barbecue](https://barbecue.sourceforge.net/)：Barbecue是一个开源的Java库，它提供了创建用于在Java应用程序中打印和显示的条形码的方法。
* [Barcode4J](https://github.com/SingingBush/barcode4j)：Barcode4J是一个用Java编写的灵活的条形码生成器。
* [Okapi Barcode](https://github.com/woo-j/OkapiBarcode)：Okapi Barcode是一款完全用Java编写的开源条形码生成器，支持50多种编码标准，包括所有ISO标准。
* [Barcode Java](https://github.com/barnhill/barcode-java)：该库旨在为开发人员提供一个简单的类，供开发人员在需要从一串数据生成条形码图像时使用。
* [Barcode Lib4J](https://github.com/vws-java/Barcode-Lib4J)：Barcode Lib4J是一个成熟且久经考验的Java库，用于绘制、打印和保存一维和二维条形码为矢量(PDF、EPS、SVG)和光栅图像(PNG、BMP、JPG)。
* [QRose](https://github.com/alexzhirkevich/qrose)：Compose Multiplatform的条码生成库。

#### 水印

* [AndroidWM](https://github.com/huangyz0918/AndroidWM)：一个支持隐写技术的Android图像水印库。
* [OpenStego](https://github.com/syvaidya/openstego)：OpenStego是一款隐写术应用程序。
* [RubberStamp](https://github.com/vinaygaba/RubberStamp)：RubberStamp是一个Android库，可让你轻松地为图像添加水印。
* [WaterMarkIt](https://github.com/OlegCheban/WaterMarkIt)：轻量级、与框架无关的Java库，用于向各种文件类型(包括PDF和图像)添加水印。
* [Innamark](https://github.com/FraunhoferISST/Innamark)：Innamark项目提供隐写/水印解决方案。

## 压缩库

这里列出了不同的数据压缩算法、存档文件操作库。

#### 数据压缩

* [Brotli](https://github.com/google/brotli)：Brotli是一种通用无损压缩算法，它结合使用LZ77算法的现代变体、霍夫曼编码和二阶上下文建模来压缩数据，其压缩率可与目前最好的通用压缩方法相媲美，由Google开源。
* [LZ4](https://github.com/lz4/lz4-java)：LZ4是无损压缩算法，提供每核大于500MB/s的压缩速度，可通过多核CPU进行扩展。
* [Zstd](https://github.com/luben/zstd-jni)：Zstd是一种新的无损压缩算法，它可以为你的标准压缩需求提供良好的压缩比和速度。
* [JavaFastPFOR](https://github.com/lemire/JavaFastPFOR)：Java中的简单整数压缩库。
* [LZF Compressor](https://github.com/ning/compress)：LZF Compressor是一个用于编码和解码LZF格式数据的Java库。
* [HPACK](https://github.com/twitter/hpack)：HPACK库提供将header列表压缩为header块的支持，由Twitter开源。
* [Snappy Java](https://github.com/xerial/snappy-java)：Snappy是Google开发的快速C++压缩器/解压缩器，这是Snappy的Java移植。
* [LZMA](https://github.com/jponge/lzma-java)：该库为在Java平台上运行的应用程序提供LZMA压缩。
* [Brotli4j](https://github.com/hyperxpro/Brotli4j)：Brotli4j为Java提供Brotli压缩和解压缩。
* [JBrotli](https://github.com/MeteoGroup/jbrotli)：Brotli的Java绑定。
* [AirCompressor](https://github.com/airlift/aircompressor)：该库包含用纯Java编写的Zstandard(Zstd)、LZ4、Snappy和LZO的实现，它们通常比原生库的JNI包装器快10-40%。
* [LZO](https://github.com/shevek/lzo-java)：LZO压缩算法的纯Java实现。
* [MiGz](https://github.com/linkedin/migz)：MiGz是一个支持多线程的使用GZIP格式的压缩库，由LinkedIn开发。
* [Compress](https://gitee.com/yu120/compress)：基于Gzip、Deflate、LZ4、Snappy、LZO等算法实现数据压缩，主要用于RPC通讯数据的压缩。
* [Kanzi](https://github.com/flanglet/kanzi)：Kanzi是一个用Java实现的现代、模块化、可扩展、高效的无损数据压缩器。
* [LibDeflate Java](https://github.com/astei/libdeflate-java)：该项目为libdeflate库提供了安全、高性能的JNI绑定。
* [Qat Java](https://github.com/intel/qat-java)：Qat Java库使用英特尔QuickAssist技术QATzip库提供加速压缩和解压缩。
* [CafeUndZopfli](https://github.com/eustas/CafeUndZopfli)：CafeUndZopfli是一个用Java编写的压缩库。
* [Atlassian Gzip Filter](https://bitbucket.org/atlassian/atlassian-gzipfilter)：Atlassian Gzip Filter通过使用Servlet过滤器透明地为你的Web应用程序添加gzip过滤功能。
* [Ziplet](https://github.com/ziplet/ziplet)：Ziplet可以基于HttpServletRequest中的HTTP请求头，压缩写入HttpServletResponse的数据，或解压从请求中读取的数据。
* [XZ Java](https://github.com/tukaani-project/xz-java)：XZ Java是纯Java中XZ数据压缩的完整实现。
* [WebGraph](https://github.com/vigna/webgraph)：WebGraph是一个旨在研究网络图的图压缩框架，它利用现代压缩技术提供了管理非常大的图形的简单方法，由米兰大学开发。
* [JVM Brotli](https://github.com/nixxcode/jvm-brotli)：适用于Brotli压缩格式的轻量级跨平台Java库。
* [Simple DEFLATE Decompressor](https://github.com/nayuki/Simple-DEFLATE-decompressor)：该项目是DEFLATE压缩格式的清晰实现。
* [Gorilla TSC](https://github.com/burmanm/gorilla-tsc)：Facebook Gorilla论文中时序压缩方法的实现。

#### 文件压缩

* [Zip4j](https://github.com/srikanth-lingala/zip4j)：Zip4j是最全面的ZIP文件/流Java库。
* [ZT ZIP](https://github.com/zeroturnaround/zt-zip)：Java ZIP库，构建于java.util.zip包之上。
* [Apache Commons Compress](https://github.com/apache/commons-compress)：Commons Compress定义了一个用于处理压缩和存档格式的API。
* [Aspose.ZIP](https://products.aspose.com/zip/java/)：Aspose.ZIP是一个针对标准ZIP格式的灵活的文档压缩和档案操作API。
* [Zip4jvm](https://github.com/oleg-cherednik/zip4jvm)：Zip4jvm是用于处理Zip文件的Java库。
* [ZIP Forge](https://github.com/helpermethod/zip-forge)：ZIP Forge是一个小型的、格式化程序友好的Java DSL，用于创建ZIP文件。
* [LLJ-ZIP](https://github.com/Col-E/LL-Java-Zip)：LLJ-ZIP是一个用于可查找文件的ZIP格式读取器，可以容忍前导和尾随垃圾，并容忍针对前导垃圾调整内部偏移。
* [Archive Patcher](https://github.com/google/archive-patcher)：Archive Patcher是一个开源项目，允许对ZIP存档进行节省空间的修补，由Google开源。
* [ParallelGZIP](https://github.com/shevek/parallelgzip)：ParallelGZIP包含一个并行GZIP实现，它是标准java.util.zip类的高性能替代品。
* [JZlib](https://github.com/ymnk/jzlib)：JZlib是zlib在纯Java中的重新实现。
* [Junrar](https://github.com/junrar/junrar)：纯Java RAR库。
* [JArchiveLib](https://github.com/thrau/jarchivelib)：JArchiveLib是一个简单的Java归档和压缩库，它在Apache Commons Compress之上提供了一个精简且易于使用的API层。
* [JTar](https://github.com/kamranzafar/jtar)：JTar是一个简单的Java Tar库，它提供了一种使用IO流创建和读取Tar文件的简单方法。
* [7 Zip JBinding](https://github.com/borisbrodski/sevenzipjbinding)：7 Zip JBinding是7-Zip免费压缩/解压缩库的免费跨平台Java绑定。
* [7 Zip JBinding Android](https://github.com/omicronapps/7-Zip-JBinding-4Android)：7 Zip JBinding Java包装器的Android库版本。
* [ShrinkWrap](https://github.com/shrinkwrap/shrinkwrap)：ShrinkWrap是一个Java库，用于创建Java存档，例如JAR、WAR、EAR和RAR，由JBoss开源。

#### 图像压缩

* [Compressor](https://github.com/zetbaitsu/Compressor)：Compressor是一款轻量级且功能强大的Android图像压缩库。
* [CompressHelper](https://github.com/nanchen2251/CompressHelper)：文件、图片压缩工具类。
* [AdvancedLuban](https://github.com/shaohui10086/AdvancedLuban)：AdvancedLuban是一个方便简单的Android图像压缩工具库。
* [SiliCompressor](https://github.com/Tourenathan-G5organisation/SiliCompressor)：SiliCompressor是一个功能强大、灵活且易于使用的Android视频和图像压缩库。
* [TurboJPEG](https://github.com/libjpeg-turbo/libjpeg-turbo/tree/main/java)：TurboJPEG是一个JPEG图像编解码器，它使用SIMD指令来加速x86、x86-64、Arm、PowerPC和MIPS系统上的基线JPEG压缩和解压缩，以及x86、x86-64和Arm系统上的渐进式JPEG压缩。
* [Compressor](https://github.com/Shouheng88/Compressor)：适用于Android的高级图像压缩库。

## 反射库

* [Reflections](https://github.com/ronmamo/reflections)：Reflections会扫描项目的类路径元数据并为其建立索引，从而允许在运行时对类型系统进行反向传递查询。
* [jOOR](https://github.com/jOOQ/jOOR)：jOOR是用于反射的流式API库，可以以更直观的方式访问Class类结构。
* [ReflectASM](https://github.com/EsotericSoftware/reflectasm)：ReflectASM是一个非常小的Java库，它通过使用代码生成来提供高性能反射。
* [Objenesis](https://github.com/easymock/objenesis)：Objenesis是一个专门用于在创建对象时绕过构造函数的库。
* [Mirror](https://github.com/Genymobile/mirror)：Java和Android的轻松反射。
* [Mirror](https://github.com/Moderocky/Mirror)：一个智能且快速的Java反射API替代方案。
* [Reflekt](https://github.com/JetBrains-Research/reflekt)：Reflekt是一个编译时反射库，它利用标准反射方法的流程，可以在编译时根据某些条件查找类、对象或函数，由JetBrains开源。
* [Intimate](https://github.com/eleme/Intimate)：Intimate提供了友好的API让Java反射的使用更加简单平滑，由饿了么开源。
* [Apache Commons ClassScan](https://commons.apache.org/sandbox/commons-classscan)：ClassScan可以提供有关运行时可用的所有类的信息，无论该类是否已加载。
* [FEST Reflect](https://github.com/alexruiz/fest-reflect)：FEST Reflect提供了直观、紧凑且类型安全的流式API，使Java反射非常易于使用：不再需要强制转换、检查异常、PriviledgedActions或setAccessible调用。
* [Lambda Factory](https://github.com/Hervian/lambda-factory)：Lambda Factory是一个Java实用程序项目，它提供了基于反射的方法调用的快速替代方案。
* [Reflection Util](https://github.com/cronn/reflection-util)：简化Java反射常见用例的工具类。
* [BlackReflection](https://github.com/CodingGay/BlackReflection)：BlackReflection提供了一系列API，方便使用Java反射。
* [Reflection ReMapper](https://github.com/jpenilla/reflection-remapper)：Reflection ReMapper是一个简化反射调用的库，特别支持重映射的环境。
* [Reflection No Reflection](https://github.com/stephanenicolas/reflection-no-reflection)：Reflection No Reflection是一个概念验证，旨在创建一个与Java核心反射API 100%兼容的API，但不包含任何反射。
* [Fast Reflection](https://github.com/daniellansun/fast-reflection)：Fast Reflection是Java反射的另一种极其快速的替代方案，使动态调用与直接调用同样高效。
* [Paranamer](https://github.com/paul-hammant/paranamer)：Paranamer是一个允许在运行时访问非私有方法和构造函数的参数名称的库，由ThoughtWorks开源。
* [Mirror](https://github.com/vidageek/mirror)：Java反射API上的简单DSL层。
* [Jeflect](https://github.com/RomanQed/jeflect)：一组旨在与反射交互并加速反射的实用程序。
* [Reflecto](https://github.com/cariochi/reflecto)：Reflecto是一个功能强大的Java反射库，旨在简化深度反射任务。
* [Permit Reflection](https://github.com/nqzero/permit-reflect)：允许Java 11反射访问。
* [InvokeBinder](https://github.com/headius/invokebinder)：此库旨在提供更友好的DSL来绑定方法句柄。
* [KavaRef](https://github.com/HighCapable/KavaRef)：KavaRef是一个使用Kotlin实现的现代化Java反射API。
* [Reflect](https://github.com/Lenni0451/Reflect)：一个反射库，其中包含一些有用的方法来绕过Java中的反射限制。

## 注解库

* [JetBrains Annotations](https://github.com/JetBrains/java-annotations)：Annotations是一组可在基于JVM的语言中使用的Java注解，由JetBrains开源。
* [Atlassian Annotations](https://bitbucket.org/atlassian/atlassian-annotations)：用于声明API状态和属性的标准注解类型，由Atlassian开源。
* [Javac Warning Annotation](https://github.com/pushtorefresh/javac-warning-annotation)：轻量级javac @warning注解。

## 接口文档

* [Swagger](https://github.com/swagger-api/swagger-core)：Swagger是OpenAPI规范的Java实现。
* [Knife4j](https://gitee.com/xiaoym/knife4j)：Knife4j是一个集Swagger 2和OpenAPI 3为一体的增强解决方案。
* [Taxi](https://github.com/taxilang/taxilang)：Taxi是一种用于记录数据和API契约的语言。
* [SmallRye OpenAPI](https://github.com/smallrye/smallrye-open-api)：SmallRye OpenAPI是Eclipse MicroProfile OpenAPI的一个实现，由RedHat开源。
* [Zally](https://github.com/zalando/zally)：Zally是一个简约、易于使用的OpenAPI 2和3 Linter。
* [Swaggy Swagger](https://github.com/Swaggy-Swagger/swagger-custom-java)：Swaggy Swagger是一个库，旨在增强API文档工具Swagger的功能和用户体验。
* [Swagger Coverage](https://github.com/viclovsky/swagger-coverage)：基于OAS(Swagger) v2和v3生成API测试覆盖率全貌的工具。
* [Swagger Spring Boot Starter](https://github.com/battcn/swagger-spring-boot)：Swagger Spring Boot Starter是一款建立在Swagger基础之上的工具包，利用Spring Boot自动装配的特性，简化了传统Swagger的繁琐配置。
* [Swagger Butler](https://github.com/dyc87112/swagger-butler)：Swagger Butler是一个基于Swagger与Zuul构建的API文档汇集工具。

#### 规范优先

* [Swagger Codegen](https://github.com/swagger-api/swagger-codegen)：Swagger Codegen允许根据OpenAPI规范自动生成API客户端库(SDK生成)、服务器存根和文档。
* [TypeSpec](https://github.com/microsoft/typespec)：TypeSpec是一种用于定义云服务API和形状的语言，由Microsoft开发。
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)：OpenAPI Generator允许在给定OpenAPI规范的情况下自动生成API客户端库(SDK生成)、服务器存根、文档和配置。
* [OpenAPI JSON Schema Generator](https://github.com/openapi-json-schema-tools/openapi-json-schema-generator)：OpenAPI JSON Schema Generator允许自动生成API客户端库，重点关注给定OpenAPI文档的JSON模式。
* [Apigen](https://github.com/apiaddicts/apigen.springboot)：Apigen允许使用OpenAPI文件作为OpenAPI定义和数据库之间的映射工具来生成Spring Boot原型。
* [AutoRest Java](https://github.com/Azure/autorest.java)：AutoRest工具会生成用于访问RESTful Web服务的客户端库。
* [OpenAPI Processor Spring](https://github.com/openapi-processor/openapi-processor-spring)：OpenAPI Processor是一个小型框架，可以将OpenAPI YAML(或JSON)描述转换为目标格式。
* [Gradle Swagger Generator Plugin](https://github.com/int128/gradle-swagger-generator-plugin)：用于OpenAPI YAML验证、代码生成和API文档发布的Gradle插件。
* [Swagger Codegen Generators](https://github.com/swagger-api/swagger-codegen-generators)：Swagger Codegen Generators项目是Swagger Codegen 3.0.0项目在其针对特定语言或语言框架的代码生成过程中使用的一组类和模板。
* [Swagger Inflector](https://github.com/swagger-api/swagger-inflector)：该项目使用Swagger规范来驱动API实现。
* [Guardrail](https://github.com/guardrail-dev/guardrail)：Guardrail是一个代码生成工具，能够读取OpenAPI/Swagger规范文件并生成Scala和Java源代码。
* [Swagger Gradle Codegen](https://github.com/Yelp/swagger-gradle-codegen)：用于从Swagger规范文件生成网络代码的Gradle插件。
* [Swagger Codegen Maven Plugin](https://github.com/garethjevans/swagger-codegen-maven-plugin)：支持Swagger代码生成项目的Maven插件。
* [Light Codegen](https://github.com/networknt/light-codegen)：基于Rocker的代码生成器，可以用作命令行实用程序或Web服务。

#### 接口优先

* [Springfox](https://github.com/springfox/springfox)：Springfox库旨在自动生成使用Spring系列项目编写的JSON API的机器和人类可读规范。
* [SpringDoc OpenAPI](https://github.com/springdoc/springdoc-openapi)：SpringDoc OpenAPI库有助于使用Spring Boot项目自动生成API文档。
* [Spring Boot Starter Swagger](https://github.com/SpringForAll/spring-boot-starter-swagger)：该项目主要利用Spring Boot的自动配置特性来实现快速的将Swagger 2引入Spring Boot应用来生成API文档，简化原生使用Swagger 2的整合代码。
* [JApiDocs](https://github.com/YeDaxia/JApiDocs)：JApiDocs是一个Spring Boot无注解API文档生成器。
* [Spring REST Docs](https://github.com/spring-projects/spring-restdocs)：Spring REST Docs的目标是帮助你为RESTful服务生成准确且可读的文档。
* [Spring Auto REST Docs](https://github.com/ScaCap/spring-auto-restdocs)：Spring REST Docs的扩展。
* [Springwolf](https://github.com/springwolf/springwolf-core)：Springwolf是一个用于Spring Boot项目的自动化文档生成工具。
* [RESTDocs API Spec](https://github.com/ePages-de/restdocs-api-spec)：为Spring REST Docs添加API规范支持。
* [Smart Doc](https://gitee.com/TongchengOpenSource/smart-doc)：Smart Doc是一款同时支持Java REST API和Java WebSocket和Dubbo RPC接口文档生成的工具，由同程开源。
* [Doc APIs](https://gitee.com/easy-es/doc-apis)：Doc APIs是一款零侵入接口文档生成工具，由dromara社区开源。
* [Swagger Maven Plugin](https://github.com/kongchen/swagger-maven-plugin)：该插件使你的Swagger注解项目能够在Maven构建阶段生成Swagger规范和可定制的模板化静态文档。
* [OpenAPI v3 Generator Spring Boot](https://github.com/qaware/openapi-generator-for-spring)：该库在运行时自动为Spring Boot应用程序生成OpenApi v3规范。
* [SpringDoc OpenAPI Maven Plugin](https://github.com/springdoc/springdoc-openapi-maven-plugin)：该插件的目的是在运行时生成JSON和YAML OpenAPI描述。
* [xDoc](https://gitee.com/treeleaf/xDoc)：基于Java注释生成接口文档，对代码无侵入，无需注解，纯代码注释。
* [Ktor OpenAPI Generator](https://github.com/papsign/Ktor-OpenAPI-Generator)：Ktor OpenAPI Generator是一个库，用于在你路由Ktor应用程序时自动生成描述符。
* [SpringDoc OpenAPI Gradle Plugin](https://github.com/springdoc/springdoc-openapi-gradle-plugin)：此插件允许你从Gradle构建中为Spring Boot应用程序生成OpenAPI 3规范。
* [Swagger Maven Plugin](https://github.com/openapi-tools/swagger-maven-plugin)：该插件旨在使用Swagger Core库从基于JAX-RS的REST服务生成OpenAPI文档，并尽可能减少更改。
* [Restdocs Spec](https://github.com/BerkleyTechnologyServices/restdocs-spec)：一个使用Spring Restdocs生成Open API和Postman Collection规范的Maven插件。
* [OpenAPI Maven Plugin](https://github.com/kbuntrock/openapi-maven-plugin)：OpenAPI Maven Plugin分析REST控制器Java类并生成相应的OpenAPI 3.0.3文档，它支持Spring MVC、Javax RS和Jakarta RS注解。
* [JSONDoc](https://github.com/fabiomaffioletti/jsondoc)：JSONDoc是一个Java库，可用于构建RESTful服务的文档。
* [Swagger Play](https://github.com/swagger-api/swagger-play)：这是一个在Play框架控制器中支持Swagger注解的模块。
* [Swagger Socket](https://github.com/swagger-api/swagger-socket)：Swagger Socket协议允许在WebSocket协议之上执行任何现有的REST资源。
* [Swagger Dubbo](https://github.com/Sayi/swagger-dubbo)：Dubbo的Swagger服务文档。
* [Swagger Akka HTTP](https://github.com/swagger-akka-http/swagger-akka-http)：Swagger Akka HTTP为Akka-Http API带来了Swagger支持。
* [Swagger Gradle Plugin](https://github.com/gigaSproule/swagger-gradle-plugin)：支持JAX-RS和Spring MVC来生成Swagger文档的Gradle构建插件。
* [Wirespec](https://github.com/flock-community/wirespec)：Wirespec是一款现代化的工具，它通过简化API的设计、文档编写和实现流程来增强软件开发。

#### 模式解析

* [Swagger Parser](https://github.com/swagger-api/swagger-parser)：Swagger Parser可以将JSON或YAML格式的OpenAPI定义解析为Java POJO的Swagger Core表示形式，返回任何验证警告/错误。
* [OpenAPI4J](https://github.com/openapi4j/openapi4j)：OpenAPI 3解析器、JSON模式和请求验证器。
* [KaiZen OpenApi Parser](https://github.com/RepreZen/KaiZen-OpenApi-Parser)：KaiZen OpenApi Parser是一个基于Java的OpenAPI 3.0验证解析器，提供高度统一的读/写编程API。

#### 模式比较

* [OpenAPI Diff](https://github.com/OpenAPITools/openapi-diff)：用于比较两个OpenAPI规范的实用程序。
* [AssertJ Swagger](https://github.com/RobWin/assertj-swagger)：AssertJ Swagger是一个AssertJ库，它将契约优先的Swagger YAML/JSON文件与代码优先的Swagger JSON输出进行比较。
* [Swagger Diff](https://github.com/Sayi/swagger-diff)：比较两个Swagger API规范(1.x或v2.0)，并将差异呈现到HTML文件或Markdown文件中。

#### 模式校验

* [Swagger Validator Badge](https://github.com/swagger-api/validator-badge)：该项目在网站上显示“valid swagger”徽章，支持Swagger/OpenAPI 2.0和OpenAPI 3.x规范。
* [OpenAPI Style Validator](https://github.com/OpenAPITools/openapi-style-validator)：可定制的样式验证器，可确保你的OpenAPI规范遵循你组织的标准。
* [Swagger Brake](https://github.com/redskap/swagger-brake)：Swagger Brake是一个简单的工具，可以验证新版本的API是否会破坏现有版本。
* [Swagger Schema Validator](https://github.com/bjansen/swagger-schema-validator)：该库根据Swagger 2规范的definitions部分中定义的模型校验JSON对象。
* [OpenAPI Spring WebFlux Validator](https://github.com/cdimascio/openapi-spring-webflux-validator)：一个友好的Kotlin库，使用OpenAPI 3或Swagger 2规范来验证API端点。

#### 规范转换

* [Swagger2Word](https://github.com/JMCuixy/swagger2word)：Swagger2Word是一个Swagger API文档转Word文档的工具项目。
* [Swagger2Markup](https://github.com/Swagger2Markup/swagger2markup)：Swagger到AsciiDoc或Markdown转换器，通过将手写文档与自动生成的API文档相结合，简化最新RESTful API文档的生成。

## API管理

* [RAP](https://github.com/thx/RAP)：RAP是一种Web工具，允许开发人员快速定义和记录在典型的基于RESTful API的Web应用程序中使用的Web API，阿里开源。
* [Apigee](https://cloud.google.com/apigee)：Apigee是Google Cloud的原生API管理平台，可用于构建、管理和保护API。
* [Yaade](https://github.com/EsperoTech/yaade)：Yaade是一个开源、自托管、协作式API开发环境。
* [AgileTC](https://github.com/didi/AgileTC)：AgileTC是一个基于思维导图的具有多实时协作能力的测试用例管理平台，由滴滴开源。
* [CrapApi](https://gitee.com/CrapApi/CrapApi)：CrapApi是完全开源、免费使用的API接口管理系统、BUG管理系统。
* [XXL-API](https://github.com/xuxueli/xxl-api)：XXL-API是一个强大易用的API管理平台，提供API的管理、文档、Mock和测试等功能。
* [Apideploy](https://www.apideploy.cn/)：更高效的API生成、托管、测试与协同平台。
* [WSO2 API Manager](https://github.com/wso2/product-apim)：WSO2 API Manager是一个用于创建、管理、使用和监控Web API的强大平台。
* [Y9 API Platform](https://gitee.com/risesoft-y9/y9-interface-platform)：基于Spring Boot、Vue前后端分离的接口管理平台，由北京有生博大软件开发。
* [Apiman](https://github.com/apiman/apiman)：Apiman是一个灵活的开源API管理平台，由RedHat开源。
* [Postin](https://github.com/tiklab-project/tiklab-postin)：Postin提供API设计、调试、文档生成和Mock数据模拟等一站式解决方案。
* [EasyOpen](https://gitee.com/durcframework/easyopen)：EasyOpen是一个简单易用的接口开放平台，平台封装了常用的参数校验、结果返回等功能。
* [Torna](https://gitee.com/durcframework/torna)：Torna是一个接口文档解决方案，目标是让接口文档管理变得更加方便、快捷。
* [Gravitee](https://github.com/gravitee-io/gravitee-api-management)：Gravitee是一种灵活、轻量级且速度极快的开源解决方案，可帮助你的组织控制用户访问API的人员、时间和方式。
* [Apicurio Studio](https://github.com/Apicurio/apicurio-studio)：Apicurio Studio项目是一个独立的API设计工具，可用于创建新的或编辑现有的API设计(使用OpenAPI或AsyncAPI规范)，由RedHat开源。
* [APK](https://github.com/wso2/apk)：APK即Kubernetes API平台，这是一种尖端的API管理解决方案，旨在利用Kubernetes的强大功能来实现无缝且可扩展的部署，WSO2开源。
* [RESTFiddle](https://github.com/AnujaK/restfiddle)：适用于团队的企业级API管理平台，RESTFiddle帮助你设计、开发、测试和发布API。
* [Qi-API](https://github.com/qimu666/qi-api)：Qi-API是一个为用户和开发者提供全面API接口调用服务的平台。

## 技术文档

* [AsciidoctorJ](https://github.com/asciidoctor/asciidoctorj)：AsciidoctorJ是在JVM上运行Asciidoctor的官方库，使用AsciidoctorJ，你可以转换AsciiDoc内容或分析来自Java和其他JVM语言的已解析AsciiDoc文档的结构。
* [DocToolchain](https://github.com/docToolchain/docToolchain)：DocToolchain是一个脚本集合，可以轻松创建和维护强大的技术文档。
* [DITA-OT](https://github.com/dita-ot/dita-ot)：DITA-OT是一个开源发布引擎，用于在Darwin信息类型架构中创作的内容。
* [Orchid](https://github.com/orchidhq/Orchid)：Orchid是一个用于生成具有所有功能的项目文档网站的框架。
* [Znai](https://github.com/testingisdocumenting/znai)：Znai将人类书写的文本与代码、图形、REST API、Java文档、Doxygen等工件相结合，以创建最新、可维护、精美的用户指南和教程。

## Javadoc

* [Markdown Doclet](https://github.com/Abnaxos/markdown-doclet)：Markdown Doclet允许在Javadoc注释中使用Markdown的Doclet。
* [UMLDoclet](https://github.com/talsma-ict/umldoclet)：UMLDoclet可以在Javadoc中自动生成PlantUML图。
* [Asciidoclet](https://github.com/asciidoctor/asciidoclet)：Asciidoclet是一个基于Asciidoctor的Javadoc Doclet，它允许你使用AsciiDoc语法编写Javadoc。
* [Multiline](https://github.com/benelog/multiline)：使用Javadoc注释在Java中实现多行字符串文本。
* [TherAPI Runtime Javadoc](https://github.com/dnault/therapi-runtime-javadoc)：该库可以在运行时读取Javadoc注释。
* [Javadoc Themer](https://github.com/nisrulz/javadoc-themer)：Javadoc Themer用于为Javadoc着色。
* [Codesnippet Javadoc Doclet](https://github.com/jtulach/codesnippet4javadoc)：Codesnippet Doclet可帮助你在文档中包含真实的代码片段，确保它们始终可编译。
* [Deploy Publish JavaDoc](https://github.com/MathieuSoysal/Javadoc-publisher.yml)：自动从Java项目生成Javadoc并将其发布到GitHub Page。

## 文件操作

#### PDF库

* [Apache PDFBox](https://github.com/apache/pdfbox)：PDFBox库是一个用于处理PDF文档的开源Java工具。
* [Stirling PDF](https://github.com/Frooodle/Stirling-PDF)：Stirling PDF是一款功能强大、基于Web的本地托管PDF处理工具。
* [iText](https://github.com/itext/itext7)：iText是一个经过考验的高性能库，可创建、改编、检查和维护PDF文档。
* [Aspose.PDF](https://products.aspose.com/pdf/java/)：Aspose.PDF是一个原生库，可让开发人员为其应用程序添加PDF处理功能。
* [Spire.PDF](https://www.e-iceblue.com/Introduce/pdf-for-java.html)：Spire.PDF是一个PDF API，它使Java应用程序无需使用Adobe Acrobat即可读取、写入和保存PDF文档。
* [JPedal](https://www.idrsolutions.com/jpedal/)：JPedal是一个Java PDF库，它使Java开发人员可以轻松地在Java中处理PDF文档，这是IDRsolutions的商业产品。
* [OpenPDF](https://github.com/LibrePDF/OpenPDF)：OpenPDF是一个Java库，用于创建和编辑PDF文件。
* [PD4ML](https://pd4ml.com/)：PD4ML提供强大的工具和API，用于生成高质量、定制化、可访问的文档，用于打印和长期电子存档。
* [PDFtk Java](https://gitlab.com/pdftk-java/pdftk)：PDFtk是一款用于处理PDF文档日常事务的简单工具。
* [PDF Clown](https://pdfclown.org/)：PDF Clown是一个用于Java的通用PDF库，专注于严格执行PDF 1.7规范(ISO 32000-1)。
* [X-EasyPDF](https://gitee.com/dromara/x-easypdf)：X-EasyPDF是一个基于PDFBox/FOP二次封装的框架，由dromara社区开源。
* [PDFsam](https://github.com/torakiki/pdfsam)：PDFsam是一款用于拆分、合并、混合、旋转PDF文件和提取页面的桌面应用程序。
* [Tabula](https://github.com/tabulapdf/tabula-java)：Tabula是一个用于从PDF文件中提取表格的库。
* [Apache FOP](https://github.com/apache/xmlgraphics-fop)：FOP是由XSL-FO驱动的打印格式化程序和独立于输出的格式化程序。
* [PdfCompare](https://github.com/red6/pdfcompare)：一个简单的Java库，用于比较两个PDF文件。
* [Boxable](https://github.com/dhorions/boxable)：Boxable是一个可用于轻松在PDF文档中创建表格的库。
* [PDF Studio Viewer](https://www.qoppa.com/pdfstudioviewer/)：PDF Studio Viewer是一款可靠且易于使用的跨平台PDF阅读器。
* [EasyTable](https://github.com/vandeseer/easytable)：这是一个基于PDFBox构建的小项目，允许你以相当简单的方式创建表格。
* [Science Parse](https://github.com/allenai/science-parse)：Science Parse解析科学论文(PDF形式)并以结构化形式返回，由艾伦人工智能研究院开源。
* [Sejda](https://github.com/torakiki/sejda)：Sejda SDK是一个用Java编写的面向任务的PDF编辑SDK库。
* [TrapRange](https://github.com/thoqbk/traprange)：TrapRange是一种可用于检测表格内容并将其提取到PDF文件中的数据方法。
* [PDF-Util](https://github.com/vinsguru/pdf-util)：PDF比较工具库。
* [JSignPdf](https://github.com/intoolswetrust/jsignpdf)：JSignPdf是一个为PDF文档添加数字签名的Java应用程序。
* [Briss](https://github.com/mbaeuerle/Briss-2.0)：Briss是一个用于裁剪PDF文件的小型应用程序。
* [PDFrenderer](https://github.com/katjas/PDFrenderer)：使用Java2D将PDF文档渲染到屏幕的Java库。
* [Staplr](https://github.com/pridiltal/staplr)：该库提供了操作PDF文件的函数。
* [VeraPDF](https://github.com/veraPDF/veraPDF-library)：行业支持的开源PDF/A验证库。
* [ICEpdf](https://github.com/pcorless/icepdf)：ICEpdf是一个纯Java PDF文档渲染和查看解决方案。
* [OrsonPDF](https://github.com/jfree/orsonpdf)：OrsonPDF是一个适用于Java平台的PDF生成库，允许你使用标准Java2D绘图API(Graphics2D)创建PDF格式的内容。
* [ComPDFKit](https://github.com/ComPDFKit/compdfkit-api-java)：ComPDFKit提供强大稳定的PDF库和完整的PDF功能来构建PDF查看器和编辑器，允许预览、编辑、注释、签名、加密和解密PDF文件。
* [PDF Test](https://github.com/codeborne/pdf-test)：PDF测试库，确保你的代码生成正确的PDF，由Codeborne开发。
* [PDF Generator](https://github.com/UttamPanchasara/PDF-Generator)：PDF生成器库，可以轻松地从字符串内容或任何HTML内容创建PDF。
* [PDFExtract](https://github.com/bitextor/pdf-extract)：PDFExtract是一个PDF解析器，它将PDF内容转换并提取为HTML格式。
* [PDFLayoutTextStripper](https://github.com/JonathanLink/PDFLayoutTextStripper)：将PDF文件转换为文本文件，同时保留原始PDF的布局。
* [PDFHTML](https://github.com/itext/itext-pdfhtml-java)：PDFHTML是Java的一个iText插件，它允许你轻松地将HTML和CSS转换为符合标准的可访问、可搜索和可用于索引的PDF。
* [PDFFigures](https://github.com/allenai/pdffigures2)：PDFFigures是一个基于Scala的项目，旨在从学术文献中提取图表、图解、表格和章节标题，尤其侧重于计算机科学领域的文档，由艾伦人工智能研究院开源。
* [PDF Kit](https://github.com/superad/pdf-kit)：Java根据模板动态生成PDF文件。
* [Ghost4J](https://github.com/zippy1978/ghost4j)：Ghost4J绑定了Ghostscript C API，将Ghostscript的强大功能带入Java世界。
* [JQuickPDF](https://github.com/paohaijiao/jquick-pdf)：JQuickPDF是一个轻量级的Java库，用于从类似HTML的模板生成PDF文档，支持动态内容和丰富的样式。
* [ExtractPDF4J](https://github.com/ExtractPDF4J/ExtractPDF4J)：一个以生产为中心的Java库，用于从PDF中提取表和结构化数据。

#### Excel库

* [Apache POI](https://github.com/apache/poi)：POI是用于读写Office二进制和OOXML文件格式的Java库。
* [EasyExcel](https://github.com/alibaba/easyexcel)：EasyExcel是一个基于Java的、快速、简洁、解决大文件内存溢出的Excel处理工具，由阿里开源。
* [Apache Fesod](https://github.com/apache/fesod)：Fesod是一个用于读写Excel文件的高性能、内存高效的Java库，旨在简化开发并确保可靠性。
* [Aspose.Cells](https://products.aspose.com/cells/java/)：Aspose.Cells提供Excel文件生成、转换和操作。
* [Spire.XLS](https://www.e-iceblue.com/Introduce/xls-for-java.html)：Spire.XLS是一个专业的Java Excel API，使开发人员无需使用Microsoft Office或Microsoft Excel即可创建、管理、操作、转换和打印Excel工作表。
* [Docx4j](https://github.com/plutext/docx4j)：Docx4j是一个开源库，用于创建、编辑和保存OpenXML包，包括docx、pptx和xslx。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入导出、加密Excel等多项功能的工具包。
* [EasyPOI](https://gitee.com/wupaas/easypoi)：EasyPOI是一个POI工具库，提供了Excel的快速导入导出、Excel模板导出、Word模板导出。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：Excel4j是基于POI的Excel和Commons CSV的CSV操作组件。
* [AGEIPort](https://github.com/alibaba/AGEIPort)：AGEIPort是数字供应链孵化并在阿里内广泛使用的一套性能卓越、稳定可靠、功能丰富、易于扩展、生态完整的数据导入导出方案，由阿里开源。
* [EasyFile](https://gitee.com/openquartz/easy-file)：EasyFile是一整套Web大文件导出解决方案，可以轻松导出千万以上数据。
* [FastExcel](https://github.com/dhatim/fastexcel)：FastExcel可用于快速生成和读取大Excel文件。
* [JXLS](https://github.com/jxlsteam/jxls)：Jxls是一个小型且易于使用的Java库，用于使用Excel模板文件生成Excel报告。
* [Poiji](https://github.com/ozlerhakan/poiji)：Poiji是一个小型线程安全Java库，提供从Excel工作表到Java类的一种映射方式。
* [AutoPOI](https://github.com/jeecgboot/autopoi)：AutoPOI是Excel和Word的简易工具类，由北京国炬公司开发。
* [XresLoader](https://github.com/owent/xresloader)：XresLoader是一组用于把Excel数据结构化并导出为程序可读的数据文件的导表工具集。
* [AutoExcel](https://github.com/feng-haitao/auto-excel)：AutoExcel是Excel的快速导入和导出工具。
* [Excel Streaming Reader](https://github.com/monitorjbl/excel-streaming-reader)：使用POI的流式Excel读取器的易于使用的实现。
* [ZeroCell](https://github.com/creditdatamw/zerocell)：ZeroCell提供了一个简单的API，用于使用注解将Excel中的数据加载到POJO中，将Excel中的列映射到Java类中的字段。
* [EEC](https://github.com/wangguanquan/eec)：EEC是一款轻量且高效的Excel读写工具，它具有包体小、接入代码量少和运行时消耗资源少等优点。
* [ExcelKit](https://gitee.com/wuwenze/ExcelKit)：简单、好用且轻量级的海量Excel文件导入导出解决方案。
* [ExcelUtil](https://github.com/SargerasWang/ExcelUtil)：用于导入导出Excel的Util包，基于Java的POI。
* [POI Excel](https://gitee.com/stupid1t/poi-excel)：POI Excel是一个基于POI的Java工具，旨在简化新手在处理Excel表格时的操作。
* [Chimm.Excel](https://gitee.com/chimmhuang/chimm.excel)：Chimm.Excel是一个用Java写的Excel生成工具，基于模板操作，简单、快捷、易上手。
* [ExcelCompare](https://github.com/na-ka-na/ExcelCompare)：ExcelCompare是一个命令行工具，用于比较Excel/Open document(ods)电子表格。
* [ZK Spreadsheet](https://github.com/zkoss/zkspreadsheet)：ZK Spreadsheet是一个开源的、可嵌入的、基于Web的在线电子表格，它使用纯Java在浏览器中提供Excel的丰富功能。
* [ToolGood.Algorithm](https://github.com/toolgood/ToolGood.Algorithm)：ToolGood.Algorithm是一个功能强大、轻量级、兼容Excel公式的算法类库，旨在提高开发人员在不同业务场景中的生产力。
* [Keikai](https://github.com/keikai/dev-ref)：Keikai是一个轻松构建电子表格驱动的Web应用程序。
* [Xcelite](https://github.com/eBay/xcelite)：Xcelite是一个类似ORM的Java库，它允许你轻松地将Java Bean序列化到Excel电子表格或从Excel电子表格反序列化Java Bean，由eBay开源。
* [Java Excel API](https://jexcelapi.sourceforge.net/)：Java Excel API是一个成熟的开源Java API，使开发人员能够动态读取、写入和修改Excel电子表格。
* [HY.Common.Report](https://github.com/HY-Org/hy.common.report)：报表、Excel操作类库。
* [DsExcel Java](https://github.com/GrapeCity/DsExcel-Java)：DsExcel是一个跨平台、高速、占用空间小的电子表格API库，无需依赖Excel。
* [Excel Boot](https://github.com/programmeres/excel-boot)：Excel Boot是一款Excel导入导出解决方案组成的轻量级开源组件。
* [MemPOI](https://github.com/firegloves/MemPOI)：使用POI简化从数据库导出到Excel文件的库。
* [Excel Plus](https://github.com/hellokaton/excel-plus)：提高Excel操作库的生产力。
* [Spark Excel](https://github.com/nightscape/spark-excel)：使用Apache Spark、Spark SQL和DataFrames查询Excel文件的库。
* [Excel Spring Boot Starter](https://github.com/pig-mesh/excel-spring-boot-starter)：Excel Spring Boot Starter是一个基于FastExcel实现的Spring Boot Starter，用于简化Excel的读写操作。
* [SQLiteToExcel](https://github.com/li-yu/SQLiteToExcel)：SQLiteToExcel库集成了Apache POI和一些基本的数据库查询操作，使得SQLite和Excel之间的转换更加容易。
* [EasyExcel Encapsulation](https://github.com/HowieYuan/easyexcel-encapsulation)：EasyExcel的方法封装，快速、简单地处理Excel。
* [J-Excel](https://github.com/hyberbin/J-Excel)：万能的Excel导入导出工具。
* [Zouzhiy Excel](https://github.com/zouzhiy/zouzhiy-excel)：Zouzhiy Excel是一款Excel导入导出的轻量级工具。
* [ZzExcelCreator](https://github.com/zhouzhuo810/ZzExcelCreator)：Excel表格生成工具。
* [Spoiwo](https://github.com/norbert-radyk/spoiwo)：Spoiwo是一个用于在Scala中生成函数式电子表格的开源库。
* [XLLoop](https://github.com/poidasmith/xlloop)：XLLoop是一个开源框架，用于在集中式服务器上实现Excel用户自定义函数(UDF)。
* [SQLite2XL](https://github.com/androidmads/SQLite2XL)：这是一个轻量级库，用于将SQLite数据库转换为Excel并将Excel转换为SQLite。
* [Excel Download](https://github.com/lannstark/excel-download)：通用Excel模块，可简单、快速地实现Excel下载。
* [EasyDataBaseExport](https://github.com/Zhuoyuan1/EasyDataBaseExport)：EasyDataBaseExport是一款数据库表结构导出工具，支持MySQL、Oracle、Sqlserver、PostgreSQL、达梦、虚谷、DB2等数据库，同时支持Excel、Word、Markdown、Html、PDF文档导出。

#### CSV库

* [Apache Commons CSV](https://github.com/apache/commons-csv)：Commons CSV库提供了一个简单的接口，用于读取和写入各种类型的CSV文件。
* [AdaptiveTableLayout](https://github.com/Cleveroad/AdaptiveTableLayout)：可以读取、编辑和写入CSV文件的库。
* [MyExcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入导出、加密Excel等多项功能的工具包，支持CSV文件。
* [Super CSV](https://github.com/super-csv/super-csv)：Super CSV是一个快速、程序员友好的开源库，用于使用Java读写CSV文件。
* [FastCSV](https://github.com/osiegmar/FastCSV)：FastCSV是一个快如闪电、无依赖的Java CSV库，符合RFC标准。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：Excel4j是基于POI的Excel和Commons CSV的CSV操作组件。
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
* [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper)：SimpleFlatMapper提供了一个非常快速且易于使用的映射器。
* [CSV Validator](https://github.com/digital-preservation/csv-validator)：CSV Validator是一个CSV验证和报告工具，它实现了CSV模式语言。
* [GroovyCSV](https://github.com/xlson/groovycsv)：GroovyCSV是一个Groovy库，旨在使读写CSV数据更容易。
* [Deephaven CSV](https://github.com/deephaven/deephaven-csv)：Deephaven CSV库是一个高性能、面向列、类型推断的CSV解析器。
* [PicoCSV](https://github.com/nbbrd/picocsv)：Java的轻量级CSV库。
* [BeanIO](https://github.com/beanio/beanio)：用于从XML、CSV、分隔和固定长度流格式编组和解组Bean对象的Java库。

#### Word库

* [Aspose.Words](https://products.aspose.com/words/java/)：Aspose.Words是一个原生库，它为开发人员提供了丰富的功能来创建、编辑和转换Word、PDF、Web文档，而无需在系统上安装Microsoft Word环境。
* [Spire.Doc](https://www.e-iceblue.com/Introduce/doc-for-java.html)：Spire.Doc是一个专业的Word API，它使Java应用程序能够创建、转换、处理和打印Word文档，而无需依赖Microsoft Word。
* [POI-TL](https://github.com/Sayi/poi-tl)：POI TL是一个Word模板引擎，可以根据Word模板和数据生成新文档。
* [Docx4j](https://github.com/plutext/docx4j)：Docx4j是一个开源库，用于创建、编辑和保存OpenXML包，包括docx、pptx和xslx。
* [Docx Stamper](https://github.com/thombergs/docx-stamper)：Docx Stamper是一个用于docx文档的Java模板引擎。
* [Stencil](https://github.com/erdos/stencil)：Stencil是一个开源模板引擎，可以从JVM转换Office Open XML文档(主要是Microsoft Office Word .docx文件)。
* [Office Stamper](https://github.com/verronpro/office-stamper)：Office Stamper是一个Java模板引擎，允许在运行时动态创建DOCX文档。
* [WordGO](https://gitee.com/qiruipeng/WordGo)：让Java生成word文档更容易。
* [OfficeExport Java](https://github.com/kmood/officeexport-java)：OfficeExport Java基于Apache FreeMarker，通过极简API实现Java Bean即数据源，模板即样式的Word导出。
* [Autodoc](https://github.com/nasa/autodoc)：Autodoc旨在实现报告自动化，减轻生成常规文档所需的工作量，由NASA开源。
* [Java2word](https://github.com/leonardoanalista/java2word)：Java2word是一个无需任何特殊组件即可从Java代码生成MS Word文档的库。

#### PPT库

* [Aspose.Slides](https://products.aspose.com/slides/java/)：Aspose.Slides是一个用于演示文稿操作和管理的Java PowerPoint API。
* [Spire.Presentation](https://www.e-iceblue.com/Introduce/presentation-for-java.html)：Spire.Presentation是一个专业的PowerPoint API，它使开发人员能够在Java应用程序中创建、读取、编写、转换和保存PowerPoint文档。
* [PPTShow](https://github.com/qrpcode/pptshow)：Java生成PPT文档工具包，支持2010版PPTX新功能。
* [PPT Template](https://github.com/Coreoz/PPT-Templates)：PPT Template是一个用于生成PowerPoint演示文稿的小型模板库。

#### ODS库

* [jOpenDocument](https://www.jopendocument.org/)：用于OASIS Open Document文件操作的纯Java库。
* [SODS](https://github.com/miachm/SODS)：Java中用于处理ODS文件的简单库。
* [FastODS](https://github.com/jferard/fastods)：FastODS是一个非常快速且轻量级的库，用于在Java中创建ODS(开放文档电子表格，主要用于Calc)文件。

#### DBF库

* [JDBF](https://github.com/iryndin/jdbf)：用于读写DBF文件的Java实用程序。
* [JavaDBF](https://github.com/albfernandez/javadbf)：JavaDBF是一个用于读写XBase文件的Java库。
* [DBF](https://github.com/jamel/dbf)：用于快速读取/写入DBF文件的Java库。

#### Office库

* [JODConverter](https://github.com/jodconverter/jodconverter)：JODConverter使用LibreOffice或OpenOffice自动执行文档转换。
* [XDocReport](https://github.com/opensagres/xdocreport)：XDocReport是一个Java API，用于将使用MS Office(docx、pptx)或OpenOffice(odt)、LibreOffice(odt)创建的XML文档与Java模型合并，生成报告，并根据需要将其转换为其他格式(PDF、XHTML等)。
* [CDC](https://gitlab.com/cdc-java/cdc-office)：与Office文档相关的工具类。
* [ODF Toolkit](https://github.com/tdf/odftoolkit)：ODF Toolkit是一组Java模块，允许以编程方式创建、扫描和操作ODF文档。

#### XML库

* [Jakarta XML Binding](https://github.com/jakartaee/jaxb-api)：Jakarta XML Binding提供了API和工具来自动执行XML文档和Java对象之间的映射。
* [FlyingSaucer](https://github.com/flyingsaucerproject/flyingsaucer)：Flying Saucer是一个纯Java库，用于使用CSS 2.1布局和格式化任意格式良好的XML(或XHTML)，输出到Swing面板、PDF和图像。
* [Dom4j](https://github.com/dom4j/dom4j)：Dom4j是一个处理XML的开源框架，它与XPath集成，完全支持DOM、SAX、JAXP和Java平台(例如Java 2 Collections)。
* [XStream](https://github.com/x-stream/xstream)：XStream是一个简单的库，用于将对象序列化为XML。
* [Apache Commons JXPath](https://github.com/apache/commons-jxpath)：XPath 1.0的基于Java的实现，除了XML处理之外，还可以检查/修改Java对象图，甚至混合Java/XML结构。
* [Jackson XML](https://github.com/FasterXML/jackson-dataformat-xml)：Jackson JSON处理器的扩展，增加了对POJO序列化为XML(以及从XML反序列化)的支持，作为JSON的替代方案。
* [jOOX](https://github.com/jOOQ/jOOX)：jOOX是org.w3c.dom包的简单包装器，允许在需要DOM但过于繁琐的情况下流畅地创建和操作XML文档。
* [Apache Commons SCXML](https://github.com/apache/commons-scxml)：状态图XML引擎的Java实现。
* [Apache Commons Digester](https://github.com/apache/commons-digester)：Commons Digester包允许你配置XML到Java对象映射模块，每当识别出嵌套XML元素的特定模式时，该模块就会触发称为规则的某些操作。
* [TikXML](https://github.com/Tickaroo/tikxml)：适用于Java和Android的快速XML解析器。
* [EXIficient](https://github.com/EXIficient/exificient)：EXIficient是EXI格式规范的开源实现，由Siemens开发。
* [JDOM](https://github.com/hunterhacker/jdom)：JDOM提供了一个完整的、基于Java的解决方案，用于从Java代码访问、操作和输出XML数据。
* [XmlUtil](https://github.com/pdvrieze/xmlutil)：XmlUtil是一组支持Kotlin中的多平台XML的包。
* [Aalto XML](https://github.com/FasterXML/aalto-xml)：Aalto XML处理器是一种超高性能的下一代Stax XML处理器实现，同时实现了基本的Stax API和Stax2 API扩展。
* [Xembly](https://github.com/yegor256/xembly)：Xembly是一种类似Assembly的命令式编程语言，用于XML文档中的数据操作。
* [GsonXml](https://github.com/stanfy/gson-xml)：GsonXml是一个小型库，允许使用Google Gson库进行XML反序列化。
* [Woodstox](https://github.com/FasterXML/woodstox)：Stax XML API(javax.xml.stream)实现。
* [TagChowder](https://github.com/yahoo/tagchowder)：TagChowder是一个用Java编写的符合SAX的解析器，由Yahoo开源。
* [Apache Santuario](https://github.com/apache/santuario-xml-security-java)：Santuario项目旨在提供XML主要安全标准的实现。
* [Jaxb RI](https://github.com/eclipse-ee4j/jaxb-ri)：JAXB的Eclipse实现。
* [SitemapGen4j](https://github.com/dfabulich/sitemapgen4j)：SitemapGen4j是一个用Java生成XML站点地图的库。
* [Jaxen](https://github.com/jaxen-xpath/jaxen)：Jaxen是一个用Java编写的开源XPath 1.0库。
* [Simple](http://simple.sourceforge.net)：Simple是Java的一个XML序列化框架。
* [Xsd2bean](https://github.com/goldmansachs/gs-xsd2bean)：Xsd2bean是一个XML到对象的映射器，由高盛银行开源。
* [Apache Xalan](https://xalan.apache.org/xalan-j/)：Xalan-Java是一个XSLT处理器，用于将XML文档转换为HTML、文本或其他XML文档类型。
* [Apache Xerces](http://xerces.apache.org/xerces2-j/)：Xerces2提供了高性能、完全兼容的XML解析器。
* [Apache VXQuery](https://vxquery.apache.org/)：Apache VXQuery是一个用Java实现的符合标准的XML查询处理器。
* [XSoup](https://github.com/code4craft/xsoup)：基于JSoup的XPath选择器。
* [XMLBeam](https://github.com/SvenEwald/xmlbeam)：通过在代码中使用注解或XPath来处理XML。
* [Jcabi XML](https://github.com/jcabi/jcabi-xml)：Java XML解析、转换、打印和校验库。
* [Java XMLBuilder](https://github.com/jmurty/java-xmlbuilder)：XML Builder是一个实用程序，允许使用相对稀疏的Java代码构建简单的XML文档。
* [XMLResolver](https://github.com/xmlresolver/xmlresolver)：XMLResolver项目提供了SAX EntityResolver、Transformer URIResolver和新的NamespaceResolver的高级实现。
* [Xjx](https://github.com/jonas-grgt/xjx)：Java的轻量级XML序列化和反序列化库。
* [Validator](https://github.com/itplr-kosit/validator)：Validator是一个XML验证引擎，用于验证和处理各种格式的XML文件。
* [XsdParser](https://github.com/xmlet/XsdParser)：XsdParser是一个将XML定义文件(.xsd)解析为Java对象列表的库。
* [SimpleXml](https://github.com/codemonstur/simplexml)：独立的Java XML解析器和序列化器。
* [Xacml4j](https://github.com/policy4j/xacml4j)：Xacml4j是OASIS XACML 3.0标准的参考实现。
* [Balana](https://github.com/wso2/balana)：Balana是WSO2基于Sun的XACML实现而进行的XACML规范的开源实现。
* [XML Calabash](https://github.com/ndw/xmlcalabash1)：XML Calabash是XProc 3.1的一个实现。
* [Ph Schematron](https://github.com/phax/ph-schematron)：Ph Schematron是一个Java库，它通过ISO Schematron、SchXslt或Java纯实现来验证XML文档。
* [SimpleXML](https://github.com/ngallagher/simplexml)：Simple是一个高性能的Java XML序列化和配置框架。
* [XOM](https://github.com/elharo/xom)：XOM是一个新的XML对象模型。
* [Scalaxb](https://github.com/eed3si9n/scalaxb)：Scalaxb是Scala的XML数据绑定工具。
* [Kotlin XML Builder](https://github.com/redundent/kotlin-xml-builder)：一个轻量级、安全类型构建器，用于在Kotlin中构建XML文档。

#### HTML库

* [Aspose.HTML](https://products.aspose.com/html/java/)：Aspose.HTML是一种高级HTML操作API，用于在Java应用程序内操作和生成HTML。
* [JFiveParse](https://github.com/digitalfondue/jfiveparse)：一个符合Java HTML 5的解析器。
* [Boilerplate](https://github.com/kohlschutter/boilerpipe)：Boilerplate库提供了算法来检测和删除网页主要文本内容周围多余的“混乱”(样板、模板)。
* [JsoupXpath](https://github.com/zhegexiaohuozi/JsoupXpath)：纯Java实现的支持W3C Xpath 1.0标准语法的HTML解析器。
* [JTidy](https://github.com/jtidy/jtidy)：JTidy是HTML Tidy的Java端口，一个HTML语法检查器和漂亮的打印机。
* [J2Html](https://github.com/tipsy/j2html)：Java到HTML生成器。
* [Jspoon](https://github.com/DroidsOnRoids/jspoon)：Jspoon是一个Java库，它提供基于CSS选择器将HTML解析为Java对象的功能。
* [NekoHTML](https://github.com/codelibs/nekohtml)：HTML解析器和标签平衡器。
* [Fruit](https://github.com/graycreate/Fruit)：Fruit是一个Java库，可用于将HTML转换为Java对象。
* [CSSBox](https://github.com/radkovo/CSSBox)：CSSBox是一个用纯Java编写的(X)HTML/CSS渲染引擎。
* [HTMLParser](https://github.com/validator/htmlparser)：Validator.nu HTML解析器是HTML解析算法的Java实现。
* [jWebForm](https://github.com/jochen777/jWebForm)：jWebForm可以以简洁的方式定义HTML表单，用请求变量填充它们，验证并从中构建HTML。
* [AttoParser](https://github.com/attoparser/attoparser)：AttoParser是一个用于XML和HTML标签的Java解析器。
* [RenderSnake](https://github.com/emicklei/rendersnake)：RenderSnake是一个Java库，用于创建仅使用Java生成HTML的组件和页面。
* [Ultralight Java](https://github.com/LabyMod/ultralight-java)：Ultralight Web引擎的Java包装器，Ultralight是一款轻量级、跨平台的HTML渲染引擎，适用于桌面应用和游戏。

#### RTF库

* [RTF Parser Kit](https://github.com/joniles/rtfparserkit)：RTF Parser Kit提供一套组件，可以从RTF文件中提取纯文本或HTML。
* [jRTF](https://github.com/ullenboom/jrtf)：jRTF是一个简单的库，用于生成RTF文档和填充RTF模板文件。
* [OpenRTF](https://github.com/LibrePDF/OpenRTF)：OpenRTF是一个用于创建和编辑RTF(富文本格式)文件的Java库。

#### EPUB库

* [FolioReader Android](https://github.com/FolioReader/FolioReader-Android)：FolioReader Android是一款用Java和Kotlin编写的EPUB读取器。
* [Epublib](https://github.com/psiegman/epublib)：Epublib是一个用于读取/写入/操作epub文件的Java库。
* [EPUBCheck](https://github.com/w3c/epubcheck)：EPUBCheck是EPUB出版物的官方一致性检查器，由W3C开源。
* [EpubParser](https://github.com/mertakdut/EpubParser)：EpubParser是一个用于解析epub文件的Java库。
* [Epub4j](https://github.com/documentnode/epub4j)：用于读取/写入/操作EPUB文件的Java库，基于Epublib进行了改进。

#### Outlook库

* [Aspose.Email](https://products.aspose.com/email/java/)：Aspose.Email可以在Java应用程序内创建Outlook电子邮件、解析电子邮件或转换消息格式，如MSG、EML、MBOX、PST、OST和MHT。
* [Jotlmsg](https://github.com/ctabin/jotlmsg)：这是一个简单的API，用于轻松生成Microsoft Outlook消息文件(.msg)。
* [OST2PST](https://github.com/mkorthof/ost2pst)：将Outlook OST文件转换为PST格式。
* [OLMReader](https://github.com/teverett/OLMReader)：用于读取MS Outlook for Mac OLM档案的Java库。
* [Outlook Message Parser](https://github.com/bbottema/outlook-message-parser)：Outlook Message Parser是一个小型开源Java库，用于解析Outlook .msg文件。
* [LibPST](https://github.com/rjohnsondev/java-libpst)：一个使用Java读取PST文件的库。

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
* [LICENSE4J](https://www.license4j.com/)：LICENSE4J包含一个强大的库、一个直观的许可证管理器和一个多功能的许可证服务器。
* [Licensius](https://github.com/decebals/licensius)：Java开源微型许可证框架。

#### Markdown库

* [Txtmark](https://github.com/rjeschke/txtmark)：Java Markdown处理器。
* [MarkdownJ](https://github.com/myabc/markdownj)：MarkdownJ是Markdown(John Gruber编写的文本到HTML转换工具)的纯Java端口。
* [Markwon](https://github.com/noties/Markwon)：Android Markdown库。
* [MarkedJ](https://github.com/gitbucket/markedj)：优雅Markdown处理器marked.js的JVM端口。
* [Commonmark Java](https://github.com/commonmark/commonmark-java)：用于根据CommonMark规范解析和渲染Markdown文本的Java库，由Atlassian开源。
* [Quarkdown](https://github.com/iamgio/quarkdown)：Quarkdown是一种基于现代Markdown的排版系统，其设计围绕多功能性这一关键概念，通过将项目无缝编译成可打印的书籍或交互式演示文稿。
* [Java Markdown Generator](https://github.com/Steppschuh/Java-Markdown-Generator)：用于生成Markdown的Java库。
* [Pegdown](https://github.com/sirthias/pegdown)：基于parboiled PEG解析器的纯Java Markdown处理器，支持多种扩展。
* [SimpleAST](https://github.com/discord/SimpleAST)：SimpleAST是一个Kotlin/Java库，旨在将文本解析为抽象语法树，由Discord开源。
* [Intellij Markdown](https://github.com/JetBrains/markdown)：用Kotlin编写的多平台Markdown处理器，由JetBrains开源。
* [MarkupDocBuilder](https://github.com/Swagger2Markup/markup-document-builder)：一个支持AsciiDoc、Markdown和Confluence Wiki的标签文档生成器。
* [Nutz](https://github.com/sangupta/nutz)：JVM的Markdown处理器，手工编码的解析器生成AST，并允许轻松添加扩展。
* [MarkdownPapers](https://github.com/lruiz/MarkdownPapers)：用Java实现的Markdown解析器和转换器。
* [Markdown To AsciiDoc](https://github.com/markdown-asciidoc/markdown-to-asciidoc)：一个小型、轻量级的Markdown到AsciiDoc转换器，用Java编写，基于Pegdown。
* [MDTool](https://github.com/cevin15/MDTool)：一个可以将Markdown转换为HTML的工具。
* [Markdown Toc](https://github.com/houbb/markdown-toc)：Markdown Toc可以用来生成Markdown页面的目录，便于Github页面展现。
* [MarkItDown Java](https://github.com/DuanYan007/markitdown-java)：微软MarkItDown的Java重写版本，将各种文档格式转换为Markdown。

#### EditorConfig库

* [EditorConfig Java](https://github.com/editorconfig/editorconfig-core-java)：用Java编写的EditorConfig核心的克隆。
* [EC4j](https://github.com/ec4j/ec4j)：EC4j是Java的EditorConfig实现。

#### EDI库

* [StAEDI](https://github.com/xlate/staedi)：StAEDI是一个使用Java编写的用于EDI读写和验证的流式API。
* [EDIReader](https://github.com/BerryWorksSoftware/edireader)：EDIReader是一款灵活轻量级的EDI解析器，采用纯Java编写，使用SAX API，提供多种集成选项。
* [X12 Parser](https://github.com/imsweb/x12-parser)：用于ANSI ASC X12文档的解析器。

#### OBJ库

* [Obj](https://github.com/javagl/Obj)：Obj是一个简单的Wavefront OBJ文件加载器和写入器。
* [OObjLoader](https://github.com/seanrowens/oObjLoader)：这是一个用于解析和加载WaveFront .OBJ文件的Java库。
* [Java Date Front](https://github.com/mokiat/java-data-front)：用于读取Wavefront 3D模型资源(OBJ、MTL)的Java库。

#### OFD库

* [OFDRW](https://gitee.com/ofdrw/ofdrw)：开源的OFD处理库，支持文档生成、数字签名、文档保护、文档合并、转换、导出等功能。
* [OFDParser](https://github.com/wangyi160/ofdparser)：OFDParser是一个OFD解析器，用于根据标准解析格式。

#### 文件库

* [HWPLib](https://github.com/neolord0/hwplib)：Java的HWP库。
* [MPXJ](https://github.com/joniles/mpxj)：该库使你能够从各种文件格式和数据库中读取项目计划(有时称为进度表或项目集)，还可以将该信息写入各种文件格式。
* [OSMPBF](https://github.com/openstreetmap/OSM-binary)：OSMPBF是一个用于读取和写入OpenStreetMap PBF文件的Java/C++库。
* [WaveAccess](https://github.com/sintrb/WaveAccess)：波形文件(.wav)的Java读写操作库。
* [JPMML Evaluator](https://github.com/jpmml/jpmml-evaluator)：用于生成和使用PMML文档的Java库。
* [Org Java](https://github.com/orgzly/org-java)：Org模式文件Java解析器。
* [JElf](https://github.com/fornwall/jelf)：用于解析ELF文件的Java库。
* [jHDF](https://github.com/jamesmudd/jhdf)：该项目是用于访问HDF5文件的纯Java实现。
* [MSLinks](https://github.com/DmitriiShamrikov/mslinks)：用于解析和创建Windows快捷方式文件(.lnk)的库。
* [JglTF](https://github.com/javagl/JglTF)：与glTF相关的Java库。
* [LASzip4j](https://github.com/mreutegg/laszip4j)：LASzip库的Java移植。
* [Java netCDF](https://github.com/Unidata/netcdf-java)：netCDF Java库提供了科学数据访问的接口，它可用于从各种文件格式读取科学数据，包括netCDF、HDF、GRIB、BUFR等，由美国国家科学基金会开源。
* [DD PList](https://github.com/3breadt/dd-plist)：一个Java库，提供对ASCII、XML和二进制属性列表的支持。
* [Meico](https://github.com/cemfi/meico)：Meico是MEI文件的转换器框架，由帕德博恩大学开源。
* [OneBusAway GTFS](https://github.com/OneBusAway/onebusaway-gtfs-modules)：用于读取和写入GTFS源的Java库，包括数据库支持。
* [Jcabi Manifests](https://github.com/jcabi/jcabi-manifests)：用于方便读取类路径中可用的MANIFEST.MF文件的Java库。
* [Samchika](https://github.com/MayankPratap/Samchika)：Samchika是Java语言的一个可重复、易于使用且速度极快的文件处理库。
* [TorchV Unstructured](https://github.com/torchv/torchv-unstructured)：一个强大且开发者友好的文档解析库，专为RAG应用优化。
* [Fixedformat4j](https://github.com/jeyben/fixedformat4j)：Fixedformat4j是一个易于使用的Java框架，用于处理平面固定格式的文本文件。
* [JWARC](https://github.com/iipc/jwarc)：一个用于读取和写入WARC文件的Java库。

#### 文件转换

* [PDF2JSON](https://github.com/modesty/pdf2json)：PDF2JSON是一个PDF文件解析器，可将PDF二进制文件转换为基于文本的JSON。
* [Retrosheet](https://github.com/theapache64/retrosheet)：将Google电子表格转换为JSON端点。
* [OPENHTMLTOPDF](https://github.com/danfickle/openhtmltopdf)：OPENHTMLTOPDF是一个纯Java库，用于使用CSS 2.1进行布局和格式化，输出为PDF或图像，呈现格式良好的XML/XHTML的合理子集。
* [Java WkHtmlToPdf Wrapper](https://github.com/jhonnymertz/java-wkhtmltopdf-wrapper)：WkHtmlToPdf命令行工具的基于Java的包装器。
* [Pdf2Dom](https://github.com/radkovo/Pdf2Dom)：Pdf2Dom是一个PDF解析器，可将文档转换为HTML DOM表示形式。
* [HTMLToPDF](https://github.com/wooio/htmltopdf-java)：该项目基于WkHtmlToPdf，它将HTML文档转换为PDF。
* [PDF Converter](https://github.com/jmrozanec/pdf-converter)：一个将.pdf文件转换为.epub、.txt、.png、.jpg和.zip格式的Java库。
* [OpenDataLoader PDF](https://github.com/opendataloader-project/opendataloader-pdf)：OpenDataLoader PDF可以安全准确地将PDF转换为JSON、Markdown或HTML。
* [Documents4j](https://github.com/documents4j/documents4j)：Documents4j是一个用于将文档转换为另一种文档格式的Java库。
* [Mammoth](https://github.com/mwilliamson/java-mammoth)：Mammoth旨在转换.docx文档，例如由Microsoft Word、Google Docs和LibreOffice创建的文档，并将其转换为HTML。
* [Html2Image](https://github.com/hkirk/java-html2image)：这个简单的Java库将纯HTML标签转换为图像，并使用HTML元素提供客户端图像映射。
* [XmlToJson](https://github.com/smart-fun/XmlToJson)：用于将XML转换为JSON以及将JSON转换为XML的Android库。
* [Jettison](https://github.com/jettison-json/jettison)：一个用于在StAX的帮助下将XML和JSON相互转换的Java库，它实现XMLStreamWriter和XMLStreamReader并支持Mapped和BadgerFish约定。
* [Apache XML Graphics](https://xmlgraphics.apache.org/)：从XML到图形输出的转换工具。
* [Json2Xml](https://github.com/lukas-krecan/json2xml)：Json2Xml项目是JSON到XML转换的简单实现。
* [Fugerit Doc](https://github.com/fugerit-org/fj-doc)：从XML文档元模型开始生成不同输出格式的文档的框架。
* [Silencio](https://github.com/damianszczepanik/silencio)：Silencio是一个用于转换XML、JSON、YAML、Properties和其他格式的Java库。
* [KefirBB](https://github.com/kefirfromperm/kefirbb)：KefirBB是一个用于文本处理的Java库。
* [Docs To PDF Converter](https://github.com/yeokm1/docs-to-pdf-converter)：一个独立的Java库/命令行工具，可将DOC、DOCX、PPT、PPTX和ODT文档转换为PDF文件。
* [Docx4j ImportXHTML](https://github.com/plutext/docx4j-ImportXHTML)：使用Docx4j将XHTML转换为OpenXML WordML(docx)，还支持转换为pptx。
* [Email To PDF Converter](https://github.com/nickrussler/email-to-pdf-converter)：该软件可用于将电子邮件文件转换为PDF文件，它可以用作库、命令行工具或带有GUI的桌面应用程序。
* [MD2File](https://gitee.com/cevin15/MD2File)：文档导出工具类，能将Markdown格式的内容，转为Office Word、PDF、HTML等格式的文档。
* [Excel2Pdf](https://github.com/caryyu/excel2pdf)：Java Excel转PDF解决方案。
* [Markdown2Pdf](https://github.com/Qkyrie/Markdown2Pdf)：一个使用Java将Markdown转换为PDF的简单库。
* [XWiki Rendering](https://github.com/xwiki/xwiki-rendering)：XWiki Rendering是一个通用的渲染系统，它将给定语法(Wiki语法、HTML等)的文本输入转换为另一种语法(XHTML等)。
* [Deck2pdf](https://github.com/melix/deck2pdf)：Deck2pdf是一个简单的应用程序，可将你的deck.js、reveal.js、impress.js、Flowtime.js、Google html5slides、Slide Presentation Framework、ruban或DZSlides幻灯片转换为PDF文件。

#### Mime解析

* [SimpleMagic](https://github.com/j256/simplemagic)：简单的文件幻数和内容类型库，提供文件和字节数组的MIME类型确定。
* [jMimeMagic](https://github.com/arimus/jmimemagic)：jMimeMagic是一个用于确定文件或流的MIME类型的Java库。
* [Apache MIME4J](https://github.com/apache/james-mime4j)：Mime4j可用于解析纯RFC822和MIME格式的电子邮件消息流，并构建电子邮件消息的树表示形式。
* [MimeCraft](https://github.com/square/mimecraft)：用于创建符合RFC要求的Multipart和表单编码HTTP请求主体的实用程序，由Square开源。
* [MIME Type](https://github.com/overview/mime-types)：用于检测文件MIME类型的Java库。
* [Email Mime Parser](https://github.com/ram-sharma-6453/email-mime-parser)：基于Mime4j的简化Java电子邮件Mime解析器。

#### 文件上传

* [Apache Commons FileUpload](https://github.com/apache/commons-fileupload)：Commons FileUpload组件提供了一种简单而灵活的方法来向Servlet和Web应用程序添加对分段文件上传功能的支持。
* [Tus Java Client](https://github.com/tus/tus-java-client)：Tus Java Client是一个使用Tus协议将文件上传到任何支持该协议的远程服务器的库。
* [DUtil](https://github.com/shehuan/DUtil)：一个基于Okhttp的文件下载、上传工具。
* [EasyFTP](https://github.com/adeelahmad94/easyFTP)：Apache Commons FTPClient的简单包装类，可轻松通过FTP上传/下载任何类型的文件。
* [TUS Java Server](https://github.com/tomdesair/tus-java-server)：此库可用于在任何Java Web应用程序中启用可断点续传的文件上传。
* [FastUpload](https://sourceforge.net/projects/fastupload/)：该组件基于RFC1867，它使用高性能的字节搜索算法来解析提交的请求，然后将数据保存到文件系统中。
* [Upload Parser](https://github.com/Elopteryx/upload-parser)：Upload Parser是一个用于Servlet和Web应用程序的文件上传库。
* [NIO Multipart](https://github.com/synchronoss/nio-multipart)：NIO Multipart项目包含一个轻量级通用Java库，用于以非阻塞方式处理Multipart请求和响应，并具有可配置但恒定的内存占用。

#### 文件比较

* [Diff Match Patch](https://github.com/google/diff-match-patch)：Diff Match Patch库提供了强大的算法来执行同步纯文本所需的操作，Google开源。
* [GumTree](https://github.com/GumTreeDiff/gumtree)：GumTree是一个代码区分工具。
* [DiffPlug](https://www.diffplug.com/)：DiffPlug是免费的文本编辑器/差异和图像查看器/差异。
* [Diff Utils](https://github.com/java-diff-utils/java-diff-utils)：Diff Utils库是一个开源库，用于执行文本之间的比较操作：计算差异、应用补丁、生成统一差异或解析它们、生成差异输出以方便将来显示(如并排视图)等。
* [Cafecompare](https://github.com/GraxCode/cafecompare)：Cafecompare是一个用于分析和比较Java档案和class文件的GUI应用程序。
* [Java Diff Utils](https://github.com/dnaumenko/java-diff-utils)：Diff Utils库是一个用于执行文本之间比较操作的开源库。

#### 文件预览

* [KKFileView](https://gitee.com/kekingcn/file-online-preview)：KKFileView是基于Spring Boot的通用文件在线预览项目，由凯京科技开源。
* [DocPreview](https://gitee.com/hcwdc/docpreview)：文件在线预览模块，支持多格式转PDF文件，由华创数字云开源。
* [WDA](https://gitee.com/macplus/WDA)：配合OpenOffice实现文档的在线预览、本地文档添加、文档转换为HTML，文档HTML方式预览，由太原扁舟科技开源。
* [WPS View](https://gitee.com/mose-x/wps-view-java)：基于WPS在线编辑、在线预览后台服务。
* [File Preview Spring Boot Starter](https://github.com/wb04307201/file-preview-spring-boot-starter)：一个文档在线预览的中间件，可通过简单的配置即可集成到Spring Boot中。
* [All Docs](https://github.com/Jarrettluo/all-docs)：All Docs是一款可以在线预览、存储和共享Word、Excel、PowerPoint、PDF、图片等文档的工具。

## 容器化工具

* [Jib](https://github.com/GoogleContainerTools/jib)：Jib无需Docker守护进程即可为Java应用程序构建优化的Docker和OCI镜像，它可作为Maven和Gradle的插件以及Java库使用，由Google开源。
* [Eclipse JKube](https://github.com/eclipse/jkube)：JKube是插件和库的集合，用于使用Docker、Jib或S2I构建策略构建容器镜像，由RedHat开源。
* [Dockerfile Maven](https://github.com/spotify/dockerfile-maven)：该库包含一组用于处理Dockerfile的Maven工具，由Spotify开源。
* [Docker Maven Plugin](https://github.com/spotify/docker-maven-plugin)：用于构建和推送Docker镜像的Maven插件，Spotify开源，该项目不再活跃。
* [Helios](https://github.com/spotify/helios)：Helios是一个Docker编排平台，用于跨整个服务器群部署和管理容器，由Spotify开源。
* [Docker Lambda](https://github.com/lambci/docker-lambda)：复制实时AWS Lambda环境的Docker镜像和测试运行器。
* [Docker Maven Plugin](https://github.com/fabric8io/docker-maven-plugin)：用于运行和创建Docker镜像的Maven插件。
* [Docker Maven Plugin](https://github.com/alexec/docker-maven-plugin)：该项目旨在让你能够轻松地在容器上构建应用程序、测试它并将其推送到Docker仓库。
* [Docker Maven Plugin](https://github.com/wouterd/docker-maven-plugin)：一个Maven插件，用于为Maven项目创建、测试和发布Docker容器和镜像。
* [Docker Compose Maven Plugin](https://github.com/Systemmanic/docker-compose-maven-plugin)：使用Maven运行Docker Compose。
* [Docker Gradle Plugin](https://github.com/palantir/gradle-docker)：用于协调Docker构建和推送的Gradle插件，由Palantir开源。
* [Gradle Docker Plugin](https://github.com/bmuschko/gradle-docker-plugin)：用于管理Docker镜像和容器的Gradle插件。
* [Gradle Docker plugin](https://github.com/Transmode/gradle-docker)：Gradle插件增加了从构建脚本构建和发布Docker镜像的功能。
* [Gradle Docker Compose Plugin](https://github.com/avast/gradle-docker-compose-plugin)：简化在Gradle环境中使用Docker Compose进行本地开发和集成测试。
* [Gradle Docker Plugin](https://github.com/gesellix/gradle-docker-plugin)：另一个Gradle插件，让你的构建脚本可以轻松地与Docker守护进程通信。
* [Terrakube](https://github.com/AzBuilder/terrakube)：Terrakube是一个开源协作平台，用于使用Terraform或OpenTofu将远程基础设施作为代码操作运行。
* [Cattle](https://github.com/rancher/cattle)：Cattle是为Rancher提供支持的编排引擎，它的主要作用是元数据管理和外部系统的编排。
* [Stargate](https://github.com/ppdaicorp/stargate)：Stargate是一个基于Kubernetes和Docker的应用发布平台，由信也科技开源。
* [DomeOS](https://github.com/domeos/server)：DomeOS是搜狐北京研发中心打造的一款基于Docker的企业级应用编排运维管理系统。
* [Haven](https://github.com/codeabovelab/haven-platform)：Haven是一个开源Docker容器管理系统，它将容器、应用程序、集群、镜像和注册表管理集成在一处。
* [Dockerfly](https://gitee.com/helyho/DockerFly)：Dockerfly是基于Docker 1.12+开发的Docker管理工具。
* [SimpleDocker](https://gitee.com/taoes_admin/SimpleDocker)：SimpleDocker是一个简单的Docker控制面板，可以让用户更方便、舒适的使用Docker，其界面简洁、操作便捷，功能强大，可以带来更好地运维体验。
* [HyScale](https://github.com/hyscale/hyscale)：HyScale是基于K8s的以应用程序为中心的抽象框架。
* [Metaparticle/Package](https://github.com/metaparticle-io/package)：Metaparticle/Package是一组库的集合，旨在为开发人员提供无缝且惯用的容器构建和部署体验。
* [Styx](https://github.com/spotify/styx)：Styx是一项用于触发Docker容器定期调用的服务，由Spotify开源。
* [Blox](https://github.com/blox/blox)：Blox提供针对在Amazon ECS上运行应用程序进行优化的开源调度程序，由Amazon开源。
* [StackGres](https://github.com/ongres/stackgres)：StackGres是Kubernetes的全栈PostgreSQL发行版，打包到一个简单的部署单元中，拥有一组精心挑选和调整的周边PostgreSQL组件。
* [Kubernetes Operators](https://github.com/operator-framework/java-operator-sdk)：Java Operator SDK是一个生产就绪的框架，可以轻松地在Java中实现Kubernetes Operator。
* [Dekorate](https://github.com/dekorateio/dekorate)：用于生成Kubernetes相关清单的工具。
* [KubeHelper](https://github.com/KubeHelper/kubehelper)：KubeHelper通过Web界面简化了许多日常Kubernetes集群任务，搜索、分析、运行命令、Cron作业、报告、过滤器、Git同步等等。
* [Titus](https://github.com/Netflix/titus-control-plane)：Titus是Netflix容器管理平台，用于管理容器并提供与基础设施生态系统的集成。
* [Admiral](https://github.com/vmware-archive/admiral)：Admiral是一款高度可扩展且极具重量级的容器管理平台，用于部署和管理基于容器的应用，由VMware开源。

## DevOps

* [Ice](https://github.com/Teevity/ice)：Ice可以从使用情况和成本的角度鸟瞰庞大而复杂的云环境，由Netflix开源。
* [Jpom](https://gitee.com/dromara/Jpom)：Jpom是一款原生Ops软件，由dromara社区开源。
* [Edda](https://github.com/Netflix/edda)：Edda是一项通过AWS API轮询你的AWS资源并记录结果的服务，由Netflix开源。
* [MQCloud](https://github.com/sohutv/mqcloud)：RocketMQ企业级一站式服务平台，由搜狐开源。
* [EazyBuilder](https://github.com/iSoftStoneGroup/EazyBuilder)：EazyBuilder是一套完整的云原生架构下的DevOps平台项目，由软通动力开源。
* [OpsCloud4](https://github.com/ixrjog/opscloud4)：OpsCloud4是用于云上运维的工具，提供持续交付、多实例动态数据源、堡垒机等功能。
* [SREWorks](https://github.com/alibaba/SREWorks)：SREWorks专注于以应用为中心的开发模式，提供一站式云原生数智化运维SaaS管理套件，由阿里开源。
* [WGCLOUD](https://github.com/tianshiyeben/wgcloud)：WGCLOUD是Linux运维监控工具，支持系统硬件信息、内存、CPU、温度、磁盘空间及IO、硬盘smart、系统负载、网络流量等监控。
* [AlterShield](https://github.com/traas-stack/altershield)：AlterShield是一款能够有效进行变更风险防控，预防变更引发生产环境故障的变更管控解决方案，这是蚂蚁集团内部变更管控平台OpsCloud的开源版本。
* [Choerodon](https://gitee.com/choerodon/choerodon)：Choerodon数智化开发管理平台，提供体系化方法论和协作、测试、DevOps及容器工具，由甄知科技开源。
* [Gaia](https://github.com/gaia-app/gaia)：Gaia是一个用于Terraform模块和自助服务基础设施的Terraform UI。
* [LINSTOR](https://github.com/LINBIT/linstor-server)：LINSTOR由LINBIT开发，是一款开源软件，用于管理跨一组机器的复制卷。
* [Dubbo Admin](https://github.com/apache/dubbo-admin)：Dubbo Admin是为了更好地可视化Dubbo服务而设计的控制台，由阿里开发。
* [Dubbokeeper](https://github.com/dubboclub/dubbokeeper)：Dubbokeeper是一个开源版本基于Spring MVC开发的社区版DubboAdmin。
* [CloudExplorer Lite](https://github.com/CloudExplorer-Dev/CloudExplorer-Lite)：CloudExplorer Lite脱胎于飞致云创始软件产品CloudExplorer多云管理平台，支持对接纳管主流的公有云和私有云基础设施，提供开箱即用的云主机管理、云账单、运营分析和安全合规等基本功能。
* [Yunyi](https://gitee.com/openeuler/yunyi)：云翼数据缓存中间件云原生管理平台通过将数据缓存中间件服务纳入管理，增加数据缓存产品的云服务能力，由华为开发。
* [Kaelthas](https://github.com/tiklab-project/tiklab-kaelthas)：支持主机、网络、数据库、容器等各种监控，支持灵活多样的告警通知方式。
* [Jianmu](https://gitee.com/jianmu-dev/jianmu)：建木是一个面向DevOps领域的极易扩展的开源无代码(图形化)/低代码(GitOps)工具。
* [Pallet](https://github.com/pallet/pallet)：Pallet用于在云和虚拟机基础设施上配置和维护服务器，旨在解决跨各种云提供一致配置的运行镜像的问题。
* [Orion Visor](https://gitee.com/dromara/orion-visor)：Orion Visor是一款高颜值、现代化的智能运维&轻量堡垒机平台，由dromara社区开源。
* [Orion Ops](https://gitee.com/lijiahangmax/orion-ops)：一站式自动化运维及自动化部署平台。
* [Rundeck](https://github.com/rundeck/rundeck)：Rundeck是一种开源自动化服务，具有Web控制台、命令行工具和Web API，它使你可以轻松地跨一组节点运行自动化任务。
* [Uyuni](https://github.com/uyuni-project/uyuni)：Uyuni是一个开源系统管理解决方案，源自Spacewalk。
* [WeCube](https://github.com/WeBankPartners/wecube-platform)：WeCube是一套开源、一站式IT架构管理和运维管理工具，主要用于简化分布式架构IT管理，并可以通过插件进行功能扩展，由微众开源。
* [MSEC](https://github.com/Tencent/MSEC)：MSEC由腾讯QQ团队开源，它是一个后端Devops引擎，包括RPC、名称查找、负载均衡、监控、发布和容量管理。
* [Phoenix](https://gitee.com/monitoring-platform/phoenix)：Phoenix是一个灵活可配置的开源监控平台，主要用于监控应用程序、服务器、Docker、数据库、网络、TCP端口和HTTP接口。
* [Frostmourne](https://github.com/AutohomeCorp/frostmourne)：Frostmourne是汽车之家经销商技术部监控系统的开源版本，用于帮助监控几乎所有数据库数据(包括Elasticsearch、Prometheus、SkyWalking、MySQL等等)。
* [Suricate](https://github.com/michelin/suricate)：Suricate是一款开源应用程序，它允许IT团队通过由可在电视上显示的小部件组成的仪表板来监控其环境，由米其林开源。
* [Ovirt](https://github.com/oVirt/ovirt-engine)：Ovirt是一个开源的虚拟化管理平台，RedHat虚拟化管理平台RHEV的开源版本。
* [CloudUnit](https://github.com/end-of-game/cloudunit)：CloudUnit是Treeptik开源的DevOps平台。
* [OneOps](https://github.com/oneops/oneops)：OneOps是一个自动化运维开发的云管理平台，由沃尔玛赞助。
* [Metrik](https://github.com/thoughtworks/metrik)：Metrik是一种自动化工具，可以从CD管道中提取数据并为交付团队分析四个关键指标趋势，由ThoughtWorks开发。
* [Rudder](https://github.com/Normation/rudder)：Rudder是一个系统基础设施自动化平台，致力于为IT运营团队提供支持以确保和改善他们的安全态势并促进安全运营(SecOps)中的协作。
* [Eclipse Xpanse](https://github.com/eclipse-xpanse/xpanse)：Xpanse是一个开源项目，允许在任何云服务提供商上轻松实施本机托管服务，由华为开源。
* [Gitaction Board](https://github.com/otto-de/gitactionboard)：Github Actions的仪表板。
* [Bk Job](https://github.com/TencentBlueKing/bk-job)：蓝鲸作业平台是一套运维脚本管理系统，具备海量任务并发处理能力，腾讯开源。
* [DQOps](https://github.com/dqops/dqo)：DQOps是一款DataOps友好的数据质量监控工具，具有可定制的数据质量检查和数据质量仪表板。
* [Easy Manager Tool](https://gitee.com/aizuda/easy-manager-tool)：Easy Manager Tool集成各类工具的核心使用方法，打造集成化程度高且专业的开、测、维一体化管理工具，由爱组搭开源。
* [RackShift](https://github.com/fit2cloud/rackshift)：RackShift是开源的裸金属服务器管理平台，功能覆盖裸金属服务器的发现、带外管理、RAID配置、固件更新、操作系统安装等，由飞致云开源。
* [Hinemos](https://github.com/hinemos/hinemos)：Hinemos是一款开源集成系统管理软件，提供监控和作业管理(工作负载调度)功能，实现系统操作自动化，由NTT Data开源。
* [NeatLogic](https://gitee.com/neat-logic/neatlogic-itom-all)：NeatLogic是一套渐进式ITOM平台，致力为不同类型、不同规模用户提供完整的ITOM解决方案。
* [Apitally](https://apitally.io/spring-boot)：Apitally是一款简单的API监控和分析工具，提供直观的仪表板，包含实时指标、请求日志和警报。
* [Lite Monitor](https://github.com/haueosc/lite-monitor)：Lite Monitor是一个快速、准确、轻量化的服务器监控系统，拥有秒级的监控粒度，支持历史数据查看便于拥有多平台服务器的用户集中管理，由河南工程学院开发。
* [MirrorGate](https://github.com/BBVA/mirrorgate)：MirrorGate是一款控制台应用程序，旨在为团队提供与软件开发相关的所有不同领域的快速反馈，由西班牙外换银行开源。
* [UEH](https://github.com/china-alert/ueh)：UEH可对各种监控工具产生的告警进行汇聚，统一处理、集中展示，并通知。
* [Nginx WebUI](https://gitee.com/cym1102/nginxWebUI)：Nginx WebUI是一款图形化管理Nginx配置的工具。
* [Nginx Admin](https://github.com/jonatansalemes/nginx-admin)：Nginx Admin是一个开源的多平台Nginx软件管理器。
* [Camel](https://github.com/dianping/camel)：Camel是大众点评开发的软负载一体解决方案，承担了F5硬负载层后的软负载工作。
* [OpenTOSCA Container](https://github.com/OpenTOSCA/container)：OpenTOSCA Container是基于Java/Maven的运行时，用于部署和管理基于TOSCA的应用程序，由斯图加特大学开源。
* [Maintain Console](https://github.com/ChenYilei2016/maintain-console-public)：Maintain Console是一个专为企业级分布式系统设计的运维管理平台，通过统一的Web控制台实现对多个微服务应用的远程实时脚本执行,不需要重新发布代码。
* [Bugatti](https://github.com/QianmiOpen/bugatti)：Bugatti是专为解决开发、运维人员在项目打包、发布、部署、项目依赖、跨环境配置，健康监控等问题统一处理平台，由千米网开源。
* [Kuvasz](https://github.com/kuvasz-uptime/kuvasz)：Kuvasz是一个开源的自托管运行时间和SSL监控服务，带有状态页面，旨在帮助你跟踪网站和服务。

## 性能分析&调优

这里列出了用于分析JVM应用的常用内存诊具、日志分析工具等。

* [BTrace](https://github.com/btraceio/btrace)：BTrace是一个用于Java平台的安全、动态跟踪工具，由SUN开源。
* [jHiccup](https://github.com/giltene/jHiccup)：jHiccup提供平台中JVM暂停的日志和记录，由Azul开源。
* [Spark](https://github.com/lucko/spark)：Spark是适用于Minecraft客户端、服务器和代理的性能分析器。
* [KOOM](https://github.com/KwaiAppTeam/KOOM)：KOOM是快手推出的一款移动平台OOM杀手。
* [Cubic](https://gitee.com/dromara/cubic)：Cubic一站式问题定位平台，分布式实例监控、线程栈监控、线程池监控、动态Arthas命令集、依赖分析等等，由dromara社区开源。
* [XPocket](https://github.com/PerfMa/xpocket)：XPocket是PerfMa为终结性能问题而生的开源的插件容器。
* [Takin](https://github.com/shulieTech/Takin)：Takin是一个基于Java的开源系统，旨在测量全链路的在线或测试环境性能测试，由数列科技开源。
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：LatencyUtils包含一些用于跟踪延迟的实用工具。
* [JOL](https://github.com/openjdk/jol)：JOL是用于分析JVM中对象布局的微型工具箱，Oracle开源。
* [Cornerstone](https://github.com/ctripcorp/vi)：Cornerstone是携程框架部门研发的内部可视化组件VI的开源版本，VI主要是一个应用及应用相关环境的可视化工具，和应用健康状态及启动管理的工具。
* [JMX Exporter](https://github.com/prometheus/jmx_exporter)：JMX Exporter是一个捕获JMX MBean值的收集器。
* [Sidekick](https://github.com/runsidekick/sidekick)：Sidekick是一个开源实时应用程序调试器。
* [Atlassian Profiling](https://bitbucket.org/atlassian/atlassian-profiling)：Atlassian Profiling是Atlassian应用程序中使用的框架，用于提供简单的服务器端分析和指标收集。
* [MySQL Performance Analyzer](https://github.com/yahoo/mysql_perf_analyzer)：MySQL Performance Analyzer是一个用于MySQL性能监控和分析的开源项目，由Yahoo开源。
* [Spring Boot Startup Report](https://github.com/maciejwalkowiak/spring-boot-startup-report)：Spring Boot Startup Report库生成交互式Spring Boot应用程序启动报告，让你了解影响应用程序启动时间的因素，并可能有助于优化它。
* [Spring Startup Ananlyzer](https://github.com/linyimin0812/spring-startup-analyzer)：Spring Startup Analyzer生成交互式Spring应用程序启动报告，让你了解影响应用程序启动时间的因素并帮助优化它。
* [PerfJ](https://github.com/coderplay/perfj)：PerfJ是Java程序的Linux Perf的包装器。
* [Speed4j](https://github.com/jalkanen/speed4j)：Speed4j是一个非常简单且快速的Java性能分析库。
* [Parfait](https://github.com/performancecopilot/parfait)：Parfait是一个Java性能监控库，能够提取指标并以多种方式提供它们。
* [MoSKito](https://github.com/anotheria/moskito)：MoSKito是一个开源系统，用于监控Java Web应用程序的性能和行为。
* [Cryostat](https://github.com/cryostatio/cryostat-legacy)：用于从云工作负载中生成、分析和检索JFR数据。
* [Instrumental](https://www.expectedbehavior.com/products/instrumental/)：实时Java应用程序性能监控，具有免费开发帐户的商业服务。
* [Jolokia](https://github.com/jolokia/jolokia)：Jolokia是一个JMX-HTTP桥接器，提供JSR-160连接器的替代方案。
* [Nudge4j](https://github.com/lorenzoongithub/nudge4j)：通过字节码注入从Java 8浏览器远程开发控制台。
* [Sysmon](https://github.com/palantir/Sysmon)：Sysmon是一个用于JVM的轻量级平台监控工具，由Palantir开源。
* [Djigger](https://github.com/exense/djigger)：Djigger是一个用于Java应用程序的生产就绪性能分析和监控解决方案，主要依赖于先进的全天候采样器和仪器代理模式。
* [JRat](https://jrat.sourceforge.net/)：JRat是一个低开销、易于使用的Java平台开源性能分析器。
* [RemoraJ](https://github.com/Nastel/remoraj)：RemoraJ是一个可扩展的Java分析代理，它使用字节码检测以最小的开销拦截Java IPC调用。
* [JETM](https://github.com/frenchc/jetm)：JETM是一个用于编程或声明式性能监控的Java库。
* [JVMM](https://gitee.com/tzfun/jvmm)：JVMM是一个提供Java虚拟机和操作系统服务监控的工具，拥有丰富的数据采集功能。
* [JAMon](https://github.com/stevensouza/jamonapi)：JAMon是一个免费、简单、高性能、线程安全的Java API，可帮助开发人员轻松监控生产应用程序。
* [Eclipse Trace Compass](https://github.com/eclipse-tracecompass/org.eclipse.tracecompass)：Trace Compass是一款开源应用程序，可通过读取和分析系统日志或跟踪来解决性能和可靠性问题。
* [Erlyberly](https://github.com/andytill/erlyberly)：Erlyberly是一款使用Erlang跟踪技术的Erlang、Elixir和LFE调试器。
* [JMXTerm](https://github.com/jiaqi/jmxterm)：JMXTerm是一个用Java编写的基于开源命令行的交互式JMX客户端。
* [Autotune](https://github.com/kruize/autotune)：Kruize Autotune是Kubernetes的自主性能调优工具，由IBM开源。
* [Container Auto Tune](https://github.com/alipay/container-auto-tune)：Container Auto Tune是一款智能参数调优产品，帮助开发者和操作员自动调整应用，通过智能算法分析JVM合理的配置参数，由蚂蚁开源。
* [JavaMonitor](https://github.com/onblog/JavaMonitor)：Java应用性能远程监控系统。

#### 诊断工具

* [VisualVM](https://github.com/oracle/visualvm)：VisualVM是一个集成了命令行JDK工具和轻量级分析功能的可视化工具，Oracle开源。
* [Arthas](https://github.com/alibaba/arthas)：Arthas是阿里开源的Java诊断工具。
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：JProfiler直观的UI帮助你解决性能瓶颈，确定内存泄漏并了解线程问题。
* [YourKit](https://www.yourkit.com/features/)：YourKit是业界领先的Java剖析工具。
* [JConsole](https://docs.oracle.com/en/java/javase/23/management/using-jconsole.html)：JConsole是一款符合JMX规范的监控工具，由Oracle开发。
* [Async Profiler](https://github.com/async-profiler/async-profiler)：该项目是一个低开销的Java采样分析器，不会遇到安全点偏差问题。
* [JVM Profiler](https://github.com/uber-common/jvm-profiler)：JVM Profiler提供了一个Java Agent，以分布式方式收集Hadoop/Spark JVM进程的各种指标和堆栈跟踪，例如CPU/内存/IO指标，由Uber开源。
* [TProfiler](https://github.com/alibaba/TProfiler)：TProfiler是一个可以在生产环境长期使用的性能分析工具，由阿里开源。
* [IntelliJ Profiler](https://lp.jetbrains.com/intellij-idea-profiler/)：IntelliJ Profiler是一款简单但功能强大的CPU和内存分配分析工具，由JetBrains开发。
* [NetBeans Profiler](https://github.com/apache/netbeans/tree/master/profiler)：NetBeans Profiler与Oracle的开源NetBeans IDE捆绑在一起。
* [Greys](https://github.com/oldmanpushcart/greys-anatomy)：Greys是一个JVM进程执行过程中的异常诊断工具，可以在不中断程序执行的情况下轻松完成问题排查工作。
* [HouseMD](https://github.com/CSUG/HouseMD)：HouseMD是淘宝的聚石写的一个非常优秀的Java进程运行时诊断和调试工具。
* [Bistoury](https://github.com/qunarcorp/bistoury)：Bistoury是去哪儿开源的一个对应用透明、无侵入的Java应用诊断工具，用于提升开发人员的诊断效率和能力。
* [Mission Control](https://github.com/openjdk/jmc)：Mission Control是一个用于Java的开源生产时间分析和诊断工具，由Oracle开发。
* [Honest Profiler](https://github.com/jvm-profiling-tools/honest-profiler)：Honest Profiler是由LinkedIn开源的Java性能分析工具。
* [Statsd JVM Profiler](https://github.com/etsy/statsd-jvm-profiler)：Statsd JVM Profiler是一个JVM代理分析器，它将分析数据发送到StatsD，由Esty开源。
* [SJK](https://github.com/aragozin/jvm-tools)：SJK是一个用于JVM诊断、故障排除和分析的命令行工具。
* [Jvmtop](https://github.com/patric-r/jvmtop)：Jvmtop是一个轻量级控制台应用程序，用于监视计算机上所有可访问的、正在运行的JVM。
* [Aprof](https://github.com/devexperts/aprof)：Aprof是一个Java内存分配分析器，对分析的应用程序的性能影响非常低，由Devexperts开源。
* [Sniffy](https://github.com/sniffy/sniffy)：Sniffy是一个Java分析器，它直接在浏览器中显示结果。
* [Spf4j](https://github.com/zolyfarkas/spf4j)：Spf4j库是旨在提高Java应用程序的可观察性和性能的组件集合。
* [Byteman](https://github.com/bytemanproject/byteman)：Byteman是一个可以轻松跟踪、监视和测试Java应用程序和JDK运行时代码的行为的工具，由RedHat开源。
* [JavaMelody](https://github.com/javamelody/javamelody)：JavaMelody的目标是监控QA和生产环境中的Java或Java EE应用程序。
* [Automon](https://github.com/stevensouza/automon)：Automon是一个功能强大的Java库，它将AOP的强大功能与你已使用的监控或日志记录工具相结合，以声明方式监控和/或跟踪Java代码、JDK以及应用程序使用的任何jar。
* [JCoz](https://github.com/Decave/JCoz)：JCoz是世界上第一个针对Java程序的因果分析器。
* [Crash](https://github.com/crashub/crash)：CRaSH是一个为扩展Java程序和Java虚拟机而设计的Shell。
* [LeakCanary](https://github.com/square/leakcanary)：LeakCanary是一个Android内存泄漏检测库，由Square开源。
* [XRebel](https://www.jrebel.com/products/xrebel)：XRebel是一个Java性能分析工具，用于实时监控和分析Java应用程序的性能。
* [JVM Mon](https://github.com/ajermakovics/jvm-mon)：基于控制台的JVM监控工具。
* [New Relic](https://newrelic.com/)：New Relic是一个很强大的服务器性能监控工具。
* [Riemann JVM Profiler](https://github.com/riemann/riemann-jvm-profiler)：Riemann JVM Profiler是一个JVM代理，将功能级探查器遥测数据发送到Riemann服务器以进行分析、可视化和存储。
* [Perf Map Agent](https://github.com/jvm-profiling-tools/perf-map-agent)：一个Java代理，用于生成与Linux perf工具一起使用的方法映射。
* [Heapster](https://github.com/mariusae/heapster)：Heapster提供了一个代理库，用于对JVM进程进行堆分析，其输出与Google perftools兼容。
* [PSI Probe](https://github.com/psi-probe/psi-probe)：Tomcat的高级管理器和监视器。
* [Jarboot](https://gitee.com/majz0908/jarboot)：Jarboot是一个Java进程启停、管理、诊断的平台，可以管理、守护、监控及诊断本地和远程的Java进程。
* [Gradle Profiler](https://github.com/gradle/gradle-profiler)：一种自动收集Gradle构建的分析和基准测试信息的工具。
* [Perfino](https://www.ej-technologies.com/products/perfino/overview.html)：Perfino是一款JVM监测工具，有虚拟机管理、商业交易策略、跨虚拟机追踪、遥测数据、末端用户体验检测等实用功能。
* [HeapStats](https://github.com/HeapStats/heapstats)：HeapStats是Java故障排除工具。
* [Meteor](https://gitee.com/reywong/meteor)：该项目基于阿里开源的Arthas基础之上完成，是线上问题定位的神器。
* [JSonde](https://github.com/bedrin/jsonde)：JSonde允许你分析现有的Java应用程序。
* [DBdoctor](https://www.dbdoctor.cn/)：DBdoctor是一款内核级数据库性能诊断软件。
* [WarmRoast](https://github.com/sk89q/warmroast)：WarmRoast是带有基于Web界面的Java CPU诊断/采样器。

#### Spring Boot仪表板

* [Spring Boot Admin](https://github.com/codecentric/spring-boot-admin)：该项目为公开Actuator端点的Spring Boot Web应用程序提供了一个管理界面。
* [Hawtio](https://github.com/hawtio/hawtio)：Hawtio是一个轻量级、模块化的Web控制台，用于管理Java应用程序，由IBM开源。
* [Ward](https://github.com/Rudolf-Barbu/Ward)：Ward是一个简单简约的服务器监控工具，支持自适应设计系统。
* [Isona](https://github.com/SpringForAll/isona)：Isona是一款基于Spring Boot与Spring Cloud构建的微服务管理工具。
* [Microservices Dashboard](https://github.com/Ordina-Group/microservices-dashboard)：该项目的主要目标是为微服务仪表板UI项目提供服务器实现。
* [SnapAdmin](https://github.com/aileftech/snap-admin)：适用于Spring Boot应用的即插即用、自动生成的CRUD数据库管理面板。
* [Ostara](https://github.com/krud-dev/ostara)：Ostara是一款开源桌面应用程序，旨在简化Spring Boot应用程序的管理和监控。
* [KoTime](https://gitee.com/huoyo/ko-time)：KoTime是一个轻量级的Spring Boot项目性能分析工具，通过追踪方法调用链路以及对应的运行时长快速定位性能瓶颈。
* [Microservice Monitoring](https://github.com/xeraa/microservice-monitoring)：监控分布式(微)服务的日志、指标、Ping和跟踪。
* [Spring Tx Board](https://github.com/Mamun-Al-Babu-Shikder/spring-tx-board)：Spring Tx Board是一个轻量级、可自动配置的事务监控库，适用于基于Spring的应用程序。
* [Spring Cloud Dashboard](https://github.com/VanRoy/spring-cloud-dashboard)：该应用程序提供了一个简单的GUI来管理Spring Cloud应用程序基础设施。
* [Hofund](https://github.com/logchange/hofund)：Hofund是一套用于监控应用程序、连接并发现系统组件当前状态的工具集。
* [Schematic](https://github.com/BjoernKW/Schematic)：Schematic是Spring Boot的一个简单的数据库管理UI。
* [Backdoor](https://github.com/tanin47/backdoor)：Backdoor是一款数据库查询和编辑工具。
* [Boot Actuator](https://github.com/qinxuewu/boot-actuator)：基于Spring Boot 2.0实现的JVM远程监工图形化工具，可以同时监控多个Web应用。

#### GC日志分析

* [GCeasy](https://gceasy.io/)：GCeasy是业界首款机器学习引导的垃圾收集日志分析工具。
* [GCGC](https://github.com/apple/GCGC)：GCGC使用Jupyter Notebook界面来分析GC日志文件，由Apple开源。
* [Sematext Logs](https://sematext.com/logsene/)：Sematext Logs是一种日志集中解决方案，针对各种以日志为中心的用例。
* [GCViewer](https://github.com/chewiebug/GCViewer)：GCViewer是一个小工具，可以可视化Sun/Oracle、IBM、HP和BEA Java虚拟机生成的详细GC输出。
* [GCPlot](https://github.com/GCPlot/gcplot)：GCPlot是一个Java垃圾收集器(GC)日志分析器。
* [GCProf](https://github.com/twitter-archive/jvmgcprof)：GCProf是一个简单的实用程序，用于JVM中的配置文件分配和垃圾收集活动，Twitter开源。
* [GarbageCat](https://github.com/mgm3746/garbagecat)：GarbageCat是一个命令行工具，可解析Java GC日志记录并进行分析，以支持OpenJDK和Oracle JDK的JVM调整和故障排除。
* [Heapothesys](https://github.com/corretto/heapothesys)：Heapothesys是由Amazon Corretto团队开发的JVM垃圾回收工作负载的集合。
* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)：Java HotSpot JIT编译器的日志分析器/可视化器。
* [Eclipse Jifa](https://github.com/eclipse-jifa/jifa)：Jifa是一款在线分析工具，支持分析Java堆转储、GC日志、线程转储以及JFR文件，由阿里开源。
* [JVM GC Logs Analyzer](https://github.com/krzysztofslusarski/jvm-gc-logs-analyzer)：该项目是一个Java虚拟机和GC日志分析器，它专用于JVM 11及更高版本。
* [GCToolkit](https://github.com/microsoft/gctoolkit)：GCToolkit是一组用于分析HotSpot Java GC日志文件的库，由Microsoft开源。
* [Gchisto](https://github.com/jewes/gchisto)：Hotspot JVM垃圾收集日志可视化工具。

#### 堆转储

* [HAHA](https://github.com/square/haha)：HAHA是一个用于自动分析Android堆转储的Java库，由Square开源。
* [Heap Dump Tool](https://github.com/paypal/heap-dump-tool)：Heap Dump Tool可以捕获、清理Java堆转储中的敏感数据，由Paypal开源。
* [JDumpSpider](https://github.com/whwlsfb/JDumpSpider)：HeapDump敏感信息提取工具。
* [Eclipse Memory Analyzer](https://github.com/eclipse-mat/mat)：Eclipse Memory Analyzer提供了一个通用工具包来分析Java堆转储。
* [TBJMap](https://github.com/alibaba/TBJMap)：基于可维护性Agent，对JMap做了增强，可以方便的输出JVM堆中，每一个分区的对象实例个数和大小的Histogram图，由淘宝开发。
* [JDumpSpiderGUI](https://github.com/DeEpinGh0st/JDumpSpiderGUI)：JDumpSpiderGUI是一个用于Java堆转储文件分析的工具，支持命令行和JavaFX图形界面两种模式。

#### 线程转储

* [FastThread](https://fastthread.io/)：Java线程转储分析器。
* [Java Thread Dump Analyzer](https://github.com/spotify/threaddump-analyzer)：这是一个用Javascript编写的Java线程转储分析器，由Spotify开源。
* [TDA](https://github.com/irockel/tda)：TDA是一个小型Swing GUI，用于分析Java VM生成的线程转储和堆信息。
* [MJProf](https://github.com/AdoptOpenJDK/mjprof)：MJProf是一个单子线程转储分析工具集，它使用一系列简单的可组合构建块(monad)来分析jstack输出。
* [JStack Review](https://jstack.review/)：JStack Review从浏览器内分析Java线程转储。
* [JStackFX](https://github.com/twasyl/jstackfx)：JStackFX是一种用于分析线程转储的工具。
* [Samurai](https://github.com/yusuke/samurai)：Samurai是一个用于Java线程转储/GC日志的分析工具。

#### 火焰图

* [JFR Flame Graph](https://github.com/chrishantha/jfr-flame-graph)：这是一个简单的应用程序，用于从Java Flight Recorder转储中读取方法分析示例，并将这些堆栈跟踪转换为FlameGraph兼容格式。
* [Flamegrapher](https://github.com/flamegrapher/flamegrapher)：Flamegrapher是Java Flight Recorder的前端，允许你启动、转储、停止、保存以及从浏览器下载JFR记录。
* [Gumshoe](https://github.com/worstcase/gumshoe)：监控与各个调用堆栈相关的应用程序性能统计数据，以火焰图或根图的形式交互过滤和查看，由Dell开源。
* [JavaFlame](https://github.com/beothorn/javaflame)：Java的简单易用的火焰图，无需服务器或打开连接，只需插入代理并获取结果。
* [PerfGenie](https://github.com/salesforce-misc/perfGenie)：PerfGenie是一种持续的低开销上下文分析解决方案，可以解析和可视化JFR格式配置文件和Jstack，由Salesforce开源。

#### 对象测量

* [Jamm](https://github.com/jbellis/jamm)：Jamm提供MemoryMeter，这是一个适用于所有Java版本的Java代理，用于测量实际对象内存使用情况，包括JVM开销。
* [Sizeof](https://github.com/ehcache/sizeof)：该库允许你以字节为单位获取Java对象实例的大小。
* [Sizeofag](https://github.com/fracpete/sizeofag)：Sizeofag是一个Java代理，允许你在运行时确定JVM内Java对象的大小。
* [Memory Measurer](https://github.com/DimitrisAndreou/memory-measurer)：Memory Measurer是一个小工具，当你设计数据结构并想查看每个结构占用的内存量时，它非常方便。

## 软件质量

这里列出了Java中促进软件开发质量保障的工具、库，包括代码分析、依赖分析、编码规范、设计模式。

* [Stan4j](http://stan4j.com/)：STAN是领先的基于Eclipse的Java结构分析工具，以自然的方式将开发和质量保证结合在一起。
* [Socomo](https://github.com/gdela/socomo)：Socomo是一个简单的工具，可以可视化源代码的组成，并在你的Java项目开发过程中跟踪组成的更改。
* [AasC](https://github.com/finos/architecture-as-code)：AasC旨在通过人类和机器可读且版本控制的代码库来设计和管理软件架构，促进对复杂软件架构的深入了解、高效开发和无缝维护，由金融科技基金会开源。
* [Structure101](https://structure101.com/)：Structure101是一个敏捷体系结构开发环境，它允许软件开发团队组织代码库，这是一个收费软件。
* [Lattix](https://www.lattix.com/)：Lattix使你能够快速识别和修复架构问题。
* [JDepend](https://github.com/clarkware/jdepend)：JDepend遍历Java类和源文件目录，并为每个Java包生成设计质量指标。
* [Macker](https://innig.net/macker/)：Macker是一个为Java开发人员提供的构建时架构规则检查实用程序。
* [Architexa](https://www.architexa.com/)：Architexa帮助你理解和记录大型/复杂的代码库。
* [USL4j](https://github.com/codahale/usl4j)：USL4j是Neil Gunther博士的通用可扩展性定律的Java建模器。

#### 静态分析

* [Checkstyle](https://github.com/checkstyle/checkstyle)：Checkstyle是一个用于检查Java源代码是否符合代码标准或验证规则集的工具。
* [Infer](https://github.com/facebook/infer)：Infer是一个针对Java、C++、Objective-C和C的静态分析工具，用OCaml编写，由Facebook开源。
* [Error Prone](https://github.com/google/error-prone)：Error Prone是一个Java静态分析工具，可以在编译时捕获常见的编程错误，由Google开源。
* [PMD](https://github.com/pmd/pmd)：PMD是一个源码分析器，它可以发现常见的编程缺陷，例如未使用的变量、空的catch块、不必要的对象创建等。
* [CodeQL](https://github.com/github/codeql)：CodeQL是GitHub开发的代码分析引擎，用于自动执行安全检查。
* [Qodana](https://www.jetbrains.com/qodana)：Qodana是JetBrains推出的代码质量检测工具。
* [SpotBugs](https://github.com/spotbugs/spotbugs)：SpotBugs是一种静态分析工具，用于查找Java代码中的错误。
* [Nullsafe](https://engineering.fb.com/2022/11/22/developer-tools/meta-java-nullsafe)：Nullsafe是一个静态分析工具，Meta使用它来检测Java代码中的NPE错误。
* [Teamscale](https://docs.teamscale.com/)：Teamscale是一个软件智能平台，提供全面的代码、测试、架构和需求分析等功能。
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
* [Appshark](https://github.com/bytedance/appshark)：Appshark是一个静态污点分析平台，用于扫描Android应用程序中的漏洞，由字节开源。
* [Argus](https://github.com/arguslab/Argus-SAF)：Argus SAF是一个静态分析框架，用于对Android应用程序进行安全审查，由堪萨斯州立大学和南卡罗来纳大学开源。
* [SWAN](https://github.com/themaplelab/swan)：SWAN是一个静态程序分析框架，支持对Swift应用程序进行深度数据流分析，由阿尔伯塔大学开源。
* [Semgrep](https://github.com/semgrep/semgrep)：Semgrep是一种快速、开源、静态分析工具，用于在编辑期、提交和CI时搜索代码、查找错误并强制执行代码标准。
* [CodeFuse Query](https://github.com/codefuse-ai/CodeFuse-Query)：CodeFuse Query是一种强大的静态代码分析平台，适合大规模、复杂的代码库分析场景，由蚂蚁CodeFuse团队开发。
* [Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs)：Find Security Bugs是用于Java Web应用程序安全审核的SpotBugs插件，由OWASP开源。
* [Tai-e](https://github.com/pascal-lab/Tai-e)：Tai-e是一个易于学习/使用的Java静态分析框架，由南京大学开源。
* [CodeCC](https://github.com/TencentBlueKing/bk-codecc)：CodeCC提供专业的代码检查解决方案及服务，为产品质量保驾护航，由腾讯开源。
* [Booster](https://github.com/didi/booster)：Booster是一款专门为移动应用设计的易用、轻量级且可扩展的质量优化框架，由滴滴开发。
* [TLAPlus](https://github.com/tlaplus/tlaplus)：TLC是一个显式状态模型检查器，用于检查以TLA+编写的规范，由Microsoft开发。
* [NullAway](https://github.com/uber/NullAway)：NullAway是一个帮助消除Java代码中的NPE的工具，由Uber开源。
* [CodeCompass](https://github.com/Ericsson/CodeCompass)：CodeCompass是一个用C/C++和Java编写的大型软件的软件理解工具，由爱立信开源。
* [Eclipse Steady](https://github.com/eclipse-steady/steady)：Steady分析你的Java应用程序是否存在已知漏洞的开源依赖，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性，由SAP开源。
* [Checker Framework](https://github.com/typetools/checker-framework)：Checker Framework增强了Java的类型系统，这使得软件开发人员能够检测并防止其Java程序中的错误，由华盛顿大学开源。
* [MobsfScan](https://github.com/MobSF/mobsfscan)：MobsfScan是一个静态分析工具，可以在Android和IOS源代码中查找不安全的代码模式。
* [CK](https://github.com/mauricioaniche/ck)：CK通过静态分析的方式(即不需要编译代码)计算Java项目中的类级和方法级代码度量。
* [LiSA](https://github.com/lisa-analyzer/lisa)：LiSA旨在简化基于抽象解释理论的静态分析器的创建和实现，由威尼斯大学开源。
* [PVS Studio](https://pvs-studio.com/en/)：PVS Studio是针对C、C++、C#和Java代码的静态分析器。
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
* [Doop](https://github.com/plast-lab/doop)：Java指针和污点分析框架，由雅典大学开源。
* [Code Asset](https://github.com/nidi3/code-assert)：断言项目的源代码满足某些规则。
* [Joern](https://github.com/joernio/joern)：Joern是一个用于分析源代码、字节码和二进制可执行文件的平台，由ShiftLeft开源。
* [Tailor](https://github.com/sleekbyte/tailor)：Tailor是一款跨平台静态分析和lint工具，用于使用Apple Swift编程语言编写的源代码。
* [JayHorn](https://github.com/jayhorn/jayhorn)：JayHorn是Java的软件模型检查工具。
* [CoraxJava](https://github.com/Feysh-Group/corax-community)：CoraxJava是一款针对Java项目的静态代码安全分析工具，由蜚语科技开源。
* [Soot](https://github.com/soot-oss/soot)：Soot是一个Java优化框架，提供了多种用于分析和转换Java字节码的中间表示形式，由麦吉尔大学开源。
* [SootUp](https://github.com/soot-oss/SootUp)：SootUp是对优秀的旧静态分析框架Soot的彻底改造，由帕德博恩大学安全软件工程组开源。
* [PySonar2](https://github.com/yinwang0/pysonar2)：PySonar2是Python的语义索引器库，专为大型代码库的批处理而设计，生成的索引可用于构建代码浏览器和代码搜索引擎。
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
* [Sourcefare](https://github.com/tiklab-project/tiklab-sourcefare)：Sourcefare是一款开源的静态代码扫描工具。
* [LitterBox](https://github.com/se2p/LitterBox)：LitterBox是一个用于检测Scratch项目中错误的静态代码分析工具，由德国帕绍大学开源。
* [TAJS](https://github.com/cs-au-dk/TAJS)：TAJS是一种JavaScript数据流分析，可以推断类型信息和调用图，由奥胡斯大学开源。
* [TIP](https://github.com/cs-au-dk/TIP)：TIP是一种小型命令式编程语言，旨在教授静态程序分析的基本概念，由奥胡斯大学开源。
* [ChanZi](https://github.com/Chanzi-keji/chanzi)：铲子是一款简单易用的Java SAST(静态应用程序安全测试)工具
* [Coverity](https://scan.coverity.com/)：Coverity是一种静态应用程序安全测试(SAST)和问题管理工具，最初由美国国土安全部开发。
* [Maple IR](https://github.com/LLVM-but-worse/maple-ir)：Maple-IR是一个基于IR的工业级Java字节码静态分析框架。
* [SourcererCC](https://github.com/Mondego/SourcererCC)：SourcererCC是Sourcerer推出的一款基于Token的代码克隆检测器，适用于超大型代码库和互联网规模的项目存储库，由加州大学欧文分校开源。
* [HuntBugs](https://github.com/amaembo/huntbugs)：基于Procyon的Java字节码静态分析工具，旨在取代FindBugs。
* [Joana](https://github.com/joana-team/joana)：Joana是一款静态分析工具，可用于Java字节码的信息流控制。
* [Freud](https://github.com/LMAX-Exchange/freud)：Freud为用户提供了一种定义自己的静态分析测试的简单方法，由英国外汇交易公司LMAX开发。
* [CodeNarc](https://github.com/CodeNarc/CodeNarc)：CodeNarc是一款Groovy源代码静态分析工具，支持监控和执行多种编码标准和最佳实践。
* [LiquidJava](https://github.com/CatarinaGamboa/liquidjava)：LiquidJava是Java的附加类型检查器，基于liquid类型和类型状态，通过编译时的细化为Java程序提供额外的安全保障。
* [Code2flow](https://github.com/menduogesei/code2flow-in-java)：Code2flow Java版本，生成动态语言的调用图。
* [JDart](https://github.com/psycopaths/jdart)：JDart是一个在Java程序上执行一致执行的工具，它是作为NASA Java Pathfinder(JPF)的扩展编写的，由NASA开源。
* [Kex](https://github.com/vorpal-research/kex)：Kex是一个用于分析Java字节码的平台，由Jetbrains开发。
* [LibScout](https://github.com/reddr/LibScout)：LibScout是一款轻量级且高效的静态分析工具，用于检测Android/Java应用中的第三方库。

#### 编码规范

* [Google Java Format](https://github.com/google/google-java-format)：Google Java Format是一个重新格式化Java源代码以符合Google Java风格的程序。
* [Spring Java Format](https://github.com/spring-io/spring-javaformat)：一组可应用于任何Java项目以提供一致的Spring风格的插件。
* [Square Java Code Style](https://github.com/square/java-code-styles)：Square的Java和Android项目的IntelliJ IDEA代码样式设置。
* [P3C](https://github.com/alibaba/p3c)：阿里巴巴Java编码指南PMD实现和IDE插件。
* [Cookpad Style Guide](https://github.com/cookpad/styleguide)：Cookpad的编码风格指南。
* [Spotless](https://github.com/diffplug/spotless)：Spotless是支持多种语言的代码格式化工具。
* [Prettier Java](https://github.com/jhipster/prettier-java)：Prettier是一个代码格式化程序，它通过解析代码并使用自己的规则重新打印代码来强制执行一致的样式。
* [CodeBuff](https://github.com/antlr/codebuff)：Codebuff是一种使用机器学习算法的格式化工具。
* [Cornell Java Code Style](https://www.cs.cornell.edu/courses/JavaAndDS/JavaStyle.html)：康奈尔大学Java编程风格指南。
* [Oracle Java Code Convention](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html)：Oracle官方Java代码约定。
* [Android AOSP Style Guide](https://source.android.com/docs/setup/contribute/code-style?hl=zh-cn)：面向贡献者的AOSP Java代码样式指南。
* [Twitter Java Code Style](https://github.com/twitter-archive/commons/blob/master/src/java/com/twitter/common/styleguide.md)：Twitter提供的一组鼓励优秀代码的约定。
* [Hackday Conventions Java](https://github.com/naver/hackday-conventions-java)：Naver使用的Java开发风格指南。
* [JavaRanch Style Guide](https://coderanch.com/wiki/718799/Style)：Oracle编码风格的替代方案。
* [GVSU Java Coding Style](https://www.gvsu.edu/computing/java-coding-style-guide-37.htm)：大峡谷州立大学的Java编码规范。
* [Databricks Scala Guide](https://github.com/databricks/scala-style-guide)：Databricks Scala编码风格指南。
* [CMU Java Code Style](https://www.cs.cmu.edu/~rdriley/121/resources/styleguide/)：CMU 15-121源代码编码标准的完整定义。
* [Chromium Java Style Guide](https://chromium.googlesource.com/chromium/src/+/HEAD/styleguide/java/java.md)：Chromium Java编码风格指南。
* [CIS Java Style Guide]()：CIS 120 Java风格指南。
* [Palantir Java Format](https://github.com/palantir/palantir-java-format)：一个现代、Lambda友好、120个字符的Java格式化器。
* [CodingStyle](https://github.com/uhafner/codingstyle)：慕尼黑应用科技大学使用的Java编码风格和模板项目。
* [Ribot Android Guidelines](https://github.com/ribot/android-guidelines)：Ribot为Android平台开发时使用的指南列表。

#### 依赖分析

* [Dependency Track](https://github.com/DependencyTrack/dependency-track)：Dependency Track是一个智能组件分析平台，允许组织识别并降低软件供应链中的风险，由OWASP开源。
* [Dependency Check](https://github.com/dependency-check/DependencyCheck)：OWASP DependencyCheck是一种软件组合分析实用程序，可检测应用程序依赖中公开披露的漏洞。
* [Depends](https://github.com/multilang-depends/depends)：Depends是一个源代码依赖提取工具，旨在从各种编程语言推断源代码实体(例如文件和方法)之间的语法关系。
* [Jarviz](https://github.com/ExpediaGroup/jarviz)：Jarviz是专为Java应用程序设计的依赖分析和可视化工具，由Expedia开源。
* [Dependency Analysis Gradle Plugin](https://github.com/autonomousapps/dependency-analysis-gradle-plugin)：提供有关管理依赖项和其他应用插件的建议。
* [Classycle](https://classycle.sourceforge.net/)：Classycle可以分析Java应用程序或库中的静态类和包依赖关系。
* [DepAn](https://github.com/google/depan)：DepAn是一个直接操作工具，用于可视化、分析和重构大型应用程序中的依赖关系，Google开源。
* [JDependency](https://github.com/tcurdt/jdependency)：JDependency是一个小型库，可帮助你分析类级依赖关系、冲突和缺失类。
* [Degraph](https://github.com/riy/degraph)：Degraph是一个用于可视化和测试JVM应用程序中的类和包依赖关系的工具。
* [Depgraph Maven Plugin](https://github.com/ferstl/depgraph-maven-plugin)：该Maven插件在单个模块上生成依赖关系图，或者在多模块项目上以聚合形式生成依赖关系图。
* [FASTEN](https://github.com/fasten-project/fasten)：FASTEN项目是一个智能软件包管理系统，旨在增强软件生态系统的稳健性和安全性，由代尔夫特理工大学开源。
* [MissingLink](https://github.com/spotify/missinglink)：用于检测Java项目中链接问题的构建时工具，由Spotify开源。
* [OSS Review Toolkit](https://github.com/oss-review-toolkit/ort)：OSS Review Toolkit是一个FOSS策略自动化和编排工具包，你可以使用它以战略、安全和高效的方式管理你的软件依赖项。
* [Eureka](https://github.com/LegacyCodeHQ/eureka)：与Kotlin和Java代码库兼容的突破性工具。
* [Dependency Check Gradle](https://github.com/dependency-check/dependency-check-gradle)：Dependency Check Gradle允许项目监控依赖库中已知、已发布的漏洞。
* [Gradle Dependency Graph Generator Plugin](https://github.com/vanniktech/gradle-dependency-graph-generator-plugin)：可让你在图表中可视化依赖关系的Gradle插件。
* [Gradle Dependency Analyze](https://github.com/gradle-dependency-analyze/gradle-dependency-analyze)：Gradle的依赖分析插件。
* [DepClean](https://github.com/ASSERT-KTH/depclean)：DepClean自动检测并删除Maven项目中未使用的依赖，由瑞士皇家理工学院开源。
* [JLib Inspector](https://github.com/brunoborges/jlib-inspector)：JLib Inspector可以捕获已加载JAR和类的精确且低开销清单，以便你缩小镜像体积、确定CVE修复的优先级并消除依赖漂移。

#### 迁移&重构

* [EMT4J](https://github.com/adoptium/emt4j)：EMT4J是一个旨在简化Java版本迁移的项目，由阿里开源。
* [Rewrite](https://github.com/openrewrite/rewrite)：OpenRewrite项目是一个源代码自动重构生态系统，使开发人员能够有效消除其仓库中的技术债务，由Netflix开源。
* [Spring Boot Migrator](https://github.com/spring-projects-experimental/spring-boot-migrator)：Spring Boot Migrator旨在通过提供自动迁移的方法来帮助开发人员升级或迁移到Spring Boot。
* [Windup](https://github.com/windup/windup)：Windup是一个工具集，支持跨广泛转换和用例的大规模Java应用程序现代化和迁移项目，由RedHat开源。
* [Jakarta Migration](https://github.com/apache/tomcat-jakartaee-migration)：该工具的目的是自动对为Java EE 8编写并在Tomcat 9上运行的Web应用程序进行转换，以便可以在实现Jakarta EE 9的Tomcat 10上运行。
* [Scientist4J](https://github.com/rawls238/Scientist4J)：Github重构工具Scientist的Java移植。
* [RefactoringMiner](https://github.com/tsantalis/RefactoringMiner)：RefactoringMiner是一个用Java编写的库/API，可以检测Java项目历史中应用的重构。
* [Eclipse Transformer](https://github.com/eclipse/transformer)：Transformer提供了转换Java二进制文件的工具和运行时组件，将更改映射到Java包、类名称和相关资源名称，由Open Liberty团队开源。
* [Butterfly](https://github.com/paypal/butterfly)：Butterfly是一种应用程序代码转换工具，通常用于执行自动化应用程序迁移、升级以及源代码和配置更改，由Paypal开源。
* [MigrationMiner](https://github.com/hussien89aa/MigrationMiner)：MigrationMiner是检测两个Java第三方库之间迁移代码的工具。
* [Astra](https://github.com/alfasoftware/astra)：Astra是一个用于分析和重构Java源代码的Java工具。

#### 污点分析

* [Gadget Inspector](https://github.com/JackOfMostTrades/gadgetinspector)：GadgetInspector是一个自动化反序列化链挖掘工具，它通过对字节码形式的Java项目进行污点分析，挖掘可能存在的反序列化链。
* [Phosphor](https://github.com/gmu-swe/phosphor)：Phosphor是一个在JVM和商用JVM上执行动态污点跟踪的系统。

#### 抄袭检测

* [JPlag](https://github.com/jplag/JPlag)：JPlag能够在一组多个程序中查找成对的相似性，由卡尔斯鲁厄理工学院开源。
* [MOJI](https://github.com/nordicway/moji)：MOJI是Moss剽窃检测服务的非官方Java客户端。
* [Antiplag](https://github.com/fanghon/antiplag)：作业查重软件，它实现了程序代码、文档文本、图片之间的相似度检查。
* [AC](https://github.com/manuel-freire/ac2)：AC是一款源代码抄袭检测工具，由马德里康普顿斯大学开源。
* [XINCHECK](https://github.com/tianlian0/duplicate-check-sample)：文本查重SDK，可用于论文查重、标书查重、文档查重、作业查重、合同查重、防串标等场景，由芯锋科技公司开发。

#### 代码属性图

* [CPG](https://github.com/Fraunhofer-AISEC/cpg)：一个用于从源代码中提取代码属性图的简单库。
* [Code Property Graph](https://github.com/ShiftLeftSecurity/codepropertygraph)：CPG是一种可扩展且与语言无关的程序代码表示形式，专为增量和分布式代码分析而设计。
* [Plume](https://github.com/plume-oss/plume)：Plume是一个代码表示基准测试库，可以选择从Java字节码中提取AST并将结果存储在各种图数据库中，由Amazon开源。

## 软件工程

#### 软件建模

* [Eclipse Capella](https://github.com/eclipse/capella)：Capella是一款全面、可扩展且经过现场验证的MBSE工具和方法，可用于成功设计系统架构，由Thales开源。
* [C4 Model](https://c4model.com/)：C4 Model是一种易于学习、对开发人员友好的软件架构图绘制方法。
* [Structurizr Java](https://github.com/structurizr/java)：Structurizr基于“图即代码”构建，允许你从单个模型创建多个软件架构图。
* [Umple](https://github.com/umple/umple)：Umple是一种面向模型的编程技术，允许开发人员在传统代码中嵌入建模概念(例如UML 关联、状态机)、模式、生成模板和其他抽象，反之亦然，由渥太华大学开源。
* [UMLGraph](https://github.com/dspinellis/UMLGraph)：UMLGraph允许以声明式方式指定和绘制UML图。
* [Overarch](https://github.com/soulspace-org/overarch)：Overarch提供了一个基于UML和C4 Model等的软件系统和组织的本体和数据驱动模型。
* [JIG](https://github.com/dddjava/jig)：JIG是一个支持代码设计的工具。
* [VMF](https://github.com/miho/VMF)：VMF是一个轻量级的建模框架，它可以方便地将带注解的Java接口转换为功能强大的实现。
* [USE](https://github.com/useocl/use)：USE是一种信息系统规范系统，它基于统一建模语言(UML)的一个子集。
* [E-ADR](https://github.com/adr/e-adr)：嵌入Java代码中的架构决策记录。
* [Eclipse Epsilon](https://github.com/eclipse-epsilon/epsilon)：Epsilon是一系列脚本语言和工具，用于自动化常见的基于模型的软件工程任务，例如代码生成、模型到模型的转换、模型验证和模型可视化，它们可以开箱即用地与EMF、UML、Simulink、XML和其他类型的模型配合使用。
* [Lowfer](https://github.com/mbouchenoire/lowfer)：Lowfer是一个简单的工具，可以帮助软件工程师和架构师记录、讨论和分析软件设计和架构。
* [Getaviz](https://github.com/softvis-research/Getaviz)：借助Getaviz，你可以通过在2D、3D和虚拟现实中探索软件工件来观察地解决软件工程问题，由莱比锡大学开源。
* [Invert](https://github.com/square/invert)：Invert是一款大规模收集和分析项目统计数据的工具，由Square开源。
* [Code to Knowledge Graph](https://github.com/Bevel-Software/code-to-knowledge-graph)：Code to Knowledge Graph是一个Kotlin/JVM工具包，利用VS Code的LSP解析源代码并创建丰富且可查询的知识图谱，从任何代码库中提取实体、关系和架构洞察。

#### 铁路图生成器

* [RR](https://github.com/GuntherRademacher/rr)：RR是语法图生成器(也称为铁路图)，它是一个独立的工具，具有基于浏览器的GUI和批处理模式。
* [RRDiagram](https://github.com/Chrriis/RRDiagram)：RR图是一个Java库，可从代码或BNF表示法生成铁路图。
* [JSyntrax](https://github.com/atp-mipt/jsyntrax)：JSyntrax是一个铁路图生成器，它创建了用于编程语言的语法的直观说明，由莫斯科物理技术学院开源。

#### DDD框架

* [COLA](https://github.com/alibaba/COLA)：COLA代表整洁面向对象分层架构，由阿里开源。
* [Axon](https://github.com/AxonFramework/AxonFramework)：Axon是一个基于DDD、CQRS和事件溯源原则构建渐进式事件驱动微服务系统的框架。
* [Spring Modulith](https://github.com/spring-projects/spring-modulith)：Spring Modulith允许开发人员构建结构良好的Spring Boot应用程序，并指导开发人员查找和使用由领域驱动的应用程序模块。
* [PICASO](https://zhuanlan.zhihu.com/p/7561767079)：PICASO是一套以DDD作为思想内核，专门为集成式复杂业务系统设计的通用基础框架，由京东开发。
* [jMolecules](https://github.com/xmolecules/jmolecules)：jMolecules用于帮助开发人员以无干扰的普通Java实现领域模型。
* [Apache Causeway](https://github.com/apache/causeway)：Causeway是一个用Java快速开发领域驱动应用程序的框架。
* [Library](https://github.com/ddd-by-examples/library)：全面的领域驱动设计示例，包含问题空间战略分析和各种战术模式。
* [DDDplus](https://github.com/funkygao/cp-ddd-framework)：DDDplus是一个轻量级的DDD正向/逆向业务建模增强框架，支持复杂的系统架构演进。
* [ContextMapper](https://github.com/ContextMapper/context-mapper-dsl)：ContextMapper是一个开源工具，提供基于DDD模式的领域特定语言，用于上下文映射和服务分解。
* [Aggregate Persistence](https://gitee.com/thoughtworks/aggregate-persistence)：Aggregate Persistence旨在提供一种轻量级聚合持久化方案，帮助开发者真正从业务出发设计领域模型，由ThoughtWorks开源。
* [DDDLib](https://github.com/dayatang/dddlib)：DDDLib是一个领域驱动设计类库。
* [Akka DDD](https://github.com/pawelkaczor/akka-ddd)：Akka DDD是在Akka平台之上构建遵循DDD/CQRS/ES架构的分布式服务的框架。
* [EzDDD](https://gitlab.com/TeddyChen/ezddd)：EzDDD是一个Java库，用于实现DDD、CQRS和清洁架构(CA)等战术设计模式。
* [DDD Framework](https://github.com/lml200701158/ddd-framework)：DDD脚手架。
* [ENode](https://github.com/anwu4/enode)：ENode是基于JVM平台，为业务实践DDD思想而落地的一个应用框架。
* [DDD Base](https://github.com/linux-china/ddd-base)：Java领域驱动设计基础包。
* [Aggregate Framework](https://github.com/changmingxie/aggregate-framework)：Aggregate Framework是一款基于DDD和CQRS思想开发的领域驱动框架。
* [Cheddar](https://github.com/travel-cloud/Cheddar)：Cheddar是一个Java框架，适用于AWS上的企业应用程序，使用DDD。
* [ZenWave SDK](https://github.com/ZenWave360/zenwave-sdk)：ZenWave SDK是一个用于DDD和API优先的可配置且可扩展的工具包，可以从不同模型的组合生成代码。
* [Nest](https://github.com/jovezhao/nest)：Nest是一个帮助开发人员快速实现基于DDD的技术框架。
* [DDD4Java](https://github.com/fuinorg/ddd-4-java)：Java领域驱动设计(DDD)的基类。

#### CQRS框架

* [JdonFramework](https://github.com/banq/jdonframework)：JdonFramework是一个支持Pub-Sub异步编程模型的领域事件框架。
* [Reveno](https://github.com/dmart28/reveno)：Reveno是一款基于JVM、速度极快、持久耐用且简洁易用的异步事务处理框架。
* [Evento](https://github.com/EventoFramework/evento-framework)：Evento框架为开发人员提供了一套强大的工具包，用于构建和管理利用事件溯源和CQRS架构模式的分布式应用程序。
* [Splitet](https://github.com/Splitet/SplitetFramework)：Splitet是一个基于Java的事件溯源框架，由Kloia开源。
* [Loom](https://github.com/loom/loom-java)：Loom是一组用于实现分布式消息传递和事件源模式的框架。
* [FModel](https://github.com/fraktalio/fmodel)：Fmodel旨在将函数式、代数式和响应式领域建模引入Kotlin。
* [OpenCQRS](https://github.com/open-cqrs/opencqrs)：OpenCQRS是一个轻量级开源Java框架，用于基于CQRS和事件源模式构建应用程序。
* [Sourcerer](https://github.com/elder-oss/sourcerer)：Sourcerer是一个固执己见、函数式且与存储无关的框架，用于使用事件源在Java 8中实现CQRS架构，由Elder开发。
* [Apache Polygene](https://github.com/apache/polygene-java)：Apache Polygene实现了面向复合编程，无需使用任何预处理器或新的语言元素。
* [Eventsourced](https://github.com/eligosource/eventsourced)：Eventsourced库为Akka增加了可扩展的Actor状态持久性和至少一次消息传递的保证。
* [Eventuate](https://github.com/RBMHTechnology/eventuate)：Eventuate是一个工具包，用于构建由事件驱动和事件源服务组成的应用程序，由红牛开源。
* [Dewdrop](https://github.com/matsientst/dewdrop)：Dewdrop是一个固执己见、简单而强大的框架，用于在Java中实现事件源。
* [ES4j](https://github.com/eventsourcing/es4j)：Java事件捕获和查询框架。
* [Assembler](https://github.com/pellse/assembler)：Assembler是一个响应式、函数式、类型安全和无状态的数据聚合框架，用于查询和合并来自多个数据源/服务的数据。
* [Occurrent](https://github.com/johanhaleby/occurrent)：Occurrent是一个基于云事件规范的事件溯源库。
* [Concursus](https://github.com/opencredo/concursus)：Concursus是一个Java 8框架，用于构建使用CQRS和事件源模式以及Cassandra事件日志实现的应用程序。
* [Thoth](https://github.com/MAIF/thoth)：Thoth是一个Java库，它提供了在应用程序中实现事件源的工具包。
* [Wow](https://gitee.com/AhooWang/Wow)：Wow是一个基于领域驱动设计和事件溯源的现代响应式CQRS微服务开发框架。
* [FactCast](https://github.com/factcast/factcast)：基于PostgreSQL的简单EventStore。
* [Spine Event Engine](https://github.com/SpineEventEngine/core-java)：Spine Event Engine是一个Java框架，用于构建事件源和CQRS应用程序。
* [Kestrel](https://github.com/cultureamp/kestrel)：Kestrel是用于在Kotlin中构建事件溯源、CQRS应用程序的框架。

## 设计模式

#### 构建器模式

* [RecordBuilder](https://github.com/Randgalt/record-builder)：RecordBuilder是用于Java记录的记录构建器。
* [FreeBuilder](https://github.com/inferred/FreeBuilder)：FreeBuilder可以自动生成Java的构建器模式，由Google开源。
* [PojoBuilder](https://github.com/mkarneim/pojobuilder)：PojoBuilder是一个符合Java 6的注解处理器，可为POJO生成流式的构建器类。
* [Jilt](https://github.com/skinny85/jilt)：Jilt是一个Java注解处理器，用于自动生成实现构建器设计模式的类。
* [CallBuilder](https://github.com/google/CallBuilder)：CallBuilder是一个Java代码生成器，可以使创建构建器类变得容易，由Google开源。
* [AutoMatter](https://github.com/danielnorberg/auto-matter)：AutoMatter用于从定义为最小接口的值类型具体化值类和构建器。
* [Kotlin Builder](https://github.com/ThinkingLogic/kotlin-builder-annotation)：Kotlin与Java互操作的构建器注解，为Java客户端提供一种简洁的Kotlin对象构建方式。
* [Bob](https://github.com/jonas-grgt/bob)：Bob是Lombok @Builder注解的轻量级替代品。
* [Pojo Builder](https://github.com/jenzz/Java-PojoBuilder)：使用注解处理的构建器模式的Java代码生成器。

#### 代理模式

* [Apache Commons Proxy](https://github.com/apache/commons-proxy)：用于动态代理的Java库。
* [AutoProxy](https://github.com/OleksandrKucherenko/autoproxy)：在接口/抽象类之上生成代理类，允许拦截调用。
* [Dynamic Proxy](https://github.com/neoremind/dynamic-proxy)：Dynamic Proxy是用于Java生成代理对象的有用库。

#### 责任链模式

* [Apache Commons Chain](https://github.com/apache/commons-chain)：GoF责任链模式的实现。
* [Pie](https://github.com/feiniaojin/pie)：Pie是一个可快速上手的责任链框架。
* [Auto Pipeline](https://github.com/foldright/auto-pipeline)：Auto Pipeline是一个源代码生成器，可以自动生成组件的管道。

## 审计框架

* [Audit4j](https://github.com/audit4j/audit4j-core)：Audit4j是一个开源审计框架，专门设计用于捕获整个企业应用程序中各个组件生成和触发的审计事件。
* [JaVers](https://github.com/javers/javers)：Java的对象审计和差异框架。
* [Envers](https://hibernate.org/orm/envers)：Envers是Hibernate ORM的扩展，它提供了一种为实体添加审计/版本控制的简便方法。
* [Java Object Diff](https://github.com/SQiShER/java-object-diff)：Java Object Diff是一个简单但功能强大的库，用于查找Java对象之间的差异。
* [Fast Object Diff](https://github.com/colincatsu/fast-object-diff)：Fast Object Diff是一个对比Java相同对象内不同值的库。
* [Equator](https://github.com/dadiyang/equator)：一个用于比较两个对象的属性是否相等，并且可以获取所有不相等的属性的比对器。

## 原型工具

* [Penpot](https://github.com/penpot/penpot)：Penpot是第一个用于设计和代码协作的开源设计工具。
* [ForeUI](https://www.foreui.com/)：ForeUI是一款易于使用的UI原型工具，旨在为你想要的任何应用程序或网站创建模型/线框/原型。

## 工件仓库

* [Maven Central](https://central.sonatype.com/)：Maven Central是JVM语言最大的开源组件仓库。
* [JitPack](https://github.com/jitpack/jitpack.io)：JitPack是一个新颖的JVM和Android项目包仓库。
* [Artifactory](https://jfrog.com/artifactory/)：Artifactory是用于容纳和管理整个软件供应链中使用的所有工件、二进制文件、包、文件、容器和组件的单一解决方案。
* [Sonatype Nexus](https://github.com/sonatype/nexus-public)：Sonatype Nexus是一个由Sonatype开发的仓库管理工具，用于管理和托管各种软件构件。
* [Bintray](https://github.com/bintray)：Bintray是一个软件包分发平台，它提供了存储、发布和分发软件包的功能。
* [Indy](https://github.com/Commonjava/indy)：Indy是一个简单的仓库管理器，适用于Maven和其他使用Maven仓库格式的构建工具。
* [FOLib](https://github.com/BoCloud/folib)：FOLib是一个为AI研发而生、全语言软件供应链服务平台。
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
* [Hadess](https://github.com/tiklab-project/tiklab-hadess)：Hadess是一款开源、免费的制品管理工具，提供了高效、安全的制品存储和版本控制。

## 打包

* [Packr](https://github.com/libgdx/packr)：用于打包JAR、资源和JVM，以便在Windows、Linux和Mac OS X上分发。
* [IzPack](https://github.com/izpack/izpack)：IzPack是一种广泛使用的工具，用于将Java平台上的应用程序打包为跨平台安装程序。
* [Install4j](https://www.ej-technologies.com/products/install4j/overview.html)：Install4j是一个功能强大的多平台Java安装程序生成器，可生成Java应用程序的本机安装程序和应用程序启动器。
* [Conveyor](https://www.hydraulic.dev/)：Conveyor使得分发桌面应用程序变得像分发Web应用程序一样简单。
* [JavaPackager](https://github.com/fvarrui/JavaPackager)：JavaPackager是Maven和Gradle的混合插件，它提供了一种在本机Windows、MacOS或GNU/Linux可执行文件中打包Java应用程序并为其生成安装程序的简单方法。
* [JPackage](https://github.com/Akman/jpackage-maven-plugin)：JPackage插件允许你使用Java 14中引入的jpackage工具创建自定义运行时镜像/安装程序。
* [JApp](https://github.com/Glavo/japp)：JApp是一种现代Java程序打包格式。
* [ExeBuilder](https://gitee.com/qsyan/ExeBuilder)：ExeBuilder是一款利用JDK模块化的特性帮你把jar打包成独立exe的工具，它支持GUI和控制台应用程序的创建。
* [InstallAnywhere](https://www.revenera.com/install/products/installanywhere)：InstallAnywhere使开发人员可以轻松创建具有相同功能的专业安装软件。
* [YAJSW](https://github.com/yajsw/yajsw)：YAJSW是tanuki的Java服务包装器(JSW)的以Java为中心的实现。
* [Java Service Wrapper](https://wrapper.tanukisoftware.org/doc/english/home.html)：Java Service Wrapper是一种经过验证的企业级解决方案，已被数千家公司和开发人员使用，它极大地简化了Java应用程序在各种平台上的部署、启动和监控。
* [Apache Commons Daemon](https://github.com/apache/commons-daemon)：Commons Daemon是一组实用程序和Java支持类，用于将Java应用程序作为服务器进程运行。
* [Launch4j](https://launch4j.sourceforge.net/)：Launch4j是一个跨平台工具，用于将作为jar分发的Java应用程序包装在轻量级Windows本机可执行文件中。
* [JSmooth](https://github.com/BrunoReX/jsmooth)：JSmooth是一个Java可执行包装器，可构建启动Java应用程序的标准Windows可执行二进制文件(.exe)。
* [JSystemd](https://github.com/jpmsilva/jsystemd)：JSystemd旨在提供一个更好的平台来将Java应用程序与systemd集成，并将它们作为适当的操作系统服务运行。
* [Jar Jar Links](https://github.com/google/jarjar)：Jar Jar Links是一个实用程序，可以轻松地重新打包Java库并将它们嵌入到你自己的发行版中。
* [JNSM](https://gitee.com/eguid/java-nssm-service-manager)：Java开发的简单Windows服务安装管理工具，支持JAR包和EXE安装为Windows服务，并支持批量管理已安装服务。

## 部署

* [OneinStack](https://github.com/oneinstack/oneinstack)：OneinStack是一个PHP/Java部署工具。
* [Asgard](https://github.com/Netflix/asgard)：Asgard是一个基于Web的工具，用于管理基于云的应用程序和基础设施，由Netflix开源。
* [Cloudify](https://github.com/CloudifySource/cloudify)：Cloudify是一个开源的多云和边缘编排平台，由GigaSpaces开源。
* [Teletraan](https://github.com/pinterest/teletraan)：Teletraan是Pinterest的部署系统。
* [Capsule](https://github.com/puniverse/capsule)：Capsule是JVM应用程序的打包和部署工具。
* [Glu](https://github.com/pongasoft/glu)：Glu是一个免费/开源部署和监控自动化平台。
* [jDeploy](https://github.com/shannah/jdeploy)：jDeploy Github Action允许你在Github工作流中为Java项目生成本机桌面安装程序。
* [BDeploy](https://github.com/bdeployteam/bdeploy)：BDeploy是一款快速、可靠且可配置的部署解决方案，适用于任何类型的应用程序。
* [Stork](https://github.com/fizzed/stork)：Stork是一个轻量级实用程序的集合，用于通过填补Java构建系统和执行之间的空白来优化“构建后”工作流程，由Fizzed开发。
* [Riff Raff](https://github.com/guardian/riff-raff)：Riff Raff是卫报的部署平台。
* [JWrapper](https://www.jwrapper.com/)：JWrapper是一款高端现代Java安装程序，可用于部署Java应用程序。
* [Getdown](https://github.com/threerings/getdown)：Getdown是一个用于将Java应用程序部署到最终用户计算机并保持这些应用程序最新的系统。
* [Kayenta](https://github.com/spinnaker/kayenta)：Kayenta是一个自动金丝雀分析(ACA)平台，由Netflix和Google开源。
* [Rultor](https://github.com/yegor256/rultor)：Rultor是一个DevOps团队助理，它通过易于使用的直观聊天机器人界面帮助你自动执行日常操作(合并、部署和发布)。
* [JarManage](https://gitee.com/code2roc/jar-manage)：JarManage是一个可视化Jar包部署平台，让部署变得简单、快捷。
* [Liima](https://github.com/liimaorg/liima)：Liima自动化中间件允许你在无限数量的不同环境中管理各种版本的Java EE应用程序的配置，包括这些应用程序的自动部署。

## 运行

* [JBang](https://github.com/jbangdev/jbang)：JBang是一个命令行开发工具，用于以脚本形式运行Java程序。
* [Just](https://github.com/maciejwalkowiak/just)：Just是一个智能零配置命令行接口，用于在开发模式下运行Spring Boot应用程序。
* [Blaze](https://github.com/fizzed/blaze)：用于JVM的快速、灵活、通用脚本和应用程序启动堆栈，由Fizzed开源。
* [Jaz](https://learn.microsoft.com/en-us/java/jaz/overview)：Jaz是一款轻量级实用程序，可简化Java开发人员在Azure上运行其应用程序的方式，由Microsoft开发。
* [WinRun4j](https://github.com/poidasmith/winrun4j)：WinRun4j是适用于Windows的Java启动器。
* [CloudCaptain](https://cloudcaptain.sh/)：CloudCaptain是在AWS上运行JVM、Node.js和Go应用程序最简单、最可靠、最安全的方式。
* [Drip](https://github.com/ninjudd/drip)：Drip是Java虚拟机的启动器，它提供比java命令更快的启动时间。
* [Trampoline](https://github.com/ErnestOrt/Trampoline)：Trampoline是一个开源项目，可帮助你在开发阶段启动和停止基于Spring Boot的服务。
* [Layrry](https://github.com/moditect/layrry)：Layrry是一个启动器和Java API，用于执行模块化Java应用程序。
* [Nailgun](https://github.com/facebookarchive/nailgun)：Nailgun是一个客户端、协议和服务器，用于从命令行运行Java程序，而不会产生JVM启动开销，由Facebook开源。
* [SlimFast](https://github.com/HubSpot/SlimFast)：SlimFast是Java应用程序的一个工具，可帮助它们停止构建用于部署的Fat JAR，由HubSpot开源。
* [Update4j](https://github.com/update4j/update4j)：Update4j是第一个专为Java 9+设计的自动更新和启动器库。
* [Webapp Runner](https://github.com/heroku/webapp-runner)：Webapp Runner旨在让你使用简单的java -jar命令将文件系统上的解压或压缩的WAR文件启动到Tomcat容器中，由Heroku开源。

## REPL

* [JShell](https://docs.oracle.com/en/java/javase/11/tools/jshell.html)：JShell是一个用于学习Java编程语言和构建Java代码原型的交互式工具。
* [Java REPL](https://github.com/albertlatacz/java-repl)：Java REPL是Java语言的简单Read-Eval-Print-Loop。

## Java Web Start

* [OpenWebStart](https://github.com/karakun/OpenWebStart)：OpenWebStart提供了一个用户友好的安装程序，可以在更高的Java版本中使用Web Start/JNLP功能。
* [IcedTeaWeb](https://github.com/AdoptOpenJDK/IcedTea-Web)：IcedTeaWeb是JSR-56(Java Web Start)的开源实现。

## RPM

* [Redline](https://github.com/craigwblake/redline)：Redline是一个纯Java库，用于操作RPM包。
* [Eclipse Packager](https://github.com/eclipse/packager)：Eclipse Packager项目提供了一组核心功能，可在纯Java中使用RPM和Debian包文件。

## Java环境管理

* [SDKMAN](https://github.com/sdkman/sdkman-cli)：SDKMAN是一个用于在任何基于Unix的系统上管理多个软件开发套件的并行版本的工具。
* [jEnv](https://github.com/jenv/jenv)：Java环境管理器。
* [jEnv](https://github.com/linux-china/jenv)：jEnv是一个用于在任何系统(例如Linux、Mac和Windows)上管理Java开发套件并行版本的工具。
* [JC jEnv](https://github.com/chroblert/JC-jEnv)：Java版本切换工具，可以很方便的在Java的多个版本之间切换。
* [JEnv Windows](https://github.com/FelixSelter/JEnv-for-Windows)：只需一行命令即可更改当前的Java版本。
* [Jabba](https://github.com/shyiko/jabba)：Java版本管理工具，由Go语言开发。
* [IDE](https://github.com/devonfw/ide)：该工具旨在帮助开发人员设置开发环境，并能够在整个团队中共享相同的项目设置。
* [JVMS](https://github.com/ystyle/jvms)：适用于Windows的JDK版本管理器。

## API变更管理

* [Revapi](https://github.com/revapi/revapi)：Revapi是一个用于API分析和变更跟踪的工具。
* [Japicmp](https://github.com/siom79/japicmp)：Japicmp是一个比较Jar存档的两个版本的工具。
* [Clirr](https://clirr.sourceforge.net/)：Clirr是一个检查Java库与旧版本的二进制和源代码兼容性的工具。
* [@API Guardian](https://github.com/apiguardian-team/apiguardian)：提供@API注解的库，用于标注框架或应用程序中的公共类型、方法、构造函数和字段，以便发布它们的状态和稳定性级别，并指示它们的使用者如何使用API。

## 源代码转换

* [JSweet](https://github.com/cincheo/jsweet)：JSweet利用TypeScript通过JavaScript库和框架用Java编写丰富且响应迅速的Web应用程序。
* [Java2Typescript](https://github.com/raphaeljolivet/java2typescript)：Java2Typescript提供了一个Java REST服务定义和Typescript客户端之间的桥梁。
* [J2CL](https://github.com/google/j2cl)：J2CL是一个功能强大、简单且轻量级的从Java到Closure风格JavaScript的转译器，由Google开源。
* [J4TS](https://github.com/j4ts/j4ts)：J4TS基于GWT的JRE模拟库的一个分支，用Java编写，并使用JSweet转译器转译为TypeScript/JavaScript。
* [SWC4j](https://github.com/caoccao/swc4j)：SWC4j是一款基于JVM的超高速JavaScript和TypeScript编译和打包工具。
* [STJS](https://github.com/st-js/st-js)：STJS是一个开源的JavaScript代码生成器，它基于Java源码。
* [J2ObjC](https://github.com/google/j2objc)：J2ObjC是Google的开源命令行工具，可将Java源代码转换为适用于iOS(iPhone/iPad)平台的Objective-C。
* [Java2Script](https://github.com/java2script/java2script)：Java2Script提供了Eclipse Java到JavaScript的转译器(源到源编译器)以及Java运行时环境的近乎完整的JavaScript实现(包括AWT和Swing)。
* [J2C](https://github.com/arnetheduck/j2c)：J2C将Java代码转换为可编译的C++(11)代码。
* [Cobol4j](https://github.com/opensourcecobol/opensourcecobol4j)：COBOL4J是一个COBOL编译器，可以将COBOL程序转换为Java程序。

## 源代码浏览器

* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)：Sourcetrail是一个免费的开源跨平台源代码浏览器，可帮助你高效地处理不熟悉的源代码。
* [OpenGrok](https://github.com/oracle/opengrok)：OpenGrok是一个快速且可用的源代码搜索和交叉引用引擎，可以帮助你搜索、交叉引用和导航源树，由Oracle开源。
* [CodeSwarm](https://github.com/rictic/code_swarm)：CodeSwarm为源代码提供的漂亮可视化，由加州大学戴维斯分校开源。

## 企业软件开发

这里列出了各行业企业级开发的管理系统，包括CMS、低代码、ERP等。

#### 项目模板

* [PLMCodeTemplate](https://github.com/xwjie/PLMCodeTemplate)：Spring开发代码模板。
* [Spring Boot Microservices](https://github.com/rohitghatol/spring-boot-microservices)：用于微服务架构的Spring Boot模板。
* [AWS CloudFormation Template](https://github.com/widdix/aws-cf-templates)：AWS CloudFormation的免费模板。
* [Spring MVC Quickstart Maven Archetype](https://github.com/kolorobot/spring-mvc-quickstart-archetype)：该项目是Spring MVC Web应用程序的Maven原型。
* [Spring Boot Starter Kit](https://github.com/khandelwal-arpit/springboot-starterkit)：适用于Spring Boot应用程序的生产就绪入门套件。
* [Spring Boot Supabase](https://github.com/ChangeNode/spring-boot-supabase)：现代Java Web应用程序入门模板。
* [Celerio Angular Quickstart](https://github.com/jaxio/celerio-angular-quickstart)：从现有数据库模式生成一个Angular 5 CRUD应用。
* [Spring Boot MicroServices Template](https://github.com/anilallewar/microservices-basics-spring-boot)：使用Spring Boot和Spring Cloud创建完整微服务的基础架构框架。
* [Spring Boot Template](https://github.com/hmcts/spring-boot-template)：该模板的目的是加快新Spring应用程序的创建速度，并帮助在多个团队之间保持相同的标准，由英国法院及审裁处事务局开源。
* [Spring Boot Java Template](https://github.com/team-dodn/spring-boot-java-template)：基于Java的Spring Boot基本结构模板。
* [Spring Boot Starter](https://github.com/ericus20/spring-boot-starter)：适用于Spring Boot项目的完整模板，可用于生产环境。
* [Spring Boot Boilerplate](https://github.com/Genc/spring-boot-boilerplate)：Spring Boot Boilerplate是一个Starter套件，该项目包括Spring Boot、Spring Data JPA、Spring Validation、Spring Security、JWT、PostgreSQL、Mapstruct、Lombok、Swagger。
* [Element Vue SpringBoot Code Template](https://github.com/xwjie/ElementVueSpringbootCodeTemplate)：使用Vue、VueX、ElementUI、Spring Boot的代码框架。
* [Spring Microservices Boilerplate](https://github.com/danielliao11/spring-microservice-boilerplate)：Spring Microservices Boilerplate是一个方便Java后端人员快速开发的微服务脚手架。
* [Spring Boot Angular 2](https://github.com/borysn/spring-boot-angular2)：使用Spring Boot、Angular 2和Bootstrap 4来构建RESTful应用程序原型的启动项目。
* [Java Spring Boot Boilerplate](https://github.com/mewebstudio/java-spring-boot-boilerplate)：Java Spring Boot 3项目样板。
* [SpringBoot Kotlin Template](https://github.com/team-dodn/spring-boot-kotlin-template)：基于Kotlin的Spring Boot基础结构模板。
* [Spring Boot Starter Kit](https://github.com/khandelwal-arpit/springboot-starterkit-mysql)：适用于带有MySQL数据库的Spring Boot应用程序的生产就绪入门套件。
* [Spring Boot Init Template](https://github.com/AntonyCheng/spring-boot-init-template)：基于Java Web项目的Spring Boot框架初始化模板。
* [Spring Boot Application Template](https://github.com/AnanthaRajuC/Spring-Boot-Application-Template)：此代码库包含一个用于引导单体式Web应用的脚手架/配方。
* [JWT Starter](https://github.com/bfwg/springboot-jwt-starter)：适用于无状态和基于令牌的身份验证应用程序的Spring Boot JWT Starter套件。
* [Angular Spring Boot JWT Starter](https://github.com/bfwg/angular-spring-starter)：全栈入门套件，具有Angular 7、Spring Boot和无状态JWT身份验证。
* [Spring Boot MicroService Best Practices](https://github.com/abhisheksr01/spring-boot-microservice-best-practices)：此仓库整合了构建基于Spring Boot的健壮微服务的最佳实践和基本集成，它以模板形式提供，允许开发人员根据自身需求添加或删除依赖项，轻松创建自己的微服务。
* [Angular Node Java AI](https://github.com/ganatan/angular-node-java-ai)：Angular 20全栈Starter，配套Node.js、Spring Boot和AI。
* [Kotlin Swagger Spring Functional](https://github.com/cdimascio/kotlin-openapi-spring-functional-template)：Kotlin Spring WebFlux的项目模板。
* [Spring Boot AdminLTE](https://github.com/hendisantika/spring-boot-adminlte)：该应用包含Spring Boot和AdminLTE 2模板以促进开发。
* [Spring Boot API Seedling](https://github.com/Zoctan/spring-boot-api-seedling)：基于Spring Boot的种子项目，用于快速构建API、RESTFul API。
* [Spring Boot Vue Template Jwt](https://github.com/itbaima-study/SpringBoot-Vue-Template-Jwt)：Spring Boot 3、Vue 3前后端分离项目模版。
* [Spring Boot Nextjs Starter Kit](https://github.com/NerminKarapandzic/spring-boot-nextjs-starter-kit)：Spring Boot、Next.js项目模板。
* [Spring Boot Starter](https://github.com/savicprvoslav/Spring-Boot-starter)：Spring启动项目，包含预配置的JPA、Spring Security、配置文件、Swagger等。
* [Spring Boot RESTful Starter](https://github.com/lmarklil/springboot-restful-starter)：Spring Boot RESTful API脚手架。

#### 脚手架

* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Spring Boot API Project Seed](https://github.com/lihengming/spring-boot-api-project-seed)：Spring Boot API Project Seed是一个基于Spring Boot、MyBatis的种子项目，用于快速构建中小型API、RESTful API项目。
* [Spring Initializr](https://github.com/spring-io/initializr)：Spring Initializr提供了可扩展的API来生成基于JVM的项目。
* [Maku Generator](https://gitee.com/makunet/maku-generator)：Maku Generator是一款低代码生成器，可根据自定义模板内容，快速生成代码。
* [Jmix](https://github.com/jmix-framework/jmix)：Jmix是一组库和工具，用于加速Spring Boot以数据为中心的应用程序开发，由Haulmont开源。
* [Mendmix](https://gitee.com/dromara/mendmix-cloud)：Mendmix是一站式分布式开发架构开源解决方案及云原生架构技术底座，由dromara社区开源。
* [Seed4J](https://github.com/seed4j/seed4j)：Seed4J是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Jeddict](https://github.com/jeddict/jeddict-modeler)：Jakarta EE 10和MicroProfile应用程序生成器和建模器。
* [SoybeanAdmin Quarkus](https://github.com/soybeanjs/soybean-admin-quarkus)：SoybeanAdmin Quarkus是一个基于Kotlin和Quarkus的现代化后台管理系统脚手架。
* [Cola Cloud](https://gitee.com/leecho/cola-cloud)：Cola Cloud基于Spring Boot、Spring Cloud构建微服务架构企业级开发平台，集成OAuth2认证、集成短信验证码登录、FlyWay数据库版本管理、网关集成Swagger聚合所有服务API文档。
* [SpringRain](https://gitee.com/chunanyong/springrain)：SpringRain是Spring/Spring Boot的开发范例，基于K8S、Apisix/Istio实现云原生微服务。
* [MJGA](https://github.com/ccmjga/mjga-scaffold)：MJGA是一款现代化Java Web脚手架。
* [XDropWizard](https://github.com/knowm/XDropWizard)：一个快速启动的DropWizard Web应用程序，集成并演示了几个有用的开源项目。
* [Alpine](https://github.com/stevespringett/Alpine)：Alpine是一个专业的脚手架库，它以API优先的设计、安全的默认值和最小的依赖关系快速启动Java项目。
* [Bootify](https://bootify.io/)：Bootify帮助开发者快速生成应用程序的第一个版本，并遵循最佳实践和个人偏好。
* [Code Gen](https://gitee.com/durcframework/code-gen)：Code Gen是一款代码生成工具，可自定义模板生成不同的代码，支持MySQL、Oracle、SQL Server、PostgreSQL。
* [AiCode](https://gitee.com/wupaas/aicode)：新一代代码生成器，根据模板配置生成代码。
* [Generator Spring Boot](https://github.com/sivaprasadreddy/generator-springboot)：用于生成Spring Boot微服务的Yeoman生成器。
* [Spring Boot Code Generator](https://github.com/moshowgame/SpringBootCodeGenerator)：基于Spring Boot 2、Freemarker的Java代码生成器。
* [ApplicationPower](https://github.com/shalousun/ApplicationPower)：ApplicationPower是Maven项目的快速代码生成器。
* [BuildCLI](https://github.com/BuildCLI/BuildCLI)：BuildCLI是一个CLI工具，用于管理和自动化Java项目开发中的常见任务。
* [Micro Infra Spring](https://github.com/4finance/micro-infra-spring)：包含使用Spring配置设置的默认微服务基础设施的存储库。
* [Zero Ecotope](https://gitee.com/zero-ws/zero-ecotope)：Zero Ecotope是一个基于Vert.x的中间件容器，它可以帮助软件开发人员在Vert.x中快速开发和实施。
* [Twitter Bootstrap Scaffolding](https://github.com/robfletcher/twitter-bootstrap-scaffolding)：Twitter Bootstrap支持的Grails脚手架模板。
* [Taming Thymeleaf CLI](https://github.com/wimdeblauwe/ttcli)：该项目的目标是提供一个命令行工具，帮助设置使用JTE或Thymeleaf作为模板引擎。

#### 快速开发框架

* [ApiBoot](https://gitee.com/minbox-projects/api-boot)：ApiBoot是接口服务的落地解决方案，提供了一系列开箱即用的组件，通过封装来简化主流第三方框架的集成。
* [Ape Frame](https://gitee.com/classicChickenWings/ape-frame)：基于Spring Boot封装的轻量级开发框架。
* [Demoiselle](https://github.com/demoiselle/framework)：Demoiselle框架实现了集成框架的概念，其目标是通过最大限度地减少选择和集成专业框架的时间来促进应用程序的构建，从而提高生产力并保证系统的可维护性。
* [Synapse](https://github.com/americanexpress/synapse)：Synapse是一组用于快速开发的轻量级基础框架模块，内置企业级成熟度和质量，由美国运通开源。
* [Tiny](https://gitee.com/tinyframework/tiny)：企业级Java EE应用开发框架套件。
* [CXBOX](https://github.com/CX-Box/cxbox)：CXBOX的主要目标是加速基于Spring Boot的典型企业级应用程序的开发。
* [Fw Cloud Framework](https://github.com/liuweijw/fw-cloud-framework)：基于Spring Cloud全家桶开发分布式框架，实现基于Vue全家桶等前后端分离项目工程。
* [DevOps Boot](https://github.com/bkdevops-projects/devops-framework)：DevOps Boot是基于Spring Boot的微服务快速开发框架，由腾讯DevOps团队开发。
* [Hawaii Framework](https://github.com/hawaiifw/hawaii-framework)：Hawaii Framework是一个用于开发基于Spring的应用程序的Java框架，由ilionx开源。
* [Essencium Backend](https://github.com/Frachtwerk/essencium-backend)：Essencium是一个构建在Spring Boot之上的软件库，允许开发人员快速开始新的软件项目。
* [Spring Higher Order Components](https://github.com/jpomykala/spring-higher-order-components)：可加速Spring Boot开发的预配置组件。
* [AppBoot](https://github.com/sofn/AppBoot)：AppBoot是一个分布式的App服务端快速开发框架，包含了基本的权限认证、日志处理、接口防刷、系统监控等基本功能。
* [Axelor Open Platform](https://github.com/axelor/axelor-open-platform)：Axelor Open Platform是一个用于创建现代商业应用程序的开源Java框架。
* [Fust](https://github.com/zhihu/fust)：Fust是一个基于Spring Boot的快速开发框架，由知乎开源。
* [Zebra](https://gitee.com/gszebra/zebra)：Zebra是国信证券的微服务框架。
* [Spring Lemon](https://github.com/naturalprogrammer/spring-lemon)：Spring Boot Web应用程序的帮助库。
* [Assistant](https://github.com/Geniusay/Assistant)：Assistant是一个基于Spring Boot框架的后端开发工具。
* [Dew](https://github.com/gudaoxuri/dew)：微服务一站式解决方案，提供架构指南、容器优先/兼容Spring与Service Mesh的框架、最佳实践。
* [AngusInfra](https://github.com/xcancloud/AngusInfra)：AngusInfra是一个基于Spring Boot的快速开发基础框架，由晓蚕云公司开源。
* [Macula Boot](https://github.com/macula-projects/macula-boot)：Macula是一个微服务应用开发平台。
* [Arconia](https://github.com/arconia-io/arconia)：Arconia是一个Spring Boot的附加框架，旨在增强使用Java构建的现代企业应用程序。
* [Eden Architect](https://github.com/shiyindaxiaojie/eden-architect)：Eden Architect致力于提供企业开发的一站式解决方案。
* [Aooms](https://gitee.com/cyb-javaer/Aooms)：Aooms是基于Spring Cloud生态的微服务开发平台，不止于简单的框架集成。
* [Plasticene](https://github.com/plasticene/plasticene-boot-starter-parent)：Plasticene基于Spring Boot 2.x、Spring Cloud和Spring Cloud Alibaba企业级系统架构底层框架封装。
* [Holon](https://github.com/holon-platform/holon-core)：Holon是一个Java开发生态系统，用于创建和维护高质量、企业级的Web应用和服务。
* [Sitebricks](https://github.com/dhanji/sitebricks)：Sitebricks是一套简单的Web应用库。

#### 后台管理系统

* [RuoYi](https://gitee.com/zhijiantianya/ruoyi-vue-pro)：RuoYi是基于Spring Boot、MyBatisPlus、Vue实现的后台管理系统、微信小程序。
* [RuoYi Cloud](https://gitee.com/zhijiantianya/yudao-cloud)：RuoYi Cloud是基于Spring Cloud Alibaba、Gateway、Nacos、RocketMQ、Vue实现的后台管理系统、用户小程序。
* [RuoYi Fast Service](https://gitee.com/zccbbg/ruoyi-fast-service)：重写RuoYi Vue所有功能，集成SaToken、Mybatis Plus、SpringDoc、Hutool、OSS。
* [Vue Element Admin](https://github.com/PanJiaChen/vue-element-admin)：Vue Element Admin基于Vue、Spring Boot的最新开发堆栈，它具有内置的I18N解决方案、企业应用程序的典型模板以及许多很棒的功能。
* [Zheng](https://gitee.com/shuzheng/zheng)：Zheng是基于Spring、Spring MVC、Mybatis分布式敏捷开发系统架构，提供整套公共微服务模块。
* [ELADMIN](https://github.com/elunez/eladmin)：一个基于Spring Boot 2.7.18 、 Spring Boot JPA、JWT、Spring Security、Redis、Vue的前后端分离的后台管理系统。
* [Qingzhou](https://gitee.com/openeuler/qingzhou)：轻舟是一款开源的轻量级软件开发平台，其愿景是优化通用型Web管理软件的开发质量与效率，并实现不同类型软件的集中化统一管理，由华为开发。
* [XXL Boot](https://github.com/xuxueli/xxl-boot)：XXL Boot是一个快速开发平台，易学易用、简化开发、丰富扩展、开箱即用。
* [LAMP Cloud](https://github.com/dromara/lamp-cloud)：LAMP Cloud基于JDK 11、Spring Cloud、Spring Boot开发的微服务中后台快速开发平台，专注于多租户(SaaS架构)解决方案，由dromara社区开源。
* [RuoYi Vue Plus](https://gitee.com/dromara/RuoYi-Vue-Plus)：RuoYi Vue Plus是RuoYi Vue的重写，针对分布式集群与多租户场景全方位升级，由dromara社区开源。
* [NBCIO](https://gitee.com/nbacheng/nbcio-boot)：NBCIO亿事达企业管理平台。
* [Bingo](https://gitee.com/bingo-rain/bingo-cloud)：金融级Spring Cloud前后端微框架。
* [MicroServices Platform](https://gitee.com/zlt2000/microservices-platform)：MicroServices Platform是基于Spring Boot 2.x、Spring Cloud和Spring Cloud Alibaba并采用前后端分离的企业级微服务多租户系统架构。
* [SpringBlade](https://gitee.com/smallc/SpringBlade)：SpringBlade是一个由商业级项目升级优化而来的微服务架构。
* [Open Capacity Platform](https://gitee.com/dromara/open-capacity-platform)：OCP是基于Spring Cloud的企业级微服务框架，其目标是帮助企业搭建一套类似百度能力开放平台的微服务框架，由dromara社区开源。
* [Hope Boot](https://github.com/java-aodeng/hope-boot)：Hope Boot是一款现代化的脚手架项目。
* [AiDex Sharp](https://gitee.com/big-hedgehog/aidex-sharp)：AiDex Sharp基于Ruoyi Vue项目扩展，前端采用Ant Design Vue。
* [iBase4J](https://gitee.com/iBase4J/iBase4J)：iBase4J是Java语言的分布式系统架构，使用Spring整合开源框架。
* [EasyAdmin](https://gitee.com/lakernote/easy-admin)：基于Spring Boot 2、MybatisPlus、LayUI、MySQL前后端分离或一体的简单、轻量级的后台管理系统脚手架。
* [Freeter](https://gitee.com/xcOschina/freeter-admin)：飞特后台管理系统，企业级快速开发框架。
* [Opensabre](https://gitee.com/toopoo/SpringCloud)：Opensabre是基于Spring Cloud 2023的微服务开发平台，整合了Spring Security、Spring Cloud Alibaba等组件。
* [Base Admin](https://github.com/huanzi-qch/base-admin)：Base Admin是一套简单通用的后台管理系统。
* [Admin3](https://github.com/cjbi/admin3)：一个轻巧的后台管理框架，项目后端基于Java 21、Spring Boot 3.2。
* [88YBG](https://gitee.com/YYDeament/88ybg)：以Spring Boot为中心，模块化开发系统，用户可以随意删减除权限框架外任意的系统模块。
* [XiaoMaYi EleVue](https://gitee.com/xiaomayicloud/XiaoMaYi-EleVue)：基于Spring Boot 3、Spring Security、Mybatis Plus、Vue3、TypeScript、Vite、ElementPlus、MySQL等技术栈实现的单体前后端分离后台管理系统。
* [MSFM](https://gitee.com/wanglingxiao/mysiteforme)：MSFM是一个基于Spring Boot开发的轻量级系统脚手架，旨在帮助开发者快速搭建属于自己的系统后台。
* [Crown](https://gitee.com/cancerGit/Crown)：Crown是基于Spring Boot 2构建的Web应用快速开发脚手架。
* [JPower](https://gitee.com/gdzWork/JPower)：JPower致力于实现集各种工具于一体的微服务管理框架。
* [JeeWeb](https://gitee.com/dataact/jeeweb)：JeeWeb是一款基于Spring Boot 2、Spring、Mybatis、Hibernate的敏捷开发系统。
* [CloudDo](https://gitee.com/lcg0124/clouddo)：CloudDo是基于Spring Cloud和Vue微服务，前后端分离的后台管理框架。
* [AOSuite](https://gitee.com/xiong-chun/AOSuite)：AOSuite基于Java EE技术体系，是一个帮助企业快速实现业务需求的全栈式技术开发框架&解决方案。
* [Pangu](https://gitee.com/xiong-chun/pangu-framework)：盘古开发框架是一套轻量稳健的工业级前、中、后台三维多端行业数字化赋能开发基座。
* [Spring Boot Plus](https://github.com/geekidea/spring-boot-plus)：Spring Boot Plus是一个简单易用、高速、高效、功能丰富的开源Spring Boot脚手架。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：X-SpringBoot是一个轻量级的Java快速开发平台。
* [BootDo](https://gitee.com/lcg0124/bootdo)：BootDo是高效率、低封装、面向学习型、微服务的开源Java EE开发框架。
* [MDP Core](https://gitee.com/maimengcloud/mdp-core)：多功能、高效率、低代码的前后端一体化、智能化的开发平台。
* [Dante Cloud](https://gitee.com/dromara/dante-cloud)：Dante Cloud国内首个支持阻塞式和响应式服务并行的微服务平台。
* [Flink Boot](https://github.com/intsmaze/flink-boot)：Flink Boot脚手架让Flink全面拥抱Spring生态体系，使得开发者可以以Java Web开发模式开发出分布式运行的流处理程序。
* [Web Flash](https://github.com/enilu/web-flash)：Web Flash是一个基于Spring Boot和Vue.js的Web系统。
* [SpringCloud](https://github.com/zhoutaoo/SpringCloud)：基于Spring Cloud 2.1的微服务开发脚手架。
* [Liugh](https://github.com/qq53182347/liugh-parent)：实现RESTful快速开发的后端脚手架。
* [ES](https://github.com/zhangkaitao/es)：ES是一个Java EE企业级项目的快速开发的脚手架，提供了底层抽象和通用功能。
* [SOP](https://gitee.com/durcframework/SOP)：SOP是一个开放平台解决方案项目，基于Spring Cloud实现，目标让用户快速搭建自己的开放平台。
* [Wind](https://gitee.com/sunseagear/wind)：飞廉是一个完全开源的开发平台，基于Spring Boot 3和Vue 3。
* [Bootx](https://gitee.com/bootx/bootx-platform)：后端基于Spring Boot，前端基于Antd Vue 3打造，可应用在不同业务场景中，目标是致力实现媲美商业版应用脚手架。
* [Roses](https://gitee.com/stylefeng/roses)：Roses基于Spring Boot 3、JDK 17，是开源项目Guns的核心支撑层。
* [JBolt](http://jbolt.cn/)：基于JFinal打造的企业级Java Web框架核心库，通过链式SQL构建器、约定优于配置和丰富的功能模块，让Java Web开发变得简单、高效。
* [NutzWk](https://github.com/Wizzercn/NutzWk)：NutzWk开源企业级Java Web开发框架。
* [BallCat](https://github.com/ballcat-projects/ballcat)：BallCat是一个快速开发脚手架，快速搭建企业级后台管理系统，并提供多种便捷Starter进行功能扩展。
* [Mall Tiny](https://github.com/macrozheng/mall-tiny)：Mall Tiny是一款基于Spring Boot、MyBatisPlus的快速开发脚手架。
* [AgileBoot](https://github.com/valarchie/AgileBoot-Back-End)：AgileBoot是一套开源的全栈精简快速开发平台。
* [Y9 Digital Infrastructure](https://github.com/risesoft-y9/Digital-Infrastructure)：基于Spring Boot、Vue前后端分离的Java快速开发框架，由北京有生博大软件开发。
* [Vole](https://github.com/gavenwangcn/vole)：Vole是一个基于最新的Spring Cloud 2.0的微服务商业开发脚手架。
* [Spring Boot V2](https://gitee.com/bdj/SpringBoot_v2)：Spring Boot V2项目是努力打造Spring Boot框架的极致细腻的脚手架。
* [Slife](https://gitee.com/jamen/slife)：Slife是一个使用Spring Boot搭建的企业级快速开发脚手架。
* [Maozi](https://github.com/1095071913/maozi-cloud-parent)：Maozi基于Spring Cloud Alibaba、Dubbo二开封装。
* [JBone](https://github.com/417511458/jbone)：JBone基于Spring Cloud框架开发，旨在为中小企业提供稳定的微服务解决方案，为开发人员提供基础开发骨架。
* [HsWeb](https://github.com/hs-web/hsweb-framework)：HsWeb是一个基于Spring Boot开发，使用全响应式编程的企业级后台管理系统基础项目。
* [Source Vue](https://gitee.com/open-source-byte/source-vue)：Source Vue是基于Spring Boot、Vue前后端分离的Java快速开发框架。
* [SaPlus](https://gitee.com/click33/sa-plus)：SaPlus是一个基于Spring Boot的快速开发框架，内置代码生成器。
* [JavaFX Falsework](https://gitee.com/lwdillon/fx-falsework)：基于JavaFX、Spring Boot开发的客户端与服务端系统开发脚手架。
* [XBoot](https://github.com/Exrick/xboot)：XBoot是基于Spring Boot 2.x的一站式前后端分离快速开发平台。
* [Snowy](https://gitee.com/xiaonuobase/snowy)：Snowy是国内首个国密前后端分离快速开发平台，集成国密加解密插件，软件层面完全符合等保测评要求，同时实现国产化机型、中间件、数据库适配。
* [FCat](https://gitee.com/softnetcat/FCat)：FCAT是企业级基础功能框架，软件巢工作室出品。
* [Vben](https://gitee.com/vben/vben-java)：Vben一个开箱即用的Java快速开发平台。
* [AXBoot Framework](https://github.com/axboot/ax-boot-framework)：AXBoot是使用Java和HTML5的全栈Java Web应用程序框架。
* [J2eeFAST](https://gitee.com/dromara/J2EEFAST)：J2eeFAST是一个Java EE企业级快速开发平台，致力于打造中小企业最好用的开源免费的后台框架平台，由dromara社区开源。
* [JVS](https://gitee.com/software-minister/jvs)：JVS是企业级应用构建的基础脚手架，提供开箱即用的基础功能集成，其中集成了账户管理、租户管理、用户权限体系、三方登录、环境配置、各种业务日志等功能，还提供了对接低代码、数据中台的能力。
* [MMS](https://gitee.com/mmsAdmin/mms)：MMS是一款灵活、高效、低代码模块化管理系统。
* [Pit](https://gitee.com/xfcode-source/pit)：Pit是基于Java构建的标准化企业级开发平台。
* [VBoot](https://gitee.com/zsvg/vboot-java)：VBoot是一个开箱即用的快速开发平台。
* [LikeAdmin](https://gitee.com/likeadmin/likeadmin_java)：LikeAdmin是一套快速开发管理后台，使用Spring Boot 2.5、MyBatis Plus、TypeScript、Vue 3、Vite 2、Element Plus 1.2。
* [XueYi MultiSaas](https://gitee.com/xueyitiantang/XueYi-MultiSaas)：基于Vue3/TypeScript/Ant-Design UI和Spring Cloud Alibaba/Mybatis-Plus的多租户SaaS开发框架。
* [Pear Admin Boot](https://gitee.com/pear-admin/Pear-Admin-Boot)：Pear Admin Boot是基于Spring Boot生态、权限、工作流的开发平台。
* [金合技术中台](https://gitee.com/ikingtech/iking-platform)：现代化的下一代企业级技术中台，简洁、高效、稳定、开源。
* [MLDong](https://gitee.com/mldong/mldong)：MLDong是基于Spring Boot、Vue 3的快速开发平台、自研工作流引擎。
* [ContiNew Admin](https://github.com/continew-org/continew-admin)：ContiNew Admin是持续迭代优化的前后端分离中后台管理系统框架。
* [TwelveT](https://github.com/twelvet-projects/twelvet)：基于Spring Boot 3.X的Spring Cloud Alibaba/Spring Cloud Tencent + React的微服务框架。
* [JSite](https://gitee.com/baseweb/JSite)：JSite快速开发框架，内置Flowable工作流引擎。
* [Spring Boot Manager](https://gitee.com/zwens/springboot-manager)：基于Spring Boot、Mybatis Plus、SaToken、Thymeleaf、Layui的后台管理系统。
* [HxyFrame](https://gitee.com/soEasyCode/hxyFrame)：HxyFrame是一个后台管理系统，采用Spring MVC、Mybatis、Shiro、Redis、Ehcache开发。
* [Zjmzxfzhl](https://gitee.com/zjm16/zjmzxfzhl)：Zjmzxfzhl集成了Spring Boot、Flowable、Vue、ElementUI、FormGenerator，采用前后端分离架构。
* [JFinal LayUI](https://gitee.com/QinHaiSenLin/Jfinal-layui)：JFinal LayUI极速企业应用开发管理系统。
* [FHS Framework](https://gitee.com/fhs-opensource/fhs-framework)：FHS Framework是一个集成了国内外诸多优秀开源项目的快速开发平台。
* [Spring Boot Plus](https://gitee.com/xiandafu/springboot-plus)：Spring Boot Plus是一个基于Spring Boot 2的管理后台系统。
* [EuBackend](https://gitee.com/zhaoeryu/eu-backend)：EuBackend是一套全部开源的前后端分离Java EE企业级快速开发平台。
* [Remi](https://gitee.com/remi-top/remi-cloud)：Remi Cloud是一款企业级AI、微服务架构的快速开发平台。
* [Campus](https://github.com/oddfar/campus)：Campus是一款简单的后台管理系统、快速开发框架。
* [TaoTao Cloud](https://github.com/shuigedeng/taotao-cloud-project)：基于JDK 21，支持GraalVM 21，采用最新的Spring Boot、SpringCloud、Spring Security、Nacos、Mybatis Plus等框架开发的微服务开发脚手架。
* [Sz Admin](https://github.com/feiyuchuixue/sz-boot-parent)：Sz Admin是一个基于Spring Boot 3、Vue 3和Element-Plus的开源中后台管理框架。
* [Albedo](https://github.com/somowhere/albedo)：Albedo是一个Java企业应用开源框架。
* [Framework Admin](https://gitee.com/backflow/framework-admin)：极简封装的Java平台快速开发框架。
* [SmallBoot](https://gitee.com/zhengqingya/smallboot)：SmallBoot是Vue、Spring Boot前后端分离的项目快速开发脚手架。
* [VueAdmin](https://github.com/MarkerHub/VueAdmin)：基于Spring Boot、JWT、Vue的前后端分离后台管理系统。
* [FrSimple](https://gitee.com/frsimple/frsimple-boot)：一个开箱即用的中后端解决方案。
* [YF](https://gitee.com/fateyifei/yf)：YF后台管理系统，使用Spring Boot 3、Java 21、Vue 3和TypeScript开发。
* [Naive Admin](https://www.naiveadmin.com/)：开箱即用的企业级前后端框架。
* [PanisBoot](https://github.com/paynezhuang/panis-boot)：PanisBoot是一款现代化的后台管理系统脚手架，基于Spring Boot 3进行开发。
* [EMS Admin](https://github.com/ems-admin/ems-admin-vue3)：EMS Admin是一套极简的后台管理系统。
* [CyreneAdmin](https://gitee.com/momoljw/CyreneAdmin)：CyreneAdmin是一个现代化的后台管理系统，提供双框架支持(Spring Boot、Solon)。
* [RuoQus](https://github.com/zhu8915985/ruoqus)：基于Quarkus的RuoYi权限管理系统。
* [Boot Admin](https://github.com/hb0730/boot-admin)：Boot Admin是一个基于Spring Boot 3和Vue 3的SaaS管理后台开源项目。

#### 低代码

* [Appsmith](https://github.com/appsmithorg/appsmith)：Appsmith是一个开源低代码平台，可简化自定义应用程序的开发、部署和维护。
* [JeecgBoot](https://github.com/jeecgboot/JeecgBoot)：JeecgBoot是一款基于AIGC和低代码引擎的AI低代码平台，旨在帮助开发者快速实现低代码开发和构建、部署个性化的AI应用，由北京国炬公司开发。
* [OutSystems](https://www.outsystems.com/)：OutSystems是一个由人工智能驱动的低代码平台。
* [APITable](https://github.com/apitable/apitable)：APITable是一个面向API的低代码平台，用于构建协作应用程序。
* [JeeSite](https://gitee.com/thinkgem/jeesite5)：JeeSite是一个轻量级、企业级低代码解决方案，由济南卓源软件公司开源。
* [Guns](https://gitee.com/stylefeng/guns)：Guns是一个现代化的Java应用开发框架，基于主流技术Spring Boot 2、Vue 3。
* [MakuBoot](https://gitee.com/makunet/maku-boot)：MakuBoot是采用Spring Boot 3.1、Spring Security 6.1、MybatisPlus等框架开发的一套Spring Boot低代码开发平台。
* [GoView](https://gitee.com/dromara/go-view)：GoView是一个Vue 3搭建的低代码数据可视化开发平台，将图表或页面元素封装为基础组件，无需编写代码即可完成业务需求。
* [OpenXava](https://github.com/openxava/openxava)：OpenXava从JPA实体生成功能齐全的Web应用程序。
* [Magic API](https://gitee.com/ssssssss-team/magic-api)：Magic API是一个基于Java的接口快速开发框架。
* [MateCloud](https://gitee.com/matevip/matecloud)：MateCloud是一款基于Spring Cloud Alibaba的微服务架构，支持多租户的低代码平台。
* [DiBoot](https://gitee.com/dibo_software/diboot)：Diboot是一个在开发框架上构建的低代码平台，由苏州帝博软件公司开源。
* [Mendix](https://www.mendix.com/)：Mendix是一个低代码平台，由Siemens开发。
* [OPSLI](https://github.com/hiparker/opsli-boot)：OPSLI是一款快速的低代码平台，零代码开发，致力于做更简洁的后台管理系统。
* [Panshi](https://gitee.com/aizuda/panshi)：稳定可靠的Web开发框架，由爱组搭维护。
* [Structr](https://github.com/structr/structr)：Structr是一个使用图数据库的集成低代码开发和运行时环境。
* [DBAPI](https://gitee.com/freakchicken/db-api)：DBAPI是一个面向数仓开发人员的低代码工具，只需在页面上编写SQL，并配置好参数，就可以自动生成HTTP接口。
* [Rocket API](https://gitee.com/alenfive/rocket-api)：API敏捷开发框架，用于API接口功能的快速开发。
* [Citrus](https://github.com/Yiuman/citrus)：低代码快速开发脚手架，灵活、高效。
* [TinyEngine](https://github.com/opentiny)：TinyEngine支持开发者定制低代码平台，实时在线构建低代码平台，并支持二次开发或集成低代码平台能力，由华为开发。
* [Convertigo](https://github.com/convertigo/convertigo)：Convertigo是一个开源的低代码和无代码平台，用于移动和Web应用程序开发以及后端即服务。
* [Orienteer](https://github.com/OrienteerBAP/Orienteer)：Orienteer是一个灵活的业务应用平台，它可以让你构建功能齐全的专用企业应用程序，例如CRM、ERP、供应链管理应用程序等。
* [Open Lowcode](https://github.com/openlowcode/Open-Lowcode)：Open Lowcode允许组织快速开发特定的应用程序，并以最低的预算扩展它们。
* [Portofino](https://github.com/ManyDesigns/Portofino)：Portofino是一个低代码工具，用于构建模型驱动的REST API和Web应用程序。
* [Skyeye](https://gitee.com/dromara/skyeye)：采用Spring Boot、WinUI、UNI-APP、Ant Design Vue的低代码平台开发模式。
* [Erupt](https://gitee.com/erupt/erupt)：Erupt是一个低代码全栈类框架，使用Java注解动态生成页面以及增删改查、权限控制等后台功能。
* [UBML](https://gitee.com/ubml/ubml-sdk)：UBML是开放原子开源基金会下的项目，它是一种用于快速构建应用软件的低代码领域建模语言，来源于浪潮海岳iGIX团队。
* [Juggle](https://gitee.com/Somta/Juggle)：Juggle是一个可用于接口编排、定制开发等场景的一套完整解决方案。
* [MDP LCode](https://gitee.com/maimengcloud/mdp-lcode-backend)：唛盟LCode旨在为企业开发业务系统提供一整套解决方案，具有高效率、低代码、功能丰富等特点。
* [MetaLowCode](https://gitee.com/MetaLowCode/MetaLowCode)：美乐是一个低代码开发平台，包含一个前端项目Meta LowCode和一个后端项目Meta Server，由极昇数科开源。
* [VLife](https://gitee.com/wwwlike/vlife)：VLife是一套采用前后端分离(Java + React)架构的企业级低代码研发平台。
* [MFish](https://gitee.com/qiufeng9862/mfish-nocode)：MFish是一款致力于让开发像摸鱼一样轻松的低代码/无代码平台。
* [Skyve](https://github.com/skyvers/skyve)：Skyve是一个开源低代码平台，可让你访问构建复杂、强大且可扩展的云解决方案所需的所有关键功能。
* [WaveMaker](https://www.wavemaker.com/)：WaveMaker是一个基于Java的低代码开发平台。
* [SmartAdmin](https://gitee.com/lab1024/smart-admin)：SmartAdmin是1024创新实验室使用Spring Boot 2和Vue 3开发出的一套简洁、易用的低代码中后台解决方案。
* [EOVA](https://gitee.com/eova/eova)：EOVA是一个基于JFinal的国产低代码开发平台。
* [Dashjoin](https://github.com/dashjoin/platform)：Dashjoin是一个开源和云原生低代码开发和集成平台，可帮助团队更快地交付应用程序。
* [Wukong](https://github.com/WuKongOpenSource/Wukong_nocode)：通过悟空无代码平台开发工具，企业可自主地快速开发出适合企业需要的信息化系统。
* [Yuncheng](http://www.yunchengxc.com/)：云程是一款支撑企业级应用系统快速开发的低代码开发平台。
* [Nop-Entropy](https://gitee.com/canonical-entropy/nop-entropy)：Nop Platform 2.0是基于可逆计算理论实现的采用面向语言编程范式的新一代低代码开发平台。
* [Orange Admin](https://gitee.com/orangeform/orange-admin)：橙单中台化低代码生成器，可完整支持多应用、多租户、多渠道、工作流、在线表单、自定义数据同步、自定义Job、多表关联、跨服务多表关联、框架技术栈自由组合等。
* [H5VE](https://gitee.com/h5ve/h5ve-boot)：H5VE是一个以数据驱动、AI编程为核心的企业级低代码开发平台。
* [Joget](https://github.com/jogetworkflow/jw-community)：Joget是下一代开源无代码/低代码应用程序平台，可实现更快、更简单的数字化转型。
* [VisionX](https://visionx.sibvisions.com/)：VisionX是一个开放的低代码平台，由SIB Visions公司开发。
* [LsFusion](https://github.com/lsfusion/platform)：LsFusion是一个免费的开源平台，用于基于同名第五代编程语言的信息系统开发。
* [JECloud](https://gitee.com/ketr/jecloud)：JECloud平台后端采用微服务架构，前端采用微应用架构，可做到不同服务使用不同数据库独立运行，由北京凯特伟业公司开源。
* [Bsin PaaS](https://gitee.com/s11e-DAO/bsin-paas-all-in-one)：Bsin-PaaS是一套企业级的低代码、零代码去中心化应用搭建平台，可帮助企业快速搭建基于云原生的有竞争力的业务中台、流程中台、业务前台。
* [PagePlug](https://github.com/cloudtogo/pageplug)：PagePlug是Appsmith的中国化项目，是一个开源、声明式、可视化的前端低代码框架，可以用来制作Web应用、微信小程序。
* [Crabc](https://gitee.com/linebyte/crabc)：Crabc是低代码接口开发平台，企业级API管理系统，深度整合Spring Boot和Mybatis实现动态数据源和动态SQL。
* [iPLAss](https://github.com/dentsusoken/iPLAss)：iPLAss是一个基于Java的低代码开发平台，主要目的是提高企业级系统开发的生产力，由电通综合研究所开源。
* [AsmoBoot](https://github.com/RotaNova/asmoboot)：AsmoBoot是基于Spring Boot开发的快速开发框架，由福建新航科技公司开源。
* [Dont Code](https://dont-code.net/)：Dont-Code是一个低代码/无代码平台，允许用户基于IT开发的完整功能集创建自己的应用程序。
* [Nussknacker](https://github.com/TouK/nussknacker)：Nussknacker是一款低代码可视化工具，可供领域专家构建、运行和监控实时决策算法，而不是在代码中实现它们。
* [JeeLowCode](https://gitee.com/jeelowecode/JeeLowCode)：JeeLowCode是一款基于芋道源码精心二次封装的企业级低代码开发框架。
* [Gemini](https://github.com/gemini-projects/gemini)：云原生和低代码平台，可在几分钟内创建全栈Web管理应用程序。
* [Oinone](https://gitee.com/oinone/oinone-pamirs)：Oinone是一个赋能企业标准化研发和敏捷交付的统一低代码平台，由数式科技开发。
* [MuYun](https://github.com/ximatai/MuYun)：MuYun是一个云原生、开发者优先、前后端分离、按需插拔的轻代码平台。
* [Aware IM](https://www.awareim.com/)：Aware IM是一款低代码Web应用构建器，专为快速、稳定且可扩展的开发而设计，由Awaresoft开发。
* [Informat](https://www.informat.cn/)：织信是基石协作科技自研的低代码应用构建平台。
* [MyApps](http://www.teemlink.com/myapps/)：MyApps是天翎自主研发的第四代可视化低代码快速开发平台。
* [Seezoon Stack](https://github.com/734839030/seezoon-stack)：Seezoon Stack是一款基于当前最前沿的前端和后台框架实现的低代码开发平台。
* [SQLREST](https://gitee.com/inrgihc/sqlrest)：SQLREST是一个开源项目，旨在提供一种简单而强大的方式来将SQL查询转化为RESTful API。
* [Z平台](https://gitee.com/zj1983/zz)： Z平台是开源免费的Java低代码开发平台，通过动态配置的方式能够快速开发各类Web管理系统。
* [Eclipse Sirius Web](https://github.com/eclipse-sirius/sirius-web)：Eclipse Sirius Web是一个轻松创建和部署工作室到Web的框架。
* [JUDO](https://www.judo.codes/)：JUDO是一个针对创建和运行企业应用优化的低代码开发工具箱。
* [Openkoda](https://github.com/openkoda/openkoda)：即用型开发平台，可加速构建业务应用程序和内部工具的过程。
* [Stratoflow](https://stratoflow.com/java-open-source-low-code-platform/)：Java开源低代码，简化并加快企业SaaS系统的开发。
* [Quick Boot](https://github.com/csx-bill/quick-boot)：基于AMIS前端框架、Spring Boot后端框架构建的企业级低代码开发平台。

#### 权限管理系统

* [Pig](https://gitee.com/log4j/pig)：Pig是基于Spring Boot 3.0、Spring Cloud 2022 & Alibaba、SAS OAuth2的微服务RBAC权限管理系统。
* [RenRen Security](https://gitee.com/renrenio/renren-security)：RenRen Security是采用Spring Boot、MyBatisPlus、Shiro、Vue 3、ElementPlus等框架开发的一套权限系统。
* [Cloud Platform](https://gitee.com/geek_qi/cloud-platform)：Cloud Platform是基于Spring Cloud微服务化RBAC的管理平台。
* [Surpass](https://gitee.com/tomsun28/bootshiro)：Surpass是基于Spring Boot、Sureness的面向REST API资源无状态认证权限管理系统的后端。
* [Dillon Admin Pro](https://gitee.com/lwdillon/dillon-admin-pro)：基于JavaFX、Java Swing、Spring Boot开发的权限管理系统。
* [Pro Cloud](https://gitee.com/gitsc/pro-cloud)：Pro Cloud是一个Security作为安全框架，基于OAuth2的RBAC权限管理微服务系统。
* [Pre](https://gitee.com/li_haodong/pre)：Pre是基于Spring Boot、Spring Security、Vue的前后端分离的的RBAC权限管理系统。
* [Kitty](https://gitee.com/liuge1988/kitty)：基于Spring Boot、Spring Cloud、Vue.js、Element UI实现，采用前后端分离架构的权限管理系统。
* [Youlai Boot](https://gitee.com/youlaiorg/youlai-boot)：基于JDK 17、Spring Boot 3、Spring Security 6、JWT、Redis、Mybatis Plus、Vue 3、Element-Plus构建的前后端分离单体权限管理系统。
* [AuthX](https://gitee.com/devlive-community/authx)：AuthX是一个简单、易用的开源权限管理平台，旨在帮助开发者轻松地实现基于角色的访问控制(RBAC)和权限管理。
* [JeeSpringCloud](https://gitee.com/JeeHuangBingGui/jeeSpringCloud)：基于Spring Boot 2.0的后台权限管理系统，界面简洁美观。
* [Cool Admin](https://github.com/cool-team-official/cool-admin-java)：Cool Admin后台权限管理系统，开源免费、AI编码、流程编排、模块化、插件化，用于快速构建后台应用程序。
* [Spring Boot Vue Admin](https://github.com/Zoctan/spring-boot-vue-admin)：Spring Boot Vue Admin提供一套后台权限管理模板。

#### 商城系统

* [微同商城](https://gitee.com/fuyang_lipengjun/platform)：减少重复造轮子，开源微信小程序商城。
* [智汇商城](https://gitee.com/catshen/zhsc)：智汇商城是一款持续更新得轻量级、高性能、前后端分离的电商系统。
* [Mall](https://github.com/macrozheng/mall)：Mall项目致力于打造一个完整的电商系统，采用现阶段主流技术实现。
* [Xbin Store](https://github.com/xubinux/xbin-store)：模仿国内知名B2C网站，实现的一个分布式B2C商城。
* [RuoYi Mall](https://gitee.com/zccbbg/RuoYi-Mall)：一个基于若依框架，Spring Boot 2、MybatisPlus、Spring Security、JWT、Redis、Vue、Taro的前后端分离商城系统。
* [SuperMarket](https://github.com/ZongXR/SuperMarket)：设计精良的网上商城系统，使用Spring Cloud框架，基于Java开发。
* [Funit](https://github.com/fushengqian/fuint)：Funit是一套开源的实体店铺会员管理和营销系统。
* [CongoMall](https://github.com/nageoffer/congomall)：刚果商城是个从零到一的C端商城项目，包含商城核心业务和基础架构两大模块。
* [Smart](https://gitee.com/52itstyle/spring-boot-seckill)：小柒商城专注赋能开发者，匠心打造高效能、全渠道、多场景电商系统。
* [Lilishop](https://gitee.com/beijing_hongye_huicheng/lilishop)：Lilishop是基于Spring Boot的开源商城，由北京宏业汇成科技公司开发。
* [JooLun WX](https://gitee.com/joolun/JooLun-wx)：Java免费开源商城，小程序、公众号管理，采用Java、Spring Boot 3、Vue 3、Element-Plus开发。
* [Open Shop](https://gitee.com/old-peanut/wechat_applet__open_source)：Open Shop小程序商城，包括分销、团购、秒杀、优惠券、等功能。
* [SmartShop](https://gitee.com/52itstyle/spring-boot-pay)：小七商城系统支持商家入驻，后端基于Spring Boot研发，前端使用Vue、UniApp开发。
* [CRMEB](https://gitee.com/ZhongBangKeJi/crmeb_java)：CRMEB开源商城系统Java版，基于Java、Vue、UniApp开发。
* [ZKMall](https://gitee.com/zkmall/b2b2c)：ZKMall是一款基于当前流行技术组合Spring Boot 3、MybatisPlus、Shiro、JWT、XXL-Job、Redisson、Redis、Mysql、Vue3、UniApp前后端分离B2B2C多商户Java电商系统。
* [GPMall](https://github.com/2227324689/gpmall)：基于Spring Boot、Dubbo构建的电商平台。
* [GoShop](https://github.com/pzhgugu/goshop2)：分布式多店铺电商系统。
* [Uni4Mall](https://gitee.com/mallcloud/uni4mall)：基于Spring Boot、MyBatis Plus的电商系统，包括前台商城系统及后台管理系统。
* [Laiketui](https://gitee.com/laiketui/open)：来客推商城系统。
* [LiteMall](https://github.com/linlinjava/litemall)：基于Spring Boot、Vue的小商场系统。
* [DTS Mall](https://gitee.com/qiguliuxing/dts-shop)：聚惠星商城DTS-SHOP，基于微信小程序、Spring Boot、Vue构建，支持单店铺、多店铺入驻的商城平台。
* [Lenosp](https://gitee.com/zzdevelop/lenosp)：Lenosp是基于Spring Boot的脚手架，提供完善社区文档教程。
* [Mall4j](https://gitee.com/gz-yami/mall4j)：Mall4j商城系统致力于为中小企业打造一个完整、易于维护的开源的电商商城系统，采用现阶段流行技术实现。
* [Unimall](https://gitee.com/iotechn/unimall)：Unimall针对中小商户、企业和个人学习者开发。
* [Timo](https://gitee.com/aun/Timo)：基于Spring Boot 2.0、Spring Data JPA、Thymeleaf、Shiro开发的后台管理系统。
* [KxMall](https://gitee.com/zhengkaixing/kxmall)：KxMall生鲜商城，同时支持微信小程序、H5、安卓APP、苹果APP。
* [Tigshop](https://www.tigshop.com/)：Tigshop是江西佰商科技旗下的开源电商软件产品。
* [ViewData](https://gitee.com/smartshop-mall/viewdata)：开源电商商城项目。
* [MallPlus](https://gitee.com/catshen/mallplus)：基于Spring Boot、MyBatis Plus的电商系统，包括前台商城系统及后台管理系统。
* [Smart Kettle](https://gitee.com/yaukie/smartkettle)：Java商城，支持小程序商城、 供应链商城，更适合二开。
* [ShopSuite](https://docs.shopsuite.cn/)：ShopSuite是基于Java/PHP/Golang、Uniapp、Vue3、ElementUI框架开发的商城系统。
* [Flash Waimai](https://gitee.com/microapp/flash-waimai)：Flash Waimai是一个仿照饿了么的外卖平台，包括手机端、后台管理、API服务。
* [BizSpring](https://github.com/BizSpringSource/bizspring-vue3-opensource)：BizSpring商城、跨境电商，专注精品独立站。
* [YouLai Mall](https://gitee.com/youlaitech/youlai-mall)：YouLai Mall是基于Spring Boot 3 、Spring Cloud & Alibaba 2022、Vue 3、Element Plus、UniApp等全栈主流技术栈构建的开源商城项目。
* [YShop](https://github.com/guchengwuyue/yshopmall)：YShop是基于当前流行技术组合的前后端分离商城系统，由郑州意象网络科技公司开发。
* [GuliMall](https://gitee.com/agoni_no/gulimall)：GuliMall项目致力于打造一个完整的电商系统，采用现阶段流行技术实现。
* [WaynBoot](https://github.com/wayn111/waynboot-mall)：WaynBoot Mall是一套全部开源的H5商城项目，包含运营后台、H5商城前台和后端接口三个项目。
* [Xiaoxiang](https://gitee.com/xiaoxiangopen/mall)：小象智慧农庄是采用Java开发的B2C商城系统。
* [TMall](https://gitee.com/project_team/Tmall_demo)：一个基于Spring Boot的综合性B2C电商平台，需求设计主要参考天猫商城的购物流程。
* [Morning](https://gitee.com/morning-pro/Morning)：猫宁Morning公益商城是中国公益性在线电子商城。
* [XMall](https://github.com/Exrick/xmall)：基于SOA架构的分布式电商购物商城。
* [Newbee Mall](https://github.com/newbee-ltd/newbee-mall)：Newbee Mall是一套电商系统，包括基础版本、前后端分离版本。
* [Paas Cloud](https://github.com/paascloud/paascloud-master)：Spring Cloud、Vue、OAuth2.0全家桶实战，前后端分离模拟商城，完整的购物流程、后端运营平台，可以实现快速搭建企业级微服务项目。
* [Weiit SaaS](https://gitee.com/wei-it/weiit-saas)：Weiit SaaS是完全开源电商SaaS系统。
* [Open Mall](https://gitee.com/brother-ting/om)：Open Mall项目致力于打造分布式开源电商平台(社区团购、跨境电商、垂直电商、商城小程序、H5电商平台)。
* [SHOPTNT](https://gitee.com/bbc-se/api)：SHOPTNT商城是使用Java语言开发，基于Spring Boot架构体系构建的一套B2B2C商城。
* [Mall Swarm](https://github.com/macrozheng/mall-swarm)：Mall Swarm是一套微服务商城系统，采用了Spring Cloud 2023、Spring Boot 3.2、Sa-Token、MyBatis、Elasticsearch、Docker、Kubernetes等核心技术。
* [Mall](https://gitee.com/zscat/mall)：Mall项目是一套电商系统，包括前台商城系统及后台管理系统、小程序、H5，基于Spring Boot + MyBatis实现。
* [ShopJsp](http://www.shopjsp.com/)：B2B2C多用户商城系统。
* [三勾商城](https://www.jjjshop.net/single_java)：三勾Java商城基于Spring Boot、Element Plus、Uniapp打造的面向开发的小程序商城，方便二次开发或直接使用。
* [九米农庄](https://gitee.com/xiaoxiangopen/mall)：九米农庄项目是一款围绕以农产品销售为主的电商小程序项目产品。
* [创创猫](https://gitee.com/luochangqing/ccm-b2b2c-uniapp)：创创猫是一款完善且经过线上验证的Java电商系统。
* [Payshop](https://gitee.com/JiaGou-XiaoGe/payshop)：基于Spring Boot、Spring Security、JWT、Vue、Element的前后端分离多商户商城管理系统。
* [TMall](https://gitee.com/HaiTao87/TmallDemo)：迷你天猫商城是一个基于SSM框架的综合性B2C电商平台。
* [Weshop](https://gitee.com/cjbi/weshop)：Weshop是基于Spring Cloud开发的小程序商城系统。
* [清大商城](https://gitee.com/zhejiang-qingda-university/mallplus-b2b2c)：清大Java商城基于Spring Boot。
* [B2B2B](https://www.shushangyun.com/p-b2b2b/)：数商云B2B2B电商平台交易系统是一款专注于B2B2B电商交易的综合解决方案，旨在帮助企业构建和管理B2B2B电商平台，实现供应链整合和交易便捷化。
* [SHOP++](https://www.shopxx.net/)：SHOP++是基于Java EE技术的企业级电子商务平台系统。
* [Javashop](https://www.enation.cn/)：Javashop支持全业务模式电商系统。
* [LegendShop](https://legendshop.cn/)：基于Spring Boot 3.0、Spring Cloud、Vue/Uniapp的多模式商城系统。
* [LEKSHOP](https://www.lekshop.cn/)：LEKSHOP商城系统支持商家入驻，后端基于Spring Boot研发，前端使用Vue、Uniapp开发。
* [QiHang ERP](https://gitee.com/qiliping/qihangerp-cloud)：启航电商ERP是一个完整开箱即用的开源电商ERP系统。
* [EDEN](https://gitee.com/codingdb/distribution_management)：微服务下的分销管理利器，更加灵活的管理佣金，涵盖并且总结了目前流行的分销模式。
* [LinjiaShop](https://github.com/microapp-store/linjiashop)：LinjiaShop是一个基于Spring Boot和Vue.js的Web商城系统。
* [MyShop](https://gitee.com/tiankong0310/my-shop)：MyShop是基于Spring MVC、Vue、Swagger 2开发的小程序商城。
* [环兴商城](https://gitee.com/lijiaxing_boy/huanxing-mall)：环兴商城是一套基于Java 17、Spring Boot 3、Spring Cloud Alibaba、Sa-Token、Dubbo的微服务电商系统。
* [ModulithShop](https://gitee.com/suisung/modulithshop)：ModulithShop是基于UniApp、Spring Boot、Vue、Element UI框架的Java商城系统，由随商信息技术公司开源。
* [NbSaaS Mall2](https://gitee.com/quhaodian/nbsaas-mall2)：去好店基于中台理念，一个平台，多个应用，根据不通的应用场景使用不同的应用。
* [Xiaomi](https://github.com/ZeroWdd/Xiaomi)：基于Vue、Spring Boot实现的前后端分离的仿小米商城项目，包含秒杀模块。
* [UZY SSM Mall](https://github.com/ghostxbh/uzy-ssm-mall)：基于Spring Boot框架搭建的电子商务平台手脚架。
* [LDBZ Shop](https://github.com/laodaobazi/ldbz-shop)：Java分布式商城项目。
* [TacoMall](https://github.com/realjerrytang/tacomall)：塔可商城是一个基于Spring Boot 3、Uniapp、Vue3 技术栈开发的开源跨平台小程序、管理后台，后端服务的项目。
* [Siam](https://github.com/siam1026/siam-server)：暹罗点餐是一款Java餐饮点餐系统，适用于多门店的连锁品牌。
* [Shopzz](https://github.com/whoiszxl/shopzz)：一个使用Spring Cloud Alibaba开发的微服务C2B2C的社区、交易平台。

#### 秒杀系统

* [Miaosha](https://github.com/qiurunze123/miaosha)：秒杀系统设计与实现。
* [Spring Boot Seckill](https://github.com/zaiyunduan123/springboot-seckill)：基于Spring Boot、MySQL、Redis、RabbitMQ、Guava开发的高并发商品限时秒杀系统。
* [Seckill](https://github.com/codingXiaxw/seckill)：Java高并发秒杀系统API。
* [Goodskill](https://github.com/techa03/goodsKill)：基于Spring Cloud 2023.x、Dubbo 3.x、AI构建的模拟秒杀微服务项目。
* [Seckill](https://github.com/lyrric/seckill)：约苗、九价秒杀脚本。
* [Seckill](https://github.com/hfbin/Seckill)：基于Spring Boot、Mybatis、Redis、RabbitMQ秒杀系统。
* [JSeckill](https://github.com/bootsrc/jseckill)：Java实现的秒杀网站，基于Spring Boot 2.X。
* [Miaosha](https://gitee.com/1028125449/miaosha)：秒杀、抢购解决方案。

#### 医疗系统

* [HAPI FHIR](https://github.com/hapifhir/hapi-fhir)：HAPI FHIR是HL7 FHIR标准的完整实现，用于Java中的医疗保健互操作性。
* [Mirth Connect](https://github.com/nextgenhealthcare/connect)：Mirth Connect是一个基于开源标准的医疗保健集成引擎，它通过接受传入的信息包并根据你提供的规则处理它们来实现两个系统之间的互操作性。
* [HIS](https://github.com/ZainZhao/HIS)：HIS主要功能按照数据流量、流向及处理过程分为临床诊疗、药品管理、财务管理、患者管理。
* [EHRServer](https://github.com/ppazos/cabolabs-ehrserver)：EHRServer是一个开源临床数据管理和共享平台，符合OpenEHR标准。
* [Open Hospital](https://github.com/informatici/openhospital)：Open Hospital是一款免费的开源健康信息管理系统(HIMS)软件应用程序。
* [Clinical Quality Language](https://github.com/cqframework/clinical_quality_language)：CQL是用于表达临床知识的HL7标准，可在广泛的临床领域中使用，包括临床决策支持(CDS)和临床质量测量(CQM)。
* [HMIS](https://github.com/hmislk/hmis)：HMIS是一个医院信息管理系统，自2004年推出以来一直积极为40多家医疗机构提供服务。
* [HAPI FHIR Core](https://github.com/hapifhir/org.hl7.fhir.core)：适用于FHIR规范的Java核心对象处理代码，带有实用程序(包括验证器)。
* [PhenoTips](https://github.com/phenotips/phenotips)：PhenoTips是一款基于浏览器的工具，用于记录遗传疾病患者的临床表型、遗传信息、疾病和家族史等相关数据。
* [OpenMRS](https://github.com/openmrs/openmrs-core)：OpenMRS是一个基于患者的医疗记录系统，专注于为提供商提供免费的可定制电子医疗记录系统(EMR)。
* [EHRbase](https://github.com/ehrbase/ehrbase)：EHRbase是一个OpenEHR临床数据存储库，为可互操作的临床应用程序提供基于标准的后端，由德国布伦瑞克工业大学及汉诺威医学院联合开发。
* [DCM4che](https://github.com/dcm4che/dcm4che)：Java中的DICOM实现。
* [Synthea](https://github.com/synthetichealth/synthea)：Synthea是一款合成患者群体模拟器，目标是以各种格式输出合成的、真实的(但不是真实的)患者数据和相关的健康记录。
* [Weasis](https://github.com/nroduit/Weasis)：Weasis是一款独立的基于Web的软件，用于可视化从医疗成像设备获得的图像。
* [OpenICE](https://github.com/mdpnp/mdpnp)：OpenICE是一项旨在创建集成临床环境的社区实施的倡议，该计划不仅包括软件实现，还包括更广泛的临床生态系统的架构，以实现临床研究的新途径。
* [Dicoogle](https://github.com/bioinformatics-ua/dicoogle)：Dicoogle是一款可扩展、独立于平台的开源PACS归档软件，它以更敏捷的索引和检索机制取代了传统的集中式数据库，由阿威罗大学开源。
* [Phoenix CTMS](https://github.com/phoenixctms/ctsms)：Phoenix CTMS是一款大型Web应用程序，将临床研究中使用的数据库软件的功能结合在一个模块化系统中。
* [SIMRS Khanza](https://github.com/mas-elkhanza/SIMRS-Khanza)：适用于医院、诊所、保健中心、私人医生的软件，已在印度尼西亚1000多家医院使用。
* [OpenELIS Global 2](https://github.com/I-TECH-UW/OpenELIS-Global-2)：OpenELIS Global是专为公共卫生实验室量身定制的开放式企业级实验室信息系统软件，由华盛顿大学开源。
* [LinuxForHealth FHIR](https://github.com/LinuxForHealth/FHIR)：LinuxForHealth FHIR服务器是HL7 FHIR规范的模块化Java实现，支持版本R4和R4B，重点关注性能和可配置性。
* [Pathling](https://github.com/aehrc/pathling)：Pathling是一组工具，可让你在健康数据分析中更轻松地使用FHIR和临床术语，由澳大利亚电子健康研究中心开源。
* [E-Medical System](https://github.com/soumyadip007/E-Medical-System-Web-Project-Using-Spring-Boot-Security-JPA-Rest-Thymeleaf-HQL)：使用Spring Boot开发的电子医疗系统Web项目。
* [Open Healthcare Codegen Tool Framework](https://github.com/wso2/open-healthcare-codegen-tool-framework)：Open Healthcare Codegen Tool Framework包含一些常用实用程序和接口，用于实现针对常见医疗协议(FHIR、HL7v2)的工具，由WSO2开源。
* [OpenClinica](https://github.com/OpenClinica/OpenClinica)：OpenClinica是一款开源的电子数据采集(EDC)和临床数据管理(CDM)软件，用于智能且安全地优化临床试验工作流程。

#### 项目管理

* [Teambition](https://www.teambition.com/)：阿里旗下数字化协作平台，提供项目管理、任务协同等解决方案。
* [MyCollab](https://github.com/MyCollab/mycollab)：MyCollab是免费的开源项目管理软件。
* [GanttProject](https://github.com/bardsoftware/ganttproject)：GanttProject是一款免费的桌面项目管理应用程序，由BarD软件公司开源。
* [Twproject](https://twproject.com/)：Twproject是一个灵活的基于Web的工作和项目管理平台，专为小型和大型团队打造。
* [Wukong PM](https://github.com/WuKongOpenSource/Wukong_ProjectManagement)：基于Spring Cloud Alibaba微服务架构、Vue、ElementUI的前后端分离项目管理系统。
* [Mone](https://github.com/XiaoMi/mone)：Mone是一个以微服务为核心的一站式企业协同研发平台，支持公有云、私有云、混合云等多种部署形态，由小米开源。
* [Codes](https://gitee.com/xiaoming1q/icodes)：Codes是一个高效、简洁、轻量的一站式研发项目管理平台，由四川无限智达公司开源。
* [IceScrum](https://github.com/icescrum/iceScrum)：IceScrum是一款Web应用，它使用Scrum的同时，也保留了协作工作空间的精髓。
* [Atlas CMMS](https://github.com/Grashjs/cmms)：Atlas CMMS是一款功能强大的自托管维护管理系统，基于Docker架构，适用于Web和移动平台。
* [Gerrit](https://github.com/GerritCodeReview/gerrit)：Gerrit是基于Git的项目的代码审查和项目管理工具，由Google开源。
* [Kooteam](https://gitee.com/sinbo/kooteam)：Kooteam是一款轻量级的在线团队协作工具，提供各类文档工具、在线思维导图、在线流程图、项目管理、任务分发，知识库管理等工具。
* [LibrePlan](https://github.com/LibrePlan/libreplan)：LibrePlan是一款用于项目管理、监控和控制的免费软件Web应用程序。
* [Naikan](https://github.com/enofex/naikan)：Naikan是一款开源软件库存管理工具，适用于由CI/CD管道驱动的开发团队。
* [TMS](https://gitee.com/xiweicheng/tms)：TMS是基于频道模式的团队沟通协作+轻量级任务看板，支持Markdown、富文本、在线表格和思维导图的团队博文wiki，i18n国际化翻译管理的响应式Web开源团队协作系统。
* [Rapla](https://github.com/rapla/rapla)：Rapla是一个灵活的多用户资源和活动规划系统，它具有多个日历视图、冲突管理、完全可配置的资源和事件类型以及许多导入/导出功能。
* [Kanass](https://github.com/tiklab-project/tiklab-kanass)：Kanass是专为项目管理而设计的应用软件，帮助项目管理者在有限的资源约束下，运用系统项目涉及的全部工作进行有效管理。
* [OpenFastTrace](https://github.com/itsallcode/openfasttrace)：OpenFastTrace是一个需求跟踪套件，可以帮助你跟踪是否真正实现了规范中计划的所有内容。
* [ProjectLibre](https://www.projectlibre.com/)：ProjectLibre是Microsoft Project的第一大替代品，ProjectLibre提供免费桌面和订阅云解决方案。
* [Plan](https://calligra.org/plan/)：Plan是一个项目管理应用程序，旨在管理具有多种资源的中等大型项目。
* [HeartBeat](https://github.com/thoughtworks/HeartBeat)：HeartBeat是一个用于跟踪项目交付指标的工具，可以帮助你更好地了解交付绩效，由ThoughtWorks开发。
* [BulletJournal](https://github.com/singerdmx/BulletJournal)：BulletJournal是一个开源平台，用于笔记本保存、账本管理、任务/项目管理和协调，擅长个人组织、日程安排、提醒、待办事项列表、笔记共享、多人账本和团队项目协作。
* [GoGoScrum](https://github.com/gogoscrum/gogoscrum-rest-service)：GoGoScrum是一款轻量级的敏捷项目管理工具，专为高效的团队协作而设计。

#### 即时通讯

* [Jitsi](https://github.com/jitsi/jitsi)：Jitsi Desktop是一款免费的开源音频/视频和聊天通信器，支持SIP、XMPP/Jabber、IRC等协议和许多其他有用的功能。
* [Signal Server](https://github.com/signalapp/Signal-Server)：Signal是一款开源、端到端加密的通讯应用程序，可用于发送文本、语音、图片和视频等多种形式的消息，由Open Whisper Systems开发。
* [TIMSDK](https://github.com/TencentCloud/TIMSDK)：腾讯云聊天拥有全球接入、一对一聊天、群聊、消息推送、档案和关系链托管、账户认证等一整套解决方案。
* [CIM](https://github.com/crossoverJie/cim)：CIM是一款面向开发者的IM系统，同时提供了一些组件帮助开发者构建一款属于自己可水平扩展的IM。
* [Google Cloud Messaging](https://github.com/google/gcm)：Google Cloud Messaging是一种服务，允许开发人员将数据从服务器发送到用户的设备，并从同一连接上的设备接收消息。
* [野火IM](https://github.com/wildfirechat/im-server)：野火IM是专业级的即时通讯和实时音视频整体解决方案，由北京野火无限网络科技有限公司维护和支持。
* [V-IM](https://gitee.com/alyouge/V-IM)：V-IM是基于JS的超轻量级聊天软件，服务端使用Spring Boot。
* [FshareIM](https://github.com/fsharechat)：FshareIM是一个技术自主可控即时IM通讯系统，适于私有化部署。
* [Face2Face](https://github.com/a2888409/face2face)：基于Netty的异步非阻塞实时聊天(IM)服务器。
* [Tigase Server](https://github.com/tigase/tigase-server)：Tigase XMPP Server是用Java编写的高度优化、高度模块化且非常灵活的XMPP/Jabber服务器。
* [MallChat](https://github.com/zongzibinbin/MallChat)：抹茶聊天是一个IM项目，通过Netty实现和前端的WebSocket连接。
* [Actor Platform](https://github.com/actorapp/actor-platform)：Actor是一个即时通讯平台。
* [NettyChat](https://github.com/FreddyChen/NettyChat)：基于Netty、TCP、Protobuf实现的Android IM库。
* [Turms](https://github.com/turms-im/turms)：Turms是全球最先进的开源即时通讯引擎，支持100K~10M并发用户。
* [InChat](https://github.com/AwakenCN/InChat)：InChat是一个轻量级、高效、分布式的异步通信框架，支持聊天和物联网。
* [Smack](https://github.com/igniterealtime/Smack)：Smack是一个开源、高度模块化、易于使用的XMPP客户端库，用Java编写，适用于兼容Java SE的JVM和Android。
* [J-IM](https://gitee.com/xchao/j-im)：J-IM是用Java语言开发的轻量、高性能、单机支持几十万至百万在线用户IM。
* [Bytedesk](https://github.com/Bytedesk/bytedesk)：企业即时通讯解决方案，具有人工智能实时聊天、电子邮件支持、全渠道客户服务和团队即时通讯功能。
* [Openfire](https://github.com/igniterealtime/Openfire)：Openfire是一个即时通信和群聊服务器，它是使用Java编写的XMPP服务器。
* [CIM](https://gitee.com/farsunset/cim)：CIM是一套完善的消息推送框架，可应用于信令推送，即时聊天，移动设备指令推送等领域。
* [IM](https://github.com/yuanrw/IM)：IM是一个轻量级的即时通讯服务器。
* [MobileIMSDK](https://github.com/JackJiang2011/MobileIMSDK)：MobileIMSDK是一个原创多端IM通信层框架，轻量级、高度提炼，支持UDP、TCP、WebSocket三种协议。
* [OIM](https://gitee.com/oimchat/oim-fx)：OIM是一套即时通讯的聊天系统，可以用于公司内网、外网通讯、客服系统等。
* [CometD](https://github.com/cometd/cometd)：CometD是用于网络消息传递的可扩展Comet(服务器推送)实现。
* [iCometClient4j](https://github.com/kyleduo/iCometClient4j)：iComet服务器的客户端，适用于Java/Android平台。
* [QIQIIM](https://gitee.com/qiqiim/qiqiim-server)：QIQIIM提供简单快捷的IM方案，可用于公司内网、外网通讯，客服系统等。
* [Spark](https://github.com/igniterealtime/Spark)：Spark是一款针对企业和组织进行优化的开源跨平台IM客户端。
* [Gifsockets](https://github.com/videlalvaro/gifsockets)：使用Gif动画作为传输的实时通信库。
* [RongCloud Server SDK](https://github.com/rongcloud/server-sdk-java)：Java版融云即时通讯服务器SDK。
* [SONA](https://github.com/BixinTech/sona)：SONA是一个由比心语音技术团队开发，用于快速搭建语音房产品的全端解决方案，支撑了比心聊天室、直播、游戏房等业务。
* [Tencent Cloud IM Server SDK](https://github.com/doocs/qcloud-im-server-sdk-java)：腾讯云IM服务端SDK Java版。
* [Xiaper](https://github.com/xiaper/xiaper)：Xiaper是一款开源企业IM解决方案。
* [盒子IM](https://gitee.com/bluexsx/box-im)：盒子IM是一个仿微信实现的网页版聊天软件，不依赖任何第三方收费组件。
* [HuLa Server](https://github.com/HuLaSpark/HuLa-Server)：HuLa Server是一款基于Spring Boot 3、Netty、MyBatis Plus和RocketMQ构建的即时通讯系统服务端。
* [Linyu](https://github.com/DWHengr/linyu-server)：林语是基于Tauri开发的桌面聊天软件，前端框架使用React，后端框架使用Spring Boot进行开发。
* [IM WhaleShark](https://github.com/BanTanger/im-whale-shark)：IM WhaleShark是基于Netty实现的高性能分布式IM即时通讯系统。
* [微聊](https://gitee.com/lakaola/im-platform)：聊天IM、实时音视频通话等功能。
* [AQChat](https://gitee.com/howcode/aq-chat-server)：AQChat是一个已接入AI的极速、便捷的匿名在线即时AI聊天室。
* [OUYUNC IM](https://gitee.com/etxync/ouyunc-im)：偶云客IM是一款开源免费基于Netty的即时通讯框架。
* [SubtleChat](https://github.com/JustCoding-Hai/subtlechat)：微言是基于前后端分离，采用Spring Boot、Vue框架开发的网页版聊天室。
* [AnyChat](https://github.com/dianbaer/anychat)：AnyChat是一个极简纯净的WebSocket聊天插件，支持对接任何身份系统，嵌入方只需提供三个API即可进行实时通讯。
* [MuChat](https://gitee.com/pisces-hub/muchat)：MuChat是用Java语言开发的轻量、高性能、单机支持几十万至百万在线用户IM。
* [Chat UniApp](https://gitee.com/lakaola/chat-api)：聊天IM，精仿微信，支持单聊、群聊、朋友圈、摇一摇、附近的人、收藏、扫码、机器人、文字、图片、名片、实时音视频通话等功能。
* [Lucky](https://github.com/Luckly-XYZ/Lucky-cloud)：Lucky是一个基于Spring Boot 3、Spring Cloud Alibaba构建的高性能、高可用的即时通讯服务端系统。
* [OrdinaryRoad Live Chat Client](https://github.com/OrdinaryRoad-Project/ordinaryroad-live-chat-client)：一个基于Netty的通用直播间弹幕客户端。
* [灯塔APS](https://gitee.com/lighthouse-aps/im)：灯塔APS高级生产计划排程是一款基于有限资源进行合理排产实现精准计划的排产类工业软件。
* [FastIM](https://github.com/zhangyaoo/fastim)：基于Netty高可用分布式即时通讯系统。
* [Live Chat Engine](https://github.com/edolganov/live-chat-engine)：开源系统，用于在任何网站上与访客进行实时聊天。
* [WebQQ](https://github.com/iqq-team/webqq-core)：一个基于WebQQ协议开发的库，你可以基于这个库让你的程序集成QQ相关的功能。

#### 问题跟踪系统

* [JIRA](https://www.atlassian.com/software/jira)：JIRA是一个Bug跟踪管理系统，为针对Bug管理、任务追踪和项目管理的商业性应用软件，由Atlassian开发。
* [YouTrack](https://www.jetbrains.com/youtrack/)：YouTrack是JetBrains开发的专有、基于商业浏览器的错误跟踪器、问题跟踪系统和项目管理软件。
* [Lavagna](https://github.com/digitalfondue/lavagna)：Lavagna是一款小型且易于使用的问题/项目跟踪软件。
* [Yobi](https://github.com/yona-projects/yona)：Yobi是一个基于Web的项目托管软件，由Naver开源。
* [唛盟XM](https://gitee.com/maimengcloud/xm-backend)：唛盟以研发管理为核心，涵盖项目规划、需求管理、开发迭代、版本控制、缺陷跟踪、测试管理、工时管理、效能分析等环节，实现全过程、全方位的研发管理。
* [Cat2Bug Platform](https://gitee.com/cat2bug/cat2bug-platform)：Cat2Bug Platform是一套永久免费开源的Bug管理平台，可以完全私有化部署。
* [ProjectForge](https://github.com/micromata/projectforge)：ProjectForge是一个基于Web的项目管理解决方案，包括时间跟踪、团队日历、甘特图、财务管理、问题管理、控制和管理工作分解结构(例如与JIRA一起作为问题管理系统)。
* [BugCatcher](https://github.com/youzan/bugCatcher)：BugCatcher是有赞开发的项目管理、测试用例管理、项目进度和质量监控工具。

#### QA系统

* [TDuck](https://gitee.com/TDuckApp/tduck-platform)：TDuck是国内首批基于Vue开源的问卷/表单收集工具。
* [DWSurvey](https://gitee.com/wkeyuan/DWSurvey)：DWSurvey是一款免费、高效、稳定的开源问卷表单系统，由北京极推科技公司开发。
* [SurveyKing](https://gitee.com/surveyking/surveyking)：SurveyKing是功能强大、搭建简单、界面更美观的在线考试/调查问卷/公开查询/题库刷题/360度评估/投票系统，由北京橙宇言信科技公司开源。
* [EUSurvey](https://github.com/EUSurvey/EUSURVEY)：EUSurvey是欧盟委员会官方的在线调查管理工具。
* [JDeSurvey](https://github.com/JD-Software/JDeSurvey)：JDeSurvey是一款由JD Software开发的开源Web应用程序，用于创建、收集和分析问卷调查。
* [XIAOJUSURVEY](https://github.com/didi/xiaoju-survey)：XIAOJUSURVEY是一套轻量、安全的问卷系统，滴滴开源。
* [QuestionAnsweringSystem](https://github.com/ysc/QuestionAnsweringSystem)：QuestionAnsweringSystem是一个Java实现的人机问答系统，能够自动分析问题并给出候选答案，这是IBM Watson的Java开源实现。
* [Qanary](https://github.com/WDAqua/Qanary)：Qanary是一种创建问答系统的方法。
* [Scoold](https://github.com/Erudika/scoold)：Scoold是一个面向团队的问答和知识共享平台。
* [YodaQA](https://github.com/brmson/yodaqa)：YodaQA是一个开源Factoid问答系统，可以使用即时信息提取从数据库和文本语料库中生成答案。
* [OpenQA](https://bitbucket.org/emarx/openqa/src/master/)：OpenQA是一个用于问答开发和发布的框架和平台。
* [Mamute](https://github.com/caelum/mamute)：Mamute是一个基于CDI和VRaptor 4使用Java开发的问答引擎，由Caelum开源。
* [Openauth](https://gitee.com/yubaolee/openauth.qa)：Openauth是一个简洁实用的问答网站。
* [OpenEphyra](https://github.com/TScottJ/OpenEphyra)：OpenEphyra是一个开源的QA框架，由CMU开源。

#### CMS系统

* [Halo](https://github.com/halo-dev/halo)：Halo是一个强大易用的开源建站工具，由飞致云开源。
* [Novel](https://github.com/201206030/novel)：Novel是一套基于Java技术栈Spring Boot 3、Vue 3开发的前后端分离学习型小说项目。
* [AEM](https://business.adobe.com/products/experience-manager/adobe-experience-manager.html)：AEM是一个以Java为核心开发的企业级内容管理系统，这是Adobe的商业产品。
* [MCMS](https://gitee.com/mingSoft/MCMS)：MCMS是免费可商用的开源Java CMS内容管理系统，由铭软科技公司开源。
* [JPress](https://gitee.com/JPressProjects/jpress)：JPress是一个使用Java开发、类似WordPress的产品，支持多站点、多语种自动切换等，由小码科技开源。
* [师说CMS](https://gitee.com/shishuo/CMS_old)：师说CMS是一款使用Java语言开发的CMS，使用了Spring MVC、Spring、MyBatis等流行框架，提供首页大图管理、目录管理、文章管理和管理员管理等功能。
* [NiceFish](https://gitee.com/mumu-osc/NiceFish)：NiceFish是一个系列项目，目标是示范前后端分离的开发模式。
* [BookLore](https://github.com/booklore-app/booklore)：BookLore是一款自托管的Web应用，用于整理和管理你的个人藏书。
* [JFinal CMS](https://gitee.com/jflyfox/jfinal_cms)：JFinal CMS是一个Java开发的功能强大的信息咨询网站，采用JFinal作为Web框架。
* [XWiki Platform](https://github.com/xwiki/xwiki-platform)：XWiki Platform是一个通用的Wiki平台，为构建在其之上的应用程序提供运行时服务。
* [StubbornJava](https://github.com/StubbornJava/StubbornJava)：用于构建无需框架的Web服务器/服务的非常规Java代码。
* [FastCMS](https://gitee.com/dianbuapp_admin/fastcms)：FastCMS是基于Spring Boot前后端分离技术，且具有插件化架构的CMS系统。
* [DotCMS](https://github.com/dotCMS/core)：DotCMS是一种开源无头/混合内容管理系统，旨在跨多个渠道管理和提供基于权限的个性化内容体验。
* [Novel Plus](https://github.com/201206030/novel-plus)：Novel Plus是一个多端(PC、WAP)阅读，功能完善的原创文学CMS系统。
* [White Jotter](https://github.com/Antabot/White-Jotter)：White Jotter是一个Spring Boot和Vue.js开发的简单CMS。
* [PublicCMS](https://github.com/sanluan/PublicCMS)：PublicCMS是2024年采用主流技术开发的开源Java CMS系统。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、Wiki、讨论等，由Spring Boot提供支持的云原生应用程序。
* [Tianti](https://github.com/xujeff/tianti)：天梯是一款使用Java编写的免费的轻量级CMS系统，目前提供了从后台管理到前端展现的整体解决方案。
* [LinCMS](https://github.com/TaleLin/lin-cms-spring-boot)：LinCMS是林间有风团队经过大量项目实践所提炼出的一套内容管理系统框架。
* [Ametys](https://www.ametys.org/community/en/index.html)：Ametys是一个用Java编写的免费开源内容管理系统。
* [网市场CMS](https://gitee.com/mail_osc/wangmarket)：私有化部署自己的SAAS云建站系统，跟可通过后台任意开通多个网站，每个网站使用自己的账号进行独立管理。
* [JFinalCMS](https://gitee.com/heyewei/JFinalcms)：JFinalCMS允许你快速搭建个性化独立网站。
* [Gentics Mesh](https://github.com/gentics/mesh)：Gentics Mesh是为开发人员提供的开源无头CMS。
* [ThinkItCMS](https://gitee.com/slfj/ThinkItCMS)：ThinkItCMS是一款面向模板开发，支持静态生成的CMS系统。
* [Nuxeo Platform](https://github.com/nuxeo/nuxeo)：Nuxeo是一个开源的可定制和可扩展的内容管理平台，用于构建业务应用程序。
* [RuoYi Plus](https://gitee.com/markbro/ruoyi-plus)：基于RuoYi 4.1.0开发，新增内容管理模块CMS、缓存模块、博客模块以及爬虫模块等等。
* [IceCMS](https://github.com/Thecosy/IceCMS)：IceCMS是基于Spring Boot、Vue前后端分离的内容管理系统。
* [Brix](https://github.com/brix-cms/brix-cms)：Brix基于Wicket和JCR，是当今最好的基于Wicket的CMS框架。
* [OFCMS](https://gitee.com/oufu/ofcms)：Java版CMS、基于Java研发的内容管理系统。
* [RuoYi Vue Blog](https://gitee.com/Ning310975876/ruo-yi-vue-blog)：基于RuoYi Vue前后端分离基础平台开发的博客网站。
* [ZrLog](https://gitee.com/94fzb/zrlog)：ZrLog是使用Java开发的博客/CMS程序，具有简约，易用，组件化，内存占用低等特点。
* [Apache Stanbol](https://stanbol.apache.org/)：Stanbol提供了一组用于语义内容管理的可重用组件。
* [Jease](https://jease.org/)：Jease是一个由Java驱动的开源CMS。
* [Quanta](https://github.com/Clay-Ferguson/quantizr)：Quanta是一种新型内容管理平台，具有强大的功能。
* [Alfresco](https://github.com/Alfresco/alfresco-community-repo)：Alfresco平台提供全面的云原生内容服务。
* [ContentGrid](https://contentgrid.com/)：ContentGrid是一个开源的内容应用程序平台。
* [WallRide](https://github.com/tagbangers/wallride)：WallRide是一个多语言、易于定制的开源CMS。
* [Magnolia CMS](https://www.magnolia-cms.com/)：Magnolia是一个开源CMS，由总部位于瑞士巴塞尔的Magnolia开发。
* [瀑布CMS](https://gitee.com/LinZhaoguan/pb-cms)：瀑布CMS采用Spring Boot、Shiro、MybatisPlus、Thymeleaf实现。
* [UJCMS](https://gitee.com/ujcms/ujcms)：Java开源内容管理系统，使用Spring Boot、MyBatis、Spring Security、Lucene、FreeMarker、TypeScript、Vue3、ElementPlus等技术开发。
* [OpenCMS](https://github.com/alkacon/opencms-core)：OpenCMS是Alkacon公司开发的Java内容管理系统。
* [SitesCMS](https://gitee.com/xhhxb/sitesCMS)：SitesCMS是基于JFinal的多站点CMS内容管理系统。
* [DreamerCMS](https://gitee.com/iteachyou/dreamer_cms)：DreamerCMS采用流行的Spring Boot搭建，支持静态化、标签化建站。
* [Enonic XP](https://github.com/enonic/xp)：Enonic XP是一个基于Java和Elasticsearch的免费开源Web应用程序平台和内容管理系统。
* [Elepy](https://github.com/RyanSusana/elepy)：Elepy是适用于Java和Kotlin的无头内容管理框架。
* [Blossom](https://github.com/blossom-editor/blossom)：Blossom是一个支持私有部署的云端双链笔记软件，你可以将你的笔记，图片，个人计划安排保存在自己的服务器中，并在任意设备之间实时同步。
* [NemakiWare](https://github.com/aegif/NemakiWare)：NemakiWare是一个开源企业内容管理系统。
* [WebSight](https://www.websight.io/)：WebSight是一个容器化内容管理系统，与StreamX数字体验服务网格进行原生集成。
* [Lutece](https://github.com/lutece-platform/lutece-core)：Lutece是一个开放平台，使城市政府能够共享、重复使用和改编其他城市创建的数字服务。
* [JTopCMS](https://gitee.com/mjtop/JTopCMSV3)：JTopCMS基于Java EE标准研发，用于管理站群内容的内容管理软件，由合肥明靖信息科技公司开源。
* [PerfreeBlog](https://gitee.com/PerfreeBlog/PerfreeBlog)：PerfreeBlog是一款基于Java开发的博客/CMS建站平台。
* [Shio CMS](https://github.com/openviglet/shio)：模型内容、使用GraphQL并使用带有本机缓存和搜索的Javascript创建站点。
* [CrafterCMS](https://github.com/craftercms/craftercms)：CrafterCMS是一个现代内容管理平台，用于构建数字体验应用程序。
* [ηCMS](https://ncms.softmotions.com/)：开发人员可以基于ηCMS核心框架创建自己的Java项目，由Softmotions开发。
* [MRCMS](https://github.com/wuweiit/mushroom)：MRCMS是一款Java开发的内容管理系统，采用数据模型、模板、插件实现，内置提供了文章模型发布功能。
* [NoraCMS](http://inbox-online.com/noracms/)：NoraCMS是一个企业CMS，它为你提供创建引人入胜的Web体验和通过所有渠道接触客户所需的自由和灵活性。
* [CONTENTBOX](https://www.contentboxcms.org/)：CONTENTBOX是一款功能强大的开源无头CMS，100%完全可定制。
* [CicadasCMS](https://gitee.com/westboy/CicadasCMS)：CicadasCMS是使用Spring Boot、Mybatis、Beetl开发的一款CMS，支持自定义内容模型、模板标签、全站静态化等功能。
* [ChestnutCMS](https://gitee.com/liweiyi/ChestnutCMS)：ChestnutCMS是前后端分离的企业级内容管理系统。
* [Spring Content](https://github.com/paulcwarren/spring-content)：适用于Spring的云原生存储和企业内容服务。
* [MDP ARC](https://gitee.com/maimengcloud/mdp-arc-backend)：MDP ARC以内容管理为核心，涵盖文章管理、广告管理、文件管理、图片管理、素材存储的内容管理一站式解决方案。
* [Ikaros](https://github.com/ikaros-dev/ikaros)：专注于ACGMN的内容管理系统。
* [Dice](https://github.com/bihell/Dice)：Dice是一个前后端分离的个人内容管理(CMS)系统。
* [CMS Boot](https://github.com/buttasam/cms-boot)：一个基于Spring Boot和SQL数据库构建的轻量级、灵活且可扩展的内容管理系统。
* [WX Manage](https://github.com/niefy/wx-manage)：WX Manage是一个公众号管理系统，支持多公众号接入。
* [JProcms](https://gitee.com/jprocms/jprocms-cloud)：Java开源内容管理系统、建站系统。
* [YoungCMS](https://gitee.com/fumiao/opencms)：Java编写的CMS系统。
* [Jahia CMS](https://www.jahia.com/product/content-management-system)：Jahia CMS是一个成熟且经过验证的解决方案，可帮助你在全球范围内创建、管理和发布内容。
* [KenSite](https://gitee.com/seeyoui/kensite_cms)：KenSite是基于多个优秀的开源项目，高度整合封装而成的高效、高性能、强安全性的开源Java EE快速开发平台。
* [TeaCMS](https://gitee.com/xiaobingby/TeaCMS)：TeaCMS是由Spring、Spring MVC、MyBatis、MySQL数据库开发的一个博客系统。
* [WxCMS](https://gitee.com/live.cn/wxcms)：微讯是基于JFinal、Shiro、LayUI、Freemarker、UEditor、MySQL等框架和技术结合Maven多模块方式构建开发的一款通用内容发布系统。
* [Zhige](https://gitee.com/Getawy/zhige)：止戈是一款基于Java开发的建站系统，上手简单，支持不同站点的建设。
* [EasyCMS](https://gitee.com/sid_jiang/easycms)：简单的Java CMS系统。
* [Zhi](https://gitee.com/free4inno-team/zhi)：知了是一款面向中小型团队的轻量化知识管理应用，由北京邮电大学开源。
* [JeeCMS](https://www.jeecms.com/)：JeeCMS是基于Java、Vue、Spring Boot等技术研发的开源内容管理系统。
* [Asbru Web](https://wcm.asbrusoft.com/)：Asbru Web内容管理系统包括全方位的先进和强大的功能，以支持业务需求并简化小型和简单网站以及大型复杂网站的开发。

#### 博客系统

* [JBake](https://github.com/jbake-org/jbake)：JBake是一个为开发人员提供的基于Java的开源静态站点/博客生成器。
* [VBlog](https://github.com/lenve/VBlog)：V部落是一个多用户博客管理平台，采用Vue、Spring Boot开发。
* [MoguBlog](https://github.com/moxi624/mogu_blog_v2)：MoguBlog是一个基于微服务架构的前后端分离博客系统。
* [Aurora](https://github.com/linhaojun857/aurora)：基于Spring Boot、Vue开发的个人博客系统。
* [Cryogen](https://github.com/cryogen-project/cryogen)：Cryogen是用Clojure编写的简单静态站点生成器。
* [My Site](https://github.com/WinterChenS/my-site)：My Site是由Docker、Spring Boot 2、Mybatis、Thymeleaf等技术实现的个人网站。
* [OpooPress](https://github.com/opoo/opoopress)：OpooPress框架是一个完全灵活、完全可扩展的基于Java的静态站点生成器。
* [Apache Roller](https://github.com/apache/roller)：Roller是一个基于Java、功能齐全的多用户和群组博客服务器，适用于大大小小的博客网站。
* [ThriveX](https://github.com/LiuYuYang01/ThriveX-Server)：ThriveX是一个高颜值、全开源、永不收费的现代化博客管理系统。
* [Tale Blog](https://github.com/otale/tale)：Tale是使用轻量级的MVC框架Blade进行开发的简洁美观的Java博客系统。
* [Shoka](https://gitee.com/wu_shengdong/blog)：基于Spring Boot、Vue 3开发的前后端分离博客。
* [MyBlog](https://github.com/zhyocean/MyBlog)：使用Spring Boot、MyBatis进行前后端开发的个人博客网站。
* [Memory](https://github.com/LinMoQC/Memory-Blog)：这是一个用React、TypeScript和Spring Boot构建的个人博客平台。
* [SunQBlog](https://github.com/SunQQQ/SunQBlog-ServerSide)：个人博客CodingLife的后端代码，使用Spring Boot、MyBatis、MySQL的技术栈开发。
* [Blog SSM](https://github.com/rawchen/blog-ssm)：Java Web博客项目。
* [Bolo Solo](https://github.com/adlered/bolo-solo)：菠萝博客是专为程序员设计的精致Java博客系统。
* [WeBlog](https://gitee.com/AllenJiang/WeBlog)：一款由Spring Boot、Vue 3.2、Vite 4.3开发的前后端分离博客。
* [POETIZE](https://gitee.com/littledokey/poetize)：个人博客、聊天室IM，使用Spring Boot和Vue的个人网站。
* [答案博客](https://gitee.com/aqian666/blog)：答案博客是基于Vue、Spring Boot搭建的博客，支持Markdown语法，整合了ES，支持搜索高亮、页面简洁、美观。
* [ForestBlog](https://github.com/saysky/ForestBlog)：ForestBlog是一个简单漂亮的SSM博客系统。
* [Solo](https://github.com/88250/solo)：Solo是一款小而美的开源博客系统，专为程序员设计。
* [SpringBlog](https://github.com/Raysmond/SpringBlog)：SpringBlog是一个用Spring Boot实现的非常简单且设计干净的博客系统。
* [MyBlog](https://github.com/shuleisanshi/myblog)：MyBlog是采用SSM架构开发的个人博客。
* [MyBlog](https://github.com/ZHENFENG13/My-Blog)：MyBlog是由Spring Boot、Mybatis、Thymeleaf等技术实现的Java博客系统。
* [Jivejdon](https://github.com/banq/jivejdon)：Jivejdon是一个类似WordPress的博客/论坛和生产就绪应用程序，具有DDD、DomainEvents/Event Soucing/CQRS、清洁架构/六边形架构。
* [OneBlog](https://gitee.com/yadong.zhang/DBlog)：OneBlog是一个简洁美观、功能强大并且自适应的Java博客。
* [MBlog](https://gitee.com/mtons/mblog)：MBlog开源Java博客系统，支持多用户、支持切换主题。
* [Grain](https://github.com/sysgears/grain)：Grain是一个轻量级框架和一个非常强大的静态网站生成器，用Groovy编写，可帮助使网站创建直观且愉快。
* [ForFun](https://github.com/shimh-develop/blog-vue-springboot)：Vue、Spring Boot实现的博客系统。
* [Antville](https://github.com/antville/antville)：Antville是一个开源项目，提供高性能、功能丰富的博客托管软件。
* [Plumemo](https://github.com/open-snail/plumemo)：Plumemo是一个轻量、易用、前后端分离的博客系统。
* [VueBlog](https://github.com/MarkerHub/vueblog)：一个基于Spring Boot、Vue开发的前后端分离博客项目。
* [Blog](https://github.com/zhisheng17/blog)：Spring Boot、Mybatis、Thymeleaf搭建的个人博客。
* [NewBlog](https://github.com/Zephery/newblog)：NewBlog是一个简单的个人博客系统。
* [ScBlogs](https://github.com/stick-i/scblogs)：校园博客，基于微服务架构且前后端分离的博客社区系统。
* [NBlog](https://github.com/Naccl/NBlog)：Spring Boot、Vue前后端分离博客系统。
* [Kyrie Blog](https://github.com/caozongpeng/SpringBootBlog)：Kyrie Blog是由Spring Boot 1.5、MyBatis、Thymeleaf等技术实现的个人网站。
* [Shiyi Blog](https://gitee.com/quequnlong/shiyi-blog)：一款基于Vue、Spring Boot的前后端分离博客系统。
* [Tumo](https://github.com/TyCoding/tumo)：Tumo Blog是一个简洁美观的博客系统，基于Spring Boot 2.x、Vue.js。
* [Blog](https://github.com/MQPearth/Blog)：前后端分离博客系统。
* [Blog](https://github.com/iszhouhua/blog)：基于Spring Boot搭建的开源个人博客系统。
* [DimpleBlog](https://github.com/martin-chips/DimpleBlog)：Dimple Blog是基于Spring Boot 2搭建的个人博客系统。
* [Aurora](https://github.com/xcyeye/aurora-blog)：Aurora是一个基于Spring Cloud Alibaba的多人微服务博客项目。
* [Blog](https://github.com/Jiale-Fang/blog)：基于Spring Boot、Vue、ELK、WebSocket构建的个人博客。
* [Lipi](https://github.com/SohanChy/Lipi)：Lipi将Hugo的强大功能融入到GUI中，并尝试让Hugo更易于日常使用，而无需记住任何烦人的命令。
* [MBlog](https://github.com/mblog-backend/backend)：MBlog基于Java、MySQL，支持自部署的前后端分离的微博。
* [Moti Blog](https://github.com/373675032/moti-blog)：莫提博客是一个基于Spring Boot开发的标准Java Web项目。
* [SkyBlog](https://github.com/yubifeng/SkyBlog)：SkyBlog是一个简单的Spring Boot、Vue前后端分离的博客系统。
* [ChuyunBlog](https://github.com/saysky/ChuyunBlog)：Spring Boot、MyBatis、Thymeleaf博客系统。
* [Spring React Blog](https://github.com/keumtae-kim/spring-boot-react-blog)：基于Token的博客应用，使用Spring Boot、React和JWT。

#### 论坛系统

* [Linfeng](https://gitee.com/virus010101/linfeng-community)：林风社交论坛是基于Spring Boot、MybatisPlus、Shiro、Quartz、JWT、WebSocket、Redis、Vue、Uniapp的前后端分离的社交论坛问答发帖/BBS、SNS项目。
* [BBS](https://github.com/maliangnansheng/bbs-springboot)：开源Java论坛(社区/问答/BBS/社交网络/博客)。
* [Echo](https://gitee.com/veal98/Echo)：Echo是一套前后端不分离的开源社区系统，基于目前主流Java Web技术栈，并提供详细的开发文档和配套教程。
* [PYBBS](https://github.com/atjiu/pybbs)：更实用的Java开发的社区。
* [Mawen](https://github.com/codedrinker/community)：开源论坛、问答系统，现有功能提问、回复、通知、最新、最热、消除零回复功能。
* [Forest](https://github.com/rymcu/forest)：Forest是一款现代化的知识社区项目，使用Spring Boot、Shiro、MyBatis、JWT、Redis实现。
* [FlowChat](https://github.com/dessalines/flowchat)：FlowChat是一个开源、可自托管的Reddit替代品，它拥有社区、主题标签、实时更新的讨论帖和投票功能。
* [JCommune](https://github.com/jtalks-org/jcommune)：JCommune是一个用Java编写的论坛引擎。
* [Symphony](https://github.com/88250/symphony)：Symphony是一款用Java实现的现代化社区(论坛/问答/BBS/社交网络/博客)系统平台，由房星科技开源。
* [Forum Java](https://github.com/Qbian61/forum-java)：Forum Java是一个开源的现代化社区平台。
* [Paicoding](https://github.com/itwanger/paicoding)：Paicoding是一个基于Spring Boot、MyBatis Plus、MySQL、Redis、ElasticSearch、MongoDB、Docker、RabbitMQ等技术栈实现的社区系统。
* [JEESNS](https://gitee.com/lxinet/jeesns)：JEESNS是一款基于Java企业级平台研发的社交管理系统。
* [FlyCMS](https://github.com/sunkaifei/FlyCms)：FlyCMS是一个类似知乎以问答为基础的完全开源的Java语言开发的社交网络建站程序。
* [Code Nest](https://github.com/xiaou61/U-space)：Code Nest是一个基于Spring Boot、Vue 3的前后端分离的一个程序员社区系统。
* [巡云轻论坛系统](https://gitee.com/diyhi/bbs)：巡云轻论坛系统包含论坛、问答模块，采用Java、MySQL架构。
* [NiterForum](https://github.com/yourkevin/NiterForum)：NiterForum是一个论坛/社区程序。
* [KuangSimpeBBS](https://gitee.com/kuangstudy/kuang_simple_bbs)：社区开源版本，基于Spring Boot精简代码。
* [Tatami](https://github.com/ippontech/tatami)：Tatami是一个开源企业社交网络，由Ippon开源。
* [Rhythm](https://github.com/FishPiOffical/rhythm)：Rhythm社区系统，超丰富的社区功能，基于Symphony社区版深度定制。
* [OpenIsle](https://github.com/nagisa77/OpenIsle)：OpenIsle是一个使用Spring Boot和Vue 3构建的全栈开源社区平台。
* [Spring Boot Forum](https://github.com/weiqingwen/spring-boot-forum)：简易微论坛、内容管理系统。
* [Roothub](https://github.com/miansen/Roothub)：SSM、MySQL开发的论坛系统。
* [JnuForum](https://github.com/xzping/jnu_forum)：JnuForum是基于Java的论坛系统。
* [Campus](https://github.com/oddfar/campus-example)：校园论坛、博客。
* [JForum](https://github.com/rafaelsteil/jforum3)：JForum是一款强大的论坛软件，作为Java Web应用构建。
* [Forum](https://github.com/fanchaoo/forum)：一个简单的论坛项目，采用Spring、SpringMVC、MyBatis。
* [Community](https://github.com/cosen1024/community)：一个仿照牛客网实现的讨论社区。

#### ERP系统

* [华夏ERP](https://gitee.com/jishenghua/JSH_ERP)：华夏ERP是基于Spring Boot框架和SaaS模式开源的ERP软件，目前专注进销存、财务、生产功能。
* [赤龙ERP](https://gitee.com/redragon/redragon-erp)：赤龙ERP是一款免费开源、业务闭环、灵活稳定的企业级ERP系统。
* [SCMR1](https://github.com/doublechaintech/scm-biz-suite)：供应链中台系统基础版，集成零售管理、电子商务、供应链管理、财务管理、订单管理等，由成都双链科技开源。
* [Metasfresh](https://github.com/metasfresh/metasfresh)：Metasfresh是一个响应迅速、免费且开源的ERP系统。
* [REBUILD](https://gitee.com/getrebuild/rebuild)：REBUILD通过创新的业务流程引擎帮助你快速搭建各类企业管理系统，全图形化配置无需了解技术，由上海锐昉科技公司开源。
* [Axelor Open Suite](https://github.com/axelor/axelor-open-suite)：Axelor Open Suite包含客户关系管理、销售管理、人力资源管理、项目管理、库存和供应链管理。
* [OMS](https://github.com/FJ-OMS/oms-erp)：一站式全渠道业务中台系统，包括订单管理系统OMS/电商ERP、库存WMS统一管理系统和SAP财务管理系统等，由厦门飞骥公司开源。
* [ADempiere](https://github.com/adempiere/adempiere)：ADempiere商业套件ERP/CRM/MFG/SCM/POS以开放且不减的方式实现了Bazaar方式。
* [Apache OFBiz](https://github.com/apache/ofbiz-framework)：OFBiz是一个用Java编写的ERP系统，包含大量库、实体、服务和功能来运行你业务的各个方面。
* [IDempiere](https://github.com/idempiere/idempiere)：IDempiere是完全开源的商务套件ERP/CRM/MFG/SCM/POS。
* [Skyeye](https://gitee.com/doc_wei01/erp-pro)：Skyeye基于Spring Boot框架，为中小企业打造的开源好用ERP软件。
* [MyCompany](https://github.com/lsfusion-solutions/mycompany)：MyCompany是一个适用于小型企业免费的开源ERP构建器。
* [Saas ERP](https://gitee.com/hy417393356/saas-java)：简云Saas平台是基于Spring Boot 2.2.0、Mybatis、JWT、Redis、Vue、ElementUI的前后端分离的Saas平台后台管理系统。
* [星云ERP](https://gitee.com/lframework/xingyun)：星云ERP基于Spring Boot框架，为中小企业提供完全开源、永久免费、用户体验好的进销存ERP系统。
* [Wimoor ERP](https://github.com/wimoor-erp/wimoor)：Wimoor ERP是国内首款百分百开源、支持商用的亚马逊ERP系统。
* [Compiere](https://www.aptean.com/en-US/solutions/erp/products/aptean-compiere-erp)：Compiere是一款开源ERP和CRM业务解决方案，适用于分销、零售、服务和制造领域的中小型企业。
* [Libertya](https://github.com/Disytel-Consulting-SA/libertya)：Libertya是一款综合管理管理软件，无需许可费用且完全免费使用，专为在任何类型的公司中快速实施和启动而设计。
* [BlueSeer ERP](https://github.com/BlueSeerERP/blueseer)：BlueSeer ERP是一个免费的开源多语言ERP软件包。
* [EAIRP](https://github.com/eairps/eairp)：开源Sass AI ERP系统。
* [Production SSM](https://github.com/megagao/production_ssm)：这是一个SSM、jQuery、EasyUI开发的ERP系统。
* [MagicERP](https://gitee.com/javastore/magic-erp-ui)：MagicERP是使用Java语言开发，基于Spring Boot 2.X架构体系构建的一套ERP系统。
* [Avalon](https://gitee.com/ShinraL/avalon)：Java版前后分离快速开发ERP平台，基于开源技术栈精心打造，融合Vue 3、Spring Boot。
* [ECP](https://gitee.com/loyin/ECP)：ECP是基于JFinal、Avalon、Bootstrap、JqGrid、Snaker工作流开发的客户关系及进销存财务系统。
* [Kingborn](https://gitee.com/kingborn/master-erp)：精博ERP是基于后端Spring Boot、MyBatis框架，PC前端Vue、ElementUI框架，微信小程序打造的全套ERP系统。
* [T3rik ERP](https://gitee.com/wangsanping/t3rik-erp)：T3rik是一个聚焦于制造执行系统(MES)和人力资源管理(HRM)的开源平台。

#### CRM系统

* [Wukong CRM](https://github.com/WuKongOpenSource/WukongCRM-11.0-JAVA)：悟空CRM是基于Spring Cloud Alibaba微服务架构、Vue ElementUI的前后端分离CRM系统。
* [Project 3 CRM](https://github.com/moshuying/project-3-crm)：CRM客户关系管理系统模板，一个不错的后台管理种子项目。
* [CalLite CRM](https://www.callite.it/)：CalLite是市场上功能最丰富、速度最快的呼叫中心软件，它可以让你消除用户时间的浪费(操作员、代理、主管、协调员等)，从而实现收益最大化。
* [YShop CRM](https://github.com/guchengwuyue/yshop-crm)：YShop CRM专门为企业销售团队量身定制的工具，能够有效的管理跟进客户提供销售业绩。
* [AEAI CRM](https://gitee.com/agileai/aeaicrm)：AEAI CRM包括一些核心的客户关系管理业务功能。
* [CordysCRM](https://github.com/1Panel-dev/CordysCRM)：Cordys CRM是飞致云出品的中国首个开源AI CRM，集信息化、数字化和智能化于一体。
* [JinBooks](https://github.com/jinbooks/jinbooks)：JinBooks是功能齐全的财务记账系统，告别Excel手工记账。

#### HRM系统

* [Vhr](https://github.com/lenve/vhr)：Spring Boot + Vue前后端分离的人力资源管理项目，可做常规企业级应用脚手架。
* [Wukong HRM](https://github.com/WuKongOpenSource/Wukong_HRM)：悟空HRM人力资源管理系统，提供入职管理、招聘管理、绩效考核管理等一站式人力管理流程。
* [iBizEHR](https://gitee.com/ibizlab/iBizEHR)：iBizEHR是一套可满足万人应用的高性能人力资源管理软件，埃毕致开源。
* [AEAI HR](https://gitee.com/agileai/aeaihr)：AEAI HR是数通畅联软件基于AEAI DP开发的开源Java Web系统，用来协助管理公司人力、薪酬等事务。
* [HRM](https://github.com/fo11ow-me/hrm)：基于Spring Boot、Vue、ElementUI的人力资源管理系统。

#### AI系统

* [ChatMaster](https://gitee.com/panday94/chat-master)：ChatMaster是基于AI大模型API实现的自建后端对话服务。
* [WGAI](https://gitee.com/dromara/wgai)：WGAI是开箱即用的Java AI平台，融合了AI图像识别、AI智能客服、AI语言模型，可定制化、自主、离线化部署。
* [AIAS](https://gitee.com/mymagicpower/AIAS)：人工智能加速器套件，提供SDK、平台引擎、场景套件。
* [HiMarket](https://github.com/higress-group/himarket)：HiMarket是一个开箱即用的AI开放平台解决方案，可以用于构建企业级的AI能力市场与开发者生态中心，由阿里开源。
* [Free NLP API](https://gitee.com/stonedtx/free-nlp-api)：免费的NLP、情感分析、实体识别、图像识别与分类、OCR识别、语音识别接口，由思通数科开源。
* [RuoYi AI](https://github.com/ageerle/ruoyi-ai)：RuoYi AI是一个全栈式AI开发平台，旨在帮助开发者快速构建和部署个性化的AI应用。
* [AIFlowy](https://gitee.com/aiflowy/aiflowy)：AIFlowy是一个使用Java开发的AI产品的底座和基石。
* [XiaoZhi ESP32 Server](https://github.com/xinnan-tech/xiaozhi-esp32-server)：本项目为开源智能硬件项目XiaoZhi ESP32提供后端服务。
* [Xiaozhi ESP32 Server Java](https://github.com/joey-zhou/xiaozhi-esp32-server-java)：基于Xiaozhi ESP32项目开发的Java版本服务端。
* [AI Beehive](https://github.com/hncboy/ai-beehive)：AI蜂巢，基于Java使用Spring Boot 3和JDK 17，支持的功能有ChatGPT、OpenAI Image、Midjourney、NewBing、文心一言等等。
* [LangChat](https://github.com/TyCoding/langchat)：LangChat是Java生态下企业级AIGC项目解决方案，在RBAC权限体系的基础上，集成AIGC大模型能力，帮助企业快速定制AI知识库、企业AI机器人。
* [Spring Boot OpenAI ChatGPT](https://github.com/274056675/springboot-openai-chatgpt)：超级AI大脑是一个基于Spring Cloud的微服务架构，已对接GPT-3.5、GPT-4.0、百度文心一言、Stable Diffusion AI绘图、Midjourney绘图等。
* [Dubhe](https://gitee.com/zhijiangtianshu/Dubhe)：之江天枢人工智能开源平台是由之江实验室牵头，联合国内顶尖科研力量共同打造的国产化自主可控的人工智能开源平台。
* [TorchV](https://torchv.com/)：TorchV AI是一款基于LLM、RAG和Agent技术的人工智能PaaS产品，目标是帮助企业快速建立AI应用。
* [FreeChat](https://github.com/freechat-fun/freechat)：FreeChat的宗旨是构建一个云原生、健壮并且可快速商用化的企业级AI虚拟角色平台。
* [PmHub](https://github.com/laigeoffer/pmhub)：PmHub是一套基于Spring Cloud、LLM的微服务智能项目管理系统。
* [HugAI](https://github.com/TouShang6015/Hugai-chatgpt)：HugAI是由Spring Boot集成Open AI SDK开发的一套智能AI知识库，支持GPT对话，AI绘图Midjourney、Stable Diffusion、Open AI。
* [AppPlatform](https://github.com/ModelEngine-Group/app-platform)：AppPlatform是一个前沿的大模型应用工程，旨在通过集成的声明式编程和低代码配置工具，简化AI应用的开发过程。
* [Bella Workflow](https://github.com/LianjiaTech/bella-workflow)：Bella Workflow是贝壳找房内部核心的LLM应用开发平台，致力于为开发者提供更灵活、高效、强大的AI应用构建能力。
* [LangChain4j AIDeepin](https://github.com/moyangzhan/langchain4j-aideepin)：LangChain4j AIDeepin是基于AI的工作效率提升工具。
* [U3W AI](https://gitee.com/U3W-AI/U3W-AI)：优立方AI主机提供多AI平台集成的AIGC解决方案，支持免Token使用并与微信生态对接。
* [Art](https://gitee.com/fxzcloud/art)：Art是一个开源、一站式AI应用开发平台，其灵感来源于行业领先的Coze和Dify。
* [Torch Yun](https://github.com/isxcode/torch-yun)：至数云是一款超轻量、企业级人工智能应用平台。
* [SuperSQL](https://gitee.com/guocjsh/supersql-open)：SuperSQL是一个基于国内外先进生成式大模型的Java框架，实现从自然语言文本到SQL查询的智能转换。
* [DataAgent](https://github.com/spring-ai-alibaba/DataAgent)：DataAgent是一个基于Spring AI Alibaba的自然语言转SQL项目，能让你用自然语言直接查询数据库，不需要写复杂的SQL。
* [DAT](https://github.com/junjiem/dat)：DAT让业务人员能够用自然语言直接与数据库对话，无需编写复杂的SQL查询。
* [AstronRPA](https://github.com/iflytek/astron-rpa)：AstronRPA是一个全能型的机器人流程自动化开发工具，为企业和开发者提供从设计到部署的全流程RPA自动化解决方案，由科大讯飞开源。
* [TalkX](https://github.com/big-mouth-cn/talkx)：TalkX是一个开源的大模型聊天平台，界面适配移动端，并且衍生出了编程插件、小智ESP智能机器人等能力。
* [Quill AI](https://github.com/Feynix2004/Quill-AI)：Quill AI是一个基于大模型(LLM)和多能力平台(MCP)的智能Agent构建平台。
* [QiaoQiaoYun](https://github.com/jeecgboot/qiaoqiaoyun)：敲敲云是一款免费的AI零代码平台，助力企业快速实现搭建业务系统和构建AI应用。

#### OA系统

* [OASys](https://gitee.com/aaluoxiang/oa_system)：OASys是一个OA办公自动化系统，使用Maven进行项目管理。
* [O2OA](https://gitee.com/o2oa/O2OA)：O2OA低代码开发平台，100%开源企业协同办公定制平台，提供完整的前后端API和模块定制能力。
* [JeePlatform](https://github.com/u014427391/jeeplatform)：JeePlatform项目是一款以Spring Boot为核心框架，和多种开源组件框架而成的一款通用基础平台。
* [JFinalOA](https://gitee.com/glorylion/JFinalOA)：点狮OA是一套多租户的企业办公系统，可以提供给集团级企业用户使用，也可对外提供未SAAS服务多公司进行入驻。
* [云网OA](https://gitee.com/bestfeng/yimioa)：云网OA是一款本地化部署的OA软件。
* [心通达OA](https://gitee.com/xtdoa/xtdoa)：心通达低代码开发平台，由北京高速波软件公司开源。
* [Smart Web2](https://gitee.com/bcworld/smart-web2)：Smart Web2是一套相对简单的OA系统，包含了流程设计器、表单设计器、权限管理、简单报表管理等功能。
* [稠云智能办公系统](https://gitee.com/cysoft_1/oa)：基于Spring Boot、MyBatis、Redis、Durid、Beetl框架组合的开源OA系统，自研工作流引擎，支持可视化表单设计与流程设计。
* [LemonOA](https://github.com/xuhuisheng/lemon)：LemonOA是一个通用的OA产品。
* [唛盟OA](https://gitee.com/maimengcloud/oa-backend)：唛盟以协同办公为核心，涵盖资产管理、会议管理、绩效管理、人力资源管理、办公用品管理、合同管理、档案管理等日常办公常用功能的企业级协同办公整体解决方案。
* [OASys](https://github.com/Furinai/OASys)：基于Spring Cloud和Vue 3的OA系统。

#### DMS系统

* [Teedy](https://github.com/sismics/docs)：Teedy是一个面向个人和企业的开源、轻量级文档管理系统。
* [MxsDoc](https://gitee.com/RainyGao/DocSys)：MxsDoc是基于Web的文件管理系统，主要用于企业或个人的文件存储管理，方便随时查看和统一管理。
* [OpenKM](https://github.com/openkm/document-management-system)：OpenKM文档管理系统允许企业控制电子文档的制作、存储、管理和分发，从而提高效率以及重用信息和控制文档流的能力。
* [LogicalDOC](https://github.com/logicaldoc/community)：LogicalDOC社区版是一款开源文档管理软件。
* [FormKiQ](https://github.com/formkiq/formkiq-core)：FormKiQ是一个功能齐全的文档管理平台/文档层。
* [ECMS](https://github.com/exoplatform/ecms)：eXo的组合ECM(文档)和CMS管理系统。
* [Docway](https://gitee.com/zhoujingjie/apiManager)：小幺鸡文档管理工具，支持富文本、Markdown、HTTP、WebSocket及其在线测试。

#### WMS系统

* [RinSim](https://github.com/rinde/RinSim)：RinSim是一个用Java编写的物流模拟器，支持动态取货和送货问题的(去)中心化算法，由比利时鲁汶大学计算机科学系部门的imec-DistriNet小组开发。
* [Warehouse](https://github.com/yeqifu/warehouse)：Warehouse是一个仓库管理系统。
* [WMS RuoYi](https://gitee.com/zccbbg/wms-ruoyi)：若依WMS是一套基于若依的仓库管理系统，支持lodop和网页打印入库单、出库单。
* [Finer](https://gitee.com/FINERME/psi)：面向中小企业的进销存管理PSI和仓库管理系统WMS。
* [OpenWMS](https://github.com/openwms/org.openwms)：OpenWMS是一个免费使用且可扩展的仓库管理系统(WMS)，带有适用于自动和手动仓库的物料流控制(MFC)系统。
* [Deer WMS](https://gitee.com/deerwms/deer-wms-2)：Deer WMS是基于自动化输送线、机械臂、点数机、提升机、堆垛机等自动化设备和现代化仓储精益管理思想开发出来的仓库管理系统，由南京大鹿智造开发。
* [MyWMS](https://github.com/wms2/mywms)：MyWMS LOS是开源仓库管理系统WMS，它在工业24/7环境中运行并支持所有基本流程。
* [OpenBoxes](https://github.com/openboxes/openboxes)：OpenBoxes是一个开源供应链管理系统，用于管理医疗机构和救灾工作的物资和药物。
* [WarehouseManager](https://gitee.com/yangshare/warehouseManager)：基于SSM框架的仓库管理系统。
* [S-PMS](https://github.com/s-pms/SPMS-Server)：S-PMS智能生产管理系统，是一个集成化、智能化的企业级应用软件，
* [JeeWMS](https://gitee.com/erzhongxmu/JEEWMS)：JeeWMS是基于Java全栈技术打造的智能仓储中枢系统。
* [Open WES](https://github.com/jingsewu/open-wes)：Open WES是一个可定制的开源仓库执行系统，旨在简化仓库运营。
* [KS Inventory](https://gitee.com/KrityCat/ks-inventory-system)：铠思进销存系统是一套开源的商用进销存系统，用于中小公司系统转型。

#### MES系统

* [KTG MES](https://gitee.com/kutangguo/ktg-mes)：苦糖果MES系统是一款B/S结构、开源、免费的生产执行管理系统。
* [MES MOM](https://gitee.com/wangziyangyang/MES-Springboot)：MES制造执行系统。
* [Qcadoo MES](https://github.com/qcadoo/mes)：Qcadoo MES是一款针对中小企业的生产管理互联网应用，它结合了大型ERP系统的功能，适应中小企业的具体特点。
* [Industry MES](https://github.com/ricefishtech/industry4.0-mes)：开源MES，生产制造管理系统。
* [HM MES](https://gitee.com/imdreamer/hm-MES)：这里汇聚了开源社区最好的MES系统，一共有几套系统。

#### PMS系统

* [HC](https://gitee.com/wuxw7/MicroCommunity)：HC小区管理系统是一套SaaS物业管理系统。
* [ZhaoXin](https://gitee.com/fanhuibin1/zhaoxinpms)：肇新智慧物业是一个开源的小型物业管理系统，由山西肇新公司开发。
* [YFCommunity](https://gitee.com/qingyun-software/YFCommunity)：萤丰开源智慧小区智慧社区系统Java版。
* [Smart Parking](https://gitee.com/52itstyle/smart-parking)：基于Spring Boot、Vue的智能停车场项目。

#### PLM系统

* [DocDokuPLM](https://github.com/docdoku)：DocDokuPLM是一款强大的先进开源PLM解决方案，由OW2开发。
* [iBizPMS](https://gitee.com/ibizlab/iBizPMS)：iBiz产品生命周期管理在于通过简化操作界面，实现研发管理流程的自动化、数字化及智能化。

#### EMS系统

* [OpenEMS](https://github.com/OpenEMS/openems)：OpenEMS是一个模块化的能源管理应用平台。
* [CP EMS RuoYi](https://gitee.com/cloudpulse/cp-ems-ruoyi)：CP EMS RuoYi是一款基于RuoYi框架开发的开源能源管理系统。
* [Zhitan EMS](https://gitee.com/liulingling1993/zhitan-ems)：智碳能源管理系统，基于Spring Boot和若依框架开发。

#### 云盘系统

* [ZFile](https://github.com/zfile-dev/zfile)：ZFile是一个适用于个人或小团队的在线网盘程序。
* [QiWen File](https://gitee.com/qiwen-cloud/qiwen-file)：基于Spring Boot、Vue CLI框架开发的分布式文件系统。
* [ZWZ](https://gitee.com/college996/zwz-netdisk)：基于Spring Boot、Dubbo、Zookeeper、Nacos技术栈的网盘系统。
* [Kiftd](https://gitee.com/kohgylw/kiftd)：Kiftd是一款便捷、开源、功能完善的Java网盘/云盘系统。
* [JmalCloud](https://github.com/jamebal/jmal-cloud-server)：JmalCloud是一款私有云存储网盘项目，能够简单安全管理你的云端文件。
* [Free FS](https://gitee.com/xddcode/free-fs)：Free FS是基于Spring Boot 3、MyBatis Flex、MySQL、Sa-Token、LayUI等搭配阿里云Oss、Minio、七牛云等各种云存储实现的云存储管理系统。
* [Network Drive](https://github.com/risesoft-y9/Network-Drive)：网络硬盘是通过存储、分类、检索、分享、协作、下发、回收、展示等方式管理文档、文件、图片、音频、视频等资料的工具，由北京有生博大软件开发。

#### 充电桩系统

* [SteVe](https://github.com/steve-community/steve)：SteVe提供充电桩管理、用户数据以及用于用户身份验证的RFID卡等基本功能，由亚琛工业大学开发。
* [Java OCA OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP)：OCA定义的开放充电点协议(OCPP)的开源客户端和服务器库。
* [OCPP](https://github.com/ShellRechargeSolutionsEU/ocpp)：OCPP是欧洲最大的电动汽车充电站运营商之一NewMotion开发和使用的OCPP的实现。
* [Caifeng](https://github.com/981011512/--)：新能源充电桩系统，停车场小程序。
* [HUIZHI ChargeOS Cloud](https://github.com/roinli/HUIZHI-ChargeOS-cloud)：慧知开源充电桩平台是一款全开源可商用的系统。
* [Orise Charge Cloud](https://github.com/NaTieJun/orise-charge-cloud)：充电桩开源云平台，由悠码科技开发。
* [JChargePointProtocol](https://gitee.com/san-bing/JChargePointProtocol)：一个高性能、分布式、支持海量并发量的充电桩Java服务端。
* [YunCharging](https://github.com/yuncitys/YunCharging)：YunCharge是一套用于二轮电单车和四轮充电桩充电领域的运营和计费系统，由深圳云创智城科技公司开发。
* [100Charge](https://gitee.com/ustcyc/100charge)：100Charge是基于若依的开源充电运营平台。

#### 数据中台

* [LarkMidTable](https://gitee.com/LarkMidTable/LarkMidTable)：LarkMidTable是一站式开源的数据中台，实现元数据管理，数据仓库开发，数据质量管理，数据的可视化，实现高效赋能数据前台并提供数据服务的产品。
* [QData](https://gitee.com/qiantongtech/qData)：QData是一款一站式开源数据中台，覆盖中台基础建设、数据治理、数据开发、监控告警、数据服务与数据可视化等核心能力，由江苏千桐科技公司开发。
* [AllData](https://github.com/alldatacenter/alldata)：AllData大数据产品是可定义数据中台，以数据平台为底座、数据中台为桥梁，以机器学习平台、GPT平台为框架，提供全链路数字化解决方案。
* [Spark Yun](https://github.com/isxcode/spark-yun)：至轻云是一款超轻量级、企业级大数据计算平台，基于Spark生态打造。
* [Data Center](https://gitee.com/fhs-opensource/data-center)：基于Kettle的可视化数据集成平台。
* [SRT Data Center](https://gitee.com/zrxjava/srt-data-center)：数睿通数据中台采用Spring Cloud Alibaba、Tidb、Doris、Flink、Hadoop等技术开发。
* [Sanzuwu](https://gitee.com/sanzujinwu/sanzuwu)：三足乌数据中台融合数据接入、数据开发、数据仓库、数据治理、数据资产、数据服务、BI可视化、系统管理、系统运维等功能模块为一体。

#### 知识管理系统

* [Logseq](https://github.com/logseq/logseq)：Logseq是一个知识管理和协作平台。
* [Atlassian Confluence](https://www.atlassian.com/zh/software)：Confluence是一个专业的企业知识管理与协同软件，也可以用于构建企业Wiki，由Atlassian开发。
* [JVS Knowledge](https://gitee.com/software-minister/jvs-knowledge-ui)：提供在线笔记、知识沉淀、在线产品手册、知识库、在线电子教程等功能。
* [Zyplayer DOC](https://gitee.com/dromara/zyplayer-doc)：Zyplayer DOC是一款适合团队和个人使用的WIKI文档管理工具，同时还包含数据库文档、API接口文档，由dromara社区开源。
* [WCP](https://gitee.com/macplus/WCP)：WCP是一套BS架构的开源知识管理系统、知识库系统，由太原扁舟科技开源。
* [QKnow](https://gitee.com/qiantongtech/qKnow)：QKnow是一款面向企业级应用的开源知识管理系统，由江苏千桐科技公司开发。
* [Knowledge](https://github.com/support-project/knowledge)：Knowledge是一个开源知识库平台。
* [Wukong KnowledgeBase](https://github.com/WuKongOpenSource/Wukong_KnowledgeBase)：悟空知识库内置了大量的模板，可辅助用于项目工作的各个环节，包括产品需求、会议记录、决策记录、指导手册、回顾记录、工作计划、任务报告等等。
* [Apache JSPWiki](https://github.com/apache/jspwiki)：JSPWiki是一个简单的WikiWiki克隆，用Java和JSP编写。
* [Apache Jackrabbit Oak](https://github.com/apache/jackrabbit-oak)：Jackrabbit Oak是一个可扩展、高性能的分层内容仓库，旨在用作现代世界级网站和其他要求高的内容应用程序的基础。
* [KYKMS](https://gitee.com/kyxxjs/km_community)：基于Elasticsearch的文件管理系统/知识管理系统，由广州科亿信息开源。
* [Hackpad](https://github.com/dropbox/hackpad)：Hackpad是一个基于Web的实时Wiki，基于开源EtherPad协作文档编辑器。
* [InfoSphere](https://gitee.com/devlive-community/incubator-infosphere)：InfoSphere是一款面向企业和个人的开源Wiki系统，旨在提供简单而强大的知识管理解决方案，由Devlive社区开源。
* [ModeShape](https://github.com/ModeShape/modeshape)：ModeShape是一种分布式、分层、事务性和一致的数据存储，支持查询、全文搜索、事件、版本控制、引用以及灵活的动态模式，由RedHat开源。
* [Bella Knowledge](https://github.com/LianjiaTech/bella-knowledge)：Bella Knowledge是Bella体系内的知识管理中心，提供文件、数据集在内多类数据源的统一存储、管理能力，由贝壳开源。
* [Knowledge Engine](https://github.com/TNO/knowledge-engine)：Knowledge Engine是一种互操作性解决方案，使不同的知识库更容易地进行通信，由荷兰应用科学研究院开源。
* [Castle](https://gitee.com/hcwdc/knowledgebase)：Castle知识库是一款集知识管理、智能检索、权限控制、文档处理与数据分析于一体的综合型企业级知识服务平台。

#### SCRM系统

* [LinkWeChat](https://gitee.com/LinkWeChat/link-wechat)：LinkWeChat是基于企业微信的开源SCRM系统，是企业私域流量管理与营销的综合解决方案。
* [源雀SCRM](https://gitee.com/iyque/iYqueCode)：源雀SCRM是完全开源的私域数智化营销解决方案。
* [MarketGo](https://github.com/marketgo-scrm/MarketGo-SCRM)：MarketGo是一个营销引擎，通过提供的标准化功能和基础能力，让开发者能快速搭建适合自己企业的营销系统。
* [EasyLink](https://github.com/lianluoyi/easyink_System)：EasyLink是基于企业微信生态的一站式私域流量运营平台。
* [Pumplabs SCRM](https://github.com/Pumplabs/scrm)：Pumplabs SCRM是一款开源、基于企业微信、简洁便捷、高效协作的CRM应用，主要面向一定售周期的业务，如家装、汽车服务、保险、IT、美容、教培等。
* [MoChat](https://gitee.com/mochat/mochat-java)：MoChat是基于企业微信的开源应用开发框架&引擎，也是一套通用的企业私域流量管理系统。

#### 门户框架

* [Apache Protals](http://portals.apache.org/)：Portals项目提供各种软件产品，包括Jetspeed-2、Pluto和Portals Applications。
* [Liferay Portal](https://github.com/liferay/liferay-portal)：Liferay是一个现成的，即开即用的，功能完备的门户网站。
* [Apereo uPortal](https://github.com/uPortal-Project/uPortal)：uPortal是由高等教育界构建并为其服务的领先开源企业门户框架，由威斯康星大学开源。
* [Silverpeas](https://github.com/Silverpeas/Silverpeas-Core)：Silverpeas是一个基于Java的开源协作门户解决方案。
* [MyWebSite](https://gitee.com/out-project/mywebsite)：Spring Boot搭建的公司官网门户系统。

#### 教育软件

* [TEAMMATES](https://github.com/TEAMMATES/teammates)：TEAMMATES是一个免费的在线工具，用于管理学生的同行评估和其他反馈路径，由新加坡国立大学开源。
* [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)：BigBlueButton是一个开源虚拟教室，旨在帮助教师教学和学习者学习。
* [Sakai](https://github.com/sakaiproject/sakai)：Sakai是一个免费提供的、功能丰富的技术解决方案，用于学习、教学、研究和协作，由美国印第安纳大学、密西根大学、斯坦福大学和麻省理工学院于2004年发起。
* [OpenOLAT](https://github.com/OpenOLAT/OpenOLAT)：OpenOlat是一个基于Web的电子学习平台，用于教学、学习、评估和交流，是一个LMS、一个学习管理系统。
* [SkillTree](https://github.com/NationalSecurityAgency/skills-service)：SkillTree是一个微型学习游戏化平台，提供开箱即用的UI可视化、方便的客户端集成库以及用于管理游戏化培训档案创建和管理的仪表板，由美国国家安全局开源。
* [SG Exam](https://gitee.com/wells2333/sg-exam)：基于Spring Boot、Vue构建的高效教学管理平台，专为便捷与美学设计。
* [Roncoo Education](https://gitee.com/roncoocom/roncoo-education)：领课教育系统是一套基于点播、直播、班级、考试、营销等功能完善的在线教育系统，由广州领课网络公司开源。
* [Wisdom Education](https://gitee.com/zhuimengshaonian/wisdom-education)：基于Spring Boot、Mybatis Plus、Shiro、MySQL、Redis构建的智慧云智能教育平台。
* [Inxedu](https://gitee.com/inxeduopen/inxedu)：免费开源网校系统，轻松搭建在线教育平台。
* [PlayEdu](https://github.com/PlayEdu/PlayEdu)：PlayEdu是由白书科技团队打造出的一款业内领先的线上培训解决方案。
* [Teaching](https://github.com/open-scratch/teaching-open)：Teaching针对机构、学校提供STEAM在线教育解决方案。
* [HZB EduERP](https://gitee.com/ryan1981/hzb-eduerp)：HZB是一套支持私有化部署的教培行业教务管理系统。
* [Online MOOC](https://github.com/finch04/online-mooc)：智慧MOOC是基于Spring Cloud Alibaba体系的在线教育平台，整合了AI客服、直播间IM、课程售卖等功能。

#### 评测系统

* [学之思](https://gitee.com/mindskip/xzs-mysql)：学之思开源考试系统是一款Java、Vue前后端分离的考试系统，由武汉思维跳跃公司开源。
* [WTS](https://gitee.com/macplus/WTS)：本系统为在线答题系统，支持在线考试、在线练习等功能，由太原扁舟科技公司开发。
* [HOJ](https://gitee.com/himitzh0730/hoj)：基于Vue、Spring Boot、Spring Cloud Alibaba构建的前后端分离，分布式架构的评测系统。
* [SpringBoot Vue Online Exam](https://github.com/YXJ2018/SpringBoot-Vue-OnlineExam)：该项目是一个后端使用Spring Boot，前端使用Vue和Element-UI组件库配合开发的在线考试系统。
* [云帆](https://github.com/qiutiandefeng/yfexam-exam)：云帆是Spring Boot、Vue开发的在线考试系统。
* [Glowxq OJ](https://github.com/glowxq/glowxq-oj)：Glowxq OJ是一个专为信息学奥林匹克竞赛和少儿编程教学设计的在线编程测评系统。
* [Spring Boot Online Exam](https://github.com/lsgwr/spring-boot-online-exam)：基于Spring Boot的在线考试系统。
* [Exam++](https://gitee.com/ocelot/examxx)：Exam++是基于Java与MySQL开发的网络考试系统。
* [Online Exam System](https://github.com/Alanosy/online-exam-system-backend)：本项目致力于打造一款通用的在线考试系统。
* [TamGuo](https://gitee.com/smiletocandy/tamguo)：TamGuo是基于Java开发的在线题库系统。
* [SDUOJ](https://github.com/SDUOJ/OnlineJudge)：SDUOJ是一款开源在线评测系统。
* [PassJava](https://github.com/Jackson0714/PassJava-Platform)：一款面试刷题的Spring Cloud开源系统。
* [VOJ](https://github.com/hzxie/voj)：VOJ是一个基于Spring MVC框架的跨平台在线评判系统。
* [ZOJ](https://github.com/licheng/zoj)：浙江大学在线评判，一款允许人们在线解决算法问题的在线评判工具。
* [Judgels](https://github.com/ia-toki/judgels)：Judgels是一个现代编程竞赛系统。
* [ZuiOJ](https://github.com/DaZuiZui/ZuiOJ)：基于Spring Boot、Spring Cloud、Vue的开源在线代码评委系统。
* [D-OnlineJudge](https://github.com/Decade-qiu/D-OnlineJudge)：D-OnlineJudge是一个全栈在线编程平台，采用基于Spring Cloud的微服务架构和Vue 3前端。
* [XMKY Exam](https://gitee.com/qq1247/xmky-exam)：小猫考试是一款开源免费的企业在线考试系统。

#### 理财系统

* [Firday](https://gitee.com/Ezer_Wu/friday)：Firday分布式家庭理财系统。
* [MoneyNote API](https://github.com/getmoneynote/moneynote-api)：一个开源免费的记账解决方案，包括后端、网页版、App，主要用于个人生活记账，开店收支记账。
* [jGnash](https://github.com/ccavanaugh/jgnash)：jGnash是一个免费的个人理财助手。
* [Fenxi365](https://gitee.com/flyemu/public-financial)：纷析云SaaS云财务软件开源版。

#### Data API

* [DB2Rest](https://github.com/kdhrubo/db2rest)：DB2Rest是一个现代低代码REST Data API平台，可以轻松构建智能应用程序。
* [Spring Data REST](https://github.com/spring-projects/spring-data-rest)：该项目的目标是提供一种灵活且可配置的机制来编写可以通过HTTP公开的简单服务。

#### 插件框架

* [OSGi](https://www.osgi.org/)：OSGi是一种模块化方法和规范，允许开发者在Java中创建稳健、高度解耦且动态的应用程序。
* [Spring Plugin](https://github.com/spring-projects/spring-plugin)：Spring Plugin提供了一种更务实的插件开发方法。
* [Jarslink](https://github.com/sofastack/sofa-jarslink)：Jarslink是SOFABoot官方基于SOFAArk开发的功能插件，负责管理多应用在SOFAArk容器之上的合并部署，由蚂蚁开源。
* [PF4J](https://github.com/pf4j/pf4j)：PF4J是一个开源的轻量级Java插件框架。
* [Spring Brick](https://gitee.com/starblues/springboot-plugin-framework-parent)：为动态扩展系统而生的插件开发框架。
* [SBP](https://github.com/hank-cp/sbp)：SBP将面向插件的编程引入Spring Boot。
* [Lattice](https://github.com/hiforce/lattice)：Lattice是一个强大、轻量级的业务扩展调用框架。
* [EXP](https://github.com/stateIs0/exp)：EXP是一款Java插件化热插拔框架。
* [Mosaic](https://github.com/Time-Machine-Lab/Mosaic)：Mosaic是一个面向企业级应用的现代化Java插件框架。
* [Easy Extension](https://github.com/xiaoshicae/easy-extension)：Easy Extension框架主要解决复杂系统的扩展性问题。
* [JPlugin](https://github.com/sunlet/jplugin)：JPlugin是轻量级的应用框架，支持便捷地开发插件式系统。
* [Zephyr](https://github.com/sunshower-io/zephyr)：Zephyr是一个基于Java的开源插件框架，具有智能依赖管理、模块化设计和小巧的占用空间。
* [KWai Business Extension Framework](https://github.com/kwai/kwai-business-extension-framwork)：KWai Business Extension Framework提供一套通用业务扩展框架，通过引入业务身份识别和可扩展的隔离架构，帮助业务搭建定制业务流程的架构标准、研发工具和运维体系，由快手开发。
* [SciJava Common](https://github.com/scijava/scijava-common)：SciJava Common提供了插件框架，支持可扩展的服务发现机制(通过自身的注解处理器)，使插件可以动态加载。
* [LingFrame](https://github.com/LingFrame/LingFrame)：LingFrame是一个基于JVM的新一代微内核插件化框架。

#### POS

* [Salespoint Framework](https://github.com/st-tu-dresden/salespoint)：Salespoint是一个用于开发销售点应用程序的框架，由德累斯顿工业大学、慕尼黑联邦国防军大学共同开发。
* [MinPOS](https://sourceforge.net/projects/minpos/)：MinPOS是一款销售点免费软件，它基于Openbravo POS开发，但经过大量修改。
* [Floreant POS](https://floreant.org/)：Floreant POS是一个用Java编写的独立于平台的销售点应用程序。
* [Openbravo POS](https://github.com/iMartinezMateu/openbravo-pos)：Openbravo Java POS是一款专为触摸屏设计的销售点应用程序，支持票证打印机、客户显示器和条形码扫描仪。
* [POSper](https://sourceforge.net/projects/posper/)：POSper是专为小型企业设计的销售点系统。
* [SmartPOS](https://sourceforge.net/projects/smart-pos/)：SmartPOS是一个完整的ERP、POS，它具有ERP的所有功能，但创建了一个直观、敏捷且易于学习的销售点100% Web。
* [POSSUM](https://github.com/target/POSSUM)：POSSUM是一个Spring Boot框架Java项目，旨在将遵循JavaPOS规范的所有USB连接的POS外围设备(扫描仪、打印机、通道灯、线路显示器、现金抽屉、支票阅读器、秤等)的功能呈现为Web服务。
* [ChromisPOS](https://github.com/ChromisPos/ChromisPOS)：ChromisPOS是用于零售和餐饮的销售点系统。
* [POS System](https://github.com/hanlinag/point-of-sale-system)：用JavaFX编写的销售点系统。
* [NORD POS](https://github.com/nordpos/nordpos)：NORD POS是Openbravo POS应用的一个分支，专为触摸屏设计。
* [Sanguine POS](https://sanguinesoftwares.com/sanguine-pos/)：Sanguine POS采用Java开发，可管理餐饮行业的所有计费复杂性。
* [ReadySTORE POS](https://www.utcretail.com/readystore-pos)：UTC RETAIL的ReadySTORE POS解决方案是一款专为多店零售商设计的企业软件解决方案。
* [JavaFX POS](https://github.com/sadatrafsanjani/JavaFX-Point-of-Sales)：带有库存管理的POS系统。
* [Store POS](https://github.com/inforkgodara/store-pos)：Store POS是一个简单的POS软件，使用JavaFX开发。

#### 业务

* [CDM](https://github.com/microsoft/CDM)：CDM是一种声明性规范，是标准实体的定义，代表业务和生产力应用程序中常用的概念和活动，并且也正在扩展到观察和分析数据，由Microsoft开源。
* [Waltz](https://github.com/finos/waltz)：Waltz可以让你直观地了解并定义组织的技术格局，由金融科技基金会开源。
* [EventHub](https://github.com/Codecademy/EventHub)：EventHub使公司能够进行跨设备事件跟踪。
* [Spring Web Flow](https://github.com/spring-projects/spring-webflow)：Spring Web Flow有助于构建需要引导导航的Web应用程序-例如购物车、航班登记、贷款申请等等。
* [EZ-vCard](https://github.com/mangstadt/ez-vcard)：EZ-vCard是一个用于Java的vCard解析器库。
* [eXo Platform](https://github.com/exoplatform/platform-public-distributions)：eXo Platform是面向成长型团队和企业的开源数字工作场所解决方案。

#### 电商

* [Broadleaf Commerce](https://github.com/BroadleafCommerce/BroadleafCommerce)：Broadleaf Commerce CE是一个完全用Java编写并利用Spring框架的电子商务框架。
* [SAP Commerce](https://www.sap.com/products/crm/commerce-cloud.html)：SAP Commerce是一个使用Java、基于Spring MVC框架的电子商务平台。
* [Ktor E-Commerce](https://github.com/piashcse/ktor-E-Commerce)：Ktor E-Commerce是一种高性能后端解决方案，专为使用Ktor构建的现代电子商务应用程序而设计。
* [YAS](https://github.com/nashtech-garage/yas)：YAS是一个商店项目，旨在练习用Java构建典型的微服务应用程序。
* [Q-Calculator](https://github.com/CyrilFeng/Q-calculator)：Stateless高性能优惠叠加计算框架。
* [Shopizer](https://github.com/shopizer-ecommerce/shopizer)：Java开源电子商务软件。
* [Scipio ERP](https://github.com/ilscipio/scipio-erp)：Scipio ERP是一个基于Java 11+和内置Tomcat应用服务器的开源业务应用程序工具包。
* [YesCart](https://github.com/inspire-software/yes-cart)：YesCart是一个使用Java技术构建的电子商务平台。
* [Qalingo](https://github.com/qalingo/qalingo-engine)：Qalingo是一个为B2C和B2B业务开发的开源Java电子商务平台。
* [Mayocat](https://github.com/jvelo/mayocat-shop)：Mayocat是一个Java开源市场和电子商务平台。
* [Kadro Merchant](https://kadro.com/ecommerce/)：Kadro Merchant是一个基于Java的全功能电子商务框架，专为电子商务业务生命周期的任何阶段而设计。
* [SoftSlate](https://www.softslate.com/)：SoftSlate是一个开源Java购物车，提供全套电子商务功能以及高性能。
* [Avetti Commerce](https://avetticommerce.com/)：Avetti Commerce是一个可靠的基于Java的电子商务解决方案，它具有针对B2C和B2B业务以及多商店电子商务的一系列深入功能。
* [Elastic Path](https://www.elasticpath.com/products/architecture/technologies/java-ecommerce)：基于Spring、OpenJPA、Eclipse、Solr、Velocity、Groovy、jQuery等开源技术的Java电子商务平台。
* [JadaSite](https://jadasite.com/)：JadaSite是一个基于Java、开源、易于使用且功能丰富的内容管理和电子商务系统。
* [KonaKart](https://www.konakart.com/)：KonaKart是一个针对大中型在线零售商的Java电子商务系统。
* [ShoppingCart](https://github.com/ikismail/ShoppingCart)：基于Spring MVC和多模块开发的一个端到端电子商务Web应用程序。
* [POP Commerce](https://github.com/moqui/PopCommerce)：POP Commerce是一个简单的电子商务应用程序和一个管理应用程序。
* [Macha](http://macha.machanism.org/index.html)：Macha项目是一个模块化且可扩展的框架，专为构建强大的电商应用而设计。
* [Memberclub](https://github.com/juejin-wuyang/memberclub)：Memberclub是面向电商C端业务的快速开发平台。
* [Online Shop Application](https://github.com/zhulinn/SpringBoot-Angular7-Online-Shopping-Store)：使用Spring Boot 2和Angular 7的全栈在线商店Web应用程序。
* [Vert.x Microservice Blueprint](https://github.com/sczyh30/vertx-blueprint-microservice)：Vert.x Microservice Blueprint是使用Vert.x开发的微商店微服务应用程序。
* [ECommerce Spring ReactJS](https://github.com/merikbest/ecommerce-spring-reactjs)：使用Spring Boot和React.js开发的电子商务项目。
* [Shopping Cart](https://github.com/shashirajraja/shopping-cart)：Java、JDBC、Servlets、JSP中的在线购物车电子商务网站项目。
* [Keyist Ecommerce](https://github.com/antkaynak/Keyist-Ecommerce)：一个由Spring Boot、Angular 10、Ngrx、OAuth2提供支持的简单电子商务网站。
* [ECommerce Microservices](https://github.com/hoangtien2k3/ecommerce-microservices)：微服务架构与电子商务项目系统。
* [E-Commerce](https://github.com/foysal-mahmud/E-BookShop----Spring-boot)：完整电子商务项目，使用Spring、Hibernate、Bootstrap和MySQL完成。

## 支付

* [Wallee Java SDK](https://github.com/wallee-payment/java-sdk)：Wallee Java库封装了Wallee API，该库方便你与各种服务(例如交易、帐户和订阅)进行交互。
* [PayPal](https://github.com/paypal/PayPal-Android-SDK)：PayPal Android SDK可以轻松地将PayPal付款添加到移动应用程序。
* [Adyen Java API](https://github.com/Adyen/adyen-java-api-library)：官方支持使用Adyen API的Java库。
* [Razorpay Java SDK](https://github.com/razorpay/razorpay-java)：Razorpay API的官方Java绑定。
* [Ping++ Java](https://github.com/PingPlusPlus/pingpp-java)：Ping++是为移动端应用以及PC网页量身打造的下一代支付系统。
* [Pay Spring Boot Starter](https://gitee.com/egzosn/pay-spring-boot-starter-parent)：Pay Spring Boot Starter是一个基于Spring Boot实现自动化配置的支付对接。

#### 微信支付

* [WxJava](https://github.com/binarywang/WxJava)：微信开发Java SDK，支持微信支付、开放平台、公众号、企业号/企业微信、小程序等的后端开发。
* [Jeepay](https://gitee.com/jeequan/jeepay)：Jeepay是一套适合互联网企业使用的开源支付系统，支持多渠道服务商和普通商户模式。
* [IJPay](https://gitee.com/javen205/IJPay)：IJPay封装了微信支付、QQ支付、支付宝支付、京东支付、银联支付、PayPal支付等常用的支付方式以及各种常用的接口。
* [WxPay SDK](https://github.com/YClimb/wxpay-sdk)：最新最全微信支付集成SDK，一行代码调用微信支付，包含基础支付功能。
* [Wechat Pay Java](https://github.com/wechatpay-apiv3/wechatpay-java)：微信支付API v3的官方Java SDK。
* [Payment Spring Boot](https://gitee.com/dromara/payment-spring-boot)：Java微信支付v3 Spring Boot Starter，支持微信优惠券，代金券、商家转账到零钱、公众号支付、微信小程序支付、电商收付通等全部微信支付功能API，由dromara社区开源。
* [WXPay SDK](https://github.com/jkrains/wxpay-sdk-v3)：微信支付v3版本的SDK，目前包含同步API和异步API。
* [WeChatPay HttpClient](https://github.com/wechatpay-apiv3/wechatpay-apache-httpclient)：微信支付API v3的Apache HttpClient扩展，实现了请求签名的生成和应答签名的验证。

#### 支付宝

* [Pay Java](https://gitee.com/egzosn/pay-java-parent)：全能第三方支付对接Java开发工具包。
* [Alipay](https://github.com/alipay/alipay-easysdk)：Alipay Easy SDK让你享受极简编程体验，快速访问支付宝开放平台开放的各项核心能力。
* [Pay SDK](https://github.com/Pay-Group/best-pay-sdk)：支付宝、微信支付SDK。
* [Alipay Java SDK](https://github.com/alipay/alipay-sdk-java-all)：支付宝开放平台Java SDK。
* [EasyPay](https://github.com/easy-pay/easy-pay)：一行代码解决支付宝和微信的二维码生成，支付回调、退款、H5支付等功能。
* [Android Pay](https://github.com/mayubao/Android-Pay)：支持微信和支付宝两种主流支付的集成库。
* [JPay](https://github.com/Javen205/JPay)：对微信App支付、支付宝App支付、银联App支付的二次封装，对外提供一个相对简单的接口以及支付结果的回调。
* [Pay](https://github.com/boyuanitsm/pay)：支付SDK集合重构，支持支付宝、微信支付、银联支付。
* [Alipay](https://github.com/ihaolin/alipay)：轻量的支付宝组件。

#### 支付平台

* [KillBill](https://github.com/killbill/killbill)：Kill Bill是一个开源的可编程平台，可让你构建自定义计费解决方案。
* [Roncoo Pay](https://gitee.com/roncoocom/roncoo-pay)：龙果支付系统是国内首款开源的互联网支付系统，拥有独立的账户体系、用户体系、支付接入体系、支付交易体系、对账清结算体系。
* [YunGouOS Pay SDK](https://gitee.com/YunGouOS/YunGouOS-PAY-SDK)：微信/支付宝官方服务商接口(支持个人、个体户、企业)签约开通，一行代码搞定所有支付。
* [XPay](https://github.com/Exrick/xpay)：XPay个人免签收款支付系统。
* [Vmq](https://github.com/szvone/Vmq)：V免签是基于Spring Boot 2.1.1实现的一套免签支付程序。
* [Payments Modernization Hub](https://github.com/RahulAutade2288/payments-modernization-hub)：这是为银行和金融科技组织设计的现代支付中心的参考实现。 

#### 支付网关

* [J2PAY](https://github.com/tranxactive/J2PAY)：J2Pay是一个用于Java的开源多网关支付处理库。
* [Braintree Java](https://github.com/braintree/braintree_java)：Braintree Java库提供对Braintree网关的集成访问。
* [DaxPay](https://gitee.com/dromara/dax-pay)：DaxPay是一套开源支付网关系统，已经对接支付宝、微信支付、云闪付相关的接口。

#### 银行卡/信用卡

* [BankCardUtils](https://github.com/nanchen2251/BankCardUtils)：根据银行卡号获取银行卡类型、银行名称和银行编码，自动格式化银行卡号、手机号、身份证号输入的工具类。
* [Java IBAN](https://github.com/barend/java-iban)：IBAN是一个用于处理国际银行帐号(IBAN)的小型Java库。
* [IBAN4j](https://github.com/arturmkrtchyan/iban4j)：IBAN4j是用于生成和验证国际银行帐号(IBAN ISO_13616)和企业标识符代码(BIC ISO_9362)的Java库。
* [Bank4j](https://github.com/inisos/bank4j)：生成ISO 20022 XML传输并提供IBAN和BIC验证。
* [JavaEMVReader](https://github.com/sasc999/javaemvreader)：用于读取和与EMV支付卡交互的Java库。
* [Magnetic Track Parser](https://github.com/sualeh/magnetictrackparser)：Magnetic Track Parser是一个Java库，可以解析银行发行的信用卡的磁道数据，例如从USB磁卡读卡器返回的数据。
* [Credit Card Number](https://github.com/sualeh/creditcardnumber)：Credit Card Number是一个Java库，可以提供银行发行的信用卡号的详细信息。
* [EMV NFC Paycard Enrollment](https://github.com/devnied/EMV-NFC-Paycard-Enrollment)：用于从NFC EMV信用卡读取和提取公共数据的Java库。
* [EMV BER TLV](https://github.com/binaryfoo/emv-bertlv)：用于解密EMV(芯片卡交易)中使用的BER TLV数据的库。
* [PaymentCardGenerator](https://github.com/kloverde/java-PaymentCardGenerator)：PaymentCardGenerator是一个用于测试支付卡处理系统的Java库。

## 云计算

#### SaaS平台

* [AWS SaaS Boost](https://github.com/awslabs/aws-saas-boost)：AWS SaaS Boost为组织提供即用型核心软件元素，以便在云中成功运行SaaS工作负载，由Amazon开源。
* [Compute Nest SaaS Boost](https://github.com/aliyun/alibabacloud-compute-nest-saas-boost)：计算巢SaaS Boost是由阿里云推出的一款开发工具和框架，旨在帮助(SaaS)开发者快速构建、部署、扩展和售卖SaaS应用程序。
* [Wemirr Platform](https://gitee.com/battcn/wemirr-platform)：优秀、简单、漂亮的开源SaaS、多租户云平台架构。

#### BaaS平台

* [Apache Usergrid](https://github.com/apache/usergrid)：Usergrid是一个基于RESTful API的用于Web和移动应用程序的多租户后端即服务堆栈，由Apigee开发。
* [Para](https://github.com/Erudika/para)：Para是一个可扩展的多租户后端服务器/框架，用于对象持久化和检索。
* [AipexBase](https://github.com/kuafuai/aipexbase)：AipexBase是由跨赴科技开源的AI原生BaaS平台。
* [BaasBox](https://github.com/baasbox/baasbox)：BaasBox是一个开源项目，旨在为移动和Web应用程序提供后端。
* [SwellRT](https://github.com/SwellRT/swellrt)：SwellRT是一个开源后端即服务，它提供预构建的功能来加速协作Web应用程序的开发。
* [Appwrite](https://github.com/appwrite/sdk-for-android)：Appwrite是一个用于开发Web、移动和Flutter应用程序的后端平台。
* [JavaBaas](https://gitee.com/javabaas/JavaBaas)：JavaBaas是基于Java语言开发的后台服务框架。
* [Divide](https://github.com/HiddenStage/divide)：Divide是一个开源的后端即服务。

#### PaaS平台

* [HZERO](https://gitee.com/open-hand/hzero)：HZERO是基于微服务架构开源免费的企业级PaaS平台，由上海汉得公司开发。
* [J2PaaS](https://gitee.com/j2paas/j2paas-framework)：J2PaaS是一个集成开发平台，以参数驱动为核心，为开发者提供可视化、组件化、低代码、拖拽式在线敏捷开发平台，由吉鼎科技开源。
* [Eclipse Dirigible](https://github.com/eclipse/dirigible)：Dirigible是一种高生产力PaaS，它提供了一个由预选执行引擎和内置Web开发工具组成的应用程序服务器，它也适合利用低代码/无代码技术来快速开发业务应用程序，由SAP开源。
* [Kalix](https://www.kalix.io/)：Kalix是一个PaaS平台，它抽象了事件驱动的微服务的复杂性，团队可以专注于构建应用程序背后的业务逻辑，由Lightbend开源。
* [XGVela](https://github.com/XGVela/XGVela)：XGVela是由中国移动主导发起的5G云原生PaaS平台开源项目。
* [Apache Stratos](https://github.com/apache/stratos)：Stratos包括多语言和环境支持，以及在多个IaaS运行时上运行的能力。

#### IaaS平台

* [Apache CloudStack](https://github.com/apache/cloudstack)：CloudStack是一款开源软件，旨在部署和管理大型虚拟机网络，是一种高可用性、高可扩展性的IaaS云计算平台，由Citrix开发。
* [Apache JClouds](https://github.com/apache/jclouds)：JClouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [Nimbus](https://github.com/nimbusproject/nimbus)：Nimbus是用于科学的云计算软件，由芝加哥大学开源。
* [ZStack](https://github.com/zstackio/zstack)：ZStack是开源IaaS软件，旨在实现数据中心自动化，通过API管理计算、存储和网络资源，由云轴科技开源。
* [Eucalyptus](https://github.com/eucalyptus/eucalyptus)：Eucalyptus是用于构建与Amazon Web Services兼容的私有云和混合云的开源软件，由加州大学圣塔芭芭拉分校开源。
* [OpenStack4j](https://github.com/openstack4j/openstack4j)：OpenStack4j是一个流式的OpenStack客户端，允许配置和控制OpenStack部署，华为开源。
* [JOSS](https://github.com/javaswift/joss)：JOSS是OpenStack Storage组件REST接口的Java客户端。

#### 仿真框架

* [CloudSim](https://github.com/Cloudslab/cloudsim)：CloudSim是一个云计算基础设施和服务的建模和仿真框架，由墨尔本大学开源。
* [PureEdgeSim](https://github.com/CharafeddineMechalikh/PureEdgeSim)：PureEdgeSim是用于云、边缘和雾计算环境性能评估的仿真框架。
* [CloudSimPlus](https://github.com/cloudsimplus/cloudsimplus)：CloudSim Plus是一个现代、最新、功能齐全且文档齐全的Java 17模拟框架，它易于使用和扩展，支持对云计算基础设施和应用服务进行建模、模拟和实验。
* [ColocationSim](https://github.com/pku-finelab/ColocationSim)：ColocationSim通过先进的模拟技术，解决了混合部署在线与离线作业在真实环境中测试所带来的高成本、高风险以及长周期问题，北京大学开源。
* [EdgeCloudSim](https://github.com/CagataySonmez/EdgeCloudSim)：EdgeCloudSim提供了一个专门针对边缘计算场景的模拟环境，可用于开展兼顾计算和网络资源的实验。

#### 边缘计算

* [Eclipse ioFog](https://github.com/eclipse-iofog/Agent)：ioFog是一个开源的边缘计算平台，它提供了一套用于管理和编排边缘设备的工具和框架，由IBM开源。
* [iFogSim](https://github.com/Cloudslab/iFogSim)：iFogSim用于物联网、边缘计算和雾计算环境中资源管理技术的建模和仿真，由墨尔本大学开源。

## 云服务SDK

* [Aliyun Java SDK](https://github.com/aliyun/aliyun-openapi-java-sdk)：阿里云Java SDK。
* [Azure Java SDK](https://github.com/Azure/azure-sdk-for-java)：Azure Java SDK。
* [Tencent SDK Java](https://github.com/TencentCloud/tencentcloud-sdk-java)：腾讯云API 3.0 Java SDK。
* [Volcengine Java SDK](https://github.com/volcengine/volcengine-java-sdk)：火山引擎Java SDK。
* [AWS Java SDK](https://github.com/aws/aws-sdk-java-v2)：AWS官方的Java SDK。
* [Huawei SDK Java](https://github.com/huaweicloud/huaweicloud-sdk-java-v3)：华为云Java SDK。
* [Google Cloud Java](https://github.com/googleapis/google-cloud-java)：适用于Java的Google Cloud客户端库。
* [Firebase Android](https://github.com/firebase/firebase-android-sdk)：Firebase安卓SDK。
* [OCI Java SDK](https://github.com/oracle/oci-java-sdk)：用于Java的Oracle云基础设施SDK。
* [BCE SDK Java](https://github.com/baidubce/bce-sdk-java)：百度云Java语言版SDK，可基于该SDK使用Java语言接入百度云的各项产品。
* [Microsoft Graph Java SDK](https://github.com/microsoftgraph/msgraph-sdk-java)：适用于Java的Microsoft Graph SDK。
* [JD Cloud SDK](https://github.com/jdcloud-api/jdcloud-sdk-java)：京东云开发者Java工具套件。
* [讯飞开放平台AI能力Java SDK](https://github.com/iFLYTEK-OP/websdk-java)：提供各种讯飞开放平台能力的Java SDK。
* [Luna Fans API](https://github.com/lunasaw/luna-fans-api)：Luna Fans API基于各个开放平台的API整合优化，大部分采用原生HTTP调用。

## 微信开发

* [Weixin SDK](https://github.com/borball/weixin-sdk)：Weixin SDK是对微信公众平台(订阅号、服务号、企业号、小程序)、微信开放平台和微信支付的Java版封装。
* [WxJava](https://github.com/binarywang/WxJava)：微信开发Java SDK，支持包括微信支付、开放平台、小程序、企业微信、公众号等的后端开发。
* [Gewechat](https://github.com/Devo919/Gewechat)：个人微信免费开源框架，支持二次开发、任意语言都可接入，REST API接入。
* [Weixin Java Tools](https://github.com/chanjarster/weixin-java-tools)：微信公众号、企业号Java SDK。
* [JFinal Weixin](https://gitee.com/jfinal/jfinal-weixin)：JFinal Weixin是基于JFinal的微信公众号极速开发SDK，只需浏览Demo代码即可进行极速开发。
* [Wafer Java Server SDK](https://github.com/tencentyun/wafer-java-server-sdk)：Wafer是腾讯云面向广大开发者提供的小程序开发全栈资源套件。
* [Java Wechaty](https://github.com/wechaty/java-wechaty)：Java Wechaty是一个用Kotlin编写的聊天机器人开发者对话式SDK。
* [FastBootWeixin](https://gitee.com/kingshine/FastBootWeixin)：基于Spring Boot的注解驱动式公众号极速开发框架，用注解重新定义公众号开发。
* [Weixin Popular](https://github.com/liyiorg/weixin-popular)：微信Java SDK(公众平台、开放平台、商户平台、服务商平台)。
* [WeiXin4j](https://github.com/foxinmy/weixin4j)：WeiXin4j是一个用Java编写针对微信开发的工具包。
* [WeiXin4j](https://gitee.com/jeecg/weixin4j)：微信和钉钉开发Java SDK，主要提供微信公众号、企业微信、钉钉、微信小程序、支付的Java封装，降低集成难度，由北京国炬公司开发。
* [WeChat4j](https://github.com/sword-org/wechat4j)：WeChat4j是一个微信开发框架。
* [WX Dump4j](https://github.com/xuchengsheng/wx-dump-4j)：WX Dump4j是一款基于Java开发的微信数据分析工具。
* [JeewxBoot](https://gitee.com/jeecg/jeewx-boot)：JeewxBoot是一款免费的Java微信管家平台，支持微信公众号、小程序、微信第三方平台、抽奖活动等，由北京国炬公司开源。
* [QYWX](https://github.com/shuaidd/qywx)：企业微信API封装。
* [Wechat](https://github.com/ihaolin/wechat)：轻量的微信公众号组件。
* [ItChat4j](https://github.com/yaphone/itchat4j)：ItChat4j提供了简单易用的API，可以很方便地对个人微信号进行扩展，实现自动回复，微信挂机机器人等。
* [WeChat API](https://github.com/hellokaton/wechat-api)：WeChat API是微信个人号的Java版本API，让个人号具备更多能力，提供方便的接口调用。
* [WeCOM SDK](https://gitee.com/felord/wecom-sdk)：WeCOM SDK是开源的企业微信开放API的Java实现。
* [FastWeixin](https://github.com/sd4324530/fastweixin)：FastWeixin可以简化微信公众平台服务端开发。
* [Wx API](https://github.com/niefy/wx-api)：Wx API是一个轻量级的公众号开发种子项目，可快速接入微信公众号管理功能。

## 推送SDK

* [MPush](https://github.com/mpusher/mpush)：MPush是一款开源实时消息推送系统。
* [Austin](https://gitee.com/zhongfucheng/austin)：Austin是统一的接口发送各种类型消息，对消息生命周期全链路追踪。
* [Dinger](https://github.com/AnswerAIL/dingtalk-spring-boot-starter)：Dinger(叮鸽)，Spring Boot集成钉钉/企业微信/飞书群机器人实现消息通知中间件。
* [MixPush](https://github.com/taoweiji/MixPush)：Android混合推送SDK，快速集成6个厂商推送，共享系统推送通道。
* [Capillary](https://github.com/google/capillary)：Capillary是一个库，用于简化从基于Java的应用服务器向Android客户端发送端到端加密推送消息的过程，由Google开源。
* [JPush API Java](https://github.com/jpush/jpush-api-java-client)：这是JPush REST API的Java版本封装开发包，由极光推送官方提供。
* [个推PUSH Java SDK](https://github.com/GetuiLaboratory/getui-pushapi-java-client-v2)：个推官方提供的推送服务端SDK，基于全新的REST API V2接口。
* [WxPusher](https://github.com/wxpusher/wxpusher-sdk-java)：WxPusher是一个轻量级企业消息推送平台，旨在提供企业内部沟通和协作的便捷解决方案。
* [Deliver](https://gitee.com/OS-Zero/deliver)：Deliver是一个面向企业的全面消息推送平台，旨在提供企业内部沟通和协作的便捷解决方案。
* [Message Gateway](https://github.com/openMF/message-gateway)：Message Gateway是Fineract提供商的推送消息服务，可以轻松地通过短信和电子邮件推送通知。
* [MEIZUPUSH](https://github.com/MEIZUPUSH/JavaSdk)：魅族开放平台PUSH系统Java版本SDK。
* [GoPush](https://gitee.com/openWolf/gopush)：GoPush是开源的分布式推送消息服务。

## 异常通知

* [Spring Boot Starter Calma](https://github.com/marvinSpring/spring-boot-starter-calma)：异常通知框架。
* [Prometheus Spring Boot Starter](https://gitee.com/ITEater/prometheus-spring-boot-starter)：管理异常通知的Spring Starter，实现了钉钉消息提醒与邮件提醒，同时加入了微服务的服务异常提醒。
* [HawkEye](https://gitee.com/liuhao3169/hawk-eye)：HawkEye通过监控Error级别的异常实现告警推送与日志记录。
* [Exception Notify](https://github.com/GuangYiDing/exception-notify)：Exception Notify是一个Spring Boot Starter组件，用于捕获Spring Boot应用中未处理的异常，并通过钉钉、飞书或企业微信实时告警通知。

## APN

* [Pushy](https://github.com/jchambers/pushy)：Pushy是一个用于发送APN(iOS、macOS和Safari)推送通知的Java库。
* [Java Apns](https://github.com/notnoop/java-apns)：Java Apns是Apple推送通知服务(APN)的Java客户端，该库旨在为Apple服务器提供高度可扩展的接口，同时保持简单和模块化。
* [DBay APNS Java](https://github.com/RamosLi/dbay-apns-for-java)：APNS的高性能Java客户端。
* [APNS HTTP2](https://github.com/CleverTap/apns-http2)：用于使用Apple的新HTTP/2 API通过APNS发送通知的Java库。
* [Apns4j](https://github.com/teaey/apns4j)：Apple推送通知服务Java实现，阿里开源。
* [JavaAPNS JDK16](https://github.com/fernandospr/javapns-jdk16)：适用于Java的Apple推送通知服务提供程序。
* [AeroGear UnifiedPush Server](https://github.com/aerogear/aerogear-unifiedpush-server)：AeroGear UnifiedPush Server允许向不同的移动平台发送推送通知。

## Webhook

* [Svix](https://github.com/svix/svix-webhooks)：Svix让开发者可以轻松发送Webhook。
* [Discord Webhook](https://github.com/MinnDevelopment/discord-webhooks)：为Discord Webhook API提供易于使用的绑定。
* [Slack WebHook](https://github.com/gpedro/slack-webhook)：Java的Slack WebHook集成。

## API&客户端

* [REST Countries](https://github.com/apilayer/restcountries)：REST Countries服务通过REST API提供有关国家/地区的通用信息。
* [Twitch4j](https://github.com/twitch4j/twitch4j)：模块化异步/同步/响应式Twitch API客户端/IRC客户端。
* [Google Maps Services Java](https://github.com/googlemaps/google-maps-services-java)：Google Maps API Web服务的Java客户端库。
* [Apple App Store Server Java Library](https://github.com/apple/app-store-server-library-java)：App Store Server API和App Store Server Notifications的Java服务器库。
* [Spring Social Google](https://github.com/spring-social/spring-social-google)：Spring Social扩展，具有连接支持和Google API绑定。
* [Social SDK](https://github.com/belerweb/social-sdk)：Social SDK是一个集成新浪微博开放平台、QQ互联、腾讯微博开发平台、微信公众平台等社交平台的接口的Java库。
* [Evernote SDK Java](https://github.com/Evernote/evernote-sdk-java)：该SDK包含用于从Java应用调用Evernote Cloud API的包装代码。
* [Bilibili API](https://github.com/czp3009/bilibili-api)：该项目提供Bilibili API的JVM调用。
* [Steamworks4j](https://github.com/code-disaster/steamworks4j)：一个用于访问Steamworks API的薄Java包装器。
* [DiscordIPC](https://github.com/jagrosh/DiscordIPC)：通过IPC本地连接到Discord客户端，以获得部分RPC功能。
* [Artifactory Java Client](https://github.com/jfrog/artifactory-client-java)：Artifactory Java客户端在你的Java代码中提供简单而强大的Artifactory连接和管理。
* [Cloud Foundry Java Client](https://github.com/cloudfoundry/cf-java-client)：CF Java Client项目是一个用于与Cloud Foundry实例交互的Java语言绑定。

#### Twitter

* [Twitter4J](https://github.com/Twitter4J/Twitter4J)：Twitter4J是Twitter API的100%纯Java库，没有外部依赖。
* [JTwitter](https://github.com/winterstein/JTwitter)：JTwitter是一个强大且易于使用的Twitter库。
* [HBC](https://github.com/twitter/hbc)：HBC是用于使用Twitter标准Streaming API的Java HTTP客户端，由Twitter开源。
* [Twittered](https://github.com/redouane59/twittered)：面向Java开发人员的Twitter API客户端。
* [Spring Social](https://github.com/spring-attic/spring-social)：Spring Social是Spring框架的扩展，可帮助你将应用程序与Facebook和Twitter等SaaS提供商连接起来。
* [Twitter API Java Client](https://github.com/xdevplatform/twitter-api-java-sdk)：Java版Twitter API客户端库。
* [Twitter Kit Android](https://github.com/twitter-archive/twitter-kit-android)：Twitter Kit是一个多模块Twitter SDK，包括TweetComposer、TwitterCore和TweetUi。
* [Twitter4s](https://github.com/DanielaSfregola/twitter4s)：用于Twitter REST和Streaming API的异步非阻塞Scala客户端。

#### Facebook

* [RestFB](https://github.com/restfb/restfb)：RestFB是一个纯Java Facebook Graph API客户端，没有外部依赖。
* [Facebook4J](https://github.com/roundrop/facebook4j)：Facebook4J是Java语言的Facebook Graph API绑定库。
* [Facebook Business SDK](https://github.com/facebook/facebook-java-business-sdk)：用于Meta营销API的Java SDK。

#### Instagram

* [Instagram4j](https://github.com/instagram4j/instagram4j)：使用OkHttpClient作为Instagram私有API的Java包装器。
* [JInstagram](https://github.com/sachin-handiekar/jInstagram)：Instagram API的Java库。
* [Instagram Java Scraper](https://github.com/postaddictme/instagram-java-scraper)：Instagram Java Scraper可以获取Instagram帐户信息、照片、视频和评论。
* [EasyInsta](https://github.com/ErrorxCode/EasyInsta)：Instagram私有API的Java库，以及Instagram4j的封装器。

#### Telegram

* [TelegramApi](https://github.com/rubenlagus/TelegramApi)：实现Telegram API来创建Telegram客户端的Java库。
* [Kotlogram](https://github.com/badoualy/kotlogram)：易于使用且直接的Kotlin和Java绑定Telegram API。
* [Telegram API](https://github.com/telegram-s/telegram-api-old)：该库允许你对Telegram进行RPC调用。
* [Telegram4J](https://github.com/Telegram4J/Telegram4J)：使用Java 17编写的Telegram MTProto API的响应式Java库。
* [Telegram Server](https://github.com/aykutalparslan/Telegram-Server)：Telegram Server是Telegram API的一个开源服务器端实现。

#### Whatsapp

* [Cobalt](https://github.com/Auties00/Cobalt)：适用于Java和Kotlin的独立非官方全功能Whatsapp Web和移动API。
* [Whatsapp Business Java API](https://github.com/Bindambc/whatsapp-business-java-api)：此SDK实现了官方Whatsapp Cloud API和WhatsApp Business Management API。

#### Slack

* [Slack Java SDK](https://github.com/slackapi/java-slack-sdk)：Slack Java SDK以Java惯用方式支持Slack平台。
* [Slack Client](https://github.com/HubSpot/slack-client)：Slack Web API的异步HTTP客户端，由HubSpot开源。
* [Simple Slack API](https://github.com/Itiviti/simple-slack-api)：该库允许应用程序连接到Slack以从任何通道接收和发送消息。
* [Flower](https://github.com/PositiveTechnologies/flower)：Flower库是一组用于存储库、任务跟踪器和消息传递系统的通用协议，其中包括与Jira、TFS、GitLab、GitHub和Exchange等最常见协议的集成。
* [Slack API](https://github.com/allbegray/slack-api)：Slack Web API、传入Webhook、Slackbot远程控制、RTM API的Java客户端。
* [Slack Scala Client](https://github.com/slack-scala-client/slack-scala-client)：用于与Slack API和实时消息传递接口交互的Scala库。
* [RoboSlack](https://github.com/palantir/roboslack)：RoboSlack是一个Java 8 API，它负责处理身份验证以及将消息作为传入的Webhook服务发送到Slack的各个方面，由Palantir开源。

#### Reddit

* [JRAW](https://github.com/mattbdean/JRAW)：JRAW是JVM的Reddit API包装器。
* [Reddit4J](https://github.com/masecla22/Reddit4J)：Reddit4J是一个全面覆盖Reddit API的库。
* [JReddit](https://github.com/jReddit/jReddit)：JReddit是用Java编写的Reddit API的包装器。

#### TikTok

* [DyJava](https://gitee.com/sxwdmjy/dy-java)：DyJava是一款功能强大的抖音Java开发工具包，支持多种抖音开发功能模块的后端开发，包括但不限于移动/网站应用、开放平台、抖店和小程序等。
* [TikTok4j](https://github.com/cyrus07424/tiktok4j)：Java版非官方TikTok/DouYin API。
* [TikTok Live Java](https://github.com/jwdeveloper/TikTokLiveJava)：用于从TikTok LIVE实时接收直播事件(评论、礼物等)。

#### Spotify

* [Librespot Java](https://github.com/librespot-org/librespot-java)：最新的开源Spotify客户端。
* [Spotify Web API Java](https://github.com/spotify-web-api-java/spotify-web-api-java)：这是Spotify Web API的Java包装器/客户端。
* [Java Spotify API](https://github.com/LabyStudio/java-spotify-api)：Java API，可以直接从本地Spotify进程访问Spotify播放数据，无需任何认证。

#### Notion

* [Notion SDK JVM](https://github.com/seratch/notion-sdk-jvm)：这是适用于任何JVM语言用户的Notion API SDK。
* [Notion SDK](https://github.com/notionsdk/notion-sdk-kotlin-old)：非官方Notion API包装器，用Kotlin编写，可在Java中使用。
* [KLibNotion](https://github.com/BoD/klibnotion)：适用于Kotlin、Java等的Notion API客户端库。

#### JIRA

* [JIRA Client](https://github.com/bobcarroll/jira-client)：JIRA Client是一个简单的Java JIRA REST客户端。
* [JiraRestClient](https://github.com/micromata/JiraRestClient)：JIRA REST API的简单Java客户端。
* [Jira REST Java Client](https://bitbucket.org/atlassian/jira-rest-java-client)：Jira REST Java Client是一个Java库，它允许你使用新的REST API轻松地与任何Jira Server 4.2+实例对话。

#### Jenkins

* [Jenkins Java Client](https://github.com/jenkinsci/java-client-api)：适用于Java的Jenkins API客户端。
* [Jenkins REST](https://github.com/cdancy/jenkins-rest)：Java客户端，基于JClouds构建，用于与Jenkins REST API配合使用。

#### Riot

* [Riot API Java](https://github.com/taycaldwell/riot-api-java)：一个易于使用的Java Riot Games API包装器。
* [Orianna](https://github.com/meraki-analytics/orianna)：Riot Games英雄联盟API的Java框架。
* [R4J](https://github.com/stelar7/R4J)：包含每个Riot游戏API的Java库。

#### TheMovieDb

* [TheMovieDB API](https://github.com/c-eg/themoviedbapi)：该库为TMdB提供的JSON API提供了一个Java包装器，TMdB是一个开放的电影和电视内容数据库。
* [The Movie DB API](https://github.com/Omertron/api-themoviedb)：TheMovieDb.org网站的API。
* [TMDB Java](https://github.com/UweTrottmann/tmdb-java)：TMDB Java是使用Retrofit 2的TMDB v3 API的非官方包装器。

#### TeamSpeak

* [TeamSpeak 3 Java API](https://github.com/TheHolyWaffle/TeamSpeak-3-Java-API)：TeamSpeak 3服务器查询API的Java包装器。(语言通话SDK)
* [TS3J](https://github.com/Manevolent/ts3j)：TS3J是逆向工程TeamSpeak 3完整服务器/客户端协议的开源实现。

#### Mastodon

* [Mastodon4j](https://github.com/sys1yagi/mastodon4j)：Mastodon是Java和Kotlin的Mastodon客户端。
* [BigBone](https://github.com/PattaFeuFeu/bigbone)：BigBone是适用于Java和Kotlin的Mastodon客户端库。
* [Twitter Scale Mastodon](https://github.com/redplanetlabs/twitter-scale-mastodon)：该项目是Mastodon实例的生产级实现，可扩展至Twitter规模(5亿用户、700平均扇出、非平衡社交图谱、每秒7000篇帖子)。

## Docker客户端

* [Docker Java](https://github.com/docker-java/docker-java)：Java Docker官方客户端。
* [Spotify Docker Client](https://github.com/spotify/docker-client)：这是一个用Java编写的Docker客户端，之前被用于Spotify的许多关键生产系统。
* [Docker Java API](https://github.com/amihaiemil/docker-java-api)：另一个轻量级的Docker客户端库。
* [Docker Client](https://github.com/gesellix/docker-client)：用Groovy编写的JVM的Docker HTTP客户端。
* [Jocker](https://github.com/ndeloof/jocker)：Jocker是用于访问Docker API的Docker客户端库。

## Consul客户端

* [Consul](https://github.com/Ecwid/consul-api)：Consul的Java客户端。
* [Spring Cloud Consul](https://github.com/spring-cloud/spring-cloud-consul)：Spring Cloud Consul为Spring Boot应用程序提供Consul集成。
* [Consul Java](https://github.com/rickfast/consul-client)：Consul HTTP API的Java客户端。
* [Consultant](https://github.com/Magnetme/consultant)：Consultant是一个Java库，允许从Consul存储中检索其配置。

## Kubernetes客户端

* [Kubernetes Java](https://github.com/kubernetes-client/java)：Kubernetes官方Java客户端库。
* [Kubernetes & OpenShift Client](https://github.com/fabric8io/kubernetes-client)：该客户端通过流式的DSL提供对完整Kubernetes和OpenShift REST API的访问。
* [Spring Cloud Kubernetes](https://github.com/spring-cloud/spring-cloud-kubernetes)：Spring Cloud Kubernetes提供了消费Kubernetes原生服务的Spring Cloud通用接口实现。
* [YAKC](https://github.com/manusa/yakc)：YAKC是Kubernetes API的较低级别Java REST客户端。
* [Amdatu Kubernetes](https://bitbucket.org/amdatulabs/amdatu-kubernetes/src/master/)：Amdatu Kubernetes是Kubernetes的客户端库。
* [OpenShift Java](https://github.com/openshift/openshift-restclient-java)：基于Kubernetes的OpenShift版本3架构的Java REST客户端。
* [MicroBean Helm](https://github.com/microbean/microbean-helm)：MicroBean Helm项目让你可以使用Java的Helm服务器端组件。
* [Helm Java](https://github.com/manusa/helm-java)：使用此客户端库直接从Java运行Helm命令，而无需Helm CLI。

## Web3

* [Hyperledger Quilt](https://github.com/hyperledger-archives/quilt)：Quilt是Interledger协议的Java实现。
* [Web3signer](https://github.com/Consensys/web3signer)：Web3Signer是一种开源签名服务，能够使用存储在外部保管库中或加密在磁盘上的私钥在多个平台(Ethereum1和2、Filecoin)上进行签名。
* [Universal Resolver](https://github.com/decentralized-identity/universal-resolver)：通用解析器实现和驱动程序。
* [OmniJ](https://github.com/OmniLayer/OmniJ)：Omni Layer的Java/JVM实现，Omni Layer是一个基于比特币区块链构建的开源、完全去中心化的资产创建平台。
* [Convex](https://github.com/Convex-Dev/convex)：Convex是价值互联网的去中心化网络和执行引擎。
* [Waltid Identity](https://github.com/walt-id/waltid-identity)：多平台库、强大的API和易于使用的白标应用程序来构建身份和钱包解决方案。

#### 区块链

* [AntChain](https://github.com/AntChainOpenLabs)：蚂蚁链是蚂蚁集团自主研发的具备高性能、强隐私保护的区块链技术平台。
* [JD Chain](https://gitee.com/jdchain/jdchain)：京东区块链是一个企业级的区块链框架系统，具有简洁、易用、可扩展和高性能的特点。
* [Chains](https://github.com/ethereum-lists/chains)：为链提供元数据。
* [WeIdentity](https://github.com/WeBankBlockchain/WeIdentity)：WeIdentity是一套分布式多中心的技术解决方案，可承载实体对象的现实身份与链上身份的可信映射、以及实现实体对象之间安全的访问授权与数据交换，由微众银行开源。
* [TRON](https://github.com/tronprotocol/java-tron)：TRON是一个致力于构建真正去中心化的互联网基础设施的项目。
* [TianXuanChain](https://github.com/TianXuan-Chain/thanos-chain)：TianXuanChain是网易自主研发区块链底层技术。
* [Corda](https://github.com/corda/corda)：Corda是一个开源区块链项目，由R3开发。
* [NEM](https://github.com/NemProject/nem)：NEM是一个去中心化的区块链平台。
* [MD BlockChain](https://gitee.com/tianyalei/md_blockchain)：MD开源Java区块链平台，可做联盟链、私链使用，不适用于公链。
* [Nxt](https://www.jelurida.com/nxt)：Nxt是一个开源区块链平台，也是第一个完全依赖权益证明共识协议的平台，由Jelurida开发。
* [Nuls](https://github.com/nuls-io/nuls-v1)：Nuls是一个全球性的区块链开源项目，是一个高度可定制的模块化区块链基础设施。
* [Manuscript](https://github.com/chainbase-labs/manuscript-core)：Manuscript不仅仅是一个语言规范，更是一个协议、框架和工具包，旨在简化和统一数据访问和处理方法。
* [Aion](https://github.com/aionnetwork/aion)：Aion是一个多层区块链网络。
* [Blockj](https://gitee.com/blackfox/blockj)：Blockj是Java实现的一个简易区块链项目，包括加密工具、钱包、P2P传输、区块同步、网络共识等基础实现。
* [J2Chain](https://gitee.com/ld/J2Chain)：J2Chain是Java开发区块链的开源项目。
* [SimBlock](https://github.com/dsg-titech/simblock)：SimBlock是一款开源区块链网络模拟器，由东京工业大学开源。
* [Ethlance](https://github.com/district0x/ethlance)：Ethlance是第一个完全基于以太坊区块链构建的就业市场平台。
* [RChain](https://github.com/rchain/rchain)：RChain是一个去中心化、经济、抗审查的公共计算基础设施和区块链。
* [Alephium](https://github.com/alephium/alephium)：Alephium是一个分片区块链，旨在使可编程货币具有可扩展性和安全性。
* [FingerNFT](https://github.com/fingerchar/fingernft)：FingerNFT是一款开源NFT市场，兼容Opensea、Rarible。
* [MultiChain](https://www.multichain.com/)：Multichain提供了一个用Java编写的区块链解决方案，主要用于构建私有链和联盟链。
* [Scorex](https://github.com/hyperledger-labs/Scorex)：Scorex 2是模块化区块链框架，采用Scala语言，允许对各种设计进行自由和无限制的实验。
* [Ultra](https://onultra.io/)：Ultra是一个区块链平台，其核心组件用Java编写，专注于去中心化应用的构建和部署。
* [Waves](https://github.com/wavesplatform/Waves)：Waves是一个基于社区的去中心化开源技术堆栈，用于构建可扩展、用户友好的应用程序。
* [Token Core](https://github.com/consenlabs/token-core-android)：TokenCore是一个区块链库，提供了相对一致的API，允许你同时管理钱包并在BTC、ETH和EOS链上签署交易。
* [Apache Tuweni](https://github.com/apache/incubator-tuweni)：Tuweni是一组库和其他工具，可帮助使用Java和其他JVM语言开发区块链和其他去中心化软件，由ConsenSys开源。
* [Emerald Dshackle](https://github.com/emeraldpay/dshackle)：Emerald Dshackle是区块链API的容错负载均衡器，由EmeraldPay开源。
* [WeBASE](https://github.com/WeBankBlockchain/WeBASE)：WeBASE是在区块链应用和FISCO BCOS节点之间搭建的一套通用组件，由微众银行开源。
* [WeCross](https://github.com/WeBankBlockchain/WeCross)：WeCross是由微众银行开源的区块链跨链协作平台，致力于促进跨行业、机构和地域的跨区块链信任传递和商业合作。
* [RepChain](https://gitee.com/BTAJL/repchain)：RepChain是第一款采用响应式编程实现的自主可控的区块链基础组件，由广州软件应用技术研究院、中国科学院软件所、贵阳信息技术研究院等共同研发。
* [Wuhan Chain](https://github.com/BSN-DDC/wuhanchain)：武汉链官方使用Solidity语言进行合约的开发，目前支持JSON-RPC API和WebSocket。
* [Universa](https://github.com/UniversaBlockchain/universa)：Universa网络、节点、客户端和API。
* [Sun Network](https://github.com/tronprotocol/sun-network)：Sun Network是一个致力于构建TRON区块链可信去中心化侧链的项目。
* [COTI Node](https://github.com/coti-io/coti-node)：COTI是第一个基于DAG的链协议，针对企业和稳定币进行了优化。
* [Minima](https://github.com/minima-global/Minima)：Minima是一个新的区块链，强调每个用户都能够运行完整的节点。
* [Semux](https://github.com/semuxproject/semux-core)：Semux是一个实验性高性能区块链平台，为去中心化应用程序提供支持。
* [Apollo](https://github.com/ApolloFoundation/Apollo)：该仓库包含Apollo区块链平台的核心类和Apollo区块链组件的主要可执行文件。
* [TokenCore](https://github.com/GalaxySciTech/tokencore)：Tokencore是区块链钱包后端的核心组件，支持多种区块链地址生成和离线签名。
* [PoR](https://github.com/BitgetLimited/proof-of-reserves)：Bitget推出PoR，以提高用户资产的安全性和透明度。
* [PIXRA](https://github.com/dodufish/PIXRA)：PIXRA是一个通过先进的人工智能和MCP技术数字化现实资产，并通过区块链上链其价值的平台。
* [Drones Privacy Ledger](https://github.com/drsaikrishnathota/drones-privacy-ledger)：一种可在本地运行的参考实现，使用哈希链账本和ECDSA签名验证来保护无人机飞行日志和操作员ID。
* [Blockchain Java](https://github.com/wangweiX/blockchain-java)：Java简化的区块链实现。

#### 以太坊

* [Web3j](https://github.com/web3j/web3j)：Web3j是一个轻量级、高度模块化、响应式、类型安全的Java和Android库，用于处理智能合约并与以太坊网络上的客户端集成。
* [Ethereumj](https://github.com/ethereum/ethereumj)：EthereumJ是以太坊协议的纯Java实现。
* [Besu](https://github.com/hyperledger/besu)：Besu是一个兼容MainNet、用Java编写的以太坊客户端。
* [Teku](https://github.com/Consensys/teku)：Teku是一个用Java编写的开源以太坊共识客户端，包含完整的信标节点和验证器客户端实现。
* [KEthereum](https://github.com/komputing/KEthereum)：KEthereum是以太坊的Kotlin库。
* [FundRequest](https://github.com/FundRequest/platform)：FundRequest是一个去中心化市场。
* [AlphaWallet](https://github.com/AlphaWallet/alpha-wallet-android)：AlphaWallet是一个开源可编程区块链应用程序平台。
* [Eventeum](https://github.com/eventeum/eventeum)：Eventeum是一个以太坊事件监听器，用于连接你的智能合约事件和后端微服务。
* [Presto Ethereum Connector](https://github.com/xiaoyao1991/presto-ethereum)：释放以太坊区块链上Presto交互式SQL查询的强大功能。
* [ETHWallet](https://github.com/DwyaneQ/ETHWallet)：一款模仿imToken实现的ETH钱包。
* [Securify](https://github.com/eth-sri/securify)：Securify是由以太坊基金会和ChainSecurity支持的以太坊智能合约安全扫描器。
* [BitcoinWallet](https://github.com/terryjiao/BitcoinWallet)：比特币和以太坊钱包。
* [EtherJar](https://github.com/emeraldpay/etherjar)：适用于以太坊区块链的框架无关的模块化Java 17+集成库。

#### 比特币

* [Bitcoinj](https://github.com/bitcoinj/bitcoinj)：Bitcoinj库是比特币协议的Java实现，它允许它维护钱包并发送/接收交易，而不需要Bitcoin Core的本地副本。
* [Bisq](https://github.com/bisq-network/bisq)：Bisq是一种安全、私密且去中心化的方式，可以将比特币兑换成国家货币和其他数字资产。
* [Eclair](https://github.com/ACINQ/eclair)：Eclair是闪电网络的Scala实现。
* [LightningJ](https://github.com/lightningj-org/lightningj)：LightningJ旨在简化Java开发者对现有Lightning节点实现的集成。
* [Lightning KMP](https://github.com/ACINQ/lightning-kmp)：Kotlin中Lightning网络的实现。
* [Bitcoin Wallet](https://github.com/bitcoin-wallet/bitcoin-wallet)：适用于Android设备的比特币钱包应用程序。
* [Huobi Java SDK](https://github.com/HuobiRDCenter/huobi_Java)：火币Java SDK v3，可以使用此SDK查询所有市场数据、进行交易和管理你的账户。
* [IRI](https://github.com/iotaledger/iri)：IRI是一款开源Java软件，可在IOTA主网和Devnet上运行。
* [Bitcoin-S](https://github.com/bitcoin-s/bitcoin-s)：Bitcoin-S是一组针对JVM的松散耦合的加密货币库。
* [Sparrow](https://github.com/sparrowwallet/sparrow)：Sparrow是一款现代桌面比特币钱包应用程序，支持大多数硬件钱包，并基于PSBT等通用标准构建，强调透明度和可用性。
* [Drongo](https://github.com/sparrowwallet/drongo)：Drongo是一个Java比特币库，主要为支持Sparrow Wallet而构建。
* [BitHub](https://github.com/signalapp/BitHub)：BitHub是一项服务，它会为每次向GitHub仓库提交的内容自动支付一定比例的比特币资金，由Open Whisper Systems开发。
* [DiabloMiner](https://github.com/Diablo-D3/DiabloMiner)：比特币OpenCL矿工。
* [CoinGecko Java](https://github.com/Philipinho/CoinGecko-Java)：CoinGecko API的Java包装器。
* [Ergo](https://github.com/ergoplatform/ergo)：Ergo是一种基于工作量证明的加密货币协议，旨在为新型货币、点对点交互、信任最小化的金融工具和衍生品提供安全的环境。
* [Thunder](https://github.com/blockchain/thunder)：闪电网络P2P协议的钱包/节点实现。
* [XDAGJ](https://github.com/XDagger/xdagj)：XDAGJ是XDAG在Java中的实现。
* [Snowblossom](https://github.com/snowblossomcoin/snowblossom)：Snowblossom是一种简单的加密货币。
* [MultiBit](https://github.com/Multibit-Legacy/multibit)：MultiBit是一个简化支付验证比特币桌面客户端。
* [Phoenix](https://github.com/ACINQ/phoenix)：Phoenix是由ACINQ开发的比特币钱包，可让你通过闪电网络安全地发送和接收比特币。
* [Lighthouse](https://github.com/vinumeris/lighthouse)：Lighthouse是一款去中心化的点对点众筹应用，它利用了比特币协议的智能合约功能。
* [BOP Bitcoin Server](https://github.com/bitsofproof/supernode)：BOP Bitcoin Server是一个企业级的比特币协议实现。
* [Mercury](https://github.com/mappum/mercury)：Mercury是一个支持无需信任的跨链交易的多币钱包。
* [ConsensusJ](https://github.com/ConsensusJ/consensusj)：JVM和Android的比特币组件。 
* [Bitcoin KMP](https://github.com/ACINQ/bitcoin-kmp)：Kotlin多平台比特币库。

#### 交易所

* [XChange](https://github.com/knowm/XChange)：XChange是一个Java库，提供简单一致的API，用于与60多个比特币和其他加密货币交易所进行交互，为交易和访问市场数据提供一致的接口。
* [Crypto Exchange](https://github.com/jammy928/CoinExchange_CryptoExchange_Java)：基于Spring Cloud微服务开发，可用于数字货币交易所的搭建和二次开发。
* [Coin Trader](https://github.com/timolson/cointrader)：Coin Trader是一个基于Java的加密货币交易后端。
* [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot)：Cassandre交易机器人框架允许你在多个加密货币交易所快速创建和执行交易策略。
* [Bex](https://github.com/gazbert/bxbot)：Bex是一个用Java编写的简单比特币交易机器人。
* [GitBitEX](https://github.com/gitbitex/gitbitex-new)：GitBitEX是一个开源的加密货币交易所。
* [Haveno](https://github.com/haveno-dex/haveno)：Haveno是一个开源平台，用于将Monero兑换为美元、欧元和英镑等法定货币或BTC、ETH和BCH等其他加密货币。
* [Orko](https://github.com/gruelbox/orko)：Orko是一款自托管Web应用程序，它提供统一的仪表板来控制众多加密货币交易所。
* [OPEX](https://github.com/opexdev/core)：Core是OPEX项目基于Kotlin开发的加密货币交易和撮合引擎。
* [BITISAN](https://github.com/bitisanop/CryptoExchange_TradingPlatform_CoinExchange)：BITISAN交易所支持多种数字资产的交易，涵盖加密货币、代币化资产以及其他数字化资产。
* [Reactive Crypto](https://github.com/namjug-kim/reactive-crypto)：用于加密货币交易的Kotlin/Java库。
* [Arbitrader](https://github.com/agonyforge/arbitrader)：Arbitrader是一个在两个不同的加密货币交易所之间寻找交易机会并执行自动低风险交易的程序。
* [Bitget Open API V3 SDK](https://github.com/BitgetLimited/v3-bitget-api-sdk)：Bitget是世界领先的数字资产交易平台。
* [CoinExchange](https://gitee.com/cexchange/CoinExchange)：开源数字货币合约交易所，基于Java开发的比特币交易所、BTC交易所、ETH交易所、数字货币交易所、交易平台、撮合交易引擎。
* [Bitrade](https://github.com/SevenEX/bitrade-parent)：七喜是一个基于ZTUO开源代码进行大量优化的数字货币交易系统。
* [TradeBot](https://github.com/markusaksli/TradeBot)：TradeBot是一款使用Binance API的加密货币交易机器人。
* [Coinc](https://github.com/newVkDing2/coinc)：Coinc是一个数字货币交易系统，基于Java开发的比特币交易所。
* [CoinEx](https://github.com/coinexcom/coinex_exchange_api)：CoinEx API开放且简洁，确保你可以自行构建交易工具，实现更有效的交易策略。
* [Binance Trader](https://github.com/unterstein/binance-trader)：Binance.com上的加密货币实验机器人。
* [Binance Trading Bot](https://github.com/yonathan95/BinanceTradingBot)：Binance Trading Bot是一个加密货币交易机器人，使用币安交易所期货市场。
* [Java Binance API](https://github.com/joaopsilva/binance-java-api)：Java Binance API是一个轻量级的Java库，用于与币安API交互，提供完整的API覆盖，支持同步和异步请求，以及使用WebSockets进行事件流。
* [AiTrader](https://github.com/sanzol-tech/ai-trader)：币安期货的交易信号与加密货币交易工具。
* [TxBits](https://github.com/txbits/txbits)：TxBits是一个开源的比特币和加密货币交易所。
* [OpenNFT](https://github.com/shengjian-tech/opennft)：开源NFT发行交易平台。
* [OKX Trading](https://github.com/ralph-wren/okx-trading)：OKX Trading是一款基于Spring Boot开发的智能加密货币交易策略回测系统，集成了策略实盘交易、AI策略生成、历史数据回测、策略评价等功能。

#### 区块链SDK

* [Fabric SDK Java](https://github.com/hyperledger/fabric-sdk-java)：该项目提供了一个用于与Hyperledger Fabric区块链网络交互的低级API。
* [EOSIO](https://github.com/EOSIO/eosio-java)：EOSIO SDK是一个使用EOSIO RPC API与基于EOSIO的区块链集成的API。
* [Cardano](https://github.com/bloxbean/cardano-client-lib)：Java中的Cardano客户端库。
* [Hashgraph Java SDK](https://github.com/hashgraph/hedera-sdk-java)：适用于Java的Hedera Hashgraph SDK。
* [Sol4k](https://github.com/sol4k/sol4k)：Sol4k是Solana的Kotlin客户端，可与Java或任何其他JVM语言以及Android一起使用。
* [Solanaj](https://github.com/p2p-org/solanaj)：Solanaj是一个用于使用Solana RPC API与Solana区块链集成的API。
* [Java Stellar SDK](https://github.com/lightsail-network/java-stellar-sdk)：Java Stellar SDK库提供了用于构建交易并连接到Horizon和Soroban-RPC服务器的API。
* [Server Blockchain SDK](https://github.com/OmniOneID/did-blockchain-sdk-server)：Server Blockchain SDK提供与区块链网络交互和调用智能合约的SDK。
* [TON4j](https://github.com/neodix42/ton4j)：用于与TON区块链交互的Java库和包装器。

#### 智能合约

* [RskJ](https://github.com/rsksmart/rskj)：RskJ是Rootstock节点的Java实现。
* [Daml](https://github.com/digital-asset/daml)：Daml是一种开源智能合约语言，用于在安全且注重隐私的运行时构建面向未来的分布式应用程序。
* [Neow3j](https://github.com/neow3j/neow3j)：Neow3j是一个开发工具包，提供简单可靠的工具来使用Java平台构建Neo dApp和智能合约。
* [Hiero Consensus Node](https://github.com/hiero-ledger/hiero-consensus-node)：Hiero Consensus Node是Hiero区块链网络中的核心组件，负责参与网络共识、验证交易并维护分布式账本。
* [SmartJ](https://github.com/signum-network/signum-smartj)：Signum的Java智能合约。
* [Java4Ever](https://github.com/deplant/java4ever-framework)：Java4Ever是一个功能丰富的框架，用于智能合约开发、测试和访问TVM兼容的区块链，例如Everscale、Venom、GOSH等。
* [Hyperledger Fabric Chaincode Java](https://github.com/hyperledger/fabric-chaincode-java)：Hyperledger Fabric Contract和Chaincode的Java实现。

## 金融

* [Portfolio](https://github.com/portfolio-performance/portfolio)：Portfolio是一个开源程序，用于根据实时加权回报率和内部回报率计算整个投资组合(跨不同投资组合和账户)的绩效。
* [CDM](https://github.com/finos/common-domain-model)：CDM是金融产品、这些产品的交易以及这些交易的生命周期事件的模型，由金融科技开源基金会FINOS托管。
* [DROP](https://github.com/lakshmiDRIP/DROP)：DROP实现的库针对固定收益、信贷、商品、股票、外汇和结构性产品内部和之间的分析/风险、交易成本分析、资产负债分析、资本、风险敞口和保证金分析、估值调整分析和投资组合构建分析。
* [FinMath Library](https://github.com/finmath/finmath-lib)：FinMath Library库提供了与数学金融相关但适用于其他领域的方法的(JVM)实现。
* [Stripe](https://github.com/stripe/stripe-java)：Stripe API的Java库。
* [Parity](https://github.com/paritytrading/parity)：Parity是一个用于交易场所的开源软件平台，它可用于运行金融市场、开发算法交易代理或研究市场微观结构。
* [Prowide](https://github.com/prowide/prowide-core)：Prowide Core是一个用于管理SWIFT FIN消息的开源Java框架。
* [Sailfish](https://github.com/exactpro/sailfish-core)：Sailfish是一个测试自动化工具，其主要目的是测试分布式交易平台和市场数据交付系统中的双向消息流。
* [JavaMoney](https://github.com/JavaMoney/javamoney-lib)：JavaMoney提供基于JSR 354(兼容实现)构建的扩展和库。
* [Bateman](https://github.com/fearofcode/bateman)：Bateman是一个非常简单的交易系统，旨在筛选美国股票市场的子集。
* [XS2A](https://github.com/adorsys/xs2a)：XS2A是一个完全符合PSD2标准的XS2A接口，支持所有强制和大多数可选的PSD2 XS2A流程。
* [SubMicroTrading](https://github.com/Richard-Rose/SubMicroTrading)：SubMicroTrading是一个高度并发的基于组件的算法交易框架。
* [Accounting](https://github.com/Nick-Triller/accounting)：Accounting是一个用Java编写的内存中复式记账组件。
* [IBC](https://github.com/IbcAlpha/IBC)：IBC可以自动化运行盈透证券交易者工作站和网关的许多方面。
* [Univocity Trader](https://github.com/uniVocity/univocity-trader)：Univocity Trader是一个开源交易框架，旨在使任何具有基本编程技能的人都能有效地创建和测试用于买卖股票、加密货币或任何其他类型工具的交易算法。
* [Eclipse Tradista](https://github.com/eclipse-tradista/tradista)：Tradista是一种轻量级的金融风险管理解决方案，使你能够使用单一工具管理你的日常财务和风险管理任务。
* [Trading Backtest](https://github.com/lukstei/trading-backtest)：这是一个用Java编写的通用轻量级股票回溯测试引擎。
* [QD](https://github.com/devexperts/QD)：QD是Devexperts开源的一个高性能金融数据处理和分发框架，专门为金融行业设计，用于处理市场数据、交易消息和其他金融数据流。

#### 金融API

* [Plaid Java](https://github.com/plaid/plaid-java)：Plaid API的Java绑定。
* [Infoway](https://github.com/infoway-api/realtime-market-data-api)：Infoway提供毫秒级金融行情数据API。
* [Finance Quotes API](https://github.com/sstrickx/yahoofinance-api)：该库提供了一些方法，可以轻松地与Yahoo Finance API进行通信，它允许你请求股票的详细信息、一些统计数据和历史报价。
* [AllTick Real-time Quotation APIs](https://github.com/alltick/alltick-realtime-forex-crypto-stock-tick-finance-websocket-api)：易用且用户友好的开源股票API、香港股票API、美股API、上海和深圳股票API、A股API、外汇API、商品贵金属API、加密货币API及其他实时市场数据。
* [Alpaca Java](https://github.com/Petersoj/alpaca-java)：这是Alpaca API的Java实现，Alpaca让你可以使用算法进行交易、与应用程序连接并通过免佣金的股票交易API构建服务。
* [Quandl4J](https://github.com/jimmoores/quandl4j)：Quandl是一个通过开放REST API提供数百万个免费数据集的来源，涵盖金融、经济、社会和国家数据。
* [AlphaVantage4j](https://github.com/patriques82/alphavantage4j)：该库实现了Alpha Vantage提供的免费API的包装器。

#### 银行API

* [Apache Fineract](https://github.com/apache/fineract)：Fineract是一个具有开放API的成熟平台，可为金融机构提供可靠、强大且价格实惠的核心银行解决方案，为全球30亿银行服务不足和无银行账户的人口提供服务。
* [OBP API](https://github.com/OpenBankProject/OBP-API)：OBP是一个面向银行的开源API，使账户持有人能够使用更广泛的应用程序和服务与银行进行交互。
* [Open Banking Gateway](https://github.com/adorsys/open-banking-gateway)：提供RESTful API、工具、适配器和连接器，用于透明访问开放银行API(适用于支持PSD2和XS2A以及HBCI/FinTS的银行)。
* [Open Banking](https://github.com/wso2/financial-open-banking)：WSO2开放银行加速器是一系列技术的集合，可提高开放银行合规性的速度并降低其复杂性。
* [JBanking](https://github.com/marcwrobel/jbanking)：JBanking是一个帮助开发银行功能的实用程序库，专注但不限于欧洲银行业。
* [BankingPortal API](https://github.com/abhi9720/BankingPortal-API)：使用Spring Boot和Spring Security的银行门户REST API。
* [EBICS Java Client](https://github.com/ebics-java/ebics-java-client)：该库允许使用EBICS与银行互动。

#### 量化交易

* [Ta4j](https://github.com/ta4j/ta4j)：Ta4j是一个用于技术分析的开源Java库，它提供了创建、评估和执行交易策略的基本组件。
* [Northstar](https://gitee.com/dromara/northstar)：这是一个面向程序员的专业级量化交易软件，用于期货、股票、外汇、炒币等多种交易场景，实现自动交易，由dromara社区开源。
* [Redtorch](https://github.com/sun0x00/redtorch)：Redtorch是基于Kotlin(Java)语言开发的开源量化交易程序开发框架。
* [HFTFramework](https://github.com/javifalces/HFTFramework)：HFTFramework包含一个使用Java和Python开发的高频交易框架。 
* [Kite Connect](https://github.com/zerodha/javakiteconnect)：Kite Connect是一组类似REST的API，它公开了构建完整的投资和交易平台所需的许多功能。
* [QuantComponents](https://github.com/lsgro/quantcomponents)：用于量化金融和算法交易的免费Java组件。
* [JQuantLib](https://github.com/frgomes/jquantlib)：JQuantLib是一个免费、开源、全面的量化金融框架，100%用Java编写。
* [Strata](https://github.com/OpenGamma/Strata)：Strata是OpenGamma的开源分析和市场风险库。
* [TA-Lib](https://github.com/TA-Lib/ta-lib)：TA-Lib是用于市场分析的多平台工具。
* [Marketcetera](https://github.com/marketcetera/marketcetera)：Marketcetera是一个开源算法交易平台，旨在支持跨计算集群的低延迟、高交易量交易。
* [Trading](https://github.com/gvolpe/trading)：用Scala 3编写的交易应用程序。
* [InteractiveBrokers Algo Trading API](https://github.com/rediar/InteractiveBrokers-Algo-Trading-API)：该Java/MySQL框架实现了算法交易的交互经纪商API。
* [Codera Quant](https://github.com/dsinyakov/quant)：Codera Quant是一个Java框架，用于通过交互经纪商TWS API或其他经纪商API进行算法交易策略的开发、执行和回测。
* [SumZeroTrading](https://github.com/FueledByChai/SumZeroTrading)：SumZeroTrading是一个全面的基于Java的算法交易框架。
* [JQuant](https://github.com/eryk/JQuant)：JQuant是使用Java语言编写的量化开发工具箱。
* [Coinbase Pro](https://github.com/irufus/gdax-java)：基于Java的Coinbase Pro API包装。

#### FIX引擎

* [QuickFIX/J](https://github.com/quickfix-j/quickfixj)：QuickFIX/J是适用于FIX协议的全功能消息传递引擎。
* [Philadelphia](https://github.com/paritytrading/philadelphia)：Philadelphia是一个用于JVM的快速FIX协议库。
* [FIXIO](https://github.com/kpavlov/fixio)：该API旨在取代高频交易场景中众所周知的QuickFIX/J。
* [CoralFIX](https://www.coralblocks.com/index.php/category/coralfix/)：CoralFIX是一款功能齐全、超低延迟、无垃圾的FIX引擎，具有非常直观的API。
* [Chronicle FIX](https://chronicle.software/fix-engine/)：微秒级延迟，多资产FIX引擎，旨在满足最严苛的交易应用需求。
* [Artio](https://github.com/artiofix/artio)：Artio是一个高性能的FIX和FIXP网关。
* [Nanofix](https://github.com/LMAX-Exchange/nanofix)：用于测试FIX服务器的FIX客户端，由英国外汇交易公司LMAX开发。

#### 订单匹配引擎

* [Exchange Core](https://github.com/exchange-core/exchange-core)：Exchange Core是一个基于LMAX Disruptor、Eclipse Collections、Real Logic Agrona、OpenHFT Chronicle-Wire、LZ4 Java和Adaptive Radix Trees的开源市场交易核心。
* [CoinTossX](https://github.com/dharmeshsing/CoinTossX)：基于JSE规则的低延迟高吞吐量匹配引擎。
* [Match Trade](https://gitee.com/flying-cattle/match-trade)：Match Trade是高效的交易所撮合引擎，采用伦敦外汇交易所LMAX开源的Disruptor框架，分布式内存存取、以及原子性操作。
* [CoralME](https://github.com/coralblocks/CoralME)：CoralME是一种订单簿数据结构，它根据价格时间优先级来匹配订单。
* [Order Book Matching Engine](https://github.com/philipperemy/Order-Book-Matching-Engine)：证券交易所订单簿匹配引擎。
* [Chronicle Matching Engine](https://chronicle.software/matching-engine/)：Chronicle Matching Engine是具有弹性且可扩展的交换解决方案的支柱。

#### 信用卡数据交换

* [jPOS](https://github.com/jpos/jPOS)：jPOS是一个开源的Java平台，用于构建和部署高度可扩展、事务处理、基于ISO-8583标准的金融交易处理系统。
* [JReactive 8583](https://github.com/kpavlov/jreactive-8583)：适用于ISO8583和Netty的Kotlin/Java客户端和服务器。
* [ISO8583 Message Client](https://github.com/imohsenb/ISO8583-Message-Client-java)：一个轻量级ISO8583库，适用于Java和Android，基于构建器模式。
* [j8583](https://bitbucket.org/chochos/j8583)：j8583是ISO8583协议的Java实现。
* [Adelbs ISO8583](https://github.com/adelbs/ISO8583)：这是一个用于测试ISO8583协议的GUI工具，同时也是一个Java库。

#### 金融信息交换

* [Prowide ISO 20022](https://github.com/prowide/prowide-iso20022)：Prowide ISO 20022是一个用于管理ISO 20022消息的开源Java框架。
* [Finaplo](https://www.paymentcomponents.com/)：Finaplo SDK是一个Java库，用于构建、解析、验证和翻译金融消息。

#### 货币

* [Joda Money](https://github.com/JodaOrg/joda-money)：Joda-Money提供了一个类库来存储大量资金。
* [Money](https://github.com/eriksencosta/money)：该库提供了强大而简单的API，使货币计算变得简单。
* [Moneta](https://github.com/JavaMoney/jsr354-ri)：Moneta是JSR 354货币API的参考实现。
* [LibNumberText](https://github.com/Numbertext/libnumbertext)：C++、Java、JavaScript和Python中的数字到数字名称和金钱文本转换库。

#### FinTS

* [HBCI4Java](https://github.com/hbci4j/hbci4java)：基于Java的FinTS协议实现，支持所有功能(chipTAN、pushTAN、HHD、SEPA、PSD2)。
* [Hibiscus](https://github.com/willuhn/hibiscus)：适用于Linux、Windows和MacOS的免费家庭银行业务分析。

#### 电子发票

* [NFE](https://github.com/wmixvideo/nfe)：Java中的电子发票。
* [Mustangproject](https://github.com/ZUGFeRD/mustangproject)：开源Java电子发票库、验证器和工具。
* [Java_NFe](https://github.com/Samuel-Oliveira/Java_NFe)：用于使用NFe/NFCe WebService的Java库。
* [RSHK JSIFENLib](https://github.com/roshkadev/rshk-jsifenlib)：RSHK JSIFENLib是一个开源库，无需外部依赖，通过Java与SIFEN(全国综合电子发票系统)进行交互。
* [Billy](https://github.com/premium-minds/billy)：Billy是一个应用程序计费库，为应用程序提供创建、管理和存储计费工件(例如发票和贷方票据)的能力。
* [Cyclops](https://github.com/icclab/cyclops)：Cyclops是一款全面的动态评级和计费解决方案，适用于云服务，由苏黎世应用科学大学开源。
* [Mustang](https://github.com/ZUGFeRD/mustangproject)：Mustang使你能够读取、写入和验证(例如重新计算)机器可读的发票、订单或交货通知。
* [Konik](https://github.com/konik-io/konik)：用于创建、读取和验证符合ZUGFeRD标准的发票的库。
* [Pb UBL](https://github.com/phax/ph-ubl)：用于读写UBL 2.0、2.1、2.2、2.3和2.4文档的Java库。
* [Phase4](https://github.com/phax/phase4)：Phase4是一个可嵌入的轻量级Java库，用于发送和接收不同配置文件的AS4消息。
* [Oxalis](https://github.com/OxalisCommunity/oxalis)：Oxalis是AS4规范的领先开源软件实现。
* [Phoss SMP](https://github.com/phax/phoss-smp)：Phoss SMP是一款功能齐全的SMP服务器，支持Peppol SMP 1.x规范以及OASIS BDXR SMP 1.0和2.0规范。
* [OpenAS2](https://github.com/OpenAS2/OpenAs2App)：OpenAS2是EDIINT AS2标准的基于Java的实现。
* [AS2 Lib](https://github.com/phax/as2-lib)：通用Java AS2库、Servlet和服务器。
* [Holodeck B2B](https://github.com/holodeck-b2b/Holodeck-B2B)：Holodeck B2B是一款AS4系统间消息传递解决方案，它实现了ebMS3及其AS4配置文件的OASIS规范。

## JavaCard

* [Sun/Oracle JavaCard SDK](https://github.com/martinpaljak/oracle_javacard_sdks)：Java Card开发工具包是一套工具，用于设计Java Card技术的实现并根据Java Card API规范开发小应用程序。
* [GPPro](https://github.com/martinpaljak/GlobalPlatformPro)：GPPro允许在兼容的JavaCard智能卡上加载和管理小程序。
* [Ant JavaCard](https://github.com/martinpaljak/ant-javacard)：Ant JavaCard是一个易于使用的Ant任务，用于构建JavaCard Classic小程序(2.1.1至3.1.0)。
* [JCardSim](https://github.com/licel/jcardsim)：JCardSim是Java Card的开源模拟器。
* [Gradle JavaCard](https://github.com/fidesmo/gradle-javacard)：该插件允许将编译的class文件转换为转换后的存档格式，这些文件可用于安装在支持SUN/Oracle JavaCard技术的智能卡和SIM卡上。
* [Keycard](https://github.com/status-im/status-keycard)：Keycard是在JavaCard 3.0.4+上运行的BIP-32 HD钱包的实现。
* [SmartPGP](https://github.com/github-af/SmartPGP)：SmartPGP是JavaCard中OpenPGP卡3.4规范的免费开源实现。
* [Java Card OpenPGP Card](https://github.com/jderuiter/javacard-openpgpcard)：这是OpenPGP智能卡规范的Java Card实现。
* [IsoApplet](https://github.com/philipWendland/IsoApplet)：IsoApplet是Java Card智能卡的开源小程序，其目的是与OpenSC一起在现代智能卡上执行公钥加密。
* [JCAlgTest](https://github.com/crocs-muni/JCAlgTest)：基于JavaCard平台的某类智能卡所支持的密码算法的自动化测试工具，由马萨里克大学开源。
* [PivApplet](https://github.com/arekinath/PivApplet)：适用于JavaCard 2.2.2和3.0.4+的PIV小程序，具有完整的ECDSA/ECDH支持。
* [JCMathLib](https://github.com/OpenCryptoProject/JCMathLib)：JCMathLib是JavaCard平台的开源库，旨在实现标准JavaCard API中不可用的低级加密计算。
* [OpenJavaCard Tools](https://github.com/OpenJavaCard/openjavacard-tools)：该项目是一个用于JavaCard开发和配置的工具包。
* [EMV Card Simulator](https://github.com/mrautio/emv-card-simulator)：用于支付终端功能和安全测试/模糊测试的EMV卡的JavaCard实现。
* [OpenJavaCard Libraries](https://github.com/OpenJavaCard/openjavacard-libraries)：这是一组用于JavaCard环境的可重用库。
* [OpenJavaCard NDEF](https://github.com/OpenJavaCard/openjavacard-ndef)：JavaCard的NDEF标签实现。
* [OpenEMV](https://github.com/JavaCardOS/OpenEMV)：OpenEMV是EMV标准的Java Card实现。
* [Gauss Key Card](https://github.com/darconeous/gauss-key-card)：Gauss Key Card是一个Java Card小程序，它实现了Tesla Key Card协议的最小工作子集。

#### 智能卡

* [Eclipse Keypop](https://github.com/eclipse-keypop)：Keypop提供一套灵活的API来处理通用智能卡读卡器操作，同时还集成了针对特定卡技术(如Calypso标准)量身定制的专用API。
* [Apdu4j](https://github.com/martinpaljak/apdu4j)：Apdu4j是一些命令行工具和有用的Java类库，用于通过JSR 268处理智能卡和智能卡读卡器。
* [SIMTester](https://github.com/srlabs/SIMTester)：测试SIM卡安全性的工具。
* [JNASmartCardIO](https://github.com/jnasmartcardio/jnasmartcardio)：javax.smartcardio API的重新实现，它允许你从Java内部与智能卡(在APDU级别)进行通信。
* [JMultiCard](https://github.com/ctt-gob-es/jmulticard)：100% Java智能卡访问抽象层。
* [SmartCard IO](https://github.com/intarsys/smartcard-io)：该项目包含PC/SC包装器和智能卡抽象层。
* [JFreesteel](https://github.com/grakic/jfreesteel)：JFreesteel是一个可重复使用的开源Java库，用于读取塞尔维亚电子身份证的公共数据。

## 物联网

这里包含物联网领域相关软件，MQTT、Modbus等。

#### 物联网框架

* [Physical Web](https://github.com/google/physical-web)：Physical Web旨在将Web的超能力(URL)扩展到日常物理对象，由Google开源。
* [Eclipse Milo](https://github.com/eclipse/milo)：Milo是OPC UA的开源实现，它包括高性能堆栈(通道、序列化、数据结构、安全性)以及构建在堆栈顶部的客户端和服务器SDK。
* [UA Java](https://github.com/OPCFoundation/UA-Java-Legacy)：UA Java是一个OPC UA堆栈参考实现。
* [Apache PLC4X](https://github.com/apache/plc4x)：PLC4X致力于创建一组库，用于以统一的方式与工业级可编程逻辑控制器(PLC)进行通信。
* [CrowdOS](https://github.com/crowdosNWPU/CrowdOS)：CrowdOS是一个适用于众包和移动众包感知的通用操作系统，可以同时处理多种类型的众包问题，由西北工业大学开发。
* [HslCommunication](https://github.com/dathlin/HslCommunicationJavaDemo)：一款非常热门的工业物联网通讯插件。
* [Eclipse Californium](https://github.com/eclipse-californium/californium)：Californium是RFC7252(物联网云服务的约束应用协议)的Java实现，由博世软件开源。
* [Eclipse Leshan](https://github.com/eclipse-leshan/leshan)：Leshan是OMA轻量级M2M服务器和客户端Java实现。
* [Apache StreamPipes](https://github.com/apache/streampipes)：StreamPipes是一个自助物联网工具箱，使非技术用户能够连接、分析和探索物联网数据流，由FZI研究中心开源。
* [Eclipse HawkBit](https://github.com/eclipse/hawkbit)：Eclipse HawkBit 是一个开源的物联网设备固件更新(FOTA)和管理平台，由博世软件开源。
* [OpenMUC](https://www.openmuc.org/openmuc/)：OpenMUC是一个基于Java和OSGi的软件框架，可简化定制监控、日志记录和控制系统的开发，由弗劳恩霍夫太阳能系统研究所开发。
* [S7Connector](https://github.com/s7connector/s7connector)：用于Java的S7 PLC连接器。
* [Eclipse Tahu](https://github.com/eclipse/tahu)：Tahu提供各种语言和各种设备的客户端库和参考实现。
* [HA-Bridge](https://github.com/bwssytems/ha-bridge)：将Philips Hue API模拟到其他家庭自动化网关，例如Amazon Echo/Dot或支持Philips Hue本地网络发现的其他系统。
* [OpenHAB Add-ons](https://github.com/openhab/openhab-addons)：该库包含在OpenHAB核心API之上实现的官方附加组件集。
* [Azure IoT SDK](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [AWS IoT Device SDK Java](https://github.com/aws/aws-iot-device-sdk-java)：AWS IoT Device SDK使Java开发人员能够通过MQTT或基于WebSocket协议的MQTT访问AWS IoT平台。
* [Eclipse Sparkplug](https://github.com/eclipse-sparkplug/sparkplug)：Sparkplug为网络边缘网关或支持本机MQTT的终端设备与Sparkplug主机应用程序如何在MQTT基础设施内进行双向通信提供了开放且免费的规范。
* [Eclipse Arrowhead](https://github.com/eclipse-arrowhead/core-java-spring)：Arrowhead是一个用于构建自动化和数字化解决方案的框架和实施平台。
* [Sentilo](https://github.com/sentilo/sentilo)：Sentilo是一个架构，它隔离了为利用“城市生成”的信息而开发的应用程序和部署在城市各处以收集和广播该信息的传感器层。
* [WSO2 IoT Server](https://github.com/wso2/product-iots)：WSO2 IoT Server是一个完整的解决方案，使设备制造商和企业能够连接和管理其设备、构建应用程序、管理事件、保护设备和数据以及以可扩展的方式可视化传感器数据。
* [MyController](https://github.com/mycontroller-org/mycontroller-v1-legacy)：MyController是一个适用于家庭、办公室或任何地方的物联网自动化控制器。
* [ESPlorer](https://github.com/4refr0nt/ESPlorer)：面向ESP8266开发人员的集成开发环境。
* [Eclipse AAS4J](https://github.com/eclipse-aas4j/aas4j)：AAS4J实现了Asset Administration Shell(AAS)的规范，例如基于AAS规范的元模型、子模型、序列化和反序列化模块、验证器和转换库。
* [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN)：GRASSMARLIN提供工业控制系统以及监控和数据采集(SCADA)网络的IP网络态势感知，以支持网络安全，由美国国家安全局网络安全局开源。
* [Apache Edgent](https://github.com/apache/incubator-retired-edgent)：Edgent是一种适用于边缘设备的开源编程模型和运行时，使你能够分析设备上的数据和事件，由Pivotal开源。
* [Eclipse sensiNact](https://eclipse-sensinact.readthedocs.io/en/latest/index.html)：Eclipse sensiNact是一个专注于物联网的横向平台，尤其适用于各种智慧城市和智能家居应用。

#### 物联网平台

* [SmartThings](https://www.samsung.com/us/smartthings/)：SmartThings是一款免费应用程序，它使用Wi-Fi连接基于Matter协议的智能设备，无论其制造商是哪家公司，这是三星的产品。
* [ThingsBoard](https://github.com/thingsboard/thingsboard)：ThingsBoard是一个开源物联网平台，用于数据收集、处理、可视化和设备管理。
* [OpenRemote](https://github.com/openremote/openremote)：OpenRemote是一个直观、用户友好的100%开源物联网平台。
* [Ignition](https://inductiveautomation.com/)：Ignition是一个强大的集成开发环境，包含你创建几乎所有类型的工业软件应用所需的一切。
* [JetLinks](https://gitee.com/jetlinks/jetlinks-community)：JetLinks是一个开箱即用，可二次开发的企业级物联网基础平台。
* [FastBee](https://gitee.com/beecue/fastbee)：FastBee开源物联网平台，简单易用，更适合中小企业和个人学习使用，由曲靖蜂信科技公司开发。
* [Syhthems](https://github.com/ehaut/syhthems-platform)：Syhthems是一个开源的物联网平台项目，由河南工业大学开源。
* [SiteWhere](https://github.com/sitewhere/sitewhere)：SiteWhere是一个具有工业实力的开源物联网应用支持平台，可促进大规模物联网设备数据的摄取、存储、处理和集成。
* [IoT DC3](https://gitee.com/pnoker/iot-dc3)：IoT DC3是一个基于Spring Cloud的开源、分布式的IoT平台，用于快速开发物联网项目和管理物联设备。
* [ThingLinks](https://gitee.com/mqttsnet/thinglinks)：ThingLinks物联网一体化平台，高性能、高吞吐量、高扩展性。
* [Enjoy IoT](https://gitee.com/open-enjoy/enjoy-iot)：Enjoy IoT是一个开源物联网平台。
* [IoT Ucy](https://gitee.com/iteaj/iot)：IoT Ucy是使用Java开发的物联网网络中间件，支持UDP、TCP、串口通讯等底层协议和HTTP、MQTT、WebSocket、Modbus(TCP，RTU)、PLC、DTU等上层协议。
* [IoTLink](https://gitee.com/sdyunze/iotlink)：IoTLink是一个基于Spring Boot、Vue、Mybatis、RabbitMQ、MySQL、Redis等开发的物联网平台，支持对物联网卡、物联网模组以及卡+模组的融合管理。
* [MzMedia](https://gitee.com/mzmedia/mz-media)：MzMedia开源视频联动物联网平台，简单易用，更适合中小企业和个人学习使用。
* [Zeus IoT](https://github.com/zmops/zeus-iot)：Zeus IoT是一个分布式物联网采集、分析、存储平台，是全球第一个基于Zabbix二次开发的物联网开源平台。
* [EasyAIoT](https://gitee.com/soaring-xiongkulu/easyaiot)：支持上千种垂直场景，支持AI模型定制化和AI算法定制化开发。
* [Groza](https://github.com/IoT-Technology/Groza)：开源物联网平台-物联网解决方案的设备管理、数据收集、处理。
* [ByteCub](https://gitee.com/byte-cub/bytecub)：基于Java 8，Spring Boot、ElasticSearch、Redis、MySQL的物联网通讯平台。
* [DeviceHive](https://github.com/devicehive/devicehive-java-server)：DeviceHive可以将任何联网设备变成物联网的一部分。
* [Freedomotic](https://github.com/freedomotic/freedomotic)：Freedomotic是一个开源、灵活、安全的IoT应用程序框架，可用于构建和管理现代智能空间。
* [OpenIita](https://gitee.com/open-iita/iotkit-parent)：铱塔智联开源平台是一个开源的物联网基础开发平台，提供了物联网及相关业务开发的常见基础功能，能帮助你快速搭建自己的物联网相关业务平台。
* [Scada LTS](https://github.com/SCADA-LTS/Scada-LTS)：Scada LTS是一个基于Web的开源多平台解决方案，用于构建你自己的SCADA(监控和数据采集)系统。
* [Aura Tower](https://github.com/blumek/aura-tower)：Aura Tower是一个开源项目，旨在通过直观的仪表板控制和监控物联网设备。
* [OpenIoT](https://github.com/OpenIotOrg/openiot)：OpenIoT为物联网构建一个新颖的开源平台，该平台包含一些独特的功能，例如能够按照基于云/实用程序的范式组合非平凡的物联网服务，由瑞士苏黎世联邦理工学院、希腊信息技术与通信研究所开源。
* [KCloud Platform IoT](https://github.com/KouShenhai/KCloud-Platform-IoT)：KCloud Platform IoT是一个企业级微服务架构的IoT云平台。
* [Frost IoT](https://github.com/footprintcat/frost-iot)：支持轻量化快速接入的IoT设备统一接入平台。
* [IoTOS](https://gitee.com/chinaiot/iotos)：IoTOS是基于Spring Boot、Vue开源IoTCard系统，企业私域管理与运营综合解决方案。
* [BudIot](https://gitee.com/budwk/budiot)：BudIot是一个开源、企业级的物联网平台，它集成了设备管理、协议解析、消息订阅、场景联动等一系列物联网核心能力。
* [Frog Smart Agriculture](https://gitee.com/nealtsiao/frog-smart-agriculture)：青蛙智慧农业平台，支持物联网设备、农业设备对接。
* [OPENIITA](https://gitee.com/open-iita/iotkitparent)：OPENIITA是铱塔智联旗下一个开源的物联网开源平台。
* [NexIoT](https://gitee.com/NexIoT/Universal-IoT-Java)：NexIoT IoT是一款基于Java技术栈构建的零代码侵入企业级物联网平台，具备高内聚低耦合，零代码侵入。
* [Beaver IoT](https://github.com/Milesight-IoT/beaver-iot)：Beaver IoT是一个开源平台，旨在快速直观地开发物联网应用程序。
* [IOT Tree](https://github.com/bambooww/iot-tree)：IOT Tree是一套面向物联网接入、数据规范化、人机交互展示、调度控制和数据利用的服务软件系统。
* [IntelliConnect](https://github.com/ruanrongman/IntelliConnect)：IntelliConnect是一个由创万联社区开发的智慧物联网平台内核。
* [SmartCity](https://gitee.com/genchuan/genchuan-smart-city)：智慧城市一网统管平台是由福建亘川科技公司开发的城市治理核心系统。

#### 智能家居

* [OpenHAB](https://github.com/openhab/openhab-core)：OpenHAB是一个开源、与技术无关的家庭自动化平台，作为智能家居的中心运行。
* [Eclipse SmartHome](https://github.com/eclipse-archived/smarthome)：SmartHome旨在创建一个构建智能家居解决方案的框架，其重点是异构环境，即各种协议和标准集成。
* [Amazon Echo Bridge](https://github.com/armzilla/amazon-echo-ha-bridge)：Amazon Echo Bridge允许你快速模拟Phillips Hue桥，从而能够将Amazon Echo无缝集成到各种家庭自动化系统中。
* [Khome](https://github.com/dennisschroeder/khome)：Khome是一个用Kotlin编写的Home Assistant智能家居自动化库。
* [SmartApplianceEnabler](https://github.com/camueller/SmartApplianceEnabler)：SmartApplianceEnabler可将普通的家用电器转变为智能的、可远程控制的家电，并使其能够参与家庭能源管理，尤其是与光伏太阳能发电相结合。
* [Arcus](https://github.com/arcus-smart-home/arcusplatform)：Arcus是一个开源的家庭自动化与控制系统。

#### 数字孪生

* [Eclipse Ditto](https://github.com/eclipse-ditto/ditto)：Ditto是物联网中的一项技术，实现了一种称为数字孪生的软件模式，由博世软件开源。
* [Eclipse Vorto](https://github.com/eclipse/vorto)：Vorto提供了一种用于描述IoT数字孪生模型和接口的语言。
* [World Avatar](https://github.com/cambridge-cares/TheWorldAvatar)：基于知识图谱的世界数字孪生，由新加坡剑桥高级研究与教育中心开源。
* [Eclipse BaSyx](https://github.com/eclipse-basyx)：BaSyx是下一代自动化的开源平台，它实现了工业4.0平台定义的关键概念，例如作为标准化数字孪生的资产管理shell。

#### 物联网网关

* [AWS IoT Greengrass](https://aws.amazon.com/greengrass/)：AWS IoT Greengrass是一种开源边缘运行时系统和云服务，用于构建、部署和管理设备软件。
* [Eclipse Kura](https://github.com/eclipse-kura/kura)：Kura是一个多功能软件框架，旨在增强你的边缘设备的性能。
* [Eclipse Kapua](https://github.com/eclipse/kapua)：Kapua是一个模块化平台，提供管理物联网网关和智能边缘设备所需的服务。
* [Eclipse Hono](https://github.com/eclipse-hono/hono)：Hono提供统一(远程)服务接口，用于将大量IoT设备连接到(云)后端。
* [Automation Gateway](https://github.com/vogler75/automation-gateway)：OPC UA网关允许你通过MQTT或GraphQL(HTTP)访问OPC UA值。
* [HiveMQ Edge](https://github.com/hivemq/hivemq-edge)：HiveMQ Edge是一个MQTT网关，可实现OT设备和IT系统之间的互操作性。
* [IBoot](https://gitee.com/iteaj/iboot)：IBoot是基于Java 1.8、Spring Boot 2.7、Netty等框架开发的物联网网关。
* [IOTGate](https://gitee.com/willbeahero/IOTGate)：Java版基于Netty的物联网高并发智能网关。
* [Gateway4Java](https://github.com/ganweisoft/Gateway4Java)：Gateway是一个高性能、集中式的各种设备插件通信和调度模块。

#### MQTT服务器

* [HiveMQ](https://github.com/hivemq/hivemq-community-edition)：HiveMQ是一个基于Java的开源MQTT代理，完全支持MQTT 3.x和MQTT 5。
* [Moquette](https://github.com/moquette-io/moquette)：Moquette的目标是成为符合MQTT标准的Broker，代理支持QoS 0、QoS 1和QoS 2。
* [BifroMQ](https://github.com/baidu/bifromq)：BifroMQ是一种高性能、分布式MQTT代理实现，可无缝集成原生多租户支持，由百度开源。
* [WeEvent](https://github.com/WeBankBlockchain/WeEvent)：WeEvent是一套分布式事件驱动架构，实现了可信、可靠、高效的跨机构、跨平台事件通知机制，由微众银行开源。
* [Akiro](https://www.akiroio.com/)：Akiro是一款高扩展性的MQTT Broker，支持超过2000万个活跃MQTT连接，每秒发送超过100万条消息。
* [JoramMQ](https://scalagent.com/mqtt/)：JoramMQ基于OW2联盟发布的开源JORAM产品构建，并由ScalAgent DT维护。
* [Waterstream](https://waterstream.io/product/)：Waterstream是一个功能齐全的MQTT代理，通过原生Kafka消费者和生产者在任何与Kafka兼容的平台上运行。
* [ActiveMQ Artemis](https://github.com/apache/activemq-artemis)：ActiveMQ Artemis是ActiveMQ的下一代消息代理。
* [Mica MQTT](https://gitee.com/dromara/mica-mqtt)：Mica MQTT是低延迟、高性能的MQTT物联网组件。
* [SMQTT](https://gitee.com/quickmsg/mqtt-cluster)：SMQTT是一款高性能、高吞吐量、高扩展性的物联网MQTT集群Broker。
* [MqttWk](https://github.com/Wizzercn/MqttWk)：MqttWk是由Netty实现的高并发高可用MQTT服务Broker。
* [JMQTT](https://github.com/Cicizz/jmqtt)：JMQTT是一个MQTT Broker，由Java和Netty实现，支持持久化和集群。
* [TBMQ](https://github.com/thingsboard/tbmq)：TBMQ是一个开源MQTT消息代理，能够处理4M+并发客户端连接，支持每个集群节点每秒至少3M消息吞吐量，并具有低延迟交付。
* [MoP](https://github.com/streamnative/mop)：MoP的开发是为了在Pulsar上原生支持MQTT协议。
* [EnMasse](https://github.com/EnMasseProject/enmasse)：EnMasse在Kubernetes和OpenShift上提供了一个自助消息传递平台，具有统一的界面来管理不同的消息传递基础设施。
* [Smart MQTT](https://gitee.com/smartboot/smart-mqtt)：Smart MQTT是一款开源的云原生分布式MQTT Broker服务器，支持海量物联网设备互联互通。
* [RocketMQ MQTT](https://github.com/apache/rocketmq-mqtt)：全新的MQTT协议架构模型，基于该模型RocketMQ可以更好地支持来自物联网设备、手机APP等终端的消息。
* [SMQTTX](https://gitee.com/quickmsg/smqttx)：基于Java实现的物联网分布式MQTT消息代理服务器。
* [MQTTX](https://github.com/Amazingwujun/mqttx)：MQTTX基于MQTT v3.1.1协议开发，旨在提供易于使用且性能优越的MQTT Broker。
* [IoT MQTT Server](https://gitee.com/recallcode/iot-mqtt-server)：轻量级物联网MQTT服务器，支持集群。
* [KMQTT](https://github.com/davidepianca98/KMQTT)：KMQTT是Kotlin多平台MQTT 3.1.1/5.0客户端和代理，目的是针对最多可能的构建目标。
* [MonsterMQ](https://github.com/vogler75/monster-mq)：MonsterMQ是一个基于Vert.X和Hazelcast构建的MQTT代理。
* [Zer0MQTTServer](https://github.com/zer0Black/zer0MQTTServer)：使用Java AIO实现的MQTT协议服务器，用于推送和IM聊天。
* [IoT Harbor](https://github.com/1ssqq1lxr/iot-harbor)：Reactor Netty库实现的MQTT Server。
* [Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt)：Vert.x MQTT提供MQTT服务器和客户端组件。
* [MQTT/UDP](https://github.com/dzavalishin/mqtt_udp)：MQTT/UDP是源自MQTT的基于UDP广播/组播的协议。

#### MQTT客户端

* [Eclipse Paho](https://github.com/eclipse/paho.mqtt.java)：Paho Java是一个用Java编写的MQTT客户端库，由Eclipse IoT组织开发。
* [HiveMQ MQTT Client](https://github.com/hivemq/hivemq-mqtt-client)：MQTT 5.0和3.1.1兼容且功能丰富的高性能Java客户端库，具有不同的API风格和背压支持。
* [MQTT Client](https://github.com/fusesource/mqtt-client)：MQTT Client为MQTT提供API，如果发生任何网络故障，它会自动重新连接到MQTT服务器并恢复客户端会话。
* [HelloIoT](https://github.com/adrianromero/helloiot)：HelloIoT是一个MQTT仪表板应用程序，你可以使用HelloIoT作为MQTT客户端应用程序来发布和订阅主题，也可以使用HelloIoT作为客户端平台来创建自己的仪表板。
* [WeMQ](https://gitee.com/dromara/WeMQ)：WeMQ是一款面向物联网设备运营商的开源物联网设备调试系统，提供完整的物联网设备调试方案，集成设备管理、MQTT服务器管理、客户管理等功能，由dormara社区开源。
* [Socket MQTT](https://github.com/daoshenzzg/socket-mqtt)：Socket MQTT是一个基于Netty、MQTT实现的推送基础框架。
* [Netty MQTT Client](https://github.com/xzc-coder/netty-mqtt-client)：基于Netty实现的MQTT 3及MQTT 5协议的客户端。
* [Courier](https://github.com/gojek/courier-android)：Courier是一个Kotlin库，用于使用MQTT协议创建长时间运行的连接。
* [MQTT.fx](https://www.softblade.de/)：MQTT.fx是开发和生产中测试物联网路由的工具。
* [CorreoMQTT](https://github.com/EXXETA/correomqtt)：CorreoMQTT是使用HiveMQ客户端库的现代图形MQTT客户端。
* [JMSToolBox](https://github.com/jmstoolbox/jmstoolbox)：JMSToolBox是一个通用JMS客户端，能够以一致的方式与市场上数量最多的队列管理器/队列提供程序进行交互。
* [MqttInsight](https://github.com/ptma/mqtt-insight)：MqttInsight是一款开源跨平台MQTT桌面客户端。
* [MQTT Spy](https://github.com/eclipse-paho/paho.mqtt-spy)：MQTT Spy是一款开源桌面和命令行实用程序，旨在帮助你监控MQTT主题上的活动。

#### 车联网

* [JT808 Server](https://gitee.com/yezhihao/jt808-server)：JT808、JT808协议解析；支持TCP、UDP，实时兼容2011、2013、2019版本协议，支持分包。
* [JT Framework](https://github.com/hylexus/jt-framework)：基于Spring Boot的JT-808协议服务端。
* [Eclipse MOSAIC](https://github.com/eclipse-mosaic/mosaic)：MOSAIC是智能互联移动领域的多尺度仿真框架，它允许将来自不同领域的模拟器耦合到综合模拟工具。
* [JTT1078 Video Server](https://gitee.com/matrixy/jtt1078-video-server)：基于JT/T 1078协议实现的视频转播服务器。
* [Spring Boot Starter JT808](https://gitee.com/zhoyq/spring-boot-starter-jt808)：交通标准808协议解析二次开发包。

#### 车载诊断

* [OBD Java API](https://github.com/pires/obd-java-api)：OBD-II Java API。
* [Kotlin OBD API](https://github.com/eltonvs/kotlin-obd-api)：一个轻量级、由开发人员驱动的API，用于查询和解析OBD命令。

#### 嵌入式

* [MICROEJ](https://developer.microej.com/)：MicroEJ的使命是将虚拟化和OOP民主化到嵌入式世界。
* [Arduino](https://github.com/arduino/Arduino)：Arduino是一个开源嵌入式硬件平台，用来供用户制作可交互式的嵌入式项目。
* [Wiring](https://github.com/WiringProject/Wiring)：Wiring是一个微控制器的开源编程框架，最初起源于意大利伊夫雷亚交互设计学院。
* [Eclipse Mita](https://github.com/eclipse/mita)：Mita是一种用于嵌入式物联网的新型编程语言。
* [CocktailPi](https://github.com/alex9849/CocktailPi)：基于树莓派的DIY鸡尾酒制作机的Web界面和控制软件。
* [Pi4J](https://github.com/Pi4J/pi4j-v1)：Pi4J旨在为Java程序员提供一个友好的面向对象的I/O API和实现库，以访问Raspberry Pi平台的完整I/O功能，起源于瑞士西北应用科学与艺术大学。
* [Ardulink 2](https://github.com/Ardulink/Ardulink-2)：Ardulink 2是一个完整的开源Java解决方案，用于控制和协调Arduino板。
* [Diozero](https://github.com/mattjlewis/diozero)：Diozero是用Java编写的设备I/O库，为连接到单板计算机的一系列GPIO/I2C/SPI设备提供面向对象的接口。
* [R2Cloud](https://github.com/dernasherbrezon/r2cloud)：R2Cloud可以跟踪和解码来自卫星的各种无线电信号。
* [RedBear Duo](https://github.com/redbear/Duo)：RedBear Duo是一款拇指大小的开发板，旨在简化构建物联网产品的过程。
* [JArduino](https://github.com/SINTEF-9012/JArduino)：JArduino是一个Java API和Arduino固件，允许使用Java对Arduino开发板进行编程。
* [JRPiCam](https://github.com/Hopding/JRPiCam)：JRPiCam是一个Java API，允许在Raspberry Pi上运行的Java应用程序访问Raspberry Pi相机。

#### 串口

* [JSerialComm](https://github.com/Fazecast/jSerialComm)：JSerialComm是一个独立于平台的Java串行端口访问库。
* [RXTX](https://github.com/rxtx/rxtx)：RXTX是Java中串口的本机接口。
* [JSSC](https://github.com/scream3r/java-simple-serial-connector)：Java中用于使用串行端口的库。
* [SerialPundit](https://github.com/RishiGupta12/SerialPundit)：SerialPundit是一个用于串行端口和HID通信的SDK。
* [PureJavaComm](https://github.com/nyholku/purejavacomm)：PureJavaComm是一个用于从Java访问串行端口的API。
* [NRJavaSerial](https://github.com/NeuronRobotics/nrjavaserial)：Java串行端口系统，这是RXTX项目的一个分支，用于本地代码的jar加载。
* [Android SerialPort](https://github.com/GeekBugs/Android-SerialPort)：Android平台上的USB串口调试库。
* [SerialPortHelper](https://github.com/freyskill/SerialPortHelper)：Android串口通讯助手，使用C++实现。
* [jRxTx](https://github.com/openmuc/jrxtx)：jRxTx是一个Java串行通信库，它可用于使用众所周知的基于UART的串行协议进行通信。
* [JavaCAN](https://github.com/pschichtel/JavaCAN)：Linux内核提供的socketcan API的简单JNI包装器。
* [NettyX](https://github.com/fbbzl/nettyx)：Netty扩展，提供了部分工具类，同时支持串口通信。

#### Modbus

* [Modbus4j](https://github.com/MangoAutomation/modbus4j)：Modbus4j是由Infinite Automation和Serotonin用Java编写的Modbus协议的高性能且易于使用的实现。
* [JLibModbus](https://github.com/kochedykov/jlibmodbus)：JLibModbus是Modbus协议的Java语言实现。
* [J2mod](https://github.com/steveohara/j2mod)：J2mod是Jamod的一个分支，进行了大量的重构和代码修复。
* [JaMod](https://github.com/openhab/jamod)：JaMod是100% Java编写的Modbus实现。
* [Modbus](https://github.com/digitalpetri/modbus)：适用于Java 17+的Modbus TCP、Modbus RTU/TCP和Modbus RTU/串行的现代、高性能、易于使用的客户端和服务器实现。
* [EasyModbus4j](https://github.com/zengfr/easymodbus4j)：EasyModbus4j是一个高性能和易用的Modbus协议的Java实现，基于Netty开发。
* [Iot Modbus](https://gitee.com/flyoss/iot-modbus)：物联网通讯协议，基于Netty框架，支持COM(串口)和TCP协议，支持服务端和客户端两种模式。
* [Modbus4Android](https://github.com/zgkxzx/Modbus4Android)：这是适用于Android的Modbus库。
* [Modbus4Android](https://github.com/licheedev/Modbus4Android)：Modbus的Android实现，添加对Android串口(RTU)的支持。
* [Nifty Modbus](https://github.com/SolarNetwork/nifty-modbus)：Nifty Modbus是一个优秀的Java Modbus库。
* [EasyModbusTCP](https://github.com/rossmann-engineering/EasyModbusTCP.Java)：EasyModbusTCP是用于Java实现的Modbus-TCP、Modbus-UDP和Modbus-RTU库。
* [IoT Communication](https://gitee.com/xingshuang/iot-communication)：IoT Communication是一个物联网通信的工具、包含西门子S7通信协议、Modbus、三菱Melsec等。
* [Protocol](https://gitee.com/weiyigulu_admin/protocol)：IEC104、Modbus、CDT的协议工具包。

#### USB库

* [USB4Java](https://github.com/usb4java/usb4java)：该库可用于在Java中访问USB设备。
* [Javax USB](https://github.com/KeyBridge/lib-javax-usb3)：用于访问USB设备的Java库。
* [USB Drive Detector](https://github.com/samuelcampos/usbdrivedetector)：一个Java库，用于获取连接到计算机的所有USB存储设备的列表。
* [Java HID-API](https://github.com/nyholku/purejavahidapi)：HID-API是一个跨平台API，用于从Java访问USB HID设备。
* [JavaDoesUSB](https://github.com/manuelbl/JavaDoesUSB)：Java Does USB是一个用于处理USB设备的Java库，它允许查询有关所有连接的USB设备的信息，并使用自定义/供应商特定协议与USB设备进行通信。
* [Hid4Java](https://github.com/gary-rowe/hid4java)：libusb/hidapi库的跨平台JNA包装器，在Windows/Mac/Linux上开箱即用。
* [Java USB LibUSB](https://github.com/trygvis/javax-usb-libusb1)：基于libusb的javax.usb实现。

#### XBee

* [XBee API](https://github.com/andrewrapp/xbee-api)：这是一个Java API，用于在API模式下与XBee/XBee-Pro系列1(802.15.4)和系列2(ZB/ZigBee Pro)OEM射频模块进行通信。
* [XBee Java](https://github.com/digidotcom/xbee-java)：这是一个用Java开发的易于使用的API，允许你与Digi International的XBee射频(RF)模块进行交互。

## 短信

* [Twilio Java](https://github.com/twilio/twilio-java)：用于与Twilio REST API通信并生成TwiML的Java库。
* [SMS4J](https://gitee.com/dromara/sms4j)：SMS4J为短信聚合框架，可以轻松集成多家短信服务，解决接入多个短信SDK的繁琐流程。
* [Guerlab](https://gitee.com/guerlab_net/guerlab-sms)：Guerlab是基于Spring Boot的短信服务支持，通过引用不同的Starter启用不同的短信通道支持，支持多通道下的负载均衡，支持同步/异步方式发送。
* [SMSGate](https://github.com/Lihuanghe/SMSGate)：SMSGate是Netty 4框架实现的三网合一短信网关核心框架。
* [SMSCGateway](https://github.com/RestComm/smscgateway)：SMSC用于向移动运营商网络(GSM、SS7 MAP)、SMS聚合器(SMPP)和互联网电话服务提供商(SIP、SMPP)发送/接收SMS。
* [SMS Platform](https://github.com/makemyownlife/platform-sms)：基于Spring Boot开发的短信网关服务，提供客户端SDK。
* [SMS](https://github.com/yunpian/sms)：云通讯、国际短信、短信API、短信SDK，短信平台，短信验证码，短信接口。
* [Cloudhopper SMPP](https://github.com/twitter-archive/cloudhopper-smpp)：Cloudhopper SMPP是SMPP的高效、可扩展且灵活的Java实现，由Twitter开源。
* [jSMPP](https://github.com/opentelecoms-org/jsmpp)：jSMPP是SMPP协议的Java实现，它提供与消息中心或ESME通信的接口，并且能够处理每秒3000-5000条消息的流量。
* [JSMPP](https://github.com/uudashr/jsmpp)：Java SMPP API。
* [OpenSmpp](https://github.com/OpenSmpp/opensmpp)：OpenSmpp是一个成熟的Java库，可实现SMPP协议，并允许开发外部短信实体(ESME)等。
* [SMSLib](https://github.com/tdelenikas/smslib)：SMSLib是一个短信库。
* [SMS Client](https://github.com/Lihuanghe/sms-client)：一个基于SMSGate框架的纯发送短信客户端库。
* [SMS Spring Boot](https://github.com/jackieonway/sms-spring-boot-project)：短信服务Spring Boot Starter，目前支持腾讯和阿里短信服务。

## 邮件库

* [Jakarta Mail](https://github.com/jakartaee/mail-api)：Jakarta Mail定义了一个独立于平台和协议的框架来构建邮件和消息传递应用程序。
* [Simple Java Mail](https://github.com/bbottema/simple-java-mail)：Simple Java Mail是Java中最易于使用的轻量级邮件库。
* [Oh My Email](https://github.com/hellokaton/oh-my-email)：非常轻量的Java邮件发送类库，支持抄送、附件、模板等功能。
* [SendGrid](https://github.com/sendgrid/sendgrid-java)：该库允许你通过Java快速轻松地使用Twilio SendGrid Web API v3。
* [Mailgun](https://github.com/sargue/mailgun)：这是一个小型Java库，可以使用出色的Mailgun服务轻松发送电子邮件。
* [NioImapClient](https://github.com/HubSpot/NioImapClient)：基于Netty的Java高性能IMAP客户端。
* [Apache Commons Email](https://github.com/apache/commons-email)：Commons Email提供了发送电子邮件的API，简化了JavaMail API。
* [JMail](https://github.com/RohanNagar/jmail)：一个现代、快速、零依赖的库，用于在Java中处理电子邮件地址并执行电子邮件地址验证。
* [Maildroid](https://github.com/nedimf/maildroid)：Maildroid是一个小型且强大的Android库，用于使用SMTP服务器发送电子邮件。
* [EWS Java API](https://github.com/OfficeDev/ews-java-api)：EWS Java API提供了一个托管接口，用于开发使用EWS的Java应用程序。
* [SubEtha SMTP](https://github.com/voodoodyne/subethasmtp)：SubEtha SMTP是一个Java库，它允许你的应用程序通过简单、易于理解的API接收SMTP邮件。
* [Eclipse Angus Mail](https://github.com/eclipse-ee4j/angus-mail)：该项目提供了Jakarta Mail规范2.1+的实现。
* [ExJello](https://code.google.com/archive/p/exjello/)：ExJello是一个连接到Microsoft Exchange服务器的JavaMail提供程序，它被设计为标准POP3和SMTP提供商的直接替代品。
* [DKIM](https://www.agitos.de/dkim-for-javamail/)：允许你使用DKIM对邮件进行签名的开源库。
* [MJML4J](https://github.com/digitalfondue/mjml4j)：MJML的Java实现，一个使响应式电子邮件变得简单的框架。
* [ImapNIO](https://github.com/yahoo/imapnio)：ImapNIO是一个支持基于NIO的IMAP客户端的Java库，由Yahoo开源。
* [JavaMail Crypto](http://javamail-crypto.sourceforge.net/)：这是JavaMail API的一个补充，它使用S/MIME和/或OpenPGP提供简单的电子邮件加密和解密。
* [Jcabi Email](https://github.com/jcabi/jcabi-email)：面向对象的电子邮件Java SDK。
* [Spring Boot Email Tools](https://github.com/ozimov/spring-boot-email-tools)：一组用于在Spring Boot应用程序中使用纯文本、HTML或模板引擎生成动态内容发送电子邮件的服务和工具。
* [Email RFC2822 Validator](https://github.com/bbottema/email-rfc2822-validator)：基于Java且符合RFC2822标准的电子邮件地址验证器和解析器。
* [Mailjet Java Wrapper](https://github.com/mailjet/mailjet-apiv3-java)：Mailjet Java API包装器，Mailjet是法国的电子邮件营销平台。
* [Email4J](https://github.com/juandesi/email4j)：Email4J是一个构建在javax.mail API之上的高级Java库，用于管理和发送电子邮件，无需了解底层传输的任何规范。
* [ErmesMail](https://github.com/SoftInstigate/ermes-mail)：ErmesMail是一个用于异步发送电子邮件的Java库和命令行接口。
* [Jodd Mail](https://github.com/oblac/jodd-mail)：Jodd Mail提供了一些工具类，用于以更简单、实用的方式发送和接收电子邮件。
* [Email Template Builder](https://github.com/rocketbase-io/email-template-builder)：该库可以以流式的方式构建HTML/文本电子邮件。
* [NioSmtpClient](https://github.com/HubSpot/NioSmtpClient)：基于Netty的Java高性能SMTP客户端。

## 邮件服务器

* [FakeSMTP](https://github.com/Nilhcem/FakeSMTP)：FakeSMTP是一个带有GUI的免费虚拟SMTP服务器，可轻松测试应用程序中的电子邮件。
* [Apache James](https://github.com/apache/james-project)：James提供在JVM上运行的完整、稳定、安全且可扩展的邮件服务器。
* [Fake SMTP Server](https://github.com/gessnerfl/fake-smtp-server)：Fake SMTP Server是一个简单的SMTP服务器，专为开发目的而设计。
* [Aspirin](https://github.com/masukomi/aspirin)：Aspirin是一个供Java开发人员使用的嵌入式仅发送SMTP服务器。
* [Email](https://github.com/risesoft-y9/Email)：Email是一款简化的具备邮件服务器的企业邮箱，支持在将其他主流邮箱的邮件进行导入后自主控制邮件数据安全。
* [MockMock](https://github.com/tweakers/MockMock)：MockMock是一个基于Java构建的跨平台SMTP服务器。
* [Dumbster](https://github.com/kirviq/dumbster)：Dumbster是一个非常简单的伪SMTP服务器，专为发送电子邮件消息的单元和系统测试应用程序而设计。
* [ElasticInbox](https://github.com/elasticinbox/elasticinbox-java)：ElasticInbox是可靠、分布式、可扩展的电子邮件存储。
* [LunaticSMTP](https://github.com/anlar/lunaticsmtp)：带有JavaFX GUI的虚拟SMTP服务器，用于测试电子邮件发送应用程序。

## DSL

* [Eclipse Xtend](https://github.com/eclipse/xtext-xtend)：Xtext是一个用于开发编程语言和DSL的框架。
* [MontiCore](https://github.com/MontiCore/monticore)：MontiCore是一个用于高效开发DSL的语言工作台，它处理定义DSL的扩展语法格式并生成用于处理DSL文档的Java组件，由亚琛工业大学开发。
* [Spoofax](https://github.com/metaborg/spoofax)：Spoofax是一个帮助开发者快速开发领域特定语言(DSL)的平台。
* [Dsl.scala](https://github.com/ThoughtWorksInc/Dsl.scala)：Dsl.scala是一个在Scala中创建嵌入式DSL的框架，由ThoughtWorks开源。

## JMX

* [Simple JMX](https://github.com/j256/simplejmx)：JMX Java库可帮助使用JMX和Web发布对象。
* [JMXUtils](https://github.com/martint/jmxutils)：让导出JMX mbean变得容易。

## RMI

* [ARMI](https://github.com/AugurSystems/ARMI)：ARMI是Java内置RMI的替代方案，最初是为了跨NAT工作而开发的。
* [Dirmi](https://github.com/cojen/Dirmi)：Dirmi是Java RMI的替代品，支持双向远程对象。
* [JrPip](https://github.com/goldmansachs/jrpip)：JrPip使用Java二进制序列化协议提供远程方法调用，由高盛银行开源。

## gRPC

* [Spring gRPC](https://github.com/spring-projects/spring-grpc)：Spring gRPC项目为开发gRPC应用程序提供了Spring友好的API和抽象。
* [gRPC Spring Boot](https://github.com/grpc-ecosystem/grpc-spring)：gRPC框架的Spring Boot Starter库。
* [gRPC Spring Boot](https://github.com/LogNet/grpc-spring-boot-starter)：gRPC的Spring Boot Starter模块。
* [gRPC Starter](https://github.com/DanielLiu1123/grpc-starter)：该项目为gRPC生态系统提供了开箱即用、高度可扩展的Spring Boot Starter。
* [Polyglot](https://github.com/grpc-ecosystem/polyglot)：Polyglot是一个gRPC客户端，可以与任何gRPC服务器通信。
* [gRPC Spring Boot Starter](https://github.com/AnoyiX/grpc-spring-boot-starter)：Spring Boot快速集成gRPC，轻松实现远程方法调用。
* [gRPC Swagger](https://github.com/grpc-swagger/grpc-swagger)：使用Swagger-UI调试gRPC应用程序。
* [Mediator](https://github.com/ButterCam/Mediator)：跨平台GUI gRPC调试代理。
* [Google API Extensions Java](https://github.com/googleapis/gax-java)：适用于Java的Google API扩展。
* [gRPC Java Contrib](https://github.com/salesforce/grpc-java-contrib)：grpc-java库的有用扩展。
* [Sisyphus](https://github.com/ButterCam/sisyphus)：Sisyphus是一个基于Spring Boot与Kotlin构建的gRPC服务框架。
* [Akka gRPC](https://github.com/akka/akka-grpc)：支持在Akka Streams之上构建流式gRPC服务器和客户端。
* [Reactive gRPC](https://github.com/salesforce/reactive-grpc)：Reactive gRPC是一套将gRPC与Reactive Streams编程库结合使用的库，由Salesforce开源。

## 对象池

* [Stormpot](https://github.com/chrisvest/stormpot)：Stormpot是一个Java对象池库。
* [Apache Commons Pool](https://github.com/apache/commons-pool)：Commons Pool库提供了对象池API和许多对象池实现。
* [Fast Object Pool](https://github.com/DanielYWoo/fast-object-pool)：FOP是一个针对并发访问进行优化的轻量级高性能对象池。
* [PooledJMS](https://github.com/messaginghub/pooled-jms)：用于消息传递应用程序的JMS连接池，为JMS连接、会话和消息生产者提供池化。
* [Vibur Object Pool](https://github.com/vibur/vibur-object-pool)：Vibur对象池是一个通用并发Java对象池，完全使用标准Java并发实用程序构建，不使用任何同步块或方法，并且没有任何外部依赖项。
* [LitePool](https://github.com/nextopcn/lite-pool)：由Java编写的精简版快速对象池。
* [CoralPool](https://github.com/coralblocks/CoralPool)：CoralPool是一种高性能、轻量级且无垃圾的Java对象池实现。
* [Reactor Pool](https://github.com/reactor/reactor-pool)：Reactor Pool项目旨在为响应式应用程序提供一个通用对象池。
* [Jillegal](https://github.com/serkan-ozal/jillegal)：Java堆外对象池和动态检测工具。

## 幂等处理

* [Idempotent](https://github.com/it4alla/idempotent)：幂等处理方案。
* [Idempotent Spring Boot Starter](https://github.com/pig-mesh/idempotent-spring-boot-starter)：对原有idempotent代码重构和功能增强。
* [Jdempotent](https://github.com/Trendyol/Jdempotent)：轻松使你的端点幂等，由Trendyol开源。
* [Idempotence4j](https://github.com/transferwise/idempotence4j)：Idempotence4j是一个轻量级库，为处理幂等操作提供支持。
* [Quidem](https://github.com/julianhyde/quidem)：Quidem是一个幂等查询执行器。
* [Tomato](https://github.com/lxchinesszz/tomato)：Tomato是一款专门为Spring Boot项目设计的幂等组件。
* [Idempotent](https://github.com/arun0009/idempotent)：Idempotent是一个轻量级的Java库，它在API中提供对幂等性的支持，从而更容易处理重复请求并确保分布式系统的可靠运行。

## 数据字典

* [EasyTrans](https://gitee.com/dromara/easy_trans)：EasyTrans是一款用于做数据翻译的代码辅助插件，由dromara社区开源。
* [Dict Trans](https://gitee.com/aizuda/dict-trans)：由爱组搭开源的简单字典翻译组件。
* [Transformer](https://github.com/luo-zhan/Transformer)：Transformer是一款功能全面的字段转换工具，只需要几个简单的注解，让开发更简单。

## Bot

* [ChopperBot](https://github.com/Geniusay/ChopperBot)：ChopperBot一款全自动的主播切片机器人。
* [BenTen](https://github.com/intuit/benten)：BenTen是一个CUI聊天机器人框架，它提供了在几分钟内构建有用的对话聊天机器人所需的所有集成，由Intuit开发。
* [Tock](https://github.com/theopenconversationkit/tock)：Tock是一个完整且开放的平台，用于构建对话代理(也称为机器人)。
* [R-Bot](https://github.com/semicons/java_oci_manage)：本系统目前应用于甲骨文云/Azure云的一些快捷操作。
* [JAICF](https://github.com/just-ai/jaicf-kotlin)：JAICF是Just AI推出的一款综合企业级框架，用于使用基于Kotlin的DSL进行对话语音助手和聊天机器人的开发。
* [PhantomBot](https://github.com/PhantomBot/PhantomBot)：PhantomBot是一款积极开发的开源交互式Twitch机器人。
* [Line Message SDK](https://github.com/line/line-bot-sdk-java)：适用于Java的LINE Messaging API SDK可以轻松使用LINE Messaging API开发机器人，并且可以在几分钟内创建示例机器人。
* [BotLibre](https://github.com/BotLibre/BotLibre)：适用于人工智能、聊天机器人、虚拟代理、社交媒体自动化和实时聊天自动化的开放平台。
* [Repairnator](https://github.com/eclipse/repairnator)：Repairnator是Github上的一个软件机器人开源项目，特别用于自动化程序修复：构建失败修复、静态警告修复(SoraldBot)等。
* [EDDI](https://github.com/labsai/EDDI)：E.D.D.I是一种中间件，用于连接和管理LLM API机器人。
* [春松客服](https://github.com/cskefu/cskefu)：春松客服是开源的智能客服系统。
* [Microsoft Bot Framework Java SDK](https://github.com/microsoft/botbuilder-java)：Microsoft Bot Framework提供了构建和连接智能机器人所需的功能，无论用户在哪里交谈，这些机器人都可以自然地交互，从文本/短信到Skype、Slack、Office 365邮件和其他流行服务。
* [Mutters](https://github.com/rabidgremlin/Mutters)：构建机器人大脑的框架。
* [FeishuBot](https://github.com/rawchen/FeishuBot)：飞书群聊/私聊ChatGPT机器人。
* [PokuBot](https://github.com/norecha/pokubot)：部落冲突机器人。
* [Command-Flow](https://github.com/FixedDev/command-flow)：适用于Java 8+的灵活且与平台无关的命令框架。
* [PircBotX](https://github.com/pircbotx/pircbotx)：PircBotX是一个强大的Java IRC客户端库，适用于机器人和用户客户端。
* [Kitteh IRC Client Lib](https://github.com/KittehOrg/KittehIRCClientLib)：KICL是一个功能强大的现代Java IRC库，使用Netty库构建，以最大限度地提高性能和可扩展性。
* [Spring Bot](https://github.com/finos/spring-bot)：Spring Bot是一组Spring Boot Starter，旨在用Java和Kotlin构建聊天机器人，由金融科技基金会开源。
* [Kingbbode Spring Boot Chatbot](https://github.com/kingbbode/spring-boot-chatbot)：基于Spring Boot的交互式聊天机器人支持框架。

#### Discord机器人

* [JMusicBot](https://github.com/jagrosh/MusicBot)：JMusicBot是一个可以轻松设置和运行的Discord音乐机器人。
* [JDA](https://github.com/discord-jda/JDA)：该开源库旨在使用实时网关和REST API在Discord上实现机器人。
* [Kord](https://github.com/kordlib/kord)：Kord是一个基于协程、模块化的Discord API实现。
* [Discord4J](https://github.com/Discord4J/Discord4J)：Discord4J是一个快速、强大、无偏见的响应式库，可使用官方Discord Bot API快速轻松地开发适用于Java、Kotlin和其他JVM语言的Discord机器人。
* [CatNip](https://github.com/mewna/catnip)：Java中的Discord API包装器，完全异步/响应式，构建在RxJava之上。
* [Javacord](https://github.com/Javacord/Javacord)：一个易于使用的多线程库，用于在Java中创建Discord机器人。
* [DiscordJar](https://github.com/discord-jar/discord.jar)：DiscordJar是一个正在进行中的Discord API Java包装器。
* [GiveawayBot](https://github.com/jagrosh/GiveawayBot)：在Discord服务器上快速轻松地保存赠品。
* [Vortex](https://github.com/jagrosh/Vortex)：Discord审核机器人。
* [MantaroBot](https://github.com/Mantaro/MantaroBot)：使用JDA用Java制作的多用途Discord机器人。
* [Sokobot](https://github.com/PolyMarsDev/Sokobot)：一个可以玩推箱子的Discord机器人。
* [AIODE](https://github.com/robinfriedli/aiode)：可播放Spotify曲目和YouTube视频或任何URL(包括Soundcloud链接和Twitch流)的Discord机器人。
* [JDA Utilities](https://github.com/JDA-Applications/JDA-Utilities)：JDA Utilities是一系列与JDA一起使用来协助创建机器人的工具和实用程序。
* [Chuu](https://github.com/ishwi/Chuu)：一个Discord机器人，将Last.fm与Discord集成。
* [Ree6](https://github.com/Ree6-Applications/Ree6)：Ree6是一款由Presti维护的一体化Discord机器人。
* [Spectra](https://github.com/jagrosh/Spectra)：Spectra是一款私人、多用途、娱乐性和实用性的Discord机器人。

#### Telegram机器人

* [TelegramBots](https://github.com/rubenlagus/TelegramBots)：使用Telegram Bots API创建机器人的Java库。
* [Java Telegram Bot API](https://github.com/pengrad/java-telegram-bot-api)：用于Java的Telegram Bot API。
* [Kotlin Telegram Bot](https://github.com/kotlin-telegram-bot/kotlin-telegram-bot)：用Kotlin编写的Telegram Bot API的包装器。
* [TeleightBots](https://github.com/Teleight/TeleightBots)：TeleightBots是一个轻量级、高性能、易于使用的Java Telegram Bot API包装器。
* [TDLight Java](https://github.com/tdlight-team/tdlight-java)：基于TDLib的完整Bot和Userbot Telegram库。
* [TelegramBotAPI](https://github.com/InsanusMokrassar/ktgbotapi)：用于Telegram Bot API的类型安全库。
* [Telegram](https://github.com/bot4s/telegram)：Telegram Bot API的简单、可扩展、强类型包装器。
* [Telegram Bot](https://github.com/vendelieu/telegram-bot)：带有方便的Kotlin DSL的Telegram Bot API包装器。

#### Facebook机器人

* [JBot](https://github.com/rampatra/jbot)：JBot是一个Java框架，可在几分钟内创建Slack和Facebook机器人。
* [Messenger4j](https://github.com/messenger4j/messenger4j)：用于在Facebook Messenger平台上构建聊天机器人的Java库。
* [Racter](https://github.com/Clivern/Racter)：用于在Facebook的Messenger平台上构建机器人的Java框架。
* [FB BotMill](https://github.com/BotMill/fb-botmill)：FB BotMill旨在简化Facebook内部机器人的开发、设计和运行过程。

#### QQ机器人

* [Mirai](https://github.com/mamoe/mirai)：Mirai是一个在全平台下运行，提供QQ Android协议支持的高效率机器人库。
* [OpenShamrock](https://github.com/whitechi73/OpenShamrock)：OpenShamrock是基于Xposed实现OneBot标准的QQ机器人框架。
* [Shiro](https://github.com/MisakaTAT/Shiro)：基于OneBot协议的QQ机器人快速开发框架。
* [Smart QQ](https://github.com/ScienJus/smartqq)：SmartQQ API，可以用它实现自己的QQ机器人。
* [QQPD Bot Java](https://github.com/Kloping/qqpd-bot-java)：Java SDK主要基于基础API封装，提供给用户一种简单、高效的使用方式。
* [Simple Robot](https://github.com/simple-robot/simpler-robot)：Simple Robot是一个基于Kotlin协程的多平台Bot风格高性能异步事件调度框架，异步高效、Java友好。
* [QQ Robot SDK](https://github.com/kosaka-bun/qqrobot-sdk)：本项目是一款Spring Boot平台一站式QQ机器人开发框架。
* [Petpet](https://github.com/Dituon/petpet)：自定义合成图片的Mirai插件。

#### 微信机器人

* [WeChat Robot](https://gitee.com/hellokaton/wechat-robot)：Java版微信普通号机器人。
* [Jeeves](https://github.com/kanjielu/jeeves)：一个智能微信机器人。
* [WeChatBotEngine](https://github.com/moontide/WeChatBotEngine)：基于微信网页版HTTP协议的机器人引擎。

## Android开发

这里列出了Android开发中各种各样的组件、布局、视图、动画等库。

#### Android框架

* [Flutter](https://github.com/flutter/flutter)：Flutter是Google的SDK，旨在通过单一代码库为移动端、网页端和桌面端打造美观、快速的用户体验。
* [React Native](https://github.com/facebook/react-native)：React Native将React的声明式UI框架引入iOS和Android平台，由Facebook开源。
* [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform)：Compose Multiplatform是一个声明式框架，用于使用Kotlin跨多个平台共享UI，由JetBrains开发。
* [RIBs](https://github.com/uber/RIBs)：RIBs是Uber许多移动应用程序背后的跨平台架构框架。
* [UniApp](https://github.com/dcloudio/uni-app)：UniApp是一个使用Vue.js开发小程序、Web、App的统一前端框架，由DCloud开源。
* [Hummer](https://github.com/didi/Hummer)：Hummer是一套高性能高可用的跨端开发框架，一套代码可以同时支持开发Android和iOS应用，由滴滴开源。
* [KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI)：Kuikly是一个基于Kotlin多平台的全面的UI和逻辑跨平台解决方案，由腾讯开源。
* [Lynx](https://github.com/lynx-family/lynx)：Lynx是一系列开源技术，使开发人员能够利用他们现有的Web技能，从单一代码库为移动和Web创建真正的原生UI，并具有规模和速度方面的性能，由字节开源。

#### Android测试库

* [Robolectric](https://github.com/robolectric/robolectric)：Robolectric是Android的行业标准单元测试框架。
* [Robotium](https://github.com/robotiumtech/robotium)：Robotium是一个Android测试自动化框架，完全支持原生和混合应用程序。
* [Kaspresso](https://github.com/KasperskyLab/Kaspresso)：Kaspresso是一个用于Android UI测试的框架。
* [AppiumTestDistribution](https://github.com/AppiumTestDistribution/AppiumTestDistribution)：一个用于跨设备并行运行Android和iOS Appium测试的工具。
* [AssertJ Android](https://github.com/square/assertj-android)：一组用于测试Android的AssertJ断言，由Square开源。
* [Shot](https://github.com/pedrovgs/Shot)：Shot是一个Android项目，你可以使用它以简单友好的方式为你的应用程序编写屏幕截图。
* [AndroidX Test](https://github.com/android/android-test)：AndroidX测试库为测试Android应用提供了一个广泛的框架，由Google开发。
* [Test Butler](https://github.com/linkedin/test-butler)：可靠的Android测试框架，由LinkedIn开源。
* [Marathon](https://github.com/MarathonLabs/marathon)：Marathon是一个帮助在最短时间内执行测试的项目。
* [Cafe](https://github.com/baidu/Cafe)：一个强大的Android测试框架，由百度开源。
* [Screen Tests For Android](https://github.com/facebook/screenshot-tests-for-android)：Screen Tests For Android是一个可以在Android上运行仪器测试时生成快速确定性屏幕截图的库，由Facebook开源。
* [ADBKeyBoard](https://github.com/senzhk/ADBKeyBoard)：ADBKeyBoard是一个虚拟键盘，它接收来自系统广播意图的命令，你可以使用adb发送文本输入。
* [Roborazzi](https://github.com/takahirom/roborazzi)：使JVM Android集成测试可见。
* [Accessibility Test Framework For Android](https://github.com/google/Accessibility-Test-Framework-for-Android)：该库收集了View对象以及AccessibilityNodeInfo对象上的各种与可访问性相关的检查，由Google开源。
* [Fork](https://github.com/shazam/fork)：提供以最快的方式执行Android仪器测试的库。
* [ElasticDownload](https://github.com/Tibolte/ElasticDownload)：通过自定义视图实现的下载动画。
* [Selendroid](https://github.com/selendroid/selendroid)：Selendroid是一个测试自动化框架，它通过Selendroid驱动Android原生和混合应用程序以及移动Web的UI。
* [Flank](https://github.com/Flank/flank)：Flank是Firebase测试实验室的大规模并行Android和iOS测试运行器。
* [LiveData Testing](https://github.com/jraska/livedata-testing)：TestObserver可轻松测试LiveData并对其做出断言。
* [JSpeedTest](https://github.com/bertrandmartel/speed-test-lib)：支持HTTP和FTP的Java/Android速度测试客户端库。
* [RxPresso](https://github.com/novoda/rxpresso)：使用RxJava对Android应用程序进行简单的Espresso UI测试。
* [AndroidUiTestingUtils](https://github.com/sergio-sastre/AndroidUiTestingUtils)：一组TestRules、ActivityScenarios和实用程序，用于在给定配置下进行UI和屏幕截图测试。
* [Dropshots](https://github.com/dropbox/dropshots)：Dropshots是一个库和Gradle插件，可以轻松在Android上进行设备上的屏幕截图测试。
* [Android Screenshot Lib](https://github.com/rtyley/android-screenshot-lib)：为你的Android集成测试提供按需截图。
* [ComposablePreviewScanner](https://github.com/sergio-sastre/ComposablePreviewScanner)：帮助使用任何屏幕截图测试库从可组合预览自动生成屏幕截图测试。
* [Fladle](https://github.com/runningcode/fladle)：使用Flank轻松在Firebase Test Lab上扩展你的Android Instrumentation测试。
* [RoboSpock](https://github.com/robospock/RoboSpock)：RoboSpock是一个Android测试框架，它将Spock引入Android应用程序。
* [Ultron](https://github.com/open-tool/ultron)：Ultron是开发Android和Compose Multiplatform UI测试的最简单的框架。
* [Testify](https://github.com/Shopify/android-testify)：为你的Android测试添加屏幕截图，由Shopify开源。
* [ConditionWatcher](https://github.com/AzimoLabs/ConditionWatcher)：Android工具有助于在自动化测试中将应用程序行为与测试线程同步。
* [BusyBee](https://github.com/americanexpress/busybee)：BusyBee是Espresso测试中IdlingResources的替代API，由美国运通开源。
* [Gordon](https://github.com/Banno/Gordon)：Gordon是一款Android仪器测试运行器，专为速度、简单性和可靠性而设计。
* [Spoon](https://github.com/square/spoon)：Spoon是一个由Square开源的用于Android的测试工具和报告生成器。
* [Kakao Compose](https://github.com/KakaoCup/Compose)：使用Kotlin为Espresso Compose提供简洁美观的DSL。
* [Testify](https://github.com/ndtp/android-testify)：为你的Android测试添加屏幕截图。
* [Kappuccino](https://github.com/concretesolutions/kappuccino)：一个使用Espresso和Kotlin简化你在应用中进行仪器测试的方式的框架。
* [Dex Test Parser](https://github.com/linkedin/dex-test-parser)：Dex Test Parser解析APK的Dex文件并返回所有JUnit 3和JUnit 4测试方法的完全限定方法名称，由LinkedIn开源。
* [Trailblaze](https://github.com/block/trailblaze)：Trailblaze是一个由人工智能驱动的移动测试框架，可让你使用自然语言编写和执行测试。

#### Android UI库

* [Material Components Android](https://github.com/material-components/material-components-android)：适用于Android的模块化和可定制的Material Design UI组件。
* [QMUI Android](https://github.com/Tencent/QMUI_Android)：QMUI Android的设计目的是用于辅助快速搭建一个具备基本设计还原效果的Android项目，由腾讯开源。
* [RxBinding](https://github.com/JakeWharton/RxBinding)：RxJava从平台和支持库中绑定用于Android UI小部件的API。
* [Aurora IMUI](https://github.com/jpush/aurora-imui)：Aurora IMUI是一个通用的IM UI组件库，不依赖于任何特定的IM SDK，极光开源。
* [XUI](https://github.com/xuexiangjys/XUI)：一个简洁而优雅的Android原生UI框架。
* [ShineButton](https://github.com/ChadCSong/ShineButton)：这是一个Android的UI库，效果类似闪光。
* [FirebaseUI Android](https://github.com/firebase/FirebaseUI-Android)：FirebaseUI是Android的一个开源库，可让你快速将常见的UI元素连接到Firebase API。
* [Tangram Android](https://github.com/alibaba/Tangram-Android)：Tangram是一个模块化UI解决方案，用于动态构建原生页面，由阿里开源。
* [ChatKit](https://github.com/stfalcon-studio/ChatKit)：ChatKit是一个旨在简化聊天等简单UI开发的库。
* [Litho](https://github.com/facebook/litho)：Litho是一个用于在Android上构建高效UI的声明性框架，由Facebook开源。
* [GreenDroid](https://github.com/cyrilmottier/GreenDroid)：GreenDroid是一个Android平台的开发库，它使应用程序的UI开发更加轻松，并保持一致性。
* [DivKit](https://github.com/divkit/divkit)：DivKit是一个开源的服务器驱动UI(SDUI)框架。
* [Genius](https://github.com/qiujuer/Genius-Android)：Android Material Design主题UI和工具库。
* [Android UI](https://github.com/markushi/android-ui)：用于UI组件的Android库。
* [Android UI Animation Libraries](https://github.com/Ramotion/android-ui-animation-components-and-libraries)：Ramotion开发的Android库、UI组件和自定义动画的精选列表。
* [RWidgetHelper](https://github.com/RuffianZhong/RWidgetHelper)：Android UI快速开发库。
* [Redwood](https://github.com/cashapp/redwood)：Redwood是一个使用Kotlin构建响应式Android、iOS和Web UI的库。
* [FlatUI](https://github.com/eluleci/FlatUI)：FlatUI是一个库，可让你使用具有更好和自定义外观的原生Android小部件。
* [Anvil](https://github.com/anvil-ui/anvil)：Anvil是一个用于创建响应式用户界面的小型Java库。
* [Compose Cupertino](https://github.com/alexzhirkevich/compose-cupertino)：用于iOS的Compose Multiplatform UI组件。
* [RapidView](https://github.com/Tencent/RapidView)：RapidView是一套用于开发Android客户端界面、逻辑以及功能的开发组件，由腾讯开源。
* [Ticker](https://github.com/robinhood/ticker)：Ticker是一个简单的Android UI组件，用于显示滚动文本。
* [CircleMenu](https://github.com/Ramotion/circle-menu-android)：CircleMenu是一个简单、优雅的UI菜单，具有圆形布局和Material Design动画。

#### ActionBar小部件

* [ActionBarSherlock](https://github.com/JakeWharton/ActionBarSherlock)：ActionBarSherlock是一个独立库，旨在通过单一API促进所有Android版本中操作栏设计模式的使用。
* [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar)：FadingActionBar是一个库，它实现了可以在新Play音乐应用中看到的炫酷淡入淡出操作条效果。
* [GlassActionBar](https://github.com/ManuelPeinado/GlassActionBar)：GlassActionBar是一个Android库，它为操作栏实现了类似玻璃的效果。
* [TabBarView](https://github.com/Mirkoddd/TabBarView)：一个Android库，可帮助你创建类似Cyril Mottier的“Capitaine train”应用程序的操作栏选项卡。

#### Activity小部件

* [Android Sliding Activity Library](https://github.com/klinker41/android-slidingactivity)：轻松创建可以在屏幕上垂直滑动的活动，并很好地融入Material Design时代。
* [Material About Library](https://github.com/daniel-stoneuk/material-about-library)：轻松为你的应用创建美观的“关于”屏幕，生成Activity或Fragment。
* [AwesomeSplash](https://github.com/ViksaaSkool/AwesomeSplash)：外观精美的可定制启动画面。
* [RatingReviews](https://github.com/Inconnu08/android-ratingreviews)：RatingReviews是一个小部件和布局，它为你的应用添加了“Rating & Reviews”栏，类似于在Google Play Store和Apple App Store上看到的。
* [AnimatedDismissableActivity](https://github.com/OpenCraft/AnimatedDismissableActivity)：简单酷炫的活动解散动画。

#### Adapter

* [Epoxy](https://github.com/airbnb/epoxy)：Epoxy是一个用于在RecyclerView中构建复杂屏幕的Android库，由Airbnb开源。
* [FastAdapter](https://github.com/mikepenz/FastAdapter)：FastAdapter可以简化RecyclerViews适配器的创建。
* [SectionedRecyclerViewAdapter](https://github.com/luizgrp/SectionedRecyclerViewAdapter)：允许将RecyclerView拆分为带有页眉和/或页脚的部分的适配器。
* [Renderers](https://github.com/pedrovgs/Renderers)：Renderers是一个Android库，旨在避免在应用中创建数据列表/网格所需的所有RecyclerView/Adapter样板以及开发人员按照ViewHolder经典实现创建的所有混乱代码。
* [MultiChoiceAdapter](https://github.com/ManuelPeinado/MultiChoiceAdapter)：MultiChoiceAdapter是ListAdapter的一个实现，它增加了对原生Gmail应用中模态多项选择的支持。
* [AutoplayVideos](https://github.com/Krupen/AutoplayVideos)：创建此库的目的是为了轻松地实现带视频的RecyclerView。
* [SlimAdapter](https://github.com/linisme/SlimAdapter)：一款纤薄、简洁、可打字的适配器。
* [RecyclerViewHelper](https://github.com/nisrulz/recyclerviewhelper)：库提供了围绕Recycler-View的最常见功能的Android，如滑动以关闭、拖放、用户界面中的分隔符、项目被选中和未选中时的事件、项目的点击监听器。
* [EasyAdapter](https://github.com/ribot/easy-adapter)：适用于Android的Easy Adapters库。
* [Efficient Adapter](https://github.com/StanKocken/EfficientAdapter)：为RecyclerView或ViewPager创建新适配器现在变得更加容易。
* [Smart Recycler Adapter](https://github.com/manneohlund/smart-recycler-adapter)：小型、智能且通用的回收器视图适配器，可轻松实现高级数据与ViewHolder的绑定。
* [FunDapter](https://github.com/amigold/FunDapter)：FunDapter让你免于为Android应用中的每个ListView创建新适配器类的痛苦和麻烦。
* [Items](https://github.com/nekocode/Items)：这个库可以为Android的RecyclerView生成基于Data-View-Binding的Adapter。
* [RxRecyclerAdapter](https://github.com/ahmedrizwan/RxRecyclerAdapter)：基于Rx的通用RecyclerView适配器库。
* [AutoAdapter](https://github.com/Zuluft/AutoAdapter)：此仓库简化了使用RecyclerView适配器的工作。

#### Android图表库

* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)：适用于Android的强大且易于使用的图表库。
* [HelloCharts](https://github.com/lecho/hellocharts-android)：适用于Android的图表库，兼容API 8+(Android 2.2)。
* [Williamchart](https://github.com/diogobernardino/williamchart)：Williamchart是一个Android库，用于在Android应用程序中快速实现有吸引力且富有洞察力的图表。
* [XCL Charts](https://github.com/xcltapestry/XCL-Charts)：XCL-Charts基于Android原生Canvas来绘制各种图表，使用简便，定制灵活。
* [AndroidCharts](https://github.com/HackPlan/AndroidCharts)：一个易于使用的带有动画的Android图表库。
* [Android Charts](https://github.com/limccn/Android-Charts)：Android Charts是一个基于Android SDK用Java编写的开源Android开发框架。
* [AnyChart Android](https://github.com/AnyChart/AnyChart-Android)：AnyChart Android Charts是一个出色的数据可视化库，可轻松在Android应用中创建交互式图表。
* [React Native Charts Wrapper](https://github.com/wuxudong/react-native-charts-wrapper)：这个库是流行的Native图表库MPAndroidChart和Charts的React Native包装器。
* [JZAndroidChart](https://github.com/JingZhuanDuoYing/JZAndroidChart)：Android股票图表库。
* [DecoView](https://github.com/bmarrdev/android-DecoView-charting)：DecoView是一个功能强大的库，可以在你的Android应用中创建高度可配置的动画圆形图表。
* [EazeGraph](https://github.com/paulroehr/EazeGraph)：EazeGraph是一个用于创建精美图表的Android库。
* [Androidplot](https://github.com/halfhp/androidplot)：用于在Android应用中创建动态和静态图表的库。
* [KLineChart](https://github.com/fujianlian/KLineChart)：Android仿火币K线图实现。
* [Compose Charts](https://github.com/tehras/charts)：这是一个使用Android Jetpack Compose库绘制和制作动画图表的库。
* [Spark](https://github.com/robinhood/spark)：一个简单的Android迷你图视图。
* [React Native PathJS Charts](https://github.com/capitalone/react-native-pathjs-charts)：该库是一个跨平台(iOS/Android)图表/图形库，使用react-native-svg和routes-js。
* [OXChart](https://github.com/openXu/OXChart)：各种自定义图表库，使用简单、支持扩展。
* [ChartProgressBar](https://github.com/hadiidbouk/ChartProgressBar-Android)：绘制进度条样式的图表。
* [Fit Chart](https://github.com/txusballesteros/fit-chart)：Fit Chart是一个类似于Google Fit轮盘图表的Android视图。
* [Vico](https://github.com/patrykandpatrick/vico)：Vico是一个功能强大且可扩展的多平台图表库。
* [React Native Graph](https://github.com/margelo/react-native-graph)：React Native Graph是基于高性能2D图形渲染引擎Skia的线图实现。
* [Charty](https://github.com/hi-manshu/charty)：一个简洁轻巧的Jetpack Compose图表库。
* [AAChartCore](https://github.com/AAChartModel/AAChartCore)：AAChartCore是AAChartKit的Java语言版本，是一套面向对象的、易于使用的、极其优雅的图形绘制控件，基于流行的开源前端图表库Highcharts。
* [AAInfographics](https://github.com/AAChartModel/AAChartCore-Kotlin)：AAInfographics是AAChartKit的Kotlin语言版本，是一套面向对象的、易于使用的、极其优雅的图形绘制控件，基于流行的开源前端图表库Highcharts。
* [React Native ECharts](https://github.com/wuba/react-native-echarts)：Apache Echarts的React Native版本，基于react-native-svg和react-native-skia，由58同城开源。
* [AChartEngine](https://github.com/ddanny/achartengine)：AChartEngine是一个适用于Android应用程序的图表库。
* [SectorProgressView](https://github.com/timqi/SectorProgressView)：一个使用圆形和扇形的Android简单进度提示或图表小部件。
* [YCharts](https://github.com/codeandtheory/YCharts)：YCharts是一个适用于Android的图库。
* [Compose Charts](https://github.com/ehsannarmani/ComposeCharts)：Jetpack Compose的动画和灵活实用图表。
* [AAY Chart](https://github.com/TheChance101/AAY-chart)：该库包含多个图表可组合项，可用于Kotlin Multiplatform项目和Android Native。
* [IkvStockChart](https://github.com/lbglobal/ikvStockChart)：一个简单的Android股票图表库。
* [RadarChartView](https://github.com/DmitriyZaitsev/RadarChartView)：用于渲染放射状图表的Android视图。
* [RadarChart](https://github.com/qstumn/RadarChart)：一个可以自由定制、旋转交互的Android雷达图库。
* [PercentageChartView](https://github.com/RamiJ3mli/PercentageChartView)：基于Java的易于使用且高度可调整的自定义视图，可显示单个给定任务的进度。
* [Charts](https://github.com/dautovicharis/charts)：这是一个使用Jetpack Compose构建的简单图表库。
* [Snake](https://github.com/txusballesteros/snake)：Snake库是适用于Android的简单动画折线图。
* [SmartChart](https://github.com/huangyanbin/SmartChart)： SmartChart是一个Android图表框架，支持线性图(折线，曲线，散点)柱状图、面积图、饼图、3D柱状图、雷达图、风向玫瑰图，支持图表多样化配置。
* [SparkLineLayout](https://github.com/majorkik/SparkLineLayout)：简单轻量级的迷你图/图表绘制库，支持标记和渐变。
* [Stfalcon PriceRangeBar](https://github.com/stfalcon-studio/StfalconPriceRangeBar-android)：用于添加价格范围图表的Android库，可灵活定制，由Stfalcon开发。
* [Sensify](https://github.com/JunkieLabs/sensify-android)：Jetpack Compose和Kotlin Flow中的MPAndroidChart。
* [StockChart](https://github.com/wangyiqian/StockChart)：StockChart一款适用于Android的高扩展性、高性能股票图/K线图开发库。
* [Android LineChart](https://github.com/jeanboydev/Android-LineChart)：一个简单的折线，贝塞尔曲线图表控件，高度可扩展，支持动态显示。
* [Compose Charts](https://github.com/bytebeats/compose-charts)：适用于多平台的简单Jetpack Compose Charts，包括Android、Web和桌面。
* [SlimChart](https://github.com/mancj/SlimChart)：SlimChart是一款轻量且易于使用的Android图表库。
* [LChart](https://github.com/linheimx/LChart)：这是一个折线图框架，它提供了几个非常实用的功能，简单易用。
* [Plot](https://github.com/Madrapps/plot)：具有不同图形和图表的Android Compose库。
* [Rings](https://github.com/lalongooo/rings)：一个简单的Android图表，包含三个指标和一个用于显示总体摘要的指标。
* [LiveChart](https://github.com/Pfuster12/LiveChart)：LiveChart是一个开源的Android库，用于绘制美观而强大的图表。
* [SuperChartView](https://github.com/Victory-Over/SuperChartView)：可滑动的自动回滚图表控件、自定义View属性、折线曲线图表。
* [Lightweight Charts Android](https://github.com/tradingview/lightweight-charts-android)：Android Lightweight Charts是TradingView Lightweight Charts库的Android包装器。
* [WeatherChartView](https://github.com/kaku2015/WeatherChartView)：适用于Android的简单天气折线图视图。
* [FlameBarChart](https://github.com/dyguests/FlameBarChart)：一个炫酷的柱状图表。
* [ArcChartView](https://github.com/imaNNeo/ArcChartView)：你可以使用这个库来绘制弧形图。
* [Timeline Chart View](https://github.com/jruesga/timeline-chart-view)：用于表示时间线上的数据的Android视图。
* [EasyScrollerChartView](https://github.com/aiceking/EasyScrollerChartView)：EasyScrollerChartView是一个自定义绘制内容，可滑动、惯性滑动、边界回弹、可点击的坐标系图。
* [GraphView](https://github.com/jjoe64/GraphView)：GraphView是一个Android库，用于以编程方式创建灵活且美观的图表。
* [HoloGraphLibrary](https://github.com/Androguide/HoloGraphLibrary)：这是一个库，旨在让你轻松地将精美的图形和图表集成到你的Android应用程序中。
* [DesCharts](https://github.com/bradipao/desCharts)：Android图表库。
* [NumAndroidCharts](https://github.com/numetriclabz/numAndroidCharts)：Numetric Technologies推出的强大Android图表库。
* [Finance.Android](https://github.com/ABTSoftware/Finance.Android)：Finance Charts SDK为原生iOS和Android应用添加了专业级财务图表功能。

#### Android日历库

* [SuperCalendar](https://github.com/MagicMashRoom/SuperCalendar)：Android自定义日历控件，支持左右无限滑动、周月切换、标记日期显示、自定义显示效果跳转到指定日期。
* [Material Calendar View](https://github.com/prolificinteractive/material-calendarview)：Android CalendarView的Material Design移植版。
* [CalendarView](https://github.com/huanghaibin-dev/CalendarView)：Android上一个优雅、万能自定义UI、仿iOS、自定义动画，支持垂直、水平方向切换、支持周视图、自定义周起始、性能高效的日历控件。
* [Calendar](https://github.com/kizitonwose/Calendar)：一个高度可定制的Android和Compose Multiplatform日历库，由用于视图系统的RecyclerView和用于撰写的LazyRow/LazyColumn支持。
* [TimesSquare](https://github.com/square/android-times-square)：独立的Android小部件，用于从日历视图中选择单个日期，由Square开发。
* [Android Week View](https://github.com/alamkanak/Android-Week-View)：Android Week View是一个Android库，用于在应用内显示日历(周视图或日视图)。
* [Simple Calendar](https://github.com/SimpleMobileTools/Simple-Calendar)：Simple Calendar 2023是一款高度可定制的Android离线月历应用程序。
* [NCalendar](https://github.com/yannecer/NCalendar)：一款安卓日历，仿MIUI、钉钉、华为的日历，万年历、365、周日历、月日历、月视图、周视图滑动切换。
* [CosmoCalendar](https://github.com/ApplikeySolutions/CosmoCalendar)：CosmoCalendar是一个完全可定制的日历，具有多种功能和显示模式。
* [CompactCalendarView](https://github.com/SundeepK/CompactCalendarView)：CompactCalendarView是一个简单的日历视图，可在月份之间滚动。
* [CalendarListview](https://github.com/traex/CalendarListview)：CalendarListview提供了一种使用日历选择日期的简便方法，适用于API 10及以上版本。
* [Caldroid](https://github.com/roomorama/Caldroid)：Caldroid是一个显示月份日期日历的片段。
* [Calendar](https://github.com/xiaojianglaile/Calendar)：Android日历，仿小米、华为、滴答清单、365日历。
* [AgendaCalendarView](https://github.com/Tibolte/AgendaCalendarView)：该库复制了Sunrise日历应用程序中日历和日程视图的基本功能，并结合了Google日历应用程序的一些小设计风格。
* [Horizontal Calendar](https://github.com/muraee/Horizontal-Calendar)：基于RecyclerView的Android Material水平日历视图。
* [CalendarExaple](https://github.com/codbking/CalendarExaple)：这是一个高仿钉钉和小米的日历控件，支持快速滑动、界面缓存。
* [CalendarListView](https://github.com/Kelin-Hong/CalendarListView)：自定义ListView与CalendarView相结合，相互交互。
* [Material Calendar View](https://github.com/Applandeo/Material-Calendar-View)：Material Calendar View是一款基于Material Design的简单且可定制的Android日历小部件。
* [React Native Calendar Events](https://github.com/wmcmahan/react-native-calendar-events)：React Native模块帮助访问和保存事件到iOS和Android日历。
* [Kalendar](https://github.com/hi-manshu/kalendar)：Kalendar是日历组件中的老魔杖，专为追求强大与优雅的Compose魔法师打造。
* [Date Range Picker](https://github.com/savvisingh/DateRangePicker)：Date Range Picker是一个日历选择器视图，用于显示自定义日期范围选择器，并改进了用户界面和功能，可以为日期添加字幕。
* [CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar)：精美的材质日历，具有无限滚动、范围选择等功能。
* [WeekCalendar](https://github.com/nomanr/WeekCalendar)：WeekCalendar是一个提供每周日历的库。
* [CollapseCalendarView](https://github.com/blazsolar/android-collapse-calendar-view)：CollapseCalendarView是一个开源Android库，允许开发者轻松地将日历添加到他们的应用中。
* [EasyCalendar](https://github.com/shichaohui/EasyCalendar)：你可以使用EasyCalendar快速获取日历风格的UI。
* [ExtendedCalendarView](https://github.com/tyczj/ExtendedCalendarView)：ExtendedCalendarView旨在可以显示日历并按日期显示事件。
* [PrimeDatePicker](https://github.com/aminography/PrimeDatePicker)：PrimeDatePicker是一款提供单日、多日和日期范围选择的工具。
* [Android Calendar Card](https://github.com/kenumir/android-calendar-card)：Android日历视图，简单易修改。
* [CalendarView](https://github.com/shehuan/CalendarView)：Android自定义日历控件。
* [LightCalendarView](https://github.com/recruit-mp/LightCalendarView)：一个轻量级的Android月历视图，完全用Kotlin编写。
* [Android Calendar View](https://github.com/myjoybar/android-calendar-view)：使用方便、易扩展的Android日历控件库。
* [Collapsible CalendarView](https://github.com/shrikanth7698/Collapsible-Calendar-View-Android)：Collapsible CalendarView是一个简单的日历视图，可以折叠以节省空间，并可以在需要时展开。
* [CalendarView](https://github.com/henry-newbie/CalendarView)：CalendarListview是一个高度定制的日期选择器，可以满足多选日期的需求。
* [SilkCal](https://github.com/NLMartian/SilkCal)：Android日历视图，受到日出日历和iOS7股票日历的启发。
* [SingleRowCalendar](https://github.com/misosvec/SingleRowCalendar)：用于水平单行日历的Android库。
* [Material Calendar View](https://github.com/BlackBoxVision/material-calendar-view)：MaterialCalendarView 是一款更漂亮、更简单的Material Design日历，允许完全自定义，并且向后兼容API 11+。
* [Compose Calendar](https://github.com/boguszpawlowski/ComposeCalendar)：Compose Calendar是一个可组合的组件，用于处理渲染日历组件和日期选择的所有复杂性。
* [Cadar](https://github.com/memfis19/Cadar)：Android解决方案，提供月历和列表日历视图，并支持显示事件-仅显示事件集和循环事件。
* [Calendar](https://github.com/lichao315/Calendar)：这是一个符合中国人使用习惯的Android上自定义日历控件。
* [PersianMaterialDateTimePicker](https://github.com/mohamad-amin/PersianMaterialDateTimePicker)：该库提供了一个hijri/shamsi(伊朗日历)日期选择器和一个正常时间选择器，它们是根据Google的Material Design Principals For Pickers为Android 4.0.3(API 15)+设计的。
* [OneCalendarView](https://github.com/darwin-morocho/OneCalendarView)：OneCalendarView是一个自定义CalendarView，允许Android开发人员在任何Android应用程序中拥有相同的CalendarView。
* [Calendar Picker](https://github.com/maxyou/CalendarPicker)：用于选择日期的日历选择器，可以预设所选日期。
* [GregorianLunarCalendar](https://github.com/Carbs0126/GregorianLunarCalendar)：GregorianLunarCalendar提供了农历、公历的日期选择模式，同时支持公历、农历的无缝切换。
* [CalendarDateRangePicker](https://github.com/ArchitShah248/CalendarDateRangePicker)：一个用于选择日期范围的Android库，可帮助用户从未来日期中选择范围。
* [MCalendarView](https://github.com/SpongeBobSun/mCalendarView)：可定制且可扩展的Android日历小部件。
* [Android Recurrence Picker](https://github.com/Shusshu/Android-RecurrencePicker)：Google日历重复选择器。
* [SunDatePicker](https://github.com/alirezaafkar/SunDatePicker)：伊朗日历的日期选择器。
* [EventsCalendar](https://github.com/tizisdeepan/EventsCalendar)：EventsCalendar是一个用户友好的库，可帮助你通过事件映射实现酷炫的日历UI。
* [Android CalendarView](https://github.com/SimonVT/android-calendarview)：Android CalendarView小部件移植到2.2。
* [CustomizableCalendar](https://github.com/MOLO17/CustomizableCalendar)：CustomizableCalendar是一个允许你创建日历、自定义UI和行为的库。
* [Roboto Calendar View](https://github.com/marcohc/roboto-calendar-view)：Android Roboto Calendar View使用出色的Calligraphy字体库，提供简单且可自定义的日历视图。
* [CalendarComponent](https://github.com/dengshiwei/CalendarComponent)：日历组件，包含了多个日历控件样式供使用，具有标识事务能力的一套日历组件。
* [Clean Simple Calendar](https://github.com/dpreussler/clean-simple-calendar)：小型简单的Android日历实现。
* [CalendarPager](https://github.com/ToDou/CalendarPager)：这是一个带有viewPager的水平日历。
* [CompactCalendarViewToolbar](https://github.com/kleisauke/CompactCalendarViewToolbar)：在Android Toolbar中使用CompactCalendarView库。
* [Android Week Calendar](https://github.com/chenyongci/Android-Week-Calendar)：Android可自定义日历方案，支持农历、自定义日历控件、排班、左右滑动、周月切换、跳转到指定日期等功能
* [MaterialCalendar](https://github.com/jMavarez/MaterialCalendar)：受School Diary的CalendarView启发的Material Design日历。
* [FlexibleCalendar](https://github.com/p-v/FlexibleCalendar)：适用于Android的可定制日历，具有可定制的事件。
* [CalendarSelector](https://github.com/TUBB/CalendarSelector)：用于选择日期的日历选择器，支持选择连续的时间段和一些不连续的日期。
* [Calendar365](https://github.com/haibuzou/Calendar365)：仿365的日历显示。
* [CalendarView](https://github.com/huangyanbin/CalendarView)：这是使用RecyclerView做的日历，比之前ViewPager不管从逻辑，功能更加强大，实现更加简单。
* [NestedCalendar](https://github.com/NanBox/NestedCalendar)：使MaterialCalendarView可以嵌套滚动，并平滑切换到周或月模式。
* [CalendarView](https://github.com/mahendramahi/CalendarView)：这是一个简单的自定义日历视图。
* [CalendarSelector](https://github.com/lvning/CalendarSelector)：仿淘宝预订日历。
* [ScrollerCalendar](https://github.com/guanchao/ScrollerCalendar)：ScrollerCalendar为Android 4.0+提供了查看日历的直接方式。
* [CalendarView](https://github.com/Airsaid/CalendarView)：Android平台上继承View实现的自定义日历控件。
* [Calendar](https://github.com/WojciechOsak/Calendar)：Kotlin多平台日历库。
* [Epic Calendar](https://github.com/epicarchitect/epic-calendar)：编写用于显示史诗日历的多平台库。
* [TaskProgressView](https://github.com/ibrahimsn98/taskprogressview)：适用于Android的轻量级日历任务进度视图库。
* [WeekCalendar](https://github.com/loonggg/WeekCalendar)：Android周日历库。
* [CustomCalendarView](https://github.com/StackTipsLab/custom-calendar-view)：CustomCalendarView提供了一个简单易用的可自定义日历，用于创建日历。
* [RecyclerCalendarAndroid](https://github.com/tejpratap46/RecyclerCalendarAndroid)：用Kotlin编写的Android DIY日历生成器库。
* [Expandable Compose Calendar](https://github.com/mateusz800/Expandable-Compose-Calendar)：用于渲染可扩展日历组件的Jetpack Compose库。
* [SuperCalendar](https://github.com/Cmahjong/SuperCalendar)：Android日历控件库。
* [Android CalendarView](https://github.com/laserwave/calendar_view)：一个显示日历的Android小部件。

#### Android布局库

* [FlexboxLayout](https://github.com/google/flexbox-layout)：FlexboxLayout是一个库项目，它为Android带来了类似CSS弹性框布局模块的功能，由Google开发。
* [Android Swipe Layout](https://github.com/daimajia/AndroidSwipeLayout)：最强大的滑动布局库。
* [VLayout](https://github.com/alibaba/vlayout)：VLayout是RecyclerView的一个强大的LayoutManager扩展，它为RecyclerView提供了一组布局，由阿里开源。
* [FlowLayout](https://github.com/hongyangAndroid/FlowLayout)：Android流式布局，支持单选、多选等，适合用于产品标签等。
* [CoordinatorTabLayout](https://github.com/hugeterry/CoordinatorTabLayout)：CoordinatorTabLayout是一个自定义复合控件，可以快速实现TabLayout与CoordinatorLayout的组合。
* [ChipsLayoutManager](https://github.com/Oleg-Beloy/ChipsLayoutManager)：自定义Recycler View的LayoutManager，当当前行没有剩余空间时，将元素移动到下一行。
* [CarouselLayoutManager](https://github.com/Azoft/CarouselLayoutManager)：Android轮播布局管理器(用于RecyclerView)。
* [DiagonalLayout](https://github.com/florent37/DiagonalLayout)：通过对角线布局探索Material Design的新风格和方法。
* [FlowLayout](https://github.com/nex3z/FlowLayout)：Android的FlowLayout，当空间不足时，允许子视图流到下一行。
* [TransformationLayout](https://github.com/skydoves/TransformationLayout)：使用容器变换动画将视图、活动和片段转换为其他组件。
* [ExpandableLayout](https://github.com/cachapa/ExpandableLayout)：一种Android布局类，支持对其子视图的展开和折叠进行动画处理。
* [BGASwipeBackLayout](https://github.com/bingoogolapple/BGASwipeBackLayout-Android)：Android Activity滑动返回，支持微信滑动返回样式、横屏滑动返回、全屏滑动返回。
* [AndroidPileLayout](https://github.com/xmuSistone/AndroidPileLayout)：一种异常的水平ListView式堆叠布局。
* [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout)：一个Android TabLayout库，目前有3个TabLayout。
* [Alerter](https://github.com/Tapadoo/Alerter)：该库旨在克服Toasts和Snackbars的局限性，同时降低布局的复杂性。
* [JKeyboardPanelSwitch](https://github.com/Jacksgong/JKeyboardPanelSwitch)：Android中键盘和面板布局冲突的处理程序。
* [SuperTextView](https://github.com/lygttpod/SuperTextView)：SuperTextView是一个功能强大的View，可以满足日常大部分布局样式，开发者可已自行组合属性配置出属于自己风格的样式。
* [ScalingLayout](https://github.com/iammert/ScalingLayout)：使用缩放布局可以根据用户交互缩放布局。
* [Android ViewBadger](https://github.com/jgilfelt/android-viewbadger)：一种在运行时“标记”任何给定Android视图的简单方法，无需在布局中迎合它。
* [ConsecutiveScrollerLayout](https://github.com/donkingliang/ConsecutiveScroller)：ConsecutiveScrollerLayout是Android下支持多个滑动布局(RecyclerView、ViewPager、WebView、ScrollView等)和普通控件(TextView、ImageView、LinearLayou、自定义View等)持续连贯滑动的容器，它使所有的子View像一个整体一样连续顺畅滑动。
* [GridListViewAdapters](https://github.com/birajpatel/GridListViewAdapters)：该库使你能够在ListView中实现类似卡片布局的GridView，并添加分页、添加页眉页脚视图等功能，还简化了列表和光标数据的实现。
* [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout)：自定义ViewPager标题条，在滚动时向用户提供持续反馈。
* [AndroidAutoLayout](https://github.com/hongyangAndroid/AndroidAutoLayout)：Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配。
* [SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)：一个Android库，可帮助你构建具有滑动返回手势的应用程序。
* [LayoutManagerGroup](https://github.com/DingMouRen/LayoutManagerGroup)：自定义RecyclerView的LayoutManager。
* [Android Percent Support Lib Sample](https://github.com/JulienGenoud/android-percent-support-lib-sample)：该库同时提供基于百分比的布局，水平和垂直。

#### Android富文本组件

* [RichEditor Android](https://github.com/wasabeef/richeditor-android)：RichEditor Android是一款适用于Android的精美富文本所见即所得编辑器。
* [RichText](https://github.com/zzhoujay/RichText)：Android平台下的富文本解析器，支持Html和Markdown。
* [Knife](https://github.com/mthli/Knife)：Knife是Android中用于编写文档的富文本编辑器组件。
* [Compose Rich Editor](https://github.com/MohamedRejeb/compose-rich-editor)：适用于Jetpack Compose和Compose Multiplatform的富文本编辑器库，完全可定制并支持常见的富文本编辑器功能。
* [Compose RichText](https://github.com/halilozercan/compose-richtext)：用于处理Markdown渲染和富文本格式的Compose库集合。
* [Android RichText Editor](https://github.com/chinalwb/Android-Rich-text-Editor)：Android富文本编辑器，支持自定义跨度。
* [Aztec](https://github.com/wordpress-mobile/AztecEditor-Android)：Aztec是一个用于在Android中编写HTML文档的富文本编辑器组件。
* [Android RTEditor](https://github.com/1gravity/Android-RTEditor)：Android RTEditor是Android的富文本编辑器组件，可以用作EditText的插件。
* [Dante](https://github.com/fourlastor/dante)：Dante是一个文本解析器，可以轻松地从原始输入生成Spannable。
* [FlexibleRichTextView](https://github.com/daquexian/FlexibleRichTextView)：该库用于显示各种富文本，包括LaTeX、图像、代码、表格以及居中、粗体、斜体等常规样式。
* [SortRichEditor](https://github.com/Hitomis/SortRichEditor)：支持图片文字混合编辑、排序的富文本编辑器。
* [RichEditor](https://github.com/RexSuper/RichEditor)：Android富文本编辑器。
* [PoorEdit](https://github.com/SpongeBobSun/PoorEdit)：Android版富文本编辑器。
* [RichEditText](https://github.com/KDF5000/RichEditText)：一个基于Android原生EditText的富文本组件，可以添加文字，插入图片。
* [RichTextEditor](https://github.com/huzhenjie/RichTextEditor)：适用于Android的富文本编辑器库。
* [RichText](https://github.com/oyd5201/RichText)：Android平台下一个原生的富文本编辑器，功能丰富、集成简单，可以转成HTML、删除图片、回退功能。
* [WordPress Editor Android](https://github.com/wordpress-mobile/WordPress-Editor-Android)：WordPress Editor Android是WordPress Android应用中用于创建和编辑页面及文章的文本编辑器。
* [RichEditText](https://github.com/chen-xiao-dong/RichEditText)：Android上一个富文本编辑视图，用于替换原生的EditText视图，它允许用户输入更多信息文本。
* [TextViewRichDrawable](https://github.com/a-tolstykh/textview-rich-drawable)：
* [MarkdownEditText](https://github.com/YahiaAngelo/MarkdownEditText)：基于Markwon库的Android原生富文本编辑器，具有导出到Markdown选项。

#### Android下拉刷新

* [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)：SmartRefreshLayout以打造一个强大、稳定、成熟的下拉刷新框架为目标，并集成各种的炫酷、多样、实用、美观的Header和Footer。
* [BGARefreshLayout Android](https://github.com/bingoogolapple/BGARefreshLayout-Android)：开发者使用BGARefreshLayout Android可以对各种控件实现多种下拉刷新效果、上拉加载更多以及配置自定义头部广告位。
* [TwinklingRefreshLayout](https://github.com/lcodecorex/TwinklingRefreshLayout)：TwinklingRefreshLayout扩展了SwipeRefreshLayout的思想，使用ViewGroup来包含View列表，保持了SwipeRefreshLayout的低耦合性和高通用性。
* [Ultra Pull To Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)：Android超级下拉刷新，支持所有视图。
* [Android Pull To Refresh](https://github.com/chrisbanes/Android-PullToRefresh)：该项目旨在为Android提供可重复使用的下拉刷新小部件。
* [Phoenix](https://github.com/Yalantis/Phoenix)：Phoenix下拉刷新。
* [LRecyclerView](https://github.com/jdsjlzx/LRecyclerView)：LRecyclerView是支持addHeaderView、addFooterView、下拉刷新、分页加载数据的RecyclerView。
* [XRefreshView](https://github.com/huxq17/XRefreshView)：一个万能的Android下拉上拉刷新的框架，完美支持RecyclerView。
* [MVCHelper](https://github.com/LuckyJayce/MVCHelper)：MVCHelper主要用于下拉刷新加载、失败、加载、空数据、成功的界面切换。
* [PullLoadMoreRecyclerView](https://github.com/WuXiaolong/PullLoadMoreRecyclerView)：实现RecyclerView下拉刷新和上拉加载更多以及RecyclerView线性、网格、瀑布流效果演示。
* [FunGameRefresh](https://github.com/Hitomis/FunGameRefresh)：有趣好玩的下拉刷新库。
* [SmoothRefreshLayout](https://github.com/dkzwm/SmoothRefreshLayout)：一个高效的Android刷新库，理论上支持所有的视图，比官方的SwipeRefreshLayout更强大且使用方便。
* [EasyBehavior](https://github.com/JmStefanAndroid/EasyBehavior)：一个可以上拉下滑的UI效果。
* [ActionBar PullToRefresh](https://github.com/chrisbanes/ActionBar-PullToRefresh)：ActionBar PullToRefresh提供了一种简单的方法来向你的应用程序添加现代版本的下拉刷新交互。
* [Android PullToRefresh](https://github.com/johannilsson/android-pulltorefresh)：该项目旨在为Android提供可重复使用的下拉刷新小部件。
* [SwipyRefreshLayout](https://github.com/omadahealth/SwipyRefreshLayout)：SwipeRefreshLayout扩展允许双向滑动。
* [BeautifulRefreshLayout](https://github.com/android-cjj/BeautifulRefreshLayout)：漂亮的RefreshLayout。
* [MaterialRefreshLayout](https://github.com/android-cjj/Android-MaterialRefreshLayout)：这是一个下拉刷新控件，比SwipeRefreshLayout更美观、功能更强大，使用简单。
* [SwipeToLoadLayout](https://github.com/Aspsine/SwipeToLoadLayout)：SwipeToLoadLayout是一个可重复使用的下拉刷新和下拉加载更多小部件。
* [Android PullRefreshLayout](https://github.com/baoyongzhang/android-PullRefreshLayout)：这个组件类似于SwipeRefreshLayout，但是比SwipeRefreshLayout更美观。
* [EasyRecyclerView](https://github.com/Jude95/EasyRecyclerView)：将开发中常用的RecyclerView的各种需求封装进库。
* [SuperRecyclerView](https://github.com/Malinskiy/SuperRecyclerView)：这是为了让RecyclerView更易于使用的一次尝试。
* [SpringView](https://github.com/liaoinstan/SpringView)：SpringView是一个提供上下拉拖拽功能的组件，可以高度定制，实现各种下拉\拉画效果。
* [WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)：该项目旨在为Android提供可重复使用的WaveSwipe刷新小部件。
* [CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout)：这是一个具有自定义下拉刷新布局的项目，其中包含有趣的动画。
* [RecyclerRefreshLayout](https://github.com/dinuscxj/RecyclerRefreshLayout)：一个用于Android的下拉刷新布局，RecyclerRefreshLayout基于SwipeRefreshLayout。
* [Taurus](https://github.com/Yalantis/Taurus)：该项目旨在提供一个简单且可定制的下拉刷新实现。
* [PullToMakeSoup](https://github.com/Yalantis/pull-to-make-soup)：可轻松添加到RecyclerView的自定义动画下拉刷新。
* [SuperSwipeRefreshLayout](https://github.com/nuptboyzhb/SuperSwipeRefreshLayout)：自定义SwipeRefreshLayout以支持下拉刷新功能。
* [CommonPullToRefresh](https://github.com/Chanven/CommonPullToRefresh)：Android小部件具有可下拉刷新所有视图的功能，并支持ListView、RecyclerView、GridView和SwipeRefreshLayout的loadMore功能。
* [FlyRefresh](https://github.com/race604/FlyRefresh)：Replace的Android实现，由Zee Youn设计。
* [XListView](https://github.com/Maxwin-z/XListView-Android)：ListView支持下拉刷新和上拉加载更多功能。
* [PullToRefreshAndLoad](https://github.com/jingchenUSTC/PullToRefreshAndLoad)：Android下拉刷新上拉加载控件，对所有View通用。
* [IRecyclerView](https://github.com/Aspsine/IRecyclerView)：IRecyclerView是一个自定义的RecyclerView，支持下拉刷新、下拉加载更多、自定义刷新页眉和加载更多页脚、添加页眉视图和页脚视图。
* [PullToRefresh](https://github.com/MarkMjw/PullToRefresh)：根据Maxwin的XListView改造而来，完善下拉刷新上拉加载更多的功能并实现自动刷新以及自动加载等功能，并增加对ScrollView的支持。
* [PullRefreshLayout](https://github.com/genius158/PullRefreshLayout)：PullRefreshLayout是一个专注回弹和手势操作无阻塞的刷新库。
* [EasyRefreshLayout](https://github.com/anzaizai/EasyRefreshLayout)：继承此库可以让你轻松实现下拉刷新和上传。
* [FireworkyPullToRefresh](https://github.com/Cleveroad/FireworkyPullToRefresh)：使用此库可以刷新你的数据。
* [PullToRefresh ListView](https://github.com/erikwt/PullToRefresh-ListView)：一个通用、可定制、开源的Android ListView实现，具有下拉刷新功能。
* [JellyRefreshLayout](https://github.com/imallan/JellyRefreshLayout)：受Lollipop滚动效果启发的下拉刷新布局。
* [AnimRefreshRecyclerView](https://github.com/shichaohui/AnimRefreshRecyclerView)：下拉刷新和上拉加载更多的RecyclerView，具有下拉和刷新动画。
* [PullToRefresh](https://github.com/lumenghz/PullToRefresh)：PullToRefresh小部件。
* [Android PullToRefresh And LoadMore](https://github.com/shontauro-zz/android-pulltorefresh-and-loadmore)：Android自定义ListView，使用加载更多和下拉刷新的交互模式动态加载数据。
* [BeerSwipeRefresh](https://github.com/recruit-lifestyle/BeerSwipeRefresh)：该项目旨在为Android系统提供一个可重复使用的滑动刷新小部件。
* [Android PullToRefreshRecyclerView](https://github.com/HomHomLin/Android-PullToRefreshRecyclerView)：这是一个基于RecyclerView的具有下拉刷新功能的项目。
* [SwipeRefreshLayout](https://github.com/hanks-zyh/SwipeRefreshLayout)：SwipeRefreshLayout是一个下拉刷新控件，几乎可以包裹一个任何可以滚动的内容，可以自动识别垂直滚动手势。
* [CanRefresh](https://github.com/canyinghao/CanRefresh)：可适配所有视图的下拉刷新上拉加载，并支持各种风格。
* [PullToRefresh](https://github.com/lynnchurch/PullToRefresh)：一个可下拉刷新与上拉加载更多的库。
* [AlipayPullRefresh](https://github.com/xmuSistone/AlipayPullRefresh)：支付宝首页下拉刷新。
* [CRefreshLayout](https://github.com/cloay/CRefreshLayout)：受CBStoreHouseRefreshControl启发的令人惊叹的Android拉刷新布局。
* [PullRefreshView](https://github.com/pierreown/PullRefreshView)：方便快捷的帮滑动控件添加弹性阻尼和下拉刷新、上拉加载的功能。
* [SHSwipeRefreshLayout](https://github.com/miomin/SHSwipeRefreshLayout)：Android升级版SwipeRefreshLayout，支持RecyclerView、ScrollView等大部分组件，下拉刷新和上拉加载，支持自定义HeaderView和FooterView。
* [MeiTuanRefreshListView](https://github.com/nugongshou110/MeiTuanRefreshListView)：仿美团下拉刷新。
* [UltraSwipeRefresh](https://github.com/jenly1314/UltraSwipeRefresh)：UltraSwipeRefresh是一个可带来极致体验的Compose刷新组件。
* [GmailLikePullToRefresh](https://github.com/learnNcode/GmailLikePullToRefresh)：类似Gmail的下拉刷新实现。
* [SmileRefresh](https://github.com/hsongxian/SmileRefresh)：微笑下拉刷新，这是在SwipeRefreshLayout基础上修改的下拉刷新库。
* [PullLoadView](https://github.com/tosslife/PullLoadView)：下拉刷新和加载更多RecyclerView。
* [SpringHeader](https://github.com/loopeer/SpringHeader)：使用CoordinatorLayout实现类似spring的标题(称为下拉刷新)。
* [AutoHomeRefreshListView](https://github.com/nugongshou110/AutoHomeRefreshListView)：仿汽车之家下拉刷新。
* [EasyPullLayout](https://github.com/huzenan/EasyPullLayout)：轻量级下拉刷新布局，支持垂直和水平。
* [CustomRefreshView](https://github.com/zhangtuodd/CustomRefreshView)：一个支持网络错误重试、无数据页、无网络界面的上拉加载更多，下拉刷新控件。
* [RefreshNow](https://github.com/mariotaku/RefreshNow)：Google Now风格下拉刷新。
* [CommonRefreshLayout](https://github.com/mylhyl/Android-CommonRefreshLayout)：基于SwipeRefreshLayout下拉刷新、上拉加载支持的AbsListView、RecycleView、WebView。
* [SimpleRecyclerView](https://github.com/xingda920813/SimpleRecyclerView)：RecyclerView和SwipeRefreshLayout的增强功能。
* [Compose RefreshLayout](https://github.com/RicardoJiang/compose-refreshlayout)：Compose版SmartRefreshLayout。
* [BaiduGoingRefreshLayout](https://github.com/Hankkin/BaiduGoingRefreshLayout)：仿百度外卖下拉刷新动画。
* [Liquid Refresh Layout](https://github.com/mukeshsolanki/liquidrefreshlayout)：Liquid Refresh Layout是一个简单的SwipeToRefresh库，可帮助你轻松集成SwipeToRefresh并执行简单干净的液体动画。
* [SSPullToRefresh](https://github.com/SimformSolutionsPvtLtd/SSPullToRefresh)：SSPullToRefresh使PullRefresh易于使用，你可以提供自己的自定义动画或在刷新视图上设置简单的GIF。
* [Nest Refresh](https://github.com/ToDou/nestrefresh)：Nest Scroll的Android刷新套件，通过行为实现下拉刷新和下拉加载更多功能。
* [RecyclerViewTools](https://github.com/eyeem/RecyclerViewTools)：RecyclerView的工具集合，包括标题栏、区块、下拉刷新等。

#### Android项目模板

* [Rosie](https://github.com/Karumi/Rosie)：Rosie是一个Android框架，用于创建遵循清洁架构原则的应用程序。
* [Android CleanArchitecture](https://github.com/android10/Android-CleanArchitecture)：这是一个示例应用程序，关于如何使用Uncle Bob的清洁架构方法构建Android应用程序。
* [Android Clean Architecture Boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate)：使用清洁架构的Android样板项目。
* [Android Clean Boilerplate](https://github.com/dmilicic/Android-Clean-Boilerplate)：这是使用清洁架构编写Android应用程序的入门模板。
* [Android Boilerplate](https://github.com/hitherejoe/Android-Boilerplate)：一个简单的样板应用程序，演示了数据的下载、保存和同步-以应用程序中使用的通用布局显示。
* [Android Clean Architecture Components Boilerplate](https://github.com/bufferapp/clean-architecture-components-boilerplate)：这是原始Clean Architecture Boilerplate的一个分支，已将表示层中的MVP方法切换为使用Android Architecture Components Library中的ViewModels。

#### Android图像库

* [Glide](https://github.com/bumptech/glide)：Glide是一个快速高效的Android开源媒体管理和图像加载框架，它将媒体解码、内存和磁盘缓存以及资源池整合到一个简单易用的界面中。
* [Picasso](https://github.com/square/picasso)：Picasso是一个强大的Android图像下载和缓存库，由Square开源。
* [Fresco](https://github.com/facebook/fresco)：Fresco是一个用于在Android应用程序中显示图像的强大的系统，由Facebook开源。
* [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader)：用于在Android上加载、缓存和显示图像的强大而灵活的库。
* [uCrop](https://github.com/Yalantis/uCrop)：Android图像裁剪库。
* [Coil](https://github.com/coil-kt/coil)：适用于Android和Compose Multiplatform的图像加载库。
* [Glide Transformations](https://github.com/wasabeef/glide-transformations)：一个Android转换库，为Glide提供各种图像转换。
* [Subsampling Scale Image View](https://github.com/davemorrissey/subsampling-scale-image-view)：专为Android打造的自定义图像视图，专为照片库设计，可显示巨幅图像(例如地图和建筑平面图)，且不会出现OutOfMemoryError错误。
* [Android Image Cropper](https://github.com/ArthurHub/Android-Image-Cropper)：适用于Android的图像裁剪库，针对相机/图库进行了优化。
* [Ion](https://github.com/koush/ion)：Android异步网络和图像加载。
* [MagicCamera](https://github.com/wuhaoyu1990/MagicCamera)：适用于Android的实时滤镜相机和视频录制器以及具有美颜功能的图像编辑器。
* [Android Crop](https://github.com/jdamcd/android-crop)：一个基于AOSP代码的Android库项目，提供简单的图像裁剪活动。
* [PhotoEditor](https://github.com/burhanrashid52/PhotoEditor)：一个照片编辑器库，支持使用绘画、文本、过滤器、表情符号和贴纸等简单、轻松地进行图像编辑。
* [BitmapCache](https://github.com/chrisbanes/Android-BitmapCache)：BitmapCache是一种专用缓存，用于Android位图对象。

#### Android ImageView

* [PhotoView](https://github.com/Baseflow/PhotoView)：PhotoView旨在帮助生成一个易于使用的缩放Android ImageView实现。
* [CircleImageView](https://github.com/hdodenhof/CircleImageView)：一个快速的圆形ImageView，非常适合用于头像。
* [RoundedImageView](https://github.com/vinc3m1/RoundedImageView)：支持圆角、椭圆和圆形的快速ImageView。
* [TouchImageView](https://github.com/MikeOrtiz/TouchImageView)：为Android ImageView添加触摸功能。
* [TextDrawable](https://github.com/amulyakhare/TextDrawable)：TextDrawable这个轻量级库提供带有字母/文本的图像，就像Gmail应用程序一样。
* [KenBurnsView](https://github.com/flavioarfaria/KenBurnsView)：Android库为ImageView提供了扩展，通过使用Ken Burns效果为其可绘制内容制作动画来创造身临其境的体验。
* [Shape Image View](https://github.com/siyamed/android-shape-imageview)：提供一组自定义形状的Android ImageView组件，以及一个用于定义更多形状的框架。

#### Android选择器

* [AndroidPicker](https://github.com/gzu-liyujiang/AndroidPicker)：安卓选择器类库，包括日期及时间选择器、单项选择器、二三级联动选择器、城市地址选择器、数字选择器、日历选日期择器、颜色选择器、文件及目录选择器、图片选择器等。
* [Android BetterPickers](https://github.com/code-troopers/android-betterpickers)：用于更好的Picker DialogFragments的Android库。
* [React Native Picker](https://github.com/beefe/react-native-picker)：高性能的Native Picker。
* [Android Pickers](https://github.com/addappcn/android-pickers)：安卓选择器类库，包括日期及时间选择器、单项选择器、城市地址选择器、数字选择器等、
* [CharacterPickerView](https://github.com/imkarl/CharacterPickerView)：可实现三级联动的选择器，高仿iOS的滚轮控件，字体大小自适应。
* [Compose Material Dialogs](https://github.com/PranavMaganti/compose-material-dialogs)：易于使用的库，可帮助你使用Jetpack Compose构建复杂的对话框。
* [TeaPickerView](https://github.com/YangsBryant/TeaPickerView)：数据级联选择器、层级结构、多数据筛选、必藏。
* [PickerUI](https://github.com/DavidPizarro/PickerUI)：Android库，用于显示项目列表以供选择，并带有模糊效果。
* [RubberPicker](https://github.com/Chrisvin/RubberPicker)：RubberPicker库包含RubberSeekBar和RubberRangePicker。
* [Collection Picker](https://github.com/anton46/Foursquare-CollectionPicker)：Collection Picker是一个Android View库，外观类似Foursquare的Tastes Picker。
* [Icon Picker Dialog](https://github.com/maltaisn/icondialoglib)：一个完全可自定义的图标选择器对话框，让你轻松访问优质图标，无需单独添加图标到项目中。

#### Android图片/视频选择器

* [PictureSelector](https://github.com/LuckSiege/PictureSelector)：一个Android平台的图片选择器，支持从相册获取图片、视频、音频、照片、裁剪、压缩、主题自定义配置等功能。
* [PickerView](https://github.com/Bigkoo/Android-PickerView)：这是一款仿iOS的PickerView控件，有时间选择器和选项选择器。
* [Matisse](https://github.com/zhihu/Matisse)：Matisse是一款专为Android设计的本地图像和视频选择器，由知乎开源。
* [Boxing](https://github.com/bilibili/boxing)：基于MVP模式的Android多媒体选择器，由B站开源。
* [React Native Image Picker](https://github.com/react-native-image-picker/react-native-image-picker)：React Native模块允许你从设备库或相机中选择照片/视频。
* [ImagePicker](https://github.com/jeasonlzy/ImagePicker)：Android自定义相册，完全仿微信UI，实现了拍照、图片选择(单选/多选)、裁剪 、旋转、等功能。
* [MultiImageSelector](https://github.com/lovetuzitong/MultiImageSelector)：适用于Android设备的图像选择器，支持单选和多选。
* [PhotoPicker](https://github.com/donglua/PhotoPicker)：类似微信的图片选择器。
* [BGAPhotoPicker Android](https://github.com/bingoogolapple/BGAPhotoPicker-Android)：Android图片选择、预览、九宫格图片控件、拖拽排序九宫格图片控件。
* [ImageSelector](https://github.com/smuyyh/ImageSelector)：Android图片选择器。
* [Image Picker](https://github.com/Dhaval2404/ImagePicker)：易于使用和可配置的库，可从图库中选择图像或使用相机捕获图像。
* [YImagePicker](https://github.com/yangpeixing/YImagePicker)：小红书多图剪裁、微信图片选择器、大图预览、图片剪裁。
* [RxImagePicker](https://github.com/qingmei2/RxImagePicker)：灵活的Android图片选择器，提供了知乎和微信主题的支持。
* [TedBottomPicker](https://github.com/ParkSangGwon/TedBottomPicker)：TedBottomPicker是使用底部表单的简单图像选择器。
* [ImagePicker](https://github.com/martin90s/ImagePicker)：Super Image Picker是一款功能强大的图片选择器。
* [PixImagePicker](https://github.com/akshay2211/PixImagePicker)：Pix是WhatsApp图像选择器的副本。
* [InsGallery](https://github.com/JessYanCoding/InsGallery)：一款UI炫酷高仿Instagram的图片、视频选择器。
* [FishBun](https://github.com/sangcomz/FishBun)：FishBun是一款高度可定制的Android图像选择器。
* [React Native Image Picker](https://github.com/syanbo/react-native-syan-image-picker)：React Native多图片选择，支持裁剪、压缩。
* [ImagePicker](https://github.com/nguyenhoanglam/ImagePicker)：一个Android库，允许你通过便捷的UI自定义从设备库或相机中选择图像。
* [Louvre](https://github.com/andremion/Louvre)：一个小型可定制库，可用于处理应用程序内置的图库图像选择操作。
* [RxGalleryFinal](https://github.com/FinalTeam/RxGalleryFinal)：RxGalleryFinal是一个Android图片/视频文件选择器。
* [TedImagePicker](https://github.com/ParkSangGwon/TedImagePicker)：TedImagePicker是一款简单/美观/智能的图像选择器。
* [RxPaparazzo](https://github.com/miguelbcr/RxPaparazzo)：Android的RxJava扩展可使用相机拍照、从设备中选择文件或照片以及选择性地裁剪或旋转任何选定的图像。
* [PickPhotoView](https://github.com/werbhelius/PickPhotoSample)：Android库的照片选择器。
* [ImagePicker](https://github.com/Lichenwei-Dev/ImagePicker)：高仿微信图片选择器。
* [AndroidPicturePicker](https://github.com/ValuesFeng/AndroidPicturePicker)：Android强大的图片选择器。
* [PolyPicker](https://github.com/jaydeepw/poly-picker)：用于从设备选择/捕获多幅图像的Android库项目。
* [ImageSelector](https://github.com/ioneday/ImageSelector)：Android的图片选择器库，支持单选、多选、裁剪图片和预览图片。
* [ChiliPhotoPicker](https://github.com/ChiliLabs/ChiliPhotoPicker)：安卓照片选择器库，可直接从文件中选择照片，或导航至相机或图库。
* [AndroidImagePicker](https://github.com/easonline/AndroidImagePicker)：一个适用于Android的图像选择器。
* [MultiImagePicker](https://github.com/yazeed44/MultiImagePicker)：Android中用于选择多张图片的库。
* [Unsplash Photo Picker](https://github.com/unsplash/unsplash-photopicker-android)：UnsplashPhotoPicker是一个Android UI组件，只需几行代码即可让你快速在Unsplash库中搜索免费的高质量照片。
* [RxPicker](https://github.com/imuhao/RxPicker)：基于RxJava的ImageSelect工具。
* [Peekaboo](https://github.com/onseok/peekaboo)：Compose Multiplatform的Kotlin Multiplatform库，旨在在iOS和Android应用程序中无缝集成图像选择器功能。
* [RxImagePicker](https://github.com/MLSDev/RxImagePicker)：使用RxJava2在Android M上请求运行时权限从图库或相机获取图像的简单方法。
* [PhotoPicker](https://github.com/liuling07/PhotoPicker)：一个从图库中挑选照片的Android库。
* [BottomSheet Image Picker](https://github.com/kroegerama/bottomsheet-imagepicker)：一个以BottomSheet形式实现的现代图像选择器。
* [SSImagePicker](https://github.com/SimformSolutionsPvtLtd/SSImagePicker)：易于使用和可配置的库，可从图库中选择多张图像或使用具有最大尺寸、扩展、裁剪、旋转、缩放和压缩功能的相机捕获图像。
* [TimeRangePicker](https://github.com/Droppers/TimeRangePicker)：一个可自定义、易于使用且功能强大的Android圆形时间范围选择器库。
* [ImageShowPicker](https://github.com/yaozs/ImageShowPicker)：单纯的上传图片展示控件。
* [TedPicker](https://github.com/ParkSangGwon/TedPicker)：TedPicker是适用于Android的图像选择器库，它允许你轻松地从图库或相机中拍摄照片，而无需使用大量样板代码。
* [MediaPicker](https://github.com/alhazmy13/MediaPicker)：Media Picker是一个Android库，可让你选择多个图像或视频。
* [ImagePicker](https://github.com/CYRUS-STUDIO/ImagePicker)：Android下的图片选择与裁剪开源库。
* [ImagePicker](https://github.com/Drjacky/ImagePicker)：Android图像选择器，从图库中选择图像或使用相机拍摄新图像。
* [Lassi Android](https://github.com/Mindinventory/Lassi-Android)：Lassi是选择媒体(图像、视频、音频或文档)的最简单方法。
* [Android ImagesPickers](https://github.com/jaikydota/Android-ImagesPickers)：Android ImagesPickers是一个集图片选择(单选/多选)、拍照、裁剪、图片预览、图片显示容器的图片选择显示工具。
* [BSImagePicker](https://github.com/siralam/BSImagePicker)：扩展BottomSheetDialogFragment的图像选择器。
* [Multiple Media Picker](https://github.com/erikagtierrez/multiple-media-picker)：一个Android库，用于从内置图库中挑选多张图片和/或视频。
* [Media Picker](https://github.com/robertlevonyan/media-picker)：轻松定制的选择器，满足你在Android应用程序中的所有需求。
* [Android Media Picker](https://github.com/tungdx/android-media-picker)：用于从Android设备中选择照片、视频的库。
* [MediaPickerPoject](https://github.com/DmcSDK/MediaPickerPoject)：仿微信视频图片选择器。
* [Thumby](https://github.com/bufferapp/Thumby)：Thumby是一款易于使用的Android嵌入式视频缩略图选择器。
* [SmartMediaPicker](https://github.com/BzCoder/SmartMediaPicker)：一款方便好用的仿微信多媒体选择器，集合图片选择、拍照、拍摄短视频功能。
* [Awesome Image Picker](https://github.com/myinnos/AwesomeImagePicker)：超棒的图片选择器库，界面美观，可快速选择图片/动图。
* [ImagePicker](https://github.com/Mariovc/ImagePicker)：ImagePicker是一个Android库，可以轻松地从图库或相机应用中选择图像。
* [Gligar](https://github.com/OpenSooq/Gligar)：Gliger是一个适用于Android的简单、轻量级且高性能的图像选择器库。
* [InstagramPhotoPicker](https://github.com/Skykai521/InstagramPhotoPicker)：类似Instagram的照片选择器功能。
* [LQRImagePicker](https://github.com/GitLqr/LQRImagePicker)：完全仿微信的图片选择。
* [Belvedere](https://github.com/zendesk/belvedere)：Android的图像选择器库。
* [UW Media Picker Android](https://github.com/AnilFurkanOkcun/UWMediaPicker-Android)：易于使用且可定制的媒体选择器库，可为Android选择多个图像(带压缩)和视频。
* [PhotoPicker](https://github.com/CNCoderX/PhotoPicker)：简洁、高效的Android图片选择库，支持图片压缩、裁剪，支持多图选择。
* [GalleryPicker](https://github.com/tizisdeepan/GalleryPicker)：Gallery Picker允许你在Android项目中为图像/视频选择器设计自定义图库。
* [LPhotoPicker](https://github.com/limuyang2/LPhotoPicker)：这是一个漂亮、纯粹的AndroidX图片选择框架。
* [MediaPicker](https://github.com/FunkyMuse/MediaPicker)：Kotlin Android库用于选择图像、视频和音频。
* [PhotoPicker](https://github.com/yudu233/PhotoPicker)：Android照片选择器，支持单图、多图、视频、GIF选择，内置鲁班压缩和Ucrop裁剪功能，以及主题自定义配置等功能。
* [ContentManager](https://github.com/stfalcon-studio/ContentManager)：用于从设备图库、外部存储、云端(Google Drive、Dropbox等)或相机获取任何类型的照片、视频或文件的库。
* [PhotoPicker](https://github.com/q805699513/PhotoPicker)：一款Android图片选择器，支持直接拍照、拍照并裁剪、单选裁剪、图片多选、图片放大预览、裁剪比例设置等。
* [Picker](https://github.com/Parag2385/Picker)：基于CameraX的WhatsApp风格图像视频选择器。
* [Android Multipicker Library](https://github.com/coomar2841/android-multipicker-library)：Android多选器库。

#### Android颜色选择器

* [ColorPickerView](https://github.com/skydoves/ColorPickerView)：Android颜色选择器，通过点击所需颜色从任何图像中获取颜色。
* [Color Picker](https://github.com/QuadFlask/colorpicker)：带有色轮和亮度条的简单Android颜色选择器。
* [HoloColorPicker](https://github.com/LarsWerkman/HoloColorPicker)：由Marie Schweiz设计的Android Holo主题颜色选择器。
* [ColorPicker](https://github.com/jaredrummler/ColorPicker)：适用于Android的高度可定制的颜色选择器。
* [ColorPickerPreference](https://github.com/attenzione/android-ColorPickerPreference)：安卓系统ColorPickerPreference，用于在偏好设置中创建颜色选择器。
* [ColorPicker Compose](https://github.com/skydoves/colorpicker-compose)：Kotlin多平台颜色选择器库，允许你通过点击所需的颜色从任何图像中获取颜色。
* [Sketchbook Compose](https://github.com/GetStream/sketchbook-compose)：Jetpack Compose画布库可帮助你使用颜色选择器和调色板在画布上绘制路径和图像。
* [Compose Color Picker](https://github.com/godaddy/compose-color-picker)：用Jetpack Compose编写的提供两个不同HSV颜色选择器的组件。
* [Color Picker Collection](https://github.com/gabrielemariotti/colorpickercollection)：该存储库提供了一个简单的颜色选择器集合。
* [ColorPicker](https://github.com/duanhong169/ColorPicker)：Android版ColorPicker，使用色轮和滑块选择颜色。
* [Android Color Picker](https://github.com/side-codes/Android-Color-Picker)：Android的颜色选择器库。
* [Color Preference](https://github.com/kizitonwose/colorpreference)：一个用于在偏好设置屏幕中创建漂亮的颜色选择器的Android库。
* [ColorPicker](https://github.com/Dhaval2404/ColorPicker)：Android颜色选择器库。
* [HSV-Alpha Color Picker Android](https://github.com/martin-stone/hsv-alpha-color-picker-android)：该库实现了颜色选择器和颜色偏好，可用于Android应用程序。
* [AndroidPhotoshopColorPicker](https://github.com/aziztitu/AndroidPhotoshopColorPicker)：适用于Android的功能齐全的颜色选择器库。
* [AmbilWarna](https://github.com/yukuku/ambilwarna)：Android颜色选择器。
* [ColorSheet](https://github.com/msasikanth/ColorSheet)：底部颜色选择器。
* [Color Picker Android](https://github.com/chiralcode/Android-Color-Picker)：易于使用、功能齐全的颜色选择器，基于HSV颜色模型，设计紧凑。
* [ColorPicker](https://github.com/kristiyanP/colorpicker)：一个简单的Android颜色选择器库。
* [ColorPicker](https://github.com/DingMouRen/ColorPicker)：ColorPicker是一款为Android项目提供的取色器。
* [Pikolo](https://github.com/Madrapps/Pikolo)：一个Android颜色选择器库。
* [ShiftColorPicker](https://github.com/DASAR-zz/ShiftColorPicker)：Android的简单颜色选择器视图。
* [ColorPickerView](https://github.com/danielnilsson9/color-picker-view)：一个简单好看的Android颜色选择器组件。
* [ColorPickerDialog](https://github.com/fennifith/ColorPickerDialog)：ColorPickerDialog是一个简单的对话框，可以快速轻松地向任何应用程序添加颜色选择器功能。
* [ColorSeekBar](https://github.com/divyanshub024/ColorSeekBar)：适用于Android的颜色选择器搜索栏。
* [Multi ColorPicker](https://github.com/skydoves/Multi-ColorPicker)：Android多颜色选择器，通过点击所需颜色从任何图像中获取颜色。
* [Chroma](https://github.com/ItsPriyesh/chroma)：用Kotlin编写的用于Android的简单、轻量级颜色选择器。
* [ColorPickerPreference](https://github.com/skydoves/ColorPickerPreference)：一个允许你实现ColorPickerView、ColorPickerDialog、ColorPickerPreference的库。

#### Android日期/时间选择器

* [Material DateTime Picker](https://github.com/wdullaer/MaterialDateTimePicker)：Material DateTime Picker尝试为你提供Material Design规范中所示的日期和时间选择器，以及一个简单的主题API。
* [React Native Date Picker](https://github.com/henninghall/react-native-date-picker)：React Native Date Picker是适用于Android和iOS的日期时间选择器。
* [SublimePicker](https://github.com/vikramkakkar/SublimePicker)：可定制的视图，提供日期、时间和重复选项的选择，所有这些都来自单个用户界面。
* [DatePicker](https://github.com/devaige/DatePicker)：实用且强大的Android日期选择器。
* [TimePickerDialog](https://github.com/JZXiang/TimePickerDialog)：Android时间选择器库。
* [Material Date Range Picker](https://github.com/heysupratim/material-daterange-picker)：基于wdullaers MaterialDateTimePicker的Material日期范围选择器。
* [DateTimePicker](https://github.com/loper7/DateTimePicker)：一个高颜值日期时间选择器。
* [BottomSheetPickers](https://github.com/philliphsu/BottomSheetPickers)：BottomSheetPickers是适用于Android的新日期和时间选择器库，支持API 14及更高版本。
* [SingleDateAndTimePicker](https://github.com/florent37/SingleDateAndTimePicker)：只需一个小部件即可选择日期和时间。
* [SlideDateTimePicker](https://github.com/jjobes/SlideDateTimePicker)：SlideDateTimePicker是一个Android库，它显示一个DialogFragment，用户可以在其中选择日期和时间。
* [DateRangePicker](https://github.com/savvisingh/DateRangePicker)：Date Range Picker是一个日历选择器视图，用于显示自定义日期范围选择器，并改进了用户界面和功能，可以为日期添加字幕。
* [Linear Time Picker](https://github.com/code-mc/linear-time-picker)：受Timely应用启发的精美时间和日期选择器库。
* [WheelPickerCompose](https://github.com/commandiron/WheelPickerCompose)：Android Jetpack Compose中的时间选择器。
* [DateTimeRangePicker](https://github.com/skedgo/DateTimeRangePicker)：Android的日期时间范围选择器。
* [PrimeDatePicker](https://github.com/aminography/PrimeDatePicker)：PrimeDatePicker是一种提供选择单日、多日和一定范围的日期的工具。
* [TimeRangePicker](https://github.com/tittojose/TimeRangePicker)：TimeRangePicker是一个可用于选择时间范围的库。
* [Android SwitchDateTime Picker](https://github.com/Kunzisoft/Android-SwitchDateTimePicker)：SwitchDateTime Picker是一个库，用于在同一个UI中使用DatePicker(日历)和TimePicker(时钟)在对话框中选择日期对象。
* [LazyDatePicker](https://github.com/lopspower/LazyDatePicker)：这是一个Android项目，旨在提供原生Android日期选择器的替代品。
* [CustomDatePicker](https://github.com/liuwan1992/CustomDatePicker)：Android自定义日期选择控件。
* [SpinnerDatePicker](https://github.com/drawers/SpinnerDatePicker)：适用于Android的可自定义样式的DatePicker，采用旧式旋转器样式。
* [Persian Date Picker Dialog](https://github.com/aliab/Persian-Date-Picker-Dialog)：该库为你提供了一个带有简单API的漂亮的波斯日期选择器对话框。
* [DatePicker](https://github.com/ycuwq/DatePicker)：Android日期选择器小部件。
* [Time Selector](https://github.com/BurnieLiu/Time-Selector)：Android时间选择器库。
* [Compose Datetime Wheel Picker](https://github.com/darkokoa/compose-datetime-wheel-picker)：Compose Multiplatform日期时间选择器实现，具有可定制的轮子选择器，用于日期、时间和日期时间选择。
* [Easy Date Picker](https://github.com/Chaintech-Network/compose_multiplatform_date_time_picker)：Easy Date Picker是一个Kotlin多平台库，用于在Android、iOS和桌面应用程序中选择日期和时间。
* [MonthAndYearPicker](https://github.com/premkumarroyal/MonthAndYearPicker)：MonthAndYearPicker允许用户根据需要仅选择月份和年份或仅选择月份或仅选择年份。
* [Date Picker](https://github.com/afollestad/date-picker)：用Kotlin编写的适用于Android的自定义响应式日期选择器小部件。
* [Compose Material3 DateTime Pickers](https://github.com/marosseleng/compose-material3-datetime-pickers)：高度可定制的Jetpack Compose组件，使用Material3支持日期和时间选择。
* [HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker)：该库提供了一个伊斯兰历日期选择器。
* [Picker](https://github.com/ozcanalasalvar/picker)：Picker是一个日期和时间选择器库，支持基于视图和Jetpack Compose UI设计。
* [DateRangePicker](https://github.com/yesidlazaro/DateRangePicker)：带有日期选择器的Dialogo片段，可用于选择时间范围。
* [DatePickerDialog](https://github.com/xuningjack/datepickerdialog)：带有全日历图表和滚轮选择日期的对话框。
* [SnapTimePicker](https://github.com/akexorcist/SnapTimePicker)：另一个针对不喜欢默认Material Time Picker的开发人员的Material Time Picker。
* [DatePickerTimeline](https://github.com/101Loop/DatePickerTimeline)：提供水平日期选择器的Android包。
* [CPicker](https://github.com/andrewjapar/rangedatepicker)：一个简单的Android垂直日期选择器。
* [HorizontalPicker](https://github.com/jhonnyx2012/HorizontalPicker)：HorizontalPicker是一个定制的Android View，用于选择日期，但水平绘制到垂直狭窄的容器中。
* [RetainedDateTimePickers](https://github.com/k0shk0sh/RetainedDateTimePickers)：Android库可帮助你使用日期和时间选择器，同时在方向改变时保留选择器的实例。
* [WinKal](https://github.com/rahulrj/WinKal)：Android版Windows Phone日期选择器。
* [PickerView](https://github.com/jaaksi/pickerview)：一个非常好用的Android PickerView库，内部提供2种常用类型的Picker。
* [WheelPicker](https://github.com/zyyoona7/WheelPicker)：一个顺滑、高度自定义的滚轮控件和选择器，支持类似iOS的3D效果。

#### Android文件/目录选择器

* [Android FilePicker](https://github.com/DroidNinja/Android-FilePicker)：允许灵活选择图像和视频的文件选择器。
* [MultiType FilePicker](https://github.com/fishwjy/MultiType-FilePicker)：这是一个轻量级的Android文件选择器库。
* [Material File Picker](https://github.com/nbsp-team/MaterialFilePicker)：Android的Material文件选择器库，由Arte al Programar提供。
* [LFilePicker](https://github.com/leonHua/LFilePicker)：这是一个轻量级的文件选择器，可以通过检索手机目录来选择文件。
* [AndroidFilePicker](https://github.com/rosuH/AndroidFilePicker)：FilePicker是一个小型且快速的文件选择器库。
* [Storage Chooser](https://github.com/codekidX/storage-chooser)：适用于4.4+设备的漂亮而简单的目录选择器和文件选择器库。
* [NoNonsense FilePicker](https://github.com/spacecowboy/NoNonsense-FilePicker)：适用于Android的文件/目录选择器。
* [Calf](https://github.com/MohamedRejeb/Calf)：Calf是一个库，可让你轻松创建自适应UI并从Compose Multiplatform应用程序访问特定于平台的API。
* [FileListerDialog](https://github.com/FirzenYogesh/FileListerDialog)：FileListerDialog可帮助你列出并选择文件/目录。
* [Compose Multiplatform File Picker](https://github.com/Wavesonics/compose-multiplatform-file-picker)：一个多Compose Multiplatform小部件，用于使用每个平台的原生文件选择器对话框来选择文件。
* [FilePicker](https://github.com/imLibo/FilePicker)：Android文件、图片选择器，可按文件夹查找，文件类型查找，支持自定义相机。
* [ExFilePicker](https://github.com/bartwell/ExFilePicker)：ExFilePicker是一个开源的Android库，允许开发人员轻松实现在应用程序中选择文件和目录。
* [Android File Chooser](https://github.com/hedzr/android-file-chooser)：轻量级文件/文件夹选择器。
* [FilePicker](https://github.com/jaiselrahman/FilePicker)：Android的FilePicker库用于选择多种类型的文件以及捕获图像和视频。
* [FileBrowser](https://github.com/adityak368/Android-FileBrowser-FilePicker)：适用于Android的FileBrowser/FileChooser/FolderChooser。
* [FilePicker](https://github.com/ChochaNaresh/FilePicker)：适用于Android的可定制现代媒体/文档选择器，支持图像和视频捕获、文件选择以及Jetpack的ActivityResult API集成。
* [FilePicker](https://github.com/TutorialsAndroid/FilePicker)：Android库从设备存储中选择文件/目录。
* [FilePicker](https://github.com/Atwa/filepicker)：无需权限的Android文件和图像选择器库。
* [AppChooser](https://github.com/Pigcasso/AppChooser)：自定义打开指定文件的应用选择器。
* [OneDrive Picker Android](https://github.com/OneDrive/onedrive-picker-android)：该库提供了一组Java API，你的应用可以使用它们浏览、选择、打开和保存用户OneDrive中的文件。

#### Android国家选择器

* [CountryCodePickerProject](https://github.com/hbb20/CountryCodePickerProject)：CCP是一个Android库，它提供了一种简单的方法来搜索和选择电话号码的国家或国家电话代码。
* [Country Picker Android](https://github.com/mukeshsolanki/country-picker-android)：CountryPicker是一个简单的库，可以显示国家/地区选择器。
* [CountryCodePicker](https://github.com/joielechong/CountryCodePicker)：CCP是一个Android库，它提供了一种简单的方法来搜索和选择电话号码的国家电话代码。
* [Kompose Country Code Picker](https://github.com/joelkanyi/kompose-country-code-picker)：Kompose Country Code Picker是一个基于Material 3的Jetpack Compose库，它为Android应用提供了国家代码选择器。
* [CountryCodePicker](https://github.com/chathudan/CountryCodePicker)：Android CountryCodePicker将帮助用户搜索和选择一个国家并检索所选国家的国家名称、代码、货币和拨号代码。
* [Country Region Picker Android](https://github.com/sahooz/country-region-picker-android)：一个简洁的Android国家代码选择器，支持中英文、国旗、ISO 3166-1。
* [AndroidCountryPicker](https://github.com/roomorama/AndroidCountryPicker)：CountryPicker是一个简单的片段，可以嵌入或以对话框形式显示。
* [AndroidCountryPicker](https://github.com/hbb20/AndroidCountryPicker)：Android Country Picker是一个Kotlin优先、灵活且功能强大的Android库，只需几行代码即可集成国家选择器。
* [Jetpack Compose Country Code Picker](https://github.com/togisoft/jetpack_compose_country_code_picker)：Jetpack Compose国家/地区代码选择。
* [PhoneNumberKit](https://github.com/ibrahimsn98/PhoneNumberKit)：用于解析和格式化国际电话号码的Android Kotlin库，国家/地区代码选择器。

#### Android城市选择器

* [CityPicker](https://github.com/zaaach/CityPicker)：城市选择、定位、搜索及右侧字母导航，类似美团、百度糯米、饿了么等APP选择城市功能。
* [XPopupExt](https://github.com/junixapp/XPopupExt)：XPopup扩展功能库，基于XPopup强大的弹窗能力和PickerView的选择器逻辑，封装了时间选择器弹窗、城市选择器弹窗和条件选择器。
* [PickerView](https://github.com/duanhong169/PickerView)：Android滚动选择器(省市区联动选择、日期选择、时间选择)。
* [PickerView](https://github.com/youth5201314/PickerView)：一种全新的选择器，可用于省市区选择和各种层级数据的展示。
* [CityPicker](https://github.com/yuruizhe/CityPicker)：一个仿大众点评、美团的城市选择器，使用如同Rx一样优雅，并且UI和城市数据可以自定义。

#### Android位置选择器

* [Leku](https://github.com/AdevintaSpain/Leku)：Android地图位置选择器组件。
* [React Native Google Place Picker](https://github.com/zhangtaii/react-native-google-place-picker)：针对iOS、Android的Google Place Picker的React Native包装器。
* [PlacePicker](https://github.com/suchoX/PlacePicker)：使用Geocoder替代Google API的免费Android地图地点选择器。
* [PING](https://github.com/rtchagas/pingplacepicker)：几乎即插即用的Google Place Picker替代品。
* [Vanilla Place Picker](https://github.com/Mindinventory/vanilla-place-picker)：Vanilla Place Picker提供了一个UI，可显示交互式地图以获取地点详细信息和自动完成功能，该功能可根据用户搜索输入显示地点预测。
* [AddressPickerLib](https://github.com/ywp0919/AddressPickerLib)：仿京东地址选择器。
* [Nibo](https://github.com/aliumujib/Nibo)：Android库，为可定制的地点选择器、出发地和目的地选择器以及Google Places自动完成搜索视图提供UI。

#### Android数字选择器

* [NumberSlidingPicker](https://github.com/sephiroth74/NumberSlidingPicker)：一个允许用户从预定义范围中选择数字的小部件。
* [NumberPickerView](https://github.com/Carbs0126/NumberPickerView)：Android平台上另一个属性更灵活的NumberPicker。
* [NumberPicker](https://github.com/ShawnLin013/NumberPicker)：提供简单且可定制的NumberPicker的Android库。
* [Jetpack Compose Number Picker](https://github.com/ChargeMap/Compose-NumberPicker)：Android库为Jetpack Compose提供数字选择器。
* [Actual Number Picker](https://github.com/appifyhub/actual-number-picker)：Actual Number Picker是Android定制的用于选择数字的视图。
* [SimpleNumberPicker](https://github.com/StephaneBg/SimpleNumberPicker)：适用于Android的可定制十进制和十六进制Material选择器视图。
* [VNTNumberPickerPreference](https://github.com/vanniktech/VNTNumberPickerPreference)：这是一个易于使用的自定义首选项，它会打开一个带有数字选择器的对话框。
* [WheelPicker](https://github.com/SuperRabbitD/NumberPicker)：该项目包含一个可定制的WheelPicker，它比Android原生NumberPicker小部件更灵活。
* [MaterialNumberPicker](https://github.com/KasualBusiness/MaterialNumberPicker)：受Material Design指南启发的可定制Android NumberPicker。
* [MaterialNumberPicker](https://github.com/StephenVinouze/MaterialNumberPicker)：基于Material Design指南的可自定义数字选择器。
* [ClickNumberPicker](https://github.com/polok/ClickNumberPicker)：自定义视图使用单击按钮或滑动从给定范围中选取一个值。
* [Android Ruler Picker](https://github.com/kevalpatel2106/android-ruler-picker)：Android自定义视图使用标尺从给定范围中选择数字。
* [HorizontalPicker](https://github.com/adityagohad/HorizontalPicker)：一个简单、可定制且易于使用的选择器，其中中心视图按比例放大。
* [HorizontalPicker](https://github.com/GoodieBag/HorizontalPicker)：适用于Android的水平选择器库，支持文本和图标。

#### Android滚动选择器

* [WheelPicker](https://github.com/devaige/WheelPicker)：简单而奇妙的Android轮盘视图，效果逼真。
* [CarouselPicker](https://github.com/GoodieBag/CarouselPicker)：适用于Android的轮播选择器库，支持文本和图标。
* [ReactNativeWheelPicker](https://github.com/Cero-Studio/ReactNativeWheelPicker)：适用于Android的简单Wheel Picker。
* [React Native Wheel Picker](https://github.com/lesliesam/react-native-wheel-picker)：基于React Native的跨平台Picker组件。
* [EasyPickerView](https://github.com/huzenan/EasyPickerView)：适用于Android的轻量级PickerView。
* [TimePicker](https://github.com/jingchenUSTC/TimePicker)：Android滚动选择器PickerView。
* [Two Step Picker Dialog](https://github.com/aliab/Two-Step-Picker-Dialog)：Android的两步选择器对话框可帮助你轻松选择Android上的嵌套数据。
* [HorizontalPicker](https://github.com/blazsolar/HorizontalPicker)：HorizontalPicker是一个开源的Android库，它允许用户通过滚动或左右点击在项目数组之间移动来选择单个项目。
* [SwipePicker](https://github.com/m4xp1/SwipePicker)：Android的一个小部件，允许用户使用滑动手势输入不同的值，例如：时间、日期、数字，而无需额外的对话框窗口。
* [Compose Wheel Picker](https://github.com/zj565061763/compose-wheel-picker)：Android Compose轮盘选择器库基于垂直方向的LazyColumn和水平方向的LazyRow。
* [PickerView](https://github.com/RameshBhupathi/PickerView)：OptionsPickerView类似iOS的三种选项选择器。
* [WheelPicker](https://github.com/open-android/WheelPicker)：Android滚轮选择控件，包含3D效果，滑动流畅无比。
* [UniversalPickerDialog](https://github.com/stfalcon-studio/UniversalPickerDialog)：可定制的对话框，其中包含根据数据集数量自动生成的选择器。

#### Android联系人选择器

* [UnifiedContactPicker](https://github.com/quiin/UnifiedContactPicker)：统一联系人选择器Android库。
* [Android Contact Picker](https://github.com/codinguser/android_contact_picker)：在Android上轻松显示和检索联系人信息。
* [MultiContactPicker](https://github.com/broakenmedia/MultiContactPicker)：一个使用RecyclerView和字母快速滚动的简单Material Design多触点选择器。

#### Android更新库

* [AppUpdate](https://github.com/WVector/AppUpdate)：一个用于Android版本更新的库。
* [APKUpdater](https://github.com/rumboalla/apkupdater)：APKUpdater是一个开源工具，可以简化查找已安装应用程序更新的过程。
* [CheckVersionLib](https://github.com/AlexLiuSheng/CheckVersionLib)：Android上的自动检查版本库。
* [AppUpdate](https://github.com/azhon/AppUpdate)：Android版本更新库，简单、轻量、可随意定制。
* [XUpdate](https://github.com/xuexiangjys/XUpdate)：一个轻量级、高可用性的Android版本更新框架。
* [Update](https://github.com/czy1121/update)：清晰灵活简单易用的应用更新库。
* [UpdatePlugin](https://github.com/easyandroidgroup/UpdatePlugin)：UpdatePlugin是一款用来进行App更新升级的框架。
* [UpdateAppUtils](https://github.com/teprinciple/UpdateAppUtils)：一行代码快速实现App版本更新。
* [AutoUpdateProject](https://github.com/MZCretin/AutoUpdateProject)：App内部更新，提供12种更新的样式，支持Android全系统版本，支持自定义UI断点续传。
* [Android Auto Update](https://github.com/feicien/android-auto-update)：Android应用自动更新库。
* [AppUpdater](https://github.com/jenly1314/AppUpdater)：AppUpdater是一个专注于App更新，一键傻瓜式集成App版本升级的轻量开源库。
* [Device Firmware Update](https://github.com/NordicSemiconductor/Android-DFU-Library)：设备固件更新库和Android应用程序。
* [UpdateFun](https://github.com/hugeterry/UpdateFun)：UpdateFun是一个fir.im的Android更新下载模块，在fir.im上上传自己的APP后接入该库即可实现检查更新下载。
* [MNUpdateAPK](https://github.com/maning0303/MNUpdateAPK)：Android APK Update版本更新的下载和安装。
* [InAppUpdater](https://github.com/SanojPunchihewa/InAppUpdater)：Android库，轻松实现应用内更新。
* [AppUpdate](https://github.com/caikaidev/AppUpdate)：Android应用更新库。
* [AndroidAppUpdater](https://github.com/hummatli/AndroidAppUpdater)：一个免费、开源的第三方Android库，用于通知有关Android设备上安装的Android应用程序的更新信息。
* [UpdateHelper](https://github.com/shelwee/UpdateHelper)：UpdateHelper是一个只需一行代码即可实现APP在线升级的Android库。
* [AppSmartUpdate](https://github.com/itlwy/AppSmartUpdate)：Android版本更新，支持增量更新。
* [AppUpdate](https://github.com/NewHuLe/AppUpdate)：原生DownloadManager实现版本的检测更新，完美适配Android M/N/O/P/Q，兼容AndroidX。
* [Android In-App Update](https://github.com/dioKaratzas/android-inapp-update)：Android应用内更新的轻量级实现。
* [CheckUpdateLibrary](https://github.com/qiangxi/CheckUpdateLibrary)：Android检查更新库。
* [AndroidAppUpdateLibrary](https://github.com/Piashsarker/AndroidAppUpdateLibrary)：Android应用更新库可用于从链接下载Apk，将其保存到外部或内部存储，然后自动安装Apk。
* [Android Update Checker](https://github.com/danielemaddaluno/Android-Update-Checker)：该项目旨在提供一个可重复使用的工具，以异步检查商店中是否存在你的应用的任何较新发布的更新。
* [Prince Versions](https://github.com/infinum/Android-Prince-of-Versions)：用于处理应用程序更新的Android库。

#### Android热修复

* [Tinker](https://github.com/Tencent/tinker)：Tinker是Android的一个热修复解决方案库，它支持dex、库和资源更新，无需重新安装apk，由腾讯开源。
* [Robust](https://github.com/Meituan-Dianping/Robust)：Robust是一款高兼容性、高稳定性的Android HotFix解决方案，由美团开发。
* [AndFix](https://github.com/alibaba/AndFix)：AndFix是一种在线修复错误的解决方案，由阿里开源。
* [Nuwa](https://github.com/jasonross/Nuwa)：纯Java实现，可以对你的Android应用程序进行热修复。
* [Small](https://github.com/wequick/Small)：将应用程序拆分成小部分的小型框架。
* [HotFix](https://github.com/dodola/HotFix)：安卓App热补丁动态修复框架。
* [RocooFix](https://github.com/dodola/RocooFix)：另一个修补程序框架。
* [FastDex](https://github.com/typ0520/fastdex)：FastDex可以帮助你加快APK生成过程。
* [Aceso](https://github.com/meili/Aceso)：Aceso是一个通过优化AOSP的“InstantRun HotSwap”解决方案的Android HotFix，它用于修复线上BUG，而无需发布新的APK，由蘑菇街开源。
* [Amigo](https://github.com/eleme/Amigo)：Amigo是一个修补程序库，可以修复Android应用的所有问题，由饿了么开源。
* [Stark](https://github.com/ximsfei/Stark)：Stark是Android的一个热修复框架。
* [Phantom](https://github.com/ManbangGroup/Phantom)：Phantom是满帮集团开源的一套稳定、灵活、兼容性好的Android插件化方案。
* [SDKHotFix](https://github.com/feelschaotic/SDKHotFix)：让SDK开发者能快速赋予SDK热修复的能力。
* [Hotfix](https://github.com/lyr408/Hotfix)：Hotfix可以动态修复移动应用程序的在线错误。
* [HotfixFlutter](https://github.com/magicbaby810/HotfixFlutter)：使用Tinker或Sophix实现Flutter热更新，兼容flutterboost。
* [Titan](https://github.com/baidu/titan-hotfix)：Titan是一个Android平台上的热修复解决方案，无需发版就可以修复线上问题，由百度开源。

#### Android运行时权限

* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)：PermissionsDispatcher提供了一个简单的基于注解的API来处理运行时权限。
* [EasyPermissions](https://github.com/googlesamples/easypermissions)：EasyPermissions是一个包装库，用于简化针对Android M或更高版本时的基本系统权限逻辑，由Google开发。
* [RxPermissions](https://github.com/tbruyelle/RxPermissions)：该库允许将RxJava与新的Android M权限模型一起使用。
* [AndPermission](https://github.com/yanzhenjie/AndPermission)：Android平台的权限管理器。
* [XXPermissions](https://github.com/getActivity/XXPermissions)：Android权限框架，适配Android 15。
* [Dexter](https://github.com/Karumi/Dexter)：Dexter是一个Android库，它简化了运行时请求权限的过程。
* [PermissionX](https://github.com/guolindev/PermissionX)：PermissionX是一个扩展Android库，它使得Android运行时权限请求变得非常容易。
* [Permissions4M](https://github.com/jokermonn/permissions4m)：国产手机5.0、6.0权限适配框架/编译时注解框架。
* [Libsu](https://github.com/topjohnwu/libsu)：一个为使用Root权限的应用程序提供完整解决方案的Android库。
* [TedPermission](https://github.com/ParkSangGwon/TedPermission)：轻松检查Android Marshmallow的权限库。
* [PermissionHelper](https://github.com/k0shk0sh/PermissionHelper)：Android库可帮助你处理运行时权限。
* [HiPermission](https://github.com/yewei02538/HiPermission)：一个简洁美观的Android运行时权限库。
* [PermissionGen](https://github.com/lovedise/PermissionGen)：PermissionGen可以轻松处理Android M中的权限。
* [MPermissions](https://github.com/hongyangAndroid/MPermissions)：基于注解处理器的简单易用的处理Android M运行时权限的库。
* [RuntimePermission](https://github.com/florent37/RuntimePermission)：在Android上请求运行时权限的最简单方法。
* [Assent](https://github.com/afollestad/assent)：Assent旨在使Android的运行时权限更容易，并减少应用中的代码使用。
* [Nammu](https://github.com/tajchert/Nammu)：使用Android 6.0 Marshmallow中引入的全新运行时权限功能，加速你的工作。
* [SoulPermission](https://github.com/soulqw/SoulPermission)：Android的权限检查或请求。
* [Let](https://github.com/canelmas/let)：基于注解的简单API，采用AOP风格来处理新的Android运行时权限模型。
* [Moko Permissions](https://github.com/icerockdev/moko-permissions)：Kotlin MultiPlatform库，用于在iOS和Android上提供运行时权限。
* [KPermissions](https://github.com/fondesa/kpermissions)：一个完全用Kotlin编写的Android库，有助于请求运行时权限。
* [Android Permissions](https://github.com/nabinbhandari/Android-Permissions)：轻松处理Android中的运行时权限。
* [QuickPermissions](https://github.com/QuickPermissions/QuickPermissions)：处理Android运行时权限最简单的方法。
* [FcPermissions](https://github.com/lypeer/FcPermissions)：FcPermissions是一个用于简化针对Android M或更高版本的基本系统权限逻辑的库。
* [HeiPermission](https://github.com/forJrking/HeiPermission)：Android M动态权限解决方案。
* [Permissify](https://github.com/holidaycheck/Permissify)：Permissify是一个Android库，它使得在运行时请求权限变得更加容易。
* [QuickPermissions](https://github.com/QuickPermissions/QuickPermissions-Kotlin)：在Kotlin中处理Android运行时权限的最简单方法。
* [PermissionUtil](https://github.com/kayvannj/PermissionUtil)：Android 6.0运行时权限API的简单包装器。
* [EazyPermission](https://github.com/sagar-viradiya/eazypermissions)：轻量级的Android库，它包装了运行时权限的样板代码并允许你请求权限。
* [Aaper](https://github.com/LikeTheSalad/aaper)：仅使用注解来确保Android运行时权限。
* [EasyPermission](https://github.com/panyiho/EasyPermission)：EasyPermission是一个简单易用，且无多余的第三方依赖的Android6.0动态权限申请库。
* [RxPermission](https://github.com/vanniktech/RxPermission)：该库使用RxJava 2包装了Android运行时权限。
* [Permiso](https://github.com/greysonp/permiso)：Permiso是一个Android库，它使得请求运行时权限变得更加容易。
* [Aopermission](https://github.com/crazyqiang/Aopermission)：AOP方式封装的6.0运行时申请权限的库。
* [RuntimePermissionsExtended](https://github.com/vuksa/RuntimePermissionsExtended)：该项目提供了Kotlin扩展函数，使得权限处理更加简单、简洁。
* [Ask](https://github.com/00ec454/Ask)：让Android运行时权限更简单。
* [PermissionsKt](https://github.com/sembozdemir/PermissionsKt)：以Kotlin方式处理Android运行时权限。
* [Permission Compose](https://github.com/meticha/permissions-compose)：轻量级Android库，可简化Jetpack Compose应用程序中的运行时权限管理。
* [Rx Android Permissions](https://github.com/sergejsha/rx-android-permissions)：Android 6.0中引入的用于观察和请求Android运行时权限的简单RxJava库。
* [PowerPermission](https://github.com/underwindfall/PowerPermission)：PowerPermission使得处理运行时权限变得非常容易。

#### Android下载库

* [FileDownloader](https://github.com/lingochamp/FileDownloader)：Android多任务文件下载引擎。
* [OkDownload](https://github.com/lingochamp/okdownload)：可靠、灵活、快速且强大的下载引擎。
* [Fast Android Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking)：Fast Android Networking是一个功能强大的库，用于在Android应用程序中执行任何类型的网络。
* [RxDownload](https://github.com/ssseasonnn/RxDownload)：使用RxJava和Kotlin编写的多线程下载工具。
* [Android Download Manager](https://github.com/majidgolshadi/Android-Download-Manager-Pro)：Android/Java下载管理器库可帮助你以并行机制分块下载文件。
* [Multi Thread Downloader](https://github.com/devaige/MultiThreadDownloader)：轻量级、简单的Android多线程下载器。
* [MultiThreadDownload](https://github.com/Aspsine/MultiThreadDownload)：Android多线程下载库。
* [Thin DownloadManager](https://github.com/smanikandan14/ThinDownloadManager)：Thin DownloadManager是一个Android库，主要用于下载文件，并在应用程序中使用Android提供的DownloadManager时避免使用DOWNLOAD_WITHOUT_NOTIFICATION权限。
* [Picasso 2 OkHttp 3 Downloader](https://github.com/JakeWharton/picasso2-okhttp3-downloader)：针对Picasso 2的OkHttp 3下载器实现。
* [CoreProgress](https://github.com/lizhangqu/CoreProgress)：CoreProgress是一个支持OkHttp上传下载进度的框架。
* [Download Manager](https://github.com/novoda/download-manager)：处理长时间下载、处理网络交互并在失败后自动重试下载的库。
* [Android Downloader](https://github.com/ixuea/android-downloader)：Android Downloader是一个适用于Android的开源多线程和多任务下载信息框架。
* [Downloader](https://github.com/Justson/Downloader)：Downloader是一个非常轻巧以及功能强大快速下载库。
* [M3U8Downloader](https://github.com/Jay-Goo/M3U8Downloader)：M3U8下载器，支持多线程下载、断点续传、后台下载、本地播放解决方案、M3U8加密解决方案。
* [FileDownloader](https://github.com/wlfcolin/file-downloader)：FileDownloader是一个强大的HTTP/HTTPS文件下载工具
* [Pump](https://github.com/huxq17/Pump)：Pump是一个快速、易于使用的Android下载库，支持多任务、多线程、断点下载。

#### Android评分库

* [SmileyRating](https://github.com/sujithkanna/SmileyRating)：SmileyRating是一款简单的Android评分栏。
* [MaterialRatingBar](https://github.com/zhanghai/MaterialRatingBar)：外观更佳的Material Design RatingBar。
* [SimpleRatingBar](https://github.com/williamyyu/SimpleRatingBar)：一个简单的评级栏，你可以更轻松地自定义图像和动画。
* [SimpleRatingBar](https://github.com/FlyingPumba/SimpleRatingBar)：开源项目，提Android默认RatingBar的简单但功能强大的替代品。
* [Android Material App Rating](https://github.com/stepstone-tech/android-material-app-rating)：该库允许在应用程序内部使用自定义的评级对话框。
* [ProperRatingBar](https://github.com/techery/ProperRatingBar)：感源自原生Android RatingBar，更简洁，并具备原版所缺乏的功能。
* [EmotionRatingView](https://github.com/rubygarage/emotion-rating-view)：EmotionRatingApp是一个Android应用程序库，可根据所选评级展示情绪反应。
* [Compose Ratingbar](https://github.com/a914-gowtham/compose-ratingbar)：适用于Jetpack Compose的评级栏。
* [Awesome App Rating](https://github.com/SuddenH4X/awesome-app-rating)：高度可定制的Android库，提供对话框，要求用户对应用程序进行评级。
* [Android Five Stars Library](https://github.com/Angtrim/Android-Five-Stars-Library)：Android Five Stars Library是一个小型库，可帮助开发人员在其应用程序中添加“评价我的应用程序”对话框。
* [SmileBar](https://github.com/eugeneek/SmileBar)：简单的Android库，提供评分视图，每个评分值对应不同的可绘制对象。
* [SimpleRatingView](https://github.com/xiprox/SimpleRatingView)：Android的评级切换可在三个评级级别之间切换：正面、中性和负面。
* [SimpleRatingBar](https://github.com/bravoborja/SimpleRatingBar)：SimpleRatingBar允许创建一个带有项目间边距的RatingBar。
* [AndroidRate](https://github.com/Vorlonsoft/AndroidRate)：AndroidRate是一个库，它通过提示用户在使用几天后对应用程序进行评级来帮助你推广Android应用程序。
* [Android Rate](https://github.com/hotchemi/Android-Rate)：Android Rate是一个库，它通过提示用户在使用几天后对应用程序进行评级来帮助你推广Android应用程序。
* [Smiley Rating](https://github.com/YuganshT79/Smiley-Rating)：Smiley Rating是一种自定义方式，当你的用户对你的应用给出精彩的反馈时，可以用微笑来问候他们。
* [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog)：这个库提供了一种简单的方法来显示评级应用程序的警报对话框。
* [AndroidRatingStar](https://github.com/everhad/AndroidRatingStar)：RatingStar 是特定于RatingBar的使用星形绘制作为评级标记。
* [Smart App Rate](https://github.com/codemybrainsout/smart-app-rate)：适用于Android的智能应用评级对话框，其中考虑了用户评级。
* [Android RateThisApp](https://github.com/kobakei/Android-RateThisApp)：Android RateThisApp是一个显示“评价此应用”对话框的库。

#### Android路由框架

* [ARouter](https://github.com/alibaba/ARouter)：帮助Android APP进行组件化改造的路由框架，由阿里开源。
* [Voyager](https://github.com/adrielcafe/voyager)：专为Jetpack Compose构建并与之无缝集成的多平台导航库。
* [Component](https://github.com/xiaojinzi123/Component)：一个强大、100%兼容、支持AndroidX、支持Kotlin并且灵活的组件化框架。
* [Decompose](https://github.com/arkivanov/Decompose)：Decompose是一个Kotlin Multiplatform库，用于将你的代码分解为树状结构的生命周期感知业务逻辑组件，具有路由功能和可插拔UI。
* [ActivityRouter](https://github.com/mzule/ActivityRouter)：支持给Activity定义URL，这样可以通过URL跳转到Activity，支持在浏览器以及APP中跳入。
* [Router](https://github.com/chenenyu/Router)：灵活的组件化路由框架。
* [TheRouter](https://github.com/HuolalaTech/hll-wp-therouter-android)：帮助App进行组件化改造的动态路由框架。
* [DRouter](https://github.com/didi/DRouter)：DRouter是18年滴滴乘客端自研的一套Android路由框架。
* [Router](https://github.com/JumeiRdGroup/Router)：一款单品、组件化、插件化全支持的Android端路由框架，由聚美优品开源。
* [AndRouter](https://github.com/campusappcn/AndRouter)：AndRouter是一个用于将URL映射到活动或动作的Android框架。
* [Compose Router](https://github.com/zsoltk/compose-router)：带有返回堆栈的Jetpack Compose路由功能。
* [Decompose](https://github.com/badoo/Decompose)：Decompose是一个Kotlin多平台库，用于将代码分解为可感知生命周期的业务逻辑组件，并支持路由功能和可插拔的UI。
* [WMRouter](https://github.com/meituan/WMRouter)：WMRouter是一款Android路由框架，基于组件化的设计思路，有功能灵活、使用简单的特点，由美团开源。
* [Floo](https://github.com/drakeet/Floo)：支持AOP、堆栈控制、跨页面消息、动态路由的URL路由器。
* [Routable](https://github.com/clayallsopp/routable-android)：Routable是一款适用于Android的应用内原生URL路由器。
* [RouterSDK](https://github.com/Jomes/routerSDK)：RouterSDK是一个优秀的路由器框架，它很容易集成到你的项目中。
* [Kompass](https://github.com/sellmair/kompass)：适用于Android和iOS的Kotlin多平台路由器。
* [RxRouter](https://github.com/ssseasonnn/RxRouter)：一个轻量级、简单、智能且强大的Android路由库。
* [Meepo](https://github.com/nekocode/Meepo)：Meepo是一款Android路由器生成器，类似于Retrofit。
* [KSP Router](https://github.com/HeartHappy/Router)：Android端使用KSP实现的路由框架。
* [BRouter](https://github.com/bilibili/BRouter)：BRouter是一个Kotlin编写的面向模块Android路由库，由B站开源。
* [Decompose Router](https://github.com/xxfast/Decompose-Router)：Compose多平台导航库，利用Decompose创建受Conductor启发的API。
* [Router](https://github.com/BaronZ88/Router)：Android平台一个简单的路由框架，包含路由和参数注入两部分功能。
* [Android Router](https://github.com/TangXiaoLv/Android-Router)：Android高性能轻量级路由框架。
* [RouterKit](https://github.com/gybin02/RouterKit)：Android平台对页面、服务的路由框架。
* [Router Android](https://github.com/Leifzhang/Router-Android)：通过注解实现路由跳转规则，同时增加KSP支持。
* [EasyRouter](https://github.com/liuzhao2007/EasyRouter)：简单、稳定、强大、高性能的组件化路由框架。
* [Router](https://github.com/eyeem/router)：Android应用内动态URL路由器。
* [EasyRouter](https://github.com/Zane96/EasyRouter)：EasyRouter是一个简易的使用字符串进行Activity、Browser跳转的路由框架，并支持组件化开发。
* [Router](https://github.com/aleyn97/router)：适用于Android的路由框架。
* [Android Router](https://github.com/myjoybar/Android-Router)：一个使用简单方便的Android Router框架。
* [Krouter](https://github.com/denisidoro/krouter)：用Kotlin编写的轻量级Android活动路由器。
* [Rabbits](https://github.com/kyleduo/Rabbits)：Android应用程序的路由器模块。
* [MyRouter](https://github.com/wenzhonghu/MyRouter)：Android平台中对页面、原生路由功能的中间件。

#### Android导航库

* [NavigationTabBar](https://github.com/Devlight/NavigationTabBar)：具有丰富多彩交互的导航标签栏。
* [Compose Destinations](https://github.com/raamcosta/compose-destinations)：一个处理注解并生成使用官方Jetpack Compose Navigation的代码的KSP库。
* [Scene](https://github.com/bytedance/scene)：Scene是一个基于视图的轻量级导航和UI组合库，由字节开源。
* [SlidingTutorial](https://github.com/Cleveroad/SlidingTutorial-Android)：用于在应用程序内制作动画教程的Android库。
* [Native Navigation](https://github.com/airbnb/native-navigation)：React Native应用程序的原生导航库，由Airbnb开源。
* [Bubble Navigation](https://github.com/gauravk95/bubble-navigation)：一个轻量级的库，可以轻松制作漂亮的导航栏，并提供大量自定义选项。
* [Cicerone](https://github.com/terrakok/Cicerone)：Cicerone是一个轻量级库，可轻松实现Android应用中的导航。
* [MenuDrawer](https://github.com/SimonVT/android-menudrawer)：滑出式菜单实现，允许用户在应用中的视图之间导航。
* [PagerBottomTabStrip](https://github.com/tyzlmjj/PagerBottomTabStrip)：Android页面底部和侧边的导航栏。
* [BGABanner Android](https://github.com/bingoogolapple/BGABanner-Android)：引导界面滑动导航、大于等于1页时无限轮播、各种切换动画轮播效果。
* [BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation)：该库帮助用户轻松使用底部导航栏，并允许大量自定义。
* [BottomBar](https://github.com/roughike/BottomBar)：模仿新的Material Design底部导航模式的自定义视图组件。
* [ImmersionBar](https://github.com/gyf-dev/ImmersionBar)：Android 4.4以上沉浸式状态栏和沉浸式导航栏管理，适配横竖屏切换、刘海屏、软键盘弹出等问题。
* [FragNav](https://github.com/ncapdevi/FragNav)：用于管理多个片段堆栈(例如底部导航、导航抽屉)的Android库。
* [RecyclerTabLayout](https://github.com/nshmura/RecyclerTabLayout)：使用RecyclerView实现的高效TabLayout库。
* [AnimatedBottomBar](https://github.com/Droppers/AnimatedBottomBar)：可定制且易于使用的BottomBar导航视图，具有流畅的动画，支持ViewPager、ViewPager2、NavController和徽章。
* [Floating Navigation View](https://github.com/andremion/Floating-Navigation-View)：一个简单的浮动操作按钮，显示一个锚定的导航视图。
* [Chip Navigation Bar](https://github.com/ismaeldivita/chip-navigation-bar)：受Google Bottom Navigation启发并混合了Chips组件的导航栏小部件。
* [NavigationTabStrip](https://github.com/Devlight/NavigationTabStrip)：具有流畅交互的导航标签条。
* [Simple Stack](https://github.com/Zhuinden/simple-stack)：Simple Stack是一个后退堆栈库，它允许你在不可变的、可打包的数据类列表中表示你的导航状态。
* [AHBottomNavigation](https://github.com/aurelhubert/ahbottomnavigation)：用于根据Material Design指南实现底部导航组件的库。
* [BottomNavigationViewEx](https://github.com/ittianyu/BottomNavigationViewEx)：用于增强BottomNavigationView的Android库。
* [SmoothBottomBar](https://github.com/ibrahimsn98/SmoothBottomBar)：一个轻量级的Android材质底部导航栏库。
* [Space Navigation](https://github.com/armcha/Space-Navigation-View)：Space Navigation是一个库，可轻松将完全可定制的Google Spaces等导航集成到你的应用中。
* [InboxRecyclerView](https://github.com/saket/InboxRecyclerView)：InboxRecyclerView是一个受Google Inbox和Reply启发的用于构建可扩展后代导航的库，并且可以轻松插入到现有项目中。
* [Material Bottom Navigation Library](https://github.com/sephiroth74/Material-BottomNavigation)：轻量级底部导航库组件，灵感来自Google Material Design指南。
* [Meow Bottom Navigation](https://github.com/oneHamidreza/MeowBottomNavigation)：用Kotlin编写的适用于Android的简单、弯曲且材质底部导航。
* [Appyx](https://github.com/bumble-tech/appyx)：用于Compose Multiplatform的模型驱动导航、带手势控制的UI组件。
* [ChromeLikeTabSwitcher](https://github.com/michael-rapp/ChromeLikeTabSwitcher)：ChromeLikeTabSwitcher是一个Android库，它提供了一个类似于Google Chrome浏览器Android版本中使用的标签切换器。
* [ByeBurger](https://github.com/githubwing/ByeBurger)：极其简便的快速实现滑动隐藏标题栏和导航栏。
* [Material Bottom Navigation](https://github.com/armcha/LuseenBottomNavigation)：BottomNavigationView根据Google GuideLine设计。
* [Morph Bottom Navigation](https://github.com/tommybuonomo/morph-bottom-navigation)：该库代表底部导航，在所选项目顶部具有出色的变形效果。
* [BottomBarLayout](https://github.com/chaychan/BottomBarLayout)：一个轻量级的底部导航控件。
* [Chip Navigation Bar](https://github.com/ismaeldivita/chip-navigation-bar)：受Google Bottom Navigation启发并混合了Chips组件的导航栏小部件。
* [Simple Bottom Navigation](https://github.com/bufferapp/AdaptableBottomNavigation)：在Android上实现底部导航视图的更简单方法。
* [Navigation Toolbar](https://github.com/Ramotion/navigation-toolbar-android)：Navigation Toolbar是一个Kotlin幻灯片模型的UI导航控制器。
* [JPTabBar](https://github.com/peng8350/JPTabBar)：TabBar Android是一款炫酷的Android底部导航栏。
* [ExpandableBottomBar](https://github.com/st235/ExpandableBottomBar)：改善应用导航的新方法。
* [BubbleTabBar](https://github.com/akshay2211/BubbleTabBar)：BubbleTabBar是底部导航栏，带有可自定义的气泡状标签。

#### Android抽屉库

* [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer)：灵活易用，一站式Android项目抽屉库，现已全新推出，采用Material 2设计。
* [SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav)：该库是一个类似DrawerLayout的ViewGroup，其中的“抽屉”隐藏在内容视图下方，可以通过移动内容视图使其可见。
* [FlowingDrawer](https://github.com/mxn21/FlowingDrawer)：向右滑动即可显示带有流动效果的抽屉。
* [Material Menu](https://github.com/balysv/material-menu)：Android L抽屉、返回、关闭和检查图标的动画。
* [SmartSwipe](https://github.com/luckybilly/SmartSwipe)：SmartSwipe Android库可帮助你更轻松地进行视图滑动。
* [Duo Navigation Drawer](https://github.com/asdsolutions-os/duo-navigation-drawer)：这个Android库提供了一种为Android创建替代导航抽屉的简便方法。
* [MaterialNavigationDrawer](https://github.com/neokree/MaterialNavigationDrawer)：采用Material Design风格和简化方法的导航抽屉Activity。
* [LDrawer](https://github.com/keklikhasan/LDrawer)：带有Material Design动画的Android抽屉图标。
* [DebugDrawer](https://github.com/palaima/DebugDrawer)：Android调试抽屉，加快开发速度。
* [NavigationDrawer MaterialDesign](https://github.com/zirouan/NavigationDrawer-MaterialDesign)：Material Design导航抽屉库。
* [DrawerArrowDrawable](https://github.com/ChrisRenke/DrawerArrowDrawable)：Android L中的新抽屉指示器/后箭头旋转可绘制对象的简单可绘制反向移植。
* [Material Drawer](https://github.com/janheinrichmerker/material-drawer)：针对Material Design应用的自定义抽屉实现。
* [Drawer Behavior](https://github.com/shiburagi/Drawer-Behavior)：Drawer Behavior是一个使用Android DrawerLayout支持库作为父类的库，它在抽屉上提供额外的行为，例如，在滑动抽屉时移动视图或缩放视图的高度。
* [AwesomeDrawer](https://github.com/Android500/AwesomeDrawer)：实现Android窗帘拉开折叠效果。
* [MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt)：MaterialDrawer库的Kotlin DSL包装器。
* [Custom Navigation Drawer](https://github.com/shrikanth7698/Custom-Navigation-Drawer)：Android自定义导航抽屉库。
* [BlurNavigationDrawer](https://github.com/charbgr/BlurNavigationDrawer)：像Etsy应用程序一样的模糊导航抽屉。
* [Undergarment](https://github.com/EddieRingle/android-undergarment)：适用于Android应用程序的滑出式导航(抽屉)实现。
* [VerticalDrawerLayout](https://github.com/corerzhang/VerticalDrawerLayout)：一个垂直方向的DrawerLayout，抽屉从上向下展开。
* [FullDraggableDrawer](https://github.com/PureWriter/FullDraggableDrawer)：让DrawerLayout在全屏范围内实时拖拽。
* [GoogleNavigationDrawerMenu](https://github.com/jmartinesp/GoogleNavigationDrawerMenu)：类似于Google Apps中的DrawerLayout的Android库。
* [NavigationDrawerSI](https://github.com/mmBs/NavigationDrawerSI)：导航抽屉简单实现。
* [SherlockNavigationDrawer](https://github.com/nicolasjafelle/SherlockNavigationDrawer)：SherlockNavigationDrawer是最新Google UX组件导航抽屉的实现。
* [SimpleSideDrawer](https://github.com/adamrocker/simple-side-drawer)：SimpleSideDrawer是一个Android库，用于将抽屉导航添加到你的Android应用程序。
* [AdvancedMaterialDrawer](https://github.com/madcyph3r/AdvancedMaterialDrawer)：类似Gmail的Material Drawer实现。
* [GoogleNavigationDrawer](https://github.com/neokree/GoogleNavigationDrawer)：采用Google设计风格和简化方法的导航抽屉活动。
* [Ti.DrawerLayout](https://github.com/manumaticx/Ti.DrawerLayout)：Titanium原生Android导航抽屉。
* [Material Navigation](https://github.com/mustafaozcan/MaterialNavigation)：Android Material导航(工具栏、导航抽屉、导航视图、标签页、CardView、ViewPager)
* [DebugDrawer](https://github.com/Gridstone/DebugDrawer)：一个可配置的调试抽屉，可用于你的Android应用。
* [Navigation Drawer Customisations](https://github.com/Mindinventory/minavdrawer)：易于使用的标准NavigationDrawer定制。
* [L Navigation Drawer](https://github.com/lewisjdeane/L-Navigation-Drawer)：该库允许你轻松复制Android L的新式导航抽屉。

#### Android动画库

* [Lottie](https://github.com/airbnb/lottie-android)：Lottie是一个适用于Android和iOS的移动库，它使用Bodymovin解析以JSON格式导出的Adobe After Effects动画并在移动设备上进行原生渲染，由Airbnb开源。
* [Balloon](https://github.com/skydoves/Balloon)：现代化且精致的工具提示，可通过Android的箭头和动画进行完全定制。
* [Pager Dots Indicator](https://github.com/tommybuonomo/dotsindicator)：用于Android中查看分页器的三个材质点指示器。
* [ShimmerLayout](https://github.com/team-supercharge/ShimmerLayout)：通过Supercharge为Android应用程序提供内存高效的闪烁效果。
* [React Native Tabbar Interaction](https://github.com/Mindinventory/react-native-tabbar-interaction)：漂亮的Tabbar交互与滑动插入FAB，专为具有RTL支持的React Native打造。
* [Android View Animations](https://github.com/daimajia/AndroidViewAnimations)：可爱的视图动画集合。
* [RecyclerView Animators](https://github.com/wasabeef/recyclerview-animators)：RecyclerView Animators是一个Android库，允许开发人员轻松创建带有动画的RecyclerView。
* [UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView)：UltimateRecyclerView是一个RecyclerView(ListView的高级和灵活版本)，具有下拉刷新、加载更多、滑动关闭、拖放、动画、粘性标题、滚动时显示或隐藏工具栏和FAB等许多其他功能。
* [HTextView](https://github.com/hanks-zyh/HTextView)：TextView支持自定义字体的动画效果。
* [ListViewAnimations](https://github.com/nhaarman/ListViewAnimations)：ListViewAnimations是一个开源Android库，允许开发人员轻松创建带有动画的ListView。
* [NineOldAndroids](https://github.com/JakeWharton/NineOldAndroids)：用于在平台所有版本上使用Honeycomb动画API的Android库。
* [Spruce](https://github.com/willowtreeapps/spruce-android)：Spruce是一个轻量级的动画库，可帮助编排屏幕上的动画。
* [Konfetti](https://github.com/DanielMartinus/Konfetti)：使用这个轻量级的五彩纸屑库，你可以轻松地在你的应用中庆祝大大小小的时刻。
* [SVGAPlayer](https://github.com/svga/SVGAPlayer-Android)：SVGAPlayer是一个轻量级的动画渲染器。
* [RecyclerViewItemAnimators](https://github.com/gabrielemariotti/RecyclerViewItemAnimators)：一个Android库，为RecyclerView元素提供简单的元素动画。
* [Like Button](https://github.com/jd-alexander/LikeButton)：Like Button是一个库，它允许你在喜欢某些东西时创建一个具有类似于Twitter心形的动画效果的按钮。
* [Aphid FlipView](https://github.com/openaphid/android-flip)：Aphid FlipView是一个UI组件，用于实现类似Flipboard的翻转动画。
* [ExpectAnim](https://github.com/florent37/ExpectAnim)：描述你的动画并运行。

* [WoWoViewPager](https://github.com/Nightonke/WoWoViewPager)：WoWoViewPager结合ViewPager和Animations来提供一种创建应用程序引导页的简单方法。
* [ViewAnimator](https://github.com/florent37/ViewAnimator)：流式的Android动画库。
* [GuillotineMenu](https://github.com/Yalantis/GuillotineMenu-Android)：简洁的库，提供了一种实现断头台式动画的简单方法。
* [TourGuide](https://github.com/worker8/TourGuide)：TourGuide是一个Android库，它允许你轻松添加指针、叠加层和工具提示，引导用户使用你的应用。
* [ViewPagerTransforms](https://github.com/ToxicBakery/ViewPagerTransforms)：包含在Android v13+上转换ViewPager滚动所需的常见动画的库。
* [AnimationEasingFunctions](https://github.com/daimajia/AnimationEasingFunctions)：Android动画缓动函数。
* [Android Ripple Background](https://github.com/skyfishjy/android-ripple-background)：为你的应用添加精美的涟漪动画。
* [Euclid](https://github.com/Yalantis/Euclid)：该项目是用户个人资料界面动画的实现。
* [Grav](https://github.com/glomadrian/Grav)：Grav是一个Android库，允许你根据点制作多个动画。
* [JazzyViewPager](https://github.com/jfeinstein10/JazzyViewPager)：一个易于使用的ViewPager，可添加一组精彩的自定义滑动动画。
* [AlphaPlayer](https://github.com/bytedance/AlphaPlayer)：AlphaPlayer是直播中台使用的一个视频动画特效SDK，由字节开源。
* [VectAlign](https://github.com/bonnyfone/vectalign)：使用VectorDrawables创建复杂变形动画的工具。
* [CircularAnim](https://github.com/XunMengWinter/CircularAnim)：Android水波动画帮助类，轻松实现View show/hide/startActivity()特效。
* [StarWars.Android](https://github.com/Yalantis/StarWars.Android)：该组件实现了过渡动画，将视图分解成小块。
* [ShootRefreshView](https://github.com/dinuscxj/ShootRefreshView)：ShootRefreshView是一个刷新动画。

#### Android插件框架

* [VirtualAPK](https://github.com/didi/VirtualAPK)：VirtualAPK是一个功能强大但轻量级的Android插件框架，由滴滴开源。
* [Shadow](https://github.com/Tencent/Shadow)：Shadow是一个腾讯自主研发的Android插件框架。
* [RePlugin](https://github.com/Qihoo360/RePlugin)：RePlugin是一个完整的Android插件解决方案，适合一般用途，由360开源。
* [DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin)：DroidPlugin是一个新的插件框架，它使宿主应用程序无需安装、修改和重新打包即可运行任何第三方APK。
* [Android Plugin Framework](https://github.com/limpoxe/Android-Plugin-Framework)：Android Plugin Framework是一个Android插件化框架，用于通过动态加载的方式免安装运行插件APK。
* [Wechat Spellbook](https://github.com/Gh0u1L5/WechatSpellbook)：Wechat Spellbook是一个使用Kotlin编写的开源微信插件框架。
* [ZeusPlugin](https://github.com/iReaderAndroid/ZeusPlugin)：最精简的插件补丁框架，日活千万级App验证稳定。
* [WXDynamicPlugin](https://github.com/wgllss/WXDynamicPlugin)：零反射、零HooK、全动态化，插件化框架。
* [Small](https://github.com/wequick/Small)：将应用程序拆分成小部分的小型框架。
* [Neptune](https://github.com/iqiyi/Neptune)：Neptune是一个灵活、强大且轻量级的Android插件框架，由爱奇艺开源。
* [APF](https://github.com/umeng/apf)：APF旨在为Android应用程序提供一个灵活、可扩展的框架。

#### Android WebView

* [VasSonic](https://github.com/Tencent/VasSonic)：VasSonic是腾讯VAS团队开发的轻量级高性能混合框架，旨在加速Android和iOS平台上网站的首屏显示。
* [AgentWeb](https://github.com/Justson/AgentWeb)：AgentWeb是一个基于Android WebView的强大库。
* [AdvancedWebView](https://github.com/delight-im/Android-AdvancedWebView)：增强型Android WebView组件，开箱即用。
* [CacheWebView](https://github.com/yale8848/CacheWebView)：CacheWebView通过拦截资源实现自定义缓存静态资源。
* [ByWebView](https://github.com/youlookwhat/ByWebView)：WebView全方面使用，JS交互、进度条、上传图片、错误页面、视频全屏播放、唤起原生App、获取网页源代码、被作为第三方浏览器打开、DeepLink。
* [FinestWebView](https://github.com/TheFinestArtist/FinestWebView-Android)：美观且可定制的Android Activity，可在应用程序内显示网页。
* [EinkBro](https://github.com/plateaukao/einkbro)：基于Android WebView的小型、快速的Web浏览器。
* [Compose WebView Multiplatform](https://github.com/KevinnZou/compose-webview-multiplatform)：JetBrains Compose多平台的WebView。
* [Compose WebView](https://github.com/KevinnZou/compose-webview)：Jetpack Compose的WebView包装器。
* [AndroidFastScroll](https://github.com/zhanghai/AndroidFastScroll)：适用于Android RecyclerView等的快速滚动。
* [JsBridge](https://github.com/pengwei1024/JsBridge)：一种更简单、可扩展的Android WebView与JavaScript双向通信框架。
* [Android Smart WebView](https://github.com/mgks/Android-SmartWebView)：Android Smart WebView是一种用于构建高级混合Android应用程序的现代开源解决方案。
* [CustomActionWebView](https://github.com/CarGuo/CustomActionWebView)：自定义WebView长按文本弹出选项。
* [WebViewUpgrade](https://github.com/JonaNorman/WebViewUpgrade)：该库实现了Android上WebView内核的免安装升级功能。
* [FastWebView](https://github.com/Ryan-Shz/FastWebView)：自定义本地缓存策略和资源加载策略，突破原生WebView缓存限制，实现多种缓存模式，支持离线加载和预加载，可大幅提升加载速度。
* [EasyBridge](https://github.com/easilycoder/EasyBridge)：一个简单的JS Bridge设计，提供Java和JavaScript之间通信的能力。
* [Codeview](https://github.com/avraampiperidis/Codeview)：Codeview是一个Android库，它能让你轻松便捷地在WebView中预览代码，并支持高亮和颜色显示。

#### Android加载库

* [AVLoadingIndicatorView](https://github.com/HarlonWang/AVLoadingIndicatorView)：AVLoadingIndicatorView是适用于Android的精美加载动画的集合。
* [Android SpinKit](https://github.com/ybq/Android-SpinKit)：Android加载动画。
* [Blurhash](https://github.com/mrousavy/react-native-blurhash)：BlurHash是图像占位符的紧凑表示。
* [LoadingDrawable](https://github.com/dinuscxj/LoadingDrawable)：一些精美的Android加载Drawable，可以像LoadingView或ProgressBar一样与任意View组合使用。
* [LoadSir](https://github.com/KingJA/LoadSir)：LoadSir是一个高效易用，低碳环保，扩展性良好的加载反馈页管理框架。
* [SmartRefreshHorizontal](https://github.com/scwang90/SmartRefreshHorizontal)：SmartRefreshHorizontal作为SmartRefreshLayout的扩展库，实现了横向刷新和加载的功能。
* [LoadingView](https://github.com/ldoublem/LoadingView)：简单的带有动画效果的加载控件。
* [Loader View Android](https://github.com/elye/loaderviewlibrary)：为TextView和ImageView提供在显示任何文本或图像之前显示闪烁(动画加载器)的功能。
* [MaterialLoadingProgressBar](https://github.com/lsjwzh/MaterialLoadingProgressBar)：MaterialLoadingProgressBar提供了一个样式化的ProgressBar，看起来像SwipeRefreshLayout的加载指示器。
* [ExcelPanel](https://github.com/zhouchaoyuan/excelPanel)：一个二维的RecyclerView，不仅可以加载历史数据，还可以加载未来的数据。
* [WaveLoadingView](https://github.com/tangqi92/WaveLoadingView)：提供逼真的波浪加载效果的Android库。
* [MkLoader](https://github.com/jamesnguyenhub/mkloader)：美观流畅的自定义加载视图。
* [FiftyShadesOf](https://github.com/florent37/FiftyShadesOf)：适用于Android的优雅Context-Care加载占位符。
* [LoadingLayout](https://github.com/czy1121/loadinglayout)：简单实用的页面多状态布局。
* [ZLoading](https://github.com/zyao89/ZLoading)：这是一个自定义Loading View库。
* [CircleProgressView](https://github.com/jenly1314/CircleProgressView)：CircleProgressView Android是一个圆形的进度动画控件，动画效果纵享丝滑。
* [MaterialImageLoading](https://github.com/florent37/MaterialImageLoading)：Material图片加载实现。
* [StateViews](https://github.com/medyo/StateViews)：StateViews基于ViewSwitcher机制，允许处理不同的应用程序状态，从加载到显示数据和错误视图。
* [KProgressHUD](https://github.com/liangchengcheng/android-loading-dialog)：Android版ProgressHUD工具，类似MBProgressHUD、SVProgressHUD。
* [LoadViewHelper](https://github.com/yangchaojiang/DemoLoadView)：切换加载中，加载失败，加载成功布局，支持全局和局部之自定义布局 定义一个LoadViewHelper所有界面通用
* [LoadingBar](https://github.com/xiandanin/LoadingBar)：极简使用的解耦Loading组件。
* [PageStateManager](https://github.com/hss01248/PageStateManager)：管理页面的加载、空、错误状态。
* [ButtonLoading](https://github.com/rasoulmiri/ButtonLoading)：漂亮的花式按钮加载。
* [Cosin](https://github.com/NikitaGordia/Cosin)：Android加载视图库。
* [AnimatedLoadingIndicator](https://github.com/yash786agg/AnimatedLoadingIndicator)：这是一个简单但有效的动画加载指示器，只需几行代码即可轻松使用。
* [StateLayout](https://github.com/junixapp/StateLayout)：一种无侵入，使用简单，无需修改现有布局，动态切换布局状态(Loading/Error/Empty/Content)的解决方案。
* [ArrowDrawable](https://github.com/wuyr/ArrowDrawable)：纯Paint实现的一个射箭效果，可用作Loading动画。

#### Android换肤框架

* [Android Skin Support](https://github.com/ximsfei/Android-skin-support)：Android Skin Support是一款Android换肤框架。
* [Android Skin Loader](https://github.com/fengjundev/Android-Skin-Loader)：一个通过动态加载本地皮肤包进行换肤的皮肤框架。
* [MagicaSakura](https://github.com/bilibili/MagicaSakura)：MagicaSakura是一个Android多主题库，支持日常多彩主题和夜间主题，由B站开源。
* [Colorful](https://github.com/garretyoder/Colorful)：Colorful是一个动态主题库，允许你轻松更改应用程序的配色方案。
* [MultipleTheme](https://github.com/dersoncheng/MultipleTheme)：该应用框架可以实现无缝换肤／切换夜间模式的需求。
* [AndroidChangeSkin](https://github.com/hongyangAndroid/AndroidChangeSkin)：一种完全无侵入的换肤方式，支持插件式和应用内，无需重启Activity。
* [ChangeSkin](https://github.com/hongyangAndroid/ChangeSkin)：基于插件式的Android换肤框架，支持App内和或者外部插件式提供资源的换肤方案，无需重启Activity。
* [ThemeSkinning](https://github.com/burgessjp/ThemeSkinning)：Android主题换肤的开源库。
* [SkinSprite](https://github.com/geminiwen/SkinSprite)：无需重新创建Activity即可更改昼夜模式的另一种解决方案。
* [Android Skin](https://github.com/MeetYouDevs/Android-Skin)：极简单的Android换肤框架，无缝支持第三方控件，由美柚开源。
* [PaintedSkin](https://github.com/CoderAlee/PaintedSkin)：一款解决Android App换肤框架，极低的侵入性与学习成本。

####  APK解析器

* [APK Parser](https://github.com/hsiafan/apk-parser)：APK解析器库，用于解码二进制XML文件，获取APK元信息。
* [APKParser](https://github.com/jaredrummler/APKParser)：安卓APK解析器。
* [Android APK Parser](https://github.com/joakime/android-apk-parser)：从Android APK文件中获取基本信息。

## GUI开发/程序

这里列出了Java中常用的Swing、JavaFX开发库，以及一些Java开发的GUI工具和游戏引擎。

#### GUI框架

* [Swing](https://docs.oracle.com/en/java/javase/21/docs/api/java.desktop/javax/swing/package-summary.html)：Swing提供一组轻量级组件，可以在所有平台上以相同的方式工作。
* [JavaFX](https://github.com/openjdk/jfx)：JavaFX是一个开源的客户端应用程序平台，适用于基于Java SE的桌面、移动和嵌入式系统，Oracle开源。
* [Jetpack Compose](https://github.com/JetBrains/compose-multiplatform)：Compose Multiplatform是一个声明式框架，用于使用Kotlin跨多个平台共享UI，由JetBrains开发。
* [Eclipse SWT](https://github.com/eclipse-platform/eclipse.platform.swt)：SWT是一个用于Java的开源小部件工具包，由IBM开源。
* [HumbleUI](https://github.com/HumbleUI/HumbleUI)：Humble UI是一个基于Clojure的桌面UI框架。
* [TotalCross](https://github.com/TotalCross/totalcross)：TotalCross是一款帮助跨平台应用程序开发的工具包。
* [NetBeans Platform](https://netbeans.apache.org/tutorial/main/kb/docs/platform/)：NetBeans Platform是一个广泛的Java框架，可以在其上构建大型桌面应用程序。
* [QtJambi](https://github.com/OmixVisualization/qtjambi)：QtJambi是Java编程语言的Qt绑定，最初由Qt公司的前身Trolltech开发。
* [ImGui](https://github.com/kotlin-graphics/imgui)：这是ImGui的Kotlin重写，一个用于C++的无膨胀图形用户界面库。
* [JImGUI](https://github.com/ice1000/jimgui)：ImGUI的的纯Java绑定。
* [ImGui Java](https://github.com/SpaiR/imgui-java)：ImGui基于JNI的绑定。
* [LEGUI](https://github.com/SpinyOwl/legui)：Java OpenGL GUI库，专为与最新的LWJGL(LWJGL 3)一起使用而创建。
* [VisUI](https://github.com/kotcrab/vis-ui)：VisUI允许在LibGDX中使用scene2d.ui创建漂亮的界面。
* [PolyUI](https://github.com/Polyfrost/polyui-jvm)：PolyUI是一个由Polyfrost开发的声明式UI框架。
* [Kotlin LibUI](https://github.com/msink/kotlin-libui)：libui是一个轻量级的C语言多平台UI库，使用此绑定，你可以开发跨平台且外观原生的GUI程序。
* [Membrane](https://github.com/phronmophobic/membrane)：Membrane提供了构建用户界面所需的所有工具。
* [Apache Pivot](https://github.com/apache/pivot)：Pivot是一个用Java构建丰富互联网应用程序的平台，其中WTK工具包是它的图形组件，由VMware开源。

#### 移动开发框架

* [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform)：Compose Multiplatform是一个声明式框架，用于使用Kotlin跨多个平台共享UI，由JetBrains开发。
* [CodenameOne](https://github.com/codenameone/CodenameOne)：Codename One是面向Java和Kotlin开发人员的移动优先跨平台环境。
* [Multi-OS Engine](https://github.com/multi-os-engine/multi-os-engine)：Multi-OS Engine为iOS平台API提供了Java运行时和Java接口，用于开发具有原生外观、原生性能以及可从Android应用程序移植常见Java逻辑模块的原生iOS应用程序。
* [MobileUI](https://mobileui.dev/)：MobileUI是第一个适用于iOS和Android的基于Java的原生UI框架。
* [OpenJDK Mobile](https://github.com/openjdk/mobile)：Mobile的目标是专注于将JDK移植到iOS、Android和Windows等流行的移动平台。

#### Swing

* [Lanterna](https://github.com/mabe02/lanterna)：Lanterna是一个Java库，允许你在纯文本环境中编写简单的半图形用户界面，与C库curses非常相似，但具有更多功能。
* [JFormDesigner](https://www.formdev.com/)：JFormDesigner是一款专业的Java Swing用户界面GUI设计器。
* [Radiance](https://github.com/kirill-grouchnikov/radiance)：Radiance是一个库集合，用于基于Ephemeral设计系统编写现代、优雅且快速的Swing应用程序。
* [JxCapture](https://teamdev.com/jxcapture/)：JxCapture是一种跨平台、能Java应用程序提供综合屏幕抓取API的库程序。
* [AutoComplete](https://github.com/bobbylight/AutoComplete)：AutoComplete是Swing JTextComponents的代码完成库，具有可用于RSyntaxTextArea实例的增强功能。
* [Sierra](https://github.com/HTTP-RPC/Sierra)：Sierra是一个用于简化Java Swing应用程序开发的开源框架。
* [Cinch](https://github.com/palantir/Cinch)：管理MVC模式的组件操作/事件绑定的Java库，由Palantir开源。
* [jGAF](https://github.com/pgdurand/jGAF)：jGAF是一个旨在促进为Java平台创建跨平台图形应用程序的库。
* [MindFusion.Swing](https://mindfusion.dev/java-pack.html)：MindFusion.Swing Pack为你的桌面应用提供丰富的数据界面控件，集成在一个高价值的套件中。
* [Projector Server](https://github.com/JetBrains/projector-server)：用于远程运行Swing应用程序的服务器端库，由JetBrains开源。
* [ReflectionUI](https://github.com/dotxyteam/ReflectionUI)：ReflectionUI是一个免费的Java GUI构建器/生成器库。
* [Compositor](https://compositor.sourceforge.net/)：Compositor让你可以将应用程序的UI与代码分开描述。
* [MDIUtilities](https://mdiutilities.sourceforge.io/)：MDIUtilities是一个提供各种实用程序类的Java库，主要用于Swing或JavaFX开发。
* [Marathon](https://github.com/jalian-systems/marathonv5)：Marathon是一款用于录制、回放和重构使用Swing或FX组件开发的Java GUI程序测试用例的工具。
* [Codion](https://github.com/codion-is/codion)：Codion是一个全栈Java富客户端桌面CRUD应用程序框架。
* [Jameica](https://github.com/willuhn/jameica)：Jameica是一个用于开发富客户端桌面应用程序的Java框架和运行时平台。

#### Swing主题库

* [FlatLaf](https://github.com/JFormDesigner/FlatLaf)：FlatLaf是Java Swing桌面应用程序的现代开源跨平台LaF。
* [Material Color Utilities](https://github.com/material-foundation/material-color-utilities)：Material Color Utilities通过一组包含算法和实用程序的颜色库为动态颜色提供支持，这些算法和实用程序可让你更轻松地在应用中开发颜色主题和方案。
* [BeautyEye](https://github.com/JackJiang2011/beautyeye)：BeautyEye是一款Java Swing跨平台外观实现。
* [Jewel](https://github.com/JetBrains/jewel)：Jewel旨在在Compose Desktop中重新创建IntelliJ平台的新UI Swing LaF，提供桌面优化的主题和组件集，由JetBrains开源。
* [WebLaf](https://github.com/mgarin/weblaf)：WebLaf是一个完全开源的外观和组件库，用纯Java编写，用于跨平台桌面Swing应用程序。
* [Darklaf](https://github.com/weisJ/darklaf)：Darklaf是基于Darcula-Laf的主题LaF。
* [VAqua](https://github.com/violetlib/vaqua)：VAqua是一种Java Swing外观，在macOS上运行，模拟标准macOS UI组件的外观和行为。
* [VTerminal](https://github.com/Valkryst/VTerminal)：用于Java的新LaF，允许基于网格显示具有自定义前景色/背景色、字体大小和伪着色器的Unicode字符。
* [Darcula](https://github.com/bulenkov/Darcula)：Darcula是Java桌面应用程序的LaF和代码编辑器主题。
* [Synthetica](https://www.jyloo.com/)：Synthetica是Swing的LaF，基于Synth，通过主题为Swing的核心组件提供了许多不同的外观，包括圆形边框、阴影弹出菜单和漂亮的图标。
* [Java Bootstrap LaF](https://github.com/danfickle/java-bootstrap-laf)：基于Bootstrap的Java Swing LaF。
* [LittleLuck](https://github.com/freeseawind/littleluck)：LittleLuck是Java Swing跨平台外观实现。
* [Sea Glass](https://github.com/khuxtable/seaglass)：Sea Glass是适用于JRE 1.6及更高版本的Java可插拔LaF。
* [FlatSwing](https://github.com/Mommoo/FlatSwing)：一个由平面设计制成的漂亮的Java Swing库。
* [JTattoo](https://github.com/michael-hagen/JTattoo)：JTattoo是一个基于Swing的应用程序的LaF库。
* [JGoodies Looks](https://www.jgoodies.com/freeware/libraries/looks/)：JGoodies的Windows L&F系列能让你的Swing应用看起来更美观。

#### Swing UI库

* [Material UI Swing](https://github.com/atarw/material-ui-swing)：适用于Java Swing的现代Material Design UI。
* [Swing9patch](https://github.com/JackJiang2011/Swing9patch)：Swing9patch工程是一组很酷的Java Swing可重用组件或UI效果。
* [SnapKit](https://github.com/reportmill/SnapKit)：SnapKit是一个现代Java UI库和工具，用于创建丰富的Java客户端应用程序。
* [Lemur](https://github.com/jMonkeyEngine-Contributions/Lemur)：Lemur是用于在jMonkeyEngine应用程序中制作用户界面的GUI工具包。
* [Griffon](https://github.com/griffon/griffon)：Griffon是JVM的桌面应用程序开发平台，受Grails的启发，Griffon利用了约定优于配置、模块化和选择自由等概念。
* [JGoodies](https://www.jgoodies.com/downloads/libraries/)：JGoodies可帮助美化桌面应用程序并更快地构建设计良好、一致的视图。
* [Eclipse Nebula](https://github.com/eclipse/nebula)：该项目包含大量UI元素，可在基于Java和SWT的胖或瘦客户端应用程序中使用。
* [JIDE](https://github.com/jidesoft/jide-oss)：JIDE提供专业的Java UI组件，专注于为软件开发人员提供富客户端应用程序。
* [Swing Modal Dialog](https://github.com/DJ-Raven/swing-modal-dialog)：使用FlatLaf定制的Java Swing UI库。
* [Swing Material](https://github.com/leMaik/swing-material)：Swing的Material Design组件和实用程序的集合。
* [KControls](https://github.com/k33ptoo/KControls)：KControls专为Java Swing打造，旨在美化用户界面，赋予UI现代化的外观。
* [SwingTree](https://github.com/globaltcad/swing-tree)：SwingTree是一个基于Swing的UI框架，用于流式地创建无样板代码且基于组合的Swing用户界面。
* [Sway](https://github.com/tbee/sway)：Java Swing UI框架的更现代风格的API。

#### Swing组件库

* [SwingBits](https://github.com/eugener/oxbow)：SwingBits是Java Swing Toolkit的有用组件和实用程序的集合。
* [UiBooster](https://github.com/Milchreis/UiBooster)：UiBooster是一个精益库，用于为实用工具创建快速且简单的对话框。
* [JXMapViewer2](https://github.com/msteiger/jxmapviewer2)：该项目基于SwingX-WS的JXMapViewer组件。
* [HMeter](https://sourceforge.net/projects/hasnatmeter/)：HMeter是一个高度可定制的Java Swing小部件，旨在直观地显示水平进度。
* [Notify](https://github.com/dorkbox/Notify)：适用于Java 8+的桌面和应用程序的Linux、MacOS或Windows弹出窗口。
* [DJ Native Swing](https://github.com/Chrriis/DJ-Native-Swing)：DJ Native Swing库允许将一些原生组件轻松集成到Swing应用程序中，并提供一些本机实用程序来增强Swing的API。
* [RSyntaxTextArea](https://github.com/bobbylight/RSyntaxTextArea)：RSyntaxTextArea是一个用于Java Swing应用程序的可定制的语法突出显示文本组件。
* [SystemTray](https://github.com/dorkbox/SystemTray)：对Java 8+上的Swing/AWT、GtkStatusIcon和AppIndicator提供专业、跨平台的SystemTray支持。
* [AsciiPanel](https://github.com/trystan/AsciiPanel)：AsciiPanel模拟Code page 437 ASCII终端显示，它支持Code page 437的全部256个字符、任意前景色、任意背景色和任意终端大小。
* [Two Slices](https://github.com/sshtools/two-slices)：用于Windows、Mac OS X和Linux上的Java桌面通知的简单库。
* [Swing Console](https://github.com/mikera/swing-console)：Swing文本控制台组件，可用于提供类似于Java中的终端的功能。
* [JTouchBar](https://github.com/Thizzer/jtouchbar)：用于在受支持的MacBook上使用touchbar API的Java库。
* [JSplitButton](https://github.com/rhwood/jsplitbutton)：Java Swing的分割按钮控件的简单实现。
* [JTreeTable](https://github.com/javagl/JTreeTable)：JTreeTable实现。
* [File Manager](https://github.com/javadev/file-manager)：Java/Swing基本文件管理器。
* [Fireplace](https://github.com/bric3/fireplace)：Java Swing火焰图组件。
* [JInputValidator](https://github.com/rhwood/jinputvalidator)：Java Swing的InputVerifier，在验证组件的右侧显示验证状态。
* [SwingX](https://github.com/arotenberg/swingx)：SwingX是一个扩展Java Swing库的组件和实用程序库。
* [SwingBox](https://github.com/radkovo/SwingBox)：SwingBox是一个Java Swing组件，允许显示包含CSS支持的(X)HTML文档。
* [Swing Toast Notifications](https://github.com/DJ-Raven/swing-toast-notifications)：适用于Java桌面应用程序的Swing Toast通知。
* [JToaster](https://jtoaster.sourceforge.net/)：JToaster是一个用于Swing应用的Java工具类，它会显示一个从屏幕底部升起的动画框，配有通知消息和/或相关的图片。
* [TableFilter](https://coderazzi.net/tablefilter/)：TableFilter是一组Swing组件，用于支持用户自定义的表格过滤功能。
* [GC4S](https://github.com/sing-group/GC4S)：GC4S是一个开源库，为Swing提供面向生物信息学的GUI组件集合，由维戈大学开源。
* [GlazedLists](https://github.com/glazedlists/glazedlists)：Java的开源List转换。
* [JIDE Components](https://www.jidesoft.com/products/component.htm)：JIDE Components包含一系列非常实用的组件。
* [JIDE Dialogs](https://www.jidesoft.com/products/dialogs.htm)：JIDE Dialogs是一个使对话框创建更简单的产品。
* [JIDE Code Editor](https://www.jidesoft.com/products/editor.htm)：JIDE Code Editor是一个源代码编辑器组件。
* [JIDE Dashboard](https://www.jidesoft.com/products/dashboard.htm)：JIDE Dashboard提供了一个占位符来展示各种小部件。
* [JIDE Grids](https://www.jidesoft.com/products/grids.htm)：JIDE Grids是一个包含所有JTable相关组件的集合。

#### Swing Dock库

* [ModernDocking](https://github.com/andrewauclair/ModernDocking)：Modern Docking是一个简单的框架，旨在为Java Swing应用程序添加程序坞功能。
* [VLDocking](https://github.com/cmadsen/vldocking)：VLDocking是一个商业级的Swing框架，提供丰富的Dock功能，可以轻松地与现有应用程序集成。
* [DockingFrames](https://github.com/Benoker/DockingFrames)：DockingFrames是一个开源Java Swing Dock框架。
* [FlexDock](https://github.com/opencollab/flexdock)：FlexDock是一个用于跨平台Swing应用程序的Java Dock框架。
* [Sanaware Java Docking](https://sanaware.com/)：Sanaware Java Docking是一个用于管理Java Swing应用程序窗口的库。
* [JIDE Docking](https://www.jidesoft.com/products/dock.htm)：JIDE Docking框架提供了一个非常强大且易于使用的可扩展窗口解决方案。

#### Swing布局库

* [Yoga](https://github.com/facebook/yoga)：Yoga是一个可嵌入的高性能Flexbox布局引擎，具有多种语言的绑定，由Facebook开源。
* [TableLayout](https://github.com/EsotericSoftware/tablelayout)：TableLayout是一个轻量级Java库，用于使用逻辑表(类似于HTML表格)设置UI小部件的位置和大小。
* [SlidingLayout](https://github.com/AurelienRibon/sliding-layout)：功能强大的Java Swing面板/布局，具有涉及滑动子面板的炫酷过渡。
* [Swing Library](https://github.com/oliverwatkins/swing_library)：该库包含许多Java Swing框架所缺少的高级组件和布局管理器。
* [PanelMatic](https://github.com/codeworth-gh/PanelMatic)：PanelMatic是一个成熟的Swing工具库，旨在轻松创建复杂的高质量布局。
* [KGradientPanel](https://github.com/k33ptoo/KGradientPanel)：Swing渐变面板。
* [JGoodies FormLayout](https://www.jgoodies.com/freeware/libraries/forms/)：JGoodies FormLayout帮助你快速布局并实现一致的Swing面板。

#### Swing选择器

* [LGoodDatePicker](https://github.com/LGoodDatePicker/LGoodDatePicker)：Java Swing日期选择器，易于使用、美观、功能强大且本地化。
* [Swing Datetime Picker](https://github.com/DJ-Raven/swing-datetime-picker)：使用Java Swing的简单日期时间选择器实现。
* [JDatePicker](https://github.com/JDatePicker/JDatePicker)：JDatePicker和JDatePanel是一组用于Java Swing应用程序的高级DatePicker控件。
* [ColorPick](https://github.com/dheid/colorpicker)：一个使用Java Swing的漂亮颜色选择器，包含可视颜色选择和用于手动输入RGB和HSB值的输入框。
* [JnaFileChooser](https://github.com/steos/jnafilechooser)：使用Windows原生对话框的Java文件选择器API。

#### Swing图表库

* [XChart](https://github.com/knowm/XChart)：XChart是一个轻量且方便的数据绘制库，旨在在尽可能短的时间内从数据到图表，并消除自定义图表样式时的猜测工作。
* [JFreeChart](https://github.com/jfree/jfreechart)：JFreeChart是一个适用于Java平台的综合免费图表库，可在客户端(JavaFX和Swing)或服务器端使用。
* [Prefuse](https://github.com/prefuse/Prefuse)：Prefuse是一个基于Java的工具包，用于构建交互式信息可视化应用程序，由加州大学伯克利分校开源。
* [Lets Plot](https://github.com/JetBrains/lets-plot)：Lets Plot是一个基于图形语法原理构建的多平台绘图库，由JetBrains开源。
* [Orson Charts](https://github.com/jfree/orson-charts)：Orson Charts是一个用于Java平台的3D图表库，可以生成各种3D图表，用于客户端应用程序(JavaFX和Swing)和服务器端应用程序(导出为PDF、SVG、PNG和JPEG)。
* [Matplotlib4j](https://github.com/sh0nk/matplotlib4j)：Matplotlib4j是一个用于Java、Scala和Kotlin的简单绘图库。
* [Ardor3D](https://github.com/Renanse/Ardor3D)：Ardor3D是一个基于Java的免费、面向专业的开源3D图形引擎。
* [JGraphX](https://github.com/jgraph/jgraphx)：JGraphX是一个Java Swing图表库。
* [JMathPlot](https://github.com/yannrichet/jmathplot)：Java交互式2D和3D绘图。
* [Matplot3D](https://gitee.com/tanling8334/Matplot3D-for-Java)：Matplot3D是一个基于Java环境开发的三维图形图表组件。
* [Java-GTK](https://github.com/bailuk/java-gtk)：Java的GTK 4绑定。
* [Mil Sym Java](https://github.com/missioncommand/mil-sym-java)：Mil Sym Java是一组陈旧的Java库，已在美国陆军任务指挥软件中使用多年。
* [VTM](https://github.com/mapsforge/vtm)：OpenGL矢量地图库-在Android、iOS、桌面和浏览器上运行。
* [JPlotter](https://github.com/hageldave/JPlotter)：使用AWT和LWJGL的基于OpenGL的Java 2D绘图库。
* [GRAL](https://github.com/eseifert/gral)：GRAL是一个用于显示图表的免费Java库。
* [Java Swing Custom Chart](https://github.com/DJ-Raven/java-swing-custom-chart)：Java Swing自定义图表库。
* [JMonet](https://github.com/defano/jmonet)：JMonet是一个易于使用的工具包，用于将MacPaint或Microsoft Paint中的绘画工具集成到Java Swing或JavaFX应用程序中。
* [Simple Graphics](https://github.com/academia-de-codigo/simple-graphics)：带有鼠标和键盘事件的简易图形库。
* [JIDE Gantt Chart](https://www.jidesoft.com/products/gantt.htm)：JIDE Gantt Chart是一个纯粹的Java Swing库，使你可以在Swing应用中创建甘特图成为可能。
* [JIDE Charts](https://www.jidesoft.com/products/charts.htm)：JIDE Charts是一个强大且灵活的图表软件。

#### Swing测试库

* [SwingLibrary](https://github.com/robotframework/SwingLibrary)：SwingLibrary是一个用于测试Java Swing应用程序的机器人框架库。
* [AssertJ Swing](https://github.com/assertj/assertj-swing)：该项目提供了一个简单直观的API，用于Swing用户界面的功能测试。
* [FEST-Swing](https://github.com/alexruiz/fest-swing-1.x)：该项目为Swing用户界面的功能测试提供了一个简单直观的API，从而使测试变得紧凑、易于编写和阅读，就像规范一样。
* [UISpec4J](https://github.com/UISpec4J/UISpec4J)：UISpec4J是一个开源功能和/或单元测试库，用于基于Swing的Java应用程序。
* [Automaton](https://github.com/renatoathaydes/Automaton)：Automaton是一个框架，它可以轻松测试使用Swing、JavaFX或两者开发的Java GUI。
* [Caciocavallo](https://github.com/CaciocavalloSilano/caciocavallo)：Caciocavallo是一个无头Swing UI测试库。

#### JavaFX

* [FXLauncher](https://github.com/edvin/fxlauncher)：JavaFX应用程序的自动更新启动器。
* [Scene Builder](https://github.com/gluonhq/scenebuilder)：Scene Builder是一款拖放式UI设计工具，可实现快速桌面和移动应用程序开发。
* [RxJavaFX](https://github.com/ReactiveX/RxJavaFX)：RxJavaFX是一个轻量级库，用于将JavaFX事件转换为RxJava Observables/Flowables，反之亦然。
* [WorkbenchFX](https://github.com/dlsc-software-consulting-gmbh/WorkbenchFX)：用于JavaFX应用程序的轻量级RCP框架。
* [MVVMFX](https://github.com/sialcasa/mvvmFX)：MVVMFX是一个应用程序框架，它为你提供使用JavaFX实现MVVM模式所需的组件。
* [JWM](https://github.com/HumbleUI/JWM)：JWM是一个跨平台的Java窗口管理和操作系统集成库。
* [ReactFX](https://github.com/TomasMikula/ReactFX)：ReactFX是对JavaFX响应式编程技术的补充。
* [Substrate](https://github.com/gluonhq/substrate)：Gluon Substrate是一款将JavaFX客户端应用程序转换为桌面、移动和嵌入式设备的本机可执行文件的工具。
* [WebFX](https://github.com/webfx-project/webfx)：WebFX是一个由GWT提供支持的JavaFX应用程序转译器，它可以将JavaFX应用程序转换为传统的独立纯JavaScript Web应用程序。
* [TestFX](https://github.com/TestFX/TestFX)：TestFX是一个用于简单、干净地测试JavaFX应用程序和组件的库。
* [TornadoFX](https://github.com/edvin/tornadofx)：TornadoFX是一个适用于Kotlin编程语言的小型轻量级JavaFX框架。
* [ValidatorFX](https://github.com/effad/ValidatorFX)：ValidatorFX是JavaFX的表单验证库。
* [EasyBind](https://github.com/TomasMikula/EasyBind)：EasyBind在创建自定义绑定时利用Lambda来减少样板文件，为Bindings.select*方法提供类型安全的替代方案，并向ObservableValue添加单子操作。
* [Advanced Bindings](https://github.com/manuel-mauky/advanced-bindings)：Advanced Bindings是一些有用的帮助程序和自定义绑定实现的集合，用于简化大量基于JavaFX的属性和绑定的应用程序的开发。
* [Gluon Maps](https://github.com/gluonhq/maps)：Gluon Maps提供了一种将OpenStreetMaps集成到JavaFX应用程序中的简单方法，它速度极快，并提供图层叠加、多个图块集等等。
* [LibRawFX](https://github.com/lanthale/LibRawFX)：集成适用于所有主要操作系统(Linux、Windows、OSX)的JavaFX的LibRaw库。
* [UpdateFX](https://github.com/vinumeris/updatefx)：UpdateFX是一个小型、简单的JavaFX应用程序自动在线更新框架。
* [ReduxFX](https://github.com/netopyr/reduxfx)：ReduxFX是一组库，使你能够在JavaFX应用程序中使用函数式响应式编程。
* [EasyFXML](https://github.com/Tristan971/EasyFXML)：EasyFXML是一组固执己见的工具，旨在简化健壮且模块化的JavaFX应用程序的开发。
* [JRebirth](https://github.com/JRebirth/JRebirth)：JRebirth是一个JavaFX应用程序框架。
* [JPro](https://www.jpro.one/)：用于在浏览器中运行Java的工具平台。
* [SupernautFX](https://github.com/SupernautApp/SupernautFX)：Supernaut.FX是一个用于JavaFX应用程序的轻量级依赖注入框架。
* [JavaFX Weaver](https://github.com/rgielen/javafx-weaver)：JavaFX和FXML的依赖注入支持库。
* [AfterburnerFX](https://github.com/AdamBien/afterburner.fx)：AfterburnerFX是一个基于约定优于配置和依赖注入的简约JavaFX MVP框架。
* [LiveDirsFX](https://github.com/TomasMikula/LiveDirsFX)：LiveDirsFX是目录监视程序、目录树模型(用于TreeView)和简单的异步文件I/O工具的组合。
* [APX](https://github.com/othreecodes/APX)：用于制作MVC类型桌面应用程序的JavaFX库。
* [Basilisk](https://github.com/basilisk-fw/basilisk)：Basilisk是JVM的桌面/移动应用程序开发平台。
* [DataFX](https://github.com/guigarage/DataFX)：DataFX是一个旨在使JavaFX UI控件中检索、处理、填充、查看和编辑数据更加容易的项目。
* [JacpFX](https://github.com/JacpFX/JacpFX)：JacpFX项目是一个API，用于使用JavaFX、Spring和类似Actor的组件方法以MVC风格创建富客户端。
* [WellBehavedFX](https://github.com/FXMisc/WellBehavedFX)：该项目为JavaFX定义和覆盖事件处理程序(例如键盘快捷键)提供了更好的机制。
* [SynchronizeFX](https://github.com/zeiss-digital-innovation/SynchronizeFX)：SynchronizeFX支持在本地计算机和网络上的不同JVM之间进行属性绑定。
* [JideFX](https://github.com/jidesoft/jidefx-oss)：JideFX通用层是JavaFX平台各种扩展和实用程序的集合。

#### JavaFX主题库

* [JFoenix](https://github.com/sshahine/JFoenix)：JFoenix是一个开源Java库，它使用Java组件实现Google Material Design。
* [MaterialFX](https://github.com/palexdev/MaterialFX)：MaterialFX是一个开源Java库，为JavaFX提供Material Design组件。
* [AtlantaFX](https://github.com/mkpaz/atlantafx)：现代JavaFX CSS主题集合，带有附加控件。
* [NSMenuFX](https://github.com/0x4a616e/NSMenuFX)：一个用于自定义macOS菜单栏的简单库，为你的JavaFX应用程序提供更原生的LaF。
* [JFXtras Styles](https://github.com/JFXtras/jfxtras-styles)：Java、JavaFX主题或LaF，目前包含JMetro主题。
* [JBootX](https://github.com/dicolar/jbootx)：JavaFX Bootstrap主题库。
* [BootstrapFX](https://github.com/kordamp/bootstrapfx)：BootstrapFX是Twitter Bootstrap的部分移植，它主要提供与原始样式非常相似的CSS样式表，同时针对JavaFX独特的CSS风格进行定制。
* [Transit](https://github.com/dukke/Transit)：Transit是一个现代JavaFX主题/风格，可用于为应用程序提供不同的LaF。
* [SyntheticaFX](https://www.jyloo.com/syntheticafx/)：SyntheticaFX提供主要为桌面上的专业商业应用程序制作的主题和组件。
* [JavaFX Fluent Theme](https://github.com/Eroica/javafx-fluent-theme)：这是JavaFX的自定义主题，可让你的应用程序看起来像Windows 11(WinUI)程序。
* [MonetFX](https://github.com/Glavo/MonetFX)：MonetFX为JavaFX提供了对Material 3颜色系统的支持。
* [jSystemThemeDetector](https://github.com/Dansoftowner/jSystemThemeDetector)：用于检测(桌面)操作系统是否使用深色UI主题的Java库。
* [FluentFX](https://github.com/Ivan-Kalatchev/FluentFX)：FluentFX是一个带有主题和一些控件的JavaFX库。
* [DarculaFX](https://github.com/mouse0w0/darculafx)：JavaFX Darcula主题。
* [FlatBee](https://github.com/marcschuler/FlatBee)：一个扁平化、流式的JavaFX CSS主题。
* [FXThemes](https://github.com/dukke/FXThemes)：用于JavaFX高级主题开发的实用程序类。
* [GNDecorator](https://github.com/gleidsonmt/GNDecorator)：适用于JavaFX应用程序的现代窗口装饰器。

#### JavaFX样式库

* [ControlsFX](https://github.com/controlsfx/controlsfx)：ControlsFX是JavaFX的一个开源项目，旨在提供真正高质量的UI控件和其他工具来补充核心JavaFX发行版。
* [PreferencesFX](https://github.com/dlsc-software-consulting-gmbh/PreferencesFX)：用于轻松创建应用程序设置/首选项UI的框架。
* [CustomStage](https://github.com/Oshan96/CustomStage)：CustomStage是一个JavaFX Undecorated Stage，它包含默认JavaFX Decorated Stage的原生行为，并且完全可设计样式。
* [StagePro](https://github.com/techsenger/stagepro)：StagePro是一个用于创建自定义JavaFX Stage的库，可以对外观和布局进行细粒度的控制。
* [CSSFX](https://github.com/McFoggy/cssfx)：CSSFX通过在运行的应用程序中提供CSS重新加载功能来提高开发人员的工作效率。
* [FXSkins](https://github.com/dukke/FXSkins)：现有JavaFX控件的新外观集合，这些皮肤将为应用程序中使用的控件添加更多功能，几乎不需要更改代码。
* [JSilhouette](https://github.com/kordamp/jsilhouette)：JSilhouette为Java应用程序提供了额外的形状，目前支持JavaFX。
* [MDFX](https://github.com/JPro-one/markdown-javafx-renderer)：MDFX是一个简单的JavaFX Markdown渲染器。
* [XmFX](https://gitee.com/xm2013/xmfx)：针对企业级的JavaFX UI，简单易用。
* [Actlist](https://github.com/actlist/actlist)：Actlist是一个实用平台，可以轻松简单地执行你自己的行为列表。
* [Tornado FXControls](https://github.com/edvin/tornadofx-controls)：JavaFX的CSS样式控件库。
* [FX BorderlessScene](https://github.com/goxr3plus/FX-BorderlessScene)：未修饰的JavaFX场景，实现了移动、调整大小、最小化、最大化、关闭和Windows Aero Snap控件。
* [TUIOFX](http://tuiofx.org/)：TUIOFX工具包旨在支持想要开发共享交互表面(如支持TUIO协议的多用户、多点触控桌面和墙壁)的Java开发人员。
* [Undecorator](https://github.com/in-sideFX/Undecorator)：使用自定义皮肤来装饰未装饰的JavaFX阶段。
* [VFX](https://github.com/wkgcass/vfx)：JavaFX UI组件库。
* [VirtualizedFX](https://github.com/palexdev/VirtualizedFX)：VirtualizedFX是一个开源Java库，它提供虚拟化组件来显示大量数据，而不会因仅渲染其中一部分而影响性能。
* [JavaFX Blur](https://github.com/kieferlam/JavaFX-Blur)：该库提供了使用JNI调用本机窗口管理器功能将模糊效果应用于JavaFX Stage的方法。

* [JavaFX UI](https://github.com/xjw580/javafx-ui)：适用于JavaFX的UI组件库。

#### JavaFX组件库

* [RichTextFX](https://github.com/FXMisc/RichTextFX)：RichTextFX为JavaFX提供了一个节省内存的TextArea，允许开发人员设置文本范围的样式、内联显示自定义对象(不再需要HTMLEditor)，并仅在必要时覆盖特定的默认行为。
* [JFXtras](https://github.com/JFXtras/jfxtras)：JavaFX的支持库，包含工具程序类、扩展布局、控件和其他有趣的小部件。
* [DashboardFx](https://github.com/gleidsonmt/DashboardFx)：该项目是为JavaFX创建的自定义组件集的一部分。
* [GemsFX](https://github.com/dlsc-software-consulting-gmbh/GemsFX)：用于渲染SVG图像文件的控件，利用jsvg库，即使在缩放时也能确保高清质量。
* [CalendarFX](https://github.com/dlsc-software-consulting-gmbh/CalendarFX)：用于创建基于JavaFX的复杂日历视图的Java框架。
* [RXControls](https://github.com/leewyatt/rxcontrols)：RXControls是一个JavaFX自定义组件库，密码可见组件、轮播图组件、动态按钮组件等。
* [Tornado FXControls](https://github.com/edvin/tornadofx-controls)：JavaFX的CSS可样式控件。
* [PDFViewFX](https://github.com/dlsc-software-consulting-gmbh/PDFViewFX)：允许应用程序显示PDF文件的自定义控件。
* [PDFViewerFX](https://github.com/Dansoftowner/PDFViewerFX)：用于在JavaFX应用程序内显示/查看PDF文档的库。
* [UnitFX](https://github.com/dlsc-software-consulting-gmbh/UnitFX)：UnitFX是一个轻量级框架，用于创建基于UOM的文本字段输入控件。
* [PhoneNumberFX](https://github.com/dlsc-software-consulting-gmbh/PhoneNumberFX)：该仓库包含一个控件，用于输入世界上任何国家/地区的有效电话号码。
* [Monocle](https://github.com/TestFX/Monocle)：Monocle是针对嵌入式系统的JavaFX Glass窗口组件的实现。
* [MonacoFX](https://github.com/miho/MonacoFX)：JavaFX编辑器节点，基于驱动VS Code的强大Monaco编辑器。
* [JavaFXSVG](https://github.com/codecentric/javafxsvg)：用于向JavaFX添加SVG支持，允许像任何其他图像类型一样使用SVG图形。
* [FormsFX](https://github.com/dlsc-software-consulting-gmbh/FormsFX)：用于轻松创建JavaFX UI表单的框架。
* [Cognitive](https://github.com/carldea/cognitive)：基于MVVM UI架构模式的轻量级JavaFX表单框架。
* [FXParallax](https://github.com/dukke/FXParallax)：用于为Java添加视差效果的控件。
* [UndoFX](https://github.com/FXMisc/UndoFX)：UndoFX是JavaFX的通用撤消管理器。
* [FXRibbon](https://github.com/dukke/FXRibbon)：Java的Ribbon控件，使用JavaFX框架，基于Microsoft Ribbon。
* [DesktopPaneFX](https://github.com/kordamp/desktoppanefx)：DesktopPaneFX是Swing JDesktopPane的JavaFX版本，它可以用作类似于JInternalFrames的单个“子”容器。
* [KeyboardFX](https://github.com/dlsc-software-consulting-gmbh/KeyboardFX)：JavaFX应用程序的屏幕键盘。
* [FXOK](https://github.com/comtel2000/fx-experience)：FXOK为带有XML布局配置的触摸显示器提供基于JavaFX 8的虚拟屏幕键盘组件。
* [FroXty](https://github.com/iAmGio/froxty)：FroXty是一个JavaFX库，可以轻松复制著名的iOS半透明效果。
* [GestureFX](https://github.com/tom91136/GestureFX)：JavaFX的轻量级捏合缩放窗格。
* [FXFileChooser](https://github.com/Oliver-Loeffler/FXFileChooser)：自定义JavaFX文件选择器，允许快速手动过滤，允许添加路径谓词作为过滤器。
* [FXTaskbarProgressBar](https://github.com/Dansoftowner/FXTaskbarProgressBar)：JavaFX的一个库，使你能够在Windows任务栏上显示进度。
* [Grid](https://github.com/manuel-mauky/Grid)：Grid是一个JavaFX(8)组件，用于基于方格网格的不同类型的小游戏，例如国际象棋或数独。
* [RichTextArea](https://github.com/gluonhq/rich-text-area)：RichTextArea是一种文本输入控件，它提供富文本功能以及表情符号和非文本对象(如图像、表格和超链接)。
* [RichTextEditor](https://github.com/dankito/RichTextEditor)：适用于Android和JavaFX的所见即所得编辑器，具有丰富的支持格式选项。
* [FXUI](https://gitee.com/lichenfei_fei/chenfei-fxui)：JavaFX常见自定义组件。
* [AppleFX](https://github.com/HanSolo/applefx)：用JavaFX实现的Apple UI控件集合。
* [DevToolsFX](https://github.com/mkpaz/devtoolsfx)：DevToolsFX是一款用于浏览应用程序场景图和探索节点属性的工具。
* [NFX](https://github.com/xdsswar/nfx-lib)：NFX是适用于Windows 10/11的JavaFX/JNI库，可让你构建完全自定义、原生感觉的窗口Chrome-标题栏、按钮和框架行为。
* [JFXC](https://github.com/innFactory/JFXC)：JFXC包含一些新的控件，可以扩展你的GUI。
* [FX Progress Circle](https://github.com/torakiki/fx-progress-circle)：一些JavaFX进度指示器，以圆弧/圆环或填充圆的形式显示进度。
* [JavaFxDialog](https://github.com/4ntoine/JavaFxDialog)：JavaFX 2的标准对话框。
* [FranzXaver](https://github.com/afester/FranzXaver)：FranzXaver是一个JavaFX组件和工具库。
* [FXSVGImage](https://github.com/hervegirod/fxsvgimage)：此库允许将SVG文件转换为JavaFX节点树或图像。
* [JavaFXCalendar](https://github.com/poralcode/JavaFXCalendar)：JavaFX中的简单Material风格日历。
* [Techsenger TabPanePro](https://github.com/techsenger/tabpanepro)：Techsenger TabPanePro是一个轻量级的JavaFX库，它通过自定义控制区域、自定义选项卡形状、带边缘滚动的选项卡拖放、选项卡滚动条等实用功能扩展了标准TabPane。

#### JavaFX Dock库

* [AnchorFX](https://github.com/alexbodogit/AnchorFX)：AnchorFX是JavaFX的免费开源库，用于创建具有Dock功能的图形界面。
* [DockFX](https://github.com/RobertBColton/DockFX)：此库旨在填补JavaFX RIA平台中Dock框架的空白。
* [FxDock](https://github.com/andy-goryachev/FxDock)：创建此库是为了向JavaFX开发人员提供一个简单的Dock框架，该框架可在具有多个显示器的Mac、Windows和Linux上良好运行。
* [TiwulFX](https://github.com/panemu/tiwulfx-dock)：TiwulFX Dock提供增强的JavaFX TabPane，支持选项卡重新排序、分离和对接。
* [BentoFX](https://github.com/Col-E/BentoFX)：JavaFX的Dock系统。
* [Cedro Modern Dock](https://github.com/arthurdeka/cedro-modern-dock)：简洁流畅的开源Dock，通过自定义快捷方式，快速访问你常用的应用和系统模块。

#### JavaFX图表库

* [JFreeChart](https://github.com/jfree/jfreechart)：JFreeChart是一个适用于Java平台的综合免费图表库，可在客户端(JavaFX和Swing)或服务器端使用。
* [TilesFX](https://github.com/HanSolo/tilesfx)：包含可用于仪表板的图块的JavaFX库。
* [Medusa](https://github.com/HanSolo/medusa)：用于仪表的JavaFX库，该项目的主要重点是提供可以多种方式配置的仪表。
* [Charts](https://github.com/HanSolo/charts)：JavaFX中的科学图表库。
* [ChartFX](https://github.com/fair-acc/chart-fx)：ChartFX是GSI为FAIR开发的一个科学图表库，专注于以25Hz更新速率对数字信号处理应用中常见的具有数万到500万个数据点的数据集进行性能优化的实时数据可视化。
* [GMapsFX](https://github.com/dlsc-software-consulting-gmbh/GMapsFX)：纯JavaFX API，允许你将Google地图添加到JavaFX应用程序，而无需与底层Google地图JavaScript API交互。
* [JCSG](https://github.com/miho/JCSG)：基于BSP的CSG(构造实体几何)的Java实现。
* [ExtJFX](https://github.com/extjfx/extjfx)：ExtJFX是CERN开发的一个小型库，包含JavaFX应用程序所需的、标准JavaFX工具包不支持的功能。
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
* [Eclipse SWTChart](https://github.com/eclipse/swtchart)：SWTChart允许创建不同类型的图表。
* [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)：该项目提供了一个通用JavaFX图形可视化库，可以通过力导向算法实时自动排列顶点的位置。
* [JavaFX D3](https://github.com/stefaneidelloth/javafx-d3)：提供用于将JavaScript库d3.js与JavaFX应用程序使用的Java API。
* [Orson Charts](https://github.com/jfree/orson-charts)：Orson Charts是一个用于Java平台的3D图表库，可以生成各种3D图表，用于客户端应用程序(JavaFX和Swing)和服务器端应用程序(导出为PDF、SVG、PNG和JPEG)。
* [JavaFxDataviewer](https://github.com/jasrodis/javafx-dataviewer-wrapper)：JavaFxDataviewer是JavaFX的开源数据可视化工具。
* [StockChartsFX](https://github.com/FueledByChai/StockChartsFX)：用于创建K线图的JavaFX API。
* [PathGraph](https://github.com/vittorioPiotti/PathGraph-JavaFX)：PathGraph是一个库，其中包含以稳定和简单的方式创建和处理路径和行走图所需的所有工具。
* [FXGraph](https://github.com/sirolf2009/fxgraph)：FXGraph是JavaFX图形可视化工具。
* [FXDiagram](https://github.com/JanKoehnlein/FXDiagram)：FXDiagram是一个基于JavaFX创建图表工具的框架。
* [JFXUtils](https://github.com/gillius/jfxutils)：适用于JDK 8的缩放和平移图表和窗格缩放。
* [Timeline](https://github.com/dariol83/timeline)：该模块包含JavaFX的时间线/甘特图的实现。
* [JLeaflet](https://github.com/makbn/java_leaflet)：JLeaflet是一个用于将Leaflet地图集成到Vaadin和JavaFX应用中的Java库，支持完整的JPMS。

#### JavaFX图标库

* [Ikonli](https://github.com/kordamp/ikonli)：Ikonli提供可在Java应用程序中使用的图标包，目前支持Swing和JavaFX UI工具包。
* [FXTrayIcon](https://github.com/dustinkredmond/FXTrayIcon)：用于JavaFX应用程序的库，可以更轻松地添加系统托盘图标。
* [jIconFont-Swing](https://github.com/jIconFont/jiconfont-swing)：jIconFont-Swing是一个API，用于提供由任何IconFont生成的图标。
* [Icon Generator](https://github.com/sshtools/icon-generator)：一个简单的库，用于在Java中生成Java2D(Swing/AWT)、JavaFX和SWT图标。
* [FontAwesomeFX](https://bitbucket.org/Jerady/fontawesomefx)：Font Awesome是一款非常酷炫的图标字体，可以完美适配JavaFX应用。

#### JavaFX布局库

* [MiGLayout](https://github.com/mikaelgrev/miglayout)：MigLayout是一个功能极其丰富的JavaFX/SWT/Swing布局管理器，它使布局问题变得微不足道。
* [Flowless](https://github.com/FXMisc/Flowless)：JavaFX的高效VirtualFlow，VirtualFlow是一个布局容器，可在垂直或水平流中布局单元格。
* [FlexBoxFX](https://github.com/onexip/FlexBoxFX)：FlexBoxFX是CSS3弹性框布局管理器的JavaFX实现。
* [ScaledFX](https://github.com/miho/ScaledFX)：JavaFX窗格，用于通过应用缩放变换来缩放任意内容节点(用于Vworkflow)。

#### JavaFX动画库

* [AnimateFX](https://github.com/Typhon0/AnimateFX)：包含70多个即用型JavaFX动画的库。
* [Animated](https://github.com/iamgio/animated)：Animated引入了隐式动画，这是JavaFX中的一个全新概念，受到Flutter动画和运动小部件的强烈启发。
* [JFXAnimation](https://github.com/schlegel11/JFXAnimation)：JavaFX的CSS关键帧动画。
* [JMathAnim](https://github.com/davidgutierrezrubio/jmathanim)：JMathAnim是一个用Java编写的库，旨在简化数学动画的制作过程。
* [BlueBub](https://github.com/b3z/bluebub)：用于在JavaFX中创建聊天气泡的库。
* [LitFX](https://github.com/Birdasaur/LitFX)：LitFX可以将其效果作为透明覆盖层应用到你的JavaFX GUI，这样效果就可以与你的各种节点进行交互，而无需事先了解你的布局。
* [Tray Notification](https://github.com/PlusHaze/TrayNotification)：Tray Notification是JavaFX的一个库，为台式计算机添加了易于使用的托盘通知。

#### JavaFX渲染库

* [DriftFX](https://github.com/eclipse-efx/efxclipse-drift)：DriftFX允许你将任何OpenGL内容直接渲染到JavaFX节点中。
* [OpenGLFX](https://github.com/husker-dev/openglfx)：该库为JavaFX添加了新元素，用于使用LWJGL、JOGL、LWJGL2或LibGDX渲染OpenGL图形。
* [NativeFX](https://github.com/miho/NativeFX)：JavaFX的原生渲染集成。
* [JFXShader](https://github.com/Teragam/JFXShader)：允许在JavaFX中使用OpenGL(GLSL)或DirectX(HLSL)自定义效果着色器。

#### JavaFX项目模板

* [JavaFX Plus](https://gitee.com/Biubiuyuyu/JavaFX-Plus)：简化开发步骤和提高开发效率的JavaFX框架。
* [Spring Boot JavaFX Support](https://github.com/roskenet/springboot-javafx-support)：Spring Boot与JavaFX集成。
* [KickstartFX](https://github.com/xpipe-io/kickstartfx)：KickstartFX是适用于JavaFX应用程序的高级、即用型模板。
* [Drombler FX](https://github.com/Drombler/drombler-fx)：JavaFX的模块化应用程序框架。
* [JavaFX Boot](https://gitee.com/westinyang/javafx-boot)：JavaFX、Spring Boot快速开始脚手架。

#### 键盘鼠标监听器

* [JNativeHook](https://github.com/kwhat/jnativehook)：JNativeHook是一个为Java提供全局键盘和鼠标监听器的库。
* [System Hook](https://github.com/kristian/system-hook)：Java System Hook为Java提供了一个非常轻量级的全局键盘和鼠标监听器。
* [MouseMaster](https://github.com/petoncle/mousemaster)：MouseMaster允许你仅使用键盘控制鼠标光标。
* [JIntellitype](https://github.com/melloware/jintellitype)：JIntellitype是一个Java API，用于与Microsoft Intellitype命令交互以及在Java应用程序中注册全局热键。
* [JKeyMaster](https://github.com/tulskiy/jkeymaster)：用于使用JNA在Java中注册全局热键的库，目标是支持基于X11的平台、Windows和MacOSX。
* [KeyboardMouse.kt](https://github.com/Animeshz/keyboard-mouse-kt)：KeyboardMouse.kt是一个轻量级、基于协程的多平台Kotlin库，用于通过Kotlin、Java和NodeJS与键盘和鼠标进行惯用交互(接收和发送全局事件)。
* [SimpleNativeHooks](https://github.com/repeats/SimpleNativeHooks)：用于全局键盘和鼠标监听器的Java库。

#### 浏览器

* [WebBrowser](https://github.com/goxr3plus/JavaFX-Web-Browser)：使用Java和JavaFX制作的Web浏览器。
* [Wolvic XR Browser](https://github.com/Igalia/wolvic)：Wolvic是一个开源浏览器，包括XR构建的沉浸式游戏、视频和环境。
* [JCEF](https://github.com/chromiumembedded/java-cef)：JCEF是一个简单的框架，用于使用Java编程语言将基于Chromium的浏览器嵌入到其他应用程序中。
* [Pandomium](https://github.com/dzikoysk/pandomium)：Pandomium是专为Maven项目设计的JCEF实现。
* [GNGR](https://github.com/gngrOrg/gngr)：这是一款支持隐私的新型跨平台浏览器，GNGR是纯Java的Web标准的独立实现。
* [JxBrowser](https://teamdev.com/jxbrowser/)：将Chromium Web浏览器添加到你的Java应用程序中。
* [Chromium](https://github.com/equodev/chromium)：Equo Chromium Community小部件是一个跨平台浏览器，允许用户在Java应用程序内创建和呈现基于Web的现代UI。
* [Gophie](https://github.com/jankammerath/gophie)：Gophie是“The Internet Gopher”的现代图形跨平台客户端或浏览器。
* [Lobo Evolution](https://github.com/LoboEvolution/LoboEvolution)：Lobo Evolution是一个可扩展的全Java Web浏览器和RIA平台。
* [Easy Browser](https://gitee.com/fhs-opensource/easy-browser)：Java开源浏览器，基于JxBrowser实现，已经包含了绝大多数的浏览器基础功能。
* [Webicity](https://github.com/WebicityBrowser/Webicity)：Webicity是一个简单的Web浏览器。
* [JFX Browser](https://github.com/badarshahzad/Jfx-Browser)：JFX Browser是一个多选项卡浏览器。
* [Webview Java](https://github.com/webview/webview_java)：Webview项目的Java移植，它使用JNA并自动提取当前系统所需的dll/dylib/so库。
* [Journey](https://github.com/BFergerson/Journey)：Journey是一款由JCEF提供支持的跨平台Web浏览器，旨在满足对开源JxBrowser替代品的需求。

#### JavaFX程序

* [JabRef](https://github.com/JabRef/jabref)：JabRef是一个开源、跨平台的引文和引用管理工具。
* [AsciidocFX](https://github.com/asciidocfx/AsciidocFX)：AsciidocFX是一款书籍/文档编辑工具，用户可以创建PDF、Epub、Mobi和HTML等形式的书籍/文档。
* [PDF4Teachers](https://github.com/ClementGre/PDF4Teachers)：PDF4Teachers专为教师设计，它允许你以出色的工作效率对PDF返回的评估进行注释。
* [NS USBloader](https://github.com/developersu/ns-usbloader)：NS USBloader是适用于Huntereb/Awoo-Installer或其他兼容安装程序以及XorTroll/Goldleaf(USB) NSP安装程序的PC端安装程序。
* [FoFa Viewer](https://github.com/wgpsec/fofa_viewer)：FoFa Viewer是一个用JavaFX编写的用户友好的FOFA客户端，由狼组安全团队开源。
* [Markdown Writer FX](https://github.com/JFormDesigner/markdown-writer-fx)：用JavaFX编写的开源Markdown编辑器。
* [ToolsFx](https://github.com/Leon406/ToolsFx)：基于Kotlin、TornadoFX的跨平台密码学工具箱。
* [xJavaFxTool](https://gitee.com/xwintop/xJavaFxTool)：xJavaFxTool是使用JavaFX开发的实用小工具集。
* [Phoenicis](https://github.com/PhoenicisOrg/phoenicis)：Phoenicis PlayOnLinux是一款软件，可让你轻松安装和使用大量专为Windows运行的游戏和应用程序。
* [XR3Player](https://github.com/goxr3plus/XR3Player)：XR3Player是一个先进的JavaFX媒体播放器。
* [FreeBox](https://github.com/kknifer7/FreeBox)：FreeBox是一款集成了影视播放和资源审计功能的桌面端软件。
* [DrawingBotV3](https://github.com/SonarSonic/DrawingBotV3)：DrawingBotV3是一款用于将图像转换为风格化绘图的软件。
* [JDKMon](https://github.com/HanSolo/JDKMon)：JDKMon是一个用JavaFX编写的小工具，它会尝试检测你计算机上安装的所有JDK，并通知你发现的每个OpenJDK发行版的新更新和漏洞。
* [VocabHunter](https://github.com/VocabHunter/VocabHunter)：VocabHunter是一个帮助外语学习者的系统。
* [Quelea](https://github.com/quelea-projection/Quelea)：Quelea是适用于教堂的开源投影软件。
* [TRex Stateless GUI](https://github.com/cisco-system-traffic-generator/trex-stateless-gui)：TRex Stateless GUI应用程序为TRex提供图形用户界面，由Cisco开发。
* [FakeImageDetection](https://github.com/afsalashyana/FakeImageDetection)：FakeImageDetection的目标是识别假图像(经过数字更改的图像)。
* [Object Graph Visualizer](https://github.com/Nurtak/ObjectGraphVisualization)：Object Graph Visualizer是一个主要用于计算机科学课程的工具，旨在帮助新学生理解面向对象的范式和模式。
* [Flow](https://github.com/eclab/flow)：Flow是一款完全模块化的多音色和复调加法软件合成器，由乔治梅森大学开源。
* [Scenic View](https://github.com/JonathanGiles/scenic-view)：Scenic View是一个JavaFX应用程序，旨在让你轻松了解应用程序场景图的当前状态，并且还可以轻松操作场景图的属性，而无需继续编辑代码。
* [Usagi](https://github.com/OHDSI/Usagi)：Usagi是一个帮助创建编码系统和词汇标准概念之间映射的应用程序，由OHDSI开源。
* [Trinity](https://github.com/Birdasaur/Trinity)：Trinity提供性能分析和XAI工具，非常适合深度学习系统或执行复杂分类或解码的其他模型。
* [Officer Breaker](https://github.com/nedlir/OfficerBreaker)：Officer Breaker是一个简单的程序，它可以从属于Office Open XML格式系列(.pptx/.xlsx/.docx文件类型)的只读保护文件中删除密码。
* [RoomIt](https://gitee.com/rococy/RoomIt)：RoomIt是一款基于JavaFX、操作简便、轻量的屏幕画笔工具。
* [Dev Tools](https://github.com/reugn/dev-tools)：单个桌面应用程序中的开发人员实用程序的集合。
* [RubberTranslator](https://github.com/RubberTranslator/RubberTranslator)：RubberTranslator是基于JavaFX开发的一款文献辅助翻译软件。
* [LectureStudio](https://github.com/lectureStudio/lectureStudio)：LectureStudio是一款开源免费的电子教学软件，支持Windows、Mac OS和Linux，由萨尔兰大学开源。

#### GUI程序

* [LanguageTool](https://github.com/languagetool-org/languagetool)：LanguageTool是一款开源校对软件，适用于英语、西班牙语、法语、德语、葡萄牙语、波兰语、荷兰语和其他20多种语言，它可以发现许多简单的拼写检查器无法检测到的错误。
* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [JISA](https://github.com/OE-FET/JISA)：JISA是一个用Java编写的库，旨在用作为常见实验室仪器创建实验控制系统的方法，由剑桥大学开源。
* [MIST](https://github.com/usnistgov/MIST)：MIST是美国国家标准与技术研究所开发的显微图像拼接应用程序。
* [Piped](https://github.com/TeamPiped/Piped)：Piped是另一种隐私友好的YouTube前端，设计高效。
* [Sonarqube](https://github.com/SonarSource/sonarqube)：SonarQube是一个开源的代码质量管理系统。
* [TempestSDR](https://github.com/martinmarinov/TempestSDR)：该项目是一个软件工具包，用于使用软件定义无线电(SDR)接收器远程窃听视频监视器。
* [yEd](https://www.yworks.com/products/yed)：yEd是一款功能强大的桌面应用程序，可用于快速有效地生成高质量图表，由yWorks开发。
* [Uppaal](https://uppaal.org/)：Uppaal是一个集成工具环境，用于对实时系统进行建模、验证和确认，由乌普萨拉大学和奥尔堡大学开源。
* [MooTool](https://github.com/rememberber/MooTool)：开发者常备小工具。
* [SDRTrunk](https://github.com/DSheirer/sdrtrunk)：SDRTrunk是一个跨平台Java应用程序，用于使用软件定义无线电(SDR)解码、监控、记录和流式传输集群移动和相关无线电协议。
* [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)：ST公司推出的一种自动创建单片机工程及初始化代码的工具。
* [BIMserver](https://github.com/opensourceBIM/BIMserver)：BIMserver使你能够存储和管理建筑(或其他建筑相关)项目的信息，由荷兰国家应用科学院和埃因霍芬理工大学开发。
* [ImageJ](https://imagej.net/ij/index.html)：ImageJ是一个基于Java的公共图像处理软件，由美国国立卫生研究院开发。
* [Repeat](https://github.com/repeats/Repeat)：跨平台鼠标/键盘记录/重播和自动化热键/宏创建，以及更高级的自动化功能。
* [EtherPad](https://github.com/ether/pad)：Etherpad Lite是一种更简单、更快、更轻的协作编辑解决方案。
* [OpenAPC](http://www.openapc.com/)：OpenAPC是一种开源APC(高级过程控制)解决方案，它具有高度灵活性和可配置性，涵盖了从家庭控制到工业自动化的各种自动化、可视化和过程控制任务。
* [Wordfast](https://www.wordfast.com/)：Wordfast是一款翻译记忆软件，它为自由译者、语言服务供应者与跨国公司提供了翻译记忆独立平台的解决方案。
* [Vivado](https://www.xilinx.com/products/design-tools/vivado.html)：Vivado是赛灵思开发的用于HDL设计的合成和分析的软件套件，具有用于片上系统开发和高级综合的附加功能。
* [Citespace](https://citespace.podia.com/)：CiteSpace是一个免费的Java应用程序，用于可视化和分析科学文献中的趋势和模式，由德雷塞尔大学开源。
* [Docear](https://github.com/BeelGroup/Docear-Desktop)：Docear是一款独特的学术文献管理解决方案，由锡根大学开源。
* [OpenPnP](https://github.com/openpnp/openpnp)：OpenPnP是一种开源SMT拾放系统，包括可立即运行的软件以及可以构建和修改的硬件设计。
* [RapidWright](https://github.com/Xilinx/RapidWright)：RapidWright是AMD的一个开源项目，它通过DCP文件为Vivado提供了一个新的桥梁。
* [JMRI](https://github.com/JMRI/JMRI)：JMRI是一个模型铁路数字指挥与控制软件。
* [IPED](https://github.com/sepinf-inc/IPED)：IPED是一款开源软件，可用于处理和分析数字证据，由巴西联邦警察局的数字取证专家开发。
* [NodeBox](https://github.com/nodebox/nodebox)：NodeBox系列工具让你能够按照自己想要的方式创建生成设计，由布鲁塞尔圣卢卡斯大学学院开发。
* [FigTree](https://github.com/rambaut/figtree)：FigTree被设计为系统发育树的图形查看器和用于生成可发表图表的程序。
* [PEmbroider](https://github.com/CreativeInquiry/PEmbroider)：PEmbroider是一个使用Processing进行计算刺绣的开源库，由CMU开源。
* [jExifToolGUI](https://github.com/hvdwolf/jExifToolGUI)：jExifToolGUI是一个多平台Java/Swing图形前端，由Phil Harvey开发，用于优秀的命令行ExifTool应用程序。
* [WePush](https://github.com/rememberber/WePush)：专注批量推送的小而美的工具，目前支持：模板消息-公众号、模板消息-小程序、微信客服消息等。
* [BlobSaver](https://github.com/airsquared/blobsaver)：用于自动保存SHSH blob的跨平台GUI和CLI应用程序。
* [Gephi](https://github.com/gephi/gephi)：Gephi是适用于各种图形和网络的领先可视化和探索软件。
* [Holer](https://github.com/wisdom-projects/holer)：Holer是一个将局域网中的应用映射到公网访问的端口映射软件，支持转发基于TCP协议的报文。
* [MooInfo](https://github.com/rememberber/MooInfo)：OSHI的可视化实现，用于查看有关系统和硬件的信息。
* [Freenet](https://github.com/hyphanet/fred)：Freenet是一个抗审查通信和发布平台，它是一种点对点软件，提供分布式、加密、去中心化的数据存储，起源于爱丁堡大学。
* [RuneLite](https://github.com/runelite/runelite)：RuneLite是一个免费、开源的OldSchool RuneScape客户端。
* [Chatty](https://github.com/chatty/chatty)：Chatty是一款用Java编写的Twitch桌面聊天客户端，具有许多Twitch特定功能。
* [Moneydance](https://infinitekind.com/moneydance)：Moneydance是一款易于使用且功能齐全的个人理财应用程序。
* [Bits N Picas](https://github.com/kreativekorp/bitsnpicas)：Bits N Picas是一组用于创建和转换位图和表情符号字体的工具。
* [Bad Peggy](https://www.malavida.com/en/soft/bad-peggy/)：Bad Peggy会分析你的文件夹以查找损坏的JPEG图像。
* [JDemetra+](https://github.com/jdemetra/jdemetra-app)：JDemetra+是比利时国家银行(NBB)与德意志联邦银行和欧盟统计局根据欧洲统计系统(ESS)指南合作开发的季节性调整(SA)新工具。
* [Archi](https://github.com/archimatetool/archi)：Archi是一款免费、开源、跨平台的工具和编辑器，用于创建ArchiMate模型。
* [JLearnIt](https://www.jlearnit.com/)：JLearnIt是一款免费的多语言词典，按类别分类，帮助你循序渐进地学习其他语言的词汇。
* [DocFetcher](https://github.com/docfetcher/DocFetcher)：DocFetcher是一个开源桌面搜索应用程序，它允许你搜索计算机上的文件内容。
* [PIPE](https://github.com/sarahtattersall/PIPE)：平台独立的Petri网编辑器。
* [MuCommander](https://github.com/mucommander/mucommander)：MuCommander是一款轻量级、跨平台的文件管理器，具有双窗格界面。
* [Open Visual Traceroute](https://github.com/leolewis/openvisualtraceroute)：Open Visual Traceroute是一款提供视觉化的路由追踪工具。
* [Plot Digitizer](https://plotdigitizer.sourceforge.net/)：Plot Digitizer是一个Java程序，用于对功能数据的扫描图进行数字化。
* [KSar](https://github.com/vlsi/ksar)：KSar是一个sar图形工具，可以绘制Linux、Mac和Solaris sar输出的图形。
* [Pixelitor](https://github.com/lbalazscs/Pixelitor)：Pixelitor是一个高级Java图像编辑器，具有图层、图层蒙版、文本图层、110多个图像滤镜和颜色调整、多重撤消等。
* [BT747](https://www.bt747.org/)：BT747是一款基于MTK芯片组控制GPS数据记录器的应用程序。
* [B4J](https://github.com/AnywhereSoftware/B4J)：B4J是一款100%免费的桌面、服务器和物联网解决方案开发工具，由Anywhere软件公司开发。
* [TreeForm](https://github.com/frekky/TreeForm)：TreeForm语法树绘图软件是一个语言语法/语义树绘图编辑器。
* [FullSync](https://github.com/fullsync/fullsync)：FullSync是一个功能强大的工具，可帮助你保持各种数据的多个副本同步。
* [Spectrum Analyzer](https://github.com/pavsa/hackrf-spectrum-analyzer)：适用于Windows/Linux的hackrf_sweep频谱分析仪GUI。
* [Janelia Workstation](https://github.com/JaneliaSciComp/workstation)：Janelia Workstation是一个神经科学发现平台，用于处理、分析、注释和共享大规模3D显微镜数据，由霍华德休斯医学研究所开源。
* [Whole Platform](https://github.com/wholeplatform/whole)：Whole Platform是一种用于工程软件生产的开源技术。
* [MyTourbook](https://github.com/mytourbook/mytourbook)：MyTourbook是一款免费软件，用于可视化和分析由GPS设备、自行车或运动电脑和测力计记录的行程。
* [Virtual Satellite](https://github.com/virtualsatellite/VirtualSatellite4-Core)：Virtual Satellite是一款DLR开源软件，用于基于模型的系统工程MBSE。
* [Sweet Home 3D](http://www.sweethome3d.com/)：Sweet Home 3D是一款免费的室内设计应用程序，它可以帮助你绘制房屋平面图、在其上布置家具并以3D形式查看结果。
* [Autopsy](https://github.com/sleuthkit/autopsy)：Autopsy是Sleuth Kit和其他开源数字取证工具的图形界面。
* [Rachota](https://rachota.sourceforge.net/en/index.html)：Rachota是一款用于跟踪不同项目时间的便携式应用程序。
* [MSPaintIDE](https://github.com/MSPaintIDE/MSPaintIDE)：这个应用程序给MS Paint带来了提升，可以让MS Paint突出显示、编译和执行代码。
* [JDiskReport](https://www.jgoodies.com/freeware/jdiskreport/)：JDiskReport使你能够了解文件和目录在磁盘驱动器上占用了多少空间，并帮助你找到过时的文件和文件夹。
* [Freerouting](https://github.com/freerouting/freerouting)：Freerouting是一款先进的自动布线器，适用于所有支持标准Specctra或Electra DSN接口的PCB程序。
* [Paintera](https://github.com/saalfeldlab/paintera)：Paintera是一种通用可视化工具，用于3D体积数据和分割/重建中的校对，主要关注连接组学中电子显微照片的神经元重建，由Saalfeld实验室开源。
* [ELamX2](https://github.com/AndiMb/eLamX2)：ELamX²是一款用Java编写的开源复合计算器，由德累斯顿工业大学航空航天工程学院飞机工程系主任开发。
* [Autoplot](https://autoplot.org/)：Autoplot是一款用于网络数据的交互式浏览器，由NASA等组织开发。
* [Underscore Backup](https://underscorebackup.com/)：Underscore Backup是一款数据备份和恢复解决方案，主要用于Windows和Mac操作系统，提供了一种安全、高效的方式来备份用户的数据。
* [Art of Illusion](https://github.com/ArtOfIllusion/ArtOfIllusion)：Art of Illusion是一个免费、开源的3D建模和渲染软件。
* [RomRaider](https://github.com/RomRaider/RomRaider)：RomRaider是一款免费的开源调校套件，用于查看、记录和调校现代斯巴鲁发动机控制单元。
* [IrScrutinizer](https://github.com/bengtmartensson/IrScrutinizer)：IrScrutinizer是一个功能强大的程序，用于捕获、生成、分析、导入和导出红外(IR)信号。
* [LPAdesktop](https://github.com/Truphone/LPAdesktop)：LPA模拟器是一款用于管理可移动eUICC上的eSIM配置文件的应用程序。
* [Tomighty](https://github.com/tomighty/tomighty)：Tomighty是一款专为番茄工作法设计的桌面计时器。

#### IDE

* [IntelliJ IDEA](https://github.com/JetBrains/intellij-community)：IntelliJ IDEA是领先的Java和Kotlin IDE，由JetBrains开发。
* [Eclipse](https://github.com/eclipse-platform)：Eclipse是一个开源、基于Java的可扩展开发平台，由IBM开发。
* [Visual Studio Code](https://code.visualstudio.com)：Visual Studio Code是Microsoft开源的一个轻量级但功能强大的源代码编辑器，也支持作为IDE开发Java。
* [Android Studio](https://developer.android.com/studio)：Android Studio是用于开发Android应用的Google官方IDE，基于Intellij引擎。
* [Apache NetBeans](https://github.com/apache/netbeans)：NetBeans是一个开源开发环境、工具平台和应用程序框架，最初由Oracle开发。
* [JetBrains Fleet](https://www.jetbrains.com/fleet)：Fleet是JetBrains公司推出的一款下一代集成开发环境，使用Kotlin开发。
* [MyEclipse](https://www.genuitec.com/products/myeclipse)：MyEclipse是一个基于Eclipse平台构建的专有Java IDE，由Genuitec软件公司提供。
* [Spring Tools](https://github.com/spring-projects/spring-tools)：Spring官方出品的基于Eclipse的Java IDE。
* [Light Table](https://github.com/LightTable/LightTable)：Light Table是一款新一代代码编辑器，它能通过即时反馈将你与你的创作紧密联系起来。
* [JDeveloper](https://www.oracle.com/application-development/technologies/jdeveloper.html)：Oracle JDeveloper是一个免费的集成开发环境，可简化基于Java的应用程序的开发。
* [DevEco Studio](https://developer.huawei.com/consumer/cn/deveco-studio/)：DevEco Studio基于IntelliJ IDEA开源版本打造，为运行在HarmonyOS系统上的应用和元服务提供一站式的开发平台，由华为开发。
* [JBoss Developer Studio](https://devstudio.jboss.com/updates/)：JBoss Developer Studio是由RedHat和Exadel创建并开发的IDE。
* [HBuilder](https://www.dcloud.io/)：HBuilder是DCloud推出的一款支持HTML 5的Web开发IDE，本身由Java编写。
* [BlueJ](https://github.com/k-pet-group/BlueJ-Greenfoot)：BlueJ是Java编程语言的IDE，主要用于教育目的，但也适合小规模软件开发，最初由莫纳什大学开源，目前由伦敦国王学院维护。
* [GigaIDE](https://gitverse.ru/features/gigaide/)：GigaIDE是由俄罗斯公司研发的免费Spring IDE，旨在为开发者提供高效的Spring应用开发体验。
* [CoreIDE](https://www.coreide.com/)：适用于Java、JavaScript、Node.js和TypeScript开发人员的IDE。
* [JBuilder](https://borland-jbuilder.software.informer.com/)：JBuilder是Borland公司出品的Java集成编程环境，有不同功能程度的多个版本。
* [Consulo](https://github.com/consulo/consulo)：Consulo是一个多语言IDE，基于Intellij引擎。
* [Codenvy](https://github.com/codenvy/codenvy)：Codenvy是一个基于云的IDE，支持Java和许多其他语言，由RedHat维护。
* [RapidClipse](https://rapidclipse.com/)：RapidClipse是一个免费的Eclipse发行版，用于使用Java进行快速跨平台开发，由XDEV软件公司提供。
* [Greenfoot](https://www.greenfoot.org/home)：Greenfoot是使用Java或Stride的集成开发环境，主要用于高中和本科生的教育目的，由坎特伯雷肯特大学开源。
* [DrJava](http://www.drjava.org/)：DrJava是一款轻量级的Java编程语言IDE，主要面向初学者设计，由莱斯大学开源。
* [AIDE](https://www.android-ide.com/)：AIDE是一个Android/Java IDE，可以在Android手机上进行Android软件和游戏的开发，由Appfour提供。
* [TIDE](https://sourceforge.net/projects/tide)：TIDE是一个小巧但功能强大且齐全的开源Java IDE。
* [FDT](https://fdt.powerflasher.com/)：FDT是一个基于Eclipse的IDE，适用于交互式开发人员、自由职业者和机构，由Powerflasher开发。
* [Lightly](https://www.lightlycode.com/)：轻量且功能强大的集成开发工具。
* [Brokk](https://github.com/BrokkAi/brokk)：Brokk是一个能够从语义上理解代码而非仅仅将其理解为文本块的代码助手。
* [FeatureIDE](https://github.com/FeatureIDE/FeatureIDE)：FeatureIDE是一个基于Eclipse的IDE，支持面向特性的软件开发的所有阶段，主要由德国马格德堡大学、帕绍大学开发。
* [Nightcode](https://github.com/oakes/Nightcode)：Nightcode是一款适用于Clojure和ClojureScript的简洁IDE。
* [Flash Builder](https://en.wikipedia.org/wiki/Adobe_Flash_Builder)：Adobe Flash Builder是基于Eclipse平台构建的IDE，可加速富互联网应用程序和跨平台桌面应用程序的开发。
* [RStudio](https://github.com/rstudio/rstudio)：RStudio是R编程语言的集成开发环境，由Posit软件公司开源。
* [Aptana Studio 3](https://github.com/aptana/studio3)：Aptana Studio 3是一个Web开发IDE，由Axway开源。
* [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE)：AndroidIDE是一款适用于Android开发的IDE。
* [CodeAssist](https://github.com/tyron12233/CodeAssist)：用于在Android上构建Android应用程序的实验性IDE。
* [Cosmic IDE](https://github.com/Cosmic-Ide/Cosmic-IDE)：Cosmic是一款功能强大、丰富的IDE，适用于Android上的JVM开发。
* [JCreator](https://jcreator.en.softonic.com/)：JCreator是一款专有软件的Java编辑器，由Xinox公司制作。
* [JGRASP](https://www.jgrasp.org/)：JGRASP是一个轻量级开发环境，专门用于提供软件可视化的自动生成，以提高软件的可理解性，由奥本大学开源。
* [Halcyon IDE](https://github.com/s4n7h0/Halcyon-IDE)：Halcyon IDE是第一个专为Nmap Script开发人员开发的IDE。
* [Portugol Studio](https://github.com/UNIVALI-LITE/Portugol-Studio)：Portugol Studio是一个学习编程的环境，针对讲葡萄牙语的编程初学者，由UNVALI教育技术创新实验室开发。
* [DevelNext](https://github.com/jphp-group/develnext)：DevelNext是一个专注于快速创建程序、简单的2D游戏以及适用于Windows/Linux/Mac的功能原型的开发环境。

#### 可视化编程

* [Processing](https://github.com/processing/processing)：Processing是一个开源的编程语言和开发环境，设计用于视觉艺术、创意编程和电子艺术领域的教学和创作，由麻省理工学院开源。
* [FlowForge](https://github.com/gufranthakur/FlowForge)：FlowForge是一款用Java编写的简单可视化编程工具，其设计灵感来源于虚幻引擎5的蓝图系统。
* [Viskell](https://github.com/viskell/viskell)：Viskell是一个实验性的可视化编程环境，适用于类型化(类似Haskell)函数式编程语言，由特文特大学开源。
* [PraxisLive](https://github.com/praxis-live/praxis-live)：PraxisLive是一种混合视觉实时编程Java IDE。

#### 文本编辑器

* [JEdit](https://www.jedit.org/)：JEdit是一个用Java语言开发的文本编辑器。
* [JEditor](https://jeditor.sourceforge.io/)：jEditor是一款具有语法高亮功能的简单Java文本编辑器，旨在作为其他应用程序的库使用。
* [Jext](https://github.com/romainguy/jext)：Jext是适用于Windows、Linux和macOS的源代码编辑器。
* [λiquid](https://github.com/mogenslund/liquid)：Clojure文本编辑器，用于编辑Clojure代码和Markdown代码。
* [Clopad](https://github.com/fredoverflow/clopad)：Clopad是一款极简的Clojure代码编辑器。
* [JNotepad](https://gitee.com/jcnc-org/JNotepad)：JNotepad是一款简约而强大的跨平台文本编辑器，旨在提供用户友好的界面和丰富的功能以及插件化使用。
* [NeoeEdit](https://github.com/neoedmund/neoeedit)：NeoeEdit是一款智能、轻量且强大的文本编辑器。
* [Pure Writer](https://github.com/PureWriter/desktop)：Pure Writer是一个开源编辑器。
* [PH NotePad](https://github.com/pH-7/Simple-Java-Text-Editor)：PH NotePad是一款简单且轻便的文本编辑器，用Java编写。
* [Arachnophilia](https://arachnoid.com/arachnophilia/)：Arachnophilia是Paul Lutus用Java编写的源代码编辑器。
* [RText](https://github.com/bobbylight/RText)：RText是一个用Java编写的程序员文本编辑器。
* [Klonk](https://github.com/zaboople/klonk)：Klonk是一款简单但功能强大的文本编辑器，旨在提供流畅易用性和便捷性，而不是奇特的功能。
* [JMarkPad](https://github.com/mayuso/JMarkPad)：JMarkPad是一个简约的文本编辑器，可以实时预览你的Markdown文本。
* [KeenWrite](https://gitlab.com/DaveJarvis/KeenWrite)：KeenWrite是一个免费的、开源的、跨平台的桌面Markdown编辑器，可以生成排版精美的PDF。
* [JTaccuino](https://github.com/jtaccuino/jtaccuino)：JTaccuino是一款基于JavaFX的笔记本应用程序，面向Java开发人员。
* [BinEd](https://github.com/exbin/bined)：用Java编写的二进制数据编辑器。

#### 在线编辑器

* [Coding WebIDE](https://github.com/coding/WebIDE)：Coding WebIDE是由腾讯Coding团队开发的云端IDE。
* [CodeCafé](https://github.com/mrktsm/codecafe)：CodeCafé为你提供浏览器中高度协作的实时开发环境。
* [Online Java](https://www.online-java.com)：Online Java是一个基于Web的工具，它是快速、健壮、强大的Java语言在线编译器之一。
* [JDoodle](https://www.jdoodle.com/)：JDoodle是一款在线Java编译器IDE，它能够让你在浏览器中编写、运行和调试Java代码，无需在本地安装任何开发环境。
* [SnapCode](https://github.com/reportmill/SnapCode)：SnapCode使你可以在任何现代浏览器中快速轻松地开始编写Java代码。
* [Compilejava](https://www.compilejava.net/)：Compilejava是运行Java代码的简单在线工具。

#### 数学软件

* [MATLAB](https://www.mathworks.com/products/matlab.html)：MATLAB是一种用于算法开发、数据可视化、数据分析以及数值计算的高级技术计算语言和交互式环境，其GUI部分由Java开发，这是MathWorks公司的商业软件。
* [Maple](https://www.maplesoft.com/products/Maple/)：Maple是一个符号计算和数值计算软件平台。
* [Mathematica](https://www.wolfram.com/mathematica/)：Mathematica是一款科学计算软件，有时候也被称为计算机代数系统，广泛使用于科学、工程、数学、计算等领域。
* [GeoGebra](https://github.com/geogebra/geogebra)：GeoGebra是一款动态数学软件，于2001年由Markus Hohenwarter在奥地利萨尔茨堡大学制作。
* [Scilab](https://gitlab.com/scilab/scilab)：Scilab是用于数值计算的免费开源软件，为工程和科学应用提供强大的计算环境，由法国国立计算机及自动化研究院和法国国立桥梁学院开源。
* [MagicPlot](https://www.magicplot.com/)：MagicPlot是一款技术绘图、曲线拟合和数据分析应用程序，这是一个商业软件。
* [SmartPLS](https://www.smartpls.com/)：SmartPLS是用于使用偏最小二乘(PLS)路径建模方法进行基于方差的结构方程建模(SEM)的软件。
* [CaR](http://car.rene-grothmann.de/doc_en/index.html)：CaR是动态几何程序，它模拟计算机上的指南针和尺子结构，由艾希施泰特天主教大学开源。
* [JGEX](https://github.com/kovzol/Java-Geometry-Expert)：JGEX是一款结合了动态几何软件(DGS)、自动几何定理证明器(GTP)和视觉动态证明呈现方法的软件，由奥地利林茨教区私立大学教育学院开源。
* [CARMetal](https://carmetal.en.uptodown.com/windows)：CARMetal是动态几何程序C.a.R.的改编版本。
* [Hodoku](https://github.com/PseudoFish/Hodoku)：HoDoKu是一个用Java编写的数独助手，有英语和德语版本。
* [Gaalop](https://github.com/CallForSanity/Gaalop)：Gaalop是一款将几何代数(GA)表达式编译并优化为高级编程语言代码的软件。
* [JPlotter](https://jplotter.sourceforge.io/)：JPlotter是一个开源数学绘图仪，可以绘制任意数学函数的图形。

#### 仿真软件

* [NetLogo](https://github.com/NetLogo/NetLogo)：NetLogo是一个多智能体可编程建模环境，由西北大学开源。
* [VirusBroadcast](https://github.com/KikiLetGo/VirusBroadcast)：VirusBroadcast是一个用Java编写的疫情传播仿真程序。
* [OpenRocket](https://github.com/openrocket/openrocket)：OpenRocket是一款免费、功能齐全的模型火箭模拟器，可让你在实际建造和飞行火箭之前设计和模拟火箭。
* [Particle Life App](https://github.com/tom-mohr/particle-life-app)：用于显示逼真行为的粒子系统模拟器。
* [JaamSim](https://github.com/jaamsim/jaamsim)：JaamSim是自2002年开发的基于Java的离散事件仿真环境，由Ausenco开源。
* [OpenSim](https://github.com/opensim-org/opensim-gui)：OpenSim是一款软件，可让用户开发肌肉骨骼结构模型并创建运动动态模拟，由斯坦福开源。
* [GAMA](https://github.com/gama-platform/gama.old)：GAMA是一个易于使用的开源建模和仿真环境，用于创建基于代理的空间显式仿真，由法国发展研究院和巴黎第六大学开源。
* [COMSOL](https://www.comsol.com/comsol-multiphysics)：COMSOL是一套跨平台的有限元素分析、求解器和多物理场模拟软件。
* [AnyLogic](https://www.anylogic.com/)：AnyLogic是一套结合多种模拟(仿真)理论的建模开发工具。
* [Warteschlangensimulator](https://github.com/A-Herzog/Warteschlangensimulator)：Warteschlangensimulator是一个免费、独立于平台、离散事件的随机模拟器，它允许以流程图的形式对排队系统进行建模。
* [Mars SIM](https://github.com/mars-sim/mars-sim)：Mars SIM被设计为一个通用模拟器，描绘火星上人类住区的早期发展。
* [Simbrain](https://github.com/simbrain/simbrain)：Simbrain是一款用于构建、运行和分析神经网络(大脑回路的计算机模拟)的免费工具。
* [Starfish](https://github.com/particleincell/Starfish)：Starfish是一款二维(笛卡尔或轴对称)程序，用于模拟各种等离子体和气体问题。
* [ArtiSynth](https://github.com/artisynth/artisynth_core)：ArtiSynth是一个3D机械建模系统，支持多体和有限元(FEM)模型以及接触和约束的组合模拟，由不列颠哥伦比亚大学开源。
* [Alchemist](https://github.com/AlchemistSimulator/Alchemist)：Alchemist是一个用于普适性、聚合性和受自然启发的计算的模拟器。
* [Java Modelling Tools](https://jmt.sourceforge.net/)：JMT是由米兰理工大学和伦敦帝国理工学院开发的一套应用程序，旨在为性能评估、使用分析和模拟技术的系统建模、容量规划和工作负载特征研究提供全面的框架。

#### UML工具

* [StarUML](https://staruml.io/)：StarUML是一个开源的UML工具列表软件，由韩国MKLabs公司开源。
* [ArgoUML](https://github.com/argouml-tigris-org/argouml)：ArgoUML是领先的开源UML建模工具，支持所有标准UML 1.4图。
* [PlantUML](https://github.com/plantuml/plantuml)：PlantUML是一个允许你通过简单的文本描述创建各种UML图的组件。
* [IBM Rational Rose](https://www.ibm.com/docs/en/rational-soft-arch/9.7.0?topic=migration-rational-rose-model)：Rational Rose是统一建模语言的开发环境，这是IBM的商业产品。
* [Visual Paradigm](https://www.visual-paradigm.com/cn/)：Visual Paradigm是一款功能强大的UML工具，适用于不同层次的用户，从初学者到专家。
* [Astah](https://astah.net/)：Astah是由日本公司Change Vision创建的UML建模工具。
* [Eclipse Papyrus](https://eclipse.dev/papyrus/)：Papyrus是一个工业级的开源基于模型的工程工具。
* [Modelio](https://github.com/ModelioOpenSource/Modelio)：Modelio是一种建模解决方案，提供基于企业架构、软件开发和系统工程常用标准的广泛功能。
* [MagicDraw](https://www.3ds.com/products/catia/no-magic/magicdraw)：MagicDraw是一款出色的建模工具，这是达索的商业工具。
* [Violet](https://github.com/violetumleditor/violetumleditor)：Violet是一个UML编辑器，易于学习和使用、可以画出漂亮的图表、完全免费跨平台。
* [JetUML](https://github.com/prmr/JetUML)：JetUML支持以最少的麻烦来绘制软件设计思想的草图，由麦吉尔大学教授开源。
* [UMLet](https://github.com/umlet/umlet)：UMLet是一个开源UML工具，具有简单的用户界面。
* [TinyUML](https://sourceforge.net/projects/tinyuml/)：TinyUML是一款免费软件工具，可轻松快速地创建UML 2图。
* [Topcoder](https://github.com/topcoder-archive/topcoder-platform-topcoder-UML-Tool)：TopCoder是一款易于使用、功能一致的建模工具，专为设计与开发竞赛而设计。

#### 数电

* [Workcraft](https://github.com/workcraft/workcraft)：Workcraft是一个跨平台工具集，用于捕获、模拟、合成和验证图形模型，由伦敦大学学院开源。
* [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)：Logisim Evolution是用于设计和模拟数字逻辑电路的教育软件。
* [Digital](https://github.com/hneemann/Digital)：Digital是一款易于使用的数字逻辑设计器和电路模拟器，专为教育目的而设计。
* [Logisim](https://github.com/lawrancej/logisim)：Logisim是一款用于设计和模拟数字逻辑电路的教育工具。
* [Cello](https://github.com/CIDARLAB/cello)：遗传电路设计自动化，由CIDAR实验室开发。
* [DIYLC](https://github.com/bancika/diy-layout-creator)：DIYLC是一款专为业余爱好者和电子爱好者设计的专用软件工具，用于在条形板、穿孔板、PCB和点对点布线上创建电路布局。
* [FidoCadJ](https://github.com/DarwinNE/FidoCadJ)：FidoCadJ是一款易于使用的编辑器，拥有庞大的电气符号和封装库(通孔和SMD)。
* [CircuitJS1](https://github.com/sharpie7/circuitjs1)：CircuitJS1是一个在浏览器中运行的电子电路模拟器。
* [Circuit Simulator](https://github.com/hausen/circuit-simulator)：Circuit Simulator是一个电子电路模拟器。
* [Blackboard](https://github.com/mpue/blackboard)：Blackboard是为业余爱好者设计的，可以帮助在所谓的面包板上轻松构建原型。
* [CircuitSim](https://github.com/ra4king/CircuitSim)：基本电路模拟器。
* [OpenBench LogicSniffer](https://github.com/jawi/ols)：开源逻辑分析仪Open Bench Logic Sniffer的替代客户端。
* [GeckoCIRCUITS](https://github.com/geckocircuits/GeckoCIRCUITS)：GeckoCIRCUITS是一款针对电力电子应用优化的快速电路模拟器。
* [JSpice](https://github.com/knowm/jspice)：JSpice是一个受SPICE启发、用Java制作的模拟电路模拟器，重点是模拟忆阻器和包含忆阻器的模拟电路。
* [Coulomb](https://github.com/hamza-algohary/Coulomb)：Coulomb是一个使用Java、Gtk4和libadwaita编写的简单而优雅的电路模拟器。

#### 数控

* [Universal G-Code Sender](https://github.com/winder/Universal-G-Code-Sender)：Universal G-Code Sender是一个基于Java的跨平台G-Code发送器，兼容GRBL、TinyG、g2core和Smoothieware。
* [CNC-GCode-Controller](https://github.com/im-pro-at/cncgcodecontroller)：CNC GCode Controller是一个用于控制和与CNC机床通信的软件应用程序。
* [GCode Sender](https://github.com/SourceRabbit/gcode-sender)：SourceRabbit GCode Sender是一款兼容GRBL的跨平台G-Code发送器。
* [TgFX](https://github.com/synthetos/tgFX)：TgFX用于使用TinyG CNC控制器的跨平台GUI。

#### CAD

* [iBioSim](https://github.com/MyersResearchGroup/iBioSim)：iBioSim是一款计算机辅助设计(CAD)工具，旨在对基因回路进行建模、分析和设计，由科罗拉多大学博尔德分校开发。
* [CaDoodle](https://github.com/CommonWealthRobotics/CaDoodle)：CaDoodle是一款适用于Linux、Windows、Mac和ChromeOS的本地拖放式CAD应用程序。
* [ORIPA](https://github.com/oripa/oripa)：ORIPA是一款专门用于设计折纸折痕图案的绘图软件。
* [Archimedes](https://github.com/ArchimedesCAD/Archimedes)：Archimedes是一款免费开源CAD软件。

#### 办公软件

* [LibreOffice](https://github.com/LibreOffice/core)：LibreOffice是一款免费且功能强大的办公套件，是OpenOffice的继承者。
* [ThinkFree Office](https://thinkfree.com/)：ThinkFree Office是一款廉价却高效的Microsoft Office替代品。
* [OpenOffice](https://www.openoffice.org/)：OpenOffice是一个开源的办公包软件，起源于Sun公司从StarDivision收购的StarOffice。
* [永中Office](https://www.yozosoft.com/index.html)：永中Office是由永中科技公司用Java语言开发的一个可以在Windows、Linux等多个不同操作系统上运行的办公软件，与微软Microsoft Office相似。
* [泰山Office](http://web.ts-it.cn/index.html)：泰山Office采用Java开发，深度优化JVM，全面兼容国产CPU(龙芯、飞腾、鲲鹏、兆芯、申威)、国产操作系统(UOS、中标麒麟、银河麒麟、深度等)，是一款完全自主可控、安全可靠的国产基础办公软件。
* [Hancom Office](https://www.hancom.com/main/main.do)：Hancom Office是一款专有办公套件，其中包括文字处理器、电子表格软件、演示软件和PDF编辑器以及可通过互联网浏览器访问的在线版本，由韩国Hancom公司开发。
* [HCL Notes](https://www.hcl-software.com/domino)：HCL Notes是由HCLTech销售的适用于Unix、IBM i、Windows、Linux和macOS的专有协作软件平台。
* [Joeffice](https://www.joeffice.com/)：Joeffice是用Java编写的开源办公套件。

#### 思维导图

* [Freeplane](https://github.com/freeplane/freeplane)：Freeplane是一款免费的开源软件应用程序，支持在工作、学校和家庭中思考、共享信息、完成工作。
* [Xmind](https://xmind.app/)：XMind是一个由香港XMind公司开发的脑力激荡法和心智图的软件工具，其主要用途为帮助用户捕捉想法，组织各类报表。
* [FreeMind](https://freemind.sourceforge.io/)：FreeMind是一款跨平台、用Java编写的绘制思维导图的软件。
* [VUE](https://github.com/VUE/VUE)：VUE是一个用Java编写的免费开源概念图应用程序，由塔夫茨大学学术技术小组开发。
* [CompendiumNG](https://github.com/compendiumng/compendiumng)：CompendiumNG是一个功能强大的应用程序，可让你使用节点和链接结构创建广泛的地图，由英国开放大学开源。
* [MindRaider](https://mindraider.sourceforge.net/)：MindRaider是一款个人笔记本和大纲编辑器。
* [Mindolph](https://github.com/mindolph/Mindolph)：Mindolph是一款开源个人知识管理软件。
* [Zettelkasten](https://github.com/Zettelkasten-Team/Zettelkasten)：Zettelkasten是一款知识管理工具。
* [Hypernomicon](https://github.com/jasonwinning/hypernomicon)：Hypernomicon是一款面向研究人员的个人生产力/数据库应用程序，它将结构化笔记记录、思维导图、文件(如PDF)和文件夹管理以及参考文献管理整合到一个集成环境中。
* [WiseMapping](https://github.com/wisemapping/wisemapping-open-source)：WiseMapping是一个基于Web的开源思维导图工具。

#### 音视频软件

* [Bitwig Studio](https://www.bitwig.com/)：Bitwig Studio是由Bitwig公司开发的专有数字音频工作站。
* [TuxGuitar](https://github.com/helge17/tuxguitar)：TuxGuitar是一个用Java编写的开源多轨指法谱编辑器和播放器。
* [Shutter Encoder](https://github.com/paulpacifico/shutter-encoder)：Shutter Encoder是最好的视频转换器软件之一，它还可以处理图像和音频。
* [FileBot](https://www.filebot.net/)：FileBot是重命名和组织电影、电视节目和动漫的终极工具。
* [OwlPlug](https://github.com/DropSnorz/OwlPlug)：OwlPlug是一个音频插件管理器，用于在Windows、MacOS和Linux上管理VST/AU/LV2插件的小工具。
* [OpenAudible](https://github.com/openaudible/openaudible)：用于下载和管理Audible有声读物的跨平台桌面应用程序。
* [Photon](https://github.com/Netflix/photon)：Photon是IMF标准的Java实现，由Netflix开源。
* [Audiveris](https://github.com/Audiveris/audiveris)：Audiveris是一款开源光学音乐识别(OMR)软件，它用于扫描乐谱并将其转换为机器可读的格式，例如MusicXML或MIDI。
* [AudioBookConverter](https://github.com/yermak/AudioBookConverter)：AudioBookConverter设计为一款简洁轻量的应用程序，用于将一组MP3文件转换为单个M4B文件。
* [SageTV](https://github.com/google/sagetv)：SageTV是一个跨平台联网DVR和媒体管理系统，由Google开发。
* [jPSXdec](https://github.com/m35/jpsxdec)：jPSXdec是一款现代的跨平台PlayStation 1音频/视频转换器。
* [JJazzLab](https://github.com/jjazzboss/JJazzLab)：JJazzLab是一个完整开放的应用程序，专用于背景音乐生成。
* [Midica](https://github.com/truj/midica)：Midica是一种音乐编程语言的解释器，它将源代码翻译成MIDI。
* [Tracker](https://github.com/OpenSourcePhysics/tracker)：基于开源物理(OSP)框架构建的视频分析和建模工具。
* [Phon](https://github.com/phon-ca/phon)：Phon是一个软件程序，可以极大地促进与基于转录和声学测量的语音数据分析相关的许多任务，由纽芬兰纪念大学开源。

#### 数据库软件

* [DBeaver](https://github.com/dbeaver/dbeaver)：DBeaver是一款免费的跨平台数据库工具。
* [Datagrip](https://www.jetbrains.com/datagrip/)：Datagrip是JetBrains公司开发的适用于关系数据库和NoSQL数据库的强大跨平台工具。
* [Chat2DB](https://github.com/CodePhiliaX/Chat2DB)：Chat2DB是一款AI first的数据管理、开发、分析工具，由阿里开源。
* [CloudDM](https://www.clougence.com/clouddm-personal)：CloudDM是开云集致公司推出的一款一站式多数据源开发管理工具。
* [MDUT](https://github.com/SafeGroceryStore/MDUT)：MDUT是一款集成多种主流数据库类型的中文数据库跨平台使用工具。
* [Jailer](https://github.com/Wisser/Jailer)：Jailer是一个用于数据库子集、模式和数据浏览的工具。
* [SQLeo](https://sqleo.sourceforge.io/)：SQLeo是一个强大的SQL工具，可将复杂查询(由OBIEE、Microstrategy、Cognos、Hyperion、Pentaho...生成)转换或反转为图表，以简化可视化和分析。
* [DbSchema](https://dbschema.com/)：DbSchema是一个面向图表的数据库设计器，具有集成的查询和数据工具。
* [Aqua Data Studio](https://aquadatastudio.com/products/)：业界领先的数据库IDE，具有数据管理和可视化功能。
* [ChartSQL](https://docs.chartsql.com/)：ChartSQL Studio是一个源代码编辑器，用于创建和执行SQL脚本、图表和可视化，由Sales Insights开源。
* [DbVisualizer](https://www.dbvis.com/)：DbVisualizer是一个功能丰富的SQL工具，适用于Windows、Mac和Linux系统。
* [SQL Workbench](https://codeberg.org/sql-workbench/workbench)：SQL Workbench/J是一个独立于DBMS的跨平台SQL查询工具。
* [Oracle SQL Developer](https://www.oracle.com/database/sqldeveloper/)：Oracle SQL Developer是一个免费的集成开发环境，可简化传统部署和云部署中Oracle数据库的开发和管理。
* [Airpal](https://github.com/airbnb/airpal)：Airpal是一种基于Web的查询执行工具，它利用Facebook的PrestoDB使用户可以轻松编写查询和检索结果，由Airbnb开源。
* [SchemaSpy](https://github.com/schemaspy/schemaspy)：SchemaSpy是一个数据库元数据分析器，它可以帮助你的数据库管理员和开发人员可视化、导航和理解你的数据模型。
* [SQuirreL](https://github.com/squirrel-sql-client/squirrel-sql-code)：SQuirrel SQL是一个用Java写的数据库管理工具。
* [DBEdit 2](https://dbedit2.sourceforge.net/)：DBEdit 2是一个数据库编辑器，适合作为所有关系型数据库的前端。
* [QStudio](https://github.com/timeseries/qstudio)：QStudio是一个免费的SQL GUI，它允许运行SQL脚本、轻松浏览表格、绘制图表和导出结果，由TimeStored开源。
* [Rel](https://reldb.org/c/)：Rel是一个主要用于教育目的的DBMS，但也适合用作桌面DBMS或轻量级服务器。
* [ODC](https://github.com/oceanbase/odc)：ODC是一款开源、全能的跨场景数据库协同开发和数据管理工具，阿里开源。
* [WeSync](https://github.com/rememberber/WeSync)：WeSync是Swing开发的数据库同步软件。
* [JookDB](https://jookdb.com/)：免费通用的数据库管理工具，支持多种数据库，由杰恩软件公司开发。
* [CloudBeaver](https://github.com/dbeaver/cloudbeaver)：CloudBeaver是一个云数据库管理器，提供丰富的Web界面。
* [EXperDB Management](https://github.com/experdb/eXperDB-Management)：EXperDB Management是一款PostgreSQL管理工具。
* [Binjr](https://github.com/binjr/binjr)：Binjr是一个独立的时序浏览器，它将其他应用程序生成的时序数据呈现为动态可编辑视图，并提供高级功能以顺畅高效地导航数据。
* [SQLucky](https://github.com/tenie/SQLucky)：SQLucky是一个跨平台数据库可视化操作工具。
* [DatabaseFX](https://gitee.com/databasefx/dbfx)：DatabaseFX是一个免费、跨平台、基于JavaFX和Vert.X SQL客户端的开源数据库管理工具。
* [ASH Viewer](https://github.com/akardapolov/ASH-Viewer)：ASH Viewer提供数据库中活动会话历史记录数据的图形视图。
* [RdbmsSyncTool](https://gitee.com/xwintop/x-RdbmsSyncTool)：RdbmsSyncTool是使用JavaFX开发的关系型数据库同步工具。
* [DBCompare](https://gitee.com/yisin/DBCompare)：DBCompare是使用Java Swing开发的一款数据库表结构对比工具，可以对比两个不同的数据库中表结构是否一致。
* [SqlBrowserFX](https://github.com/pariskol/sqlbrowserfx)：SqlBrowserFX是一个功能丰富的跨平台SQL客户端，适用于SQLite、MySQL、MariaDB和PostgreSQL。
* [Turacos](https://github.com/alanni-tom/Turacos)：Turacos是一款专业的多数据库安全评估工具，支持PostgreSQL、MySQL、Redis、MSSQL等多种数据库的后渗透操作。

#### 数据库建模

* [Open ModelSphere](http://www.modelsphere.com/org/index.html)：Open ModelSphere是一个强大的数据、流程和UML建模工具。
* [PDMaas](https://gitee.com/yonsum/PDMaas)：PDMaas是一款优秀的国产数据建模工具。
* [Mogwai ERDesigner NG](https://github.com/mirkosertic/MogwaiERDesignerNG)：Mogwai ERDesigner是一款实体关系建模/设计工具(ERD)，类似于ERWin等。
* [CHINER](https://gitee.com/robergroup/chiner)：CHINER元数建模，一款丰富数据库生态、独立于具体数据库之外的、数据库关系模型设计平台。
* [BrModelo](https://github.com/chcandido/brModelo)：BrModelo是一款开源的数据库建模工具，专为教育用途设计，由圣卡塔琳娜联邦大学开源。
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler)：SchemaCrawler是一个免费的数据库模式发现和理解工具。
* [FML](https://github.com/alibaba/fast-modeling-language)：FML是一种专为维度建模而设计的类似SQL的语言，由阿里开源。

#### 远程连接

* [XPipe](https://github.com/xpipe-io/xpipe)：XPipe是一种新型的Shell连接集线器和远程文件管理器，允许你从本地计算机访问整个服务器基础架构。
* [Cyberduck](https://github.com/iterate-ch/cyberduck)：Cyberduck是一款适用于Mac和Windows的自由FTP、SFTP、WebDAV、Amazon S3、Backblaze B2、Microsoft Azure和OneDrive以及OpenStack Swift文件传输客户端。
* [FinalShell](https://www.hostbuf.com/)：FinalShell是一款一体化的服务器，网络管理软件。
* [Ultimate Cube](https://github.com/G3G4X5X6/ultimate-cube)：Ultimate Cube是开源的远程服务器管理工具，支持SSH、RDP、Telnet、COM等协议。
* [Google Drive FTP Adapter](https://github.com/andresoviedo/google-drive-ftp-adapter)：使用Google Drive FTP Adapter，你可以通过FTP协议访问Google Drive。
* [SpringRemote](https://github.com/HaleyWang/SpringRemote)：SpringRemote是一个开源、选项卡式的远程Linux SSH连接管理器。

#### 终端模拟器

* [Snowflake](https://github.com/subhra74/snowflake)：图形化SFTP客户端和终端仿真器以及有用的实用程序。
* [Termora](https://github.com/TermoraDev/termora)：Termora是一个终端模拟器和SSH客户端，支持Windows，macOS和Linux。
* [T-Shell](https://github.com/TheBlindM/T-Shell)：T-Shell是一个可配置命令提示的终端模拟器和SSH客户端，目前只支持Windows。
* [TerminalFX](https://github.com/javaterminal/TerminalFX)：TerminalFX是一个用JavaFX 18编写的终端模拟器应用程序。
* [JediTerm](https://github.com/JetBrains/jediterm)：纯Java终端模拟器，适用于SSH和PTY，由JetBrains开源。
* [JediTermFX](https://github.com/techsenger/jeditermfx)：Techsenger JediTermFX是一款JavaFX终端仿真器。
* [TN5250J](https://github.com/tn5250j/tn5250j)：用Java编写的IBM i(AS/400)的5250终端仿真器。

#### 远程桌面控制

* [Dayon](https://github.com/retgal/dayon)：Dayon是一种易于使用、跨平台的远程桌面协助解决方案。
* [Tentacle](https://gitee.com/matrixy/tentacle)：基于Java AWT、Spring Boot、WebSocket、Canvas的跨平台远程桌面实现。
* [Remote Desktop Control](https://github.com/Cool-Coding/remote-desktop-control)：基于Spring、Netty、Swing开发的远程桌面控制软件。

#### Git客户端

* [SmartGit](https://www.syntevo.com/smartgit/)：SmartGit是一个Git GUI客户端，支持GitHub、BitBucket、GitLab拉取请求和评论。
* [Gitnuro](https://github.com/JetpackDuba/Gitnuro)：适合新手和专业人士的FOSS Git多平台客户端。
* [MeGit](https://github.com/eclipsesource/megit)：基于EGit的独立Git GUI。
* [Geetember](https://github.com/iazarny/gitember)：Gitember是一个用JavaFX编写的Git GUI客户端。

#### 下载器

* [Xtreme Download Manager](https://github.com/subhra74/xdm/tree/old-java-master)：XDM是一款功能强大的工具，可将下载速度提高500%，保存来自热门视频流网站的视频，恢复损坏/死亡的下载，安排和转换下载。
* [AB Download Manager](https://github.com/amir1376/ab-download-manager)：AB Download Manager是一款桌面应用程序，可帮助你比以往更高效地管理和组织下载。
* [MegaBasterd](https://github.com/tonikelope/megabasterd)：MegaBasterd是一个非官方的跨平台MEGA下载器/上传器/流媒体套件。
* [Proxyee Down](https://github.com/proxyee-down-org/proxyee-down)：Proxyee Down是一款开源的免费HTTP高速下载器，底层使用Netty开发，支持自定义HTTP请求下载且支持扩展功能，可以通过安装扩展实现特殊的下载需求。
* [Video Download Manager](https://github.com/ingbyr/vdm)：命令行视频下载器的GUI。
* [RipMe](https://github.com/RipMeApp/ripme)：RipMe是一个适用于各种网站的专辑翻录工具。
* [BilibiliDown](https://github.com/nICEnnnnnnnLee/BilibiliDown)：Bilibili视频下载器，用于下载B站视频。
* [Uncle Novel](https://github.com/uncle-novel/uncle-novel)：一个桌面端应用，支持MacOS/Windows，提供了全网小说的转码阅读功能。
* [Telegram Files](https://github.com/jarvis2f/telegram-files)：自托管的Telegram文件下载器，用于连续、稳定和无人值守的下载。
* [Drifty](https://github.com/SaptarshiSarkar12/Drifty)：Drifty是一个用Java构建的开源交互式文件下载系统，它提供CLI和GUI，灵活易用。
* [JDownloader](https://github.com/mycodedoesnotcompile2/jdownloader_mirror)：JDownloader是一款免费的开源下载管理工具。
* [JDownloader](https://github.com/mirror/jdownloader)：JDownloader是一款免费的开源下载管理工具。

#### LaTeX编辑器

* [TeXtidote](https://github.com/sylvainhalle/textidote)：LaTeX文档和其他格式的修正工具。
* [LaTeXDraw](https://github.com/latexdraw/latexdraw)：LaTeXDraw是LaTeX的图形绘图编辑器。
* [Open LaTeX Studio](https://github.com/sebbrudzinski/Open-LaTeX-Studio)：支持远程协作的开源LaTeX编辑器。

#### 字幕软件

* [Jubler](https://github.com/teras/Jubler)：Jubler是一个编辑基于文本的字幕的工具。
* [ArcTime](https://arctime.org/)：ArcTime是一个易用、强大、高效的字幕制作软件，由南京亿铭科技开发。
* [Caption OCR Tool](https://github.com/sum1re/caption_ocr_tool)：视频硬字幕提取工具。

## 游戏开发

这里列出来Java中用于开发游戏的引擎、库、工具，以及Java开发的一些免费游戏

#### 游戏引擎

* [LibGDX](https://github.com/libgdx/libgdx)：LibGDX是一个基于OpenGL的跨平台Java游戏开发框架，专为Windows、Linux、macOS、Android、Web浏览器和iOS设计。
* [FXGL](https://github.com/AlmasB/FXGL)：Java/JavaFX/Kotlin游戏引擎库。
* [Godot Kotlin/JVM](https://github.com/utopia-rise/godot-kotlin-jvm)：Godot Kotlin/JVM是一个Godot模块，它允许你在JVM上使用Kotlin编写游戏或应用程序逻辑。
* [KTX](https://github.com/libktx/ktx)：KTX是一个扩展LibGDX的Kotlin游戏框架。
* [jMonkeyEngine](https://github.com/jMonkeyEngine/jmonkeyengine)：jMonkeyEngine是一款适合富有冒险精神的Java开发人员的3D游戏引擎。
* [Defold](https://github.com/defold/defold)：Defold是一款完全免费的游戏引擎，可用于开发桌面、移动和Web游戏。
* [KorGE](https://github.com/korlibs/korge)：KorGE是Kotlin的现代多平台游戏引擎。
* [Ludii](https://github.com/Ludeme/Ludii)：Ludii是一个通用游戏系统，旨在玩、评估和设计各种游戏，包括棋盘游戏、纸牌游戏、骰子游戏、数学游戏等，由马斯特里赫特大学开源。
* [SGDK](https://github.com/Stephane-D/SGDK)：适用于Sega Mega Drive的免费开源开发套件。
* [OpenRTS](https://github.com/methusalah/OpenRTS)：OpenRTS是一个3D即时战略游戏引擎。
* [JBox2d](https://github.com/jbox2d/jbox2d)：JBox2d是C++物理引擎LiquidFun和Box2d的Java端口。
* [Terasology](https://github.com/MovingBlocks/Terasology)：Terasology项目诞生于受Minecraft启发的技术演示，并正在成为体素世界中各种类型游戏设置的稳定平台。
* [AndEngine](https://github.com/nicolasgramlich/AndEngine)：免费Android 2D OpenGL游戏引擎。
* [XMage](https://github.com/magefree/mage)：XMage允许你与一名或多名在线玩家或电脑对手玩万智牌。
* [FriceEngine](https://github.com/icela/FriceEngine)：FriceEngine是一个简单、轻量级的原生游戏引擎，主要运行在JVM上。
* [TripleA](https://github.com/triplea-game/triplea)：TripleA是一款回合制策略游戏和棋盘游戏引擎，类似于Axis & Allies或Risk。
* [Delver](https://github.com/Interrupt/delverengine)：Delver游戏引擎和编辑器。
* [Indigo](https://github.com/PurpleKingdomGames/indigo)：Indigo是一款用Scala编写的游戏引擎，专为函数式程序员打造，由Purple Kingdom游戏公司开源。
* [Litiengine](https://github.com/gurkenlabs/litiengine)：LITIENGINE是一个免费且开源的Java 2D游戏引擎，它提供了一个全面的Java库和一个专用的地图编辑器来创建基于图块的2D游戏。
* [Mini2Dx](https://github.com/mini2Dx/mini2Dx)：Mini2Dx的主要目标是提供一个初学者友好、精通的框架，用于用Java快速原型设计和构建2D游戏。
* [LGame](https://github.com/cping/LGame)：LGame是一个跨平台的Java游戏引擎，支持JavaFX/Android/IOS/HTML5/Linux/MAC/Windows。
* [Jake2](https://bytonic.de/html/jake2.html)：Quake II游戏引擎的Java端口。
* [LionEngine](https://github.com/b3dgs/lionengine)：LionEngine是专为Lionheart Remake项目开发的游戏引擎，可轻松与Java一起使用。
* [SilenceEngine](https://github.com/sriharshachilakapati/SilenceEngine)：SilenceEngine是一款2D/3D游戏引擎，可以为你处理游戏开发的低级方面，如图形、输入处理、资源加载和碰撞检测。
* [JustWeEngine](https://github.com/lfkdsk/JustWeEngine)：一个简单的开源Android原生游戏框架。
* [Spout](https://github.com/spoutdev/Spout)：开源、多线程、体素游戏引擎和平台，用Java编写。
* [LittleKt](https://github.com/littlektframework/littlekt)：LittleKt是一个基于WebGPU的Kotlin多平台2D游戏开发框架。
* [MiniGDX](https://github.com/minigdx/minigdx)：MiniGDX是一款基于Kotlin/Multiplatform的极简3D游戏引擎。
* [DD Poker](https://github.com/dougdonohoe/ddpoker)：DD Poker电脑游戏源代码、底层游戏引擎以及支持的后端服务器和配套网站。
* [Chunk Stories](https://github.com/Hugobros3/chunkstories)：Chunk Stories是一款高级版Minecraft克隆版，其定制引擎拥有一流的模组支持。
* [CosPlay](https://github.com/nivanov/cosplay)：CosPlay是用Scala 3编写的2D ASCII游戏引擎。
* [Engine](https://github.com/UnknownDomainGames/Engine)：本项目为一款模组化游戏引擎，开发语言为Java，渲染后端为OpenGL 4.2及Vulkan。
* [Scage](https://github.com/delorum/scage)：Scage是一个用于编写简单2D OpenGL游戏的框架。
* [Tiny](https://github.com/minigdx/tiny)：Tiny是一款由Lua提供支持的轻量级跨平台游戏引擎。
* [Voodoo2D](https://github.com/JacksonHoggard/voodoo2d)：Voodoo2D是一款基于LWJGL构建的2D游戏引擎，其设计旨在轻量级且易于使用。
* [WurfelEngine](https://github.com/BSVogler/WurfelEngineSDK)：WurfelEngine是一款基于Java的游戏引擎，专为创建具有等距渲染风格的3D游戏而设计。
* [Kubriko](https://github.com/pandulapeter/kubriko)：Kubriko旨在为Android、桌面(Windows、Linux、macOS)、iOS和Web平台创建简单的2D游戏，提供一个轻量级、可扩展且易于使用的解决方案。
* [GDL](https://github.com/damn/gdl-old)：GDL是一个函数式2D游戏引擎，围绕保存应用程序当前状态的上下文对象的思想构建。
* [DimensioneX](https://www.dimensionex.net/)：DimensioneX是一款简单、免费的多人(MMORPG)游戏引擎。
* [VASSAL](https://github.com/vassalengine/vassal)：VASSAL是一个游戏引擎，用于构建和玩在线改编的棋盘游戏和纸牌游戏。
* [Env3D](https://sourceforge.net/projects/env3d/)：用Java编写的3D引擎，面向计算机科学专业的学生。
* [FastJ](https://github.com/fastjengine/FastJ)：FastJ是一个免费开源的基于Java的2D游戏引擎和框架，它旨在使用Java(和JVM语言)提供最佳的2D游戏制作体验。
* [Kool](https://github.com/kool-engine/kool)：Kool是一个多平台OpenGL/WebGPU/Vulkan游戏引擎，适用于桌面Java、Android和浏览器。
* [OpenRSC](https://github.com/Open-RSC/Core-Framework)：该仓库包含Open RuneScape Classic游戏框架。
* [Yaeger](https://github.com/han-yaeger/yaeger)：Yaeger是一个教育游戏引擎运行时，也是一个功能齐全的2D游戏引擎，只需要传统的面向对象编程风格，由HAN应用科技大学开源。
* [Arc](https://github.com/Anuken/Arc)：基于LibGDX的Java游戏开发框架。
* [VatraLib](https://vatrasoft.de/vatralib/)：VatraLib是一个用Java编写的2D游戏引擎。
* [Omicron](https://github.com/msx80/Omicron)：Omicron是一个基于LibGDX的开源Java游戏引擎。
* [RemsEngine](https://github.com/AntonioNoack/RemsEngine)：RemsEngine是一个基于Kotlin/OpenGL/ECS的开源游戏引擎。
* [Marauroa](https://github.com/arianne/marauroa)：Marauroa是一款多人在线游戏引擎。

#### Minecraft

* [Paper](https://github.com/PaperMC/Paper)：Paper是一个基于Spigot的Minecraft游戏服务器，旨在大幅提高性能并提供更高级的功能和API。
* [Docker Minecraft Server](https://github.com/itzg/docker-minecraft-server)：Docker镜像为Java版提供Minecraft服务器，可在启动时自动下载所选版本。
* [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge)：Forge是一个免费的开源修改API，可供你所有喜爱的Mod使用。
* [HMCL](https://github.com/HMCL-dev/HMCL)：HMCL是一个开源、跨平台的Minecraft启动器，支持Mod管理、游戏自定义、ModLoader安装、Modpack创建、UI自定义等。
* [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)：PojavLauncher是一个启动器，可让你在Android和iOS设备上玩Minecraft Java版。
* [Sodium](https://github.com/CaffeineMC/sodium-fabric)：Sodium是Minecraft客户端的强大渲染引擎和优化模块，可提高帧速率并减少微卡顿，同时修复Minecraft中的许多图形问题。
* [Geyser](https://github.com/GeyserMC/Geyser)：Geyser是Minecraft基岩版和Minecraft Java版之间的桥梁，为那些想要真正跨平台游戏的玩家提供了便利。
* [Brigadier](https://github.com/Mojang/brigadier)：Brigadier是一个命令解析器和调度器，专为Minecraft Java版设计和开发。
* [WorldEdit](https://github.com/EngineHub/WorldEdit)：WorldEdit是一款易于使用的游戏内Minecraft地图编辑器。
* [Iris](https://github.com/IrisShaders/Iris)：适用于Minecraft的现代着色器模型，与现有的OptiFine着色器包兼容。
* [MCA Selector](https://github.com/Querz/mcaselector)：MCA Selector是一个外部工具，用于导出、删除或编辑Minecraft Java版世界保存中的选定块和区域。
* [Bukkit](https://github.com/Bukkit/Bukkit)：Bukkit是一个由社区开发的开源工具，用于减轻开发服务器插件的负担。
* [Create](https://github.com/Creators-of-Create/Create)：Create是一个提供用于建筑、装饰和美学自动化的各种工具和模块的模组。
* [Amidst](https://github.com/toolbox4minecraft/amidst)：Amidst是一个显示Minecraft世界概览的工具，无需实际创建它。
* [Minestom](https://github.com/Minestom/Minestom)：Minestom是一个开源库，开发人员可以使用它创建自己的Minecraft服务器软件，而无需Mojang的任何代码。
* [Dynmap](https://github.com/webbukkit/dynmap)：Dynmap是类似Google地图的Minecraft服务器地图，可以在浏览器中查看。
* [Fabric](https://github.com/FabricMC/fabric)：Fabric API是Fabric模块必备钩子和互操作机制的库。
* [SeedcrackerX](https://github.com/19MisterX98/SeedcrackerX)：SeedcrackerX是一个用于破解我的世界Java版游戏世界种子的模组。
* [McMMO](https://github.com/mcMMO-Dev/mcMMO)：McMMO的目标是采用核心Minecraft游戏机制并将其扩展为广泛而优质的RPG体验。
* [Glowstone](https://github.com/GlowstoneMC/Glowstone)：Glowstone是一款轻量级、从零开始的开源Minecraft服务器，支持为Bukkit API及其主要分支Spigot和Paper编写的插件。
* [CatServer](https://github.com/Luohuayu/CatServer)：CatServer是一个高性能的Forge、Bukkit、Spigot服务端核心。
* [LuckPerms](https://github.com/LuckPerms/LuckPerms)：LuckPerms是一款适用于Minecraft服务器的权限插件，它允许服务器管理员通过创建群组和分配权限来控制玩家可以使用的功能。
* [Lithium](https://github.com/CaffeineMC/lithium-fabric)：Lithium是一款免费的开源Minecraft模组，可优化游戏的许多领域，以提供更好的整体性能。
* [Essentials](https://github.com/EssentialsX/Essentials)：EssentialsX是Essentials插件套件的延续，已更新以支持现代Minecraft和Spigot版本。
* [Meteor](https://github.com/MeteorDevelopment/meteor-client)：基础Minecraft实用程序模组。
* [BungeeCord](https://github.com/SpigotMC/BungeeCord)：BungeeCord是一款复杂的代理和API，主要用于在多个Minecraft服务器之间传送玩家。
* [BlueMap](https://github.com/BlueMap-Minecraft/BlueMap)：BlueMap是一个程序，它可以读取你的Minecraft世界文件并生成地图，还可以生成整个表面的3D模型。
* [Velocity](https://github.com/PaperMC/Velocity)：Velocity是一款现代的高性能代理服务器。
* [FarPlaneTwo](https://github.com/PorkStudios/FarPlaneTwo)：FarPlaneTwo是一个为Minecraft实现了多细节层次(LoD)地形渲染的Mod。
* [Applied Energistics 2](https://github.com/AppliedEnergistics/Applied-Energistics-2)：Applied Energistics 2是Minecraft的一个综合模组，它引入了一种独特的游戏内库存管理方法。
* [Botania](https://github.com/VazkiiMods/Botania)：Botania是一个以自然魔法为主题的Minecraft技术模组。
* [SpongeAPI](https://github.com/SpongePowered/SpongeAPI)：Sponge的目的是为Minecraft Java版创建一个插件开发框架。
* [Nukkit](https://github.com/CloudburstMC/Nukkit)：Nukkit是Minecraft基岩版的核动力服务器软件。
* [SpongeForge](https://github.com/SpongePowered/SpongeForge)：实现SpongeAPI的Forge模组。
* [Adventure](https://github.com/KyoriPowered/adventure)：Adventure是Minecraft Java版中服务器可控制的用户界面元素库。
* [BuildCraft](https://github.com/BuildCraft/BuildCraft)：BuildCraft是一个历史悠久的物流向模组。
* [MultiPaper](https://github.com/MultiPaper/MultiPaper)：MultiPaper是一个多服务器、单世界的PaperMC实现。
* [Folia](https://github.com/PaperMC/Folia)：Folia是PaperMC组织最新的项目，旨在实现真正的多线程和区域化心跳。
* [Fold Craft Launcher](https://github.com/FCL-Team/FoldCraftLauncher)：FCL是由FCL-Team基于HMCL的核心功能，结合PojavLauncher后端和Boat后端开发的Minecraft Java版启动器。
* [Purpur](https://github.com/PurpurMC/Purpur)：Purpur是Paper服务器的替代品，旨在实现可配置性、新颖有趣且令人兴奋的游戏功能以及基于Paper的性能。
* [VulkanMod](https://github.com/xCollateral/VulkanMod)：VulkanMod是一个Fabric Mod，它为Minecraft Java引入了一个全新的基于Vulkan的体素渲染引擎，以替换默认的OpenGL渲染器并带来性能改进。
* [Arclight](https://github.com/IzzelAliz/Arclight)：Arclight是一款支持Bukkit和Forge插件的混合服务器。
* [LiquidBounce](https://github.com/CCBlueX/LiquidBounce)：LiquidBounce是一个免费的开源的基于Mixin的注入式黑客客户端，使用Minecraft的Fabric API。
* [BedrockConnect](https://github.com/Pugmatt/BedrockConnect)：BedrockConnect是一款极简版Minecraft基岩版服务器软件，为玩家提供服务器列表解决方案。
* [OpenComputers](https://github.com/MightyPirates/OpenComputers)：OpenComputers是一个Minecraft模组，它为游戏添加了可编程计算机和机器人。
* [NeoForge](https://github.com/neoforged/NeoForge)：NeoForge是针对Minecraft的免费、开源、面向社区的修改API。
* [Mekanism](https://github.com/mekanism/Mekanism)：Mekanism是一款独立的Minecraft插件，具有可用于制造强大工具、盔甲和武器的高科技机械。
* [Mohist](https://github.com/MohistMC/Mohist)：Mohist是一个出色的Minecraft Forge服务器软件，实现了Bukkit、Spigot API。
* [ViaVersion](https://github.com/ViaVersion/ViaVersion)：ViaVersion是一个多平台插件，允许你在Minecraft服务器上处理未来的客户端版本。
* [Cardboard](https://github.com/CardboardPowered/cardboard)：Cardboard是FabricMC流行的Bukkit/Spigot/Paper Modding API的实现。
* [Carpet](https://github.com/gnembon/fabric-carpet)：Carpet Mod是原版Minecraft的一个模组，它允许你从游戏的技术角度完全控制重要的事情。
* [GrimAC](https://github.com/GrimAnticheat/Grim)：GrimAC是一款开源的Minecraft反作弊软件，旨在支持最新版本的Minecraft。
* [Starlight](https://github.com/PaperMC/Starlight)：重写灯光引擎以修复照明性能和照明错误。
* [Wurst](https://github.com/Wurst-Imperium/Wurst7)：Wurst是一个开源的Minecraft破解客户端。
* [Phosphor](https://github.com/CaffeineMC/phosphor-fabric)：Phosphor是一个免费的开源Minecraft模组，旨在通过优化Minecraft最低效的区域之一-照明引擎，节省你的CPU周期并提高性能。
* [Tweaked](https://github.com/cc-tweaked/CC-Tweaked)：Tweaked是Minecraft的一个模组，它为游戏添加了可编程计算机、乌龟等内容。
* [Yarn](https://github.com/FabricMC/yarn)：Yarn是一组开放、不受限制的Minecraft映射。
* [Minecraft World Downloader](https://github.com/mircokroon/minecraft-world-downloader)：Minecraft世界下载器作为客户端和服务器之间的代理服务器来读取和保存块数据。
* [MCinaBox](https://github.com/AOF-Dev/MCinaBox)：MCinaBox是Android上的Minecraft Java版启动器。
* [Skript](https://github.com/SkriptLang/Skript)：Skript是Paper/Spigot的Minecraft插件，它允许服务器所有者和其他人无需学习Java即可修改他们的服务器。
* [ProtocolLib](https://github.com/dmulloy2/ProtocolLib)：使用Bukkit提供对Minecraft协议的读写访问。
* [EnchantmentCracker](https://github.com/Earthcomputer/EnchantmentCracker)：EnchantmentCracker是一个用于Minecraft Java版的工具，它通过分析游戏的随机数种子，来预测和破解游戏中的附魔机制。
* [ZalithLauncher](https://github.com/ZalithLauncher/ZalithLauncher)：Zalith Launcher是一款基于PojavLauncher的Minecraft启动器，可在Android设备上运行Minecraft Java版。
* [DiscordSRV](https://github.com/DiscordSRV/DiscordSRV)：DiscordSRV是一个用于Minecraft服务器的插件，它能在游戏的聊天频道和指定的Discord服务器频道之间建立一座双向桥梁，实现无缝的实时通信。
* [Slimefun4](https://github.com/Slimefun/Slimefun4)：Slimefun是一个插件，旨在将你的Spigot服务器变成一个Modpack，而无需安装任何Mod。
* [MCreator](https://github.com/MCreator/MCreator)：MCreator是一款用于制作Minecraft Java版模组、Minecraft Bedrock版附加组件和数据包的软件，使用直观易学的界面或集成代码编辑器。
* [Minosoft](https://github.com/Bixilon/Minosoft)：Minosoft是一个开源的Minecraft客户端，用Kotlin和Java从头开始编写。
* [PojavLauncher iOS](https://github.com/PojavLauncherTeam/PojavLauncher_iOS)：PojavLauncher是一款适用于Android、iOS和iPadOS的Minecraft Java版启动器。

#### 游戏服务器

* [Lila](https://github.com/lichess-org/lila)：Lila是一款免费的在线国际象棋游戏服务器，专注于实时游戏玩法和易用性。
* [NettyGameServer](https://github.com/jwpttcg66/NettyGameServer)：NettyGameServer是基于Netty 4.X实现的手机游戏分布式服务器，支持TCP、UDP、HTTP、WebSocket链接。
* [JetServer](https://github.com/menacher/java-game-server)：JetServer是一个基于高速NIO套接字的多人Java游戏服务器，使用Netty和Jetlang编写。
* [Game Server](https://github.com/jzyong/game-server)：Game Server是一个基于棋牌、MMORPG游戏的分布式java游戏服务器。
* [AiJ](https://gitee.com/xiyoufang/aij)：AiJ是一套完整的房间类游戏解决方案，支持无限水平扩展来满足更大的人数承载，并且提供了良好的调试接口。
* [Summer](https://github.com/SwingFrog/Summer)：Summer是一个轻量级、一站式的Java游戏服务器框架，也可用于开发简单的Web服务。
* [JForGame](https://github.com/kingston-csj/jforgame)：JForGame是一个用Java编写的轻量级高性能手游服务端框架，包含游戏服、跨服、匹配服、后台管理系统等模块。
* [Mmorpg](https://github.com/kingston-csj/mmorpg)：Mmorpg是一个用Java编写的分布式高性能mmorpg手游服务端框架。
* [GameServer4j](https://github.com/jzyong/GameServer4j)：分布式Java游戏服务器，包括登录、网关、游戏演示。
* [ZFoo](https://github.com/zfoo-project/zfoo)：ZFoo是一个极快的企业服务器框架，可用于RPC、游戏服务器、Web服务器。
* [Apollo](https://github.com/apollo-rsps/apollo)：Apollo是一个高性能、模块化的RuneScape模拟器，具有一系列用于管理数据文件和插件的实用程序。
* [Noark](https://gitee.com/xiaoe/noark3)：Noark是一个游戏服务器端框架，可快速开发出一个易维护、易扩展且稳定高能的游戏服务器。
* [Carmelo](https://github.com/needmorecode/carmelo)：Carmelo是一个快速、可扩展的Java服务器框架，专为在线游戏而设计。
* [Okra](https://github.com/ogcs/Okra)：Okra是一个简单的使用Java开发的高性能、高扩展、高并发、低延迟的服务器框架。
* [Gamioo](https://github.com/jiangguilong2000/gamioo)：游戏服务器框架，基于此框架，可以快速实现一个高可用、易维护、稳定、高性能的游戏服务器。
* [TenIO](https://github.com/congcoi123/tenio)：TenIO是一个用于创建多人在线游戏的开源项目，其中包括专门为多人游戏设计的基于Java NIO的服务器。
* [Avalon](https://gitee.com/codeborker/Avalon)：基于Akka的高性能可伸缩的Java网络游戏服务器，简单的单服务器开发与集群开发的切换。
* [Grasscutter](https://github.com/Grasscutters/Grasscutter)：Grasscutter是一个实验性游戏服务器，旨在模拟玩某个动漫游戏的体验。
* [Sorapointa](https://github.com/Sorapointa/Sorapointa)：为某款动漫游戏重新实现服务器软件。
* [Finisterra](https://github.com/ao-libre/finisterra)：基于热门阿根廷MMORPG Argentum Online的Java游戏客户端和服务器。
* [RS Mod](https://github.com/rsmod/rsmod)：RS Mod是一款RuneScape游戏服务器模拟器，旨在尽可能在机械上与原版游戏保持一致。
* [TOAST Haste](https://github.com/nhn/toast-haste.framework)：TOAST Haste是一个易于开发的异步游戏服务器框架。
* [PretendYoureXyzzy](https://github.com/ajanata/PretendYoureXyzzy)：反人类卡牌克隆、服务器和Web客户端。
* [LunarCore](https://github.com/Melledy/LunarCore)：某回合制动漫游戏的游戏服务器重新实现。
* [L2J Server](https://bitbucket.org/l2jserver/l2j-server-game)：L2J Server是一款完全用Java编写的开源服务器模拟器，适用于著名的韩国MMORPG。

#### 游戏模拟器

* [Coffee GB](https://github.com/trekawek/coffee-gb)：Coffee GB是一款Gameboy Color模拟器。
* [Jpcsp](https://github.com/jpcsp/jpcsp)：Jpcsp是最先进的PlayStation Portable模拟器，允许你在PC上玩PSP游戏。
* [Kepler](https://github.com/Quackster/Kepler)：Kepler是一款Habbo Hotel模拟器，旨在完全模拟2007年v14版本。
* [Aion Germany](https://github.com/AionGermany/aion-germany)：Aion EU模拟器。
* [Entralinked](https://github.com/kuroppoi/entralinked)：Entralinked是一款独立的Game Sync模拟器，专为Pokémon Black & White及其续作开发。
* [Halfnes](https://github.com/andrew-hoffman/halfnes)：一款精准的NES/Famicom模拟器。
* [Battle Cats Ultimate](https://github.com/battlecatsultimate/BCU-java-PC)：战斗猫终极版，一款由粉丝制作的战斗猫模拟器。
* [ZX-Poly](https://github.com/raydac/zxpoly)：多CPU ZX-Spectrum 128概念平台。
* [Nes4j](https://gitee.com/navigatorCode/nes4j)：基于Java语言实现的任天堂红白机模拟器。

#### 2D/3D渲染

* [LWJGL](https://github.com/LWJGL/lwjgl3)：LWJGL是一个Java库，支持跨平台访问流行的原生API，可用于图形(OpenGL、Vulkan、bgfx)、音频(OpenAL、Opus)、并行计算(OpenCL、CUDA)和XR(OpenVR、LibOVR、OpenXR)应用程序。
* [Skija](https://github.com/JetBrains/skija)：Skia是一个开源2D图形库，提供可跨各种硬件和软件平台工作的通用API，Skija是Skia的高质量Java绑定，由JetBrains开源。
* [Rajawali](https://github.com/Rajawali/Rajawali)：Rajawali是一款基于OpenGL ES 2.0/3.0的Android 3D引擎。
* [Jzy3d](https://github.com/jzy3d/jzy3d-api)：Jzy3d是一个用Java轻松绘制3D和2D图表的框架，使用快速原生GPU渲染或基于CPU的渲染来增强跨OS/JVM/GPU组合的可移植性。
* [JOGL](https://github.com/sgothel/jogl)：JOGL项目负责Java高性能图形绑定的开发，旨在为用Java编写的应用程序提供硬件支持的3D图形和多媒体，最初由Sun开发。
* [PanamaGL](https://gitlab.com/jzy3d/panama-gl)：PanamaGL旨在使用适用于JDK 22及更高版本的FFM API提供与OpenGL的多平台绑定。
* [OPENRNDR](https://github.com/openrndr/openrndr)：OPENRNDR是一个用于创意编码、实时和交互式图形的Kotlin/JVM库。
* [VK²](https://github.com/kotlin-graphics/vkk)：VK²的目标是为Vulkan C API提供一个库，以提升开发者的Vulkan体验，且不会带来任何显著的CPU运行时开销。
* [GraphicsFuzz](https://github.com/google/graphicsfuzz)：GraphicsFuzz提供了自动查找和简化图形驱动程序中的错误的工具，由Google开源。
* [Kgpu](https://github.com/kgpu/kgpu)：基于WebGPU和WebGPU Native的Kotlin JVM/JS跨平台图形API。
* [Nifty GUI](https://github.com/nifty-gui/nifty-gui)：Nifty GUI是一个Java库，支持为游戏或类似应用程序构建交互式用户界面。
* [GLN](https://github.com/kotlin-graphics/gln)：OpenGL的包装器，旨在通过使GL代码紧凑、更简单和类型安全来改善开发体验。
* [GLM](https://github.com/kotlin-graphics/glm)：GLM是OpenGL Mathematics的Kotlin端口。
* [OverrunGL](https://github.com/Over-Run/overrungl)：Overrun Game Library是一个用Java 24实现的高性能库，它支持跨平台访问一组C库绑定，提供各种有用的实用程序。
* [Three Kt](https://github.com/markaren/three.kt)：流行的Three.js 3D库的Kotlin/JVM端口。
* [Korender](https://github.com/zakgof/korender)：Kotlin基于OpenGL/OpenGL ES/WebGL的多平台3D图形渲染引擎。
* [Matplot3D](https://github.com/tanling8334/Matplot3D-for-Java)：Matplot3D旨在为Java开发者提供类似于Python中Matplotlib的三维绘图功能。
* [JGLM](https://github.com/jroyalty/jglm)：OpenGL Mathematics C++库(GLM)的概念性移植。
* [GLM](https://github.com/java-graphics/glm)：GLM是OpenGL Mathematics(GLM)的Java端口，它是一个基于OpenGL着色语言(GLSL)规范的图形软件数学库。
* [Kgl](https://github.com/gergelydaniel/kgl)：Kotlin Multiplatform的轻量级OpenGL抽象。
* [Marlin](https://github.com/bourgesl/marlin-renderer)：Marlin是一个开源Java 2D渲染引擎，基于OpenJDK的Pisces实现，针对性能进行了优化(改进了内存使用和占用空间、更好的多线程)和更好的视觉质量。
* [Oreon](https://github.com/fynnfluegge/oreon-engine)：OpenGL/Vulkan Java 3D引擎。
* [ModernUI](https://github.com/BloCamLimb/ModernUI)：Modern UI是一个专为独立2D和3D渲染软件开发而设计的桌面应用程序框架。
* [Scenery](https://github.com/scenerygraphics/scenery)：Scenery是一个场景绘制和渲染库，它允许你基于网格数据快速创建高质量的3D可视化效果。
* [Grafx](https://grafx.sourceforge.net/)：Grafx是一个开源Java库，用于使用浮点端点坐标绘制线条和填充多边形。
* [JRender](https://github.com/nbrugger-tgm/JRender)：JRender是一个完全用Java完成的3D PBR引擎。
* [ClearVolume](https://github.com/ClearVolume/clearvolume)：ClearVolume是一个实时3D可视化库，专为SPIM和DLSM显微镜等高端体积显微镜而设计，由马克斯普朗克分子细胞生物学和遗传学研究所开源。
* [Vulkan4j](https://github.com/club-doki7/vulkan4j)：Vulkan4j是一系列针对Java的图形和相关API绑定，使用Java 22 Panama API实现。
* [Box2DLights](https://github.com/libgdx/box2dlights)：Box2DLights是一个2D光照框架，它使用Box2D进行光线投射，并使用OpenGL ES 2.0进行渲染。
* [JGLFW](https://github.com/badlogic/jglfw)：JGLFW是一个跨平台GLFW包装器。
* [JRender](https://github.com/JordyH297/JRender)：JRender是一个完全原生的Java 3D图形引擎，从头开始构建，没有外部依赖。
* [Dayflower](https://github.com/macroing/Dayflower)：Dayflower是一个用于Java渲染的应用程序和库。
* [Aventura](https://github.com/obarry/Aventura)：Aventura是一个完全用Java编写的轻量级3D渲染引擎，不依赖硬件加速，可以嵌入到任何Java应用中。
* [SkijaGraphics2D](https://github.com/jfree/skijagraphics2d)：SkijaGraphics2D是Java2D API的一个实现，通过Skija绑定针对Skia。

#### 游戏开发库

* [GDX AI](https://github.com/libgdx/gdx-ai)：GDX AI是一个高性能框架，提供游戏行业使用的一些最常见的AI技术。
* [Tiled](https://github.com/mapeditor/tiled)：Tiled是一款通用的图块地图编辑器，适用于所有基于图块的游戏，例如角色扮演游戏、平台游戏或Breakout克隆游戏。
* [PlayN](https://github.com/playn/playn)：PlayN是一个用Java编写的跨平台Java游戏开发库，面向HTML5浏览器、桌面JVM、Android和iOS设备。
* [Zircon](https://github.com/Hexworks/zircon)：Zircon是一个可扩展且用户友好的多平台图块引擎。
* [Raylib-J](https://github.com/CreedVI/Raylib-J)：Raylib-J是Raylib在Java中的手写绑定。
* [Recast4j](https://github.com/ppiastucki/recast4j)：Recast和Detour导航网格工具集的Java端口。
* [Slick2D](https://slick.ninjacave.com/)：Slick2D是一组易于使用的工具和实用程序，围绕LWJGL、OpenGL绑定，使2D Java游戏开发变得更加容易。
* [Discord Game SDK4j](https://github.com/JnCrMx/discord-game-sdk4j)：该项目为Discord GameSDK提供Java绑定。
* [Discord RPC](https://github.com/Vatuu/discord-rpc)：Discord RPC库的Java包装器。
* [JInput](https://github.com/jinput/jinput)：用于访问输入设备的库，由Sun公司游戏技术小组发起。
* [Mixite](https://github.com/Hexworks/mixite)：Mixite是一个六边形网格库，提供一个优化、简单且易用的六边形网格绘制库，而无需依赖任何GUI框架。
* [SquidLib](https://github.com/yellowstonegames/SquidLib)：SquidLib是一个功能非常齐全的库，部分目标是制作传统Roguelike和类似类型的游戏。
* [Game](https://github.com/pacampbell/Game)：用于Java 2D游戏编程的类集合。
* [SGL](https://github.com/regb/scala-game-library)：SGL是一个使用Scala开发跨平台2D视频游戏的库。
* [Chesslib](https://github.com/bhlangonijr/chesslib)：Chesslib是一个简单的Java国际象棋库，用于根据棋盘位置生成合法的国际象棋走法、解析以PGN或FEN格式存储的国际象棋游戏以及许多其他内容。
* [JBT](https://github.com/gaia-ucm/jbt)：JBT是一个用于构建和运行行为树的Java框架。
* [Clyde](https://github.com/threerings/clyde)：Clyde库提供了各种用于创建动作导向的联网3D游戏的工具。
* [Smallville](https://github.com/nickm980/smallville)：电子游戏的生成代理。
* [Jamepad](https://github.com/williamahartman/Jamepad)：Jamepad是一个用于使用Java游戏手柄的库。

#### 碰撞检测

* [ODE4j](https://github.com/tzaeschke/ode4j)：ODE是一个用于模拟刚体动力学的开源高性能库。
* [Dyn4j](https://github.com/dyn4j/dyn4j)：纯Java 2D碰撞检测和物理引擎，旨在快速、稳定、可扩展且易于使用。
* [Phys2D](https://code.google.com/archive/p/phys2d/)：Phys2D是一个Java的2D物理库。
* [JBullet](http://jbullet.advel.cz/)：JBullet是Bullet物理库的Java端口。
* [Minie](https://github.com/stephengold/Minie)：Minie项目旨在改进Bullet实时物理模拟和Khaled Mamou的V-HACD库与jMonkeyEngine游戏引擎的集成。
* [Bullet](https://github.com/kotlin-graphics/bullet)：JVM Bullet物理SDK：用于VR、游戏、视觉效果、机器人、机器学习等的实时碰撞检测和多物理模拟。
* [Libbulletjme](https://github.com/stephengold/Libbulletjme)：BulletPhysics和V-HACD的JNI接口。
* [Jolt JNI](https://github.com/stephengold/jolt-jni)：Jolt JNI项目为Jolt Physics和V-HACD库提供JVM绑定，以促进使用Java和Kotlin等JVM语言进行物理模拟。
* [JBump](https://github.com/implicit-invocation/jbump)：JBump是Bump.Lua的Java端口，它是一个2D AABB碰撞检测和响应库。

#### 寻路算法

* [Baritone](https://github.com/cabaletta/baritone)：Baritone是Impact从4.4版本开始使用的寻路系统。
* [Pathetic](https://github.com/bsommerfeld/pathetic)：Pathetic是一个高度可配置的Java A*寻路库，旨在通过自定义节点验证和成本处理实现可扩展性。
* [Recast4j](https://github.com/recast4j/recast4j)：Recast和Detour导航网格工具集的Java端口。
* [Pathfinding](https://github.com/xaguzman/pathfinding)：一个用于游戏的Java寻路库。
* [Tektosyne](https://github.com/kynosarges/tektosyne)：Tektosyne库提供了计算几何和基于图形的寻路算法，以及支持数学实用程序和专门的集合。

#### 实体框架

* [Artemis ODB](https://github.com/junkdog/artemis-odb)：Artemis ODB是一个基于Java的高性能实体组件系统框架。
* [Ashley](https://github.com/libgdx/ashley)：Ashley是一个用Java编写的小型实体框架，它的灵感来自于Ash和Artemis等框架。
* [Dominion](https://github.com/dominion-dev/dominion-ecs-java)：Dominion是Java的一个实体组件系统库。
* [Zay ES](https://github.com/jMonkeyEngine-Contributions/zay-es)：Zay ES是一个基于Java的高性能实体组件系统。
* [Fleks](https://github.com/Quillraven/Fleks)：用Kotlin编写的快速、轻量级实体组件系统库。
* [Geary](https://github.com/MineInAbyss/geary)：Geary是一个用Kotlin编写的实体组件系统。

#### 游戏编辑器

* [Spine](https://github.com/EsotericSoftware/spine-runtimes)：Spine是一款针对游戏开发的2D骨骼动画编辑工具，旨在提供更高效和简洁的工作流程，以创建游戏所需的动画。
* [HyperLap2D](https://github.com/rednblackgames/HyperLap2D)：HyperLap2D是一个功能强大、独立于平台的可视化编辑器，适用于复杂的2D世界和场景。
* [Overlap2D](https://github.com/UnderwaterApps/overlap2d)：Overlap2D是一款2D关卡和UI编辑器，具有与引擎无关的游戏开发理念。
* [Bladecoder Adventure](https://github.com/bladecoder/bladecoder-adventure-engine)：Bladecoder Adventure引擎是一组用于创建交互式图形冒险(经典点击游戏)的工具。
* [Talos](https://github.com/rockbite/talos)：基于节点的开源VFX编辑器，具有强大的界面和随时可用的LibGDX运行时。
* [Moon](https://github.com/damn/moon)：Moon是一款开源的动作角色扮演游戏制作器。
* [RPGBoss](https://github.com/rpgboss/rpgboss)：点击式角色扮演游戏编辑器和引擎。
* [Mundus](https://github.com/mbrlabs/Mundus)：Mundus是一个独立于平台的3D世界编辑器，采用Java、Kotlin以及LibGDX、VisUI构建。

#### 开源游戏

* [Unciv](https://github.com/yairm210/Unciv)：Civ V的开源、注重可修改性的Android和桌面重制版，使用LibGDX制作。
* [BGBlitz](https://www.bgblitz.com/)：BGBlitz是一款专门用于玩西洋双陆棋的计算机程序。
* [Mindustry](https://github.com/Anuken/Mindustry)：Mindustry是一款2D游戏，其玩法融合塔防、工厂自动化、沙盒与即时战略。
* [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon)：Shattered Pixel Dungeon是一款传统的Roguelike地下城探索角色扮演游戏。
* [Pixel Dungeon](https://github.com/watabou/pixel-dungeon)：Pixel Dungeon是一款传统的Roguelike游戏，具有像素艺术图形和简单的界面，适用于Android、iOS、Windows、Mac和Linux。
* [Riiablo](https://github.com/collinsmith/riiablo)：用Java和LibGDX重制《暗黑破坏神II》。
* [ByteLegend](https://github.com/ByteLegend/ByteLegend)：ByteLegend是一款免费、开源的MMORPG游戏，你可以在其中获得现实世界的高薪编程技能。
* [OpenKeeper](https://github.com/tonihele/OpenKeeper)：OpenKeeper是地下城守护者II游戏和引擎的开源重制版。

#### 象棋引擎

* [BlackWidow](https://github.com/amir650/BlackWidow-Chess)：BlackWidow是一个跨平台的象棋引擎。
* [Public Xiangqi](https://github.com/sojourners/public-Xiangqi)：支持UCI和UCCI协议引擎的象棋界面程序，具有加载引擎、对弈、分析、连线、开局库等功能。
* [JFXChess](https://github.com/asdfjkl/jfxchess)：JFXChess是一个跨平台的国际象棋图形用户界面。
* [Bagatur](https://github.com/bagaturchess/Bagatur)：Bagatur是世界上最强大的Java国际象棋引擎之一。

#### 游戏开发工具

* [Live2D](https://www.live2d.com/)：Live2D是一种应用于电子游戏的绘图渲染技术，由日本Cybernoids公司开发。
* [Lizzie](https://github.com/featurecat/lizzie)：Lizzie是一个图形界面，允许用户使用Leela Zero实时分析游戏。
* [ArkPets](https://github.com/isHarryh/Ark-Pets)：ArkPets是基于Java的针对游戏《明日方舟》开发的非营利性的桌宠软件。
* [DisUnity](https://github.com/ata4/disunity)：用Java编写的Unity资源和资源包文件的实验性命令行工具集，主要用于提取。
* [TabletopGames](https://github.com/GAIGResearch/TabletopGames)：TabletopGames是一个基于Java的基准测试，用于开发现代AI研究桌游。
* [Alice](https://github.com/TheAliceProject/alice3)：Alice是一个基于块的创新编程环境，可以轻松创建动画、构建交互式叙述或以3D方式编写简单游戏，由CMU开源。
* [PCGen](https://github.com/PCGen/pcgen)：PCGen是一个用于在D&D等纸笔游戏中创建和管理玩家角色的程序。

#### 虚拟现实

* [jMonkeyVR](https://github.com/phr00t/jMonkeyVR)：简单、免费且通用的VR开发解决方案。
* [OpenVR](https://github.com/kotlin-graphics/openvr)：OpenVR的Kotlin包装器。

## JVM代理

* [BlockHound](https://github.com/reactor/BlockHound)：用于检测来自非阻塞线程的阻塞调用的Java代理。
* [One Java Agent](https://github.com/alibaba/one-java-agent)：One Java Agent提供插件化支持，统一管理众多的Java Agent，由阿里开源。
* [DongTai Agent Java](https://github.com/HXSecurity/DongTai-agent-java)：DongTai Agent是针对Java应用程序的数据采集工具，由火线安全开源。
* [RR4J](https://github.com/Kartikvk1996/RR4J)：RR4J是一个记录Java字节码执行情况并允许开发人员在本地重放的工具。
* [FlowTracker](https://github.com/coekie/flowtracker)：FlowTracker是一个Java代理，用于跟踪程序如何读取、操作和写入数据。
* [Zorka](https://github.com/jitlogic/zorka)：Zorka是一个用于Java应用程序的可编程通用监控代理。
* [Disco](https://github.com/awslabs/disco)：Disco包括用于创建Java代理的框架，用于分布式系统的面向切面的工具，由AWS开源。
* [JVMQuake](https://github.com/Netflix-Skunkworks/jvmquake)：一个JVMTI代理，它附加到你的JVM，并在程序变得不稳定时自动发出信号并终止它，由Netflix开源。
* [Java Debug Tool](https://github.com/pandening/Java-debug-tool)：Java Debug Tool是一个动态调试工具，它提供了一些调试命令来在运行时调试你的代码。
* [inspectIT Ocelot](https://github.com/inspectIT/inspectit-ocelot)：inspectIT Ocelot是一个零配置Java代理，用于基于OpenCensus库动态收集应用程序性能、跟踪和行为数据。
* [LinkAgent](https://github.com/shulieTech/LinkAgent)：LinkAgent是一个基于Java的开源代理，旨在通过JVM字节码收集Java应用程序的数据和控制功能，而无需修改应用程序代码。
* [File Leak Detector](https://github.com/jenkinsci/lib-file-leak-detector)：File Leak Detector是一个小型Java代理，可以跟踪在JVM中打开文件的位置/时间/人员。
* [EA Agent Loader](https://github.com/electronicarts/ea-agent-loader)：EA Agent Loader是一套面向Java Agent开发者的实用工具，由艺电开源。
* [JVMKill](https://github.com/airlift/jvmkill)：JVMKill是一个简单的JVMTI代理，当JVM无法分配内存或创建线程时，它会强制终止JVM。
* [Invesdwin Instrument](https://github.com/invesdwin/invesdwin-instrument)：这是一个检测Java代理，能够将自身加载到正在运行的JVM中。

## 热加载

* [JRebel](http://zeroturnaround.com/software/jrebel/)：JRebel是一款JVM插件，它使得Java代码修改后不用重启系统，立即生效。
* [Spring Loaded](https://github.com/spring-projects/spring-loaded)：Spring Loaded是一个JVM代理，用于在JVM运行时重新加载class文件更改。
* [Hotswap Agent](https://github.com/HotswapProjects/HotswapAgent)：Java无限运行时类和资源重定义。
* [Fakereplace](https://github.com/fakereplace/fakereplace)：该项目提供了一个JavaAgent和一个客户端，用于在标准JDK热交换提供的基础上热替换JVM中的类。
* [RelProxy](https://github.com/jmarranz/relproxy)：RelProxy是一个简单的Java和Groovy热类重加载器，提供透明的动态编译和类重新加载，以及纯Java代码的脚本支持和Shell。
* [HotSeconds](https://github.com/Liubsyy/HotSecondsIDEA)：HotSeconds是一款Java远程热部署的插件。

## 类加载

* [SOFAArk](https://github.com/sofastack/sofa-ark)：SOFAArk是一款基于Java实现的动态热部署和轻量级类隔离框架，由蚂蚁集团开源贡献，主要提供应用模块的动态热部署和类隔离能力。
* [Pandora](https://www.infoq.cn/article/kgxytjb2cr7hgukmjg0p)：Pandora是由淘宝团队打造的基于隔离技术而构建出的新一代的隔离容器
* [JCL](https://github.com/kamranzafar/JCL)：JCL是一个可配置、动态且可扩展的自定义类加载器，可以直接从Jar文件和其他源加载Java类。
* [Nicobar](https://github.com/Netflix/Nicobar)：Nicobar是一个Java动态脚本框架，由基于JBoss Modules的强大模块加载系统驱动，Netflix开源。
* [Java Dynamic Load Jar](https://github.com/Trinea/java-dynamic-load-jar)：解决在不同JAR中加载相同类时的类加载器隔离问题。
* [ModRun](https://github.com/nanosai/modrun)：ModRun可以直接从Maven仓库加载和运行类，并在运行时解决依赖关系。
* [Land](https://github.com/oldratlee/land)：Land是一个通过类加载器实现的简单Java依赖隔离容器。
* [JuShaTa](https://github.com/didi/JuShaTa)：JuShaTa是一个Java容器，提供模块隔离及模块热加载能力，由滴滴开源。
* [JBoss Modules](https://github.com/jboss-modules/jboss-modules)：JBoss Modules是Java模块化(非分层)类加载和执行环境的独立实现。
* [Classloader Leak Prevention](https://github.com/mjiderhamn/classloader-leak-prevention)：类加载器泄漏预防库。
* [Plexus Classworlds](https://github.com/codehaus-plexus/plexus-classworlds)：Plexus Classworlds是一个为需要复杂操作Java类加载器的容器开发人员提供的框架。
* [Cytodynamics](https://github.com/linkedin/Cytodynamics)：Cytodynamics是一个使JVM上的动态JAR加载和类加载器隔离变得简单的Java库，由LinkedIn开源。
* [XJar](https://github.com/core-lib/xjar)：Spring Boot JAR安全加密运行工具，同时支持的原生JAR。
* [Sonar Classloader](https://github.com/SonarSource/sonar-classloader)：Sonar Classloader是一个用于创建Java 7+类加载器的工具箱。
* [Grab’n Run](https://github.com/lukeFalsina/Grab-n-Run)：Grab‘n Run是一个简单且高效的Java库，通过标准DexClassLoader执行安全的动态类加载。

## 芯片模拟器

* [Chisel](https://github.com/chipsalliance/chisel)：Chisel是一种开源硬件描述语言(HDL)，用于在寄存器传输级别描述数字电子设备和电路，从而促进ASIC和FPGA数字逻辑的高级电路生成和设计重用设计，由伯克利大学开源。
* [XiangShan](https://github.com/OpenXiangShan/XiangShan)：XiangShan是一款开源的高性能RISC-V处理器，中国科学院计算技术研究所开发。
* [RISC-V BOOM](https://github.com/riscv-boom/riscv-boom)：BOOM是一个可综合且可参数化的开源RV64GC RISC-V内核，采用Chisel硬件构造语言编写，由加州大学伯克利分校开源。
* [RARS](https://github.com/TheThirdOne/rars)：RISC-V汇编器和运行时模拟器。
* [Sedna](https://github.com/fnuecke/sedna)：Sedna是一个用Java编写的64位RISC-V模拟器，它实现了被视为“通用”所需的所有扩展以及管理模式，这意味着它可以引导Linux。
* [NutShell](https://github.com/OSCPU/NutShell)：NutShell是由OSCPU(大学开源芯片项目)团队开发的处理器。
* [Ventus GPGPU](https://github.com/THU-DSP-LAB/ventus-gpgpu)：支持RISCV-V扩展的GPGPU处理器，使用Chisel HDL开发，由清华大学开源。
* [FireSim](https://github.com/firesim/firesim)：FireSim是一款开源FPGA加速的全系统硬件仿真平台，可以轻松验证、分析和调试10到100 MHz的RTL硬件实现，由加州大学伯克利分校的电气工程和计算机科学系开发。
* [Venus](https://github.com/kvakil/venus)：Venus是一款专为教育打造的RISC-V指令集模拟器。
* [OpenCar](https://github.com/anons-org/opencar)：OpenCar是一款仿真RISC-V指令集的软件，目标是提供基础的RV指令模拟环境。
* [ARMStrong](https://github.com/linouxis9/ARMStrong)：专为教育而设计的快速、简单的ARM模拟器。
* [Symon](https://github.com/sethm/symon)：Symon是基于MOS Technologies 6502微处理器及其兼容系统的通用模拟器。
* [Neptune](https://github.com/LPC4/Neptune-32)：Neptune是一款定制的32位CPU模拟器，集成了汇编器和汇编语言。

## MIPS

* [EduMIPS64](https://github.com/EduMIPS64/edumips64)：EduMIPS64是一个用Java编写的免费跨平台可视化MIPS64 CPU模拟器，由卡塔尼亚大学开源。
* [MARS](https://github.com/dpetersanderson/MARS)：MARS是一个轻量级交互式IDE，用于使用MIPS汇编语言进行编程，旨在与Patterson和Hennessy的计算机组织和设计一起用于教育级别，由密苏里州立大学。
* [Simulizer](https://github.com/Simulizer/Simulizer)：Simulizer允许你编写汇编代码并在模拟和可视化的CPU上运行它。

## 汇编

* [Jasmin](https://github.com/Sable/jasmin)：Jasmin是一个Java汇编器接口，由麦吉尔大学开源。
* [Iced](https://github.com/icedland/iced)：适用于Rust、.NET、Java、Python、Lua的快速且正确的x86/x64反汇编器、汇编器、解码器、编码器。
* [Smali](https://github.com/JesusFreke/smali)：Smali是Dalvik使用的dex格式的汇编器/反汇编器。
* [Krakatau](https://github.com/Storyyeller/Krakatau)：Krakatau提供了Java字节码的汇编器和反汇编器，它允许你将二进制class文件转换为人类可读的文本格式，进行更改，然后将其转换回class文件，甚至对于混淆的代码也是如此。
* [JASM](https://github.com/roscopeco/jasm)：现代JVM汇编器。
* [Java Grinder](https://github.com/mikeakohn/java_grinder)：将Java字节码编译为微控制器程序集。
* [Jasm](https://github.com/jumanji144/Jasm)：Jasm是Java和Dalvik汇编程序套件。
* [Jasmin](https://github.com/TUM-LRR/Jasmin)：Jasmin是一款面向学生的x86汇编语言学习工具，由慕尼黑工业大学开源。
* [FFmasm](https://github.com/YaSuenag/ffmasm)：FFmasm是一个用于从Java手工组装的汇编器。

## LLVM

* [Sulong](https://github.com/graalvm/sulong)：Sulong是Oracle实验室基于GraalVM构建的高性能LLVM位码运行时。
* [JLang](https://github.com/polyglot-compiler/JLang)：JLang向Polyglot编译器添加了LLVM后端，将Java转换为LLVM IR，由康奈尔大学开源。
* [LLJVM](https://github.com/davidar/lljvm)：LLJVM提供了一组工具和库，用于在JVM上运行相对较低级别的语言(例如C)。
* [LLFI](https://github.com/DependableSystemsLab/LLFI)：LLFI是一个基于LLVM的故障注入工具，它将故障注入到应用程序源代码的LLVM IR中，由不列颠哥伦比亚大学开源。
* [Jeandle](https://github.com/jeandle/jeandle-jdk)：Jeandle是一个Java的JIT，利用LLVM编译器基础架构生成机器码，旨在提供强大的编译优化并交付高性能代码，由蚂蚁开源。

## PC模拟器

* [JPC](https://github.com/ianopolous/JPC)：JPC是一款快速的现代x86 PC模拟器，能够启动Windows直至Windows 95(以及安全模式下的Windows 98)和一些图形Linux，由牛津大学开源。
* [MTMC](https://github.com/msu/mtmc)：MTMC是一台虚拟计算机，旨在以有趣和直观的方式展示数字计算的工作原理，由蒙大拿州立大学开源。
* [Triton-64](https://github.com/LPC4/Triton-64)：完整的64位虚拟机实现，具有自定义CPU架构、汇编器、编译器和使用JavaFX用Java构建的开发环境。
* [Bcomp](https://github.com/tune-it/bcomp)：Bcomp是ITMO大学一年级学生学习的简单计算机模型，由圣彼得堡国立信息技术、机械与光学研究型大学开源。
* [z390](https://github.com/z390development/z390)：z390大型机汇编程序模拟器和运行时引擎。
* [JC64](https://github.com/ice00/jc64)：JC64是一款使用Java语言尝试100%模拟C64的模拟器。

## JavaME

* [MicroEmu](https://code.google.com/archive/p/microemu/)：MicroEmu是Java ME的纯Java实现。
* [J2ME-Loader](https://github.com/nikita36078/J2ME-Loader)：J2ME-Loader是适用于Android的J2ME模拟器，它支持大多数2D和3D游戏(包括Mascot Capsule 3D游戏)。
* [SquirrelJME](https://github.com/SquirrelJME/SquirrelJME)：SquirrelJME是用于嵌入式和物联网设备的Java ME 8虚拟机，它的最终目标是与Java ME标准99.9%兼容。
* [FreeJ2ME](https://github.com/hex007/freej2me)：包含Libretro、AWT和SDL2前端的免费J2ME模拟器。
* [PluotSorbet](https://github.com/mozilla/pluotsorbet)：PluotSorbet是一个用JavaScript编写的兼容J2ME的虚拟机，由Mozilla开源。
* [KEmulator](https://github.com/shinovon/KEmulator)：跨平台J2ME模拟器，基于反编译的KEmulator 1.0.3。
* [J2ME Polish](https://github.com/Enough-Software/j2mepolish)：J2ME Polish是一个框架，开发人员可以从单一源基础在J2ME、Blackberry和Android设备上创建应用程序。
* [Cibyl](https://github.com/SimonKagstrom/cibyl)：Cibyl是一个在J2ME手机上编译和运行用C、 Objective-C、C++以及可能的Fortran编写的程序的环境。
* [FreeJ2ME Plus](https://github.com/TASEmulators/freej2me-plus)：FreeJ2ME Plus是一个带有libretro和AWT前端的J2ME模拟器，它旨在运行在任何可以运行Java VM的东西上。
* [JL Mod](https://github.com/woesss/JL-Mod)：J2ME Loader的非官方分支。
* [JS2ME](https://github.com/szatkus/js2me)：JS2ME是Firefox OS中Java ME的JavaScript实现。
* [OpenTTY](https://github.com/mrlima4095/OpenTTY-J2ME)：OpenTTY是一种先进的终端仿真器，设计用于在J2ME设备上运行，提供针对复古和低资源环境量身定制的类似Unix的Shell体验。

## 编译器

* [Polyglot](https://github.com/polyglot-compiler/polyglot)：Polyglot是Java编程语言的高度可扩展的编译器前端，由康奈尔大学开源。
* [Jikes](https://jikes.sourceforge.net/)：Jikes是一个编译器，它将Java语言规范中定义的Java源文件转换为Java虚拟机规范中定义的字节码指令集和二进制格式，由IBM开源。
* [OpenLDK](https://github.com/atgreen/openldk)：OpenLDK是Java的JIT编译器和运行时环境，完全以Common Lisp实现。
* [RubyFlux](https://github.com/headius/rubyflux)：RubyFlux是一个编译器，它将Ruby代码库转换为一组封闭的.java源文件，适合在任何JVM上运行，无需额外的运行时要求。
* [MateVM](https://github.com/MateVM/MateVM)：MateVM是一个用Haskell编写的Java JIT编译器。
* [Apache Royale Compiler](https://github.com/apache/royale-compiler)：Royale编译器将ActionScript 3.0和MXML代码编译为SWF或JavaScript。
* [JLLVM](https://github.com/JLLVM/JLLVM)：JLLVM是一个无需解释器的按需JIT编译JVM，由维也纳工业大学开源。
* [BIT Mini C](https://github.com/jiweixing/BIT-MiniCC)：BIT Mini C编译器是一个用于教学的Java C编译框架，由北京理工大学开源。

#### 内存中编译器

* [Janin](https://github.com/janino-compiler/janino)：Janino是一个超小、超快的Java编译器。
* [Chronicle Runtime Compiler](https://github.com/OpenHFT/Java-Runtime-Compiler)：Chronicle Runtime Compiler是一个Java运行时编译器。
* [Apache Commons JCI](https://github.com/apache/commons-jci)：Commons JCI是一个Java编译器接口，它可用于编译Java本身，或任何其他可编译为Java类的语言(例如Groovy或JavaScript)。
* [InMemoryJavaCompiler](https://github.com/trung/InMemoryJavaCompiler)：在内存中编译Java源代码的实用程序类。
* [Compiler](https://github.com/michaelliao/compiler)：使用Java 6编译器API在内存中编译Java代码。
* [SourceBuddy](https://github.com/sourcebuddy/sourcebuddy)：SourceBuddy是一个Java库，可用于在程序中编译和加载动态生成的Java源代码。
* [Jeed](https://github.com/cs125-illinois/jeed)：Jeed是一个快速的Java和Kotlin内存编译和执行工具包，由伊利诺伊大学开源。
* [Dynamic Loader Utility](https://github.com/wb04307201/dynamic-loader-utility)：Dynamic Loader Utility是一个用于动态加载和管理Java类的工具库，支持动态编译、AOP代理和Spring Bean管理功能。

#### AOT编译器

* [GraalVM](https://github.com/oracle/graal)：GraalVM将Java应用程序编译为本机可执行文件，可立即启动、快速扩展并使用更少的计算资源，由Oracle开源。
* [RoboVM](https://github.com/MobiVM/robovm)：RoboVM是Java字节码的提前编译器，针对Linux、Mac OS X和iOS，由Xamarin维护。
* [TeaVM](https://github.com/konsoletyper/teavm)：TeaVM是Java字节码的提前编译器，可生成在浏览器中运行的JavaScript和WebAssembly。
* [JTransc](https://github.com/soywiz-archive/jtransc)：JTransc是一个AOT编译器，它将.class和.jar文件编译为目标编程语言/可执行文件，将所有必需的依赖项捆绑在单个文件或文件夹中，无需抖动或外部运行时。
* [Excelsior JET](https://github.com/excelsior-oss/excelsior-jet-maven-plugin)：Excelsior JET是一款带有AOT的Java虚拟机增强工具。
* [BugVM](https://github.com/ibinti/bugvm)：BugVM使用独立的JVM将字节码编译为二进制代码。
* [Qbicc](https://github.com/qbicc/qbicc)：Qbicc是一个实验性的Java原生镜像编译器，由RedHat开源。

#### 编译器插件

* [Java-OO](https://github.com/amelentev/java-oo)：Java-OO是Java编译器和IDE的模块化扩展，用于支持运算符重载(类似Scala)。
* [Manifold](https://github.com/manifold-systems/manifold)：Manifold是一个Java编译器插件，其功能包括元编程、属性、扩展方法、运算符重载、模板、预处理器等。
* [Deptitive](https://github.com/moditect/deptective)：Deptitive是javac的一个插件，它根据允许的依赖的描述来验证项目包之间的依赖关系，并在检测到任何无意的依赖关系时使编译失败。
* [Turbine](https://github.com/google/turbine)：Turbine是Java的标头编译器，Google开发。

## 语言服务器

* [JDT Language Server](https://github.com/eclipse-jdtls/eclipse.jdt.ls)：JDT语言服务器是语言服务器协议的Java语言特定实现，可以与支持该协议的任何编辑器一起使用，为Java语言提供良好的支持。
* [Eclipse LSP4J](https://github.com/eclipse-lsp4j/lsp4j)：语言服务器协议的Java实现，旨在由用Java实现的工具和语言服务器使用。
* [Kotlin LSP](https://github.com/Kotlin/kotlin-lsp)：Kotlin语言服务器和Visual Studio Code插件，由JetBrains开发。
* [Language Server](https://github.com/georgewfraser/java-language-server)：基于协议v3.0并使用Java编译器API实现的Java语言服务器。
* [Eclipse LemMinX](https://github.com/eclipse/lemminx)：语言服务器协议的XML语言特定实现，可以与支持该协议的任何编辑器一起使用，为XML语言提供良好的支持。
* [Groovy Language Server](https://github.com/GroovyLanguageServer/groovy-language-server)：Groovy的语言服务器。
* [Lsp4IntelliJ](https://github.com/ballerina-platform/lsp4intellij)：Lsp4IntelliJ是一个客户端库，为IntelliJ IDEA和其他Jetbrains IDE提供语言服务器支持。
* [Build Server Protocol](https://github.com/build-server-protocol/build-server-protocol)：该项目致力于改进语言服务器/编辑器和构建工具之间的集成，由Scala中心和JetBrains领导。
* [BSL Language Server](https://github.com/1c-syntax/bsl-language-server)：BSL语言服务器协议的实现。
* [Meghanada Server](https://github.com/mopemope/meghanada-server)：适用于你的编辑器的Java IDE服务器，为你最喜欢的文本编辑器提供类似Java IDE的功能。

## 元编程

* [Eclipse Xtext](https://github.com/eclipse/xtext)：Xtext是一个用于开发编程语言和特定领域语言的框架。
* [MPS](https://github.com/JetBrains/MPS)：JetBrains元编程系统。
* [GenSym](https://github.com/Generative-Program-Analysis/GenSym)：GenSym是LLVM IR的高性能并行符号执行引擎。
* [Rascal](https://github.com/usethesource/rascal)：Rascal是一个开源、基于Java的元编程库，由荷兰阿姆斯特丹自由大学的UseTheSource团队开发。
* [Procyon](https://github.com/mstrobel/procyon)：Procyon是一套专注于代码生成和分析的Java元编程工具。
* [JNI Bind](https://github.com/google/jni-bind)：JNI Bind是一个新的元编程库，为C++ => Java/Kotlin提供语法糖，Google开源。
* [JBSE](https://github.com/pietrobraione/jbse)：JBSE是一个用于自动程序分析、验证和测试生成的符号Java虚拟机。
* [Symbolic Java PathFinder](https://github.com/SymbolicPathFinder/jpf-symbc)：此JPF扩展为Java字节码提供符号执行，由NASA开源。
* [Ideal](https://github.com/dynin/ideal)：实验性元编程框架。

## 对象存储

* [Aliyun OSS](https://github.com/aliyun/aliyun-oss-java-sdk)：Aliyun OSS Java SDK让Java开发者能够轻松使用阿里云OSS。
* [Java Storage](https://github.com/googleapis/java-storage)：Google Cloud Storage的Java惯用客户端。
* [Ambry](https://github.com/linkedin/ambry)：Ambry是一个分布式对象存储，支持存储数万亿个小型不可变对象(50K-100K)以及数十亿个大型对象，由LinkedIn开发。
* [S3Proxy](https://github.com/gaul/s3proxy)：S3Proxy实现S3 API和代理请求，支持多种用例。
* [MinIO](https://github.com/minio/minio-java)：MinIO Java SDK是S3客户端，用于对任何与Amazon S3兼容的对象存储服务执行存储桶和对象操作。
* [MinIO Plus](https://gitee.com/lxp135/minio-plus)：MinIO Plus是一个MinIO的二次封装与增强工具。
* [X File Storage](https://gitee.com/dromara/x-file-storage)：X File Storage允许使用一行代码将文件存储到本地、FTP、SFTP、WebDAV以及各种云对象存储服务。
* [OSS Spring Boot](https://github.com/pig-mesh/oss-spring-boot-starter)：兼容S3协议的通用文件存储工具类。
* [Syncany](https://github.com/syncany/syncany)：Syncany是一款云存储和文件共享应用程序，重点关注存储的安全性和抽象性。
* [Qiniu Resource Storage SDK](https://github.com/qiniu/java-sdk)：七牛资源存储Java SDK。
* [KSAN](https://github.com/infinistor/ksan)：KSAN是一个软件定义的对象存储系统，旨在可靠、高效地提供大规模对象存储服务。
* [Huawei OBS](https://github.com/huaweicloud/huaweicloud-sdk-java-obs)：用于访问华为对象存储服务的OBS Java SDK。
* [BlobIt](https://github.com/diennea/blobit)：BlobIt是基于Apache BookKeeper构建的分布式二进制大对象(BLOB)存储。
* [ByteBin](https://github.com/lucko/bytebin)：ByteBin是一种快速、轻量级的内容存储网络服务。
* [Dante OSS](https://gitee.com/herodotus/dante-oss)：Dante OSS是一款简化对象存储操作的开源框架。
* [UPYUN Java SDK](https://github.com/upyun/java-sdk)：又拍云存储Java SDK。
* [Pithos](https://github.com/exoscale/pithos)：Pithos是一个与S3兼容的对象存储，利用Cassandra水平分发内容。

## 文件系统

* [HDFS](https://github.com/apache/hadoop)：Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Hops](https://github.com/hopshadoop/hops)：Hops是Apache Hadoop的下一代发行版，具有可扩展、高可用和可定制的元数据。
* [Jimfs](https://github.com/google/jimfs)：Jimfs是Java 8及更高版本的内存文件系统，实现了java.nio.file抽象文件系统API，由Google开源。
* [Ruyuan](https://gitee.com/suzhou-mopdila-information/ruyuan-dfs)：本项目是使用Java开发的一个分布式海量小文件存储系统，功能包括文件上传、文件下载、文件存储等。
* [XtreemFS](https://github.com/xtreemfs/xtreemfs)：XtreemFS是一个用于联合IT基础设施的分布式、可复制和容错的文件系统，由柏林自由大学开源。
* [Memory File System](https://github.com/marschall/memoryfilesystem)：用于测试目的的JSR-203文件系统的内存实现。
* [ADFS](https://github.com/taobao/ADFS)：ADFS是Hadoop的演进版本，提供高可用性、自动重启等特性，由阿里开源。
* [TngouFS](https://gitee.com/397713572/tngouFS)：TngouFS是天狗网用于该网站的图片存储。
* [JFileServer](https://github.com/FileSysOrg/jfileserver)：JFileServer是一个基于Java的文件服务器，目前支持SMB/CIFS、FTP/FTPS和NFS协议。
* [Apache Commons VFS](https://github.com/apache/commons-vfs)：Commons VFS是一个虚拟文件系统库。
* [FastDFS Client](https://github.com/happyfish100/fastdfs-client-java)：FastDFS Java客户端SDK。
* [FastDFS Client](https://github.com/tobato/FastDFS_Client)：FastDFS的Java客户端。
* [JNR FUSE](https://github.com/SerCeMan/jnr-fuse)：JNR FUSE是使用Java Native Runtime的Java中的FUSE实现。
* [NFS4J](https://github.com/dCache/nfs4j)：NFS服务器版本3、4.0和4.1的纯Java实现，包括带有nfs4.1-files和flex-files布局类型的pNFS扩展。
* [NFS Java Client](https://github.com/EMCECS/nfs-client-java)：该项目是一个NFS Java客户端，具有一些额外的抽象，允许扩展处理其他NFS版本(目前仅处理NFS v3)，由EMC开源。
* [JavaFS](https://github.com/puniverse/javafs)：Java文件系统，由FUSE提供支持。
* [ParallelGit](https://github.com/pimpcapital/ParallelGit)：适用于Git的高性能Java 7 NIO内存文件系统。
* [Amazon S3 FileSystem NIO2](https://github.com/Upplication/Amazon-S3-FileSystem-NIO2)：适用于Java 7(NIO2)的Amazon AWS S3文件系统提供程序。
* [FUSE Java](https://github.com/EtiennePerot/fuse-jna)：使用JNA的Java FUSE绑定。
* [JSR-203 Hadoop](https://github.com/damiencarol/jsr203-hadoop)：Hadoop分布式文件系统的JSR 203实现。
* [S3FS NIO](https://github.com/carlspring/s3fs-nio)：这是使用Java 8的JSR-203的Amazon AWS S3文件系统提供程序的实现。
* [Hadoop COS](https://github.com/tencentyun/hadoop-cos)：Hadoop COS实现了以腾讯云COS作为底层文件系统运行上层计算任务的功能，支持使用Hadoop、Spark以及Tez等处理存储在腾讯云COS对象存储系统上的数据。
* [Hadoop-20](https://github.com/facebookarchive/hadoop-20)：Facebook基于Hadoop 0.20-append的实时分布式FS。
* [SDFS](https://github.com/opendedup/sdfs)：一种去重文件系统，可以将数据存储在对象存储或块存储中。
* [N5](https://github.com/saalfeldlab/n5)：N5 API指定了存储大块n维张量以及类似于HDF5的组层次中的任意元数据所需的原始操作。
* [Sfs](https://github.com/pitchpoint-solutions/sfs)：PitchPoint开发的传统少云对象存储服务器能够以极小的资源存储存储亿个大小的文件。
* [JSch NIO](https://github.com/lucastheisen/jsch-nio)：JSch NIO尝试利用JSch SSH实现来实现NIO文件系统及其附带的一切。
* [CryptoFS](https://github.com/cryptomator/cryptofs)：CryptoFS是Cryptomator加密工具的底层Java文件系统库。
* [MongoDB File Server](https://github.com/waylau/mongodb-file-server)：MongoDB File Server是一个基于MongoDB的文件服务器系统。

## S3

* [S3Proxy](https://github.com/gaul/s3proxy)：S3Proxy实现S3 API和代理请求，支持多种用例。
* [S3S3Mirror](https://github.com/cobbzilla/s3s3mirror)：一个用于将内容从一个S3桶镜像到另一个桶的工具。
* [S3mper](https://github.com/Netflix/s3mper)：S3mper是一个库，通过使用一致的次级索引，在亚马逊S3索引之上增加了一层一致性检查，由Netflix开源。
* [S3Auth](https://github.com/yegor256/s3auth)：Amazon S3 HTTP基础认证网关。
* [S3 Stream Upload](https://github.com/alexmojaki/s3-stream-upload)：这个库让你能够高效地将大量数据流传输到AWS S3，而无需将整个对象存储在内存中或使用文件。

## 音视频处理

这里包括Java中音频、视频、多媒体相关的库、框架。

#### 音频库

* [RxAndroidAudio](https://github.com/Piasy/RxAndroidAudio)：Android音频封装库，部分Rx支持。
* [Libpd](https://github.com/libpd/libpd)：Pure Data可嵌入音频合成库。
* [Noise](https://github.com/paramsen/noise)：Noise是kissfft的Android包装器，kissfft是一个用C语言编写的FFT实现。
* [MP3agic](https://github.com/mpatric/mp3agic)：用于读取MP3文件和读取/操作ID3标签(ID3v1和ID3v2.2到ID3v2.4)的Java库。
* [TarsosDSP](https://github.com/JorenSix/TarsosDSP)：TarsosDSP是一个用于音频处理的Java库，其目的是为实用的音乐处理算法提供一个易于使用的接口。
* [LavaPlayer](https://github.com/sedmelluq/lavaplayer)：LavaPlayer是一个用Java编写的音频播放器库，它可以从各种源加载音轨并将其转换为Opus帧流，专为Discord机器人使用而设计。
* [Horizon](https://github.com/Yalantis/Horizon)：Horizon是适用于Android的简单视觉均衡器。
* [TinySound](https://github.com/finnkuusisto/TinySound)：TinySound是一个简单的声音系统，它包装了标准的Java声音库。
* [Echoprint Server](https://github.com/spotify/echoprint-server)：Echoprint音频指纹系统服务器，由Spotify开源。
* [Chromaprint.scala](https://github.com/mgdigital/Chromaprint.scala)：Chromaprint音频指纹算法的JVM实现。
* [Beat Link](https://github.com/Deep-Symmetry/beat-link)：用于与Pioneer DJ Link设备同步和通信的Java库。
* [MidiBus](https://github.com/sparks/themidibus)：MidiBus是一个用于处理的MIDI库，它提供了一种快速简便的方法来发送和接收MIDI数据。
* [Android MIDI Library](https://github.com/LeffelMania/android-midi-lib)：该项目主要适用于无法访问Java的javax.sound.midi库的Android应用程序。
* [MWEngine](https://github.com/igorski/MWEngine)：适用于Android的音频引擎和DSP库，以C++编写，在音乐环境中提供低延迟性能，同时提供Java/Kotlin API。
* [Minim](https://github.com/ddf/Minim)：Java音频库，设计用于与Processing一起使用。
* [JSyn](https://github.com/philburk/jsyn)：Java模块化音频合成器。
* [Jaudiotagger](https://bitbucket.org/ijabz/jaudiotagger)：Jaudiotagger是音频标记库，用于标记音频文件中的数据。
* [JNAJack](https://github.com/jaudiolibs/jnajack)：JACK音频连接套件的Java绑定。
* [SoundLibs](https://github.com/pdudits/soundlibs)：Java声音库的Maven工件。
* [JOAL](https://github.com/sgothel/joal)：JOAL是OpenAL API的Java绑定的参考实现，旨在为用Java编写的应用程序提供硬件支持的3D空间音频。
* [jLibrosa](https://github.com/Subtitle-Synchronizer/jlibrosa)：Librosa等效的Java库，用于处理音频文件并从中提取特征。
* [JSSRC](https://github.com/hutm/JSSRC)：JSSRC是用纯Java编写的高质量音频重采样器。
* [Java Stream Player](https://github.com/goxr3plus/java-stream-player)：Java高级音频控制器库。
* [Micromod](https://github.com/martincameron/micromod)：适用于ProTracker MOD音乐格式的优质播放器库。
* [Panako](https://github.com/JorenSix/Panako)：Panako是一种声学指纹识别系统，该系统能够从音频流中提取指纹，并将这些指纹存储在数据库中，或者在提取的指纹和存储的指纹之间找到匹配。
* [Java LAME](https://github.com/nwaldispuehl/java-lame)：LAME库的本机Java端口。
* [Xt Audio](https://github.com/sjoerdvankreel/xt-audio)：适用于C、C++、Java和.NET的平台独立低延迟音频。
* [Volctl](https://github.com/BjoernPetersen/volctl)：一个简单的Java库，提供对Windows和Linux上的音频音量控制的访问。
* [Crate Digger](https://github.com/Deep-Symmetry/crate-digger)：一个用于获取和解析rekordbox媒体导出跟踪分析文件的Java库。

#### 视频库

* [WVP GB28181](https://github.com/648540858/wvp-GB28181-pro)：Web Video Platform是一个基于GB28181-2016标准实现的开箱即用的网络视频平台，负责实现核心信令与设备管理后台部分，支持NAT穿透，支持海康、大华、宇视等品牌的IPC、NVR接入。
* [Opencast](https://github.com/opencast/opencast)：Opencast是一个灵活、可靠、可扩展的开源视频管理系统，适用于学术机构，由来自全球领先大学和组织的开发人员社区构建。
* [Libjitsi](https://github.com/jitsi/libjitsi)：Libjitsi是用于安全实时音频/视频通信的高级Java媒体库。
* [M3U8 Parser](https://github.com/carlanton/m3u8-parser)：适用于Java的简单HLS播放列表解析器。
* [Open M3U8](https://github.com/iheartradio/open-m3u8)：这是一个开源的M3U8播放列表解析器和写入器Java库。
* [V4L4j](https://code.google.com/archive/p/v4l4j/)：V4L4j是一个Java包，它提供了从Java简单访问Video4Linux(V4L) API捕获接口的功能。
* [Video4j](https://github.com/metaloom/video4j)：Video4j是org.openpnp:opencv之上的高级库，它提供API在Java中处理视频媒体。
* [FMJ](http://fmj-sf.net/)：FMJ是一个开源项目，其目标是提供Java媒体框架(JMF)的替代方案，同时保持与JMF的API兼容。
* [Easy FLV](https://gitee.com/javpower/easy-flv)：Easy FLV是一个Java库，可以将RTSP或RTMP视频流转换为FLV格式，以便在Web浏览器中播放。

#### 多媒体库

* [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor)：Metadata Extractor是一个用于从媒体文件中读取元数据的Java库。
* [Vlcj](https://github.com/caprica/vlcj)：VLC媒体播放器的Java框架。
* [VLC Android](https://code.videolan.org/videolan/vlc-android/)：这是VLC的官方Android端口。
* [MCAV](https://github.com/PulseBeat02/mcav)：MCAV是一个非常强大的Java多媒体库和插件，是EzMediaCore2的后继者。
* [MediathekView](https://github.com/mediathekview/MediathekView)：MediathekView程序会搜索各公共广播公司的媒体库，并下载或播放内容。
* [GStreamer 1.x Java Core](https://github.com/gstreamer-java/gst1-java-core)：这是GStreamer 1.x的一组Java绑定，GStreamer是一个用C语言编写的开源、基于管道的多媒体框架。
* [Quick Media](https://github.com/liuyueyi/quick-media)：QuickMedia是一个提供图片、音频、视频、二维码、网页、Markdown处理的Web项目。
* [Monte Media Library](http://www.randelshofer.ch/monte/)：Monte Media Library是一个用于处理媒体数据的Java库，支持的媒体格式包括静态图像、视频、音频和元数据。
* [Humble Video](https://github.com/artclarke/humble-video)：HumbleVideo允许JVM语言对音频和视频数据进行解码、分析/修改和编码为数百种不同格式(例如H264、AAC、MP3、FLV等)。
* [LibSDL4J](https://github.com/libsdl4j/libsdl4j)：LibSDL4J是SDL2 API到Java的映射。
* [JavaForce](https://github.com/pquiring/javaforce)：JavaForce库，用于构建强大的应用程序和服务(相机、OpenGL、OpenCL、FFmpeg的原生绑定)，包含VoIP协议栈、PLC I/O和众多应用程序。
* [SimpleRtmp](https://github.com/faucamp/SimpleRtmp)：SimpleRtmp是一个用于构建RTMP客户端应用程序的Java库。

#### 视频通讯

* [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)：BigBlueButton是一个开源虚拟教室，旨在帮助教师教学和学习者学习。
* [Apache OpenMeetings](https://github.com/apache/openmeetings)：Openmeetings提供视频会议、即时消息、白板、协作文档编辑和其他群件工具。
* [Ant Media Server](https://github.com/ant-media/Ant-Media-Server)：Ant Media Server是一款直播流引擎软件，通过使用WebRTC技术提供自适应、超低延迟流媒体，延迟约为0.5秒。
* [WebRTC Java](https://github.com/devopvoid/webrtc-java)：WebRTC Java是WebRTC Native API的Java包装器，提供与W3C JavaScript API类似的功能。
* [Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)：Jitsi Videobridge是一个与WebRTC兼容的视频路由器或SFU，可用于构建高度可扩展的视频会议基础设施。
* [OpenVidu](https://github.com/OpenVidu/openvidu)：OpenVidu是一个使你能够构建实时应用程序的平台。
* [OnChat](https://github.com/onch-at/onchat)：OnChat是一个简单、美观、移动优先的即时消息渐进式Web应用程序。
* [Kurento](https://github.com/Kurento/kurento)：Kurento Media Server负责媒体传输、处理、加载和记录。
* [NextRTC](https://github.com/mslosarz/nextrtc-signaling-server)：NextRTC是一个用Java编写的简单WebRTC信令服务器。
* [SIP Servlet](https://github.com/RestComm/sip-servlets)：RestComm SIP Servlet是SIP、IMS和WebRTC应用服务器。
* [WebRTC Server Java](https://github.com/ddssingsong/webrtc_server_java)：实现基本的信令收发，配合Android端实现基本的呼叫、响铃、挂断、语音通话、视频通话的功能。
* [Contact Center](https://github.com/caoliang1918/contact-center)：智能电话外呼系统。
* [JSIP](https://github.com/usnistgov/jsip)：Java SIP规范参考实现，由美国国家标准技术研究院开源。
* [CSipSimple](https://github.com/r3gis3r/CSipSimple)：CSipSimple是一款开源的Android原生SIP客户端。
* [ICE4j](https://github.com/jitsi/ice4j)：ICE协议的Java实现，可供SIP和XMPP应用程序使用。
* [JazminServer](https://github.com/guooscar/JazminServer)：JazminServer是一个基于Java的应用程序/消息/RPC/SIP/RTMP/UDP中继服务器。
* [Taoyao](https://gitee.com/acgist/taoyao)：桃夭是套基于Mediasoup开发的WebRTC音视频信令服务，可以非常方便的扩展信令接入更多智能终端。

#### FFmpeg包装器

* [JavaCV](https://github.com/bytedeco/javacv)：JavaCV包含OpenCV、FFmpeg等的Java接口。
* [RxFFmpeg](https://github.com/microshow/RxFFmpeg)：RxFFmpeg是基于FFmpeg 4.0、X264、mp3lame、fdk-aac、opencore-amr、openssl编译的适用于Android平台的音视频编辑、视频剪辑的快速处理框架。
* [FFmpeg CLI Wrapper](https://github.com/bramp/ffmpeg-cli-wrapper)：用于从Java运行FFmpeg的流式接口。
* [FFmpeg Android Java](https://github.com/cropsly/ffmpeg-android-java)：FFmpeg Android Java是一个Java库，简化了在Android项目中使用Ffmpeg的任务。
* [JAVE2](https://github.com/a-schild/jave2)：JAVE库是ffmpeg项目的Java包装器。
* [Jaffree](https://github.com/kokorin/Jaffree)：Jaffree代表Java FFmpeg和FFprobe FREE命令行包装器。
* [FFmpeg4j](https://github.com/Manevolent/ffmpeg4j)：FFmpeg4j是一个Java库，它封装了FFmpeg库的功能。
* [FFCH4J](https://github.com/eguid/FFCH4J)：Java封装的提供FFmpeg命令执行、停止、查询功能的简单管理器。

#### 音频编解码器

* [LiTr](https://github.com/linkedin/LiTr)：LiTr是一款轻量级的视频/音频转换工具，支持对视频和音频轨道进行转码，并可选择进行帧修改，由LinkedIn开源。
* [JLayer](https://github.com/umjammer/jlayer)：JLayer是一个用于Java平台实时解码/播放/转换MPEG 1/2/2.5 Layer 1/2/3(即MP3)的库。
* [MP4 Parser](https://github.com/sannies/mp4parser)：用于读取、写入和创建MP4容器的Java API。
* [Jave](https://github.com/dadiyang/jave)：音频转码工具，主要用于将微信语音AMR格式转换为MP3格式以便在H5的Audio标签中进行播放。
* [JCodec](https://github.com/jcodec/jcodec)：JCodec是视频/音频编解码器的纯Java实现。
* [Concentus](https://github.com/lostromb/concentus)：Opus音频编解码器的纯可移植C#和Java实现。
* [FLAC Java](https://github.com/nayuki/FLAC-library-Java)：Java中的FLAC解码器库。
* [Xuggler](https://www.xuggle.com/xuggler/)：Xuggler是一个功能强大的工具，旨在简化直接从Java解压缩、修改和重新压缩任何媒体文件或流的过程。
* [JNA AAC Encoder](https://github.com/sheinbergon/jna-aac-encoder)：此库为JVM提供AAC编码功能。

#### 媒体服务器

* [Airsonic](https://github.com/airsonic/airsonic)：Airsonic是一款免费的基于Web的媒体服务器，可让你随时随地访问音乐。
* [Universal Media Server](https://github.com/UniversalMediaServer/UniversalMediaServer)：Universal Media Server是兼容DLNA的UPnP媒体服务器，它能够在大多数现代设备之间共享视频、音频和图像。
* [LiveBox](https://github.com/parzulpan/livebox)：LiveBox是一个跨平台的网络媒体聚合应用，支持直播视频、高清电视和广播电台的在线观看或收听。
* [EasyMedia](https://gitee.com/52jian/EasyMedia)：Spring Boot、Netty实现的HTTP-FLV、WebSocket-FLV流媒体服务。
* [PS3 Media Server](https://github.com/ps3mediaserver/ps3mediaserver)：PS3 Media Server是一个跨平台的DLNA兼容UPnP媒体服务器。
* [RestComm Media](https://github.com/RestComm/media-core)：Restcomm媒体服务器，用于实时云通信。
* [ZLM4J](https://gitee.com/aizuda/zlm4j)：本项目是对ZLMediaKit提供的C API的Java封装，由爱组搭开源。
* [Supersonic](https://github.com/Mach5/supersonic)：Supersonic可将你的媒体即时传输到任何HTTP连接设备，不受比特率限制。

#### 呼叫中心

* [ESL Client](https://github.com/esl-client/esl-client)：ESL Client是FreeSWITCH项目中基于Java的事件套接字库。
* [FreeSWITCH ESL ALL](https://github.com/zhouhailin/freeswitch-externals)：FreeSWITCH额外项目。
* [Contact Center](https://github.com/caoliang1918/contact-center)：智能电话外呼系统。
* [Asterisk Java](https://github.com/asterisk-java/asterisk-java)：Asterisk Java包含一组Java类，使你能够轻松构建与Asterisk PBX服务器交互的Java应用程序。
* [Peers](https://github.com/ymartineau/peers)：Peers是一款非常简单的软电话。

## 数据结构

* [T-Digest](https://github.com/tdunning/t-digest)：一种新的数据结构，用于准确在线累积基于排名的统计数据，例如分位数和修剪平均值。
* [Bifurcan](https://github.com/lacuna/bifurcan)：该库提供了可变和不可变数据结构的高质量Java实现，每个实现都共享一个通用API。
* [Sux4J](https://github.com/vigna/Sux4J)：Sux4J提供了许多相关数据结构的实现，涵盖位数组、压缩列表和最小完美哈希函数的排名/选择，由米兰大学开发。
* [Pods4k](https://github.com/daniel-rusu/pods4k)：Kotlin的面向性能的数据结构。
* [NetworkAnalysis](https://github.com/CWTSLeiden/networkanalysis)：该库提供了用于网络分析的算法和数据结构，专注于网络的聚类(或社区检测)和布局(或映射)，由莱顿大学开源。
* [Time-Utilities](https://github.com/Breinify/brein-time-utilities)：包含多个时间相关数据和索引结构(例如IntervalTree、BucketTimeSeries)以及算法的库。
* [Funcj](https://github.com/typemeta/funcj)：用于Java的面向函数的数据结构、算法和库的集合。
* [Athena](https://github.com/sanity/Athena)：支持任意布尔查询的高效内存数据结构。
* [HyperMinHash Java](https://github.com/LiveRamp/HyperMinHash-java)：用于计算对数空间中的并集、交集和集合基数的概率数据结构。
* [Dictomaton](https://github.com/danieldk/dictomaton)：该Java库实现存储在有限状态自动机中的字典。
* [ObjectLayout](https://github.com/ObjectLayout/ObjectLayout)：ObjectLayout提供了一组数据结构类，这些类的设计考虑了优化的内存布局。
* [Zero-Allocation Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing)：用于对Java中的任何字节序列进行哈希处理，包括各种原始数组、缓冲区、CharSequence等。
* [Completely](https://github.com/fmmfonseca/completely)：Completely是一个Java自动完成库。

#### 树

* [SnapTree](https://github.com/nbronson/snaptree)：SnapTree是一种具有快速克隆、快照和一致迭代功能的并发AVL树，由斯坦福开源。
* [Darts Java](https://github.com/komiya-atsushi/darts-java)：Darts Java是Darts(双数组Trie系统)的Java移植。
* [DoubleArrayTrie](https://github.com/digitalstain/DoubleArrayTrie)：DoubleArrayTrie是双数组trie的纯Java实现。
* [Adaptive Radix Tree](https://github.com/rohansuri/adaptive-radix-tree)：Java中快速且节省空间的基数树。
* [RTree](https://github.com/davidmoten/rtree)：使用响应式API在Java中实现不可变的内存中R树和R*树。
* [RTree](https://github.com/conversant/rtree)：RTree是一种索引，支持构建边界矩形树，用于任意范围搜索。
* [Tree](https://github.com/Scalified/tree)：该库包含树数据结构的不同实现，例如K进制、二叉树、表达式树等。
* [RTree2](https://github.com/davidmoten/rtree2)：内存中不可变的二维R树实现。
* [BTree4j](https://github.com/myui/btree4j)：Btree4j是一个用纯Java编写的基于磁盘的B+树。
* [BPlusTree](https://github.com/andylamp/BPlusTree)：一种高效、简洁、简单的纯磁盘B+Tree数据结构实现。
* [Trie4J](https://github.com/takawitter/trie4j)：Trie4J是各种trie实现的排序集合。
* [PH-Tree](https://github.com/tzaeschke/phtree)：PH-Tree是一种多维索引和存储结构，默认情况下，它存储由k个64位整数组成的k维键(点)。
* [Suffix Tree](https://github.com/abahgat/suffixtree)：使用Ukkonen算法的广义后缀树的Java实现。
* [LSM-Tree](https://github.com/tomfran/LSM-Tree)：Java中日志结构合并树(LSM Tree)数据结构的实现。
* [TinSpin Indexes](https://github.com/tzaeschke/tinspin-indexes)：TinSpin Indexes是一个内存索引库。
* [PART](https://github.com/ankurdave/part)：PART是一种基于ART的具有高分支因子和自适应大小节点的字典树。
* [Quadtree](https://github.com/varunpant/Quadtree)：这是四叉树的Java实现，四叉树是一种用于存储二维位置数据的树形数据结构。
* [GenericTree](https://github.com/vivin/GenericTree)：Java中的通用(N元)树实现。
* [Autocomplete](https://github.com/vivekn/autocomplete)：在多种语言中实现高效的自动单词补全的Tries。
* [JSI](https://github.com/aled/jsi)：JSI项目旨在维护高性能Java版本的RTree空间索引算法。

#### 堆

* [JHeaps](https://github.com/d-michail/jheaps)：JHeaps是一个免费库，提供各种用Java编写的堆实现。
* [Chronicle-Values](https://github.com/OpenHFT/Chronicle-Values)：通过接口生成Bean的堆上实现。

#### 图

* [Apache Commons Graph](https://github.com/apache/commons-graph)：Commons Graph是一个用于管理图和基于图的数据结构的工具包。
* [Cassovary](https://github.com/twitter/cassovary)：Cassovary是一个简单的JVM大图处理库，由Twitter开源。
* [NetflixGraph](https://github.com/Netflix/netflix-graph)：NetflixGraph是一种紧凑的内存数据结构，用于表示有向图数据，由Netflix开源。
* [JGraLab](https://github.com/jgralab/jgralab)：JGraLab是一个Java图形库，实现了所谓的TGraphs：类型化、属性化、有序和有向图，由科布伦茨兰道大学开源。
* [Traverser](https://github.com/intuit/Traverser)：Traverser是一个Java库，可帮助软件工程师实现数据结构的高级迭代，由Intuit开发。

#### BitSet

* [SparseBitSet](https://github.com/brettwooldridge/SparseBitSet)：Java的高效稀疏位集实现。
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap)：Java中更好的压缩位集。
* [JavaEWAH](https://github.com/lemire/javaewah)：Java BitSet类的压缩替代方案。
* [Bit-Lib4j](https://github.com/devnied/Bit-lib4j)：Bit-Lib4j是一个用于在Java中处理字节或位的库。

#### 队列

* [Conversant](https://github.com/conversant/disruptor)：Conversant Disruptor是环形缓冲区中性能最高的实现，它几乎没有开销，并且采用了特别简单的设计。
* [CoralRing](https://github.com/coralblocks/CoralRing)：CoralRing是堆外共享内存中的超低延迟、无锁、无垃圾、批处理和并发循环队列(环)，用于使用内存映射文件跨不同JVM进行Java进程间通信。
* [CoralQueue](https://github.com/coralblocks/CoralQueue)：CoralQueue是一种超低延迟、高性能、无锁、无垃圾的并发队列、多路分解器、多路复用器、mpmc队列和拆分器。
* [Tape](https://github.com/square/tape)：Android和Java中与队列相关的类的集合，由Square开源。
* [Big Queue](https://github.com/bulldog2011/bigqueue)：基于内存映射文件的大、快速且持久的队列。
* [Low GC MemBuffers](https://github.com/cowtowncoder/low-gc-membuffers)：用于创建内存循环缓冲区的库，该缓冲区使用直接ByteBuffer来最大限度地减少GC开销。
* [Popout](https://github.com/infobip/popout)：Popout是Java的基于文件的队列，由Infobip开源。

#### Map

* [TinyMap](https://github.com/intelie/tinymap)：内存高效的不可变HashMap/HashSet。
* [CompactHashMap](https://github.com/vlsi/compactmap)：这是HashMap的内存高效替代方案。
* [PauselessHashMap](https://github.com/giltene/PauselessHashMap)：java.util.HashMap兼容的Map，在调整大小时不会停止put或get。
* [SmoothieMap](https://github.com/TimeAndSpaceIO/SmoothieMap)：SmoothieMap是Java的Map实现，具有最低的内存使用率并且不存在重哈希延迟峰值。
* [BigMap](https://github.com/fizzed/bigmap)：轻量级Map、SortedMap、LinkedMap、Set和SortedSet实现，可通过将任务卸载到磁盘来缓解内存压力。
* [HashSmith](https://github.com/bluuewhale/HashSmith)：HashSmith提供多种高性能哈希表实现，优化于现代JVM的速度和内存效率。

#### List

* [GlueList](https://github.com/ertugrulcetin/GlueList)：GlueList是一个全新的List实现，它比ArrayList和LinkedList快得多。

#### CRDT

* [Wurmloch CRDT](https://github.com/netopyr/wurmloch-crdt)：JVM无冲突复制数据类型(CRDT)的实验实现。
* [Java CRDT](https://github.com/ajantis/java-crdt)：Java中常见的无冲突复制数据类型集合。

#### 布隆过滤器

* [Orestes Bloomfilter](https://github.com/Baqend/Orestes-Bloomfilter)：Java中不同布隆过滤器的库，具有可选的Redis支持、计数和许多哈希选项。
* [InBloom](https://github.com/EverythingMe/inbloom)：跨语言布隆过滤器实现。
* [JRedisBloom](https://github.com/RedisBloom/JRedisBloom)：RedisBloom概率模块的Java客户端。
* [Bloom Filter Scala](https://github.com/alexandrnikitin/bloom-filter-scala)：Scala的布隆过滤器。
* [Greplin Bloom Filter](https://github.com/Cue/greplin-bloom-filter)：概率集合数据结构的Java实现。
* [PDD](https://github.com/jparkie/PDD)：基于高级布隆过滤器的算法，可在流中实现高效的近似数据去重复。
* [Minperf](https://github.com/thomasmueller/minperf)：极小的完美哈希函数库。
* [Bloofi](https://github.com/lemire/bloofi)：多维布隆过滤器的Java实现。
* [Opposite Bloom Filter](https://github.com/jmhodges/opposite_of_a_bloom_filter)：该仓库包含Java和Go中“布隆过滤器的对立面”的线程安全实现。
* [Java Bloom Filter](https://github.com/MagnusS/Java-BloomFilter)：Java Bloom Filter是一个用Java编写的独立布隆过滤器实现。
* [Bloomfilter](https://github.com/wangxu0/bloomfilter)：该项目实现了布隆过滤器，并可选择和扩展不同的BitSet或其他存储方法。

#### 布谷鸟过滤器

* [CuckooFilter4J](https://github.com/MGunlogson/CuckooFilter4J)：Cuckoo过滤器的高性能Java实现。
* [Setfilters](https://github.com/google/setfilters)：该仓库包含集合过滤器数据结构的集合的实现，通常也称为近似成员资格查询数据结构，由Google开源。
* [FastFilter](https://github.com/FastFilter/fastfilter_java)：Java中的快速近似成员资格过滤器。

## 基本类型

* [jOOU](https://github.com/jOOQ/jOOU)：jOOU为四种Java整数类型byte、short、int和long提供无符号整数版本。
* [Primitive](https://github.com/mintern-java/primitive)：Primitive提供与基本类型相关的功能的实用方法，包括基于自定义比较器的排序和搜索。

## 堆外内存库

* [Unsafe Tool](https://github.com/alexkasko/unsafe-tools)：使用sun.misc.Unsafe处理堆外内存的工具。
* [LLPL](https://github.com/pmem/llpl)：LLPL是一个Java库，提供对堆外持久性内存的访问，由Intel开源。
* [Slice](https://github.com/airlift/slice)：Slice是一个用于高效处理Java字节数组的Java库。
* [FastTuple](https://github.com/boundary/fasttuple)：FastTuple生成原始值的异构集合，并尽可能确保它们在内存中相邻排列。
* [Chronicle Core](https://github.com/OpenHFT/Chronicle-Core)：Chronicle Core是一个先进的低级库，为开发人员提供了与操作系统交互、管理内存、处理资源等功能强大的工具。
* [DataSketches Java Memory Component](https://github.com/apache/datasketches-memory)：Java的高性能本机内存访问库。
* [LArray](https://github.com/xerial/larray)：用于管理大型堆外数组的库，可以在Java和Scala中容纳超过2G(2^31)的条目。
* [JNVM](https://github.com/jnvm-project/jnvm)：J-NVM是一个Java框架，用于高效、本地地访问Java中的非易失性主存储器(NVMM)作为堆外内存，由南巴黎电信学院开源。
* [Slab](https://github.com/RichardWarburton/slab)：保证内存对齐的堆外Java POJO。
* [Overlord](https://github.com/Moderocky/Overlord)：Overlord是一个强大的内存管理库。

## 结构体

* [JUnion](https://github.com/TehLeo/junion)：为Java编程语言提供结构类型。
* [Javastruct](https://github.com/dubrousky/javastruct)：Javastruct是一个将Java对象用作C或C++结构的库。
* [Strukt](https://github.com/Jire/Strukt)：JVM上的C风格结构体。

## 随机数生成器

* [JNanoId](https://github.com/aventrix/jnanoid)：Java的唯一字符串ID生成器。
* [UUID Creator](https://github.com/f4b6a3/uuid-creator)：这是一个用于生成通用唯一标识符的Java库。
* [ULID Creator](https://github.com/f4b6a3/ulid-creator)：这是一个用于生成ULID的Java库。
* [Apache Commons RNG](https://github.com/apache/commons-rng)：Commons RNG项目提供伪随机生成器的纯Java实现。
* [Java UUID Generator](https://github.com/cowtowncoder/java-uuid-generator)：JUG是一组用于处理UUID的Java类：使用任何标准方法生成UUID、高效输出、排序等。
* [FastUUID](https://github.com/jchambers/fast-uuid)：FastUUID是一个用于快速有效地解析和写入UUID的Java库。
* [FriendlyID](https://github.com/Devskiller/friendly-id)：FriendlyID库将给定的UUID(36个字符)转换为基于Base62(最多22个字符)的URL友好ID。
* [Juniper](https://github.com/tommyettinger/juniper)：Juniper提供了java.util.Random功能的超集，其中包含EnhancedRandom抽象类和各种具体实现。
* [Sqids Java](https://github.com/sqids/sqids-java)：Sqids是一个小型库，可让你从数字生成唯一的ID。
* [ULIDJ](https://github.com/azam/ulidj)：Java的ULID生成器和解析器。
* [Biski64](https://github.com/danielcota/biski64)：Biski64是一个极快的伪随机数生成器(PRNG)，保证最小周期为2^64。
* [GraphAware UUID](https://github.com/graphaware/neo4j-uuid)：GraphAware UUID是一个简单的库，它透明地为图中新创建的节点和关系分配一个UUID。
* [Locality UUID Java](https://github.com/groupon/locality-uuid.java)：这是一个UUID类，旨在帮助在插入分布式数据系统(例如MongoDB或HBase)时控制数据位置，由Groupon开源。
* [Kotlinx UUID](https://github.com/hfhbd/kotlinx-uuid)：Kotlinx UUID是一个多平台Kotlin库，为kotlin.uuid.Uuid添加了辅助方法。
* [CUID Java](https://github.com/thibaultmeyer/cuid-java)：CUID的Java实现。
* [IDGenerator](https://github.com/jingpeicomp/id-generator)：生成19位的Long ID、22位的短UUID、卡号、短卡号、带校验码卡号、激活码、付款码、数据加密、手机号加密、带失效时间的数字加密。

## 算法库

* [WikiSort](https://github.com/BonzaiThePenguin/WikiSort)：WikiSort是块合并排序的一种实现。
* [Hashids.java](https://github.com/yomorun/hashids-java)：Hashids算法Java实现。
* [AhoCorasickDoubleArrayTrie](https://github.com/hankcs/AhoCorasickDoubleArrayTrie)：基于双数组Trie结构的Aho Corasick算法的极快实现。
* [MinHash](https://github.com/codelibs/minhash)：该库提供了用于b位MinHash算法的工具。
* [Evo Inflector](https://github.com/atteo/evo-inflector)：Evo Inflector实现了英语复数化算法。
* [ConsistentHash](https://github.com/Jaskey/ConsistentHash)：Java中的通用一致性哈希实现，支持虚拟节点和用户定义的哈希函数。
* [Min2phase](https://github.com/cs0x7f/min2phase)：Kociemba两阶段算法的优化实现。
* [JWave](https://github.com/graetz23/JWave)：离散傅里叶变换、快速小波变换和小波包变换算法的Java实现。
* [Kalman](https://github.com/wouterbulten/kalmanjs)：卡尔曼一维数据滤波器。 
* [RNNoise4j](https://github.com/henkelmax/rnnoise4j)：一个用C语言使用JNI编写的RNNoise Java包装程序。
* [RendezvousHash](https://github.com/clohfink/RendezvousHash)：基于环的一致哈希的替代方案，这是Rendezvous(最高随机权重，HRW)哈希的快速线程安全实现。
* [Patricia Trie](https://github.com/rkapsi/patricia-trie)：检索以字母数字编码的信息的实用算法。
* [Jbsdiff](https://github.com/malensek/jbsdiff)：bsdiff算法的Java实现。
* [SZZ Unleashed](https://github.com/wogscpar/SZZUnleashed)：SZZ Unleashed是SZZ算法的实现，这是一种识别引入错误的提交的方法。
* [Hilbert Curve](https://github.com/davidmoten/hilbert-curve)：用于将沿N维希尔伯特曲线的距离转换为点并返回的Java实用程序。
* [Chronicle Algorithms](https://github.com/OpenHFT/Chronicle-Algorithms)：用于哈希、BitSet操作、访问数据类型的原始字节、堆外锁定的零分配，高效算法。
* [Compression](https://github.com/lichess-org/compression)：lichess.org的国际象棋时钟和着法压缩算法。
* [Timeseries Forecast](https://github.com/Workday/timeseries-forecast)：这是一个Java开源库，提供时序预测功能。
* [Delaunay Triangulation](https://github.com/jdiemke/delaunay-triangulator)：增量2D Delaunay三角剖分算法的简单Java实现。
* [JavaReedSolomon](https://github.com/Backblaze/JavaReedSolomon)：这是一个简单而高效的Java Reed-Solomon实现。
* [LattiCG](https://github.com/mjtb49/LattiCG)：反转Java的java.util.Random类的可能内部种子，并以各种Random调用的不等式系统的形式给出其输出信息。
* [ByteSeek](https://github.com/nishihatapalmer/byteseek)：ByteSeek是一个Java库，用于有效匹配字节模式并搜索这些模式。
* [LightGBM4j](https://github.com/metarank/lightgbm4j)：LightGBM4j是LightGBM项目的零依赖Java包装器。
* [TreeLayout](https://github.com/abego/treelayout)：TreeLayout可以为任意树创建树布局。
* [STL4j](https://github.com/ServiceNow/stl-decomp-4j)：Seasonal-Trend-Loess时序分解算法的Java实现。
* [Sudoku](https://github.com/sfuhrm/sudoku)：一个用于创建数独谜题的超快速算法的Java实现，同时还具有解答数独谜题的功能。
* [Dancing Links Java](https://github.com/rafalio/dancing-links-java)：这是Knuth的Dancing Links算法的Java实现，用于有效解决精确覆盖问题。
* [APTED](https://github.com/DatabaseGroup/apted)：这是APTED算法的实现，该算法是计算树编辑距离的最先进的解决方案，由奥地利萨尔茨堡大学开源。
* [MurmurHash Java](https://github.com/tnm/murmurhash-java)：MurmurHash2的32位和64位实现。
* [Libcrunch](https://github.com/twitter-archive/libcrunch)：Libcrunch是一个轻量级映射框架，它将数据对象映射到多个节点，并受到用户指定的约束，由Twitter开源。
* [VNameGenerator](https://github.com/Valkryst/VNameGenerator)：一种Java实现的多种过程式命名生成算法，包括组合命名、辅音元音、上下文无关语法和马尔可夫链。

#### 字符串算法

* [Java String Similarity](https://github.com/tdebatty/java-string-similarity)：实现不同字符串相似度和距离测量的库。
* [Fuzzy Matcher](https://github.com/intuit/fuzzy-matcher)：Fuzzy Matcher是一个基于Java的库，用于对文档集合中的相似元素进行匹配和分组，由Intuit开发。
* [StringMetric](https://github.com/rockymadden/stringmetric)：StringMetric提供执行近似字符串匹配、字符串相似度/距离测量、按单词发音索引以及发音相似性比较的功能。
* [SimMetrics](https://github.com/Simmetrics/simmetrics)：相似度和距离度量的Java库，例如Levenshtein距离和余弦相似度。
* [Xsimilarity](https://github.com/iamxiatian/xsimilarity)：相似度计算软件包。
* [TextAnalyzer](https://github.com/sea-boat/TextAnalyzer)：基于机器学习、统计学和词典的文本分析器，可以分析文本。
* [Java String Similarity](https://github.com/rrice/java-string-similarity)：Java String Similarity是一个实现了多种计算字符串之间相似度算法的Java库。
* [NLP HanZi Similar](https://github.com/houbb/nlp-hanzi-similar)：NLP HanZi Similar为汉字提供相似性的计算。
* [StringDistance](https://github.com/vickumar1981/stringdistance)：Scala和Java的模糊匹配字符串距离库。
* [JavaWuzzy](https://github.com/xdrop/fuzzywuzzy)：FuzzyWuzzy模糊字符串匹配算法的Java实现。
* [Apache Commons Text](https://github.com/apache/commons-text)：Commons Text是一个专注于字符串算法的库。
* [Strman](https://github.com/shekhargulati/strman-java)：Java 8字符串操作库。
* [Aho Corasick](https://github.com/robert-bor/aho-corasick)：用于高效字符串匹配的Aho-Corasick算法的Java实现。
* [StringSearch](https://github.com/johannburkard/StringSearch)：Java中的高性能模式匹配算法。
* [Word Checker](https://github.com/houbb/word-checker)：Word Checker用于单词拼写检查。
* [JavaPermutationTools](https://github.com/cicirello/JavaPermutationTools)：JavaPermutationTools库提供Java类、接口等，用于表示和生成排列和序列，以及对排列和序列执行计算。

#### 文本排序

* [Externalsortinginjava](https://github.com/lemire/externalsortinginjava)：Externalsortinginjava使用多个核心和外部内存算法对非常大的文件进行排序。
* [Big Sorter](https://github.com/davidmoten/big-sorter)：通过将非常大的文件(或输入流)拆分为多个中间小排序文件并合并来对其进行排序。
* [Java Merge Sort](https://github.com/cowtowncoder/java-merge-sort)：Java Merge Sort项目实现了基于磁盘的基本多路归并排序，并支持可配置的输入和输出格式(不仅仅是文本排序)。

#### 聚类算法

* [Carrot2](https://github.com/carrot2/carrot2)：Carrot2是一个用于文本聚类的编程库。
* [T SNE Java](https://github.com/lejon/T-SNE-Java)：Van Der Maaten和Hinton的t-SNE聚类算法的纯Java实现。
* [Clust4j](https://github.com/tgsmith61591/clust4j)：Clust4j是一组基于Java的分类聚类算法。
* [Hierarchical Clustering Java](https://github.com/lbehnke/hierarchical-clustering-java)：用Java实现凝聚层次聚类算法，支持不同的链接方法。

#### 图算法

* [JGraphT](https://github.com/jgrapht/jgrapht)：JGraphT是一个免费的Java类库，提供数学图论对象和算法。
* [Kaliningraph](https://github.com/breandan/galoisenne)：Kotlin中的图、有限域和离散动力系统。
* [Eclipse Layout Kernel](https://github.com/eclipse-elk/elk)：Eclipse Layout Kernel提供了多种布局算法，以及基于Eclipse的基础架构，用于将它们连接到编辑器和查看器。
* [Dijkstras Algorithm](https://github.com/mburst/dijkstras-algorithm)：Dijkstra最短路径算法的不同语言实现。
* [PathFinder](https://github.com/kevinwang1975/PathFinder)：该项目包含广泛应用于路径查找和图遍历的A*搜索算法和用于Cisco路由器最短路径查找的Dijkstra算法的Java实现。
* [Hnswlib](https://github.com/jelmerk/hnswlib)：用于执行近似最近邻搜索的分层可导航小世界图(HNSW)算法的Java实现。
* [Graph Neo4j](https://github.com/neo4j-contrib/neo4j-graph-algorithms)：Neo4j的高效图算法。
* [Viterbi](https://github.com/hankcs/Viterbi)：通用的维特比算法实现。
* [Hipster4j](https://github.com/citiususc/hipster)：Hipster4j是一个轻量级且功能强大的Java和Android启发式搜索库，它包含常见的、完全可定制的算法，例如Dijkstra、A*、DFS、BFS、Bellman-Ford等，由圣地亚哥德孔波斯特拉大学开源。
* [Jaicore Search](https://starlibs.github.io/AILibs/projects/jaicore-search/)：Jaicore Search是一个启发式搜索库，由帕德博恩大学开发。
* [Maze](https://github.com/armin-reichert/mazes)：该项目提供了35多种算法的Java实现，用于生成所谓的“完美迷宫”(只是无向图的生成树)。
* [JGAlgo](https://github.com/barakugav/JGAlgo)：JGAlgo是一个用Java编写的高性能图算法库。
* [JWalker](https://github.com/epieffe/jwalker)：一个极其通用的Java库，用于将A*及其他内置搜索算法应用于用户定义的图。

#### 随机流算法

* [Apache DataSketches](https://github.com/apache/datasketches-java)：Yahoo开源的随机流算法软件库。
* [Sketches Java](https://github.com/DataDog/sketches-java)：分布式分位数草图算法DDSketch的Java实现，由DataDog开源。
* [ZetaSketch](https://github.com/google/zetasketch)：用于单通道、分布式、近似聚合和草图绘制算法的库集合，由Google开源。

#### HyperLogLog算法

* [Stream Lib](https://github.com/addthis/stream-lib)：Stream Lib是一个用于汇总无法存储所有事件的流中数据的Java库，由AddThis开源。
* [Java HyperLogLog](https://github.com/aggregateknowledge/java-hll)：HyperLogLog算法的Java库。
* [Streaminer](https://github.com/mayconbordin/streaminer)：用于挖掘数据流的算法集合，包括频繁项集、分位数、采样、移动平均、集合成员资格和基数。
* [Hash4j](https://github.com/dynatrace-oss/hash4j)：Hash4j是Dynatrace的一个Java库，其中包括基于高质量哈希函数的各种非加密哈希算法和数据结构。

#### Simhash算法

* [Simhash Java](https://github.com/sing1ee/simhash-java)：Simhash算法的Java简单实现。
* [Simhash4J](https://github.com/xlturing/Simhash4J)：Simhash Java单机实现。

#### LSH算法

* [Annoy](https://github.com/spotify/annoy-java)：Annoy是一种最近邻搜索算法，用于搜索空间中与给定查询点接近的点，由Spotify开源。
* [Java LSH](https://github.com/tdebatty/java-LSH)：局部敏感哈希(LSH)的Java实现。
* [TarsosLSH](https://github.com/JorenSix/TarsosLSH)：TarsosLSH是一个实现次线性最近邻搜索算法的Java库。
* [ScANNS](https://github.com/LinkedInAttic/scanns)：ScANNS是Apache Spark的一个最近邻搜索库，最初由LinkedIn开发。
* [DynamicExplorationGraph](https://github.com/Visual-Computing/DynamicExplorationGraph)：DEG是一种基于图的近似最近邻搜索(ANNS)算法，由柏林应用技术大学开源。

#### LDA算法

* [LDA4j](https://github.com/hankcs/LDA4j)：LDA(潜在狄利克雷分配)的Java实现。
* [JGibbLDA](https://jgibblda.sourceforge.net/)：JGibbLDA是隐性狄利克雷分配(LDA)的Java实现，使用吉布斯抽样技术进行参数估计和推理，由越南国立大学开源。
* [JGibbLabeledLDA](https://github.com/myleott/JGibbLabeledLDA)：这是基于流行的JGibbLDA包的Labeled LDA的Java实现。

#### 噪声库

* [Noise](https://github.com/SpongePowered/noise)：Java噪声生成库，基于Jason Bevins的libnoise C++库。
* [JNoise](https://github.com/Articdive/JNoise)：JNoise是一个简单易用的Java库，用于在Java中生成噪声(包括梯度噪声)。
* [FastNoise Lite](https://github.com/Auburn/FastNoiseLite)：FastNoise Lite是一个极其便携的开源噪声生成库，具有大量噪声算法可供选择。
* [OpenSimplex2](https://github.com/KdotJPG/OpenSimplex2)：OpenSimplex Noise的后继者，以及更新的OpenSimplex。
* [Joise](https://github.com/SudoPlayGames/Joise)：Joise是一个用Java编写的2D、3D、4D和6D模块化噪声库。
* [OpenSimplexNoise](https://gist.github.com/KdotJPG/b1270127455a94ac5d19)：基于A*格的替代构造的视觉各向同性相干噪声算法。

#### 装箱算法

* [3D Bin Container Packing](https://github.com/skjolber/3d-bin-container-packing)：此库用于处理3D矩形装箱，它尝试将一组3D物品与一组3D容器中的一个或多个物品进行匹配。
* [XFLP](https://github.com/hschneid/xflp)：XFLP是一个解决具有现实世界约束的3D卡车装载问题的求解器。
* [2D Bin Packing](https://github.com/mses-bly/2D-Bin-Packing)：该项目旨在提供解决不规则(和规则)零件组二维装箱问题的基本功能。
* [Dalsoo Bin Packing](https://github.com/whitegreen/Dalsoo-Bin-Packing)：Dalsoo Bin Packing是一个用于在矩形薄片中对二维不规则形状进行填充的Java库。
* [Nest4J](https://github.com/Yisaer/Nest4J)：Nest4J是一款基于Java作为开发语言的Nest算法包。

#### 下采样

* [Downsampling Java](https://github.com/ggalmazor/lt_downsampling_java8)：Java 8的最大三角形下采样算法实现。
* [Downsample](https://github.com/drcrane/downsample)：这是flot charts插件使用的下采样实现。

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
* [Native Utils](https://github.com/adamheinrich/native-utils)：一个简单的工具库，用于加载存储在JAR存档中的动态库。
* [Jextract](https://github.com/openjdk/jextract)：Jextract是一个从本机库头自动生成Java绑定的工具，Oracle开发。
* [BridJ](https://github.com/nativelibs4java/BridJ)：BridJ是一个Java/原生互操作性库，专注于速度和易用性。
* [HawtJNI](https://github.com/fusesource/hawtjni)：基于Eclipse SWT中使用的JNI生成器的JNI代码生成器。
* [FastFFI](https://github.com/alibaba/fastFFI)：适用于Java和C++的现代高效FFI，由阿里开源。
* [Native Library Loader](https://github.com/scijava/native-lib-loader)：用于从Java中提取和加载本机库的本机库加载器。
* [Jssembly](https://github.com/dvx/jssembly)：Jssembly是一个库，允许你通过JNI桥从Java执行本机汇编。
* [Facebook JNI](https://github.com/facebookincubator/fbjni)：Facebook JNI工具库旨在简化Java JNI的使用。
* [JFFI](https://github.com/jnr/jffi)：libffi的Java绑定。
* [JNIPP](https://github.com/mitchdowd/jnipp)：JNIPP是标准JNI的C++包装器，它旨在简化Java和C++代码集成过程中的一些繁琐步骤。
* [JNIGen](https://github.com/libgdx/gdx-jnigen)：JNIGen是一个小型库，可以与LibGDX一起/或不一起使用，允许C/C++代码与Java源代码内联编写。
* [Native Platform](https://github.com/gradle/native-platform)：用于各种本机API的跨平台Java API的集合，由Gradle团队开源。
* [Libcore Syscall](https://github.com/cinit/LibcoreSyscall)：Libcore Syscall是一个适用于Android的Java库，允许你直接从Java代码进行任何Linux系统调用。
* [JNI HPP](https://github.com/mapbox/jni.hpp)：JNI HPP是一个现代的、类型安全的、仅标头的C++14 JNI包装器，其目的是使从C++调用Java或从Java调用C++变得方便而安全。
* [JNI4Android](https://github.com/bilibili/jni4android)：从伪Java生成C包装器，由B站开源。
* [JFA](https://github.com/0x4a616e/jfa)：JFA是一个用于访问Apple Foundation框架的纯Java库。
* [JPassport](https://github.com/boulder-on/JPassport)：JPassport类似于JNA，但使用Foreign Linker API，而不是JNI。

## 互操作

* [LuaJava](https://github.com/jasonsantos/luajava)：LuaJava是一个Java脚本编写工具，该工具的目标是允许用Lua编写的脚本操作用Java开发的组件。
* [Rococoa](https://github.com/iterate-ch/rococoa)：Rococoa是绑定到Mac Objective-C对象系统的通用Java，它允许在Java中创建和使用Objective-C对象，以及在Java中实现Objective-C接口。
* [Javonet](https://www.javonet.com/)：Javonet是一个高级库，可以在任何编程语言和模块之间进行直接方法调用，从而无需集成层。
* [DynamicObject](https://github.com/rschmitt/dynamic-object)：DynamicObject使Java开发人员能够以惯用的方式和最少的样板使用Clojure强大的数据建模功能。
* [GraalPHP](https://github.com/abertschi/graalphp)：GraalPHP是一个实验性的即时(JIT)编译器和运行时，用于在GraalVM上托管的PHP 7.4+。
* [TruffleSqueak](https://github.com/hpi-swa/trufflesqueak)：GraalVM的Squeak/Smalltalk VM和多语言编程环境，由波茨坦大学开源。
* [Inline Java](https://github.com/tweag/inline-java)：Haskell/Java通过Haskell模块中的内联Java代码进行互操作。
* [JavaErlang](https://github.com/fredlund/JavaErlang)：JavaErlang是一个试图促进Java和Erlang节点之间通信的库，它作为JInterface Java接口之上的附加层实现。

#### Python

* [GraalPy](https://github.com/oracle/graalpython)：GraalPy是基于GraalVM构建的JVM的Python语言的高性能实现，由Oracle开源。
* [Py4J](https://github.com/py4j/py4j)：Py4J使Python程序能够动态访问任意Java对象。
* [JPype](https://github.com/jpype-project/jpype)：JPype是一个Python模块，可在Python内部提供对Java的完全访问。
* [Jep](https://github.com/ninia/jep)：Jep通过JNI将CPython嵌入到Java中。
* [PemJa](https://github.com/alibaba/pemja)：PemJa是一个基于FFI的开源跨语言调用框架，由阿里开源。
* [QPython](https://github.com/qpython-android/qpython)：QPython是适用于Android的Python引擎。
* [Pyrolite](https://github.com/irmen/Pyrolite)：该库允许你的Java或.NET程序非常轻松地与Python程序交互，使用Pyro协议调用远程对象上的方法。

#### Swift

* [Swift Java](https://github.com/swiftlang/swift-java)：Swift Java互操作性工具和库，Apple开源。
* [SwiftJava](https://github.com/SwiftJava/SwiftJava)：SwiftJava是一个Swift代码生成器，以及一个支持用Swift 3.0的Xcode beta6版本编写的代码的小框架。
* [AndroidKit](https://github.com/PureSwift/Android)：Swift绑定到Android SDK(通过JNI)和NDK。
* [Swift4j](https://github.com/scade-platform/swift4j)：Swift4j是一组库和工具，使Swift和Java/Kotlin之间的无缝互作性成为可能。

#### Ruby

* [JRuby](https://github.com/jruby/jruby)：JRuby是使用JVM的Ruby语言的实现。
* [TruffleRuby](https://github.com/oracle/truffleruby)：TruffleRuby是Ruby编程语言的GraalVM高性能实现，由Oracle开源。
* [Rjb](https://github.com/arton/rjb)：Rjb是使用JNI的Ruby-Java桥。

#### Rust

* [JNI Rs](https://github.com/jni-rs/jni-rs)：该项目为Rust提供了完整的JNI绑定。
* [J4RS](https://github.com/astonbitecode/j4rs)：J4RS允许从Rust轻松调用Java代码，反之亦然。
* [Robusta](https://github.com/giovanniberti/robusta)：该库提供了一个过程宏，使得在Rust中编写与JNI兼容的代码变得更容易。
* [Duchess](https://github.com/duchess-rs/duchess)：Duchess是一个Rust包，可以简单、符合人体工程学且高效地与Java代码进行互操作。

#### R

* [RCaller](https://github.com/jbytecode/rcaller)：RCaller是一个软件库，旨在简化从Java调用R的过程，由伊斯坦布尔大学数值方法教授开源。
* [FastR](https://github.com/oracle/fastr)：FastR是基于GraalVM构建的R编程语言的高性能实现，由Oracle开发。
* [RJava](https://github.com/s-u/rJava)：R/Java接口允许在R中使用Java以及将R嵌入到Java中(通过JRI)。
* [Renjin](https://github.com/bedatadriven/renjin)：Renjin是基于JVM的R语言解释器。
* [Rserve](https://github.com/s-u/REngine)：Rserve是一个TCP/IP服务器，它允许其他程序使用各种语言的R功能，而无需初始化R或链接到R库。
* [RSession](https://github.com/yannrichet/rsession)：Rsession提供了一个易于使用的Java类，可以访问远程或本地R会话。

#### .NET

* [JNI4NET](https://github.com/jni4net/jni4net)：JVM和CLR之间的快速、面向对象、进程内桥梁。
* [Java.Interop](https://github.com/dotnet/java-interop)：Java.Interop是JNI的绑定，可用于托管语言(如C#)和一组相关的代码生成器，以允许Java代码调用托管代码，由Microsoft开源。
* [Bluebonnet](https://github.com/spaceflint7/bluebonnet)：这是基于JVM的.NET平台的部分实现，并与Android运行时兼容。
* [JCOReflector](https://github.com/masesgroup/JCOReflector)：JCOReflector是一套全面的库和工具，可并行使用Java/JVM API和.NET。

## 操作系统信息

* [Sigar](https://github.com/hyperic/sigar)：Sigar提供跨平台的系统信息收集的API。
* [OSHI](https://github.com/oshi/oshi)：OSHI是一个免费的基于JNA的Java操作系统和硬件信息库，提供跨平台实现来检索系统信息，例如操作系统版本、进程、内存和CPU使用情况、磁盘和分区、设备、传感器等。
* [JavaSysMon](https://github.com/jezhumble/javasysmon)：JavaSysMon旨在提供一种独立于操作系统的方式来管理操作系统进程并获取实时系统性能信息(例如CPU和内存使用情况)，并作为单个jar文件分发。

## 外部进程执行

* [NuProcess](https://github.com/brettwooldridge/NuProcess)：Java的低开销、非阻塞I/O、外部进程执行实现，它是java.lang.ProcessBuilder和java.lang.Process的替代品。
* [Apache Commons Exec](https://github.com/apache/commons-exec)：Commons Exec是一个从JVM内可靠地执行外部进程的库。
* [Ch.Vorburger.Exec](https://github.com/vorburger/ch.vorburger.exec)：这是一个小型库，允许在后台从Java代码启动外部进程。
* [JProc](https://github.com/fleipold/jproc)：用于运行外部进程的Java库。
* [Giraffe](https://github.com/palantir/giraffe)：Giraffe是一个Java库，可让你轻松访问本地和远程计算机上的文件并执行命令，由Palantir开源。
* [Overthere](https://github.com/xebialabs/overthere)：Overthere是一个Java库，用于在远程主机上操作文件和执行进程。
* [ZT EXEC](https://github.com/zeroturnaround/zt-exec)：Java进程执行库。
* [jPowerShell](https://github.com/profesorfalken/jPowerShell)：允许与PowerShell控制台交互的简单Java API。
* [ZT Process Killer](https://github.com/zeroturnaround/zt-process-killer)：停止从Java启动的进程或通过PID的系统进程。
* [Winrm4j](https://github.com/cloudsoft/winrm4j)：Winrm4j是一个使Java应用程序能够使用WinRM在远程Windows服务器上执行批处理或PowerShell命令的项目。
* [JNR Process](https://github.com/jnr/jnr-process)：JNR Process库提供了JDK ProcessBuilder API的直接替代品，但它不是线程泵填充程序，而是围绕posix_spawn C API的直接抽象，并提供可选择的in、out和err通道。
* [WinP](https://github.com/jenkinsci/winp)：该项目可以让你更好地控制Windows进程，超越JDK中的可用功能。
* [Jash](https://github.com/jbangdev/jbang-jash)：Jash是一个Java库，提供流式、可预测且具有出色开发人员体验的Process接口。
* [KtSh](https://github.com/jaredrummler/KtSh)：KtSh是一个用Kotlin编写的在Android或JVM上执行Shell命令的开源库。
* [Unix4j](https://github.com/tools4j/unix4j)：Unix4j是Unix命令行工具的Java实现，你可以在Java程序中使用你在Unix中了解的命令。
* [jProcesses](https://github.com/profesorfalken/jProcesses)：使用Java获取跨平台进程详细信息。
* [PE/COFF4J](https://github.com/kichik/pecoff4j)：PE/COFF4J是一个用于可移植可执行文件(Windows使用的格式)的Java工程库。
* [Turtle](https://github.com/lordcodes/turtle)：Turtle简化了从Kotlin(或Java)代码运行外部命令和进程的过程。

## 守护进程

* [Termd](https://github.com/termd/termd)：用Java编写终端应用程序的开源库。
* [Akuma](https://github.com/kohsuke/akuma)：Akuma是一个Java库，你可以在应用程序中使用它来支持Unix守护进程。
* [SDNotify](https://github.com/faljse/SDNotify)：SDNotify在Java中实现了systemd通知协议。

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
* [PixelFlow](https://github.com/diwi/PixelFlow)：PixelFlow是一款用于高性能GPU计算的Processing/Java库。
* [JavaCL](https://github.com/nativelibs4java/JavaCL)：Java的OpenCL绑定。
* [ArrayFire Java](https://github.com/arrayfire/arrayfire-java)：ArrayFire的Java包装器。
* [JOCL](https://github.com/gpu/JOCL)：OpenCL的Java绑定。
* [grCUDA](https://github.com/NVIDIA/grcuda)：GraalVM的多语言CUDA集成，由英伟达开源。
* [CLIJ2](https://github.com/clij/clij2)：CLIJ2是一个适用于ImageJ/Fiji、Icy、Matlab和Java的GPU加速图像处理库，由萨塞克斯大学、荷兰癌症研究所、剑桥大学、牛津大学、悉尼大学等组织共同开发。
* [Beehive LevelZero JNI](https://github.com/beehive-lab/levelzero-jni)：该项目是针对Intel LevelZero的Java本机接口(JNI)绑定，由曼彻斯特大学开源。

## 硬件操作

* [JCgroup](https://github.com/haosdent/jcgroup)：JCgroup是JVM上的Cgroup包装器，你可以使用该库来限制线程的CPU份额、磁盘I/O速度、网络带宽等。
* [NaturalMouseMotion](https://github.com/JoonasVali/NaturalMouseMotion)：该库提供了一种将光标可靠地移动到屏幕上指定坐标的方法，同时随机形成弧线，看起来就像真手使用鼠标将其移动到那里。
* [Webcam Capture](https://github.com/sarxos/webcam-capture)：该库允许你直接从Java使用内置或外部网络摄像头。
* [Picam](https://github.com/caprica/picam)：Picam是一个易于使用的开源Java库，用于访问Raspberry Pi相机模块。
* [PixelController](https://github.com/neophob/PixelController)：该应用程序的主要目标是创建一个易于使用的矩阵控制器软件。
* [Stream Pi Client](https://github.com/stream-pi/client)：免费、开源、模块化、跨平台和可编程宏垫。
* [EDSDK4J](https://github.com/kritzikratzi/edsdk4j)：这是Canon EOS数字软件开发套件EDSDK的Java包装器，可让你在Windows上完全访问Canon SLR相机。
* [Canon EOS SDK](https://github.com/Blackdread/canon-sdk-java)：Java版佳能EOS SDK。
* [ProviewR](http://www.proview.se/v3/)：ProviewR可能是世界上第一个用于过程控制和自动化的开源系统。
* [KWSwitch](https://gitee.com/kerwincui/kwswitch)：智能开关平台，包含服务端、硬件端、安卓端和前端。
* [Mixly](https://gitee.com/mixlyplus/Mixly)：Mixly是一款面向初学者、硬件编程爱好者的图形化编程工具。
* [Attach](https://github.com/gluonhq/attach)：Gluon Attach是一个解决端到端Java Mobile解决方案中与低级平台API集成的组件。
* [ZSmartSystems](https://github.com/zsmartsystems/com.zsmartsystems.zigbee)：该项目旨在提供一个用Java编写并与Android兼容的ZigBee兼容框架。
* [VisiCut](https://github.com/t-oster/VisiCut)：VisiCut是一个用户友好、独立于平台的工具，用于准备、保存作业并将其发送到激光切割机。
* [jSensors](https://github.com/profesorfalken/jSensors)：jSensors是一个监控电脑所有硬件传感器的Java库。
* [Java ONVIF](https://github.com/fpompermaier/onvif)：Java ONVIF库。
* [ONVIF Java Lib](https://github.com/milg0/onvif-java-lib)：ONVIF是一个社区，旨在规范基于IP的安全产品(如摄像头)之间的通信。
* [Twain4java](https://github.com/DenisLAD/twain4java)：Windows x86和x64的Java库。
* [TWAIN Java](https://github.com/dynarithmic/twain_library-java)：Dynarithmic TWAIN库的JNI新版本桥接器。

## 操作系统

* [JOS](https://sourceforge.net/projects/jos/)：JOS是一个免费且开源的基于Java的操作系统。
* [JNode](https://github.com/jnode/jnode)：JNode是一个开源项目以创建一个Java平台的操作系统。
* [JX](https://github.com/mczero80/jx)：JX是一个Java操作系统，专注于灵活和健壮的操作系统架构，由埃尔朗根大学开发。
* [JavaOS](https://zh.wikipedia.org/zh-cn/JavaOS)：JavaOS是一套操作系统，以JVM与一些基础软件组件所构成，由SUN公司开发。
* [MentraOS](https://github.com/Mentra-Community/MentraOS)：智能眼镜的开源操作系统。

## 运动规划

* [OWL](https://github.com/idsc-frazzoli/owl)：Java中的运动规划库，由苏黎世联邦理工学院开源。
* [RVO2 Java](https://github.com/snape/RVO2-Java)：最佳相互避免碰撞(ORCA)算法的Java实现，由北卡罗来纳大学开源。
* [SmoothPathPlanner](https://github.com/KHEngineering/SmoothPathPlanner)：平滑路径规划器。

## 自动规划

* [PDDL4J](https://github.com/pellierd/pddl4j)：PDDL4J的目的是促进基于PDDL语言(规划域描述语言)的自动化规划Java工具的开发，格勒诺布尔计算机科学实验室开源。
* [Neptus](https://github.com/LSTS/neptus)：Neptus是用于操作所有类型无人驾驶车辆的分布式指挥和控制基础设施，由波尔图大学开源。

## 电力系统

* [PowSyBl](https://github.com/powsybl/powsybl-core)：PowSyBl是一个用Java编写的开源框架，可以轻松编写用于电力系统仿真和分析的复杂软件。
* [SIMONA](https://github.com/ie3-institute/simona)：SIMONA提供了一个仿真工具箱，用于运行和实施大规模基于代理的电网仿真，重点关注配电网，由多特蒙德工业大学开源。
* [GXF](https://github.com/OSGP/open-smart-grid-platform)：GXF是一个支持公共空间硬件监控和控制的软件平台，由荷兰Alliander公司开源。
* [j60870](https://github.com/gythialy/j60870)：j60870是一个实现IEC 60870-5-104通信标准的库。
* [IEC](https://github.com/mujave/iec)：国家电网规约101/104协议解析与组装。
* [OperatorFabric](https://github.com/opfab/operatorfabric-core)：OperatorFabric是一个模块化、可扩展、工业强度的平台，用于电力、水和其他公用事业运营。
* [JoularJX](https://github.com/joular/joularjx)：JoularJX是一个基于Java的源代码级别电源监控代理，支持现代Java版本和多操作系统，以监控硬件和软件的功耗，由波城大学开源。
* [IEC61850bean](https://github.com/beanit/iec61850bean)：IEC61850bean是一个基于MMS映射实现IEC 61850标准的库，用于客户端和服务器通信。
* [IEC104 Microgrid](https://github.com/msun1996/IEC104_microgrid)：IEC104协议主站客户端程序，属于微电网管理系统一部分。
* [IEC104-1](https://github.com/huarda/IEC104-1)：用于与光伏之间进行通信。

## 量子计算

* [Strange](https://github.com/redfx-quantum/strange)：该项目定义了一个可用于创建量子程序的Java API。
* [iQuantum](https://github.com/Cloudslab/iQuantum)：iQuantum是用于量子计算环境建模和仿真的工具包，由墨尔本大学开源。
* [QuantumVITAS](https://github.com/quantumVITAS/quantumVITAS)：QuantumVITAS是专为从头计算模拟软件Quantum ESPRESSO设计的图形用户界面，旨在使从头计算模拟在各种操作系统中易于访问和直观控制。

## IPFS

* [Java IPFS HTTP Client](https://github.com/ipfs-shipyard/java-ipfs-http-client)：HTTP IPFS API的Java实现。
* [Mahuta](https://github.com/Consensys/Mahuta)：Mahuta是一个用于聚合和整合应用程序在IPFS网络上存储的文件或文档的库。
* [Nabu](https://github.com/Peergos/nabu)：IPFS的最小Java实现。
* [IPFS Cloud](https://gitee.com/doobo/ipfs-cloud)：IPFS Cloud是一个基于IPFS的星际文件系统，也是分布式的WebSocket服务端。

## 地理空间

* [GeoTools](https://github.com/geotools/geotools)：GeoTools是一个开源Java库，它提供符合标准的方法来操作地理空间数据，例如实现地理信息系统(GIS)，由英国利兹大学开源。
* [Gisgraphy](https://github.com/gisgraphy/gisgraphy)：Gisgraphy提供正向和反向地理编码、地理定位和车辆跟踪Web服务。
* [Apache SIS](https://github.com/apache/sis)：SIS是一个用于开发地理空间应用程序的Java语言库。
* [Geo Assist](https://github.com/thegeekyasian/geo-assist)：Geo Assist是一个开源Java库，旨在简化空间数据的处理过程。
* [GeoMesa](https://github.com/locationtech/geomesa)：GeoMesa是一套开源工具，可在分布式计算系统上进行大规模地理空间查询和分析。
* [Barefoot](https://github.com/bmwcarit/barefoot)：Barefoot是一个Java库，用于与OpenStreetMap进行在线和离线地图匹配，由宝马开源。
* [Mapsforge](https://github.com/mapsforge/mapsforge)：Mapsforge是一个Android、Java平台可用的地图库，支持OpenStreetMap地图数据的离线呈现。
* [SeaRoute](https://github.com/eurostat/searoute)：SeaRoute可以计算两个地点之间的最短海上路线，由欧盟统计局开源。
* [MrGeo](https://github.com/ngageoint/mrgeo)：MrGeo是一个地理空间工具包，旨在提供可大规模执行的基于栅格的地理空间功能，由美国国家地理空间情报局与DigitalGlobe合作开发。
* [NoiseModelling](https://github.com/Universite-Gustave-Eiffel/NoiseModelling)：NoiseModelling是一个能够生成噪声图的库，由古斯塔夫埃菲尔大学开源。
* [Spatial4j](https://github.com/locationtech/spatial4j)：Spatial4j是一个通用空间/地理空间开源Java库，其核心功能有三重：提供常见的地理空间感知形状，提供距离计算和其他数学运算，以及读取形状并将其写入字符串。
* [GeoIP2 Java](https://github.com/maxmind/GeoIP2-java)：GeoIP2 WebService客户端和数据库读取器的Java API。
* [GeoFire Java](https://github.com/firebase/geofire-java)：GeoFire是一个Java开源库，允许你根据地理位置存储和查询一组密钥，由Google开源。
* [GeoWave](https://github.com/locationtech/geowave)：GeoWave在Accumulo、HBase、BigTable、Cassandra、Kudu、Redis、RocksDB和DynamoDB之上提供地理空间和时间索引。
* [Geo Platform](https://github.com/geosdi/geo-platform)：Geo Plaform是一个开发富Web GIS应用程序的框架，由意大利国家研究委员会开源。
* [Geotoolkit](https://github.com/Geomatys/geotoolkit)：Geotoolkit是一个开源库，提供了操作制图数据的工具。
* [Spatial K](https://github.com/maplibre/spatial-k)：Spatial K是一组用于在Kotlin中处理地理空间数据的库。
* [Geocoding](https://github.com/bitlap/geocoding)：本项目旨在将不规范(或者连续)的文本地址进行尽可能的标准化，以及对两个地址进行相似度的计算。
* [GeoPackage Java](https://github.com/ngageoint/geopackage-java)：GeoPackage是开放地理空间联盟GeoPackage规范的Java实现，由美国国家地理空间情报局开源。
* [GeoJson Jackson](https://github.com/opendatalab-de/geojson-jackson)：GeoJson POJO Jackson，轻松序列化和反序列化对象。
* [GeoGig](https://github.com/locationtech/geogig)：GeoGig是一个地理空间分布式版本控制系统。
* [CLAVIN](https://github.com/Novetta/CLAVIN)：CLAVIN是一个开源软件包，用于文档地理解析和地理分辨率，采用基于上下文的地理实体分辨率。
* [JPX](https://github.com/jenetics/jpx)：JPX是一个Java库，用于创建、读取和写入GPX格式的GPS数据。
* [GoGPS](https://github.com/goGPS-Project/goGPS_Java)：goGPS是一个软件包，旨在通过相对定位提高低成本GPS设备的定位精度，由大阪市立大学维护。
* [Apache Sedona](https://github.com/apache/sedona)：Sedona是一种空间计算引擎，使开发人员能够在Spark和Flink等现代集群计算系统中轻松处理任何规模的空间数据，由亚利桑那州立大学开源。
* [H3-Java](https://github.com/uber/h3-java)：该库为H3核心库提供Java绑定，由Uber开源。
* [ElasticGeo](https://github.com/ngageoint/elasticgeo)：ElasticGeo提供了一个GeoTools数据存储，允许使用GeoServer通过OGC服务发布Elasticsearch索引中的地理空间特征，由美国国家地理空间情报局开源。
* [Unfolding](https://github.com/tillnagel/unfolding)：Unfolding是一个用Processing和Java创建交互式地图和地理可视化的库。
* [H2GIS](https://github.com/orbisgis/h2gis)：H2数据库的空间扩展，由法国Lab-STICC实验室内CNRS的GIS和信息科学领域的科学家和工程师领导。
* [OSHDB](https://github.com/GIScience/oshdb)：OpenStreetMap全历史数据的高性能时空数据分析平台，由海德堡大学开源。
* [OpenLR](https://github.com/tomtom-international/openlr)：OpenLR的参考实现。一种地图无关的动态位置定位方法。
* [Apache Baremaps](https://github.com/apache/incubator-baremaps)：Baremaps是一个工具包和一组用于创建、发布和操作在线地图的基础设施组件。
* [Wilayah Indonesia](https://github.com/yusufsyaifudin/wilayah-indonesia)：印度尼西亚行政地图。
* [CityGML4j](https://github.com/citygml4j/citygml4j)：CityGML4j是OGC CityGML的开源Java库和API。
* [GeoAPI](https://github.com/opengeospatial/geoapi)：GeoAPI为地理空间应用程序提供了一组Java和Python语言编程接口。
* [THREDDS Data Server](https://github.com/Unidata/tds)：TDS提供对科学数据集的元数据和数据访问，由美国国家科学基金会开源。
* [JGiscoTools](https://github.com/eurostat/JGiscoTools)：JGiscoTools是一个用于操作地理空间和统计数据的Java库，重点关注Eurostat和Eurostat-GISCO生成的欧洲数据，由欧盟统计局开源。
* [OpenMap](https://github.com/OpenMap-java/openmap)：OpenMap是一个基于Java Beans的工具包，用于构建需要地理信息的应用程序和Applet，由雷神公司开源。
* [MapLibre Tiles](https://github.com/maplibre/maplibre-tile-spec)：下一代矢量切片格式。
* [JavAPRSlib](https://github.com/ab0oo/javAPRSlib)：JavAPRSlib是一个用于解析和创建APRS数据包的Java库。
* [Mapbox Java SDK](https://github.com/mapbox/mapbox-java)：Mapbox Java SDK包含路线、地理编码以及更多可在Android或Java应用程序中使用的API。
* [GB2260.java](https://github.com/cn/GB2260.java)：查找中国行政区划的Java实现。
* [Trilateration](https://github.com/lemmingapex/trilateration)：使用非线性最小二乘优化器解决N维空间三边测量问题的公式。
* [Compass](https://github.com/jordond/compass)：Compass是一个Kotlin多平台库定位工具包。
* [PostGIS](https://github.com/postgis/postgis-java)：PostGIS的Java绑定及其他Java相关项目。

#### 坐标库

* [Proj4J](https://github.com/locationtech/proj4j)：Proj4J是一个用于在不同地理空间坐标参考系之间转换坐标的Java库，这是一个Eclipse基金会项目。
* [Timeshape](https://github.com/RomanIakovlev/timeshape)：Timeshape是一个Java库，可用于确定给定地理坐标属于哪个时区。
* [Proj4J](https://github.com/Proj4J/proj4j)：Proj4J是一个Java库，用于将点坐标从一个地理坐标系转换到另一个地理坐标系，包括基准面转换。
* [GeoGeometry](https://github.com/jillesvangurp/geogeometry)：GeoGeometry是一组用于处理地理哈希和具有地理坐标的几何形状的算法和函数。
* [Sunrise/SunsetLib Java](https://github.com/mikereedell/sunrisesunsetlib-java)：用于计算给定纬度/经度和日期组合的当地日出和日落的Java库。
* [RTree2D](https://github.com/plokhotnyuk/rtree2d)：RTree2D是二维不可变R树，用于平面和球面坐标中的超快速最近和相交查询。
* [Time Zone Map](https://github.com/dustin-johnson/timezonemap)：用于将位置或地区映射到时区的Java/Kotlin库。
* [IPDatabase](https://github.com/wzhe06/ipdatabase)：二叉树快速搜索IP地址数据库。
* [JMapProjLib](https://github.com/OSUCartography/JMapProjLib)：Java地图投影库，由俄勒冈州立大学开源。
* [PROJ JNI](https://github.com/OSGeo/PROJ-JNI)：PROJ C/C++库的Java原生接口。 

#### 经纬度库

* [Open Location Code](https://github.com/google/open-location-code)：Open Location Code是一种将位置编码为比纬度和经度更易于使用的形式的技术，由Google开源。
* [Geohash Java](https://github.com/kungfoo/geohash-java)：Geohashes的纯Java实现。
* [SimpleLatLng](https://github.com/JavadocMD/simplelatlng)：SimpleLatLng提供了一个简单、轻量级的库，可满足Java中常见的纬度和经度计算需求。
* [LatLongToTimezone](https://github.com/drtimcooper/LatLongToTimezone)：Java语言的经纬度到时区映射器。
* [GeoHash](https://github.com/GongDexing/Geohash)：GeoHash算法的简洁Java实现。
* [AddrParser](https://github.com/hsp8712/addrparser)：根据经纬度解析省市区信息的工具包。
* [JGeohash](https://github.com/astrapi69/jgeohash)：jGeohash是一个易于实现的库，可以帮助Java开发人员使用GeoHash算法根据自定义纬度和经度值创建地理编码。
* [IP2Location](https://github.com/ip2location/ip2location-java)：IP2Location组件允许用户查询IP地址以获取访问者的国家、地区、城市、ISP或公司名称等信息。
* [Geo](https://github.com/davidmoten/geo)：用于地理哈希的Java实用方法。
* [Location4j](https://github.com/tomaytotomato/location4j)：Location4j是一个简单的Java库，旨在高效、准确地查找国家、州和城市的地理数据。

#### GIS系统

* [GeoServer](https://github.com/geoserver/geoserver)：GeoServer是一个用Java编写的开源软件服务器，允许用户共享和编辑地理空间数据。
* [Deegree](https://github.com/deegree/deegree3)：Deegree是用于空间数据基础设施和地理空间网络的开源软件，由德国波恩大学地理系开发。
* [geOrchestra](https://github.com/georchestra/georchestra)：geOrchestra是一个完整的空间数据基础设施解决方案，由法国地理信息社区开源。
* [Photon](https://github.com/komoot/photon)：Photon是一个为OpenStreetMap数据构建的开源地理编码器。
* [Beast](https://bitbucket.org/bdlabucr/beast)：Beast是一个针对时空数据进行大型探索性分析的系统，支持矢量和栅格数据，具有多维数据类型和索引结构，由加州大学河滨分校开源。
* [SEPAL](https://github.com/openforis/sepal)：SEPAL是一个用于地理数据处理的云计算平台。
* [GeoWebCache](https://github.com/GeoWebCache/geowebcache)：GeoWebCache是一个用Java实现的图块缓存服务器，提供各种图块缓存服务，如WMS-C、TMS、WMTS、谷歌Maps、MS Bing等。
* [GeoNetwork](https://github.com/geonetwork/core-geonetwork)：GeoNetwork是一个用于管理空间参考资源的目录应用程序，它提供强大的元数据编辑和搜索功能以及交互式Web地图查看器，由OSGeo开源。
* [DHIS 2](https://github.com/dhis2/dhis2-core)：DHIS 2是一个灵活、基于Web的开源信息系统，具有出色的可视化功能，包括GIS、图表和数据透视表，由奥斯陆大学HISP中心开发。
* [GAF](https://gitee.com/supermapgaf/GAF)：SuperMap GAF基于SuperMap GIS基础软件进行研发，是连接GIS基础软件与行业应用的重要纽带。
* [Traccar](https://github.com/traccar/traccar)：Traccar是一个开源GPS跟踪系统，支持200多种GPS协议和2000多种GPS跟踪设备型号。
* [Planetiler](https://github.com/onthegomap/planetiler)：Planetiler是一种从OpenStreetMap等地理数据源生成矢量切片的工具。
* [Nunaliit](https://github.com/GCRC/nunaliit)：Nunaliit是一个用于创建交互式、数据驱动的网络地图集的系统，由卡尔顿大学地理信息学和制图研究中心(GCRC)的一个团队开发。
* [Mago 3DTiler](https://github.com/Gaia3D/mago-3d-tiler)：Mago 3DTiler是一款OGC 3D Tiles工具，由Gaia3D开源。
* [Reitti](https://github.com/dedicatedcode/reitti)：Reitti是一款全面的个人位置追踪和分析应用，可帮助你了解自己的活动模式和重要地点。
* [Mapton](https://github.com/trixon/mapton)：Mapton是一款在桌面上运行的易于使用的地图应用程序。
* [GeoPulse](https://github.com/tess1o/geopulse)：GeoPulse将来自OwnTracks、Overland、Dawarich或HomeAsssitant等跟踪应用程序的原始GPS数据转换为有组织的时间线和见解。

#### GIS GUI

* [WorldWind Java](https://github.com/NASAWorldWind/WorldWindJava)：WorldWind Java是NASA推出的一款开源的三维地球软件开发套件。
* [MeteoInfo](https://github.com/meteoinfo/MeteoInfo)：MeteoInfo是GIS应用(MeteoInfoMap)、科学计算和可视化环境(MeteoInfoLab)的集成框架，特别适合气象界，由中国气象局开源。
* [Map Download](https://gitee.com/CrimsonHu/java_map_download)：使用Java开发的地图瓦片图下载工具，支持OpenStreetMap、天地图、谷歌地图、高德地图、腾讯地图、必应地图的XYZ瓦片图下载与合并。
* [GpsPrune](https://github.com/activityworkshop/GpsPrune)：GpsPrune是一款基于地图的应用程序，用于查看、编辑和转换来自GPS系统的坐标数据。
* [OrbisGIS](https://github.com/orbisgis/orbisgis)：OrbisGIS是一个跨平台开源地理信息系统(GIS)，由法国Lab-STICC实验室内的CNRS领导。
* [Tinfour](https://github.com/gwlucastrig/Tinfour)：Tinfour是一个用Java编写的软件库，提供了用于构建和应用符合Delaunay准则的不规则三角网络(TIN)的工具。
* [G3M](https://github.com/glob3mobile/g3m)：G3M是一个开源的3D地理可视化引擎，专注于高效渲染大规模地理空间数据(如地图、地形、卫星影像等)。
* [OpenJUMP](https://github.com/openjump-gis/openjump)：OpenJUMP诞生于JUMP，JUMP是一个开源GIS，最初由Vividsolutions用Java开发，并由不列颠哥伦比亚省(加拿大)自然资源部资助。
* [Maxent](https://github.com/mrmaxent/Maxent)：Maxent是一个独立的Java应用程序，用于对物种地理分布进行建模，由美国自然历史博物馆开源。
* [McIDAS-V](https://github.com/mcidasv/mcidasv)：McIDAS-V是3D地球物理数据分析和可视化的免费开源软件，由威斯康星大学麦迪逊分校开发。

#### 大地测量

* [JAG3D](https://github.com/applied-geodesy/jag3d)：JAG3D是用于大地测量科学的最流行的开源最小二乘软件包之一，由斯坦拜斯转运中心开源。
* [Geodesy](https://github.com/mgavaghan/geodesy)：这是实现Thaddeus Vincenty算法的Java源代码，用于解决正向和逆向大地测量问题。
* [CTS](https://github.com/orbisgis/cts)：CTS是一个为使用众所周知的大地测量算法和参数集执行坐标变换而开发的库，由法国Lab-STICC实验室开源。
* [GeographicLib](https://github.com/geographiclib/geographiclib-java)：这是一个用于解决地球椭球模型上的大地测量问题的库。

## 路由引擎

* [GraphHopper](https://github.com/graphhopper/graphhopper)：OpenStreetMap的开源路由引擎，可以将其用作Java库或独立的Web服务器。
* [Openrouteservice](https://github.com/GIScience/openrouteservice)：具有大量功能的开源路线规划器API，由海德堡大学开源。
* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner)：OpenTripPlanner是一款开源多模式旅行规划器，专注于通过定期公共交通结合自行车、步行和移动服务(包括自行车共享和叫车)出行，由俄勒冈州波特兰市交通机构TriMet开源。
* [R5](https://github.com/conveyal/r5)：R5是Conveyal的路线引擎，Conveyal是一个基于Web的系统，允许用户创建交通场景并根据累积机会可达性指标对其进行评估。
* [R5R](https://github.com/ipeaGIT/r5r)：R5R是一个R软件包，用于在多式联运交通网络(步行、自行车、公共交通和汽车)上快速实现现实路线规划。
* [JOpt](https://dna-evolutions.com/products/#jopt-touroptimizer)：JOpt是一个用Java编写的灵活的路线优化引擎，可以解决受到严格限制的旅游优化问题，由DNA Evolutions公司开发。
* [Public Transport Enabler](https://github.com/schildbach/public-transport-enabler)：这是一个Java库，允许你从公共交通提供商获取数据。
* [OneBusAway](https://github.com/OneBusAway/onebusaway-application-modules)：OneBusAway应用程序套件的主要功能是通过各种界面与乘客共享实时公共交通信息。
* [MovSim](https://github.com/movsim/movsim)：MovSim是一款基于微观车道的交通模拟器，具有基于XML的配置和CSV文本输出。
* [MATSim](https://github.com/matsim-org/matsim-libs)：MATSim提供了一个工具箱来运行和实施大规模基于代理的运输模拟，由柏林工业大学开源。
* [EqaSim](https://github.com/eqasim-org/eqasim-java)：EqaSim包是用于基于代理和基于活动的传输模拟框架MATSim的准备运行的高质量场景的集合。
* [OpenTrafficSim](https://github.com/averbraeck/opentrafficsim)：OpenTrafficSim是一个多级交通模拟器，由代尔夫特理工大学开源。
* [RouteConverter](https://github.com/cpesch/RouteConverter)：RouteConverter是一款流行的开源工具，用于显示、编辑、丰富和转换路线、轨迹和航点。
* [MobiTopp](https://github.com/kit-ifv/mobitopp)：MobiTopp是卡尔斯鲁厄理工学院交通研究所开发的基于代理的出行需求模型。

## GTFS

* [OneBusAway GTFS](https://github.com/OneBusAway/onebusaway-gtfs-modules)：用于读取和写入GTFS源的Java库，包括数据库支持。
* [GTFS Realtime](https://github.com/MobilityData/gtfs-realtime-bindings)：根据GTFS Realtime协议缓冲区规范为流行语言生成的语言绑定。
* [GTFS Validator](https://github.com/MobilityData/gtfs-validator)：用于调度(静态)文件的规范GTFS验证器项目。
* [GTFS Validator](https://github.com/conveyal/gtfs-validator)：用于GTFS验证和统计的Java框架。
* [GTFS Lib](https://github.com/conveyal/gtfs-lib)：一个使用磁盘存储加载和保存任意大小的GTFS提要的库。

## 几何学

* [Apache Commons Geometry](https://github.com/apache/commons-geometry)：Commons Geometry项目提供几何类型和实用程序。
* [S2 Geometry Library](https://github.com/google/s2-geometry-library-java)：这是一个Google开源的用于操作几何形状的包，S2主要设计用于处理球面几何，即在球体上而不是在平面2D地图上绘制的形状。
* [Geolatte GeoM](https://github.com/GeoLatte/geolatte-geom)：符合OGC SQL简单功能规范的几何模型。
* [JGEX](https://github.com/yezheng1981/Java-Geometry-Expert)：JGEX是一款结合了动态几何软件、自动几何定理证明器(GTP)和视觉动态证明呈现方法的软件，由威奇托州立大学开源。
* [JTS](https://github.com/locationtech/jts)：JTS Topology是一个用于创建和操作向量几何的Java库。
* [PGS](https://github.com/micycle1/PGS)：Processing Geometry Suite是一个软件项目，它以Processing库的形式提供对2D几何算法的轻松访问。
* [Geometry API](https://github.com/Esri/geometry-api-java)：Esri几何API可用于在第三方数据处理解决方案中启用空间数据处理。
* [Campskeleton](https://github.com/twak/campskeleton)：Java中的加权直骨架实现。
* [GeoRegression](https://github.com/lessthanoptimal/GeoRegression)：GeoRegression是一个基于Java的免费几何库，用于机器人和计算机视觉等领域的科学计算，重点关注2D/3D空间。
* [Computational Geometry](https://github.com/mikhaildubov/computational-geometry)：该项目包含二维空间中基本计算几何算法的实现和可视化工具。
* [Polygon Contains Point](https://github.com/sromku/polygon-contains-point)：检查平面上的给定点位于多边形内、外还是边界上。
* [JTS2GeoJSON](https://github.com/bjornharrtell/jts2geojson)：此Java库可以将JTS几何体转换为GeoJSON格式，反之亦然。

## 航空航天

* [Sentinel Application Platform](https://github.com/senbox-org/snap-engine)：SNAP是欧洲航天局为Sentinel-1、Sentinel-2和Sentinel-3任务的科学开发而开发的三个Sentinel工具箱的通用软件平台。
* [Sentinel-1](https://github.com/senbox-org/s1tbx)：Sentinel-1 Toolbox是由欧空局开发的一款界面友好的开源SAR图像处理软件，它能够处理1级以及更高级的SAR数据。
* [Sentinel-2](https://github.com/senbox-org/s2tbx)：ESA Sentinel-2卫星上的MSI仪器的工具箱。
* [Sentinel-3](https://github.com/senbox-org/s3tbx)：用于ESA Sentinel-3卫星上的OLCI和SLSTR仪器的工具箱。
* [Trick](https://github.com/nasa/Trick)：Trick模拟环境由NASA约翰逊航天中心开发，是一个功能强大的模拟开发框架，使用户能够为航天器开发的所有阶段构建应用程序。
* [Orekit](https://github.com/CS-SI/Orekit)：Orekit是一个用Java编写的免费低级空间动力学库，它提供了基本元素(轨道、日期、姿态、框架...)以及处理它们的各种算法，由法国航天局开源。
* [NanoSat MO Framework](https://github.com/esa/nanosat-mo-framework)：NanoSat MO是基于CCSDS任务运营服务的纳米卫星软件框架，由格拉茨科技大学与欧洲航天局合作开发。
* [SBMT](https://sbmt.jhuapl.edu/)：SBMT是一种搜索、访问和分析小天体航天器数据的简单方法，由约翰霍普金斯大学应用物理实验室开发。
* [DERT](https://github.com/nasa/DERT)：DERT是一款开源软件工具，用于探索NASA的3D数字地形模型。
* [CCDD](https://github.com/nasa/CCDD)：CCDD是一款用于管理CFS和CFS应用程序的命令和遥测数据的软件工具，NASA开发。
* [SNAP Desktop](https://github.com/senbox-org/snap-desktop)：SNAP是欧洲航天局为光学和微波任务的科学开发而开发的三个工具箱的通用软件平台。
* [JMARS](https://jmars.mars.asu.edu/)：JMARS是由亚利桑那州立大学火星太空飞行设施开发的地理空间信息系统，旨在为NASA科学家、仪器团队成员、各个年龄段的学生和公众提供任务规划和数据分析工具。
* [EarthSci](https://github.com/GeoscienceAustralia/earthsci)：用于地球科学可视化的Eclipse RCP平台，基于NASA WorldWind Java SDK构建。
* [Gaia Sky](https://codeberg.org/gaiasky/gaiasky)：Gaia Sky是一款实时3D宇宙应用程序，由海德堡大学开源。
* [DSTE](https://ai-solutions.com/dste/)：DSTE是一个交互式软件包，具有创新可视化功能的多体轨迹设计技术，可显著减少轨迹设计所花费的时间，被约翰逊航天中心用作设计工具。
* [JHelioviewer](https://github.com/Helioviewer-Project/JHelioviewer-SWHV)：JHelioviewer是基于JPEG 2000图像压缩标准的太阳物理数据可视化工具，由ESA/NASA开源。
* [Java Astrodynamics Toolkit](https://sourceforge.net/projects/jat/)：JAT是一个开源软件组件库，用于用Java或Matlab编写的航天应用程序，该软件由NASA使用，是德克萨斯大学计算机科学系的主要合作项目。
* [IDV](https://github.com/Unidata/IDV)：IDV是一个用于分析和显示地球科学数据的框架，由美国国家科学基金会Unidata开源。
* [Aerie](https://github.com/NASA-AMMOS/aerie)：Aerie是一个用于航天器建模的软件框架，NASA开源。
* [Orbdetpy](https://github.com/ut-astria/orbdetpy)：Orbdetpy是一个Python轨道确定库，航天先进科学技术研究(ASTRIA)开源。
* [Yamcs](https://github.com/yamcs/yamcs)：Yamcs是一个用Java开发的任务控制框架。
* [CCSDS](https://github.com/dariol83/ccsds)：CCSDS协议和格式的Java开源实现。
* [ProsEO](https://github.com/dlr-eoc/prosEO)：ProsEO软件系统是一个开源处理控制系统，旨在执行处理地球观测卫星数据(例如Sentinel数据)所需的所有活动，根据配置的任务生成用户级数据、工程数据和/或内部遥测数据，由德国航空航天中心开发。
* [Aladin](http://aladin.cds.unistra.fr/aladin.gml)：Aladin是一款广泛使用的Java工具，能够解决诸如定位目标数据、访问和探索分布式数据集以及可视化多波长数据等挑战，由法国斯特拉斯堡数据中心开发。
* [XTCETools](https://gitlab.com/dovereem/xtcetools)：XTCE工具包提供了本机Java库和基于该库的图形用户界面，以支持OMG XML遥测和命令交换(XTCE)标准。

## 天文学

* [SolarPositioning](https://github.com/klausbrunner/solarpositioning)：SolarPositioning是一个用于查找地心太阳坐标的Java库。
* [Nom.Tam.Fits](https://github.com/nom-tam-fits/nom-tam-fits)：Nom.Tam.Fits是一个功能齐全、快速、100%纯Java 8+库，用于读取、写入和修改FITS文件，最初起源于NASA，目前由哈佛大学维护。
* [Astro4j](https://github.com/melix/astro4j)：Java天文图像处理库和应用程序的集合。
* [Predict4Java](https://github.com/davidmoten/predict4java)：Predict4Java提供实时卫星跟踪和轨道预测信息。
* [JSOFA](https://github.com/Javastro/jsofa)：JSOFA是国际天文学联合会的C SOFA软件库的纯Java版本，由曼彻斯特大学开源。
* [AstroLib](https://mhuss.com/AstroLib/docs/Overview.html)：Java天文算法库。
* [Commons Suncalc](https://github.com/shred/commons-suncalc)：用于计算太阳和月亮位置和相位的Java库。
* [Kastro](https://github.com/yoxjames/Kastro)：Kastro是一个Kotlin多平台库，用于计算月亮和太阳的天文事件。
* [Debian Astro Java](https://blends.debian.org/astro/tasks/java)：用于天文学的Java包集合。
* [JSky](https://jsky.sourceforge.net/)：JSky项目的目标是构建一套用于天文学的可复用Java组件，最初源于欧洲南方天文台的Skycat应用程序的开发。
* [Simple Astronomy Lib](https://github.com/SimpleAstronomy/simple-astronomy-lib)：一个用于计算月相的简单且免费的天文学库。
* [Geocalc](https://github.com/grumlimited/geocalc)：Geocalc是一个简单的Java库，用于处理地球坐标的运算。
* [GUSTO](https://github.com/esa/GUSTO)：GUSTO是用于空间天文学的Java库，由欧洲航天局开源。
* [Starlink Java](https://github.com/Starlink/starjava)：星链项目是一个长期运行的英国项目，支持天文数据处理，现在由东亚天文台维护。

## 水文学

* [SOS](https://github.com/52North/SOS)：SOS提供了一个可互操作的基于Web的界面，用于插入和查询传感器数据和传感器描述。
* [Unidata AWIPS](https://github.com/Unidata/awips2)：AWIPS是一个气象软件包，它用于解码、显示和分析数据，最初由雷神公司为国家气象局(NWS)开发。
* [OpenDCS](https://github.com/opendcs/opendcs)：水文/气象数据开放数据采集系统。
* [Vortex](https://github.com/HydrologicEngineeringCenter/Vortex)：Vortex是针对水文工程中心应用程序的数据处理实用程序的集合，例如HEC-HMS、HEC-RAS。
* [SeaDAS](https://github.com/seadas/seadas)：SeaDAS软件由NASA开发，专门用于海洋水色数据的处理、可视化、分析和质量保证。

## 地震学

* [Swarm](https://github.com/usgs/swarm)：Swarm是一款用于实时显示和分析地震波形的Java应用程序，由美国地质调查局开源。
* [GlobalQuake](https://github.com/xspanger3770/GlobalQuake)：GlobalQuake是一款实验性的Java应用，旨在近乎实时地显示全球地震。
* [JQuake](https://jquake.net/en/)：JQuake是一款日本开发的免费软件，可以帮助监控实时地震事件。
* [OpenSHA](https://github.com/opensha/opensha)：OpenSHA是一个基于Java的开源平台，用于进行地震危险性分析，由南加州大学开源。
* [SeisFile](https://github.com/crotwell/seisFile)：SeisFile是一个用Java读写地震文件格式的库。
* [TauP](https://github.com/crotwell/TauP)：TauP工具包是一款地震走时计算器，由南卡罗来纳大学开源。
* [NSHMP Lib](https://code.usgs.gov/ghsc/nshmp/nshmp-lib)：NSHMP Lib是美国地质调查局开发的Java库，支持概率地震危险性(PSHA)和相关分析。

## 物理库

* [Rebound](https://github.com/facebookarchive/rebound)：Rebound是一个模拟弹簧动力学的Java库，由Facebook开源。
* [SICMUtils](https://github.com/sicmutils/sicmutils)：Scmutils系统的Clojure实现，用于Clojure和ClojureScript语言中的数学和物理研究。
* [FreeHEP](https://java.freehep.org/)：FreeHEP库的目标是鼓励高能物理领域Java代码的共享和重用，由SLAC国家加速器实验室开源。
* [NeqSim](https://github.com/equinor/neqsim)：NeqSim是一个用于估计流体特性和流程设计的Java库，由挪威科技大学开源。

## 无人机

* [RosettaDrone](https://github.com/RosettaDrone/rosettadrone)：RosettaDrone是一个用于开发和测试DJI无人机软件的框架。
* [MAVGCL](https://github.com/ecmnet/MAVGCL)：这个基于JavaFX的工具使PX4用户能够根据PX4Logs或ULogs记录和分析飞行期间或离线时通过UDP发布的数据。
* [MAVLink](https://github.com/dronefleet/mavlink)：用于MAVLink通信的Java API。
* [DJI Cloud API](https://github.com/dji-sdk/DJI-Cloud-API-Demo)：Cloud API基于业界标准的MQTT、HTTPS、Websocket协议，对无人机业务功能集充分抽象，隔离了复杂的无人机底层业务逻辑，大疆开源。
* [OpenAMASE](https://github.com/afrl-rq/OpenAMASE)：OpenAMASE是用于模拟多无人机任务的项目，由空军研究实验室、航空航天系统局、动力和控制部门开发。
* [MAVLinkJava](https://github.com/ghelle/MAVLinkJava)：用于MAVLink的Java代码生成器和Java库。
* [MAVLink Kotlin](https://github.com/divyanshupundir/mavlink-kotlin)：适用于Kotlin多平台的现代MAVLink库。
* [MAVSDK Java](https://github.com/mavlink/MAVSDK-Java)：Java的MAVSDK客户端。
* [DroneDetour](https://github.com/xumeng367/DroneDetour)：DroneDetour是一个基于Java的库，并提供Android演示，它实现了一种智能无人机绕行路径规划算法。
* [Drone Route Path](https://github.com/originDoris/drone-route-path)：本项目是一个专业的无人机航线规划算法库，主要用于无人机摄影测量任务的路径规划。

## AIS库

* [AISmessages](https://github.com/tbsalling/aismessages)：AISmessages是一种基于Java的轻量级、零依赖、超高效消息解码器，用于符合ITU 1371(NMEA装甲AIS消息)的海上导航和安全消息。
* [AisLib](https://github.com/dma-ais/AisLib)：AisLib是一个用于处理AIS消息的Java库，由丹麦海事局开源。
* [Java Marine API](https://github.com/ktuukkan/marine-api)：Java Marine API是一个NMEA 0183解析器库，用于对各种电子海洋设备(例如GPS、回声测深仪和气象仪器)提供的数据进行解码和编码。
* [Risky](https://github.com/amsa-code/risky)：用于分析带有时间戳的位置数据的工具，例如来自AIS的船舶位置报告。

## 转换库

* [Apache Commons Convert](https://commons.apache.org/sandbox/commons-convert)：Commons Convert是一个专用于将一种类型的对象转换为另一种类型的库。
* [TypeMap](https://github.com/YunaBraska/type-map)：TypeMap和TypeConverter是一个动态、可扩展、高性能的类型转换库，原生支持GraalVM。
* [Joda Convert](https://github.com/JodaOrg/joda-convert)：Joda Convert是一个小型的、高度集中的库，提供对象和字符串之间的往返转换。
* [Type Parser](https://github.com/drapostolos/type-parser)：解析字符串并将其转换为另一种类型，支持所有适用的Java库类。

## IO库

* [Apache Commons IO](https://github.com/apache/commons-io)：Commons IO库包含实用程序类、流实现、文件过滤器、文件比较器、字节序转换类等等。
* [Okio](https://github.com/square/okio)：Okio是一个补充java.io和java.nio的库，使你可以更轻松地访问、存储和处理数据，由Square开源。
* [Kotlinx IO](https://github.com/Kotlin/kotlinx-io)：Kotlinx IO是一个多平台的Kotlin库，提供基本的IO原语。
* [Plexus IO](https://github.com/codehaus-plexus/plexus-io)：Plexus IO是一组Plexus组件，设计用于I/O操作。
* [Jaydio](https://github.com/smacke/jaydio)：Jaydio是一个Java库，可让程序员更好地控制文件I/O，部分方法是绕过操作系统缓冲区高速缓存。
* [PerfIO](https://github.com/szeiger/perfio)：PerfIO为二进制和文本数据提供缓冲流式I/O抽象。
* [Chronicle Bytes](https://github.com/OpenHFT/Chronicle-Bytes)：Chronicle Bytes的用途与Java的NIO ByteBuffer类似，但具有一些附加功能。
* [Kdio](https://github.com/lexburner/kdio)：一个使用非常简单的Java Direct IO框架。
* [FastJavaIO](https://github.com/williamfiset/FastJavaIO)：非常快的Java输入读取器。
* [Rsync4j](https://github.com/fracpete/rsync4j)：适用于Linux、OSX和Windows的rsync的简单Java包装器。
* [Jayo](https://github.com/jayo-projects/jayo)：Jayo是一个基于java.io的JVM同步I/O库，这会产生简单、可读和可调试的代码，就像标准的阻塞程序一样，但它在幕后执行非阻塞I/O。
* [Iota](https://github.com/thebusby/iota)：Iota是一个用于处理内存中大型文本文件的Clojure库。
* [KmpIO](https://github.com/skolson/KmpIO)：这是一个Kotlin多平台库，用于基础文本文件、二进制文件和zip/archive文件IO。

## 文件监听

* [FSWatch](https://github.com/vorburger/ch.vorburger.fswatch)：基于java.nio.file.WatchService监控目录或单个文件的Java库。
* [Directory Watcher](https://github.com/gmethvin/directory-watcher)：适用于JDK 8+的目录监视实用程序，旨在为Linux、macOS和Windows提供准确且高效的递归监视。
* [Play File Watch Library](https://github.com/playframework/play-file-watch)：这是Play文件监视库，它可用于以独立于平台的方式监视文件。
* [Kfswatch](https://github.com/irgaly/kfswatch)：Kotlin多平台文件系统观察器库。
* [RxFileWatcher](https://github.com/helmbold/rxfilewatcher)：RxFileWatcher允许你使用RxJava Observable对象来观察目录(递归或非递归)中的文件系统事件。
* [JNotify](https://jnotify.sourceforge.net/)：JNotify是一个Java库，允许Java应用程序监听文件系统事件。

## 目录库

* [AppDirs](https://github.com/harawata/appdirs)：AppDirs是一个小型Java库，它提供了平台相关的特殊文件夹/目录的路径。
* [Wildcard](https://github.com/EsotericSoftware/wildcard)：Wildcard是一个小型Java库，用于执行文件和目录的高效模式匹配。
* [Directories](https://github.com/dirs-dev/directories-jvm)：Directories是一个提供配置/缓存/数据路径的小型库，遵循Linux、MacOS、BSD和Windows上的相应约定。

## RSS

* [ROME](https://github.com/rometools/rome)：ROME是一个用于RSS和Atom提要的Java框架。
* [Huntly](https://github.com/lcomplete/huntly)：Huntly是一个信息管理工具，它不仅可以自托管，也可以通过客户端在本地运行。
* [CommaFeed](https://github.com/Athou/commafeed)：受Google Reader启发而开发的自托管RSS阅读器，基于Dropwizard和React/TypeScript。
* [Android RSS](https://github.com/ahorn/android-rss)：用于解析RSS 2.0提要的轻量级Android库。
* [Sismics Reader](https://github.com/sismics/reader)：Reader是一个开源的、基于Web的聚合器，通过Web Feeds(RSS、Atom)提供内容。
* [RSSOwl](https://github.com/rssowl/RSSOwl)：RSS Owl是一款功能强大的应用程序，可以以舒适的方式组织、搜索和阅读你的RSS、RDF和Atom新闻提要。
* [RSS Reader](https://github.com/w3stling/rssreader)：RSS Reader是一个用于读取RSS和Atom提要的简单Java库。
* [RSS Parser](https://github.com/prof18/RSS-Parser)：RSS Parser是一个用于解析RSS和Atom提要的Kotlin多平台库，支持Android、iOS和JVM。
* [ROME](https://github.com/rometools/rome)：ROME是一个用于RSS和Atom提要的Java框架。
* [Huntly](https://github.com/lcomplete/huntly)：Huntly是一个信息管理工具，它不仅可以自托管，也可以通过客户端在本地运行。
* [CommaFeed](https://github.com/Athou/commafeed)：受Google Reader启发而开发的自托管RSS阅读器，基于Dropwizard和React/TypeScript。
* [Android RSS](https://github.com/ahorn/android-rss)：用于解析RSS 2.0提要的轻量级Android库。
* [Sismics Reader](https://github.com/sismics/reader)：Reader是一个开源的、基于Web的聚合器，通过Web Feeds(RSS、Atom)提供内容。
* [RSSOwl](https://github.com/rssowl/RSSOwl)：RSS Owl是一款功能强大的应用程序，可以以舒适的方式组织、搜索和阅读你的RSS、RDF和Atom新闻提要。
* [RSS Parser](https://github.com/prof18/RSS-Parser)：RSS Parser是一个用于解析RSS和Atom提要的Kotlin多平台库，支持Android、iOS和JVM。
* [ANI RSS](https://github.com/wushuo894/ani-rss)：基于RSS自动追番、订阅、下载。
* [Android RSS Reader Library](https://github.com/matshofman/Android-RSS-Reader-Library)：RSS读取器库，用于从网络获取RSS提要并将其解析为可操作的对象。
* [ParseRSS](https://github.com/muhrifqii/ParseRSS)：ParseRSS是一个用于Android平台RSS解析的库。
* [Simplistic RSS](https://github.com/ShirwaM/Simplistic-RSS)：这是一个非常简单的Android RSS库。
* [KtRssReader](https://github.com/ivanisidrowu/KtRssReader)：KtRssReader是一个用于解析RSS提要的Kotlin库。

## SSE

* [Okhttp EventSource](https://github.com/launchdarkly/okhttp-eventsource)：基于OkHttp的Java SSE客户端实现。
* [OkSse](https://github.com/heremaps/oksse)：OkSse是OkHttp的扩展库，用于创建SSE客户端。
* [Turbine](https://github.com/Netflix/Turbine)：Turbine是一种用于将SSE JSON数据流聚合到单个流中的工具，由Netflix开源。
* [SSE-EventBus](https://github.com/ralscha/sse-eventbus)：EventBus库，用于使用SSE将事件从Spring应用程序发送到Web浏览器。
* [RxSSE](https://github.com/EnricSala/RxSSE)：适用于Android和Java应用程序的SSE客户端。

## EPC

* [EPCIS](https://github.com/JaewookByun/epcis)：Oliot EPCIS 2.2.0是电子产品代码信息服务(EPCIS) v2.0的原型实现，能够捕获和共享GS1批准的标准化事件/主数据，由韩国世宗大学开源。
* [OpenEPCIS](https://github.com/openepcis)：OpenEPCIS是GS1 EPCIS标准的开源完全兼容实现，它还提供了许多开源项目、工具和工件。
* [EPCtagCoder](https://github.com/jlcout/epctagcoder)：EPCtagCoder是一个极其直观、小型且超快的Java EPC编码和解码库。

## FMI

* [FMI4j](https://github.com/NTNU-IHB/FMI4j)：FMI4j是一个用Kotlin编写的软件包，用于处理功能模型单元(FMU)，由挪威科技大学开源。
* [JavaFMI](https://bitbucket.org/siani/javafmi)：JavaFMI是一组与功能模型接口FMI配合使用的组件。

## OSGI

* [Apache Karaf](https://github.com/apache/karaf)：Karaf提供了一个轻量级的OSGi容器，可以用于部署各种组件。
* [OPS4j Pax Web](https://github.com/ops4j/org.ops4j.pax.web)：Pax Web通过更好的Servlet支持、过滤器、监听器、错误页面和JSP等扩展了OSGi HTTP服务，以满足最新版本的Servlet规范。
* [Bnd](https://github.com/bndtools/bnd)：Bnd是用于构建OSGi包的工具，包括Eclipse、Maven和Gradle插件。
* [OSGi enRoute](https://github.com/osgi/osgi.enroute)：OSGi enRoute项目提供了OSGi应用程序的编程模型，该项目包含为OSGi enRoute基本配置文件提供API的捆绑包和用于OSGi enRoute项目的捆绑包。
* [Apache Aries](https://github.com/apache/aries)：Aries项目由一组可插拔Java组件组成，支持企业OSGi应用程序编程模型。
* [Apache Felix](https://github.com/apache/felix-dev)：Felix项目是一些半相关的OSGi子项目的集合，这些子项目可以单独构建和发布。
* [Eclipse Equinox](https://eclipse.dev/equinox/)：Equinox是OSGi核心框架规范的实现，这是一组实现各种可选OSGi服务和其他用于运行基于OSGi的系统的基础设施的捆绑包。
* [Eclipse Virgo](https://projects.eclipse.org/projects/rt.virgo)：Virgo Web Server是一个完全基于模块的Java应用程序服务器，旨在以高度的灵活性和可靠性运行企业Java应用程序和Spring驱动的应用程序，由VMware开发。
* [OSGi Testing](https://github.com/osgi/osgi-test)：该项目提供了一组捆绑包，其中包含用于测试OSGi API的有用类。

## RAML

* [RAML Java Parser](https://github.com/raml-org/raml-java-parser)：这是RAML解析器的官方Java实现，适用于1.0和0.8版本。
* [RAML JAX-RS](https://github.com/mulesoft-labs/raml-for-jax-rs)：RAML JAX-RS的目标是提供一组工具来与这些技术协同工作，以便能够基于现有的RAML API定义(代码生成)构建Java + JAX-RS应用程序，或者基于现有的Java + JAX-RS应用程序(文档)生成RAML API定义。
* [Raml Tester](https://github.com/nidi3/raml-tester)：测试请求/响应是否与给定的RAML定义匹配。

## OData

* [OData](https://github.com/RWS/odata)：这是基于OData标准的Tridion开放数据框架，完全用Java实现。
* [Apache Olingo](https://github.com/apache/olingo-odata4)：Apache Olingo是一个围绕OData规范的Java库及扩展，由SAP开源。

## 海关

* [GTAS](https://github.com/US-CBP/GTAS)：GTAS是用于提高边境安全的网络应用程序，它使政府机构能够在高风险航空旅客计划旅行之前自动识别他们，由美国海关和边境保护局开源。
* [China E-Port Data Signature](https://github.com/julxxy/chinaport-data-signature)：该项目为中国电子口岸海关总署XML报文和海关179数据上报加签服务，提供一站式的免费解决方案，开箱即用。

## 蓝牙

* [BLE Indoor Positioning](https://github.com/neXenio/BLE-Indoor-Positioning)：BLE Indoor Positioning是一个Java库，能够根据从蓝牙信标接收的广播数据包估算位置。
* [Bluetooth Manager](https://github.com/sputnikdev/bluetooth-manager)：用于管理蓝牙适配器、蓝牙设备、GATT服务和特性的库/框架。
* [BlueCove](https://sourceforge.net/projects/bluecove/)：Bluecove是Java的跨平台蓝牙库，最初由英特尔研究院开发。
* [LiteBle](https://github.com/litesuits/android-lite-bluetoothLE)：Android低功耗蓝牙便捷操作框架，基于回调。
* [SmartGattLib](https://github.com/movisens/SmartGattLib)：SmartGattLib是一个Java库，可简化与蓝牙SMAR设备的协作。
* [Bluez DBus](https://github.com/hypfvieh/bluez-dbus)：使用DBus和Bluez的Linux操作系统蓝牙库。

## 校验

* [Jakarta Validation](https://github.com/jakartaee/validation)：Jakarta Validation为JavaBean和方法验证定义了元数据模型和API。
* [Hibernate Validator](https://github.com/hibernate/hibernate-validator)：Hibernate Validator是Jakarta Bean Validation的参考实现。
* [Apache BVal](https://github.com/apache/bval)：这是Jakarta EE和Java SE的Java Bean Validation(JSR 303、349、380)规范的实现。
* [Fluent Validator](https://github.com/neoremind/fluent-validator)：Fluent Validator通过利用流式接口风格和JSR 303 Bean Validation规范，提供了轻松支持验证的功能。
* [YAVI](https://github.com/making/yavi)：YAVI是一种基于Lambda的Java类型安全验证框架。
* [RAVE](https://github.com/uber-archive/rave)：RAVE使用Java注解处理来利用模型类中已有的注解(Nullness、Value Constraint、Typedef)来提高运行时的安全性，Uber开源。
* [Valiktor](https://github.com/valiktor/valiktor)：Valiktor是一种类型安全、强大且可扩展的流式DSL，用于验证Kotlin中的对象。
* [Apache Commons Validator](https://github.com/apache/commons-validator)：Commons Validator为客户端验证和服务器端数据验证提供构建块。
* [Java Fluent Validator](https://github.com/mvallim/java-fluent-validator)：Java Fluent Validator在Java语言中定义了一个内部DSL供程序员使用。
* [Coody Verification](https://gitee.com/coodyer/coody-verification)：Coody Verification是一款参数自动化校验工具。
* [JBVE](https://github.com/nomemory/java-bean-validation-extension)：JBVE是一个小型工具库，它通过额外注解扩展了Java Bean Validation规范。
* [Collection Validator](https://github.com/jirutka/validator-collection)：该库可以轻松地为任何验证约束创建“伪约束”来标注简单类型的集合，而无需为每个集合编写额外的验证器或不必要的包装类。
* [dOOv](https://github.com/doov-org/doov)：dOOv是一个用于类型安全域模型验证和映射的流式API。
* [Avaje Validator](https://github.com/avaje/avaje-validator)：通过APT源代码生成进行无反射POJO验证的Java库。
* [OVal](https://github.com/sebthom/oval)：OVal是一个实用且可扩展的验证框架，适用于任何类型的Java对象，可以使用注解(@NotNull、@MaxLength)、POJO或XML来声明约束。
* [Functional Validation](https://github.com/MAIF/functional-validation)：该库提供了工具来验证Bean并组合验证堆栈错误。
* [Vador](https://github.com/salesforce-misc/Vador)：Vador是一个现代验证框架，旨在简化和提高REST API验证，由Salesforce开源。
* [SpEL Validator](https://github.com/stick-i/spel-validator)：SpEL Validator是基于Spring EL的参数校验包，也是javax.validation的扩展增强包，用于简化参数校验。
* [Smart Validator](https://gitee.com/fetech-framework/smart-validator)：轻量级服务端校验框架。
* [Konform](https://github.com/konform-kt/konform)：Kotlin的可移植校验库。
* [Akkurate](https://github.com/nesk/akkurate)：Akkurate是一个利用Kotlin表达能力的校验库。
* [Parsix](https://github.com/parsix/parsix)：高级解析，以确保你的输入满足业务逻辑所需的所有约束。
* [ValidateTor](https://github.com/nisrulz/validatetor)：用于快速简单的字符串校验的Android库。

## IPP

* [JIPP](https://github.com/HPInc/jipp)：IPP的Java兼容实现，由惠普开源。
* [Cups4j](https://github.com/harwey/cups4j)：CUPS的Java打印库。
* [IPP Client Kotlin](https://github.com/gmuth/ipp-client-kotlin)：适用于Java和Kotlin的IPP协议客户端实现。

## OSC

* [JavaOSC](https://github.com/hoijui/JavaOSC)：JavaOSC赋予JVM语言程序以OSC内容格式序列化、解析、发送和接收数据的能力。
* [OSCP5](https://github.com/sojamo/oscp5)：Java和Processing的OSC实现。

## CalDAV

* [CalDAV4j](https://github.com/caldav4j/caldav4j)：CalDAV4j是一个实现CalDAV协议的Java库。
* [Cosmo](https://github.com/mam-dev/cosmo)：Cosmo日历服务器实现了CalDAV协议的服务器端。

## WebDav

* [Sardine](https://github.com/lookfirst/sardine)：Sardine可用于与WebDAV服务器交互，并且与FTP相比，以编程方式管理远程文件要容易得多。
* [Jackrabbit WebDAV](https://jackrabbit.apache.org/jcr/components/jackrabbit-webdav-library.html)：该组件提供用于构建WebDAV服务器或客户端的接口和常用实用程序类。
* [Dav4JVM](https://github.com/bitfireAT/dav4jvm)：Dav4JVM是用于JVM(Java/Kotlin)的WebDAV/CalDAV/CardDAV库，它最初是为DAVx⁵开发的。
* [Milton](https://github.com/miltonio/milton2)：可在Windows、Mac、Linux、Android和iOS上运行的Milton Java WebDAV/CalDAV/CardDAV服务器库。
* [Webdav Caiyun](https://github.com/VGEAREN/webdav-caiyun)：中国移动和彩云WebDAV。

## AirPlay

* [Open AirPlay](https://github.com/openairplay/open-airplay)：Apple的AirPlay协议的库集合。
* [Java AirPlay Lib](https://github.com/serezhka/java-airplay-lib)：此库旨在轻松创建类似Apple TV的AirPlay2服务器。

## Unicode

* [AnyAscii](https://github.com/anyascii/anyascii)：AnyAscii为几乎所有Unicode字符提供纯ASCII替换字符串。
* [JUnidecode](https://github.com/gcardone/junidecode)：JUnidecode是用于将Unicode转换到ASCII的Java库。
* [Unidecode](https://github.com/xuender/unidecode)：Java的Unicode字符串的ASCII音译库。

## 表情库

* [Emoji](https://github.com/delight-im/Emoji)：支持Java和Android的Emoji和表情符号。
* [Emoji Java](https://github.com/vdurmont/emoji-java)：Emoji Java是一个轻量级的Java库，可帮助你在Java应用程序中使用表情符号。
* [EmojiOne](https://github.com/joypixels/emojione)：该项目包括用于将表情符号转换为各种格式的库，包括转换为EmojiOne表情符号图像。
* [Emoji4j](https://github.com/kcthota/emoji4j)：用于将短代码、HTML实体转换为表情符号的Java库，还支持解析表情符号、代理HTML实体。
* [Java Emoji Converter](https://github.com/binarywang/java-emoji-converter)：Emoji转换工具，便于各种规格客户端生成的Emoji字符串转换成另外一种格式。
* [Emoji](https://github.com/vanniktech/Emoji)：Kotlin多平台库，用于向Android应用程序/JVM后端添加表情符号支持。
* [Emoji Java](https://github.com/coding/emoji-java)：Emoji Java是一个轻量级的Java库，可帮助你在Java应用程序中使用表情符号，由腾讯Coding开源。
* [JEmoji](https://github.com/felldo/JEmoji)：JEmoji是一个轻量级且快速的Java表情符号库，包含来自unicode联盟的所有表情符号的完整列表。
* [EmojiReader](https://github.com/YvesCheung/EmojiReader)：EmojiReader是一个能在字符串中识别出Emoji的简单工具。
* [Lightbend Emoji](https://github.com/lightbend-labs/lightbend-emoji)：Lightbend Emoji是Java的Unicode处理的包装器。

## 字体库

* [Aspose.Font](https://products.aspose.com/font/java/)：Aspose.Font使你能够轻松加载、保存、绘制、转换和渲染字体文件。
* [SFNTly](https://github.com/googlefonts/sfntly)：使用、编辑和创建基于SFNT的字体的库，由Google开源。
* [FontBox](https://github.com/apache/pdfbox/tree/trunk/fontbox)：FontBox库是一个用于处理PDF字体的开源Java工具。

## 语言库

* [TinyPinyin](https://github.com/promeG/TinyPinyin)：适用于Java和Android的快速、低内存占用的汉字转拼音库。
* [Pinyin4j](https://github.com/belerweb/pinyin4j)：支持汉字(简体和繁体)到最流行的拼音系统，包括汉语拼音、通用拼音、Wade-Giles、MPS2、Yale和Gwoyeu Romatzyh。
* [Opencc4j](https://github.com/houbb/opencc4j)：Opencc4j支持中文繁简体转换，考虑到词组级别。
* [Pinyin](https://github.com/houbb/pinyin)：Java高性能中文转拼音工具，支持同音字。
* [Pinyin Plus](https://github.com/taptap/pinyin-plus)：汉字转拼音库，支持多音字，由Taptap开源。
* [PinyinSearchLibrary](https://github.com/handsomezhou/PinyinSearchLibrary)：PinyinSearch库是一个Java库，为T9搜索和Qwerty搜索提供数据解析方法、数据匹配方法等。
* [Bopomofo4j](https://gitee.com/rnkrsoft/Bopomofo4j)：Bopomofo4j是一个零依赖、纯Java开发的汉字转拼音库。
* [JPinyin](https://github.com/qzw1210/jpinyin)：JPinyin是一个汉字转拼音的Java开源类库，在PinYin4j的功能基础上做了一些改进。
* [PinIn](https://github.com/Towdium/PinIn)：PinIn是一个用于解决各类汉语拼音匹配问题的Java库。
* [Moji4J](https://github.com/andree-surya/moji4j)：Moji4J是一个开源Java库，用于在日语平假名、片假名和罗马字脚本之间进行转换。
* [Myanmar Tools](https://github.com/google/myanmar-tools)：该项目包括用于处理缅甸使用的字体编码的工具，目前支持广泛的Zawgyi-One字体编码，由Google开源。
* [Jakaroma](https://github.com/nicolas-raoul/jakaroma)：Java汉字/等到罗马字转换器。
* [JCorrector](https://github.com/jiangnanboy/jcorrector)：JCorrector中文文本纠错工具。

## 敏感词过滤

* [ToolGood.Words](https://github.com/toolgood/ToolGood.Words)：一款高性能非法词(敏感词)检测组件，附带繁体简体互换，支持全角半角互换等功能。
* [Sensitive Word](https://github.com/houbb/sensitive-word)：基于DFA算法实现的高性能敏感词工具。
* [Sensitive Word Filter](https://github.com/hailin0/sensitive-word-filter)：简易敏感词处理器，支持返回敏感词、高亮敏感词、替换敏感词等操作。
* [Sensitive Words Filter](https://github.com/hooj0/sensitive-words-filter)：敏感词过滤项目，提供TTMP、DFA、DAT、Hash Bucket、Tire算法支持过滤。
* [DzFilter](https://github.com/fanhua1994/DzFilter)：使用DFA算法实现的敏感词过滤。
* [BadWordFiltering](https://github.com/VaneProject/bad-word-filtering)：此库可识别并处理脏话、粗俗语言及其他语言。
* [KeywordFilter](https://github.com/k5h9999/keywordfilter)：基于分词原理修改写的一个过滤敏感词库，可以改成动态，支持返回敏感词，高亮敏感词，替换敏感词等操作。

## 国际化

* [CLDR](https://github.com/unicode-org/cldr)：CLDR为支持世界语言的软件提供了关键构建块，拥有最大、最广泛的可用区域设置数据标准存储库，由Unicode Consortium开源。
* [Java Locales](https://github.com/spotify/java-locales)：集中并标准化Java组件中Unicode区域设置的使用的库，由Spotify开发。
* [L10nMessages](https://github.com/pinterest/l10nmessages)：L10nMessages是一个使Java应用程序的国际化(i18n)和本地化(l10n)变得简单且安全的库，由Pinterest开源。
* [NV-1i8n](https://github.com/TakahikoKawasaki/nv-i18n)：支持国际化的包，包含ISO 3166-1国家代码枚举、ISO 639-1语言代码枚举、ISO 15924脚本代码枚举等。
* [Mojito](https://github.com/box/mojito)：Mojito是一个持续本地化平台，依靠持续集成将所有软件字符串收集到一处，实时查看哪些产品需要本地化。
* [Tolgee](https://github.com/tolgee/tolgee-platform)：Tolgee是一个本地化平台，允许你将应用程序翻译成任何语言，而无需修改代码。
* [Humanize](https://github.com/mfornos/humanize)：Humanize是一种Java工具，用于为数据添加国际化。
* [Tradukisto](https://github.com/allegro/tradukisto)：Tradukisto是一个强大的Java库，旨在将数字转换为相应的单词表示形式，由Allegro开源。
* [Kilt](https://github.com/hupfdule/kilt)：Kilt是一组小工具，用于简化Java i18n资源包的处理。
* [ICU4j](https://github.com/unicode-org/icu)：ICU4j为软件应用提供Unicode和国际化支持，由IBM开源。
* [Gettext](https://github.com/jgettext/gettext-commons)：Gettext Commons项目为国际化(i18n)通过GNU gettext和Java实现资源包。
* [Cosmopolitan](https://github.com/rodionmoiseev/c10n)：一个Java库，专注于使国际化更加模块化、更易于发展和维护、易于更改且IDE友好，无需过多的外部工具。
* [Easy I18N](https://github.com/awkay/easy-i18n)：这是一个Java库，旨在使创建国际化程序变得更加容易。
* [Resource4j](https://github.com/resource4j/resource4j)：Resource4j库是Java ResourceBundle机制的替代品，支持大型和遗留应用程序的复杂i18n场景，并提供对键/值应用程序配置和任意资源文件的安全访问。
* [Loc4J](https://loc4j.sourceforge.net/)：Loc4J是一个Java库，可帮助本地化应用程序。
* [I18N4k](https://github.com/comahe-de/i18n4k)：I18N4k是一个Kotlin多平台(JVM、JS、Native)库和代码生成器，用于在你的程序中处理国际化。
* [OmegaT](https://github.com/omegat-org/omegat)：OmegaT是一款免费开源多平台计算机辅助翻译工具，具有模糊匹配、翻译记忆库、关键字搜索、术语表以及翻译到更新项目中的功能。
* [Singleton](https://github.com/vmware/singleton)：Singleton是一个用于简化软件全球化的开源应用程序，由VMWare开源。

## 翻译库

* [MTrans](https://github.com/hujingshuang/MTrans)：MTrans提供了集多种主流的在线翻译及TTS功能于一身的轻量级服务。
* [Zanata](https://github.com/zanata/zanata-platform)：Zanata是一个基于Web的系统，供翻译人员使用Web浏览器在线翻译文档和软件。
* [Translator](https://github.com/therealbush/translator)：适用于Kotlin/JVM和Java的简单且免费的Google翻译库。
* [DeepL Java](https://github.com/DeepLcom/deepl-java)：DeepL API是一种语言翻译API，它允许其他计算机程序将文本和文档发送到DeepL的服务器并接收高质量的翻译。
* [Google API Translate Java](https://github.com/richmidwinter/google-api-translate-java)：提供一个简单、非官方的Java客户端API来使用Google翻译。
* [Microsoft Translator Java API](https://github.com/boatmeme/microsoft-translator-java-api)：提供一个围绕Microsoft Translator API的Java包装器。
* [Lokalized](https://github.com/lokalized/lokalized-java)：Lokalized有助于在JVM上进行听起来自然的软件翻译。
* [AT4J](https://github.com/brenoepics/at4j)：AT4J是Azure Translator API的Java封装库。

## 字幕库

* [Subtitle](https://github.com/noophq/subtitle)：将字幕从一种格式转换为另一种格式，支持格式STL EBU、TTML SMI、VTT、SRT。
* [SubtitleConverter](https://github.com/JDaren/subtitleConverter)：这是一个处理字幕格式并转换成其他格式的Java框架。
* [SRTParser](https://github.com/gusthavosouza/SRTParser)：SRTParser是处理SRT文件、图例文件所需的库。
* [DualSub](https://github.com/bonigarcia/dualsub)：DualSub是一个工具，可以让你在一个文件中合并两个SRT字幕。

## 字典库

* [Mdict Java](https://github.com/KnIfER/mdict-java)：用于Java的Mdict字典文件格式的查询库。
* [ExtJWNL](https://github.com/extjwnl/extjwnl)：ExtJWNL是一个用于创建、读取和更新WordNet格式词典的Java API。
* [Stardict4j](https://codeberg.org/miurahr/stardict4j)：Stardict4j是Java版StarDict词典文件的访问库。

## 颜色库

* [Color Java](https://github.com/ngageoint/color-java)：Color是一个Java库，提供颜色表示，支持十六进制、RBG、算术RBG、HSL和整数颜色，由美国国家地理空间情报局开发。
* [Color](https://github.com/bowbahdoe/color)：JVM的颜色库。
* [Color.kt](https://github.com/kdrag0n/colorkt)：Color.kt是适用于Kotlin Multiplatform和Java的现代色彩科学库。
* [Android Random Color](https://github.com/uknownothingsnow/AndroidRandomColor)：Android随机颜色生成器库。

## 短链接

* [ShortLink](https://github.com/Enndfp/short-link)：SaaS短链接系统，为企业和个人用户提供了一个高效、安全和可靠的短链接管理平台。
* [Octopus](https://github.com/zjcscut/octopus)：Octopus是一个长链接压缩为短链接的服务。
* [URLShorter](https://gitee.com/tinyframework/urlshorter)：满足多种场景下的短链接生成需求。
* [URL Shortener](https://github.com/cami-la/url-shortener-preview)：URL Shortener是一个提供URL缩短服务的项目。
* [UrlShortener API](https://github.com/marinsborg/UrlShortener-API)：Url Shorter是一项在消息、Twitter、演示文稿等中共享URL时将长URL转换为短别名以节省空间的服务。

## 单位库

* [UnitOf](https://github.com/Digidemic/UnitOf)：适用于Java、JavaScript和C#的测量和数据类型转换库。
* [Indriya](https://github.com/unitsofmeasurement/indriya)：JSR 385参考实现。
* [Alchemist](https://github.com/kevincianfarini/alchemist)：管理物理单位，灵感来自kotlin.time.Duration。
* [Unit API](https://github.com/unitsofmeasurement/unit-api)：Unit API提供了一组用于处理单位和数量的Java语言编程接口。
* [Byte Units](https://github.com/JakeWharton/byteunits)：用于在SI和IEC字节单位和位单位粒度之间进行转换的实用程序类。
* [Byte Size](https://github.com/saket/byte-size)：用于表示SI和IEC字节和位的单位。
* [Measured](https://github.com/nacular/measured)：Measured提供了一种安全且简单的使用测量单位的方法。
* [QUDTLib](https://github.com/qudtlib/qudtlib-java)：QUDTLib为Java提供单位转换及相关功能。
* [UNITILITY](https://github.com/pjazdzyk/unitility)：适用于Java的计量单位和物理量转换器，支持Spring Boot和Quarkus，可用于Web应用开发。

## 调用图

* [AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder)：一个能让你了解所有函数调用顺序以及函数耗时的Android库。
* [Java CallGraph](https://github.com/Adrninistrator/java-all-call-graph)：Java CallGraph能够通过静态分析的方式批量生成指定Java方法向下的完整调用链。
* [Java CallGraph](https://github.com/gousiosg/java-callgraph)：一套用于在Java中生成静态和动态调用图的程序。
* [Spring Project Tree](https://github.com/onblog/ProjectTree)：基于AOP开发的一款方法调用链分析框架。

## 语言检测

* [Language Detection](https://github.com/shuyo/language-detection)：这是一个用纯Java实现的语言检测库。
* [Language Detector](https://github.com/optimaize/language-detector)：Java语言检测库。
* [JLangDetect](https://github.com/melix/jlangdetect)：JLangDetect是JVM的语言检测库。

## 解析库

这里列出了语法、表达式、SQL等解析库。

#### 词法解析

* [ANTLR](https://github.com/antlr/antlr4)：ANTLR是一个强大的解析器生成器，用于读取、处理、执行或翻译结构化文本或二进制文件。
* [SableCC](https://github.com/SableCC/sablecc)：SableCC是一个解析器生成器，它能够生成功能齐全的面向对象框架，用于构建编译器、解释器和其他文本解析器，由麦吉尔大学开发。
* [JavaParser](https://github.com/javaparser/javaparser)：该项目包含一组实现具有高级分析功能的Java 1.0 - Java 17解析器的库。
* [Flexmark Java](https://github.com/vsch/flexmark-java)：Flexmark Java是CommonMark(规范0.28)解析器的Java实现，使用块优先、内联后Markdown解析架构。
* [Kotlinx.AST](https://github.com/kotlinx/ast)：Kotlinx.AST是一个通用的AST解析库，Kotlin是目前唯一支持的语言。
* [PartiQL Lang Kotlin](https://github.com/partiql/partiql-lang-kotlin)：PartiQL是一种富有表现力的、与SQL兼容的查询语言，可以访问关系型、半结构化和嵌套数据，由Amazon开源。
* [Gumtree Spoon AST Diff](https://github.com/SpoonLabs/gumtree-spoon-ast-diff)：使用Gumtree算法计算两个Spoon抽象语法树之间的AST差异。
* [JavaCC](https://github.com/javacc/javacc)：JavaCC是用于Java应用程序的最流行的解析器生成器，最初由Sun开发。
* [JFlex](https://github.com/jflex-de/jflex)：JFlex是Java的词法分析器生成器(也称为扫描器生成器)。
* [JCPP](https://github.com/shevek/jcpp)：JCPP是C预处理器的完整、兼容、独立、纯Java实现。
* [JLex](https://www.cs.princeton.edu/~appel/modern/java/JLex/)：JLex是一个用Java编写的词法分析器生成器，由普林斯顿大学开发。
* [RSQL Parser](https://github.com/jirutka/rsql-parser)：RSQL是一种用于对RESTful API中的条目进行参数化过滤的查询语言。
* [Parboiled](https://github.com/sirthias/parboiled)：Parboiled是一个混合Java/Scala库，提供基于解析表达式语法(PEG)的轻量级且易于使用但功能强大且优雅的任意输入文本解析。
* [CUP](http://www2.cs.tum.edu/projects/cup/)：CUP是Java的一个LALR解析器生成器，慕尼黑工业大学开发。
* [Parrot](https://github.com/daniellansun/groovy-parser)：Parrot可以解析Groovy源代码并构造相关的AST，与旧解析器生成的AST几乎相同。
* [Canopy](https://github.com/jcoglan/canopy)：Canopy是一个针对Java、JavaScript、Python和Ruby的解析器编译器。
* [CongoCC](https://github.com/congo-cc/congo-parser-generator)：Congo Parser Generator是一个递归下降解析器生成器，可生成Java、Python和C#代码。
* [Pika Parser](https://github.com/lukehutch/pikaparser)：Pika解析器参考实现。
* [Grammatica](https://github.com/cederberg/grammatica)：Grammatica是一款Java解析器生成器。
* [Kolasu](https://github.com/Strumenta/kolasu)：Kolasu提供使用Kotlin构建自定义、可能可变的抽象语法树(AST)的基础设施。
* [Kastree](https://github.com/cretz/kastree)：Kastree是一个简单的库，用于将Kotlin源代码作为一组AST对象进行操作。
* [Despector](https://github.com/Despector/Despector)：一个Java/Kotlin反编译工具和AST库。
* [YAJCo](https://github.com/kpi-tuke/yajco)：YAJCo是一款基于注解模型的语言解析器生成器。

#### 表达式引擎

* [Aviator](https://code.google.com/archive/p/aviator/)：Aviator是一个高性能、轻量级的基于Java实现的表达式引擎，它动态地将String类型的表达式编译成Java字节码并交给JVM执行，Google开源。
* [Apache Commons JEXL](https://github.com/apache/commons-jexl)：Commons JEXL库是Java共生表达式语言的实现。
* [AviatorScript](https://github.com/killme2008/aviatorscript)：AviatorScript是一门高性能、轻量级寄宿于JVM(包括Android平台)之上的脚本语言。
* [JSEL](https://code.google.com/archive/p/lite/wikis/JSEL.wiki)：JSEL是一个兼容JavaScript运算规则的简单表达式解释引擎。
* [ACE4J](https://javacalculationengine.com/)：ACE4J是由Crystal Prism Software开发的Java库，旨在无需实际的Excel文件即可执行类似Excel的公式。
* [EsProc](https://github.com/SPLWare/esProc)：EsProc SPL是一种用于数据处理的脚本语言，具有精心设计的丰富的库函数和强大的语法，可以通过JDBC接口在Java程序中执行并独立计算，由SPLWare开源。
* [IK Expression](https://code.google.com/archive/p/ik-expression/)：IK Expression是一个开源、可扩展、基于Java语言开发的一个超轻量级的公式化语言解析执行工具包。
* [FastEL](https://github.com/dbcxy/fast-el)：轻量级的高效表达式计算引擎。
* [QLExpress](https://github.com/alibaba/QLExpress)：QLExpress是一种强大的、轻量级的、动态的Java平台语言，旨在提高开发人员在不同业务场景中的生产力，阿里开源。
* [MVEL](https://github.com/mvel/mvel)：MVEL是一种混合动态/静态类型、可嵌入的表达式语言和Java平台运行时。
* [BeanShell](https://github.com/beanshell/beanshell)：Beanshell是一个小型、免费、可嵌入的Java源解释器，具有对象脚本语言功能。
* [Magic Script](https://gitee.com/ssssssss-team/magic-script)：Magic Script是一款基于JVM的脚本语言。
* [Recognizers Text](https://github.com/microsoft/Recognizers-Text)：Microsoft.Recognizers.Text提供对数字、单位和日期/时间等实体的强大识别和解析。
* [OGNL](https://github.com/orphan-oss/ognl)：OGNL代表对象图导航语言，它是一种用于获取和设置Java对象属性的表达式语言。
* [Formula](https://github.com/salesforce/formula-engine)：可重用公式引擎的实现，具有JavaScript和SQL生成以及Salesforce批准的语法。
* [SpEL](https://github.com/spring-projects/spring-framework)：SpEL是一种功能强大的表达式语言，支持在运行时查询和操作对象图。
* [Janino](https://github.com/janino-compiler/janino)：Janino是一个超小、超快的Java编译器。
* [JUEL](https://github.com/beckchr/juel)：JUEL是统一表达语言(EL)的实现，指定为JSP 2.1标准(JSR-245)的一部分，已在JEE5中引入。
* [FEEL](https://github.com/camunda/feel-scala)：由Camunda用Scala编写的FEEL引擎。
* [Liquor](https://gitee.com/noear/liquor)：Java动态编译、表达式、脚本工具。
* [Cucumber Expressions](https://github.com/cucumber/cucumber-expressions)：Cucumber Expressions是正则表达式的替代品，具有更直观的语法。
* [CEL Java](https://github.com/google/cel-java)：CEL是一种非图灵完备语言，旨在简单、快速、安全和可移植，由Google开发。
* [Grammaticus](https://github.com/salesforce/grammaticus)：Grammaticus是一个语法引擎，允许用户重命名名词，同时保持内容的语法正确，由Salesforce开源。
* [CEL-Java](https://github.com/projectnessie/cel-java)：通用表达式语言的Java实现。
* [Eclipse Expressly](https://github.com/eclipse-ee4j/expressly)：Expressly实现了Jakarta Expression Language，这是一种用于Java应用程序的表达式语言。
* [JFireEL](https://gitee.com/eric_ds/jfireEL)：快速的EL表达式解析器，支持丰富的EL表达式。
* [Crunch](https://github.com/boxbeam/Crunch)：快速的Java表达式编译器/评估器。
* [SimpleEL](https://github.com/alibaba/simpleel)：SimpleEL是阿里开发的简单表达式语言。
* [JBool Expressions](https://github.com/bpodgursky/jbool_expressions)：JBool Expressions是一个简单的开源库，用于在Java中创建和操作布尔表达式。
* [Tweakflow](https://github.com/twineworks/tweakflow)：Tweakflow为JVM应用程序提供了一种以类似公式的符号来评估用户提供的表达式的方法。
* [Starscript](https://github.com/MeteorDevelopment/starscript)：Java的快速文本格式化语言。
* [JQuick Java](https://github.com/paohaijiao/jquick-java)：JQuick Java是一种轻量级类Java脚本语言，专为简洁高效的编程而设计。

#### 数学表达式

* [Exp4j](https://github.com/fasseg/exp4j)：Exp4j是用于Java编程语言的小型数学表达式计算器。
* [Keval](https://github.com/notKamui/Keval)：用于数学表达式字符串求值的Kotlin迷你库。
* [ExprK](https://github.com/Keelar/ExprK)：ExprK是一个用于Kotlin和Java的简单数学表达式评估器。
* [EvalEx](https://github.com/ezylang/EvalEx)：EvalEx是一个方便的Java表达式计算器，它允许评估简单的数学和布尔表达式。
* [Javaluator](https://github.com/fathzer/javaluator)：Javaluator是一个简单、功能强大的Java中缀表达式计算器。
* [Parsington](https://github.com/scijava/parsington)：Parsington是一个中缀到后缀和中缀到语法树表达式解析器，用于用Java编写的数学表达式。
* [MathParser](https://github.com/mariuszgromada/MathParser.org-mXparser)：MathParser是一个超级简单、丰富且高度灵活的数学表达式解析器库，适用于Java、Android、.NET、TypeScript和JavaScript。
* [Parsii](https://github.com/scireum/parsii)：用Java编写的数学表达式的超级快速且简单的计算器。
* [ParserNG](https://github.com/gbenroscience/ParserNG)：ParserNG是一个功能强大的开源数学工具，可以解析和评估代数表达式。
* [Paralithic](https://github.com/PolyhedralDev/Paralithic)：Paralithic是一个用于解析和评估数学表达式的库。
* [Jep](https://www.singularsys.com/index.html)：Jep Java是一个用于解析和计算数学表达式的库。
* [Expression Parser](https://slovesnov.users.sourceforge.net/index.php?parser)：Expression Parser是sin(pi/4)等字符串的解析器，它使用C++、JavaScript、Java、PHP语言实现。
* [Mathematical Expression](https://github.com/BeardedManZhao/mathematical-expression)：本框架是一种针对数学公式解析的有效工具，能够解析包含嵌套函数，包含函数，数列步长累加等数学公式。
* [Expr](https://github.com/darius/expr)：该包解析并评估浮点数的数学表达式。
* [Expression Parser](https://github.com/javalc6/Expression-Parser)：一个用于Java数学和布尔表达式递归的下降式解析器。

#### 正则表达式

* [RegexGenerator](https://github.com/MaLeLabTs/RegexGenerator)：该项目包含用于生成文本提取正则表达式的工具的源代码。
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)：VerbalExpressions是一个Java库，可帮助构建困难的正则表达式。
* [Generex](https://github.com/mifmif/Generex)：用于生成与给定正则表达式匹配的字符串的Java库。
* [RE2/J](https://github.com/google/re2j)：RE2是一个正则表达式引擎，其运行时间与输入的大小成线性关系，由Google开源。
* [Joni](https://github.com/jruby/joni)：Oniguruma正则表达式库的Java端口。
* [Hyperscan Java](https://github.com/gliwka/hyperscan-java)：Hyperscan是一个高性能的多正则表达式匹配库。
* [DRegex](https://github.com/marianobarrios/dregex)：DRegex是一个Java库，它使用确定性有限自动机(DFA)实现正则表达式引擎。
* [Readable Regex](https://github.com/ricoapon/readable-regex)：这个库使用构建器模式来创建正则表达式。
* [Readable Regex](https://github.com/codebox/readable-regex)：该库提供了一种使Java代码中的复杂正则表达式更具可读性的方法。
* [RgxGen](https://github.com/curious-odd-man/RgxGen)：根据正则表达式模式生成匹配和不匹配的字符串。
* [JRegex](https://sourceforge.net/projects/jregex/)：JRegex是一个Java正则表达式库。
* [RegExodus](https://github.com/tommyettinger/RegExodus)：正则表达式库，可跨Java变体移植。
* [Xeger](https://github.com/agarciadom/xeger)：Xeger是一个用于生成与特定正则表达式匹配的字符串的Java库。
* [OpenRegex](https://github.com/knowitall/openregex)：OpenRegex是一种高效灵活的基于标记的正则表达式语言和引擎，由华盛顿大学开源。
* [Regex Builder](https://github.com/sgreben/regex-builder)：Regex Builder库是作为java.util.regex的轻量级包装器实现的。
* [Needle](https://github.com/hyperpape/needle)：Needle是JVM的一个非常快速的正则表达式库。
* [Regex](https://github.com/xindoo/regex)：Java实现的正则表达式引擎。

#### SQL解析器

* [SQLSolver](https://github.com/SJTU-IPADS/SQLSolver)：SQLSolver是一个查询等效性验证器，由上海交通大学、耶鲁大学、纽约大学和普林斯顿大学的研究人员开发。
* [JSqlParser](https://github.com/JSQLParser/JSqlParser)：JSqlParser是一个与RDBMS无关的SQL语句解析器，它将SQL语句转换为可遍历的Java类层次结构。
* [SQL Parser](https://www.sqlparser.com/sql-parser-java.php)：SQL Parser提供了对各种数据库的SQL脚本的深入和详细分析，这是一个付费产品。
* [ElasticSearch SQL](https://github.com/iamazy/elasticsearch-sql)：使用Antlr4将SQL解析为ElasticSearch DSL。
* [Superior SQL Parser](https://github.com/melin/superior-sql-parser)：基于Antlr 4的多种数据库SQL解析器。
* [M-SqlParser](https://gitee.com/M-SQLParse/M-SqlParser)：M-SqlParser解析SQL语句并将其转换为Java类的层次结构。
* [JSQLTranspiler](https://github.com/starlake-ai/jsqltranspiler)：JSQLTranspiler是一个纯Java独立的SQL转译器、列和谱系解析器，用于将各种大型RDBMS SQL方言转换为一些较小的RDBMS方言，以便进行单元测试。
* [BigBash](https://github.com/Borisvl/bigbash)：BigBash是一个SQL解析器，可以将select语句转换为Bash的单行语句。

#### 解析器组合器

* [JParsec](https://github.com/jparsec/jparsec)：Jparsec是一个为Java编写的递归下降解析器组合器框架。
* [Autumn](https://github.com/norswap/autumn)：Autumn是一个Java解析器组合器库。
* [Better Parse](https://github.com/h0tk3y/better-parse)：一个不错的解析器组合器库，适用于Kotlin JVM、JS和多平台项目。
* [ParsecJ](https://github.com/jon-hanson/parsecj)：ParsecJ是一个用于构建LL(1)解析器的Java单子解析器组合器框架。
* [Java PetitParser](https://github.com/petitparser/java-petitparser)：PetitParser结合了无扫描器解析、解析器组合器、解析表达式语法(PEG)和Packrat解析器的思想，将语法和解析器建模为可以动态重新配置的对象。
* [Jar Jar Parse](https://github.com/BjoernLoetters/Jar-Jar-Parse)：Jar Jar Parse是一个轻量级库，专为Java中的解析器快速原型设计而设计。
* [Mug Dot Parse](https://github.com/google/mug/tree/master/dot-parse)：低程序的Java解析器组合器，适合日常一次性解析任务。

#### 源代码解析

* [Roaster](https://github.com/forge/roaster)：Roaster是一个可以轻松解析和格式化Java源文件的库。
* [JRecordBind](https://github.com/ffissore/jrecordbind)：JRecordBind是小型且超快的定长文件读取器/解析器。

#### 手机号解析

* [LibPhoneNumber](https://github.com/google/libphonenumber)：Google的通用Java、C++和JavaScript库，用于解析、格式化和验证国际电话号码。
* [PhoneNumber Geo](https://github.com/fengjiajie/phone-number-geo)：手机号码归属地本地解析Java实现。
* [PhoneNumber Geo](https://github.com/EeeMt/phone-number-geo)：根据手机号确定手机号运营商即归属地，支持包括虚拟运营商的中国大陆手机号查询。
* [PhoneNumber](https://github.com/xdtianyu/PhoneNumber)：一个获取号码归属地和其他信息(诈骗、骚扰等)的开源库。
* [PhoneNumber Normalizer](https://github.com/telekom/phonenumber-normalizer)：使用PhoneNumber Normalizer库，你可以将电话号码标准化为E164格式和国家格式，同时考虑到德国号码计划的特定复杂性，由德国电信开源。

#### Cron解析

* [Cron Utils](https://github.com/jmrozanec/cron-utils)：CronUtils是一个Java库，用于定义、解析、验证、迁移Cron以及获取人类可读的描述。
* [Cron Parser](https://github.com/grahamar/cron-parser)：将Cron表达式转换为人类可读字符串的Java库。
* [Nlp2cron](https://gitee.com/huoyo/nlp2cron)：Nlp2cron是一个将自然语言转换为Cron表达式的工具包。

#### Tree Sitter

* [Tree Sitter Java](https://github.com/tree-sitter/tree-sitter-java)：Tree-Sitter的Java语法。
* [Java Tree Sitter](https://github.com/serenadeai/java-tree-sitter)：Tree-Sitter是一个解析器生成工具和增量解析库。
* [Java Tree Sitter](https://github.com/seart-group/java-tree-sitter)：Tree-Sitter的Java绑定，由瑞士卢加诺的意大利大学软件研究所开源。
* [Tree Sitter NG](https://github.com/bonede/tree-sitter-ng)：下一代Tree Sitter Java绑定。
* [JSitter](https://github.com/JetBrains/jsitter)：JVM的Tree-Sitter API，由JetBrains开源。

## 形式验证

* [CATG](https://github.com/ksen007/janala2)：Concolic单元测试引擎，使用形式化方法自动生成单元测试。
* [JKind](https://github.com/loonwerks/jkind)：JKind是基于SMT的Lustre安全属性无限状态模型检查器，由柯林斯航空航天公司开源。
* [Asmeta](https://github.com/asmeta/asmeta)：Asmeta是抽象状态机(ASM)形式化方法的框架，它由用于执行不同验证和确认活动的不同工具组成，米兰大学开源。
* [PRISM](https://github.com/prismmodelchecker/prism)：PRISM是一个概率模型检查器，用于对表现出随机或概率行为的系统进行形式化建模和分析，由牛津大学开源。
* [Checker Framework](https://checkerframework.org/)：可插拔类型系统，包括空类型、物理单位、不变性类型等等。
* [Daikon](https://github.com/codespecs/daikon)：检测可能的程序不变量并根据这些不变量生成JML规范，由华盛顿大学开源。
* [Java PathFinder](https://github.com/javapathfinder/jpf-core)：JVM形式验证工具，包含模型检查器等，由NASA开源。
* [JmlOk2](https://massoni.computacao.ufcg.edu.br/home/jmlok)：通过反馈引导的随机测试生成来检测代码和JML规范之间的不一致，并建议检测到的每个不符合项的可能原因，由大坎皮纳联邦大学开发。
* [jCUTE](https://github.com/osl/jcute)：jCUTE自动生成Java程序的单元测试，Concolic执行将随机具体执行与符号执行和自动约束求解相结合。
* [Event-B](https://www.event-b.org/index.html)：Event-B是一种用于系统级建模和分析的形式化方法，由苏黎世联邦理工学院、杜塞尔多夫海因里希海涅大学、纽卡斯尔大学和南安普顿大学开发和维护。
* [KeY](https://github.com/KeYProject/key)：形式化软件开发工具，旨在尽可能无缝地集成面向对象软件的设计、实现、形式化规范和形式化验证，由卡尔斯鲁厄理工学院开源。
* [OpenJML](https://github.com/OpenJML/OpenJML)：Java程序的程序验证工具，可让你检查以Java建模语言注释的程序规范。
* [Java Modeling Language](https://www.cs.ucf.edu/~leavens/JML/index.shtml)：JML是一种行为接口规范语言，可用于指定Java模块的行为，佛罗里达大学开发。
* [Theta](https://github.com/ftsrg/theta)：Theta是布达佩斯技术经济大学关键系统研究组开发的通用、模块化和可配置的模型检查框架，旨在支持基于抽象细化的算法的设计和评估，以进行各种形式主义的可达性分析。

## 印章生成

* [SealKit](https://gitee.com/liuzy1988/SealKit)：印章生成工具。
* [SealUtil](https://github.com/localhost02/SealUtil)：印章生成工具，使用Java Graphics2D生成各类圆形/椭圆公章、私章图片。
* [开放签](https://gitee.com/kaifangqian/kaifangqian-base)：开放签提供企业印章制作、证书签发、文件签署API接口服务。
* [iText GM](https://gitee.com/capki/iText-GM)：iText5国密PDF电子签章，基于《GB/T 38540-2020安全电子签章规范》开发。

## 代码生成器

* [Auto](https://github.com/google/auto)：Java源代码生成器的集合，由Google开发。
* [Joda Beans](https://github.com/JodaOrg/joda-beans)：Joda Beans提供了一个小型框架，用于向Java添加属性。
* [Burningwave](https://github.com/burningwave/core)：Burningwave Core是一个先进、免费的开源Java框架构建库，它可用于扫描类路径、在运行时生成类、促进反射的使用、扫描文件系统、执行字符串化的源代码、并行迭代集合或数组、并行执行任务等等。
* [JavaPoet](https://github.com/square/javapoet)：JavaPoet是一个用于生成源文件的Java API，由Square开源。
* [Java::Geci](https://github.com/verhas/javageci)：Java::Geci是一个用于生成Java代码的库。
* [Wsilk](https://github.com/wuba/wsilk)：Wsilk是一个辅助开发人员的代码生成框架，由58同城开源。
* [AutoRecord](https://github.com/pawellabaj/auto-record)：AutoRecord是一个代码生成器，可以帮助你轻松生成Java记录。
* [AutoParcel](https://github.com/frankiesardo/auto-parcel)：AutoParcel是AutoValue的扩展，可以生成Parcelable值。
* [Sculptor](https://github.com/sculptor/sculptor)：Sculptor是一个代码生成器，应用了领域驱动设计和领域特定语言的概念。
* [Scrooge](https://github.com/twitter/scrooge)：Scrooge是一个用Scala编写的Thrift代码生成器，目前可以为Scala、Java、Cocoa、Android和Lua生成代码，由Twitter开源。
* [Generator](https://github.com/GreedyStar/generator)：Generator是一款基于数据库表生成Java代码的工具。
* [Enunciate](https://github.com/stoicflame/enunciate)：Enunciate是一个构建时Web服务增强工具，可应用于基于Java的项目，以便从Web服务端点的源代码生成大量很酷的工件。
* [Telosys](https://github.com/telosys-tools-bricks/telosys-cli)：Telosys CLI允许通过简单的命令行工具使用Telosys Core生成器的所有功能。
* [Parceler](https://github.com/johncarl81/parceler)：Parceler是一个代码生成库，可生成Android Parcelable样板源代码。
* [PaperParcel](https://github.com/grandstaish/paperparcel)：PaperParcel可以自动生成Java和Kotlin的Parcelable实现。
* [JCodeModel](https://github.com/phax/jcodemodel)：Java代码生成库。
* [TableGo](https://gitee.com/vipbooks/TableGo)：TableGo是基于数据库的代码自动生成工具。

## 注解处理器

* [Lombok](https://github.com/projectlombok/lombok)：Lombok是对Java语法非常有用的补充，消除大量样板代码。
* [AndroidAnnotations](https://github.com/androidannotations/androidannotations)：AndroidAnnotations是一个开源框架，可加速Android开发。
* [Jackdaw](https://github.com/vbauer/jackdaw)：Jackdaw是一个Java注解处理器，可以简化Java/Android开发并防止编写繁琐的代码。
* [Rest.Vertx](https://github.com/zandero/rest.vertx)：适用于Vert.x Vertical的JAX-RS风格注解处理器。
* [Domino Jackson](https://github.com/DominoKit/domino-jackson)：Domino Jackson是一个基于注解处理器的JSON映射器。
* [Gson Path](https://github.com/LachlanMcKee/gsonpath)：一个注解处理器库，在编译时生成Gson类型适配器，也使用基本的JsonPath功能。
* [Sundrio](https://github.com/sundrio/sundrio)：Sundrio提供了一种抽象的Java代码表示方法，允许你在不受上下文限制的情况下表示、操作和生成代码。
* [APTK](https://github.com/toolisticon/aptk)：APTK可帮助你以更有效的方式构建注解处理器的工具包。
* [Incap](https://github.com/tbroyer/gradle-incap-helper)：用于构建增量注解处理器的辅助库和注解处理器。
* [Better Strings](https://github.com/antkorwin/better-strings)：Better Strings是用于Java字符串插值的插件。
* [ValueClasses](https://github.com/tguzik/valueclasses)：Java值类的基础抽象和模板。
* [AutoDelegate](https://github.com/ryandens/auto-delegate)：Java注解处理器，用于自动将接口API委托给该接口的组合实例。

#### 访问器模式

* [Magic Bean](https://github.com/bowbahdoe/magic-bean)：一个生成Getter和Setter的非常基本的库。
* [Pojo Analyzer](https://github.com/almogtavor/pojo-analyzer)：Pojo Analyzer是一个Java库，旨在为POJO的每个字段生成包含Getter、Setter和字符串名称的List或Map。

#### 不可变模式

* [Immutables](https://github.com/immutables/immutables)：Immutables是用于创建不可变对象和构建器的注解处理器。
* [Deoplice](https://github.com/chriskiehl/Deoplice)：Deoplice是一个Java库，它会自动生成用于转换不可变POJO的API。

#### 配置对象模式

* [Config Builder](https://github.com/TNG/config-builder)：Config Builder使用注解和反射来构建自定义类的配置实例。
* [Propify](https://github.com/vgerbot-libraries/propify)：Propify是一个功能强大、轻量级的Java注解处理器，它通过从配置文件(YAML、INI或Properties)和国际化包生成类型安全的类来消除配置错误。
* [Coat](https://github.com/poiu-de/coat)：Coat是一个注解处理器，用于生成将配置值读入类型安全对象的类。

#### 命名参数

* [Default4j](https://github.com/reugn/default4j)：通过注解在Java中处理默认参数值。
* [NamedParameters](https://github.com/Auties00/NamedParameters)：Java 17的命名和可选参数。

#### 处理器测试

* [Compile Testing](https://github.com/google/compile-testing)：javac和注解处理器的测试工具，由Google开源。
* [Kotlin Compile Testing](https://github.com/tschuchortdev/kotlin-compile-testing)：用于测试Kotlin和Java注解处理器、编译器插件和代码生成的库。
* [Cute](https://github.com/toolisticon/cute)：Java编译测试库，允许你测试注解处理器。
* [Java Compiler Testing](https://github.com/ascopes/java-compiler-testing)：针对现代Java库中的Java编译器执行详尽集成测试的框架，重点是完整的JPMS支持。
* [Elementary](https://github.com/Pante/elementary)：Elementary是一套可简化注解处理器的创建和单元测试的库。

## 类路径扫描

* [ClassGraph](https://github.com/classgraph/classgraph)：ClassGraph是一个超快速的并行类路径扫描器和模块扫描器，适用于Java、Scala、Kotlin和其他JVM语言。
* [Scannotation](https://scannotation.sourceforge.net/)：Scannotation是一个Java库，它从一组.class文件创建注解数据库。
* [Annovention](https://github.com/ngocdaothanh/annovention)：Annovention是一个Java注解发现库。
* [ClassIndex](https://github.com/atteo/classindex)：ClassIndex通过提供标准注解处理器的实现来在编译时对你的类进行索引。
* [Jandex](https://github.com/smallrye/jandex)：Jandex是一个节省空间的Java类文件索引器和离线反射库。
* [Extcos](https://sourceforge.net/projects/extcos/)：Extcos是一个Java组件扫描库。
* [QDox](https://github.com/paul-hammant/qdox)：QDox是一个高速、占用空间小的解析器，用于完全提取类/接口/方法定义(包括注解、参数、参数名称)，由Throughworks开发。
* [INFOMAS ASL](https://github.com/rmuller/infomas-asl)：INFOMAS ASL可用于扫描类路径以查找带注解的类、方法或实例变量。
* [Class Scanner](https://gitee.com/centchen/class-scanner)：Class Scanner为一个Java类扫描器，用于获取指定包下的Class类，同时可根据指定注解进行过滤。

## 行为分析

* [Dawn](https://github.com/eventtracing/dawn)：曙光埋点集自动化埋点与全链路追踪等特点于一身，近乎完美地解决了传统埋点的所有痛点，兼顾了开发效率与埋点数据的高精度特点，网易云开源。
* [SA Java SDK](https://github.com/sensorsdata/sa-sdk-java)：神策数据官方Java埋点SDK，是一款轻量级用于Java端的数据采集埋点SDK。
* [小象用户行为分析平台](https://gitee.com/xiaoxiangopen/analysis)：商用产品开源，包括用户埋点数据采集、用户标签分群和画像、智慧运营、营销等。
* [ClkLog](https://gitee.com/clklog/clklog)：ClkLog是一款记录用户行为分析和画像的免费可商用开源软件，技术人员可快速搭建私有的应用系统。
* [UBA](https://github.com/Foleyzhao/UBA)：JianWei是一款专业的企业级用户行为分析系统。

## URL库

* [Url Detector](https://github.com/linkedin/URL-Detector)：Url Detector是由LinkedIn安全团队创建的一个库，用于检测和提取长文本中的URL。
* [Slugify](https://github.com/slugify/slugify)：用于生成语音URL的小型工具类库。
* [Uri KMP](https://github.com/eygraber/uri-kmp)：用于在Kotlin Multiplatform中使用URI和URL的库。
* [Unbescape](https://github.com/unbescape/unbescape)：Unbescape是一个Java库，旨在执行功能齐全且高性能的转义和取消转义操作。
* [Java URLBuilder](https://github.com/mikaelhg/urlbuilder)：无运行时依赖的URL构建器。
* [AutoLink Java](https://github.com/robinst/autolink-java)：用于从纯文本中提取URL和电子邮件地址等链接的Java库。
* [Rewrite](https://github.com/ocpsoft/rewrite)：适用于Java EE 6+和Servlet 2.5+应用程序的高度可配置的URL重写工具。
* [Galimatias](https://github.com/smola/galimatias)：Galimatias是一个用Java编写的URL解析和规范化库。
* [JURL](https://github.com/anthonynsimon/jurl)：快速简单的Java URL解析库，支持UTF-8和路径解析。
* [Handy URI Templates](https://github.com/damnhandy/Handy-URI-Templates)：Handy URI Templates是一个用Java编写的实现RFC6570的uritemplate处理器。
* [UrlRewriteFilter](https://github.com/paultuckey/urlrewritefilter)：UrlRewriteFilter是一个Java Web过滤器，基于Apache中广受欢迎且实用的mod_rewrite库。
* [URLCanon](https://github.com/iipc/urlcanon)：适用于Python和Java的URL规范化库，由国际互联网保护联盟开源。
* [UrlEncoder](https://github.com/ethauvin/urlencoder)：UrlEncoder是一个简单的防御库，用于对URL组件进行编码/解码。

## Expect库

* [ExpectIt](https://github.com/agavrilov76/ExpectIt)：ExpectIt是Expect工具的另一个纯Java 1.6+实现。
* [Expect4J](https://github.com/cverges/expect4j)：用Java重写Expect并提供与TclJava解释器的绑定。
* [ExpectJ](https://expectj.sourceforge.net/)：ExpectJ可用于自动与进程或telnet会话进行交互。
* [Enchanter](https://bitbucket.org/mrdon/enchanter)：Enchanter是一个小型库，可以帮助你以类似于Expect的方式编写SSH会话脚本。
* [Expect Java](https://github.com/ronniedong/Expect-for-Java)：Expect工具的纯Java实现。
* [Expect4Java](https://github.com/iTransformers/expect4java)：Java的Expect语言实现，使用Java 8闭包。

## Wikipedia

* [JWiki](https://github.com/fastily/jwiki)：用于轻松与Wikipedia/MediaWiki交互的库。
* [DBpedia](https://github.com/dbpedia/extraction-framework)：DBpedia旨在从Wikipedia中提取结构化信息并将这些信息发布到网络上。
* [JWPL](https://github.com/dkpro/dkpro-jwpl)：JWPL是一个基于Java的免费应用程序编程接口，允许访问维基百科中的所有信息，由达姆施塔特工业大学开源。
* [XOWA](https://github.com/gnosygnu/xowa)：XOWA是一款离线维基百科应用程序，可让你在计算机上运行维基百科。

## 用户代理解析

* [Uap Java](https://github.com/ua-parser/uap-java)：这是ua-parser的Java实现。
* [User Agent Utils](https://github.com/HaraldWalker/user-agent-utils)：用于处理用户代理字符串的实用程序，可用于实时处理HTTP请求或分析日志文件。
* [UADetector](https://github.com/arouel/uadetector)：UADetector是一个库，可以识别190多种不同的桌面和移动浏览器，以及130种其他用户代理。
* [HTTPRequest](https://github.com/Konloch/HTTPRequest)：HTTPRequest是一个易于使用的零依赖Java包装器，用于从URL读取Cookie、代理、UserAgent、发布数据等。
* [BrowsCap Java](https://github.com/blueconic/browscap-java)：一个基于BrowsCap CSV源文件的速度极快且内存高效的Java客户端。
* [Yauaa](https://github.com/nielsbasjes/yauaa)：这是一个Java库，可以解析和分析useragent字符串(以及可用的User-Agent客户端提示)提取尽可能多的相关属性。
* [Salvation](https://github.com/shapesecurity/salvation)：这是一个用于处理内容安全策略策略的通用库。
* [UASparser](https://github.com/chetan/UASparser)：Java的高性能用户代理解析器。

## 数字信号处理

* [JDSP](https://github.com/psambit9791/jdsp)：JDSP是一个信号处理工具库，旨在提供MATLAB或Python的scipy-signal包中可用的功能。
* [IIRJ](https://github.com/berndporr/iirj)：用Java编写的高效IIR滤波器库。
* [JRadio](https://github.com/dernasherbrezon/jradio)：用Java编写的软件无线电解码，这个项目的想法是从gnuradio获取块并用Java实现它们。
* [SpinCAD Designer](https://github.com/HolyCityAudio/SpinCAD-Designer)：SpinCAD Designer是一个开源Java项目，允许为Spin FV-1音频DSP芯片创建补丁并进行音频模拟。

## 数字资产管理

* [LOCKSS](https://github.com/lockss/lockss-daemon)：LOCKSS是LOCKSS计划开发和维护的成熟、垂直集成、开源、分布式数字保存系统，由斯坦福赞助。
* [DSpace](https://github.com/DSpace/DSpace)：DSpace是一个专门的数字资产管理系统，它管理和发布由数字文件或“位流”组成的数字条目，并且允许创建、索引和搜索相关的元数据以便定位和存取该条目，由麻省理工学院联合美国惠普公司实验室开源。
* [Cudami](https://github.com/dbmdz/cudami)：Cudami是一个编辑后台，用于管理网站、文章、数字化对象、数字原生对象和实体等文化数字资产，由巴伐利亚国立图书馆开源。
* [OCFL Java](https://github.com/OCFL/ocfl-java)：该项目是牛津大学OCFL规范的Java实现，OCFL规范描述了一种独立于应用程序的方法，以结构化、透明且可预测的方式存储数字信息。
* [DuraCloud](https://github.com/duracloud/duracloud)：DuraCloud是一种开源托管数字保存服务，它将灵活的存储选项与强大的工具相结合，以简化你的保存工作流程。
* [Goobi](https://github.com/intranda/goobi-workflow)：Goobi是一款用于数字化项目的开源软件应用程序，它允许你对可自由定义的生产流程进行建模、管理和监督，并且许多机构每天都使用它来处理创建数字图书馆或博物馆所涉及的所有步骤。
* [Vitam](https://github.com/ProgrammeVitam/vitam)：法国政府开发的数字档案管理系统。
* [ePADD](https://github.com/ePADD/epadd)：ePADD是由斯坦福大学特殊馆藏和大学档案馆开发的软件包，支持围绕电子邮件档案的评估、摄取、处理、发现和交付的档案流程。
* [RODA](https://github.com/keeps/roda)：RODA是一个长期数字存储库解决方案，提供OAIS参考模型所有主要功能单元的功能。
* [Kitodo](https://www.kitodo.org/)：Kitodo是一款开源软件套件，用于对大大小小的图书馆、档案馆、博物馆和文献中心的文化资产进行数字化。
* [MyCoRe](https://github.com/MyCoRe-Org/mycore)：MyCoRe是一个开源仓库软件框架，用于构建学科或机构存储库、数字档案、数字图书馆和科学期刊。
* [MARC4J](https://github.com/marc4j/marc4j)：MARC4J的目标是提供一个易于使用的API，以便在Java中使用MARC和MARCXML。
* [Fedora](https://github.com/fcrepo/fcrepo)：Fedora是一个强大、模块化、开源存储库系统，用于管理和传播数字内容，它特别适合数字图书馆和档案馆的访问和保存。
* [DROID](https://github.com/digital-preservation/droid)：DROID是英国国家档案馆开发的一款软件工具，用于自动批量识别文件格式。
* [LoA](https://github.com/bottomless-archive-project/library-of-alexandria)：LoA是一个旨在从互联网收集和存档文献的项目。
* [Kramerius](https://github.com/ceskaexpedice/kramerius)：Kramerius是一款数字图书馆开源软件解决方案，主要用于数字化图书馆藏书、专著和期刊，由捷克共和国科学院图书馆、捷克共和国国家图书馆等开源。

## 自动程序修复

* [Astor](https://github.com/SpoonLabs/astor)：Astor是Java的自动软件修复框架，由法国国立计算机及自动化研究院、里尔大学、法兰西理工大学和皇家理工学院共同开发。
* [SimFix](https://github.com/xgdsmileboy/SimFix)：SimFix是一种自动程序修复技术，它利用其他项目中现有的补丁和同一项目中的类似代码片段来生成补丁，由天津大学开源。
* [Defects4J](https://github.com/rjust/defects4j)：Defects4J是可重现错误和支持基础设施的集合，旨在推动软件工程研究。
* [Angelix](https://github.com/msv-lab/angelix)：Angelix是基于语义的C程序自动程序修复工具，由新加坡国立大学开源。
* [Sorald](https://github.com/ASSERT-KTH/sorald)：Sorald是一款自动修复使用SonarQube检查的静态分析规则违规的工具，由瑞典斯德哥尔摩皇家理工学院开源。
* [KGenProg](https://github.com/kusumotolab/kGenProg)：KGenProg是一个用Java编写的用于Java的自动程序修复工具，由大阪大学开源。

## 协议实现

* [Open eCard](https://github.com/ecsec/open-ecard)：Open eCard旨在提供eCard-API-Framework(BSI TR-03112)和相关国际标准ISO/IEC 24727的开源和跨平台实现。
* [HAP Java](https://github.com/hap-java/HAP-Java)：HAP-Java是HomeKit附件协议的Java实现。
* [SECS4Java8](https://github.com/kenta-shimizu/secs4java8)：该库是Java 8上的SEMI-SECS通信实现。
* [DBus Java](https://github.com/hypfvieh/dbus-java)：该库是D-Bus协议的原生Java实现。
* [Calimero Core](https://github.com/calimero-project/calimero-core)：Calimero Core提供(安全)KNX通信协议、KNX数据点和属性访问以及管理功能。
* [Bacnet4J Wrapper](https://github.com/Code-House/bacnet4j-wrapper)：Bacnet4j是bacnet协议的Java实现，这是Bacnet4j API的简单门面。
* [RISE V2G](https://github.com/SwitchEV/RISE-V2G)：车辆到电网(V2G)通信接口ISO 15118的开源参考实现。
* [Chromecast Java API v2](https://github.com/vitalidze/chromecast-java-api-v2)：Chromecast V2协议客户端的Java实现。

## BitTorrent

* [Bt](https://github.com/atomashpolskiy/bt)：BitTorrent库和客户端，具有DHT、磁力链接、加密等功能。
* [BiglyBT](https://github.com/BiglySoftware/BiglyBT)：基于Azureus开源项目的功能齐全的Bittorrent客户端。
* [PeerBanHelper](https://github.com/PBH-BTN/PeerBanHelper)：PeerBanHelper是一个开源的个人网络防火墙安全软件。
* [Vuze](https://www.vuze.com/)：Vuze是一个用Java编写的BitTorrent客户端，且支持I2P和Tor匿名网络协议。
* [Snail](https://gitee.com/acgist/snail)：基于Java、JavaFX开发的下载工具，支持下载协议BT(BitTorrent、磁力链接、种子文件)、HLS(M3U8)、FTP、HTTP。
* [MLDHT](https://github.com/the8472/mldht)：一个Java库和独立节点，实现了基于Kademlia的BitTorrent主线DHT，并考虑到长期运行的服务器级节点。
* [Kademlia](https://github.com/JoshuaKissoon/Kademlia)：这是Kademlia路由协议和DHT的实现。
* [OpenSeedbox](https://github.com/openseedbox/openseedbox)：OpenSeedbox是一个基于Web的BitTorrent用户界面。
* [BitLet](https://github.com/bitletorg/bitlet)：BitLet是BitTorrent协议的简单Java实现。
* [Ttorrent](https://github.com/mpetazzoni/ttorrent)：BitTorrent协议的Java实现。
* [FrostWire JLibTorrent](https://github.com/frostwire/frostwire-jlibtorrent)：FrostWire为libtorrent提供的swig Java接口。
* [Libtorrent4j](https://github.com/aldenml/libtorrent4j)：Libtorrent的swig Java接口。
* [FrostWire](https://github.com/frostwire/frostwire)：FrostWir是BitTorrent网络的媒体播放器和点对点(P2P)信息共享客户端。

## 编解码

* [Apache Commons Codec](https://github.com/apache/commons-codec)：Commons Codec包含各种格式(例如Base64和十六进制)的简单编码器和解码器。
* [OWASP Java Encoder](https://github.com/OWASP/owasp-java-encoder)：OWASP Java Encoder是一个简单易用的嵌入式高性能编码器类，没有依赖且包袱很少，由OWASP开源。
* [Simple Binary Encoding](https://github.com/aeron-io/simple-binary-encoding)：SBE是OSI第6层表示，用于对低延迟金融应用程序的二进制应用程序消息进行编码和解码。
* [Juniversalchardet](https://github.com/albfernandez/juniversalchardet)：Juniversalchardet是universalchardet的Java端口，universalchardet是Mozilla的编码检测器库。
* [PETSCII BBS Builder](https://github.com/sblendorio/petscii-bbs)：一个Java框架，用于构建高度可定制的PETSCII(和ASCII)支持的BBS，可从8位Commodore计算机访问。
* [Xtream Codec](https://github.com/hylexus/xtream-codec)：基于Reactor Netty的私有协议编解码库。
* [Preon](https://github.com/preon/preon)：Preon旨在提供一个处理二进制编码数据的框架。
* [Netty ZMTP](https://github.com/spotify/netty-zmtp)：这是Netty的ZeroMQ编解码器，旨在实现ZMTP，由Spotify开源。
* [Base62](https://github.com/seruco/base62)：Java的Base62编码器/解码器。

## 打印机

* [ESC/POS Thermal Printer](https://github.com/DantSu/ESCPOS-ThermalPrinter-Android)：可帮助Android开发人员使用(蓝牙、TCP、USB)ESC/POS热敏打印机进行打印的库。
* [ECS/POS Coffee](https://github.com/anastaciocintra/escpos-coffee)：用于ESC/POS打印机命令的Java库。
* [Printer](https://github.com/AlexMofer/Printer)：标准ESC-POS命令打印，固定IP或蓝牙打印，支持黑白图片打印。
* [RepRap](https://sourceforge.net/projects/reprap/)：RepRap是一种三维打印机原型机，它具有一定程度的自我复制能力，能够打印出大部分其自身的塑料组件，由英国巴斯大学开发。
* [Zebra ZPL](https://github.com/w3blogfr/zebra-zpl)：用于生成通用ZPL命令以使用Java在Zebra打印机上打印标签的库。
* [ESC/POS Java](https://github.com/stefanosbou/esc-pos-java)：用于ESC/POS兼容热敏打印机的Java库，串行或网络连接。

## Web开发

* [YUI Compressor](https://github.com/yui/yuicompressor)：YUI Compressor是一个JavaScript压缩器，除了删除注释和空格之外，它还使用尽可能小的变量名称来混淆局部变量，该库由Yahoo开源。
* [Google Closure Compiler](https://github.com/google/closure-compiler)：Closure Compiler是一款加速JavaScript下载和运行的工具，由Google开源。
* [WebJars](https://github.com/webjars/webjars)：WebJars是打包到JAR文件中的客户端Web库(例如jQuery和Bootstrap)。
* [Caja](https://github.com/googlearchive/caja)：Caja是一个用于在你的网站中安全嵌入第三方HTML、CSS和JavaScript的工具，由Google开源。
* [Wro4j](https://github.com/wro4j/wro4j)：Wro4j是一个免费的开源Java项目，可以帮助缩短Web应用程序页面加载时间。
* [Nu Html Checker](https://github.com/validator/validator)：Nu Html Checker可帮助你发现HTML、CSS和SVG中的意外错误。
* [Closure Templates](https://github.com/google/closure-templates)：客户端和服务器端模板系统，可帮助你动态构建可重用的HTML和UI元素，由Google开源。
* [Chart.java](https://github.com/mdewilde/chart)：Chart.java可以在Java应用程序中与优秀的Chart.js库集成。
* [Displaytag](https://github.com/hazendaz/displaytag)：Displaytag库是一个开源的自定义标签套件，提供可在MVC模型中工作的高级Web表示模式。
* [AngularFaces](https://github.com/stephanrauh/AngularFaces)：AngularFaces是一个JSF组件库，旨在通过允许你用简单的AngularJS代码替换大量巧妙的AJAX代码来简化JSF开发。
* [Adminfaces](https://github.com/adminfaces/admin-template)：Admin Template是一个基于Bootstrap和Admin LTE的完全响应式Java Server Faces管理模板。
* [Orbeon Forms](https://github.com/orbeon/orbeon-forms)：Orbeon Forms是一个开源Web表单解决方案。
* [HAR Reader](https://github.com/sdstoehr/har-reader)：用于使用Java访问HTTP存档(HAR)的库。
* [Stapler](https://github.com/jenkinsci/stapler)：Stapler是一个将应用程序对象装订到URL的库，使编写Web应用程序变得更加容易，由Jenkins组织开源。
* [Wicket Stuff](https://github.com/wicketstuff/core)：Wicket Stuff是由Wicket社区创建和维护的Apache Wicket Web框架的开源项目集合。
* [ORCID Source](https://github.com/ORCID/ORCID-Source)：ORCID Source是一组使用Java构建的Web应用程序和库，使用Spring Web MVC和Postgres数据库提供的持久性。
* [Mateu](https://github.com/miguelperezcolom/mateu)：Mateu是一个用于以光速从Java创建出色的响应式Web应用程序的框架。
* [Metawidget](https://github.com/metawidget/metawidget)：Metawidget是一个智能小部件，它可以静态或运行时填充自身，并使用UI组件来匹配域对象的属性。
* [AngularBeans](https://github.com/bessemHmidi/AngularBeans)：AngularBeans是一个框架，其目的是将Java EE 7(更准确地说是CDI规范)与AngularJS结合使用。
* [N2O Framework](https://github.com/i-novus-llc/n2o-framework)：N2O Framework是一个用Java和ReactJS编写的库，允许你创建具有复杂用户界面的Web应用程序，而无需深入了解Web技术和前端框架。
* [ApexCharts Flow](https://github.com/appreciated/apexcharts-flow)：Vaadin平台的ApexCharts.js包装器。
* [JWt](https://github.com/emweb/jwt)：JWt是一个用于开发Web应用程序的Java库，它提供了一种纯Java组件驱动的方法来构建Web应用程序，并使用Ajax或纯HTML进行呈现。
* [LightAdmin](https://github.com/la-team/light-admin)：该项目的主要目标是通过为基于JPA的应用程序引入可插入的完全可操作的数据管理后端来加速应用程序开发。
* [Fastball](https://github.com/fastball-projects/fastball)：Fastball是一套面向后端、声明式界面开发框架。
* [Wicket Bootstrap](https://github.com/martin-g/wicket-bootstrap)：Wicket Bootstrap基于Bootstrap工具包和Apache Wicket框架。

#### WebAssembly

* [GraalWasm](https://www.graalvm.org/webassembly/)：GraalWasm是一个适用于Java的高性能嵌入式WebAssembly运行时。
* [Bytecoder](https://github.com/mirkosertic/Bytecoder)：Bytecoder是Java字节码和框架的富域模型，用于将其解释并转换为其他语言，例如JavaScript、OpenCL或WebAssembly。
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly)：JWebAssembly是Java字节码到WebAssembly的编译器。
* [TeaVM](https://github.com/konsoletyper/teavm)：TeaVM是Java字节码的提前编译器，可生成在浏览器中运行的JavaScript和WebAssembly。
* [DoppioJVM](https://github.com/plasma-umass/doppio)：Doppio是一个兼容POSIX的运行时系统以及一个用TypeScript编写的JVM，也是马萨诸塞大学PLASMA小组的一个活跃的研究项目。
* [Asmble](https://github.com/cretz/asmble)：Asmble是一个将WebAssembly代码编译为JVM字节码的编译器，它还包含一个解释器和实用程序，用于从命令行和JVM语言处理WASM代码。
* [Wasmtime Java](https://github.com/kawamuray/wasmtime-java)：Wasmtime的Java语言绑定。
* [CheerpJ](https://github.com/leaningtech/cheerpj-meta)：CheerpJ是一个基于WebAssembly的浏览器JVM。
* [Chicory](https://github.com/dylibso/chicory)：Chicory是JVM原生WebAssembly运行时，它允许你以零本机依赖或JNI运行WebAssembly程序。
* [Wasmer](https://github.com/wasmerio/wasmer-java)：基于Wasmer的完整且成熟的Java WebAssembly运行时。

#### JavaScript引擎

* [DSBridge Android](https://github.com/wendux/DSBridge-Android)：现代跨平台JavaScript桥接器，通过它在JavaScript和原生应用程序之间可以同步或者异步调用彼此的函数。
* [GraalJS](https://github.com/oracle/graaljs)：JavaScript编程语言的高性能实现，由Oracle实验室基于GraalVM构建。
* [Nashorn](https://github.com/openjdk/nashorn)：Nashorn的目标是使用原生JVM在Java中实现轻量级高性能JavaScript运行时。
* [Grakkit](https://github.com/grakkit/grakkit)：Minecraft的现代JavaScript开发环境。
* [Javet](https://github.com/caoccao/Javet)：在Java中嵌入Node.js和V8的绝佳方式。
* [Rhino](https://github.com/mozilla/rhino)：Rhino是完全用Java编写的JavaScript的开源实现，Mozilla开源。
* [Node Android](https://github.com/InstantWebP2P/node-android)：通过使用兼容的API用Java重写Node.js，在Android上运行Node.js。
* [RingoJS](https://github.com/ringo/ringojs)：Ringo是一个基于JVM构建的JavaScript平台，并针对服务器端应用程序进行了优化。
* [Dynjs](https://github.com/dynjs/dynjs)：JVM的ECMAScript运行时。
* [Nodyn](https://github.com/nodyn/nodyn)：Nodyn是JVM上的Node.js兼容框架。
* [J2V8](https://github.com/eclipsesource/j2v8)：J2V8是V8的一组Java绑定，注重性能以及与V8的紧密集成。
* [ES4X](https://github.com/reactiverse/es4x)：ES4X是一款支持EcmaScript >= 5应用的小型运行时。
* [LebJS](https://github.com/LebsterFace/LebJS)：LebJS是用Java编写的JavaScript引擎。
* [JScript](https://github.com/TopchetoEU/jscript)：JScript是一个引擎，能够运行EcmaScript 5，完全用Java编写。
* [Karate JS](https://github.com/karatelabs/karate-js)：适用于JVM的轻量级JavaScript引擎。
* [Trireme](https://github.com/apigee/trireme)：Trireme在JVM内运行Node.js脚本。
* [DWR](https://github.com/directwebremoting/dwr)：DWR是一个Java库，它使服务器上的Java和浏览器中的JavaScript能够尽可能简单地交互和调用。
* [Reeva](https://github.com/ReevaJS/reeva)：Reeva是一个使用Kotlin从头编写的JavaScript引擎。
* [QuickJs4J](https://github.com/roastedroot/quickjs4j)：QuickJs4J允许你使用沙盒环境安全轻松地从Java运行JavaScript。
* [QuickJS Wrapper](https://github.com/HarlonWang/quickjs-wrapper)：Android/JVM的QuickJS包装器。

#### GWT库

* [Nalu](https://github.com/NaluKit/nalu)：Nalu是一个微型框架，可帮助你轻松创建基于GWT的应用程序。
* [Elemento](https://github.com/hal/elemento)：Elemento可以简化GWT Elemental2的使用。
* [Elemental](https://github.com/google/elemental2)：Elemental2为Java代码提供对所有浏览器API的类型检查访问，由Google开源。
* [AngularGWT](https://github.com/cromwellian/angulargwt)：这是一个能够用Java为AngularJS编写组件或完整的应用程序的库。
* [AutoREST](https://github.com/intendia-oss/autorest)：GWT自动RESTful服务代理生成器。
* [GWTP](https://github.com/ArcBees/GWTP)：GWTP是一个完整的模型视图演示器框架，可简化你的下一个GWT项目。
* [Domino UI](https://github.com/DominoKit/domino-ui)：类型安全且功能丰富的UI组件库，供Java开发人员使用流式API，并且不依赖于外部JavaScript。
* [React4j](https://github.com/react4j/react4j)：该项目的目标是能够从GWT无缝使用React的组件模型，并利用React开发支持工具(例如React的Devtools)生态系统。
* [GWT Material](https://github.com/GwtMaterialDesign/gwt-material)：GWT的Google Material Design包装器。
* [Vue GWT](https://github.com/VueGWT/vue-gwt)：Vue GWT使用JsInterop和Elemental2将Vue.js与GWT 2.9集成，它允许你用Java编写Vue组件。
* [GWT Bootstrap](https://github.com/gwtbootstrap/gwt-bootstrap)：提供了简单灵活的组件来表示Bootstrap组件、样式和插件，由Twitter开源。
* [GwtBootstrap3](https://github.com/gwtbootstrap3/gwtbootstrap3)：GWTBootstrap3是Twitter Bootstrap的包装器，可帮助你使用Java和GWT在Web上开发响应式、移动优先的HTML、CSS和JS项目。
* [Charba](https://github.com/pepstock-org/Charba)：基于Chart.js的J2CL和GWT图表库。
* [DnComponents](https://dncomponents.com/index.html)：客户端Java UI框架，用于使用GWT编译器和Elemental2浏览器API纯粹使用Java语言构建丰富的Web应用程序，无需任何外部JS库。
* [GwtQuery](https://github.com/ArcBees/gwtquery)：GwtQuery是一个用GWT编写的类似jQuery的API，它允许在GWT小部件可能过于重量级的渐进式增强场景中使用GWT。
* [GWT React](https://github.com/GWTReact)：GWT React为React v16.3提供Java GWT绑定。

#### CSS库

* [CSSEmbed](https://github.com/nzakas/cssembed)：CSSEmbed是一个小型程序/库，用于自动将数据URI嵌入CSS文件中。
* [Closure Stylesheets](https://github.com/google/closure-stylesheets)：Closure Stylesheets是CSS的一个扩展，它为标准CSS添加变量、函数、条件语句和混合宏，由Google开源。
* [CSS Validator](https://github.com/w3c/css-validator)：W3C CSS验证服务。
* [Ph CSS](https://github.com/phax/ph-css)：Java CSS 2和CSS 3解析器和构建器。
* [LESS Engine](https://github.com/asual/lesscss-engine)：LESS引擎提供对核心LESS功能的基本访问。
* [LESS CSS Compiler](https://github.com/marceloverdijk/lesscss-java)：LESS CSS Compiler是一个将LESS源代码编译为CSS样式表的库。
* [JLessC](https://github.com/i-net-software/jlessc)：JLessC是一个完全用Java编写的Less CSS编译器。
* [Less4j](https://github.com/SomMeri/less4j)：Less4j将Less编译为常规CSS。
* [CSS Selectors](https://github.com/chrsan/css-selectors)：W3C选择器规范的Java实现。
* [jStyleParser](https://github.com/radkovo/jStyleParser)：jStyleParser是一个Java库，用于解析CSS样式表并根据CSS 3规范为HTML或XML文档元素分配样式。

## 对象图导航

* [Apache Commons OGNL](https://github.com/apache/commons-ognl)：OGNL代表对象图导航语言；它是一种表达式语言，用于获取和设置Java对象的属性，以及其他附加功能，例如列表投影和选择以及Lambda表达式。
* [OGNL](https://github.com/orphan-oss/ognl)：对象图导航库。
* [OGNL Expression](https://mvnrepository.com/artifact/marmalade/marmalade-el-ognl)：OGNL表达式库。

## 超媒体类型

* [Spring HATEOAS](https://github.com/spring-projects/spring-hateoas)：Spring HATEOAS提供了一些API，以便在与Spring配合使用时轻松创建遵循HATEOAS原则的REST表示。
* [Hate](https://github.com/blackdoor/hate)：根据HAL规范构建超媒体友好的对象。
* [Katharsis](https://github.com/katharsis-project/katharsis-framework)：Katharsis实现了JSON API标准，引入了一致的REST接口定义，可以通过统一的机制轻松地与其他系统集成。
* [Spring HATEOAS JSON API](https://github.com/toedter/spring-hateoas-jsonapi)：这是与Spring HATEOAS集成的媒体类型application/vnd.api+json(JSON:API)的实现。
* [Edison HAL](https://github.com/otto-de/edison-hal)：使用Jackson生成和使用REST资源的application/hal+json表示的库。

## 术语服务器

* [Snow Owl](https://github.com/b2ihealthcare/snow-owl)：Snow Owl是一款高度可扩展的开源术语服务器，具有修订控制功能和协作创作平台功能。
* [Snowstorm](https://github.com/IHTSDO/snowstorm)：Snowstorm是一个开源术语服务器，特别支持SNOMED CT。

## Maven插件

* [Frontend Maven Plugin](https://github.com/eirslett/frontend-maven-plugin)：该插件会在你的项目本地下载/安装Node和NPM，运行npm install，然后运行Bower、Grunt、Gulp、Jspm、Karma或Webpack的任意组合。
* [Git Commit Id Maven Plugin](https://github.com/git-commit-id/git-commit-id-maven-plugin)：可以将构建时Git仓库信息包含到POJO/properties文件中的Maven插件。
* [Android Maven Plugin](https://github.com/simpligility/android-maven-plugin)：用于Android应用程序开发等的Maven插件。
* [TypeScript Generator](https://github.com/vojtechhabarta/typescript-generator)：TypeScript Generator是一个用于从Java JSON类生成TypeScript定义文件(.d.ts)的工具。
* [SonarQube Maven Plugin](https://github.com/SonarSource/sonar-scanner-maven)：用于Maven的SonarQube扫描器。
* [Nexus Maven Plugin](https://github.com/sonatype/nexus-maven-plugins)：支持Nexus Suite的Apache Maven插件集合。
* [Scala Maven Plugin](https://github.com/davidB/scala-maven-plugin)：Scala Maven插件用于在Maven中编译/测试/运行/记录Scala代码。
* [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin)：能够在构建过程中运行JMeter测试的Maven插件。
* [Polyglot Maven](https://github.com/takari/polyglot-maven)：Polyglot Maven是Maven 3.3.1+的一组扩展，允许使用XML以外的方言编写POM模型。
* [JAXB Tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [Aadarchi](https://github.com/Riduidel/aadarchi)：Aadarchi是一个Maven原型，可轻松生成项目，允许使用C4、敏捷架构、Asciidoc和PlantUML的组合进行架构描述。
* [ModiTect](https://github.com/moditect/moditect)：ModiTect项目旨在提供使用Java模块系统的生产力工具。
* [Maven Javadoc Plugin](https://github.com/apache/maven-javadoc-plugin)：Javadoc插件使用Javadoc工具为指定项目生成javadoc。
* [GitFlow Helper Maven Plugin](https://github.com/egineering-llc/gitflow-helper-maven-plugin)：一个构建扩展和插件，可帮助Maven与gitflow项目、CI服务器和本地开发完美配合。
* [Modernizer Maven Plugin](https://github.com/gaul/modernizer-maven-plugin)：Modernizer Maven插件检测现代Java版本取代的遗留API的使用。
* [JavaFX Maven Plugin](https://github.com/javafx-maven-plugin/javafx-maven-plugin)：JavaFX Maven插件提供了一种从Maven内组装JavaFX应用程序(8+)分发包的方法。
* [JavaFX Maven Plugin](https://github.com/openjfx/javafx-maven-plugin)：用于运行JavaFX 11+应用程序的Maven插件。
* [GluonFX Maven Plugin](https://github.com/gluonhq/gluonfx-maven-plugin)：简化为Java/JavaFX Maven项目创建本机镜像的插件。
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
* [Tomcat Maven Plugin](https://github.com/apache/tomcat-maven-plugin)：在构建期间启动Tomcat服务器的Maven插件。
* [Exec Maven Plugin](https://github.com/mojohaus/exec-maven-plugin)：该插件提供了2个目标来帮助执行系统和Java程序。
* [GWT Maven Plugin](https://github.com/tbroyer/gwt-maven-plugin)：该插件旨在通过提供两个特定的包gwt-lib和gwt-app，使使用Maven构建GWT项目变得更容易。
* [JShell Maven Plugin](https://github.com/johnpoth/jshell-maven-plugin)：Java Shell工具(JShell)的Maven插件。
* [Web3j Maven Plugin](https://github.com/web3j/web3j-maven-plugin)：Web3j Maven插件用于根据Solidity合约文件创建Java类。
* [AspectJ Maven Plugin](https://github.com/mojohaus/aspectj-maven-plugin)：该插件使用AspectJ编译器ajc将AspectJ切面编织到类中。
* [Google App Engine Maven plugin](https://github.com/GoogleCloudPlatform/app-maven-plugin)：该Maven插件提供了构建和部署Google App Engine应用程序的目标。
* [Mosec Maven Plugin](https://github.com/momosecurity/mosec-maven-plugin)：用于检测Maven项目的第三方依赖组件是否存在安全漏洞。
* [Rewrite Maven Plugin](https://github.com/openrewrite/rewrite-maven-plugin)：OpenRewrite的Maven插件，将Rewrite检查和修复任务应用为构建任务。
* [Allure Maven Plugin](https://github.com/allure-framework/allure-maven)：该插件在Maven构建过程中通过现有XML文件生成Allure报告。
* [Heroku Maven Plugin](https://github.com/heroku/heroku-maven-plugin)：用于将Java应用程序直接部署到Heroku，而无需推送到Git仓库。
* [Cargo Maven Plugin](https://github.com/codehaus-cargo/cargo)：Cargo是一个瘦Java包装器，允许你以标准方式操作各种类型的应用程序容器(J2EE、Java EE、Jakarta EE等)。
* [Maven Build Scanner](http://github.com/intuit/maven-build-scanner)：Maven Build Scanner是一款挂载到Maven构建的工具，它可以生成报告和图表，详细分析Maven执行不同任务所花费的时间，由Intuit开发。
* [Maven IT Extension](https://github.com/khmarbaise/maven-it-extension)：实验性JUnit Jupiter扩展，用于为Maven插件/Maven扩展/Maven核心编写集成测试。
* [Maven PlantUML Plugin](https://github.com/arnaudroques/maven-plantuml-plugin)：一个使用PlantUML语法生成UML图的Maven插件。
* [Helm Maven Plugin](https://github.com/kokuwaio/helm-maven-plugin)：这是一个用于测试、打包和上传HELM图表的Maven插件。
* [Maven Download Plugin](https://github.com/maven-download-plugin/maven-download-plugin)：该插件可帮助Maven用户在Maven构建过程中下载不同协议上的不同文件。
* [Yeoman Maven Plugin](https://github.com/trecloux/yeoman-maven-plugin)：使用此插件可以将yeoman构建集成到你的Maven构建中。
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
* [JSass](https://github.com/bit3/jsass)：JSass是一个模块化的Java Sass编译器。
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
* [Download Maven Plugin](https://github.com/download-maven-plugin/download-maven-plugin)：这是一个插件，旨在帮助Maven用户在Maven构建过程中使用不同的协议下载不同的文件。
* [JGitVer Maven Plugin](https://github.com/jgitver/jgitver-maven-plugin)：该插件允许使用来自Git历史记录的信息来定义项目的POM版本。
* [JRuby Maven Plugin](https://github.com/jruby/jruby-maven-plugins)：以Maven方式处理RubyGems的插件。
* [PlantUML Generator](https://github.com/devlauer/plantuml-generator)：PlantUML Generator是一个由实用模块组成的项目，该模块可用于从现有的Java类及其Maven插件前端生成PlantUML 类图。
* [MojoHaus BuildPlan Maven Plugin](https://github.com/mojohaus/buildplan-maven-plugin)：用于检查项目生命周期的Maven插件。
* [Maven Assembly Plugin](https://github.com/apache/maven-assembly-plugin)：Assembly插件使开发人员能够将项目输出组合成一个可分发的档案，其中还包含依赖项、模块、站点文档和其他文件。
* [Protobuf Maven Plugin](https://github.com/ascopes/protobuf-maven-plugin)：Maven的现代Protobuf集成，包括对二进制和JAR协议插件的支持。
* [Maven Dependency Plugin](https://github.com/apache/maven-dependency-plugin)：Dependency插件提供了操作工件的能力，它可以将工件从本地或远程仓库复制和/或解压到指定位置。

## Gradle插件

* [Gradle Retrolambda](https://github.com/evant/gradle-retrolambda)：用于在Java 6、7和Android中获取Java Lambda支持。
* [Build Time Tracker](https://github.com/passy/build-time-tracker-plugin)：可以持续跟踪和报告构建时间的Gradle插件。
* [Dexcount Gradle Plugin](https://github.com/KeepSafe/dexcount-gradle-plugin)：用于报告每次构建时APK中方法引用的数量。
* [Hunter](https://github.com/Leaking/Hunter)：一个快速、增量、并发的框架，用于开发Android项目的编译插件来操作字节码。
* [Gradle Shadow](https://github.com/GradleUp/shadow)：Gradle插件，用于创建fat/uber JAR，支持包重定位。
* [Packer-NG Gradle Plugin](https://github.com/mcxiaoke/packer-ng-plugin)：下一代Android打包工具。
* [Gradle Versions Plugin](https://github.com/ben-manes/gradle-versions-plugin)：此插件提供了一个任务来确定哪些依赖项有更新。
* [Bintray Release](https://github.com/novoda/bintray-release)：这是一个将库发布到Bintray的助手。
* [Protobuf Gradle Plugin](https://github.com/google/protobuf-gradle-plugin)：Gradle插件，用于编译项目中的Protocol Buffer定义文件(*.proto)。
* [Gradle Maven Publish Plugin](https://github.com/vanniktech/gradle-maven-publish-plugin)：Gradle插件可将你的Android和Kotlin库发布到Maven Central或任何其他Nexus实例。
* [IntelliJ Platform Gradle Plugin](https://github.com/JetBrains/intellij-platform-gradle-plugin)：IntelliJ Platform Gradle Plugin是Gradle构建系统的插件，可帮助你配置基于IntelliJ的IDE的构建、测试、验证和发布插件的环境。
* [Gradle Bintray Plugin](https://github.com/bintray/gradle-bintray-plugin)：Gradle Bintray插件允许你将工件发布到Bintray。
* [Secrets Gradle Plugin](https://github.com/google/secrets-gradle-plugin)：Gradle插件，用于为你的Android项目提供机密信息。
* [Gradle Task Tree](https://github.com/dorongold/gradle-task-tree)：将任务依赖树报告打印到控制台的Gradle插件。
* [Gradle Release](https://github.com/researchgate/gradle-release)：Gradle Release插件的设计与Maven发布插件类似。
* [Gradle Node Plugin](https://github.com/srs/gradle-node-plugin)：此插件使你能够在构建过程中使用许多基于NodeJS的技术，而无需在系统上本地安装NodeJS。
* [Gradle Lint Plugin](https://github.com/nebula-plugins/gradle-lint-plugin)：Gradle Lint Plugin是一个可插入且可配置的Linter工具，用于识别和报告Gradle脚本和相关文件中的误用或弃用模式。
* [Gogradle](https://github.com/gogradle/gogradle)：Gogradle是一个Gradle插件，提供对构建Golang的支持。
* [Gradle Doctor](https://github.com/runningcode/gradle-doctor)：适合你的Gradle构建的正确处方。
* [Gradle BuildConfig Plugin](https://github.com/gmazzo/gradle-buildconfig-plugin)：用于为任何类型的Gradle项目生成BuildConstants的插件。
* [IHub Plugins](https://github.com/ihub-pub/plugins)：IHub Plugins是一套为Gradle项目提供基础设施的插件集，可以极大简化项目配置。
* [HiBeaver](https://github.com/hydraxman/hibeaver)：HiBeaver是一个用于进行Java字节码插桩的Gradle插件。
* [Dependency Management Plugin](https://github.com/spring-gradle-plugins/dependency-management-plugin)：提供类似Maven的依赖管理功能。
* [Gradle Test Logger Plugin](https://github.com/radarsh/gradle-test-logger-plugin)：用于在运行测试时在控制台上打印漂亮日志的Gradle插件。
* [JavaFX Gradle Plugin](https://github.com/openjfx/javafx-gradle-plugin)：简化使用JavaFX 11+ Gradle项目的插件。
* [JavaFX Gradle Plugin](https://github.com/FibreFoX/javafx-gradle-plugin)：用于JavaFX的Gradle插件。
* [GluonFX Gradle Plugin](https://github.com/gluonhq/gluonfx-gradle-plugin)：简化使用Gluon Client处理Java/JavaFX Gradle项目的插件。
* [Google Play Gradle Plugin](https://github.com/google/play-services-plugins)：帮助使用Google Play服务SDK的插件。
* [Clean Architecture Gradle Plugin](https://github.com/bancolombia/scaffold-clean-architecture)：用于按照最佳实践创建基于Clean Architecture的Java和Kotlin应用程序的Gradle插件，由哥伦比亚银行开源。
* [Gradle Download Task](https://github.com/michel-kraemer/gradle-download-task)：向Gradle添加下载任务以显示进度信息。
* [JMH Gradle Plugin](https://github.com/melix/jmh-gradle-plugin)：该插件将JMH微基准测试框架与Gradle集成。
* [Licensee](https://github.com/cashapp/licensee)：Gradle插件可验证你的依赖图的许可证是否与你的期望相符，否则会导致构建失败。
* [Gretty](https://github.com/akhikhl/gretty)：Gretty是一个功能丰富的Gradle插件，用于在嵌入式Servlet容器上运行Web应用程序。
* [Gradle Node Plugin](https://github.com/node-gradle/gradle-node-plugin)：该插件使你能够在构建过程中使用许多基于Node.js的技术，而无需在系统本地安装Node.js。
* [Affected Module Detector](https://github.com/dropbox/AffectedModuleDetector)：Gradle插件用于确定哪些模块受到提交中的一组文件的影响。
* [Gradle Advanced Build Version Plugin](https://github.com/moallemi/gradle-advanced-build-version)：一个根据Git提交数量、日期和自动生成Android版本代码和版本名称的插件。
* [Marathon](https://github.com/MarathonLabs/marathon)：Marathon是一个帮助在最短时间内执行测试的项目。
* [Version Catalog Update Plugin](https://github.com/littlerobots/version-catalog-update-plugin)：该插件有助于保持Gradle版本目录Toml文件中的版本为最新版本。
* [PyGradle](https://github.com/linkedin/pygradle)：PyGradle是一个企业级Python构建系统，由LinkedIn开源。
* [Talaiot](https://github.com/cdsap/Talaiot)：Talaiot是一个可扩展的库，针对使用Gradle构建系统的团队。
* [Axion Release Plugin](https://github.com/allegro/axion-release-plugin)：Gradle发布和版本管理插件，由Allegro开源。
* [JaCoCo Android Gradle Plugin](https://github.com/arturdm/jacoco-android-gradle-plugin)：Gradle插件为每个Android应用程序和库项目变体的单元测试添加了完全配置的JacocoReport任务。
* [Gradle Git](https://github.com/ajoberstar/gradle-git)：Gradle的Git插件。
* [Gradle Tomcat Plugin](https://github.com/bmuschko/gradle-tomcat-plugin)：该插件提供了将Web应用程序部署到任何给定的Gradle构建中的嵌入式Tomcat Web容器的功能。
* [Gradle jOOQ Plugin](https://github.com/etiennestuder/gradle-jooq-plugin)：集成jOOQ代码生成工具的Gradle插件。
* [Gradle XCode Plugin](https://github.com/openbakery/gradle-xcodePlugin)：Gradle XCode Plugin通过在单个配置文件中指定构建设置，可以更轻松地构建Xcode项目。
* [Dependency Guard](https://github.com/dropbox/dependency-guard)：Gradle插件可帮助你防止意外的依赖项更改。
* [Gradle Nexus Publish Plugin](https://github.com/gradle-nexus/publish-plugin)：用于发布到Nexus仓库的Gradle插件。
* [Gradle License Plugin](https://github.com/jaredsburrows/gradle-license-plugin)：该插件提供了根据配置生成HTML许可证报告的任务。
* [License Gradle Plugin](https://github.com/hierynomus/license-gradle-plugin)：该插件将扫描并调整你的源文件以包含提供的标头。
* [Badass JLink Plugin](https://github.com/beryx/badass-jlink-plugin)：使用此Gradle插件，你可以用最少的努力创建模块化应用程序的自定义运行时镜像，即使它依赖于自动模块。
* [Gradle Static Analysis Plugin](https://github.com/novoda/gradle-static-analysis-plugin)：Gradle插件可轻松在不同的Android、Java或Kotlin项目中应用相同的静态分析工具设置。
* [Focus](https://github.com/dropbox/focus)：Gradle插件可通过排除不必要的模块来帮助你加快构建速度。
* [Gradle Android JUnit JaCoCo Plugin](https://github.com/vanniktech/gradle-android-junit-jacoco-plugin)：Gradle插件可从Android Gradle项目生成JaCoCo报告。
* [Gradle ErrorProne Plugin](https://github.com/tbroyer/gradle-errorprone-plugin)：该插件配置JavaCompile任务以使用Error Prone。
* [Android Unused Resources Remover Plugin](https://github.com/konifar/gradle-unused-resources-remover-plugin)：Gradle插件可删除Android项目中未使用的资源。
* [Gradle Linux Packaging Plugin](https://github.com/nebula-plugins/gradle-ospackage-plugin)：该插件使用规范的Gradle Copy Specs提供基于Gradle的系统包组装，通常适用于基于RedHat和Debian的发行版。
* [Gradle Code Quality Tools Plugin](https://github.com/vanniktech/gradle-code-quality-tools-plugin)：配置Checkstyle、PMD、CPD、Lint、Detekt和Ktlint的Gradle插件。
* [Gradle License Report](https://github.com/jk1/Gradle-License-Report)：用于生成有关Gradle项目依赖项许可证的报告的插件。
* [Gradle Git Properties](https://github.com/n0mer/gradle-git-properties)：这个Gradle插件可用于为基于Git的项目生成git.properties文件。
* [Gradle SSH Plugin](https://github.com/int128/gradle-ssh-plugin)：Gradle SSH Plugin提供SSH功能，例如Gradle上的命令执行或文件传输。
* [Gradle Launch4j](https://github.com/TheBoegl/gradle-launch4j)：使用Launch4j创建Windows可执行文件的Gradle插件。
* [Gradle Dependency Lock Plugin](https://github.com/nebula-plugins/gradle-dependency-lock-plugin)：允许使用动态依赖版本将其锁定到特定版本。
* [Gradle APT Plugin](https://github.com/tbroyer/gradle-apt-plugin)：Gradle插件使使用Java注解处理器变得更容易/更安全。
* [Gradle Sonatype Nexus Plugin](https://github.com/bmuschko/gradle-nexus-plugin)：该插件提供配置和上传工件到Sonatype Nexus的支持。
* [Gradle Changelog Plugin](https://github.com/JetBrains/gradle-changelog-plugin)：用于以“保留变更日志”风格解析和管理变更日志的插件。
* [Paraphrase](https://github.com/JakeWharton/paraphrase)：一个实验性的Gradle插件，可生成编译安全的格式字符串构建器。
* [Gradle Android Git Version](https://github.com/gladed/gradle-android-git-version)：一个Gradle插件，用于从Git标签计算Android友好的版本名称和代码。
* [Gradle Cargo Plugin](https://github.com/bmuschko/gradle-cargo-plugin)：Gradle插件通过Cargo为本地和远程容器提供部署功能。
* [Gradle Plugins](https://github.com/freefair/gradle-plugins)：Gradle插件集合。
* [Gradle TestSets Plugin](https://github.com/unbroken-dome/gradle-testsets-plugin)：Gradle构建系统的插件，允许指定测试集。
* [Gradle Witness](https://github.com/signalapp/gradle-witness)：一个支持对远程依赖项进行静态验证的Gradle插件。
* [Gradle One Jar](https://github.com/rholder/gradle-one-jar)：该插件将你当前项目的JAR及其所有依赖项汇总到One JAR所需的布局中，生成一个可运行的FatJar。
* [App Versioning](https://github.com/ReactiveCircus/app-versioning)：Gradle插件用于从Git标签延迟生成Android应用程序的versionCode和versionName。
* [Versioning](https://github.com/nemerosa/versioning)：Gradle插件从SCM分支生成版本信息。
* [Gradle Properties Plugin](https://github.com/stevesaliman/gradle-properties-plugin)：Properties是一个实用的插件，它可以改变Gradle从各种属性文件加载属性的方式。
* [Google Java Format Gradle Plugin](https://github.com/sherter/google-java-format-gradle-plugin)：Gradle 插件利用Google Java Format来格式化Gradle项目中的Java源文件。
* [Gradle Best Practices Plugin](https://github.com/autonomousapps/gradle-best-practices-plugin)：可检测Gradle插件中违反Gradle最佳实践的情况。
* [Gradle Credentials Plugin](https://github.com/etiennestuder/gradle-credentials-plugin)：Gradle插件用于存储和访问用于Gradle构建的加密凭证。
* [Gradle FatJar Plugin](https://github.com/musketyr/gradle-fatjar-plugin)：Gradle FatJar允许你创建包含所有依赖的JAR文件。
* [Gradle Nexus Staging Plugin](https://github.com/Codearte/gradle-nexus-staging-plugin)：Gradle插件提供关闭和提升/发布暂存仓库的任务。
* [Gradle BuildConfig Plugin](https://github.com/mfuerstenau/gradle-buildconfig-plugin)：Gradle Java项目的BuildConfig插件。
* [ClassPlugin](https://github.com/dinuscxj/ClassPlugin)：ClassPlugin是Gradle的一个灵活的类替换插件。
* [Frontend Gradle Plugin](https://github.com/siouan/frontend-gradle-plugin)：一体化Gradle Node/NPM/PNPM/Yarn插件，使用支持Corepack的包管理器构建、测试、部署JavaScript应用程序。
* [Enigma](https://github.com/christopherney/Enigma)：混淆器字符串加密的Gradle插件。
* [Extra Java Module Info Gradle plugin](https://github.com/gradlex-org/extra-java-module-info)：一个Gradle 6.8+插件，用于在模块化Java项目中将旧版Java库用作Java模块。
* [Clojurephant](https://github.com/clojurephant/clojurephant)：Gradle插件为Clojure和ClojureScript语言提供支持。
* [KtFmt Gradle](https://github.com/cortinico/ktfmt-gradle)：一个将KtFmt应用于你的Gradle构建的包装器，并重新格式化你的Kotlin源代码。
* [Badass Runtime Plugin](https://github.com/beryx/badass-runtime-plugin)：使用此Gradle插件，你可以为非模块化应用程序创建自定义运行时镜像。
* [Gratatouille](https://github.com/GradleUp/gratatouille)：Gratatouille是一个用于构建Gradle插件的框架。
* [Genymotion Gradle Plugin](https://github.com/Genymobile/genymotion-gradle-plugin)：一个插件，允许你从Gradle脚本轻松控制所有Genymotion设备。
* [Gradle Gatling Plugin](https://github.com/lkishalmi/gradle-gatling-plugin)：Gradle的Gatling插件。
* [Gatling Gradle Plugin](https://github.com/gatling/gatling-gradle-plugin)：Gradle的Gatling官方插件。
* [GCP Gradle Build Cache](https://github.com/androidx/gcp-gradle-build-cache)：Gradle远程缓存的实现，由Google Cloud Storage或AWS S3存储桶支持。
* [WSDL2Java Gradle Plugin](https://github.com/nilsmagnus/wsdl2java)：用于从WSDL文件生成Java源代码的Gradle插件。
* [Git-Version Gradle Plugin](https://github.com/palantir/gradle-git-version)：使用git describe生成版本字符串的Gradle插件。
* [Gradle Avro Plugin](https://github.com/davidmc24/gradle-avro-plugin)：允许轻松执行Avro的Java代码生成的Gradle插件。
* [Gradle Baseline Plugin](https://github.com/palantir/gradle-baseline)：为开发人员配置默认的代码质量工具。
* [Gradle AWS Plugin](https://github.com/classmethod/gradle-aws-plugin)：用于管理Amazon Web Services的Gradle插件。
* [Gradle Modules Plugin](https://github.com/java9-modularity/gradle-modules-plugin)：这个Gradle插件有助于使用Java 9平台模块系统。
* [Android SVG Drawable](https://github.com/avianey/androidsvgdrawable-plugin)：可在Android项目构建时从SVG文件生成合格的、特定于密度的PNG绘图。
* [OkBuck Gradle Plugin](https://github.com/uber/okbuck)：OkBuck是一个Gradle插件，允许开发人员在Gradle项目上使用Buck构建系统，由Uber开源。
* [Gradle Graal](https://github.com/palantir/gradle-graal)：一个Gradle插件，添加了下载、提取任务以及与GraalVM工具交互的任务。
* [Module Graph Assert](https://github.com/jraska/modules-graph-assert)：Gradle插件可帮助你保持模块图健康和精简。
* [Module Graph Plugin](https://github.com/iurysza/module-graph)：一个由Mermaid提供支持的用于可视化项目结构的Gradle插件。

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
* [ChatGPT](https://github.com/obiscr/ChatGPT)：本项目是一个支持在JetBrains系列IDE上运行ChatGPT的插件。
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
* [Devoxx Genie](https://github.com/devoxx/DevoxxGenieIDEAPlugin)：DevoxxGenie是IntelliJ IDEA的一个插件，它使用本地LLM(Ollama、LMStudio、GPT4All、Jan和Llama.cpp)和基于云的LLM来帮助审查、测试和解释你的项目代码。
* [RunVSAgent](https://github.com/wecode-ai/RunVSAgent)：RunVSAgent是一款创新的跨平台开发工具，使开发人员能够在JetBrains IDE或其他IDE平台中运行基于VSCode的编码代理和扩展，由微博开源。

## 其他

* [Gurux.DLMS](https://github.com/Gurux/gurux.dlms.java)：Gurux.DLMS库是一个高性能Java组件，可帮助你读取DLMS/COSEM兼容的电表、燃气表或水表。
* [FlowGate](https://github.com/vmware/flowgate)：FlowGate是一个与供应商无关的开源项目，可帮助企业集成设施系统数据和IT数据，形成其运营的单一整体视图，由VMWare开源。
* [ALARA](https://github.com/svalinn/ALARA)：ALARA的主要目的是计算整个核系统(包括裂变反应堆、聚变反应堆和加速器)中子辐射引起的诱导活化，由威斯康星大学麦迪逊分校开源。
* [OpenLCA](https://github.com/GreenDelta/olca-app)：OpenLCA是一款用于可持续性和生命周期评估的开源免费软件。
* [XraysLib](https://github.com/tschoonj/xraylib)：用于X射线荧光应用的X射线物质相互作用截面库。
* [Unique4j](https://github.com/prat-man/unique4j)：Unique4j是一个跨平台Java库，仅允许Java应用程序的单个实例运行，并支持第一个实例和后续实例之间的通信。
* [Portico](https://github.com/openlvc/portico)：Portico是一个开源HLA运行时基础设施(RTI)实现，它旨在确保开源和免费访问驱动HLA联盟所需的必要基础设施。
* [K Framework](https://github.com/runtimeverification/k)：K Framework是一种用于设计和建模编程语言和软件/硬件系统的工具。
* [OpenWayback](https://github.com/iipc/openwayback)：OpenWayback是全球网络档案馆用来在用户浏览器中“回放”存档网站的关键软件，由国际互联网保护联盟开源。
* [Alf.io](https://github.com/alfio-event/alf.io)：Alf.io是一款免费开源活动出席管理系统，专为关心客户隐私、安全和公平定价政策的活动组织者而开发。
* [AsTeRICS](https://github.com/asterics/AsTeRICS)：AsTeRICS是一个用于辅助技术的免费开源图形构建集。
* [JIDT](https://github.com/jlizier/jidt)：JIDT提供了复杂系统中分布式计算的信息论测量的独立、开源代码Java实现。
* [Metis](https://github.com/europeana/metis-framework)：Metis是数据发布框架，包括客户端应用程序和许多数据处理服务，由欧洲数位图书馆开源。
* [Hello eBPF](https://github.com/parttimenerd/hello-ebpf)：允许直接用Java编写eBPF程序。
* [MetarParser](https://github.com/mivek/MetarParser)：这个Java库提供了Metar和TAF解码器。
* [Nginx Java Parser](https://github.com/odiszapc/nginx-java-parser)：基于ANTLR4语法的Nginx配置解析器。
* [ShrinkWrap Resolvers](https://github.com/shrinkwrap/resolver)：ShrinkWrap Resolvers是一个Java API，旨在简化从仓库系统获取工件的过程，由JBoss开源。
* [Lorem](https://github.com/mdeanda/lorem)：一个非常有用的Java Lorem Ipsum生成器。
* [NFCTools](https://github.com/grundid/nfctools)：NFCTools是Java中NFC库和工具的集合。
* [Java ADS-B](https://github.com/openskynetwork/java-adsb)：这是Java的Mode S和ADS-B解码库。
* [Kumo](https://github.com/kennycason/kumo)：Kumo的目标是用Java创建一个功能强大且用户友好的词云API。
* [Amadeus Java](https://github.com/amadeus4dev/amadeus-java)：Amadeus为旅游行业提供了丰富的API。
* [SourceAFIS](https://github.com/robertvazan/sourceafis-java)：SourceAFIS Java是SourceAFIS(一种用于识别人类指纹的算法)的纯Java端口，它可以1:1比较两个指纹或1:N在大型数据库中搜索匹配的指纹。

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
* [30 Seconds Of Java 8](https://github.com/hellokaton/30-seconds-of-java8)：你可以在30秒或更短时间内收集有用的Java 8代码片段。
* [Note](https://github.com/scalad/Note)：常规Java工具、算法、加密、数据库、面试题、源代码分析、解决方案。
* [Java Lambda Internals](https://github.com/CarpenterLee/JavaLambdaInternals)：深入理解Java函数式编程和Streams API。
* [Java Learning](https://github.com/brianway/java-learning)：旨在打造在线最佳的Java学习笔记，含博客讲解和源码实例，包括Java SE和Java Web。
* [Java Tutorial](https://github.com/dunwu/java-tutorial)：Java Tutorial是一个Java教程。
* [Java Keeper](https://github.com/Jstarfish/JavaKeeper)：Java工程师必备架构体系知识总结：涵盖分布式、微服务、RPC等互联网公司常用架构，以及数据存储、缓存、搜索等必备技能。
* [Java 8 Lambdas Exercises](https://github.com/RichardWarburton/java-8-lambdas-exercises)：该仓库包含Java 8 Lambdas书籍的支持材料。
* [Six Finger](https://github.com/bin392328206/six-finger)：从Java基础、Java Web基础到常用的框架再到面试题、微服务、分布式、大数据都有完整的教程，几乎涵盖了Java必备的知识点。
* [WhatsMars](https://github.com/javahongxi/whatsmars)：Java生态研究(Spring Boot + Redis + Dubbo + RocketMQ + ElasticSearch)。
* [BestJavaer](https://github.com/crisxuan/bestJavaer)：这是一个成为更好的Java程序员的系列教程。
* [Better Java](https://github.com/cxxr/better-java)：编写现代Java的资源。
* [Java Bible](https://github.com/hellokaton/java-bible)：这里记录了一些技术摘要，以Java为主。
* [Java Learning](https://github.com/Tyson0314/Java-learning)：Java相关知识总结，包括Java基础、MySQL、Spring Boot、Mybatis、Redis、RabbitMQ等等，面试必备。
* [JavaNote](https://github.com/Seazean/JavaNote)：Java学习笔记，记录作者从编程入门到深入学习的所有知识。
* [Java Blog](https://github.com/farmerjohngit/myblog)：有深度的Java技术博客。
* [Tutorial](https://github.com/zhonghuasheng/Tutorial)：后端(Java/Golang)全栈知识架构体系总结。
* [Java Tutorial For Beginners](https://github.com/in28minutes/java-tutorial-for-beginners)：Java初学者教程(含500个代码示例)。
* [Java Notes](https://github.com/PansonPanson/Java-Notes)：计算机科学基础知识、Java开发、后端/服务端、面试相关。
* [LearningSummary](https://github.com/yehongzhi/learningSummary)：涵盖大部分Java进阶需要掌握的知识。
* [Java Best Practices](https://github.com/in28minutes/java-best-practices)：Java应用程序编码、设计和架构的最佳实践。
* [JavaYouth](https://github.com/youthlql/JavaYouth)：主要是Java技术栈的文章。
* [Java RoadMap](https://github.com/fuzhengwei/RoadMap)：Java后端开发技能路书。
* [MindManager](https://github.com/xingchenpro/MindManager)：Java技术体系思维导图。
* [JavaOk](https://github.com/xjjdog/javaok)：Java发展路线技术要点。
* [JCFInternals](https://github.com/CarpenterLee/JCFInternals)：深入理解Java集合框架。
* [Java Concurrency](https://github.com/CL0610/Java-concurrency)：Java并发知识点总结。
* [Java Concurrency](https://github.com/code-review-checklists/java-concurrency)：Java并发知识总结。

#### 大数据教程

* [BigData-Notes](https://github.com/heibaiying/BigData-Notes)：大数据入门指南。
* [Flink Learning](https://github.com/zhisheng17/flink-learning)：含Flink入门、概念、原理、实战、性能调优、源码解析等内容。
* [Flink Recommand System Demo](https://github.com/will-che/flink-recommandSystem-demo)：基于Flink实现的商品实时推荐系统。
* [DB Tutorial](https://github.com/dunwu/db-tutorial)：DB Tutorial是一个数据库教程。
* [Kafka For Beginners](https://github.com/conduktor/kafka-beginners-course)：这是Conduktor的Kafka初学者课程的配套仓库。
* [Movie Recommend](https://github.com/LuckyZXL2016/Movie_Recommend)：基于Spark的电影推荐系统，包含爬虫项目、Web网站、后台管理系统以及Spark推荐系统。
* [BigData Guide](https://github.com/MoRan1607/BigDataGuide)：大数据学习指南，从零开始学习大数据开发，包含大数据学习各个阶段资汇总。
* [Learning Spark](https://github.com/databricks/learning-spark)：Learning Spark书中的示例。
* [Spark Doc Zh](https://github.com/apachecn/spark-doc-zh)：Spark官方文档中文版。
* [Coolplay Spark](https://github.com/lw-lin/CoolplaySpark)：Coolplay Spark包含Spark源代码解析、Spark类库、Spark代码等。
* [Bigdata Growth](https://github.com/collabH/bigdata-growth)：大数据知识仓库，涉及数据仓库建模、实时计算、大数据、数据中台、系统设计、Java、算法等。

#### Spring教程

* [Spring Boot Demo](https://github.com/xkcoding/spring-boot-demo)：Spring Boot Demo是一个用来深度学习并实战Spring Boot的项目。
* [Spring Boot Examples](https://github.com/ityouknow/spring-boot-examples)：Spring Boot使用的各种示例，以最简单、最实用为标准，此开源项目中的每个示例都以最小依赖，最简单为标准，帮助初学者快速掌握Spring Boot各组件的使用。
* [SpringAll](https://github.com/wuyouzhuguli/SpringAll)：循序渐进，学习Spring Boot、Spring Batch、Spring Cloud、Spring Cloud Alibaba、Spring Security。
* [Spring Boot Reference Guide](https://github.com/qibaoguang/Spring-Boot-Reference-Guide)：Spring Boot Reference Guide中文翻译。
* [SpringBoot Labs](https://github.com/yudaocode/SpringBoot-Labs)：一个涵盖六个专栏：Spring Boot 2.X、Spring Cloud、Spring Cloud Alibaba、Dubbo、分布式消息队列、分布式事务的仓库。
* [Spring Cloud Learning](https://github.com/forezp/SpringCloudLearning)：史上最简单的Spring Cloud教程源码。
* [Spring Boot Learning Example](https://github.com/JeffLi1993/springboot-learning-example)：Spring Boot实践学习案例，是Spring Boot初学者及核心技术巩固的最佳实践。
* [Spring Boot Learning](https://github.com/dyc87112/SpringBoot-Learning)：打造全网内容最全，比收费教程更好的Spring Boot免费教程。
* [Spring Boot Learning](https://github.com/loda-kun/spring-boot-learning)：Spring Boot、Spring Cloud完整指南，越南语示例代码。
* [Spring Petclinic](https://github.com/spring-projects/spring-petclinic)：Spring Petclinic是一个使用Maven或Gradle构建的Spring Boot应用程序。
* [Mini Spring Cloud](https://github.com/DerekYRC/mini-spring-cloud)：Mini Spring Cloud是简化版的Spring Cloud框架，能帮助你快速熟悉Spring Cloud源码及掌握其核心原理。
* [Spring Boot Demo](https://github.com/roncoo/spring-boot-demo)：Spring Boot的基础教程。
* [FlyClould](https://github.com/mxdldev/spring-cloud-flycloud)：FlyClould微服务实战项目框架。
* [Master Spring Boot](https://github.com/in28minutes/master-spring-and-spring-boot)：Spring和Spring Boot初学者教程。
* [Spring Cloud Learning](https://github.com/dyc87112/SpringCloud-Learning)：本项目内容为Spring Cloud教程的程序样例。
* [Spring Boot Study](https://github.com/xuwujing/springBoot-study)：Spring Boot学习的相关工程并辅以博文讲解。
* [Spring Boot Learning Example](https://github.com/rhwayfun/spring-boot-learning-examples)：Spring Boot知识点整理、工程实践，并结合工作案例进行深入。
* [Spring Boot Samples](https://github.com/netgloo/spring-boot-samples)：Netgloo的Spring Boot示例。
* [SpringBoot](https://github.com/527515025/springBoot)：Spring Boot框架与其它组件结合如JPA、MyBatis、WebSocket、Security、Shiro、Cache等的教程。
* [Spring Cloud Examples](https://github.com/ityouknow/spring-cloud-examples)：Spring Cloud使用的各种示例，以最简单、最实用为标准。
* [Spring Cloud Learning](https://github.com/macrozheng/springcloud-learning)：一套涵盖大部分核心组件使用的Spring Cloud教程，包括Spring Cloud Alibaba及分布式事务Seata，基于Spring Cloud Greenwich及Spring Boot 2.1.7。
* [JavaEE Test](https://github.com/lenve/JavaEETest)：Spring、Spring MVC、MyBatis、Spring Boot案例。
* [SSM](https://github.com/liyifeng1994/ssm)：手把手教你整合最优雅SSM框架：Spring MVC + Spring + MyBatis。
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
* [Spring Cloud REST TCC](https://github.com/prontera/spring-cloud-rest-tcc)：以Spring Cloud Netflix作为服务治理基础，展示基于TCC思想所实现的分布式事务解决方案。
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
* [Spring Boot Tutorial](https://github.com/timebusker/spring-boot)：Spring Boot项目实践总结。

#### 算法和数据结构教程

* [LeetCode Animation](https://github.com/MisterBooo/LeetCodeAnimation)：用动画的形式呈现解LeetCode题目的思路。
* [Hello Algo](https://github.com/krahets/hello-algo)：动画图解、一键运行的数据结构与算法教程。
* [The Algorithms](https://github.com/TheAlgorithms/Java)：所有算法的Java实现。
* [LeetCode Master](https://github.com/youngyangyang04/leetcode-master)：《代码随想录》LeetCode刷题攻略：200道经典题目刷题顺序，共60w字的详细图解，视频难点剖析，50余张思维导图。
* [Hello Algorithm](https://github.com/geekxh/hello-algorithm)：一套针对小白的完整的算法训练流程。
* [LeetCode](https://github.com/doocs/leetcode)：本项目包含LeetCode、《剑指Offer(第2版)》、《剑指Offer(专项突击版)》、《程序员面试金典(第6版)》等题目的相关题解。
* [Algorithms](https://github.com/williamfiset/Algorithms)：该仓库的目标是演示如何以最简单、最优雅的方式正确实现常见的数据结构和算法。
* [CodeLibrary](https://github.com/indy256/codelibrary)：C++、Java、Kotlin、Python和Rust中的算法和数据结构集合。
* [Awesome Java LeetCode](https://github.com/Blankj/awesome-java-leetcode)：LeetCode算法与Java解决方案。
* [LeetCode](https://github.com/yuanguangxin/LeetCode)：LeetCode题目分类与面试问题整理。
* [JS Sorting Algorithm](https://github.com/hustcc/JS-Sorting-Algorithm)：一本关于排序算法的GitBook在线书籍《十大经典排序算法》，多语言实现。
* [Project Euler Solutions](https://github.com/nayuki/Project-Euler-solutions)：用于解决Java、Python、Mathematica、Haskell中的欧拉计划问题的可运行代码。
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
* [Leetcode](https://github.com/qiyuangong/leetcode)：Leetcode Python和Java解决方案。
* [Leetcode](https://github.com/wind-liang/leetcode)：Leetcode详细通俗题解。
* [Algorithm & Data Structure Notes](https://github.com/jainaman224/Algo_Ds_Notes)：用于学习和实现算法和数据结构的综合资源。

#### 软件工程教程

* [Java Design Patterns](https://github.com/iluwatar/java-design-patterns)：用Java实现的设计模式教程。
* [ITStack Demo Design](https://github.com/fuzhengwei/itstack-demo-design)：《重学Java设计模式》是一本互联网真实案例实践书籍。
* [Awesome Low Level Design](https://github.com/ashishps1/awesome-low-level-design)：该仓库包含学习低级设计(LLD)/面向对象设计(OOD)和准备面试的资源。
* [Awesome Architect](https://github.com/xingshaocheng/architect-awesome)：后端架构师技术图谱。
* [DesignPattern](https://github.com/youlookwhat/DesignPattern)：Java 23种设计模式全归纳。
* [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples)：这是Vaughn Vernon所著的《实现领域驱动设计》一书中的限界上下文示例。
* [Migration](https://github.com/phodal/migration)：《系统重构与迁移指南》手把手教你分析、评估现有系统、制定重构策略、探索可行重构方案、搭建测试防护网、进行系统架构重构、服务架构重构、模块重构、代码重构、数据库重构、重构后的架构守护。
* [FTGO Example Application](https://github.com/microservices-patterns/ftgo-application)：这是《微服务模式》一书的示例代码。
* [Head First Design Patterns](https://github.com/bethrobson/Head-First-Design-Patterns)：《Head First设计模式》一书代码。
* [Buckpal](https://github.com/thombergs/buckpal)：这个仓库以六角形架构风格实现了一个小型Web应用程序。
* [Three High Import](https://github.com/qiurunze123/threadandjuc)：高并发、高可靠、高性能导入系统-高并发多线程进阶。
* [PostgreSQL Event Sourcing](https://github.com/eugene-khyst/postgresql-event-sourcing)：这是一个使用PostgreSQL作为事件存储的事件源系统的参考实现，并使用Spring Boot构建。

#### Java安全教程

* [Spring Boot Vulnerability Exploit](https://github.com/LandGrey/SpringBootVulExploit)：Spring Boot相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估。
* [Learn Java Bug](https://github.com/threedr3am/learnjavabug)：Java安全相关的漏洞和技术Demo。
* [HackJava](https://github.com/HackJava/HackJava)：本项目是记录自己在学习研究Java安全过程中遇到的优秀资源，包括Java安全的多个细分领域，如Java漏洞分析和Java代码审计以及Java开发的应用程序组件协议甚至Java本身的安全问题等。
* [JavaSec](https://github.com/Maskhe/javasec)：作者学习Java安全的一些总结，主要是安全审计相关。
* [JavaThings](https://github.com/phith0n/JavaThings)：Java安全漫谈笔记相关内容。
* [Hello Java Sec](https://github.com/j3ers3/Hello-Java-Sec)：Hello Java Security通过结合漏洞场景和安全编码，帮助安全和研发团队理解漏洞原理。
* [SecGuide](https://github.com/Tencent/secguide)：面向开发人员梳理的代码安全指南，旨在梳理API层面的风险点并提供详实可行的安全编码方案。
* [JavaWeb Sec](https://github.com/javaweb-sec/javaweb-sec)：这是一个不定期更新的免费开源的Java Web安全相关知识归纳总结、培训的项目。
* [SecurityList](https://github.com/ax1sX/SecurityList)：Web安全和代码审计列表。
* [Java Security Learning](https://github.com/Drun1baby/JavaSecurityLearning)：该项目的目的是学习Java安全的时候能够有一条比较清晰的学习路线。
* [Java Sec Code](https://github.com/JoyChou93/java-sec-code)：Java Sec Code是一个非常强大且友好的学习Java漏洞代码的项目。

#### 其他技术教程

* [RabbitMQ Tutorials](https://github.com/rabbitmq/rabbitmq-tutorials)：该项目包含RabbitMQ教程的代码及其对各种语言的移植。
* [Leave Sample](https://github.com/ouchuangxin/leave-sample)：本代码源于极客时间《DDD实战课》，DDD知识体系和代码详解可参考专栏。
* [API Samples](https://github.com/youtube/api-samples)：YouTube API的代码示例，包括YouTube Data API、YouTube Analytics API和YouTube Live Streaming API。
* [RxJava Samples](https://github.com/rengwuxian/RxJavaSamples)：RxJava 2和Retrofit结合使用的几个最常见使用方式举例。
* [Vert.x 4 Examples](https://github.com/vert-x3/vertx-examples)：该仓库包含一系列Vert.x 4示例。
* [RxJava2 Examples](https://github.com/nanchen2251/RxJava2Examples)：从RxJava 1跳到RxJava 2(学习RxJava2 )的例子Demo。
* [Intro to RxJava](https://github.com/Froussios/Intro-To-RxJava)：本指南旨在向初学者响应式程序员介绍RxJava实现JVM响应式编程的完整功能。
* [Java EE 7 Samples](https://github.com/javaee-samples/javaee7-samples)：该仓库由Java EE 7示例和单元测试组成。
* [AWS Lambda Developer Guide](https://github.com/awsdocs/aws-lambda-developer-guide)：该仓库包含AWS Lambda开发人员指南的其他资源。
* [Netty Learning Example](https://github.com/sanshengshui/netty-learning-example)：Netty实践学习案例。
* [Netty in Action](https://github.com/normanmaurer/netty-in-action)：该仓库包含《Netty in Action》一书所有章节的源代码。
* [Netty Demos](https://github.com/waylau/netty-4-user-guide-demos)：《Netty 4.x用户指南》/《Netty原理解析与开发实战》文中用到的例子源码。
* [MyBatis Plus Samples](https://github.com/baomidou/mybatis-plus-samples)：MyBatis Plus示例代码。
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
* [JavaWeb Project Source](https://github.com/coderzcr/JavaWeb-Project-Source-Share)：分享基于Servlet、SSH、SSM、SpringBoot、SpringCloud等流行技术实现的JavaWeb项目。

#### 面试宝典

* [Interviews](https://github.com/kdn251/interviews)：你的软件工程技术面试个人指南。
* [ToBeTopJavaer](https://github.com/hollischuang/toBeTopJavaer)：一份Java面试宝典。
* [Tech Interview](https://github.com/gyoogle/tech-interview-for-developer)：新开发者主要知识技能面试百科。
* [Awesome System Design](https://github.com/ashishps1/awesome-system-design-resources)：该仓库包含用于学习系统设计概念和准备面试的免费资源。
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
* [Java Interview](https://github.com/gzc426/Java-Interview)：Java面试整理项目。
* [Java Interview](https://github.com/enhorse/java-interview)：Java开发人员面试问题和答案。
* [AlgoDeck](https://github.com/teivah/algodeck)：帮助你准备算法和数据结构以及系统设计面试。
* [Bank Interview](https://github.com/sty945/bank_interview)：银行笔试面试经验分享及资料分享。
* [Java Interview](https://github.com/xbox1994/Java-Interview)：经历BAT面试后总结的高级Java后台开发面试指南。
* [JavaInterview](https://github.com/hello-java-maker/JavaInterview)：Java面试、Java后端技术学习指南。
* [JavaHome](https://github.com/whx123/JavaHome)：一份超级详细的Java面试题。
* [Java Interview Advanced](https://github.com/shishan100/Java-Interview-Advanced)：互联网Java进阶面试训练营。
* [Java Interview Tutorial](https://github.com/Java-Edge/Java-Interview-Tutorial)：涵盖国际大厂Java/数据库/DDD/设计模式/微服务/中间件/AI大模型应用/区块链开发最佳实践。
* [Java Interview](https://github.com/cosen1024/Java-Interview)：一份通向理想互联网公司的面试汇总，包括Java基础、Java并发、JVM、MySQL、Redis、Spring、MyBatis、Kafka、计算机操作系统、计算机网络、系统设计、分布式、Java项目实战等。
* [EasyJob](https://github.com/chucheng92/EasyJob)：互联网求职面试题、知识点和面经整理。
* [Java Interview](https://github.com/DuHouAn/Java)：本仓库是对Java的一些基础知识、数据库知识、以及框架知识进行收集、整理。
* [JavaInterview](https://github.com/gsjqwyl/JavaInterview)：Java面试整理，涵盖基础、JVM、线程并发、框架、MySQL、微服务、Redis、中间件、数据结构与算法等。
* [Java Notes](https://github.com/lvminghui/Java-Notes)：一份面向Java初学者和初级工程师的知识点总结和面试题解析，着重关注面试中最常见的知识点。
* [Interview](https://github.com/hadyang/interview)：本文档收集整理计算机、Java相关基础知识。
* [YCBlogs](https://github.com/yangchong211/YCBlogs)：技术博客笔记大汇总，包括Java基础、线程、并发、数据结构、Android技术博客等。
