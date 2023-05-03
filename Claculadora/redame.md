
Algoritmo calculadora
	Escribir "Ingrese un numero"
	leer num1
	
Escribir "Ingrese el segundo numero"
	leer num2
	
	Escribir "Ingrese una operacion valida : +, -, *, /"
	leer signo
	
	si signo == "+" Entonces
		resultado = num1 + num2
		Escribir resultado
	FinSi
	
	si signo == "-" Entonces
		resultado = num1 - num2
		Escribir resultado
	FinSi
	
	si signo == "*"
		resultado = num1 * num2
		Escribir resultado
	FinSi
	
	si signo == "/"
		resultado = num1 / num2
		Escribir resultado
	FinSi 
	
	si signo <> "+" & signo <> "-" & signo <> "*" & signo <> "/" Entonces
		Escribir "La operacion es invalida"
		
	FinSi

	
	
FinAlgoritmo
