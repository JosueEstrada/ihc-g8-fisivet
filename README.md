# Proyecto del curso Interacción Hombre Computador - Grupo 8

Nombre del proyecto: FISIVET

Este es el readme para el desarrollo del sitio web de veterinaria con un sistema de registro para usuarios y mascotas, que incluye estadísticas y perfiles. El proyecto utiliza el framework Laravel para el backend y Vue.js para el frontend.

## Requisitos previos
Antes de comenzar, asegúrate de tener instalados los siguientes requisitos en tu entorno de desarrollo:

- PHP 7.4 o superior
- Composer
- Node.js y npm
- Laravel CLI (opcional, pero recomendado)

## Instalación
1. Clona el repositorio del proyecto desde GitHub.
   ```
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Accede al directorio del proyecto.
   ```
   cd veterinaria-web
   ```
3. Instala las dependencias de PHP utilizando Composer.
   ```
   composer install
   ```
4. Instala las dependencias de JavaScript utilizando npm.
   ```
   npm install
   ```
5. Crea una copia del archivo `.env.example` y renómbrala como `.env`. Luego, genera una clave de aplicación.
   ```
   cp .env.example .env
   php artisan key:generate
   ```
6. Configura las variables de entorno en el archivo `.env` según la configuración de tu entorno.

7. Crea la base de datos para el proyecto y actualiza el archivo `.env` con los detalles de la conexión a la base de datos.

8. Ejecuta las migraciones para crear las tablas en la base de datos.
   ```
   php artisan migrate
   ```
9. Compila los assets de JavaScript y CSS.
   ```
   npm run dev
   ```
10. Inicia el servidor de desarrollo.
    ```
    php artisan serve
    ```
El servidor se ejecutará en http://localhost:8000.

## Uso
Una vez que el servidor esté en funcionamiento, puedes acceder al sitio web de veterinaria a través de tu navegador web.

El sitio web permite a los usuarios registrarse y crear perfiles para sus mascotas. También se incluye una funcionalidad de estadísticas que muestra información relevante sobre las mascotas registradas.

Explora las diferentes secciones del sitio web para acceder a las funciones de registro de usuarios y mascotas, así como para visualizar las estadísticas disponibles.

## Contribución
Si deseas contribuir a este proyecto, sigue los pasos a continuación:

1. Crea una rama de desarrollo.
   ```
   git checkout -b feature/nueva-funcionalidad
   ```
2. Realiza los cambios y mejoras necesarias.
3. Realiza commits con mensajes descriptivos.
   ```
   git commit -m "Agrega la nueva funcionalidad"
   ```
4. Sube los cambios a tu repositorio remoto.
   ```
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un pull request en el repositorio original.

## Soporte
Si tienes alguna pregunta o encuentras algún problema, puedes abrir un issue en el repositorio del proyecto en GitHub.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más información.
