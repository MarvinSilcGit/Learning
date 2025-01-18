<h2>Chapter 7: The paragraph element</h2>
  
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
  
  <h2>Chapter 8: Lists</h2>
  
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
  
  <p>É possíve também com listas, aninhar uma dentro da outra, criando listas dentro de listas. Vale tanto para listas ordenadas dentro de listas não ordenadas ou vice-versa, listas ordenads dentro de listas ordenadas e listas não ordenadas dentro de listas não ordenadas</p>
  
  <summary><h2>Chapter 10: Intro to Landmarks</h2></summary>
  
  ### Intro to Landmarks
  
  <p style ="text-align: justify">Elementos referenciais teem o objetivo de dividir a página em várias áreas reconhecíveis. Um usuário pode usar leitores de tela para navegar com facilidade e motores de buscam podem melhor entender o conteúdo do seu website</p>
  
  <br>
  
  ### The Main Element
  
  <p style ="text-align: justify">O elemento <code>main</code> é utilizado para representar o conteúdo principal da página.</p>
  
  <br>
  
  ### The header element
  
  <p style ="text-align: justify">O elemento <code>header</code> representa o conteúdo usado para introduzir a página. Ele contém geralmente o cabeçalho, uma logo e elementos de navegação.</p>
  
  <br>
  
  ### The footer element
  
  <p style ="text-align:justify">O elemento <code>footer</code> representa o rodapé da página. Ele contém os dados comumente utilizados no final da página, tais como: links, documentos relacionados, direitos de propriedade intelectual, informações de contato e endereço.</p>
  
  
  <h2>Chapter 11: strong and em</h2>
  
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

  <h2>Chapter 12: Intro to Images</h2>
  
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

  
  <h2>Chapter 13: Intro do CSS</h2>
  
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
  
  ```html
  h1 {
  color: red;
  }
  ```
  
  <p>O elemento <code>h1</code> no contexto CSS é chamado de seletor. Um seletor CSS é usado para encontrar os elementos em uma página web que irá receber um conjunto de estilos.</p>
  
  <p>A sintexe do CSS é composta de duas partes: o seletor e par propriedade/valor. No contexto do código de cima. <code>color:</code> é proprieade e <code>red</code> é o valor.</p>
  
  <br>
  
  ### O seletor simples
  
  <p>Há várias maneiras de selecionar as tags de uma página, e uma delas é pelo uso do seletor simples. Com isso, toda vez que a tag <code>h1</code> for escrita, o seletor captura seu uso e aplica o efeito de cor green. No contexto do código acima, foi usado o seletor simples na tag <code>h1</code>.</p>
  
  <br>
  
  ### CSS comments
  
  ```html
  /* This is a CSS comment */
  h1 {
  color: red;
  }
  ```
  
  <p>Os comentários permitem acrescentar lembretes ou guias das funções que arquivo CSS possui e como isso afeta o conteúdo exibido no navegador.</p>

  <h2>Chapter 14: Intro do CSS (continued)</h2>
  
  ### CSS Properties
  
  <p>A propriedade <code>font-weight: bold</code> é responsável por deixar o texto com a fonte em destaque. Tem o mesmo que a tag <code>b</code>, porém é uma boa prática fazer uso da estilização no arquivo CSS que está conectado ao arquivo HTML. Pois, HTML se refere a estrutura e não estilização. Também é possível fazer múltiplias declações utilizando somente um seletor.</p>
  
  ```html
  p
  {
  color: red;
  font-weight: bold;
  }
  ```
  _Sempre utilize ponto e vírgula para finalizar cada linha da declaração dentro do seletor_

  
  <h2>Chapter 15: CSS inheritance</h2>
  
  
  ### User-agent sylesheet
  
  <p>O agente-usuário é um software que consome conteúdo da web à pedido dos usuários. Nesse caso, os navegadores web se encaixam nessa definição. O stylesheeet se refere ao arquivo CSS que todos os navegadores tem por padrão como forma de estilização mínima de uma página. Por exemplo, toda cabeça já vem estilizado em um determinado tamanho de fonte e destaque visual.</p>
  
  <br>
  
  ### User-agent styles and the cascade
  
  <p>Por ser um arquivo do tipo <i>cascade</i> (cascata) a declaração que você fizer irá sobescrever o mesmo tipo de declaração feita pelo navegador, pois será a última declaração e assim ficará com a prioridade na hora da estilização. Do mesmo modo, dentro do seu arquivo css, qualquer declaração feita depois e que seja do mesmo tipo sobsescreverá a declaração feita antes.</p>
  
  ```html
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
  
  <p>Muitas propriedades podem ser herdadas através da tag pai respectiva. Somente quando a tag filha já possuir uma estilização depois da tag pag, é que a herança não funciona. Se a estilização for antes, ela herdará a característica da tag pai.</p>
  
  ```html
  <p>Welcome to my <strong>first</strong> website.  </p>
  
  <style>
  p
  {
    color: blue;
  }
  </style>
  ```
  
  _No caso acima, a tag strong é filha da tag p e herdada a estilização da mesma._
