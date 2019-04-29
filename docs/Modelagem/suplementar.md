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

### Requisito de Usabilidade Um
A plataforma deve oferecer um fluxo intuitivo de navegação pela plataforma

### Requisito de Usabilidade Dois
A aplicação deve possuir instruções aos novos usuário para ajudá-lo no uso do aplicativo.

### Requisito de Usabilidade Três
O sistema deve dar avisos ao usuário quando alguma ação importante ocorrer na plataforma, como uma nova mensagem

### Requisito de Usabilidade Quatro
O sistema deve fornecer feedbacks ao usuário, de forma que ele entenda o antes, durante e depois das suas ações no sistema.

###Requisito de usabilidade Cinco
O sistema deve possuir ícones e cores que condizem com alguma ação que será realizada no aplicativo

###Requisito de usabilidade Seis
O sistema deve fornecer avisos quando houver algum erro no ato de uma ação.

## Desempenho

Este tópico descreve as restrições de comportamento geral do sistema.

### Requisito de Desempenho Um
A aplicação deve ser capaz de responder com rapidez a uma ação de um usuário.

### Requisito de Desempenho Dois
O sistema deve possuir servidores eficientes para o suporte e tratamento do fluxo de dados criado pelos diversos usuários sem gerar sobrecarga, considerando também o suporte a escalabilidade de usuários ao longo do ciclo de existência do aplicativo.

## Portabilidade
Aqui são listados os requisitos da aplicação quanto a sua portabilidade, em diferentes plataformas.

### Requisito de Portabilidade Um
A aplicação deve estar disponível e ser suportada em dispositivos móveis com sistema operacional Android 5.0 ou superior, incluindo tablets e smartphones

### Requisito de Portabilidade Dois
A aplicação deve estar disponível e ser suportada em dispositivos móveis com sistema operacional IOS 11.0 ou superior, incluindo dispositivos como Iphone e Ipad.

### Requisito de Portabilidade Três
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional Windows 7 ou superior.

### Requisito de Portabilidade Quatro
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional Linux, com processadores de 32 ou 64 bits, incluindo diversas distribuições: CentOs, Baseadas no Debian através dos pacotes .deb ou gerenciadores de pacote (apt ou snap), RedHat ou outras distribuições que suportam pacotes .rpm.

### Requisito de Portabilidade Cinco
A aplicação deve estar disponível e ser suportada em computadores ou notebooks com sistema operacional MacOs X 10.10.0 ou superior, com processadores de 64 bits.

## Conectividade
Descreve a integração da aplicação com diferentes plataformas de sistema e aplicações de terceiros.

### Requisito de Conectividade Um
A aplicação deve permitir a integração com redes sociais, para maior facilidade do usuário em se cadastrar.

### Requisito de Conectividade Dois
A aplicação deve manter um padrão de interface em todas as plataformas se adequando a qualquer dispositivo, para que o usuário possa ter uma fácil integração em todos os meios.

### Requisito de Conectividade Três
A aplicação deve manter a comunicação com o usuário por meio de notificações e por meio de e-mails previamente cadastrados.

## Tratamento de Falhas
Este tópico descrece como a aplicação deve identificar e tratar erros.

### Requisito de Tratamento de Falhas Um
A aplicação deve manter monitoramento e inspeção constantes de problemas afim de executar a correção de bugs.
### Requisito de Tratamento de Falhas Dois
A aplicação pede ao usuário que certifique-se de que está executando a última versão. É muito provável que a simples atualização resolva seu problema.
### Requisito de Tratamento de Falhas Três
A aplicação relata ao usuário que ocorreu uma falha no sistema e solicita um feedback para tentar resolve-lá. Com essas informações o suporte pode corrigir o problema mais rapidamente.

## Segurança
Aqui são tratados os requerimentos da aplicação quanto a sua segurança e a segurança dos dados que nela trafegam.

### Requisito de Segurança Um
A aplicação deve fornecer um sistema de autenticação segura, por meio de e-mail ou nome de usuário, acrescido da senha do usuário.

