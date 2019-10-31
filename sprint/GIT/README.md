# PREGUNTAS
**remote**:Los repositorios remotos son versiones
de tu proyecto que se encuentran alojados en
Internet o en algún punto de la red.
Puedes tener varios, cada uno de los cuales puede
ser de sólo lectura, o de lectura/escritura,
según los permisos que tengas.

**init**:Este comando se usa para crear un nuevo
repertorio GIT:
git init

**Clone** :Si deseas obtener una copia de un
repositorio Git existente

**ADD** : Mueve al índice las modificaciones que
hayamos realizado

**COMMIT** :Es el comando que registra los cambios
en el repositorio de git.

**push** : es un comando que sube los cambios hechos
en tu ambiente de trabajo a una rama de trabajo tuya
y/o de tu equipo remota.

**pull** :es una abreviación de git fetch seguido de
git merge FETCH_HEAD . Es decir, git fetch trae los
cambios, pero los deja en otro branch, hasta que se
hace el git merge para traerlos al branch local.

**merge** :La forma mas conocida es git merge,
la cual realiza una fusión a tres bandas entre
las dos últimas instantáneas de cada rama y el
ancestro común a ambas, creando un nuevo commit
con los cambios mezclados.

**Nombra las fases de GIT y que pasa en cada una
de ellas.**

1.Untracked: Signigica que no se lleva registro
de ese archivo

1.Untracked: Signigica que no se lleva registro de
ese archivo

2.Tracked: Signigica que ya hay registro y cambio

3.Modified: QUe el archivo esta siendo modificado

4.Staged: Es un archivo que ya añadimos para hacer
un commit

5.Commited: Archivo que ya se respaldo
Fin de la conversación
Escribe un mensaje...

**¿Que son las cosas que NO se deben hacer en un repositorio de GIT?**

1. NUNCA hacer commit directamente a 'master' Esto sobre todo aplica cuando trabajas colaborativamente usando un repositorio central principal pero también es válido si uno trabaja solo.
2. NUNCA hacer git push --force
Normalmente, cuando hacemos push a nuestro repositorio central los commits que hemos realizado son enviados y colocados "tal cual" encima del estado actual de nuestra rama en el repositorio central.
3. NUNCA subir archivos binarios
Los archivos de texto son un punto clave aquí, pues los cambios en esta clase de archivos son fácilmente detectables, pero es casi imposible para datos binarios.
4. NUNCA usar git pull
Ok esto podría sonar un tanto jalado de los pelos, pero es que si hacemos git pull no tendremos oportunidad de ver qué clase de cambios estamos tratando de incorporar (haciendo pull), podrían estos ser grandes refactorizaciones con un alto impacto o cambios sencillos de los que no hay que preocuparnos.
5. NUNCA Usar Fast Forward
Si nosotros hacemos git merge directamente, no estamos asegurándonos de crear un merge commit. Los merge commit solo son necesarios cuando ambas ramas que queremos mezclar (merge) tienen nuevos commits.
Fin de la conversación
Escribe un mensaje...

**¿A que año debía volver Marty McFly para
reestablecer la linea de tiempo?**
al 1958
