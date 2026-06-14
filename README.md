Curso Formação Arquitetura de Software no nextwave(LuisDEV)

### O que é Arquitetura de Software
 - De maneira simples, arquitetura no contexto de software se refere a construir um sistema para um cliente
 - Também é descrita como composição, integração e interação de componentes em um sistema
 - Desse ponto de vista, todo sistema tem uma arquitetura de software. Porem, é de entendimento comum que existem arquiteturas boas e arquiteturas não tão boas.
 - Algo que será discutido mais para frente no curso é sobre as consequências de uma má arquitetura de software, como:
   - Dificuldade em se entender
   - Dificuldade em se modificar
 - Isso resulta em entregas mais lentas e com maior índice de defeitos
 - Por outro lado, uma boa arquitetura resulta em sistemas mais fáceis de entender, com código e estrutura legíveis e de melhor manutenção, resultando em entregas mais rápidas    e com menos bugs
 - Definição de arquitetura a partir de norma
   - Existia a norma 1471 ANSI/IEEE que define Arquitetura de Software desde setembro de 2000
     - Recommended practice for architectural description of software-intensive systems
   - Foi substituído pela norma ISO/IEC 42010
     - Mais detalhes sobre ela em https://www.iso.org/standard/74393.html
   - Embora a maior parte dos programadores realmente não ligam para essas normas, existem muitas informações interessantes nela aplicáveis em nossos projetos

### Arquitetura: Construção x Software: faz sentido comparar?
 - Pelo termo similar, é comum associarmos Arquitetura de Software a Arquitetura relacionada a construção civil
 - Uma diferença fundamental é a respeito ao processo de planejamento e execução de ambas arquiteturas
   - Na construção civil, existe um imenso trabalho de desenho da arquitetura ANTEs de sua execução, com planos muitos detalhados. Nela também os seus artefatos são caros e      complexos, dificultando muito uma mudança em tempo real no projeto aprovado.
 - Uma diferença fundamental é a respeito ao processo de planejamento e execução de ambas arquiteturas
   - Já no planejamento e desenvolvimento de Software, os requisitos são constantemente definidos e refinados (e até removidos), exigindo agilidade que não pode ser              comparada a arquitetura da construção civil

  ### Identificação de Requisitos
   - As funções de um sistema são definidas através de um conjunto de requisitos
   - Esses requisitos podem influenciar a arquitetura do sistema
   - Tipos de requisito
     - Requisitos funcionais
     - Requisitos não-funcionais
   - Requisitos Funcionais
     - Define uma ação necessária do sistema
     - Uma função é descrita através de entrada, comportamento, e saída
     - Geralmente falta uma descrição mais detalhada do comportamento esperado das funções de sistema
   - Requisitos Não-Funcionais
     - Define um atributo do sistema que foi explicitamente solicitado por algum dos stakeholdes
     - Alguns exemplos
       - Escalabilidade
       - Segurança
       - Acessibilidade

### Arquitetura de Software x Modelo Waterfall
 - Upfront Architecture (Arquitetura Adiantada/Antecipada)
   - Definição da arquitetura do sistema completa e definida antes de se iniciar o projeto
   - Programação nesse modelo é visto como a implementação das ideias definidas em instruções de software
 - Modelo Waterfall
   - Datado da década de 1970, define uma sequencia de fases para o desenvolvimento de software
   - Cada fase precisa estar complete antes de avançar para a próxima
   - São elas:
     - Definição de Requisitos
     - Desenho
     - Implementação
     - Verificação
     - Manutenção
   - Falha em se adaptar a dinâmica normal de criação de softwares
   - A maior parte dos projetos ultrapassam o orçamento e prazos, muitas vezes até entregando funcionalidades que não atendem os requisitos definidos
   - A realidade é diferente
     - Requisitos mudam muito rápido, muitas vezes sendo criados novos e até removidos alguns que se acreditar agregar valor no projeto
     - Por essa razão, o modelo Waterfall não atende aos cenários modernos de software por ignorar a dinâmica do desenvolvimento de software e focar excessivamente em             planejamento. 

