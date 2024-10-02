# Script de Red y Escaneo de Puertos

Este script de Bash permite realizar tres funciones principales: escanear equipos activos en una red, verificar puertos abiertos en una dirección IP específica, y mostrar información del sistema. Utiliza comandos como `ifconfig`, `ip`, `ping`, y `bash` para interactuar con la red y el sistema.

## Requisitos

- Bash
- Comando `ifconfig` o `ip` instalado en el sistema
- Permisos de red para ejecutar `ping` y escanear puertos

## Uso

Al ejecutar el script, se presenta un menú con las siguientes opciones:

1. **Escaneo de equipos activos**: Busca dispositivos en la misma subred.
2. **Escaneo de puertos**: Verifica el estado de varios puertos comunes en una dirección IP que el usuario proporciona.
3. **Mostrar información**: Muestra información básica del sistema, como el nombre de usuario, nombre del host y el sistema operativo.
4. **Salir**: Finaliza la ejecución del script.

### Ejecución

```bash
./script.sh

Al ejecutarlo, se mostrará el siguiente menú:

-*-*-*-*-*-*-*-*-*-*
   Menu de Inicio  
-*-*-*-*-*-*-*-*-*-*
 1) Escaneo de equipos activos
 2) Escaneo de puertos
 3) Mostrar informacion
 4) Salir

Detalles de las Funciones
Escaneo de equipos activos: Esta función escanea todos los dispositivos en la misma subred, utilizando ping para verificar si los hosts están activos.

Escaneo de puertos: Realiza una verificación de los puertos comunes en una IP dada por el usuario. Los puertos escaneados son los siguientes:

20, 21, 22, 23, 24, 25, 50, 51, 53, 80, 110, 119, 135, 136, 137, 138, 139, 143,
161, 162, 389, 443, 445, 636, 1025, 1443, 3389, 5985, 5986, 8080, 10000

Mostrar información: Muestra detalles básicos del sistema, como el nombre de usuario, nombre del host y el sistema operativo en uso.

