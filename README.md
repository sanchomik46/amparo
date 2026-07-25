# Amparo · 48 vueltas al sol

Web-regalo **mobile first** creada para Amparo, nacida el 27 de julio de 1978 y celebrando sus 48 años el 27 de julio de 2026.

**Dirección prevista:** `https://sanchomik46.github.io/amparo/`

## Qué incluye

- Diseño mobile first desde 320 px.
- Identidad turquesa, elegante y personal.
- Cuenta atrás para el 27 de julio de 2026.
- Historia de Amparo y sus cualidades.
- Sección sobre sus gustos: amigas, vino, tardeos, conciertos, Julián, Can Guti y pizza.
- Galería preparada para exactamente **37 fotografías**.
- Bloque propio con 7 fotografías: **Miki & La Molona**.
- Página independiente y animada para los tres regalos personales.
- Caja de regalo interactiva y confeti ligero.
- Visor ampliado accesible para las fotografías.
- Menú móvil, navegación por teclado y respeto por `prefers-reduced-motion`.
- Página 404 personalizada.
- Publicación automática mediante GitHub Actions.
- Sin cookies, anuncios, analítica ni base de datos.

## Publicar en GitHub Pages

El repositorio ya incluye el flujo `.github/workflows/pages.yml`.

1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment → Source**, selecciona **GitHub Actions**.
3. Abre la pestaña **Actions** y ejecuta o revisa `Publicar la web de Amparo`.
4. La web aparecerá en `https://sanchomik46.github.io/amparo/`.

Cada cambio enviado a la rama `main` volverá a publicar la web automáticamente.

## Reparto de las 37 fotografías

- Fotografías 01–08: Amparo.
- Fotografías 09–16: familia.
- Fotografías 17–23: amigas, vino, tardeos y conciertos.
- Fotografías 24–30: Amparo y Julián.
- Fotografías 31–37: Miki y **La Molona**.

Las imágenes todavía se mantienen como espacios preparados hasta recibir los archivos originales. Lo más cómodo es subir aquí un ZIP con las fotos; así se conservan los nombres de archivo y se pueden optimizar, ordenar y añadir sin tocar el código manualmente.

## Los tres regalos personales

La web incluye una página sorpresa independiente en `regalos.html`, con tres aperturas animadas. Los títulos, descripciones e imágenes definitivas se completarán al recibir los tres archivos originales, ya que sus nombres contienen la información del regalo.

## Nota técnica

Los archivos `site.part-*` contienen el proyecto comprimido. El flujo de GitHub Actions los reconstruye dentro de `_site` y publica el resultado en GitHub Pages. Esta solución mantiene el proyecto completo y permite volver a desplegarlo automáticamente.

## Probar la web localmente

Después de descargar y reconstruir el proyecto, desde la carpeta de la web ejecuta:

```bash
python3 -m http.server 8080
```

Después abre `http://localhost:8080`.

## Privacidad importante

GitHub Pages publica la web mediante una dirección accesible en internet. La etiqueta `noindex` pide a los buscadores que no la indexen, pero **no convierte la página en privada**.

No añadas fotografías o información que no quieras compartir mediante esa dirección. Confirma el consentimiento de las personas que aparezcan y elimina los metadatos EXIF de las imágenes antes de publicarlas.
