<div class="github-widget" data-repo="parro-it/awesome-micro-npm-packages"></div>
## Awesome Micro npm Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 精选的小型、重点 Node.js 模块列表.

*灵感来自于 [awesome](https://github.com/sindresorhus/awesome) 列出事情.*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* [Module best practices](https://github.com/mattdesl/module-best-practices)
* [Evaluating Packages Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* [Evaluating Packages Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* [Small modules: it’s not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* [Tiny npm package: Guidelines to create a Node.js module following the small package philosophy](http://g14n.info/2015/12/tiny-npm-package/)
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)

## Modules

### Array

* [is-sorted](https://github.com/dcousens/is-sorted) - 用于检查数组是否已排序的小模块.
* [array-first](https://github.com/jonschlinkert/array-first) - 获取数组的第一个元素或前 n 个元素.
* [array-last](https://github.com/jonschlinkert/array-last) - 返回数组中的最后一个元素.
* [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - 递归地展平一个或多个数组.
* [dedupe](https://github.com/seriousManual/dedupe) - 从数组中删除重复项.
* [array-range](https://github.com/mattdesl/array-range) - 创建一个具有给定范围的新数组.
* [arr-diff](https://github.com/jonschlinkert/arr-diff) - 通过使用严格相等进行比较排除其他数组中的所有值，返回仅包含第一个数组中的唯一值的数组.
* [filled-array](https://github.com/sindresorhus/filled-array) - 返回一个由指定输入填充的数组
* [map-array](https://github.com/parro-it/map-array) - 将对象键和值映射到数组中.
* [in-array](https://github.com/jonschlinkert/in-array) - 如果数组中存在任何传递的值，则返回 true - 比使用 indexOf 更快.
* [unordered-array-remove](https://github.com/mafintosh/unordered-array-remove) - 有效地从无序数组中删除元素，而无需进行拼接.
* [array-swap](https://github.com/michaelzoidl/swap-array) - 交换数组中两个项目的位置.
* [mirrarray](https://github.com/johnwquarles/mirrarray) - 从有效键数组创建一个键镜像对象.
* [group-array](https://github.com/doowb/group-array) - 将对象数组分组到列表中.
* [array.chunk](https://github.com/zhiyelee/array.chunk) - 将数组/TypedArray 拆分为给定大小的块.
* [fast-cartesian](https://github.com/ehmicky/fast-cartesian) - 快速笛卡尔积.

### String

* [decamelize](https://github.com/sindresorhus/decamelize) - 使用自定义分隔符将驼峰字符串转换为小写字符串：unicornRainbow → unicorn_rainbow.
* [pad-left](https://github.com/jonschlinkert/pad-left) - 用零或指定字符串向左填充字符串.
* [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - 将字符串转换为驼峰式大小写.
* [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - 将字符串转换为大写字母.
* [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - 将字符串转换为常量大小写.
* [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - 将字符串转换为点大小写.
* [to-no-case](https://github.com/ianstormtaylor/to-no-case) - 从字符串中删除现有的情况.
* [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - 将字符串转换为帕斯卡大小写.
* [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - 将字符串转换为句子大小写.
* [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - 将字符串转换为蛇形大小写.
* [to-space-case](https://github.com/ianstormtaylor/to-space-case) - 将字符串转换为空格.
* [to-title-case](https://github.com/ianstormtaylor/to-title-case) - 将字符串转换为标题大小写.
* [node-slug](https://github.com/dodo/node-slug) - 甚至可以对 utf-8 字符进行 slugizes.
* [rtrim](https://github.com/sergejmueller/rtrim) - 从字符串末尾去除空格或其他字符.
* [slice.js](https://github.com/hustcc/slice.js) - 使用 python 切片样式增强 String.substring / Array.slice 的 Javascript 库.
* [strip-ansi](https://github.com/chalk/strip-ansi) - 去除 ANSI 转义码.
* [striptags](https://github.com/ericnorris/striptags) - PHP 的 strip_tags 在 Node.js 中的实现.
* [parse-next-json-value](https://github.com/ErikOnBike/parse-next-json-value) - 从字符串中解析下一个 JSON 值，允许值后面有无关字符.
* [pluralize](https://github.com/DaniAkash/pluralizer) - 一个非常小的单词复数库


### Date & Time

* [pretty-ms](https://github.com/sindresorhus/pretty-ms) - 将毫秒转换为人类可读的字符串：1337000000 → 15d 11h 23m 20s.
* [hirestime](https://github.com/seriousManual/hirestime) - 内置高分辨率计时器的包装，简化了时间戳的计算.
* [periods](https://github.com/timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds.
* [fecha](https://github.com/taylorhakes/fecha) - Javascript 日期格式化和解析.
* [akamai-time-reference](https://github.com/jucrouzet/akamai-time-reference) - 使用 Akamai 的时间参考服务获取参考时间.
* [timeago.js](https://github.com/hustcc/timeago.js) - 一个小型（~1.7kb）库，用于使用“*** time ago”语句格式化日期.
* [count-days-in-month](https://github.com/shinnn/count-days-in-month) - 获取给定月份的天数.
* [time-stamp](https://github.com/jonschlinkert/time-stamp) - 获取格式化的时间戳.
* [twas](https://github.com/vutran/twas) - 生成相对时间字符串（示例：“3 秒前”）

### Object

* [map-obj](https://github.com/sindresorhus/map-obj) - 将对象键和值映射到新对象中.
* [filter-obj](https://github.com/sindresorhus/filter-obj) - 将对象键和值过滤到新对象中.
* [object-values](https://github.com/sindresorhus/object-values) - 获取对象的值.
* [object-pairs](https://github.com/eush77/object-pairs) - 将对象转换为[键，值]对列表以用于映射、迭代或其他目的.
* [zipmap](https://github.com/landau/zipmap)  - 返回一个映射，其中键映射到相应的值.  zipmap 还接受对象或对的单个值.
* [just-pluck](https://github.com/jarofghosts/just-pluck) - 不疯狂地采摘.
* [deep-equal](https://github.com/substack/node-deep-equal) - Node 的assert.deepEqual() 算法作为独立模块.
* [deep-assign](https://github.com/sindresorhus/deep-assign) - 递归Object.assign().
* [set-value](https://github.com/jonschlinkert/set-value) - 创建嵌套值和任何中间点符号 (`&#39;abc&#39;`) 路径.
* [get-value](https://github.com/jonschlinkert/get-value) - 使用属性路径 (abc) 从对象中获取嵌套值.
* [has-value](https://github.com/jonschlinkert/has-value)  - 如果值存在则返回 true，如果为空则返回 false. 使用点表示法 (`&#39;abc&#39;`) 路径处理深度嵌套的值.
* [has-key-deep](https://github.com/ryanaghdam/has-key-deep)  - 深度搜索对象的键. 可以通过提供键数组或使用点表示法来搜索键.
* [flatkeys](https://github.com/ricardobeat/flatkeys) - 使用自定义分隔符将对象键层次结构展平为字符串列表.
* [flatten-obj](https://github.com/watson/flatten-obj) - 将具有深层嵌套节点的对象文字转换为简单的键/值对象.
* [is-empty-object](https://github.com/gummesson/is-empty-object) - 检查对象是否为空.
* [stringify-object](https://github.com/yeoman/stringify-object) - 像 JSON.stringify 一样对对象/数组进行字符串化，只是没有所有双引号.
* [sorted-object](https://github.com/domenic/sorted-object) - 返回一个对象的副本，其键已排序.
* [static-props](https://github.com/fibo/static-props) - 使用“Object.defineProperties”定义静态对象属性
* [missing-deep-keys](https://github.com/vladgolubev/missing-deep-keys) - 返回第一个对象中第二个对象中缺失的键数组.
* [has-own-property](https://github.com/LinusU/has-own-property) - 检查对象是否具有本地属性. 
* [merge-objects](https://github.com/shevaroller/node-merge-objects)  - 深度合并两个对象. 具有相同对象键值的数组会被连接起来.
* [deep-object-diff](https://github.com/mattphillips/deep-object-diff)  - 深度比较两个 JavaScript 对象，同时保留数据结构. 包括数组和对象的嵌套结构.

### Function

* [compose-function](https://github.com/stoeffel/compose-function) - 从较小的函数“f(g(x))”组成一个新函数.
* [curry](https://github.com/dominictarr/curry) - 咖喱函数，没有任何太聪明的东西.
* [once](https://github.com/isaacs/once) - 只运行一次函数.
* [deep-bind](https://github.com/jonschlinkert/deep-bind) - 将上下文绑定到对象中的所有函数，包括深度嵌套的函数.
* [identity-function](https://github.com/substack/identity-function) - 始终返回输入参数. 
* [mem](https://github.com/sindresorhus/mem) - 一种优化技术，用于通过缓存具有相同输入的调用结果来加速连续函数调用.
* [throttle-debounce](https://github.com/niksy/throttle-debounce) - 限制/消除你的功能.
* [compose-tiny](https://github.com/hipstersmoothie/compose-tiny) - 一个非常小而快速的撰写功能.

### Math

* [is-even](https://github.com/jonschlinkert/is-even)  - 判断数字是否为偶数的好方法（避免类型问题）. 在底层使用“is-odd”和“is-number”.
* [is-number](https://github.com/jonschlinkert/is-number) - 如果值为数字，则返回“true”.
* [is-odd](https://github.com/jonschlinkert/is-odd)  - 判断数字是否为奇数的好方法（避免类型问题）. 在底层使用“is-number”.
* [easy-math.js](https://github.com/kingzez/easy-math.js) - 一个简单的小型数学库，包括加法、乘法、减法和除法.
* [my-prime](https://github.com/jinnatul/my-prime) - 判断一个数是否为质数的好方法.
* [fun-gcd](https://github.com/zubayerhimel/fun-gcd) - 一个小型数学库，使用欧几里德算法获取两个数字的 gcd

### Stream
* [through2](https://github.com/rvagg/through2) - 节点流2变换周围的微小包装以避免显式子类化噪音.
* [through2-filter](https://github.com/brycebaril/through2-filter) - through2 为流创建 Array.prototype.filter 模拟.
* [through2-map](https://github.com/brycebaril/through2-map) - through2 为流创建 Array.prototype.map 模拟.
* [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - 可读流生成器，可用于测试简单函数或将简单函数转换为可读流.
* [concat-stream](https://github.com/maxogden/concat-stream) - 连接字符串或数据并使用结果调用回调的可写流.
* [JSONStream](https://github.com/dominictarr/JSONStream) - 流式 JSON.parse 和 stringify
* [through2-map-promise](https://github.com/RangerMauve/through2-map-promise) - through2 的一个基于承诺的小型包装器.
* [pump](https://github.com/mafintosh/pump) - 将流通过管道连接在一起，如果其中一个流关闭，则关闭所有流.
* [split](https://github.com/dominictarr/split) - 分解一个流并重新组合它，使每一行都是一个块.
* [is-stream](https://github.com/sindresorhus/is-stream) - 检查某物是否是 Node.js 流.
* [syncthrough](https://github.com/mcollina/syncthrough) - 同步转换您的数据.


### Promise

* [pify](https://github.com/sindresorhus/pify) - Promise 回调式函数.
* [promise-all-props](https://github.com/Siilwyn/promise-all-props) - 与“Promise.all”类似，但针对对象属性.
* [sleep-promise](https://github.com/brummelte/sleep-promise) - 在指定的延迟后解决承诺.
* [is-promise](https://github.com/then/is-promise) - 测试一个对象是否看起来像一个 Promise-a+ Promise.

### Data Structure

* [quetie](https://github.com/TomerAberbach/quetie) - 最可爱、最小的队列/双端队列实现！

### File System

* [rimraf](https://github.com/isaacs/rimraf) - 节点的深度删除模块（如 rm -rf）.
* [mkdirp](https://github.com/substack/node-mkdirp) - 递归mkdir，如mkdir -p.
* [du](https://github.com/rvagg/node-du) - du -sb 的简单 JavaScript 实现.
* [file-size](https://github.com/Nijikokun/file-size) - 轻量级文件大小为人类可读/比例，无依赖性.
* [tmp](https://github.com/raszi/node-tmp) - Node.js 的临时文件和目录创建器.
* [fs-promise](https://github.com/kevinbeaty/fs-promise) - 节点 fs 方法为 Promise/A+（可选 fs-extra、graceful-fs）.
* [read-git-user](https://github.com/RocktimSaikia/read-git-user) - 从 `.gitconfig` :wrench: 读取用户名和电子邮件并将其作为 json 对象返回.

### Browser

* [delegate](https://github.com/zenorocha/delegate) - 轻量级事件委托.
* [insert-css](https://github.com/substack/insert-css) - 在头部插入一串css
* [dom-element-value](https://github.com/crysalead-js/dom-element-value) - DOM 元素值获取器/设置器.
* [image-promise](https://github.com/bfred-it/image-promise)  - 加载一个或多个`<img> 是在一个承诺中.
* [get-media-size](https://github.com/bfred-it/get-media-size) - 获取任何“img”/“video”/“svg”/“canvas”标签或画布上下文的原始大小.
* [document-ready](https://github.com/bendrucker/document-ready) - 现代浏览器的文档就绪侦听器.
* [copee](https://github.com/styfle/copee) - 将文本从浏览器复制到剪贴板...本机！

### Semver

* [semver](https://github.com/npm/node-semver) - npm 使用的语义版本解析器.
* [semver-max](https://github.com/eush77/semver-max) - 根据 semver 查找最大（或最小）版本.
* [semver-first-satisfied](https://github.com/parro-it/semver-first-satisfied) - 在版本数组中查找满足 semver 范围的最小值.



### CLI

* [abbrev](https://github.com/isaacs/abbrev-js) - 计算给定字符串集的唯一缩写集.
* [glob](https://github.com/isaacs/node-glob) - Node.js 的全局功能.
* [username](https://github.com/sindresorhus/username) - 获取当前用户的用户名.
* [minimist](https://github.com/substack/minimist) - 解析参数选项.
* [png-to-ico](https://github.com/steambap/png-to-ico) - 将 png 转换为 windows ico 格式.
* [help-version](https://github.com/eush77/help-version) - 在 CLI 应用程序中轻松处理 --help 和 --version 参数

### Module management

* [pkg-conf](https://github.com/sindresorhus/pkg-conf) - 从最近的 package.json 获取命名空间配置.
* [normalize-pkg](https://github.com/jonschlinkert/normalize-pkg) - 标准化 package.json 中的值，以提高第三方库的兼容性、编程可读性和实用性.

### Generators

* [is-generator](https://github.com/blakeembrey/is-generator) - 检查给定值是否是生成器函数.

### Other

* [uuid](https://github.com/kelektiv/node-uuid) - 在 JavaScript 中生成符合 RFC 的 UUID.
* [node-mime](https://github.com/broofa/node-mime) - 基于 mime-db 模块的综合 MIME 类型映射 API.
* [not-defined](https://github.com/fibo/not-defined) - 检查 foo 是否未定义，即未定义、null、空字符串、数组或对象.
* [is-fqdn](https://github.com/parro-it/is-fqdn) - 检查字符串是否代表完全限定的域名.
* [shurley](https://github.com/BrunoBernardino/shurley) - 解析来自用户输入的 URL（协议中可能存在拼写错误、错误的复制+粘贴等）并返回正确的 URL.
* [mime-type-check](https://github.com/RocktimSaikia/mime-type-check) - 通过文件扩展名获取文件的 MIME 类型.
* [nanoid](https://github.com/ai/nanoid) - 一个小型（130 字节）、安全、URL 友好、唯一的 JavaScript 字符串 ID 生成器

## Related lists

本节包含一些很棒的列表，如果您使用或编写小型 NPM 模块，您可能会发现这些列表很有用.

* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - 令人愉快的 Node.js 包和资源的精选列表.
* [awesome-npm](https://github.com/sindresorhus/awesome-npm) - 很棒的 npm 资源和技巧.

## Small modules rockstars to follow

这些人被用来开发遵循单一责任理念的出色 NPM 模块.
跟随他们发现新的精彩模块：

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|---
[Sindre Sorhus](https://github.com/sindresorhus) | [James Halliday](https://github.com/substack) | [Eugene Sharygin](https://github.com/eush77) | [Isaac Z. Schlueter](https://github.com/isaacs) | [Jon Schlinkert](https://github.com/jonschlinkert) | [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden) | [![Brian Woodward](https://avatars1.githubusercontent.com/u/995160?s=130)](https://github.com/doowb)
---|---|---
[Rod Vagg](https://github.com/rvagg) | [Max Ogden](https://github.com/maxogden) | [Brian Woodward](https://github.com/doowb)


## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/parro-it/awesome-micro-npm-packages/blob/master/contributing.md) 第一的.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Andrea Parodi](https://github.com/parro-it) 已放弃本作品的所有版权以及相关或邻接权.
