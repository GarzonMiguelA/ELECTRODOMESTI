# Sistema de Electrodomésticos

Este proyecto implementa un sistema de gestión de electrodomésticos con una estructura de clases en Kotlin. El sistema incluye una clase base `Electrodomestic` y dos clases derivadas `Rentadora` y `Televisio`.

## Clases Principales

### `Electrodomestic`

La clase `Electrodomestic` es la clase base que contiene propiedades comunes para todos los electrodomésticos. Estas propiedades incluyen:

- **preuBase**: El precio base del electrodoméstico.
- **color**: El color del electrodoméstico.
- **consum**: El nivel de consumo energético (etiqueta energética).
- **pes**: El peso del electrodoméstico.

La clase tiene un constructor primario que inicializa estas propiedades y un constructor secundario que permite la creación de instancias con valores personalizados.

La función `preuFinal()` calcula el precio final del electrodoméstico, teniendo en cuenta el consumo energético y el peso.

### `Rentadora`

La clase `Rentadora` hereda de `Electrodomestic` e introduce una propiedad adicional:

- **càrrega**: La capacidad de carga de la lavadora.

La función `preuFinal()` de esta clase sobrescribe la función de la clase base e incluye el cálculo del precio final considerando la capacidad de carga.

### `Televisio`

La clase `Televisio` también hereda de `Electrodomestic` e introduce la propiedad:

- **mida**: El tamaño de la pantalla de la televisión.

La función `preuFinal()` de esta clase sobrescribe la función de la clase base e incluye el cálculo del precio final considerando el tamaño de la pantalla.

## Ejemplo de Uso

El archivo `Main.kt` contiene un ejemplo de uso donde se crean instancias de varios electrodomésticos, se muestra la información detallada de cada uno y se calculan los totales para diferentes tipos de electrodomésticos.

## Estructura del Código

- `Electrodomestic.kt`: Contiene la implementación de la clase base `Electrodomestic`.
- `Rentadora.kt`: Contiene la implementación de la clase `Rentadora`.
- `Televisio.kt`: Contiene la implementación de la clase `Televisio`.
- `Main.kt`: Contiene el ejemplo de uso del sistema con la creación de instancias y el cálculo de totales.

## Ejecución del Proyecto

El proyecto puede ejecutarse directamente desde el archivo `Main.kt`. Al ejecutarlo, se crean instancias de electrodomésticos y se presentan los totales para diferentes categorías.


[Imgur](https://i.imgur.com/Euzq0pR.png)
