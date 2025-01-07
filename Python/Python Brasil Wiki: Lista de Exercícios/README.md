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
raio_circulo = int(input("Digite o raio do círculo: "))

area = 3.14 * (raio_circulo ** 2)

print(area)
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
numero_inteiro1 = int(input("Digite o primeiro número inteiro: "))

numero_inteiro2 = int(input("Digite o segundo número inteiro: "))

numero_real = float(input("Digite o número real: "))

resultado1 = numero_inteiro1 * 2 * numero_inteiro2 / 2

print(resultado1)

resultado2 = numero_inteiro1 * 3 + numero_real

print(resultado2)

resultado3 = numero_real ** 3

print(resultado3)
```

  </details>

  <br>

  #### 12. Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula: (72.7 * altura) - 58

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
altura = float(input("Digite sua altura: "))

peso_ideal = (72.7 * altura) - 58

print("O peso ideal dessa pessoa é %.2f" % peso_ideal)
```

  </details>

  <br>

  #### 13. Tendo como dado de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas: Para homens: (72.7 * altura) - 58 e para mulheres: (62.1 * altura) - 44.7 

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
altura_homem = float(input("Digite a altura do homem: "))

altura_mulher = float(input("Digite a altura da mulher: "))

peso_ideal_homem = (72.7 * altura_homem) - 58

peso_ideal_mulher = (62.1 * altura_mulher) - 44.7

print("O peso ideal desse homem é %.2f.\nO peso ideal dessa mulher é %.2f" % (peso_ideal_homem, peso_ideal_mulher))
```

  </details>

  <br>

  #### 14. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.

   <details>
    <summary><h4>Resposta</h4></summary>
     
```python
peso_peixe = float(input("Digite o peso do peixe: "))

if peso_peixe > 50:

    peso_limite = 50

    peso_adicional = peso_peixe - peso_limite

    multa = peso_adicional * 4

    print("A multa será R$ %.2f por exceder o peso limite em %.2f quilos " % (multa, peso_adicional))

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

salario_liquido = salario

salario_liquido -= salario / 100 * 11

salario_liquido -= salario_liquido / 100 * 8

salario_liquido -= salario_liquido / 100 * 5

print("O salário líquido será R$ %.2f, com R$ %.2f de desconto" % (salario_liquido, salario - salario_liquido))
```

  </details>

  <br>

  #### 16. Faça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.

  <details>
    <summary><h4>Resposta</h4></summary>

```python
metragem = float(input("Digite a metragem: "))

cobertura_tinta = 3

metragem_lata = 18 * cobertura_tinta

quantidade_latas = 0

preco_final = 0

preco_lata = 80

if metragem / metragem_lata <= 1:

    quantidade_latas = 1

    preco_final = quantidade_latas * preco_lata

    print("Será necessária, no máximo, uma lata de tinta para pintar %.2f metros². O custo será R$ %.2f" % (metragem, preco_final))

