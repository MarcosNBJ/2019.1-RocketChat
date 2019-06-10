# Inspeção NFR

## Introdução

Aqui buscamos realizar a verificação dos artefatos da modelagem por NFR. Em busca de aferir quais artefatos feitos possuem a qualidade necessária e quais precisam ser revisados. Sendo que essa qualidade foi julgada de acordo com as definições do _NFR Framework_


## Metodologia da inspeção

Para inspecionar cada artefato foi construída uma checklist, que busca verificar se o artefato atende a alguns critérios de qualidade considerados importantes para a produção do mesmo com um bom grau de confiabilidade. Com isso, é avaliado para cada artefato quantos critérios o mesmo atende e quantos não, ao fim aprovando ou reprovando o mesmo a depender desse resultado, sendo que alguns critérios tem peso diferente de outros, como será melhor explicado em um tópico seguinte. Além disso, são sugeridas melhorias para os critérios que tiverem falhado em ser atendidos.

### Critérios
Os critérios foram divididos em dois grupos: 

* Do artefato modelo: referentes ao NFR puro, sem a análise da propagação dos impactos por algum caminho específico.
* Do artefato de análise: referentes ao artefato com análise da propagação dos impactos e cumprimento dos softgoals com algum caminho definido.

Esses critérios apresentam três níveis de cumprimento: Não cumprimento, cumprimento parcial e satisfação total. Além disso, para cada critério foi adotado também um nível de importância, que varia entre baixo, médio e alto, definindo o quão importante é o cumprimento do mesmo para a boa qualidade do artefato. A seguir podem ser vistos os críeterios definidos e seus devidos niveis de importância:   


#### Checklist-V01

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

#### Checklist-V02

Nessa versão, foi adicionada uma tabela extra para a checklist, que contem critérios acerca da rastreabilidade do artefato, para que dessa forma fosse também possível avalia-lo na qualidade de artefat de requisitos.

|Nº|**Pré-rastreabilidade**||
|:--:|:--:|:--:|
|16|Existe rastro no artefato ?|Alto|
|17|O artefato possuí versionamento ?|Alto|


### Critério avaliativo

#### CA-V1

