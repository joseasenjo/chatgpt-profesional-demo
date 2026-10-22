# ChatGPT profesional · demostración

Complemento interactivo del trabajo final del curso *ChatGPT e Inteligencia Artificial Profesional*: «Implementación estratégica de ChatGPT en el entorno profesional».

Es una única página web que pone en práctica la teoría del trabajo. Incluye una pestaña de inicio, un caso guiado con el prompt de Javier y archivos de ejemplo (CSV y Excel).

## Qué incluye

1. **Constructor y validador de prompts.** Fórmula Rol + Tarea + Contexto + Formato. El validador comprueba por reglas que cada componente esté presente, avisa de datos sensibles (correos, teléfonos, DNI, IBAN) y sugiere pedir fuentes para reducir alucinaciones. Incluye un modo práctica con retos y pistas, ideas con un clic en cada bloque, un comparador que indica qué le falta a un prompt simple, una galería de seis ejemplos completos y un botón para copiar un prompt de revisión que se pega en el propio ChatGPT.
2. **Anonimización de datos.** Sube un CSV o Excel de prueba, elige las columnas con nombres y la página los sustituye por «Cliente A, B…», convierte los importes en índice o cuartil, enmascara datos personales avisa de las filas identificables por combinación de columnas (con opción de generalizar la ciudad a comunidad autónoma), genera la tabla de equivalencias y permite restaurar los nombres en la respuesta de la IA.
3. **Human-in-the-loop.** Lista de verificación obligatoria que crece con el riesgo del informe (interno, cliente, decisión importante) y exportación del informe revisado (texto o PDF) con el nombre del responsable.

## Privacidad

Todo se ejecuta en el navegador: los textos y archivos que usas no se envían a ningún servidor y no hay cookies. Lo único que se envía es un recuento anónimo de visitas a GoatCounter (sin datos personales; las cifras solo las ve el autor). Los recursos externos son ese contador y la librería SheetJS (cdnjs) para leer archivos Excel; con CSV no hace falta.

Los datos de `ejemplo.csv` son ficticios. No subas datos reales de clientes a un repositorio público.

## Límites

El validador comprueba la estructura de un prompt, no la calidad de su contenido, que debe juzgar una persona. La detección de datos personales se basa en patrones y puede no encontrar todos los casos: revisa siempre el resultado a mano.

## Uso

Abre `index.html` en un navegador, o la versión publicada en GitHub Pages.

## Autoría

Desarrollado por Jose Luis Asenjo para el curso ChatGPT 2026. Contacto: https://www.linkedin.com/in/joseluisasenjo
