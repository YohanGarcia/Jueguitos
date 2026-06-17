# Jueguitos — AGENTS.md

Colección de juegos HTML/Canvas estáticos. Sin build, sin tests, sin frameworks.

## Estructura

- `index.html` — menú/launcher. Contiene un array `GAMES` con la lista de juegos.
- Cada juego es un **HTML autocontenido** (HTML + CSS + JS inline).
- `support.js` y `Canvas.dc.html` son experimentos **no usados** — no modificarlos.
- `phaser` en `package.json` está instalado pero **no se usa** en ningún juego.
- `node_modules/` en `.gitignore`.

## Comandos

No hay scripts de build, test, lint ni formateo. Solo abrir `index.html` en el navegador.

## Convenciones

- **Idioma:** todo en español (UI, comentarios, README).
- **Canvas:** 1000×650, responsive con `max-width: 98vw; max-height: 90vh`.
- **Teclado:** `R`/`Space` = reiniciar, `Escape` = volver al menú.
- **Scores:** `localStorage` con claves por juego.
- **Tema:** dark, cada juego tiene color de acento propio.

## Cómo agregar un juego

1. Crear `nuevojuego.html` (HTML+CSS+JS inline).
2. Agregar entrada en el array `GAMES` en `index.html` (icono, nombre, descripción, color).

## Despliegue

GitHub Pages desde `main`. Sin servidor ni build. El sitio live está en `https://yohangarcia.github.io/Jueguitos/`.
