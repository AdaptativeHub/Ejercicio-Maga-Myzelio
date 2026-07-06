---
name: minuta-ejecutiva-myzelio
tipo: shallow
petalos: [transversal]
version: 0.1
autor: micelio
descripcion: Convierte una transcripción o notas de reunión en una minuta ejecutiva Myzelio — decisiones, compromisos con dueña y fecha, riesgos, y próximo paso. Formato fijo, tono cálido, sin relleno.
---

# Minuta ejecutiva Myzelio

## Cuándo usar esta skill

Cuando salgas de una reunión — interna, con cliente, con aliadas de coalición — y necesites una minuta en menos de cinco minutos que otras personas puedan leer sin haber estado. Sirve para reuniones de proyecto, comités, sesiones de innovación, llamadas comerciales de seguimiento.

**No usar para:** actas legales, reuniones de junta directiva, o cualquier documento con requisitos formales de registro. Para eso, escríbelo tú.

## Qué produce

Un documento en Markdown con esta estructura exacta:

```markdown
# Minuta · [nombre del espacio] · [fecha]

**Participantes:** [nombres, sin cargos]
**Duración:** [min]
**Contexto en una frase:** [para qué nos reunimos]

## Decisiones tomadas
- [decisión 1]
- [decisión 2]

## Compromisos
| Qué | Dueña | Para cuándo |
|---|---|---|
| [tarea] | [nombre] | [fecha] |

## Riesgos y alertas
- [riesgo 1 — con contexto de una línea]

## Próximo paso concreto
[la siguiente acción del sistema, no del equipo entero]
```

## Reglas de la maga

1. Nada de relleno. Si no hubo decisiones, escribe "no se tomaron decisiones formales". No inventes.
2. Los compromisos van con dueña **específica** — nunca "el equipo", nunca "todas". Si no hay dueña clara, la maga pregunta.
3. Los riesgos se nombran, no se suavizan. "Retraso probable de 2 semanas" — no "posibles ajustes de cronograma".
4. Tono cálido pero seco. Somos micelio, no consultoras.
5. Si la reunión tuvo carga emocional o de cuidado (equipo, conflicto, transición), agrega al final un párrafo corto de contexto — pero sin dramatismo. Solo lo que la próxima lectora necesita saber para entrar bien.

## Cómo se activa

Le pasas a la maga la transcripción, las notas o el audio (si tienes conector) y le dices:

> "Convierte esto en una minuta Myzelio con la skill de minuta-ejecutiva."

Si la maga no tiene la skill cargada, primero cárgala como archivo de contexto en el proyecto/gema.

## Referentes de excelencia

Una buena minuta Myzelio se lee en 90 segundos, tiene 3-5 decisiones máximo, todos los compromisos tienen dueña y fecha, y la próxima lectora sabe exactamente qué pasa después. Si la minuta tiene más de una página, algo se está inflando.
