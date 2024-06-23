<details>
  <summary><h2> Chapter 1: Basic Functions</h2></summary>

```javascript
function sum (x, y)
{
  return x + y;
}
```

### Multiplication

```javascript
function multi (x, y)
{
  return x * y;
}
```

### Division

```javascript
function div (x, y)
{
  return x / y;
}
```

### Subtraction 

```javascript
function sub(x, y)
{
  return x + y;
}
```

### Exponentiation

```javascript
function exp (x, y)
{
  return x ** y;
}
```

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

### toUpperCase

<p style ="text-align: justify">Transforma a string em caixa alta</p>

```javascript
function shoutMyName(name)
{
    return name.toUpperCase;
}
```

### toLowerCase

<p style ="text-align: justify">Transforma a string em caixa baixa</p>

```javascript
function lowerName(name)
{
    return name.toLowerCase(name);
}
```

### Character acess

<p style ="text-align: justify"> Você pode acessar um caractere específico em uma string ao utilizar a sintaxe dos colchetes</p>

```javascript
function getFirstCharacter(name)
{
    return name[0];
}
```

<p></p>

```javascript
function getLastCharacter(name)
{
    return name[name.length-1];
}
```

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
    return text.substring(1); // quando um, assume o fim como sendo o comprimento máximo da string
}
```

### Concatenation

<p style ="text-align: justify">Em JavaScript, o operador + irá se comportar de maneira diferente baseado nos tipos de valores que você usa com ele. Você já viu que <code>1 + 3 </code> irá retornar 4. Contudo, você poderia usar o operador + para concatenar duas strings. que significa unificar elas em uma única string.</p>

**Exemplo:**

```javascript
function concatInitials(firstNameInitial, lastNameInitial)
{
    return firstNameInitial + lastNameInitial;
}
```

### Interpolation

<p style ="text-align: justify">Strings Template suportam interpolação. Isso significa que você poderia escrever uma variável em sua string, e recuperar o seu valor. A sintaxe é direta ao ponto, você envolve a variável com <code>${variável}</code> </p>

**Exemplo:**

```javascript
function sayHello(name)
{
    return `Hello ${name}`;
}
```

### Interpolation advanced

**Exemplo:**

```javascript
function getFullName(firstName, lastName)
{
    return `${firstName} ${lastName}`;
}
```

### Multiline string

**Exemplo:**

```javascript
return `I am Learning JavaScript
and I found it to be
quite fun!`
```

### Capitalize

```javascript
function captalized(word)
{
  return word[0].toUpperCase() + word.substring(1).toLowerCase();
}
```

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

  <p style ="text-align: justify">Você pode representar números grandes mais claramente com o separador numério (_)</p>

```javascript
let nb = 1_000; // equivalent to 1000

let nb = 1_000_000; // 1000000 (1 million)
```

### Converting from number to string

<p style ="text-align: justify">Embora seja raramente utilizado, você pode converter um número para string ao chamar o método <code>to.string()</code></p>

```javascript
let answer = 42;
answer.toString(); //"42"
```

### NaN

<p>Você pode algumas vezes encontar <code>NaN</code> que significa <b>Not a Number</b>. Por exemplo, você tenta multiplicar um número por uma string. NaN é com frequência um sinal que algo está errado com seu código, na maioria das vezes vocês esqueceu de converter uma string para um número.</p>

</details>
