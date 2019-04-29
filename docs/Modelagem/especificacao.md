#Especificação de casos de uso

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

## EC1

|**Fixar Mensagem**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo fazer com que o usuário consiga encontrar mensagens com mais facilidade, possui uma similaridade com a funcionalidade de favoritar mensagem |
| **Atores** |
| - [usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - usuário deve estar logado no aplicativo |
| - usuário deve ser integrante em uma room no aplicativo |
| **Fluxo Principal** |
| 1 - Usuário seleciona seleciona uma room <br> 2 - Seleciona uma mensagem de seu interesse <br> 3 - Abre o menu de opções da mensagem <br> 4 - Seleciona a opção de "fixar mensagem" |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| **Pós Condições**|
| - As mensagens fixadas ficarão disponíveis em “mensagens fixadas” localizada no menu principal da [room](lexicos.md#l51) |
| **Cenário** |
| - [Fixar Mensagem](cenarios.md#c11) |


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

## EC11

|**Conectar com um servidor**|
|--|
| **Descrição**|
| - Funcionalidade que permiti o usuário iniciar conexão com uma instância do [Rocket.chat](lexicos.md#l65)  |
| **Atores** |
| - Usuário |
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
