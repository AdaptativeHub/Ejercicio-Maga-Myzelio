---
name: doble-materialidad-fase-1-mapeo
tipo: deep
petalos: [innovation-impact-solution-design]
version: 0.1
autor: micelio
requiere_referentes: sí
descripcion: Acompaña la Fase 1 de un análisis de doble materialidad — mapeo inicial de temas materiales candidatos a partir de la industria del cliente, sus stakeholders y su cadena de valor. NO produce el reporte final. Produce el mapa exploratorio que la analista humana refina con juicio experto.
---

# Doble materialidad · Fase 1 · Mapeo de temas candidatos

## Cuándo usar esta skill

En el arranque de un análisis de doble materialidad con un cliente, cuando necesitas producir el **mapa inicial de temas materiales candidatos** — el insumo que después la analista humana valida, prioriza y conecta con el diagnóstico del cliente. Esta skill acelera la fase exploratoria; no reemplaza el juicio de la analista.

**No usar para:** producir la matriz final de doble materialidad, escribir la sección de materialidad de un reporte, ni tomar decisiones sobre qué temas quedan dentro o fuera. Esas son decisiones humanas.

## Qué produce

Un documento estructurado con cinco secciones:

### 1. Contexto del cliente
- Industria (ISIC/GICS)
- Cadena de valor en 3-5 nodos
- Ubicaciones geográficas relevantes
- Stakeholders principales identificados

### 2. Universo de temas candidatos
Lista de 20-40 temas materiales candidatos, cada uno con:
- Nombre del tema
- Marco de referencia primario (GRI, ESRS, SASB, TCFD, TNFD según aplique)
- Dimensión: impacto (inside-out) / financiero (outside-in) / ambas
- Fuente del dato (por qué aparece este tema para este cliente)

### 3. Clústeres temáticos
Los 20-40 temas agrupados en 5-8 clústeres de sentido (ej: gestión del agua, cadena de suministro responsable, gobernanza climática, capital humano, comunidad y territorio).

### 4. Stakeholders y voces por consultar
Mapa preliminar de qué stakeholder tiene visibilidad sobre cuáles clústeres. Base para el plan de engagement de la Fase 2.

### 5. Preguntas abiertas para la analista
Lo que la maga NO puede resolver sola y necesita juicio humano:
- Temas de frontera (¿entra o no entra?)
- Solapamientos con otros marcos del cliente
- Sensibilidades del contexto local que la maga no puede leer

## Reglas de la maga

1. **Marcos de referencia explícitos siempre.** Cada tema candidato cita el marco (GRI, ESRS, SASB, TCFD, TNFD). Sin marco no hay tema.
2. **Doble dimensión no negociable.** Cada tema clasificado por impacto Y por financiero. Si no sabes clasificarlo, márcalo como "revisar" y pregunta a la analista.
3. **Sin humo.** Si un tema no tiene fuente clara (marco de referencia, hallazgo de peer review, mención en documentación del cliente), no lo incluyas. Cero temas inventados.
4. **Contexto latinoamericano cuando aplique.** Si el cliente opera en LATAM, los temas de derechos humanos, consulta previa, informalidad laboral, ecosistemas frágiles no se subestiman.
5. **La maga declara sus límites.** Si la industria del cliente es atípica o si hay solapamiento fuerte entre marcos, lo escribe explícito en la sección 5.
6. **Voz técnica, no consultoril.** Terminología precisa de sostenibilidad. Cero muletillas ("cabe destacar", "es importante mencionar").

## Cómo se activa

> "Corre la fase 1 de doble materialidad para este cliente. Datos que te paso: [industria, ubicaciones, documentos si tienes]. Usa la skill doble-materialidad-fase-1-mapeo. Al final, dame el documento estructurado y la lista de preguntas abiertas para mí."

## Referentes de excelencia

Un buen output Fase 1 le ahorra a la analista 2-3 días de exploración y le entrega un mapa que puede refinar, no un mapa que tiene que rehacer. Los temas están bien clasificados por marco, los clústeres tienen coherencia interna, y las preguntas abiertas revelan qué decisiones humanas quedan pendientes. Si la analista tiene que reclasificar más del 30% de los temas, la maga necesita mejor contexto de entrada.

## Dependencias de contexto

Esta skill funciona bien cuando el proyecto tiene cargados:
- Manual metodológico Myzelio de doble materialidad
- Marcos de referencia relevantes (al menos GRI + ESRS + uno sectorial)
- 2-3 documentos del cliente (memoria de sostenibilidad previa si existe, plan estratégico, mapa de stakeholders)
- 1-2 análisis de doble materialidad de referencia (peer benchmark)
