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
| 1  | A descrição de caso de uso é a de um caso de uso representado no diagrama? | Alto |
| 2  | A descrição de caso de uso contém nome do caso de uso, nome do ator, fluxo básico e alternativo? | Alto |
| 3  | As frases utilizam o tempo presente? | Baixo |
| 4  | As frases representam um diálogo entre ator e sistema, evidenciando a ação do ator e a resposta do sistema? | Médio |
| 5  | As frases se utilizam de subtítulos para comunicar as idéias chaves dos fluxos de forma mais clara? | Baixo |
| 6  | As frases são construídas em voz ativa? (ex.: “Sistema valida a quantia informada” em vez de “A quantia informada deve ser validada pelo sistema”). | Baixo |
| 7  | São evitados termos sem quantificação precisa, como “muito”, “pouco”, “adequado”, “claro”, “fácil” “longo”, “curto”, “rápido” “etc”? | Médio |
| 8  | Os termos passíveis de mais de uma interpretação constam em glossário, com clara definição? | Alto |
| 9  | Uma vez utilizado um termo, ele é mantido para referenciar-se ao mesmo elemento? | Médio |
| 10 | São evitados termos que indicam a prematura especificação de interface, tais como “clicar” “botão” etc?| Baixo |
| 11 | As funcionalidades se restringem ao quê o sistema deve fazer e não em como, evitando a definição explícita de código na especificação? | Médio |
| 12 | A descrição evita requisitos de negócio sem ação direta ao sistema? | Médio |
| 13 | Há presença de breve descrição de caso de uso, que especifique de forma clara o seu propósito? | Baixo |
| 14 | O fluxo básico está aparentemente completo, isto é, há inexistência de evidências claras de incompleteza na especificação? | Alto |
| 15 | O fluxo alternativo está aparentemente completo, isto é, há inexistência de evidências claras de incompleteza na especificação? | Alto |
| 16 | As frases são numeradas para que possibilitem a rastreabilidade? | Alto |
| 17 | Os fluxos de exceção são corretamente descritos?  | Médio |

### Registro de inspeção de Caso de Uso

As colunas 3, 4, 5 são registros de não-conformidades referem-se ao registro da aplicação de cada questão, onde N/A (não se aplica) indica que a questão não se aplica ao produto inspecionado, S (sim) indica que o produto inspecionado atende à questão e N (não) indica que o produto não atende à questão e que representa um defeito.
Para o registro de inspeção deve seguir a seguinte tabelas:

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|||||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   |   |          |
| 2  | Alto  |   |   |   |          |
| 3  | Baixo |   |   |   |          |
| 4  | Médio |   |   |   |          |
| 5  | Baixo |   |   |   |          |
| 6  | Baixo |   |   |   |          |
| 7  | Médio |   |   |   |          |
| 8  | Alto  |   |   |   |          |
| 9  | Médio |   |   |   |          |
| 10 | Baixo |   |   |   |          |
| 11 | Médio |   |   |   |          |
| 12 | Médio |   |   |   |          |
| 13 | Baixo |   |   |   |          |
| 14 | Alto  |   |   |   |          |
| 15 | Alto  |   |   |   |          |
| 16 | Alto  |   |   |   |          |
| 17 | Médio |   |   |   |          |

### Medição da inspeção

