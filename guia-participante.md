# Markdown × IA: guía del participante

## Idea central

La IA recibe texto. CREA ayuda a hacer explícitos el contexto, los límites, el formato y la acción esperada. Esto mejora la trazabilidad y facilita revisar la respuesta.

## CREA: estructura mínima de un prompt reutilizable

\`\`\`markdown
# C · Contexto y rol
¿Cuál es la situación, qué fuentes puede usar y desde qué perspectiva debe trabajar la IA?

# R · Restricciones y criterios
¿Qué no debe inventar, usar o hacer? ¿Qué tono, extensión y criterios debe respetar?

# E · Estructura de salida
¿Qué formato debe tener la respuesta: tabla, lista, Markdown, JSON, XML o código?

# A · Acción principal
¿Qué debe hacer exactamente? Usa un verbo: analiza, redacta, resume, extrae o compara.
\`\`\`

## Cuándo usar cada formato

| Formato | Úsalo cuando necesitas | Ejemplo |
|---|---|---|
| Markdown | Comunicar y organizar información | Un informe, un prompt, notas de reunión |
| Graphviz / DOT | Visualizar relaciones o un proceso | Flujo de aprobación |
| JSON | Campos constantes y datos reutilizables | Registro de solicitudes |
| XML | Jerarquía y etiquetas descriptivas | Documento estructurado o integración |

## Reglas de cuidado

1. No cargues información personal, financiera o institucional confidencial en servicios no autorizados.
2. Revisa todo resultado: una salida bien formateada puede seguir siendo incorrecta.
3. Si conviertes un documento a Markdown, valida títulos, listas, tablas y números antes de usarlo.
4. Si un texto copiado se comporta extraño, verifica espacios, saltos de línea y caracteres invisibles.

## Herramientas de práctica

- [StackEdit](https://stackedit.io/): editor de Markdown con vista previa.
- [Dillinger](https://dillinger.io/): editor Markdown en el navegador.
- [MDFlux](https://github.com/ibrahimqureshae/mdflux): aplicación local para Windows que convierte documentos y escaneos a Markdown sin usar terminal.
- [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/): visualizador de código DOT.
- [XML Validation](https://www.xmlvalidation.com/): comprobación de sintaxis XML.
- [MarkItDown](https://github.com/microsoft/markitdown): proyecto para convertir documentos a Markdown.

## Reto final

Escoge una tarea no sensible. Crea una plantilla Markdown con CREA: Contexto y rol, Restricciones, Estructura de salida y Acción. Pruébala con una IA, revisa el resultado y ajusta una sola sección para mejorar la siguiente respuesta.
