# GPS

El sistema de posicionamiento global (GPS) es un sistema de navegación por satélite que proporciona información, localización y tiempo en exteriores bajo cualquier tipo de condición climática en cualquier lugar de la Tierra, donde hay una línea de visión sin obstáculos con cuatro o más satélites GPS.

![](https://erlerobotics.com/blog/wp-content/uploads/2014/11/erle-gps1.jpg)

En Erle Robotics generalmente utilizamos un modelo que incorpora el GPS uBlox Neo-7M y la brújula digital HMC5883L. Este kit incluye una carcasa y un pedestal que proporciona una manera de montar el modulo alejado de las posibles fuentes de interferencias.

Este módulo de GPS supera significativamente al GPS Mediatek gracias a la antena más grande y a un chipset de nueva generación. Es una excelente solución para multicopteros y rovers en particular, donde la precisión del GPS es primordial. Caracteriza un circito activo para un 'parche de ceramica en la antena', una batería de reserva recargable para los comienzos calientes, y una memoria EEPROM I2C para el almacenamiento de la configuracion.

Este módulo GPS puede conseguirse en la [tienda de Erle Robotics](https://erlerobotics.com/blog/product/erle-gps-erle-ublox-gps-compass-kit/).

-----

Te recomendaríamos separar el GPS del ardupilot usando un palo (o algo similar). Nuestra experiencia en escenarios practicos nos ha hecho ver que la señal del GPS es mucho mas optima haciendo esto.

![](../img/variado/IMG_20150115_192954.jpg)
