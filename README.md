# core-code-from-scratch-readme
//Semana 1
1. Pizza
    -Comprar harina para pizza, tomate, etc. (Ingredientes)
    -Hacer salsa de tomate
    -Hacer la masa con la haria de pizza
    -cocer la masa
    -Agregar todos los ingredientes y hornear
    -Cuando termine de hornearse, la pizza ya estarà listo

2. Hot N Cold
    -Definir temperatura y si es Celsius o Fahrenheit
    -Si la temperatura indicada es Celsius entonces convertirlo a Fahrenheit
    -tomar la temperatura multiplicarlo por 1.8
    -Del resultado anterior sumarlo 32 para obtener la temperatura en Fahrenheit
    -Si la temperatura indicada es en Fahrenheit entonces convertirlo a Celsius
    -tomar la temperatura dividirlo por 1.8 para obtener la temperatura en Celsius

3. Geometry
    -Indicar si es una piràmide, cubo o esfera
    -Si es piràmide obtener informaciòn del radio y altura de la piràmide
    -Aplicar la fòrmula (1/3)x pi x radio al cuadrado x altura, para obtener el volumèn de la piràmide
    -Si es un cubo obtener el tamaño de uno de sus lados
    -Aplicar la formula lado x lado x lado, para obtener el volumèn del cubo
    -Si es una esfera obtener informaciòn del radio.
    -Aplicar la fòrmula de (4/3) x pi x radio x radio x radio

4. Numbers

https://github.com/LuisIxcajoc/core-code-from-scratch-readme/blob/c48c27c5261ea3c5322b54146385f19565c9ecae/numParImpar.png

5. Date of birth
    -Obtener la fecha de nacimiento
    -Años = Restar año actual - año fecha nacimiento
    -Si nùmero de mes actual es mayor al mes de fecha de nacimiento entonces Años = Años
    -Si no entonces Años = Años - 1
    -Su edad es Años

6. Treasures
    Anàlisis:
    1 habitaciòn
    3 cofres
    Al menos 1 tesoro en cofre
    1 mensaje en cada cofre, todos son falsos

    Mensajes
    Falso                                                     Verdadero
    Cofre izquierdo: El cofre del medio tiene un tesoro.      //El cofre del medio no tiene un tesoro
    Cofre medio: Todos estos cofres tienen tesoros en ellos   //No todos estos cofres tienen tesoros en ellos
    Cofre derecho: Solo uno de estos cofres tiene tesoros.    //Hay màs de un cofre que tiene tesoros

    Conclusiòn:
    El cofre de medio no tiene tesoro
    Hay màs de un cofe con tesoros, son tres cofres, el del medio no tiene tesoro, entonces los cofres restantes contienen tesoros
    
    ¿Qué cofres tienen tesoros?
    Cofre izquierdo y cofre derecho


//Semana 2
7. Logic problem

Analìsis:
5 Estudiantes

Alice: "Nadie estudió matemáticas ayer".               //Los 5 estudiantes no estudiaron matemàticas
Bob: "1 persona estudió matemáticas ayer".             //4 estudiantes no estudiaron matemàticas
Charlie: "2 personas estudiaron matemáticas ayer".     //3 estudiantes no estudiaron matemàticas
Dan: "3 personas estudiaron matemáticas ayer".         //2 estudiantes no estudiaron matemàticas
Eva: "Ayer estudiaron matemáticas 4 personas".         //1 estudiante no estudiò matemàticas

El maestro sabe que solo los que estudiaron estarían diciendo la verdad y los que no, estarían mintiendo. quien esta diciendo la verdad?

Respuesta: Bob dice la verdad


8. Cereal vrs Milk
//Pseudocòdigo
Inicio pseudocòdigo PreparaTazon
Obtener cereal
Obtener leche
Obtener tazòn
Colocar cereal en el tazòn
Colocar la leche en el tazòn
Mezclar
fin

//diagrama de flujo
https://github.com/LuisIxcajoc/core-code-from-scratch-readme/blob/a67f06534e22cb6cbc4129039f00cf79141a5c0a/PraparaTazon.JPG

