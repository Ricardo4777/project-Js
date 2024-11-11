# Proyecto en JavaScript con Node.js

Este repositorio contiene un proyecto en JavaScript utilizando Node.js, listo para ser ejecutado en tu máquina local o en un contenedor Docker.

## Requisitos Previos

Antes de iniciar, asegúrate de tener instalados los siguientes programas:

- **[Node.js](https://nodejs.org/en/download/)**: Necesario para ejecutar la aplicación.
- **[Git](https://git-scm.com/book/es/v2/Comenzando-Instalando-Git)**: Para clonar este repositorio.
- **[Docker](https://www.docker.com/get-started)**: Si deseas ejecutar el proyecto en un contenedor Docker.

Para verificar la instalación de Node.js y Git, ejecuta estos comandos en la terminal:

```bash
node --version
git --version


Primero, clona este repositorio en tu máquina local usando Git:

```bash
git clone https://github.com/tu-usuario/tu-proyecto-node.git
cd tu-proyecto-node

4 Construir la Imagen de Docker
Primero, construye la imagen Docker con el siguiente comando:

docker build -t js-andy .

Ejecutar el Contenedor Docker
Una vez que la imagen esté construida, ejecuta el contenedor con este comando:

docker run -p 8082:8082 js-andy
