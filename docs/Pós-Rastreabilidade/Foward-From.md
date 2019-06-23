# Foward-From

Neste documento busca-se construir a matriz de pós-rastreabilidade através da ótica Foward-From. Foram feitas duas tabelas, a primeira para requisitos funcionais e a segunda para os não funcionais.

## Metodologia

Para o desenvolvimento do documento a seguir, a equipe decidiu separa-lo em duas tabelas, a primeira tabela com os requisitos funcionais e a segunda para os requisitos não-funcionais. Como vários membros da equipe iriam trabalhar no documento ao mesmo tempo, foram criadas duas tabelas no drive, para evitar a repetição de requisitos na tabela, que posteriormente seriam convertidas para formato markdown e colocadas na wikia. Link para as tabelas no drive: [funcionais](https://docs.google.com/spreadsheets/d/17uv-YxoEdDHEgwkEWWxdQUYqHkHEk-N381ivfJEQQyI/edit#gid=0) e [não-funcionais](https://docs.google.com/spreadsheets/d/1HN24HaJRe7yE16k5k425cvma3hwgEx9qS4XVkG3EEkM/edit#gid=0).


## Requisitos Funcionais

|Código|Descrição|Tema|Épico|US|Funcionalidade|Código|
|---|---|---|----|----|---|
|RF1 |Tradução instântanea para mensagens em línguas diferentes da padrão|[T04](../Modelagem/backlog.md#t04-channel)|[EP11](../Modelagem/backlog.md#ep11-acoes-do-channel)| [US45](../Modelagem/backlog.md#us45)|[Tradução](#rf1_gif)||
|RF2 |O aplicativo deve ser capaz de realizar videoconferências em  grupo|[T04](../Modelagem/backlog.md#t04-channel) | [EP11](../Modelagem/backlog.md#ep11-acoes-do-channel)|[US46](../Modelagem/backlog.md#us46)|[Videoconferência em grupo](#rf2_gif)||
|RF3   |A aplicação deve oferecer ao usuário a possibilidade de entrar no app através de username e senha, previamente cadatrados no aplicativo      |[T01](../Modelagem/backlog.md#t01-entrar-no-aplicativo)|[EP01](Modelagem/backlog.md/#ep01-fazer-login)                                                                           |[US01](../Modelagem/backlog.md#us01)<br> [US02](../Modelagem/backlog.md#us02) |                                      [Login](#RF3_gif)<br>| [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/LoginView.js) <br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/login.js)|
|RF4   |O app deve permitir o cadastro na aplicação por contas de serviços de terceiros ou a partir de dados do usuário, como email, username e senha|[T01](../Modelagem/backlog.md#t01-entrar-no-aplicativo)|[EP02](../Modelagem/backlog.md/#ep02-fazer-cadastro)                                                                     |[US03](../Modelagem/backlog.md#us03)<br> [US04](../Modelagem/backlog.md#us04)                                       |[Cadastro](#rf4_gif) <br>| [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RegisterView.js)<br> [Utils](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/isValidEmail.js)|
|RF5   |O usuário deve ter a disposição, a criação de canais, subgrupos de discussão e grupos, privados/publicos, ilimitados.| [T04](../Modelagem/backlog.md#t04-channel)                       |[EP08](../Modelagem/backlog.md/#ep08-criar-channel)                                                                      |[US18](../Modelagem/backlog.md#us18) <br> [US19](../Modelagem/backlog.md#us19) <br> [US21](../Modelagem/backlog.md#us21)      |[Criar channel](#rf5_gif) <br>| [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/CreateChannelView.js)<br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/createChannel.js) |
|RF6   |O usuário deve ser capaz de, dentro da plataforma, enviar mensagens dentro de grupos de conversa ou dentro de chats privados |[T04](../Modelagem/backlog.md#t04-channel)                |[EP08](../Modelagem/backlog.md/#ep08-criar-channel)                                                                      |[US20](../Modelagem/backlog.md#us20)                                                                               |[Enviar mensagem](#rf6_gif)<br>| [Código - Método "sendMessage"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomView/index.js)           |
|RF7   |O usuário deve ser capaz de realizar uma busca de uma mensagem dentro de um determinado chat                                                 |[T04](../Modelagem/backlog.md#t04-channel)|[EP11](../Modelagem/backlog.md#ep11-acoes-do-channel)                                                                      |[US48](../Modelagem/backlog.md#us48)                                                                               | [Procurar mensagem](#RF7_gif)<br>| [Código](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/SearchMessagesView/index.js) |
|RF8   |O app deve oferecer a possibilidade do usuário instalar seu próprio servidor local. |[T05](../Modelagem/backlog.md#t05-servidor)|[EP16](../Modelagem/backlog.md#ep16-conectar-com-um-servidor)  |[US65](../Modelagem/backlog.md#us65) | [Servidor](#rf8_gif) ||
|RF9   |A plataforma deve permitir a integração de Bots|[T04](../Modelagem/backlog.md#t04-channel)|[EP14](../Modelagem/backlog.md#ep14-integrações) |[US62](../Modelagem/backlog.md#us62) |  [Bots](#rf9_gif) ||
|RF10  |A plataforma deve permitir a alteração nas configurações do app |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP05](../Modelagem/backlog.md#ep05-configurações-do-aplicativo)|[US09](../Modelagem/backlog.md#us09)| [Configurações do app](#rf10_gif)<br>| [View](https://github.com/RocketChat/Rocket.Chat.ReacótNative/blob/develop/app/views/SettingsView/index.js)<br> [Action](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/actions/markdown.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/deviceInfo.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js)|
|RF11  |Possibilidade de alteração do idioma no aplicativo                                                                                           |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP05](../Modelagem/backlog.md#ep05-configurações-do-aplicativo)|[US09](../Modelagem/backlog.md#us09), [US10](../Modelagem/backlog.md#us10)                                      | [Alterar idioma](#rf11_gif)| [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/LanguageView/index.js)<br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js)
|RF12  ||| |[](#rf12_gif)||
|RF13  |Alteração de senha |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP05](../Modelagem/backlog.md#ep05-configurações-do-aplicativo)|[US12](../Modelagem/backlog.md#us12) | [Alterar senha](#rf13_gif)<br> |[Código - Método "newPassword"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/ProfileView/index.js)
|RF14  |Possibilidade de mencionar, um ou todos, os membros do grupo |[T04](../Modelagem/backlog.md#t04-channel)|[EP11](../Modelagem/backlog.md#ep11-acoes-do-channel) |[US43](../Modelagem/backlog.md#us43)|  [Mencionar](#rf14_gif) ||
|RF15  |Sistema deve ser capaz de Adicionar autenticação de 2 Fatores  |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP06](../Modelagem/backlog.md#ep06-configurações-da-conta)|[US13](../Modelagem/backlog.md#us13) | [Autenticação 2 Fatores](#rf15_gif)||
|RF16  |Sistema deve mostrar e permitir a edição das configurações da conta |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP05](../Modelagem/backlog.md#ep05-configurações-do-aplicativo)<br> [EP06](../Modelagem/backlog.md#ep06-configurações-da-conta)|[US09](../Modelagem/backlog.md#us09) <br> [US14](../Modelagem/backlog.md#us14) | [Editar conta](#rf16_gif) <br>| [View](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/ProfileView/index.js) <br> [Util](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/utils/info.js) |
|RF17  |O sistema deve permitir o envio de arquivos e documentos em um chat |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens)  |[US28](../Modelagem/backlog.md#us28) <br> [US33](../Modelagem/backlog.md#us33) |  [Envio de Arquivo](#rf17_gif) ||
|RF18  |Permitir a alteração do status do usuário                                                                                                    |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP06](../Modelagem/backlog.md#ep06-configurações-da-conta)                                                                |[US15](../Modelagem/backlog.md#us15)                                                                            | [Alterar status](#rf18_gif) <br>| [Código - Método "renderStatusItem"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/SidebarView/index.js)  |
|RF19  |App deve possuir ferramenta para busca de Channels                                                                                           |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP07](../Modelagem/backlog.md#ep07-channels)                                                                              |[US16](../Modelagem/backlog.md#us16)                                                                            | [Buscar channel](#rf_19_gif) <br>| [Código - Método "search"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomsListView/index.js)   |
|RF20  |App deve possuir opções para listar Channels em categorias |[T03](../Modelagem/backlog.md#t03--visao-geral-do-aplicativo)|[EP07](../Modelagem/backlog.md#ep07-channels) |[US17](../Modelagem/backlog.md#us17) | [Ordenar por categoria](#rf20_gif) <br>| [Código - Método "groupByType"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomsListView/index.js)    |
|RF21  |Possibilidade de favoritar um grupo |[T04](../Modelagem/backlog.md#t04-channel)|[EP11](../Modelagem/backlog.md#ep11-acoes-do-channel)|[US42](../Modelagem/backlog.md#us42)|  [Favoritar Channel](#rf21_gif)||
|RF22  |Permitir a alteração de privacidade do Channel|[T04](../Modelagem/backlog.md#t04-channel)|[EP09](../Modelagem/backlog.md#ep09-configurações-do-channel) |[US22](../Modelagem/backlog.md#us22)| [Privacidade do Channel](#rf22_gif)||
|RF23  |Definir Channel como Read Only |[T04](../Modelagem/backlog.md#t04-channel)|[EP09](../Modelagem/backlog.md#ep09-configurações-do-channel) |[US23](../Modelagem/backlog.md#us23) |  [Read Only](#rf23_gif)||
|RF24  |Definir Channel para BroadCast |[T04](../Modelagem/backlog.md#t04-channel)|[EP09](../Modelagem/backlog.md#ep09-configurações-do-channel) |[US24](../Modelagem/backlog.md#us24) | [BroadCast](#rf24_gif) ||
|RF25  |Permitir que o usuário possa adicionar ou visualizar as informações do Channel através de uma descrição, tópico do Channel |[T04](../Modelagem/backlog.md#t04-channel)|[EP09](../Modelagem/backlog.md#ep09-configurações-do-channel) <br>  [EP11](../Modelagem/backlog.md#ep11-acoes-do-channel) |[US25](../Modelagem/backlog.md#us25) <br> [US26](../Modelagem/backlog.md#us26) <br> [US47](../Modelagem/backlog.md#us47)| [Adicionar descrição](#rf25_gif) <br> |[Código - Método "description"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomInfoEditView/index.js) |
|RF26  |App deve permitir o envio de desenhos, como mensagens |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US30](../Modelagem/backlog.md#us30) | [Desenho](#rf26_gif) ||
|RF27  |O sistema deve permitir o envio de arquivos de midia, como vídeo e áudio |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US31](../Modelagem/backlog.md#us31) | [Midia](#rf27_gif) ||
|RF28  |O usuário deve poder editar suas mensagens enviadas |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US34](../Modelagem/backlog.md#us34) | [Editar Mensagens](#rf28_gif) ||
|RF29  |O usuário deve poder copiar uma mensagem |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US35](../Modelagem/backlog.md.md#us35) | [Copiar Mensagem](#rf29_gif) ||
|RF30  |O sistema deve oferecer uma maneira para o usuário possa compartilhar mensagens |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US36](../Modelagem/backlog.md#us36) | [Compartilhar Mensagens](#rf30_gif) ||
|RF31  |O usuário deve ter a possibilidade excluir uma mensagem a qualquer momento |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US38](../Modelagem/backlog.md#us38) | [Excluir Mensagem](#rf31_gif) ||
|RF32  |Usuário deve poder adicionar reações a mensagens |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US39](../Modelagem/backlog.md#us39) | [Adicionar reação a mensagens](#rf32_gif) <br> |[Código - Método "onReactionPress"](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/views/RoomView/index.js) <br> [Código](https://github.com/RocketChat/Rocket.Chat.ReactNative/blob/develop/app/containers/ReactionsModal.js) |
|RF33  |Usuário deve ser capaz de responder mensagens enviadas dentro de Channels que ele participa |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US40](../Modelagem/backlog.md#us40) | [Responder Mensagem](#rf33_gif) ||
|RF34  |Usuário deve ter a possibilidade de reportar alguma mensagem em um Channel que não respeite as diretrizes do app |[T04](../Modelagem/backlog.md#t04-channel)|[EP10](../Modelagem/backlog.md#ep10-mensagens) |[US41](../Modelagem/backlog.md#us41) | [Reportar Mensagem](#rf34_gif)||
|RF35  | | | | [](#rf35_gif)||
|RF36  |A aplicação deve fornecer suporte aos seus usuários via chat e e-mail.|[T02](../Modelagem/backlog.md#t02-ajuda-ao-usuario)|[EP03](../Modelagem/backlog.md/#ep02-atendimento-online)|[US05](../Modelagem/backlog.md#us05) <br>  [US06](../Modelagem/backlog.md#us06) |[Suporte](#rf36_gif) ||
|RF37  | | | | ||


## Requisitos Não-Funcionais

|Código|Descrição                                                                                                                    |NFR                                                          |Operacionalizações                                                                                              |Funcionalidade                                                                                                                                                                |
|------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|RNF1  |A aplicação deve ser capaz de ser executada em diversas plataformas                                                          |[NFR-Portabilidade](../Modelagem/nfr.md#nfr1-portabilidade)  |"Acesso por aplicação mobile".  "Acesso por aplicação web";  "Acesso por aplicação desktop";                    |[Plataformas](#rnf1)                                                                                                                                                              |
|RNF2  |O Rocket.chat deve ofecer suporte tanto para a aplicação, em diversas arquiteturas, como para o usuário                      |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)                   |"Documentação" "Suporte online"                                                                                 |    [Suporte](#rnf2)                                                                                                                                                                          |
|RNF3  |Deve ser uma plataforma que ofereça segurança com dados dos usuários.                                                        |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)                   |"Criptografia ponta a ponta" "Backup de dados"                                                                  |                                                                                                                                                                              |
|RNF4  |O Rocket.chat deve estar disponível na maior quantidade possível de idiomas                                                  |[NFR-05](../Modelagem/nfr.md#nfr5-personabilidade)           |"Traduzir todos os menus do app para diferentes linguagens" "permitir a escolha de nova linguagem dentro do app"|                                                                                                                                                                              |
|RNF5  |O Rocket.chat deve ter uma boa interface visual, minimalista e intuitiva, facilitando a usabilidade do usuário.              |[NFR-04](../Modelagem/nfr.md#nfr4-usabilidade)               |"Layout simples"; "Icones intuitivos"; "Descrições"                                                             |[Repositório aplicação desktop/web](https://github.com/RocketChat/Rocket.Chat.Electron)  [Repositório aplicação mobile](https://github.com/RocketChat/Rocket.Chat.ReactNative)|
|RNF6  |A plataforma deve possuir uma documentação bem organizada. Que explique todas as funcionalidades e restrições aplicáveis.    |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)                   |"Documentação"                                                                                                  |                                                                                                                                                                              |
|RNF7  |A aplicação, sendo do tipo openSource, deve possuir a liberdade da contribuição pela comunidade de software                  |[NFR-08](../Modelagem/nfr.md#nfr8-contribuiçao-da-comunidade)|"Encorajar a evolução do código existente""Divulgar as vantagens da comunidade ser ativa"                       |                                                                                                                                                                              |
|RNF8  |A aplicação deve oferecer uma performace fluida ajude na experiência positiva do usuário                                     |[NFR-02](../Modelagem/nfr.md#nfr2-performace-do-chat)        |"Compressão de dados" "uso de cach para dados não modificados"                                                  |                                                                                                                                                                              |
|RNF9  |Visando uma melhor experiência ao usuário e desempenho da plataforma, o app deve fazer integrações com diferentes plataformas|[NFR-09](../Modelagem/nfr.md#nfr2-conectividade)             |"Integrável com redes sociais para autenticação"                                                                |                                                                                                                                                                              |
|RNF10 |A plataforma deve identificar e tratar erros dentro do aplicativo                                                            |                                                             |                                                                                                                |                                                                                                                                                                              |



## Gifs

### RF1_GIF

![](../img/PosRastreabilidade/RF01.gif)

### RF2_GIF

![](../img/PosRastreabilidade/RF02.gif)

### RF3_GIF

![Login](../img/PosRastreabilidade/rf3.gif)

### RF4_GIF

![Cadastro](../img/PosRastreabilidade/rf4.gif)

### RF5_GIF

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

Mobile

![](../img/PosRastreabilidade/rnf1_03.gif)

Web navegador

![](../img/PosRastreabilidade/rnf1_01.gif)

Desktop

![](../img/PosRastreabilidade/rnf1_02.gif)

### rnf2

Suporte

![](../img/PosRastreabilidade/rnf2_02.gif)

![](../img/PosRastreabilidade/rnf2_01.gif)

## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 16/06/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 17/06/2019 | 1.1 | Inclusão das tabelas inicias de requisitos | Marcos Nery |
| 18/06/2019 | 1.2 | Inclusão dos elos | Marcos Nery |
| 19/06/2019 | 1.3 | Inclusão dos GIFS | André Lucas |
