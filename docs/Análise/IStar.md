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

**Strategic Dependency Model**

|Impacto do critério|Peso atribuído|Quantidade de critérios|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
|Alta | 3 | 3 | 9 |
|Média| 2 | 4 | 8 |
|Baixa| 1 | 1 | 1 |
|**Total:**||9| 18|

Modelo SD será considerado reprovado se  ultrapassar **5,4 pontos** em defeitos.

**Strategic Rationale Model**

|Impacto do critério|Peso atribuído|Quantidade de critérios|Pontuação máxima total|
|:--:|:--:|:--:|:--:|
|Alta | 3 | 3 | 9 |
|Média| 2 | 6 | 12|
|Baixa| 1 | 2 | 2 |
|**Total:**||9| 23|

Modelo SR será considerado reprovado se  ultrapassar **6,9 pontos** em defeitos.

Utilizando como base a tolerância máxima de 30%, temos como resultado que os modelos devem ter uma pontuação de no mínimo 12,6 pontos para o SD e de no mínimo 16,1 para o SR para serem aprovados, com qualquer pontuação menor do que está, o modelo é considerado reprovado e deve ser revisado. Isso não impede, é claro, de que modelos considerados aprovados também possam ser revisados, pois podem existir pequenos erros facilmente reparáveis.

### Inspeção

A seguir podem ser vistas as inspeções individuais de cada Strategic Dependency Model(SD) e de cada Strategic Rationale Model(SR) previamente construído. Todas as inspeções são feitas tomando como base a versão mais atual de cada modelo.

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

#### IISD-01

