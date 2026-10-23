# Pasen y sueñen — La mesa abierta del Chañar

Proyecto cultural digital independiente inspirado en San Patricio del Chañar, Neuquén. Una mesa tranquila de recursos gratuitos para leer, imprimir, aprender y compartir. La colaboración es voluntaria y nunca condiciona el acceso.

## Estado de esta primera versión

- Sitio estático en `index.html`, sin backend, cuenta, contraseña ni dependencias externas.
- Catálogo curado de 8 recursos con buscador y filtros por categoría.
- Fichas de recursos con vista previa, descarga HTML imprimible y opción de impresión.
- Diseño adaptable a móviles y escritorio, navegación por teclado y respeto por `prefers-reduced-motion`.
- Alias informado por el responsable: `ocarina.guitarra`, titular informado Elías Martínez. Aporte voluntario y sin condiciones de acceso.
- Identidad visual cálida con paleta pastel, escena rural ilustrada en CSS y pequeñas escenas vectoriales para las piezas imprimibles.

## Principios editoriales

1. Primero aportar valor; nunca bloquear recursos gratuitos detrás de una donación.
2. Separar hechos documentados, hipótesis, testimonios e imaginación artística.
3. Verificar horarios, direcciones, contactos y datos prácticos antes de publicarlos.
4. Respetar derechos de autor, atribuciones y permisos de publicación.
5. Evitar urgencia artificial, presión emocional, publicidad invasiva y registros obligatorios.
6. Revisar los recursos y corregir errores con transparencia.

## Arquitectura actual

La primera versión se mantiene intencionalmente en un solo archivo para facilitar la edición desde GitHub y reducir dependencias. El catálogo, el estilo y la lógica están organizados por secciones internas. Las piezas descargables se generan en el navegador como archivos HTML imprimibles: no se envían datos a un servidor.

## Próximas etapas

- Probar manualmente búsqueda, filtros, vista previa, descarga e impresión en celular y escritorio.
- Verificar fuentes históricas y añadir referencias específicas a cada ficha documental.
- Ampliar las ilustraciones originales y probar la impresión en distintos navegadores.
- Verificar que el alias y el nombre del titular coincidan en la aplicación de pago antes de transferir.
- Añadir una página de fuentes, créditos y condiciones de uso de los materiales.
- Si el catálogo crece mucho, separar estilos, catálogo y lógica en `styles.css`, `catalog.js` y `app.js` sin perder compatibilidad con GitHub Pages.

## Publicación

Activar GitHub Pages desde **Settings → Pages**, seleccionando la rama principal y la carpeta raíz (`/`). GitHub publicará `index.html` como portada. No se necesita un proceso de compilación.

## Créditos

Proyecto cultural independiente preparado por Elías Martínez. Inspirado en San Patricio del Chañar, Neuquén. No representa oficialmente al municipio ni reemplaza fuentes institucionales.