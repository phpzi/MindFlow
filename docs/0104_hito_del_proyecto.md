# Plantilla: propuesta del Proyecto A

---

## 0 · Datos

|                      |                          |
|----------------------|--------------------------|
| **Nombre de la app** | MindFlow                 |
| **Autor/a**          | Sonia González Rodríguez |
| **Fecha**            | 30/09/2026               |

---

## 1 · La idea en una frase

> 
> Una app que permite a los usuarios jóvenes realizar un seguimiento diario de sus emociones
para mejorar tu salud mental y el bienestar diario.


## 2 · El problema

>  La salud mental de los jóvenes de entre 16 y 30 años ha empeorado bastante aumentando la sensación
> de ansiedad, estrés o depresión.
> Hoy en día, se acude a consultas de profesionales psicólogos siendo muy caras sin poder acabar
> la terapia. Además de libros de autoayuda genéricos que no te solucionan las dudas personales y
> como afrontarlas.


---

## 3 · Personas usuarias

> Lucas, 16 años, de habla hispana, que esté familiarizado con uso de la tecnología, que pueda 
> usarlo en el momento que la necesite como antes de un examen, en casa, en la biblioteca, se dedica
> 2-3 minutos de uso cada vez y si no tienen datos, wifi... siempre pueden llamar al equipo psicológico para
> ser atendido.


---

## 4 · Funcionalidades

### Imprescindibles (sin esto la app no tiene sentido)

| #   | Funcionalidad                                                                |
|-----|------------------------------------------------------------------------------|
| F1  | Registro diario del estado de ánimo (escala de 1 a 5 con emojis)             |
| F2  | Historial con gráfico semanal para ver la evolución del ánimo                |
| F3  | Ejercicio de respiración y meditacion guiado con animación y audio relajante |


### Opcionales (si sobra tiempo)

| #  | Funcionalidad                                                            |
|----|--------------------------------------------------------------------------|
| O1 | Recordatorio diario con una notificación a la hora que elija el usuario  |
| O2 | Frase o consejo de bienestar del día                                     |

---

## 5 · Pantallas

| Pantalla         | Para qué sirve                                                                  | Se llega desde |
|------------------|---------------------------------------------------------------------------------|----------------|
| 01 Inicio        | Resumen de hoy (si ya registró su ánimo, clima) y accesos a las demás pantallas | (arranque)     |
| 02 Reg. de ánimo | Elegir cómo me siento, escribir una nota y guardar                              | Inicio         |
| 03 Respiración   | Ejercicio guiado con animación y audio                                          | Inicio         |
| 04 Ayuda         | Aviso de que la app no sustituye a un profesional. Tfno de apoyo                | Inicio         |                

---

## 6 · Bocetos

> Dibuja las pantallas principales. A mano y fotografiado es válido.
> Pega aquí las imágenes o indica el nombre de los archivos adjuntos.
>
---
<img  src="res/01_inicio.jpg" alt="Pantalla Inicio">

## 7 · Qué datos guarda la app

| Tipo de dato      | Campos                                           | Ejemplo                                                       |
|-------------------|--------------------------------------------------|---------------------------------------------------------------|
| Registro de ánimo | id, fecha/hora, nivel (1-5), nota, temp y tiempo | 30/09/2026 12:10, nivel 2, "entrega practica", 20 °C, nublado |
|                   |                                                  |                                                               |

---

## 8 · Encaje con los requisitos del módulo

> Apartado obligatorio: ninguna casilla puede quedar vacía.

| Requisito                                                             | Dónde encaja en tu app | Tema |
|-----------------------------------------------------------------------|------------------------|------|
| **Persistencia de datos** — la información sobrevive al cerrar la app |                        | 4    |
| **Servicio web** — la app consulta datos por internet                 |                        | 5    |
| **Sensor o localización**                                             |                        | 6    |
| **Contenido multimedia** — foto, audio, vídeo o animación             |                        | 7    |

---

## 9 · Riesgos

| Lo que me preocupa                                                                          | Plan B                                                                                                                                                     |
|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Que alguien crea que la app sustituye a un profesional y la use en una situación de crisis  | Incluir un aviso claro y una pantalla de Ayuda con el 024 (línea de atención a la conducta suicida) y otros teléfonos de apoyo; la app no diagnostica nada |
| La API del clima falla o el usuario no da permiso de ubicación                              | Guardar el registro sin clima, o dejar que elija su ciudad a mano                                                                                          |

---

## Antes de entregar

- [ ] La idea cabe en una frase.
- [ ] El público es una persona concreta, no «todo el mundo».
- [ ] Hay **3 o 4** funcionalidades imprescindibles, no diez.
- [ ] Cada funcionalidad imprescindible tiene su pantalla.
- [ ] Hay bocetos de las pantallas principales.
- [ ] **Las cuatro casillas del apartado 8 están rellenas.**
- [ ] Está identificado al menos un riesgo con su plan B.
