# Especificação suplementar

## Introdução
<p align="justify">O Presente documento reúne os requisitos não identificados nos demais processos de elicitação e que não foram atendidos pelo contato direto com o aplicativo, mas com a percepção de usuários e membros da equipe.</p>

## Finalidade
<p align="justify">Esse documento visa descrever requisitos não funcionais do Shazam, ou seja, restrições qualitativas que impactam na usabilidade, no visual, no desempenho, na segurança e outros.Permite uma visão mais ampla sobre os requisitos da aplicação que vão além de funcionalidades, que descrevem necessidades relacionadas à qualidade, estrutura e condições subjetivas.</p>

## Escopo
<p align="justify">O escopo se resume à uma aplicação mobile que oferece captura de áudio e detecção de mídias tais como programas de TV, propagandas e músicas.</p>

## Definições, Acrônimos e Abreviações
<p align="justify">Shazam- aplicativo utilizado pela equipe, cujo foco é detectar mídias através de gravação de trecho da mídia desejada.</p>
<p align="justify">Elicitação - Processo de obtenção de requisitos através das técnicas de entrevistas, brainstorming, introspecções, dentre outras.</p>

## Visão Geral
<p align="justify">O Documento presente apresenta uma introdução ao escopo do projeto analisado, cujos requisitos suplementares estão listados posteriormente, contendo requisitos não funcionais (obtidos pelas impressões de usuários assíduos do aplicativo), requisitos de usabilidade, confiabilidade, desempenho, suportabilidade, sistema, licenciamento, restrições de design e interfaces.</p>

## Funcionalidade
<p align="justify">Esse tópico reúne os requisitos não funcionais, dado que os requisitos funcionais estão dispostos e definidos na documentação de elicitação, sendo representados pelos casos de uso.</p>

## Usabilidade
<p align="justify">Os usuários devem poder aprender a mexer no sistema de forma intuitiva através do uso. Dessa forma, o treinamento necessário para fazer uma utilização correta do sistema deverá ser rápido, com aprendizado máximo de 30 minutos - considerando que um usuário não gasta muito tempo de uma vez só no sistema. Já para um usuário que deseja ter conhecimento profundo do sistema (usuário avançado) pode levar um período de tempo maior através de aprendizagem orgânica, ou seja, utilizando a aplicação.</p>
<p align="justify">Uma observação pertinente é que para fazer bom uso do sistema o usuário deve ser capaz de utilizar seu dispositivo físico de acesso (celular smartphone) e também o sistema operacional instalado no dispositivo   (Android ou iOS).</p>

### Requisito de Usabilidade 
<p align="justify">A aplicação  deve utilizar padrões visuais de informação condizentes  com a plataforma em que se encontra.</p>

### Requisito de Usabilidade Dois
<p align="justify">A aplicação deve oferecer tutoriais para usuários de primeira viagem, no intuito de capacitá-los ao uso do aplicativo.</p>

### Requisito de Usabilidade Três
<p align="justify">A aplicação deve fornecer ao usuário um fluxo intuitivo, por meio dos ícones, para suas diversas funcionalidades.</p>

### Requisito de Usabilidade Quatro
<p align="justify">O sistema deve oferecer agilidade e facilidade no momento em que o usuário executa funcionalidades básicas e principais.</p>

## Confiabilidade
<p align="justify">O Sistema possui servidores estáveis, com uma baixa taxa de reclamação dos usuários quanto a falhas de funcionamento, tendo fluxo contínuo e rápida resposta com informações sobre a mídia para o usuário.</p>

### Requisito de Confiabilidade Um
<p align="justify">O Sistema deve armazenar e recuperar informações com precisão, fazendo uso de criptografia de dados para impedir o vazamento de informações.</p>

### Requisito de Confiabilidade Dois
<p align="justify">No caso de uma sessão de usuário expirar, qualquer tarefa que exija futuras informações dependentes terá o acesso bloqueado, para que o os dados do usuário em sua sessão não fique exposto a um acesso de terceiros.</p>

### Requisito de Confiabilidade Quatro
<p align="justify">O software deve procurar deixar o usuário ciente do que ocorre no sistema, assim como as falhas que possam ocorrer durante o uso. Esse feedback deve informar o motivo da falha e possíveis soluções que o próprio usuário possa executar.<p/> 
<p align="justify">Caso a correção não esteja ao alcance das ações do usuário ou não possa ser informado, o suporte deve ser imediatamente informado.</p>

