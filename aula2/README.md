# CSS

# Unidades de medida

O CSS permite o uso de uma grande variedade de unidades de medida, que servem para definir
a dimensão dos mais diversos elementos (largura de bordas de tabela, tamanho de fonte etc.).
A seguir, serão listadas as unidades de medida válidas no CSS.

| Unidade de medida| Descrição   
|--|--|                                                                                                                                               
|% |Indica valor percentual.|
|in|Indica valor em polegadas.|    
|cm|Indica valor em centímetros.|   
|mm|Indica valor em milímetros.|  
|em|1em equivale ao tamanho atual de uma fonte.|
|ex|Um ex equivale à medida x-height de uma fonte.|   
|pt|Indica valor em pontos (1pt = 1/72in). |
|pc|Indica valor em picas (1pc = 12pt).|
|px|Indica valor em pixels.|

# Background

| Atributo | Descrição | Valores suportados |
| --- | --- | --- |
| background-color | Define a cor de fundo | nome da cor ou código hexadecimal |
| background-image | Define a imagem de fundo | url('caminho/para/imagem') |
| background-repeat | Define como a imagem de fundo se repete | repeat, repeat-x, repeat-y, no-repeat |
| background-position | Define a posição inicial da imagem de fundo | left top, left center, left bottom, right top, right center, right bottom, center top, center center, center bottom, x% y%, xpos ypos |
| background-size | Define o tamanho da imagem de fundo | auto, cover, contain, largura altura |
| background-attachment | Define se a imagem de fundo é fixa ou rola com a página | fixed, scroll, local |

# Textos
| Atributo | Descrição | Valores suportados |
| --- | --- | --- |
| color | Define a cor do texto | Cor em hexadecimal, RGB, RGBA, nome da cor |
| font-family | Define a família de fonte do texto | Nome da fonte, fonte genérica |
| font-size | Define o tamanho da fonte | Valor em pixels (px), em pontos (pt), em ems (em), em porcentagem (%), em viewport width (vw) |
| font-weight | Define a espessura da fonte | Números de 100 a 900, palavras-chave `normal` e `bold` |
| font-style | Define o estilo da fonte | Palavras-chave `normal`, `italic` e `oblique` |
| text-align | Define o alinhamento do texto | Palavras-chave `left`, `right`, `center`, `justify` |
| text-decoration | Define a decoração do texto | Palavras-chave `none`, `underline`, `overline`, `line-through`, `blink` |
| text-transform | Transforma o texto em maiúsculo, minúsculo ou capitalizado | Palavras-chave `none`, `uppercase`, `lowercase`, `capitalize` |
| line-height | Define a altura da linha de texto | Valor em pixels (px), em ems (em), em porcentagem (%) |
| letter-spacing | Define o espaçamento entre caracteres | Valor em pixels (px), ems (em) |
| word-spacing | Define o espaçamento entre palavras | Valor em pixels (px), ems (em) |
| white-space | Define como o espaçamento em branco é tratado | Palavras-chave `normal`, `nowrap`, `pre`, `pre-wrap`, `pre-line` |

# Fontes
| Atributo | Descrição | Valores Suportados |
| --- | --- | --- |
| font-family | Define a família da fonte | nome da fonte, fontes genéricas |
| font-size | Define o tamanho da fonte | unidades de comprimento, porcentagem, tamanho absoluto |
| font-style | Define o estilo da fonte | normal, italic, oblique |
| font-weight | Define a espessura da fonte | normal, bold, bolder, lighter, 100-900 |
| font-variant | Define a variante da fonte | normal, small-caps |
| font-stretch | Define a largura da fonte | normal, condensed, expanded |
| font-size-adjust | Define a largura da fonte relativa a uma fonte alternativa | número |
| line-height | Define a altura da linha de texto | unidades de comprimento, número, porcentagem |
| font | Define todas as propriedades de fonte em uma única declaração | estilo, variante, peso, tamanho, família |

