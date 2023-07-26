<div class="github-widget" data-repo="kdeldycke/awesome-iam"></div>
<!--lint disable awesome-heading-->

<p align="center">
  <a href="https://github.com/kdeldycke/awesome-iam#readme">
    <img src="https://raw.githubusercontent.com/kdeldycke/awesome-iam/main/assets/awesome-iam-header.jpg" alt="Awesome IAM">
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/kdeldycke/awesome-iam#readme" hreflang="en"><img src="https://img.shields.io/badge/lang-English-blue?style=flat-square" lang="en" alt="English"></a>
  <a href="https://raw.githubusercontent.com/kdeldycke/awesome-iam/blob/main/readme.zh.md" hreflang="zh"><img src="https://img.shields.io/badge/lang-汉语-blue?style=flat-square" lang="zh" alt="汉语"></a>
</p>

<p align="center">
  <sup>This list is <a href="#sponsor-def">sponsored<sup id="sponsor-ref">[0]</sup></a> by:</sup><br>
</p>

<p align="center">
  <a href="https://www.descope.com/?utm_source=awesome-iam&utm_medium=referral&utm_campaign=awesome-iam-oss-sponsorship">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kdeldycke/awesome-iam/main/assets/descope-logo-dark-background.svg?sanitize=true">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kdeldycke/awesome-iam/main/assets/descope-logo-light-background.svg?sanitize=true">
      <img width="300" src="https://raw.githubusercontent.com/kdeldycke/awesome-iam/main/assets/descope-logo-light-background.svg">
    </picture>
    <br/>
    <strong>拖放您的身份验证.</strong><br/>
    使用几行代码向您的应用程序添加身份验证、用户管理和授权.
  </a>
  <!-- Comment this sponsorship call-to-action if there is a sponsor logo to increase its impact. -->
  <!--
  <a href="https://github.com/sponsors/kdeldycke">
    <strong>Yᴏᴜʀ Iᴅᴇɴᴛɪᴛʏ &amp; Aᴜᴛʜᴇɴᴛɪᴄᴀᴛɪᴏɴ Pʀᴏᴅᴜᴄᴛ ʜᴇʀᴇ！</strong>
    <br/>
    <sup>在此处添加指向您的公司或项目的链接：通过 GitHub 赞助支持我.</sup>
  </a>
  -->
</p>

---

<p align="center">
  </i> </i><br>
  — Maria V. Snyder<sup id="intro-quote-ref"><a href="#intro-quote-def">[1]</a></sup>
</p>

<!--lint disable double-link-->