## Desempenho
<p align="justify">Como requisito de desempenho, o tempo de resposta das requisições feitas pelo usuário deve ser o menor possível, não podendo passar de 1 minuto para uma melhor experiência do usuário dentro da aplicação.</p>

### Requisito de Desempenho Um
<p align="justify">A aplicação deve conter o balanceamento de carga ao servidor como suporte, devido ao grande número de acessos diários na aplicação, a fim de garantir o acesso de todos os usuários dentro do Shazam.</p>

### Requisitos de Desempenho Dois
<p align="justify">A aplicação deve ser capaz de responder rapidamente a uma ação de cada usuário do Shazam, de forma simultânea.</p>

## Suportabilidade
<p align="justify">O sistema deve estar disponível para mobile, tanto nos dispositivos Android como IOS.</p>

## Restrições de Design
<p align="justify">Esta seção reúne as decisões quanto ao design estabelecido e aplicado no Shazam, refletindo o padrão adotado para o uso em diferentes plataformas e a adaptação às alterações conforme o formato de exibição de informações, caracterizando a forma de utilização e o grau de contato entre o usuário e o aplicativo.</p>

### Restrição de Design Um
<p align="justify">A aplicação deverá ter o suporte a diversas línguas, definido através do idioma estabelecido no dispositivo do usuário.</p>

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line
<p align="justify">Esta seção reúne os requisitos que buscam tratar do suporte e dos sistemas de auxílio ao usuário para o uso correto da aplicação, como sistemas de suporte e páginas de apoio.</p>

### Requisito de Suporte ao Usuário Um
<p align="justify">A aplicação deve possuir um link de acesso a uma página da web com suporte e guia de funcionalidades da aplicação, para guiar o usuário em seu primeiro uso ou sanar dúvidas pontuais de forma direta.</p>

### Requisito de Suporte ao Usuário Dois
<p align="justify">A página de suporte deve conter guias de instrução para as principais funcionalidades do aplicativo, com exemplificações claras e textos diretos e informativos.</p>

### Requisito de Suporte ao Usuário Três
<p align="justify">A página de suporte deverá proporcionar a resposta a perguntas frequentes, com páginas de resolução de dúvidas contendo links e índices de satisfação do usuário.</p>

## Componentes Adquiridos
<p align="justify">O sistema deve levar em consideração as licenças do software e reservas legais ao ser desenvolvido.</p>

## Interfaces
<p align="justify">A Presente seção busca definir e categorizar os tipos de interface presentes na aplicação, contando com a necessidade do software conter um desenvolvimento correto e a presença de endereços, lógicas, protocolos e planejamento de execução bem integrados para um funcionamento correto.</p>

### Interfaces do Usuário
<p align="justify">A plataforma deverá disponibilizar uma interface de suporte gráfico com os componentes da aplicação, de modo que o usuário possa interagir com as funcionalidades da melhor forma possível.</p>

### Interfaces de Hardware
<p align="justify">A plataforma deve ter suporte para smartphones.</p>

### Interfaces de Software
<p align="justify">A plataforma deve usufruir de linguagens e frameworks que ajude na manutenção e viabilize a eficiência no desenvolvimento, através de algum paradigma definido.</p>

### Interfaces de Comunicação
<p align="justify">A plataforma deve possuir uma interface de comunicação afim a suportar as diversas requisições de dados do sistema de forma a manter a integridade de todos os dados. Além de comunicação por meio de micro serviço que possibilitará o registro de contas e armazenamento de mídias na biblioteca do aplicativo.</p>

## Requisitos de Licenciamento
<p align="justify">Esta seção reúne os requisitos que definem as especificações do licenciamento da aplicação, buscando abranger os aspectos referentes às permissões e restrições do usuário, definidas nos documentos de licenciamento.</p>

### Requisito de Licenciamento Um
<p align="justify">Aos usuários que seguirem todas os Termos e Diretrizes da Comunidade, será oferecida uma licença limitada, não exclusiva, intransferível e revogável para usar a aplicação de forma gratuita.</p>

## Versionamento do documento
|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 21/10/2019 | 1.0 | Criação do documento | Débora Vilela |

## Referências

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 11. 1º/2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.