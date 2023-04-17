# Relatório de Requisitos

## 1. Introdução

Relatório que deve ser entregue até dia 26/04/2023. Todo mundo deve seguir o mesmo padrão e contribuir. É recomendável que cada um faça 2 ou 3 features. Quando pensar num recurso, eu sugiro mandar no grupo, assim não temos 2 pessoas fazendo a mesma coisa.

Como todos vamos mexer no mesmo arquivo, faça sua parte [aqui](https://stackedit.io/app), num editor online. Antes de editar o arquivo com suas modificações prontas, avise no grupo que está editando, para evitar conflitos. Também avise quando terminar e fizer o commit, assim eu faço o merge e os outros vão poder continuar.

Por controle, jamais façam merge nas branches `main` e `develop`. Tudo deve ser feito através de pull requests.

## 2. Instruções

### 2.1. Instalação

Esta seção assume que você tem o vscode, git e git flow instalados e configurados. Se me lembro, o git do Windows o inclui, mas no linux você precisa instalar, a depender da distribuição. De qualquer forma, abram o terminal e digitem `git flow` para ver se está tudo certo.

### 2.2 Primeiros passos

1. Faça fork deste repositório
2. No vscode, pressione `Ctrl+Shift+P` para abrir o menu de comandos
3. Digite `git clone` e aperte enter
4. Clone o seu fork e abra
5. No canto inferior esquerdo, onde deve estar escrito `main`, clique e selecione `develop`. Lembre-se de fazer pull

### 2.3. Adicionando feature

1. Sempre faça pull antes de começar. Certifique-se de ser o único editando o arquivo
2. Abra o terminal (`Ctrl+'`) e digite `git flow feature start <nome>`, onde `<nome>` é o nome da feature
3. Ao fim de `relatorio.md`, adicione seus recursos. O modelo de cada um pode ser encontrado [aqui](https://github.com/wchar-t/relatorio-es-2023-01/blob/develop/formato.md)
4. Lembre-se de se incluir em Requisitos, no início do relatório, no formato
5. Faça commit e push
6. Execute `git flow feature finish <nome>`
7. Caso o merge não tenha sido automático (veja o terminal), faça na sua develop
8. Faça pull request [aqui](https://github.com/wchar-t/relatorio-es-2023-01/compare) da sua develop para a develop do repositório original

- Sempre que reservar o repositório para uso e terminar e enviar, envie mensagem no grupo ;)