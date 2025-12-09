# MicroService Framework

```text
ms-framework/
│
├── pom.xml                                    # 父POM，管理所有模块
│
├── ms-dependencies/                       # BOM依赖版本管理
│   └── pom.xml
│
├── ms-common/                             # 通用模块
│   ├── pom.xml
│   ├── ms-common-core/                    # 核心工具类
│   │   └── pom.xml
│   ├── ms-common-web/                     # Web通用组件
│   │   └── pom.xml
│   ├── ms-common-validation/              # 参数校验增强
│   │   └── pom.xml
│   └── ms-common-test/                    # 测试工具
│       └── pom.xml
│
├── ms-boot-starters/                      # 所有Starter
│   ├── pom.xml
│   │
│   ├── ms-cache-spring-boot-starter/      # 缓存组件
│   │   └── pom.xml
│   │
│   ├── ms-mq-spring-boot-starter/         # 消息队列组件
│   │   └── pom.xml
│   │
│   ├── ms-database-spring-boot-starter/   # 数据库组件
│   │   └── pom.xml
│   │
│   ├── ms-gateway-spring-boot-starter/    # API网关组件
│   │   └── pom.xml
│   │
│   ├── ms-ratelimit-spring-boot-starter/  # 分布式限流组件
│   │   └── pom.xml
│   │
│   ├── ms-trace-spring-boot-starter/      # 链路追踪组件
│   │   └── pom.xml
│   │
│   ├── ms-metrics-spring-boot-starter/    # 指标监控组件
│   │   └── pom.xml
│   │
│   ├── ms-logging-spring-boot-starter/    # 日志组件
│   │   └── pom.xml
│   │
│   └── ms-security-spring-boot-starter/   # 安全认证组件
│       └── pom.xml
│
├── ms-examples/                           # 示例工程
│   ├── pom.xml
│   ├── example-user-service/
│   └── example-order-service/
│
└── docs/                                       # 文档
├── getting-started.md
└── component-guide/
```
