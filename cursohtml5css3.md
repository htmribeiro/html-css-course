# Módulo 01 
## #C03A01 - A diferença entre HTML, CSS e JavaScript

> **HTML** - **H**yper**T**ext **M**arkup **L**anguage  
Linguagem focada em **conteúdo**  
- textos
- imagens
- vídeos
- tabelas

> **CSS** - **C**ascading **S**tyle **S**heets  
Linguagem focada no **design/estilo**  
- cores
- sombras
- tamanhos
- posicionamento

> **JS** - **J**ava **S**cript  
Linguagem de programação focada nas **interações**  
- menu
- animações
- popups
- validações

Instalar a Extensão do Chrome `WEB DEVELOPER`.

### Conteúdo em HTML

**Abertura<br>de tag** | **Conteúdo** | **Fechamento<br>de tag**
:---: | :---: |:---:
**\<h1>** | Exemplo de título | **\</h1>**
**\<p>** | Exemplo de parágrafo | **\</p>**

**Abertura<br>de tag** | **Parâmetro** | **Valor**
:---: | :---: |:---:
**\<img src="** foto.png | **"** **alt="** | Exemplo de foto **">**

**Abertura<br>de tag** | **Parâmetro** | **Valor** | **Conteúdo** | **Fechamento<br>de tag**
:---: | :---: |:---: | :---: |:---:
**\<a** | **href=** | "destino.html"**>** | Exemplo de link | **\</a>**

### Estilo em CSS
> Par de **propriedade** e **valor**  

**h1** **{**  
  **font-family:** Arial;  
  **font-size:** 20pt;  
  **color:** blue;  
**}**

**Seletor**|**Declaração**|**Propriedade**|**Valor**
:---: | :---: |:---: |:---:
**h1** | **{ }** | **font-family:** | Arial;
||| **font-size:** | 20pt;
||| **color:** | blue;

### Estrutura básica de documento HTML
```html
<!DOCTYPE html>
<html lang="pt-br">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" 
      content="width=device-width,
      initial-scale=1.0">
      <title>Document</title>
 
   </head>
   <body>
      <h1>Olá, Mundo!</h1>

   </body>
</html>
```
### Como funcionam a HTML e as CSS?
> Ambos ficam hospedado em um servidor de conteúdo.  
Ao serem requisitados pela máquina (client), esse conteúdo é transferido e apresentado em seu navegador.

## #C03A02 - Front-end, Back-end e Full stack
### Front-end e Back-end

client-side - **front-end**   
> HTML + CSS + JS  
Está focado na experiência e interatividade do usuário.  

Server-side - **back-end**  
> PHP + JS + C# + Python + Ruby + Java  
Está focado na interação do código com o servidor.  

**Full-stack** - engloba o conhecimento e experiência dessas duas frentes tecnológicas.

## #C04A02 - Seu primeiro código HTML  

Criamos o primeiro documento HTML
Para criarmos a estrutura básica do HTML, podemos digitar o sinal de exclamação **`!`** e em seguida precione a tecla **Enter**, e o código é criado automaticamente.

`<!DOCTYPE html>` - Essa linha de código, indica que é um documento em HTML5.  
> *Observação: demais partes do código se encontram no pdf da aula 04.*  

## #C05A01 - Parágrafos e Quebras

> \<p>\</p> - Tag de parágrafo  

> \<br> - break row

> `\&lt;` - Código ASCII que Representa o sinal menor que "<" (LESS THAN)  

> `\&gt;` - Código ASCII que Representa o sinal maior que ">" (GREATER THAN)  

## #C05A02 - Simbolos e Emoji no seu site

> `<!-- -->` - Comentário de bloco  

### Símbolos
Existem alguns outros símbolos que podem ser exibidos usando códigos. Esses códigos são chamados de **HTML Entities**, basta uma breve consulta para descobrir quais são as opções. Abaixo uma tabela com outras opções.  

