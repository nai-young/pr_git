**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

git reset --hard HEAD~1, ya que rehace el último cambio y altera el Working Copy.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

Utilizé git reflog para identificar el commit y git reset --hard <identificador> para volver al commit deshecho

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, por que tiene acceso al commit y no pierde el acceso a los anteriores

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, ya que el archivo esta siendo modificado en dos ramas diferentes

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, ya que ha sido Fast-Forward y no ha perdido acceso a los commits anteriores

**¿Qué comando o comandos utilizaste en el paso 25?**

git log --pretty=oneline --graph

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

No, porque master no tiene acceso a los commits en title

**¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD~1

**¿Qué comando o comandos utilizaste en el paso 28?**

Git merge --abort

**¿Qué comando o comandos utilizaste en el paso 29?**

Git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? 

Git reflog para identificar el commit del merge y git reset --hard <identificador>

- ¿Qué comando o comandos usaste en el paso 32?

Git log para buscar el commit inicial y git reset --hard <identificador> para volver

- ¿Qué comando o comandos usaste en el punto 33?

Git reflog para identificar el commit final y git reset --hard <identificador> para volver

