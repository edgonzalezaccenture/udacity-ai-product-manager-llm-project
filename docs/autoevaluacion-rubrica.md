# Autoevaluación frente a la rúbrica

Revisión de [definicion-de-producto.md](definicion-de-producto.md) criterio por criterio.
Leyenda: ✅ cumple · ⚠️ mejorable · ❌ no cumple.

## Criterios obligatorios

| Sección | Criterio de la rúbrica | Estado | Dónde y cómo se cumple |
|---|---|---|---|
| Problema | Declaración simple del problema de negocio | ✅ | §1.1: una frase con el usuario, el coste (20 min, 1 de cada 12 errores) y la causa (60 versiones + manual). |
| Problema | Cómo lo resuelve hoy el cliente | ✅ | §1.1: los 5 pasos del proceso manual actual. |
| Problema | Mayores fallos de ese enfoque | ✅ | §1.1: cuatro fallos, cada uno con su impacto cuantificado. |
| Solución | Descripción en 1–3 oraciones | ✅ | §1.2: dos oraciones. |
| Solución | Qué lo hace atractivo o exitoso | ✅ | §1.2: integrado en la herramienta, verificable mediante citas, el tramitador mantiene el control. |
| Solución | Beneficio + funcionalidades necesarias | ✅ | §1.2: tabla que asocia cada beneficio a la funcionalidad que lo hace posible. |
| Solución | Por qué es mejor que la solución actual | ✅ | §1.2: comparación con la búsqueda manual, con preguntar a un senior y con un chatbot genérico. |
| Riesgos | 3–5 riesgos realistas y creativos | ✅ | §1.3: cinco riesgos. Ninguno es el genérico "la IA alucina": póliza equivocada, sesgo de automatización, inyección vía adjuntos… |
| Riesgos | Centrados en lo que está bajo nuestro control | ✅ | Cada mitigación es una decisión de diseño, de proceso o de proveedor que tomamos nosotros. |
| Riesgos | Mitigación para cada riesgo | ✅ | Columna de mitigación en la tabla. |
| Atributos | Objetivo principal + 1–2 secundarios | ✅ | §2.1: precisión (principal); privacidad y latencia (secundarios), con umbrales y regla para resolver conflictos entre ellos. |
| Arquitectura | Lista de componentes | ✅ | §2.2: 12 componentes con su papel. |
| Arquitectura | Diagrama de relaciones | ✅ | §2.2: diagrama Mermaid más el flujo numerado de una petición. |
| Arquitectura | Qué es seguro o confidencial y cómo | ✅ | §2.2: código de color en el diagrama y tabla de controles por componente y conexión. |
| Configuración LLM | Elección del modelo justificada | ✅ | §2.3: comparación de tres modelos con precio, contexto y encaje; la elección se ata al atributo principal. |
| Configuración LLM | Parámetros justificados por los objetivos | ✅ | §2.3: temperatura, razonamiento, esfuerzo, `max_tokens`, contexto, RAG frente a fine-tuning, formato de salida y caché, cada uno con su porqué. |
| Métricas | 3–5 métricas medibles ligadas a necesidades del usuario | ✅ | §3.1: cinco métricas con la necesidad, el método de medida, la línea base y el objetivo. |

## Extras para destacar

| Extra | Estado | Dónde y cómo se cumple |
|---|---|---|
| Ilustración de la arquitectura para ingeniería, producto y legal | ✅ | §2.2, "Cómo leer esta arquitectura según tu rol": por qué este enfoque y qué mira cada audiencia en el diagrama. |
| System prompt y user prompt | ✅ | §4.1, más la respuesta esperada en JSON, que muestra el razonamiento sobre una exclusión. |
| Datos de referencia: tipo, cantidad, fuentes, sesgos y actualización | ✅ | §4.2: cinco conjuntos de datos, cuatro sesgos con su detección y corrección, y una tabla de frecuencias. |

## Puntos mejorables

Ninguno impide aprobar, pero un revisor exigente podría señalarlos:

- ⚠️ **Las dos oraciones de la solución son largas.** Cumplen el límite, pero se podrían partir en tres más cortas para leerse mejor.
- ⚠️ **Las métricas 2 y 3 no tienen línea base** porque el producto es nuevo. Para que la comparación sea creíble, convendría medirlas en un piloto con 10–15 tramitadores antes del despliegue.
- ⚠️ **La estimación de coste depende de que el 70 % de los análisis reutilice la caché.** Habría que validar ese porcentaje con la distribución real de siniestros por versión de póliza.
- ⚠️ **El análisis regulatorio es preliminar.** El documento lo indica, pero una versión final debería incluir la validación de Legal.

## Ejercicios para la formación

1. Cambia el objetivo principal a **latencia** (por ejemplo, un chatbot para el cliente final). ¿Qué cambia en el modelo elegido, en los parámetros y en los riesgos?
2. Propón un sexto riesgo y decide cuál de los cinco actuales sacrificarías para respetar el límite de la rúbrica.
3. Redacta una métrica que parezca buena pero sea engañosa (por ejemplo, "número de análisis lanzados") y explica por qué no la usarías.
