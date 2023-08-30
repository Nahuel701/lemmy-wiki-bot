# **¿Qué es Lightning Network?**

-   [Alejo Blasco](https://wiki.lemon.me/autor/alejoblasco/)

*Lightning Network* (LN) es un protocolo de capa 2 que funciona
directamente sobre la blockchain de Bitcoin y permite realizar
micropagos en BTC en forma instantánea y muy barata.

¿Cómo funciona? Acumula transacciones fuera de la cadena de bitcoin para
después, si es necesario, guardarlas todas juntas *on-chain*. Como la
información no está siendo toda almacenada de forma directa sobre la
blockchain de Bitcoin, las comisiones son mucho más baratas.

## ¿Por qué necesitamos *Lightning Network*?

Desde la creación de Bitcoin en el 2009, siempre se le cuestionó [la
falta de
escalabilidad](https://wiki.lemon.me/que-es-el-problema-de-escalabilidad-en-blockchain-y-por-que-es-importante/).
Este concepto hace referencia a la capacidad que tiene una red de crecer
sin comprometer sus funcionalidades. En el caso de Bitcoin y de las
criptomonedas en general, la escalabilidad es crecer en usuarios y
cantidad de transacciones sin volverse lenta y cara.

Actualmente, cada bloque de la blockchain de Bitcoin puede contener un
máximo de 1 MB de transacciones. Con un promedio de 250 bytes por
transacción, entrarían como máximo 4000 por bloque. Si calculamos que se
forma un nuevo bloque cada 10 minutos, nos daría que Bitcoin puede
procesar entre 6 y 7 transacciones por segundo (TPS). Esto no es
suficiente para una pequeña ciudad, menos para el mundo entero. Si los
45 millones de Argentinos quisiéramos usar Bitcoin, podríamos hacer al
año solo 5 transacciones cada uno.

Esta falta de escalabilidad causa el aumento repentino de las comisiones
en momentos de congestión. Mientras más gente quiera usar la red, más
van a tener que pagar por cada transacción. Como se puede ver en el
gráfico de más abajo, durante los mercados alcistas del 2017 y del 2021,
las comisiones llegaron a costar más de 50 USD por transacción.

Y, ¿qué pasa si aumentamos el límite de 1 MB por bloque? Este límite se
creó para mantener la descentralización de la red. Si aumentamos el
tamaño de los bloques (en MB), la blockchain pasaría a ser muy pesada
para los nodos que almacenan una copia completa de ella. Si se aumentan
los requerimientos para mantener un nodo, menos gente lo va a hacer,
volviendo a la red más centralizada.

Es evidente que necesitamos una solución alternativa para lograr que
Bitcoin escale sin perder su seguridad y descentralización. Ese es el
objetivo de *Lightning Network.*

## ¿Cómo funciona *Lightning Network*?

Como dijimos antes, *Lightning Network* funciona llevando un registro de
transacciones *off-chain* y después subiéndolas a la blockchain de
Bitcoin todas juntas al mismo tiempo. Esto es posible gracias a los
canales de pago. Un canal de pago es un camino bi-direccional abierto
entre dos personas que les va a servir para intercambiar BTC
*off-chain*. Las transacciones dentro de estos canales son gratis e
instantáneas.

Veamos un ejemplo para que quede más claro: Supongamos que nos vamos de
vacaciones y planeamos quedarnos una semana en un hotel, que nos ofrece
diferentes actividades turísticas y varias opciones de restaurantes.
Para no estar pagando todos los días diferentes gastos, en el *check-in*
nos proponen bloquear un monto de plata de nuestra tarjeta de crédito.
Cada vez que hagamos un gasto, el balance de la cuenta va a ir cambiando
a favor del hotel.

Decidimos bloquear \$1000 y a lo largo de la semana gastamos \$600.
Ahora, en una sola transacción, el hotel va a recibir los \$600 que
gastamos. Este trato simboliza el funcionamiento de un canal de pagos.
Para abrirlo hay que hacer una transacción *on-chain* firmada por ambas
partes. Una vez que ese canal es fondeado con BTC por alguna de las dos,
estas pueden intercambiar todas las transacciones que quieran sin ningún
costo. Con cada transacción, el balance del canal va a cambiar.

## Ahora viene la magia: pagos a terceros

Si tuviéramos que abrir y cerrar un canal con cada persona con la cual
queremos transaccionar, el uso de *Lightning Network* sería muy
limitado. Como para abrir y cerrar canales hay que hacer una transacción
*on-chain* y pagar comisiones, pocas veces nos convendría hacerlo. Sin
embargo, LN nos deja transaccionar con gente sin necesidad de tener un
canal abierto con ellos. Únicamente hay que tener un camino que conecte
al que envía y al que recibe.

Volviendo al ejemplo anterior, al tener un canal abierto con el hotel
podemos transaccionar con él y con la gente detrás de todos sus otros
canales. Es decir que cada persona puede funcionar como intermediario
para enrutar pagos de terceros y no hay límite máximo de intermediarios
de un pago. Por lo cual, si existe un camino entre 2 personas, la red lo
va a encontrar y el pago se podría realizar.

## *Lightning Network*: Experiencia de usuario

Al leer todo esto y entender cómo funciona *Lightning Network*, es
posible que nos preguntemos qué tanto tenemos que saber para usarla.
¿Funciona igual que Bitcoin? ¿Tenemos que saber cómo abrir y cerrar
canales? ¿Cómo se enrutan pagos?

Igual que Bitcoin, LN nos da la chance de correr nuestro propio nodo y
tener total libertad sobre nuestros movimientos. Sin embargo, esto no es
recomendable para la mayoría de los usuarios ya que requiere cierto
conocimiento técnico. Por suerte, existen *wallets* que integran
*Lightning Network* y se ocupan de los canales y el enrutado de pagos.
Esto hace que la experiencia de usar LN sea muy parecida a las
transacciones regulares de bitcoin.

## ¡Ahora en Lemon!

En Lemon habilitamos la red *Lightning Network* para transferencias en
Bitcoin. Sí, ¡ahora vos también vas a tener acceso a esta red para mover
BTC de forma instantánea y a muy bajo costo!

¿Cómo? Es muy fácil. Para recibir BTC a través de *Lightning Network*:

1.  Ingresá a tu cuenta y andá a "Mercado" sobre el menú inferior.

2.  Seleccioná BTC y después "Depositar"

3.  Dentro de las opciones de red, vas a poder elegir *Lightning
    > Network*.

4.  Elegí el monto que querés depositar.

5.  Por último, te mostrará la dirección y el código QR de tu billetera
    > BTC. Copia esa dirección y compartila.

> "Presentar *Lightning Network* a más de un millón de usuarios es un
> gran paso hacia nuestro objetivo principal: hacer que las
> criptomonedas sean accesibles y más fáciles de usar en América
> Latina".
>
> Borja Martel Seward, cofundador de Lemon.

\*Si estás haciendo tu primer depósito en su aplicación Lemon, intente
enviar una pequeña cantidad de criptomonedas primero para familiarizarse
con el proceso. Asegurate siempre de enviar tus crypto a la dirección
correcta, ya que las transacciones criptográficas son irreversibles.
