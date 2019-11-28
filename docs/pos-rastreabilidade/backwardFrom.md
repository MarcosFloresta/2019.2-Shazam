# Backward-From

## Objetivo

O objetivo deste artefato é fazer a pós-rastreabilidade dos requisitos, verificando e documentando a fonte original de cada requisito levantado para o sistema. Para isso será usado uma Matriz de Rastreabilidade

| Requisito | Descrição | NFR |Product Backlog | Esp. Casos de Uso | Cenário | Léxico | MoSCoW | First Things First | Instrospecção | Análise de Protocolo/Observação | Questionário | Rich Picture | Brainstorming | Elo |
| :-------- | :-------: | :-: | :-------------: | :---------------: | :-----: | :----: | :----: | :----------------: | :-----------: | :---------------------: | :----------: | :----------: | :-----------: | :-: |
| RNF01 | Cadastro de Usuário |  [Segurança](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-seguranca) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Histórico de Músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#historico-de-musicas) | [C2](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF01](#EF01) |
| RNF02 | Conectar com aplicativos de _streaming_ de terceiros | - | [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [RF20](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US05](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) |  [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/observacao) | - | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming#Requisitos-Funcionais) | [EF02](#EF02) |
| RNF03 | Ter acesso a uma lista de amigos | - | [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF03](#EF03) |
| RNF04 | Utilizar a aplicação de forma intuitiva.	| [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-usabilidade) | [RF08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF04](#EF04) |
| RNF05 | Não necessitar de um conhecimento grande sobre o mundo da música. | [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-usabilidade) | [RF09](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF09](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | - | - | - | - | - | [EF05](#EF05) |
| RNF06 | Não gastar todo meu plano de internet.	| [Desempenho](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-desempenho) | [RF10](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - |  -| [EF06](#EF06) |
| RNF07 | Conhecer novas músicas e pessoas. | - | [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Descobir novas músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu) | - | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | - | [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais) | [EF07](#EF07) |
| RNF08 | Dissipar meu conhecimento musical.	| - | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | [V1](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais) | [EF08](#EF08) |
| RNF09 | Não precisar entrar no app para escanear uma música. | - | [RF13](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF13](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/requisitos-funcionais) | [EF09](#EF09) |
| RNF10 | Saber a letra de uma música que está tocando em um vídeo. | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF10](#EF10) |
| RNF11 | Poder identificar qualquer música ao redor sem entrar no app com a opção auto Shazam ativada. | - | [RF15](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF15](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/requisitos-funcionais) | [EF11](#EF11) |
| RNF12 | Poder escolher um tema claro ou escuro para o app.	| - | [RF16](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF16](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF12](#EF12) |
| RNF13 | Reconhecer mídia através da voz do usuário	| - | [RF17](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF17](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF13](#EF13) |
| RF14 | Cadastro de Usuário |  [Segurança](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-seguranca) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Histórico de Músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#historico-de-musicas) | [C2](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF14](#EF14) |
| RF15 | Conectar com aplicativos de _streaming_ de terceiros | - | [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Compartilhamento de músicas](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) |  [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/observacao) | - | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming#Requisitos-Funcionais) | [EF15](#EF15) |
| RF16 | Ter acesso a uma lista de amigos | - | [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF16](#EF16) |
| RF17 | Detecção de mídias ao meu redor | - | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Escanear Música](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#escanear-musica) | [C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Buscar mídias](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo) | [Q01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) | [EF17](#EF17) |
| RF18 | Escanear uma música que estou ouvindo no meu dispositivo | - | [RF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Escanear Música](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#escanear-musica) | [C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Buscar mídias](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo) | [Q01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) | [EF18](#EF18) |
| RNF19 | Acessar uma música já escaneada | [Confiabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-confiabilidade) | [RNF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Histórico de Músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#historico-de-musicas) | [C3](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RNF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Armazenar músicas](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US02](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo) | [Q05](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) | -| [RF03](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) | [EF19](#EF19) |
| RNF20 | Acessar playlists baseadas no meu gosto | [Confiabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-confiabilidade) | [RNF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Histórico de Músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#historico-de-musicas) | - | [L07](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RNF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Recomendações de músicas e playlists](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) | - | [Q04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) | - | [RF08](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) | [EF20](#EF20) |
| RNF21 | Ver artistas favoritos | [Confiabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-confiabilidade) | [RNF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C5](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | - | [RNF03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | -| - | - | [EF21](#EF21) |
| RNF22 | Saber as músicas mais tocadas de um país | - | [RNF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Descobrir novas músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#descobrir-novas-musicas) | - | [L06](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RNF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US03](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | - | - | [EF22](#EF22) |
| RNF23 | Conhecer lançamentos no mundo da música | - | [RNF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Descobrir novas músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu/#descobrir-novas-musicas) | - | [L06](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RNF06](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | - | - | [EF23](#EF23) |
| RNF24 | Mostrar aos amigos o que estou escutando | - | [RNF06](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | - | [RNF06](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF18](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) | [EF24](#EF24) |
| RNF25 | Adicionar novas músicas ao meu serviço de _streaming_ | - | [RNF07](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C10](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RNF07](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [Compartilhar músicas em outras plataformas](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | [US05](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) | [RNF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/observacao) | - | [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF20](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) | [EF25](#EF25) |
| RNF26 | Utilizar a aplicação de forma intuitiva.	| [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-usabilidade) | [RF08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF26](#EF26) |
| RNF27 | Não necessitar de um conhecimento grande sobre o mundo da música. | [Usabilidade](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-usabilidade) | [RF09](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF09](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF27](#EF27) |
| RNF28 | Não gastar todo meu plano de internet.	| [Desempenho](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-desempenho) | [RF10](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF28](#EF28) |
| RNF29 | Conhecer novas músicas e pessoas. | - | [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | [Descobir novas músicas](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/especificacao_dcu) | - | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) | - | - | - | [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais) | [EF29](#EF29) |
| RNF30 | Dissipar meu conhecimento musical.	| - | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) | [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) | [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | [US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) | - | - | [V1](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) | [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais) | [EF30](#EF30) |
| RNF31 | Não precisar entrar no app para escanear uma música. | - | [RF13](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF13](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/requisitos-funcionais) | [EF31](#EF31) |
| RNF32 | Saber a letra de uma música que está tocando em um vídeo. | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - | - | - | - | - | [EF32](#EF32) |
| RNF33 | Poder identificar qualquer música ao redor sem entrar no app com a opção auto Shazam ativada. | - | [RF15](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF15](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | [RF20](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst) | - |  - | - | - | [RF14](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/requisitos-funcionais) | [EF33](#EF33) |
| RNF34 | Poder escolher um tema claro ou escuro para o app.	| - | [RF16](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF16](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF34](#EF34) |
| RNF35 | Reconhecer mídia através da voz do usuário	| - | [RF17](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) | - | - | - | [RF17](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) | - | - |  - | - | - | - | [EF35](#EF35) |
| RNF36 | Interação com o Shazam Code | - | [RNF18](../modelagem/backlog.md) | - | [C13](../modelagem/cenarios.md#c13)| [L11](../modelagem/lexicos.md#l11) | - | - | - | - | - | - | - | - | - | - |


## Elos Funcionais

### EF01

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

Representação:  [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) representa [C2](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios)

Agregação: [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog) agrega [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos)

---
### EF02

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) representa [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog)

[C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) agrega [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos)

---
### EF03
---
### EF04
---
### EF05

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[RF09](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) agrega [RF14 First things First](https://requisitos-de-software.github.io/2019.2-Shazam/priorizacao/firstThingFirst)

---
### EF06

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[NFR de Desempenho](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-desempenho) agrega [RF10](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF07

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[RF11](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) agrega [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos)

[US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [RF11 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais)

---
### EF08

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) agrega [C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos)

[US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [Rich Picture V1](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/)

---
### EF09

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[RF13](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) representa [RF11 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais)

---
### EF10
---
### EF11

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[RF15](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog) representa [RF14 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming/#requisitos-funcionais)

---
### EF12
---
### EF13
---
### EF14

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[NFR de Segurança](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/NFR/#nfr-de-seguranca) [C2](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF15

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/)

[RF04 Observação](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/observacao) representa [RF12 Brainstroming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming#Requisitos-Funcionais)

### EF16
---
### EF17

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [RF01 Análise de Protocolo](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo) [Q01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1)

[C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) demanda [US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories)

---
### EF18

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [RF01 Análise de Protocolo](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo) [Q01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1)

[C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[C1](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [Rich Pictures](https://requisitos-de-software.github.io/2019.2-Shazam/pre-rastreabilidade/rich-pictures/) demanda [US01](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories)

---
### EF19

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US02](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories) representa [RF03 Analise de Protocolo](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/analise_protocolo)  [Q05](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) [RF03 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming)

[C3](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RNF01](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF20

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) representa [Q04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1) [RF08 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming)

[L04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RNF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF21

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[C5](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) agrega [RNF02](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF22

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US03](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) demanda [RNF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF23

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) demanda [RNF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[L6](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RNF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF24

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) representa [RF18 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming)

[US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) demanda [RNF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) agrega [RNF05](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF25

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[C10](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) [L08](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF04](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

[US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) representa [RF20 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming) [Q05](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/questionario/questionario_v1)

---
### EF26
---
### EF27
---
### EF28
---
### EF29

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US04](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) representa [RF11 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming)

[L03](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/lexicos) agrega [RF11](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF30

<b>Categoria</b>: Desenvolvimento

<b>Elos</b>:

[US06](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/introspeccao/#user-stories/#user-stories) representa [RF04 Brainstorming](https://requisitos-de-software.github.io/2019.2-Shazam/elicitacao/brainstorming)

[C9](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/cenarios) agrega [RF12](https://requisitos-de-software.github.io/2019.2-Shazam/modelagem/backlog/#product-backlog)

---
### EF31
---
### EF32
---
### EF33
---
### EF34
---
### EF35
---

## Controle de versão

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 13/11/2019 | 1.0 | Criação do documento e primeira versão da Matriz de Rastreabilidade | Ernando | 
| 14/11/2019 | 1.1 | Adição de novos requisitos | Victor Levi Peixoto && Gabriel Marques Tiveron | 
| 14/11/2019 | 1.2 | Adição de referencias ao First Things First | Victor Levi && Gabriel Tiveron |
| 14/11/2019 | 1.3 | Correção de links de rastreabilidade | Victor Levi && Gabriel Tiveron |
| 25/11/2019 | 2.0 | Adição dos Elos Funcionais | Ernando Braga | 
| 27/11/2019 | 2.1 | Padronização do identificador dos requisitos não funcionais | Gabriel Tiveron |
| 27/11/2019 | 2.2 | Adição da pós rastrabilidade do RNF36 | Gabriel Tiveron |


## Referências

### Exemplo de modelo de Backward From

http://www.joberth-rogers.ml/2018.2-Requisitos-Pinterest/backward_from/ Acesso em 13 de novembro de 2019.

https://github.com/gabrielziegler3/Requisitos-2018-1/wiki/Matriz-Rastreabilidade Acesso em 13 de novembro de 2019.


### Material disponibilizado pelo professor

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 24. 2º/2019. 44 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
