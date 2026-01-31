Inicializar um repositório git:
$ git init

Visualizar os arquivos que foram modificados:
$ git status

Visualizar as modifições realizadas:
$ git diff [--name-only]

Visualizar lista dos commits já realizados:
$ git log [--stat] [--graph] [--author="Autor"] [--decorate]

Visualizar árvore de branchs e commits:
$ git log --graph --pretty=oneline --abbrev-commit

Visualizar log resumido dos commits, mostrando quantidade de commits e quais foram os commits:
$ git shortlog [-sn]

Visualizar detalhes de um commit:
$ git show hash_do_commit

Adicionar todos os arquivos modificados para serem enviados no commit:
$ git add .

Realizar commit com descrição do que foi modificado:
$ git commit -m "Descrição das modificações"

Realizar commit já adicionando todos os arquivos modificados, que já tenham sido adicionados alguma vez, e enviando a mensagem:
$ git commit -am "Descrição das modificações"

Adicionar um repositório remoto:
$ git remote add origin https://github.com/davidalves1/gerador-cnpj.git

Visualizar branchs locais e remotos:
git branch [--list] [-a]

Enviar as modificações commitadas:
$ git push origin master

Criar tags para versionamento:
$ git tag -a 1.0.0 -m "Descrição sobre a versão"
$ git push origin master --tags

Criar um branch e mudar para ele ao mesmo tempo:
$ git checkout -b nome_do_branch

Enviar o branch para o repositório remoto
$ git push origin nome-do-branch