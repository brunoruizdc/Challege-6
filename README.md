# Challege-6

En el primer ejercicio es importante realizar un print("\nCurrent Scores:") para determinar el marcador cada ronda que se va jugando.

Por otro lado, especificar que implica el empate; la victoria del primer y segundo jugador mediante  player2['score'] += result[1]; de dicha forma, se actualiza el resultado.

Para cada ronda en específico; el comando: if result con un print si es empate, si es el primer jugador ganador o si es el segundo jugador el ganador.

Estos son los resultados tras 100 rondas de juego entre Jim, Jane, Peter y Zoe:
![Imagen de WhatsApp 2024-11-25 a las 22 51 31_f26fa14e](https://github.com/user-attachments/assets/c91de48e-0004-43e0-a07c-39d9347456a0)


Como se nota, es Zoe la ganadora con 97 puntos.


Para el Segundo ejercicio, 10 amigos empiezan a jugar 100 rondas de "Piedra, papel o tijera" incluyendo las opciones Lagarto y Spock. Mítico juego de la serie "The Big Ban Theory"

El payoff debe especificar lo siguiente:

Spock le gana a tijeras y piedra; pierde con papel y lagarto.

Lagarto le gana a papel y Spock; pierde con tijeras y piedra.

Piedra le gala a lagarto y tijeras; pierde con papel y Spock.

Papel le gana a piedra y Spock; pierde con lagarto y tijeras.

Tijeras le gana a papel y lagarto; pierde con piedra y Spock.

Especificar las caracteristicas de cada estrategia se hace de la siguiente manera; si, por ejemplo, Spock le gana a piedra:  ('Spock', 'Rock'): (1, 0)

O, si a caso, Lagarto pierde con piedra: ('Lizard', 'Rock'): (0, 1)

Teniendo en cuenta dichas estrategias, los amigos empiezan a jugar soltando los siguientes resultados:

![Captura de pantalla 2024-11-25 225512](https://github.com/user-attachments/assets/89ec2599-b8cd-4336-9264-28b747050c33)
