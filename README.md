# plantilla-para-TPs

_Un ejemplo de cómo crear un proyecto_

## Instalación

Clonar este repo:

    $ git clone https://gitlab.com/untref-ayp2-docentes/plantilla-para-tps


## Uso

Ejecutar el proyecto:

    $ gradle run

Ejecutar los tests del proyecto (van a fallar hasta que los editen):

    $ gradle test

Ejecutar los tests del proyecto con mayor detalle (van a fallar hasta que los editen):

    $ gradle test --info


Más opciones:

    $ gradle tasks

## Configuración para uso remoto

El remoto por defecto ("origin"), apunta al repo de los docentes.

    % git remote -v
    origin	git@gitlab.com:untref-ayp2-docentes/plantilla-para-tps (fetch)
    origin	git@gitlab.com:untref-ayp2-docentes/plantilla-para-tps (push)

El repo de los docentes sólo es modificable si se es miembro del grupo de docentes. Si se desea publicar el repositorio local en el grupo de GitLab, deben modificarse los remotos para que apunten a la versión remota del alumno, previamente creado en GitLab.

    $ git remote set-url origin https://gitlab.com//untref-ayp2-estudiantes/tp1-grupo-<NN>-<nombre_del_grupo>-turno-{mar_jue,mie_vie}
    // NN: número del grupo de la forma "03", "04", "10" ...
    // URL de ejemplo:
    // https://gitlab.com/untref-ayp2-estudiantes/tp1-grupo-03-pachamama-turno-mar_jue


## Opciones

FIXME: listar opciones aceptadas por esta aplicación.

## Ejemplos

...

## Bugs

...

## (Cualquier Otra Sección Que Puedas Considerar Útil)


## Cómo se creó esta plantilla

Inicializar un repositorio git y entrar en su directorio:

    $ git init <nombre-del-proyecto>

    $ cd <nombre-del-proyecto>


Crear el proyecto con Gradle:

    $ gradle init --type java-application


Agregar el README:

    $ touch README.md
    # (Luego, agregarle contenido al archivo)


Agregar el .gitignore:

    $ touch .gitignore
    # (Luego, agregarle contenido al archivo)

## Renuncia de garantía

Este programa se distribuye con el objetivo de que sea útil, pero SIN NINGUNA GARANTÍA; sin siquiera la garantía implícita de COMERCIALIZACIÓN o ADECUACIÓN PARA UN PROPÓSITO PARTICULAR.
