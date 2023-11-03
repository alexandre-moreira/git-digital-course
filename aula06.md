# Git e Versionamento | Git log e restore | Aula 06

## Git log
 - git log - trás o histórico dos ultimos commits que foram feitos, mostrando o hash do commit, credencias do autor e data.

 Ex:
    commit f9f70828c609293fe7b446276d45c131cf1fb7a4
    Author: Alexandre Moreira <4lexandre.moreira@gmail.com>
    Date:   Fri Nov 3 09:58:06 2023 -0300
    Msg:    docs: update new title

    commit 5cd87397eaaa58579f0b804943f8f1e753be0efe
    Author: Alexandre Moreira <4lexandre.moreira@gmail.com>
    Date:   Fri Nov 3 09:53:36 2023 -0300
    Msg:    docs: created readme

## Git Restore
 - git restore ./Readme.md  -> Desfaz a modificacoes em documento salvo em Changes/
 - git restore --staged ./Readme.md  -> Desfaz a modificacoes em documento salvo em Staged, voltando para Changes.