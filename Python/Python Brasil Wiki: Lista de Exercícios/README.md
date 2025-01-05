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

if numero1 > numero2 > numero3:

    print("O primeiro número é o maior")

elif numero1 > numero3 > numero2:

    print("O primeiro número é o maior")

elif numero2 > numero1 > numero3:

    print("O segundo número é o maior")

elif numero2 > numero3 > numero1:

    print("O segundo número é o maior")

elif numero3 > numero1 > numero2:

    print("O terceiro número é o maior")

elif numero3 > numero2 > numero1:

    print("O terceiro número é o maior")
```

  </details>

  <br>

  #### 7. Faça um Programa que leia três números e mostre o maior e o menor deles.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
numero1 = float(input("Digite o primeiro número: "))

numero2 = float(input("Digite o segundo número: "))

numero3 = float(input("Digite o terceiro número: "))

if numero1 > numero2 > numero3:

    print("O primeiro número é o maior")
    print("O terceiro número é o menor")

elif numero1 > numero3 > numero2:

    print("O primeiro número é o maior")
    print("O segundo número é o maior")

elif numero2 > numero1 > numero3:

    print("O segundo número é o maior")
    print("O terceiro número é o menor")

elif numero2 > numero3 > numero1:

    print("O segundo número é o maior")
    print("O primeiro número é o menor")

elif numero3 > numero1 > numero2:

    print("O terceiro número é o maior")
    print("O segundo número é o menor")

elif numero3 > numero2 > numero1:

    print("O terceiro número é o maior")
    print("O primeiro número é o menor")
```

  </details>

  <br>
  
  #### 8. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
produto1 = float(input("Digite o valor do primeiro produto: "))

produto2 = float(input("Digite o valor do primeiro produto: "))

produto3 = float(input("Digite o valor do primeiro produto: "))

if produto1 > produto2 > produto3:

    print("Você deve comprar o terceiro produto por ser o mais barato")

elif produto1 > produto3 > produto2:

    print("Você deve comprar o segundo produto por ser o mais barato")

elif produto2 > produto1 > produto3:

    print("Você deve comprar o terceiro produto por ser o mais barato")

elif produto2 > produto3 > produto1:

    print("Você deve comprar o primeiro produto por ser o mais barato")

elif produto3 > produto1 > produto2:

    print("Você deve comprar o segundo produto por ser o mais barato")

elif produto3 > produto2 > produto1:

    print("Você deve comprar o primeiro produto por ser o mais barato")
```

  </details>

  <br>
  
  #### 9. Faça um Programa que leia três números e mostre-os em ordem decrescente.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero1 = float(input("Digite o primeiro número: "))

numero2 = float(input("Digite o segundo número: "))

numero3 = float(input("Digite o terceiro número: "))

if numero1 > numero2 > numero3:

    print("%d\n%d\n%d" % (numero1, numero2, numero3))

elif numero1 > numero3 > numero2:

    print("%d\n%d\n%d" % (numero1, numero3, numero2))

elif numero2 > numero1 > numero3:

    print("%d\n%d\n%d" % (numero2, numero1, numero3))

elif numero2 > numero3 > numero1:

    print("%d\n%d\n%d" % (numero2, numero3, numero1))

elif numero3 > numero1 > numero2:

    print("%d\n%d\n%d" % (numero3, numero1, numero2))

elif numero3 > numero2 > numero1:

    print("%d\n%d\n%d" % (numero3, numero2, numero1))
```

  </details>

  <br>

  #### 10. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
turno = input("Digite o turno:\nN - Noturo\nM - Matutino\nV - Vespertino\n")

if turno == "N" or turno == "n":

    print("Boa noite")

elif turno == "M" or turno == "m":

    print("Bom dia")

elif turno == "V" or turno == "v":

    print("Boa tarde")

else:

    print("Valor inválido")
