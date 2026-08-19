# Imágenes

## `hero.png` — foto de fondo de la pantalla principal

Es la foto de la mesa familiar con la januquiá. La página la toma sola desde
`index.html`; si el archivo falta, el hero cae al degradado de marca y no se
rompe nada. Cuando la foto carga, el hero apaga sus tramas decorativas
(ladrillos y puntitos) para no ensuciar la imagen.

### Sobre la resolución

El archivo actual mide **389 × 261 px**. En celulares se ve bien, pero en una
notebook o monitor el navegador lo estira unas 3,5 veces y pierde algo de
definición. No se aplica ningún desenfoque: se muestra tal cual.

**Si conseguís el original en alta**, reemplazá este archivo y queda perfecto:

- **Ancho:** ~1800 px (mínimo 1400)
- **Formato:** JPG con calidad 80–85, o WebP — ambos pesan bastante menos que
  un PNG para una foto
- **Peso ideal:** por debajo de ~400 KB

Si cambiás la extensión, hay que actualizar el `src` de `[data-hero-img]` en
`index.html`.

### Encuadre

El texto del hero cae sobre la mitad izquierda, así que conviene que el motivo
principal de la foto quede hacia la derecha (que es como está ahora).
