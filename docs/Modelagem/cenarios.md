
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


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 19/04/2019 | 1.0 | Abertura do documento | Marcos Nery |
| 21/04/2019 | 1.1 | Adição dos Cenários C5, C7, C8, C9, L12 | Marcos Nery |
