# Sintax

<details>
	<summary><h2>Mindmaps</h2></summary>

### Simple Mindmap

```
mindmap
	**Course**
		**HTML**
			(Semantics)
			(Accessibility)
			(Headings)
		**JavaScript**
			(Numbers)
			(Strings)
		**CSS**
			(Style)
			(Visuals)
```


```mermaid
mindmap
	**Course**
		**HTML**
			(Semantics)
			(Accessibility)
			(Headings)
		**JavaScript**
			(Numbers)
			(Strings)
		**CSS**
			(Style)
			(Visuals)
```

### Shapes

```
mindmap
	Formas
	    id[I am a square]
	    id(I am a rounded square)
	    id((I am a circle))
	    id))I am a bang((
	    id)I am a cloud(
	    id{{I am a hexagon}}
	    Default
```

_Resultado_

```
mindmap
	Formas
	    id[I am a square]
	    id(I am a rounded square)
	    id((I am a circle))
	    id))I am a bang((
	    id)I am a cloud(
	    id{{I am a hexagon}}
	    Default
```

<br>

</details>


## EMR diagrams

```mermaid
---

---
erDiagram


Escola {
    cnpj REAL
    endereco TEXT
		listaDepartamento TEXT
}

Aluno{
 		nome TEXT
    cpf TEXT
}

Diretor{
		nome text
		salario real
}

Departamento{
		listaFuncionarios TEXT
		Nome TEXT
		orcamento TEXT
		
}
Escola ||--|{ Diretor: temUm
Escola ||--|{ Aluno: possuiMuitos
Escola ||--|{ Departamento: temUm
```

## Flowchart

```mermaid
flowchart LR;
		Tipos_Sistemas_Operacionais ==> Uso_Pessoal & Uso_Empresarial;
    
		Uso_Pessoal --> Móvel & Desktop_Multiusuário & Embarcado;
		
		Uso_Empresarial --> Embarcado & Lote & Servidor & Distribuído & Tempo-real & Rede;
		
		Móvel --> iOS & Android;
		
		Desktop_Multiusuário --> Windows & MacOS;
		
		Embarcado --> Microondas & Satélite;
		
		Lote --> Sistema_Bancário & Sistema_Votação;
		
		Servidor --> Google;
		
		Distribuído --> TikTok & Netflix;
		
		Tempo-real --> GPS & Aviação;
		
		Rede --> Provedor_Internet & Starlink;
```


## Piechart

```mermaid


```

```mermaid
mindmap
	Formas
	    id[I am a square]
	    id(I am a rounded square)
	    id((I am a circle))
	    id))I am a bang((
	    id)I am a cloud(
	    id{{I am a hexagon}}
	    Default
```