### Requisito de Segurança Dois
A aplicação deve oferecer a opção de Criptografar as mensagens dos grupos privados e mensagens diretas na aplicação, através de uma chave E2E única para cada usuário no servidor principal compartilhado da Rocket.Chat

### Requisito de Segurança Três
O sistema de possuir a opção do usuário adicionar servidores particulares para a prevenção e segurança dos seus dados.


## Restrições de Design

### Restrição de Design um
Na página principal do usuário, deverão estar acessíveis os chennels principais que o usuário acessa, um menu com as configurações do aplicativo e opções de suporte, bem como ferramentas de pesquisa para que o usuário procure rapidamente por usuários ou channels.

### Restrição de Design Dois
Dentro do channel, deverá existir uma interface de edição de texto com ferramentas para formatar e escrever o texto. Bem como menus visíveis com todas as funcionalidades relacionadas aquele channel em específico.

### Restrição de Design Três
A interface deverá estar disponível na maior pluralidade possível de idiomas.


### Restrição de Design Um

## Requisitos de Suporte ao usuário
Aqui são listados todos os requisitos referentes a ajuda e suporte aos usuários da aplicação.

### Requisito de Suporte ao Usuário Um
A plataforma deve possuir uma documentação bem organizada, no formato de uma Wikia. Que explique todas as funcionalidades e restrições aplicáveis.

### Requisito de Suporte ao Usuário Dois
Dentro do menu da aplicação deve haver um botão de ajuda. Que leva para uma página com problemas frequentes dos usuário e suas respectivas resoluções, bem como um link para a documentação e para entrar em contato com o suporte caso a ajuda ali não seja suficiente.

### Requisito de Suporte ao Usuário Três
A equipe de suporte ao usuário deve ser eficiente, de forma que o usuário que entre em contato para receber ajuda com algo deve receber sua resposta idealmente no prazo máximo de 24 horas.

### Requisito de Suporte ao Usuário Quatro
Deve haver um fórum dedicado a discussão de problemas e submissão de feedbacks acerca da aplicação. Pelo qual tanto os usuário quanto a equipe de desenvolvimento podem se manifestar.

### Requisito de Suporte ao Usuário Cinco
Por ser uma aplicação Open Source, na documentação deve haver uma secção explicando claramente os passos de como alguém pode contribuir com o projeto.

### Requisito de Suporte ao Usuário Seis
O repositório da aplicação do Github deve ser bem organizado, de modo que os interessados consigam facilmente submeter problemas, resoluções e feedbacks através das issues.


## Interfaces
Aqui são definidos todos os tipos de interface presentes na aplicação.

### Interfaces do Usuário
A plataforma deverá possuir uma interface gráfica, pela qual os usuários sejam capazes de interagir com todas as funcionalidades para eles disponíveis no sistema.

### Interfaces de Hardware
Os dispositivos de hardware nos quais a aplicação pode ser instalada são: Computadores Desktop, Notebooks e dispositivos mobile como smartphones e tablets. 

### Interfaces de Software
As definições de linguagens, frameworks e paradigmas para a criação e evolução do software devem ser as quais ofereçam a longo prazo uma fácil manutenção e confiabilidade.


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 28/04/2019 | 1.0 | Abertura do documento e inclusão do template | Marcos Nery|
| 28/04/2019 | 1.1 | Preenchimento inicial do documento, de introdução à funcionalidades | Marcos Nery|
| 29/04/2019 | 1.2 | Preenchendo os requisitos de usabilidade e desempenho | Gabriel Davi|
| 29/04/2019 | 1.3 | Adição dos requisitos de portabilidade e segurança | Lucas Maciel |
| 29/04/2019 | André Lucas | Adição dos requisitos de conectividade e tratamento de falhas | 1.4 |
| 29/04/2019 | 1.5 | Adição dos requisitos de suporte ao usuário | Marcos Nery|
| 29/04/2019 | 1.6 | Adição da listagem de Interfaces | Marcos Nery|
