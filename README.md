# herencia_interfaces_java
# Interfaces en Java

Este repositorio contiene ejemplos de archivos de código fuente en Java que ilustran el concepto de interfaces.

## Archivos

El repositorio incluye los siguientes archivos:

- `Main.java`: Archivo que contiene el método `main` y se utiliza para ejecutar el programa.
- `InterfaceB.java`: Archivo que define una interfaz llamada `InterfaceB` con un método `mostrarMensaje` y un método `saluda` por defecto.
- `InterfaceA.java`: Archivo que define una interfaz llamada `InterfaceA` que extiende de `InterfaceB`.
- `ClaseFinal.java`: Archivo que implementa la interfaz `InterfaceA` y proporciona una implementación del método `mostrarMensaje`.

## Compilación y Ejecución

Para compilar y ejecutar los archivos, sigue los siguientes pasos:

1. Asegúrate de tener Java Development Kit (JDK) instalado en tu sistema.
2. Abre una terminal o línea de comandos.
3. Navega hasta el directorio donde se encuentran los archivos con el código fuente.
4. Ejecuta el siguiente comando para compilar los archivos:

   ```shell
   javac Main.java ClaseFinal.java
