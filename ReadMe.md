
Olá esse projeto te ensina a usar o git

São comandos basicos para enterder sua "arvore de codigo" suas "ramificaçoes" e como versionar e gerenciar o seu codigo com git.

----------------------------------------------------------

Comandos para usar do git - configurações iniciais

Abra o git bash

Caso vc tenha baixado o Git pela primeira vez e não tenha configurado ele ainda, será necessário configura-lo.

git config --global user.name " seu nome" (Adiciona o seu nome no git bash)

git config --global user.email "email usado por vc no Github" (adiciona o seu email ao git O MESMO EMAIL USADO NA CRIAÇÃO DO SEU GITHUB)

------------------------------------------------------------
Configuração da chave SSH

caso vc não tenha uma chave ssh configurada será necessario rodar o comando e instalar a chave ssh no seu pc e depois adicionar a chave publica nas configurações do seu github pessoal

ssh-keygen -t rsa -b 4096 -C " seu _email@example.com" (comando para instalar a chave) 

ssh-keygen -t rsa -b 4096 -C "seu_email@example.com" (comando alternativo para instalar a chave ssh, caso a primeira não funcione)

depois de instalada abra a chave publica com o notepad ou outro leitor copie e adicione ela no seu github em configurações.

------------------------------------------------------------

Comandos comuns do git

git init (dentro da pasta a ser compartilhada para iniciar o git)

git add "nome do arquivo" (para mandar o arquivo para aréa de stade)

git status (verificar o status)

git branch -M "main"  (trocar o nome da 'ramificação atual')

git remote add origin https:// seu github/o nome do projeto (usado para conectar o git local com o github)

git remote show origin (comandos para verificar se a conecção remote deu certo)

git push -u origin main (empura as suas alteraçoes locais para o github)


Segundo commit 

git add . (caso vc queira que todos os arquivos sejam alterados) 

git status (para verificar)

git commit -m "nome do novo commit"

git push origin main 


Criação de Branchs

git checkout -b "nome da nova branch" (o comando cria e muda o usuário de lugar para a nova branch criada - é possivel ver no gitbash o caminho onde vc esta e em qual branch está fazendo alterações)

alteraçoes não principais....

git checkout 'nome da branch' (para alterar entre branch)

git add . (stade - em espera)

git status (verificar)

git push origin 'nome da branch que vc deseja alterar - vc de ve estar na main a ser alterada tb'


