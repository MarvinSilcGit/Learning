<h2>Introdução à Programação com Python 2ª Edição</h2>

  <details>
    <summary>
      <h3>Capítulo 3: Variáveis e Entrada de Dados</h3>
    </summary>

  #### Exercício 3.7: Faça um programa que peça dois números inteiros. Imprima a soma desses dois números na tela.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero1 = int(input("Digite o primeiro número: "))

numero2 = int(input("Digite o segundo número: "))

total = numero1 + numero2

print("A soma de %d + %d é igual a %d" % (numero1, numero2, total))
```

  </details>

  <br>

  #### Exercício 3.8: Escreva um programa que leia um valor em metros e o exiba convertido em milímetros.

  <details>
    <summary><h4>Resposta</h4></summary>
  
```python
valorMetro = float(input("Digite o valor para ser convertido em milímetros: "))

valorMilimetro = valorMetro * 1000

print("O valor de %.2f metro(s) é equivalente à %d milímetro(s)" %(valorMetro, valorMilimetro))
```

  </details>

  <br>

  #### Exercício 3.9: Escreva um programa que leia a quantidade de dias, horas, minutos e segundos do usuário. Calcule o total em segundos.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>
  
  #### Exercício 3.10: Faça um programa que calcule o aumento de um salário. Ele deve solicitar o valor do salário e a porcentagem do aumento. Exiba o valor do aumento e do novo salário.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
salario = float(input("digite o salário recebido anualmente: "))

porcentagem = float(input("qual a porcentagem de aumento? "))

aumento = (porcentagem / 10) * (salario / 10)

total = salario + aumento

print("com um salario inicial de R$ %.2f e um aumento de R$ %.2f, o funcionario passará à receber R$ %.2f" % (salario, aumento, total))
```

  </details>

  <br>
  
  #### Exercício 3.11: Faça um programa que solicite o preço de uma mercadoria e o percentual de desconto. Exiba o valor do desconto e o preço a pagar.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
precoMercadoria = float(input("Digite o preço da mercadoria: "))

desconto = float(input("Digite a pocentagem de desconto: "))

valorDesconto = (desconto / 10 ) * (precoMercadoria / 10)

precoTotal = precoMercadoria - valorDesconto

print("O valor do desconto é de R$ %.2f. E o preço à pagar é de R$ %.2f" % (valorDesconto, precoTotal))
```

  </details>

  <br>
  
  #### Exercício 3.12 Escreva um programa que calcule o tempo de uma viagem de carro. Pergunte a distância a percorrer e a velocidade média esperada para a viagem.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
distancia = float(input("Qual foi a distância percorrida em kilômetros? "))

velocidadeMedia = float(input("Digite a velocidade média: "))

tempo = distancia / velocidadeMedia

print("O tempo necessário para a viagem foi de %.1f hora(s)" % tempo)
```

  </details>

  <br>
  
  #### Exercício 3.13 Escreva um programa que converta uma temperatura digitada em °C em °F.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
celsius = float(input("Digite a temperatura para ser convertida de celsius para fahrenheit: "))

fahrenheit = (celsius * 1.8) + 32

print("A temperatura em %.1f° celsius equivale à %.1f° fahrenheit" % (celsius, fahrenheit))

fahrenheit = float(input("Digite a temperautra para ser convertida de fahrenheit para celsius: "))

celsius = (fahrenheit - 32) / 1.8

