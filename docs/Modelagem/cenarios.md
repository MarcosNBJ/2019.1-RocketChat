# Cenários

### C

|**Título do Cenário**|
|--|
|**Objetivo** |
| objetivo aqui |
|**Contexto** |
| contexto aqui |
|**Atores** |
|  atores aqui |
|**Recursos** |
|  recursos aqui |
|**Restrição**|
|  restrições aqui |
|**Exceção** |
|  exeções aqui |
|**Episódios** |
|  episódios aqui |
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|


### C1 - V1

|**Cadastro de  um novo [usuário](lexicos.md#l19) no [Rocket.chat](lexicos.md#l65)**|
|--|
|**Objetivo** |
| Cadastrar um novo [usuário](lexicos.md#l19) |
|**Contexto** |
| -Local: Página inical do app do [Rocket.chat](lexicos.md#l65) |
| -pré-condição: Possuir internet, não estar logado na plataforma |
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
|-Na tela inicial, o [usuário](lexicos.md#l19) não logado seleciona a opção “Registrar um novo [usuário](lexicos.md#l19)”.|
|-Na tela de cadastro, o [usuário](lexicos.md#l19) preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer log up.|
|-Criando um [usuário](lexicos.md#l19) do zero ou usando uma rede social, o novo [usuário](lexicos.md#l19) é direcionado para uma página onde deve selecionar seu user name.|
|-O [usuário](lexicos.md#l19) preenche o campo de user name e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|  - |


### C1 - V2

|**Cadastrar um novo [usuário](lexicos.md#l19)**|
|--|
|**Objetivo** |
| Acessar as funcionalidades da plataforma disponíveis para [usuários](lexicos.md#l19) cadastrados |
|**Contexto** |
| -Local: Página inical do app do [Rocket.chat](lexicos.md#l65) |
| -pré-condição: Possuir internet, não estar logado na plataforma |
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
|-Na tela inicial, o [usuário](lexicos.md#l19) não logado seleciona a opção “Registrar um novo [usuário](lexicos.md#l19)”.|
|-Na tela de cadastro, o [usuário](lexicos.md#l19) preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer sign up.|
|-Criando um [usuário](lexicos.md#l19) do zero ou usando uma rede social, o novo [usuário](lexicos.md#l19) é direcionado para uma página onde deve selecionar seu user name.|
|-O [usuário](lexicos.md#l19) preenche o campo de user name e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|-|


### C2 - V1

|**Realizar Web conferência**|
|--|
|**Objetivo** |
| Realizar uma reunião online |
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65) |
| -Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador |
| -Pós-condição: Web conferência será realizada com sucesso entre os [usuários](lexicos.md#l19)
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
|  -Pessoa 2 acessa a internet e baixa o rocket chat em seu celular.|
|  -Pessoa 2 testa o microfone e autofalante de seu celular, já que não possui fones de ouvido.|
|  -Pessoa um entra em sua [conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) e procura o [usuário](lexicos.md#l19) da Pessoa 2.|
|  -Pessoa 1 entra em um bate papo com a pessoa 2. |
|  -Pessoa 1 seleciona a opção “Realizar Vídeo conferência” e manda o convite para a pessoa 2.|
|  -Pessoa 2 entra em sua conta do [Rocket.chat](lexicos.md#l65) e aceita o convite para a realização da web conferencia.|
|**Levantado pela técnica**|
|  Storyboard, introspecção, questionário, análise de protocolo, análise de discurso |


### C2 - V2

|**Realizar Web conferência**|
|--|
|**Objetivo** |
| Conversar a distância com outro [usuário](lexicos.md#l19)/grupo. |
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65) |
| -Pré-condição: possuir internet, possuir a plataforma [Rocket.chat](lexicos.md#l65) no celular ou computador |
| -Pós-condição: Web conferência será realizada com sucesso entre os [usuários](lexicos.md#l19)
|
|**Atores** |
|  -Criador da web conferência |
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
| -O criador da web conferência um marca reunião com o grupo/pessoa.|
| -Todos os envolvidos pegam seu fone de ouvido e testam seu microfone.|
| -Criador da conversa entra em sua [conta](lexicos.md#l67) no [Rocket.chat](lexicos.md#l65) e procura o [usuários](lexicos.md#l19) dos outros envolvidos.|
| -Criador da web conferência entra em um bate papo com o grupo/pessoa.|
| -Criador da web conferência seleciona a opção “Realizar Vídeo conferência” e manda o convite para o grupo/pessoa.|
| -O grupo/pessoa entra em sua [conta](lexicos.md#l67) do [Rocket.chat](lexicos.md#l65) e aceita o convite para a realização da web conferência.|
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
| - Introspecção [INT1.1](../Elicitação/introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/introspeccao.md#introspeccao-03)|
| - [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos)|
| - Analise de Protocolo [AP4](../Elicitação/analprot.md#requisitos-elicitados) |
| - Questionário [Q16](../Elicitação/questionario#requisitos-elicitados) |

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
| - Diversos [Usuários](lexicos.md#l19) para participar do [channel](lexicos.md#l1)|
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
| - Introspecção [INT1.1](../Elicitação/introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/introspeccao.md#introspeccao-03)|
| - [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos)|
| - Analise de Protocolo [AP4](../Elicitação/analprot.md#requisitos-elicitados) |
| - Questionário [Q16](../Elicitação/questionario#requisitos-elicitados) |


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
| - Introspecção [INT1.4](../Elicitação/introspeccao.md#introspeccao-01), [INT3.2](../Elicitação/introspeccao.md#introspeccao-03)|
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
| - Introspecção [INT1.4](../Elicitação/introspeccao.md#introspeccao-01), [INT3.2](../Elicitação/introspeccao.md#introspeccao-03)|
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
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C6

|**Deletar conta**|
|--|
|**Objetivo** |
| Deletar uma conta existente no app Rocket.Chat |
|**Contexto** |
| Local: Perfil do usuário |
|Tempo: A qualquer momento após uma conta ter sido criada|
|Pré-condição: Estar conectado à internet, possuir conta no Rocket.Chat|
|Pós-condição: A conta será deletada com sucesso|
|**Atores** |
|  Usuário com conta no Rocket.Chat |
|**Recursos** |
| Internet |
| Celular |
|  Conta ativa no Rocket.Chat |
|**Restrição**|
| Conexão de baixa qualidade com a internet |
|**Exceção** |
| Internet cair |
| Usuário digitar sua senha errado|
| Usuário cancelar a ação|
| App parar de funcionar |
|**Episódios** |
| Um usuário que já possui uma conta no Rocket.Chat deseja excluí-la |
| Usuário acessa o seu perfil e clica em “deletar conta” |
| Uma tela com a mensagem “Você tem certeza?” é exibida ao usuário |
| Usuário preenche o campo obrigatório com a senha de sua conta |
| Usuário clica em “Deletar Conta” |
| Usuário tem sua conta deletada com sucesso |
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
|  qual técnica ou quais técnicas levantaram esse necessidade|

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
|- [Usuário](lexicos.md#l19) entra logado no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado|
|- [Usuário](lexicos.md#l19) clica no botão de “plus”|
|- [Usuário](lexicos.md#l19) clica na opção “desenho”|
|- [Usuário](lexicos.md#l19) desenha o conteúdo desejado|
|- [Usuário](lexicos.md#l19) envia o desenho|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C9

|**Anexar um arquivo**|
|--|
|**Objetivo** |
|- [Usuário](lexicos.md#l19) enviar, com ou sem uma mensagem textual, um arquivo de mídia (como fotos ou vídeos) ou um documento|
|**Contexto** |
|- Local: [channel](lexicos.md#l1) da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O [usuário](lexicos.md#l19) ter [conta](lexicos.md#l67) no aplicativo e estar dentro do [channel](lexicos.md#l1) |
|- Pós-condição: Será mostrado para os outros usuários no [channel](lexicos.md#l1) o arquivo enviado pelo [usuário](lexicos.md#l19), com a opção de download|
|**Atores** |
|  [Usuário](lexicos.md#l19) |
|**Recursos** |
|- Internet|
|- [Conta](lexicos.md#l67) no aplicativo|
|- Arquivo qualquer|
|**Restrição**|
|- [Usuário](lexicos.md#l19) enviar o arquivo correto|
|- O arquivo não deve demorar para ser enviado|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) não tem permissão|
|- [Usuário](lexicos.md#l19) cancela a ação|
|**Episódios** |
|- [Usuário](lexicos.md#l19) entra logado no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado|
|- [Usuário](lexicos.md#l19) clica no botão “plus”|
|- [Usuário](lexicos.md#l19) clica em anexar um arquivo|
|- [Usuário](lexicos.md#l19) seleciona o arquivo desejado|
|- [Usuário](lexicos.md#l19) envia o arquivo|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C10

|**Alterar status do perfil**|
|--|
|**Objetivo** |
| Alterar o status de uma conta existente no app Rocket.Chat entre um dos 4 existentes |
|**Contexto** |
| Local: Aba lateral do Rocket.Chat |
| Tempo: A qualquer momento após uma conta ter sido criada |
| Pré-condição: Estar conectado à internet, possuir conta no Rocket.Chat |
| Pós-condição: O status será diferente do status inicial |
|**Atores** |
|  Usuário com conta no Rocket.Chat |
|**Recursos** |
| Internet|
| Celular |
| Conta ativa no Rocket.Chat |
|**Restrição**|
|  Conexão de baixa qualidade com a internet |
|**Exceção** |
| Internet cair |
| Usuário selecionar o status que já possuía anteriormente |
| Usuário cancelar a ação |
| App parar de funcionar |
|**Episódios** |
| Um usuário que já possui uma conta no Rocket.Chat deseja alterar seu status dentro do app |
| Usuário clica na aba lateral do aplicativo |
| Usuário visualiza uma lista com os status disponíveis |
| Usuário escolhe um status entre as opções Online, Ausente, Ocupado e Invisível |
| O usuário agora tem um novo status |
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
|- Transmitir aos outros integrantes da conversa uma mensagem, que pode conter texto, Emojis, arquivos de mídia, documentos, áudios gravados pelo app, e desenhos digitais feitos pelo menu do app.|
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
|- O [usuário](lexicos.md#l19) conseguir anexar todos os arquivos que quer|
|**Exceção** |
|- Queda da internet|
|- [Usuário](lexicos.md#l19) cancela a ação|
|- Mensagem do [usuário](lexicos.md#l19) está acima do limite de caracteres|
|**Episódios** |
|- [Usuário](lexicos.md#l19) entra logado no [servidor](lexicos.md#l18)|
|- [Usuário](lexicos.md#l19) entra no [channel](lexicos.md#l1) desejado |
|- [Usuário](lexicos.md#l19) digita a mensagem no campo de texto|
|- [Usuário](lexicos.md#l19) anexa todos os arquivos que quiser na mensagem|
|- [Usuário](lexicos.md#l19) insere um Emoji se quiser|
|- [Usuário](lexicos.md#l19) envia a mensagem clicando no botão presente na caixa de texto para essa finalidade|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C13

|**Favoritar Mensagem**|
|--|
|**Objetivo** |
| Favoritar uma mensagem para que seja possível visualizá-la com mais facilidade posteriormente |
|**Contexto** |
| Local: Chat privado ou em grupo no Rocket.Chat |
| Tempo: A qualquer momento após um chat ser iniciado e possuir mensagens enviadas |
| Pré-condição: Estar conectado à internet, possuir conta no Rocket.Chat e estar em um chat que já possua mensagens enviadas |
| Pós-condição: A mensagem favoritada irá aparecer no menu de mensagens favoritas |
|**Atores** |
| Usuário participante de um chat |
|**Recursos** |
| Internet |
| Celular |
| Conta ativa no Rocket.Chat |
| Chat privado ou em grupo |
|**Restrição**|
| Conexão de baixa qualidade com a internet |
| Chat não possuir nenhuma mensagem ainda |
|**Exceção** |
| Internet cair |
| Usuário cancelar a ação |
| Usuário escolher opção errada |
| App parar de funcionar |
|**Episódios** |
| Um usuário participante de um chat deseja favoritar uma mensagem para que seja possível visualizá-la mais facilmente depois |
| O usuário abre uma conversa e clica na mensagem que deseja favoritar |
| Várias opções são exibidas ao usuário, dentre elas a opção de Favoritar, que pode ser identificada também pelo ícone de estrela |
| Usuário favorita a mensagem |
| Mensagem favoritada pode ser vista pelo menu de Mensagens Favoritas na aba de Detalhes do canal |
|**Levantado pela técnica**|
| - |

### C14

|**Visualizar membros de chat em grupo**|
|--|
|**Objetivo** |
| Visualizar membros participantes de determinado chat em grupo |
|**Contexto** |
| Local: Menu “Membros” dentro do menu “Detalhes do canal” em um chat em grupo |
| Tempo: A qualquer momento após um chat em grupo ser iniciado e possuir dois ou mais membros |
| Pré-condição: Estar conectado à internet, possuir conta no Rocket.Chat e estar em um chat em grupo |
| Pós-condição: Uma área com todos os membros pertencentes a um grupo é exibida |
|**Atores** |
| Usuário participante de um chat em grupo |
|**Recursos** |
| Internet |
| Celular |
| Conta ativa no Rocket.Chat |
| Chat em grupo |
|**Restrição**|
| Conexão de baixa qualidade com a internet|
| Chat não possuir membros ainda |
|**Exceção** |
| Internet cair|
| Usuário escolher opção errada|
| App parar de funcionar|
| Todos os membros saírem do chat em grupo |
|**Episódios** |
| Um usuário participante de um chat em grupo deseja ver quais os membros que também fazem parte daquele chat|
| O usuário abre uma conversa e clica no nome do grupo para abrir o menu de Detalhes do canal |
| Várias opções são exibidas ao usuário, dentre elas a opção de “Membros” |
| Usuário clica na opção Membros e uma lista é exibida com todos os usuários do grupo bem como seus respectivos status, fotos de perfil e nomes de usuário|
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
| Não ver mais uma sala e nem receber notificações da mesma|
|**Contexto** |
| -Local: Plataforma [Rocket.chat](lexicos.md#l65).|
| -Tempo: a qualquer momento, quando o surgir no [usuário](lexicos.md#l19) o desejo de deixar uma sala.|
| -Pré-condição: Estar conectado com a internet, ter o [Rocket.chat](lexicos.md#l65) baixado em seu computador, possuir um [usuário](lexicos.md#l19) na plataforma, estar presente no chat que deseja Esconder.|
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
| -Não participar de nenhum grupo |
| -Não possuir [Rocket.chat](lexicos.md#l65) versão desktop, nem [conta](lexicos.md#l67) na plataforma |
|**Episódios** |
| -Surge no [usuário](lexicos.md#l19) o desejo sair de esconder um grupo.|
| -O [usuário](lexicos.md#l19) abre a plataforma em seu computador.|
| -O [usuário](lexicos.md#l19) busca na área de [channels](lexicos.md#l1), o grupo no qual deseja se esconder.|
| -O [usuário](lexicos.md#l19) clica nos três pontos que surgem ao manter o cursor em cima do grupo.|
| -Após o clique, surgem diversas interações que podem ser realizadas com o grupo, dentre tais a de “esconder grupo”.|
| -O [usuário](lexicos.md#l19) clica na opção “ esconder grupo” e , com isso, esconde o grupo, passando a não receber mais atividades do mesmo, mas podendo restaurar a qualquer momento.|
|**Levantado pela técnica**|
|-|


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 19/04/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 21/04/2019 | 1.1 | Adição dos Cenários C5, C7, C8, C9, c12 | Marcos Nery |
| 21/04/2019 | 1.2 | Adição dos Cenários C1 - v1, C1 - v2, C2 - v1, C2 - v2, C15, C16, c12 | Gabriel Davi |
| 21/04/2019 | 1.3 | Adição do Cenário C11 | Lucas Maciel |
<<<<<<< 93385b14d74cdef434636303d1d7ccf43c22ab7c
| 21/04/2019 | 1.4 | Adição do Cenários C3, C4 | Heron Rodrigues |
=======
| 21/04/2019 | 1.4 | Adição dos Cenários C6, C10, C13, C14 | Weiller Fernandes |
>>>>>>> adding some Cenarios in cenarios.md document
