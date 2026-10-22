# Autoevaluación frente a la rúbrica

Revisión de [asesor-experto-ia-escenario-c.pptx](../asesor-experto-ia-escenario-c.pptx) con los criterios de la rúbrica oficial del proyecto.
Leyenda: ✅ cumple · ⚠️ mejorable · ❌ no cumple.

## Requisitos de la entrega

| Requisito | Estado | Cómo se cumple |
|---|---|---|
| Usar uno de los tres escenarios oficiales | ✅ | Escenario C: Asesor Experto impulsado por IA para robots industriales. |
| Entregar en la plantilla oficial de diapositivas | ✅ | Construido sobre el Starter Slide Deck, con su diseño. Se ha quitado la diapositiva de "Instrucciones" y se ha actualizado la portada, como pide la plantilla. |

## Definición del producto

| Criterio | Estado | Diapositiva |
|---|---|---|
| **Describe el problema:** declaración simple del problema de negocio | ✅ | 4: recuadro "Problema de negocio" |
| Cómo lo resuelve hoy el cliente y los mayores problemas de ese enfoque | ✅ | 4: tabla con 3 objetivos, el proceso actual y sus fallos |
| **Describe la solución** en 1–3 oraciones claras y precisas | ✅ | 5: dos oraciones en el recuadro principal |
| Qué lo hará más o menos atractivo o exitoso para el cliente | ✅ | 6: "Qué lo hará atractivo (o no)" |
| Beneficio y características necesarias para proporcionarlo | ✅ | 5 ("¿Qué haría?") y 9 (beneficios) |
| Por qué es mejor que la forma actual | ✅ | 6: "Mejor que hoy"; 5: "¿Por qué un LLM?" frente a las alternativas |
| **Riesgos y mitigaciones:** 3–5, creativos, realistas y bajo nuestro control | ✅ | 7: los 3 del escenario y 2 propios (traducción de valores críticos, fuga entre clientes); incluye elegir un proveedor de LLM que cumpla la política de privacidad |

## Detalles del sistema

| Criterio | Estado | Diapositiva |
|---|---|---|
| **Atributos:** objetivo principal y 1–2 secundarios | ✅ | 9: principal (resolver de forma segura y correcta a la primera) y 2 secundarios (rapidez e idioma) |
| **Arquitectura:** componentes y diagrama de sus relaciones | ✅ | 10: diagrama con 12 componentes y conexiones numeradas |
| Componentes y conexiones seguros o confidenciales, y cómo | ✅ | 10 (código de color) y 12 (tabla de controles) |
| **Configuración del LLM** ideal para los objetivos | ✅ | 13: licencia, implementación, temperatura y Top K; 14: modelo, contexto, salida, RAG, búsqueda y coste |

## Mejores prácticas de la industria

| Criterio | Estado | Diapositiva |
|---|---|---|
| **Métricas de éxito:** 3–5 ligadas a las necesidades del usuario | ✅ | 16: cinco métricas con valor ideal y propósito |

## Sugerencias para destacar

| Sugerencia | Estado | Diapositiva |
|---|---|---|
| Ilustración de la arquitectura para ingeniería, producto y legal | ✅ | 10 (diagrama) y 11 (qué mira cada audiencia) |
| Por qué se eligió este enfoque | ✅ | 11: "Por qué este enfoque" |
| Papel de cada componente y conexión | ✅ | 10: una línea de función en cada componente; 11: los 10 pasos numerados del flujo |
| Prompt de sistema y prompt de usuario | ✅ | 18 |
| Datos de referencia: tipo, cantidad y fuente | ✅ | 19 |
| Cómo detectar y corregir sesgos | ✅ | 20 |
| Frecuencia de actualización | ✅ | 19 |
| Supuestos señalados | ✅ | 21, junto con los próximos pasos |

## Puntos mejorables

- ⚠️ **Elección del modelo.** Se propone Claude Sonnet 4.6 porque permite fijar la temperatura y el Top K que pide la plantilla. Los modelos Claude más recientes ya no exponen esos parámetros. Un revisor podría preguntar por qué no se usa el más nuevo: la respuesta está en la diapositiva 14.
- ⚠️ **Cifras supuestas.** Los 20 minutos de búsqueda, los 30.000 tickets y las 1.000 consultas diarias no vienen del escenario. Están señalados en la diapositiva 21, pero un piloto debería medirlos.
- ⚠️ **Densidad de texto.** El deck está pensado para leerse sin presentador, así que algunas diapositivas tienen bastante texto. Para presentarlo en directo convendría resumirlo y llevar el detalle a las notas del orador.