print("A temperatura em %.1f° fahrenheit equivale à %.1f° celsius" % (fahrenheit, celsius))
```

  </details>
  
  <br>

  #### Exercício 3.14: Escreva um programa que pergunte a quantidade de km percorridos por um carro alugado pelo usuário, assim como a quantidade de dias pelos quais o carro foi alugado. Calcule o preço a pagar, sabendo que o carro custa R$ 60 por dia e R$ 0,15 por km rodado.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
kilometrosPercorridos = float(input("Quantos kilômetros foram percorridos com o carro? "))

diasAlugados = int(input("Por quantos dias o carro foi alugado? "))

diariaAluguel = 60 * diasAlugados

custoKilometro = 0.15 * kilometrosPercorridos

custoTotalAluguel = diariaAluguel + custoKilometro

print("O custo total do aluguel foi de R$ %.2f, por um carro que foi alugado por %d dias e com %.1f kilômetros percorridos" % (custoTotalAluguel, diasAlugados, kilometrosPercorridos))
```

  </details>

  <br>

  #### Exercício 3.15: Escreva um programa para calcular a redução do tempo de vida de um fumante. Pergunte a quantidade de cigarros fumados por dia e quantos anos ele já fumou. Considere que um fumante perde 10 minutos de vida a cada cigarro, calcule quantos dias de vida um fumante perderá. Exiba o total em dias.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
cigarrosDia = int(input("Quantos cigarros você fumou por dia? "))

cigarrosAnos = int(input("Por quantos anos você fomou? "))

cigarrosTotal = 365 * cigarrosAnos * cigarrosDia

diasPerdidos = cigarrosTotal * 10 / 60 / 24

print("Você já perdeu %d dias fumando %d cigarro(s) por dia, por %d anos" % (diasPerdidos, cigarrosDia, cigarrosAnos))
```
  
  </details>

  <br>
    
  </details>

  <details>
    <summary>
      <h3>Capítulo 4: Condições</h3>
    </summary>
  
  #### Exercício 4.2: Escreva um programa que pergunte a velocidade do carro de um usuário. Caso ultrapasse 80 km/h, exiba uma mensagem dizendo que o usuário foi multado. Nesse caso, exiba o valor da multa, cobrando R$ 5 por km acima de 80 km/h.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
velocidade = int(input("Qual a velocidade do veículo? "))

if velocidade > 80:

    multa = (velocidade - 80) * 5

    print("O condutor foi multado em R$ %.2f por estar %.0f quilômetro(s) acima do limite de velodade" % (multa, velocidade - 80))

if velocidade <= 80:

    print("O condutor não foi multado por estar dentro do limite de velocidade")
```

  </details>

  <br>

  #### Exercício 4.3: Escreva um programa que leia três números e que imprima o maior e o menor.

  <details>
    <summary><h4>Resposta</h4></summary>
  
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

  </details>

  <br>
  
  #### Exercício 4.4: Escreva um programa que pergunte o salário do funcionário e calcule o valor do aumento. Para salários superiores a R$ 1.250,00, calcule um aumento de 10%. Para os inferiores ou iguais, de 15%.

  <details>
    <summary><h4>Resposta</h4></summary>
  
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

  </details>

  <br>

  #### Exercício 4.6: Escreva um programa que pergunte a distância que um passageiro deseja percorrer em km. Calcule o preço da passagem, cobrando R$ 0,50 por km   para viagens de até de 200 km, e R$ 0,45 para viagens mais longas.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
distancia = float(input("Qual a distância que irá percorrer? "))

if distancia <= 200:

    passagem = distancia * 0.50

    print("Com uma distância inferior à 200 kilômetros o passageiro irá pagar R$ %.2f pela distância de %.2f kilômetros percorridos"%(passagem, distancia))

else:

    passagem = distancia * 0.45

    print("Com uma distância superior à 200 kilômetros o passageiro irá pagar R$ %.2f pela distância de %.2f kilômetros percorridos"%(passagem, distancia))
