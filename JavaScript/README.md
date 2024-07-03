<details>
  <summary><h2> Chapter 1: Basic Functions</h2></summary>

### Sum

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

<p style ="text-align: justify">Em alguns cenários, você iria preferir converter de uma string para um número, Por conta disso, você terá que usar o método <code>Number.parseInt()</code>.</p>

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

<details>
  <summary><h2>Chapter 4: Variables</h2></summary>

### Variables

<p>Há dois tipos de declarar variáveis em JavaScript.</p>


### let

<p style ="text-align: justify">A primeira que você escreve uma variável nova, use o prefixo <code>let</code>.</p>

```javascript
let name = "Sam";
console.log(name);
```

<p style ="text-align: justify">Isso define uma varíavel chamada <code>name</code> com o valor <code>"Sam"</code>. Da próxima vez que foz utilizar a variável, basta apenas o nome dela. Variável com prefixo <code>let</code> podem ser modificadas futuramente por qualquer outro tipo de valor.</p>


<br>

### const

<p style ="text-align: justify">Variáveis declaradas com <code>const</code> não podem ser modificadas depois com sinal <code>=</code> de atribuição. Esse tipo de prefixo é útil quando for definir variáveis e forçar que o comportamento seja o mais previsível.</p>

```javascript
const language = "C++"; // Cannot be re-assigned anymore
console.log(language); // "C++"
```

<br>

### let vs const

<p style ="text-align: justify">Para escolher entre <code>let</code> e <code>const</code> use o seguinte regra: sempre vá com <code>const</code> até você perceber que precisa atribuir um novo valor para a variável. Quando sim, mude para let.</p>
  
</details>

<details>
  <summary><h2>Chapter 5: Conditions</h2></summary>

### If

<p style ="text-align: justify">Sintaxe básica</p>

```javascript
const grade = 15;

if (grade >= 10)
{
    console.log("Passing grade");
}
```

<br>

### else

<p style ="text-align: justify">Sintaxe básica</p>

```javascript
const grade = 3;

if (grade >= 10)
{
    console.log("Passing grade");
}

else
{
    console.log("Failing grade");
}
```

<br>


### else if

<p style ="text-align: justify">Sintaxe básica</p>

```javascript
const grade = 10;

if (grade > 10) {
    console.log("Passing grade");
}

else if (grade === 10)
{
    console.log("Passing on the limit");
}

else
{
    console.log("Failing grade");
}
```

<br>

### advanced if

<p>Sintaxe básica</p>

```java script
function canVote(age)
{

    if (age >= 18)
    {
        return true;
    }

    else
    {
        return false;
    }

}
```

_Agora no estilo sofisticado_

```javascript
function canVote(age)
{
    if (age >=18)
    {
        return true;
    }

    return false;

}
```

<br>

### Legany note

<p style ="text-align: justify">Não utilize <code>==</code> para fazer comparações entre valores e/ou variáveis. Utilize no lugar <code>===</code>.</p>

```javascript
const a  = "2";
console.log(a == 2) // true!!!

console.log(a === 2) // false
```

<br>

### Returning booleans

<p style ="text-align: justify">Sempre que estiver retorando booleano, não é necessário utilizar if e elses</p>

```javascript
function isPassing(grade)
{

    if (grade >= 10)
    {
        return true;
    }

    else
    {
        return false;
    }

}

isPassing(12);
```

_Pode ser simplicado com:_

```javascript
function isPassing(grade)
{
    return grade >= 10;
}
```

<br>

### Even & Odd

<p style ="text-align: justify">O operator <code>%</code> pode ser utilizad para retornar se tal número é par ou ímpar.</p>

```javascript
// even numbers
4 % 2 // 0
6 % 2 // 0
8 % 2 // 0
10 % 2 // 0

// odd numbers
3 % 2 // 1
5 % 2 // 1
7 % 2 // 1
9 % 2 // 1
```

<br>

### The ternary operator

<p style ="text-align: justify">Condições também podem ser feitas utilizando o operador ternário <code>?</code>.</p>

```javascript
function evenOrOdd(number)
{

    if (number % 2 === 0)
    {
        return "even";
    }
    return "odd";
}
```

_Modo ternário_

```javascript
function evenOrOdd(number)
{
  return (number % 2 === 0) ? "even": "odd";
}
```

_O operador ternário possui a seguinte sintaxe_

```
condition ? expressionWhenTrue: expressionWhenFalse
```

</details>

<details>
  <summary><h2>Chapter 6: Arrays I</h2></summary>

### Arrays

```javascript
const users = []; // empty array
const grades = [10, 8, 13, 15]; // array of numbers
const attendees = ["Sam", "Alex"]; // array of strings
const values = [10, false, "John"]; // mixed
```

<p style ="text-align: justify">Vetores permitem você armazenar vários tipos de dados diferentes em uma mesma variável. Dessa forma, a variável em questão assume a condição de uma variável que possuem diversos valores individuais. Semelhante a Strins, também é possível as seguintes funções: <code>length</code>, <code>at()</code>, acesso pelo índice <code>[]</code> e adicionar novos valores ao final do vetor <code>push()</code></p>

```javascript
const numbers = [1, 2, 3, '4'];

numbers.push(11); // Ao final do vetor;
numbers[1] // 2;
numbers.at(-1) // 3;
numbers.length; // 5;
```

<br>

### Array forEach

```javascript
const grades = [10, 8, 13];

grades.forEach(function(grade)
{
    // do something with individual grade
    console.log(grade);
});
```

<p style ="text-align: justify">Iteração em um vetor é um dos conceito mais importantes em JavaScript. O método <code>.forEach</code> permite a você executar a função <code>callback</code> para item do vetor. Um <i>callback</i> é uma definição de função passada como parâmetro para outra função. No caso acima, a função <code>function(grade)</code> é passada como parâmetro para a iteração buscar os índices dentro do vetor.</p>

```javascript
const grades = [10, 8, 13];
// this is the callback
function(grade) {
    console.log(grade);
}
// call the callback with grade = 10 (grades[0])
console.log(grade); // will log 10
// call the callback with grade = 8 (grades[1])
console.log(grade); // will log 8
// call the callback with grade = 13 (grades[2])
console.log(grade); // will log 13
```

<br>

### How does it know that it's "grade"

```javascript
const grades = [10, 8, 13];

const gradis = [10, 0 ,10];

grades.forEach(function(grade)
{
    // do something with individual grade
    console.log(grade);
});

// Resultado
10
8
13

gradis.forEach(function(gradi)
{
    // do something with individual grade
    console.log(gradi);
});

// Resultado
10
0
10

```

<p style ="text-align: justify">Como pode ter observado, a variável grades é diferente do nome pasado como parâmetro. O que acontece é que no caso do <code>.forEach()</code> o javaScript supôe que o primeiro parâmetro passado é o parâmetro percetence ao vetor <code>grades</code> pois o método está sendo inicializado através da varíavel <code>grades</code></p>

<br>

### Return confusion

<p></p>

</details>

<details>
  <summary><h2>Chapter 6: Arrays II & callbacks</h2></summary>

  
</details>
