# DWES Trabajo Primer Trimestre

Este es el espacio para el trabajo del primer trimestre de la asignatura de Desarrollo Web en Entorno Servidor.

Será un proyecto individual de una aplicación con **Django**    

Elige un tema que te guste y describe bien los objetivos de tu web en el fichero `README.md` de tu repositorio.

* Trabaja en una rama `develop` y haz un `merge` a `main` cuando esté todo listo o necesites ayuda.

## PASOS

* Crea el proyecto. Crea la aplicación y actívala en el fichero `settings.py` de tu proyecto.
* Crea el fichero  `models.py` con las clases, atributos y métodos necesarios. Documenta bien la clase y crea como mínimo el método `__str__` (1 pto)
* Configura el archivo `admin.py` para poder editar los modelos desde el **admin**. (1 pto). Modifica el `list_display` para que se vean los campos que consideres necesarios. Añade un `list_filter` para filtrar por algún campo y haz que se puedan hacer búsquedas también. (1 pto)
* Crea las vistas necesarias para que el usuario pueda ver la información de la web. Al menos una vista de listado y una vista de detalle (1 pto). La vista de listado estará paginada y cada elemento tendrá un enlace a la url de su detalle.
* Crea las plantillas necesarias. Al menos una plantilla **base.html** una plantilla **nav.html** para la navegación y las plantillas que necesiten tus vistas. (2 pto)
* Introduce datos en la base de datos a través del **admin** y crea un volcado de datos de prueba (**fixtures**) (1 pto)
* Crea un fichero `urls.py` en la aplicación y configúralo desde las urls del proyecto. (1 pto)
* Crea una página de contacto con un formulario que envíe un correo. Adapta el formulario a las necesidades de tu proyecto. (1 pto)
* Crea vistas que permitan crear, modificar y eliminar elementos de tu aplicación. (1 pto)

## Recuerda
Documenta bien las vistas y los modelos.

En el documento README.md tiene que quedar claro cómo se instala la aplicación, cómo se cargan los datos de prueba y cómo se usa. 