```
  </details>

  <br>

  #### Exercício 4.8:

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>

  #### Exercício 4.9: Escreva um programa para aprovar o empréstimo bancário para compra de uma casa. O programa deve perguntar o valor da casa a comprar, o salário e a quantidade de anos a pagar. O valor da prestação mensal não pode ser superior a 30% do salário. Calcule o valor da prestação como sendo o valor da casa a comprar dividido pelo número de meses a pagar.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>
  
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

 <details>
    <summary><h4>Resposta</h4></summary>
   
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

  <br>

  </details>

  <details>
    <summary>
      <h3>Capítulo 5: Repetições</h3>
    </summary>
    
  <br>
    
  #### Exercício 5.1-2:

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>

  #### Exercício 5.3: Faça um programa para escrever a contagem regressiva do lançamento de um foguete. O programa deve imprimir '10, 9, 8, ..., 1, 0 e Fogo!' na tela.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>
  
  #### Exercício 5.4: Modifique o programa anterior para imprimir de 1 até o número digitado pelo usuário, mas, dessa vez, apenas os números ímpares.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>
  
  #### Exercício 5.5: Reescreva o programa anterior para escrever os 10 primeiros múltiplos de 3.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
for contador in range(1, 11):

    print(contador * 3)
```

  </details>

  <br>
  
  #### Exercício 5.6: Altere o programa anterior para exibir os resultados no mesmo formato de uma tabuada: 2x1 = 2, 2x2=4, ...

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
for contador in range(1, 11):

    print(contador * 2)
```

  </details>

  <br>

  #### Exercício 5.7: Modifique o programa anterior de forma que o usuário também digite o início e o fim da tabuada, em vez de começar com 1 e terminar com 10.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

while contador != 0:

    inicioTabuada = int(input("Digite o valor inicial da tabuada: "))
    
    fimTabuada = int(input("Digite o valor final da tabuada: "))
    
    for contador in range(inicioTabuada, fimTabuada + 1):
    
        print(contador * 2)
        
    print()

    contador = int(input("Digite 0 para interromper a execução: "))
```

  </details>

  <br>

  #### Exercício 5.8: Escreva um programa que leia dois números. Imprima o resultado da multiplicação do primeiro pelo segundo. Utilize apenas os operadores de soma e subtração para calcular o resultado. Lembre-se de que podemos entender a multiplicação de dois números como somas sucessivas de um deles. Assim, 4 × 5 = 5 + 5 + 5 + 5 = 4 + 4 + 4 + 4 + 4.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

  </details>

  <br>

  #### Exercício 5.9: Escreva um programa que leia dois números. Imprima a divisão inteira do primeiro pelo segundo, assim como o resto da divisão. Utilize apenas os operadores de soma e subtração para calcular o resultado. Lembre-se de que podemos entender o quociente da divisão de dois números como a quantidade de vezes que podemos retirar o divisor do dividendo. Logo, 20 ÷ 4 = 5, uma vez que podemos subtrair 4 cinco vezes de 20.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

            while valor2 + resto <= valor1:

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

  </details>

  <br>

  #### Exercício 5.10: Modifique o programa da listagem 5.10 para que aceite respostas com letras maiúsculas e minúsculas em todas as questões.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

while contador != 0:

    pontos = 0

    for questao in range (1, 4):

        resposta = input("Digite a reposta da questao %d : " % questao)

        if questao == 1 and resposta == "b" or resposta == "B":

            pontos = pontos + 1

        elif questao == 2 and resposta == "a" or resposta == "A":

            pontos = pontos + 1

        elif questao == 3 and resposta == "d" or resposta == "D":

            pontos = pontos + 1

        questao += 1

        print("O aluno fez %d pontos(s)" % pontos)

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>
  
  #### Exercício 5.11-12: Escreva um programa que pergunte o depósito inicial e a taxa de juros de uma poupança. Exiba os valores mês a mês para os 24 primeiros meses. Escreva o total ganho com juros no período.
  
  <details>
    <summary><h4>Resposta</h4></summary>

