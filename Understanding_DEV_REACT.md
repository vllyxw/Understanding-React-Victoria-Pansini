<h1> Entendendo as Disciplinas Técnicas de React do Entra21 </h1>

<p>Aqui estarão listados todos os conteúdos juntos, quaso queira consultar os conteúdos separados, estará separado por pastas neste mesmo diretório</p>

<h2> Git e Github </h2>

<h3>Começaremos pela configuração</h3>

~~~
$ git config --list
~~~

<p>Configurando seu nome de usuário e e-mail (globalmente):</p>

~~~
$ git config --global user.name "Nome Sobrenome"
$ git config --global user.email seuemail@email.com
~~~

<p>Verificar se o usuário e o e-mail foram cadastrados:</p>

~~~
$ git config user.name
$ git config user.email
~~~


<p>Configurando o nome da Branch Padrão:</p>

~~~
$ git config --global init.defaultBranch main
~~~

<p>Verificar status:</p>

~~~
$ git status 
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

<h3>Desfazendo Alterações no Repositório Local</h3>

<p>Como alterar a mensagem do último commit:</p>

~~~
$ git commit --amend
~~~

<p>Alterando a mensagem sem abrir o editor:</p>

~~~
$ git commit --amend –m"nova mensagem"
~~~

<p>Como desfazer um commit:</p>

~~~
$ git reset
~~~

~~~
$ git reset --soft
~~~

~~~
$ git reset --mixed
~~~

~~~
$ git reset --hard
~~~

<p>Enviar alterações para o repositório remoto:</p>

~~~
$ git push -u origin main
$ git push 
~~~

<p>Verificar alterações:</p>

~~~
$ git log
$ git log --oneline -->
~~~



<h2>HTML</h2>
<p>O HTML é uma uma linguagem de marcação e é utilizado para estruturar e formatar o conteúdo de páginas web.</p>


<h4>Estrutura básica do HTML</h4>

~~~
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>Hello World</h1>

</body>
</html>
~~~

<h4>Títulos</h4>

~~~
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
~~~

<h4>Elementos textuais</h4>

~~~
<h1>Título 1</h1>
<p>Parágrafo</p>
<br> - quebra a linha
~~~


<h4>Elementos de formatação</h4>

~~~
<b> - Texto em negrito
<strong> - Texto importante
<i> - Texto em itálico
<em> - Texto enfatizado
<mark> - Texto marcado
<small> - Texto menor
<del> - Texto excluído
<ins> - Texto inserido
<sub> - Texto subscrito
<sup> - Texto sobrescrito
~~~

<h4>Citações</h4>

~~~
<address> - Define informações de contato do autor/proprietário de um documento
<blockquote> - Define uma seção que é citada de outra fonte
<cite> - Define o título de um trabalho
<q> - Define uma pequena cotação in-line
~~~


<h4>Comentários</h4>

~~~
<!-- Seu comentário aqui-->
~~~

<h4>Links</h4>

~~~
<a href="https://github.com/vllyxw" target="_blank">Visite meu GitHub</a>
~~~
