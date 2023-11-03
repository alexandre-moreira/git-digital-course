# Git e Versionamento | Git diff e commit | Aula 05

## Estados do Git
    [] Untracked  - 
    [] UnModified - Arquivo salvo, já commitado.
    [] Modified   - Arquivo que sobre modificação
    [] Stage      - Area de preparação de commit.

## Comandos Git
    - git status -> mostra o estado atual do seu repositório e se há modificações a serem salvas.
    - git add ./readme.md -> salvar as modifições realizadas em um unico documento.
    - git add . -> salvar as modifições realizadas em todos os documentos modificados de uma só vez.

## Novos comandos
    - git diff -> Mostra onde foram feitas as modificações e o que foi alterado.
    - git diff --staged -> Mostra onde foram feitas as modificações e o que foi alterado no estado.
    - git commit -m "descrever o que foi feito" -> Salvar o estado, fazendo o snapshot do sistema.