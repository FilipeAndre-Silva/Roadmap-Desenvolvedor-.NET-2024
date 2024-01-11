# Roadmap Desenvolvedor .NET 2024

Este é um roadmap para se tornar um Desenvolvedor .NET, com listagens, conteúdos e links organizados para seu aprendizado.

## Orientaçãoes sobre o roadmap

> Este roadmap pretende dar-lhe uma ideia sobre o que aprender para se tornar um Desenvolvedor .NET em 2024. O roteiro irá guiá-lo se você precisar de esclarecimentos sobre o que aprender e onde, em vez de encorajá-lo a escolher o que está na moda e na moda. O conteúdo desse documento é proviniente de experiências e pesquisas pessais do autor.

> Todas as referências de terceiros vão ser citadas, preservando assim os direitos autorias dos mesmos. 

## ROADMAP

### 1. C#

O C# (pronuncia-se "C Sharp") é uma linguagem de programação moderna, orientada a objeto e fortemente tipada. O C# permite que os desenvolvedores criem muitos tipos de aplicativos seguros e robustos que são executados no .NET.

- Programação orientada a objetos (classes, objetos, interfaces, herança, polimorfismo)
- Variáveis, tipos de dados e operadores
- Tipos de referência e valor
- Fluxo de controle (condicionais, loops)
- Genéricos
- Manipulação de exceção
- Delegates e eventos
- Assemblies
- Collections
- LINQ (consulta integrada de linguagem)
- Assíncrono
- File I/O e serialização de arquivos
- Estruturas de dados
- Networking 
- Multithreading e paralelismo de tarefas
- Segurança e criptografia
- CLI dotnet
- Gerenciador de pacotes NuGet

### 2. Habilidades Gerais de Desenvolvimento

Dominar padrões de design, código limpo e controle de versão como o Git permite que você escreva código eficiente e de fácil manutenção que funcione e prospere em um ambiente de equipe. É a diferença entre ser um programador e um engenheiro de software qualificado.

**Princípios SOLID**:
- Princípio de Responsabilidade Única (SRP)
- Princípio Aberto/Fechado (OCP)
- Princípio de Substituição de Liskov (LSP)
- Princípio de segregação de interface (ISP)
- Princípio de Inversão de Dependência (DIP)
- SECO (não se repita)
- KISS (mantenha-o simples, estúpido)
- YAGNI (Você não vai precisar disso)
- Lei de Deméter (LoD) ou Princípio do Menor Conhecimento
- Composição sobre herança
- O princípio do menor espanto
- Estilos e padrões de arquitetura de software (MVC, MVP)

**Habilidades Gerais**:
- Aprenda Git
- Aprenda estruturas de dados e algoritmos
- Aprenda código limpo
- Aprenda os fundamentos da refatoração
- Aprenda Design Patterns.
  - Singleton
  - Factory Method
  - Adapter
  - Facade
  - Decorator
  - Proxy
  - Command
  - Template method
  - Strategy
  - Observer
- Aprenda os principais princípios de design de software
- Aprenda em profundidade os princípios SOLID de OO Design.
- Estilos de arquitetura de software
    - Aprenda os fundamentos das arquiteturas de software
    - Aprenda o estilo de arquitetura em camadas
    - Aprenda microsserviços e DAPR
    - Aprenda Design Orientado a Domínio ou com o livro

### 3. ASP.NET Core 

É uma estrutura multiplataforma e de alto desempenho desenvolvida pela Microsoft para a construção de aplicativos web, APIs e microsserviços. Você também pode executar seus aplicativos no Windows, Linux ou macOS. Ele foi projetado para oferecer flexibilidade e escalabilidade com recursos como injeção de dependência integrada e um sistema de configuração robusto.

- Noções básicas da Web:
  - Como funciona a Internet
  - O que acontece quando você digita um URL no seu navegador?
  - Como funciona o DNS
  - Protocolo HTTP(S)
- ASP.NET MVC
- Middlewares
- APIs
  - API Web
  - APIs mínimas
  - Protocolos
    - DESCANSAR
    - GráficoQL
    - gRPC
  - Práticas recomendadas de design de API REST
  - Compreendendo os cabeçalhos REST
- Injeção de dependência
  - Ciclos de vida
  - Injeção de dependência de extensões da Microsoft
  - Autofac
  - Escrutador
