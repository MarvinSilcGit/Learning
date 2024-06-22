# Códigos básicos do SQL

## Create Table:

### 1. Tabela hospital_geral_santa_tereza

```sql
CREATE TABLE hospital_geral_santa_tereza
(
	cnpj TEXT,
	nome_empresarial TEXT,
	nome_fantasia TEXT,
	telefone INTEGER,
	cep TEXT,
	bairro TEXT,
	cidade TEXT,
	logradouro TEXT,
	email TEXT,
	orcamento REAL
);
```
### 2. Tabela estudante_cetep

```sql
CREATE TABLE estudante_cetep
(
	cpf TEXT,
	matricula INTEGER,
	data_nascimento TEXT,
	nome TEXT
);
```

### 3. Tabela estudante_cetep (aprimorada)

```sql
CREATE TABLE estudante_cetep
(
	cpf TEXT,
	matricula INTEGER,
	data_nascimento TEXT,
	nome TEXT,
	email TEXT,
	nte TEXT,
	municipio TEXT,
	escola TEXT,
	codigo_sec INTEGER,
	oferta_ensino TEXT,
	ano_serie TEXT,
	turma TEXT
);
```