```

  </details>

  <br>

  #### 11. As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e lhe contraram para desenvolver o programa que calculará os reajustes. Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério, baseado no salário atual: salários até R$ 280,00 (incluindo): aumento de 20%, salários entre R$ 280,00 e R$ 700,00: aumento de 15%; salários entre R$ 700,00 e R$ 1500,00: aumento de 10%; salários de R$ 1500,00 em diante: aumento de 5% Após o aumento ser realizado, informe na tela: o salário antes do reajuste, o percentual de aumento aplicado, o valor do aumento, o novo salário, após o aumento. 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
salarioInicial = float(input("Digite o salário atual: "))

aumento = 0

salarioFinal = salarioInicial

if salarioInicial <= 280:

    aumento = salarioInicial / 100 * 20

    salarioFinal += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 20 por cento" % (salarioInicial, salarioFinal, aumento,))

elif salarioInicial <= 700:

    aumento = salarioInicial / 100 * 15

    salarioFinal += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 15 por cento" % (salarioInicial, salarioFinal, aumento,))

elif salarioInicial <= 1500:

    aumento = salarioInicial / 100 * 10

    salarioFinal += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 10 por cento" % (salarioInicial, salarioFinal, aumento,))

elif salarioInicial > 1500:

    aumento = salarioInicial / 100 * 5

    salarioFinal += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 5 por cento" % (salarioInicial, salarioFinal, aumento,))
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
cargaHoraria = int(input("Digite a sua carga horária mensal: "))

salarioHora = float(input("Digite o seu salário hora: "))

salarioBruto = cargaHoraria * salarioHora

descontos = 0

impostoRenda = 0

inss = 0

if salarioBruto <=  900:

    print("O salário será R$ %.2f com R$ %.2f de Imposto de renda, R$ %.2f de INSS. Totalizando R$ %.2f em descontos" % (salarioBruto, impostoRenda, inss, descontos))

elif salarioBruto <= 1500:

    impostoRenda = salarioBruto / 100 * 5

    inss = salarioBruto / 100 * 10

    descontos = impostoRenda + inss

elif salarioBruto <= 2500:

    impostoRenda = salarioBruto / 100 * 10

    inss = salarioBruto / 100 * 10

    descontos = impostoRenda + inss

elif salarioBruto > 2500:

    impostoRenda = salarioBruto / 100 * 20

    inss = salarioBruto / 100 * 10

    descontos = impostoRenda + inss

print("O salário inicial era de R$ %.2f e será R$ %.2f, com R$ %.2f de Imposto de renda e R$ %.2f de INSS. Totalizando R$ %.2f em descontos" % (salarioBruto, salarioBruto-descontos, impostoRenda, inss, descontos))
```

  </details>

  <br>

  #### 13. Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
diaSemana = input("Digite o dia da semana:\n1 - Domingo\n2 - Segunda-feira\n3 - Terça-feira\n4 - Quarta-feira\n5 - Quinta-feira\n6 - Sexta-feira\n7 - Sábado\n")

if diaSemana == "1":

    print("Domingo")

elif diaSemana == "2":

    print("Segunda-feira")

elif diaSemana == "3":

    print("Terça-feira")

elif diaSemana == "4":

    print("Quarta-feira")

elif diaSemana == "5":

    print("Quinta-feira")

elif diaSemana == "6":

    print("Sexta-feira")

elif diaSemana == "7":

    print("Sábado")

else:

    print("Valor inválido")
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
notaParcial1 = float(input("Digite a primeira nota parcial: "))

if notaParcial1 > 10 or notaParcial1 < 0:

    print("Nota inválida")

notaParcial2 = float(input("Digite a segunda nota parcial: "))

if notaParcial2 > 10 or notaParcial2 < 0:

    print("Nota inválida")

mediaFinal = (notaParcial1 + notaParcial2) / 2

if mediaFinal >= 6:

    print("Aprovado e a média foi %.2f" % mediaFinal)

    if mediaFinal >= 9 and mediaFinal <= 10:

        print("Conceito A")

    elif mediaFinal >= 7.5 and mediaFinal < 9:

        print("Conceito B")

    elif mediaFinal >= 6 and mediaFinal < 7.5:

        print("Conceito C")

else:

    print("Reprovado e a média foi %.2f" % mediaFinal)

    if mediaFinal >= 4 and mediaFinal < 6:

        print("Conceito D")

    else:

        print("Conceito E")
```

  </details>

  <br>
  
  #### 15. Faça um Programa que peça os 3 lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno. Dicas: Três lados formam um triângulo quando a soma de quaisquer dois lados for maior que o terceiro; Triângulo Equilátero: três lados iguais; Triângulo Isósceles: quaisquer dois lados iguais; Triângulo Escaleno: três lados diferentes.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
lado1 = int(input("Digite o primeiro lado do triângulo: "))

lado2 = int(input("Digite o segundo lado do triângulo: "))

lado3 = int(input("Digite o terceiro lado do triângulo: "))

if lado1 == 0 or lado2 == 0 or lado3 == 0:

    print("Um triângulo não poder lado 0")

else:

    if lado1 + lado2 <= lado3:

       print("A soma desses lados não forma um triângulo")

    else:

        if lado1 == lado2 == lado3:

            print("Esse é um triângulo equilátero")

        elif lado1 != lado2 != lado3 != lado1:

            print("Esse é um triângulo escaleno")

        elif lado1 == lado2 or lado2 == lado3 or lado1 == lado3:

            print("Esse é um triângulo isóceles")
```

  </details>

  <br>

  #### 16. Faça um programa que calcule as raízes de uma equação do segundo grau, na forma ax2 + bx + c. O programa deverá pedir os valores de a, b e c e fazer as consistências, informando ao usuário nas seguintes situações:

  1. Se o usuário informar o valor de A igual a zero, a equação não é do segundo grau e o programa não deve fazer pedir os demais valores, sendo encerrado.
  2. Se o delta calculado for negativo, a equação não possui raizes reais. Informe ao usuário e encerre o programa;
  3. Se o delta calculado for igual a zero a equação possui apenas uma raiz real; informe-a ao usuário;
  4. Se o delta for positivo, a equação possui duas raiz reais; informe-as ao usuário; 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 17. Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
