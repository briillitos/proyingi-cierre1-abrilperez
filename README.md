# proyingi-cierre1-abrilperez
---

**Abril Pérez** · Cierre de parcial 1 · Proyecto de ingeniería

---

## 1. Criterios de viabilidad

Para elegir entre mis tres ideas las evalué con estos criterios:

| Criterio | Qué significa |
|---|---|
| Problema común | ¿Mucha gente lo vive? |
| Cercanía personal | ¿Es un problema que yo conozco o he vivido? |
| Novedad | ¿Hay pocas soluciones accesibles que ya lo resuelvan? |
| Factibilidad técnica | ¿Puedo construir un prototipo con mis recursos? |
| Costo y materiales | ¿Puedo conseguir lo necesario a un precio razonable? |

---

## 2. Ideas evaluadas

### Idea 1: Alarma de pendientes tipo reloj despertador
Un dispositivo que funciona como despertador, pero para recordar tareas y pendientes.

### Idea 2: Detector de mala postura
Un dispositivo que detecta cuando la persona adopta una mala postura y le avisa para corregirla.

### Idea 3: Rodillera de cuidado de rehabilitación
Una rodillera con sensores dentro que ayuda a vigilar el movimiento de la rodilla durante la recuperación.

### Comparación

| Criterio | Idea 1: Alarma | Idea 2: Postura | Idea 3: Rodillera |
|---|:---:|:---:|:---:|
| Problema concreto de mi entorno | parcial | sí | sí |
| Parte física fabricable | sí | sí | sí |
| Sensor o actuador | parcial | sí | sí |
| Construible en ocho sesiones por participante | parcial | sí | parcial |
| Qué tan seguro estoy de lo anterior | medio | medio | medio |

---

## 3. Mi elección

Elegí la **rodillera de cuidado de rehabilitación** por tres razones:

1. **Es un problema muy común.** Las lesiones y molestias de rodilla afectan a muchas personas, y la rehabilitación suele hacerse en casa sin que nadie vigile si los movimientos son correctos.
2. **Es un problema cercano a mí.** Lo conozco de forma personal, así que entiendo lo que necesita el usuario.
3. **Hay pocas opciones accesibles.** Existen rodilleras ortopédicas y algunas con tecnología, pero casi no hay una sencilla y económica con sensores pensada para el cuidado en casa. Eso deja espacio para proponer algo nuevo.

---

## 4. Investigación

### 4.1 Ejemplos reales de las tres ideas

| | Idea 1: Alarma | Idea 2: Postura | Idea 3: Rodillera |
|---|---|---|---|
| Ejemplo real | Reloj BBrain (para demencia) | Upright Go S | Rodilleras ortopédicas comunes (sin sensores) |
| Fuente | https://nuraconfort.com/producto/reloj-recordatorio-personalizado/ NuraConfort | [Pendiente: link] | [nuraconfort](link) |
| Comentario | Pensado para otro público, no para pendientes cotidianos | Detecta postura de espalda con un sensor pegado | Dan soporte, pero no miden ni avisan nada |


### 4.2 Fuentes de la idea elegida

| Fuente | Autor / año | Qué aprendí |
|---|---|---|
| [Tipos de rodilleras ortopédicas adecuadas para cada condición](link) | [Pendiente] | [Pendiente: qué tipos existen y para qué sirven] |
| [Knee Braces: Current Evidence and Clinical Recommendations for Their Use](link) | [Pendiente] | [Pendiente: qué dice la evidencia sobre su uso] |

---

## 5. Lo que me falta averiguar

- [ ] **Sensor:** ¿Qué sensor me sirve para medir el ángulo de flexión de la rodilla (por ejemplo un IMU o un sensor flex) y cuánto cuesta?
- [ ] **Diseño base:** ¿Qué diseños de rodillera existentes puedo usar como referencia para la estructura?
- [ ] **Comodidad:** ¿Cómo acomodo los sensores y la electrónica dentro de la rodillera sin que molesten ni se humedezcan con el sudor?
- [ ] **Alimentación:** ¿Qué batería necesito y cuánto debe durar?
- [ ] **Aviso al usuario:** ¿Cómo le aviso si hace un movimiento incorrecto (vibración, luz, app)?

---

## 6. Archivos de diseño (.dxf)

Piezas diseñadas para corte láser. Los archivos están en la carpeta `/dxf`.

| Parámetro | Prueba de kerf | Cajita |
|---|---|---|
| Largo | 100 mm | 80 mm |
| Ancho | N/A | 50 mm |
| Alto | 20 mm | 60 mm |
| Kerf | 0.2 mm | 0.2 mm |
| Espesor del material | 3 mm | 3 mm |
| Ranura | 2.8 mm | 2.8 mm |

> **Nota:** el kerf es lo que "come" el láser al cortar. La ranura de 2.8 mm es menor que el espesor de 3 mm para que las piezas encajen justas.

### Vista previa

<!-- Agrega aquí las imágenes: ![Cajita](imagenes/cajita.png) -->

---

## 7. Siguientes pasos

1. Resolver las preguntas pendientes de la sección 5.
2. Elegir sensor y microcontrolador.
3. Hacer un primer prototipo de la cajita y probar su tamaño sobre la rodilla.
4. Probar la comodidad con los componentes dentro de la rodillera.
