# Tests

## Manipulation

### SELECT FROM

```sql
SELECT * FROM estudante_cetep;
```

### CREATE TABLE

```sql
CREATE TABLE estudante_cetep
(
	matricula INTEGER PRIMARY KEY,
	cpf TEXT UNIQUE NOT NULL,
	nome TEXT NOT NULL,
	email TEXT NOT NULL,
	cidade TEXT NOT NULL,
	oferta_ensino TEXT NOT NULL,
	ano_serie INTEGER NOT NULL,
	turma TEXT NOT NULL
);
```

### INSERT INTO

```sql
INSERT INTO estudante_cetep (cpf, nome, email, cidade, oferta_ensino, ano_serie, turma)
VALUES ('543.786.210-81', 'Camino', 'comio@mail.com', 'Pombilvis', 'Técnico Agrário', 2, 'B');
```

### ALTER TABLE

```sql
ALTER TABLE estudante_cetep
ADD COLUMN rg INTEGER;

ALTER TABLE estudante_cetep
ADD COLUMN data_nascimento TEXT;

ALTER TABLE estudante_cetep
ADD COLUMN sexualidade TEXT;
```

### UPDATE SET

```sql
UPDATE estudante_cetep SET sexualidade = 'Fêmea' WHERE matricula = 2;
UPDATE estudante_cetep SET data_nascimento = '11/01/2007' WHERE matricula = 2;
UPDATE estudante_cetep SET rg = 14111983 WHERE matricula = 2;
```

### DELETE FROM

```sql
DELETE FROM estudante_cetep
WHERE matricula = 1;
```
