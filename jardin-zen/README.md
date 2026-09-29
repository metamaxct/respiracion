# Jardín Zen

Escena 3D interactiva de un estanque japonés con carpas (koi), puente, pabellón, rana, clima y estaciones, dibujada en tiempo real con Three.js.

Para verla, sirve la carpeta con cualquier servidor estático y abre `jardin-zen.html`. Necesita un navegador con WebGL y una GPU decente.

    python3 -m http.server 8000   # y abre http://localhost:8000/jardin-zen/jardin-zen.html

## Controles

**Teclado y ratón:** `C` cámara · `E` dar de comer · `G` acariciar · `P` fijar plano · `O` congelar tiempo · `K` seguir una carpa · `V` vista limpia · `T` clima · `M` sonido · `H` panel de control · `I` guía. Con la cámara manual: arrastra para mirar, `WASD` para moverte, `Q` y `Espacio` para bajar y subir, `Mayús` para ir más rápido.

**Mando** (Xbox, PlayStation, Switch Pro o cualquier mando estándar; pulsa un botón para que el navegador lo detecte):

| Botón | Acción |
|---|---|
| Stick izquierdo / derecho | Moverte / mirar (al moverlos con la cámara cinemática, pasa a manual) |
| LT / RT | Bajar / subir |
| RB | Ir más rápido (mantener) |
| A · B | Dar de comer · acariciar (con el stick derecho mueves la mano) |
| X · Y | Cambiar de cámara · cambiar el clima |
| LB | Seguir una carpa (otra vez, la siguiente) |
| Cruceta ↑ · ↓ | Sonido · gota en el agua (o salto de la rana) en el centro de la vista |
| Cruceta ← → | Velocidad de vuelo |
| L3 · R3 | Fijar plano · congelar tiempo |
| Select · Start | Vista limpia · mostrar u ocultar la guía |

**Móvil y tableta:** pulsa **Cámara manual** para que aparezcan el joystick (mover), los botones ▲ ▼ (subir y bajar) y el arrastre con el dedo (mirar). Tocar el agua crea ondas y tocar la rana la hace saltar. **Alimentar** y **Acariciar** están en la barra inferior.

## Archivos

| Archivo | Qué es |
|---|---|
| `jardin-zen.html` | La escena |
| `three.min.js` | Three.js r160 |
| `dat.gui.min.js` | dat.GUI |

## Origen y créditos

Esta página es una copia de **Koi Pond Garden**, de `souranyp-stack`:

- Repositorio: https://github.com/souranyp-stack/koi-pond-garden
- Página: https://souranyp-stack.github.io/koi-pond-garden/koi-pond.html

Cambios sobre el original: el nombre, la traducción al castellano (interfaz, guía, avisos y panel de control), el soporte de mando y los controles táctiles para móvil; también se han quitado las vistas previas que apuntaban a la web original y se han reorganizado las rutas de las dos librerías. El código de la escena es de su autor y se rige por la licencia de su repositorio: comprueba que permite reutilizarlo antes de publicar esta copia, y conserva estos créditos.
