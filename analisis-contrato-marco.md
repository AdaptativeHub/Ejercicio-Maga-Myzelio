---
name: analisis-contrato-marco
tipo: deep
petalos: [finance]
version: 0.1
autor: micelio
requiere_referentes: sí
descripcion: Produce un análisis estructurado de un contrato marco recibido de un cliente o aliada — cláusulas clave identificadas, riesgos jurídicos y operativos, obligaciones asumidas, y preguntas para abogada externa antes de firmar. No sustituye asesoría legal; la prepara.
---

# Análisis inicial de contrato marco

## Cuándo usar esta skill

Cuando llega un contrato marco, convenio, contrato de prestación de servicios o acuerdo de colaboración de un cliente o de una aliada, y necesitas un análisis estructurado antes de:

- Firmar
- Enviar a la abogada externa para revisión legal formal
- Devolverlo con comentarios y ajustes solicitados

**No usar para:** decidir firmar sin revisión de abogada (el análisis de la maga **no** reemplaza asesoría legal), interpretar cláusulas de contratos ya firmados en disputa (esas van directo a abogada), o redactar contratos desde cero.

## Qué produce

Un documento estructurado con:

### 1. Identificación
- Tipo de contrato (marco, prestación de servicios, colaboración, subcontratación, otro)
- Partes involucradas
- Objeto del contrato en una frase
- Vigencia
- Valor económico (si aplica)
- Ley aplicable y jurisdicción

### 2. Obligaciones de Myzelio
Lista completa y específica de:
- Qué se compromete Myzelio a hacer
- Entregables y plazos
- Estándares de calidad exigidos
- Responsabilidades continuas post-entrega

### 3. Obligaciones de la contraparte
Lista completa y específica de:
- Qué se compromete la contraparte a hacer
- Pagos (montos, moneda, plazos, condiciones)
- Insumos que debe proveer
- Aprobaciones y validaciones

### 4. Cláusulas críticas identificadas
Análisis de:
- **Propiedad intelectual** — quién es dueña de qué (metodologías, entregables, herramientas)
- **Confidencialidad** — alcance, duración, excepciones
- **Exclusividad** — si existe y con qué alcance
- **Terminación** — causales, plazos, penalidades
- **Responsabilidad** — límites, exclusiones, seguros exigidos
- **Cesión** — si Myzelio puede subcontratar o ceder derechos
- **Resolución de conflictos** — arbitraje, jurisdicción, ley aplicable
- **Fuerza mayor** — cómo se define y cómo opera
- **Modificaciones** — cómo se ajusta el contrato durante su vigencia

### 5. Riesgos identificados
- **Riesgos operativos:** obligaciones difíciles de cumplir, plazos ajustados, dependencias externas
- **Riesgos jurídicos:** cláusulas potencialmente desequilibradas, ambigüedades peligrosas, obligaciones abiertas
- **Riesgos financieros:** términos de pago problemáticos, penalidades desproporcionadas, exposición no acotada

Cada riesgo con clasificación: alto / medio / bajo, y sugerencia de cómo mitigarlo (ajuste de cláusula, garantía, seguro, etc.).

### 6. Preguntas para abogada externa
Lo que la maga identifica como necesitado de juicio legal profesional. Estas van directo a Inés o a la abogada externa antes de firmar.

### 7. Recomendación de flujo
- ¿Se puede firmar como está? (rara vez)
- ¿Requiere ajustes menores negociables? (típico)
- ¿Requiere renegociación de fondo? (bandera roja mayor)
- ¿Requiere revisión legal completa obligatoria? (siempre para contratos marco nuevos)

## Reglas de la maga

1. **La maga NO reemplaza a la abogada.** Al inicio del análisis lo declara explícito: "Este análisis es un primer filtro. Todo contrato debe pasar por revisión de abogada antes de firmar."
2. **Cero interpretación jurídica creativa.** La maga identifica y clasifica; no interpreta implicaciones legales complejas. Si una cláusula requiere interpretación jurídica (por ejemplo, alcance de una limitación de responsabilidad bajo derecho colombiano), la maga la marca como pregunta para abogada.
3. **Contexto Myzelio siempre.** La maga sabe que Myzelio es consultora regenerativa y las cláusulas se leen en ese contexto — una cláusula de exclusividad amplia es más grave para Myzelio que para una gran corporación.
4. **Detecta lo que falta, no solo lo que dice.** Muchos riesgos vienen por lo que el contrato **no** dice: silencio sobre propiedad intelectual de metodología, silencio sobre confidencialidad reversa (cliente hacia Myzelio), silencio sobre uso de casos como referentes futuros.
5. **Rango temporal en obligaciones.** Toda obligación se lee en su horizonte: obligaciones que sobreviven a la terminación del contrato son especialmente sensibles.
6. **Voz precisa y jurídica.** Terminología correcta. No confundir "convenio" con "contrato" ni "responsabilidad" con "obligación". Si la maga no sabe la palabra correcta, pregunta.
7. **Idioma del contrato = idioma del análisis.** Si el contrato está en inglés, el análisis se produce en español pero cita las cláusulas en su idioma original.

## Cómo se activa

> "Analiza este contrato con la skill analisis-contrato-marco. Contraparte: [nombre + tipo de organización]. Contexto del proyecto: [una frase]. Ley aplicable esperada: [Colombia / otra]. Aquí va el archivo del contrato."

## Referentes de excelencia

Un buen análisis Myzelio le ahorra a la abogada externa entre 40% y 60% del tiempo de revisión — llega con obligaciones ya mapeadas, riesgos clasificados y preguntas específicas. Detecta al menos una cláusula problemática en cada contrato nuevo (los contratos limpios son raros). No pretende sustituir a la abogada, pero le entrega el trabajo hecho a nivel de estructura para que ella se concentre en interpretación y negociación.

## Dependencias de contexto

Esta skill funciona bien cuando el proyecto tiene cargados:
- Contratos marco Myzelio ya firmados como referentes
- Documento interno con "cláusulas modelo Myzelio" si existe (posiciones estándar en propiedad intelectual, confidencialidad, resolución de conflictos)
- Notas de casos previos con problemas de contrato (aprendizajes documentados)
- Marco legal aplicable resumido si opera en múltiples jurisdicciones

## Nota de seguridad

Los contratos suelen contener información confidencial de ambas partes. Esta skill se corre **solo** dentro del stack autorizado (Claude org, Gemini Workspace, ChatGPT org). Nunca cargar contratos en instancias públicas. Al terminar el análisis, la maga sugiere buenas prácticas de manejo del archivo (permisos, quién puede acceder, retención).
