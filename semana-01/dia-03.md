# 📅 Día 3 - [04 de Febrero de 2026]

# VS Code y Seguridad (Bandit 0-3).

## 🎯 Lo que hemos visto hoy

VS Code y OverTheWire (Niveles 0-3)

• Visual Studio Code: Editor de código gratuito. Es fundamental agregarlo al PATH durante la instalación.
    ◦ GUI: Interfaz gráfica (lo que vemos).
    ◦ CLI: Interfaz de línea de comandos.

• Comandos de gestión avanzada:
    ◦ ls -la: Muestra todos los archivos, incluyendo los ocultos.
    ◦ code .: Abre Visual Studio Code en la carpeta actual.
    ◦ Permisos (rwx): Lectura (read), escritura (write) y ejecución (execute).

• Práctica: OverTheWire (Bandit): Juego para aprender terminal mediante el protocolo SSH.

    ◦ Conexión: ssh bandit0@bandit.labs.overthewire.org -p 2220 (donde -p indica el puerto).

    ◦ Nivel 0: Leer el archivo readme con cat.

    ◦ Nivel 1: Para leer un archivo llamado -, usar cat ./- para que el sistema lo reconozca como archivo y no como comando.

    ◦ Nivel 2: Para archivos con espacios en el nombre, usar comillas: cat "./spaces in this filename".

    ◦ Nivel 3: Buscar archivos ocultos en carpetas con ls -la o el comando find.

## 🔗 Recursos útiles

DICCIONARIO DE COMANDOS: 
https://explainshell.com/

## Comandos investigados

### ls -la:
 Se utiliza para listar todos los archivos de un directorio, con la función específica de mostrar también aquellos que están ocultos.

### code .:
 Su función es abrir el editor Visual Studio Code directamente en la carpeta donde te encuentras posicionado actualmente.

### ssh [usuario]@[host] -p [puerto]: 
 Se usa para establecer una conexión remota segura a otro servidor; en la práctica se usó para conectar al juego OverTheWire especificando el puerto con -p.

### cat [archivo]: 
Su función principal es leer y mostrar el contenido de un archivo en la terminal.
    ◦ Uso especial: cat ./- permite leer archivos cuyo nombre es un guion.
    ◦ Uso especial: cat "nombre con espacios" permite leer archivos que contienen espacios en su nombre.

### find: 
Comando cuya función es buscar archivos dentro de las carpetas, útil para localizar archivos ocultos.