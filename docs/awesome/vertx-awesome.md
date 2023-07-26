<div class="github-widget" data-repo="vert-x3/vertx-awesome"></div>
## Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-logo.svg?sanitize=true" align="right" width="250">](http://vertx.io)

*Awesome Vert.x* 是一个很棒的框架、库或其他相关组件的列表
[Vert.x](https://github.com/eclipse/vert.x).

如果您希望您的组件出现在这里，请向此存储库发送拉取请求以添加它.

请注意，我们不能保证此列表中所有内容的稳定性或生产价值，除非它有
图标 <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px">
在它的旁边. 这个图标表示该组件是官方的一部分
[Vert.x stack](https://vertx.io/docs/).



## Books

* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) 克莱门特埃科菲
* [Vert.x in Action](https://www.manning.com/books/vertx-in-action) 通过 Julien Ponge

## Build tools

* [Vert.x Maven plugin](https://github.com/reactiverse/vertx-maven-plugin)
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)
* [Vert.x Codegen Gradle plugin](https://github.com/bulivlad/vertx-codegen-plugin) - 一个 Gradle 插件，用于促进 Vert.x Java 项目的代码生成使用.

## Web Frameworks

* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - 创建 JAX-RS [Jersey](https://jersey.java.net/) Vert.x 中的资源.
* [Kovert](https://github.com/kohesive/kovert) - 用于 Kotlin + Vert.x Web 的隐形 REST 框架.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - Vert.x 的开放网络框架.
* [QBit](https://github.com/advantageous/qbit) - REST 和 WebSocket 方法调用编组和反应库.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - Persistence for REST resources in the filesystem or a redis database.
* [Jubilee](https://github.com/isaiah/jubilee) - 基于 Vert.x 3 构建的机架兼容 Ruby HTTP 服务器.
* [Knot.x](https://github.com/Cognifide/knotx) - 适用于基于 Vert.x 3 的现代网站的高效和高性能集成平台.
* [Irked](https://github.com/GreenfieldTech/irked) - 用于 Vert.x Web 的基于注释的配置，具有用于 REST 的控制器框架和富有表现力的 API.
* [REST.VertX](https://github.com/zandero/rest.vertx) - 轻量级 JAX-RS (RestEasy)，例如用于 Vert.x 垂直行业的注释处理器.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) - 用于 JVM 的实时客户端服务器框架，支持 WebSockets 和具有跨浏览器回退的服务器发送事件.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) - 在 Vert.x 上运行 Vaadin 应用程序.
* [Serverx](https://github.com/lukehutch/serverx) - 允许您仅使用路由处理程序注释快速轻松地设置 Vert.x 驱动的服务器.
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next) - Cloudopt Next 是一个非常轻量级的、现代的、基于 JVM 的全堆栈 kotlin 框架，旨在构建模块化、易于测试的 JVM 应用程序，支持 Java、Kotlin 语言，由最好的 Java 库和标准精心打造.
* [Donkey](https://github.com/AppsFlyer/donkey) - 为易用性和性能而构建的现代 Clojure HTTP 服务器和客户端.
* [SCX](https://github.com/scx567888/scx) - 一个开放易用的web框架，大部分功能基于注解.
* [vertx-rest](https://github.com/dream11/vertx-rest) - 对 resteasy-vertx 的抽象，以简化基于 JAX-RS 注释编写 Vert.x REST 应用程序.

## Authentication Authorisation


* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - 使用实现的 Vert.x 身份验证/授权 [pac4j](http://www.pac4j.org/).

## Database Clients

*连接数据库的客户端*

* 关系数据库
  * [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 高性能反应式 SQL 客户端.
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 围绕 JDBC 数据源的异步接口.
  * [MySQL / PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - MySQL/PostgreSQL 的异步客户端.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - 反应式 PostgreSQL 客户端.
  * [database](https://github.com/susom/database) - Oracle、PostgreSQL、SQL Server、HyperSQL 等的客户端，专为安全性、正确性和易用性而设计.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - 执行类型安全的异步 SQL 并使用 jOOQ 生成代码.
  * [jOOQx](https://github.com/zero88/jooqx) - 利用来自 jOOQ DSL 的类型安全 SQL 的强大功能，并使用来自 Vert.x 的反应式和非阻塞 SQL 驱动程序.

* NoSQL 数据库
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于与 MongoDB 数据库交互的异步客户端.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 与 Redis 交互的异步 API.
  * [Cassandra](https://github.com/vert-x3/vertx-cassandra-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 允许应用程序与 Cassandra 服务交互的 Vert.x 客户端.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - 与 Cassandra 和 Cassandra 映射交互的异步 API.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - Non-blocking OrientDB server integration.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - 非阻塞 Bitsy Graph 服务器集成.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) - Marklogic 数据库服务器的异步客户端.
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) - 非阻塞 SirixDB HTTP 服务器.
  * [DGraph](https://github.com/aesteve/vertx-dgraph-client)  - 有关如何构建 Vert.x gRPC 兼容客户端的示例. 此处定位 [dgraph](https://dgraph.io)
  * [RxFirestore](https://github.com/pjgg/rxfirestore) - 以反应方式编写的非阻塞 Firestore SDK.
  * [MongoDB](https://github.com/imrafaelmerino/vertx-mongodb-effect) - 纯功能性和反应性 MongoDB 客户端之上 [Vert.x Effect](https://github.com/imrafaelmerino/vertx-mongodb-effect) . 完全支持重试、回退和恢复操作.
  * [Aerospike](https://github.com/dream11/vertx-aerospike-client)  - 与 Aerospike 服务器交互的异步和非阻塞 API. 用途 [AerospikeClient's](https://github.com/aerospike/aerospike-client-java) 内部异步命令并在 Vert.x 上下文中处理结果.

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) - MySQL 和 MongoDB 的非阻塞 POJO 映射.
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - 用于进入 MySQL 复制流的 Vert.x 客户端.

## Integration

* 服务器发送的事件
  * [jEaSSE](https://github.com/mariomac/jeasse)  - Java 简易 SSE.  SSE 的简单、轻量级实现.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) - Vert.x SSE 实现 + 事件总线 SSE 桥.

* 邮件
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 异步 SMTP 客户端.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) - 桥接到 EventBus 的 SMTP 服务器.

* 休息
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) - 一个高度可扩展的适配器，用于使用 Vert.x 进行改造.
  * [openapi4j adapter for Vert.x](https://github.com/openapi4j/openapi4j/tree/master/openapi-operation-adapters/openapi-operation-vertx) - OpenAPI 3 请求验证器和路由器工厂替代方案.
  * [Vert.x Effect HTTP client](https://github.com/imrafaelmerino/vertx-effect) - 纯功能性和反应性 HTTP 客户端使用 [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) 具有 OAuth 支持和重试、回退和恢复操作.

* 文件服务器
  * [Vert.x TFTP Client](https://github.com/OneManCrew/vertx-tftp-client) - Vert.x 的 TFTP 客户端支持下载/上传文件.
*消息
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-bridge) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用 Vert.x 生产者和消费者 API 与 AMQP 1.0 服务器交互.
  * [MQTT](https://github.com/vert-x3/vertx-mqtt) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 提供两个不同的组件：一个 MQTT 服务器，用于处理所有 MQTT 通信和与客户端的消息交换，以及一个 MQTT 客户端，用于发送和接收针对 MQTT 代理的消息.
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 一个 RabbitMQ 客户端（AMQP 0.9.1）.
  * [Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 卡夫卡客户端.
  * [kafka](https://github.com/cyngn/vertx-kafka) - 用于消费和生产消息的 Kafka 客户端.
  * [STOMP](https://github.com/vert-x3/vertx-stomp) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Kafka 客户端和服务器.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) - ZeroMQ 事件总线桥.
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) - 蔚蓝 [ServiceBus](https://azure.microsoft.com/en-us/services/service-bus/) 生产者和消费者（完全异步，不使用 Microsoft Azure SDK）.
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) - 使用 AMQP 1.0 协议向/从 Apache Kafka 发送/接收消息的桥.
  * [Vert.x Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - Apache Kafka 客户端，用于从/向 Apache Kafka 集群读取和发送消息.
  * [The White Rabbit](https://github.com/viartemev/the-white-rabbit) - 基于 Kotlin 协程的异步 RabbitMQ (AMQP) 客户端.
  * [WAMP Broker](https://github.com/i22-digitalagentur/vertx-wamp) - 可以嵌入到 Vert.x 应用程序中的 WAMP 代理.

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 用于 Vert.x 事件总线的 Java 连接器架构适配器.
  * [Weld](https://github.com/weld/weld-vertx) - 将 CDI 编程模型引入 Vert.x 生态系统（将 CDI 观察器方法注册为 Vert.x 消息消费者、CDI 驱动的 Verticles、以声明方式定义路由等）.

* 流星
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - 通过 Vert.x 事件总线支持 Meteor 集成.

* 指标
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) Vert.x Metrics SPI 的实现.
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用 DropWizard 指标的指标实施.
  * [Micrometer metrics](https://github.com/vert-x3/vertx-micrometer-metrics) <img src="https://raw.githubusercontent.com/vert-x3/vertx-awesome/master/vertx-favicon.svg?sanitize=true" alt="(stack)" title="Vert.x Stack" height="16px"> - 使用 Micrometer 指标的指标实施.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) Vert.x 的指标客户端.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) Vert.x 的客户端库.

* Netflix - Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) - 从 Vert.x 应用程序发出 Hystrix 仪表板的指标 [Hystrix](https://github.com/Netflix/Hystrix).

* 飞镖
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) 整合为 [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) 和使用 dart:js 的普通 SockJS.

* 推送通知
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) - 从您的 Vert.x 应用程序向（移动/网络）应用程序发送推送通知 [OneSignal](https://onesignal.com/).

* CNCF 云事件
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) - 发送和接收 [CloudEvents](https://cloudevents.io/) 使用 [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) 对于 CloudEvents.

## Middleware

* [Apache Camel](https://camel.apache.org/components/vertx-component.html) - [Apache Camel](http://camel.apache.org/) 用于桥接 Camel 与 Vert.x 事件总线的组件.
* [Gateleen](https://github.com/swisspush/gateleen) - 基于 Vert.x 的中间件库，用于构建高级 JSON/REST 通信服务器.
* [Gravitee.io](https://gravitee.io) - 一个OSS API平台，包括一个API网关和一个基于Vert.x Core / Vert.x Web等模块的OAuth2 / OIDC授权服务器.
* [API Framework](https://github.com/vinscom/api-framework)  - 基于 Vert.x 和 Glue 的微服务框架消除了独立应用程序和无服务应用程序之间的区别. 所有服务都可以在独立服务器中运行，但如果需要，可以使用相同的代码库将任何服务作为无服务器应用程序运行.

## Language Support

*对 Vert.x 的编程语言支持*

* [Python](https://github.com/vert-x3/vertx-lang-python) - Python 支持.
* [EcmaScript](https://github.com/reactiverse/es4x) - EcmaScript &gt;=6 (JavaScript) 支持.
* [Php](https://github.com/vert-x-cn/vertx-lang-jphp) - PHP支持.

*语言扩展*

* [Grooveex](https://github.com/aesteve/grooveex) - 语法糖 + 实用程序（DSL 构建器等） [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy).

## Reactive

* [vertx-util](https://github.com/cyngn/vertx-util) - Vert.x 的轻量级承诺和闩锁.
* [QBit](https://github.com/advantageous/qbit)  - 异步类型的 actor-like lib，可以在 Vert.x 异步回调中轻松运行. 回调管理.
* [VxRifa](https://nsforth.github.io/vxrifa) - Vert.X 的实用程序库，允许在通过 EventBus 的通信中使用强类型接口.
* [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect)  - 基于 IO Monad 的纯函数式和反应式库，用于实现任何复杂的流程. 完全支持重试、回退和恢复操作.
* [SmallRye Mutiny](https://smallrye.io/smallrye-mutiny/) - 用于 Java 的直观事件驱动的反应式编程库 [bindings for Vert.x](https://smallrye.io/smallrye-mutiny-vertx-bindings/).

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - 同步但非操作系统线程阻塞的 Verticle.

## Vert.x Event Bus Clients

*将应用程序连接到 Vert.x 事件总线的客户端*

* [C++11](https://github.com/julien3/vertxbuspp) - C++11 事件总线客户端.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) - vertxbus.js 的 Java 实现.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) - Java 和 Android 事件总线客户端.
* [Java](https://github.com/danielstieger/javaxbus) - 使用纯 TCP 套接字 I/O 的简单 Java 事件总线客户端.
* [CLI](https://github.com/cinterloper/vxc) - Vert.x 事件总线的命令行二进制客户端 - JSON 管道，发出 JSON.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) - 事件总线客户端 [Apple's Swift](https://swift.org) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) - 使用 Python 的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) - C99 的事件总线客户端使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)- 使用 Go-lang 的事件总线客户端 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)- 事件总线客户端 [Pharo Smalltalk](http://pharo.org/) 使用 [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) - 通过 Java 代码在 JavaScript 中支持事件总线.
* [Elixir](https://github.com/PharosProduction/ExVertx) - 事件总线支持使用 TCP 套接字的 Elixir 应用程序.
* [Rust](https://github.com/aesteve/vertx-eventbus-client-rs) - 通过 TCP 的 Rust 应用程序事件总线客户端.

## Vert.x Event Bus Extensions

* [Eventbus Service](https://github.com/wowselim/eventbus-service) - 通过简单的 Kotlin 接口进行类型安全事件总线通信的代码生成器.

## Cluster Managers

*Vert.x 集群管理器 SPI 的实现*

* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups 集群管理器.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) - 一个 [Atomix](http://atomix.io) 基于 Vert.x 3 的集群管理器实现.
* [Consul Cluster Manager](https://github.com/reactiverse/consul-cluster-manager) - 领事集群管理器.

## Cloud Support

* [AWS SDK](https://github.com/reactiverse/aws-sdk) - 将 AWS Java SDK v2（异步）与 Vert.x 结合使用

## Microservices

* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) 服务发现和查询您的 Vert.x 微服务.
* [Resilience4j](https://github.com/resilience4j/resilience4j)  - Resilience4j 是为 Java8 和函数式编程设计的容错库.  Resilience4j 提供了用于熔断、速率限制、隔板、自动重试、响应缓存和指标测量的模块.
* [Failsafe](https://failsafe.dev/)  - Failsafe 是一个轻量级、*零依赖* 库，用于处理 Java 8+ 中的故障. 简洁的API. 与使用自己的调度程序进行异步执行的库集成，例如 Akka 或 Vert.x. [Vert.x example](https://github.com/failsafe-lib/failsafe/blob/master/examples/src/main/java/dev/failsafe/examples/VertxExample.java)
* [Autonomous Services](https://github.com/mikand13/autonomous-services)  - 用于创建自主服务的工具包. 一种利用 vert.x 和 nannoq-tools 提供基于事件的反应式架构的架构，无需集中式组件，既不用于通信也不用于数据，从而在理论上提供跨架构的线性可扩展性.
* [Apache ServiceComb Java Chassis](https://github.com/apache/servicecomb-java-chassis) - ServiceComb Java Chassis 是一个用于Java微服务快速开发的软件开发工具包（SDK），提供服务注册、服务发现、动态路由和服务管理等功能.

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - 垂直 x 3 [Elasticsearch](https://www.elastic.co/) 事件总线代理服务.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - 带有事件总线代理的 Vert.x 3 Solr 服务.

## Template Engines

* [KorTE Template Engine](https://github.com/korlibs/korte) - 类似于 Twig/Django/Liquid 的 Kotlin 模板引擎，支持调用 Kotlin 挂起方法.

## Service Factory

* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) - Vert.x Node.js 服务工厂.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) - Vert.x 与 [Eclipse SISU](https://www.eclipse.org/sisu/) DI 容器提供 `vertx-service-factory` 和 `vertx-maven-service-factory` 的替代品.

## Config

* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - A [config store](http://vertx.io/docs/vertx-config/java/) 从中检索配置值的实现 [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从 HOCON 配置部署 Verticles.

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - 用于 Guice 依赖注入的 Vert.x verticle 工厂.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - 用于 HK2 依赖注入的 Vert.x verticle 工厂.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - 用于 Spring DI 注入的 Vert.x verticle 工厂.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) - 将 Vert.x 对象作为 bean 注入到您的 Spring 应用程序中.
* [QBit](https://github.com/advantageous/qbit)  - QBit 与 Spring DI 和 Spring Boot（当然还有 Vert.x）一起工作. 允许您在同一应用程序中使用 QBit、Vert.x、Spring DI 和 Spring Boot.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) - Vert.x 与 [Eclipse SISU](https://www.eclipse.org/sisu/) 的容器.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) - 使用 Spring 获取和配置 Verticle 的 Vert.x Verticle Factory.
* [Glue](https://github.com/vinscom/glue)  - 基于 Java 和 Vert.x 的应用程序的经过验证和自以为是的编程和配置模型. 受 ATG Nucleus 启发，使用简单的属性文件提供强大的层基础配置管理.

## Testing

* [Vert.x WireMongo](https://github.com/noenv/vertx-wiremongo) - 用于 Vert.x 的轻量级 MongoDB 模拟

## Development Tools

* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) - 允许在 Vert.x 项目中进行远程健康检查.
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) - 用于热部署 Maven Vert.x 项目的 Maven 插件.
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) - 用于不同语言和构建工具的模板驱动的 Vert.x 项目生成器.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet)  - Vert.x 的 Visual Studio Code（多语言）插件. 也可从 [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - 用于 Vert.x 应用程序的基于浏览器的项目启动器和项目模板.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) - 用于 Vert.x 应用程序的简单 livereload 服务器.
* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI 生成器允许在给定 OpenAPI 规范（v2、v3）的情况下自动生成 API 客户端库（SDK 生成）、服务器存根、文档和配置.

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) - 从 Vert.x 生成子进程.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) - 用于 Vert.x 的高度可扩展的 redis-persistent 排队系统.
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) - 一个 OpenStack Swift 兼容的分布式对象存储服务器，可以使用 Vert.x 实现的最少资源来服务和安全地存储数十亿个大小文件.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - 从 HOCON 配置部署 Verticles.
* [GDH](https://github.com/maxamel/GDH) - 建立在 Vert.x 之上的通用 Diffie-Hellman 密钥交换 Java 库.
* [vertx-values](https://github.com/imrafaelmerino/vertx-values) - 从发送不可变和持久的 JSON [json-values](https://github.com/imrafaelmerino/json-values) 穿过事件总线.

## Distribution


## Examples

* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - 使用 Vert.x、Gradle、MongoDB、Redis、Handlebars 模板、AngularJS、事件总线和 SockJS 构建的 RSS 聚合器示例.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - 如何使用示例 [service-proxy](https://github.com/vert-x3/vertx-service-proxy) 与摇篮.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) - 带有 wiki 描述的分步示例展示了如何使用事件总线和服务代理连接 Vert.x 和 Node.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx)  - Todo MVC 后端的纯 Java 8 实现. 使用 Vert.x LocalMap 进行存储.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) - Todo MVC 后端的 Kotlin 实现.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) - Todo MVC 后端的 Scala 实现.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) - 使用 Vert.x + Groovy + 一些语法糖 + DSL 路由设施的 Todo MVC 后端实现.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) - Java 8 入门应用程序，带有将 Vert.x 与 Gradle 构建系统、配置文件配置和 SLF4J 结合使用的示例.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) - 关于如何使用 Gentics Mesh 和 handlebars 构建基于模板的 Web 服务器的示例.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) - 一个简单的演示，展示了 HTTP/2 如何在涉及巨大延迟时显着改善用户体验.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) - 关于如何使用 RxJava 构建 Vert.x 应用程序的示例应用程序.
* [Crabzilla](https://github.com/crabzilla/crabzilla)  - 另一个事件溯源实验. 探索 Vert.x 以开发事件源/CQRS 应用程序的项目.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) - 使用 Vert.x 堆栈和 PostgreSQL 构建整体 CRUD RESTful Web 服务的初学者.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) - 用于部署到的 Vert.x 示例 [Cloud Foundry](https://www.cloudfoundry.org/) 服务提供者.
* [Knative](https://github.com/knative/docs/tree/main/code-samples/community/serving/helloworld-vertx) - 关于如何使用的示例应用程序 [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) 和 [Knative](https://github.com/knative).
* [Starter Single Verticle API](https://github.com/jgarciasm/ssv-api) - REST API Starter 和项目模板准备好部署大量管道代码、示例和文档，以快速开发 API，几乎不了解 vert.x，也不会浪费任何时间.
* [AI model output API based on PMML with Vert.x](https://github.com/immusen/vertx-pmml)  - 基于 Vert.x 的高性能 PMML 评估器 API. 支持通过 JSON 对多个 PMML 模型进行动态路由配置.

## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) -（无缝）部署到基于 AWS 的 Vert.x 应用程序集群.

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) - 在 Vert.x 事件总线上工作的时间调度程序允许使用 *cron-style* 和 *interval* 计时器进行调度.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron)  - 使用 cron 规范安排事件. 有事件总线和 Observable 版本.
* [Vert.x CronUtils](https://github.com/NoEnv/vertx-cronutils)  - vertx 调度程序的 cron-utils 的抽象. 支持 Unix、Cron4j 和 Quartz 风格的表达式.
* [Vert.x Scheduler](https://github.com/zero88/vertx-scheduler) - 基于普通 Vert.x 核心的轻量级可插拔调度程序，没有任何外部库，用于使用 *cron-style* 和 *interval* 计时器进行调度，并在同步和异步任务上有详细的 *monitor*.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config)  - 允许在标准 JSON 配置和（类型安全的）配置 Java bean 之间进行映射. 还允许通过 JSR 303 验证配置 bean.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) - 将 caolan/async nodejs 模块移植到 Vert.x 框架，为常见的异步模式提供帮助方法.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt)  - 基于原始 bazaarvoice JOLT 项目的 JSON 到 JSON 转换工具. 有助于将不同的 json 结构转换为预期的 json 格式.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) - 旨在部署 Verticle 及其相关 Verticle 的 Vert.x Verticle.
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader)  - 用于 Vert.x 的 Facebook Dataloader 的 Java 端口. 数据层的高效批处理和缓存.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) - Vert.x 实用方法的集合.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) - 只是一个简单的处理程序，用于在 Vert.x Web 中生成访问日志.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) - 路由处理程序和 Vert.x 兼容接口，用于处理 Vert.x 和 Vert.x Web 中的 GraphQL 查询.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) - Nannoq-Tools 是一个利用 Vert.x 构建健壮、可扩展和分布式应用程序的工具包，包括用于身份验证、集群管理、Firebase 云消息传递、DynamoDB、完全通用查询、REST 等的模块.
* [Contextual logging](https://github.com/reactiverse/reactiverse-contextual-logging) - 适用于 Vert.x 事件循环模型的映射诊断上下文 (MDC).
* [Vert.x JsonPath](https://github.com/NoEnv/vertx-jsonpath) - JsonPath 的一个非常基本的实现，使用 Vert.x 的 JsonObject 和 JsonArray，模仿它们的 getX、containsKey、put 和 remove 方法.

## Presentations

* [Vert.x Youtube channel](https://www.youtube.com/channel/UCGN6L3tRhs92Uer3c6VxOSA)

## Community

* [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - 讨论与*使用* Vert.x 相关的所有用户问题.
* [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) - Vert.x 核心*开发人员*和*贡献者*的群组.
* [Discord Server](https://discord.gg/KzEMwP2) - 讨论任何与 Vert.x 相关的话题.
* [Issues](https://github.com/vert-x3/issues/issues) - Vert.x 核心问题跟踪器.
* [Wiki](https://github.com/vert-x3/wiki/wiki) - 包含有关 Vert.x 的有用信息.
* [Blog](http://vertx.io/blog/) - 包含许多教程和其他信息的官方 Vert.x 博客.

## Articles

* [Going reactive with Eclipse Vert.x and RX Java](https://blogs.oracle.com/javamagazine/going-reactive-with-eclipse-vertx-and-rxjava)
* [First Steps With Vert.x and Infinispan - Part 2: PUSH API](https://dzone.com/articles/first-steps-with-vertx-and-infinispan-push-api-par)
* [First Steps With Vert.x and Infinispan - Part 1: REST API](https://dzone.com/articles/first-steps-with-vertx-and-infinispan-rest-api)
* [Location Transparency With Vert.x](https://dzone.com/articles/location-transparency-with-vertx)
* [Reactive Microservices and Service Discovery with Vert.x](https://dzone.com/articles/reactive-microservices-and-service-discovery-with)
* [https://dzone.com/articles/vertx-330-development-automation](https://dzone.com/articles/vertx-330-development-automation)
* [Vert.x 3.3.0 Features Enhanced Networking Microservices, Testing and More](https://www.infoq.com/news/2016/06/Vert.x-3.3.0-release-features)
* [Launching Vert.x Dynamically](https://dzone.com/articles/vertx-launcher)
* [Secure Your Vertx 3 App With Pac4j](https://dzone.com/articles/secure-your-vertx)
* [Interview with Tim Fox About Vert.x 3, the Original Reactive, Microservice Toolkit for the JVM](http://www.infoq.com/articles/vertx-3-tim-fox)

## Tutorials

* [Introduction to Vert.x](https://vertx.io/get-started/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) - 一个纯 Java 前端工具包，具有描述性流畅的模型视图、POJO 流量、虚拟 DOM 上的 JUnit 测试或真实 DOM 上的混合语言等等.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/vert-x3/vertx-awesome/blob/master/CONTRIBUTING.md) 第一的.
