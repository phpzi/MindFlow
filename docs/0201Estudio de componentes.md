# 03. Estudio de los componentes 
Varias zonas de los mockups corresponden a datos dinámicos que provienen de una lista o colección. En Compose, estos elementos se definen una sola vez dentro de un ítem y se repiten automáticamente

 <img src="res/Registro.png" alt="Pantalla Registro emocional" width="70%">
 <img src="res/Historial.png" alt="Historial Registro emocional" width="70%">
 
 ## Componentes que se repiten
 ### Tarjeta de emociones 
 ![alt text](image.png)

Cinco estados de ánimo representados por un emoji sobre un fondo de color suave con su respectivo texto debajo, teniendo uno de ellos un borde resaltado como activo. Es un mismo patrón visual repetido en horizontal que se resuelve iterando una colección de datos sobre una Row.

### Etiquetas de selección
![alt text](image-1.png)

Cinco botones interactivos con esquinas redondeadas donde el usuario selecciona una etiqueta que cambia su color de fondo y de texto al estar activa. Al variar la longitud del texto, se organizan dentro de un contenedor FlowRow para que salten de línea automáticamente.

### Fila de registro de historial 
![alt text](image-2.png)

Tarjeta de registro diario con fecha, hora, nota de texto y emoji de estado.
Se repite siete veces en la pantalla de "Historial de Emociones" (Hoy, Ayer, Viernes...). Muestra la fecha y hora arriba a la izquierda, una vista previa de la nota reflexiva debajo, y el emoji correspondiente al estado de ánimo en un recuadro redondeado a la derecha. Es el elemento típico que se renderiza dentro de una LazyColumn.


## Componentes que aparecen una sola vez
Estas piezas son fijas, actúan como contenedores únicos o controles globales y forman el armazón estructural de cada pantalla.

### Tarjeta Horizontal. App Bar
![alt text](image-4.png)

Barra con un boton de retroceso, fecha con estilo de capsula y un icono de informacion. Ocupa el espacio topBar / Row de esta pantalla.

### Historial de Emociones
![alt text](image-5.png)

Incluye la navegación hacia atrás, el título central estático y un icono de agenda/calendario a la derecha. Se resuelve con el hueco topBar de un Scaffold mediante un TopAppBar.

### Fila de pestañas fijas: Esta semana, Mes, Año
![alt text](image-6.png)

Un control horizontal superior con tres opciones fijas para filtrar el histórico, donde la opción activa ("Esta semana") queda resaltada con un fondo blanco. Se maqueta de forma estática usando una TabRow o una Row con botones de opción.

### Barra de navegación inferior
![alt text](image-7.png)

Ocupa el hueco bottomBar del Scaffold. Muestra los cuatro accesos fijos de la app y un botón de acción flotante central (FloatingActionButton) con un icono de más (+) sobre un fondo degradado morado para registrar una nueva emoción.

# Estructura en layot
<img src="res/leyenda.png">
<img src="res/registrodivision.png" alt="Pantalla Registro emocional" width="70%">

 <img src="res/historialdivision.png" alt="Historial Registro emocional" width="70%">