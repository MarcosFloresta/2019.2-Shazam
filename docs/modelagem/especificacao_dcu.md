# Especificação dos diagramas de casos de uso

## Introdução
As especificações de casos de uso tem como objetivo de proporcionar um maior detalhamento sobre os diagramas de casos de uso e de exportar para uma linguagem natural, no nosso caso são 3 especificações, uma para cada diagrama em específico, sem contar com o diagrama geral, tendo em vista que o detalhamento do mesmo está dentro dos outros diagramas.

### **Escanear música**

|Objetivo  |
 -----------   |
|Descobrir uma música       |
|**Atores**|
|Usuário que quer descobrir uma música|
|**Fluxo principal**|
|Usuário que quer descobrir uma música abre o aplicativo<br>Usuário clica no botão circular da tela de início<br>A música e artista são detectados pelo Shazam com sucesso<br>Se a música não foi detectada, usuário clica no botão circular e tenta novamente|
|**Fluxos alternativos**|
|O usuário está cadastrado<br>Música adicionada à biblioteca do usuário<br>|
|**Fluxos de exceção**|
|Internet cair<br>Conteúdo musical muito distante para ser detectado<br>Aplicativo estar indisponível<br>Muitos ruídos no ambiente|
|**Rastreabilidade**|
|[Diagrama de casos de uso](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/diagramas/#escanear)|

### **Histórico de músicas**

|Objetivo  |
 -----------   |
|Histórico de músicas       |
|**Atores**|
|Usuário que deseja ver suas músicas escaneadas	|
|**Fluxo principal**|
|Usuário que deseja rever suas músicas escaneadas<br>Usuário desliza a tela no sentido esquerda-direita<br>O histórico das músicas é mostrado|
|**Fluxos alternativos**|
|O usuário deseja ver as playlists baseadas nas suas músicas<br>O usuário deseja ver as músicas e os álbuns dos artistas do seu histórico<br>|
|**Fluxos de exceção**|
|Internet cair<br>Usuário não cadastrado<br>Aplicativo estar indisponível|
|**Rastreabilidade**|
|[Diagrama de casos de uso](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/diagramas/#historico-de-musicas)|

### **Descobrir novas músicas**

|Objetivo  |
 -----------   |
|descobrir novas músicas       |
|**Atores**|
|Usuário que deseja ver músicas novas	|
|**Fluxo principal**|
|Usuário que deseja conhecer novas músicas<br>Usuário desliza a tela no sentido direita-esquerda<br>A aba de descobrir abre e o usuário tem acesso as músicas mais tocadas|
|**Fluxos alternativos**|
|O usuário deseja ver as melhores músicas de um país|
|**Fluxos de exceção**|
|Internet cair<br>Aplicativo estar indisponível|
|**Rastreabilidade**|
|[Diagrama de casos de uso](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/diagramas/#descobrir-musicas-novas)|

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 01/10/2019 | 1.0 | Criação do documento | Victor Levi |

