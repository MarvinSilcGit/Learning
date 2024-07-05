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
