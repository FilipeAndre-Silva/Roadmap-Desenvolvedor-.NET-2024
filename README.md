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

O cache é como a memória pessoal de curto prazo do seu aplicativo, armazenando dados acessados ​​com frequência para que possam ser recuperados rapidamente sem sobrecarregar seu banco de dados. Ao reduzir a carga do banco de dados e acelerar o acesso aos dados, o cache dá ao seu aplicativo a vantagem competitiva necessária para atender às demandas dos usuários por capacidade de resposta e disponibilidade.
**Resources**:

- [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
- [Redis](https://redis.io/)
- Application-Level
   - [Built-in](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
   - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)

### 8. Logging

O registro captura informações de tempo de execução, erros e outros dados cruciais que podem ajudá-lo a identificar e corrigir problemas rapidamente, tornando seu aplicativo mais confiável e seguro. Estruturas de registro como NLog ou Serilog integram-se perfeitamente ao .NET, fornecendo uma ferramenta de diagnóstico em tempo real indispensável para monitorar a integridade do aplicativo, solucionar problemas e até mesmo coletar insights para desenvolvimento futuro.

**Resources**:

- [Serilog](https://github.com/serilog/serilog)
- [NLog](https://github.com/NLog/NLog)
- [Microsoft.Extensions.Logging](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging)

### 9. Comunicação

No .NET temos três tipos de comunicação: comunicação em tempo real, comunicação síncrona e comunicação assíncrona. Tecnologias de comunicação em tempo real, como o SignalR no ecossistema .NET, possibilitam essas funcionalidades mantendo uma conexão constante entre servidor e cliente. A comunicação síncrona é feita principalmente por meio do cliente HTTP, enquanto a comunicação assíncrona é feita por meio de diferentes estruturas e bibliotecas baseadas em mensagens e eventos. Os sistemas de mensagens atuam como intermediários entre diferentes partes do seu sistema, permitindo que eles se comuniquem sem estarem diretamente conectados. Os manipuladores de eventos, por outro lado, são usados ​​para manipular eventos dentro de um único aplicativo. Eles facilitam um modelo editor-assinante onde uma parte do aplicativo pode gerar um evento ao qual outras partes podem reagir.

**Recursos**:

- Comunicação em tempo real:
    - [SignalR Core](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets) 
    - [Socket.IO](https://github.com/doghappy/socket.io-client-csharp)
- Comunicação síncrona: 
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
   
### 10. Tarefas em segundo plano

Esses serviços executam tarefas em segundo plano, liberando seu aplicativo para se concentrar nas interações do usuário. Seja processamento de dados, e-mails automatizados ou limpezas periódicas, os serviços em segundo plano garantem que essas tarefas não atrasem ou interrompam a experiência do usuário.

**Recursos**:

- [Background Service](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
- [HangFire](https://github.com/HangfireIO/Hangfire)
- [Quartz](https://github.com/quartznet/quartznet)

### 11. Mapeamento de objetos 

Their libraries automate the task of mapping between objects, eliminating the need for repetitive, error-prone manual mapping code. This boosts productivity and minimizes bugs, especially when dealing with complex models and DTOs (Data Transfer Objects). 

**Resources**:

- [AutoMapper](https://github.com/AutoMapper/AutoMapper)
- [Mapster](https://github.com/MapsterMapper/Mapster)

### 12. Testes

Os testes de unidade concentram-se em partes isoladas do seu código, os testes de integração garantem que diferentes partes funcionem bem juntas e os testes ponta a ponta validam toda a jornada do usuário dentro do seu aplicativo. Juntos, eles formam uma rede de segurança, detectando bugs antecipadamente, simplificando a depuração e tornando sua base de código robusta e fácil de manter.

**Resources**:

- [Unit Testing](https://www.pluralsight.com/courses/advanced-unit-testing)
    - Frameworks
      - [xUnit](https://xunit.net/)
      - [NUnit](https://nunit.org/)
      - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
    - Mocking
      - [NSubstitute](https://github.com/nsubstitute/NSubstitute) - para novos projetos
      - [Moq](https://github.com/moq/moq4) - para projetos antigos ([why](https://www.bleepingcomputer.com/news/security/popular-open-source-project-moq-criticized-for-quietly-collecting-data/))
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

### 13. Observabilidade   

Essas ferramentas fornecem insights em tempo real sobre o desempenho do seu aplicativo, o comportamento do usuário e as taxas de erro, permitindo que você resolva os problemas antes que eles se transformem em problemas graves de forma proativa.

- **Monitorização** centra-se na saúde e disponibilidade de serviços e sistemas, desencadeando frequentemente alertas para condições predefinidas.

- **Telemetria** coleta, processa e transmite dados de sistemas, permitindo a análise de padrões, tendências e anomalias.
- [Prometheus](https://github.com/prometheus/prometheus)
- [Grafana](https://github.com/grafana/grafana)
- [Datadog](https://www.datadoghq.com)
- [ELK Stack](https://www.elastic.co/what-is/elk-stack)
- [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-dotnet)
- [Jaeger](https://www.jaegertracing.io/)
- [Azure Application Insights](https://docs.microsoft.com/azure/azure-monitor/app/app-insights-overview)
- [Azure Log Analytics](https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)

### 14. Conteinerização

As soluções de contêiner encapsulam seu aplicativo .NET, bibliotecas e tempo de execução em contêineres isolados. Isso permite consistência em vários ambientes de desenvolvimento e produção, resolvendo problemas de dependência. Com recursos como sistemas de arquivos em camadas, você pode gerenciar facilmente imagens de contêiner para ASP.NET, .NET Core ou outros serviços .NET, otimizando os tempos de compilação e a utilização de recursos.

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

### 15. Nuvem

Os provedores de nuvem fornecem uma camada de APIs para abstrair a infraestrutura e provisioná-la com base nos limites de segurança e faturamento. A nuvem é executada em servidores em data centers, mas as abstrações dão a impressão de interagir com uma única “plataforma” ou aplicativo grande. A capacidade de provisionar, configurar e proteger rapidamente recursos com provedores de nuvem tem sido fundamental para o tremendo sucesso e complexidade do DevOps moderno.

Os provedores de nuvem mais populares do mercado são AWS e Azure , bem como Google Cloud.

Aqui você deve saber gerenciar usuários e administração, redes, servidores virtuais, etc.

- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Google Cloud](https://cloud.google.com/)

### 16. Integração e entrega contínua (CI/CD)

CI/CD automatiza os estágios de construção, teste e implantação em um pipeline simplificado e resistente a erros. Isso significa lançamentos mais rápidos, correções de bugs e mais tempo para focar no desenvolvimento de recursos.

- [Conceitos de DevOps](https://newsletter.techworld-with-milan.com/p/devops-roadmap-2023)
- Services:
    - [GitHub Actions](https://github.com/features/actions)
    - [Gitlab CI](https://docs.gitlab.com/ee/ci)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [Travis CI](https://travis-ci.org)
    - [Jenkins](https://www.jenkins.io)
    - [TeamCity](https://www.jetbrains.com/teamcity)

### 17. Bibliotecas .NET

Algumas bibliotecas .NET úteis. Observe que nem todas as bibliotecas serão usadas por todos, depende principalmente do projeto em que você trabalha.

- **[MediatR](https://github.com/jbogard/MediatR)** - Implementação do padrão mediador em .NET
- **[Polly](https://github.com/App-vNext/Polly)** -  Biblioteca de tratamento de falhas que permite expressar políticas como Retry e Circuit Breaker.
- **[Fluent Validation](https://github.com/JeremySkinner/FluentValidation)** - biblioteca de validação .NET para construir regras de validação fortemente tipadas.
- **[Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)** - biblioteca .NET para benchmarking.
- **[Refit](https://github.com/reactiveui/refit)** - Transforma sua API REST em uma interface ativa.
- **[YARP](https://microsoft.github.io/reverse-proxy/)** - Servidor proxy reverso.
- **[Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)** - Ferramentas Swagger para documentar APIs construídas em ASP.NET Core.
  
## Considerações adicionais

### Melhores práticas de desempenho

#### Perfil e diagnóstico

Essas ferramentas podem ajudá-lo a identificar e depurar diferentes gargalos de desempenho em seu código. Para isso, você pode utilizar outras ferramentas, como:

- [PerfView](https://joshthecoder.com/2023/10/23/using-perfview-to-diagnose-high-cpu-in-an-aspnet-app.html)
- [Visual Studio Profiler](https://learn.microsoft.com/en-us/visualstudio/profiling/profiling-feature-tour?view=vs-2022)
- [dotTrace](https://www.jetbrains.com/profiler/) and [dotMemory](https://www.jetbrains.com/dotmemory/)

#### Melhores práticas de desempenho

- **Cache** (cache de memória in-mem ou Redis)

- **Otimização de banco de dados** (otimizar consultas, indexação adequada, pool de conexões)

- **Programação assíncrona** (descarrega todas as operações extensas da CPU ou vinculadas a E/S para banco de dados, sistemas de arquivos, sistemas externos)

- **Use o Entity Framework com sabedoria** (use carregamento rápido, projeções e otimizações como consultas compiladas)

- **Gerenciamento de memória** (use tipos de valor e seja cauteloso com gráficos de objetos grandes. Use o padrão de descarte para conexões ou fluxos de banco de dados. Evite boxe/unboxing. Use StringBuilder em vez de String para um grande número de concatenações.)

- **Cache HTTP** (use ETags, cabeçalhos modificados pela última vez)

- **Minimize as viagens de ida e volta** (reduza o número de solicitações HTTP e viagens de ida e volta ao banco de dados)

- **Redes de distribuição de conteúdo** (CDNs) (descarregue ativos estáticos (CSS, JavaScript, imagens) para CDNs para entrega mais rápida aos usuários)

- **Compressão** (habilite a compressão GZIP ou Brotli para respostas HTTP para reduzir o tamanho da transferência de dados)

- **Registro e rastreamento** (evite registro excessivo na produção. Use rastreamento distribuído entre microsserviços).

- **Paralelismo e simultaneidade** (utilize paralelismo e multithreading para tarefas vinculadas à CPU usando classe Parallel ou Task Parallel Library (TPL))

- **Otimização de recursos** (otimize imagens e ativos para a Web para reduzir o tempo de carregamento)

- **HTTP2 sobre SSL** (agora tome decisões inteligentes sobre o conteúdo da página)

- **Meça e monitore o desempenho** (use ferramentas de diagnóstico VS, App Insights ou BenchmarkDotNet)

- **User Span<> em vez de coleções** (spans podem representar uma seção contígua de memória; isso significa que podemos usá-los para operar em arrays)

- **User Span<> instead of collections** (spans can represent a contiguous section of memory; this means we can use them to operate over arrays)

### Segurança e criptografia

A segurança desempenha um papel essencial no desenvolvimento de aplicativos. Os aspectos mais críticos da segurança no mundo .NET são:

- [**Conceitos de autenticação e autorização**](https://learn.microsoft.com/en-us/aspnet/web-api/overview/security/authentication-and-authorization-in-aspnet-web-api):
  - Cookies
  - ASP.NET Core para gerenciamento de usuários
  - .NET OIDC middleware
  - OAuth e OpenID Connect para autenticação de terceiros
  - JWT (JSON Web Tokens) para autenticação baseada em token
  - Autorização baseada em funções e declarações

- [**Conceitos de criptografia e proteção de dados**](https://learn.microsoft.com/en-us/dotnet/standard/security/cross-platform-cryptography):
  - Algoritmos de criptografia simétrica e assimétrica
  - APIs de proteção de dados do .NET Core
  - Hashing e assinaturas digitais
  - Geração segura de números aleatórios

## Recursos adicionais de aprendizagem

- [Pluralsight learning platform](https://www.pluralsight.com/browse?q=C%20sharp&type=all&sort=highest) - Learn C#/.NET mostly from Microsoft MVPs.
- [Awesome .NET!](https://github.com/quozd/awesome-dotnet) - A collection of awesome .NET libraries, tools, frameworks, and software.
- [Microsoft .NET Architecture Guides](https://dotnet.microsoft.com/en-us/learn/dotnet/architecture-guides)

### Livros

- [Learn C# in One Day and Learn It Well](https://amzn.to/3Qld3fT) - the best for beginners
- [C# in Depth: Fourth Edition](https://amzn.to/3ZPcZbq) by Jon Skeet - the best for intermediate
- [Concurrency in C# Cookbook: Asynchronous, Parallel, and Multithreaded Programming](https://amzn.to/490EMtu) - the best for advanced
- [The C# Yellow](http://www.csharpcourse.com/) (free) - the best book overall

### Canais do YouTube

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

## Licença

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Autor

[Filipe Silva](https://milan.milanovic.org) -  Analista II de Backend
