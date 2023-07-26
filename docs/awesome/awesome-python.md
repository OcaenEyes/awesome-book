<div class="github-widget" data-repo="vinta/awesome-python"></div>
## Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

精彩的 Python 框架、库、软件和资源的精选列表.

灵感来自 [awesome-php](https://github.com/ziadoz/awesome-php).


---

## Admin Panels

*管理界面库.*

* [ajenti](https://github.com/ajenti/ajenti) - 您的服务器值得拥有的管理面板.
* [django-grappelli](https://grappelliproject.com/) - Django 管理界面的爵士皮肤.
* [django-jet](https://github.com/geex-arts/django-jet) - Django 管理界面的现代响应式模板，具有改进的功能.
* [django-suit](https://djangosuit.com/) - 替代 Django 管理界面（仅免费用于非商业用途）.
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Django admin 的直接替换带来了很多好处.
* [flask-admin](https://github.com/flask-admin/flask-admin) - Flask 的简单且可扩展的管理界面框架.
* [flower](https://github.com/mher/flower) - Celery 的实时监控和网络管理.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - 适用于任何具有良好 UI 的应用程序的管理面板框架（例如 Jet Django）.
* [wooey](https://github.com/wooey/wooey) - 一个 Django 应用程序，可为 Python 脚本创建自动 Web UI.

## Algorithms and Design Patterns

 *数据结构、算法和设计模式的Python实现. 另请参阅 [awesome-algorithms](https://github.com/tayllan/awesome-algorithms).*

* 算法
    * [algorithms](https://github.com/keon/algorithms) - 数据结构和算法的最小示例.
    * [python-ds](https://github.com/prabhupant/python-ds) - 用于编码面试的数据结构和算法的集合.
    * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - 排序集合的快速、纯 Python 实现.
    * [TheAlgorithms](https://github.com/TheAlgorithms/Python) - 所有算法均以 Python 实现.
* 设计模式
    * [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - 一个简单而有效的库，用于实现常见的设计模式.
    * [python-patterns](https://github.com/faif/python-patterns) - Python 中的设计模式集合.
    * [transitions](https://github.com/pytransitions/transitions) - 轻量级、面向对象的有限状态机实现.

## ASGI Servers

*[ASGI](https://asgi.readthedocs.io/en/latest/)-兼容的网络服务器.*

* [daphne](https://github.com/django/daphne) - 用于 ASGI 和 ASGI-HTTP 的 HTTP、HTTP2 和 WebSocket 协议服务器.
* [uvicorn](https://github.com/encode/uvicorn) - 使用 uvloop 和 httptools 实现闪电般快速的 ASGI 服务器.

## Asynchronous Programming

* [asyncio](https://docs.python.org/3/library/asyncio.html) -（Python 标准库）异步 I/O、事件循环、协程和任务.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [trio](https://github.com/python-trio/trio) - 用于异步并发和 I/O 的友好库.
* [Twisted](https://twistedmatrix.com/trac/) - 事件驱动的网络引擎.
* [uvloop](https://github.com/MagicStack/uvloop) - 超快的异步事件循环.

## Audio

*用于操作音频及其元数据的库.*

* 声音
    * [audioread](https://github.com/beetbox/audioread) - 跨库（GStreamer + Core Audio + MAD + FFmpeg）音频解码.
    * [audioFlux](https://github.com/libAudioFlux/audioFlux) - 用于音频和音乐分析、特征提取的库.
    * [dejavu](https://github.com/worldveil/dejavu) - 音频指纹识别和识别.
    * [kapre](https://github.com/keunwoochoi/kapre) - Keras 音频预处理器.
    * [librosa](https://github.com/librosa/librosa) - 用于音频和音乐分析的 Python 库.
    * [matchering](https://github.com/sergree/matchering) - 用于自动参考音频母带制作的库.
    * [mingus](http://bspaans.github.io/python-mingus/) - 先进的音乐理论和乐谱包，支持 MIDI 文件和播放.
    * [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - 音频特征提取、分类、分割及应用.
    * [pydub](https://github.com/jiaaro/pydub) - 通过简单易用的高级界面来操作音频.
    * [TimeSide](https://github.com/Parisson/TimeSide) - 开放的网络音频处理框架.
* 元数据
    * [beets](https://github.com/beetbox/beets) - 音乐库管理员和 [MusicBrainz](https://musicbrainz.org/) 标签.
    * [eyeD3](https://github.com/nicfit/eyeD3) - 用于处理音频文件的工具，特别是包含 ID3 元数据的 MP3 文件.
    * [mutagen](https://github.com/quodlibet/mutagen) - 用于处理音频元数据的 Python 模块.
    * [tinytag](https://github.com/devsnd/tinytag) - 用于读取 MP3、OGG、FLAC 和 Wave 文件的音乐元数据的库.

## Authentication

*用于实现身份验证方案的库.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) - JavaScript 对象签名和加密草案实施.
    * [django-allauth](https://github.com/pennersr/django-allauth) - “正常工作”的 Django 身份验证应用程序.
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - Django 的 OAuth 2 好东西.
    * [oauthlib](https://github.com/idan/oauthlib) - OAuth 请求签名逻辑的通用且彻底的实现.
    * [python-oauth2](https://github.com/joestump/python-oauth2) - 用于创建 OAuth 客户端和服务器的经过充分测试的抽象接口.
    * [python-social-auth](https://github.com/omab/python-social-auth) - 易于设置的社交认证机制.
* 智威汤逊
    * [pyjwt](https://github.com/jpadilla/pyjwt) - Python 中的 JSON Web 令牌实现.
    * [python-jose](https://github.com/mpdavis/python-jose/) - Python 中的 JOSE 实现.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - 用于生成和验证 JSON Web 令牌的模块.

## Build Tools

*从源代码编译软件.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - 用于嵌入式 Linux 的类似 make 的构建工具.
* [buildout](http://www.buildout.org/en/latest/) - 用于从多个部分创建、组装和部署应用程序的构建系统.
* [PlatformIO](https://github.com/platformio/platformio-core) - 用于使用不同开发平台构建代码的控制台工具.
* [pybuilder](https://github.com/pybuilder/pybuilder) - 用纯Python编写的持续构建工具.
* [SCons](http://www.scons.org/) - 一个软件构建工具.

## Built-in Classes Enhancement

*用于增强Python内置类的库.*

* [attrs](https://github.com/python-attrs/attrs) - 替换类定义中的“__init__”、“__eq__”、“__repr__”等样板文件.
* [bidict](https://github.com/jab/bidict) - 高效、Pythonic 双向地图数据结构和相关功能.
* [Box](https://github.com/cdgriffith/Box) - 具有高级点表示法访问的 Python 字典.
* [dataclasses](https://docs.python.org/3/library/dataclasses.html) -（Python 标准库）数据类.
* [DottedDict](https://github.com/carlosescri/DottedDict) - 一个库，提供使用点路径表示法访问列表和字典的方法.

## CMS


* [django-cms](https://www.django-cms.org/en/) - 基于 Django 的开源企业 CMS.
* [indico](https://github.com/indico/indico) - 功能丰富的事件管理系统，@ [CERN](https://en.wikipedia.org/wiki/CERN).
* [Kotti](https://github.com/Kotti/Kotti) - 一个基于 Pyramid 构建的高级 Pythonic Web 应用程序框架.
* [plone](https://plone.org/) - 构建在开源应用程序服务器 Zope 之上的 CMS.
* [quokka](https://github.com/rochacbruno/quokka) - 由 Flask 和 MongoDB 提供支持的灵活、可扩展、小型 CMS.

## Caching

*用于缓存数据的库.*

* [beaker](https://github.com/bbangert/beaker) - 用于会话和缓存的 WSGI 中间件.
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Django 模型的自动缓存和失效.
* [django-cacheops](https://github.com/Suor/django-cacheops) - 灵活的 ORM 缓存，具有自动粒度事件驱动的失效功能.
* [dogpile.cache](http://dogpilecache.readthedocs.io/en/latest/) -dogpile.cache 是由同一作者制作的 Beaker 的下一代替代品.
* [HermesCache](https://pypi.org/project/HermesCache/) - Python 缓存库，具有基于标签的失效和狗堆效应预防功能.
* [pylibmc](https://github.com/lericson/pylibmc) - 一个 Python 包装器 [libmemcached](https://libmemcached.org/libMemcached.html) 界面.
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/) - SQLite 和文件支持的缓存后端具有比 memcached 和 redis 更快的查找速度.

## ChatOps Tools

*用于聊天机器人开发的库.*

* [errbot](https://github.com/errbotio/errbot/) - 实施 ChatOps 的最简单且最受欢迎的聊天机器人.

## Code Analysis

 *静态分析、linter 和代码质量检查工具. 另请参阅 [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* 代码分析
    * [coala](https://github.com/coala/coala/) - 独立于语言且易于扩展的代码分析应用程序.
    * [code2flow](https://github.com/scottrogowski/code2flow) - 将您的 Python 和 JavaScript 代码转换为 DOT 流程图.
    * [prospector](https://github.com/PyCQA/prospector) - 分析Python代码的工具.
    * [pycallgraph](https://github.com/gak/pycallgraph) - 一个可视化 Python 应用程序流程（调用图）的库.
    * [vulture](https://github.com/jendrikseipp/vulture) - 用于查找和分析无效 Python 代码的工具.
* 代码检查器
    * [flake8](https://pypi.org/project/flake8/) - 围绕“pycodestyle”、“pyflakes”和 McCabe 的包装.
        * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
    * [pylama](https://github.com/klen/pylama) - 适用于 Python 和 JavaScript 的代码审核工具.
    * [pylint](https://www.pylint.org/) - 完全可定制的源代码分析器.
    * [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - 有史以来最严格、最固执己见的 python linter.
* 代码格式化程序
    * [black](https://github.com/python/black) - 毫不妥协的 Python 代码格式化程序.
    * [isort](https://github.com/timothycrosley/isort) - 用于对导入进行排序的 Python 实用程序/库.
    * [yapf](https://github.com/google/yapf) - 来自 Google 的另一个 Python 代码格式化程序.
* 静态类型检查器，另请参阅 [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
    * [mypy](http://mypy-lang.org/) - 在编译时检查变量类型.
    * [pyre-check](https://github.com/facebook/pyre-check) - 高性能类型检查.
    * [typeshed](https://github.com/python/typeshed) - Python 库存根集合，具有静态类型.
* 静态类型注释生成器
    * [MonkeyType](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types.
    * [pytype](https://github.com/google/pytype) - Pytype 检查并推断 Python 代码的类型 - 无需类型注释.

## Command-line Interface Development

*用于构建命令行应用程序的库.*

* 命令行应用程序开发
    * [cement](http://builtoncement.com/) - Python 的 CLI 应用程序框架.
    * [click](http://click.pocoo.org/dev/) - 用于以可组合方式创建漂亮的命令行界面的包.
    * [cliff](https://docs.openstack.org/developer/cliff/) - 用于创建具有多级命令的命令行程序的框架.
    * [docopt](http://docopt.org/) - Pythonic 命令行参数解析器.
    * [python-fire](https://github.com/google/python-fire) - 用于从任何 Python 对象创建命令行界面的库.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - 用于构建强大的交互式命令行的库.
* 终端渲染
    * [alive-progress](https://github.com/rsalmei/alive-progress) - 一种新型进度条，具有实时吞吐量、eta 和非常酷的动画.
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - 用于创建全屏文本 UI 的包（从交互式表单到 ASCII 动画）.
    * [bashplotlib](https://github.com/glamp/bashplotlib) - 在终端中制作基本绘图.
    * [colorama](https://pypi.org/project/colorama/) - 跨平台彩色终端文本.
    * [rich](https://github.com/willmcgugan/rich)  - 用于在终端中实现富文本和漂亮格式的 Python 库. 还提供了一个很棒的“RichHandler”日志处理程序.
    * [tqdm](https://github.com/tqdm/tqdm) - 快速、可扩展的循环和 CLI 进度条.

## Command-line Tools

*基于 CLI 的实用工具可提高生产力.*

* 生产力工具
    * [copier](https://github.com/pykong/copier) - 用于渲染项目模板的库和命令行实用程序.
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - 一个命令行实用程序，可从 cookiecutter（项目模板）创建项目.
    * [doitlive](https://github.com/sloria/doitlive) - 在终端中进行现场演示的工具.
    * [howdoi](https://github.com/gleitz/howdoi) - 通过命令行即时编码答案.
    * [Invoke](https://github.com/pyinvoke/invoke#readme) - 用于管理面向 shell 的子进程并将可执行 Python 代码组织成 CLI 可调用任务的工具.
    * [PathPicker](https://github.com/facebook/PathPicker) - 从 bash 输出中选择文件.
    * [percol](https://github.com/mooz/percol) - 为 UNIX 上的传统管道概念添加了交互式选择的风格.
    * [thefuck](https://github.com/nvbn/thefuck) - 更正您之前的控制台命令.
    * [tmuxp](https://github.com/tony/tmuxp) - A [tmux](https://github.com/tmux/tmux) 会话管理器.
    * [try](https://github.com/timofurrer/try) - 一个非常简单的 CLI 来尝试 python 包 - 从未如此简单.
* CLI 增强
    * [httpie](https://github.com/jakubroztocil/httpie) - 命令行 HTTP 客户端，用户友好的 cURL 替代品.
    * [iredis](https://github.com/laixintao/iredis) - Redis CLI 具有自动完成和语法突出显示功能.
    * [kube-shell](https://github.com/cloudnativelabs/kube-shell) - 用于使用 Kubernetes CLI 的集成 shell.
    * [litecli](https://github.com/dbcli/litecli) - SQLite CLI 具有自动完成和语法突出显示功能.
    * [mycli](https://github.com/dbcli/mycli) - MySQL CLI 具有自动完成和语法突出显示功能.
    * [pgcli](https://github.com/dbcli/pgcli) - 具有自动完成和语法突出显示功能的 PostgreSQL CLI.
    * [saws](https://github.com/donnemartin/saws) - 增压 [aws-cli](https://github.com/aws/aws-cli).

## Compatibility

*用于从 Python 2 迁移到 3 的库.*

* [python-future](http://python-future.org/index.html) - Python 2 和 Python 3 之间缺少兼容性层.
* [modernize](https://github.com/PyCQA/modernize) - 对 Python 代码进行现代化改造，以实现最终的 Python 3 迁移.
* [six](https://pypi.org/project/six/) - Python 2 和 3 兼容性实用程序.

## Computer Vision

*计算机视觉库.*

* [EasyOCR](https://github.com/JaidedAI/EasyOCR) - 即用型 OCR，支持 40 多种语言.
* [Face Recognition](https://github.com/ageitgey/face_recognition) - 简单的面部识别库.
* [Kornia](https://github.com/kornia/kornia/) - PyTorch 的开源可微计算机视觉库.
* [OpenCV](https://opencv.org/) - 开源计算机视觉库.
* [pytesseract](https://github.com/madmaze/pytesseract) - 一个包装纸 [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [SimpleCV](https://github.com/sightmachine/SimpleCV) - 用于构建计算机视觉应用程序的开源框架.
* [tesserocr](https://github.com/sirfz/tesserocr) - 另一个简单的、Pillow 友好的 OCR“tesseract-ocr” API 包装器.

## Concurrency and Parallelism

 *用于并发和并行执行的库. 另请参阅 [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) -（Python 标准库）用于异步执行可调用对象的高级接口.
* [eventlet](http://eventlet.net/) - 具有 WSGI 支持的异步框架.
* [gevent](http://www.gevent.org/) - 基于协程的 Python 网络库，使用 [greenlet](https://github.com/python-greenlet/greenlet).
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) -（Python 标准库）基于进程的并行性.
* [scoop](https://github.com/soravux/scoop) - Python 中的可扩展并发操作.
* [uvloop](https://github.com/MagicStack/uvloop) - 在“libuv”之上超快速实现“asyncio”事件循环.

## Configuration

*用于存储和解析配置选项的库.*

* [configobj](https://github.com/DiffSK/configobj) - 带验证的 INI 文件解析器.
* [configparser](https://docs.python.org/3/library/configparser.html) - （Python 标准库）INI 文件解析器.
* [hydra](https://github.com/facebookresearch/hydra) - Hydra 是一个用于优雅地配置复杂应用程序的框架.
* [profig](https://profig.readthedocs.io/en/latest/) - 通过值转换从多种格式进行配置.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - 设置与代码严格分离.

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) - 旨在向 Python 开发人员公开加密原语和配方的包.
* [paramiko](https://github.com/paramiko/paramiko) - 领先的原生 Python SSHv2 协议库.
* [passlib](https://passlib.readthedocs.io/en/stable/) - 安全密码存储/哈希库，非常高水平.
* [pynacl](https://github.com/pyca/pynacl) - Python 绑定到网络和密码学 (NaCl) 库.

## Data Analysis

*用于数据分析的库.*

* [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler) - AWS 上的 Pandas.
* [Blaze](https://github.com/blaze/blaze) - NumPy 和 Pandas 与大数据的接口.
* [Open Mining](https://github.com/mining/mining) - Pandas 界面中的商业智能 (BI).
* [Optimus](https://github.com/ironmussa/Optimus) - 使用 PySpark 使敏捷数据科学工作流程变得简单.
* [Orange](https://orange.biolab.si/) - 通过可视化编程或脚本进行数据挖掘、数据可视化、分析和机器学习.
* [Pandas](http://pandas.pydata.org/) - 提供高性能、易于使用的数据结构和数据分析工具的库.

## Data Validation

 *用于验证数据的库. 在许多情况下用于表单.*

* [Cerberus](https://github.com/pyeve/cerberus) - 一个轻量级且可扩展的数据验证库.
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - 验证和反序列化通过 XML、JSON、HTML 表单发布获得的数据.
* [jsonschema](https://github.com/Julian/jsonschema) - 实施 [JSON Schema](http://json-schema.org/) 对于Python.
* [schema](https://github.com/keleshev/schema) - 用于验证 Python 数据结构的库.
* [Schematics](https://github.com/schematics/schematics) - 数据结构验证.
* [valideer](https://github.com/podio/valideer) - 轻量级可扩展数据验证和适应库.
* [voluptuous](https://github.com/alecthomas/voluptuous) - Python 数据验证库.

## Data Visualization

 *用于可视化数据的库. 另请参阅 [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Python 的声明式统计可视化库.
* [Bokeh](https://github.com/bokeh/bokeh) - Python 交互式网页绘图.
* [bqplot](https://github.com/bloomberg/bqplot) - Jupyter Notebook 的交互式绘图库.
* [Cartopy](https://github.com/SciTools/cartopy) - 具有 matplotlib 支持的制图 Python 库.
* [Dash](https://plot.ly/products/dash/) - 构建在 Flask、React 和 Plotly 之上，旨在分析 Web 应用程序.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash)
* [diagrams](https://github.com/mingrammer/diagrams) - 图表即代码.
* [Matplotlib](http://matplotlib.org/) - Python 2D 绘图库.
* [plotnine](https://github.com/has2k1/plotnine) - 基于 ggplot2 的 Python 图形语法.
* [Pygal](http://www.pygal.org/en/latest/) - Python SVG 图表创建器.
* [PyGraphviz](https://pypi.org/project/pygraphviz/) - Python 接口 [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - 交互式和实时 2D/3D/图像绘图和科学/工程小部件.
* [Seaborn](https://github.com/mwaskom/seaborn) - 使用 Matplotlib 进行统计数据可视化.
* [VisPy](https://github.com/vispy/vispy) - 基于OpenGL的高性能科学可视化.

## Database

*用Python实现的数据库.*

* [pickleDB](https://github.com/patx/pickledb) - A simple and lightweight key-value store for Python.
* [tinydb](https://github.com/msiemens/tinydb) - 一个小型的、面向文档的数据库.
* [ZODB](https://github.com/zopefoundation/ZODB)  - Python 的本机对象数据库. 键值和对象图数据库.

## Database Drivers

*用于连接和操作数据库的库.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - 支持 Python 3 的 MySQL 连接器（[mysql-python](https://sourceforge.net/projects/mysql-python/) 叉）.
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) - 与 mysql-python 兼容的纯 Python MySQL 驱动程序.
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) - 最流行的 Python PostgreSQL 适配器.
    * [queries](https://github.com/gmr/queries) - 用于与 PostgreSQL 交互的 psycopg2 库的包装器.
* SQlite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite)
    * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - （Python标准库）SQlite接口符合DB-API 2.0
    * [SuperSQLite](https://github.com/plasticityai/supersqlite) - 一个强大的 SQLite 库构建在 [apsw](https://github.com/rogerbinns/apsw).
* 其他关系数据库
    * [pymssql](https://pymssql.readthedocs.io/en/latest/) - Microsoft SQL Server 的简单数据库接口.
    * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) - 具有 ClickHouse 原生接口的 Python 驱动程序.
* NoSQL 数据库
    * [cassandra-driver](https://github.com/datastax/python-driver) - Apache Cassandra 的 Python 驱动程序.
    * [happybase](https://github.com/wbolster/happybase) - Apache HBase 的开发人员友好库.
    * [kafka-python](https://github.com/dpkp/kafka-python) - Apache Kafka 的 Python 客户端.
    * [py2neo](https://py2neo.org/) - 用于使用 Neo4j 的客户端库和工具包.
    * [pymongo](https://github.com/mongodb/mongo-python-driver) - MongoDB 的官方 Python 客户端.
    * [redis-py](https://github.com/andymccurdy/redis-py) - Redis 的 Python 客户端.
* 异步客户端
    * [motor](https://github.com/mongodb/motor) - MongoDB 的异步 Python 驱动程序.

## Date and Time

*用于处理日期和时间的库.*

* [Arrow](https://arrow.readthedocs.io/en/latest/) - 一个 Python 库，提供了一种合理且人性化的方法来创建、操作、格式化和转换日期、时间和时间戳.
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - 用于解析人类编写的时间和日期的 Python 3 库.
* [dateutil](https://github.com/dateutil/dateutil) - 标准 Python 的扩展 [datetime](https://docs.python.org/3/library/datetime.html) 模块.
* [delorean](https://github.com/myusuf3/delorean/) - 一个用于澄清处理日期时间时出现的令人不快的事实的库.
* [maya](https://github.com/timofurrer/maya) - 人类的日期时间.
* [moment](https://github.com/zachwill/moment)  - 用于处理日期/时间的 Python 库. 灵感来自 [Moment.js](http://momentjs.com/).
* [Pendulum](https://github.com/sdispater/pendulum) - Python 日期时间变得简单.
* [PyTime](https://github.com/shinux/PyTime) - 一个易于使用的Python模块，旨在通过字符串操作日期/时间/日期时间.
* [pytz](https://launchpad.net/pytz)  - 世界时区定义，现代和历史. 带来了 [tz database](https://en.wikipedia.org/wiki/Tz_database) 进入Python.
* [when.py](https://github.com/dirn/When.py) - 提供用户友好的功能来帮助执行常见的日期和时间操作.

## Debugging Tools

*用于调试代码的库.*

* 类似pdb的调试器
    * [ipdb](https://github.com/gotcha/ipdb) - 支持 IPython [pdb](https://docs.python.org/3/library/pdb.html).
    * [pdb++](https://github.com/antocuni/pdb) - pdb 的另一个直接替代品.
    * [pudb](https://github.com/inducer/pudb) - 全屏、基于控制台的 Python 调试器.
    * [wdb](https://github.com/Kozea/wdb) - 通过 WebSockets 实现的不可能的 Web 调试器.
* 追踪
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) 对于Python程序.
    * [manhole](https://github.com/ionelmc/python-manhole) - 调试 UNIX 套接字连接并显示所有线程的堆栈跟踪和交互式提示.
    * [pyringe](https://github.com/google/pyringe) - 能够附加到 Python 进程并向其中注入代码的调试器.
    * [python-hunter](https://github.com/ionelmc/python-hunter) - 灵活的代码跟踪工具包.
* 分析器
    * [line_profiler](https://github.com/rkern/line_profiler) - 逐行分析.
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - 监控Python代码的内存使用情况.
    * [py-spy](https://github.com/benfred/py-spy)  - Python 程序的采样分析器. 用 Rust 编写.
    * [pyflame](https://github.com/uber/pyflame) - Python 的 ptracing 分析器.
    * [vprof](https://github.com/nvdv/vprof) - 可视化 Python 分析器.
* 其他
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - 显示Django的各种调试信息.
    * [django-devserver](https://github.com/dcramer/django-devserver) - Django 运行服务器的直接替代品.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - django-debug-toolbar 到 Flask 的端口.
    * [icecream](https://github.com/gruns/icecream) - 通过单个简单的函数调用检查变量、表达式和程序执行.
    * [pyelftools](https://github.com/eliben/pyelftools) - 解析分析ELF文件和DWARF调试信息.

## Deep Learning

 *神经网络和深度学习框架. 另请参阅 [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [caffe](https://github.com/BVLC/caffe) - 一个快速开放的深度学习框架..
* [keras](https://github.com/keras-team/keras) - 高级神经网络库，能够在 TensorFlow 或 Theano 上运行.
* [mxnet](https://github.com/dmlc/mxnet) - 专为提高效率和灵活性而设计的深度学习框架.
* [pytorch](https://github.com/pytorch/pytorch) - Python 中的张量和动态神经网络，具有强大的 GPU 加速功能.
* [SerpentAI](https://github.com/SerpentAI/SerpentAI)  - 游戏代理框架. 使用任何视频游戏作为深度学习沙箱.
* [tensorflow](https://github.com/tensorflow/tensorflow) - Google 创建的最受欢迎的深度学习框架.
* [Theano](https://github.com/Theano/Theano) - 用于快速数值计算的库.
* [lightning](https://github.com/Lightning-AI/lightning) - 深度学习框架，可快速训练、部署和交付人工智能产品.

## DevOps Tools

*用于 DevOps 的软件和库.*

* 配置管理
    * [ansible](https://github.com/ansible/ansible) - 一个极其简单的 IT 自动化平台.
    * [cloudinit](https://cloudinit.readthedocs.io/en/latest/) - 一个多分发包，用于处理云实例的早期初始化.
    * [OpenStack](https://www.openstack.org/) - 用于构建私有云和公共云的开源软件.
    * [pyinfra](https://github.com/Fizzadar/pyinfra) - 用于自动化基础设施的多功能 CLI 工具和 python 库.
* SSH方式部署
    * [cuisine](https://github.com/sebastien/cuisine) - Fabric 的类似 Chef 的功能.
    * [fabric](https://github.com/fabric/fabric) - 一个简单的 Python 工具，用于远程执行和部署.
    * [fabtools](https://github.com/fabtools/fabtools) - 用于编写出色的 Fabric 文件的工具.
* 流程管理
    * [honcho](https://github.com/nickstenning/honcho) - Python 克隆 [Foreman](https://github.com/ddollar/foreman)，用于管理基于 Procfile 的应用程序.
    * [supervisor](https://github.com/Supervisor/supervisor) - UNIX 的主管进程控制系统.
* 监控
    * [psutil](https://github.com/giampaolo/psutil) - 跨平台进程和系统实用程序模块.
* 备份
    * [BorgBackup](https://www.borgbackup.org/) - 具有压缩和加密功能的重复数据删除归档程序.
* 其他
    * [docker-compose](https://docs.docker.com/compose/) - 使用快速、隔离的开发环境 [Docker](https://www.docker.com/).

## Distributed Computing

*分布式计算的框架和库.*

* 批量处理
    * [dask](https://github.com/dask/dask) - 用于分析计算的灵活并行计算库.
    * [luigi](https://github.com/spotify/luigi) - 帮助您构建复杂的批处理作业管道的模块.
    * [mrjob](https://github.com/Yelp/mrjob) - 在 Hadoop 或 Amazon Web Services 上运行 MapReduce 作业.
    * [PySpark](https://pypi.org/project/pyspark/) - [Apache Spark](https://spark.apache.org/) Python API.
    * [Ray](https://github.com/ray-project/ray/) - 统一机器学习生态系统的并行分布式 Python 系统.
* 流处理
    * [faust](https://github.com/robinhood/faust) - 一个流处理库，移植了来自 [Kafka Streams](https://kafka.apache.org/documentation/streams/) 到Python.
    * [streamparse](https://github.com/Parsely/streamparse) - 针对实时数据流运行 Python 代码 [Apache Storm](http://storm.apache.org/).

## Distribution

*用于创建用于发布分发的打包可执行文件的库.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - 将 virtualenv 构建并分发为 Debian 软件包.
* [Nuitka](http://nuitka.net/) - 将脚本、模块、包编译为可执行文件或扩展模块.
* [py2app](http://pythonhosted.org/py2app/) - 冻结 Python 脚本 (Mac OS X).
* [py2exe](http://www.py2exe.org/) - 冻结 Python 脚本 (Windows).
* [pyarmor](https://github.com/dashingsoft/pyarmor) - 用于混淆 python 脚本、将混淆脚本绑定到固定机器或使混淆脚本过期的工具.
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - 将Python程序转换为独立的可执行文件（跨平台）.
* [pynsist](http://pynsist.readthedocs.io/en/latest/) - 构建 Windows 安装程序的工具，安装程序捆绑 Python 本身.
* [shiv](https://github.com/linkedin/shiv) - 用于构建完全独立的 zipapps (PEP 441) 的命令行实用程序，但包含其所有依赖项.

## Documentation

*用于生成项目文档的库.*

* [sphinx](https://github.com/sphinx-doc/sphinx/) - Python 文档生成器.
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc)
* [pdoc](https://github.com/mitmproxy/pdoc) - Epydoc 替换为自动生成 Python 库的 API 文档.
* [pycco](https://github.com/pycco-docs/pycco) - 文学编程风格的文档生成器.

## Downloader

*可供下载的库.*

* [akshare](https://github.com/jindaxiang/akshare) - 一个金融数据接口库，为人类而建！
* [s3cmd](https://github.com/s3tools/s3cmd) - 用于管理 Amazon S3 和 CloudFront 的命令行工具.
* [s4cmd](https://github.com/bloomreach/s4cmd) - 超级S3命令行工具，有利于更高的性能.
* [you-get](https://you-get.org/) - 用 Python 3 编写的 YouTube/Youku/Niconico 视频下载器.
* [youtube-dl](https://rg3.github.io/youtube-dl/) - 一个用于从 YouTube 下载视频的小型命令行程序.

## E-commerce

*电子商务和支付的框架和库.*

* [alipay](https://github.com/lxneng/alipay) - 适用于 Python 的非官方支付宝 API.
* [Cartridge](https://github.com/stephenmcd/cartridge) - 使用 Mezzanine 构建的购物车应用程序.
* [django-oscar](http://oscarcommerce.com/) - Django 的开源电子商务框架.
* [django-shop](https://github.com/awesto/django-shop) - 基于 Django 的商店系统.
* [forex-python](https://github.com/MicroPyramid/forex-python) - 外汇汇率、比特币价格指数和货币兑换.
* [merchant](https://github.com/agiliq/merchant) - 一个 Django 应用程序，用于接受来自各种支付处理器的付款.
* [money](https://github.com/carlospalol/money) - “Money”类，具有可选的 CLDR 支持的区域设置感知格式和可扩展的货币交换.
* [python-currencies](https://github.com/Alir3z4/python-currencies) - 显示货币格式及其肮脏的货币.
* [saleor](https://saleor.io/) - 无头开源电子商务平台.
* [shoop](https://www.shuup.com/en/) - 基于 Django 的开源电子商务平台.

## Editor Plugins and IDEs

* Emacs
    * [elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python 开发环境.
* 崇高的文字
    * [anaconda](https://github.com/DamnWidget/anaconda) - Anaconda 将您的 Sublime Text 3 转变为功能齐全的 Python 开发 IDE.
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - 很棒的自动完成库 Jedi 的 Sublime Text 插件.
* 为什么
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) - Python 的 Jedi 自动完成库的 Vim 绑定.
    * [python-mode](https://github.com/python-mode/python-mode) - 一款将 Vim 转变为 Python IDE 的一体化插件.
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - 包括 [Jedi](https://github.com/davidhalter/jedi)基于 Python 的补全引擎.
* 视觉工作室
    * [PTVS](https://github.com/Microsoft/PTVS) - Visual Studio 的 Python 工具.
* 视觉工作室代码
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - 官方 VSCode 扩展，对 Python 提供丰富的支持.
* 去
    * [PyCharm](https://www.jetbrains.com/pycharm/)  - JetBrains 的商业 Python IDE. 有免费的社区版可用.
    * [spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE.

## Email

*用于发送和解析电子邮件的库.*

* 邮件服务器
    * [modoboa](https://github.com/modoboa/modoboa) - 邮件托管和管理平台，包括现代 Web UI.
    * [salmon](https://github.com/moggers87/salmon) - Python 邮件服务器.
* 客户
    * [imbox](https://github.com/martinrusev/imbox) - 用于人类的Python IMAP.
    * [yagmail](https://github.com/kootenpv/yagmail) - 又一个 Gmail/SMTP 客户端.
* 其他
    * [flanker](https://github.com/mailgun/flanker) - 电子邮件地址和 Mime 解析库.
    * [mailer](https://github.com/marrow/mailer) - 高性能可扩展邮件传递框架.

## Enterprise Application Integrations

*企业环境中系统集成的平台和工具*

* [Zato](https://zato.io) - Python 中的 ESB、SOA、REST、API 和云集成.

## Environment Management

*用于Python版本和虚拟环境管理的库.*

* [pyenv](https://github.com/pyenv/pyenv) - 简单的Python版本管理.
* [virtualenv](https://github.com/pypa/virtualenv) - 创建隔离 Python 环境的工具.

## File

*用于文件操作和 MIME 类型检测的库.*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - （Python 标准库）将文件名映射到 MIME 类型.
* [path.py](https://github.com/jaraco/path.py) - 模块包装器 [os.path](https://docs.python.org/3/library/os.path.html).
* [pathlib](https://docs.python.org/3/library/pathlib.html) -（Python 标准库）跨平台、面向对象的路径库.
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) - Python 的文件系统抽象层.
* [python-magic](https://github.com/ahupp/python-magic) - libmagic 文件类型识别库的 Python 接口.
* [Unipath](https://github.com/mikeorr/Unipath) - 文件/目录操作的面向对象方法.
* [watchdog](https://github.com/gorakhargosh/watchdog) - 用于监视文件系统事件的 API 和 shell 实用程序.

## Foreign Function Interface

*提供外部函数接口的库*

* [cffi](https://pypi.org/project/cffi/) - Python 调用 C 代码的外部函数接口.
* [ctypes](https://docs.python.org/3/library/ctypes.html) -（Python 标准库）Python 调用 C 代码的外部函数接口.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - Nvidia CUDA API 的 Python 包装器.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - 简化的包装器和接口生成器.

## Forms

*用于处理表单的库.*

* [Deform](https://github.com/Pylons/deform) - Python HTML 表单生成库受 formish 表单生成库的影响.
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 与 Django 集成.
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) - Bootstrap 4 与 Django 集成.
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) - 一个 Django 应用程序，可让您以非常优雅和干燥的方式创建漂亮的表单.
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - 一个独立于平台的 Django 表单序列化器.
* [WTForms](https://github.com/wtforms/wtforms) - 灵活的表单验证和渲染库.

## Functional Programming

*使用Python进行函数式编程.*

* [Coconut](https://github.com/evhub/coconut) - Python 的一个变体，专为简单、优雅、Python 式的函数式编程而构建.
* [CyToolz](https://github.com/pytoolz/cytoolz/) - `Toolz` 的 Cython 实现：高性能功能实用程序.
* [fn.py](https://github.com/kachayev/fn.py) - Python 中的函数式编程：实现缺失的功能以享受 FP.
* [funcy](https://github.com/Suor/funcy) - 一款精美实用的功能工具.
* [more-itertools](https://github.com/erikrose/more-itertools) - 除了“itertools”之外，还有更多用于操作可迭代对象的例程.
* [returns](https://github.com/dry-python/returns) - 一组类型安全的 monad、变压器和组合实用程序.
* [Toolz](https://github.com/pytoolz/toolz) - 用于迭代器、函数和字典的功能实用程序的集合.

## GUI Development

*用于使用图形用户界面应用程序的库.*

* [curses](https://docs.python.org/3/library/curses.html) - 内置包装器 [ncurses](http://www.gnu.org/software/ncurses/) 用于创建终端 GUI 应用程序.
* [Eel](https://github.com/ChrisKnott/Eel) - 用于制作简单的类似 Electron 的离线 HTML/JS GUI 应用程序的库.
* [enaml](https://github.com/nucleic/enaml) - 使用 QML 等声明性语法创建漂亮的用户界面.
* [Flexx](https://github.com/zoofIO/flexx) - Flexx 是一个用于创建 GUI 的纯 Python 工具包，它使用 Web 技术进行渲染.
* [Gooey](https://github.com/chriskiehl/Gooey) - 用一行将命令行程序变成一个完整的 GUI 应用程序.
* [kivy](https://kivy.org/) - 用于创建在 Windows、Linux、Mac OS X、Android 和 iOS 上运行的 NUI 应用程序的库.
* [pyglet](https://github.com/pyglet/pyglet) - Python 的跨平台窗口和多媒体库.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - GLib/GObject/GIO/GTK+ (GTK+3) 的 Python 绑定.
* [PyQt](https://doc.qt.io/qtforpython/) - Python 绑定 [Qt](https://www.qt.io/) 跨平台应用程序和 UI 框架.
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - tkinter、Qt、WxPython 和 Remi 的包装器.
* [pywebview](https://github.com/r0x0r/pywebview/) - 围绕 webview 组件的轻量级跨平台本机包装器.
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter 是 Python 事实上的标准 GUI 包.
* [Toga](https://github.com/pybee/toga) - Python 本机、操作系统本机 GUI 工具包.
* [urwid](http://urwid.org/) - 用于创建终端 GUI 应用程序的库，对小部件、事件、丰富的颜色等提供强大支持.
* [wxPython](https://wxpython.org/) - wxWidgets C++ 类库与 Python 的混合.
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) - 一个简单的 GPU 加速 Python GUI 框架

## GraphQL

*用于使用 GraphQL 的库.*

* [graphene](https://github.com/graphql-python/graphene/) - Python 的 GraphQL 框架.
* [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/) - 基于“aiohttp”的 Tartiflette 包装器，用于通过 HTTP 公开 GraphQL API.
* [tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/) - Tartiflette GraphQL 引擎的 ASGI 支持.
* [tartiflette](https://tartiflette.io) - 适用于 Python 3.6+ 和 asyncio 的 SDL-first GraphQL 引擎实现.

## Game Development

*很棒的游戏开发库.*

* [Arcade](https://api.arcade.academy/en/latest/) - Arcade 是一个现代 Python 框架，用于制作具有引人注目的图形和声音的游戏.
* [Cocos2d](http://cocos2d.org/) - cocos2d 是一个用于构建 2D 游戏、演示和其他图形/交互式应用程序的框架.
* [Harfang3D](http://www.harfang3d.com) - 用于 3D、VR 和游戏开发的 Python 框架.
* [Panda3D](https://www.panda3d.org/) - 迪士尼开发的3D游戏引擎.
* [Pygame](http://www.pygame.org/news.html) - Pygame 是一组专为编写游戏而设计的 Python 模块.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Ogre 3D 渲染引擎的 Python 绑定，可用于游戏、模拟、任何 3D 内容.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - OpenGL 及其相关 API 的 Python ctypes 绑定.
* [PySDL2](https://pysdl2.readthedocs.io) - SDL2 库的基于 ctypes 的包装器.
* [RenPy](https://www.renpy.org/) - 视觉小说引擎.

## Geolocation

*用于对地址进行地理编码并处理纬度和经度的库.*

* [django-countries](https://github.com/SmileyChris/django-countries) - 一个 Django 应用程序，为模型和表单提供国家/地区字段.
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - 世界一流的地理网络框架.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - MaxMind GeoIP 遗留数据库的 Python API.
* [geojson](https://github.com/frewsxcv/python-geojson) - GeoJSON 的 Python 绑定和实用程序.
* [geopy](https://github.com/geopy/geopy) - Python 地理编码工具箱.

## HTML Manipulation

*用于处理 HTML 和 XML 的库.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - 提供用于迭代、搜索和修改 HTML 或 XML 的 Pythonic 习惯用法.
* [bleach](https://github.com/mozilla/bleach) - 基于白名单的 HTML 清理和文本链接库.
* [cssutils](https://pypi.org/project/cssutils/) - Python 的 CSS 库.
* [html5lib](https://github.com/html5lib/html5lib-python) - 一个符合标准的库，用于解析和序列化 HTML 文档和片段.
* [lxml](http://lxml.de/) - 一个非常快速、易于使用和多功能的库，用于处理 HTML 和 XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) - 为 Python 实现 XML/HTML/XHTML 标记安全字符串.
* [pyquery](https://github.com/gawel/pyquery) - 一个类似 jQuery 的库，用于解析 HTML.
* [untangle](https://github.com/stchris/untangle) - 将 XML 文档转换为 Python 对象以便于访问.
* [WeasyPrint](http://weasyprint.org) - 可以导出为 PDF 的 HTML 和 CSS 视觉渲染引擎.
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/) - 简单的 XML 解析.
* [xmltodict](https://github.com/martinblech/xmltodict) - 使用 XML 就像使用 JSON 一样.

## HTTP Clients

*用于使用 HTTP 的库.*

* [grequests](https://github.com/spyoungtech/grequests) - requests + gevent 用于异步 HTTP 请求.
* [httplib2](https://github.com/httplib2/httplib2) - 综合 HTTP 客户端库.
* [httpx](https://github.com/encode/httpx) - Python 的下一代 HTTP 客户端.
* [requests](https://github.com/psf/requests) - 人类的 HTTP 请求.
* [treq](https://github.com/twisted/treq) - Python 请求，例如构建在 Twisted 的 HTTP 客户端之上的 API.
* [urllib3](https://github.com/shazow/urllib3) - 具有线程安全连接池、文件发布支持、理智友好的 HTTP 库.

## Hardware

*用于硬件编程的库.*

* [ino](http://inotool.org/) - 用于使用的命令行工具包 [Arduino](https://www.arduino.cc/).
* [keyboard](https://github.com/boppreh/keyboard) - 在 Windows 和 Linux 上挂钩并模拟全局键盘事件.
* [mouse](https://github.com/boppreh/mouse) - 在 Windows 和 Linux 上挂钩并模拟全局鼠标事件.
* [Pingo](http://www.pingo.io/) - Pingo 为 Raspberry Pi、pcDuino、Intel Galileo 等设备提供统一的 API 编程.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - 用于跨平台控制鼠标和键盘的模块.
* [scapy](https://github.com/secdev/scapy) - 一个出色的数据包操作库.

## Image Processing

*用于操作图像的库.*

* [hmap](https://github.com/rossgoodwin/hmap) - 图像直方图重新映射.
* [imgSeek](https://sourceforge.net/projects/imgseek/) - 使用视觉相似性搜索图像集合的项目.
* [nude.py](https://github.com/hhatto/nude.py) - 裸体检测.
* [pagan](https://github.com/daboth/pagan) - 基于输入字符串和散列的复古标识（头像）生成.
* [pillow](https://github.com/python-pillow/Pillow) - 枕头很友好 [PIL](http://www.pythonware.com/products/pil/) 叉.
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) - 在 Python 中创建条形码，无需额外的依赖项.
* [pygram](https://github.com/ajkumar25/pygram) - 类似 Instagram 的图像过滤器.
* [PyMatting](http://github.com/pymatting/pymatting) - 用于 alpha 抠图的库.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - 纯Python QR 码生成器.
* [pywal](https://github.com/dylanaraps/pywal) - 从图像生成配色方案的工具.
* [pyvips](https://github.com/libvips/pyvips) - 内存需求低的快速图像处理库.
* [Quads](https://github.com/fogleman/Quads) - 基于四叉树的计算机艺术.
* [scikit-image](http://scikit-image.org/) - 用于（科学）图像处理的 Python 库.
* [thumbor](https://github.com/thumbor/thumbor)  - 智能影像服务. 它支持按需裁剪、调整图像大小和翻转图像.
* [wand](https://github.com/dahlia/wand) - Python 绑定 [MagickWand](http://www.imagemagick.org/script/magick-wand.php), ImageMagick 的 C API.

## Implementations

*Python 的实现.*

* [CLPython](https://github.com/metawilm/cl-python) - 用 Common Lisp 编写的 Python 编程语言的实现.
* [CPython](https://github.com/python/cpython) - **默认、最广泛使用的用 C 编写的 Python 编程语言实现.**
* [Cython](http://cython.org/) - 优化 Python 静态编译器.
* [Grumpy](https://github.com/google/grumpy) - 更多的编译器而不是解释器，作为更强大的 CPython2.7 替代品（alpha）.
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#.
* [Jython](https://hg.python.org/jython) - 为 JVM 实现用 Java 编写的 Python 编程语言.
* [MicroPython](https://github.com/micropython/micropython) - 精益高效的 Python 编程语言实现.
* [Numba](http://numba.pydata.org/) - 针对科学 Python 的 LLVM 的 Python JIT 编译器.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - Python 中嵌入的 x86-64 汇编器.
* [Pyjion](https://github.com/Microsoft/Pyjion) - 基于 CoreCLR 的 Python JIT.
* [PyPy](https://foss.heptapod.net/pypy/pypy) - Python 语言的非常快速且兼容的实现.
* [Pyston](https://github.com/pyston/pyston/) - 使用 JIT 技术的 Python 实现.
* [Stackless Python](https://github.com/stackless-dev/stackless) - Python 编程语言的增强版本.

## Interactive Interpreter

*交互式 Python 解释器 (REPL).*

* [bpython](https://github.com/bpython/bpython) - Python 解释器的精美界面.
* [Jupyter Notebook (IPython)](https://jupyter.org) - 丰富的工具包可帮助您充分利用 Python 交互功能.
    * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
* [ptpython](https://github.com/jonathanslenders/ptpython) - 建立在高级 Python REPL 之上 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).

## Internationalization

*用于 i18n 的库.*

* [Babel](http://babel.pocoo.org/en/latest/) - Python 国际化库.
* [PyICU](https://github.com/ovalhub/pyicu) - Unicode C++ 库国际组件的包装器 ([ICU](http://site.icu-project.org/)).

## Job Scheduler

*用于调度作业的库.*

* [Airflow](https://airflow.apache.org/) - Airflow 是一个以编程方式创作、安排和监控工作流程的平台.
* [APScheduler](http://apscheduler.readthedocs.io/en/latest/) - 一个轻量级但功能强大的进程内任务调度程序，可让您调度功能.
* [django-schedule](https://github.com/thauber/django-schedule) - Django 的日历应用程序.
* [doit](http://pydoit.org/) - 任务运行器和构建工具.
* [gunnery](https://github.com/gunnery/gunnery) - 用于具有基于 Web 界面的分布式系统的多用途任务执行工具.
* [Joblib](https://joblib.readthedocs.io/) - 一组在 Python 中提供轻量级流水线的工具.
* [Plan](https://github.com/fengsp/plan) - 用 Python 编写 crontab 文件就像一个魅力.
* [Prefect](https://github.com/PrefectHQ/prefect) - 现代工作流程编排框架，可以轻松构建、调度和监控强大的数据管道.
* [schedule](https://github.com/dbader/schedule) - 用于人类的 Python 作业调度.
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - 用纯Python实现的强大的工作流引擎.
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) - 一个 Python 库，有助于使任务执行变得简单、一致和可靠.

## Logging

*用于生成和处理日志的库.*

* [logbook](http://logbook.readthedocs.io/en/stable/) - Python 的日志记录替代.
* [logging](https://docs.python.org/3/library/logging.html) -（Python 标准库）Python 的日志记录工具.
* [loguru](https://github.com/Delgan/loguru) - 旨在为 Python 带来愉快的日志记录的库.
* [sentry-python](https://github.com/getsentry/sentry-python) - 适用于 Python 的 Sentry SDK.
* [structlog](https://www.structlog.org/en/stable/) - 结构化日志记录变得简单.

## Machine Learning

 *机器学习库. 另请参阅 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [gym](https://github.com/openai/gym) - 用于开发和比较强化学习算法的工具包.
* [H2O](https://github.com/h2oai/h2o-3) - 开源快速可扩展机器学习平台.
* [Metrics](https://github.com/benhamner/Metrics) - 机器学习评估指标.
* [NuPIC](https://github.com/numenta/nupic) - Numenta 智能计算平台.
* [scikit-learn](http://scikit-learn.org/) - 最流行的机器学习 Python 库.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)的可扩展机器学习库.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - 一个轻量级的Python包装器 [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) - 一个可扩展、可移植、分布式梯度增强库.
* [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB 是现有数据库的开源 AI 层，可让您使用标准查询轻松开发、训练和部署最先进的机器学习模型.

## Microsoft Windows

*在 Microsoft Windows 上进行 Python 编程.*

* [Python(x,y)](http://python-xy.github.io/) - 基于 Qt 和 Spyder 的面向科学应用的 Python 发行版.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Python 扩展包的非官方 Windows 二进制文件.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python 与 .NET 公共语言运行时 (CLR) 集成.
* [PyWin32](https://github.com/mhammond/pywin32) - Windows 的 Python 扩展.
* [WinPython](https://winpython.github.io/) - Windows 7/8 的便携式开发环境.

## Miscellaneous

*不属于上述类别的有用库或工具.*

* [blinker](https://github.com/jek/blinker) - 一个快速的Python进程内信号/事件调度系统.
* [boltons](https://github.com/mahmoud/boltons) - 一组纯Python实用程序.
* [itsdangerous](https://github.com/pallets/itsdangerous) - 各种帮助程序将可信数据传递到不可信环境.
* [magenta](https://github.com/magenta/magenta) - 使用人工智能生成音乐和艺术的工具.
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - 一个简单但灵活的 Python 插件系统.
* [tryton](http://www.tryton.org/) - 通用业务框架.

## Natural Language Processing

*用于处理人类语言的库.*

- 一般
    * [gensim](https://github.com/RaRe-Technologies/gensim) - 人类主题建模.
    * [langid.py](https://github.com/saffsd/langid.py) - 独立的语言识别系统.
    * [nltk](http://www.nltk.org/) - 用于构建 Python 程序以处理人类语言数据的领先平台.
    * [pattern](https://github.com/clips/pattern) - 网络挖掘模块.
    * [polyglot](https://github.com/aboSamoor/polyglot) - 支持数百种语言的自然语言管道.
    * [pytext](https://github.com/facebookresearch/pytext) - 基于 PyTorch 的自然语言建模框架.
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - 一个工具包，可实现快速深度学习 NLP 原型研究.
    * [spacy](https://spacy.io/) - 使用 Python 和 Cython 进行工业级自然语言处理的库.
    * [Stanza](https://github.com/stanfordnlp/stanza) - 斯坦福 NLP Group 的官方 Python 库，支持 60 多种语言.
- 中国人
    * [funNLP](https://github.com/fighting41love/funNLP) - 中文NLP工具和数据集的集合.
    * [jieba](https://github.com/fxsjy/jieba) - 最流行的中文文本分词库.
    * [pkuseg-python](https://github.com/lancopku/pkuseg-python) - 多领域中文分词工具包.
    * [snownlp](https://github.com/isnowfy/snownlp) - 一个用于处理中文文本的库.

## Network Virtualization

*用于虚拟网络和SDN（软件定义网络）的工具和库.*

* [mininet](https://github.com/mininet/mininet) - 用 Python 编写的流行网络模拟器和 API.
* [napalm](https://github.com/napalm-automation/napalm) - 跨供应商 API 来操作网络设备.
* [pox](https://github.com/noxrepo/pox) - 基于Python的SDN控制应用程序，例如OpenFlow SDN控制器.

## News Feed

*用于构建用户活动的库.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - 根据站点上的操作生成通用活动流.
* [Stream Framework](https://github.com/tschellenbach/Stream-Framework) - 使用 Cassandra 和 Redis 构建新闻源和通知系统.

## ORM

*实现对象关系映射或数据映射技术的库.*

* 关系数据库
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - Django ORM.
    * [SQLAlchemy](https://www.sqlalchemy.org/) - Python SQL 工具包和对象关系映射器.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [dataset](https://github.com/pudo/dataset) - 将 Python 字典存储在数据库中 - 与 SQLite、MySQL 和 PostgreSQL 配合使用.
    * [orator](https://github.com/sdispater/orator) - Orator ORM 提供了一个简单而美观的 ActiveRecord 实现.
    * [orm](https://github.com/encode/orm) - 异步 ORM.
    * [peewee](https://github.com/coleifer/peewee) - 一个小型的、富有表现力的 ORM.
    * [pony](https://github.com/ponyorm/pony/) - ORM 提供面向生成器的 SQL 接口.
    * [pydal](https://github.com/web2py/pydal/) - 纯Python数据库抽象层.
* NoSQL 数据库
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Redis 的丰富 Python 数据类型.
    * [mongoengine](https://github.com/MongoEngine/mongoengine) - 用于使用 MongoDB 的 Python 对象文档映射器.
    * [PynamoDB](https://github.com/pynamodb/PynamoDB) - Pythonic 接口 [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
    * [redisco](https://github.com/kiddouk/redisco) - Redis 中保留的简单模型和容器的 Python 库.

## Package Management

*用于包和依赖管理的库.*

* [pip](https://pip.pypa.io/en/stable/) - Python 的包安装程序.
    * [pip-tools](https://github.com/jazzband/pip-tools) - 一组工具，可让您固定的 Python 依赖项保持最新状态.
    * [PyPI](https://pypi.org/)
* [conda](https://github.com/conda/conda/) - 跨平台、与 Python 无关的二进制包管理器.
* [poetry](https://github.com/sdispater/poetry) - Python 依赖管理和打包变得简单.

## Package Repositories

*本地 PyPI 存储库服务器和代理.*

* [bandersnatch](https://github.com/pypa/bandersnatch/) - Python Packaging Authority (PyPA) 提供的 PyPI 镜像工具.
* [devpi](https://github.com/devpi/devpi) - PyPI 服务器和打包/测试/发布工具.
* [localshop](https://github.com/jazzband/localshop) - 本地 PyPI 服务器（自定义包和 pypi 自动镜像）.
* [warehouse](https://github.com/pypa/warehouse) - 下一代 Python 包存储库 (PyPI).

## Penetration Testing

*渗透测试的框架和工具.*

* [fsociety](https://github.com/Manisso/fsociety) - 渗透测试框架.
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) - 社会工程工具包.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动 SQL 注入和数据库接管工具.

## Permissions

*允许或拒绝用户访问数据或功能的库.*

* [django-guardian](https://github.com/django-guardian/django-guardian) - Django 1.2+ 的每个对象权限的实现
* [django-rules](https://github.com/dfunckt/django-rules) - 一个微小但功能强大的应用程序，无需数据库即可为 Django 提供对象级权限.

## Processes

*用于启动操作系统进程并与操作系统进程通信的库.*

* [delegator.py](https://github.com/amitt001/delegator.py) - [Subprocesses](https://docs.python.org/3/library/subprocess.html) 为人类2.0.
* [sarge](https://sarge.readthedocs.io/en/latest/) - 子流程的另一个包装器.
* [sh](https://github.com/amoffat/sh) - Python 的成熟子进程替代品.

## Recommender Systems

*用于构建推荐系统的库.*

* [annoy](https://github.com/spotify/annoy) - C++/Python 中的近似最近邻针对内存使用进行了优化.
* [fastFM](https://github.com/ibayer/fastFM) - 因式分解机的库.
* [implicit](https://github.com/benfred/implicit) - 隐式数据集协同过滤的快速 Python 实现.
* [libffm](https://github.com/guestwalk/libffm) - 现场感知分解机（FFM）的库.
* [lightfm](https://github.com/lyst/lightfm) - 许多流行推荐算法的 Python 实现.
* [spotlight](https://github.com/maciejkula/spotlight) - 使用 PyTorch 的深度推荐模型.
* [Surprise](https://github.com/NicolasHug/Surprise) - 用于构建和分析推荐系统的 scikit.
* [tensorrec](https://github.com/jfkirk/tensorrec) - TensorFlow 中的推荐引擎框架.

## Refactoring

*Python 重构工具和库*

 * [Bicycle Repair Man](http://bicyclerepair.sourceforge.net/) - Bicycle Repair Man，Python 的重构工具.
 * [Bowler](https://pybowler.io/) - 现代 Python 的安全代码重构.
 * [Rope](https://github.com/python-rope/rope) - Rope 是一个Python 重构库.

## RESTful API

*用于构建 RESTful API 的库.*

* 姜戈
    * [django-rest-framework](http://www.django-rest-framework.org/) - 用于构建 Web API 的强大而灵活的工具包.
    * [django-tastypie](http://tastypieapi.org/) - 为 Django 应用程序创建美味的 API.
* 烧瓶
    * [eve](https://github.com/pyeve/eve) - 由 Flask、MongoDB 和良好意愿提供支持的 REST API 框架.
    * [flask-api](https://github.com/flask-api/flask-api) - Flask 的可浏览 Web API.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - 快速构建 Flask 的 REST API.
* 金字塔
    * [cornice](https://github.com/Cornices/cornice) - Pyramid 的 RESTful 框架.
* 框架不可知
    * [apistar](https://github.com/encode/apistar) - 一个智能 Web API 框架，专为 Python 3 设计.
    * [falcon](https://github.com/falconry/falcon) - 用于构建云 API 和 Web 应用程序后端的高性能框架.
    * [fastapi](https://github.com/tiangolo/fastapi) - 一个现代、快速的 Web 框架，用于基于标准 Python 类型提示使用 Python 3.6+ 构建 API.
    * [hug](https://github.com/hugapi/hug) - 用于干净地公开 API 的 Python 3 框架.
    * [sandman2](https://github.com/jeffknupp/sandman2) - 适用于现有数据库驱动系统的自动化 REST API.
    * [sanic](https://github.com/huge-success/sanic) - 专为快速运行而编写的 Python 3.6+ Web 服务器和 Web 框架.
    * [vibora](https://vibora.io/) - 受 Flask 启发的快速、高效和异步 Web 框架.

## Robotics

*机器人图书馆.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - 这是各种机器人算法与可视化的汇编.
* [rospy](http://wiki.ros.org/rospy) - 这是 ROS（机器人操作系统）的库.

## RPC Servers

*RPC兼容服务器.*

* [RPyC](https://github.com/tomerfiliba/rpyc) (Remote Python Call) - Python 的透明且对称的 RPC 库
* [zeroRPC](https://github.com/0rpc/zerorpc-python) - Zerorpc是一个基于的灵活的RPC实现 [ZeroMQ](http://zeromq.org/) 和 [MessagePack](http://msgpack.org/).

## Science

 *科学计算库. 另请参阅 [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists).*

* [astropy](http://www.astropy.org/) - 天文学社区 Python 库.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - 为全自动高通量测序分析提供最佳实践流程.
* [bccb](https://github.com/chapmanb/bcbb) - 与生物分析相关的有用代码的收集.
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython 是一组免费的生物计算工具.
* [cclib](http://cclib.github.io/) - 用于解析和解释计算化学包结果的库.
* [Colour](http://colour-science.org/) - 实施全面的颜色理论转换和算法.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) - 用于图结构化数据的无监督机器学习工具箱.
* [NetworkX](https://networkx.github.io/) - 适用于复杂网络的高生产力软件.
* [NIPY](http://nipy.org) - 神经影像工具包的集合.
* [NumPy](http://www.numpy.org/) - 使用 Python 进行科学计算的基本包.
* [ObsPy](https://github.com/obspy/obspy/wiki/) - 用于地震学的 Python 工具箱.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - 一个化学工具箱，旨在使用多种化学数据语言.
* [PyDy](http://www.pydy.org/) - Python Dynamics 的缩写，用于协助动态运动建模的工作流程.
* [PyMC](https://github.com/pymc-devs/pymc3) - 马尔可夫链蒙特卡罗采样工具包.
* [QuTiP](http://qutip.org/) - Python 中的量子工具箱.
* [RDKit](http://www.rdkit.org/) - 化学信息学和机器学习软件.
* [SciPy](https://www.scipy.org/) - 基于 Python 的数学、科学和工程开源软件生态系统.
* [SimPy](https://gitlab.com/team-simpy/simpy) - 基于过程的离散事件模拟框架.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Python 中的统计建模和计量经济学.
* [SymPy](https://github.com/sympy/sympy) - 用于符号数学的 Python 库.
* [Zipline](https://github.com/quantopian/zipline) - Pythonic 算法交易库.

## Search

*用于对数据进行索引和执行搜索查询的库和软件.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Django 的模块化搜索.
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - Elasticsearch 的官方高级 Python 客户端.
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - 官方低级Python客户端 [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [pysolr](https://github.com/django-haystack/pysolr) - 一个轻量级的Python包装器 [Apache Solr](https://lucene.apache.org/solr/).
* [whoosh](http://whoosh.readthedocs.io/en/latest/) - 一个快速、纯Python 搜索引擎库.

## Serialization

*用于序列化复杂数据类型的库*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) - 一个轻量级库，用于在复杂对象与简单 Python 数据类型之间进行转换.
* [pysimdjson](https://github.com/TkTech/pysimdjson) - Python 绑定 [simdjson](https://github.com/lemire/simdjson).
* [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson) - Python 包装器 [RapidJSON](https://github.com/Tencent/rapidjson).
* [ultrajson](https://github.com/esnme/ultrajson) - 使用 C 语言编写并带有 Python 绑定的快速 JSON 解码器和编码器.

## Serverless Frameworks

*用于开发无服务器 Python 代码的框架.*

* [python-lambda](https://github.com/nficano/python-lambda) - 用于在 AWS Lambda 中开发和部署 Python 代码的工具包.
* [Zappa](https://github.com/zappa/Zappa) - 用于在 AWS Lambda 和 API Gateway 上部署 WSGI 应用程序的工具.

## Shell

*基于Python的Shell.*

* [xonsh](https://github.com/xonsh/xonsh/) - 一种基于 Python 的、跨平台的、面向 Unix 的 shell 语言和命令提示符.

## Specific Formats Processing

*用于解析和操作特定文本格式的库.*

* 一般
    * [tablib](https://github.com/jazzband/tablib) - XLS、CSV、JSON、YAML 格式的表格数据集模块.
* 办公室
    * [docxtpl](https://github.com/elapouya/python-docx-template) - 通过jinja2模板编辑docx文档
    * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - 用于读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - 提供一个 API 用于读取、操作和写入 csv、ods、xls、xlsx 和 xlsm 文件.
    * [python-docx](https://github.com/python-openxml/python-docx) - 读取、查询和修改 Microsoft Word 2007/2008 docx 文件.
    * [python-pptx](https://github.com/scanny/python-pptx) - 用于创建和更新 PowerPoint (.pptx) 文件的 Python 库.
    * [unoconv](https://github.com/unoconv/unoconv) - 在 LibreOffice/OpenOffice 支持的任何文档格式之间进行转换.
    * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - 用于创建 Excel .xlsx 文件的 Python 模块.
    * [xlwings](https://github.com/ZoomerAnalytics/xlwings) - 一个 BSD 许可的库，可以轻松地从 Excel 调用 Python，反之亦然.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - 从 Excel 文件写入和读取数据以及格式化信息.
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - 从 PDF 文档中提取信息的工具.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - 能够拆分、合并和转换 PDF 页面的库.
    * [ReportLab](https://www.reportlab.com/opensource/) - 允许快速创建丰富的 PDF 文档.
* 降价
    * [Mistune](https://github.com/lepture/mistune) - 最快且功能齐全的 Markdown 纯 Python 解析器.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - John Gruber 的 Markdown 的 Python 实现.
* yaml
    * [PyYAML](http://pyyaml.org/) - Python 的 YAML 实现.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV.
* 档案
    * [unp](https://github.com/mitsuhiko/unp) - 一个可以轻松解压档案的命令行工具.

## Static Site Generator

*静态站点生成器是一个软件，它以一些文本+模板作为输入并在输出上生成 HTML 文件.*

* [lektor](https://github.com/lektor/lektor) - 易于使用的静态 CMS 和博客引擎.
* [mkdocs](https://github.com/mkdocs/mkdocs/) - Markdown 友好的文档生成器.
* [makesite](https://github.com/sunainapai/makesite) - 简单、轻量级且无魔法的静态站点/博客生成器（&lt; 130 行）.
* [nikola](https://github.com/getnikola/nikola) - 静态网站和博客生成器.
* [pelican](https://github.com/getpelican/pelican) - 支持 Markdown 和 reST 语法的静态站点生成器.

## Tagging

*用于标记项目的库.*

* [django-taggit](https://github.com/jazzband/django-taggit) - Django 的简单标记.

## Task Queues

*用于处理任务队列的库.*

* [celery](https://docs.celeryproject.org/en/stable/) - 基于分布式消息传递的异步任务队列/作业队列.
* [dramatiq](https://github.com/Bogdanp/dramatiq) - 适用于 Python 3 的快速可靠的后台任务处理库.
* [huey](https://github.com/coleifer/huey) - 小型多线程任务队列.
* [mrq](https://github.com/pricingassistant/mrq) - 使用 Redis 和 gevent 的 Python 分布式工作任务队列.
* [rq](https://github.com/rq/rq) - Python 的简单作业队列.

## Template Engine

*用于模板和词法分析的库和工具.*

* [Genshi](https://genshi.edgewall.org/) - 用于生成 Web 感知输出的 Python 模板工具包.
* [Jinja2](https://github.com/pallets/jinja) - 一种现代且设计师友好的模板语言.
* [Mako](http://www.makotemplates.org/) - 适用于 Python 平台的超快速且轻量级模板.

## Testing

*用于测试代码库和生成测试数据的库.*

* 测试框架
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis) - Hypothesis 是一个先进的 Quickcheck 风格的基于属性的测试库.
    * [nose2](https://github.com/nose-devs/nose2) - “nose”的后继者，基于“unittest2”.
    * [pytest](https://docs.pytest.org/en/latest/) - 成熟的全功能Python测试工具.
    * [Robot Framework](https://github.com/robotframework/robotframework) - 通用测试自动化框架.
    * [unittest](https://docs.python.org/3/library/unittest.html) -（Python 标准库）单元测试框架.
* 测试运行者
    * [green](https://github.com/CleanCut/green) - 干净、色彩丰富的测试运行程序.
    * [mamba](http://nestorsalceda.github.io/mamba/)  - Python 的权威测试工具. 诞生于BDD的旗帜下.
    * [tox](https://tox.readthedocs.io/en/latest/) - 在多个 Python 版本中自动构建和测试发行版
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) - 用 Python 编写的可扩展用户负载测试工具.
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI 是一个面向人类的跨平台 GUI 自动化 Python 模块.
    * [Schemathesis](https://github.com/kiwicom/schemathesis) - 用于对使用 Open API / Swagger 规范构建的 Web 应用程序进行基于属性的自动测试的工具.
    * [Selenium](https://pypi.org/project/selenium/) - Python 绑定 [Selenium](http://www.seleniumhq.org/) 网络驱动程序.
    * [sixpack](https://github.com/seatgeek/sixpack) - 与语言无关的 A/B 测试框架.
    * [splinter](https://github.com/cobrateam/splinter) - 用于测试 Web 应用程序的开源工具.
* 嘲笑
    * [doublex](https://pypi.org/project/doublex/) - 强大的 Python 测试双打框架.
    * [freezegun](https://github.com/spulec/freezegun) - 通过模拟日期时间模块来穿越时间.
    * [httmock](https://github.com/patrys/httmock) - 用于 Python 2.6+ 和 3.2+ 请求的模拟库.
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - Python 的 HTTP 请求模拟工具.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - （Python 标准库）模拟和修补库.
    * [mocket](https://github.com/mindflayer/python-mocket) - 支持 gevent/asyncio/SSL 的套接字模拟框架.
    * [responses](https://github.com/getsentry/responses) - 用于模拟请求 Python 库的实用程序库.
    * [VCR.py](https://github.com/kevin1024/vcrpy) - 记录并重放测试中的 HTTP 交互.
* 对象工厂
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) - Python 的测试装置替代品.
    * [mixer](https://github.com/klen/mixer)  - 另一个固定装置更换. 支持Django、Flask、SQLAlchemy、Peewee等.
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - 创建随机装置用于在 Django 中进行测试.
* 代码覆盖率
    * [coverage](https://pypi.org/project/coverage/) - 代码覆盖率测量.
* 虚假数据
    * [fake2db](https://github.com/emirozer/fake2db) - 假数据库生成器.
    * [faker](https://github.com/joke2k/faker) - 一个生成假数据的 Python 包.
    * [mimesis](https://github.com/lk-geimfari/mimesis) - 是一个Python库，可以帮助你生成假数据.
    * [radar](https://pypi.org/project/radar/) - 生成随机日期时间/时间.

## Text Processing

*用于解析和操作纯文本的库.*

* 一般
    * [chardet](https://github.com/chardet/chardet) - Python 2/3 兼容的字符编码检测器.
    * [difflib](https://docs.python.org/3/library/difflib.html) -（Python 标准库）用于计算增量的帮助程序.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - 自动减少 Unicode 文本的损坏并使其更加一致.
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - 模糊字符串匹配.
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - 快速计算编辑距离和字符串相似度.
    * [pangu.py](https://github.com/vinta/pangu.py) - 偏执的文本间距.
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - 用 Python 编写的Figlet 的实现.
    * [pypinyin](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi (汉字) to pinyin (拼音).
    * [textdistance](https://github.com/orsinium/textdistance) - 使用 30 多种算法计算序列之间的距离.
    * [unidecode](https://pypi.org/project/Unidecode/) - ASCII transliterations of Unicode text.
* 斯拉格化
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - 一个可以保留 unicode 的 Python slugify 库.
    * [python-slugify](https://github.com/un33k/python-slugify) - 一个将 unicode 转换为 ASCII 的 Python slugify 库.
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - 一个 slugifier，它以 Django 作为依赖项生成 unicode slugs.
* 唯一标识符
    * [hashids](https://github.com/davidaurelio/hashids-python) - 实施 [hashids](http://hashids.org) 在Python中.
    * [shortuuid](https://github.com/skorokithakis/shortuuid) - 用于简洁、明确且 URL 安全的 UUID 的生成器库.
* 解析器
    * [ply](https://github.com/dabeaz/ply) - Python 的 lex 和 yacc 解析工具的实现.
    * [pygments](http://pygments.org/) - 通用语法荧光笔.
    * [pyparsing](https://github.com/pyparsing/pyparsing) - 用于生成解析器的通用框架.
    * [python-nameparser](https://github.com/derek73/python-nameparser) - 将人名解析为各个组成部分.
    * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - 解析、格式化、存储和验证国际电话号码.
    * [python-user-agents](https://github.com/selwin/python-user-agents) - 浏览器用户代理解析器.
    * [sqlparse](https://github.com/andialbrecht/sqlparse) - 非验证 SQL 解析器.

## Third-party APIs

 *用于访问第三方服务 API 的库. 另请参阅 [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) - 适用于所有云的一个 Python 库.
* [boto3](https://github.com/boto/boto3) - Amazon Web Services 的 Python 接口.
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) - Django 的 WordPress 模型和视图.
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook 平台 Python SDK.
* [google-api-python-client](https://github.com/google/google-api-python-client) - 适用于 Python 的 Google API 客户端库.
* [gspread](https://github.com/burnash/gspread) - 谷歌电子表格Python API.
* [twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API.

## URL Manipulation

*用于解析 URL 的库.*

* [furl](https://github.com/gruns/furl) - 一个小型 Python 库，可以轻松解析和操作 URL.
* [purl](https://github.com/codeinthehole/purl) - 一个简单、不可变的 URL 类，具有用于询问和操作的干净 API.
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - 一个纯 Python URL 缩短库.
* [webargs](https://github.com/marshmallow-code/webargs) - 一个友好的库，用于解析 HTTP 请求参数，并内置对流行 Web 框架的支持.

## Video

*用于操作视频和 GIF 的库.*

* [moviepy](https://zulko.github.io/moviepy/) - 用于基于脚本的电影编辑模块，具有多种格式，包括动画 GIF.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.
* [vidgear](https://github.com/abhiTronix/vidgear) - 最强大的多线程视频处理框架.

## Web Asset Management

*用于管理、压缩和缩小网站资产的工具.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - 将链接和内联 JavaScript 或 CSS 压缩到单个缓存文件中.
* [django-pipeline](https://github.com/jazzband/django-pipeline) - Django 的资产打包库.
* [django-storages](https://github.com/jschneier/django-storages) - Django 自定义存储后端的集合.
* [fanstatic](http://www.fanstatic.org/en/latest/) - 将静态文件依赖项打包、优化并作为 Python 包提供服务.
* [fileconveyor](http://wimleers.com/fileconveyor) - 用于检测文件并将其同步到 CDN、S3 和 FTP 的守护进程.
* [flask-assets](https://github.com/miracle2k/flask-assets) - 帮助您将网络资产集成到 Flask 应用程序中.
* [webassets](https://github.com/miracle2k/webassets) - 捆绑、优化和管理静态资源的独特缓存清除 URL.



* [html2text](https://github.com/Alir3z4/html2text) - 将 HTML 转换为 Markdown 格式的文本.
* [python-readability](https://github.com/buriy/python-readability) - arc90 可读性工具的快速 Python 端口.
* [requests-html](https://github.com/psf/requests-html) - 人类的 Pythonic HTML 解析.
* [sumy](https://github.com/miso-belica/sumy) - 用于自动摘要文本文档和 HTML 页面的模块.
* [textract](https://github.com/deanmalmgren/textract) - 从任何文档、Word、PowerPoint、PDF 等中提取文本.
* [toapi](https://github.com/gaojiuli/toapi) - 每个网站都提供 API.

## Web Crawling

*自动化网页抓取的库.*

* [cola](https://github.com/chineking/cola) - 分布式爬行框架.
* [feedparser](https://pythonhosted.org/feedparser/) - 通用提要解析器.
* [grab](https://github.com/lorien/grab) - 网站抓取框架.
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - 用于自动与网站交互的 Python 库.
* [portia](https://github.com/scrapinghub/portia) - Scrapy 的视觉抓取.
* [pyspider](https://github.com/binux/pyspider) - 强大的蜘蛛系统.
* [robobrowser](https://github.com/jmcarp/robobrowser) - 一个简单的 Python 库，无需独立的 Web 浏览器即可浏览 Web.
* [scrapy](https://scrapy.org/) - 快速的高级屏幕抓取和网络爬行框架.

## Web Frameworks

 *传统的全栈Web框架. 另请参阅 [RESTful API](https://github.com/vinta/awesome-python#restful-api).*

* 同步
    * [Django](https://www.djangoproject.com/) - Python 中最流行的 Web 框架.
        * [awesome-django](https://github.com/shahraizali/awesome-django)
        * [awesome-django](https://github.com/wsvincent/awesome-django)
    * [Flask](http://flask.pocoo.org/) - Python 的微框架.
        * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
    * [Pyramid](https://pylonsproject.org/) - 一个小型、快速、实用、开源的 Python Web 框架.
        * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)
    * [Masonite](https://github.com/MasoniteFramework/masonite) - 现代且以开发人员为中心的 Python Web 框架.
* 异步
    * [Tornado](http://www.tornadoweb.org/en/latest/) - Web 框架和异步网络库.

## WebSocket

*用于使用 WebSocket 的库.*

* [autobahn-python](https://github.com/crossbario/autobahn-python) - Twisted 上用于 Python 的 WebSocket 和 WAMP [asyncio](https://docs.python.org/3/library/asyncio.html).
* [channels](https://github.com/django/channels) - Django 开发人员友好的异步.
* [websockets](https://github.com/aaugustin/websockets) - 用于构建 WebSocket 服务器和客户端的库，重点关注正确性和简单性.

## WSGI Servers

*兼容 WSGI 的 Web 服务器.*

* [bjoern](https://github.com/jonashaag/bjoern) - 异步，非常快，用 C 编写.
* [gunicorn](https://github.com/benoitc/gunicorn) - 预分叉，从 Ruby 的 Unicorn 项目移植.
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - 一个项目旨在开发用于构建托管服务的完整堆栈，用 C 编写.
* [waitress](https://github.com/Pylons/waitress) - 多线程，为 Pyramid 提供动力.
* [werkzeug](https://github.com/pallets/werkzeug) - 用于 Python 的 WSGI 实用程序库，为 Flask 提供支持，并且可以轻松嵌入到您自己的项目中.

## Resources

在哪里可以发现学习资源或新的 Python 库.

## Books

- [Fluent Python](https://www.oreilly.com/library/view/fluent-python/9781491946237/)
- [Think Python](https://greenteapress.com/wp/think-python-2e/)

## Websites

* 教程
    * [Full Stack Python](https://www.fullstackpython.com/)
    * [Python Cheatsheet](https://www.pythoncheatsheet.org/)
    * [Real Python](https://realpython.com)
    * [The Hitchhiker’s Guide to Python](https://docs.python-guide.org/)
    * [Ultimate Python study guide](https://github.com/huangsam/ultimate-python)
* 图书馆
    * [Awesome Python @LibHunt](https://python.libhunt.com/)
* 其他
    * [Python ZEEF](https://python.zeef.com/alan.richmond)
    * [Pythonic News](https://news.python.sc/)
    * [What the f*ck Python!](https://github.com/satwikkansal/wtfpython)

## Newsletters

* [Awesome Python Newsletter](http://python.libhunt.com/newsletter)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Tricks](https://realpython.com/python-tricks/)
* [Python Weekly](http://www.pythonweekly.com/)

## Podcasts

* [Django Chat](https://djangochat.com/)
* [Podcast.\_\_init__](https://podcastinit.com/)
* [Python Bytes](https://pythonbytes.fm)
* [Running in Production](https://runninginproduction.com/)
* [Talk Python To Me](https://talkpython.fm/)
* [Test and Code](https://testandcode.com/)
* [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

## Contributing

随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) 第一的.

如果我不确定这些库是否很棒，我会保留一些拉取请求，您可以 [vote for them](https://github.com/vinta/awesome-python/pulls) 通过添加 :+1: 给它们. 当投票达到 **20** 时，Pull 请求将被合并.

- - -

如果您对此固执己见的列表有任何疑问，请随时与我联系 [@VintaChen](https://twitter.com/VintaChen) 在 Twitter 上或在 GitHub 上提出问题.
