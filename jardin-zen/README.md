# Jardín Zen

Escena 3D interactiva de un estanque japonés con carpas (koi), puente, pabellón, rana, clima y estaciones, dibujada en tiempo real con Three.js.

Para verla, sirve la carpeta con cualquier servidor estático y abre `jardin-zen.html`. Necesita un navegador con WebGL y una GPU decente.

    python3 -m http.server 8000   # y abre http://localhost:8000/jardin-zen/jardin-zen.html

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

Solo se ha cambiado el nombre (título y pantalla de carga), se han quitado las vistas previas que apuntaban a la web original y se han reorganizado las rutas de las dos librerías. El código de la escena es de su autor y se rige por la licencia de su repositorio: comprueba que permite reutilizarlo antes de publicar esta copia, y conserva estos créditos.
