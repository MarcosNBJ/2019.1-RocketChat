# Backward-From

Neste documento busca-se construir a matriz de pós-rastreabilidade através da ótica Backward-From. Foram feitas duas tabelas, a primeira para requisitos funcionais e a segunda para os não funcionais. Além disso, abaixo das duas, podem ser vistos os elos de Toranzo citados.

## Metodologia

Para o desenvolvimento do documento a seguir, a equipe decidiu separa-lo em duas tabelas, a primeira tabela com os requisitos funcionais e a segunda para os requisitos não-funcionais. Como vários membros da equipe iriam trabalhar no documento ao mesmo tempo, foram criadas duas tabelas e um documento para a descrição dos elos de Toranzo, no drive, para evitar a repetição de requisitos na tabela, que posteriormente seriam convertidos para formato markdown e colocados na wikia. Link para os documentos no drive: [funcionais](https://docs.google.com/spreadsheets/d/168HYGph8Eej0beBT-cx17m5uqU7ri8c5_yXTadeorXA/edit#gid=0),  [não-funcionais](https://docs.google.com/spreadsheets/d/1UpGv5ptRkG0C3dM1Lm2cr5km9RnHXvbDRiUhfuSoFic/edit#gid=0) e [elos de Toranzo](https://docs.google.com/document/d/1bHJZ8CRE6feJlxCX8M_u0xksos1K2PCDmhw3TzwfqVw/edit).

## Requisitos Funcionais


|Código|Descrição                                                                                                                                            |Elicitação                                                                                                                                                                                                                                                                                                                                                     |Modelagem                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |Elo          |
|------|-----------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
|RF1   |Tradução instântanea para mensagens em línguas diferentes da padrão                                                                                  |[AD1](../Elicitação/analdiscurso#requisitos-elicitados) <br> [INT4.4](../Elicitação/Introspeccao#introspeccao-04)<br> [Storyboard3](../Elicitação/Storyboard#4-requisitos-obtidos)                                                                                                                                                                                    |[L31](../Modelagem/lexicos#31) <br> [US45](../Modelagem/backlog#us45) <br> [ISR05](../Modelagem/istar#isr05-acoes-sobre-o-channel)                                                                                                                                                                                                                                                                                                                                                |[EF1](#ef1)  |
|RF2   |O aplicativo deve ser capaz de realizar videoconferências em grupo                                                                                   |[AD2](../Elicitação/analdiscurso#requisitos-elicitados) <br> [AD3](../Elicitação/analdiscurso#requisitos-elicitados)<br> [INT1.4](../Elicitação/Introspeccao#introspeccao-01)<br> [INT3.5](../Elicitação/Introspeccao#introspeccao-03)<br> [Storyboard 2 e 3](../Elicitação/Storyboard#4-requisitos-obtidos)<br> [Q12](../Elicitação/questionario#requisitos-elicitados)       |[L25](../Modelagem/lexicos#25)<br> [C2](../Modelagem/cenarios#c2-v2)<br> [DCU1-V2](../Modelagem/diagramas#dcu1-v2)<br> [EC20](../Modelagem/especificacao#ec20)<br> [US46](../Modelagem/backlog#us46)<br> [ISD01](../Modelagem/istar#isd01-chat)                                                                                                                                                                                                                                          |[EF2](#ef2)  |
|RF3   |A aplicação deve oferecer ao usuário a possibilidade de entrar no app através de username e senha, previamente cadatrados no aplicativo              |[AP1](../Elicitação/analprot#requisitos-elicitados)<br> [INT1.3](../Elicitação/Introspeccao#introspeccao-01)    <br>                                                                                                                                                                                                                                                  |[C1](../Modelagem/cenarios#c1-v2)<br> [DCU13 - V1](../Modelagem/diagramas#dcu13-v1)<br> [EC21](../Modelagem/especificacao#ec21)<br> [US02](../Modelagem/backlog#us02)<br> [ISR02](../Modelagem/istar#isr02-realizar-cadastro)                                                                                                                                                                                                                                                         |[EF3](#ef3)  |
|RF4   |O app deve permitir o cadastro na aplicação por contas de serviços de terceiros ou a partir de dados do usuário, como email, username e senha        |[AP10](../Elicitação/analprot.md#requisitos-elicitados)                                                                                                                                                                                                                                                                                                        |[EP02](../Modelagem/backlog.md/#ep02-fazer-cadastro)<br> [C1](../Modelagem/cenarios.md/#c1-v2)<br> [DCU21](../Modelagem/diagramas.md/#cadastrar-novo-usuario)<br> [ECU21](../Modelagem/especificacao.md/#ec21)<br> [ISR02](../Modelagem/istar.md/#isr02-realizar-cadastro)                                                                                                                                                                                                            |[EF4](#ef4)  |
|RF5   |O usuário deve ter a disposição, a criação de canais, subgrupos de discussão e grupos, privados/publicos, ilimitados.                                |[INT1.1](../Elicitação/Introspeccao#introspeccao-01)<br> [INT3.1](../Elicitação/Introspeccao#introspeccao-03)<br> [INT4.2](../Elicitação/Introspeccao#introspeccao-04)<br> [SB2](../Elicitação/Storyboard#4-requisitos-obtidos)<br> [AP4](../Elicitação/analprot.md#requisitos-elicitados)                                                                                     |[EP08](../Modelagem/backlog.md/#ep08-criar-channel)<br>[C3](../Modelagem/cenarios.md/#c3-v2)<br> [C22](../Modelagem/cenarios.md/#c22)<br> [DCU16](../Modelagem/diagramas.md/#dcu16-v1)<br>  [DCU09](../Modelagem/diagramas.md/#dcu9-v1) <br> [ECU03](../Modelagem/especificacao.md/#ec3) <br> [ECU10](../Modelagem/especificacao.md/#ec10)<br> [ISR01](../Modelagem/istar.md/#versao-02_2)<br> [US18](../Modelagem/backlog#us18)<br> [US19](../Modelagem/backlog#us19)<br> [US21](../Modelagem/backlog.md#us21)|[EF5](#ef5)  |
|RF6   |O usuário deve ser capaz de, dentro da plataforma, enviar mensagens dentro de grupos de conversa ou dentro de chats privados                         |[INT4.1](../Elicitação/Introspeccao#introspeccao-04)<br>[SB1](../Elicitação/Storyboard.md#4-requisitos-obtidos)                                                                                                                                                                                                                                                    |[EP10](../Modelagem/backlog.md/#ep10-Mensagens)<br> [C12](../Modelagem/cenarios.md/#c12-v2)<br> [DCU2](../Modelagem/diagramas.md/#dcu2-v2)<br> [ECU15](../Modelagem/especificacao.md/#ec15)<br> [ISR03](../Modelagem/istar.md/#isr03-envio-de-mensagens)<br> [L41](../Modelagem/lexicos.md/#l41)<br> [US20](../Modelagem/backlog#us20)                                                                                                                                                       |[EF6](#ef6)  |
|RF7   |O usuário deve ser capaz de realizar uma busca de uma mensagem dentro de um determinado chat                                                         |[INT2.2](../Elicitação/Introspeccao#introspeccao-02)<br>[AD11](../Elicitação/analdiscursi#requisitos-elicitados)                                                                                                                                                                                                                                                  |[EP11](../Modelagem/backlog.md/#ep11-acoes-do-channel)<br> [L11](../Modelagem/lexicos.md/#l11) <br> [US48](../Modelagem/backlog#us48)                                                                                                                                                                                                                                                                                                                                           |[EF7](#ef7)  |
|RF8   |O app deve oferecer a possibilidade do usuário instalar seu próprio servidor local.                                                                  |[INT4.8](../Elicitação/Introspeccao#introspeccao-04)<br> [INT1.4](../Elicitação/Introspeccao#introspeccao-01) <br>[Storyboard 4](../Elicitação/Storyboard#4-requisitos-obtidos)                                                                                                                                                                                      |[EP16](../Modelagem/backlog.md/#ep16-conectar-com-um-servidor)<br> [C4](../Modelagem/cenarios.md/#c4-v2)<br> [DCU17](../Modelagem/diagramas.md/#dcu17-v2)<br> [EC11](../Modelagem/especificacao.md/#ec11)<br> [L14](../Modelagem/lexicos.md/#l14)<br> [US65](../Modelagem/backlog#us65)                                                                                                                                                                                                  |[EF8](#ef8)  |
|RF9   |A plataforma deve permitir a integração de Bots                                                                                                      |[INT3.9](../Elicitação/Introspeccao.md#introspeccao-03)<br> [ENT1.1](../Elicitação/entrevista.md#requisitos)<br> [AD7](../Elicitação/analdiscurso.md#requisitos-elicitados)<br>[Q2](../Elicitação/questionario.md#requisitos-elicitados)                                                                                                                                |[EP14](../Modelagem/backlog.md/#ep14-integraçoes)<br> [C4](../Modelagem/cenarios.md/#c4-v2)<br> [DCU17](../Modelagem/diagramas.md/#dcu17-v2)<br> [EC11](../Modelagem/especificacao.md/#ec11)<br> [L26](../Modelagem/lexicos.md/#ec14)<br> [US62](../Modelagem/backlog#us62)                                                                                                                                                                                                              |[EF9](#ef9)  |
|RF10  |A plataforma deve permitir a configuração de preferências dentro do app                                                                              |[AP8](../Elicitação/analprot.md#requisitos-elicitados)                                                                                                                                                                                                                                                                                                         |[EP05](../Modelagem/backlog.md/#ep05-configurações-do-aplicativo)<br> [NFR5](Modelagem/nfr.md#nf5-personabilidade)<br> [US09](../Modelagem/backlog#us09)                                                                                                                                                                                                                                                                                                                        |[EF10](#ef10)|
|RF11  |Possibilidade de alteração do idioma no aplicativo                                                                                                   |[INT4.5](../Elicitação/Introspeccao#introspeccao-04)<br> [Storyboard3](../Elicitação/Storyboard#4-requisitos-obtidos)                                                                                                                                                                                                                                             |[US09](../Modelagem/backlog.md#us09)<br> [US10](../Modelagem/backlog.md#us10)                                                                                                                                                                                                                                                                                                                                                                                                |[EF11](#ef11)|
|RF12  |                                                                                                                                                     |                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |[EF12](#ef12)|
|RF13  |Alteração de senha                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                               |[US12](../Modelagem/backlog.md#us12)<br> [L21](../Modelagem/lexicos.md#l21)<br> [L41](../Modelagem/lexicos.md#l41)<br> [L45](../Modelagem/lexicos.md#l45)<br> [L46](../Modelagem/lexicos.md#l46)                                                                                                                                                                                                                                                                                      |[EF13](#ef13)|
|RF14  |Possibilidade de mencionar, um ou todos, os membros do grupo                                                                                         |[INT1.6](../Elicitação/Introspeccao#introspeccao-01)<br> [INT2.4](../Elicitação/Introspeccao#introspeccao-02)<br> [ENT1.5](../Elicitação/entrevista.md#requisitos)                                                                                                                                                                                                   |[US43](../Modelagem/backlog.md#us43)<br> [ISD04](../Modelagem/istar#isd04-acoes-sobre-o-channel)<br> [ISR05](../Modelagem/istar#isr05-acoes-sobre-o-channel)<br> [L4](../Modelagem/lexicos.md#l4)                                                                                                                                                                                                                                                                                  |[EF14](#ef14)|
|RF15  |Sistema deve ser capaz de Adicionar autenticação de 2 Fatores                                                                                        |                                                                                                                                                                                                                                                                                                                                                               |[US13](../Modelagem/backlog.md#us13)                                                                                                                                                                                                                                                                                                                                                                                                                                     |[EF15](#ef15)|
|RF16  |Sistema deve mostrar e permitir a edição das configurações da conta                                                                                  |[AP7](../Elicitação/analprot.md#requisitos-elicitados)                                                                                                                                                                                                                                                                                                        |[US09](../Modelagem/backlog.md#us09)<br> [US14](../Modelagem/backlog.md#us14)<br> [L08](../Modelagem/lexicos.md#l08)<br> [ISD02](../Modelagem/istar#isr02-geral)                                                                                                                                                                                                                                                                                                                    |[EF16](#ef16)|
|RF17  |O sistema deve permitir o envio de arquivos e documentos em um chat                                                                                  |[INT2.1](../Elicitação/Introspeccao#introspeccao-02)<br> [Q6](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                                                                                                                                   |[US28](../Modelagem/backlog.md#us28)<br>[US33](../Modelagem/backlog.md#us33)<br>[C9](../Modelagem/cenarios.md/#c9-v2)<br>[DCU2](../Modelagem/diagramas.md/#dcu2-v3)<br>[DCU18](../Modelagem/diagramas.md/#dcu18-v1)<br>[EC16](../Modelagem/especificacao.md/#ec16)<br>[L5](../Modelagem/lexicos.md#l5)                                                                                                                                                                                      |[EF17](#ef17)|
|RF18  |Permitir a alteração do status do usuário                                                                                                            |                                                                                                                                                                                                                                                                                                                                                               |[US15](../Modelagem/backlog.md#us15)<br> [C10](../Modelagem/cenarios.md/#c10)                                                                                                                                                                                                                                                                                                                                                                                               |[EF18](#ef18)|
|RF19  |App deve possuir ferramenta para busca de Channels                                                                                                   |[AD11](../Elicitação/analdiscurso.md#requisitos-elicitados)                                                                                                                                                                                                                                                                                                   |[US16](../Modelagem/backlog.md#us16)                                                                                                                                                                                                                                                                                                                                                                                                                                     |[EF19](#ef19)|
|RF20  |App deve possuir opções para listar Channels em categorias                                                                                           |[Q16](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                                                                                                                                                                                        |[US17](../Modelagem/backlog.md#us17)<br> [L39](../Modelagem/lexicos.md#l39)                                                                                                                                                                                                                                                                                                                                                                                                  |[EF20](#ef20)|
|RF21  |Possibilidade de favoritar um grupo                                                                                                                  |[Q15](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                                                                                                                                                                                        |[US42](../Modelagem/backlog.md#us42)<br>[L34](../Modelagem/lexicos.md#l34)<br>[L35](../Modelagem/lexicos.md#l35)                                                                                                                                                                                                                                                                                                                                                                |[EF21](#ef21)|
|RF22  |Permitir a alteração de privacidade do Channel                                                                                                       |                                                                                                                                                                                                                                                                                                                                                               |[US22](../Modelagem/backlog.md#us22)<br> [C26](../Modelagem/cenarios.md/#c26)<br> [DCU8](../Modelagem/diagramas.md/#dcu8-v1)<br> [EC2](../Modelagem/especificacao.md/#ec2)<br> [L72](../Modelagem/lexicos.md#l72)                                                                                                                                                                                                                                                                     |[EF22](#ef22)|
|RF23  |Definir Channel como Read Only                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                               |[US23](../Modelagem/backlog.md#us23)<br> [C22](../Modelagem/cenarios.md/#c22)<br> [DCU9 ](../Modelagem/diagramas.md/#dcu9-v1)<br> [EC3](../Modelagem/especificacao.md/#ec3)<br> [L69](../Modelagem/lexicos.md#l69)                                                                                                                                                                                                                                                                    |[EF23](#e23)   |
|RF24  |Definir Channel para BroadCast                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                               |[US24](../Modelagem/backlog.md#us24)                                                                                                                                                                                                                                                                                                                                                                                                                                     |[EF24](#e24)   |
|RF25  |Permitir que o usuário possa adicionar ou visualizar as informações do Channel através de uma descrição, tópico do Channel                           |                                                                                                                                                                                                                                                                                                                                                               |[US25](../Modelagem/backlog.md#us25)<br> [US26](../Modelagem/backlog.md#us26)<br> [US47](../Modelagem/backlog.md#us47)<br> [L33](../Modelagem/lexicos.md#l33)                                                                                                                                                                                                                                                                                                                      |[EF25](#e25)   |
|RF26  |App deve permitir o envio de desenhos, como mensagens                                                                                                |                                                                                                                                                                                                                                                                                                                                                               |[US30](../Modelagem/backlog.md#us30)<br> [C8](../Modelagem/cenarios.md/#c22)<br> [DCU18](../Modelagem/diagramas.md/#dcu18-v1)<br> [EC17](../Modelagem/especificacao.md/#ec17)<br> [L43](../Modelagem/lexicos.md#l43)                                                                                                                                                                                                                                                                  |[EF26](#e26)   |
|RF27  |O sistema deve permitir o envio de arquivos de midia, como vídeo e áudio                                                                             |[INT1.5](../Elicitação/Introspeccao#introspeccao-01)<br> [Q6](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                                                                                                                                   |[US31](../Modelagem/backlog.md#us31)                                                                                                                                                                                                                                                                                                                                                                                                                                     |[EF27](#e27)   |
|RF28  |O usuário deve poder editar suas mensagens enviadas                                                                                                  |                                                                                                                                                                                                                                                                                                                                                               |[US34](../Modelagem/backlog.md#us34)<br> [C5](../Modelagem/cenarios.md#c5)<br> [E19](../Modelagem/especificacao.md#ec19)<br> [DCU19](../Modelagem/diagramas.md#dcu19-v1)                                                                                                                                                                                                                                                                                                           |[EF28](#e28)   |
|RF29  |O usuário deve poder copiar uma mensagem                                                                                                             |                                                                                                                                                                                                                                                                                                                                                               |[US35](../Modelagem/backlog.md#us35)<br> [L54](../Modelagem/lexicos.md#l54)                                                                                                                                                                                                                                                                                                                                                                                                  |[EF29](#e29)   |
|RF30  |O sistema deve oferecer uma maneira para o usuário possa compartilhar mensagens                                                                      |                                                                                                                                                                                                                                                                                                                                                               |[US36](../Modelagem/backlog.md#us36)<br> [L13](../Modelagem/lexicos.md#l13)<br> [L54](../Modelagem/lexicos.md#l54)                                                                                                                                                                                                                                                                                                                                                              |[EF30](#e30)   |
|RF31  |O usuário deve ter a possibilidade excluir uma mensagem a qualquer momento                                                                           |[Q8](../Elicitação/questionario.md#requisitos-elicitados)                                                                                                                                                                                                                                                                                                      |[US38](../Modelagem/backlog.md#us38)<br> [L58](../Modelagem/lexicos.md#l58)                                                                                                                                                                                                                                                                                                                                                                                                  |[EF31](#e31)   |
|RF32  |Usuário deve poder adicionar reações a mensagens                                                                                                     |                                                                                                                                                                                                                                                                                                                                                               |[US39](../Modelagem/backlog.md#us39)<br> [L9](../Modelagem/lexicos#l9)<br> [L10](../Modelagem/lexicos#l10)                                                                                                                                                                                                                                                                                                                                                                      |[EF32](#e32)   |
|RF33  |Usuário deve ser capaz de responder mensagens enviadas dentro de Channels que ele participa                                                          |[StoryBoarding1](../Elicitação/StoryBoarding.md#4-requisitos-obtidos)                                                                                                                                                                                                                                                                                          |[US40](../Modelagem/backlog.md#us40)<br> [C7](cenarios.md#c7-v2)<br> [DCU20](../Modelagem/diagramas.md#dcu20-v1)<br> [EC18](../Modelagem/especificacao.md/#ec18)<br> [ISD01](../Modelagem/istar#isd01-chat)<br> [ISR03](../Modelagem/istar#isr03-envio-de-mensagens)                                                                                                                                                                                                                     |[EF33](#e33)   |
|RF34  |Usuário deve ter a possibilidade de reportar alguma mensagem em um Channel que não respeite as diretrizes do app                                     |                                                                                                                                                                                                                                                                                                                                                               |[US41](../Modelagem/backlog.md#us41)                                                                                                                                                                                                                                                                                                                                                                                                                                      |[EF34](#ef34)  |
|RF35  |O sistema deve ser capaz de exibir notificações para mensagens não lidas e  para menções em chats e possibilitar ao usuário a configuração das mesmas|[ENT1.4](../Elicitação/entrevista.md#requisitos)<br>[AD5](../Elicitação/analdiscurso#requisitos-elicitados)<br>[Q6](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                                                                                |[US44](../Modelagem/backlog.md#us44)<br>[C19](cenarios.md#c19)<br>[DCU14](../Modelagem/diagramas.md#dcu14-v1)<br>[EC24](../Modelagem/especificacao.md/#ec24)<br>[L28](../Modelagem/lexicos#l28)<br>[ES03](../Modelagem/suplementar.md#es03-notificacoes)                                                                                                                                                                                                                                 |[EF35](#ef35)  |
|RF36  |A aplicação deve fornecer suporte aos seus usuários via chat e e-mail.                                                                               |[ENT1.3](../Elicitação/entrevista.md#requisitos)<br> [INT3.10](../Elicitação/Introspeccao#introspeccao-03)                                                                                                                                                                                                                                                        |[US05](../Modelagem/backlog.md#us05)<br> [US06](../Modelagem/backlog.md#us06)<br> [NFR-03](../Modelagem/nfr.md#nfr3-suporte)                                                                                                                                                                                                                                                                                                                                                    |[EF36](#ef36)  |

## Requisitos Não Funcionais

|Código|Descrição                                                                                                                    |Fonte                                                                                                                                                                                                                                                                                                                                                                                          |Elicitação                                                                                                                                                                                                                                                                                           |Modelagem                                                                                                                                                                                                        |
|------|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|RNF1  |A aplicação deve ser capaz de ser executada em diversas plataformas                                                          |[Mobile e Desktop](https://rocket.chat/docs/installation/mobile-and-desktop-apps/#mobile-and-desktop-apps) <br> [Navegador web](https://rocket.chat/docs/getting-support/#supported-browser-versions)                                                                                                                                                                                               |[Q17](../Elicitação/questionario.md#requisitos-elicitados)<br> [AD6](../Elicitação/analdiscurso.md#requisitos-elicitados)<br> [SB2](../Elicitação/Storyboard.md#4-requisitos-obtidos)                                                                                                                        |[NFR-01](../Modelagem/nfr.md#nfr1-portabilidade)<br> [ES - Portabilidade](../Modelagem/suplementar.md/#portabilidade)                                                                                                |
|RNF2  |O Rocket.chat deve ofecer suporte tanto para a aplicação, em diversas arquiteturas, como para o usuário                      |[Recebendo suporte do Rocket.chat](https://rocket.chat/docs/getting-support/#getting-support)                                                                                                                                                                                                                                                                                                  |[Q1](../Elicitação/questionario.md#requisitos-elicitados)<br> [Q18](../Elicitação/questionario.md#requisitos-elicitados)<br> [AD4](../Elicitação/analdiscurso.md#requisitos-elicitados)<br> [ENT 1.3](../Elicitação/Entrevista.md#requisitos)                                                                    |[NFR-03](../Modelagem/nfr.md#nfr3-suporte)<br> [ES - Suporte a aplicação](../Modelagem/suplementar.md/#tratamento-de-falhas)<br> [ES - Suporte ao usuário](../Modelagem/suplementar.md/#requisitos-de-suporte-ao-usuario)|
|RNF3  |Deve ser uma plataforma que ofereça segurança com dados dos usuários.                                                        |[Security](https://rocket.chat/docs/contributing/security/)                                                                                                                                                                                                                                                                                                                                    |[INT1.7](../Elicitação/Introspeccao.md#requisitos)<br>[SB4](../Elicitação/StoryBoarding#4-requisitos-obtidos)<br>[AD12](../Elicitação/analdiscurso#requisitos-elicitados)                                                                                                                                  |[EP17](../Modelagem/backlog.md#us67)[NFR6](../Modelagem/nfr.md#nfr6)<br> [ES - segurança](../Modelagem/suplementar.md#segurança)                                                                                     |
|RNF4  |O Rocket.chat deve estar disponível na maior quantidade possível de idiomas                                                  |[idiomas](https://rocket.chat/docs/contributing/translating/)                                                                                                                                                                                                                                                                                                                                  |[INT4.5](../Elicitação/Introspeccao.md#requisitos)<br>[SB3](../Elicitação/StoryBoarding#4-requisitos-obtidos)<br>[AD12](../Elicitação/analdiscurso#requisitos-elicitados)                                                                                                                                  |[EP05](../Modelagem/backlog.md#us10)<br>[NFR6](../Modelagem/nfr.md#nfr6)<br> [ES25](../Modelagem/suplementar.md#es25-pluralidade-de-idiomas)                                                                             |
|RNF5  |O Rocket.chat deve ter uma boa interface visual, minimalista e intuitiva, facilitando a usabilidade do usuário.              |[Interface Intuitiva](https://rocket.chat/docs/user-guides/)                                                                                                                                                                                                                                                                                                                                   |[INT1.2](../Elicitação/Introspeccao.md#requisitos)<br> [INT2.6](../Elicitação/Introspeccao.md#requisitos)<br> [AP6](../Elicitação/analprot#requisitos-elicitados)                                                                                                                                          |[NFR-04](../Modelagem/nfr.md#nfr4-usabilidade)<br> [ES01](../Modelagem/suplementar.md#es1-fluxo-de-navegacao)<br> [ES05](../Modelagem/suplementar.md#es5-icones-e-cores)                                               |
|RNF6  |A plataforma deve possuir uma documentação bem organizada. Que explique todas as funcionalidades e restrições aplicáveis.    |[Documentação](https://rocket.chat/docs/)                                                                                                                                                                                                                                                                                                                                                      |[AD4](../Elicitação/analdiscurso.md#requisitos-elicitados)                                                                                                                                                                                                                                           |[EP04](../Modelagem/backlog.md#us07)<br>[NFR6](../Modelagem/nfr.md#nfr6)<br> [ES26 - Documentação](../Modelagem/suplementar.md#es26-documentaçao)                                                                        |
|RNF7  |A aplicação, sendo do tipo openSource, deve possuir a liberdade da contribuição pela comunidade de software                  |[Contribuição pela comunidade](https://rocket.chat/docs/contributing/)                                                                                                                                                                                                                                                                                                                         |[SB5](../Elicitação/StoryBoarding#4-requisitos-obtidos)<br>[SB5](../Elicitação/StoryBoarding#4-requisitos-obtidos)<br>[Q21](../Elicitação/questionario#requisitos-elicitados)                                                                                                                                |[ISD05](../modelagem/istar.md#isd05)<br>[ISR06](../modelagem/istar.md#isr06)<br>[NFR08](../modelagem/nfr.md#nfr08)<br>[ES30](../modelagem/suplementar.md#es30)                                                               |
|RNF8  |A aplicação deve oferecer uma performace fluida ajude na experiência positiva do usuário                                     |[performace](https://rocket.chat/docs/installation/manual-installation/multiple-instances-to-improve-performance/#run-multiple-instances-of-rocketchat)                                                                                                                                                                                                                                        |[ENT1.8](../Elicitação/questionario.md#requisitos-elicitados)                                                                                                                                                                                                                                        |[NFR-02](../Modelagem/nfr.md#nfr2-performace-do-chat)                                                                                                                                                            |
|RNF9  |Visando uma melhor experiência ao usuário e desempenho da plataforma, o app deve fazer integrações com diferentes plataformas|[Giphy Integrations](https://rocket.chat/docs/administrator-guides/integrations/giphy/#giphy-integrations) [Nextcloud and WebDAV integrations](https://rocket.chat/docs/administrator-guides/integrations/nextcloud-and-webdav/#nextcloud-and-webdav-integrations) [Bamboo Integration ](https://rocket.chat/docs/administrator-guides/rocket-chat-apps/bamboo-integration/#bamboo-integration)|[ENT1.2](../Elicitação/questionario.md#requisitos-elicitados) [ENT1.6](../Elicitação/questionario.md#requisitos-elicitados)<br>[INT3.8](../Elicitação/Introspeccao.md#introspecçao-03)<br>[INT4.6](../Elicitação/Introspeccao.md#introspecçao-04)<br>[SB5](../Elicitação/StoryBoarding#4-requisitos-obtidos)|[EP14](../Modelagem/backlog.md#us62)<br>[C14](../modelagem/cenarios.md#C14)<br>[ES14](../Modelagem/suplementar.md#es14-redes-sociais)<br>[NFR-09](../Modelagem/nfr.md#nfr2-conectividade)                                    |
|RNF10 |A plataforma deve identificar e tratar erros dentro do aplicativo                                                            |[Reportando erros](https://rocket.chat/docs/developer-guides/branches-and-releases/#error-reporting)                                                                                                                                                                                                                                                                                           |[AD10](../Elicitação/analdiscurso.md#requisitos-elicitados)                                                                                                                                                                                                                                          |[ES - Tratamento de falhas](../Modelagem/suplementar.md/#tratamento-de-falhas)                                                                                                                                   |

## Elos

### EF1

**Elementos rastreáveis:**

* [AD1](../Elicitação/analdiscurso#requisitos-elicitados)
* [INT4.4](../Elicitação/Introspeccao#introspeccao-04)
* [Storyboard 3](../Elicitação/Storyboard#4-requisitos-obtidos)
* [L31](../Modelagem/lexicos#31)
* [US45](../Modelagem/backlog#us45)
* [ISR05](../Modelagem/istar#isr05-acoes-sobre-o-channel)

**Elo:**


### EF2

**Elementos rastreáveis:**

* [AD2](../Elicitação/analdiscurso#requisitos-elicitados)
* [INT1.4](../Elicitação/Introspeccao#introspeccao-01)
* [Storyboard 2 e 3](../Elicitação/Storyboard#4-requisitos-obtidos),
* [Q12](../Elicitação/questionario#requisitos-elicitados)
* [L25](../Modelagem/lexicos#25)
* [C2](../Modelagem/cenarios#c2-v2)
* [DCU1-V2](../Modelagem/diagramas#dcu1-v2)
* [EC20](../Modelagem/especificacao#ec20)
* [US46](../Modelagem/backlog#us46)
*  [ISD01](../Modelagem/istar#isd01-chat)

**Elo:**

* Representação: [ECU20](../Modelagem/especificacao.md/#ec20) representa [C2](../Modelagem/cenarios.md/#c2-v2)
* Alocação:  [ECU20](../Modelagem/especificacao.md/#ec20) está alocado em [US46](../Modelagem/backlog.md/#us46)
* Representação: [ISD01](../Modelagem//istar#isd01-chat) representa [DCU1-V2](../Modelagem/diagramas#dcu1-v2)

### EF3

**Elementos rastreáveis:**

* [AP1](../Elicitação/analprot#requisitos-elicitados),
* [INT1.3](../Elicitação/Introspeccao#introspeccao-01)
* [C1](../Modelagem/cenarios#c1-v2)
* [DCU13](../Modelagem/diagramas#dcu13-v1)
* [EC21](../Modelagem/especificacao#ec21)
* [US02](../Modelagem/backlog#us02)
* [ISR02](../Modelagem/istar#isr02-realizar-cadastro)

**Elo:**

* Representação: [ECU21](../Modelagem/especificacao.md/#ec21) representa [C1](../Modelagem/cenarios.md/#c1-v2)
* Alocação:  [ECU21](../Modelagem/especificacao.md/#ec21) está alocado em [US02](../Modelagem/backlog.md/#us02)
* Representação: [ISR02](../Modelagem/istar.md/#isr02-realizar-cadastro) representa [DCU21](../Modelagem/diagramas.md/#cadastrar-novo-usuario)

### EF4

**Elementos rastreáveis:**

* [EP02](../Modelagem/backlog.md/#ep02-fazer-cadastro)
* [C1](../Modelagem/cenarios.md/#c1-v2)
* [DCU21](../Modelagem/diagramas.md/#cadastrar-novo-usuario)
* [ECU21](../Modelagem/especificacao.md/#ec21)
* [ISR02](../Modelagem/istar.md/#isr02-realizar-cadastro)

**Elo:**

* Representação: [ECU21](../Modelagem/especificacao.md/#ec21) representa [C1](../Modelagem/cenarios.md/#c1-v2)
* Alocação:  [ECU21](../Modelagem/especificacao.md/#ec21) está alocado em [EP02](../Modelagem/backlog.md/#ep02-fazer-cadastro)
* Representação: [ISR02](../Modelagem/istar.md/#isr02-realizar-cadastro) representa [DCU21](../Modelagem/diagramas.md/#cadastrar-novo-usuario)

### EF5

**Elementos rastreáveis:**

* [EP08](../Modelagem/backlog.md/#ep08-criar-channel)
* [C3](../Modelagem/cenarios.md/#c3-v2)
* [C22](../Modelagem/cenarios.md/#c22)
* [DCU16](../Modelagem/diagramas.md/#dcu16-v1)
* [DCU09](../Modelagem/diagramas.md/#dcu9-v1)
* [ECU03](../Modelagem/especificacao.md/#ec3)
* [ECU10](../Modelagem/especificacao.md/#ec10)
* [ISR01](../Modelagem/istar.md/#versao-02_2)

**Elo:**

* Agregação: [C3](../Modelagem/cenarios.md/#c3-v2) é composto por [C22](../Modelagem/cenarios.md/#c22)
* Alocação: [C3](../Modelagem/cenarios.md/#c3-v2) está alocado em [EP08](../Modelagem/backlog.md/#ep08-criar-channel)
* Representação: [ECU03](../Modelagem/especificacao.md/#ec3) representa [C22](../Modelagem/cenarios.md/#c22)
* Representação: [ECU10](../Modelagem/especificacao.md/#ec10) representa [C3](../Modelagem/cenarios.md/#c3-v2)
* Representação: [ISR01](../Modelagem/istar.md/#versao-02_2) representa [DCU16](../Modelagem/diagramas.md/#dcu16-v1)

### EF6

**Elementos rastreáveis:**

* [INT4.1](../Elicitação/Introspeccao#introspeccao-04)
* [SB1](../Elicitação/Storyboard.md#4-requisitos-obtidos)
* [EP10](../Modelagem/backlog.md/#ep10-Mensagens)
* [C12](../Modelagem/cenarios.md/#c12-v2)
* [DCU2](../Modelagem/diagramas.md/#dcu2-v2)
* [ECU15](../Modelagem/especificacao.md/#ec15)
* [ISR03](../Modelagem/istar.md/#isr03-envio-de-mensagens)
* [L41](../Modelagem/lexicos.md/#l41)
* [US20](../Modelagem/backlog#us20)

**Elo:**

* Satisfação: [DCU2](../Modelagem/diagramas.md/#dcu2-v2) e [ISR03](../Modelagem/istar.md/#isr03-envio-de-mensagens) satisfazem [US20](../Modelagem/backlog#us20) e [INT4.1](../Elicitação/Introspeccao#introspeccao-04)
* Alocação: [US20](../Modelagem/backlog#us20) está alocado em [EP10](../Modelagem/backlog.md/#ep10-Mensagens)
* Representação: [ECU15](../Modelagem/especificacao.md/#ec15) representa o [C12](../Modelagem/cenarios.md/#c12-v2)

### EF7

**Elementos rastreáveis:**

* [INT2.2](../Elicitação/Introspeccao#introspeccao-02)
* [AD11](../Elicitação/analdiscursi#requisitos-elicitados)
* [EP11](../Modelagem/backlog.md/#ep11-acoes-do-channel),
* [L11](../Modelagem/lexicos.md/#l11)
* [US48](../Modelagem/backlog#us48)

**Elo:**



### EF8

**Elementos rastreáveis:**

* [INT4.8](../Elicitação/Introspeccao#introspeccao-04)
* [INT1.4](../Elicitação/Introspeccao#introspeccao-01)
* [Storyboard 4](../Elicitação/Storyboard#4-requisitos-obtidos)
* [EP16](../Modelagem/backlog.md/#ep16-conectar-com-um-servidor)
* [C4](../Modelagem/cenarios.md/#c4-v2)
* [DCU17](../Modelagem/diagramas.md/#dcu17-v2)
* [EC11](../Modelagem/especificacao.md/#ec11)
* [L14](../Modelagem/lexicos.md/#l14)
* [US65](../Modelagem/backlog#us65)

**Elo:**

### EF9

**Elementos rastreáveis:**

* [INT3.9](../Elicitação/Introspeccao.md#introspeccao-03)
* [ENT1.1](../Elicitação/entrevista.md#requisitos)
* [AD7](../Elicitação/analdiscurso.md#requisitos-elicitados)
* [Q2](../Elicitação/questionario.md#requisitos-elicitados)
* [EP14](../Modelagem/backlog.md/#ep14-integraçoes),
* [C4](../Modelagem/cenarios.md/#c4-v2),
* [DCU17](../Modelagem/diagramas.md/#dcu17-v2),
* [EC11](../Modelagem/especificacao.md/#ec11),
* [L26](../Modelagem/lexicos.md/#ec14),
* [US62](../Modelagem/backlog#us62)

**Elo:**

### EF10

**Elementos rastreáveis:**

* [AP8](../Elicitação/analprot.md#requisitos-elicitados)
* [EP05](../Modelagem/backlog.md/#ep05-configurações-do-aplicativo)
* [NFR5](Modelagem/nfr.md#nf5-personabilidade)
* [US09](../Modelagem/backlog#us09)

**Elo:**

### EF11

**Elementos rastreáveis:**

* [INT4.5](../Elicitação/Introspeccao#introspeccao-04)
* [Storyboard3](../Elicitação/Storyboard#4-requisitos-obtidos)

**Elo:**

### EF12

**Elementos rastreáveis:**

**Elo:**

### EF13

**Elementos rastreáveis:**

* [US12](../Modelagem/backlog.md#us12)
* [L21](../Modelagem/lexicos.md#l21)
* [L41](../Modelagem/lexicos.md#l41)
* [L45](../Modelagem/lexicos.md#l45)
* [L46](../Modelagem/lexicos.md#l46)

**Elo:**

### EF14

**Elementos rastreáveis:**

* [US43](../Modelagem/backlog.md#us43)
* [ISD04](../Modelagem/istar#isd04-acoes-sobre-o-channel)
* [ISR05](../Modelagem/istar#isr05-acoes-sobre-o-channel)
* [L4](../Modelagem/lexicos.md#l4)

**Elo:**

* Representação: [US43](../Modelagem/backlog.md#us43) representa [L4](../Modelagem/lexicos.md#l4)

### EF15

**Elementos rastreáveis:**

* [US13](../Modelagem/backlog.md#us13)

**Elo:**

### EF16

**Elementos rastreáveis:**

* [US09](../Modelagem/backlog.md#us09)
* [US14](../Modelagem/backlog.md#us14)
* [L08](../Modelagem/lexicos.md#l08)
* [ISD02](../Modelagem/istar#isr02-geral)

**Elo:**

* Recurso: [ISD02](../Modelagem/istar#isr02-geral) depende de um recurso provido pelo [L08](../Modelagem/lexicos.md#l08), no caso, o perfil a ser editado
* Recurso: [US14](../Modelagem/backlog.md#us14) depende de um recurso provido pelo [L08](../Modelagem/lexicos.md#l08), no caso, o perfil a ser acessado
* Agregação: [ISD02](../Modelagem/istar#isr02-geral) é composto por [US14](../Modelagem/backlog.md#us14)


### EF17

**Elementos rastreáveis:**

* [US28](../Modelagem/backlog.md#us28)
* [US33](../Modelagem/backlog.md#us33)
* [C9](../Modelagem/cenarios.md/#c9-v2)
* [DCU2](../Modelagem/diagramas.md/#dcu2-v3)
* [DCU18](../Modelagem/diagramas.md/#dcu18-v1)
* [EC16](../Modelagem/especificacao.md/#ec16)
* [L5](../Modelagem/lexicos.md#l5)

**Elo:**

* Representação: [US33](../Modelagem/backlog.md#us33) representa [C9](../Modelagem/cenarios.md/#c9-v2)
* Representação: [DCU18](../Modelagem/diagramas.md/#dcu18-v1) representa [L5](../Modelagem/lexicos.md#l5)
* Recurso: [DCU2](../Modelagem/diagramas.md/#dcu2-v3) depende de um recurso provido pelo [C9](../Modelagem/cenarios.md/#c9-v2), no caso, o arquivo a ser enviado

### EF18

**Elementos rastreáveis:**

* [US15](../Modelagem/backlog.md#us15)
* [C10](../Modelagem/cenarios.md/#c10)

**Elo:**

* Representação: [US15](../Modelagem/backlog.md#us15) representa [C10](../Modelagem/cenarios.md/#c10)

### EF19

**Elementos rastreáveis:**

* [US16](../Modelagem/backlog.md#us16)

**Elo:**

### EF20

**Elementos rastreáveis:**

* [US17](../Modelagem/backlog.md#us17)
* [L39](../Modelagem/lexicos.md#l39)

**Elo:**

* Representação: [US17](../Modelagem/backlog.md#us17) representa [L39](../Modelagem/lexicos.md#l39)

### EF21

**Elementos rastreáveis:**

* [US42](../Modelagem/backlog.md#us42)
* [L34](../Modelagem/lexicos.md#l34)
* [L35](../Modelagem/lexicos.md#l35)

**Elo:**

* Representação: [US42](../Modelagem/backlog.md#us42) representa [L35](../Modelagem/lexicos.md#l35)
* Recurso: [US42](../Modelagem/backlog.md#us42) depende de um recurso provido pelo [L34](../Modelagem/lexicos.md#l34), no caso, o channel favoritado

### EF22

**Elementos rastreáveis:**

* [US22](../Modelagem/backlog.md#us22)
* [C26](../Modelagem/cenarios.md/#c26)
* [DCU8](../Modelagem/diagramas.md/#dcu8-v1)
* [EC2](../Modelagem/especificacao.md/#ec2)
* [L72](../Modelagem/lexicos.md#l72)

**Elo:**

* Representação: [C26](../Modelagem/cenarios.md/#c26) representa [US22](../Modelagem/backlog.md#us22)
* Representação: [EC2](../Modelagem/especificacao.md/#ec2) representa [C26](../Modelagem/cenarios.md/#c26)
* Representação:  [DCU8](../Modelagem/diagramas.md/#dcu8-v1)representa [L72](../Modelagem/lexicos.md#l72)
* Recurso: [US22](../Modelagem/backlog.md#us22) depende de um recurso provido pelo [L72](../Modelagem/lexicos.md#l72), no caso, a privacidade do channel a ser alterada
* Recurso: [C26](../Modelagem/cenarios.md/#c26) depende de um recurso provido pelo [L72](../Modelagem/lexicos.md#l72), no caso, a privacidade do channel a ser alterada

### EF23

**Elementos rastreáveis:**

* [US23](../Modelagem/backlog.md#us23)
* [C22](../Modelagem/cenarios.md/#c22)
* [DCU9 ](../Modelagem/diagramas.md/#dcu9-v1)
* [EC3](../Modelagem/especificacao.md/#ec3)
* [L69](../Modelagem/lexicos.md#l69)

**Elo:**

* Representação: [US23](../Modelagem/backlog.md#us23) representa [C22](../Modelagem/cenarios.md/#c22)
* Representação:  [DCU9 ](../Modelagem/diagramas.md/#dcu9-v1) representa [C22](../Modelagem/cenarios.md/#c22)
* Recurso: [C22](../Modelagem/cenarios.md/#c22) depende de um recurso provido pelo [L69](../Modelagem/lexicos.md#l69), no caso, o Read-only channel
* Recurso:  [US23](../Modelagem/backlog.md#us23) depende de um recurso provido pelo [L69](../Modelagem/lexicos.md#l69), no caso, o Read-only channel

### EF24

**Elementos rastreáveis:**

* [US24](../Modelagem/backlog.md#us24)

**Elo:**

### EF25

**Elementos rastreáveis:**

* [US25](../Modelagem/backlog.md#us25)
* [US26](../Modelagem/backlog.md#us26)
* [US47](../Modelagem/backlog.md#us47)
* [L33](../Modelagem/lexicos.md#l33)

**Elo:**

* Recurso: [US26](../Modelagem/backlog.md#us26) depende de um recurso provido pelo [L33](../Modelagem/lexicos.md#l33), no caso, o tópico a ser adicionado
* Recurso: [US47](../Modelagem/backlog.md#us47) depende de um recurso provido pelo [L33](../Modelagem/lexicos.md#l33), no caso, o tópico a ser visualizado

### EF26

**Elementos rastreáveis:**

* [US30](../Modelagem/backlog.md#us30)
* [C8](../Modelagem/cenarios.md/#c8)
* [DCU18](../Modelagem/diagramas.md/#dcu18-v1)
* [EC17](../Modelagem/especificacao.md/#ec17)
* [L43](../Modelagem/lexicos.md#l43)

**Elo:**

* Representação: [US30](../Modelagem/backlog.md#us30) representa [C8](../Modelagem/cenarios.md/#c8)
* Representação: [EC17](../Modelagem/especificacao.md/#ec17) representa [C8](../Modelagem/cenarios.md/#c8)
* Agregação: [DCU18](../Modelagem/diagramas.md/#dcu18-v1) é composto por [EC17](../Modelagem/especificacao.md/#ec17)

### EF27

**Elementos rastreáveis:**

* [US31](../Modelagem/backlog.md#us31)

**Elo:**

### EF28

**Elementos rastreáveis:**

* [US34](../Modelagem/backlog.md#us34)
* [C5](../Modelagem/cenarios.md#c5)
* [E19](../Modelagem/especificacao.md#ec19)
* [DCU19](../Modelagem/diagramas.md#dcu19-v1)

**Elo:**

* Representação: [US34](../Modelagem/backlog.md#us34) representa [C5](../Modelagem/cenarios.md#c5)
* Representação: [DCU19](../Modelagem/diagramas.md#dcu19-v1) representa [US34](../Modelagem/backlog.md#us34)

### EF29

**Elementos rastreáveis:**

* [US35](../Modelagem/backlog.md#us35)
* [L54](../Modelagem/lexicos.md#l54)

**Elo:**

* Representação: [US35](../Modelagem/backlog.md#us35) representa [L54](../Modelagem/lexicos.md#l54)

### EF30

**Elementos rastreáveis:**

* [US36](../Modelagem/backlog.md#us36)
* [L13](../Modelagem/lexicos.md#l13)
* [L54](../Modelagem/lexicos.md#l54)

**Elo:**

* Representação: [US36](../Modelagem/backlog.md#us36) representa [L13](../Modelagem/lexicos.md#l13)

### EF31

**Elementos rastreáveis:**

* [US38](../Modelagem/backlog.md#us38)
* [L58](../Modelagem/lexicos.md#l58)

**Elo:**

* Representação: [US38](../Modelagem/backlog.md#us38) representa [L58](../Modelagem/lexicos.md#l58)

### EF32

**Elementos rastreáveis:**
* [US39](../Modelagem/backlog.md#us39)
* [L9](../Modelagem/lexicos#l9)
* [L10](../Modelagem/lexicos#l10)

**Elo:**

* Representação: [US39](../Modelagem/backlog.md#us39) representa [L9](../Modelagem/lexicos#l9)

### EF33

**Elementos rastreáveis:**

* [US40](../Modelagem/backlog.md#us40)
* [C7](cenarios.md#c7-v2)
* [DCU20](../Modelagem/diagramas.md#dcu20-v1)
* [EC18](../Modelagem/especificacao.md/#ec18)
* [ISD01](../Modelagem/istar#isd01-chat)
* [ISR03](../Modelagem/istar#isr03-envio-de-mensagens)

**Elo:**

### EF34

**Elementos rastreáveis:**

* [US41](../Modelagem/backlog.md#us41)

**Elo:**

### EF35

**Elementos rastreáveis:**

* [US44](../Modelagem/backlog.md#us44)
* [C19](cenarios.md#c19)
* [DCU14](../Modelagem/diagramas.md#dcu14-v1)
* [EC24](../Modelagem/especificacao.md/#ec24)
* [L28](../Modelagem/lexicos#l28)
* [ES03](../Modelagem/suplementar.md#es03-notificacoes)

**Elo:**

* Representação: [DCU14](../Modelagem/diagramas.md#dcu14-v1) representa [C19](cenarios.md#c19)
* Representação: [ES03](../Modelagem/suplementar.md#es03-notificacoes) representa [L28](../Modelagem/lexicos#l28)
* Recurso: [C19](cenarios.md#c19) depende de um recurso provido pelo [L28](../Modelagem/lexicos#l28), no caso, a notificação
* Recurso: [DCU14](../Modelagem/diagramas.md#dcu14-v1) depende de um recurso provido pelo [L28](../Modelagem/lexicos#l28), no caso, a notificação

### EF36

**Elementos rastreáveis:**

* [ENT1.3](../Elicitação/entrevista.md#requisitos)
* [INT3.10](../Elicitação/Introspeccao#introspeccao-03)
* [US05](../Modelagem/backlog.md#us05)
* [US06](../Modelagem/backlog.md#us06)
* [NFR-03](../Modelagem/nfr.md#nfr3-suporte)

**Elo:**


## Versionamento

| Data | Versão | Modificação | Autor |
|------|--------|-------------|-------|
| 16/06/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 17/06/2019 | 1.1 | Inclusão das tabelas inicias de requisitos | Marcos Nery |
| 18/06/2019 | 1.2 | Inclusão dos elos | Marcos Nery |
| 19/06/2019 | 1.3 | Inclusão dos elos | Weiller Fernandes |
