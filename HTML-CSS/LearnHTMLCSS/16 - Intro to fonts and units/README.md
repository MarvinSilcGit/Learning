# Chapter 16: Intro to fonts and units

## The font-size property

  <p>A propriedade <code>font-size</code> é utilizada para definir o tamanho de todas as fontes numa página web. Por padrão, para definir o tamanho do parágrafo utiliza-se a sintaxe: <code>font-size: 10px</code>, definindo assim o tamanho para 10 píxeis.</p>

```css
p{
    font-size: 10px;
}
```

## CSS Units

  <p>Contudo, o tamanho dos píxeis não é consenso universal dentre os navegadores e os Sistemas Operacionais. Por isso, uma alternativa ainda melhor a unidade <code>px</code> vista acima, é a utilização da unidade <code>rem</code>: ele é mais precisa e adaptada aos vários formatos.</p>

## Font-size is inherited

  <p>Por padrão todos os elementos filhos também herdam o font-size. Caso seja necessário mudar o font-size será preciso alterar individualmente para cada elemento filho.</p>

```html
<ul>
  <li>elemento</li>
</ul>
```
```css
ul{
  font-size: 20px;
}
```

#### *Versão com o font-size herdado.*

```html
<ul>
  <li>elemento</li>
</ul>
```
```css
ul{
  font-size: 20px;
}

li{
  font-size: 16px;
}
```

#### *Versão com o font-size não herdado.*


## Erros comuns ao utilizar o font-size

  <ol>
    <li>Não colocar ao final a abreviação px. 20px é diferente de 20 ou 20 px.</li>
    <li>Caso o tamanho da fonte seja 0 não precisa definir com px.</li>
    <li>Os atributos <code>width</code> e <code>height</code> utilizados em imagens e vídeos não utilizam o px para funcionar corretamente.</li>
  </ol>
testando vscode integration