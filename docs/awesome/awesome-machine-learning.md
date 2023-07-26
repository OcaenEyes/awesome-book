<div class="github-widget" data-repo="josephmisiti/awesome-machine-learning"></div>
## Awesome Machine Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/josephmisiti/awesome-machine-learning/)

精彩的机器学习框架、库和软件的精选列表（按语言）. 受到“awesome-php”的启发.

_如果您想对此列表做出贡献（请这样做），请向我发送拉取请求或联系我 [@josephmisiti](https://twitter.com/josephmisiti)._
此外，如果出现以下情况，则应弃用列出的存储库：

* 存储库的所有者明确表示“该库未被维护”.
* 长期（2~3年）未承诺.

更多资源：

* 要获取可供下载的免费机器学习书籍列表，请访问 [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/books.md).

* 如需专业机器学习活动列表，请访问 [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/events.md).

* 如需在线提供的（大部分）免费机器学习课程列表，请访问 [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/courses.md).

* 有关数据科学和机器学习的博客和新闻通讯列表，请访问 [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/blogs.md).

* 如需免费参加聚会和当地活动的列表，请访问 [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/meetups.md).


### Frameworks and Libraries
<!-- MarkdownTOC depth=4 -->

- [Awesome Machine Learning ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](#awesome-machine-learning-)





<!-- /MarkdownTOC -->

<a name="apl"></a>
## APL

<a name="apl-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [naive-apl](https://github.com/mattcunningham/naive-apl)  - APL 中朴素贝叶斯分类器的实现.  **[已弃用]**

<a name="c"></a>
## C

<a name="c-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [Darknet](https://github.com/pjreddie/darknet)  - Darknet 是一个用 C 和 CUDA 编写的开源神经网络框架. 它速度快、易于安装，并支持 CPU 和 GPU 计算.
* [Recommender](https://github.com/GHamrouni/Recommender) - 使用协同过滤 (CF) 的产品推荐/建议的 AC 库.
* [Hybrid Recommender System](https://github.com/SeniorSA/hybrid-rs-trainner)  - 基于 scikit-learn 算法的混合推荐系统.  **[已弃用]**
* [neonrvm](https://github.com/siavashserver/neonrvm)  - neonrvm是一个基于RVM技术的开源机器学习库. 它是用 C 编程语言编写的，并附带 Python 编程语言绑定.
* [cONNXr](https://github.com/alrevuelta/cONNXr)  - 用纯 C (99) 编写的“ONNX”运行时，零依赖，专注于小型嵌入式设备. 无论您使用哪种框架进行训练，都可以对机器学习模型进行推理. 即使在非常旧的设备中，也易于在任何地方安装和编译.
* [libonnx](https://github.com/xboot/libonnx) - 轻量级、便携式纯 C99 onnx 推理引擎，适用于具有硬件加速支持的嵌入式设备.

<a name="c-computer-vision"></a>
#### Computer Vision

* [CCV](https://github.com/liuliu/ccv) - 基于 C/缓存/核心计算机视觉库，现代计算机视觉库.
* [VLFeat](http://www.vlfeat.org/) - VLFeat 是一个开放且可移植的计算机视觉算法库，它有一个 Matlab 工具箱.

<a name="cpp"></a>
## C++

<a name="cpp-computer-vision"></a>
#### Computer Vision

* [DLib](http://dlib.net/imaging.html) - DLib 具有用于人脸检测和训练通用对象检测器的 C++ 和 Python 接口.
* [EBLearn](http://eblearn.sourceforge.net/) - Eblearn 是一个面向对象的 C++ 库，可实现各种机器学习模型 **[已弃用]**
* [OpenCV](https://opencv.org) - OpenCV 具有 C++、C、Python、Java 和 MATLAB 接口，支持 Windows、Linux、Android 和 Mac OS.
* [VIGRA](https://github.com/ukoethe/vigra) - VIGRA 是一个通用的跨平台 C++ 计算机视觉和机器学习库，适用于具有 Python 绑定的任意维度的卷.
* [Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - 实时多人关键点检测库，用于身体、面部、手部和脚部估计

<a name="cpp-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Speedster](https://github.com/nebuly-ai/nebullvm/tree/main/apps/accelerate/speedster)  -自动应用 SOTA 优化技术，以在您的硬件上实现最大的推理加速.  [深度学习]
* [BanditLib](https://github.com/jkomiyama/banditlib)  - 一个简单的多臂强盗库.  **[已弃用]**
* [Caffe](https://github.com/BVLC/caffe)  - 开发时考虑到清洁性、可读性和速度的深度学习框架.  [深度学习]
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, contains fast inference implementation and supports CPU and GPU (even multi-GPU) computation.
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Research 的计算网络工具包 (CNTK) 是一个统一的深度学习工具包，它将神经网络描述为通过有向图的一系列计算步骤.
* [CUDA](https://code.google.com/p/cuda-convnet/) - 这是卷积 [深度学习] 的快速 C++/CUDA 实现
* [DeepDetect](https://github.com/jolibrain/deepdetect)  - 用 C++11 编写的机器学习 API 和服务器. 它使最先进的机器学习易于使用并集成到现有应用程序中.
* [Distributed Machine learning Tool Kit (DMTK)](http://www.dmtk.io/)  - Microsoft 的分布式机器学习（参数服务器）框架. 支持跨多台机器对大数据集进行训练模型. 当前与其捆绑的工具包括：LightLDA 和分布式（多义）词嵌入.
* [DLib](http://dlib.net/ml.html) - 一套旨在轻松嵌入其他应用程序的机器学习工具.
* [DSSTNE](https://github.com/amznlabs/amazon-dsstne) - Amazon 创建的软件库，用于使用 GPU 训练和部署深度神经网络，强调速度和规模而不是实验灵活性.
* [DyNet](https://github.com/clab/dynet)  - 动态神经网络库，与具有针对每个训练实例而变化的动态结构的网络配合良好. 用 C++ 编写，并用 Python 进行绑定.
* [Fido](https://github.com/FidoProject/Fido) - 用于嵌入式电子和机器人的高度模块化 C++ 机器学习库.
* [igraph](http://igraph.org/) - 通用图形库.
* [Intel® oneAPI Data Analytics Library](https://github.com/oneapi-src/oneDAL)  - 由英特尔开发并针对英特尔架构进行优化的高性能软件库. 库为数据分析的所有阶段提供算法构建块，并允许以批量、在线和分布式模式处理数据.
* [LightGBM](https://github.com/Microsoft/LightGBM) - Microsoft 基于决策树算法的快速、分布式、高性能梯度提升（GBDT、GBRT、GBM 或 MART）框架，用于排名、分类和许多其他机器学习任务.
* [libfm](https://github.com/srendle/libfm) - 一种通用方法，允许通过特征工程模拟大多数分解模型.
* [MLDB](https://mldb.ai)  - 机器学习数据库是专为机器学习而设计的数据库. 通过 RESTful API 向其发送命令以存储数据，使用 SQL 探索数据，然后训练机器学习模型并将其公开为 API.
* [mlpack](https://www.mlpack.org/) - 可扩展的 C++ 机器学习库.
* [MXNet](https://github.com/apache/incubator-mxnet)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [N2D2](https://github.com/CEA-LIST/N2D2) - CEA-List 的 CAD 框架，用于设计和模拟深度神经网络，并在嵌入式平台上构建完整的基于 DNN 的应用程序
* [oneDNN](https://github.com/oneapi-src/oneDNN) - 用于深度学习应用程序的开源跨平台性能库.
* [ParaMonte](https://github.com/cdslaborg/paramonte)  - 具有 C/C++ 接口的通用库，用于通过串行/并行蒙特卡罗和 MCMC 模拟进行贝叶斯数据分析和可视化. 文档可以找到 [here](https://www.cdslab.org/paramonte/).
* [proNet-core](https://github.com/cnclabs/proNet-core) - 通用网络嵌入框架：成对表示优化网络编辑.
* [PyCaret](https://github.com/pycaret/pycaret) - Python 中的开源低代码机器学习库，可自动执行机器学习工作流程.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - CUDA 的 Python 接口
* [ROOT](https://root.cern.ch)  - 模块化科学软件框架. 它提供了处理大数据处理、统计分析、可视化和存储所需的所有功能.
* [shark](http://image.diku.dk/shark/sphinx_pages/build/html/index.html) - 一个快速、模块化、功能丰富的开源 C++ 机器学习库.
* [Shogun](https://github.com/shogun-toolbox/shogun) - 幕府将军机器学习工具箱.
* [sofia-ml](https://code.google.com/archive/p/sofia-ml) - 一套快速增量算法.
* [Stan](http://mc-stan.org/) - 一种概率编程语言，通过哈密顿蒙特卡罗采样实现完整的贝叶斯统计推断.
* [Timbl](https://languagemachines.github.io/timbl/)  - 实现多种基于内存的学习算法的软件包/C++ 库，其中 IB1-IG（k 最近邻分类的实现）和 IGTree（IB1-IG 的决策树近似）. 常用于 NLP.
* [Vowpal Wabbit (VW)](https://github.com/VowpalWabbit/vowpal_wabbit) - 快速的核心外学习系统.
* [Warp-CTC](https://github.com/baidu-research/warp-ctc) - 在 CPU 和 GPU 上快速并行实现联结时间分类 (CTC).
* [XGBoost](https://github.com/dmlc/xgboost) - 并行优化的通用梯度增强库.
* [ThunderGBM](https://github.com/Xtra-Computing/thundergbm) - GPU 上的 GBDT 和随机森林的快速库.
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) - GPU 和 CPU 上的快速 SVM 库.
* [LKYDeepNN](https://github.com/mosdeo/LKYDeepNN)  - 仅限头文件的 C++11 神经网络库. 低依赖性，原生繁体中文文档.
* [xLearn](https://github.com/aksnzhy/xlearn)  - 高性能、易于使用、可扩展的机器学习包，可用于解决大规模机器学习问题.  xLearn 对于解决大规模稀疏数据的机器学习问题特别有用，这在在线广告和推荐系统等互联网服务中非常常见.
* [Featuretools](https://github.com/featuretools/featuretools)  - 用于自动化特征工程的库. 它擅长使用可重用的特征工程“基元”将事务和关系数据集转换为用于机器学习的特征矩阵.
* [skynet](https://github.com/Tyill/skynet) - A library for learning neural networks, has C-interface, net set in JSON. Written in C++ with bindings in Python, C++ and C#.
* [Feast](https://github.com/gojek/feast)  - 用于管理、发现和访问机器学习功能的功能存储.  Feast 为模型训练和模型服务提供一致的特征数据视图.
* [Hopsworks](https://github.com/logicalclocks/hopsworks)  - 人工智能数据密集型平台，拥有业界第一个开源特征存储.  Hopsworks Feature Store 既提供了基于 Apache Hive 的用于训练和批处理的特征仓库，也提供了基于 MySQL Cluster 的用于在线应用程序的特征服务数据库.
* [Polyaxon](https://github.com/polyaxon/polyaxon) - 可重复且可扩展的机器学习和深度学习平台.
* [QuestDB](https://questdb.io/) 面向列的关系数据库，专为时间序列和事件数据的实时分析而设计.
* [Phoenix](https://phoenix.arize.com) 发现见解、表面问题、监控和微调您的生成式 LLM、CV 和表格模型.

<a name="cpp-natural-language-processing"></a>
#### Natural Language Processing

* [BLLIP Parser](https://github.com/BLLIP/bllip-parser) - BLLIP 自然语言解析器（也称为 Charniak-Johnson 解析器）.
* [colibri-core](https://github.com/proycon/colibri-core) - C++ 库、命令行工具和 Python 绑定，用于以快速且节省内存的方式提取和使用基本语言结构，例如 n-gram 和 Skipgram.
* [CRF++](https://taku910.github.io/crfpp/) - Open source implementation of Conditional Random Fields (CRFs) for segmenting/labeling sequential data & other Natural Language Processing tasks. **[Deprecated]**
* [CRFsuite](http://www.chokkan.org/software/crfsuite/)  - CRFsuite 是用于标记顺序数据的条件随机场 (CRF) 的实现.  **[已弃用]**
* [frog](https://github.com/LanguageMachines/frog) - 为荷兰语开发的基于内存的 NLP 套件：PoS 标注器、词形还原器、依存解析器、NER、浅层解析器、形态分析器.
* [libfolia](https://github.com/LanguageMachines/libfolia) - C++ 库 [FoLiA format](https://proycon.github.io/folia/)
* [MeTA](https://github.com/meta-toolkit/meta) - [MeTA : ModErn Text Analysis](https://meta-toolkit.org/) 是一个 C++ 数据科学工具包，有助于挖掘大文本数据.
* [MIT Information Extraction Toolkit](https://github.com/mit-nlp/MITIE) - 用于命名实体识别和关系提取的 C、C++ 和 Python 工具
* [ucto](https://github.com/LanguageMachines/ucto)  - 适用于各种语言的基于 Unicode 感知正则表达式的分词器. 工具和 C++ 库. 支持 FoLiA 格式.

<a name="cpp-speech-recognition"></a>
#### Speech Recognition
* [Kaldi](https://github.com/kaldi-asr/kaldi)  - Kaldi 是一个用 C++ 编写的语音识别工具包，并根据 Apache License v2.0 获得许可.  Kaldi 旨在供语音识别研究人员使用.

<a name="cpp-sequence-analysis"></a>
#### Sequence Analysis
* [ToPS](https://github.com/ayoshiaki/tops)  - 这是一个面向对象的框架，有助于在用户定义的字母表上集成序列的概率模型.  **[已弃用]**

<a name="cpp-gesture-detection"></a>
#### Gesture Detection
* [grt](https://github.com/nickgillian/grt) - 手势识别工具包 (GRT) 是一个跨平台、开源、C++ 机器学习库，专为实时手势识别而设计.

<a name="common-lisp"></a>
## Common Lisp

<a name="common-lisp-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [mgl](https://github.com/melisgl/mgl/) - 神经网络（玻尔兹曼机、前馈和循环网络）、高斯过程.
* [mgl-gpr](https://github.com/melisgl/mgl-gpr/)  - 进化算法.  **[已弃用]**
* [cl-libsvm](https://github.com/melisgl/cl-libsvm/)  - libsvm 支持向量机库的包装.  **[已弃用]**
* [cl-online-learning](https://github.com/masatoi/cl-online-learning) - 在线学习算法（感知器、AROW、SCW、逻辑回归）.
* [cl-random-forest](https://github.com/masatoi/cl-random-forest) - 在 Common Lisp 中实现随机森林.

<a name="clojure"></a>
## Clojure

<a name="clojure-natural-language-processing"></a>
#### Natural Language Processing

* [Clojure-openNLP](https://github.com/dakrone/clojure-opennlp) - Clojure 中的自然语言处理 (opennlp).
* [Infections-clj](https://github.com/r0man/inflections-clj) - 用于 Clojure 和 ClojureScript 的类似 Rails 的变形库.

<a name="clojure-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [scicloj.ml](https://github.com/scicloj/scicloj.ml) - 基于 tech.ml.dataset 的惯用 Clojure 机器学习库，具有用于不可变数据处理管道的独特方法.
* [clj-ml](https://github.com/joshuaeckroth/clj-ml/) - 基于 Weka 和朋友构建的 Clojure 机器学习库.
* [clj-boost](https://gitlab.com/alanmarazzi/clj-boost) - XGBoost 的包装
* [Touchstone](https://github.com/ptaoussanis/touchstone) - Clojure A/B 测试库.
* [Clojush](https://github.com/lspector/Clojush) - 在 Clojure 中实现的 Push 编程语言和 PushGP 遗传编程系统.
* [lambda-ml](https://github.com/cloudkj/lambda-ml) - Clojure 中机器学习技术和实用程序的简单、简洁的实现.
* [Infer](https://github.com/aria42/infer)  - Clojure 中的推理和机器学习.  **[已弃用]**
* [Encog](https://github.com/jimpil/enclog)  - Encog (v3) 的 Clojure 包装器（专门研究神经网络的机器学习框架）.  **[已弃用]**
* [Fungp](https://github.com/vollmerm/fungp)  - Clojure 的遗传编程库.  **[已弃用]**
* [Statistiker](https://github.com/clojurewerkz/statistiker)  - Clojure 中的基本机器学习算法.  **[已弃用]**
* [clortex](https://github.com/htm-community/clortex)  - 使用 Numenta 的皮质学习算法的通用机器学习库.  **[已弃用]**
* [comportex](https://github.com/htm-community/comportex)  - 使用 Numenta 的皮质学习算法的功能可组合机器学习库.  **[已弃用]**

<a name="clojure-deep-learning"></a>
#### Deep Learning
* [MXNet](https://mxnet.apache.org/versions/1.7.0/api/clojure) - 绑定到 Apache MXNet - MXNet 项目的一部分
* [Deep Diamond](https://github.com/uncomplicate/deep-diamond) - 快速 Clojure 张量和深度学习库
* [jutsu.ai](https://github.com/hswick/jutsu.ai) - 用于 deeplearning4j 的 Clojure 包装器，添加了一些语法糖.
* [cortex](https://github.com/originrose/cortex) - Clojure 中的神经网络、回归和特征学习.
* [Flare](https://github.com/aria42/flare) - Clojure 中的动态张量图库（例如 PyTorch、DynNet 等）
* [dl4clj](https://github.com/yetanalytics/dl4clj) - Deeplearning4j 的 Clojure 包装器.

<a name="clojure-data-analysis--data-visualization"></a>
#### Data Analysis
* [tech.ml.dataset](https://github.com/techascent/tech.ml.dataset) - 用于数据处理和机器学习的 Clojure 数据框架库和管道
* [Tablecloth](https://github.com/scicloj/tablecloth) - 数据框语法包装 tech.ml.dataset，受到多个 R 库的启发
* [Panthera](https://github.com/alanmarazzi/panthera) - Clojure API 包装 Python 的 Pandas 库
* [Incanter](http://incanter.org/) - Incanter 是一个基于 Clojure 的类似 R 的统计计算和图形平台.
* [PigPen](https://github.com/Netflix/PigPen) - Clojure 的 Map-Reduce.
* [Geni](https://github.com/zero-one-group/geni) - 在 Apache Spark 上运行的 Clojure 数据框架库

<a name="clojure-data-visualization"></a>
#### Data Visualization
* [Hanami](https://github.com/jsa-aerial/hanami)  ：Clojure(Script) 库和框架，用于创建基于 Vega-Lite (VGL) 和/或 Vega (VG) 规范的交互式可视化应用程序. 自动框架和布局以及用于抽象可视化规范的强大模板系统
* [Saite](https://github.com/jsa-aerial/saite) - Clojure（Script）客户端/服务器应用程序，用于动态交互式探索并创建实时可共享文档，使用 Vega/Vega-Lite、CodeMirror、markdown 和 LaTeX 捕获它们
* [Oz](https://github.com/metasoarous/oz) - 使用 Vega/Vega-Lite 和 Hiccup 进行数据可视化，以及用于文学编程的实时重新加载平台
* [Envision](https://github.com/clojurewerkz/envision) - Clojure 数据可视化库，基于 Statistiker 和 D3.
* [Pink Gorilla Notebook](https://github.com/pink-gorilla/gorilla-notebook) - 基于 Gorilla-REPL 的 Clojure/Clojurescript 笔记本应用程序/库
* [clojupyter](https://github.com/clojupyter/clojupyter) - Clojure 的 Jupyter 内核 - 在 Jupyter 实验室、笔记本和控制台中运行 Clojure 代码.
* [notespace](https://github.com/scicloj/notespace) - Clojure 命名空间中的笔记本体验
* [Delight](https://github.com/datamechanics/delight) - 一个监听器，可以流式传输您的 Spark 事件日志以取悦您，这是一个免费且改进的 Spark UI

<a name="clojure-interop"></a>
#### Interop

* [Java Interop](https://clojure.org/reference/java_interop) - Clojure 具有 Native Java Interop，可以从中访问 Java 的 ML 生态系统
* [JavaScript Interop](https://clojurescript.org/reference/javascript-api) - ClojureScript 具有本机 JavaScript 互操作性，可以从中访问 JavaScript 的 ML 生态系统
* [Libpython-clj](https://github.com/clj-python/libpython-clj) - 与Python的互操作
* [ClojisR](https://github.com/scicloj/clojisr) - 与 R 和 Renjin 的互操作（JVM 上的 R）

<a name="clojure-misc"></a>
#### Misc
* [Neanderthal](https://neanderthal.uncomplicate.org/) - 快速 Clojure 矩阵库（原生 CPU、GPU、OpenCL、CUDA）
* [kixistats](https://github.com/MastodonC/kixi.stats) - 统计分布采样和转换函数库
* [fastmath](https://github.com/generateme/fastmath) - 数学和统计计算、机器学习等函数的集合，包装了多个 JVM 库
* [matlib](https://github.com/atisharma/matlib) - 基于 Neanderthal 的优化和控制理论工具以及便利函数的 Clojure 库.

<a name="clojure-extra"></a>
#### Extra
* [Scicloj](https://scicloj.github.io/pages/libraries/) - Clojure ML 相关资源的精选列表.

<a name="crystal"></a>
## Crystal

<a name="crystal-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [machine](https://github.com/mathieulaporte/machine) - 简单的机器学习算法.
* [crystal-fann](https://github.com/NeuraLegion/crystal-fann) - FANN（快速人工神经网络）绑定.

<a name="elixir"></a>
## Elixir

<a name="elixir-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Simple Bayes](https://github.com/fredwu/simple_bayes) - Elixir 中的简单贝叶斯/朴素贝叶斯实现.
* [emel](https://github.com/mrdimosthenis/emel) - 用 Elixir 编写的简单且实用的机器学习库.
* [Tensorflex](https://github.com/anshuman23/tensorflex) - Elixir 编程语言的 Tensorflow 绑定.

<a name="elixir-natural-language-processing"></a>
#### Natural Language Processing

* [Stemmer](https://github.com/fredwu/stemmer) - Elixir 中的英语 (Porter2) 词干实现.

<a name="erlang"></a>
## Erlang

<a name="erlang-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Disco](https://github.com/discoproject/disco/)  - Erlang 中的地图缩减.  **[已弃用]**

<a name="fortran"></a>
## Fortran

<a name="fortran-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [neural-fortran](https://github.com/modern-fortran/neural-fortran) - 并行神经网络微框架.
阅读论文 [here](https://arxiv.org/abs/1902.06714).

<a name="fortran-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [ParaMonte](https://github.com/cdslaborg/paramonte)  - 通用 Fortran 库，用于通过串行/并行蒙特卡罗和 MCMC 模拟进行贝叶斯数据分析和可视化. 文档可以找到 [here](https://www.cdslab.org/paramonte/).

<a name="go"></a>
## Go

<a name="go-natural-language-processing"></a>
#### Natural Language Processing

* [Cybertron](https://github.com/nlpodyssey/cybertron) - 塞伯坦：围棋中变形金刚的家乡星球.
* [snowball](https://github.com/tebeka/snowball) - 雪球投票给 Go.
* [word-embedding](https://github.com/ynqa/word-embedding) - 词嵌入：Word2vec、GloVe 在 Go 中的完整实现.
* [sentences](https://github.com/neurosnap/sentences) - Punkt 句子标记器的 Golang 实现.
* [go-ngram](https://github.com/Lazin/go-ngram)  - 带压缩的内存中 n-gram 索引.  *[已弃用]*
* [paicehusk](https://github.com/Rookii/paicehusk)  - Paice/Husk 词干算法的 Golang 实现.  *[已弃用]*
* [go-porterstemmer](https://github.com/reiver/go-porterstemmer)  - Porter Stemming 算法的原生 Go 洁净室实现.  **[已弃用]**

<a name="go-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Spago](https://github.com/nlpodyssey/spago) - Go 中独立的机器学习和自然语言处理库.
* [birdland](https://github.com/rlouf/birdland) - Go 中的推荐库.
* [eaopt](https://github.com/MaxHalford/eaopt) - 进化优化库.
* [leaves](https://github.com/dmitryikh/leaves) - GBRT 预测部分的纯 Go 实现，包括 XGBoost 和 LightGBM.
* [gobrain](https://github.com/goml/gobrain) - 用 Go 编写的神经网络.
* [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Go 中低延迟机器学习的快速便捷的特征处理.
* [go-mxnet-predictor](https://github.com/songtianyi/go-mxnet-predictor) - 绑定 MXNet c_predict_api 以使用预训练模型进行推理.
* [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Go 机器学习推理基准.
* [go-ml-transpiler](https://github.com/znly/go-ml-transpiler) - 用于机器学习模型的开源 Go 转译器.
* [golearn](https://github.com/sjwhitworth/golearn) - Machine learning for Go.
* [goml](https://github.com/cdipaolo/goml) - 用纯 Go 编写的机器学习库.
* [gorgonia](https://github.com/gorgonia/gorgonia) - Go 中的深度学习.
* [goro](https://github.com/aunum/goro) - Keras 风格的高级机器学习库.
* [gorse](https://github.com/zhenghaoz/gorse) - 用 Go 编写的基于协同过滤的离线推荐系统后端.
* [therfoo](https://github.com/therfoo/therfoo) - Go 的嵌入式深度学习库.
* [neat](https://github.com/jinyeom/neat)  - 用于增强拓扑的 NeuroEvolution (NEAT) 的即插即用、并行 Go 框架.  **[已弃用]**
* [go-pr](https://github.com/daviddengcn/go-pr)  - Go 语言中的模式识别包.  **[已弃用]**
* [go-ml](https://github.com/alonsovidales/go_ml)  - 线性/逻辑回归、神经网络、协同过滤和高斯多元分布.  **[已弃用]**
* [GoNN](https://github.com/fxsjy/gonn)  - GoNN是Go语言的神经网络实现，包括BPNN、RBF、PCN.  **[已弃用]**
* [bayesian](https://github.com/jbrukh/bayesian)  - Golang 的朴素贝叶斯分类.  **[已弃用]**
* [go-galib](https://github.com/thoj/go-galib)  - 用 Go / Golang 编写的遗传算法库.  **[已弃用]**
* [Cloudforest](https://github.com/ryanbressler/CloudForest)  - Go/Golang 中的决策树集合.  **[已弃用]**
* [go-dnn](https://github.com/sudachen/go-dnn) - Golang 深度神经网络（由 MXNet 提供支持）

<a name="go-spatial-analysis-and-geometry"></a>
#### Spatial analysis and geometry

* [go-geom](https://github.com/twpayne/go-geom) - 去图书馆处理几何图形.
* [gogeo](https://github.com/golang/geo) - Go 中的球面几何.

<a name="go-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - 用于机器学习和统计的数据框架（类似于 pandas）.
* [gota](https://github.com/go-gota/gota) - 数据框.
* [gonum/mat](https://godoc.org/gonum.org/v1/gonum/mat) - Go 的线性代数包.
* [gonum/optimize](https://godoc.org/gonum.org/v1/gonum/optimize) - 优化算法的实现.
* [gonum/plot](https://godoc.org/gonum.org/v1/plot) - 绘图库.
* [gonum/stat](https://godoc.org/gonum.org/v1/gonum/stat) - 统计图书馆.
* [SVGo](https://github.com/ajstarks/svgo) - 用于 SVG 生成的 Go 语言库.
* [glot](https://github.com/arafatk/glot) - Glot 是一个构建在 gnuplot 之上的 Golang 绘图库.
* [globe](https://github.com/mmcloughlin/globe) - 地球线框可视化.
* [gonum/graph](https://godoc.org/gonum.org/v1/gonum/graph) - 通用图形库.
* [go-graph](https://github.com/StepLg/go-graph)  - Go/Golang 语言的图形库.  **[已弃用]**
* [RF](https://github.com/fxsjy/RF.go)  - Go 中的随机森林实现.  **[已弃用]**

<a name="go-computer-vision"></a>
#### Computer vision

* [GoCV](https://github.com/hybridgroup/gocv) - 使用 OpenCV 4 及更高版本的计算机视觉包.

<a name="go-reinforcement-learning"></a>
#### Reinforcement learning

* [gold](https://github.com/aunum/gold) - 强化学习库.

<a name="haskell"></a>
## Haskell

<a name="haskell-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [haskell-ml](https://github.com/ajtulloch/haskell-ml)  - 各种机器学习算法的 Haskell 实现.  **[已弃用]**
* [HLearn](https://github.com/mikeizbicki/HLearn)  - 一套用于根据代数结构解释机器学习模型的库.  **[已弃用]**
* [hnn](https://github.com/alpmestan/HNN) - Haskell 神经网络库.
* [hopfield-networks](https://github.com/ajtulloch/hopfield-networks)  - Hopfield Networks 用于 Haskell 中的无监督学习.  **[已弃用]**
* [DNNGraph](https://github.com/ajtulloch/dnngraph)  - 用于深度神经网络的 DSL.  **[已弃用]**
* [LambdaNet](https://github.com/jbarrow/LambdaNet)  - Haskell 中的可配置神经网络.  **[已弃用]**

<a name="java"></a>
## Java

<a name="java-natural-language-processing"></a>
#### Natural Language Processing
* [Cortical.io](https://www.cortical.io/) - Retina：一个像大脑一样快速直观地执行复杂 NLP 操作（消歧、分类、流文本过滤等）的 API.
* [IRIS](https://github.com/cortical-io/Iris) - [Cortical.io's](https://cortical.io) 免费 NLP、Retina API 分析工具（用 JavaFX 编写！）- [See the Tutorial Video](https://www.youtube.com/watch?v=CsF4pd7fGF0).
* [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Stanford CoreNLP provides a set of natural language analysis tools which can take raw English language text input and give the base forms of words.
* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml) - 自然语言解析器是一种计算句子语法结构的程序.
* [Stanford POS Tagger](https://nlp.stanford.edu/software/tagger.shtml) - 词性标注器（词性标注器）.
* [Stanford Name Entity Recognizer](https://nlp.stanford.edu/software/CRF-NER.shtml) - 斯坦福 NER 是命名实体识别器的 Java 实现.
* [Stanford Word Segmenter](https://nlp.stanford.edu/software/segmenter.shtml) - 原始文本的标记化是许多 NLP 任务的标准预处理步骤.
* [Tregex, Tsurgeon and Semgrex](https://nlp.stanford.edu/software/tregex.shtml) - Tregex 是一个用于匹配树中模式的实用程序，基于树关系和节点上的正则表达式匹配（名称是“树正则表达式”的缩写）.
* [Stanford Phrasal: A Phrase-Based Translation System](https://nlp.stanford.edu/phrasal/)
* [Stanford English Tokenizer](https://nlp.stanford.edu/software/tokenizer.shtml) -斯坦福短语是一个最先进的基于统计短语的机器翻译系统，用 Java 编写.
* [Stanford Tokens Regex](https://nlp.stanford.edu/software/tokensregex.shtml) - 分词器将文本划分为一系列标记，这些标记大致对应于“单词”.
* [Stanford Temporal Tagger](https://nlp.stanford.edu/software/sutime.shtml) - SUTime 是一个用于识别和标准化时间表达式的库.
* [Stanford SPIED](https://nlp.stanford.edu/software/patternslearning.shtml) - 从未标记的文本中学习实体，从种子集开始，以迭代方式使用模式.
* [Twitter Text Java](https://github.com/twitter/twitter-text/tree/master/java) - Twitter 文本处理库的 Java 实现.
* [MALLET](http://mallet.cs.umass.edu/) - 一个基于 Java 的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用程序.
* [OpenNLP](https://opennlp.apache.org/) - 用于处理自然语言文本的基于机器学习的工具包.
* [LingPipe](http://alias-i.com/lingpipe/index.html) - 使用计算语言学处理文本的工具包.
* [ClearTK](https://github.com/ClearTK/cleartk)  - ClearTK 提供了一个用于在 Java 中开发统计自然语言处理 (NLP) 组件的框架，并且构建在 Apache UIMA 之上.  **[已弃用]**
* [Apache cTAKES](https://ctakes.apache.org/) - Apache 临床文本分析和知识提取系统 (cTAKES) 是一个开源自然语言处理系统，用于从电子病历临床自由文本中提取信息.
* [NLP4J](https://github.com/emorynlp/nlp4j)  - NLP4J 项目提供用于自然语言处理的软件和资源. 该项目始于计算语言和教育研究中心，目前由埃默里大学语言和信息研究中心开发.  **[已弃用]**
* [CogcompNLP](https://github.com/CogComp/cogcomp-nlp) - 该项目收集了伊利诺伊大学认知计算小组开发的一些自然语言处理（NLP）核心库，例如“illinois-core-utilities”，它提供了一组NLP友好的数据结构和一些与 NLP 相关的实用程序，支持编写 NLP 应用程序、运行实验等，“illinois-edison”是一个用于从 illinois-core-utilities 数据结构和许多其他包中提取特征的库.

<a name="java-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [aerosolve](https://github.com/airbnb/aerosolve) - Airbnb 的机器学习库从一开始就设计得人性化.
* [AMIDST Toolbox](http://www.amidsttoolbox.com/) - 用于可扩展概率机器学习的 Java 工具箱.
* [Chips-n-Salsa](https://github.com/cicirello/Chips-n-Salsa) - 用于遗传算法、进化计算和随机局部搜索的 Java 库，重点关注自适应/自调整以及并行执行.
* [Datumbox](https://github.com/datumbox/datumbox-framework) - 用于快速开发机器学习和统计应用程序的机器学习框架.
* [ELKI](https://elki-project.github.io/)  - 用于数据挖掘的 Java 工具包.  （无监督：聚类、异常值检测等）
* [Encog](https://github.com/encog/encog-java-core)  - 先进的神经网络和机器学习框架.  Encog 包含用于创建各种网络的类，以及用于标准化和处理这些神经网络数据的支持类. 使用多线程弹性传播进行 Encog 训练.  Encog 还可以利用 GPU 进一步加快处理时间. 还提供基于 GUI 的工作台来帮助建模和训练神经网络.
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/dev/libs/ml/index.html) - Flink 中的分布式机器学习库.
* [H2O](https://github.com/h2oai/h2o-3) - ML 引擎，支持通过 R、Python、Scala、REST/JSON 中的 API 在 Hadoop、Spark 或笔记本电脑上进行分布式学习.
* [htm.java](https://github.com/numenta/htm.java) - 使用 Numenta 的皮质学习算法的通用机器学习库.
* [liblinear-java](https://github.com/bwaldvogel/liblinear-java) - lib Linear 的 Java 版本.
* [Mahout](https://github.com/apache/mahout) - 分布式机器学习.
* [Meka](http://meka.sourceforge.net/) - 多标签分类和评估方法的开源实现（Weka 的扩展）.
* [MLlib in Apache Spark](https://spark.apache.org/docs/latest/mllib-guide.html) - Spark 中的分布式机器学习库.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - 用于将 Apache Spark MLLib 机器学习模型部署为实时、批处理或反应式 Web 服务的服务.
* [Neuroph](http://neuroph.sourceforge.net/) - Neuroph 是轻量级 Java 神经网络框架.
* [ORYX](https://github.com/oryxproject/oryx) - 使用 Apache Spark 和 Apache Kafka 的 Lambda 架构框架，专门用于实时大规模机器学习.
* [Samoa](https://samoa.incubator.apache.org/) SAMOA 是一个框架，其中包括针对数据流的分布式机器学习，以及可插入不同流处理平台的接口.
* [RankLib](https://sourceforge.net/p/lemur/wiki/RankLib/)  - RankLib 是一个学习排名算法的库.  **[已弃用]**
* [rapaio](https://github.com/padreati/rapaio) - Java 中的统计、数据挖掘和机器学习工具箱.
* [RapidMiner](https://rapidminer.com) - RapidMiner 集成到 Java 代码中.
* [Stanford Classifier](https://nlp.stanford.edu/software/classifier.shtml) - 分类器是一种机器学习工具，它将获取数据项并将它们放入 k 个类别之一.
* [Smile](https://haifengl.github.io/) - 统计机器智能和学习引擎.
* [SystemML](https://github.com/apache/systemml) - 灵活、可扩展的机器学习 (ML) 语言.
* [Tribou](https://tribuo.org) - 由 Oracle 用 Ja​​va 编写的机器学习库.
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Weka 是用于数据挖掘任务的机器学习算法的集合.
* [LBJava](https://github.com/CogComp/lbjava) - 基于学习的Java 是一种用于快速开发软件系统的建模语言，直接根据程序员应用程序中的对象为分类器和约束定义提供方便的声明性语法.
* [knn-java-library](https://github.com/felipexw/knn-java-library) - 只是使用一系列相似性度量的 K 最近邻算法的简单实现.

<a name="java-speech-recognition"></a>
#### Speech Recognition
* [CMU Sphinx](https://cmusphinx.github.io) - 纯粹基于Java语音识别库的语音识别开源工具包.

<a name="java-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [Flink](https://flink.apache.org/) - 用于分布式流和批量数据处理的开源平台.
* [Hadoop](https://github.com/apache/hadoop) - Hadoop/HDFS.
* [Onyx](https://github.com/onyx-platform/onyx)  - 分布式、无主、高性能、容错数据处理. 完全用 Clojure 编写.
* [Spark](https://github.com/apache/spark) - Spark是一种快速、通用的大规模数据处理引擎.
* [Storm](https://storm.apache.org/) - Storm 是一个分布式实时计算系统.
* [Impala](https://github.com/cloudera/impala) - Hadoop 实时查询.
* [DataMelt](https://jwork.org/dmelt/) - 用于数值计算、统计、符号计算、数据分析和数据可视化的数学软件.
* [Dr. Michael Thomas Flanagan's Java Scientific Library.](https://www.ee.ucl.ac.uk/~mflanaga/java/) **[已弃用]**

<a name="java-deep-learning"></a>
#### Deep Learning

* [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) - 具有并行 GPU 的可扩展工业深度学习.
* [Keras Beginner Tutorial](https://victorzhou.com/blog/keras-neural-network-tutorial/) - 使用 Keras 在 Python 中实现简单神经网络的友好指南.
* [deepjavalibrary/djl](https://github.com/deepjavalibrary/djl) - Deep Java Library (DJL) 是一个开源、高级、与引擎无关的深度学习 Java 框架，旨在让 Java 开发人员易于上手且易于使用.

<a name="javascript"></a>
## JavaScript

<a name="javascript-natural-language-processing"></a>
#### Natural Language Processing

* [Twitter-text](https://github.com/twitter/twitter-text) - Twitter 文本处理库的 JavaScript 实现.
* [natural](https://github.com/NaturalNode/natural) - 节点的通用自然语言设施.
* [Knwl.js](https://github.com/loadfive/Knwl.js) - JS 中的自然语言处理器.
* [Retext](https://github.com/retextjs/retext) - 用于分析和操作自然语言的可扩展系统.
* [NLP Compromise](https://github.com/spencermountain/compromise) - 浏览器中的自然语言处理.
* [nlp.js](https://github.com/axa-group/nlp.js) - 内置于 Node over Natural 的 NLP 库，具有实体提取、情感分析、自动语言识别等功能.



<a name="javascript-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [D3.js](https://d3js.org/)
* [High Charts](https://www.highcharts.com/)
* [NVD3.js](http://nvd3.org/)
* [dc.js](https://dc-js.github.io/dc.js/)
* [chartjs](https://www.chartjs.org/)
* [dimple](http://dimplejs.org/)
* [amCharts](https://www.amcharts.com/)
* [D3xter](https://github.com/NathanEpstein/D3xter)  - 基于 D3 的直接绘图.  **[已弃用]**
* [statkit](https://github.com/rigtorp/statkit)  - JavaScript 统计工具包.  **[已弃用]**
* [datakit](https://github.com/nathanepstein/datakit) - 用于 JavaScript 数据分析的轻量级框架
* [science.js](https://github.com/jasondavies/science.js/)  - JavaScript 中的科学和统计计算.  **[已弃用]**
* [Z3d](https://github.com/NathanEpstein/Z3d) - 轻松制作基于 Three.js 的交互式 3D 绘图 **[已弃用]**
* [Sigma.js](http://sigmajs.org/) - 专用于图形绘制的 JavaScript 库.
* [C3.js](https://c3js.org/) - 基于 D3.js 的可定制库，可轻松绘制图表.
* [Datamaps](https://datamaps.github.io/)  - 使用 D3.js 进行可定制的 SVG 地图/地理可视化.  **[已弃用]**
* [ZingChart](https://www.zingchart.com/) - 用 Vanilla JS 编写的用于大数据可视化的库.
* [cheminfo](https://www.cheminfo.org/) - 数据可视化和分析平台，使用 [visualizer](https://github.com/npellet/visualizer) 项目.
* [Learn JS Data](http://learnjsdata.com/)
* [AnyChart](https://www.anychart.com/)
* [FusionCharts](https://www.fusioncharts.com/)
* [Nivo](https://nivo.rocks) - 建立在很棒的 d3 和 Reactjs 库之上


<a name="javascript-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Auto ML](https://github.com/ClimbsRocks/auto_ml)  - 用于竞赛和探索的自动化机器学习、数据格式化、集成和超参数优化 - 只需给它一个 .csv 文件！  **[已弃用]**
* [Convnet.js](https://cs.stanford.edu/people/karpathy/convnetjs/) - ConvNetJS 是一个用于训练深度学习模型的 JavaScript 库[深度学习] **[已弃用]**
* [Clusterfck](https://harthur.github.io/clusterfck/)  - 在 JavaScript 中为 Node.js 和浏览器实现的聚合层次集群.  **[已弃用]**
* [Clustering.js](https://github.com/emilbayes/clustering.js)  - 在 Node.js 和浏览器的 JavaScript 中实现的聚类算法.  **[已弃用]**
* [Decision Trees](https://github.com/serendipious/nodejs-decision-tree-id3)  - 使用 ID3 算法的 NodeJS 决策树实现.  **[已弃用]**
* [DN2A](https://github.com/antoniodeluca/dn2a.js)  - 数字神经网络架构.  **[已弃用]**
* [figue](https://code.google.com/archive/p/figue) - K 均值、模糊 c 均值和凝聚聚类.
* [Gaussian Mixture Model](https://github.com/lukapopijac/gaussian-mixture-model) - 使用多元高斯混合模型的无监督机器学习.
* [Node-fann](https://github.com/rlidwka/node-fann) - Node.js 的 FANN（快速人工神经网络库）绑定 **[已弃用]**
* [Keras.js](https://github.com/transcranial/keras-js) - 在浏览器中运行 Keras 模型，并使用 WebGL 2 提供的 GPU 支持.
* [Kmeans.js](https://github.com/emilbayes/kMeans.js)  - k-means 算法的简单 JavaScript 实现，适用于 Node.js 和浏览器.  **[已弃用]**
* [LDA.js](https://github.com/primaryobjects/lda) - Node.js 的 LDA 主题建模
* [Learning.js](https://github.com/yandongliu/learningjs) - 逻辑回归/c4.5 决策树的 JavaScript 实现 **[已弃用]**
* [machinelearn.js](https://github.com/machinelearnjs/machinelearnjs) - 适用于 Web、Node.js 和开发人员的机器学习库
* [mil-tokyo](https://github.com/mil-tokyo) - 几个机器学习库的列表.
* [Node-SVM](https://github.com/nicolaspanel/node-svm) - Node.js 的支持向量机
* [Brain](https://github.com/harthur/brain) - JavaScript 中的神经网络 **[已弃用]**
* [Brain.js](https://github.com/BrainJS/brain.js) - JavaScript 中的神经网络 - 持续的社区分支 [Brain](https://github.com/harthur/brain).
* [Bayesian-Bandit](https://github.com/omphalos/bayesian-bandit.js)  - Node 和浏览器的贝叶斯强盗实现.  **[已弃用]**
* [Synaptic](https://github.com/cazala/synaptic) - 适用于 Node.js 和浏览器的无架构神经网络库.
* [kNear](https://github.com/NathanEpstein/kNear) - 用于监督学习的 k 最近邻算法的 JavaScript 实现.
* [NeuralN](https://github.com/totemstech/neuraln)  - Node.js 的 C++ 神经网络库. 它在大数据集和多线程训练方面具有优势.  **[已弃用]**
* [kalman](https://github.com/itamarwe/kalman)  - JavaScript 的卡尔曼滤波器.  **[已弃用]**
* [shaman](https://github.com/luccastera/shaman)  - Node.js 库支持简单和多元线性回归.  **[已弃用]**
* [ml.js](https://github.com/mljs/ml) - 适用于 Node.js 和浏览器的机器学习和数值分析工具！
* [ml5](https://github.com/ml5js/ml5-library) - 友好的网络机器学习！
* [Pavlov.js](https://github.com/NathanEpstein/Pavlov.js) - 使用马尔可夫决策过程的强化学习.
* [MXNet](https://github.com/apache/incubator-mxnet)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [TensorFlow.js](https://js.tensorflow.org/) - 一个基于浏览器的 WebGL 加速 JavaScript 库，用于训练和部署 ML 模型.
* [JSMLT](https://github.com/jsmlt/jsmlt)  - 具有 Node.js 分类和聚类功能的机器学习工具包； 支持可视化（参见 [visualml.io](https://visualml.io)).
* [xgboost-node](https://github.com/nuanio/xgboost-node) - 运行 XGBoost 模型并在 Node.js 中进行预测.
* [Netron](https://github.com/lutzroeder/netron) - 机器学习模型的可视化工具.
* [tensor-js](https://github.com/Hoff97/tensorjs) - 浏览器的深度学习库，由 WebGL 和 WebAssembly 加速.
* [WebDNN](https://github.com/mil-tokyo/webdnn)  - 快速深度神经网络 JavaScript 框架.  WebDNN 使用下一代 JavaScript API、用于 GPU 执行的 WebGPU 和用于 CPU 执行的 WebAssembly.

<a name="javascript-misc"></a>
#### Misc

* [stdlib](https://github.com/stdlib-js/stdlib)  - JavaScript 和 Node.js 的标准库，重点是数值计算. 该库提供了一系列强大的高性能库，用于数学、统计、流、实用程序等.
* [sylvester](https://github.com/jcoglan/sylvester)  - JavaScript 的向量和矩阵数学.  **[已弃用]**
* [simple-statistics](https://github.com/simple-statistics/simple-statistics)  - 描述性统计、回归统计和推理统计的 JavaScript 实现. 使用无依赖关系的 JavaScript 实现，设计用于所有现代浏览器（包括 IE）以及 Node.js.
* [regression-js](https://github.com/Tom-Alexander/regression-js) - 一个 javascript 库，包含最小二乘拟合方法的集合，用于查找一组数据中的趋势.
* [Lyric](https://github.com/flurry/Lyric)  - 线性回归库.  **[已弃用]**
* [GreatCircle](https://github.com/mwgg/GreatCircle) - 用于计算大圆距离的库.
* [MLPleaseHelp](https://github.com/jgreenemi/MLPleaseHelp)  - MLPleaseHelp 是一个简单的 ML 资源搜索引擎. 您现在可以使用此搜索引擎： [https://jgreenemi.github.io/MLPleaseHelp/](https://jgreenemi.github.io/MLPleaseHelp/)，通过 GitHub Pages 提供.
* [Pipcook](https://github.com/alibaba/pipcook) - 用于机器学习及其工程的 JavaScript 应用程序框架.

<a name="javascript-demos-and-scripts"></a>
#### Demos and Scripts
* [The Bot](https://github.com/sta-ger/TheBot) - 神经网络如何学习预测使用创建的两点之间的角度的示例 [Synaptic](https://github.com/cazala/synaptic).
* [Half Beer](https://github.com/sta-ger/HalfBeer) - 创建的啤酒杯分类器 [Synaptic](https://github.com/cazala/synaptic).
* [Rock Paper Scissors](https://rps-tfjs.netlify.com/) - 使用 TensorFlow.js 在浏览器中训练石头剪刀布
* [Heroes Wear Masks](https://heroeswearmasks.fun/)  - 一个有趣的基于 TensorFlow.js 的预言机，可以判断一个人是否戴口罩. 它甚至可以判断一个人是否错误地佩戴了口罩.

<a name="julia"></a>
## Julia

<a name="julia-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [MachineLearning](https://github.com/benhamner/MachineLearning.jl)  - 朱莉娅机器学习库.  **[已弃用]**
* [MLBase](https://github.com/JuliaStats/MLBase.jl) - 一组支持机器学习算法开发的函数.
* [PGM](https://github.com/JuliaStats/PGM.jl) - 用于概率图形模型的 Julia 框架.
* [DA](https://github.com/trthatcher/DiscriminantAnalysis.jl) - 用于正则判别分析的 Julia 包.
* [Regression](https://github.com/lindahua/Regression.jl)  - 回归分析算法（例如线性回归和逻辑回归）.  **[已弃用]**
* [Local Regression](https://github.com/JuliaStats/Loess.jl) - 局部回归，太流畅了！
* [Naive Bayes](https://github.com/nutsiepully/NaiveBayes.jl)  - Julia 中的简单朴素贝叶斯实现.  **[已弃用]**
* [Mixed Models](https://github.com/dmbates/MixedModels.jl) - 用于拟合（统计）混合效应模型的 Julia 包.
* [Simple MCMC](https://github.com/fredo-dedup/SimpleMCMC.jl)  - 在 Julia 中实现的基本 MCMC 采样器.  **[已弃用]**
* [Distances](https://github.com/JuliaStats/Distances.jl) - 用于距离评估的 Julia 模块.
* [Decision Tree](https://github.com/bensadeghi/DecisionTree.jl) - 决策树分类器和回归器.
* [Neural](https://github.com/compressed/BackpropNeuralNet.jl) - Julia 中的神经网络.
* [MCMC](https://github.com/doobwa/MCMC.jl)  - Julia 的 MCMC 工具.  **[已弃用]**
* [Mamba](https://github.com/brian-j-smith/Mamba.jl) - 用于 Julia 中贝叶斯分析的马尔可夫链蒙特卡罗 (MCMC).
* [GLM](https://github.com/JuliaStats/GLM.jl) - Julia 中的广义线性模型.
* [Gaussian Processes](https://github.com/STOR-i/GaussianProcesses.jl) - 用于高斯过程的 Julia 包.
* [Online Learning](https://github.com/lendle/OnlineLearning.jl) **[已弃用]**
* [GLMNet](https://github.com/simonster/GLMNet.jl) - Julia 包装器，用于使用 glmnet 拟合 Lasso/ElasticNet GLM 模型.
* [Clustering](https://github.com/JuliaStats/Clustering.jl) - 聚类数据的基本函数：k-means、dp-means等.
* [SVM](https://github.com/JuliaStats/SVM.jl)  - 朱莉娅的支持向量机.  **[已弃用]**
* [Kernel Density](https://github.com/JuliaStats/KernelDensity.jl) - Kernel density estimators for Julia.
* [MultivariateStats](https://github.com/JuliaStats/MultivariateStats.jl) - 降维方法.
* [NMF](https://github.com/JuliaStats/NMF.jl) - 用于非负矩阵分解的 Julia 包.
* [ANN](https://github.com/EricChiang/ANN.jl)  - 朱莉娅人工神经网络.  **[已弃用]**
* [Mocha](https://github.com/pluskid/Mocha.jl)  - 受 Caffe 启发的 Julia 深度学习框架.  **[已弃用]**
* [XGBoost](https://github.com/dmlc/XGBoost.jl) - Julia 中的 eXtreme 梯度提升包.
* [ManifoldLearning](https://github.com/wildart/ManifoldLearning.jl) - 用于流形学习和非线性降维的 Julia 包.
* [MXNet](https://github.com/apache/incubator-mxnet)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [Merlin](https://github.com/hshindo/Merlin.jl) - Julia 中灵活的深度学习框架.
* [ROCAnalysis](https://github.com/davidavdav/ROCAnalysis.jl) - 用于评估概率二元分类器的接收器操作特性和函数.
* [GaussianMixtures](https://github.com/davidavdav/GaussianMixtures.jl) - 大规模高斯混合模型.
* [ScikitLearn](https://github.com/cstjean/ScikitLearn.jl) - scikit-learn API 的 Julia 实现.
* [Knet](https://github.com/denizyuret/Knet.jl) - 科奇大学深度学习框架.
* [Flux](https://fluxml.ai/)  - 放松！  Flux 是不会让你张量的 ML 库
* [MLJ](https://github.com/alan-turing-institute/MLJ.jl) - Julia 机器学习框架.

<a name="julia-natural-language-processing"></a>
#### Natural Language Processing

* [Topic Models](https://github.com/slycoder/TopicModels.jl)  - Julia 的主题模型.  **[已弃用]**
* [Text Analysis](https://github.com/JuliaText/TextAnalysis.jl) - 用于文本分析的 Julia 包.
* [Word Tokenizers](https://github.com/JuliaText/WordTokenizers.jl) - Julia 中自然语言处理的分词器
* [Corpus Loaders](https://github.com/JuliaText/CorpusLoaders.jl) - 一个 Julia 包，为各种 NLP 语料库提供各种加载器.
* [Embeddings](https://github.com/JuliaText/Embeddings.jl) - 用于加载各种词嵌入的函数和数据依赖性
* [Languages](https://github.com/JuliaText/Languages.jl) - 用于处理各种人类语言的 Julia 包
* [WordNet](https://github.com/JuliaText/WordNet.jl) - 普林斯顿 WordNet 的 Julia 包

<a name="julia-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [Graph Layout](https://github.com/IainNZ/GraphLayout.jl) - 纯 Julia 中的图形布局算法.
* [LightGraphs](https://github.com/JuliaGraphs/LightGraphs.jl) - 图形建模和分析.
* [Data Frames Meta](https://github.com/JuliaData/DataFramesMeta.jl) - DataFrame 的元编程工具.
* [Julia Data](https://github.com/nfoti/JuliaData)  - 用于在 Julia 中处理表格数据的库.  **[已弃用]**
* [Data Read](https://github.com/queryverse/ReadStat.jl) - 从 Stata、SAS 和 SPSS 读取文件.
* [Hypothesis Tests](https://github.com/JuliaStats/HypothesisTests.jl) - 朱莉娅的假设检验.
* [Gadfly](https://github.com/GiovineItalia/Gadfly.jl) - 朱莉娅巧妙的统计图表.
* [Stats](https://github.com/JuliaStats/StatsKit.jl) - 朱莉娅的统计测试.
* [RDataSets](https://github.com/johnmyleswhite/RDatasets.jl) - 用于加载 R 中可用的许多数据集的 Julia 包.
* [DataFrames](https://github.com/JuliaData/DataFrames.jl) - 用于在 Julia 中处理表格数据的库.
* [Distributions](https://github.com/JuliaStats/Distributions.jl) - 用于概率分布和相关函数的 Julia 包.
* [Data Arrays](https://github.com/JuliaStats/DataArrays.jl)  - 允许缺失值的数据结构.  **[已弃用]**
* [Time Series](https://github.com/JuliaStats/TimeSeries.jl) - Julia 的时间序列工具包.
* [Sampling](https://github.com/lindahua/Sampling.jl) - Julia 的基本采样算法.

<a name="julia-misc-stuff--presentations"></a>
#### Misc Stuff / Presentations

* [DSP](https://github.com/JuliaDSP/DSP.jl) - 数字信号处理（滤波、周期图、频谱图、窗函数）.
* [JuliaCon Presentations](https://github.com/JuliaCon/presentations) - JuliaCon 的演示.
* [SignalProcessing](https://github.com/JuliaDSP/DSP.jl) - Julia 的信号处理工具.
* [Images](https://github.com/JuliaImages/Images.jl) - 朱莉娅的图像库.
* [DataDeps](https://github.com/oxinabox/DataDeps.jl) - 用于可重复科学的可重复数据设置.

<a name="kotlin"></a>
## Kotlin

<a name="kotlin-deep-learning"></a>
#### Deep Learning
* [KotlinDL](https://github.com/JetBrains/KotlinDL) - 用 Kotlin 编写的深度学习框架.

<a name="lua"></a>
## Lua

<a name="lua-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Torch7](http://torch.ch/)
  * [cephes](https://github.com/deepmind/torch-cephes)  - Cephes 数学函数库，为 Torch 包装. 提供并封装了由 Stephen L. Moshier 开发的 Cephes 数学库中的 180 多个特殊数学函数. 它被用于 SciPy 的核心以及许多其他地方.  **[已弃用]**
  * [autograd](https://github.com/twitter/torch-autograd)  - Autograd 自动区分原生 Torch 代码. 受到原始 Python 版本的启发.
  * [graph](https://github.com/torch/graph)  - Torch 的图形包.  **[已弃用]**
  * [randomkit](https://github.com/deepmind/torch-randomkit)  - Numpy 的 randomkit，为 Torch 封装.  **[已弃用]**
  * [signal](https://github.com/soumith/torch-signal)  - Torch-7 的信号处理工具箱.  FFT、DCT、希尔伯特、倒谱、stft.
  * [nn](https://github.com/torch/nn) - Torch 的神经网络包.
  * [torchnet](https://github.com/torchnet/torchnet) - torch 框架提供了一组抽象，旨在鼓励代码重用以及鼓励模块化编程.
  * [nngraph](https://github.com/torch/nngraph) - 该软件包为 Torch7 中的 nn 库提供图形计算.
  * [nnx](https://github.com/clementfarabet/lua---nnx) - 一个完全不稳定的实验性软件包，扩展了 Torch 的内置 nn 库.
  * [rnn](https://github.com/Element-Research/rnn)  - 一个循环神经网络库，扩展了 Torch 的 nn.  RNN、LSTM、GRU、BRNN、BLSTM 等
  * [dpnn](https://github.com/Element-Research/dpnn) - 许多有用的功能不属于主要的 nn 包.
  * [dp](https://github.com/nicholas-leonard/dp)  - 一个深度学习库，旨在使用 Torch7 发行版简化研究和开发. 它通过优雅地使用面向对象的设计模式来强调灵活性.  **[已弃用]**
  * [optim](https://github.com/torch/optim)  - Torch 的优化库.  SGD、Adagrad、共轭梯度、LBFGS、RProp 等.
  * [unsup](https://github.com/koraykv/unsup)  - Torch 中无监督学习的包. 提供与 nn 兼容的模块（LinearPsd、ConvPsd、AutoEncoder...）和独立算法（k-means、PCA）.  **[已弃用]**
  * [manifold](https://github.com/clementfarabet/manifold) - 操纵流形的包.
  * [svm](https://github.com/koraykv/torch-svm)  - Torch-SVM 库.  **[已弃用]**
  * [lbfgs](https://github.com/clementfarabet/lbfgs)  - liblbfgs 的 FFI 包装.  **[已弃用]**
  * [vowpalwabbit](https://github.com/clementfarabet/vowpal_wabbit)  - 一个旧的 vowpalwabbit 火炬接口.  **[已弃用]**
  * [OpenGM](https://github.com/clementfarabet/lua---opengm)  - OpenGM 是一个用于图形建模和推理的 C++ 库.  Lua 绑定提供了一种从 Lua 描述图形的简单方法，然后使用 OpenGM 对其进行优化.  **[已弃用]**
  * [spaghetti](https://github.com/MichaelMathieu/lua---spaghetti) - @MichaelMathieu 用于 torch7 的 Spaghetti（稀疏线性）模块 **[已弃用]**
  * [LuaSHKit](https://github.com/ocallaco/LuaSHkit) - 局部敏感哈希库 SHKit 的 Lua 包装器 **[已弃用]**
  * [kernel smoothing](https://github.com/rlowrance/kernel-smoothers)  - KNN，核加权平均值，局部线性回归平滑器.  **[已弃用]**
  * [cutorch](https://github.com/torch/cutorch) - 火炬 CUDA 实施.
  * [cunn](https://github.com/torch/cunn) - Torch CUDA 神经网络实现.
  * [imgraph](https://github.com/clementfarabet/lua---imgraph)  - Torch 的图像/图形库. 该包提供了在图像上构建图形、对它们进行分割、从中构建树以及将它们转换回图像的例程.  **[已弃用]**
  * [videograph](https://github.com/clementfarabet/videograph)  - Torch 的视频/图形库. 该包提供了在视频上构建图表、对其进行分段、从中构建树并将其转换回视频的例程.  **[已弃用]**
  * [saliency](https://github.com/marcoscoffier/torch-saliency)  - 围绕积分图像的代码和工具. 一个基于快速积分直方图查找兴趣点的库.  **[已弃用]**
  * [stitch](https://github.com/marcoscoffier/lua---stitch)  - 允许我们使用 Hugin 来拼接图像并将相同的拼接应用于视频序列.  **[已弃用]**
  * [sfm](https://github.com/marcoscoffier/lua---sfm)  - 来自运动包的捆绑调整/结构.  **[已弃用]**
  * [fex](https://github.com/koraykv/fex)  - Torch 中的特征提取包. 提供SIFT和dSIFT模块.  **[已弃用]**
  * [OverFeat](https://github.com/sermanet/OverFeat)  - 最先进的通用密集特征提取器.  **[已弃用]**
  * [wav2letter](https://github.com/facebookresearch/wav2letter) - 来自 Facebook AI Research 的简单高效的端到端自动语音识别 (ASR) 系统.
* [Numeric Lua](http://numlua.luaforge.net/)
* [Lunatic Python](https://labix.org/lunatic-python)
* [SciLua](http://scilua.org/)
* [Lua - Numerical Algorithms](https://bitbucket.org/lucashnegri/lna) **[已弃用]**
* [Lunum](https://github.com/jzrake/lunum) **[已弃用]**
* [Keras GPT Copilot](https://github.com/fabprezja/keras-gpt-copilot) - 一个 python 包，将 LLM copilot 集成到 keras 模型开发工作流程中.

<a name="lua-demos-and-scripts"></a>
#### Demos and Scripts
* [Core torch7 demos repository](https://github.com/e-lab/torch7-demos).
  * 线性回归、逻辑回归
  * 人脸检测器（训练和检测作为单独的演示）
  * 基于 mst 的分段器
  * 训练数字分类器
  * 训练自动编码器
  * 光流演示
  * 火车门牌号码
  * 西法尔火车
  * 深度网络跟踪
  * kinect演示
  * 滤波器组可视化
  * 显着性网络
* [Training a Convnet for the Galaxy-Zoo Kaggle challenge(CUDA demo)](https://github.com/soumith/galaxyzoo)
* [torch-datasets](https://github.com/rosejn/torch-datasets) - 用于加载多个流行数据集的脚本，包括：
  * BSR 500
  * CIFAR-10
  * 线圈
  * 街景门牌号
  * 国家标准技术研究所
  * 诺布
* [Atari2600](https://github.com/fidlej/aledataset) - 用于从 Arcade 学习环境生成包含静态帧的数据集的脚本.



<a name="matlab"></a>
## Matlab

<a name="matlab-computer-vision"></a>
#### Computer Vision

* [Contourlets](http://www.ifp.illinois.edu/~minhdo/software/contourlet_toolbox.tar) - 实现轮廓波变换及其实用函数的 MATLAB 源代码.
* [Shearlets](https://www3.math.tu-berlin.de/numerik/www.shearlab.org/software) - 用于剪切波变换的 MATLAB 代码.
* [Curvelets](http://www.curvelet.org/software.html) - Curvelet 变换是小波变换的高维推广，旨在表示不同尺度和不同角度的图像.
* [Bandlets](http://www.cmap.polytechnique.fr/~peyre/download/) - Bandlet 变换的 MATLAB 代码.
* [mexopencv](https://kyamagu.github.io/mexopencv/) - OpenCV 库的 MATLAB mex 函数集合和开发套件.

<a name="matlab-natural-language-processing"></a>
#### Natural Language Processing

* [NLP](https://amplab.cs.berkeley.edu/an-nlp-library-for-matlab/) - Matlab 的 NLP 库.

<a name="matlab-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [训练深度自动编码器或分类器
在 MNIST 数字上](https://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html) - 训练深度自动编码器或分类器
MNIST 数字[深度学习].
* [Convolutional-Recursive Deep Learning for 3D Object Classification](https://www.socher.org/index.php/Main/Convolutional-RecursiveDeepLearningFor3DObjectClassification) - 用于 3D 对象分类的卷积递归深度学习[深度学习].
* [Spider](https://people.kyb.tuebingen.mpg.de/spider/) - Spider 旨在成为 Matlab 中机器学习的完整面向对象环境.
* [LibSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/#matlab) - 支持向量机库.
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) - GPU 和 CPU 上的开源 SVM 库
* [LibLinear](https://www.csie.ntu.edu.tw/~cjlin/liblinear/#download) - 大型线性分类库.
* [Machine Learning Module](https://github.com/josephmisiti/machine-learning-module) - 机器上的课程，包含 PDF、讲座、代码
* [Caffe](https://github.com/BVLC/caffe) - 开发时考虑到清洁性、可读性和速度的深度学习框架.
* [Pattern Recognition Toolbox](https://github.com/covartech/PRT) - Matlab 中完整的面向对象的机器学习环境.
* [Pattern Recognition and Machine Learning](https://github.com/PRML/PRMLT) - 该软件包包含 C. Bishop 所著的《模式识别和机器学习》一书中描述的算法的 matlab 实现.
* [Optunity](https://optunity.readthedocs.io/en/latest/)  - 一个致力于自动超参数优化的库，具有简单、轻量级的 API，以方便网格搜索的直接替换.  Optunity 用 Python 编写，但与 MATLAB 无缝连接.
* [MXNet](https://github.com/apache/incubator-mxnet/)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [Machine Learning in MatLab/Octave](https://github.com/trekhleb/machine-learning-octave) - 流行的机器学习算法（神经网络、线性/逻辑回归、K-Means 等）的示例，并解释了它们背后的代码示例和数学.


<a name="matlab-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [ParaMonte](https://github.com/cdslaborg/paramonte)  - 通用 MATLAB 库，用于通过串行/并行蒙特卡洛和 MCMC 模拟进行贝叶斯数据分析和可视化. 文档可以找到 [here](https://www.cdslab.org/paramonte/).
* [matlab_bgl](https://www.cs.purdue.edu/homes/dgleich/packages/matlab_bgl/) - MatlabBGL 是一个用于处理图形的 Matlab 软件包.
* [gaimc](https://www.mathworks.com/matlabcentral/fileexchange/24134-gaimc---graph-algorithms-in-matlab-code) - 高效的纯 Matlab 图形算法实现，以补充 MatlabBGL 的 mex 函数.

<a name="net"></a>
## .NET

<a name="net-computer-vision"></a>
#### Computer Vision

* [OpenCVDotNet](https://code.google.com/archive/p/opencvdotnet) - 与 .NET 应用程序一起使用的 OpenCV 项目的包装器.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - OpenCV 的跨平台包装器，可以在 Mono 中编译，以便在 Windows、Linus、Mac OS X、iOS 和 Android 上运行.
* [AForge.NET](http://www.aforgenet.com/framework/) - Open source C# framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence. Development has now shifted to GitHub.
* [Accord.NET](http://accord-framework.net)  - 该库与 AForge.NET 一起，可以为 Windows、Windows RT 和 Windows Phone 提供图像处理和计算机视觉算法. 一些组件也可用于 Java 和 Android.

<a name="net-natural-language-processing"></a>
#### Natural Language Processing

* [Stanford.NLP for .NET](https://github.com/sergey-tihon/Stanford.NLP.NET/) - 将斯坦福 NLP 包完整移植到 .NET，并且还可以预编译为 NuGet 包.

<a name="net-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Accord-Framework](http://accord-framework.net/) - Accord.NET Framework 是一个用于构建机器学习、计算机视觉、计算机试听、信号处理和统计应用程序的完整框架.
* [Accord.MachineLearning](https://www.nuget.org/packages/Accord.MachineLearning/)  - 支持向量机、决策树、朴素贝叶斯模型、K 均值、高斯混合模型和通用算法，例如用于机器学习应用的 Ransac、交叉验证和网格搜索. 该包是 Accord.NET Framework 的一部分.
* [DiffSharp](https://diffsharp.github.io/DiffSharp/)  - 一个自动微分 (AD) 库，为机器学习和优化应用提供精确且高效的导数（梯度、Hessian、Jacobian、方向导数以及无矩阵 Hessian 和 Jacobian 向量积）. 操作可以嵌套到任何级别，这意味着您可以计算精确的高阶导数，并对内部利用微分的函数进行微分，适用于超参数优化等应用.
* [Encog](https://www.nuget.org/packages/encog-dotnet-core/)  - 先进的神经网络和机器学习框架.  Encog 包含用于创建各种网络的类，以及用于标准化和处理这些神经网络数据的支持类.  Encog 使用多线程弹性传播进行训练.  Encog 还可以利用 GPU 进一步加快处理时间. 还提供基于 GUI 的工作台来帮助建模和训练神经网络.
* [GeneticSharp](https://github.com/giacomelli/GeneticSharp)  - 适用于.NET Core 和.NET Framework 的多平台遗传算法库. 该库有多种 GA 算子的实现，例如：选择、交叉、变异、重新插入和终止.
* [Infer.NET](https://dotnet.github.io/infer/)  - Infer.NET 是一个用于在图形模型中运行贝叶斯推理的框架. 人们可以使用 Infer.NET 来解决许多不同类型的机器学习问题，从分类、推荐或聚类等标准问题到特定领域问题的定制解决方案.  Infer.NET 已广泛应用于信息检索、生物信息学、流行病学、视觉等领域.
* [ML.NET](https://github.com/dotnet/machinelearning)  - ML.NET 是一个跨平台开源机器学习框架，使 .NET 开发人员可以使用机器学习.  ML.NET 最初由 Microsoft Research 开发，在过去十年中发展成为一个重要的框架，并在 Microsoft 的许多产品组中使用，例如 Windows、Bing、PowerPoint、Excel 等.
* [Neural Network Designer](https://sourceforge.net/projects/nnd/)  - DBMS 管理系统和神经网络设计器. 设计器应用程序是使用 WPF 开发的，它是一个用户界面，允许您设计神经网络、查询网络、创建和配置能够提出问题并从您的反馈中学习的聊天机器人. 聊天机器人甚至可以在互联网上抓取信息，以返回其输出并用于学习.
* [Synapses](https://github.com/mrdimosthenis/Synapses) - Neural network library in F#.
* [Vulpes](https://github.com/fsprojects/Vulpes) - Deep belief and deep learning implementation written in F# and leverages CUDA GPU execution with Alea.cuBase.
* [MxNet.Sharp](https://github.com/tech-quantum/MxNet.Sharp) - .NET Standard bindings for Apache MxNet with Imperative, Symbolic and Gluon Interface for developing, training and deploying Machine Learning models in C#. https://mxnet.tech-quantum.com/

<a name="net-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [numl](https://www.nuget.org/packages/numl/) -numl 是一个机器学习库，旨在简化使用标准建模技术进行预测和聚类的使用.
* [Math.NET Numerics](https://www.nuget.org/packages/MathNet.Numerics/)  - Math.NET 项目的数值基础，旨在为科学、工程和日常使用中的数值计算提供方法和算法. 支持 Windows、Linux 和 Mac 上的 .Net 4.0、.Net 3.5 和 Mono；  Silverlight 5、WindowsPhone/SL 8、WindowsPhone 8.1 和 Windows 8（带 PCL 便携式配置文件 47 和 344）；  Android/iOS 与 Xamarin.
* [Sho](https://www.microsoft.com/en-us/research/project/sho-the-net-playground-for-data/)  - Sho 是一个用于数据分析和科学计算的交互式环境，可让您将脚本（IronPython 中）与编译代码（.NET 中）无缝连接，以实现快速灵活的原型设计. 该环境包括强大而高效的线性代数库以及可从任何 .NET 语言使用的数据可视化，以及用于快速开发的功能丰富的交互式 shell.

<a name="objective-c"></a>
## Objective C

<a name="objective-c-general-purpose-machine-learning"></a>
### General-Purpose Machine Learning

* [YCML](https://github.com/yconst/YCML) - 适用于 Objective-C 和 Swift (OS X / iOS) 的机器学习框架.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet)  - 适用于 iOS 和 Mac OS X 的快速多层感知器神经网络库.MLPNeuralNet 通过经过训练的神经网络预测新示例. 它构建在 Apple 的加速框架之上，使用矢量化操作和硬件加速（如果可用）.  **[已弃用]**
* [MAChineLearning](https://github.com/gianlucabertani/MAChineLearning)  - Objective-C 多层感知器库，全面支持反向传播训练. 它使用 vDSP 和 vecLib 实现，比 Java 同类产品快 20 倍. 包括供 Swift 使用的示例代码.
* [BPN-NeuralNetwork](https://github.com/Kalvar/ios-BPN-NeuralNetwork)  - 它实现了 3 层神经网络（输入层、隐藏层和输出层），并被命名为反向传播神经网络 (BPN). 该网络可用于产品推荐、用户行为分析、数据挖掘和数据分析.  **[已弃用]**
* [Multi-Perceptron-NeuralNetwork](https://github.com/Kalvar/ios-Multi-Perceptron-NeuralNetwork) - 它实现了基于反向传播神经网络（BPN）的多感知器神经网络，并设计了无限隐藏层.
* [KRHebbian-Algorithm](https://github.com/Kalvar/ios-KRHebbian-Algorithm)  - 它是机器学习神经网络中的无监督自学习算法（调整权重）.  **[已弃用]**
* [KRKmeans-Algorithm](https://github.com/Kalvar/ios-KRKmeans-Algorithm)  - 它实现了 K-Means 聚类和分类算法. 它可用于数据挖掘和图像压缩.  **[已弃用]**
* [KRFuzzyCMeans-Algorithm](https://github.com/Kalvar/ios-KRFuzzyCMeans-Algorithm)  - 它实现了 Fuzzy C-Means (FCM)，即机器学习上的模糊聚类/分类算法. 它可用于数据挖掘和图像压缩.  **[已弃用]**

<a name="ocaml"></a>
## OCaml

<a name="ocaml-general-purpose-machine-learning"></a>
### General-Purpose Machine Learning

* [Oml](https://github.com/rleonid/oml) - 通用统计和机器学习库.
* [GPR](https://mmottl.github.io/gpr/) - OCaml 中的高效高斯过程回归.
* [Libra-Tk](https://libra.cs.uoregon.edu) - 使用离散概率模型进行学习和推理的算法.
* [TensorFlow](https://github.com/LaurentMazare/tensorflow-ocaml) - TensorFlow 的 OCaml 绑定.

<a name="opencv"></a>
## OpenCV

<a name="opencv-ComputerVision and Text Detection"></a>
### OpenSource-Computer-Vision

* [OpenCV](https://github.com/opencv/opencv) - 开源计算机视觉库

<a name="perl"></a>
## Perl

<a name="perl-data-analysis--data-visualization"></a>
### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning)，一种用于数据和图像处理的可插拔架构，可以
be [used for machine learning](https://github.com/zenogantner/PDL-ML).

<a name="perl-general-purpose-machine-learning"></a>
### General-Purpose Machine Learning

* [MXnet for Deep Learning, in Perl](https://github.com/apache/incubator-mxnet/tree/master/perl-package),
also [released in CPAN](https://metacpan.org/pod/AI::MXNet).
* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
使用 Perl 的 AWS 机器学习平台.
* [Algorithm::SVMLight](https://metacpan.org/pod/Algorithm::SVMLight),
  支持向量机及其下的 SVMLight 的实现.  **[已弃用]**
* 多种机器学习和人工智能模型
  包含在 [`AI`](https://metacpan.org/search?size=20&q=AI)
  命名空间. 例如，您可以
  寻找 [Naïve Bayes](https://metacpan.org/pod/AI::NaiveBayes).

<a name="perl6"></a>
## Perl 6

* [Support Vector Machines](https://github.com/titsuki/p6-Algorithm-LibSVM)
* [Naïve Bayes](https://github.com/titsuki/p6-Algorithm-NaiveBayes)

<a name="perl-6-data-analysis--data-visualization"></a>
### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
用于数据和图像处理的可插拔架构，可以
be
[used for machine learning](https://github.com/zenogantner/PDL-ML).

<a name="perl-6-general-purpose-machine-learning"></a>
### General-Purpose Machine Learning

<a name="php"></a>
## PHP

<a name="php-natural-language-processing"></a>
### Natural Language Processing

* [jieba-php](https://github.com/fukuball/jieba-php) - 中文分词实用程序.

<a name="php-general-purpose-machine-learning"></a>
### General-Purpose Machine Learning

* [PHP-ML](https://gitlab.com/php-ai/php-ml)  - PHP 机器学习库. 算法、交叉验证、神经网络、预处理、特征提取等尽在一个库中.
* [PredictionBuilder](https://github.com/denissimon/prediction-builder) - 使用线性回归构建预测的机器学习库.
* [Rubix ML](https://github.com/RubixML) - 高级机器学习 (ML) 库，可让您构建使用 PHP 语言从数据中学习的程序.
* [19 Questions](https://github.com/fulldecent/19-questions) - 机器学习/贝叶斯推理为对象分配属性.

<a name="python"></a>
## Python

<a name="python-computer-vision"></a>
#### Computer Vision

* [Scikit-Image](https://github.com/scikit-image/scikit-image) - Python 中图像处理算法的集合.
* [Scikit-Opt](https://github.com/guofei9987/scikit-opt) - Python中的群体智能（Python中的遗传算法、粒子群优化、模拟退火、蚁群算法、免疫算法、人工鱼群算法）
* [SimpleCV](http://simplecv.org/)  - 一个开源计算机视觉框架，可以访问多个高性能计算机视觉库，例如 OpenCV. 用 Python 编写，可在 Mac、Windows 和 Ubuntu Linux 上运行.
* [Vigranumpy](https://github.com/ukoethe/vigra) - VIGRA C++ 计算机视觉库的 Python 绑定.
* [OpenFace](https://cmusatyalab.github.io/openface/) - 使用深度神经网络的免费开源人脸识别.
* [PCV](https://github.com/jesolem/PCV)  - 用于计算机视觉的开源 Python 模块.  **[已弃用]**
* [face_recognition](https://github.com/ageitgey/face_recognition) - 人脸识别库，可从 Python 或命令行识别和操作人脸.
* [deepface](https://github.com/serengil/deepface) - Python的轻量级人脸识别和人脸属性分析（年龄、性别、情感和种族）框架，涵盖VGG-Face、FaceNet、OpenFace、DeepFace、DeepID、Dlib和ArcFace等前沿模型.
* [retinaface](https://github.com/serengil/retinaface) - 基于深度学习的 Python 尖端面部检测器，带有面部标志
* [dockerface](https://github.com/natanielruiz/dockerface)  - 易于安装和使用深度学习 Faster R-CNN 人脸检测，用于 Docker 容器中的图像和视频.  **[已弃用]**
* [Detectron](https://github.com/facebookresearch/Detectron)  - FAIR 的软件系统实现了最先进的目标检测算法，包括 Mask R-CNN. 它是用 Python 编写的，由 Caffe2 深度学习框架提供支持.  **[已弃用]**
* [detectron2](https://github.com/facebookresearch/detectron2)  - FAIR 的下一代对象检测和分割研究平台. 它是对之前版本 Detectron 的彻底重写，并由 PyTorch 深度学习框架提供支持.
* [albumentations](https://github.com/albu/albumentations)  - 快速且与框架无关的图像增强库，实现了多种增强技术. 支持开箱即用的分类、分割、检测. 用于赢得 Kaggle、Topcoder 以及 CVPR 研讨会的多项深度学习竞赛.
* [pytessarct](https://github.com/madmaze/pytesseract)  - Python-tesseract 是Python 的光学字符识别（OCR）工具. 也就是说，它将识别并“读取”图像中嵌入的文本.  Python-tesseract 是一个包装器 [Google's Tesseract-OCR Engine](https://github.com/tesseract-ocr/tesseract).
* [imutils](https://github.com/jrosebr1/imutils) - 一个包含便利函数的库，可使用 OpenCV 和 Python 更轻松地进行基本图像处理操作，例如平移、旋转、调整大小、骨架化和显示 Matplotlib 图像.
* [PyTorchCV](https://github.com/donnyyou/PyTorchCV) - 基于 PyTorch 的计算机视觉深度学习框架.
* [joliGEN](https://github.com/jolibrain/joliGEN) - 具有 GAN 和扩散功能的生成 AI 图像工具集，适用于实际应用.
* [Self-supervised learning](https://pytorch-lightning-bolts.readthedocs.io/en/latest/self_supervised_models.html)
* [neural-style-pt](https://github.com/ProGamerGov/neural-style-pt) - Justin Johnson 神经风格（神经风格迁移）的 PyTorch 实现.
* [Detecto](https://github.com/alankbi/detecto) - 使用 5-10 行代码训练并运行计算机视觉模型.
* [neural-dream](https://github.com/ProGamerGov/neural-dream) - DeepDream 的 PyTorch 实现.
* [Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - 实时多人关键点检测库，用于身体、面部、手部和脚部估计
* [Deep High-Resolution-Net](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch) - CVPR2019 论文“Deep High-Resolution Representation Learning for Human Pose Estimation”的 PyTorch 实现
* [dream-creator](https://github.com/ProGamerGov/dream-creator)  - DeepDream 的 PyTorch 实现. 允许个人使用 DeepDream 的自定义数据集快速轻松地训练自己的自定义 GoogleNet 模型.
* [Lucent](https://github.com/greentfrapp/lucent) - Tensorflow and OpenAI Clarity's Lucid adapted for PyTorch.
* [lightly](https://github.com/lightly-ai/lightly) - Lightly 是一个用于自我监督学习的计算机视觉框架.
* [Learnergy](https://github.com/gugarosa/learnergy) - 基于 PyTorch 构建的基于能量的机器学习模型.
* [OpenVisionAPI](https://github.com/openvisionapi) - 基于开源模型的开源计算机视觉 API.
* [IoT Owl](https://github.com/Ret2Me/IoT-Owl) - 具有巨大可能性的轻型人脸检测和识别系统，基于 Microsoft Face API 和 TensorFlow，专为树莓派等小型物联网设备而设计.
* [Exadel CompreFace](https://github.com/exadel-inc/CompreFace)  - 人脸识别系统可以轻松集成到任何系统中，无需具备机器学习技能.  CompreFace 提供用于人脸识别、人脸验证、人脸检测、口罩检测、地标检测、年龄和性别识别的 REST API，并且可以通过 docker 轻松部署.
* [computer-vision-in-action](https://github.com/Charmve/computer-vision-in-action)  - 简称“L0CV”，是新一代计算机视觉开源在线学习媒体，集图文、源码、HTML于一体的跨平台互动学习框架.  L0CV 生态系统——笔记本、数据集、源代码，从深入到高级——以及 L0CV 中心.
* [timm](https://github.com/rwightman/pytorch-image-models) - PyTorch 图像模型、脚本、预训练权重 - ResNet、ResNeXT、EfficientNet、EfficientNetV2、NFNet、Vision Transformer、MixNet、MobileNet-V3/V2、RegNet、DPN、CSPNet 等.

<a name="python-natural-language-processing"></a>
#### Natural Language Processing

* [pkuseg-python](https://github.com/lancopku/pkuseg-python) - 更好的结巴版本，由北京大学开发.
* [NLTK](https://www.nltk.org/) - 用于构建 Python 程序以处理人类语言数据的领先平台.
* [Pattern](https://github.com/clips/pattern)  - Python 编程语言的网络挖掘模块. 它拥有用于自然语言处理、机器学习等的工具.
* [Quepy](https://github.com/machinalis/quepy) - 一个Python框架，用于将自然语言问题转换为数据库查询语言中的查询.
* [TextBlob](http://textblob.readthedocs.io/en/dev/)  - 提供一致的 API，用于深入研究常见的自然语言处理 (NLP) 任务. 站在NLTK和Pattern的巨人肩膀上，并且与两者配合得很好.
* [YAlign](https://github.com/machinalis/yalign)  - 句子对齐器，一个从可比语料库中提取平行句子的友好工具.  **[已弃用]**
* [jieba](https://github.com/fxsjy/jieba#jieba-1) - 中文分词实用程序.
* [SnowNLP](https://github.com/isnowfy/snownlp) - 一个用于处理中文文本的库.
* [spammy](https://github.com/tasdikrahman/spammy) - 基于 NLTK 构建的电子邮件垃圾邮件过滤库
* [loso](https://github.com/fangpenlin/loso)  - 另一个中文分词库.  **[已弃用]**
* [genius](https://github.com/duanhongyi/genius) - 基于条件随机场的中文片段.
* [KoNLPy](http://konlpy.org) - 用于韩语自然语言处理的 Python 包.
* [nut](https://github.com/pprett/nut)  - 自然语言理解工具包.  **[已弃用]**
* [Rosetta](https://github.com/columbia-applied-data-science/rosetta) - 文本处理工具和包装器（例如Vowpal Wabbit）
* [BLLIP Parser](https://pypi.org/project/bllipparser/)  - BLLIP 自然语言解析器（也称为 Charniak-Johnson 解析器）的 Python 绑定.  **[已弃用]**
* [PyNLPl](https://github.com/proycon/pynlpl)  - Python 自然语言处理库.  Python 通用 NLP 库. 还包含一些用于解析常见 NLP 格式的特定模块，尤其是 [FoLiA](https://proycon.github.io/folia/)，还有 ARPA 语言模型、Moses 短语表、GIZA++ 对齐.
* [PySS3](https://github.com/sergioburdisso/pyss3)  - Python 包，实现了一种用于文本分类的新型白盒机器学习模型，称为 SS3. 由于 SS3 能够直观地解释其原理，因此该软件包还附带易于使用的交互式可视化工具（[online demos](http://tworld.io/ss3/)).
* [python-ucto](https://github.com/proycon/python-ucto) - Python 绑定到 ucto（适用于各种语言的 unicode 感知、基于规则的标记生成器）.
* [python-frog](https://github.com/proycon/python-frog)  - Python 与 Frog 的绑定，Frog 是荷兰语的 NLP 套件.  （词性标记、词形还原、依存分析、NER）
* [python-zpar](https://github.com/EducationalTestingService/python-zpar) - Python 绑定 [ZPar](https://github.com/frcchang/zpar)，一个统计词性标注器、选区解析器和英语依存解析器.
* [colibri-core](https://github.com/proycon/colibri-core) - Python 绑定到 C++ 库，用于以快速且节省内存的方式提取和使用基本语言结构，例如 n-gram 和 Skipgram.
* [spaCy](https://github.com/explosion/spaCy) - 使用 Python 和 Cython 进行工业级 NLP.
* [PyStanfordDependencies](https://github.com/dmcc/PyStanfordDependencies) - 用于将 Penn Treebank 树转换为斯坦福依赖项的 Python 接口.
* [Distance](https://github.com/doukremt/distance)  - 编辑和汉明距离计算.  **[已弃用]**
* [Fuzzy Wuzzy](https://github.com/seatgeek/fuzzywuzzy) - Python 中的模糊字符串匹配.
* [jellyfish](https://github.com/jamesturk/jellyfish) - 一个用于对字符串进行近似和语音匹配的 python 库.
* [editdistance](https://pypi.org/project/editdistance/) - 快速实现编辑距离.
* [textacy](https://github.com/chartbeat-labs/textacy) - 基于 Spacy 构建的更高级别的 NLP.
* [stanford-corenlp-python](https://github.com/dasmith/stanford-corenlp-python) - Python 包装器 [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) **[已弃用]**
* [CLTK](https://github.com/cltk/cltk) - 古典语言工具包.
* [Rasa](https://github.com/RasaHQ/rasa) - “用于自动化基于文本和语音的对话的机器学习框架.”
* [yase](https://github.com/PPACI/yase) - 将句子（或其他序列）转码为词向量列表.
* [Polyglot](https://github.com/aboSamoor/polyglot) - 多语言文本（NLP）处理工具包.
* [DrQA](https://github.com/facebookresearch/DrQA) - 阅读维基百科来回答开放域问题.
* [Dedupe](https://github.com/dedupeio/dedupe) - 用于精确且可扩展的模糊匹配、记录重复删除和实体解析的 Python 库.
* [Snips NLU](https://github.com/snipsco/snips-nlu) - 用于意图分类和实体提取的自然语言理解库
* [NeuroNER](https://github.com/Franck-Dernoncourt/NeuroNER) - 使用神经网络进行命名实体识别，提供最先进的结果
* [DeepPavlov](https://github.com/deepmipt/DeepPavlov/) - 对话式 AI 库，包含许多预先训练的俄罗斯 NLP 模型.
* [BigARTM](https://github.com/bigartm/bigartm) - 主题建模平台.
* [NALP](https://github.com/gugarosa/nalp) - 基于 Tensorflow 构建的自然对抗语言处理框架.
* [DL Translate](https://github.com/xhlulu/dl-translate) - 一个基于深度学习的 50 种语言之间的翻译库，使用“transformers”构建.
* [Haystack](https://github.com/deepset-ai/haystack) - 使用 Transformer 模型和法学硕士构建工业强度应用程序的框架.

<a name="python-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

 * [Aim](https://github.com/aimhubio/aim) -&gt; 易于使用且功能强大的开源 AI 元数据跟踪器.
 * [RexMex](https://github.com/AstraZeneca/rexmex) -&gt; 用于公平评估的通用推荐指标库.
 * [ChemicalX](https://github.com/AstraZeneca/chemicalx) -&gt; 基于 PyTorch 的深度学习库，用于药物对评分
 * [Microsoft ML for Apache Spark](https://github.com/Azure/mmlspark) -&gt; 分布式机器学习框架 Apache Spark
 * [Shapley](https://github.com/benedekrozemberczki/shapley) -&gt; 一个数据驱动的框架，用于量化机器学习集成中分类器的价值.
 * [igel](https://github.com/nidhaloff/igel) -&gt; 一个令人愉快的机器学习工具，允许您训练/拟合、测试和使用模型**无需编写代码**
 * [ML Model building](https://github.com/Shanky-21/Machine_learning) -&gt; 一个包含分类、聚类、回归、推荐笔记本的存储库，并附有制作它们的插图.
 * [ML/DL project template](https://github.com/PyTorchLightning/deep-learning-project-template)
 * [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) -&gt; PyTorch Geometric 的时间扩展，用于动态图表示学习.
 * [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur) -&gt; NetworkX 的图形采样扩展库，具有类似 Scikit-Learn 的 API.
 * [Karate Club](https://github.com/benedekrozemberczki/karateclub) -&gt; NetworkX 的无监督机器学习扩展库，具有类似 Scikit-Learn 的 API.
* [Auto_ViML](https://github.com/AutoViML/Auto_ViML)  -&gt; 快速自动构建变体可解释的 ML 模型！  Auto_ViML 发音为“auto vimal”，是一个全面且可扩展的 Python AutoML 工具包，具有不平衡处理、集成、堆叠和内置特征选择功能. 精选于<a href="https://towardsdatascience.com/why-automl-is-an-essential-new-tool-for-data-scientists-2d9ab4e25e46?source=friends_link&sk=d03a0cc55c23deb497d546d6b9be0653">Medium 文章</a>.
* [PyOD](https://github.com/yzhao062/pyod)  -&gt; Python 离群值检测，全面且可扩展的 Python 工具包，用于检测多变量数据中的离群对象. 适用于高级模型，包括神经网络/深度学习和异常值集成.
* [steppy](https://github.com/neptune-ml/steppy)  -&gt; 轻量级 Python 库，用于快速且可重复的机器学习实验. 引入了一个非常简单的界面，可以实现干净的机器学习管道设计.
* [steppy-toolkit](https://github.com/neptune-ml/steppy-toolkit) -&gt; 神经网络、变压器和模型的精选集合，使您的机器学习工作更快、更有效.
* [CNTK](https://github.com/Microsoft/CNTK)  - Microsoft Cognitive Toolkit (CNTK)，一个开源深度学习工具包. 文档可以找到 [here](https://docs.microsoft.com/cognitive-toolkit/).
* [Couler](https://github.com/couler-proj/couler) - 用于在不同工作流引擎（例如 Argo Workflows、Tekton Pipelines 和 Apache Airflow）上构建和管理机器学习工作流的统一界面.
* [auto_ml](https://github.com/ClimbsRocks/auto_ml)  - 用于生产和分析的自动化机器学习. 让您可以专注于 ML 的有趣部分，同时输出可用于生产的代码以及数据集和结果的详细分析. 包括对 NLP、XGBoost、CatBoost、LightGBM 以及即将推出的深度学习的支持.
* [dtaidistance](https://github.com/wannesm/dtaidistance) - 用于时间序列距离（DTW）和时间序列聚类的高性能库.
* [einops](https://github.com/arogozhnikov/einops) - 深度学习操作的重新设计（针对 pytorch、tensorflow、jax 等）.
* [machine learning](https://github.com/jeff1evesque/machine-learning) - 自动构建包括 [web-interface](https://github.com/jeff1evesque/machine-learning#web-interface)，以及一组 [programmatic-interface](https://github.com/jeff1evesque/machine-learning#programmatic-interface)  API，用于支持向量机. 相应的数据集存储到 SQL 数据库中，然后生成的用于预测的模型存储到 NoSQL 数据存储中.
* [XGBoost](https://github.com/dmlc/xgboost) - eXtreme Gradient Boosting（树）库的 Python 绑定.
* [ChefBoost](https://github.com/serengil/chefboost)  - 一个轻量级的Python决策树框架，支持分类特征，涵盖常规决策树算法，如ID3、C4.5、CART、CHAID和回归树； 还有一些先进的装袋和增强技术，例如梯度增强、随机森林和 adaboost.
* [Apache SINGA](https://singa.apache.org) - 用于开发开源机器学习库的 Apache 孵化项目.
* [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - 关于 Python 概率编程的书籍/iPython 笔记本.
* [Featureforge](https://github.com/machinalis/featureforge) 一组用于创建和测试机器学习功能的工具，具有 scikit-learn 兼容的 API.
* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Spark中的分布式机器学习库
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - 用于将 Apache Spark MLLib 机器学习模型部署为实时、批处理或反应式 Web 服务的服务.
* [Towhee](https://towhee.io) - 将非结构化数据编码为嵌入的 Python 模块.
* [scikit-learn](https://scikit-learn.org/) - 构建在 SciPy 之上的用于机器学习的 Python 模块.
* [metric-learn](https://github.com/metric-learn/metric-learn) - 用于度量学习的 Python 模块.
* [OpenMetricLearning](https://github.com/OML-Team/open-metric-learning) - 基于 PyTorch 的框架，用于训练和验证生成高质量嵌入的模型.
* [Intel(R) Extension for Scikit-learn](https://github.com/intel/scikit-learn-intelex) - 一种无缝的方式来加速您的 Scikit-learn 应用程序，不会造成准确性损失和代码更改.
* [SimpleAI](https://github.com/simpleai-team/simpleai)  Python 实现了《人工智能，一种现代方法》一书中描述的许多人工智能算法. 它专注于提供一个易于使用、文档齐全且经过测试的库.
* [astroML](https://www.astroml.org/) - 天文学的机器学习和数据挖掘.
* [graphlab-create](https://turi.com/products/create/docs/) - 一个包含各种机器学习模型（回归、集群、推荐系统、图形分析等）的库，在磁盘支持的 DataFrame 之上实现.
* [BigML](https://bigml.com) - 联系外部服务器的库.
* [pattern](https://github.com/clips/pattern) - Python 的 Web 挖掘模块.
* [NuPIC](https://github.com/numenta/nupic) - Numenta 智能计算平台.
* [Pylearn2](https://github.com/lisa-lab/pylearn2) - 基于的机器学习库 [Theano](https://github.com/Theano/Theano) .  **[已弃用]**
* [keras](https://github.com/keras-team/keras) - 高级神经网络前端 [TensorFlow](https://github.com/tensorflow/tensorflow), [CNTK](https://github.com/Microsoft/CNTK) 和 [Theano](https://github.com/Theano/Theano).
* [Lasagne](https://github.com/Lasagne/Lasagne) - 用于在 Theano 中构建和训练神经网络的轻量级库.
* [hebel](https://github.com/hannes-brt/hebel)  - Python 中的 GPU 加速深度学习库.  **[已弃用]**
* [Chainer](https://github.com/chainer/chainer) - 灵活的神经网络框架.
* [prophet](https://facebook.github.io/prophet/) - Facebook 的快速自动化时间序列预测框架.
* [gensim](https://github.com/RaRe-Technologies/gensim) - 人类主题建模.
* [topik](https://github.com/ContinuumIO/topik)  - 主题建模工具包.  **[已弃用]**
* [PyBrain](https://github.com/pybrain/pybrain) - 另一个 Python 机器学习库.
* [Brainstorm](https://github.com/IDSIA/brainstorm)  - 快速、灵活且有趣的神经网络. 这是 PyBrain 的继承者.
* [Surprise](https://surpriselib.com) - 用于构建和分析推荐系统的 scikit.
* [implicit](https://implicit.readthedocs.io/en/latest/quickstart.html) - 针对隐式数据集的快速 Python 协同过滤.
* [LightFM](https://making.lyst.com/lightfm/docs/home.html) - 许多流行的推荐算法的 Python 实现，用于隐式和显式反馈.
* [Crab](https://github.com/muricoca/crab)  - 灵活、快速的推荐引擎.  **[已弃用]**
* [python-recsys](https://github.com/ocelma/python-recsys) - 用于实现推荐系统的 Python 库.
* [thinking bayes](https://github.com/AllenDowney/ThinkBayes) - 贝叶斯分析书籍.
* [Image-to-Image Translation with Conditional Adversarial Networks](https://github.com/williamFalcon/pix2pix-keras) - 从论文中实现图像到图像（pix2pix）的转换 [isola et al](https://arxiv.org/pdf/1611.07004.pdf).[深度学习]
* [Restricted Boltzmann Machines](https://github.com/echen/restricted-boltzmann-machines)  -Python 中的受限玻尔兹曼机.  [深度学习]
* [Bolt](https://github.com/pprett/bolt)  - Bolt 在线学习工具箱.  **[已弃用]**
* [CoverTree](https://github.com/patvarilly/CoverTree) - 覆盖树的 Python 实现，几乎直接替代 scipy.spatial.kdtree **[已弃用]**
* [nilearn](https://github.com/nilearn/nilearn) - Python 中的神经影像机器学习.
* [neuropredict](https://github.com/raamana/neuropredict)  - 该软件包针对机器学习新手和非专家程序员，提供简单（无需编码）和全面的机器学习（无需编码即可评估和预测性能的完整报告），用于神经成像和任何其他类型的功能. 其目的是吸收大部分 ML 工作流程，与 nilearn 和 pymvpa 等其他软件包不同，这些软件包需要您学习它们的 API 和代码才能生成任何有用的内容.
* [imbalanced-learn](https://imbalanced-learn.org/stable/) - 使用各种技术执行欠采样和过采样的 Python 模块.
* [imbalanced-ensemble](https://github.com/ZhiningLiu1998/imbalanced-ensemble)  - 用于快速实现、修改、评估和可视化类不平衡数据的集成学习算法的 Python 工具箱. 支持开箱即用的多类不平衡（长尾）分类.
* [Shogun](https://github.com/shogun-toolbox/shogun) - 幕府将军机器学习工具箱.
* [Pyevolve](https://github.com/perone/Pyevolve)  - 遗传算法框架.  **[已弃用]**
* [Caffe](https://github.com/BVLC/caffe) - 开发时考虑到清洁性、可读性和速度的深度学习框架.
* [breze](https://github.com/breze-no-salt/breze) - 基于 Theano 的深度和循环神经网络库.
* [Cortex](https://github.com/cortexlabs/cortex) - 用于在生产中部署机器学习模型的开源平台.
* [pyhsmm](https://github.com/mattjj/pyhsmm) - 贝叶斯隐马尔可夫模型 (HMM) 和显式持续时间隐半马尔可夫模型 (HSMM) 中的近似无监督推理库，重点关注贝叶斯非参数扩展、HDP-HMM 和 HDP-HSMM，大多具有弱极限近似.
* [SKLL](https://github.com/EducationalTestingService/skll) - scikit-learn 的包装器，使实验变得更简单.
* [neurolab](https://github.com/zueve/neurolab)
* [Spearmint](https://github.com/HIPS/Spearmint)  - Spearmint 是一个根据机器学习算法的实用贝叶斯优化论文中概述的算法执行贝叶斯优化的软件包. 贾斯珀·斯诺克、雨果·拉罗谢尔和瑞安·P·亚当斯. 神经信息处理系统的进展，2012 年. **[已弃用]**
* [Pebl](https://github.com/abhik/pebl/)  - 用于贝叶斯学习的 Python 环境.  **[已弃用]**
* [Theano](https://github.com/Theano/Theano/) - 优化 GPU 元编程代码，在 Python 中生成面向数组的优化数学编译器.
* [TensorFlow](https://github.com/tensorflow/tensorflow/) - 使用数据流图进行数值计算的开源软件库.
* [pomegranate](https://github.com/jmschrei/pomegranate) - Python 的隐马尔可夫模型，在 Cython 中实现，以提高速度和效率.
* [python-timbl](https://github.com/proycon/python-timbl)  - 包装完整 TiMBL C++ 编程接口的 Python 扩展模块.  Timbl 是一个精心设计的 k-Nearest Neighbors 机器学习工具包.
* [deap](https://github.com/deap/deap) - 进化算法框架.
* [pydeep](https://github.com/andersbll/deeppy)  - Python 深度学习.  **[已弃用]**
* [mlxtend](https://github.com/rasbt/mlxtend) - 一个由数据科学和机器学习任务的有用工具组成的库.
* [neon](https://github.com/NervanaSystems/neon) - 涅瓦纳 [high-performance](https://github.com/soumith/convnet-benchmarks) 基于Python的深度学习框架[DEEP LEARNING].  **[已弃用]**
* [Optunity](https://optunity.readthedocs.io/en/latest/) - 一个致力于自动超参数优化的库，具有简单、轻量级的 API，以方便网格搜索的直接替换.
* [Neural Networks and Deep Learning](https://github.com/mnielsen/neural-networks-and-deep-learning) - 我的书“神经网络和深度学习”[深度学习]的代码示例.
* [Annoy](https://github.com/spotify/annoy) - 近似最近邻实现.
* [TPOT](https://github.com/EpistasisLab/tpot)  - 使用遗传编程自动创建和优化机器学习管道的工具. 将其视为您的个人数据科学助手，自动执行机器学习的繁琐部分.
* [pgmpy](https://github.com/pgmpy/pgmpy) 用于处理概率图形模型的 python 库.
* [DIGITS](https://github.com/NVIDIA/DIGITS) - 深度学习 GPU 训练系统 (DIGITS) 是一个用于训练深度学习模型的 Web 应用程序.
* [Orange](https://orange.biolab.si/) - 适合新手和专家的开源数据可视化和数据分析.
* [MXNet](https://github.com/apache/incubator-mxnet)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [milk](https://github.com/luispedro/milk)  - 专注于监督分类的机器学习工具包.  **[已弃用]**
* [TFLearn](https://github.com/tflearn/tflearn) - 深度学习库，具有适用于 TensorFlow 的更高级别 API.
* [REP](https://github.com/yandex/rep)  - 基于 IPython 的环境，用于以一致且可重复的方式进行数据驱动的研究.  REP 并不是试图取代 scikit-learn，而是对其进行了扩展并提供更好的用户体验.  **[已弃用]**
* [rgf_python](https://github.com/RGF-team/rgf) - Python bindings for Regularized Greedy Forest (Tree) Library.
* [skbayes](https://github.com/AmazaspShumik/sklearn-bayes) - 使用 scikit-learn API 进行贝叶斯机器学习的 Python 包.
* [fuku-ml](https://github.com/fukuball/fuku-ml) - Simple machine learning library, including Perceptron, Regression, Support Vector Machine, Decision Tree and more, it's easy to use and easy to learn for beginners.
* [Xcessiv](https://github.com/reiinakano/xcessiv) - 基于 Web 的应用程序，用于快速、可扩展且自动化的超参数调整和堆叠集成.
* [PyTorch](https://github.com/pytorch/pytorch) - Python 中的张量和动态神经网络，具有强大的 GPU 加速功能
* [PyTorch Lightning](https://github.com/PyTorchLightning/pytorch-lightning) - 用于高性能人工智能研究的轻量级 PyTorch 包装器.
* [PyTorch Lightning Bolts](https://github.com/PyTorchLightning/pytorch-lightning-bolts) - 供 AI/ML 研究人员使用的模型、回调和数据集工具箱.
* [skorch](https://github.com/skorch-dev/skorch) - 一个封装 PyTorch 的 scikit-learn 兼容神经网络库.
* [ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch)  - 使用 Python 从头开始​​实现机器学习模型，重点是透明度. 旨在以易于理解的方式展示机器学习的具体细节.
* [Edward](http://edwardlib.org/)  - 概率建模、推理和批评的库. 构建于 TensorFlow 之上.
* [xRBM](https://github.com/omimo/xRBM) - Tensorflow 中的受限玻尔兹曼机 (RBM) 及其条件变体的库.
* [CatBoost](https://github.com/catboost/catboost)  - 决策树库上的通用梯度提升，具有开箱即用的分类特征支持. 它易于安装、文档齐全并支持 CPU 和 GPU（甚至多 GPU）计算.
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) - 在 Python 中将机器学习堆栈技术实现为一个方便的库.
* [modAL](https://github.com/modAL-python/modAL) - Python 的模块化主动学习框架，构建于 scikit-learn 之上.
* [Cogitare](https://github.com/cogitare-ai/cogitare)：现代、快速、模块化的 Python 深度学习和机器学习框架.
* [Parris](https://github.com/jgreenemi/Parris) - Parris，用于机器学习算法的自动化基础设施设置工具.
* [neonrvm](https://github.com/siavashserver/neonrvm)  - neonrvm是一个基于RVM技术的开源机器学习库. 它是用 C 编程语言编写的，并附带 Python 编程语言绑定.
* [Turi Create](https://github.com/apple/turicreate)  - Apple 的机器学习.  Turi Create 简化了自定义机器学习模型的开发. 您无需成为机器学习专家即可将推荐、对象检测、图像分类、图像相似度或活动分类添加到您的应用程序中.
* [xLearn](https://github.com/aksnzhy/xlearn)  - 高性能、易于使用、可扩展的机器学习包，可用于解决大规模机器学习问题.  xLearn 对于解决大规模稀疏数据的机器学习问题特别有用，这在在线广告和推荐系统等互联网服务中非常常见.
* [mlens](https://github.com/flennerhag/mlens) - 与 scikit-learn 集成的高性能、内存高效、最大并行的集成学习.
* [Thampi](https://github.com/scoremedia/thampi) - AWS Lambda 上的机器学习预测系统
* [MindsDB](https://github.com/mindsdb/mindsdb) - 简化神经网络使用的开源框架.
* [Microsoft Recommenders](https://github.com/Microsoft/Recommenders) ：构建推荐系统的示例和最佳实践，以 Jupyter 笔记本形式提供. 该存储库包含来自 Microsoft Research 以及其他公司和机构的一些最新的最先进算法.
* [StellarGraph](https://github.com/stellargraph/stellargraph)：Machine Learning on Graphs，一个用于对图结构（网络结构）数据进行机器学习的 Python 库.
* [BentoML](https://github.com/bentoml/bentoml)：用于打包和部署机器学习模型以在生产中提供服务的工具包
* [MiraiML](https://github.com/arthurpaulino/miraiml)：用于连续和自主机器学习的异步引擎，专为实时使用而构建.
* [numpy-ML](https://github.com/ddbourgin/numpy-ml)：用 numpy 编写的 ML 模型的参考实现
* [Neuraxle](https://github.com/Neuraxio/Neuraxle)：提供正确抽象的框架，以简化 ML 管道的研究、开发和部署.
* [Cornac](https://github.com/PreferredAI/cornac) - 多模式推荐系统的比较框架，重点关注利用辅助数据的模型.
* [JAX](https://github.com/google/jax) - JAX 是 Autograd 和 XLA 的结合，用于高性能机器学习研究.
* [Catalyst](https://github.com/catalyst-team/catalyst)  - 用于 PyTorch DL 和 RL 研究的高级实用程序. 它的开发重点是可重复性、快速实验和代码/想法重用. 能够研究/开发新的东西，而不是编写另一个常规的火车循环.
* [Fastai](https://github.com/fastai/fastai) - 构建在 Pytorch 之上的高级包装器，支持视觉、文本、表格数据和协作过滤.
* [scikit-multiflow](https://github.com/scikit-multiflow/scikit-multiflow) - 用于多输出/多标签和流数据的机器学习框架.
* [Lightwood](https://github.com/mindsdb/lightwood) - 一种基于 Pytorch 的框架，可将机器学习问题分解为更小的块，这些块可以无缝地粘合在一起，目标是用一行代码构建预测模型.
* [bayeso](https://github.com/jungtaekkim/bayeso) - 一个简单但重要的贝叶斯优化包，用 Python 编写.
* [mljar-supervised](https://github.com/mljar/mljar-supervised)  - 用于表格数据的自动机器学习 (AutoML) python 包. 它可以处理：二元分类、多类分类和回归. 它提供解释和降价报告.
* [evostra](https://github.com/alirezamika/evostra) - Python 中的快速进化策略实现.
* [Determined](https://github.com/determined-ai/determined) - 可扩展的深度学习训练平台，包括对分布式训练、超参数调整、实验跟踪和模型管理的集成支持.
* [PySyft](https://github.com/OpenMined/PySyft) - 基于 PyTorch 和 TensorFlow 构建的用于安全和私有深度学习的 Python 库.
* [PyGrid](https://github.com/OpenMined/PyGrid/) - 数据所有者和数据科学家的点对点网络，他们可以使用 PySyft 共同训练人工智能模型
* [sktime](https://github.com/alan-turing-institute/sktime) - 时间序列机器学习的统一框架
* [OPFython](https://github.com/gugarosa/opfython) - 受 Python 启发的最佳路径森林分类器的实现.
* [Opytimizer](https://github.com/gugarosa/opytimizer) - 基于Python的元启发式优化技术.
* [Gradio](https://github.com/gradio-app/gradio)  - 用于快速创建和共享模型演示的 Python 库. 在浏览器中以交互方式调试模型，从协作者那里获取反馈，并生成公共链接，而无需部署任何内容.
* [Hub](https://github.com/activeloopai/Hub)  - TensorFlow/PyTorch 最快的非结构化数据集管理. 流和版本控制数据. 将 PB 级数据存储在云上的单个类似 numpy 的数组中，可在任何计算机上访问. 访问 [activeloop.ai](https://activeloop.ai) 了解更多信息.
* [Synthia](https://github.com/dmey/synthia) - Python 中的多维合成数据生成.
* [ByteHub](https://github.com/bytehub-ai/bytehub)  - 易于使用、基于 Python 的特征存储. 针对时间序列数据进行了优化.
* [Backprop](https://github.com/backprop-ai/backprop) - Backprop 使使用、微调和部署最先进的 ML 模型变得简单.
* [River](https://github.com/online-ml/river)：通用在线机器学习的框架.
* [FEDOT](https://github.com/nccr-itmo/FEDOT) ：用于自动设计复合建模管道的 AutoML 框架. 它可以处理不同类型数据（包括多模态数据集）的分类、回归和时间序列预测任务.
* [Sklearn-genetic-opt](https://github.com/rodrigo-arenas/Sklearn-genetic-opt)：使用进化算法进行超参数调整的 AutoML 包，具有​​内置回调、绘图、远程日志记录等功能.
* [Evidently](https://github.com/evidentlyai/evidently)：交互式报告，用于在验证或生产监控期间分析机器学习模型.
* [Streamlit](https://github.com/streamlit/streamlit)：Streamlit 是一个框架，可以在数小时而不是数周内创建漂亮的数据应用程序.
* [Optuna](https://github.com/optuna/optuna)：Optuna 是一个自动超参数优化软件框架，专为机器学习而设计.
* [Deepchecks](https://github.com/deepchecks/deepchecks) ：在模型开发、部署和生产过程中验证和测试机器学习模型和数据. 这包括与各种类型问题相关的检查和套件，例如模型性能、数据完整性、分布不匹配等.
* [Shapash](https://github.com/MAIF/shapash) ：Shapash 是一个 Python 库，它提供多种类型的可视化，显示每个人都可以理解的显式标签.
* [Eurybia](https://github.com/MAIF/eurybia)：Eurybia 监控数据和模型随时间的漂移，并通过数据验证确保模型部署的安全.
* [Colossal-AI](https://github.com/hpcaitech/ColossalAI)：一个开源的深度学习系统，用于高效率、低成本的大规模模型训练和推理.
* [dirty_cat](https://github.com/dirty-cat/dirty_cat)  - 促进对脏的、非策划类别的机器学习. 它提供了对形态变异（例如拼写错误）具有鲁棒性的变压器和编码器.
* [Upgini](https://github.com/upgini/upgini)：用于机器学习的免费自动化数据和特征丰富库 - 从公共和社区共享数据源自动搜索数千个即用型特征，并仅通过提高准确性的特征来丰富您的训练数据集.
* [AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics](https://github.com/Western-OC2-Lab/AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics)：帮助机器学习研究人员自动获得优化的机器学习模型的教程，在任何特定任务上都具有最佳的学习性能.
* [SKBEL](https://github.com/robinthibaut/skbel)：用于贝叶斯证据学习 (BEL) 的 Python 库，用于估计预测的不确定性.
* [NannyML](https://bit.ly/nannyml-github-machinelearning) ：能够充分捕捉数据漂移对性能影响的Python库. 允许在不访问目标的情况下评估部署后模型的性能.
* [cleanlab](https://github.com/cleanlab/cleanlab)：以数据为中心的标准 AI 包，用于数据质量和机器学习，包含混乱的真实数据和标签.
* [AutoGluon](https://github.com/awslabs/autogluon)：适用于图像、文本、表格、时间序列和多模态数据的 AutoML.
* [PyBroker](https://github.com/edtechre/pybroker) - 机器学习的算法交易.
* [Frouros](https://github.com/IFCA/frouros)：Frouros 是一个开源 Python 库，用于机器学习系统中的偏差检测.


<a name="python-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization
* [DataVisualization](https://github.com/Shanky-21/Data_visualization) - GitHub 存储库，您可以在其中学习数据可视化基础知识到中级水平.
* [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) - Cartopy 是一个 Python 包，专为地理空间数据处理而设计，以生成地图和其他地理空间数据分析.
* [SciPy](https://www.scipy.org/) - 基于 Python 的数学、科学和工程开源软件生态系统.
* [NumPy](https://www.numpy.org/) - 使用 Python 进行科学计算的基本包.
* [AutoViz](https://github.com/AutoViML/AutoViz)  AutoViz 使用一行 Python 代码对任何数据集执行自动可视化. 给它任何大小的输入文件（CSV、txt 或 JSON），AutoViz 就会将其可视化. 请参阅<a href="https://towardsdatascience.com/autoviz-a-new-tool-for-automated-visualization-ec9c1744a6ad?source=friends_link&sk=c9e9503ec424b191c6096d7e3f515d10">中型文章</a>.
* [Numba](https://numba.pydata.org/) - Cython 和 NumPy 开发人员针对科学 Python 的 LLVM 的 Python JIT（及时）编译器.
* [Mars](https://github.com/mars-project/mars) - 用于大规模数据计算的基于张量的框架，通常被视为 NumPy 的并行分布式版本.
* [NetworkX](https://networkx.github.io/) - 适用于复杂网络的高生产力软件.
* [igraph](https://igraph.org/python/) - 绑定到 igraph 库 - 通用图形库.
* [Pandas](https://pandas.pydata.org/) - 提供高性能、易于使用的数据结构和数据分析工具的库.
* [ParaMonte](https://github.com/cdslaborg/paramonte)  - 通用 Python 库，用于通过串行/并行蒙特卡罗和 MCMC 模拟进行贝叶斯数据分析和可视化. 文档可以找到 [here](https://www.cdslab.org/paramonte/).
* [Vaex](https://github.com/vaexio/vaex)  - 用于惰性外核数据帧（类似于 Pandas）的高性能 Python 库，用于可视化和探索大型表格数据集. 文档可以找到 [here](https://vaex.io/docs/index.html).
* [Open Mining](https://github.com/mining/mining) - Python 中的商业智能 (BI)（Pandas Web 界面）**[​​已弃用]**
* [PyMC](https://github.com/pymc-devs/pymc) - 马尔可夫链蒙特卡罗采样工具包.
* [zipline](https://github.com/quantopian/zipline) - Pythonic 算法交易库.
* [PyDy](https://www.pydy.org/) - Python Dynamics 的缩写，用于协助基于 NumPy、SciPy、IPython 和 matplotlib 的动态运动建模工作流程.
* [SymPy](https://github.com/sympy/sympy) - 用于符号数学的 Python 库.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Python 中的统计建模和计量经济学.
* [astropy](https://www.astropy.org/) - 天文学社区 Python 库.
* [matplotlib](https://matplotlib.org/) - Python 2D 绘图库.
* [bokeh](https://github.com/bokeh/bokeh) - Python 交互式网页绘图.
* [plotly](https://plot.ly/python/) - Python 和 matplotlib 的协作网络绘图.
* [altair](https://github.com/altair-viz/altair) - Python 到 Vega 的翻译器.
* [d3py](https://github.com/mikedewar/d3py) - Python 绘图库，基于 [D3.js](https://d3js.org/).
* [PyDexter](https://github.com/D3xterjs/pydexter)  - Python 的简单绘图.  D3xterjs 的包装器； 轻松在浏览器中呈现图表.
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R. **[Deprecated]**
* [ggfortify](https://github.com/sinhrks/ggfortify) - ggplot2 流行 R 包的统一接口.
* [Kartograph.py](https://github.com/kartograph/kartograph.py) - 在 Python 中渲染漂亮的 SVG 地图.
* [pygal](http://pygal.org/en/stable/) - Python SVG 图表创建器.
* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) - 基于 PyQt4 / PySide 和 NumPy 构建的纯 python 图形和 GUI 库.
* [pycascading](https://github.com/twitter/pycascading) **[已弃用]**
* [Petrel](https://github.com/AirSage/Petrel) - 用纯 Python 编写、提交、调试和监控 Storm 拓扑的工具.
* [Blaze](https://github.com/blaze/blaze) - NumPy 和 Pandas 与大数据的接口.
* [emcee](https://github.com/dfm/emcee) - 用于仿射不变 MCMC 的 Python 集成采样工具包.
* [windML](https://github.com/cigroup-ol/windml) - 用于风能分析和预测的 Python 框架.
* [vispy](https://github.com/vispy/vispy) - 基于GPU的高性能交互式OpenGL 2D/3D数据可视化库.
* [cerebro2](https://github.com/numenta/nupic.cerebro2) 基于 Web 的 NuPIC 可视化和调试平台.  **[已弃用]**
* [NuPIC Studio](https://github.com/htm-community/nupic.studio) 一款一体化 NuPIC 分层时序内存可视化和调试超级工具！  **[已弃用]**
* [SparklingPandas](https://github.com/sparklingpandas/sparklingpandas) PySpark 上的 Pandas (POPS).
* [Seaborn](https://seaborn.pydata.org/) - 基于 matplotlib 的 python 可视化库.
* [ipychart](https://github.com/nicohlr/ipychart) - Jupyter Notebook 中 Chart.js 的强大功能.
* [bqplot](https://github.com/bloomberg/bqplot) - 用于在 Jupyter (IPython) 中绘图的 API.
* [pastalog](https://github.com/rewonc/pastalog) - 神经网络训练性能的简单、实时可视化.
* [Superset](https://github.com/apache/incubator-superset) - 一个旨在可视化、直观和交互的数据探索平台.
* [Dora](https://github.com/nathanepstein/dora) - 用于 Python 探索性数据分析的工具.
* [Ruffus](http://www.ruffus.org.uk) - python 计算管道库.
* [SOMPY](https://github.com/sevamoo/SOMPY) - 用 Python 编写的自组织地图（使用神经网络进行数据分析）.
* [somoclu](https://github.com/peterwittek/somoclu) 大规模并行自组织映射：加速多核 CPU、GPU 和集群上的训练，具有 python API.
* [HDBScan](https://github.com/lmcinnes/hdbscan) - Python 中 hdbscan 算法的实现 - 用于聚类
* [visualize_ML](https://github.com/ayush1997/visualize_ML)  - 用于数据探索和数据分析的Python包.  **[已弃用]**
* [scikit-plot](https://github.com/reiinakano/scikit-plot) - 一个可视化库，用于快速轻松地生成数据分析和机器学习中的常见图表.
* [Bowtie](https://github.com/jwkvam/bowtie) - 使用 Flask socketio 和 React 进行交互式可视化的仪表板库.
* [lime](https://github.com/marcotcr/lime)  - Lime 旨在解释机器学习分类器（或模型）正在做什么. 它能够解释任何具有两个或更多类的黑盒分类器.
* [PyCM](https://github.com/sepandhaghighi/pycm) - PyCM is a multi-class confusion matrix library written in Python that supports both input data vectors and direct matrix, and a proper tool for post-classification model evaluation that supports most classes and overall statistics parameters
* [Dash](https://github.com/plotly/dash) - 用于创建基于 Plotly.js、React 和 Flask 的分析 Web 应用程序的框架
* [Lambdo](https://github.com/asavinov/lambdo) - A workflow engine for solving machine learning problems by combining in one analysis pipeline (i) feature engineering and machine learning (ii) model training and prediction (iii) table population and column evaluation via user-defined (Python) functions.
* [TensorWatch](https://github.com/microsoft/tensorwatch)  - 用于机器学习和数据科学的调试和可视化工具. 它广泛利用 Jupyter Notebook 来显示机器学习训练等运行过程中数据的实时可视化.
* [dowel](https://github.com/rlworkgroup/dowel)  - 用于机器学习研究的小记录器. 只需调用一次“logger.log()”即可将任何对象输出到终端、CSV、TensorBoard、磁盘上的文本日志等.

<a name="python-misc-scripts--ipython-notebooks--codebases"></a>
#### Misc Scripts / iPython Notebooks / Codebases
* [MiniGrad](https://github.com/kennysong/minigrad) – A minimal, educational, Pythonic implementation of autograd (~100 loc).
* [Map/Reduce implementations of common ML algorithms](https://github.com/Yannael/BigDataAnalytics_INFOH515)：Jupyter 笔记本，介绍如何使用 Python NumPy 从头开始​​实现不同的 ML 算法（普通最小二乘、梯度下降、k 均值、交替最小二乘），以及如何使用 Map/Reduce 和 Spark 使这些实现可扩展.
* [BioPy](https://github.com/jaredthecoder/BioPy)  - Python 中的生物学启发和机器学习算法.  **[已弃用]**
* [CAEs for Data Assimilation](https://github.com/julianmack/Data_Assimilation) - 用于降阶的 3D 图像/场压缩的卷积自动编码器 [Data Assimilation](https://en.wikipedia.org/wiki/Data_assimilation).
* [handsonml](https://github.com/ageron/handson-ml) - Python 机器学习基础知识.
* [SVM Explorer](https://github.com/plotly/dash-svm) - 交互式 SVM Explorer，使用 Dash 和 scikit-learn
* [pattern_classification](https://github.com/rasbt/pattern_classification)
* [thinking stats 2](https://github.com/Wavelets/ThinkStats2)
* [hyperopt](https://github.com/hyperopt/hyperopt-sklearn)
* [numpic](https://github.com/numenta/nupic)
* [2012-paper-diginorm](https://github.com/dib-lab/2012-paper-diginorm)
* [A gallery of interesting IPython notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* [ipython-notebooks](https://github.com/ogrisel/notebooks)
* [data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - 持续更新数据科学Python笔记本：Spark、Hadoop MapReduce、HDFS、AWS、Kaggle、scikit-learn、matplotlib、pandas、NumPy、SciPy和各种命令行.
* [decision-weights](https://github.com/CamDavidsonPilon/decision-weights)
* [Sarah Palin LDA](https://github.com/Wavelets/sarah-palin-lda) - 对 Sarah Palin 电子邮件进行主题建模.
* [Diffusion Segmentation](https://github.com/Wavelets/diffusion-segmentation) - 基于扩散方法的图像分割算法的集合.
* [Scipy Tutorials](https://github.com/Wavelets/scipy-tutorials)  - SciPy 教程. 这已经过时了，请查看 scipy-lecture-notes.
* [Crab](https://github.com/marcelcaraciolo/crab) - Python 的推荐引擎库.
* [BayesPy](https://github.com/maxsklar/BayesPy) - Python 中的贝叶斯推理工具.
* [scikit-learn tutorials](https://github.com/GaelVaroquaux/scikit-learn-tutorial) - 用于学习 scikit-learn 的系列笔记本.
* [sentiment-analyzer](https://github.com/madhusudancs/sentiment-analyzer) - 推文情绪分析器
* [sentiment_classifier](https://github.com/kevincobain2000/sentiment_classifier) - 使用词义消歧的情感分类器.
* [group-lasso](https://github.com/fabianp/group_lasso) -（稀疏）组套索模型中使用的坐标下降算法的一些实验.
* [jProcessing](https://github.com/kevincobain2000/jProcessing)  - 汉字/平假名/片假名到罗马字转换器. 法令词典和平行句子搜索. 两个 JP 句子之间的句子相似度. 日语文本的情感分析. 在 Python 中运行 Cabocha（已配置 ISO--8859-1）.
* [mne-python-notebooks](https://github.com/mne-tools/mne-python-notebooks) - 使用 mne-python 进行 EEG/MEG 数据处理的 IPython 笔记本.
* [Neon Course](https://github.com/NervanaSystems/neon_course) - IPython 笔记本，用于了解 Nervana Neon 的完整课程.
* [pandas cookbook](https://github.com/jvns/pandas-cookbook) - 使用 Python 的 pandas 库的秘诀.
* [climin](https://github.com/BRML/climin) - 专注于机器学习、梯度下降、LBFGS、rmsprop、adadelta 等的 Pythonic 实现的优化库.
* [Allen Downey’s Data Science Course](https://github.com/AllenDowney/DataScience) - 奥林学院数据科学代码，2014 年春季.
* [Allen Downey’s Think Bayes Code](https://github.com/AllenDowney/ThinkBayes) - Think Bayes 的代码存储库.
* [Allen Downey’s Think Complexity Code](https://github.com/AllenDowney/ThinkComplexity) - Allen Downey 的书《Think Complexity》的代码.
* [Allen Downey’s Think OS Code](https://github.com/AllenDowney/ThinkOS) - Think OS 的文本和支持代码：操作系统简介.
* [Python Programming for the Humanities](https://www.karsdorp.io/python-course/)  - 人文科学 Python 编程课程，假设没有任何先验知识. 重点关注文本处理/NLP.
* [GreatCircle](https://github.com/mwgg/GreatCircle) - 用于计算大圆距离的库.
* [Optunity examples](http://optunity.readthedocs.io/en/latest/notebooks/index.html) - 演示如何将 Optunity 与机器学习库协同使用的示例.
* [Dive into Machine Learning  with Python Jupyter notebook and scikit-learn](https://github.com/hangtwenty/dive-into-machine-learning) - “我首先通过黑客技术学习了 Python，*后来才开始认真学习.*我想通过机器学习来做到这一点.如果这是您的风格，请和我一起超越自己.”
* [TDB](https://github.com/ericjang/tdb)  - TensorDebugger (TDB) 是一个用于深度学习的可视化调试器. 它具有交互式、逐节点调试和 TensorFlow 可视化功能.
* [Suiron](https://github.com/kendricktan/suiron/) - 遥控汽车的机器学习.
* [Introduction to machine learning with scikit-learn](https://github.com/justmarkham/scikit-learn-videos) - Data School 的 scikit-learn 视频教程中的 IPython 笔记本.
* [Practical XGBoost in Python](https://parrotprediction.teachable.com/p/practical-xgboost-in-python) - 关于在 Python 中使用 XGBoost 的综合在线课程.
* [Introduction to Machine Learning with Python](https://github.com/amueller/introduction_to_ml_with_python) - 《Python 机器学习简介》一书的笔记本和代码
* [Pydata book](https://github.com/wesm/pydata-book) - Wes McKinney 所著的“Python for Data Analysis”的材料和 IPython 笔记本，由 O&#39;Reilly Media 出版
* [Homemade Machine Learning](https://github.com/trekhleb/homemade-machine-learning) - 流行机器学习算法的 Python 示例，带有交互式 Jupyter 演示和数学解释
* [Prodmodel](https://github.com/prodmodel/prodmodel) - 构建数据科学管道工具.
* [the-elements-of-statistical-learning](https://github.com/maitbayev/the-elements-of-statistical-learning) - 该存储库包含实现书中算法和教科书摘要的 Jupyter 笔记本.
* [Hyperparameter-Optimization-of-Machine-Learning-Algorithms](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms) - 机器学习和深度学习算法的超参数调整/优化代码.
* [Heart_Disease-Prediction](https://github.com/ShivamChoudhary17/Heart_Disease) - 根据患者的临床参数，我们可以预测他们是否患有心脏病吗？
* [Flight Fare Prediction](https://github.com/ShivamChoudhary17/Flight_Fare_Prediction) - 这基本上是为了衡量对机器学习工作流程和回归技术的具体理解.
* [Keras Tuner](https://github.com/keras-team/keras-tuner) - 易于使用、可扩展的超参数优化框架，解决超参数搜索的痛点.



<a name="python-neural-networks"></a>
#### Neural Networks

* [nn_builder](https://github.com/p-christ/nn_builder) - nn_builder 是一个 Python 包，可让您用 1 行构建神经网络
* [NeuralTalk](https://github.com/karpathy/neuraltalk) - NeuralTalk 是一个 Python+numpy 项目，用于学习用句子描述图像的多模态循环神经网络.
* [Neuron](https://github.com/molcik/python-neuron)  - Neuron 是用于时间序列预测的简单类. 它利用 LNU（线性神经单元）、QNU（二次神经单元）、RBF（径向基函数）、MLP（多层感知器）、MLP-ELM（多层感知器 - 极限学习机）神经网络，通过梯度下降或 LeLevenberg 学习–Marquardt 算法.

* [NeuralTalk](https://github.com/karpathy/neuraltalk2)  - NeuralTalk 是一个 Python+numpy 项目，用于学习用句子描述图像的多模态循环神经网络.  **[已弃用]**
* [Neuron](https://github.com/molcik/python-neuron)  - Neuron 是用于时间序列预测的简单类. 它利用 LNU（线性神经单元）、QNU（二次神经单元）、RBF（径向基函数）、MLP（多层感知器）、MLP-ELM（多层感知器 - 极限学习机）神经网络，通过梯度下降或 LeLevenberg 学习–Marquardt 算法.  **[已弃用]**
* [Data Driven Code](https://github.com/atmb4u/data-driven-code) - 在 python 中非常简单地实现了傻瓜神经网络，无需使用任何库，并带有详细的注释.
* [Machine Learning, Data Science and Deep Learning with Python](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python) - 涵盖机器学习、Tensorflow、人工智能和神经网络的实时视频课程.
* [TResNet: High Performance GPU-Dedicated Architecture](https://github.com/mrT23/TResNet) - TResNet 模型经过设计和优化，可在 GPU 上实现最佳的速度与准确度权衡.
* [TResNet: Simple and powerful neural network library for python](https://github.com/zueve/neurolab) - 各种受支持类型的人工神经网络和学习算法.
* [Jina AI](https://jina.ai/) 在云中构建神经搜索的更简单方法. 与 Jupyter 笔记本兼容.
* [sequitur](https://github.com/shobrook/sequitur) PyTorch 库，只需两行代码即可创建和训练序列自动编码器


<a name="python-spiking-neural-networks"></a>
#### Spiking Neural Networks

* [Rockpool](https://github.com/synsense/rockpool)  - 用于尖峰神经网络的机器学习库. 支持使用 torch 和 jax 管道进行训练，以及部署到神经形态硬件.
* [Sinabs](https://github.com/synsense/sinabs) - 基于 PyTorch 的尖峰神经网络深度学习库，专注于快速训练并支持神经形态硬件推理.
* [Tonic](https://github.com/neuromorphs/tonic) - 一个库，使下载公开可用的神经形态数据集变得轻而易举，并提供基于事件的数据转换/增强管道.

<a name="python-survival-analysis"></a>
#### Python Survival Analysis
* [lifelines](https://github.com/CamDavidsonPilon/lifelines) - lifelines是一个完整的生存分析库，用纯Python编写
* [Scikit-Survival](https://github.com/sebp/scikit-survival)  - scikit-survival 是一个基于 scikit-learn 构建的用于生存分析的 Python 模块. 它允许在利用 scikit-learn 的强大功能的同时进行生存分析，例如用于预处理或进行交叉验证.

<a name="python-federated-learning"></a>
#### Federated Learning
* [Flower](https://flower.dev/)  - 联合学习、分析和评估的统一方法. 联合任何工作负载、任何 ML 框架和任何编程语言.
* [PySyft](https://github.com/OpenMined/PySyft) - 用于安全和私密深度学习的 Python 库.
* [Tensorflow-Federated](https://www.tensorflow.org/federated) 用于机器学习和其他分散数据计算的联邦学习框架.

<a name="python-kaggle-competition-source-code"></a>
#### Kaggle Competition Source Code
* [open-solution-home-credit](https://github.com/neptune-ml/open-solution-home-credit) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Home-Credit-Default-Risk) 为了 [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk).
* [open-solution-googleai-object-detection](https://github.com/neptune-ml/open-solution-googleai-object-detection) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Google-AI-Object-Detection-Challenge) 为了 [Google AI Open Images - Object Detection Track](https://www.kaggle.com/c/google-ai-open-images-object-detection-track).
* [open-solution-salt-identification](https://github.com/neptune-ml/open-solution-salt-identification) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Salt-Detection) 为了 [TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge).
* [open-solution-ship-detection](https://github.com/neptune-ml/open-solution-ship-detection) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Ships) 为了 [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection).
* [open-solution-data-science-bowl-2018](https://github.com/neptune-ml/open-solution-data-science-bowl-2018) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Data-Science-Bowl-2018) 为了 [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018).
* [open-solution-value-prediction](https://github.com/neptune-ml/open-solution-value-prediction) -&gt; 源代码和 [experiments results](https://app.neptune.ml/neptune-ml/Santander-Value-Prediction-Challenge) 为了 [Santander Value Prediction Challenge](https://www.kaggle.com/c/santander-value-prediction-challenge).
* [open-solution-toxic-comments](https://github.com/neptune-ml/open-solution-toxic-comments) -&gt; 源代码 [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).
* [wiki challenge](https://github.com/hammer/wikichallenge) - Dell 张在 Kaggle 上针对维基百科参与挑战的解决方案的实施.
* [kaggle insults](https://github.com/amueller/kaggle_insults) - Kaggle 提交的“检测社会评论中的侮辱”.
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Kaggle 获取有价值购物者挑战的代码.
* [kaggle-cifar](https://github.com/zygmuntz/kaggle-cifar) - Kaggle 的 CIFAR-10 竞赛代码，使用 cuda-convnet.
* [kaggle-blackbox](https://github.com/zygmuntz/kaggle-blackbox) - 深度学习变得简单.
* [kaggle-accelerometer](https://github.com/zygmuntz/kaggle-accelerometer) - Kaggle 加速度计生物识别竞赛代码.
* [kaggle-advertised-salaries](https://github.com/zygmuntz/kaggle-advertised-salaries) - 通过广告预测工作薪资 - Kaggle 竞赛.
* [kaggle amazon](https://github.com/zygmuntz/kaggle-amazon) - 亚马逊访问控制挑战.
* [kaggle-bestbuy_big](https://github.com/zygmuntz/kaggle-bestbuy_big) - Kaggle 百思买竞赛的代码.
* [kaggle-bestbuy_small](https://github.com/zygmuntz/kaggle-bestbuy_small)
* [Kaggle Dogs vs. Cats](https://github.com/kastnerkyle/kaggle-dogs-vs-cats) - Kaggle 狗与猫比赛的代码.
* [Kaggle Galaxy Challenge](https://github.com/benanne/kaggle-galaxies) - Kaggle 银河挑战赛的获胜解决方案.
* [Kaggle Gender](https://github.com/zygmuntz/kaggle-gender) - A Kaggle competition: discriminate gender based on handwriting.
* [Kaggle Merck](https://github.com/zygmuntz/kaggle-merck) - 默克在 Kaggle 的挑战.
* [Kaggle Stackoverflow](https://github.com/zygmuntz/kaggle-stackoverflow) - 预测 Stack Overflow 上的封闭式问题.
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Kaggle 获取有价值购物者挑战的代码.
* [wine-quality](https://github.com/zygmuntz/wine-quality) - 预测葡萄酒品质.

<a name="python-reinforcement-learning"></a>
#### Reinforcement Learning
* [DeepMind Lab](https://github.com/deepmind/lab)  - DeepMind Lab 是一个通过 ioquake3 和其他开源软件基于 id Software 的 Quake III Arena 的 3D 学习环境. 其主要目的是作为人工智能研究的测试平台，特别是深度强化学习.
* [Gym](https://github.com/openai/gym) - OpenAI Gym 是一个用于开发和比较强化学习算法的工具包.
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI)  - Serpent.AI 是一个游戏代理框架，可让您将您拥有的任何视频游戏变成沙盒来开发人工智能和机器学习实验. 对于研究人员和爱好者来说.
* [ViZDoom](https://github.com/mwydmuch/ViZDoom)  - ViZDoom 允许开发仅使用视觉信息（屏幕缓冲区）玩 Doom 的 AI 机器人. 它主要用于机器视觉学习，特别是深度强化学习的研究.
* [Roboschool](https://github.com/openai/roboschool) - 用于机器人模拟的开源软件，与 OpenAI Gym 集成.
* [Retro](https://github.com/openai/retro) - 健身房的复古游戏
* [SLM Lab](https://github.com/kengz/SLM-Lab) - PyTorch 中的模块化深度强化学习框架.
* [Coach](https://github.com/NervanaSystems/coach) - 英特尔® AI 实验室的强化学习教练支持使用最先进的强化学习算法轻松进行实验
* [garage](https://github.com/rlworkgroup/garage) - 可重复的强化学习研究工具包
* [metaworld](https://github.com/rlworkgroup/metaworld) - 用于元任务和多任务强化学习的开源机器人基准
* [acme](https://deepmind.com/research/publications/Acme) - 用于强化学习的开源分布式框架，可以轻松构建和训练您的代理.
* [Spinning Up](https://spinningup.openai.com) - 旨在让任何人学习成为深度强化学习的熟练实践者的教育资源
* [Maze](https://github.com/enlite-ai/maze) - 面向应用的深度强化学习框架，解决现实世界的决策问题.
* [RLlib](https://github.com/ray-project/ray)  - RLlib 是一个基于 Ray 的行业级、高度可扩展的 RL 库，适用于 tf 和 torch. 亚马逊和微软等公司使用它来大规模解决现实世界的决策问题.
* [DI-engine](https://github.com/opendilab/DI-engine)  - DI-engine 是一个通用的决策智能引擎. 它支持最基本的深度强化学习 (DRL) 算法，例如 DQN、PPO、SAC，以及特定领域的算法，例如多代理 RL 中的 QMIX、逆 RL 中的 GAIL 以及探索问题中的 RND.

<a name="ruby"></a>
## Ruby

<a name="ruby-natural-language-processing"></a>
#### Natural Language Processing

* [Awesome NLP with Ruby](https://github.com/arbox/nlp-with-ruby) - Ruby 中实用自然语言处理的精选链接列表.
* [Treat](https://github.com/louismullie/treat) - 文本检索和注释工具包，绝对是我迄今为止遇到的最全面的 Ruby 工具包.
* [Stemmer](https://github.com/aurelian/ruby-stemmer)  - 将 libstemmer_c 暴露给 Ruby.  **[已弃用]**
* [Raspell](https://sourceforge.net/projects/raspell/)  - raspell 是 ruby​​ 的接口绑定.  **[已弃用]**
* [UEA Stemmer](https://github.com/ealdent/uea-stemmer) - UEALite Stemmer 的 Ruby 端口 - 用于搜索和索引的保守型词干分析器.
* [Twitter-text-rb](https://github.com/twitter/twitter-text/tree/master/rb) - 一个库，可以自动链接和提取推文中的用户名、列表和主题标签.

<a name="ruby-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Awesome Machine Learning with Ruby](https://github.com/arbox/machine-learning-with-ruby) - Ruby ML 相关资源的精选列表.
* [Ruby Machine Learning](https://github.com/tsycho/ruby-machine-learning)  - 一些机器学习算法，用 Ruby 实现.  **[已弃用]**
* [Machine Learning Ruby](https://github.com/mizoR/machine-learning-ruby) **[已弃用]**
* [jRuby Mahout](https://github.com/vasinov/jruby_mahout)  - JRuby Mahout 是一个宝石，它在 JRuby 世界中释放了 Apache Mahout 的力量.  **[已弃用]**
* [CardMagic-Classifier](https://github.com/cardmagic/classifier) - 通用分类器模块，允许贝叶斯和其他类型的分类.
* [rb-libsvm](https://github.com/febeling/rb-libsvm) - LIBSVM 的 Ruby 语言绑定，这是一个支持向量机库.
* [Scoruby](https://github.com/asafschers/scoruby) - 从 PMML 文件创建随机森林分类器.
* [rumale](https://github.com/yoshoku/rumale) - Rumale 是 Ruby 中的机器学习库

<a name="ruby-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [rsruby](https://github.com/alexgutteridge/rsruby) - 红宝石 - R 桥.
* [ruby-plot](https://www.ruby-toolbox.com/projects/ruby-plot)  - Ruby 的 gnuplot 包装器，特别适用于将 ROC 曲线绘制到 SVG 文件中.  **[已弃用]**
* [plot-rb](https://github.com/zuhao/plotrb)  - 建立在 Vega 和 D3 之上的 Ruby 绘图库.  **[已弃用]**
* [scruffy](https://github.com/delano/scruffy) - 一个漂亮的 Ruby 图形工具包.
* [SciRuby](http://sciruby.com/)
* [Glean](https://github.com/glean/glean)  - 人类的数据管理工具.  **[已弃用]**
* [Bioruby](https://github.com/bioruby/bioruby)
* [Arel](https://github.com/nkallen/arel) **[已弃用]**

<a name="ruby-misc"></a>
#### Misc

* [Big Data For Chimps](https://github.com/infochimps-labs/big_data_for_chimps)
* [Listof](https://github.com/kevincobain2000/listof)  - 基于社区的数据收集，打包在 gem 中. 获取 txt、JSON 或哈希中几乎所有内容（停用词、国家/地区、非单词）的列表. [Demo/Search for a list](http://kevincobain2000.github.io/listof/)


<a name="rust"></a>
## Rust

<a name="rust-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [smartcore](https://github.com/smartcorelib/smartcore) - "The Most Advanced Machine Learning Library In Rust."
* [linfa](https://github.com/rust-ml/linfa) - 使用 Rust 构建机器学习应用程序的综合工具包
* [deeplearn-rs](https://github.com/tedsta/deeplearn-rs) - deeplearn-rs 提供了在 MIT 许可下使用矩阵乘法、加法和 ReLU 的简单网络.
* [rustlearn](https://github.com/maciejkula/rustlearn) - 具有逻辑回归、支持向量机、决策树和随机森林的机器学习框架.
* [rusty-machine](https://github.com/AtheMathmo/rusty-machine) - 一个纯 Rust 机器学习库.
* [leaf](https://github.com/autumnai/leaf) - open source framework for machine intelligence, sharing concepts from TensorFlow and Caffe. Available under the MIT license. [**[Deprecated]**](https://medium.com/@mjhirn/tensorflow-wins-89b78b29aafb#.s0a3uy4cc)
* [RustNN](https://github.com/jackm321/RustNN)  - RustNN 是一个前馈神经网络库.  **[已弃用]**
* [RusticSOM](https://github.com/avinashshenoy97/RusticSOM) - 用于自组织映射 (SOM) 的 Rust 库.


<a name="r"></a>
## R

<a name="r-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [ahaz](https://cran.r-project.org/web/packages/ahaz/index.html)  - ahaz：半参数加性风险回归的正则化.  **[已弃用]**
* [arules](https://cran.r-project.org/web/packages/arules/index.html) - arules：采矿协会规则和频繁项集
* [biglasso](https://cran.r-project.org/web/packages/biglasso/index.html) - biglasso：将 Lasso 模型拟合扩展到 R 中的大数据.
* [bmrm](https://cran.r-project.org/web/packages/bmrm/index.html) - bmrm：正规化风险最小化包的捆绑方法.
* [Boruta](https://cran.r-project.org/web/packages/Boruta/index.html) - Boruta：用于所有相关特征选择的包装算法.
* [bst](https://cran.r-project.org/web/packages/bst/index.html) - bst：梯度提升.
* [C50](https://cran.r-project.org/web/packages/C50/index.html) - C50：C5.0 决策树和基于规则的模型.
* [caret](https://topepo.github.io/caret/index.html) - 分类和回归训练：R 中约 150 种 ML 算法的统一接口.
* [caretEnsemble](https://cran.r-project.org/web/packages/caretEnsemble/index.html)  - caretEnsemble：用于拟合多个插入符模型以及创建此类模型的集成的框架.  **[已弃用]**
* [CatBoost](https://github.com/catboost/catboost) - 决策树库上的通用梯度提升，具有开箱即用的 R 分类特征支持.
* [Clever Algorithms For Machine Learning](https://machinelearningmastery.com/)
* [CORElearn](https://cran.r-project.org/web/packages/CORElearn/index.html) - CORElearn：分类、回归、特征评估和序数评估.
-* [CoxBoost](https://cran.r-project.org/web/packages/CoxBoost/index.html) - CoxBoost：Cox 模型通过基于可能性的单一生存终点或竞争风险的提升 **[已弃用]**
* [Cubist](https://cran.r-project.org/web/packages/Cubist/index.html) - Cubist：基于规则和实例的回归建模.
* [e1071](https://cran.r-project.org/web/packages/e1071/index.html) - e1071：维也纳工业大学统计系的其他职能 (e1071)
* [earth](https://cran.r-project.org/web/packages/earth/index.html) - 地球：多元自适应回归样条模型
* [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html) - elasticnet：用于稀疏估计和稀疏 PCA 的 Elastic-Net.
* [ElemStatLearn](https://cran.r-project.org/web/packages/ElemStatLearn/index.html) - ElemStatLearn：书中的数据集、函数和示例：“统计学习、数据挖掘、推理和预测的要素”，作者：Trevor Hastie、Robert Tibshirani 和 Jerome Friedman 预测”：作者：Trevor Hastie、Robert Tibshirani 和 Jerome Friedman.
* [evtree](https://cran.r-project.org/web/packages/evtree/index.html) - evtree：全局最优树的进化学习.
* [forecast](https://cran.r-project.org/web/packages/forecast/index.html) - 预测：使用 ARIMA、ETS、STLM、TBATS 和神经网络模型进行时间序列预测.
* [forecastHybrid](https://cran.r-project.org/web/packages/forecastHybrid/index.html) - ForecastHybrid：自动集成和交叉验证 ARIMA、ETS、STLM、TBATS 和“预测”包中的神经网络模型.
* [fpc](https://cran.r-project.org/web/packages/fpc/index.html) - fpc：灵活的聚类程序.
* [frbs](https://cran.r-project.org/web/packages/frbs/index.html)  - frbs：用于分类和回归任务的基于模糊规则的系统.  **[已弃用]**
* [GAMBoost](https://cran.r-project.org/web/packages/GAMBoost/index.html)  - GAMBoost：基于可能性的增强的广义线性和加性模型.  **[已弃用]**
* [gamboostLSS](https://cran.r-project.org/web/packages/gamboostLSS/index.html) - gamboostLSS：GAMLSS 的增强方法.
* [gbm](https://cran.r-project.org/web/packages/gbm/index.html) - gbm：广义提升回归模型.
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html) - glmnet：套索和弹性网络正则化广义线性模型.
* [glmpath](https://cran.r-project.org/web/packages/glmpath/index.html) - glmpath：广义线性模型和 Cox 比例风险模型的 L1 正则化路径.
* [GMMBoost](https://cran.r-project.org/web/packages/GMMBoost/index.html)  - GMMBoost：广义混合模型的基于似然的提升.  **[已弃用]**
* [grplasso](https://cran.r-project.org/web/packages/grplasso/index.html) - grplasso：使用组套索惩罚来拟合用户指定的模型.
* [grpreg](https://cran.r-project.org/web/packages/grpreg/index.html) - grpreg：具有分组协变量的回归模型的正则化路径.
* [h2o](https://cran.r-project.org/web/packages/h2o/index.html) - 大规模快速、并行和分布式机器学习算法的框架——深度学习、随机森林、GBM、KMeans、PCA、GLM.
* [hda](https://cran.r-project.org/web/packages/hda/index.html)  - hda：异方差判别分析.  **[已弃用]**
* [Introduction to Statistical Learning](https://www-bcf.usc.edu/~gareth/ISL/)
* [ipred](https://cran.r-project.org/web/packages/ipred/index.html) - ipred：改进的预测器.
* [kernlab](https://cran.r-project.org/web/packages/kernlab/index.html) - kernlab：基于内核的机器学习实验室.
* [klaR](https://cran.r-project.org/web/packages/klaR/index.html) - klaR：分类和可视化.
* [L0Learn](https://cran.r-project.org/web/packages/L0Learn/index.html) - L0Learn：最佳子集选择的快速算法.
* [lars](https://cran.r-project.org/web/packages/lars/index.html)  - lars：最小角度回归、套索和向前阶段.  **[已弃用]**
* [lasso2](https://cran.r-project.org/web/packages/lasso2/index.html) - lasso2：L1 约束估计又名“lasso”.
* [LiblineaR](https://cran.r-project.org/web/packages/LiblineaR/index.html) - LiblineaR：基于 Liblinear C/C++ 库的线性预测模型.
* [LogicReg](https://cran.r-project.org/web/packages/LogicReg/index.html) - LogicReg：逻辑回归.
* [Machine Learning For Hackers](https://github.com/johnmyleswhite/ML_for_Hackers)
* [maptree](https://cran.r-project.org/web/packages/maptree/index.html)  - maptree：映射、修剪和绘制树模型.  **[已弃用]**
* [mboost](https://cran.r-project.org/web/packages/mboost/index.html) - mboost: Model-Based Boosting.
* [medley](https://www.kaggle.com/general/3661) - medley：混合回归模型，使用贪婪的逐步方法.
* [mlr](https://cran.r-project.org/web/packages/mlr/index.html) - mlr：R 中的机器学习.
* [ncvreg](https://cran.r-project.org/web/packages/ncvreg/index.html) - ncvreg：SCAD 和 MCP 惩罚回归模型的正则化路径.
* [nnet](https://cran.r-project.org/web/packages/nnet/index.html)  - nnet：前馈神经网络和多项对数线性模型.  **[已弃用]**
* [pamr](https://cran.r-project.org/web/packages/pamr/index.html)  - pamr：Pam：微阵列的预测分析.  **[已弃用]**
* [party](https://cran.r-project.org/web/packages/party/index.html) - 聚会：递归分区实验室
* [partykit](https://cran.r-project.org/web/packages/partykit/index.html) - partykit：递归分区工具包.
* [penalized](https://cran.r-project.org/web/packages/penalized/index.html) - 惩罚：GLM 和 Cox 模型中的 L1（套索和融合套索）和 L2（岭）惩罚估计.
* [penalizedLDA](https://cran.r-project.org/web/packages/penalizedLDA/index.html)  - penalizedLDA：使用 Fisher 线性判别式进行惩罚分类.  **[已弃用]**
* [penalizedSVM](https://cran.r-project.org/web/packages/penalizedSVM/index.html) - penalizedSVM：使用惩罚函数的特征选择 SVM.
* [quantregForest](https://cran.r-project.org/web/packages/quantregForest/index.html) - quantregForest：分位数回归森林.
* [randomForest](https://cran.r-project.org/web/packages/randomForest/index.html) - randomForest：Breiman 和 Cutler 的用于分类和回归的随机森林.
* [randomForestSRC](https://cran.r-project.org/web/packages/randomForestSRC/index.html) - randomForestSRC：用于生存、回归和分类的随机森林 (RF-SRC).
* [rattle](https://cran.r-project.org/web/packages/rattle/index.html) -rattle：R 中数据挖掘的图形用户界面.
* [rda](https://cran.r-project.org/web/packages/rda/index.html) - rda: Shrunken Centroids Regularized Discriminant Analysis.
* [rdetools](https://cran.r-project.org/web/packages/rdetools/index.html)  - rdetools：特征空间中的相关维度估计（RDE）.  **[已弃用]**
* [REEMtree](https://cran.r-project.org/web/packages/REEMtree/index.html)  - REEMtree：对纵向（面板）数据具有随机效应的回归树.  **[已弃用]**
* [relaxo](https://cran.r-project.org/web/packages/relaxo/index.html)  - Relaxo：放松套索.  **[已弃用]**
* [rgenoud](https://cran.r-project.org/web/packages/rgenoud/index.html) - rgenoud：使用导数的遗传优化的 R 版本
* [Rmalschains](https://cran.r-project.org/web/packages/Rmalschains/index.html) - Rmalschains：在 R 中使用模因算法和本地搜索链 (MA-LS-Chains) 进行持续优化.
* [rminer](https://cran.r-project.org/web/packages/rminer/index.html)  - rminer：在分类和回归中更简单地使用数据挖掘方法（例如NN和SVM）.  **[已弃用]**
* [ROCR](https://cran.r-project.org/web/packages/ROCR/index.html)  - ROCR：可视化评分分类器的性能.  **[已弃用]**
* [RoughSets](https://cran.r-project.org/web/packages/RoughSets/index.html)  - RoughSets：使用粗糙集和模糊粗糙集理论进行数据分析.  **[已弃用]**
* [rpart](https://cran.r-project.org/web/packages/rpart/index.html) - rpart：递归分区和回归树.
* [RPMM](https://cran.r-project.org/web/packages/RPMM/index.html) - RPMM：递归分区混合模型.
* [RSNNS](https://cran.r-project.org/web/packages/RSNNS/index.html) - RSNNS：使用斯图加特神经网络模拟器 (SNNS) 的 R 神经网络.
* [RWeka](https://cran.r-project.org/web/packages/RWeka/index.html) - RWeka：R/Weka 接口.
* [RXshrink](https://cran.r-project.org/web/packages/RXshrink/index.html) - RXshrink：通过广义岭或最小角回归进行最大似然收缩.
* [sda](https://cran.r-project.org/web/packages/sda/index.html)  - sda：收缩判别分析和 CAT 分数变量选择.  **[已弃用]**
* [spectralGraphTopology](https://cran.r-project.org/web/packages/spectralGraphTopology/index.html) -spectralGraphTopology：通过谱约束从数据中学习图.
* [SuperLearner](https://github.com/ecpolley/SuperLearner) - 多算法集成学习包.
* [svmpath](https://cran.r-project.org/web/packages/svmpath/index.html)  - svmpath：svmpath：SVM 路径算法.  **[已弃用]**
* [tgp](https://cran.r-project.org/web/packages/tgp/index.html)  - tgp：贝叶斯树高斯过程模型.  **[已弃用]**
* [tree](https://cran.r-project.org/web/packages/tree/index.html) - 树：分类和回归树.
* [varSelRF](https://cran.r-project.org/web/packages/varSelRF/index.html) - varSelRF：使用随机森林进行变量选择.
* [XGBoost.R](https://github.com/tqchen/xgboost/tree/master/R-package) - 用于 eXtreme Gradient Boosting（树）库的 R 绑定.
* [Optunity](https://optunity.readthedocs.io/en/latest/)  - 一个致力于自动超参数优化的库，具有简单、轻量级的 API，以方便网格搜索的直接替换.  Optunity 用 Python 编写，但与 R 无缝连接.
* [igraph](https://igraph.org/r/) - 绑定到 igraph 库 - 通用图形库.
* [MXNet](https://github.com/apache/incubator-mxnet)  - 轻量级、便携式、灵活的分布式/移动深度学习，具有动态、突变感知数据流调度程序； 适用于 Python、R、Julia、Go、JavaScript 等.
* [TDSP-Utilities](https://github.com/Azure/Azure-TDSP-Utilities)  - Microsoft R 中的两个数据科学实用程序：1) 交互式数据探索、分析和报告 (IDEAR)；  2) 自动建模和报告（AMR）.

<a name="r-data-analysis--data-visualization"></a>
#### Data Manipulation | Data Analysis | Data Visualization

* [dplyr](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8) - 一个数据操作包，有助于解决最常见的数据操作问题.
* [ggplot2](https://ggplot2.tidyverse.org/) - 基于图形语法的数据可视化包.
* [tmap](https://cran.r-project.org/web/packages/tmap/vignettes/tmap-getstarted.html) 用于使用静态地图可视化地理空间数据和 [leaflet](https://rstudio.github.io/leaflet/) 用于交互式地图
* [tm](https://www.rdocumentation.org/packages/tm/) 和 [quanteda](https://quanteda.io/) are the main packages for managing,  analyzing, 和 visualizing textual data.
* [shiny](https://shiny.rstudio.com/) 是 R 中真正交互式显示和仪表板的基础.但是，可以通过以下方式实现某种程度的交互性： [htmlwidgets](https://www.htmlwidgets.org/) 将 javascript 库引入 R.其中包括， [plotly](https://plot.ly/r/), [dygraphs](http://rstudio.github.io/dygraphs), [highcharter](http://jkunst.com/highcharter/)，以及其他几个.

<a name="sas"></a>
## SAS

<a name="sas-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Visual Data Mining and Machine Learning](https://www.sas.com/en_us/software/visual-data-mining-machine-learning.html)  - 从数据准备到部署，在端到端分析环境中使用最新的机器学习算法进行交互式、自动化和编程建模. 可以免费试用.
* [Enterprise Miner](https://www.sas.com/en_us/software/enterprise-miner.html) - 使用 GUI 或代码创建可部署模型的数据挖掘和机器学习.
* [Factory Miner](https://www.sas.com/en_us/software/factory-miner.html) - 使用 GUI 自动创建跨众多市场或客户群的可部署机器学习模型.

<a name="sas-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [SAS/STAT](https://www.sas.com/en_us/software/stat.html) - 用于进行高级统计分析.
* [University Edition](https://www.sas.com/en_us/software/university-edition.html)  - 自由的！ 包括数据分析和可视化所需的所有 SAS 软件包，并包括在线 SAS 课程.

<a name="sas-natural-language-processing"></a>
#### Natural Language Processing

* [Contextual Analysis](https://www.sas.com/en_us/software/contextual-analysis.html) - 使用 GUI 将结构添加到非结构化文本.
* [Sentiment Analysis](https://www.sas.com/en_us/software/sentiment-analysis.html) - 使用 GUI 从文本中提取情感.
* [Text Miner](https://www.sas.com/en_us/software/text-miner.html) - 使用 GUI 或代码进行文本挖掘.

<a name="sas-demos-and-scripts"></a>
#### Demos and Scripts

* [ML_Tables](https://github.com/sassoftware/enlighten-apply/tree/master/ML_tables) - 包含机器学习最佳实践的简明备忘单.
* [enlighten-apply](https://github.com/sassoftware/enlighten-apply) - 说明 SAS 机器学习技术应用的示例代码和材料.
* [enlighten-integration](https://github.com/sassoftware/enlighten-integration) - 示例代码和材料，说明将 SAS 与 Java、PMML、Python 和 R 中的其他分析技术集成的技术.
* [enlighten-deep](https://github.com/sassoftware/enlighten-deep) - 说明在 SAS 中使用具有多个隐藏层的神经网络的示例代码和材料.
* [dm-flow](https://github.com/sassoftware/dm-flow) - SAS Enterprise Miner 流程​​图库可帮助您通过示例了解特定的数据挖掘主题.


<a name="scala"></a>
## Scala

<a name="scala-natural-language-processing"></a>
#### Natural Language Processing

* [ScalaNLP](http://www.scalanlp.org/) - ScalaNLP 是一套机器学习和数值计算库.
* [Breeze](https://github.com/scalanlp/breeze) - Breeze 是 Scala 的数值处理库.
* [Chalk](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library. **[Deprecated]**
* [FACTORIE](https://github.com/factorie/factorie)  - FACTORIE 是一个用于可部署概率建模的工具包，在 Scala 中作为软件库实现. 它为用户提供了一种简洁的语言，用于创建关系因子图、估计参数和执行推理.
* [Montague](https://github.com/Workday/upshot-montague) - Montague 是一个 Scala 语义解析库，具有易于使用的 DSL.
* [Spark NLP](https://github.com/JohnSnowLabs/spark-nlp) - 基于 Apache Spark ML 构建的自然语言处理库，为机器学习管道提供简单、高性能且准确的 NLP 注释，可在分布式环境中轻松扩展.

<a name="scala-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization

* [NDScala](https://github.com/SciScala/NDScala) - Scala 3 中的 N 维数组.想想 NumPy ndarray，但具有对形状、张量/轴标签和数字数据类型的编译时类型检查/推理
* [MLlib in Apache Spark](https://spark.apache.org/docs/latest/mllib-guide.html) - Spark中的分布式机器学习库
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - 用于将 Apache Spark MLLib 机器学习模型部署为实时、批处理或反应式 Web 服务的服务.
* [Scalding](https://github.com/twitter/scalding) - 用于级联的 Scala API.
* [Summing Bird](https://github.com/twitter/summingbird) - 带有 Scalding 和 Storm 的流式 MapReduce.
* [Algebird](https://github.com/twitter/algebird) - Scala 的抽象代数.
* [xerial](https://github.com/xerial/xerial)  - Scala 的数据管理实用程序.  **[已弃用]**
* [PredictionIO](https://github.com/apache/predictionio) - PredictionIO, a machine learning server for software developers and data engineers.
* [BIDMat](https://github.com/BIDData/BIDMat) - CPU 和 GPU 加速矩阵库，旨在支持大规模探索性数据分析.
* [Flink](https://flink.apache.org/) - 用于分布式流和批量数据处理的开源平台.
* [Spark Notebook](http://spark-notebook.io) - 使用 Scala 和 Spark 进行交互式和反应式数据科学.

<a name="scala-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Microsoft ML for Apache Spark](https://github.com/Azure/mmlspark) -&gt; 分布式机器学习框架 Apache Spark
* [ONNX-Scala](https://github.com/EmergentOrder/onnx-scala) - ONNX（开放神经网络交换）API 和后端，用于 Scala 中的类型化、功能性深度学习 (3).
* [DeepLearning.scala](https://deeplearning.thoughtworks.school/) - 从面向对象和函数式编程结构创建静态类型的动态神经网络.
* [Conjecture](https://github.com/etsy/Conjecture) - Scalding 中的可扩展机器学习.
* [brushfire](https://github.com/stripe/brushfire) - Scala 中的分布式决策树集成学习.
* [ganitha](https://github.com/tresata/ganitha)  - 烫手驱动的机器学习.  **[已弃用]**
* [adam](https://github.com/bigdatagenomics/adam)  - 使用 Apache Avro、Apache Spark 和 Parquet 构建的基因组处理引擎和专用文件格式.  Apache 2 已获得许可.
* [bioscala](https://github.com/bioscala/bioscala) - Scala 编程语言的生物信息学
* [BIDMach](https://github.com/BIDData/BIDMach) - CPU 和 GPU 加速的机器学习库.
* [Figaro](https://github.com/p2t2/figaro) - 用于构建概率模型的 Scala 库.
* [H2O Sparkling Water](https://github.com/h2oai/sparkling-water) - H2O 和 Spark 互操作性.
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/dev/libs/ml/index.html) - Flink 中的分布式机器学习库.
* [DynaML](https://github.com/transcendent-ai-labs/DynaML) - 用于机器学习研究的 Scala 库/REPL.
* [Saul](https://github.com/CogComp/saul) - 灵活的基于声明式学习的编程.
* [SwiftLearner](https://github.com/valdanylchuk/swiftlearner/) - 简单编写算法来帮助学习 ML 或编写您自己的实现.
* [Smile](https://haifengl.github.io/) - 统计机器智能和学习引擎.
* [doddle-model](https://github.com/picnicml/doddle-model)  - 构建在 Breeze 之上的内存机器学习库. 它提供不可变对象并通过类似 scikit-learn 的 API 公开其功能.
* [TensorFlow Scala](https://github.com/eaplatanios/tensorflow_scala) - 适用于 TensorFlow 的强类型 Scala API.

<a name="scheme"></a>
## Scheme

<a name="scheme-neural-networks"></a>
#### Neural Networks

* [layer](https://github.com/cloudkj/layer) - 从命令行进行神经网络推理，实现于 [CHICKEN Scheme](https://www.call-cc.org/).

<a name="swift"></a>
## Swift

<a name="swift-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

* [Bender](https://github.com/xmartlabs/Bender)  - 基于 Metal 构建的快速神经网络框架. 支持 TensorFlow 模型.
* [Swift AI](https://github.com/Swift-AI/Swift-AI) - 用 Swift 编写的高度优化的人工智能和机器学习库.
* [Swift for Tensorflow](https://github.com/tensorflow/swift) - 下一代机器学习平台，融合了机器学习、编译器、可微分编程、系统设计等方面的最新研究.
* [BrainCore](https://github.com/alejandro-isaza/BrainCore) - iOS 和 OS X 神经网络框架.
* [swix](https://github.com/stsievert/swix)  - 一个简单的库，包括通用矩阵语言并包装了一些用于 iOS 开发的 OpenCV.  **[已弃用]**
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - 用 Swift 编写的 AI 模块工具箱框架：图/树、线性回归、支持向量机、神经网络、PCA、KMeans、遗传算法、MDP、高斯混合.
* [MLKit](https://github.com/Somnibyte/MLKit)  - 用 Swift 编写的简单机器学习框架. 目前具有简单线性回归、多项式回归和岭回归功能.
* [Swift Brain](https://github.com/vlall/Swift-Brain) - The first neural network / machine learning library written in Swift. This is a project for AI algorithms in Swift for iOS and OS X development. This project includes algorithms focused on Bayes theorem, neural networks, SVMs, Matrices, etc...
* [Perfect TensorFlow](https://github.com/PerfectlySoft/Perfect-TensorFlow)  - TensorFlow 的 Swift 语言绑定. 在 macOS / Linux 上使用原生 TensorFlow 模型.
* [PredictionBuilder](https://github.com/denissimon/prediction-builder-swift) - 使用线性回归构建预测的机器学习库.
* [Awesome CoreML](https://github.com/SwiftBrain/awesome-CoreML-models) - 预训练 CoreML 模型的精选列表.
* [Awesome Core ML Models](https://github.com/likedan/Awesome-CoreML-Models) - CoreML 格式的机器学习模型精选列表.

<a name="tensorflow"></a>
## TensorFlow

<a name="tensorflow-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [Awesome Keras](https://github.com/markusschanta/awesome-keras) - A curated list of awesome Keras projects, libraries and resources.
* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - 与 TensorFlow 相关的所有内容的列表.

<a name="tools"></a>
## Tools

<a name="tools-neural-networks"></a>
#### Neural Networks
* [layer](https://github.com/cloudkj/layer) - 从命令行进行神经网络推理

<a name="tools-misc"></a>
#### Misc

* [Humanloop](https://humanloop.com) – Humanloop 是一个用于快速实验、微调模型以获得更好性能、成本优化以及收集模型生成的数据和用户反馈的平台.
* [Qdrant](https://qdrant.tech) – Qdrant 是 [open source](https://github.com/qdrant/qdrant) 具有扩展过滤支持的矢量相似性搜索引擎，用 Rust 编写.
* [milvus](https://milvus.io) - 他是一只风筝 [open source](https://github.com/milvus-io/milvus) 用于生产 AI 的向量数据库，用 Go 和 C++ 编写，可扩展且速度极快，可容纳数十亿个嵌入向量.
* [Weaviate](https://www.semi.technology/developers/weaviate/current/) – Weaviate 是一个 [open source](https://github.com/semi-technologies/weaviate) 矢量搜索引擎和矢量数据库.  Weaviate 使用机器学习来矢量化​​和存储数据，并找到自然语言查询的答案. 借助 Weaviate，您还可以将自定义 ML 模型投入生产规模.
* [txtai](https://github.com/neuml/txtai) - 构建语义搜索应用程序和工作流程.
* [MLReef](https://about.mlreef.com/) - MLReef 是一个端到端开发平台，利用 git 的强大功能为 ML 开发流程提供结构和深度协作的可能性.
* [Pinecone](https://www.pinecone.io/) - 用于需要实时、可扩展矢量嵌入和相似性搜索的应用程序的矢量数据库.
* [CatalyzeX](https://chrome.google.com/webstore/detail/code-finder-for-research/aikkeehnlfpamidigaffhfmgbkdeheil) - 浏览器扩展（[Chrome](https://chrome.google.com/webstore/detail/code-finder-for-research/aikkeehnlfpamidigaffhfmgbkdeheil) 和 [Firefox](https://addons.mozilla.org/en-US/firefox/addon/code-finder-catalyzex/)) that automatically finds 和 shows code implementations for machine learning papers anywhere: Google, Twitter, Arxiv, Scholar, etc.
* [ML Workspace](https://github.com/ml-tooling/ml-workspace)  - 用于机器学习和数据科学的基于 Web 的一体化 IDE. 工作区部署为 Docker 容器，并预加载了各种流行的数据科学库（例如 Tensorflow、PyTorch）和开发工具（例如 Jupyter、VS Code）.
* [Notebooks](https://github.com/rlan/notebooks)  - Jupyter 笔记本和机器学习的入门套件. 配套 docker 镜像由 python 版本、机器学习框架（Keras、PyTorch 和 Tensorflow）和 CPU/CUDA 版本的所有组合组成.
* [DVC](https://github.com/iterative/dvc)  - 数据科学版本控制是一个开源版本控制系统，适用于具有管道支持的机器学习项目. 它使机器学习项目具有可复制性和可共享性.
* [DVClive](https://github.com/iterative/dvclive) - 用于将实验指标记录到简单格式的本地文件中的 Python 库.
* [VDP](https://github.com/instill-ai/vdp) - 开源视觉数据 ETL，以简化端到端视觉数据处理流程：从预构建的数据源中提取非结构化视觉数据，通过从各种机器学习平台导入的 Vision AI 模型将其转换为可分析的结构化见解，并加载见解进入仓库或应用程序.
* [Kedro](https://github.com/quantumblacklabs/kedro/) - Kedro 是一个数据和开发工作流程框架，它实现数据管道的最佳实践，着眼于生产机器学习模型.
* [guild.ai](https://guild.ai/)  - 记录、分析、比较和“优化”实验的工具. 它是跨平台和独立框架的，并提供集成的可视化工具，例如张量板.
* [Sacred](https://github.com/IDSIA/sacred)  - Python 工具可帮助您配置、组织、记录和重现实验. 就像化学/生物学背景下的笔记本实验室一样. 社区已经利用提议的标准构建了多个附加组件.
* [Comet](https://www.comet.com/)  - 用于跟踪实验、超参数、工件等的 ML 平台. 它与超过 15 个以上的深度学习框架和编排工具深度集成. 用户还可以使用该平台来监控生产中的模型.
* [MLFlow](https://mlflow.org/)  - 管理机器学习生命周期的平台，包括实验、再现性和部署. 与框架和语言无关，请查看所有内置集成.
* [Weights & Biases](https://www.wandb.com/) - 机器学习实验跟踪、数据集版本控制、超参数搜索、可视化和协作
* 更多改善机器学习生命周期的工具： [Catalyst](https://github.com/catalyst-team/catalyst), [PachydermIO](https://www.pachyderm.io/) . 以下是类似 GitHub 和目标团队 [Weights & Biases](https://www.wandb.com/), [Neptune.ai](https://neptune.ai/), [Comet.ml](https://www.comet.ml/), [Valohai.ai](https://valohai.com/), [DAGsHub](https://DAGsHub.com/).
* [Arize AI](https://www.arize.com) - 跨结构化和非结构化数据的模型验证和性能监控、偏差检测、可解释性、可视化
* [MachineLearningWithTensorFlow2ed](https://www.manning.com/books/machine-learning-with-tensorflow-second-edition) - 一本关于通用机器学习技术回归、分类、无监督聚类、强化学习、自动编码器、卷积神经网络、RNN、LSTM 的书，使用 TensorFlow 1.14.1.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A tool that allows the conversion of ML models into native code (Java, C, Python, Go, JavaScript, Visual Basic, C#, R, PowerShell, PHP, Dart) with zero dependencies.
* [CML](https://github.com/iterative/cml)  - 用于与 ML 项目进行持续集成的库. 使用 GitHub Actions 和 GitLab CI 在类似生产环境中训练和评估模型，并自动生成包含拉取/合并请求中的指标和图表的可视化报告. 与框架和语言无关.
* [Pythonizr](https://pythonizr.com) - 一个在线工具，用于生成使用 scikit-learn 的样板机器学习代码.
* [Flyte](https://flyte.org/) - Flyte 可以轻松地为机器学习和数据处理创建并发、可扩展且可维护的工作流程.
* [Chaos Genius](https://github.com/chaos-genius/chaos_genius/) - 机器学习驱动的分析引擎，用于异常值/异常检测和根本原因分析.
* [MLEM](https://github.com/iterative/mlem) - 按照 GitOps 原则版本和部署 ML 模型
* [DockerDL](https://github.com/matifali/dockerdl) - 准备使用深度学习 docker 镜像.
* [Aqueduct](https://github.com/aqueducthq/aqueduct) - Aqueduct 使您能够在任何云基础设施上轻松定义、运行和管理 AI 和 ML 任务.
* [Ambrosia](https://github.com/reactorsh/ambrosia) - Ambrosia 帮助您使用_其他_ LLM 清理您的 LLM 数据集.

<a name="books"></a>
## Books

* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns)   - 本书教您如何将机器学习模型从个人笔记本电脑转移到大型分布式集群. 您将探索成功的分布式机器学习系统背后的关键概念和模式，并直接从关键维护者和贡献者那里通过真实场景和实践项目学习 TensorFlow、Kubernetes、Kubeflow 和 Argo 工作流等技术.
* [Grokking Machine Learning](https://www.manning.com/books/grokking-machine-learning) - Grokking 机器学习教您如何仅使用标准 Python 代码和高中水平的数学将机器学习应用到您的项目中.
* [Machine Learning Bookcamp](https://www.manning.com/books/machine-learning-bookcamp) - 通过完成一组精心设计的现实项目来学习机器学习的基础知识.
* [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1098125975)  - 通过最近的一系列突破，深度学习推动了整个机器学习领域的发展. 现在，即使是对这项技术几乎一无所知的程序员也可以使用简单、高效的工具来实现能够从数据中学习的程序. 这本畅销书使用具体示例、最少的理论和可用于生产的 Python 框架（Scikit-Learn、Keras 和 TensorFlow）来帮助您直观地了解构建智能系统的概念和工具.


<a name="credits"></a>
* [Netron](https://netron.app/) - 用于神经网络、深度学习和机器学习模型的开源查看器
* [Teachable Machine](https://teachablemachine.withgoogle.com/) - 动态训练机器学习模型来识别您自己的图像、声音和姿势.
* [Model Zoo](https://modelzoo.co/) - 发现开源深度学习代码和预训练模型.

## Credits

* 一些Python库是从 [vinta](https://github.com/vinta/awesome-python)
* Go 的参考资料大部分是从 [gopherdata](https://github.com/gopherdata/resources/tree/master/tooling)
