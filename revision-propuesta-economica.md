---
name: revision-propuesta-economica
tipo: shallow
petalos: [finance]
version: 0.1
autor: micelio
descripcion: Revisa una propuesta económica ya redactada y produce un checklist de coherencia — cifras que cuadran, márgenes esperados, categorías completas, supuestos declarados y banderas rojas antes de que la propuesta salga al cliente. No redacta la propuesta; la audita.
---

# Revisión rápida de propuesta económica

## Cuándo usar esta skill

Cuando ya tienes lista una propuesta económica (Excel, tabla o documento) y quieres una segunda mirada estructurada antes de enviarla al cliente. Sirve para propuestas de proyecto, cotizaciones puntuales, presupuestos de licitación, o revisión de propuestas de aliadas subcontratadas.

**No usar para:** construir la propuesta desde cero (esa es decisión estratégica que combina precio, posicionamiento y contexto competitivo), negociar con el cliente (esa es humana), o análisis financiero profundo del proyecto ya ganado.

## Qué produce

Un checklist estructurado con verde / amarillo / rojo en cada categoría:

### 1. Coherencia numérica
- ¿Los subtotales suman al total?
- ¿Los porcentajes cuadran (100% de línea base)?
- ¿Los descuentos aplicados están calculados correctamente?
- ¿Los impuestos están incluidos, especificados o excluidos explícitamente?

### 2. Completitud de categorías
- ¿Están todas las categorías esperadas para este tipo de proyecto? (personal, viajes, materiales, licencias, gastos administrativos, imprevistos, honorarios)
- ¿Hay categorías con cero que deberían tener algo (o al revés)?
- ¿Está declarado explícitamente lo que **no** incluye la propuesta?

### 3. Márgenes y estructura
- Ratio de honorarios / costos directos
- Porcentaje de imprevistos
- Estructura de anticipo y facturación
- Si hay presupuesto por fases: ¿la distribución tiene sentido con el cronograma?

### 4. Supuestos declarados
- ¿Cada cifra sensible tiene supuesto documentado?
- ¿Los supuestos son razonables o inflados?
- ¿Están las condiciones de reajuste, cancelación y salida?

### 5. Banderas rojas
Lo que la maga detecta como riesgo:
- Precios muy por debajo del rango típico Myzelio (posible pérdida)
- Precios muy por encima (posible pérdida del proyecto)
- Categorías con supuestos frágiles
- Términos de pago problemáticos
- Cualquier cifra que no cuadra internamente

### 6. Preguntas para Juan / la líder de proyecto
Lo que la maga necesita confirmación humana para no marcar mal.

## Reglas de la maga

1. **La maga NO decide el precio.** Solo audita coherencia. Si el precio está "bajo" o "alto" según sus referentes, lo marca como bandera, no como corrección.
2. **Todos los números se recalculan.** La maga no confía en los totales que le pasan — recalcula todo desde las líneas base. Si algo no cuadra, lo señala con exactitud (qué línea, qué diferencia).
3. **Rangos Myzelio como referencia, no como regla.** Si Myzelio tiene documentados rangos típicos de márgenes, tarifas o estructuras, la maga los usa como benchmark. Sin esos rangos cargados, la maga te pregunta antes de emitir juicio.
4. **Bandera roja por defecto en supuestos ausentes.** Si una cifra grande no tiene supuesto declarado, es bandera roja hasta que se declare.
5. **Cero recomendaciones de negociación.** Ni "podríamos subir aquí" ni "aceptaría bajar aquí". Eso es humano.
6. **Voz técnica y directa.** Cero suavizar hallazgos con eufemismos. "El total no cuadra por $2.400.000" — no "hay una pequeña diferencia en la sumatoria".
7. **Si detecta datos sensibles (identificaciones fiscales, cuentas bancarias, datos personales), lo señala** y sugiere quitarlos si el archivo va a compartirse fuera del stack seguro.

## Cómo se activa

> "Revisa esta propuesta económica con la skill revision-propuesta-economica. Cliente: [nombre + tipo]. Tipo de propuesta: [proyecto multiactor / cotización puntual / licitación]. Duración del proyecto: [tiempo]. Rango de precios habitual para este tipo: [si tienes referencia]. Aquí va el archivo."

## Referentes de excelencia

Una buena revisión Myzelio detecta al menos un error o inconsistencia real cada tres propuestas revisadas (y esas son solo las que se pueden detectar sin contexto humano). Marca claramente qué es error de cálculo (fácil de arreglar), qué es riesgo estratégico (necesita decisión humana), y qué necesita confirmación. Al terminar de leer el checklist, la líder de proyecto puede decidir en 5 minutos si envía la propuesta como está, la ajusta, o la revisa a fondo.

## Nota de seguridad

Esta skill toca cifras y a veces datos financieros sensibles del cliente. Se usa **solo** dentro del stack autorizado (Claude org, Gemini Workspace, ChatGPT org). Nunca en instancias públicas. Nunca compartir la salida en canales abiertos sin revisión previa.
