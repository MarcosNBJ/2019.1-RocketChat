
# Cenários

### C1

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

|**Cadastro de  um novo usuário no Rocket.Chat**|
|--|
|**Objetivo** |
| Cadastrar um novo usuário |
|**Contexto** |
| -Local: Página inical do app do rocket.chat |
| -pré-condição: Possuir internet, não estar logado na plataforma |
| -Pós-condição:  Usuário cadastrado |
|**Atores** |
|  Usuário não cadastrado |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -Rocket.Chat instalado. |
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
|  -Um novo usuário ou usuário que deseja uma nova conta entra na plataforma do Rocket.Chat em seu computador ou celular. |
|-Na tela inicial, o usuário não logado seleciona a opção “Registrar um novo usuário”.|
|-Na tela de cadastro, o usuário preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer log up.|
|-Criando um usuário do zero ou usando uma rede social, o novo usuário é direcionado para uma página onde deve selecionar seu user name.|
|-O usuário preenche o campo de user name e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|  - |


### C1 - V2

|**Cadastrar um novo usuário**|
|--|
|**Objetivo** |
| Acessar as funcionalidades da plataforma disponíveis para usuários cadastrados |
|**Contexto** |
| -Local: Página inical do app do rocket.chat |
| -pré-condição: Possuir internet, não estar logado na plataforma |
| -Pós-condição:  Usuário cadastrado |
|**Atores** |
|  Usuário não cadastrado |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -Rocket.Chat instalado. |
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
|  -Um novo usuário ou usuário que deseja uma nova conta entra na plataforma do Rocket.Chat em seu computador ou celular. |
|-Na tela inicial, o usuário não logado seleciona a opção “Registrar um novo usuário”.|
|-Na tela de cadastro, o usuário preenche os campos de cadastro com sua senha e email e nome. Caso deseje, pode-se também selecionar umas das redes sociais para fazer sign up.|
|-Criando um usuário do zero ou usando uma rede social, o novo usuário é direcionado para uma página onde deve selecionar seu user name.|
|-O usuário preenche o campo de user name e seu cadastro é realizado com sucesso.|
|**Levantado pela técnica**|
|-|


### C2 - V1

|**Realizar Web conferência**|
|--|
|**Objetivo** |
| Realizar uma reunião online |
|**Contexto** |
| -Local: Plataforma Rocket.chat |
| -Pré-condição: possuir internet, possuir a plataforma Rocket.Chat no celular ou computador |
| -Pós-condição: Web conferência será realizada com sucesso entre os usuários
|
|**Atores** |
|  -Pessoa 1 |
|  -Pessoa 2 |
|**Recursos** |
|  -Internet |
|  -Computador/celular |
|  -Rocket.Chat instalado |
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
|  -Pessoa 1 acessa a internet e baixa o rocket.chat em seu computador.|
|  -Pessoa 1 pega seu fone de ouvido e testa seu microfone.|
|  -Pessoa 2 acessa a internet e baixa o rocket chat em seu celular.|
|  -Pessoa 2 testa o microfone e autofalante de seu celular, já que não possui fones de ouvido.|
|  -Pessoa um entra em sua conta no Rocket.Chat e procura o usuário da Pessoa 2.|
|  -Pessoa 1 entra em um bate papo com a pessoa 2. |
|  -Pessoa 1 seleciona a opção “Realizar Vídeo conferência” e manda o convite para a pessoa 2.|
|  -Pessoa 2 entra em sua conta do Rocket.chat e aceita o convite para a realização da web conferencia.|
|**Levantado pela técnica**|
|  Storyboard, introspecção, questionário, análise de protocolo, análise de discurso |


### C2 - V2

