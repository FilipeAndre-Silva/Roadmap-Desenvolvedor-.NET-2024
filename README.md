# Roadmap Desenvolvedor .NET 2024

Este é um roadmap para se tornar um Desenvolvedor .NET, com listagens, conteúdos e links organizados para seu aprendizado.

## Orientaçãoes sobre o roadmap

> Este roadmap pretende dar-lhe uma ideia sobre o que aprender para se tornar um Desenvolvedor .NET em 2024. O roteiro irá guiá-lo se você precisar de esclarecimentos sobre o que aprender e onde, em vez de encorajá-lo a escolher o que está na moda e na moda. O conteúdo desse documento é proveniente de experiências e pesquisas pessoais do autor.

> Todas as referências de terceiros vão ser citadas, preservando assim os direitos autorias dos mesmos. 

## ROADMAP

### 1. C#

O [C#](https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/) (pronuncia-se "C Sharp") é uma linguagem de programação moderna, orientada a objeto e fortemente tipada. O C# permite que os desenvolvedores criem muitos tipos de aplicativos seguros e robustos que são executados no .NET.

Você precisa entender os diferentes recursos da linguagem C# , como:

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

**Recursos**:

- [Microsoft Aprenda C#](https://dotnet.microsoft.com/en-us/learn/csharp).
- [Microsoft C#](https://learn.microsoft.com/en-us/shows/csharp-101/)
- [Aprenda a CLI dotnet](https://docs.microsoft.com/dotnet/core/tools)
- [Gerenciador de pacotes NuGet](https://learn.microsoft.com/en-us/nuget/what-is-nuget)
  
### 2. Habilidades Gerais de Desenvolvimento

Dominar padrões de design, código limpo e controle de versão, como o Git, é fundamental para desenvolver código eficiente e facilmente mantido em ambientes colaborativos. Essas práticas não apenas aprimoram a qualidade do código, mas também diferenciam um programador comum de um engenheiro de software qualificado.

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
    - [Aprenda Design Orientado a Domínio](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/february/best-practice-an-introduction-to-domain-driven-design)
      
### 3. ASP.NET Core 

ASP.NET é uma estrutura popular de desenvolvimento na Web para a criação de aplicativos Web em Plataforma .NET.

O [ASP.NET Core](https://dotnet.microsoft.com/pt-br/learn/aspnet/what-is-aspnet-core) é a versão de código aberto do ASP.NET, que executa no macOS, Linux e Windows. O ASP.NET Core foi lançado pela primeira vez em 2016 e é um novo design de versões anteriores somente para Windows do ASP.NET.

- Noções básicas da Web:
  - [Como funciona a Internet](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)
  - O que acontece quando você digita um URL no seu navegador?
  - Como funciona o DNS
  - [Protocolo HTTP(S)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) 
- [ASP.NET MVC](https://dotnet.microsoft.com/en-us/apps/aspnet/mvc)
- [Middlewares](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware)
- APIs
  - [Web API](https://dotnet.microsoft.com/en-us/apps/aspnet/apis)
  - [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis?view=aspnetcore-8.0)
  - Protocolos
    - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
    - [GraphQL](https://graphql.org/)
    - [gRPC](https://grpc.io/)
  - Práticas recomendadas de design de API REST
  - Compreendendo os cabeçalhos REST
- Injeção de dependência
  - [Ciclos de vida](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection)
  - [Injeção de dependência de extensões da Microsoft](https://learn.microsoft.com/en-us/dotnet/api/microsoft.extensions.dependencyinjection?view=dotnet-plat-ext-7.0)
  - [Autofac](https://autofac.org/)
  - [Scrutor](https://github.com/khellang/Scrutor)
- [Configurações e configurações do aplicativo](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration)
- [Filtros e atributos](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters)
- Segurança
  - [Authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication) or [este tópico do Reddit](https://www.reddit.com/r/dotnet/comments/we9qx8/a_comprehensive_overview_of_authentication_in/)
  - [Authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction)
  - [IdentityServer](https://identityserver4.readthedocs.io/en/latest)
  - [Auth0](https://auth0.com)
  - [OIDC](https://openid.net/connect)

### 4. Client-Side .NET

Caso deseje desenvolver interfaces de usuário em .NET, será necessário utilizar essas estruturas. O Razor destaca-se como um mecanismo de modelo para gerar HTML dinâmico, ao passo que o Blazor amplia essa capacidade, possibilitando a criação de interfaces interativas para a web utilizando C#, em substituição ao JavaScript. O MAUI, por sua vez, representa uma evolução do Xamarin, direcionado à construção de aplicativos móveis multiplataforma. Já o Windows Presentation Foundation (WPF) emerge como uma estrutura para a criação de interfaces em aplicativos clientes de desktop.

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

O mapeamento objeto-relacional (ORM) desempenha o papel de um intermediário tradutor entre o seu código C# orientado a objetos e o banco de dados relacional. Ele simplifica a tarefa árdua de redigir consultas SQL para operações CRUD básicas. Ao utilizar estruturas ORM como o Entity Framework, torna-se possível manipular dados como se fossem objetos no seu código, conferindo-lhe maior legibilidade e facilidade de manutenção. Esse enfoque agiliza o processo de desenvolvimento, reduzindo erros e permitindo que você se concentre nas lógicas de negócios mais complexas, em vez de lidar com a sintaxe específica do banco de dados.

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

O cache funciona como a memória de curto prazo do seu aplicativo, retendo dados frequentemente acessados para uma recuperação rápida, evitando assim sobrecarregar o banco de dados. Ao aliviar a carga do banco de dados e otimizar o acesso aos dados, o cache proporciona ao seu aplicativo a vantagem competitiva necessária para atender às exigências dos usuários por responsividade e disponibilidade.
**Resources**:

- [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
- [Redis](https://redis.io/)
- Application-Level
   - [Built-in](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/response)
   - [Output Caching](https://learn.microsoft.com/en-us/aspnet/core/performance/caching/output?source=recommendations)

### 8. Logging

O registro(Logging) é responsável por capturar dados de tempo de execução, erros e outras informações essenciais que facilitam a identificação e correção rápida de problemas, contribuindo para tornar seu aplicativo mais confiável e seguro. Estruturas de registro como NLog ou Serilog integram-se de maneira fluida ao ambiente .NET, oferecendo uma ferramenta de diagnóstico em tempo real crucial para monitorar a saúde do aplicativo, solucionar questões e até mesmo obter insights valiosos para orientar o desenvolvimento futuro.

**Resources**:

- [Serilog](https://github.com/serilog/serilog)
- [NLog](https://github.com/NLog/NLog)
- [Microsoft.Extensions.Logging](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging)

### 9. Comunicação


No ecossistema .NET, a comunicação se desdobra em três formas: comunicação em tempo real, comunicação síncrona e comunicação assíncrona. Tecnologias de comunicação em tempo real, como o SignalR, estabelecem funcionalidades mantendo uma conexão contínua entre servidor e cliente. A comunicação síncrona ocorre predominantemente por meio do cliente HTTP, enquanto a comunicação assíncrona se vale de diversas estruturas e bibliotecas baseadas em mensagens e eventos.


Os sistemas de mensagens atuam como intermediários entre diferentes partes do seu sistema, permitindo que elas se comuniquem sem uma conexão direta. Por outro lado, os manipuladores de eventos são utilizados para lidar com eventos dentro de um único aplicativo, facilitando um modelo editor-assinante. Nesse modelo, uma parte do aplicativo pode gerar um evento ao qual outras partes podem reagir de forma adequada. Essas abordagens proporcionam flexibilidade e eficiência na comunicação entre os componentes do sistema.

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

Esses serviços realizam tarefas em segundo plano, permitindo que seu aplicativo direcione sua atenção para as interações do usuário. Seja para processamento de dados, envio de e-mails automatizados ou execução de limpezas periódicas, os serviços em segundo plano asseguram que essas atividades não afetem nem interrompam a experiência do usuário, garantindo um funcionamento suave e contínuo do aplicativo.

**Recursos**:

- [Background Service](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
- [HangFire](https://github.com/HangfireIO/Hangfire)
- [Quartz](https://github.com/quartznet/quartznet)

### 11. Mapeamento de objetos 

As bibliotecas que disponibiliza automatizam a tarefa de mapeamento entre objetos, eliminando a necessidade de codificação manual repetitiva e sujeita a erros. Esse processo aprimora a produtividade e reduz a incidência de bugs, especialmente ao lidar com modelos complexos e objetos de transferência de dados (DTOs).

**Resources**:

- [AutoMapper](https://github.com/AutoMapper/AutoMapper)
- [Mapster](https://github.com/MapsterMapper/Mapster)

### 12. Testes

Os testes unitários direcionam sua atenção para partes isoladas do código, os testes de integração asseguram a harmonia entre diferentes componentes, e os testes ponta a ponta validam toda a jornada do usuário no seu aplicativo. Juntos, esses testes constituem uma rede de segurança, identificando bugs precocemente, simplificando a depuração e fortalecendo sua base de código, tornando-a robusta e fácil de manter.

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

Essas ferramentas oferecem informações em tempo real sobre o desempenho do seu aplicativo, o comportamento do usuário e as taxas de erro, capacitando-o a abordar questões antes que evoluam para problemas significativos de maneira proativa.

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

As soluções de contêiner encapsulam seu aplicativo .NET, suas bibliotecas e o ambiente de execução em contêineres isolados. Essa abordagem possibilita a consistência em diversos ambientes de desenvolvimento e produção, resolvendo problemas de dependência. A implementação de recursos como sistemas de arquivos em camadas permite a gestão eficiente de imagens de contêiner para ASP.NET, .NET Core ou outros serviços .NET, otimizando os tempos de compilação e a eficiência na utilização de recursos.

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

Os provedores de nuvem disponibilizam uma camada de APIs para abstrair a infraestrutura e realizar o provisionamento com base em parâmetros de segurança e faturamento. Embora a nuvem opere em servidores localizados em data centers, as abstrações criam a ilusão de interação com uma única "plataforma" ou aplicativo abrangente. A habilidade de provisionar, configurar e proteger rapidamente recursos por meio dos provedores de nuvem tem sido essencial para o notável sucesso e a complexidade do DevOps moderno.

Os provedores de nuvem mais populares do mercado são AWS e Azure , bem como Google Cloud.

Aqui você deve saber gerenciar usuários e administração, redes, servidores virtuais, etc.

- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Google Cloud](https://cloud.google.com/)

### 16. Integração e entrega contínua (CI/CD)

A integração contínua e a entrega contínua (CI/CD) automatizam os estágios de construção, teste e implementação em um pipeline simplificado e resistente a erros. Esse processo resulta em lançamentos mais rápidos, correções de bugs eficientes e mais tempo disponível para se concentrar no desenvolvimento de novos recursos.

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
- [dotTrace](https://www.jetbrains.com/profiler/) e [dotMemory](https://www.jetbrains.com/dotmemory/)

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

### Canais do YouTube

- [Lucas Montano](https://www.youtube.com/@LucasMontano)
- [Daniel Avelar - Programação Além do Código](https://www.youtube.com/@DanielAvelar)
- [LuisDev](https://www.youtube.com/@luisdev)
- [Milton Sampaio - Programação](https://www.youtube.com/@MiltonSampaioProgramacao)
- [Bolt](https://www.youtube.com/@boltjz)
- [Alura](https://www.youtube.com/@alura)
- [mano deyvin](https://www.youtube.com/@manodeyvin)
- [Attekita Dev](https://www.youtube.com/@attekitadev)
- [Área Tech Brasil](https://www.youtube.com/@AreaTechBrasil)
- [Daniel Jesus](https://www.youtube.com/@DanielJesusNet)
- [balta.io](https://www.youtube.com/@baltaio)
- [Nick Chapsas](https://www.youtube.com/@nickchapsas/videos)
- [Canal dotNET](https://www.youtube.com/@CanalDotNET)
- [Azure na Prática](https://www.youtube.com/@AzurenaPratica)
- [.NET Foundation](https://www.youtube.com/@NETFoundation)
- [DEV NET CORE Valdir Ferreira](https://www.youtube.com/@devnetcore)
- [Jose Carlos Macoratti](https://www.youtube.com/@josecarlosmacoratti)
- [Código Fonte TV](https://www.youtube.com/@codigofontetv)
- [Diogo Costa Dev](https://www.youtube.com/@diogocostadev)
- [Patrick God](https://www.youtube.com/@PatrickGod)
- [Dev Fico](https://www.youtube.com/@devfico)
- [CodeTotal](https://www.youtube.com/@CodeTotal)
- [Alexandre B L](https://www.youtube.com/@abrandaol)
- [Aprenda a programar de graça](https://www.youtube.com/@programedegraca)
- [André Secco](https://www.youtube.com/@AndreSecco)
- [Filipe Brito · BraboDev](https://www.youtube.com/@filipebritodev)
- [Code Yourself](https://www.youtube.com/@abrandaol])
- [Curso De Tecnologia](https://www.youtube.com/@cursodetecnologia)
- [Central dotNET](https://www.youtube.com/@CentraldotNET)
- [Manual do Programador](https://www.youtube.com/@manualdoprogramador1653)
- [Luiz Carlos Faria](https://www.youtube.com/@luizcarlosfaria)
- [Fabio Akita](https://www.youtube.com/@Akitando)
- [Alexandre B L](https://www.youtube.com/@abrandaol)
  
## Licença

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Autor

[Filipe Silva](https://milan.milanovic.org) -  Analista II de Backend
