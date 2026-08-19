# Markdown × IA: guía del participante

## Idea central

La IA recibe texto. Al estructurar el texto, haces explícitos el objetivo, el contexto, los límites y el formato esperado. Esto mejora la trazabilidad y facilita revisar la respuesta.

## Estructura mínima de un prompt reutilizable

\`\`\`markdown
# Rol
¿Desde qué perspectiva debe trabajar la IA?

# Tarea
¿Qué debe hacer exactamente?

# Contexto
¿Qué información puede usar? Delimítala con etiquetas.

# Límites
¿Qué no debe inventar, usar o hacer?

# Entregable
¿Qué formato debe tener la respuesta?
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
- [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/): visualizador de código DOT.
- [XML Validation](https://www.xmlvalidation.com/): comprobación de sintaxis XML.
- [MarkItDown](https://github.com/microsoft/markitdown): proyecto para convertir documentos a Markdown.

## Reto final

Escoge una tarea no sensible. Crea una plantilla Markdown con rol, tarea, contexto, límites y entregable. Pruébala con una IA, revisa el resultado y ajusta una sola sección para mejorar la siguiente respuesta.
