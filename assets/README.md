# Imágenes

## `hero.png` — foto de fondo de la pantalla principal

Es la foto de la mesa familiar con la januquiá. La página la toma sola desde
`index.html`; si el archivo falta, el hero cae al degradado de marca y no se
rompe nada.

### Sobre la resolución

El archivo actual mide **389 × 261 px**. En celulares se ve bien (el ancho de
pantalla es parecido), pero en una notebook o monitor la imagen se estira
unas 3,7 veces y pierde nitidez. Para compensarlo, `index.html` le aplica un
desenfoque de 2 px de 768 px de ancho en adelante.

**Si conseguís el original en alta**, reemplazá este archivo y queda nítido:

- **Ancho:** ~1800 px (mínimo 1400)
- **Formato:** JPG con calidad 80–85, o WebP — ambos pesan bastante menos que
  un PNG para una foto
- **Peso ideal:** por debajo de ~400 KB

Si cambiás la extensión, hay que actualizar el `src` de `[data-hero-img]` en
`index.html` y se puede sacar el bloque de desenfoque del `<style>`.

### Encuadre

El texto del hero cae sobre la mitad izquierda, así que conviene que el motivo
principal de la foto quede hacia la derecha (que es como está ahora).
