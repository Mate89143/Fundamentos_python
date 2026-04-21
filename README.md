# Fundamentos_python

## Autor

Mateo Úsuga Álvarez

## Estructura del proyecto

El repositorio está organizado por secciones, donde cada carpeta contiene los laboratorios correspondientes:

**seccion1/** → El Programa "¡Hola, Mundo!"
**seccion2/** → Literales de Python
**seccion3/** → Operadores - herramientas de manipulación de datos
**seccion4/** → Variables

## Sección 1 – El Programa "¡Hola, Mundo!"

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