### Arquitetura Emergente
 - Quanto antes o time começar a desenvolver, mais cedo vai conseguir feedback e melhorar a qualidade do software
 - É comum que em projetos de software se tenha arquitetura inicial, similar a outros projetos da empres, como um boilerplate
 - A arquitetura deve suportar alterações frequentes e entrega de valor acelerada
 - Arquitetura Emergente (ou Emerging Architecture) é o processo composto pela construção incremental do software.
 - Apos o início, o projeto passa por diversas iterações compostas por fases do desenvolvimento de software, como desenho, implementação e teste
 - Quando um projeto que utiliza metodologias ágeis é iniciado, apenas alguns requisitos são definidos, sendo refinados ou surgindo novos ao longo do projeto
 - No inicio de cada iteração ou sprint os requisitos a serem implementados são definidos, e no final uma entrega de software funcional é feita

### O que é Arquiteto de Software e Suas Responsabilidades
 - Profissional responsavel por unir os requisitos e as especificações do sistema
 - Responsavel pela arquitetura do sistema
 - Interage com analistas de negocio e gerentes de projeto, avaliando e recomendando opções de soluções para o projeto, além de coordenar um time de programadores
 - Principais Responsabilidades:
   - Identificação de requisitos
   - Divisão do sistema em componentes
     - O desenho da solução é influenciado pelo requisitos
   - Identificação e avaliação de tecnologias
     - O arquiteto deve conhecer os custos e beneficios associados a diferentes tecnologias e produtos, propondo o uso de algum(s) deles em cenários que sejam beneficios ao projeto.
   - Formular especificações
     - Forma de comunicar as decisões arquiteturais ao time de desenvolvimento
     - Alguns formatos comumente utilizados são os diagramas UML, documentos de word, Wikis e etc

### Mito sobre Arquiteto de Software
 - Um grande mito existente no mercado é que o Arquiteto de Software não deveria escrever codigo
 - Na minha opinião, arquitetos não deveriam estar em um patamar diferente dos programadores em equipes de desenvolvimento
 - São profissionais bons e experientes, que têm grande exposição a código, e que após a definição do desenho do sistema, trabalham juntos com os programadores para garantir a implementação adequada
 - Logo, arquitetos são programadores com amior experiência e formação
 - No final, quanto mais experiente um programador é, mais comumente ele discuta sobre desenho da solução, boas práticas de escrita de código, escolha de ferramenta, entre outros tópicos
 - A evolução para um perfil de Arquiteto de Software acaba sendo natual na carreira de programadores

### O que é Sucesso em Projetos de Software
 - Uma pergunta que parece ser simples mas ao mesmo tempo completa é: o que é sucesso em um projeto de software ?
   - Um projeto que utiliza más práticas mas entrega as funcionalidades prometidas ?
   - Um projeto que utiliza as melhores práticas mas com funcionalidades que não atendem o que o cliente precisa ?
 - Um projeto de software bem-sucedido entrega uma solução funcional a necessidades do negócio
 - Um desenho de software bem-sucedido utiliza as melhores práticas em desenho de código e arquitetura, através das tecnologias disponiveis, para entregar o projeto de software
 - É claro que o software deve atender as necessidades do negócio, mas software de má qualidade é algo que deve ser evitado a todo custo.
 - Software de má qualidade pode causar danos financeiros de diversas formas as empresas
   - Paginas lentas que afastam usuarios ( antes mesmo de entrar no site)
   - Interface de usuario ruim que resulta em má usabilidade e fluxos ruins para o usuario utilizar os serviços disponiveis
   - Falta de resiliencia em situações de falhas de componentes terceiros da arquitetura 

### O que é "Big Ball of Mud"
 - Software que cresce de maneira descontrolada, resultando em software que é dificil de se manter
 - Não apresenta estrutura clara em sua maior parte, contendo diversos componentes altamente adoplados entre si, além de duplicações de código, e pouca separação de camadas e responsabilidades
 - É comum se encontrar sistemas que foram desenvolvidos de maneira acelerada e que, apos alguns ajustes descuidados, "atendeu" o seu objetivo, se tornando um sistema legado a ser mantido e (temido)

