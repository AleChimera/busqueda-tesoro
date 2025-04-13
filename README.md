
![Búsqueda del Tesoro](ChatGPT Image 13 abr 2025, 02_36_39 p.m..png)

---Uso de los programas---

La idea de estos programas viene de implementar en una escuela un
juego de Búsqueda del Tesoro utilizando placas microbit.

En este sentido, un alumno, con la placa con el programa emisora.py
guía a otro alumno que tiene la placa con el programa receptora.py
hacia uno o varios objetivos.

En los displays de ambas placas se muestran dos tipos de flechas.
Unas estáticas, que significan 'no caminar'. Y otras con movimiento,
que significan 'caminar'. Se pasa de un tipo de flechas a las otras
pulsando a la vez los botones A y B. A su vez, para ambos tipos de
flechas (orden de caminar o no caminar) se pueden dar instrucciones
de giro, a izquierda o derecha, pulsando los botones correspondientes
(A o B).

Si el juego lo juegan más de un par de jugadores a la vez, es necesa-
rio establecer un canal para cada par. Esto se hace mediante el pará-
metro channel del método radio.config(). Así, un par de jugadores
pueden utilizar un channel=0, otro par un channel=1, etc. Es impor-
tante hacer esta modificación en los programas antes de comenzar el
juego.

Para finalizar, esta versión de los programas creo tiene alguna uti-
lidad para mostrar el tema de programación orientada a objetos y 
darle una aplicación práctica de modo inmediato.

Espero les sea útil y divertido.

Alejandro Chimera
