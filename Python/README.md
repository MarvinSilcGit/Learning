<details>
  <summary>
    <h2>Python Brasil Wiki: Lista de Exercícios</h2>
  </summary>
  <h3>Resources:</h3>
  <h3>https://wiki.python.org.br/ListaDeExercicios</h3>

  <br>

  <details>
    <summary>
      <h3>Estrutura Sequencial</h3>
    </summary>
    
  #### 1. Faça um Programa que mostre a mensagem "Alo mundo" na tela.

```python
print("Alô Mundo")
```

  #### 2. Faça um Programa que peça um número e então mostre uma mensagem com o número informado

```python
numero = input("Digite o número")

print(numero)
```

  #### 3. Faça um Programa que peça dois números e imprima a soma.

```python
numero1 = int(input("Digite o primeiro número"))

numero2 = int(input("Digite o segundo número"))

print(numero1 + numero2)
```

  #### 4. Faça um Programa que peça as 4 notas bimestrais e mostre a média.

```python
nota1 = float(input("Digite a primeira nota"))

nota2 = float(input("Digite a segunda nota"))

nota3 = float(input("Digite a terceira nota"))

nota4 = float(input("Digite a quarta nota"))

print((nota1+nota2+nota3+nota4)/4)
```

  #### 5. Faça um Programa que converta metros para centímetros.

```python
metros = 100

centimetros = 100*100

print(centimetros)
```

  #### 6. Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.

```python
raioCirculo = int(input("Digite o raio do círculo"))

area = 3.14 * (raioCirculo**2)
```

  #### 7. Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.

```python

```

  #### 8. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês. 

```python


```
  </details>

  <details>
    <summary>
      <h3>Estrutura de Decisão</h3>
    </summary>

  </details>

</details>


<details>
  <summary>
    <h2>Introdução à programação com Python 2ª Edição</h2>
  </summary>

  ### Atividades

  #### Exercício 3.7: Faça um programa que peça dois números inteiros. Imprima a soma desses dois números na tela.

```python
numero1 = int(input("Digite o primeiro número: "))

numero2 = int(input("Digite o segundo número: "))

total = numero1 + numero2

print("A soma de %d + %d é igual a %d" % (numero1, numero2, total))
```

  #### Exercício 3.8: Escreva um programa que leia um valor em metros e o exiba convertido em milímetros.

```python
valorMetro = float(input("Digite o valor para ser convertido em milímetros: "))

valorMilimetro = valorMetro * 1000

print("O valor de %.2f metro(s) é equivalente à %d milímetro(s)" %(valorMetro, valorMilimetro))
```

  #### Exercício 3.9: Escreva um programa que leia a quantidade de dias, horas, minutos e segundos do usuário. Calcule o total em segundos.

```python
dias = int(input("Digite a quantidade de dia: "))

horas = int(input("Digite a quantidade de horas: "))

minutos = int(input("Digite a quantidade de minutos: "))

segundos = int(input("Digite a quantidade de segundos: "))

horas = dias * 24 + horas

minutos = horas * 60 + minutos

segundos = minutos * 60 + segundos

print("%d dia(s) dura ao equivalente à %d segundos" % (dias, segundos))
```
  #### Exercício 3.10: Faça um programa que calcule o aumento de um salário. Ele deve solicitar o valor do salário e a porcentagem do aumento. Exiba o valor do aumento e do novo salário.

```python
salario = float(input("digite o salário recebido anualmente: "))

porcentagem = float(input("qual a porcentagem de aumento? "))

aumento = (porcentagem / 10) * (salario / 10)

total = salario + aumento

print("com um salario inicial de R$ %.2f e um aumento de R$ %.2f, o funcionario passará à receber R$ %.2f" % (salario, aumento, total))
```
  #### Exercício 3.11: Faça um programa que solicite o preço de uma mercadoria e o percentual de desconto. Exiba o valor do desconto e o preço a pagar.

```python
precoMercadoria = float(input("Digite o preço da mercadoria: "))

desconto = float(input("Digite a pocentagem de desconto: "))

valorDesconto = (desconto / 10 ) * (precoMercadoria / 10)

precoTotal = precoMercadoria - valorDesconto

print("O valor do desconto é de R$ %.2f. E o preço à pagar é de R$ %.2f" % (valorDesconto, precoTotal))
```

  #### Exercício 3.12 Escreva um programa que calcule o tempo de uma viagem de carro. Pergunte a distância a percorrer e a velocidade média esperada para a viagem.

```python
distancia = float(input("Qual foi a distância percorrida em kilômetros? "))

velocidadeMedia = float(input("Digite a velocidade média: "))

tempo = distancia / velocidadeMedia

print("O tempo necessário para a viagem foi de %.1f hora(s)" % tempo)
```
  
  #### Exercício 3.13 Escreva um programa que converta uma temperatura digitada em °C em °F.

```python
celsius = float(input("Digite a temperatura para ser convertida de celsius para fahrenheit: "))

fahrenheit = (celsius * 1.8) + 32

print("A temperatura em %.1f° celsius equivale à %.1f° fahrenheit" % (celsius, fahrenheit))

fahrenheit = float(input("Digite a temperautra para ser convertida de fahrenheit para celsius: "))

celsius = (fahrenheit - 32) / 1.8

print("A temperatura em %.1f° fahrenheit equivale à %.1f° celsius" % (fahrenheit, celsius))
```

  #### Exercício: 3.14: Escreva um programa que pergunte a quantidade de km percorridos por um carro alugado pelo usuário, assim como a quantidade de dias pelos quais o carro foi alugado. Calcule o preço a pagar, sabendo que o carro custa R$ 60 por dia e R$ 0,15 por km rodado.

