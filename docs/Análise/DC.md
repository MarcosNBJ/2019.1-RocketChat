# Inspeção de Diagramas de caso de Uso

## Introdução

Este documento tem como finalidade apresentar a inspeção de alguns diagramas de casos de uso, que é uma das técnicas utilizadas no módulo anterior de Modelagem de requisitos.

## Objetivo

O objetivo é observar vários aspectos do documento e realizar a análise da qualidade. A partir dos dados da análise descobrir as falhas existentes, facilitando assim a melhoria.

## Metodologia

Para a inspeção dos diagramas de casos de uso foi estabelecido um checklist, com questões e critérios a serem avaliados, que busca localizar defeitos no modelo. É sugerida uma classificação para cada artefato, categorizados em alto, médio e baixo, confome a avaliação.
Critérios de alto impacto, são defeitos que afetam a compreensão, a falta de coerência e a falta de definição. Critérios de impacto médio, são defeitos que afetam a qualidade do caso de uso de forma considerável, abaixo do impacto alto. Critérios de baixo impacto são defeitos que se corrigidos aumentariam a qualidade do caso de uso, mas que não impedem a compreensão.
A fim de registrar os defeitos com os checklists para que sirvam como base para a medição da inspeção, os seguintes artefatos são propostos:

### Checklist

|Nº|Critério|Impacto|
|:--:|:--:|:--:|
| 1  | O nome do ator reflete o seu papel no sistema, evitando títulos de cargos, nomes de áreas ou atividades relacionadas com a estrutura da organização? | Médio |
| 2  | O nome do caso de uso utiliza verbo seguido de substantivo(s), podendo o substantivo ter adjetivo, e o verbo se encontra no modo infinitivo ou no modo indicativo em tempo presente, e utiliza a voz ativa ao invés da passiva? (Ex: “Imprimir atestado” ou “Imprime atestado” e não “Impressão de atestado” ou “Atestado impresso”) | Médio |
| 3  | O nome do caso de uso é de fácil compreensão e evita a utilização de verbos ou substantivos específicos de sistemas, de forma a tornar difícil a compreensão para o leitor, clientes e usuários?  | Médio |
| 4  | O nome do caso de uso reflete funções de forma agrupada com um resultado de valor para o usuário, sem derivar-se em múltiplos casos de uso que poderiam ser agrupados?  | Alto |
| 5  | Os casos de uso evitam a utilização de especificação de múltiplos relatórios ou CRUD (Create, Retrieve, Update, Delete ou Criar,Consultar com finalidade de cadastro,Atualizar, Deletar), havendo no máximo um caso de uso genérico para todos os cadastros? (Ex: “Gerenciar Cadastros”, “Visualizar Relatórios”) (Considerar 1 erro para cada caso de uso de cadastro para o mesmo ator e subtrair 1 da Qtde no Registro de Inspeção).  | Baixo |
| 6  |  Cada ator tem relacionamento com ao menos um caso de uso e é representado por uma linha sólida, podendo ou não ser seguida de uma flecha aberta indicando a direção da invocação inicial do relacionamento?  | Alto |
| 7  | Se houver relacionamentos entre casos de uso e casos de uso, são um entre estes: <br>Relacionamento de Inclusão: Representado por uma linha hifenizada, seguida de flecha aberta apontando para o caso de uso incluído, sendo este o oposto do caso de uso base, com estereótipo que indique a inclusão << include >>?<br> Relacionamento de Extensão: Representado por uma linha hifenizada, seguida de uma flecha aberta apontando para o caso de uso base, seguida de estereótipo que indique a extensão  << extend >>?<br> Relacionamento de Generalização: Representado por uma linha sólida, seguida de uma flecha fechada, sendo na origem o caso de uso especializado e no destino o caso de uso genérico?  | Alto |
| 8  | Se houver relacionamentos entre os casos de uso e se removidos todos os relacionamentos entre eles, isto é, os casos de uso incluídos, os de extensão e os de generalização, o propósito do modelo de caso de uso continua claro no diagrama?  | Alto |
| 9  | Cada caso de uso tem relacionamento com ao menos um ator (excetuando-se casos de uso incluídos, de extensão de generalização) e é representado por uma linha sólida, podendo ou não ser seguida de uma flecha aberta indicando a direção da invocação inicial do relacionamento?  | Alto |
| 10 | Se houver caso de uso incluído, ele utilizado para dividir suas funcionalidades, portanto tem relacionamento de inclusão com mais de um caso de uso?| Alto |
| 11 | Se houver caso de uso de extensão, ele é utilizado sob as seguintes situações: funcionalidades adicionadas a um produto existente, funcionalidades que podem ser compradas separadamente, descrições | Alto |
| 12 | Se houver caso de uso especializado, advindo de um relacionamento de generalização, ele é utilizado para representar o reuso de um caso de uso em famílias de sistemas com funcionalidades variáveis?  | Alto |
| 13 | Se houver relacionamento entre atores e atores, ele é de generalização, representado por uma linha sólida seguida de uma flecha fechada, sendo na origem o ator especializado e no destino o ator generalizado?  | Alto |
| 14 | Se houver relacionamento entre os atores e atores, ele é utilizado apenas para representar que o ator especializado tem características comuns ao ator generalizado, mas também acessa casos de uso adicionais, evitando representar hierarquias como as de permissão de segurança ou hierarquias funcionais na organização? | Alto |
| 15 | Há presença de breve descrição de atores, que especifica de forma clara o que eles representam?  | Baixo |
| 16 | .Há presença de breve descrição de casos de uso, que especifica de forma clara o seu propósito?  | Baixo |


