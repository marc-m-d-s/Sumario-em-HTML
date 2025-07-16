# Introdução - em atualização

HTML (HyperText Markup Language) é a linguagem padrão usada para criar páginas e aplicações na web. Ela estrutura o conteúdo, definindo títulos, parágrafos, links, imagens e outros elementos que o navegador interpreta e exibe.

Características principais:

Linguagem de marcação, não de programação.
Base da web, suportada por todos os navegadores.
Focada na estrutura e semântica do conteúdo.
Evolui continuamente com novos padrões e recursos.

# História

1991: Tim Berners-Lee cria a primeira versão do HTML no CERN, focada em documentos científicos.
1995: Surgem HTML 2.0 e depois HTML 3.2, trazendo suporte a formulários e tabelas.
1997: HTML 4.0 introduz elementos para acessibilidade, estilos e scripts.
2000: Surgimento do XHTML 1.0, versão mais rigorosa e baseada em XML.
2014: W3C lança oficialmente o HTML5, com foco em multimídia, semântica, APIs avançadas e responsividade.

Atualidade: HTML é mantido em formato “living standard” pelo WHATWG, recebendo atualizações contínuas para novas funcionalidades.

# Estrutura Básica e Metadados

<!DOCTYPE>-Declara o tipo do documento HTML (HTML5).
<html> - Elemento raiz do documento HTML.
<head> - Contém metadados da página (título, links, scripts etc.).
<title> - Define o título da página mostrado na aba do navegador.
<base> - Define URL base para links relativos.
<link> - Relaciona documento a recurso externo (CSS, favicon etc.).
<meta> - Define metadados (charset, viewport, descrição etc.).
<style> - Adiciona CSS embutido.
<script> - Insere ou referencia código JavaScript.
<noscript> - Conteúdo alternativo quando JavaScript está desabilitado.

# Estrutura de Conteúdo Semântico

<body> - Corpo da página, conteúdo visível.
<header> - Cabeçalho de página ou seção.
<footer> - Rodapé de página ou seção.
<main> - Conteúdo principal único da página.
<section> - Seção temática ou agrupamento de conteúdo.
<article> - Conteúdo independente e reutilizável (ex: post, notícia).
<aside> - Conteúdo complementar ou lateral (barra lateral, widgets).
<nav> - Área de links de navegação.
<h1> a <h6> - Títulos de seção, do mais importante (<h1>) ao menos (<h6>).
<address> - Informações de contato.
<hr> - Linha horizontal separadora temática.
<br> - Quebra de linha.
<p> - Parágrafo de texto.
<pre> - Texto pré-formatado (mantém espaçamento e quebras).

# Formatação e Texto

<abbr> - Abreviação com explicação (via atributo title).
<b> - Negrito (sem ênfase semântica).
<bdi> - Isola texto com direção bidirecional independente.
<bdo> - Altera a direção do texto (ex: LTR, RTL).
<cite> - Citação de fonte ou obra.
<code> - Trecho de código.
<data> - Dado legível e acessível para máquina (atributo value).
<dfn> - Definição de termo.
<em> - Ênfase textual (geralmente itálico).
<i> - Itálico sem ênfase semântica.
<kbd> - Entrada do teclado.
<mark> - Destaque (marca-texto).
<q> - Citação curta (aspas automáticas).
<rp> - Texto alternativo para navegadores sem suporte a <ruby>.
<rt> - Anotação ruby (pronúncia, transliteração).
<ruby> - Texto com anotação ruby (ex: japonês).
<s> - Texto riscado (obsoleto, incorreto).
<samp> - Saída de programa ou sistema.
<small> - Texto de menor importância.
<span> - Container genérico inline.
<strong> - Ênfase forte (geralmente negrito).
<sub> - Texto subscrito (abaixo da linha).
<sup> - Texto sobrescrito (acima da linha).
<time> - Data ou hora com valor legível por máquina.
<u> - Texto sublinhado (semântico, ex: erro ortográfico).
<var> - Representa variável.
<wbr> - Ponto opcional de quebra de linha.

# Listas

<ul> - Lista não ordenada.
<ol> - Lista ordenada.
<li> - Item de lista.
<dl> - Lista de definições.
<dt> - Termo da definição.
<dd> - Descrição do termo.

# Tabelas

<table> - Define tabela.
<caption> - Legenda da tabela.
<colgroup> - Agrupamento de colunas.
<col> - Define estilo/estrutura de coluna..
<thead> - Cabeçalho da tabela.
<tbody> - Corpo da tabela.
<tfoot> - Rodapé da tabela.
<tr> - Linha da tabela.
<td> - Célula de dados.
<th> - Célula de cabeçalho.

# Mídia e Multimídia

<img> - Imagem.
<map> - Mapa de imagem com áreas clicáveis.
<area> - Área clicável dentro de um mapa de imagem.
<picture> - Agrupamento de múltiplas fontes de imagem (responsivo).
<source> - Fonte alternativa para <picture>, <audio> ou <video>.
<figcaption> - Legenda para mídia ou figura.
<figure> - Container para mídia com legenda.
<audio> - Áudio embutido.
<video> - Vídeo embutido.
<track> - Faixa de texto para legendas/captions em <video> ou <audio>.
<embed> - Incorporação genérica de conteúdo externo.
<object> - Objeto externo (plugin, app etc.).
<param> - Parâmetro para <object>.
<iframe> - Janela embutida que exibe outro conteúdo HTML.

# Formulários e Interação com Usuário

<form> - Formulário para envio de dados.
<input> - Campo de entrada (texto, checkbox, rádio etc.).
<textarea> - Área de texto multilinha.
<button> - Botão clicável.
<select> - Lista suspensa.
<option> - Opção dentro de <select>.
<optgroup> - Agrupamento de opções.
<label> - Rótulo associado a campo de formulário.
<fieldset> - Agrupamento visual e semântico de campos.
<legend> - Legenda para <fieldset>.
<datalist> - Lista de sugestões para <input>.
<output> - Exibe resultado de cálculo.
<meter> - Medidor de valor dentro de faixa.
<progress> - Barra de progresso.

# Tag / Motivo da Obsolescência / Substituição Recomendada - Observação

<acronym> - Foi substituída por <abbr>. - Use <abbr> para abreviações.
<applet> - Plugins Java obsoletos, inseguro e descontinuado. - Use <object> ou tecnologias modernas (JS, HTML5).
<basefont> - Controle de fonte via CSS. - Use CSS para definir fontes.
<big> - Controle de tamanho via CSS. - Use CSS (font-size).
<center> - Alinhamento via CSS. - Use CSS (text-align: center).
<dir> - Listas de diretórios, substituída por <ul>. - Use <ul>.
<font> - Controle de estilo via CSS. - Use CSS para definir cor, fonte, tamanho.
<frame>, <frameset>, <noframes> - Estrutura com frames foi descontinuada. - Use <iframe> ou layouts modernos CSS/JS.
<isindex> - Elemento de busca simples obsoleto. - Use <input> dentro de <form>.
<strike> - Texto riscado, substituído por <s>. - Use <s> para texto riscado.
<tt> - Fonte monoespaçada via tag, não mais usada. - Use CSS (font-family: monospace).
<u> - Uso antigo para sublinhado, redefinida semântica. - Pode ser usado para indicar texto sublinhado ou erro ortográfico.
<xmp> - Exibição de código pré-formatado, perigoso. - Use <pre><code> para código pré-formatado.
<keygen> - Elemento para geração de chaves criptográficas. - Substituído por Web Crypto API.