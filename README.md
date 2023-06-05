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


- Full name

Algoritmo FullName
	Escribir 'Ingrese su nombre: '
	Leer nombre
	Escribir 'Ingrese su apellido: '
	Leer apellido

	Escribir Mayusculas(Subcadena(nombre, 0, 0)) + Minusculas(Subcadena(nombre, 1, Longitud(nombre))) + ' ' + Mayusculas(Subcadena(apellido, 0, 0)) + Minusculas(Subcadena(apellido, 1, Longitud(apellido)))

FinAlgoritmo


- Throw dice

Algoritmo ThrowDice
	Para i = 1 Hasta 10 Con Paso 1
		dado1 = Aleatorio(1,6)
		dado2 = Aleatorio(1,6)

		si dado1 == dado2 Entonces
			Escribir dado1 ' ' dado2 ' los dados son iguales'
		SiNo
			Escribir dado1 ' ' dado2
		FinSi

	FinPara
FinAlgoritmo


- Distance to zero

Algoritmo DistanceToZero
	Imprimir 'Ingrese un nùmero: '
	Leer num

	Para i = 1 hasta 4 Con Paso 1 Hacer
		Imprimir 'Ingrese un nùmero: '
		Leer num2

		Si Abs(num2) > Abs(num) Entonces
			num = num2
		FinSi
	FinPara

	Imprimir Trunc(num)
FinAlgoritmo


- Toss coin

Algoritmo TossCoin
	Escribir 'Ingrese el primer nombre: '
	Leer nombre1
	Escribir 'Ingrese el primer valor: '
	Leer valor1

	Escribir 'Ingrese el segundo nombre: '
	Leer nombre2
	Escribir 'Ingrese el segundo valor: '
	Leer valor2

	Si valor1 <= 0 | valor2 <= 0 Entonces
		Si valor1 <= 0 & valor2 > 0 Entonces
			Escribir 'Jugador ganador: ' + Mayusculas(nombre2) + ' ' + ConvertirATexto(valor2)
		SiNo
			Si valor1 > 0 & valor2 <= 0 Entonces
				Escribir 'Jugador ganador: ' + Mayusculas(nombre1) + ' ' + ConvertirATexto(valor1)
			FinSi
		FinSi
	SiNo
		numGanador = Aleatorio(1, 2)
		Si numGanador == 1 Entonces
			Escribir 'Jugador ganador: ' + Mayusculas(nombre1) + ' ' + ConvertirATexto(valor1)
		SiNo
			Escribir 'Jugador ganador: ' + Mayusculas(nombre2) + ' ' + ConvertirATexto(valor2)
		FinSi
	FinSi
FinAlgoritmo


-Total price

Funcion RetornarprecioTotal <- precioTotal(precio, iva)
	RetornarprecioTotal = precio + (precio * (iva / 100))
	Si precio > 3000 Entonces
		RetornarprecioTotal = RetornarprecioTotal - (RetornarprecioTotal * 0.1)
	FinSi
FinFuncion

Algoritmo TotalPrice
	Escribir 'Ingrese el precio: '
	Leer precio
	Escribir 'Ingrese el iva: '
	Leer iva

	Imprimir precioTotal(precio, iva)
FinAlgoritmo


- Reverse direction and size

Funcion RetornaReverse <- ReverseDirectionAndSize(ar_texto)
	Definir Reverse_texto Como Caracter
	Definir Sub_texto Como Caracter
	Reverse_texto = ''
	Sub_texto = ''

	l_ar_texto = Longitud(ar_texto)
	Para i = l_ar_texto - 1 Hasta 0 Con Paso -1 Hacer
		Sub_texto = Subcadena(ar_texto, i, i)
		Si Sub_texto = Mayusculas(Sub_texto) Entonces
			Sub_texto = Minusculas(Sub_texto)
		SiNo
			Sub_texto = Mayusculas(Sub_texto)
		FinSi
		Reverse_texto = Reverse_texto + Sub_texto
	FinPara
	RetornaReverse = Reverse_texto
