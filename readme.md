- �Qu� comando utilizaste en el paso 11? �Por qu�?

git reset --hard HEAD~1 para volver al commit anterior y dejando el working area igual que estaba en ese momento.

- �Qu� comando o comandos utilizaste en el paso 12? �Por qu�?

git reflog para comprobar la referencia y $ git reset --hard 904deaf para volver a al estado original.

- El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?

No, porque la rama "styled" compartia los mismos archivos y las mismas lineas que "master" m�s sus modificaciones propias.

- El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?

Si, porque los archivos de las dos ramas tenian distinta informaci�n en todas las lineas.

- El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?

No, porque previamente (en el paso 13) ya se habia hecho un merge de master a styled.

- �Qu� comando o comandos utilizaste en el paso 25?

git graph, porque previamente cre� ese alias para evitar teclear el comando completo: git log --graph --decorate --pretty=oneline

- El merge del paso 26, �Podr�a ser fast forward? �Por qu�?

Si, porque al haber sido creada desde el ultimo commit de la rama "master" ya tenia acceso a todo lo recogido en esa rama.

- �Qu� comando o comandos utilizaste en el paso 27?

git reset HEAD~1

- �Qu� comando o comandos utilizaste en el paso 28?

git reset --hard a80a02d

- �Qu� comando o comandos utilizaste en el paso 29?

git branch -D title

- �Qu� comando o comandos utilizaste en el paso 30?

git reset --hard 5555a5f

- �Qu� comando o comandos usaste en el paso 32?

git reset --hard 79c9c15

- �Qu� comando o comandos usaste en el punto 33?

git reset --hard 5555a5f