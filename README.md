Repo del Badge Life de la Euskal Encounter

## IDEAS Varias

Diseño central del logo de la euskal "begitxo" con pantalla central redonda

En lugar de diseñar un badge distinto cada año (como hacen muchas conferencias), podemos mantener el mismo "begitxo", e ir evolucionando únicamente el firmware y los cuerpos intercambiables. Esto reduce el coste de desarrollo y crea una identidad reconocible.

# Concepto "begitxo"

- Pantalla circular = iris / pupila
- LEDs RGB = brillo
- Sensor de luz = dilatación de pupila
- IMU = el ojo "mira" hacia donde se mueve
- Micrófono = parpadea cuando hay ruido
- Vibración = reacciona

Begitxo siempre es el mismo. Lo que cambia es el cuerpo.

## El cuerpo

El cuerpo sería un SAO grande.
Cada edición podría sacar uno distinto. 
La colección se hace sobre el cuerpo, no sobre la electrónica.

Ejemplos:
- Robot
- Dragón
- Pulpo
- Fantasma
- Alien
- Cthulhu
etc.

# Hadware + Software

## MCU - **ESP32-S3**

- USB nativo
- BLE
- WiFi
- bastante RAM
- PlatformIO
- TinyUSB
- LVGL

- ❓Joypad + 2/3 botones
- Pantalla - TFT Circular
- Conectores:
  - 1-2 SAO (1 arriba y 1 abajo)
  - USB-C
  - ❓GPIO extra para hacking

## Sensores

- ✅ altavoz/buzzer
- ❓ IMU / acelerómetro
- ❓ sensor de luz
- ❓ micrófono MEMS
- ❓ sensor Hall / proximidad
- ❓ acelerómetro
- ❓ ~~temperatura~~
- ❓ ~~humedad~~

## Alimentación

- Batería LiPo.
- Carga por USB-C.

## Software

- SDK
- Documentación
- Ejemplos (Hello World...)

# Equipos:
(puede haber menos equipos que hagan más cosas o gente que esté en varios)

## Hardware

- PCB - KiCad
- Alimentación
- USB
- SAO
- producción

## Equipo Firmware

- Drivers
- animaciones
- BLE
- menús
- OTA (si interesa)

## Equipo Diseño

- _Begitxo_
- Packaging
- Pegatinas
- Manual
- Web

## Equipo Juegos

- Snake
- Pong
- Tamagotchi
- CTF
- Easter eggs

## Equipo Badge Life

- Normativa
- Concurso
- charlas
- Discord
- GitHub

## Equipo SAO

- Definir estándar
- Conector
- Documentación
- Ejemplos

## Equipo Producción

- JLCPCB
- BOM
- Componentes
- Montaje
- Tests
- QA

# Cronograma

## Fase 1

- Concept art
- Logo de Badgelife EE
- Nombre del Badge
- Forma (begitxo)

## Fase 2

- Electrónica
- Esquemáticos
- PCB
- Prototipo

## Fase 3

- Firmware básico
- Boot
- Pantalla
- LEDs
- USB
- SAO

## Fase 4

- SDK
- Documentación
- Ejemplos

## Fase 5

- Primer prototipo
- Validación
- Correcciones

## Fase 6

- Producción
- Lanzamiento


# Actividades

## Antes de la Euskal

- Concurso para elegir la animación de arranque.
- Concurso para diseñar la carcasa o el "cuerpo" oficial.
- Hackatón online para desarrollar demos.
- Publicación del SDK para que la gente llegue con ideas.

## Durante la Euskal

### Charla

**Cómo diseñamos el badge de la Euskal**
Desde la idea hasta el PCB.

---

### Talleres

1. **Aprende a soldar tu primer badge**
2. **Programa tu primer firmware para el badge**
3. **Diseña tu primer SAO**: Desde KiCad hasta la fabricación.

### Competición - **Mejor firmware**

- más útil
- más divertido
- mejor interfaz
- mejor juego
- mejor hack
- mejor uso del hardware

### Competición - **Mejor SAO**

- diseño artístico
- utilidad
- hardware
- locura
- mejor acabado

### Competición - **Mejor modificación física**

- Pintura
- Impresión 3D
- Carcasa
- Iluminación

---
## Otras actividades:
 
### CTF del badge
Resolver retos usando únicamente el hardware del badge.

### Easter Egg Hunt
Descubrir funciones ocultas.

### Badge Bingo
Interactuar con otros asistentes para completar una tarjeta de objetivos.

### Speed Hacking
Dispones de X horas para crear una mejora funcional o estética para el badge.

### Lightning Talks
Presentaciones de cinco minutos donde cualquiera puede enseñar su firmware, su SAO o un truco que haya descubierto.

### Clínica del Badge
Una mesa permanente con herramientas para reparar, actualizar o modificar badges y SAOs, atendida por voluntarios.

### Galería de SAOs
Exposición abierta donde los participantes muestran sus diseños con una breve explicación técnica y artística.

### "Firmware Arena"
Los autores presentan su creación en directo y el público la prueba y vota.

### "SAO Swap"
Intercambio de SAOs entre asistentes para fomentar la colaboración y el coleccionismo.

## Otras ideas:

- Que el badge **"reconozca" a otros begitxos**. Cada badge podría emitir un identificador mediante BLE o ESP-NOW. 
- Cuando dos asistentes se acercan, los ojos se miran, la pupila cambia de tamaño y ambos desbloquean una animación o un logro. 
- Si un participante consigue "mirar a los ojos" a suficientes personas, puede desbloquear nuevos comportamientos, minijuegos o elementos cosméticos. 

# Objetivos realistas para el primer año

## Hardware

- Definir el hardware concreto del badge
- Definir cuántos puertos SAO tendrá
- Funcionalidades previstas para los SAO

## Software

- Identificación del usuario (y que también valga como entrada oficial?)
- Menú
- Animaciones del ojo
- BLE o ESP-NOW básico
- API documentada
- Algún minijuegos sencillo (tipo snake)
- Un huevo de Pascua

## Comunidad

-  Repositorio en GitHub
-  Documentación pública
-  Taller de montaje
-  Charla de presentación
-  Concurso de firmware
-  Concurso de SAOs
-  SAOs creados por la comunidad