[IAM](https://en.wikipedia.org/wiki/Identity_management) 代表身份和访问管理. 这是一个复杂的域，涵盖**用户帐户、身份验证、授权、角色、权限和隐私**. 它是云堆栈的重要支柱，是用户、产品和安全性的结合点. 这 [other pillar being billing & payments 💰](https://github.com/kdeldycke/awesome-billing/).

此次策划 [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) 列表以全面且可操作的方式公开该领域的所有技术、协议和术语.

<!--lint enable double-link-->


<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->


<!-- mdformat-toc end -->

## Overview

<img align="right" width="50%" src="https://raw.githubusercontent.com/kdeldycke/awesome-iam/master/./assets/cloud-software-stack-iam.jpg"/>

在斯坦福大学的一堂课上，提供了 [overview of cloud computing](http://web.stanford.edu/class/cs349d/docs/L01_overview.pdf)，平台软件架构描述如右图→

在这里，我们列出了总体情况：该领域的定义和战略重要性、它在更大的生态系统中的地位，以及一些关键功能.

- [The EnterpriseReady SaaS Feature Guides](https://www.enterpriseready.io) - 让 B2B 用户满意的大部分功能将由 IAM 外围实现.

- [IAM is hard. It's really hard.](https://twitter.com/kmcquade3/status/1291801858676228098)  - “过于宽松的 AWS IAM 政策允许‘s3:GetObject’访问‘*’（所有）资源”，导致 Capital One 被处以 8000 万美元的罚款. 作为企业主，您不能忽视 IAM 的唯一原因.

- [IAM Is The Real Cloud Lock-In](https://forrestbrazeal.com/2019/02/18/cloud-irregular-iam-is-the-real-cloud-lock-in/)  - 有点*点击诱骗*，但作者承认，“这取决于你对他们的信任程度： 1. 继续经营；  2.不抬高价格；  3. 不弃用您手下的服务；  4. 在业务加速方面为您提供的价值比在灵活性方面带来的价值更多.”

## Security

安全性是 IAM 基础的最核心支柱之一. 以下是一些广泛的概念.

- [Enterprise Information Security](https://infosec.mozilla.org) - Mozilla 的安全和访问指南.

- [Mitigating Cloud Vulnerabilities](https://media.defense.gov/2020/Jan/22/2002237484/-1/-1/0/CSI-MITIGATING-CLOUD-VULNERABILITIES_20200121.PDF) - “本文档将云漏洞分为四类（配置错误、访问控制不良、共享租赁漏洞和供应链漏洞）”.

- [Cartography](https://github.com/lyft/cartography)  - 一个基于 Neo4J 的工具，用于绘制服务和资源之间的依赖关系和关系. 支持 AWS、GCP、GSuite、Okta 和 GitHub.

- [Open guide to AWS Security and IAM](https://github.com/open-guides/og-aws#security-and-iam)

## Account Management

IAM的基础：用户、组、角色和权限的定义和生命周期.

- [As a user, I want…](https://mobile.twitter.com/oktopushup/status/1030457418206068736) - 账户管理的元批评者，其中业务期望的功能与真实用户需求发生冲突，以虚构的项目经理编写的用户故事的形式.

- [Things end users care about but programmers don't](https://instadeq.com/blog/posts/things-end-users-care-about-but-programmers-dont/)  - 本着与上述相同的精神，但范围更广：作为开发人员我们忽视但用户真正关心的所有小事情. 该列表的顶部是以帐户为中心的功能、多样化的集成和导入/导出工具. 即覆盖所有企业客户的需求.

- [Separate the account, user and login/auth details](https://news.ycombinator.com/item?id=21151830) - 为面向未来的 IAM API 奠定基础的合理建议.

- [Identity Beyond Usernames](https://lord.io/blog/2020/usernames/) - 关于用户名作为标识符的概念，以及 unicode 字符满足唯一性要求时引入的复杂性.

- [Kratos](https://github.com/ory/kratos) - 用户登录、用户注册、2FA 和个人资料管理.

- [Conjur](https://github.com/cyberark/conjur) - 自动保护特权用户和机器身份使用的机密.

- [SuperTokens](https://github.com/supertokens/supertokens-core) - 用于登录和会话管理的开源项目，支持无密码、社交登录、电子邮件和电话登录.

- [UserFrosting](https://github.com/userfrosting/UserFrosting) - 现代 PHP 用户登录和管理框架.

## Cryptography

整个身份验证堆栈基于加密原语. 这一点不容忽视.

- [Cryptographic Right Answers](https://latacora.micro.blog/2018/04/03/cryptographic-right-answers.html)  - 为非密码工程师的开发人员提供的一组最新建议. 甚至还有一个 [shorter summary](https://news.ycombinator.com/item?id=16749140) 可用的.

- [Real World Crypto Symposium](https://rwc.iacr.org) - 旨在将密码学研究人员与开发人员聚集在一起，重点关注在互联网、云和嵌入式设备等现实环境中的使用.

- [An Overview of Cryptography](https://www.garykessler.net/library/crypto.html)  - “这篇论文有两个主要目的. 首先是定义基本加密方法背后的一些术语和概念，并提供一种方法来比较当今使用的无数加密方案. 第二是提供一些当今使用的密码学的真实例子.”

- [Papers we love: Cryptography](https://github.com/papers-we-love/papers-we-love/blob/master/cryptography/README.md) - 密码学基础论文.

- [Lifetimes of cryptographic hash functions](http://valerieaurora.org/hash.html) - “如果您使用哈希比较来生成恶意用户可能提供的数据地址，那么您应该制定计划，每隔几年迁移到新的哈希”.

### Identifiers

令牌、主键、UUID……无论最终用途如何，您都必须生成具有一些随机性和唯一性属性的这些数字.

- [Security Recommendations for Any Device that Depends on Randomly-Generated Numbers](https://www.av8n.com/computer/htm/secure-random.htm)  - “短语‘随机数生成器’应解析如下：它是数字的随机生成器. 它不是随机数生成器.”

- [RFC #4122: UUID - Security Considerations](https://www.rfc-editor.org/rfc/rfc4122#section-6)  - “不要假设 UUID 很难猜测； 它们不应被用作安全功能（仅拥有即可授予访问权限的标识符）”.  UUID 被设计为唯一的，而不是随机的或不可预测的：不要将 UUID 用作秘密.

- [Awesome Identifiers](https://adileo.github.io/awesome-identifiers/) - 所有标识符格式的基准.

- [Awesome GUID](https://github.com/secretGeek/AwesomeGUID) - 对唯一标识符的全球方面的有趣看法.

## Zero-trust Network

零信任网络安全的运作原则是“从不信任，始终验证”.

- [BeyondCorp: A New Approach to Enterprise Security](https://www.usenix.org/system/files/login/articles/login_dec14_02_ward.pdf) - 快速概述 Google 的零信任网络计划.

- [What is BeyondCorp? What is Identity-Aware Proxy?](https://medium.com/google-cloud/what-is-beyondcorp-what-is-identity-aware-proxy-de525d9b3f90)  - 越来越多的公司添加了额外的 VPN、防火墙、限制和约束层，从而导致糟糕的体验和轻微的安全增益. 有更好的方法.

- [oathkeeper](https://github.com/ory/oathkeeper)  - 身份和访问代理以及访问控制决策 API，用于验证、授权和改变传入的 HTTP 请求. 受到 BeyondCorp / 零信任白皮书的启发.

- [transcend](https://github.com/cogolabs/transcend) - 受 BeyondCorp 启发的访问代理服务器.

- [Pomerium](https://github.com/pomerium/pomerium) - 身份感知代理，可安全访问内部应用程序.

## Authentication

用于验证您是否是您假装的人的协议和技术.

- [API Tokens: A Tedious Survey](https://fly.io/blog/api-tokens-a-tedious-survey/) - 最终用户 API 的所有基于令牌的身份验证方案的概述和比较.

- [A Child's Garden of Inter-Service Authentication Schemes](https://web.archive.org/web/20200507173734/https://latacora.micro.blog/a-childs-garden/) - 本着与上述相同的精神，但这次是在服务层面.

- [Scaling backend authentication at Facebook](https://www.youtube.com/watch?v=kY-Bkv3qxMc)  - 简而言之：1. 小信任根；  2. TLS 还不够；  3. 基于证书的代币；  4. 加密身份验证令牌 (CAT). 请参阅 [slides](https://rwc.iacr.org/2018/Slides/Lewi.pdf) 更多细节.

### Password-based

- [The new NIST password guidance](https://pciguru.wordpress.com/2019/03/11/the-new-nist-password-guidance/) - 总结 [NIST Special Publication 800-63B](https://pages.nist.gov/800-63-3/sp800-63b.html) 涵盖新的密码复杂性指南.

- [Password Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html) - 减缓离线攻击的唯一方法是仔细选择尽可能占用资源的哈希算法.

- [Password expiration is dead](https://techcrunch.com/2019/06/02/password-expiration-is-dead-long-live-your-passwords/) - 最近的科学研究对许多长期存在的密码安全实践（例如密码过期策略）的价值提出了质疑，并指出了更好的替代方案，例如强制执行禁止密码列表和 MFA.

- [Practical Recommendations for Stronger, More Usable Passwords](http://www.andrew.cmu.edu/user/nicolasc/publications/Tan-CCS20.pdf) - 本研究建议关联：针对常见泄露密码的阻止列表检查、无字符类要求的密码策略、最小强度策略.

- [Banks, Arbitrary Password Restrictions and Why They Don't Matter](https://www.troyhunt.com/banks-arbitrary-password-restrictions-and-why-they-dont-matter/)  - “对长度和字符组成的任意低限制是不好的. 它们看起来很糟糕，会导致对安全状况的负面猜测，还会破坏密码管理器等工具.”

- [Dumb Password Rules](https://github.com/dumb-password-rules/dumb-password-rules) - 用愚蠢的密码规则羞辱网站.

- [Plain Text Offenders](https://plaintextoffenders.com/about/) - 对以纯文本形式存储密码的网站进行公开羞辱.

- [Password Manager Resources](https://github.com/apple/password-manager-resources) - 密码规则、更改 URL 和站点怪癖的集合.

- [A Well-Known URL for Changing Passwords](https://github.com/WICG/change-password-url) - 定义密码更新站点资源的规范.

- [How to change the hashing scheme of already hashed user's passwords](https://news.ycombinator.com/item?id=20109360)  - 好消息：您不再受制于旧密码保存方案. 这是一个透明地升级到更强的哈希算法的技巧.

### Password-less

- [An argument for passwordless](https://web.archive.org/web/20190515230752/https://biarity.gitlab.io/2018/02/23/passwordless/)  - 密码并不是用户身份验证的全部和最终目的. 这篇文章试图告诉你原因.

- [Magic Links – Are they Actually Outdated?](https://zitadel.com/blog/magic-links) - 什么是魔法链接，它们的起源，优点和缺点.

- [WebAuthn guide](https://webauthn.guide) - 非常容易理解的 WebAuthn 指南，该标准允许“服务器使用公钥加密技术而不是密码来注册和验证用户”，受到所有主要浏览器的支持.

### Security Key

- [Webauthn and security keys](https://www.imperialviolet.org/2018/03/27/webauthn.html)  - 描述身份验证如何使用安全密钥，详细介绍协议以及它们如何与 WebAuthn 结合. 要点：“但是，无法使用 webauthn 创建 U2F 密钥.  (…) 因此，请先完成登录过程到 Webauthn 的转换，然后再转换注册.”

- [Getting started with security keys](https://paulstamatiou.com/getting-started-with-security-keys/) - 使用 FIDO2、WebAuthn 和安全密钥保持在线安全并防止网络钓鱼的实用指南.

- [Solo](https://github.com/solokeys/solo) - 通过 USB + NFC 支持 FIDO2 和 U2F 的开放安全密钥.

- [OpenSK](https://github.com/google/OpenSK) - 用 Rust 编写的安全密钥的开源实现，支持 FIDO U2F 和 FIDO2 标准.

- [YubiKey Guide](https://github.com/drduh/YubiKey-Guide)  - 使用 YubiKey 作为智能卡来存储 GPG 加密、签名和身份验证密钥（也可用于 SSH）的指南. 本文档中的许多原则也适用于其他智能卡设备.

- [YubiKey at Datadog](https://github.com/DataDog/yubikey) - 设置 Yubikey、U2F、GPG、git、SSH、Keybase、VMware Fusion 和 Docker Content Trust 的指南.

### Multi-Factor

- [Breaking Password Dependencies: Challenges in the Final Mile at Microsoft](https://www.youtube.com/watch?v=B_mhJO2qHlQ)  - 帐户黑客攻击的主要来源是密码喷射（在传统身份验证上，如 SMTP、IMAP、POP 等），其次是重放攻击. 要点：密码不安全，请使用并强制执行 MFA.

- [Beyond Passwords: 2FA, U2F and Google Advanced Protection](https://www.troyhunt.com/beyond-passwords-2fa-u2f-and-google-advanced-protection/) - 对所有这些技术的出色讲解.

- [A Comparative Long-Term Study of Fallback Authentication](https://maximiliangolla.com/files/2019/papers/usec2019-30-wip-fallback-long-term-study-finalv5.pdf)  - 要点：“基于电子邮件和短信的方案更有用. 另一方面，基于指定受托人和个人知识问题的机制在便利性和效率方面都存在不足.”

- [Secrets, Lies, and Account Recovery: Lessons from the Use of Personal Knowledge Questions at Google](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43783.pdf)  - “我们的分析证实，秘密问题通常提供的安全级别远低于用户选择的密码.  (…) 令人惊讶的是，我们发现这种不安全感的一个重要原因是用户经常不如实回答.  （……）在可用性方面，我们表明秘密答案的记忆力出奇地差”.

- [How effective is basic account hygiene at preventing hijacking](https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html) - Google 安全团队的数据显示 2FA 可以 100% 阻止自动机器人黑客攻击.

- [Your Pa\$\$word doesn't matter](https://techcommunity.microsoft.com/t5/Azure-Active-Directory-Identity/Your-Pa-word-doesn-t-matter/ba-p/731984) - 与上述 Microsoft 的结论相同：“根据我们的研究，如果您使用 MFA，您的帐户被盗的可能性会降低 99.9% 以上.”

- [Attacking Google Authenticator](https://unix-ninja.com/p/attacking_google_authenticator) - 可能处于偏执边缘，但可能是限制 2FA 验证尝试的原因.

- [Compromising online accounts by cracking voicemail systems](https://www.martinvigo.com/voicemailcracker/)  - 或者为什么您不应依赖自动电话作为联系用户和重置密码、2FA 或任何类型验证的方法. 与基于短信的 2FA 不同，它目前并不安全，并且可能会因其最薄弱的环节：语音邮件系统而受到损害.

- [Getting 2FA Right in 2019](https://blog.trailofbits.com/2019/06/20/getting-2fa-right-in-2019/) - 关于 2FA 的用户体验方面.

- [2FA is missing a key feature](https://syslog.ravelin.com/2fa-is-missing-a-key-feature-c781c3861db) - “当我的 2FA 代码输入错误时，我想了解一下”.

- [SMS Multifactor Authentication in Antarctica](https://brr.fyi/posts/sms-mfa) - 不起作用，因为南极洲的车站没有手机信号塔.

- [Authelia](https://github.com/authelia/authelia) - 开源身份验证和授权服务器通过 Web 门户为您的应用程序提供双因素身份验证和单点登录 (SSO).

- [Kanidm](https://github.com/kanidm/kanidm) - 简单、安全、快速的身份管理平台.

### SMS-based

 TL;DR：不要. 有关详细信息，请参阅下面的文章.

- [SMS 2FA auth is deprecated by NIST](https://techcrunch.com/2016/07/25/nist-declares-the-age-of-sms-based-2-factor-authentication-over/) - 自 2016 年以来，NIST 表示通过短信进行的 2FA 很糟糕而且很糟糕.

- [SMS: The most popular and least secure 2FA method](https://www.allthingsauth.com/2018/02/27/sms-the-most-popular-and-least-secure-2fa-method/)

- [Is SMS 2FA Secure? No.](https://www.issms2fasecure.com) - 展示 SIM 交换成功尝试的权威研究项目.

- [Hackers Hit Twitter C.E.O. Jack Dorsey in a 'SIM Swap.' You're at Risk, Too.](https://www.nytimes.com/2019/09/05/technology/sim-swap-jack-dorsey-hack.html)

- [AT&T rep handed control of his cellphone account to a hacker](https://www.theregister.co.uk/2017/07/10/att_falls_for_hacker_tricks/)

- [The Most Expensive Lesson Of My Life: Details of SIM port hack](https://medium.com/coinmonks/the-most-expensive-lesson-of-my-life-details-of-sim-port-hack-35de11517124)

- [SIM swap horror story](https://www.zdnet.com/article/sim-swap-horror-story-ive-lost-decades-of-data-and-google-wont-lift-a-finger/)

- [AWS is on its way to deprecate SMS-based 2FA](https://aws.amazon.com/iam/details/mfa/)  - “我们鼓励您通过 U2F 安全密钥、硬件设备或虚拟（基于软件的）MFA 设备来使用 MFA. 您可以继续使用此功能直至 2019 年 1 月 31 日.”

### Public-Key Infrastructure (PKI)

基于证书的身份验证.

- [PKI for busy people](https://gist.github.com/hoffa/5a939fd0f3bcd2a6a0e4754cb2cf3f1b) - 快速概述重要内容.

- [Everything you should know about certificates and PKI but are too afraid to ask](https://smallstep.com/blog/everything-pki.html)  - PKI 允许您以加密方式定义系统. 它是通用的且供应商中立的.

- [`lemur`](https://github.com/Netflix/lemur) - 充当 CA 和环境之间的代理，为开发人员提供一个中央门户，以颁发具有“合理”默认值的 TLS 证书.

- [CFSSL](https://github.com/cloudflare/cfssl)  - CloudFlare 的 PKI/TLS 瑞士军刀. 用于签名、验证和捆绑 TLS 证书的命令行工具和 HTTP API 服务器.

- [JA3](https://github.com/salesforce/ja3) - 创建 SSL/TLS 客户端指纹的方法，该指纹应该易于在任何平台上生成，并且可以轻松共享以获取威胁情报.

### JWT

[JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) 是一个不记名的令牌.

- [Introduction to JSON Web Tokens](https://jwt.io/introduction/) - 通过本文快速了解 JWT.

- [Learn how to use JWT for Authentication](https://github.com/dwyl/learn-json-web-tokens) - 了解如何使用 JWT 来保护您的 Web 应用程序.

- [Using JSON Web Tokens as API Keys](https://auth0.com/blog/using-json-web-tokens-as-api-keys/) - 与 API 密钥相比，JWT 提供精细的安全性、同质身份验证架构、去中心化发行、OAuth2 合规性、可调试性、过期控制、设备管理.

- [Managing a Secure JSON Web Token Implementation](https://cursorblog.com/managing-a-secure-json-web-token-implementation/) - JWT 具有各种灵活性，使其难以很好地使用.

- [Hardcoded secrets, unverified tokens, and other common JWT mistakes](https://r2c.dev/blog/2020/hardcoded-secrets-unverified-tokens-and-other-common-jwt-mistakes/) - 对智威汤逊所有陷阱的一个很好的回顾.

- [Adding JSON Web Token API Keys to a DenyList](https://auth0.com/blog/denylist-json-web-token-api-keys/) - 令牌失效.

- [Stop using JWT for sessions](http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/) - 和 [why your "solution" doesn't work](http://cryto.net/%7Ejoepie91/blog/2016/06/19/stop-using-jwt-for-sessions-part-2-why-your-solution-doesnt-work/)， 因为 [stateless JWT tokens cannot be invalidated or updated](https://news.ycombinator.com/item?id=18354141) . 它们会引入尺寸问题或安全问题，具体取决于您存储它们的位置. 有状态 JWT 令牌在功能上与会话 cookie 相同，但没有经过实战测试和充分审查的实现或客户端支持.

- [JWT, JWS and JWE for Not So Dummies!](https://medium.facilelogin.com/jwt-jws-and-jwe-for-not-so-dummies-b63310d201a3)  - 签名的 JWT 称为 JWS（JSON Web 签名）. 事实上，JWT 本身并不存在——它必须是 JWS 或 JWE（JSON Web 加密）. 它就像一个抽象类——JWS 和 JWE 是具体的实现.

- [JOSE is a Bad Standard That Everyone Should Avoid](https://paragonie.com/blog/2017/03/jwt-json-web-tokens-is-bad-standard-that-everyone-should-avoid) - 标准要么完全被破坏，要么是难以驾驭的复杂雷区.

- [JWT.io](https://jwt.io) - 允许您解码、验证和生成 JWT.

- [`loginsrv`](https://github.com/tarent/loginsrv) - 独立的简约登录服务器，为多个登录后端（htpasswd、OSIAM、用户/密码、HTTP 基本身份验证、OAuth2：GitHub、Google、Bitbucket、Facebook、Gitlab）提供 JWT 登录.

- [jwtXploiter](https://github.com/DontPanicO/jwtXploiter) - 测试 json Web 令牌安全性的工具.

### OAuth2 & OpenID

[OAuth 2.0](https://en.wikipedia.org/wiki/OAuth#OAuth_2.0) 是一个*委托授权*框架. [OpenID Connect (OIDC)](https://en.wikipedia.org/wiki/OpenID_Connect) 是其之上的*身份验证*层.

旧的*OpenID*已经死了； 新的*OpenID Connect* 还没有消亡.

- [The problem with OAuth for Authentication](http://www.thread-safe.com/2012/01/problem-with-oauth-for-authentication.html)  - “问题是 OAuth 2.0 是委托授权协议，而不是身份验证协议.”  10年后，这篇文章仍然是最好的解释 [why use OpenID Connect instead of plain OAuth2](https://security.stackexchange.com/a/260519)?

- [An Illustrated Guide to OAuth and OpenID Connect](https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc) - 使用简化的插图解释这些标准的工作原理.

- [OAuth 2 Simplified](https://aaronparecki.com/oauth-2-simplified/) - 以简化格式描述协议的参考文章，以帮助开发人员和服务提供商实现它.

- [OAuth 2.0 and OpenID Connect (in plain English)](https://www.youtube.com/watch?v=996OiexHze0) - 从这些标准如何产生的历史背景开始，澄清词汇中的不准确之处，然后详细说明协议及其陷阱，以使其不那么令人生畏.

- [Everything You Need to Know About OAuth (2.0)](https://gravitational.com/blog/everything-you-need-to-know-about-oauth/) - 通过实际案例研究很好地概述了开源远程访问工具 Teleport 如何允许用户通过 GitHub SSO 登录.

- [OAuth in one picture](https://mobile.twitter.com/kamranahmedse/status/1276994010423361540) - 一张漂亮的总结卡.

- [How to Implement a Secure Central Authentication Service in Six Steps](https://engineering.shopify.com/blogs/engineering/implement-secure-central-authentication-service-six-steps)  - 有多个遗留系统要与自己的登录方法和帐户合并吗？ 以下是如何通过 OIDC 合并所有混乱的内容.

- [Open-Sourcing BuzzFeed's SSO Experience](https://increment.com/security/open-sourcing-buzzfeeds-single-sign-on-process/)  - 中央身份验证服务 (CAS) 协议的 OAuth2 友好改编. 您会发现很好的 OAuth 用户流程图.

- [OAuth 2.0 Security Best Current Practice](https://tools.ietf.org/html/draft-ietf-oauth-security-topics-16) - “更新和扩展了 OAuth 2.0 安全威胁模型，以纳入自 OAuth 2.0 发布以来收集的实践经验，并涵盖由于更广泛的应用而相关的新威胁”.

- [Hidden OAuth attack vectors](https://portswigger.net/web-security/oauth) - 如何识别和利用 OAuth 2.0 身份验证机制中发现的一些关键漏洞.

- [PKCE Explained](https://www.loginradius.com/blog/engineering/pkce/) - “PKCE 用于为 OAuth 和 OpenID Connect 中的授权代码流提供又一个安全层.”

- [Hydra](https://gethydra.sh) - 开源 OIDC 和 OAuth2 服务器.

- [Keycloak](https://www.keycloak.org)  - 开源身份和访问管理. 支持 OIDC、OAuth 2 和 SAML 2、LDAP 和 AD 目录、密码策略.

- [Casdoor](https://github.com/casbin/casdoor)  - 基于 UI 优先的集中式身份验证/单点登录 (SSO) 平台. 支持 OIDC 和 OAuth 2、社交登录、用户管理、基于电子邮件和短信的 2FA.

- [authentik](https://goauthentik.io/?#correctness) - 类似于Keycloak的开源身份提供者.

- [ZITADEL](https://github.com/zitadel/zitadel)  - 使用 Go 和 Angular 构建的开源解决方案，用于管理所有系统、用户和服务帐户及其角色和外部身份.  ZITADEL 为您提供 OIDC、OAuth 2.0、登录和注册流程、无密码和 MFA 身份验证. 所有这一切都建立在事件外包之上，并与 CQRS 相结合，以提供出色的审计跟踪.

- [a12n-server](https://github.com/curveball/a12n-server) - 一个简单的身份验证系统，仅实现 OAuth2 标准的相关部分.

- [Logto](https://github.com/logto-io/logto) - 使用此基于 OIDC 的身份服务构建登录、身份验证和用户身份.

- [The Decline of OpenID](https://penguindreams.org/blog/the-decline-of-openid/) - OpenID 在公共网络中被替换为 OAuth 1、OAuth 2 或其他专有 SSO 协议的组合.

- [Why Mastercard Doesn't Use OAuth 2.0](https://developer.mastercard.com/blog/why-mastercard-doesnt-use-oauth-20)  - “他们这样做是为了提供消息级别的完整性.  OAuth 2 切换到传输级机密性/完整性.”  （TLS 提供）（[source](https://news.ycombinator.com/item?id=17486165)).

- [OAuth 2.0 and the Road to Hell](https://gist.github.com/nckroy/dd2d4dfc86f7d13045ad715377b6a48f) - Oauth 2.0 规范的主要作者和编辑的辞职信.

### SAML

安全断言标记语言 (SAML) 2.0 是一种在服务之间交换授权和身份验证的方法，例如上面的 OAuth/OpenID 协议.

典型的 SAML 身份提供商是机构或大公司的内部 SSO，而典型的 OIDC/OAuth 提供商是运行数据竖井的科技公司.

- [SAML vs. OAuth](https://web.archive.org/web/20230327071347/https://www.cloudflare.com/learning/access-management/what-is-oauth/)  - “OAuth 是一种授权协议：它确保 Bob 前往正确的停车场. 相比之下，SAML 是一种身份验证协议，或者允许 Bob 通过警卫室.”

- [The Difference Between SAML 2.0 and OAuth 2.0](https://www.ubisecure.com/uncategorized/difference-between-saml-and-oauth/)  - “尽管 SAML 实际上被设计为广泛适用，但其当前的使用通常转向企业 SSO 场景. 另一方面，OAuth 设计用于互联网上的应用程序，特别是委派授权.”

- [What's the Difference Between OAuth, OpenID Connect, and SAML?](https://www.okta.com/identity-101/whats-the-difference-between-oauth-openid-connect-and-saml/)  - 身份很难. 我们总是欢迎对不同协议的另一种看法，以帮助理解这一切.

- [How SAML 2.0 Authentication Works](https://gravitational.com/blog/how-saml-authentication-works/) - SSO 和 SAML 的方式和原因概述.

- [Web Single Sign-On, the SAML 2.0 perspective](https://blog.theodo.com/2019/06/web-single-sign-on-the-saml-2-0-perspective/) - 在企业 SSO 实施的背景下对 SAML 工作流程的另一个天真的解释.

- [The Beer Drinker's Guide to SAML](https://duo.com/blog/the-beer-drinkers-guide-to-saml)  - SAML 有时很神秘. 另一个类比可能有助于从中获得更多意义.

- [SAML is insecure by design](https://joonas.fi/2021/08/saml-is-insecure-by-design/)  - 不仅奇怪，SAML 在设计上也是不安全的，因为它依赖于基于 XML 规范化的签名，而不是 XML 字节流. 这意味着您可以利用 XML 解析器/编码器的差异.

- [The Difficulties of SAML Single Logout](https://wiki.shibboleth.net/confluence/display/CONCEPT/SLOIssues) - 关于单点注销实施的技术和用户体验问题.

- [The SSO Wall of Shame](https://sso.tax)  - 对 SaaS 提供商在其产品上激活 SSO 实行过高定价的有记录的咆哮. 作者的观点是，作为一项核心安全功能，SSO 的定价应该合理，而不是专属级别的一部分.

## Authorization

Now we know you are you. But are you allowed to do what you want to do?

政策规范是科学，执行是艺术.

### Policy models

作为一个概念，访问控制策略可以设计为遵循非常不同的原型，从经典 [Access Control Lists](https://en.wikipedia.org/wiki/Access-control_list) 到 [Role Based Access Control](https://en.wikipedia.org/wiki/Role-based_access_control) . 在本节中，我们将探讨许多不同的模式和架构.

- [Why Authorization is Hard](https://www.osohq.com/post/why-authorization-is-hard) - 因为它需要在很多地方都需要的执行、将业务逻辑与授权逻辑分离的决策架构以及平衡功能和复杂性的建模方面进行多重权衡.

- [The never-ending product requirements of user authorization](https://alexolivier.me/posts/the-never-ending-product-requirements-of-user-authorization) - 基于角色的简单授权模型是不够的，并且由于产品包装、数据局部性、企业组织和合规性而迅速变得复杂.

- [RBAC like it was meant to be](https://tailscale.com/blog/rbac-like-it-was-meant-to-be/)  - 我们如何从 DAC（unix 权限、秘密 URL）到 MAC（DRM、MFA、2FA、SELinux）再到 RBAC. 详细介绍了后者如何更好地对策略、ACL、用户和组进行建模.

- [The Case for Granular Permissions](https://cerbos.dev/blog/the-case-for-granular-permissions) - 讨论 RBAC 的局限性以及 ABAC（基于属性的访问控制）如何解决这些局限性.

- [In Search For a Perfect Access Control System](https://goteleport.com/blog/access-controls/)  - 授权方案的历史渊源. 暗示不同团队和组织之间共享、信任和授权的未来.

- [AWS IAM Roles, a tale of unnecessary complexity](https://infosec.rodeo/posts/thoughts-on-aws-iam/) - AWS 快速增长的历史解释了当前方案的形成过程，以及它与 GCP 资源层次结构的比较.

- [Semantic-based Automated Reasoning for AWS Access Policies using SMT](https://d1.awsstatic.com/Security/pdfs/Semantic_Based_Automated_Reasoning_for_AWS_Access_Policies_Using_SMT.pdf)  - Zelkova 就是 AWS 的做法. 该系统对IAM策略进行符号分析，根据用户的权限和访问约束来解决资源的可达性问题. 另请参阅更高级别 [introduction given at re:inforce 2019](https://youtu.be/x6wsTFnU3eY?t=2111).

- [Zanzibar: Google's Consistent, Global Authorization System](https://ai.google/research/pubs/pub48190)  - 可扩展到每秒数万亿个访问控制列表和数百万个授权请求，以支持数十亿人使用的服务. 在 3 年的生产使用中，它保持了 95% 的延迟低于 10 毫秒，可用性高于 99.999%. [Other bits not in the paper](https://twitter.com/LeaKissner/status/1136626971566149633). [Zanzibar Academy](https://zanzibar.academy/) 是一个致力于解释桑给巴尔如何运作的网站.

- [SpiceDB](https://github.com/authzed/spicedb) - 受桑给巴尔启发，用于管理安全关键应用程序权限的开源数据库系统.

- 描述 [authz system that is built around labeled security and RBAC concepts](https://news.ycombinator.com/item?id=20136831).

### Open-source policy frameworks

如果您希望实施自己的政策，请收集开源项目.

- [Keto](https://github.com/ory/keto)  - 政策决策点. 它使用一组访问控制策略（类似于 AWS 策略）来确定主体是否有权对资源执行特定操作.

- [Ladon](https://github.com/ory/ladon) - 访问控制库，受 AWS 启发.

- [Athenz](https://github.com/yahoo/athenz) - 一组服务和库，支持用于供应和配置的服务身份验证和基于角色的授权 (RBAC).

- [Casbin](https://github.com/casbin/casbin) - Golang 项目的开源访问控制库.

- [Open Policy Agent](https://github.com/open-policy-agent/opa) - 开源通用决策引擎，用于创建和实施基于属性的访问控制 (ABAC) 策略.

- [Topaz](https://github.com/aserto-dev/topaz) - 一个开源项目，它将 OPA 的策略即代码和决策日志记录与桑给巴尔建模目录相结合.

- [Open Policy Administration Layer](https://github.com/permitio/opal)  - OPA 的开源管理层，实时检测策略和策略数据的变化，并将实时更新推送到 OPA 代理.  OPAL 使开放策略达到实时应用程序所需的速度.

- [Gubernator](https://github.com/mailgun/gubernator) - 高性能限速微服务和库.

- [Biscuit](https://www.clever-cloud.com/blog/engineering/2021/04/12/introduction-to-biscuit/)  - Biscuit 合并了 cookie、JWT、蛋白杏仁饼干和开放策略代理的概念.  “它提供了一种基于Datalog的逻辑语言来编写授权策略. 它可以存储数据（如 JWT）或小条件（如杏仁饼），但它也能够表示更复杂的规则，如基于角色的访问控制、委派、层次结构.”

- [Oso](https://github.com/osohq/oso) - 包含电池的库，用于在您的应用程序中构建授权.

- [Cerbos](https://github.com/cerbos/cerbos) - 用于编写上下文感知访问控制策略的授权端点.

### AWS policy tools

专门针对 [AWS IAM policies](http://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html) 生态系统.

- [Become an AWS IAM Policy Ninja](https://www.youtube.com/watch?v=y7-fAT3z8Lo) - “在亚马逊工作的近 5 年里，我每天、每周都会抽出一点时间浏览论坛、客户票证，试图找出人们在哪里遇到了麻烦.”

- [Cloudsplaining](https://github.com/salesforce/cloudsplaining) - 安全评估工具，可识别违反最低权限的行为并生成风险优先级报告.

- [Policy Sentry](https://github.com/salesforce/policy_sentry)  - 手动编写具有安全意识的 IAM 策略可能非常乏味且效率低下.  Policy Sentry 可帮助用户在几秒钟内创建最低权限策略.

- [Aardvark and Repokid](https://netflixtechblog.com/introducing-aardvark-and-repokid-53b081bf3a7e)  - Netflix 工具在 AWS 上强制执行最低权限. 这个想法是，新事物的默认策略是全部拒绝，然后它监视 cloudtrail 的权限失败并重新配置 IAM 以允许尽可能小的权限来摆脱该拒绝消息.

- [Principal Mapper](https://github.com/nccgroup/PMapper) - 快速评估权限.

- [PolicyUniverse](https://github.com/Netflix-Skunkworks/policyuniverse) - 解析和处理 AWS 策略、语句、ARN 和通配符.

- [IAM Floyd](https://github.com/udondan/iam-floyd)  - 具有流畅界面的 AWS IAM 策略声明生成器. 通过 IntelliSense 提供条件和 ARN 生成，帮助创建类型安全的 IAM 策略并编写更具限制性/安全的语句. 适用于 Node.js、Python、.Net 和 Java.

- [ConsoleMe](https://github.com/Netflix/consoleme) - AWS 的自助服务工具，根据跨多个帐户管理权限的授权级别，为最终用户和管理员提供对已登录帐户的凭证和控制台访问权限，同时鼓励使用最低权限.

- [IAMbic](https://github.com/noqdev/iambic)  - IAM 的 GitOps.  Cloud IAM 的 Terraform.  IAMbic 是一个多云身份和访问管理 (IAM) 控制平面，可集中并简化云访问和权限. 它在版本控制中维护 IAM 的最终一致、人类可读的双向表示.

### Macaroons

对分配和委托授权的聪明好奇心.

- [Google's Macaroons in Five Minutes or Less](https://blog.bren2010.io/blog/googles-macaroons) - 如果我得到一个杏仁饼，授权我在某些限制下执行某些操作，我可以非交互式地构建第二个具有更严格限制的杏仁饼，然后我可以将其提供给您.

- [Macaroons: Cookies with Contextual Caveats for Decentralized Authorization in the Cloud](https://ai.google/research/pubs/pub41892) - 谷歌的原始论文.

- [Google paper's author compares Macaroons and JWTs](https://news.ycombinator.com/item?id=14294463)  - 作为杏仁饼的消费者/验证者，他们允许您（通过第三方警告）将某些授权决定推迟给其他人.  JWT 则不然.

## Secret Management

Architectures, software and hardware allowing the storage and usage of secrets to allow for authentication and authorization, while maintaining the chain of trust.

- [Secret at Scale at Netflix](https://www.youtube.com/watch?v=K0EOPddWpsE)  - 基于盲签名的解决方案. 请参阅 [slides](https://rwc.iacr.org/2018/Slides/Mehta.pdf).

- [High Availability in Google's Internal KMS](https://www.youtube.com/watch?v=5T_c-lqgjso) - Not GCP's KMS, but the one at the core of their infrastructure. See the [slides](https://rwc.iacr.org/2018/Slides/Kanagala.pdf).

- [`vault`](https://www.vaultproject.io) - 保护、存储和严格控制对令牌、密码、证书、加密密钥的访问.

- [`sops`](https://github.com/mozilla/sops) - 加密 YAML 和 JSON 文件的值，而不是密钥.

- [`gitleaks`](https://github.com/zricethezav/gitleaks) - 审核 git 存储库中的秘密.

- [`truffleHog`](https://github.com/dxa4481/truffleHog) - 在 git 存储库中搜索高熵字符串和秘密，深入挖掘提交历史记录.

- [Keywhiz](https://square.github.io/keywhiz/) - 一个用于管理和分发秘密的系统，它可以很好地适应面向服务的架构（SOA）.

- [`roca`](https://github.com/crocs-muni/roca) - 用于检查各种密钥格式中的弱 RSA 模数的 Python 模块.

### Hardware Security Module (HSM)

HSM是在硬件层面保证机密管理安全的物理设备.

- [HSM: What they are and why it's likely that you've (indirectly) used one today](https://rwc.iacr.org/2015/Slides/RWC-2015-Hampton.pdf) - HSM 用法的基本概述.

- [Tidbits on AWS Cloud HSM hardware](https://news.ycombinator.com/item?id=16759383) - AWS CloudHSM Classic 由 SafeNet 的 Luna HSM 支持，当前的 CloudHSM 依赖于 Cavium 的 Nitrox，它允许可分区的“虚拟 HSM”.

- [CrypTech](https://cryptech.is) - 开放硬件 HSM.

- [Keystone](https://keystone-enclave.org) - 基于 RISC-V 架构，用于构建具有安全硬件飞地的可信执行环境 (TEE) 的开源项目.

- [Project Oak](https://github.com/project-oak/oak) - 数据安全传输、存储和处理的规范和参考实现.

- [Everybody be cool, this is a robbery!](https://www.sstic.org/2019/presentation/hsm/) - HSM 的漏洞和可利用性案例研究（法语，抱歉）.

## Trust & Safety

一旦你拥有了重要的用户群，它就被称为社区. 然后，您将负责保护它：客户、人员、公司、业务，并促进其中发生的所有交互和交易.

信任与安全部门是一个由政策和当地法律约束驱动的关键中介综合体，很可能由一个由 24/7 运营商和高度先进的审核和管理工具系统组成的跨职能团队体现. 您可以将其视为客户支持服务的延伸，专门处理边缘情况，例如手动身份检查、有害内容审核、停止骚扰、处理搜查令和版权索赔、数据扣押和其他信用卡纠纷.

- [Trust and safety 101](https://www.csoonline.com/article/3206127/trust-and-safety-101.html) - 关于该领域及其职责的精彩介绍.

- [What the Heck is Trust and Safety?](https://www.linkedin.com/pulse/what-heck-trust-safety-kenny-shi) - 几个真实的用例来展示 TnS 团队的作用.

<!--lint disable double-link-->

- [Awesome List of Billing and Payments: Fraud links](https://github.com/kdeldycke/awesome-billing#fraud) - 专门用于计费和付款欺诈管理的部分，来自我们的姊妹存储库.

<!--lint enable double-link-->

### User Identity

大多数企业不会收集客户的身份来创建用户配置文件以出售给第三方，不会. 但您仍然必须：当地法律要求跟踪大额合同关系 [Know You Customer (KYC)](https://en.wikipedia.org/wiki/Know_your_customer) 横幅.

- [The Laws of Identity](https://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.pdf) - 本文针对的是身份元系统，其定律在较小规模上仍然提供了很好的见解，尤其是第一定律：始终允许用户控制并请求同意以赢得信任.

- [How Uber Got Lost](https://www.nytimes.com/2019/08/23/business/how-uber-got-lost.html)  -“为了限制“摩擦”，Uber 允许乘客注册，无需提供电子邮件（很容易伪造）或电话号码以外的身份信息.  (…) 车辆被盗并被烧毁； 司机遭到袭击、抢劫，有时甚至被谋杀. 即使暴力事件有所增加，该公司仍坚持采用低摩擦的注册系统.”

- [A Comparison of Personal Name Matching: Techniques and Practical Issues](http://users.cecs.anu.edu.au/~Peter.Christen/publications/tr-cs-06-02.pdf) - 客户姓名匹配有很多应用，从帐户重复数据删除到欺诈监控.

- [Statistically Likely Usernames](https://github.com/insidetrust/statistically-likely-usernames) - 用于创建统计上可能的用户名的单词列表，用于用户名枚举、模拟密码攻击和其他安全测试任务.

- [Facebook Dangerous Individuals and Organizations List](https://theintercept.com/document/2021/10/12/facebook-dangerous-individuals-and-organizations-list-reproduced-snapshot/)  - 某些团体和内容在某些司法管辖区是非法的. 这是阻止列表的示例.

- [Ballerine](https://github.com/ballerine-io/ballerine) - 用于用户身份和风险管理的开源基础设施.

- [Sherlock](https://github.com/sherlock-project/sherlock) - 通过社交网络上的用户名搜索社交媒体帐户.

### Fraud

作为在线服务提供商，您面临着欺诈、犯罪和滥用行为的风险. 你会惊讶地发现人们在金钱方面变得如此聪明. 预计工作流程中的任何错误或差异都会被利用来获取经济利益.

- [After Car2Go eased its background checks, 75 of its vehicles were stolen in one day.](https://web.archive.org/web/20230526073109/https://www.bloomberg.com/news/articles/2019-07-11/mercedes-thieves-showed-just-how-vulnerable-car-sharing-can-be) - Why background check are sometimes necessary.

- [Investigation into the Unusual Signups](https://openstreetmap.lu/MWGGlobalLogicReport20181226.pdf)  - 对 OpenStreetMap 上可疑贡献者注册的真正详细分析. 这份精美且高水平的报告展示了精心策划和定向的活动，可以作为欺诈报告的模板.

- [MIDAS: Detecting Microcluster Anomalies in Edge Streams](https://github.com/bhatiasiddharth/MIDAS) - 提出的方法“使用恒定的时间和内存检测边缘流中的微簇异常或突然到达的可疑相似边缘组”.

- [Gephi](https://github.com/gephi/gephi) - 用于可视化和操作大型图形的开源平台.

### Moderation

任何在线社区，不仅仅是那些与游戏和社交网络相关的社区，都需要其运营商投入大量资源和精力来对其进行管理.

- [Still Logged In: What AR and VR Can Learn from MMOs](https://youtu.be/kgw8RLHv1j4?t=534)  - “如果你主持一个在线社区，人们可能会伤害另一个人：你就陷入了困境. 如果您承担不起责任，就不要主办在线社区”.

- [You either die an MVP or live long enough to build content moderation](https://mux.com/blog/you-either-die-an-mvp-or-live-long-enough-to-build-content-moderation/)  - “你可以通过考虑三个维度来思考这个问题的解决方案空间：成本、准确性和速度. 两种方法：人工审查和机器审查. 人类在以下几个方面都很伟大：准确性. 缺点是人类成​​本昂贵且缓慢. 机器或机器人在其他两个方面表现出色：成本和速度——它们更便宜、速度更快. 但我们的目标是找到一种能够足够准确地满足您的需求的机器人解决方案.”

- [Keep out the bad apples: How to moderate a marketplace](https://www.twosided.io/p/keep-out-the-bad-apples-how-to-moderate)  - “拥有权利的同时也被赋予了重大的责任. 我的一些提示和技巧可以让您的市场变得更安全.”

- [The despair and darkness of people will get to you](https://restofworld.org/2020/facebook-international-content-moderators/)  - 庞大的社交网络的管理是由大量外包分包商执行的. 这些人面临着最糟糕的情况，通常最终会患上创伤后应激障碍 (PTSD).

- [The Cleaners](https://thoughtmaybe.com/the-cleaners/) - 一部关于这些工资过低的团队删除帖子和删除帐户的纪录片.

### Threat Intelligence

如何检测、揭露和分类攻击性在线活动. 大多数时候，这些都是由安全、网络和/或基础设施工程团队监控的. 尽管如此，这些对于 T&amp;S 和 IAM 人员来说都是很好的资源，他们可能需要额外的专业知识来分析和处理威胁.

- [Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) - “威胁情报的简明定义：基于证据的知识，包括有关现有或新出现的威胁或资产危害的背景、机制、指标、影响和可行的建议，可用于为有关主体对该威胁的响应的决策提供信息或危险.”

- [SpiderFoot](https://github.com/smicallef/spiderfoot)  - 开源情报 (OSINT) 自动化工具. 它与几乎所有可用的数据源集成，并使用一系列数据分析方法，使数据易于导航.

- [Standards related to Threat Intelligence](https://www.threat-intelligence.eu/standards/) - 支持威胁情报分析的开放标准、工具和方法.

- [MISP taxonomies and classification](https://www.misp-project.org/taxonomies.html) - 用于组织“威胁情报，包括网络安全指标、金融欺诈或反恐信息”的标签.

- [Browser Fingerprinting: A survey](https://arxiv.org/pdf/1905.01051.pdf) - 指纹可用作识别机器人和欺诈者的信号源.

- [The challenges of file formats](https://speakerdeck.com/ange/the-challenges-of-file-formats)  - 在某一时刻，您将允许用户在您的系统中上传文件. 这里有一个 [corpus of suspicious media files](https://github.com/corkami/pocs) 骗子可以利用它来绕过安全或愚弄用户.

- [SecLists](https://github.com/danielmiessler/SecLists)  - 安全评估期间使用的多种类型列表的收集，收集在一个地方. 列表类型包括用户名、密码、URL、敏感数据模式、模糊测试负载、Web shell 等等.

- [PhishingKitTracker](https://github.com/neonprimetime/PhishingKitTracker) - 网络钓鱼工具包中威胁行为者使用的电子邮件地址的 CSV 数据库.

- [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga)  - 仅使用免费资源扫描电话号码的工具. 目标是首先以非常高的准确性收集任何国际电话号码的标准信息，例如国家、地区、运营商和线路类型. 然后在搜索引擎上搜索足迹，尝试找到 VoIP 提供商或识别所有者.

- [Confusable Homoglyphs](https://github.com/vhf/confusable_homoglyphs) - 同形文字是一种常见的网络钓鱼伎俩.

### Captcha

抵御垃圾邮件发送者的另一道防线.

- [Awesome Captcha](https://github.com/ZYSzys/awesome-captcha) - 参考所有开源验证码库、集成、替代方案和破解工具.

- [reCaptcha](https://www.google.com/recaptcha) - 当您的公司无力拥有专门的团队来对抗互联网规模的机器人和垃圾邮件发送者时，reCaptcha 仍然是一种有效、经济且快速的解决方案.

- [You (probably) don't need ReCAPTCHA](https://web.archive.org/web/20190611190134/https://kevv.net/you-probably-dont-need-recaptcha/) - 首先抱怨该服务是隐私噩梦，并且在用户界面方面很乏味，然后列出替代方案.

- [Anti-captcha](https://anti-captcha.com) - 验证码解决服务.

## Blocklists

防止滥用行为的第一道机械防线包括简单明了的拒绝名单. 这是打击欺诈的唾手可得的成果，但您会惊讶地发现它们仍然有效.

- [Bloom Filter](https://en.wikipedia.org/wiki/Bloom_filter)  - 非常适合此用例，因为布隆过滤器旨在快速检查元素是否不在（大）集合中. 针对特定数据类型存在不同的布隆过滤器变体.

- [How Radix trees made blocking IPs 5000 times faster](https://blog.sqreen.com/demystifying-radix-trees/) - 基数树可能会方便地加速 IP 阻止列表.

### Hostnames and Subdomains

对于识别客户端、捕获和阻止机器人群以及限制 dDOS 的影响非常有用.

- [`hosts`](https://github.com/StevenBlack/hosts) - 整合信誉良好的主机文件，并将它们合并为统一的主机文件，并删除重复项.

- [`nextdns/metadata`](https://github.com/nextdns/metadata) - 广泛收集安全、隐私和家长控制列表.

- [The Public Suffix List](https://publicsuffix.org) - Mozilla 的公共后缀注册表，互联网用户可以（或历史上可以）直接注册名称.

- [Country IP Blocks](https://github.com/herrbischoff/country-ip-blocks) - CIDR 国家级 IP 数据直接来自区域互联网注册管理机构，每小时更新一次.

- [Certificate Transparency Subdomains](https://github.com/internetwache/CT_subdomains) - 从证书透明度日志收集的每小时更新的子域列表.

- 子域拒绝列表： [#1](https://gist.github.com/artgon/5366868), [#2](https://github.com/sandeepshetty/subdomain-blacklist/blob/master/subdomain-blacklist.txt), [#3](https://github.com/nccgroup/typofinder/blob/master/TypoMagic/datasources/subdomains.txt), [#4](https://www.quora.com/How-do-sites-prevent-vanity-URLs-from-colliding-with-future-features).

- [`common-domain-prefix-suffix-list.tsv`](https://gist.github.com/erikig/826f49442929e9ecfab6d7c481870700) - 前 5000 个最常见的域前缀/后缀列表.

- [`hosts-blocklists`](https://github.com/notracking/hosts-blocklists) - 不再有广告、跟踪和其他虚拟垃圾.

- [`xkeyscorerules100.txt`](https://gist.github.com/sehrgut/324626fa370f044dbca7) - 美国国家安全局 [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore) TOR 和其他匿名保护工具的匹配规则.

- [`pyisp`](https://github.com/ActivisionGameScience/pyisp) - IP 到 ISP 查找库（包括 ASN）.

- [AMF site blocklist](https://www.amf-france.org/Epargne-Info-Service/Proteger-son-epargne/Listes-noires) - 法国官方禁止与金钱相关的欺诈网站名单.

### Emails

- [Burner email providers](https://github.com/wesbos/burner-email-providers)  - 临时电子邮件提供商列表. 还有它 [derivative Python module](https://github.com/martenson/disposable-email-domains).

- [MailChecker](https://github.com/FGRibreau/mailchecker) - 跨语言临时（一次性/一次性）电子邮件检测库.

- [Temporary Email Address Domains](https://gist.github.com/adamloving/4401361)  - 一次性和临时电子邮件地址的域列表. 对于过滤电子邮件列表以提高打开率很有用（向这些域发送电子邮件可能不会被打开）.

- [`gman`](https://github.com/benbalter/gman)  - “一个红宝石宝石，用于检查给定电子邮件地址或网站的所有者是否为 THE MAN 工作（又名验证政府域名）.” 在您的用户群中寻找潜在政府客户的好资源.

- [`Swot`](https://github.com/leereilly/swot) - 本着与上述相同的精神，但这次是为了标记学术用户.

### Reserved IDs

- [General List of Reserved Words](https://gist.github.com/stuartpb/5710271) - 这是您可能想要考虑在用户可以选择任何名称的系统中保留的单词的一般列表.

- [Hostnames and usernames to reserve](https://ldpreload.com/blog/names-to-reserve) - 应限制在自动化系统中注册的所有名称的列表.

### Profanity

- [List of Dirty, Naughty, Obscene, and Otherwise Bad Words](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words) - Shutterstock 的脏话黑名单.

- [`profanity-check`](https://github.com/vzhou842/profanity-check) - 使用线性 SVM 模型，该模型经过 20 万个人类标记的干净和亵渎文本字符串样本的训练.

## Privacy

作为用户数据的守护者，IAM 堆栈深深受到尊重隐私的约束.

- [Privacy Enhancing Technologies Decision Tree](https://www.private-ai.com/wp-content/uploads/2021/10/PETs-Decision-Tree.pdf) - 根据数据类型和上下文选择正确工具的流程图.

- [Paper we love: Privacy](https://github.com/papers-we-love/papers-we-love/tree/master/privacy) - 通过设计提供隐私的方案的科学研究集合.

- [IRMA Authentication](https://news.ycombinator.com/item?id=20144240) - 开源应用程序和协议，提供基于隐私友好属性的身份验证和签名 [Camenisch and Lysyanskaya's Idemix](https://privacybydesign.foundation/publications/).

- [Have I been Pwned?](https://haveibeenpwned.com) - 数据泄露指数.

- [Automated security testing for Software Developers](https://fahrplan.events.ccc.de/camp/2019/Fahrplan/system/event_attachments/attachments/000/003/798/original/security_cccamp.pdf) - Most privacy breaches were allowed by known vulnerabilities in third-party dependencies. Here is how to detect them by the way of CI/CD.

- [Email marketing regulations around the world](https://github.com/threeheartsdigital/email-marketing-regulations) - 随着世界联系日益紧密，电子邮件营销监管环境变得越来越复杂.

- [World's Biggest Data Breaches & Hacks](https://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/) - 不要成为下一个泄露客户数据的公司.

### Anonymization

作为用户数据的中央存储库，IAM 堆栈利益相关者必须防止业务和客户数据的任何泄漏. 为了进行内部分析，需要匿名化.

- [The False Allure of Hashing for Anonymization](https://gravitational.com/blog/hashing-for-anonymization/)  - 散列不足以实现匿名化. 但它对于假名化来说仍然足够好（这是 GDPR 允许的）.

- [Four cents to deanonymize: Companies reverse hashed email addresses](https://freedom-to-tinker.com/2018/04/09/four-cents-to-deanonymize-companies-reverse-hashed-email-addresses/) - “散列电子邮件地址可以轻松逆转并链接到个人”.

- [Why differential privacy is awesome](https://desfontain.es/privacy/differential-privacy-awesomeness.html) - 解释背后的直觉 [differential privacy](https://en.wikipedia.org/wiki/Differential_privacy) ，一个理论框架，允许在不损害机密性的情况下共享聚合数据. 请参阅后续文章 [more details](https://desfontain.es/privacy/differential-privacy-in-more-detail.html) 和 [practical aspects](https://desfontain.es/privacy/differential-privacy-in-practice.html).

- [k-anonymity: an introduction](https://www.privitar.com/listing/k-anonymity-an-introduction) - 另一种匿名隐私模型.

- [Presidio](https://github.com/microsoft/presidio) - 上下文感知、可插入和可定制的数据保护以及文本和图像的 PII 数据匿名化服务.

- [Diffix: High-Utility Database Anonymization](https://aircloak.com/wp-content/uploads/apf17-aspen.pdf) - Diffix 尝试提供匿名化、避免假名化并保持数据质量. [Written in Elixir at Aircloak](https://elixirforum.com/t/aircloak-anonymized-analitycs/10930)，它充当分析师和未修改的实时数据库之间的 SQL 代理.

### GDPR

著名的欧洲隐私框架

- [GDPR Tracker](https://gdpr.eu) - 欧洲的参考网站.

- [GDPR Developer Guide](https://github.com/LINCnil/GDPR-Developer-Guide) - 开发人员的最佳实践.

- [GDPR – A Practical guide for Developers](https://techblog.bozho.net/gdpr-practical-guide-developers/) - 上述内容的一页摘要.

- [GDPR Tracker](https://gdprtracker.io) - 跟踪云服务和分处理商的 GDPR 合规性.

- [GDPR documents](https://github.com/good-lly/gdpr-documents) - 供个人使用的模板，以使公司遵守“数据访问”请求.

- [Dark Patterns after the GDPR](https://arxiv.org/pdf/2001.02479.pdf) - 本文表明，由于缺乏 GDPR 执法，黑暗模式和默示同意无处不在.

- [GDPR Enforcement Tracker](http://enforcementtracker.com) - GDPR 罚款和处罚清单.

## UX/UI

作为 IAM 堆栈的利益相关者，您将在后端实现构建注册隧道和用户入门所需的大部分原语. 这是客户从你的产品中得到的第一印象，不能被忽视：你必须与前端专家一起仔细设计它. 这里有一些指南可以帮助您完善这种体验.

- [The 2020 State of SaaS Product Onboarding](https://userpilot.com/saas-product-onboarding/) - 涵盖用户入门的所有重要方面.

- [User Onboarding Teardowns](https://www.useronboard.com/user-onboarding-teardowns/) - 大量已解构的首次用户注册列表.

- [Discover UI Design Decisions Of Leading Companies](https://goodui.org/leaks/) - 来自泄露的屏幕截图和 A/B 测试.

- [Conversion Optimization](https://www.nickkolenda.com/conversion-optimization-psychology/#cro-tactic11) - 一系列策略，可增加用户完成帐户创建渠道的机会.

- [Trello User Onboarding](https://growth.design/case-studies/trello-user-onboarding/) - 详细的案例研究，很好地介绍了如何改进用户引导.

- [11 Tips for Better Signup / Login UX](https://learnui.design/blog/tips-signup-login-ux.html) - 登录表单的一些基本提示.

- [Don't get clever with login forms](http://bradfrost.com/blog/post/dont-get-clever-with-login-forms/) - 创建简单、可链接、可预测的登录表单，并与密码管理器完美配合.

- [Why are the username and password on two different pages?](https://www.twilio.com/blog/why-username-and-password-on-two-different-pages)  - 支持单点登录和基于密码的登录. 现在，如果分两步打破登录渠道让用户太恼火，请像 Dropbox 那样解决这个问题： [an AJAX request when you enter your username](https://news.ycombinator.com/item?id=19174355).

- [HTML attributes to improve your users' two factor authentication experience](https://www.twilio.com/blog/html-attributes-two-factor-authentication-autocomplete)  - “在这篇文章中，我们将看看谦虚的`<input>  ` 元素和 HTML 属性将有助于加快用户的两因素身份验证体验”.

- [Remove password masking](http://passwordmasking.com) - 总结了一项学术研究的结果，该研究调查了消除密码屏蔽对消费者信任的影响.

- [For anybody who thinks "I could build that in a weekend," this is how Slack decides to send a notification](https://twitter.com/ProductHunt/status/979912670970249221)  - 通知很难. 真的很难.

## Competitive Analysis

跟踪在该领域运营的开源项目和公司的活动.

- [Best-of Digital Identity](https://github.com/jruizaranguren/best-of-digital-identity) - 开源数字身份项目的排名、受欢迎程度和活动状态.

- [AWS Security, Identity & Compliance announcements](https://aws.amazon.com/about-aws/whats-new/security_identity_and_compliance/) - 添加到 IAM 边界的所有新功能的来源.

- [GCP IAM release notes](https://cloud.google.com/iam/docs/release-notes) - 另外值得注意的是： [Identity](https://cloud.google.com/identity/docs/release-notes), [Identity Platform](https://cloud.google.com/identity-platform/docs/release-notes), [Resource Manager](https://cloud.google.com/resource-manager/docs/release-notes), [Key Management Service/HSM](https://cloud.google.com/kms/docs/release-notes), [Access Context Manager](https://cloud.google.com/access-context-manager/docs/release-notes), [Identity-Aware Proxy](https://cloud.google.com/iap/docs/release-notes), [Data Loss Prevention](https://cloud.google.com/dlp/docs/release-notes) 和 [Security Scanner](https://cloud.google.com/security-scanner/docs/release-notes).

- [Unofficial Weekly Google Cloud Platform newsletter](https://www.gcpweekly.com) - 相关关键词： [`IAM`](https://www.gcpweekly.com/gcp-resources/tag/iam/) 和 [`Security`](https://www.gcpweekly.com/gcp-resources/tag/security/).

- [DigitalOcean Accounts changelog](http://docs.digitalocean.com/release-notes/accounts/) - DO 上的所有最新帐户更新.

- [163 AWS services explained in one line each](https://adayinthelifeof.nl/2020/05/20/aws.html#discovering-aws)  - 帮助了解他们庞大的服务目录. 本着同样的精神： [AWS in simple terms](https://netrixllc.com/blog/aws-services-in-simple-terms/) & [AWS In Plain English](https://expeditedsecurity.com/aws-in-plain-english/).

- [Google Cloud Developer's Cheat Sheet](https://github.com/gregsramblings/google-cloud-4-words#the-google-cloud-developers-cheat-sheet) - 用 4 个或更少的单词描述所有 GCP 产品.

## History

- [cryptoanarchy.wiki](https://cryptoanarchy.wiki)  - 密码朋克与安全重叠. 该维基汇编了有关该运动、其历史和值得注意的人物/事件的信息.

## Contributing

随时欢迎您的贡献！ 请看一下 [contribution guidelines](https://github.com/kdeldycke/awesome-iam/blob/master/.github/contributing.md) 第一的.

## Footnotes

The [header image](https://github.com/kdeldycke/awesome-iam/blob/main/assets/awesome-iam-header.jpg) 是基于修改 [photo](https://unsplash.com/photos/2LowviVHZ-E) by [Ben Sweet](https://unsplash.com/@benjaminsweet).

<!--lint disable no-undefined-references-->

<a name="sponsor-def">\[0\]</a>: You can <a href="https://github.com/sponsors/kdeldycke">add your Identity & Authentication product in the list of sponsors via a GitHub sponsorship</a>. [\[↑\]](#sponsor-ref)

<a name="intro-quote-def">\[1\]</a>: [*Poison Study*](https://www.amazon.com/dp/0778324338?&linkCode=ll1&tag=kevideld-20&linkId=0b92c3d92371bd53daca5457bdad327e&language=en_US&ref_=as_li_ss_tl) (Mira, 2007). [\[↑\]](#intro-quote-ref)
