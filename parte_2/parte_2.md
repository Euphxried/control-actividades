1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.

R=
- Fork: Es para crear una copia del repositorio ajeno
- Clone: Clona de forma local el repositorio del otro desarrollador
- Branch: Ves en que rama se van a hacer los cambios
- Modificar: Modificas lo que quieras del proyecto
- Add: Añadir a git los archivos con los cambios hechos
- Status: Ver qué archivos faltan por agregar o si ya están todos
- Review: Verificas que los cambios se hayan hecho correctamente
- Commit: Se registran los cambios y se preparan para subirse a la nube
- Push: Los cambios hechos se suben al repositorio propio en la nube
- Pull Request: Se le manda una solicitud al otro de desarrollador para que acepte los cambios hechos
- Merge: Se mezclan los avances del desarrollador y los propios en uno solo

-------------------------------------------------------------------------------------------------------------------------

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.

R= No es correcta, ya que Clone se encarga de descargar el repositorio al almacenamiento local mientras que
   Fork se encarga de clonar ese mismo repositorio pero en la nube

-------------------------------------------------------------------------------------------------------------------------

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

R= Debe haber un git add entre la modificación y el commit, ya que si no no se detectará ningún cambio

-------------------------------------------------------------------------------------------------------------------------

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

R= No se debe hacer otro pull request ya que el aporte fue aceptado solo se necesita hacer unos cuantos cambios

-------------------------------------------------------------------------------------------------------------------------

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

R= Porque el repositorio está en la nube y los cambios se hicieron ahí mismo, para tenerlos de manera local
   se debe hacer otro Clone

-------------------------------------------------------------------------------------------------------------------------

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.

R= Usaria de nuevo otro Fork, se actualizaría el repositorio original y el Sync Fork es para fusionar 
   repositorios en github en la nube y el git pull para hacerlo de forma local