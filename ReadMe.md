
# ASP.NET Core Developer Roadmap

> Roadmap to becoming a [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-2.2) developer in 2019:

Below you can find a chart demonstrating the paths that you can take and the libraries that you would want to learn to become a ASP.NET Core developer. I made this chart as a tip for everyone who asks me, "What should I learn next as a ASP.NET Core developer?"

## Disclaimer
> The purpose of this roadmap is to give you an idea about the landscape. The road map will guide you if you are confused about what to learn next, rather than encouraging you to pick what is hip and trendy. You should grow some understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does not always mean best suited for the job

## Give a Star! :star:
If you like or are using this project to learn or start your solution, please give it a star. Thanks!

## Roadmap

![Roadmap](./aspnetcore-developer-roadmap.png)

## Resources

1. Prerequisites
    * [C#](https://www.pluralsight.com/paths/csharp)
    * [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
    * [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
    
2. General Development Skills
    * Learn GIT, create a few repositories on GitHub, share your code with other people
    * Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
    * Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com/)
    * Learn [dotnet CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x)
    * Read a few books about algorithms and data structures
    
3. Dependency Injection
    1. DI Containers
        * [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2)
        * [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
        * [Ninject](http://www.ninject.org/)
        * [StructureMap](https://github.com/structuremap/structuremap)
        * [Castle Windsor](https://github.com/castleproject/Windsor)
    2. [Life Cycles](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2#service-lifetimes)
    3. [Scrutor](https://github.com/khellang/Scrutor)
    
4. Databases
    1. Relational
	    1. [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2017)
	    2. [PostgreSQL](https://www.postgresql.org/)
	    3. [MariaDB](https://mariadb.org/)
	    4. [MySQL](https://www.mysql.com/)
    2. Cloud Databases
        * [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db)
        * [DynamoDB](https://aws.amazon.com/dynamodb/)
    3. Search Engines
        * [ElasticSearch](https://www.elastic.co/)
        * [Solr](http://lucene.apache.org/solr/)
        * [Sphinx](http://sphinxsearch.com/)
    4. NoSQL
	    * [MongoDB](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-2.2&tabs=visual-studio)
	    * [Apache Cassandra](http://cassandra.apache.org/)
	    * [LiteDB](https://github.com/mbdavid/LiteDB)
	    * [Redis](https://redis.io/)
	    * [CouchDB](http://couchdb.apache.org/)

5. Caching
    1. Entity Framework 2nd Level Cache
	    1. [EFSecondLevelCache.Core](https://github.com/VahidN/EFSecondLevelCache.Core)
	    2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)
    2. [Distributed Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/distributed?view=aspnetcore-2.2)
        1. [Redis](https://redis.io/)
        2. [Memcached](https://memcached.org/)
    3. [Memory Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-2.2)

6. Log Frameworks
    * [Serilog](https://github.com/serilog/serilog)
    * [NLog](https://github.com/NLog/NLog)
    * [Elmah](https://elmah.github.io/)

7. Object Mapping
    * [AutoMapper](https://github.com/AutoMapper/AutoMapper)
    * [Mapster](https://github.com/MapsterMapper/Mapster)
    * [AgileMapper](https://github.com/agileobjects/AgileMapper)
    * [ExpressMapper](http://expressmapper.org/)

8. API Clients
      1. REST
	        * [OData](https://blogs.msdn.microsoft.com/odatateam/2018/07/03/asp-net-core-odata-now-available/)
	        * [Sieve](https://github.com/Biarity/Sieve)
    2. GraphQL
        * [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

9. Good to Know
    * [MediatR](https://github.com/jbogard/MediatR)
    * [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    * [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    * [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    * [Polly](https://github.com/App-vNext/Polly)
    * [NodaTime](https://github.com/nodatime/nodatime)
    * [GenFu](https://github.com/MisterJames/GenFu)

10. Testing
	1. Unit Testing
		1. Frameworks
		    * [MSTest](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-mstest)
		    * [NUnit](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit)
		    * [xUnit](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test)
		2. Mocking
			* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
			* [NSubstitute](https://github.com/nsubstitute/NSubstitute)
		3. Assertion
			* [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
			* [Shoudly](https://github.com/shouldly/shouldly)
	2. Behavior Testing
		* [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
		* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
		* [LightBDD](https://github.com/LightBDD/LightBDD)
	3. Integration Testing
		* [AspNetCore.TestServer](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-2.2)
	4. E2E Testing
		* [Selenium](https://www.automatetheplanet.com/webdriver-dotnetcore2/)
		* [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

11. Task Scheduling
    * [HangFire](https://github.com/HangfireIO/Hangfire)
    * [Coravel](https://github.com/jamesmh/coravel)
    * [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)

12. Static Site Generator
    * [Wyam](https://github.com/Wyamio/Wyam)

13. MicroServices
	1. Message-Broker
	    * [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
	    * [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
	    * [ActiveMQ](https://github.com/apache/activemq)
	2. Message-Bus
		* [MassTransit](https://github.com/MassTransit/MassTransit)
		* [NServiceBus](https://github.com/Particular/NServiceBus)
		* [CAP](https://github.com/dotnetcore/CAP)

14. Design-Patterns
	* [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
	* [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
	* [Observer](https://www.dofactory.com/net/observer-design-pattern)
	* [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
	* [Builder](https://www.dofactory.com/net/builder-design-pattern)
	* [Facade](https://www.dofactory.com/net/facade-design-pattern)
	* [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
	* [Mediator](https://www.dofactory.com/net/mediator-design-pattern)

## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit.

Idea from : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## Contribution

The roadmap is built using [Draw.io](https://www.draw.io/). Project file can be found at `aspnetcore-developer-roadmap.xml` file. To modify it, open draw.io, click **Open Existing Diagram** and choose `xml` file with project. It will open the roadmap for you. Update it, upload and update the images in readme and create a PR (export as png).

- Open a pull request with improvements
- Discuss ideas in issues
- Spread the word

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
