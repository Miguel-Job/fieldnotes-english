# Fieldnotes English

Plataforma web de práctica de inglés para la convocatoria Joven YEP 2027–2029, con énfasis en conversación, comprensión lectora, escritura y vocabulario de gestión integrada de recursos hídricos.

## Abrir la plataforma

1. Abre una terminal en esta carpeta.
2. Ejecuta `node server.js`. El servidor usa solo herramientas incluidas con Node; no instala paquetes ni necesita internet. Si el puerto 8000 está ocupado, probará automáticamente 8001 y otros puertos cercanos, e imprimirá la dirección elegida.
3. Abre en el navegador la dirección que imprimió el servidor (normalmente `http://127.0.0.1:8000`; si ese puerto estaba ocupado, será uno cercano).

La primera visita almacena la aplicación para volver a abrirla sin conexión desde el mismo navegador. También puedes elegir **Instalar aplicación** en el menú del navegador. Los archivos de la aplicación y tus avances no necesitan conexión a internet. Para cerrar el servidor, vuelve a la terminal y presiona `Ctrl+C`.

Para instalar el Service Worker y permitir la grabación del micrófono, abre el sitio en `127.0.0.1` o desde un sitio HTTPS. No abras el HTML con doble clic: los navegadores restringen esas funciones en archivos locales. Las preguntas de listening usan la voz inglesa del dispositivo cuando está disponible; la grabación de speaking se procesa en el navegador y puedes descargarla con el botón **Guardar audio**.

## Datos locales

El borrador, glosario y progreso se guardan en el almacenamiento local del navegador. Se quedan en este perfil del navegador y no se sincronizan con otros dispositivos. Las grabaciones se mantienen en memoria hasta descargarlas.

## Contenido incluido

- Curso offline de 15 unidades, desde fundamentos A2 hasta práctica C1: cuencas, GIRH, actores, monitoreo, riesgos climáticos, coordinación, evaluación crítica de evidencia, negociación de prioridades y defensa de recomendaciones.
- Cada unidad incluye reading con comprobación, listening con audio sintetizado y transcripción, vocabulario inglés-español, ejercicio de writing y preguntas de speaking.
- Las unidades C1 añaden una respuesta de lectura de 80–100 palabras para practicar inferencia y síntesis; el borrador se guarda localmente.
- Diagnóstico orientativo de gramática, vocabulario y lectura con una recomendación de siguiente paso.
- Writing prompt con esquema de respuesta y revisión guiada.
- Revisión local de borradores en ejercicios y simulacros: rango de palabras, estructura, conectores y algunos errores frecuentes, sin nota automática.
- Preguntas de entrevista oral, lectura de voz del navegador y grabación local.
- Ruta oral repetible de siete retos, de presentación personal a entrevista, con frases modelo, escucha y práctica grabada.
- Diálogos offline por turnos: coordinación, visita de campo y entrevista; escucha, responde con tu voz y compara con un modelo.
- Glosario editable inglés-español con tarjetas de recuerdo activo, intervalos adaptativos y palabras pendientes del día.
- Simulacro escrito cronometrado de 30 minutos y entrevista oral de tres preguntas con reloj por respuesta, autoevaluación e historial local.
- Plan de cinco días y seguimiento básico de sesiones.
- Ruta orientativa de 24 semanas desde la base hasta simulaciones de entrevista y examen.

## Copia de seguridad

En **Mi plan**, usa **Descargar copia** para exportar un archivo JSON con tu progreso, glosario, borradores e intentos. En otro navegador, abre la plataforma y elige **Restaurar copia**. La restauración reemplaza los datos locales de ese navegador y pide confirmación antes de hacerlo.
