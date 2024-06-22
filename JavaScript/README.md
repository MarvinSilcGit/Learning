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

<p style ="text-align: justify">Em JavaScript, o operador + irá se comportar de maneira diferente baseado nos tipos de valores que você usa com ele. Você já viu que 1 + 3 irá retornar 4. Contudo, você poderia usar o operador + para concatenar duas strings. que significa unificar elas em uma única string.</p>

**Exemplo:**

```javascript
function concatInitials(firstNameInitial, lastNameInitial)
{
    return firstNameInitial + lastNameInitial;
}
```

### Interpolation

<p style ="text-align: justify">Strings Template suportam interpolação. Isso significa que você poderia escrever uma variável em sua string, e recuperar o seu valor. A sintaxe é direta ao ponto, você envolve a variável com <i>_${variável}</i> </p>

**Exemplo:**

```javascript
function sayHello(name)
{
    return `Hello ${name}`;
}
```

### Interpolation Advanced
Capitalize
Nutrition Table
Multiline string
</details>
