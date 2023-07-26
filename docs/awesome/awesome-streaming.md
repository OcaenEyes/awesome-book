<div class="github-widget" data-repo="manuzhang/awesome-streaming"></div>
## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://github.com/manuzhang/awesome-streaming/workflows/build/badge.svg)](https://github.com/manuzhang/awesome-streaming/actions)

精选的精彩清单 [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 框架、应用程序、阅读材料和其他资源. 灵感来自 [other awesome projects](https://github.com/sindresorhus/awesome). 

## Website

[https://manuzhang.github.io/awesome-streaming/](https://manuzhang.github.io/awesome-streaming/) 是一个更加动态的网站，您可以在这里找到精彩项目的**更新**.



### Streaming Engine

- [Apache Apex](https://github.com/apache/apex-core) [Java] - 大数据流和批处理的统一平台.
- [Apache Ballista](https://github.com/apache/arrow-ballista) [Rust] - 由 Apache Arrow 支持的分布式计算平台.
- [Apache Flink](https://github.com/apache/flink) [Java] - 用于高吞吐量、低延迟数据流处理的系统，支持状态计算、数据驱动的窗口语义和迭代流处理.
- [Apache Heron (incubating)](https://github.com/apache/incubator-heron) [Java] - Twitter 的实时、分布式、容错流处理引擎.
- [Apache Samza](https://github.com/apache/samza) [Scala/Java] - 基于 Kafka（消息传递、存储）和 YARN（容错、处理器隔离、安全性和资源管理）构建的分布式流处理框架.
- [Apache Spark Streaming](https://github.com/apache/spark) [Scala] - 可以轻松构建可扩展的容错流应用程序.
- [Apache Storm](https://github.com/apache/storm)  [Clojure/Java] - 分布式实时计算系统.  Storm之于流处理就像Hadoop之于批处理. 
- [AthenaX](https://github.com/uber/AthenaX) [Java] - 生产中使用的 Uber 流分析框架
- [Bytewax](https://github.com/bytewax/bytewax) [Python] - 数据并行、分布式、有状态的流处理框架.
- [Faust](https://github.com/robinhood/faust) [Python] - 流处理库，将 Kafka Streams 的思想移植到 Python
- [Gearpump](https://github.com/gearpump/gearpump) [Scala] - 基于 Akka 构建的轻量级实时分布式流引擎.
- [Hazelcast Jet](https://github.com/hazelcast/hazelcast-jet) [Java] - 通用分布式数据处理引擎，构建在 Hazelcast 之上.
- [hailstorm](https://github.com/hailstorm-hs/hailstorm) [Haskell] - 基于 Storm 的具有一次性语义的分布式流处理.
- [Maki Nage](https://github.com/maki-nage/makinage) [Python] - 面向数据科学家的流处理框架，基于 Kafka 和 ReactiveX.
- [mantis](https://github.com/Netflix/mantis) [Java] - Netflix构建实时流处理应用生态系统的平台
- [mupd8(muppet)](https://github.com/walmartlabs/mupd8) [Scala/Java] - 用于处理快速/流数据的 mapReduce 风格框架.
- [Onyx](https://github.com/onyx-platform/onyx) [Clojure] - 分布式、无主、高性能、容错数据处理.
- [s4](https://github.com/apache/incubator-s4) [Java] - 通用、分布式、可扩展、容错、可插拔平台，允许程序员轻松开发用于处理连续无界数据流的应用程序.
- [SABER](https://github.com/lsds/Saber) [Java/C] - 基于窗口的混合 CPU/GPU 流处理引擎.
- [Scramjet Cloud Platform](https://github.com/scramjetorg/transform-hub) [Python/JavaScript/Node.js] - 用于运行用 Python、JavaScript 或 TypeScript 编写的多个数据处理应用程序（序列）的数据处理引擎 
- [SPQR](https://github.com/ottogroup/SPQR) [Java] - 通过管道处理大量数据流的动态框架.
- [tigon](https://github.com/caskdata/tigon) [C++/Java] - 基于 Hadoop 和 HBase 构建的高吞吐量实时流处理框架.
- [Teknek](https://github.com/edwardcapriolo/teknek-core) [Java] - 使用交互式原型 shell SOL（流操作语言）进行简单优雅的流处理
Mesos，专为需要灵活性和控制的高性能数据处理作业而设计.
- [Trill](https://github.com/Microsoft/trill) [.NET/C#] - Trill is a high-performance one-pass in-memory streaming analytics engine from Microsoft Research.
- [Wallaroo](https://github.com/WallarooLabs/wallaroo)  [Python] - 一个快速的流处理框架.  Wallaroo 可以轻松地对数据做出实时反应. 通过消除基础设施的复杂性，从原型到生产变得前所未有的简单.
- [LightSaber](https://github.com/lsds/LightSaber)  [C++] - 基于多核窗口的流处理引擎.  LightSaber 使用代码生成来实现高效的窗口聚合.
- [HStreamDB](https://github.com/hstreamdb/hstream) [Haskell] - 为物联网数据存储和实时处理而构建的流数据库.
- [Kuiper](https://github.com/emqx/kuiper) [Golang] - 由 Golang 实现的边缘轻量级物联网数据分析/流媒体软件，它可以在各种资源受限的边缘设备上运行.
- [WindFlow](https://paragroup.github.io/WindFlow) [C++] - 用于多核和 GPU 的 C++17 数据流处理并行库

### Streaming Library

- [Apache Kafka Streams](https://github.com/apache/kafka) [Java] - Apache Kafka 中包含的轻量级流处理库（自 0.10 版本起）.
- [Streamiz](https://github.com/LGouellec/kafka-streams-dotnet) [C#] - a .Net Stream Processing Library for Apache Kafka
- [Akka Streams](https://github.com/akka/akka) [Scala] - Akka Actors 上的流处理库.
- [Daggy](https://github.com/synacker/daggy) [C++] - 实时流聚合和捕获. 
- [Benthos](https://github.com/Jeffail/benthos) [Go] - Benthos 是一种高性能且有弹性的消息流服务，能够连接各种源和接收器并对有效负载执行任意操作、转换和过滤
- [FS2(prev. 'Scalaz-Stream')](https://github.com/functional-streams-for-scala/fs2) [Scala] - Scala 的组合式流 I/O 库.
- [monix](https://github.com/monix/monix) [Scala] - 用于编写异步和基于事件的程序的高性能 Scala / Scala.js 库.
- [Quix Streams](https://github.com/quixio/quix-streams) [Python] - 最初为迈凯伦一级方程式赛车队设计的流媒体库，可以使用 Apache Kafka 作为消息代理来处理大量时间序列数据，精度高达纳秒.
- [Scramjet Node.js](https://github.com/scramjetorg/framework-js) - [Node.js] 在 Node.js 对象流之上编写的功能反应式流编程框架 + [the legacy Scramjet.js version](https://github.com/scramjetorg/scramjet)
- [Scramjet Python](https://github.com/scramjetorg/framework-python) - [Python] 功能反应式流编程框架从头开始编写，可在对象、字符串和缓冲区流上运行.
- [Scramjet C++](https://github.com/scramjetorg/framework-cpp) - [C++] 在 Node.js 对象流之上编写的函数反应式流编程框架.
- [Streamline](https://github.com/hortonworks/streamline)  [Java] - Hortonworks 的流分析框架，设计为现有流解决方案（如 Storm）的包装器. 旨在允许用户拖放流组件以专注于业务逻辑.
- [StreamAlert](https://github.com/airbnb/streamalert) [Python] - Airbnb 的实时数据分析和警报.
- [Swave](https://github.com/sirthias/swave) [Scala] - Scala 的轻量级反应流基础设施工具包.
- [Streamz](https://github.com/python-streamz/streamz)  [Python] - 一个轻量级库，用于构建管道来管理连续的数据流； 支持涉及分支、连接、流控制、反馈、背压等的复杂管道.
- [Stream Ops](https://github.com/nanosai/stream-ops-java) [Java] - 用于 Java 的完全嵌入式数据流引擎和流处理 API.
- [Substation](https://github.com/brexhq/substation) [Go] - Substation 是一个用 Go 编写的云原生数据管道和转换工具包.
- [Tributary](https://github.com/timkpaine/tributary)  [Python] - 用于构建数据流图的 python 库. 支持使用模拟复杂事件处理器的 python 生成器构建的同步、反应式数据流，以及惰性评估的非循环图和函数柯里化流.
- [YoMo](https://github.com/yomorun/yomo)  [Go] - 用于构建低延迟地理分布式系统的开源流无服务器框架.  YoMo 建于顶部 [QUIC Transport Protocol](https://en.wikipedia.org/wiki/QUIC) 和函数式反应式编程接口. 
- [Mediapipe](https://github.com/google/mediapipe) - 适用于直播和流媒体的跨平台、可定制的机器学习解决方案.

### Streaming Application

- [javactrl-kafka](https://github.com/javactrl/javactrl-kafka) [Java] - 作为 Java 代码的工作流状态流处理应用程序（微服务编排、业务流程自动化等）.
- [straw](https://github.com/rwalk/straw) [Python/Java] - A platform for real-time streaming search.
- [storm-crawler](https://github.com/DigitalPebble/storm-crawler) [Java] - 基于 Apache Storm 的网络爬虫 SDK.
- [Zilla](https://github.com/aklivity/zilla) [Java] - 为事件驱动架构和流媒体构建的跨平台 API 网关，支持 HTTP、SSE、gRPC、MQTT 和本机 Kafka 协议等标准协议.

### IoT

- [sensorbee](https://github.com/sensorbee/sensorbee) [Go] - 用于物联网的轻量级流处理引擎.
- [Apache Edgent](https://github.com/apache/incubator-edgent) [Java] - 一种编程模型和运行时，支持在网关和边缘设备上进行连续流分析，这些设备可以与集中式系统配合使用，在整个物联网生态系统中提供高效、及时的分析：从中心到边缘，由 IBM 开源.
- [Apache StreamPipes](https://github.com/apache/incubator-streampipes) [Java] - 一个自助式（工业）物联网工具箱，使非技术用户能够连接、分析和探索物联网数据流.

### DSL

- [Apache Beam](https://github.com/apache/beam) [Java、Python、SQL、Scala、Go] - 统一模型和一组特定于语言的 SDK，用于定义和执行数据处理工作流以及数据摄取和集成流，支持企业集成模式 (EIP) 和领域特定语言 (DSL) ），由 Google 开源.
- [coast](https://github.com/bkirwi/coast) [Scala] - 一种在 Samza 之上构建 DAG 并提供一次性语义的 DSL.
- [Esper](https://github.com/espertechinc/esper) [Java] - 用于复杂事件处理（CEP）和事件系列分析的组件.
- [Streamparse](https://github.com/Parsely/streamparse) [Python] - 让您可以通过 Apache Storm 针对实时数据流运行 Python 代码.
- [summingbird](https://github.com/twitter/summingbird) [Scala] - 允许您编写类似于本机 Scala 或 Java 集合转换的 MapReduce 程序的库，并在许多著名的分布式 MapReduce 平台（包括 Storm 和 Scalding）上执行它们.

### Data Pipeline

- [Apache Kafka](https://github.com/apache/kafka) [Scala/Java] - 分布式、分区、复制的提交日志服务，它提供消息系统的功能，但具有独特的设计.
- [Apache Pulsar](https://github.com/apache/incubator-pulsar) [Java] - 分布式发布-订阅消息传递平台，具有非常灵活的消息传递模型和直观的客户端 API.
- [Apache RocketMQ](https://github.com/apache/rocketmq) [Java] - 分布式消息和流媒体平台，具有低延迟、高性能和可靠性、万亿级容量和灵活的可扩展性.
- [brooklin](https://github.com/linkedin/Brooklin/) [Java] - 一种分布式系统，用于在各种异构源和目标系统之间流式传输数据，具有高可靠性和大规模吞吐量，来自 Linkedin（已替换数据总线）.
- [camus](https://github.com/linkedin/camus) [Java] - Linkedin 的 Kafka -&gt; HDFS 管道.
- [databus](https://github.com/linkedin/databus) [Java] - Linkedin 的源无关分布式变更数据捕获系统.
- [flume](https://github.com/apache/flume) [Java] - 分布式、可靠且可用的服务，用于高效收集、聚合和移动大量日志数据.
- [fluvio](https://github.com/infinyon/fluvio) [Rust/WASM] - 具有在线计算功能的实时可编程数据流平台.
- [Gazette](https://github.com/gazette/core) [golang] - 基于云存储构建的分布式流基础设施，可以轻松混合和匹配批处理和流范例.
- [LogDevice](https://logdevice.io/) [C++] - Facebook 的高性能分布式系统，用于使用日志结构流式传输和存储顺序数据.
- [metaq](https://github.com/killme2008/Metamorphosis) [Java] - 淘宝高可用、高性能的分布式消息系统
- [NATS streaming](https://github.com/nats-io/nats-streaming-server) [Go] - 快速的磁盘支持的消息传递解决方案
- [nsq](https://github.com/nsqio/nsq) [Go] - 实时分布式消息传递平台，旨在大规模运行，每天处理数十亿条消息.
- [Redpanda](https://github.com/redpanda-data/redpanda) [C++] - Redpanda 与 Kafka 兼容，无 ZooKeeper，无 JVM，并且源代码可用.
- [RudderStack](https://github.com/rudderlabs/rudder-server) [Go] - 一个开源客户数据基础设施（segment、marticle 替代方案）.
- [suro](https://github.com/Netflix/suro) [Java] - 用于收集、聚合和分派大量应用程序事件（包括日志数据）的数据管道服务.
- [StreamSets Data Collector](https://github.com/streamsets/datacollector-oss) [Java] - 连续大数据摄取基础设施，可读取和写入大量端点，包括 S3、JDBC、Hadoop、Kafka、Cassandra 等.

### Online Machine Learning 

- [Apache Samoa](https://github.com/apache/incubator-samoa) [Java] - 分布式流式机器学习 (ML) 框架，包含分布式流式 ML 算法的编程抽象.
- [DataSketches](https://github.com/DataSketches/sketches-core) [Java] - 来自 Yahoo! 的草图库.
- [River](https://github.com/online-ml/river) [Python] - 在线机器学习库.
- [streamDM](https://github.com/huawei-noah/streamDM) [Scala] - 使用华为的 Spark Streaming 挖掘大数据流.
- [StreamingBandit](https://github.com/Nth-iteration-labs/streamingbandit) [Python] - 提供网络服务器来快速设置和评估上下文多臂老虎机 (cMAB) 问题的可能解决方案.
- [StormCV](https://github.com/sensorstorm/StormCV) [Java] - 通过添加计算机视觉 (CV) 特定操作和数据模型，支持使用 Apache Storm 进行视频处理.
- [trident-ml](https://github.com/pmerienne/trident-ml) [Java] - 基于Trident的实时在线机器学习库.
- [yurita](https://github.com/paypal/yurita) [Scala] - 基于 Paypal 的 Spark Structured Streaming 构建的异常检测框架.

### Streaming SQL

- [pipelinedb](https://github.com/pipelinedb/pipelinedb) [C] - 一种开源关系数据库，可在流上连续运行 SQL 查询，并将结果增量存储在表中.
- [squall](https://github.com/epfldata/squall) [Java] - Squall 在 Storm 之上执行 SQL 查询以进行在线处理.
- [StreamCQL](https://github.com/Zhiqiang-He/StreamCQL) [Java] - 实时计算系统上的连续查询语言.
- [ksqlDB](https://github.com/confluentinc/ksql) [Java] - 云原生、源码可用 [database](https://ksqldb.io/) 专为流处理应用程序而构建
- [Materialize](https://materialize.com) [Rust] - 一个可用源的流式 SQL 引擎，用于维护来自消息代理和数据库的数据的物化视图.
- [Siddhi](https://github.com/siddhi-io/siddhi) [Java] - 云原生流式处理和复杂事件处理引擎，它理解流式 SQL 查询，以便从不同的数据源捕获事件、处理它们、检测复杂条件并将输出实时发布到各种端点.

### Benchmark

- [storm-perf-test](https://github.com/yahoo/storm-perf-test) [Java] - 一个简单的风暴性能/压力测试.
- [streaming-benchmarks](https://github.com/yahoo/streaming-benchmarks) [Java] - 低延迟（流）解决方案的基准，包括 Apache Storm、Apache Spark、Apache Flink 等.
- [flotilla](https://github.com/tylertreat/Flotilla) [Go] - 用于扩大基准测试的自动消息队列编排.

### Toolkit

- [akka](https://github.com/akka/akka) [Scala] - toolkit and runtime for building highly concurrent, distributed, and resilient message-driven application on the JVM.
- [pulsar](https://github.com/quantmind/pulsar/) [Python] - Python 的基于 Actor 的事件驱动并发框架.
- [aeron](https://github.com/real-logic/Aeron) [Java/C++] - 高效可靠的单播和多播消息传输.
- [StreamFlow](https://github.com/lmco/streamflow) [Java] - 流处理工具，旨在帮助构建和监控处理工作流程.
- [samza-luwak](https://github.com/romseygeek/samza-luwak) [Java] - 使用 Luwak（一个基于 Lucene 构建的存储查询引擎）来实现流上的全文搜索.
- [Turbine](https://github.com/Netflix/Turbine) [Java] - 用于将服务器发送事件 (SSE) JSON 数据流聚合到单个流中的工具.
- [Nussknacker](https://github.com/TouK/nussknacker) [Scala] - 用于定义和运行实时决策算法的可视化工具.

### Closed Source

- [Amazon Kinesis Streams](https://aws.amazon.com/kinesis/) [Java] - AWS 提供的实时、完全托管且可扩展的数据流引擎. 
- [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) [.NET] Microsoft Azure 提供的大规模可扩展、完全托管、实时数据流引擎.
- [Cloud Dataflow](https://cloud.google.com/dataflow/) [Java、Python、SQL、Scala] - Google 的托管流和批数据处理引擎. 支持运行Beam管道.
- [concord](https://www.slideshare.net/concord-io/may-2016-data-by-the-bay-concord-simple-flexible-stream-processing-on-apache-mesos) [C++] - 在 Apache 之上用 C++ 构建的分布式流处理框架.
- [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/)  [Python/Java/Scala] - 分布式处理和实时分析平台. 提供开箱即用的高级分析工具包，例如地理空间、时间序列等.
- [jubatus](http://jubat.us/en/) [C++] - 分布式处理框架和流式机器学习库.
- [millwheel](http://research.google.com/pubs/pub41378.html) - 用于构建 Google 广泛使用的低延迟数据处理应用程序的框架.
- [NVIDIA Deep Stream](https://developer.nvidia.com/deepstream-sdk) [Python/C/C++] - 实时图像、视频和音频处理的平台，最好在边缘设备或云上使用.

### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) 作者：泰勒·阿基道. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)
4. [Grokking Streaming Systems](https://www.manning.com/books/grokking-streaming-systems) 作者：乔什·费舍尔和王宁
5. [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/) 作者：Reuven Lax、Slava Chernyak 和 Tyler Akidau
6. [Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow) 作者：Bas P. Harenslak 和 Julian Rutger de Ruiter

## License

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)

已获得许可 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
