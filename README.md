# Proyecto en NestJS
Este es un proyecto desarrollado con NestJS, un framework para construir aplicaciones Node.js eficientes y escalables. En este README se describen los pasos necesarios para instalar y ejecutar el proyecto en tu máquina local.

# Requisitos previos
Antes de comenzar, asegúrate de tener instalados los siguientes programas en tu máquina:

Node.js (versión 14 o superior)
Puedes descargarlo desde aquí.

npm (que generalmente se instala junto con Node.js) o Yarn.

Nest CLI (opcional, si deseas usar comandos específicos de NestJS)
Puedes instalarlo globalmente con el siguiente comando:

bash
Copiar código
npm install -g @nestjs/cli
Clonar el repositorio
Primero, clona este repositorio en tu máquina local. Abre la terminal y ejecuta:

bash
Copiar código
git clone https://github.com/Juandavid08/proceso_pagos.git



# Instalación de dependencias
Navega al directorio del proyecto e instala las dependencias:

bash
Copiar código
cd nombre-del-repositorio
npm install


bash
Copiar código
npm run start
O con Yarn:

Por defecto, el proyecto se ejecutará en http://localhost:3000.

Modo de desarrollo
Si deseas ejecutar el proyecto en modo de desarrollo (con recarga automática), puedes usar:

bash
Copiar código
npm run start:dev
O con Yarn:

bash
Copiar código
yarn start:dev
Este comando activa el modo --watch, que recompila y recarga automáticamente el servidor cuando realizas cambios en el código.

## Estructura del Proyecto
La estructura del proyecto está organizada de la siguiente manera:

│
├── src/                # Código fuente de NestJS
│   ├── app.controller.ts  # Controlador principal
│   ├── app.module.ts      # Módulo principal
│   ├── app.service.ts     # Servicio principal
│   └── ...               # Otros controladores, servicios, módulos, etc.
├── test/                # Archivos de prueba
├── node_modules/        # Dependencias del proyecto
├── .env                 # Variables de entorno (no olvides crear este archivo)
├── .gitignore           # Archivos y directorios que git debe ignorar
├── package.json         # Información sobre el proyecto y dependencias
├── tsconfig.json        # Configuración de TypeScript
├── README.md            # Este archivo
└── yarn.lock / package-lock.json  # Bloqueo de dependencias