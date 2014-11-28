#Aprendendo a usar o github

**Inicio Usando o markdown**
*Primeiro dia 27/11/2014 corujão*

*Entao os passos são:*

Repositorio no GIT

Stag Area

Pasta PC


em alguma pasta do pc vc da o comando 

   git init

Inicializa o repositório na pasta local

ai então você vincula esta pasta local ao repositório do GITHUB, copiando o link http://github.user/repositorio.git

e dando o seguinte comando localmente:

    git add origin master http://repositorioqvcquertrazer.git

**OBS:isto funciona se o repositório for seu, se for de outra pessoa, vc deve dar um fork antes para trazer para o seu repositório e copiar o endereço do repositório forkado e fazer um branch**

conforme for dazendo alterações localmente vc vai adicionando as alterações ao *Stag Area* quando terminar de um commit para comentar as alterações feitas e finalizar a entrega com o comando:

    git commit -m "Seu comentário das alterações"

e apos estar concluido hora de enviar para o repositório remoto no GITHUB com o comando:

    git push -u origin master

**OSB: isso considerando você sendo o dono do repositório, porque se não for o dono, vc solicita um Pull Request. O dono do repositório achando interessante as alterações que você fez vai aceitar e fazer um merge para consolidar suas alterações ao código principal.**




