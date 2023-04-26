# Introdução

TODO

# Requisitos

- [ ] RF01 - Registro e Login [João](https://github.com/wchar-t)
- [ ] RF02 - Editar Configurações de Perfil [Emanuel Catão Montenegro](https://github.com/emanuelcatao)
- [ ] RF04 - Alteração de Senha do Usuário [Luiz Henrique Campos](https://github.com/lizenriq)
- [ ] RF05 - Recuperar senha do usuário [Antonio André](https://github.com/andrebarceloschagas)
- [ ] RF06 - Solicitar Suporte [Helorrayne Cristine](https://github.com/HeloCris)
- [ ] RF08 - Transmitir tela ao vivo [Luis Felipe](https://github.com/Luis-Felipe-N)
- [ ] RF11 - Seguir usuário [Ruan Carlos Ribeiro de Sena Mangueira](https://github.com/okkvlt)
- [ ] RF13 - Banir Usuário Do Chat. [Afonso Dglan Cirqueira Rodrigues](https://github.com/afonsodglan) Revisador --> Anderson Freitas
- [ ] RF15 - Vincular conta de usuário com outros serviços [Lucas José de Sousa Gomes](https://github.com/yamatosz)
- [ ] RF17 - Receber pontos ao assistir transmissões ao vivo [Anderson Freitas](https://github.com/freitasanderson)


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

## RF02 - Editar Configurações de Perfil
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
|Passo 3|Usuário as atualiza de imagem de perfil, nome e/ou descrição|
|Passo 4|O sistema faz as devidas validações|
|Passo 5|Em caso de  sucesso, o usuário poderá verificar se as alterações foram aplicadas visualizando seu perfil|

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

###  Opções de usuário

|Opção|Descrição|
| - | - |
|Foto de Perfil?|Define/Altera a foto de perfil do usuário|
|Nome?|Define/Altera o apelido do usuário|
|Descrição?|Define/Altera a descrição do usuário|
|Salvar|Ao clicar, as informações são atualizados|

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder personalizar meu perfil com minha imagem de perfil, nome e outras informações pessoais, para que eu possa me identificar e me conectar com outros usuários. Isso me permite ter uma experiência personalizada e segura no aplicativo de livestreaming.| O usuário pode personalizar completamente seu perfil de acordo com suas preferências e atualizá-lo conforme necessário.|

![RF](https://placehold.co/600x400/EEE/31343C)

## RF04 - Alteração de Senha do Usuário

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Alteração de Senha do Usuário|
|Resumo|Este caso de uso descreve como um usuário autenticado em um sistema pode alterar sua senha atual para uma nova senha.|
|Ator principal|Usuário.|
|Ator secundário|  |
|Pré-condição|O usuário deve estar autenticado no sistema e acessando sua conta.|
|Pós-condição|A senha do usuário é atualizada no sistema com a nova senha fornecida pelo usuário.|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário clica em "Alterar senha" na página de configurações da conta.|
|Passo 2|O sistema exibe um formulário solicitando a senha atual e a nova senha.|
|Passo 3|O usuário preenche o formulário com a senha atual e a nova senha.|
|Passo 4|O sistema valida se a senha atual está correta e se a nova senha atende aos critérios de segurança (como comprimento mínimo, uso de caracteres especiais, etc.).|
|Passo 5|Se a validação for bem-sucedida, o sistema atualiza a senha do usuário com a nova senha e exibe uma mensagem de confirmação para o usuário.|
|Passo 6|Se a validação falhar, o sistema exibe uma mensagem de erro informando o motivo da falha (por exemplo, "senha atual incorreta" ou "nova senha muito curta") e solicita que o usuário corrija o problema e tente novamente.|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 4a|Se a senha atual não estiver correta, o sistema exibe uma mensagem de erro informando que a senha atual está incorreta e solicita que o usuário insira a senha correta.|
|Passo 4b|Se a nova senha não atender aos critérios de segurança, o sistema exibe uma mensagem de erro informando quais critérios não foram atendidos e solicita que o usuário insira uma nova senha que atenda a esses critérios.|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Senha atual|Sim|Sim|Texto|
|Nova senha|Sim|Sim|Texto|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Nova Senha?|Altera a Senha do usuário|
|Salvas|Ao clicar, as informações sãosalvas atualizadas|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usuário, eu quero poder alterar minha senha para garantir a segurança da minha conta.|Os novos dados de senha devem ser validados e salvos, o usuário deve conseguir utilizar sua nova senha para login, com a antiga se tornando incapaz do mesmo.|

![RF](https://placehold.co/600x400/EEE/31343C)


## RF05 - Recuperar senha do usuário
###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Recuperar senha|
|Resumo|Painel para recuperação de senha do perfil|
|Ator principal|Usuário cadastrado|
|Ator secundário| Não possui |
|Pré-condição|O usuário deve ser cadastrado, ter o aplicativo instalado e não estar logado em sua conta.|
|Pós-condição|A senha do usuário recuperada com sucesso e estar logado na conta.|

###  Fluxo principal

|Passos|Descrição|
| - | - |
|Passo 1|O usuário clica no botão "Esqueci minha senha" na página de login.|
|Passo 2|O sistema exibe um formulário para o usuário preencher com o endereço de e-mail associado à sua conta.|
|Passo 3|O usuário preenche o formulário com seu endereço de e-mail e clica no botão "Enviar".|
|Passo 4|O sistema envia um e-mail contendo um link de recuperação de senha para o endereço de e-mail fornecido pelo usuário.|
|Passo 5|O usuário acessa seu e-mail, abre a mensagem de recuperação de senha e clica no link fornecido.|
|Passo 6|O sistema exibe um formulário para o usuário criar uma nova senha.|
|Passo 7|O usuário preenche o formulário com uma nova senha e clica no botão "Salvar".|
|Passo 8|O sistema armazena a nova senha do usuário e redireciona o usuário para a página de login.|


###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1|O endereço de e-mail fornecido pelo usuário não está registrado no sistema.|
|Passo 2|O sistema exibe uma mensagem de erro informando que o endereço de e-mail fornecido não está registrado no sistema.|
|Passo 3|O usuário é solicitado a tentar novamente.|

###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|Nome|Sim|Sim|Texto|
|Email|Sim|Sim|Texto|
|Senha|Sim|Sim|Texto|



###  Opções de usuário

|Opção|Descrição|
| - | - |
|"Esqueci minha senha"|Botão que abre uma nova pagina para a recuperação de senha.|
|Email|Email do usuário registrado no sitema na criação da conta.|
|Enviar|Ao clicar, as informações de recuperação são enviadas ao email registrado pelo usuário.|
|Página de recuperação|Página de recuperação da senha do usuário.|
|Enviar|Ao clicar, salva a senha recuperada e redireciona o usuário para a página de login.|

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder recuperar minha senha para acessar minha conta caso eu a esqueça ou perca, a fim de não perder o acesso aos meus dados e funcionalidades da plataforma.| Certificar que todos os dados são validados e senha recuperada e o usuário consiga fazer login ao fim.|

![RF](https://placehold.co/600x400/EEE/31343C)

## RF06 - Solicitar Suporte

#### Autor: @HeloCris - Helorrayne Cristine

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Solicitar Suporte|
|Resumo|O usuário irá visualizar o perfil, onde após entrar no perfil, ele poderá solicitar suporte caso precise. Ele visualizará algumas ajudas na tela, mas caso mesmo assim não seja possível solucionar, pode ser pedido ajuda ao suporte do aplicativo.|
|Ator principal|Usuário final cadastrado|
|Ator secundário| |
|Pré-condição|  É necessário que o usuário possua o aplicativo instalado no dispositivo móvel e ter uma conta válida|
|Pós-condição| |

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário abre o aplicativo, e na tela inicial entra com a conta caso já possua ou cria uma nova
Passo 2|É exibido a tela inicial
Passo 3|Para solicitar suporte vai no ícone com a foto do perfil
Passo 4|Seleciona suporte
Passo 5| Nessa tela o usuário poderá solicitar a ajuda referente a sua dúvida
Passo 6| O usuário poderá tentar resolver pelo guia, ou conversar com o suporte, onde será colocado as informações do ocorrido
Passo 7| Caso o usuário não encontre a ajuda desejada no guia, ele pode selecionar a opção de conversar com o suporte
Passo 8| O usuário preenche as informações necessárias sobre o ocorrido, como descrição do problema, capturas de tela, etc.
Passo 9|O usuário envia a solicitação de suporte
Passo 10|O sistema registra a solicitação de suporte e notifica a equipe de suporte do aplicativo
Passo 11|A equipe de suporte do aplicativo recebe a solicitação e entra em contato com o usuário para fornecer assistência e resolver o problema
Passo 12|O suporte do aplicativo trabalha com o usuário para identificar e resolver o problema, podendo solicitar mais informações ou fornecer orientações adicionais
Passo 13|Após o problema ser resolvido, o suporte do aplicativo fecha o chamado de suporte e registra as ações tomadas para solucioná-lo
Passo 14| O usuário recebe a confirmação de que o problema foi resolvido e o chamado de suporte é encerrado

|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|“Outras opções” de cadastro |

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Login | Sim | Sim | E-mail e senha
Perfil| Sim | Não| Botão
Suporte| Sim| Não| Botão|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Login|O usuário precisa estar logado
Perfil|O usuário clica no ícone do perfil
Suporte|O usuário clica no suporte|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usuário final cadastrado no aplicativo, eu quero poder solicitar suporte quando tiver dúvidas ou problemas, para obter assistência adequada|Eu devo ter o aplicativo instalado em meu dispositivo móvel e estar logado com uma conta válida|

|

![RF](https://placehold.co/600x400/EEE/31343C)

## RF08 - Transmitir tela ao vivo

### Atributos

| Item | Descrição |
| --- | --- |
| Caso de Uso | Função que permiti iniciar uma transmissão ao vivo |
| Resumo | Usuário inicia transmissão para que outros usuários possam assistir |
| Ator principal | Usuário logado |
| Ator secundário |  |
| Pré-condição | Estar logado |
| Pós-condição | Tela será transmitida para outros assistirem |

### Fluxo principal

| Passos | Descrição |
| --- | --- |
| Passo 1 | Usuário acessa a página canal e clica em “Iniciar transmissão” |
| Passo 2 | Seleciona a entrada de vídeo e áudio |
| Passo 3 | Clica em “Iniciar” |

### Fluxo alternativo

| Passos | Descrição |
| --- | --- |
| Passo 1 | Se o usuário não estiver logado, ele será redirecionado para parte de login |

### Campos

| Campo | Obrigatório | Editável | Formato |
| --- | --- | --- | --- |
| Entrada de vídeo | Não | Sim | video/webm |
| Entrada de áudio | Não | Sim | audio/mpeg |

### Opções de usuário

| Opção | Descrição |
| --- | --- |
| Entrada de vídeo | Escolher qual entrada de vídeo transmitir |
| Entrada de áudio | Escolher qual entrada de áudio transmitir |
| Salvar transmissão | Selecionar se a transmissão será gravada |

### User Story

| User Story | Critério de Avaliação |
| --- | --- |
| Como usuário, quero compartilhar com outras pessoas minhas atividades como jogar, programar ou apenas conversar. | Usuário deve estar logado. |

![RF](https://placehold.co/600x400/EEE/31343C)

## RF11 - Seguir usuário

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Seguir usuários|
|Resumo|Usuário segue outro(s) usuário(s) para acompanhar suas atividades|
|Ator principal|Usuário logado|
|Ator secundário||
|Pré-condição|O usuário deve estar logado em sua conta para ser capaz de seguir outro(s) usuário(s)|
|Pós-condição|O usuário acompanhará as atividades do(s) usuário(s) que segue|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário acessa o perfil ou alguma transmissão do usuário X que deseja seguir|
|Passo 2|O usuário se deparará com um botão contendo um texto "Seguir"|
|Passo 3|Ao clicar no botão, o usuário imediatamente estará seguindo o usuário X e poderá acompanhar todas as suas atividades|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário acessa o perfil ou alguma transmissão do usuário X que deseja seguir|
|Passo 2|O usuário talvez já esteja seguindo o usuário X e então se deparará com um botão destacado escrito "Seguindo"|
|Passo 3|Ao clicar no botão, o usuário imediatamente deixará de seguir o usuário X e não mais poderá acompanhar todas as suas atividades|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|||||

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Seguir usuário X|Deixar de seguir usuário X|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como usuário, quero poder ser capaz de seguir quantos outros usuários eu quiser para que com isso eu possa acompanhar todas as suas atividades, incluindo por exemplo atualizações, novas transmissões ao vivo e novas gravações de transmissões feitas pelo(s) usuário(s) que sigo|O usuário pode seguir e deixar de seguir quantos usuários quiser e quando quiser, podendo administrar dessa forma o conteúdo que será capaz de acompanhar e que lhe será sugerido|

![RF](https://placehold.co/600x400/EEE/31343C)

## **RF13 - Banir Usuário Do Chat**

#### Autor: @afonsodglan - Afonso Dglan Cirqueira Rodrigues.

---

### Revisor: @freitasanderson - Anderson Freitas
| Item | Descrição |
| --- | --- |
| Caso de Uso | Banir Usuário Do Chat |
| Resumo          | Uma funcionalidade que pode ser ultilizada pelos administradores da live ou do próprio sistema, possibilitando banir usuários que violarem as diretrizes do sistema. |
| Ator principal  | administradores de live.|
| Ator secundário | próprio sistema.|
| Pré-condição    | Está logado em uma das contas que fazem parte da administração da live.|
| Pós-condição    | Não há.|

#### Fluxo principal

| Passos  | Descrição                                                          |
| ------- | ------------------------------------------------------------------ |
| Passo 1 | Buscar pelo usuário.                                               |
| Passo 2 | Clicar no botão bloquear usuário.                                  |
| Passo 3 | Confirmar ação.                                                    |

#### Campos

| Campo                 | Obrigatório | Editável | Formato |
| --------------------- | ----------- | -------- | ------- |
| Buscar pelo usuário   | Sim         | Sim      | Texto   |
| Bloquear usuário      | Sim         | Não      | Botão   |
| Confirmar ação        | Sim         | Não      | Botão   |


#### Opções de usuário

| Opção                    | Descrição                                                                                             | Atalho |
| ------------------------ | ----------------------------------------------------------------------------------------------------- | ------ |
| Bloquear usuário do chat | Ao clicar nessa aba o usuário vai poder bloquear contas no chat                                       |        |

#### Relatório de usuário

| Campo | Descrição | Formato |
| ----- | --------- | ------- |
| --    | --        | --      |

#### Fluxo alternativo

| Passos      | Descrição                                                                                           |
| ----------- | --------------------------------------------------------------------------------------------------- |
|             |                                                                                                     |


# User story

Agora iremos escrever uma história de usuário para uma persona.

**Persona um, usuário comum.**

| Epic                                                                                                                                                                                                               | User Story                                                                                                                                 | Critério de aceitação                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| Eu enquanto "usuário admistrador" quero "poder bloquear contas de usuário que violaram as regras da plataforma por meio de mensagens ofensivas." para "ter mais segurança e uma experiências mais completa". | Enquanto "usuário admistrador" preciso ter controle sobre o conteúdo que é inserido no chat da própria live | Certifique-se que o usuário é capaz de **Bloquear usuário do chat.** |

Prototipo
## RF15 - Vincular conta de usuário com outros serviços

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Vincular conta de usuário com outros serviços|
|Resumo|Página para vincular conta do usuário com outros serviços|
|Ator principal|Usuário cadastrado|
|Ator secundário|Não possui|
|Pré-condição|O usuario deve estar devidamente logado em sua conta|
|Pós-condição|A conta do usuario estará vinculada com sua conta de outros serviços|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário deve fazer login na sua conta e clicar no botão "Configurações de perfil"|
|Passo 2|O usuário é redirecionado para a página em que pode promover as atualizações de imagem de perfil, nome, descrição e outras configurações de visibilidade e segurança|
|Passo 3|Na seção de vinculação de conta, o usuário deverá clicar no botão que represente o serviço ao qual ele deseja vincular a sua conta na plataforma|
|Passo 4|O usuário será redirecionado para uma página para que ele autorize a vinculação das duas contas|
|Passo 5|Em caso de sucesso, o usuário será redirecionado para a plataforma informando o sucesso ao vincular a conta|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Se o usuário não autorizar, ou houver falha no momento da autorização de vinculação, o usuário será redirecionado para a plataforma informando que ocorreu um erro|
|Passo 2|Se o usuário não conseguir vincular a conta a outros serviços por dificuldade, ele poderá entrar em contato com a equipe de suporte ao cliente da plataforma|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Nenhum|Não|Não|Nenhum|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Vincular conta|Vincula a conta da plataforma à uma conta de outro serviço|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Eu como usuário quero vincular minha conta na plataforma com minha conta em outro serviço, assim eu posso utilizar minhas preferências e também terei mais segurança na minha conta|Todas as opções de configurações de perfil devem estar funcionando perfeitamente, assim como o serviço ao qual o usuário deseja vincular sua conta. O usuário poderá vincular sua conta na página de configuração de perfil ao serviço que estiver disponível e desejar |

![RF](https://placehold.co/600x400/EEE/31343C)


## RF17 - Receber pontos ao assistir transmissões ao vivo

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso| Receber pontos ao assistir|
|Resumo| Usuário recebe pontos conforme assiste uma transmissão ao vivo|
|Ator principal| Usuário logado|
|Ator secundário||
|Pré-condição|O usuário deve estar logado em sua conta e estar assistindo uma transmissão ao vivo|
|Pós-condição|O usuário receberá pontos que posteriormente podem ser trocados|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário logado acessa uma transmissão ao vivo|
|Passo 2|Conforme a transmissão selecionada estiver sendo reproduzida e não minimizada o usuário recebe pontos|
|Passo 3|O sistema contabiliza esses pontos e o adiciona ao saldo do usuário logado|
|Passo 4|Posteriormente o usuário poderá resgatar esses pontos em troca de benefícios ou prêmios|




### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Se o usuário não estiver logado ou estiver com alguma restrição, será alertado que não está elegível para receber pontos|
|Passo 2|Se o usuário não estiver logado, ele poderá efetuar login. Se for algum problema no sistema, ele poderá entrar em contato com a equipe de suporte ao cliente para obter ajuda|


### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Nenhum|Não|Não|Nenhum|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Receber Pontos|O usuário recebe pontos|
|Resgatar Pontos|O usuário pode resgatar os seus pontos|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Eu como usuário quero assistir uma transmissão ao vivo e receber pontos que posso utilizar para resgatar prêmios ou benefícios na plataforma|Todas os pontos devem ser contabilizados corretamente (quando elegível) ao assistir a transmissão e devem poder serem resgatados conforme desejar alguma das opções de resgate disponíveis|

![RF](https://placehold.co/600x400/EEE/31343C)
