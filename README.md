# README practicaGit

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset —-hard HEAD~1` 

Con HEAD~1 deshago el último commit y con --hard hago que el *working copy* quede vacío.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` 

`git reset --hard bd67dfc`

Con el primer comando localizo la referencia del commit y con el segundo voy a el modificando el working copy.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causo conflicto puesto que la rama styled contenia a master.

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si causó conflicto pues estaban modificadas las mismas lineas del mismo documento en cada rama.

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causó conflicto, pues se hizo un *merge fast forward* avanzando master a styled.

**¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph --decorate --pretty=oneline`

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si podría ser *fast-forward* pues en vez de haber añadido un commit podríamos haber avanzado el puntero master a title.

**¿Qué comando o comandos utilizaste en el paso 27?** 

`git reset HEAD~1` 

Con esto desago el merge y mantengo los cambios en el *Working Copy*. 

**¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- git-nuestro.md`

**¿Qué comando o comandos utilizaste en el paso 29?** 

`git branch -D title`

**¿Qué comando o comandos utilizaste en el paso 30?** 

`git reflog` 

`git reset --hard 8a25503`

Con el primer comando localizo el merge y con el segundo voy a el modificando el *working copy*.

**¿Qué comando o comandos usaste en el paso 32?**

`git reflog`

`git reset --hard 27c0cb6`

Con el primer comando localizo el commit inicial y con el segundo voy a el modificando el *working copy*.

**¿Qué comando o comandos usaste en el punto 33?**

`git reflog`

`git reset --hard b502a39`

Con el primer comando localizo el estado final y con el segundo voy a el modificando el *working copy*.
