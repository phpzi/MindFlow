# **Comparativa: Android nativo vs Flutter vs PWA**
|                                         |                            Android nativo                           |                       Flutter                       |                    PWA                    |
|-----------------------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------:|:-----------------------------------------:|
|  1. Lenguaje / herramientas necesarias  | Kotlin, Java / Android Studio (IDE), Android SDK, Gradle (Compilar) | Dart / framework de Google, Android Studio, VS Code | HTML, CSS, JavaScript / editor, navegador |
|  2. Plataformas que soporta             | Solo Android                                                        | Android, iOS, web, Windows, macOS y Linux           | Cualquiera con navegador                  |
|  3. Rendimiento / acceso al hardware    | Máximo / Acceso total                                               | Muy alto / Bueno (plugins)                          | Medio / Limitado                          |
|  4. Coste de desarrollo y mantenimiento | Alto si quieres varias plataformas                                  | Medio                                               | Bajo                                      |
|  5. Caso de uso real (mejor opción)     | Apps con mucho hardware                                             | Apps multiplataforma con poco presupuesto           | Webs instalables y de alcance masivo      |

1. **Lenguaje y herramientas**
    _Android nativo_: Kotlin (o Java) con Android Studio, SDK y Gradle. Es el modelo oficial, así que tiene la mejor documentación. 
    _Flutter_: Dart, con Android Studio o VS Code. Todo son widgets y el hot reload te deja ver los cambios al momento.
    _PWA_: HTML, CSS y JavaScript, más un manifest y un Service Worker para instalarla y usarla offline. Solo necesitas editor y navegador.

2. **Plataformas que soporta**
    _Android nativo_: solo Android. Para iOS hay que hacer otra app aparte.
    _Flutter_: Android, iOS, web y escritorio con un único código.
    _PWA_: cualquier dispositivo con navegador, aunque en iOS (Safari) va más limitada.

3. **Rendimiento y hardware** 
   _Android nativo_: el mejor rendimiento y acceso total a sensores, Bluetooth, NFC y segundo plano.
   _Flutter_: casi nativo, porque compila a código máquina y dibuja la UI con su propio motor. El hardware se usa con plugins y, si falta alguno, toca escribir código nativo.
   _PWA_: la más limitada. Corre dentro del navegador y tiene poco acceso a Bluetooth, NFC o tareas en segundo plano.

4. **Coste y mantenimiento**
   _Androd nativo_: razonable si solo haces Android, pero se duplica si quieres iOS (dos equipos y dos códigos).
   _Flutter_: un solo equipo y una sola base de código. A cambio, dependes de Google y de que los plugins estén al día.
   _PWA_: la más barata. No pasa por tiendas y las actualizaciones son instantáneas, pero tiene menos funciones.

5. **Caso de uso ideal**
   _Android nativo_: app de fitness con GPS, sensores y Bluetooth funcionando con la pantalla apagada.
   _Flutter_: app de reservas o delivery para un negocio pequeño que necesita Android e iOS con poco presupuesto.
   _PWA_: tienda online o portal de eventos donde importan el alcance y el SEO, sin obligar a descargar nada.