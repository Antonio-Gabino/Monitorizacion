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
![Procesos](imagenes/1_ps.PNG)
![Procesos](imagenes/2_ps.PNG)
![Procesos](imagenes/3_ps.PNG)
![Procesos](imagenes/4_ps.PNG)
![Procesos](imagenes/5_ps.PNG)
![Procesos](imagenes/6_ps.PNG)
![Procesos](imagenes/7_ps.PNG)
![Procesos](imagenes/8_ps.PNG)
![Procesos](imagenes/9_ps.PNG)
![Procesos](imagenes/10_ps.PNG)

## 1.4 Comentario del resultado del comando  

### Detalles de las opciones del comando `ps`:  

- **ps**:  
Nos muestra el identificador del proceso en ejecución. El PID 1 está reservado para el sistema (como `systemd` o `init`). También identifica la terminal física o virtual, como `tty1`, `tty2`, etc., el tiempo total de CPU utilizado, incluyendo el tiempo de usuario (user time) y el tiempo de sistema (system time), además del nombre del comando que se ejecutó en el proceso.  

- **ps a**:  
  Además de lo anterior, muestra el estado del proceso, que puede ser:  
  - **S** (Sleeping - Durmiendo): Inactivo.  
  - **R** (Running - Corriendo): Ejecutándose.  
  - **D** (Uninterruptible sleep): Durmiendo ininterrumpidamente.  
  - **T** (Stopped - Detenido): Detenido.  
  - **Z** (Zombie): Terminado.  

- **ps -C nano y ps -C nano 3836 (número PID):**  
  Muestra todo lo anterior y además indica que el proceso está en primer plano, es decir, interactúa directamente con el terminal.  

- **ps -f**:  
  Además de algunos de los datos anteriores, muestra:  
  - El ID del usuario/a.  
  - El ID del proceso y del proceso padre (PPID).  
  - La proporción de tiempo que el proceso ha estado activo en la CPU. Un valor más alto sugiere que el proceso ha consumido más recursos de CPU.  

- **ps -l**:  
  Además de lo anterior, incluye:  
  - **PRI (Priority - Prioridad):** Prioridad del proceso para ser programado en la CPU.  
  - **NI (Nice Value - Valor de Amabilidad):** Representa la prioridad o "amabilidad" del proceso hacia otros.  
  - **ADDR (Address - Dirección de Memoria):** Indica la dirección en memoria donde se carga el proceso.  
  - **WCHAN (Waiting Channel - Canal de Espera):** Muestra el nombre del kernel o función en la que el proceso está esperando.  

- **ps -o**:  
  Nos permite especificar el formato de salida de la información.  

- **ps -o vsz**:  
  Muestra el tamaño total de la memoria virtual utilizada por el proceso.  

- **ps -p 3836**:  
  Muestra información sobre un proceso específico por su ID de proceso (PID).  

- **ps u**:  
  Además de lo anterior, muestra:  
  - El porcentaje del tiempo de CPU (%CPU) utilizado por un proceso en relación con el total disponible.  
  - El porcentaje de memoria física total (%RAM) utilizada por un proceso.  

- **ps -u antonio**:  
  Muestra los procesos asociados al usuario especificado.  

- **ps x**:  
  Muestra los procesos que no están asociados a un terminal.  
