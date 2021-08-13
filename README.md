# Descripción del proyecto

El proyecto consiste en desarrollar una red social básica. Podremos crear posts y comentar los posts de otros usuarios.
    

## Inicializar proyecto

*   Instalación de Homestead o Docker

    Se recomienda consultar la [documentación oficial de Laravel](https://laravel.com), también puede consultar otras fuentes.

*   Clonar e instalar proyecto desde Github

    Deberá crear un fork del proyecto ([link](https://github.com/Kemok-Repos/laravel-ejercicio)) a un repositorio personal que deberá configurar como público, seguido debe clonar el proyecto para luego instalar la aplicación. A partir de este momento se espera que utilice git para manejar el código del proyecto.


## Dependencias

*    Utilizaremos [laravel-permission](https://github.com/spatie/laravel-permission) para el manejo de roles y permisos. Es el único paquete solicitado en este ejercicio, queda a discreción el uso de paquetes adicionales.

*   Utilice vistas y componentes de la plantilla a su elección para el frontend.


## Requerimientos

*   Los usuarios se registran proporcionando únicamente su correo electrónico y contraseña.
*   Cada usuario tiene un perfil en el que puede editar:
    *   Nombre completo
    *   Fecha de nacimiento 
    *   Nacionalidad
*   La lista de países para la nacionalidad del usuario debe mostrarse en un tag select utilizando a discreción una librería de JS que permita la búsqueda del país. La búsqueda debe realizarse por ajax o axios (no cargar a la vista todos los países).
*   Los usuarios pueden crear y ver posts en el feed.
*   Los usuarios únicamente pueden editar y/o eliminar posts creados por ellos mismos.
*   En el feed los post deben mostrarse ordenados por fecha y hora.
*   Los comentarios son un recurso anidado de los posts y ambos pertenecer a un usuario. (ej: dominio.test/post/10/comentario/20)
*   Crear un usuario super-admin (utilizando laravel-permission), este tiene permisos para realizar cualquier acción en posts o comentarios de cualquier usuario. Crear el rol y permisos pertinentes para cada acción del CRUD.
*   Para cada modelo, crear su propio factory para llenar con datos dummies la base de datos utilizando seeders.
*   Crear tests unitarios en phpunit. (trate de abarcar un 80% del código)

## Suman puntos a tu favor

*   Uso de estándares de programación PSR
*   Manejo de variables de entorno
*   Uso de principios SOLID
*   Patrones de diseño
*   Uso correcto de GIT
*   Aplicación de algún workflow de Git
*   Despliegue de aplicación en plataforma online


Al finalizar, envíe el link de su repositorio para la revisión del mismo al correo luis@kemok.io
