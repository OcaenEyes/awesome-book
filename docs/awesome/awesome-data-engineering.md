<div class="github-widget" data-repo="igorbarinov/awesome-data-engineering"></div>
很棒的数据工程
==========================

为软件开发人员精心挑选的数据工程工具列表 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

内容清单


## Databases
- 关系型
	* [RQLite](https://github.com/rqlite/rqlite) 使用 Raft 共识协议复制 SQLite
	* [MySQL](https://www.mysql.com/) 世界上最受欢迎的开源数据库.
		* [TiDB](https://github.com/pingcap/tidb) TiDB 是兼容 MySQL 协议的分布式 NewSQL 数据库
		* [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) Percona XtraBackup 是一款免费、开源、完整的在线备份解决方案，适用于所有版本的 Percona Server、MySQL® 和 MariaDB®
		* [mysql_utils](https://github.com/pinterest/mysql_utils) Pinterest MySQL 管理工具
	* [MariaDB](https://mariadb.org/) MySQL 的增强型直接替代品.
	* [PostgreSQL](https://www.postgresql.org/) 世界上最先进的开源数据库.
	* [Amazon RDS](https://aws.amazon.com/rds/) Amazon RDS 让您可以轻松地在云中设置、操作和扩展关系数据库. 
	* [Crate.IO](https://crate.io/) 具有 NOSQL 功能的可扩展 SQL 数据库.
- 核心价值
	* [Redis](https://redis.io/) 一个开源、BSD 许可的高级键值缓存和存储.
	* [Riak](http://docs.basho.com/riak/kv/) 分布式数据库，旨在通过将数据分布在多个服务器上来提供最大的数据可用性.
	* [AWS DynamoDB](https://aws.amazon.com/dynamodb/) 快速灵活的 NoSQL 数据库服务，适用于任何规模都需要一致的个位数毫秒延迟的所有应用程序.
	* [HyperDex](https://github.com/rescrv/HyperDex)  HyperDex 是一个可扩展、可搜索的键值存储. 已弃用.
	* [SSDB](http://ssdb.io) 支持多种数据结构的高性能NoSQL数据库，Redis的替代品
	* [Kyoto Tycoon](https://github.com/alticelabs/kyoto) 京都大亨 (Kyoto Tycoon) 是一个基于京都橱柜键值数据库的轻量级网络服务器，专为高性能和并发性而构建
	* [IonDB](https://github.com/iondbproject/iondb) 用于微控制器和物联网应用的键值存储
- 柱子
	* [Cassandra](https://cassandra.apache.org/) 当您需要可扩展性和高可用性而不影响性能时，这是正确的选择.
		* [Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) 这个简单的表单允许您尝试 Apache Cassandra 集群的不同值，并查看对您的应用程序的影响.
		* [CCM](https://github.com/pcmanus/ccm) 用于在本地主机上轻松创建和销毁 Apache Cassandra 集群的脚本
		* [ScyllaDB](https://github.com/scylladb/scylla) 使用seastar框架的NoSQL数据存储，与Apache Cassandra兼容 https://www.scylladb.com/
	* [HBase](https://hbase.apache.org/) Hadoop 数据库，一种分布式、可扩展的大数据存储.
	* [AWS Redshift](https://aws.amazon.com/redshift/) 快速、完全托管的 PB 级数据仓库，使使用现有商业智能工具分析所有数据变得简单且经济高效.
	* [FiloDB](https://github.com/filodb/FiloDB) 分散式. 柱状. 版本化. 流媒体.  SQL.
	* [Vertica](https://www.vertica.com) 具有广泛分析 SQL 的分布式 MPP 列式数据库.
	* [ClickHouse](https://clickhouse.tech) 用于 OLAP 的分布式列式 DBMS.  SQL.
- 文档
	* [MongoDB](https://www.mongodb.com) 一个开源文档数据库，旨在简化开发和扩展. 
		* [Percona Server for MongoDB](https://www.percona.com/software/mongo-database/percona-server-for-mongodb) Percona Server for MongoDB® 是 MongoDB® Community Edition 的免费、增强、完全兼容、开源、直接替代品，包含企业级特性和功能.
		* [MemDB](https://github.com/rain1017/memdb) 分布式事务内存数据库（基于MongoDB）
	* [Elasticsearch](https://www.elastic.co/) 实时搜索和分析数据.
	* [Couchbase](https://www.couchbase.com/) 性能最高的 NoSQL 分布式数据库.
	* [RethinkDB](https://rethinkdb.com/) 实时网络的开源数据库.
	* [RavenDB](https://ravendb.net/) 完全事务性 NoSQL 文档数据库.
- 图表
	* [Neo4j](https://neo4j.com/) 全球领先的图数据库.
	* [OrientDB](https://orientdb.com) 2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license.
	* [ArangoDB](https://www.arangodb.com/) 分布式免费开源数据库，具有灵活的文档、图形和键值数据模型. 
	* [Titan](https://titan.thinkaurelius.com) 一个可扩展的图形数据库，经过优化，可存储和查询包含分布在多机集群中的数千亿个顶点和边的图形.
	* [FlockDB](https://github.com/twitter-archive/flockdb)  Twitter 的分布式容错图形数据库. 已弃用.
- 分散式
	* [DAtomic](https://www.datomic.com) 完全事务性、云就绪、分布式数据库.
	* [Apache Geode](https://geode.apache.org/) 用于横向扩展应用程序的开源分布式内存数据库.
	* [Gaffer ](https://github.com/gchq/Gaffer) 大规模图数据库
- 时间序列
	* [InfluxDB](https://github.com/influxdata/influxdb) 用于指标、事件和实时分析的可扩展数据存储.
	* [OpenTSDB](https://github.com/OpenTSDB/opentsdb) 可扩展的分布式时间序列数据库.
	* [QuestDB](https://questdb.io/) 面向列的关系数据库，专为时间序列和事件数据的实时分析而设计.
	* [kairosdb](https://github.com/kairosdb/kairosdb) 快速可扩展的时间序列数据库.
	* [Heroic](https://github.com/spotify/heroic) Spotify 提供的基于 Cassandra 和 Elasticsearch 的可扩展时间序列数据库
	* [Druid](https://github.com/apache/incubator-druid) 面向列的分布式数据存储，非常适合为交互式应用程序提供支持
	* [Riak-TS](http://basho.com/products/riak-ts/) Riak TS 是唯一专门针对物联网和时间序列数据优化的企业级 NoSQL 时间序列数据库
	* [Akumuli](https://github.com/akumuli/Akumuli)  Akumuli 是一个数字时间序列数据库. 它可用于实时捕获、存储和处理时间序列数据.  “akumuli”这个词可以从世界语翻译为“积累”.
	* [Rhombus](https://github.com/Pardot/Rhombus) Cassandra 的时间序列对象存储，可处理构建宽行索引的所有复杂性.
	* [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) 快速分布式指标数据库
	* [Blueflood](https://github.com/rackerlabs/blueflood) 旨在摄取和处理时间序列数据的分布式系统
	* [Timely](https://github.com/NationalSecurityAgency/timely) Timely 是一个时间序列数据库应用程序，提供基于 Accumulo 和 Grafana 的时间序列数据的安全访问.
- 其他
	* [Tarantool](https://github.com/tarantool/tarantool/) Tarantool 是一个内存数据库和应用程序服务器.
	* [GreenPlum](https://github.com/greenplum-db/gpdb)  Greenplum 数据库 (GPDB) 是一个先进的、功能齐全的开源数据仓库. 它提供对 PB 级数据量的强大而快速的分析.
	* [cayley](https://github.com/cayleygraph/cayley) 一个开源图形数据库. 谷歌.
	* [Snappydata](https://github.com/SnappyDataInc/snappydata) SnappyData：基于 Apache Spark 构建的 OLTP + OLAP 数据库
	* [TimescaleDB](https://www.timescale.com/)：TimescaleDB 作为 PostgreSQL 之上的扩展而构建，是一个时间序列 SQL 数据库，可在经过验证的存储引擎上提供快速分析、可扩展性以及自动化数据管理.

## Data Ingestion
* [Kafka](https://kafka.apache.org/) 发布-订阅消息传递被重新考虑为分布式提交日志.
	* [BottledWater](https://github.com/confluentinc/bottledwater-pg) 将数据捕获从 PostgreSQL 更改为 Kafka. 已弃用.
	* [kafkat](https://github.com/airbnb/kafkat) 简化 Kafka 代理的命令行管理
	* [kafkacat](https://github.com/edenhill/kafkacat) 通用命令行非 JVM Apache Kafka 生产者和消费者
	* [pg-kafka](https://github.com/xstevens/pg_kafka) 用于向 Apache Kafka 生成消息的 PostgreSQL 扩展
	* [librdkafka](https://github.com/edenhill/librdkafka) Apache Kafka C/C++ 库
	* [kafka-docker](https://github.com/wurstmeister/kafka-docker) Docker 中的卡夫卡
	* [kafka-manager](https://github.com/yahoo/kafka-manager) 管理 Apache Kafka 的工具
	* [kafka-node](https://github.com/SOHU-Co/kafka-node) Apache Kafka 0.8 的 Node.js 客户端
	* [Secor](https://github.com/pinterest/secor) Pinterest 的 Kafka 到 S3 分布式消费者
	* [Kafka-logger](https://github.com/uber/kafka-logger) 来自 uber 的用于 Nodejs 的 Kafka-winston 记录器
* [AWS Kinesis](https://aws.amazon.com/kinesis/) 一种完全托管的基于云的服务，用于对大型分布式数据流进行实时数据处理.
* [RabbitMQ](https://www.rabbitmq.com/) 强大的应用程序消息传递.
* [FluentD](https://www.fluentd.org) 用于统一日志记录层的开源数据收集器.
* [Embulk](https://www.embulk.org) 开源批量数据加载器，可帮助在各种数据库、存储、文件格式和云服务之间传输数据.
* [Apache Sqoop](https://sqoop.apache.org) 一种设计用于在 Apache Hadoop 和结构化数据存储（例如关系数据库）之间高效传输批量数据的工具.
* [Heka](https://github.com/mozilla-services/heka) 数据采集​​和处理变得简单. 已弃用.
* [Gobblin](https://github.com/apache/incubator-gobblin) Linkedin 的 Hadoop 通用数据摄取框架
* [Nakadi](https://nakadi.io) Nakadi 是一个开源事件消息传递平台，它在类似 Kafka 的队列之上提供 REST API.
* [Pravega](http://www.pravega.io) Pravega 为连续且无界的数据提供了一种新的存储抽象——流.
* [Apache Pulsar](https://pulsar.apache.org/) Apache Pulsar 是一个开源分布式发布-订阅消息系统.
* [AWS Data Wranlger](https://github.com/awslabs/aws-data-wrangler) 用于处理 AWS 上数据的实用带.

## File System
* [HDFS](https://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html)
	* [Snakebite](https://github.com/spotify/snakebite) 一个纯Python的HDFS客户端
* [AWS S3](https://aws.amazon.com/s3/)
	* [smart_open](https://github.com/RaRe-Technologies/smart_open) 用于流式传输大文件的实用程序（S3、HDFS、gzip、bz2）
* [Alluxio](https://www.alluxio.org/) Alluxio 是一个以内存为中心的分布式存储系统，能够跨集群框架（例如 Spark 和 MapReduce）以内存速度可靠地共享数据
* [CEPH](https://ceph.com/) Ceph 是一个统一的分布式存储系统，旨在实现卓越的性能、可靠性和可扩展性
* [OrangeFS](https://www.orangefs.org/) Orange文件系统是并行虚拟文件系统的一个分支
* [SnackFS](https://github.com/tuplejump/snackfs-release) SnackFS 是我们基于 Cassandra 构建的小型、轻量级 HDFS 兼容文件系统
* [GlusterFS](https://www.gluster.org/) Gluster 文件系统
* [XtreemFS](http://www.xtreemfs.org/) 满足所有存储需求的容错分布式文件系统
* [SeaweedFS](https://github.com/chrislusf/seaweedfs)  Seaweed-FS 是一个简单且高度可扩展的分布式文件系统. 有两个目标：存储数十亿个文件！ 快速提供文件！  Seaweed-FS 选择仅实现密钥到文件映射，而不是支持完整的 POSIX 文件系统语义. 与“NoSQL”一词类似，您可以将其称为“NoFS”.
* [S3QL](https://github.com/s3ql/s3ql/) S3QL 是一种文件系统，它使用 Google Storage、Amazon S3 或 OpenStack 等存储服务在线存储所有数据.
* [LizardFS](https://lizardfs.com/) LizardFS 软件定义存储是一个分布式、并行、可扩展、容错、地理冗余和高可用的文件系统.

## Serialization format
* [Apache Avro](https://avro.apache.org) Apache Avro™ 是一个数据序列化系统
* [Apache Parquet](https://parquet.apache.org) Apache Parquet 是一种列式存储格式，适用于 Hadoop 生态系统中的任何项目，无论选择何种数据处理框架、数据模型或编程语言.
	* [Snappy](https://github.com/google/snappy) 快速压缩器/解压缩器. 与镶木地板一起使用
	* [PigZ](https://zlib.net/pigz/) 现代 gzip 的并行实现
多处理器、多核机器
* [Apache ORC](https://orc.apache.org/) 适用于 Hadoop 工作负载的最小、最快的列式存储 
* [Apache Thrift](https://thrift.apache.org) Apache Thrift 软件框架，用于可扩展的跨语言服务开发
* [ProtoBuf](https://github.com/protocolbuffers/protobuf) Protocol Buffers - Google 的数据交换格式
* [SequenceFile](https://wiki.apache.org/hadoop/SequenceFile)  SequenceFile 是由二进制键/值对组成的平面文件. 它在 MapReduce 中广泛用作输入/输出格式
* [Kryo](https://github.com/EsotericSoftware/kryo) Kryo 是一个快速高效的 Java 对象图序列化框架


## Stream Processing
* [Apache Beam](https://beam.apache.org/) Apache Beam 是一个统一的编程模型，可实现在许多执行引擎上运行的批处理和流数据处理作业.
* [Spark Streaming](https://spark.apache.org/streaming/) Spark Streaming 可以轻松构建可扩展的容错流应用程序.
* [Apache Flink](https://flink.apache.org/) Apache Flink 是一个流数据流引擎，为数据流上的分布式计算提供数据分发、通信和容错能力.
* [Apache Storm](https://storm.apache.org) Apache Storm 是一个免费开源的分布式实时计算系统
* [Apache Samza](https://samza.apache.org) Apache Samza 是一个分布式流处理框架
* [Apache NiFi](https://nifi.apache.org/) 是一个易于使用、功能强大且可靠的系统，用于处理和分发数据
* [Apache Hudi](https://hudi.apache.org/) Apache Hudi 是一个用于管理实时处理存储的开源框架，最有趣的功能之一是 Upsert
* [VoltDB](https://voltdb.com/) VoltDb 是一个符合 ACID 的 RDBMS，它使用 [shared nothing architecture](https://en.wikipedia.org/wiki/Shared-nothing_architecture).
* [PipelineDB](https://github.com/pipelinedb/pipelinedb) 流式 SQL 数据库
* [Spring Cloud Dataflow](https://cloud.spring.io/spring-cloud-dataflow/) Spring Boot 应用程序之间的流传输和任务执行
* [Bonobo](https://www.bonobo-project.org/) Bonobo 是一个适用于 python 3.5+ 的数据处理工具包
* [Robinhood's Faust](https://github.com/faust-streaming/faust) 永远可扩展的事件处理和内存中持久的 K/V 存储作为具有异步和静态类型的库.
* [HStreamDB](https://github.com/hstreamdb/hstream) 专为物联网数据存储和实时处理而构建的流数据库.
* [Kuiper](https://github.com/emqx/kuiper) 由Golang实现的边缘轻量级物联网数据分析/流媒体软件，可以在各种资源受限的边缘设备上运行.

## Batch Processing
* [Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) Hadoop MapReduce 是一个软件框架，用于轻松编写应用程序，以可靠、容错的方式在商用硬件的大型集群（数千个节点）上并行处理大量数据（多 TB 数据集）
* [Spark](https://spark.apache.org/)
	* [Spark Packages](https://spark-packages.org) Apache Spark 软件包的社区索引
	* [Deep Spark](https://github.com/Stratio/deep-spark) 将 Apache Spark 与不同的数据存储连接. 已弃用.
	* [Spark RDD API Examples](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html) by Zhen He
	* [Livy](https://livy.incubator.apache.org) Livy，REST Spark 服务器
* [AWS EMR](https://aws.amazon.com/emr/) 一种 Web 服务，可以轻松快速且经济高效地处理大量数据.
* [Tez](https://tez.apache.org/) 一个应用程序框架，允许使用复杂的有向无环任务图来处理数据.
* [Bistro](https://github.com/asavinov/bistro) 是一个轻量级引擎，用于通用数据处理，包括批处理和流分析. 它基于一种新颖独特的数据模型，该模型通过“函数”表示数据并通过“列操作”处理数据，而不是像 MapReduce 或 SQL 等传统方法中仅进行设置操作.
- 批量机器学习
	* [H2O](https://www.h2o.ai/) 快速可扩展的机器学习 API，适用于更智能的应用程序.
	* [Mahout](https://mahout.apache.org/) 用于快速创建可扩展的高性能机器学习应用程序的环境.
	* [Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) Spark 的可扩展机器学习库由常见的学习算法和实用程序组成，包括分类、回归、聚类、协同过滤、降维以及底层优化原语.
- 批次图
	* [GraphLab Create](https://turi.com/products/create/docs/) 一个机器学习平台，使数据科学家和应用程序开发人员能够轻松地大规模创建智能应用程序.
	* [Giraph](https://giraph.apache.org/) 专为高可扩展性而构建的迭代图形处理系统. 
	* [Spark GraphX](https://spark.apache.org/graphx/) Apache Spark's API for graphs and graph-parallel computation. 
- 批量SQL
	* [Presto](https://prestodb.github.io/docs/current/index.html) 一种分布式 SQL 查询引擎，旨在查询分布在一个或多个异构数据源上的大型数据集.
	* [Hive](https://hive.apache.org) 数据仓库软件有助于查询和管理分布式存储中的大型数据集. 
		* [Hivemall](https://github.com/apache/incubator-hivemall) 适用于 Hive/Hadoop 的可扩展机器学习库.
		* [PyHive](https://github.com/dropbox/PyHive) Hive 和 Presto 的 Python 接口.
	* [Drill](https://drill.apache.org/) 适用于 Hadoop、NoSQL 和云存储的无架构 SQL 查询引擎.

## Charts and Dashboards
* [Highcharts](https://www.highcharts.com/) 用纯 JavaScript 编写的图表库，提供了一种向网站或 Web 应用程序添加交互式图表的简单方法.
* [ZingChart](https://www.zingchart.com/) 适用于任何数据集的快速 JavaScript 图表.
* [C3.js](https://c3js.org) 基于 D3 的可重用图表库.
* [D3.js](https://d3js.org/) 用于基于数据操作文档的 JavaScript 库.
	* [D3Plus](https://d3plus.org)  D3 更简单，更容易使用. 大多数是预定义的模板，您只需插入数据即可.
* [SmoothieCharts](http://smoothiecharts.org) 用于流数据的 JavaScript 图表库.
* [PyXley](https://github.com/stitchfix/pyxley) 使用 Flask 和 React 构建仪表板的 Python 助手
* [Plotly](https://github.com/plotly/dash) Flask、JS 和 CSS 样板，用于 Python 中基于 Web 的交互式可视化应用程序
* [Apache Superset](https://github.com/apache/incubator-superset) Apache Superset（正在孵化）是一个现代的企业级商业智能 Web 应用程序
* [Redash](https://redash.io/) 让您的公司由数据驱动. 连接到任何数据源，轻松可视化和共享您的数据.
* [Metabase](https://github.com/metabase/metabase) Metabase is the easy, open source way for everyone in your company to ask questions and learn from data.
* [PyQtGraph](http://www.pyqtgraph.org/)  PyQtGraph 是一个基于 PyQt4 / PySide 和 numpy 构建的纯 python 图形和 GUI 库. 它旨在用于数学/科学/工程应用.


## Workflow
* [Luigi](https://github.com/spotify/luigi) Luigi 是一个 Python 模块，可帮助您构建复杂的批处理作业管道.
	* [CronQ](https://github.com/seatgeek/cronq) 一个类似 cron 的应用程序系统. [Used](https://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/) 与路易格. 已弃用.
* [Cascading](https://www.cascading.org/) 基于Java的应用程序开发平台.
* [Airflow](https://github.com/apache/airflow) Airflow 是一个以编程方式编写、调度和监控数据管道的系统.
* [Azkaban](https://azkaban.github.io/)  Azkaban 是 LinkedIn 创建的批处理工作流作业调度程序，用于运行 Hadoop 作业.  Azkaban 通过作业依赖关系解决排序问题，并提供易于使用的 Web 用户界面来维护和跟踪您的工作流程. 
* [Oozie](https://oozie.apache.org/) Oozie 是一个工作流调度系统，用于管理 Apache Hadoop 作业
* [Pinball](https://github.com/pinterest/pinball) 基于 DAG 的工作流管理器. 作业流是在 Python 中以编程方式定义的. 支持作业之间的输出传递.
* [Dagster](https://github.com/dagster-io/dagster) Dagster 是一个用于构建数据应用程序的开源 Python 库.
* [Dataform](https://dataform.co/) 是一个开源框架和基于 Web 的 IDE，用于管理数据集及其依赖项.  SQLX 扩展了现有的 SQL 仓库方言，添加了支持依赖项管理、测试、文档等的功能.
* [Census](https://getcensus.com/) 是一种反向 ETL 工具，可让您将云数据仓库中的数据同步到 Salesforce、Marketo、HubSpot、Zendesk 等 SaaS 应用程序.无需任何工程支持，只需 SQL.
* [dbt](https://getdbt.com/) 是一个命令行工具，使数据分析师和工程师能够更有效地转换仓库中的数据.
* [RudderStack](https://github.com/rudderlabs/rudder-server) 是一个仓库优先的客户数据平台，使您能够从每个应用程序、网站和 SaaS 平台收集数据，然后在您的仓库和业务工具中激活它

## Data Lake Management
* [lakeFS](https://github.com/treeverse/lakeFS) LakeFS 是一个开源平台，可为基于对象存储的数据湖提供弹性和可管理性.

## ELK Elastic Logstash Kibana
* [docker-logstash](https://github.com/pblittle/docker-logstash) 一个高度可配置的logstash (1.4.4) docker 镜像，运行Elasticsearch (1.7.0) 和Kibana (3.1.2).
* [elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) Elasticsearch 的 JDBC 导入器
* [ZomboDB](https://github.com/zombodb/zombodb) Postgres 扩展允许创建由 Elasticsearch 支持的索引

## Docker
* [Gockerize](https://github.com/redbooth/gockerize) 将 golang 服务打包到最小的 docker 容器中
* [Flocker](https://github.com/ClusterHQ/flocker) 轻松管理 Docker 容器及其数据
* [Rancher](https://rancher.com/rancher-os/) RancherOS 是一个 20mb Linux 发行版，将整个操作系统作为 Docker 容器运行
* [Kontena](https://www.kontena.io/) 大众应用容器
* [Weave](https://github.com/weaveworks/weave) 将 Docker 容器编织到应用程序中
* [Zodiac](https://github.com/CenturyLinkLabs/zodiac) 一个轻量级工具，可轻松部署和回滚 Docker 化应用程序
* [cAdvisor](https://github.com/google/cadvisor) 分析运行容器的资源使用情况和性能特征
* [Micro S3 persistence](https://github.com/figadore/micro-s3-persistence) 用于将卷数据保存/恢复到 S3 的 Docker 微服务
* [Rocker-compose](https://github.com/grammarly/rocker-compose) 具有幂等性功能的 Docker 组合工具，用于部署由多个容器组成的应用程序. 已弃用.
* [Nomad](https://github.com/hashicorp/nomad) Nomad 是一个集群管理器，专为长期服务和短期批处理工作负载而设计
* [ImageLayers](https://imagelayers.io/) 可视化 docker 镜像以及组成它们的层


## Datasets
## Realtime
* [Twitter Realtime](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) Streaming API 使开发人员能够低延迟地访问 Twitter 的全球推文数据流.
* [Eventsim](https://github.com/Interana/eventsim) 事件数据模拟器. 从一组用户生成伪随机事件流，旨在模拟 Web 流量.
* [Reddit](https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/) 提供实时数据，包括评论、提交内容和发布到 reddit 的链接

## Data Dumps
* [GitHub Archive](https://www.gharchive.org/) GitHub 自 2011 年以来的公开时间表，每小时更新一次
* [Common Crawl](https://commoncrawl.org/) 网络爬取数据的开源存储库
* [Wikipedia](https://dumps.wikimedia.org/enwiki/latest/) 维基百科所有 wiki 的完整副本，采用嵌入 XML 的 wiki 文本源和元数据的形式. 还提供许多 SQL 形式的原始数据库表.

## Monitoring

## Prometheus
* [Prometheus.io](https://github.com/prometheus/prometheus) 开源的服务监控系统和时序数据库
* [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) 简单的服务器，用于抓取 HAProxy 统计信息并通过 HTTP 导出它们以供 Prometheus 使用

## Community

## Forums
* [/r/dataengineering](https://www.reddit.com/r/dataengineering/) 数据工程的新闻、技巧和背景
* [/r/etl](https://www.reddit.com/r/ETL/) Reddit 子版块专注于 ETL

## Conferences
* [Data Council](https://www.datacouncil.ai/about) 数据委员会是第一个弥合数据科学家、数据工程师和数据分析师之间差距的技术会议.

## Podcasts
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com/) 关于现代数据基础设施的节目.

干杯 [The Data Engineering Ecosystem: An Interactive Map](http://xyz.insightdataengineering.com/blog/pipeline_map.html)

灵感来自于 [awesome](https://github.com/sindresorhus/awesome) 列表. 由...制作 [Insight Data Engineering](https://insightdataengineering.com) 各位.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Igor Barinov](https://github.com/igorbarinov/) 已放弃本作品的所有版权以及相关或邻接权.
