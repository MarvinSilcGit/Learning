<details>
  <summary>
    <h2>Introdução à Programação com Python 2ª Edição</h2>
  </summary>

  <details>
    <summary>
      <h3>Variáveis e Entrada de Dados</h3>
    </summary>

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

  #### Exercício 3.14: Escreva um programa que pergunte a quantidade de km percorridos por um carro alugado pelo usuário, assim como a quantidade de dias pelos quais o carro foi alugado. Calcule o preço a pagar, sabendo que o carro custa R$ 60 por dia e R$ 0,15 por km rodado.

```python
kilometrosPercorridos = float(input("Quantos kilômetros foram percorridos com o carro? "))

diasAlugados = int(input("Por quantos dias o carro foi alugado? "))

diariaAluguel = 60 * diasAlugados

custoKilometro = 0.15 * kilometrosPercorridos

custoTotalAluguel = diariaAluguel + custoKilometro

print("O custo total do aluguel foi de R$ %.2f, por um carro que foi alugado por %d dias e com %.1f kilômetros percorridos" % (custoTotalAluguel, diasAlugados, kilometrosPercorridos))
```

  #### Exercício 3.15: Escreva um programa para calcular a redução do tempo de vida de um fumante. Pergunte a quantidade de cigarros fumados por dia e quantos anos ele já fumou. Considere que um fumante perde 10 minutos de vida a cada cigarro, calcule quantos dias de vida um fumante perderá. Exiba o total em dias.

```python
cigarrosDia = int(input("Quantos cigarros você fumou por dia? "))

cigarrosAnos = int(input("Por quantos anos você fomou? "))

cigarrosTotal = 365 * cigarrosAnos * cigarrosDia

diasPerdidos = cigarrosTotal * 10 / 60 / 24

print("Você já perdeu %d dias fumando %d cigarro(s) por dia, por %d anos" % (diasPerdidos, cigarrosDia, cigarrosAnos))
```

  </details>

  <details>
    <summary>
      <h3>Condições</h3>
    </summary>
  
  #### Exercício 4.2: Escreva um programa que pergunte a velocidade do carro de um usuário. Caso ultrapasse 80 km/h, exiba uma mensagem dizendo que o usuário foi multado. Nesse caso, exiba o valor da multa, cobrando R$ 5 por km acima de 80 km/h.

```python
velocidade = int(input("Qual a velocidade do veículo? "))

if velocidade > 80:

    multa = (velocidade - 80) * 5

    print("O condutor foi multado em R$ %.2f por estar %.0f quilômetro(s) acima do limite de velodade" % (multa, velocidade - 80))

if velocidade <= 80:

    print("O condutor não foi multado por estar dentro do limite de velocidade")
```

  #### Exercício 4.3: Escreva um programa que leia três números e que imprima o maior e o menor.

```python
numero1 = int(input("Digite o primeiro número: "))

numero2 = int(input("Digite o segundo número: "))

numero3 = int(input("Digite o terceiro número: "))

if numero1 > numero2 > numero3:

    print("%d, %d" % (numero1, numero3))

if numero1 > numero3 > numero2:

    print("%d, %d" % (numero1, numero2))

if numero2 > numero1 > numero3:

    print("%d, s%d" % (numero2, numero3))

if numero2 > numero3 > numero1:

    print("%d, r%d" % (numero2, numero1))

if numero3 > numero2 > numero1:

    print("%d, t%d" % (numero3, numero1))

if numero3 > numero1 > numero2:

    print("%d, u%d" % (numero1, numero2))
```

  #### Exercício 4.4: Escreva um programa que pergunte o salário do funcionário e calcule o valor do aumento. Para salários superiores a R$ 1.250,00, calcule um aumento de 10%. Para os inferiores ou iguais, de 15%.

