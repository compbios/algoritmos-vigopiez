Algoritmo Volumen_area_cilindro

	//Inicio definiendo las variables
	
	Definir radio, cilindro Como Entero
	
	//Escriba los valores de las variables
	
	Escribir "Escribe el radio del cilindro"
	
	Leer radio
	Escribir "Escribe la altura del cilidro"
	Leer altura
	
	Volumen = 3.1416 * (radio *radio) * altura
	Area = 2 * 3.1416 * radio * (radio + altura)  
	
	//Imprima los resultados	
	Escribir "el volumen es ", Volumen
	Escribir "el area es ", Area 
	
	FinAlgoritmo
