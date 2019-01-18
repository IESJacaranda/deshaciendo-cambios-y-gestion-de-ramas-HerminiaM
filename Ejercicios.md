1. Tienes que modificar la escena 5 de Hamlet en el fichero scene-5.txt. En dicha escena Hamlet encuentra al fantasma de su padre. Añade este texto al fichero:
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting flames
> Must render up myself.
Creamos mkdir prueba, nos cambiamos init git y clonamos contenido.
nano scene-5.txt 
escribimos texto y guardamos cambios
2. Añade scene-5.txt al área de preparación.
git add 
3. Haz un commit con los cambios con un buen mensaje de commit.
git commit -m"comentario"
4. Modifica las palabras del fantasma. Aquí tienes una sugerencia divertida:
> Ghost: 
> My hour is almost come,
> When I to sulphurous and tormenting balloons
> Must render up myself.
nano scene-5.txt, git add, git commit
5. Devuelve el fichero al estado del último commit.
git log online, vemos codigo y para deshacer ultimo commit
git reset --mixed 2433069
6. Cambia el nombre de LARRY por LAERTES en los ficheros scene-3.txt y scene-7.txt.
modificamos archivos con nano scene 3 y 7 txt
7. Añade los ficheros al área de preparación usando un único comando git.
git add --all para añadir todos los ficheros con cambios

8. Vamos a cometer un error a propósito. Borra cualquier línea del fichero scene-2.txt.
9. Añade scene-2.txt al área de preparación.
nano secene-2.txt y git add para añadir

10. Comprueba el estado del repositorio. 
git status para comprobar modificaciones

11. Devuelve scene-2.txt al directorio de trabajo.
para volver al directorio desde index
git rm --keep -local scene-2.txt 

12. Haz un commit para guardar los cambios realizados en el nombre de Larry por Laertes.
13. Busca el primer commit que has hecho y vuelve a dicho commit. Indica como has buscado el commit anterior y como has vuelto a él.
para buscar commit git log --online y obtenemos el código
14. Crea una nueva rama llamada **reinventando_hamlet**
git branch reinventando_hamlet
15. Cámbiate a dicha rama
git checkout reinventando_hamlet
16. Mejora la escena 2 como creas conveniente.
17. Haz un commit con los cambios con un mensaje adecuado.
18. Vuelve a la rama master.
git checkout master
19. Elimina la rama **reinventando_halet**
git branch -d reinventando_hamlet
20. Crea una nueva rama, modifica algo en la rama master, haz commit y llévate los cambios a la rama que has creado.
para llevar los cambios a la rama que he creado:
git status para compobar
git merge para llevarme cambios
21. Provoca un conflicto entre la rama master y la rama que has creado (indica lo que has hecho). Une la rama a la rama master resolviendo el conflicto.