*Nota:* Os valores suportados para font-family incluem o nome da fonte (por exemplo, Arial), fontes genéricas (por exemplo, serif, sans-serif, monospace) e fontes externas que são referenciadas usando @font-face. Os valores suportados para font-size incluem unidades de comprimento (por exemplo, px, em, rem), porcentagem, tamanhos absolutos (por exemplo, medium, x-large) e tamanhos relativos (por exemplo, larger, smaller).

# Bordas
| Atributo | Descrição | Valores suportados |
| --- | --- | --- |
| border | Define a borda de um elemento | `width`, `style`, `color` |
| border-width | Define a largura da borda | `thin`, `medium`, `thick`, `<valor>` |
| border-style | Define o estilo da borda | `none`, `hidden`, `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset` |
| border-color | Define a cor da borda | `<nome da cor>`, `<valor RGB>`, `transparent` |
| border-top | Define a borda superior de um elemento | `width`, `style`, `color` |
| border-top-width | Define a largura da borda superior | `thin`, `medium`, `thick`, `<valor>` |
| border-top-style | Define o estilo da borda superior | `none`, `hidden`, `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset` |
| border-top-color | Define a cor da borda superior | `<nome da cor>`, `<valor RGB>`, `transparent` |
| border-right | Define a borda direita de um elemento | `width`, `style`, `color` |
| border-right-width | Define a largura da borda direita | `thin`, `medium`, `thick`, `<valor>` |
| border-right-style | Define o estilo da borda direita | `none`, `hidden`, `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset` |
| border-right-color | Define a cor da borda direita | `<nome da cor>`, `<valor RGB>`, `transparent` |
| border-bottom | Define a borda inferior de um elemento | `width`, `style`, `color` |
| border-bottom-width | Define a largura da borda inferior | `thin`, `medium`, `thick`, `<valor>` |
| border-bottom-style | Define o estilo da borda inferior | `none`, `hidden`, `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset` |
| border-bottom-color | Define a cor da borda inferior | `<nome da cor>`, `<valor RGB>`, `transparent` |
| border-left | Define a borda esquerda de um elemento | `width`, `style`, `color` |
| border-left-width | Define a largura da borda esquerda | `thin`, `medium`, `thick`, `<valor>` |
| border-left-style | Define o estilo da borda esquerda | `none`, `hidden`, `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset` |
| border-left-color | Define a cor da borda esquerda | `<nome da cor>`, `<valor RGB>`, `transparent` |

# Margens

```css
/* Aplica para todos os quatro lados */
margin: 1em;

/* vertical | horizontal */
margin: 5% auto;

/* topo | horizontal | inferior */
margin: 1em auto 2em;

/* topo | direita | inferior | esquerda */
margin: 2px 1em 0 auto;

/* Valores globais */
margin: inherit;
margin: initial;
margin: unset;
```
| Atributo | Descrição | Valores Suportados |
| --- | --- | --- |
| margin | Define o espaçamento externo de todos os lados do elemento | `auto`, `length`, `%%` |
| margin-top | Define o espaçamento externo superior do elemento | `auto`, `length`, `%%` |
| margin-right | Define o espaçamento externo direito do elemento | `auto`, `length`, `%%` |
| margin-bottom | Define o espaçamento externo inferior do elemento | `auto`, `length`, `%%` |
| margin-left | Define o espaçamento externo esquerdo do elemento | `auto`, `length`, `%%` |
| margin-collapse | Especifica como mesclar as margens adjacentes | `collapse`, `separate` |
| margin-inline | Define a margem horizontal (esquerda e direita) em elementos inline | `auto`, `length`, `%%` |
| margin-inline-end | Define a margem à direita ou esquerda de um elemento inline dependendo da direção do texto | `auto`, `length`, `%%` |
| margin-inline-start | Define a margem à direita ou esquerda de um elemento inline dependendo da direção do texto | `auto`, `length`, `%%` |
| gap | Define a distância entre as linhas de grade em um layout de grade | `length`, `%%`, `normal` |
