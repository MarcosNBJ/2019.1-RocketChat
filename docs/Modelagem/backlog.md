# Product Backlog

## T01 - Entrar no aplicativo

### EP01 - Fazer Login

#### US01

| ID   | Eu, como | desejo | porque| comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US01 | Usuário  | Fazer login na aplicação utilizando minha conta | gostaria de acessar as funcionalidades de um usuário logado | Deve haver um limite de tentativas | 5 | Must  |Funcional|

* O usuário deverá ser capaz de utilizar uma conta previamente criada na aplicação para fazer login, digitando seu usuário e sua senha
* O usuário deverá conseguir utilizar o email no lugar do nome de usuário se preferir
* Se forem excedidas três tentativas sem sucesso de login com um nome de usuário, as tentativas devem ser bloqueadas temporariamente e o dono da conta deverá receber um email
* Quando o usuário errar os dados de entrada, ele deverá ser avisado se errou o nome ou a senha

_Originada em: [AP1](../Elicitação/analprot.md#requisitos-elicitados)_


#### US02

| ID   | Eu, como | desejo | porque  | Comentário | Pontos | Prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US02 | Usuário  | Fazer login na aplicação utilizando minhas redes sociais | gostaria de acessar as funcionalidades de um usuário logado sem ter que criar uma nova conta | Login pelo facebook, google ou twitter| 5| Must|Funcional|

* O usuário deverá ser capaz de fazer login no aplicativo utilizando uma conta que ele possui em uma dessas redes sociais: GitHub, Facebook, Twitter e Google

_Originada em: [INT1.3](../Elicitação/Introspeccao.md#introspeccao-02), [AP1](../Elicitação/analprot.md#requisitos-elicitados)_

### EP02 - Fazer Cadastro

#### US03

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
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

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|US05|Usuário|Falar com algum integrande da equipe de suporte do Rocket.chat|gostaria de tirar uma dúvida ou obter ajuda com algum problema no aplicativo|Live chat com integrantes da equipe de suporte do Rocket.chat deverá ser disponibilizado no aplicativo|8|Would| Funcional|

* Deverá ser criado um grupo de funcionarios do Rocket.chat dedicado a prover suporte aos usuários via chat
* Esse atendimento deverá estar disponível de 8 as 18h nos dias úteis
* Deverá haver, na aplicação, um botão pelo qual o usuário pode ser levado ao chat e direcionado a um atendente
* Os funcionarios responsáveis por prover o atendimento deverão ser previamente capacitados para prover um bom atendimento, dessa forma, devendo saber todo o necessário acerca da aplicação

_Originada em: [ENT 1.3](../Elicitação/Entrevista#requisitos)_

#### US06

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|US06|Usuário|Enviar um email para a equpe de suporte do Rocket.chat e te-lo respondido|gostaria de tirar uma dúvida ou obter ajuda com algum problema no aplicativo|Deve haver um botão que encaminha o usuário para uma opção que o permite enviar um email|5|Could|Funcional|

_Originada em: [INT3.10](../Elicitação/Introspeccao#introspeccao-03)_

### EP04 - Documentacao

#### US07

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|US07|Usuário ou interessado|Ter a minha disposição documentos que expliquem mais sobre como utilizar a aplicação | preciso entender todas as capacidades da aplicação | Deve ser redigida uma documentação completa do aplicativo | 5 | Must | Não Funcional|

_Originada em: [AD4](../Elicitação/analdiscurso#requisitos-elicitados), [INT3.10](../Elicitação/Introspeccao#introspeccao-03)_

#### US08

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|US08|Usuário ou interessado|Ter acesso a tutoriais ou ajuda dentro do aplicativo |preciso entender como funciona a aplicação|Deve haver um botão de ajuda, que fornece ao usuário tutoriais e descrições de como utilizar funcionalidades|3|Should| Funcional|

_Originada em: [AD4](../Elicitação/analdiscurso#requisitos-elicitados), [INT3.10](../Elicitação/Introspeccao#introspeccao-03)_

## T03 - Channel

### EP05 - Criar channel

#### US09

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US09 | Usuário | Criar channel publico | para que todos possam procurar e ter acesso à esse channel | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |Funcional|

- Deve ser disponibilizado para o usuário, a opção de criar channel publico
- Usuário pode criar número ilimitado de channels publicos
- Nome do channel deve ser obrigatório
- Qualquer tipo de caractere deve ser aceito para o nome do channel
- Nome do channel deve conter no mínimo um caractere
- Channel deve ser disponibilizado para qualquer usuário ter acesso, ao ser procurado na barra de pesquisa, na página inicial
- Não é necessário que convide membros durante a criação do channel

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US10

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US10 | Usuário | Criar channel privado | para que seja acessado apenas por convite e visivel somente por seus membros | É necessário um nome para o channel, porém não é obrigatório convidar membros no momento de sua criação | 5 | Must |Funcional|

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

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US11

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US11 | Usuário | Enviar mensagem direta | gostaria de enviar mensagens privadas para determinado usuário|  | 5 | Must |Funcional|

- Conversa iniciada ao acessar o perfil de um usuário na lista de membros de um channel, ou ao procura-lo na barra de pesquisa, na página inicial

_Originada em: [INT1.1](../Elicitação/Introspeccao.md#introspeccao-01), [INT2.5](../Elicitação/Introspeccao.md#introspeccao-02), [INT3.1](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AP4](../Elicitação/analprot.md#requisitos-elicitados), [Q16](../Elicitação/questionario.md#requisitos-elicitados), [C3](cenarios.md#c3-v2)_

#### US12

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US12 | Usuário | criar um canal onde apenas eu posso enviar mensagens | assim posso usa-lo como uma lista de transmissão e não canal de discussão | canal apenas de leitura | 5 | Should |

- No momento em que é criado um canal deve existir a opção only-read channel
- Apenas o usuário o qual criou o canal deve poder enviar mensagens
- Apenas administradores devem poder convidar pessoas para o canal
- O nome do canal deve possuir ao menos um caractere
- Não é necessário que convide membros durante a criação do channel


### EP06 - Mensagens

#### US13

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US13 | Usuário | Enviar uma mensagem de texto | para poder me comunicar de forma escrita com os membros de um channel|  | 5 | Must |Funcional|

* O usuário deverá ser capaz de enviar uma mensagem de texto para qualquer channel que ele faça parte
* A mensagem enviada deverá ser recebida por todos os membros que fazem parte daquele channel
* Não deve haver limite de caracteres para uma mensagem

_Originada em: [INT4.1](../Elicitação/Introspeccao.md#introspeccao-04),
[Storyboard 1](../Elicitação/Storyboard.md#4-requisitos-obtidos)_

#### US14

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US14 | Usuário | Enviar um arquivo | para poder enviar qualquer documento ou arquivo que esteja armazenado no meu dispositivo para os demais membros do channel| Este arquivo pode ser uma foto, vídeo, documento, áudio, etc | 5 | Must |Funcional|

* Ao selecionar essa opção o usuário deverá buscar no armazenamento do seu dispositivo o arquivo que deseja enviar
* O arquivo enviado deverá ser recebido por todos os membros que fazem parte daquele channel

_Originada em: [INT2.1](../Elicitação/Introspeccao.md#introspeccao-02),
[Q6](../Elicitação/questionario.md#requisitos-elicitados)_

#### US15

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US15 | Usuário | Enviar um emoji| para poder demonstrar minha reação ou sentimento em um channel|  | 3 | Could |Funcional|

* O usuário poderá enviar emojis ou gifs, que estarão divididos por categorias
* O emoji enviado deverá ser recebido por todos os membros que fazem parte daquele channel

#### US16

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US16 | Usuário | Enviar mensagem de áudio| para mandar mensagem de voz ao invés de escreve um texto |  | 5 | Could |Funcional|

* O usuário poderá enviar mensagem de áudio com tempo ilimitado

_Originada em: [INT1.5](../Elicitação/Introspeccao.md#introspeccao-01),
[Q6](../Elicitação/questionario.md#requisitos-elicitados)_

#### US17

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US17 | Usuário | Editar uma mensagem que foi enviada em um channel| para poder corrigir erros ou fazer quaisquer alterações na mesma|  | 5 | Should |Funcional|

* O usuário deve poder editar a mensagem a qualquer momento após tê-la enviado

#### US18

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US18 | Usuário | Remover uma mensagem de um channel| para que ela não seja mais exibida dentro daquele channel e os demais membros não possam mais lê-la| É necessário que tenha um aviso de que a mensagem foi removida | 3 | Should |Funcional|

* O usuário deve poder remover uma mensagem a qualquer momento após tê-la enviado
* No lugar da mensagem removida deverá ser exibido um aviso escrito "mensagem removida"

_Originada em: [Q8](../Elicitação/questionario.md#requisitos-elicitados)_

#### US19

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US19 | Usuário | Adicionar uma reação(emoji) em uma determinada mensagem dentro de um channel| para expressar o sentimento ou sensação que tive ao ler aquela mensagem| A reação deverá ficar junto á mensagem que foi "reagida" | 2 | Would |Funcional|

* O usuário deverá poder adicionar uma reação para uma mensagem enviada em um channel da qual faz parte
* Se vários usuários adicionarem reações a uma mesma mensagem, todas as reações deverão ser exibidas

#### US20

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US19 | Usuário | Responder uma mensagem de um channel| para que o usuário que a enviou saiba que aquela resposta foi direcionada a sua mensagem|  | 5 | Should |Funcional|

* O usuário deverá poder responder uma mensagem que foi enviada em um channel
* Uma mensagem de resposta deve exibir junto a ela a mensagem que está sendo respondida

#### US21

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US21 | Usuário | Reportar uma mensagem de um channel| para indicar que aquela mensagem foi ofensiva de alguma forma |  | 5 | Could |Funcional|

* O usuário deve poder reportar qualquer mensagem que tenha sido enviada no channel caso deseje

## T04 - Servidor

### EP07 - Conectar com um servidor

#### US22

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US22 | Usuário | Conectar com um servidor da aplicação | para que eu possa acessar o servidor em que meu time/empresa esteja utilizando para se comunicar | Deve conter o nome do servidor e provedor | 3 | Must |Funcional|

* O endereço de servidor deve ser validado, conter o nome do servidor e provedor
* Deve ser aplicado um protocolo de conexão

*Originada em: [ENT1.7](../Elicitação/Entrevista.md#requisitos),[INT1.4](../Elicitação/Introspeccao.md#introspeccao-01),  [INT3.2](../Elicitação/Introspeccao.md#introspeccao-03), [Storyboard 4](../Elicitação/Storyboard.md#4-requisitos-obtidos), [AD13](../Elicitação/analdiscurso.md#requisitos-elicitados), [AP2](../Elicitação/analprot.md#requisitos-elicitados), [C4](cenarios.md#c4-v2)*

### EP08 - Segurança 

#### US23

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US23 | Usúario | estar em uma conexão segura | preciso transmitir mensagens confidenciais com minha equipe | independente do usuário possuir um servidor particular ou não |  | Must | Não-funcional |

#### US4 

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US24 | Usuário administrador do servidor | Definir opção para criptografar meus channels por chave E2E | preciso transitir mensagens confidenciais com minha equipe | independente do usuário possuir um servidor particular ou não | | Must | Não-funcional | 

### EP09 - Suporte a grandes Equipes

#### US25

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US25 | Usuário administrador do servidor | Adicionar vários channels e usuários ao servidor dedicado | preciso que todas as equipes envolvidas no(s) projeto(s) tenham acesso aos channels que representam suas equipes | O servidor deve suportar o aumento de usuários | | Must | não-funcional | 

### EP10 - Diretório

#### US26

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US26 | Usuário | Verificar todos os Channels do servidor | desejo saber a relação de Channels criados no servidor | Opções disponíveis apenas no Desktop | | Would | Funcional |

#### US27

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |Tipo |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US27 | Usuário | Verificas todos os usuários do servidor | desejo saber a relação de todos os usuários cadastrados no servidor | desejo saber a relação de todos os usuários cadastrados no servidor | Opções disponíveis apenas no Desktop | | | Would | Funcional | 


## T06 - Arquitetura do Software

### EP - Escalar Servidor

#### TS1

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| TS1 | Arquiteto do projeto | que o software possua uma arquitetura escalável para que ele possa atender mais pessoas de forma mais estável | assim mantenho o servidor funcionando de forma adequada para todos os usuários | | 13 | Should |

* A arquitetura deve permitir que o servidor além de ser escalável possoa funcionar sob uma infraestrutura on-premise
* A aquitetura deve permitir instâncias individuais do software

*Originada em: [ENT1.9](../Elicitação/Entrevista.md#requisitos)*

### EP - Instanciar servidor on-premise

#### US23

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| US23 | Usuário | fazer minha própria instancia do software com infraestrutura on-premise | assim tenho mais controle dos dados os quais são enviados no servidor o qual uso |  | 13 | Must |

* O serviço deve ser suportado por servidor Linux

*Originada em: [ENT1.7](../Elicitação/Entrevista.md#requisitos)*

## T05 - 


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 07/05/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 07/05/2019 | 1.1 | Inclusão dos épicos EP01 e EP02 | Marcos Nery |
| 07/05/2019 | 1.2 | Inclusão do épico EP03 | Heron Rodrigues |
| 07/05/2019 | 1.3 | Inclusão do tema T03 | Weiller Fernandes |
| 08/05/2019 | 1.4 | Inclusão do tema T04 | Heron Rodrigues |
| 07/05/2019 | 1.2 | Inclusão do épico EP05 | Heron Rodrigues |
| 07/05/2019 | 1.3 | Inclusão do tema EP06 | Weiller Fernandes |
| 08/05/2019 | 1.4 | Inclusão do tema T04 | Heron Rodrigues |
| 08/05/2019 | 1.5 | Inclusão do tema T03, com EP03 e 04 | Marcos Nery |
| 08/05/2019 | 1.6 | Melhor formatação das tabelas | Marcos Nery |
| 08/05/2019 | 1.7 | Inclusão dos pontos da US13 a US20 | Weiller Fernandes |
| 08/05/2019 | 1.8 | Inclusão da restreabilidade nas US13, US14, US16 e US18 | Weiller Fernandes |
| 08/05/2019 | 1.9 | Inclusão de tema T06, US12, TS1 e US23 | João Lucas |
| 08/05/2019 | 2.0 | Inclusão dos épicos EP8, EP9, EP10 | João Lucas |
