![Leonardo_Diffusion_Galactic_programming_setup_0](https://github.com/leo1929/PythonProyects/assets/65140715/529ed8e1-9dc1-4040-8bf5-bc20e564004b)

# Generador de Base de Datos Ficticia en Python

El proyecto **Generador de Base de Datos Ficticia** es una herramienta desarrollada en Python usando [Google Colab](https://colab.research.google.com/?hl=es) que permite crear una base de datos simulada con información de clientes, productos, ventas y opiniones. Esta base de datos ficticia es ideal para practicar y aprender sobre el lenguaje de consulta estructurado (SQL) y el manejo de bases de datos.

## Tablas de Contenido

- [Descripción](#descripción)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Ejecución](#ejecución)
- [Ejemplos](#ejemplos)

## Descripción

El código utiliza la biblioteca [Pandas](https://pandas.pydata.org/) para crear y manipular los datos de manera sencilla y efectiva. Además, hace uso de la librería [Faker](https://faker.readthedocs.io/en/master/), que permite generar datos aleatorios como nombres de clientes, números de teléfono y fechas de ventas de manera realista.

La base de datos ficticia creada consta de cuatro tablas: "Clientes", "Productos", "Ventas" y "Opiniones". La tabla "Clientes" almacena información como nombres, edades, correos y números de teléfono aleatorios para 100 clientes simulados. La tabla "Productos" incluye detalles sobre 100 productos ficticios, como categoría, subcategoría y precios en dólares.

La tabla "Ventas" registra 100 ventas ficticias, donde cada venta se relaciona con un cliente y un producto específico, junto con la cantidad comprada y el total de la venta. Por último, la tabla "Opiniones" contiene 100 opiniones simuladas sobre los productos, proporcionando una calificación o descripción de la experiencia de compra.

Este proyecto es útil para quienes deseen practicar sus habilidades en SQL, realizar análisis de datos de muestra o probar consultas y comandos en una base de datos ficticia antes de aplicarlos en un entorno de producción real.

## Requisitos

Antes de utilizar este código, asegúrate de cumplir con los siguientes requisitos:

1. **Python**: Es necesario tener Python 3.x instalado en tu sistema. Si aún no lo tienes, puedes descargarlo desde el sitio oficial de Python: [Python.org](https://www.python.org/downloads/) o en su defecto usar [Google Colab](https://colab.research.google.com/?hl=es).
2. **Bibliotecas requeridas**: Asegúrate de tener las siguientes bibliotecas de Python instaladas en tu entorno virtual o sistema global:

   ```bash
   pip install
   pandas
   faker
   ```
Como este cóigo fue desarrolado en google colab se debe usar tambien la biblioteca:

   ```bash
   from google.colab import files
   ```
Para la exportación de los datos a excel.
   
## Instalación

Sigue estos pasos para instalar y configurar el proyecto:

1. Clona el repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
Si no tienes Git instalado, puedes descargar el código fuente directamente desde GitHub y extraer el archivo ZIP.

2. Navega al directorio del proyecto:

   ```bash
   cd tu_repositorio
   ```

3. Instala las dependencias requeridas. Puedes usar pip para instalar las bibliotecas necesarias:

   ```bash
   pip install -r requirements.txt
   ```
   
Asegúrate de que tengas Python 3.x instalado en tu sistema antes de ejecutar este comando.

4. Ejecuta el proyecto:

   ```bash
   python nombre_del_archivo.ipynb o nombre_del_archivo.py
   ```
   
Reemplaza "nombre_del_archivo.ipynb o nombre_del_archivo.py" con el nombre real del archivo principal del proyecto que deseas ejecutar.

Con estos pasos, podrán seguir las instrucciones para instalar y configurar el proyecto en su máquina local. 

## Uso

El proyecto "Generador de Base de Datos Ficticia" tiene como objetivo proporcionar una herramienta fácil de usar para generar bases de datos ficticias de clientes, productos, ventas y opiniones. Esta base de datos simulada es ideal para fines educativos, pruebas de consultas SQL y análisis de datos de muestra.

Para utilizar el proyecto, simplemente sigue las instrucciones de instalación proporcionadas en la sección anterior. Una vez instalado, ejecuta el archivo principal nombre_del_archivo.py, el cual generará una base de datos ficticia con información aleatoria de clientes, productos y ventas. A partir de esta base de datos, podrás practicar tus habilidades en SQL, realizar análisis de datos de muestra o experimentar con consultas para obtener información útil.

Además, puedes explorar las diferentes tablas de la base de datos, como "Clientes", "Productos", "Ventas" y "Opiniones", para obtener una visión general de los datos generados y cómo se relacionan entre sí. También puedes modificar el código para ajustar la cantidad de datos generados o agregar nuevas características según tus necesidades.

¡Disfruta usando el "Generador de Base de Datos Ficticia" y mejora tus habilidades en manipulación de bases de datos y consultas SQL!

## Ejecución
Sigue estos pasos para ejecutar el código y generar la base de datos ficticia:

1. Clona este repositorio o descarga el archivo nombre_del_archivo.py a tu sistema.

2. Asegúrate de tener Python y las bibliotecas requeridas instaladas según se describió anteriormente.

3. Ejecuta el archivo Creacion_Base_de_datos_Ficticia.ipynb utilizando google colab o  creacion_base_de_datos_ficticia.py utilizando el intérprete de Python:

Esto generará la base de datos ficticia y mostrará los datos en la consola.

## Ejemplos

Proporciona ejemplos de uso del proyecto, como consultas SQL interesantes que se pueden realizar en la base de datos ficticia.

![Leonardo_Diffusion_MINIATURA_PARA_YOUTUBE_ENTRENAMIENTO_NATACI_0](https://github.com/leo1929/PythonProyects/assets/65140715/012f944d-5d6c-4303-b3fd-aa0e8c2169c1)



