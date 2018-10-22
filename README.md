# Estructuras
#Notas para compilar y ejecutar el programa en CMD Windows:

#88110e -o archivo.bin archivo.ens --> Ejecuta archivo.ens; archivo.bin nos sirve para ver la info del programa
#	mc88110 archivo.bin --> Muestra info sobre archivo.bin con los registros y valores
#		·1ª linea tiene los datos del programa al inicio.
#		·FL=1 --> Little Endian (0-->Big Endian)
#		·FC --> Acarreo
#		·FV --> OverFlow
		
#		Comandos: al introducir valores "a pelo", los convierte a hexadecimal (20->14, 0x20 introduce un 20) 
#			>INTRO --> Ejecuta el ultimo comando
#			>h --> Muestra las opciones de comandos
#			>r --> Cambia el valor inicial de un registro. No se puede cambiar el PC más que con ejecución de instrucciones
#			>d -->	Muestra las direcciones de las instrucciones en el rango (o desde si solo se pone un valor) especificado. La dirección 0 es la 1ª instr. d 0 2 --> Muestra 2 instrucciones desde la dirección 0.
#			>e --> Ejecuta el programa y muestra la info de registros y valores al terminar.
#			>v --> Muestra el numero de palabras desde la dirección que se especifique. v 0 4 --> muestra 4 palabras desde la direccion 0.
#			>t --> Ejecuta el numero de instrucciones que se pasen (1 si no se especifica)
#			>i --> Introduce un valor en la direccion especificada. i 16 20 --> introduce un 20 en la direccion 16
#			>l --> Activa o desactiva el fichero de traza
#			>c --> Muestra la configuración