_Inspeção do [ISD01](../Modelagem/istar.md#isd01-chat)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Não|Corrigir o sentido de algumas dependências|
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 3 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 4 | Os atores estão representados com a abstração correta?  |Não|Sistema de controle de chat pode ser descrito como agente|
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar? |Sim||
| 7 | As metas estão descritas em voz passiva? |Sim||
| 8 | Todos os recursos são substantivos? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISD-02

_Inspeção do [ISD02](../Modelagem/istar.md#isd02-geral)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Sim||
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 3 | Os Softgoals representam requisitos não-funcionais? |-|Este modelo não possui softgoals|
| 4 | Os atores estão representados com a abstração correta?  |Não|O Rocket.Chat pode ser representado como um agente|
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar?|-|Este modelo não possui metas|
| 7 | As metas estão descritas em voz passiva? |-|Este modelo não possui metas|
| 8 | Todos os recursos são substantivos? |-|Este modelo não possui recursos||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISD-03

_Inspeção do [ISD03](../Modelagem/istar.md#isd03-sistema-de-contas)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Sim||
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |-|Este modelo não possui tarefas|
| 3 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 4 | Os atores estão representados com a abstração correta?  |Sim||
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar?|Sim||
| 7 | As metas estão descritas em voz passiva? |Não|Revisar escrita das metas|
| 8 | Todos os recursos são substantivos? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISD-04

_Inspeção do [ISD04](../Modelagem/istar.md#isd04-acoes-sobre-o-channel)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Não|Algumas dependências estão invertidas|
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |-|Este modelo não possui tarefas|
| 3 | Os Softgoals representam requisitos não-funcionais? |Não|Revisar se o softgoal descrito realmente é um softgoal|
| 4 | Os atores estão representados com a abstração correta?  |Sim||
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar? |Sim||
| 7 | As metas estão descritas em voz passiva? |Sim||
| 8 | Todos os recursos são substantivos? |Sim|Corrigir recurso duplicado||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|1|3|
|Médio|1|2|
|Baixo|0|0|
|**Total**|2|5|
||**Conclusão**||
||Várias melhorias são necessárias e devem ser aplicadas a este modelo, no entanto, o modelo foi aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida.|||

#### IISD-05

_Inspeção do [ISD05](../Modelagem/istar.md#isd05-contribuicao-da-comunidade)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Sim||
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Não|Revisar a escrita das tarefas|
| 3 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 4 | Os atores estão representados com a abstração correta?  |Sim||
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar? |Sim||
| 7 | As metas estão descritas em voz passiva? |Sim||
| 8 | Todos os recursos são substantivos? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|1|3|
|Médio|0|0|
|Baixo|0|0|
|**Total**|1|3|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISD-06

_Inspeção do [ISD06](../Modelagem/istar.md#isd06-Videochamada)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Dependency Model**|||
| 1 | Todas as dependências estão direcionadas corretamente? |Não|Revisar ordem das dependências|
| 2 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 3 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 4 | Os atores estão representados com a abstração correta?  |Não|O Rocket.Chat pode ser representado como um agente do sistema|
| 5 | Os atores descritos são realmente os necessários e suficientes para o modelo proposto? |Sim||
| 6 | As metas são objetivos que se deseja alcançar? |Sim||
| 7 | As metas estão descritas em voz passiva? |Sim||
| 8 | Todos os recursos são substantivos? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

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

#### IISR-01

_Inspeção do [ISR01](../Modelagem/istar.md#isr01-criar-channel)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Sim||
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Não|Verificar se é possível criar outros tipos de relacionamentos de impacto. Sugestão: Definir um nome intuitivo pode ajudar na interação entre os membros.|
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim|Usar adjetivos qualitativos. Ex: Bom entendimento.|
| 10 | As metas são objetivos que se deseja alcançar? |Sim||
| 11 | As metas estão descritas em voz passiva? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISR-02

_Inspeção do [ISR02](../Modelagem/istar.md#isr02-realizar-cadastro)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Sim|Verificar se é possível adicionar mais impactos.|
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Não|Verificar se é possível adicionar mais impactos.|
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 10 | As metas são objetivos que se deseja alcançar? |Sim||
| 11 | As metas estão descritas em voz passiva? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|0|0|
|Baixo|1|1|
|**Total**|1|1|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISR-03

_Inspeção do [ISR03](../Modelagem/istar.md#isr03-envio-de-mensagens)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Sim||
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Não||
| 7 | Todos os recursos são substantivos? |-|Este modelo não possui recursos, verificar se é possível adicionar recursos.|
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 9 | Os Softgoals representam requisitos não-funcionais? |Não|Revisar softgoal 'Mensagens direcionadas'|
| 10 | As metas são objetivos que se deseja alcançar? |Não|Verificar se mensagem de texto, video e áudio são realmente hardgoals|
| 11 | As metas estão descritas em voz passiva? |Não|Verificar se mensagem de texto, video e áudio são realmente hardgoals||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|2|6|
|Médio|1|2|
|Baixo|1|1|
|**Total**|4|9|
||**Conclusão**||
||Modelo reprovado, pois a pontuação dos defeitos está além da tolerância estabelecida. Várias melhorias são necessárias e devem ser aplicadas a este modelo.|||

#### IISR-04

_Inspeção do [ISR04](../Modelagem/istar.md#isr04-acoes-sobre-as-mensagens)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Sim||
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Sim||
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim|Verificar se a tarefa 'responder' pode ser substituída por 'responder mensagem'.|
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim|Usar adjetivos qualitativos. Ex: Boa variedade de opções.|
| 10 | As metas são objetivos que se deseja alcançar? |Sim||
| 11 | As metas estão descritas em voz passiva? |Não|Revisar os hardgoals.||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISR-05

_Inspeção do [ISR05](../Modelagem/istar.md#isr05-acoes-sobre-o-channel)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |-|Este modelo não possui impactos. Verificar se é possível adicionar impactos.|
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |-|Este modelo não possui impactos. Verificar se é possível adicionar impactos.|
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 10 | As metas são objetivos que se deseja alcançar? |Sim||
| 11 | As metas estão descritas em voz passiva? |Não|Verificar a meta 'exibir conversas'.||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|0|0|
|**Total**|1|2|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

#### IISR-06

_Inspeção do [ISR06](../Modelagem/istar.md#isr06-contribuicao-da-comunidade)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Não|As ligações com os elementos externos não foram representadas, adicionar essas ligações e suas dependências.|
| 4 | As ligações 'and' e 'or' estão corretas? |Sim||
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Não|Verificar o sentido dos impactos.|
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Sim||
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Não|Usar verbos no infinitivo para descrever as tasks.|
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 10 | As metas são objetivos que se deseja alcançar? |Sim||
| 11 | As metas estão descritas em voz passiva? |Sim|||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|1|3|
|Médio|2|4|
|Baixo|0|0|
|**Total**|3|7|
||**Conclusão**||
||Modelo reprovado, pois a pontuação dos defeitos está além da tolerância estabelecida. Várias melhorias são necessárias e devem ser aplicadas a este modelo.|||

#### IISR-07

_Inspeção do [ISR07](../Modelagem/istar.md#isr07-videochamada)_

|Nº|Critério|Check|Observação/Melhoria Sugerida|
|:--:|:--:|:--:|:--:|
||**Strategic Rationale Model**|||
| 1 | A boundary representa a fronteira de um ator, limitando o escopo de sua atuação? |Sim||
| 2 | Todos os elementos presentes dentro da fronteira são elementos relacionados ao ator que ela pertence? |Sim||
| 3 | As ligações com elementos de fora da fronteira são feitas através de dependências? |Sim||
| 4 | As ligações 'and' e 'or' estão corretas? |Não|Ligações 'and' e 'or' não estão sendo representadas, revisar todas as ligações e corrigir as erradas.|
| 5 | Os impactos estão representados com sentido e intensidade corretas? |Sim|Verificar se algum impacto deve se tornar uma ligação 'and' ou 'or'. |
| 6 | Existe propagação de impacto entre diferentes ramos? (Não apenas entre pais e filhos) |Não|Verificar se é possível propagar impactos entre diferentes ramos.|
| 7 | Todos os recursos são substantivos? |Sim||
| 8 | Todas as tarefas(task) são ações e estão representadas com verbos no infinitivo? |Sim||
| 9 | Os Softgoals representam requisitos não-funcionais? |Sim||
| 10 | As metas são objetivos que se deseja alcançar? |-|Este modelo não possui hardgoals|
| 11 | As metas estão descritas em voz passiva? |-|Este modelo não possui hardgoals.||

||**Resultados**||
|:--:|:--:|:--:|
|**Importância**|**Critérios não atendidos**|**Pontuação total dos defeitos**|
|Alto|0|0|
|Médio|1|2|
|Baixo|1|1|
|**Total**|2|3|
||**Conclusão**||
||Modelo aprovado, pois a pontuação dos defeitos está dentro da tolerância estabelecida. Poucas melhorias são necessárias.|||

## Referências

1 - Gregolin, Rosângela. Uma proposta de inspeção em modelos de caso de uso. 2007. Disponível em: http://cassiopea.ipt.br/teses/2007_EC_Rosangela_Gregolin.pdf. Acessado em: 07, jun, 2019.

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 07/05/2019 | 1.0 | Abertura do documento | Weiller Fernandes |
| 07/05/2019 | 1.1 | Inclusão da Metodologia, Critérios e Critério de aceitação | Weiller Fernandes |
| 08/05/2019 | 1.2 | Adição das inspeções-modelo IISD-0X e IISR-0X | Weiller Fernandes |
| 08/05/2019 | 1.3 | Adição das inspeções IISD-01 até IISD-06 | Weiller Fernandes |
| 09/05/2019 | 1.4 | Adição das inspeções IISR-01 até IISR-07 | Weiller Fernandes |
| 10/05/2019 | 1.5 | Adição das conclusões das inspeções IISD-01 a IISD-06 e IISR-01 a IISR-07 | Weiller Fernandes |