### Causas da "Big Ball of Mud"
 - A Big Ball of Mud não inicia grande causando irreversíveis ao projeto
 - Existem algumas cauas raízes possiveis do Ball Ball of Mud
 - Falha na identificação de requisitos
   - O Software tem uma série de objetivos, expressados através do que o cliente quer alcançar, e quais problema quer resolver
   - O problema aqui ocorre na transformação de requisitos expressados para funcionalidades implementadas em código.
   - Dos objetivos de diferentes stakeholders em relação ao sistema, uma lista deve ser definida paa validação
 - Imprecisão em estimativas
   - A area de negocio sempre vai querer saber extamente em qual a funcinalidade vai ser entregue, focando sempre em expressoes de alto nível
 - Falta de testes
   - Diversos niveis de testes podem existir em um projeto
     - Testes Unitarios para verificar o comportamento de componentes individuais de código (Teste Unitário para testar o comportamento)
     - Testes de Integração para verificar o comportamento dos componentes macros quando inseridos em um ambiente Com componentes de infraestrutura, como bancos de dados e serviços de nuvem
     - Testes de Aceitação que validam o caminho real da aplicação, interagindo geralmente com um browser de maneira automatizada
  - Falta de responsabilidade pelo projeto
  - Ignorar crise no projeto

### Custo de Código Bom x Ruim
 - Embora muitos projetos sobrevivam, mesmo que muito código ruim, é inegável que os danos financeiros causados são muito grandes
 - Nesse contexto, código ruim é mais caro que código bom.Ponto.
 - Por mais que sair copiando e colando código pelo projeto, pular escrita de testes, falta de revisão e tudo mais, dê a impessão de aceleração do projeto, isto ocorre apenas no curto prazo.
 - Projetos que durarem mais que o curto prazo vaõ sofrer da falta de qualidade nas atividades comuns de escrita de código
   - Debugging
   - Solução de bugs
   - Manutenção e evolução de código
 - Código que "apenas funciona" é mais barato de desenvolver, mas muito mais caro para manter e evoluir.            

### Ferramentas de Checagem de Código
 - Uma boa manutenção de código é alcançada através de código bem escrito. Isso inclui conhecimento de princípios de desenvolvimento, bons pradrões e práticas de projeto, testabilidade e recursos de linguagem
 - É necessário reforçar a melhora de código de maneira contínua, não apenas noss famosos TODOs (que estão mais para "TODO sempre")
 - Para isso, utilizar ferramentas de suporte e checagem de código é essencial.
 - Ferramentas de suporte a código incluem as que já vem em algumas IDEs. Funcionalidades como auto-complete, atalhos para geração de código, nomenclatura de variaveis, entre outros.
 - O exemplo mais popular deste tipo de ferramenta é o ReSharper, que além das funcionalidades anteriores também inclui uma excelente função de refatoração
 - Já as ferramentas de checagem de código auxiliam bastante na análise do seu código, detectando uma grande quantidade de itens de atenção no seu projeto, como
   - Bugs
   - Code Smells
   - Indice de manutenção e Confiabilidade
   - Cobertura de código
   - Duplicação de código
 - O SonarQube/SonarCloud é uma ferramenta bem popular de checagem de código, analisando os pontos tratados anteriormente, além de oferecer remediação nos erros apresentandos
 - Também permite criar Quality Gates baseados nas métricas criadas, definindo então um padrão minimo para o codigo "passar" na avaliação
 - Finalmente, é ossivel também realizar análise de código apenas em um Pull Request, garantindo também que o código esteja aderante aos padrões de qualidade adotados.

