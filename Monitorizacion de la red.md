# Monitorización de la red.
## Comando tcpdump.
## 3.1	Explicación del comando.
El comando tcpdump es una herramienta esencial en sistemas Unix/Linux para capturar y analizar tráfico de red en tiempo real. Es utilizado por administradores para diagnosticar problemas, monitorear tráfico y detectar actividades sospechosas, examinando los datos que pasan por una interfaz de red.

**Sintaxis básica**:
tcpdump [opciones] [expresión de filtro]
## 3.2	Opciones comunes del comando.
-	**-i [nombre_interfaz]**: Especifica la interfaz de red para capturar tráfico (por defecto selecciona la interfaz activa). 
-	**-n**: No resuelve nombres de host ni puertos (muestra direcciones IP y números de puerto).
-	**-v, -vv, -vvv**: Aumenta el nivel de detalle de la salida.
-	**-c [número]**: Captura un número específico de paquetes.
-	**-w [archivo]**: Guarda los paquetes capturados en un archivo para analizarlos más tarde con herramientas como Wireshark.
-	**-r [archivo]**: Lee paquetes desde un archivo guardado.
-	**-s [snaplen]**: Especifica el tamaño del paquete a capturar (por defecto 96 bytes, usa 0 para capturar todo el paquete).
## 3.3	Capturas de pantalla ejecutando las opciones.

