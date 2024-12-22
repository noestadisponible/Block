# Block

---
.
=======

# Probando GitFlow

---

Usando 
git branch (te ubica en la rama que estas)


=======

# Apuntes

![Examen 1](/IMAGENES/examen1.png)

Poner la maquina virtual de ubuntu en NAT.
Los contenedores de ubuntu tienen que tener como nombre de host el nombre 
indicado en la foto.

Politicas iptables en ACCEPT

1) Que todo tenga conectividad
• Foto del ping del cliente de dentro del nat a la ip NAT del ubuntu de la MV 
• Foto del cliente de la red de alumnos a la ip de la red de secretaría.
2) Politicas de todos los routers en DROP dejado salida de todo a internet
• Foto del ping del cliente de dentro del nat a la ip NAT del ubuntu de la MV 
• Foto del cliente de la red de alumnos a la ip NAT de ubuntu de la MV
• Foto de iptables –S del router de salida y del de alumnos
3) Monta un NAT en el router que se indica en la foto.
• Foto del iptables –S del router del NAT ,
• Foto de un ping del cliente de dentro de NAT a la ip NAT del ubuntu de la MV
4) La red de profesores debe de poder conectarse a los clientes de los alumnos 
pero no al reves. Usa ipset.
• Foto de la ipset creada
• Foto de iptables –S del router de profesores y del de alumnos
• Foto comprobación conexión.
5) Nadie puede entrar en la red de secretaría, usa ipset
• Foto de iptables –S del router de secretaría
6) Desde el ubuntu a traves del router de salida se debe de llegar al ssh del cliente 
de dentro de la red NAT
• Foto del iptables –S –t nat de cada router implicado
• Foto de la conexion desde el ubuntu de la MV
7) Desde todas las redes se puede entrar el ssh del router de alumnos. Usa ipset.
• Foto de iptables –S del router de alumnos
• Foto de la ipset creada
• Foto de alguna conexion al ss

---

## Solución

Este proyecto incluye:
- Ejemplo 1.
- Ejemplo 2.
- Ejemplo 3.

---

## Estructura del Proyecto
- [Enlace 1](https://youtu.be/zJlaFBv5IqM?si=NN1I46NykYP9lpzF)
- Enlace 2
- Enlace 3

---


![Champion](/IMAGENES/sergio.jpg)

### Contacto
Si tienes alguna pregunta, no dudes en contactarme:

- Email: lucho.salas@educa.madrid.org
- GitHub: [noestadisponible](https://github.com/noestadisponible)
- Linkedin: [Linkedin](https://www.linkedin.com/in/luchopaul)
