
# Video - Tutorial

[![Alt text](https://img.youtube.com/vi/1hSZi3SKg9Y/0.jpg)](https://youtu.be/1hSZi3SKg9Y)

# USO GIT DIFF

Para comenzar este pequeño tutorial vamos a inicializar un repositorio en local con  **git init**

 - Inicializamos un repositorio con:
   >```git init```
 - Creamos un archivo con el comando touch seguido del nombre del archivo seguido de la extensión.
   >```touch hola.txt```

 - Editamos el archivo con nano
	  >```nano hola.txt```

 - Añadimos al stage el archivo
	>```git add hola.txt```

 - Hacemos un commit
   >```git commit -m "commit1"```

 - Editamos el archivo con nano podemos borrar algunas cosas que hicimos con anterioridad
   >```nano hola.txt```

 - Hacemos uso de git diff
	 >```git diff hola.txt```



 
# USO GIT CHECKOUT

Continuando con esta parte del tutorial
 - Haremos un git add 
  >```git add hola.txt```
 - Haremos un segundo commit del archivo
  >```git commit -m "commit2"```
 - Ahora que tenemos dos commit intentaremos volver al commit anterior, para eso haremos git log --oneline para saber el id del commit
  >```git log --oneline```

 - Una vez que tengamos el id haremos uso del git checkout
  >```git checkout 34db23```

Hemos finalizado el tutorial.


