<details>
  <summary><h2> Chapter 1: Basic Functions</h2></summary>

```javascript
function sum (x, y)
{
  return x + y;
}
```

<br>

### Multiplication

```javascript
function multi (x, y)
{
  return x * y;
}
```

<br>

### Division

```javascript
function div (x, y)
{
  return x / y;
}
```

<br>

### Subtraction 

```javascript
function sub(x, y)
{
  return x + y;
}
```

<br>

### Exponentiation

```javascript
function exp (x, y)
{
  return x ** y;
}
```

<br>

### Remainder (Resto da divisão)

```javascript
function sum (x, y)
{
  return x % y;
}
```
</details>

<details>
  <summary><h2>Chapter 2: String I</h2></summary>

### Length

<p style="text-align: justify">A propriedade length é usada para retornar o comprimento de uma string</p>

```javascript
function getCharCount(variável)
{
    return variável.length;
}
```

<br>

### toUpperCase

<p style ="text-align: justify">Transforma a string em caixa alta</p>

```javascript
function shoutMyName(name)
{
    return name.toUpperCase;
}
```

<br>

### toLowerCase

<p style ="text-align: justify">Transforma a string em caixa baixa</p>

```javascript
function lowerName(name)
{
    return name.toLowerCase(name);
}
```

<br>

### Character acess

<p style ="text-align: justify"> Você pode acessar um caractere específico em uma string ao utilizar a sintaxe dos colchetes</p>

```javascript
function getFirstCharacter(name)
{
    return name[0];
}
```

<br>

<p style ="text-align> justify">Também é possível utilizar a função <code>.lenght</code> abaixo para buscar o último caractere dentro da função dos colchetes.</p>

```javascript
function getLastCharacter(name)
{
    return name[name.length-1];
}
```

<br>

### Substring

<p style="text-align">Uma substring é uma parte ou uma porção de uma string. Por exemplo, "rain" é uma substring da string "brain. Você pode recupear "rain" ao tomar os últimos quatro caracteres.</p>

**Exemplo:**

```javascript
function getDescription(text)
{
    console.log(text);
    return text.substring(0, 10); // Dois parâmetros: um de ínico e outro de fim
}
```

```javascript
function skipFirstCharacter(text)
{
    return text.substring(1); // Quando um, assume o fim como sendo o comprimento máximo da string
}
```

<br>

### Concatenation

<p style ="text-align: justify">Em JavaScript, o operador + irá se comportar de maneira diferente baseado nos tipos de valores que você usa com ele. Você já viu que <code>1 + 3 </code> irá retornar 4. Contudo, você poderia usar o operador + para concatenar duas strings. que significa unificar elas em uma única string.</p>

**Exemplo:**

```javascript
function concatInitials(firstNameInitial, lastNameInitial)
{
    return firstNameInitial + lastNameInitial;
}
```

<br>

### Interpolation

<p style ="text-align: justify">Strings Template suportam interpolação. Isso significa que você poderia escrever uma variável em sua string, e recuperar o seu valor. A sintaxe é direta ao ponto, você envolve a variável com <code>${variável}</code> </p>

**Exemplo:**

```javascript
function sayHello(name)
{
    return `Hello ${name}`;
}
```

<br>

### Interpolation advanced

**Exemplo:**

```javascript
function getFullName(firstName, lastName)
{
    return `${firstName} ${lastName}`;
}
```

<br>

### Multiline string

**Exemplo:**

```javascript
return `I am Learning JavaScript
and I found it to be
quite fun!`
```

<br>

### Capitalize

```javascript
function captalized(word)
{
  return word[0].toUpperCase() + word.substring(1).toLowerCase();
}
```

<br>

### at is similar to [] index, but can do negative index

```javascript
function index(word)
{
  return word.at(1);
}

```
</details>

<details>
  <summary><h2>Chapter 3: Numbers</h2></summary>

  ### Numeric separator (<code>_</code>)

  <p style ="text-align: justify">Você pode representar números grandes mais claramente com o separador numério (<code>_</code>)</p>

```javascript
let nb = 1_000; // equivalent to 1000

let nb = 1_000_000; // 1000000 (1 million)
```

<br>

### Converting from number to string

<p style ="text-align: justify">Embora seja raramente utilizado, você pode converter um número para string ao chamar o método <code>to.string()</code></p>

```javascript
let answer = 42;
answer.toString(); //"42"
```

<br>

### NaN

<p>Você pode algumas vezes encontar <code>NaN</code> que significa <b>Not a Number</b>. Por exemplo, você tenta multiplicar um número por uma string. NaN é com frequência um sinal que algo está errado com seu código, na maioria das vezes vocês esqueceu de converter uma string para um número.</p>

<br>

### Converting string to number

<p style ="text-align: justify">Em alguns cenários, você iria preferir converter de uma string para um número, Por conta disso, você teria que usar o método <code>Numer.parseInt()</code>.</p>

```javascript
let str = "42";
Number.parseInt(str, 10); //42
```

<p style ="text-align: justify">O nome da função é chamada <code>Numer.parseInt()</code>. Sim, incluindo the <code>Number</code>. É assim porque há um objeto global chamado <code>Number</code> que contém o método chamado <code>parseInt()</code>. Esse método espera dois parâmetros: o primeiro parâmetro é a string que você gostaria de converter em um número. O segundo argumeneto é a raiz que será usada na conversão.</p>

<p style ="text-align: justify">A raiz é a base do sistema numérico que você gostaria de usar. No seu caso, utilize o número pois representa a maneira que nós contamos números diariamente utilizando o sistema decimal. Sempre utilze a raiz em 10 para garantir a compatibilidade com o sistema decimal. Caso seja o sistema binário, utilize 2</p>

<br>

### Use cases for converting to a number

<p style ="text-align: justify">Há muitas razões que você gostaria de converter uma string para um número, porém, a mais comum é quando o número e digitado pelo usuáiro em uma caixa de texto or o número está sendo lido de um DOM. Como você verá, os valores serão sempre uma string mesmo se o usuário digitar um número.</p>

</details>
