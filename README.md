# Pasen y sueñen — La mesa abierta del Chañar

Proyecto cultural digital independiente inspirado en San Patricio del Chañar, Neuquén. Una mesa tranquila de recursos gratuitos para leer, imprimir, aprender y compartir. La colaboración es voluntaria y nunca condiciona el acceso.

## Estado de esta primera versión

- Sitio estático en `index.html`, sin backend, cuenta, contraseña ni dependencias externas.
- Catálogo de 28 productos distribuidos en 8 puertas temáticas: cuentos, escuela, familia, decoración, papelería, curiosidades, arte y memoria de San Patricio del Chañar, y recetarios.
- La portada es breve y presenta ocho puertas ilustradas; al entrar se abre un estante con productos visuales, descripción, vista previa y opciones de descarga HTML imprimible o impresión / guardado como PDF. Incluye un mapa artístico del valle, un mazo de 24 cartas recortables y un rompecabezas imprimible.
- Diseño adaptable a móviles y escritorio, navegación por teclado y respeto por `prefers-reduced-motion`.
- Alias informado por el responsable: `ocarina.guitarra`, titular informado Elías Martínez. Aporte voluntario y sin condiciones de acceso.
- Identidad visual cálida con paleta pastel, escena rural ilustrada en CSS y pequeñas escenas vectoriales para las piezas imprimibles.
- `historia.html`: introducción a la historia y las curiosidades de San Patricio del Chañar, con cautela al tratar hipótesis.
- `contactos.html`: diez contactos útiles y líneas adicionales de asistencia, con avisos para reconfirmar teléfonos directos.
- `fuentes.html`: criterios editoriales y fuentes iniciales.

## Principios editoriales

1. Primero aportar valor; nunca bloquear recursos gratuitos detrás de una donación.
2. Separar hechos documentados, hipótesis, testimonios e imaginación artística.
3. Verificar horarios, direcciones, contactos y datos prácticos antes de publicarlos.
4. Respetar derechos de autor, atribuciones y permisos de publicación.
5. Evitar urgencia artificial, presión emocional, publicidad invasiva y registros obligatorios.
6. Revisar los recursos y corregir errores con transparencia.

## Arquitectura actual

La versión actual mantiene el catálogo en un único archivo para facilitar la edición desde GitHub y reducir dependencias. Los 28 recursos se organizan automáticamente detrás de ocho puertas temáticas; la búsqueda y los filtros ocultan secciones vacías. El sitio es autoservicio y no depende de que Elías esté conectado. Las piezas descargables se generan en el navegador como archivos HTML imprimibles: no se envían datos a un servidor.

## Próximas etapas

- Probar manualmente búsqueda, filtros, vista previa, descarga e impresión en celular y escritorio.
- Verificar fuentes históricas y añadir referencias específicas a cada ficha documental.
- Ampliar las ilustraciones originales y probar la impresión en distintos navegadores.
- Verificar que el alias y el nombre del titular coincidan en la aplicación de pago antes de transferir.
- Mantener actualizados los contactos y ampliar las fuentes de las piezas culturales.
- Si el catálogo crece mucho, separar estilos, catálogo y lógica en `styles.css`, `catalog.js` y `app.js` sin perder compatibilidad con GitHub Pages.

## Publicación

Activar GitHub Pages desde **Settings → Pages**, seleccionando la rama principal y la carpeta raíz (`/`). GitHub publicará `index.html` como portada. No se necesita un proceso de compilación.

## Créditos

Proyecto cultural independiente preparado por Elías Martínez. Inspirado en San Patricio del Chañar, Neuquén. No representa oficialmente al municipio ni reemplaza fuentes institucionales.