else:

    if metragem % metragem_lata == 0:

        quantidade_latas = metragem / metragem_lata

        preco_final = quantidade_latas * preco_lata

        print("Serão necessária exatas %d latas de tinta para pintar %.2f metros². O custo será R$ %.2f" % (quantidade_latas, metragem, preco_final))

    else:

        quantidade_latas = (metragem // metragem_lata) + 1

        preco_final = quantidade_latas * preco_lata

        print("Será necessária aos menos %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_latas, metragem, preco_final))
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
metragem_area = float(input("Digite a metragem: "))

cobertura_tinta = 6

metragem_lata = 18 * cobertura_tinta

preco_lata = 80

quantidade_latas = 0

metragem_galao = 3.6 * cobertura_tinta

preco_galao = 25

quantidade_galoes = 0

preco_final = 0

if metragem_area <= metragem_galao * 4:

    if metragem_area % metragem_galao == 0:

        quantidade_galoes = metragem_area / metragem_galao

        preco_final = quantidade_galoes * preco_galao

        print("Serão necessários exatos %d galões de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_galoes, metragem_area, preco_final))

    else:

        quantidade_galoes = metragem_area // metragem_galao + 1

        preco_final = quantidade_galoes * preco_galao

        print("Serão necessários aos menos %d galões de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_galoes, metragem_area, preco_final))

else:

    if metragem_area % metragem_lata == 0:

        quantidade_latas = metragem_area / metragem_lata

        preco_final = quantidade_latas * preco_lata

        print("Serão necessária exatas %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_latas, metragem_area, preco_final))

    else:

        if metragem_area - metragem_lata < 0:

            quantidade_latas = metragem_area // metragem_lata + 1

            preco_final = quantidade_latas * preco_lata

            print("Serão necessária ao menos %d latas de tinta para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_latas, metragem_area, preco_final))

        else:

            quantidade_latas = metragem_area // metragem_lata

            preco_final = quantidade_latas * preco_lata

            metragemRestante = metragem_area - (metragem_lata * quantidade_latas)

            if metragemRestante % metragem_galao == 0:

                quantidade_galoes = metragemRestante / metragem_galao

                preco_final += quantidade_galoes * preco_galao

                print("Serão necessárias ao menos %d latas de tinta e ao menos %d Galões para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_latas, quantidade_galoes, metragem_area, preco_final))

            else:

                if metragemRestante // metragem_galao >= 4:

                    quantidade_latas +=1

                    preco_final = quantidade_latas * preco_lata

                    quantidade_galoes = 0

                else:

                    quantidade_galoes = metragemRestante // metragem_galao + 1

                    preco_final += quantidade_galoes * preco_galao

                print("Serão necessárias ao menos %d latas de tinta e ao menos %d Galões para pintar %.1f metros². O custo será R$ %.2f" % (quantidade_latas, quantidade_galoes, metragem_area, preco_final))
```

  </details>

  <br>

  #### 18. Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
tamanho_arquivo = float(input("Digite o tamanho do arquivo em Megabytes: "))

if tamanho_arquivo < 1:

    print("Valor inválido!")

velecidade_link = float(input("Digite a velocidade de sua conexão em megabits: "))

tempo_download = (tamanho_arquivo / (velecidade_link / 8))

if tempo_download >= 60:

    tempo_download = tempo_download / 60

    print("O tempo de Download será de no mínimo %.1f minutos" % tempo_download)

else:

    print("O tempo de Download será de no mínimo %.1f segundos" % tempo_download)
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
letra_busca = input("Digite a letra para saber se é vogal ou consoante: ")

if (letra_busca == "a" or letra_busca == "e" or letra_busca == "i" or letra_busca == "o" or letra_busca == "u" or letra_busca == "A"
    or letra_busca == "E" or letra_busca == "I" or letra_busca == "O" or letra_busca == "U"):

    print("A letra '%s' é Vogal" % letra_busca)

elif (letra_busca == "b" or letra_busca == "c" or letra_busca == "d" or letra_busca == "f" or letra_busca == "g" or letra_busca == "h"
    or letra_busca == "j" or letra_busca == "k" or letra_busca == "l" or letra_busca == "m" or letra_busca == "n" or letra_busca == "p"
    or letra_busca == "q" or letra_busca == "r" or letra_busca == "s" or letra_busca == "t" or letra_busca == "v" or letra_busca == "w"
    or letra_busca == "x" or letra_busca == "y" or letra_busca == "z" or letra_busca == "ç" or letra_busca == "B" or letra_busca == "C"
    or letra_busca == "D" or letra_busca == "F" or letra_busca == "G" or letra_busca == "H" or letra_busca == "J" or letra_busca == "K"
    or letra_busca == "L" or letra_busca == "M" or letra_busca == "N" or letra_busca == "P" or letra_busca == "Q" or letra_busca == "R"
    or letra_busca == "S" or letra_busca == "T" or letra_busca == "V" or letra_busca == "W" or  letra_busca =="X" or  letra_busca =="Y"
    or letra_busca == "Z" or letra_busca == "Ç"):

    print("A letra '%s' é Consoante" % letra_busca)

else:

    print("O caractere '%s' não é nem vogal nem consoante" % letra_busca)
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
salario_inicial = float(input("Digite o salário atual: "))

aumento = 0

salario_final = salario_inicial

if salario_inicial <= 280:

    aumento = salario_inicial / 100 * 20

    salario_final += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 20 por cento" % (salario_inicial, salario_final, aumento,))

elif salario_inicial <= 700:

    aumento = salario_inicial / 100 * 15

    salario_final += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 15 por cento" % (salario_inicial, salario_final, aumento,))

elif salario_inicial <= 1500:

    aumento = salario_inicial / 100 * 10

    salario_final += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 10 por cento" % (salario_inicial, salario_final, aumento,))

elif salario_inicial > 1500:

    aumento = salario_inicial / 100 * 5

    salario_final += aumento

    print("O salário antes do reajuste era de R$ %.2f e passou a ser R$ %.2f com um aumento de R$ %.2f, ou um aumento de 5 por cento" % (salario_inicial, salario_final, aumento,))
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
carga_horaria = int(input("Digite a sua carga horária mensal: "))

salario_hora = float(input("Digite o seu salário hora: "))

salario_bruto = carga_horaria * salario_hora

descontos = 0

imposto_renda = 0

inss = 0

if salario_bruto <=  900:

    print("O salário será R$ %.2f com R$ %.2f de Imposto de renda, R$ %.2f de INSS. Totalizando R$ %.2f em descontos" % (salario_bruto, imposto_renda, inss, descontos))

elif salario_bruto <= 1500:

    imposto_renda = salario_bruto / 100 * 5

    inss = salario_bruto / 100 * 10

    descontos = imposto_renda + inss

elif salario_bruto <= 2500:

    imposto_renda = salario_bruto / 100 * 10

    inss = salario_bruto / 100 * 10

    descontos = imposto_renda + inss

elif salario_bruto > 2500:

    imposto_renda = salario_bruto / 100 * 20

    inss = salario_bruto / 100 * 10

    descontos = imposto_renda + inss

print("O salário inicial era de R$ %.2f e será R$ %.2f, com R$ %.2f de Imposto de renda e R$ %.2f de INSS. Totalizando R$ %.2f em descontos" % (salario_bruto, salario_bruto - descontos, imposto_renda, inss, descontos))
```

  </details>

  <br>

  #### 13. Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
dia_semana = input("Digite o dia da semana:\n1 - Domingo\n2 - Segunda-feira\n3 - Terça-feira\n4 - Quarta-feira\n5 - Quinta-feira\n6 - Sexta-feira\n7 - Sábado\n")

if dia_semana == "1":

    print("Domingo")

elif dia_semana == "2":

    print("Segunda-feira")

elif dia_semana == "3":

    print("Terça-feira")

elif dia_semana == "4":

    print("Quarta-feira")

elif dia_semana == "5":

    print("Quinta-feira")

elif dia_semana == "6":

    print("Sexta-feira")

elif dia_semana == "7":

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
nota_parcial1 = float(input("Digite a primeira nota parcial: "))

if nota_parcial1 > 10 or nota_parcial1 < 0:

    print("Nota inválida")

nota_parcial2 = float(input("Digite a segunda nota parcial: "))

if nota_parcial2 > 10 or nota_parcial2 < 0:

    print("Nota inválida")

media_final = (nota_parcial1 + nota_parcial2) / 2

if media_final >= 6:

    print("Aprovado e a média foi %.2f" % media_final)

    if media_final >= 9 and media_final <= 10:

        print("Conceito A")

    elif media_final >= 7.5 and media_final < 9:

        print("Conceito B")

    elif media_final >= 6 and media_final < 7.5:

        print("Conceito C")

else:

    print("Reprovado e a média foi %.2f" % media_final)

    if media_final >= 4 and media_final < 6:

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
import cmath

a = int(input("Digite o valor de a: "))

if a < 1:

    print("Valor inválido")

else:

    b = int(input("Digite o valor de b: "))

    c = int(input("Digite o valor de c: "))

    delta = b ** 2 - 4 * a * c

    raiz_negativa = (- b - cmath.sqrt(delta)) / 2 * a

    raiz_positiva = (- b + cmath.sqrt(delta)) / 2 * a

    raiz_negativa = raiz_negativa.real

    raiz_positiva = raiz_positiva.real

    if delta < 0:

        print("A equação não possui raizes reais")

    elif delta == 0:

        print("A equação possui apenas uma raiz real")

        print("A raiz positiva é %d" % raiz_positiva)

    else:

        print("A equação possui duas raiz reais")

        print("A raiz negativa é %d e a raiz positiva é %d" % (raiz_negativa, raiz_positiva))
```

  </details>

  <br>

  #### 17. Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
ano_bissexto = int(input("Digite o ano para saber se é bissexto ou não: "))

if ano_bissexto % 4 == 0:

    if ano_bissexto % 100 != 0:

        print("O ano %d é bissexto" % ano_bissexto)

    elif ano_bissexto % 100 == 0:

        print("O ano %d é bissexto especial" % ano_bissexto)

else:

    print("O ano %d não é bissexto" % ano_bissexto)
```

  </details>

  <br>

  #### 18. Faça um Programa que peça uma data no formato dd/mm/aaaa e determine se a mesma é uma data válida.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
formato_data = input("Digite a data no formato dd/mm/aaaa: ")

if len(formato_data) != 10 or formato_data[2] == "/" or formato_data[5] == "/":

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

quantidade_centena = 0

quantidade_dezena = 0

quantidade_unidade = 0

quantidade_decimo = 0

if valor // 100 > 0:

    quantidade_centena = valor // 100

    valor -= quantidade_centena * 100

    if valor // 10 > 0:

        quantidade_dezena = valor // 10

        valor -= quantidade_dezena * 10

        if valor // 1 > 0:

            quantidade_unidade = valor // 1

            valor -= quantidade_unidade * 1

print("%d = %d centenas, %d dezenas e %d unidades" % (0 + (quantidade_unidade * 1) + 0 + (quantidade_dezena * 10) + 0 + (quantidade_centena * 100), quantidade_centena, quantidade_dezena, quantidade_unidade))
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

valor_pagamento = math.trunc(valor)

if valor_pagamento < 10:

    print("Valor insuficiente para saque")

else:

    cedulas = 0

    limite_cedula = 100

    while True:

        if limite_cedula <= valor_pagamento:

            valor_pagamento -= limite_cedula

            cedulas += 1

        else:

            print("%d cédula(s) de R$ %.2f" % (cedulas, limite_cedula))

            if valor_pagamento == 0:

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

numero_decimal = float(input("Digite o número para saber se é decimal ou não: "))

numero_inteiro = math.trunc(numero_decimal)

if numero_decimal > numero_inteiro:

    print("O número %.1f é decimal" % numero_decimal)

else:

    print("O número %d não é decimal" % numero_inteiro)
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
import math

operacao = input("Digite qual operação deseja realizar:\n1 - Inteiro ou decimal\n2 - Par ou Ímpar\n3 - Positivo ou Negativo\n")

if operacao == "1":

    numero_decimal = float(input("Digite o número para saber se é decimal ou não: "))

    numero_inteiro = math.trunc(numero_decimal)

    if numero_decimal > numero_inteiro:

        print("O número %.1f é decimal" % numero_decimal)

    else:

        print("O número %d não é decimal" % numero_inteiro)

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
  
  #### 25. Faça um programa que faça 5 perguntas para uma pessoa sobre um crime.  Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente". O programa deve no final emitir uma classificação sobre a participação da pessoa no crime. As perguntas são:
 
  1. "Telefonou para a vítima?"
  2. "Esteve no local do crime?"
  3. "Mora perto da vítima?"
  4. "Devia para a vítima?"
  5. "Já trabalhou com a vítima?"

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
pergunta1 = input("Você telefonou para a vítima?: ")

pergunta2 = input("Você esteve no local do crime? ")

pergunta3 = input("Você mora perto da Vítima? ")

pergunta4 = input("Você devia para a vítima? ")

pergunta5 = input("Você já trabalhou com a vítima? ")

criminalidade = 0

if pergunta1 == "Sim" or pergunta1 == "sim":

    criminalidade += 1

if pergunta2 == "Sim" or pergunta2 == "sim":

    criminalidade += 1

if pergunta3 == "Sim" or pergunta3 == "sim":
    criminalidade += 1

if pergunta4 == "Sim" or pergunta4 == "sim":

    criminalidade += 1

if pergunta5 == "Sim" or pergunta5 == "sim":

    criminalidade += 1

if criminalidade <= 1:

    print("Inocente")

elif criminalidade == 2:

    print("Suspeito")

elif criminalidade <= 4:

    print("Cúmplice")

elif criminalidade == 5:

    print("Assasino")
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
quantidade_litros = float(input("Digite a quantidade de litros: "))

tipo_gasolina = input("Para Álcool digite A\nPara Gasolina digite G\n")

preco_final = 0

if tipo_gasolina == "A" or tipo_gasolina == "a":

    if quantidade_litros <= 20:

        preco_final = quantidade_litros * 1.9

        preco_final -= preco_final / 100 * 3

    else:

        preco_final = quantidade_litros * 1.9

        preco_final -= preco_final / 100 * 4

elif tipo_gasolina == "G" or tipo_gasolina == "g":

    if quantidade_litros <= 20:

        preco_final = quantidade_litros * 2.5

        preco_final -= preco_final / 100 * 4

    else:

        preco_final = quantidade_litros * 2.5

        preco_final -= preco_final / 100 * 5

print("O preço final será R$ %.2f" % preco_final)
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
quantidade_morango = float(input("Digite a quantidade em kilos de morangos: "))

quantidade_maca = float(input("Digite a quantidade em kilos de maçãs: "))

preco_final = 0

if quantidade_morango <= 5:

    preco_final += quantidade_morango * 2.5

else:

    preco_final += quantidade_morango * 2.2

if quantidade_maca <= 5:

    preco_final += quantidade_maca * 1.8

else:

    preco_final += quantidade_maca * 1.2

print("O preço final será R$ %.2f" % preco_final)
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
quantidade_file = int(input("Digite a quantidade em kilos de Filé Duplo: "))

quantidade_picanha = int(input("Digite a quantidade em kilos de Picanha: "))

quantidade_alcatra = int(input("Digite a quantidade em kilos de Alcatra: "))

preco_final = 0

if quantidade_file <= 5:

    preco_final += quantidade_file * 4.9

else:

    preco_final += quantidade_file * 5.8

if quantidade_picanha <= 5:

    preco_final += quantidade_picanha * 5.9

else:

    preco_final += quantidade_picanha * 6.8

if quantidade_alcatra <= 5:

    preco_final += quantidade_alcatra * 6.9

else:

    preco_final += quantidade_picanha * 7.8

print("O preço final será R$ %.2f" % preco_final)
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

                    estado_civil = input("Digite seu estado civil:\ns - solteiro(a)\nv - viúvo(a)\nc - casado(a)\nd - divorciado\n")

                    if estado_civil != "s" and estado_civil != "v" and estado_civil != "c" and estado_civil != "d":

                        print("Estado civil inválido")

                        continue

                    else:

                        print("%s, %d, %.2f, %s, %s" % (nome, idade, salario, sexo, estado_civil))

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
numero_final = 0

for contador in range(5):

    numero = float(input("Digite um número: "))

    if numero > numero_final:

        numero_final = numero

print("O maior número foi %d" % numero_final)
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
numero_inicial = int(input("Digite o número inicial: "))

numero_final = int(input("Digite o número final: "))

soma = 0

for contador in range(numero_inicial + 1, numero_final):

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
inicio_tabuada = int(input("Digite o valor inicial da tabuada: "))

for contador in range(1, 10 + 1):

    print("%d x %d = %d " % (inicio_tabuada, contador, inicio_tabuada * contador))
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

    numero = int(input("Digite um número ou 0 para interromper a execução: "))

    if numero == 0:

        contador = 0

    else:

        if numero > 1000 or numero < 1:

            print("Valor inválido")

            continue

        else:

            if menor_numero == 0:

                menor_numero = numero

            if maior_numero < numero:

                maior_numero = numero

            if menor_numero > numero:

                menor_numero = numero

if maior_numero == menor_numero:

    print("Os números são idênticos")

else:

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

media_notas = 0

while contador != 0:

    notas = float(input("Digite uma nota ou digite 0 para interromper a execução: "))

    if notas == 0:

        contador = notas

    else:

        media_notas += notas

        contador2 += 1

media_notas = media_notas / contador2

print("A média das notas foi %.2f" % media_notas)
```

  </details>

  <br>

  #### 25. Faça um programa que peça para n pessoas a sua idade, ao final o programa devera verificar se a média de idade da turma varia entre 0 e 25, 26 e 60 e maior que 60; e então, dizer se a turma é jovem, adulta ou idosa, conforme a média calculada.
  
  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
idade_media = 0

contador = 0

while True:

    idade = int(input("Digite a sua idade ou digite 0 para interromper a execução: "))

    if idade == 0:

        break

    else:

        contador += 1

        idade_media += idade

        suficiente = input("Digite sim para calcular a média de idade: ")

        if suficiente == "Sim" or suficiente == "sim":

            idade_media = idade_media / contador

            print("A idade média foi %.2f anos" % idade_media)

            if idade_media <= 25:

                print("Turma jovem")

            elif idade_media <= 60:

                print("Turma adulta")

            elif idade_media > 60:

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

    numero_eleitores = int(input("Número total de eleitores: "))

    for contador2 in range(1, numero_eleitores + 1):

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

custo_total = 0

custo_medio = 0

while contador != 0:

    quantidade_cds = int(input("Digite a quantidade de CDs na coleção: "))

    for contador2 in range(1, quantidade_cds + 1):

        print("Digite o valor do %d° CD" % contador2)

        valorCd = float(input(""))

        custo_total += valorCd

    custo_medio = custo_total / quantidade_cds

    print("O custo total foi %.2f, e o custo médio de cada CD é R$ %.2f" % (custo_total, custo_medio))

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
preco = float(input("Digite o preço da unidade do Pão: "))

for contador in range(1, 51):

    print("%d - R$ %.2f" % (contador, preco * contador))
```

  </details>

  <br>

   #### 31. O Sr. Manoel Joaquim expandiu seus negócios para além dos negócios de 1,99 e agora possui uma loja de conveniências. Faça um programa que implemente uma caixa registradora rudimentar. O programa deverá receber um número desconhecido de valores referentes aos preços das mercadorias. Um valor zero deve ser informado pelo operador para indicar o final da compra. O programa deve então mostrar o total da compra e perguntar o valor em dinheiro que o cliente forneceu, para então calcular e mostrar o valor do troco. Após esta operação, o programa deverá voltar ao ponto inicial, para registrar a próxima compra.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

preco_final = 0

contador3 = 1

troco = 0

valor_pagamento = 0

while contador != 0:

    while True:

        print("Digite o preço da mercadoria %d ou 0 para finalizar a compra: " % contador3)

        preco = float(input(""))

        preco_final += preco

        contador3 += 1

        if preco == 0:

            contador3 = 1

            break

    print("Total: %.2f" % preco_final)

    while True:

        valor_pagamento = float(input("Digite o valor de pagamento: "))

        if valor_pagamento < preco_final:

            print("Valor insuficiente para o pagamento")

            continue

        else:

            troco = valor_pagamento - preco_final

            print("Troco: %.2f" % troco)

            break

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()
```

  </details>

  <br>

  #### 32. Faça um programa que calcule o fatorial de um número inteiro fornecido pelo usuário. Ex.: 5! = 5.4.3.2.1 = 120. A saída deve ser conforme o exemplo anterior:

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
numero = int(input("Fatorial de: "))

resultado_fatorial = numero

print("%d! =" % numero, end=" ")

for contador in range(numero, 0, -1):

    if contador == 1:

        print("%d" % contador, end=" = ")

        break

    else:

        resultado_fatorial *= contador - 1

        print("%d" % contador, end=" x ")

print(resultado_fatorial)
```

  </details>

  <br>

  #### 33. O Departamento Estadual de Meteorologia lhe contratou para desenvolver um programa que leia as um conjunto indeterminado de temperaturas, e informe ao final a menor e a maior temperaturas informadas, bem como a média das temperaturas.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

maior_temperatura = 0

menor_temperatura = 0

while contador != 0:

    temperatura = float(input("Digite uma temperatura ou 0 para interromper a execução: "))

    if temperatura == 0:

        contador = 0

    else:

        if menor_temperatura == 0:

            menor_temperatura = temperatura

        if maior_temperatura < temperatura:

            maior_temperatura = temperatura

        if menor_temperatura > temperatura:

            menor_temperatura = temperatura

if maior_temperatura == menor_temperatura:

    print("Os números são idênticos")

else:

    print("O maior temperatura foi %.1f° e a menor temperatura foi %.1f°" % (maior_temperatura, menor_temperatura))
```

  </details>

  <br>

  #### 36. Desenvolva um programa que faça a tabuada de um número qualquer inteiro que será digitado pelo usuário, mas a tabuada não deve necessariamente iniciar em 1 e terminar em 10, o valor inicial e final devem ser informados também pelo usuário. Obs: Você deve verificar se o usuário não digitou o final menor que o inicial.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
tabuada = int(input("Montar tabuada de: "))

inicio_tabuada = int(input("Começar por: "))

fim_tabudada = int(input("Terminar em: "))

if fim_tabudada <= inicio_tabuada:

    print("O fim não pode ser menor ou igual ao início da tabuada")

else:

    print()

    print("Vou montar a tabuada de %d, começando por %d e terrminando em %d:" % (tabuada, inicio_tabuada, fim_tabudada))

    for contador in range(inicio_tabuada, fim_tabudada + 1):

        print("%d x %d = %d " % (tabuada, contador, tabuada * contador))
```

  </details>

  <br>

  #### 37. Uma academia deseja fazer um senso entre seus clientes para descobrir o mais alto, o mais baixo, a mais gordo e o mais magro, para isto você deve fazer um programa que pergunte a cada um dos clientes da academia seu código, sua altura e seu peso. O final da digitação de dados deve ser dada quando o usuário digitar 0 (zero) no campo código. Ao encerrar o programa também deve ser informados os códigos e valores do cliente mais alto, do mais baixo, do mais gordo e do mais magro, além da média das alturas e dos pesos dos clientes.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

contador2 = 0

codigo = 0

maior_altura = 0

menor_altura = 0

codigo_pessoa_menor_altura = 0

codigo_pessoa_maior_altura = 0

media_altura = 0

maior_peso = 0

menor_peso = 0

codigo_pessoa_maior_peso = 0

codigo_pessoa_menor_peso = 0

media_peso = 0

while contador != 0:

    altura = float(input("Digite a altura da pessoa: "))

    peso = float(input("Digite o peso da pessoa: "))

    codigo = int(input("Digite o código da pessoa: "))

    media_altura += altura

    media_peso += peso

    contador2 += 1

    if altura < 0.5 or peso < 30 or codigo < 1:

        print("Valores incorretos")

        continue

    else:

        if menor_altura == 0:

            menor_altura = altura

            codigo_pessoa_menor_altura = codigo

        if maior_altura < altura:

            maior_altura = altura

            codigo_pessoa_maior_altura = codigo

        if menor_altura > altura:

            menor_altura = altura

            codigo_pessoa_menor_altura = codigo

        if menor_peso == 0:

            menor_peso = peso

            codigo_pessoa_menor_peso = codigo

        if maior_peso < peso:

            maior_peso = peso

            codigo_pessoa_maior_peso = codigo

        if menor_peso > peso:

            menor_peso = peso

            codigo_pessoa_menor_peso = codigo

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()

media_altura = media_altura / contador2

media_peso = media_peso / contador2

print("O cliente com o código %d teve a maior altura %.2f" % (codigo_pessoa_maior_altura, maior_altura))

print("O cliente com o código %d teve a menor altura %.2f" % (codigo_pessoa_menor_altura, menor_altura))

print("A média de altura foi %.2f" % media_altura)

print()

print("O cliente com o código %d teve o maior peso %.1f" % (codigo_pessoa_maior_peso, maior_peso))

print("O cliente com o código %d teve o menor peso %.1f" % (codigo_pessoa_menor_peso, menor_peso))

print("A média de peso foi %.1f" % media_peso)
```

  </details>

  <br>

  #### 38. Um funcionário de uma empresa recebe aumento salarial anualmente: Sabe-se que: Esse funcionário foi contratado em 1995, com salário inicial de R$ 1.000,00; Em 1996 recebeu aumento de 1,5% sobre seu salário inicial; A partir de 1997 (inclusive), os aumentos salariais sempre correspondem ao dobro do percentual do ano anterior. Faça um programa que determine o salário atual desse funcionário. Após concluir isto, altere o programa permitindo que o usuário digite o salário inicial do funcionário.

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
salario = float(input("Digite o salário inicial: "))

juros_inicial = 1.5

for contador in range(1996, 2024 + 1):

    salario += salario / 100 * juros_inicial

    juros_inicial = juros_inicial * 2

    print("R$ %.2f de salário no ano de %d" % (salario, contador))
```

  </details>

  <br>

  #### 39. Faça um programa que leia dez conjuntos de dois valores, o primeiro representando o número do aluno e o segundo representando a sua altura em centímetros. Encontre o aluno mais alto e o mais baixo. Mostre o número do aluno mais alto e o número do aluno mais baixo, junto com suas alturas

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
contador = 1

numero = 0

maior_altura = 0

menor_altura = 0

numero_aluno_baixo = 0

numero_aluno_alto = 0

while contador != 0:

    altura = float(input("Digite a altura do aluno: "))

    numero = int(input("Digite o número do aluno: "))

    if altura < 0.5 or numero < 1:

        print("Valores incorretos")

        continue

    else:

        if menor_altura == 0:

            menor_altura = altura

            numero_aluno_baixo = numero

        if maior_altura < altura:

            maior_altura = altura

            numero_aluno_alto = numero

        if menor_altura > altura:

            menor_altura = altura

            numero_aluno_baixo = numero

    print()

    contador = int(input("Digite 0 para interromper a execução: "))

    print()

print("O aluno com o número %d teve a maior altura %.2f" % (numero_aluno_alto, maior_altura))

print("O aluno com o número %d teve a menor altura %.2f" % (numero_aluno_baixo, menor_altura))
```

  </details>

  <br>

  #### 40. Foi feita uma estatística em cinco cidades brasileiras para coletar dados sobre acidentes de trânsito. Foram obtidos os seguintes dados:

  1. Código da cidade.
  2. Número de veículos de passeio (em 1999).
  3. Número de acidentes de trânsito com vítimas (em 1999).
  4. Qual o maior e menor índice de acidentes de transito e a que cidade pertence?
  5. Qual a média de veículos nas cinco cidades juntas?
  6. Qual a média de acidentes de trânsito nas cidades com menos de 2.000 veículos de passeio?

  <details>
    <summary><h4>Resposta</h4></summary>
    
```python
maior_media_acidentes = 0

menor_media_acidentes = 0

media_veiculos = 0

codigo_cidade_menor_acidente = 0

codigo_cidade_maior_acidente = 0

contador = 0

while contador != 5:

    codigo = int(input("Digite o código da cidade: "))

    numero_veiculos = int(input("Digite o número de veículo na cidade: "))

    numero_acidentes = int(input("Digite o número de acidentes no ano: "))

    if menor_media_acidentes == 0:

        menor_media_acidentes = numero_acidentes / numero_veiculos * 100

        codigo_cidade_menor_acidente = codigo

    if maior_media_acidentes < numero_acidentes / numero_veiculos * 100:

        maior_media_acidentes = numero_acidentes / numero_veiculos * 100

        codigo_cidade_maior_acidente = codigo

    if menor_media_acidentes > numero_acidentes / numero_veiculos * 100:

        menor_media_acidentes = numero_acidentes / numero_veiculos * 100

        codigo_cidade_menor_acidente = codigo

    media_veiculos += numero_veiculos

    contador += 1

media_veiculos = media_veiculos / contador

print("A cidade com o código %d teve a maior taxa de acidentes com %.2f" % (codigo_cidade_maior_acidente, maior_media_acidentes))

print("A cidade com o código %d teve a menor taxa de acidentes com %.2f" % (codigo_cidade_menor_acidente, menor_media_acidentes))

print("A média de veículos das %d cidades é %.2f" % (contador, media_veiculos))
```

  </details>

  <br>
  
  </details>
