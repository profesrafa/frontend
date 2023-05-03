# Tópicos de HTML5

[Estrutura básica](https://github.com/profesrafa/frontend/tree/main/aula1#estrutura-básica)

[Tags marcadoras de texto](https://github.com/profesrafa/frontend/tree/main/aula1#tags-marcadoras-de-texto)

[Exibindo imagens](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#exibindo-imagens)

[Criando links](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#criando-links)

[Tabelas](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#tabelas)

[Exemplo de div e span](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#exemplo-de-div-e-span)

[Formulários](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#formul%C3%A1rios)
 - [Listas suspensas](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#listas-suspensas)
 - [Caixas de texto](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#caixas-de-texto)
 - [Campos de texto](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#campos-de-texto)
 - [Botões tipo rádio](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#bot%C3%B5es-tipo-r%C3%A1dio)
 - [Elementos tipo check box](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#elementos-tipo-check-box)
 - [Botões](https://github.com/profesrafa/frontend/blob/main/aula1/README.md#bot%C3%B5es)

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
## Tags marcadoras de texto

O uso das tags abaixo passa a ter sentido ao complementar-se a página usando a linguagem CSS. Mediante seu uso, podemos definir exatamente como queremos que nossa página seja vista, por exemplo, todas as citações (tags tipo quote).

| Tag | Descrição | 
| --- | --- |
| `<i>` | Define um texto em itálico.|
| `<em>` | Define um texto em ênfase.|
| `<u>` | Define um texto sublinhado.|
| `<small>` | Define um texto de menor tamanho.|
| `<sub>` | Define um texto tipo subíndice (aparece mais abaixo e em menor tamanho).|
| `<sup>` | Define um texto sobrescrito (aparece mais acima e em tamanho menor).|
| `<ins>` | Define um texto inserido (geralmente equivale ao sublinhado).|
| `<do>` | Define um texto eliminado (geralmente se mostra tachado).|
| `<code>` | Define uma porção de texto tipo programa.|
| `<kbd>` | Define uma entrada de texto a partir do teclado (igual ao anterior).|
| `<samp>` | Define um exemplo (igual ao anterior).|
| `<var>` | Define uma variável (usualmente em itálico).|
| `<pre>` | Define um texto pré-formatado (usualmente respeita os espaços em branco).|
| `<abbr>` | Define uma abreviatura.|
| `<address>` | Define um endereço pessoal.|
| `<bdo>` | Define a direção do texto (direita a esquerda o vice-versa).|
| `<blockquote>` | Define uma seção que corresponde a uma cita de outro texto (altera os margens).|
| `<q>` | Define uma citação de uma ou poucas palavras.|
| `<cite>` | Define uma citação de, por exemplo, um título de uma obra.|
| `<dfn>` | Destaca uma definição (usualmente se faz em itálico).| 


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



## Tabelas

Para criar tabelas de forma fácil e rápido use o site [Tables Generator](https://www.tablesgenerator.com/html_tables).
Para mais informações consulte o site [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/table).

| Atributo   | Descrição   | Exemplo  |
|---|---|---|
| `align` | Especifica a posição horizontal do conteúdo da tabela em relação à margem esquerda ou direita da página. | `<table align="center">` |
| `bgcolor` | Define a cor de fundo da tabela. | `<table bgcolor="#f2f2f2">` |
| `border` | Define a largura das bordas da tabela. | `<table border="1">` |
| `cellpadding` | Define a quantidade de espaço em pixels entre o conteúdo da célula e sua borda interna. | `<table cellpadding="5">` |
| `cellspacing` | Define a quantidade de espaço em pixels entre as células da tabela. | `<table cellspacing="2">` |
| `frame` | Define se as bordas da tabela devem ser exibidas ou não. | `<table frame="void">` |
| `rules` | Define a exibição das bordas internas da tabela. | `<table rules="all">` |
| `summary` | Fornece uma breve descrição da tabela. | `<table summary="Esta tabela apresenta os resultados da pesquisa">` |
| `width` | Define a largura da tabela em pixels ou em porcentagem da largura da página. | `<table width="80%">` |


## Exemplo de div e span

```html
<!DOCTYPE html>
<html>
<head>
 <title>Exemplo de div e span</title>
</head>
<body>
<!-- Exemplo de um código CSS dentro do HTML -->
<style>
    #cabecalho{
        background-color: #cccccc;
        width: 600px;
        padding: 40px 2%;
        color: white;
        text-align: center;
    }
    #corpo{
        background-color: red;
        width: 600px;
        padding: 10px 2%;
    }
    #rodape{
        width: 600px;
        padding: 10px 2%;
        background-color: #888888;
        color: white;
        text-align: center;
    }
    .sessao_conteudo{
        text-align: center;
        width: 100%;
        background-color: green;
    }
</style>
  <div id="cabecalho">
    <h2>Meu documento sobre div HTML</h2>
  </div>
  <div id="corpo">
    <div class="sessao_conteudo">
        <h3>Meu conteúdo 01</h3>
          <p>Meu parágrafo contendo texto 1 </p>
          <p>Meu parágrafo contendo texto 2 </p>
    </div>
    <div class="sessao_conteudo">
        <h3>Meu conteúdo 02</h3>
        <p>Meu parágrafo contendo texto 1 </p>
        <p>Meu parágrafo contendo texto 2 </p>
    </div>    
</div>
<span>meu span 1 </span>
<span>meu span 2 </span>
<div>minha div 1</div>
<div>minha div 2</div>
<div id="rodape">
   <p>Todos os direitos reservados</p>
</div>
</body>
</html>
```

## Formulários

Segue  abaixo a tabela com alguns atributos do `<form>`. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/form).

| Atributo  | Descrição | Exemplo |
| --- | --- | --- |
| action | Especifica o URL para onde os dados do formulário serão enviados quando o formulário for submetido. | `<form action="https://www.example.com/submit-form" method="post"></form>` |
| method | Especifica o método de envio dos dados do formulário. Os valores aceitos são "get" e "post". | `<form action="https://www.example.com/submit-form" method="post"></form>` |
| autocomplete | Especifica se o autocomplete dos campos do formulário está ativado ou desativado. Os valores aceitos são "on" e "off". | `<form action="https://www.example.com/submit-form" method="post" autocomplete="on"></form>` |
| enctype | Especifica o tipo de codificação a ser usada para os dados do formulário. Os valores aceitos são "application/x-www-form-urlencoded", "multipart/form-data" e "text/plain". | `<form action="https://www.example.com/submit-form" method="post" enctype="multipart/form-data"></form>` |
| name | Especifica um nome para o formulário. | `<form action="https://www.example.com/submit-form" method="post" name="my-form"></form>` |
| novalidate | Especifica que o formulário não deve ser validado quando for submetido. | `<form action="https://www.example.com/submit-form" method="post" novalidate></form>` |
| target | Especifica onde exibir a resposta após o envio do formulário. Os valores aceitos são "_self", "_blank", "_parent" e "_top". | `<form action="https://www.example.com/submit-form" method="post" target="_blank"></form>` |
| accept-charset | Especifica o conjunto de caracteres que será usado para codificar os dados do formulário. | `<form action="https://www.example.com/submit-form" method="post" accept-charset="UTF-8"></form>` |
| class | Especifica uma ou mais classes CSS para o elemento do formulário. | `<form action="https://www.example.com/submit-form" method="post" class="my-form"></form>` |
| id | Especifica um ID único para o elemento do formulário. | `<form action="https://www.example.com/submit-form" method="post" id="form1"></form>` |

### Listas suspensas

Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo</title>
</head>
<body>
 <form name="formulário">
      Selecione um valor:
<select name="valores">
  <option value="valor1">Valor 1</option>
  <option value="valor2" selected>Valor 2</option>
  <option value="valor3">Valor 3</option>
</select>
  </form>
</body>
</html>
```
Segue  abaixo a tabela com alguns atributos do `<select>`. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/select).

| Atributo | Descrição | Exemplo |
| --- | --- | --- |
| name | Define um nome para o elemento | `<select name="frutas">` |
| autofocus | Especifica que o elemento deve receber o foco automaticamente quando a página é carregada | `<select autofocus>` |
| disabled | Desativa o elemento para impedir que ele seja selecionado ou submetido | `<select disabled>` |
| form | Especifica o formulário ao qual o elemento pertence | `<select form="formulario">` |
| multiple | Permite que o usuário selecione múltiplas opções | `<select multiple>` |
| required | Especifica que o elemento é obrigatório e não pode ser submetido sem uma seleção | `<select required>` |
| size | Define o número de opções visíveis em um menu suspenso | `<select size="3">` |
| formaction | Especifica o URL de destino para o formulário quando o elemento é submetido | `<select formaction="/enviar.php">` |
| formenctype | Especifica o tipo de codificação de caracteres usado para enviar dados do formulário | `<select formenctype="multipart/form-data">` |
| formmethod | Especifica o método HTTP usado para enviar dados do formulário | `<select formmethod="post">` |
| formtarget | Especifica o destino da resposta do servidor ao enviar dados do formulário | `<select formtarget="_blank">` |

### Caixas de texto
Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo de Campos de text</title>
</head>
<body>
<form name=”formulário”>
<textarea name="textarea"
   rows="10" cols="50"> Escreva alguma coisa aqui! </textarea>
<form>
</body>
</html>
```
Segue  abaixo a tabela com alguns atributos do `<textarea>`. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/textarea).



| Atributo | Descrição | Exemplo |
| -------- | --------- | ------- |
| cols | Define o número de colunas visíveis em uma caixa de texto | `<textarea cols="50"></textarea>` |
| rows | Define o número de linhas visíveis em uma caixa de texto | `<textarea rows="10"></textarea>` |
| name | Define o nome da caixa de texto | `<textarea name="mensagem"></textarea>` |
| required | Define que a caixa de texto é obrigatória em um formulário | `<textarea required></textarea>` |
| disabled | Define que a caixa de texto deve ser desativada | `<textarea disabled></textarea>` |
| readonly | Define que a caixa de texto não pode ser editada | `<textarea readonly></textarea>` |
| autofocus | Define que a caixa de texto deve ter foco automaticamente ao carregar a página | `<textarea autofocus></textarea>` |
| placeholder | Define um texto de instrução que aparece dentro da caixa de texto | `<textarea placeholder="Digite sua mensagem"></textarea>` |
| form | Define o ID do formulário a que a caixa de texto pertence | `<textarea form="form-mensagem"></textarea>` |
| maxlength | Define o número máximo de caracteres que podem ser inseridos na caixa de texto | `<textarea maxlength="100"></textarea>` |

### Campos de texto
Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo de Campos de texto</title>
</head>
<body>
 <form name=”formulário”>
  <input type=”text” />
 </form>
</body>
</html>
```

#### Campos de texto oculto (password)
Estrutura básica
```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo de Campos de texto</title>
</head>
<body>
 <form name=”formulário”>
   Senha: <input type=”password” /><br>
 </form>
</body>
</html>
```

#### Campos de texto invisíveis
Estrutura básica
```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo de Campos de texto</title>
</head>
<body>
 <form name=”formulário”>
   Senha: <input type=”hidden” /><br>
 </form>
</body>
</html>
```

Segue  abaixo a tabela com alguns atributos do `<input>`. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input).

| Atributo | Descrição | Exemplo |
| -------- | --------- | ------- |
| type | Especifica o tipo de input | `<input type="text">` |
| name | Define o nome do input | `<input type="text" name="username">` |
| value | Define o valor padrão do input | `<input type="checkbox" value="sim">` |
| checked | Define se o input do tipo checkbox ou radio está selecionado | `<input type="radio" checked>` |
| placeholder | Define uma mensagem de ajuda dentro do input | `<input type="text" placeholder="Digite seu nome">` |
| required | Define se o input é obrigatório | `<input type="text" required>` |
| disabled | Define se o input está desabilitado | `<input type="text" disabled>` |
| readonly | Define se o input é somente leitura | `<input type="text" readonly>` |
| size | Define a largura do input em caracteres | `<input type="text" size="20">` |
| maxlength | Define o número máximo de caracteres permitidos no input | `<input type="text" maxlength="10">` |
| minlength | Define o número mínimo de caracteres permitidos no input | `<input type="text" minlength="2">` |
| pattern | Define uma expressão regular para validar o input | `<input type="text" pattern="[A-Za-z]+">` |
| autofocus | Define se o input recebe o foco automaticamente ao carregar a página | `<input type="text" autofocus>` |
| form | Define o ID do formulário ao qual o input pertence | `<input type="text" form="form_id">` |
| autocomplete | Define se o input deve ser autocompletado pelo navegador | `<input type="text" autocomplete="on">` |

### Botões tipo rádio
Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo</title>
</head>
<body>

</body>
</html>
```
Segue  abaixo a tabela com alguns atributos do `<textarea>`. Para uma referência mais completa consulte o site  [developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/).
### Elementos tipo check box
Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo</title>
</head>
<body>

</body>
</html>
```
### Botões
Estrutura básica

```html
<!DOCTYPE html>
<html lang=”pt-br”>
<head>
  <meta charset="utf-8">
 <title>Exemplo</title>
</head>
<body>

</body>
</html>
```
#### Botão