```python
salario = float(input("Qual o seu salário? "))

if salario > 1250:

    aumento1 = salario / 10

    salarioFinal = salario + aumento1

    print("O salário  de R$ %.2f passará a ser de R$ %.2f, com um aumento de R$ %.2f" % (salario, salarioFinal, aumento1))

else:

    if salario <= 1250:

        aumento1 = salario * 0.15

        salarioFinal = salario + aumento1

        print("O salário de R$ %.2f passará a ser de R$ %.2f, com um aumento de R$ %.2f" % (salario, salarioFinal, aumento1))
```

  #### Exercício 4.6: Escreva um programa que pergunte a distância que um passageiro deseja percorrer em km. Calcule o preço da passagem, cobrando R$ 0,50 por km   para viagens de até de 200 km, e R$ 0,45 para viagens mais longas.

```python
distancia = float(input("Qual a distância que irá percorrer? "))

if distancia <= 200:

    passagem = distancia * 0.50

    print("Com uma distância inferior à 200 kilômetros o passageiro irá pagar R$ %.2f pela distância de %.2f kilômetros percorridos"%(passagem, distancia))

else:

    passagem = distancia * 0.45

    print("Com uma distância superior à 200 kilômetros o passageiro irá pagar R$ %.2f pela distância de %.2f kilômetros percorridos"%(passagem, distancia))
```

  #### Exercício 4.8:

```python
numero1 = float(input("Digite o primeiro valor: "))

print("Digite 1 para somar")

print("Digite 2 para subtrair")

print("Digite 3 para multiplicar")

print("Digite 4 para dividir")

print()

operadores = input("Qual operador deseja utilizar na operação? ")

print()

numero2 = float(input("Digite o segundo valor: "))

print()

if operadores == "1":

    soma = numero1 + numero2

    print("O resultado da soma entre %.1f e %.1f é %.1f" % (numero1, numero2, soma))

elif operadores == "2":

    soma = numero1 - numero2

    print("O resultado da subtração entre %.1f e %.1f é %.1f" % (numero1, numero2, soma))

elif operadores == "3":

    soma = numero1 * numero2

    print("O resultado da multiplicação entre %.1f e %.1f é %.1f" % (numero1, numero2, soma))

elif operadores == "4":

    soma = numero1 / numero2

    print("O resultado da divisão entre %.1f e %.1f é %.1f" % (numero1, numero2, soma))

elif operadores != 1 and operadores != 2 and operadores != 3 and operadores != 4:

    print("Digite um número entre 1 e 4 para concluir a operação")
```

  #### Exercício 4.9: Escreva um programa para aprovar o empréstimo bancário para compra de uma casa. O programa deve perguntar o valor da casa a comprar, o salário e a quantidade de anos a pagar. O valor da prestação mensal não pode ser superior a 30% do salário. Calcule o valor da prestação como sendo o valor da casa a comprar dividido pelo número de meses a pagar.

```python
valorCasa = float(input("Qual o valor da casa? "))

salario = float(input("Qual o seu salário? "))

anos = int(input("Irá pagar em quantos anos? "))

anos *= 12

parcelasMensais = valorCasa / anos

porcentagem = salario / 100 * 30

if valorCasa / anos  < porcentagem:

    print("O usuário poderá contratar o financiamento, pois parcela não é superior a um terço de sua renda mensal. As parcelas serão de R$ %.2f" % parcelasMensais)

else:

    print("O usuário não poderá contratar o financiamento, pois parcela é superior a um terço de sua renda mensal. As parcelas seriam de R$ %.2f" % parcelasMensais)
```
  
  #### Exercício 4.10: Escreva um programa que calcule o preço a pagar pelo fornecimento de energia elétrica. Pergunte a quantidade de kWh consumida e o tipo de instalação: R para residências, I para indústrias e C para comércios. Calcule o preço a pagar de acordo com a tabela a seguir:

  ##### Preço por tipo e faixa de consumo

  |**Tipo**  |**Faixa(kWh)**  |**Preço**  |
  |------|---------------|--------- |
  |Residencial  |Até 500 | R$ 0,40  |
  |      |Acima de 500   | R$ 0,65  |
  |Comercial  |Até 1000  | R$ 0,55  |
  |      |Acima de 1000  | R$ 0,60  |
  |Industrial  |Até 5000 | R$ 0,55  |
  |      |Acima de 5000  | R$ 0,60  |
 