```python
kilometrosPercorridos = float(input("Quantos kilômetros foram percorridos com o carro? "))

diasAlugados = int(input("Por quantos dias o carro foi alugado? "))

diariaAluguel = 60 * diasAlugados

custoKilometro = 0.15 * kilometrosPercorridos

custoTotalAluguel = diariaAluguel + custoKilometro

print("O custo total do aluguel foi de R$ %.2f, por um carro que foi alugado por %d dias e com %.1f kilômetros percorridos" % (custoTotalAluguel, diasAlugados, kilometrosPercorridos))
```

</details>

<details>

  <summary>
    <h2>Techie Delight</h2>
  </summary>
  <h3>Resources:</h3>
  <h3>https://www.techiedelight.com/data-structures-and-algorithms-problems/</h3>
  <br>
  
  ### Data Structures and Algorithm Problems

  #### 1. Find a pair with the given sum in an array

```python
# Source: https://www.techiedelight.com/find-pair-with-given-sum-array/

import random

# Fix this code. It should only find a pair with sum, not sum and sub

counter1, counter2, array, randomLen, par = 0, 0, [], [], []

goal = random.randint(1, 30)

for Counter in range(15):

    randomLen.append(random.randint(1, 15))

    if randomLen[Counter] in array:

        continue

    else:

        array.append(randomLen[Counter])

while counter1 != len(array):

    if array[counter1] == array[counter2]:

        counter1 += 1

        continue

    elif array[counter1] + array[counter2] == goal or array[counter1] - array[counter2] == goal:

        if array[counter2] and array[counter1] not in par:

            par.append(array[counter1])

            par.append(array[counter2])

        else:

            pass

    if counter1 == len(array)-1:

        counter2 += 1

        counter1 = 0

        continue

    else:

        counter1 += 1

print("The Bullseye-Array", array)

print()

print("The Goal is", goal)

print()

if len(par) > 1:

    print("The pairs that matchs:", par)

elif len(par) == 1:

    print("The only one pair that matchs:", par)

```

  #### 2. Check if a subarray with 0 sum exists or not

```python
# Source: https://www.techiedelight.com/check-subarray-with-0-sum-exists-not/

import random

counter, arrLen, zeroSum, zeroSum1, zeroSum2, subArr0, subArr1, subArr2, masterArr = 0, 15, 0, 0, 0, [], [], [], []

while counter != arrLen//3:

    subArr0.append(random.randint(-30, 30))

    subArr1.append(random.randint(-30, 30))

    subArr2.append(random.randint(-30, 30))

    counter += 1

    if counter == arrLen//3:

        masterArr.append(subArr0)

        masterArr.append(subArr1)

        masterArr.append(subArr2)

        for Counter1 in range(len(masterArr[0])):

            zeroSum += masterArr[0][Counter1]

        for Counter2 in range(len(masterArr[1])):

            zeroSum1 += masterArr[1][Counter2]

        for Counter3 in range(len(masterArr[2])):

            zeroSum2 += masterArr[2][Counter3]

print(masterArr)

print()

if zeroSum == 0:

    print("The Subarray", masterArr[0], "is sum 0")

elif zeroSum1 == 0:

    print("The Subarray", masterArr[1], "is sum 0")

elif zeroSum2 == 0:

    print("The Subarray", masterArr[2], "is sum 0")

elif zeroSum == 0 and zeroSum1 == 0 and zeroSum2 == 0:

    print("All the Subarrays are sum 0")

elif zeroSum + zeroSum1 + zeroSum2 == 0:

    print("The Array is sum 0")

else:

    print("There's no 0 sum")
```

  #### 3. Print all subarrays with 0 sum

```python

```

  #### 4. Sort binary array in linear time

```python
# Source https://www.techiedelight.com/sort-binary-array-linear-time/

import random

array, exchange, counter1 = [], [], 0

for counter in range(0, random.randint(5, 30)):

    array.append(random.randrange(0, 2))

print("The original Array is: ", array)

while counter1 != len(array)-1:

    if array[counter1] > 0:

        exchange.append(array.pop(counter1))

        counter1 = 0

    else:

        counter1 += 1

        continue

while True:

    array.append(exchange.pop(0))

    if len(exchange) == 0:

        break

print("The new Array sorted in Binary: ", array)
```

  #### 5. Find maximum length subarray having a given sum

```python
# Source https://www.techiedelight.com/find-maximum-length-sub-array-having-given-sum/

## Fix this code. Isn't working as supposed to be

import random

counter1, counter2, sum, array, randomLen, subArray = 0, 1, 0, [], [], []

goal = random.randint(1, 30)

for counter in range(15):

    randomLen.append(random.randint(1, 15))

    if randomLen[counter] in array:

        continue

    else:

        array.append(randomLen[counter])

sum = array[counter1]

subArray.append(array[counter1])

while counter1 != len(array) - 1:

    if sum + array[counter2] <= goal:

        subArray.append(array[counter2])

        sum += array[counter2]

# if Sum != Goal and Array[Counter2 + 1] + Sum > Goal:

# Sum -= Array[Counter2]

    counter2 += 1

    if counter2 == len(array):

        counter1 += 1

        counter2 = counter1 + 1

        print(subArray)

        sum = array[counter1]

        subArray.append("|")

        if array[counter1] <= goal:

            subArray.append(array[counter1])

print()
print(array)
print(goal)
print(subArray)

# 24
# 2, 6, 10, 9, 11, 15, 12, 13
```

</details>
