## Identificación

**Nombre:** Jose Antonio

**Apellidos:** Marín Rodríguez

**Nombre del modulo:** Lenguajes de Marcas y Gestor de Información

**Nombre del instituto:** IES Aguadulce

**Curso:** 1º DAW

**Enlace web:** https://joseant25.github.io/PracticaGit/

## Uso de Git mediante la terminal git bash. Las instrucciones y sus resultados deben mostrar como **bloques de código markdown:**

[rep2.PNG](https://github.com/JoseAnt25/PracticaGit/blob/main/rep.PNG)
# Creación del repositorio en nuestro ordenador (init):

```
MINGW64 ~ (master)
$ cd Downloads

 MINGW64 ~/Downloads (master)
$ cd PracticaGit

 MINGW64 ~/Downloads/PracticaGit (master)
$ git init
Initialized empty Git repository in C:/Users/josea/Downloads/PracticaGit/.git/
```

# Creación de un commit inicial (add, status, commit, log)

```
 MINGW64 ~/Downloads/PracticaGit (master)
$ git add README.md

 MINGW64 ~/Downloads/PracticaGit (master)
$ git status

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

 MINGW64 ~/Downloads/PracticaGit (master)
$ git commit
[master (root-commit) 15ee4d9] add hola
 1 file changed, 25 insertions(+)
 create mode 100644 README.md

 MINGW64 ~/Downloads/PracticaGit (master)
$ git log
commit 15ee4d94684c2a845fb50e28b7b54c39e8750c63 (HEAD -> master)
Author: Jose Antonio Marín Rodríguez <jmarrod2504@g.educaand.es>
Date:   Mon Jan 22 17:55:25 2024 +0100

    add hola


```

# Añadir el remoto al repositorio local (branch, remote)

``` 
 MINGW64 ~/Downloads/PracticaGit (master)
$ git remote add origin https://github.com/JoseAnt25/PracticaGit.git

 MINGW64 ~/Downloads/PracticaGit (master)
$ git branch -M main



```

# Subir el repositorio a Github (push)

```
MINGW64 ~/Downloads/PracticaGit (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 643 bytes | 643.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JoseAnt25/PracticaGit.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```


## Uso de Git mediante la interfaz de VSCode:

# Creación de otro commit

```
MINGW64 ~/Downloads/PracticaGit (main)
$ git commit index.html
[main 9480db3] hola
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
```

 # Subir el repositorio a Github

 ```
MINGW64 ~/Downloads/PracticaGit (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JoseAnt25/PracticaGit.git
   15ee4d9..9480db3  main -> main
branch 'main' set up to track 'origin/main'.
```

