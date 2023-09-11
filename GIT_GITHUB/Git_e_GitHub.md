<h1>Git e Github<h1>

<h3>Começaremos pela configuração</h3>

~~~
$ git config --list
~~~

<p>Configurando seu nome de usuário e e-mail (globalmente):</p>

~~~
$ git config --global user.name "Nome Sobrenome"
$ git config --global user.email seuemail@email.com
~~~

<p>Configurando o nome da Branch Padrão:<p>

~~~
$ git config --global init.defaultBranch main
~~~

<h3>Criando e Clonando Repositórios</h3>

<h4>Criando um Repositório Local</h4>

<p>Acesse a pasta que deseja transformar em um repositório Git pelo terminal ou clique no atalho em “Git Bash Here”:</p>

1. Inicialize um repositório Git no diretório escolhido:

~~~
$ git init
~~~

2. Conecte o repositório local com o repositório remoto:

~~~
$ git remote add origin https://github.com/username/nome-do-repositorio.git
~~~