FinFuncion

Algoritmo reverse
	Imprimir 'Ingrese un texto: '
	Leer texto

	Imprimir ReverseDirectionAndSize(texto)

FinAlgoritmo


//Semana 5

- Time Converter

Funcion retornarTimeConverter <- timeConverter(ar_segundos)

	dias = Trunc(ar_segundos / 86400)
	horas = Trunc((ar_segundos - (dias * 86400)) / 3600)
	minutos = Trunc((ar_segundos - (dias * 86400) - (horas * 3600)) / 60)
	seg = ar_segundos - (dias * 86400) - (horas * 3600) - (minutos * 60)
	retornarTimeConverter = 'dìas: ' + ConvertirATexto(dias) + ', horas: ' + ConvertirATexto(horas) + ', minutos: ' + ConvertirATexto(minutos) + ' y segundos: ' + ConvertirATexto(seg)
FinFuncion

Algoritmo Converter
	Imprimir 'Ingrese los segundos: '
	Leer seg
	Imprimir timeConverter(seg)
FinAlgoritmo


- Compare distances

Funcion retornarCompareDistances <- compareDistances(ar_num1, ar_num2, ar_num3, ar_num4, ar_num5)
	Definir sumaPositivos Como Real
	Definir sumaNegativos Como Real
	sumaPositivos = 0
	sumaNegativos = 0

	Si ar_num1 > 0 Entonces
		sumaPositivos = sumaPositivos + ar_num1
	SiNo
		sumaNegativos = sumaNegativos + ar_num1
	FinSi

	Si ar_num2 > 0 Entonces
		sumaPositivos = sumaPositivos + ar_num2
	SiNo
		sumaNegativos = sumaNegativos + ar_num2
	FinSi

	Si ar_num3 > 0 Entonces
		sumaPositivos = sumaPositivos + ar_num3
	SiNo
		sumaNegativos = sumaNegativos + ar_num3
	FinSi

	Si ar_num4 > 0 Entonces
		sumaPositivos = sumaPositivos + ar_num4
	SiNo
		sumaNegativos = sumaNegativos + ar_num4
	FinSi

	Si ar_num5 > 0 Entonces
		sumaPositivos = sumaPositivos + ar_num5
	SiNo
		sumaNegativos = sumaNegativos + ar_num5
	FinSi

	distanciaPositivos = sumaPositivos - 0
	distanciaNegativos = Abs(sumaNegativos) - 0
	
	Si distanciaPositivos > distanciaNegativos
		retornarCompareDistances = Verdadero
	SiNo
		retornarCompareDistances = Falso
	FinSi
FinFuncion

Algoritmo Distances
	Imprimir 'Ingrese 5 nùmeros: '
	Leer num1
	Leer num2
	Leer num3
	Leer num4
	Leer num5

	Imprimir CompareDistances(num1, num2, num3, num4, num5)
FinAlgoritmo


- Sum of pairs

Funcion retornaSumOfPairs <- sumOfPairs()
	Definir sumatoria Como Entero
	sumatoria = 0

	Repetir
		Imprimir 'Ingrese un nùmero del 1 al 100: '
		Leer num

		Si (num % 2) = 0 & num >= 0 & num <= 100 Entonces
			sumatoria = sumatoria + num
			Imprimir sumatoria
		FinSi
	Mientras Que num >= 0 & num <= 100

	retornaSumOfPairs = sumatoria
FinFuncion

Algoritmo sumaPares
	Imprimir sumOfPairs()
FinAlgoritmo


- Mid point

Funcion retornaMidPoint <- midpoint(num1, num2)
	retornaMidPoint = (num1 + num2) / 2
FinFuncion

Algoritmo puntoMedio
	Imprimir 'Ingrese dos nùmeros: '
	Leer num1
	Leer num2
	
	Imprimir midpoint(num1, num2)
