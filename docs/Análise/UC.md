# Inspeção de Casos de Uso

## Introdução

Este documento tem como finalidade apresentar a inspeção de alguns casos de uso, que é uma das técnicas utilizadas no módulo anterior de Modelagem de requisitos.

## Objetivo

O objetivo é observar vários aspectos do documento e realizar a análise da qualidade. A partir dos dados da análise descobrir as falhas existentes, facilitando assim a melhoria.

## Metodologia

Para a inspeção dos casos de uso foi estabelecido um checklist, com questões e critérios a serem avaliados, que busca localizar defeitos no modelo. É sugerida uma classificação para cada artefato, categorizados em alto, médio e baixo, confome a avaliação.
Critérios de alto impacto, são defeitos que afetam a compreensão, a falta de coerência e a falta de definição. Critérios de impacto médio, são defeitos que afetam a qualidade do caso de uso de forma considerável, abaixo do impacto alto. Critérios de baixo impacto são defeitos que se corrigidos aumentariam a qualidade do caso de uso, mas que não impedem a compreensão.
A fim de registrar os defeitos com os checklists para que sirvam como base para a medição da inspeção, os seguintes artefatos são propostos:

### Checklist

|Nº|Critério|Impacto|
|:--:|:--:|:--:|
| 1 | A descrição de caso de uso é a de um caso de uso representado no diagrama? | Alto |
| 2 | A descrição de caso de uso contém nome do caso de uso, nome do ator, fluxo básico e alternativo? | Alto |
| 3 | Se houver tabelas ou figuras, elas têm explicação adicional de forma que fiquem compreensíveis para o leitor? | Baixo |
| 4 | As frases representam um diálogo entre ator e sistema, evidenciando a ação do ator e a resposta do sistema? | Médio |
| 5  | As frases se utilizam de subtítulos para comunicar as idéias chaves dos fluxos de forma mais clara? | Baixo |
| 6  | As frases são construídas em voz ativa? (ex.: “Sistema valida a quantia informada” em vez de “A quantia informada deve ser validada pelo sistema”). | Baixo |
| 7  | São evitados termos sem quantificação precisa, como “muito”, “pouco”, “adequado”, “claro”, “fácil” “longo”, “curto”, “rápido” “etc”? | Médio |
| 8  | Uma vez utilizado um termo, ele é mantido para referenciar-se ao mesmo elemento? | Médio |
| 9  | São evitados termos que indicam a prematura especificação de interface, tais como “clicar” “botão” etc? | Baixo |
| 10 | As funcionalidades se restringem ao quê o sistema deve fazer e não em como, evitando a definição explícita de código na especificação? | Médio |
| 11 | A descrição evita requisitos de negócio sem ação direta ao sistema? | Médio |
| 12 | O fluxo básico está aparentemente completo, isto é, há inexistência de evidências claras de incompleteza na especificação? | Alto |
| 13 | O fluxo alternativo está aparentemente completo, isto é, há inexistência de evidências claras de incompleteza na especificação? | Alto |
| 14 | O caso de uso é acompanhado de protótipo de interface a fim de aumentar a sua compreensibilidade? | Alto |
| 15 | O caso de uso é acompanhado de especificação de requisitos não funcionais separadas do fluxo de eventos do caso de uso ou em documento de especificação suplementar? | Médio |

### Registro de inspeção de Caso de Uso

As colunas 3, 4, 5 são registros de não-conformidades referem-se ao registro da aplicação de cada questão, onde N/A (não se aplica) indica que a questão não se aplica ao produto inspecionado, S (sim) indica que o produto inspecionado atende à questão e N (não) indica que o produto não atende à questão e que representa um defeito.
Para o registro de inspeção deve seguir a seguinte tabelas:

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|||||

|Nº|Impacto|N/A|Sim|Não|Observação|
|:--:|:--:|:--:|:--:|:--:|:--:|
| 1  | Alto |||||
| 2  | Alto |||||
| 3  | Baixo |||||
| 4  | Médio |||||
| 5  | Baixo |||||
| 6  | Baixo |||||
| 7  | Médio |||||
| 8  | Médio |||||
| 9  | Baixo |||||
| 10 | Médio |||||
| 11 | Médio |||||
| 12 | Alto |||||
| 13 | Alto |||||
| 14 | Alto |||||
| 15 | Médio ||||||

### Medição da inspeção

O critério de aceitação se refere a um percentual máximo de defeitos que o artefato inspecionado pode ter. Se esse resultado ultrapassar o critério de aceitação, será reprovado. Acredita-se que um percentual razoável esteja entre 30% a 40%. Neste trabalho é proposto um percentual de 35%, o que significa que os casos de usos inspecionados deveram ter no máximo 35% de defeitos para serem aprovados.
A metodologia e as métricas utilizadas para melhor inspeção dos casos de usos, assim como as tabelas e diagramas, foram inspirados a partir do estudo proposto em [(1)](#referencias).

|Impacto |Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitavivo|
|:--:|:--:|:--:|:--:||:--:|:--:|:--:|:--:|
|Alta|3|5|15||||Aprovado ou Reprovado
|Média|2|6|12|||
|Baixa|1|4|4|||
|**Total:**||15|31|||
|Critério de aceitação:|35%|

## Referências

[1] - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acesso em: 05 jun. 2019.

[2] - IBM. Use-case. Disponível em: https://www.ibm.com/developerworks/rational/library/content/RationalEdge/may02/m_chapter4_jr.pdf. Acesso em: 05 jun. 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|  --- | ------ | ----------- | ----- |
| 05/06/2019 | 1.0 | Abertura do documento | André Lucas |
| 05/06/2019 | 1.1 | Inclusão da metodologia, checklist e medição utilizadas | André Lucas |
