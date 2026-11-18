# maneja.do

Archivos públicos de maneja.do: las imágenes que se publican en Instagram y los logos de la marca. Más adelante, aquí puede vivir la página web.

## Cómo está organizado

```
media/
  instagram/
    posts/AAAA-MM-DD-tema/       una carpeta por post; las láminas van 01.jpg, 02.jpg… en el orden del carrusel
    historias/AAAA-MM-DD-tema.jpg
    reels/AAAA-MM-DD-tema/       video.mp4 y portada.jpg
    perfil/                      foto de perfil
  marca/                         logotipo e ícono en SVG
```

- La raíz queda libre para la página web (`index.html` y sus carpetas), por si un día la publicamos con GitHub Pages.
- Nombres en minúscula, sin espacios ni acentos, con la fecha de publicación al inicio.
- Todo lo que se sube aquí es público: nada de datos de clientes, contraseñas ni documentos internos.

## Enlaces directos

Instagram toma cada imagen desde su enlace directo, por ejemplo:

`https://raw.githubusercontent.com/bvargas1804/maneja.do/main/media/instagram/posts/2026-11-18-libreta/01.jpg`

## Marca

- `media/marca/logotipo-sobre-oscuro.svg`: blanco y verde, para fondos azul noche.
- `media/marca/logotipo-sobre-claro.svg`: azul noche y verde oscuro, para papel y fondos blancos.
- `media/marca/icono-noche.svg` e `icono-verde.svg`: el ícono "m." para fotos de perfil.

Las reglas completas están en el libro de marca.
