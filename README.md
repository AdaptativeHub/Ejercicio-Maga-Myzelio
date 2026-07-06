# Skills semilla · Curso Starter Myzelio · S3

Cinco skills en Markdown, listas para subir al repo del curso en GitHub. Son la primera cosecha del micelio — sirven como referentes de qué es una skill bien escrita y como recetas útiles desde el día uno.

## Mix elegido

| Skill | Tipo | Pétalos objetivo | Uso probable |
|---|---|---|---|
| `minuta-ejecutiva-myzelio` | shallow | transversal | diario, todas las magas |
| `correo-seguimiento-stakeholder` | shallow | commercial, innovation, transversal | semanal |
| `post-linkedin-myzelio` | shallow | comms, strategy | 2-3× semana |
| `doble-materialidad-fase-1-mapeo` | **deep** | innovation impact | por proyecto |
| `propuesta-tecnica-multiactor` | **deep** | commercial, innovation | por licitación |

**Balance:** 3 shallow (uso diario/semanal, alta frecuencia, adopción rápida) + 2 deep (alto valor, uso puntual, muestran el potencial del Escalón 2 en su expresión más seria).

**Cobertura de pétalos:** las dos transversales sirven a todas. Innovation Impact & Solution Design queda cubierta (corazón metodológico). Commercial Outreach queda cubierto. Comms & Marketing queda cubierta. **Sin cobertura directa:** Operations PMO, Finance, Talent & Care, Strategy & Vision — si quieres que produzca 3-4 más para cerrar el mapa completo, dime.

## Estructura común

Todas siguen la misma anatomía. Esto es intencional — cuando las magas del curso creen sus propias skills, van a copiar esta plantilla.

```
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

Las deep además tienen `## Dependencias de contexto` — los archivos que la maga necesita cargados para que la skill funcione.

## Cómo usarlas en el aula (S3)

1. **Demo en vivo con `minuta-ejecutiva-myzelio`** — es la más simple, funciona en 90 segundos. Perfecta para el paseo guiado del bloque 5.
2. **Para descargar en el ejercicio** — cada participante elige la que le sirva a su pétalo, la carga en su maga corporativa, la corre con un caso real de la sparring.
3. **Como referente para crear su propia skill** — la estructura de estas cinco es la plantilla mental que se llevan.

## Pendientes de decisión

- **Repo:** ¿lo montamos como público en GitHub para que se vea como comunidad abierta, o privado del curso? Sugerencia: público, pero con `README` que aclare que son piezas educativas del curso, no política oficial de Myzelio.
- **Estructura de carpetas del repo:** propongo `/skills/<petalo>/<slug>.md`. Al inicio con solo 5 skills queda todo en `/skills/transversal/` y `/skills/innovation-impact/` etc.
- **Licencia:** sugiero CC BY-SA 4.0 (atribución + compartir igual) — así el micelio crece pero mantiene coherencia.

Dime cuáles ajusto y cuáles pétalos faltantes cubro.
