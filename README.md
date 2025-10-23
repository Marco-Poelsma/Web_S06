# S06 - Grid

El Grid Layout nos sirve para hacer cosas similares a lo que vimos la semana pasada con Flexbox, pero en 2 dimensiones.

## `display: grid`

`display: grid` nos permite definir un contenedor como una cuadrícula (grid) para sus elementos hijos.

## `grid-template-columns` y `grid-template-rows`

`grid-template-columns` y `grid-template-rows` nos permiten definir el tamaño de las columnas y filas de la cuadrícula.

### Unidades fraccionales (`fr`)
Las unidades fraccionales (`fr`) nos permiten asignar proporciones del espacio disponible en la cuadrícula. Por ejemplo, `1fr` representa una fracción del espacio disponible, `2fr` representa dos fracciones, y así sucesivamente.

## `grid-gap`

`grid-gap` nos permite definir el espacio entre las filas y columnas de la cuadrícula.

## `grid-column` y `grid-row`

`grid-column` y `grid-row` nos permiten definir en qué columna o fila debe ubicarse un elemento dentro de la cuadrícula, así como cuántas columnas o filas debe abarcar.

## `repeat(auto-fit, minmax())`

`repeat(auto-fit, minmax())` es una función útil para crear diseños responsivos en grid, permitiendo que las columnas se ajusten automáticamente al tamaño del contenedor.

## `grid-template-areas`

`grid-template-areas` nos permite nombrar áreas específicas dentro de la cuadrícula para facilitar la colocación de los elementos.

## `grid-area`

`grid-area` nos permite asignar un elemento a una de las áreas definidas en `grid-template-areas`.