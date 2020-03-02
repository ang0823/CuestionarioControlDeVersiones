# Preguntas

1. ¿Qué es un sistema de control de versiones?
Un control de versiones es un sistema que registra los cambios realizados en un artefacto o conjunto de artefactos a lo largo del tiempo, 
de modo que puedas recuperar versiones específicas más adelante. 

2. ¿Cuáles son los objetivos de un sistema de control de versiones?
-dar seguimientos a todos los canmbios
-mantener una copia de todos los cambios que se hagan al código de nuestro proyecto

3. ¿Cuáles son las pautas para controlar los cambios de diseño?

4. ¿Qué es un repositorio?
Es el lugar en que el CVS almacena y da seguimiento a todos los cambios que se hagan el los archivos.

5. ¿Qué se debe almacenar en un repositorio?
-todo lo que se necesite para trabajar en el proyecto, todo lo que es esencial modificar, mejorar o crear nuevas versiones de ello.
--codigo fuente
--archivos de muestra de configuracion
--documentacion
--imagenes que sean usada en la aplicacion
--las pruebas de unidad

6. ¿Cómo se puede determinar que incluir en un repositorio?
-haciendonos las pregunta "¿Si no tuviera X, podria continuar con mi trabajo en este proyecto?". Si se responde que no, entonces sí se debe de incluir en el repositorio. La excepcion es no incluir la herramientas con las cuales es forzoso trabajar.

7. ¿Qué es un *Working Tree*?
-Es la vista actual dentro del repositorio. Contiene todos los archivos del proyecto: el codigo fuente, los archivos de construccion, pruebas unitaria, etcetera.

Es la vista actual del flujo de cambios y/o modificaciones de archivos dentro de nuestro proyecto en el repositorio.

8. ¿Qué hace un *commit*?
--agrega una nueva version al repositorio y almacena el mensaje de log que explica el cambio que se hizo.

9. ¿Qué ocurre cuando se hace *push*?
--Sube los cambios a un repositorio remoto, de modo que esos cambios se puedan compartir con otros desarrolladores para que tengan acceso a ellos.

Se utiliza para subir confirmaciones de cambios realizados en un rama local a una rama remota

10. ¿Qué ocurre cuando se hace *fetch*?
--Crea una copia de los cambios en el repositorio remoto.

Contrario a push, se obtienen los cambios de un repositorio remoto.

11. ¿Qué es un *branch* o rama?
--es el seguimiento de los cambios realizados en el contenido separado por otras ramas para que se puedan crear otras versiones alternativas. Se ocupan para desarrollar funcionalidades aisladas unas de otras.

12. ¿Qué es un *merge*?
--Une la copia de los cambios en el repositorio remoto con mi repositorio local.

Proceso de unir dos ramas; estos cambios deben ser aprovados por los colaboradores.

13. ¿Qué es un *strict locking*?
--se pide al repositorio para hacer cambios a un artefacto, evitando cambios simultaneos.

14. ¿Qué es un *optimistic locking*?
--permite que varios desarrolladores trabajen en el mismo codigo y los mismos archivos con el supuesto de que la mayoria de la veces sus cambios no entraran en conflictos.

<!-- 15. ¿Con qué comandos se configuran el nombre el correo para git?

16. ¿Qué es el archivo *.gitignore*?

17. ¿Qué debería poner en el archivo *.gitignore*? -->