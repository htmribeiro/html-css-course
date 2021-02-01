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
- \<b> que colocava um texto em negrito
- \<u> que colocava o termo sublinhado
- \<blink> que fazia o texto piscar  

Essas eram tags que representavam apenas uma **forma**.
> Exemplo:
>*`"Juvenal era um sujeito de muita sorte. E já começou de pequeno, onde morou na \<u>Rua Marquês de Lira Filho\</u>, um local de fácil acesso ao Centro da cidade."`*  

Essa seria uma maneira de determinar somente um formato visual para chamar atenção para o endereço onde o cara nasceu. O sublinhado é apenas uma **forma**, sem **significado** explícito.  
</br>

Já a HTML5 chegou com o conceito de valorizar a **semântica**, logo suas tags tentam levar um **significado** embutido muito forte.
> Exemplo:
>*`"Juvenal era um sujeito de muita sorte. E já começou de pequeno, onde morou na \<address>Rua Marquês de Lira Filho\</address>, um local de fácil acesso ao Centro da cidade."`*  

Note que agora, usamos a tag `<address>` para dar um **significado** ao destaque que fizemos.  
</br>

Sendo assim, em HTML5, vemos de forma bastante evidênte a presença do chamado **HTML semântico** ou **tags semânticas** ou ainda o **conteúdo semântico**.  

> **O intuito é deixar a apresentação gráfica por conta das CSS.**


# modulo02
# modulo03
# modulo04
# modulo05
# modulo06
# modulo07
# modulo08
# modulo09
# modulo10
# modulo11
# modulo12
# modulo13