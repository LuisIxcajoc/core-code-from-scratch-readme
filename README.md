# core-code-from-scratch-readme

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
