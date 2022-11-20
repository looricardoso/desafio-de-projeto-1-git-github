
# Introdução

Esta página foi criada seguindo a documentação no site oficial do Markdown [disponível aqui](https://www.markdownguide.org/).

Este foi meu primeiro contato com Markdown, e a sintaxe disponível no site é bem didática, de forma que se torna possível criar uma página estática em instantes.

Como editor de códigos, utilizei o VS Code juntamente com uma extensão para facilitar a edição em Markdown, o que também facilitou o aprendizado.


## Sobre o Git Bash

O Git Bash é uma interface CLI (Command Line Interface) que emula um terminal Linux e torna possível a integração com o Git / GitHub.

Para fazer o download do Git [acesse este link](https://git-scm.com/downloads).


## Comandos para utilização no Git Bash

 - git init
     - Este comando inicializa seu repositório localmente, possibilitando o versionamento dos arquitos e códigos presentes no repositório criado.

 - git status
     - Este comando verifica o estado dos arquivos presentes no seu repositório, indicando quais arquivos estão ou não adicionados e preparados para um commit.

 - git add \<nomeDoArquivo>
     - Este comando permite adicionar/preparar um único arquivo do repositório para um commit, indicando o nome do arquivo.

 - git add .
     - Este comando é muito similar ao comando anterior, sua principal diferença é que todos os arquivos que possuem alterações serão preparadados para um commit.

 - git commit -m "descricao do commit"
     - Este comando de fato versiona seu código após as alterações, com este código o Git cria um registro das alterações e as salva, possibilitando o envio para um repositório remoto.

 - git remote add origin urlDoRepositorio
     - Este comando "linka" o repositório remoto criado préviamente no GitHub com seu repositório local, possibilitando sincronizar seu repositório local com o remoto. Deve-se indicar a URL do repositório substituindo a **urlDoRepositorio** pelo link disponibilizado pelo GitHub.

 - git push origin master
     - Comando utilizado para enviar seu repositório recém atualizado para o repositório remoto.


## Importância do versionamento

O versionamento de código se torna muito importante para o desenvolvedor e para o time, visto que com o versionamento, haverá um maior controle sobre as alterações no código e também, juntamente com as facilidade que o GitHub proporciona, podem facilitar o compartilhamento de código, bem como facilitar o desenvolvimento através de um ambiente mais colaborativo.


# Conclusão

Estes foram apenas alguns pontos de destaque sobre o Git e GitHub, para aprender mais recomendo que acessem o site da [DIO](https://www.dio.me/), onde podem conhecer, aprender e explorar um pouco mais sobre o mundo da tecnologia e participar dos cursos e Bootcamps.

Até mais !!! ✌