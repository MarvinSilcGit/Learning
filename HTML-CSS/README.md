<details>
  
  <summary><h2>Charpter 2: Intro to Semantics</h2></summary>

### Intro to Semantics

<p style="text-align: justify">Escrever HTML semântico significa dar significado para os elementos que nós usamos. Isso permite você focar no propósito do elemente ao invés de sua aparência. Semântica foca em fornecer significado e propósito para os elementos que você usa.</p>

<br>

### Intro to Headings

<p style ="text-align: justify">O elemento cabeçalho h1 é usado para representa o tópico de mais alta importância em uma página web. Ao escrever código HTML, é importante focar na semântica ao invés da aparencia. HTML é feito para o conteúdo, enquanto que o CSS é usado para estilizar o conteúdo.</p>

</details>

<details>
  <summary><h2>Chapter 3: Intro to Acceessibility</h2></summary>

  ### Intro to Accessibility

  <p style ="text-align: justify">No contexto do HTML, acessibilidade se refere a fazer seu site usável por todo mundo. Quando você escrever seu código de acessibilidade, seu eu do futuro irá te agradecer. Nós estamos escrevendo websites que nós iremos usar daqui alguns anos. Nossa extensão de habilidades pode muito bem mudar em poucos anos.</p>

<br>

### Headings and Accesibility

<p style ="text-align: justify">Leitor de tela é um software que tem comandos para rapidamente pular entre cabeçalhos ou regiões referenciais específicas. Isso faz com que seja essencial ter cabeçalhos siginificativos. Isso ajuda ususários com tecnologias assistivas facilmente navegar e explorar sua página. Note que isso não é o único benefício de ter cabeçalhos siginicativos. Há muito mais benefícios no que diz respeito a SEO.</p>
  
</details>

<details>
  <summary><h2>Chapter 4: Headings deep dive</h2></summary>

  ### H1 e H2

  <p style ="text-align: justify">O elemento h2 é usado para definir títulos da principais seções de uma página web. O elemente h2 é uma subseção do elemento h1. É importante pensar nos elementos h1 e h2 como um rascunho de um livro. O h1 é o título da página e os elementos h2 são os capítulos. Nós estamos levando um tempo e focando nos pequenos detalhes porque é muito importante usar h1 e h2 baseado na hierarquia no documento ao invés do tamanho da fonte. Utilize somente um h1 por página, pois o h1 é o principal</p>

<br>

### H3, H4, H5 and H6

<p style ="text-align: justify">Nós já aprendemos sobre h1 e h2. Similarmente para como h2 se relaciona com h1: o elemento h3 é uma subseção de h2, h4 é uma subseção de 3, h5 é uma subseção de h4 e h6 é uma subseção de h5. É importante evitar pular níveis de cabeçalhos. Se você tem um h1, o cabeçalho a seguir deverá ser h2. Você não deve pular h2 e ir direto para h3. O mesmo se aplica aos outros cabeçalhos.</p>

<br>

### Headings and SEO

<p style ="text-align: justify">SEO (Search Engine Optimization) é a prática de aprimorar a qualidade de seu website de modo a adquirir mais visitantes advindos dos motores de busca. Cabeçalhos teem uma função importante em SE, pois você está comunicndo para o motor de busca o rascunho da página e o tópico mais importante.</p>
</details>

<details>
  <summary><h2>Chapter 5: Boilerplate</h2></summary>

  ### What is an attribute?

  <p style ="text-align: justify">Todo elemento html pode ter um ou mais pares de <code>chave="valor"</code> que permite você customizar ou configurar o comportamento do elemento. Os pares <code>chave="valor" são chamados de atributos.</code></p>
  
```html
<html lang ="pt-br">

</html>
```

<p style ="text-align: justify">O <code>lang</code> é chamado de chave e o <code>"pt-br"</code> é chamado de valor. As aspas são necessárias para diferenciar atributos de outros e não gerar problemas inesperados. Observe abaixo que o elemento <code>meta</code> possui 2 atributos: <code>name ="viewport" content ="width=device.width, initial-scale=1.0"</code></p>

```html
<meta name ="viewport" content ="width=device-width, initial-scale=1.0">
```

<br>

### The doctype

```html
<!DOCTYPE html>
```

<p>Especifica a versão do html que o navegador irá renderizar. Nesse caos, HTML 5</p>

<br>

### The html element

<p style ="text-align: justify">O elemento html é o elemento raiz de toda página html. A partir dele, todos os outros elementos são criados. Esse elemento possui dois elementos filho, <code>head</code> e <code>body</code>.</p>

<br>

### The head element

<p style ="text-align: justify">O elemento <code>head</code> contém informação e dados que serão processados pelo navegador e motores de busca. O conteúdo dentro dessa tag não é exibido na página, mas pode afetar o comportamento visual dela.</p>

<br>

### The body element

<p style ="text-align: justify">O elemento <code>body</code> contém todo o conteúdo da página. É aqui onde você escreve os cabeçalhos, parágrafos, adiciona imagens, vídeos e tudo o mais.</p>

<br>

### Meta charset

```html
<meta charset ="UTF-8"
```

<p style ="text-align: justify">A chave <code>charset</code> é a abreviação de <i>character set</i>(conjunto de caracteres). Ela refere a como exibir os diversos tipos de caracteres na tela pelo computador. O valor <code>UTF-8</code> possui suporte para muitos dos caracteres do mundo inteiro.</p>

<br>

### Meta viewport

