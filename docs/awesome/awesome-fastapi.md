<div class="github-widget" data-repo="mjhea0/awesome-fastapi"></div>
<!--lint disable double-link-->

## Awesome FastAPI | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 FastAPI 相关的精彩内容的精选列表.

[FastAPI](https://fastapi.tiangolo.com/) 是一个现代、高性能、包含电池的 Python Web 框架，非常适合构建 RESTful API.



## Third-Party Extensions

### Admin

- [FastAPI Admin](https://github.com/fastapi-admin/fastapi-admin)  - 功能管理面板，提供用于对数据执行 CRUD 操作的用户界面. 目前仅适用于 Tortoise ORM.
- [FastAPI Amis Admin](https://github.com/amisadmin/fastapi-amis-admin) - 高性能、高效且易于扩展的 FastAPI 管理框架.
- [Piccolo Admin](https://github.com/piccolo-orm/piccolo_admin) - 强大且现代的管理 GUI，使用 Piccolo ORM.
- [SQLAlchemy Admin](https://github.com/aminalaee/sqladmin) - Admin Panel for FastAPI/Starlette that works with SQLAlchemy models.
- [Starlette Admin](https://github.com/jowilf/starlette-admin) - FastAPI/Starlette 的管理框架，支持 SQLAlchemy、SQLModel、MongoDB 和 ODMantic.


### Auth

- [AuthX](https://github.com/yezz123/AuthX) - FastAPI 的可定制身份验证和 Oauth2 管理.
- [FastAPI Auth](https://github.com/dmontagu/fastapi-auth) - 可插入身份验证，支持具有 JWT 访问和刷新令牌的 OAuth2 密码流程.
- [FastAPI Azure Auth](https://github.com/Intility/fastapi-azure-auth) - 通过单租户和多租户支持对 API 进行 Azure AD 身份验证.
- [FastAPI Cloud Auth](https://github.com/tokusumi/fastapi-cloudauth) - FastAPI 和云身份验证服务（AWS Cognito、Auth0、Firebase 身份验证）之间的简单集成.
- [FastAPI Login](https://github.com/MushroomMaula/fastapi_login) - 账户管理和身份验证（基于 [Flask-Login](https://github.com/maxcountryman/flask-login)).
- [FastAPI JWT Auth](https://github.com/IndominusByte/fastapi-jwt-auth) - JWT 身份验证（基于 [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended)).
- [FastAPI Permissions](https://github.com/holgi/fastapi-permissions) - 行级权限.
- [FastAPI Security](https://github.com/jacobsvante/fastapi-security) - 在 FastAPI 中将身份验证和授权作为依赖项实现.
- [FastAPI Simple Security](https://github.com/mrtolkien/fastapi_simple_security) - 可通过路径操作管理开箱即用的 API 密钥安全性.
- [FastAPI Users](https://github.com/fastapi-users/fastapi-users) - 账户管理、身份验证、授权.

### Databases

#### ORMs

- [FastAPI SQLAlchemy](https://github.com/mfreeborn/fastapi-sqlalchemy) - FastAPI 和之间的简单集成 [SQLAlchemy](https://www.sqlalchemy.org/).
- [Fastapi-SQLA](https://github.com/dialoguemd/fastapi-sqla) - FastAPI 的 SQLAlchemy 扩展，支持分页、异步和 pytest.
- [FastAPIwee](https://github.com/Ignisor/FastAPIwee) - 一种基于REST API创建的简单方法 [PeeWee](https://github.com/coleifer/peewee) 楷模.
- [GINO](https://github.com/python-gino/gino) - 一个轻量级异步 ORM，构建在 SQLAlchemy 核心之上，用于 Python asyncio.
  - [FastAPI Example](https://github.com/leosussan/fastapi-gino-arq-uvicorn)
- [ORM](https://github.com/encode/orm) - 异步 ORM.
- [ormar](https://collerek.github.io/ormar/)  - Ormar 是一个异步 ORM，它使用 Pydantic 验证，可以直接在 FastAPI 请求和响应中使用，因此您只需维护一组模型. 包括蒸馏器迁移.
  - [FastAPI Example](https://collerek.github.io/ormar/fastapi/) - 将 FastAPI 与 ormar 一起使用.
- [Piccolo](https://github.com/piccolo-orm/piccolo) - 异步 ORM 和查询生成器，支持 Postgres 和 SQLite，带有电池（迁移、安全性等）.
  - [FastAPI Examples](https://github.com/piccolo-orm/piccolo_examples) - 将 FastAPI 与 Piccolo 结合使用.
- [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) - 自动生成、完全类型安全的 ORM，由 Pydantic 提供支持，专为您的架构量身定制 - 支持 SQLite、PostgreSQL、MySQL、MongoDB、MariaDB 等.
  - [FastAPI Example](https://github.com/RobertCraigie/prisma-client-py/tree/main/examples/fastapi-basic)
- [Tortoise ORM](https://tortoise.github.io) - 受 Django 启发的易于使用的 asyncio ORM（对象关系映射器）.
  - [FastAPI Example](https://tortoise.github.io/examples/fastapi.html) - Tortoise-ORM FastAPI 集成的示例.
  - [Tutorial: Setting up Tortoise ORM with FastAPI](https://web.archive.org/web/20200523174158/https://robwagner.dev/tortoise-fastapi-setup/)
  - [Aerich](https://github.com/tortoise/aerich) - Tortoise ORM 迁移工具.
- [SQLModel](https://sqlmodel.tiangolo.com/) - SQLModel（由 Pydantic 和 SQLAlchemy 提供支持）是一个用于通过 Python 代码和 Python 对象与 SQL 数据库进行交互的库.

#### Query Builders

- [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - 一个包装纸 [asyncpg](https://github.com/MagicStack/asyncpg) 与使用 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/).
- [Databases](https://github.com/encode/databases) - 在之上工作的异步 SQL 查询构建器 [SQLAlchemy Core](https://docs.sqlalchemy.org/en/latest/core/) 表达语言.

#### ODMs

- [Beanie](https://github.com/roman-right/beanie) - MongoDB的异步Python ODM，基于 [Motor](https://motor.readthedocs.io/en/stable/) 和 [Pydantic](https://docs.pydantic.dev/latest/), which supports data 和 schema migrations out of the box.
- [MongoEngine](http://mongoengine.org/) - 文档对象映射器（想想 ORM，但用于文档数据库），用于从 Python 处理 MongoDB.
- [Motor](https://motor.readthedocs.io/) - MongoDB 的异步 Python 驱动程序.
- [ODMantic](https://art049.github.io/odmantic/) - AsyncIO MongoDB ODM 集成 [Pydantic](https://docs.pydantic.dev/latest/).
- [PynamoDB](https://github.com/pynamodb/PynamoDB) - Amazon DynamoDB 的 pythonic 接口.

#### Other Tools

- [Pydantic-SQLAlchemy](https://github.com/tiangolo/pydantic-sqlalchemy) - 将 SQLAlchemy 模型转换为 [Pydantic](https://docs.pydantic.dev/latest/) 楷模.
- [FastAPI-CamelCase](https://nf1s.github.io/fastapi-camelcase/) - 利用 FastAPI 支持 CamelCase JSON [Pydantic](https://docs.pydantic.dev/latest/).
  - [CamelCase Models with FastAPI and Pydantic](https://medium.com/analytics-vidhya/camel-case-models-with-fast-api-and-pydantic-5a8acb6c0eee) - 扩展作者的随附博客文章.

### Developer Tools

- [FastAPI Code Generator](https://github.com/koxudaxi/fastapi-code-generator) - 从 OpenAPI 文件创建 FastAPI 应用程序，从而实现架构驱动的开发.
- [FastAPI Client Generator](https://github.com/dmontagu/fastapi_client) - 根据 OpenAPI 规范生成 mypy 和 IDE 友好的 API 客户端.
- [FastAPI MVC](https://github.com/fastapi-mvc/fastapi-mvc) - 开发人员生产力工具，用于制作高质量的 FastAPI 生产就绪 API.
- [FastAPI Profiler](https://github.com/sunhailin-Leo/fastapi_profiler) - joerick/pyinstrument 的 FastAPI 中间件，用于检查您的服务性能.
- [FastAPI Versioning](https://github.com/DeanWay/fastapi-versioning) - API 版本控制.
- [Jupyter Notebook REST API](https://github.com/Invictify/Jupter-Notebook-REST-API) - 将 Jupyter 笔记本作为 RESTful API 端点运行.
- [Manage FastAPI](https://github.com/ycd/manage-fastapi) - 用于生成和管理 FastAPI 项目的 CLI 工具.
- [msgpack-asgi](https://github.com/florimondmanca/msgpack-asgi) - 自动 [MessagePack](https://msgpack.org/) 内容协商.

### Email

- [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) - 用于发送电子邮件和附件（单独和批量）的轻量级邮件系统.

### Utils

- [ASGI Correlation ID](https://github.com/snok/asgi-correlation-id) - 请求ID记录中间件.
- [FastAPI Cache](https://github.com/comeuplater/fastapi_cache) - 一个简单的轻量级缓存系统.
- [FastAPI Cache](https://github.com/long2ice/fastapi-cache) - 缓存 FastAPI 响应和函数结果的工具，支持 Redis、Memcached、DynamoDB 和内存后端.
- [FastAPI Chameleon](https://github.com/mikeckennedy/fastapi-chameleon) - 添加 Chameleon 模板语言与 FastAPI 的集成.
- [FastAPI Contrib](https://github.com/identixone/fastapi_contrib) - 一套自以为是的实用程序：分页、身份验证中间件、权限、自定义异常处理程序、MongoDB 支持和 Opentracing 中间件.
- [FastAPI CRUDRouter](https://github.com/awtkns/fastapi-crudrouter) - FastAPI 路由器，可自动为您的模型创建和记录 CRUD 路由.
- [FastAPI Events](https://github.com/melvinkcx/fastapi-events) - FastAPI 和 Starlette 的异步事件调度/处理库.
- [FastAPI FeatureFlags](https://github.com/Pytlicek/fastapi-featureflags) - FastAPI 功能标志的简单实现.
- [FastAPI Jinja](https://github.com/AGeekInside/fastapi-jinja) - 添加 Jinja 模板语言与 FastAPI 的集成.
- [FastAPI Lazy](https://github.com/yezz123/fastapi-lazy) - 使用 FastAPI 启动项目的惰性包.
- [FastAPI Limiter](https://github.com/long2ice/fastapi-limiter) - FastAPI 的请求速率限制器.
- [FastAPI MQTT](https://github.com/sabuhish/fastapi-mqtt) - MQTT 协议的扩展.
- [FastAPI Opentracing](https://github.com/wesdu/fastapi-opentracing) - FastAPI 的 Opentracing 中间件和数据库跟踪支持.
- [FastAPI Pagination](https://github.com/uriyyo/fastapi-pagination) - FastAPI 的分页.
- [FastAPI Plugins](https://github.com/madkote/fastapi-plugins) - Redis 和调度程序插件.
- [FastAPI ServiceUtils](https://github.com/skallfass/fastapi_serviceutils) - 用于创建 API 服务的生成器.
- [FastAPI SocketIO](https://github.com/pyropy/fastapi-socketio) - FastAPI 和 SocketIO 的轻松集成.
- [FastAPI Utilities](https://github.com/dmontagu/fastapi-utils) - 可重用实用程序：基于类的视图、响应推断路由器、定期任务、定时中间件、SQLAlchemy 会话、OpenAPI 规范简化.
- [FastAPI Websocket Pub/Sub](https://github.com/authorizon/fastapi_websocket_pubsub) - 经典的发布/订阅模式可以通过网络和跨云实时轻松访问和扩展.
- [FastAPI Websocket RPC](https://github.com/authorizon/fastapi_websocket_rpc) - 通过 Websockets 的 RPC（双向 JSON RPC）变得简单、强大且可用于生产.
- [OpenTelemetry FastAPI Instrumentation](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation/opentelemetry-instrumentation-fastapi) - 库提供 FastAPI Web 框架的自动和手动检测，检测由使用该框架的应用程序提供的 http 请求.
- [Prerender Python Starlette](https://github.com/BeeMyDesk/prerender-python-starlette) - 用于预渲染的 Starlette 中间件.
- [Prometheus FastAPI Instrumentator](https://github.com/trallnag/prometheus-fastapi-instrumentator) - 适用于 FastAPI 应用程序的可配置和模块化 Prometheus Instrumentator.
- [SlowApi](https://github.com/laurents/slowapi) - 速率限制器（基于 [Flask-Limiter](https://flask-limiter.readthedocs.io)).
- [Starlette Context](https://github.com/tomwojcik/starlette-context) - 允许您在项目中的任何位置存储和访问请求数据，这对于记录很有用.
- [Starlette Exporter](https://github.com/stephenhillier/starlette_exporter) - FastAPI 和 Starlette 的又一个普罗米修斯集成.
- [Starlette OpenTracing](https://github.com/acidjunk/starlette-opentracing) - 对 Starlette 和 FastAPI 的 Opentracing 支持.
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) - FastAPI 和 Starlette 的 Prometheus 集成.
- [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) - 基于数据类的 Python GraphQL 库.

## Resources

### Official Resources

- [Documentation](https://fastapi.tiangolo.com/) - 全面的文档.
- [Tutorial](https://fastapi.tiangolo.com/tutorial/) - 官方教程向您展示如何逐步使用 FastAPI 及其大部分功能.
- [Source Code](https://github.com/tiangolo/fastapi) - 托管在 GitHub 上.
- [Discord](https://discord.com/invite/VQjSZaeJmf) - 与其他 FastAPI 用户聊天.

### External Resources

- [TestDriven.io FastAPI](https://testdriven.io/blog/topics/fastapi/) - 多篇特定于 FastAPI 的文章，重点关注开发和测试生产就绪的 RESTful API、提供机器学习模型等.

### Podcasts

- [Build The Next Generation Of Python Web Applications With FastAPI](https://www.pythonpodcast.com/fastapi-web-application-framework-episode-259/) - 在这一集中 [Podcast Init](https://www.pythonpodcast.com/)，FastAPI的创建， [Sebastián Ramirez](https://tiangolo.com/)，分享了他构建 FastAPI 的动机以及它的幕后工作原理.
- [FastAPI on PythonBytes](https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855) - 很好的项目概述.

### Articles

- [FastAPI has Ruined Flask Forever for Me](https://towardsdatascience.com/fastapi-has-ruined-flask-forever-for-me-73916127da)
- [Why we switched from Flask to FastAPI for production machine learning](https://medium.com/@calebkaiser/why-we-switched-from-flask-to-fastapi-for-production-machine-learning-765aab9b3679) - In-depth look at why you may want to move from Flask to FastAPI.

### Tutorials

- [Async SQLAlchemy with FastAPI](https://stribny.name/blog/fastapi-asyncalchemy/) - 了解如何异步使用 SQLAlchemy.
- [Build and Secure an API in Python with FastAPI](https://blog.yezz.me/blog/Build-and-Secure-an-API-in-Python-with-FastAPI) - 保护和维护基于 FastAPI 和 SQLAlchemy 的 API.
- [Deploy a Dockerized FastAPI App to Google Cloud Platform](https://towardsdatascience.com/deploy-a-dockerized-fastapi-app-to-google-cloud-platform-24f72266c7ef) - 使用 Cloud Run 和 SQL 实例将 Dockerized Python 应用程序部署到 Google Cloud Platform 的简短指南.
- [Deploy Machine Learning Models with Keras, FastAPI, Redis and Docker](https://medium.com/analytics-vidhya/deploy-machine-learning-models-with-keras-fastapi-redis-and-docker-4940df614ece)
- [Deploying Iris Classifications with FastAPI and Docker](https://towardsdatascience.com/deploying-iris-classifications-with-fastapi-and-docker-7c9b83fdec3a) - Docker 化 FastAPI 应用程序.
- [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - 使用测试驱动开发，使用 FastAPI、Postgres、Pytest 和 Docker 开发和测试异步 API.
- [FastAPI for Flask Users](https://amitness.com/2020/06/fastapi-vs-flask/) - 通过与 Flask 的并排代码比较来学习 FastAPI.
- [FastAPI Microservice Patterns](https://python.plainenglish.io/fastapi-microservice-patterns-3052c1241019) - 博客文章系列，其中包含微服务模式的示例性实现.
  - [Local Development Environment](https://python.plainenglish.io/fastapi-microservice-patterns-local-development-environment-12182e786f1c) - 简而言之，Skaffold、docker、kubectl 和 minikube.
  - [Service discovery in Container Orchestration Platforms](https://python.plainenglish.io/fastapi-microservice-patterns-service-discovery-in-container-orchestration-platforms-290c00d1ad8) - 解释了在 Kubernetes 中启用 FastAPI 服务通信.
  - [Asynchronous Communication](https://python.plainenglish.io/fastapi-microservice-patterns-asynchronous-communication-45a3b68f8bb8) - 通过消息传递启用松散耦合的服务.
  - [Application Monitoring](https://python.plainenglish.io/fastapi-microservice-patterns-application-monitoring-49fcb7341d9a) - 使用 Prometheus 和 Grafana 进行应用程序指标监控.
  - [Serverless Deployment](https://python.plainenglish.io/fastapi-microservice-serverless-deployment-41a6d21e5cb3) - 关于FastAPI与Kubernetes原生FaaS平台的兼容性现状.
- [Getting started with GraphQL in Python with FastAPI and Ariadne](https://blog.yezz.me/blog/Getting-started-with-GraphQL-in-Python-with-FastAPI-and-Ariadne) - 使用 FastAPI、GraphQL 和 Ariadne 生成 FullStack 游乐场.
- [Implementing FastAPI Services – Abstraction and Separation of Concerns](https://camillovisini.com/article/abstracting-fastapi-services/) - FastAPI 应用程序和服务结构，实现更易于维护的代码库.
- [Introducing FARM Stack - FastAPI, React, and MongoDB](https://www.mongodb.com/developer/languages/python/farm-stack-fastapi-react-mongodb/) - 开始使用完整的 FastAPI Web 应用程序堆栈.
- [Multitenancy with FastAPI, SQLAlchemy and PostgreSQL](https://mergeboard.com/blog/6-multitenancy-fastapi-sqlalchemy-postgresql/) - 了解如何使 FastAPI 应用程序做好多租户准备.
- [Porting Flask to FastAPI for ML Model Serving](https://www.pluralsight.com/tech-blog/porting-flask-to-fastapi-for-ml-model-serving/) - Flask 与 FastAPI 的比较.
- [Real-time data streaming using FastAPI and WebSockets](https://stribny.name/blog/2020/07/real-time-data-streaming-using-fastapi-and-websockets/) - 了解如何将 FastAPI 中的数据直接传输到实时图表中.
- [Running FastAPI applications in production](https://stribny.name/blog/fastapi-production/) - 将 Gunicorn 与 systemd 结合使用进行生产部署.
- [Serving Machine Learning Models with FastAPI in Python](https://medium.com/@8B_EC/tutorial-serving-machine-learning-models-with-fastapi-in-python-c1a27319c459) - 使用 FastAPI 作为 RESTful API 快速轻松地部署和服务 Python 中的机器学习模型.
- [Streaming video with FastAPI](https://stribny.name/blog/fastapi-video/) - 了解如何提供视频流.
- [Using Hypothesis and Schemathesis to Test FastAPI](https://testdriven.io/blog/fastapi-hypothesis/) - 将基于属性的测试应用于 FastAPI.

### Talks

- [PyConBY 2020: Serve ML models easily with FastAPI](https://www.youtube.com/watch?v=z9K5pwb0rt8) - 从 Sebastian Ramirez 的演讲中，您将了解如何使用 FastAPI 轻松为您的 ML 模型构建生产就绪的 Web (JSON) API，包括默认的最佳实践.
- [PyCon UK 2019: FastAPI from the ground up](https://www.youtube.com/watch?v=3DLwPcrE5mA) - 本次演讲展示了如何使用 FastAPI 从头开始​​为数据库构建简单的 REST API.

### Videos

- [Building a Stock Screener with FastAPI](https://www.youtube.com/watch?v=5GorMC2lPpk) - 当您使用 FastAPI 构建基于 Web 的股票筛选器时，您将了解 FastAPI 的许多功能，包括 Pydantic 模型、依赖项注入、后台任务和 SQLAlchemy 集成.
- [Building Web APIs Using FastAPI](https://www.youtube.com/watch?v=Pe66M8mn-wA) - 使用FastAPI构建Web应用程序编程接口（RESTful API）.
- [FastAPI - A Web Framework for Python](https://www.youtube.com/watch?v=PUhio8CprhI&list=PL5gdMNl42qynpY-o43Jk3evfxEKSts3HS) - 了解如何使用 FastAPI 进行数字验证.
- [FastAPI vs. Django vs. Flask](https://www.youtube.com/watch?v=9YBAOYQOzWs)  - 2020 年哪个框架最适合 Python？ 哪个使用 async/await 最好？ 哪个最快？
- [Serving Machine Learning Models As API with FastAPI](https://www.youtube.com/watch?v=mkDxuRvKUL8) - 使用 FastAPI 构建机器学习 API.

### Courses

- [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) - 了解如何使用 Python、FastAPI 和 Docker 构建、测试和部署文本摘要微服务.
- [Modern APIs with FastAPI and Python](https://training.talkpython.fm/courses/getting-started-with-fastapi) - 旨在让您使用 FastAPI 快速创建在云中运行的新 API 的课程.
- [Full Web Apps with FastAPI Course](https://training.talkpython.fm/courses/full-html-web-applications-with-fastapi) - 您将学习使用 FastAPI 构建完整的 Web 应用程序，相当于使用 Flask 或 Django 所做的事情.
- [The Definitive Guide to Celery and FastAPI](https://testdriven.io/courses/fastapi-celery/) - 了解如何将 Celery 添加到 FastAPI 应用程序以提供异步任务处理.

### Best Practices

- [FastAPI Best Practices](https://github.com/zhanymkanov/fastapi-best-practices) - GitHub 存储库中的最佳实践集合.

## Hosting

### PaaS

(Platforms-as-a-Service)

- [Heroku](https://www.heroku.com/) ([Step-by-step tutorial](https://tutlinks.com/create-and-deploy-fastapi-app-to-heroku/), [ML model on Heroku tutorial](https://testdriven.io/blog/fastapi-machine-learning/))
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [Google App Engine](https://cloud.google.com/appengine/)
- [Microsoft Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)
- [Deta](https://www.deta.sh/) ([example](https://dev.to/athulcajay/fastapi-deta-ni5))

### IaaS

(Infrastructure-as-a-Service)

- [AWS EC2](https://aws.amazon.com/ec2/)
- [Google Compute Engine](https://cloud.google.com/compute/)
- [Digital Ocean](https://www.digitalocean.com/)
- [Linode](https://www.linode.com/)

### Serverless

Frameworks:

- [Chalice](https://github.com/aws/chalice)
- [Mangum](https://mangum.io/) - 用于使用 AWS Lambda 和 API Gateway 运行 ASGI 应用程序的适配器.
- [Vercel](https://vercel.com/) -（以前的时间）（[example](https://github.com/Snailedlt/Markdown-Videos)).

Compute:

- [AWS Lambda](https://aws.amazon.com/lambda/) ([example](https://github.com/iwpnd/fastapi-aws-lambda-example))
- [Google Cloud Functions](https://cloud.google.com/functions/)
- [Azure Functions](https://azure.microsoft.com/en-us/products/functions/)
- [Google Cloud Run](https://cloud.google.com/run) ([example](https://github.com/anthonycorletti/cloudrun-fastapi))

## Projects

### Boilerplate

- [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) - 全栈、现代 Web 应用程序生成器，包括 FastAPI、PostgreSQL、Docker、Celery、Vue 前端、自动 HTTPS 等（由 FastAPI 的创建者开发， [Sebastián Ramírez](https://github.com/tiangolo)).
- [FastAPI and Tortoise ORM](https://github.com/prostomarkeloff/fastapi-tortoise) - 强大但简单的 Web API 模板，带有 FastAPI（作为 Web 框架）和 Tortoise-ORM（通过数据库轻松工作）.
- [FastAPI Model Server Skeleton](https://github.com/eightBEC/fastapi-ml-skeleton) - 为机器学习模型提供生产就绪的骨架应用程序.
- [cookiecutter-spacy-fastapi](https://github.com/microsoft/cookiecutter-spacy-fastapi) - 使用 FastAPI 快速部署 spaCy 模型.
- [cookiecutter-fastapi](https://github.com/arthurhenrique/cookiecutter-fastapi) - FastAPI 项目的 Cookiecutter 模板使用：机器学习、Poetry、Azure Pipelines 和 pytest.
- [openapi-python-client](https://github.com/openapi-generators/openapi-python-client) - 从 OpenAPI 生成现代 FastAPI Python 客户端（通过 FastAPI）.
- [Pywork](https://github.com/vutran1710/YeomanPywork) - [Yeoman](https://yeoman.io/) 用于构建 FastAPI 应用程序的生成器.
- [fastapi-gino-arq-uvicorn](https://github.com/leosussan/fastapi-gino-arq-uvicorn)  - Python 中的高性能异步 REST API 模板.  FastAPI + GINO + Arq + Uvicorn（带 Redis 和 PostgreSQL）.
- [FastAPI and React Template](https://github.com/Buuntu/fastapi-react) - 使用 FastAPI、TypeScript、Docker、PostgreSQL 和 React 的全栈 cookiecutter 样板.
- [FastAPI Nano](https://github.com/rednafi/fastapi-nano) - 具有工厂模式架构的简单 FastAPI 模板.
- [FastAPI template](https://github.com/s3rius/FastAPI-template)  - 灵活、轻量级的 FastAPI 项目生成器. 它包括对 SQLAlchemy、多个数据库、CI/CD、Docker 和 Kubernetes 的支持.
- [FastAPI on Google Cloud Run](https://github.com/anthonycorletti/cloudrun-fastapi) - 使用 FastAPI、SQLModel 和 Google Cloud Run 构建 API 的样板.
- [FastAPI with Firestore](https://github.com/anthonycorletti/firestore-fastapi) - 使用 FastAPI 和 Google Cloud Firestore 构建 API 的样板.
- [fastapi-alembic-sqlmodel-async](https://github.com/jonra1993/fastapi-alembic-sqlmodel-async) - 这是一个使用 FastAPI、Alembic 和异步 SQLModel 作为 ORM 的项目模板.
- [fastapi-starter-project](https://github.com/mirzadelic/fastapi-starter-project) - 使用 FastAPI、SQLModel、Alembic、Pytest、Docker、GitHub Actions CI 的项目模板.

### Docker Images

- [inboard](https://github.com/br3ndonland/inboard) - Docker 镜像为您的 FastAPI 应用程序提供支持并帮助您更快地交付.
- [uvicorn-gunicorn-fastapi-docker](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - 由 Gunicorn 管理的带有 Uvicorn 的 Docker 镜像，用于 Python 3.7 和 3.6 中的高性能 FastAPI Web 应用程序，并具有性能自动调整功能.
- [uvicorn-gunicorn-poetry](https://github.com/max-pfeiffer/uvicorn-gunicorn-poetry)  - 此 Docker 映像提供了一个使用 Gunicorn 和 Uvicorn 工作人员运行 FastAPI 的平台. 它提供了 Poetry 来管理依赖关系并在容器中设置虚拟环境.
- [uvicorn-poetry](https://github.com/max-pfeiffer/uvicorn-poetry)  - 此 Docker 镜像提供了一个在 Kubernetes 容器编排系统上使用 Uvicorn 运行 FastAPI 的平台. 它提供了 Poetry 来管理依赖关系并在容器中设置虚拟环境.

### Open Source Projects

- [Astrobase](https://github.com/anthonycorletti/astrobase) - 随时随地简单、快速、安全的部署.
- [Awesome FastAPI Projects](https://github.com/Kludex/awesome-fastapi-projects) - 使用 FastAPI 的项目的组织列表.
- [Bitcart](https://github.com/bitcart/bitcart) - 为商家、用户和开发人员提供轻松设置和使用的平台.
- [Bali](https://github.com/bali-framework/bali) - 基于FastAPI和gRPC简化云原生微服务开发.
- [Bunnybook](https://github.com/pietrobassi/bunnybook) - 使用 FastAPI、React+RxJs、Neo4j、PostgreSQL 和 Redis 构建的小型社交网络.
- [Coronavirus-tg-api](https://github.com/egbakou/coronavirus-tg-api) - 用于跟踪全球冠状病毒（COVID-19、SARS-CoV-2）爆发的 API.
- [Dispatch](https://github.com/Netflix/dispatch) - 管理安全事件.
- FastAPI CRUD 示例：
  - [Async flavor](https://github.com/testdrivenio/fastapi-crud-async)
  - [Sync Flavor](https://github.com/testdrivenio/fastapi-crud-sync)
- [FastAPI with Observability](https://github.com/Blueswen/fastapi-observability) - 通过 OpenTelemetry 和 OpenMetrics 在 Grafana 上观察具有可观测性三大支柱的 FastAPI 应用程序：跟踪 (Tempo)、指标 (Prometheus)、日志 (Loki).
- [DogeAPI](https://github.com/yezz123/DogeAPI) - 具有高性能的 API，可使用 OAuth2PasswordBearer 创建简单的博客和 CRUD.
- [FastAPI Websocket Broadcast](https://github.com/kthwaite/fastapi-websocket-broadcast) - Websocket“广播”演示.
- [FastAPI with Celery, RabbitMQ, and Redis](https://github.com/GregaVrbancic/fastapi-celery) - 利用 FastAPI 和 Celery 以及 RabbitMQ 作为任务队列、Redis 作为 Celery 后端以及 Flower 来监控 Celery 任务的最小示例.
- [JeffQL](https://github.com/yezz123/JeffQL/) - 使用 GraphQL 和 JWT 的简单身份验证和登录 API.
- [JSON-RPC Server](https://github.com/smagafurov/fastapi-jsonrpc) - 基于 FastAPI 的 JSON-RPC 服务器.
- [Mailer](https://github.com/rclement/mailer) - 用于静态网站的极其简单的邮件程序微服务.
- [Markdown-Videos](https://github.com/Snailedlt/Markdown-Videos) - 用于生成缩略图以嵌入到您的 Markdown 内容中的 API.
- [Nemo](https://github.com/harshitsinghai77/nemo-backend) - 与 Nemo 一起提高工作效率.
- [OPAL (Open Policy Administration Layer)](https://github.com/authorizon/opal)  - 基于开放策略的实时授权更新； 使用 FastAPI、Typer 和 FastAPI WebSocket pub/sub 构建.
- [RealWorld Example App - mongo](https://github.com/markqiu/fastapi-mongodb-realworld-example-app)
- [RealWorld Example App - postgres](https://github.com/nsidnev/fastapi-realworld-example-app)
- [redis-streams-fastapi-chat](https://github.com/leonh/redis-streams-fastapi-chat) - 一个简单的 Redis Streams 支持的聊天应用程序，使用 Websockets、Asyncio 和 FastAPI/Starlette.
- [Sprites as a service](https://github.com/ljvmiranda921/sprites-as-a-service) - 使用元胞自动机生成您的个人 8 位头像.
- [Slackers](https://github.com/uhavin/slackers) - Slack webhooks API.
- [TermPair](https://github.com/cs01/termpair) - 通过端到端加密从浏览器查看和控制终端.
- [Universities](https://github.com/ycd/universities) - 用于获取全球超过 9600 所大学信息的 API 服务.

## Sponsors

请查看我们的赞助商来支持这个开源项目：

<a href="https://www.deta.sh/?ref=awesome-fastapi" target="_blank" title="The launchpad for all your (team's) ideas"><img src="https://raw.githubusercontent.com/mjhea0/awesome-fastapi/master/images/deta.svg?sanitize=true"></a>

<a href="https://testdriven.io/courses/tdd-fastapi/?ref=awesome-fastapi" target="_blank" title="Learn to build high-quality web apps with best practices"><img src="https://raw.githubusercontent.com/mjhea0/awesome-fastapi/master/images/testdriven.svg?sanitize=true"></a>