O critério de aceitação se refere a um percentual máximo de defeitos que o artefato inspecionado pode ter. Se esse resultado ultrapassar o critério de aceitação, será reprovado. Acredita-se que um percentual razoável esteja entre 30% a 40%. Neste trabalho é proposto um percentual de 30%, o que significa que os casos de usos inspecionados deveram ter no máximo 30% de defeitos para serem aprovados.
A metodologia e as métricas utilizadas para melhor inspeção dos casos de usos, assim como as tabelas e diagramas, foram inspirados a partir do estudo proposto em [(1)](#referencias).

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 6  | 18 |   |    |        |Aprovado ou Reprovado |
|Média     | 2 | 6  | 12 |   |    |        |   |  
|Baixa     | 1 | 5  | 5  |   |    |        |   |
|**Total:**|   | 17 | 35 |   |    |        |   |
|Critério de aceitação:|30%|

### Inspeção

A seguir podem ser vistas as inspeções individuais de cada caso de uso previamente construído.

#### IUC-01

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[EC1 - Fixar Mensagem](../Modelagem/especificacao.md#ec1)|05/06/2019|André Lucas|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|:--:|:-----:|:-:|:-:|:-:|:--------:|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  | x |   |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | São utilizadas expressões que especifica a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  | x |   |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, não descrevem as ações do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|---|--------|---|
|Alta      | 3 | 6  | 18 | 0 | 0 | 14.29% | Aprovado |
|Média     | 2 | 6  | 12 | 2 | 4 |        |   |  
|Baixa     | 1 | 5  | 5  | 1 | 1 |        |   |
|**Total:**|   | 17 | 35 | 3 | 5 |        |   |
|Critério de aceitação:|30%|

#### IUC-02

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[EC2 - Mudar privacidade do Channel](../Modelagem/especificacao.md#ec2)|06/06/2019|André Lucas|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|:--:|:-----:|:-:|:-:|:-:|:--------:|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   |   | x | O fluxo alternativo não está especificado |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema em nenhum momento |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo | x |   |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | O termo "clica" é utilizado várias vezes |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   |   | x | Algumas frases do fluxo devem ser reformuladas |
| 15 | Alto  |   |   | x | Não há fluxo alternativo|
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 6  | 18 | 3 | 9  | 34.29% | Reprovado |
|Média     | 2 | 6  | 12 | 1 | 2  |        |   |  
|Baixa     | 1 | 5  | 5  | 1 | 1  |        |   |
|**Total:**|   | 17 | 35 | 5 | 12 |        |   |
|Critério de aceitação:|30%|

#### IUC-03

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[EC3 - Criar only-read channel](../Modelagem/especificacao.md#ec3)|06/06/2019|André Lucas|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|:--:|:-----:|:-:|:-:|:-:|:--------:|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   |   | x | O fluxo alternativo não está especificado |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo | x |   |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utiliza o termo "clica" e o termo "botão" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   |   | x | O fluxo principal pode ser reescrito, retirando os termos incorretos |
| 15 | Alto  |   |   | x | Não há fluxo alternativo |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 6  | 18 | 3 | 9  | 34.29% | Reprovado |
|Média     | 2 | 6  | 12 | 1 | 2  |        |   |  
|Baixa     | 1 | 5  | 5  | 1 | 1  |        |   |
|**Total:**|   | 17 | 35 | 3 | 12 |        |   |
|Critério de aceitação:|30%|

#### IUC-04

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[EC4 - Alterar Status](../Modelagem/especificacao.md#ec4)|06/06/2019|André Lucas|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo | x |   |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utiliza o termo "clica" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|---|--------|---|
|Alta      | 3 | 6  | 18 | 0 | 0 | 8.57%  | Aprovado |
|Média     | 2 | 6  | 12 | 1 | 2 |        |   |  
|Baixa     | 1 | 5  | 5  | 1 | 1 |        |   |
|**Total:**|   | 17 | 35 | 2 | 3 |        |   |
|Critério de aceitação:|30%|

#### IUC-05

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC5 - Deletar Conta](../Modelagem/especificacao.md#ec5)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   | A especificação de uso está se referindo á um tema no diagrama e não a um caso de uso |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado o termo "clica" algumas vezes|
| 11 | Médio |   | x |   |          |
| 12 | Médio | x |   |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, deve ser descrito as ações do sistema após a exceção e não as ações do usuário |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|----------|
|Alta      | 3 | 5 | 18 | 1 |  3  | 22.86% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 15| 35 | 4 |  8  |
| Critério de aceitação: | 30%    |

#### IUC-06

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC6 - Mensagens Favoritadas](../Modelagem/especificacao.md#ec6)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado o termo "clica" algumas vezes|
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção incompleto, exceção 2 não é uma exceção do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|----------|
|Alta      | 3 | 5 | 18 | 0 |  0  | 14.29% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 15| 35 | 3 |  5  |
| Critério de aceitação: | 30%    |

#### IUC-07

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC7 - Visualizar membros de chat em grupo](../Modelagem/especificacao.md#ec7)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  | x |   |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   | x |   |          |
| 9  | Médio |   | x |   |          |
| 10  | Baixo |   |   | x | Utilizado o termo "clica" algumas vezes|
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  | x |   |   | Os fluxos alternativos contém ações que não se aplicam ao caso de uso |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, não descrevem as ações do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|----------|
|Alta      | 3 | 5 | 18 | 0 |  0  | 14.29% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 15| 35 | 3 |  5  |
| Critério de aceitação: | 30%    |

## Referências

[1] - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acesso em: 05 jun. 2019.

[2] - IBM. Use-case. Disponível em: https://www.ibm.com/developerworks/rational/library/content/RationalEdge/may02/m_chapter4_jr.pdf. Acesso em: 05 jun. 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|  --- | ------ | ----------- | ----- |
| 05/06/2019 | 1.0 | Abertura do documento | André Lucas |
| 05/06/2019 | 1.1 | Inclusão da metodologia, checklist e medição utilizadas | André Lucas |
| 06/06/2019 | 1.2 | Adição do IUC01 e IUC02 | André Lucas |
| 06/06/2019 | 1.3 | Adição do IUC03 e IUC04 | André Lucas |
| 07/06/2019 | 1.4 | Adição das IUC05 - IUC07 | Lucas Maciel |
