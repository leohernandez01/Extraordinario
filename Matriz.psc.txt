Algoritmo Matriz
		Leer nFilas
		Leer nColumnas
		
		contador = 1
		
		linea = ""
		Para i = 1 Hasta nFilas Hacer
			linea = ""
			
			Si i mod 2 = 0 Entonces
				
				contador = contador + nColumnas - 1
				
				Para j = 1 Hasta nColumnas Hacer
					linea = linea + " " + ConvertirATexto(contador)
					
					contador = contador - 1
				Finpara
				contador = contador + nColumnas + 1
				
			SiNo
				Para j = 1 Hasta nColumnas Hacer
					linea = linea + " " + ConvertirATexto(contador)
				
					contador = contador + 1
				Finpara
				
			FinSi
			Escribir linea
			linea = ""	
		FinPara
FinAlgoritmo