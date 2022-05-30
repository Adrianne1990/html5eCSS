# html5eCSS

Aula 11 - Introdução ao Css

A partir desta aula iremos avançar nos estudos de HTML e Css ao mesmo tempo. Isso por que HTML é muito mais interessante com Css e você não pode aprender realmente Css sem conhecer HTML.

-Como incluir Css em uma página HTML
-Setores
-Declarações, propriedades e valor

### 1) O que é CSS?

CSS (Cascading Style shetts) é um mecânismo para adicionar estilo (cores, fontes, espaçamentos, etc) a um documento web.

O CSS desenvolvido por um grupo dentro do w3c chamado CSS working Group.

-Representantes de fornecedores web;

-Outras empresas que tem interesse em CSS;

-Outras pessoas, conhecidas como peritos convidados (invited experts).

### 2) Sintaxe CSS

CSS é uma linguagem baseada em regras. - Você define regras específicando grupos de estilo que devem ser aplicados para elementos particulares ou grupos de elementos a sua página web.

Exemplo:

  h1{
      /* propriedade: valor */
      color: red;
      font-size: 36px
  }

  ### 3) Adicionando CSS para o nosso documento

  Temos tres formas de adicionar CSS ao nosso documento html.

  3.1) Adicionando rega inline

  <h1 style= "color: red;">Estudando CSS</h1>

  3.2) Adicionando regra CSS entre as tags <head>...</head> e <style> ... </style>:


Exemplo:

<head>
 
1- <style>
        h1 {
            color: red
        }
        
        h2 {
            color: olive;
        }
</style>

2- <h1 style="color:red">Curso Html5 e Css</h1>

3.3)Para ligar o style.css ao index.html adicione a seguinte linha em algum lugar dentro do <head> do documento HTML.

Exemplo:

 <link rel="stylesheet" href="style.css">

Este elemento <link> diz ao navegador que temos uma folha de estilo, usando o atributo 'rel', e a localização desse arquivo como valor do atributo 'href'.

A regra é aberta com um seletor. Isso seleciona o elemento HTML que vamos estilizar. Neste caso, estamos estilizando títulos de nível um (<h1>).

### 4) Múltiplos Seletores

Você pode pode especificar múltiplos seletores, separando-os com virgula.

Exemplo:

h1, p {
    color: red;
}