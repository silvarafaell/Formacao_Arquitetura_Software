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



 
