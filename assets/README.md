# Imágenes

## Foto de fondo de la pantalla principal

Va acá, con el nombre `hero` y cualquiera de estas extensiones:

    assets/hero.png
    assets/hero.jpg
    assets/hero.webp

La página las prueba en ese orden y usa la primera que encuentre, así que no
hace falta tocar el código según el formato. Si no hay ninguna, el hero
muestra el degradado de marca y no se rompe nada.

Cuando la foto carga, el hero apaga sus tramas decorativas (ladrillos y
puntitos) y el resplandor naranja, para no ensuciar la imagen.

## Qué conviene subir

- **Ancho:** ~1800 px (mínimo 1400). El hero la muestra a todo el ancho de la
  pantalla, así que por debajo de eso se nota estirada.
- **Formato:** JPG con calidad 80–85, o WebP. Para una foto pesan bastante
  menos que un PNG.
- **Peso:** idealmente por debajo de ~400 KB.
- **Encuadre:** apaisado. El texto del hero cae sobre la mitad izquierda, así
  que conviene que el motivo principal quede hacia la derecha.

## Legibilidad

El texto no depende de oscurecer la foto: hay un velo suave sólo en la franja
izquierda (llega a cero al 72% del ancho) y las letras llevan su propia
sombra. Si la foto nueva es muy clara del lado izquierdo y el texto queda
justo, se ajusta el gradiente de `.scrim-photo` en el `<style>` de
`index.html`.
