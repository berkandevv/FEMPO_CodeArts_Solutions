![Image](https://github.com/user-attachments/assets/ab43bd32-33d6-47c2-8518-a1a855f912bd)

# Estructura de un Proyecto Symfony

## Carpetas principales

### `assets/`
Contiene archivos frontend como CSS, JavaScript o imágenes, que pueden ser procesados con herramientas como Webpack Encore.

### `bin/`
Archivos ejecutables, como `console`, que es la CLI de Symfony para ejecutar comandos.

### `config/`
Archivos de configuración del proyecto (servicios, enrutamiento, paquetes, etc.).

### `migrations/`
Contiene las migraciones de la base de datos generadas con Doctrine.

### `public/`
Es el punto de entrada de la aplicación. Aquí se encuentra `index.php` y otros recursos públicos (CSS, imágenes, JS compilados, etc.).

### `src/`
Código fuente de la aplicación. Contiene subcarpetas como:
- **`Controller/`**: Controladores que manejan las peticiones HTTP.
- **`Entity/`**: Entidades de Doctrine que representan las tablas de la base de datos.
- **`Repository/`**: Clases que gestionan la interacción con la base de datos.
- **`templates/`**: Plantillas Twig utilizadas en las vistas.

### `tests/`
Pruebas automatizadas de la aplicación.

### `translations/`
Archivos de traducción si la aplicación es multilenguaje.

### `var/`
Archivos temporales y de caché generados por Symfony.

### `vendor/`
Librerías externas gestionadas por Composer.

---

## Archivos clave

### `.env, .env.dev, .env.test`
Variables de entorno según el entorno de ejecución.

### `.gitignore`
Archivos y carpetas que Git debe ignorar.

### `composer.json y composer.lock`
Definen las dependencias PHP del proyecto.

### `symfony.lock`
Indica qué paquetes están bloqueados en el proyecto.

### `phpunit.xml.dist`
Configuración para ejecutar pruebas con PHPUnit.
