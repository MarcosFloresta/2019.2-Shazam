# Forward-from 

## Tabela de Requisitos Funcionais

|Requisito|Descrição|NFR|US|Épicos|Artefato de desenho|
|:--:|:----:|:-------:|:---:|:----:|:----:|
|RF01 |Detecção de mídias musicais por áudio|-|[Escanear música](../modelagem/diagramas#Escanear-musica)|[EP2,EP3](../modelagem/backlog#ep1)|[Tela inicial do Shazam](../imgs/RF01.shazam.android.jpg)|
|RF02 |Permite ouvir trecho da música detectada|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP3](../modelagem/backlog#ep1)|[Tela de acesso ao trecho da música](../imgs/RF02.shazam.android.jpg)|
|RF03 |Armazena músicas descobertas em uma biblioteca permitindo encontrá-las novamente em outro momento|-|[Escanear música](../modelagem/diagramas#Escanear-musica) , [Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP3](../modelagem/backlog#ep1)|[Biblioteca de músicas detectadas](../imgs/rf03.shazam.android.jpg)|
|RF04 |Compartilhamento de músicas descobertas em outras plataformas|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP12](../modelagem/backlog#Ep1)|[Tela de compartilhar mídia](../imgs/RF04.shazam.android.jpg)|
|RF05 |Detecção de alguns programas de TV|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica) , [Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP2](../modelagem/backlog#ep1)|-|
|RF06 |Detecção de Qr code especifícos|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica) , [Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP2](../modelagem/backlog#Ep1)|-|
|RF07 |Opção de abrir a música descoberta em aplicativos reprodutores de músicas|-|[Descobrir novas músicas](../modelagem/diagramas#Descobrir-novas-musicas)|[EP4](../modelagem/backlog#ep1)|[Tela de abrir as músicas em outros apps](../imgs/RF07.shazam.android.jpg)|
|RF08 |Recomendações de músicas e playlists|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP12](../modelagem/backlog#ep1)|[Tela de playlists recomendadas](../imgs/RF08.shazam.android.jpg)|
|RF09 |Recomendações de músicas mais localizadas com o Shazam na última semana|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP](../modelagem/backlog#ep1)|[Tela de top-trending](../imgs/RF09.shazam.android.jpg)|
|RF10 |Permitir a opção de ser um detector e reprodutor de música no mesmo aplicativo|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP](../modelagem/backlog#ep1)|-|
|RF11 |Permitir que a detecção da música indique playlists relacionadas a gêneros musicais já existentes em um aplicativo de reprodução de músicas|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP12](../modelagem/backlog#ep1)|-|
|RF12 |É possível conectar-se com o Spotify, dessa forma, músicas descobertas pelo Shazam formam uma playlist no Spotify|-|[Descobrir novas músicas](../modelagem/diagramas#Descobrir-novas-musicas)|[EP4,EP12](../modelagem/backlog#ep1)|[Tela de conectar com o Spotify](../imgs/RF12.shazam.android.jpg)|
|RF13 |O aplicativo não necessita do Login para detectar músicas. O login é opcional|[Segurança](../modelagem/NFR#NFR-de-Segurança)|[Escanear música](../modelagem/diagramas#Escanear-musica) , [Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP1](../modelagem/backlog#ep1)|-|
|RF14 |Modo auto Shazam. É uma ferramenta do smartphone que possibilita identificar músicas automaticamente sem a necessidade do aplicativo estar aberto|-|[Descobrir novas músicas](../modelagem/diagramas#Descobrir-novas-musicas)|[EP4, EP9](../modelagem/backlog#ep1)|[Tela de autorizar o Auto Shazam](../imgs/RF12.shazam.android.jpg)|
|RF15 |Locais com muitos ruídos atrapalham a detecção do aúdio musical|-|[Descobrir novas músicas](../modelagem/diagramas#Descobrir-novas-musicas)|[EP4](../modelagem/backlog#ep1)|-|
|RF16 |Caso o usuário esteja offline a busca fica salva no histórico, e quando houver conexão com internet ele efetua a pesquisa|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica)|[EP11](../modelagem/backlog#Ep1)|-|
|RF17 |Permitir acesso a biblioteca sem efetuar login|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|[Escanear música](../modelagem/diagramas#Escanear-musica), [Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP1](../modelagem/backlog#ep1)|-|
|RF18 |Permitir a opção de playlists compartilhadas no próprio aplicativo ao invés de ter que migrar para outro aplicativo para realizar essa ação|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP12](../modelagem/backlog#ep1)|-|
|RF19 |Permitir a opção de visualizar o vídeo clipe da música no próprio aplicativo sem a necessidade de migrar para um aplicativo reprodutor de vídeos|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP8](../modelagem/backlog#ep1)|-|
|RF20 |Permitir a integração com o Spotify, criação de um botão do Shazam no Spotify|-|[Descobrir novas músicas](../modelagem/diagramas#Descobrir-novas-musicas)|[EP4](../modelagem/backlog#ep1)|-|
|RF21 |Permitir a opção de backup de conteúdo descoberto no aplicativo caso o usuário troque de dispostivo móvel|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP1](../modelagem/backlog#ep1)|-|
|RF22 |O aplicativo disponibiliza a letra da música descoberta|-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP13](../modelagem/backlog#ep1)|[Tela que disponibiliza letra da música](../imgs/RF22.shazam.android.jpg)|
|RF23 | O usuário pode escutar o conteúdo que descobriu e receber mais informações sobre o mesmo |-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP2](../modelagem/backlog#ep1)|-|


## Tabela de Requisitos Não Funcionais

|Requisito|Descrição|NFR|US|Épicos|Artefato de desenho|
|:--:|:----:|:-------:|:---:|:----:|:----:|
|RNF01 |Disponibilidade de uso em tempo integral|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|-|[EP7](../modelagem/backlog#ep1)||
|RNF02 |Acesso para download em Android e IOS|[Portabilidade](../modelagem/NFR#NFR-de-Portabilidade)|-|-||
|RNF03 |Necessidade de internet apenas para finalizar buscas|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica)|[EP11](../modelagem/backlog#ep1)||
|RNF04 |Curto tempo de busca no banco de dados|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica)|-||
|RNF05 |Botão intuitivo e com frases instrutivas|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|-|[EP6](../modelagem/backlog#ep1)||
|RNF06 |O aplicativo possuir três telas|[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|-|[EP6](../modelagem/backlog#ep1)||
|RNF07 |ícones instrutivos na opção  de abrir a mídia musical em um aplicativo reprodutor de músicas|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|[EP6](../modelagem/backlog#ep1)|[Tela de abrir as músicas em outros apps](../imgs/RF07.shazam.android.jpg)|
|RNF08 |ícones instrutivos na opção  de compartilhar mídia musical|[Usabilidade](../modelagem/NFR#NFR-de-Usabilidade)|-|[EP6](../modelagem/backlog#ep1)|[Tela de compartilhar mídia com ícones intuitivos](../imgs/RF04.shazam.android.jpg)|
|RNF09 | Atualização constante do banco de dados |[Desempenho](../modelagem/NFR#NFR-de-Desempenho)|[Escanear música](../modelagem/diagramas#Escanear-musica)|[EP7](../modelagem/backlog#ep1)|| 
|RNF10 | Portabilidades (Dispositivos móveis, Web App) |[Portabilidade](../modelagem/NFR#NFR-de-Portabilidade)|-|[EP7](../modelagem/backlog#ep1)|[Tela do Shazam Web](../imgs/RNF10.shazam.web.png)|
|RNF11 | Ter uma versão mais leve para abranger mais usuários |-|-|-||
|RNF12 | Fazer conexão com outros streamings de música |-|[Ações a partir da biblioteca](../modelagem/diagramas#Acoes-a-partir-da-biblioteca)|||



# Versionamento

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
|13/11/2019|1.0|Criação do documento e adição de conteúdo|Débora Vilela|
|13/11/2019|1.1|Adicionando Artefato de desenho |Nathalia Lorena|
|13/11/2019|1.2|Adicionando NFRs ao documento|Débora Vilela|
|13/11/2019|1.3|Adicionando Artefato de desenho |Nathalia Lorena|
|13/11/2019|1.4|Adicionando USs ao documento|Débora Vilela|

# Referências

### Exemplo de modelo de Forward From

[Repositório Pinterest](http://www.joberth-rogers.ml/2018.2-Requisitos-Pinterest/forward_from/) Acesso em 13 de novembro de 2019.

[Repositório Twitch](https://github.com/gabrielziegler3/Requisitos-2018-1/wiki/Matriz-Rastreabilidade) Acesso em 13 de novembro de 2019.


### Material disponibilizado pelo professor

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 24. 2º/2019. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
