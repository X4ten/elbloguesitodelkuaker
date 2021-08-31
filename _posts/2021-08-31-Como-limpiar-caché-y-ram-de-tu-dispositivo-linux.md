---
layout: post
author: X4ten
---
En este post vamos a aprender a como crear un limpiador de caché para linux
utilizaremos las siguientes herramientas:

**·geany**
 
**·Bash**

**·terminal**  

Lo primero que tenemos que hacer es entrar en nuestro editor de codigo que más nos guste, en mi caso entraré en **Geany**



<pre> #! /bin/bash

echo "Se está limpiando la caché y aligerando el pc"

sync ; echo 3 > /proc/sys/vm/drop_caches </pre>



Una vez hecho eso lo que tenemos que hacer es ejecutarlo con usuario root


---

<pre>sudo bash limpiador.sh</pre>

---
Yo le puse en este caso el nombre de limpiador, teneís que sustituir el nombre de limpiador por el que querais y poner .sh


