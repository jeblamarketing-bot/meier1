# MEIER1

Página de producto de MEIER1 (Meier Instruments). Sitio estático publicado con GitHub Pages.

- `index.html`: la página completa (scroll cinematográfico, modo «Pruébalo» y formulario de reservas).
- `f/`: secuencias renderizadas en Blender, empacadas en pares de cuadros WebP.
- `s/`: escenas, estados del aparato y del modo interactivo.

Las reservas se guardan en Supabase (esquema `meier1`, tabla `reservas`) a través de la función `public.meier1_reservar`, que solo permite insertar.
