<div class="github-widget" data-repo="iipc/awesome-web-archiving"></div>
<!--lint ignore awesome-github-->
## Awesome Web Archiving [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

网络归档是收集万维网部分内容的过程，以确保信息保存在档案中，供未来的研究人员、历史学家和公众使用. 由于网络规模庞大，网络档案管理员通常使用网络爬虫进行自动捕获. 不断发展的 Web 标准要求归档工具不断发展，以跟上 Web 技术的变化，以确保可靠且有意义地捕获和重放已归档的网页.




## Training/Documentation

* 网络归档概念介绍：
  * [What is a web archive?](https://youtu.be/ubDHY-ynWi0) - 视频来自 [the UK Web Archive YouTube Channel](https://www.youtube.com/channel/UCJukhTSw8VRj-VNTpBcqWkw)
  * [Wikipedia's List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives)
  * [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
  * [The Web Archiving Lifecycle Model](https://archive-it.org/blog/post/announcing-the-web-archiving-life-cycle-model/)  - 网络归档生命周期模型试图将网络归档的技术和程序化部分合并到一个框架中，该框架与任何寻求从网络归档内容的组织相关.  Archive-It 是互联网档案馆的网络归档服务，根据与世界各地的记忆机构的合作开发了该模型.
  * [Retrieving and Archiving Information from Websites by Wael Eskandar and Brad Murray](https://kit.exposingtheinvisible.org/en/web-archive.html/)
* 培训教材：
  * [IIPC and DPC Training materials: module for beginners (8 sessions)](https://netpreserve.org/web-archiving/training-materials/)
  * [UNT Web Archiving Course 2022](https://github.com/vphill/web-archiving-course)
  * [Continuing Education to Advance Web Archiving (CEDWARC)](https://cedwarc.github.io/)
* WARC 标准：
  * 这 [warc-specifications](https://iipc.github.io/warc-specifications/) 社区 HTML 版本的官方规范和新提案中心.
  * 这 [offical ISO 28500 WARC specification homepage](http://bibnum.bnf.fr/WARC/).
* 对于使用网络档案的研究人员：
  * [GLAM Workbench: Web Archives](https://glam-workbench.github.io/web-archives/) - 也可以看看 [this related blog post on 'Asking questions with web archives'](https://netpreserveblog.wordpress.com/2020/05/28/asking-questions-with-web-archives/).
  * [Archives Unleashed Toolkit documentation](https://aut.docs.archivesunleashed.org/)
  * [Tutorial for Humanities researchers about how to explore Arquivo.pt](https://sobre.arquivo.pt/en/tutorial-for-humanities-researchers-about-how-to-use-arquivo-pt/)

## Resources for Web Publishers

当与在网络上发布内容并希望确保其网站可以存档的个人或组织合作时，这些资源可以提供帮助.

* [Stanford Libraries' Archivability pages](https://library.stanford.edu/projects/web-archiving/archivability)
* 这 [Archive Ready](http://archiveready.com/) 工具，用于估计网页成功存档的可能性.


## Tools & Software

此工具和软件列表旨在简要描述一些与网络归档相关的最重要和最广泛使用的工具. 有关更多详细信息，我们建议您参考（并贡献！）来自其他团体的这些优秀资源：
* [Comparison of web archiving software](https://github.com/archivers-space/research/tree/master/web_archiving)
* [Awesome Website Change Monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)

### Acquisition

* [ArchiveBox](https://github.com/pirate/ArchiveBox)  - 使用 wget、Chrome headless 和其他方法维护 RSS 提要、书签和链接的附加存档的工具（以前称为“书签存档器”）.  *（开发中）*
* [archivenow](https://github.com/oduwsdl/archivenow) - A [Python library](http://ws-dl.blogspot.com/2017/02/2017-02-22-archive-now-archivenow.html) 将网络资源推送到按需网络档案中.  *（稳定的）*
* [ArchiveWeb.Page](https://archiveweb.page)  - 适用于 Chrome 和其他基于 Chromium 的浏览器的插件，可让您以交互方式存档网页、重播网页并将其导出为 WARC 数据. 也可作为基于 Electron 的桌面应用程序使用.
* [Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler) - 基于 Chrome 的高保真爬行系统，旨在在单个 Docker 容器中运行复杂的、可定制的基于浏览器的爬行.
* [Brozzler](https://github.com/internetarchive/brozzler)  - 分布式网络爬虫（爬虫），使用真实的浏览器（Chrome 或 Chromium）来获取页面和嵌入的 url 并提取链接.  *（稳定的）*
* [Cairn](https://github.com/wabarc/cairn)  - 用于保存网页的 npm 包和 CLI 工具.  *（稳定的）*
* [Chronicler](https://github.com/CGamesPlay/chronicler)  - 具有记录和重播功能的网络浏览器.  *（开发中）*
* [crau](https://github.com/turicas/crau)  - crau 是（大多数）巴西人发音“crawl”的方式，它是用于归档网络和播放档案的最简单的命令行工具：您只需要一个 URL 列表.  *（稳定的）*
* [Crawl](https://git.autistici.org/ale/crawl)  - Golang 中的一个简单的网络爬虫.  *（稳定的）*
* [crocoite](https://github.com/promyloph/crocoite)  - 使用无头 Google Chrome/Chromium 抓取网站，并将资源、静态 DOM 快照和页面屏幕截图保存到 WARC 文件中.  *（开发中）*
* [DiskerNet](https://github.com/dosyago/DiskerNet)  - 一种非基于 WARC 的工具，可连接到 Chrome 浏览器并存档您浏览的所有内容，使其可用于离线重播.  *（开发中）*
* [F(b)arc](https://github.com/justinlittman/fbarc) - 用于归档数据的命令行工具和 Python 库 [Facebook](https://www.facebook.com/) 使用 [Graph API](https://developers.facebook.com/docs/graph-api) .  *（稳定的）*
* [freeze-dry](https://github.com/WebMemex/freeze-dry)  - JavaScript 库将页面转换为静态、独立的 HTML 文档； 对于浏览器扩展很有用.  *（开发中）*
* [grab-site](https://github.com/ArchiveTeam/grab-site)  - 档案管理员的网络爬虫：WARC 输出、所有爬网的仪表板、动态忽略模式.  *（稳定的）*
* [Heritrix](https://github.com/internetarchive/heritrix3/wiki)  - 开源、可扩展、网络规模、存档质量的网络爬虫.  *（稳定的）*
  * [Heritrix Q&A](https://github.com/internetarchive/heritrix3/discussions/categories/q-a) - 一个讨论论坛，用于提出有关使用 Heritrix 的问题并获得答案.
  * [Heritrix Walkthrough](https://github.com/web-archive-group/heritrix-walkthrough) *（开发中）*
* [html2warc](https://github.com/steffenfritz/html2warc)  - 一个简单的脚本，用于将离线数据转换为单个 WARC 文件.  *（稳定的）*
* [HTTrack](http://www.httrack.com/)  - 一个开源网站复制实用程序.  *（稳定的）*
* [monolith](https://github.com/Y2Z/monolith)  - 用于将网页保存为单个 HTML 文件的 CLI 工具.  *（稳定的）*
* [Obelisk](https://github.com/go-shiori/obelisk)  - Go 包和 CLI 工具，用于将网页保存为单个 HTML 文件.  *（稳定的）*
* [Scoop](https://github.com/harvard-lil/scoop)  - 高保真、基于浏览器的单页网络存档库和 CLI，用于见证网络.  *（稳定的）*
* [SingleFile](https://github.com/gildas-lormeau/SingleFile)  - Firefox/Chrome 浏览器扩展和 CLI 工具可将完整页面的忠实副本保存为单个 HTML 文件.  *（稳定的）*
* [SiteStory](http://mementoweb.github.com/SiteStory/)  - 事务存档，有选择地捕获和存储 Web 客户端（浏览器）和 Web 服务器之间发生的事务.  *（稳定的）*
* [Social Feed Manager](https://gwu-libraries.github.io/sfm-ui/)  - 开源软件，使用户能够从 Twitter、Tumblr、Flickr 和新浪微博公共 API 创建社交媒体集合.  *（稳定的）*
* [Squidwarc](https://github.com/N0taN3rd/Squidwarc) - 一个 [open source, high-fidelity, page interacting](http://ws-dl.blogspot.com/2017/07/2017-07-24-replacing-heritrix-with.html) 直接使用 Chrome 或 Chrome Headless 的档案爬虫.  *（开发中）*
* [StormCrawler](http://stormcrawler.net/)  - 用于在 Apache Storm 上构建低延迟、可扩展的网络爬虫的资源集合.  *（稳定的）*
* [twarc](https://github.com/docnow/twarc)  - 用于归档 Twitter JSON 数据的命令行工具和 Python 库.  *（稳定的）*
* [WAIL](https://github.com/machawk1/wail) - 多个网络归档工具之上的图形用户界面（GUI），旨在为任何人提供保存和重播网页的简单方法； [Python](https://machawk1.github.io/wail/), [Electron](https://github.com/n0tan3rd/wail) .  *（稳定的）*
* [Warcprox](https://github.com/internetarchive/warcprox)  - WARC 编写 MITM HTTP/S 代理.  *（稳定的）*
* [WARCreate](http://matkelly.com/warcreate/) - A [Google Chrome](https://www.google.com/intl/en/chrome/browser/) 用于将单个网页或网站存档到 WARC 文件的扩展名.  *（稳定的）*
* [Warcworker](https://github.com/peterk/warcworker)  - 一个开源、dockerized、排队、高保真 Web 存档器，基于 Squidwarc，具有简单的 Web GUI.  *（稳定的）*
* [Wayback](https://github.com/wabarc/wayback)  - 用于将网页快照到 Internet Archive、archive.today、IPFS 等的工具包.  *（稳定的）*
* [Waybackpy](https://github.com/akamhy/waybackpy) - Python 中的 Wayback Machine Save、CDX 和可用性 API 接口以及命令行工具 *（稳定）*
* [Web2Warc](https://github.com/helgeho/Web2Warc) - An easy-to-use and highly customizable crawler that enables anyone to create their own little Web archives (WARC/CDX). *(Stable)*
* [Web Curator Tool](https://webcuratortool.org)  - 用于选择性网络存档的开源工作流程管理.  *（稳定的）*
* [WebMemex](https://github.com/WebMemex)  - 适用于 Firefox 和 Chrome 的浏览器扩展，可让您存档您访问的网页.  *（开发中）*
* [Webrecorder](https://webrecorder.io/)  - 创建您浏览的任何网站的高保真交互式录音.  *（稳定的）*
* [Wget](http://www.gnu.org/software/wget/) - 一个开源文件检索实用程序 [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output) .  *（稳定的）*
* [Wget-lua](https://github.com/alard/wget-lua)  - 带 Lua 扩展的 Wget.  *（稳定的）*
* [Wpull](https://github.com/chfoo/wpull)  - Wget 兼容（或重制/克隆/替换/替代）网络下载器和爬虫.  *（稳定的）*

### Replay

* [InterPlanetary Wayback (ipwb)](https://github.com/oduwsdl/ipwb) - 使用 Web Archive (WARC) 索引和重放 [IPFS](https://ipfs.io/).
* [OpenWayback](https://github.com/iipc/openwayback/)  - 该开源项目旨在开发 Wayback Machine，这是全球网络档案馆用来在用户浏览器中回放存档网站的关键软件.  *（稳定的）*
* [PyWb](https://github.com/ikreymer/pywb)  - Web 档案重放工具的 Python（2 和 3）实现，有时也称为“Wayback Machine”.  *（稳定的）*
* [Reconstructive](https://oduwsdl.github.io/Reconstructive/) - Reconstructive 是一个 ServiceWorker 模块，用于通过将资源请求重新路由到相应的存档副本 (JavaScript) 来客户端重建复合纪念品.
* [ReplayWeb.Page](https://replayweb.page/) - 基于浏览器的完全客户端重播引擎，适用于本地和远程 WARC 文件.
* [warc2html](https://github.com/iipc/warc2html) - 将 WARC 文件转换为适合离线浏览或重新托管的静态 HTML.

### Search & Discovery

* [Mink](https://github.com/machawk1/mink) - A [Google Chrome](https://www.google.com/intl/en/chrome/) 用于在浏览和集成实时存档的网络导航时查询 Memento 聚合器的扩展.  *（稳定的）*
<!--lint ignore double-link-->
* [playback](https://github.com/wabarc/playback) - 用于搜索存档网页的工具包 [Internet Archive](https://web.archive.org), [archive.today](https://archive.today), [Memento](http://timetravel.mementoweb.org) 超越.  *（开发中）*
* [SecurityTrails](https://securitytrails.com/)  - 基于网络的 WHOIS 和 DNS 记录存档. 免费提供 REST API.
* [Tempas v1](http://tempas.L3S.de/v1) - 基于时态网络档案搜索 [Delicious](https://en.wikipedia.org/wiki/Delicious_(website) ）标签.  *（稳定的）*
* [Tempas v2](http://tempas.L3S.de/v2) - 基于 1996 年至 2013 年从德国网络中提取的链接和锚文本的时态网络档案搜索（结果不限于德语页面，例如， [Obama@2005-2009 in Tempas](http://tempas.l3s.de/v2/query?q=obama&from=2005&to=2009) ）.  *（稳定的）*
* [webarchive-discovery](https://github.com/ukwa/webarchive-discovery)  - WARC 和 ARC 全文索引和发现工具，以及许多能够使用如下所示索引的相关工具.  *（稳定的）*
  * [Shine](https://github.com/ukwa/shine) - 与研究人员一起开发的原型网络档案探索 UI，作为 [Big UK Domain Data for the Arts and Humanities project](https://buddah.projects.history.ac.uk/) .  *（稳定的）*
  * [SolrWayback](https://github.com/netarchivesuite/solrwayback)  - 后端 Java 和前端 VUE JS 项目，具有自由文本搜索和内置播放引擎. 要求 Warc 文件已使用 Warc-Indexer 建立索引. 该网络应用程序还具有广泛的数据可视化工具和数据导出工具，可以在整个网络存档上使用. [SolrWayback 4 Bundle release](https://github.com/netarchivesuite/solrwayback/releases) 包含易于安装的开箱即用解决方案中的所有软件和依赖项.
  * [Warclight](https://github.com/archivesunleashed/warclight)  - 基于 Project Blacklight 的 Rails 引擎，支持发现以 WARC 和 ARC 格式保存的 Web 档案.  *（开发中）*
  * [Wasp](https://github.com/webis-de/wasp) - 个人的功能齐全的原型 [web archive and search system](http://ceur-ws.org/Vol-2167/paper6.pdf) .  *（开发中）*
  * 构建前端的其他可能选项列在“webarchive-discovery”wiki 中， [here](https://github.com/ukwa/webarchive-discovery/wiki/Front-ends).

### Utilities

* [ArchiveTools](https://github.com/recrm/ArchiveTools) - 用于提取 WARC 文件并与之交互的工具集合 (Python).
<!--lint ignore double-link-->
* [cdx-toolkit](https://pypi.org/project/cdx-toolkit/)  - 用于查阅 cdx 索引并创建子集的 WARC 提取的库和 CLI. 抽象出 Common Crawl 不寻常的爬行结构.  *（稳定的）*
* [Go Get Crawl](https://github.com/karust/gogetcrawl) - 使用提取网络存档数据 [Wayback Machine](https://web.archive.org/) 和 [Common Crawl](https://commoncrawl.org/) .  *（稳定的）*
* [gowarcserver](https://github.com/nlnwa/gowarcserver) - [BadgerDB](https://github.com/dgraph-io/badger)基于捕获索引（CDX）和WARC记录服务器，用于索引和服务WARC文件（Go）.
* [har2warc](https://github.com/webrecorder/har2warc) - 转换 HTTP 存档 (HAR) -&gt; Web 存档 (WARC) 格式 (Python).
* [httpreserve.info](http://httpreserve.info/)  - 返回网页状态或将其保存到互联网档案馆的服务. 使用 GET（Golang 包）通过浏览器或命令行通过 CURL 返回 JSON.  *（稳定的）*
* [HTTPreserve Workbench](https://github.com/httpreserve/workbench)  - 用于描述网页状态的工具和 API，以简单的 JSON 输出编码，描述当前状态以及 wayback.org 上最早和最新的链接. 将网页保存到互联网档案馆. 审核 URI 列表并输出包含上述数据的 CSV (Golang).  *（开发中）*
* [httrack2warc](https://github.com/nla/httrack2warc) - 将 HTTrack 存档转换为 WARC 格式 (Java).
* [MementoMap](https://github.com/oduwsdl/MementoMap)  - 总结网络档案馆藏的工具（Python）.  *（开发中）*
* [MemGator](https://github.com/oduwsdl/MemGator)  - Memento 聚合器 CLI 和服务器 (Golang).  *（稳定的）*
* [node-cdxj](https://github.com/N0taN3rd/node-cdxj) - [CDXJ](https://github.com/oduwsdl/ORS/wiki/CDXJ) 文件解析器 (Node.js).  *（稳定的）*
* [OutbackCDX](https://github.com/nla/outbackcdx)  - 基于 RocksDB 的捕获索引 (CDX) 服务器支持增量更新和压缩. 可用作 OpenWayback、PyWb 和 [Heritrix](https://github.com/ukwa/ukwa-heritrix/blob/master/src/main/java/uk/bl/wap/modules/uriuniqfilters/OutbackCDXRecentlySeenUriUniqFilter.java) .  *（稳定的）*
* [py-wasapi-client](https://github.com/unt-libraries/py-wasapi-client)  - 用于从 WASAPI (Python) 下载爬网的命令行应用程序.  *（稳定的）*
* [tikalinkextract](https://github.com/httpreserve/tikalinkextract)  - 从可由 Apache Tika（Golang、Apache Tika Server）解析的文档类型文件夹中提取超链接作为 Web 归档的种子.  *（开发中）*
* [wasapi-downloader](https://github.com/sul-dlss/wasapi-downloader)  - 用于从 WASAPI 下载爬网的 Java 命令行应用程序.  *（稳定的）*
* [Warchaeology](https://nlnwa.github.io/warchaeology/)  - Warchaeology 是用于检查、操作、重复数据删除和验证 WARC 文件的工具集合.  *稳定的*
* [warcdedupe](https://gitlab.com/taricorp/warcdedupe)  - 用 Rust 编写的 WARC 重复数据删除工具（和 WARC 库）.  （开发中）
* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner)  - 按 MIME 类型和年份对 (W)ARC 文件进行分区.  *（稳定的）*
* [warcrefs](https://github.com/arcalex/warcrefs)  - 网络存档重复数据删除工具.  *稳定的*
* [webarchive-indexing](https://github.com/ikreymer/webarchive-indexing) - 用于在 Hadoop、EMR 或本地文件系统上对 WARC/ARC 文件进行批量索引的工具.
* [wikiteam](https://github.com/WikiTeam/wikiteam)  - 下载和保存维基的工具.  *（稳定的）*

### WARC I/O Libraries

* [FastWARC](https://github.com/chatnoir-eu/chatnoir-resiliparse) - 高性能 WARC 解析库（Python）.
* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz)  - 用于串联 GZIP 文件（和“*.warc.gz”）的可拆分 Hadoop 输入格式.  *（稳定的）*
* [jwarc](https://github.com/iipc/jwarc) - 使用类型安全 API (Java) 读取和写入 WARC 文件.
* [Jwat](https://sbforge.org/display/JWAT/JWAT)  - 用于读取/写入/验证 WARC/ARC/GZIP 文件 (Java) 的库和工具.  *（稳定的）*
* [node-warc](https://github.com/N0taN3rd/node-warc) - 解析 WARC 文件或使用以下任一方法创建 WARC 文件 [Electron](https://electron.atom.io/) 或者 [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface)  （Node.js）.  *（稳定的）*
* [Sparkling](https://github.com/internetarchive/Sparkling)  - 互联网档案馆的闪闪发光的数据处理库.  *（稳定的）*
* [Unwarcit](https://github.com/emmadickson/unwarcit) - 用于解压缩 WARC 和 WACZ 文件的命令行界面 (Python).
* [Warcat](https://github.com/chfoo/warcat)  - 用于处理 Web ARChive (WARC) 文件的工具和库 (Python).  *（稳定的）*
* [warcio](https://github.com/webrecorder/warcio)  - 用于快速 Web 存档 IO 的流式 WARC/ARC 库 (Python).  *（稳定的）*
* [warctools](https://github.com/internetarchive/warctools) - 用于处理 ARC 和 WARC 文件的库 (Python).
* [webarchive](https://github.com/richardlehane/webarchive) - ARC 和 WARC 网络存档格式的 Golang 阅读器（Golang）.

### Analysis

* [Archives Research Compute Hub](https://github.com/internetarchive/arch)  - 用于 Archive-It Web 档案馆藏的分布式计算分析的 Web 应用程序.  *（稳定的）*
* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark)  - 用于 Web Archives 的 Apache Spark 框架（不仅如此），可以轻松进行数据处理、提取和派生.  *（稳定的）*
* [Archives Unleashed Notebooks](https://github.com/archivesunleashed/notebooks)  - 用于使用 Archives Unleashed Toolkit 处理网络档案的笔记本，以及由 Archives Unleashed Toolkit 生成的衍生产品.  *（稳定的）*
* [Archives Unleashed Toolkit](https://github.com/archivesunleashed/aut)  - Archives Unleashed Toolkit (AUT) 是一个使用 Apache Spark 分析 Web 档案的开源平台.  *（稳定的）*
* [Common Crawl Columnar Index](https://commoncrawl.org/tag/columnar-index/)  - SQL 可查询索引，带有 CDX 信息和语言分类.  *（稳定的）*
* [Common Crawl Web Graph](https://commoncrawl.org/category/web-graph/)  - 带有排名信息的主机或域级网络图表.  *（稳定的）*
* [Common Crawl Jupyter notebooks](https://github.com/commoncrawl/cc-notebooks)  - 使用 Common Crawl 的各种数据集的笔记本集合.  *（稳定的）*
* [Tweet Archvies Unleashed Toolkit](https://github.com/archivesunleashed/twut)  - 一个开源工具包，用于使用 Apache Spark 分析面向行的 JSON Twitter 档案.  *（开发中）*
* [Web Data Commons](http://webdatacommons.org/)  - 从 Common Crawl 中提取的结构化数据.  *（稳定的）*

### Quality Assurance

* [Chrome Check My Links](https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) - 浏览器扩展：具有更多选项的链接检查器.
* [Chrome link checker](https://chrome.google.com/webstore/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) - 浏览器扩展：基本链接检查器.
* [Chrome link gopher](https://chrome.google.com/webstore/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US&gl=US) - 浏览器扩展：页面上的链接收集器.
* [Chrome Open Multiple URLs](https://chrome.google.com/webstore/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) - 浏览器扩展：打开多个 URL 并从文本中提取 URL.
* [Chrome Revolver](https://chrome.google.com/webstore/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) - 浏览器扩展：在浏览器选项卡之间切换.
* [FlameShot](https://github.com/lupoDharkael/flameshot) - Ubuntu 上的屏幕截图和注释.
* [PlayOnLinux](https://www.playonlinux.com/en/) - 用于在 Ubuntu 上运行 Xenu 和 Notepad++.
* [PlayOnMac](https://www.playonmac.com/en/) - 用于在 macOS 上运行 Xenu 和 Notepad++.
* [Windows Snipping Tool](https://support.microsoft.com/en-gb/help/13776/windows-use-snipping-tool-to-capture-screenshots)  - 内置 Windows，用于部分屏幕捕获和注释. 在 macOS 上，您可以使用 Command + Shift + 4（用于截取部分屏幕的键盘快捷键）.
* [WineBottler](http://winebottler.kronenberg.org/) - 用于在 macOS 上运行 Xenu 和 Notepad++.
* [xDoTool](https://github.com/jordansissel/xdotool) - 单击 Ubuntu 上的自动化.
* [Xenu](http://home.snafu.de/tilman/xenulink.html) - Windows 桌面链接检查器.

### Curation

* [Zotero Robust Links Extension](https://robustlinks.mementoweb.org/zotero/) - A [Zotero](https://www.zotero.org/) 提交到网络档案并从中读取的扩展. 来源 [on GitHub](https://github.com/lanl/Zotero-Robust-Links-Extension) . 取代 [leonkt/zotero-memento](https://github.com/leonkt/zotero-memento).

## Community Resources

### Other Awesome Lists

* [Web Archiving Community](https://github.com/pirate/ArchiveBox/wiki/Web-Archiving-Community)
* [Awesome Memento](https://github.com/machawk1/awesome-memento)
* [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
* [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)

### Blogs and Scholarship

* [IIPC Blog](https://netpreserveblog.wordpress.com/)
* [Web Archiving Roundtable](https://webarchivingrt.wordpress.com/) - 网络归档圆桌会议的非官方博客 [Society of American Archivists](https://www2.archivists.org/) 由网络归档圆桌会议的成员维护.
* [The Web as History](https://www.uclpress.co.uk/products/84010) - 一本开源书籍，提供网络归档研究的概念概述以及几个案例研究.
* [WS-DL Blog](https://ws-dl.blogspot.com/) - 网络科学和数字图书馆研究小组关于各种网络归档相关主题、学术工作和学术旅行报告的博客.
* [DSHR's Blog](https://blog.dshr.org/) - David Rosenthal 定期回顾和总结数字保存领域所做的工作.
* [UK Web Archive Blog](https://blogs.bl.uk/webarchive/)

### Mailing Lists

* [Common Crawl](https://groups.google.com/g/common-crawl)
* [IIPC](http://netpreserve.org/about-us/iipc-mailing-list/)
* [OpenWayback](https://groups.google.com/g/openwayback-dev)
* [WASAPI](https://groups.google.com/g/wasapi-community)

### Slack

* [IIPC Slack](https://iipc.slack.com/) - 问 [@netpreserve](https://twitter.com/NetPreserve?s=20) 以供访问.
* [Archives Unleashed Slack](https://archivesunleashed.slack.com/) - [Fill out this request form](http://slack.archivesunleashed.org/) 用于访问从事网络档案工作的研究人员小组.
* [Archivers Slack](https://archivers.slack.com) - [Invite yourself](https://archivers-slack.herokuapp.com/) 多学科努力归档附属运行的项目 [EDGI](https://envirodatagov.org/archiving/) 和 [Data Together](http://datatogether.org/).

### Twitter

* [@NetPreserve](https://twitter.com/NetPreserve) - 官方 IIPC 手柄.
* [@WebSciDL](https://twitter.com/WebSciDL) - ODU 网络科学和数字图书馆研究小组.
* [#WebArchiving](https://twitter.com/search?q=%23webarchiving)
* [#WebArchiveWednesday](https://twitter.com/hashtag/webarchivewednesday)
