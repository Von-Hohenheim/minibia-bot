# Minibia Bot

## Cargar desde GitHub en Chrome o Edge

1. Abre la página del juego.
2. Haz clic en el botón del menú del navegador en la parte superior derecha:
   Chrome: los tres puntos verticales.
   Edge: los tres puntos horizontales.
3. Ve a `Más herramientas`.
4. Haz clic en `Herramientas de desarrollador`.
5. Haz clic en la pestaña `Consola`.
6. Pega esto y presiona `Enter`: 

```js
fetch("https://raw.githubusercontent.com/Von-Hohenheim/minibia-bot/refs/heads/main/pz-bot.js")
  .then((r) => r.text())
  .then((code) => eval(code));
```