|**Realizar Web conferência**|
|--|
|**Objetivo** |
| Conversar a distância com outro usuário/grupo. |
|**Contexto** |
| -Local: Plataforma Rocket.chat |
| -Pré-condição: possuir internet, possuir a plataforma Rocket.Chat no celular ou computador |
| -Pós-condição: Web conferência será realizada com sucesso entre os usuários
|
|**Atores** |
|  -Criador da web conferência |
|  -Grupo/pessoas que irão participar  |
|**Recursos** |
|  -Internet |
|  -Computador/celular |
|  -Rocket.Chat instalado |
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
| -Criador da conversa entra em sua conta no Rocket.Chat e procura o usuário dos outros envolvidos.|
| -Criador da web conferência entra em um bate papo com o grupo/pessoa.|
| -Criador da web conferência seleciona a opção “Realizar Vídeo conferência” e manda o convite para o grupo/pessoa.|
| -O grupo/pessoa entra em sua conta do Rocket.chat e aceita o convite para a realização da web conferência.|
|**Levantado pela técnica**|
|  Storyboard, introspecção, questionário, análise de protocolo, análise de discurso |


### C5

|**Editar uma mensagem**|
|--|
|**Objetivo** |
| Usuário editar o conteúdo textual de uma mensagem em um texto |
|**Contexto** |
|-Local: channel da conversa|
|-Tempo: A qualquer momento|
|-Pré-condição: O usuário ter conta no aplicativo e estar dentro do channel, bem como ter as permissões necessárias
|-Pós-condição: A dada mensagem no channel será mostrada com o conteúdo editado e um identificador contendo a palavra “Editada”|
|**Atores** |
|  Usuário |
|**Recursos** |
|- Internet|
|- Conta no aplicativo|
|**Restrição**|
|  restrições aqui |
|**Exceção** |
|- Queda da internet|
|- Usuário não tem permissão|
|- Usuário cancela a ação|
|**Episódios** |
|- Usuário abre o aplicativo|
|- Usuário loga no servidor|
|- Usuário vai até o channel|
|- Usuário clica na mensagem que deseja editar|
|- Usuário clica na opção editar|
|- Usuário edita o conteúdo da mensagem|
|- Usuário clica no botão enviar, finalizando a edição|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|


### C7

|**Responder  mensagem**|
|--|
|**Objetivo** |
|- Usuário enviar uma mensagem que responde uma outra mensagem anterior|
|**Contexto** |
|- Local: channel da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O usuário ter conta no aplicativo e estar dentro do channel |
|- Pós-condição: A resposta enviada pelo usuário será mostrada no channel com o anexo da mensagem respondida abaixo|
|**Atores** |
|  Usuário |
|**Recursos** |
|- Internet|
|- Conta no aplicativo|
|**Restrição**|
|  restrições aqui |
|**Exceção** |
|- Queda da internet|
|- Usuário cancela a ação|
|**Episódios** |
|- Usuário loga no servidor|
|- Usuário clica no channel desejado|
|- Usuário clica na mensagem que deseja responder|
|- Usuário escreve o conteúdo desejado|
|- Usuário envia a resposta|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C8

|**Enviar desenho**|
|--|
|**Objetivo** |
|- Usuário enviar uma mensagem cujo conteúdo é um desenho digital feito por ele na aplicação, com o objetivo de expor alguma ideia ou mensagem ilustrada|
|**Contexto** |
|- Local: channel da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O usuário ter conta no aplicativo e estar dentro do channel|
|- Pós-condição: Será visto no channel o desenho enviado pelo usuário|
|**Atores** |
|  Usuário |
|**Recursos** |
|- Internet|
|- Conta no aplicativo|
|**Restrição**|
|- Usuário não desenhou corretamente o que queria|
|- Ferramenta de desenhos digitais não oferecia algum recurso de desenho que o usuário precisava|
|**Exceção** |
|- Queda da internet|
|- Usuário cancela a ação|
|**Episódios** |
|- Usuário entra logado no servidor|
|- Usuário entra no channel desejado|
|- Usuário clica no botão de “plus”|
|- Usuário clica na opção “desenho”|
|- Usuário desenha o conteúdo desejado|
|- Usuário envia o desenho|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C9

