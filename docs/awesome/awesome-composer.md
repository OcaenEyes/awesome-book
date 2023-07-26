<div class="github-widget" data-repo="jakoch/awesome-composer"></div>
## Awesome Composer [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

&gt; Composer、Packagist、Satis、插件、脚本、视频、教程的精选资源列表.

你可能还喜欢 [awesome-php](https://github.com/ziadoz/awesome-php).

*请阅读 [contribution guidelines](https://github.com/jakoch/awesome-composer/blob/master/contributing.md) 在贡献之前.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Github](https://github.com/composer/composer)
- [Issues](https://github.com/composer/composer/issues)
- [Source](https://github.com/composer/composer/tree/HEAD/src/Composer)
- [Documentation](https://getcomposer.org/doc/)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](https://composer.json.jolicode.com/) - CLI 命令和 `composer.json` 模式概述.
- [Composer Installers](https://github.com/composer/installers) - 多个框架的 Composer 安装程序.

### Support

#### Stack Overflow

- 您可以使用以下标签：`composer-php`、`packagist`、`satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC 频道位于 `irc.freenode.org` 上： [#composer](https://webchat.freenode.net/#composer) 对于用户和 [#composer-dev](https://webchat.freenode.net/#composer-dev) 为了发展.

---------------------------------------------------------

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - 在编写 Composer 插件时，这个官方文档是一个很好的起点.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) - Composer 的 npm/Bower 依赖管理器.
- [Composer-AWS](https://github.com/naderman/composer-aws) - 该插件加载存储库数据并从 Amazon S3 下载数据包（具有对私有存储库的身份验证支持）.
- [Composer-Composition](https://github.com/bamarni/composition) - 提供 API，用于在运行时检查您的环境.
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) - 使您能够根据关键字模式安装一组自定义的建议包.
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) - 在使用更新命令后显示最后一个主要版本的过时包（显示“最新版本是 vX.YZ”）.
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs)  - 提供更新摘要以及指向更改日志/发布说明/标签的链接. 更新 composer.lock 文件时，输出已准备好粘贴到提交消息中.
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) - 在 Composer 运行时合并多个 `composer.json` 文件.
- [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) - 添加了对管理单个存储库中多个包的依赖关系或隔离 bin 依赖关系的支持.
- [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) - 维基媒体 composer-merge-plugin 的自以为是的版本与 Bamarni composer-bin-plugin 一起工作.
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) - 该插件有助于管理单个存储库中多个包的依赖关系.
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin)  - 使您能够为任何包中的任何包提供补丁. 获取依赖项时，补丁将应用在顶部.
- [Composer-Patches](https://github.com/cweagans/composer-patches) - 该插件将本地或远程文件中的补丁应用于任何所需的包.
- [Composer-Patches](https://github.com/vaimo/composer-patches) - 将本地或远程文件的补丁应用到属于给定作曲家项目的任何包.
- [Composer-Patchset](https://github.com/mageops/php-composer-plugin-patchset) - 自动获取、更新补丁并将补丁应用于任何带有扭曲的作曲家包 - 将补丁集存储为作曲家包本身.
- [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) - 作曲家执行 PHP 质量保证工具的综合插件.
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) - 从供应商目录中删除测试和文档文件夹.
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) - 该工具从供应商目录中删除不必要的文件和目录.
- [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin)  - 使您能够从供应商文件夹中删除文件和文件夹（以便对生产进行更清洁和更小的部署）. 它是 .gitattributes 的替代品.
- [Composer-Vendor-Cleaner](https://github.com/liborm85/composer-vendor-cleaner) - 插件通过 glob 模式语法从 `vendor` 目录中删除不必要的开发文件和目录.
- [Composer-Skrub](https://github.com/ssx/skrub) - 该插件有助于从 Composer 安装中删除垃圾并调整构建大小.
- [Drupal Vendor Hardening Composer Plugin](https://github.com/drupal/core-vendor-hardening) - 从项目的供应商目录中删除无关的目录，并将 .htaccess 和 web.config 文件添加到项目供应商目录的根目录中.
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) - 允许您通过创建符号链接在项目之间共享选定的包.
- [Composer-Symlinker](https://github.com/e-picas/composer-symlinker) - 使您能够从不同的目录加载包（而不是从 /vendor 加载它们）.
- [Prestissimo](https://github.com/hirak/prestissimo) - 使用 `phpext_curl` 的并行下载器.
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) - 该插件使用 `phpext_curl` 来下载包.
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) - 作曲家插件，用于在默认作曲家安装路径（供应商文件夹）之外的自定义目录中安装不同类型的作曲家包.
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - 允许您为已安装的作曲家项目构建依赖关系图.
- [Graph-Composer](https://github.com/clue/graph-composer) - 为项目的 `composer.json` 及其依赖项提供图形可视化.
- [PackageVersions](https://github.com/Ocramius/PackageVersions) - 提供对已安装的作曲家依赖版本的非常快速和轻松的访问.
- [PackageVersions Deprecated](https://github.com/composer/package-versions-deprecated) - 是 Ocramius/PackageVersions 的一个分支，提供与 PHP 7+ 上的 Composer 1 和 2 的兼容性.
- [Composer-Locator](https://github.com/mindplay-dk/composer-locator) - 提供一种定位给定 Composer 包名称的安装路径的方法.
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) - 使您能够检索所有包信息（如版本、标签、发布日期、描述）.
- [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) - 一个用于在您的作曲家配置中轻松管理 git 钩子的库.
- [Symfony-Flex](https://github.com/symfony/flex) - 提供 [recipe-based](https://github.com/symfony/recipes) Symfony 包的安装和配置管理.
- [Narrowspark-Automatic](https://github.com/narrowspark/automatic) - 自动执行最常见的应用程序任务、提升包下载量、添加作曲家安全审核等.
- [PHPCodeSniffer-Composer-Installer](https://github.com/DealerDirect/phpcodesniffer-composer-installer) - 该插件使您能够安装 [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 编码标准（规则集）.
- [Composer-Warmup](https://github.com/jderusse/composer-warmup) - 该插件将命令 `warmup-opcode` 添加到 Composer，这会触发将项目中发现的所有 PHP 文件编译到 Opcache 中.
- [Foxy](https://github.com/fxpio/foxy) - 当安装或更新 composer 包时执行 npm/yarn 包安装操作的 Composer 插件.
- [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) - NodeJS 和 npm 的安装程序.
- [Node-Composer](https://github.com/mariusbuescher/node-composer) - NodeJS、npm 和 yarn 的安装程序.
- [Imposter-Plugin](https://github.com/typisttech/imposter-plugin)  - 将所有作曲家供应商包包装在您自己的命名空间中. 用于 WordPress 插件.
- [Composer Preload](https://github.com/Ayesh/Composer-Preload) - 该插件生成一个“vendor/preload.php”文件来预热 Opcache.
- [PHP Inc](https://github.com/krakphp/php-inc) - 自动包含 autoload 和 autoload-dev 的文件，以方便在 composer 加载的应用程序中使用函数和分组定义.
- [Composer Registry Manager](https://github.com/slince/composer-registry-manager) - 使您能够在不同的作曲家存储库之间切换.
- [Production-Dependencies-Guard](https://github.com/kalessil/production-dependencies-guard) - 防止开发包被添加到需求中并进入生产环境.
- [Composer-Plugin-Exclude-Files](https://github.com/mcaskill/composer-plugin-exclude-files) - 一个插件，用于排除使用“文件”自动加载机制的包所需的文件.
- [Composer-Downloads-Plugin](https://github.com/civicrm/composer-downloads-plugin) - 仅使用“url”和“path”下载外部资源（ZI​​P/TAR 文件）的轻量级机制.
- [Private-Composer-Installer](https://github.com/ffraenz/private-composer-installer) - 将包 URL 中的帮助程序外包敏感密钥安装到环境变量中.
- [CycloneDX-PHP-Composer](https://github.com/CycloneDX/cyclonedx-php-composer) - 创建一个 [CycloneDX](https://cyclonedx.org/) 项目依赖项的“软件物料清单”(SBOM).  SBOM 通过以下方式启用依赖性监控和风险分析 [OWASP DependencyTrack](https://dependencytrack.org/).
- [Composer-Compile-Plugin](https://github.com/civicrm/composer-compile-plugin)  - 允许 PHP 库定义简单、自由形式的编译任务. 支持任何包中的安装后挂钩.
- [Composer-Link](https://github.com/SanderSander/composer-link) - 添加了链接本地包以进行开发的能力.
- [Composer-REPL](https://github.com/ramsey/composer-repl) - 该插件提供了 `composer repl` 命令，它为您提供了一个 PHP 语言 shell（read-eval-print 循环）.
- [Composer-Diff](https://github.com/IonBazan/composer-diff) - 比较 `composer.lock` 更改并生成 Markdown 报告以供在拉取请求描述中使用.
- [Composer-Velocita](https://github.com/isaaceindhoven/composer-velocita) - 使用快速可靠的 Composer 包下载 [Velocita](https://github.com/isaaceindhoven/velocita-proxy)：不需要您修改项目的缓存反向代理.

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - 通过对 Packagist 托管的包进行语义版本检查，使您能够识别版本解析问题的约束.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) - 此工具将 `composer.yml` 转换为 `composer.json`.
- [Studio](https://github.com/franzliedke/studio)  - 用于开发 Composer 包的工作台. 它是在供应商文件夹中编辑依赖项或使用的替代方法 [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) 将您的依赖项的本地克隆加载到您的项目中.
- [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) - 使您能够浏览 Github 上的 Composer/NPM 依赖项.
- [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) - 一个 CLI 工具，用于分析依赖关系并验证包的源代码中没有使用未知的导入符号.
- [Composer-Unused](https://github.com/composer-unused/composer-unused) - 一个 CLI 工具，它可以扫描您的代码并显示未使用的 Composer 依赖项.
- [Composer-Normalize](https://github.com/ergebnis/composer-normalize) - 该插件通过重组和排序条目（规范化）帮助您保持 `composer.json` 文件的一致性.
- [Composer-Service](https://github.com/pborreli/composer-service) - Enables you to run Composer as a service on a remote server.
- [Composer PreferLowest Checker](https://github.com/dereuromark/composer-prefer-lowest) - 严格比较 composer.json 的指定最低版本与 prefer-lowest composer update 命令选项实际使用的版本.
- [Bramus/Composer-Autocomplete](https://github.com/bramus/composer-autocomplete) - 用于 Composer 的 Bash/Shell 自动完成脚本.
- [Composer/Xdebug-Handler](https://github.com/composer/xdebug-handler) - 帮助您在不加载 xdebug 扩展的情况下重新启动 CLI 进程.
- [Composer Semver Range Checker](https://gitlab.com/MattyRad/composer.guru) - 帮助检查作曲家约束的可满足范围的工具.

## Scripts

- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) - 允许您在运行作曲家安装或更新时管理忽略的参数.
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script)  - 在项目“composer.json”中管理所需的 PHAR 文件. 每个 PHAR 文件都将保存在 composer 二进制目录中. 每个 PHAR 的 GPG 验证都是可选的.
- [Melody](https://github.com/sensiolabs/melody) - 单文件作曲家脚本.
- [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) - 允许您检查 Travis CI 配置文件 (`.travis.yml`).
- [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) - 使您能够针对多个本地安装的 PHP 版本运行 Composer 脚本，这些版本由 PHPBrew 或 phpenv 管理.
- [ScriptsDev](https://github.com/neronmoon/scriptsdev) - 使您能够使用 `scripts-dev` 部分，该部分仅在开发模式下触发脚本.
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer) - 一个 Composer 包，它将 PhantomJS 二进制文件（Linux、Windows、Mac）安装到项目的 /bin 中.
- [Composer-Vendor-Cleanup](https://github.com/0xch/composer-vendor-cleanup) - 从供应商目录中删除列入白名单的不必要文件（如测试/文档等）的脚本.
- [Composer-Substitution-Plugin](https://github.com/villfa/composer-substitution-plugin) - 一个 Composer 插件，用动态值替换“脚本”部分中的占位符.

## Services

- [Packanalyst](https://packanalyst.com/) - Packanalyst 是一项服务，可让您浏览 Packagist 中定义的任何 PHP 类/接口/特征.
- [Dependabot](https://dependabot.com/)  - Dependabot 是一个依赖更新服务. 它通过发送拉取请求来监视和更新您的依赖项. 该服务对公共回购和个人账户回购是免费的.

---------------------------------------------------------

## Tutorials

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](https://alanstorm.com/php_composer_magento_tutorial/ )
- [Creating and Using Composer Packages](https://hub.packtpub.com/creating-and-using-composer-packages/)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](https://naderman.de/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)
- [The long journey of making PHP’s Composer memory-efficient and fast (toflar)](https://medium.com/@yanick.witschi/the-long-journey-of-making-phps-composer-memory-efficient-and-fast-63d12944aaa8)

## Videos

- [Composer Best Practices 2018 - Nils Adermann @ scotphp18](https://www.youtube.com/watch?v=eQkFjMfyqFY)
- [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
- [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
- [作曲家最佳实践 — Jordi Boggiano @ php[tek] 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
- [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)
- [Composer 2 - Jordi Boggiano @ Symfony UK usergroup 2020](https://www.youtube.com/watch?v=BAgwWhRo82w)
- [Lessons learned building the Composer internals - Jordi Boggiano @ CODEiD Odessa PHP Conference 2017](https://www.youtube.com/watch?v=pjvbn6TBZqM) 

## Slides

- Nils Adermann 的幻灯片
  - 来源：https://naderman.de/slippy/src/
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](https://naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  - [Composer Update](https://naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](https://naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  - [管理依赖关系是
不仅仅是跑步
“作曲家更新”](https://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf)
  - [作曲家
最佳实践 @ T3DD17](https://naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf)
  - [控制你
依赖关系
私有 Packagist](https://naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf)
  - [Composer.lock demystified](https://naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
  - [Compoer In-Depth @ Contao Konferenz 2018](https://naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
  - [Composer Best Practices 2018](https://naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
  - [Developing and Deploying Magento with Composer Best Practices](https://naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
  - [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](https://naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
- Jordi Boggiano 的幻灯片
  - 来源：http://slides.seld.be/
  - [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  - [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)
  - [Lessons Learned Building the Composer Internals (2018)](http://slides.seld.be/?file=2018-04-20+Lessons+Learned+Building+the+Composer+Internals.html)

---------------------------------------------------------

## Packagist

[Packagist](https://packagist.org) 是 PHP 包存储库.

### Setup a Packagist Mirror

- [Packagist Mirror](https://github.com/Webysther/packagist-mirror)  - 此脚本有助于设置 packagist 镜像. 它是维护和稳定的版本 [Packagist Crawler](https://github.com/hirak/packagist-crawler).
- [Docker Image](https://github.com/Webysther/packagist-mirror-docker) - 此 Docker 镜像有助于创建定制的 packagist 镜像.
- [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) - 创建 packagist 镜像的另一个实现.

### Packagist Mirrors

关于元数据镜像：https://packagist.org/mirrors

- 北美
  - 加拿大 - [packagist.org](https://packagist.org) *Main mirror*
- 南美洲
  - 巴西 - [packagist.com.br](https://packagist.com.br)
- 非洲
  - 南非 - [https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za](https://github.com/jakoch/awesome-composer/blob/master/packagist.co.za)
- 亚洲
  - 中国 - [php.cnpkg.org](https://php.cnpkg.org), [https://pkg.phpcomposer.com/](https://pkg.phpcomposer.com/), [https://mirrors.aliyun.com/composer/](https://mirrors.aliyun.com/composer/)
  - 印度 - [https://packagist.in/](https://packagist.in/)
  - 印度尼西亚 - [packagist.phpindonesia.id](https://packagist.phpindonesia.id)
  - 日本 - [packagist.jp](https://packagist.jp)

## Composer Repositories

### Registry Manager
- https://github.com/slince/composer-registry-manager - 该插件可帮助您在不同的作曲家存储库之间切换.

### Private repositories
- [fxpio/tug](https://github.com/fxpio/tug) - 使您能够在 AWS Serverless 上托管私有 Composer 注册表，为托管在 Github 或 Gitlab 服务上的私有 PHP 包提供服务.

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) - 一个 Composer Repository as a Service for private packages and to mirror packages from other repositories.
- [Private Packagist Enterprise](https://packagist.com) - Private Packagist 的本地自托管版本.
- [Private Packagist API Client](https://github.com/packagist/private-packagist-api-client)  - 用于 Private Packagist API 的 PHP 客户端. 客户端处理身份验证、签名生成和对所有端点的访问.

### Repman

- [repman.io](https://repman.io) & [repman-io/repman](https://github.com/repman-io/repman) - 私有 PHP 包存储库管理器和 Packagist 代理.
- [repman-io/composer-plugin](https://github.com/repman-io/composer-plugin) - 此插件通过为所有依赖项添加分发镜像 URL 来启用通过 Repman 下载（无需更新 `composer.lock` 文件）.

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) - 将 WordPress 插件和主题目录镜像为 Composer 存储库.
- [Asset Packagist](https://asset-packagist.org/) - 允许将 Bower 和 NPM 包安装为本机 Composer 包.
- [Firegento](https://packages.firegento.com/) - 提供 Magento 模块的 Composer 存储库.
- [Drupal Packagist](https://www.drupal.org/node/2822344) - Drupal 7 和 8 核心、模块和主题的 Composer 存储库.
- [Satis Server](https://github.com/lukaszlach/satis-server) - 此 docker 容器提供 Satis 服务器，使您能够运行私有的、自托管的 Composer 存储库，支持 Git、Mercurial 和 Subversion、HTTP API、HTTPs 支持、webhook 处理程序和计划构建.
- [Cloudsmith](https://cloudsmith.com/) - 具有 PHP/Composer 支持（以及许多其他）的完全托管的包管理 SaaS.
- [Release Belt](https://github.com/Rarst/release-belt) - 自托管 Composer 存储库实施，以快速集成第三方非 Composer 版本的 ZIP 文件.
- [Packeton](https://github.com/vtsykun/packeton)  - 供应商的私有自托管 Composer 存储库.  packagist 的分支，添加了对授权、客户用户、组、webhook 的支持.

### Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - 这是 Gitlab 存储库的分支/标签索引器.
- [Satisfy](https://github.com/ludofleury/satisfy) - 带有 Web UI 的 Satis 作曲家存储库管理器.
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - 一个简单的 web UI，用于通过可选的 CI 集成管理您的 Satis 存储库.
- [Satis Go](https://github.com/benschw/satis-go) - 用于管理 Satis 配置和托管生成的 Composer 存储库的 Web 服务器.

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) （已弃用）- 除了提供作曲家存储库之外，ToranProxy 还充当 Packagist 和 GitHub 的代理服务器.

---------------------------------------------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Jens A. Koch](https://github.com/jakoch) 已放弃该作品的所有版权和相关或邻接权.