Para avaliar se um artefato deve ser aprovado ou reprovado está sendo seguida a metodologia proposta em [1](#referencias). Que sugere uma tolerância entre 30% e 40% para defeitos no artefato, sendo que essa porcentagem é feita em cima de uma pontuação obtida pelo artefato, que é calculada de acordo com os critérios por ele atendidos e não atendidos, levando em conta os diferentes pesos. No nosso caso, o range de pontuação é definido da seguinte forma:

|Importância do critério|Peso atribuido|Quantidade|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
|Alta|3|10|30|
|Média|2|3|6|
|Baixa|1|4|4|
|**Total:**||17|40|


E a tolerância máxima escolhida foi de 30%. Sendo assim, os artefatos que pontuarem abaixo do total de 28 pontos serão reprovados. Sendo aprovados apenas aqueles cuja quantidade de defeitos seja igual ou inferior ao correspondente a 12 pontos.

#### CA-V2

Na segunda versão do método avaliativo, além da pontuação, existe também um veredito final dado pelo inspetor. Este segue a seguinte escala: 

_Péssimo < Muito ruim < Ruim < Regular < Bom < Muito bom < Ótimo_

Essa parte da avaliação permite uma nota mais subjetiva que poderá ser dada ao artefato e fomentar a diferenciação de qualidade entre artefatos de pontuação similar. Além de demonstrar mais a opinião do avaliador acerca do artefato.


### Fase de preparação
Aqui estão definidos alguns esclarescimentos acordados acerca do objetivo de alguns critérios específicos da checklist, cujo valor é mais subjetivo.

|ID do critério|Definição|
|:--:|:--:| 
|4|O critério é satisfeito caso para todo nome atribuido a um softgoal/operacionalização seja possível entender perfeitamente o que ele significa.|
|5|Normalmente considera-se 3 níveis como um bom exemplo de maturidade, porém, varia de caso para caso. O critério é satisfeito caso as operacionalizações se iniciem apenas após os softgoals serem explorados extensivamente, quebrando-se em outros softgoals menores.|


### Inspeção

A seguir podem ser vistas as inspeções individuais de cada NFR previamente construído.

#### INFR-01
 
_Inspeção do [NFR-01](../Modelagem/nfr.md#nfr1-portabilidade) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|2|4|
|Baixo|2|2|
|**Total**|4|6|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|2|4|
|Baixo|2|2|
|**Total**|5|9|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||
||**Veredito do inspetor**||
||Bom||


#### INFR-02
 
_Inspeção do [NFR-02](../Modelagem/nfr.md#nfr2-performance-do-chat) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|0|0|
|Baixo|1|1|
|**Total**|2|4|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||
||**Veredito do inspetor**||
||Muito Bom||

#### INFR-03
 
_Inspeção do [NFR-03](../Modelagem/nfr.md#nfr3-suporte) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|3|6|
|Baixo|2|2|
|**Total**|5|8|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|3|6|
|Baixo|2|2|
|**Total**|6|11|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||
||**Veredito do inspetor**||
||Regular||

#### INFR-04
 
_Inspeção do [NFR-04](../Modelagem/nfr.md#nfr4-usabilidade) por Marcos Nery_

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

||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|3|6|
|Baixo|1|1|
|**Total**|4|7|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||

||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|3|6|
|Baixo|1|1|
|**Total**|5|10|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||
||**Veredito do inspetor**||
||Regular||

#### INFR-05
 
_Inspeção do [NFR-05](../Modelagem/nfr.md#nfr5-personabilidade) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|1|2|
|Baixo|2|2|
|**Total**|3|4|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Algumas melhorias são necessárias||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|1|2|
|Baixo|2|2|
|**Total**|4|7|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Algumas melhorias são necessárias||
||**Veredito do inspetor**||
||Bom||

#### INFR-06
 
_Inspeção do [NFR-06](../Modelagem/nfr.md#nfr6-seguranca) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|0|0|
|Baixo|1|1|
|**Total**|2|4|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||
||**Veredito do inspetor**||
||Muito Bom||

#### INFR-07
 
_Inspeção do [NFR-07](../Modelagem/nfr.md#nfr07-manutenabilidade) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|2|6|
|Médio|1|2|
|Baixo|4|4|
|**Total**|7|12|
||**Conclusão**||
||Artefato reprovado, pois a pontuação dos defeitos superam a tolerância máxima. Muitas melhorias podem ser feitas||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|3|9|
|Médio|1|2|
|Baixo|4|4|
|**Total**|8|15|
||**Conclusão**||
||Artefato reprovado, pois a pontuação dos defeitos superam a tolerância máxima. Muitas melhorias precisam ser feitas||
||**Veredito do inspetor**||
||Ruim||


#### INFR-08
 
_Inspeção do [NFR-08](../Modelagem/nfr.md#nfr08-contribuicao-da-comunidade) por Marcos Nery_

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


||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Artefato aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias||
||**Veredito do inspetor**||
||Bom||

#### INFR-09
 
_Inspeção do [NFR-09](../Modelagem/nfr.md#nfr09-conectividade) por Marcos Nery_

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

||**Resultados V01**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|2|4|
|Baixo|3|3|
|**Total**|6|10|
||**Conclusão**||
||Existe uma substancial quantidade de melhorias que podem ser realizadas. No entanto, o artefato foi aprovado, pois a quantidade de defeitos foi inferior a tolerância máxima||


||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|2|6|
|Médio|2|4|
|Baixo|3|3|
|**Total**|7|13|
||**Conclusão**||
||Artefato reprovado, pois a pontuação dos defeitos superam a tolerância máxima. Muitas melhorias precisam ser feitas||
||**Veredito do inspetor**||
||Ruim||


#### INFR-09 V2

Para este artefato, houve uma discordância entre duas pessoas que realizaram a inspeção, por conta disso. Essa é uma segunda inspeção, do mesmo artefato, feita por outro avaliador.


_Inspeção do [NFR-09](../Modelagem/nfr.md#nfr09-conectividade) por André Lucas_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Sim|Alguns softgoals poderiam estar mais bem definidos|
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Sim||
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

||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|1|3|
|Médio|1|2|
|Baixo|3|3|
|**Total**|5|8|
||**Conclusão**||
||Artefato aprovado, pos a quantidade de defeitos foi inferior a tolerância máxima, embora hajam muitas melhorias a serem feitas.||
||**Veredito do inspetor**||
||Regular||


#### INFR-09 V3

Como para este artefato houveram duas inspeções com resultados diferentes, foi realizada uma terceira versão, que representa o consenso ao qual os dois avaliadores chegaram. A discussão entre os dois avaliadores para chegar ao consenso foi gravada e pode ser conferida a partir do [link](https://drive.google.com/drive/u/0/folders/18UPonJuOZrWZdTYW7UiKlUXVuvkiyPYo).


_Inspeção do [NFR-09](../Modelagem/nfr.md#nfr09-conectividade) por Marcos Nery e André Lucas_

|Nº|Critério|Check|Observação/Melhoria| 
|:--:|:--:|:--:|:--:|
||**Artefato modelo**|||
|1|O foco do modelo é avaliar a satisfação de uma meta flexível ?|Sim||
|2|As operacionalizações estão representadas majoritariamente por meio de verbos ?|Não|Verbalizar as operacionalizações|
|3|Todos os softgoals constituem critérios de qualidade / Requisitos Não Funcionais ?|Não|Muitos softgoals tem mais cara de operacionalização|
|4|Estão claros os conceitos ou tarefas representados pelos nomes escolhidos para cada softgoal ou operacionalização ?|Sim||
|5|Antes do inicio das  operacionalizações, existe maturidade suficiente nos softgoals (normalmente com no mínimo 3 níveis) ?|Não|Como os softgoals tem mais cara de operacionalização, não há maturidade suficiente nessa parte.|
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

||**Resultados V02**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alta|2|6|
|Médio|2|4|
|Baixo|3|3|
|**Total**|7|13|
||**Conclusão**||
||Artefato reprovado, pos a quantidade de defeitos foi superior a tolerância máxima, existem muitas melhorias a serem feitas.||
||**Veredito do inspetor**||
||Ruim||


## Resultados


### RV1
Resultados com a primeira versão da checklist

* Modelos analisados: 9
* Modelos reprovados: 1
* Média de pontuação dos defeitos: 5.7, ou cerca de 17%. De forma geral abaixo da tolerância máxima, que foi admitida como sendo de 30%. 

### RV2
Resultados com a segunda versão da checklist. Com a adição dos critérios de rastreio e versionamento, é possível ver que a porcentagem de defeitos aumentou, o que revela um problema significativo nos artefatos análisados que anteriormente não estava sendo observado.
 
* Modelos analisados: 9
* Modelos reprovados: 2
* Média de pontuação dos defeitos: 8.4, ou cerca de 21%. De forma geral abaixo da tolerância máxima, que foi admitida como sendo de 30%. 

Dessa forma, a conclusão da análise é que a maioria dos NFRs atingiu o padrão mínimo de qualidade, embora todos eles possam melhorar em alguns pontos e alguns precisem de refatoração. Além disso, abaixo pode ser vista uma lista que conta quantas vezes cada erro foi cometido. Para que seja possível concluír os principais pontos a se melhorar.

|ID do critério|Quantidade de defeitos|
|:--:|:--:|
|1|0|
|2|4|
|3|2|
|4|0|
|5|6|
|6|4|
|7|0|
|8|0|
|9|0|
|10|2|
|11|2|
|12|0|
|13|1|
|14|10|
|15|2|
|16|8|
|17|0|  

Como pode ser visto, o principal problema encontrado é a váriabilidade de caminhos análisados no artefato de análise do NFR. Logo após, vem um problema de maior importância, que é a falta de rastro no artefato, algo que precisa ser melhorado em quase todos os NFR análisados. Por fim, um outro erro cuja recorrência foi significativa, foi o erro referente a falta de maturidade na hora de começar as operacionalizações. 


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
| 05/05/2019 | 1.9 | Adição da pré-rastreabilidade | Marcos Nery |
| 05/05/2019 | 2.0 | Adição do versionamento da checklist | Marcos Nery |
| 05/05/2019 | 2.1 | Adição do check de pré-rastreabilidade para cada inspeção | Marcos Nery |
| 05/05/2019 | 2.2 | Adição do veredito do inspetor para cacda inspeção | Marcos Nery |
| 05/05/2019 | 2.3 | Adição da fase de preparação | Marcos Nery |
| 05/05/2019 | 2.4 | Adição da segunda análise do NFR09 | André Lucas |
| 05/05/2019 | 2.5 | Adição do consenço para a INFR09 | André Lucas e Marcos Nery|
| 05/05/2019 | 2.6 | Refatoração dos resultados | Marcos Nery|
