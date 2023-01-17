# RamasBasico

## COMANDOS UTILIZADOS EN ESTA TAREA.
Para realizar este ejercicio, usé la interfaz y por lo tanto no utilicé ningún comando, y los pasos que seguí fueron 
los siguientes:

1. En la barra de herramientas, le doy al botón VCS y create git repository.
2. Una vez hecho, aparece a la izquierda una pestaña para hacer los commits y la abro.
3. En la Main, hago el primer comit, me situú en la ventana, le pongo nombre al commit y selecciono la clase Main que
es la que he modificado, y le doy al botón commit.
4. Hago lo mismo para los siguientes commits.
5. Cuando tengo que crear la nueva rama, le doy al botón inferior que pone master, y le doy a new branch y le pongo el 
nombre exp.
6. Sobre el src le doy al botón derecho y creo una clase llamada Nueva, donde haré los siguientes commits, y estoy en 
la rama exp, ya que me cambié pulsando sobre checkout.
7. Hago los commits correspondientes,cambiándome sobre las ramas en función de como sea el esquema.
8. Finalmente voy a la pestaña de Git, le doy a Merge y selecciono la rama que quiero traer a la Main, en este caso exp.
9. Le doy a la opción de poner mensaje (-m) y le pongo la letra F.
10. Hago push dándole a la flecha verde situada en la esquina superior derecha.

En el caso de que se usaran comandos en la consola, serían los siguientes:
1. Git init
2. Git add src
3. Hago el commit en la main con git commit -m""
4. Sigo haciendo los commits necesarios.
5. Creo una nueva rama: git branch exp
6. Me cambio a la rama exp: git checkout exp
7. Compruebo en que rama estoy: git branch
8. Sigo haciendo los commits como anteriormente.
9. Una vez que acabo, hago el merge dándole al botón git, luego merge y seleccionando la rama con la que quiero hacer
merge, pudiendo ponerle un nombre al commit con la opción -m (en este caso F)
10. Creo el Readme.md con el comando echo>>Readme.md y escribo en él los comandos usados.
11. Hago push con el comando git push -u origin main.
