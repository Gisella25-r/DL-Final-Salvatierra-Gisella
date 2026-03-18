Resumen Ejecutivo
Instrucciones: Proporcione un resumen conciso (máximo 300 palabras) que incluya:

Problema de negocio abordado

Metodología utilizada

Principales hallazgos

Impacto esperado en el negocio

Problema abordado: La gestión de riesgos de la Banca Corporativa del Banco ABC (clientes con ventas > S/ 350MM) enfrenta una limitación crítica: su modelo de evaluación es reactivo, basándose en revisiones anuales que pueden demorar hasta 45 días. Esta falta de agilidad impide detectar deterioros financieros a tiempo, exponiendo a la institución a pérdidas crediticias que podrían mitigarse con un monitoreo preventivo y oportuno.

Metodología: Se diseñó e implementó un Sistema de Alerta Temprana (EWS) fundamentado en técnicas de Deep Learning. El proyecto se estructuró como un problema de clasificación multiclase para categorizar el riesgo en cuatro niveles: Sin Alerta, Verde, Amarilla y Roja. La arquitectura emplea una Red Neuronal Artificial (ANN) multicapa con funciones de activación ReLU y capas de normalización (Batch Normalization) para capturar interacciones no lineales entre ratios financieros de liquidez, solvencia y rentabilidad. Se utilizó una capa de salida Softmax para determinar las probabilidades de riesgo y se aplicó Dropout al 20% para garantizar la robustez del modelo. La solución fue validada mediante un benchmarking contra modelos de regresión logística y bosques aleatorios (Random Forest)

Principales hallazgos: El modelo de Deep Learning alcanzó un Accuracy del 94.44% en el conjunto de test, demostrando una capacidad superior de generalización frente a datos no vistos. Un hallazgo estratégico para el negocio fue la precisión del 98% en la detección de Alertas Rojas, lo que virtualmente elimina los "falsos positivos" en casos críticos y asegura que las alarmas de default sean altamente confiables. Asimismo, la red neuronal superó en 17 puntos porcentuales a la Regresión Logística tradicional (77.8%), confirmando que los riesgos financieros actuales requieren modelos no lineales para una predicción precisa.

Impacto esperado: La implementación de esta herramienta transforma la gestión de riesgos de una postura estática a una estrategia proactiva y continua. Se logra una reducción drástica en los tiempos de respuesta ante el envío de información trimestral, permitiendo la ejecución de planes de acción inmediatos y la optimización de las provisiones bancarias. Además de la mejora en la calidad de la cartera, el modelo dota al Banco ABC de una infraestructura de IA explicable y auditable, alineada con las exigencias regulatorias de la SBS y preparada para escalar hacia análisis transaccionales de alta frecuencia.

