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
 
