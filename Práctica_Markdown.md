# MARKDOWN

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.

~~~
- Elementos de bloque
  -Párrafos
  - Saltos de línea
  - Encabezados
  - Citas
  - Listas
  - Códigos de bloque
  - Líneas horizontales
- Elementos de línea
  - Énfasis
  - Links o enlaces
  - Código
  - Imágenes
- Otro elementos
  - Links automáticos
  - Omitir Markdown
  - Símbolos matemáticos
~~~

# Saltos de bloque (=Párrafos)

Para generar un nuevo párrado en Markdon simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO). `Ejemplo:`

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras cursus commodo urna at mattis. Aliquam lobortis vestibulum metus in fermentum. Ut sit amet dignissim leo. Vivamus eu justo lacus. Morbi fermentum risus ut dictum fermentum. Nullam cursus scelerisque lacus non molestie.


# Saltos de línea (=lineas de texto)

Para generar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar **dos veces** la barra espaciadora antes de pulsar una vez INTRO. `Ejemplo:`

Nombres:  
Rioja Montaño  
Gandia






# ENCABEZADOS

Las almuadillas o hastag `#` es el
método utilizado en Markdown para
crear encabezados. Debes usarlos
añdiendo un por cada nivel y
dejando un espacio en blanco.
 `Ejemplo:`

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1 asterisco Para poner negritas encierra entre 2 asteriscos Para poner negritas y cursiva encierra entre 3 asteriscos `Ejemplo:`

Lorem *ipsum* **dolor** ***sit amet, consectetur adipiscing elit.*** Cras cursus commodo urna at mattis. Aliquam lobortis vestibulum metus in fermentum. Ut sit amet dignissim leo. Vivamus eu justo lacus. Morbi fermentum risus ut dictum fermentum. Nullam cursus scelerisque lacus non molestie.

# Líneas horizontales

Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemplo:`

---

# Citas

Las citas se generan utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`

>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras cursus commodo urna at mattis. Aliquam lobortis vestibulum metus in fermentum. Ut sit amet dignissim leo. Vivamus eu justo lacus. Morbi fermentum risus ut dictum fermentum. Nullam cursus scelerisque lacus non molestie.

# Listas

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos de por cada item de la lista: Un asterisco `*`, un guión medio `-` o un símbolo más `+`. `Ejemplo:`

- ítem 1
- ítem 1
- ítem 1

Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1.`.
1. ítem1
2. ítem1
3. ítem2

Para generear listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendrás que añadir `dos (o cuatro) espacios en blanco.` `Ejemplo:`

- ítem 1
  - ítem 12
    - ítem 121
- ítem 2

1. ítem 1
   1. ítem12
      1. ítem121
2. ítem 1

# Links o enlaces

Insertar una imagen con Markdown se realiza de un manera idéntica a insertar links. En este caso, debes añadir un símbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

~~~
[Texto alternativo](ruta/imagen.jpg "Título alternativo")
~~~

`Ejemplo:`

![paisaje](https://images.pexels.com/photos/13716813/pexels-photo-13716813.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load "Paisaje")

![gato](https://images.pexels.com/photos/13539518/pexels-photo-13539518.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load "gato")

# Tablas

Markdown permite dibujar tablas mediante plecas `|`. Cada celda está separada por uno de estos caracateres. Para crear encabeazados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones `-`. `Ejemplo:`

| Columna 1 | Columna 2 |
| -- | -- |
| uno | dos |
| tres | cuatros |
| cinco | seis |

# Línea de Códgio

Encerrando el código entre acentos graves `<html lang="es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas o tres acentos grave. La otra manera de añadir en Markdown es comenzar el párrafo con `cuatro espacios en blanco.` `Ejemplo:`

~~~ html
!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
~~~

# Omitir Markdown

Cómo escribir ciertos símbolos como * o #, sin que Markdown los intrprete para convertirlos en negritas,...  
Escribiendo justo delante del símbolo la barra `\`. `Ejemplo:` Esto es un asterisco \*

# Escritura matemática

En línea encerrando la fórmula entre signos de `$` En párrafos centrados, encerrando las formulas entre dos signos de `$$`

- Fórmulas $C12+C22=h2$
- Fórmulas centradas: $$a² - b² = (a + b) x (a - b)$$
- Radicales $$\sqrt{a² - b²}$$
- Fracciones $$ x = \frac {-b \pm \sqrt{b² - 4ac}}{2a}$$
- Paréntesis grandes: $$\left (\sqrt{x²}\right)²$$
- Colores:
$$ aBb123\color {red} {G}$$