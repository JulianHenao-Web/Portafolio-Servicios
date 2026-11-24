# Magic Moon - Portafolio de figuras en porcelanicrón

Portafolio web de **Magic Moon**, un emprendimiento de figuras hechas a mano en porcelana fría (porcelanicrón). Las piezas miden entre 6 y 15 cm y se elaboran por encargo.


**Ver el sitio en vivo:** https://julianhenao-web.github.io/Portafolio-Servicios/

## Servicios que presenta

- **Figuras personalizadas:** retratos en miniatura de personas, parejas o mascotas.
- **Toppers y detalles para pasteles:** figuras temáticas para tortas y cupcakes.
- **Regalos personalizados:** detalles con nombre, fecha o mensaje.

## Tecnologías

- HTML5 con estructura semántica (`header`, `main`, `section`, `article`, `footer`)
- CSS3 (estilos propios en `styles.css`)
- [Bulma 1.0.4](https://bulma.io/), incluida localmente en `bulma.min.css`
- Fuentes de Google Fonts: Fredoka y Nunito

## Qué se modernizó con Bulma

- **Componentes de Bulma:** `navbar`, `hero`, `columns`, `card`, `button`, `tag` y `footer`.
- **Colores y tipografía personalizados** mediante las variables de Bulma (`--bulma-primary-*`, `--bulma-family-primary`).
- **Elementos propios** : portada con `.vitrina`, stickers flotantes, tarjetas con `.tarjeta` y nombres que aparecen en la galería con `leyenda`.
- **Diseño adaptable** a computador y celular.

## Estructura del proyecto

```
Portafolio-Modernizado/
├── index.html           ← versión con Bulma
├── styles.css
├── bulma.min.css
├── imagenes/
├── README.md
└── Portafolio-Servicios-(Original)/    ← versión original
    ├── index.html
    ├── styles.css
    └── images/
```

## Cómo verlo en tu computador

1. Descarga o clona este repositorio.
2. Abre `index.html` en tu navegador. No necesita instalación.

> Las fuentes se cargan desde Google Fonts, por lo que se ven mejor con conexión a internet.

## Versiones

- **Versión con Bulma (principal):** https://github.com/JulianHenao-Web/Portafolio-Servicios
- **Versión original (HTML y CSS):** https://github.com/JulianHenao-Web/Portafolio-Servicios/tree/main/Portafolio%20Servicios%20(Original)