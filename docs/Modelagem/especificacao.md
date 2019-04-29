# Especificação de Caso de Uso

Aqui estão listadas as especificações de casos de uso, que, sendo baseadas cada uma em seu respectivo diagrama de caso de uso, buscam ilustrar de forma verbal e mais detalhada o expresso pelo diagrama.


## EC0

|**Título**|
|--|
| **Descrição**|
| |
| **Atores** |
| |
| **Pré Condições** |
| |
| **Fluxo Principal** |
| |
| **Fluxos Alternativos** |
| |
| **Fluxos de Exceção**|
| |
| **Pós Condições**|
| |
|**Requerimentos especiais**|
| |
| **Cenário** |
| |
|**Diagrama**|
|[DCU](diagramas.md#)|

## EC1

|**Fixar Mensagem**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo fazer com que o usuário consiga encontrar mensagens com mais facilidade, possui uma similaridade com a funcionalidade de favoritar mensagem |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - Usuário deve estar logado no aplicativo |
| - Usuário deve ser integrante em uma room no aplicativo |
| **Fluxo Principal** |
| 1 - Usuário seleciona seleciona uma room <br> 2 - Seleciona uma mensagem de seu interesse <br> 3 - Abre o menu de opções da mensagem <br> 4 - Seleciona a opção de "fixar mensagem" **[FE2]**|
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| __FE2__ - Mensagem foi apagada |
| **Pós Condições**|
| - As mensagens fixadas ficarão disponíveis em “mensagens fixadas” localizada no menu principal da [room](lexicos.md#l51) |
| **Cenário** |
| - [Fixar Mensagem](cenarios.md#c11) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC2

|**Mudar privacidade do Channel**|
|--|
|**Descrição**|
| - Funcionalidade com objetivo de mudar a [privacidade do channel](lexicos.md#l72), fazendo com que o mesmo quando for privado possa se tornar público, permitindo a entrada de qualquer usuário ou quando for público se tornar privado, impedindo a entrada de usuários sem convites |
|**Atores**|
| - [Usuário](lexicos.md#l19) dono do grupo |
| - [Usuário](lexicos.md#l19) criador do grupo |
|**Pré-Condições**|
| - [Usuário](lexicos.md#l19) deve estar lógado |
| - [Usuário](lexicos.md#l19) deve possuir internet com conexão de mínima qualidade |
| - [Usuário](lexicos.md#l19) deve ser dono do grupo ou criador do grupo|
|**Fluxo Principal**|
| 1 - Usuário abre o aplicativo e faz login <br> 2 - Usuário seleciona um canal <br> 3 - criador clica em informações da sala na parte superior direita da janela do canal <br> 4 - Clica em editar no canto inferior esquerdo do modal <br> 5 - Na opção Publico/Privado o usuário dono do canal ou criador muda o estado de privacidade clicando no radio button <br> 6 - Usuário clica em salvar no canto inferior direito para salvar a mudança |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| **Pós Condições**|
| - A [privacidade do channel](lexicos.md#l72) é alterada para a aposta a anterior |
| **Cenário** |
| - [Mudar privacidade do Channel](cenarios.md#c26) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC3

|**Criar only-read channel**|
|--|
|**Descrição**|
| - Funcionalidade com objetivo de criar um [only-read channel](lexicos.md#69), que é um canal o qual os usuários que não sejam o usuário criador do channel não podem enviar mensagem, apenas ler |
|**Atores**|
| - [Usuário](lexicos.md#l19)|
|**Pré-Condições**|
| - [Usuário](lexicos.md#l19) deve estar lógado |
|**Fluxo Principal**|
| 1 - Usuário abre o aplicativo e faz login <br> 2 - Usuário perta no menu lateral do aplicativo no canto superior esquerdo <br> 3 - Usuário clica no botão Criar chat <br> 4 - Usuário seleciona a opção Read only channel e cria o channel |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| **Pós Condições**|
| - Um [only-read channel](lexicos.md#69) é criado |
| **Cenário** |
| - [Criar only read Channel](cenarios.md#c21) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC4

|**Alterar Status**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo permitir com que o [usuário](lexicos.md#l19) possa trocar seu status para mostrar sua disponibilidade dentro do app|
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) no aplicativo |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| **Fluxo Principal** |
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre a aba lateral do app <br> 3 - Usuário clica no nome de usuário <br> 4 - Usuário escolhe um dos status disponíveis **[FA1][FA2][FA3]** <br> 5 - Usuário escolhe status online <br> 6 - Usuário tem um novo status|
| **Fluxos Alternativos** |
| __FA1__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status ausente <br> 2 - Usuário tem um novo status |
| __FA2__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status Ocupado <br> 2 - Usuário tem um novo status |
| __FA3__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status Invisível <br> 2 - Usuário tem um novo status |
| **Fluxos de Exceção**|
| __FE1__ - Pode ocorrer em qualquer momento da ação<br>1 - Erro de conexão |
| **Pós Condições**|
| - O status será diferente do status inicial |
| **Cenário** |
| - [Alterar Status](cenarios.md#c10) |
|**Diagrama**|
|[DCU](diagramas.md#dcu4-v1)|


## EC5

|**Deletar Conta**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo permitir com que o [usuário](lexicos.md#l19) possa excluir sua conta do Rocket.Chat |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) no aplicativo |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| **Fluxo Principal** |
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre a aba lateral do app <br> 3 - Usuário abre o perfil <br> 4 - Usuário clica em "Deletar Conta"**[FA1]** <br> 5 - Usuário digita senha**[FA1][FE2]** <br> 6 - Usuário clica em "Deletar Conta" novamente <br> 7 - Usuário tem sua conta deletada |
| **Fluxos Alternativos** |
| __FA1__ - Nos passos 4 ou 5 do fluxo principal <br> 1 - Usuário clica em cancelar <br> 2 - A conta do usuário é mantida |
| **Fluxos de Exceção**|
| __FE1__ - Pode ocorrer em qualquer momento da ação<br>1 - Erro de conexão |
| __FE2__ - No passo 5 do fluxo principal <br> 1 - Usuário digita sua senha errado <br> 2 - A conta do usuário é mantida |
| **Pós Condições**|
| - A conta será deletada com sucesso |
| **Cenário** |
| - [Deletar Conta](cenarios.md#c6) |
|**Diagrama**|
|[DCU](diagramas.md#dcu5-v1)|


## EC6

|**Mensagens Favoritadas**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo permitir com que o [usuário](lexicos.md#l19) possa favoritar mensagens de um determinado channel e visualizar as mensagens favoritadas |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) no aplicativo |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| - [Usuário](lexicos.md#l19) deve estar participando de algum channel que possua mensagens enviadas |
| **Fluxo Principal** |
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre um channel**[FA1][FE2]** <br> 3 - Usuário clica em uma mensagem**[FA2]** <br> 4 - Usuário clica em "Favoritar" <br> 5 - Mensagem é favoritada |
| **Fluxos Alternativos** |
| __FA1__ - No passo 2 do fluxo principal <br> 1 - Usuário clica no nome do channel <br> 2 - Usuário clica em "Mensagens Favoritas" <br> 3 - Usuário visualiza as mensagens favoritadas |
| __FA2__ - No passo 3 do fluxo principal <br> 1 - Usuário clica em "Desfavoritar Mensagem" <br> 2 - Mensagem é desfavoritada |
| **Fluxos de Exceção**|
| __FE1__ - Pode ocorrer em qualquer momento da ação<br>1 - Erro de conexão |
| __FE2__ - No passo 2 do fluxo principal <br> Channel não possui nenhuma mensagem |
| **Pós Condições**|
| - A mensagem favoritada irá aparecer no menu de mensagens favoritas e será identificada dentro do chat por um ícone de estrela |
| **Cenário** |
| - [Favoritar Mensagem](cenarios.md#c13) |
|**Diagrama**|
|[DCU](diagramas.md#dcu6-v1)|



## EC7

|**Visualizar membros de chat em grupo**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo permitir com que o [usuário](lexicos.md#l19) possa visualizar os membros participantes de determinado chat em grupo bem como visualizar seus status, fotos de perfil e nomes de usuário |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) no aplicativo |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| - [Usuário](lexicos.md#l19) deve estar participando de algum chat em grupo |
| **Fluxo Principal** |
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre um channel em grupo <br> 3 - Usuário clica no nome do channel <br> 4 - Usuário clica em "Membros"**[FE2]** <br> 5 - Usuário visualiza os membros do grupo e suas informações**[FA1][FA2]** |
| **Fluxos Alternativos** |
| __FA1__ - No passo 5 do fluxo principal <br> 1 - Usuário clica em um determinado membro do grupo <br> 2 - Usuário envia mensagem privada para o membro do grupo |
| __FA2__ - No passo 5 do fluxo principal <br> 1 - Usuário clica em um determinado membro do grupo <br> 2 - Usuário inicia videochamada com o membro do grupo |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| __FE2__ - No passo 4 do fluxo principal <br> Channel não possui nenhum membro |
| **Pós Condições**|
| - Usuário pode visualizar todos os membros pertencentes a determinado chat em grupo |
| **Cenário** |
| - [Visualizar Membros de Chat em Grupo](cenarios.md#c14) |
|**Diagrama**|
|[DCU](diagramas.md#dcu7-v1)|


## EC8

|**Definir membro do [channel](lexicos.md#l1) como proprietário**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo definir um usuário do channel como dono do mesmo, com a finalidade de aumentar suas permissões sobre o [channel](lexicos.md#l1) e assim poder administra-lo |
|**Atores**|
| - Usuário criador do channel |
| - Usuário que participa do channel |
|**Pré-Condição**|
| - O [channel](lexicos.md#l1) deve possuir mais do que um participante |
| - O usuário criador do [channel](lexicos.md#l1) deve ainda fazer parte do channel |
|**Fluxo Principal**|
| 1 - Usuário criador do channel abre o aplicativo e faz login <br> 2 - Usuário procura o channel criado por ele <br> 3 - Usuário criador do channel entra no channel criado por ele <br> 4 - Usuário criador do channel clica na lista de membros na parte superior direita <br> 5 - Usuário criador do channel clica nos tres pontos ao lado do [usuário](lexicos.md#l19) o qual deseja tornar proprietário do channel |
|**Fluxos Alternativos**|
| __FA1__ - No passo 2 o criador do channel procura seu channel pela funcionalidade de busca no canto superior direito |
|**Fluxos de Excessão**|
| __FE1__ - Sem conexão com a internet |
| __FE2__ - No passo 2 o usuário não consegue achar o channel pois ele foi apagado |
| __FE3__ - No passo 4 o usuário criardor não consegue definir um novo propriétario pois outro proprietário retirou sua permissão |
|**Pós-Condição**|
| - Usuário selecionado se torna proprietário do grupo |
|**Cenário**|
| [Definir membro de channel como proprietário](cenarios.md#c23) |
|**Diagrama**|
|[DCU](diagramas.md#)|


##EC9

|**Escolher tom de pele padrão**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo definir o tom de pele padrão dos emojis para assim poder transmitir com mais representatividade os sentimentos expressados pelos mesmos |
|**Atores**|
| - [Usuário](lexicos.md#l19) |
|**Pré-Condição**|
| - O [usuário](lexicos.md#l19) deve estar logado |
| - O [usuário](lexicos.md#l19) deve possuir conexão com a internet |
|**Fluxo Principal**|
| 1 - Usuário abre o aplicativo e faz login <br> 2 - Usuário abre uma conversa privada <br> 3 - Usuário clica no simbolo de emoji presente no canto inferior direito <br> 4 - Usuário clica no circulo amarelo abaixo dos [emojis](lexicos.md#l7), no conto inferior direito <br> 5 - [Usuário](lexicos.md#l19) escolhe a cor de pele padrão <br> 6 - Usuário retorna a conversa |
|**Fluxos ALternativos**|
| __FA1__ - No passo 2 do fluxo principal o usuário seleciona um channel ao invés de uma conversa privada |
| __FA2__ - No passo 6 o usuário retorna ao channel ao invés da conversa caso tenha usado o __FA1__ |
|**Fluxo de Excessão**|
| __FE1__ - Sem conexão com a internet |
|**Pós-Condição**|
| - Os emojis quando clicados aparecerão com o tom de pele escolhido pelo usuário |
|**Cenário**|
| [Escolher tom de pele padrão](cenarios.md#c21) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC10

|**Criar channel**|
|--|
| **Descrição**|
|- Funcionalidade que permite o usuário criar um novo [channel](lexicos.md#l1) |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve estar [logado](lexicos.md#l62) no aplicativo |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| **Fluxo Principal** |
| 1 - Usuário acessa a pagina inicial <br> 2 - Usuário abre a aba lateral do app <br> 3 - Usuário clica em "Criar chat" <br> 4 - Usuário define se o channel será publico **[FA1]** <br> 5 - Usuário escolhe se o channel será somente para leitura <br> 6 - Usuário define o nome do channel **[FE1]** <br> 7 - Usuário convida membros do channel **[FA2]** <br> 8 - Clica no botão "check" no canto superior direito |
| **Fluxos Alternativos** |
| __FA1__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe se o channel será privado |
| __FA2__ - No passo 7 do fluxo principal <br> 1 - Usuário pode criar um channel sem outros membros |
| **Fluxos de Exceção**|
| __FE1__ - Pode ocorrer em qualquer momento da ação<br>1 - Erro de conexão |
| __FE2__ - No passo 6 do fluxo principal <br> 1 - Usuário não define o nome do channel <br> 2 - Botão "check", não estará disponivel |
| **Pós Condições**|
| - [Channel](lexicos.md#l1) estará criado |
| **Cenário** |
| - [Criar channel](cenarios.md#c3-v2)|
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC11

|**Conectar com um servidor**|
|--|
| **Descrição**|
| - Funcionalidade que permiti o usuário iniciar conexão com uma instância do [Rocket.chat](lexicos.md#l65)  |
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - [Usuário](lexicos.md#l19) deve possuir acesso á internet |
| **Fluxo Principal** |
| 1 - Usuário acessa a pagina inicial <br> 2 - Usuário clica em "Conectar com um servidor" <br> 3 - Usuário define o protocolo de conexão **[FA1] [FA2]** <br> 4 - Usuário insere o endereço do servidor **[FE1]** <br> 5 - Usuário clica em “Conectar” **[FE2]** |
| **Fluxos Alternativos** |
| __FA1__ - No passo 3 do fluxo principal <br> 1 - Usuário escolhe o protocolo de conexão "https" |
| __FA2__ - No passo 3 do fluxo principal <br> 1 - Usuário escolhe o protocolo de conexão "http" |
| **Fluxos de Exceção**|
| __FE1__ - No passo 4 do fluxo principal <br>1 - Usuário insere um endereço de servidor inválido <br> 2 - Será mostrado ao usuário um aviso com o erro |
| __FE2__ - No passo 5 do fluxo principal <br>1 - Erro de conexão|
| **Pós Condições**|
| - Usuário estará conectado com um servidor |
| **Cenário** |
| - [Conectar com um servidor](cenarios.md#c4-v2) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC12

|**Visualizar Mensagem Fixada**|
|--|
| **Descrição**|
| - Encontrar Mensagens que foram fixadas |
| - Acesso rápido a mensagens do interesse do [usuário](lexicos.md#l19) |
| **Atores** |
| - Usuário Membro em uma Room |
| **Pré Condições** |
| - Usuário deve estar logado no aplicativo |
| - Usuário deve ser integrante em uma room no aplicativo |
| **Fluxo Principal** |
| 1 - Usuário seleciona seleciona uma room <br> 2 - Seleciona o Menu de Opções da Room <br> 3 - Seleciona opção de "Mensagens Fixadas" ou "Pinned Messages" para visualizar as mensagens **[FE2]** |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| __FE2__ - Mensagem fixada foi deletada |
| **Pós Condições**|
| - Usuário estará conectado com um servidor |
| **Cenário** |
| - [Conectar com um servidor](cenarios.md#c4-v2) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC13

|**Pesquisa de mensagem**|
|--|
| **Descrição**|
| - Funcionalidade que permite utilizar uma mensagem como base de pesquisa para encontrar mensagens desejadas.|
| **Atores** |
| - [Usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - Usuário possuir conta no [Rocket.chat](lexicos.md#l65) <br> - Usuário ter em mente as mensagens a serem pesquisadas |
| **Fluxo Principal** |
| 1- Usuário acessa o aplicativo <br> 2- Na página inicial seleciona um channel <br> 3- Usuário clica na "Lupa" no canto superior <br> 4- Usuário digita a mensagem que deseja pesquisar **[FA1]** <br> 5- Mensagens relacionadas ao que foi pesquisado são retornadas para o usuário <br> 6- A pesquisa é realizada com sucesso **[FE1]** **[FE2]**|
| **Fluxos Alternativos** |
| **[FA1]** - Ocorre no passo 4 do fluxo principal |
| - O usuário não especifica bem o termo para pesquisa de mensagem <br> - São retornadas várias mensagens semelhantes a pesquisa |
| **Fluxos de Exceção**|
| **[FE1]** Ocorre no passo 6 do fluxo principal <br> - São retornadas mensagens que não correspondem a pesquisada pelo usuário <br> - A pesquisa é finalizada|
|  **[FE2]** Ocorre no passo 6 do fluxo principal <br> - Nada é retornado, a mensagem pesquisada foi apagada ou não existe <br> - A pesquisa é finalizada|
| **Pós Condições**|
| - São retornadas mensagens relacionadas as pesquisadas pelo usuário|
| **Cenário** |
| - [Pesquisar mensagem](cenarios.md#c17) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC14

|**Realização de login**|
|--|
| **Descrição**|
| - Fazer login no [Rocket.chat](lexicos.md#l65) para ter acesso a todas as funcionalidades disponíveis para [usuário](lexicos.md#l19) [logado](lexicos.md#l62)  |
| **Atores** |
| - [Usuário](lexicos.md#l19) |
| **Pré Condições** |
| - Usuário possuir o Rocket.chat instalado <br> - Usuário deve ter acesso a internet <br> - Usuário deve possuir uma conta de e-mail ou de alguma rede social |
| **Fluxo Principal** |
| 1- Usuário entra na página de login do aplicativo **[FA1][FA2][FA3][FA4] [FE1][FE2][FE3]]**<br> 2- Usuário usa um e-mail e senha válidos **[FE1][FE2][FA5]**<br> 3- Usuário obtem acesso e é direcionado para página inicial|
| **Fluxos Alternativos** |
| **[FA1]** - Ocorre no passo 1 do fluxo principal <br> - Usuário faz o login com o **Facebook** <br> - Usuário é redirecionado para página principal |
| **[FA2]** - Ocorre no passo 1 do fluxo principal <br> - Usuário faz o login com o **Google** <br> - Usuário é redirecionado para página principal |
| **[FA3]** - Ocorre no passo 1 do fluxo principal <br> - Usuário faz o login com o **Github** <br> - Usuário é redirecionado para página principal |
| **[FA4]** - Ocorre no passo 1 do fluxo principal <br> - Usuário criar uma nova conta com e-mail <br> - Usuário cadastra e-mail e senha de acesso <br> - Usuário é redirecionado para página principal |
| **[FA5]** - Ocorre no passo 2 do fluxo principal <br> - Usuário não se lembra da senha de acesso <br> - Usuário clica em "Esqueci minha senha" e é redirecionado para criar uma nova senha |
| **Fluxos de Exceção**|
| **[FE1]** - Ocorre no passo 1 do fluxo principal <br> - Usuário não tem permissão de acesso a conta do **Facebook** <br> - Usuário retorna a página de login |
| **[FE1]** - Ocorre no passo 1 do fluxo principal <br> - Usuário não tem permissão de acesso a conta do **Google** <br> - Usuário retorna a página de login |
| **[FE1]** - Ocorre no passo 1 do fluxo principal <br> - Usuário não tem permissão de acesso a conta do **Github** <br> - Usuário retorna a página de login |
| **[FE1]** - Ocorre no passo 2 do fluxo principal <br> - Usuário digita um e-mail inválido <br> - Usuário retorna a página de login |
| **[FE2]** - Ocorre no passo 2 do fluxo principal <br> - Usuário digita uma senha inválida <br> - Usuário retorna a página de login |
| **Pós Condições**|
| - Acessar o aplicativo e todas as funcionalidades disponíveis para usuário logado|
| **Cenário** |
| - [Fazer login](cenarios.md#c17) |
|**Diagrama**|
|[DCU](diagramas.md#)|


## EC15

|**Enviar mensagem**|
|--|
| **Descrição**|
| Descrição Enviar uma mensagem em uma conversa para um usuário ou grupo de usuários. |
| **Atores** |
| Usuário Logado.|
| **Pré Condições** |
| O usuário ter conta no aplicativo e estar dentro do channel. |
| **Fluxo Principal (FE)** |
|1- Entrar na sua lista de channels no aplicativo.|
|2- Entrar no channel desejado.|
|3- Digitar o texto da mensagem|
|4- Enviar mensagem|
| **Fluxos Alternativos** |
|*FA1* - Procurar por channel fora da lista. **[FP-1]**|
|*FA2* - Selecionar mensagem para [responder](#ec38) **[FP -2]**|
|*FA3* - [Anexar arquivo](#ec16)  **[FP -2]**|
| **Fluxos de Exceção**|
| *FE1* - Queda de conexão **[Todo o processo]**|
| *FE2* - Numero máximo de caractéres excedido **[FP-4]**|
| **Pós Condições**|
| A mensagem enviada pelo usuário poderá ser vista no channel pelos outros usuários membros.|
|**Requerimentos especiais**|
| O limite máximo de caractéres deve ser satisfatório.|
| As ferramentas de edição e formatação do texto devem oferecer grande quantidade de recursos.|
| **Cenário** |
| **[Enviar mensagem](cenarios.md#c12)** |
|**Diagrama**|
|[DCU2-V3](diagramas.md#dcu2-v3)|


## EC16

|**Anexar arquivo**|
|--|
| **Descrição**|
|Anexar um arquivo de mídia, como uma foto ou vídeo, a mensagem. |
| **Atores** |
| Usuário Logado.|
| **Pré Condições** |
| O usuário ter conta no aplicativo e estar dentro do channel. |
| **Fluxo Principal (FE)** |
|1- Entrar na sua lista de channels no aplicativo.|
|2- Entrar no channel desejado.|
|3- Clicar no botão de "anexar arquivo" dentro da caixa de texto.|
|4- Selecionar o tipo de arquivo a ser anexado. |
|5- Confirmar o arquivo.|
| **Fluxos Alternativos** |
|*FA1* - Procurar por channel fora da lista. **[FP-1]**|
|*FA2* -  Seleciona o tipo "Tirar Foto" **[FP-4]**|
| 1- Tirar foto com a câmera|
| 2- Confirmar foto tirada  |
|*FA3* -  Seleciona o tipo "Arquivo"  **[FP-4]**|
| 1- Vai até a lista de arquivos do dispositivo|
| 2- Seleciona o arquivo desejado |
|*FA4* -  Seleciona o tipo "Desenho" **[FP-4]**|
| 1- [Anexa um desenho](#ec17)|
| **Fluxos de Exceção**|
| *FE1* - Queda de conexão **[Todo o processo]**|
| *FE2* - Formato de arquivo não suportado **[FA3-2]**|
| *FE3* - Falha no envio **[FA3-2]**|
| **Pós Condições**|
| O usuário terá em sua mensagem o arquivo anexado.|
|**Requerimentos especiais**|
| Uma grande quantidade de formatos de arquivo deve ser suportada.|
| **Cenário** |
| **[Anexar um arquivo](cenarios.md#c9)** |
|**Diagrama**|
|[DCU18](diagramas.md#18-v1)|


## EC17

|**Anexar desenho**|
|--|
| **Descrição**|
|Anexar um dsenho digital, feito na plataforma, a mensagem|
| **Atores** |
| Usuário Logado|
| **Pré Condições** |
|O usuário ter conta no aplicativo e estar dentro do channel|
| **Fluxo Principal** |
|1- Logar no servidor|
|2- Clicar no channel desejado|
|3- Clicar no botão de anexar arquivo|
|4- Seecionar a opção desenho|
|5- Desenhar|
|6- Confirmar desenho|
| **Fluxos Alternativos (FA)** |
| *FA1* - Procurar por channel fora da lista. **[FP-1]**|
| **Fluxos de Exceção**|
| *FE1* - Queda de conexão **[Todo o processo]**|
| **Pós Condições**|
|O usuário poderá enviar a mensagem com o desenho anexado|
|**Requerimentos especiais**|
| A plataforma deve oferecer uma interface intuitíva de desenho, que ofereça ferramentas como coloração, apagador e tipo do pincel.|
| **Cenário** |
| **[Anexar um desenho](cenarios.md#c8)**|
|**Diagrama**|
|[DCU18](diagramas.md#dcu18-v1)|


## EC18

|**Responder mensagem**|
|--|
| **Descrição**|
| Enviar uma mensagem que responde especificamente a uma outra mensagem, de forma explícita|
| **Atores** |
| Usuário logado|
| **Pré Condições** |
| O usuário ter conta no aplicativo e estar dentro do channel|
| **Fluxo Principal** |
|1- Logar no servidor|
|2- Clicar no channel desejado|
|3- Clicar na mensagem que deseja responder|
|4- Clicar na função responder|
|5- Escrever e [envia a mensagem](#ec15)|
| **Fluxos Alternativos (FA)** |
| *FA1* - Procurar por channel fora da lista. **[FP-1]**|
| *FA2* - Pesquisar por uma mensagem no channel.**[FP-2]**|
| **Fluxos de Exceção**|
| *FE1* - Queda de conexão **[Todo o processo]**|
| *FE2* - Mensagem foi apagada **[FP-3]**|
| **Pós Condições**|
| A resposta enviada pelo usuário será mostrada no channel com o anexo da mensagem respondida abaixo|
|**Requerimentos especiais**|
| - |
| **Cenário** |
| **[Responder uma mensagem](cenarios.md#c7)** |
|**Diagrama**|
|[DCU20](diagramas.md#dcu20-v1)|


## EC19

|**Editar Mensagem**|
|--|
| **Descrição**|
| Usuário editar o conteúdo textual de uma mensagem para exprimir uma ideia diferente da anterior|
| **Atores** |
| Usuário logado|
| **Pré Condições** |
| O usuário ter conta no aplicativo e estar dentro do channel|
| **Fluxo Principal (FP)** |
|1-  Ir até a lista de channels|
|2-  Ir até o channel desejado|
|3-  Clicar na mensagem que deseja editar|
|4-  Clicar na opção editar|
|5-  Entrar no modo de edição de mensagem|
|6-  Clicar no botão enviar, fnalizando a edição|
| **Fluxos Alternativos (FA)** |
| *FA1* - Procurar por channel fora da lista. **[FP-1]**|
| *FA2* - Pesquisar por uma mensagem no channel.**[FP-2]**|
| **Fluxos de Exceção**|
| *FE1* - Queda de conexão **[Todo o processo]**|
| *FE2* - Mensagem foi apagada **[FP-6]**|
| **Pós Condições**|
| A dada mensagem no channel será mostrada com o conteúdo editado e um identificador contendo a palavra “Editada”|
|**Requerimentos especiais**|
| A interface para editar mensagens deve conter tantos recursos quanto a de enviar.|
| **Cenário** |
| **[Editar uma Mensagem](cenarios.md#c5)** |
|**Diagrama**|
|[DCU19](diagramas.md#dcu19-v1)|

## EC20

|**Realizar video Chat**|
|--|
| **Descrição**|
| Comunicação a distância e online entre um grupo de usuários do Rocket.chat|
| **Atores** |
| -Usuário logado criador da sala de video chat|
| -Participantes do grupo |
| **Pré Condições** |
|-Possuir o Rocket.chat instalado em seu computador/celular|
|-Todos os participantes estarem  logados em suas respectivas contas|
|-Participar de um grupo dentro da plataforma|
|-Possuir acesso a internet|
| **Fluxo Principal** |
| 1. Usuários abrem o Rocket.chat em seu computador ou celular<br>2. Usuários procuram um grupo na área lateral da página inicial**[FA1][FE1]**<br>3. Usuários clicam no canal e o acessa**[FA2]**<br>4. Usuário criador do video chat manda o convite para acesso de uma sala de video conferência<br>5. Participantes do grupo aceitam o convite **[FA3][FE2]**|
| **Fluxos Alternativos** |
| **FA1** -No passo 2 do fluxo principal<br>1 - Usuário pode clicar na ferramenta de pesquisa<br>2 - Usuário digita o nome do grupo que deseja<br>3 - Usuário seleciona o grupo, se o mesmo for encontrado **[FE1]**|
|**FA2** - no passo 3 do fluxo principal<br>1- usuário pode entrar no chat<br>2- Usuário Desliza a tela para cima<br>3- Usuário lê os comentários anteriores|
|**FA3** - No passo 5 do fluxo principal<br>1 - O usuário recebe o convite<br>2 - O usuário não entra na sala, ignorando o convite|
| **Fluxos de Exceção**|
|**FE1** - Pode acontecer no fluxo principal  2 ou no fluxo alternativo 1 passo 3:<br>1 -  Não encontrar a sala para a video conferencia|
|**FE2** - pode ocorrer no fluxo principal 5<br>1- sala de videio chat atingir um numero limite de participante|
|**FE3** - pode ocorrer a qualquer momento da ação<br>1- internet cair no do decorrer do video chat|
| **Pós Condições**|
|-Realização da video conferencia bem sucedida  |
|**Requerimentos especiais**|
|- Para cada interação com o usuário, um convite de video chat é enviado por vez|
| **Cenário** |
|[Realizar video chat](cenarios.md#c2-v2) |
|**Diagrama**|
|[DCU](diagramas.md#dcu1-v2)|

## EC21

|**Cadastrar novo usuário**|
|--|
| **Descrição**|
|-Um usuário irá criar sua conta na plataforma|
| **Atores** |
|-Usuário não cadastrado |
| **Pré Condições** |
|-Possuir internet |
|-Possuir possuir email |
|-Ter acesso a plataforma em seu computador/celular |
| **Fluxo Principal** |
|1. Usuário acessa a página inicial de login<br>2. Usuário clica em registrar nova conta<br>3. Usuário acessa página de cadastro**[FA1]**<br>4. Usuário faz o cadastro pelo formulário**[FA2]**<br>5. Usuário preeche o campo de nome**[FE1]**<br>6. O usuário preenche o campo de email**[FE2]**<br>7. Usuário preenche o campo de senha**[FE3]**<br>8. Usuário preeche o campo de confirmação de senha**[FE4]**|
| **Fluxos Alternativos** |
|**FA1** - No passo 3 do fluxo principal:<br>1. O usuário pode clicar em "retornar para a página de login" e retornar para a página de login|
|**FA2** - No passo 4 do fluxo princial:<br>1. O usuário pode criar sua conta usando redes sociais**[FE5]**<br>1.1 usuário pode cadastrar usando o facebook<br>1.2 usuário pode cadastrar usando o Google + <br>1.3 usuário pode cadastrar usando o Twitter<br>1.4 usuário pode cadastrar usando o Github<br>1.5 usuário pode cadastrar usando o GitLab<br>1.6 usuário pode cadastrar usando o meteor<br>|
| **Fluxos de Exceção**|
|**FE1** - No passo 5 do fluxo principal<br>1. O campo  de nome opde estar em branco|
|**FE2** - No passo 6 do fluxo principal<br>1. Campo de email pode estar em branco ou o email pode ser inexistente|
|**FE3** - No passo 7 do fluxo principal<br>1. Senha fraca ou campo em branco|
|**FE4** - No passo 8 do fluxo princial<br>1. Campo de confirmação de senha não coincide com o campo de senha|
|**FE5** - No FA2<br>1. Rede social informada incorreta|
|**FE6** - Em qualquer momento da interação<br>1. Pode ocorrer falaha na conexão|
| **Pós Condições**|
|- Usuário passa a possuir uma nova conta no  Rocket.chat|
|**Requerimentos especiais**|
|- Os passos 5, 6 e 7 do fluxo principal não precisa seguir a ordem informada|
| **Cenário** |
|[Cadastrar um novo usuário](cenarios.md#c1-v2) |
|**Diagrama**|
|[DCU](diagramas.md#21)|

## EC22

|**Deixar Grupo**|
|--|
| **Descrição**|
|- O usuário sai de um grupo, passando a não receber mais notificações do mesmo |
| **Atores** |
|- usuário logado |
| **Pré Condições** |
|- Possuir conta no Rocket.chat |
|- Estar logado a uma conta no Rocket.chat |
|- Participar de um grupo  |
|- Possuir acesso a internet  |
| **Fluxo Principal** |
|1.Entrar na página inical do rocket.chat<br>2. Buscar o grupo no  qual deseja sair pela barra lateral onde se encontram os grupos**[FA1][FE2]**<br>2. Clicar nos 3 pontos ao lado do ícone do grupo<br>3. Escolher entre as opções mostradas a de "Deixar grupo"<br>4. Confirmar a retirada do grupo**[FA2]** |
| **Fluxos Alternativos** |
| **FA1** - No passo 2 do fluxo principal<br>1. O usuário pode pesquiser o grupo usando a ferramenta de pesquisa|
| **FA2** - No passo 4 do fluxo principal<br>1. O usuário pode clicar em cancelar|
| **Fluxos de Exceção**|
|**FE1** - Em qualquer momento da interação<br>1. Pode ocorrer falaha na conexão|
|**FE2** - No passo2 do fluxo principal:<br>1. O grupo pode não ser encontrado |
| **Pós Condições**|
|- Usuário não mais participa do grupo|
|**Requerimentos especiais**|
|- |
| **Cenário** |
| [Sair de um channel](cenarios.md#c15-v1)|
|**Diagrama**|
|[DCU](diagramas.md#dcu22-v1)|

## EC23

|**Esconder Grupo**|
|--|
| **Descrição**|
|- O usuário esconde um grupo, passando a não receber mais notificações do mesmo |
| **Atores** |
|- usuário logado |
| **Pré Condições** |
|- Possuir conta no Rocket.chat |
|- Estar logado a uma conta no Rocket.chat |
|- Participar de um grupo  |
|- Possuir acesso a internet  |
| **Fluxo Principal** |
|1.Entrar na página inical do rocket.chat<br>2. Buscar o grupo no  qual deseja esconder pela barra lateral onde se encontram os grupos**[FA1][FE2]**<br>2. Clicar nos 3 pontos ao lado do ícone do grupo<br>3. Escolher entre as opções mostradas a de "Esconder grupo"<br>4. Confirmar ação**[FA2]** |
| **Fluxos Alternativos** |
| **FA1** - No passo 2 do fluxo principal<br>1. O usuário pode pesquiser o grupo usando a ferramenta de pesquisa|
| **FA2** - No passo 4 do fluxo principal<br>1. O usuário pode clicar em cancelar|
| **Fluxos de Exceção**|
|**FE1** - Em qualquer momento da interação<br>1. Pode ocorrer falaha na conexão|
|**FE2** - No passo2 do fluxo principal:<br>1. O grupo pode não ser encontrado |
| **Pós Condições**|
|- Grupo possa e ser escondido|
|**Requerimentos especiais**|
|-|
| **Cenário** |
| [Sair de um channel](cenarios.md#c16-v1)|
|**Diagrama**|
|[DCU](diagramas.md#dcu23-v1)|


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 25/04/2019 | 1.0 | Abertura do documento | Gabriel Davi|
| 25/04/2019 | 1.1 | Inclusão do template para criação das especificações de casos de uso | Marcos Nery|
| 26/04/2019 | 1.2 | Adição da EC1 | Lucas Maciel |
| 28/04/2019 | 1.3 | Adição de EC2 e EC3 | João Lucas |
| 28/04/2019 | 1.4 | Adição da EC4, EC5, EC6 e EC7 | Weiller Fernandes |
| 28/04/2019 | 1.5 | Editando EC4, EC5, EC6 e EC7 | Gabriel Davi |
| 28/04/2019 | 1.6 | Adição EC8 e EC9 | João Lucas |
| 28/04/2019 | 1.7 | Adição EC10 e EC11 | Heron Rodrigues |
| 28/04/2019 | 1.8 | Adição EC12 | Lucas Maciel |
| 28/04/2019 | 1.9 | Adição EC13 e EC14 | André Lucas |
| 28/04/2019 | 2.0 | Adição de EC15 a EC19 | Marcos Nery |
| 29/04/2019 | 2.1 | Adição de EC20 a EC23 | Gabriel Davi |
