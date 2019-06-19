# Foward-From

Neste documento busca-se construir a matriz de pós-rastreabilidade através da ótica Foward-From. Foram feitas duas tabelas, a primeira para requisitos funcionais e a segunda para os não funcionais.


## Requisitos Funcionais

|Código|Descrição|US|Épico|Funcionalidade|
|---|---|---|----|----|
|RF1 |Tradução instântanea para mensagens em línguas diferentes da padrão| [US45](../Modelagem/backlog#us45)|[EP11](../Modelagem/backlog#ep11-acoes-do-channel)| |
|RF2 |O aplicativo deve ser capaz de realizar videoconferências em  grupo| [US46](../Modelagem/backlog#us46)| [EP11](../Modelagem/backlog#ep11-acoes-do-channel)| |
|RF3   |A aplicação deve oferecer ao usuário a possibilidade de entrar no app através de username e senha, previamente cadatrados no aplicativo      |[US01](../Modelagem/backlog.md#us01)<br> [US02](../Modelagem/backlog.md#us02)                                       |[EP01](Modelagem/backlog.md/#ep01-fazer-login)                                                                           |[Login](#RF3_GIF)<br> [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/LoginView.js) <br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/login.js)|
|RF4   |O app deve permitir o cadastro na aplicação por contas de serviços de terceiros ou a partir de dados do usuário, como email, username e senha|[US03](../Modelagem/backlog.md#us03)<br> [US04](../Modelagem/backlog.md#us04)                                       |[EP02](../Modelagem/backlog.md/#ep02-fazer-cadastro)                                                                     |[Cadastro](#RF4_GIF) <br> [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RegisterView.js)<br> [Utils](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/isValidEmail.js)|
|RF5   |O usuário deve ter a disposição, a criação de canais, subgrupos de discussão e grupos, privados/publicos, ilimitados.                        |[US18](../Modelagem/backlog#us18) <br> [US19](../Modelagem/backlog#us19) <br> [US21](../Modelagem/backlog.md#us21)      |[EP08](../Modelagem/backlog.md/#ep08-criar-channel)                                                                      |[Criar channel](#RF5_GIF) <br> [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/CreateChannelView.js)<br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/createChannel.js) |
|RF6   |O usuário deve ser capaz de, dentro da plataforma, enviar mensagens dentro de grupos de conversa ou dentro de chats privados                 |[US20](../Modelagem/backlog#us20)                                                                               |[EP08](../Modelagem/backlog.md/#ep08-criar-channel)                                                                      |[Enviar mensagem](#RF6_GIF)<br> [Código - Método "sendMessage"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomView/index.js)           |
|RF7   |O usuário deve ser capaz de realizar uma busca de uma mensagem dentro de um determinado chat                                                 |[US48](../Modelagem/backlog#us48)                                                                               | [EP11](../Modelagem/backlog#ep11-acoes-do-channel)                                                                      |[Procurar mensagem](#RF7_GIF)<br> [Código](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/SearchMessagesView/index.js) |
|RF8   |O app deve oferecer a possibilidade do usuário instalar seu próprio servidor local. |[US65](../Modelagem/backlog#us65) | [EP16](../Modelagem/backlog#ep16-conectar-com-um-servidor)  |[Servidor](#RF8_GIF) |
|RF9   |A plataforma deve permitir a integração de Bots|[US62](../Modelagem/backlog#us62) | [EP14](../Modelagem/backlog#ep14-integrações) | [Bots](#RF9_GIF) |
|RF10  |A plataforma deve permitir a alteração nas configurações do app |[US09](../Modelagem/backlog#us09)| [EP05](../Modelagem/backlog#ep05-configurações-do-aplicativo)|[Configurações do app](#RF10_GIF)<br> [View](https://github.com/RocketChat/Rocket.Chat.ReacótNative/blob/develop/app/views/SettingsView/index.js)<br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/markdown.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/deviceInfo.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js)|
|RF11  |Possibilidade de alteração do idioma no aplicativo                                                                                           |[US09](../Modelagem/backlog.md#us09), [US10](../Modelagem/backlog.md#us10)                                      | [EP05](../Modelagem/backlog#ep05-configurações-do-aplicativo)|[Alterar idioma](#RF11_GIF) [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/LanguageView/index.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js)
|RF12  ||| |[](#RF12_GIF)|
|RF13  |Alteração de senha |[US12](../Modelagem/backlog.md#us12) | [EP05](../Modelagem/backlog#ep05-configurações-do-aplicativo)|[Alterar senha](#RF13_GIF)<br> [Código - Método "newPassword"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/ProfileView/index.js)
|RF14  |Possibilidade de mencionar, um ou todos, os membros do grupo |[US43](../Modelagem/backlog.md#us43)| [EP11](../Modelagem/backlog#ep11-acoes-do-channel) | [Mencionar](#RF14_GIF) |
|RF15  |Sistema deve ser capaz de Adicionar autenticação de 2 Fatores  |[US13](../Modelagem/backlog.md#us13) | [EP06](../Modelagem/backlog#ep06-configurações-da-conta)|[Autenticação 2 Fatores](#RF15_GIF)|
|RF16  |Sistema deve mostrar e permitir a edição das configurações da conta |[US09](../Modelagem/backlog.md#us09) <br> [US14](../Modelagem/backlog.md#us14) | [EP05](../Modelagem/backlog#ep05-configurações-do-aplicativo)<br> [EP06](../Modelagem/backlog#ep06-configurações-da-conta)|[Editar conta](#RF16_GIF) <br> [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/ProfileView/index.js) <br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js) |
|RF17  |O sistema deve permitir o envio de arquivos e documentos em um chat |[US28](../Modelagem/backlog.md#us28) <br> [US33](../Modelagem/backlog.md#us33) | [EP10](../Modelagem/backlog#ep10-mensagens)  | [Envio de Arquivo](#RF17_GIF) |
|RF18  |Permitir a alteração do status do usuário                                                                                                    |[US15](../Modelagem/backlog.md#us15)                                                                            | [EP06](../Modelagem/backlog#ep06-configurações-da-conta)                                                                |[Alterar status](#RF18_GIF) <br> [Código - Método "renderStatusItem"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/SidebarView/index.js)  |
|RF19  |App deve possuir ferramenta para busca de Channels                                                                                           |[US16](../Modelagem/backlog.md#us16)                                                                            | [EP07](../Modelagem/backlog#ep07-channels)                                                                              |[Buscar channel](#rf_19_gif) <br> [Código - Método "search"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomsListView/index.js)   |
|RF20  |App deve possuir opções para listar Channels em categorias |[US17](../Modelagem/backlog.md#us17) | [EP07](../Modelagem/backlog#ep07-channels) |[Ordenar por categoria](#RF20_GIF) <br> [Código - Método "groupByType"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomsListView/index.js)    |
|RF21  |Possibilidade de favoritar um grupo |[US42](../Modelagem/backlog.md#us42)| [EP11](../Modelagem/backlog#ep11-acoes-do-channel)| [Favoritar Channel](#RF21_GIF)|
|RF22  |Permitir a alteração de privacidade do Channel|[US22](../Modelagem/backlog.md#us22)| [EP09](../Modelagem/backlog#ep09-configurações-do-channel) |[Privacidade do Channel](#RF22_GIF)|
|RF23  |Definir Channel como Read Only |[US23](../Modelagem/backlog.md#us23) | [EP09](../Modelagem/backlog#ep09-configurações-do-channel) | [Read Only](#RF23_GIF)|
|RF24  |Definir Channel para BroadCast |[US24](../Modelagem/backlog.md#us24) | [EP09](../Modelagem/backlog#ep09-configurações-do-channel) |[BroadCast](#RF24_GIF) |
|RF25  |Permitir que o usuário possa adicionar ou visualizar as informações do Channel através de uma descrição, tópico do Channel |[US25](../Modelagem/backlog.md#us25) <br> [US26](../Modelagem/backlog.md#us26) <br> [US47](../Modelagem/backlog.md#us47)| [EP09](../Modelagem/backlog#ep09-configurações-do-channel) <br>  [EP11](../Modelagem/backlog#ep11-acoes-do-channel) |[Adicionar descrição](#RF25_GIF) <br> [Código - Método "description"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomInfoEditView/index.js) |
|RF26  |App deve permitir o envio de desenhos, como mensagens |[US30](../Modelagem/backlog.md#us30) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Desenho](#RF26_GIF) |
|RF27  |O sistema deve permitir o envio de arquivos de midia, como vídeo e áudio |[US31](../Modelagem/backlog.md#us31) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Midia](#RF27_GIF) |
|RF28  |O usuário deve poder editar suas mensagens enviadas |[US34](../Modelagem/backlog.md#us34) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Editar Mensagens](#RF28_GIF) |
|RF29  |O usuário deve poder copiar uma mensagem |[US35](../Modelagem/backlog.md#us35) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Copiar Mensagem](#RF29_GIF) |
|RF30  |O sistema deve oferecer uma maneira para o usuário possa compartilhar mensagens |[US36](../Modelagem/backlog.md#us36) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Compartilhar Mensagens](#RF30_GIF) |
|RF31  |O usuário deve ter a possibilidade excluir uma mensagem a qualquer momento |[US38](../Modelagem/backlog.md#us38) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Excluir Mensagem](#RF31_GIF) |
|RF32  |Usuário deve poder adicionar reações a mensagens |[US39](../Modelagem/backlog.md#us39) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Adicionar reação a mensagens](#RF32_GIF) <br> [Código - Método onReactionPress](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomView/index.js) <br> [Código](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/containers/ReactionsModal.js) |
|RF33  |Usuário deve ser capaz de responder mensagens enviadas dentro de Channels que ele participa |[US40](../Modelagem/backlog.md#us40) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Responder Mensagem](#RF33_GIF) |
|RF34  |Usuário deve ter a possibilidade de reportar alguma mensagem em um Channel que não respeite as diretrizes do app |[US41](../Modelagem/backlog.md#us41) | [EP10](../Modelagem/backlog#ep10-mensagens) |[Reportar Mensagem](#RF34_GIF)|
|RF35  | | | | [](#RF35_GIF)|
|RF36  |A aplicação deve fornecer suporte aos seus usuários via chat e e-mail.|[US05](../Modelagem/backlog.md#us05) <br> [US06](../Modelagem/backlog.md#us06) |[EP03](../Modelagem/backlog.md/#ep02-atendimento-online) |[Suporte](#RF36_GIF) |
|RF37  | | | | |


## Requisitos Não-Funcionais

|Código|Descrição                                                                                                                                    |NFR                                                                                                             |Operacionalizações                                                                                                       |Funcionalidade                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|------|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|RNF1  |A aplicação deve ser capaz de ser executada em diversas plataformas                                                                          |[NFR-Portabilidade](../Modelagem/nfr.md#nfr1-portabilidade)                                                     |"Acesso por aplicação mobile".  "Acesso por aplicação web";  "Acesso por aplicação desktop";                             |[Plataformas](#rnf1)                                                                                                                                                                                                                                                                                                                                                                                                                                |
|RNF2  |O Rocket.chat deve ofecer suporte tanto para a aplicação, em diversas arquiteturas, como para o usuário                                      |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)                                                                      |"Documentação" "Suporte online"                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|RNF3  |Deve ser uma plataforma que ofereça segurança com dados dos usuários.                                                                        |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)                                                                      |                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|RNF4  |O Rocket.chat deve estar disponível na maior quantidade possível de idiomas                                                                  |                                                                                                                |                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|RNF5  |O Rocket.chat deve ter uma boa interface visual, minimalista e intuitiva, facilitando a usabilidade do usuário.                              |[NFR-04](../Modelagem/nfr.md#nfr4-usabilidade)                                                                  |"Layout simples"; "Icones intuitivos"; "Descrições"                                                                      |[Repositório aplicação desktop/web](https://github.com/RocketChat/Rocket.Chat.Electron) <br> [Repositório aplicação mobile](https://github.com/RocketChat/Rocket.Chat.ReactNative)                                                                                                                                                                                                                                                                  |

## Gifs

### RF1_GIF

![](../img/PosRastreabilidade/RF01.gif)

### RF2_GIF

![](../img/PosRastreabilidade/RF02.gif)

### RF3_GIF

![Login](../img/PosRastreabilidade/rf3.gif)

### RF4_GIF

![Cadastro](../img/PosRastreabilidade/rf4.gif)

## RF5_GIF

![Criar Channel](../img/PosRastreabilidade/rf5.gif)

### RF6_GIF

![Enviar Mensagem](../img/PosRastreabilidade/rf6.gif)

### RF7_GIF

![Pesquisar Mensagem](../img/PosRastreabilidade/pesquisar_mensagem.gif)

### RF8_GIF

![](../img/PosRastreabilidade/RF8.gif)

### RF9_GIF

![](../img/PosRastreabilidade/)

### RF10_GIF

![](../img/PosRastreabilidade/RF10.gif)

### RF11_GIF

![](../img/PosRastreabilidade/)

### RF12_GIF

![](../img/PosRastreabilidade/)

### RF13_GIF

![](../img/PosRastreabilidade/RF13.gif)

### RF14_GIF

![](../img/PosRastreabilidade/RF14.gif)

### RF15_GIF

![](../img/PosRastreabilidade/RF15.gif)

### RF16_GIF

![](../img/PosRastreabilidade/RF16.gif)

### RF17_GIF

![](../img/PosRastreabilidade/RF17.gif)

### RF18_GIF

![](../img/PosRastreabilidade/RF18.gif)

### RF19_GIF

![](../img/PosRastreabilidade/RF19.gif)

### RF20_GIF

![](../img/PosRastreabilidade/RF20.gif)

### RF21_GIF

![](../img/PosRastreabilidade/RF21.gif)

### RF22_GIF

![](../img/PosRastreabilidade/RF22.gif)

### RF23_GIF

![](../img/PosRastreabilidade/RF23.gif)

### RF24_GIF

![](../img/PosRastreabilidade/RF24.gif)

### RF25_GIF

![](../img/PosRastreabilidade/RF25.gif)

### RF26_GIF

![](../img/PosRastreabilidade/RF26.gif)

### RF27_GIF

![](../img/PosRastreabilidade/RF27.gif)

### RF28_GIF

![](../img/PosRastreabilidade/RF28.gif)

### RF29_GIF

![](../img/PosRastreabilidade/RF29.gif)

### RF30_GIF

![](../img/PosRastreabilidade/RF30.gif)

### RF31_GIF

![](../img/PosRastreabilidade/RF31.gif)

### RF32_GIF

![](../img/PosRastreabilidade/RF32.gif)

### RF33_GIF

![](../img/PosRastreabilidade/RF33.gif)

### RF34_GIF

![](../img/PosRastreabilidade/RF34.gif)

### RF35_GIF

![](../img/PosRastreabilidade/)

### RF36_GIF

![](../img/PosRastreabilidade/RF36.gif)

### RF37_GIF

![](../img/PosRastreabilidade/)

### rnf1

|Mobile|Web navegador|Desktop|
|--|--|--|
|![](../img/PosRastreabilidade/rnf1_03.gif)|![](../img/PosRastreabilidade/rnf1_01.gif)|![](../img/PosRastreabilidade/rnf1_02.gif)|

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 16/06/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 17/06/2019 | 1.1 | Inclusão das tabelas inicias de requisitos | Marcos Nery |
| 18/06/2019 | 1.2 | Inclusão dos elos | Marcos Nery |
| 19/06/2019 | 1.3 | Inclusão dos GIFS | André Lucas |
