# Módulo 01 | Primeiros passos HTML + CSS

> Resumo:

* Conceitos básicos
* preparação do ambiente
* semântica da HTML5
* textos
* títulos
* ligações (links)
* multimídia
* estilos

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

### Sites que contém imagens e vídeos livres para uso
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

Toda lista de definições estão dentro de uma tag  
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

## #C10A03 - Links para downloads
### E para fazer Downloads?
> página 5  

A partir da versão HTML5, as âncoras recebem atributos especiais para efetuar dowloads de material em PDF ou de um arquivo ZIP qualquer.  e adicionar o atributo e .

#### Atributo
- **`download`** - Basta fazer o link diretamente para o arquivo que se deseja efetuar o download configurando o valor com o nome do arquivo a ser baixado  
- **`type`** - Usado para indicar ao navegador que tipo de arquivo está sendo baixado.  
>```html
><a href="livro/meulivro.zip" download="meulivro.zip" type="application/pdf">
>  Baixe aqui o PDF do meu livro
></a>
>```

#### Alguns *media types* bem usados no nosso dia-a-dia:
|||||||
--|--|--|--|--|--|
application/zip | video/mp4 | audio/mpeg | image/jpeg | text/html | font/ttf
application/pdf | video/H264 | audio/aac | image/png | text/css | font/collection
application/nsword | video/JPEG |audio/mp4| image/bmp| text/javascript | font/otf

