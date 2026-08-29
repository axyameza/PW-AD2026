<h1>Comandos Básicos de Git</h1>
<p>Guía rápida de los 20 comandos más utilizados en Git y sus descripciones.</p>

<ol>
  <li>
    git init: Inicializa un nuevo repositorio de Git en el directorio actual.
  </li>
  <li>
    git clone [URL]: Descarga y clona un repositorio remoto existente en tu máquina local.
  </li>
  <li>
    git status: Muestra el estado del directorio de trabajo y del área de preparación (staging area).
  </li>
  <li>
    git add [archivo]: Añade un archivo específico al área de preparación. Usa (git add .) para añadir todos los cambios.
  </li>
  <li>
    git commit -m "[mensaje]": Guarda los cambios preparados en el historial del repositorio con un mensaje descriptivo.
  </li>
  <li>
    git push origin [rama]: Sube los commits locales a la rama especificada en el repositorio remoto.
  </li>
  <li>
    git pull: Obtiene los últimos cambios del repositorio remoto y los fusiona con la rama actual.
  </li>
  <li>
    git branch: Lista todas las ramas locales. Usa git branch [nombre] para crear una nueva.
  </li>
  <li>
    git checkout [nombre-rama]: Cambia a la rama especificada. Con -b crea y cambia a la rama simultáneamente.
  </li>
  <li>
    git switch [nombre-rama]: Comando moderno para cambiar entre ramas (alternativa a checkout).
  </li>
  <li>
    git merge [nombre-rama]: Combina el historial de la rama especificada con la rama actual.
  </li>
  <li>
    git fetch: Descarga los cambios y ramas del repositorio remoto sin fusionarlos automáticamente.
  </li>
  <li>
    git log: Muestra el historial de commits realizados en el proyecto.
  </li>
  <li>
    git diff: Muestra las diferencias entre los cambios no preparados y la última versión guardada.
  </li>
  <li>
    git stash: Guarda temporalmente los cambios no confirmados para dejar el directorio de trabajo limpio.
  </li>
  <li>
    git stash pop: Recupera los cambios guardados previamente con git stash y los reaplica.
  </li>
  <li>
    git reset [archivo]: Elimina un archivo del área de preparación sin borrar los cambios del código.
  </li>
  <li>
    git revert [commit-hash]: Crea un nuevo commit que deshace los cambios realizados en un commit anterior.
  </li>
  <li>
    git remote -v: Lista los repositorios remotos vinculados al proyecto local y sus URLs.
  </li>
  <li>
    git config --global user.name "[nombre]": Establece el nombre de usuario global que se asociará a tus commits.
  </li>
</ol>
