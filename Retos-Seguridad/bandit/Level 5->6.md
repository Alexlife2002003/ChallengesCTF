
## Objetivo
The password for the next level is stored in a file somewhere under the **inhere** directory and has all of the following properties:

-   human-readable
-   1033 bytes in size
-   not executable
## Datos Acceso
bandit5
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
## Solucion
```bash
andit5@bandit:~$ ls
inhere
bandit5@bandit:~$ cd inhere/
bandit5@bandit:~/inhere$ find . -readable -type f -size 1033c
./maybehere07/.file2
bandit5@bandit:~/inhere$ cat ./maybehere07/.file2
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
bandit5@bandit:~/inhere$ 




```
## Notas adicionales
| comando |  descripcion|
|---|----|
|find|busca un archivo en los directorios de acuerdo a caracteristicas especificadas


## Referencias



