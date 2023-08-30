# **¿Qué es Bitcoin Core?**

-   [Ramiro Menne](https://wiki.lemon.me/autor/ramiro-menne/)

*Bitcoin Core* es un software de código abierto que sirve para validar y
almacenar transacciones de la red de Bitcoin. Fue registrado bajo la
licencia MIT, una de las patentes menos restrictivas que permite el
acceso, la edición y la copia del software. A las computadoras que se
descargaron y corren *Bitcoin Core* se les llama
[nodos](https://wiki.lemon.me/que-es-un-nodo-validador-en-una-blockchain/).

## ¿Cómo funciona el código de Bitcoin?

Bitcoin, como todo programa computacional, depende de un código fuente
que determina las reglas de la red. Al ser un protocolo descentralizado,
este código no es controlado por una sola persona o institución, sino
que hay varias implementaciones distintas del código de Bitcoin. Todas
cumplen las reglas básicas necesarias para participar de la red, pero
algunas pueden tener funcionalidades extras.\
Podemos comparar Bitcoin y su código fuente con internet y los distintos
navegadores: Para conectarse a internet, los navegadores deben cumplir
con ciertos requisitos. Pero después Chrome, Firefox o Safari tienen
diferencias a nivel de funcionalidades y experiencia de usuario. Como
coinciden en las reglas básicas, pueden coexistir.\
*Bitcoin Core* es, por lejos, la implementación más popular del código
de Bitcoin; más de un 98% de los nodos la utilizan actualmente. Es por
eso que los desarrolladores que trabajan con Bitcoin la usan como guía y
referencia.

## ¿Cómo instalar *Bitcoin Core*?

*Bitcoin Core* es un programa como cualquier otro y se puede descargar
desde su página oficial. La instalación no requiere de ningún
conocimiento especial. En caso que lo instales, el programa va a tener
que procesar todas las transacciones de la blockchain de Bitcoin desde
el 2009 hasta el presente. Dependiendo de la computadora, este proceso
puede tardar unas horas o incluso hasta días. Se recomienda como mínimo
tener 7 GB de memoria disponible y 2 GB de RAM.

## ¿Cómo funciona *Bitcoin Core*?

Una vez instalado y corriendo, el software de *Bitcoin Core* va a estar
conectado a la blockchain de Bitcoin. ¿Sus principales funciones?
Recibir transacciones de otros nodos, verificarlas y propagarlas al
resto de la red. Todo esto se va a hacer de manera automática. Más allá
de eso, *Bitcoin Core* funciona como una *wallet* donde se pueden enviar
y recibir transacciones.\
Cuando descargamos una *wallet* regular, por detrás hay un nodo de
Bitcoin corriendo que se comunica con la blockchain. Lo que hace la
aplicación es crear una interfaz intuitiva y fácil de usar para poder
crear y recibir transacciones. Es decir que la *wallet* funciona como un
intermediario entre el nodo y el usuario. En el caso de usar *Bitcoin
Core*, estamos teniendo acceso directo a un nodo de la blockchain. Esto
implica más privacidad y algunas funciones extra, pero sacrificando su
facilidad de uso.

## ¿Puedo minar con *Bitcoin Core*?

En el 2014, cuando salió el software de *Bitcoin Core*, este tenía una
función integrada de
[minado](https://wiki.lemon.me/que-es-la-mineria-de-criptomonedas/). Sin
embargo, en el 2016 la sacaron porque se volvió obsoleta. Los mineros de
Bitcoin, además de verificar transacciones y formar bloques, tienen que
realizar un [*Proof of
Work*](https://wiki.lemon.me/que-son-proof-of-history-proof-of-work-y-proof-of-stake/)
(*PoW*) para poder recibir la recompensa en BTC. Esta prueba la realiza
la computadora y se va volviendo más difícil mientras más mineros se
unen a la red.\
En los primeros años de la historia de Bitcoin, era posible minar con
cualquier computadora común. A medida que se fueron sumando más mineros,
la *PoW* se volvió más difícil. Esto quiere decir que se necesitaba
hardware especializado para minar. En ese momento empezaron a surgir los
*pools* de minería, programas donde muchos mineros unen su poder de
cómputo para tener más chances de realizar exitosamente la *PoW*.
*Bitcoin Core* eliminó la función de minado ya que no es rentable
intentar minar fuera de un *pool*.

## ¿Debería descargarme *Bitcoin Core*?

Descargar y mantener el software de *Bitcoin Core* implica correr un
nodo en la red de Bitcoin. Esto tiene beneficios tanto para la red como
para nosotros como usuarios. Veamos algunos de ellos.

-   Seguridad de la red: Mientras más nodos tenga la blockchain, más
    > descentralizado será Bitcoin como protocolo y, por ende, más
    > seguro. Aunque ya hayan decenas de miles de nodos manteniendo una
    > copia de la blockchain, ante un ataque o un evento catastrófico,
    > muchos podrían quedar fuera de servicio. Cada nodo extra le da más
    > resiliencia a la red.

```{=html}
<!-- -->
```
-   Privacidad: Al realizar transacciones desde la *wallet* de *Bitcoin
    > Core*, tenemos acceso directo a la blockchain. De esta manera, nos
    > ahorramos el paso por un intermediario que puede llegar a guardar
    > y filtrar nuestra información. Además, al mostrarnos el estado de
    > las transacciones, ya no necesitamos usar un explorador de bloques
    > para verificar eso. Esto dificulta que se relacione nuestra
    > dirección IP con nuestra dirección de BTC.

```{=html}
<!-- -->
```
-   Funcionalidades avanzadas: La *wallet* de *Bitcoin Core* tiene
    > algunas funcionalidades interesantes para usuarios avanzados. Un
    > ejemplo es el *coin control*, una función para elegir exactamente
    > qué monedas queremos gastar en un envío de BTC. Otra, es la que
    > nos permite realizar envíos a diferentes billeteras en la misma
    > transacción, ahorrando en comisiones.

## Un último punto a tener en cuenta...

*Bitcoin Core* es la implementación más popular del código de Bitcoin.
Lo podemos usar como una *wallet* para realizar transacciones propias y
para contribuir a la red verificando transacciones ajenas.\
Si te interesa el funcionamiento de *Bitcoin Core* y te gustaría
probarlo, podés bajarte el *software* de la *testnet* de Bitcoin. Esta
es una red de prueba que funciona exactamente igual que la real pero no
tiene ningún valor monetario. Así vas a poder probar todas las funciones
de la *wallet* sin miedo de perder plata. Otra ventaja es que la
*testnet* de Bitcoin es bastante más liviana que la blockchain real,
entonces la instalación va a ser más rápida.
