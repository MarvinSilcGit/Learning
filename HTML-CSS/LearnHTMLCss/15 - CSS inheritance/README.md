# Chapter 15: CSS inheritance

## User-agent sylesheet

   <p>O agente-usuário é um software que consome conteúdo da web a pedido dos usuários. Nesse caso, os navegadores web se encaixam nessa definição. O stylesheeet se refere ao arquivo CSS que todos os navegadores têm por padrão como forma de estilização mínima de uma página. Por exemplo, toda cabeça já vem estilizado em um determinado tamanho de fonte e destaque visual.</p>

## User-agent styles and the cascade

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

  <p>Na página irá aparecer um parágrafo da cor azul, pois ele é o último na cascata.</p>

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

   <p>No caso acima, a tag strong é filha da tag <code>p</code> e herdada a estilização da mesma.</p>
