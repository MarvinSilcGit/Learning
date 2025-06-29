
<details>
  <summary>
    <h2>Strings</h2>
  </summary>

  # Formatting basics

```python
x = 10

# Utilização de marcador do tipo inteiro <code>%d</code>

print("João tem %d anos" % x)

print("[%4d]" % x)

print("[%-4d]" % x)


# utilização de marcador do tipo flutuante <code>%f</code>

print("joão tem [%.2f]" % x)

print("joão tem [%.1f]" % x)


# utilização de marcador do tipo string <code>%s</code>

john = "joão"

print("Meu nome é %s" % john)


# Utilizando múltiplos marcadores

john = "joão"

idade = x

dinheiro = x * 10

print("%s tem %d anos e %.2f reais de dinheiro" % (john, idade, dinheiro)) # Acrescente o parênteses
```
</details>
