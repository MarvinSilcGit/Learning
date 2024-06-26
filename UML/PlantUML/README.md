# PlantUML Sintax

## EMR

```plantuml
@startuml
entity "Aluno"
{

* nome: text
* cpf: text

}

entity "Escola"
{
* cnpj
}

entity "Departamento"
{
* orcamento: real
* diretor: text
}

entity "Diretor"
{
* nome: text
* salario: real
}

Aluno }|-- Escola
Diretor ||-- Escola
Departamento }|-- Escola
@enduml
```

## Repeat Loop

```plantuml
@startuml
start
floating note right: Início

partition declaraçãoVariáveis{
	:**salário** é igual a 2500;
	:**porcentagemAumento** é igual a 15;
	:**aumento** é igual a **salário** / 100 * 15;
}

partition repetição{
repeat: salário igual a 2500?;
	:**salario** acrescenta **aumento**;
	:**print**(aumento);
	:**print**(salario);
	backward: voltar ao começo;
	repeat while (**Salário** é diferente de 2500?) is (Não)
->Sim;
}

end
floating note left: Fim
@enduml
```

## While Loop

### With backward function

```plantuml
@startuml
start
floating note left: Início
partition declaraçãoVariáveis{
	:**salário** é igual a 2500;
	:**porcentagemAumento** é igual a 15;
	:**aumento** é igual a **salário** / 100 * 15;
}
partition repetição{
while (**salário** é igual ou menor que 2500) is (Sim)
	:**salario** acrescenta **aumento**;
	:**print**(aumento);
	:**print**(salario);
	
backward: Recomeçar;
endwhile (Não)
}
end
floating note right: Fim
@enduml
```

### Without backward function

```plantuml
@startuml
start
floating note left: Início

partition declaraçãoVariáveis{
	:**a** é igual a 0;
}
partition repetição{

while (**a** diferente de 10?) is (Sim)

	:**a** acrescenta 1;
	
	if (**a** igual a 10?) then (Sim)
		
		:print("O contador funciona");
		break
	
	else (Não)
	
	endif
	
endwhile (Não)
}
end
floating note right: Fim
@enduml
```

## Conditions

### If (floating notes included)

```plantuml
@startuml
start
floating note left: Início
partition declaraçãoVariáveis{
	:**salário** é igual a 2500;
	:**porcentagemAumento** é igual a 15;
	:**aumento** é igual a **salário** / 100 * 15;
	
}
partition testeCondicional{
if (**salário** é igual a 2500?) then (Sim)
		
	:**salario** acrescenta **aumento**;
	:**print**(aumento);
	:**print**(salario);
else (Não)

	:print("Erro fatal");
	
endif
}

end
floating note right: Fim
@enduml
```

### Elseif (vertical mode on)

```plantuml
@startuml
!pragma useVerticalIf on
start
partition declaraçãoVariáveis{
:**valor1** é igual a 50;
:**valor2** é igual a 30;
}
if (**valor1** > **valor2**) then (**Sim**)

	:print(O valor 50 é maior que o valor 30);
	
(**Não**) elseif (**valor1** < **valor2**) then (**Sim**)
	
	:print(O valor 50 é menor que o valor 30);
	
(**Não**) elseif (**valor1** == valor2) then (**Sim**)
	:print("O valor 50 é igual ao valor 30");

else (**Não**)

endif

end
@enduml
```