anoBissexto = int(input("Digite o ano para saber se é bissexto ou não: "))

if anoBissexto % 4 == 0:

    if anoBissexto % 100 != 0:

        print("O ano %d é bissexto" % anoBissexto)

    elif anoBissexto % 100 == 0:

        print("O ano %d é bissexto especial" % anoBissexto)

else:

    print("O ano %d não é bissexto" % anoBissexto)
```

  </details>

  <br>

  #### 18. Faça um Programa que peça uma data no formato dd/mm/aaaa e determine se a mesma é uma data válida.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
formatoData = input("Digite a data no formato dd/mm/aaaa: ")

if len(formatoData) != 10 or formatoData[2] == "/" or formatoData[5] == "/":

    print("Formato de data inválida")

else:

    print("Formato de data válida")
```

  </details>

  <br>

  #### 19. Faça um Programa que leia um número inteiro menor que 1000 e imprima a quantidade de centenas, dezenas e unidades do mesmo. Observando os termos no plural a colocação do "e", da vírgula entre outros. Exemplo: 326 = 3 centenas, 2 dezenas e 6 unidades 12 = 1 dezena e 2 unidades Testar com: 326, 300, 100, 320, 310,305, 301, 101, 311, 111, 25, 20, 10, 21, 11, 1, 7 e 16 

  <details>
    <summary><h4>Resposta</h4></summary>

```python
valor = int(input("Digite um número: "))

quantidadeCentena = 0

quantidadeDezena = 0

quantidadeUnidade = 0

if valor // 100 > 0:

    quantidadeCentena = valor // 100

    valor -= quantidadeCentena * 100

    if valor // 10 > 0:

        quantidadeDezena = valor // 10

        valor -= quantidadeDezena * 10

        if valor // 1 > 0:

            quantidadeUnidade = valor // 1

            valor -= quantidadeUnidade * 1

print("%d = %d centenas, %d dezenas e %d unidades" % (0 + (quantidadeUnidade * 1) + 0 + (quantidadeDezena * 10) + 0 + (quantidadeCentena * 100), quantidadeCentena, quantidadeDezena, quantidadeUnidade))
```

  </details>

  <br>
  
  #### 20. Faça um Programa para leitura de três notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e presentar:
  
  1. A mensagem "Aprovado", se a média for maior ou igual a 7, com a respectiva média alcançada.
  2. A mensagem "Reprovado", se a média for menor do que 7, com a respectiva média alcançada.
  3. A mensagem "Aprovado com Distinção", se a média for igual a 10.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
nota1 = float(input("Digite a primeira nota:"))

nota2 = float(input("Digite a segunda nota:"))

nota3 = float(input("Digite a terceira nota: "))

media = (nota1 + nota2 + nota3) / 3

if media == 10:

    print("Aprovado com distinção")

elif media >= 7 and media < 10:

    print("Aprovado")

else:

    print("Reprovado")
```

  </details>

  <br>
  
  #### 21. Faça um Programa para um caixa eletrônico. O programa deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais. O programa não deve se preocupar com a quantidade de notas existentes na máquina.

  1. Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1.
  2. Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.
  
  <details>
    <summary><h4>Resposta</h4></summary>

```python
import math

valor = float(input("Digite o valor que deseja sacar: "))

valorPagamento = math.trunc(valor)

if valorPagamento < 10:

    print("Valor insuficiente para saque")

else:

    cedulas = 0

    limite_cedula = 100

    while True:

        if limite_cedula <= valorPagamento:

            valorPagamento -= limite_cedula

            cedulas += 1

        else:

            print("%d cédula(s) de R$ %.2f" % (cedulas, limite_cedula))

            if valorPagamento == 0:

                break

            else:

                if limite_cedula == 100:

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
```

  </details>

  <br>

  #### 22. Faça um Programa que peça um número inteiro e determine se ele é par ou impar. Dica: utilize o operador módulo (resto da divisão). 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero = int(input("Digite o número para saber se é par ou ímpar: "))

if numero % 2 !=0:

    print("O número %d é ímpar" % numero)

else:

    print("O número %d é par" % numero)
```

  </details>

  <br>
  
  #### 23. Faça um Programa que peça um número e informe se o número é inteiro ou decimal. Dica: utilize uma função de arredondamento.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
