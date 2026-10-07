1. Analiza

git status = muestra qué archivos están registrados en el git y cuales no 
git add README.md = registra un usuario en el git
git commit -m "Actualiza documentación" = nombra el cambio que se hará al subir los archivos registrados
git push = sube los cambios hechos a la nube

Explica qué ocurre en cada instrucción.

-------------------------------------------------------------------------------------------------------------------------

2. Identifica qué falta

Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push

Indica qué operación falta y explica su función.

R= Falta el "git -m commit", ya que es el que se encarga de registrar y nombrar los cambios en sí

--------------------------------------------------------

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local

Indica qué operación utilizarías y explica por qué.

R= Falta el "git remote add origin", ya que es el que liga el repositorio local con el hecho en la nube

--------------------------------------------------------

Caso C

Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado

Indica qué operación utilizarías y explica por qué.

R= Falta el "git pull", ya que es el que se encarga de descargar y actualizar el repositorio local de acuerdo con el de la nube