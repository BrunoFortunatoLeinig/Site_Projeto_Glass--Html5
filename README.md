Estrutura e comandos HTML-5


<!DOCTYPE html>
<html lang="pt-br">             	      ----->   Usado para deixar em pt-br
<head>
	<meta charset="utf-8">      ----->   Usado para acentuação de do português
	<title></title>   		      ----->   Usado para Título da página
</head>
<body>				      -----> corpo do site
</body>

<h1></h1>		-----> título de paragrafo
<h2></h2>		-----> título de parágrafo abaixo na hierarquia do h1
<h3></h3>		-----> título de parágrafo abaixo na hierarquia do h2
<h4></h4>		-----> título de parágrafo abaixo na hierarquia do h3
<h5></h5>		-----> título de parágrafo abaixo na hierarquia do h4
<h6></h6>		-----> título de parágrafo abaixo na hierarquia do h5

<hgroup></hgroup>		-----> grupo de títulos
<header></header>		-----> cabeçalhos
<p></p> 			-----> separa paragrafo

<img src=" ">			-----> invoca uma imagem

<div></div>			-----> cria divisão

<wbr/>		-----> permite que palavra seja quebrada, mas sem hífen de continuação
&shy;		-----> permite que palavra seja quebrada com hífen de continuação

<b></b>	-----> coloca em negrito
<i></i>		-----> coloca em itálico
<em></em>	-----> coloca em itálico e também enfatiza aquela palavra
<del></del>	-----> coloca um risco na palavra
<span style=”text-decoration: underline;”></span>    --------> sublinha o texto ou palavra.
Style=”text-align: justfy”	--------> justifica o texto
Style=”text-align: center”	--------> centraliza o texto

<form></form>   ------> usado para formulários
Post  ------>  não faz parte do objeto é mais lento e mais seguro
Get  ------>  parte do objeto é mais rápido menos seguro
Method=”^get OU post” ^^^^ método usado para resgatar as repostas do formulários e envia-las

<input></input> ------> usado para criar uma caixa seja texto/numero/data/senha....
<fieldset><fieldset> ------> usado para criar campos para um formulário

<legend></legends>  ------> usado para deixar um titulo para o fieldset

<label></label> ------> usado para referenciar um objeto ou botão

<style>
p{
	text-align: justify;
	text-indent: 50px;
	}
</style>         -----------> Cria um padrão de estilo para tudo que estiver em <p></p>

<code></code>     -------> tudo que está entre essa TAG é considerado e mostrado como código

<pre></pre>        -------> é considerado espaços e enters dados no texto



Mudar cor por código RGB - #000000, também é possível pelo nome da cor, ou pelo código RGB sem hexadecimal   --->rgb(161, 35, 89), e existe ainda uma outra maneira que é por matiz, saturação e luminosidade Exemplo: hsl(165, 81%, 93%) também é possível usar a opacidade do texto colocando o A no final do hsl,

Background-image: url(“Nome ou caminho da imagem de funcho”)     ----> troca o fundo da pagina pela imagem solicitada

Comando color rgba(0, 0, 0, 0) 		------> onde o ultimo 0 é o nível de transparência do texto sendo  0 totalmente transparente e 1 totalmente visível

<nav></nav> 		------> usado para criar um contêiner de navegação
<ol></ol>    ---> OL: ordered list 	-------> cria uma lista ordenada podendo ser numérico, alfabético ou em algarismos romanos
<ul></ul>    ---> UL: unordered list	-------> cria uma lista não ordenada também chamada de lista com demarcadores, square --> quadrados, circle --> bolinha com fundo branco, disc --> bolinha preta
<li></li>    --->   Li: list items	-------> lista de itens

<section></section>		----> usado para dividir a pagina seção
<aside></aside>		----> usado para dividir a pagina lateral
<footer></footer>		----> usado para dividir a pagina rodapé

<table></table> 		----->usado para criar tabelas
<caption></caption>		----->usado para criar separar o título da tabela
<tr></tr> 	--->(Table row) 		----->usado para criar um “título dentro de uma tabela”
<td></td>	--->(Table data)		----->usado para os dados que compõem a tabela”
rowspan="2"			----->usado para que a célula da tabela ocupe duas linhas
colspan=”2”			----->usado para que a célula da tabela ocupe duas colunas

<article></article>	------> usado para separar coisas dentro da tag como se fossem artigos

<select></select>		----->usado para criar uma cadeia de seleção
<option></option>		----->usado para criar opções dentro da seleção
<optgroup></optgroup> 	----->usado para criar um grupo de opções




FUNÇÕES JAVA SCRIPT

<script></script>	----> tudo que está entre essa função é considerado código java script
EXEMPLO
	<script>
		document.write("Hoje é dia " + Date());
	</script> 	----> mostra a o texto e invoca a função de hora direto do sistema.

onclick="” 		------> comando para uma determinada ação quando clicar.
onmousemove="” 	------> comando para uma determinada ação quando passar o mouse
function		------> cria uma função para ser invocada
