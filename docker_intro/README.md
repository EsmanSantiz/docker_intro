# Introducción de Docker: Reto del Mike

Este repositorio contiene la resolución del reto práctico para la materia de **Cómputo en la Nube** 
## Objetivo del Proyecto
El propósito de esta práctica es configurar un entorno de desarrollo aislado utilizando **contenedores**, desplegando un nodo de **Ubuntu** para la integración de herramientas de código abierto.

## Evidencias de Entrega
Puedes consultar el reporte detallado con las capturas de pantalla y conclusiones individuales en el siguiente enlace:
* [Ver Reporte Técnico (PDF)](./Docker%20y%20Entornos%20Cloud.pdf)

## Tecnologías y Herramientas
* **Docker Desktop**: Motor de contenedores utilizado en el sistema anfitrión.
* **Ubuntu Linux**: Imagen oficial utilizada para el nodo de trabajo.
* **Git**: Herramienta utilizada para la clonación del proyecto **Infoga** dentro del contenedor.

## Desarrollo Técnico Realizado
1. **Verificación**: Comprobación de la versión activa de Docker.
2. **Despliegue**: Creación y ejecución del contenedor interactivo `nodo_ubuntu`.
3. **Instalación**: Aprovisionamiento interno del nodo con Git y dependencias de Python.
4. **Persistencia**: Validación del ciclo de vida del contenedor mediante los comandos `start` y `stop`.

---
