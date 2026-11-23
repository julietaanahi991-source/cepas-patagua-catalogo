# Catálogo digital · Cepas de la Patagua

Catálogo web de los aceites de oliva extra virgen monovarietales **Cepas de la Patagua** (Arbequina, Frantoio y Picual), Valle de Pencahue, Región del Maule, Chile.

Es una sola página estática: `index.html` y las fotos en `img/`. No necesita instalar nada ni servidor especial.

## Qué incluye

- Portada, perfil sensorial de las tres cepas y catálogo de 13 productos.
- Filtros por formato: botellas 1 litro, bidones 5 litros, packs degustación 250 ml y packs 1 litro.
- PDF para descargar o enviar: `catalogo-cepas-de-la-patagua.pdf` (A4, se genera imprimiendo `index.html`).
- Botón «Consultar producto» que abre WhatsApp con el nombre del producto ya escrito.
- Botón «PDF / Imprimir» (imprime todos los productos, sin filtros ni botones).
- Sin precios: las consultas van por WhatsApp, correo o la tienda online.

## Cómo editar

- **Productos:** lista `PRODUCTOS` al final de `index.html` (nombre, formato, perfil, descripción y fotos).
- **WhatsApp y web oficial:** constantes `WHATSAPP` y `WEB` en el mismo script; el teléfono y el correo del pie están en la sección `contacto`.
- **Fotos:** van en `img/`, en JPG de unos 1000 px de alto y fondo blanco.

## Publicación

Publicado con GitHub Pages desde la rama `main` (carpeta raíz). Cada cambio que se suba a `main` se publica solo en uno o dos minutos.
