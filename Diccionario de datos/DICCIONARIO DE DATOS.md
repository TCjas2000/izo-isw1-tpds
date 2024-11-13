
**DICCIONARIO DE DATOS:**

Vehículo = Patente + Velocidad

Cámara = IDCamara + Descripción  + IP + Modelo

Fecha = Fecha + Hora

Ubicación = CoordX + CoordY

|**Nombre**|**Descripción**|**Longitud**|**Tipo**|**Dominio**|
| :- | :- | :- | :- | :- |
|Fecha|Fecha al momento de la detección del vehículo|-|Fecha|Continuo|
|Hora|Hora al momento de la detección del vehículo|-|Fecha|Continuo|
|IDCamara|Código de identificación único de la cámara|20|Entero|Continuo|
|Patente|Patente del vehículo|10|Entero|a-Z 0-9|
|Velocidad|Velocidad a la que circula el vehículo|7|Float|Continuo|
|Descripción|Descripción del vehículo|-|Texto|a-Z|

|CoordX|Ubicación del paso del vehiculo|100|Float|Continuo|
| :- | :- | :-: | :- | :- |
|CoordY|Ubicación del paso del vehiculo|100|Float|Continuo|
|IP|Codigo IP de la camara|50|Entero|Continuo|
|Modelo|Modelo de la camara|20|Char|a-Z 0-9|

