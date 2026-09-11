# SimuLENS — Estética y producción

## 1. Canon visual

**Warm cinematic 2D editorial animation.**

- contornos orgánicos oscuros;
- sombreado suave tipo painted/cel;
- textura de papel **muy sutil**;
- anatomía estilizada pero creíble;
- expresiones legibles en móvil;
- paleta muted teal, coral, cream, navy, blue-grey y warm wood;
- movimiento contenido;
- evitar hiperrealismo, glossy 3D, infantilización y futurismo brillante.

### Regla operativa para Runway / Seedance

> **Preserve the exact texture and palette of the supplied reference images.  
> Do not add extra grain, noise or texture that is not present in the reference.**

La textura de papel forma parte del lenguaje de campaña, pero el generador no debe añadir
grano artificial ni ensuciar un asset limpio.

## 2. Regla visual superior

**Los assets aprobados son autoritativos.**

No redescribir un asset de forma que el modelo lo reinterprete.
Si texto y referencia visual discrepan, manda el asset aprobado más reciente.

## 3. Regla de preservación en edición de imágenes

Cuando se edite una imagen existente aprobada:

> **Preserve exactly the original texture and color palette unless the user explicitly requests a change.**

Los cambios solicitados deben afectar **únicamente** a los elementos expresamente indicados,
por ejemplo:
- posición;
- tamaño;
- objetos;
- personajes;
- poses;
- pantallas;
- otros elementos concretamente mencionados.

No reinterpretar ni alterar por iniciativa propia:
- estilo visual;
- textura;
- grano;
- iluminación general;
- paleta;
- colores.

La imagen que se está editando es la referencia autoritativa para su textura, paleta, iluminación
y acabado visual. Las hojas de personaje y otros assets auxiliares sirven para identidad, vestuario,
forma o detalle del elemento correspondiente, pero no autorizan a cambiar el acabado global de la
imagen editada.

Principio operativo:

> **Si el usuario pide cambiar X, cambiar X y nada más.**

## 4. Cámara

Seedance 2.5 puede manejar múltiples encuadres/escenas dentro del mismo clip.

Por defecto:
- cámara estable;
- planos medios y reacciones claras;
- inserts cuando aporten información;
- push-in/pull-back suaves;
- cortes internos limpios;
- evitar órbitas, temblores, zoom agresivo y movimiento lateral complejo.

Regla útil:

> **Una acción narrativa clara por beat; varios beats pueden convivir en un mismo clip.**

## 5. Formato y resolución

- **Formato:** vertical 9:16.
- **Assets / keyframes:** preferentemente **1440 × 2560 px**.
- **Vídeo generado:** por defecto **720p vertical (720 × 1280)**.
- Cambiar la resolución de vídeo solo si un caso concreto lo justifica.
- Los assets fijos de apertura/cierre se conservan tal como están y no se regeneran.

## 6. Estrategia de clips

Se elimina como regla general la antigua recomendación de “clips de 2–4 s”.

### Fase 1
- por defecto **2 clips**;
- cada clip puede contener **2–3 escenas/encuadres**.

### Fase 2
- por defecto **1 clip**;
- debe incluir animación, VO, música y SFX.

### Fase 3
- por defecto **1 clip**;
- pasar a 2 solo por cambio de escenario, salto narrativo o necesidad técnica.

Principio:

> **Prefer fewer, more coherent clips when Seedance can maintain continuity reliably.**

## 7. Pantallas e interfaces

Minimizar interacciones complejas.

Cuando la precisión importe:
- preparar pantallas, topografías, textos, números, PDFs, Excel, QR, botones y mensajes como assets;
- mantener monitor/tablet/móvil frontal o casi frontal;
- no pedir al modelo que improvise una UI densa.

Puede haber excepciones de episodio si Seedance genera correctamente interfaces simples;
esas excepciones no cambian la regla general.

## 8. Audio

### Fase 1
Música ligera y discreta + diálogo + foley.

### Fase 2
El clip debe generarse por defecto con:
- voz en off;
- música calmada;
- efectos de audio;
- animación sincronizada.

### Fase 3
Audio integrado si ayuda a continuidad: diálogo breve, ambiente, foley y música de resolución.

Evitar solapamientos de voz.
Si una línea no cabe con dicción natural, recortar texto o ajustar la duración; no acelerar la voz.

### Pronunciación operativa
Solo para voz:
- `topographer` → `tuh-POG-ruh-fer`
- `SimuLENS` → `SIM-yoo-lenz`

Texto visible: **SimuLENS**.

## 9. Referencias necesarias

Para un clip con personajes, preparar según necesidad:
1. fondo limpio;
2. anchor / first frame;
3. character sheet;
4. pantallas;
5. objetos nuevos;
6. frame anterior si existe continuidad directa.

**Fondo limpio:** entorno y objetos.  
**Character sheet:** identidad.  
**Anchor:** posición/pose inicial.  
**Screen asset:** contenido exacto.  
**Previous frame:** continuidad.

## 10. Texto

Una placa = una idea.
Poco texto, grande y legible.
La voz complementa el texto; no debe repetirlo literalmente.