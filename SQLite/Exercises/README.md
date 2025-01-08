## 1. Criar um banco de dados referente à um hospital.

<details>
  <summary><h4>Resposta</h4></summary>

```sql
CREATE TABLE hospital_cardeal
(
    logradouro TEXT NOT NULL,
    municipio TEXT NOT NULL,
    complemento TEXT NOT NULL,
    cep TEXT NOT NULL,
    bairro TEXT NOT NULL,
    numero INTEGER NOT NULL,
    razao_social TEXT NOT NULL,
    nome_fantasia TEXT NOT NULL,
    cnpj TEXT PRIMARY KEY,
    telefone TEXT NOT NULL UNIQUE,
    codigo_natureza_juridica TEXT NOT NULL,
    codigo_atividade_economica TEXT NOT NULL,
    email TEXT NOT NULL UNIQUE,
    porte TEXT NOT NULL
);

CREATE TABLE enfermeiro
(
    nome TEXT NOT NULL,
    idade INTEGER NOT NULL,
    cnis TEXT NOT NULL UNIQUE,
    cpf TEXT PRIMARY KEY,
    salario REAL,
    email TEXT UNIQUE,
    endereco TEXT NOT NULL,
    codigo_crm TEXT UNIQUE
);

CREATE TABLE departamento
(
    departamento_id INTEGER PRIMARY KEY,
    orcamento REAL NOT NULL,
    nome TEXT NOT NULL,
    nome_diretor TEXT UNIQUE,
    quantidade_funcionarios INTEGER NOT NULL
)
```

  </details>

  <br>