```html
<meta name ="viewport" content ="width=device-width, initial-scale=1.0">
```

<p style ="text-align: justify">O viewport precisa ser utilizado por um website para que em uma tela móvel a exibição seja adequada ao tamanho da tela. Ele pede para o navegador representar a largura da página de acordo com o dispositivo atual.</p>

<br>

### The title element

```html
<title>MDN Web Docs</title>
```

<p style ="text-align: justify">O elemento <code>title</code> mostra o título de uma página web barra de abas de um navegador.</p>
  
</details>

<details>
  <summary><h2>Chapter 6: Blank space and comments</h2></summary>

  ### HTML Comments

```html
<!-- Comentário de linha única-->

<!-- Comenário
de múltiplas linhas -->
```

  <p style ="text-align: justify">Um comentário é um pedaço de texto escrito por um desenvolvedor para descrever o que está acontecendo no código, prover esclarecimento, uma nota para ele mesmo ou outras notas.</p>
  
  <br>

  ### Blank space and newlines

  <p style ="text-align: justify">Espaços em branco são tratados diferentemente no HTML do que você pode experar. Olhe abaixo:</p>

```html
<h1>Hello           world</h1>
```
**Resposta:**

<code>Hello world</code>

<p style ="text-align: justify">Você tem mais do que um espaço em branco, ele será renderizado como um espaço em branco pelo navegador. Este comportamento dá a você flexibilidade sobre como escrever seu código, especialmente conforme sua página vai ficando mais complexa..</p>

<br>

### New Lines

<p style ="text-align: justify">Caracteres de nova linha são representados por um único caractere de espaço em branco.</p>

```
<h1>Hello

World</h1>
```

**Resultado:**

<code>Hello World</code>

<br>

### What if a want a new line to render?

<p style ="text-align: justify">Em alguns caso, você quer um caractere de nova linha para renderizar na página. Nesse caso, você usa o elemento de quebra de linha <code>br</code>. Esse elemento produz uma nova linha e não possui tag de fechamento.</p>

<p style ="text-align: justify">O elemento <code>br</code> não é tão utilizado como você pode espear. Seu uso deveria ser limitado a lugares onde uma nova linha dentro da mesma sentência ou contexto. Você não deveria usar-ló para separar parágrafos. Também, o elemento <code>br</code> nunca deveria ser usado para criar separação entre elementos: 1. ele quebre a página em termos de acessibilidade e 2. você não pode facilmente modificar a separação entre dois elementos.</p>

<p style ="text-align: justify">O exemplo mais comum de uso é para representar endereços. Outro exemplo típico está em literatura (poemas), onde você precisa que um pedaço do texto vá em outra linha.</p>
  
</details>

<details>
  <summary><h2>Chapter 7: The paragraph element</h2></summary>


```html
<p>The xPhone is the best phone on the market.</p>
```

### The paragraph element

<p style ="text-align: justify">O elemento <code>p</code>é usado para representar um parágrafo de texto de uma página web. Alguns leitores de tela anunciam o elemento <code>p</code> como um parágrafo. Isso permite ao usuário escutar algumas poucas palavras do parágrafo e pular para o seguinte. Quando você escreve o texto dentro do parágrafo, você fala ao navegador o significado do elemento. Isso é chamado de HTML semântico.</p>

<br>

### Paragraphs and line breaks

<p style ="text-align: justify">O elemento <code>br</code> não deveria ser usado para separar parágrafos ou dois elementos. De fato, ele deveria ser usado somente para criar uma nova linha dentro da mesma sentência ou contexto.</p>

<br>

### Contents of a paragraph

<p style ="text-align: justify">Um elemento parágrafo irá conter majoritariamente texto. Por agora, é importante saber que você não pode aninhar um parágrafo dentro do outro.</p>
  
</details>

<details>
  <summary><h2>Chapter 8: Lists</h2></summary>

### The ol and ul elements

```html
<ol>

    <li>Heat the pasta.</li>

    <li>Pour the sauce on the cooked pasta.</li>

</ol>
```

### The ol (ordered list) element

<p style ="text-align: justify">O elemento <code>ol</code> (ordered list) representa uma lista de items onde os items foram intencionalmente ordenados. O elemento <code>li</code> representa o um item da lista. Então, o <code>ol</code> define que a lista é ordenada. Então, cada elemento <code>li</code> dentro representa um item dessa lista ordenada.</p>

<br>

```html
<ul>

    <li>Heat the pasta.</li>

    <li>Pour the sauce on the cooked pasta.</li>

</ul>
```


### The ul (unordered list) element

<p style="text-align: justify">Similar ao elmento <code>ol</code> nós temos agora o elemento <code>ul</code>. O elemento <code>ul</code> representa listas de items onde a ordem de items não importa.</p>

<br>

### Element nesting

<p style ="text-align: justify">É possíve também com listas, aninhar uma dentro da outra, criando listas dentro de listas. Vale tanto para listas ordenadas dentro de lista não ordenadas ou vice-versa, listas ordenads dentro de listas ordenadas e listas não ordenadas dentro de listas não ordenadas</p>

  
</details>

<details>
  <summary><h2>Chapter 9: HTML validity</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 10: Intro to landmarks</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 11: strong and em</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 12: Intro to Images</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 13: Intro do CSS</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 14: Intro do CSS (continued)</h2></summary>

  
</details>

<details>
  <summary><h2>Chapter 15: CSS inheritance</h2></summary>

  
</details>