### O que é Code Review
 - O Code Review, ou Revisão de Código, é uma avaliação sistemática de código produzido seguindo uma série de parametros definidos
   - Idealmente, que estejam documentados, para facilitar o processo
 - Basicamente, o processo do Code Review segue o seguinte fluxo
   - Uma pessoa se torna revisor de código do autor, de uma tarefa
   - Ela analise o código em busca de inconsistencias aos padrões, e também de potenciais problemas de performance, segurança e etc
   - Feedback é adicionado através de ferramenta, e repassado ao autor
 - É uma boa prática ter um documento para guiar o processo
   - Oferece valor tanto para quem vai revisar, quanto para quem vai desenvolver
   - Sem ele, é mais comum que programadores cometam erros que já foram submetidos a Code Reviews anteriores, e que não foram documentados. Além disso, revisores podem ficar sem um "norte" e irem mais por intuição do que um padrão adotado pela equipe, resultando em revisões menos assertivas e atritos
 - Beneficios do Code Review
   - Maior qualidade de código
     - Fazer com que o código produzido pela equipe passe pelo processo de Code Review resulta em maior qualidade deste. Ele auxilia, entre outras coisas, a
       - Produzir c´doigo com uso de melhores práticas
       - Remover código desnecessario ou não utilizado
       - Melhorar a legibilidade
    - Eliminação de Bugs
      - Code Reviews podem ser uma maneira mais "barata" de descobrir bugs do que testes (mas não substitui)
      - Os tipos de bugs que normalmente são mais encontrados nessa fase são:
        - Logica e desenho utilizados para resolver o problema
        - Segurança
        - Tratamento (ou a falta dele) de excessões
        - Performance
     - Evita o surgimento de salvadores da pátria
       - Com a revisão de código, evita-se que uma pessoa seja a detentora universal de uma solução, sendo a única capaz de resolver problemass nos modulos desta. E se essa pessoa ficar doente ou sair da empresa ?
       - Diferentes membros da equipe terão conhecimento sobre os modulos que estão sendo desenvolvidos, e isso contribui para um ambiente mais saudavel
    - Obstaculos ao Code Review
      - Prazos curtos
        - Se prazos curtos são a norma no projeto, é muito dificil convencer a gerencia sobre a importancia deles e justificar o tempo adicional ao final das tarefas para garantir a revisão do código
        - Apresentar os beneficios, nesse caso     
      - Fator humano
        - Alguns programadores são lidam bem com feedbaks sobre seu código
        - Alguns programadores não ligam de fazer o Code Review direito

### O que é Código Legado
 - Código existente que herdamos e que precisamos manter, dar suporte ou simplesmente integrar com outro sistema
 - Geralmente dificil de se substituir, já que negociso inteiros forma e são construidos através de tecnologias que hoje em dia é considerada ultrapassada
 - Muito dificil nunca interagir com projetos desse tipo em nossa carreira
 - O maior problema é realizar manutenções ou evoluções nesse software
 - Porém, algo que poucos programadores se atentam é que é possivel melhorar codigo legado, através da refatoração
 - Para isso, é necessario entender quais técnicas existem para refatorar código, isto é, realizar melhorias na qualidade dele sem afetar a funcionalidade implementada
 - E é exatamente o medo de "quebrar tudo" que impede a maioria dos programadores de tentar melhorar
 - O livro "Trabalho Eficaz com Código Legado" é fantastico para isso, apresentando diversas informações e técnicas para refatorar código legado, em diversas situações
 - "Código legado é código sem testes"
 - Passos para melhorar um código legado
   - Parar a escrita de novo código
   - Refatorar o código, separando em componentes
   - Cobrir com testes, para dar segurança nas proximas refatorações
   - Refatorações contínuas


### Orientação a Objetos
 - Antes do conceito de Orientação a Objetos existir, a programação era procedural
 - Isso resultava em um grande fluxo de código contendo rotinas que executavam os passos necessários
 - Com o surgimento da OO, começou a ser possivel criar programas através de interações entre os objetos, com seus dados e comportamentos próprios.
 - Entre as atividades envolvidas no desenho orientado a objeto estão
   - Identificar objetos
   - Extrair classes a partir deles
   - Definir interfaces e heranças
   - Estabelecer relacionamentos entre eles
 - Tópico muito comum em entrevistas para cargos de programador, tanto nacionais quanto internacionais. 

### Orientação a Objetos - Como extrair Classes
 - Antes mesmo de chegarmos ao tema de extração de classes, algo essencial é a identificação de objetos
 - Quando se fala de Orientação a Objetos, é comum se dizer que o mundo a nossa volta tem "objetos", como caixas eletrônicos, mesas, ou pessoas
 - Classes são utilizadas para associar objetos identificados para o dominio do software
 - A partir dos requisitos e casos de uso são extraidas as hierarquias de classes e seus relacionamentos
 - Uma abordagem comum para identificação de objetos é através da narrativa apresentada nos casos de uso, onde seriam identificados os substantivos e verbos
 - Substantivos dariam origem a classes ou propriedades, e verbos a métodos
 - Classe: Pedido (de delivery), cliente, funcionario
 - Casos de uso: Visualizar Pedidos de Delivery por Cliente

 ### Orientação a Objetos - Programar para Interfaces (Sempre)
  - Toda vez que utilizamos uma classe, criamos um acoplamento do código consumidor e a classe
  - Caso a classe esteja indisponivel, o código não compila
  - Por exemplo, imagine uma classe UserSevice com método GetUserConfiguration, que obtém uma configuração padrão de usuário da cache, e se não existir, obtém do repositório de dados e salva na cache
  - Caching é m cross-cutting concern, que corresponde a funcionalidade que não esteja associada a requisitos especifico da classe
  - Alguns outros exemplos de cross-cutting concerns são autenticação, logging, validação e threading
  - Para esses casos, para evitar acoplamento, a decomposição dessas responsabilidades pode ser feita com o uso de padrões como Dependency Injection ou Service Locator.
  - Ao utilizarmos interface podemos escrever testes unitários
  - Um passo a passo para realizar essa decomposição é:
    - Extrair uma interface a partir da classe
    - Utilizar a interface extraída no código-fonte consumidor, através de injeção de dependência
      <img src="Images/Interface_ICacheService.png" alt="Arquitetura de Software" width="600">
    - Com a decomposição feita, será possivle que a classe UserSerivce possa trabalhar com qualquer implementação do ICacheService, resultando em desacoplamento e também e permitindo a escrita de testes unitários

