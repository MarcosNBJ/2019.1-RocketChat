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
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre a aba lateral do app <br> 3 - Usuário clica no nome de usuário <br> 4 - Usuário escolhe um dos status disponíveis <br> 5 - Usuário escolhe status online <br> 6 - Usuário tem um novo status|
| **Fluxos Alternativos** |
| __FA1__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status ausente <br> 2 - Usuário tem um novo status |
| __FA2__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status Ocupado <br> 2 - Usuário tem um novo status |
| __FA3__ - No passo 4 do fluxo principal <br> 1 - Usuário escolhe status Invisível <br> 2 - Usuário tem um novo status |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
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
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre a aba lateral do app <br> 3 - Usuário abre o perfil <br> 4 - Usuário clica em "Deletar Conta" <br> 5 - Usuário digita senha <br> 6 - Usuário clica em "Deletar Conta" novamente <br> 7 - Usuário tem sua conta deletada |
| **Fluxos Alternativos** |
| __FA1__ - Nos passos 4 ou 5 do fluxo principal <br> 1 - Usuário clica em cancelar <br> 2 - A conta do usuário é mantida |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
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
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre um channel <br> 3 - Usuário clica em uma mensagem <br> 4 - Usuário clica em "Favoritar" <br> 5 - Mensagem é favoritada |
| **Fluxos Alternativos** |
| __FA1__ - No passo 2 do fluxo principal <br> 1 - Usuário clica no nome do channel <br> 2 - Usuário clica em "Mensagens Favoritas" <br> 3 - Usuário visualiza as mensagens favoritadas |
| __FA2__ - No passo 3 do fluxo principal <br> 1 - Usuário clica em "Desfavoritar Mensagem" <br> 2 - Mensagem é desfavoritada |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
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
| 1 - Usuário acessa página inicial <br> 2 - Usuário abre um channel em grupo <br> 3 - Usuário clica no nome do channel <br> 4 - Usuário clica em "Membros" <br> 5 - Usuário visualiza os membros do grupo e suas informações |
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

## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 25/04/2019 | 1.0 | Abertura do documento | Gabriel Davi|
| 25/04/2019 | 1.1 | Inclusão do template para criação das especificações de casos de uso | Marcos Nery|
| 26/04/2019 | 1.2 | Adição da EC1 | Lucas Maciel |
| 28/04/2019 | 1.3 | Adição de EC2 e EC3 | João Lucas |
| 28/04/2019 | 1.4 | Adição da EC4, EC5, EC6 e EC7 | Weiller Fernandes |
