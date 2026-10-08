# FEATER — Mis coberturas

Prototipo interactivo con datos de ejemplo. Incluye carpetas y filtros, carga de materiales, títulos y etiquetas masivas, revisión visual y solicitud de cambios. La bandeja del revisor muestra únicamente las coberturas en revisión.

## Subir a GitHub

1. Descomprimir el ZIP.
2. Crear un repositorio llamado `feater-coberturas-demo`. Puede ser privado.
3. Subir el CONTENIDO de esta carpeta a la raíz del repositorio: `index.html`, `style.css`, `app.js`, `vercel.json`, `README.md` y la carpeta `assets`. No subir el ZIP ni una carpeta adicional que los contenga.
4. Confirmar que `index.html` aparezca directamente en la raíz del repositorio.

## Publicar en Vercel

1. Crear un proyecto e importar el repositorio de GitHub.
2. Framework Preset: Other.
3. Root Directory: raíz del repositorio (no cambiar).
4. Build Command: vacío.
5. Output Directory: `.`. El archivo `vercel.json` ya incluye esta configuración.
6. Publicar con Deploy y copiar el enlace resultante para compartirlo.

Documentación: https://vercel.com/docs/builds/configure-a-build

## Probar localmente

Abrir `index.html` en un navegador, o ejecutar `python3 -m http.server 8000` en esta carpeta y visitar http://localhost:8000.

## Recorrido sugerido

Crear una cobertura, cargar materiales de ejemplo, seleccionar todos y aplicar etiquetas obligatorias (Mes, Formato, Año y Proveedor), modificar títulos, revisar y enviar. Cambiar a Revisor para solicitar cambios o aprobar y transferir.

## Alcance

Los archivos elegidos desde la computadora se previsualizan localmente. Las cargas y transferencias son simuladas y no se conectan a FEATER. Los cambios duran en la pestaña actual y se reinician al recargar.

Las imágenes de ejemplo y la marca se extrajeron de la grabación facilitada como referencia. Los videos de ejemplo tienen una previsualización simulada; los videos elegidos desde la computadora pueden reproducirse con sus controles.

No requiere instalación de dependencias, claves ni base de datos.
