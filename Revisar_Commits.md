# Revisar Commits Realizados
Para este ejercicio, utilizaremos un nuevo repositorio e iremos consultando los diferentes commits que se han hecho.

# 1. Contenido del README.md en el commit actual

Si utilizamos el comando:

~~~
cat README.md
~~~

Éste debería ser el resultado:

![](cat%20commit%20actual.png)

# 2. Cambiar al commit anterior

Para abrir el commit anterior, primero debemos saber la cabecera de ese commit. Para ello, utilizamos el comando:

~~~
git checkout *cabecera*
~~~
En mi caso:
![](cabeceras%20commits.png)

Por lo tanto, si ejecuto el comando:

~~~
cat README.md
~~~

El resultado es:

![](cat%20commit%20actual.png)

# 3. Veamos en que posición nos encontramos

Actualmente, la posición es esta:
![](posicion%20commit%20.png)

# 4. Vamos a movernos al segundo commit