```python
contador1 = 1

while contador1 != 0:

    depositoInicial = float(input("Qual o valor do depósito inicial na conta? "))

    depositoMensal = float(input("Qual o valor depositado mensalmente? "))

    taxaJuros = float(input("Qual a taxa de juros anual da poupança no período? "))

    periodo = int(input("Digite a quantidade de meses do rendimento: "))

    print()

    ganhoTotal = depositoInicial

    ganhoJuros = 0

    for contador2 in range(1, periodo + 1):

        ganhoTotal += ganhoTotal / 100 * taxaJuros / 12

        ganhoJuros += ganhoTotal / 100 * taxaJuros / 12

        print("O valor na conta no %d° mês era de %.2f. Com uma taxa de %.2f por cento, gerou o valor de R$ %.2f em juros" % (contador2, ganhoTotal, taxaJuros, ganhoJuros))

        ganhoTotal += depositoMensal

    ganhoTotal = 0

    print()

    contador1 = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### Exercício 5.13: Escreva um programa que pergunte o valor inicial de uma dívida e o juro mensal. Pergunte também em quantos meses será pago. Imprima o valor mensal de pagamaneto, o total pago e o total de juros pago.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador1 = 1

pagamentoMensal = 0

while contador1 != 0:

    valorInicial = float(input("Qual o valor inicial da dívida? "))

    jurosMensal = float(input("Qual o juros mensal? "))

    tempoPagamento = int(input("Qual será o número de parcelas? "))

    dividaTotal = valorInicial

    for contadorDivida in range(1, tempoPagamento + 1):

        dividaTotal += dividaTotal / 100 * jurosMensal

    pagamentoMensal = dividaTotal / tempoPagamento

    print()

    print("O pagamento da dívida de R$ %.2f foi feita em %d meses com um valor de R$ %.2f" % (dividaTotal, tempoPagamento, pagamentoMensal))

    print()

    contador1 = int(input("Digite 0 para interromper a execução: "))

    pagamentoMensal = 0

    dividaTotal = 0

    print()
```

  </details>

  <br>
  
  #### Exercício 5.14: Escreva um programa que leia números inteiros do teclado. O programa deve ler os números até que o usuário digite 0 (zero). No final da execução, exiba a quantidade de números digitados, assim como a soma e a média aritmética.

  <details>
    <summary><h4>Resposta</h4></summary>
  
```python
contador = 1

while contador != 0:

    valor = 1

    contador1 = 0

    contador2 = 0

    mediaValor = 0

    while True:

        valor = int(input("Digite um número ou digite 0 para interromper: "))

        contador1 += valor

        contador2 += 1

        if valor == 0 and contador2 == 1:

            print("A iteração parou e não foi realizado nenhum cálculo")

            break

        else:

            if valor == 0:

                contador2 -= 1

                mediaValor = contador1 / contador2

                print()

                print("A iteração parou por ter digitado o número %d" % valor)

                print("A média das somas dos números digitados é: %.2f E o valor total da soma é: %d" % (mediaValor, contador1))

                break

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### Exercício 5.15: Escreva um programa para controlar uma pequena máquina registradora. Você deve solicitar ao usuário que digite o código do produto e a quantidade comprada. Utilize a tabela de códigos abaixo para obter o preço de cada produto:

  |**Código**|**Preço**|
  |----------|---------|
  |1         | R$ 0,50 |
  |2         | R$ 1,00 |
  |3         | R$ 4,00 |
  |5         | R$ 7,00 |
  |9         | R$ 8,00 |

  #### Seu programa deve exibir o total das compras depois que o usuário digitar 0. Qualquer outro código deve gerar a mensagem de erro “Código inválido”.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
contador1 = 1

while contador1 != 0:

    total = 0

    codigoProduto = 1

    while codigoProduto != 0:

        print()

        print("Se não deseja nenhum produto digite o valor 0")

        print()

        print("código 1, referente ao produto A; com valor de R$ 0,50")

        print()

        print("código 2, referente ao produto B; com valor de R$ 1,00")

        print()

        print("código 3, referente ao produto C; com valor de R$ 4,00")

        print()

        print("código 5, referente ao produto E, com valor de R$ 7,00")

        print()

        print("código 9, referente ao produto I; com valor de R$ 8,00")

        print()

        codigoProduto = float(input("Digite o código do produto desejado: "))

        if codigoProduto == 0:

            print()

            print("O valor total das compras foi de R$ %.2f" % total)

            break

        else:

            quantidadeProduto = int(input(f"Digite a quantidade desejada do produto {codigoProduto:.{0}f} "))

            if codigoProduto == 1:

                total += quantidadeProduto * 0.5

            elif codigoProduto == 2:

                total += quantidadeProduto * 1

            elif codigoProduto == 3:

                total += quantidadeProduto * 4

            elif codigoProduto == 5:

                total += quantidadeProduto * 7

            elif codigoProduto == 9:

                total += quantidadeProduto * 8

            elif codigoProduto != 0 or codigoProduto != 1 or codigoProduto != 2 or codigoProduto != 3 or codigoProduto != 5 or codigoProduto != 9:

                print("Valor incorreto digitado")

                continue

            print("O valor atual das compras é R$ %.2f:" % total)

    print()

    contador1 = int(input("Digite 0 para interromper a execução: "))
```

  </details>

  <br>

  #### Exercício 5.16-21: Escreva um programa que peça o valor de pagamento e imprima quantas cédulas são necessárias para pagar, sempre priorizando a cédulas e moedas de maior valor.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
