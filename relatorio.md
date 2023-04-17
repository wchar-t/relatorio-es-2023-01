# Introdução

TODO

# Requisitos

- [ ] RF01 - Registro e Login [João](https://github.com/wchar-t)

# Casos de uso e User stories

## RF01 - Registro e Login

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Registro e Login|
|Resumo|Painel onde se faz o registro e login de contas.|
|Ator principal|Usuário que acessa|
|Ator secundário||
|Pré-condição|Dados válidos, conforme os campos|
|Pós-condição|O ator estará logado|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Escolher se fará o registro ou login|
|Passo 2|Preencher as informações dos campos solicitados|
|Passo 3|O sistema faz as devidas validações|
|Passo 4|Em caso de registro ou login com sucesso, o ator será redirecionado|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Será notificado em falha de validação dos campos|
|Passo 2|O usuário pode fazer logout|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Nome|Não|Sim|Texto|
|Usuário|Sim|Sim|Texto|
|Senha|Sim|Sim|Texto|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Registro?|Define o modo de registro para o formulário|
|Enviar|Ao clicar, a ação registro ou login é feita, a depender do campo anterior|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usário, eu quero fazer registro ou login, para que eu possa ter a experiência completa da plataforma|Certificar que todos os dados são validados e o usuário consiga fazer login ao fim|

![RF](https://placehold.co/600x400/EEE/31343C)