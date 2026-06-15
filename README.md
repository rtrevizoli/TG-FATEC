# Rafael Trevizoli

<p align="center">
  <img src="./assets/rtrevizoli.png" alt="Rafael Trevizoli" width="140"/>
</p>

## Introdução

Este portfólio reúne os projetos desenvolvidos ao longo da minha formação em Banco de Dados pela [Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/). Ingressei no curso em 2019, trazendo uma trajetória prévia na área de desenvolvimento de software, com passagens por diferentes segmentos da indústria.

O curso de Banco de Dados ampliou minha visão técnica, especialmente nas áreas de modelagem de dados, arquitetura de sistemas e desenvolvimento orientado a dados. Ao longo dos semestres, trabalhei com equipes multidisciplinares em projetos reais, aplicando metodologias ágeis e tecnologias variadas para entregar soluções a parceiros acadêmicos.

Atuo principalmente no desenvolvimento backend, com experiência em Java, Python e ambientes containerizados. Tenho familiaridade com bancos de dados relacionais e não relacionais, desenvolvimento de APIs REST e integração de sistemas.

## Meus Principais Conhecimentos

Java e Spring Boot, no desenvolvimento de APIs REST seguras e escaláveis; Python com Django, na construção de backends orientados a dados; Vue.js e TypeScript, no desenvolvimento de interfaces web modernas e componentizadas; PostgreSQL e MySQL, para modelagem relacional, otimização de consultas e controle de migrações; MongoDB, para armazenamento de dados não relacionais; Docker e Docker Compose, na construção de ambientes containerizados e reproduzíveis; Oracle Spatial e GeoTools, para processamento e armazenamento de dados geoespaciais; Swagger, na documentação de APIs REST; AWS e Azure, para hospedagem e deploy de aplicações em nuvem.

## Meus Projetos

<p align="center">
  <a href ="#em-2022-1">  Dynamics </a> •
  <a href ="#em-2024-2">  GSW_API </a> •
  <a href="#em-2025-1">  GeoHood </a> •
  <a href="#em-2025-2"> Athos Insight </a> •
  <a href="#em-2026-1"> EnerSight </a>
</p>


### Em 2022-1

<p align="center">
  <img src="assets/tudo-digital/logo-dynamics.png" alt="Logo Dynamics" width="220"/><br>
  <em>Figura 01 - Projeto Dynamics</em>
</p>

O primeiro projeto integrador do curso de Banco de Dados propôs o desenvolvimento de uma solução de gerenciamento voltada ao controle de processos internos. O desafio envolvia a criação de um sistema capaz de cadastrar produtos, definir regras de promoções e vincular essas promoções aos produtos dentro da plataforma, uma demanda concreta de automação de processos comerciais.

O produto desenvolvido, o Dynamics, foi um sistema web com funcionalidades de cadastro de produtos, categorias e promoções, além do vínculo entre promoção e produto. A aplicação contou com diagramas de entidade e relacionamento, servidor de banco de dados online e wireframes que orientaram o desenvolvimento das telas.

