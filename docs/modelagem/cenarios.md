# Cenários

## Introdução


<p align="justify">Os cenários consistem de uma coleção de narrativas de situações no domínio que favorecem o levantamento de informações em um contexto proposto que permitem a identificação de possíveis tarefas e funcionalidades que se pode realizar em um software, como também identifica problemas e a antecipação das soluções. A técnica de elaborar cenários é uma maneira excelente de representar, para clientes e usuários, os problemas existentes em um software e as possibilidades que podem surgir. Os cenários têm como foco as atividades desempenhadas pelos usuários nas organizações em diferentes contextos possibilitando uma perspectiva mais ampla dos problemas atuais onde o sistema será inserido, explicando porque ele é necessário.</p>

## [C1](#c1)

**[Identificar](lexicos.md#l09) uma música**

|Objetivo  |
 -----------   |
|[Descobrir](lexicos.md#l09) uma música       |
|**Contexto** |
|Local: Página inicial do Shazam ([login](lexicos.md#l05) não obrigatório)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: [Usuário](lexicos.md#l10) descobre música<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que quer [descobrir](lexicos.md#l09) uma música|
|**Recursos**|
|Internet, aplicativo|
|**Episódios**|
|[Usuário](lexicos.md#l10) que quer [descobrir](lexicos.md#l09) uma música abre o aplicativo<br>[Usuário](lexicos.md#l10) clica no botão circular da tela de início<br>A música e artista são detectados pelo Shazam com sucesso<br>Se a música não foi detectada, [Usuário](lexicos.md#l10) clica no botão circular e tenta novamente|
|**Restrição**|
|Aplicativo estar instalado<br>Música(s) tocando no momento|
|**Exceção**|
Internet cair<br>Conteúdo musical muito distante para ser detectado<br>Aplicativo estar indisponível<br>Muitos ruídos no ambiente|

## [C2](#c2)

**Realizar cadastro**

|Objetivo  |
 -----------   |
|Permitir que [usuários](lexicos.md#l10) se cadastrem    |
|**Contexto** |
|Local: Tela da esquerda do Shazam (no ícone de configurações)<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: [Usuário](lexicos.md#l10) realiza inscrição<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja ter cadastro na plataforma|
|**Recursos**|
|Internet, aplicativo, conta de e-mail|
|**Episódios**|
|[Usuário](lexicos.md#l10) quer [descobrir](lexicos.md#l09) uma música abre o aplicativo<br>[Usuário](lexicos.md#l10) clica no botão circular da tela de início<br>A música e artista são detectados pelo Shazam com sucesso<br>Se a música não foi detectada, usuário clica no botão circular e tenta novamente<br>[Usuário](lexicos.md#l10) quer salvar seus [Shazams](lexicos.md#l09), então clica na opção de configurações e em seguida realizar inscrição|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter conta no Facebook<br>O [Usuário](lexicos.md#l10) possuir e-mail|
|**Exceção**|
|Internet cair<br>E-mail inválido<br>Aplicativo estar indisponível<br>Senha inválida<br>E-mail ou conta do Facebook inexistente<br>E-mail ou Facebook fora do ar|

## [C3](#c3)

**Visualizar músicas [descobertas](lexicos.md#l09)**

|Objetivo  |
 -----------   |
|Visualizar as músicas que o [Usuário](lexicos.md#l10) descobriu   |
|**Contexto** |
|Local: Tela da esquerda do Shazam (em [biblioteca](lexicos.md#l04))<br>Pré-Condição: Ter instalado o app<br>Pós-Condição: [Usuário](lexicos.md#l10) visualiza músicas que descobriu<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja ter acesso às músicas que descobriu|
|**Recursos**|
|Internet, aplicativo, músicas [identificadas](lexicos.md#l01)|
|**Episódios**|
|[Usuário](lexicos.md#l10) quer visualizar uma música que descobriu<br>[Usuário](lexicos.md#l10) clica no ícone escrito "[biblioteca](lexicos.md#l04)" ou desliza o dedo da esquerda para a direita partindo da tela de início<br>O [Usuário](lexicos.md#l10) encontra suas músicas e artistas na [biblioteca](lexicos.md#l04)|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>O [Usuário](lexicos.md#l10) ter clicado no botão de [identificar](lexicos.md#l09) músicas na tela inicial do Shazam|
|**Exceção**|
|Internet cair<br>Músicas não terem sido reconhecidas<br>Aplicativo estar indisponível<br>|

## [C4](#c4)

**Salvar músicas [descobertas](lexicos.md#l09)**

|Objetivo  |
 -----------   |
|Salvar as músicas que foram [identificadas](lexicos.md#l01)   |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone de configurações)<br>Pré-Condição: Ter instalado o app e ter músicas [descobertas](lexicos.md#l09) na [biblioteca](lexicos.md#l04)<br>Pós-Condição: [Usuário](lexicos.md#l10) salva músicas que descobriu<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja salvar às músicas [identificadas](lexicos.md#l01) pelo app|
|**Recursos**|
|Internet, aplicativo, músicas  [identificadas](lexicos.md#l01 na [biblioteca](lexicos.md#l04) do app|
|**Episódios**|
|[Usuário](lexicos.md#l10) quer salvar as músicas que descobriu sem ter o risco de sair do aplicativo e elas sumirem da [biblioteca](lexicos.md#l04)<br>Usuário clica no ícone escrito "[biblioteca](lexicos.md#l04)" ou desliza o dedo da esquerda para a direita partindo da tela de início e depois no ícone de configurações<br>O [Usuário](lexicos.md#l10) encontra a opção de inscrição que garante que suas músicas sejam salvas|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) ter músicas na [biblioteca](lexicos.md#l04) que deseja salvar<br>O [Usuário](lexicos.md#l10) ter conta no Facebook<br>O [Usuário](lexicos.md#l10) possuir e-mail|
|**Exceção**|
|Internet cair<br>Músicas não terem sido [reconhcidas](lexicos.md#l01)<br>E-mail inválido<br>Aplicativo estar indisponível<br>Senha inválida<br>E-mail ou conta do Facebook inexistente<br>E-mail ou Facebook fora do ar|

## [C5](#c5)

**Procurar músicas ou artistas no app**

|Objetivo  |
 -----------   |
|Efetuar busca por músicas ou artistas já disponíveis no app   |
|**Contexto** |
|Local: Tela da direita do Shazam (ícone de [descobrir](lexicos.md#l09))<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: [Usuário](lexicos.md#l10) encontra músicas ou artistas de seu interesse existentes no app<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja explorar músicas ou artistas de seu interesse que estão disponíveis no app|
|**Recursos**|
|Internet, aplicativo|
|**Episódios**|
|[Usuário](lexicos.md#l10) quer explorar as músicas ou artistas existentes no aplicativo<br>[Usuário](lexicos.md#l10) clica no ícone escrito "[Descobrir](lexicos.md#l09)" ou desliza o dedo da direita para a esquerda partindo da tela de início e depois no ícone de "lupa" em seguida, digita algo de seu interesse<br>O [Usuário](lexicos.md#l10) encontra as músicas ou artistas que deseja e visualiza as músicas mais populares "[top-trending](lexicos.md#l106)"|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo|
|**Exceção**|
|Internet cair<br>[Usuário](lexicos.md#l10) pesquisar por um artista ou música inexistente|

## [C6](#c6)

**Fazer [login](lexicos.md#l05)**

|Objetivo  |
 -----------   |
|Fazer [login](lexicos.md#l05) no app e salvar suas músicas |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) e botão de "fazer [login](lexicos.md#l05)"<br>Pré-Condição: Ter o app instalado<br>Pós-Condição: [Usuário](lexicos.md#l10) faz [login](lexicos.md#l05)<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja ter sua conta logada e já fez inscrição|
|**Recursos**|
|Internet, aplicativo, e-mail válido|
|**Episódios**|
|[Usuário](lexicos.md#l10) prefere ter uma conta com [login](lexicos.md#l05)<br>[Usuário](lexicos.md#l10) clica no ícone escrito "[biblioteca](lexicos.md#l04)" ou desliza o dedo da esquerda para a direita partindo da tela de início e depois no clica no botão referente a "fazer [login](lexicos.md#l05)" em seguida, clica na opção de realizá-lo com e-mail ou facebook<br>O [Usuário](lexicos.md#l10) recebe uma validação por e-mail<br>Após a confirmação o [Usuário](lexicos.md#l10) estará logado|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) possuir cadastro|
|**Exceção**|
|Internet cair<br>[Usuário](lexicos.md#l10) esquecer e-mail<br>[Usuário](lexicos.md#l10) não ter confirmado a conta por e-mail|

## [C7](#c7)

**Sair do aplicativo Shazam**

|Objetivo  |
 -----------   |
|Fazer logout no app |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, ícone de configurações<br>Pré-Condição: O [Usuário](lexicos.md#l10) deve estar logado<br>Pós-Condição: [Usuário](lexicos.md#l10) clica na opção de "sair" e encerra a sessão a conta<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja sair da sua conta logada|
|**Recursos**|
|Internet, aplicativo, conta do [Usuário](lexicos.md#l10)|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)" em seguida, na ferramenta de "configurações"<br>[Usuário](lexicos.md#l10) clica na opção de sair<br>[Usuário](lexicos.md#l10) visualiza a página de início do app|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) estar logado|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível|

## [C8](#c8)

**Excluir conta**

|Objetivo  |
 -----------   |
|Excluir conta no app |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, ícone de configurações e na opção "sobre"<br>Pré-Condição: O [Usuário](lexicos.md#l10) deve ter conta e estar logado<br>Pós-Condição: [Usuário](lexicos.md#l10) exclui sua conta<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que não quer mais ter conta no app|
|**Recursos**|
|Internet, aplicativo, conta do [Usuário](lexicos.md#l10)|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)", em seguida, na ferramenta de "configurações" e na opção "sobre"<br>[Usuário](lexicos.md#l10) visualiza a opção de excluir conta<br>[Usuário](lexicos.md#l10) clica em "excluir conta" e o app direciona para uma página no browser que solicita ao [Usuário](lexicos.md#l10) iniciar uma sessão com e-mail ou facebook de acordo com a opção que o [Usuário](lexicos.md#l10) se cadastrou |
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) ter conta e estar logado|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>E-mail ou facebook inválidos|

## [C9](#c9)

**[Compartilhar](lexicos.md#l03) [mídia](lexicos.md#l02) identificada**

|Objetivo  |
 -----------   |
|[Compartilhar](lexicos.md#l03) [mídia](lexicos.md#l02) identificada pelo Shazam |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, "[Shazams](lexicos.md#l09) recentes" e menu contido na música que o [Usuário](lexicos.md#l10) escolheu<br>Pré-Condição: O [Usuário](lexicos.md#l10) deve ter  identificado uma ou mais músicas<br>Pós-Condição: [Usuário](lexicos.md#l10) compartilha [mídia](lexicos.md#l02)<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja [Compartilhar](lexicos.md#l03) [mídia](lexicos.md#l02) com outros [Usuários](lexicos.md#l10)|
|**Recursos**|
|Internet, aplicativo, Facebook, Gmail, Messenger, Instagram, Telegram, Whatsapp, Hangouts, etc|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)", em seguida, no título de "[Shazams](lexicos.md#l09) recentes" encontra suas músicas<br>[Usuário](lexicos.md#l10) escolhe a opção que deseja [Compartilhar](lexicos.md#l03)<br>[Usuário](lexicos.md#l10) clica na música, em seguida, no menu à direita no canto inferior da tela<br>[Usuário](lexicos.md#l10) clica na opção "[Compartilhar](lexicos.md#l03)" e escolhe uma opção de compartilhamento em outras plataformas disponíveis|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) possuir conta em alguma das plataformas disponíveis na opção de "[Compartilhar](lexicos.md#l03)" |
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>E-mail ou conta em alguma das plataformas de compartilhamento estar indisponível<br>O [Usuário](lexicos.md#l10) não possuir e-mail ou nenhuma conta nas plataformas disponíveis|

## [C10](#c10)

**Abrir [mídia](lexicos.md#l02) do Shazam em plataformas de reprodução de músicas**

|Objetivo  |
 -----------   |
|Abrir músicas [identificadas](lexicos.md#l01) pelo Shazam em outros aplicativos que reproduzam [mídia](lexicos.md#l02) musical |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, "[Shazams](lexicos.md#l09) recentes" e menu contido na música que o [Usuário](lexicos.md#l10) escolheu<br>Pré-Condição: O [Usuário](lexicos.md#l10) deve ter  identificado uma ou mais músicas<br>Pós-Condição: [Usuário](lexicos.md#l10) abre a música em outro app<br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja ouvir [mídia](lexicos.md#l02) que identificou através de outros apps de reprodução de música|
|**Recursos**|
|Internet, aplicativo, Apple Music, Google Play Music, Spotify|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)", em seguida, no título de "[Shazams](lexicos.md#l09) recentes" encontra suas músicas<br>[Usuário](lexicos.md#l10) escolhe a opção que deseja [Compartilhar](lexicos.md#l03)<br>[Usuário](lexicos.md#l10) clica na música, em seguida, no menu à direita no canto inferior da tela<br>[Usuário](lexicos.md#l10) clica na opção "Abrir no Apple Music" ou "Abrir no Google Play music" ou "Abrir no Spotify" e escolhe a opção de seu interesse para reproduzir a música|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) possuir conta em alguma das plataformas disponíveis na opção de "Abrir a música"|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>A conta em alguma das plataformas d[Usuário](lexicos.md#l10)e compartilhamento estar indisponível<br>O [Usuário](lexicos.md#l10) não possuir conta em nenhuma das plataformas disponíveis|

## [C11](#c110)

**Remover alguma [mídia](lexicos.md#l02) identificada da [biblioteca](lexicos.md#l04)**

|Objetivo  |
 -----------   |
|Remover alguma música descoberta da [biblioteca](lexicos.md#l04) do Shazam |
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, "[Shazams](lexicos.md#l09) recentes" e menu contido na música que o [Usuário](lexicos.md#l10) escolheu<br>Pré-Condição: O [Usuário](lexicos.md#l10) deve ter identificado uma ou mais músicas<br>Pós-Condição: [Usuário](lexicos.md#l10) remove a música de sua [biblioteca](lexicos.md#l04) <br> |
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja remover uma música de sua [biblioteca](lexicos.md#l04)|
|**Recursos**|
|Internet, aplicativo, músicas da [biblioteca](lexicos.md#l04) do app|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)", em seguida, no título de "[Shazams](lexicos.md#l09) recentes" e encontra suas músicas<br>[Usuário](lexicos.md#l10) clica em alguma música e no menu à direita dessa música escolhida encontra a opção de remover música da sua [biblioteca](lexicos.md#l04)|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) possuir uma ou mais músicas em sua [biblioteca](lexicos.md#l04)|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>[Usuário](lexicos.md#l10) não ter nenhuma música em sua [biblioteca](lexicos.md#l04)|

## [C12](#c12)

**Visualizar letra de alguma música [identificada](lexicos.md#l01)**

|Objetivo  |
 -----------   |
|Visualizar as letras de músicas [identificadas](lexicos.md#l01) pelo Shazam|
|**Contexto** |
|Local: Tela da esquerda do Shazam (ícone da [biblioteca](lexicos.md#l04)) em seguida, "[Shazams](lexicos.md#l09) recentes" e a opção "letra" na música que o [Usuário](lexicos.md#l10) escolheu<br>Pré-Condição: O [Usuário](lexicos.md#l10) ter identificado uma ou mais músicas<br>Pós-Condição: [Usuário](lexicos.md#l10) acessa a letra de alguma das músicas de sua [biblioteca](lexicos.md#l04)|
|**Atores**|
|[Usuário](lexicos.md#l10) que deseja ter acesso a letra de alguma música de sua [biblioteca](lexicos.md#l04)|
|**Recursos**|
|Internet, aplicativo, músicas da [biblioteca](lexicos.md#l04) do app|
|**Episódios**|
|[Usuário](lexicos.md#l10) clica em "[biblioteca](lexicos.md#l04)", em seguida, no título de "[Shazams](lexicos.md#l09) recentes" e encontra suas músicas<br>[Usuário](lexicos.md#l10) clica em alguma música e na opção "letra"|
|**Restrição**|
|O [Usuário](lexicos.md#l10) ter o aplicativo<br>[Usuário](lexicos.md#l10) possuir uma ou mais músicas em sua [biblioteca](lexicos.md#l04)|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>Não existir letra da música que o [Usuário](lexicos.md#l10) optou<br>[Usuário](lexicos.md#l10) não ter nenhuma música em sua [biblioteca](lexicos.md#l04)|

## [C13](#c13)

**Utilizar o [Shazam Code](lexicos.md#l11)**

|Objetivo|
| ------- |
|Visualizar o ambiente proporcionado pelo [Shazam Code](lexicos.md#11)|
|**Contexto**|
|Local: Parte inferior da tela Principal do Shazam (ícone da câmera) em seguida deve-se ajudar o [Shazam Code](lexicos.md#11) na área indicada pelo app.<br>Pré-Condição: O [Usuário](lexicos.md#10) deve ter acesso a um [Shazam Code](lexicos.md#11)<br>Pós-condição:O [Usuário](lexicos.md#10) tem acesso à interface proporcionada pelo [Shazam Code](lexicos.md#11)|
|**Recursos**|
|Internet, aplicativo, [Shazam Code](lexico.md#11)|
|**Episódios**|
|[Usuário](lexicos.md#10) clica no ícone da câmera e aponta para o [Shazam Code](lexico.md#11)|
|**Restrição**|
|O [Usuário](lexicos.md#10) ter o aplicativo<br>O [Usuário](lexicos.md#10) deve ter acesso à um [Shazam Code](lexicos.md#11)|
|**Exceção**|
|Internet cair<br>Aplicativo estar indisponível<br>O [Shazam Code](lexico.md#11) ser inválido<br>O [Usuário](lexico.md#10) não ter acesso ao [Shazam Code](lexico.md#11)|

## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 27/09/2019 | 1.0 | Criação do documento | Nathalia Lorena |
| 27/09/2019 | 2.0 | Adicionando cenários | Nathalia Lorena |
| 28/09/2019 | 2.1 | Adicionando cenários | Nathalia Lorena |
| 30/09/2019 | 2.2 | Correção de indentação | Débora|
| 13/11/2019 | 2.3 | Adicionando rastreabilidade | Nathalia Lorena |
| 27/11/2019 | 2.4 | Adição do cenário C13 | Gabriel Tiveron |

## Referências

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
