1 Que comando utilizaste en el paso 11? Por que?

* utilice git reset --hard HEAD~1 porque necesito mover el puntero head 
ystyled un commit atras y ademas quitar del staging area los cambios 
realizados en git-nuestro. Lo anterior lo puedo hacer con git reset HEAD-1 
y git restore por  aparte. Sin embargo, uso git reset --hard para hacer 
los dos comandos en uno.

2 Que comando o comandos utilizaste en el paso 12? Por que?

* Utilice git reset --hard identificador_commit. Porque de esta forma 
puedo mover el puntero head y styled a otro commit y con --hard me aseguro 
de traer los cambios de vuelta. 

3 El merge del paso 13, causo algun conflicto? Por que?

* No causo ningun conflicto. no se agregaron cambios que se sobrepusieran 
a los existentes

4 El merge del paso 19, causo algun conflicto? Por que?

* Si, se genero un conflicto porque los cambios se sobreponian a los 
existentes.

5 El merge del paso 21, causo algun conflicto? Por que?

* No genero ningun conflicto porque no se sobreponen los cambios a los 
existentes.

6 Que comando o comandos utilizaste en el paso 25?

* git log --graph

7 El merge del paso 26, podria ser fast forward? Por que?

* Si, porque la rama main no tiene commits delante. 
commit existente

8 Que comando o comandos utilizaste en el paso 27?

* git reset HEAD~1

9 Que comando o comandos utilizaste en el paso 28?

* git reset --hard identificador_commit

10 Que comando o comandos utilizaste en el paso 29?

* git branch -D title

11 Que comando o comandos utilizaste en el paso 30?

* git reflog
   git reset --hard identificador_commit

12 Que comando o comandos utilizaste en el paso 32?

* git reflog
   git reset identificador_commit

13 Que comando o comandos utilizaste en el paso 33?

* git reflog
   git reset identificador_commit
