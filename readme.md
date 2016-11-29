- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1 para volver al commit anterior y dejando el working area igual que estaba en ese momento.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog para comprobar la referencia y $ git reset --hard 904deaf para volver a al estado original.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, porque la rama "styled" compartia los mismos archivos y las mismas lineas que "master" más sus modificaciones propias.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, porque los archivos de las dos ramas tenian distinta información en todas las lineas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, porque previamente (en el paso 13) ya se habia hecho un merge de master a styled.

- ¿Qué comando o comandos utilizaste en el paso 25?

git graph, porque previamente creé ese alias para evitar teclear el comando completo: git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, porque al haber sido creada desde el ultimo commit de la rama "master" ya tenia acceso a todo lo recogido en esa rama.

- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?

git reset --hard a80a02d

- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

git reset --hard 5555a5f

- ¿Qué comando o comandos usaste en el paso 32?

git reset --hard 79c9c15

- ¿Qué comando o comandos usaste en el punto 33?

git reset --hard 5555a5f