# EJercicio Práctico Jonay Contreras

## Índice
1. [Ejercicio 1](#ejercicio-1)
2. [Ejercicio 2](#ejercicio-2)
3. [Ejercicio 3](#ejercicio-3)
4. [Ejercicio 4](#ejercicio-4)
5. [Ejercicio 5](#ejercicio-5)
6. [Ejercicio 6](#ejercicio-6)
7. [Ejercicio 7](#ejercicio-7)
8. [Ejercicio 8](#ejercicio-8)
9. [Ejercicio 9](#ejercicio-9)
10. [Ejercicio 10](#ejercicio-10)
11. [Ejercicio 11](#ejercicio-11)
12. [Ejercicio 12](#ejercicio-12)
13. [Ejercicio 13](#ejercicio-13)
14. [Ejercicio 14](#ejercicio-14)
15. [Ejercicio 15](#ejercicio-15)
16. [Ejercicio 16](#ejercicio-16)
17. [Ejercicio 17](#ejercicio-17)
18. [Ejercicio 18](#ejercicio-18)
19. [Ejercicio 19](#ejercicio-19)
20. [Ejercicio 20](#ejercicio-20)
21. [Ejercicio 21](#ejercicio-21)
22. [Ejercicio 22](#ejercicio-22)
23. [Ejercicio 23](#ejercicio-23)
24. [Ejercicio 24](#ejercicio-24)




## Ejercicio 1
Creamos el repositorio en GitHub y despues lo clonaremos con su enlace

## Ejercicio 2 
```code
git clone https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
```
- <b>Explicación:</b>
    - git clone https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    
    ```code
    Clona el directorio remoto al local
    ```

- <b>Salida</b>
    - git clone https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    
    ```code
    
    ```


---

## Ejercicio 3
```code
touch README.md
git add .
git commit -m "Primer commit"
```
- <b>Explicación:</b>
    - touch README.md

    ```code
    Creamos el README.md
    ```

    - git add .
    
    ```code
    Añadimos los ficherosal siguiente commit
    ```

    - git commit -m "Primer commit"
    
    ```code
    Creamos un commit local llamado "Primer commit"
    ```

- <b>Salida</b>
    - touch README.md

    ```code

    ```

    - git add .
    
    ```code

    ```

    - git commit -m "Primer commit"
    
    ```code
        [main (commit-raíz) aeb1d5b] Primer commit
    1 file changed, 84 insertions(+)
    create mode 100644 README.md
    ```

---

## Ejercicio 4
```code
git branch develop
```
- <b>Explicación:</b>
    - git branch develop

    ```code
    Creamos una rama llamada "develop"
    ```


- <b>Salida</b>
    - git branch develop

    ```code

    ```

---

## Ejercicio 5
```code
git branch
```
- <b>Explicación:</b>
    - git branch 

    ```code
    Enseña las ramas creadas
    ```


- <b>Salida</b>
    - git branch 

    ```code
    develop
    * main
    ```

---


## Ejercicio 6
```code
git switch develop
git nano hola.html
CTRL+X
S
Enter
git add .
git commit -m "Creado archivo hola.html"
```
- <b>Explicación:</b>
    - git switch develop

    ```code
    Cambia la rama a develop
    ```

    - git nano hola.html

    ```code
    Crea un archivo llamado hola.html y nos deja escribir dentro
    ```


- <b>Salida</b>
    - git switch develop 

    ```code
    Cambiado a rama 'develop'
    ```

    - git nano hola.html

    ```code

    ```
---



## Ejercicio 7
```code
git switch main
nano adios.html
CTRL+X
S
Enter
```
- <b>Explicación:</b>
    - git switch main

    ```code
    Cambia a la rama main
    ```

    - nano adios.html

    ```code
    Crear el archivo adios.html
    ```


- <b>Salida</b>
    - git switch main

    ```code
    Cambiado a rama 'main'
    ```

    - nano adios.html

    ```code
    
    ```


---



## Ejercicio 8
```code
git add.
git commit -m "Creado el archivo adios.html"
```
- <b>Explicación:</b>
    - git add.

    ```code
    Añade los ficheros
    ```

    - git commit -m "Creado el archivo adios.html"

    ```code
    Crea un commit con dicho nombre
    ```


- <b>Salida</b>
    - git add.

    ```code

    ```

    - git commit -m "Creado el archivo adios.html"

    ```code
        [main e191553] Creado el archivo adios.html
    2 files changed, 138 insertions(+), 1 deletion(-)
    create mode 100644 adios.html
    ```


---


## Ejercicio 9
```code
git push origin main
```
- <b>Explicación:</b>
    - 

    ```code
    Envia el repositorio local de la rama actual a la rama main remota
    ```


- <b>Salida</b>
    -  git push origin main

    ```code
        Enumerando objetos: 16, listo.
    Contando objetos: 100% (16/16), listo.
    Compresión delta usando hasta 4 hilos
    Comprimiendo objetos: 100% (13/13), listo.
    Escribiendo objetos: 100% (16/16), 2.29 KiB | 2.29 MiB/s, listo.
    Total 16 (delta 4), reusados 0 (delta 0), pack-reusados 0
    remote: Resolving deltas: 100% (4/4), done.
    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    * [new branch]      main -> main
    ```

---



## Ejercicio 10
```code
git branch
```
- <b>Explicación:</b>
    - git branch

    ```code
    Miramos el listado de las ramas
    ```


- <b>Salida</b>
    - git branch 

    ```code
      develop
    * main
    ```

---

## Ejercicio 11
```code
git merge develop
```
- <b>Explicación:</b>
    - git merge develop

    ```code
    Une la rama develop a la actual (va a crear un conflicto por los cambios en el README.md)
    ```


- <b>Salida</b>
    - git merge develop 

    ```code
        Auto-fusionando README.md
    CONFLICTO (contenido): Conflicto de fusión en README.md
    Fusión automática falló; arregle los conflictos y luego realice un commit con el resultado.
    ```

---

## Ejercicio 12
```code
git add .
git commit -m "Merge realizado"
git push origin main
```
- <b>Explicación:</b>
    - git add .

    ```code
    Añade los ficheros
    ```

    - git commit -m "Merge realizado"

    ```code
    Crea un commit llamado "Merge realizado"
    ```

    - git push origin main

    ```code
    Envia el ultimo commit al repositorio remoto en la rama main
    ```


- <b>Salida</b>
    - git add .

    ```code
    
    ```

    - git commit -m "Merge realizado"

    ```code
    [main 667fd85] Merge realizado
    ```

    - git push origin main

    ```code
    origin main
    Enumerando objetos: 17, listo.
    Contando objetos: 100% (17/17), listo.
    Compresión delta usando hasta 4 hilos
    Comprimiendo objetos: 100% (13/13), listo.
    Escribiendo objetos: 100% (13/13), 2.06 KiB | 2.06 MiB/s, listo.
    Total 13 (delta 4), reusados 0 (delta 0), pack-reusados 0
    remote: Resolving deltas: 100% (4/4), completed with 1 local object.
    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    c847918..667fd85  main -> main
    ```

---

## Ejercicio 13
```code
git diff HEAD~2..HEAD~1
```
- <b>Explicación:</b>
    - git diff HEAD~2..HEAD~1

    ```code
    Enseña todos los cambios entre el merge y el commit llamado "Merge realizado"
    ```


- <b>Salida</b>
    -  git diff HEAD~2..HEAD~1

    ```code
                diff --git a/README.md b/README.md
            index 5a9d540..5a76299 100644
            --- a/README.md
            +++ b/README.md
            @@ -249,6 +249,59 @@ git commit -m "Creado el archivo adios.html"
            ## Ejercicio 9
            ```code
            git push origin main
            +```
            +- <b>Explicación:</b>
            +    - 
            +
            +    ```code
            +    Envia el repositorio local de la rama actual a la rama main remota
            +    ```
            +
            +
            +- <b>Salida</b>
            +    -  git push origin main
            +
            +    ```code
            +        Enumerando objetos: 16, listo.
            +    Contando objetos: 100% (16/16), listo.
            +    Compresión delta usando hasta 4 hilos
            +    Comprimiendo objetos: 100% (13/13), listo.
            +    Escribiendo objetos: 100% (16/16), 2.29 KiB | 2.29 MiB/s, listo.
            +    Total 16 (delta 4), reusados 0 (delta 0), pack-reusados 0
            +    remote: Resolving deltas: 100% (4/4), done.
            +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodrigue
            z
            +    * [new branch]      main -> main
            +    ```
            +
            +---
            +
            +
            +
            +## Ejercicio 10
            +```code
            +git branch
            +```
            +- <b>Explicación:</b>
            +    - git branch
            +
            +    ```code
            +    Miramos el listado de las ramas
            +    ```
            +
            +
            +- <b>Salida</b>
            +    - git branch 
            +
            +    ```code
            +      develop
            +    * main
            +    ```
            +
            +---
            +
            +## Ejercicio 11
            +```code
            +
        ```
        - <b>Explicación:</b>
            - 
            ```code
        @@ -267,9 +320,70 @@ git push origin main
        
        ---
        
        +## Ejercicio 12
        +```code
        
        +```
        +- <b>Explicación:</b>
        +    - 
        
        -## Ejercicio 10
        +    ```code
        +    
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  
        +
        +    ```code
        +    
        +    ```
        +
        +---
        +
        +## Ejercicio 13
        +```code
        +
        +```
        +- <b>Explicación:</b>
        +    - 
        +
        +    ```code
        +    
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  
        +
        +    ```code
        +    
        +    ```
        +
        +---
        +
        +## Ejercicio 14
        +```code
        +
        +```
        +- <b>Explicación:</b>
        +    - 
        +
        +    ```code
        +    
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  
        +
        +    ```code
        +    
        +    ```
        +
        +---
        +
        +## Ejercicio 15
        ```code
        
        ```
    ```

---

## Ejercicio 14
```code
git log 
```
- <b>Explicación:</b>
    - git log 

    ```code
    Enseña los commits del repositorio
    ```


- <b>Salida</b>
    -  git log 

    ```code
        commit 667fd85bf722986f7a9960016b39c2f939b8c2a9 (HEAD -> main, origin/main)
    Merge: 093233c 95a0859
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:22:12 2023 +0100

        Merge realizado

    commit 093233c0db6ab799c38aa0616e83857d3b57ce2a
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:17:40 2023 +0100

        Creado el archivo adios.html

    commit c847918b68ffc95c876bc305ddb37d5ac252d080
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:14:59 2023 +0100

        Creado el archivo adios.html

    commit e191553491ba7f4c04b92cfb084bc8dd000d4c66
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:12:50 2023 +0100

        Creado el archivo adios.html

    commit 95a08594bc7c81f0c6d47fef47a82478c3ad4281 (develop)
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:08:05 2023 +0100

        Creado archivo hola.html

    commit f252b985c4073dce24fb8aa67e749dc2d581434b
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:07:54 2023 +0100

        Creado archivo hola.html

    commit edb7a5433d1e5d849ad575d3eace0af3621b1209
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:05:32 2023 +0100

        Primer commit

    commit a90d762ebf9219f13977835fffcc03a01bd0c993
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 15:01:00 2023 +0100

        Primer commit

    commit aeb1d5b195432bcebf33d8f0132d11f018b8ac46
    Author: JonayKB <JonayKB@gmail.com>
    Date:   Wed Oct 18 14:59:20 2023 +0100

        Primer commit
    ```

---

## Ejercicio 15
```code
git tag
```
- <b>Explicación:</b>
    - git tag

    ```code
    Enseña todos los tags (ninguno)
    ```


- <b>Salida</b>
    -  git tag

    ```code
    
    ```

---

## Ejercicio 16
```code
git add .
git commit -m "Creación del tag v.1"
git tag v.1
```
- <b>Explicación:</b>
    - git add .

    ```code
    Añadimos los ficheros
    ```

    - git commit -m "Creación del tag v.1"

    ```code
    Creamos un commit al cual apuntara la etiqueta
    ```

    - git tag v.1

    ```code
    Creamos una etiqueta llamada v.1
    ```


- <b>Salida</b>
    - git add .

    ```code
    
    ```

    - git commit -m "Creación del tag v.1"

    ```code
        [main d261eca] Creación del tag v.1
    1 file changed, 335 insertions(+), 4 deletions(-)
    ```

    - git tag v.1

    ```code
    
    ```

---

## Ejercicio 17
```code
git checkout -b feature-2
nano Estamos_a_punto_de_terminar.html
CTRL+X
S
Enter
```
- <b>Explicación:</b>
    - git checkout -b feature-2

    ```code
    Crea una rama llamada feature-2 y te mueve a ella
    ```
    - nano Estamos_a_punto_de_terminar.html

    ```code
    Crear un archivo llamado Estamos_a_punto_de_terminar.html
    ```


- <b>Salida</b>
    - git checkout -b feature-2

    ```code
    Cambiado a nueva rama 'feature-2'
    ```
    - nano Estamos_a_punto_de_terminar.html

    ```code

    ```

---

## Ejercicio 18
```code
git add .
git commit -m "Creamos Estamos_a_punto_de_terminar.html"
git push origin feature-2
```
- <b>Explicación:</b>
    - git add .

    ```code
    Añadimos los ficheros
    ```
    - git commit -m "Creamos Estamos_a_punto_de_terminar.html"

    ```code
    Creamos un commit llamado como se ha nombrado
    ```

    - git push origin feature-2

    ```code
    Enviamos los ficheros al repositorio remoto a la rama feature-2
    ```


- <b>Salida</b>
    - git add .

    ```code

    ```
    - git commit -m "Creamos Estamos_a_punto_de_terminar.html"

    ```code
        [feature-2 20049df] Creamos Estamos_a_punto_de_terminar.html
    2 files changed, 61 insertions(+), 11 deletions(-)
    create mode 100644 Estamos_a_punto_de_terminar.html
    ```

    - git push

    ```code
    Enumerando objetos: 12, listo.
    Contando objetos: 100% (12/12), listo.
    Compresión delta usando hasta 4 hilos
    Comprimiendo objetos: 100% (10/10), listo.
    Escribiendo objetos: 100% (10/10), 3.76 KiB | 3.76 MiB/s, listo.
    Total 10 (delta 3), reusados 0 (delta 0), pack-reusados 0
    remote: Resolving deltas: 100% (3/3), done.
    remote: 
    remote: Create a pull request for 'feature-2' on GitHub by visiting:
    remote:      https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez/pull/new/feature-2
    remote: 
    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    * [new branch]      feature-2 -> feature-2
    ```

---


## Ejercicio 19
```code
git checkout develop
git merge feature-2
```
- <b>Explicación:</b>
    - git checkout develop

    ```code
    Cambiamos a la rama develop
    ```

    - git merge feature-2

    ```code
    Copiamos el contenido de la rama feature-2 a la develop (conflcito por el README.md)
    ```




- <b>Salida</b>
    - git checkout develop

    ```code
    Cambiado a rama 'develop'
    ```

    - git merge feature-2
        Auto-fusionando README.md
    CONFLICTO (contenido): Conflicto de fusión en README.md
    Fusión automática falló; arregle los conflictos y luego realice un commit con el resultado.
    ```code

    ```

---


## Ejercicio 20
```code
git add .
git commit -m "Merge realizado de feature-2"
git push origin develop
```
- <b>Explicación:</b>
    - git add .

    ```code
    Añadimos los ficheros
    ```
    - git commit -m "Merge realizado de feature-2"

    ```code
    Creamos un commit con dicho nombre
    ```
    - git push origin develop

    ```code
    Enviamos los ficheros al repositorio remoto en la rama develop
    ```


- <b>Salida</b>
    - git add .

    ```code

    ```
    - git commit -m "Merge realizado de feature-2"

    ```code
    [develop fd3e42b] Merge realizado de feature-2
    ```
    - git push origin develop

    ```code
    Enumerando objetos: 16, listo.
    Contando objetos: 100% (16/16), listo.
    Compresión delta usando hasta 4 hilos
    Comprimiendo objetos: 100% (12/12), listo.
    Escribiendo objetos: 100% (12/12), 1.59 KiB | 1.59 MiB/s, listo.
    Total 12 (delta 7), reusados 0 (delta 0), pack-reusados 0
    remote: Resolving deltas: 100% (7/7), completed with 2 local objects.
    remote: 
    remote: Create a pull request for 'develop' on GitHub by visiting:
    remote:      https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez/pull/new/develop
    remote: 
    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    * [new branch]      develop -> develop
    ```

---


## Ejercicio 21
```code
git switch main
git merge develop
```
- <b>Explicación:</b>
    - git switch main

    ```code
    Cambiamos a la rama main
    ```
    - git merge develop

    ```code
    Copiamos los ficheros de la rama develop a la main (Con conflicto por el README.md)
    ```



- <b>Salida</b>
    - git switch main

    ```code
    Cambiado a rama 'main'
    ```
    - git merge develop

    ```code
        Auto-fusionando README.md
    CONFLICTO (contenido): Conflicto de fusión en README.md
    Fusión automática falló; arregle los conflictos y luego realice un commit con el resultado.
    ```



---


## Ejercicio 22
```code
git add .
git commit -m "Creamos tag v.2"
git tag v.2
git push origin main
```
- <b>Explicación:</b>
    - git add .

    ```code
    Añade los ficheros
    ```
    - git commit -m "Creamos tag v.2"

    ```code
    Crea un commit con dicho nombre
    ```
    - git tag v.2
    ```code
    Crea un tag llamado v.2 apuntando al último commit realizado
    ```
    - git push origin main
    ```code
    Envia el repositorio a la rama main remota
    ```



- <b>Salida</b>
    - git add .

    ```code
    
    ```
    - git commit -m "Creamos tag v.2"

    ```code
    [main 7aa9d0c] Creamos tag v.2
    ```
    - git tag v.2
    ```code
    
    ```
    - git push origin main
    ```code
        Enumerando objetos: 13, listo.
    Contando objetos: 100% (13/13), listo.
    Compresión delta usando hasta 4 hilos
    Comprimiendo objetos: 100% (9/9), listo.
    Escribiendo objetos: 100% (9/9), 1.21 KiB | 1.21 MiB/s, listo.
    Total 9 (delta 5), reusados 0 (delta 0), pack-reusados 0
    remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
    667fd85..d56f1b1  main -> main
    ```


---


## Ejercicio 23
```code
git diff aeb1d5b195432bcebf33d8f0132d11f018b8ac46..HEAD
```
- <b>Explicación:</b>
    - 

    ```code
    
    ```



- <b>Salida</b>
    - 

    ```code
        diff --git a/Estamos_a_punto_de_terminar.html b/Estamos_a_punto_de_terminar.html
        new file mode 100644
        index 0000000..fc695b9
        --- /dev/null
        +++ b/Estamos_a_punto_de_terminar.html
        @@ -0,0 +1,11 @@
        +<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
        +<html>
        +<head>
        +<title>Terminando </title>
        +</head>
        +<body>
        +<h1 align="center" >Apunto de terminar </h1>
        +<hr>
        +<p> Esto se esta acabando Jonay_Contreras_Rodriguez </p>
        +</body>
        +</html>
        diff --git a/README.md b/README.md
        index bfeeddb..5c27059 100644
        --- a/README.md
        +++ b/README.md
        @@ -77,8 +77,931 @@ git commit -m "Primer commit"
            - git commit -m "Primer commit"
            
            ```code
        -    Creamos un commit local llamado "Primer commit"
        +        [main (commit-raíz) aeb1d5b] Primer commit
        +    1 file changed, 84 insertions(+)
        +    create mode 100644 README.md
        +    ```
        +
        +---
        +
        +## Ejercicio 4
        +```code
        +git branch develop
        +```
        +- <b>Explicación:</b>
        +    - git branch develop
        +
        +    ```code
        +    Creamos una rama llamada "develop"
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git branch develop
        +
        +    ```code
        +
        +    ```
        +
        +---
        +
        +## Ejercicio 5
        +```code
        +git branch
        +```
        +- <b>Explicación:</b>
        +    - git branch 
        +
        +    ```code
        +    Enseña las ramas creadas
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git branch 
        +
        +    ```code
        +    develop
        +    * main
        +    ```
        +
        +---
        +
        +
        +## Ejercicio 6
        +```code
        +git switch develop
        +git nano hola.html
        +CTRL+X
        +S
        +Enter
        +git add .
        +git commit -m "Creado archivo hola.html"
        +```
        +- <b>Explicación:</b>
        +    - git switch develop
        +
        +    ```code
        +    Cambia la rama a develop
        +    ```
        +
        +    - git nano hola.html
        +
        +    ```code
        +    Crea un archivo llamado hola.html y nos deja escribir dentro
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git switch develop 
        +
        +    ```code
        +    Cambiado a rama 'develop'
        +    ```
        +
        +    - git nano hola.html
        +
        +    ```code
        +
        +    ```
        +---
        +
        +
        +
        +## Ejercicio 7
        +```code
        +git switch main
        +nano adios.html
        +CTRL+X
        +S
        +Enter
        +```
        +- <b>Explicación:</b>
        +    - git switch main
        +
        +    ```code
        +    Cambia a la rama main
        +    ```
        +
        +    - nano adios.html
        +
        +    ```code
        +    Crear el archivo adios.html
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git switch main
        +
        +    ```code
        +    Cambiado a rama 'main'
        +    ```
        +
        +    - nano adios.html
        +
        +    ```code
        +    
        +    ```
        +
        +
        +---
        +
        +
        +
        +## Ejercicio 8
        +```code
        +git add.
        +git commit -m "Creado el archivo adios.html"
        +```
        +- <b>Explicación:</b>
        +    - git add.
        +
        +    ```code
        +    Añade los ficheros
        +    ```
        +
        +    - git commit -m "Creado el archivo adios.html"
        +
        +    ```code
        +    Crea un commit con dicho nombre
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git add.
        +
        +    ```code
        +
        +    ```
        +
        +    - git commit -m "Creado el archivo adios.html"
        +
        +    ```code
        +        [main e191553] Creado el archivo adios.html
        +    2 files changed, 138 insertions(+), 1 deletion(-)
        +    create mode 100644 adios.html
        +    ```
        +
        +
        +---
        +
        +
        +## Ejercicio 9
        +```code
        +git push origin main
        +```
        +- <b>Explicación:</b>
        +    - 
        +
        +    ```code
        +    Envia el repositorio local de la rama actual a la rama main remota
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  git push origin main
        +
        +    ```code
        +        Enumerando objetos: 16, listo.
        +    Contando objetos: 100% (16/16), listo.
        +    Compresión delta usando hasta 4 hilos
        +    Comprimiendo objetos: 100% (13/13), listo.
        +    Escribiendo objetos: 100% (16/16), 2.29 KiB | 2.29 MiB/s, listo.
        +    Total 16 (delta 4), reusados 0 (delta 0), pack-reusados 0
        +    remote: Resolving deltas: 100% (4/4), done.
        +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
        +    * [new branch]      main -> main
        +    ```
        +
        +---
        +
        +
        +
        +## Ejercicio 10
        +```code
        +git branch
        +```
        +- <b>Explicación:</b>
        +    - git branch
        +
        +    ```code
        +    Miramos el listado de las ramas
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git branch 
        +
        +    ```code
        +      develop
        +    * main
        +    ```
        +
        +---
        +
        +## Ejercicio 11
        +```code
        +git merge develop
        +```
        +- <b>Explicación:</b>
        +    - git merge develop
        +
        +    ```code
        +    Une la rama develop a la actual (va a crear un conflicto por los cambios en el README.md
        )
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git merge develop 
        +
        +    ```code
        +        Auto-fusionando README.md
        +    CONFLICTO (contenido): Conflicto de fusión en README.md
        +    Fusión automática falló; arregle los conflictos y luego realice un commit con el resulta
        do.
        +    ```
        +
        +---
        +
        +## Ejercicio 12
        +```code
        +git add .
        +git commit -m "Merge realizado"
        +git push origin main
        +```
        +- <b>Explicación:</b>
        +    - git add .
        +
        +    ```code
        +    Añade los ficheros
        +    ```
        +
        +    - git commit -m "Merge realizado"
        +
        +    ```code
        +    Crea un commit llamado "Merge realizado"
        +    ```
        +
        +    - git push origin main
        +
        +    ```code
        +    Envia el ultimo commit al repositorio remoto en la rama main
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git add .
        +
        +    ```code
        +    
        +    ```
        +
        +    - git commit -m "Merge realizado"
        +
        +    ```code
        +    [main 667fd85] Merge realizado
        +    ```
        +
        +    - git push origin main
        +
        +    ```code
        +    origin main
        +    Enumerando objetos: 17, listo.
        +    Contando objetos: 100% (17/17), listo.
        +    Compresión delta usando hasta 4 hilos
        +    Comprimiendo objetos: 100% (13/13), listo.
        +    Escribiendo objetos: 100% (13/13), 2.06 KiB | 2.06 MiB/s, listo.
        +    Total 13 (delta 4), reusados 0 (delta 0), pack-reusados 0
        +    remote: Resolving deltas: 100% (4/4), completed with 1 local object.
        +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
        +    c847918..667fd85  main -> main
        +    ```
        +
        +---
        +
        +## Ejercicio 13
        +```code
        +git diff HEAD~2..HEAD~1
        +```
        +- <b>Explicación:</b>
        +    - git diff HEAD~2..HEAD~1
        +
        +    ```code
        +    Enseña todos los cambios entre el merge y el commit llamado "Merge realizado"
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  git diff HEAD~2..HEAD~1
        +
        +    ```code
        +        diff --git a/README.md b/README.md
        +    index 5a9d540..5a76299 100644
        +    --- a/README.md
        +    +++ b/README.md
        +    @@ -249,6 +249,59 @@ git commit -m "Creado el archivo adios.html"
        +    ## Ejercicio 9
        +    ```code
        +    git push origin main
        +    +```
        +    +- <b>Explicación:</b>
        +    +    - 
        +    +
        +    +    ```code
        +    +    Envia el repositorio local de la rama actual a la rama main remota
        +    +    ```
        +    +
        +    +
        +    +- <b>Salida</b>
        +    +    -  git push origin main
        +    +
        +    +    ```code
        +    +        Enumerando objetos: 16, listo.
        +    +    Contando objetos: 100% (16/16), listo.
        +    +    Compresión delta usando hasta 4 hilos
        +    +    Comprimiendo objetos: 100% (13/13), listo.
        +    +    Escribiendo objetos: 100% (16/16), 2.29 KiB | 2.29 MiB/s, listo.
        +    +    Total 16 (delta 4), reusados 0 (delta 0), pack-reusados 0
        +    +    remote: Resolving deltas: 100% (4/4), done.
        +    +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodrigue
        +    z
        +    +    * [new branch]      main -> main
        +    +    ```
        +    +
        +    +---
        +    +
        +    +
        +    +
        +    +## Ejercicio 10
        +    +```code
        +    +git branch
        +    +```
        +    +- <b>Explicación:</b>
        +    +    - git branch
        +    +
        +    +    ```code
        +    +    Miramos el listado de las ramas
        +    +    ```
        +    +
        +    +
        +    +- <b>Salida</b>
        +    +    - git branch 
        +    +
        +    +    ```code
        +    +      develop
        +    +    * main
        +    +    ```
        +    +
        +    +---
        +    +
        +    +## Ejercicio 11
        +    +```code
        +    +
        +    ```
        +    - <b>Explicación:</b>
        +        - 
        +    @@ -267,9 +320,70 @@ git push origin main
        +    
        +    ---
        +    
        +    +## Ejercicio 12
        +    +```code
        +    
        +    +```
        +    +- <b>Explicación:</b>
        +    +    - 
        +    
        +    -## Ejercicio 10
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +
        +    +- <b>Salida</b>
        +    +    -  
        +    +
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +---
        +    +
        +    +## Ejercicio 13
        +    +```code
        +    +
        +    +```
        +    +- <b>Explicación:</b>
        +    +    - 
        +    +
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +
        +    +- <b>Salida</b>
        +    +    -  
        +    +
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +---
        +    +
        +    +## Ejercicio 14
        +    +```code
        +    +
        +    +```
        +    +- <b>Explicación:</b>
        +    +    - 
        +    +
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +
        +    +- <b>Salida</b>
        +    +    -  
        +    +
        +    +    ```code
        +    +    
        +    +    ```
        +    +
        +    +---
        +    +
        +    +## Ejercicio 15
        +    ```code
        +    
        +    ```
        +    ```
        +
        +---
        +
        +## Ejercicio 14
        +```code
        +git log 
        +```
        +- <b>Explicación:</b>
        +    - git log 
        +
        +    ```code
        +    Enseña los commits del repositorio
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  git log 
        +
        +    ```code
        +        commit 667fd85bf722986f7a9960016b39c2f939b8c2a9 (HEAD -> main, origin/main)
        +    Merge: 093233c 95a0859
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:22:12 2023 +0100
        +
        +        Merge realizado
        +
        +    commit 093233c0db6ab799c38aa0616e83857d3b57ce2a
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:17:40 2023 +0100
        +
        +        Creado el archivo adios.html
        +
        +    commit c847918b68ffc95c876bc305ddb37d5ac252d080
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:14:59 2023 +0100
        +
        +        Creado el archivo adios.html
        +
        +    commit e191553491ba7f4c04b92cfb084bc8dd000d4c66
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:12:50 2023 +0100
        +
        +        Creado el archivo adios.html
        +
        +    commit 95a08594bc7c81f0c6d47fef47a82478c3ad4281 (develop)
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:08:05 2023 +0100
        +
        +        Creado archivo hola.html
        +
        +    commit f252b985c4073dce24fb8aa67e749dc2d581434b
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:07:54 2023 +0100
        +
        +        Creado archivo hola.html
        +
        +    commit edb7a5433d1e5d849ad575d3eace0af3621b1209
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:05:32 2023 +0100
        +
        +        Primer commit
        +
        +    commit a90d762ebf9219f13977835fffcc03a01bd0c993
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 15:01:00 2023 +0100
        +
        +        Primer commit
        +
        +    commit aeb1d5b195432bcebf33d8f0132d11f018b8ac46
        +    Author: JonayKB <JonayKB@gmail.com>
        +    Date:   Wed Oct 18 14:59:20 2023 +0100
        +
        +        Primer commit
        +    ```
        +
        +---
        +
        +## Ejercicio 15
        +```code
        +git tag
        +```
        +- <b>Explicación:</b>
        +    - git tag
        +
        +    ```code
        +    Enseña todos los tags (ninguno)
        +    ```
        +
        +
        +- <b>Salida</b>
        +    -  git tag
        +
        +    ```code
        +    
        +    ```
        +
        +---
        +
        +## Ejercicio 16
        +```code
        +git add .
        +git commit -m "Creación del tag v.1"
        +git tag v.1
        +```
        +- <b>Explicación:</b>
        +    - git add .
        +
        +    ```code
        +    Añadimos los ficheros
        +    ```
        +
        +    - git commit -m "Creación del tag v.1"
        +
        +    ```code
        +    Creamos un commit al cual apuntara la etiqueta
        +    ```
        +
        +    - git tag v.1
        +
        +    ```code
        +    Creamos una etiqueta llamada v.1
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git add .
        +
        +    ```code
        +    
        +    ```
        +
        +    - git commit -m "Creación del tag v.1"
        +
        +    ```code
        +        [main d261eca] Creación del tag v.1
        +    1 file changed, 335 insertions(+), 4 deletions(-)
        +    ```
        +
        +    - git tag v.1
        +
        +    ```code
        +    
        +    ```
        +
        +---
        +
        +## Ejercicio 17
        +```code
        +git checkout -b feature-2
        +nano Estamos_a_punto_de_terminar.html
        +CTRL+X
        +S
        +Enter
        +```
        +- <b>Explicación:</b>
        +    - git checkout -b feature-2
        +
        +    ```code
        +    Crea una rama llamada feature-2 y te mueve a ella
        +    ```
        +    - nano Estamos_a_punto_de_terminar.html
        +
        +    ```code
        +    Crear un archivo llamado Estamos_a_punto_de_terminar.html
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git checkout -b feature-2
        +
        +    ```code
        +    Cambiado a nueva rama 'feature-2'
        +    ```
        +    - nano Estamos_a_punto_de_terminar.html
        +
        +    ```code
        +
        +    ```
        +
        +---
        +
        +## Ejercicio 18
        +```code
        +git add .
        +git commit -m "Creamos Estamos_a_punto_de_terminar.html"
        +git push origin feature-2
        +```
        +- <b>Explicación:</b>
        +    - git add .
        +
        +    ```code
        +    Añadimos los ficheros
        +    ```
        +    - git commit -m "Creamos Estamos_a_punto_de_terminar.html"
        +
        +    ```code
        +    Creamos un commit llamado como se ha nombrado
        +    ```
        +
        +    - git push origin feature-2
        +
        +    ```code
        +    Enviamos los ficheros al repositorio remoto a la rama feature-2
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git add .
        +
        +    ```code
        +
        +    ```
        +    - git commit -m "Creamos Estamos_a_punto_de_terminar.html"
        +
        +    ```code
        +        [feature-2 20049df] Creamos Estamos_a_punto_de_terminar.html
        +    2 files changed, 61 insertions(+), 11 deletions(-)
        +    create mode 100644 Estamos_a_punto_de_terminar.html
        +    ```
        +
        +    - git push
        +
        +    ```code
        +    Enumerando objetos: 12, listo.
        +    Contando objetos: 100% (12/12), listo.
        +    Compresión delta usando hasta 4 hilos
        +    Comprimiendo objetos: 100% (10/10), listo.
        +    Escribiendo objetos: 100% (10/10), 3.76 KiB | 3.76 MiB/s, listo.
        +    Total 10 (delta 3), reusados 0 (delta 0), pack-reusados 0
        +    remote: Resolving deltas: 100% (3/3), done.
        +    remote: 
        +    remote: Create a pull request for 'feature-2' on GitHub by visiting:
        +    remote:      https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez/pull/new
        /feature-2
        +    remote: 
        +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
        +    * [new branch]      feature-2 -> feature-2
        +    ```
        +
        +---
        +
        +
        +## Ejercicio 19
        +```code
        +git checkout develop
        +git merge feature-2
        +```
        +- <b>Explicación:</b>
        +    - git checkout develop
        +
        +    ```code
        +    Cambiamos a la rama develop
        +    ```
        +
        +    - git merge feature-2
        +
        +    ```code
        +    Copiamos el contenido de la rama feature-2 a la develop (conflcito por el README.md)
        +    ```
        +
        +
        +
        +
        +- <b>Salida</b>
        +    - git checkout develop
        +
        +    ```code
        +    Cambiado a rama 'develop'
        +    ```
        +
        +    - git merge feature-2
        +        Auto-fusionando README.md
        +    CONFLICTO (contenido): Conflicto de fusión en README.md
        +    Fusión automática falló; arregle los conflictos y luego realice un commit con el resulta
        do.
        +    ```code
        +
        +    ```
        +
        +---
        +
        +
        +## Ejercicio 20
        +```code
        +git add .
        +git commit -m "Merge realizado de feature-2"
        +git push origin develop
        +```
        +- <b>Explicación:</b>
        +    - git add .
        +
        +    ```code
        +    Añadimos los ficheros
        +    ```
        +    - git commit -m "Merge realizado de feature-2"
        +
        +    ```code
        +    Creamos un commit con dicho nombre
        +    ```
        +    - git push origin develop
        +
        +    ```code
        +    Enviamos los ficheros al repositorio remoto en la rama develop
        +    ```
        +
        +
        +- <b>Salida</b>
        +    - git add .
        +
        +    ```code
        +
        +    ```
        +    - git commit -m "Merge realizado de feature-2"
        +
        +    ```code
        +    [develop fd3e42b] Merge realizado de feature-2
        +    ```
        +    - git push origin develop
        +
        +    ```code
        +    Enumerando objetos: 16, listo.
        +    Contando objetos: 100% (16/16), listo.
        +    Compresión delta usando hasta 4 hilos
        +    Comprimiendo objetos: 100% (12/12), listo.
        +    Escribiendo objetos: 100% (12/12), 1.59 KiB | 1.59 MiB/s, listo.
        +    Total 12 (delta 7), reusados 0 (delta 0), pack-reusados 0
        +    remote: Resolving deltas: 100% (7/7), completed with 2 local objects.
        +    remote: 
        +    remote: Create a pull request for 'develop' on GitHub by visiting:
        +    remote:      https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez/pull/new
        /develop
        +    remote: 
        +    To https://github.com/JonayKB/ejercicio_git_Jonay_Contreras_Rodriguez
        +    * [new branch]      develop -> develop
        +    ```
        +
        +---
        +
        +
        +## Ejercicio 21
        +```code
        +git switch main
        +git merge develop
        +```
        +- <b>Explicación:</b>
        +    - git switch main
        +
        +    ```code
        +    Cambiamos a la rama main
        +    ```
        +    - git merge develop
        +
        +    ```code
        +    Copiamos los ficheros de la rama develop a la main (Con conflicto por el README.md)
        +    ```
        +
        +
        +
        +- <b>Salida</b>
        +    - git switch main
        +
        +    ```code
        +    Cambiado a rama 'main'
        +    ```
        +    - git merge develop
        +
        +    ```code
        +        Auto-fusionando README.md
        +    CONFLICTO (contenido): Conflicto de fusión en README.md
        +    Fusión automática falló; arregle los conflictos y luego realice un commit con el resulta
        do.
        +    ```
        +
        +
        +
        +---
        +
        +
        +## Ejercicio 22
        +```code
        +git add .
        +git commit -m "Creamos tag v.2"
        +git tag v.2
        +git push origin main
        +```
        +- <b>Explicación:</b>
        +    - git add .
        +
        +    ```code
        +    Añade los ficheros
        +    ```
        +    - git commit -m "Creamos tag v.2"
        +
        +    ```code
        +    Crea un commit con dicho nombre
        +    ```
        +    - git tag v.2
        +    ```code
        +    Crea un tag llamado v.2 apuntando al último commit realizado
        +    ```
        +    - git push origin main
        +    ```code
        +    Envia el repositorio a la rama main remota
        +    ```
        +
        +
        +
        +- <b>Salida</b>
        +    - git add .
        +
        +    ```code
        +    
        +    ```
        +    - git commit -m "Creamos tag v.2"
        +
        +    ```code
        +    [main 7aa9d0c] Creamos tag v.2
        +    ```
        +    - git tag v.2
        +    ```code
        +    
        +    ```
        +    - git push origin main
        +    ```code
        +    
        +    ```
        +
        +
        +---
        +
        +
        +## Ejercicio 23
        +```code
        +
        +```
        +- <b>Explicación:</b>
        +    - 
        +
        +    ```code
        +    
        +    ```
        +
        +
        +
        +- <b>Salida</b>
        +    - 
        +
        +    ```code
        +
            ```
        
        +
        ---
        
        +
        +## Ejercicio 24
        +```code
        +
        +```
        +- <b>Explicación:</b>
        +    - 
        +
        +    ```code
        +    
        +    ```
        +
        +
        +
        +- <b>Salida</b>
        +    - 
        +
        +    ```code
        +
        +    ```
        +
        +
        +---
        \ No newline at end of file
        diff --git a/adios.html b/adios.html
        new file mode 100644
        index 0000000..7dbf1b7
        --- /dev/null
        +++ b/adios.html
        @@ -0,0 +1,13 @@
        +```html
        +<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
        +<html>
        +<head>
        +<title>Adios </title>
        +</head>
        +<body>
        +<h1 align="center" >Adios soy un título </h1>
        +<hr>
        +<p> Adios soy el alumno Jonay_Contreras_Rodriguez </p>
        +</body>
        +</html>
        +```
        diff --git a/hola.html b/hola.html
        new file mode 100644
        index 0000000..d76906b
        --- /dev/null
        +++ b/hola.html
        @@ -0,0 +1,13 @@
        +```html
        +<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
        +<html>
        +<head>
        +<title>Hola </title>
        +</head>
        +<body>
        +<h1 align="center" >Hola soy un título </h1>
        +<hr>
        +<p> Hola soy el alumno Jonay_Contreras_Rodriguez </p>
        +</body>
        +</html>
        +```
    ```


---


## Ejercicio 24
```code
git log --oneline --all --graph --decorate
```
- <b>Explicación:</b>
    - git log --oneline --all --graph --decorate

    ```code
    Enseña todos los commits en una linea con toda la información y los merges con colorines y graficamente
    ```



- <b>Salida</b>
    - git log --oneline --all --graph --decorate

    ```code
    * d56f1b1 (HEAD -> main, origin/main) Creamos tag v.2
    *   7aa9d0c (tag: v.2) Creamos tag v.2
    |\  
    | * b37cb21 (origin/develop, develop) Merge realizado de feature-2
    | * 95d19f6 Merge realizado de feature-2
    | *   fd3e42b Merge realizado de feature-2
    | |\  
    | | * c926a4f (feature-2) Creamos Estamos_a_punto_de_terminar.html
    | | * ff4c095 (origin/feature-2) Creamos Estamos_a_punto_de_terminar.html
    | | * 20049df Creamos Estamos_a_punto_de_terminar.html
    | * | 202fd12 Commit en develop por el readme
    * | | 8a5fcb4 Commit por cualpa del readme
    | |/  
    |/|   
    * | d261eca (tag: v.1) Creación del tag v.1
    * | 667fd85 Merge realizado
    |\| 
    | * 95a0859 Creado archivo hola.html
    | * f252b98 Creado archivo hola.html
    * | 093233c Creado el archivo adios.html
    * | c847918 Creado el archivo adios.html
    * | e191553 Creado el archivo adios.html
    * | edb7a54 Primer commit
    |/  
    * a90d762 Primer commit
    * aeb1d5b Primer commit
    ```


---