```python
print("Digite 1 para residências")

print("Digite 2 para comércios")

print("Digite 3 para indústrias")

tipo = int(input("Qual o tipo de instalação? "))

if tipo == 1:

    consumo = float(input("Quanto foi consumido? "))

    if consumo <= 500:

        faixa = consumo * 0.40

        print("A quantidade consumida custou R$ %.2f" % faixa)

    elif consumo > 500:

        faixa = consumo * 0.65

        print("A quantidade consumida custou R$ %.2f" % faixa)

elif tipo == 2:

    consumo = float(input("Quanto foi consumido? "))

    if consumo <= 1000:

        faixa = consumo*0.55

        print("A quanidade consumida custou R$ %.2f" % faixa)

    elif consumo > 1000:

        faixa = consumo*0.60

        print("A quantidade consumida custou R$ %.2f" % faixa)

elif tipo == 3:

    consumo = float(input("Quanto foi consumido? "))

    if consumo <= 5000:

        faixa = consumo*0.55

        print("A quantidade consumida custou %.2f" % faixa)

    elif consumo > 5000:

        faixa = consumo*0.60

        print("A quantidade consumida custou %.2f" % faixa)

else:

    print("Digite um valor entre 1 e 3 para proseguir para o próximo menu")
```

  </details>

  <details>
    <summary>
      <h3>Repetições</h3>
    </summary>
    
  #### Exercício 5.1-2:

```python
contador1 = 0

while contador1 != 4:

    print(contador1)

    contador1 += 1


contador2 = 0

while contador2 != 51:

    print(contador2)

    contador2 += 1


contador3 = 50

while contador3 != 101:

    print(contador3)

    contador3 += 1
```

  #### Exercício 5.3: Faça um programa para escrever a contagem regressiva do lançamento de um foguete. O programa deve imprimir '10, 9, 8, ..., 1, 0 e Fogo!' na tela.

```python
contador = 1

contagem = 11

while contador != 0:

    while contagem != 1:

        contagem -= 1

        print(contagem)

    print("Fogo!")

    contador = int(input("Digite 0 para interromper a execução: "))
```

  #### Exercício 5.4: Modifique o programa anterior para imprimir de 1 até o número digitado pelo usuário, mas, dessa vez, apenas os números ímpares.

```python
contador1 = 1

while contador1 != 0:

    valorInicial = int(input("Digite o valor inicial: "))

    if valorInicial != 1:

        print("Número incorreto")

        continue

    else:

        valorFinal = int(input("Digite o valor final: "))

        while valorInicial < valorFinal:

            print(valorInicial)

            valorInicial += 2

        print()

        contador1 = int(input("Digite 0 para interromper a execução: "))
```

  #### Exercício 5.5: Reescreva o programa anterior para escrever os 10 primeiros múltiplos de 3.

```python
for contador in range(1, 11):

    print(contador * 3)
```

  #### Exercício 5.6: Altere o programa anterior para exibir os resultados no mesmo formato de uma tabuada: 2x1 = 2, 2x2=4, ...

```python
for contador in range(1, 11):

    print(contador * 2)
```

  #### Exercício 5.7: Modifique o programa anterior de forma que o usuário também digite o início e o fim da tabuada, em vez de começar com 1 e terminar com 10.

