# Fundamentos_python

## Autor

Mateo Úsuga Álvarez

## Estructura del proyecto

El repositorio está organizado por secciones, donde cada carpeta contiene los laboratorios correspondientes:

**seccion1/** → El Programa "¡Hola, Mundo!"
**seccion2/** → Literales de Python
**seccion3/** → Operadores - herramientas de manipulación de datos
**seccion4/** → Variables

## Sección 1 - El Programa "¡Hola, Mundo!"

### Laboratorio 1: Trabajando con la función print()

**Código:**

print("¡Hola, Mundo!")
print("Mateo")

**Salida:**

¡Hola, Mundo!
Mateo

**Explicación:**
Se utiliza la función "print()" para mostrar texto en consola. Las cadenas deben ir entre comillas.
Si no van entre comillas al ejecutarlo en terminal da error, lo mismo pasa si no lleva paréntesis.
Al escribir el código con solo una comilla sí ejecuta en la terminal, al igual si escribimos varios "prints" en una sola línea.

### Laboratorio 2: La función print() y sus argumentos

**Código:**

print("Programming", "Essentials", "in", sep="***", end="...")
print("Python")

**Salida:**

Programming***Essentials***in...Python

**Explicación:**

"sep" define el separador entre palabras.
"end" evita el salto de línea y agrega texto al final.

### Laboratorio 3: Dando formato a la salida

**Código:**

"Flecha común"
print("    *")
print("   * *")
print("  *   *")
print(" *     *")
print("***   ***")
print("  *   *")
print("  *   *")
print("  *****")

**Salida:**

    *
   * *
  *   *
 *     *
***   ***
  *   *
  *   *
  *****

**Explicación:**

Se utilizan múltiples instrucciones "print()" para generar una figura en consola.

**Versión usando \n (menos líneas de código)**
print("    *\n   * *\n  *   *\n *     *\n***   ***\n  *   *\n  *   *\n  *****")

Se usa \n para generar saltos de línea dentro de una sola instrucción print().

**Flecha más grande**
print("        *")
print("       * *")
print("      *   *")
print("     *     *")
print("    *       *")
print("   *         *")
print("  *           *")
print(" *             *")
print("****         ****")
print("   *         *")
print("   *         *")
print("   *         *")
print("   ***********")

Se mantiene la proporción de la figura aumentando los espacios.

**Flechas duplicadas**
print("    *    " * 2)
print("   * *   " * 2)
print("  *   *  " * 2)
print(" *     * " * 2)
print("***   ***" * 2)
print("  *   *  " * 2)
print("  *   *  " * 2)
print("  *****  " * 2)

**Salida:**

    *           *
   * *         * *
  *   *       *   *
 *     *     *     *
***   ********     ***
  *   *       *   *
  *   *       *   *
  *****       *****

Se utiliza la multiplicación de cadenas (* 2) para repetir el patrón.

## Sección 2 - Literales de Python

### Laboratorio 1: Literales de Python - Cadenas

**Código:**

print("\"Estoy\"\"\"aprendiendo\"\"\"\"\"Python\"\"\"")

**Salida:**

"Estoy"""aprendiendo"""""Python"""

**Explicación:**

Se utilizaron caracteres de escape (\) para imprimir comillas dentro de una cadena.
Cada \" permite mostrar una comilla sin cerrar la cadena.
Python interpreta correctamente la secuencia de escape y muestra el texto exacto.

## Sección 3 - Operadores - herramientas de manipulación de datos

### Laboratorio 1: Ejercicios de Operadores, Matematicos.

**Operaciones:**

# Ejercicio 1
print(5 + 3 * 2)

# Ejercicio 2
print(8 / 2 + 4 * 3)

# Ejercicio 3
print((7 + 3) * 2 - 5)

# Ejercicio 4
print(10 - 4 + 2 * 3)

# Ejercicio 5
print((10 / 2) * (3 + 2) - 4)

# Ejercicio 6
print(2 + 3 * (4 - 1))

# Ejercicio 7
print(5 * 2 ** 3)

# Ejercicio 8
print(6 + 4 / 2 ** 2)

# Ejercicio 9
print(10 % 3 + 2 * 5)

# Ejercicio 10
print((8 + 2) * 3 ** 2)

# Ejercicio 11
print(7 + 2 * (3 + 5) / 4)

# Ejercicio 12
print(2 ** 3 * 4 / 2)

# Ejercicio 13
print(9 - 6 + 3 ** 2)

# Ejercicio 14
print((7 - 2) * 5 + 3 ** 2)

# Ejercicio 15
print(4 * 2 ** 3 / 8 + 1)

## Paso a paso para solucionarlos:

**Ejercicios de Operadores Matemáticos**

**Ejercicio 1**

Expresión:
5 + 3 * 2

Paso a paso:

Multiplicación: 3 * 2 = 6
Suma: 5 + 6 = 11

Resultado:
11

**Ejercicio 2**

Expresión:
8 / 2 + 4 * 3

Paso a paso:

División: 8 / 2 = 4.0
Multiplicación: 4 * 3 = 12
Suma: 4.0 + 12 = 16.0

Resultado:
16.0

**Ejercicio 3**

Expresión:
(7 + 3) * 2 - 5

Paso a paso:

Paréntesis: 7 + 3 = 10
Multiplicación: 10 * 2 = 20
Resta: 20 - 5 = 15

Resultado:
15

**Ejercicio 4**

Expresión:
10 - 4 + 2 * 3

Paso a paso:

Multiplicación: 2 * 3 = 6
Operaciones de izquierda a derecha:
10 - 4 = 6
6 + 6 = 12

Resultado:
12

**Ejercicio 5**

Expresión:
(10 / 2) * (3 + 2) - 4

Paso a paso:

Paréntesis:
10 / 2 = 5.0
3 + 2 = 5
Multiplicación: 5.0 * 5 = 25.0
Resta: 25.0 - 4 = 21.0

Resultado:
21.0

**Ejercicio 6**

Expresión:
2 + 3 * (4 - 1)

Paso a paso:

Paréntesis: 4 - 1 = 3
Multiplicación: 3 * 3 = 9
Suma: 2 + 9 = 11

Resultado:
11

**Ejercicio 7**

Expresión:
5 * 2 ** 3

Paso a paso:

Exponente: 2 ** 3 = 8
Multiplicación: 5 * 8 = 40

Resultado:
40

**Ejercicio 8**

Expresión:
6 + 4 / 2 ** 2

Paso a paso:

Exponente: 2 ** 2 = 4
División: 4 / 4 = 1.0
Suma: 6 + 1.0 = 7.0

Resultado:
7.0

**Ejercicio 9**

Expresión:
10 % 3 + 2 * 5

Paso a paso:

Módulo: 10 % 3 = 1
Multiplicación: 2 * 5 = 10
Suma: 1 + 10 = 11

Resultado:
11

**Ejercicio 10**

Expresión:
(8 + 2) * 3 ** 2

Paso a paso:

Paréntesis: 8 + 2 = 10
Exponente: 3 ** 2 = 9
Multiplicación: 10 * 9 = 90

Resultado:
90

**Ejercicio 11**

Expresión:
7 + 2 * (3 + 5) / 4

Paso a paso:

Paréntesis: 3 + 5 = 8
Multiplicación: 2 * 8 = 16
División: 16 / 4 = 4.0
Suma: 7 + 4.0 = 11.0

Resultado:
11.0

**Ejercicio 12**

Expresión:
2 ** 3 * 4 / 2

Paso a paso:

Exponente: 2 ** 3 = 8
Multiplicación: 8 * 4 = 32
División: 32 / 2 = 16.0

Resultado:
16.0

**Ejercicio 13**

Expresión:
9 - 6 + 3 ** 2

Paso a paso:

Exponente: 3 ** 2 = 9
Operaciones de izquierda a derecha:
9 - 6 = 3
3 + 9 = 12

Resultado:
12

**Ejercicio 14**

Expresión:
(7 - 2) * 5 + 3 ** 2

Paso a paso:

Paréntesis: 7 - 2 = 5
Exponente: 3 ** 2 = 9
Multiplicación: 5 * 5 = 25
Suma: 25 + 9 = 34

Resultado:
34

**Ejercicio 15**

Expresión:
4 * 2 ** 3 / 8 + 1

Paso a paso:

Exponente: 2 ** 3 = 8
Multiplicación: 4 * 8 = 32
División: 32 / 8 = 4.0
Suma: 4.0 + 1 = 5.0

Resultado:
5.0



