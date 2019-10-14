---
nav: true
title: 1 - Markdown
---
# O início
A primeira coisa que vamos explorar é a linguagem Markdown.
## 1. Markdown
O Markdown é uma linguagem simples para aplicar estilo em páginas da web
ou outros documentos, aplicando poucos símbolos, como *, # ou +, e é bem útil
para quem não gosta ou não sabe html. É uma ferramenta de diagramação muito útil
para páginas da Internet, além de outros documentos.
Os níveis e subníveis de texto podem ser escritos com # Título ou ## Subtítulo 
ou ### Subsubtítulo.
### Entatizar um texto
Por exemplo, é muito simples escrever em **negrito** utilizando a palavra 
entre "****" ou *itálico*, com "**". Ou até criar um link utilizando colchetes,
como a [minha página institucional](http://professor.ufop.br/tonidandel). 
Se necessário, é poossível fazer uma citação com >. Por exemplo

>Mundo Mundo vasto mundo...

Ou até uma nota de rodapé,[^1] utilizando o comando `[^1]`,
e depois `[^1]: texto da nota` 

[^1]: A nota é essa aqui ó.
### Criando listas
Podemos também criar listas com `*` e listas ordenadas com `1.`, tais como: 

* Item 1
* Item 2
* Item 2a
* Item 2b

Ou listas ordenadas, como

1. Item 1
1. Item 2
  1. Item 2a 
  1. Item 2b

Ou de tarefas, como

- [x] Primeiro fazer isso;
- [x] Segundo, fazer isso;
- [] Depois aquilo.

### Inserindo imagens
Ou inserindo imagens, tal utilizando a sintaxe `![Logo UFOP](/images/logo-universidade.svg)`, 
que, no nosso caso, insere a imagem:[^2]

[^2]: Colocar a imagem em uma pasta criada na pasta raiz (root) do projeto. Neste caso, criamos a pasta images.

![logo-ufop](/images/logo-universidade.svg)

### Inserindo Código
Ou até uma fórmula em LateX, como $$E=mc^2 \,,$$ ou até código de alguma linguagem,
inserindo aspas simples:

*Eu acho que você deveria utilizar o pacote da ams, com o comando:* `\usepackage{ams}`. 
Para mais linhas de código, use um "tab" ou uma distância de 4 espaços:

	Código aqui;
	Cógigo aqui;
	Código aqui;

### Tabelas
É possível também fazer uma tabela bem simples, utilizando os delimitadores --|--, por exemplo:

Coluna 1 | Coluna 2
----------- | -----------
texto linha 1 x coluna 1 | texto linha 1 x coluna 2
texto linha 2 x coluna 1 | texto linha 2 x coluna 2

## 2. Instalação do Jekyll 

## Após a instalação do Jekyll 
Em um terminal Linux, crie uma pasta em uma determinada localização,
"blog" por exemplo e entre nesta pasta:
 
	$ mkdir blog  
	$ cd blog

Para criar um site estático simples dentro da pasta, basta usar o comando:

	$~blog/ jekyll new .

## Fazendo uma postagem
Para criar uma postagem, basta criar um arquivo de texto simples em Markdown,
com a extensão `.md`, e salvá-la na pasta `_posts`, no formato:

	ANO-MES-DIA-titulo-da-postagem.md

## Publicando
Para atualizar o servidor jekyll, basta fornecer os comandos, em um terminal 
Linux:
	$ jekyll build
	$ jekyll serve

Após isso será aberta uma janela da página que foi criada no servidor local. 
Basta abrir o endereço informado em `server adress` para ver o resultado:

![Jekyll-image](/images/blog-jekyll1.png)

A partir deste momento, todo o conteúdo do site criado automaticamente
pelo Jekyll, estará disponível na pasta `_site`.
