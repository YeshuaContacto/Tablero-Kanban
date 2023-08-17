# Tablero-Kanban - YeshuaContacto
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)]()
[![PySide6](https://img.shields.io/badge/PySide6-Qt-4A90E2?style=for-the-badge&logo=qt&logoColor=white&labelColor=101010)](https://wiki.qt.io/Qt_for_Python)

![[https://github.com/YeshuaContacto](https://github.com/YeshuaContacto)](./Tablero-Kanban.jpg)

Esta es una aplicación de Kanban escrita en Python utilizando la biblioteca PySide6 para la interfaz de usuario y CSV para el almacenamiento de datos.

## Características

- La aplicación permite organizar tareas en tres categorías: Pendientes, En Progreso y Completadas.
- Las tareas se muestran en listas que admiten eventos de doble clic y menús contextuales.
- Se pueden agregar nuevas tareas a la lista de Pendientes y se pueden eliminar tareas de cualquier lista.
- Las tareas se guardan en un archivo CSV llamado `tareas.csv` para persistencia.

## Funciones Principales

- `MainWindow` es la clase principal que contiene la interfaz de usuario.
- Las listas de tareas se manejan dinámicamente a través de una lista de listas.
- Las funciones de manejo de eventos se utilizan para crear menús contextuales y manejar acciones como añadir y borrar tareas.
- Las tareas se cargan desde el archivo CSV al iniciar la aplicación y se guardan en el archivo al cerrarla.

## Uso

1. Ejecuta el script y se abrirá la ventana de la aplicación Kanban.
2. Haz doble clic en una tarea para moverla de una categoría a otra.
3. Haz clic derecho en una tarea para abrir un menú contextual con opciones para añadir o borrar tareas.

## Dependencias

- PySide6: Biblioteca para la creación de interfaces gráficas.
- pathlib: Utilizado para manejar rutas de archivos de manera eficiente.
- csv: Utilizado para leer y escribir archivos CSV.
