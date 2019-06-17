# Product Backlog

Aqui buscamos construir um backlog completo para o produto com base nos requisitos anteriormente elicitados. Além de, com o backlog construido e todas as histórias de usuário devidamente descritas com críterios de aceitação, simular o que seria desenvolvido em cada Sprint. Sendo que o backlog ficou dividido nos seguinte níveis de granularidade: Tema, Épico, histórias de usuário.

## Tabela de backlog e planejamento das sprints
Como a tabela que constroí o backlog e o divide em sprints é muito grande, para melhor visualização, a mesma foi colocada em um arquivo excel no drive, que pode ser visualizado a partir deste [link](https://docs.google.com/spreadsheets/d/1_gxL7uqWzSuB0wnm_buf4MWh9d_7JhUOwTsVjyAAZp0/edit?usp=sharing).


## T01 - Entrar no aplicativo

### EP01 - Fazer Login

#### US01

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US01 | Usuário  | Fazer login na aplicação utilizando minha conta | gostaria de acessar as funcionalidades de um usuário logado | Deve haver um limite de tentativas | 5 | Must  |Funcional|

* O usuário deverá ser capaz de utilizar uma conta previamente criada na aplicação para fazer login, digitando seu usuário e sua senha
* O usuário deverá conseguir utilizar o email no lugar do nome de usuário se preferir
* Se forem excedidas três tentativas sem sucesso de login com um nome de usuário, as tentativas devem ser bloqueadas temporariamente e o dono da conta deverá receber um email
* Quando o usuário errar os dados de entrada, ele deverá ser avisado se errou o nome ou a senha

_Originada em: [AP1](../Elicitação/analprot.md#requisitos-elicitados)_

#### US02

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US02 | Usuário  | Fazer login na aplicação utilizando minhas redes sociais | gostaria de acessar as funcionalidades de um usuário logado sem ter que criar uma nova conta | Login pelo facebook, google ou twitter| 5| Must|Funcional|

* O usuário deverá ser capaz de fazer login no aplicativo utilizando uma conta que ele possui em uma dessas redes sociais: GitHub, Facebook, Twitter e Google

_Originada em: [INT1.3](../Elicitação/Introspeccao.md#introspeccao-02), [AP1](../Elicitação/analprot.md#requisitos-elicitados)_

### EP02 - Fazer Cadastro

#### US03

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
|US03|Usuário|Criar uma conta no aplicativo|gostaria de ter uma conta para fazer login e acessar as funcionalidades do aplicativo|Cada usuário deve cadastrar um email, usuário e senha|8|Must|Funcional|

* O usuário deverá ser capaz de criar uma conta no aplicativo, para conseguir fazer login posteriormente.
* As seguintes informações do usuário deverão ser requisitadas para cadastrar a conta: email, usuário, tag e senha.
* A tag deve ser única, cada usuário tendo a sua. E assim como o nome de usuário estar restrito a letras e números.
* A senha deverá conter um número mínimo de 6 caractéres, incluíndo letras maíusculas, minúsculas, números e caracteres especiais.
* Deverá aparecer uma mensagem clara de erro caso o usuário insira errado alguma das informações.
* Opcionalmente, o usuário deverá conseguir colocar uma foto para aparecer no seu perfil.

_Originada em: [AP10](../Elicitação/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_

#### US04

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|US04|Dono do servidor|Modificar as informações pedidas na criação de conta |gostaria de ter uma experiência mais customizada, adaptada as necessidades do meu grupo||8|Should|Funcional|

* O dono do servidor deverá ser capaz de, ao criar o servidor, modificar quais informações são pedidas ao usuário quando o mesmo cria uma conta
* O dono do servidor deverá também conseguir mudar os critérios de aceitação de cada campo
* O dono do servidor deverá ser capaz de modificar essas definições a qualquer momento que desejar

_Originada em: [AP10](../Elicitação/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_

## T02 - Ajuda ao usuario

### EP03 - Atendimento online

#### US05

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
|US05|Usuário|Falar com algum integrande da equipe de suporte do Rocket.chat|gostaria de tirar uma dúvida ou obter ajuda com algum problema no aplicativo|Live chat com integrantes da equipe de suporte do Rocket.chat deverá ser disponibilizado no aplicativo|8|Would| Funcional|

* Deverá ser criado um grupo de funcionarios do Rocket.chat dedicado a prover suporte aos usuários via chat
* Esse atendimento deverá estar disponível de 8 as 18h nos dias úteis
* Deverá haver, na aplicação, um botão pelo qual o usuário pode ser levado ao chat e direcionado a um atendente
* Os funcionarios responsáveis por prover o atendimento deverão ser previamente capacitados para prover um bom atendimento, dessa forma, devendo saber todo o necessário acerca da aplicação

_Originada em: [ENT 1.3](../Elicitação.md/Entrevista#requisitos)_

#### US06

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
|US06|Usuário|Enviar um email para a equpe de suporte do Rocket.chat e te-lo respondido|gostaria de tirar uma dúvida ou obter ajuda com algum problema no aplicativo|Deve haver um botão que encaminha o usuário para uma opção que o permite enviar um email|5|Could|Funcional|

_Originada em: [INT3.10](../Elicitação/Introspeccao.md#introspeccao-03)_

### EP04 - Documentacao

#### US07

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
|US07|Usuário ou interessado|Ter a minha disposição documentos que expliquem mais sobre como utilizar a aplicação | preciso entender todas as capacidades da aplicação | Deve ser redigida uma documentação completa do aplicativo | 5 | Must | Não Funcional|

_Originada em: [AD4](../Elicitação/analdiscurso.md#requisitos-elicitados), [INT3.10](../Elicitação/Introspeccao.md#introspeccao-03)_

#### US08

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
|US08|Usuário ou interessado|Ter acesso a tutoriais ou ajuda dentro do aplicativo |preciso entender como funciona a aplicação|Deve haver um botão de ajuda, que fornece ao usuário tutoriais e descrições de como utilizar funcionalidades|3|Should| Funcional|

_Originada em: [AD4](../Elicitação/analdiscurso.md#requisitos-elicitados), [INT3.10](../Elicitação/Introspeccao.md#introspeccao-03)_

## T03 - Visão geral do aplicativo

### EP05 - Configurações do aplicativo

#### US09

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US09 | Usuário |Acessar as preferências do aplicativo| quero modificar as preferências do aplicativo que melhor se adequem as minhas necessidades|  | 8 | Must |Funcional|

* Deve estar disponibilizada no menu de personalização a função de alterar o comportamento das notificações, se são para todas as mensagens ou somente menções
* Deve haver uma opção para configurar os temas utilizados
* Deve haver um menu de seleção de idioma
* Deve haver uma opção de personalização de perfil, que direciona o usuário a tela dedicada alterar suas informações pessoais

_Originada em: [AD5](../Elicitação/analdiscurso.md#requisitos-elicitados), [AP8](../Elicitação/analdiscurso.md#requisitos-elicitados)_

#### US10

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US10 | Usuário |Alterar Idioma| preciso alterar para um idioma que eu tenha mais familiaridade ou apenas para padronizar com minha equipe|  |  8| Must |Funcional|

* O usuário deverá ser capaz de alterar o idioma no qual a aplicação vigora, alterando os textos de todos os botões e menus existentes
* Inicialmente deverão haver os idiomas Inglês, Portugugês-Brasil e Espanhol.
* A funcionalidade deve dar suporte para que outros idiomas sejam adicionados posteriormente

_Originada em: [INT4.5](../Elicitação/Introspeccao.md#introspeccao-04), [StoryBoarding 6](../Elicitação/Storyboard.md#4-requisitos-obtidos)_

#### US11

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US11 | Usuário |Configurar Exibição| gostaria de alterar opções que melhor se adaptem as minhas necessidades e ao meu dispositivo|  | 3 | Could |Funcional|

* A funcionalidade deve oferecer ao usuário a opção de alterar o modo de exibição do aplicativo
* Dois modos de exibição devem por padrão existir, o normal e o simplificado. No simplificado, a tela é focada em um channel e a barra lateral fica escondida

_Originada em: [AD9]((../Elicitação/analdiscurso.md#requisitos-elicitados))_

### EP06 - Configurações da Conta

#### US12

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US12 | Usuário | Alterar Senha | preciso melhorar a segurança da minha conta |  | 3 | Must | Funcional |

* Para alterar a senha o usuário deverá informar a senha atual
* A senha deve possuir no minimo 8 caracteres

_Originada em: [L21]((lexicos.md#l21)), [L45]((lexicos.md#l45))_

#### US13

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US13 | Usuário | Adicionar autenticação de 2 Fatores | gostaria de proteger a minha conta com mais eficiência | na autênticação de 2 fatores, sempre na realização do login é preciso verificar o token enviado para o e-mail do usuário | 8 | Must | Não Funcional |

* Para ativar a autenticação é necessário o usuário confirmar sua conta de e-mail
* Cada a funcionalidade estiver ativa, é necessário que a cada vez que o usuário fizer um login em um novo dispositivo que não está logado, o aplicativo deve pedir para o usuário confirmar o token enviado para seu e-mail

#### US14

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US14 | Usuário | Acessar informações da Conta | gostaria de visualizar e alterar o nome, e-mail, avatar, ocupações, linguagens entre outras opções | Na versão de desktop essa funcionalidade é mais completa | 2 | Must | funcional |

* O usuário deverá ser capaz de visualizar as informações de sua conta, como, nome, e-mail, avatar,, ocupações, idiomas.
* O usuário também deve ser capaz de alterar essas informações, exceto o nome de usuário
* Nessa tela específica o usuário somente poderá visualizar as informações de seu usuário

_Originada em: [AP7]((../Elicitação/analprot.md#requisitos-elicitados))_

#### US15

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US15 | Usuário | Verificar e alterar status do perfil | desejo indicar qual meu estado atual no uso do aplicativo | Opções de usuário, como: online, ausente, ocupado, invisivel | 3 | Must | Funcional |

* Usuário deve ser capaz de visualizar seu status atual (online, ausente, ocupado, invisivel)
* usuário também deve conseguir alterar o seu status atual
* Quando o usuário estiver deslogado, seu status deverá ser alterado para offline, mesmo sem que o usuário altere

_Originada em: [L22](lexicos.md#l22), [C10](cenarios.md#c10)_

### EP07 - Channels

#### US16

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US16 | Usuário | Procurar Channels | preciso encontrar um channel com a facilidade de procurar por texto |  | 2 | Could | Funcional |

* Usuário deverar se capaz de procurar, através de texto, por qualquer channel público vísivel no servidor
* Nessa pesquisa deverá ser mostrado todos os channels pessoais do usuário, como private groups, channels públicos, direct messages pessoais, discussões
* Nessa mesma ferramenta de pesquisa, também serão mostrados outros direct messages vazios, se usuário não tiver conversado com o usuário

_Originada em:_

#### US17

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US17 | Usuário | Ordenar Channels | desejo visualizar e separar meus channels por categorias | Categorias dos Channels: Channel, Grupo privado, Direct Messages e Discussão | 2 | Could | Funcional |

* O usuário deverá visualizar os channel separados por categoria (versão Desktop)
* Usuário deverá conseguir alterar a categoria de um channel favoritando o mesmo
* Usuário poderar alterar a qualquer momento o modo de ordenação dentro das categorias, seja alfabética, ou pela última ativadde.
* Usuário deve conseguir adicionar categorias adicionais, como visualizar o grupo de favoritos ou de channels com mensagens não lidas(unread)

_Originada em: [L39](lexicos.md#l39)_

## T04 - Channel

### EP08 - Criar channel

#### US18

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US18 | Usuário | Criar channel publico | para que todos possam procurar e ter acesso à esse channel | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |Funcional|

* Deve ser disponibilizado para o usuário, a opção de criar channel publico
* Usuário pode criar número ilimitado de channels publicos
* Nome do channel deve ser obrigatório
* Qualquer tipo de caractere deve ser aceito para o nome do channel
* Nome do channel deve conter no mínimo um caractere
* Channel deve ser disponibilizado para qualquer usuário ter acesso, ao ser procurado na barra de pesquisa, na página inicial
* Não é necessário que convide membros durante a criação do channel

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US19

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US19 | Usuário | Criar channel privado | para que seja acessado apenas por convite e visivel somente por seus membros | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |Funcional|

* Por padrão, somente administradores e moderadores podem convidar novos membros
* Somente membros podem ter acesso à esse channel
* Usuário pode criar número ilimitado de channels privados
* Deve ser disponibilizado para o usuário, a opção de criar channel privado
* Nome do channel deve ser obrigatório
* Membros só podem ser adicionados, se forem convidados
* Qualquer tipo de caractere deve ser aceito para o nome do channel
* Administrador determina quem pode convidar membros
* Nome do channel deve conter no mínimo um caractere
* Não é necessário que convide membros durante a criação do channel

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US20

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US20 | Usuário | Enviar mensagem direta | gostaria de enviar mensagens privadas para determinado usuário|  | 5 | Must |Funcional|

* Conversa iniciada ao acessar o perfil de um usuário na lista de membros de um channel, ou ao procura-lo na barra de pesquisa, na página inicial

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US21

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US21 | Usuário | Criar Discussão | necessito tratar de assuntos rápidos, porém mais específicos entre um pequeno grupo de usuários em um channel |  | 3 | Could | Funcional|

* Por padrão, somente administradores e moderadores podem convidar novos membros
* Somente membros podem ter acesso à esse channel
* Nome do channel deve ser obrigatório
* Qualquer tipo de caractere deve ser aceito para o nome do channel
* Nome do channel deve conter no mínimo um caractere
* Não é necessário que convide membros durante a criação do channel

_Originada em: [L27](lexicos.md#l27), [C3](cenarios.md#c3)_

### EP09 - Configurações do Channel

#### US22

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US22 | Administrador/Proprietário do Channel | Alterar Privacidade do Channel | preciso da liberdade de poder deixar que os usuários do servidor consigam ou não visualizar a existência do meu Channel |  | 3 | Must | Funcional |

* Usuário deve conseguir alterar a qualquer momento depois da criação do channel a privacidade
* Somente usuários administradores ou o Proprietário deverão conseguir alterar a privacidade
* Qualquer tipo de channel (private group, channel público, discussões) pode ter a privacidade alterada, exceto direct messages

_Originada em: [L72](lexicos.md#l72), [C26](cenarios.md#c26), [DCU8](diagramas.md#dcu8), [EC2](especificacao.md#ec2)_

#### US23

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US23 | Administrador/Proprietário do Channel | Definir modo de Read Only Channel | assim posso usa-lo como uma lista de transmissão onde apenas os administradores podem enviar mensagem | canal apenas de leitura | 5 | Should | Funcional |

* No momento em que é criado um canal deve existir a opção only-read channel
* Apenas o usuário o qual criou o canal deve poder enviar mensagens
* Apenas administradores devem poder convidar pessoas para o canal
* O nome do canal deve possuir ao menos um caractere
* Não é necessário que convide membros durante a criação do channel

_Originada em: [L69](lexicos.md#l69), [C22](cenarios.md#c22), [DCU9](diagramas.md#dcu9-v1), [EC3](especificacao#ec3)_

#### US24

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US24 | Administrador/Proprietário do Channel | Alterar modo para BroadCast | gostaria de alterar o Channel, onde apenas os usuários autorizados consigam enviar mensagens, mas os usuários consigam responder as mesmas |  | 5 | Should | Funcional |

* Somente usuários administradores ou o Proprietário deverão conseguir alterar o channel para modo de BroaCast
* Com o modo ativado, apenas os usuários autorizados pelos administradores conseguem enviar mensagens, mas todos os outros usuários conseguem responder a mensagem
* Este modo só poderá ser ativado na criação do Channel

_Originada em:_

#### US25

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US25 | Administrador/Proprietário do Channel | Adicionar descrição do Channel | gostaria de adicionar uma descrição adequada para meu Channel |  | 2 | Could | Funcional |

* Somente usuários administradores ou o Proprietário deverão conseguir adicionar a descrição de um Channel
* A descrição deverá possuir um limite de caracteres inseridos

_Originada em:_

#### US26

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US26 | Administrador/Proprietário do Channel | Adicionar tópico do Channel | gostaria de adicionar os tópicos, temas e interesses do meu Channel |  | 2 | Could | Funcional |

* Somente usuários administradores ou o Proprietário deverão conseguir adicionar o tópico de um Channel
* O tópico deve possuir um limite de caracteres inseridos

_Originada em: [L33](lexicos.md#l33)_

### EP10 - Mensagens

#### US27

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US27 | Usuário | Enviar uma mensagem de texto | preciso me comunicar de forma escrita com os membros de um channel |  | 5 | Must |Funcional|

* O usuário deverá ser capaz de enviar uma mensagem de texto para qualquer channel que ele faça parte
* A mensagem enviada deverá ser recebida por todos os membros que fazem parte daquele channel
* Quando usuário digitar uma mensagem muito grande será perguntado se ele deseja enviar a mensagem pelo meio padrão ou se ele deseja encapsular a mensagem em um arquivo e enviá-lo ao channel

_Originada em: [INT4.1](../Elicitação/Introspeccao.md#introspeccao-04),
[Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [C12](cenarios.md#c12-v2)__

#### US28

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US28 | Usuário | Enviar um arquivo | para poder enviar qualquer documento ou arquivo que esteja armazenado no meu dispositivo para os demais membros do channel| Este arquivo pode ser uma foto, vídeo, documento, áudio, etc | 5 | Must |Funcional|

* Essa opção deve possibilitar ao usuário buscar no armazenamento do seu dispositivo o arquivo que deseja enviar
* Essa opção deve possibilitar ao usuário buscar no Google Drive um arquivo que deseja enviar
* O arquivo enviado deverá ser recebido por todos os membros que fazem parte daquele channel

_Originada em: [INT2.1](../Elicitação/Introspeccao.md#introspeccao-02),
[Q6](../Elicitação/questionario.md#requisitos-elicitados), [C9](cenarios.md#c9-v2)_

#### US29

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US29 | Usuário | Enviar um emoji| para poder demonstrar minha reação ou sentimento em um channel|  | 3 | Could |Funcional|

* O usuário deve poder enviar emojis ou gifs, que estarão divididos por categorias
* O emoji enviado deverá ser recebido por todos os membros que fazem parte daquele channel

_Originada em: [L7](lexicos.md#l7)_

#### US30

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US30 | Usuário | Enviar desenho | gostaria de fazer uma representação ou explicação rápida que é melhor representado com um rascunho de um desenho |  | 5 | Would | Funcional |

* O usuário deve conseguir fazer um desenho estando em um channel (versão mobile)
* O desenho deverá ser enviado como qualquer mensagem no chat
* Os outros usuários devem conseguir visualizar o desenho no próprio aplicativo

_Originada em: [L43](lexicos.md#l43), [C8](cenarios.md#c8), [EC17](especificacao.md#ec17)_

#### US31

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US31 | Usuário | Enviar mensagem de áudio| para mandar mensagem de voz ao invés de escreve um texto |  | 5 | Could |Funcional|

* O usuário poderá enviar mensagem de áudio com tempo ilimitado
* A mensagem de áudio deverá ser recebida por todos os membros que fazem parte daquele channel

_Originada em: [INT1.5](../Elicitação/Introspeccao.md#introspeccao-01),
[Q6](../Elicitação/questionario.md#requisitos-elicitados)_

#### US32

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US32 | Usuário | Enviar Mensagem de vídeo | preciso transmitir uma mensagem melhor compreendida através de um video | como por exemplo uma demonstração de um trabalho, ou um video da gravação de uma reunião física | 8 | Should | Funcional |

* Qualquer usuário em uma channel deve conseguir enviar um vídeo
* O vídeo deverá ser gravado no momento que o usuário deseja enviar (versão Desktop) ou ser enviado como um arquivo presente no dispositivo
* O vídeo deverá possuir um tamanho máximo suportado
* O aplicativo deverá suportar os principais formatos disponíveis no mercado

_Originada em: [INT1.5](../Elicitação/Introspeccao.md#introspeccao-01)_

#### US33

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US33 | Usuário | Anexar Arquivo na mensagem | preciso compartilhar um arquivo com minha equipe | arquivo anexado, pode ser um audio, documento de texto, video, imagem entre outros | 5 | Should | Funcional |

* Qualquer usuário em uma channel deve conseguir anexar um arquivo a partir do dispositivo utilizado
* Os arquivos devem ser compativeis com os formatos suportados pelo aplicativo
* O usuário deve conseguir anexar arquivos de audio, documento de texto, video, imagem entre outros
* O arquivo pode ser enviado sozinho ou junto com uma mensagem de texto
* Todos os outros usuários devem ser capazes de visualizar a mensagem com o arquivo anexado

_Originada em: [INT2.1](../Elicitação/Introspeccao.md#introspecção-02)_

#### US34

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US34 | Usuário | Editar uma mensagem que foi enviada em um channel| para poder corrigir erros ou fazer quaisquer alterações na mesma| Deve haver um aviso que a mensagem foi editada | 5 | Should |Funcional|

* O usuário deve poder editar a mensagem a qualquer momento após tê-la enviado
* Um aviso com a mensagem "editado" deve ser exibido junto á mensagem que foi editada

_Originada em: [C5](cenarios.md#c5)_

#### US35

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US35 | Usuário | Copiar Mensagem | preciso repassar a mensagem para outro lugar |  | 2 | Would | Funcional |

* Os usuários de um channel devem conseguir copiar o texto de mensagens para a área de compartilhamento do dispositivo

_Originada em: [L54](lexicos.md#l54)_

#### US36

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US36 | Usuário | Pegar Link da Mensagem | preciso compartilhar a mensagem |  | 3 | Would | Funcional |

* O usuário deverá conseguir pegar o link de uma mensagem e compartilhar com outro usuário
* O link poderáser acessado através de um navegador
* Apenas usuários cadastrados no Rocket.Chat e que tenham acesso ao Channel conseguem acessar o link

_Originada em: [L13](lexicos.md#l13)_

#### US37

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US37 | Usuário | Seguir Mensagem | gostaria de seguir as respostas para uma mensagem de meu interesse que não foi eu que criei |  | 3 | Could | Funcional |

* O usuário deverá conseguir acompanhar uma mensagem recebendo notificações de novas respostas para a mensagem seguida
* Qualquer usuário do channel deverá conseguir realizar esta ação
* O usuário que criou a mensagem não precisa realizar essa ação, pois naturalmente ele já recebe notificações de novas respostas

_Originada em:_

#### US38

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US38 | Usuário | Remover uma mensagem de um channel| para que ela não seja mais exibida dentro daquele channel e os demais membros não possam mais lê-la| É necessário que tenha um aviso de que a mensagem foi removida | 3 | Should |Funcional|

* O usuário deve poder remover uma mensagem a qualquer momento após tê-la enviado
* No lugar da mensagem removida deverá ser exibido um aviso escrito "mensagem removida"

_Originada em: [Q8](../Elicitação/questionario.md#requisitos-elicitados)_

#### US39

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US39 | Usuário | Adicionar uma reação(emoji) em uma determinada mensagem dentro de um channel| para expressar o sentimento ou sensação que tive ao ler aquela mensagem| A reação deverá ficar junto á mensagem que foi "reagida" | 2 | Would |Funcional|

* O usuário deverá poder adicionar uma reação para uma mensagem enviada em um channel da qual faz parte
* Se vários usuários adicionarem reações a uma mesma mensagem, todas as reações deverão ser exibidas

_Originada em: [L9](lexicos#l9)_

#### US40

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US40 | Usuário | Responder uma mensagem de um channel| para que o usuário que a enviou saiba que aquela resposta foi direcionada a sua mensagem|  | 5 | Should |Funcional|

* O usuário deverá poder responder uma mensagem que foi enviada em um channel
* Uma mensagem de resposta deve exibir junto a ela a mensagem que está sendo respondida

_Originada em: [C7](cenarios.md#c7-v2)_

#### US41

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US41 | Usuário | Reportar uma mensagem de um channel| para indicar que aquela mensagem foi ofensiva de alguma forma |  | 5 | Could |Funcional|

* O usuário deve poder reportar qualquer mensagem que tenha sido enviada no channel caso deseje

_Originada em:_

### EP11 - Ações do Channel

#### US42

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US42 | Usuário | Favoritar o channel | preciso conseguir agrupar os Channels que eu mais interajo, em um espaço para que eu consiga acessá-lo com mais facilidade | | 3 | Could | Funcional |

* Somente os Channels que o usuário é membro favoritou devem aparecer na listagem dessa categoria
* Quando o usuário Favoritar um Channel deve aparecer um botão para remover o Channel como Favorito

_Originada em: [Q15](../Elicitação/questionario.md#requisitos-elicitados)_

#### US43

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US43 | Usuário | Mencionar Usuários | preciso enviar uma mensagem direcionada para o usuário, ou apenas chamar a sua atenção | | 5 | Should | Funcional |

* Apenas usuários do channels devem aparecer como opção quando o usuário estiver tentando escrever o nome de usuário ao qual quer mencionar
* Quando um usuário for mencionado ele receberá uma notificação

_Originada em: [AD5](../Elicitação/analdiscurso.md#requisitos-elicitados), [INT1.6](../Elicitação/Introspeccao.md#introspecção-01), [L4](lexicos#l4)_

#### US44

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US44 | Usuário | Alterar Preferências de notificações | desejo recebimento de notificações de acordo com minhas preferências de utilização do Channel | | 5 | Should | Funcional |

* Apenas usuários membros de um channel podem alterar as notificações
* Devem ter opções separadas de notificaçõs para cada tipo de dispositivo (Desktop, Mobile)
* Deve ser possível alterar notificações de áudio
* Deve ser possível alterar notificações de E-mails
* Deve ser possível desativar ou ativar as notificações quando o usuário for mencionado dentro do channel

_Originada em: [AD5](../Elicitação/analdiscurso.md#requisitos-elicitados), [L28](lexicos.md#l28), [C19](cenarios.md#c19), [DCU14](diagramas.md#dcu14-v1), [EC24](especificacao.md#ec24)_

#### US45

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US45 | Usuário | Utilizar tradução instantânea | preciso me comunicar com membros da equipe que possuem um idioma que não domino totalmente | | 13 | Should | Funcional |

* A tradução deve estar disponível a qualquer momento quando em uma videoconfrerência
* Tradução também deve estar disponível no chat principal do Channel para as mensagens de texto
* Deve ser possível alterar os idiomas de preferência
* Deve ser possível ativar ou desativar a funcionalidade

_Originada em: [INT4.4](../Elicitação/Introspeccao.md#introspecção-04), [StoryBoard 3](../Elicitação/StoryBoard.md#4-requisitos-obtidos), [L31](lexicos.md#l31)_

#### US46

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US46 | Usuário | Iniciar Video Chat | preciso realizar uma reunião com membros que não podem se encontrar fisicamente |  | 8 | Should | Funcional |

* A funcionalidade deve estar disponível a qualquer momento quando o usuário for membro em uma equipe
* Quando inicada deve aparecer uma mensagem no chat do Channel indicando que um video chat foi iniciado
* Deve ser possível compartilhar o link do Channel que pode ser acessado a partir de qualquer dispositivo suportado pelo aplicativo
* Deve ser possível transmitir o video chat para o YouTube

_Originada em: [INT1.5](../Elicitação/Introspeccao.md#introspecção-01), [INT3.5](../Elicitação/Introspeccao.md#introspecção-03), [StoryBoard 2](../Elicitação/StoryBoard.md#4-requisitos-obtidos), [C2](cenarios.md#c2-v1), [L25](lexicos.md#l25), [DCU1](diagramas.md#dcu1-v1), [EC20](especificacao.md#ec20)_

#### US47

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US47 | Usuário | Visualizar informações do Channel | gostaria de ver a descrição do Channel, Deixar, ou Esconder o Channel | Também possui informações de anúncios e tópicos | 3 | Should | funcional |

* Deve ser possível a visualização da tela por qualquer membro do Channel
* Apenas usuários administradores podem alterar as informações
* Deve aparecer três titulos principais e seu conteúdo (Descrição, Tópico e Anúncios)

_Originada em:_

#### US48

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US48 | Usuário | Procurar Mensagens | preciso encontrar mensagens a partir de texto | por exemplo, um trecho da mensagem que eu me lembro | 2 | Could | funcional |

* Para procurar uma mensagem o usuário deve ser membro do channel ao qual a mensagem pertence
* A busca poderá ser realizada através de texto
* A busca poderá ser realizada através da listagem cronológica de publicação no chat do channel
* A busca poderá ser realizada através da listagem de mensagens favoritadas
* A busca poderá ser realizada através da listagem de mensagens fixadas pelo administrador do Channel

_Originada em: [L11](lexicos.md#l11), [C17](cenarios.md#c17), [DCU12](diagramas.md#dcu12-v1), [EC13](especificacao.md#ec13)_

#### US49

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US49 | Usuário | Favoritar Mensagem | gostaria de conseguir encontrá-la com mais facilidade mais tarde | | 3 | Should | funcional |

* Apenas usuários membros em um Channel podem favoritar uma mensagem pertencente ao Channel
* Quando favoritada a mensagem deve ser listar nas opções pessoais do channel individuais para cada usuários para uma busca rápida da mensagem
* Quando uma mensagem for favoritada deverá a ver um botão para desfavoritar mensagem

_Originada em: [L71](lexicos.md#l71), [C13](cenarios.md#c13), [DCU6](diagramas.md#dcu6-v1), [EC6](especificacao.md#ec6)_

#### US50

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US50 | Administrador/Proprietário do Channel | Fixar Mensagem | gostaria de destacar mensagens importantes para todos os membros do channel visualizarem | | 3 | Should | funcional |

* Apenas usuários administradores em um Channel podem fixar uma mensagem pertencente ao Channel
* Quando favoritada a mensagem deve ser listar nas opções pessoais do channel compartilhdas por todos para uma busca rápida da mensagem
* Quando uma mensagem for fixada deverá a ver um botão para desafixar mensagem

_Originada em: [L3](lexicos.md#l3), [L16](lexicos.md#l16), [C11](cenarios.md#c11), [C25](cenarios.md#c25), [DCU3](diagramas.md#dcu3), [EC6](especificacao.md#ec6), [EC12](especificacao.md#ec12)_

#### US51

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US51 | Usuário | Visualizar lista de arquivos enviados | preciso encontrar com mais facilidade um arquivo que foi compartilhado no Channel | Útil para ganhar tempo, sem preciso encontrar a mensagem em que o arquivo foi enviado | 5 | Could | funcional |

* Um arquivo irá aparecer nessa listagem imediatamente quando for anexado a uma mensagem
* A lista de arquivos em um channel será única e compartilhada por todos do Channel
* O arquivo deverá desaparecer da lista se a sua mensagem correspondente for apagada
* Quando clicado na representação de um arquivo o usuário deverá imediatamente ser redirecionado para a localização original da mensagem correspondente

_Originada em:_

#### US52

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US52 | Usuário | Utilizar atalhos no teclado | gostaria de aumentar a eficiência e produtividade para usuários mais experientes | Funcionalidade disponível apenas no Desktop | 3 | Would | funcional |

* Qualquer usuário do aplicativo poderá utilizar essa funcionalidade
* Funcionalidade apenas disponível para desktop
* A funcionalidade deverá estar disponível a qualquer momento
* Deverá haver no menu de ajuda uma lista com os atalhos suportados pelo aplicativo

_Originada em:_

### EP12 - Video Chat

#### US53

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US53 | Administrador da Video Chat | Convidar Membros da equipe | preciso convidar usuários membros no channel para a video conferência | | 8 | Must | funcional |

* Apenas o usuário que iniciou a Video Chat poderá convidar novos membros
* Ao Usuário convidado deverá ser enviado uma notificação
* Usuário deverá ter a opção de aceitar ou recusar convite para a Video Chat

_Originada em: [L59](lexicos.md#l59)_

#### US54

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US54 | Administrador da Video Chat | Compartilhar link | gostaria de compartilhar video chat com qualquer pessoa que tenha um dispositivo com acesso a internet e um navegador | | 3 | Could | funcional |

* Qualquer usuário poderá compartilhar o link da Video Chat
* Apenas usuários membros do Channel ao qual a mensagem pertence poderão acessar o link gerado
* O link deverá ser possível o acesso através de qualquer dispositivo suportado, inclusive através do navegador

_Originada em: [L13](lexicos.md#l13)_

#### US55

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US55 | Administrador da Video Chat | Compartilhar para YouTube | gostaria de realizar uma transmissão da video conferência na plataforma do YouTube | | 3 | Could | funcional |

* Apenas o usuário que iniciou a Video Chat poderá realizar esta ação
* Deverá haver a opção para transmitir de maneira ao vivo a Video Chat para um Canal do Youtube

_Originada em:_

#### US56

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US56 | Usuário | Assistir a video aula através de texto | não sou capaz de acompanhar a reunião através da audição | pode ser requirido por não entendimento da pronúncia do idioma utlizado por outros membros, por deficiência na audição, ou até mesmo por não possuir um dispositivo disponível com audio | 5 | 13 | Could | funcional |

* Qualquer usuário presente na video chat poderá utilizar essa funcionalidade
* Deverá ter uma opção para ativar ou desativar a funcionalidade
* Deverá ter opções para alterar idioma de tradução

_Originada em:_

#### US57

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US57 | Usuário | Compartilhar tela do computador | preciso realizar uma apresentação com slides ou mostrar um trabalho que estou realizando | | 8 | Could | funcional |

* Opção deverá estar disponível para todos usuários presentes na video chat
* O usuário poderá restringir o compartilhamento para uma tela específica
* O usuário poderá compartilhar a tela atual que o mesmo está visualizando no momento
* A qualquer momento deverá haver uma opção para ativar ou desativar a funcionalidade

_Originada em: [AD3](../Elicitação/analdiscurso.md#requisitos-elicitados), [INT3.5](../Elicitação/Instrospeccao.md#introspecção-03), [Q11](../Elicitação/questionario.md#requisitos-elicitados), [Storyboard 2](../Elicitação/storyboard.md#requisitos-obtidos)_

### EP13 - Gerenciar Usuários

#### US58

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US58 | Usuário | Visualizar Lista de Membros | preciso saber a quantidade de mebros em um Channel ou procurar por um usuário | | 3 | Should | funcional |

* Qualquer usuário membro no Channel poderá visualizar a lista de integrantes
* Usuário poderá realizar a busca pelo nome de usuário de um mbro
* Usuário poderá filtrar a lista de membros de acordo com os membros "online" ou todos

_Originada em:_

#### US59

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US59 | Usuário | Visualizar informações de um Usuário | gostaria de iniciar uma conversa com o usuário ou bloquear as notificações enviadas por ele. Também gostaria de saber se o usuário está online | | 3 | Should | funcional |

* Qualquer usuário poderá visualizar as informações básicas de outro usuário
* Apenas o usuário dono da conta poderá visualizar as informações pessoais
* Apenas o usuário dono da conta poderá alterar as informações pessoais

_Originada em: [AP7](../Elicitação/analprot.md#requisitos-elicitados), [L8](lexicos.md#l8)_

#### US60

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
 US60 | Administrador/Proprietário do Channel | Adicionar usuários | preciso formar a minha equipe dentro de um channel | | 3 | Must | funcional |

* Apenas os usuários administradores poderão adicionar ou aceitar usuários no Channel

 _Originada em: [AP5](../Elicitação/analpro.md#requisitos-elicitados), [L59](lexicos.md#l59)_

#### US61

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US61 | Administrador/Proprietário do Channel | Remover usuários | necessito retirar do channel um usuário que não faz mais parte da equipe | |3 | Should | funcional |

* Apenas os usuários administradores poderão remover um usuário membro em um grupo
* Para um usuário ser removido ele deverá estar na lista de mebros
* Após removido o usuário deverá ser retirado da lista

_Originada em:_

### EP14 - Integrações

#### US62

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US62 | Administrador/Proprietário do Channel | Adicionar Bots | gostaria de ajuda na realização de tarefas repetitivas | geralmente para mostrarem as regras do Channel, mensagens de rotina em outro serviço que o grupo utilize (como github por exemplo), responderem perguntas programadas ou até mesmo remover um usuário que propaga spam | 8 | Should | funcional |

* Para adicionar bots o usuário deverá ser administrador em Channel
8 O bot deverá ser integrado ao Channel como um usuário
* O bot integrado ao channel poderá interagir com os outros usuários
* Para adicionar bots o usuário deverá possuir conhecimentos prévios para configurar ou programar o bot
* As permissões do bot devem ser configurados pelo seu "dono" (exemplo: alguns bots podem ter poder até para remover outros usuários se os mesmos infrigirem alguma regra do Channel)
* A inserção de bots se aplica apenas para Channels e Grupos privados

_Originada em: [AD7](../Elicitação/analdiscurso.md/requisitos-elicitados), [ENT1.1](../Elicitação/Entrevista.md#requisitos), [INT3.9](../Elicitação/Introspeccao.md#introspecção-03), [Q2](../Elicitação/questionario.md#requisitos-elicitados), [L26](lexicos.md#l26), [C24](cenarios.md#c24)_

### EP15 - Deixar Channel

#### US63

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US63 | Usuário | Esconder um channel | necessito que possa continuar como membro, porém não receber notificações e não ser exibido em minha lista de channels | | 2 | Should | funcional |

* Qualquer usuário membro em um grupo poderá realizar a ação de ocultar um channel da listagem de channels
* Channels não podem ser removidas do aplicativo
* Quando um usuário for o único membro em um Channel, essa será a única opção possível, não podendo deixar ou remover o Channel

_Originada em: [L49](lexicos.md#l49), [C16](cenarios.md#c16-v1), [DCU23](diagramas.md#dcu23-v1), [EC23](especificacao.md#ec23)_

#### US64

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US64 | Usuário | Deixar um Channel | não faço mais parte da equipe | | 2 | Must | funcional |

* Opção disponível para qualquer usuário desde que seja membro do Channel
* Se o usuário for o proprietário do Channel, ele deverá nomear outro usuário como membro antes de poder deixar o Channel
* Quando usuário deixar o Channel, deverá ser removido da lista de membros

_Originada em: [L48](lexicos.md#l48), [DCU22](diagramas.md#dcu22-v1), [EC22](especificacao.md#ec22)_

## T05 - Servidor

### EP16 - Conectar com um servidor

#### US65

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US65 | Usuário | Conectar com um servidor da aplicação | para que eu possa acessar o servidor em que meu time/empresa esteja utilizando para se comunicar | Deve conter o nome do servidor e provedor | 3 | Must |Funcional|

* O endereço de servidor deve ser validado, conter o nome do servidor e provedor
* Deve ser aplicado um protocolo de conexão

*Originada em: [ENT1.7](../Elicitação/Entrevista.md#requisitos),[INT1.4](../Elicitação/Introspeccao.md#introspeccao-01),  [INT3.2](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 4](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AD13](../Elicitação/analdiscurso.md#requisitos-elicitados), [AP2](../Elicitação/analprot.md#requisitos-elicitados), [C4](cenarios.md#c4-v2)*

### EP17 - Segurança

#### US66

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US66 | Usuário | estar em uma conexão segura | preciso transmitir mensagens confidenciais com minha equipe | independente do usuário possuir um servidor particular ou não | 8 | Must | Não Funcional |

_Originada em: [INT1.7](../Elicitação/Introspeccao.md#introspecção-01)_

#### US67

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US67 | Usuário administrador do servidor | Definir opção para criptografar meus channels por chave E2E | preciso transitir mensagens confidenciais com minha equipe | independente do usuário possuir um servidor particular ou não | | Must | Não Funcional |

_Originada em:_

### EP18 - Suporte a grandes Equipes

#### US68

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US68 | Usuário administrador do servidor | Adicionar vários channels e usuários ao servidor dedicado | preciso que todas as equipes envolvidas no(s) projeto(s) tenham acesso aos channels que representam suas equipes | O servidor deve suportar o aumento de usuários | | Must | Não Funcional |

_Originada em: [INT3.2](../Elicitação/Introspeccao.md#introspecção-03)_

### EP19 - Diretório

#### US69

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US69 | Usuário | Verificar todos os Channels do servidor | desejo saber a relação de Channels criados no servidor | Opções disponíveis apenas no Desktop | | Would | Funcional |

_Originada em:_

#### US70

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US70 | Usuário | Verificas todos os usuários do servidor | desejo saber a relação de todos os usuários cadastrados no servidor | | 3 | Would | Funcional |

_Originada em:_

#### US71

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US71 | Arquiteto do projeto | que o software possua uma arquitetura escalável para que ele possa atender mais pessoas de forma mais estável | assim mantenho o servidor funcionando de forma adequada para todos os usuários | | 13 | Should | Não Funcional |

* A arquitetura deve permitir que o servidor além de ser escalável possoa funcionar sob uma infraestrutura on-premise
* A aquitetura deve permitir instâncias individuais do software

*Originada em: [ENT1.9](../Elicitação/Entrevista.md#requisitos)*

#### US72

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade | Tipo |
|----|----------|--------|--------|------------|--------|------------|------|
| US72 | Usuário | fazer minha própria instancia do software com infraestrutura on-premise | assim tenho mais controle dos dados os quais são enviados no servidor o qual uso |  | 13 | Must | Não funcional |

* O serviço deve ser suportado por servidor Linux

*Originada em: [ENT1.7](../Elicitação/Entrevista.md#requisitos)*

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 07/05/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 07/05/2019 | 1.1 | Inclusão dos épicos EP01 e EP02 | Marcos Nery |
| 07/05/2019 | 1.2 | Inclusão do épico EP08 | Heron Rodrigues |
| 07/05/2019 | 1.3 | Inclusão do tema EP10 | Weiller Fernandes |
| 08/05/2019 | 1.4 | Inclusão do tema T05 | Heron Rodrigues |
| 08/05/2019 | 1.5 | Inclusão do tema T03, com EP03 e 04 | Marcos Nery |
| 08/05/2019 | 1.6 | Melhor formatação das tabelas | Marcos Nery |
| 08/05/2019 | 1.7 | Inclusão dos pontos da US27 a US41 | Weiller Fernandes |
| 08/05/2019 | 2.0 | Inclusão dos épicos EP8, EP9, EP10 | João Lucas |
| 08/05/2019 | 2.1 | Inclusão do épico EP11 | João Lucas |
| 08/05/2019 | 2.2 | Inclusão do tema T06, com EP13 | Marcos Nery |
| 08/05/2019 | 2.3 | Reorganização dos identificadores dos Ts, EPs e USs | Lucas Maciel |
| 11/05/2019 | 2.4 | Adicionado Us no tema de Visão do aplicativo | Lucas Maciel |
| 11/05/2019 | 2.5 | Inclusão das USs nos épicos Configurações e Mensagens | Lucas Maciel |
| 18/05/2019 | 2.6 | Inclusão das USs 46-64 | Lucas Maciel |
| 17/06/2019 | 2.7 | Adição da tablea de backlog no drive | Marcos Nery |
