<div class="github-widget" data-repo="mojoaxel/awesome-regression-testing"></div>
## Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 很棒的视觉回归测试资源的精选列表.

回归测试是一种软件测试，它验证先前开发和测试的软件在更改或与其他软件交互后仍然以相同的方式执行. 回归测试的目的是确保对软件的更改没有引入新的故障.

## Foreword

这是关于视觉回归测试的*不完整*资源列表. 它不是针对特定领域或角色（开发人员/QA/UX 设计师）量身定制的. 请注意，这适用于*在*编写有问题的代码之后进行回归软件测试的所有领域. 有关一般软件测试的精彩列表，请参见例如 [awesome-testing](https://github.com/TheJambo/awesome-testing).

最后，我相信每个阅读此列表的人都想添加一件事. 请阅读 [How to Contribute](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 页面和 **随时添加到列表中！！**. 如果觉得有帮助**请给个Star⭐️**.



## General information

- [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)
- [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)

## Browser automation

- [Selenium](https://github.com/SeleniumHQ/selenium) - 浏览器自动化框架和生态系统.
- [SlimerJS](https://github.com/laurentj/slimerjs) - 可编写脚本的浏览器，如基于 Firefox 的 PhantomJS.
- [Webdriver.io](https://github.com/webdriverio/webdriverio/) - W3C WebDriver 协议的 Node.js 绑定实现.
- [Cypress.io](https://www.cypress.io/) - 在浏览器中运行的自动化框架.

## Tools and frameworks

- [OSnap](https://github.com/eWert-Online/osnap) - 快速且易于使用的项目快照测试工具（1200 个快照将在 3 分钟内运行）.
- [basset](https://basset.io)  - 用于生成和审查视觉差异的开源平台. 支持多种浏览器，github 和 slack 的集成.
- [AyeSpy](https://github.com/newsuk/ayespy) - 90 秒内进行 44 次图像比较.
- [Wraith](https://github.com/BBC-News/wraith) - 易于使用的 ruby​​ 工具，支持 docker.
- [BackstopJS](https://github.com/garris/BackstopJS) - 配置驱动的自动屏幕截图测试框架.
- [Galen](https://github.com/galenframework/galen) - 基于Java框架 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Creevey](https://github.com/wKich/creevey)  - 使用魔法进行跨浏览器视觉测试. 具有 UI Runner、测试热重载、Docker 和 Storybook 集成的功能丰富的工具.
- [CSSCritic](https://github.com/cburgmer/csscritic) - 轻量级 CSS 回归测试.
- [Spectre](https://github.com/wearefriday/spectre) - 提供图像比较功能和用于管理屏幕截图的管理界面.
- [Shoov](https://github.com/shoov/shoov) - 专注于 Drupal 7 站点的 UI 回归和功能测试.
- [qd_screenshottests](https://www.drupal.org/project/qd_screenshottests) - 专注于 Drupal 8 站点的基于 CasperJS 的 UI 回归和功能测试.
- [Look-alike](https://github.com/kdzwinel/Look-alike) - 用于获取和比较屏幕截图的 Chrome 扩展.
- [Hardy](https://github.com/thingsinjars/Hardy) - 硒驱动、黄瓜驱动的 CSS 测试.
- [TestCafe](https://github.com/DevExpress/testcafe) - 用于现代 Web 开发堆栈的自动化浏览器测试.
- [Needle](https://github.com/python-needle/needle) - Needle 是一种使用 Selenium 和 nose (Python) 测试视觉效果的工具.
- [gatling](https://github.com/gabrielrotbart/gatling) - 集成视觉 RSpec 匹配器，使真正的视觉测试变得容易 (Ruby).
- [grunt-photobox](https://github.com/stefanjudis/grunt-photobox) - 通过您网站的屏幕截图照片会话来防止您的项目布局损坏的插件.
- [vrtest](https://github.com/nathanmarks/vrtest) - JavaScript 库，用于通过 selenium 在您的组件上跨浏览器运行视觉回归测试.
- [Happo](https://github.com/Galooshi/happo) - Visual diffing in CI for user interfaces.
- [reg-cli](https://github.com/bokuweb/reg-cli) - 视觉回归测试工具，输出易于阅读的单个文件 html 报告.
- [Nightmare](https://github.com/segmentio/nightmare) - 基于 Electron 的高级浏览器自动化库.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - 无头谷歌浏览器节点 API.
- [Playwright](https://github.com/microsoft/playwright) - 使用单个 API 自动化 Chromium、Firefox 和 WebKit 的节点库.
- [reg-suit](https://github.com/reg-viz/reg-suit) - 视觉回归测试套件，可比较图像、存储快照并将差异通知您的 GitHub 存储库.
- [Chimp](https://github.com/xolvio/chimp) - 通过实时反馈开发验收测试和端到端测试.
- [Differencify](https://github.com/NimaSoroush/differencify) - 用于视觉回归测试的库，使用 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ResembleJS](https://github.com/Huddle/Resemble.js) - 使用 Javascript 和 HTML5 分析和比较图像.
- [Muppeteer](https://github.com/HuddleEng/Muppeteer) - 使用 Chrome 的视觉回归测试框架 [Mocha](https://mochajs.org/) 和 [Puppeteer](https://github.com/GoogleChrome/puppeteer).
- [ember-visual-test](https://github.com/Cropster/ember-visual-test) - 简单的视觉回归测试 [Ember](https://emberjs.com/).
- [AET](https://github.com/Cognifide/aet) - 可扩展的测试工具，提供视觉回归测试、可访问性和性能验证、标记分析等.
- [Wendigo](https://github.com/angrykoala/wendigo) - 基于 Puppeteer 的面向测试的浏览器自动化库.
- [Loki](https://github.com/oblador/loki) - 在 docker 等中使用 Chrome 对 Storybook 进行视觉回归测试.
- [Zombie.js](http://zombie.js.org/) - 使用 Node.js 进行异常快速、无头的全栈测试.
- [CodeceptJS](https://github.com/codeception/codeceptjs/) - NodeJS 的现代验收测试框架.
- [FuncUnit](https://github.com/bitovi/funcunit) - 基于 jQuery 的功能测试套件
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于Node.js，使用Webdriver协议的自动化测试和持续集成框架.
- [Protractor](https://github.com/angular/protractor) - Angular 应用程序的 E2E 测试框架.
- [jest-puppeteer-react](https://github.com/Hapag-Lloyd/jest-puppeteer-react) - 使用 Jest 和 puppeteer 对 React 组件进行视觉回归测试
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) - 使用 Jest 进行图像比较的 Jest 匹配器 [pixelmatch](https://www.npmjs.com/package/pixelmatch)
- [test-crawler](https://github.com/apiel/test-crawler) - 视觉回归测试，通过抓取网站并提供快照比较报告.
- [wdio-visual-regression](https://github.com/ennjin/wdio-visual-regression) - webdriver.io 视觉回归工具
- [Selenide](https://github.com/selenide/selenide) - 由 Selenium WebDriver 提供支持的框架，用于在 Java 中编写易于阅读和易于维护的自动化测试.
- [Karma](http://karma-runner.github.io/latest/index.html) - AngularJS 团队的测试运行器，可以满足我们的所有需求.
- [Touca](https://github.com/trytouca/trytouca) - 开源持续回归测试，无需管理快照文件的麻烦.
- [Lost Pixel](https://github.com/lost-pixel/lost-pixel) - 对整页、组件（通过 Storybook 和 Ladle 集成）和自定义镜头（例如通过 Cypress）进行整体视觉回归测试.

## Online services

- [BrowserStack](https://www.browserstack.com)  - 开源免费. 支持 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [BugBug.io](https://bugbug.io/)  - 用于 Web 应用程序的轻量级测试自动化工具. 易于学习，不需要编码. 它是免费的，可以进行无限制的测试. 每月支付额外费用，您还可以获得云监控和 CI/CD 集成.
- [HeadSpin](https://www.headspin.io/) - HeadSpin 的回归测试为您提供了一个强大的比较工具，用于分析新应用程序构建、操作系统版本、功能添加、位置等的退化情况.
- [LambdaTest](https://www.lambdatest.com/) - 在 2000 多个真实浏览器和操作系统上在线执行自动化和实时交互式跨浏览器测试.
- [screener.io](https://screener.io) - 对于 React，看起来是开源的.
- [applitools](https://applitools.com) - 云基础视觉测试.
- [percy.io](https://percy.io) - 网络应用程序的持续视觉审查.
- [screenster.io](http://screenster.io) - 用于 Web 和移动 UI 的基于云的自动化测试平台.
- [browserling](https://www.browserling.com) - 实时交互式跨浏览器测试.
- [Browser Shots](http://browsershots.org) - 仅限截图.
- [Ghost Inspector](https://ghostinspector.com) - 看 [introduction video](https://vimeo.com/ghostinspector/intro).
- [CrossBrowserTesting](https://crossbrowsertesting.com) - 在 1500 多个真实浏览器和移动设备上进行手动和探索性测试.
- [Argos-CI](https://www.argos-ci.com) - 自动化视觉回归测试.
- [Diffy](https://diffy.website)  - 基于云的视觉回归工具. 使用 puppeteer 和专有比较算法（检测布局变化）.  AWS Lambda 具有出色的可扩展性.
- [Chromatic](https://www.chromatic.com/)  - 组件库的可视化测试和 UI 审查. 基于云. [Video](https://youtu.be/6KDLJBcutQE)
- [VisWiz.io](https://www.viswiz.io) - 灵活的视觉回归测试服务.
- [Happo](https://happo.io/) - 基于云的屏幕截图测试服务，支持多种浏览器.
- [Visual Knight](https://visual-knight.io/) - 基于云的可视化测试平台，具有测试工具的实时结果.
- [Axcept](https://axcept.io)  - 测试整个团队. 多达 100 个并行测试. 端点模拟. 代码覆盖率. 
- [Fluxguard](https://fluxguard.com) - 屏幕截图像​​素和 DOM 变化比较和回归.
- [Vidiff](https://vidiff.com) - 跨阶段的基于云的视觉回归测试.
- [Reflect](https://reflect.run) - 视觉回归测试和测试自动化工具.
- [Visual Regression Tracker](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker) - 用于视觉回归测试的开源自托管服务
- [Micoo](https://github.com/Mikuu/Micoo) - 所有UI应用视觉回归解决方案的开源服务
- [TestingBot](https://testingbot.com)  - 提供 +3600 个浏览器来运行自动化视觉测试. 开源免费.
- [Preflight](https://preflight.com)  - 最简单的视觉回归测试和自动化 Web 测试工具.  （有限）免费使用.
- [Preflight: Cypress Recorder](https://cypress.preflight.com) - 在您的浏览器中创建 AI 驱动的 Cypress 测试/POM 模型，并为 Cypress 自动化电子邮件和视觉测试.
- [Meticulous.ai](https://meticulous.ai)  - 无需编写代码即可轻松创建前端测试. 使用 Meticulous 在您的 Web 应用程序上记录工作流程. 然后，您可以在新的前端代码上重放这些流，并通过比较两个重放来创建测试.
- [testRigor](https://testrigor.com) - 用于 Web、移动和桌面测试的端到端功能测试自动化工具.

## Blog posts

- [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - 比较：Wraith、PhantomCSS、Gemini、WebdriverCSS 和 Spectre.
- [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) - 使用 BackstopJS 的教程.
- [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - 使用 BackstopJS 的教程.
- [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - 使用 BackstopJS 的教程.
- [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - 为什么你应该使用 BackstopJS.
- [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) - PhantomCSS 简介.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome 正在颠覆传统的测试自动化方法.
- [Visual regression testing using Jest, Chromeless and AWS Lambda](https://github.com/novemberfiveco/visual-regression-testing-jest-chromeless) - 使用 Chromeless 和 jest-image-snapshot 的教程.
- [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - 简介 [Differencify](https://github.com/NimaSoroush/differencify) 以及如何使用它.
- [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - 使用 Puppeteer、Jest 和 VisWiz.io 设置视觉测试的教程.
- [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - 使用 percy 和 jest puppeteer 可视化测试 React 组件库.
- [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - 使用 WebdriverIO 和 WebdriverCSS 与 Spec Reporter 的教程
- [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
- [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)
- [theheadless.dev](https://theheadless.dev) - 在 Playwright 和 Puppeteer 上提供实用指南和可运行示例的博客.
- [Visual regression testing for Hugo with Github-CI and BackstopJS](https://jameskiefer.com/posts/visual-regression-testing-for-hugo-with-github-ci-and-backstopjs/) - 如何使用 BackstopJS 对 Hugo 进行自动化回归测试
- [UI Visual Regression Testing with Micoo](https://mikuu.medium.com/ui-visual-regression-testing-with-micoo-12c7a4a036b9) - 介绍如何使用Micoo服务做视觉回归测试
- [Poor man's visual regression testing](https://idkshite.com/posts/compare-visual-changes) - 使用 PerfectPixel chrome 插件改进手动视觉回归测试.
- [Everything you need to know about Visual Regression Testing in 2022](https://david-x.medium.com/the-state-of-visual-regression-testing-in-2022-5de10ffe8f6f) - 使用自 2022 年起更新的工具介绍视觉回归测试. 

## Slideshows, talks and videos

- [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - 截图：截图比较工具 wraith 的基本介绍.
- [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - 如何设置 shoov 并编写您的第一个测试.
- [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) - 由 Jon Bellah 讲述如何在 wordpress 开发过程中使用 PhantomCSS.
- [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - 带有代码演示和最佳实践的截屏视频.
- [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - 关于如何使用 Screenster 创建可视化自动化测试的教程.
- [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - 演示 Look-alike Chrome 扩展是什么、它是如何工作的以及它是如何构建的以及为什么构建.
- [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - 如何与 CSS critic 一起编写您的第一个 CSS 测试，如何通过、破坏并再次通过.
- [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) 作者：Nikhil Verma - Badoo 的移动 Web 团队如何将 PhantomCSS 转换并集成到他们的工作流程中，并将其连接到他们的 CI 流程.
- [Cypress in 100 Seconds](https://www.youtube.com/watch?v=BQqzfHQkREo&ab_channel=Fireship) - Fireship 的介绍视频. 

## Deprecated

以下项目不再积极维护，但由于其用户群仍然值得一提.

- [PhantomJS](https://github.com/ariya/phantomjs)  - 可编写脚本的无头 WebKit. 自 2018 年 6 月 2 日起不再维护.
- [PhantomCSS](https://github.com/Huddle/PhantomCSS)  - 使用 PhantomJS 或 SlimerJS 进行视觉/CSS 回归测试. 自 2017 年 12 月 22 日起不再维护.
- [PhantomFlow](https://github.com/Huddle/PhantomFlow) - 基于决策树的 UI 测试实验方法.
- [DalekJS](https://github.com/dalekjs/dalek)  - 使用 JavaScript 自动进行跨浏览器测试. 自 2017 年 6 月 4 日起不再维护.
- [dpxdt](https://github.com/bslatkin/dpxdt) - 使用 Python 进行端到端测试.
- [Visual Review](https://github.com/xebia/VisualReview) - 用于测试和审查视觉回归的人性化工具.
- [Huxley](https://github.com/facebookarchive/huxley) - 基于Python的框架 [Selenium Webdriver](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - WebdriverCSS 位于 [Webdriver.io](https://github.com/webdriverio/webdriverio/) 并挂钩 [Selenium](https://github.com/SeleniumHQ/selenium).
- [Gemini](https://github.com/gemini-testing/gemini) - 功能丰富的框架，支持 [Selenium](https://github.com/SeleniumHQ/selenium) 和  [CasperJS](https://github.com/casperjs/casperjs) .  Gemini 已弃用，请改用 hermione.
- [OcularJS](https://github.com/mmacartney10/ocularjs) - 使用 [PhantomJS](https://github.com/ariya/phantomjs).
- [trifleJS](https://github.com/sdesalas/trifleJS)  - Internet Explorer 的无头自动化.  （最后更新于 2016 年）
- [CasperJS](https://github.com/casperjs/casperjs)  - 用于 PhantomJS 和 SlimerJS 的导航脚本和测试实用程序.  （存档于 2018 年）
- [Navalia](https://github.com/joelgriffith/navalia)  - 基于无头 Chrome 和 GraphQL 的浏览器自动化.  （存档于 2018 年）
- [Chromeless](https://github.com/graphcool/chromeless)  - Chrome 自动化变得简单. 在 AWS Lambda 上本地或无头运行.  （存档于 2018 年）

## Miscellaneous

### Contributing

见 [Contribution Guide](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CONTRIBUTING.md) 有关如何贡献的详细信息.

### Code of Conduct

见 [Code of Conduct](https://github.com/mojoaxel/awesome-regression-testing/blob/master/.github/CODE-OF-CONDUCT.md) 了解详情. 基本上可以归结为：
&gt; 为了营造一个开放和热情的环境，我们作为
贡献者和维护者承诺参与我们的项目，并且
我们的社区为每个人提供无骚扰的体验，无论年龄、身体如何
体型、残疾、种族、性别认同和表达、经验水平、
国籍、外貌、种族、宗教或性认同和性取向.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

这项工作已获得许可 [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
执照持有人是 [all contributors](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).
