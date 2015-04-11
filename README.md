# git-testeos
git-testeos

*** NOTA IMPORTANTE aparece el usuario y password de github configurado en maven-scm-plugin.

- Funciona correctamente (11/04/2015)

$ git push origin master 
  Subimos los cambios 

$ mvn release:clean

$ mvn release:prepare
  Nos va preguntando por las versiones:
   - versión a crear
   - versión del siguiente SNAPSHOT 
  Cambiará el pom.xml con la versión SNAPSHOT que le indiquemos.
