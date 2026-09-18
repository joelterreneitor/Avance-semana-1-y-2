# Módulo: Base de Datos (PostgreSQL) - Proyecto Integrador Extratron

## Descripción del Módulo
Este módulo corresponde a la base de datos de la plataforma Extratron. Aquí nos encargamos de diseñar la estructura, crear las tablas y administrar la base de datos en PostgreSQL para guardar de forma organizada toda la información que procesan los demás equipos (datos extraídos, catastro geográfico y registros del sistema).

## Responsable
* **Integrante:** J (Diseño de tablas, importación de datos masivos DENUE, configuración en DBeaver y pruebas en servidor)

## Alcance Personal
* Configuración del cliente DBeaver para trabajar tanto en servidor remoto como de forma local.
* Pruebas de entorno de desarrollo con Docker y diagnóstico de problemas de virtualización.
* Creación de tablas de prueba para validar la conexión entre los integrantes del equipo.
* Creación de estructuras para almacenar datasets geográficos pesados (DENUE - INEGI con 1 millón de registros).
* Pruebas de carga de archivos CSV de gran volumen y solución de errores de mapeo en DBeaver.

## Herramientas Utilizadas
* **Base de datos:** PostgreSQL 16
* **Administración y consultas:** DBeaver
* **Pruebas de contenedor:** Docker Desktop
* **Fuente de datos:** Dataset DENUE del INEGI (CSV)
