# VUURK-DEMO-SHOIFY

Theme Shopify de la tienda oficial VUURK (gummies energéticas), tienda de producto único sobre **Shopify Basic** con el theme **Savor**.

Dirección del proyecto: eQuantum Consulting.

## Base

- Theme: Savor 4.3.0 (Shopify), código original exportado desde el admin de Shopify.
- Rama de trabajo: `main`.
- Shopify gestiona catálogo, carrito, checkout, pagos y pedidos. Este repositorio contiene solo el theme; no hay storefront externo.

## Estructura

| Carpeta | Contenido |
| --- | --- |
| `assets/` | JavaScript, CSS e iconos SVG del theme |
| `blocks/` | Bloques de theme reutilizables |
| `config/` | `settings_schema.json` y `settings_data.json` |
| `layout/` | `theme.liquid` y `password.liquid` |
| `locales/` | Traducciones del storefront y del editor |
| `sections/` | Secciones y grupos de secciones (header y footer) |
| `snippets/` | Fragmentos Liquid compartidos |
| `templates/` | Plantillas JSON de cada tipo de página |

## Conexión con Shopify

La conexión se hace desde el admin de Shopify (Tienda online → Temas → Agregar tema → Conectar desde GitHub), eligiendo este repositorio y la rama `main`. Shopify la añade como un theme **no publicado** en la biblioteca. No publicar ni sustituir el theme activo sin aprobación.

Los cambios hechos en el editor de temas sobre el theme conectado se guardan como commits en `main`.

## Reglas

- No incluir credenciales, tokens ni datos privados.
- No inventar precios, ingredientes, claims ni información técnica del producto.
- No modificar el logo ni el packaging original de VUURK.
- Cada etapa (E01–E09) requiere aprobación antes de avanzar.
