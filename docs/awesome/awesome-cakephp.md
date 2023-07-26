<div class="github-widget" data-repo="friendsofcake/awesome-cakephp"></div>
## Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
令人惊叹的 **CakePHP 4.x+** 插件、资源和闪亮事物的精选列表.

带有“”图标的插件也具有 CakePHP 5 兼容版本（最低“测试版”）.

如果您正在寻找以前的 CakePHP 资源，请访问：
- 这 [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) 在这个很棒的清单中
- 这 [CakePHP 3.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake3) 在这个很棒的清单中
- 这个维基有一个 [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

您可能会发现有用的其他列表：
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

 &gt; 对于那些想知道的人； 该列表与plugins.cakephp.org 的不同之处在于支持
&gt; 插件子部分（而不是整个插件/存储库），更细粒度
&gt; 分组并主要关注任务特定功能.



## Plugins

## APM
*用于应用程序性能监控的插件.*


## Architecture

- [Burzum/CakeServiceLayer plugin](https://github.com/burzum/cakephp-service-layer) - 服务层和领域/业务模型实现.

## Asset Management
*用于管理、压缩和缩小网站资产的工具.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
- [AssetMix plugin](https://github.com/ishanvyas22/asset-mix) - 提供与 [Laravel Mix](https://laravel-mix.com) 资产编译.

## Auditing / Logging
*用于审计和日志记录的插件.*

- [AuditStash plugin](https://github.com/lorenzo/audit-stash) - 灵活且坚如磐石的审计日志跟踪.
- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - 简单且独立的日志记录到数据库而不是文件.
- [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - 允许将当前登录用户传递到模型层的插件.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - 一个促进版本化数据库实体的插件.

## Authentication and Authorization
*用于实现身份验证和授权的插件和库.*

- [Acl plugin](https://github.com/cakephp/acl/) - 将 ACL 作为数据库方法进行管理.
- [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - 使用 JSON Web 令牌进行身份验证的插件.
- [ADmad/SocialAuth plugin](https://github.com/ADmad/cakephp-social-auth) - 一个插件，允许您使用 Facebook/Google/Twitter 等社交提供商进行身份验证 [SocialConnect/auth](https://github.com/SocialConnect/auth) 图书馆上的社交标志.
- [Authentication plugin](https://github.com/cakephp/authentication) - 官方 CakePHP 身份验证中间件插件.
- [Authorization plugin](https://github.com/cakephp/authorization) - 官方 CakePHP 授权堆栈.
- [CakeDC/Users plugin](https://github.com/CakeDC/users) - 完整的用户管理（管理面板、记住我等）、社交登录（FB、Twitter、LinkedIn、Google、Instagram）、RBAC、API 等.
- [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - 事件驱动行为，可轻松生成一次性安全令牌.
- [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - 身份验证和基于角色（单/多）授权作为非常轻量级的方法.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - 含有 [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) 用于密码散列的 DRY 方法.
- [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth)  - 允许使用 Google Authenticator 或类似应用程序进行两因素身份验证以生成一次性代码. 基于 [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) 图书馆.

## Caching
*用于缓存数据的插件.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - 用于将视图（HTML、CSV、JSON、XML...）缓存为静态缓存文件.

## Code Analysis
*用于分析、解析和操作代码库的插件.*

- [CakeDC/PHPStan](https://github.com/CakeDC/cakephp-phpstan) - PHPStan 扩展，用于解决静态分析器 getter 返回类型周围的 CakePHP 魔法.
- [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - 通过向现有代码添加注释（类似于烘焙对新代码的作用），有助于更好地支持 IDE.
- [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - 提供测试增强功能和 TDD 支持作为浏览器后端.

## Debugging
*用于调试和本地开发的插件.*

- [AssociationsDebugger plugin](https://github.com/zunnu/associations-debugger) - 将模型关联绘制为图表的插件.
- [CakephpWhoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP 错误和异常，适合酷孩子 [filp/whoops](https://github.com/filp/whoops).
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - 调试的事实上的标准.
- [Execution order](https://github.com/dereuromark/executionorder) - 一个演示应用程序，用于显示文件、方法和回调的执行顺序.
- [Sentry plugin](https://github.com/lordsimal/cakephp-sentry) 一个无缝集成 Sentry 错误和异常的插件.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - 包含调试和维护工具的轻量级设置插件.

## Dependency Injection
*实现依赖注入设计模式的插件.*


## E-commerce
*用于付款和建立在线电子商务商店的插件和应用程序.*


## Email
*用于发送和解析电子邮件的插件.*

- [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - 带有预览和发件人外壳的电子邮件队列插件.
- [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - 电子邮件传输插件，用于通过 Mailgun 发送电子邮件.

## Environment
*环境插件.*


## File Manipulation
*用于文件操作的插件.*

- [FileStorage plugin](https://github.com/dereuromark/cakephp-file-storage) - 灵活的文件存储和上传插件.
- [Josbeir/Filesystem plugin](https://github.com/josbeir/cakephp-filesystem) - 抽象 [Flysystem](https://flysystem.thephpleague.com/) + 基于文件实体的上传插件.
- [Josegonzalez/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - 一个可定制的插件，使用 [Flysystem](https://flysystem.thephpleague.com/) 写入多个后端（Dropbox、FTP、S3、本地等）.

## Filtering and Validation
*用于过滤和验证数据的插件.*


## Geolocation
*用于对地址进行地理编码并处理纬度和经度的插件.*

- [Geo plugin](https://github.com/dereuromark/cakephp-geo) - 含有 [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) 和 [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## HTTP
*用于 HTTP 和客户端抽象的插件*

- [Http/Adapter/Cake library](https://github.com/php-http/cakephp-adapter) - 适配器 [HTTPlug](https://github.com/php-http/httplug) HTTP 客户端抽象.

## I18n
*I18n（国际化）和 L10n（本地化）插件.*

- [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - 带有 I18n 相关工具的插件.
- [Cake/Localized plugin](https://github.com/cakephp/localized) - 本地化验证和即用型翻译 PO 文件.
- [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - 具有基于影子表的核心翻译行为替换的插件.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate)  - 通过网络后端轻松管理静态内容的翻译，包括. 从 POT 文件导入，通过 API 自动建议和自动翻译.

## Imagery
*用于操作图像的插件.*

- [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - 一个使用插件 [Glide](https://glide.thephpleague.com/) 图像处理库.

## Libs
*不属于任何其他类别的有用的库或工具.*

- [Capcake](https://github.com/jadb/capcake) - 使用 Capistrano 部署 CakePHP 应用程序.
- [Chronos](https://github.com/cakephp/chronos) - 一个简单的独立 DateTime API 扩展（Carbon 的继承者）.
- [Composer Installers](https://github.com/composer/installers) - 多框架 Composer 库安装程序.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - 包和依赖项管理器.
- [Graphviz](https://github.com/alexandresalome/graphviz) - Graphviz 库.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP 任务运行器和部署包.
- [makallio85/YamlRoute plugin](https://github.com/makallio85/yaml-route) - 使用简单的 YAML 文件配置路由.

## Markup
*用于处理标记的插件.*

- [Markup plugin](https://github.com/dereuromark/cakephp-markup) - 允许使用基于 PHP 或 JS 的语法突出显示.

## Migration
*有关迁移和升级的插件和资源.*

- [Migrations plugin](https://github.com/cakephp/migrations) - (DB) 迁移插件.
- [Upgrade app](https://github.com/cakephp/upgrade) - 2.x=&gt;3.x 和 3.x=&gt;4.x 的官方升级应用程序.
- [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - 2.x=&gt;3.x 的扩展升级应用程序，介于 3.x 和一些 4.x 代码片段之间.
- [Upgrade/Migration Guide](https://book.cakephp.org/4.0/en/appendices.html) - 官方迁移指南.

## Miscellaneous
*杂项插件和库.*

- [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - 一个简化处理 AJAX 请求的插件.
- [CakeDC/Enum plugin](https://github.com/CakeDC/enum) - 一个为您的应用程序添加枚举列表支持的插件.
- [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) - 快速为您的应用程序生成有用的数据传输对象（可变/不可变），替换杂乱的数组并通过类型提示和自动完成来利用您的 IDE.
- [CakeImpersonate plugin](https://github.com/jomweb/CakeImpersonate)  - 存储当前身份验证会话并为模拟用户创建新会话的组件. 用户可以恢复到原始身份验证会话，而无需重新登录.
- [Calendar plugin](https://github.com/dereuromark/cakephp-calendar)  - 用于生成基本日历. 包括用于生成 ICS 日历文件的 IcalView.
- [Feedback plugin](https://github.com/dereuromark/cakephp-feedback)  - 允许访客发送快速、简单的反馈，包括. 通过侧边栏形式的屏幕截图.
- [Flash plugin](https://github.com/dereuromark/cakephp-flash) - 为您的应用程序提供更强大的闪存消息.
- [OPCache Preloader](https://github.com/cnizzardini/cakephp-preloader) - CakePHP 4.x 应用程序的 OPCache 预加载器. 
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - 维护 shell 进入维护模式以处理所有具有可选 IP 白名单的请求.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - 一个包含有用的垫片和改进的插件，作为您的应用程序的基础.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - 包含许多有用的库、帮助器、行为、组件、shell 等.

## Navigation
*用于构建导航结构的工具.*

- [Icings/Menu plugin](https://github.com/icings/menu) - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) CakePHP 的经验丰富的菜单插件.

## NoSQL
*用于使用“NoSQL”后端的插件.*

## Notifications
*用于使用通知软件的插件.*


## ORM / Database / Datamapping
*实现对象关系映射或数据映射技术的插件.*

- [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - 维护有序记录列表的行为.
- [CakeDecimal plugin](https://github.com/dereuromark/cakephp-decimal) - 处理小数的值对象方法.
- [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - 复制实体（包括相关数据）的行为.
- [Lampager/Cake plugin](https://github.com/lampager/lampager-cakephp) - 无需使用OFFSET即可快速分页.
- [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - 允许为您的表设置默认顺序.
- [Muffin/Sti plugin](https://github.com/UseMuffin/Sti) - CakePHP 的单表继承. 
- [Muffin/Trash plugin](https://github.com/usemuffin/trash) - CakePHP 的软删除行为.
- [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - 单表继承（STI）插件.
- [RowLocker plugin](https://github.com/lorenzo/row-locker) - 表中行的独占锁.
- [Muffin/Webservices ORM plugin](https://github.com/usemuffin/webservice) - 类似 ORM 的 Web 服务接口.
- [Connehito/CakephpMasterReplica plugin](https://github.com/Connehito/cakephp-master-replica) - 切换主/副本数据库连接.
- [Itosho/EasyQuery plugin](https://github.com/itosho/easy-query) - 轻松生成一些复杂查询的行为，例如（批量）插入/更新插入等.
- [Icings/Partitionable plugin](https://github.com/icings/partitionable) - 可分区的关联允许对每个组进行基本限制.

## PDF
*用于处理 PDF 文件的插件和软件.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - 一个围绕 PDF 生成的插件.

## Queue
*用于处理事件和任务队列的插件.*

- [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - 一个提供与各种后端（BeanstalkD、MySQL、Redis 等）的队列集成的插件.
- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - 最小且无依赖性的队列解决方案.
- [Queue plugin](https://github.com/cakephp/queue) - CakePHP 核心队列系统 [php-queue](https://php-enqueue.github.io) 队列库.

## REST and API
*用于开发 REST-ful API 的插件和 Web 工具.*

- [CRUD plugin](https://github.com/FriendsOfCake/crud) - CakePHP 类固醇应用程序开发 - 快速原型设计/脚手架和生产就绪代码.
- [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - 使用 swagger-php 和 swagger-ui 的 CakePHP API 的 Swagger 2.0 文档.
- [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api)  - 一体化解决方案，提供完整的 API. 它包括版本控制、渲染器、CRUD、身份验证、扩展（分页、过滤器、HATEOAS）等等.
- [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - 一个允许使用的插件 [Fractal transformers](https://fractal.thephpleague.com/transformers/) 用于您的 API 输出.
- [MixerApi](https://mixerapi.com) - 为您的团队 CakePHP 项目简化现代 RESTful API 的开发.
- [SwaggerBake plugin](https://github.com/cnizzardini/cakephp-swagger-bake) - 该插件自动根据现有模型和路线构建 OpenAPI，以便在 Swagger 和 Redoc 中显示.

## Search
*用于对数据进行索引和执行搜索查询的插件和软件.*

- [Cake/ElasticSearch plugin](https://github.com/cakephp/elastic-search) - 替代 ORM 使用 [Elasticsearch](https://www.elastic.co/) 作为其后端.
- [PlumSearch plugin](https://github.com/skie/plum_search)  - 搜索插件实现自定义、灵活且可扩展的搜索策略. 实现 PRG 模式.
- [Search plugin](https://github.com/FriendsOfCake/search) - 使用 PRG 模式为分页视图提供轻松搜索/过滤.
- [Tags plugin](https://github.com/dereuromark/cakephp-tags) - 用于标记和查找标记记录.

## Security
*有关安全的插件和信息，防止漏洞并防范 XSS 等.*

- [Bruteforce](https://github.com/Ali1/cakephp-bruteforce/) - 在不涉及数据库的情况下向您的安装添加暴力保护的简单方法.
- [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - 简单、不显眼且可扩展的验证码解决方案默认提供基于图像的数学验证码.
- [Expose plugin](https://github.com/dereuromark/cakephp-expose) - 通过额外的 UUID 而不是 AIID 主键来公开实体，以混淆与这些数字排序值关联的 ID 和数据.
- [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - 使用 UUID、HashId、Optimus、Tiny 和/或自定义混淆策略进行主键混淆/缩短.
- [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - 速率限制 (API) 请求的插件.
- [Recaptcha plugin](https://github.com/ctlabvn/Recaptcha) - 简单、轻量级的 Google Recaptcha v2.

## SEO
*搜索引擎优化.*

- [Muffin/Slug plugin](https://github.com/UseMuffin/Slug)  - 用于生成 slug 并通过 slug 查找记录的插件. 使用可插入架构，允许使用您自己的 slug 生成器类.
- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - 包含 Slugged 行为，可从标题自动生成 URL 兼容的 slugs.

## Skeleton
*围绕应用程序骨架的插件和存储库.*

- [App template](https://github.com/cakephp/app) - 一个与 Composer 一起使用的空 CakePHP 项目.
- [MixerApi/Bake](https://github.com/mixerapi/bake) - 烘焙主题以生成 RESTful 控制器.

## Social
*围绕社交功能的插件.*

- [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - 允许用户对记录进行评分并显示评分.

## Templating
*用于模板和词法分析的插件.*

- [Bake plugin](https://github.com/cakephp/bake) - 提供代码生成功能.
- [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 3 集成.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - 一个可以轻松生成 CSV 的视图类.
- [Feed plugin](https://github.com/dereuromark/cakephp-feed) - 包含一个 RssView 类，可以轻松生成（复杂）RSS 提要.
- [Meta plugin](https://github.com/dereuromark/cakephp-meta) - 使处理元标记和 SEO 相关的 HTML 标记变得干燥而简单.
- [TwigView plugin](https://github.com/cakephp/twig-view) - 使用 Twig 模板语言进行视图的插件.

## Testing
*用于测试代码库和生成测试数据的插件/工具.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - 官方 CakePHP 集成 [Codeception](https://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - 官方 CakePHP CS 规则.
- [CakephpFixtureFactories plugin](https://github.com/pakacuda/cakephp-fixture-factories) - 在测试的基础上动态创建您的装置，加速测试的编写和维护.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) 支持 CakePHP 装置.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) - 灯具插件可读取现有灯具并创建表格/插入数据以快速启动应用程序.
- [FriendsOfCake/Fixturize plugin](https://github.com/FriendsOfCake/fixturize) - 通过减少插入量（仅限 mysql）运行测试套件时更有效地插入固定装置.

## Third Party APIs
*用于访问第三方 API 的插件.*


## Software
*用于创建开发环境的软件.*

## Development Environment
*用于创建沙盒开发环境的软件和工具.*

- [CakePHP Docker](https://github.com/cnizzardini/cakephp-docker) - 用于 docker 和 kubernetes 设置的 cakephp/app 模板.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - 用于启动多个 CakePHP 3.x Vanilla 开发环境的工具.
- [Devilbox](https://devilbox.readthedocs.io/en/latest/) - 用于自动设置（CakePHP）应用程序的 Docker 开发环境，包括许多工具.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) - Docker 容器环境中的 CakePHP.
- [Galley](https://gitlab.com/amayer5125/galley) - 用于 CakePHP 开发的小型 Docker 开发环境，其中包括一个简单的命令行实用程序.
- [NetBeans](https://github.com/junichi11/cakephp3-netbeans) - 此软件包在 NetBeans 8.1+ 中提供对 CakePHP 的支持.
- [Oven](https://github.com/CakeDC/oven) - 只需 1 个文件和 1 个点击即可设置您最喜爱的框架.
- [Puppet](https://puppetlabs.com/) - 服务器自动化框架和应用程序.
- [Vagrant](https://www.vagrantup.com/) - 便携式开发环境实用程序.

IDE具体兼容性信息和提示可以找到 [here](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips).

## Web Applications

## CMS and applications built on CakePHP

- [baserCMS](https://github.com/baserproject/basercms)  - 这是一个带有 RESTful API 的网站开发框架. 可作为 CakePHP 4.x 的插件安装.
- [Croogo](https://croogo.org) - CMS 软件（参见 5.0 分支）.

## Demo
*基于网络（演示）的应用程序和工具.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - 一个基于 CakePHP 的简单博客示例 [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) 使用 CRUD 插件构建的书签应用程序.
- [CakeFest](http://cakefest.dereuromark.de/) - 围绕年度 CakePHP 会议“CakeFest”的演示应用程序.
- [Fluentd + Grafana Loki demo application](https://github.com/ishanvyas22/cakephp-loki-demo) - 将 CakePHP docker 容器日志发送到的演示应用程序 [Grafana Loki](https://grafana.com/logs/) 通过 [Fluentd](https://www.fluentd.org/).
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - 示例 CakePHP 代码库包含遵循以下原则的真实示例（CRUD、身份验证、高级模式等） [RealWorld](https://github.com/gothinkster/realworld-example-apps) 规格和 API.
- [Sandbox](https://sandbox.dereuromark.de) - 沙箱 CakePHP 应用程序，包含大量演示和插件展示.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) 高级查询构建示例.
- [Xeta](https://github.com/XetaIO/Xeta) - 帮助人们开始使用 CakePHP 的资源.
- [Vue.js Demo App](https://github.com/ishanvyas22/cakephpvue-spa) - CakePHP + VueJS 单页面应用程序框架.

## Resources
用于提高 CakePHP 开发技能和知识的各种资源，例如书籍、网站和文章.

## Help
*从哪里获得帮助.*

- [CakePHP-FR.org](http://cakephp-fr.org) - 法语社区网站.
- [Official CakePHP Forum](https://discourse.cakephp.org/) - 这适用于一般问题等.
- [IRC Channel](https://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - 与其他开发人员和核心开发人员进行实时聊天/讨论.
- [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - 这是针对特定问题的，最好附带一些示例代码.

## CakePHP Websites
*有用且最新的 CakePHP 相关网站和博客.*

- [CakeDC](http://www.cakedc.com/articles) - 有关 CakePHP 的文章.
- [dereuromark.de](https://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - CakePHP 相关的开发博客.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - 主要与 CakePHP 相关的核心开发博客.
- [mark-story.com](http://mark-story.com) - CakePHP 领导开发博客.

## CakePHP Books and Articles
*Fantastic CakePHP 相关（电子）书籍和其他阅读材料.*

## CakePHP Videos
*精彩的 CakePHP 相关视频.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - 有关 CakePHP 视频的频道.


## CakePHP Tutorials
*必做教程.*

- [Official Blog tutorial](https://book.cakephp.org/4.0/en/tutorials-and-examples/blog/blog.html)
- [Official Content Management Tutorial](https://book.cakephp.org/4/en/tutorials-and-examples/cms/installation.html)

## CakePHP Reading and Listening
*文档和CakePHP相关的阅读和听力材料.*

- [CakePHP Cookbook(!)](https://book.cakephp.org/) - CakePHP 官方文档.

## CakePHP Internals Reading
*阅读与 CakePHP 内部结构和决策相关的材料.*

- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - 帮他们一把.

## Conferences

## Official
*国际会议.*

- [cakefest.org](https://cakefest.org/) - 年度 CakePHP 会议.

## MeetUps
*区域聚会.*

- [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - 德国聚会.

## Contributing
请参见 [CONTRIBUTING](https://github.com/friendsofcake/awesome-cakephp/blob/master/CONTRIBUTING.md) 了解详情.

## Credits
Awesome-cakephp 的创建者 [dereuromark](https://github.com/dereuromark) 目前由他和 FriendsOfCake 小组维护. 谢谢你们 [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors)， 也.
