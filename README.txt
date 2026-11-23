DEFIENDE EL JARDÍN — VERSIÓN 6 (UN INTENTO POR REGISTRO)

ARCHIVOS
- index.html: videojuego y examen de factorización.
- manifest.webmanifest: instalación como aplicación web.
- sw.js: actualización de caché para cargar esta versión.
- AppsScript.gs: receptor opcional de resultados para Google Sheets.

CAMBIOS DE ESTA VERSIÓN
1. Se conserva el registro del estudiante (nombre completo y grado/grupo).
2. Se conserva el guardado del resultado y de las respuestas en el dispositivo. Se mantiene la cola de resultados pendientes de sincronizar.
3. Se conserva el envío a Google Sheets cuando se configure la URL de Apps Script.
4. En el esquema, cada apartado acepta cualquiera de sus elementos correctos o varios juntos: coeficientes 2, 5 y 4; exponentes 2 y 1; variables x y y; signos + y -; y los tres términos 2x², 5x y -4y/4y.
5. El apartado de términos identifica que la expresión tiene tres términos.
6. Se amplía el reconocimiento de respuestas abiertas mediante conceptos equivalentes y pequeñas variaciones de escritura. La calificación sigue siendo automática por reglas, no por una IA que compruebe cualquier respuesta matemática.
7. Se eliminan ejemplos y pistas de apoyo en las preguntas. Se conserva el enunciado necesario de los problemas.
8. En diferencia de cuadrados, los paréntesis aparecen automáticamente y el alumno escribe solamente los dos factores. Se acepta cualquiera de los órdenes de los factores registrados como equivalentes.
9. Las plantas se colocan centradas en la casilla seleccionada.
10. Se conserva la velocidad reducida de los zombis y el botón ² para escribir exponentes.
11. Se conservan las 13 preguntas y los 37 aciertos posibles.

REGISTRO EN GOOGLE SHEETS
El formulario de registro y el almacenamiento local funcionan dentro del juego. Para reunir los resultados de diferentes dispositivos en una sola hoja de cálculo, es necesario configurar la conexión:
1. Abre https://script.google.com/ y crea un proyecto.
2. Copia el contenido de AppsScript.gs y guarda.
3. Implementar > Nueva implementación > Aplicación web.
4. Ejecutar como: tú. Acceso: cualquier persona (según las opciones de tu cuenta).
5. Autoriza el proyecto y copia la URL terminada en /exec.
6. En index.html, sustituye PEGA_AQUI_LA_URL_DE_TU_APPS_SCRIPT por esa URL.
7. Sube los archivos del ZIP a GitHub Pages, reemplazando los anteriores.
8. Antes de aplicarlo con el grupo, realiza una prueba y confirma que el resultado aparece en la pestaña Resultados de tu hoja.

IMPORTANTE
- El registro local queda guardado en el navegador/dispositivo donde se juega.
- Para consolidar resultados de distintos alumnos/dispositivos en Google Sheets, debe configurarse la URL de Apps Script.
- Se permite utilizar el juego varias veces en el mismo dispositivo con registros diferentes.
- Cada registro (nombre completo + grado/grupo) puede realizar un solo intento en ese dispositivo y navegador. Si el mismo estudiante intenta entrar de nuevo con los mismos datos, el juego lo bloquea.
- Los nombres se comparan sin distinguir mayúsculas, minúsculas, acentos ni espacios repetidos.
- El historial local conserva los resultados de cada estudiante. Para reunir resultados de varios dispositivos en una sola hoja, configura Google Sheets como se explica arriba.
- Las preguntas abiertas y las expresiones algebraicas usan reglas de aceptación flexibles; se recomienda probar respuestas reales antes de usar la puntuación como calificación definitiva.

CAMBIO DE ESTA VERSIÓN
12. El bloqueo ya no es general para todo el dispositivo: ahora se aplica individualmente a cada registro de nombre completo y grado/grupo. Otro estudiante puede iniciar una nueva partida en el mismo equipo.

CAMBIOS DE ESTA VERSIÓN 6
12. En el esquema, el campo se muestra como “Términos”, sin indicar la cantidad en la etiqueta.
13. Después de cada respuesta aparecen tres zombis para aumentar la actividad entre preguntas.
14. La velocidad de los zombis se ajusta ligeramente de 0.035 a 0.030 por ciclo, haciéndolos un poco más lentos.


Versión 8: se restaura la aparición de tres zombis al mismo tiempo y la velocidad anterior (0.030). La primera pregunta acepta también “multiplicación de factores” como definición válida de factorización.


Actualización versión 9: la cantidad de zombis alterna por pregunta: 1 en las preguntas impares y 2 en las pares. Se conserva la velocidad anterior de 0.030.


Versión 10: aparece exactamente un zombi por pregunta. Se conserva la velocidad de 0.030 y todos los demás ajustes de la versión 9.


Actualización versión 11 (corrección solicitada):
14. En la pregunta 7, la diferencia de áreas acepta expresiones con cuadrados de variables y de números, por ejemplo x²-y² y 2²-4²; también acepta la escritura '2 al cuadrado menos 4 al cuadrado'.
15. En la pregunta 8, las opciones completas 'Factor común' y 'Diferencia de cuadrados' se validan sin separarlas por palabras, corrigiendo el falso error al seleccionar una respuesta correcta.
