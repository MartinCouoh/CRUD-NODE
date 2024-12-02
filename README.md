# Sistema CRUD con Node.js

Este proyecto implementa un sistema CRUD (Crear, Leer, Actualizar y Eliminar) utilizando **Node.js** con el framework **Express**. El objetivo es proporcionar una API RESTful que permita gestionar datos de manera eficiente.

---

## Tabla de Contenidos

- [Descripción](#descripción)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)

---

## Descripción

Este proyecto permite gestionar un recurso genérico (por ejemplo, **usuarios**) mediante un conjunto de operaciones CRUD. A través de esta API RESTful, podrás realizar las siguientes operaciones:

- **Agregar**: Insertar un nuevo usuario.
- **Ver**: Consultar los usuarios existentes.
- **Actualizar**: Modificar los datos de un usuario.
- **Eliminar**: Eliminar un usuario.

La API está construida utilizando **Node.js** y **Express** y gestiona los datos de los usuarios en memoria (puedes modificarla para usar una base de datos como MongoDB o MySQL si lo deseas).

---

## Requisitos

Para ejecutar este proyecto, necesitas tener instalados los siguientes programas:

- **Node.js** (versión 16 o superior)
- **npm**

---

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. **Clona el repositorio**:
    ```bash
    git clone https://github.com/MartinCouoh/CRUD-NODE.git
    ```

2. **Accede al directorio del proyecto**:
    ```bash
    cd tu-repositorio
    ```

3. **Instala las dependencias**:
    Si usas **npm**:
    ```bash
    npm install
    ```

---

## Uso

Una vez que hayas instalado las dependencias, puedes iniciar el servidor de desarrollo:

```bash
node app
