# awesome-serverless(🚀 Serverless 精选指南)

## 什么是“无服务器”（Serverless）计算？

**Serverless** 并不是没有服务器，而是开发者无需直接管理服务器。资源按需调用，无需担忧容量、部署、扩展、容错、操作系统更新等问题。

例如，**AWS Lambda** 提供了一种无需管理服务器的计算方式，开发者只需关注代码本身。

## 常用 Serverless 平台和工具

### 一体化解决方案

- **[Firebase](https://firebase.google.com/)**：实时数据库、认证、托管，适合移动端与 Web 应用。
- **[LeanCloud](https://leancloud.app/)**：快速开发的无服务器云平台。
- **[Backendless](https://backendless.com/)**：提供实时数据库、认证及托管服务。
- **[Vercel](https://vercel.com/)**：支持多种前端框架，集成 Serverless Functions。
- **[Netlify](https://netlify.com/)**：自动化部署静态网站及 Lambda 函数。

### 托管与代码执行平台

- **[AWS Lambda](https://aws.amazon.com/lambda)**：按调用量付费，无需管理服务器。
- **[Google Cloud Functions](https://cloud.google.com/functions/docs)**：轻量、事件驱动，适合构建单一功能服务。
- **[Azure Functions](https://azure.microsoft.com/en-us/services/functions/)**：跨栈事件响应服务。
- **[Cloudflare Workers](https://workers.cloudflare.com/)**：全球分布式无服务器平台，适用于边缘计算。

### 框架

- **[Serverless Framework](https://serverless.com/)**：支持多种云服务（如 AWS Lambda、Google Cloud Functions 等）的开发和部署。
- **[Pulumi](https://pulumi.io/)**：多云支持的 Serverless 应用开发平台，支持 JavaScript、Python 等语言。
- **[OpenFaaS](https://www.openfaas.com/)**：基于 Docker 和 Kubernetes 的无服务器函数框架。
- **[AWS Amplify](https://aws.amazon.com/amplify/)**：简化前端应用开发和部署。

### 安全

- **[Auth0](https://auth0.com/)**：提供单点登录和基于令牌的认证。
- **[Amazon Cognito](https://aws.amazon.com/cognito/)**：快速添加用户登录、注册功能。
- **[PureSec CLI](https://github.com/puresec/serverless-puresec-cli)**：自动生成最小权限的 IAM 角色。

### 数据库

- **[Amazon DynamoDB](https://aws.amazon.com/dynamodb/)**：灵活的 NoSQL 数据库服务。
- **[Upstash](https://upstash.com/)**：支持 Redis 的 Serverless 数据库。
- **[Neon](https://neon.tech)**：支持 PostgreSQL 的无服务器数据库。

### CI/CD（持续集成与持续交付）

- **[Serverless Framework Pro](https://www.serverless.com/pro/)**：提供 CI/CD、监控和故障排除。
- **[LambCI](https://github.com/lambci/lambci)**：基于 AWS Lambda 的持续集成系统。

### 观察性工具（日志/监控/性能追踪）

- **[AWS X-Ray](https://aws.amazon.com/xray/)**：分析和调试分布式应用。
- **[Thundra](https://www.thundra.io/)**：集成指标、日志和分布式追踪。
- **[Lumigo](https://www.lumigo.io/)**：提供 Serverless 应用的可视化调试平台。

### 文件与媒体管理

- **[Filestack](https://www.filestack.com/)**：文件上传、转换与分发的云服务。
- **[Mux](https://mux.com/)**：提供视频直播、文件上传、动态生成缩略图等功能。

### 实时功能

- **[Pusher](https://pusher.com/)**：构建实时应用的推送服务。
- **[PubNub](https://www.pubnub.com/)**：发布/订阅模型的实时数据流服务。

### 表单处理

- **[Formspree](https://formspree.io/)**：提供简单 HTML 表单的后端支持。
- **[Formspark](https://formspark.io/)**：快速集成表单后端服务。

### 电商平台

- **[Snipcart](https://snipcart.com/)**：基于 HTML 和 JavaScript 的购物车解决方案。
- **[Medusa](https://medusajs.com/)**：开源的无服务器电商平台。

### 邮件发送

- **[Mailchimp Lambda](https://github.com/TaylorBriggs/mailchimp-lambda)**：集成 Mailchimp 的订阅服务。
- **[AWS SES](https://aws.amazon.com/ses/)**：支持大规模邮件发送的 Amazon 服务。

## 精选资源

### 入门与实践

- **[Serverless Stack](https://serverless-stack.com/)**：从零开始构建全栈 Serverless 应用的指南。
- **[Serverless Framework Examples](https://www.serverless.com/examples/)**：丰富的 Serverless 应用模板和示例。

### 相关文章

- **[Serverless 架构](https://martinfowler.com/articles/serverless.html)**：Martin Fowler 关于 Serverless 的经典解读。
- **[Serverless Architectures on AWS](https://www.manning.com/books/serverless-architectures-on-aws)**：Serverless 架构设计指南。

## 总结

**Serverless** 是一种革命性的计算模式，适用于现代化 Web 应用开发。通过以上工具和资源，你可以快速上手并打造高效的无服务器架构！
