# Neo-Zen Beauty

Catálogo de maquillaje y skincare para Ecuador. Incluye el proyecto real actualizado y sus fotos.

## Archivos incluidos

- `index.html`: abre la tienda desde la dirección principal del sitio.
- `catalogo-v2.html`: la misma tienda en la ruta que ya se venía usando.
- `images1/`: 93 fotografías originales. El catálogo utiliza 91 de ellas; las otras dos también se conservan.
- `netlify.toml`: publicación desde la raíz, sin compilación.

Las dos páginas HTML contienen el mismo código. Para futuros cambios, mantenerlas sincronizadas.

## Crear el repositorio en GitHub, paso a paso

1. Descomprime el ZIP en tu computadora.
2. Abre https://github.com/new con tu cuenta.
3. Nombre sugerido: `neozen-beauty`. Puedes elegir visibilidad privada. Activa **Add README** y pulsa **Create repository**.
4. Dentro del repositorio, abre **Add file → Upload files**.
5. Arrastra el contenido de la carpeta descomprimida: `index.html`, `catalogo-v2.html`, `netlify.toml`, `README.md` y la carpeta `images1` completa. Conserva esa estructura en la raíz del repositorio.
6. Pulsa **Commit changes**. Deben verse las páginas HTML y `images1` al mismo nivel.

El ZIP es el paquete para descargar y descomprimir. En GitHub se suben los archivos y la carpeta que contiene.

## Conectar con Netlify después

Importa el repositorio en Netlify y usa la rama `main`. El archivo `netlify.toml` establece la carpeta de publicación en `.` y no requiere un comando de compilación. La página principal será `index.html`.

Para una prueba rápida también puedes arrastrar a Netlify la carpeta descomprimida que contiene `index.html` e `images1`.

## Qué funciona y qué queda pendiente

- 36 productos y 62 variantes con sus precios y fotos originales.
- Búsqueda, filtros por categoría y colección, favoritos, enlaces de productos y pedidos por WhatsApp.
- Probador de maquillaje con cámara. Actívalo desde un producto compatible; la prueba física se debe realizar en un teléfono, usando el sitio HTTPS y conexión a internet.
- Un único popup de bienvenida propuesto. El formulario es una demostración: no envía ni guarda correos y no aplica descuentos. Hay que conectar el registro y definir la promoción antes de activarla.

Las rutas de las fotos son relativas. Conserva el nombre `images1` y los nombres de sus archivos.

## Referencias para la publicación

- GitHub: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
- Subir archivos y carpetas: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Netlify: https://docs.netlify.com/build/configure-builds/file-based-configuration/