- Configurações e configurações do aplicativo
- Filtros e atributos
- Segurança
  - Autenticação ou este tópico do Reddit
  - Autorização
  - Servidor de Identidade
  - Autor0
  - OIDC

### 4. Client-Side .NET

Se quiser construir UIs em .NET, você precisará dessas estruturas. O Razor é um mecanismo de modelo para a criação de HTML dinâmico, enquanto o Blazor vai além, permitindo criar UIs interativas da web usando C# em vez de JavaScript. MAUI é um sucessor do Xamarin feito para a construção de aplicativos móveis multiplataforma. Windows Presentation Foundation (WPF) é uma estrutura de UI que cria aplicativos clientes de desktop.

- [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
- [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- [.NET MAUI](https://github.com/dotnet/maui)
- [WPF](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/overview/?view=netdesktop-8.0)

### 5. Bancos de dados

Na definição mais básica, um banco de dados é qualquer coleção de informações inter-relacionadas. Ao fazer uma lista de compras em um pedaço de papel, você está criando um pequeno banco de dados analógico. Mas o que é um banco de dados na ciência da computação? Nesse contexto, você define "banco de dados" como uma coleção de informações armazenadas como dados em um sistema de computador, como o estoque do mercado local.

- Sintaxe SQL
- Noções básicas de design de banco de dados (formulários normais, chaves, relacionamentos)
- A diferença entre junção interna, esquerda, direita e completa
- Ordem de execução de consultas SQL
- O que é o otimizador de consulta
- Projeto de banco de dados
- Aprenda SQL
- Relational
  - [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
  - [PostgreSQL](https://www.postgresql.org)
  - [MariaDB](https://mariadb.org)
  - [MySQL](https://www.mysql.com)
  - [Azure SQL](https://azure.microsoft.com/en-us/products/azure-sql/database)
- NoSQL
  - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
  - [RavenDB](https://github.com/ravendb/ravendb)
  - [Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db)
- Tools:
  - [SQLFlow](https://sqlflow.gudusoft.com/#/) - uma ótima ferramenta para visualizar consultas SQL.

### 6. ORM

O mapeamento objeto-relacional (ORM) é como um tradutor entre seu código C# orientado a objetos e o banco de dados relacional, eliminando a tediosa tarefa de escrever consultas SQL para operações CRUD básicas. Usando estruturas ORM como Entity Framework, você pode manipular dados como objetos em seu código, tornando-o mais legível e fácil de manter. Isso acelera o desenvolvimento, minimiza erros e permite que você se concentre em lógicas de negócios complexas, em vez de lidar com a sintaxe do banco de dados.

Para **Entity Framework**, você precisa saber o seguinte:

- DbContext e DbSet para gerenciar conexões de banco de dados e consultar dados
- Abordagens Code-First e Database-First para definir modelos de dados
- Migrações para gerenciar alterações no esquema do banco de dados
- Consultando dados usando LINQ e SQL bruto
- Rastreando alterações e salvando dados

**Outros recursos**:

- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core)
    - [Code First Migrations](https://learn.microsoft.com/en-us/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli)
    - [Change Tracker API](https://learn.microsoft.com/en-us/ef/core/change-tracking/)
    - [Lazy Eager Explicit Loading](https://learn.microsoft.com/en-us/ef/core/querying/related-data/) 
- [Dapper](https://github.com/StackExchange/Dapper)
- [LINQ](https://www.dotnetnakama.com/blog/understanding-the-dot-net-language-integrated-query-linq/)
- [ADO.NET](https://learn.microsoft.com/en-us/dotnet/framework/data/adonet/)

### 7. Caching

Caching is like your app's personal short-term memory, storing frequently accessed data so it can be quickly retrieved without taxing your database. By reducing database load and speeding up data access, caching gives your app the competitive edge it needs to meet user demands for responsiveness and availability.

**Resources**:

- [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
- [Redis](https://redis.io/)
- Application-Level
   - [Built-in](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
   - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)

### 8. Logging

Logging captures runtime information, errors, and other crucial data that can help you quickly identify and fix issues, making your application more reliable and secure. Logging frameworks like NLog or Serilog integrate seamlessly into .NET, giving you a real-time diagnostic tool indispensable for monitoring application health, troubleshooting problems, and even gathering insights for future development. 

**Resources**:

- [Serilog](https://github.com/serilog/serilog)
- [NLog](https://github.com/NLog/NLog)
- [Microsoft.Extensions.Logging](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging)

### 9. Communication

In .NET we have three types of communication: Real-time communication, Synchronous, and Asynchronous communication. Real-time communication technologies, like SignalR in the .NET ecosystem, enable these functionalities by maintaining a constant connection between server and client. Synchronous communication is mainly done by using through HTTP Client, while asynchronous communication is done through different messaging and event-based frameworks and libraries. Messaging systems act as a middleman between different parts of your system, allowing them to communicate without being directly connected. Event handlers, on the other side, are used for handling events within a single application. They facilitate a publisher-subscriber model where one part of the application can raise an event that other parts can react to.

**Resources**:

- Real time communication:
    - [SignalR Core](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets) 
    - [Socket.IO](https://github.com/doghappy/socket.io-client-csharp)
- Synchronous communication: 
    - [HTTP Client](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient?view=net-8.0)
- Asynchronous communication: 
    - Message brokers:
         - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
         - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
         - [ActiveMQ](https://activemq.apache.org/)
         - [NetMQ](https://netmq.readthedocs.io/en/latest/)
         - [Apache Kafka](https://kafka.apache.org/)
     - Message bus:
         - [MassTransit](https://github.com/MassTransit/MassTransit)
         - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
         - [NServiceBus](https://learn.microsoft.com/en-us/azure/service-bus-messaging/build-message-driven-apps-nservicebus?tabs=Sender)
         - [EasyNetQ](https://easynetq.com/)
     - Event handlers:
         - [Azure Event Hub](https://docs.microsoft.com/azure/event-hubs/event-hubs-about)
         - [Azure Event Grid](https://docs.microsoft.com/azure/event-grid/overview)
   
### 10. Background tasks

These services run tasks in the background, freeing up your application to focus on user interactions. Whether data processing, automated emails, or periodic clean-ups, background services ensure these tasks don't slow down or interrupt the user experience. 

**Resources**:

- [Background Service](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
- [HangFire](https://github.com/HangfireIO/Hangfire)
- [Quartz](https://github.com/quartznet/quartznet)

### 11. Object Mapping  

Their libraries automate the task of mapping between objects, eliminating the need for repetitive, error-prone manual mapping code. This boosts productivity and minimizes bugs, especially when dealing with complex models and DTOs (Data Transfer Objects). 

**Resources**:

- [AutoMapper](https://github.com/AutoMapper/AutoMapper)
- [Mapster](https://github.com/MapsterMapper/Mapster)

### 12. Testing

Unit tests focus on isolated pieces of your code, integration tests ensure different parts play well together, and end-to-end tests validate the entire user journey within your application. Together, they form a safety net, catching bugs early, simplifying debugging, and making your codebase robust and maintainable.

Here you need to know:

- Test frameworks (xUnit, NUnit, MSTest)
- Test runners and test explorers
- Asserts and test attributes
- Mocking libraries (Moq, NSubstitute, etc.)

**Resources**:

- [Unit Testing](https://www.pluralsight.com/courses/advanced-unit-testing)
    - Frameworks
      - [xUnit](https://xunit.net/)
      - [NUnit](https://nunit.org/)
      - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
    - Mocking
      - [NSubstitute](https://github.com/nsubstitute/NSubstitute) - for new projects
      - [Moq](https://github.com/moq/moq4) - for old projects ([why](https://www.bleepingcomputer.com/news/security/popular-open-source-project-moq-criticized-for-quietly-collecting-data/))
    - Assertion
      - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
      - [Shouldly](https://github.com/shouldly/shouldly)
    - Test Data Generators
      - [Bogus](https://github.com/bchavez/Bogus)
      - [AutoFixture](https://github.com/AutoFixture/AutoFixture)
- Integration Testing
    - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
    - [TestServer](https://learn.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-7.0)
    - [Testcontainers](https://dotnet.testcontainers.org/)
- Snapshot Testing
     - [Verify](https://github.com/VerifyTests/Verify)
- Behavior Testing
     - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
- End-to-End Testing
     - [Playwright](https://playwright.dev/)
- Performance Testing
     - [K6](https://github.com/grafana/k6)
     - [JMeter](https://github.com/apache/jmeter)

### 13. Observability   

These tools provide real-time insights into your application's performance, user behavior, and error rates, enabling you to address issues before they escalate into full-blown problems proactively.

- **Monitoring** focuses on the health and availability of services and systems, often triggering alerts for predefined conditions.

- **Telemetry** collects, processes, and transmits data from systems, enabling analysis of patterns, trends, and anomalies.

**Resources**:

- [Prometheus](https://github.com/prometheus/prometheus)
- [Grafana](https://github.com/grafana/grafana)
- [Datadog](https://www.datadoghq.com)
- [ELK Stack](https://www.elastic.co/what-is/elk-stack)
- [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-dotnet)
- [Jaeger](https://www.jaegertracing.io/)
- [Azure Application Insights](https://docs.microsoft.com/azure/azure-monitor/app/app-insights-overview)
- [Azure Log Analytics](https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)

### 14. Containerization

Container solutions encapsulate your .NET application, libraries, and runtime into isolated containers. This enables consistency across multiple development and production environments, resolving dependency issues. With features like layered file systems, you can easily manage container images for ASP.NET, .NET Core, or other .NET services, optimizing build times and resource utilization.

**Resources**:
- Containers
    - [Docker](https://www.docker.com)
    - [Docker Compose](https://docs.docker.com/compose/)
    - [Docker Hub](https://hub.docker.com/)
    - [Azure Container Registry](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-intro)
- Orchestration
    - [Kubernetes](https://kubernetes.io)
    - [Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/products/kubernetes-service)
    - [Helm](https://helm.sh/)
    - [Azure Container Apps](https://docs.microsoft.com/en-us/azure/container-apps/overview)

### 15. Cloud

Cloud providers provide a layer of APIs to abstract infrastructure and provision it based on security and billing boundaries. The cloud runs on servers in data centers, but the abstractions cleverly give the appearance of interacting with a single "platform" or large application. The ability to quickly provision, configure, and secure resources with cloud providers has been key to the tremendous success and complexity of modern DevOps.

The most popular cloud providers in the market are **AWS** and **Azure**, as well as **Google Cloud**.

Here, you must know how to manage users and administration, networks, virtual servers, etc.

**Resources**:

- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Google Cloud](https://cloud.google.com/)

### 16. Continuous Integration & Delivery (CI/CD)

CI/CD automates the building, testing, and deployment stages into a streamlined, error-resistant pipeline. This means faster releases, bug fixes, and more time to focus on feature development.

Here you need to know how to:

- Build and deployment tools (MSBuild, dotnet CLI)
- Version control systems (Git, Azure DevOps)
- CI/CD platforms (GitHub Actions, Azure Pipelines, Jenkins, TeamCity)

**Resources**:

- [DevOps concepts](https://newsletter.techworld-with-milan.com/p/devops-roadmap-2023)
- Services:
    - [GitHub Actions](https://github.com/features/actions)
    - [Gitlab CI](https://docs.gitlab.com/ee/ci)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [Travis CI](https://travis-ci.org)
    - [Jenkins](https://www.jenkins.io)
    - [TeamCity](https://www.jetbrains.com/teamcity)

### 17. NET Libraries

Some useful .NET libraries. Note that not all libraries will be used by everyone, it mainly depends on a project you work on.

- **[MediatR](https://github.com/jbogard/MediatR)** - Mediator pattern implementation in .NET
- **[Polly](https://github.com/App-vNext/Polly)** - Fault-handling library that allows expressing policies such as Retry and Circuit Breaker.
- **[Fluent Validation](https://github.com/JeremySkinner/FluentValidation)** - .NET validation library for building strongly-typed validation rules.
- **[Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)** - .NET library for benchmarking.
- **[Refit](https://github.com/reactiveui/refit)** - Turns your REST API into a live interface.
- **[YARP](https://microsoft.github.io/reverse-proxy/)** - Reverse proxy server.
- **[Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)** - Swagger tools for documenting API's built on ASP.NET Core.

## Additional considerations

In addition to this, you also need to know the following:

### Performance best practices

Performances play an essential role in .NET applications. Here you need to know:

#### Profiling and diagnostics

These tools can help you identify and debug different performance bottlenecks you have in your code. For this, you can use other tools, such as:

- [PerfView](https://joshthecoder.com/2023/10/23/using-perfview-to-diagnose-high-cpu-in-an-aspnet-app.html)
- [Visual Studio Profiler](https://learn.microsoft.com/en-us/visualstudio/profiling/profiling-feature-tour?view=vs-2022)
- [dotTrace](https://www.jetbrains.com/profiler/) and [dotMemory](https://www.jetbrains.com/dotmemory/)

#### Performance best practices

Along with tools, you should be aware of different performance best practices for .NET:

- **Caching** (in-mem Memory Cache or Redis)

- **Database Optimization** (optimize queries, proper indexing, connection pooling)

- **Async Programming** (offload all CPU extensive or I/O bound operations to DB, file systems, ext. systems)

- **Use Entity Framework wisely** (use eager loading, projections, and optimizations like compiled queries)

- **Memory management** (use value types and be cautious with large object graphs. Use dispose pattern to db connections or streams. Avoid boxing/unboxing. Use StringBuilder instead of String for a large number of concatenations.)

- **HTTP Caching** (use ETags, Last-Modified headers)

- **Minimize Round-Trips** (reduce the number of HTTP requests and database round-trips)

- **Content Delivery Networks (CDNs)** (Offload static assets (CSS, JavaScript, images) to CDNs for faster delivery to users)

- **Compression** (Enable GZIP or Brotli compression for HTTP responses to reduce data transfer size)

- **Logging and Tracing** (Avoid excessive logging in production. Use distributed tracing across microservices.)

- **Parallelism and Concurrency** (Utilize parallelism and multithreading for CPU-bound tasks using Parallel class or Task Parallel Library (TPL))

- **Resource Optimization** (Optimize images and assets for the Web to reduce load times)

- **HTTP2 over SSL** (now make intelligent decisions about the page content)

- **Measure and Monitor Performance** (use VS Diagnostic Tools, App Insights, or BenchmarkDotNet)

- **User Span<> instead of collections** (spans can represent a contiguous section of memory; this means we can use them to operate over arrays)

### Security and Cryptography

Security plays an essential role in application development. The most critical aspects of security in the .NET world are:

- [**Authentication and Authorization**](https://learn.microsoft.com/en-us/aspnet/web-api/overview/security/authentication-and-authorization-in-aspnet-web-api) concepts:
  - Cookies
  - ASP.NET Core Identity for user management
  - .NET OIDC middleware
  - OAuth and OpenID Connect for 3rd-party authentication
  - JWT (JSON Web Tokens) for token-based authentication
  - Role-based and claims-based authorization

- [**Cryptography and Data Protection**](https://learn.microsoft.com/en-us/dotnet/standard/security/cross-platform-cryptography) concepts:
  - Symmetric and asymmetric encryption algorithms
  - .NET Core Data Protection APIs
  - Hashing and digital signatures
  - Secure random number generation

## Additional learning resources

- [Pluralsight learning platform](https://www.pluralsight.com/browse?q=C%20sharp&type=all&sort=highest) - Learn C#/.NET mostly from Microsoft MVPs.
- [Awesome .NET!](https://github.com/quozd/awesome-dotnet) - A collection of awesome .NET libraries, tools, frameworks, and software.
- [Microsoft .NET Architecture Guides](https://dotnet.microsoft.com/en-us/learn/dotnet/architecture-guides)

### Books

- [Learn C# in One Day and Learn It Well](https://amzn.to/3Qld3fT) - the best for beginners
- [C# in Depth: Fourth Edition](https://amzn.to/3ZPcZbq) by Jon Skeet - the best for intermediate
- [Concurrency in C# Cookbook: Asynchronous, Parallel, and Multithreaded Programming](https://amzn.to/490EMtu) - the best for advanced
- [The C# Yellow](http://www.csharpcourse.com/) (free) - the best book overall

### YouTube Channels

- [IAmTimCorey](https://www.youtube.com/user/IAmTimCorey) 
- [Programming with Mosh](https://www.youtube.com/user/programmingwithmosh) 
- [Nick Chapsas](https://www.youtube.com/channel/UCrkPsvLGln62OMZRO6K-llg) 
- [Milan Jovanovic](https://www.youtube.com/@MilanJovanovicTech) 
- [Zoran Horvat](https://www.youtube.com/@zoran-horvat) 
- [CodeOpinion](https://www.youtube.com/watch?v=_rgH0Kb9Bis), by Derek Comartin
- freeCodeCamp
  - [C# Tutorial - Full Course for Beginners](https://www.youtube.com/watch?v=GhQdlIFylQ8) (3h)
  - [Advanced C# Programming Course](https://www.youtube.com/watch?v=YT8s-90oDC0) (15h)

### Blogs

- Official [.NET Blog](https://devblogs.microsoft.com/dotnet/)
- [The Morning Dew](https://www.alvinashcraft.com/), aggregator of different info about .NET world, by Alvin Ashcraft.
- [You’ve Been Haacked](https://haacked.com/), by Phil Haack.
- [Eric Lippert's blog](https://ericlippert.com/), who worked on C# compiler team.
- [Steve Smith](https://ardalis.com/), who focus on code qualiy and DDD.
- [Andrew Lock](https://andrewlock.net/), Senior Engineer at Datadog
- [Scott Hanselman](https://www.hanselman.com/blog/), Partner Program Manager at Microsoft
- [Rick Strahl's Web Log](https://weblog.west-wind.com/), focus on web and desktop apps in .NET.
- [Adam Sitnik](https://adamsitnik.com/), an expert on .NET Performance and Reliability.
- [Jimmy Bogard](https://www.jimmybogard.com/), creator of AutoMapper.
- [Vladimir Khorikov](https://enterprisecraftsmanship.com/), and expert in Testing.
- [Ayende @ Rahien](https://ayende.com/blog/), written by Oren Eini, creator of RavenDB.
- [Maarten Balliauw](https://blog.maartenballiauw.be/), Developer Advocate at JetBrains.
- [Khalid Abuhakmeh’s Blog](https://khalidabuhakmeh.com/), Developer Advocate at JetBrains.
- [Stephen Cleary](https://blog.stephencleary.com/), the author of "Concurrency in C# Cookbook"
- [Scott Brady](https://www.scottbrady91.com/articles), an expert on OAuth and web security.
- [Jiří Činčura](https://www.tabsoverspaces.com/), a project lead for ADO.NET provider for Firebird DB.
- [Coding Militia](https://blog.codingmilitia.com/), by João Antunes (Microsoft MVP).
- [Michael Shpilt](https://michaelscodingspot.com/), a software developer working at Microsoft
- [Mark Seemann](https://blog.ploeh.dk/), explains concepts that are not commonly blogged about with C#.
- [Steven Giesel](https://steven-giesel.com/), Microsoft MVP
- [Code Maze Weekly](https://code-maze.com/), articles on .NET, weekly.

### Podcasts

  - [.NET Rocks!](https://www.dotnetrocks.com/)
  - [Rockin' the Code World with Dot Net Dave](https://www.c-sharpcorner.com/live/rockin-the-code-world-with-dotnetdave)
  - [The Modern .NET Show](https://dotnetcore.show/)
    
### Other [.NET Content creators](https://www.wearedotnet.io/)

## Tools

- [Git](https://github.com/git-guides/install-git) and some [GUI clients](https://www.hostinger.com/tutorials/best-git-gui-clients/) - Distibuted source control system.
- [Visual Studio](https://visualstudio.microsoft.com/) - Main code editor for .NET projects.
- [Visual Studio Code](https://code.visualstudio.com/) - Lightweight code editor for different tech stacks, including .NET.
- [Rider](https://www.jetbrains.com/rider/) - Cross-Platform .NET IDE from JetBrains.
- [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15) / [Azure Data Studio](https://azure.microsoft.com/en-us/products/data-studio/) - IDE for managing any SQL infrastructure, from SQL Server to Azure SQL Database.
- [LINQPad](https://www.linqpad.net/) - interactively query databases with LINQ.
- [ReSharper](https://www.jetbrains.com/resharper/) - rapid refactoring.
- [.NET Reflector](https://www.red-gate.com/products/reflector/) - .NET decompiler.
- [Postman](https://www.postman.com/) - platform for testing APIs.
- [NDepend](https://www.ndepend.com/) - static code analyzer.
- [NCrunch for Visual Studio](https://www.ncrunch.net/) - enables developers to run tests in the background as they write code.

## Wrap Up

If you think the roadmap can be improved, please open a PR with any updates and submit any issues. Also, I will continue to improve this, so you should star this repository, too.

## Contribution

- Open a pull request with improvements
- Discuss ideas in issues
- Spread the word

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Author

[Dr. Milan Milanović](https://milan.milanovic.org) -  CTO at [3MD](https://3mdinc.com) and Microsoft MVP for Developer Technologies.
