# Práctica GIT

### Martínez Pitarch, Alicia

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
`git reset --hard HEAD~1`

Porque pide deshacer todos los cambios realizados en el working copy, es decir, "perderlo todo".

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
`git reflog`
`git rest --hard <HASH>`

Para volver al commit identificado e incorporar los cambios a la rama activa.
**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

El merge no es posible, ya que styled no puede absorber a master, porque el commit en el que está la rama master es el commit ancestro, por lo que habría que hacer el commit desde master.
**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, porque en ambas ramas hay modificaciones en el archivo don-quijote.md, por lo que git no sabía con cuál quedarse. 
**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, porque la rama styled ya incorpora en sus commits los cambios de master, por lo que puede realizar un merge fast-forward.
**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`
**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, porque master es el padre de title, por lo que al absorber title no prescribe los datos que ya contiene, así que no crea conflicto.
**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD`

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout don-quijote.md`

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`
**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`
`git reset --hard <HASH>`
**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog` `git checkout <HASH>`
**13. ¿Qué comando o comandos usaste en el punto 33?**

`git checkout <HASH>`