contador1 = 1

while contador1 != 0:

    print()

    valor_pagamento = float(input("Digite o valor que deseja sacar: "))

    if valor_pagamento < 1:

        print("Valor insuficiente para saque")

        continue

    else:

        cedulas = 0

        limite_cedula = 200

        limite_moeda = 0.5

        moedas = 0

        while True:

            if limite_cedula <= valor_pagamento:

                valor_pagamento -= limite_cedula

                cedulas += 1

            else:

                print("%d cédula(s) de R$ %.2f" % (cedulas, limite_cedula))

                if valor_pagamento == 0:

                    break

                else:

                    if limite_cedula == 200:

                        limite_cedula = 100

                    elif limite_cedula == 100:

                        limite_cedula = 50

                    elif limite_cedula == 50:

                        limite_cedula = 20

                    elif limite_cedula == 20:

                        limite_cedula = 10

                    elif limite_cedula == 10:

                        limite_cedula = 5

                    elif limite_cedula == 5:

                        limite_cedula = 2

                    elif limite_cedula == 2:

                        limite_cedula = 1

                    cedulas = 0

                    if 0 < valor_pagamento < 1:

                        if limite_moeda <= valor_pagamento:

                            valor_pagamento -= limite_moeda

                            moedas += 1

                            if valor_pagamento == 0:

                                print("%d moeda(s) de R$ %.2f" % (moedas, limite_moeda))

                                break

    print()

    contador1 = int(input("Digite 0 para interromper a execuão: "))