### Registro de inspeção de Diagrama de Caso de Uso

As colunas 3, 4, 5 são registros de não-conformidades referem-se ao registro da aplicação de cada questão, onde N/A (não se aplica) indica que a questão não se aplica ao produto inspecionado, S (sim) indica que o produto inspecionado atende à questão e N (não) indica que o produto não atende à questão e que representa um defeito.
Para o registro de inspeção deve seguir a seguinte tabelas:

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|||||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   |   |   |          |
| 2  | Médio  |   |   |   |          |
| 3  | Médio |   |   |   |          |
| 4  | Alto |   |   |   |          |
| 5  | Baixo |   |   |   |          |
| 6  | Alto |   |   |   |          |
| 7  | Alto |   |   |   |          |
| 8  | Alto  |   |   |   |          |
| 9  | Alto |   |   |   |          |
| 10 | Alto |   |   |   |          |
| 11 | Alto |   |   |   |          |
| 12 | Alto |   |   |   |          |
| 13 | Alto |   |   |   |          |
| 14 | Alto  |   |   |   |          |
| 15 | Baixo  |   |   |   |          |
| 16 | Baixo  |   |   |   |          ||

### Medição da inspeção

O critério de aceitação se refere a um percentual máximo de defeitos que o artefato inspecionado pode ter. Se esse resultado ultrapassar o critério de aceitação, será reprovado. Acredita-se que um percentual razoável esteja entre 30% a 40%. Neste trabalho é proposto um percentual de 30%, o que significa que os casos de usos inspecionados deveram ter no máximo 30% de defeitos para serem aprovados.
A metodologia e as métricas utilizadas para melhor inspeção dos casos de usos, assim como as tabelas e diagramas, foram inspirados a partir do estudo proposto em [(1)](#referencias).

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 |   |    |        |Aprovado ou Reprovado |
|Média     | 2 | 3  | 6 |   |    |        |   |  
|Baixa     | 1 | 3 | 3  |   |    |        |   |
|**Total:**|   | 16 | 39 |   |    |        |   |
|Critério de aceitação:|30%|

### Inspeção

A seguir podem ser vistas as inspeções individuais de diagrama de cada caso de uso previamente construído.

#### IDCU - 01

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU1 - Realização de video chat - v2](../Modelagem/diagramas.md#dcu1)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |          |
| 2  | Médio  |   |   | x  |          |
| 3  | Médio |   |   |  x | A escolha do nome vídeo chat, ao invés de video conferencia e afins pode vir a causar uma confusão para o usuário devido ao seu uso incomum|
| 4  | Alto |   |  x |   |          |
| 5  | Baixo |   |  x |   |          |
| 6  | Alto |   |  x |   |          |
| 7  | Alto |  x |   |   |          |
| 8  | Alto  |  x|   |   |          |
| 9  | Alto |   |  x |   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto |   |   |  x |   Uso raso da descrição por extends inviabiliza a conformidade da função       |
| 12 | Alto |  x |   |   |          |
| 13 | Alto |  x |   |   |          |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   | x  |  |          |
| 16 | Baixo  |   | x  |   |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 |  1 | 3   |    17.9%    |Aprovado |
|Média     | 2 | 3  | 6 |   2|  4  |        |   |  
|Baixa     | 1 | 3 | 3  |  0 |    0|        |   |
|**Total:**|   | 16 | 39 | 4  |   7 |        |   |
|Critério de aceitação:|30%|

#### IDCU - 02

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU2 - Enviar mensagem - v3](../Modelagem/diagramas.md#dcu2)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |          |
| 2  | Médio  |   | x  |   |          |
| 3  | Médio |   | x  |   |          |
| 4  | Alto |   |  x |   |          |
| 5  | Baixo |   |   |  x |  O diagrama descreve o a ação de visualizar e de enviar mensagem, portanto, descrevendo diferentes relatórios|
| 6  | Alto |   | x  |   |          |
| 7  | Alto |  x |   |   |          |
| 8  | Alto  |  x |  |   |          |
| 9  | Alto |   |  x |   |          |
| 10 | Alto | x  |   |   |          |
| 11 | Alto |  x |   |   |          |
| 12 | Alto |   |   x|   |          |
| 13 | Alto |  x |   |   |          |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   |   |x   |          |
| 16 | Baixo  |   |   | x  |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 | 0  |  0  |    7.8%    |Aprovado |
|Média     | 2 | 3  | 6 | 0  |   0 |        |   |  
|Baixa     | 1 | 3 | 3  |  3 |  3  |        |   |
|**Total:**|   | 16 | 39 |  3 |  3  |        |   |
|Critério de aceitação:|30%|

#### IDCU - 03

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU3 - Fixar mensagem - v2](../Modelagem/diagramas.md#dcu3)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   |   | x  |    O termo "room" é uma palavra relacionada com a estrutura da organização, inviabilizando o tópico em questão |
| 2  | Médio  |   | x  |   |          |
| 3  | Médio |   | x  |   |          |
| 4  | Alto |   |  x |   |          |
| 5  | Baixo |   | x  |   |          |
| 6  | Alto |   |  x |   |          |
| 7  | Alto |  x |   |   |          |
| 8  | Alto  |  x |   |   |          |
| 9  | Alto |   | x  |   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto |   |  x |   |          |
| 12 | Alto |   | x  |   |          |
| 13 | Alto |   |   |  x |O uso da flecha aberta inviabiliza o caso  |
| 14 | Alto  |   | x  |   |          |
| 15 | Baixo  |   |   |  x |          |
| 16 | Baixo  |   |   |  x |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 | 1  |  3  |    17.9%    |Aprovado |
|Média     | 2 | 3  | 6 | 1  |   2 |        |   |  
|Baixa     | 1 | 3 | 3  |  2 |  2  |        |   |
|**Total:**|   | 16 | 39 |  4 |  7  |        |   |
|Critério de aceitação:|30%|

#### IDCU - 04

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU4 - Alterar status - v1](../Modelagem/diagramas.md#dcu4)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |    |
| 2  | Médio  |   |  x |   |          |
| 3  | Médio |   |  x |   |          |
| 4  | Alto |   |  x |   |          |
| 5  | Baixo |   |x    |   |          |
| 6  | Alto |   |   |   |          |
| 7  | Alto |  x |   |   |          |
| 8  | Alto  | x  |   |   |          |
| 9  | Alto |   | x |   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto |  x |   |   |          |
| 12 | Alto |  x |  |   |          |
| 13 | Alto |  x |   |   | |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   |   |  x|          |
| 16 | Baixo  |   |   |  x |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 |  0 |   0|    5.12%   |Aprovado |
|Média     | 2 | 3  | 6 |0  | 0   |        |   |  
|Baixa     | 1 | 3 | 3  |   2|   2 |        |   |
|**Total:**|   | 16 | 39 | 2 | 2   |        |   |
|Critério de aceitação:|30%|

#### IDCU - 05

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU5 - Deletar Conta - v1](../Modelagem/diagramas.md#dcu5)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |    |
| 2  | Médio  |   |  x |   |          |
| 3  | Médio |   |   x|   |          |
| 4  | Alto |   |  |  x |          |
| 5  | Baixo |   |   |x   |          |
| 6  | Alto |   |   | x  |          |
| 7  | Alto | x  |   |   |          |
| 8  | Alto  | x |   |   |          |
| 9  | Alto |   |  x|   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto | x  |   |   |          |
| 12 | Alto | x  |  |   |          |
| 13 | Alto |   x|   |   | |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   |   | x |          |
| 16 | Baixo  |   |   | x |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 | 0  |0   |     5.12%  |Aprovado |
|Média     | 2 | 3  | 6 | 0 |   0 |        |   |  
|Baixa     | 1 | 3 | 3  | 2  |  2  |        |   |
|**Total:**|   | 16 | 39 |2  |  2  |        |   |
|Critério de aceitação:|30%|

#### IDCU - 06

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU6 - Mensagens Favoritadas - v1](../Modelagem/diagramas.md#dcu6)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |    |
| 2  | Médio  |   |   | x  |          |
| 3  | Médio |   |   x|   |          |
| 4  | Alto |   |  x|   |          |
| 5  | Baixo |   |   x|   |          |
| 6  | Alto |   |   x|   |          |
| 7  | Alto | x  |   |   |          |
| 8  | Alto  | x |   |   |          |
| 9  | Alto |   |  x|   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto | x  |   |   |          |
| 12 | Alto | x  |  |   |          |
| 13 | Alto |   x|   |   | |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   |   | x |          |
| 16 | Baixo  |   |   | x |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 | 0  |0   |     10.2%  |Aprovado |
|Média     | 2 | 3  | 6 | 1 |   2 |        |   |  
|Baixa     | 1 | 3 | 3  | 2  |  2  |        |   |
|**Total:**|   | 16 | 39 |2  |  4  |        |   |
|Critério de aceitação:|30%|


#### IDCU - 07

|Nome do Diagrama de Caso de Uso|Data da inspeção|Responsável pela inspeção|
|:--:|:--:|:--:|
|[DCU7 - Visualizar Membros de Chat em Grupo - v1](../Modelagem/diagramas.md#dcu7)|10/06/2019|Gabriel Davi||

|Nº  |Impacto|N/A|Sim|Não|Observação|
|----|-------|---|---|---|----------|
| 1  | Médio  |   | x  |   |    |
| 2  | Médio  |   |  x |  |          |
| 3  | Médio |   |   | x  |          |
| 4  | Alto |   |  x|   |          |
| 5  | Baixo |   |   x|   |          |
| 6  | Alto |   |   x|   |          |
| 7  | Alto | x  |   |   |          |
| 8  | Alto  | x |   |   |          |
| 9  | Alto |   |  x|   |          |
| 10 | Alto |  x |   |   |          |
| 11 | Alto | x  |   |   |          |
| 12 | Alto | x  |  |   |          |
| 13 | Alto |   x|   |   | |
| 14 | Alto  |  x |   |   |          |
| 15 | Baixo  |   |   | x |          |
| 16 | Baixo  |   |   | x |          ||

|Impacto|Peso|Questões Aplicadas|Peso das questões aplicadas|Não-conformidades encontradas|Peso das não-conformidades encontradas| Resultado quantitativo|Descrição do resultado quantitativo|
|----------|---|----|----|---|----|--------|---|
|Alta      | 3 | 10  | 30 | 0  |0   |     10.2%  |Aprovado |
|Média     | 2 | 3  | 6 | 1 |   2 |        |   |  
|Baixa     | 1 | 3 | 3  | 2  |  2  |        |   |
|**Total:**|   | 16 | 39 |2  |  4  |        |   |
|Critério de aceitação:|30%|
