# _propiedades — HOUSEMYCPROPIEDADES

Portal inmobiliario autogestionable para **HOUSEMYCPROPIEDADES**, orientado a publicar, filtrar y administrar propiedades (venta, arriendo y terrenos/paños) con gestión centralizada de imágenes por propiedad.

## Características planificadas

- **Catálogo público de propiedades:** listado con filtros por operación (venta/arriendo), tipo de inmueble, ubicación y rango de precio.
- **Ficha detallada por propiedad:** descripción, superficie, características clave, ubicación y galería de fotos.
- **Panel autogestionable:** creación, edición, cambio de estado (disponible, reservada, vendida/arrendada) y eliminación de propiedades.
- **Gestión de imágenes por propiedad:** carga múltiple, definición de imagen de portada, reordenamiento y eliminación vinculada a cada propiedad.

## Gestión de imágenes por propiedad

- **Organización por ID:** cada propiedad mantiene su propio conjunto de fotos (`properties/{property_id}/cover.jpg`, `gallery_1.jpg`, etc.).
- **Imagen principal (portada):** define qué foto se muestra primero en el catálogo y tarjetas de búsqueda.
- **Galería y orden:** permite agregar nuevas imágenes, cambiar su orden de aparición y quitar fotos obsoletas sin afectar otras fichas.

## Arquitectura base propuesta

- **Frontend:** React + Vite + Tailwind CSS
- **Backend / Base de datos:** por definir (ej. Node.js/Express o PHP/MySQL, o servicios gestionados como Supabase/Firebase)
- **Almacenamiento de imágenes:** estructura por identificador de propiedad (`properties/{property_id}/cover.jpg`, `gallery_1.jpg`, etc.)

## Estructura inicial del repositorio

```text
_propiedades/
├── README.md
├── frontend/
├── backend/
└── docs/
´´´
## Estado actual

- Repositorio inicializado (`Initial commit` en `HOUSEMYC/_propiedades`).