import math

numeroDecimal = float(input("Digite o número para saber se é decimal ou não: "))

numeroInteiro = math.trunc(numeroDecimal)

if numeroDecimal > numeroInteiro:

    print("O número %.1f é decimal" % numeroDecimal)

else:

    print("O número %d não é decimal" % numeroInteiro)
```

  </details>

  <br>

  #### 24. Faça um Programa que leia 2 números e em seguida pergunte ao usuário qual operação ele deseja realizar. O resultado da operação deve ser acompanhado de uma frase que diga se o número é:

  1. par ou ímpar;
  2. positivo ou negativo;
  3. inteiro ou decimal. 

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
operacao = input("Digite qual operação deseja realizar:\n1 - Inteiro ou decimal\n2 - Par ou Ímpar\n3 - Positivo ou Negativo\n")

if operacao == "1":

    import math

    numeroDecimal = float(input("Digite o número para saber se é decimal ou não: "))

    numeroInteiro = math.trunc(numeroDecimal)

    if numeroDecimal > numeroInteiro:

        print("O número %.1f é decimal" % numeroDecimal)

    else:

        print("O número %d não é decimal" % numeroInteiro)

elif operacao == "2":

    numero = int(input("Digite o número para saber se é par ou ímpar: "))

    if numero % 2 != 0:

        print("O número %d é ímpar" % numero)

    else:

        print("O número %d é par" % numero)

elif operacao == "3":

    numero = float(input("Digite o número para saber se é negativo ou positivo: "))

    if numero < 0:

        print("O número %.1f é negativo" % numero)

    else:

        print("O número %.1f é positivo" % numero)
```

  </details>

  <br>
  
  #### 25. Faça um programa que faça 5 perguntas para uma pessoa sobre um crime.  Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente". As perguntas são:
 
  1. "Telefonou para a vítima?"
  2. "Esteve no local do crime?"
  3. "Mora perto da vítima?"
  4. "Devia para a vítima?"
  5. "Já trabalhou com a vítima?" O programa deve no final emitir uma classificação sobre a participação da pessoa no crime.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>

  #### 26. Um posto está vendendo combustíveis, portanto, Escreva um algoritmo que leia o número de litros vendidos, o tipo de combustível (codificado da seguinte forma: A-álcool, G-gasolina), calcule e imprima o valor a ser pago pelo cliente, calcule e imprima o valor a ser pago pelo cliente, sabendo-se que o preço do litro da gasolina é R$ 2,50 o preço do litro do álcool é R$ 1,90. A seguir a tabela de valores:
  
  |         |Até 20 Litros| Acima 20 Litros|
  |---------|-----------|------------------|
  |Álcool   |3% desconto| 5% desconto|
  |Gasolina |4% desconto| 6% desconto|

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
quantidadeLitros = float(input("Digite a quantidade de litros: "))

tipoGasolina = input("Para Álcool digite A\nPara Gasolina digite G\n")

precoFinal = 0

if tipoGasolina == "A" or tipoGasolina == "a":

    if quantidadeLitros <= 20:

        precoFinal = quantidadeLitros * 1.9

        precoFinal -= precoFinal / 100 * 3

    else:

        precoFinal = quantidadeLitros * 1.9

        precoFinal -= precoFinal / 100 * 4

elif tipoGasolina == "G" or tipoGasolina == "g":

    if quantidadeLitros <= 20:

        precoFinal = quantidadeLitros * 2.5

        precoFinal -= precoFinal / 100 * 4

    else:

        precoFinal = quantidadeLitros * 2.5

        precoFinal -= precoFinal / 100 * 5

print("O preço final será R$ %.2f" % precoFinal)
```

  </details>

  <br>
  
  #### 27. Uma comerciante está vendendo frutas com a possibilidade de: se, o cliente comprar mais de 8 Kg em frutas ou o valor total da compra ultrapassar R$ 25,00, receberá ainda um desconto de 10% sobre este total. Escreva um algoritmo para ler a quantidade (em Kg) de morangos e a quantidade (em Kg) de maças adquiridas e escreva o valor a ser pago pelo cliente. A seguir a tabela de preços:
  
  |          |Até 5 Kg|Acima de 5 Kg|
  |----------|----------|-----------|
  |Morango   |R$ 2,50 Kg| R$ 2,20 Kg|
  |Maçã      |R$ 1,80 Kg| R$ 1,50 Kg|
  
  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
quantidadeMorango = float(input("Digite a quantidade em kilos de morangos: "))

quantidadeMaca = float(input("Digite a quantidade em kilos de maçãs: "))

precoFinal = 0

if quantidadeMorango <= 5:

    precoFinal += quantidadeMorango * 2.5

else:

    precoFinal += quantidadeMorango * 2.2

if quantidadeMaca <= 5:

    precoFinal += quantidadeMaca * 1.8

else:

    precoFinal += quantidadeMaca * 1.2

print("O preço final será R$ %.2f" % precoFinal)
```

  </details>

  <br>
  
  #### 28. O Hipermercado Tabajara está com uma promoção de carnes que é imperdível. Confira:

  |          |Até 5 Kg|Acima de 5 Kg|
  |----------|----------|-----------|
  |Filé Duplo|R$ 4,90 Kg| R$ 5,80 Kg|
  |Alcatra   |R$ 5,90 Kg| R$ 6,80 Kg|
  |Picanha   |R$ 6,90 Kg| R$ 7,80 Kg|

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
quantidadeFile = int(input("Digite a quantidade em kilos de Filé Duplo: "))

