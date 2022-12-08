# Enlaces útiles

## Acceso al moodle

http://187.217.4.141/~edc/moodle/ Folio de usuario / curp*p

## Asistencia

https://docs.google.com/forms/u/0/d/e/1FAIpQLSc9JNBZU4ZtbsQTLawLtPfrEMHHLop6D1jDw2-uEVnBVaHK_w/formResponse

## Ejercicios básicos

https://colab.research.google.com/drive/1Q93rZvPbXWvDqVAMNMdX4gUEkXDF3vAH

## Estudiar

https://www.learnpython.org/es/

https://www.codedex.io/

https://learn.grasshopper.app/      Javascript

https://www.online-python.com/     IDE para python

# Unidad 1

## Tipos de datos

+ int
+ float
+ chr
+ str
+ bool

## Variables 
+ acumulativas (almacenan valores a partir de sumas sucesivas)
+ trabajo (contienen fórmulas y/o funciones)
+ contadores (secuencia en aumento)

Sintaxis
- this_is_snake_case  Este es el que se utiliza en Python

- PascalCaseExample

- camelCaseExample

- kebab-case-example


## Funciones

Sintaxis: palabraReservada(arg1,arg2,arg3,...)

## Importar funciones

from nombreLibrería import función1, función2,...

librerías importantes
+ math        funciones matemáticas
+ datetime    formatos de tiempo
+ time        funciones de tiempo
+ random      funciones aleatorias
+ 

## Tipo de datos
Cadena(string): utilizaremos el formato f-string para convertir a cadena

```
f 'cadena de texto {variable1} cadena de texto {variable2}'
```

https://realpython.com/python-f-strings/

### Métodos relevantes:

.title()  

## Listas, Tuplas y diccionarios

+ Tuplas. Se escriben con corchetes y no piueden modificarse.
+ Listas. Se escriben con paréntesis y se pueden modificar.
+ Diccionarios. Conjuntos a pares de elementos. un identificador y su valor

## Práctica 1

https://colab.research.google.com/github/sicariusdevx/Python/blob/main/02.ENTREROS_Y_REALES/int_y_float.ipynb#scrollTo=ZcNt0zNY7xEs

# Operadores

## Operadores de Python

https://www.programiz.com/python-programming/operators

## Estructuras de control u Operadores relacionles

IF

Se puede utilizar if para comprobar que en la captura de información el usuario no meta cadenas vacías
Al preguntar con var_captura cualquier valor que contenga devuelve TRUE y si está en null devuelve FALSE

if var_captura:
  lista.append(var_captura)

FOR   sintaxis:  for var_iteración in lista_iterable:

+ La var_iteración no necesita ser inicializada. Es una variable local del for y es buena práctica darle una especificación que dé a entender sobre qué elementos va a iterar
+ función range([valor_inicial],valor_limite,[salto])  crea una lista de rango, valor límite no se abarca al momento de recorrerlo
+ 