FinAlgoritmo


- Cashier

Funcion retornaSaldo <- Depositar(saldo)
	Imprimir '¿Cuànto quiere dèpositar?'
	Leer deposito
	retornaSaldo = saldo + deposito
FinFuncion

Funcion retornaRetiro <- Retirar(saldo)
	Imprimir '¿Cuànto quiere retirar?'
	Leer retiro
	retornaRetiro = saldo - retiro
FinFuncion

Funcion retornarSaldo <- Cajero()
	Definir saldo Como Real
	saldo = 1000

	Repetir
		Imprimir 'Seleccione una opciòn: '
		Imprimir 'a. depositar'
		Imprimir 'b. retirar'
		Imprimir 'c. salir'
		Leer opcionSel

		Segun opcionSel
			'a':
				saldo = Depositar(saldo)
			'b':
				saldo = Retirar(saldo)
			'c':
			De Otro Modo:
				Imprimir 'Opciòn no vàlida'
		FinSegun
	Mientras Que Minusculas(opcionSel) <> 'c'

	retornarSaldo = saldo
FinFuncion

Algoritmo caja
	Imprimir 'Saldo actual: ' + ConvertirATexto(cajero())
FinAlgoritmo


- Weather average

Funcion retornarGradoCelsius <- gradosCelsius(grado)
	retornarGradoCelsius = (grado - 32) / 1.8
FinFuncion

Algoritmo WeatherAverage
	Definir cont Como Entero
	cont = 0
	Definir sumatoria Como Real
	sumatoria = 0
	Definir opcionSel Como Caracter
	opcionSel = ''

	Repetir
		Imprimir 'Seleccione una opciòn: '
		Imprimir 'a. grados celsius'
		Imprimir 'b. grados fahrenheit'
		Imprimir 'x. salir'
		Leer opcionSel

		Segun opcionSel
			'a':
				cont = cont + 1
				Imprimir 'Ingrese el valor: '
				Leer grado

				sumatoria = sumatoria + grado
			'b':
				cont = cont + 1
				Imprimir 'Ingrese el valor: '
				Leer grado

				grado = gradosCelsius(grado)
				sumatoria = sumatoria + grado

			'x':
			De Otro Modo:
				Imprimir 'Opciòn no vàlida'
		FinSegun
	Mientras Que Minusculas(opcionSel) <> 'x'

	Si cont = 0 Entonces
		cont = 1
	FinSi
	Imprimir 'El resultado es: ' + ConvertirATexto(sumatoria / cont)
FinAlgoritmo


- IF

//Verifica si un nùmero es mayor o igual a otro nùmero

const num1 = 5;
const num2 = 10;

if (num1 >= num2){
    console.log(num1 + ' es mayor o igual a ' + num2)
}
else{
    console.log(num2 + ' es mayor a ' + num1)
};


- WHILE

//tabla de multiplicar

var i;
var j;

i = 1;
while (i <= 10) {
    j = 1;
    while (j <= 10){
        console.log(i + ' x ' + j + ' = ' + i * j);
        j++;
    }
    console.log('-----------');
    i++;
}


- FOR

//tabla de multiplicar

var i;
var j;

for (i = 1; i <= 10; i++){
    for (j = 1; j <= 10; j++){
        console.log(i + ' x ' + j + ' = ' + i * j);
    }
    console.log('-----------');
}


//Semana 6

- Variables

let firstname = 'Lata';


- What is x?

'Geeta'


- Several variables

let flower = 'rose';
let tree = 'maple';


- Reassignment

'Toe'


- Assign variables

'Hardy'


- Functions

function hello(){
   return 'Hello world!';
}


3.- Multiple functions

function a(){
   return 'Hello a!';
}

function b(){
   return 'Hello b!';
}


4.- Function calls

function greet(){
   return 'Haydo!';
}

let salutation = greet();


5.- What is x? (function version)

