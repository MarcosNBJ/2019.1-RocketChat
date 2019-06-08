# Inspeção do IStar

## Introdução

Documento que busca analisar os modelos de IStar levantados anteriormente no tópico de modelagem, tanto a parte de Strategic Dependency Models quanto a parte de Strategic Rationale Models serão alvos desta inspeção, afim de identificar possíveis erros e falhas presentes nos mesmos, bem como apontar soluções e correções para esses erros.

## Metodologia

Para que a inspeção fosse realizada de forma a se obter um resultado positivo, primeiro foram estabelecidas duas checklists, uma para o Strategic Dependency Models(SD) e outra para o Strategic Rationale Models(SR), contendo critérios considerados importantes para que se possa obter um IStar de qualidade. Para cada um destes critérios foi atribuído um peso, podendo ser de alto, médio ou baixo impacto. Sendo o de alto impacto o critério considerado crítico para o bom entendimento do modelo, bem como os aspectos fundamentais para que o modelo possa ser considerado "correto". Já os critérios de baixo impacto são aqueles que se ausentes, não tornam o modelo necessariamente ruim ou incorreto, mas sua presença contribui para a qualidade do mesmo.

### Critérios

|Nº|Critério|Impacto|
|:--:|:--:|:--:|
||**Strategic Dependency Model**||
| 1 | Todas as dependências estão direcionadas corretamente? | Médio |
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? | Alto |
| 3 | Os Softgoals representam requisitos não-funcionais? | Alto |
| 4 | Os atores estão representados com a abstração correta?  | Baixo |
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? | Médio |
| 6 | As metas são objetivos que se deseja alcançar? | Alto |
| 7 | As metas estão descritas em voz passiva? | Médio |
| 8 | Todos os recursos são substantivos? | Médio |

|Nº|Critério|Impacto|
|:--:|:--:|:--:|
||**Strategic Rationale Model**||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? | Baixo |
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? | Médio |
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? | Médio |
| 4 | As ligações 'and' e 'or' estão corretas? | Médio |
| 5 | Os impactos estão representados com sentido e intensidade corretas? | Médio |
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) | Baixo |
| 7 | Todos os recursos são substantivos? | Médio |
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? | Alto |
| 9 | Os Softgoals representam requisitos não-funcionais? | Alto |
| 10 | As metas são objetivos que se deseja alcançar? | Alto |
| 11 | As metas estão descritas em voz passiva? | Médio |

### Critério de aceitação

O critério de aceitação implica na atribuição de um peso para cada tipo de impacto que um critério pode ter, o que possibilita calcular a pontuação máxima total, que é a quantidade de pontos máxima que um modelo pode alcançar caso tenha cumprido com todos os critérios listados anteriormente. Neste caso, a tolerância usada será de 30%, ou seja, para ser considerado aprovado, o modelo deverá obter no mínimo 70% da pontuação total possível. Para formulação desse critério de aceitação foi usado como base a metodologia presente em [(1)](#referencias).

|Impacto do critério|Peso atribuído|Quantidade de critérios|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
|Alta | 3 | 3 | 9 |
|Média| 2 | 4 | 8 |
|Baixa| 1 | 1 | 1 |
|**Total:**||9| 18|

|Impacto do critério|Peso atribuído|Quantidade de critérios|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
|Alta | 3 | 3 | 9 |
|Média| 2 | 6 | 12|
|Baixa| 1 | 2 | 2 |
|**Total:**||9| 23|

Utilizando como base a tolerância máxima de 30%, temos como resultado que os modelos devem ter uma pontuação de no mínimo 12,6 pontos para o SD e de no mínimo 16,1 para o SR para serem aprovados, com qualquer pontuação menor do que está, o modelo é considerado reprovado e deve ser revisado. Isso não impede, é claro, de que modelos considerados aprovados também possam ser revisados, pois podem existir pequenos erros facilmente reparáveis.

### Inspeção

A seguir podem ser vistas as inspeções individuais de cada Strategic Dependency Model(SD) e de cada Strategic Rationale Model(SR) previamente construído.

#### IISD-0X

_Inspeção do [ISD0X](../Modelagem/istar.md#)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |||
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |||
| 3 | Os Softgoals representam requisitos não-funcionais? |||
| 4 | Os atores estão representados com a abstração correta?  |||
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |||
| 6 | As metas são objetivos que se deseja alcançar? |||
| 7 | As metas estão descritas em voz passiva? |||
| 8 | Todos os recursos são substantivos? ||||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|||
|Médio|||
|Baixo|||
|**Total**|||
||**Conclusão**||
|||||

#### IISR-0X

_Inspeção do [ISR0X](../Modelagem/istar.md#)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |||
| 4 | As ligações 'and' e 'or' estão corretas? |||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |||
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |||
| 7 | Todos os recursos são substantivos? |||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |||
| 9 | Os Softgoals representam requisitos não-funcionais? |||
| 10 | As metas são objetivos que se deseja alcançar? |||
| 11 | As metas estão descritas em voz passiva? ||||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|||
|Médio|||
|Baixo|||
|**Total**|||
||**Conclusão**||
|||||

## Referências

1 - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acessado em: 07, jun, 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 07/05/2019 | 1.0 | Abertura do documento | Weiller Fernandes |
| 07/05/2019 | 1.1 | Inclusão da Metodologia, Critérios e Critério de aceitação | Weiller Fernandes |
| 08/05/2019 | 1.2 | Adição das inspeções-modelo IISD-0X e IISR-0X | Weiller Fernandes |
