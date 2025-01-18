# Chapter 13: Intro do CSS

  ## Intro to CSS

  <p>CSS significa Cascading Style Sheets. O CSS é utilizado para estilizar uma página escrita em HTML. Ou seja, CSS vai de mão dada com HTML na construção de uma página minimamente decente e funcional.</p>

  ## Adding stylesheet

  ```html
  <link rel ="stylesheet" type ="text/css" href ="style.css">
  ```

   <p>Sintaxe para conexão entre um arquivo CSS e uma página HTML. Aplique dentro da tag <code>head</code></p>

  ## CSS sintax

  ```css
  h1 
  {
    color: red;
  }
  ```

   <p>O elemento <code>h1</code> no contexto CSS é chamado de seletor. Um seletor CSS é usado para encontrar os elementos em uma página web que irá receber um conjunto de estilos.</p>

   <p>A sintaxe do CSS é composta de duas partes: o seletor e par propriedade/valor. No contexto do código de cima. <code>color:</code> é propriedade e <code>red</code> é o valor.</p>

  ## O seletor simples

   <p>Há várias maneiras de selecionar as tags de uma página, e uma delas é pelo uso do seletor simples. Com isso, toda vez que a tag <code>h1</code> for escrita, o seletor captura seu uso e aplica o efeito de cor green. No contexto do código acima, foi usado o seletor simples na tag <code>h1</code>.</p>

  ## CSS comments

  ```css
  /* This is a CSS comment */

  h1 
  {
    color: red;
  }
  ```

  <p>Os comentários permitem acrescentar lembretes ou guias das funções que arquivo CSS possui e como isso afeta o conteúdo exibido no navegador.</p>