```

  </details>

  <br>

  #### Exercício 5.22: Escreva um programa que exiba uma lista de opções (menu): adição, subtração, divisão, multiplicação e sair. Imprima a tabuada da operação escolhida. Repita até que a opção saída seja escolhida. 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador1 = 1

while contador1 != 0:

    print("Escolha dentre as opções abaixo: ")

    print()

    print("Digite 1 para somar: ")

    print("Digite 2 para subtrair: ")

    print("Digite 3 para dividir: ")

    print("Digite 4 para multiplicar: ")

    print()

    mathOperator = int(input("Digite o valor correspondente para a operação desejada: "))

    print()

    if mathOperator != 1 and mathOperator != 2 and mathOperator != 3 and mathOperator != 4:

        print("Opção inexistente")

        continue

    else:

        valor1 = float(input("Digite o primeiro valor: "))

        valor2 = float(input("Digite o segundo valor: "))

        print()

        if mathOperator == 1:

            print("O resultado da soma é: %.1f" % (valor1 + valor2))

        elif mathOperator == 2:

            print("O resultado da subtração é: %.1f" % (valor1 - valor2))

        elif mathOperator == 3:

            print("O resultado da divisão é: %.1f" % (valor1 / valor2))

        elif mathOperator == 4:

            print("O resultado da multiplicação é: %.1f" % (valor1 * valor2))

    print()

    contador1 = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### Exercício 5.23-24: Escreva um programa que leia um número e verifique se é ou não um número primo. Para fazer essa verificação, calcule o resto da divisão do número por 2 e depois por todos os números ímpares até o número lido. Se o resto de uma dessas divisões for igual a zero, o número não é primo. Observe que 0 e 1 não são primos e que 2 é o único número primo que é par. Depois Modifique esse mesmo programa de forma a ler um número *n*. Imprima os *n* primeiros números primos.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

while contador != 0:

    confirmacao = 2

    numero = int(input("Digite um número inteiro para saber se ele é primo ou não: "))

    if numero == 0 or numero == 1:

        print("Esse número é inválido")

        continue

    if numero == 2 or numero == 3:

        print("%d é um número primo" % numero)

    else:

        for contador2 in range(confirmacao, numero + 1):

            if numero % contador2 != 0:

                confirmacao += 1

        if confirmacao == numero:

            print("%d é um número primo" % numero)

        else:

           print("%d não é um número primo" % numero)

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### Exercício 5.25: Escreva um programa que calcule a raiz quadrada de um número. Utilize o método de Newton para obter o resultado aproximado. Sendo *n* o número a obter a raiz quadrada, considere a base b = 2. Calcule *p* usando a fórmula p = (b + (n / b) ) / 2. Agora, calcule o quadrado de *p*. A cada passo, faça  b = p e recalcule *p* usando a fórmula apresentada. Pare quando a diferença absoluta entre *n* e o quadrado de *p* for menor que 0,0001.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador1 = 1

while contador1 != 0:

    numero = float(input("Digite um número para saber a sua raiz aproximada, utilizando o método Newtoniano: "))

    base = 2

    raizQuadrada = (base + numero / base) / 2

    raizQuadrada = raizQuadrada**2

    while raizQuadrada * raizQuadrada - numero > 0.001:

        base = raizQuadrada

        raizQuadrada = (base + numero / base) / 2

    print("A raiz aproximada de %d é: %.4f" % (numero, raizQuadrada))

    print()

    contador1 = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### Exercício 5.26: Escreva um programa que calcule o resto da divisão inteira entre dois números. Utilize apenas as operações de soma e subtração para calcular o resultado.

  <details>
    <summary><h4>Resposta</h4></summary>
    
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

            while valor2 + resto <= valor1:

                restoInteiro += 1

                resto += valor2

        else:

            while valor1 + resto < valor2:

                resto += valor1

            while resto != valor2:

                resto += 1

        print("O resto inteiro da divisão entre %.1f e %.1f é: %.1f" % (valor1, valor2, restoInteiro))

        print()

        contador1 = int(input("Digite 0 para interromper a execução: "))

        print()
```
  
  </details>

  <br>
  
  #### Exercício 5.27: Escreva um programa que verifique se um número é palíndromo. Um número é palíndromo se continua o mesmo caso seus dígitos sejam invertidos. Exemplos: 454, 10501

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador1 = 1

while contador1 != 0:

    contador3 = 0

    valor1 = (input("Digite um número ou uma letra para saber se é palíndromo: "))

    if len(valor1) < 2:

        print("Tamanho insuficiente!")

        continue

    else:

        for contador2 in range(0, len(valor1)):

            if valor1 [0 + contador2] == valor1 [-1 - contador2]:

                contador3 += 1

        if contador3 == len(valor1):

            print("%s é palíndromo" % valor1)

        else:

            print("%s não é palíndromo" % valor1)

        print()

    contador1 = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  </details>

  <details>
    <summary>
      <h3>Capítulo 6: Listas</h3>
    </summary>


  </details>

  <details>
    <summary>
      <h3>Capítulo 7: Trabalhando com Strings</h3>
    </summary>

  </details>