|**Anexar um arquivo**|
|--|
|**Objetivo** |
|- Usuário enviar, com ou sem uma mensagem textual, um arquivo de mídia (como fotos ou vídeos) ou um documento|
|**Contexto** |
|- Local: channel da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O usuário ter conta no aplicativo e estar dentro do channel |
|- Pós-condição: Será mostrado para os outros usuários no channel o arquivo enviado pelo usuário, com a opção de download|
|**Atores** |
|  Usuário |
|**Recursos** |
|- Internet|
|- Conta no aplicativo|
|- Arquivo qualquer|
|**Restrição**|
|- Usuário enviar o arquivo correto|
|- O arquivo não deve demorar para ser enviado|
|**Exceção** |
|- Queda da internet|
|- Usuário não tem permissão|
|- Usuário cancela a ação|
|**Episódios** |
|- Usuário entra logado no servidor|
|- Usuário entra no channel desejado|
|- Usuário clica no botão “plus”|
|- Usuário clica em anexar um arquivo|
|- Usuário seleciona o arquivo desejado|
|- Usuário envia o arquivo|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C11

|**Fixar Mensagem**|
|--|
|**Objetivo** |
| - Encontrar uma mensagem com mais facilidade |
|**Contexto** |
| - Local: Menu de opções de mensagens presentes em channels ou grupos |
| - Tempo: Quando uma mensagem está disponível no channel ou grupo |
| - Pré-condição:  O usuário ter conta no aplicativo e estar dentro do channel |
| - Pós-condição: As mensagens fixadas ficarão disponíveis em “mensagens fixadas” localizada no menu principal do channel ou grupo |
 |
|**Atores** |
|- Usuário devidamente cadastrado no app e participante de um grupo |
|**Recursos** |
| - Internet |
| - Plataforma para uso da aplicação (celular ou computador) |
| Aplicativo instalado |
|**Restrição**|
| - Baixa qualidade na conexão de internet |
|**Exceção** |
| - Impossibilidade de conexão de internet |
| - Usuário cancelar ação |
| - Mensagem a ser fixada foi removida |
| - Bug no aplicativo |
|**Episódios** |
| - Usuário abre o aplicativo se loga em um servidor |
| - Usuário seleciona um grupo |
| - Usuário encontra uma mensagem de seu interesse |
| - Usuário seleciona a mensagem desejada através do menu de opções da mensagem |
| - Usuário seleciona o botão de fixar mensagem |


### C12

|**Enviar mensagem**|
|--|
|**Objetivo** |
|- Transmitir aos outros integrantes da conversa uma mensagem, que pode conter texto, Emojis, arquivos de mídia, documentos, áudios gravados pelo app, e desenhos digitais feitos pelo menu do app.|
|**Contexto** |
|- Local: channel da conversa|
|- Tempo: A qualquer momento|
|- Pré-condição: O usuário ter conta no aplicativo e estar dentro do channel no qual deseja enviar uma mensagem|
|- Pós-condição: A mensagem enviada será mostrada no channel para todos os usuários membros, junto com uma notificação que chegará se o usuário tiver sido mencionado|
|**Atores** |
|  Usuário |
|**Recursos** |
|- Internet|
|- Conta no aplicativo|
|**Restrição**|
|- Usuário escrever corretamente o que quer expressar |
|- A aplicação oferecer ferramentas que ajudem o usuário a escrever sua mensagem, como um corretor ortográfico|
|- O usuário conseguir anexar todos os arquivos que quer|
|**Exceção** |
|- Queda da internet|
|- Usuário cancela a ação|
|- Mensagem do usuário está acima do limite de caracteres|
|**Episódios** |
|- Usuário entra logado no servidor|
|- Usuário entra no channel desejado |
|- Usuário digita a mensagem no campo de texto|
|- Usuário anexa todos os arquivos que quiser na mensagem|
|- Usuário insere um Emoji se quiser|
|- Usuário envia a mensagem clicando no botão presente na caixa de texto para essa finalidade|
|**Levantado pela técnica**|
|  qual técnica ou quais técnicas levantaram esse necessidade|

