# Дорожная карта разработчика ASP.NET Core 

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Backers on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/AspNetCore-Developer-Roadmap/sponsors/badge.svg)](#sponsors)

- [Read-me на Английском](ReadMe.md)
- [Read-me на Традиционном китайском](ReadMe.zh-Hant.md)
- [Read-me на Упрощенном китайском](ReadMe.zh-Hans.md)
- [Read-me на Турецком](ReadMe-tr.md)
- [Read-me на Японском](ReadMe.ja.md)

> Дорожная карта разработчика [ASP.NET Core](https://docs.microsoft.com/aspnet/core) в 2025:
На данной карте представлен список технологий и библиотек, которые вам стоит изучить, чтобы стать разработчиком ASP.NET Core. Я создал эту карту в качестве простого руководства для всех, кто спрашивает меня: "Что я должен изучить дальше, чтобы стать разработчиком ASP.NET Core?"

## Дисклеймер

> Цель этой дорожной карты - помочь вам понять общую картину. Она поможет вам определить, что изучать дальше, а не просто следовать модным технологиям. Важно разобраться, когда и какие технологии лучше использовать в конкретных ситуациях и помнить, что модные и трендовые технологии не всегда подходят для всех задач.

## Поставьте звездочку! :star:

Если вам понравилась эта карта или вы собираетесь использовать ее или просто разобрались с ее применением, пожалуйста, поставьте звездочку. Мы благодарим вас!

## Дорожная карта

![Дорожная карта](./aspnetcore-developer-roadmap.ru.png)

## Материалы

1. Общие навыки разработчика
   - Освойте [Git](https://git-scm.com/doc), создайте пару репозиториев на [GitHub](https://docs.github.com/en/get-started/quickstart), покажите свой код другим.
   - Освойте [протокол HTTP(S)](https://developer.mozilla.org/ru/docs/Web/HTTP/Overview), методы запросов ([GET](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/GET), [POST](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/POST), [PUT](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/PUT), [PATCH](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/PATCH), [DELETE](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/DELETE), [OPTIONS](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods/OPTIONS), etc.)
   - Что такое [TLS](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/)?
   - Что такое [SSL](https://www.cloudflare.com/learning/ssl/what-is-ssl/)?
   - Не бойтесь использовать Google, [прокачайте навык гугления](http://www.powersearchingwithgoogle.com)
   - Начните использовать [ChatGPT](https://chat.openai.com/chat)
   - [Прочтите несколько книг о структурах данных и алгоритмах](https://www.interviewbit.com/blog/data-structures-and-algorithms-books)

2. C#
   - [C#](https://www.pluralsight.com/paths/c-10)
   - [.NET 7](https://devblogs.microsoft.com/dotnet/announcing-dotnet-7)
   - Интерфейс командной строки [dotnet CLI](https://docs.microsoft.com/dotnet/core/tools)
   - [Правила StyleCop ](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/DOCUMENTATION.md)
   
3. Основы SQL
   - Обучающие материалы 📚
     - [Pluralsight Learning Path: Querying Data with T-SQL from SQL Server](https://www.pluralsight.com/paths/querying-data-with-t-sql-from-sql-server)

4. Основы ASP.NET Core
   - [MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview)
   - [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis)
   - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
   - [Application Settings & Configurations](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration)
   - [Middlewares](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware)
   - [Filters & Attributes](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters)
   - [Background Tasks](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
   - [Authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication)
   - [Authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction)
   - [IdentityServer](https://identityserver4.readthedocs.io/en/latest)
   - [Duende IdentityServer](https://duendesoftware.com)
   - [OpenIddict](https://github.com/openiddict/openiddict-core)
   - [Auth0](https://auth0.com/docs)
   - [OIDC](https://openid.net/connect)
   - [Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/overview)
   - [Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/razor-pages)
   - [Razor Components](https://docs.microsoft.com/en-us/aspnet/core/blazor/components)
   - Обучающие материалы 📚
      - [From Zero to Hero: REST APIs in .NET](https://dometrain.com/course/from-zero-to-hero-rest-apis-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Minimal APIs in .NET with C#](https://dometrain.com/course/from-zero-to-hero-minimal-apis-in-net-with-c/?affcode=1115529_alq6yoqt)

5. SOLID
    - [Принцип единственной ответственности (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Принцип открытости/закрытости (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Принцип подстановки Лисков (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Принцип разделения интерфейса (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Принцип инверсии зависимостей (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

6. Объектно-реляционное отображение данных (ORM)
    - [Основы платформы сущностей(EF Core)](https://learn.microsoft.com/ru-ru/ef/core)
       - Обучающие материалы 📚
         - [From Zero to Hero: Entity Framework Core in .NET](https://dometrain.com/course/from-zero-to-hero-entity-framework-core-in-dotnet/?affcode=1115529_alq6yoqt)
    - [Dapper](https://github.com/StackExchange/Dapper)


7. Внедрение зависимости
    1. Контейнеры DI
       - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
       - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
    3. [Scrutor](https://github.com/khellang/Scrutor)
    - Обучающие материалы 📚
       - [From Zero to Hero: Dependency Injection in .NET](https://dometrain.com/course/from-zero-to-hero-dependency-injection-in-net/?affcode=1115529_alq6yoqt) 
8. Базы данных
    1. Реляционные
       - [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
       - [PostgreSQL](https://www.postgresql.org)
       - [MariaDB](https://mariadb.org)
       - [MySQL](https://www.mysql.com)
    2. Поисковые системы
       - [ElasticSearch](https://www.elastic.co)
       - [Meilisearch](https://github.com/meilisearch/meilisearch)
       - [ManticoreSearch](https://github.com/manticoresoftware/manticoresearch)
       - [OpenSearch](https://github.com/opensearch-project/OpenSearch)
    3. NoSQL
        - Локальный
          - [Redis](https://redis.io)
          - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
          - [Apache Cassandra](http://cassandra.apache.org)
          - [LiteDB](https://github.com/mbdavid/LiteDB)
          - [RavenDB](https://github.com/ravendb/ravendb)
          - [CouchDB](http://couchdb.apache.org)
       - Облачный
          - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
          - [DynamoDB](https://aws.amazon.com/dynamodb)

9. Кэширование
    - [Кэширование в памяти](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
    - [Распределенный кэш](https://docs.microsoft.com/aspnet/core/performance/caching/distributed)
       1. [Redis](https://redis.io/)
          1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
          2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
       2. [Memcached](https://memcached.org)
    - Прикладной уровень
       - Кэширование ответов
          1. [Built in](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
          2. [Marvin.Cache.Headers](https://github.com/KevinDockx/HttpCacheHeaders)
       - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)
       - [Entity Framework 2nd Level Cache](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)

10. Фреймворки логирования
    - [Serilog](https://github.com/serilog/serilog)
    - [NLog](https://github.com/NLog/NLog)
	- Обучающие материалы 📚
      - [From Zero to Hero: Logging in .NET](https://dometrain.com/course/from-zero-to-hero-logging-in-dotnet/?affcode=1115529_alq6yoqt)
      
11. API-клиенты и коммуникации
    1. REST
       - [Sieve](https://github.com/Biarity/Sieve)
       - [OData](https://learn.microsoft.com/ru-ru/odata/webapi/first-odata-api) 
       - [REPR Pattern](https://ardalis.com/mvc-controllers-are-dinosaurs-embrace-api-endpoints/)
            - [Minimal APIs](https://learn.microsoft.com/ru-ru/aspnet/core/fundamentals/minimal-apis/overview)
            - [Fast Endpoints](https://github.com/FastEndpoints/FastEndpoints)
            - [Ardalis.Endpoints](https://github.com/ardalis/ApiEndpoints)
    2. [gRPC](https://docs.microsoft.com/ru-ru/aspnet/core/grpc)
    3. GraphQL
        - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
        - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)
    - Обучающие материалы 📚
      - [From Zero to Hero: REST APIs in .NET](https://dometrain.com/course/from-zero-to-hero-rest-apis-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Minimal APIs in .NET with C#](https://dometrain.com/course/from-zero-to-hero-minimal-apis-in-net-with-c/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: gRPC in .NET](https://dometrain.com/course/from-zero-to-hero-grpc-in-dotnet/?affcode=1115529_alq6yoqt)
	  
12. Коммуникации в реальном времени
    - [SignalR](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/ru-ru/aspnet/core/fundamentals/websockets)
   
13. Объектное отображение (маппинг)
    - [Manual mapping!](https://www.youtube.com/watch?v=U8gSdQN2jWI)
    - [Mapperly](https://github.com/riok/mapperly)
    - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
   
14. Планировка фоновых задач
    - [Native BackgroundService](https://docs.microsoft.com/ru-ru/aspnet/core/fundamentals/host/hosted-services)
    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Quartz](https://github.com/quartznet/quartznet)
    - [Coravel](https://github.com/jamesmh/coravel)    
    
15. Тестирование
    1. Юнит тестирование
       - Фреймворки
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       - Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       - Утверждения (assertions)
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
       - Генераторы фиктивных данных
          - [Bogus](https://github.com/bchavez/Bogus)
          - [AutoFixture](https://github.com/AutoFixture/AutoFixture)
    2. Интеграционное тестирование
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
       - [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire)
       - [Test Containers](https://github.com/testcontainers/testcontainers-dotnet)
       - [Respwan](https://github.com/jbogard/Respawn)
    3. Снэпшот тестирование
       - [Verify](https://github.com/VerifyTests/Verify)
    4. Тестирование поведения
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
    5. E2E тестирование
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)
    6. Тестирование производительности
       - [K6](https://github.com/grafana/k6)
       - [JMeter](https://github.com/apache/jmeter)
       - [Crank](https://github.com/dotnet/crank)
       - [Bombardier](https://github.com/codesenberg/bombardier)
	7. Архитектурное тестирование
	   - [ArchUnitNET](https://github.com/TNG/ArchUnitNET)
       - [NetArchTest](https://github.com/BenMorris/NetArchTest)   
    - Обучающие материалы 📚
      - [From Zero to Hero: Unit testing in C#](https://dometrain.com/course/from-zero-to-hero-unit-testing-in-c/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Integration testing in ASP.NET Core](https://dometrain.com/course/from-zero-to-hero-integration-testing-in-asp-net-core/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Test-Driven Development in C#](https://dometrain.com/course/from-zero-to-hero-test-driven-development-tdd-csharp/?affcode=1115529_alq6yoqt)
	  
16. Микросервисы
    1. Брокеры сообщении
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Шина передачи сообщении
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
    3. Шлюз API
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
       - [YARP](https://github.com/microsoft/reverse-proxy)
    4. Контейнеризация
       - [Docker](https://www.docker.com)
	   - [Podman](https://podman.io)
    5. Оркестрация
       - [Kubernetes](https://kubernetes.io)
         - [Rancher](https://github.com/rancher/rancher)
         - [Kubectl](https://kubernetes.io/docs/reference/kubectl)
         - [K9s](https://github.com/derailed/k9s)
    6. Прочее
       - [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire)
       - [Orleans](https://github.com/dotnet/orleans)
       - [Proto.Actor](https://github.com/asynkron/protoactor-dotnet)
       - [Dapr](https://github.com/dapr/dapr)
       - [Akka.NET](https://github.com/akkadotnet/akka.net)
	- Обучающие материалы 📚	   
      - [Getting Started: Microservices Architecture](https://dometrain.com/course/getting-started-microservices-architecture/?affcode=1115529_alq6yoqt)
      - [Getting Started: Solution Architecture](https://dometrain.com/course/getting-started-solution-architecture/?affcode=1115529_alq6yoqt)
      - [From Zero to Hero: Docker for Developers](https://dometrain.com/course/from-zero-to-hero-docker/?affcode=1115529_alq6yoqt)
	  
17. Непрерывная интеграция и развертывание(CI/CD)
    - [GitHub Actions](https://github.com/features/actions)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [GitLab CI/CD](https://docs.gitlab.com/ee/ci)
    - [TeamCity CI/CD](https://www.jetbrains.com/teamcity)

18. Паттерны проектирования
    - Категории
      - [Creational](https://docs.microsoft.com/azure/architecture/patterns/cqrs)
      - [Structural](https://www.dofactory.com/net/decorator-design-pattern)
      - [Behavioral](https://www.dofactory.com/net/strategy-design-pattern)
    - Обучающие материалы 📚
      - [Pluralsight Learning Path: Design Patterns in C#](https://www.pluralsight.com/paths/design-patterns-in-c)

19. Мониторинг/Логирование/Отслеживание/Оповещение
    - Мониторинг
       - Локальный
          - [Prometheus](https://github.com/prometheus/prometheus)
          - [Grafana](https://github.com/grafana/grafana)
       - Облачный
          - [Datadog](https://www.datadoghq.com)
    - Логирование
       - Локальное
          - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
          - [Seq](https://datalust.co/seq)
		  - [Sentry.io](https://sentry.io/welcome/)
       - Облачное
          - [Datadog](https://docs.datadoghq.com/logs)
          - [Sentry.io](https://sentry.io/welcome/)
       - Обучающие материалы 📚
         - [From Zero to Hero: Logging in .NET](https://dometrain.com/course/from-zero-to-hero-logging-in-dotnet/?affcode=1115529_alq6yoqt)		  
    - Отслеживание
       - Локальное
          - [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-dotnet)
             - [Jaeger](https://github.com/jaegertracing/jaeger)
             - [Zipkin](https://github.com/openzipkin/zipkin)
             - [Sentry.io](https://sentry.io/welcome/)			 
       - Облачное
          - [Datadog](https://docs.datadoghq.com/tracing)
          - [Sentry.io](https://sentry.io/welcome/)		  
    - Оповещение
       - Локальное
          - [Zabbix](https://www.zabbix.com)
          - [Alertmanager](https://github.com/prometheus/alertmanager)
       - Облачное
          - [Datadog](https://docs.datadoghq.com/monitors)

20. Клиентский.NET
    - Шаблонизаторы
       - [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
       - [Scriban](https://github.com/lunet-io/scriban)
       - [Fluid](https://github.com/sebastienros/fluid)
    - Фреймворки
       - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
       - [.NET MAUI](https://github.com/dotnet/maui)
	   
21. AI / LLMs
    - [Semantic Kernel](https://github.com/microsoft/semantic-kernel)
    - [OpenAI .NET](https://github.com/openai/openai-dotnet)
	
22. Будет полезным
    - [Scalar](https://github.com/scalar/scalar)
    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [Distributed Lock](https://github.com/madelson/DistributedLock)
    - [EF Core Bulk Extensions](https://github.com/borisdj/EFCore.BulkExtensions)
    - [Nuke Build](https://github.com/nuke-build/nuke)
    - [Marten](https://github.com/JasperFx/marten)


## Заключение

Если у вас есть предложения по улучшению этой карты, пожалуйста, отправьте запрос на изменение (PR) с вашими обновлениями или задайте вопросы в разделе Issues. Кроме того, я буду продолжать обновлять эту карту, поэтому не забудьте поставить звезду, чтобы не пропустить новые обновления.

Идя взята из : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## Участие

Хотите поучаствовать? Мы ценим фидбек и участие сообщества. Просьба придерживатся [гайдлайну по участию](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/CONTRIBUTING.md).

## Упоминания

### Поддержка

Благодарим всех кто нас поддерживает! 🙏 [[Поддержать](https://opencollective.com/AspNetCore-Developer-Roadmap#backer)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/backers.svg?width=890"></a>

### Спонсоры

Поддержите этот проект став спонсором. Ваше лого будет отображено здесь со ссылкой на ваш сайт. [[Стать спонсором](https://github.com/sponsors/MoienTajik)]

<a href="https://github.com/sponsors/MoienTajik" target="_blank"><img src="https://opencollective.com/AspNetCore-Developer-Roadmap/sponsor/0/avatar.svg"></a>


## Лицензия

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0)
