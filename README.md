# EJercicio Práctico Jonay Contreras

## Índice
1. [Ejercicio 1](#ejercicio-1)
2. [Ejercicio 2]()
3. [Ejercicio 3]()
4. [Ejercicio 4]()
5. [Ejercicio 5]()
6. [Ejercicio 6]()
7. [Ejercicio 7]()




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
    
    ```

    - git push origin main

    ```code
    
    ```

---

## Ejercicio 13
```code

```
- <b>Explicación:</b>
    - 

    ```code
    
    ```


- <b>Salida</b>
    -  

    ```code
    
    ```

---

## Ejercicio 14
```code

```
- <b>Explicación:</b>
    - 

    ```code
    
    ```


- <b>Salida</b>
    -  

    ```code
    
    ```

---

## Ejercicio 15
```code

```
- <b>Explicación:</b>
    - 

    ```code
    
    ```


- <b>Salida</b>
    -  

    ```code
    
    ```

---