# 🎮 Jueguitos

[![Jugar](https://img.shields.io/badge/jugar-Jueguitos-ff69b4?style=for-the-badge)](https://yohangarcia.github.io/Jueguitos/)

Colección de juegos HTML/Canvas open source. Livianos, sin dependencias, listos para jugar en el navegador.

👉 **Jugá online:** https://yohangarcia.github.io/Jueguitos/

## Juegos

| Juego | Descripción |
|---|---|
| 🔫 **Destructor de Círculos** | Explotá círculos, esquivá bombas, subí de nivel. Combo, hover, vidas extra. |
| 🐍 **Snake** | La serpiente clásica. Comé estrellas, crecé, la velocidad aumenta. |

## Cómo jugar

1. Abrí `index.html` en tu navegador
2. Elegí un juego
3. Atajos de teclado: `R` / `Espacio` para reiniciar, `Escape` para volver al menú

No necesitas servidor web ni instalar nada.

## Cómo agregar un juego nuevo

Los juegos son archivos HTML independientes. Para agregar uno:

1. Creá `mijuego.html` en la carpeta
2. El juego debe ser completamente autocontenido (HTML + CSS + JS en un solo archivo)
3. Agregá el enlace en `index.html` en la sección `.games`:

```html
<a class="game-btn" href="mijuego.html">
  <div class="icon">🎮</div>
  <div class="name">Mi Juego</div>
  <div class="desc">Una breve descripción</div>
</a>
```

Podés seguir el diseño visual de los botones existentes. Si tu juego necesita teclas especiales, documentalas dentro del juego.

## Requisitos técnicos

- Los juegos deben ser archivos HTML únicos (sin dependencias externas)
- Canvas recomendado: 1000×650 (con `max-width: 98vw; max-height: 90vh` para responsive)
- Sin frameworks, sin librerías externas, sin servidor

## Licencia

MIT — hacé lo que quieras. Forkeá, compartí, mejorá, rompé, divertite.
