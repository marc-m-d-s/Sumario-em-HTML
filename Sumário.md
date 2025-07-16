# 1. Introdução - em atualização

HTML (HyperText Markup Language) é a linguagem padrão usada para criar páginas e aplicações na web. Ela estrutura o conteúdo, definindo títulos, parágrafos, links, imagens e outros elementos que o navegador interpreta e exibe.

Características principais:

    - Linguagem de marcação, não de programação.
    - Base da web, suportada por todos os navegadores.
    - Focada na estrutura e semântica do conteúdo.
    - Evolui continuamente com novos padrões e recursos.

# 2. História

    - 1991: Tim Berners-Lee cria a primeira versão do HTML no CERN, focada em documentos científicos.
    - 1995: Surgem HTML 2.0 e depois HTML 3.2, trazendo suporte a formulários e tabelas.
    - 1997: HTML 4.0 introduz elementos para acessibilidade, estilos e scripts.
    - 2000: Surgimento do XHTML 1.0, versão mais rigorosa e baseada em XML.
    - 2014: W3C lança oficialmente o HTML5, com foco em multimídia, semântica, APIs avançadas e responsividade.

Atualidade: HTML é mantido em formato “living standard” pelo WHATWG, recebendo atualizações contínuas para novas funcionalidades.

# 3. Estrutura Básica e Metadados

    - &lt;!DOCTYPE&gt; - Declara o tipo do documento HTML (HTML5).
    - &lt;html&gt; - Elemento raiz do documento HTML.
    - &lt;head&gt; - Contém metadados da página (título, links, scripts etc.).
    - &lt;title&gt; - Define o título da página mostrado na aba do navegador.
    - &lt;base&gt; - Define URL base para links relativos.
    - &lt;link&gt; - Relaciona documento a recurso externo (CSS, favicon etc.).
    - &lt;meta&gt; - Define metadados (charset, viewport, descrição etc.).
    - &lt;style&gt; - Adiciona CSS embutido.
    - &lt;script - Insere ou referencia código JavaScript.
    - &lt;noscript&gt; - Conteúdo alternativo quando JavaScript está desabilitado.

# 4. Estrutura de Conteúdo Semântico

    - &lt;body&gt; - Corpo da página, conteúdo visível.
    - &lt;header&gt; - Cabeçalho de página ou seção.
    - &lt;footer&gt; - Rodapé de página ou seção.
    - &lt;main&gt; - Conteúdo principal único da página.
    - &lt;section&gt; - Seção temática ou agrupamento de conteúdo.
    - &lt;article&gt; - Conteúdo independente e reutilizável (ex: post, notícia).
    - &lt;aside&gt; - Conteúdo complementar ou lateral (barra lateral, widgets).
    - &lt;nav&gt; - Área de links de navegação.
    - &lt;h1&gt;  a &lt;h6&gt; - Títulos de seção, do mais importante (&lt;h1&gt; ) ao menos (&lt;h6&gt; ).
    - &lt;address&gt; - Informações de contato.
    - &lt;hr&gt; - Linha horizontal separadora temática.
    - &lt;br&gt; - Quebra de linha.
    - &lt;p&gt; - Parágrafo de texto.
    - &lt;pre&gt; - Texto pré-formatado (mantém espaçamento e quebras).

# 5. Formatação e Texto

    - &lt;abbr&gt; - Abreviação com explicação (via atributo title).
    - &lt;b&gt; - Negrito (sem ênfase semântica).
    - &lt;bdi&gt; - Isola texto com direção bidirecional independente.
    - &lt;bdo&gt; - Altera a direção do texto (ex: LTR, RTL).
    - &lt;cite&gt; - Citação de fonte ou obra.
    - &lt;code&gt; - Trecho de código.
    - &lt;data&gt; - Dado legível e acessível para máquina (atributo value).
    - &lt;dfn&gt; - Definição de termo.
    - &lt;em&gt; - Ênfase textual (geralmente itálico).
    - &lt;i&gt; - Itálico sem ênfase semântica.
    - &lt;kbd&gt; - Entrada do teclado.
    - &lt;mark&gt; - Destaque (marca-texto).
    - &lt;q&gt; - Citação curta (aspas automáticas).
    - &lt;rp&gt; - Texto alternativo para navegadores sem suporte a &lt;ruby&gt;.
    - &lt;rt&gt; - Anotação ruby (pronúncia, transliteração).
    - &lt;ruby&gt; - Texto com anotação ruby (ex: japonês).
    - &lt;s&gt; - Texto riscado (obsoleto, incorreto).
    - &lt;samp&gt; - Saída de programa ou sistema.
    - &lt;small&gt; - Texto de menor importância.
    - &lt;span&gt; - Container genérico inline.
    - &lt;strong&gt; - Ênfase forte (geralmente negrito).
    - &lt;sub&gt; - Texto subscrito (abaixo da linha).
    - &lt;sup&gt; - Texto sobrescrito (acima da linha).
    - &lt;time&gt; - Data ou hora com valor legível por máquina.
    - &lt;u&gt; - Texto sublinhado (semântico, ex: erro ortográfico).
    - &lt;var&gt; - Representa variável.
    - &lt;wbr&gt; - Ponto opcional de quebra de linha.

