# onesaitplatform-revolution
Onesait Platform revolution es una iniciativa de MINSAIT  para activar al colectivo de desarrolladores de su plantilla mediante una competición consistente en 2 fases: una inicial que se desarrolla de forma individual y una  en equipos. 

## ¿Qué esperamos de ti?
Tan sólo queremos que nos hagas un Pull Request, para eso basta con que clones el repositorio, añadas un fichero .md con tu usuario de Minsait y dentro de él nos cuentes qué te parece la iniciativa y por qué participas en ella.

### Cómo hacer un Pull Request
En Git se trabaja siempre en local, con la copia del repositorio en nuestro ordenador. Pero el repositorio que tienes en local no debe ser un clon de aquel con el que deseas contribuir, sino un fork propio. A continuación te explicamos cómo hacer este proceso:

- Para hacer el fork del repositorio, haz clic en el botón **Fork** situado arriba a la derecha. Inmediatamente se creará en tu cuenta de GitHub un nuevo repositorio que es la copia de estado actual del repositorio original.
- Una vez tienes el respositorio creado en tu cuenta de GitHub, el siguiente paso es clonar dicho repositorio en tu equipo, para ello haz clic en el botón **Clone or download**, copia la URL y escribe en tu terminal el comando `git clone <URL>` sustituyendo `<URL>` por la URL que acabas de copiar.
- Al clonar el repositorio en tu equipo se habrá creado la carpeta **onesaitplatform-revolution** con el contenido del repositorio, dentro de esa carpeta crea el fichero `<tu-usuario-minssait>.md` y dentro de él cuéntanos qué te parece esta iniciativa y porqué participas.
- Una vez creado tu archivo es el momento de subirlo a tu repositorio de GitHub.
  
Para ello en tu terminal escribe:
- El comando `git status` y verás tu nuevo archivo. 
- Haz un `git add <file>` Siendo `<file>` la ruta del archivo. Con esto has añadido este archivo a tu próximo commit.
- Haz un `git commit -m "Añado mi fichero .md"`. Donde el texto entremcomillado va a ser la descripción de tu commit.
- Haz un `git push origin master` para subir al repositorio de tu usuario de GitHub el commit generado.

El siguiente paso es hacer la Pull Request al repositorio de onesaitplatform, para ello:
- En tu fork haz clic sobre el botón **New pull request** y automáticamente te saldrá una comparativa entre el repositorio original y el tuyo.
- Si estás de acuerdo con lo que quieres subir, haz clic sobre el botón `Create pull request`


