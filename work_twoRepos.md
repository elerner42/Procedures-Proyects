# Pull, Push a dos repos al mismo tiempo:

repo 1 -> github <br>
repo 2 -> git de 42 <br>

  1. Add new repo >>>                     $ git remote add set-url <NOMBRE> <URL_REPO>
  
  nota: agregar otro repo que al hacer PUSH a los dos repos automaticamente. 
  
Tendremos algo como esto: <br>
  <br>
  2.- Vemos todos los repos remotos >>>   $ git remote -v <br>
                                              origin	git@github.com:<RepoName> (fetch) <br>
                                              origin	git@github.com:<RepoName>(push) <br>
                                              origin	git@vogsphere-v2.42madrid.com:vogsphere/<RepoName para evaluacion> (push) <br>
  <br>
  NOTA: Nos muestra todos los repos que podemos hacer push, vemos que el nombre del repo es ORIGIN. <br>
  <br>
  <br>
  # Pull, Push a dos repos por separado:

repo 1 -> github <br>
repo 2 -> git de 42 <br>
<br>
  1. Add new repo >>>                     $ git remote add <second> <URL_REPO> <br>
  <br>
  nota: agregar otro repo. <br>
  <br>
Tendremos algo como esto: <br>
    <br>
  2.- Vemos todos los repos remotos >>>   $ git remote -v <br>
                                              origin	git@github.com:<RepoName> (fetch) <br>
                                              origin	git@github.com:<RepoName> (push) <br>
                                              second	git@vogsphere-v2.42madrid.com:vogsphere/<RepoName para evaluacion> (push) <br>
  <br>
  NOTA: Nos muestra todos los repos que podemos hacer push, y vemos los nombres de los remos remotos a los cuales pordemos hacer PUSH independientemente.