### C15 - V1

|**Sair de um channel  **|
|--|
|**Objetivo** |
| Não ser mais participante de um channel na plataforma e com isso não receber notificações do mesmo |
|**Contexto** |
| -Local: Um channel dentro da plataforma|
| -Tempo: A qualquer momento após um chat em grupo ser iniciado e o membro que deseja se retirar seja adicionado|
| -Pré-condição: Estar conectado com a internet, ter o Rocket.chat baixado em seu computador, possuir um usuário na plataforma, estar presente no chat que deseja sair.|
| -Pós-condição: Não participação no chat em grupo.|
|**Atores** |
|  Usuário cadastrado presente no channel |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -Rocket.Chat instalado. |
|  -Estar presente em um channel |
|**Restrição**|
| -Baixa conexão com a internet|
| -Baixo desempenho do computador, causando lentidão no processo|
|**Exceção** |
| -Não possuir internet |
| -App dar crash |
| -Computador quebrar |
| -Não participar de nenhum grupo |
| -Não possuir Rocket.chat versão desktop, nem conta na plataforma |
|**Episódios** |
| -Surge no usuário o desejo sair de um determinado grupo.|
| -O usuário abre a plataforma em seu computador.|
| -O usuário busca na área de channels, o grupo no qual deseja se retirar.|
| -O usuário clica nos três pontos que surgem ao manter o cursor em cima do grupo que deseja sair.|
| -Após o clique, surgem diversas interações que podem ser realizadas com o grupo, dentre tais a de “Deixar grupo”.|
| -O usuário clica na opção “ Deixar grupo” e , com isso, deixa o grupo.|
|**Levantado pela técnica**|
|-|

### C16 - V1

|**Esconder sala**|
|--|
|**Objetivo** |
| Não ver mais uma sala e nem receber notificações da mesma|
|**Contexto** |
| -Local: Plataforma Rocket.Chat.|
| -Tempo: a qualquer momento, quando o surgir no usuário o desejo de deixar uma sala.|
| -Pré-condição: Estar conectado com a internet, ter o Rocket.chat baixado em seu computador, possuir um usuário na plataforma, estar presente no chat que deseja Esconder.|
| -Pós-condição: Não ver mais e nem ser notificado pelo chat escondido.|
|**Atores** |
|  Usuário cadastrado presente no channel |
|**Recursos** |
|  -Internet. |
|  -Computador/celular. |
|  -Rocket.Chat instalado. |
|  -Estar presente em um channel |
|**Restrição**|
| -Baixa conexão com a internet|
| -Baixo desempenho do computador, causando lentidão no processo|
|**Exceção** |
| -Não possuir internet |
| -App dar crash |
| -Computador quebrar |
| -Não participar de nenhum grupo |
| -Não possuir Rocket.chat versão desktop, nem conta na plataforma |
|**Episódios** |
| -Surge no usuário o desejo sair de esconder um grupo.|
| -O usuário abre a plataforma em seu computador.|
| -O usuário busca na área de channels, o grupo no qual deseja se esconder.|
| -O usuário clica nos três pontos que surgem ao manter o cursor em cima do grupo.|
| -Após o clique, surgem diversas interações que podem ser realizadas com o grupo, dentre tais a de “esconder grupo”.|
| -O usuário clica na opção “ esconder grupo” e , com isso, esconde o grupo, passando a não receber mais atividades do mesmo, mas podendo restaurar a qualquer momento.|
|**Levantado pela técnica**|
|-|


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 19/04/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 21/04/2019 | 1.1 | Adição dos Cenários C5, C7, C8, C9, c12 | Marcos Nery |
| 21/04/2019 | 1.2 | Adição dos Cenários C1 - v1, C1 - v2, C2 - v1, C2 - v2, C15, C16, c12 | Gabriel Davi |
| 21/04/2019 | 1.3 | Adição do Cenário C11 | Lucas Maciel |
