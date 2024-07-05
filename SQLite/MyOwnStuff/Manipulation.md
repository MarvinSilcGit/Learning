# Tests

## Manipulation

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
