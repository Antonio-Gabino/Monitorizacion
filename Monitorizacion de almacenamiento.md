# Monitorización del almacenamiento.
![Almacenamiento](imagenes/Imagen_almacenamiento.jpeg)
## Comando free.
## 2.1	Explicación del comando.
El comando free en sistemas operativos basados en Linux sirve para mostrar información detallada sobre el uso de la memoria del sistema. 
Incluye datos sobre:
Memoria física (RAM): Memoria libre y utilizada.
Memoria de intercambio (swap): Espacio asignado para ampliar la memoria virtual.
Buffers y cachés del sistema: Recursos usados para optimizar el rendimiento.
Es una herramienta útil para monitorear el estado de la memoria y diagnosticar problemas relacionados con su gestión.
## 2.2	Opciones comunes del comando.
-	__free__: Muestra información del uso de la memoria RAM (libre y utilizada).
-	__-b__: Muestra la memoria en bytes.
-	__-k__: Muestra la memoria en kilobytes (por defecto).
-	__-m__: Muestra la memoria en megabytes.
-	__-g__: Muestra la memoria en gigabytes.
-	__-h__: Muestra los valores en un formato legible para humanos (por ejemplo, 2.0G en lugar de 2097152).
-	__-t__: Muestra una fila adicional con el total de memoria (RAM + swap).
## 2.3	Capturas de pantalla ejecutando las opciones.
![Almacenamiento](imagenes/1_free.PNG)
![Almacenamiento](imagenes/2_free.PNG)
![Almacenamiento](imagenes/3_free.PNG)
![Almacenamiento](imagenes/4_free.PNG)

## 2.4 Comentario del resultado del comando.
-	**free**: Muestra información sobre el uso de la memoria RAM del sistema.
-	**free -b**: Muestra información de la memoria en bytes.
-	**free -b**: Muestra la memoria en gigabytes.
-	**free -t**: Muestra una fila adicional con el total de memoria (RAM + swap).
  
Descripción de las columnas:
-	__total__: Memoria total del sistema.
-	__usado__: Memoria en uso.
-	__libre__: Memoria libre (sin usar en absoluto).
-	__compartido__: Memoria compartida entre procesos.
-	__buf/cache__: Memoria usada por buffers y cachés del sistema.
-	__disponible__: Memoria realmente disponible para ser usada por aplicaciones.
## Comando df.
## 2.4	Explicación del comando.
El comando df en Linux muestra información sobre el uso y la disponibilidad de espacio en los sistemas de archivos montados. Permite conocer:
Espacio de disco utilizado.
Espacio de disco libre.
Es una herramienta útil para monitorear y gestionar el almacenamiento en discos y particiones.
## 2.5	Opciones comunes del comando.
-	**df**: Muestra el espacio utilizado y disponible en los sistemas de archivos montados.
-	**-h**: Muestra los valores en un formato legible para humanos (por ejemplo, 1G en lugar de 1073741824).
-	**-k**: Muestra los tamaños en kilobytes (por defecto).
-	**-m**: Muestra los tamaños en megabytes.
-	**-T**: Muestra el tipo del sistema de archivos (ext4, xfs, etc.).
-	**-i**: Muestra el uso de inodos en lugar del espacio en disco.
-	**--total**: Muestra un total acumulado de todas las entradas listadas.
-	**--output**: Permite personalizar las columnas que se muestran en la salida.
## 2.6	Capturas de pantalla ejecutando las opciones.
