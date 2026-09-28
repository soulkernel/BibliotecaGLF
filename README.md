# Biblioteca documental GLF

Biblioteca bilingüe de políticas, normas y documentos ambientales y sociales del Galápagos Life Fund. Interfaz en español e inglés, idioma inicial del navegador, búsqueda sobre metadatos, filtros por colección, tema, entidad, tipo, idioma y disponibilidad. Fichas enlazables y descargas locales con acceso a fuentes oficiales.

## Uso local

Abrir `index.html` desde la carpeta completa. No requiere instalación, conexión a internet ni servidor para buscar y consultar las copias locales. Los enlaces oficiales sí requieren internet. La preferencia de idioma se conserva en el navegador cuando permite almacenamiento local.

## GitHub Pages

Publicar la rama `main`, directorio raíz, desde Settings → Pages → Deploy from a branch. No se necesita compilación ni dependencias. El archivo `.nojekyll` evita procesamiento adicional. Todos los enlaces locales son relativos y funcionan en subdirectorios de GitHub Pages.

## Vercel

Importar el repositorio como proyecto estático (Other). Sin comando de instalación ni compilación. Directorio de publicación: raíz del repositorio. La configuración `vercel.json` está incluida. No se ha desplegado en Vercel.

## Contenido y mantenimiento

- 82 archivos locales distintos por SHA-256 y 5 referencias sin copia local.
- 84 ubicaciones originales se consolidaron en 82 archivos; las copias idénticas de los anexos A y F se presentan una vez y aparecen en ambas colecciones.
- Se excluyen INFORMES, INFORMES FINANCIEROS y Nuevo procedimiento en creación. SUBVENCIONES no forma parte de este alcance.
- El plan de manejo de Hermandad y su resumen se incluyen aunque sus nombres originales comiencen por Informe.
- La vigencia del corpus fue confirmada por el responsable de las fuentes. El catálogo no revalida su vigencia ni actualiza los archivos automáticamente.
- Los originales se conservan sin alterar. Los títulos y resúmenes de la interfaz son descripciones editoriales; los archivos mantienen su idioma original.
- El buscador consulta títulos, descripciones, códigos, entidades y temas, no el texto completo de los archivos.
- Las páginas oficiales de GLF publican los documentos internos aquí incluidos; se mantienen sus fuentes. Antes de incorporar documentos adicionales no publicados, revisar su audiencia.
- El catálogo no clasifica requisitos, no toma decisiones sobre salvaguardas y no contiene expedientes de postulantes.

`catalog.json` es la copia legible del catálogo. Tras editarlo, actualizar `catalog.js` con `window.GLF_CATALOG = <contenido JSON>;`. Mantener ambos sincronizados. Para reemplazar un archivo, registrar edición, SHA-256 y tamaño, conservar la trazabilidad y comprobar sus enlaces.

Fuentes, entidades, ediciones, huellas e idiomas están registrados en las fichas de datos. Las rutas privadas del equipo no se incluyen en el sitio. Los PDF, DOCX y XLSX conservan los derechos y atribuciones de sus emisores. Los recursos de marca pertenecen a GLF; Cabin se distribuye bajo SIL Open Font License.
