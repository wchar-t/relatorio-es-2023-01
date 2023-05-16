# Introdução

Plataforma de streaming de vídeo focada em jogos e entretenimento ao vivo. O sistema permite que os usuários transmitam ao vivo suas jogadas de videogame, performances musicais, bate-papos e outras formas de conteúdo ao vivo. Os usuários podem assistir às transmissões ao vivo de outros usuários, segui-los, fazer comentários e interagir com os criadores de conteúdo em tempo real.

# Membros
* [João Pedro](https://github.com/wchar-t)
* [Emanuel Montenegro](https://github.com/emanuelcatao)
* [Lucas José](https://github.com/yamatosz)
* [Afonso Dglan](https://github.com/AfonsoDglan)
* [Antonio André Barcelos Chagas](https://github.com/andrebarceloschagas)
* [Anderson Freitas](https://github.com/freitasanderson)
* [Helorrayne Cristine](https://github.com/HeloCris)
* [Luiz Henrique](https://github.com/lizenriq)
* [Luis Felipe Nunes](https://github.com/Luis-Felipe-N)
* [Victor Campelo](https://github.com/Victorcampelo14)
* [Ruan Carlos](https://github.com/okkvlt)

# Requisitos

## Iteração 1:

- [x] [RF01](#rf01---cadastrar-usuário) - Cadastrar Usuário [João](https://github.com/wchar-t). Revisão: [João](https://github.com/wchar-t)
- [x] [RF03](#rf03---editar-configurações-de-perfil) - Editar Configurações de Perfil [Emanuel Catão Montenegro](https://github.com/emanuelcatao). Revisão: [João](https://github.com/wchar-t)
- [x] [RF04](#rf04---alterar-senha-do-usuário) - Alterar Senha do Usuário [Luiz Henrique Campos](https://github.com/lizenriq). Revisão: [Anderson Freitas](https://github.com/freitasanderson)
- [x] [RF05](#rf05---recuperar-senha-do-usuário) - Recuperar Senha do Usuário [Antonio André](https://github.com/andrebarceloschagas). Revisão: [João](https://github.com/wchar-t)
- [x] [RF06](#rf06---solicitar-suporte) - Solicitar Suporte [Helorrayne Cristine](https://github.com/HeloCris). Revisão: [João](https://github.com/wchar-t)
- [x] [RF07](#rf07---visualização-da-politica-de-privacidade-da-plataforma) - Visualizar Politica de Privacidade da Plataforma [Victor Campelo](https://github.com/victorcampelo14). Revisão: [Anderson Freitas](https://github.com/freitasanderson)
- [x] [RF08](#rf08---transmitir-tela-ao-vivo) - Transmitir Tela Ao Vivo [Luis Felipe](https://github.com/Luis-Felipe-N). Revisão: [João](https://github.com/wchar-t)
- [x] [RF11](#rf11---seguir-usuário) - Seguir Usuário [Ruan Carlos Ribeiro de Sena Mangueira](https://github.com/okkvlt). Revisão: [João](https://github.com/wchar-t)
- [x] [RF13](#rf13---banir-usuário-do-chat) - Banir Usuário Do Chat [Afonso Dglan Cirqueira Rodrigues](https://github.com/afonsodglan). Revisão: [Emanuel Catão Montenegro](https://github.com/emanuelcatao)
- [x] [RF15](#rf15---vincular-conta-de-usuário-a-outros-serviços) - Vincular Conta de Usuário a Outros Serviços [Lucas José de Sousa Gomes](https://github.com/yamatosz). Revisão: [João](https://github.com/wchar-t)
- [x] [RF17](#rf17---receber-pontos-ao-assistir-transmissões-ao-vivo) - Receber Pontos ao Assistir Transmissões Ao Vivo [Anderson Freitas](https://github.com/freitasanderson). Revisão: [João](https://github.com/wchar-t)

## Iteração 2:

- [x] [RF02](#rf02---fazer-login) - Fazer Login [João](https://github.com/wchar-t). Revisão: [João](https://github.com/wchar-t)
- [x] [RF12](#rf12---filtrar-conteúdo) - Filtrar Conteúdo [Emanuel Catão Montenegro](https://github.com/emanuelcatao). Revisão: [Lucas José de Sousa Gomes](https://github.com/yamatosz)
- [x] [RF10](#rf10---salvar-transmissão) - Salvar Transmissão [Luis Felipe](https://github.com/Luis-Felipe-N). Revisão: [Anderson Freitas](https://github.com/freitasanderson)
- [x] [RF14](#rf14---compartilhar-perfil-da-plataforma) - Compartilhar Transmissão ao Vivo [Lucas José de Sousa Gomes](https://github.com/yamatosz). Revisão: [João](https://github.com/wchar-t)
- [x] [RF16](#rf16---buscar-termo-na-plataforma) - Buscar Termo na Plataforma [Helorrayne Cristine](https://github.com/HeloCris). Revisão: [João](https://github.com/wchar-t)
- [x] [RF18](#rf18---sortear-brindes-especiais-ao-assistir-transmissões-ao-vivo) - Sortear brindes especiais ao Assistir Transmissões Ao Vivo [Anderson Freitas](https://github.com/freitasanderson). Revisão: [Ruan Carlos Ribeiro de Sena Mangueira](https://github.com/okkvlt)
- [x] [RF19](#rf19---denunciar-transmissão) - Denunciar Transmissão [Luiz Henrique Campos](https://github.com/lizenriq). Revisão: [Lucas José de Sousa Gomes](https://github.com/yamatosz)
- [x] [RF20](#rf20---bloquear-usuário) - Bloquear Usuário [Antonio André](https://github.com/andrebarceloschagas). Revisão: [João](https://github.com/wchar-t)
- [x] [RF21](#rf21---definir-qualidade-do-vídeo) - Definir qualidade do vídeo [Afonso Dglan Cirqueira Rodrigues](https://github.com/afonsodglan). Revisão: [João](https://github.com/wchar-t)
- [x] [RF22](#rf22---ativar-notificações-de-usuário-que-segue) - Ativar notificações de usuário que segue [Ruan Carlos Ribeiro de Sena Mangueira](https://github.com/okkvlt). Revisão: [João](https://github.com/wchar-t)

# Casos de uso e User stories

## RF01 - Cadastrar Usuário

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Criar uma conta|
|Resumo|Painel onde se faz o registro de contas|
|Ator principal|Usuário que acessa|
|Ator secundário||
|Pré-condição|Dados válidos, conforme os campos|
|Pós-condição|O ator estará registrado|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Escolher a opção "registro"|
|Passo 2|Preencher as informações dos campos solicitados|
|Passo 3|O sistema faz as devidas validações|
|Passo 4|Em caso de registro, o usuário estará criado e pode ser logado|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Será notificado em falha de validação dos campos|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Nome|Não|Sim|Texto|
|Usuário|Sim|Sim|Texto|
|Senha|Sim|Sim|Texto|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Enviar|Envia os dados ao backend, que faz validações|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usário, eu quero fazer registron, para que eu possa fazer login e ter a experiência completa da plataforma|Certificar que todos os dados são validados e registrados|

## RF02 - Fazer Login

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Entrar em uma conta|
|Resumo|Painel onde se faz o login de contas|
|Ator principal|Usuário que acessa|
|Ator secundário||
|Pré-condição|Dados válidos, conforme os campos|
|Pós-condição|O ator estará logado|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Escolher a opção "login"|
|Passo 2|Preencher as informações dos campos solicitados|
|Passo 3|O sistema faz as devidas validações|
|Passo 4|Em caso de login com sucesso, o ator será redirecionado|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Será notificado em falha de validação dos campos|
|Passo 2|O usuário pode fazer logout|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Usuário|Sim|Sim|Texto|
|Senha|Sim|Sim|Texto|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Enviar|Envia dados ao backend, que faz as checagens|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usário, eu quero fazer login, para que eu possa ter a experiência completa da plataforma|Certificar que todos os dados são validados e o usuário consiga fazer login ao fim|

## RF03 - Editar Configurações de Perfil
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

## RF04 - Alterar Senha do Usuário

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


## RF05 - Recuperar Senha do Usuário
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


## RF07 - Visualização da Politica de Privacidade da Plataforma
###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Cadastro de usuário|
|Resumo|Painel para cadrasto de usuário na plataforma|
|Ator principal|Continuidade no cadastro|
|Ator secundário| Interrupção no cadastro |
|Pré-condição|O usuário deverá optar por aceitar ou não os termos de politica de privacidade.|
|Pós-condição|O cadastro do usuário dará prosseguimento.|

###  Fluxo principal

|Passos|Descrição|
| - | - |
|Passo 1|A plataforma exibe na tela principal, toda a informação para que o usuário veja sobre as políticas e dados de privacidade.|
|Passo 2|O usuário pode escolher voltar para a tela anterior através ou dar continuidade no processo.|



###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1|Todos os dados sobre as politicas e termos de privacidade saão exibidos.|


###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|Concordo|Sim|Não|Texto|
|Não Concordo|Não|Não|Texto|



###  Opções de usuário

|Opção|Descrição|
| - | - |
|Concordo|Aceita os termos de politica e privacidade.|
|Não Concordo|Não aceita os termos de politicas e privacidade.|


###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder ter acesso aos termo de politica e privacidade, para ter ciência dos dados que fornecerei para a plataforma e os riscos de exibir essas informações.| As políticas de privacidade devem ser exibidas corretamente e de forma clara para o usuário e devem ser atualizadas para a jurisdição do usuário.|

## RF08 - Transmitir Tela Ao Vivo

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


##  RF10 - Salvar Transmissão

###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Salvar Transmissão|
|Resumo|O usuário vai ter a opção de salvar a transmissão apos encerrado|
|Ator principal|Dono da transmissão|
|Ator secundário|Não possui|
|Pré-condição|Somente após encerrado a transmissão|
|Pós-condição|Não possui|

###  Fluxo principal

|Passos|Descrição|
| -- | - |
|Passo 1| O usuário acessa o página com as transmissões |
|Passo 2| O usuário seleciona a transmissão |
|Passo 3| O usuário clica no botão de salvar transmissão |

###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1| Usuário finaliza transmissão |
|Passo 2| Usuário clica no botão de salvar transmissão |

###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|||||

###  Opções de usuário

|Opção|Descrição|
| - | - |
|Salvar transmissão|Define/Altera um filtro para data|

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder salvar minhas transmissões em meu dispositivo. Isso me permite editar e compartilhar em outras plataformas.| O usuário tem acesso às transmissões passadas e pode salvá-las. |

## RF11 - Seguir Usuário

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


##  RF12 - Filtrar Conteúdo

###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Filtrar Conteúdo|
|Resumo|Opções de filtro de conteúdo para a função de busca|
|Ator principal|Usuário cadastrado ou não |
|Ator secundário| Não possui |
|Pré-condição| Não possui |
|Pós-condição| O conteúdo exibido na busca está atualizado seguindo o filtro de conteúdo |

###  Fluxo principal

|Passos|Descrição|
| -- | - |
|Passo 1| O usuário acessa o campo de busca e realiza uma pesquisa|
|Passo 2| O resultados da busca são exibidos|
|Passo 3| O usuário seleciona os devidos filtros para o conteúdo buscado |
|Passo 4| O resultados da busca são recarregados seguindo a condição estabelecida no filtro de conteúdo|
|Passo 5| Em caso de sucesso, o usuário poderá ver os conteúdos dentro de um determinado perfil de conteúdo |

###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1|Se o usuário selecionar um filtro para o qual não existem conteúdos cadastrados, uma mensagem de "Não existem conteúdos em 'nome da categoria' " deverá em exibida.|
|Passo 2|Se o usuário acreditar que um conteúdos está listado na categoria errada, ele poderá sugerir a alteração de categoria para esse conteúdo em específico. |

###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|Filtro por Data|Não|Sim|List select|
|Filtro por Categoria|Não|Sim|List select|
|Filtro por Idioma|Não|Sim|List select|
|Filtro por Duração|Não|Sim|List select|

###  Opções de usuário

|Opção|Descrição|
| - | - |
|Filtro por Data|Define/Altera um filtro para data|
|Filtro por Categoria|Define/Altera um filtro por categoria|
|Filtro por Idioma|Define/Altera um filtro por idioma|
|Filtro por Duração|Define/Altera um filtro por duração|
|Salvar|Ao clicar, os critérios de busca são atualizados e uma nova busca é realizada. |

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder escolher filtros para os conteúdos que eu buscar dentro da plataforma. Isso me permite ter uma experiência personalizada e facilitada na busca por conteúdos quem me agradem.| O usuário tem acesso a todos os filtros de busca e eles são aplicáveis para toda busca realizada, gerando um resultado ou mensagem padrão do sistema.|


## **RF13 - Banir Usuário Do Chat**

#### Autor: @afonsodglan - Afonso Dglan Cirqueira Rodrigues.

---

### Revisor: @emanuelcatao - Emanuel Catão Montenegro

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
| User Story| Critério de aceitação| 
|---------- | -------------------- |
| Eu enquanto "usuário admistrador" quero "poder bloquear contas de usuário que violaram as regras da plataforma por meio de mensagens ofensivas." para "ter mais segurança e uma experiências mais completa".| Certifique-se que o usuário é capaz de **Bloquear usuário do chat.** |

![RF](https://raw.githubusercontent.com/AfonsoDglan/imagens/main/banir.png)

Prototipo

## RF14 - Compartilhar Perfil da Plataforma

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Compartilhar Transmissão Ao Vivo da Plataforma|
|Resumo|Botão em que ao clicar, o usuário da plataforma consegue compartilhar uma transmissão ao vivo da plataforma para outras pessoas, por meio de um link.|
|Ator principal|Usuário cadastrado ou não|
|Ator secundário|Não possui|
|Pré-condição|Não possui|
|Pós-condição|Não possui|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Entrar na transmissão ao vivo da plataforma que deseja compartilhar|
|Passo 2|Clicar no botão de compartilhar|
|Passo 3|Escolher entre as opões de compartilhamento|
|Passo 4|Completar segundo a plaforma em que ele irá compartilhar ou enviar o link copiado na área de transferência|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Se o usuário desistir de compartilhar, basta clicar fora da caixa de opções disponíveis para fechar|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Copiar URL|Não|Não|Botão|
|Twitter|Não|Não|Botão|
|Facebook|Não|Não|Botão|


### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Copiar URL|Copia a URL da transmissão para a área de transferência do usuário|
|Twitter|Abre a plataforma Twitter com um 'tweet' pré-montado para o usuário postar contendo o título da tramissão e a URL para a transmissão|
|Facebook|Abra a plataforma Facebook com uma publicação pré-montada para o usuário postar contendo a URL da transmissão|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como usuário eu quero poder compartilhar uma transmissão ao vivo da plataforma para divulgar/convidar outras pessoas a assistirem a transmissão ao vivo.|A transmissão estar ao vivo dentro da plataforma, assim podendo compartilhar a mesma para outras pessoas, em suas redes sociais.|

## RF15 - Vincular Conta de Usuário a Outros Serviços

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

## RF16 - Buscar Termo na Plataforma
#### Autor: @HeloCris - Helorrayne Cristine

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Buscar Termo na Plataforma|
|Resumo|Permite ao usuário final cadastrado buscar por um termo na plataforma e visualizar os resultados da busca na tela.|
|Ator principal|Usuário final cadastrado|
|Ator secundário|Sistema de busca da plataforma|
|Pré-condição| O usuário deve estar logado na plataforma.|
|Pós-condição|O usuário visualiza os resultados da busca na tela. |

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário abre o aplicativo, e na tela inicial entra com a conta caso já possua ou cria uma nova.
Passo 2|É exibido a tela inicial.
Passo 3|O usuário clica na barra de busca.
Passo 4|O usuário digita o termo que deseja buscar.
Passo 5|O sistema de busca da plataforma recebe o termo digitado pelo usuário.
Passo 6|O sistema de busca da plataforma realiza uma busca nos dados da plataforma que correspondem ao termo buscado.
Passo 7|O sistema de busca da plataforma retorna os resultados da busca para o usuário.
Passo 8|O usuário visualiza os resultados da busca na tela.


### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Caso não haja dados na plataforma correspondentes ao termo buscado, o sistema de busca retorna uma mensagem de que não foram encontrados resultados para a busca. |

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Login | Sim | Sim | E-mail e senha
Home| Sim | Sim| Botão
Buscar| Sim| Sim|Botão |

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Login|O usuário precisa estar logado
Home|O usuário clica no ícone home
Buscar|O usuário clica no ícone de pesquisa|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usuário da plataforma, eu gostaria de poder buscar por termos na plataforma para encontrar informações relevantes de maneira rápida e fácil. Eu quero ser capaz de digitar o termo que desejo buscar na barra de busca e visualizar os resultados da busca na tela. Se não houver dados correspondentes ao termo que busco, eu quero receber uma mensagem informando que não foram encontrados resultados para minha busca.|1-A barra de busca deve estar visível e facilmente acessível para o usuário. 2-O sistema de busca deve ser capaz de buscar por termos em todos os dados relevantes da plataforma. 3-Os resultados da busca devem ser apresentados de forma clara e organizada para o usuário. 4-O sistema de busca deve retornar resultados relevantes e precisos para os termos buscados. 5- Se não houver dados correspondentes ao termo buscado, o sistema de busca deve retornar uma mensagem clara informando que não foram encontrados resultados para a busca. 6-A busca deve ser realizada de forma eficiente e rápida, sem causar atrasos ou interrupções no uso da plataforma pelo usuário.|


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

## RF18 - Sortear brindes especiais ao Assistir Transmissões Ao Vivo

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso| Receber brindes ao assistir|
|Resumo| Usuários recebem brindes aleatoriamente conforme assistem uma transmissão especial ao vivo|
|Ator principal| Usuário logado|
|Ator secundário| Usuário transmitindo|
|Pré-condição|O usuário deve estar logado em sua conta e estar assistindo uma transmissão ao vivo marcada como especial|
|Pós-condição|O usuário, se for sorteado, podera receber brindes em jogos, outros sites e etc|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário logado acessa uma transmissão ao vivo marcada como especial|
|Passo 2|Conforme a transmissão selecionada estiver sendo reproduzida, não silenciada e não minimizada o usuário tem a possibilidade de ser sorteado|
|Passo 3|O usuário que está transmitindo ou alguém com permissões realiza um sorteio entre os telespectadores válidos e o sistema escolhe o do usuário premiado|
|Passo 4|Posteriormente o usuário resgatará esse brinde em seu jogo, site ou outro que está conectado em sua conta na plataforma|




### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|Se o usuário não estiver logado ou estiver com alguma restrição, será alertado que não está elegível para participar do sorteio|
|Passo 2|Se o usuário não estiver logado, ele poderá efetuar login. Se for algum problema no sistema, ele poderá entrar em contato com a equipe de suporte ao cliente para obter ajuda|


### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Nenhum|Não|Não|Nenhum|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Receber Brindes|O usuário recebe brindes em jogo, site ou outro|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Eu como usuário quero assistir uma transmissão ao vivo e poder ser sorteado para ganhar prêmios ou benefícios na plataforma ou outras, como jogos, sites, entre outros|
Todos os brindes devem ser entregues corretamente ao usuário sorteado durante a transmissão especial|

## RF19 - Denunciar Transmissão

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Denunciar Transmissão|
|Resumo|Este caso de uso permite que os usuários denunciem transmissões de streaming que contenham conteúdo inapropriado, ofensivo ou ilegal. |
|Ator principal|Usuário|
|Ator secundário|Moderador|
|Pré-condição|O usuário está assistindo a uma transmissão de na plataforma.|
|Pós-condição|A denúncia terá sido analisada e as devidas ações tomadas.|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário assiste a uma transmissão de streaming na plataforma.|
|Passo 2|O usuário encontra conteúdo inapropriado, ofensivo ou ilegal na transmissão.|
|Passo 3|O usuário clica no botão "Denunciar" na página da transmissão.|
|Passo 4|A plataforma exibe uma janela de confirmação para o usuário.|
|Passo 5|O usuário confirma a denúncia.|
|Passo 6|A plataforma envia a denúncia para os moderadores.|
|Passo 7|Os moderadores analisam a denúncia e tomam medidas apropriadas para remover a transmissão e punir o streamer, se necessário.|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 4a|O usuário confirma a denúncia e o processo segue normalmente.|
|Passo 4b|O usuário pode decidir cancelar a denúncia na janela de confirmação, a denúncia não é enviada para os moderadores, a transmissão continua normalmente.|
|Passo 7a|A denúncia é avaliada e considerada válida pelos moderadores, eles podem decidem qual ação tomar contra o streamer, como uma suspensão, advertência ou banimento permanente.|
|Passo 7b|A denúncia é avaliada e considerada inválida pelos moderadores, a transmissão continua normalmente.|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|Tipo da Denúncia|Sim|Sim|Texto|
|Descrição detalhada da denúncia|Não|Sim|Texto|
|Momento da violação|Não|Sim|Texto|

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Denunciar?|Abre a janela para denúncia.|
|Selecionar o Tipo da Denúncia|Seleciona um tipo específico de infração cometida na transmissão.|
|Confirmar Denúncia|Ao clicar, as informações são enviadas aos moderadores.|
|Cancelar Denúncia|Ao clicar, as informações são excluídas.|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como um usuário da plataforma de streaming, quero ter a opção de denunciar transmissões que violem as políticas da plataforma, para que os moderadores possam tomar as medidas apropriadas e manter a comunidade segura e saudável.|O formulário de denúncia deve ser facilmente acessível e visível na plataforma de streaming, o formulário deve incluir campos claros e relevantes para o tipo de denúncia que o usuário deseja fazer, a plataforma deve levar as denúncias a sério e tomar medidas apropriadas em tempo hábil, caso sejam confirmadas violações das políticas, a plataforma de streaming deve monitorar e avaliar continuamente as denúncias para garantir que as políticas sejam atualizadas e eficazes na proteção da comunidade.|


## RF20 - Bloquear Usuário
###  Atributos

|Item|Descrição|
| -- | - |
|Caso de Uso|Bloquear Usuário|
|Resumo|Permite que um usuário bloqueie o perfil de outro usuário|
|Ator principal|Usuário final cadastrado|
|Ator secundário|Usuário cujo perfil será bloqueado|
|Pré-condição|O usuário deve ser cadastrado, ter o aplicativo instalado e estar logado na sua conta|
|Pós-condição|O perfil do usuário bloqueado não estará mais visível para o usuário que realizou o bloqueio|

###  Fluxo principal

|Passos|Descrição|
| --   | - |
|Passo 1|O usuário acessa o perfil do usuário que deseja bloquear.|
|Passo 2|O usuário clica no botão "Bloquear".|
|Passo 3|O sistema exibe uma mensagem de confirmação perguntando se o usuário realmente deseja bloquear o perfil.|
|Passo 4|O usuário confirma a ação.|
|Passo 5|O sistema realiza o bloqueio do perfil do usuário e exibe uma mensagem de confirmação.|
|Passo 6|O Sistema redireciona para a "Home".|



###  Fluxo alternativo

|Passos|Descrição|
| -- | - |
|Passo 1|No Passo 4, se o usuário cancelar a ação de bloqueio, o fluxo retorna para o Passo 1.|
|Passo 2|No Passo 5, se ocorrer algum erro durante a atualização da lista de usuários bloqueados, o aplicativo exibe uma mensagem de erro e o fluxo retorna para o Passo 1.|

###  Campos

|Campo|Obrigatório|Editável|Formato|
| - | - | -- | - |
|Usuário|Sim|Não|Botão|
|Bloquear|Sim|Não|Botão|
|Confirmar|Sim|Não|Botão|
|Cancelar|Sim|Não|Botão|



###  Opções de usuário

|Opção|Descrição|
| - | - |
|Bloquear|Permite bloquear o perfil de outro usuário.|
|Confirmar|Confirma a ação de bloqueio.|
|Cancelar|Cancela a ação de bloqueio.|

###  User Story

|User Story|Critério de Avaliação|
| -- | --- |
|Como um usuário, eu quero poder bloquear o perfil de outro usuário para não visualizar suas publicações, a fim de melhorar minha experiência na plataforma.|Certificar que o perfil do usuário bloqueado não está mais visível para o usuário que realizou o bloqueio.|



## **RF21 - Definir qualidade do vídeo**

#### Autor: @afonsodglan - Afonso Dglan Cirqueira Rodrigues.

---

### Revisor:
| Item | Descrição |
| ---  | --- |
| Caso de Uso | Definir qualidade do vídeo |
| Resumo          | Uma funcionalidade que pode ser ultilizada pelos usuários da live, possibilitando definir uma qualidade de vídeo maior ou menor. |
| Ator principal  | Usuário.|
| Ator secundário | |
| Pré-condição    | Estar assistindo uma live.|
| Pós-condição    | Não há.|

#### Fluxo principal

| Passos  | Descrição                                                          |
| ------- | ------------------------------------------------------------------ |
| Passo 1 | Clicar no botão de configurações de vídeo                          |
| Passo 2 | Clicar no botão de qualidade                                       |
| Passo 3 | Selecionar a opção da qualidade do vídeo                           |

#### Campos

| Campo                 | Obrigatório | Editável | Formato |
| --------------------- | ----------- | -------- | ------- |
| Configurações de vídeo| Sim         | Não      | Botão   |
| Qualidade             | Sim         | Não      | Botão   |
| Qualidades disponíveis| Não         | Sim      | Botão   |


#### Opções de usuário

| Opção                                | Descrição                                                                                                                                 | Atalho |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------| ------ |
| Alterar a qualidade de vídeo da live | Ao clicar no botão de configuração de vídeo terá a opção de qualidade de vídeo onde o usuário pode alterar a qualidade que deseja assistir|        |

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

| User Story | Critério de aceitação |
| ---------- | --------------------- |
| Enquanto "usuário" preciso ter controle sobre a quantidade de consumo da banda de internet que está sendo consumida para assistir a live ou para assistir a live com uma alta definição | Certifique-se que o usuário é capaz de **Definir a qualidade do vídeo da live.**|



![RF](https://raw.githubusercontent.com/AfonsoDglan/imagens/main/qualidade.png)
## RF22 - Ativar notificações de usuário que segue

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso|Função que permite ativar notificações da atividade de algum usuário que segue|
|Resumo|Usuário ativa a função e então passa a receber notificações|
|Ator principal|Usuário logado|
|Ator secundário||
|Pré-condição|O usuário deve estar logado em sua conta para ser capaz de ativar a notificação da atividade de algum usuário e além disso deve também já estar seguindo o usuário em questão|
|Pós-condição|O usuário acompanhará as atividades do(s) usuário(s) que segue por meio de notificações|

### Fluxo principal

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário verá no perfil de um usuário X que segue a função de notificações desativada através dum ícone de botão|
|Passo 2|Ao clicar no botão, o usuário imediatamente estará acompanhando as atividades do usuário X através de notificações|

### Fluxo alternativo

|Passos|Descrição|
|  --  |    -    |
|Passo 1|O usuário verá no perfil de um usuário X que segue a função de notificações ativada através dum ícone de botão|
|Passo 2|Ao clicar no botão, o usuário imediatamente deixará de acompanhar as atividades do usuário X através de notificações|

### Campos

|Campo|Obrigatório|Editável|Formato|
|  -  |     -     |   --   |   -   |
|||||

### Opções de usuário

|Opção|Descrição|
|  -  |    -    |
|Ativar notificações de usuário X|Desativar notificações de usuário X|

### User Story

|User Story|Critério de Avaliação|
|    --    |         ---         |
|Como usuário, quero poder ser capaz de ser notificado sobre as atividades dos usuários que sigo na plataforma de streaming. Assim como, também, desejo ser capaz de desativar as notificações no momento em que eu quiser|O usuário pode ativar e desativar as notificações de um usuário que segue no momento em que quiser|

