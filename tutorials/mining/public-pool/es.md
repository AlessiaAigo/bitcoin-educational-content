---
name: Piscina Pública
description: Introducción a Piscina Pública
---

![signup](assets/cover.webp)

**Piscina Pública** no es una piscina cualquiera; es lo que también se conoce como **Solo Pool**. Si tu minero logra minar un bloque, entonces recibes la recompensa completa del bloque, la cual no se comparte con otros participantes de la piscina ni con la piscina misma.

**Piscina Pública** únicamente proporciona una **plantilla de bloque** para que tu minero pueda realizar su trabajo, sin que necesites tener un **nodo de Bitcoin** y el software que se comunica con tu minero. Dado que no estás agrupando tu poder de cómputo con el de otros participantes, tus posibilidades de minar exitosamente un bloque son obviamente muy bajas, lo que lo convierte en algo así como un sistema de lotería, donde a veces un individuo afortunado gana el premio mayor.

![signup](assets/1.webp)

En el **Dashboard** de **Piscina Pública**, aún tienes algunas estadísticas como el **Hashrate Total** de la piscina, así como una distribución de los diferentes tipos de mineros que están conectados a la piscina.

![signup](assets/2.webp)

En las primeras líneas, podemos ver **Bitaxe** con 1323 **Bitaxe** conectados para un total de 649TH/s. **Bitaxe** es un proyecto de **Código abierto** que permite la reutilización simple de un chip de un **ASIC** como el **Antminer S19** en una placa electrónica de **código abierto** para hacer un minero muy pequeño de 0.5TH/s por 15W. Este es el minero que usaremos como ejemplo para este tutorial.

## Añadir un **Trabajador** 👷‍♂️

![signup](assets/cover.webp)

En la parte superior de la página, puedes copiar la dirección de la piscina **stratum+tcp://public-pool.io:21496**.

A continuación, para el campo **usuario**, introduce una dirección de **Bitcoin** que te pertenezca.

Si tienes varios mineros, puedes introducir la misma dirección para todos ellos para que sus **hashrates** se combinen y aparezcan como un solo minero. También puedes distinguirlos añadiendo un nombre distinto a cada uno. Para hacer esto, simplemente añade **.nombretrabajador** después de la dirección de **Bitcoin**.

Finalmente, para el campo **contraseña**, usa **‘x’**.

Ejemplo: Si tu dirección de **Bitcoin** es **‘bc1q2ed8zxq8njqsznkp7gj84n0xwl9dp224uha2fv’** y deseas nombrar a tu minero **« Brrrr »**, entonces deberías introducir la siguiente información en la interfaz de tu minero:

- **URL** : stratum+tcp://public-pool.io:21496
- **USUARIO** : **‘bc1q2ed8zxq8njqsznkp7gj84n0xwl9dp224uha2fv.Brrrr’**
- **Contraseña** : **‘x’**
Si tu minero es un **Bitaxe**, los campos son un poco diferentes, pero la información sigue siendo la misma:
- **URL**: public-pool.io (aquí, necesitas eliminar la parte del principio **‘stratum+tcp://’** y la parte del final **‘:21496’** que se informará en el campo del puerto)
- **Puerto**: 21496
- **Usuario**: **‘bc1q2ed8zxq8njqsznkp7gj84n0xwl9dp224uha2fv.Brrrr’**
- **Contraseña**: **‘x’**
![signup](assets/3.webp)
Unos minutos después de comenzar a minar, podrás ver tus datos en el sitio web de **Public Pool** buscando por tu dirección.

## Tablero de control

![signup](assets/4.webp)

Una vez que estés conectado a **Public Pool**, puedes acceder a tu **Tablero de control** buscando con tu dirección de **Bitcoin** que ingresaste en el campo **Usuario**. En nuestro caso aquí, es **‘bc1q2ed8zxq8njqsznkp7gj84n0xwl9dp224uha2fv’**.

En el **Tablero de control**, se muestra diferente información tanto de tus datos como sobre la red.

![signup](assets/5.webp)

Tienes el **Network Hash Rate** que corresponde al poder de trabajo total de la red de **Bitcoin**.

La **Network Difficulty** indica la dificultad que debe alcanzarse para validar un bloque.

Y **Your Best Difficulty** es la mayor dificultad que has logrado. Si, por casualidad 🍀, alcanzas la dificultad de la red, entonces ganas la recompensa completa del bloque... después de 100 bloques. Tendrías que esperar 100 bloques antes de poder gastarlos.

También tienes la **Block Height** que es el número del último bloque que se minó así como su peso expresado en WU, siendo el máximo 4,000,000.

Abajo, puedes ver todas las estadísticas de cada uno de tus dispositivos individualmente si les has dado un nombre distinto añadiendo **.name** detrás de tu dirección de **Bitcoin** en el campo **Usuario**.