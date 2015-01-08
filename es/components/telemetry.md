# Telemetría

La teemetría es un proceso de comunicación altamente automatizado con el cúal se efectuan las mediciones y recogidas de datos en puntos remotos o inaccesibles y se transmiten a equipos receptores para su monitorización.

Los drones generalmente incluyen un enlace radio que se usa para las comunicaciones con la Estación de Control en Tierra. APM (el software del autopiloto) permite varias maneras de comunicación:
- puerto serial, generalmente se utiliza con [telemetría por radio](http://copter.ardupilot.com/wiki/3dradio/).
- UDP socket
- TCP socket

Erle-Copter puede utilizar un enlace de telemetría por radio (puerto serie) o un dongle USB WIFI (TCP o UCP).