quantidadePicanha = int(input("Digite a quantidade em kilos de Picanha: "))

quantidadeAlcatra = int(input("Digite a quantidade em kilos de Alcatra: "))

precoFinal = 0

if quantidadeFile <= 5:

    precoFinal += quantidadeFile * 4.9

else:

    precoFinal += quantidadeFile * 5.8

if quantidadePicanha <= 5:

    precoFinal += quantidadePicanha * 5.9

else:

    precoFinal += quantidadePicanha * 6.8

if quantidadeAlcatra <= 5:

    precoFinal += quantidadeAlcatra * 6.9

else:

    precoFinal += quantidadePicanha * 7.8

print("O preço final será R$ %.2f" % precoFinal)
```

  </details>

  <br>

  </details>

  
  <details>
    <summary>
      <h3>Estrutura de Repetição</h3>
    </summary>

  #### 1. Faça um programa que peça uma nota, entre zero e dez. Mostre uma mensagem caso o valor seja inválido e continue pedindo até que o usuário informe um valor válido.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
contador = 1

while contador != 0:

    nota = int(input("Digite uma nota entre 1 e 10: "))

    if nota >= 1 or nota <= 10:

        print(nota)

    else:

        print("Nota inválida")

        continue

    contador = int(input("Digite 0 para finalizar o programa: "))
```

  </details>

  <br>

  #### 2. Faça um programa que leia um nome de usuário e a sua senha e não aceite a senha igual ao nome do usuário, mostrando uma mensagem de erro e voltando a pedir as informações.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
contador = 1

while contador != 0:

    nome = input("Digite o nome de usuário: ")

    senha = input("Digite a senha: ")

    if nome == senha:

        print("Usuário e senha não podem ser idênticos")

        continue

    contador = int(input("Digite 0 para finalizar o programa: "))
```

  </details>

  <br>

  #### 3. Faça um programa que leia e valide as seguintes informações:
  
  1. Nome: maior que 3 caracteres;
  2. Idade: entre 0 e 150;
  3. Salário: maior que zero;
  4. Sexo: 'f' ou 'm';
  5. Estado Civil: 's', 'c', 'v', 'd';


   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
contador = 1

while contador != 0:

    nome = input("Digite seu nome: ")

    if len(nome) < 3:

        print("Nome muito pequeno")

        continue

    else:

        idade = int(input("Digite sua idade: "))

        if idade < 0 or idade > 150:

            print("Idade inválida")

            continue

        else:

            salario = float(input("Digite o seu salário: "))

            if salario <= 0:

                print("Salário inválido")

                continue

            else:

                sexo = input("Digite o seu sexo:\nf - mulheres\nm - homens\n")

                print(sexo)

                if sexo != "m" and sexo != "f":

                    print("Sexo inválido")

                    continue

                else:

                    estadoCivil = input("Digite seu estado civil:\ns - solteiro(a)\nv - viúvo(a)\nc - casado(a)\nd - divorciado\n")

                    if estadoCivil != "s" and estadoCivil != "v" and estadoCivil !="c" and estadoCivil != "d":

                        print("Estado civil inválido")

                        continue

                    else:

                        print("%s, %d, %.2f, %s, %s" % (nome, idade, salario, sexo, estadoCivil))

    contador = int(input("Digite 0 para finalizar o programa: "))
```

  </details>

  <br>

  #### 4-5. Supondo que a população de um país A seja da ordem de 80.000 habitantes com uma taxa anual de crescimento de 3% e que a população de B seja 200.000 habitantes com uma taxa de crescimento de 1.5%. Faça um programa que calcule e escreva o número de anos necessários para que a população do país A ultrapasse ou iguale a população do país B, mantidas as taxas de crescimento. Depois, altere o programa anterior permitindo ao usuário informar as populações e as taxas de crescimento iniciais. Valide a entrada e permita repetir a operação.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
