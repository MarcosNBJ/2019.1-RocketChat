# Documento de Especificação Suplementar

## Introdução

### Finalidade
Aqui buscamos reunir requisitos, principalmente não funcionais, que abrangem de forma mais geral alguns critérios de qualidade aos quais está submetida a aplicação, além de outros tipos de necessidade do produto.

### Escopo
O escopo é definido por uma plataforma de chat, focada em uso profissional e chat em grupos, que pode ser acessada via web, mobile, ou instalada nos computadores de sistemas operacionais MacOS, Windows e Linux.
### Definições, Acrônimos e Abreviações
 Listados nos [Léxicos](lexicos.md).


## Funcionalidades

  Os requisitos funcionais podem ser vistos através das listagens nos métodos de elicitação e também por meio dos [Cenários](cenarios.md), [Casos de uso](diagramas.md), e [especificações dos casos de uso](especificacao.md)

## Usabilidade

Aqui são listados critérios de qualidade quanto a interação do usuário com a aplicação.

### ES01 - Fluxo de naveçaão
A plataforma deve oferecer um fluxo intuitivo de navegação pela plataforma
_Rastro:[AP6](../Elicitação/analprot/#requisitos-elicitados)_


### ES02 - Instruções de uso
A aplicação deve possuir instruções aos novos usuário para ajudá-lo no uso do aplicativo.
_Rastro:[AP3](../Elicitação/analprot/#requisitos-elicitados)_


### ES03 - Notificações
O sistema deve dar avisos ao usuário quando alguma ação importante ocorrer na plataforma, como uma nova mensagem
_Rastro:[Q3](../Elicitação/questionario/#requisitos-elicitados),[AD5](../Elicitação/analdiscurso/#requisitos-elicitados)_


### ES04 - Visibilidade de status do sistema
O sistema deve fornecer feedbacks ao usuário, de forma que ele entenda o antes, durante e depois das suas ações no sistema.

### ES05 - Ícones e cores
O sistema deve possuir ícones e cores que condizem com alguma ação que será realizada no aplicativo
_Rastro:[AP6](../Elicitação/analprot/#requisitos-elicitados)_

### ES06 - Resolução de erros
O sistema deve fornecer avisos quando houver algum erro no ato de uma ação.

## Desempenho

Este tópico descreve as restrições de comportamento geral do sistema.

### ES07 - Velocidade de resposta
A aplicação deve ser capaz de responder com rapidez a uma ação de um usuário.

### ES08 - Servidores
O sistema deve possuir servidores eficientes para o suporte e tratamento do fluxo de dados criado pelos diversos usuários sem gerar sobrecarga, considerando também o suporte a escalabilidade de usuários ao longo do ciclo de existência do aplicativo.
_Rastro:[ENT1.7](../Elicitação/Introspeccao/#introspeccao-01)_


## Portabilidade
Aqui são listados os requisitos da aplicação quanto a sua portabilidade, em diferentes plataformas.

### ES09 - Android
A aplicação deve estar disponível e ser suportada em dispositivos móveis com sistema operacional Android 5.0 ou superior, incluindo tablets e smartphones
_Rastro:[INT3.7](../Elicitação/Introspeccao/#introspeccao-03) e [Q18](../Elicitação/questionario/#requisitos-elicitados)_


### ES10 - IOS
A aplicação deve estar disponível e ser suportada em dispositivos móveis com sistema operacional IOS 11.0 ou superior, incluindo dispositivos como Iphone e Ipad.
_Rastro:[INT3.7](../Elicitação/Introspeccao/#introspeccao-03) e [Q18](../Elicitação/questionario/#requisitos-elicitados)_


### ES11 - Windows
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional Windows 7 ou superior.
_Rastro:[INT3.7](../Elicitação/Introspeccao/#introspeccao-03) e [Q18](../Elicitação/questionario/#requisitos-elicitados)_


### ES12 - Linux
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional Linux, com processadores de 32 ou 64 bits, incluindo diversas distribuições: CentOs, Baseadas no Debian através dos pacotes .deb ou gerenciadores de pacote (apt ou snap), RedHat ou outras distribuições que suportam pacotes .rpm.
_Rastro:[INT3.7](../Elicitação/Introspeccao/#introspeccao-03) e [Q18](../Elicitação/questionario/#requisitos-elicitados)_


### ES13 - MacOS
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional MacOs X 10.10.0 ou superior, com processadores de 64 bits.
_Rastro:[INT3.7](../Elicitação/Introspeccao/#introspeccao-03) e [Q18](../Elicitação/questionario/#requisitos-elicitados)_


## Conectividade
Descreve a integração da aplicação com diferentes plataformas de sistema e aplicações de terceiros.

### ES14 - Redes sociais
A aplicação deve permitir a integração com redes sociais, para maior facilidade do usuário em se cadastrar.
_Rastro:[AP1](../Elicitação/analprot/#requisitos-elicitados)_

### ES15 - Padrão de interface entre plataformas
A aplicação deve manter um padrão de interface em todas as plataformas se adequando a qualquer dispositivo, para que o usuário possa ter uma fácil integração em todos os meios.
_Rastro:[Q18](../Elicitação/questionario/#requisitos-elicitados), [Q1](../Elicitação/questionario/#requisitos-elicitados)_

### ES16 - Comunicação com usuários
A aplicação deve manter a comunicação com o usuário por meio de notificações e por meio de e-mails previamente cadastrados.

## Tratamento de Falhas
Este tópico descrece como a aplicação deve identificar e tratar erros.

### ES17 - Monitoramento
A aplicação deve manter monitoramento e inspeção constantes de problemas afim de executar a correção de bugs.
### ES18 - Atualização
A aplicação pede ao usuário que certifique-se de que está executando a última versão. É muito provável que a simples atualização resolva seu problema.

### ES19 - Feedback
A aplicação relata ao usuário que ocorreu uma falha no sistema e solicita um feedback para tentar resolve-lá. Com essas informações o suporte pode corrigir o problema mais rapidamente.

## Segurança
Aqui são tratados os requerimentos da aplicação quanto a sua segurança e a segurança dos dados que nela trafegam.

### ES20 - Autenticação
A aplicação deve fornecer um sistema de autenticação segura, por meio de e-mail ou nome de usuário, acrescido da senha do usuário.

### ES21 - Criptografia
A aplicação deve oferecer a opção de Criptografar as mensagens dos grupos privados e mensagens diretas na aplicação, através de uma chave E2E única para cada usuário no servidor principal compartilhado da Rocket.Chat

### ES22 - Servidores particulares
O sistema de possuir a opção do usuário adicionar servidores particulares para a prevenção e segurança dos seus dados.


## Restrições de Design

### ES23 - Listagem de channels
Na página principal do usuário, deverão estar acessíveis os chennels principais que o usuário acessa, um menu com as configurações do aplicativo e opções de suporte, bem como ferramentas de pesquisa para que o usuário procure rapidamente por usuários ou channels.

### ES24 - Interface de edição de texto
Dentro do channel, deverá existir uma interface de edição de texto com ferramentas para formatar e escrever o texto. Bem como menus visíveis com todas as funcionalidades relacionadas aquele channel em específico.

### ES25 - Pluralidade de idiomas
A interface deverá estar disponível na maior pluralidade possível de idiomas.


## Requisitos de Suporte ao usuário
Aqui são listados todos os requisitos referentes a ajuda e suporte aos usuários da aplicação.

### ES26 - Documentação
A plataforma deve possuir uma documentação bem organizada, no formato de uma Wikia. Que explique todas as funcionalidades e restrições aplicáveis.
_Rastro: [Documentação](https://rocket.chat/docs/)_


### ES27 - Ajuda
Dentro do menu da aplicação deve haver um botão de ajuda. Que leva para uma página com problemas frequentes dos usuário e suas respectivas resoluções, bem como um link para a documentação e para entrar em contato com o suporte caso a ajuda ali não seja suficiente.
_Rastro: [Ajuda](https://rocket.chat/docs/getting-support/)_

### ES28 - Suporte online
A equipe de suporte ao usuário deve ser eficiente, de forma que o usuário que entre em contato para receber ajuda com algo deve receber sua resposta idealmente no prazo máximo de 24 horas.

### ES29 - Forum de discussão
Deve haver um fórum dedicado a discussão de problemas e submissão de feedbacks acerca da aplicação. Pelo qual tanto os usuário quanto a equipe de desenvolvimento podem se manifestar.

### ES30 - Como contribuir
Por ser uma aplicação Open Source, na documentação deve haver uma secção explicando claramente os passos de como alguém pode contribuir com o projeto.
_Rastro: [Guia de contribuição](https://rocket.chat/docs/contributing/)_

### ES31 - Organização do repositório.
O repositório da aplicação do Github deve ser bem organizado, de modo que os interessados consigam facilmente submeter problemas, resoluções e feedbacks através das issues.
_Rastro: [Repositório do Rocket.chat](https://github.com/RocketChat)_


## Interfaces
Aqui são definidos todos os tipos de interface presentes na aplicação.

### ES32 - Interfaces do Usuário
A plataforma deverá possuir uma interface gráfica, pela qual os usuários sejam capazes de interagir com todas as funcionalidades para eles disponíveis no sistema.

### ES33 - Interfaces de Hardware
Os dispositivos de hardware nos quais a aplicação pode ser instalada são: Computadores Desktop, Notebooks e dispositivos mobile como smartphones e tablets.

### ES34 - Interfaces de Software
As definições de linguagens, frameworks e paradigmas para a criação e evolução do software devem ser as quais ofereçam a longo prazo uma fácil manutenção e confiabilidade.

## Requisitos de Licenciamento
Será expecificado os aspectos referentes às permissões e restrições ao usuário, definidas na [politica de privacidade](https://rocket.chat/privacy) e [termos de serviço](https://rocket.chat/terms), estes, que não serão aplicados quando usuário estiver usando a instalação on-premises do Rocket.chat.

### ES35 - Cadastro
Ao se cadastrar na aplicação, o usuário disponibiliza seu endereço de e-mail, primeiro e ultimo nome, alem de cookies e dados de uso, como o endereço de IP, informações do navegador, na versão web e ID do dispositivo, endereço de IP, sistema operacional, na versão mobile, entre outras informações. Será enviado noticias e notificações para o usuário, o mesmo sendo opcional.
_Rastro:[Rocket.chat-Privacidade](https://rocket.chat/privacy)_

### ES36 - GDPR
Rocket.Chat é compativel à General Data Protection Regulation (GDPR), é um regulamento do direito europeu sobre privacidade e proteção de dados pessoais, aplicável a todos os indivíduos na União Europeia e Espaço Económico Europeu.


## ES37 - Observações Legais, de Copyright e Outras
A aplicação é licenciada sob a MIT License. É permitido o uso, copía, modificação, entre outros, totalmente gratuito garantido pela [licença do software](https://github.com/RocketChat/Rocket.Chat.Hubot/blob/master/LICENSE).

## Referências

* [Documentação do Rocket chat](https://rocket.chat/docs/)
* [Site do Rocket chat](https://rocket.chat/)
* [Repositórios do Rocket chat](https://github.com/RocketChat)


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 28/04/2019 | 1.0 | Abertura do documento e inclusão do template | Marcos Nery|
| 28/04/2019 | 1.1 | Preenchimento inicial do documento, de introdução à funcionalidades | Marcos Nery|
| 29/04/2019 | 1.2 | Preenchendo os requisitos de usabilidade e desempenho | Gabriel Davi|
| 29/04/2019 | 1.3 | Adição dos requisitos de portabilidade e segurança | Lucas Maciel |
| 29/04/2019 | 1.4 | Adição dos requisitos de conectividade e tratamento de falhas | André Lucas |
| 29/04/2019 | 1.5 | Adição dos requisitos de suporte ao usuário | Marcos Nery|
| 29/04/2019 | 1.6 | Adição da listagem de Interfaces | Marcos Nery|
| 29/04/2019 | 1.7 | Adição das observações legais e copyright | Heron Rodrigues|
| 29/04/2019 | 1.8 | Adição dos requisitos de licenciamento | Heron Rodrigues|
| 29/04/2019 | 1.9 | Adição das referências | Marcos Nery|
| 03/04/2019 | 2.0 | Refatoração dos títulos dos tópicos | Marcos Nery |
| 22/06/2019 | 2.1 | Adição dos rastros por tópico | Marcos Nery |