Repo: [Projeto Dynamics](https://github.com/TudoDigital/Dynamics)

### Tecnologias utilizadas

- Java com Quarkus: Framework utilizado no desenvolvimento do backend, com foco em leveza e inicialização rápida.
- SQL Server: Banco de dados relacional escolhido para persistência dos dados de produtos, categorias e promoções.
- Vue.js: Biblioteca JavaScript utilizada no desenvolvimento da interface web da aplicação.
- Maven: Ferramenta de automação de build para gerenciamento de dependências do projeto.

### Contribuições pessoais

Atuei no desenvolvimento das APIs REST principais, incluindo os endpoints de cadastro de produtos, categorias e promoções. Um dos principais desafios foi implementar a lógica de negócio que vinculava promoções a produtos respeitando regras de vigência e compatibilidade, o que exigiu atenção ao modelo de dados e à validação das entradas. Também fui responsável pela implementação da autenticação e autorização, garantindo que diferentes perfis de acesso fossem tratados corretamente no backend.

### Hard Skills

- Desenvolvimento de API com Java e Quarkus: Sei fazer com autonomia;
- Modelagem relacional de banco de dados: Sei fazer com autonomia;
- Desenvolvimento de frontend com Vue.js: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- Liderança técnica: coordenei decisões de arquitetura e orientei o time nas escolhas de implementação ao longo das sprints.
- Resolução de problemas: a tradução das regras de negócio do parceiro em fluxos implementáveis exigiu análise e adaptação constante, especialmente na lógica de vínculo entre promoções e produtos.
- Proatividade: como era o primeiro contato do time com o Quarkus, assumi a responsabilidade de estudar a documentação e propor a estrutura inicial do projeto.


## Em 2024-2

<p align="center">
  <img src="assets/coderhood/logo-gsw-api.png" alt="Logo GSW_API" width="220"/><br>
  <em>Figura 02 - Projeto GSW_API</em>
</p>

O desafio proposto foi criar um mecanismo para mapeamento de portais de notícias estratégicas, com captura rotineira de dados para geração de histórico. A ideia era possibilitar, futuramente, a aplicação de análises baseadas em inteligência artificial para cruzamento de dados e identificação de ações estratégicas de negócio. Essa estrutura deveria ser aplicada também para APIs de fornecimento de dados estratégicos, como previsão do tempo.

A solução desenvolvida foi uma API com funcionalidades de cadastro de portais de notícias, cadastro de APIs externas, cadastro de tags, processo de web scraping para captura e armazenamento de dados, e telas de consulta com filtros. O sistema também oferecia indicação automática de tags relacionadas às notícias, facilitando a categorização e a análise posterior do conteúdo capturado.

Repo: [Projeto GSW_API](https://github.com/FatecCoderHood/GSW_API)

### Tecnologias utilizadas

- Java com Spring Boot: Backend estruturado com base consolidada para o desenvolvimento da API REST.
- JPA e Hibernate: Responsáveis pelo mapeamento objeto-relacional e pela comunicação com o banco de dados.
- MySQL: Banco de dados relacional escolhido para persistência de notícias, portais, jornalistas, tags e demais entidades.
- Vue.js: Utilizado no desenvolvimento do frontend minimalista da aplicação.
- Docker: Utilizado para containerização do ambiente de desenvolvimento.
- Figma: Ferramenta de design para prototipação das interfaces.

### Contribuições pessoais

Participei da definição da arquitetura da API e da implementação dos endpoints de cadastro e consulta. O principal desafio técnico foi modelar e implementar o relacionamento muitos-para-muitos entre notícias e tags de forma eficiente para consultas e capaz de suportar a indicação automática de categorias. Também trabalhei na camada de validação de dados, garantindo que as informações capturadas via scraping fossem armazenadas de forma consistente, mesmo diante de variações no formato dos conteúdos externos.

### Hard Skills

- Desenvolvimento de API REST com Java e Spring Boot: Sei fazer com autonomia;
- Modelagem de banco de dados relacional: Sei fazer com autonomia;
- Web scraping e captura de dados: Sei fazer com autonomia;
- Desenvolvimento de frontend com Vue.js: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- Trabalho em equipe: as decisões de arquitetura foram tomadas em conjunto, o que exigiu abertura para ouvir diferentes perspectivas e chegar a consensos técnicos sem travar o andamento das sprints.
- Comunicação: documentar os endpoints com clareza foi essencial para que o time de frontend conseguisse integrar sem retrabalho.
- Atenção a detalhes: dados coletados via scraping chegam em formatos variados; garantir consistência na camada de validação exigiu cuidado redobrado a cada fonte adicionada.

## Em 2025-1

<p align="center">
  <img src="assets/coderhood/logo-geohood.png" alt="Logo GeoHood" width="220"/><br>
  <em>Figura 03 - Projeto GeoHood</em>
</p>

O quarto semestre trouxe um desafio voltado ao processamento de dados geoespaciais aplicados à agricultura. O objetivo era criar um sistema para cadastro, análise e visualização de áreas agrícolas, com gestão eficiente por meio de dashboards interativos e mapas. O sistema deveria suportar diferentes perfis de usuário com permissões específicas e possibilitar o cadastro de geometrias via upload de arquivos .geojson.

O GeoHood foi desenvolvido como uma aplicação web que importa dados GeoJSON, processa as geometrias e as armazena em banco de dados Oracle Spatial. O sistema oferece consultas geográficas e visualização em mapas, dashboards interativos com filtros e controle de acesso por perfil de usuário, Administrador, Analista e Consultor, cada um com responsabilidades distintas no ciclo de vida das áreas cadastradas.

Neste projeto, atuei como Product Owner, sendo responsável pela definição e priorização do backlog, levantamento de requisitos junto ao parceiro e acompanhamento da evolução das entregas ao longo das sprints.

Repo: [Projeto GeoHood](https://github.com/FatecCoderHood/4_GeoHood)

### Tecnologias utilizadas

- Java com Spring Boot: Backend robusto para as operações de importação, consulta e visualização dos dados geoespaciais.
- GeoTools e JTS: Bibliotecas Java utilizadas para processamento das geometrias e manipulação dos objetos geográficos.
- Oracle Spatial: Banco de dados com suporte nativo a dados geoespaciais, escolhido pela capacidade de armazenar e consultar geometrias.
- Vue 3 com TypeScript: Frontend moderno e modular para as interfaces de visualização e interação com o usuário.
- Figma: Ferramenta de design utilizada na prototipação das telas.

### Contribuições pessoais

A equipe deste semestre se manteve unida a partir do projeto anterior, e a chegada de novos membros foi bem recebida pelo grupo. Esse histórico compartilhado acelerou o alinhamento inicial e trouxe confiança para enfrentar os desafios que viriam. Neste projeto atuei em dupla função: como Product Owner, conduzi o levantamento de requisitos com o parceiro, organizei o backlog e priorizei as entregas a cada sprint; e como desenvolvedor backend, assumi as responsabilidades técnicas mais complexas do ciclo.

Um dos requisitos mais desafiadores foi a necessidade de utilizar o Oracle Database na Oracle Cloud para armazenar dados geoespaciais no formato GeoJSON como polígonos espaciais nativos. A tarefa foi iniciada por outro membro do backend, mas diante da complexidade técnica foi necessário redistribuir as responsabilidades. Um colega ficou responsável pela configuração da conexão com a Oracle Cloud e pela autenticação via wallet criptografada, enquanto assumi a frente de entender o padrão GeoJSON, implementar o sistema de importação e tratamento dos dados e integrar a biblioteca Oracle Spatial ao stack Java do backend.

Durante o desenvolvimento, a licença estudantil expirou sem aviso e a instância do banco na nuvem foi encerrada automaticamente, apagando toda a infraestrutura configurada. Para resolver a situação, entrei em contato com o suporte internacional da Oracle durante a madrugada, identifiquei o ocorrido e reconstruí toda a estrutura em uma nova conta estudantil, incluindo a reconfiguração do banco para aceitar dados espaciais e a reintegração da biblioteca ao projeto Java, com a ingestão completa dos dados GeoJSON funcionando. Fomos o único grupo da turma a entregar esse requisito, e ainda auxiliamos outra equipe a configurar o mesmo ambiente com a respectiva wallet criptografada.

Ao longo das sprints seguintes, enfrentamos um desequilíbrio de comprometimento dentro da equipe. Como resposta, reorganizamos as frentes de trabalho: assumi inteiramente o backend e o banco de dados, enquanto Juan ficou responsável pelo frontend e pela integração performática dos dados ao mapa interativo com Leaflet, um desafio técnico significativo por si só. Os demais membros concentraram suas contribuições em atividades administrativas, cadastrais e de design. A divisão foi desgastante, mas nos permitiu manter o ritmo e entregar um produto funcional dentro dos prazos.

### Hard Skills

- Geoprocessamento com Java: Sei fazer com autonomia;
- Integração com Oracle Spatial: Sei fazer com autonomia;
- Desenvolvimento fullstack com Vue 3 e TypeScript: Sei fazer com autonomia;
- Atuação como Product Owner: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- Resiliência: quando a instância do banco foi encerrada no meio do desenvolvimento, a resposta foi acionar o suporte internacional durante a madrugada e reconstruir toda a infraestrutura do zero, sem perder a sprint.
- Protagonismo: assumi a feature tecnicamente mais complexa do projeto após a redistribuição de tarefas e conduzi a implementação até a entrega final, sem referências anteriores dentro da equipe.
- Colaboração: após resolver o desafio no próprio projeto, compartilhei o conhecimento com outra equipe da turma, auxiliando-a a configurar o mesmo ambiente Oracle Cloud.
- Adaptabilidade: reagir à perda da infraestrutura e à redistribuição de responsabilidades ao longo das sprints exigiu flexibilidade e capacidade de replanejamento sob pressão.
- Liderança: manter o time com entregas consistentes em um contexto de desequilíbrio interno exigiu firmeza na reorganização das frentes e senso claro de prioridade.


## Em 2025-2

<p align="center">
  <img src="assets/athos/logo-athos-insight.png" alt="Logo Athos Insight" width="220"/><br>
  <em>Figura 04 - Projeto Athos Insight</em>
</p>

O Athos Insight é uma plataforma web que centraliza e organiza dados de projetos, transformando-os em informações estratégicas para a tomada de decisão. A aplicação permite monitorar produtividade e horas lançadas por desenvolvedor e projeto, acompanhar custos previstos em relação aos realizados, visualizar dashboards com indicadores financeiros e operacionais, controlar a evolução de tarefas, bugs e issues, e exportar relatórios em PDF. A solução foi hospedada em uma máquina virtual na Microsoft Azure, com capacidade para até 30 usuários simultâneos no ambiente educacional.

Repo: [Projeto Athos Insight](https://github.com/AthosFatecSjc/Athos_Insight)

### Tecnologias utilizadas

- Python com Django: Framework web utilizado no desenvolvimento do backend, escolhido pela robustez e maturidade do ecossistema Python.
- PostgreSQL: Banco de dados relacional utilizado para o Data Warehouse e persistência dos dados analíticos.
- HTMX: Biblioteca utilizada para interações assíncronas no frontend, sem a necessidade de um framework JavaScript pesado.
- Docker: Utilizado para orquestração do ambiente de desenvolvimento e produção.
- Git e GitHub: Controle de versão e colaboração entre os membros do time.
- Figma: Ferramenta de design para criação dos protótipos de interface.
- SonarQube: Utilizado para análise estática de código, garantindo qualidade e padronização ao longo do desenvolvimento.

### Contribuições pessoais

Após o projeto anterior, eu e Juan chegamos ao Athos Insight com maturidade técnica e confiança construídas ao longo de um semestre muito exigente. De forma inesperada, recebemos um convite para integrar um novo grupo que estava se formando na turma. Aceitamos, motivados pela perspectiva de uma distribuição de tarefas mais equilibrada e por acreditar no potencial da equipe. As decisões técnicas e estruturais foram tomadas de forma democrática, o que tornou o processo colaborativo, mesmo quando as escolhas majoritárias foram em direção diferente da que eu defendia. Faz parte do trabalho em grupo.

A situação ficou mais difícil quando membros que participaram de forma decisiva nas votações de stack e arquitetura trancaram o semestre logo no início, deixando o projeto com uma equipe reduzida. O backend e o frontend foram desenvolvidos em Python, uma stack nova para o grupo, o que significou aprender o framework enquanto o produto era construído, como trocar o pneu com o carro em movimento. Ruth, Caique, Juan e eu assumimos a responsabilidade de sustentar o projeto e manter o ritmo das entregas.

Ao longo das sprints, conflitos de código e integrações mal testadas se tornaram parte da rotina. Funcionalidades que funcionavam voltavam quebradas após novos merges, o que gerava ciclos de correção intensos próximos às entregas. Os finais de sprint concentravam uma carga significativa de resolução de problemas: era recorrente que Ruth, Juan e eu ficássemos até tarde corrigindo código, alinhando lógica de negócio e garantindo que as funcionalidades chegassem estáveis na entrega. Esse nível de comprometimento foi necessário para manter a qualidade do produto mesmo diante de um ambiente de desenvolvimento bastante desgastante.

Entregamos o produto. Ao final do semestre, parte do time optou por seguir em outra direção, uma decisão que foi difícil de absorver considerando o esforço coletivo investido por quem permaneceu. A experiência, por mais exigente que tenha sido, reforçou o valor do comprometimento real e da capacidade de manter a qualidade técnica mesmo quando as circunstâncias externas ao código se tornam adversas.

### Hard Skills

- Desenvolvimento de API com Python e Django: Sei fazer com autonomia;
- Modelagem de Data Warehouse: Sei fazer com autonomia;
- Desenvolvimento frontend com HTMX: Sei fazer com autonomia;
- Uso de Docker para orquestração de ambiente: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- Adaptabilidade: aprender e aplicar Python com Django enquanto o produto estava sendo construído exigiu flexibilidade e ritmo de absorção acelerado, sem espaço para uma curva de aprendizado convencional.
- Resiliência: manter o nível de entrega com equipe reduzida, gerenciando conflitos de código recorrentes e sessões longas de correção ao final de cada sprint, foi uma escolha deliberada de não largar o projeto.
- Trabalho em equipe: a entrega final foi sustentada pela parceria entre Ruth, Caique, Juan e eu, um núcleo que se manteve coeso e se apoiou mutuamente ao longo de um semestre muito exigente.
- Resolução de conflitos técnicos: identificar, depurar e corrigir integrações problemáticas antes de cada entrega tornou-se uma responsabilidade recorrente, desenvolvendo agilidade de diagnóstico e comunicação direta sob pressão.


## Em 2026-1

<p align="center">
  <img src="assets/coderhood/logo-enersight.png" alt="Logo EnerSight" width="220"/><br>
  <em>Figura 05 - Projeto EnerSight</em>
</p>

O EnerSight é uma plataforma web analítica desenvolvida para a TECSYS com o objetivo de centralizar, organizar e processar dados públicos da ANEEL. A plataforma automatiza a coleta de conjuntos de dados regulatórios, armazena-os em banco estruturado e permite a análise de indicadores de continuidade como DEC e FEC entre diferentes distribuidoras, regiões e agrupamentos elétricos. Entre as funcionalidades principais estão a coleta automatizada de dados, análise de indicadores, visualização comparativa, gerenciamento de usuários com controle de acesso e registro de logs para rastreabilidade das operações.

Repo: [Projeto EnerSight](https://github.com/FatecCoderHood/EnerSight)

### Tecnologias utilizadas

- Java 21 com Spring Boot 3: Backend moderno com as versões mais recentes do ecossistema Java, garantindo performance e suporte de longo prazo.
- Swagger: Documentação automática da API REST, facilitando o consumo dos endpoints por outras equipes.
- PostgreSQL: Banco de dados relacional para persistência estruturada dos indicadores regulatórios coletados.
- MongoDB: Banco de dados NoSQL utilizado para armazenamento de dados com estrutura variável.
- Docker: Containerização dos serviços do sistema para consistência entre ambientes de desenvolvimento e produção.
- Vue.js 3 com TypeScript: Frontend moderno com tipagem estática e componentização eficiente.
- Vuetify: Framework de componentes UI para Vue.js, utilizado na construção das interfaces visuais.
- Git e GitHub: Controle de versão e colaboração entre os membros do time.

### Contribuições pessoais

O semestre começou com energias renovadas e um novo integrante no grupo. Ruth assumiu o papel de Product Owner e fez um trabalho muito cuidadoso: chegou à reunião de planejamento com um plano estruturado, pensado para facilitar a organização de todos. Em um momento de ceticismo, fiz questionamentos excessivos ao plano sem considerar o quanto ela havia se dedicado. Dias depois, em conversa com outros membros, percebi o erro, procurei ela pessoalmente, me desculpei e agradeci o esforço. Foi um momento importante de autoconhecimento e respeito.

A sprint 1 trouxe problemas estruturais desde cedo: uma tarefa de base do backend que deveria estar pronta antes do início oficial só foi mergeada sete dias após o começo da sprint. Com isso, outros membros que avançaram com suas implementações sem a fundação pronta acumularam PRs com conflitos que se tornaram cada vez mais difíceis de resolver. O processo de revisão ficou excessivamente rígido logo de início, muitas críticas e exigências de alteração na primeira PR, gerando atrasos que se propagaram por todas as entregas posteriores. Neste período, atravessei um momento pessoal muito difícil: a hospitalização e o falecimento da minha avó exigiram viagens frequentes e me afastaram do projeto em um momento crítico para o grupo.

Ao retomar, identifiquei um problema recorrente no backlog: tarefas criadas sem avaliação crítica descreviam a mesma implementação de formas diferentes, distribuídas entre membros distintos. Passei uma madrugada implementando todos os pontos de uma tarefa para descobrir, no dia seguinte ao registrar a entrega no Jira, que outro membro tinha uma tarefa diferente com a mesma demanda. Comuniquei diretamente o colega sobre o problema. Nesse contexto, o PO pediu saída e outros membros decidiram formar um grupo próprio.

A decisão foi encarada como uma oportunidade. Convenci Juan e Renato a abandonarmos o código anterior e começarmos do zero: novo grupo, nova empresa, novo produto. Assumi o backend integralmente, Juan ficou com o frontend e a função de PO, e Renato com as documentações e o cargo de SM. Com apenas duas sprints restantes, definimos um plano objetivo, primeira sprint para construir o produto, segunda para validar as matérias, e trabalhamos no ritmo e no clima de uma startup. Entregamos o EnerSight com qualidade que, na minha avaliação, representou o melhor produto técnico da turma. Na sprint final, recebemos Lucas e Vinícius, que desenvolveram a frente de séries temporais e previsibilidade com alto nível de dedicação e entrega.

### Hard Skills

- Desenvolvimento de API com Java 21 e Spring Boot 3: Sei fazer com autonomia;
- Integração com fontes de dados públicas: Sei fazer com autonomia;
- Modelagem e consulta em PostgreSQL: Sei fazer com autonomia;
- Desenvolvimento frontend com Vue.js 3 e TypeScript: Sei fazer com autonomia;
- Uso de Docker para orquestração: Sei fazer com autonomia;
- Documentação de API com Swagger: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- Autoconhecimento: reconhecer que minha postura inicial no planejamento foi inadequada para o momento e corrigi-la diretamente com a colega foi um exercício de maturidade e autocrítica que impactou positivamente a dinâmica do grupo.
- Resiliência pessoal: manter o comprometimento profissional durante um período de perda pessoal significativa foi o desafio mais humano do semestre.
- Tomada de decisão: propor o recomeço do zero, descartando o trabalho acumulado em favor de uma equipe alinhada e de um produto viável, foi uma escolha difícil e que se mostrou acertada.
- Protagonismo: assumir a liderança técnica do backend no novo grupo e entregar dentro dos prazos reduzidos exigiu autonomia total e foco nas prioridades certas.

## Contatos

- [GitHub](https://github.com/rtrevizoli)
- [LinkedIn](https://www.linkedin.com/in/rafael-trevizoli/)