**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
>`git reset head~1 --hard` porque es el paso justo anterior y es la opción más cómoda.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
>`git reflog` Para listar todos lo movimientos del head y localizar donde esta el commit a restaurar
`git reset 25eaee7 --hard` Restauro el commit con los cambios que quiero recuperar

**El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?**
> No, Porque la rama *styled* ha evolucionado desde *main* por lo que ya de por si integra todos los commits de esta rama, que no ha seguido evolucionando despues de la creacion de la rama *styled*

**El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?**
>Si, Porque en este caso ambas ramas si han evolucionado en paralelo y hay líneas en las que hay cambios distintos en cada rama 

**El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?**
>no, pq no las ramas no han seguido evolucionando por separado, la unica que ha evolucionado es *styled* y con este merge *main* absorve los commits que no tiene en esta rama

**¿Qué comando o comandos utilizaste en el paso 25?**
> `git log --graph --oneline`

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
>Si, porque no se generan conflictos en el merge

**¿Qué comando o comandos utilizaste en el paso 27?**
>`git reset head~1`

**¿Qué comando o comandos utilizaste en el paso 28?**
>`git restore git-nuestro.md`

**¿Qué comando o comandos utilizaste en el paso 29?**
>`git branch title -D`

**¿Qué comando o comandos utilizaste en el paso 30?**
>`git reset 7a87f7f`

**¿Qué comando o comandos usaste en el paso 32?**
>`git reflog` 
`git reset e82cee1`

**¿Qué comando o comandos usaste en el punto 33?**
>`git reflog`
` git reset da29f15`
