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
| 2  | Alto  |   |   | x |          |
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
| 15 | Alto  | x |   |   | Caso de uso não necessariamente necessita de fluxo alternativo |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, não descrevem as ações do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|---|--------|---|
|Alta      | 3 | 6  | 18 | 1 | 3 | 22.86% | Aprovado |
|Média     | 2 | 6  | 12 | 2 | 4 |        |   |
|Baixa     | 1 | 5  | 5  | 1 | 1 |        |   |
|**Total:**|   | 17 | 35 | 4 | 8 |        |   |
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
|Alta      | 3 | 6 | 18 | 1 |  3  | 22.86% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 4 |  8  |
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
|Alta      | 3 | 6 | 18 | 0 |  0  | 14.29% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 3 |  5  |
| Critério de aceitação: | 30%    |

#### IUC-07

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC7 - Visualizar membros de chat em grupo](../Modelagem/especificacao.md#ec7)|07/06/2019|Lucas Maciel|

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
| 15 | Alto  |   |   |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, não descrevem as ações do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|----------|
|Alta      | 3 | 6 | 18 | 0 |  0  | 14.29% | Aprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 3 |  5  |
| Critério de aceitação: | 30%    |

#### IUC - 08

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC8 - Definir membro do channel como proprietário](../Modelagem/especificacao.md#ec8)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | O caso de uso está com o nome de "Tornar Proprietário do Channel" no diagrama |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Está faltando alguns links para os léxicos correspondentes |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Os fluxos alternativos estão incompletos |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos, não descrevem as ações do sistema |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 3 |  9  | 40.00% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 6 |  14 |
| Critério de aceitação: | 30%    |

#### IUC - 09

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC9 - Escolher tom de pele padrão](../Modelagem/especificacao.md#ec9)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Está faltando alguns links para os léxicos dos termos que precisam de interpretação |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Os fluxos alternativos estão incompletos |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções incompletos |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 31.43% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 5 |  11 |
| Critério de aceitação: | 30%    |

#### IUC - 10

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC10 - Criar channel](../Modelagem/especificacao.md#ec10)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Está faltando alguns links para os léxicos dos termos que precisam de interpretação |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Os fluxos alternativos estão incompletos, sem etapas com ações |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   | Talvez pudesse ter um complemento nas exceções |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 25.71% | Aprovado  |
|Média     | 2 | 6 | 12 | 1 |  2  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 5 |  11 |
| Critério de aceitação: | 30%    |

#### IUC - 11

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC11 - Conectar com um servidor](../Modelagem/especificacao.md#ec11)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  | x |   |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como o termo "clica" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Os fluxos alternativos estão incompletos, sem etapas com ações   |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   | Talvez pudesse ter um complemento nas exceções |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 22.86% | Aprovado  |
|Média     | 2 | 6 | 12 | 1 |  2  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 3 |  8  |
| Critério de aceitação: | 30%    |

#### IUC - 12

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC12 - Visualizar Mensagem Fixada](../Modelagem/especificacao.md#ec12)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Room e Pinned Messages não possuem os links para os léxicos que explicam os termos |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   | x |   |          |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  | x |   |   | Não há fluxo alternativo para esse caso de uso |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de Exceção incompletos |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 20.00% | Aprovado  |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 0 |  0  |
|**Total:**|   | 17| 35 | 3 |  7  |
| Critério de aceitação: | 30%    |

#### IUC - 13

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC13 - Pesquisa de mensagem](../Modelagem/especificacao.md#ec13)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   | No diagrama não há um caso de uso especifico de "Pesquisa de mensagem" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não apresenta a resposta do sistema ao usuário |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | Algumas frases não estão em voz ativa, como "O usuário não especifica bem o termo..." no fluxo alternativo |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos precisam de glossário, que seja nos léxicos ou na própria especificação |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como o termo "clica" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 20.00% | Aprovado  |
|Média     | 2 | 6 | 12 | 1 |  2  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 4 |  7  |
| Critério de aceitação: | 30%    |

#### IUC - 13 - v2

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC13 - Pesquisa de mensagem](../Modelagem/especificacao.md#ec13)|10/06/2019|André Lucas|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   | x |   | No item 5 do fluxo evidencia o retorno do sistema: "Mensagens relacionadas ao que foi pesquisado são retornadas para o usuário" |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | No item 5 poderia ser reescrito: "Sistema retorna mensagens relacionadas ao que foi pesquisado." |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos especificos não contém a definição, nem o link para o endereço que contenha |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utiliza-se o termo "clica", que indica a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 14.28% | Aprovado  |
|Média     | 2 | 6 | 12 | 0 |  0  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 3 |  5  |
| Critério de aceitação: | 30%    |

#### IUC - 14

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC14 - Realização de login](../Modelagem/especificacao.md#ec14)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   | x |   |          |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  | x |   |   |          |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como o termo "clica" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   |          |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 0 |  0  | 2.86%  | Aprovado  |
|Média     | 2 | 6 | 12 | 0 |  0  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 1 |  1  |
| Critério de aceitação: | 30%    |


#### IUC - 15

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC15 - Enviar mensagem](../Modelagem/especificacao.md#ec15)|07/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Channel" devem estar no glossário ou ter um link para o léxico |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   | x |   |          |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Fluxos alternativos incompletos, não possuem as ações possiveis |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções não mostra as ações que o sistema executa para orientar o usuário |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 28.57% | Aprovado  |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 0 |  0  |
|**Total:**|   | 17| 35 | 4 |  10  |
| Critério de aceitação: | 30%    |

#### IUC - 16

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC16 - Anexar arquivo](../Modelagem/especificacao.md#ec16)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Channel" devem estar no glossário ou ter um link para o léxico |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxos de exceções não mostram as ações que o sistema executa para orientar o usuário |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 22.86% | Aprovado  |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 4 |  8  |
| Critério de aceitação: | 30%    |

#### IUC - 17

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC17 - Anexar desenho](../Modelagem/especificacao.md#ec17)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Channel" e "Desenhar" devem estar no glossário ou ter um link para o léxico em questão |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Fluxo alternativo está incompleto, também não constam as ações tomadas pelo ator |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 31.43% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 5 |  11 |
| Critério de aceitação: | 30%    |

#### IUC - 18

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC18 - Responder mensagem](../Modelagem/especificacao.md#ec18)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | O nome utilizado no caso de uso do diagrama é diferente, "Selecionar responder na mensagem desejada", o que dificulta a rastreabilidade |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Channel", "Edição" devem estar no glossário ou ter um link para o léxico em questão |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Fluxo alternativo está incompleto |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 3 |  9  | 40.00% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 6 |  14 |
| Critério de aceitação: | 30%    |

#### IUC - 19

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC19 - Editar Mensagem](../Modelagem/especificacao.md#ec19)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Channel", "Logar" devem estar no glossário ou ter um link para o léxico em questão |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Fluxo alternativo está incompleto |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 40.00% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 1 |  1  |
|**Total:**|   | 17| 35 | 5 |  14 |
| Critério de aceitação: | 30%    |

#### IUC - 20

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC20 - Realizar video Chat](../Modelagem/especificacao.md#ec20)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | Não consta o caso de uso no diagrama linkado "Realização de Video chat" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não há resposta do sistema em nenhum momento dos fluxos |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | Em alguns momentos não é utilizada a voz ativa, fazendo o uso de ações duvidosas do ator, como "usuário pode fazer algo" |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Grupo", "Desliza tela", "Sala" devem estar no glossário ou ter um link para o léxico em questão |
| 9  | Médio |   |   | x | Alternância entre o termo "grupo", "canal" e "sala", que pode confundir quem ler a documentação |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como "clicam no canal", "clicam na ferramenta" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 40.00% | Reprovado |
|Média     | 2 | 6 | 12 | 3 |  6  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 7 |  14 |
| Critério de aceitação: | 30%    |

#### IUC - 21

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC21 - Cadastrar novo usuário](../Modelagem/especificacao.md#ec21)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | O caso de uso no diagrama "Cadastrar novo usuário" está com outro nome, "cadastro por formulário" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não há resposta do sistema em nenhum momento dos fluxos |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | Em alguns momentos não é utilizada a voz ativa, fazendo o uso de ações duvidosas do ator, como "usuário pode fazer algo" |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Termos, como "Formulário" devem estar no glossário ou ter um link para o léxico em questão |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 34.29% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 6 |  12 |
| Critério de aceitação: | 30%    |

#### IUC - 22

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC22 - Deixar Grupo](../Modelagem/especificacao.md#ec22)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | Não consta o caso de uso no diagrama "Sair de um channel" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | Em alguns momentos não é utilizada a voz ativa, fazendo o uso de ações duvidosas do ator, como "usuário pode fazer algo" |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos precisam estar no glossário ou linkados dos léxicos |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como "Usuário clica em" |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  | x |   |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 2 |  6  | 34.29% | Reprovado |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 6 |  12 |
| Critério de aceitação: | 30%    |

#### IUC - 23

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC22 - Esconder Grupo](../Modelagem/especificacao.md#ec23)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   | O caso de uso consta no diagrama, porém estar com uma frase, "Escolher entre as opções marcadas a de "Esconder grupo"" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | As frases no fluxo principal não especificam o ator que usa o sistema e não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   |   | x | Em alguns momentos não é utilizada a voz ativa, fazendo o uso de ações duvidosas do ator, como "usuário pode fazer algo" |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos precisam estar no glossário ou linkados dos léxicos |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   |   | x | Utilizado termos que indicam a interface, como "Clicar nos três pontos..." |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  | x |   |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 25.71% | Aprovado  |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 2 |  2  |
|**Total:**|   | 17| 35 | 5 |  9 |
| Critério de aceitação: | 30%    |

#### IUC - 24

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC24 - Receber Notificação](../Modelagem/especificacao.md#ec24)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   | x |   |          |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   |   | x | Não há resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos, como "Video Chat", "grupo",  precisam estar no glossário ou linkados dos léxicos |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   | x |   |          |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   | x |   |          |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   |   | x | Fluxo de exceção não especifica como o sistema deve proceder internamente e as medidas tomadas para orientar o usuário sobre a exceção |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 1 |  3  | 20.00% | Aprovado  |
|Média     | 2 | 6 | 12 | 2 |  4  |
|Baixa     | 1 | 5 | 5  | 0 |  0  |
|**Total:**|   | 17| 35 | 3 |  7  |
| Critério de aceitação: | 30%    |

#### IUC - 25

|Nome do Caso de Uso|Data da inspeção|Responsável pela inspeção|
|-------------------|----------------|-------------------------|
|[EC25 - Sair do aplicativo](../Modelagem/especificacao.md#ec25)|08/06/2019|Lucas Maciel|

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Alto  |   |   | x | Caso de uso não consta especificamente no diagrama, o mais próximo seria, "Selecionar a opção sair" |
| 2  | Alto  |   | x |   |          |
| 3  | Baixo |   | x |   |          |
| 4  | Médio |   | x |   | Finalmente outra especificação que possui resposta do sistema |
| 5  | Baixo |   | x |   |          |
| 6  | Baixo |   | x |   |          |
| 7  | Médio |   | x |   |          |
| 8  | Alto  |   |   | x | Alguns termos, como "chats", "página inicial",  precisam estar no glossário ou linkados dos léxicos |
| 9  | Médio |   | x |   |          |
| 10 | Baixo |   | x |   |          |
| 11 | Médio |   | x |   |          |
| 12 | Médio |   | x |   |          |
| 13 | Baixo |   | x |   |          |
| 14 | Alto  |   | x |   |          |
| 15 | Alto  |   |   | x | Fluxo alternativo não faz parte do caso de uso |
| 16 | Alto  |   | x |   |          |
| 17 | Médio |   | x |   | Finalmente outra especificação com exceção correta. Poderia ter outras exceções para complementar |

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|---|----|---|-----|--------|-----------|
|Alta      | 3 | 6 | 18 | 3 |  9  | 25.71% | Aprovado  |
|Média     | 2 | 6 | 12 | 0 |  0  |
|Baixa     | 1 | 5 | 5  | 0 |  0  |
|**Total:**|   | 17| 35 | 3 |  9  |
| Critério de aceitação: | 30%    |

## Referências

[1] - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acesso em: 05 jun. 2019.

[2] - IBM. Use-case. Disponível em: https://www.ibm.com/developerworks/rational/library/content/RationalEdge/may02/m_chapter4_jr.pdf. Acesso em: 05 jun. 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|  --- | ------ | ----------- | ----- |
| 05/06/2019 | 1.0 | Abertura do documento | André Lucas |
| 05/06/2019 | 1.1 | Inclusão da metodologia, checklist e medição utilizadas | André Lucas |
| 06/06/2019 | 1.2 | Adição das IUC01 e IUC02 | André Lucas |
| 06/06/2019 | 1.3 | Adição das IUC03 e IUC04 | André Lucas |
| 07/06/2019 | 1.4 | Adição das IUC05 - IUC11 | Lucas Maciel |
| 08/06/2019 | 1.5 | Adição das IUC12 - IUC15 | Lucas Maciel |
| 08/06/2019 | 1.5 | Adição das IUC16 - IUC20 | Lucas Maciel |
| 08/06/2019 | 1.6 | Adição das IUC21 - IUC25 | Lucas Maciel |
| 10/06/2019 | 1.7 | Adição da ICU13 - v2 | André Lucas |
