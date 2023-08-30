# **¿Qué es una dirección bitcoin?**

-   [Jazmín Nogaró](https://wiki.lemon.me/autor/jazminnogaro/)

Una dirección de bitcoin es un identificador único de nuestra *wallet*
que nos va a servir para enviar y recibir transacciones. Las
direcciones, también llamadas llaves públicas, son análogas al CBU del
sistema bancario. Cuando queremos que alguien nos envíe BTC, le debemos
mandar nuestra dirección o mostrar el código QR que la representa. Hay
diferentes tipos de direcciones que fueron surgiendo a lo largo de los
años, pero en general tienen un aspecto parecido a este:

*bc1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh*

## Características de las direcciones de bitcoin

-   Libres y gratuitas

Las direcciones son gratuitas y no hay límites en cuanto a la cantidad
que podemos tener. Es más, hay ciertas *wallets* que nos crean
automáticamente un nueva dirección cada vez que recibimos una
transacción para mejorar nuestra privacidad. Más adelante hablaremos de
eso. Los requerimientos para obtener un *wallet* son mínimos, no
necesitamos más que bajarnos una aplicación en el teléfono o en la
computadora.

-   Privadas y transparentes

Todos los movimientos asociados a nuestra dirección quedan grabados
públicamente en la blockchain. A través de un [*block
explorer*](https://wiki.lemon.me/que-es-un-block-explorer-y-como-se-usa/),
podemos fácilmente ver el saldo actual y todas las transacciones que
hizo una dirección. Por default las direcciones son anónimas ya que no
están atadas a nuestra identidad. Sin embargo, tenemos que ser
conscientes que al compartirla le estamos dando el poder a cualquier
persona de ver nuestros movimientos.

Por esa razón algunas billeteras nos crean una nueva dirección cada vez
que recibimos fondos. Así, si alguien la busca en un *block explorer,*
solo va a poder ver una pequeña parte de nuestros movimientos.

## Diferentes tipos de direcciones de Bitcoin

-   Direcciones Legacy (P2PKH)

Estas son las direcciones originales del protocolo de Bitcoin y siguen
vigentes y funcionando. Se les llama *Pay to Public Key Hash* (P2PKH) ya
que se derivan pasando a la llave pública por una función hash. Las
direcciones Legacy se pueden identificar ya que empiezan con un 1.

-   Direcciones multisig (P2SH)

Estas direcciones se usan para crear [*wallets
multisig*](https://wiki.lemon.me/que-es-una-wallet-multisig/), es decir,
direcciones que están controladas por más de una billetera. El nombre
*Pay to Script Hash* (P2SH) significa que se le paga a un *script* (o un
programa) en vez de a una simple dirección. Ese programa es el que
permite tener más flexibilidad a este tipo de direcciones, por eso se
usan para crear canales de [*Lightning
Network*](https://wiki.lemon.me/que-es-lightning-network/). Estas
multisig se identifican porque empiezan con un 3.

-   Direcciones SegWit (Bech 32)

Las direcciones SegWit fueron implementadas en el 2017 después de un
largo debate dentro de la comunidad Bitcoiner. El nombre viene de
*Segregated Witness* y hace referencia a que la firma de las
transacciones está separada o segregada de la estructura principal. Esto
provoca que las transacciones usando direcciones SegWit sean más baratas
porque ocupan menos lugar en la blockchain. Podemos identificar estas
direcciones porque empiezan con bc1.

-   Direcciones Taproot (P2TR)

La última actualización de Bitcoin el año pasado trajo un nuevo tipo de
direcciones llamadas *Pay to Taproot.* Estas tienen la misma
programabilidad que las direcciones multisig pero con una ventaja, las
transacciones se ven iguales a las regulares. Usando *Taproot,* no hay
forma de distinguir una transacción *multisig* de una convencional.
Esto, aparte de traer más privacidad a la red, mejora la escalabilidad
porque hace que las transacciones complejas ocupen menos lugar en la
blockchain. Las direcciones de *Taproot* empiezan con bc1p.

¿Cómo se crea una dirección bitcoin?

Para un usuario, la creación de una dirección es tan simple como
descargar una *wallet*. Pero, ¿qué pasa por detrás? El proceso para
obtener una dirección de bitcoin puede variar de *wallet* a *wallet,* a
continuación vamos a describir el estándar impuesto por el Bitcoin
Improvement Proposal 39 (BIP-39).

El primer paso para crear una dirección de bitcoin es obtener un número
binario aleatorio. Este se va a separar en 12 números distintos y cada
uno va a corresponder a una lista preestablecida de 2048 palabras. A
esta se le llama *seed phrase* o frase de recuperación, y se ve así:

*witch collapse practice feed shame open despair creek road again ice
least*

La seed phrase se va a usar para generar la llave privada, la cual
generalmente se suele mostrar en formato hexadecimal.

Quedaría algo como esto:

*1E99423A4ED27608A15A2616A2B0E9E52CED330AC530EDCC32C8FFC6A526AEDD*

Esta llave privada se pasa por un algoritmo de curvas elípticas para
obtener la llave pública. El proceso para pasar de llave privada a
pública es sencillo, pero lo opuesto es casi imposible. Por eso es
seguro compartir nuestra llave pública sin miedo a que nos puedan robar
los fondos.

Una vez obtenida la llave pública, se pasa por una función hash para
finalmente obtener la dirección. Entonces, aunque a veces se usen como
sinónimos, la llave pública no es lo mismo que la dirección.

Ejemplo de una dirección:

*1BvBMSEYstWetqTFn5Au4m4GFg7xJaNVN2*

## Entonces ¿Cómo puedo saber mi dirección bitcoin?

Cualquier *wallet* nos debería mostrar nuestra dirección al querer
recibir una transacción. Puede que aparezca bajo la solapa de "Recibir"
o "Depositar". Algunas *wallets* nos dejan elegir si queremos hacer el
deposito a una dirección *Legacy* o *SegWit*. Como dijimos antes, las
transacciones con *SegWit* son un poco más baratas.

Vale la pena aclarar que, aunque cada vez que queremos hacer una
transacción nuestra *wallet* nos muestre una dirección distinta, todas
las anteriores siguen siendo válidas. Es decir que si enviamos BTC a una
dirección vieja también va a llegar.

En resumen, una dirección bitcoin es un conjunto de números y letras que
identifica a nuestra wallet y nos permite recibir BTC. Las direcciones
son gratuitas y no están atadas a nuestra identidad, pero los
movimientos se guardan públicamente en la blockchain. Hay diferentes
tipos de direcciones vigentes en la red de Bitcoin, cada una tiene sus
características y funciones.

Para obtener una dirección primero hay que pasar por una *seed phrase*,
llave privada, llave pública. Aunque como usuarios no tenemos que
conocer ese proceso, solo interactuamos con la *seed phrase* y la
dirección.
