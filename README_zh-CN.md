# free-for.dev

开发者和开源作者现在有许多服务提供免费套餐，但要找到所有这些服务并做出明智的决定需要花费时间。

这是一份包含免费开发者套餐的软件（软件即服务、平台即服务、基础设施即服务等）和其他产品的列表。

这份特定列表的范围仅限于基础设施开发者（系统管理员、DevOps 从业者等）可能觉得有用的东西。我们喜欢所有的免费服务，但最好保持主题相关。这有时是一个灰色地带，所以这是主观的；如果我不接受您的贡献，请不要感到被冒犯。

这份列表是 1600 多人通过合并请求、审查、想法和工作成果汇集而成的。您也可以通过发送 [合并请求](https://github.com/ripienaar/free-for-dev) 来帮助添加更多服务，或移除那些产品已变更或已停止服务的项目。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**：此列表仅适用于“即服务”产品，不适用于自托管软件。要符合资格，服务必须提供免费套餐，而不仅仅是免费试用。如果是有时限的，免费套餐必须至少持续一年。我们也会从安全角度考虑免费套餐，所以 SSO 是可以的，但我不会接受将 TLS 限制为仅付费套餐的服务。

# 目录

  * [主要云提供商的永久免费额度](#主要云提供商)
  * [云管理解决方案](#云管理解决方案)
  * [分析、事件和统计](#分析事件和统计)
  * [API、数据和机器学习](#api数据和机器学习)
  * [制品仓库](#制品仓库)
  * [后端即服务 (BaaS)](#后端即服务-baas)
  * [低代码平台](#低代码平台)
  * [CDN 和保护](#cdn-和保护)
  * [持续集成和持续交付 (CI/CD)](#持续集成和持续交付-cicd)
  * [内容管理系统 (CMS)](#内容管理系统-cms)
  * [代码生成](#代码生成)
  * [代码质量](#代码质量)
  * [代码搜索和浏览](#代码搜索和浏览)
  * [崩溃和异常处理](#崩溃和异常处理)
  * [地图上的数据可视化](#地图上的数据可视化)
  * [托管数据服务](#托管数据服务)
  * [设计和 UI](#设计和-ui)
  * [设计灵感](#设计灵感)
  * [开发者博客网站](#开发者博客网站)
  * [DNS](#dns)
  * [Docker 相关](#docker-相关)
  * [域名](#域名)
  * [教育和职业发展](#教育和职业发展)
  * [电子邮件](#电子邮件)
  * [功能开关管理平台](#功能开关管理平台)
  * [字体](#字体)
  * [表单](#表单)
  * [生成式 AI](#生成式-ai)
  * [基础设施即服务 (IaaS)](#基础设施即服务-iaas)
  * [IDE 和代码编辑](#ide-和代码编辑)
  * [国际手机号码验证 API 和 SDK](#国际手机号码验证-api-和-sdk)
  * [问题跟踪和项目管理](#问题跟踪和项目管理)
  * [日志管理](#日志管理)
  * [移动应用分发和反馈](#移动应用分发和反馈)
  * [管理系统](#管理系统)
  * [消息和流媒体](#消息和流媒体)
  * [杂项](#杂项)
  * [监控](#监控)
  * [平台即服务 (PaaS)](#平台即服务-paas)
  * [包构建系统](#包构建系统)
  * [支付和账单集成](#支付和账单集成)
  * [隐私管理](#隐私管理)
  * [截图 API](#截图-api)
  * [Flutter 相关及无 Mac 构建 IOS 应用](#flutter-相关及无-mac-构建-ios-应用)
  * [搜索](#搜索)
  * [安全和 PKI](#安全和-pki)
  * [认证、授权和用户管理](#认证授权和用户管理)
  * [源代码仓库](#源代码仓库)
  * [存储和媒体处理](#存储和媒体处理)
  * [隧道、WebRTC、Web Socket 服务器和其他路由器](#隧道webrtcweb-socket-服务器和其他路由器)
  * [测试](#测试)
  * [团队和协作工具](#团队和协作工具)
  * [翻译管理](#翻译管理)
  * [Vagrant 相关](#vagrant-相关)
  * [访客会话录制](#访客会话录制)
  * [Web 托管](#web-托管)
  * [评论平台](#评论平台)
  * [基于浏览器的硬件仿真](#基于浏览器的硬件仿真)
  * [远程桌面工具](#远程桌面工具)
  * [游戏开发](#游戏开发)
  * [其他免费资源](#其他免费资源)

## 主要云提供商

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，9 个后端实例小时
    * Cloud Firestore - 1GB 存储，每天 50,000 次读取，20,000 次写入，20,000 次删除
    * Compute Engine - 1 个非抢占式 e2-micro 实例，30GB HDD，5GB 快照存储（仅限特定区域），每月从北美到所有区域目的地（不包括中国和澳大利亚）的 1 GB 网络流出
    * Cloud Storage - 5GB 存储，1GB 网络流出
    * Cloud Shell - 基于 Web 的 Linux Shell/主 IDE，具有 5GB 持久存储。每周 60 小时限制
    * Cloud Pub/Sub - 每月 10GB 消息
    * Cloud Functions - 每月 200 万次调用（包括后台和 HTTP 调用）
    * Cloud Run - 每月 200 万次请求，360,000 GB-秒内存，180,000 vCPU-秒计算时间，每月从北美流出 1 GB 网络流量
    * Google Kubernetes Engine - 一个区域集群无集群管理费。每个用户节点按标准 Compute Engine 定价收费
    * BigQuery - 每月 1 TB 查询，每月 10 GB 存储
    * Cloud Build - 每天 120 分钟构建时间
    * Cloud Source Repositories - 最多 5 个用户，50 GB 存储，50 GB 流出
    * [Google Colab](https://colab.research.google.com/) - 免费 Jupyter Notebooks 开发环境。
    * [Firebase Studio](https://firebase.studio) Google Firebase Studio (前身为 Project IDX)。运行在 Google Cloud 上的在线 VSCode。
    * 完整详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 流出和每月 200 万次函数调用
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标和 10 个警报
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分钟构建时间
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 个活跃用户，50GB 存储，每月 10000 次请求
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 个活跃管道
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
    * [EC2](https://aws.amazon.com/ec2/) - 每月 750 小时 t2.micro 或 t3.micro (12个月)。每月 100GB 流出
    * [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用 (SSD) 或 磁性存储 (12个月)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 每月 750 小时 (12个月)
    * [RDS](https://aws.amazon.com/rds/) - 每月 750 小时 db.t2.micro、db.t3.micro 或 db.t4g.micro，20GB 通用 (SSD) 存储，20GB 存储备份 (12个月)
    * [S3](https://aws.amazon.com/s3/) - 5GB 标准对象存储，20,000 次 Get 请求和 2,000 次 Put 请求 (12个月)
    * [Glacier](https://aws.amazon.com/glacier/) - 10GB 长期对象存储
    * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 万次请求
    * [SNS](https://aws.amazon.com/sns/) - 每月 100 万次发布
    * [SES](https://aws.amazon.com/ses/) - 每月 3,000 条消息 (12个月)
    * [SQS](https://aws.amazon.com/sqs/) - 100 万次消息队列请求
    * 完整详细列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux VM，1 个 B1S Windows VM (12个月)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个 Web、移动或 API 应用 (每天 60 CPU 分钟)
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万次请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 启用快速、简单和精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月 50,000 个存储用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限私有 Git 仓库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费并行作业，Linux、macOS 和 Windows 开源项目无限分钟数
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费公共负载均衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万次推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 15GB 流入 (12个月) & 5GB 流出
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB 存储和 1000 RU 的预置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — 构建、部署和托管静态应用和无服务器函数，包含免费 SSL、认证/授权和自定义域名
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储 (12个月)
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译器、人脸检测、机器人等），免费套餐包含有限交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于 AI 的搜索和索引服务，免费 10,000 个文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管 Kubernetes 服务，免费集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 每月 100,000 次操作
    * 完整详细列表 - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算
       - 2 个基于 AMD 的计算 VM，每个具有 1/8 OCPU 和 1 GB 内存
       - 4 个基于 Arm 的 Ampere A1 核心和 24 GB 内存，可用作一个 VM 或最多 4 个 VM
       - 当[被视为闲置](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)时，实例将被回收
    * 块卷 - 2 个卷，总计 200 GB（用于计算）
    * 对象存储 - 10 GB
    * 负载均衡器 - 1 个实例，10 Mbps
    * 数据库 - 2 个数据库，每个 20 GB
    * 监控 - 5 亿个摄取数据点，10 亿个检索数据点
    * 带宽 - 每月 10 TB 流出，x64 架构 VM 限速 50 Mbps，ARM 架构 VM 限速 500 Mbps * 核心数
    * 公共 IP - VM 2 个 IPv4，负载均衡器 1 个 IPv4
    * 通知 - 每月 100 万次交付选项，每月发送 1000 封电子邮件
    * 完整详细列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudant 数据库 - 1 GB 数据存储
    * Db2 数据库 - 100MB 数据存储
    * API Connect - 每月 50,000 次 API 调用
    * Availability Monitoring - 每月 300 万个数据点
    * Log Analysis - 500MB 日志/天
    * 完整详细列表 - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - 无限域名的免费 DNS，DDoS 保护，CDN 以及免费 SSL，防火墙规则和页面规则，WAF，机器人缓解，免费不计量速率限制 - 每个域名 1 条规则，分析，电子邮件转发
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 个用户，24 小时活动日志记录，三个网络位置
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 您可以通过隧道将本地运行的 HTTP 端口暴露给 trycloudflare.com 上的随机子域，使用 [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)，无需帐户。更多功能（TCP 隧道、负载均衡、VPN）在 [Zero Trust](https://www.cloudflare.com/products/zero-trust/) 免费计划中。
    * [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 的全球网络上免费部署无服务器代码——每天 10 万次请求。
    * [Workers KV](https://developers.cloudflare.com/kv) - 每天 10 万次读取请求，每天 1000 次写入请求，每天 1000 次删除请求，每天 1000 次列表请求，1 GB 存储数据
    * [R2](https://developers.cloudflare.com/r2/) - 每月 10 GB，每月 100 万次 A 类操作，每月 1000 万次 B 类操作
    * [D1](https://developers.cloudflare.com/d1/) - 每天 500 万行读取，每天 10 万行写入，1 GB 存储
    * [Pages](https://developers.cloudflare.com/pages/) - 在 Cloudflare 快速、安全的全球网络上开发和部署您的 Web 应用程序。每月 500 次构建，100 个自定义域名，集成 SSL，无限访问席位，无限预览部署，以及通过 Cloudflare Workers 集成的全栈能力。
    * [Queues](https://developers.cloudflare.com/queues/) - 每月 100 万次操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) – 每月 1TB 免费（流出）流量。

**[⬆️ 回到顶部](#目录)**

## 云管理解决方案

  * [Brainboard](https://www.brainboard.co) - 协同解决方案，用于从端到端可视化构建和管理云基础设施。
  * [Cloud 66](https://www.cloud66.com/) - 个人项目免费（包括一个部署服务器，一个静态站点），Cloud 66 为您提供在任何云上构建、部署和扩展应用程序所需的一切，而无需为“服务器事务”头疼。
  * [Pulumi](https://www.pulumi.com/) — 现代基础设施即代码平台，允许您使用熟悉的编程语言和工具来构建、部署和管理云基础设施。
  * [terraform.io](https://www.terraform.io/) — Terraform Cloud。免费远程状态管理和团队协作，最多 500 个资源。
  * [scalr.com](https://scalr.com/) - Scalr 是一个 Terraform 自动化和协作 (TACO) 产品，用于更好地协作和自动化由 Terraform 管理的基础设施和配置。完整的 Terraform CLI 支持，OPA 集成和分层配置模型。无 SSO 税。包含所有功能。每月免费使用最多 50 次运行。
  * [deployment.io](https://deployment.io) - Deployment.io 帮助开发者自动化 AWS 上的部署。在我们的免费套餐中，开发者（单个用户）可以部署无限的静态站点、Web 服务和环境。我们每月免费提供 20 次作业执行，免费套餐中包含预览和自动部署。

**[⬆️ 回到顶部](#目录)**

## 源代码仓库

  * [Bitbucket](https://bitbucket.org/) — 最多 5 个用户的无限公共和私有 Git 仓库，带有用于 CI/CD 的 Pipelines
  * [chiselapp.com](https://chiselapp.com/) — 无限公共和私有 Fossil 仓库
  * [codebasehq.com](https://www.codebasehq.com/) — 一个免费项目，100 MB 空间和两个用户
  * [Codeberg](https://codeberg.org/) — 免费和开源项目的无限公共和私有 Git 仓库（无限协作者）。由 [Forgejo](https://forgejo.org/) 提供支持。使用 [Codeberg Pages](https://codeberg.page/) 进行静态网站托管。使用 [Codeberg's CI](https://docs.codeberg.org/ci/) 进行 CI/CD 托管。使用 [Codeberg Translate](https://translate.codeberg.org/) 进行翻译托管。包括包和容器托管、项目管理和问题跟踪
  * [GitGud](https://gitgud.io) — 无限私有和公共仓库。永久免费。由 GitLab & Sapphire 提供支持。不提供 CI/CD。
  * [GitHub](https://github.com/) — 无限公共仓库和无限私有仓库（无限协作者）。包括 CI/CD、开发环境、静态托管、包和容器托管、项目管理和 AI Copilot
  * [gitlab.com](https://about.gitlab.com/) — 无限公共和私有 Git 仓库，最多 5 个协作者。包括 CI/CD、静态托管、容器注册表、项目管理和问题跟踪
  * [framagit.org](https://framagit.org/) — Framagit 是 Framasoft 基于 Gitlab 软件的软件锻造厂，包括 CI、静态页面、项目页面和问题跟踪。
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的友好分支，提供对 Mercurial 的支持
  * [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 开发应用程序的仓库和工具；您也有一个 ionic 仓库
  * [NotABug](https://notabug.org) — NotABug.org 是一个用于自由许可项目的自由软件代码协作平台，基于 Git
  * [OSDN](https://osdn.net/) - OSDN.net 是面向开源软件开发者的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 仓库。
  * [Pagure.io](https://pagure.io) — Pagure.io 是一个用于 FOSS 许可项目的免费开源软件代码协作平台，基于 Git
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免费 1GB 云和 Git、Mercurial 或 SVN 仓库。
  * [pijul.com](https://pijul.com/) - 无限免费和开源分布式版本控制系统。其独特之处在于基于完善的补丁理论，使其易于学习、使用和分发。解决了 git/hg/svn/darcs 的许多问题。
  * [plasticscm.com](https://plasticscm.com/) — 个人、OSS 和非营利组织免费
  * [projectlocker.com](https://projectlocker.com) — 一个免费私有项目（Git 和 Subversion），50 MB 空间
  * [RocketGit](https://rocketgit.com) — 基于 Git 的仓库托管。无限公共和私有仓库。
  * [savannah.gnu.org](https://savannah.gnu.org/) - 作为自由软件项目（针对 GNU 项目）的协作软件开发管理系统
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为自由软件项目（针对非 GNU 项目）的协作软件开发管理系统

**[⬆️ 回到顶部](#目录)**

## API、数据和机器学习

  * [JSONGrid](https://jsongrid.com) - 免费工具，用于将复杂的 JSON 数据可视化、编辑、过滤为漂亮的表格网格。通过链接保存和共享 JSON 数据。
  * [Zerosheets](https://zerosheets.com) - 将您的 Google Sheets 电子表格转换为强大的 API，以快速开发原型、网站、应用程序等。每月免费提供 500 次请求。
  * [JSON to Table](https://jsontotable.org) - 将 JSON 转换为交互式表格，以便在线快速查看、编辑和共享。
  * [IP.City](https://ip.city) — 每天 100 次免费 IP 地理定位请求
  * [Abstract API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理定位、性别检测或电子邮件验证。
  * [Apify](https://www.apify.com/) — Web 抓取和自动化平台，可为任何网站创建 API 并提取数据。现成的抓取工具、集成代理和自定义解决方案。免费计划每月包含 5 美元的平台积分。
  * [APITemplate.io](https://apitemplate.io) - 使用简单的 API 或 Zapier & Airtable 等自动化工具自动生成图像和 PDF 文档。无需 CSS/HTML。免费计划每月提供 50 张图像和三个模板。
  * [APIToolkit.io](https://apitoolkit.io) - 完全了解 API 和后端发生的情况所需的所有工具。具有自动 API 合约验证和监控功能。免费计划涵盖每天最多 10,000 次请求的服务器。
  * [APIVerve](https://apiverve.com) - 免费即时访问 120 多个 API，以质量、一致性和可靠性为构建理念。免费计划每月涵盖最多 50 个 API 令牌。（可能已下线，2025-06-25）
  * [Arize AI](https://arize.com/) - 用于模型监控和根本原因问题（如数据质量和性能漂移）的机器学习可观测性。最多两个模型免费。
  * [Maxim AI](https://getmaxim.ai/) - 模拟、评估和观察您的 AI 代理。Maxim 是一个端到端的评估和可观测性平台，帮助团队可靠地发布他们的 AI 代理，速度提高 5 倍以上。独立开发者和小型团队（3 个席位）永久免费。
  * [Beeceptor](https://beeceptor.com) - 无代码、基于云的平台，用于模拟和调试多协议 API（REST、SOAP、gRPC 和 GraphQL），提供具有基于规则的逻辑、CRUD 和有状态模拟、代理和 CORS 管理的即时服务器，以实现更快的集成和测试。免费计划包括每天 50 次请求，并提供一个公共仪表板/端点，任何拥有仪表板 URL 的人都可以查看提交的请求和响应。
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确和免费（无限或每月最多 10K-50K）的 API，如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户端信息等。
  * [Browse AI](https://www.browse.ai) — 提取和监控网络上的数据。每月免费 1k 积分，相当于 1k 并发请求。
  * [BrowserCat](https://www.browsercat.com) - 用于自动化、抓取、 AI 代理网络访问、图像/pdf 生成等的无头浏览器 API。免费计划每月 1k 请求。
  * [CarAPI.dev](https://carapi.dev) — 具有 VIN 解码、被盗车辆检查、车辆估值、检查数据等的综合汽车数据 API。免费套餐包括所有 9 个端点的每月 100 次请求。
  * [Calendarific](https://calendarific.com) - 覆盖 200 多个国家的企业级公共假期 API 服务。免费计划包括每月 500 次调用。
  * [Canopy](https://www.canopyapi.co/) - Amazon.com 产品、搜索和类别数据的 GraphQL API。免费计划包括每月 100 次调用。
  * [Clarifai](https://www.clarifai.com) — 用于自定义人脸识别和检测的图像 API。能够训练 AI 模型。免费计划每月 1,000 次调用。
  * [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问扩展的 API 库，包括文档转换、病毒扫描等，每月 600 次调用，仅限北美 AZ，最大文件大小 2.5MB。
  * [Colaboratory](https://colab.research.google.com) — 带有 Nvidia Tesla K80 GPU 的免费基于 Web 的 Python 笔记本环境。
  * [CometML](https://www.comet.com/site/) - 用于实验跟踪、模型生产管理、模型注册和完整数据沿袭的 MLOps 平台，涵盖从训练到生产的工作流程。个人和学术界免费。
  * [Commerce Layer](https://commercelayer.io) - 可组合的商务 API，可以从任何前端构建、下达和管理订单。开发者计划允许每月 100 个订单和最多 1,000 个 SKU 免费。
  * [Composio](https://composio.dev/) - AI 代理和 LLM 的集成平台。集成代理互联网上的 200 多个工具。
  * [Conversion Tools](https://conversiontools.io/) - 文档、图像、视频、音频和电子书的在线文件转换器。提供 REST API。Node.js、PHP、Python 库。支持最大 50 GB 的文件（付费计划）。免费套餐受文件大小（20MB）和转换次数（30/天，300/月）限制。
  * [Country-State-City Microservice API](https://country-state-city.rebuscando.info/) - 提供广泛信息的 API 和微服务，包括国家、地区、省份、城市、邮政编码等。免费套餐包括每天最多 100 次请求。
  * [Coupler](https://www.coupler.io/) - 在应用程序之间同步的数据集成工具。它可以创建实时仪表板和报告，转换和操作值，并收集和备份见解。免费计划仅限于一个用户、数据连接、数据源和数据目的地。还需要手动数据刷新。
  * [CraftMyPDF](https://craftmypdf.com) - 使用拖放编辑器和简单的 API 从可重用模板自动生成 PDF 文档。免费计划每月提供 100 个 PDF 和三个模板。
  * [Crawlbase](https://crawlbase.com/) — 无需代理、基础设施或浏览器即可抓取和刮取网站。我们为您解决验证码并防止您被阻止。前 1000 次调用免费。
  * [CurlHub](https://curlhub.io) — 用于检查和调试 API 调用的代理服务。免费计划包括每月 10,000 次请求。
  * [CurrencyScoop](https://currencyscoop.com) - 金融科技应用程序的实时货币数据 API。免费计划包括每月 5,000 次调用。
  * [CustomJS](https://www.customjs.io) - HTML 转 PDF 或 PDF 转 PNG/文本以及 PDF 合并/提取/合并 API。免费套餐每月 600 次调用。
  * [Cube](https://cube.dev/) - Cube 帮助数据工程师和应用程序开发者访问现代数据存储中的数据，将其组织成一致的定义，并将其交付给每个应用程序。使用 Cube 最快的方法是使用 Cube Cloud，它有一个免费套餐，限制为每天 1,000 次查询。
  * [Data Dead Drop](https://datadeaddrop.com) - 简单、免费的文件共享。数据访问后自毁。通过浏览器或您最喜欢的命令行客户端上传和下载数据。
  * [Data Fetcher](https://datafetcher.com) - 无需代码即可将 Airtable 连接到任何应用程序或 API。类似于 Postman 的界面，用于在 Airtable 中运行 API 请求。与数十个应用程序的预构建集成。免费计划包括每月 100 次运行。
  * [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清理和将数据导入 Salesforce 的工具。免费计划包括每月最多 20,000 条记录。
  * [Datalore](https://datalore.jetbrains.com) - Jetbrains 的 Python 笔记本。每月包括 10 GB 存储空间和 120 小时运行时间。
  * [Data Miner](https://dataminer.io/) - 用于从网页 CSV 或 Excel 提取数据的浏览器扩展（Google Chrome、MS Edge）。免费计划每月为您提供 500 页。
  * [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报告并将 Python 脚本和 Jupyter Notebooks 部署为自助服务的 API。
  * [DB-IP](https://db-ip.com/api/free) - 免费 IP 地理定位 API，每个 IP 每天 1k 请求。CC-BY 4.0 许可下的 lite 数据库也是免费的。
  * [DB Designer](https://www.dbdesigner.net/) — 基于云的数据库模式设计和建模工具，免费入门计划包含 2 个数据库模型和每个模型 10 个表。
  * [DeepAR](https://developer.deepar.ai) — 适用于任何平台的增强现实人脸滤镜，只需一个 SDK。免费计划提供最多 10 个月活跃用户 (MAU) 并跟踪最多 4 张人脸。
  * [Deepnote](https://deepnote.com) - 一个新的数据科学笔记本。Jupyter 兼容实时协作并在云端运行。免费套餐包括无限个人项目、无限基本机器（5GB RAM 和 2vCPU）以及最多 3 名编辑的团队。
  * [Disease.sh](https://disease.sh/) — 提供准确数据以构建 Covid-19 相关有用应用程序的免费 API。
  * [Doczilla](https://www.doczilla.app/) — SaaS API，支持直接从 HTML/CSS/JS 代码生成屏幕截图或 PDF。免费计划允许每月 250 个文档。
  * [Doppio](https://doppio.sh/) — 托管 API，使用顶级渲染技术生成并私密存储 PDF 和屏幕截图。免费计划允许每月 400 个 PDF 和屏幕截图。
  * [drawDB](https://drawdb.app/) — 免费且开源的在线数据库图表编辑器，无需注册。
  * [dreamfactory.com](https://dreamfactory.com/) — 用于移动、Web 和 IoT 应用程序的开源 REST API 后端。连接任何 SQL/NoSQL 数据库、文件存储系统或外部服务，它会立即创建一个具有实时文档和用户管理的综合 REST API 平台。
  * [Duply.co](https://duply.co) — 从 API 和 URL 创建动态图像，设计一次模板并重复使用。免费套餐提供 20 个免费积分。
  * [DynamicDocs](https://advicement.io) - 使用基于 LaTeX 模板的 JSON 转 PDF API 生成 PDF 文档。免费计划允许每月 50 次 API 调用并访问模板库。
  * [Efemarai](https://efemarai.com) - ML 模型和数据的测试和调试平台。可视化任何计算图。免费本地使用。
  * [ERD Lab](https://www.erdlab.io) — 专为开发者打造的免费基于云的实体关系图 (ERD) 工具。免费试用包括 2 个项目，每个项目 10 个表。
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端，用于发送 HTTP 请求。
  * [Export SDK](https://exportsdk.com) - 带有拖放模板编辑器的 PDF 生成器 API，提供 SDK 和无代码集成。免费计划有 250 个月度页面、无限用户和三个模板。
  * [file.coffee](https://file.coffee/) - 一个平台，您可以在其中存储高达 15MB/文件（有帐户则为 30/MB 文件）。
  * [Financial Data](https://financialdata.net/) - 股市和金融数据 API。免费计划允许每天 300 次请求。
  * [FormatJSONOnline.com](https://formatjsononline.com) - 一个免费的、基于浏览器的工具，用于即时格式化、验证、比较和缩小 JSON 数据。
  * [FraudLabs Pro](https://www.fraudlabspro.com) — 筛选订单交易以防信用卡支付欺诈。此 REST API 将根据订单的输入参数检测所有可能的欺诈特征。免费微型计划每月有 500 笔交易。
  * [GeoDataSource](https://www.geodatasource.com) — 位置搜索服务使用经纬度坐标查找城市名称。免费 API 每月查询最多 500 次。
  * [Geolocated.io](https://geolocated.io) — 具有多大陆服务器的 IP 地理定位 API，提供每天 2,000 次请求的免费计划。
  * [Glitterly](https://glitterly.app/) - 以编程方式从基础模板生成动态图像。Restful API 和无代码集成。免费套餐每月提供 50 张图像和五个模板。
  * [Hex](https://hex.tech/) - 用于笔记本、数据应用程序和知识库的协作数据平台。免费社区套餐，最多五个项目。
  * [Hook0](https://www.hook0.com/) - Hook0 是一个开源的 Webhooks 即服务 (WaaS)，使在线产品可以轻松提供 webhook。每天免费分发最多 100 个事件，保留 7 天的历史记录。
  * [Hoppscotch](https://hoppscotch.io) - 一个免费、快速且漂亮的 API 请求构建器。
  * [huggingface.co](https://huggingface.co) - 构建、训练和部署 Pytorch、TensorFlow 和 JAX 的 NLP 模型。每月免费最多 30k 输入字符。
  * [Hybiscus](https://hybiscus.dev/) - 使用简单的声明性 API 构建 pdf 报告。14 天免费套餐包括 50 个单页报告，能够自定义调色板和字体。
  * [Invantive Cloud](https://cloud.invantive.com/) — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，如 Exact Online、Twinfield、ActiveCampaign 或 Visma。包括数据复制和交换。开发者和实施顾问免费计划。特定平台免费，数据量有限制。
  * [ipaddress.sh](https://ipaddress.sh) — 获取不同[格式](https://about.ipaddress.sh/)的公共 IP 地址的简单服务。
  * [ip-api](https://ip-api.com) — IP 地理定位 API，非商业用途免费，无需 API 密钥，免费计划限制为同一 IP 地址每分钟 45 次请求。
  * [ipbase.com](https://ipbase.com) - IP 地理定位 API - 永久免费计划，每月 150 次请求。
  * [IP Geolocation](https://ipgeolocation.io/) — IP 地理定位 API - 开发者永久免费计划，每天 1,000 次请求限制。
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — Abstract 的 IP 地理定位 API - 允许 1,000 次免费请求。
  * [IPLocate](https://www.iplocate.io) — IP 地理定位 API，每天免费最多 1,000 次请求。包括代理/VPN/托管检测、ASN 数据、IP 到公司等。IPLocate 还提供 CSV 或 GeoIP 兼容 MMDB 格式的免费可下载 IP 到国家和 IP 到 ASN 数据库。
  * [IP2Location](https://www.ip2location.com) — 免费增值 IP 地理定位服务。LITE 数据库可免费下载。将数据库导入服务器并执行本地查询以确定城市、坐标和 ISP 信息。
  * [IP2Location.io](https://www.ip2location.io/) — 免费增值、快速且可靠的 IP 地理定位 API。获取城市、坐标、ISP、ASN、AS 数据等数据。免费计划包括每月 50k 积分。IP2Location.io 还提供每月 500 次免费 WHOIS 和托管域查找。查看域注册详细信息并查找托管在特定 IP 上的域。升级到付费计划以获得更多功能。
  * [ipapi](https://ipapi.co/) - Kloudend, Inc 的 IP 地址位置 API - 基于 AWS 构建的可靠地理定位 API，深受财富 500 强信赖。免费套餐提供 30k 查找/月（1k/天），无需注册。
  * [ipapi.is](https://ipapi.is/) - 来自开发者为开发者提供的可靠 IP 地址 API，具有现有的最佳托管检测功能。免费计划提供 1000 次查找，无需注册。
  * [IPinfo](https://ipinfo.io/) — 快速、准确且免费（每月最多 50k）的 IP 地址数据 API。提供有关地理定位、公司、运营商、IP 范围、域、滥用联系人等的详细信息的 API。所有付费 API 均可免费试用。
  * [IPQuery](https://ipquery.io) — 开发者的无限 IP API，无速率限制或定价。
  * [IPTrace](https://iptrace.io) — 一个极其简单的 API，为您的企业提供可靠且有用的 IP 地理定位数据，每月 50,000 次免费查找。
  * [JSON2Video](https://json2video.com) - 一个视频编辑 API，用于以编程方式或无代码自动化视频营销和社交媒体视频。
  * [JSON IP](https://getjsonip.com) — 返回请求它的客户端的公共 IP 地址。免费套餐无需注册。使用 CORS，可以直接从浏览器使用客户端 JS 请求数据。用于监控客户端和服务器 IP 变化的服务。无限请求。
  * [JSON Serve](https://jsonserve.com/) — 一个免费服务，帮助开发者存储 JSON 对象并在他们的应用程序中将该 JSON 用作 REST API。
  * [JSONing](https://jsoning.com/api/) — 从 JSON 对象创建一个虚假的 REST API，并自定义 HTTP 状态代码、标头和响应正文。
  * [JSONSwiss](https://www.jsonswiss.com/) - JSONSwiss 是一个强大的在线 JSON 查看器、编辑器和验证器。使用 AI 驱动的修复、树视图、表视图、12 种以上编程语言的代码生成、将 json 转换为 csv、xml、yaml、properties 等，格式化、可视化、搜索和操作 JSON 数据。
  * [konghq.com](https://konghq.com/) — API 市场和强大的私有和公共 API 工具。在免费套餐中，某些功能（如监控、警报和支持）受到限制。
  * [Kreya](https://kreya.app) — 免费 gRPC GUI 客户端，用于调用和测试 gRPC API。可以通过服务器反射导入 gRPC API。
  * [Lightly](https://www.lightly.ai/) — 通过使用正确的数据改进您的机器学习模型。免费使用最多 1000 个样本的数据集。
  * [LoginLlama](https://loginllama.app) - 一个登录安全 API，用于检测欺诈和可疑登录并通知您的客户。每月 1,000 次登录免费。
  * [MailboxValidator](https://www.mailboxvalidator.com) — 使用真实邮件服务器连接确认有效电子邮件的电子邮件验证服务。免费 API 计划每月有 100 次验证。
  * [Market Data API](https://www.marketdata.app) - 提供股票、期权、共同基金等的实时和历史金融数据。永久免费 API 层允许免费每天 100 次 API 请求。
  * [Meteosource Weather API](https://www.meteosource.com/) — 用于当前和预测天气数据的全球天气 API。预测基于更多天气模型的机器学习组合，以实现更高的准确性。免费计划每天提供 400 次调用。
  * [microlink.io](https://microlink.io/) – 它将任何网站转换为数据，如元标记规范化、美观链接预览、抓取功能或屏幕截图即服务。每天 50 次请求，每天免费。
  * [Mindee](https://developers.mindee.com) – Mindee 是一款功能强大的 OCR 软件和 API 优先平台，通过使用计算机视觉和机器学习识别关键信息的数据来标准化文档处理层，从而帮助开发者自动化应用程序的工作流程。免费套餐每月提供 500 页。
  * [Mintlify](https://mintlify.com) — API 文档的现代标准。美观且易于维护的 UI 组件、应用内搜索和交互式游乐场。1 名编辑免费。
  * [MockAPI](https://www.mockapi.io/) — MockAPI 是一个简单的工具，让您可以快速模拟 API、生成自定义数据并使用 RESTful 接口执行操作。MockAPI 旨在成为原型设计/测试/学习工具。一个项目/每个项目 2 个资源免费。
  * [Mockfly](https://www.mockfly.dev/) — Mockfly 是用于 API 模拟和功能标志管理的值得信赖的开发工具。通过直观的界面快速生成和控制模拟 API。免费套餐提供每天 500 次请求。
  * [Mocki](https://mocki.io) - 一个工具，让您可以创建同步到 GitHub 仓库的模拟 GraphQL 和 REST API。简单的 REST API 无需注册即可免费开发和使用。
  * [Mocko.dev](https://mocko.dev/) — 代理您的 API，选择要在云中模拟的端点并检查流量，免费。加快您的开发和集成测试。
  * [Mocky](https://designer.mocky.io/) - 一个简单的 Web 应用程序，用于生成自定义 HTTP 响应以模拟 HTTP 请求。也可作为 [开源](https://github.com/julien-lafont/Mocky) 使用。
  * [Mock N Roll](https://mocknroll.me/) - 免费模拟 API 服务——一个强大的工具，可以模拟真实的 API 响应而没有后端延迟。非常适合前端开发者、QA 测试人员和 DevOps 团队。[repo](https://github.com/haerulmuttaqin/mocknroll-web)。
  * [microenv.com](https://microenv.com) — 为开发者创建虚假 REST API，并可能在 docker 容器中生成代码和应用程序。
  * [Multi-Exit IP Address Checker](https://ip.alstra.ca/) — 一个免费且简单的工具，用于检查您在多个节点上的出口 IP 地址，并了解您的 IP 在不同全球区域和服务中的显示方式。对于测试基于规则的 DNS 拆分工具（如 Control D）很有用。
  * [Namekit](https://namekit.app/) - AI 驱动的域名发现 – 即时查找可用的标准价格名称。免费每日查询。
  * [News API](https://newsapi.org) — 使用代码搜索网络上的新闻，并获取 JSON 结果。开发者每天免费获得 100 次查询。文章有 24 小时延迟。
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 每月 100 次免费请求。
  * [OCR.Space](https://ocr.space/) — 一个 OCR API，解析图像和 pdf 文件，以 JSON 格式返回文本结果。每月 25,000 次请求免费，文件大小限制为 1MB。
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 免费可视化创建 Open API 3 定义。
  * [parsehub.com](https://parsehub.com/) — 从动态站点提取数据，将动态网站转换为 API，五个项目免费。
  * [Parseur](https://parseur.com) — 每月 20 个免费页面：从 PDF、电子邮件中提取数据。AI 驱动。完整的 API 访问权限。
  * [PDFBolt](https://pdfbolt.com) - 专为隐私设计的以开发者为中心的 PDF 生成 API。它提供受 Stripe 启发的文档，并包括每月 500 次免费 PDF 转换。
  * [pdfEndpoint.com](https://pdfendpoint.com) - 使用简单的 API 轻松将 HTML 或 URL 转换为 PDF。每月免费一百次转换。
  * [PDF-API.io](https://pdf-api.io) - PDF 自动化 API、可视化模板编辑器或 HTML 转 PDF、动态数据集成和使用 API 进行 PDF 渲染。免费计划附带一个模板，每月 100 个 PDF。
  * [Pixela](https://pixe.la/) - 免费日流数据库服务。所有操作均通过 API 执行。还可以使用热图和折线图进行可视化。
  * [Postman](https://postman.com) — 使用 Postman 简化工作流程并更快地创建更好的 API，Postman 是一个用于 API 开发的协作平台。永久免费使用 Postman 应用程序。Postman 云功能也永久免费，但有一定的限制。
  * [Insomnia](https://insomnia.rest) - 用于设计和测试 API 的开源 API 客户端，支持 REST 和 GraphQL
  * [PrefectCloud](https://www.prefect.io/cloud/) — 数据流自动化的完整平台。免费计划包括每月 5 个已部署的工作流和 500 分钟的无服务器计算积分。
  * [Preset Cloud](https://preset.io/) - 托管的 Apache Superset 服务。最多 5 个用户的团队永久免费，具有无限的仪表板和图表、无代码图表构建器和协作 SQL 编辑器。
  * [PromptLoop](https://www.promptloop.com/) - PromptLoop 提供 10 倍更轻松的 AI 网络抓取，采用时间几乎为零，现有工作流程节省 85% 以上的时间，并且比手动研究快 4 倍，且不打折扣，并包括用于所有研究任务的 REST API 端点。每月前 1,000 个积分为免费。
  * [ProxySentry](https://proxysentry.io/) - 检测住宅代理和 VPN 的 IP API。ProxySentry.io 在 rapidapi.com 上提供每月 10k 请求的免费套餐。
  * [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — 免费公共 API 列表。
  * [Reducto](https://reducto.ai) - 将任何非结构化文档（PDF、XLSX、JPG、PPTX 等）转换为结构化 JSON 数据。解析、提取数据并编辑 PDF 表单。免费套餐包含 15k 免费积分和即用即付。
  * [Rapidapi](https://rapidapi.com/) - 世界上最大的 API 中心 数百万开发者查找并连接到数千个 API，使用有趣的挑战（带有解决方案！）和交互式示例进行 API 开发。
  * [Rendi](https://rendi.dev) - FFmpeg API - FFmpeg 的 REST API，无需处理基础设施即可在线运行 FFmpeg。免费套餐提供每月处理配额和 4 个 vCPU。
  * [RequestBin.com](https://requestbin.com) — 创建一个免费端点，您可以向其发送 HTTP 请求。发送到该端点的任何 HTTP 请求都将与关联的有效负载和标头一起记录，以便您可以观察来自 webhook 和其他服务的建议。
  * [reqres.in](https://reqres.in) - 一个免费托管的 REST-API，准备响应您的 AJAX 请求。
  * [Roboflow](https://roboflow.com) - 创建和部署自定义计算机视觉模型，无需任何机器学习经验。免费套餐包括每月 30 个积分。
  * [ROBOHASH](https://robohash.org/) - 从任何文本生成独特且酷炫图像的 Web 服务。
  * [Scraper's Proxy](https://scrapersproxy.com) — 用于抓取的简单 HTTP 代理 API。匿名抓取，无需担心限制、阻止或验证码。每月前 100 次成功抓取免费，包括 javascript 渲染（如果联系支持，可获得更多）。
  * [ScrapingAnt](https://scrapingant.com/) — 无头 Chrome 抓取 API 和免费检查代理服务。Javascript 渲染、高级轮换代理、避免验证码。免费 10,000 API 积分。
  * [ScrapX](https://www.scrapx.io/) — 监控目标网站的任何视觉或文本变化并提取数据。免费计划允许每月最多 5 个 URL。
  * [Simplescraper](https://simplescraper.io) — 每次操作后触发您的 webhook。免费计划包括 100 个云抓取积分。
  * [Select Star](https://www.selectstar.com/) - 是一个智能数据发现平台，可自动分析和记录您的数据。免费轻量级套餐，包含 2 个数据源、最多 1,000 个表和 25 个用户。
  * [Sheetson](https://sheetson.com) - 立即将任何 Google Sheets 转换为 RESTful API。提供免费计划，包括每张表 1,000 个免费行。
  * [Siterelic](https://siterelic.com/) - Siterelic API 让您可以截取屏幕截图、审核网站、TLS 扫描、DNS 查找、测试 TTFB 等。免费计划每月提供 100 次 API 请求。
  * [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取 API。返回 Google、YouTube、Bing、百度、沃尔玛和许多其他机器的结构化 JSON 结果。免费计划包括每月 100 次成功的 API 调用。
  * [SmartParse](https://smartparse.io) - SmartParse 是一个数据迁移和 CSV 到 API 平台，提供节省时间和成本的开发者工具。免费套餐包括每月 300 个处理单元、浏览器上传、数据隔离、断路器和作业警报。
  * [Sofodata](https://www.sofodata.com/) - 从 CSV 文件创建安全的 RESTful API。上传 CSV 文件并通过其 API 即时访问数据，从而加快应用程序开发。免费计划包括每月 2 个 API 和 2,500 次 API 调用。您不需要信用卡。
  * [YourGPT CSV to JSON](https://yourgpt.ai/tools/csv-to-json) — 一个快速、免费且注重隐私的在线工具，可轻松在浏览器中将 CSV 文件转换为结构化 JSON 数据。
  * [Sqlable](https://sqlable.com/) - 免费在线 SQL 工具集合，包括 SQL 格式化程序和验证器、SQL 正则表达式测试器、虚假数据生成器和交互式数据库游乐场。
  * [Stoplight](https://stoplight.io/) - 用于协作设计和记录 API 的 SaaS。免费计划提供免费的设计、模拟和文档工具。
  * [Supportivekoala](https://supportivekoala.com/) — 允许您通过模板根据输入自动生成图像。免费计划允许您每月创建最多 50 张图像。
  * [Svix](https://www.svix.com/) - Webhooks 即服务。每月免费发送最多 50,000 条消息。
  * [Tavily AI](https://tavily.com/) - 用于在线搜索、快速洞察和综合研究的 API，具有组织研究结果的能力。免费套餐每月 1000 次请求，无需信用卡。
  * [The IP API](https://theipapi.com/) - 每天 1000 次免费请求的 IP 地理定位 API。提供有关 IP 地址位置的信息，包括国家、城市、地区等。
  * [TinyMCE](https://www.tiny.cloud) - 富文本编辑 API。核心功能免费无限使用。
  * [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) - 提供天气 API 的免费计划。提供准确和最新的天气预报，具有全球覆盖范围、历史数据和天气监控解决方案。
  * [Treblle](https://www.treblle.com) - Treblle 帮助团队构建、发布和治理 API。具有高级 API 日志聚合、可观测性、文档和调试功能。您可以免费获得所有功能，但免费套餐每月最多限制 250k 请求。
  * [UniRateAPI](https://unirateapi.com) – 590 多种货币和加密货币的实时汇率。免费计划无限 API 调用，非常适合开发者和金融应用程序。
  * [vatcheckapi.com](https://vatcheckapi.com) - 简单且免费的增值税号验证 API。每月 150 次免费验证。
  * [WeatherXu](https://weatherxu.com/) — 全球天气数据，包括当前状况、每小时和每日预报以及通过我们的 API 发出的天气警报。集成 AI 模型和 ML 系统以分析和组合多个天气模型，从而提供改进的预报准确性。免费套餐包括 10,000 次 API 调用/月。
  * [WebScraping.AI](https://webscraping.ai) - 具有内置解析、Chrome 渲染和代理的简单 Web 抓取 API。每月两千次免费 API 调用。
  * [Weights & Biases](https://wandb.ai) — 开发者优先的 MLOps 平台。通过实验跟踪、数据集版本控制和模型管理更快地构建更好的模型。免费套餐仅限个人项目，包含 100 GB 存储空间。
  * [What The Diff](https://whatthediff.ai) - AI 驱动的代码审查助手。免费计划限制为 25,000 个月度代币（~10 个 PR）。
  * [wolfram.com](https://wolfram.com/language/) — 云中内置的基于知识的算法。
  * [wrapapi.com](https://wrapapi.com/) — 将任何网站转换为参数化 API。每月 30k API 调用。
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — 具有无头浏览器、住宅 IP 和简单定价的 Web 抓取 API。每月一千次免费 API 调用，学生和非营利组织可获得额外积分。
  * [Zipcodebase](https://zipcodebase.com) - 免费邮政编码 API，访问全球邮政编码数据。每月 5,000 次免费请求。
  * [Zipcodestack](https://zipcodestack.com) - 免费邮政编码 API 和邮政编码验证。每月一万次免费请求。
  * [Zuplo](https://zuplo.com/) - 免费 API 管理平台，用于设计、构建并将 API 部署到边缘。在几分钟内为任何 API 添加 API 密钥认证、速率限制、开发者文档和货币化。OpenAPI 原生且完全可编程，具有 Web 标准 api 和 Typescript。免费计划提供最多 10 个项目、无限生产边缘环境、1M 月度请求和 10GB 流出。
  * [DiffJSON](https://diffjson.com) - 一个在线工具，用于比较两个 JSON 数据结构之间的差异，帮助您快速定位 JSON 数据中的差异。
  * [FreeIPAPI](https://freeipapi.com) - 免费、快速且可靠的 IP 地理定位 API，适用于商业和非商业用户，以 JSON 格式提供

**[⬆️ 回到顶部](#目录)**

## 制品仓库

  * [Artifactory](https://jfrog.com/artifactory/) - 一个支持多种包格式（如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS）的制品仓库。包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（前身为 Shippable），免费套餐每月提供 2,000 CI/CD 分钟。
  * [central.sonatype.org](https://central.sonatype.org/) — Apache Maven、SBT 和其他构建系统的默认制品仓库。
  * [cloudrepo.io](https://cloudrepo.io/) — 基于云的私有和公共 Maven 和 PyPi 仓库。开源项目免费。
  * [cloudsmith.io](https://cloudsmith.io/) — 简单、安全和集中的仓库服务，适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等。免费套餐 + 开源免费。
  * [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 仓库，公共项目免费。
  * [repsy.io](https://repsy.io) — 1 GB 免费私有/公共 Maven 仓库。
  * [Gemfury](https://gemfury.com/) — Maven、PyPi、NPM、Go Module、Nuget、APT 和 RPM 仓库的私有和公共制品仓库。公共项目免费。
  * [paperspace](https://www.paperspace.com/) — 构建和扩展 AI 模型，开发、训练和部署 AI 应用程序，免费计划：公共项目，5Gb 存储，基本实例。
  * [RepoForge](https://repoforge.io/) — Python、Debian、NPM 包和 Docker 注册表的私有云托管仓库。开源/公共项目免费计划。
  * [RepoFlow](https://repoflow.com) — RepoFlow 简化了包管理，支持 npm、PyPI、Docker、Go、Helm 等。免费试用 10GB 存储、10GB 带宽、100 个包和无限用户，或仅供个人使用的自托管。

**[⬆️ 回到顶部](#目录)**

## 团队和协作工具

  * [3Cols](https://3cols.com) - 一个免费的基于云的代码片段管理器，用于个人和协作代码。
  * [Bitwarden](https://bitwarden.com/) - 个人、团队和企业组织存储、共享和同步敏感数据的最简单、最安全的方式。
  * [Braid](https://getbraid.io/) - 专为团队设计的聊天应用程序。公共访问组、无限用户、历史记录和集成免费。此外，它还提供自托管开源版本。
  * [cally.com](https://cally.com/) - 找到会议的最佳时间和日期。简单易用，非常适合小型和大型团体。
  * [Calendly](https://calendly.com/) — Calendly 是连接和安排会议的工具。免费计划为每个用户提供 1 个日历连接和无限会话。还提供桌面和移动应用程序。
  * [Discord](https://discord.com/) — 具有公共/私人房间的聊天。Markdown 文本、语音、视频和屏幕共享功能。无限用户免费。
  * [Fibo](https://fibopoker.com) - 一个免费的在线实时 scrum 扑克工具，适用于敏捷团队，让无限成员估算故事点以加快规划。
  * [Telegram](https://telegram.org/) - Telegram 适合所有想要快速、可靠消息传递和通话的人。商业用户和小型团队可能会喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项。
  * [DevToolLab](https://devtoollab.com) - 在线开发者工具，免费提供所有基本工具的访问权限，能够每个工具自动保存一个条目，标准处理速度和社区支持。
  * [Dubble](https://dubble.so) - 免费分步指南创建者。截取屏幕截图、记录流程并与您的团队协作。还支持异步屏幕录制。
  * [Duckly](https://duckly.com/) - 与您的团队实时交谈和协作。与 IDE 配对编程、终端共享、语音、视频和屏幕共享。小型团队免费。
  * [Dyte](https://dyte.io) - 对开发者最友好的实时视频和音频 SDK，具有协作插件以提高生产力和参与度。免费套餐包括每月 10,000 分钟的实时视频/音频使用。
  * [evernote.com](https://evernote.com/) — 组织信息的工具。分享您的笔记并与他人合作
  * [Fibery](https://fibery.io/) — 连接的工作区平台。单用户免费，最多 2 GB 磁盘空间。
  * [flock.com](https://flock.com/) — 团队沟通的更快方式。免费无限消息、频道、用户、应用程序和集成
  * [Gather](https://gather.town/) - 在线见面的更好方式。以完全可定制的空间为中心，Gather 让与社区共度时光就像现实生活一样轻松。最多 10 个并发用户免费。
  * [gokanban.io](https://gokanban.io/) - 基于语法的、无需注册的看板，可快速使用。免费无限制。
  * [flat.social](https://flat.social) - 用于团队会议和欢乐时光社交的交互式可定制空间。无限会议，最多 8 个并发用户免费。
  * [GitDailies](https://gitdailies.com/) - 团队在 GitHub 上的提交和合并请求活动的每日报告。包括推送可视化工具、同行认可系统和自定义警报构建器。免费套餐拥有无限用户、三个仓库和 3 个警报配置。
  * [gitter.im](https://gitter.im/) — GitHub 的聊天。无限公共和私人房间，最多 25 人的团队免费
  * [Hackmd.io](https://hackmd.io/) - markdown 格式文档/文件的实时协作和写作工具。像 Google Docs 但用于 markdown 文件。免费无限数量的“笔记”，但私人笔记和模板的协作者（受邀者）数量[将受到限制](https://hackmd.io/pricing)。
  * [hangouts.google.com](https://hangouts.google.com/) — 所有对话的一个地方，免费，需要 Google 帐户
  * [HeySpace](https://hey.space/) — 带有聊天、日历、时间线和视频通话的任务管理工具。最多 5 个用户免费。
  * [helplightning.com](https://helplightning.com/) — 通过增强现实视频提供帮助。免费，无分析、加密、支持
  * [ideascale.com](https://ideascale.com/) — 允许客户提交想法并投票，1 个社区中的 25 名成员免费
  * [Igloo](https://www.igloosoftware.com/) — 用于共享文档、博客、日历等的内部门户。最多 10 个用户免费。
  * [Keybase](https://keybase.io/) - Keybase 是 Slack 的 FOSS 替代品；它可以确保每个人的聊天和文件安全，从家庭到社区再到公司。
  * [Google Meet](https://apps.google.com/meet/) - 使用 Google Meet 满足您企业的在线视频会议需求。Meet 提供安全、易于加入的在线会议。
  * [/meet for Slack](https://meet.google.com/slack) - 直接从 Slack 启动、加入和共享 Google Meet 视频通话。
  * [Mattermost](https://mattermost.com/) — 具有 10GB 存储空间的 Slack 安全替代品。
  * [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) — Microsoft Teams 是一款专有的商业通信平台，是 Microsoft 365 系列产品的一部分。
  * [Miro](https://miro.com/) - 用于视觉协作的可扩展、安全、跨设备和企业就绪的团队协作白板。免费增值计划提供 3 个板和无限的团队成员。
  * [noora](https://noorahq.com/) - 帮助产品团队收集和优先考虑客户反馈的工具。免费计划包括 1 个管理员、无限用户和公开路线图。
  * [Notion](https://notion.so/) — 免费用于个人笔记、任务、wiki 和数据库。
  * [Pumble](https://pumble.com/) - 免费的团队聊天应用程序，允许各种规模的团队进行交流。无限用户、无限历史记录、用户和管理员管理、Web 和移动应用程序。
  * [Raindrop.io](https://raindrop.io) - 适用于 macOS、Windows、Android、iOS 和 Web 的私有且安全的书签管理器。用于协作和团队工作的免费无限书签和设备。
  * [Retool](https://retool.com) - 供开发者构建内部工具的平台。最多 5 个用户免费。
  * [Riot](https://about.riot.im/) — 建立在 [Matrix](https://matrix.org/) 标准之上的免费开源协作工具。
  * [Rocket.Chat](https://rocket.chat/) — 具有无限用户、消息、频道和音频/视频会议的开源通信平台。
  * [Screen.so](https://screen.so/) — 具有绘图、控制等功能的屏幕共享。
  * [Skype](https://www.skype.com/) — 免费进行 Skype 到 Skype 的视频和语音通话。
  * [Slack](https://slack.com/) — 具有 10k 消息限制的免费计划。
  * [Spectrum](https://spectrum.chat/) — 免费创建无限的公共或私人社区。
  * [StatusHero](https://statushero.com/) — 自动化的团队状态跟踪和签到。无需信用卡。
  * [Symphony](https://symphony.com/) — 免费向所有人发送消息，向所有人发送语音和视频。
  * [Talk](https://talk.talkjs.com/) — 免费的 P2P 群组视频通话，无需注册/登录。适用于 iOS/Android/Web。
  * [Taiga](https://taiga.io/) — 敏捷项目管理平台。公共项目免费，一个私人项目免费（最多 3 名成员）。
  * [TeamViewer](https://www.teamviewer.com/) — 远程控制和在线会议软件。非商业用途免费。
  * [Teletype for Atom](https://teletype.atom.io/) — 免费的开源工具，允许开发者共享他们的工作区并实时协作编写代码。
  * [Trello](https://trello.com/) — 免费无限的板、列表、卡片、成员、清单和附件。
  * [Tuck](https://tuck.app/) — 免费的统一团队主页，包含会议、文档、链接和 iframe。
  * [Twist](https://twist.com/) — 异步友好的团队沟通应用程序。免费计划包括 1 个月的消息和文件历史记录，以及 5 个集成。
  * [TypeTalk](https://www.typetalk.com/) — 通过即时消息在 Web 或移动设备上与您的团队共享和讨论想法。10 个用户免费，1GB 文件存储。
  * [Uptime.com](https://uptime.com/) — 免费的基本网站监控（5 分钟间隔，1 个检查）。
  * [Userback](https://www.userback.io/) — 收集用户反馈的视觉反馈工具。免费计划包括 1 个项目、2 个用户和无限反馈。
  * [Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) — 实时代码协作。
  * [WakaTime](https://wakatime.com/) — 自动生成的指标、见解和时间跟踪，源自您的编程活动。
  * [WeTransfer](https://wetransfer.com/) — 免费发送高达 2GB 的文件。
  * [Whereby](https://whereby.com/) — 免费的一键式视频会议（最多 4 人）。
  * [Whimsical](https://whimsical.com/) — 协作流程图、线框图、思维导图和文档。最多 3 个协作板免费。
  * [Wire](https://wire.com/) — 安全的信使、文件共享、语音和视频会议。个人使用免费。
  * [Yandex.Connect](https://connect.yandex.com/) — 免费的电子邮件和团队协作工具。
  * [Youtrack](https://www.jetbrains.com/youtrack/) — 免费的基于云的问题跟踪器，适用于最多 10 个用户的团队（包括 30GB 存储空间）。
  * [Zoom](https://zoom.us/) — 免费的安全视频会议（最多 100 人，40 分钟限制）。
  * [Zulip](https://zulip.com/) — 具有独特线程模型的实时聊天。免费计划包括 10k 消息历史记录。

**[⬆️ 回到顶部](#目录)**

## 内容管理系统 (CMS)

  * [Acquia](https://www.acquia.com/) — 托管 Drupal 站点。开发人员免费沙盒环境。
  * [Contentful](https://www.contentful.com/) — 无头 CMS。云端免费提供 5 个用户、25k 条记录、2 个语言环境、1TB 带宽。
  * [Cosmic](https://www.cosmicjs.com/) — 无头 CMS。免费个人计划供开发者构建应用程序。
  * [Crystalize](https://crystallize.com/) — 具有丰富产品信息的电子商务无头 CMS。免费套餐包括无限用户、1000 个目录项、5GB 带宽/月和 25k API 调用/月。
  * [DatoCMS](https://www.datocms.com/) — 采用 GraphQL 构建的无头 CMS。免费层级提供 100k API 调用/月、200MB 资产存储和 1TB 带宽/月。
  * [Directus](https://directus.io/) — 无头 CMS。免费自托管层级。
  * [Forestry](https://forestry.io/) — 基于 Git 的 CMS。最多 3 个站点免费。
  * [Ghost](https://ghost.org/) — 发布平台。自托管免费。
  * [GraphCMS](https://graphcms.com/) — GraphQL 原生无头 CMS。免费层级提供 5 个席位、100k 操作/月、100GB 资产流量/月和 500GB 资产存储。
  * [Kontent.ai](https://kontent.ai/) — 无头 CMS。开发者计划提供 2 个用户、每个项目 500 个内容项、无限项目和 API 调用。
  * [Prismic](https://prismic.io/) — 无头 CMS。1 个用户免费。
  * [Sanity](https://www.sanity.io/) — 具有开源编辑环境的结构化内容平台。包含慷慨的免费层级（10GB 带宽/月、500k API 请求/月、3 个用户）。
  * [Strapi](https://strapi.io/) — 开源无头 CMS。自托管免费。
  * [TinaCMS](https://tina.io/) — 基于 Git 的无头 CMS。免费层级提供 2 个用户。
  * [Typro3](https://typo3.org/) — 企业级开源 CMS。自托管免费。
  * [Wagtail](https://wagtail.org/) — 基于 Django 的开源 CMS。自托管免费。
  * [Webflow](https://webflow.com/) — CMS 和网站构建器。2 个项目免费。
  * [Wordpress](https://wordpress.com/) — 网站托管。免费计划包括 3GB 存储空间。

**[⬆️ 回到顶部](#目录)**

## 代码生成

  * [Appinvento](https://appinvento.io/) — 免费的无代码应用程序构建器，具有 Google 登录、Google 地图和 AWS 托管。完整的源代码下载。一个应用程序免费。
  * [Codeium](https://codeium.com/) — 免费的 AI 代码补全和聊天工具。
  * [CodeRabbit](https://coderabbit.ai/) — 免费的 AI 代码审查工具。
  * [CorsBypass](https://corsbypass.com/) — 免费的 CORS 代理服务，帮助开发者解决跨域资源共享问题。
  * [DhiWise](https://dhiwise.com/) — 将 Figma 设计转换为 Flutter、React、iOS、Android 代码。免费计划包括无限的屏幕和代码生成。
  * [HackerAI](https://hackerai.co/) — 免费的 AI 代码审计工具，用于检测基础设施即代码 (IaC) 中的安全漏洞。
  * [MarsX](https://www.marsx.dev/) — 免费的低代码平台，用于构建 Web 和移动应用程序。
  * [Phind](https://www.phind.com/) — 专为开发者设计的 AI 搜索引擎。
  * [QuickType](https://app.quicktype.io/) — 从 JSON 生成多种语言的模型和序列化代码。
  * [TeleportHQ](https://teleporthq.io/) — 低代码平台，用于构建静态网站和 UI。3 个项目免费。
  * [Wagtail](https://wagtail.org/) — 基于 Django 的开源 CMS。自托管免费。

**[⬆️ 回到顶部](#目录)**

## 代码质量

  * [Axolo](https://axolo.co) - 协作代码审查。每个仓库最多 3 名开发者免费。
  * [BeanHunter](https://bean-hunter.com/) - 扫描 Java 代码中的潜在安全漏洞。
  * [Better Code Hub](https://bettercodehub.com/) — 检查 GitHub 拉取请求的质量。公共仓库免费。
  * [Bold](https://bold.dx.com/) — 代码审查和工程指标。初创公司免费。
  * [Codacy](https://www.codacy.com/) — 自动代码审查，监控代码质量。开源项目免费。
  * [Codeac](https://codeac.io/) — 基础设施即代码 (IaC) 审查工具。公共仓库免费。
  * [CodeBeat](https://codebeat.co/) — 自动代码审查平台。公共仓库免费。
  * [CodeClimate](https://codeclimate.com/) — 自动代码审查和测试覆盖率。开源项目免费。
  * [CodeCov](https://codecov.io/) — 代码覆盖率工具。公共仓库免费。
  * [CodeFactor](https://www.codefactor.io/) — 自动代码审查。公共仓库免费。
  * [CodeScene](https://codescene.io/) — 代码分析工具，识别技术债务。开源项目免费。
  * [Codiga](https://www.codiga.io/) — 代码分析和自动代码审查。开源项目免费。
  * [Coveralls](https://coveralls.io/) — 代码覆盖率历史和统计。开源项目免费。
  * [DeepScan](https://deepscan.io/) — JavaScript 代码的静态分析工具。开源项目免费。
  * [DeepSource](https://deepsource.io/) — 自动代码审查和静态分析。开源项目免费。
  * [Embold](https://embold.io/) — 软件分析平台。开源项目免费。
  * [gerrit-review](https://www.gerritcodereview.com/) — 代码审查工具。开源项目免费。
  * [Go Report Card](https://goreportcard.com/) — Go 语言代码质量报告。免费。
  * [Hounds](https://hounds.io/) — 自动代码审查工具。开源项目免费。
  * [Immersive](https://immersive.dev/) — 代码文档和知识库。个人免费。
  * [LGTM](https://lgtm.com/) — 自动代码审查。开源项目免费。
  * [PullRequest](https://www.pullrequest.com/) — 代码审查即服务。开源项目免费。
  * [Quality](https://quality.io/) — 代码质量监控。开源项目免费。
  * [Reviewable](https://reviewable.io/) — 代码审查工具。开源项目免费。
  * [Scrutinizer](https://scrutinizer-ci.com/) — 代码质量检查。开源项目免费。
  * [SensioLabs Insight](https://insight.sensiolabs.com/) — PHP 代码质量检查。开源项目免费。
  * [SideCI](https://sideci.com/) — 自动代码审查。开源项目免费。
  * [Snyk](https://snyk.io/) — 查找和修复开源依赖项中的漏洞。开源项目免费。
  * [SonarCloud](https://sonarcloud.io/) — 自动代码审查和质量分析。开源项目免费。
  * [SourceLevel](https://sourcelevel.io/) — 代码审查和工程指标。开源项目免费。
  * [StyleCI](https://styleci.io/) — PHP 代码风格检查。开源项目免费。
  * [Swimm](https://swimm.io/) — 代码文档工具。开源项目免费。
  * [Tickgit](https://www.tickgit.com/) — 项目管理工具，基于代码中的 TODO 注释。公共仓库免费。
  * [Typo CI](https://typo.ci/) — 拼写检查工具。开源项目免费。
  * [Vercel](https://vercel.com/) — 静态站点和无服务器函数的部署平台。个人免费。

**[⬆️ 回到顶部](#目录)**

## 代码搜索和浏览

  * [Blink](https://blink.sh) - 允许您在眨眼间搜索整个源代码的工具。它在云端运行，因此您无需克隆任何内容。免费计划适用于公共仓库。
  * [CommandDash](https://commanddash.io) - 这是一个 AI 驱动的工具，允许您在 IDE 中搜索和浏览代码片段、文档和解释。
  * [Grep.app](https://grep.app/) — 搜索 GitHub 上的公共仓库。
  * [Hound](https://github.com/etsy/Hound) — React 驱动的代码搜索工具。
  * [Livegrep](https://livegrep.com/) — 交互式正则表达式代码搜索。
  * [PublicWWW](https://publicwww.com/) — 搜索公共网页源代码。
  * [Sourcegraph](https://sourcegraph.com/) — 代码搜索和浏览工具。公共仓库免费。
  * [Tickgit](https://www.tickgit.com/) — 项目管理工具，基于代码中的 TODO 注释。公共仓库免费。

**[⬆️ 回到顶部](#目录)**

## 持续集成和持续部署 (CI/CD)

  * [AccessLint](https://accesslint.com/) — 自动化的 Web 可访问性测试。开源项目免费。
  * [Appcircle](https://appcircle.io/) — 自动化的移动 CI/CD/CT，用于 iOS 和 Android。免费计划包括每月 20 次构建。
  * [AppVeyor](https://www.appveyor.com/) — Windows CI/CD 服务。开源项目免费。
  * [Argos-CI](https://argos-ci.com/) — 自动化的视觉回归测试。开源项目免费。
  * [Bitrise](https://www.bitrise.io/) — 移动 CI/CD 平台。免费计划包括每月 200 次构建。
  * [Buildkite](https://buildkite.com/) — 混合 CI/CD 平台。开源项目免费。
  * [CircleCI](https://circleci.com/) — 自动化的 CI/CD 平台。免费计划包括每月 2,500 积分。
  * [Codefresh](https://codefresh.io/) — Kubernetes 原生 CI/CD 平台。免费计划包括每月 20 次构建。
  * [Codeship](https://codeship.com/) — 简单、灵活的 CI/CD 平台。免费计划包括每月 100 次构建。
  * [Codemagic](https://codemagic.io/) — Flutter CI/CD 平台。免费计划包括每月 500 分钟。
  * [Concourse](https://concourse-ci.org/) — 容器化的 CI/CD 系统。开源项目免费。
  * [DeployHQ](https://www.deployhq.com/) — 自动化的部署服务。免费计划包括每天 10 次部署。
  * [Drone](https://drone.io/) — 容器原生的 CI/CD 平台。开源项目免费。
  * [GitHub Actions](https://github.com/features/actions) — GitHub 的 CI/CD 服务。公共仓库免费，私有仓库每月 2,000 分钟。
  * [GitLab CI](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/) — GitLab 的 CI/CD 服务。公共仓库免费，私有仓库每月 400 分钟。
  * [Google Cloud Build](https://cloud.google.com/build) — Google Cloud 的 CI/CD 服务。每天 120 分钟免费。
  * [LayerCI](https://layerci.com/) — 全栈 CI/CD 平台。开源项目免费。
  * [Magnum CI](https://magnum-ci.com/) — 托管的 CI 服务。开源项目免费。
  * [Netlify](https://www.netlify.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [Nevercode](https://nevercode.io/) — 移动 CI/CD 平台。免费计划包括每月 200 次构建。
  * [Semaphore](https://semaphoreci.com/) — 高速 CI/CD 平台。免费计划包括每月 1,300 分钟。
  * [Shippable](https://www.shippable.com/) — 容器化的 CI/CD 平台。免费计划包括每月 150 次构建。
  * [Solano CI](https://www.solanolabs.com/) — 高性能 CI/CD 平台。免费计划包括每月 50 次构建。
  * [StyleCI](https://styleci.io/) — PHP 代码风格检查。开源项目免费。
  * [Travis CI](https://travis-ci.com/) — 托管的 CI 服务。开源项目免费。
  * [Vercel](https://vercel.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [Wercker](https://www.wercker.com/) — 容器化的 CI/CD 平台。免费计划包括每月 2 个并发构建。

**[⬆️ 回到顶部](#目录)**

## 测试

  * [Applitools](https://applitools.com/) — 自动化的视觉测试。免费计划包括每月 100 次检查点。
  * [BrowserStack](https://www.browserstack.com/) — 跨浏览器测试平台。开源项目免费。
  * [Checkly](https://www.checklyhq.com/) — API 和端到端监控。免费计划包括每月 10k API 检查和 1k 浏览器检查。
  * [CodeceptJS](https://codecept.io/) — 端到端测试框架。开源项目免费。
  * [Cypress](https://www.cypress.io/) — 前端测试工具。开源项目免费。
  * [Ghost Inspector](https://ghostinspector.com/) — 自动化的浏览器测试。免费计划包括每月 100 次测试运行。
  * [Happo](https://happo.io/) — 跨浏览器截图测试。开源项目免费。
  * [HeadSpin](https://www.headspin.io/) — 移动应用测试平台。免费计划包括每天 10 分钟。
  * [K6](https://k6.io/) — 负载测试工具。免费计划包括每月 50 次云测试。
  * [LambdaTest](https://www.lambdatest.com/) — 跨浏览器测试平台。开源项目免费。
  * [Loader.io](https://loader.io/) — 负载测试服务。免费计划包括每月 10k 客户端。
  * [Mabl](https://www.mabl.com/) — 智能测试自动化。开源项目免费。
  * [Percy](https://percy.io/) — 视觉审查平台。免费计划包括每月 5,000 张截图。
  * [Sauce Labs](https://saucelabs.com/) — 跨浏览器测试平台。开源项目免费。
  * [TestingBot](https://testingbot.com/) — 跨浏览器测试平台。开源项目免费。
  * [TestProject](https://testproject.io/) — 免费的端到端测试自动化平台。
  * [Uptrends](https://www.uptrends.com/) — 网站监控和测试。免费计划包括每月 10 个检查点。

**[⬆️ 回到顶部](#目录)**

## 安全和 PKI

  * [Alienvault](https://www.alienvault.com/open-threat-exchange) — Open Threat Exchange (OTX) 是一个开放的威胁情报社区，可以免费访问。
  * [Auth0](https://auth0.com/) — 托管的 SSO。最多 7,000 个活跃用户免费。
  * [Bitwarden](https://bitwarden.com/) — 个人、团队和企业组织存储、共享和同步敏感数据的最简单、最安全的方式。
  * [Bluesentry](https://bluesentry.com/) — AWS 安全监控。免费计划包括每月 100 次扫描。
  * [Censys](https://censys.io/) — 互联网范围内的扫描数据。研究人员免费。
  * [Cloudflare](https://www.cloudflare.com/) — 免费的 SSL、DDoS 保护和 CDN。
  * [CodeNotary](https://www.codenotary.io/) — 具有不可变分类账的开源软件供应链安全。开源项目免费。
  * [Crypteron](https://crypteron.com/) — 云优先的数据安全平台。免费计划包括每月 100 次加密操作。
  * [Detectify](https://detectify.com/) — 自动化的 Web 安全扫描。开源项目免费。
  * [Duo Security](https://duo.com/) — 双因素认证。最多 10 个用户免费。
  * [GoodAccess](https://www.goodaccess.com/) — 免费的云 VPN，最多 100 个用户。
  * [Google Cloud KMS](https://cloud.google.com/kms) — 密钥管理服务。免费层级包括每月 10,000 次操作。
  * [HackerOne](https://www.hackerone.com/) — 漏洞赏金平台。开源项目免费。
  * [Intruder](https://intruder.io/) — 漏洞扫描器。30 天免费试用。
  * [Keychest](https://keychest.net/) — SSL 证书管理和过期监控。免费计划包括 10 个域名。
  * [Let's Encrypt](https://letsencrypt.org/) — 免费的 SSL/TLS 证书颁发机构。
  * [LogRhythm](https://logrhythm.com/) — 安全情报和分析平台。免费计划包括每天 1GB 日志。
  * [Metasploit](https://www.metasploit.com/) — 渗透测试框架。开源版本免费。
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 免费的 Web 安全扫描器。
  * [Okta](https://www.okta.com/) — 身份管理平台。开发者版免费，每月 15,000 个活跃用户。
  * [Onelogin](https://www.onelogin.com/) — 身份管理平台。开发者版免费，3 个应用程序和 25 个用户。
  * [OpenVPN](https://openvpn.net/) — VPN 服务器。2 个并发连接免费。
  * [Opswat](https://www.opswat.com/) — 网络安全平台。免费工具可用。
  * [Qualys](https://www.qualys.com/) — 云安全和合规性。免费社区版。
  * [Report URI](https://report-uri.com/) — 实时安全报告。免费计划包括每月 10,000 份报告。
  * [Ring4](https://www.ring4.com/) — 商务电话系统。免费计划包括 1 个号码和无限通话。
  * [Snyk](https://snyk.io/) — 查找和修复开源依赖项中的漏洞。开源项目免费。
  * [SonarQube](https://www.sonarqube.org/) — 代码质量和安全扫描。开源版本免费。
  * [Sqreen](https://www.sqreen.com/) — 应用程序安全管理。免费计划包括每月 100 万次请求。
  * [SSLLabs](https://www.ssllabs.com/) — 免费的 SSL 服务器测试。
  * [StackHawk](https://www.stackhawk.com/) — 应用程序安全测试。开发者免费。
  * [Sucuri](https://sucuri.net/) — 网站安全平台。免费扫描器可用。
  * [Tailscale](https://tailscale.com/) — 基于 WireGuard 的零配置 VPN。个人免费，最多 20 台设备。
  * [ThreatStack](https://www.threatstack.com/) — 云安全和合规性。免费试用。
  * [Twingate](https://www.twingate.com/) — 零信任网络访问。免费计划包括 5 个用户和 2 个远程网络。
  * [Ubiq Security](https://www.ubiqsecurity.com/) — 应用程序层加密。免费计划包括每月 10,000 次加密操作。
  * [Virustotal](https://www.virustotal.com/) — 免费的在线病毒、恶意软件和 URL 扫描器。
  * [Vulcain](https://vulcain.rocks/) — 免费的漏洞扫描器。
  * [Wazuh](https://wazuh.com/) — 开源安全监控。免费。
  * [WhiteSource](https://www.whitesourcesoftware.com/) — 开源安全和合规性。开源项目免费。
  * [ZeroTier](https://www.zerotier.com/) — 软件定义的网络。免费计划包括 50 个成员。

**[⬆️ 回到顶部](#目录)**

## 认证、授权和用户管理

  * [Aserto](https://www.aserto.com/) — 云原生授权平台。免费计划包括每月 1,000 个授权决策。
  * [Auth0](https://auth0.com/) — 托管的 SSO。最多 7,000 个活跃用户免费。
  * [Authress](https://authress.io/) — 身份验证和授权即服务。免费计划包括每月 1,000 次登录。
  * [Authing](https://authing.cn/) — 身份管理平台。免费计划包括每月 1,000 个活跃用户。
  * [AWS Cognito](https://aws.amazon.com/cognito/) — 身份管理服务。每月 50,000 个活跃用户免费。
  * [Azure Active Directory](https://azure.microsoft.com/en-us/services/active-directory/) — 身份管理服务。免费版包括 500,000 个对象。
  * [Clerk](https://clerk.dev/) — 身份验证和用户管理。免费计划包括每月 5,000 个活跃用户。
  * [Cloud-IAM](https://cloud-iam.com/) — 托管的 Keycloak 身份和访问管理。免费计划包括 100 个用户。
  * [Firebase Authentication](https://firebase.google.com/products/auth) — 身份验证服务。免费计划包括无限的电话验证（美国/加拿大/印度）。
  * [FusionAuth](https://fusionauth.io/) — 身份验证和授权平台。自托管免费。
  * [Keycloak](https://www.keycloak.org/) — 开源身份和访问管理。自托管免费。
  * [LoginRadius](https://www.loginradius.com/) — 身份管理平台。免费计划包括每月 2,500 个活跃用户。
  * [Magic](https://magic.link/) — 无密码身份验证。免费计划包括每月 1,000 次登录。
  * [Okta](https://www.okta.com/) — 身份管理平台。开发者版免费，每月 15,000 个活跃用户。
  * [OneLogin](https://www.onelogin.com/) — 身份管理平台。开发者版免费，3 个应用程序和 25 个用户。
  * [Ory](https://www.ory.sh/) — 开源身份基础设施。自托管免费。
  * [SuperTokens](https://supertokens.io/) — 开源身份验证解决方案。自托管免费。
  * [Userfront](https://userfront.com/) — 身份验证和访问控制。免费计划包括每月 10,000 个活跃用户。
  * [WorkOS](https://workos.com/) — 企业 SSO 和目录同步。开发者免费。
  * [Zitadel](https://zitadel.ch/) — 身份管理平台。免费计划包括每月 25,000 个请求。

**[⬆️ 回到顶部](#目录)**

## 移动应用分发和反馈

  * [AppCenter](https://appcenter.ms/) — 持续构建、测试、发布和监控应用程序。免费计划包括每月 240 分钟构建时间。
  * [Appetize.io](https://appetize.io/) — 在浏览器中运行原生移动应用程序。免费计划包括每月 100 分钟。
  * [AppStore Connect](https://appstoreconnect.apple.com/) — Apple 的应用程序分发平台。包含在开发者计划中。
  * [Beta Family](https://betafamily.com/) — 众包 beta 测试平台。免费计划包括 1 个测试。
  * [Diawi](https://www.diawi.com/) — iOS 和 Android 应用程序部署。免费计划包括 3 个应用程序。
  * [Expo](https://expo.dev/) — React Native 应用程序平台。免费计划包括无限的构建和更新。
  * [Fabric](https://fabric.io/) — 移动平台（现已合并到 Firebase）。免费。
  * [Firebase App Distribution](https://firebase.google.com/products/app-distribution) — 将应用程序分发给测试人员。免费。
  * [Google Play Console](https://play.google.com/console) — Google 的应用程序分发平台。一次性费用 25 美元。
  * [InstallOnAir](https://www.installonair.com/) — iOS 和 Android 应用程序分发。免费计划包括 1 个应用程序。
  * [TestFlight](https://developer.apple.com/testflight/) — Apple 的 beta 测试平台。包含在开发者计划中。
  * [UberTesters](https://ubertesters.com/) — 移动 beta 测试平台。免费计划包括 2 个项目。

**[⬆️ 回到顶部](#目录)**

## 管理系统

  * [Bitrix24](https://www.bitrix24.com/) — 免费的内网和项目管理工具。无限用户免费。
  * [Clockify](https://clockify.me/) — 免费的时间跟踪工具。无限用户免费。
  * [Flow](https://www.getflow.com/) — 项目管理工具。30 天免费试用。
  * [Freedcamp](https://freedcamp.com/) — 项目管理工具。无限用户、项目和存储免费。
  * [HubSpot](https://www.hubspot.com/) — 免费的 CRM、营销、销售和客户服务工具。
  * [Kissflow](https://kissflow.com/) — 业务流程管理。14 天免费试用。
  * [Lark](https://www.larksuite.com/) — 协作套件。无限用户免费（有存储限制）。
  * [MeisterTask](https://www.meistertask.com/) — 任务管理工具。最多 3 个项目免费。
  * [Monday.com](https://monday.com/) — 项目管理工具。2 个用户免费。
  * [Odoo](https://www.odoo.com/) — 开源 ERP 和 CRM。一个应用程序免费。
  * [Plaky](https://plaky.com/) — 免费的项目管理工具。无限用户免费。
  * [Plan.io](https://plan.io/) — 项目管理工具。免费计划包括 2 个用户和 10 个问题。
  * [Process Street](https://www.process.st/) — 流程管理工具。免费计划包括 1 个活跃工作流。
  * [Toggl](https://toggl.com/) — 时间跟踪工具。最多 5 个用户免费。
  * [Wrike](https://www.wrike.com/) — 项目管理工具。最多 5 个用户免费。
  * [Zoho](https://www.zoho.com/) — 商业应用程序套件。免费计划可用。

**[⬆️ 回到顶部](#目录)**

## 消息和流媒体

  * [Ably](https://ably.com/) — 实时消息传递平台。免费计划包括每月 300 万条消息。
  * [AIOQ](https://aioq.io/) — 消息队列服务。免费计划包括每月 100 万条消息。
  * [Amazon SNS](https://aws.amazon.com/sns/) — 消息发布/订阅服务。每月 100 万次发布免费。
  * [Amazon SQS](https://aws.amazon.com/sqs/) — 消息队列服务。每月 100 万次请求免费。
  * [Apache Kafka](https://kafka.apache.org/) — 分布式流媒体平台。开源免费。
  * [Azure Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/) — 大数据流媒体平台。免费试用。
  * [Azure Service Bus](https://azure.microsoft.com/en-us/services/service-bus/) — 企业消息传递服务。免费试用。
  * [CloudAMQP](https://www.cloudamqp.com/) — 托管的 RabbitMQ。免费计划包括 100 万条消息/月。
  * [Confluent Cloud](https://www.confluent.io/confluent-cloud/) — 托管的 Kafka。免费试用。
  * [Courier](https://www.courier.com/) — 通知基础设施。每月 10,000 条消息免费。
  * [Google Cloud Pub/Sub](https://cloud.google.com/pubsub) — 消息传递服务。每月 10GB 免费。
  * [HiveMQ](https://www.hivemq.com/) — MQTT 代理。免费计划包括 100 个连接。
  * [IBM MQ](https://www.ibm.com/products/mq) — 企业消息传递。开发者版免费。
  * [Inngest](https://www.inngest.com/) — 事件驱动的队列。免费计划包括每月 50k 事件。
  * [Knock](https://knock.app/) — 通知基础设施。每月 10,000 条消息免费。
  * [Memphis](https://memphis.dev/) — 消息代理。开源免费。
  * [Novu](https://novu.co/) — 通知基础设施。每月 10,000 条消息免费。
  * [Pusher](https://pusher.com/) — 实时消息传递 API。免费计划包括每天 200k 消息。
  * [RabbitMQ](https://www.rabbitmq.com/) — 开源消息代理。免费。
  * [Redis](https://redis.io/) — 内存数据结构存储，用作数据库、缓存和消息代理。开源免费。
  * [ScaleDrone](https://www.scaledrone.com/) — 实时消息传递 API。免费计划包括每天 100k 消息。
  * [Stream](https://getstream.io/) — 活动流和聊天 API。免费计划包括每月 300 万次 API 调用。
  * [SuprSend](https://suprsend.com/) — 通知基础设施。每月 10,000 条消息免费。
  * [Tinybird](https://www.tinybird.co/) — 实时数据平台。免费计划包括每天 10GB 数据摄取。
  * [Upstash](https://upstash.com/) — 无服务器 Redis 和 Kafka。免费计划包括每天 10,000 个命令。

**[⬆️ 回到顶部](#目录)**

## 日志管理

  * [Better Stack](https://betterstack.com/) — 日志管理和监控。免费计划包括每月 1GB 日志。
  * [Bugfender](https://bugfender.com/) — 远程日志记录服务。免费计划包括每天 100k 日志行。
  * [Coralogix](https://coralogix.com/) — 日志分析平台。免费计划包括每天 500MB。
  * [Datadog](https://www.datadoghq.com/) — 监控和安全平台。免费计划包括最多 5 个主机。
  * [DNA](https://www.dna-platform.com/) — 日志分析平台。免费计划包括每天 100MB。
  * [Elastic Cloud](https://www.elastic.co/cloud/) — 托管的 Elasticsearch。免费试用。
  * [Grafana Cloud](https://grafana.com/products/cloud/) — 托管的 Grafana、Loki 和 Prometheus。免费计划包括 50GB 日志/月。
  * [Humio](https://www.humio.com/) — 日志管理平台。免费计划包括每天 2GB。
  * [LogDNA](https://www.logdna.com/) — 日志管理平台。免费计划包括无限日志摄取（无保留）。
  * [Loggly](https://www.loggly.com/) — 日志管理服务。免费计划包括每天 200MB。
  * [Logz.io](https://logz.io/) — 基于 ELK 的日志管理。免费计划包括每天 1GB。
  * [New Relic](https://newrelic.com/) — 可观测性平台。免费计划包括每月 100GB 数据摄取。
  * [Papertrail](https://www.papertrail.com/) — 日志管理服务。免费计划包括每月 50MB。
  * [Sematext](https://sematext.com/) — 监控和日志管理。免费计划包括每天 500MB。
  * [Sentry](https://sentry.io/) — 错误跟踪和性能监控。免费计划包括每月 5k 事件。
  * [Splunk](https://www.splunk.com/) — 数据分析平台。免费计划包括每天 500MB。
  * [Sumo Logic](https://www.sumologic.com/) — 云原生机器数据分析。免费计划包括每天 500MB。

**[⬆️ 回到顶部](#目录)**

## 翻译管理

  * [Crowdin](https://crowdin.com/) — 翻译管理平台。开源项目免费。
  * [GitLocalize](https://gitlocalize.com/) — 翻译管理平台。公共仓库免费。
  * [Localizely](https://localizely.com/) — 翻译管理平台。开源项目免费。
  * [Locize](https://locize.com/) — 翻译管理平台。14 天免费试用。
  * [OneSky](https://www.oneskyapp.com/) — 翻译管理平台。免费计划包括 5 个协作者。
  * [POEditor](https://poeditor.com/) — 翻译管理平台。免费计划包括 1000 个字符串。
  * [SimpleLocalize](https://simplelocalize.io/) — 翻译管理平台。免费计划包括 100 个键。
  * [Tolgee](https://tolgee.io/) — 翻译管理平台。开源项目免费。
  * [Transifex](https://www.transifex.com/) — 翻译管理平台。开源项目免费。
  * [Weblate](https://weblate.org/) — 翻译管理平台。开源项目免费。

**[⬆️ 回到顶部](#目录)**

## 监控

  * [AppDynamics](https://www.appdynamics.com/) — 应用程序性能管理。免费计划包括 1 个代理。
  * [AppSignal](https://appsignal.com/) — 应用程序性能监控。30 天免费试用。
  * [Assertible](https://assertible.com/) — API 测试和监控。免费计划包括 2 个服务。
  * [Blackfire](https://blackfire.io/) — PHP 性能分析。免费计划包括开发者版。
  * [Catchpoint](https://www.catchpoint.com/) — 数字体验监控。免费试用。
  * [Checkly](https://www.checklyhq.com/) — API 和端到端监控。免费计划包括每月 10k API 检查和 1k 浏览器检查。
  * [CloudWatch](https://aws.amazon.com/cloudwatch/) — AWS 监控服务。免费层级包括每月 10 个警报。
  * [Cronitor](https://cronitor.io/) — Cron 作业监控。免费计划包括 5 个监视器。
  * [Datadog](https://www.datadoghq.com/) — 监控和安全平台。免费计划包括最多 5 个主机。
  * [Dead Man's Snitch](https://deadmanssnitch.com/) — Cron 作业监控。免费计划包括 1 个嗅探器。
  * [Dynatrace](https://www.dynatrace.com/) — 软件智能平台。免费试用。
  * [Elastic APM](https://www.elastic.co/apm) — 应用程序性能监控。开源免费。
  * [Grafana](https://grafana.com/) — 监控和可观测性平台。开源免费。
  * [Healthchecks.io](https://healthchecks.io/) — Cron 作业监控。免费计划包括 20 个检查。
  * [Honeybadger](https://www.honeybadger.io/) — 异常监控。免费计划包括每月 12k 错误。
  * [Inspector](https://inspector.dev/) — 实时代码执行监控。免费计划包括每月 30k 事务。
  * [Instrumental](https://instrumentalapp.com/) — 应用程序和服务器监控。免费计划包括每月 500 个指标。
  * [Librato](https://www.librato.com/) — 实时云监控。免费计划包括 100 个指标。
  * [Monit](https://mmonit.com/monit/) — 系统监控。开源免费。
  * [Munin](http://munin-monitoring.org/) — 网络资源监控。开源免费。
  * [Nagios](https://www.nagios.org/) — IT 基础设施监控。开源免费。
  * [Netdata](https://www.netdata.cloud/) — 实时性能监控。开源免费。
  * [New Relic](https://newrelic.com/) — 可观测性平台。免费计划包括每月 100GB 数据摄取。
  * [NodeQuery](https://nodequery.com/) — Linux 服务器监控。免费计划包括 10 台服务器。
  * [OpsGenie](https://www.opsgenie.com/) — 事件管理平台。免费计划包括 5 个用户。
  * [PagerDuty](https://www.pagerduty.com/) — 事件响应平台。免费计划包括 5 个用户。
  * [Pingdom](https://www.pingdom.com/) — 网站性能监控。14 天免费试用。
  * [Prometheus](https://prometheus.io/) — 监控系统和时间序列数据库。开源免费。
  * [Raygun](https://raygun.com/) — 错误、崩溃和性能监控。14 天免费试用。
  * [Runscope](https://www.runscope.com/) — API 监控和测试。14 天免费试用。
  * [Scout APM](https://scoutapm.com/) — 应用程序性能监控。免费计划包括每月 10k 事务。
  * [Sematext](https://sematext.com/) — 监控和日志管理。免费计划包括每天 500MB。
  * [Sentry](https://sentry.io/) — 错误跟踪和性能监控。免费计划包括每月 5k 事件。
  * [Site24x7](https://www.site24x7.com/) — 网站监控。免费计划包括 5 个监视器。
  * [Skylight](https://www.skylight.io/) — Rails 应用程序性能分析。免费计划包括每月 100k 请求。
  * [SpeedCurve](https://speedcurve.com/) — 前端性能监控。免费试用。
  * [StatusCake](https://www.statuscake.com/) — 网站正常运行时间监控。免费计划包括 10 个监视器。
  * [Statuspage](https://www.statuspage.io/) — 状态页面托管。免费计划包括 100 个订阅者。
  * [ThousandEyes](https://www.thousandeyes.com/) — 网络智能平台。免费试用。
  * [Uptime Robot](https://uptimerobot.com/) — 网站正常运行时间监控。免费计划包括 50 个监视器。
  * [Zabbix](https://www.zabbix.com/) — 企业级监控。开源免费。

**[⬆️ 回到顶部](#目录)**

## 崩溃和异常处理

  * [Airbrake](https://airbrake.io/) — 错误监控。30 天免费试用。
  * [AppCenter](https://appcenter.ms/) — 持续构建、测试、发布和监控应用程序。免费计划包括每月 240 分钟构建时间。
  * [Bugsnag](https://www.bugsnag.com/) — 错误监控。免费计划包括每月 7.5k 事件。
  * [Crashlytics](https://firebase.google.com/products/crashlytics) — 崩溃报告（现已合并到 Firebase）。免费。
  * [Honeybadger](https://www.honeybadger.io/) — 异常监控。免费计划包括每月 12k 错误。
  * [Raygun](https://raygun.com/) — 错误、崩溃和性能监控。14 天免费试用。
  * [Rollbar](https://rollbar.com/) — 错误监控。免费计划包括每月 5,000 个事件。
  * [Sentry](https://sentry.io/) — 错误跟踪和性能监控。免费计划包括每月 5k 事件。

**[⬆️ 回到顶部](#目录)**

## 搜索

  * [Algolia](https://www.algolia.com/) — 托管的搜索引擎。免费计划包括每月 10k 条记录和 100k 次操作。
  * [Bonsai](https://bonsai.io/) — 托管的 Elasticsearch。免费计划包括 1 个节点和 1GB 存储。
  * [Elastic Cloud](https://www.elastic.co/cloud/) — 托管的 Elasticsearch。免费试用。
  * [Komo](https://komo.ai/) — AI 搜索引擎。免费。
  * [MeiliSearch](https://www.meilisearch.com/) — 开源搜索引擎。自托管免费。
  * [Searchly](https://www.searchly.com/) — 托管的 Elasticsearch。免费计划包括 2 个索引和 5MB 存储。
  * [Typesense](https://typesense.org/) — 开源搜索引擎。自托管免费。
  * [ZincSearch](https://zincsearch.com/) — 开源搜索引擎。自托管免费。

**[⬆️ 回到顶部](#目录)**

## 教育和职业发展

  * [Codecademy](https://www.codecademy.com/) — 交互式编程课程。免费课程可用。
  * [Codewars](https://www.codewars.com/) — 编程挑战。免费。
  * [Coursera](https://www.coursera.org/) — 在线课程。免费旁听。
  * [edX](https://www.edx.org/) — 在线课程。免费旁听。
  * [Exercism](https://exercism.org/) — 编程练习和指导。免费。
  * [freeCodeCamp](https://www.freecodecamp.org/) — 编程课程和认证。免费。
  * [HackerRank](https://www.hackerrank.com/) — 编程挑战和竞赛。免费。
  * [Khan Academy](https://www.khanacademy.org/) — 在线教育。免费。
  * [LeetCode](https://leetcode.com/) — 编程面试准备。免费问题可用。
  * [MIT OpenCourseWare](https://ocw.mit.edu/) — MIT 课程材料。免费。
  * [Udacity](https://www.udacity.com/) — 在线课程。免费课程可用。
  * [Udemy](https://www.udemy.com/) — 在线课程。免费课程可用。

**[⬆️ 回到顶部](#目录)**

## 电子邮件

  * [10 Minute Mail](https://10minutemail.com/) — 临时电子邮件地址。免费。
  * [AnonAddy](https://anonaddy.com/) — 匿名电子邮件转发。免费计划包括无限别名。
  * [Brevo](https://www.brevo.com/) — 电子邮件营销平台。免费计划包括每天 300 封电子邮件。
  * [Burner Mail](https://burnermail.io/) — 临时电子邮件地址。免费计划包括 5 个燃烧器地址。
  * [Buttondown](https://buttondown.email/) — 电子邮件通讯工具。免费计划包括 1,000 个订阅者。
  * [CleverReach](https://www.cleverreach.com/) — 电子邮件营销平台。免费计划包括每月 1,000 封电子邮件和 250 个收件人。
  * [CloudMailin](https://www.cloudmailin.com/) — 接收电子邮件作为 HTTP POST。免费计划包括每月 200 封电子邮件。
  * [Contact.do](https://contact.do/) — 简单的联系表单。免费。
  * [ConvertKit](https://convertkit.com/) — 电子邮件营销平台。免费计划包括 1,000 个订阅者。
  * [DebugMail](https://debugmail.io/) — 电子邮件调试工具。免费。
  * [Elastic Email](https://elasticemail.com/) — 电子邮件发送服务。免费计划包括每天 100 封电子邮件。
  * [EmailOctopus](https://emailoctopus.com/) — 电子邮件营销平台。免费计划包括 2,500 个订阅者和每月 10,000 封电子邮件。
  * [Forward Email](https://forwardemail.net/) — 电子邮件转发服务。开源免费。
  * [Gmail](https://www.google.com/gmail/) — 免费电子邮件服务。15GB 存储空间。
  * [ImprovMX](https://improvmx.com/) — 电子邮件转发服务。免费计划包括 1 个域名和 25 个别名。
  * [Inbound](https://www.inbound.net/) — 电子邮件解析服务。免费。
  * [Mailchimp](https://mailchimp.com/) — 电子邮件营销平台。免费计划包括 500 个联系人和每月 1,000 封电子邮件。
  * [MailerLite](https://www.mailerlite.com/) — 电子邮件营销平台。免费计划包括 1,000 个订阅者和每月 12,000 封电子邮件。
  * [Mailgun](https://www.mailgun.com/) — 电子邮件 API。免费试用。
  * [Mailjet](https://www.mailjet.com/) — 电子邮件发送服务。免费计划包括每天 200 封电子邮件。
  * [Mailtrap](https://mailtrap.io/) — 电子邮件测试工具。免费计划包括每月 500 封电子邮件。
  * [Moosend](https://moosend.com/) — 电子邮件营销平台。30 天免费试用。
  * [Omnisend](https://www.omnisend.com/) — 电子邮件和短信营销。免费计划包括每月 500 封电子邮件。
  * [Outlook](https://outlook.live.com/) — 免费电子邮件服务。15GB 存储空间。
  * [Pepipost](https://pepipost.com/) — 电子邮件发送服务。免费计划包括每天 100 封电子邮件。
  * [Phistank](https://www.phishtank.com/) — 反网络钓鱼数据库。免费。
  * [Postmark](https://postmarkapp.com/) — 电子邮件发送服务。免费计划包括每月 100 封电子邮件。
  * [ProtonMail](https://protonmail.com/) — 加密电子邮件服务。免费计划包括 500MB 存储空间。
  * [SendGrid](https://sendgrid.com/) — 电子邮件发送服务。免费计划包括每天 100 封电子邮件。
  * [Sendinblue](https://www.sendinblue.com/) — 电子邮件营销平台。免费计划包括每天 300 封电子邮件。
  * [SendPulse](https://sendpulse.com/) — 多渠道营销平台。免费计划包括 500 个订阅者和每月 15,000 封电子邮件。
  * [SimpleLogin](https://simplelogin.io/) — 电子邮件别名服务。免费计划包括 15 个别名。
  * [SparkPost](https://www.sparkpost.com/) — 电子邮件发送服务。免费计划包括每月 500 封电子邮件。
  * [Substack](https://substack.com/) — 通讯发布平台。免费。
  * [Temp Mail](https://temp-mail.org/) — 临时电子邮件地址。免费。
  * [TinyLetter](https://tinyletter.com/) — 简单的通讯工具。免费。
  * [Tutanota](https://tutanota.com/) — 加密电子邮件服务。免费计划包括 1GB 存储空间。
  * [Yandex.Mail](https://mail.yandex.com/) — 免费电子邮件服务。10GB 存储空间。
  * [Zoho Mail](https://www.zoho.com/mail/) — 电子邮件托管。免费计划包括 5 个用户和 5GB 存储空间/用户。

**[⬆️ 回到顶部](#目录)**

## 功能切换管理平台

  * [App Config](https://aws.amazon.com/systems-manager/features/appconfig/) — 托管的功能标志。免费。
  * [ConfigCat](https://configcat.com/) — 功能标志服务。免费计划包括每月 10 个标志。
  * [Flagsmith](https://flagsmith.com/) — 开源功能标志。免费计划包括每月 50k 请求。
  * [GrowthBook](https://www.growthbook.io/) — 开源功能标志。自托管免费。
  * [LaunchDarkly](https://launchdarkly.com/) — 功能标志管理。30 天免费试用。
  * [Molasses](https://molasses.app/) — 功能标志服务。免费计划包括每月 10k 请求。
  * [Split](https://www.split.io/) — 功能标志和实验平台。免费计划包括 10 个席位。
  * [Toggles](https://toggles.dev/) — 功能标志服务。免费计划包括每月 10k 请求。
  * [Unleash](https://www.getunleash.io/) — 开源功能标志。自托管免费。

**[⬆️ 回到顶部](#目录)**

## 字体

  * [DaFont](https://www.dafont.com/) — 免费字体下载。
  * [FontAwesome](https://fontawesome.com/) — 图标字体。免费版可用。
  * [FontFabric](https://www.fontfabric.com/) — 免费字体。
  * [FontSquirrel](https://www.fontsquirrel.com/) — 免费商业字体。
  * [Google Fonts](https://fonts.google.com/) — 免费开源字体。
  * [Nerd Fonts](https://www.nerdfonts.com/) — 开发者字体。免费。
  * [Use & Modify](https://usemodify.com/) — 开源字体。免费。

**[⬆️ 回到顶部](#目录)**

## 表单

  * [123FormBuilder](https://www.123formbuilder.com/) — 在线表单构建器。免费计划包括 5 个表单。
  * [99Inbound](https://99inbound.com/) — 表单构建器。免费计划包括 2 个表单。
  * [Arengu](https://arengu.com/) — 表单构建器。免费计划包括每月 1,000 次提交。
  * [Cognito Forms](https://www.cognitoforms.com/) — 表单构建器。免费计划包括每月 500 个条目。
  * [FormAssembly](https://www.formassembly.com/) — 表单构建器。14 天免费试用。
  * [Formbold](https://formbold.com/) — 表单 API 和无服务器表单后端。免费计划包括每月 100 次提交。
  * [Formcarry](https://formcarry.com/) — 表单后端。免费计划包括每月 100 次提交。
  * [Formik](https://formik.org/) — React 表单库。开源免费。
  * [FormKeep](https://formkeep.com/) — 表单后端。免费计划包括每月 50 次提交。
  * [Formspree](https://formspree.io/) — 表单后端。免费计划包括每月 50 次提交。
  * [FormSubmit](https://formsubmit.co/) — 表单后端。免费无限。
  * [Getform](https://getform.io/) — 表单后端。免费计划包括每月 50 次提交。
  * [HeroTofu](https://herotofu.com/) — 表单后端。免费计划包括每月 100 次提交。
  * [HeyForm](https://heyform.net/) — 在线表单构建器。免费计划包括无限表单。
  * [JotForm](https://www.jotform.com/) — 表单构建器。免费计划包括每月 100 次提交。
  * [KwesForms](https://kwesforms.com/) — 表单后端。免费计划包括每月 50 次提交。
  * [Pageclip](https://pageclip.co/) — 表单后端。免费计划包括每月 1,000 次提交。
  * [Paperform](https://paperform.co/) — 表单构建器。14 天免费试用。
  * [Slapform](https://slapform.com/) — 表单后端。免费计划包括每月 100 次提交。
  * [SmartForms](https://smartforms.dev/) — 表单后端。免费计划包括每月 50 次提交。
  * [StaticForms](https://www.staticforms.xyz/) — 表单后端。免费无限。
  * [SurveyJS](https://surveyjs.io/) — 调查库。开源免费。
  * [Tally](https://tally.so/) — 表单构建器。免费无限。
  * [Typeform](https://www.typeform.com/) — 表单构建器。免费计划包括每月 10 个响应。
  * [Wufoo](https://www.wufoo.com/) — 表单构建器。免费计划包括 5 个表单。
  * [Yakforms](https://yakforms.org/) — 自托管表单构建器。开源免费。

**[⬆️ 回到顶部](#目录)**

## 生成式 AI

  * [Blackbox](https://www.blackbox.ai/) — AI 编码助手。免费。
  * [ChatGPT](https://chat.openai.com/) — AI 聊天机器人。免费研究预览版。
  * [Claude](https://claude.ai/) — AI 助手。免费 beta 版。
  * [Codeium](https://codeium.com/) — 免费的 AI 代码补全和聊天工具。
  * [Copilot](https://github.com/features/copilot) — AI 编码助手。学生和开源维护者免费。
  * [DeepL](https://www.deepl.com/) — AI 翻译工具。免费版可用。
  * [Gemini](https://gemini.google.com/) — Google 的 AI 助手。免费。
  * [Hugging Face](https://huggingface.co/) — AI 模型和数据集平台。免费。
  * [Midjourney](https://www.midjourney.com/) — AI 图像生成器。免费试用（有时不可用）。
  * [Perplexity](https://www.perplexity.ai/) — AI 搜索引擎。免费。
  * [Phind](https://www.phind.com/) — 专为开发者设计的 AI 搜索引擎。
  * [Poe](https://poe.com/) — AI 聊天机器人聚合器。免费。
  * [Replicate](https://replicate.com/) — 运行 AI 模型。免费试用。
  * [Stable Diffusion](https://stability.ai/) — AI 图像生成模型。开源免费。

**[⬆️ 回到顶部](#目录)**

## CDN 和保护

  * [ArvanCloud](https://www.arvancloud.com/) — CDN 和云安全。免费计划包括每月 200GB 流量。
  * [CacheFly](https://www.cachefly.com/) — CDN 服务。免费计划包括每月 5TB 流量（开发者）。
  * [Cloudflare](https://www.cloudflare.com/) — 免费的 SSL、DDoS 保护和 CDN。
  * [Cloudinary](https://cloudinary.com/) — 图像和视频管理。免费计划包括每月 25 个积分。
  * [Fastly](https://www.fastly.com/) — 边缘云平台。免费试用。
  * [Gcore](https://gcore.com/) — CDN 和云服务。免费计划包括每月 1TB 流量。
  * [Gumlet](https://www.gumlet.com/) — 视频托管和优化。免费计划包括每月 250GB 带宽。
  * [ImageKit](https://imagekit.io/) — 图像优化和 CDN。免费计划包括每月 20GB 带宽。
  * [Imgix](https://www.imgix.com/) — 图像处理和 CDN。免费计划包括每月 1,000 张主图像。
  * [JSDelivr](https://www.jsdelivr.com/) — 开源 CDN。免费。
  * [KeyCDN](https://www.keycdn.com/) — CDN 服务。免费试用。
  * [LightCDN](https://lightcdn.com/) — CDN 服务。免费计划包括每月 100GB 流量。
  * [Netlify](https://www.netlify.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [PageCDN](https://pagecdn.com/) — CDN 服务。免费计划包括每月 50GB 流量。
  * [Sirv](https://sirv.com/) — 图像 CDN。免费计划包括每月 500MB 存储。
  * [Statically](https://statically.io/) — 静态资产 CDN。免费。
  * [TwicPics](https://www.twicpics.com/) — 图像 CDN。免费计划包括每月 3GB 带宽。
  * [Uploadcare](https://uploadcare.com/) — 文件上传和 CDN。免费计划包括每月 300MB 存储。
  * [Vercel](https://vercel.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [Wesco](https://wesco.io/) — 图像 CDN。免费计划包括每月 1GB 带宽。

**[⬆️ 回到顶部](#目录)**

## 平台即服务 (PaaS)

  * [Acquia](https://www.acquia.com/) — 托管 Drupal 站点。开发人员免费沙盒环境。
  * [Appwrite](https://appwrite.io/) — 开源后端服务器。自托管免费。
  * [Back4App](https://www.back4app.com/) — 基于 Parse 的后端即服务。免费计划包括每月 10k 请求。
  * [Clever Cloud](https://www.clever-cloud.com/) — PaaS 平台。免费试用。
  * [Cloud 66](https://www.cloud66.com/) — 个人项目免费（包括一个部署服务器，一个静态站点），Cloud 66 为您提供在任何云上构建、部署和扩展应用程序所需的一切，而无需为“服务器事务”头疼。
  * [Coherence](https://www.coherence.com/) — 全栈开发平台。免费计划包括 1 个应用程序。
  * [Cyclic](https://www.cyclic.sh/) — 全栈应用程序托管。免费计划包括 1 个应用程序。
  * [Deta](https://www.deta.sh/) — 免费的云平台。无限应用程序和数据库。
  * [Dokku](https://dokku.com/) — Docker 驱动的 PaaS。自托管免费。
  * [Engine Yard](https://www.engineyard.com/) — Ruby on Rails PaaS。免费试用。
  * [Fly.io](https://fly.io/) — 全球应用程序平台。免费计划包括每月 3 个共享 CPU VM。
  * [Ggigalixir](https://gigalixir.com/) — Elixir PaaS。免费层级可用。
  * [Glitch](https://glitch.com/) — 构建和托管 Web 应用程序。免费。
  * [Google App Engine](https://cloud.google.com/appengine) — 托管的应用程序平台。免费层级可用。
  * [Hasura](https://hasura.io/) — GraphQL 引擎。免费计划包括每月 1GB 数据传输。
  * [Heroku](https://www.heroku.com/) — 应用程序平台。不再提供免费计划（除了学生）。
  * [Koyeb](https://www.koyeb.com/) — 无服务器平台。免费计划包括每月 5.50 美元的积分。
  * [Meteor Cloud](https://www.meteor.com/cloud) — Meteor 应用程序托管。免费计划包括 1 个容器。
  * [Mogenius](https://mogenius.com/) — 云开发平台。免费计划包括 1 个服务。
  * [Netlify](https://www.netlify.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [Northflank](https://northflank.com/) — 全栈云平台。免费计划包括 1 个服务。
  * [Platform.sh](https://platform.sh/) — 持续部署云托管。30 天免费试用。
  * [Porter](https://porter.run/) — Kubernetes 上的 PaaS。免费计划包括 1 个集群。
  * [PythonAnywhere](https://www.pythonanywhere.com/) — Python 托管。免费计划包括 1 个 Web 应用程序。
  * [Railway](https://railway.app/) — 基础设施平台。免费计划包括每月 5 美元的积分。
  * [Render](https://render.com/) — 统一云平台。免费计划包括静态站点和服务。
  * [Replit](https://replit.com/) — 在线 IDE 和托管。免费计划可用。
  * [Supabase](https://supabase.com/) — 开源 Firebase 替代品。免费计划包括 500MB 数据库。
  * [Surge](https://surge.sh/) — 静态 Web 发布。免费。
  * [Tsuru](https://tsuru.io/) — 开源 PaaS。自托管免费。
  * [Vercel](https://vercel.com/) — 静态站点和无服务器函数的部署平台。个人免费。
  * [Virtuozzo](https://www.virtuozzo.com/) — 应用程序平台。免费试用。

**[⬆️ 回到顶部](#目录)**

## 设计和 UI

  * [AllTheFreeStock](https://allthefreestock.com) — 免费库存图片、音频和视频的精选列表。
  * [Ant Design Landing Page](https://landing.ant.design/) — Ant Design Landing Page 提供由 Ant Motion 运动组件构建的模板。
  * [Backlight](https://backlight.dev/) — 团队构建、记录、发布、扩展和维护设计系统的完整编码平台。免费计划允许最多 3 名编辑者。
  * [BoxySVG](https://boxy-svg.com/app) — 用于绘制 SVG 并导出为 SVG、PNG、jpeg 和其他格式的免费可安装 Web 应用程序。
  * [Branition](https://branition.com/colors) — 最适合品牌的手工策划调色板。
  * [Carousel Hero](https://carouselhero.com/) — 免费在线工具，用于创建社交媒体轮播。
  * [Circum Icons](https://circumicons.com) — 一致的开源图标，例如用于 React、Vue 和 Svelte 的 SVG。
  * [clevebrush.com](https://www.cleverbrush.com/) — 免费图形设计/照片拼贴应用程序。
  * [cloudconvert.com](https://cloudconvert.com/) — 将任何内容转换为任何内容。支持 208 种格式。
  * [CMYK Pantone](https://www.cmyktopantone.com/) — 轻松将 CMYK 值转换为最接近的 Pantone 颜色。
  * [CodeMyUI](https://codemyui.com) — 带有代码片段的 Web 设计和 UI 灵感精选集。
  * [ColorKit](https://colorkit.co/) — 在线创建调色板或从顶级调色板中获取灵感。
  * [colorr.me](https://colorr.me/) — 颜色和渐变生成器。
  * [coolors](https://coolors.co/) — 调色板生成器。免费。
  * [css-gradient.com](https://www.css-gradient.com/) — 快速生成自定义跨浏览器 CSS 渐变的免费工具。
  * [DaisyUI](https://daisyui.com/) — 免费。使用 Tailwind CSS 但编写更少的类名。
  * [easyvectors.com](https://easyvectors.com/) — 免费 SVG 矢量艺术库存。
  * [figma.com](https://www.figma.com) — 团队的在线协作设计工具；免费层级包括无限文件和查看者。
  * [Float UI](https://floatui.com/) — 免费 Web 开发工具，用于快速创建现代、响应式网站。
  * [Flyon UI](https://flyonui.com/) — Tailwind CSS 的最简单组件库。
  * [framer.com](https://www.framer.com/) — Framer 帮助您迭代和动画化界面创意。
  * [freeforcommercialuse.net](https://freeforcommercialuse.net/) — FFCU 无忧模型/财产发布库存照片。
  * [Glyphs](https://glyphs.fyi/) — 免费、完全可编辑且真正的开源设计系统。
  * [Gradientos](https://www.gradientos.app) — 快速轻松地选择渐变。
  * [Grapedrop](https://grapedrop.com/) — 基于 GrapesJS 框架的响应式网页构建器。前 5 页免费。
  * [haikei.app](https://www.haikei.app/) — 生成独特 SVG 形状、背景和图案的 Web 应用程序。
  * [HyperUI](https://www.hyperui.dev/) — 免费开源 Tailwind CSS 组件。
  * [hypercolor.dev](https://hypercolor.dev/) — Tailwind CSS 颜色渐变的精选集。
  * [Icon Horse](https://icon.horse) — 从简单的 API 获取任何网站的最高分辨率图标。
  * [Iconify](https://icon-sets.iconify.design/) — 超过 100 个图标包的集合，具有统一的界面。
  * [Iconoir](https://iconoir.com) — 具有数千个图标的开源图标库。
  * [Icons8](https://icons8.com) — 图标、插图、照片、音乐和设计工具。
  * [Image BG Blurer](https://imagebgblurer.com/) — 为图像生成模糊背景框。
  * [landen.co](https://www.landen.co) — 生成、编辑和发布漂亮的网站和登陆页面。
  * [lensdump.com](https://lensdump.com/) — 免费云图像托管。
  * [Logo.dev](https://www.logo.dev) — 公司徽标 API。前 10,000 次 API 调用免费。
  * [Lorem Picsum](https://picsum.photos/) — 免费工具，易于使用，时尚的占位符。
  * [LottieFiles](https://lottiefiles.com/) —世界上最大的动画格式在线平台。
  * [LovelyLanding.net](https://www.lovelylanding.net/) — 经常更新的登陆页面截图。
  * [Lucide](https://lucide.dev) — 免费可定制且一致的 SVG 图标工具包。
  * [Lunacy](https://icons8.com/lunacy) — 具有离线支持的免费图形设计工具。
  * [MagicPattern](https://www.magicpattern.design/tools) — CSS 和 SVG 背景生成器和工具的集合。
  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作。
  * [Mastershot](https://mastershot.app) — 完全免费的基于浏览器的视频编辑器。
  * [MDBootstrap](https://mdbootstrap.com/) — 免费用于个人和商业用途的 Bootstrap、Angular、React 和 Vue UI 套件。
  * [Mindmup.com](https://www.mindmup.com/) — 免费无限思维导图并将其存储在云端。
  * [Mockplus iDoc](https://www.mockplus.com/idoc) — 强大的设计协作和交付工具。
  * [mockupmark.com](https://mockupmark.com/create/free) — 创建逼真的 T 恤和服装模型。
  * [Modeldraw.com](https://modeldraw.com) — 完整的图表平台，包括 UML、系统架构、流程图等。
  * [Mossaik](https://mossaik.app) — 免费 SVG 图像生成器。
  * [movingpencils.com](https://movingpencils.com) — 快速、基于浏览器的矢量编辑器。
  * [NextUI](https://nextui.org/) — 免费。美观、快速且现代的 React 和 Next.js UI 库。
  * [Octopus.do](https://octopus.do) — 可视化站点地图构建器。
  * [okso.app](https://okso.app) — 极简在线绘图应用程序。
  * [Pencil](https://github.com/evolus/pencil) — 使用 Electron 的开源设计工具。
  * [Penpot](https://penpot.app) — 基于 Web 的开源设计和原型制作工具。
  * [pexels.com](https://www.pexels.com/) — 用于商业用途的免费库存照片。
  * [photopea.com](https://www.photopea.com) — 免费、高级的在线设计编辑器。
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜的独特图形和图像。
  * [pixlr.com](https://pixlr.com/) — 免费在线浏览器编辑器。
  * [Plasmic](https://www.plasmic.app/) — 快速、易于使用的 Web 设计工具和页面构建器。
  * [PNG to WebP Converter](https://pngtowebpconverter.com/) — 直接在浏览器中将 PNG 图像转换为 WebP 图像。
  * [Pravatar](https://pravatar.cc/) — 生成随机/占位符假头像。
  * [Proto.io](https://www.proto.io) — 无需编码即可创建完全交互式的 UI 原型。
  * [Quant Ux](https://quant-ux.com/) — 原型和设计工具。
  * [resizeappicon.com](https://resizeappicon.com/) — 调整和管理应用程序图标大小的简单服务。
  * [Responsively App](https://responsively.app) — 用于更快、更精确的响应式 Web 应用程序开发的免费开发工具。
  * [Rive](https://rive.app) — 创建并向任何平台发布精美的动画。
  * [SceneLab](https://scenelab.io) — 在线模型图形编辑器。
  * [Scrollbar.app](https://scrollbar.app) — 用于为 Web 设计自定义滚动条的简单免费 Web 应用程序。
  * [Shadcn Studio](https://shadcnstudio.com/theme-editor) — 预览不同组件和布局的主题更改。
  * [ShadcnUI](https://ui.shadcn.com/) — 设计精美的组件，您可以将其复制并粘贴到您的应用程序中。
  * [smartmockups.com](https://smartmockups.com/) — 创建产品模型。
  * [storyset.com](https://storyset.com/) — 使用此工具为您的项目创建令人难以置信的免费定制插图。
  * [Superdesigner](https://superdesigner.co) — 免费设计工具集合。
  * [SVG Converter](https://svgconverter.online/) — 免费 JPG/PNG 到 SVG 转换器。
  * [SVGmix.com](https://www.svgmix.com/) — 300K+ 免费 SVG 图标、集合和品牌徽标的海量存储库。
  * [svgrepo.com](https://www.svgrepo.com/) — 探索、搜索并找到最适合您项目的图标或矢量。
  * [tabler-icons.io](https://tabler-icons.io/) — 超过 1500 个免费复制和粘贴 SVG 可编辑图标。
  * [Tailark](https://tailark.com/) — 现代、响应式、预构建 UI 块的集合。
  * [Tailcolors](https://tailcolors.com/) — 美丽的 Tailwind CSS v4 调色板。
  * [Tailkits](https://tailkits.com/) — Tailwind 模板、组件和工具的精选集。
  * [TeleportHQ](https://teleporthq.io/) — 低代码前端设计和开发平台。
  * [tweakcn](https://tweakcn.com/) — shadcn/ui 的精美主题。
  * [TW Elements](https://tw-elements.com/) — 使用 Tailwind CSS 重新创建的免费 Bootstrap 组件。
  * [UI Avatars](https://ui-avatars.com/) — 从名字生成带有首字母的头像。
  * [unDraw](https://undraw.co/) — 不断更新的精美 SVG 图像集合。
  * [Unicorn Platform](https://unicornplatform.com/) — 带有托管的轻松登陆页面构建器。
  * [unsplash.com](https://unsplash.com/) — 用于商业和非商业目的的免费库存照片。
  * [Updrafts.app](https://updrafts.app) — 基于 tailwindcss 的设计的所见即所得网站构建器。
  * [vector.express](https://vector.express) — 快速轻松地转换矢量。
  * [vectr.com](https://vectr.com/) — 适用于 Web + 桌面的免费设计应用程序。
  * [Vertopal](https://www.vertopal.com) — 将文件转换为各种格式的免费在线平台。
  * [walkme.com](https://www.walkme.com/) — 企业级指导和参与平台。
  * [Wdrfree SVG](https://wdrfree.com/free-svg) — 黑白免费 SVG 切割文件。
  * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内 IDE，用于隔离编码 Web 组件。
  * [Webflow](https://webflow.com) — 带有动画和网站托管的所见即所得网站构建器。
  * [Webstudio](https://webstudio.is/) — Webflow 的开源替代品。
  * [whimsical.com](https://whimsical.com/) — 协作流程图、线框图、便签和思维导图。
  * [xLayers](https://xlayers.dev) — 预览 Sketch 设计文件并将其转换为 Angular、React、Vue 等。
  * [Zeplin](https://zeplin.io/) — 设计师和开发人员协作平台。

**[⬆️ 回到顶部](#目录)**

## 地图上的数据可视化

  * [carto.com](https://carto.com/) — 从您的数据和公共数据创建地图和地理空间 API。
  * [Clockwork Micro](https://clockworkmicro.com/) — 像时钟一样工作的地图工具。每月 50,000 次免费查询。
  * [developers.arcgis.com](https://developers.arcgis.com) — 用于 Web、桌面和移动设备的地图、地理空间数据存储、分析、地理编码、路由等的 API 和 SDK。
  * [Foursquare](https://developer.foursquare.com/) — 位置发现、地点搜索和上下文感知内容。
  * [geoapify.com](https://www.geoapify.com/) — 矢量和栅格地图图块、地理编码、地点、路由、等值线 API。每天 3,000 次免费请求。
  * [geocod.io](https://www.geocod.io/) — 通过 API 或 CSV 上传进行地理编码。每天 2,500 次免费查询。
  * [geocodify.com](https://geocodify.com/) — 通过 API 或 CSV 上传进行地理编码和地理分析。每月 10k 免费查询。
  * [Geokeo api](https://geokeo.com) — 具有语言校正等功能的地理编码 API。每天 2,500 次免费查询。
  * [geojs.io](https://www.geojs.io/) — 高可用性 REST/JSON/JSONP IP 地理定位查找 API。
  * [giscloud.com](https://www.giscloud.com/) — 在线可视化、分析和共享地理数据。
  * [graphhopper.com](https://www.graphhopper.com/) — 为路由、路由优化、距离矩阵、地理编码和地图匹配提供免费开发者包。
  * [here](https://developer.here.com/) — 用于地图和位置感知应用程序的 API 和 SDK。每月 250k 笔交易免费。
  * [IP Geolocation](https://ipgeolocation.io/) — 提供免费开发者计划，每月 30K 请求。
  * [ipstack](https://ipstack.com/) — 通过 IP 地址定位和识别网站访问者。
  * [locationiq.com](https://locationiq.com/) — 地理编码、地图和路由 API。每天 5,000 次请求免费。
  * [mapbox.com](https://www.mapbox.com/) — 用于显示地图数据的地图、地理空间服务和 SDK。
  * [maps.stamen.com](http://maps.stamen.com/) — 免费地图图块和图块托管。
  * [maptiler.com](https://www.maptiler.com/cloud/) — 用于地图可视化的矢量地图、地图服务和 SDK。
  * [nextbillion.ai](https://nextbillion.ai/) — 地图相关服务：地理编码、导航、地图 SDK。
  * [nominatim.org](https://nominatim.org/) — OpenStreetMap 的免费地理编码服务。
  * [opencagedata.com](https://opencagedata.com) — 聚合 OpenStreetMap 和其他开放地理来源的地理编码 API。每天 2,500 次免费查询。
  * [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名。
  * [positionstack](https://positionstack.com/) — 全球地点和坐标的免费地理编码。
  * [stadiamaps.com](https://stadiamaps.com/) — 地图图块、路由、导航和其他地理空间 API。每天 2,500 次免费地图视图和 API 请求。

**[⬆️ 回到顶部](#目录)**

## 包构建系统

  * [build.opensuse.org](https://build.opensuse.org/) — 适用于多种发行版（SUSE、EL、Fedora、Debian 等）的包构建服务。
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — 适用于 Fedora 和 EL 的基于 Mock 的 RPM 构建服务。
  * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务。

**[⬆️ 回到顶部](#目录)**

## IDE 和代码编辑

  * [3v4l](https://3v4l.org/) — 免费在线 PHP shell 和代码片段共享网站。
  * [Android Studio](https://developer.android.com/studio) — Android Studio 提供构建 Android 应用程序的最快工具。
  * [AndroidIDE](https://m.androidide.com/) — 用于在 Android 设备上开发真正的、基于 Gradle 的 Android 应用程序的开源 IDE。
  * [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用程序框架。
  * [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API。
  * [BBEdit](https://www.barebones.com/) — BBEdit 是 macOS 上流行且可扩展的编辑器。
  * [Binder](https://mybinder.org/) — 将 Git 仓库转换为交互式笔记本集合。
  * [BlueJ](https://bluej.org) — 专为初学者设计的免费 Java 开发环境。
  * [Bootify.io](https://bootify.io/) — 具有自定义数据库和 REST API 的 Spring Boot 应用程序生成器。
  * [Brackets](http://brackets.io/) — 专为 Web 开发设计的开源文本编辑器。
  * [cacher.io](https://www.cacher.io) — 带有标签并支持 100 多种编程语言的代码片段管理器。
  * [cocalc.com](https://cocalc.com/) — 云端协作计算。
  * [Code::Blocks](https://codeblocks.org) — 免费 Fortran 和 C/C++ IDE。
  * [code.cs50.io](https://code.cs50.io/) — CS50 的 Visual Studio Code。
  * [Codepen.io](https://codepen.io/) — CodePen 是 Web 前端的游乐场。
  * [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preact 等的在线游乐场。
  * [codesnip.com.br](https://codesnip.com.br) — 简单的代码片段管理器。
  * [codiga.io](https://codiga.io/) — 编码助手，让您直接在 IDE 中搜索、定义和重用代码片段。
  * [Cody](https://sourcegraph.com/cody) — 免费 AI 编码助手。
  * [Components.studio](https://webcomponents.dev/) — 隔离编码组件，在故事中可视化它们，测试它们并在 npm 上发布。
  * [Eclipse Che](https://www.eclipse.org/che/) — 基于 Web 和 Kubernetes 原生的 IDE。
  * [fakejson.com](https://fakejson.com/) — FakeJSON 帮助您使用其 API 快速生成虚假数据。
  * [ForgeCode](https://forgecode.dev/) — 适用于 Claude、GPT4 系列、Grok、Deepseek、Gemini 和所有前沿模型的 AI 启用结对程序员。
  * [GetVM](https://getvm.io) — 即时免费 Linux 和 IDE chrome 侧边栏。
  * [ide.goorm.io](https://ide.goorm.io) — 云端全功能 IDE。
  * [JDoodle](https://www.jdoodle.com) — 超过 60 种编程语言的在线编译器和编辑器。
  * [jetbrains.com](https://jetbrains.com/products.html) — 生产力工具、IDE 和部署工具。
  * [jsbin.com](https://jsbin.com) — JS Bin 是另一个前端 Web 的游乐场和代码共享网站。
  * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 Web 的游乐场和代码共享网站。
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) — 一些返回 JSON 格式虚假数据的 REST API 端点。
  * [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是用于快速应用程序开发的 Delphi 兼容跨平台 IDE。
  * [MarsCode](https://www.marscode.com/) — 免费的 AI 驱动的基于云的 IDE。
  * [micro-jaymock](https://micro-jaymock.now.sh/) — 用于生成虚假 JSON 数据的微型 API 模拟微服务。
  * [mockable.io](https://www.mockable.io/) — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务。
  * [mockaroo](https://mockaroo.com/) — Mockaroo 让您生成 CSV、JSON、SQL 和 Excel 格式的逼真测试数据。
  * [Mocklets](https://mocklets.com) — 基于 HTTP 的模拟 API 模拟器。
  * [OneCompiler](https://onecompiler.com/) — 支持 70 多种语言的免费在线编译器。
  * [Paiza](https://paiza.cloud/en/) — 无需设置即可在浏览器中开发 Web 应用程序。
  * [PHPSandbox](https://phpsandbox.io/) — PHP 在线开发环境。
  * [Prepros](https://prepros.io/) — Prepros 可以开箱即用地编译 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript。
  * [Replit](https://replit.com/) — 适用于各种编程语言的云编码环境。
  * [SoloLearn](https://code.sololearn.com) — 非常适合运行代码片段的云编程游乐场。
  * [stackblitz.com](https://stackblitz.com/) — 在线/云代码 IDE，用于创建、编辑和部署全栈应用程序。
  * [Sublime Text](https://www.sublimetext.com/) — Sublime Text 是一个流行、多功能且高度可定制的文本编辑器。
  * [Visual Studio Code](https://code.visualstudio.com/) — 重新定义并优化用于构建和调试现代 Web 和云应用程序的代码编辑器。
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — 全功能 IDE。
  * [VSCodium](https://vscodium.com/) — 社区驱动、无遥测/跟踪且免费许可的 Microsoft 编辑器 VSCode 二进制分发版。
  * [wakatime.com](https://wakatime.com/) — 使用文本编辑器插件量化关于您的编码活动的自我指标。
  * [Wave Terminal](https://waveterm.dev/) — Wave 是一个开源、跨平台的终端，用于无缝工作流程。
  * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内 IDE，用于隔离编码 Web 组件。
  * [WebDB](https://webdb.app) — 免费高效数据库 IDE。
  * [Zed](https://zed.dev/) — Zed 是 Atom 和 Tree-sitter 的创建者推出的高性能多人代码编辑器。

**[⬆️ 回到顶部](#目录)**

## 分析、事件和统计

  * [Axiom](https://axiom.co) — 云原生日志和分析平台。免费层级包括 0.5 TB 的摄取和 30 天的保留。
  * [Beamanalytics.io](https://beamanalytics.io) — 免费 Google Analytics 替代品。每月最多 100k 页面浏览量免费。
  * [Cauldron](https://cauldron.io/) — 免费的开源解决方案，用于分析您的用户和社区。
  * [clarity.microsoft.com](https://clarity.microsoft.com/) — 免费分析，帮助您了解用户如何与您的网站互动。
  * [Clicky](https://clicky.com/) — 网站分析平台。免费计划允许每天 3,000 次页面浏览量。
  * [counter.dev](https://counter.dev/) — 尊重隐私的开源 Web 分析。免费。
  * [Databox](https://databox.com/) — 业务分析平台，将数据集中在一个地方。免费计划有 3 个数据源用户和每天刷新。
  * [Expresso](https://expresso.store/) — 适用于移动应用程序的免费、注重隐私的分析。
  * [GoatCounter](https://www.goatcounter.com/) — 免费开源 Web 分析。注重隐私。每月 100k 页面浏览量免费。
  * [Google Analytics](https://marketingplatform.google.com/about/analytics/) — Google Analytics。
  * [Hardal](https://hardal.io) — 免费、注重隐私的 Web 分析。
  * [Heap](https://heap.io) — 自动捕获 iOS、Android、Web 上的每一次用户操作。每月最多 10k 会话免费。
  * [Hotjar](https://www.hotjar.com/) — 网站热图和行为分析工具。每天 2,000 次页面浏览量免费。
  * [Improvado](https://improvado.io/) — 营销人员的 ETL 平台。
  * [InfoCaptor](https://www.infocaptor.com/free-dashboard-software) — 免费仪表板软件。
  * [Inspectlet](https://www.inspectlet.com/) — 记录 1,000 个会话/月免费。
  * [Keen.io](https://keen.io/) — 用于数据收集、分析和可视化的自定义分析。每月 1,000 个事件流免费。
  * [LogSpot](https://logspot.io) — 具有自动化功能的 Web 分析平台。每月 100k 页面浏览量免费。
  * [Mixpanel](https://mixpanel.com/) — 移动和 Web 分析。每月 100k 跟踪用户免费。
  * [Moesif](https://www.moesif.com/) — API 分析（REST、GraphQL 等）。每月 500k 事件免费。
  * [Open Web Analytics](https://www.openwebanalytics.com/) — Google Analytics 的开源替代品。
  * [Panelbear](https://panelbear.com/) — 免费、快速且注重隐私的网站分析。每月 1,000 次页面浏览量免费。
  * [Plausible](https://plausible.io/) — 简单且注重隐私的 Web 分析。自托管免费。
  * [PostHog](https://posthog.com/) — 免费开源产品分析。每月 100 万个事件免费。
  * [Rakam](https://rakam.io/) — 自定义分析平台。自托管免费。
  * [Segment](https://segment.com/) — 客户数据平台 (CDP)。每月 1,000 个访客免费。
  * [Sematext](https://sematext.com/experience/) — 网站和 API 监控。每月 50k 页面浏览量免费。
  * [Sentry](https://sentry.io/) — 应用程序监控和错误跟踪。每月 5k 个错误事件免费。
  * [Smartlook](https://www.smartlook.com/) — 记录用户在网站和移动应用程序上的操作。每月 1,500 个会话免费。
  * [Splitbee](https://splitbee.io/) — 转换优化的分析。每月 2,500 个访客免费。
  * [StatCounter](https://statcounter.com/) — 网站流量分析。最近 500 次页面浏览量免费。
  * [Umami](https://umami.is/) — 简单、快速、注重隐私的 Google Analytics 替代品。自托管免费。
  * [Usetiful](https://www.usetiful.com/) — 用户引导和产品采用平台。每月 2,000 次辅助免费。
  * [Visualping](https://visualping.io/) — 网站变更监控。每月 65 次检查免费。
  * [Woopra](https://www.woopra.com/) — 客户旅程分析。每月 500k 个动作免费。
  * [Yandex.Metrica](https://metrica.yandex.com/) — 免费且无限制的 Web 分析。

**[⬆️ 回到顶部](#目录)**

## 访客会话录制

  * [FullStory](https://www.fullstory.com/) — 1,000 个会话/月免费。
  * [Hotjar](https://www.hotjar.com/) — 每天 35 个会话免费。
  * [Inspectlet](https://www.inspectlet.com/) — 1,000 个会话/月免费。
  * [LogRocket](https://logrocket.com/) — 每月 1,000 个会话免费。
  * [Mouseflow](https://mouseflow.com/) — 每月 100 个会话免费。
  * [OpenReplay](https://openreplay.com/) — 开源会话重播套件。每月 1,000 个会话免费。
  * [Smartlook](https://www.smartlook.com/) — 移动应用程序和网站的免费会话记录。每月 1,500 个会话免费。

**[⬆️ 回到顶部](#目录)**

## 国际手机号码验证 API 和 SDK

  * [cognalys.com](https://www.cognalys.com/) — 通过未接来电验证手机号码。免费增值。
  * [numverify.com](https://numverify.com/) — 全球电话号码验证和查找 JSON API。每月 250 次验证 API 请求。
  * [textlocal.com](https://www.textlocal.com/) — 仅限英国。免费发送测试短信。
  * [veriphone.io](https://veriphone.io/) — 全球电话号码验证 JSON API。每月 1,000 次请求免费。

**[⬆️ 回到顶部](#目录)**

## 支付和计费集成

  * [Adapty](https://adapty.io/) — 具有内置 A/B 测试的应用程序内购买集成。每月高达 $10k 的收入免费。
  * [Chargebee](https://www.chargebee.com/) — 订阅计费和收入运营。首个 $100k 收入免费。
  * [CurrencyFreaks](https://currencyfreaks.com/) — 提供当前和历史汇率。每月 1,000 次请求免费。
  * [Exchangerate.host](https://exchangerate.host/) — 免费且无限制的外汇汇率和加密货币汇率 API。
  * [Foxy.io](https://foxy.io/) — 自定义购物车和结账。无限制免费开发。
  * [Glassfy](https://glassfy.io/) — 基础设施构建和增长订阅收入。每月高达 $10k 的收入免费。
  * [Mailchimp Open Commerce](https://mailchimp.com/developer/open-commerce/) — 以前是 Reaction Commerce。开源 API 优先的模块化商务堆栈。
  * [Mollie](https://www.mollie.com/en) — 支付 API。仅按交易付费。
  * [Paddle](https://paddle.com/) — 专注于 B2B SaaS 的支付基础设施。仅按交易付费。
  * [PayPal](https://developer.paypal.com/) — 支付处理。仅按交易付费。
  * [RevenueCat](https://www.revenuecat.com/) — 应用程序内订阅计费基础设施。每月高达 $10k 的收入免费。
  * [Square](https://squareup.com/us/en/developers) — 支付处理。仅按交易付费。
  * [Stripe](https://stripe.com/) — 支付处理。仅按交易付费。
  * [Trolley](https://trolley.com/) — 全球支付平台。免费试用。
  * [VAT API](https://vatapi.com/) — 欧盟增值税号验证。每月 100 次请求免费。
  * [Zota](https://zota.com/) — 支付处理。仅按交易付费。

**[⬆️ 回到顶部](#目录)**

## Docker 相关

  * [Canister.io](https://canister.io/) — 20 个免费私人仓库，用于构建和存储 Docker 镜像。
  * [Docker Hub](https://hub.docker.com/) — 一个免费私人仓库和无限公共仓库，用于构建和存储 Docker 镜像。
  * [Play with Docker](https://labs.play-with-docker.com/) — 简单、交互式且有趣的游乐场，用于学习 Docker。
  * [quay.io](https://quay.io/) — 构建和存储容器镜像。无限免费公共仓库。

**[⬆️ 回到顶部](#目录)**

## Vagrant 相关

  * [Vagrant Cloud](https://app.vagrantup.com/boxes/search) — HashiCorp Vagrant Cloud。Vagrant box 托管。

**[⬆️ 回到顶部](#目录)**

## 开发者博客网站

  * [Dev.to](https://dev.to) — 程序员分享想法并互相帮助成长的社区。
  * [Hashnode](https://hashnode.com) — 适合开发者和超级开发者的无忧博客软件。
  * [Medium](https://medium.com) — 智能阅读和写作的地方。

**[⬆️ 回到顶部](#目录)**

## 评论平台

  * [Cusdis](https://cusdis.com) — 开源、轻量级（5kb gzip）、注重隐私的 Disqus 替代品。免费托管版本。
  * [Disqus](https://disqus.com/) — 帮助发布者建立受众、货币化并参与讨论。
  * [GraphComment](https://graphcomment.com/) — 评论平台，帮助您建立活跃的社区。
  * [HyperComments](https://www.hypercomments.com/) — 博客的实时评论和小部件。
  * [IntenseDebate](https://www.intensedebate.com/) — 功能丰富的评论系统，适用于 WordPress、Blogger、Tumblr 和许多其他 CMS。
  * [ReplyBox](https://replybox.com) — 简单、注重隐私的评论系统。免费计划每月最多 10k 页面浏览量。
  * [Utterances](https://utteranc.es/) — 基于 GitHub issues 构建的轻量级评论小部件。用于开源博客、文档和维基。

**[⬆️ 回到顶部](#目录)**

## 截图 API

  * [ApiFlash](https://apiflash.com/) — 基于 Chrome 和 AWS Lambda 的截图 API。每月 100 次截图免费。
  * [microlink.io](https://microlink.io/) — 将任何链接转换为数据。每天 50 次请求免费。
  * [ScreenshotAPI.net](https://screenshotapi.net/) — 截图 API。每月 100 次截图免费。
  * [ScreenshotMachine](https://www.screenshotmachine.com/) — 捕获在线网站的截图。每月 100 次截图免费。
  * [screenshotone.com](https://screenshotone.com/) — 截图 API。每月 300 次截图免费。
  * [urlbox.io](https://urlbox.io/) — 截图即服务 API。每月 50 次截图免费。
  * [URL2PNG](https://www.url2png.com/) — 截图即服务 API。每月 50 次截图免费。

**[⬆️ 回到顶部](#目录)**

## Flutter 相关和无需 Mac 构建 iOS 应用程序

  * [Codemagic](https://codemagic.io/) — 免费 500 分钟/月构建时间。
  * [FlutLab](https://flutlab.io/) — 在线 Flutter IDE。免费。
  * [FlutterFlow](https://flutterflow.io/) — 用于构建原生移动应用程序的 UI 构建器。免费。

**[⬆️ 回到顶部](#目录)**

## 用 Javascript 编写的基于浏览器的硬件仿真

  * [Box86](https://github.com/ptitSeb/box86) — Linux 用户空间 x86 模拟器。
  * [JSLinux](https://bellard.org/jslinux/) — 在浏览器中运行 Linux 和其他操作系统。
  * [Pce.js](https://jamesfriend.com.au/pce-js/) — 浏览器中的经典 Mac OS。
  * [v86](https://copy.sh/v86/) — 在浏览器中进行 x86 虚拟化，能够运行各种操作系统。

**[⬆️ 回到顶部](#目录)**

## 隐私管理

  * [Bear](https://bear.com) — 帮助您遵守 GDPR、CCPA 等的隐私合规平台。
  * [Breezedocs](https://breezedocs.com) — 帮助您遵守 GDPR、CCPA 等的隐私合规平台。
  * [Cookiefirst](https://cookiefirst.com/) — Cookie 许可管理。免费计划每月 30,000 次页面浏览量。
  * [CookieYes](https://www.cookieyes.com/) — 网站的 Cookie 许可解决方案。每月 25,000 次页面浏览量免费。
  * [Iubenda](https://www.iubenda.com/) — 隐私和 Cookie 政策生成器。免费精简版。
  * [Osano](https://www.osano.com/) — 许可管理平台。免费计划每月 5,000 次访客。
  * [Privado](https://privado.ai/) — 隐私合规平台。免费计划每月 10,000 次页面浏览量。
  * [Seers](https://seersco.com/) — 隐私和 Cookie 许可管理。免费计划每月 5,000 次页面浏览量。
  * [Termly](https://termly.io/) — 免费隐私政策生成器。

**[⬆️ 回到顶部](#目录)**

## 杂项

  * [Api2Pdf](https://www.api2pdf.com/) — HTML 到 PDF 生成 API。每月 50 次免费。
  * [App-Privacy-Policy-Generator](https://app-privacy-policy-generator.firebaseapp.com/) — 为您的应用程序生成隐私政策。
  * [Barcodeapi](https://www.barcodeapi.org/) — 免费条形码生成 API。
  * [Base64 Image](https://www.base64-image.de/) — 免费图像到 Base64 转换器。
  * [Browserling](https://www.browserling.com/) — 实时交互式跨浏览器测试。免费 3 分钟会话。
  * [Carbon](https://carbon.now.sh/) — 创建和分享源代码的美丽图像。
  * [Code Time](https://www.software.com/) — 编程指标和时间跟踪。
  * [Cron-job.org](https://cron-job.org/) — 免费 cron 作业服务。
  * [Dillinger](https://dillinger.io/) — 基于云的 HTML5 Markdown 编辑器。
  * [Excalidraw](https://excalidraw.com/) — 虚拟白板，用于绘制手绘风格的图表。
  * [Formspree](https://formspree.io/) — 使用 HTML 表单发送电子邮件。每月 50 次提交免费。
  * [FullContact](https://www.fullcontact.com/) — 联系人管理和身份解析。
  * [Hoppscotch](https://hoppscotch.io/) — 免费、快速且美观的 API 请求构建器。
  * [Httpie](https://httpie.io/) — 现代、用户友好的命令行 HTTP 客户端。
  * [IFTTT](https://ifttt.com/) — 连接您的应用程序和设备。
  * [JSONLint](https://jsonlint.com/) — JSON 验证器和格式化程序。
  * [Lorem Ipsum](https://loremipsum.io/) — Lorem Ipsum 生成器。
  * [MailtoUI](https://mailtoui.com/) — 增强 mailto 链接的用户体验。
  * [Mockaroo](https://mockaroo.com/) — 随机数据生成器。
  * [Ngrok](https://ngrok.com/) — 将本地服务器公开给互联网。
  * [Online-Convert](https://www.online-convert.com/) — 免费在线文件转换器。
  * [PDF.co](https://pdf.co/) — PDF 生成和转换 API。
  * [Placeholder.com](https://placeholder.com/) — 快速简单的图像占位符服务。
  * [Quicktype](https://quicktype.io/) — 从 JSON 生成类型和转换器。
  * [Random User Generator](https://randomuser.me/) — 生成随机用户数据。
  * [Readme.so](https://readme.so/) — 简单的编辑器，用于创建 README 文件。
  * [ReqBin](https://reqbin.com/) — 在线 API 测试工具。
  * [Shields.io](https://shields.io/) — 简洁、一致且易读的徽章。
  * [StackEdit](https://stackedit.io/) — 浏览器内 Markdown 编辑器。
  * [Swagger](https://swagger.io/) — API 设计和文档工具。
  * [TableConvert](https://tableconvert.com/) — 在线表格转换器。
  * [TinyPNG](https://tinypng.com/) — 智能 WebP、PNG 和 JPEG 压缩。
  * [Trello](https://trello.com/) — 协作工具，用于组织项目。
  * [WakaTime](https://wakatime.com/) — 自动时间跟踪和指标。
  * [Zapier](https://zapier.com/) — 连接您的应用程序并自动化工作流程。每月 100 个任务免费。
  * [Zipcodebase](https://zipcodebase.com/) — 邮政编码 API。

**[⬆️ 回到顶部](#目录)**

## 远程桌面工具

  * [AnyDesk](https://anydesk.com) — 3 台设备免费，会话数量和持续时间无限制。
  * [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关。
  * [Getscreen.me](https://getscreen.me) — 2 台设备免费，会话数量和持续时间无限制。
  * [RemSupp](https://remsupp.com) — 按需支持和永久访问设备（每天 2 次免费会话）。
  * [RustDesk](https://rustdesk.com/) — 适合所有人的开源虚拟/远程桌面基础设施！

**[⬆️ 回到顶部](#目录)**

## 游戏开发

  * [3Dassets.one](https://3dassets.one/) — 超过 8,000 个免费/付费 3D 模型和用于制作纹理的 PBR 材质。
  * [ArtStation](https://www.artstation.com/) — 免费/付费 2D、3D 资产和音频、图标、图块集、游戏工具包的市场。此外，它还可用于展示您的艺术作品集。
  * [CraftPix](https://craftpix.net) — 免费/付费资产，如 2D、3D、音频、GUI、背景、图标、图块集、游戏工具包。
  * [Freesound](https://freesound.org/) — 提供不同 CC 许可的免费协作声音库。
  * [Game Icons](https://game-icons.net/) — 根据 CC-BY 许可提供的免费可样式化 SVG/PNG 图标。
  * [GameDevMarket](https://gamedevmarket.net) — 免费/付费资产，如 2D、3D、音频、GUI。
  * [Gamefresco.com](https://gamefresco.com/) — 发现、收集和分享来自世界各地游戏艺术家的免费游戏资产。
  * [itch.io](https://itch.io/game-assets) — 免费/付费资产，如精灵、图块集和角色包。
  * [Kenney](https://www.kenney.nl/assets/) — 免费 (CC0 1.0 Universal licensed) 2D、3D、音频和 UI 游戏资产。
  * [LoSpec](https://lospec.com/) — 用于创建像素艺术和其他限制性数字艺术的在线工具，有大量教程/调色板列表可供选择用于您的游戏。
  * [OpenGameArt](https://opengameart.org) — 开源游戏资产，如音乐、声音、精灵和 gif。
  * [Poliigon](https://www.poliigon.com/) — 免费和付费纹理（具有可变分辨率）、模型、HDRI 和画笔。提供免费插件以导出到 Blender 等软件。
  * [Poly Pizza](https://poly.pizza/) — 免费低多边形 3D 资产。
  * [Rive](https://rive.app/community/) — 社区资产以及使用其免费计划创建您自己的游戏资产。

**[⬆️ 回到顶部](#目录)**

## 其他免费资源

  * [360Converter](https://www.360converter.com/) — 免费层级有用的网站，用于转换：视频到文本 && 音频到文本 && 语音到文本 && 实时音频到文本 && YouTube 视频到文本 && 添加视频字幕。也许在短视频转换或简短的 youtube 教程中有用 :)
  * [AdminMart](https://adminmart.com/) — 使用 Angular、Bootstrap、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板和网站模板！
  * [Axonomy App](https://axonomy-app.com/) — 免费工具，用于创建、管理和与客户共享发票。每月 10 张免费发票。
  * [Buttons Generator](https://markodenic.com/tools/buttons-generator/) — 100 多个可在项目中使用的按钮。
  * [ElevateAI](https://www.elevateai.com) — 每月免费获得长达 200 小时的音频转录。
  * [Framacloud](https://degooglisons-internet.org/en/) — 法国非营利组织 [Framasoft](https://framasoft.org/en/) 提供的免费/自由开源软件和 SaaS 列表。
  * [Free Code Tools](https://freecodetools.org/) — 100% 免费的有效代码工具。Markdown 编辑器、代码缩小器/美化器、QR 码生成器、Open Graph 生成器、Twitter 卡片生成器等。
  * [get.localhost.direct](https://get.localhost.direct) — 用于具有子域支持的 localhost 开发的更好的 `*.localhost.direct` 通配符公共 CA 签名 SSL 证书。
  * [GitHub Education](https://education.github.com/pack) — 面向学生的免费服务集合。需要注册。
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 开发者的免费和开源软件中心。
  * [Glob tester](https://globster.xyz/) — 允许您设计和测试 glob 模式的网站。它还提供学习 glob 模式的资源。
  * [Hosting Checker](https://hostingchecker.co) — 检查任何域、网站或 IP 地址的托管信息，例如 ASN、ISP、位置等。还包括多个托管和 DNS 相关工具。
  * [It tools](https://it-tools.tech/) — 适用于开发人员和 IT 从业人员的有用工具。
  * [Killer Coda](https://killercoda.com/) — 浏览器中的交互式游乐场，用于学习 Linux、Kubernetes、容器、编程、DevOps、网络。
  * [Kody Tools](https://www.kodytools.com/dev-tools) — 100 多个开发工具，包括格式化程序、缩小器和转换器。
  * [Markdown Tools](https://markdowntools.com) — 用于将 HTML、CSV、PDF、JSON 和 Excel 文件转换为 Markdown 以及从 Markdown 转换的工具。
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) — 获取构建 Microsoft 365 平台解决方案所需的免费沙盒、工具和其他资源。订阅是 90 天的 [Microsoft 365 E5 订阅](https://www.microsoft.com/microsoft-365/enterprise/e5)（不包括 Windows），可续订。如果您积极参与开发（使用遥测数据和算法进行测量），它将续订。
  * [MySQL Visual Explain](https://mysqlexplain.com) — 易于理解且免费的 MySQL EXPLAIN 输出可视化工具，用于优化慢查询。
  * [PageTools](https://pagetools.co/) — 提供一套永久免费的 AI 驱动工具，帮助您通过简单的一键式界面生成基本的网站政策、创建社交媒体简介、帖子和网页。
  * [PHPhub](https://phphub.net/) — PHP 工具集合，包括格式化程序、验证器、沙盒、正则表达式测试器等。
  * [PostPulse](https://PostPulseAI.com) — 每月通过 AI 制作的帖子发布到 SEO 优化的域，提升您的在线形象，增强您的 SEO 和网站排名。免费计划允许您每月在我们的网站上手动发布一个帖子。
  * [Pyrexp](https://pythonium.net/regex) — 用于调试正则表达式的免费基于 Web 的正则表达式测试器和可视化工具。
  * [QRCodeBest](https://qrcode.best/) — 使用 13 个模板、完全隐私和个人品牌创建自定义 QR 码。具有跟踪像素、项目分类和 QRCode.Best 上的无限团队席位。
  * [RedHat for Developers](https://developers.redhat.com) — 免费访问 Red Hat 产品，包括 RHEL、OpenShift、CodeReady 等，专供开发人员使用。仅限个人计划。还提供免费电子书以供参考。
  * [regex101](https://regex101.com/) — 免费网站，允许您测试和调试正则表达式 (regex)。它提供正则表达式编辑器和测试器，以及用于学习正则表达式的有用文档和资源。
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) — 免费发送和接收测试短信。
  * [SimpleBackups.com](https://simplebackups.com/) — 服务器和数据库（MySQL、PostgreSQL、MongoDB）的备份自动化服务，直接存储到云存储提供商（AWS、DigitalOcean 和 Backblaze）。提供 1 个备份的免费计划。
  * [SimpleRestore](https://simplerestore.io) — 无忧 MySQL 备份恢复。无需代码或服务器即可将 MySQL 备份恢复到任何远程数据库。
  * [SmallDev.tools](https://smalldev.tools/) — 适用于开发人员的免费工具，允许您编码/解码各种格式，缩小 HTML/CSS/Javascript，美化，生成 JSON/CSV 和多种其他格式的虚假/测试数据集以及更多功能。界面令人愉悦。
  * [SnapShooter](https://snapshooter.com/) — 适用于 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持直接数据库、文件系统和应用程序备份到基于 s3 的存储。提供一项资源的每日备份免费计划。
  * [Table Format Converter](https://www.tableformatconverter.com) — 免费工具，可将表格数据转换为不同格式，如 CSV、HTML、JSON、Markdown 等。
  * [Themeselection](https://themeselection.com/) — 精选高质量、现代设计、专业且易于使用的免费管理仪表板模板、HTML 主题和 UI 套件，可更快地创建您的应用程序！
  * [UseCSV by Layercode](https://layercode.com/usecsv) — 在几分钟内将 CSV 和 Excel 导入添加到您的 Web 应用程序。为您的用户提供愉快而强大的数据导入体验。无需任何信用卡详细信息即可免费开始使用，并立即开始集成 UseCSV。您可以创建无限的导入器并上传最大 100Mb 的文件。
  * [Utils.fun](https://utils.fun/en) — 所有基于浏览器计算能力的离线日常和开发工具，包括水印生成、屏幕录制、编码和解码、加密和解密以及代码格式化，完全免费，不上传任何数据到云端进行处理。
  * [Web.Dev](https://web.dev/measure/) — 这是一个免费工具，允许您查看网站的性能并改进 SEO 以在搜索引擎中获得更高的排名列表。
  * [Wikimint Developer](https://developer.wikimint.com/p/tools.html) — 永远免费的 Web 开发人员工具，包括 CSS 缩小取消缩小、图像优化器、图像调整器、大小写转换器、CSS 验证器、JavaScript 编译器、HTML 编辑器等。
  * [WrapPixel](https://www.wrappixel.com/) — 下载使用 Angular、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板模板！

**[⬆️ 回到顶部](#目录)**
