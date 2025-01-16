# List of functions

<details>
  <summary>
    <h2>Date and Time</h2>
  </summary>

  ### strftime

  #### Essa função possui até 2 argumentos e tem a função de retornar o horário ou a data conforme os argumentos. A seguir, a lista de marcadores:

##### 1. <code>%d</code> dia do mês: 01-31

```sql
SELECT strftime('%d');
```

##### 2. %F data no formato: YYYY-MM-DD

```SQL
SELECT strftime('%F');
```

##### 3. <code>%j</code> dia do ano: 001-366

```SQL
SELECT strftime('%j');
```

##### 4. <code>%m</code> mês do ano: 1-12

```SQL
SELECT strftime('%m');
```

##### 5. <code>%W</code> semana do ano a partir da primeira segunda: 00-53

```SQL
SELECT strftime('%W');
```

##### 6. <code>%p</code> "am" ou "pm" dependendo do horário:

```SQL
SELECT strftime('%p');
```

##### 7. <code>%H</code> horas: 00-24

```SQL
SELECT strftime('%H');
```

##### 8. <code>%M</code> minutos: 00-59

```SQL
SELECT strftime('%M');
```

##### 9. <code>%S</code> segundos: 00-59

```SQL
SELECT strftime('%S');
```

</details>
