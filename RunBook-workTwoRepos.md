# Pull, Push a dos repos al mismo tiempo:
<pre>
repo 1 -> github
repo 2 -> git de 42

  1. Add new repo >>>                     $ git remote add set-url <NOMBRE> <URL_REPO>
  
  nota: Agrega otro repos, cuando hagamos PUSH, aplicaremos los cambios a los dos repos automaticamente. 
  
Tendremos algo como esto: 

  2.- Veamos todos los repos remotos >>>
  
  $ git remote -v
    origin	git@github.com:<RepoName> (fetch)
    origin	git@github.com:<RepoName>(push)
    origin	git@vogsphere-v2.42madrid.com:vogsphere/<RepoName> (push)
    
  NOTA: Nos muestra todos los repos que podemos hacer push, vemos que el nombre del repo es ORIGIN.
  
# Pull, Push a dos repos por separado: 

repo 1 -> github
repo 2 -> git de 42

  1. Add new repo >>> 
  $ git remote add <NameNewRepo> <URL_REPO> 
 
Tendremos algo como esto:

  2.- Vemos todos los repos remotos >>>
  
  $ git remote -v
      origin	git@github.com:<RepoName> (fetch) 
      origin	git@github.com:<RepoName> (push) 
      second	git@vogsphere-v2.42madrid.com:vogsphere/<RepoName para evaluacion> (push) 
      
  NOTA: Nos muestra todos los repos que podemos hacer push, y vemos los nombres de los remos remotos a los cuales pordemos hacer PUSH independientemente.
</pre>
