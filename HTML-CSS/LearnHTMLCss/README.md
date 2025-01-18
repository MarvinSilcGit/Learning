<h1>Learn HTML & CSS</h1>

<details>

<summary>

<h2>Charpter 2: Intro to Semantics</h2>

</summary>

### Intro to Semantics

<p>Escrever HTML semântico significa dar significado para os elementos que nós usamos. Isso permite você focar no propósito do elemente ao invés de sua aparência. Semântica foca em fornecer significado e propósito para os elementos que você usa.</p>

#### Código sem semântica

```html
<div>My Blog</div>

<div>

 <div>This is the content of my blog</div>

</div>

<div>We are located in Amsterdam</div>
```

#### Código com semântica</h4>

```html
<header>My Blog</header>

<main>

 <p>This is the content of my blog</p>

</main>

<footer>We are located in Amsterdam</footer>
```

<br>

### Intro to Headings

<p>O elemento cabeçalho h1 é usado para representa o tópico de mais alta importância em uma página web. Ao escrever código HTML, é importante focar na semântica ao invés da aparencia. HTML é feito para o conteúdo, enquanto que o CSS é usado para estilizar o conteúdo.</p>

<br>

</details>

<details>

<summary><h2>Chapter 3: Intro to Acceessibility</h2></summary>

### Intro to Accessibility

<p>No contexto do HTML, acessibilidade se refere a fazer seu site usável por todo mundo. Quando você escrever seu código de acessibilidade, seu eu do futuro irá te agradecer. Nós estamos escrevendo websites que nós iremos usar daqui alguns anos. Nossa extensão de habilidades pode muito bem mudar em poucos anos.</p>

<br>

### Headings and Accesibility

<p>Leitor de tela é um software que tem comandos para rapidamente pular entre cabeçalhos ou regiões referenciais específicas. Isso faz com que seja essencial ter cabeçalhos siginificativos. Isso ajuda ususários com tecnologias assistivas facilmente navegar e explorar sua página. Note que isso não é o único benefício de ter cabeçalhos siginicativos. Há muito mais benefícios no que diz respeito a SEO.</p>

<br>

</details>

<details>

<summary>

<h2>Chapter 4: Headings deep dive</h2>

</summary>

### H1 e H2

<p>O elemento h2 é usado para definir títulos da principais seções de uma página web. O elemente h2 é uma subseção do elemento h1. É importante pensar nos elementos h1 e h2 como um rascunho de um livro. O h1 é o título da página e os elementos h2 são os capítulos. Nós estamos levando um tempo e focando nos pequenos detalhes porque é muito importante usar h1 e h2 baseado na hierarquia no documento ao invés do tamanho da fonte. Utilize somente um h1 por página, pois o h1 é o principal</p>

<br>

### H3, H4, H5 and H6

<p>Nós já aprendemos sobre h1 e h2. Similarmente para como h2 se relaciona com h1: o elemento h3 é uma subseção de h2, h4 é uma subseção de 3, h5 é uma subseção de h4 e h6 é uma subseção de h5. É importante evitar pular níveis de cabeçalhos. Se você tem um h1, o cabeçalho a seguir deverá ser h2. Você não deve pular h2 e ir direto para h3. O mesmo se aplica aos outros cabeçalhos.</p>

<br>

### Headings and SEO

<p>SEO (Search Engine Optimization) é a prática de aprimorar a qualidade de seu website de modo a adquirir mais visitantes advindos dos motores de busca. Cabeçalhos teem uma função importante em SE, pois você está comunicndo para o motor de busca o rascunho da página e o tópico mais importante.</p>

<br>

</details>

<details>

<summary>

<h2>Chapter 5: Boilerplate</h2>

</summary>

### What is an attribute?

<p>Todo elemento html pode ter um ou mais pares de <code>chave="valor"</code> que permite você customizar ou configurar o comportamento do elemento. Os pares <code>chave="valor" são chamados de atributos.</code></p>

```html
<html lang ="pt-br">

</html>
```

<p>O <code>lang</code> é chamado de chave e o <code>"pt-br"</code> é chamado de valor. As aspas são necessárias para diferenciar atributos de outros e não gerar problemas inesperados.</p>

```html
<meta name ="viewport" content ="width=device-width, initial-scale=1.0">
```

<p>Observe acima que o elemento <code>meta</code> possui 2 atributos: <code>name ="viewport" content ="width=device.width, initial-scale=1.0"</code></p>

<br>

### Boilerplate

<p>Boilerplate representa uma porção de texto frequentemente utilizada e que raramente sofre alterações. No Html existem algumas tag/elementos que sempre serão utilizadas na construção de uma página. São eles a seguir:</p>

