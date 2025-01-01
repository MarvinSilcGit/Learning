<h2>Python Brasil Wiki: Lista de Exercícios</h2>

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

media = (nota1 + nota2 + nota3 + nota4) / 4

print(media)
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

print("O peso ideal desse homem é %.2f.\nO peso ideal dessa mulher é %.2f" % (pesoIdealHomem, pesoIdealMulher))
```

  </details>

  <br>

  #### 14. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
pesoPeixe = float(input("Digite o peso do peixe: "))

if pesoPeixe > 50:

    pesoLimite = 50

    pesoAdicional = pesoPeixe - pesoLimite

    multa = pesoAdicional * 4

    print("A multa será R$ %.2f por exceder o peso limite em %.2f quilos " %(multa, pesoAdicional))

else:

    print("Não haverá pagamento de multa")
```

  </details>

  <br>

  #### 15. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês, sabendo-se que são descontados 11% para o Imposto de Renda, 8% para o INSS e 5% para o sindicato, faça um programa que nos dê: salário bruto, quanto pagou ao INSS, quanto pagou ao sindicato e o salário líquido. Calcule os descontos e o salário líquido conforme a ordem a seguir: + Salário Bruto : R$ - IR (11%) : R$ - INSS (8%) : R$ - Sindicato ( 5%) : R$ = Salário Liquido : R$ Obs.: Salário Bruto - Descontos = Salário Líquido. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
salario = float(input("Digite o seu salário: "))

salarioLiquido = salario

salarioLiquido -= salario / 100 * 11

salarioLiquido -= salarioLiquido / 100 * 8

salarioLiquido -= salarioLiquido / 100 * 5

print("O salário líquido será R$ %.2f, com R$ %.2f de desconto" % (salarioLiquido, salario-salarioLiquido))
```

  </details>

  <br>

  #### 16. Faça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
metragem = float(input("Digite a metragem: "))

coberturaTinta = 3

metragemLata = 18 * coberturaTinta

quantidadeLatas = 0

precoFinal = 0

precoLata = 80

if metragem / metragemLata <= 1:

    quantidadeLatas = 1

    precoFinal = quantidadeLatas * precoLata

    print("Será necessária, no máximo, uma lata de tinta para pintar %.2f metros². O custo será R$ %.2f" % (metragem, precoFinal))

else:

    if metragem % metragemLata == 0:

        quantidadeLatas = metragem / metragemLata

        precoFinal = quantidadeLatas * precoLata

        print("Serão necessária exatas %d latas de tinta para pintar %.2f metros². O custo será R$ %.2f" % (quantidadeLatas, metragem, precoFinal))

    else:

        quantidadeLatas = (metragem // metragemLata) + 1

        precoFinal = quantidadeLatas * precoLata

        print("Será necessária aos menos %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeLatas, metragem, precoFinal))
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
metragemArea = float(input("Digite a metragem: "))

coberturaTinta = 6

metragemLata = 18 * coberturaTinta

precoLata = 80

quantidadeLatas = 0

metragemGalao = 3.6 * coberturaTinta

precoGalao = 25

quantidadeGaloes = 0

precoFinal = 0

if metragemArea <= metragemGalao * 4:

    if metragemArea % metragemGalao == 0:

        quantidadeGaloes = metragemArea / metragemGalao

        precoFinal = quantidadeGaloes * precoGalao

        print("Serão necessários exatos %d galões de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeGaloes, metragemArea, precoFinal))

    else:

        quantidadeGaloes = metragemArea // metragemGalao + 1

        precoFinal = quantidadeGaloes * precoGalao

        print("Serão necessários aos menos %d galões de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeGaloes, metragemArea, precoFinal))

else:

    if metragemArea % metragemLata == 0:

        quantidadeLatas = metragemArea / metragemLata

        precoFinal = quantidadeLatas * precoLata

        print("Serão necessária exatas %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeLatas, metragemArea, precoFinal))

    else:

        if metragemArea - metragemLata < 0:

            quantidadeLatas = metragemArea // metragemLata + 1

            precoFinal = quantidadeLatas * precoLata

            print("Serão necessária ao menos %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeLatas, metragemArea, precoFinal))

        else:

            quantidadeLatas = metragemArea // metragemLata

            precoFinal = quantidadeLatas * precoLata

            metragemRestante = metragemArea - (metragemLata * quantidadeLatas)

            if metragemRestante % metragemGalao == 0:

                quantidadeGaloes = metragemRestante / metragemGalao

                precoFinal += quantidadeGaloes * precoGalao

                print("Serão necessárias ao menos %d latas de tinta e ao menos %d Galões para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeLatas, quantidadeGaloes, metragemArea, precoFinal))

            else:

                if metragemRestante // metragemGalao >= 4:

                    quantidadeLatas +=1

                    precoFinal = quantidadeLatas * precoLata

                    quantidadeGaloes = 0

                else:

                    quantidadeGaloes = metragemRestante // metragemGalao + 1

                    precoFinal += quantidadeGaloes * precoGalao

                print("Serão necessárias ao menos %d latas de tinta e ao menos %d Galões para pintar %.1f metros². O custo será R$ %.2f" % (quantidadeLatas, quantidadeGaloes, metragemArea, precoFinal))
```

  </details>

  <br>

  #### 18. Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
