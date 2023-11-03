# Git e Versionamento | Git branch | Aula 09

## Braches
 [] Master
    [] commit 2
    [] commit 1
    [] commit 0

## Criar uma nova branch
 - git branch testing

## Verificar em qual branch você está.
 - git log --oneline --decorate -> Para saber qual branch está selecionada, basta ver pra onde Head está apontando.

 Ex: 07cec55 (HEAD -> main, origin/main, testing) feat: aula08
     Observe que a HEAD, está apontando para main.

## Trocar de branch
 - git checkout testing
 - git log --oneline --decorate

 Ex: 07cec55 (HEAD -> testing, origin/main, main) feat: aula08
    Observe que agora o HEAD, está apontando para testing.

## Criar um arquivo na nova branch
    - criar o arquivo .gitignore
    - git add .
    - git commit -m "feat: add .gitignore file"

## Voltando para a branch principal, que pode ser master  ou main.
    - git checkout main
    - Verifique que o arquivo .gitignore, não se encontra na brach atual.
    - Criar um arquivo chamado Todo.md
    - Adicionar o seguinte texto no Todo.md:  - [] Dar merge no código.
    - Salve o documento com ctrl + s.
    - git add .
    - git commit  -m "feat: add TodoList file"

