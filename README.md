# Altura 120

Aplicación web para preparar los exámenes teóricos de AESA de pilotaje de drones: **A1/A3**, **A2** y **escenarios estándar (STS)** de categoría específica.

Funciona en el móvil, se puede instalar como aplicación y no necesita conexión una vez cargada.

## Qué incluye

- **Temario** en 37 bloques, organizados por las materias oficiales de cada examen.
- **42 esquemas** dibujados a medida: distancias y subcategorías, regla de los 120 m, clases C0 a C6, espacio aéreo, viento y turbulencia, anillo de vórtices, volumen operacional, zona terrestre controlada y buffer de riesgo en tierra, entre otros.
- **331 preguntas tipo test**, todas con explicación del porqué. El orden de las opciones cambia en cada intento.
- **Simulacro de examen** con el número real de preguntas y temporizador: 40 preguntas para A1/A3 y STS, 30 para A2, con el corte en el 75 %.
- **Diagnóstico por materia** al terminar cada test, con acceso directo a practicar solo el bloque que falla.
- **Repaso espaciado**: las preguntas falladas vuelven al día siguiente y se van espaciando a los 3 días, la semana, las dos semanas y el mes conforme se aciertan.
- **Tabla de clases**: qué puedes volar, dónde, con qué acreditación y si se puede en zona urbana.
- **Chuleta** con las cifras que más caen, para el repaso de última hora.

## Cómo instalarla en el móvil

1. Abrir el enlace en el navegador del teléfono.
2. En Android (Chrome): menú de tres puntos → *Añadir a pantalla de inicio*.
3. En iPhone (Safari): botón de compartir → *Añadir a pantalla de inicio*.

Queda con icono propio, se abre a pantalla completa y funciona sin datos.

El progreso se guarda en el propio dispositivo. Si se borran los datos del navegador o se cambia de teléfono, se empieza de cero.

## Base normativa

El contenido se apoya en:

- Reglamento de Ejecución (UE) 2019/947, operaciones, con el Apéndice 1 sobre escenarios estándar.
- Reglamento Delegado (UE) 2019/945, requisitos de producto y clases C0 a C6.
- Real Decreto 517/2024, marco español, en vigor desde el 25 de junio de 2024.
- Cursos de formación publicados por AESA para A1/A3 y para la subcategoría A2.

Los escenarios nacionales STS-ES-01 y STS-ES-02 dejaron de ser válidos el 31 de diciembre de 2025; la aplicación trabaja ya con los escenarios europeos STS-01 y STS-02.

Última revisión normativa: noviembre de 2026.

## Aviso

Material de estudio no oficial. No sustituye al temario ni a los cursos publicados por AESA, que son la referencia válida. La normativa cambia: contrasta siempre con la documentación oficial antes de examinarte y antes de volar.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La aplicación completa: contenido, esquemas y lógica |
| `manifest.webmanifest` | Permite instalarla como aplicación |
| `sw.js` | Hace que funcione sin conexión |
| `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` | Iconos |
| `robots.txt` | Permite que los buscadores indexen la página |
| `README.md` | Este documento |

Para actualizarla, se sustituyen los archivos por los nuevos manteniendo los mismos nombres. Conviene subir también el número de versión del caché en `sw.js` para que los dispositivos que ya la tengan instalada reciban los cambios.

## Autoría

Altura 120 está hecho por **Dani Tena**.

© Dani Tena. Todos los derechos reservados. Si quieres reutilizar el material para docencia, escríbeme y lo hablamos.
