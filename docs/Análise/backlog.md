# Inspeção do Product Backlog

## Introdução

Documento que busca analisar os modelos de product backlog levantados anteriormente no tópico de modelagem, mais especificamente as User Stories propostas, afim de identificar possíveis erros e falhas presentes nas mesmas e apontar as soluções e correções a serem feitas.

## Metodologia

Para que a inspeção fosse realizada de forma a se obter um resultado positivo, primeiro foi estabelecida uma checklist, contendo critérios considerados importantes para que se possa obter um product backlog de qualidade. Para cada um destes critérios foi atribuído um peso, podendo ser de alto, médio ou baixo impacto. Sendo o de alto impacto o critério considerado crítico para o bom entendimento do modelo, bem como os aspectos fundamentais para que o modelo possa ser considerado "correto". Já os critérios de baixo impacto são aqueles que se ausentes, não tornam o modelo necessariamente ruim ou incorreto, mas sua presença contribui para a qualidade do mesmo.

### Critérios

|Nº|Critério|Impacto|
|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) | Alto |
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) | Alto |
| 3 | A User Storie tem um ID único para identificação? | Médio |
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? | Médio |
| 5 | A User Storie possui critérios de aceitação? | Alto |
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? | Médio |
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? | Médio |
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? | Baixo |
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) | Médio |

### Critério de aceitação

O critério de aceitação implica na atribuição de um peso para cada tipo de impacto que um critério pode ter, o que possibilita calcular a pontuação máxima total, que é a quantidade de pontos máxima que um modelo pode alcançar caso tenha cumprido com todos os critérios listados anteriormente. Neste caso, a tolerância usada será de 30%, ou seja, para ser considerado aprovado, o modelo deverá obter no mínimo 70% da pontuação total possível. Para formulação desse critério de aceitação foi usado como base a metodologia presente em [(1)](#referencias).

|Impacto do critério|Peso atribuído|Quantidade de critérios|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
|Alta | 3 | 3 | 9 |
|Média| 2 | 5 | 10|
|Baixa| 1 | 1 | 1 |
|**Total:**||9| 20|

Modelo US será considerado reprovado se ultrapassar **6 pontos** em defeitos.

Utilizando como base a tolerância máxima de 30%, temos como resultado que os modelos devem ter uma pontuação de no mínimo 14 pontos para serem aprovados, com qualquer pontuação menor do que está, o modelo é considerado reprovado e deve ser revisado.

### Inspeção

A seguir podem ser vistas as inspeções individuais de cada User Storie previamente construída.

#### IUS-0X

_Inspeção do [US0X](../Modelagem/backlog.md#)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |||
| 3 | A User Storie tem um ID único para identificação? |||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |||
| 5 | A User Storie possui critérios de aceitação? |||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|||
|Médio|||
|Baixo|||
|**Total**|||
||**Conclusão**||
|||||

#### IUS-01

_Inspeção do [US01](../Modelagem/backlog.md#us01)_ Inspetor: Weiller Fernandes

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |Sim||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |Sim||
| 3 | A User Storie tem um ID único para identificação? |Sim||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |Não|Apenas o tema e o épico possuem nomes, para uma melhor identificação da US, o recomendado seria ela ter um nome também.|
| 5 | A User Storie possui critérios de aceitação? |Sim||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |Sim||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |Sim||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |Sim||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, poucas mudanças são necessárias, a principal é a adição de um nome para a US.|||

#### IUS-02

_Inspeção do [US02](../Modelagem/backlog.md#us02)_ Inspetor: Weiller Fernandes

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |Sim||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |Sim||
| 3 | A User Storie tem um ID único para identificação? |Sim||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |Não|Apenas o tema e o épico possuem nomes, para uma melhor identificação da US, o recomendado seria ela ter um nome também.|
| 5 | A User Storie possui critérios de aceitação? |Sim||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |Sim||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |Sim||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |Sim||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, poucas mudanças são necessárias, a principal é a adição de um nome para a US.|||

#### IUS-03

_Inspeção do [US03](../Modelagem/backlog.md#us03)_ Inspetor: Weiller Fernandes

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |Sim||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |Sim||
| 3 | A User Storie tem um ID único para identificação? |Sim||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |Não|Apenas o tema e o épico possuem nomes, para uma melhor identificação da US, o recomendado seria ela ter um nome também.|
| 5 | A User Storie possui critérios de aceitação? |Sim||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |Sim||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |Sim||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |Sim||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, poucas mudanças são necessárias, a principal é a adição de um nome para a US.|||

#### IUS-04

_Inspeção do [US04](../Modelagem/backlog.md#us04)_ Inspetor: Weiller Fernandes

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |Sim||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |Sim||
| 3 | A User Storie tem um ID único para identificação? |Sim||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |Não|Apenas o tema e o épico possuem nomes, para uma melhor identificação da US, o recomendado seria ela ter um nome também.|
| 5 | A User Storie possui critérios de aceitação? |Sim||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |Sim||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |Sim||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |Sim||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, poucas mudanças são necessárias, a principal é a adição de um nome para a US.|||

#### IUS-05

_Inspeção do [US05](../Modelagem/backlog.md#us05)_ Inspetor: Weiller Fernandes

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
| 1 | A granularidade do backlog está dentro do esperado? (Tema, épico, feature, US...) |Sim||
| 2 | O formato da US está correto e padronizado? (Eu, como, desejo, porque...) |Sim||
| 3 | A User Storie tem um ID único para identificação? |Sim||
| 4 | A User Storie tem um nome para que se possa saber de maneira fácil sobre o que se trata aquela US? |Não|Apenas o tema e o épico possuem nomes, para uma melhor identificação da US, o recomendado seria ela ter um nome também.|
| 5 | A User Storie possui critérios de aceitação? |Sim||
| 6 | Os critérios de aceitação são claros e diretos de forma que seja de fácil compreensão o que deve ser feito? |Sim||
| 7 | A User Storie possui rastreabilidade para o modelo de elicitação que a originou? |Sim||
| 8 | Os termos usados no product backlog são os mesmos usados pelos desenvolvedores dentro do app e na documentação do Rocket.Chat? |Sim||
| 9 | A priorização da US é feita utilizando-se uma técnica de fácil entendimento? (Alta, média e baixa ou MoSCoW) |Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, poucas mudanças são necessárias, a principal é a adição de um nome para a US.|||

## Referências

1 - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acessado em: 05, jun, 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 05/05/2019 | 1.0 | Abertura do documento | Weiller Fernandes |
| 05/05/2019 | 1.1 | Inclusão da Metodologia, Critérios e Critério de aceitação | Weiller Fernandes |
| 10/05/2019 | 1.2 | Adição das inspeções IUS-01 até IUS-05 | Weiller Fernandes |
