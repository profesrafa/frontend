# Tópicos de HTML5

[Estrutura básica](https://github.com/profesrafa/frontend/tree/main/aula1#estrutura-básica)

[Exibindo imagens](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#exibindo-imagens)

[Criando links](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#criando-links)

[Tags marcadoras de texto](https://github.com/profesrafa/frontend/tree/main/aula1#tags-marcadoras-de-texto)

## Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo</title>
 <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
 <h1>Bem-vindo ao meu site!</h1>
 <p>Este é um exemplo de um site simples.</p>
 <img src="imagem.jpg" alt="Imagem de exemplo">
</body>
</html>
``` 
## Exibindo imagens

Estrutura básica
```html
<figure>
  <img src="imagem.jpg" alt="Minha Figura">
  <figcaption>Informações da Figura</figcaption>
</figure>
```

Segue  abaixo a tabela com alguns atributos. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img#exemplo_da_implementa%C3%A7%C3%A3o_do_html5).

| Atributo | Descrição | Exemplo |
| --- | --- | --- |
| `alt` | Especifica o texto alternativo para uma imagem, quando ela não pode ser exibida | `<img src="imagem.jpg" alt="Descrição da imagem">` |
| `src` | Especifica o URL da imagem | `<img src="imagem.jpg">` |
| `width` | Especifica a largura da imagem em pixels | `<img src="imagem.jpg" width="300">` |
| `height` | Especifica a altura da imagem em pixels | `<img src="imagem.jpg" height="200">` |
| `title` | Especifica o título da imagem (quando o usuário passa o mouse sobre ela) | `<img src="imagem.jpg" title="Título da imagem">` |
| `loading` | Especifica quando a imagem deve ser carregada | `<img src="imagem.jpg" loading="lazy">` |
| `sizes` | Especifica tamanhos de imagem para diferentes dispositivos | `<img srcset="imagem-300.jpg 300w, imagem-600.jpg 600w" sizes="(max-width: 768px) 100vw, 50vw">` |
| `srcset` | Especifica vários arquivos de imagem para diferentes resoluções de tela | `<img srcset="imagem-300.jpg 300w, imagem-600.jpg 600w" sizes="(max-width: 768px) 100vw, 50vw" src="imagem.jpg">` |
| `decoding` | Especifica como o navegador deve decodificar a imagem | `<img src="imagem.jpg" decoding="async">` |
| `crossorigin` | Especifica se a requisição da imagem deve ter o atributo `cross-origin` | `<img src="imagem.jpg" crossorigin="anonymous">` |
| `usemap` | Especifica a imagem como um mapa de imagem e vincula um mapa de imagem a ela | `<img src="imagem.jpg" usemap="#mapa">` |
| `ismap` | Especifica que a imagem é um mapa de imagem | `<img src="imagem.jpg" ismap>` |
| `referrerpolicy` | Especifica a política de referenciamento para a imagem | `<img src="imagem.jpg" referrerpolicy="no-referrer">` |


## Criando links

Estrutura básica
```html
<a href="https://www.google.com">Google</a>
```

Segue  abaixo a tabela com alguns atributos. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/a).



| Atributo  | Descrição  | Exemplo |
|---|---|---|
| `href`  | Especifica o destino do link  | `<a href="https://www.google.com">Google</a>`  |
| `target`  | Especifica onde abrir o link  | `<a href="https://www.google.com" target="_blank">Google</a>`  |
| `download`  | Especifica que o link é para ser baixado  | `<a href="/imagens/imagem.png" download>Download da imagem</a>`  |
| `rel`  | Especifica a relação do link com a página atual  | `<a href="https://www.instagram.com" rel="nofollow">Instagram</a>`  |
| `hreflang`  | Especifica o idioma do destino do link  | `<a href="https://www.google.com" hreflang="en">Google</a>`  |
| `type`  | Especifica o tipo de mídia do destino do link  | `<a href="/audio/audio.mp3" type="audio/mpeg">Reproduzir áudio</a>`  |
| `referrerpolicy`  | Especifica a política de referência para informações confidenciais  | `<a href="https://www.google.com" referrerpolicy="origin">Google</a>`  |
| `ping`  | Especifica uma lista de URLs para receber notificações quando o link for seguido  | `<a href="https://www.google.com" ping="/analytics.php">Google</a>`  |
| `media`  | Especifica a mídia a qual a mídia relacionada é adaptada  | `<a href="/imagens/imagem.png" media="(max-width: 600px)">Imagem para dispositivos móveis</a>`  |
| `crossorigin`  | Especifica como as requisições são feitas quando a página de origem e a página de destino possuem origens diferentes  | `<a href="https://www.google.com" crossorigin="anonymous">Google</a>`  |
| `relList`  | Especifica a relação do link com a página atual, de forma programática  | `<a href="https://www.instagram.com" relList="nofollow">Instagram</a>`  |
| `downloadHint`  | Especifica sugestões para o nome do arquivo quando o link é baixado  | `<a href="/imagens/imagem.png" download downloadHint="imagem-1.png">Download da imagem</a>`  |

## Tags marcadoras de texto

O uso das tags abaixo passa a ter sentido ao complementar-se a página usando a linguagem CSS. Mediante seu uso, podemos definir exatamente como queremos que nossa página seja vista, por exemplo, todas as citações (tags tipo quote).


```html

 <i> Define um texto em itálico.
 
 <em> Define um texto em ênfase.
 
 <u> Define um texto sublinhado.
 
 <small> Define um texto de menor tamanho.
 
 <sub> Define um texto tipo subíndice (aparece mais abaixo e em menor tamanho).
 
 <sup> Define um texto sobrescrito (aparece mais acima e em tamanho menor).
 
 <ins> Define um texto inserido (geralmente equivale ao sublinhado).
 
 <do> Define um texto eliminado (geralmente se mostra tachado).
 
 <code> Define uma porção de texto tipo programa.
 
 <kbd> Define uma entrada de texto a partir do teclado (igual ao anterior).
 
 <samp> Define um exemplo (igual ao anterior).
 
 <var> Define uma variável (usualmente em itálico).
 
 <pre> Define um texto pré-formatado (usualmente respeita os espaços em branco).
 
 <abbr> Define uma abreviatura.

 <address> Define um endereço pessoal.
 
 <bdo> Define a direção do texto (direita a esquerda o vice-versa).
 
 <blockquote> Define uma seção que corresponde a uma cita de outro texto (altera os margens).
 
 <q> Define uma citação de uma ou poucas palavras.
 
 <cite> Define uma citação de, por exemplo, um título de uma obra.
 
 <dfn> Destaca uma definição (usualmente se faz em itálico).
```
