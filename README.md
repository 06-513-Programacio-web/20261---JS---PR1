# Proyecto PR1 - Programación Web

Este proyecto forma parte de la asignatura de Programación Web de la UOC.

Este fichero es solo de referencia: el enunciado válido de la práctica es el que está en el aula correspondiente (aula.uoc.edu).

## Estructura del proyecto

El proyecto contiene los siguientes archivos:

- `pra1_estructura.js`: archivo base con las clases y funciones que debéis implementar (con sus nombres y parámetros) y los datos de prueba.
- `README.md`: este archivo, con unas explicaciones mínimas y referencias útiles.
- `LICENSE`: licencia del proyecto.

## Instrucciones de uso

1. Clona el repositorio en tu máquina local.
2. Haz un duplicado del archivo `pra1_estructura.js` y nómbralo `pra1.js`.
3. Implementa sobre `pra1.js` las clases y funciones que pide el enunciado, sin cambiar sus nombres ni sus parámetros.
4. Añade al final del archivo, en la sección **PRUEBAS**, las llamadas necesarias para comprobar que todo funciona, incluidas las pruebas con datos no válidos.

### Cómo ejecutarlo

Con [Node.js](https://nodejs.org/) 18 o superior:

```bash
node pra1.js
```

También podéis ejecutarlo en la consola del navegador o con el depurador de Visual Studio Code (lo veremos en la videoconferencia de presentación de la práctica).

## Datos de prueba

El archivo incluye seis series ya creadas. Cinco son series reales con datos de la API de TVmaze, simplificados: cada serie tiene solo algunos episodios por temporada. Hay tres excepciones, pensadas para poder probar todos los casos:

- El valor de `weight`: en la API vale 100 en todas estas series, y aquí se usan valores distintos para que la ordenación por popularidad dé un resultado visible.
- El episodio T3E1 de *The Last of Us*, que es ficticio y no tiene fecha de emisión.
- La serie *Proyecto Aurora*, que es ficticia: no tiene valoración, géneros ni plataforma, y sus episodios se emiten en el futuro.

Para las funciones de fechas, usad la constante `TODAY` (13 de noviembre de 2026) como fecha de referencia, de manera que los resultados no dependan del día en que ejecutéis el código.

## Requisitos

- Haber trabajado los contenidos de las PEC 0, 1 y 2 (introducción a JavaScript, casos específicos de funciones y clases).

## Referencias

### Clases

- [Clases](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Classes)
- [Campos privados (`#`)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Classes/Private_properties)
- [Campos públicos de clase (incluidas las funciones flecha como campos)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Classes/Public_class_fields)
- [`get`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/get) y [`set`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/set)
- [`instanceof`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/instanceof)

### Funciones

- [Funciones flecha](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Parámetros rest](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [Parámetros por defecto](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/Default_parameters)
- [Recursión (glosario de MDN)](https://developer.mozilla.org/es/docs/Glossary/Recursion)

### Arrays

- [`map`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/map), [`filter`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) y [`reduce`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
- [`find`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/find), [`some`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/some) y [`flatMap`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)
- [`sort`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) (¡ojo!: modifica el array sobre el que se llama)

### Objetos y operadores

- [Desestructuración](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
- [Sintaxis spread (`...`)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
- [Encadenamiento opcional (`?.`)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Optional_chaining) y [operador de fusión de nulos (`??`)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing)

### Fechas

- [`Date`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [`Date.UTC()`](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Date/UTC)
- [Formato de fecha ISO y cómo se interpreta](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date#date_time_string_format) (en inglés)

### API de TVmaze

- [Documentación de la API de TVmaze](https://www.tvmaze.com/api) (en inglés). En la PRA1 no se usa, pero conviene ver qué forma tienen los datos que recibiréis en la PRA2.

### Buenas prácticas

- [Best practices for writing code comments](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/), Ellen Spertus (en inglés): las 9 reglas con las que se evalúan los comentarios.

### Git y GitHub (voluntario)

- [Hoja de referencia de Git](https://training.github.com/downloads/es_ES/github-git-cheat-sheet/)
- [Libro oficial de Git](https://git-scm.com/book/es/v2)

## Autores

- Kepa Sarasola Bengoetxea y Vicent Moncho Mas
