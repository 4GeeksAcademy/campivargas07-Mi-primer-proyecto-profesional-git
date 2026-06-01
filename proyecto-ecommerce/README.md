# Prototipo E-commerce de Lujo (Maison Varga)

Prototipo frontend responsive para una tienda online de ropa de lujo con base en Francia.

## Stack

- HTML5 semantico
- Tailwind CSS (via CDN)
- JavaScript vanilla solo para interacciones basicas (carrito, filtros y checkout)

## Estructura

```
/proyecto-ecommerce
  /html
    home.html
    catalog.html
    product.html
    cart.html
    checkout.html
  /css
    tailwind.css
  /img
    product-01.svg
    product-02.svg
    product-03.svg
    product-04.svg
    product-05.svg
    product-06.svg
```

## Vistas implementadas

1. Home
- Navbar reutilizable
- Hero principal
- Nuevos lanzamientos (6 productos)
- Mas vendidos (6 productos)
- Footer reutilizable

2. Catalogo
- Navbar y footer reutilizados
- Filtros visuales por categoria y talla
- Grid de 20 productos (4 columnas en desktop)
- Cards con enlace a detalle
- Marcado Schema.org en tarjetas de producto

3. Producto
- Layout de dos columnas
- Product Schema (Product + Offer)
- Selector de talla y cantidad
- Boton Agregar al carrito (localStorage y sessionStorage)
- Seccion de descripcion extendida

4. Carrito
- Vista completa con productos
- 3 productos de ejemplo si el carrito esta vacio
- Calculo de subtotal, impuestos (20%) y total
- Boton de avance a checkout

5. Checkout
- Flujo progresivo de 3 pasos
- Indicador de progreso
- Validacion visual basica de campos requeridos
- Finalizacion de pago (simulada)

## SEO y semantica

- Uso de: header, nav, main, section, article, footer
- Meta description y title por pagina
- Product Schema en catalogo y producto

## Responsive

Diseñado para:
- 320px (movil)
- 768px (tablet)
- 1024px y superior (desktop)

## Ejecucion local

Puedes abrir directamente el archivo:

- html/home.html

o levantar un servidor estatico desde la raiz del repo.

## Convenciones de ramas sugeridas

- feature/home
- feature/catalog
- feature/product
- feature/cart
- feature/checkout

y merge posterior a main.
