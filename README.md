# Curso profesional de python con platzi 
En este repositorio encontraremos todos los archivos que se generen en el transcurso del curso y algunos consejos practicos 
veamos por qué deeriamos escoer python como lenguaje de programación:
* tiene una de las mas grandes comunidades de desarrollo
* tiene una sintaxis bastante legible
* es facil de aprender
 
#### Turtle
turtle es un modulo de python que nos sirve para generar programas graficos y es una forma sencilla de ver y dar insrucciones. 

#### Operadores en python
* Operadores aritméticos
* Operadores Lógicos
* Operadores comparativos

#### Orden de las operaciones
* PEMDAS
* Parentesis
* Exponentes
* Multiplicación
* Division
* Adicion
* Sustracción

#### Funciones en python
son una secuencia de comandos que se pueden ordenar por nombres 
se definen don la palabra reservada def 
``` p
def suma(numero1,numero2):
	return numero1+numero2
```
##### Limites de las funciones
* no pueden empezar con un digito
* no puede ser un keyword
* deben tener nombres diferentes entre si 
##### Funciones con parámetros

#### Estructuras condicionales en python
en un programa no solo necesitamos hacer operaciones, tambien debemos tomar decisiones a partir de lo que vamos sabiendo, por eso existen las estructuras condicionales y para ello utilizamos los operadores relacionales y logicos 

###### Operadores relacionales
* ==
* !=
* <
* >
* <=
* >=

###### Operadores lógicos 
* Or
* And
* Not

#### El zen de python
~~~ p
ĩmport this
~~~
El zen de Python:
Hermoso es mejor que feo.
Explícito es mejor que implícito.
Simple es mejor que complejo.
Complejo es mejor que complicado.
Sencillo es mejor que anidado.
Escaso es mejor que denso.
La legibilidad cuenta.
Los casos especiales no son lo suficientemente especiales para romper las reglas.
Lo práctico le gana a la pureza.
Los errores no debe pasar en silencio.
A menos que sean silenciados.
En cara a la ambigüedad, rechazar la tentación de adivinar.
Debe haber una - y preferiblemente sólo una - manera obvia de hacerlo.
Aunque esa manera puede no ser obvia en un primer momento a menos que seas holandés.
Ahora es mejor que nunca.
Aunque “nunca” es a menudo mejor que “ahora mismo”.
Si la aplicación es difícil de explicar, es una mala idea.
Si la aplicación es fácil de explicar, puede ser una buena idea.
Los espacios de nombres son una gran idea ¡hay que hacer más de eso!
#### Comparación de Strings
los strings son inmutables, no se pueden modificar y si se quiere cambiar hay que crear uno nuevo

~~~ py
a = 'hola'
r = 'l' + a[1:]
~~~

* Los String se pueden comparar haciendo uso de los operadores relacionales

#### ASCII vs UNICODE
* Ambos son codigos de caracteres
* ASCII (american standar code for information interchange)
* UNICODE incluye la mayoria de los alfabetos del mundo

python 2 maneja por defecto la codificacion ASCII y python 3 ya lo hace con UNICODE.

#### Recursión
hace referencia a una funcion que se llama a si misma 

#### Manejo de strings
La función len nos permite saber la longitud de un string

##### Metodos de string
~~~ py
my_string = 'La Wea cuatica'
my_string.upper() #lo pone todo en mayus
my_string.lower() # lo pone todo en minusculas
my_string.find('W') #busca el indice de la letra ingresada
~~~

#### Slices
* se pueden obtener sud-strings utilizando la notacion en slices
* se definen los rangos que se requieren y los sltos necesarios
~~~ py
x='platzi'
x[1]
x[1:]
x[1:3] #no se cuenta la ultia posición
x[1:6:2] #el ultimo es el intervalo en el cual queremos que salte
x[::-1] #le da la vuelta a un string
x[start:end:hops]
#### Iteraciones 
* permite realiza la misma secuencia de pasos varias veces
* permite recorrer una secuencia (como un string)
* es una herramienta clave de cualquier programador 

##### Range
~~~ py 
range(x) #imprime una secuencia de x numeros
~~~

#### Ciclos for con python
Es un ciclo iterativo que nos pertime ejecutar x cantidad de veces ciertas lineas de codigo

~~~ py
for i in range(5):
	print(i)
~~~

#### Ciclos while con python
Ejecuta una operacion siempre y cuando una condicion sea verdadera
~~~ py
while x=1:
	instrucciones aquí
~~~

#### Listas
* Es una secuencia de elementos
* Cuando se asigna a una variable, permite agrupar varios elementos en un solo lugar
* Se crean con los corchetes [] o con la funcion list()
```py
productos=['papas','salsa de tomate','pollo frito']
precios=[1000,1500,15000]
```

* Las listas son mutables
```py
productos[0]='zanahorias'
```

* Se puede acceder a un elemento de una lista con su idice

##### Operaciones con listas

* al sumar dos listas, éstas se concatenan
* al multiplicarlas, éstas se multiplican la cantidad de veces que le pusimos
* se pueden trabajar con los slices
* son modificables utilizando su indice y el operador de asignación 
* se pueden ordenar con la funcion sort()
* se puede extraer un elemento de una lista y asignarlo a una variable con la funcion pop()
* pueden extender de otra lista con el metodo extend([list_name])
* podemos eliminar elementos con el keyward  del [list_name[position]]
* podemos convertir un string en una lista haciendo uso de la función list([string]) y ésto deconstruye un string, dejandolo letra por letra, podria ser util para un juego de ahorcado

#### Busquedas binarias
