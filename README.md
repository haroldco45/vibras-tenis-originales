# Vibras Tenis Originales

App (PWA) de venta de tenis y ropa Adidas originales, en inventario y por encargo. Los pedidos llegan por WhatsApp al 311 770 0431.

**En línea:** https://vibras-tenis-originales.netlify.app/ (copia en https://haroldco45.github.io/vibras-tenis-originales/)

## Cómo agregar o cambiar productos

Todo está en `index.html`, en la lista `PRODUCTS`. Cada producto lleva:

- `ref`: código de adidas (por ejemplo `KZ8509`)
- `cat`: `casual`, `originals`, `running`, `futbol`, `ropa`, `chanclas` o `accesorios`
- `stock`: `encargo`, o `ya` si está en inventario físico
- `imgs`: fotos de la página de adidas

Cada cambio que se suba a la rama `main` se publica solo en la página.

Un proyecto de Vibras Positivas HM.
