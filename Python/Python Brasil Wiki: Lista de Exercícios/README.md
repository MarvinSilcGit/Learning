<details>
  <summary>
    <h2>Python Brasil Wiki: Lista de Exercícios</h2>
  </summary>

  <br>

  <details>
    <summary>
      <h3>Estrutura Sequencial</h3>
    </summary>
    
  #### 1. Faça um Programa que mostre a mensagem "Alo mundo" na tela.
<details>
    <summary><h4>Resposta</h4></summary>

```python
print("Alô Mundo")
```

</details>

<br>

  #### 2. Faça um Programa que peça um número e então mostre uma mensagem com o número informado

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero = input("Digite o número")

print(numero)
```

  </details>

  <br>

  #### 3. Faça um Programa que peça dois números e imprima a soma.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero1 = int(input("Digite o primeiro número"))

numero2 = int(input("Digite o segundo número"))

print(numero1 + numero2)
```

  </details>

  <br>

  #### 4. Faça um Programa que peça as 4 notas bimestrais e mostre a média.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
nota1 = float(input("Digite a primeira nota"))

nota2 = float(input("Digite a segunda nota"))

nota3 = float(input("Digite a terceira nota"))

nota4 = float(input("Digite a quarta nota"))

média = (nota1 + nota2 + nota3 + nota4) / 4

print(média)
```

  </details>

  <br>

  #### 5. Faça um Programa que converta metros para centímetros.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
metros = 100

centimetros = 100 * 100

print(centimetros)
```
  
  </details>

  <br>
  
  #### 6. Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
raioCirculo = int(input("Digite o raio do círculo"))

area = 3.14 * (raioCirculo**2)
```

  </details>

  <br>

  #### 7. Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
ladoQuadrado = float(input("Digite um lado do quadrado: "))

areaQuadrado = ladoQuadrado**2 * 2

print("A área do quadrado é %.2f" % areaQuadrado)
```

  </details>

  <br>
  
  #### 8. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
salarioHora = float(input("Digite seu salário por hora: "))

horasMensal = float(input("Digite sua carga horária mensal: "))

salario = salarioHora * horasMensal

print("O salário mensal é R$ %.2f " % salario)
```

  </details>

  <br>

  #### 9. Faça um Programa que peça a temperatura em graus Fahrenheit, transforme e mostre a temperatura em graus Celsius.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
fahrenheit = float(input("Digite a temperautra para ser convertida de fahrenheit para celsius: "))

celsius = (fahrenheit - 32) / 1.8

print("A temperatura em %.1f° fahrenheit equivale à %.1f° celsius" % (fahrenheit, celsius))
```

  </details>

  <br>

  #### 10. Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Fahrenheit.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
celsius = float(input("Digite a temperatura para ser convertida de celsius para fahrenheit: "))

fahrenheit = (celsius * 1.8) + 32

print("A temperatura em %.1f° celsius equivale à %.1f° fahrenheit" % (celsius, fahrenheit))
```

  </details>

  <br>

  #### 11. Faça um Programa que peça 2 números inteiros e um número real. Calcule e mostre: o produto do dobro do primeiro com metade do segundo, a soma do triplo do primeiro com o terceiro e o terceiro elevado ao cubo. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
numeroInteiro1 = int(input("Digite o primeiro número inteiro: "))

numeroInteiro2 = int(input("Digite o segundo número inteiro: "))

numeroReal = float(input("Digite o número real: "))

resultado1 = numeroInteiro1 * 2 * numeroInteiro2 / 2

print(resultado1)

resultado2 = numeroInteiro1 * 3 + numeroReal

print(resultado2)

resultado3 = numeroReal**3

print(resultado3)
```

  </details>

  <br>

  #### 12. Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula: (72.7 * altura) - 58

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
altura = float(input("Digite sua altura: "))

pesoIdeal = (72.7 * altura) - 58

print("O peso ideal dessa pessoa é %.2f" % pesoIdeal)
```

  </details>

  <br>

  #### 13. Tendo como dado de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas: Para homens: (72.7 * altura) - 58 e para mulheres: (62.1 * altura) - 44.7 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
alturaHomem = float(input("Digite a altura do homem: "))

alturaMulher = float(input("Digite a altura da mulher: "))

pesoIdealHomem = (72.7 * alturaHomem) - 58

pesoIdealMulher = (62.1  * alturaMulher) - 44.7

print("O peso ideal desse homem é %.2f" % pesoIdealHomem)

print("O peso ideal dessa mulher é %.2f" % pesoIdealMulher)
```

  </details>

  <br>

  #### 14. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python


