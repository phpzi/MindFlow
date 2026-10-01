# Análisis de limitaciones de un dispositivo

| Datos                                | Valor                                                   |
|--------------------------------------|---------------------------------------------------------|
| Procesador                           | 2,4 ghz Dimensity 6300 8 nucleos                        |
| RAM                                  | 12 GB + 12 GB                                           |
| Almacenamiento libre                 | 512 GB                                                  |
| Pantalla (tamaño,resolucion,densidad)| 6,77", 1080 x 2392px, 387dpi                            |
| Version Android                      | 16                                                      |
| API                                  | 36                                                      |
| Sensores                             | magnetometro, acelerometro, giroscopio, proximidad, luz |
| Bateria (estado, consumo aplicacion) | 6500mAh, estado optimo, 18%                             |


### Conclusiones.

 **Pantalla:** Mi móvil tiene una pantalla de 6,77" y 1080 × 2392 px, muy alta y estrecha.
Con una mano, el pulgar no llega bien a la parte de arriba. Por eso pondré los botones 
importantes en la parte de abajo de la pantalla y usaré tamaños en dp y sp para que se vea bien en 
cualquier móvil.

**Sensores**:En mi lista de sensores aparecen acelerómetro, giroscopio, magnetómetro, proximidad 
y luz, pero no barómetro. Mi app no dependerá de sensores que no todos los móviles tienen. 
Antes de usar uno, comprobaré si existe, y si no está, usaré otra opción (como el GPS) o desactivaré
esa función para que la app no falle.

**Versión de Android:** Mi móvil tiene Android 16 (API 36), que es de las versiones más nuevas.
Conclusión: no todo el mundo tiene un móvil tan actual. Por eso no pondré la API 36 como mínima, 
sino una más baja (por ejemplo, API 26), para que la app pueda instalarse en más móviles.