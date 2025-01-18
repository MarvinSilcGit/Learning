# Chapter 6: Blank space and comments

 ## HTML Comments

  ```html
  <!-- Comentário de linha única-->
  
  <!-- Comenário
  de múltiplas linhas -->
  ```

   <p>Um comentário é um pedaço de texto escrito por um desenvolvedor para descrever o que está acontecendo no código, prover esclarecimento, uma nota para ele mesmo ou outras notas.</p>

  <br>

  ## Blank space and newlines

   <p>Espaços em branco são tratados diferentemente no HTML do que você pode experar. Olhe abaixo:</p>

  ```html
  <h1>Hello           world</h1>
  ```

   <p><code>Hello world</code></p>

   <p>Você tem mais do que um espaço em branco, ele será renderizado como um espaço em branco pelo navegador. Este comportamento dá a você flexibilidade sobre como escrever seu código, especialmente conforme sua página vai ficando mais complexa.</p>

  <br>

  ## New Lines

   <p>Caracteres de nova linha são representados por um único caractere de espaço em branco.</p>

  ```html
  <h1>Hello
  
  World</h1>
  ```

   <p><code>Hello World</code></p>

  <br>

  ## What if a want a new line to render?

   <p>Em alguns casos, você pode querer um caractere de nova linha para renderizar na página. Nesse caso, você usa o elemento de quebra de linha <code>br</code>. Esse elemento produz uma nova linha e não possui tag de fechamento.</p>

   <p>O elemento <code>br</code> não é tão utilizado como você pode esperar. Seu uso deveria ser limitado a lugares onde uma nova linha dentro da mesma sentência ou contexto. Você não deveria usar-ló para separar parágrafos. Também, o elemento <code>br</code> nunca deveria ser usado para criar separação entre elementos: 1. ele quebra a página em termos de acessibilidade e 2. você não pode facilmente modificar a separação entre dois elementos.</p>

   <p>O exemplo mais comum de uso é para representar endereços. Outro exemplo típico está em literatura (poemas), onde você precisa que um pedaço do texto vá em outra linha.</p>

  ```html
  Street name<br>
  City<br>
  Postcode, Country
  ```
