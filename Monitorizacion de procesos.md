# Monitorización de procesos
## Comando ps 

## 1.1 Explicación del comando  
El comando **ps** es una herramienta fundamental que proporciona una instantánea de los procesos en ejecución. Es útil para obtener información específica sobre los procesos en un sistema Linux.  

## 1.2 Opciones comunes del comando  
El comando `ps` en Linux tiene muchas opciones útiles para mostrar información sobre los procesos en ejecución:  

- **ps**: Muestra una lista de procesos.  
- **ps a**: Muestra los procesos de todos los usuarios/as.  
- **ps -C nano y ps -C nano 3836** (número PID): Filtra los procesos que coinciden con el nombre exacto del comando `nano` y muestra el campo de identificador de proceso (PID).  
- **ps -f**: Muestra una lista completa con información detallada.  
- **ps -l**: Muestra una lista larga de procesos con información detallada.  
- **ps -o vsz**: Muestra el tamaño total de la memoria virtual utilizada por un proceso, expresado en kilobytes (Virtual Memory Size).  
- **ps -p 3836**: Muestra información sobre un proceso específico por su ID de proceso (PID).  
- **ps u**: Muestra la información en formato legible, tipo lista o tabla.  
- **ps -u Antonio**: Muestra los procesos del usuario/a especificado.  
- **ps x**: Muestra los procesos sin terminal.  

## 1.3 Capturas de pantalla ejecutando las opciones  
![Uso de la memoria](imagenes/memoria.png)