9. Algorithm game
https://github.com/LuisIxcajoc/core-code-from-scratch-readme/blob/47f8abc71f8f13675aaa9e0447749ac8d70ab72c/Algorithmgame.JPG

10. Mod
Algoritmo numParImpar
	Definir num Como Real
	Escribir 'Ingrese número'
	Leer num
	residuo <- num % 2
	Si residuo = 0 Entonces
		Escribir 'El nùmero es par'
	SiNo
		Escribir 'El nùmero es impar'
	FinSi
FinAlgoritmo

11. Register form
Algoritmo Formulario
	Definir nombre, apellido, edad, correo, direccion Como Caracter

	Escribir 'Ingrese su nombre: '
	Leer nombre

	Escribir 'Ingrese su apellido: '
	Leer apellido

	Escribir 'Ingrese su edad: '
	Leer edad

	Escribir 'Ingrese su correo electrònico: '
	Leer correo

	Escribir 'Ingrese su direcciòn: '
	Leer direccion

	Imprimir 'Nombre: ' + nombre
	Imprimir 'Apellido: ' + apellido
	Imprimir 'edad: ' + edad
	Imprimir 'Correo electrònico: ' + correo
	Imprimir 'direccion: ' + direccion

FinAlgoritmo


12. Truth tables

T & T = T                            ✅
T & F = F                            ✅
F & T = T                            ❌
F & F = F                            ✅
T | T = T                            ✅
T | F = F                            ❌
F | T = T                            ✅
F | F = F                            ✅
~T = T                               ❌
~F = T                               ✅
(T & F) | (~F) = T                   ✅
(T | F ) & (F | F) = T               ❌
~((T | F ) & (F | F)) & F = T        ❌
~((T | F ) & (F | F)) & T = F        ❌


13. Boolean results

Algoritmo boolean
	a <- 5 == 3
	//Compara 5 con 3, el resultado de a es falso debido a que 5 no es igual a 3
	b <- 4 <> 3
	//b es verdadero debido a que 4 es distinto a 3
	c <- 7 > 7
	//c es falso debido a que 7 no es mayor a 7
	d <- 4 < 4
	//d es falso debido a que 4 no es menor a 4
	e <- 100 <= 90
	//e es falso debido a que 100 no es menor o igual a 90
	f <- 40 >= 40
	//f es verdadero debido a que 40 es mayor o igual a 40
FinAlgoritmo


14. Identify odd and even numbers

Algoritmo numParImpar
	Definir num Como Real
	Escribir 'Ingrese número'
	Leer num

	residuo <- num % 2
	Si residuo = 0
		Entonces Escribir 'El nùmero: ' + ConvertirATexto(num) + ' es par'
	SiNo Escribir 'El nùmero: ' + ConvertirATexto(num) + ' es impar'
		FinSi
FinAlgoritmo


//Semana 3
- Simple calculator

Algoritmo calculadoraSensilla
	Escribir 'Ingrese dos números: '
	Leer num1, num2
	
	Escribir 'Ingrese operación a realizar (+, -, *, /): '
	Leer operacion

	Si operacion == '+' | operacion == '-' | operacion == '*' | operacion == '/' Entonces
		Si operacion == '+' Entonces
			Imprimir ConvertirATexto(num1) + ' + ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 + num2
		SiNo
			Si operacion == '-' Entonces
				Imprimir ConvertirATexto(num1) + ' - ' + ConvertirATexto(num2) + ' ='
				Imprimir  num1 - num2
			SiNo
				Si operacion == '*' Entonces
					Imprimir ConvertirATexto(num1) + ' * ' + ConvertirATexto(num2) + ' ='
					Imprimir  num1 * num2
				SiNo
					Si operacion == '/' Entonces
						Imprimir ConvertirATexto(num1) + ' / ' + ConvertirATexto(num2) + ' ='
						Imprimir  num1 / num2
					SiNo
						Imprimir 'Opción no válida'
					FinSi
					
				FinSi
			FinSi
		FinSi
	FinSi
