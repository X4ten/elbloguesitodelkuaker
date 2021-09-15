---
layout: post
author: X4ten
---

Ayer tuve que ir a preparar los ordenadores de un colegio y entre las incidencias tipicas

de no me funciona una cosa, no va lo otro etc, me encontré con un muro y encima me lo puso 

windows xp, era que una carpeta compartida que tenian en la secretaria por servidor no

abria y le daba error. En una situación normal me hubiera puesto y arreglado pero la cosa

de trabajar en esto es que tu vas a hacer un objetivo y no a otros, en mi caso, instalar

los escritorios remotos, entonces me tuve que ir y no pude solucionar la incidencia que 

era de gravedad.

Hoy, estoy aquí para enseñaros como solucionar esa incidencia si os pasa en windows xp, 7

8 y 10.

Una de las soluciones es *Habilitar NetBIOS sobre TCP/IP e iniciar el examinador de equipos*.

Aquí os dejo enumerado lo que son los pasos


*Paso 1: Habilitar NetBIOS sobre TCP/IP*
*Haga clic en Inicio, haga clic en Panel de Controly, a continuación, haga clic en red y conexiones a Internet.*

*Haga clic en conexiones de red.*

*Haga clic en Conexión de área Local y, a continuación, haga clic en Propiedades.*

*Haga clic en Protocolo Internet (TCP/IP)y, a continuación, haga clic en Propiedades.*

*Haga clic en la ficha General y, a continuación, haga clic en Avanzadas.*

*Haga clic en la ficha WINS .*

*En configuración de NetBIOS, haga clic en Habilitar NetBIOS sobre TCP/IPy, a continuación, haga clic en Aceptar dos veces.*

*Haga clic en Cerrar para cerrar el cuadro de diálogo Propiedades de conexión de área Local .*

*Cierre la ventana Conexiones de red.*

*Paso 2: Iniciar el servicio Examinador de equipos*
*Haga clic en Inicio, haga clic con el botón secundario en Mi PC y, a continuación, haga clic en Administrar.*

*Haga doble clic en servicios y aplicaciones.*

*Haga doble clic en Servicios.*

*En el lado derecho, haga clic en Examinador de equiposy, a continuación, haga clic en Inicio.*

*Cierre la ventana Administración de equipos.*

Este es una de las soluciones que puedes usar. Si esta solución no funciona, tenemos la otra solución

Esta solución se basa en Instalar compartir archivos e impresoras y asegúrese de que no está bloqueado por Firewall de Windows

*Paso 1: Instalar el archivo compartir e impresoras para redes Microsoft*
*Haga clic en Inicio, haga clic en Ejecutar, escriba ncpa.cpl, y a continuación, haga clic en Aceptar.*

*Haga clic en Conexión de área Local y, a continuación, haga clic en Propiedades.*

*Haga clic en la ficha General y, a continuación, haga clic en instalar.*

*Haga clic en servicioy, a continuación, haga clic en Agregar.*

*En la lista Servicio de red , haga clic en Compartir archivos e impresoras para redes Microsofty, a continuación, haga clic en Aceptar.*

*Haga clic en Cerrar.*

*Paso 2: Asegúrese de que compartir archivos e impresoras no está bloqueado por Firewall de Windows*
*Haga clic en Inicio, haga clic en Ejecutar, escriba firewall.cply, a continuación, haga clic en Aceptar.*

*En la ficha General , asegúrese de que está desactivada la casilla de verificación no permitir excepciones .*

*Haga clic en la ficha excepciones .*

*En la ficha excepciones , asegúrese de que está activada la casilla de verificación Compartir archivos e impresoras y, a continuación, haga clic en Aceptar*

Si ya no funciona ninguna de las dos tiene que ponerse en contacto con eñ servicio del servidor.

Y bueno aquí os dejo esta pequeña anecdota acompañada de dos soluciones.

Un saludo ;).
