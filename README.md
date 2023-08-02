# Exemplos de oprerações básicas para git via CLI ()

## Comando de uso geral CLI

-Criar pasta: mkdir nomepasta
-Lista conteúdo: dir
-Limpar tela: cls
-Entar na pasta: cd nomepasta

## Comandos princispais do git 

`git config user .nome` e `git config user.email`

Verificar usuário/email

`git config --global user.nome "seu nome como quiser"` e `git config --global user.email "seuemail@provedor.com"`

Mudar usuário e e-mail de forma global.

**Obs:**normalmente estes dados estão relacionados ao usuário/conta do site GitHub

`git init`

Inicializar um repositório (Executado dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`

Renomear branches

Para alterar a branch de **master** para **main** (novo padrão),usaríamos: `git branch master main`

`git status`

Verificar o status atual do repositório

`git add nomearquivo` ou `git add`

Adocionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit - m "texto da mensagem sobre esta alteração"`

fazer commit das alterações (salvar no histórico).

`git remote add origin endereço-do-repositório.git`

Adicionar/conectar o repositório remoto ao local. 





