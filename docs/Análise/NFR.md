# Inspeção NFR

## Introdução

Aqui buscamos realizar a verificação dos artefatos da modelagem por NFR. Em busca de aferir quais artefatos feitos possuem a qualidade necessária e quais precisam ser revisados. Sendo que essa qualidade foi julgada de acordo com as definições do _NFR Framework_


## Metodologia da inspeção

Para inspecionar cada artefato foi construída uma checklist, que busca verificar se o artefato atende a alguns critérios de qualidade considerados importantes para a produção do mesmo com um bom grau de confiabilidade. Com isso, é avaliado para cada artefato quantos critérios o mesmo atende e quantos não, ao fim aprovando ou reprovando o mesmo a depender desse resultado, sendo que alguns critérios tem peso diferente de outros, como será melhor explicado em um tópico seguinte. Além disso, são sugeridas melhorias para os critérios que tiverem falhado em ser atendidos.

### Critérios
Os critérios foram divididos em dois grupos: 

* Do artefato modelo: referentes ao NFR puro, sem a análise da propagação dos impactos por algum caminho específico.
* Do artefato de análise: referentes ao artefato com análise da propagação dos impactos e cumprimento dos softgoals com algum caminho definido.

Além disso, para cada critério foi adotado também um nível de importância, que varia entre baixo, médio e alto, definindo o quão importante é o cumprimento do mesmo para a boa qualidade do artefato. A seguir podem ser vistos os críeterios definidos e seus devidos niveis de importância:   

|Nº|Critério|Importância|
|:--:|:--:|:--:|
||**Artefato modelo**||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Alto|
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Médio|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Alto|
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Alto|
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Médio|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Baixo|
|7|A simbologia está corretamente implementada ?|Alto|
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Alto|
|9|Existe propagação de impacto para  toda operacionalização ?|Alto|
|10|Existe propagação de impacto entre branches diferentes do NFR ? |Baixo|
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Médio|
||**Artefato de análise**||
|12|A simbologia das labels está corretamente representada ?|Alto|
|13|O resultado da propagação dos impactos está correto ?|Alto|
|14|Existe a variabilidade de caminhos tomados ?|Baixo|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Baixo|
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Alto|
|17|O artefato possuí versionamento ?|Alto|


