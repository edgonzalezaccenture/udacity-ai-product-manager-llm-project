# Autoevaluación frente a la rúbrica

Revisión de [asesor-experto-ia-escenario-c.pptx](../asesor-experto-ia-escenario-c.pptx) criterio por criterio.
Leyenda: ✅ cumple · ⚠️ mejorable · ❌ no cumple.

## Requisitos de la entrega

| Requisito | Estado | Cómo se cumple |
|---|---|---|
| Usar uno de los tres escenarios oficiales | ✅ | Escenario C: Asesor Experto impulsado por IA para robots industriales. |
| Entregar en la plantilla oficial de diapositivas | ✅ | Construido sobre el Starter Slide Deck, con su diseño. Se ha quitado la diapositiva de "Instrucciones" y se ha actualizado la portada, como pide la plantilla. |

## Criterios obligatorios

| Sección | Criterio | Estado | Diapositiva |
|---|---|---|---|
| Cliente | Usuario objetivo y características demográficas y de comportamiento | ✅ | 3: técnicos de 20 a 60 años, 5 idiomas, 95 % en el móvil, contexto a pie de máquina |
| Problema | Qué intenta hacer el usuario, cómo lo hace hoy y los mayores fallos | ✅ | 4: tres objetivos, cada uno con su proceso actual y sus fallos |
| Solución | Descripción en 1–3 frases | ✅ | 5: dos frases en el recuadro principal |
| Solución | Preguntas de la plantilla: qué haría, qué reemplaza, datos, privacidad, conectividad, por qué un LLM | ✅ | 5 y 6: una tarjeta por pregunta |
| Riesgos | 3–5 riesgos con mitigación | ✅ | 7: los 3 del escenario y 2 propios, con mitigaciones bajo nuestro control |
| Atributos | Beneficio principal y 1–2 secundarios | ✅ | 9: principal (seguro y correcto a la primera) y 2 secundarios (rapidez e idioma), con la regla para cuando chocan |
| Arquitectura | Componentes, diagrama y flujo de datos | ✅ | 10 y 11: diagrama con 12 componentes y flujo numerado en 10 pasos |
| Arquitectura | Qué es confidencial y cómo se protege | ✅ | 10 (código de color) y 12 (tabla de controles) |
| Configuración del LLM | Licencia, implementación, temperatura y Top K justificados | ✅ | 13: las cuatro celdas de la plantilla rellenas y justificadas |
| Configuración del LLM | Modelo, tokens, contexto, RAG o fine-tuning | ✅ | 14: modelo, contexto, salida, RAG frente a fine-tuning, búsqueda y coste |
| Métricas | 3–5 métricas con valor ideal y propósito | ✅ | 16: cinco métricas ligadas a los beneficios y a los riesgos |

## Extras para destacar

| Extra | Estado | Diapositiva |
|---|---|---|
| Arquitectura explicada para ingeniería, producto y legal | ✅ | 11: por qué este enfoque y qué mira cada audiencia |
| Prompt de sistema y prompt de usuario | ✅ | 18 |
| Datos de referencia: tipo, cantidad, fuente y actualización | ✅ | 19 |
| Sesgos: detección y corrección | ✅ | 20 |
| Supuestos señalados | ✅ | 21, junto con los próximos pasos |

## Puntos mejorables

- ⚠️ **Elección del modelo.** Se propone Claude Sonnet 4.6 porque permite fijar la temperatura y el Top K que pide la plantilla. Los modelos Claude más recientes ya no exponen esos parámetros. Un revisor podría preguntar por qué no se usa el más nuevo: la respuesta está en la diapositiva 14.
- ⚠️ **Cifras supuestas.** Los 20 minutos de búsqueda, los 30.000 tickets y las 1.000 consultas diarias no vienen del escenario. Están señalados en la diapositiva 21, pero un piloto debería medirlos.
- ⚠️ **Densidad de texto.** El deck está pensado para leerse sin presentador, así que algunas diapositivas tienen bastante texto. Para presentarlo en directo convendría resumirlo y llevar el detalle a las notas del orador.