araja = 80000

bacalaca = 200000

anos = 0

while araja < bacalaca:

    araja += araja / 100 * 3

    bacalaca += bacalaca / 100 * 1.5

    anos +=1

    print(araja)

    print(bacalaca)

print("Serão necessários pelos menos %d anos" % anos)
```

  </details>

  <br>
 
  #### 6. Faça um programa que imprima na tela os números de 1 a 20, um abaixo do outro. Depois modifique o programa para que ele mostre os números um ao lado do outro.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
for _ in range(1, 20 + 1):
    
    print(_, end= " ")
```

  </details>

  <br>

  #### 7. Faça um programa que leia 5 números e informe o maior número.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
numeroFinal = 0

for contador in range(5):

    numero = float(input("Digite um número: "))

    if numero > numeroFinal:

        numeroFinal = numero

print("O maior número foi %d" % numeroFinal)
```

  </details>

  <br>

  #### 8. Faça um programa que leia 5 números e informe a soma e a média dos números.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
for contador in range(1) :

    numero1 = float(input("Digite o primeiro número "))

    numero2 = float(input("Digite o segundo número: "))

    numero3 = float(input("Digite o terceiro número: "))

    numero4 = float(input("Digite o quarto número: "))

    numero5 = float(input("Digite o quinto número: "))

    media = (numero1 + numero2 + numero3 + numero4 + numero5) / 5

    print("O soma foi %.2f e a média foi %.2f" % ((numero1 + numero2 + numero3 + numero4 + numero5), media))
```

  </details>

  <br>

  #### 9. Faça um programa que imprima na tela apenas os números ímpares entre 1 e 50.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
for contador in range(1, 50):

    if contador % 2 != 0:

        print("O número %d é impar" % contador)
```

  </details>

  <br>

  #### 10-11. Faça um programa que receba dois números inteiros e gere os números inteiros que estão no intervalo compreendido por eles. Depois, altere o programa anterior para mostrar no final a soma dos números.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
numeroInicial = int(input("Digite o número inicial: "))

numeroFinal = int(input("Digite o número final: "))

soma = 0

for contador in range(numeroInicial + 1, numeroFinal):
    print(contador)

    soma += contador

print(soma)
```

  </details>

  <br>

  #### 12. Desenvolva um gerador de tabuada, capaz de gerar a tabuada de qualquer número inteiro entre 1 a 10. O usuário deve informar de qual numero ele deseja ver a tabuada.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
inicioTabuada = int(input("Digite o valor inicial da tabuada: "))

for contador in range(1, 10 + 1):

    print("%d x %d = %d " % (inicioTabuada, contador, inicioTabuada * contador))
```

  </details>

  <br>

  #### 13. Faça um programa que peça dois números, base e expoente, calcule e mostre o primeiro número elevado ao segundo número. Não utilize a função de potência da linguagem.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
base = int(input("Digite o número base: "))

expoente = int(input("Digite o número expoente: "))

resultado = base

for contador in range(expoente - 1):

    resultado *= base

print(resultado)
```

  </details>

  <br>

  #### 14. Faça um programa que peça 10 números inteiros, calcule e mostre a quantidade de números pares e a quantidade de números impares.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
for contador in range(10):

    numero = int(input("Digite o número para saber se é par ou ímpar: "))

    if numero % 2 != 0:

        print("O número %d é par" % numero)

    else:

        print("O número %d é ímpar" % numero)
```

  </details>

  <br>

  #### 15. A série de Fibonacci é formada pela seqüência 0,1,1,2,3,5,8,13,21,34,55,... Faça um programa capaz de gerar a série até o n−ésimo termo.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
fibo0, fibo1 = 0, 1

for contador in range(10):

    print(fibo0)

    fibo0, fibo1 = fibo1, fibo0 + fibo1
```

  </details>

  <br>

  #### 16. A série de Fibonacci é formada pela seqüência 0,1,1,2,3,5,8,13,21,34,55,... Faça um programa que gere a série até que o valor seja maior que 500.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
fibo0, fibo1 = 0, 1

while fibo0 < 500:

    print(fibo0)

    fibo0, fibo1 = fibo1, fibo0 + fibo1
```

  </details>

  <br>

  #### 17. Faça um programa que calcule o fatorial de um número inteiro fornecido pelo usuário. Ex.: 5! = 5 x 4 x 3 x 2 x 1 = 120

  <details>
    <summary><h4>Resposta</h4></summary>

```python
numero = int(input("Digite um número para saber a fatorial: "))

resultado_fatorial = numero

for contador in range(numero, 1, -1):

    resultado_fatorial *= contador - 1

