# ¿Cómo contribuir?

Para contribuir con este repositorio puede seguir el proceso de **Pull Request**
que se describe a continuación. En caso de no saber manejar la herramienta `git`
pero desea agregar una comunidad en este listado solicite asistencia en el chat
de [OpenVE](https://t.me/openve).

## Proceso de Pull Request

1. Proceda a crear un fork del repositorio desde la página del repo en
   [Github](https://github.com/OpenVE/comunidades-en-telegram). (botón en la
   esquina superior derecha)
2. Clone su fork del repositorio en su computadora
   `git clone git@github.com:(tu usuario)/comunidades-en-telegram.git`. O
   dependiendo de su configuración deberá usar
   `git clone https://github.com/(tu usuario)/comunidades-en-telegram.git`.
3. Ingrese a su repositorio (`cd comunidades-en-telegram`) y proceda a agregar
   el repositorio original como `upstream` para que pueda actualizar su
   contenido respecto al original para futuras actualizacione (`git remote add upstream https://github.com/OpenVE/comunidades-en-telegram.git`).
4. Traiga los ultimos cambios del repositorio original a su fork (`git fetch upstream`).
5. Observe su copia local de la rama `master` (`git checkout master`).
6. Una los cambios del repositorio original `upstream/master` a su rama local
   `master` (`git merge upstream/master`).
7. Repita los pasos 4, 5 y 6 para mantener su repositorio actualizado respecto
   al original.
8. Al agregar un nuevo grupo se debe tener en cuenta que todos los campos son requeridos, siguiendo el siguiente formato:
    - Comunidad: Nombre de la comunidad.
    - Administrador(es): Usuario de los administradores separados por un guión (-), con por lo menos 1 admin.
    - Link: Enlace al grupo de telegram de la forma `https://t.me/`.
9. Cuando complete sus cambios, subalos a su copia del repositorio (`git push origin master`).
10. Proceda a realizar crear un `Pull Request` para solicitar agregar sus cambios al repositorio original. 

## Sobre los derechos de autor

Al contribuir con este repositorio usted está cediendo su trabajo como
[dominio público](https://creativecommons.org/publicdomain/mark/1.0/deed.es).
