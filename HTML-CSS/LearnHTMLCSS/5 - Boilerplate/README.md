# Chapter 5: Boilerplate</h2>

  ## What is an attribute?

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

  ## Boilerplate

   <p>Boilerplate representa uma porção de texto frequentemente utilizada e que raramente sofre alterações. No Html existem algumas tag/elementos que sempre serão utilizadas na construção de uma página. São eles a seguir:</p>

  <br>

  ## The doctype

  ```html
  <!DOCTYPE html>
  ```

   <p>Especifica a versão do html que o navegador irá renderizar. Nesse caos, HTML 5</p>

  <br>

  ## The html element

   <p>O elemento html é o elemento raiz de toda página html. A partir dele, todos os outros elementos são criados. Esse elemento possui somente dois elementos filho: <code>head</code> e <code>body</code>.</p>

  <br>

  ## The head element

   <p>O elemento <code>head</code> contém informação e dados que serão processados pelo navegador e motores de busca. O conteúdo dentro dessa tag não é exibido na página, mas pode afetar o comportamento visual dela.</p>

  <br>

  ## The body element

   <p>O elemento <code>body</code> contém todo o conteúdo da página. É aqui onde você escreve os cabeçalhos, parágrafos, adiciona imagens, vídeos e tudo o mais.</p>

  <br>

  ## The Meta element

   <p>Esse elemento diz respeito a como devem ser exibidos os diversos tipos de elementos da página.</p>

   ### Meta Charset

  ```html
  <meta charset ="UTF-8"
  ```

   <p>A chave <code>charset</code> é a abreviação para <i>character set</i> e signica qual conjunto de caracteres serão utilizados com referência para a representação textual da página. Já o atributo <code>charset = "UTF-8"</code> possui suporte para muitos dos caracteres do mundo inteiro.</p>

   ### Meta viewport

  ```html
  <meta name ="viewport" content ="width=device-width, initial-scale=1.0">
  ```

   <p>Os atributos <code>name ="viewport" content ="width=device-width, initial-scale=1.0"</code> são utilizado para adequar o tamanho e proporção da página web conforme o tipo de tela. Eles informam para o navegador representar a largura da página de acordo com o dispositivo atual.</p>

  <br>

  ## The Title element

  ```html
  <title>MDN Web Docs</title>
  ```

   <p>O elemento <code>title</code> mostra o título de uma página web barra de abas de um navegador.</p>
