# Sistema de Login y Registro Prueba Tecnica Ulern

Este proyecto implementa un sistema de login y registro utilizando Laravel 11, Vue 3, TailwindCSS y SQLite como base de datos, como se indica en las introducciones del enunciado de la prueba tecnica de Ulern.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Tecnologías](#tecnologías)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)

## Descripción

Este proyecto permite a los usuarios registrarse, iniciar sesión y ver sus datos personales. El sistema se implementó siguiendo los requisitos de la prueba técnica.

## Tecnologías

Este proyecto utiliza las siguientes tecnologías:

- **Laravel 11**
- **Vue 3**
- **TailwindCSS**
- **SQLite**

## Requisitos

Antes de comenzar, asegúrate de tener lo siguiente instalado:

- **PHP** 8.0 o superior
- **Composer** (para instalar dependencias de PHP)
- **Node.js** y **npm** o **yarn** (para las dependencias de frontend)
- **SQLite** (base de datos)

## Instalación

Sigue los pasos a continuación para instalar y ejecutar el proyecto localmente.

### 1. Clonar el repositorio

Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/nicolasanhueza/Prueba-tecnica-Ulern.git
cd Prueba-tecnica-Ulern
```

### 2. Instalar dependencias

Ejecuta el siguiente comando para instalar las dependencias de Laravel utilizando Composer:

```bash
composer install
```

### 3. Configurar variables de entorno

Copia el archivo .env.example y renómbralo a .env:

```bash
cp .env.example .env
```

Abre el archivo .env y configura la conexión a la base de datos SQLite:

```bash
DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=laravel
# DB_USERNAME=root
# DB_PASSWORD=
```

### 4. Ejecuta las migraciones

Ejecuta las migraciones para crear las tablas en la base de datos:

```bash
php artisan migrate
```

### 5. Instalar las dependencias de frontend

Instala las dependencias de frontend utilizando npm:

```bash
npm install
```

### 6. Compilar los archivos de frontend

Ejecuta el siguiente comando para compilar los archivos de frontend

```bash
npm run dev
```

### 7. Iniciar el servidor

Inicia el servidor de desarrollo de Laravel:

```bash
php artisan serve
```

## Uso

dirigete a http://localhost:8000 para acceder al sitio web. Ahi se mostrara la pagina con dos botones para iniciar sesión y registrarse.

