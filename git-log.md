### git log
Muestra el historial de commits

`git log pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el fromato que indicamos.

#### Limitar la salida del historial
`git log -n`: Cambiamos la n por cualquier número entero, por ejemplo: `git log -2` nos mostrará los 2 commits más recientes.

`git log --after="2018-10-23"`: Muestra los commits realizados despúes de la fecha especificada.

`git log --before="2018-10-25"`: Muestra los commits realizados antes de la fecha especificada.

Las banderas de comando `git log` se pueden usar juntas según nos convega, por ejemplo:
`git log --after="2018-10-23" --before="2018-10-25"`