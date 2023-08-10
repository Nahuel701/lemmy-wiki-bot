# **¿Qué es el script de bitcoin? ¿Cómo funciona?**

[Jazmín Nogaró](https://wiki.lemon.me/autor/jazminnogaro/)

Se le llama Bitcoin Script al lenguaje de programación que hace
funcionar a Bitcoin. Un script es un programa con una serie de
instrucciones que llevan a un fin, como realizar una simple transacción.
Se puede entender a los scripts como [smart
contracts](https://wiki.lemon.me/crypto-for-beginners/que-son-los-smart-contracts-y-para-que-sirven/)
parecidos a los de Ethereum pero más básicos. Bitcoin Script funciona
diferente a lenguajes como Solidity porque no es Turing Complete. Esto
quiere decir que no soporta todos los tipos de instrucciones. En este
artículo vamos a ver cómo funcionan y para qué se puede usar.

Si te gustaría aprender más sobre criptomonedas y blockchain, es hora de
inscribirte en nuestro curso gratis crypto. Ingresa dando clic en el
siguiente botón:

## ¿Cómo funcionan los scripts de Bitcoin?

Cada movimiento de
[Bitcoin](https://wiki.lemon.me/bitcoin/como-funciona-bitcoin/) está
aparejado a un script que dicta los detalles de la transacción. Este
programa verifica las condiciones necesarias para hacer el envío y
determina cómo el que recibe los BTC los va a poder gastar. La mayoría
de las transacciones requieren un script simple que se divide en 2
pasos, el desbloqueo de fondos de una wallet y el bloqueo en otra.

Si Milagros le quiere mandar 0.1 BTC a Tomás, el script va a chequear
que Milagros tenga las llaves privadas correspondientes a esos BTC a
través de su firma digital. Si esta es válida, los BTC se desbloquean y
se vuelven a bloquear pero en la
[wallet](https://wiki.lemon.me/crypto-for-beginners/crypto-wallets-que-son-cual-elegir-y-como-asegurarte-su-seguridad/)
de Tomás en forma de *Unspent Transaction Output* (UTXO), o salida de
transacción sin gastar.

En términos más simples, los BTC que tenemos en nuestra wallet contienen
un script que dice que esas monedas solo se pueden gastar con nuestra
llave privada. Para las transacciones más complejas, hay scripts que
contienen otro tipo de condiciones.

##  ¿Qué se puede hacer con Bitcoin Scripts?

-   *Multisig wallets*

Es posible crear un script que determine que ciertos BTC solo se pueden
gastar presentando 2 o más llaves privadas, así funcionan las [*multisig
wallets*](https://wiki.lemon.me/que-es-una-wallet-multisig/). Esta
función es útil para crear *wallets* compartidas que requieran la
aprobación de ambas partes para realizar una transacción.

Utilizando scripts, podemos decidir cuántas llaves privadas van a estar
asociadas a la multisig y cuántas se necesitan como mínimo para mover
los BTC. Por ejemplo, en una wallet multisig 2 de 3, hay 3 llaves
privadas y se necesitan al menos 2 para hacer una transacción.

-   Time locks

Un time lock es una condición de tiempo que se le agrega a una
transacción. En la red de Bitcoin, y en la mayoría de las blockchains,
el tiempo se mide en bloques. Entonces, podemos crear un script con una
transacción que solo se pueda ejecutar pasados los próximos 100 bloques.

Estas dos funciones, multisig wallets y time locks, son justamente las
necesarias para crear un canal de pago de [Lightning
Network](https://wiki.lemon.me/que-es-lightning-network/). Lightning es
un protocolo construido sobre la red de Bitcoin que permite realizar
transacciones de BTC instantáneas y casi sin comisiones.

## ¿Qué son los OP CODES?

Los lenguajes de programación sirven para que los desarrolladores puedan
crear programas y aplicaciones. Estos lenguajes son solo legibles por
humanos, no por computadoras. Es por eso que el código tiene que pasar
por una traducción para ser ejecutado. Los OP CODES son las
instrucciones que la computadora tiene que seguir para lograr el
objetivo del programa. Los scripts usan OP CODES para comunicarse con el
software de Bitcoin. Veamos algunos ejemplos.

-   OP_CHECKSIG: Verifica la firma digital del enviador, si es válida se
    > puede continuar la transacción.

-   OP_RETURN: Este OP CODE permite el agregado de un pedazo de
    > información arbitraria dentro de una transacción y fue producto de
    > mucha discusión en el pasado. En el 2014, apareció un protocolo
    > llamado Counterparty que utilizaba OP_RETURN para crear tokens
    > dentro de la red de Bitcoin. Esto no fue bien tomado por algunos
    > bitcoiners que pensaban que no se deberían desarrollar
    > aplicaciones sobre Bitcoin porque agregan complejidad y la hacen
    > menos escalable.

##  ¿En qué lenguaje está escrito el código de Bitcoin?

Aunque Bitcoin utilice Bitcoin Script para funcionar, su código no está
escrito en este lenguaje. La implementación original de Bitcoin,
desarrollada por Satoshi Nakamoto, estaba escrita en el lenguaje C++.
Sin embargo, después se desarrollaron otras versiones en Java, Python y
Go. Lo bueno de las blockchains descentralizadas y de código abierto es
que pueden convivir diferentes versiones del mismo protocolo, siempre y
cuando sean compatibles unas con las otras. Esto implica que si hay un
error de código en una versión, solo va a afectar a una parte de los
nodos.

## ¿Por qué Bitcoin Script no es turing complete?

En la teoría, un lenguaje de programación turing complete es capaz de,
dado los suficientes recursos, resolver cualquier problema computacional
que se le presenta. Aunque esto no es posible en la práctica, el término
se usa para describir un sistema que no tiene ninguna limitación
técnica. Los lenguajes más conocidos como Python o Java son turing
complete.

Bitcoin Script no es un lenguaje turing complete porque no necesita
serlo. Al crearlo, Satoshi intentó hacerlo lo más simple posible para
priorizar la seguridad. Como regla general, mientras más complejo es un
sistema, existen más posibles vectores de ataque. Como Bitcoin es
simplemente una red descentralizada de pagos, no necesita un lenguaje
tan complejo.

Ethereum, en cambio, surgió como una blockchain de propósito general
donde se pueden construir aplicaciones descentralizadas. Esto implica
necesariamente el uso de un lenguaje turing complete, en este caso
Solidity.

Entonces, los scripts de Bitcoin son programas que nos dejan ponerle
diferentes condiciones a las transacciones. Las versiones más básicas se
usan en todos los movimientos de BTC, y se pueden desarrollar scripts
más complejos para otros tipos de transacciones. Algunas personas
piensan que se deben usar los scripts para desarrollar más
funcionalidades sobre la blockchain de Bitcoin. Sin embargo, otros
argumentan que Bitcoin cumple su función como red de pagos y no se
deberían hacer cambios que puedan perjudicar su funcionamiento. Ya
veremos qué camino decide seguir la comunidad.