print("Fatorial de %d é %d" % (numero, resultado_fatorial))
```

  </details>

  <br>

  #### 18-19. Faça um programa que, dado um conjunto de N números, determine o menor valor, o maior valor e a soma dos valores. Depois, altere o programa anterior para que ele aceite apenas números entre 0 e 1000.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
contador = 1

maior_numero = 0

menor_numero = 0

while contador != 0:

    numero = int(input("Digite um número ou 0 para interoomper a execução: "))

    if numero == 0:

        contador = 0

    else:

        if numero > 1000:

            print("Valor inválido")

            continue

        else:

            if numero > maior_numero:

                maior_numero = numero

                menor_numero = numero

            if numero < menor_numero:

                menor_numero = numero

print("O maior número foi %d e o menor número foi %d" % (maior_numero, menor_numero))
```

  </details>

  <br>

  #### 20. Altere o programa de cálculo do fatorial, permitindo ao usuário calcular o fatorial várias vezes e limitando o fatorial a números inteiros positivos e menores que 16.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

while contador != 0:

    numero = int(input("Digite um número para saber a fatorial: "))

    if numero > 16:

        print("Somente número menores que 16")

        continue

    resultado_fatorial = numero

    for contador in range(numero, 1, -1):

        resultado_fatorial *= contador - 1

    print("Fatorial de %d é %d" % (numero, resultado_fatorial))

    contador = int(input("Digite 0 para interromper a execução: "))
```

  </details>

  <br>

  #### 21. Faça um programa que peça um número inteiro e determine se ele é ou não um número primo. Um número primo é aquele que é divisível somente por ele mesmo e por 1.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
confirmacao = 2

numero = int(input("Digite um número inteiro para saber se ele é primo ou não: "))

if numero == 0 or numero == 1:

    print("Esse número é inválido")

if numero == 2 or numero == 3:

    print("%d é um número primo" % numero)

else:

    for contador in range(confirmacao, numero + 1):

        if numero % contador != 0:

            confirmacao += 1

    if confirmacao == numero:

        print("%d é um número primo" % numero)

    else:

       print("%d não é um número primo" % numero)
```

  </details>

  <br>

  #### 22. Altere o programa de cálculo dos números primos, informando, caso o número não seja primo, por quais número ele é divisível.
  
  <details>
    <summary><h4>Resposta</h4></summary>

```python
confirmacao = 2

numero = int(input("Digite um número inteiro para saber se ele é primo ou não: "))

if numero == 0 or numero == 1:

    print("Esse número é inválido")

if numero == 2 or numero == 3:

    print("%d é um número primo" % numero)

else:

    for contador in range(confirmacao, numero + 1):

        if numero % contador != 0:

            confirmacao += 1

    if confirmacao == numero:

        print("%d é um número primo" % numero)

    else:

       print("O número %d não é primo, pois ele é divisível por: " % numero, end="")

       for contador in range(1, numero + 1):

           if numero % contador == 0:

               if numero - contador == 0:

                   print(contador, end=" ")

               else:

                    print(contador, end=", ")
```

  </details>

  <br>
  
  #### 23. Faça um programa que mostre todos os primos entre 1 e N sendo N um número inteiro fornecido pelo usuário. O programa deverá mostrar também o número de divisões que ele executou para encontrar os números primos. Serão avaliados o funcionamento, o estilo e o número de testes (divisões) executados.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

confirmacao = 2

divisoes = 0

while contador != 0:

    numero = int(input("Digite o número inicial: "))

    if numero == 0 or numero == 1:

        print("Esse número é inválido")

        continue

    else:

        numero2 = int(input("Digite o número final: "))

        if numero2 <= numero:

            print("Número final não pode ser menor ou igual ao número inicial")

            continue

        else:

            for contador2 in range(numero, numero2 + 1):

                for contador3 in range(confirmacao, numero + 1):

                    if numero % contador3 != 0:

                        confirmacao += 1

                    divisoes +=1

                if confirmacao == numero:

                    print("%d é um número primo e foram feitas %d diviões" % (numero, divisoes))

                else:

                    print("%d não é um número primo" % numero)

                confirmacao = 2

                contador3 = 2

                numero +=1

                divisoes = 0

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### 24. Faça um programa que calcule o mostre a média aritmética de N notas.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

contador2 = 0

mediaNotas = 0

while contador != 0:

    notas = float(input("Digite uma nota ou digite 0 para interromper a execução: "))

    if notas == 0:

        contador = notas

    else:

        mediaNotas += notas

        contador2 += 1

mediaNotas = mediaNotas / contador2

