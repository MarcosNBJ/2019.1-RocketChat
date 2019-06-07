# Inspeção de Argumentação

## Introdução

Neste documento, iremos demonstrar a verificação para os os artefatos do modelo de argumentação. Através de alguns critérios para a avaliação do artefato, seguindo o framework Acceptability Evaluation (ACE), proposto por Jureta em 2009.

## Metodologia

Para executar a inspeção de cada artefato, foi desenvolvido um checklist, contendo critérios e importância. <br>
Os critérios foram baseados no modelo ACE e em parâmetros definidos pela equipe. A importância de cada critério foi determinada levando em consideração pontos para que o artefato esteja em conformidade com o modelo proposto, sendo alta as condições para que o artefato esteja correto, e baixa, que não necessáriamente a condição precise ser atendida mas que agregaria positivamente ao artefato. <br>
Com isso, é avaliado para cada artefato quantos critérios o mesmo atende e quantos não, ao fim aprovando ou reprovando o mesmo. Além disso, são sugeridas melhorias para os critérios que tiverem falhado em ser atendidos.

### Critérios

Ao final do documento, foi disponibilizado um [material de apoio]() para os critérios a seguir.

|Nº|Critério|Importância|
|:--:|:--:|:--:|
|1|O diagrama foi representado na forma de um grafo?|Alta|
|2|Cada vértice foi classificado de forma correta?|Alta|
|3|Cada vértice foi formalmente descrito?|Médio|
|4|A propagação dos vértices (setas) foram executadas de forma correta?|Alta|
|5|Todos os conflitos, gerados na discussão, foram resolvidos?|Médio|
|6|Relação do conflitos somente com proposições e preferências?|Alta|
|7|Todas as inferências do diagrama foram descritas no documento?|Alta|
|8|Relação das inferências somente entre proposições?|Alta|
|9|Os vértices foram destacados com cores, representando cada classificação, possibilitando uma melhor visualização?|Baixo|


### Registro de inspeção

|Diagrama de argumentação|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|||||

#### IARG-0X


|Nº|Critério|Check|Observação/Melhoria|
|:--:|:--:|:--:|:--:|
|1|O diagrama foi representado na forma de um grafo?|||
|2|Labels de cada vértice foi classificado de forma correta?|||
|3|A propagação dos vértices (setas) foram executadas de forma correta?|||
|4|Todos os conflitos, gerados na discussão, foram resolvidos?|||
|5|Relação do conflitos somente com proposições e preferências?|||
|6|Todas as inferências do diagrama foram descritas no documento?|||
|7|Relação das inferências somente entre proposições?|||
|8|Os vértices foram destacados com cores, representando cada classificação, possibilitando uma melhor visualização?|||

## Material de apoio para a avaliação

### __1 - Classificação de cada vértice:__
* __i__ - informações, proposições.
* __It__ - inferências.
* __C__ - conflito.
* __P__ - preferência.

### __2 - Descrição formal:__
* Conflito: C1(i(p2), i(p1))
* Inferência: It(i(p1), i(p2))
* Preferência: P1(i(p1), i(p2))





## Referências

1 - JURETA, I.; MYLOPOULOS, J.; FAULKNER, S. Analysis of multi-party agreement in requirements validation. In: Proceedings of the 2009 17th IEEE International Requirements Engineering Conference, RE. Washington, DC, USA: IEEE Computer Society, 2009. (RE ’09), p. 57–66. ISBN 978-0-7695-3761-0.

2 - SERRANO, Maurício. Desenvolvimento Intencional de Software Transparente Baseado em Argumentação. 2011. Tese de Doutorado. PUC-Rio.

## Versionamento

| Data | Versão | Modificação | Autor |
|  --- | ------ | ----------- | ----- |
| 07/06/2019 | 1.0 | Abertura do documento | Heron Rodrigues |