<br>

<h3>The doctype</h3>

```html
<!DOCTYPE html>
```

<p>Especifica a versão do html que o navegador irá renderizar. Nesse caos, HTML 5</p>

<br>

### The html element

<p>O elemento html é o elemento raiz de toda página html. A partir dele, todos os outros elementos são criados. Esse elemento possui somente dois elementos filho: <code>head</code> e <code>body</code>.</p>

<br>

### The head element

<p>O elemento <code>head</code> contém informação e dados que serão processados pelo navegador e motores de busca. O conteúdo dentro dessa tag não é exibido na página, mas pode afetar o comportamento visual dela.</p>

<br>

### The body element

<p>O elemento <code>body</code> contém todo o conteúdo da página. É aqui onde você escreve os cabeçalhos, parágrafos, adiciona imagens, vídeos e tudo o mais.</p>

<br>

### The Meta element

<p>Esse elemento diz respeito a como devem ser exibidos os diversos tipos de elementos da página.</p>

#### Meta Charset

```html
<meta charset ="UTF-8"
```

<p>A chave <code>charset</code> é a abreviação para <i>character set</i> e signica qual conjunto de caracteres serão utilizados com referência para a representação textual da página. Já o atributo <code>charset = "UTF-8"</code> possui suporte para muitos dos caracteres do mundo inteiro.</p>

#### Meta viewport

```html
<meta name ="viewport" content ="width=device-width, initial-scale=1.0">
```

<p>Os atributos <code>name ="viewport" content ="width=device-width, initial-scale=1.0"</code> são utilizado para adequar o tamanho e proporção da página web conforme o tipo de tela. Eles informam para o navegador representar a largura da página de acordo com o dispositivo atual.</p>

<br>

### The Title element

```html
<title>MDN Web Docs</title>
```

<p>O elemento <code>title</code> mostra o título de uma página web barra de abas de um navegador.</p>

<br>

</details>

<details>

<summary>

<h2>Chapter 6: Blank space and comments</h2>

</summary>

### HTML Comments

```html
<!-- Comentário de linha única-->

<!-- Comenário
de múltiplas linhas -->
```

<p>Um comentário é um pedaço de texto escrito por um desenvolvedor para descrever o que está acontecendo no código, prover esclarecimento, uma nota para ele mesmo ou outras notas.</p>

<br>

### Blank space and newlines

<p>Espaços em branco são tratados diferentemente no HTML do que você pode experar. Olhe abaixo:</p>

```html
<h1>Hello           world</h1>
```

<p><code>Hello world</code></p>

<p>Você tem mais do que um espaço em branco, ele será renderizado como um espaço em branco pelo navegador. Este comportamento dá a você flexibilidade sobre como escrever seu código, especialmente conforme sua página vai ficando mais complexa.</p>

<br>

### New Lines

<p>Caracteres de nova linha são representados por um único caractere de espaço em branco.</p>

```html
<h1>Hello

World</h1>
```

<p><code>Hello World</code></p>

<br>

### What if a want a new line to render?

<p>Em alguns casos, você pode querer um caractere de nova linha para renderizar na página. Nesse caso, você usa o elemento de quebra de linha <code>br</code>. Esse elemento produz uma nova linha e não possui tag de fechamento.</p>

<p>O elemento <code>br</code> não é tão utilizado como você pode esperar. Seu uso deveria ser limitado a lugares onde uma nova linha dentro da mesma sentência ou contexto. Você não deveria usar-ló para separar parágrafos. Também, o elemento <code>br</code> nunca deveria ser usado para criar separação entre elementos: 1. ele quebra a página em termos de acessibilidade e 2. você não pode facilmente modificar a separação entre dois elementos.</p>

<p>O exemplo mais comum de uso é para representar endereços. Outro exemplo típico está em literatura (poemas), onde você precisa que um pedaço do texto vá em outra linha.</p>

```html
Street name<br>
City<br>
Postcode, Country
```

<br>

</details>

<details>

<summary>
 
<h2>Chapter 7: The paragraph element</h2>

</summary>

```html
<p>The xPhone is the best phone on the market.</p>
```

### The paragraph element

<p>O elemento <code>p</code>é usado para representar um parágrafo de texto de uma página web. Alguns leitores de tela anunciam o elemento <code>p</code> como um parágrafo. Isso permite ao usuário escutar algumas poucas palavras do parágrafo e pular para o seguinte. Quando você escreve o texto dentro do parágrafo, você fala ao navegador o significado do elemento. Isso é chamado de HTML semântico.</p>

<br>

### Paragraphs and line breaks

