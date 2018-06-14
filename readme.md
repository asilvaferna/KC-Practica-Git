- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
`git reset —hard HEAD~1` Use `-—hard` para perder los cambios en el `working-copy `
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? `git reflog` para ver el commit deshecho y `git reset --hard 79ec56f` para volver al commit deshecho siendo 79ec56f el hash de ese commit
 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? No causó ningún conflicto ya que la rama `styled` ya tenía todo el historial de commits de master
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? Si, ya que estábamos escribiendo contenido en las mismas líneas.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? No, ya que las dos ramas formaban una lista y pudieron ser mergeadas con `fast-forward` sin problema
- ¿Qué comando o comandos utilizaste en el paso 25? `git graph` siendo `graph` un alias de `git log --graph --decorate --pretty=oneline `
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? Si, porque el directorio ya contenía todo el contenido de la rama master al ser creada a partir de esta.
- ¿Qué comando o comandos utilizaste en el paso 27? `git reset HEAD~1`
- ¿Qué comando o comandos utilizaste en el paso 28? `git checkout -- git-nuestro.md`
- ¿Qué comando o comandos utilizaste en el paso 29? `git branch -D title`
- ¿Qué comando o comandos utilizaste en el paso 30? `git reset --hard HEAD@{1}`
- ¿Qué comando o comandos usaste en el paso 32? `git reflog` para ver el hash del commit y `git reset —hard 91680ce` para ir al commit
- ¿Qué comando o comandos usaste en el punto 33? `git reflog` para ver el hash del commit y `git reset —hard b13a143` para ir al commit