```

  </details>

  <br>

  #### 15. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês, sabendo-se que são descontados 11% para o Imposto de Renda, 8% para o INSS e 5% para o sindicato, faça um programa que nos dê: salário bruto, quanto pagou ao INSS, quanto pagou ao sindicato e o salário líquido. Calcule os descontos e o salário líquido conforme a ordem a seguir: + Salário Bruto : R$ - IR (11%) : R$ - INSS (8%) : R$ - Sindicato ( 5%) : R$ = Salário Liquido : R$ Obs.: Salário Bruto - Descontos = Salário Líquido. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python


```

  </details>

  <br>

  #### 16. aça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.

  <details>
    <summary><h4>Resposta</h4></summary>

```python

```

  </details>

  <br>

  #### 17. Faça um Programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00 ou em galões de 3,6 litros, que custam R$ 25,00. Informe ao usuário as quantidades de tinta a serem compradas e os respectivos preços em 3 situações: 
  1. Comprar apenas  latas de 18 litros.
  2. Comprar apenas galões de 3,6 litros
  3. Misturar latas e galões, de forma que o disperdício de tinta seja o menor possível. Acrescente 10% de folga e sempre arredonde os valores para cima, isto é, considere latas  cheias.
     
  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 18. Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  </details>

  
  <details>
    <summary>
      <h3>Estrutura de Decisão</h3>
    </summary>
  
  #### 1. Faça um Programa que peça dois números e imprima o maior deles. 

```python
numero1 = int(input("Digite o primeiro número: "))

numero2 = int(input("Digite o segundo número: "))

if numero1 > numero2:

    print("O maior número é %d" % numero1)

elif numero1 < numero2:

    print("O maior número é %d" % numero2)

else:

    print("Os dois números são iguais")
```

  #### 2. Faça um Programa que peça um valor e mostre na tela se o valor é positivo ou negativo.

```python
valor = float(input("Digite um número: "))

if valor < 0:

    print("O valor %.1f é negativo" % valor)

else:

    print("O valor %.1f é positivo" % valor)
```
  
  #### 3. Faça um Programa que verifique se uma letra digitada é "F" ou "M". Conforme a letra escrever: F - Feminino, M - Masculino ou Sexo Inválido.

```python
sexo = input("Digite o sexo: ")

if sexo == "F" or sexo == "f":

    print("O sexo é Feminino")

elif sexo == "M" or sexo == "m":

    print("O sexo é Masculino")

else:

    print("O sexo é inválido")
```
  
  #### 4. Faça um Programa que verifique se uma letra digitada é vogal ou consoante.

```python
listaConsoante = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z", "ç",
                  "A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z", "Ç"]

listaVogal = ["A", "E", "I", "O", "U", "a", "e", "i", "o", "u"]

letraBusca = input("Digite a letra para saber se é vogal ou consoante: ")

if letraBusca in listaVogal:

    print("A letra '%s' é Vogal" % letraBusca)

elif letraBusca in listaConsoante:

    print("A letra '%s' é Consoante" % letraBusca)

else:

    print("A letra '%s' não é nem vogal nem consoante" % letraBusca)
```
  
  #### 5. Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar: A mensagem "Aprovado", se a média alcançada for maior ou igual a 7; A mensagem "Reprovado", se a média for menor do que 7; A mensagem "Aprovado com Distinção", se a média for igual a 10. 

```python
nota1 = float(input("Digite a primeira nota: "))

nota2 = float(input("Digite a segunda nota: "))

media = (nota1 + nota2) / 2

if media < 7:

    print("O aluno foi reprovado com a nota %.2f" % media)

elif media < 10:

    print("O aluno foi aprovado com a nota %.2f" % media)

else:

    print("O aluno foi aprovado com distinção através da nota %.2f" % media)
```
  
  #### 6. Faça um Programa que leia três números e mostre o maior deles. 

```python
numero1 = float(input("Digite o primeiro número: "))

numero2 = float(input("Digite o segundo número: "))

numero3 = float(input("Digite o terceiro número: "))

if numero1 > numero2 and numero1 > numero3:

    print("O primeiro número é maior")

elif numero2 > numero1 and numero2 > numero3:

    print("O segundo número é maior")

elif numero3 > numero2  and numero3 > numero1:

    print("O terceiro número é maior")
```
  </details>

</details>
