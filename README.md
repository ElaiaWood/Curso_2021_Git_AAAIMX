### Comandos Git
Para ejecutar la preview de nuestro archivo oprima: Ctrl + Shift + v

26/04/2021

## Comando para logearte
> git config --global user.email "email"
## git init
> Va iniciar nuestro repositorio local
## git add
> Agregar todos los cambios hechos a los archivos
## git commit "comentario"
> Nos va a generar una historia del repositorio y se va pasar a memoria estática
## git status
> Nos va mostrar los archivos a los que no les hemo hecho git . add

## git log
> Muestra el historial de los commit

## git show
>Nos muestra el último commit

## git diff <tag> <tag>
>Nos va servir para comparar versiones de commits

## git reset -- hard
>Este es un reset duro, elimina todos los commits antes del tag que escogimos

## git reset -- soft
> Elimina lo que está en el staging pero no borra los cambios que tenemos sin git add

## git restore <nombre_del_archivo>
>Funciona de manera parecida al reset -- soft, pero no borra de manera permanente lo que está en memoria ram

## git brach <nombre_de_la_rama>
> Sirve para crear una rama

