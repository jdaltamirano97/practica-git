- Que comando utilizaste en el paso 11? Por que?
R/ git reset --hard HEAD~1 - porque necesito mover el puntero head y 
styled un commit atras y ademas quitar del staging area los cambios 
realizados en git-nuestro. Lo anterior lo puedo hacer con git reset HEAD~1 
y git restore por  aparte. Sin embargo, uso git reset --hard para hacer 
los dos comandos en uno.

- Que comando o comandos utilizaste en el paso 12? Por que?
R/ Utilice git reset --hard identificador_commit. Porque de esta forma 
puedo mover el puntero head y styled a otro commit y con --hard me aseguro 
de traer los cambios de vuelta. 

- El merge del paso 13, causo algun conflicto? Por que?
R/ No causo ningun conflicto. no se agregaron cambios que se sobrepusieran 
a los existentes

- El merge del paso 19, causo algun conflicto? Por que?
R/ Si, se genero un conflicto porque los cambios se sobreponian a los 
existentes.

- El merge del paso 21, causo algun conflicto? Por que?
R/ No genero ningun conflicto porque no se sobreponen los cambios a los 
existentes.

- Que comando o comandos utilizaste en el paso 25?
R/ git log --graph

- El merge del paso 26, podria ser fast forward? Por que?
R/ Si, porque la rama main no tiene commits delante. 
commit existente

- Que comando o comandos utilizaste en el paso 27?
R/ git reset HEAD~1

- Que comando o comandos utilizaste en el paso 28?
R/ git reset --hard identificador_commit

- Que comando o comandos utilizaste en el paso 29?
R/ git branch -D title

- Que comando o comandos utilizaste en el paso 30?
R/ git reflog
   git reset --hard identificador_commit

- Que comando o comandos utilizaste en el paso 32?
R/ git reflog
   git reset identificador_commit

- Que comando o comandos utilizaste en el paso 33?
R/ git reflog
   git reset identificador_commit
