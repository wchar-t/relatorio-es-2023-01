# Introdução

TODO

# Requisitos

- [ ] RF01 - Registro e Login [João](https://github.com/wchar-t)
- [ ] RF02 - Configurações de Perfil [Emanuel Catão Montenegro](https://github.com/emanuelcatao)

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

## RF02 - Configurações de Perfil
###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Configurações de Perfil|
|Resumo|Painel para personalização e configuração do perfil|
|Ator principal|Usuário cadastrado|
|Ator secundário| Não possui |
|Pré-condição|O usuário deve estar logado em sua conta|
|Pós-condição|As configurações do perfil estarão atualizadas|

###  Fluxo principal

|Passos|Descrição|
| -- | - |
|Passo 1|O usuário acessa sua conta e clica em "Configurações de perfil"|
|Passo 2|O usuário é redirecionado para a página em que pode promover as atualizações de imagem de perfil, nome, descrição e outras configurações de visibilidade e segurança|
|Passo 3|O sistema faz as devidas validações|
|Passo 4|Em caso de  sucesso, o usuário poderá verificar se as alterações foram aplicadas visualizando seu perfil|

###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1|Se o usuário tentar salvar informações inválidas, o sistema deve exibir uma mensagem de erro indicando que a informação é inválida e instruir o usuário a corrigi-la antes de tentar salvar novamente.|
|Passo 2|Se o usuário não conseguir salvar as informações do perfil, ele pode entrar em contato com a equipe de suporte ao cliente para obter ajuda adicional.|

###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|Foto|Sim|Sim|Imagem|
|Nome|Sim|Sim|Texto|
|Descrição|Sim|Sim|Texto|
|Email|Sim|Sim|Texto|
|Senha|Sim|Sim|Texto|
|Notificações|Sim|Sim|Lista de itens|
|Visibilidade|Sim|Sim|Checkbox|


###  Opções de usuário

|Opção|Descrição|
| - | - |
|Foto de Perfil?|Define/Altera a foto de perfil do usuário|
|Nome?|Define/Altera o apelido do usuário|
|Descrição?|Define/Altera a descrição do usuário|
|email?|Define/Altera a email do usuário|
|senha?|Define/Altera a email do usuário|
|notificações?|Define a maneira que o usuário quer lidar com as notificações (não exibir, silenciar por X horas/dias)|
|visibilidade?|Define/Altera a visibilidade do usuário (privado/público)|
|Salvar|Ao clicar, as informações são atualizados|

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder personalizar meu perfil com minha imagem de perfil, nome e outras informações pessoais, para que eu possa me identificar e me conectar com outros usuários. Também quero poder configurar minhas preferências de notificação e privacidade para controlar o tipo de informação que compartilho com outros usuários e quais notificações recebo. Isso me permite ter uma experiência personalizada e segura no aplicativo de livestreaming.| Todas as opções de configurações de perfil e preferências de notificação e privacidade estão disponíveis e funcionando corretamente. O usuário pode personalizar completamente seu perfil de acordo com suas preferências e atualizá-lo conforme necessário.|

![RF](https://placehold.co/600x400/EEE/31343C)
