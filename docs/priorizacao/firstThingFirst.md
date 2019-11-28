# First Thing First

## 1. Introdução
<p align="justify">O First Things First(em português "primeiras coisas primeiro") é uma técnica de priorização de requisitos que equilibra os benefícios de cada função contra seus custos, define as implicações que serão acarretadas na arquitetura, alinha requisitos e regras de negócio e estabelece risco técnico e demais dificuldades associados a um dado requisito.</p>

## 2. Objetivo
<p align="justify">O First Things First tem como objetivo produzir uma tabela que prioriza os requisitos sem que haja desbalanceamento por parte apenas do cliente, do desenvolvedor. Ele envolve 3 papeis, o gerente, o representante dos clientes e o representante do desenvolvimento.</p>

## 3. Metodologia
<p align="justify">As pririzações foram feitas usando uma introspecção em que as necessidades de cada papel eram levadas em consideração. A metologia segue 8 passos :</p>

<p align="justify">Passo 1: Listar todos os requisitos em uma tabela, retirando aqueles dependentes de outro requisito. Os requisitos aqui utilizados foram retirados das outras técnicas de outras técnicas de elicitação de requisitos, como o storytelling, entrevistas e introspecção.</p>
<p align="justify">Passo 2: Estimar o benefício relativo que cada recurso fornece ao cliente ou ao negócio de 1 a 9, em que 1 é o menos significativo</p>
<p align="justify">Passo 3: Estimar a penalidade que o negócio sofreria, se o recurso não for incluído, de 1 a 9, em que 1 é o com menor penalidade</p>
<p align="justify">Passo 4: A Coluna valor total é a soma do (Benefício Relativo * Peso Relativo + Penalidade Relativa * Peso Relativo), o peso relativo utilizado nesse caso foi de 1.</p>
<p align="justify">Passo 5: Estime o custo relativo de implementação de cada requisito, de 1 a 9.</p>
<p align="justify">Passo 6: Estime o grau relativo ao risco a cada requisito de uma escala de 1 a 9.</p>
<p align="justify">Passo 7: Calcular a prioridade para cada requisito usando: valor % / (custo % * Peso custo + risco % * Peso Risco). O Peso custo e risco aqui utilizados foram de 1.</p>
<p align="justify">Passo 8: Ordenar a lista em ordem decrescente de prioridade.</p>

#### V1.0
<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos2-2019/Shazam/master/docs/imgs/Firstthingfirst.jpg">
</p>
#### V1.1
<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos2-2019/Shazam/master/docs/imgs/First.png">
</p>

|Data|Versão|Alteração|Responsável(eis)|
|:--:|:----:|:-------:|:---:|
| 30/09/2019 | 1.0 | Criação do documento | Débora Vilela |
| 30/09/2019 | 1.1 | Adicionando imagem do First Thing First | Débora Vilela | 
| 14/11/2019 | 1.2 | Adição de indexação dos Requisitos | Gabriel Tiveron|

## Referências

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. 1º/2019. 35 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.