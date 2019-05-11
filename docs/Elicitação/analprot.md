# Análise de protocolo

A técnica da análise de protocolo consiste em solicitar a uma pessoa que realize algum conjunto de tarefas enquanto descreve verbalmente, em voz alta, o processo que realiza. De tal forma que o aplicador da técnica pode também questiona-la sobre o porquê de cada ação se achar que faltou especificar algum passo, permitindo que partes do processo que normalmente seriam omitidas por já serem feitas de forma muito automática pelos praticantes sejam declaradas. 

## Metodologia

Para a execução do método, foram escolhidos dois usuários vonluntários que nunca havia usado o Rocket.chat antes, mas que já era familiarizado com outros aplicativos de comunicação. O aplicador da técnica interfiriu o mínimo possível, questionando o usuário apenas quando o mesmo deixava de comentar algum passo dentro do fluxo dele no uso do aplicativo. Com isso, foi pedido para que os dois usuários tentassem começar a usar o aplicativo, e que um deles criasse um canal para se comunicar com o outro, e após isso que eles explorassem livremente as opções de personalização e configurações da aplicação. Infelizmente, não pôde ser feita a gravação do processo, pois um dos usuários não permitiu. Porém segue abaixo os comentários de cada um dos usuários em cada parte de seu fluxo de uso, bem como quais requisitos foram levantados através de cada um deles.


## Usuário 1

|Atividade|Comentário|Requisitos fomentados|
|:--:|:--:|:--:|
|Login| Legal não ter que criar conta e poder fazer login com as contas de outros lugares, eu farei com o Facebook|AP1, AP10|
|Entrar no servidor| Agora estou entrando no servidor público do Rocket.chat, o que é uma opção legal de se ter, já que eu não faço parte de nenhum outro servidor instânciado |AP2|
|Primeiro contato com a tela principal do aplicativo|A interface é intuitíva o suficiente, mas seria bom ter um pequeno tutorial para ensinar onde faço cada coisa, já que o aplicativo parece ter muitas funcionalidades|AP3, AP6|
|Criar channel e adicionar usuário 2 para uma conversa|Para criar um channel de conversas o processo é bem fácil, a tela de criação pede o mínimo de informações necessárias para possibilitar a criação e a adição dos primeiros usuários|AP4|
|Adição de usuários no channel|Para adicionar um usuário basta usar a tag dele no aplicativo, o que é muito melhor que ter que adiciona-lo a lista de contatos|AP5|
|Conversa|A interface do chat é em maior parte intuitíva, consigo saber logo de início onde posso anexar arquivos ou emojis ao meu texto, mas ainda não sei como fazer algumas coisas que o app possuí, como a vídeoconferência|AP6|
|Personalização de perfil|Gostei, para personalizar meu perfil os campos são bem simples|AP7|
|Configurações do aplicativo| São dadas poucas opções de configuração no geral, o aplicativo parece pouco customizável|AP8|

## Usuário 2

|Atividade|Comentário|Requisitos fomentados|
|:--:|:--:|:--:|
|Login|Prefiro criar uma conta específica para este aplicativo, mas legal darem outras opções|AP1|
|Entrar no servidor| Poderia ficar mais claro para o  usuário essa diferença entre entrar no servidor geral do Rocket.chat e entrar em um servidor próprio |AP2|
|Primeiro contato com a tela principal do aplicativo|A interface é feia, mas consigo ver onde preciso ir pra fazer cada coisa|AP6, AP3|
|Entrar em channel criado pelo usuário 1|Essa parte foi fácil, bastou eu passar minha tag e pude ser adicionado ao grupo|AP5|
|Conversa|A interface do chat é boa, lembra a interface padrão da maioria dos aplicativos mais populares, e por isso é fácil saber onde fazer cada coisa|AP09|
|Personalização de perfil|A personalização de perfil é bem acessível, basta ir ao menu, e as opções dadas são suficientes|AP7|
|Configurações do aplicativo| Confuso, não sei exatamente onde tenho que clicar para alterar cada coisa|AP8|


## Requisitos elicitados

Abaixo seguem os requisitos elicitados pelo método, com seus respectivos códigos pelos quais pode ser visto qual comentário os gerou. A técnica de priorização utilizada foi a MoSCoW, que separa as prioridades em níveis que vão de Would para Must, passando pelos níveis intermediários Could e Should, nessa ordem de prioridade. E para definir a prioridade de cada requisito foram levados em consideração os seguintes critérios: 

	* Se ambos os usuários falaram sobre ou apenas 
	* O quão necessário seria tal requisito para cada usuário, e se a falta dele causaria grandes impedimentos no uso do aplicativo ou não, o que também foi coletado com os dois usuários durante a análise.


| Código | Descrição | Prioridade |
 |--|--|--|
|AP1| O aplicativo precisa permitir que o usuário faça login através de contas em outras aplicações, como Google ou Facebook, além de permitir a criação de contas singulares |  Should |
|AP2| Oferecer a opção de entrar no servidor público, deixando claro a diferenciação disso pra ter um servidor próprio | Could |
|AP3| O aplicativo deve oferecer ao usuário um tutorial de uso, logo que o mesmo entra na interface principal | Would |
|AP4| A criação de channels deve ser rápida e fácil, de forma que é perguntado ao usuário apenas o mínimo necessário de início| Should |
|AP5| Os usuários devem ser diferenciados por forma de tags, de tal forma que para adicionar alguém a um channel não é necessário adicionar seu número ou qualquer outra informação de contato | Must |
|AP6| A interface principal deve ser atrativa e intuitíva, deixando claro onde clicar para realizr cada ação possível | Must |
|AP7| A aplicação deve oferecer o usuário a opção de personalizar suas informações pessoais, como foto, email e tag | Should |
|AP8| As configurações do aplicativo devem permitir uma extensiva personalização do comportamento do aplicativo, e com um fluxo fácil de ser seguido | Should |
|AP09| As interfaces de chat devem lembrar o visto em outros aplicativos populares de comunicação, para que o usuário consiga, ao enxergar os padrões, saber como fazer cada coisa |Could|
|AP10|O usuário deverá ser capaz de criar uma conta no aplicativo|Must|


## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 14/04/2019 | 1.0 | Adição da análise de protocolo | Marcos Nery |
| 02/05/2019 | 1.1 | Adição do requisito AP10, por necessidades levantadas nos cenários | Marcos Nery |