**Entity** | **Descrição**
:--:|:--:  
**`\&reg;`** | Marca registrada  
**`\&copy;`** | Corporate  
**`&trade;`** | Trade Mark (marca registrada)  
**`&euro;`** | moeda euro  
**`&pound;`** | moeda libra (pound)  
**`&yen;`** | moeda yen  
**`&cent;`** | moeda cent dolar  
**`&empty;`** | Vazio  
**`&sum;`** | Soma  
**`&Delta;`** | Símbolo de Delta  
**`&larr;`** | Seta esquerda  
**`&uparrow;`** <br> ou<br> **`&uarr;`** | Seta acima  
**`&rarr;`** | Seta direita  
**`&darr;`** | Seta baixo  

[!Tips]: Acesse o [W3Schools](https://www.w3schools.com/charsets/ref_utf_symbols.asp), na área de Misc Symbols, para uma referência com vários símbolos e seus códigos.
### Emoji's
Para uma pesquisa mais precisa e atualizada, acesse o site da [emojipedia.org](https://emojipedia.org/).  
- Para adicionar na página:
  - iremos adicionar o **Codepoints**
  - Exemplo: `1F596`
  - &#x - (representa um código hexadecimal) seguido do **Codepoint** e finaliza com o ponto-e-vírgula.
  - &#x1F596;  

### Desafio d001
> [Resolução](exercicios\ex002\index.html)
## #C06A01 - Direitos Autorais

### Sites que contém imagens livres para uso
> https://www.pexels.com/pt-br/
> https://unsplash.com/

### Utilizando filtro de imagens do google images
> Ferramentas > Licenças Creative Commons

### Outros links no PDF da aula
[06 - Imagens e Favicons.pdf](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/06%20-%20Imagens%20e%20Favicon.pdf)

## #C06A02 - Formatos de Imagem para web

### JPEG
> Arquivo altamente compactada

### PNG
> Arquivo permite transparência

### GIF
> Permite transparência e movimento

## #C06A03 - Sobre o tamanho das imagens

### Redimendionamento através do GIMP
[!Tips] - A largura das imagens no site podem ser alteradas pelo CSS, porém isso não altera o tamanho do arquivo. Importante fazer alterações das larguras antes de inserir no site, para que o site não fique lento.  
Os mecanismos de busca como o Google **PENALIZAM** sites lentos e pesados, retirando-os da primeira página de buscas.

## #C06A04 - A tag img em HTML5

### Carga de imagem que está no mesmo nível de pasta do arquivo **index.html**
>```html
><img src="logo-html.png" alt="imagem do logotipo HTML 5">
>```

### Carga de imagem que está no nível de subpastas
>```html
><img src="imagens/logo-css.png" alt="imagem do logotipo CSS 3">
>```

### Carga de imagem da internet (externa ao projeto)
>```html
><img src="https://www.dondi.net/port/skills/js.png" alt="imagem logotipo do JavaScript">
> <!-- Utilizando uma URL dentro do parâmetro src="" -->
>```

## #C06A05 - Como mudar o favicon de um site
- Para usar um favicon no site, precisamos de uma imagem no formato **ICO**.  
  - [IconArchive.com](https://iconarchive.com/)
- Podemos desenhar o favicon
  - [favicon.cc](https://www.favicon.cc/)
- Podemos criar um ícone personalizado, baseado em imagens que já temos
  - [favicon.io](https://favicon.io/)

### Adicionando um favicon na página
O favicon é adicionado na estrutura de configuração da página, dentro da tag \<head>\</head>.
>```html
>link:favicon <!-- Utilizando o Emmet Abbreviantion -->
><link rel="shortcut icon" href="HTML5.ico" type="image/x-icon">
>```

### Formatos aceitos para Favicon
Além do formato **ICO** utilizado na aula, também existem outros formatos suportados para o favicon, como o próprio **PNG** que estudamos anteriormente e até o formato **SVG**, que é vetorizado e seria a melhor das opções.  
Porém, nem todo navegador é compatível com o formato **SVG** e acaba causando inconsistência na exibição do site em outras plataformas.

- Sendo assim, é aconselhavel a utilização do formato ICO. 

## #C07A01 - Hierarquia de Títulos
### Outros links no PDF da aula
[07 - Hierarquia de títulos.pdf](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/07%20-%20Hierarquia%20de%20t%C3%ADtulos.pdf)
### Estutura de títulos de uma revista 
- Título: FALTA DE SINTONIA
  - Sub-títulos: 
    - Pense antes de agir
    - Passe mais tempo com seu desafeto
    - Saiba com quem está lidando
    - Tenha objetividade
### Índice de um livro também é hierárquico
- Título: Entendendo Portugal

1. INTRODUÇÃO  
  1.1 JUSTIFICAÇÃO DA TEMÁTICA  
  1.2 CARÁTER EXCECIONAL DO CASO DE ESTUDO  
  1.3 PERGUNTAS DE PARTIDA E OBJETIVOS DE INVESTIGAÇÃO  
  1.4 METODOLOGIA DE INVESTIGAÇÃO  
    1.4.1 Etapas de investigação  
    1.4.2 Instrumentos de análise e fontes de informação  

2. O ORDENAMENTO DO TERRITÓRIO EM PORTUGAL: INSTRUMENTOS E ATORES  
  2.1 OS INSTRUMENTOS DE GESTÃO DO TERRITÓRIO  
    2.1.1 Os intrumento de planeamento territorial  
    2.1.2 Os regimes territoriais especiais  

### Entendendo os níveis dos títulos
> Página 3 da apostíla  
Títulos em HTML são conhecidos como *Headings* (que, traduzindo do Inglês, significa *título* mesmo).
### Os títulos vão de H1 até H6
Os títulos possuem **SEIS NÍVEIS** de hierarquia, e esses níveis servem parar organizar nosso conteúdo.  
Para isso usamos as tags \<h1>, \<h2>, \<h3>, \<h4>, \<h5>, \<h6> para demarcar nossos títulos

**Título Principal da matéria:** 
- "Falta de sintonia"  
### Tags para o título principal
>```html
> <h1></h1>
>```
### H1 é letra grande? H6 é letra pequena?
> Isso não tem fundamento algum!  
Um `<h1>` significa que esse é um assunto principal  
Já o `<h2>` significa que esse é um sub-assunto de `<h1>`  
O `<h3>` significa que esse é um sub-assunto do `<h2>`  
E assim sucessivamente até o `<h6>`.
### Pode ter mais de um H1 em uma página?
> Ele é um tema principal, e se a sua página tem vários temas principais, use vários H1 sem medo.
### Gerador de Lorem Ipsum
>```html
><p>lorem</p>
>```

## #C08A01 - Semântica na HTML5 é importante
>*`"Semântica é o significado dos vocábulos, por oposição à sua forma."`*  

Analisando a frase acima percebemos que uma palavra pode ter **forma** e **significado**, e que a **semântica** dá mais valor ao significado.
### Comparando HTML4 e HTML5
Na HTML4, tinham tags como:
- `<b>` que colocava um texto em negrito
- `<u>` que colocava o termo sublinhado
- `<blink>` que fazia o texto piscar  

Essas eram tags que representavam apenas uma **forma**.
> Exemplo:
>*`"Juvenal era um sujeito de muita sorte. E já começou de pequeno, onde morou na <u>Rua Marquês de Lira Filho</u>, um local de fácil acesso ao Centro da cidade."`*  

Essa seria uma maneira de determinar somente um formato visual para chamar atenção para o endereço onde o cara nasceu. O sublinhado é apenas uma **forma**, sem **significado** explícito.  
</br>

Já a HTML5 chegou com o conceito de valorizar a **semântica**, logo suas tags tentam levar um **significado** embutido muito forte.
> Exemplo:
>*`"Juvenal era um sujeito de muita sorte. E já começou de pequeno, onde morou na <address>Rua Marquês de Lira Filho</address>, um local de fácil acesso ao Centro da cidade."`*  

Note que agora, usamos a tag `<address>` para dar um **significado** ao destaque que fizemos.  
</br>

Sendo assim, em HTML5, vemos de forma bastante evidênte a presença do chamado **HTML semântico** ou **tags semânticas** ou ainda o **conteúdo semântico**.  

> **O intuito é deixar a apresentação gráfica por conta das CSS.**

## #C08A02 – Negrito e Itálico do jeito certo
> Existe um documento oficial do Consórcio da World Wide Web (W3C) que é atualizado constantemente com as tags que estão ficando obsoletas e algumas substituição desejáveis que devemos fazer.

> - [Diferenças entre HTML4 e 5](https://www.w3.org/TR/html5-diff/#absent-attributes)
> - [Elementos obsoletos na HTML5](https://dev.w3.org/html5/pf-summary/obsolete.html)

### **Negrito** e *Itálico*
Vamos ver agora algumas formatações bem usadas das últimas versões da linguagem, começando pelos famosos **negrito** e *itálico*.

Como vimos anteriormente, existem as tags `<b>` e `<i>` para essa tarefa, mas elas não possuem significado e focam apenas na forma, sendo assim, são pouco semânticos.  
Sendo assim, passaremos a utilizar as tags `<strong>` e `<em>` para realizar essas mesmas formatações visuais, só que agora com sentido.

A tag `<strong>` significa que o termo delimitado possui força dentro da frase. Logo, ele aparecerá em **negrito**.

Já a tag `<em>` significa que queremos dar **ênfase** (do Inglês *emphasis*) ao termo. Logo, ele aparecerá em *itálico*.

> Note que, ao usar `<strong>` e `<em>` no lugar de `<b>` e `<i>`, damos mais significado aos nossos termos e conteúdos. Como eles vão ser representados visualmente (formal), vai depender das nossas folhas de estilo CSS.

## #C08A03 – Formatações adicionais em HTML
### Usando marca texto
Para fazer essas marcas em HTML5, usamos a tag `<mark>...</mark>` para delimitar o texto que queremos demarcar, como se estivéssemos usando uma caneta marcador.  

> **COMO FAÇO PARA MUDAR A COR DA CANETA?** Com usar outras cores? Contando que as configurações sejam especificadas nas folhas de estilo CSS.

### Tags "Mortas"
- `<font>` e `<center>`
- `<applet>` e `<blink>`
- `<b>`
- `<big>`
- `<strike>`

### `<small>` ainda sobrevive
A tag `<small>` - que deixa o texto menor.

### Texto deletado
A tag `<del>`, que siginifica que o texto está ali, pode ser lido, mas deve ser desconsiderado pelo leitor.

### Texto inserido
Se colocarmos um texto qualquer dentro de `<ins> e </ins>`, estamos dizendo que o texto ali, deve ser lido e você deve prestar atenção nele.

### Texto sobrescrito e subscrito
As tags `<sub>` e `<sup>` para essa finalidade.

### Trecho de código
A tag `<code>` da HTML onde você pode delimitar seu código. A principal vantagem no uso dessa tag é o valor semântico que ela representa, indicando ao navegador que se trata de um código de computador. Porém, existe também um efeito visual, pois as letras ficam no modo mono-espaçadas (monospace), o facilita bastante a leitura do código.  
> Analise, por exemplo, o trecho de código a seguir:  

```html
<h1>Exemplo de código em Python</h1>
<code>
  num = int(input("Digite um número"))
  if num % 2 == 0:
    print(f'O número {num} é par')
  else:
    print(f'O número {num} é impar')
  print("FIM DO PROGRAMA")
</code>
```

> Acontece que o código acima, irá mudar as letras, para que fiquem mono-espaçadas

Para resolver esse problema, vamos usar uma outra tag HTML chamada `<pre>`, que mantém o texto pré-formatado, exatamente da mesma maneira na qual ele foi digitado, incluindo quebras de linhas, espaços e tabulações.

```html
<h1>Exemplo de código em Python</h1>
<pre><code>
  num = int(input("Digite um número"))
  if num % 2 == 0:
    print(f'O número {num} é par')
  else:
    print(f'O número {num} é impar')
  print("FIM DO PROGRAMA")
</code></pre>
```
## #C08A04  – Citações e Códigos
### Citações
Para criar uma citação em HTML, podemos usar a tag `<q>` (do Inglês *quote*, que significa citar). O texto que estiver entre `<q> e </q>` já vai receber automaticamente as aspas, mas não terá nenhum deslocamento. Essa técnica é mais usada quando queremos uma citação no meio de um parágrafo.  

Também podemos criar citações mais longas (em bloco) e que tenham um parágrafo só para si. Nesse caso, colocaremos tudo dentro de `<blockquote>` e `</blockquote>` e o texto ganha um recuo automaticamente. Podemos também colocar um link para o texto original, usando o parâmentro `cite` dentro da tag.  

```html
<blockquote cite="https://www.martinsfontespaulista.com.br/php-a-biblia-53304.aspx/p">
  O PHP é uma linguagem para a criação de scripts para a Web do lado servidor embutidos em HTML, cujo código-font é aberto, e que é compatível com os mais importantes servidores Web (especialmente Apache).
</blockquote>
```
### Abreviações
Essa é uma novidade da HTML5 e que ajuda muito em áreas como a de Tecnologia, que usa muitas siglas e abreviações. Sempre que você quiser escrevver uma sigla, mas deixar claro ao usuário (e aos mecanismos de busca) o significado dela, use a tag `<abbr>`.

```html
<p>Estou estudando <abbr title="HyperText Markup Language">HTML</abbr> para criar sites.</p>
```
> Quando passamos o mouse sobre a sigla abreviada, um pequeno texto aparece com o seu significado.

### Texto Invertido
A função da tag `<bdo>`é de inverter o conteúdo entre `<bdo> e </bdo>`.

Para começo de conversa, BDO significa *bi-directional orerride*. Ao usar essa tag, coloque também o parametro `dir` para indicar uma das duas direções possíveis:
- `rtl` = da direita para a esquerda (right-to-left)
- `ltr` = da esquerda para a direita (left-to-right)
```html
<h2>Texto Invertido</h2>
<bdo dir="rll">Este texto todo está invertido no formato RIGHT-TO-LEFT.</bdo>
```
## #C09A01 - Listas OL e UL
A linguagem HTML disponibiliza vários tipos de lista para produzirmos nosso conteúdo e deixá-lo mais claro e eficiente.  

### Listas Ordenadas
A HTML chama de **ordered lists** todas aquelas listas onde a ordem dos itens é algo muito importante.  
> **Exemplos:**
1. Um passo-a-passo para criar um bolo
1. Uma lista de aprovados no vestibular
1. Uma lista com os carros mais caros do mundo

Para criar uma ***ordered list***, vamos usar a tag `<ol>` para delimitar a lista e `<li>` (***list item***) para identificar cada item da lista.  
```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
  <li>Item 5</li>
</ol>
```

IMPORTANTE! |
:-- |
Segundo a **W3C**, a tag `<ol>` é de fechamento obrigatório (ou seja, devemos sempre usar `</ol>`). Já a tag `<li>` tem o seu fechamento **opcional** a partir da HTML5.|

#### Parâmetros da tag `<ol>`
> **`type=""`**  
> Onde configuramos o tipo de marcador da lista atual. As opções de valores para esse parâmetro são:
- **1** - Valor padrão. Cria listas numeradas. ***Ex.: 1, 2, 3, 4, ...***
- **A** - Cria listas alfabéticas em maiúsculas. ***Ex.: A, B, C, D, ...***
- **a** - Cria listas alfabéticas em minúsculas. ***Ex.: a, b, c, d, ...***
- **I** - Cria listas com algarismos romanos em maiúsculas. ***Ex.: I, II, III, IV, ...***
- **i** - Cria listas com algarismos romanos em minúsculas. ***Ex.: i, ii, iii, iv, ...***  
> **`start=""`**  
> Podemos também indicar o início da contagem usuando esse parâmetro.  

Por exemplo,  a tag **`<ol type="I" start="5">`** vai gerar itens numerados como ***V, VI, VII, VIII, IX, ...***
### Lista Não Ordenadas
**Unordered lists**, também chamadas de listas com marcadores, que são aquelas onde a ordem dos itens não influenciará no significado da lista. Ela é apenas uma ótima maneira para organizar os itens que não apresentam uam classificação necessariamente.  

Para criar uma **unordered lists**, vamos usar a tag `<ul>` para delimitar a lista e a tag `<li>` para criar cada um dos seus itens internos.  
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
  <li>Item 5</li>
</ul>
```
#### Parâmetros da tag `<ul>`
>**`type=""`**  
O marcador padrão é a bolinha preta totalmente preenchida, mas existe a opção de configurar a propriedade  da tag `<ul>` com os seguintes valores:
- **disk** - padrão. Uma bola preta totalmente pintada.
- **circle** - Uma bola com uma borda preta e sem preenchimento.
- **square** - Um pequeno quadrado preto totalmente pintado.  

## #C09A02 - Listas mistas e de definição
### Misturando as coisas
Podemos também criar listas mistas, configurando listas dentro de outras listas. Exemplo:  
```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <ol type="a">
    <li>Item 2.1</li>
    <li>Item 2.2</li>
    <li>Item 2.3</li>
  </ol>
  <li>Item 3</li>
  <li>Item 4</li>
  <li>Item 5</li>
</ol>
```  
O resultado visual do código acima será semelhante ao que temos a seguir:  
1. Item 1
2. Item 2  
  a. Item 2.1  
  b. Item 2.2  
  c. Item 2.3
3. Item 3
4. Item 4
5. Item 5

note que os itens da lista interna (a, b, c) estão deslocados para a direita em relação ao item 2, do qual essa sub-lista é filha.  

[!DICA] | 
:-- |
Além de aninhar listas ordenadas, podemos juntar lisatas `<ul>` com `<ol>` e vice-versa. As listas internas sempre terão deslocamento interno para a direita. |

### Lista de Definições
É como se fosse um dicionário, temos os termos e as suas descrições. É uma lista sem demarcações, mas bem útil em alguns casos.  

Toda lista de definições estã dentro de uma tag  
- **`<dl>  </dl>` (definition list)**  

Cada termo é um
- **`<dt>  </dt>` (definition term)**

E cada descrição é um
- **`<dd>  </dd>` (definition description)**  

IMPORTANTE! |
:-- |
Assim como os itens da lista, essas duas tags `<dt>` e `<dd>` tem o seu fechamento **opcional** segundo a referência oficial da HTML5.|  

Exemplo simples que cria uma lista com três definições

```html
<dl>
  <dt>HTML</dt>
  <dd>Linguagem de marcação para a criação do conteúdo de um site.</dd>
  
  <dt>CSS</dt>
  <dd>Linguagem de marcação para a criação do design de um site.</dd>
  
  <dt>JavaScript</dt>
  <dd>Linguagem de programação para a criação de interatividade de um site.</dd>
</dl>
```
O resultado visual dessa lista aplicado pelo navegador é:  

HTML  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Linguagem de marcação para a criação do conteúdo de um site.  
CSS  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Linguagem de marcação para a criação do design de um site.  
JavaScript  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Linguagem de programação para a criação de interatividade de um site.  

## #C10A01 - Links e Âncoras em HTML5

### Joga a âncora, marujo
> página 3  

Os *hyperlinks* são um dos conceitos mais antigos da históra da linguagem HTML. Eles permitem que você ligue um ponto a outro na *World Wide Web*. Toda vez que você está acessando um site e clica em um local para  ir para outra página, outro site pou até para baixar um arquivo, você está interagindo com um *hyperlink*.  

Mecanismos de busca se utilizam de hyperlinks para descobrir novos conteúdos. Por isso é tão importante conseguir links válidos de outros sites para o nosso próprio site.

**APRENDA MAIS:** |
:--|
Veja com mais detalhees como funcionam os algoritmos fundamentais de busca assistendo esse vídeo do próprio **Google**, onde o engenheiro **Mat Cutts** explica o mecanismo básico na ferramenta mais valiosa do mundo.|
Google: https://youtu.be/BNHR6IQJGZs |

[?] SEO - SEARCH ENGINEE OTMIZATION
#### Criando uma âncora
Para criar um hyperlink, devemos utilizar a tag **`<a>`**. 

#### Principais atributos da tag `<a>`
- **`href`**, que cria um referência hipertexto. Exemplo:
>```html
><h1>Vamos criar um link</h1>
><a href="https://github.com/htmribeiro">Acesse o meu perfil GitHub</a>
>```

> Note que dentro do atributo **`href`**, o que colocamos foi uma **URL** completa para outro site.

- **`hreflang`**, que permite indicar qual é o idioma principal do site para onde o link está desviando o fluxo de navegação.  
```html
<a href="https://www.w3schools.com/html/" hreflang="en">
  Site da W3Schools (em inglês)
</a>
```
> Isso vai permitir avisar ao navegador e a softwares de tradução como lidr caso o visitante opte por traduzir automaticamente os conteúdos.

## #C10A02 - Links Internos
### Mira no Alvo
> página 4  

Por padrão, um *hyperlink*, abre o site de destino na mesma janela que está sendo navegado, ou seja, o conteúdo anterior vai deixar de ser exibido, mostrando o novo conteúdo.  

Esse comportamento é desejado quando o visitante vai continuar a visitar o nosso site, apenas mudando de um documento para outro. 

> Mas e quando um clique leva o visitante para outro site e provavelmente ele nunca mais voltará ao nosso?  

- **`target`** - atributo controla onde o site de destino vai abrir
#### Valores suportados pelo `target`
- `_blank` vai abrir o link em uma nova janela em branco
- `_self` vai abrir  o link na janela ou frame atual (padrão)
- `_top` vai desfazer todos os frames e abrir o destino no navegador completo
- `-parent` similar ao uso do `_top` em uma referência à janela pai
- nome-do-frame caso esteja usando frames, indicar o nome da janela a abrir  

> Como o uso de frames é uma técnica quase em desuso, vamos nos basear apenas nas duas primeiras opções `_blank` e `_self`  
>```html
><a href="pagina2.html" target="_self">
>  Continuar navegando no site
></a>
>
><a href="https://github.com/htmribeiro" target="_blank">
>  Abrir perfil GitHub em nova janela
></a>
>```
- **`rel`** - indica qual é a natureza do destino do link
#### Alguns Valores suportados pelo `rel`
- `next` indica que o link é para a próxima parte do documento atual
- `prev` indica que o link é para a parte anterior do documento atual
- `author` indica que é um link para o site do autor do artigo atual
- `external` indica que é um link para outro site que não faz parte do site atual
- `nofollow` indica que é um link para um site não endossado, como link pago

>```html
><a href="pagina2.html" target="_self" rel="next">
>  Continuar navegando no site
></a>
>``` 

> Nesse código, chamamos de **link local** ou **link interno**, já que ele leva o visitante a outra página dentro do nosso próprio site. Note que não é necessário nem indicar a URL completa.

>```html
><a href="https://github.com/htmribeiro" target="_blank" rel="external">
>  Abrir perfil GitHub em nova janela
></a>
>```

> Nesse segundo código, o link vai nos levar par um outro site, o que chamamos **link externo**. Neste caso, devemos indicar a URL completa.


# Módulo 02
# Módulo 03
# Módulo 04
# Módulo 05
# Módulo 06
# Módulo 07
# Módulo 08
# Módulo 09
# Módulo 10
# Módulo 11
# Módulo 12
# Módulo 13