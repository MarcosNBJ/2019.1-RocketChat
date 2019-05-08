# Product Backlog

1. [T01 - Entrar no aplicativo](#t01-entrar-no-aplicativo)
    1. [EP01 - Fazer Login](#ep01-fazer-login)
    2. [EP02 - Fazer Cadastro](#ep02-fazer-cadastro)


## T01 - Entrar no aplicativo

### EP01 - Fazer Login

#### US01

| ID   | Eu, como | desejo | porque| comentário | pontos | prioridade |
|------|----------|-------|---------------------|--------|------------|
| US01 | Usuário  | Fazer login na aplicação utilizando minha conta | gostaria de acessar as funcionalidades de um usuário logado | Deve haver um limite de tentativas |        | Must       |

* O usuário deverá ser capaz de utilizar uma conta previamente criada na aplicação para fazer login, digitando seu usuário e sua senha 
* O usuário deverá conseguir utilizar o email no lugar do nome de usuário se preferir 
* Se forem excedidas três tentativas sem sucesso de login com um nome de usuário, as tentativas devem ser bloqueadas temporariamente e o dono da conta deverá receber um email
* Quando o usuário errar os dados de entrada, ele deverá ser avisado se errou o nome ou a senha

_Originada em: [AP1](../Elicita%C3%A7%C3%A3o/analprot.md#requisitos-elicitados)_


#### US02

| ID   | Eu, como | desejo | porque  | Comentário | Pontos | Prioridade |
|------|----------|--------|---------|------------|--------|------------|
| US02 | Usuário  | Fazer login na aplicação utilizando minhas redes sociais | gostaria de acessar as funcionalidades de um usuário logado sem ter que criar uma nova conta | Login pelo facebook, google ou twitter| | Must|

* O usuário deverá ser capaz de fazer login no aplicativo utilizando uma conta que ele possui em uma dessas redes sociais: GitHub, Facebook, Twitter e Google

_Originada em: [INT1.3](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [AP1](../Elicita%C3%A7%C3%A3o/analprot.md#requisitos-elicitados)_

### EP02 - Fazer Cadastro

#### US03

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
|US03|Usuário|Criar uma conta no aplicativo|gostaria de ter uma conta para fazer login e acessar as funcionalidades do aplicativo|Cada usuário deve cadastrar um email, usuário e senha||Must|

* O usuário deverá ser capaz de criar uma conta no aplicativo, para conseguir fazer login posteriormente
* As seguintes informações do usuário deverão ser requisitadas para cadastrar a conta: email, usuário, tag e senha


_Originada em: [AP10](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_


#### US04

| ID | Eu, como | desejo | porque | comentário | pontos | prioridade |
|----|----------|--------|--------|------------|--------|------------|
|US04|Dono do servidor|Modificar as informações pedidas na criação de conta |gostaria de ter uma experiência mais customizada, adaptada as necessidades do meu grupo|||Should|

* O dono do servidor deverá ser capaz de, ao criar o servidor, modificar quais informações são pedidas ao usuário quando o mesmo cria uma conta 
* O dono do servidor deverá ser capaz de modificar essas definições a qualquer momento que desejar

_Originada em: [AP10](../Elicita%C3%A7%C3%A3o/Introspeccao.md#introspeccao-02), [C1](cenarios.md#c1-v2)_
