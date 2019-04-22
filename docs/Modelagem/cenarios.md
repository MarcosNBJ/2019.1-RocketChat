# Cenários

Cenários é uma técnica de modelagem que consiste em explicar diversos fluxos de ações possíveis no app através da listagem de todos os fatores que os constituem, sendo estes: objetivo, contexto, atores envolvidos, recursos necessários, restrições, exceções e episódios que constituem o fluxo. Adicionalmente, são aqui colocados também qual requisito elicitou cada cenário, para melhorar a rastreabilidade.


### C1 - V1

|**Cadastro de  um novo [usuário](lexicos.md#l19) no [Rocket.chat](lexicos.md#l65)**|
|--|
|**Objetivo** |
| Cadastrar um novo [usuário](lexicos.md#l19) |
|**Contexto** |
| -Local: Página inical do app do [Rocket.chat](lexicos.md#l65) |
| -pré-condição: Possuir internet, não estar [logado](lexicos.md#l62) na plataforma |
| -Pós-condição:  [Usuário](lexicos.md#l19) cadastrado |
|**Atores** |
|  [Usuário](lexicos.md#l19) não cadastrado |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -[Rocket.chat](lexicos.md#l65) instalado. |
|**Restrição**|
|  -Internet ruim, não possuir uma conta em uma rede social externa. |
|  -não possuir uma conta em uma rede social externa. |
|**Exceção** |
|  -Internet cair. |
|  -App dar crash. |
|  -Senha inválida. |
|  -Email inválido. |
|  -Conta em uma rede social externa inexistente. |
|**Episódios** |
|  -Um novo [usuário](lexicos.md#l19) ou [usuário](lexicos.md#l19) que deseja uma nova [conta](lexicos.md#l67) entra na plataforma do [Rocket.chat](lexicos.md#l65) em seu computador ou celular. |
|-Na tela inicial, o [usuário](lexicos.md#l19) não [logado](lexicos.md#l62) seleciona a opção “Registrar um novo [usuário](lexicos.md#l19)”.|
|-Na tela de cadastro, o [usuário](lexicos.md#l19) preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer log up.|
|-Criando um [usuário](lexicos.md#l19) do zero ou usando uma rede social, o novo [usuário](lexicos.md#l19) é direcionado para uma página onde deve selecionar seu [user name](lexicos.md#l17).|
|-O [usuário](lexicos.md#l19) preenche o campo de [user name](lexicos.md#l17) e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|  - |


### C1 - V2

|**Cadastrar um novo [usuário](lexicos.md#l19)**|
|--|
|**Objetivo** |
| Acessar as funcionalidades da plataforma disponíveis para [usuários](lexicos.md#l19) cadastrados |
|**Contexto** |
| -Local: Página inical do app do [Rocket.chat](lexicos.md#l65) |
| -pré-condição: Possuir internet, não estar [logado](lexicos.md#l62) na plataforma |
| -Pós-condição:  [Usuário](lexicos.md#l19) cadastrado |
|**Atores** |
|  [Usuário](lexicos.md#l19) não cadastrado |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -[Rocket.chat](lexicos.md#l65) instalado. |
|**Restrição**|
|  -Internet ruim, não possuir uma conta em uma rede social externa. |
|  -não possuir uma conta em uma rede social externa. |
|**Exceção** |
|  -Internet cair. |
|  -App dar crash. |
|  -Senha inválida. |
|  -Email inválido. |
|  -Conta em uma rede social externa inexistente. |
|**Episódios** |
|  -Um novo [usuário](lexicos.md#l19) ou [usuário](lexicos.md#l19) que deseja uma nova [conta](lexicos.md#l67) entra na plataforma do [Rocket.chat](lexicos.md#l65) em seu computador ou celular. |
|-Na tela inicial, o [usuário](lexicos.md#l19) não [logado](lexicos.md#l62) seleciona a opção “Registrar um novo [usuário](lexicos.md#l19)”.|
|-Na tela de cadastro, o [usuário](lexicos.md#l19) preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer sign up.|
|-Criando um [usuário](lexicos.md#l19) do zero ou usando uma rede social, o novo [usuário](lexicos.md#l19) é direcionado para uma página onde deve selecionar seu [user name](lexicos.md#l17).|
|-O [usuário](lexicos.md#l19) preenche o campo de [user name](lexicos.md#l17) e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|-|


### C2 - V1

|**Realizar [Video Chat](lexicos.md#l25)**|
|--|
|**Objetivo** |
| Realizar uma reunião online |
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65) |
| -Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador |
| -Pós-condição: [Video Chat](lexicos.md#l25) será realizada com sucesso entre os [usuários](lexicos.md#l19)
|
|**Atores** |
|  -Pessoa 1 |
|  -Pessoa 2 |
|**Recursos** |
|  -Internet |
|  -Computador/celular |
|  -[Rocket.chat](lexicos.md#l65) instalado |
|**Restrição**|
|  -Internet ruim |
|  -bug na plataforma |
|  -muito ruído externo |
|  -microfone ruim |
|  -alto-falante ruim |
|  -computador ou celular com configurações ruins |
|  -ausência de webcam |
|**Exceção** |
|  -Internet cair. |
|  -Plataforma dar crash. |
|  -computador quebrar. |
|  -microfone do computador quebrar.|
|**Episódios** |
|  -Pessoa 1 um marca reunião com a pessoa 2. |
|  -Pessoa 1 acessa a internet e baixa o [Rocket.chat](lexicos.md#l65) em seu computador.|
|  -Pessoa 1 pega seu fone de ouvido e testa seu microfone.|
|  -Pessoa 2 acessa a internet e baixa o [Rocket.chat](lexicos.md#l65) em seu celular.|
|  -Pessoa 2 testa o microfone e autofalante de seu celular, já que não possui fones de ouvido.|
|  -Pessoa um entra em sua [conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) e procura o [usuário](lexicos.md#l19) da Pessoa 2.|
|  -Pessoa 1 entra em um bate papo com a pessoa 2. |
|  -Pessoa 1 seleciona a opção “Realizar [Vídeo conferência](lexicos.md#l25)” e manda o convite para a pessoa 2.|
|  -Pessoa 2 entra em sua conta do [Rocket.chat](lexicos.md#l65) e aceita o convite para a realização da [Video Chat](lexicos.md#l25).|
|**Levantado pela técnica**|
|  Storyboard, introspecção, questionário, análise de protocolo, análise de discurso |


### C2 - V2

|**Realizar [Video Chat](lexicos.md#l25)**|
|--|
|**Objetivo** |
| Conversar a distância com outro [usuário](lexicos.md#l19)/grupo. |
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65) |
| -Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador |
| -Pós-condição: [Video Chat](lexicos.md#l25) será realizada com sucesso entre os [usuários](lexicos.md#l19)
|
|**Atores** |
|  -Criador da [Video Chat](lexicos.md#l25) |
|  -Grupo/pessoas que irão participar  |
|**Recursos** |
|  -Internet |
|  -Computador/celular |
|  -[Rocket.chat](lexicos.md#l65) instalado |
|**Restrição**|
|  -Internet ruim |
|  -bug na plataforma |
|  -muito ruído externo |
|  -microfone ruim |
|  -alto-falante ruim |
|  -computador ou celular com configurações ruins |
|  -ausência de webcam |
|**Exceção** |
|  -Internet cair. |
|  -Plataforma dar crash. |
|  -computador quebrar. |
|  -microfone do computador quebrar.|
|**Episódios** |
| -O criador da [Video Chat](lexicos.md#l25) um marca reunião com o grupo/pessoa.|
| -Todos os envolvidos pegam seu fone de ouvido e testam seu microfone.|
| -Criador da conversa entra em sua [conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) e procura o [usuários](lexicos.md#l19) dos outros envolvidos.|
| -Criador da [Video Chat](lexicos.md#l25) entra em um bate papo com o grupo/pessoa.|
| -Criador da [Video Chat](lexicos.md#l25) seleciona a opção “Realizar [Video Chat](lexicos.md#l25)” e manda o convite para o grupo/pessoa.|
| -O grupo/pessoa entra em sua [conta](lexicos.md#l67) do [Rocket.chat](lexicos.md#l65) e aceita o convite para a realização da [Video Chat](#l25).|
|**Levantado pela técnica**|
|  Storyboard, introspecção, questionário, análise de protocolo, análise de discurso |

### C3 - V1
|**Criar [channel](lexicos.md#l1)**|
|--|
|**Objetivo** |
| Criação de um local para discussões |
|**Contexto** |
| - Em um [servidor](lexicos.md#l18) do [Rocket.chat](lexicos.md#l65) |
|**Atores** |
|  - [Usuários](lexicos.md#l19) e [membros](lexicos.md#l12) |
|**Recursos** |
| - Possuir internet |
| - [Conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
| - Internet ruim
| - Diversos [usuários](lexicos.md#l19) para participar do [channel](lexicos.md#l1)|
|**Exceção** |
| - Não possuir internet |
| - Aplicação para de funcionar |
| - Dispositivo não funcionar |
|**Episódios** |
| - [Usuário](lexicos.md#l19), que possui internet, instala o [Rocket.chat](lexicos.md#l65) em um dispositivo |
| - [Usuário](lexicos.md#l19), que possui internet, instala o [Rocket.chat](lexicos.md#l65) em um dispositivo|
| - [Usuário](lexicos.md#l19) entre na aplicação|
| - [Usuário](lexicos.md#l19) entra na aplicação e conecta-se a um [servidor](lexicos.md#l18)|
| - [Usuário](lexicos.md#l19) efetua o login através de uma [conta](lexicos.md#l67)|
| - Na aba lateral do app, o [usuário](lexicos.md#l19) clica em “Criar chat”|
| - [Usuário](lexicos.md#l19) define se o [channel](lexicos.md#l1) será privado, se somente [usuários](lexicos.md#l19) autorizados poderão enviar mensagens, se o [channel](lexicos.md#l1) será criptografado ou se somente [usuários](lexicos.md#l19) autorizados poderão enviar mensagens e os demais [membros](lexicos.md#l12) poderão apenas responder às mensagens|
| - [Usuário](lexicos.md#l19) insere o nome do [channel](lexicos.md#l1)|
| - [Usuário](lexicos.md#l19) escolhe os [membros](lexicos.md#l12) que irão participar do [channel](lexicos.md#l1)|
| - [Usuário](lexicos.md#l19) clica no botão “Criar”|
|**Levantado pela técnica**|
| - Introspecção [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03)|
| - [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos)|
| - Analise de Protocolo [AP4](../Elicitação/analprot.md#requisitos-elicitados) |
| - Questionário [Q16](../Elicitação/questionario.md#requisitos-elicitados) |

### C3 - V2
|**Criar [channel](lexicos.md#l1)**|
|--|
|**Objetivo** |
| Criação de um local para discussões |
|**Contexto** |
| - Local: Em um [servidor](lexicos.md#l18) do [Rocket.chat](lexicos.md#l65)|
| - Tempo: A qualquer momento|
| - Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador, estar conectado à um [servidor](lexicos.md#l18) do aplicativo |
| - Pós-condição: [Channel](lexicos.md#l1) estará criado |
|**Atores** |
|  - [Usuário](lexicos.md#l19) e [membros](lexicos.md#l12) |
|**Recursos** |
| - Dispositivo com [Rocket.chat](lexicos.md#l65) instalado |
| - Possuir internet |
| - [Conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) |
| - [Usuário](lexicos.md#l19) precisa estar conectado à um [servidor](lexicos.md#l18) |
|**Restrição**|
| - Internet ruim
| - Diversos [usuários](lexicos.md#l19) para participar do [channel](lexicos.md#l1)|
| - [Membros](lexicos.md#l12) que mantém o foco e sejam concisos nas discussões|
|**Exceção** |
| - Não possuir internet |
| - Aplicação para de funcionar |
| - Dispositivo não funcionar |
| - [Servidor](lexicos.md#l18) cair |
|**Episódios** |
| - Na aba lateral do app, o [usuário](lexicos.md#l19) clica em “Criar chat”|
| - [Usuário](lexicos.md#l19) define se o [channel](lexicos.md#l1) será privado, se somente [usuários](lexicos.md#l19) autorizados poderão enviar mensagens, se o [channel](lexicos.md#l1) será criptografado ou se somente [usuários](lexicos.md#l19) autorizados poderão enviar mensagens e os demais [membros](lexicos.md#l12) poderão apenas responder às mensagens|
| - [Usuário](lexicos.md#l19) insere o nome do [channel](lexicos.md#l1)|
| - [Usuário](lexicos.md#l19) escolhe os [membros](lexicos.md#l12) que irão participar do [channel](lexicos.md#l1)|
| - [Usuário](lexicos.md#l19) clica no botão “Criar”|
|**Levantado pela técnica**|
| - Introspecção [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03)|
| - [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos)|
| - Analise de Protocolo [AP4](../Elicitação/analprot.md#requisitos-elicitados) |
| - Questionário [Q16](../Elicitação/questionario.md#requisitos-elicitados) |


### C4 - V1

|**Conectar com um [servidor](lexicos.md#l18)**|
|--|
|**Objetivo** |
| Iniciar conexão com uma instância do [Rocket.chat](lexicos.md#l65) |
|**Contexto** |
| - Local: Tela inicial do app ou na aba lateral dentro de um [servidor](lexicos.md#l18) |
|**Atores** |
| - [Usuário](lexicos.md#l19) |
|**Recursos** |
| - Possuir internet |
| - [Conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
| - Internet ruim |
|**Exceção** |
| - Dispositivo não funcionar |
| - Não ser um [servidor](lexicos.md#l18) válido |
| - Aplicação para de funcionar |
| - Não possuir internet |
|**Episódios** |
| - [Usuário](lexicos.md#l19), que possui internet, instala o [Rocket.chat](lexicos.md#l65) em um dispositivo |
| - [Usuário](lexicos.md#l19) entra na aplicação |
| - Se usuário não estiver conectado à um [servidor](lexicos.md#l18), na primeira tela do aplicativo. Caso contrário, na aba lateral, [usuário](lexicos.md#l19) vai até “Adicionar novo [servidor](lexicos.md#l18)” |
| - [Usuário](lexicos.md#l19) clica em “Conectar com um [servidor](lexicos.md#l18)”|
| - [Usuário](lexicos.md#l19) define o protocolo de conexão|
| - [Usuário](lexicos.md#l19) insere o endereço do [servidor](lexicos.md#l18) |
| - [Usuário](lexicos.md#l19) clica em “Conectar” |
|**Levantado pela técnica**|
| - Entrevista [ENT1.7](../Elicitação/Entrevista.md#requisitos) |
| - Introspecção [INT1.4](../Elicitação/Introspeccao.md#introspeccao-01), [INT3.2](../Elicitação/Introspeccao.md#introspeccao-03)|
| - [Storyboard 4](../Elicitação/Storyboard.md#4-requisitos-obtidos) |
| - Analise de Discurso [AD13](../Elicitação/analdiscurso.md#requisitos-elicitados) |
| - Analise de Protocolo [AP2](../Elicitação/analprot.md#requisitos-elicitados) |

### C4 - V2

|**Conectar com um [servidor](lexicos.md#l18)**|
|--|
|**Objetivo** |
| Iniciar conexão com uma instância do [Rocket.chat](lexicos.md#l65) |
|**Contexto** |
| - Local: Tela inicial do app ou na aba lateral dentro de um [servidor](lexicos.md#l18) |
| - Tempo: A qualquer momento|
| - Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador|
| - Pós-condição: [Usuário](lexicos.md#l19) estará conectado com um [servidor](lexicos.md#l18) |
|**Atores** |
| - [Usuário](lexicos.md#l19) |
|**Recursos** |
| - Dispositivo com [Rocket.chat](lexicos.md#l65) instalado |
| - Possuir internet |
| - [Conta de usuário](lexicos.md#l67) |
|**Restrição**|
| - Internet ruim |
| - [Servidor](lexicos.md#l18) instável |
|**Exceção** |
| - Dispositivo não funcionar |
| - Não ser um [servidor](lexicos.md#l18) válido |
| - Aplicação para de funcionar |
| - Não possuir internet |
|**Episódios** |
| - Se [usuário](lexicos.md#l19) não estiver conectado à um [servidor](lexicos.md#l18), na primeira tela do aplicativo, caso contrário, na aba lateral, [usuário](lexicos.md#l19) vai até “Adicionar novo [servidor](lexicos.md#l18)”
| - [Usuário](lexicos.md#l19) clica em “Conectar com um [servidor](lexicos.md#l18)”
| - [Usuário](lexicos.md#l19) define o protocolo de conexão
| - [Usuário](lexicos.md#l19) insere o endereço do [servidor](lexicos.md#l18)
| - [Usuário](lexicos.md#l19) clica em “Conectar” |
|**Levantado pela técnica**|
| - Entrevista [ENT1.7](../Elicitação/Entrevista.md#requisitos) |
| - Introspecção [INT1.4](../Elicitação/Introspeccao.md#introspeccao-01), [INT3.2](../Elicitação/Introspeccao.md#introspeccao-03)|
| - [Storyboard 4](../Elicitação/Storyboard.md#4-requisitos-obtidos) |
| - Analise de Discurso [AD13](../Elicitação/analdiscurso.md#requisitos-elicitados) |
| - Analise de Protocolo [AP2](../Elicitação/analprot.md#requisitos-elicitados) |

### C5

|**Editar uma mensagem**|
|--|
|**Objetivo** |
| [Usuário](lexicos.md#l19) editar o conteúdo textual de uma mensagem em um texto |
|**Contexto** |
|-Local: [channel](lexicos.md#l1) da conversa|
|-Tempo: A qualquer momento|
|-Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1), bem como ter as permissões necessárias
|-Pós-condição: A dada mensagem no [channel](lexicos.md#l1) será mostrada com o conteúdo editado e um identificador contendo a palavra “Editada”|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|**Restrição**|
|  restrições aqui |
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) não tem permissão|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) abre o aplicativo|
|- [Usuário](lexicos.md#l19) loga no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) vai até o [channel](lexicos.md#l1)|
|- [Usuário](lexicos.md#l19) clica na mensagem que deseja editar|
|- [Usuário](lexicos.md#l19) clica na opção editar|
|- [Usuário](lexicos.md#l19) edita o conteúdo da mensagem|
|- [Usuário](lexicos.md#l19) clica no botão enviar, finalizando a edição|
|**Levantado pela técnica**|
| - |

### C5 - V2

|**Editar uma mensagem**|
|--|
|**Objetivo** |
| [Usuário](lexicos.md#l19) editar o conteúdo textual de uma mensagem para exprimir uma ideia diferente da anterior |
|**Contexto** |
|-Local: [channel](lexicos.md#l1) da conversa|
|-Tempo: A qualquer momento|
|-Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1), bem como ter as permissões necessárias
|-Pós-condição: A dada mensagem no [channel](lexicos.md#l1) será mostrada com o conteúdo editado e um identificador contendo a palavra “Editada”|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|**Restrição**|
|- Qualidade da conexão com a internet |
|- Usuário exprimir corretamente a ideia que gostaria|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) não tem permissão|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) abre o aplicativo|
|- [Usuário](lexicos.md#l19) loga no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) vai até o [channel](lexicos.md#l1)|
|- [Usuário](lexicos.md#l19) clica na mensagem que deseja editar|
|- [Usuário](lexicos.md#l19) clica na opção editar|
|- [Usuário](lexicos.md#l19) edita o conteúdo da mensagem|
|- [Usuário](lexicos.md#l19) clica no botão enviar, finalizando a edição|
|**Levantado pela técnica**|
| - |


### C6

|**Deletar conta**|
|--|
|**Objetivo** |
| [Deletar uma conta](lexicos.md#l21) existente no app [Rocket.Chat](lexicos.md#l65), por não se interessar mais em usa-lo |
|**Contexto** |
| Local: [Perfil](lexicos.md#l8) do usuário |
|Tempo: A qualquer momento após uma conta ter sido criada|
|Pré-condição: Estar conectado à internet, possuir conta no [Rocket.Chat](lexicos.md#65)|
|Pós-condição: A conta será deletada com sucesso|
|**Atores** |
|  [usuário](lexicos.md#l19) com conta no [Rocket.Chat](lexicos.md#l65) |
|**Recursos** |
| Internet |
| Celular |
|  Conta ativa no [Rocket.Chat](lexicos.md#l65) |
|**Restrição**|
| Conexão de baixa qualidade com a internet |
|**Exceção** |
| Internet cair |
| Usuário digitar sua senha errado|
| Usuário cancelar a ação|
| App parar de funcionar |
|**Episódios** |
| Um usuário que já possui uma conta no [Rocket.Chat](lexicos.md#l65) deseja excluí-la |
| [Usuário](lexicos.md#l19) acessa o seu perfil e clica em “deletar conta” |
| Uma tela com a mensagem “Você tem certeza?” é exibida ao [usuário](lexicos.md#l19) |
| [Usuário](lexicos.md#l19) preenche o campo obrigatório com a senha de sua conta |
| [Usuário](lexicos.md#l19) clica em “Deletar Conta” |
| [Usuário](lexicos.md#l19) tem sua conta deletada com sucesso |
|**Levantado pela técnica**|
| - |


### C7

|**Responder  mensagem**|
|--|
|**Objetivo** |
|- [Usuário](lexicos.md#l19) enviar uma mensagem que responde uma outra mensagem anterior|
|**Contexto** |
|- Local: [channel](lexicos.md#l1) da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1) |
|- Pós-condição: A resposta enviada pelo [usuário](lexicos.md#l19) será mostrada no [channel](lexicos.md#l1) com o anexo da mensagem respondida abaixo|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|**Restrição**|
|  restrições aqui |
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) loga no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) clica no [channel](lexicos.md#l1) desejado|
|- [Usuário](lexicos.md#l19) clica na mensagem que deseja responder|
|- [Usuário](lexicos.md#l19) escreve o conteúdo desejado|
|- [Usuário](lexicos.md#l19) envia a resposta|
|**Levantado pela técnica**|
| - [StotyBoarding](../Elicitação/StotyBoarding.md) |

### C8

|**Enviar desenho**|
|--|
|**Objetivo** |
|- [Usuário](lexicos.md#l19) enviar uma mensagem cujo conteúdo é um desenho digital feito por ele na aplicação, com o objetivo de expor alguma ideia ou mensagem ilustrada|
|**Contexto** |
|- Local: [channel](lexicos.md#l1) da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1)|
|- Pós-condição: Será visto no [channel](lexicos.md#l1) o desenho enviado pelo [usuário](lexicos.md#l19)|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|**Restrição**|
|- [Usuário](lexicos.md#l19) não desenhou corretamente o que queria|
|- Ferramenta de desenhos digitais não oferecia algum recurso de desenho que o [usuário](lexicos.md#l19) precisava|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) entra [logado](lexicos.md#l62) no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado|
|- [Usuário](lexicos.md#l19) clica no botão de “plus”|
|- [Usuário](lexicos.md#l19) clica na opção “desenho”|
|- [Usuário](lexicos.md#l19) desenha o conteúdo desejado|
|- [Usuário](lexicos.md#l19) envia o desenho|
|**Levantado pela técnica**|
|  - |

### C9

|**[Anexar um arquivo](lexicos.md#l5)**|
|--|
|**Objetivo** |
|- [Usuário](lexicos.md#l19) enviar, com ou sem uma mensagem textual, um arquivo de mídia (como fotos ou vídeos) ou um documento|
|**Contexto** |
|- Local: [channel](lexicos.md#l1) da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1) |
|- Pós-condição: Será mostrado para os outros usuários no [channel](lexicos.md#l1) o [arquivo enviado](lexicos.md#l5) pelo [usuário](lexicos.md#l19), com a opção de download|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|- Arquivo qualquer|
|**Restrição**|
|- [Usuário](lexicos.md#l19) [enviar o arquivo](lexicos.md#l5) correto|
|- O arquivo não deve demorar para ser enviado|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) não tem permissão|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) entra [logado](lexicos.md#l62) no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado|
|- [Usuário](lexicos.md#l19) clica no botão “plus”|
|- [Usuário](lexicos.md#l19) clica em [anexar um arquivo](#c9)|
|- [Usuário](lexicos.md#l19) seleciona o arquivo desejado|
|- [Usuário](lexicos.md#l19) envia o arquivo|
|**Levantado pela técnica**|
| - [Questionário](../Elicitação/questionario.md)|
| - [Introspecção](../Elicitação/Introspeccao.md) |


### C10

|**Alterar status do perfil**|
|--|
|**Objetivo** |
| Alterar o status de uma conta existente no app [Rocket.Chat](lexicos.md#l65) entre um dos 4 existentes |
|**Contexto** |
| Local: Aba lateral do [Rocket.Chat](lexicos.md#l65)|
| Tempo: A qualquer momento após uma conta ter sido criada |
| Pré-condição: Estar conectado à internet, possuir conta no [Rocket.Chat](lexicos.md#l65) |
| Pós-condição: O status será diferente do status inicial |
|**Atores** |
|  [Usuário](#l19) com conta no [Rocket.Chat](lexicos.md#l65) |
|**Recursos** |
| Internet|
| Celular |
| Conta ativa no [Rocket.Chat](lexicos.md#l65) |
|**Restrição**|
|  Conexão de baixa qualidade com a internet |
|**Exceção** |
| Internet cair |
| [Usuário](lexicos.md#l19) selecionar o status que já possuía anteriormente |
| [Usuário](lexicos.md#l19) cancelar a ação |
| App parar de funcionar |
|**Episódios** |
| Um [usuário](lexicos.md#l19) que já possui uma conta no [Rocket.Chat](lexicos.md#l65) deseja alterar seu status dentro do app |
| [Usuário](lexicos.md#l19) clica na aba lateral do aplicativo |
| [Usuário](lexicos.md#l19) visualiza uma lista com os status disponíveis |
| [Usuário](lexicos.md#l19) escolhe um status entre as opções Online, Ausente, Ocupado e Invisível |
| O [usuário](lexicos.md#l19) agora tem um novo status |
|**Levantado pela técnica**|
| Análise de protocolo |

### C11

|**Fixar Mensagem**|
|--|
|**Objetivo** |
| - Encontrar uma mensagem com mais facilidade |
|**Contexto** |
| - Local: Menu de opções de mensagens presentes em [channels](lexicos.md#l1) ou grupos |
| - Tempo: Quando uma mensagem está disponível no [channel](lexicos.md#l1) ou grupo |
| - Pré-condição:  O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1) |
| - Pós-condição: As mensagens fixadas ficarão disponíveis em “mensagens fixadas” localizada no menu principal do [channel](lexicos.md#l1) ou grupo |
 |
|**Atores** |
|- [Usuário](lexicos.md#l19) devidamente cadastrado no app e participante de um grupo |
|**Recursos** |
| - Internet |
| - Plataforma para uso da aplicação (celular ou computador) |
| Aplicativo instalado |
|**Restrição**|
| - Baixa qualidade na conexão de internet |
|**Exceção** |
| - Impossibilidade de conexão de internet |
| - [Usuário](lexicos.md#l19) cancelar ação |
| - Mensagem a ser fixada foi removida |
| - Bug no aplicativo |
|**Episódios** |
| - [Usuário](lexicos.md#l19) abre o aplicativo se loga em um [servidor](lexicos.md#l18) |
| - [Usuário](lexicos.md#l19) seleciona um grupo |
| - [Usuário](lexicos.md#l19) encontra uma mensagem de seu interesse |
| - [Usuário](lexicos.md#l19) seleciona a mensagem desejada através do menu de opções da mensagem |
| - [Usuário](lexicos.md#l19) seleciona o botão de fixar mensagem |


### C12

|**Enviar mensagem**|
|--|
|**Objetivo** |
|- Transmitir aos outros integrantes da conversa uma mensagem, que pode conter texto, Emojis, [arquivos de mídia](#c9), documentos, áudios gravados pelo app, e [desenhos digitais](#c8) feitos pelo menu do app.|
|**Contexto** |
|- Local: [channel](lexicos.md#l1) da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1) no qual deseja enviar uma mensagem|
|- Pós-condição: A mensagem enviada será mostrada no [channel](lexicos.md#l1) para todos os usuários [membros](lexicos.md#l12), junto com uma notificação que chegará se o [usuário](lexicos.md#l19) tiver sido mencionado|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|**Restrição**|
|- [Usuário](lexicos.md#l19) escrever corretamente o que quer expressar |
|- A aplicação oferecer ferramentas que ajudem o [usuário](lexicos.md#l19) a escrever sua mensagem, como um corretor ortográfico|
|- O [usuário](lexicos.md#l19) conseguir [anexar](lexicos.md#l5) todos os arquivos que quer|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) cancela a ação|
|- Mensagem do [usuário](lexicos.md#l19) está acima do limite de caracteres|
|**Episódios** |
|- [Usuário](lexicos.md#l19) entra [logado](lexicos.md#l62) no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado |
|- [Usuário](lexicos.md#l19) digita a mensagem no campo de texto|
|- [Usuário](lexicos.md#l19) [anexa todos os arquivos](#c9) ou [desenhos](#c8) que quiser na mensagem|
|- [Usuário](lexicos.md#l19) insere um [Emoji](lexicos.md#l7) se quiser|
|- [Usuário](lexicos.md#l19) envia a mensagem clicando no botão presente na caixa de texto para essa finalidade|
|**Levantado pela técnica**|
| - [Questionário](../Elicitação/questionario.md)|
| - [StotyBoarding](../Elicitação/storyboarding.md) |


### C13

|**[Favoritar Mensagem](lexicos.md#l44)**|
|--|
|**Objetivo** |
| [Favoritar uma mensagem](lexicos.md#l44) para que seja possível visualizá-la com mais facilidade posteriormente |
|**Contexto** |
| Local: Chat privado ou em grupo no [Rocket.Chat](lexicos.md#l65) |
| Tempo: A qualquer momento após um chat ser iniciado e possuir mensagens enviadas |
| Pré-condição: Estar conectado à internet, possuir conta no [Rocket.Chat](lexicos.md#l65) e estar em um chat que já possua mensagens enviadas |
| Pós-condição: A mensagem favoritada irá aparecer no menu de mensagens favoritas |
|**Atores** |
| Usuário participante de um chat |
|**Recursos** |
| Internet |
| Celular |
| Conta ativa no [Rocket.Chat](lexicos.md#l65) |
| Chat privado ou em grupo |
|**Restrição**|
| Conexão de baixa qualidade com a internet |
| Chat não possuir nenhuma mensagem ainda |
|**Exceção** |
| Internet cair |
| [Usuário](lexicos.md#l19) cancelar a ação |
| [Usuário](lexicos.md#l19) escolher opção errada |
| App parar de funcionar |
|**Episódios** |
| Um [usuário](lexicos.md#l19) participante de um chat deseja [favoritar uma mensagem](lexicos.md#l44) para que seja possível visualizá-la mais facilmente depois |
| O [usuário](lexicos.md#l19) abre uma conversa e clica na mensagem que deseja [favoritar](lexicos.md#l44) |
| Várias opções são exibidas ao [usuário](lexicos.md#l19), dentre elas a opção de [Favoritar](lexicos.md#l44), que pode ser identificada também pelo ícone de estrela |
| [Usuário](lexicos.md#l19) [favorita a mensagem](lexicos.md#l44) |
| Mensagem favoritada pode ser vista pelo menu de Mensagens Favoritas na aba de Detalhes do canal |
|**Levantado pela técnica**|
| - |

### C14

|**Visualizar [membros](lexicos.md#l12) de chat em grupo**|
|--|
|**Objetivo** |
| Visualizar [membros](lexicos.md#l12) participantes de determinado chat em grupo |
|**Contexto** |
| Local: Menu “[Membros](lexicos.md#l12)” dentro do menu “Detalhes do canal” em um chat em grupo |
| Tempo: A qualquer momento após um chat em grupo ser iniciado e possuir dois ou mais [membros](lexicos.md#l12) |
| Pré-condição: Estar conectado à internet, possuir conta no [Rocket.Chat](lexicos.md#l65) e estar em um chat em grupo |
| Pós-condição: Uma área com todos os [membros](lexicos.md#l12) pertencentes a um grupo é exibida |
|**Atores** |
| Usuário participante de um chat em grupo |
|**Recursos** |
| Internet |
| Celular |
| Conta ativa no [Rocket.Chat](lexicos.md#l65) |
| Chat em grupo |
|**Restrição**|
| Conexão de baixa qualidade com a internet|
| Chat não possuir [membros](lexicos.md#l12) ainda |
|**Exceção** |
| Internet cair|
| Usuário escolher opção errada|
| App parar de funcionar|
| Todos os [membros](lexicos.md#l12) saírem do chat em grupo |
|**Episódios** |
| Um usuário participante de um chat em grupo deseja ver quais os [membros](lexicos.md#l12) que também fazem parte daquele chat|
| O usuário abre uma conversa e clica no nome do grupo para abrir o menu de Detalhes do canal |
| Várias opções são exibidas ao usuário, dentre elas a opção de “[Membros](lexicos.md#l12)” |
| Usuário clica na opção [Membros](lexicos.md#l12) e uma lista é exibida com todos os usuários do grupo bem como seus respectivos status, fotos de perfil e [nome de usuário](#l17)|
|**Levantado pela técnica**|
| - |

### C15 - V1

|**Sair de um [channel](lexicos.md#l1)  **|
|--|
|**Objetivo** |
| Não ser mais participante de um [channel](lexicos.md#l1) na plataforma e com isso não receber notificações do mesmo |
|**Contexto** |
| -Local: Um [channel](lexicos.md#l1) dentro da plataforma|
| -Tempo: A qualquer momento após um chat em grupo ser iniciado e o [membro](lexicos.md#l12) que deseja se retirar seja adicionado|
| -Pré-condição: Estar conectado com a internet, ter o [Rocket.chat](lexicos.md#l65) baixado em seu computador, possuir um [usuário](lexicos.md#l19) na plataforma, estar presente no chat que deseja sair.|
| -Pós-condição: Não participação no chat em grupo.|
|**Atores** |
|  [Usuário](lexicos.md#l19) cadastrado presente no [channel](lexicos.md#l1) |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -[Rocket.chat](lexicos.md#l65) instalado. |
|  -Estar presente em um [channel](lexicos.md#l1) |
|**Restrição**|
| -Baixa conexão com a internet|
| -Baixo desempenho do computador, causando lentidão no processo|
|**Exceção** |
| -Não possuir internet |
| -App dar crash |
| -Computador quebrar |
| -Não participar de nenhum grupo |
| -Não possuir [Rocket.chat](lexicos.md#l65) versão desktop, nem [conta](lexicos.md#l67) na plataforma |
|**Episódios** |
| -Surge no [usuário](lexicos.md#l19) o desejo sair de um determinado grupo.|
| -O [usuário](lexicos.md#l19) abre a plataforma em seu computador.|
| -O [usuário](lexicos.md#l19) busca na área de [channels](lexicos.md#l1), o grupo no qual deseja se retirar.|
| -O [usuário](lexicos.md#l19) clica nos três pontos que surgem ao manter o cursor em cima do grupo que deseja sair.|
| -Após o clique, surgem diversas interações que podem ser realizadas com o grupo, dentre tais a de “Deixar grupo”.|
| -O [usuário](lexicos.md#l19) clica na opção “ Deixar grupo” e , com isso, deixa o grupo.|
|**Levantado pela técnica**|
|-|

### C16 - V1

|**Esconder sala**|
|--|
|**Objetivo** |
| Não ver mais uma sala e nem receber [notificações](lexicos.md#l28) da mesma|
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65).|
| -Tempo: a qualquer momento, quando o surgir no [usuário](lexicos.md#l19) o desejo de deixar uma sala.|
| -Pré-condição: Estar conectado com a internet, ter o [Rocket.chat](lexicos.md#l65) baixado em seu computador, possuir um [usuário](lexicos.md#l19) na plataforma, estar presente no [chat](lexicos.md#l1) que deseja Esconder.|
| -Pós-condição: Não ver mais e nem ser notificado pelo chat escondido.|
|**Atores** |
|  [Usuário](lexicos.md#l19) cadastrado presente no [channel](lexicos.md#l1) |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -[Rocket.chat](lexicos.md#l65) instalado. |
|  -Estar presente em um [channel](lexicos.md#l1) |
|**Restrição**|
| -Baixa conexão com a internet|
| -Baixo desempenho do computador, causando lentidão no processo|
|**Exceção** |
| -Não possuir internet |
| -App dar crash |
| -Computador quebrar |
| -Não participar de nenhum [grupo](lexicos.md#l1) |
| -Não possuir [Rocket.chat](lexicos.md#l65) versão desktop, nem [conta](lexicos.md#l67) na plataforma |
|**Episódios** |
| -Surge no [usuário](lexicos.md#l19) o desejo sair de esconder um [grupo](lexicos.md#l1).|
| -O [usuário](lexicos.md#l19) abre a plataforma em seu computador.|
| -O [usuário](lexicos.md#l19) busca na área de [channels](lexicos.md#l1), o [grupo](lexicos.md#l1) no qual deseja se esconder.|
| -O [usuário](lexicos.md#l19) clica nos três pontos que surgem ao manter o cursor em cima do [grupo](lexicos.md#l1).|
| -Após o clique, surgem diversas interações que podem ser realizadas com o [grupo](lexicos.md#l1), dentre tais a de “esconder [grupo](lexicos.md#l1)”.|
| -O [usuário](lexicos.md#l19) clica na opção “ esconder [grupo](lexicos.md#l1)” e , com isso, escondendo-o, passando a não receber mais atividades do mesmo, mas podendo restaurar a qualquer momento.|
|**Levantado pela técnica**|
|-|

### C17

|**Pesquisar mensagem**|
|--|
|**Objetivo** |
| Encontrar a mensagem desejada pelo [usuário](lexicos.md#l19) |
|**Contexto** |
| Local: Página do Chanel do [Rocket.chat](lexicos.md#l65) |
| Tempo: a qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) ter em mente as mensagens que deseja |
| Pós-condição: O [usuários](lexicos.md#l19) encontrará a mensagem de acordo com o que pesquisou |
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
| Internet|
| Conta ativa no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
|  O conteúdo retornado pela pesquisa deve ter relação com o pesquisado |
|**Exceção** |
| Internet cair |
| Palavras não tão bem especificadas que coincidem com outras |
| Não existir a mensagem pesquisada |
|**Episódios** |
| [Usuário](lexicos.md#l19) já [logado](lexicos.md#l62) abre o chanel |
| [Usuário](lexicos.md#l19) pesquisa a mensagem desejada na barra de pesquisa |
| [Usuário](lexicos.md#l19) pressiona a lupa |
| O aplicativo retorna uma seleção de mensagens conforme a pesquisa do [usuário](lexicos.md#l19) |
|**Levantado pela técnica**|
| - |

### C18

|**Fazer login**|
|--|
|**Objetivo** |
| Utilizar todas as funcionalidades disponíveis para [usuários](lexicos.md#l19) |
|**Contexto** |
| Local: Página inicial do [Rocket.chat](lexicos.md#l65) |
| Tempo: a qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) ter conta no aplicativo, inserir o [login](lexicos.md#l62) e senha corretos |
| Pós-condição: O [usuários](lexicos.md#l19) está [logado](lexicos.md#l62) |
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
| Internet|
| Conta ativa no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
| - |
|**Exceção** |
| Esqueceu a senha |
| Esqueceu o [login](lexicos.md#l62) |
| Não está cadastrado |
|**Episódios** |
| Inicia o Rocket.chat |
| [Usuário](lexicos.md#l19) preenche o [login](lexicos.md#l62) e senha |
| [Usuário](lexicos.md#l19) clica em "Entrar" |
|**Levantado pela técnica**|
| [Introspecção](../Elicitação/Introspeccao.md) |

### C19

|**Receber notificação**|
|--|
|**Objetivo** |
| Ser notificado sobre alguma mensagem recebida ou interações de outros [usuários](lexicos.md#l19) |
|**Contexto** |
| Local: Aba de [notificações](lexicos.md#l28) |
| Tempo: a qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) e com o aplicativo do [Rocket.chat](lexicos.md#l65) em segundo plano |
| Pós-condição: O [usuário](lexicos.md#l19) receberá a notificação quando receber uma mensagem ou ocorrer alguma interação |
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
| Internet|
| Conta ativa no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
| O [usuário](lexicos.md#l19) não ter as [notificações](lexicos.md#l28) desativadas |
|**Exceção** |
| Internet cair |
| App dar crash |
| Não estar com o app em segundo plano |
|**Episódios** |
| [Usuário](lexicos.md#l19) já [logado](lexicos.md#l62) acessa o [Rocket.chat](lexicos.md#l65) |
| [Usuário](lexicos.md#l19) recebe uma mensagem |
| [Usuário](lexicos.md#l19) clica nas [notificações](lexicos.md#l28) |
| [Usuário](lexicos.md#l19) vê a mensagem de outro [usuário](lexicos.md#l19) |
|**Levantado pela técnica**|
| [Questionário](../Elicitação/questionario.md) |

### C20

|**Sair do Rocket.chat**|
|--|
|**Objetivo** |
| Sair de uma [conta](lexicos.md#l67) de [usuário](lexicos.md#l19) logada |
|**Contexto** |
| Local: Aba lateral de opcões do [Rocket.chat](lexicos.md#l65) |
| Tempo: a qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) em sua conta do [Rocket.chat](lexicos.md#l65) |
| Pós-condição: O [usuário](lexicos.md#l19) saiu da sua conta no [Rocket.chat](lexicos.md#l65) |
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
| Internet|
| Conta ativa no [Rocket.chat](lexicos.md#l65) |
|**Restrição**|
| O [usuário](lexicos.md#l19) estar [logado](lexicos.md#l62) em uma conta |
|**Exceção** |
| Internet cair |
| App dar crash |
|**Episódios** |
| [Usuário](lexicos.md#l19) já logado abre o [Rocket.chat](lexicos.md#l65) |
| [Usuário](lexicos.md#l19) entra na aba de opções |
| [Usuário](lexicos.md#l19) seleciona a opção Sair |
| [Usuário](lexicos.md#l19) retorna para página inicial de [login](lexicos.md#l62) do [Rocket.chat](lexicos.md#l65) |
|**Levantado pela técnica**|
| - |

### C21

|**Escolher tom de pele padrão**|
|--|
|**Objetivo**|
| Escolher o tom de pele padrão dos [emojis](lexicos.md#l7) |
|**Contexto**|
| Local: Icone de [emojis](lexicos.md#l7) dentro de uma conversa, sendo individual ou em um canal |
| Tempo: A qualquer momento
| Pré-condição: O [usuário](lexicos.md#l19) deve estar logado em sua conta do [Rocket.chat](lexicos.md#l65) |
| Pós-condição O [usuário](lexicos.md#l19) possui um tom de pele padrão para seus emojis |
|**Atores**|
| [Usuário](lexicos.md#l19) |
|**Restrição**|
| O [usuário](lexicos.md#l19) estar logado em uma conta |
|**Exceção**|
| Estar sem internet |
|**Episódios**|
| [Usuário](lexicos.md#l19) já logado abre o [Rocket.chat](lexicos.md#l65) |
| [Usuário](lexicos.md#l19) entra em alguma conversa ou [canal](lexicos.md#l1) |
| [Usuário](lexicos.md#l19) clica no simbolo de emoji presente no canto inferior esquerdo |
| [Usuário](lexicos.md#l19) clica na circulo amarelo abaixo dos [emojis](lexicos.md#l7), no conto inferior direito |
| [Usuário](lexicos.md#l19) usuário escolhe a cor de pele padrão |
| [Usuário](lexicos.md#l19) é retornado a conversa ou [canal](lexicos.md#l1) |
|**Levantado pela técnica**|
| - |

### C22

|**Criar only read [Channel](lexicos.md#l1)**|
|--|
|**Objetivo**|
| Criar um channel onde apenas o administrador pode mandar mensagem |
|**Contexto**|
| Local: Criar chat, menu lateral do aplicativo |
| Tempo: A qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) deve estar logado em sua conta do [Rocket.chat](lexicos.md#l65) |
| Pós-condição: O [usuário](lexicos.md#l19) cria um read only channel e vira adminstrador do mesmo |
|**Atores**|
| [usuário](lexicos.md#l19) |
|**Exceção**|
| Estar sem internet |
|**Episódios**|
| [usuário](lexicos.md#l19) aperta no menu lateral do aplicativo no canto superior esquerdo |
| [usuário](lexicos.md#l19) clica no botão Criar chat |
| Na página de criar chat o [usuário](lexicos.md#l19) seleciona a opção Read only channel e cria o channel |
|**Levantado pela técnica**|
| - |

### C23

|**Definir membro de [channel](lexicos.md#l1) como proprietário**|
|--|
|**Objetivo**|
| Definir um usuário como proprietário do channel |
|**Contexto**|
| Local: Dentro do channel |
| Tempo: A qualquer momento |
| Pré-condição: O [usuário](lexicos.md#l19) deve estar logado em sua conta do [Rocket.chat](lexicos.md#l65) e ser membro do channel |
| Pós-condição: O [usuário](lexicos.md#l19) escolhido como propríetário recebe os privilégios de proprietário |
|**Atores**|
| [usuário](lexicos.md#l19) administrador do channel e participante do grupo |
|**Episódios**|
| O [usuário](lexicos.md#l19) adminstrador entrar no channel |
| O [usuário](lexicos.md#l19) administrador clica na lista de membros na parte superior direita |
| O [usuário](lexicos.md#l19) clica nos tres pontos ao lado do [usuário](lexicos.md#l19) o qual deseja tornar proprietário do channel |
|**Levantado pela técnica**|
| - |

### C24

|**Integrar Serviços**|
|--|
|**Objetivo**|
| - Melhorar comunicação com a equipe |
| - Aumentar produtividade |
| - Visualização de serviços externos no aplicativo |
|**Contexto**|
| - Local: No aplicativo e na documentação de integração do Rocket.Chat e do serviço que deseja integrar |
| - Tempo: Qualquer momento |
| - Pré-condição: [Usuário](lexicos.md#l19) deve possuir um cadastro ativo, ter o Rocket.Chat instalado, possuir conexão com internet e ter um certo conhecimento em integrações ao Rocket.Chat |
| - Pós-condição: Integração de um serviço que ajudará a equipe, geralmente um [bot](lexicos.md#l26) |
|**Atores**|
| - Usuário Administrador |
|**Recursos**|
| - Internet |
| - Conta no aplicativo |
|**Restrição**|
| - Estar logado em uma conta |
| - Não possuir um servidor próprio |
| - Falta de conhecimento no assunto |
| - Falta de tutoriais ou suporte |
|**Excessão**|
| - Queda de conexão com a internet |
| - Não possuir uma documentação adequada que instrua como |
| - realizar a integração de certo serviço |
| - Serviço de integração foi descontinuado |
|**Episódios**|
| - Usuário acessa aplicativo através do desktop preferencialmente |
| - Na tela inicial acessa um servidor |
| - Cria um novo usuário para o bot no [grupo](lexicos.md#l51) ou channel |
| - Usuário define os scripts para configurar o bot |
|**Levantado pela técnica**|
| - [Entrevista](../Elicitação/Entrevista.md) |
| - [Introspecção](../Elicitação/Introspeccao.md) |
| - [Questionário](../Elicitação/questionario.md) |
| - [StoryBoard](../Elicitação/Storyboard.md)


## Cenários que não correspondem a nenhum requisito elicitado

Alguns cenários listados não são correlacionados a nenhum requisito previamente elicitado. Fato este que demonstra uma provável falha na etapa de elicitação, que não permitiu que algumas necessidades fossem identificados.
*[c1](#c1-v2) [c5](#c5-v2) [c6](#c6) [c8](#c8) [c13](#c13) [c14](#c14) [c15](#c15) [c16](#c16) [c17](#c17) [c18](#c18) [c23](#c23)  [c22](#c22) [c21](#c21)*


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 19/04/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 21/04/2019 | 1.1 | Adição dos Cenários C5, C7, C8, C9, c12 | Marcos Nery |
| 21/04/2019 | 1.2 | Adição dos Cenários C1 - v1, C1 - v2, C2 - v1, C2 - v2, C15, C16, c12 | Gabriel Davi |
| 21/04/2019 | 1.3 | Adição do Cenário C11 | Lucas Maciel |
| 21/04/2019 | 1.4 | Adição do Cenários C3, C4 | Heron Rodrigues |
| 21/04/2019 | 1.5 | Adição dos Cenários C6, C10, C13, C14 | Weiller Fernandes |
| 21/04/2019 | 1.6 | Adição dos Cenários 17-20 | André Lucas |
| 22/04/2019 | 1.7 | Criando alguns links | Gabriel Davi |
| 22/04/2019 | 1.8 | Adição dos Cenários C21, C22, C23 | João Lucas |
| 22/04/2019 | 1.9 | Criando alguns links | Weiller Fernandes |
| 22/04/2019  |2.0  | Adicionando tabelamento de cenários não elicitados| Marcos Nery|
