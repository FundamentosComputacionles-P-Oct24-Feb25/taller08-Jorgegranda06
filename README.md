# taller8

## Diseño de la solución de problemas con pseudocódigo aplicando arreglos unidimensionales.

A. Revisar los ejercicios y problemáticas de la carpeta ej1, ej2, ej3. Plantear las mejores o completar lo solicitado

* ej1
* ej2
* ej3

B. **ej4** Generar una miniespecificación que permita ingresar los valor de ventas de un vendedor por cada día de la semana (lunes a viernes); donde día 0 es Lunes.
Usar 2 arreglos.
```
(ventas(5),i[0-n])  // arreglo que debe ser llenado por el usuario


(dias(5), x(20)[{a-z}, {BS}])
dias[0]<-- "Lunes"
dias[1]<-- "Martes"
dias[2]<-- "Miércoles"
dias[3]<-- "Jueves"
dias[4]<-- "Viernes"
```

Luego presentar un reporte así
- Lunes $130
- Martes $200
- Miércoles $190
- Jueves $200
- Viernes $100

C. **ej5** Dados los siguientes arreglos
```
arreglo(3), x(50)[{a-z}, {A-Z}, {1-9}, BS]
arreglo[0] <-- "Café tradicional"
arreglo[1] <-- "Café francés"
arreglo[2] <-- "Café alemán"

arreglo(3),d[0-n]
arreglo[0] <-- 1.5
arreglo[1] <-- 2.1
arreglo[2] <-- 2.3

```
Generar una solución que permita de forma repetitiva solicitar a un cliente que seleccione los productos que desea comprar (hasta que le usuario lo decida). Por ejemplo, si el usuario decide comprar café tradicional, se debe preguntar el número de tazas y calcular el total a pagar por ese pedido solo pedido. Al final se debe presentar en una cada acumuladora lo siguiente.

El usuario ha comprado:

Café tradicional (6 t), valor a cancelar $9
Café alemán (3 t), valor a cancelar $6.3
Café francés (2 t), valor a cancelar $4.6
Total a pagar: 19.6


E. **ej6** Genere una solución. Dada los siguientes arreglos, analice y llene un nuevo arreglo, llamado calificaciones_cuantitativas. Para ello considere:
* 0-7 es una nota Regular
* Mayor a 7 y menor 9 es una nota Muy Buena
* Mayor o igual a 9, es una nota Excelente

notasEstudiantes <-- {9, 10, 7, 8}
nombresEstudiantes <-- {"Mónica", "Homero", "Antonio", "Vanessa"}
apellidosEstudiantes <-- {"Suárez", "Jara", "Salas", "Mora"}

Al final debe presentar el siguiente reporte
```
Mónica Suárez tiene una nota de 9 (Excelente)
Homero Jara tiene una nota de 10 (Excelente)
Antonio Salas tiene una nota de 7 (Regular)
Vanessa Mora tiene una nota de 8 (Muy Buena)
```
F. **ej7** Diseñe una miniespecificación que permita al usuario introducir 10 números en un arreglo, luego despliegue cada número y su diferencia a partir del promedio numérico de los números introducidos.