### Os 4 pilares da POO
 - Os quatro pilares da Programação Orientada a Objetos são:
   - Abstração
   - Encapsulamento
   - Herança
   - Polimorfismo
 - Pergunta muito comum em entrevistas: quais são os pilares da POO e o que cada um significa ?
 - Abstração
   - Técnica que permite esconder do código consumidor/cliente detalhes de implementação, através do agrupamento de características e comportamentos
   - REsulta na separação do código para um método ou classe separados
   - Auxilia na melhoria da qualidade e legibilidade do código, por separar responsabilidades dentro da aplicação
   - O próprio padrão Repositorio é uma abstração do acesso a dados
   - Exemplo
     - Em um serviço de aplicação implementamos o caso de uso CadastrarAluno
     - Não somente a persistencia é feita, mas também operações como sincronização com ERP através de HTTP, salvamento de dados em cache, e publicação de mensagem em fila
     - Se todas essas funcionalidades estiverem implementadas diretamente no serviço, o código vai ser dificil manutenção e pouso testável
     - Ao invés disso, podemos extrair classes ( e em seguida, interfaces) contendo código responsavel por persistencia, mensageria, chamadas HTTP e Caching
     - Com isso, o código se torna mais limpo e testável
 - Encapsulmanento
   - Técnica que permite controlar o acesso de código cliente a dados e comportamentos internos de uma classe
   - Em diversass linguagens, isso é realizado através de modificadores de acesso
   - Alguns exemplos de modificadores de acesso são: public, protected, private
   - Definições
     - public: o acesso não é restrito
     - protectec: o acesso é limitado a classe que contém ou aos seus tipos derivados
     - private: o acesso é limitado a propria classe
   - No geral, é interessante deixar métodos que não vaõ ser expostos ao exterior com modificador de acesso private, facilitando a refatoração posterior e evitando quebras
 - Herança
   - Ténica que permite reutilizar, estender e modificar outras classes
   - A classe que é herdada é comumente chamada de classe base ou pai, e a classe que herda é chamada de derivada ou filha
   - Afetada por modificadores de acesso que estejam aplicados a classe base (por exemplo, private e protected)
   - Exemplo
     - Em um sistema que realiza notificação por e-mail e SMs, existe uma classe base Notificação
     - Porem, existem diferenças entre a formatação e campos necessarios para uma notificação em e-mail, como por exemplo um Assunto, e maiores personalizações do que uma por SMS
     - Nesse caso, seria possivel utilizar a classe base Notificação, que teria propriedades de Remetente, Destinatário e Conteúdo
     - E se estenderia através de classe NotificaticaoEmail e NotifcacaoSms, que teriam suas propriedades e maneiras próprias de formatar a mensagem  ( mais pra frente falaremos de polimofirmos)
 - Polimorfismo
   - Técnica de permite que objetos de classes derivadas se comportem de maneira diferente ao da classe base para o mesmo método
   - Ou seja, objetos de mesmo "pai" poderão ter particularidades no momento de executar um comportamento comum
   - Em C#, por exemplo, isso é feito através de palavras-chave virtual e override, sendo a primeira a que define os comportamentos que podem ser alterados na classe derivada
   - Já o override é responsável pela implementação na classe derivada
    
    
      
       


 
