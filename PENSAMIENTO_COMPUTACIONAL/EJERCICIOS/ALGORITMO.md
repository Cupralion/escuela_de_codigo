# REALIZA UN ALGORITMO SOBRE ALGUNA ACTIVIDAD EN TU VIDA COTIDIANA.
# Mantenimiento a Cadena de Motocicleta F800R
1.- Inicio

2.- Declarar Materiales a Utilizar (Grasa liquida, llave española 13, Dado 1" entrada 3/4, Maneral, Torquimetro, Desengrasante, Trapo)

3.- Coloca la motocicleta sobre el caballete central

4.- Gira con la mano la llanta para que la cadena se mueva y aplica desengrasante

5.- Con un trapo limpia el desengrasante y retira la suciedad hasta dejar la cadena limpia

6.- Una vez mas gira la llanta y aplica grasa liquida

7.- Con un trapo limpio retira el exedente de grasa

8.- Baja la motocicleta del caballete central y coloca el parador lateral

9.- Con el maneral y el dado de 1" afloja la tuerca del eje trasero

10.- Con la llave española 13 afloja los tensores de cadena que se ubican a un costado del bastidor

11.- Con la llave española 13  ajusta los 2 tensores hasta que la cadena tenga una holgura entre 20 y 30 mm

12.- Revisar que los 2 tensores esten alineados entre si

13.- Una vez que los tensores esten alineados aseguralos con la llave española 13

14.- Con el maneral y el dado de 1" aprieta al llegue la tuerca del eje trasero

15.- Con el torquimetro y el dado de 1" aprieta la tuerca a 90Nm

16.- Fin







# DESARROLLA UN ALGORITMO QUE CALCULE LA EDAD DE UNA PERSONA CON BASE A LA OBTENCION DE SU FECHA DE NACIMIENTO.

# Calculo tu Fecha de Nacimiento
1.- Inicio

2.- Declarar Fechas (Fecha Actual, Fecha de Nacimiento, edad)

3.- Revisar mes de nacimiento (si el mes de nacimiento ya paso al actual no se suma nada a la resta del año, si el mes no a pasado se tiene que restar un año a la resta de los años, si el mes es igual al actual se tiene que validar el día)

4.- Ingresa tu mes de nacimiento

5.- El mes de nacimiento es menor al actual  (respuesta si (rev mes = 0) y continuar a paso (12), respuesta no = seguir siguiente paso)

6.- El mes de nacimiento es mayor al actual (respuesta si (rev mes = 1) y continuar al paso (12), respuesta no = seguir siguiente paso)

7.- El mes de nacimiento es igual al actual (respuesta si = validar día de nacimiento seguir siguiente paso)

8.- El día de nacimiento es menor al actual  (respuesta si (rev mes = 0) y continuar a paso (12), respuesta no = seguir siguiente paso)

9.- El día de nacimiento es mayor al actual (respuesta si (rev mes = 1) y continuar al paso (12), respuesta no = seguir siguiente paso)

10.- El día de nacimiento es igual al actual (respuesta si (rev mes = 0)  "Feliz cumpleaños")

11.- Ingresa el año de Nacimiento

12.- (Año Actual - Año de nacimiento)  - (rev mes)

13.- Mostrar Edad Actual

14.- Fin


 
# Realice un algoritmo que resuelva la siguiente situación: un producto tenía un precio inicial que debe solicitarse y ahora tiene un nuevo valor, mayor, que también deberá pedirse, determine el porcentaje de incremento del producto. 

1.- Inicio

2.- Declarar (Producto, Precio Inicial = X, Precio Nuevo = Y, Porcentaje de Incremento)

3.- Cual es el Precio Inicial

4.- Cual es el precio Nuevo

5.- ((Y * 100) / X ) - 100

6.- Muestre el porcentaje de Incremento

7.- Fin


Resolución en clase

1.- Inicio

2.- Declarar (precio_inicial,precio_final,incremento,porcentaje)float

3.- mostrar("dame el precio inicial")

4.- asignar(precioInicial)

5.- mostrar("dame el precio final")

6.- asignar(precioFinal)

7.- incremento=precioFinal-precioInicial

8.- porcentaje=(incremento*100)/precioInicial

9.- mostrar("el incremento fue de ",porcentaje)

10.- Fin




Comentarios:

En asignar las variables estos son los tipos que se puedem usar
precio_final o precioFinal



Algoritmo de ejercicio en PSeInt echo por mi

# Pedir su nombre y sacar el promedio de sus calificaciones

1.- Inicio

2.- Declarar (nombre,calificacion1,calificacion2,calificacion3,calificacion4,promedio)float

3.- mostrar("dame tu nombre")

4.- asignar(nombre)

5.- mostrar("dame tu calificación 1")

6.- asignar(calificacion1)

7.- mostrar("dame tu calificación 2")

8.- asignar(calificacion2)

9.- mostrar("dame tu calificación 3")

10.- asignar(calificacion3)

11.- mostrar("dame tu calificación 4")

12.- asignar(calificacion4)

13.- promedio=(calificacion1+calificacion2+calificacion3+calificacion4)/4

14.- mostrar("Hola" nombre "tu promedio es de " promedio)

15.- Fin

PSeInt

Algoritmo Promedio
	calificación1<-0
	calificación2<-0
	calificación3<-0
	calificación4<-0
	prom<-0
	Escribir " Hola, cual es tu nombre "
	Leer nombre
	Escribir " Cual es tu primer calificación "
	Leer calificación1
	Escribir " Cual es tu segunda calificación "
	Leer calificación2
	Escribir " Cual es tu tercer calificación "
	Leer calificación3
	Escribir " Cual es tu cuarta calificación "
	Leer calificación4
	prom<-(calificación1+calificación2+calificación3+calificación4)/4
	Escribir nombre," tu promedio es de ",prom
	Escribir " ADIOS"
	FinAlgoritmo


Resolución en grupo

1.- Inicio

2.- Declarar (nombre)string
    (cal1,cal2,cal3,cal4,promedio)float
    
3.- mostrar("ingresa el nombre del alumno")

4.- asignar(nombre)

5.- mostrar("ingresa la primera calificación")

6.- asignar(cal1)

7.- mostrar("ingresa la segunda calificación")

8.- asignar(cal2)

9.- mostrar("ingresa la tercera calificación")

10.- asignar(cal3)

11.- mostrar("ingresa la cuarta calificación")

12.- asignar(cal4)

13.- promedio=(cal1+cal2+cal3+cal4)/4

14.- mostrar("Hola" nombre "tu promedio es de " promedio)

15.- Fin


# Determinar si una persona es mayor a otras 2

1.- Inicio

2.- Declarar (persona1,persona2,persona3)int
    (diferencia)logico

3.- Mostrar("Dame tu edad")

4.- asignar(persona1)

5.- Mostrar("Dame la edad de la persona que esta a tu lado derecho")

6.- asignar(persona2)

7.- Mostrar("Dame la edad de la persona que esta a tu lado izquierdo")

8.- asignar(persona3)

9.- diferencia=((persona1>persona2) Y (persona1>persona3))

10.- mostrar("Es mayor a las otras 2 personas" diferencia)

11.- Fin


PSeInt

Algoritmo Edad

	pers1<-0
	
	pers2<-0
	
	pers3<-0
	
	dif<-0
	
	Escribir "Dame tu edad"
	
	Leer pers1
	
	Escribir "Dame la edad de la persona que esta a tu derecha"
	
	Leer pers2
	
	Escribir "Dame la edad de la persona que esta a tu izquierda"
	
	Leer pers3
	
	si(pers1>pers2)Y(pers1>pers3) Entonces
	
		Escribir "Eres Mayor que tus dos compañeros"
		
	SiNo
	
		Escribir"No eres Mayor que tus Compañeros"
	
	FinSi
	
FinAlgoritmo


![image](https://user-images.githubusercontent.com/104279605/166835815-f7f841dc-495c-47a6-af7c-8c64a0ea2ad3.png)