FinAlgoritmo


- Special number

Algoritmo specialNumber
	Escribir 'Ingrese número: '
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'
	SiNo
		Si n < 1000 & n <> 100 & (n % 10 == 0) Entonces
			Imprimir 'This number is almost special'
		SiNo
			Imprimir 'Just a regular number'
		FinSi
	FinSi
	//Si n % 10 == 0 Entonces
		//Imprimir 'This number is multiple of 10'
	//FinSi
FinAlgoritmo


- Simple calculator with Switch

Algoritmo calculadoraSensilla
	Escribir 'Ingrese dos números: '
	Leer num1, num2

	Escribir 'Ingrese operación a realizar (+, -, *, /): '
	Leer operacion
	
	Segun operacion Hacer
		'+':
			Imprimir ConvertirATexto(num1) + ' + ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 + num2
		'-':
			Imprimir ConvertirATexto(num1) + ' - ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 - num2
		'*':
			Imprimir ConvertirATexto(num1) + ' * ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 * num2
		'/':
			Imprimir ConvertirATexto(num1) + ' / ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 / num2
		De Otro Modo:
			Imprimir 'Opción no válida'
	FinSegun
FinAlgoritmo


-Multi Option Program

Algoritmo calculadoraSensilla

	Escribir 'Seleccione una opciòn ingresando el nùmero: '
	Escribir '1. Suma dos nùmeros: '
	Escribir '2. Imprimir el dìa de la semana: '
	Escribir '3. Imprimir la longitud de un texto: '
	Leer operacion

	Segun operacion Hacer
		'1':
			Imprimir 'Ingrese dos nùmero para realizar la suma: '
			Leer num1
			Leer num2
			Imprimir 'Suma de ' + ConvertirATexto(num1) + ' + ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 + num2
		'2':
			Imprimir 'Ingrese un dìa de la semana'
			Leer numeroDia
			Segun numeroDia Hacer
				'1':
					Imprimir 'Lunes'
				'2':
					Imprimir 'Martes'
				'3':
					Imprimir 'Mièrcoles'
				'4':
					Imprimir 'Jueves'
				'5':
					Imprimir 'Viernes'
				'6':
					Imprimir 'Sàbado'
				'7':
					Imprimir 'Domingo'
				De Otro Modo:
					Imprimir 'Opciòn no vàlida'
			FinSegun
		'3':
			Imprimir 'Ingrese un texto para calcular su longitud'
			Leer texto
			Imprimir 'La longitud de ' + texto + ' es: ' + ConvertirATexto(Longitud(texto))
		De Otro Modo:
			Imprimir 'Opción no válida'
	FinSegun
FinAlgoritmo


- Multiplication Tables

Algoritmo tablaMultiplicar
	Definir  i Como Entero
	Escribir 'Ingrese nùmero a generar tabla de multiplicar: '
	Leer num
	i = 1

	Mientras i <= 10 Hacer
		Imprimir ConvertirATexto(num) + ' x ' + ConvertirATexto(i) + ' = ' num * i
		i = i + 1
	FinMientras
FinAlgoritmo


- Simple calculator with Do While

Algoritmo calculadoraSensilladowhile
	Repetir
	Escribir 'Ingrese dos números: '
	Leer num1, num2

	Escribir 'Ingrese operación a realizar (+, -, *, /): '
	Leer operacion
	
	Si operacion == '+' | operacion == '-' | operacion == '*' | operacion == '/' Entonces
		Si operacion == '+' Entonces
			Imprimir ConvertirATexto(num1) + ' + ' + ConvertirATexto(num2) + ' ='
			Imprimir  num1 + num2
		SiNo
			Si operacion == '-' Entonces
				Imprimir ConvertirATexto(num1) + ' - ' + ConvertirATexto(num2) + ' ='
				Imprimir  num1 - num2
			SiNo
				Si operacion == '*' Entonces
					Imprimir ConvertirATexto(num1) + ' * ' + ConvertirATexto(num2) + ' ='
					Imprimir  num1 * num2
				SiNo
					Si operacion == '/' Entonces
						Imprimir ConvertirATexto(num1) + ' / ' + ConvertirATexto(num2) + ' ='
						Imprimir  num1 / num2
					SiNo
						Imprimir 'Opción no válida'
					FinSi
					
				FinSi
			FinSi
		FinSi
	FinSi

	Imprimir '¿Desean continuar (S)?: '
	Leer opcion
	Mientras Que opcion = 'S' | opcion = 's'
