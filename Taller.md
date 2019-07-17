### Las máquinas también sueñan, robotas feministas para Twitter
---

### Bienvenides :)

Este es un taller de bots donde la idea es que hagamos una (o muchas) robota(s) feminista(s) para Twitter utilizando gramática o arte generativa.

Yo soy Steffania Paola, activista feminista brasileña; desarrolladora web, diseñadora y artista visual y facilitadora de talleres de seguridad digital y programación. Colaboro con diferentes organizaciones latinoamericanas. Fue becada de la Fundación Mozilla (FORD-Mozilla Open Web Fellowship 2016-2017) en Derechos Digitales (Chile).

Formo parte de la colectiva acoso.online, soy co-fundadora de la servidora feminista clandestina.io, parte de la red ciberseguras.org y una de las editoras de la publicación de arte contemporáneo teteia.org.

[@stepaola](https://twitter.com/stepaola) / stepaola.github.io/

---


### Qué es un bot?

[![N|Solid](https://media.giphy.com/media/UH9QKcraNtbxK/giphy.gif)](https://nodesource.com/products/nsolid)

Un bot (aféresis de robot) es un programa informático que efectúa automáticamente tareas repetitivas a través de Internet. Normalmente, estos bots ejecutan tareas simples y estructuralmente repetitivas. (Wikipedia)

Cuando actúan en conjunto se le suele decir granja de bots. Rara vez son influyentes, pero sí ayudan a generar trending topics -los temas que Twitter considera “calientes” en cierto momento y destaca en su plataforma- o generan “ruido” acerca de un tema. (Chequeado)

#### Bots x Trolls

Un troll es alguien enfocado en acosar, criticar o antagonizar de manera provocadora y despectiva. La palabra originalmente refiere a desagradables personajes folclóricos que viven en las cavernas escandinavas. (Chequeado)


### Usos y posibilidades de robotas para internet feminista: diversión + lucha

- [@Botota](https://twitter.com/bototadice)
![enter image description here](https://i.imgur.com/ELUB0RA.jpg)

- [@lachakalarixxo](https://twitter.com/LACHAKALARIXXO)
![](https://i.imgur.com/xfQik76.jpg)
- [@DominemoslasTIC](https://twitter.com/DominemoslasTIC)
![enter image description here](https://i.imgur.com/8pKxtOR.png)

- [Acoso.online Bot para Telegram](https://acoso.online/cl/chat-de-ayuda/)
![enter image description here](https://media.giphy.com/media/jtv3zdHN5DqPQ1j6Fy/giphy.gif)

- [Beta, Bot para Facebook](bit.ly/chamabetanoinbox)
![enter image description here](https://i.imgur.com/2IIc6Zb.jpg)

- [@clitoscope](https://twitter.com/clitoscope)
![N|Solid](https://i.imgur.com/VouA6ki.jpg)
- [@softlandscapes](https://twitter.com/softlandscapes)
![enter image description here](https://i.imgur.com/iF6i8Qe.png)


---
### Nuestras robotas
Conceptualmente en este manual vamos utilizar la teoria de la gramática generativa para crear nuestra robota. 

#### Qué es una gramática generativa 

[![N|Solid](https://media.giphy.com/media/qccVJBDT6xNqU/giphy.gif)](https://nodesource.com/products/nsolid)

Gramática generativa es un modelo gramatical cuyo objetivo es formular las reglas y principios por medio de los cuales una hablante es capaz de producir y comprender todas las oraciones posibles y aceptables de su lengua. (Wikipedia)

Ejemplo: 
Supongamos que hay una maquina donde tu eliges algunos colores y tipos de ropas. Todos los días la máquina hace una combinación para ti basado en los tipos de ropas y colores que te gusta. Si con ese concepto creas frases, tenemos un bot basado en una gramática generativa.

### Manos a la obra!
1. Concepto de la robota: ideas? 
- Cual será el '@'
- La foto de capa
- Imagen de perfil
- Descripción 

2. [Crear una cuenta en Twitter](https://twitter.com/i/flow/signup)

3. (logueada en Twitter) Acceder al sitio web: https://cheapbotsdonequick.com/
4. Hacer clic en "Sign in with Twitter"
5. Hacer clic en "Autorizar la aplicación"
6. Si llegaste a la pagina que sigue, estas liste para crear las reglas de la robota. En el espacío después de "Tracery JSON" es donde vamos a escribir nuestro codigo. 

![enter image description here](https://i.imgur.com/RYLoszA.png)

7. Probar con un ejemplo es la mejor manera de entender como funciona y desde ahí empezar a crear tu propia robota. Pega el código que sigue en el espacio y empieza a jugar: 
~~~~ 
{
"origin": ["Buen día para #accion# #quecosa# con #conque# #donde#"]
,"accion": ["explotar","salir","matar","?","?","?","?"]
,"quecosa": ["Facebook","el patriarcado","al machitroll","?","?","?"]
,"conque": ["una cuchara","el cifrado","?","?","?","?","?"]
,"donde": ["en la cocina","en el auto","?","?","?"]

} 
~~~~
- **En "origin" es donde viene la estructura de nuestra frase**
- **Todo que está con "#" en "origin" es lo que se va a mezclarse en la frase**


8. Con el codigo allá al clicar en "refrescar" puedes mirar las posibilidades de combinaciones con las palabras que definimos en nuestro ejemplo:

![enter image description here](https://i.imgur.com/ZcVL3jc.png)

- Si clicas en "tweet" ese texto se va a publicar en la cuenta de Twitter de tu robota.

- Donde ves "Never" puedes definir de cuanto en cuanto tiempo tu robota va a decir algo en Twitter.
- En "Don't reply" tienes la posibilidad de elegir que la robota conteste (Reply) o no conteste (Don't reply) cuando alguién le envía un mensagen en Twitter. Si la elección es "Reply", ella va a contestar con una combinación de palabras con la misma regla que ya creaste. 
- En "Don't share" puedes elegir si el codigo de tu robota queda disponible (Share) o no (Don't share) para el publico en el sitio de Cheap bots done quick
10. Con todo listo tienes apenas que "SAVE" y vas a tener la robota activa en la cuenta de Twitter que creaste para ella. 

![N|Solid](https://media2.giphy.com/media/3og0ISTHRg4HSNKTao/giphy.gif)


---
### Lecturas adicionales
- [Escritura Cyborg: las máquinas también sueñan](https://www.genderit.org/es/articles/edicion-especial-escritura-cyborg-las-maquinas-tambien-suenan)
- [Bestiario de bots: un acercamiento a las poéticas de la escritura automática](http://editorial.centroculturadigital.mx/articulo/bestiario-de-bots)
- [El mundo secreto de los bots](http://www.chequeado.com/investigacion/el-mundo-secreto-de-los-bots-y-los-trolls-y-como-esos-ejercitos-influyen-en-la-politica/)
- [You auto-complete me: romancing the bot](https://deepdives.in/you-auto-complete-me-romancing-the-bot-f2f16613fec8)
