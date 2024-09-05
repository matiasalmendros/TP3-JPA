# TP3_DesarrolloSoftware
Este proyecto es una implementación de JPA (Java Persistence API) utilizando la base de datos H2. A continuación, se detallan los pasos para descargar, configurar, y ejecutar el proyecto.

# Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

IntelliJ IDEA

H2 Database

# Instalación

Descargar el repositorio:

Haz clic en el botón Code en la página principal del repositorio.

Selecciona Download ZIP y guarda el archivo ZIP en tu computadora.

Extrae el contenido del archivo ZIP en una ubicación de tu preferencia.

# Abrir el proyecto en IntelliJ IDEA:

Abre IntelliJ IDEA.
Selecciona File > Open... y navega hasta la carpeta donde extrajiste el contenido del ZIP.

Selecciona la carpeta raíz del proyecto y haz clic en OK para abrirlo.

# Configuración de la base de datos H2

Iniciar la base de datos H2:
Asegúrate de que el servidor H2 esté en funcionamiento.

Abre la consola de H2 (h2.bat o h2.sh dependiendo de tu sistema operativo).

Conectarse a la base de datos:

En la consola de H2, selecciona Generic H2 (Embedded).

En el campo JDBC URL, ingresa la siguiente URL:

Copiar código:
jdbc:h2:tcp://localhost/~/test

Completa los campos User Name con sa y Password (déjalo vacío) y haz clic en Connect.

# Ejecución del Proyecto

Ejecutar el proyecto:

En IntelliJ IDEA, navega hasta la clase Main ubicada en src/main/java/org/example/Main.java.

Haz clic derecho sobre el archivo Main.java y selecciona Run 'Main.main()'.
Verificación de los objetos creados:

Después de ejecutar el proyecto, vuelve a la consola de H2.

Ejecuta una consulta para verificar que las tablas y los datos correspondientes han sido creados correctamente:
sql

Copiar código:
SELECT * FROM ARTICULO ;
