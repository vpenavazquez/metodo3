## Método 3: Fork y Clonar (Bifurcación y Colaboración)

Este método es el procedimiento estándar para colaborar en proyectos Open Source o entregar tareas. Consiste en crear una bifurcación (*Fork*) del repositorio original en mi propia cuenta de GitHub, manteniendo un vínculo con el proyecto original.

### Pasos realizados:

1.  **Bifurcación en GitHub (Fork):**
    * Accedí al repositorio original en GitHub y utilicé el botón **Fork**. Esto generó una copia exacta del proyecto dentro de mi cuenta de usuario, pero manteniendo un enlace interno con el repositorio de *Daniel Castelao*.

2.  **Clonado del Fork en PyCharm:**
    * En lugar de clonar el original, cloné **mi propia versión bifurcada** (`https://github.com/MI_USUARIO/pruebasReadme.git`) en PyCharm.

3.  **Flujo de Trabajo:**
    * Al trabajar de esta manera, el remoto `origin` apunta automáticamente a mi repositorio bifurcado.
    * Esto me permite subir cambios (*Push*) a mi cuenta sin permisos en el repositorio original y, si fuera necesario, solicitar la incorporación de mis cambios al original mediante un *Pull Request*.