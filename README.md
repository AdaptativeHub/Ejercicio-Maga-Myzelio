# Skills semilla · Curso Starter Myzelio · repo del curso

Diez skills en Markdown, listas para subir al repo del curso en GitHub. Cubren los seis pétalos operativos de Myzelio con al menos una skill por pétalo, más dos transversales. Sirven a la vez como referentes de qué es una skill bien escrita y como recetas útiles desde el día uno.

## Decisiones estructurales del repo

- **Visibilidad:** público, con `README` que aclara que son piezas educativas del Curso Starter, no política oficial de Myzelio ni servicios comerciales.
- **Estructura de carpetas:** `/skills/<petalo>/<slug>.md`. Los slugs sin prefijo, en minúsculas con guiones.
- **Licencia:** CC BY-SA 4.0 (atribución + compartir igual).
- **Contribuciones:** cualquier maga del curso puede abrir PR con una skill nueva. Las skills se aprueban por revisión de la líder de pétalo correspondiente.

## Catálogo — cobertura por pétalo

| # | Skill | Tipo | Pétalo principal | Uso probable |
|---|---|---|---|---|
| 1 | `minuta-ejecutiva-myzelio` | shallow | transversal | diario |
| 2 | `correo-seguimiento-stakeholder` | shallow | transversal | semanal |
| 3 | `post-linkedin-myzelio` | shallow | comms & marketing | 2-3× semana |
| 4 | `doble-materialidad-fase-1-mapeo` | **deep** | innovation impact | por proyecto |
| 5 | `propuesta-tecnica-multiactor` | **deep** | commercial outreach | por licitación |
| 6 | `circulo-cuidado-1a1` | **deep** | talent & care | mensual |
| 7 | `plan-proyecto-90-dias` | **deep** | operations PMO | por proyecto nuevo |
| 8 | `revision-propuesta-economica` | shallow | finance | por propuesta |
| 9 | `analisis-contrato-marco` | **deep** | finance / legal | por contrato nuevo |
| 10 | `storytelling-caso-impacto` | **deep** | strategy & vision | mensual |

**Balance:** 4 shallow (uso frecuente, adopción rápida, todas las magas las prueban al menos una vez) + 6 deep (alto valor, uso puntual, muestran el potencial pleno del Escalón 2).

**Pétalos cubiertos directamente:** transversal (2), Comms & Marketing, Innovation Impact & Solution Design, Commercial Outreach, Talent & Care, Operations PMO, Finance, Strategy & Vision. Los siete pétalos operativos de Myzelio quedan con al menos una skill de referencia.

**Overrides de asignación respetados:**
- Storytelling → Carolina (Strategy & Vision)
- P6 legal → Inés (contrato marco)
- P6 financial → Juan (propuesta económica)
- P7 core care → Helena (círculo de cuidado)

## Estructura común de una skill

Todas siguen la misma anatomía. Esto es intencional — cuando las magas del curso creen sus propias skills, van a copiar esta plantilla.

```markdown
---
name: [slug]
tipo: shallow | deep
petalos: [lista]
version: 0.1
autor: micelio
descripcion: [una frase]
---

# [Título]

## Cuándo usar esta skill
## Qué produce
## Reglas de la maga
## Cómo se activa
## Referentes de excelencia
```

Las **deep** añaden `## Dependencias de contexto` al final.

Las skills con carga ética o sensible (cuidado del equipo, contratos, storytelling con protagonistas reales) añaden `## Nota ética` o `## Nota de seguridad` — esto marca a las magas del curso que hay territorios donde la IA acompaña pero la responsabilidad sigue siendo humana.

## Cómo se usan en el aula (S3)

1. **Demo en vivo con `minuta-ejecutiva-myzelio`** — es la más simple, funciona en 90 segundos. Perfecta para el paseo guiado del bloque 5.
2. **Descarga en el ejercicio** — cada participante elige la que le sirva a su pétalo, la carga en su maga corporativa, la corre con un caso real de la sparring.
3. **Como referente para crear su propia skill** — la estructura de estas diez es la plantilla mental que se llevan para redactar las suyas.

## Cómo se descarga una skill

Desde el repo público:

```
1. Navegar a la skill (ej: /skills/finance/revision-propuesta-economica.md)
2. Click en el botón "Raw"
3. Guardar como archivo .md
4. Subirla a tu maga corporativa (proyecto en Claude o gema en Gemini)
   como archivo de contexto
```

Alternativa para las que sepan git: `git clone` del repo entero y sirven todas las skills a la vez.

## Cómo se agrega una skill nueva al repo

Las magas del curso pueden proponer skills nuevas creadas con sus magas:

```
1. Fork del repo del curso
2. Crear la skill en /skills/<tu-petalo>/<slug>.md siguiendo la plantilla
3. Actualizar el catálogo de este README (fila nueva en la tabla)
4. Abrir Pull Request describiendo qué hace la skill y con qué maga
   la crearon
5. Revisión de la líder del pétalo correspondiente + una co-revisora
   del micelio
6. Merge
```

Las skills contribuidas mantienen atribución de autora en el frontmatter (`autor:`).

## Skills que quedan como pendientes obvios

Con este catálogo cubrimos el 80% de la operación Myzelio. Skills que probablemente se van a pedir pronto:

- **`revision-doble-materialidad-fase-2`** (Innovation Impact) — la continuación natural de la 4
- **`estructura-deck-ejecutivo`** (Comms) — para Laura Correa, transformar contenido en storyboard de deck
- **`tracker-clima-diario`** (Innovation Impact, Laura Bedoya) — el override lo asigna
- **`agenda-de-comite-multiactor`** (Operations PMO) — complemento de la 7
- **`brief-comercial-para-oportunidad-entrante`** (Commercial Outreach) — cuando llega un lead, cómo se procesa

Estas se producen cuando las dueñas de pétalo las pidan — no hay que sembrarlas todas de una.

## Cierre

Este repo es el primer músculo del micelio. Diez skills semilla; el resto crece con las magas que las usan, las mejoran y proponen las suyas. La regla es simple: si algo te queda muy bien hecho con una maga, documéntalo y compártelo. Las recetas del micelio son de todas.
