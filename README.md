<img align="right" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/engenheiroDeSoftware.svg" width="450"/>

### Hello, I'm Guilherme Bafica 👋

Vamos falar um pouco sobre Engenharia de Software, `processo de desenvolvimento de software e sua aplicação no Gerenciamento de Projeto`. 

Destaco que um software tem como importante objetivo agregar valor a uma organização por meio da automação de processos e deve-se sempre ser baseado em:

> FUNCIONALIDADE => Satisfação dos requisitos funcionais.

> CONFIABILIDADE => Tempo de disponibilidade do software.

> USABILIDADE => Facilidade de uso.

> EFICIÊNCIA => Otimização dos recursos do sistema.

> FACILIDADE DE MANUTENÇÃO => Realização de correção e atualização no software.

> PORTABILIDADE => Adequação a diferentes ambientes.

<img align="left" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/idea.svg" width="300"/>

O processo de desenvolvimento é dividido em 6 etapas:
- Levantamento de requisitos; 
- Análise;
- Projeto;
- Implementação;
- Testes;
- Implantação.

## 📝 Levantamento de requisitos => 
<img align="right" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/levantamento.svg" width="400"/>

Os requisitos de um sistema são descrições dos serviços fornecidos pelo sistema e as suas restrições operacionais. Esses requisitos refletem as necessidades dos clientes de um sistema que ajuda a resolver algum problema. Atividades de descobrir, analisar, documentar e verificar os serviços fornecidos pelo sistema e suas restrições operacionais.
  - Concepção -> Entendimento inicial do problema, identificação das partes interessadas que serão atendidas pelo software, a natureza da solução desejada e a eficácia da comunicação e colaboração preliminares entre clientes e usuários com a equipe de projeto;

  - Levantamento ->  Definir o escopo do projeto, ou “tamanho do problema”, além de possibilitar que usuários e desenvolvedores tenham a mesma visão do problema a ser resolvido. Esclarecendo aos clientes o que será entregue como produto do trabalho da equipe de desenvolvimento:
    - Os requisitos funcionais estão relacionados aos serviços fornecidos pelo sistema;
    - Os requisitos não funcionais incluem as restrições operacionais impostas ao software, confiabilidade, manutenibilidade, usabilidade etc;
    - Os requisitos de domínio também são conhecidos como “regras de negócio”, que normalmente apresentam-se como restrições ao requisito funcional.

  - Elaboração -> Realiza um estudo detalhado dos requisitos levantados e, a partir desse estudo, são construídos modelos para representar o sistema a ser construído;

  - Negociação ->  Avaliação de custos, riscos e conflitos, a fim de eliminar, combinar e/ou modificar os referidos requisitos e, logicamente, priorizá-los;

  - Especificação -> Gerar um documento de especificação incluindo todos os requisitos e modelos gerados nas etapas anteriores;

  - Validação -> Evidenciar que os modelos refletem as necessidades dos usuários com relação ao sistema a ser desenvolvido. Um defeito não considerado gera a construção de um sistema que não corresponderá às expectativas do usuário.

  - Gestão -> Finalizando o processo da engenharia de requisitos, a etapa de gestão permite controlar as mudanças dos requisitos à medida que o projeto evolui.

## 🔎 Análise => 
<img align="left" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/analise.svg" width="400"/>

Análise de ambas as partes do projeto para continuação.

## 👷 Projeto => 
<img align="right" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/projeto.svg" width="400"/>

Modelos, ou seja, diagramas, designs e especificações textuais que permitem a implementação.
        
> Exemplo: Demostrar estrutura desenhada e detalhada do banco de dados, com atributos, métodos e funções relacionadas as entidades envolvidas.

Realizando um paralelo com a Engenharia Civil, temos plantas baixas, projeto estrutural, hidráulico-sanitário, elétrico e etc... Agora, podemos ir para o terreno construir a casa.

## 💻 Implementação => 
<img align="left" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/implementacao.svg" width="400"/>

Realizar a tradução dos modelos de projeto em código executável por meio do uso de uma ou mais linguagens de programação, baseando-se na Funcionalidade, Confiabilidade, Usabilidade, Eficiência, Facilidade de Manutenção e Portabilidade.

## 🧪 Testes => 
<img align="right" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/testes.svg" width="400"/>