### Critério avaliativo
Para avaliar se um artefato deve ser aprovado ou reprovado está sendo seguida a metodologia proposta em [1](#referencias). Que sugere uma tolerância entre 30% e 40% para defeitos no artefato, sendo que essa porcentagem é feita em cima de uma pontuação obtida pelo artefato, que é calculada de acordo com os critérios por ele atendidos e não atendidos, levando em conta os diferentes pesos. No nosso caso, o range de pontuação é definido da seguinte forma:

|Importância do critério|Peso atribuido|Quantidade|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
|Alta|3|8|24|
|Média|2|3|6|
|Baixa|1|4|4|
|**Total:**||15|34|



E a tolerância máxima escolhida foi de 30%. Sendo assim, os artefatos que pontuarem abaixo do total de 23.8 pontos serão reprovados. Sendo aprovados apenas aqueles cuja quantidade de defeitos seja igual ou inferior ao correspondente a 10.2 pontos.

### Inspeção

A seguir podem ser vistas as inspeções individuais de cada NFR previamente construído.

#### INFR-0X
 
_Inspeção do [NFRX](../Modelagem/nfr.md#)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|||
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|||
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|||
|7| A simbologia está corretamente implementada ?|||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|||
|9|Existe propagação de impacto para  toda operacionalização ?|||
|10|Existe propagação de impacto entre branches diferentes do NFR ? |||
 |11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|||
|13|O resultado da propagação dos impactos está correto ?|||
|14|Existe a variabilidade de caminhos tomados ?|||
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|||


||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|||
|Médio|||
|Baixo|||
|**Total**|||
||**Conclusão**||
||||

#### INFR-01
 
_Inspeção do [NFR-01](../Modelagem/nfr.md#nfr1-portabilidade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Não||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||


||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|2|4|
|Baixo|2|2|
|**Total**|4|6|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


#### INFR-02
 
_Inspeção do [NFR-02](../Modelagem/nfr.md#nfr2-performance-do-chat)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Sim||
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Sim||
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Sim||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||

#### INFR-03
 
_Inspeção do [NFR-03](../Modelagem/nfr.md#nfr3-suporte)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Sim||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Não|Onde cabivel, representar os impactos que uma operacionalização ou softgoal de uma determinada branch podem ter em outros softgoals|
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Não|Modelar mais possibilidades|
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|3|6|
|Baixo|2|2|
|**Total**|5|8|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||

#### INFR-04
 
_Inspeção do [NFR-04](../Modelagem/nfr.md#nfr4-usabilidade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Sim||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Não|Modelar mais possibilidades|
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|3|6|
|Baixo|1|1|
|**Total**|4|7|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


#### INFR-05
 
_Inspeção do [NFR-05](../Modelagem/nfr.md#nfr5-personabilidade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Sim||
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Não||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|1|2|
|Baixo|2|2|
|**Total**|3|4|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Algumas melhorias são necessárias||


#### INFR-06
 
_Inspeção do [NFR-06](../Modelagem/nfr.md#nfr6-seguranca)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Sim||
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Sim||
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Sim||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||


#### INFR-07
 
_Inspeção do [NFR-07](../Modelagem/nfr.md#nfr07-manutenabilidade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Não|Alguns softgoals tem mais cara de operacionalização. Refinar os softgoals para dar a ideia de critério de qualidade|
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Sim||
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Não||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Não||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Não|Algumas labels resultantes de propagação de impacto estão faltando|
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Não| Levar a análise para todos os níveis incluindo o último, para demonstrar se o softgoal tema do NFR foi cumprido ou não.|
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|2|6|
|Médio|1|2|
|Baixo|4|4|
|**Total**|7|12|
||**Conclusão**||
||Artefato reprovado, pois a pontuação dos defeitos superam a tolerância máxima. Muitas melhorias podem ser feitas||



#### INFR-08
 
_Inspeção do [NFR-08](../Modelagem/nfr.md#nfr08-contribuicao-da-comunidade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Sim||
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim||
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Sim||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Sim||
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Sim||
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||


#### INFR-09
 
_Inspeção do [NFR-09](../Modelagem/nfr.md#nfr09-conectividade)_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Não|Alguns softgoals tem mais cara de operacionalização. Refinar os softgoals para dar a ideia de critério de qualidade|
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Construir mais maturidade nos softgoals antes de operacionalizar|
|6|Estão sendo utilizados claims para melhorar a clareza do modelo ?|Não||
|7| A simbologia está corretamente implementada ?|Sim||
|8|Os relacionamentos, por meio de ANDs e ORs, estão corretamente representados ?|Sim||
|9|Existe propagação de impacto para  toda operacionalização ?|Sim||
|10|Existe propagação de impacto entre branches diferentes do NFR onde cabivel ? |Sim||
|11|Existe variabilidade de caminhos possíveis para atingir o softgoal ?|Sim||
||**Artefato de análise**|||
|12|A simbologia das labels está corretamente representada ?|Sim||
|13|O resultado da propagação dos impactos está correto ?|Sim||
|14|Existe a variabilidade de caminhos tomados ?|Não|Modelar análises que seguem alternativas diferentes de caminhos a seguir|
|15| A análise vai até o último nível para demonstrar se o softgoal é de fato atendido ?|Não| Levar a análise para todos os níveis incluindo o último, para demonstrar se o softgoal tema do NFR foi cumprido ou não.|
||**Pré-rastreabilidade**||
|16|Existe rastro no artefato ?|Não|Adicionar rastro para mostrar o que justifica o colocado no NFR|
|17|O artefato possuí versionamento ?|Sim||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|2|4|
|Baixo|3|3|
|**Total**|6|10|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


## Resultados

* Modelos analisados: 9
* Modelos reprovados: 1
* Média de pontuação dos defeitos: 5.7, ou cerca de 17%. De forma geral abaixo da tolerância máxima, que foi admitida como sendo de 30%. 

Dessa forma, a conclusão da análise é que a maioria dos NFRs atingiu o padrão mínimo de qualidade, embora todos eles possam melhorar em alguns pontos e alguns precisem de refatoração.   



## Referências

1 - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acessado em: 05, jun, 2019.

2 - COUTO, Anselmo; MARTINS, Luiz Eduardo. (2009). Um Processo de Validação de Requisitos Não-Funcionais Baseado no NFR-Framework. Disponível em: https://www.researchgate.net/publication/221235239_Um_Processo_de_Validacao_de_Requisitos_Nao-Funcionais_Baseado_no_NFR-Framework. Acessado em: 05, jun, 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 04/05/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 05/05/2019 | 1.1 | Inclusão da introdução e metodologia utilizada | Marcos Nery |
| 05/05/2019 | 1.2 | Inclusão da inspeção INFR-01 | Marcos Nery |
| 05/05/2019 | 1.3 | Inclusão da inspeção INFR-02 e INFR-03| Marcos Nery |
| 05/05/2019 | 1.4 | Inclusão da inspeção INFR-04 e INFR-05| Marcos Nery |
| 05/05/2019 | 1.5 | Inclusão da inspeção INFR-06 e atualização dos demais| Marcos Nery |
| 05/05/2019 | 1.6 | Inclusão da inspeção INFR-07 | Marcos Nery |
| 05/05/2019 | 1.7 | Inclusão da inspeção INFR-08 e INFR-09 | Marcos Nery |
| 05/05/2019 | 1.8 | Adição dos resultados | Marcos Nery |