print("A média das notas foi %.2f" % mediaNotas)
```

  </details>

  <br>

  #### 25. Faça um programa que peça para n pessoas a sua idade, ao final o programa devera verificar se a média de idade da turma varia entre 0 e 25, 26 e 60 e maior que 60; e então, dizer se a turma é jovem, adulta ou idosa, conforme a média calculada.
  
  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
idadeMedia = 0

contador = 0

while True:

    idade = int(input("Digite a sua idade ou digite 0 para interromper a execução: "))

    if idade == 0:

        break

    else:

        contador += 1

        idadeMedia += idade

        suficiente = input("Digite sim para calcular a média de idade: ")

        if suficiente == "Sim" or suficiente == "sim":

            idadeMedia = idadeMedia / contador

            print("A idade média foi %.2f anos" % idadeMedia)

            if idadeMedia <= 25:

                print("Turma jovem")

            elif idadeMedia <= 60:

                print("Turma adulta")

            elif idadeMedia > 60:

                print("Turma idosa")
```

  </details>

  <br>

  #### 26. Numa eleição existem três candidatos. Faça um programa que peça o número total de eleitores e peça também para cada eleitor votar e ao final mostrar o número de votos de cada candidato.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

candidato1 = 0

candidato2 = 0

candidato3 = 0

while contador != 0:

    numeroEleitores = int(input("Número total de eleitores: "))

    for contador2 in range(1, numeroEleitores + 1):

        print("Qual o voto do eleitor %d ?" % contador2)

        voto = int(input("Candidato 1 - 23\nCandidato 2 - 15\nCandidato 3 - 18\n"))

        if voto == 23:

            candidato1 += 1

        elif voto == 15:

            candidato2 += 1

        elif voto == 18:

            candidato3 += 1

        else:

            print("Candidato inexistente. Voto foi nulo")

    if candidato1 > candidato2 and candidato1 > candidato3:

        print("O vencedor foi o canditado 1 com %d votos" % candidato1)

    elif candidato2 > candidato1 and candidato2 > candidato3:

        print("O vencedor foi o canditado 2 com %d votos" % candidato2)

    elif candidato3 > candidato2 and candidato3 > candidato1:

        print("O vencedor foi o canditado 3 com %d votos" % candidato3)
```

  </details>

  <br>

  #### 27. Faça um programa que calcule o número médio de alunos por turma. Para isto, peça a quantidade de turmas e a quantidade de alunos para cada turma. As turmas não podem ter mais de 40 alunos.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

contador2 = 1

mediaAlunos = 0

while contador != 0:

    quantidadeTurmas = int(input("Digite a quantidade de turmas: "))

    if quantidadeTurmas < 1:

        print("Digite um valor maior que 0")

        continue

    while quantidadeTurmas - contador2 + 1 > 0:

        print("Digite a quantidade de alunos na turma %d:" % contador2)

        quantidadeAlunos = int(input(""))

        if quantidadeAlunos > 40 or quantidadeAlunos < 1:

            print("Quantidade de alunos inválida")

            continue

        else:

            mediaAlunos += quantidadeAlunos

            contador2 += 1

    mediaAlunos = mediaAlunos / quantidadeTurmas

    print("A média de alunos por turma é %.2f" % mediaAlunos)

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### 28. Faça um programa que calcule o valor total investido por um colecionador em sua coleção de CDs e o valor médio gasto em cada um deles. O usuário deverá informar a quantidade de CDs e o valor para em cada um.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

custoTotal = 0

custoMedio = 0

while contador != 0:

    quantidadeCds = int(input("Digite a quantidade de CDs na coleção: "))

    for contador2 in range(1, quantidadeCds + 1):

        print("Digite o valor do %d° CD" % contador2)

        valorCd = float(input(""))

        custoTotal += valorCd

    custoMedio = custoTotal / quantidadeCds

    print("O custo total foi %.2f, e o custo médio de cada CD é R$ %.2f" % (custoTotal, custoMedio))

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### 29. O Sr. Manoel Joaquim possui uma grande loja de artigos de R$ 1,99, com cerca de 10 caixas. Para agilizar o cálculo de quanto cada cliente deve pagar ele desenvolveu um tabela que contém o número de itens que o cliente comprou e ao lado o valor da conta. Desta forma a atendente do caixa precisa apenas contar quantos itens o cliente está levando e olhar na tabela de preços. Você foi contratado para desenvolver o programa que monta esta tabela de preços que conterá os preços de 1 até 50 produtos.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
preco = 1.99

for contador2 in range(1, 51):

    print("%d - R$ %.2f" % (contador2, preco * contador2))
```

  </details>

  <br>

  #### 30. O Sr. Manoel Joaquim acaba de adquirir uma panificadora e pretende implantar a metodologia da tabelinha, que já é um sucesso na sua loja de 1,99. Você foi contratado para desenvolver o programa que monta a tabela de preços de pães, de 1 até 50 pães, a partir do preço do pão informado pelo usuário.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python

```

  </details>

  <br>
  
  </details>
