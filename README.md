# ETL con MySQL y Python

## Descripción
Este repositorio contiene un flujo de ETL (Extracción, Transformación y Carga) implementado con **MySQL, Docker y Python**. Permite mover datos desde una base transaccional a un almacén de datos (Data Warehouse) optimizado para análisis.

## Contenido del Repositorio
- **Dockerfile** y **docker-compose.yml**: Configuración del entorno de MySQL en Docker.
- **Scripts SQL**: Creación y carga de datos en las bases de datos.
- **Archivos CSV**: Datos de prueba para la dimensión de usuarios y premios de películas.
- **Notebook ETL**: Código en Python para extraer, transformar y cargar los datos.

## Requisitos
- Tener una cuenta en GitHub y hacer un **fork** de este repositorio.
- Usar **GitHub Codespaces** para ejecutar el proyecto sin necesidad de instalaciones locales.
- La extensión **MySQL Database Client** en Codespaces para gestionar la base de datos.

## Instrucciones de Uso
1. Haz un **fork** del repositorio y ábrelo en **GitHub Codespaces**.
2. Ejecuta el siguiente comando en la terminal para iniciar el entorno:
   ```bash
   docker-compose up -d

3. Usa la extensión MySQL Database Client para conectarte a la base de datos.
   
   El contenedor de MySQL ya habrá ejecutado los scripts SQL automáticamente.

4. Explora los archivos y el notebook para entender el proceso ETL.

5. Modifica y ejecuta el código según sea necesario.

## Notas Adicionales

- Los datos en los archivos CSV son ficticios y usados solo con fines educativos.

- Si tienes preguntas o mejoras, no dudes en contribuir al repositorio.

🚀 ¡Disfruta del aprendizaje con este proyecto ETL!
