# ChatGPT profesional · demostración

Complemento interactivo del trabajo final del curso *ChatGPT e Inteligencia Artificial Profesional*: «Implementación estratégica de ChatGPT en el entorno profesional».

Es una única página web que pone en práctica la teoría de los cuatro apartados del trabajo.

## Qué incluye

1. **Constructor y validador de prompts.** Fórmula Rol + Tarea + Contexto + Formato. El validador comprueba por reglas que cada componente esté presente, avisa de datos sensibles (correos, teléfonos, DNI, IBAN) y sugiere pedir fuentes para reducir alucinaciones. Incluye un botón para copiar un prompt de revisión que se pega en el propio ChatGPT.
2. **Anonimización de datos.** Sube un CSV o Excel de prueba, elige las columnas con nombres y la página los sustituye por «Cliente A, B…», convierte los importes en índice o cuartil, enmascara datos personales y genera la tabla de equivalencias aparte.
3. **Human-in-the-loop.** Lista de verificación obligatoria y exportación del informe revisado (texto o PDF) con el nombre del responsable.

## Privacidad

Todo se ejecuta en el navegador. Los archivos no se envían a ningún servidor, no hay cookies ni seguimiento. El único recurso externo es la librería SheetJS (cdnjs) para leer archivos Excel; con CSV no hace falta.

Los datos de `ejemplo.csv` son ficticios. No subas datos reales de clientes a un repositorio público.

## Límites

El validador comprueba la estructura de un prompt, no la calidad de su contenido, que debe juzgar una persona. La detección de datos personales se basa en patrones y puede no encontrar todos los casos: revisa siempre el resultado a mano.

## Uso

Abre `index.html` en un navegador, o la versión publicada en GitHub Pages.

## Autoría

jlasenjo