```python
contador = 0

while contador != 1:

    inicioTabuada = int(input("Digite o valor inicial da tabuada: "))
    
    fimTabuada = int(input("Digite o valor final da tabuada: "))
    
    for contador in range(inicioTabuada, fimTabuada + 1):
    
        print(contador * 2)
        
    print()

    contador = int(input("Digite 0 para interromper a execução: "))
```

  #### Exercício 5.8: Escreva um programa que leia dois números. Imprima o resultado da multiplicação do primeiro pelo segundo. Utilize apenas os operadores de soma e subtração para calcular o resultado. Lembre-se de que podemos entender a multiplicação de dois números como somas sucessivas de um deles. Assim, 4 × 5 = 5 + 5 + 5 + 5 = 4 + 4 + 4 + 4 + 4.

```python
contador = 1

resultado = 0

while contador != 0:

    valor1 = int(input("Digite um valor: "))

    valor2 = int(input("Digite outro valor: "))

    for contador2 in range(0, valor2):

        print("%d + %d = %d" % (resultado, valor1, resultado + valor1))

        resultado += valor1

    print()

    contador = int(input("Digite 0 para interromper a execução: "))
```

  #### Exercício 5.9: Escreva um programa que leia dois números. Imprima a divisão inteira do primeiro pelo segundo, assim como o resto da divisão. Utilize apenas os operadores de soma e subtração para calcular o resultado. Lembre-se de que podemos entender o quociente da divisão de dois números como a quantidade de vezes que podemos retirar o divisor do dividendo. Logo, 20 ÷ 4 = 5, uma vez que podemos subtrair 4 cinco vezes de 20.

```python
contador1 = 1

while contador1 != 0:

    restoInteiro = 0

    resto = 0

    valor1 = float(input("Digite o primeiro valor: "))

    valor2 = float(input("Digite o segundo valor: "))

    if valor1 == 0 or valor2 == 0:

        print("Divisão por zero inválida")

        print()

        continue
        
    else:

        if valor1 == valor2:
    
            restoInteiro = 1
    
            print()
    
        elif valor1 > valor2:
    
            while valor2 + resto < valor1:
    
                restoInteiro += 1
    
                resto += valor2
    
            resto = valor1 - resto
    
        else:
    
            while valor1 + resto < valor2:
    
                resto += valor1
    
            while resto != valor2:
    
                resto += 1
    
        print("O resto inteiro da divisão entre %.1f e %.1f é: %.1f. E o resto da divisão é: %.1f" % (valor1, valor2, restoInteiro, resto))
    
        print()
    
        contador1 = int(input("Digite 0 para interromper a execução: "))
    
        print()
```

  #### Exercício 5.10: Modifique o programa da listagem 5.10 para que aceite respostas com letras maiúsculas e minúsculas em todas as questões.

```python

```

  #### Exercício 5.11-12: Escreva um programa que pergunte o depósito inicial e a taxa de juros de uma poupança. Exiba os valores mês a mês para os 24 primeiros meses. Escreva o total ganho com juros no período.

```python

```

  #### Exercício 5.13: Escreva um programa que pergunte o valor inicial de uma dívida e o juro mensal. Pergunte também o valor mensal que será pago. Imprima o número de meses para que a dívida seja paga, o total pago e o total de juros pago.

```python

```

  #### Exercício 5.14: Escreva um programa que leia números inteiros do teclado. O programa deve ler os números até que o usuário digite 0 (zero). No final da execução, exiba a quantidade de números digitados, assim como a soma e a média aritmética.

```python

```

  #### Exercício 5.15: Escreva um programa para controlar uma pequena máquina registradora. Você deve solicitar ao usuário que digite o código do produto e a quantidade comprada. Utilize a tabela de códigos abaixo para obter o preço de cada produto:

  |**Código**|**Preço**|
  |----------|---------|
  |1         | R$ 0,50 |
  |2         | R$ 1,00 |
  |3         | R$ 4,00 |
  |5         | R$ 7,00 |
  |9         | R$ 8,00 |

  #### Seu programa deve exibir o total das compras depois que o usuário digitar 0. Qualquer outro código deve gerar a mensagem de erro “Código inválido”.
  

```python

```

  </details>

</details>
