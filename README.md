# SPD_Dojo2
![Tinkercad](Dojo1/Img/Super_Trug.jpg)


## Integrantes 
- Belén Funtanillas
- Agustin Di Leone
- Lucas Da Silva Pinheiro
- Matias Cuervo
- Adolfo Pumacayo
- Diego Uthurburu


## Proyecto: SUBTE.
![Tinkercad](Dojo1/Img/semaforoEnArduino.png)


## Descripción
permita al usuario saber a qué estación de subte está
llegando, aparte el sistema muestra las estaciones que faltan hasta llegar a destino,
para ello debemos utilizar 4 LEDs y el display de 7 segmentos. Esta vez el buzzer
deberá emitir un sonido diferente cada vez que se llegue a una estación.
El sistema deberá arrancar apagado, luego de presionar el botón empezará y hará lo
pedido.


## Funciónes principales
Estas funciones se encargan de encender y apagar los leds.

LED_RED, LED_GREEN, LED_YELLOW, LED_RED_TWO, LED_GREEN_TWO,LED_YELLOW_TWO,
 SONIDO, son #define que utilizamos para agregar los leds y Piezo o Buzzer , asociandolo a pines de la placa arduino.

(Esta funcion se encarga de prender los Led del mismo color al mismo tiempo, pudiendo indicarle ademas la duracion )

~~~ C++ (lenguaje en el que esta escrito)
void prender(int ledUno, int ledDos, int tiempo)
{
	  digitalWrite(ledUno, HIGH);
  	digitalWrite(ledDos, HIGH);
  	delay(tiempo); 
}
~~~
  (Esta funcion se encarga de apagar los Led del mismo color al mismo tiempo)
~~~ C++ (lenguaje en el que esta escrito)
void apagar(int ledUno, int ledDos)
{
  	digitalWrite(ledDos, LOW);
  	digitalWrite(ledUno, LOW);
}
~~~

## :robot: Link a los proyectos

-[ver proyecto](https://www.tinkercad.com/things/fROji6YbE7s-super-trug/editel?sharecode=7sJjtdV6HB2lzgoVJFzteLHUV6UUO2PUq_lvnrYaJLY)

## :tv: Link al video del proceso
- [video](https://www.youtube.com/watch?v=VyGjE8kx-O0)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---