<p>O elemento <code>br</code> não deveria ser usado para separar parágrafos ou dois elementos. De fato, ele deveria ser usado somente para criar uma nova linha dentro da mesma sentência ou contexto.</p>

<br>

### Contents of a paragraph

<p>Um elemento parágrafo irá conter majoritariamente texto. Por agora, é importante saber que você não pode aninhar um parágrafo dentro do outro.</p>

<br>

</details>

<details>

<summary>

<h2>Chapter 8: Lists</h2>

</summary>

### The ol and ul elements

```html
<ol>

 <li>Heat the pasta.</li>

 <li>Pour the sauce on the cooked pasta.</li>

</ol>
```

### The ol (ordered list) element

<p>O elemento <code>ol</code> (ordered list) representa uma lista de items onde os items foram intencionalmente ordenados. O elemento <code>li</code> representa o um item da lista. Então, o <code>ol</code> define que a lista é ordenada. Então, cada elemento <code>li</code> dentro representa um item dessa lista ordenada.</p>

<br>

```html
<ul>

 <li>Heat the pasta.</li>

 <li>Pour the sauce on the cooked pasta.</li>

</ul>
```

<br>

### The ul (unordered list) element

<p>Similar ao elmento <code>ol</code> nós temos agora o elemento <code>ul</code>. O elemento <code>ul</code> representa listas de items onde a ordem de items não importa.</p>

<br>

```html
<ol>

<li>Introduction</li>

<li>Hypothesis</li>

<li>Theories</li>

 <ul>

   <li>Behavior theory</li>

   <li>Relational theory</li>

 </ul>

<li>Conclusion</li>

</ol>
```

### Element nesting

<p>É possíve também com listas, aninhar uma dentro da outra, criando listas dentro de listas. Vale tanto para listas ordenadas dentro de lista não ordenadas ou vice-versa, listas ordenads dentro de listas ordenadas e listas não ordenadas dentro de listas não ordenadas</p>


</details>

<details>
<summary><h2>Chapter 10: Intro to Landmarks</h2></summary>

### Intro to Landmarks

<p style ="text-align: justify">Elementos referenciais teem o objetivo de dividir a página em várias áreas reconhecíveis. Um usuário pode usar leitores de tela para navegar com facilidade e motores de buscam podem melhor entender o conteúdo do seu website</p>

<br>

### The Main Element

<p style ="text-align: justify">O elemento <code>main</code> é utilizado para representar o conteúdo principal da página.</p>

<br>

### The header element

<p style ="text-align: justify">O elemento <code>header</code> representa o conteúdo usado para introduzir a página. Ele geralmente contém o cabeçalho, uma logo e elementos de navegação.</p>

<br>

### The footer element

<p style ="text-align:justify">O elemento <code>footer</code> representa o rodapé da página. Ele contém os dados comumente utilizados no final da página, tais como: links, documentos relacionados, direitos de propriedade intelectual, informações de contato e endereço.</p>


</details>

<details>
<summary><h2>Chapter 11: strong and em</h2></summary>

### The strong and b elements

<p style ="text-align: justify">O elemento <code>strong</code> é utilizado para represenar conteúdo que forte relevância, seriedade ou urgência.</p>

<br>

### The b element

<p style ="text-align: justify">O elemento <code>b</code> é utilizado para chamar a atenção de uma porção de texto relevante, sem tem muita importância além disso.</p>

<br>

### The em and i elements

<p style ="text-align: justify">O elemento <code>em</code> é utilizado para dar ênfase em termos de tonalidade ao conteúdo.</p>

<br>

<p style ="text-align: justify">O elemento <code>i</code> é utilizado para denotar outros termos de idioma diferentes, títulos de obras artísticas ou termos técnicos.</p>


</details>

<details>
<summary><h2>Chapter 12: Intro to Images</h2></summary>

```html
<img src = "" width ="" height ="" alt ="">
```

### The img element

<p style ="text-align: justify">O elemento <code>img</code> é responsável por exibir imagens na página.</p>

<br>

### The src attribute

<p style ="text-align: justify">O atributo src é usado para definir o local da página.</p>

### The width and height attributes

<p style ="text-align: justify">O atributo width define a largura da imagem e height a altura da página e é sempre necessário utilizar-los para explicitar o tamanho da imagem para o navegador e remover comportamentos preditivos dos navegadores em alocar o espaço certo para imagem na página.</p>

<br>

### Alternative text

<p style ="text-align: justify">O atributo alt é usado para especificar um texto alternativo no lugar da imagem caso ele não possa ser exibida. Com isso, ele sempre é necessário. Ele é usado também em leitores de tela, como forma de narrar a imagem para uma pessoa cega.</p>


#### Decorative images

