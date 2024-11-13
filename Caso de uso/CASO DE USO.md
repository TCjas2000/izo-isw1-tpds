**CASO DE USO:** 

Camaras de seguridad vial

Actores: Camara (primario)

Camino básico:

` `1-  La cámara envía los datos al sistema

` `2- el sistema registra los datos del vehículo y los evalua

Camino alternativo:

2\.A. Si la velocidad es mayor a 70km/h y menor a 100km/h

2\.a.1 El sistema envía los datos a una API que se encargará de guardarlos en una base de datos

2\.b. Si la velocidad es mayor a 100km/h 

2\.b.1 El sistema envía, 3 veces, los datos recibidos por la cámara a una impresora para que sean impresos

Escenario de éxito: El sistema pudo recibir, evaluar y enviar los datos correctamente a una API

