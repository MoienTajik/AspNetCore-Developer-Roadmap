# ASP.NET Core Developer Roadmap

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Backers on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/sponsors/badge.svg)](#sponsors)

- [Read-me in Traditional Chinese](ReadMe.zh-Hant.md)
- [Read-me in Simplified Chinese](ReadMe.zh-Hans.md)
- [Read-me in Turkish](ReadMe-tr.md)
- [Read-me in Japanese](ReadMe.ja.md)

> Roadmap to becoming an [ASP.NET Core](https://docs.microsoft.com/aspnet/core) developer in 2024:

Below you can find a chart demonstrating the paths that you can take and the libraries that you would want to learn to become an ASP.NET Core developer. I made this chart as a tip for everyone who asks me, "What should I learn next as an ASP.NET Core developer?"

## Disclaimer

> The purpose of this roadmap is to give you an idea about the landscape. The road map will guide you if you are confused about what to learn next, rather than encouraging you to pick what is hip and trendy. You should grow some understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does not always mean best suited for the job.

## Give a Star! :star:

If you like or are using this project to learn or start your solution, please give it a star. Thanks!

## Roadmap

![Roadmap](./aspnetcore-developer-roadmap.png)

## Resources

1. General Development Skills
   - Learn [Git](https://git-scm.com/doc), create a few repositories on [GitHub](https://docs.github.com/en/get-started/quickstart), share your code with other people
   - Know [HTTP(S) protocol](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview), request methods ([GET](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET), [POST](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST), [PUT](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PUT), [PATCH](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PATCH), [DELETE](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/DELETE), [OPTIONS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/OPTIONS), etc.)
   - What is [TLS](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/)?
   - What is [SSL](https://www.cloudflare.com/learning/ssl/what-is-ssl/)?
   - Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com)
   - Start using [ChatGPT](https://chat.openai.com/chat)
   - [Read a few books about algorithms and data structures](https://www.interviewbit.com/blog/data-structures-and-algorithms-books)

2. C#
   - [C#](https://www.pluralsight.com/paths/c-12)
   - [.NET 8](https://devblogs.microsoft.com/dotnet/announcing-dotnet-8)
   - [.NET CLI](https://docs.microsoft.com/dotnet/core/tools)
   - [StyleCop rules](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/DOCUMENTATION.md)

3. SQL Fundamentals
   - Tutorials 📚
     - [Pluralsight Learning Path: Querying Data with T-SQL from SQL Server](https://www.pluralsight.com/paths/querying-data-with-t-sql-from-sql-server)

5. ASP.NET Core Basics
   - [MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview)
   - [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis)
   - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
   - [Application Settings & Configurations](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration)
   - [Middlewares](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware)
   - [Filters & Attributes](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters)
   - [Authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication)
   - [Authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction)
   - [IdentityServer](https://identityserver4.readthedocs.io/en/latest)
   - [Duende IdentityServer](https://duendesoftware.com)
   - [OpenIddict](https://github.com/openiddict/openiddict-core)
   - [Auth0](https://auth0.com/docs)
   - [OIDC](https://openid.net/connect)
   - [Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/razor-pages)
   - [Razor Components](https://docs.microsoft.com/en-us/aspnet/core/blazor/components)
   - Tutorials 📚
      - [From Zero to Hero: REST APIs in .NET](https://dometrain.com/course/from-zero-to-hero-rest-apis-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Minimal APIs in .NET with C#](https://dometrain.com/course/from-zero-to-hero-minimal-apis-in-net-with-c/?affcode=1115529_alq6yoqt)

6. SOLID
    - [Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

7. ORM
    - [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core)
       - Tutorials 📚
          - [From Zero to Hero: Entity Framework Core in .NET](https://dometrain.com/course/from-zero-to-hero-entity-framework-core-in-dotnet/?affcode=1115529_alq6yoqt)
    - [Dapper](https://github.com/StackExchange/Dapper)

8. Dependency Injection
    1. DI Containers
       - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
       - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
    2. [Scrutor](https://github.com/khellang/Scrutor)
    - Tutorials 📚
       - [From Zero to Hero: Dependency Injection in .NET](https://dometrain.com/course/from-zero-to-hero-dependency-injection-in-net/?affcode=1115529_alq6yoqt) 

9. Databases
    1. Relational
       - [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
       - [PostgreSQL](https://www.postgresql.org)
       - [MariaDB](https://mariadb.org)
       - [MySQL](https://www.mysql.com)
    2. Search Engines
       - [ElasticSearch](https://www.elastic.co)
       - [Meilisearch](https://github.com/meilisearch/meilisearch)
       - [ManticoreSearch](https://github.com/manticoresoftware/manticoresearch)
       - [OpenSearch](https://github.com/opensearch-project/OpenSearch)
    3. NoSQL
        - On-Premises
          - [Redis](https://redis.io)
          - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
          - [Apache Cassandra](http://cassandra.apache.org)
          - [LiteDB](https://github.com/mbdavid/LiteDB)
          - [RavenDB](https://github.com/ravendb/ravendb)
          - [CouchDB](http://couchdb.apache.org)
       - Cloud
          - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
          - [DynamoDB](https://aws.amazon.com/dynamodb)

10. Caching
    - [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
    - [Distributed Cache](https://docs.microsoft.com/aspnet/core/performance/caching/distributed)
       1. [Redis](https://redis.io/)
          1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
          2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
       2. [Memcached](https://memcached.org)
    - Application-Level
       - Response Caching
          1. [Built in](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
          2. [Marvin.Cache.Headers](https://github.com/KevinDockx/HttpCacheHeaders)
       - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)
       - [Entity Framework 2nd Level Cache](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)

11. Log Frameworks
    - [Serilog](https://github.com/serilog/serilog)
    - [NLog](https://github.com/NLog/NLog)
    - Tutorials 📚
      - [From Zero to Hero: Logging in .NET](https://dometrain.com/course/from-zero-to-hero-logging-in-dotnet/?affcode=1115529_alq6yoqt)
      
12. API Clients & Communications
    1. REST
       - [Gridify](https://github.com/alirezanet/Gridify)
       - [OData](https://learn.microsoft.com/en-us/odata/webapi/first-odata-api) 
       - [REPR Pattern](https://ardalis.com/mvc-controllers-are-dinosaurs-embrace-api-endpoints/)
            - [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis/overview)
            - [Ardalis.Endpoints](https://github.com/ardalis/ApiEndpoints)
            - [Fast Endpoints](https://github.com/FastEndpoints/FastEndpoints)
    2. [gRPC](https://docs.microsoft.com/en-us/aspnet/core/grpc)
    3. GraphQL
        - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
        - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)
    - Tutorials 📚
      - [From Zero to Hero: REST APIs in .NET](https://dometrain.com/course/from-zero-to-hero-rest-apis-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Minimal APIs in .NET with C#](https://dometrain.com/course/from-zero-to-hero-minimal-apis-in-net-with-c/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: gRPC in .NET](https://dometrain.com/course/from-zero-to-hero-grpc-in-dotnet/?affcode=1115529_alq6yoqt)

13. Real-Time Communication
    - [SignalR](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets)
   
14. Object Mapping
    - [Manual mapping!](https://www.youtube.com/watch?v=U8gSdQN2jWI)
    - [Mapperly](https://github.com/riok/mapperly)
    - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
   
15. Background Task Scheduler
    - [Native BackgroundService](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Quartz](https://github.com/quartznet/quartznet)
    - [Coravel](https://github.com/jamesmh/coravel)    
    
16. Testing
    1. Unit Testing
       - Frameworks
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       - Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       - Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
       - Fake Data Generators
          - [Bogus](https://github.com/bchavez/Bogus)
          - [AutoFixture](https://github.com/AutoFixture/AutoFixture)
    2. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
       - [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire)
       - [Test Containers](https://github.com/testcontainers/testcontainers-dotnet)
       - [Respwan](https://github.com/jbogard/Respawn)
    3. Snapshot Testing
       - [Verify](https://github.com/VerifyTests/Verify)
    4. Behavior Testing
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
    5. E2E Testing
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)
    6. Performance Testing
       - [K6](https://github.com/grafana/k6)
       - [JMeter](https://github.com/apache/jmeter)
       - [Crank](https://github.com/dotnet/crank)
       - [Bombardier](https://github.com/codesenberg/bombardier)
    - Tutorials 📚
      - [From Zero to Hero: Unit testing in C#](https://dometrain.com/course/from-zero-to-hero-unit-testing-in-c/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Integration testing in ASP.NET Core](https://dometrain.com/course/from-zero-to-hero-integration-testing-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Test-Driven Development in C#](https://dometrain.com/course/from-zero-to-hero-test-driven-development-tdd-csharp/?affcode=1115529_alq6yoqt)

17. Microservices
    1. Message-Brokers
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging)
       - [Amazon SQS](https://aws.amazon.com/sqs)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
    3. API Gateway
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
       - [YARP](https://github.com/microsoft/reverse-proxy)
    4. Containerization
       - [Docker](https://www.docker.com)
       - [Podman](https://podman.io)
    5. Orchestration
       - [Kubernetes](https://kubernetes.io)
         - [Rancher](https://github.com/rancher/rancher)
         - [Kubectl](https://kubernetes.io/docs/reference/kubectl)
         - [K9s](https://github.com/derailed/k9s)
    6. Other
       - [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire)
       - [Orleans](https://github.com/dotnet/orleans)
       - [Proto.Actor](https://github.com/asynkron/protoactor-dotnet)
       - [Dapr](https://github.com/dapr/dapr)
    - Tutorials 📚
      - [Getting Started: Microservices Architecture](https://dometrain.com/course/getting-started-microservices-architecture/?affcode=1115529_alq6yoqt)
      - [Getting Started: Solution Architecture](https://dometrain.com/course/getting-started-solution-architecture/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Docker for Developers](https://dometrain.com/course/from-zero-to-hero-docker/?affcode=1115529_alq6yoqt)

18. Continuous Integration & Continuous Delivery
    - [GitHub Actions](https://github.com/features/actions)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [GitLab CI/CD](https://docs.gitlab.com/ee/ci)
    - [TeamCity CI/CD](https://www.jetbrains.com/teamcity)

19. Design Patterns
    - Categories
      - [Creational](https://refactoring.guru/design-patterns/creational-patterns)
      - [Structural](https://refactoring.guru/design-patterns/structural-patterns)
      - [Behavioral](https://refactoring.guru/design-patterns/behavioral-patterns)
    - Tutorials 📚
      - [Pluralsight Learning Path: Design Patterns in C#](https://www.pluralsight.com/paths/design-patterns-in-c)

20. Monitoring/Logging/Tracing/Alerting
    - Monitoring
       - On-Premises
          - [Prometheus](https://github.com/prometheus/prometheus)
          - [Grafana](https://github.com/grafana/grafana)
       - Cloud
          - [Datadog](https://www.datadoghq.com)
    - Logging
       - On-Premises
          - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
          - [Seq](https://datalust.co/seq)
          - [Sentry.io](https://sentry.io/welcome/)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/logs)
          - [Sentry.io](https://sentry.io/welcome/)
       - Tutorials 📚
         - [From Zero to Hero: Logging in .NET](https://dometrain.com/course/from-zero-to-hero-logging-in-dotnet/?affcode=1115529_alq6yoqt)
    - Tracing
       - On-Premises
          - [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-dotnet)
             - [Jaeger](https://github.com/jaegertracing/jaeger)
             - [Zipkin](https://github.com/openzipkin/zipkin)
             - [Sentry.io](https://sentry.io/welcome/)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/tracing)
          - [Sentry.io](https://sentry.io/welcome/)
    - Alerting
       - On-Premises
          - [Zabbix](https://www.zabbix.com)
          - [Alertmanager](https://github.com/prometheus/alertmanager)
       - Cloud
          - [Datadog](https://docs.datadoghq.com/monitors)

21. Client-Side .NET
    - Template Engines
       - [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
       - [Scriban](https://github.com/lunet-io/scriban)
       - [Fluid](https://github.com/sebastienros/fluid)
    - Frameworks
       - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
       - [.NET MAUI](https://github.com/dotnet/maui)

22. Good to Know
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [Distributed Lock](https://github.com/madelson/DistributedLock)
    - [EF Core Bulk Extensions](https://github.com/borisdj/EFCore.BulkExtensions)
    - [Nuke Build](https://github.com/nuke-build/nuke)
    - [Marten](https://github.com/JasperFx/marten)


## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit.

Idea from : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## Contribution

Want to contribute? We encourage community feedback and contributions. Please follow our [contributing guidelines](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/CONTRIBUTING.md).

## Credits

### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/AspNetCore-Developer-Roadmap#backer)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/backers.svg?width=890"></a>

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://github.com/sponsors/MoienTajik)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/sponsor/0/avatar.svg"></a>


## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0)
