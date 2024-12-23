<details>
  <summary>
    <h2>Python Brasil: Lista de Exercícios</h2>
    <br>
    <h3>Resources:</h3>
    <h3>https://wiki.python.org.br/ListaDeExercicios</h3>
  </summary>
  

  ### Estrutura Sequencial

  #### 1. Faça um Programa que mostre a mensagem "Alo mundo" na tela.

```python
print("Alo Mundo")
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
</details>
