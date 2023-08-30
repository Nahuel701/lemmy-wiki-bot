# **¿Qué es el bloque génesis de una blockchain?**

[Alejo Blasco](https://wiki.lemon.me/autor/alejoblasco/)

Se le llama bloque génesis al primer bloque de una blockchain. Este es
el principio de la cadena y es la base para la construcción de todos los
demás bloques. Los nodos completos guardan una copia del bloque génesis,
y de todos los que vinieron después, para poder reconstruir las
transacciones en caso de que sea necesario. Veamos de qué se trata el
bloque génesis y sus particularidades en bitcoin y otras blockchains.

## ¿Cuál es la función de un bloque génesis?

El bloque génesis es distinto a todos los demás porque no tiene ningún
predecesor. En una blockchain, la información se guarda en bloques
unidos a través de una función criptográfica. Cada bloque contiene sus
transacciones y una referencia al bloque anterior. Este no es el caso
del bloque génesis, ya que es el primero de la cadena.

Aunque el bloque génesis no cumple ninguna función especial, es el punto
de partida que da lugar a la construcción de la blockchain. En el caso
de que nos descarguemos un nodo completo de Bitcoin, nuestra computadora
va a procesar desde el bloque génesis hasta el más actual para generar
una copia completa y actualizada de la blockchain. Así nos vamos a poder
comunicar con otros nodos que hicieron lo mismo y vamos a formar parte
de la red.

El bloque génesis fue el que dio lugar a la primera transacción
*coinbase*, es decir la que emite nuevos BTC y los manda a la *wallet*
del minero que formó el bloque. Desde el 2009 hasta el 2012, cada nuevo
bloque contenía una transacción *coinbase* de 50 BTC. Luego del primer
*halving,* este valor bajó a 25 BTC. Hoy, después de 2 halvings más, se
encuentra en 6.25 BTC por bloque.

## Datos interesantes del bloque génesis de Bitcoin 

-   Los 50 BTC emitidos no se pueden gastar

En el bloque génesis se encuentra la transacción que emite los primeros
50 BTC en existencia. Sin embargo, por una razón desconocida, esos BTC
no se pueden transferir. Algunos piensan que fue un error de código y
otros que fue una decisión intencional de Satoshi Nakamoto, el creador
de Bitcoin.

La *wallet* que recibió esos primeros BTC no realizó ningún movimiento.
Sin embargo, a lo largo de los años recibió 18,55 BTC en más de 3400
transacciones distintas. Posiblemente, estos fueron usuarios de Bitcoin
que decidieron mandarle a Satoshi algunas fracciones de BTC en forma de
agradecimiento.

-   El bloque génesis contiene un mensaje

Dentro de la transacción *coinbase* del bloque génesis, Satoshi escondió
el siguiente mensaje "*The Times 03/Jan/2009 Chancellor on brink of
second bailout for banks*". Lo cual se podría traducir a "El Canciller
está a punto de dar un segundo rescate a los bancos". Este fue el
titular del diario britanico *The Times* del 3 de Enero del 2009 y hace
referencia a la decisión de los gobiernos de imprimir dinero para salvar
a los bancos y grandes empresas después de la fuerte crisis económica.

-   No hubo pre-minado

El pre-minado hace referencia a la creacion de monedas antes de que una
blockchain sea abierta al público. Algunos proyectos utilizan esta
técnica para favorecer a los desarrolladores o inversores tempranos
permitiéndoles obtener monedas antes del lanzamiento oficial de la
blockchain.

Satoshi Nakamoto publicó desde el primer momento el código de Bitcoin
para que cualquiera se lo pueda descargar y empezar a minar. Aunque en
un principio los mineros eran pocos y lograron acumular muchos BTC, la
distribución fue justa ya que el minado era público.

-   Pasaron 6 dias entre el primer bloque y el segundo

Según el *timestamp* que deja cada bloque luego de ser agregado a la
blockchain, el bloque génesis fue creado el 3 de enero. Sin embargo, el
bloque siguiente recién se crea el 9 de enero. No se sabe a ciencia
cierta porque hay un espacio de 6 días entre el primer bloque y el
segundo.

Algunos dicen que Satoshi se tomó esos días para hacer pruebas con la
red y luego decidió borrar los bloques formados y empezar de cero con el
bloque génesis. Otros dicen que ese simplemente fue el tiempo que le
tomó a su computadora encontrar un bloque válido.

-   La primer transacción de BTC

Los primeros 169 bloques de BTC contenían una sola transacción, la que
emite 50 BTC y los manda a la *wallet* del minero. Fue recién en el
bloque 170, el 12 de enero del 2009, cuando se dio el primer envío real
de BTC entre usuarios. Satoshi Nakamoto le mandó 10 BTC a Hal Finney, un
conocido criptógrafo y contribuidor temprano de Bitcoin. En [esta
página](https://www.blockchain.com/btc/tx/f4184fc596403b9d638783cf57adfe4c75c605f6356fbc91338530e9831e9e16)
podemos ver los detalles de la transacción.

## Bloques génesis de otras cryptos

-   Litecoin: 8 de Octubre del 2011

Una de las primeras criptomonedas en aparecer luego de Bitcoin fue
Litecoin. El bloque génesis de esta blockchain fue minado por su
creador, Charlie Lee. Luego de un periodo de testeo de 5 días, el código
de Litecoin se hizo público y la red quedó oficialmente abierta.

-   Ethereum: 30 de Julio del 2015

Aunque el lanzamiento oficial de la red de Ethereum fue en Julio del
2015, las redes de prueba ya estaban disponibles desde hace unos meses
atrás. Había una recompensa de 25.000 ETH para los desarrolladores que
se dediquen a jugar con la red de prueba y reportar posibles errores.
Luego de este periodo, el 30 de julio se minó el bloque génesis con una
emisión de 5 ETH.
