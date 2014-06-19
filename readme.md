Code.Education
===============================================================
Módulo 01 - Git e Github
---------------------------------------------------------------

Este é um repositório de testes, utilizado para aprendizado do Git e GitHub, no curso da Code.Education
Logo abaixo seguem comandos utilizados para chegar até aqui:

###Primeira parte - Primeiros Passos
1.Através do comando *git init*, iniciei um novo repositório no diretório atual
2.Criado os arquivos *arquivo01.php* e *readme.md* utilizando o comando *vim* do terminal
3.Logo após, utilizando o comando *git add .*, passei ambos os arquivos de untracked para read to commit
4.Comitei estas inclusões utilizando o comando *git commit -a* que me permitiu colocar a mensagem do commit logo após de maneira mais tranquila

###Segunda parte - Commitando e Readme.md
1. Realizei alterações no arquivo readme.md e chequei pelo comando *git status* que o mesmo está alterado
2. Commit de alterações realizadas no arquivo readme.md

###Terceira parte - .Gitignore e Voltando Versões
1. Adicionando e comitando .gitignore - comandos: *git add*, *git commit -m*
2. Testando também os comandos *git log*, *git log -p*, *git log --pretty=oneline*
3. Testando retorno a versões anteriores - comandos: *git reset HEAD~1 --soft* e *git checkout hash_da_versão;

###Quarta parte - Branchs
1. Criando novos branchs - comando: *git checkout -b nome_do_branch*
2. Brincando com comandos *git branch*, *git checkout nome_do_branch*, *git log*, *git commit*
3. Unificando branchs com *git merge* - necessariamente gerando um commit do merge
4. Unificando branchs com *git rebase* - não gera

###Quinta parte - GitHub
1. Criado o Repositório mod01-git no GitHub
2. Inserindo o caminho do repositório remoto utilizando *git remote add origin https://github.com/pcfordelone/mod01-git.git*
3. Dando o primeiro push nos arquivos utilizando *git push origin master*;
4. Testei também os comandos *git clone* *git pull*;
