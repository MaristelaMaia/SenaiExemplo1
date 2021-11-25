Entrar no Git  https://git-scm.com/
E fazer o Download
Instala / executa = Muda para Main = next em demais autorizações. Até instalar oficialmente.
Finaliza.

Vai na área de trabalho e cria uma pasta = Exemplo1= com o botão direito clica em git Bash, abrirá uma tela, dê o comando Git Init
Tem que abrir uma pasta (Vai em Exibir – clica em Itens Ocultos e Extensões de nomes de arquivos)
A pasta ficará clara, pois ela estava oculta. Clica no campo da tela, novo, documento de texto (arquivo .txt) – 

# SenaiExemplo1
Exemplo 1 Senai
ajuste2


$ git commit -m "teste.txt"
Author identity unknown
*** Please tell me who you are.
Run
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
to set your account's default identity.
Omit --global to set the identity only in this repository.
fatal: unable to auto-detect email address (got 'Supervisor@DESKTOP-V5Q5C76.(none)')
 
Daí eu dei o comando do git log:
$ git log
fatal: your current branch 'main' does not have any commits yet

Conta no GitHub. Ok!
Git add .     Ok! 
Git commit -m "Alteracao"     ok! 
Git log   OK!

Supervisor@DESKTOP-V5Q5C76 MINGW64 /d/Meus Documentos/Desktop/Exemplo1 (main)
$ git log
commit aee3b236e755fd0305c57fe1026c6cd1513dd3ad (HEAD -> main)
Author: MaristelaMaia <estagiomaris@gmail.com>
Date: Tue Nov 23 01:17:03 2021 -0300
Alteracao
Supervisor@DESKTOP-V5Q5C76 MINGW64 /d/Meus Documentos/Desktop/Exemplo1 (main)
$