tamanhoArquivo = float(input("Digite o tamanho do arquivo em Megabytes: "))

if tamanhoArquivo < 1:

    print("Valor inválido!")

velecidadeLink = float(input("Digite a velocidade de sua conexão em megabits: "))

tempoDownload = (tamanhoArquivo / (velecidadeLink / 8))

if tempoDownload >= 60:

    tempoDownload = tempoDownload / 60

    print("O tempo de Download será de no mínimo %.1f minutos" % tempoDownload)

else:

    print("O tempo de Download será de no mínimo %.1f segundos" % tempoDownload)
```

  </details>

  <br>

  </details>

  
  <details>
    <summary>
      <h3>Estrutura de Decisão</h3>
    </summary>
  
  #### 1. Faça um Programa que peça dois números e imprima o maior deles. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
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

  </details>

  <br>

  #### 2. Faça um Programa que peça um valor e mostre na tela se o valor é positivo ou negativo.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
valor = float(input("Digite um número: "))

if valor < 0:

    print("O valor %.1f é negativo" % valor)

else:

    print("O valor %.1f é positivo" % valor)
```

  </details>

  <br>
  
  #### 3. Faça um Programa que verifique se uma letra digitada é "F" ou "M". Conforme a letra escrever: F - Feminino, M - Masculino ou Sexo Inválido.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
sexo = input("Digite o sexo: ")

if sexo == "F" or sexo == "f":

    print("O sexo é Feminino")

elif sexo == "M" or sexo == "m":

    print("O sexo é Masculino")

else:

    print("O sexo é inválido")
```

  </details>

  <br>
  
  #### 4. Faça um Programa que verifique se uma letra digitada é vogal ou consoante.

   <details>
    <summary><h4>Resposta</h4></summary>
     
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

  </details>

  <br>
  
  #### 5. Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar: A mensagem "Aprovado", se a média alcançada for maior ou igual a 7; A mensagem "Reprovado", se a média for menor do que 7; A mensagem "Aprovado com Distinção", se a média for igual a 10. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
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

  </details>

  <br>
  
  #### 6. Faça um Programa que leia três números e mostre o maior deles. 

   <details>
    <summary><h4>Resposta</h4></summary>
     
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

  <br>

  #### 7. Faça um Programa que leia três números e mostre o maior e o menor deles.

  <details>
    <summary><h4>Resposta</h4></summary>

```python

```

  </details>

  <br>
  
  #### 8. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 9. Faça um Programa que leia três números e mostre-os em ordem decrescente.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 10. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 11. As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e lhe contraram para desenvolver o programa que calculará os reajustes. Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério, baseado no salário atual: salários até R$ 280,00 (incluindo): aumento de 20%, salários entre R$ 280,00 e R$ 700,00: aumento de 15%; salários entre R$ 700,00 e R$ 1500,00: aumento de 10%; salários de R$ 1500,00 em diante: aumento de 5% Após o aumento ser realizado, informe na tela: o salário antes do reajuste, o percentual de aumento aplicado, o valor do aumento, o novo salário, após o aumento. 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 12. Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita). O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês. Desconto do IR: Salário Bruto até 900 (inclusive) - isento; Salário Bruto até 1500 (inclusive) - desconto de 5%; Salário Bruto até 2500 (inclusive) - desconto de 10%; Salário Bruto acima de 2500 - desconto de 20%. Imprima na tela as informações, dispostas conforme o exemplo abaixo. No exemplo o valor da hora é 5 e a quantidade de hora é 220.

  |Salário Bruto: (5 * 220) | R$ 1110,00|
  |-------------------|-----------------|
  |(-) IR (5%)        |R$ 55,00         |
  |(-) INSS (10%)     |R$ 110,00        |
  |FGTS (11%)         |R$ 121,00        |
  |Total de descontos |R$ 165,00        |
  |Salário Líquido    |R$ 935,00        |

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 13. Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 14. Faça um programa que lê as duas notas parciais obtidas por um aluno numa disciplina ao longo de um semestre, e calcule a sua média. O algoritmo deve mostrar na tela as notas, a média, o conceito correspondente e a mensagem “APROVADO” se o conceito for A, B ou C ou “REPROVADO” se o conceito for D ou E. A atribuição de conceitos obedece à tabela abaixo: 

  |Média de Aproveitamento|Conceito|
  |----------------|---------------|
  |Entre 9.0 e 10.0|A              |
  |Entre 7.5 e 9.0 |B              |
  |Entre 6.0 e 7.5 |C              |
  |Entre 4.0 e 6.0 |D              |
  |Entre 4.0 e 0.0 |E              |

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 15.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 16.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 17.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 18.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 19.

  <details>
    <summary><h4>Resposta</h4></summary>

```python

```

  </details>

  <br>
  
  #### 20.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 21.
  
  <details>
    <summary><h4>Resposta</h4></summary>

```python

```

  </details>

  <br>

  #### 22.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 23.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 24.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 25.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 26.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 27.
  
  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  #### 28

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  </details>
