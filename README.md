# Revisando Conceitos de Git/GitHub

Repositório criado com intuito de revisar os conceitos de Git/GitHub para o primeiro desafio de projeto do Bootcamp Spreed Java Developer disponível na plataforma da Digital Innovation One - DIO.


## Comandos Básicos Git

- Comando utilizado para iniciar o versionamento de um repositório local com o git.

  $ git init

- Comando utilizado para clonar um repositório remoto.

  $ git clone <caminho-repositório>

- Comando utilizado para adicionar todas as mudanças realizadas nos arquivos do repositório local.

  $ git add .

 - Comando utilizado para verificar qual estágio dos arquivos do repositório local ( adicionado, comitado, etc. ).
 
    $ git status

- Comando utilizado para confirmar as alterações realizadas no repositório local.

  $ git commit -m "descreva as alterações"

- Comando utilizado para se conectar o repositório local com um repositório remoto, caso você não tenha feito o clone de um.

  $ git remote add origin <caminho-repositório>

- Comando utilizado para enviar as alterações realizadas no repositório local para o repositório remoto. 

  $ git push -u origin master
  
- Comando utilizado para atualizar o repositório local com a versão mais atualizada do repositório remoto.

  $ git pull
