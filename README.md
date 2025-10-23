# S06 - Grid

[Ejercicio](https://github.com/Marco_Poelsma/Web_S06-Ex)

El Grid Layout nos sirve para hacer cosas similares a lo que vimos la sesión pasada con Flexbox, pero en 2 dimensiones.

## `display: grid`

`display: grid` nos permite definir un contenedor como una cuadrícula (grid) para sus elementos hijos.

---

## `grid-template-columns` y `grid-template-rows`

`grid-template-columns` y `grid-template-rows` nos permiten definir el tamaño de las columnas y filas de la cuadrícula.

### Unidades fraccionales (`fr`)

Las unidades fraccionales (`fr`) nos permiten asignar proporciones del espacio disponible en la cuadrícula. Por ejemplo, `1fr` representa una fracción del espacio disponible, `2fr` representa dos fracciones, y así sucesivamente.

### `repeat()`

La función `repeat()` nos permite repetir un patrón de columnas o filas en la cuadrícula. Por ejemplo, `grid-template-columns: repeat(3, 1fr);` crea tres columnas de igual tamaño.

#### Nota adicional:

Pese a que también se puede usar `grid-template-rows`, en la práctica es más común definir solo las columnas y dejar que las filas se ajusten automáticamente según el contenido.

---

## `grid-auto-columns` y `grid-auto-rows`

`grid-auto-columns` y `grid-auto-rows` nos permiten definir el tamaño de las columnas y filas que se crean automáticamente cuando los elementos hijos exceden el número de columnas o filas definidas en `grid-template-columns` y `grid-template-rows`.

Aún así, nosotros usaremos la funcion `repeat()`, que es más común.

---

## `grid-gap`

`grid-gap` nos permite definir el espacio entre las filas y columnas de la cuadrícula.

---

## `grid-column` y `grid-row`

`grid-column` y `grid-row` nos permiten definir en qué columna o fila debe ubicarse un elemento dentro de la cuadrícula, así como cuántas columnas o filas debe abarcar.

---

## `repeat(auto-fit, minmax())`

`repeat(auto-fit, minmax())` es una función útil para crear diseños responsivos en grid, permitiendo que las columnas se ajusten automáticamente al tamaño del contenedor.

---

## `grid-template-areas`

`grid-template-areas` nos permite nombrar áreas específicas dentro de la cuadrícula para facilitar la colocación de los elementos.

---

## `grid-area`

`grid-area` nos permite asignar un elemento a una de las áreas definidas en `grid-template-areas`.