A qualidade do produto software pode ser garantida através de sistemáticas aplicações de testes nos vários estágios do desenvolvimento da aplicação. Esses testes permitem a validação da estrutura interna do software e sua aderência aos respectivos requisitos.        
Softwares mal testados podem gerar prejuízos às empresas. Um defeito de projeto poderá encadear requisições de compras inadequadas, gerar resultados financeiros incorretos, entre outros. 
  - Teste de Unidade => Primeira etapa da estratégia, tendo por objetivo testar componentes individuais de uma aplicação. Executar o software a fim de exercitar adequadamente toda a estrutura interna de um componente, como os desvios condicionais, os laços de processamento etc.

  - Teste de Integração => Objetiva a manutenção de compatibilidade das novas unidades construídas, ou modificadas, com os componentes previamente existentes.

  - Teste de Validação => Realiza a validação da solução como um todo. Os testes de validação contam com uma infraestrutura mais complexa de hardware, visando estar o mais próximo do ambiente real de produção:
    - (Aceite Teste Alpha) - Os usuários finais são convidados a operar o software dentro de um ambiente controlado, sendo realizado na instalação do desenvolvedor.
    - (Aceite Teste Beta) - Os usuários finais são convidados a operar o produto utilizando suas próprias instalações físicas, ou seja, o software é testado em um ambiente não controlado pelo desenvolvedor.

  - TESTE DE SISTEMA => Etapa final, focada e tratativa de exceções:
    - (Teste de recuperação) - Avaliar o comportamento do software após a ocorrência de um erro ou de determinadas condições anormais.
    - (Teste de segurança) - Detectar as falhas de segurança que podem comprometer o sigilo e a fidelidade das informações, bem como provocar perdas de dados ou interrupções de processamento. "Verificar se senha está sendo transportada desnecessariamente".
    - (Teste por esforço) - Simular condições atípicas de utilização do software, provocando aumentos e reduções sucessivas de transações que superem os volumes máximos previstos para o software, gerando contínuas situações de pico e avaliando como o software e toda a infraestrutura estão se comportando. Como exemplo, simular 10.000 saques simultâneos.
    - (Teste de desempenho) - Determinar se o desempenho, nas situações previstas de pico máximo de acesso e concorrência, está consistente com os requisitos definidos.
    - (Teste de disponibilização) - Também chamado de teste de configuração, tem por objetivo executar o software sobre diversas configurações de softwares e hardwares.

## 📲 Implantação => 
<img align="left" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/implantacao.svg" width="400"/>

O produto software testado em condições de migrar para o ambiente denominado “produção”, ou seja, mundo real, onde os usuários irão utilizá-lo nas suas rotinas diárias, seja na realização de um controle administrativo, seja no contexto de um processo de tomada de decisão. A implantação é a etapa do processo de desenvolvimento de software relacionada à transferência do sistema da comunidade de desenvolvimento para a comunidade de usuários, ou seja, o sistema entra em produção no ambiente real.
        
O objetivo da implantação é produzir com sucesso a entrega do software para seus usuários finais, podendo cobrir vasta gama de atividades, como descritas a seguir: 

  - A produção de releases externos do software => Inclui o lançamento de uma nova versão do software, ou resultado de uma manutenção no mesmo, sendo exigidas decisões, por parte de desenvolvedores e usuários, sobre como realizar a distribuição do produto.
  - A embalagem do software => Quando o software será comercializado por meio de determinada mídia, como, por exemplo, DVD.
  - Distribuição do software => É o processo de entrega de software para o usuário final, podendo ocorrer de forma manual, sem auxílio de ferramentas, ou automática, com auxílio de ferramentas.
  - Instalação do software => É um processo que inclui a instalação de todos os arquivos necessários à execução do software projetado.
  - Prestação de ajuda e assistência aos usuários => Quando a complexidade do software exige um serviço de atendimento aos clientes que procuram esclarecimentos sobre dúvidas relacionadas às funcionalidades ou sobre problemas técnicos relacionados ao software, serviço de help desk.

## 🔨 "EXTRA "MANUTENÇÃO => 
<img align="right" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/manuntencao2.svg" width="400"/>

A etapa mais longa do ciclo de vida do software, a manutenção inclui a correção de defeitos não identificados nas etapas anteriores do processo de desenvolvimento de software, no aprimoramento da implementação dos subsistemas e na disponibilização de novas funcionalidades a partir da identificação de novos requisitos. Estas devem ser planejadas, programadas e executadas.

### Solicitação de alteração => Geração de relatório de avaliação (Levantamento de requisitos + Análise) => Aprovação === sim => Gera a ECO (Projeto) e Realiza a alteração => Realiza garantia da qualidade (testes) => Distribui a nova revisão.

> REENGENHARIA DE SOFTWARE => Reconstruir o produto com mais funcionalidades, melhor desempenho, confiabilidade e manutenibilidade, focado no aumento da eficiência e competitividade de uma empresa.

<img align="center" src="https://github.com/guibafica/Engenharia-de-Software/blob/main/images/manutencao3.svg" width="400"/>

