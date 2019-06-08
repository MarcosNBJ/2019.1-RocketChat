# Inspeção de Argumentação

## Introdução

Neste documento, iremos demonstrar a verificação para os os artefatos do modelo de argumentação. Através de alguns critérios para a avaliação do artefato, seguindo o framework Acceptability Evaluation (ACE), proposto por Jureta em 2009.

## Metodologia

Para executar a inspeção de cada artefato, foi desenvolvido uma tabela, contendo critérios e importância. <br>
Os critérios foram baseados no modelo ACE e em parâmetros definidos pela equipe. A importância de cada critério foi determinada levando em consideração pontos para que o artefato esteja em conformidade com o modelo proposto, sendo alta as condições para que o artefato esteja correto, e baixa, que não necessáriamente a condição precise ser atendida mas que agregaria positivamente ao artefato. <br>
Com isso, é atribuido uma nota de 1 a 5 para cada critério, sendo 1, critério não foi satisfeito e 5, critério totalmente satisfeito. Além disso, são sugeridas melhorias para os critérios que tiverem falhado em ser atendidos.

## Critérios

Ao final do documento, foi disponibilizado um [material de apoio](#material-de-apoio-para-a-avaliacao) para os critérios a seguir.

|Nº|Critério|Material correspondente|Importância
|:--:|:--:|:--:|:--:|
|1|O diagrama foi representado na forma de um grafo?|[Exemplo](#4-exemplo)|Alta|
|2|Cada vértice foi classificado de forma correta?|[Classificação](#1-classificacao-de-cada-vertice)|Alta|
|3|Cada vértice foi formalmente descrito?|[Descrição](#2-descricao-formal)|Baixo|
|4|A propagação (setas) dos vértices foram executadas de forma correta?|[Propagação](#3-propagacao)|Alta|
|5|Todos os conflitos, gerados na discussão, foram resolvidos?||Médio|
|6|Vértices de proposições, ligados somente por I, C, P?||Alta|
|7|Todas as inferências do diagrama foram descritas no artefato?|[Exemplo](#4-exemplo)|Alta|
|8|Os vértices foram destacados com cores, representando cada classificação, possibilitando uma melhor visualização?|[Exemplo](#4-exemplo)|Baixo|


## Registro de inspeção

#### IARG-0X

|Diagrama de argumentação|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|||||

|Nº|Critério|Material correspondente|Nota|Observação/Melhoria|
|:--:|:--:|:--:|:--:|:--:|
|1|O diagrama foi representado na forma de um grafo?|[Exemplo](#4-exemplo)|||
|2|Cada vértice foi classificado de forma correta?|[Classificação](#1-classificacao-de-cada-vertice)|||
|3|Cada vértice foi formalmente descrito?|[Descrição](#2-descricao-formal)|||
|4|A propagação (setas) dos vértices foram executadas de forma correta?|[Propagação](#3-propagacao)|||
|5|Todos os conflitos, gerados na discussão, foram resolvidos?||||
|6|Vértices de proposições, ligados somente por I, C, P?||||
|7|Todas as inferências do diagrama foram descritas no artefato?|[Exemplo](#4-exemplo)|||
|8|Os vértices foram destacados com cores, representando cada classificação, possibilitando uma melhor visualização?|[Exemplo](#4-exemplo)|||

## Material de apoio para a avaliação

### __1 -Classificação de cada vértice:__
* __i__ - informações, proposições.
* __I__ - inferências.
* __C__ - conflito.
* __P__ - preferência.

### __2 -Descrição formal:__
* Ex. Conflito: C1(i(p2), i(p1))
* Ex. Inferência: It(i(p1), i(p2))
* Ex. Preferência:  P1(i(p1), i(p2))

### __3 - Propagação__

A partir da proposição de p1, podemos inferir a proposição de p2. A proposição de p3 gera conflito com a proposição de p2. Acaba gerando uma preferência por p2 em relação à p3 e essa preferência conflita com C1 e com p3. Pela preferência escolhida, podemos inferir p4.

![](../img/Analise/ex_argumentação.jpg)

### __4 - Exemplo__

![](../img/Analise/elicitacao.png)


## Referências

1 - JURETA, I.; MYLOPOULOS, J.; FAULKNER, S. Analysis of multi-party agreement in requirements validation. In: Proceedings of the 2009 17th IEEE International Requirements Engineering Conference, RE. Washington, DC, USA: IEEE Computer Society, 2009. (RE ’09), p. 57–66. ISBN 978-0-7695-3761-0.

2 - SERRANO, Maurício. Desenvolvimento Intencional de Software Transparente Baseado em Argumentação. 2011. Tese de Doutorado. PUC-Rio.

## Versionamento

| Data | Versão | Modificação | Autor |
|  --- | ------ | ----------- | ----- |
| 07/06/2019 | 1.0 | Abertura do documento | Heron Rodrigues |
