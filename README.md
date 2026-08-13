# Planeta Electrónico — rediseño conceptual

Landing page estática (HTML/CSS/JS puro, sin build) inspirada en
[planetaelectronico.com](https://planetaelectronico.com/), la tienda de
electrónica y componentes con sede en Málaga desde 2002.

Toda la información (categorías, productos con precio y código real,
marcas distribuidas, horarios, formas de pago, datos de contacto/legales)
y las imágenes (productos, logos de marca, banners promocionales) fueron
tomadas del sitio original y reorganizadas sobre una identidad visual
propia: un motivo "planeta + electrón" (jugando con el nombre de la
marca) combinado con una estética de placa de circuito oscura y acentos
neón.

## Estructura

```
index.html          página única
assets/css/style.css estilos
assets/js/main.js    menú móvil, scroll-spy, animaciones de aparición, aviso de cookies
assets/img/          imágenes reales descargadas del sitio original
  productos/         fotos de producto (novedades + más vendidos)
  marcas/             logos de marcas distribuidas
  banners/             banners y avisos promocionales
```

## Ver el sitio localmente

No requiere build ni dependencias. Basta con servir la carpeta:

```
python3 -m http.server 8000
```

y abrir `http://localhost:8000/`.

Los enlaces de categorías, productos, marcas y políticas legales apuntan
al sitio oficial `planetaelectronico.com`, ya que este proyecto es una
propuesta de diseño y no implementa carrito ni checkout propios.