'How do you do?'


6.- Parameters

function echo(input){
   return input;
}

echo('Greta');
echo('CO2');


Week challenges (Thursday)
1.- Strings

function greet(name){
   return 'Hello ' + name + '!';
}


2.- String: length

function length(cadena){
   return cadena.length;
}


3.- String: toUpperCase()

function toCase(cadena){
   return cadena.toLowerCase() + '-' + cadena.toUpperCase();
}


4.- String: charAt()

function shortcut(cadena1, cadena2){
   return cadena1.charAt(0) + cadena2.charAt(0);
}


5.- String: indexOf()

function indexOfIgnoreCase(cadena1, cadena2){
   return cadena1.toLowerCase().indexOf(cadena2.toLowerCase());
}


- JavaScript - Week 7


- Week challenges (Monday)


1.- String: substr()

function firstWord(cadena){
   return cadena.substr(0, cadena.indexOf(' '));
};


2.- String: replace()

function normalize(fecha){
   return fecha.replace(/-/g, '/');
}


3.- Increment

Tiene un valor de 7

4.- Fahrenheit

function toFahrenheit(gCelsius){
   return (gCelsius * 9/5) + 32
};


5.- Boolean

function nand(valBool1, valBool2){
   if(valBool1 && valBool2){
      return false;
   }
   else{
      return true;
   };
};


- Week challenges (Tuesday)


2.- Objects

function animal(obj){
  return 'This ' + obj.color + ' ' + obj.name + ' has ' + obj.legs + ' legs.';
}


3.- Return to sanity

function mystery() {
  var results =
    {sanity: 'Hello'};
  return results;
}


4.- Object syntax debug

var rooms = {
  first: {
    description: 'This is the first room',
    items: {
      chair: 'The old chair looks comfortable',
      lamp: 'This lamp looks ancient'
    }
  },
  second: {
    description: 'This is the second room',
    items: {
      couch: 'This couch looks like it would hurt your back',
      table: 'On the table there is an unopened bottle of water'
    }
  }
}


- Week challenges (Wednesday)


1.- Count strings in objects

function strCount(obj){
  let count = 0
  for (key in obj){
    if (typeof obj[key] == 'string') count++;
    if (typeof obj[key] == 'object') count+= strCount(obj[key]);
  }

  return count
}


2.- Extending JavaScript Objects: Get First & Last Array Element

Array.prototype.first = function() {
    return this[0];
  };
  
  Array.prototype.last = function() {
    return this[this.length-1];
  };


3.- Object Oriented Piracy

function Ship(draft,crew) {
 this.draft = draft;
 this.crew = crew;

 this.isWorthIt = function(){
  if ((this.draft - (this.crew * 1.5)) > 20){
    return true;
  }
  else{
    return false;
  }
}
}


- Week challenges (Thursday)


1.- Convert a String to a Number!

const stringToNumber = function(str){
  return Number(str);
}


2.- Convert number to reversed array of digits

function digitize(n) {
  return String(n).split('').reverse().map(Number);
}


3.- Truthy and Falsy

const truthy = [1, '1', 'hola', ' ', true];
const falsy = [0, false, undefined, '', NaN];


4.- Training JS #4: Basic data types--Array

function getLength(arr){
  return arr.length;
}
function getFirst(arr){
  //return the first element of arr
  return arr[0];
}
function getLast(arr){
  //return the last element of arr
  return arr[arr.length - 1];
}
function pushElement(arr){
  var el=1;
  arr.push(el);
  return arr;
}
function popElement(arr){
  //pop an element from arr
  arr.pop();
  return arr;
}


- Javascript - Week 8


- Week challenges (Monday)


1.- Training JS #7: if..else and ternary operator!

function saleHotdogs(n){
  return n < 5? n * 100 : (n >= 5 && n < 10) ? n * 95 : n * 90;
}


2.- Training JS #8: Conditional statement--switch