# 6. Listas

    - &lt;ul&gt; - Lista não ordenada.
    - &lt;ol&gt; - Lista ordenada.
    - &lt;li&gt; - Item de lista.
    - &lt;dl&gt; - Lista de definições.
    - &lt;dt&gt; - Termo da definição.
    - &lt;dd&gt; - Descrição do termo.

# 7. Tabelas

    - &lt;table&gt; - Define tabela.
    - &lt;caption&gt; - Legenda da tabela.
    - &lt;colgroup&gt; - Agrupamento de colunas.
    - &lt;col&gt; - Define estilo/estrutura de coluna..
    - &lt;thead&gt; - Cabeçalho da tabela.
    - &lt;tbody&gt; - Corpo da tabela.
    - &lt;tfoot&gt; - Rodapé da tabela.
    - &lt;tr&gt; - Linha da tabela.
    - &lt;td&gt; - Célula de dados.
    - &lt;th&gt; - Célula de cabeçalho.

# 8. Mídia e Multimídia

    - &lt;img&gt; - Imagem.
    - &lt;map&gt; - Mapa de imagem com áreas clicáveis.
    - &lt;area&gt; - Área clicável dentro de um mapa de imagem.
    - &lt;picture&gt; - Agrupamento de múltiplas fontes de imagem (responsivo).
    - &lt;source&gt; - Fonte alternativa para &lt;picture&gt; , &lt;audio&gt;  ou &lt;video&gt;.
    - &lt;figcaption&gt; - Legenda para mídia ou figura.
    - &lt;figure&gt; - Container para mídia com legenda.
    - &lt;audio&gt; - Áudio embutido.
    - &lt;video&gt; - Vídeo embutido.
    - &lt;track&gt; - Faixa de texto para legendas/captions em &lt;video&gt;  ou &lt;audio&gt;.
    - &lt;embed&gt; - Incorporação genérica de conteúdo externo.
    - &lt;object&gt; - Objeto externo (plugin, app etc.).
    - &lt;param&gt; - Parâmetro para &lt;object&gt;.
    - &lt;iframe&gt; - Janela embutida que exibe outro conteúdo HTML.

# 9. Formulários e Interação com Usuário

    - &lt;form&gt; - Formulário para envio de dados.
    - &lt;input&gt; - Campo de entrada (texto, checkbox, rádio etc.).
    - &lt;textarea&gt; - Área de texto multilinha.
    - &lt;button&gt; - Botão clicável.
    - &lt;select&gt; - Lista suspensa.
    - &lt;option&gt; - Opção dentro de &lt;select&gt;.
    - &lt;optgroup&gt; - Agrupamento de opções.
    - &lt;label&gt; - Rótulo associado a campo de formulário.
    - &lt;fieldset&gt; - Agrupamento visual e semântico de campos.
    - &lt;legend&gt; - Legenda para &lt;fieldset&gt;.
    - &lt;datalist&gt; - Lista de sugestões para &lt;input&gt;.
    - &lt;output&gt; - Exibe resultado de cálculo.
    - &lt;meter&gt; - Medidor de valor dentro de faixa.
    - &lt;progress&gt; - Barra de progresso.

# 10. Tag / Motivo da Obsolescência / Substituição Recomendada - Observação

    - &lt;acronym&gt; - Foi substituída por &lt;abbr&gt;. - Use &lt;abbr&gt; para abreviações.
    - &lt;applet&gt; - Plugins Java obsoletos, inseguro e descontinuado. - Use &lt;object&gt; ou tecnologias modernas (JS, HTML5).
    - &lt;basefont&gt; - Controle de fonte via CSS. - Use CSS para definir fontes.
    - &lt;big&gt; - Controle de tamanho via CSS. - Use CSS (font-size).
    - &lt;center&gt; - Alinhamento via CSS. - Use CSS (text-align: center).
    - &lt;dir&gt; - Listas de diretórios, substituída por &lt;ul&gt;. - Use &lt;ul&gt;.
    - &lt;font&gt; - Controle de estilo via CSS. - Use CSS para definir cor, fonte, tamanho.
    - &lt;frame&gt; , &lt;frameset&gt; , &lt;noframes&gt; - Estrutura com frames foi descontinuada. - Use &lt;iframe&gt; ou layouts modernos CSS/JS.
    - &lt;isindex&gt; - Elemento de busca simples obsoleto. - Use &lt;input&gt; dentro de &lt;form&gt;.
    - &lt;strike&gt; - Texto riscado, substituído por &lt;s&gt;. - Use &lt;s&gt; para texto riscado.
    - &lt;tt&gt; - Fonte monoespaçada via tag, não mais usada. - Use CSS (font-family: monospace).
    - &lt;u&gt; - Uso antigo para sublinhado, redefinida semântica. - Pode ser usado para indicar texto sublinhado ou erro ortográfico.
    - &lt;xmp&gt; - Exibição de código pré-formatado, perigoso. - Use &lt;pre&gt; &lt;code&gt; para código pré-formatado.
    - &lt;keygen&gt; - Elemento para geração de chaves criptográficas. - Substituído por Web Crypto API.