**LISTA DE MEDIA TYPES** |
--|
Se você quer saber o que escrever dentro do atributo `type` de uma âncora de hypertext, consulte a lista oficial da [IANNA.org](https://www.iana.org/assignments/media-types/media-types.xhtml)|

## #C10A04 - Desafios propostos

#### [Desafio 05 - desafio-social](desafios\modulo-01\d005\pdf\desafio-social.pdf)
#### [Desafio 06 - Desafio das Tags](desafios\modulo-01\d006\pdf\desafio-tags.pdf)


## #C11A01 - Imagens Dinâmicas
### Seu site deve se adaptar ao tamanho da tela
> página 3

A mídia que mais sofre com a diversidade de dispositivos de acesso a sites, são as fotos. Se utilizarmos uma mesma foto que é exibida em uma TV para também ser exibida em um celular, teremos que redimensionar forçadamente a imagem com CSS.  
Porém, essa prática não vai fazer com que o tamanho (em bytes) diminua também.  
Isso acaba aumentando o consumo  de dados em dispositivos móveis e deixando seu site muito pesado.  

**CUIDADO!** |
:--|
Sites lentos diminuem a **taxa de rejeição** dos usuários, que ficam menos tempo acessando e podem prejudicar a indexação da sua página em mecanismos de busca como o **Google**. Veja o vídeo a seguir, um especialista em SEO - SEARCH ENGINEE OTMIZATION (otimização para mecanismos de busca) falando sobre lentidão de sites, principalemente via 3G e 4G do celular.|
Portal SEO: https://youtu.be/jWnMfvSdo1E |

## #C11A02 - Imagens que se adaptam sozinhas
### Imagens Flexíveis
> página 4

Nosso primeiro passo no caminho de adaptar nosso conteúdo ao tamanho da tela vais ser aprender a gerar imagens de tamanhos diferentes.

As tags **`<picture>`** e **`<source>`** - fará com que o navegador carregue a imagem certa para cada situação.  

Para exemplo, vamos utilizar três imagens:
- a menor com 300x300px
- a média com 700x700px
- a maior com 1000x1000px

```html
<picture>
  <img src="foto-g.png" alt="A imagem flexível funciona">
</picture>
```
A novidade aqui é que inserimos a tag `<img>` dentro da tag `<picture>`, que vai concentrar as outras fontes de imagem. Por padrão, a imagem **foto-g.png** (1000x1000px) será carregada.

O problema vai começar a surgir quando a janela do navegador chegar perto dos 1000 pixels de largura, pois a foto não vai mais caber lá. Vamos agora adicionar uma linha para resolver esse problema:
>```html
><picture>
>  <source media="(max-width: 1050px)" srcset="foto-m.png" type="image/png">
>  <img src="foto-g.png" alt="A imagem flexível funciona">
></picture>
>```
Note que a tag `<source>` possui três atributos:
- **media** indica o tamanho máximo a ser considerado para carregar a imagem indicada no atributo **srcset**.
- **srcset** vai configurar o nome da imagem que será carregada quando o tamanho indicado for atingido  
- **type** vai indicar o *media type* da imagem que usamos  

>**ATENÇÃO!** |
>:-- |
>Você pode até colocar o valor exato de 1000px na propriedade max-width, mas vai perceber que um valor ligeiramente acima vai gerar resultados mais interessantes.

Recarrege seu código e mude o tamanho da janela do navegador. Você vai perceber que a imagem muda automaticamente conforme aumentamos ou diminuímos o tamanho da tela.

Vamos continuar e acrescentar mais um `<source>` à nossa imagem:

>```html
><picture>
>  <source media="(max-width: 750px)" srcset="foto-p.png" type="image/png">
>  <source media="(max-width: 1050px)" srcset="foto-m.png" type="image/png">
>  <img src="foto-g.png" alt="A imagem flexível funciona">
></picture>
>```
É importante que exista uma ordem entre os `<source>`, e nessa nossa confiugração, os itens mais acima sejam os menores tamanhos para `max-width` e que os seguintes sejam os maiores, de forma crescente.  

> **IMPORTANTE!**  
> O último item dentro de `<picture>` deve ser a imagem padrão.

## #C11A03 - Colocando áudio no seu site

### Vamos falar sobre áudio
> página 5  

Com o HTML5, temos a facilidade em compartilhar áudio nos nossos sites sem depender necessariamente de JavaScript ou plugins extras. A partir de agora, basta uma tag **`<audio>`** e alguns **`<source>`** para fazer seu site ser capaz de tocar qualquer áudio.  
```html
<audio>
  <source src="midia/guanacast-33.mp3" type="audio/mpeg">
  <source src="midia/guanacast-33.ogg" type="audio/ogg">
  <source src="midia/guanacast-33.wav" type="audiio/wav">
  <p>seu navegador não suporta áudio <a href="midia/guanacast-33.mp3" download="guanacast-33.mp3" type="audio/mpeg">Clique aqui</a>para baixar o arquivo MP3.</p>
</audio>
```
Vamos analisar os principais atributos da tag `<audio>`:  

- O atributo **`preload`** indica se o áudio será pré-carregado ou não e aceita três valores:
  - **metadata** vai carregar apenas as informações sobre o arquivo (tamanho, tempo, informações de direitos, etc)
  - **none** não vai carregar absolutamente nada até que o usuário clique no botõ play ou um script inicie a reprodução
  - **auto** (padrão) vai carregar o arquivo de áudio inteiro assim que a página for carregada, mesmo que o usuário nunca aperte o play
- O atributo **`controls`** vai apresentar o player na tela. Caso seja colocado na tag `<audio>`, o controle será transparente e o usuário não poderá interagir com ele.
- O atributo **`autoplay`**, quando inserido, vai iniciar a reprodução do áudio assim que a página for carregada.  

Dentro da tag `<audio>`, adicionamos vários `<source>` com formatos diferentes do mesmo áudio. Coloque na parte de cima o seu formato favorito. Os demais só serão carregados caso o de cima falhe. Caso todos falhem, criamos um parágrafo que permite o download do arquivo MP3 para ouvir no player padrão do dispositivo.  

## #C11A04 - Formatos de vídeo para seu site

### Que formatos são esses?
Vídeos possuem formatos e codecs e isso pode tornar o vídeo inviável de ser reproduzido pela maioria dos  navegadores na maioria dos dispositivos. É preciso prestar muita atenção nesse pequeno detalhe.

Os formatos suportados são MPEG, WEBM e OGG, mas os dois primeiros são os que possuem maior compatibilidade com os navegadores atualmente.  

**UM ÓTIMO CONVERSOR:** |
:-- |
Para gerar arquivos em vários formatos e usando codecs padronizados, recomendo usar o programa open source chamado [Handbrake](https://handbrake.fr/downloads.php), disponível para várias plataformas. |
Utilizei o site [Convertio](https://convertio.co/pt/mp4-ogv/) para gerar o formato *.ogv* |
 

> **Navegador** | **Arquivos compatíveis**
> :--: | :--:
> Microsoft Edge | .mp4 .m4v
> Apple Safari | .mp4 .m4v
> Google Chrome | .mp4 .m4v .webm .ogv
> Mozilla Firefox | .webm .ogv
> Opera | .webm .ogv

## #C11A05 - Vídeos em hospedagem própria
### E os vídeos
> página 7  

Para inserir um vídeo em nosso site, podemos utilizar a nova tag **`<video>`** da HTML5, ***caso o arquivo esteja hospedado no nosso próprio servidor***.
```html
<video width="500" poster="imagens/pinguin_capa.jpg" controls>
  <source src="midia/meu-video.mp4" type="video/mp4">
  <source src="midia/meu-video.m4v" type="video/mp4">
  <source src="midia/meu-video.webm" type="video/webm">
  <source src="midia/meu-video.ogv" type="video/ogg">
  <p>Infelizmente, seu navegador não tem compatibilidade com reprodução de vídeos.</p>
</video>
```
Antes de mais nada, vamos criar a tag `<video>` e configurar alguns atributos importantes:  
-  **`width`** vai indicar a largura que o vídeo vai ter na tela. Nesse exemplo, 600px.
- **`poster`** configura uma imagem que vai aparecer como uma capa, enquanto o visitante não aperta o play para reproduzir o vídeo.
- **`controls`** vai configurar se os controles de vídeo vão aparecer na parte inferior da mídia. Por padrão, os cotroles não aparecerão, mas basta colocar a palavra `controls` na tag `<video>`.
- **`autoplay`** diz para o navegador se o vídeo vai começãr a tocar automaticamente, assim que a página for carregada.

## #C11A06 - Incorporação de vídeo externo
> página 8
### Hospedar seus próprios vídeos pode ser caro
Quando colocamos vídeos no nosso próprio servidor, podemos passar por problemas com alto consumo de banda, site lento e incompatibilidades com alguns navegadores por conta dos codecs.
### E agora, quem poderá nos defender?
Euuuuuu! Ou melhor, o **YouTube** ou o **Vimeo**! Esses são serviços para a hospedagem de vídeos que vai evitar consumir nossos próprios recursos de host contratado.
### E dá pra incorporar com esses aí em HTML?
Para incorporar vídeos que você subiu no **YouTube** ou **Vimeo**, existem recursos que te dão o código pronto em HTML5.

- No **YouTube**, abra o vídeo que você quer incorporar e clique no link COMPARTILHAR que fica abaixo do título.

```html
<iframe width="480" height="270" src="https://www.youtube.com/embed/o73ABi-so6k?start=69" frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
</iframe>
```

- No **Vimeo**, o procedimento é bastante semelhante. Abra seu painel de controle do serviço e vá para a sua lista de vídeos hospedados. Na lista de mídias armazenadas, clique no botão com reticências e escolha a opção **Incorporação**.

```html
<iframe src="https://player.vimeo.com/video/191954993?portrait=0" width="480" height="270" frameborder="0"
    allow="autoplay; fullscreen; picture-in-picture" allowfullscreen>
</iframe>
```

O código HTML personalizado vai aparecer em uma nova janela de contexto, incluindo um botão que permite COPIAR o código com a tag do **`<iframe>`** que vai aparecer diretamente na sua página. Volte ao seu editor de código e cole a tag no seu arquivo HTML que vai apresentar o vídeo.

## #C11A07 - Desafios propostos
#### [Desafio 07 - desafio-desafio-imagem-flexivel](desafios\modulo-01\d007\pdf\desafio-imagem-flexivel.pdf)

#### [Desafio 08 - desafio-navegacao](desafios\modulo-01\d008\pdf\desafio-navegacao.pdf)

#### [Desafio 09 - desafio-videos](desafios\modulo-01\d009\pdf\desafio-videos.pdf)

## #C12A01 - Estilos CSS inline (HTML style)

> página 3

### A forma mais simples de aplicar estilo: CSS inline style

Essa é a técnica mais básica para aplicar estilos em áreas pontuais em nosso site, que é usando as **CSS dentro de parâmetros de HTML5**.

```html
<body>
  <h1>Capítulo 1</h1>
  <h2>Capítulo 1.1</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
  <h2>Capítulo 1.2</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
  <h1>Capítulo 2</h1>
  <h2>Capítulo 2.1</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
</body>
```

Vamos começar nos focando na tag `<body>` e aplicando um estilo diferente ao corpo da página. Adicione o parâmetro **`style`** e digite as duas declarações de `font-family` e `color`, conforme apresentado a seguir:

```html
<body style="font-family: Arial, Helvetica, sans-serif; color: blue;">
```
:warning: Atenção `&#xU+26A0;`|
--|
Tudo deve ser seguido exatamente como demostrado acima, inclusive com letras maiúsclas e minúsculas. Não esquecendo os **ponto e vírgula** para separar as declarações|

:warning: CUIDADO!|
--|
A tag `<font color="blue">` ***NÃO É MAIS ACEITA*** para as especificações da HTML5!|

Vamos fazer mais uma alteração, dessa vez na linha do primeiro título `<h1>` do nosso código:
```html
<h1 style="color: Red;">Capítulo 1<h1>
```

Note que apenas o Capítulo 1 ficou vermelho, o Capítulo 2 - que também é um `<h1>` - não teve alteração alguma. Isso acontece pois estamos fazendo **configurações pontuais** usando CSS.

## #C12A02 - Estilos CSS Internos (CSS style)

### Estilizando de maneira mais interessante: CSS Internal Style

> Página 6
Para aplicar estilos de forma mais dinâmica e prática, podemos adicionar uma tag **`<style>`** dentro da área **`<head>`** do nosso documento HTML local.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estilos Locais / Internos</title>
    <style>
        body {
            background-color: lightsteelblue;
            font-family: Arial, Helvetica, sans-serif;
            color: blue;
        }
        
        h1 {
            color: green;
        }
    </style>
</head>
```
:warning: **Atenção!** |
--|
A tag `<style>` deve ser dentro da área `<head>` do seu documento HTML5. Se você colocá-la em qualquer outro local, como dentro da tag `<body>`, o resultado até pode funcionar, mas seu código estará fora dos padrões estabelecidos pela W3C. Siga sempre as regras!|

> **As configurações pontuais (HTML style) vão prevalecer sobre as configurações gerais (CSS style)**

## #C12A03 - Estilos CSS externos

### A técnica mais versátil: CSS external style

> página 7

Manter as folha de estilo fora do código HTML, além de uma maior organização faz com que tudo seja reaproveitado de maneira mais eficiente nas outras páginas do nosso site. Para isso, utilizamos a tag **`<link>`** especialmente configurada para trabalhar com arquivos externos de estilo. Essa tag deve ser colocada dentro da área `<head>` do seu documento HTML.

```html
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device=width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>CSS External</title>
  </head>
</html>
```

**A linha como o `<link>` pode estar em qualquer linha, contanto que seja dentro da área `<head>`.** Particularmente, sempre procuro adicionar essa configuração após a tag `<tilte>` do documento atual.

Após inserir a linha de código do `link:css`, você observará que ao passar o mouse sobre o nome do arquivo **`style.css`**, existe um atalho *"Siga o link"* clicando sobre o link, o VSCode vai perguntar se você quer que ele crie o arquivo para você. Clique em **Sim** ou **Ok** para aceitar a ajuda e seu aruqivo será criado automaticamente.

Agora é só adicionar os seletores e todas as suas respectivas declarações nesse arquivo separado para que elas possam ser aplicadas ao documento que contiver um **`<link>`** para ele.

```css
@charset "UTF-8";
/* Regra @charset caso haja problemas com acentuação */

body {
    background-color: lightgoldenrodyellow;
    color: chocolate;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
}

h1 {
    color: maroon;
    background-color: goldenrod;
}

a {
    color: brown;
    text-decoration: none;
}
```

Na **linha 1**, colocamos uma **regra** em CSS, que vai indicar a compatibilidade de codificação com o padráo UTF-8, assim como fizemos com o arquivo HTML5. Essa linha não é obrigatória e normalmente nem vai aparecer na maioria dos seus arquivos de configurações de estilo, mas saiba que ela existe.

Na **linha 2**, adicionamos um **comentário** para facilitar a documentação do arquivo. Os comentários - assim como vimos em HTML - só servirão de explicação para que o desenvolvedor entenda o funcionamento de uma determinada linha ou trecho de código. O navegador não vai considerar nada que está entre os símbolos `/*` e `*/` em CSS.

Nas demais linhas, fizemos as configurações dos seletores, da mesma maneira que criamos com as outras duas técnicas apresentadas no capítulo.

### Qual técnica eu escolho para usar?

Nesse capítulo, aprendemos as três técnicas de uso de folhas de estilo em cascata: **inline**, **interna** e **externa**. Mas em que situação devemos escolher cada um dos formatos?

De forma resumida, para fixar na cabeça:

Tipo | Descrição | Ordem de precedência
:--:|:--:|:--:
CSS **externo** | use sempre que puder | 3
CSS **interno** | use para pequenas configurações | 2
CSS **inline**  | procure evitar | 1

Ainda é possível misturar as três técnicas, criando um CSS exteno para as cofigurações globais, CSS interno para a s configurações locais de um documento e CSS inline para pequenas configurações pontuais.

# Módulo 02 | Deixando as coisas mais bonitas

> Resumo

* Fundamentos do design
* psicologia das cores
* tipografia
* elementos CSS
* modelo de caixas
* wireframe
* responsividade

# Módulo 03 | Colocando um protótipo no ar

> Resumo

* Versionamento de software
* hospedagem de sites estáticos
* tabelas

# Módulo 04 | Aprofundando os conhecimentos

> Resumo

* Quadros em linha
* formulários
* media queries
* mobile first

# Módulo 05 | Novas tecnologias

> Resumo

* Flexbox
* Grid Layout
* projeto final