function howManydays(month){
  var days;
  switch (month){
    case 1:
       days = 31;
       break;
    case 3:
       days = 31;
       break;
    case 5:
       days = 31;
       break;
    case 7:
       days = 31;
       break;
    case 8:
       days = 31;
       break;
    case 10:
       days = 31;
       break;
    case 12:
       days = 31;
       break;
    case 4:
       days = 30;
       break;
    case 6:
       days = 30;
       break;
    case 9:
       days = 30;
       break;
    case 11:
       days = 30;
       break;
    case 2:
       days = 28;
       break;
  }
  return days;
}


3.- Basic Calculator

function calculate(num1, operation, num2) {
  if( !(typeof num1 === 'number') && !(typeof num2 === 'number') ){
    return null;
  }

  switch (operation){
    case '+':
      return num1 + num2;
      break;
    case '-':
      return num1 - num2;
      break;
    case '*':
      return num1 * num2;
      break;
    case '/':
      if(num2 === 0 ){
        return null;
      }
      else{
        return num1 / num2;
      }
      break;
    default:
      return null;
  }
}


- Week challenges (Tuesday)


1.- Even or odd

function evenOrOdd(number) {
  return number % 2 === 0 ? 'Even' : 'Odd';
}


2.- A wolf in sheep's clothing

function warnTheSheep(queue) {
  if(queue[queue.length - 1] === 'wolf'){
    return "Pls go away and stop eating my sheep";
  }
  else
    var posicion = queue.length - queue.indexOf('wolf') - 1
    return "Oi! Sheep number " + posicion + "! You are about to be eaten by a wolf!"
}


3.- Decode the morse code

decodeMorse = function(morseCode){
  // Your code here
  // You can use MORSE_CODE[morse]
  let nMorseCode = morseCode.trim();
  let codes = morseCode.split('   ');
  let letras = []
  let frase = []

  for(let i = 0; i < codes.length; i++){
    letras = codes[i].split(' ');
    for (let j = 0; j < letras.length; j++) {
      letras[j] = MORSE_CODE[letras[j]];
    }
    frase.push(letras.join(''));
  }
  return frase.join(' ').trim();
};


- Week challenges (Wednesday)


1.- Who likes it?

function likes(names) {
  switch (names.length){
    case 0:
      return 'no one likes this';
      break;
    case 1:
      return names[0] + ' likes this';
      break;
    case 2:
      return names[0] + ' and ' + names[1] + ' like this';
      break;
    case 3:
      return names[0] + ', ' + names[1] + ' and ' + names[2] + ' like this';
      break;
    default:
      return (names[0] + ', ' + names[1] + ' and ' + (names.length - 2) + ' others like this');
      break;
  }
}


2.- Bit counting

var countBits = function (n) {
  let binaryNumber = n.toString(2);
  let oneBitCount = 0;
  for (let i = 0; i < binaryNumber.length; i++) {
    if (binaryNumber[i] === '1') oneBitCount++;
  }
  return oneBitCount;
};


3.- Your order, please

function order(words){
  const palabras = words.split(' ');
  var words2 = words.split(' ');
  var index = 0;
  var palabra;

  for(let i = 0; i < palabras.length; i++){
    palabra = palabras[i];

    for(let j = 0; j < palabra.length; j++){
      index = Number(palabra[j]);

      if(index > 0){
          words2.splice(index - 1, 1, palabras[i]);
        }
    }
  }
    return String(words2).replace(/,/g," ");
}


- Week challenges (Thursday)


1.- Counting duplicates

function duplicateCount(text){
  let cont = 0;
  text = text.toLowerCase(); // todo minuscula

  for(let i = 0; i < text.length; i++){
    if(text.indexOf(text[i]) !== text.lastIndexOf(text[i])){
      cont++;
      text = text.replace(new RegExp(text[i], 'g'), '');
      i = i - 1;
    }
  }
  return cont;
}


2.- Encrypt this!