FinAlgoritmo


- Multiplication Tables with For

Algoritmo tablaMultiplicar
	Definir i Como Entero
	Escribir 'Ingrese nùmero a generar tabla de multiplicar: '
	Leer num

	Para i = 1 Hasta 10 Con Paso 1 Hacer
		Imprimir ConvertirATexto(num) + ' x ' + ConvertirATexto(i) + ' = ' num * i
	FinPara
FinAlgoritmo


- Ascending and Descending Numbers

Algoritmo ordenar
	Imprimir 'Ingrese un número: '
	Leer num

	imprimir 'Selecciones una opción'
	Imprimir '1. Orden ascendente'
	Imprimir '2. Orden descendente'
	Leer opcion

	si opcion == 1 Entonces
		Para i = 0 Hasta num Con Paso 1 Hacer
			Imprimir i
		FinPara
	SiNo
		si opcion == 2 Entonces
			Para i = num Hasta 0 Con Paso -1 Hacer
				Imprimir i
			FinPara
		FinSi
	FinSi

FinAlgoritmo


- Greetings

Algoritmo saludar
	Definir contadorSaludos Como Entero
	contadorSaludos = 0

	Repetir
	Imprimir 'Ingrese una hora: '
	Leer hora

	si hora >= 0 & hora <= 12 Entonces
		Imprimir 'Buenos días'
		contadorSaludos = contadorSaludos + 1
	FinSi

	si hora >= 13 & hora <= 18 Entonces
		Imprimir 'Buenas tardes'
		contadorSaludos = contadorSaludos + 1
	FinSi

	si hora >= 19 & hora <= 23 Entonces
		Imprimir 'Buenas noches'
		contadorSaludos = contadorSaludos + 1
	FinSi

	Imprimir '¿Desea continuar (s = Si)?'
	Leer opcion
	Mientras Que opcion = 's' | opcion = 'S'

	Imprimir 'Cantidad de saludos: ' contadorSaludos
FinAlgoritmo


- Pseudocode - Week 4

- Average sales and commission

Algoritmo comision
	Definir TotalValorVenta Como Real
	TotalValorVenta = 0

	Escribir 'Ingrese el nùmero de ventas: '
	Leer numVentas

	Para i = 1 Hasta numVentas Con Paso 1 Hacer
		Imprimir 'Ingrese el valor de la venta ' + ConvertirATexto(i) + ' :'
		Leer valorVenta
		TotalValorVenta = TotalValorVenta + valorVenta
	FinPara

	Imprimir 'Valor promedio de las ventas = ' + ConvertirATexto(TotalValorVenta / numVentas)
	si numVentas > 5 Entonces
		Imprimir 'La comisiòn del 15% es: ' + ConvertirATexto(TotalValorVenta * 0.15)
	SiNo
		Imprimir 'La comisiòn del 10% es: ' + ConvertirATexto(TotalValorVenta * 0.10)
	FinSi
FinAlgoritmo


- Even or odd

Algoritmo numeros

	Repetir
		Imprimir 'Ingrese un nùmero entre el 1 al 50: '
		Leer num
		si num < 1 | num > 50 Entonces
			Imprimir '-Error- nùmero invàlido'
		FinSi
	Mientras Que num < 1 | num > 50
	
	par = num % 2 = 0
	Para i = 1 Hasta num Con Paso 1 Hacer
		si i % 2 = 0 & par Entonces
			Imprimir i
		FinSi
		si i % 2 = 1 & ~(par) Entonces
			Imprimir i
		FinSi
	FinPara
FinAlgoritmo
