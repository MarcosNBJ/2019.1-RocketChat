#Especificação de casos de uso

## EC0

|**Título**|
|--|
| **Descrição**|
| |
| **Atores** |
| |
| **Pré Condições** |
| |
| **Fluxo Principal** |
| |
| **Fluxos Alternativos** |
| |
| **Fluxos de Exceção**|
| |
| **Pós Condições**|
| |
|**Requerimentos especiais**|
| |
| **Cenário** |
| |

## EC1

|**Fixar Mensagem**|
|--|
| **Descrição**|
| - Funcionalidade que tem como objetivo fazer com que o usuário consiga encontrar mensagens com mais facilidade, possui uma similaridade com a funcionalidade de favoritar mensagem |
| **Atores** |
| - [usuário](lexicos.md#l19) [logado](lexicos.md#l62) no aplicativo |
| **Pré Condições** |
| - usuário deve estar logado no aplicativo |
| - usuário deve ser integrante em uma room no aplicativo |
| **Fluxo Principal** |
| 1 - Usuário seleciona seleciona uma room <br> 2 - Seleciona uma mensagem de seu interesse <br> 3 - Abre o menu de opções da mensagem <br> 4 - Seleciona a opção de "fixar mensagem" |
| **Fluxos Alternativos** |
| - |
| **Fluxos de Exceção**|
| __FE1__ - Erro de conexão |
| **Pós Condições**|
| - As mensagens fixadas ficarão disponíveis em “mensagens fixadas” localizada no menu principal da [room](lexicos.md#l51) |
| **Cenário** |
| - [Fixar Mensagem](cenarios.md#c11) |

## Versionamento

| Data | Versão | Modificação | Autor |
|  :------: | :------: | :------: | :------: |
| 25/04/2019 | 1.0 | Abertura do documento | Gabriel Davi|
| 25/04/2019 | 1.1 | Inclusão do template para criação das especificações de casos de uso | Marcos Nery|
| 26/04/2019 | 1.2 | Adição da EC1 | Lucas Maciel |