<p style ="text-align: justify">Um imagem decorativa é usada somente com o único propósito estético na página. Para tais imagens, o atributo alt precisa estar assim: <code>alt =""</code>.</p>

<br>

#### Informative images

<p style ="text-align: justify">Imagens informativas são imagens que adicionam valor para a página e possuem relacão com o conteúdo. Para tais imagens o atributo alt precisa estar assim: <code>alt ="textoDescritivoImagem"</code>. Evite utilizar descrições genéricas, pois pode confundir pessoas que estejam utilizando leitores de tela.</p>

</details>

<details>
<summary><h2>Chapter 13: Intro do CSS</h2></summary>

### Intro to CSS

<p style ="text-align: justify">CSS significa _Cascading Style Sheets_. O CSS é utilizado para estilizar uma página escrita em HTML. Ou seja, CSS vai de mão dada com HTML na construção de uma página minimamente decente e funcional.</p>

<br>

### Adding stylesheet

```html
<link rel ="stylesheet" type ="text/css" href ="style.css">
```

<p>Sintaxe para conexão entre um arquivo CSS e uma página HTML. Aplique dentro da tag <code>head</code></p>

<br>

### CSS sintax

```css
h1 {
 color: red;
}
```

<p style ="text-align: justify">O elemento <code>h1</code> no contexto CSS é chamado de seletor. Um seletor CSS é usado para encontrar os elementos em uma página web que irá receber um conjunto de estilos.</p>

<p style ="text-align: justify">A sintexe do CSS é composta de duas partes: o seletor e par propriedade/valor. No contexto do código de cima. <code>color:</code> é proprieade e <code>red</code> é o valor.</p>

<br>

### O seletor simples

<p style ="text-align: justify">Há várias maneiras de selecionar as tags de uma página, e uma delas é pelo uso do seletor simples. Com isso, toda vez que a tag <code>h1</code> for escrita, o seletor captura seu uso e aplica o efeito de cor green. No contexto do código acima, foi usado o seletor simples na tag <code>h1</code>.</p>

<br>

### CSS comments

```css
/* This is a CSS comment */
h1 {
 color: red;
}
```
<p style ="text-align: justify">Os comentários permitem acrescentar lembretes ou guias das funções que arquivo CSS possui e como isso afeta o conteúdo exibido no navegador.</p>

</details>

<details>
<summary><h2>Chapter 14: Intro do CSS (continued)</h2></summary>

### CSS Properties

<p style ="text-align: justify">A propriedade <code>font-weight: bold</code> é responsável por deixar o texto com a fonte em destaque. Tem o mesmo que a tag <code>b</code>, porém é uma boa prática fazer uso da estilização no arquivo CSS que está conectado ao arquivo HTML. Pois, HTML se refere a estrutura e não estilização. Também é possível fazer múltiplias declações utilizando somente um seletor.</p>

```css
p
{
color: red;
font-weight: bold;
}
```
_Sempre utilize ponto e vírgula para finalizar cada linha da declaração dentro do seletor_


</details>

<details>
<summary><h2>Chapter 15: CSS inheritance</h2></summary>


### User-agent sylesheet

<p style ="text-align: justify">O agente-usuário é um software que consome conteúdo da web à pedido dos usuários. Nesse caso, os navegadores web se encaixam nessa definição. O stylesheeet se refere ao arquivo CSS que todos os navegadores tem por padrão como forma de estilização mínima de uma página. Por exemplol, todo cabeça já vem estilizado em um determinado tamanho de fonte e destaque visual.</p>

<br>

### User-agent styles and the cascade

<p>Por ser um arquivo do tipo <i>cascade</i> (cascata) a declaração que você fizer irá sobescrever o mesmo tipo de declaração feita pelo navegador, pois será a última declaração e assim ficará com a prioridade na hora da estilização. Do mesmo modo, dentro do seu arquivo css, qualquer declaração feita depois e que seja do mesmo tipo sobsescreverá a declaração feita antes.</p>

```css
p
{
color: red;
}

p
{
color: blue;
}
```

_Na página irá apareceu um parágrafo da cor azul, pois ele é o último na cascata._

<br>

### CSS inheritance

<p style ="text-align: justify">Muitas propriedades podem ser herdadas através da tag pai respectiva. Somente quando a tag filha já possuir uma estilização depois da tag pag, é que a herança não funciona. Se a estilização for antes, ela herdará a característica da tag pai.</p>

```css
<p>
 Welcome to my <strong>first</strong> website.
</p>

<style>
 p
 {
     color: blue;
 }
</style>
```

_No caso acima, a tag strong é filha da tag p e herdada a estilização da mesma._

</details>
