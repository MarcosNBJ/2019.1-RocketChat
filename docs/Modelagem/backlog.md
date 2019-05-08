# Product Backlog

1. [T01 - Entrar no aplicativo](#t01-entrar-no-aplicativo)
    1. [EP01 - Fazer Login](#ep01-fazer-login)
    2. [EP02 - Fazer Cadastro](#ep02-fazer-cadastro)
2. [T02 - Channel](#t01-channel)
    1. [EP03 - Criar channel](#ep03-criar-channel)


## T01 - Entrar no aplicativo

### EP01 - Fazer Login

#### US01

| ID   | Eu, como | desejo | porque| comentário | pontos | prioridade |
|------|----------|--------|-------|------------|--------|------------|
| US01 | Usuário  | Fazer login na aplicação utilizando minha conta | gostaria de acessar as funcionalidades de um usuário logado | Deve haver um limite de tentativas | 5 | Must       |

* O usuário deverá ser capaz de utilizar uma conta previamente criada na aplicação para fazer login, digitando seu usuário e sua senha
* O usuário deverá conseguir utilizar o email no lugar do nome de usuário se preferir
* Se forem excedidas três tentativas sem sucesso de login com um nome de usuário, as tentativas devem ser bloqueadas temporariamente e o dono da conta deverá receber um email
* Quando o usuário errar os dados de entrada, ele deverá ser avisado se errou o nome ou a senha

_Originada em: [AP1](../Elicita%C3%A7%C3%A3o/analprot.md#requisitos-elicitados)_


#### US02

| ID   | Eu, como | desejo | porque  | Comentário | Pontos | Prioridade |
|------|----------|--------|---------|------------|--------|------------|
| US02 | Usuário  | Fazer login na aplicação utilizando minhas redes sociais | gostaria de acessar as funcionalidades de um usuário logado sem ter que criar uma nova conta | Login pelo facebook, google ou twitter| 5| Must|

* O usuário deverá ser capaz de fazer login no aplicativo utilizando uma conta que ele possui em uma dessas redes sociais: GitHub, Facebook, Twitter e Google

_Originada em: [INT1.3](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [AP1](../Elicita%C3%A7%C3%A3o/analprot.md#requisitos-elicitados)_

### EP02 - Fazer Cadastro

#### US03

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
|US03|Usuário|Criar uma conta no aplicativo|gostaria de ter uma conta para fazer login e acessar as funcionalidades do aplicativo|Cada usuário deve cadastrar um email, usuário e senha|8|Must|

* O usuário deverá ser capaz de criar uma conta no aplicativo, para conseguir fazer login posteriormente.
* As seguintes informações do usuário deverão ser requisitadas para cadastrar a conta: email, usuário, tag e senha.
* A tag deve ser única, cada usuário tendo a sua. E assim como o nome de usuário estar restrito a letras e números.
* A senha deverá conter um número mínimo de 6 caractéres, incluíndo letras maíusculas, minúsculas, números e caracteres especiais.
* Deverá aparecer uma mensagem clara de erro caso o usuário insira errado alguma das informações.
* Opcionalmente, o usuário deverá conseguir colocar uma foto para aparecer no seu perfil.

_Originada em: [AP10](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_


#### US04

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
|US04|Dono do servidor|Modificar as informações pedidas na criação de conta |gostaria de ter uma experiência mais customizada, adaptada as necessidades do meu grupo||8|Should|

* O dono do servidor deverá ser capaz de, ao criar o servidor, modificar quais informações são pedidas ao usuário quando o mesmo cria uma conta
* O dono do servidor deverá também conseguir mudar os critérios de aceitação de cada campo
* O dono do servidor deverá ser capaz de modificar essas definições a qualquer momento que desejar

_Originada em: [AP10](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_

## T02 - Channel

### EP03 - Criar channel

#### US05

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US05 | Usuário | Criar channel publico | para que todos possam procurar e ter acesso à esse channel | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |

- Deve ser disponibilizado para o usuário, a opção de criar channel publico
- Usuário pode criar número ilimitado de channels publicos
- Nome do channel deve ser obrigatório
- Qualquer tipo de caractere deve ser aceito para o nome do channel
- Nome do channel deve conter no mínimo um caractere
- Channel deve ser disponibilizado para qualquer usuário ter acesso, ao ser procurado na barra de pesquisa, na página inicial
- Não é necessário que convide membros durante a criação do channel

#### US06

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US05 | Usuário | Criar channel privado | para que seja acessado apenas por convite e visivel somente por seus membros | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |

- Por padrão, somente adminstradores e moderadores podem convidar novos membros
- Somente membros podem ter acesso à esse channel
- Usuário pode criar número ilimitado de channels privados
- Deve ser disponibilizado para o usuário, a opção de criar channel privado
- Nome do channel deve ser obrigatório
- Membros só podem ser adicionados, se forem convidados
- Qualquer tipo de caractere deve ser aceito para o nome do channel
- Administrador determina quem pode convidar membros
- Nome do channel deve conter no mínimo um caractere
- Não é necessário que convide membros durante a criação do channel

#### US07

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US05 | Usuário | Enviar mensagem direta | gostaria de enviar mensagens privadas para determinado usuário|  | 5 | Must |

- Conversa iniciada ao acessar o perfil de um usuário na lista de membros de um channel, ou ao procura-lo na barra de pesquisa, na página inicial

## T03 - Mensagem Enviada

### EP - Enviar Mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Enviar uma mensagem de texto | para poder me comunicar de forma escrita com os membros de um channel|  |  | Must |

* O usuário deverá ser capaz de enviar uma mensagem de texto para qualquer channel que ele faça parte
* A mensagem enviada deverá ser recebida por todos os membros que fazem parte daquele channel
* Não deve haver limite de caracteres para uma mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Enviar um arquivo | para poder enviar qualquer documento ou arquivo que esteja armazenado no meu dispositivo para os demais membros do channel| Este arquivo pode ser uma foto, vídeo, documento, áudio, etc |  | Must |

* Ao selecionar essa opção o usuário deverá buscar no armazenamento do seu dispositivo o arquivo que deseja enviar
* O arquivo enviado deverá ser recebido por todos os membros que fazem parte daquele channel

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Enviar um emoji| para poder demonstrar minha reação ou sentimento em um channel|  |  | Could |

* O usuário poderá enviar emojis ou gifs, que estarão divididos por categorias
* O emoji enviado deverá ser recebido por todos os membros que fazem parte daquele channel

### EP - Editar Mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Editar uma mensagem que foi enviada em um channel| para poder corrigir erros ou fazer quaisquer alterações na mesma|  |  | Should |

* O usuário deve poder editar a mensagem a qualquer momento após tê-la enviado

### EP - Remover Mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Remover uma mensagem de um channel| para que ela não seja mais exibida dentro daquele channel e os demais membros não possam mais lê-la| É necessárioque tenha um aviso de que a mensagem foi removida |  | Should |

* O usuário deve poder remover uma mensagem a qualquer momento após tê-la enviado
* No lugar da mensagem removida deverá ser exibido um aviso escrito "mensagem removida"

### EP - Adicionar Reação

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Adicionar uma reação(emoji) em uma determinada mensagem dentro de um channel| para expressar o sentimento ou sensação que tive ao ler aquela mensagem| A reação deverá ficar junto á mensagem que foi "reagida" |  | Would |

* O usuário deverá poder adicionar uma reação para uma mensagem enviada em um channel da qual faz parte
* Se vários usuários adicionarem reações a uma mesma mensagem, todas as reações deverão ser exibidas

### EP - Responder Mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Responder uma mensagem de um channel| para que o usuário que a enviou saiba que aquela resposta foi direcionada a sua mensagem|  |  | Should |

* O usuário deverá poder responder uma mensagem que foi enviada em um channel
* Uma mensagem de resposta deve exibir junto a ela a mensagem que está sendo respondida

### EP - Reportar Mensagem

#### US

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
| US | Usuário | Reportar uma mensagem de um channel| para indicar que aquela mensagem foi ofensiva de alguma forma |  |  | Could |

* O usuário deve poder reportar qualquer mensagem que tenha sido enviada no channel caso deseje

## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 07/05/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 07/05/2019 | 1.1 | Inclusão dos épicos EP01 e EP02 | Marcos Nery |
| 07/05/2019 | 1.2 | Inclusão do épico EP03 | Heron Rodrigues |
| 07/05/2019 | 1.3 | Inclusão do tema T03 | Weiller Fernandes |
