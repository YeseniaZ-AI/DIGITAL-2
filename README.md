# Entrega1
Sistema avanzado de medición de reflejos
Es un juego de reacción rápida implementado en un ESP32, en el que uno o dos jugadores deben responder lo más rápido posible a estímulos visuales (LEDs) o sonoros (buzzer). 
*Cada jugador tiene 4 botones, uno por cada estímulo posible (3 LEDs + buzzer). 
*El sistema genera estímulos de forma aleatoria y mide el tiempo de reacción de los jugadores. 
*Si el jugador acierta el botón correspondiente → gana un punto.
*Si se equivoca → pierde un punto.
*El puntaje se muestra por consola serial.

El juego incluye tres modos:
*Un jugador → mide el tiempo de reacción de un solo jugador.
*Dos jugadores → ambos compiten en la misma ronda.
*Contrarreloj (30s) → los jugadores deben acumular la mayor cantidad de puntos en 30 segundos.

También incorpora controles extra:
*Botón de inicio para comenzar el juego.
*Botón de modo 3 para activar el contrarreloj.
*Botón de stop para detener el juego en cualquier momento.
