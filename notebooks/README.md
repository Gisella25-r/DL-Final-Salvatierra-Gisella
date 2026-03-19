Resumen Ejecutivo
Instrucciones: Proporcione un resumen conciso (máximo 300 palabras) que incluya:

Problema de negocio abordado

Metodología utilizada

Principales hallazgos

Problema abordado:
La gestión de riesgos de la Banca Corporativa del Banco ABC (clientes con ventas > S/ 350MM) enfrenta una limitación crítica: su modelo de evaluación es reactivo, basándose en revisiones anuales que pueden demorar hasta 45 días. Esta falta de agilidad impide detectar deterioros financieros a tiempo, exponiendo a la institución a pérdidas crediticias que podrían mitigarse con un monitoreo preventivo y oportuno.

Metodología:
Se implementó un Sistema de Alerta Temprana (EWS) basado en Deep Learning (PyTorch). El proyecto categoriza el riesgo en cuatro niveles (Sin Alerta, Verde, Amarilla y Roja) mediante un etiquetado por juicio experto. La arquitectura emplea una Red Neuronal Artificial de tres capas ocultas (128, 64 y 32 neuronas) con funciones de activación ReLU y Batch Normalization. Se aplicó Dropout al 30% para garantizar la robustez ante ruidos financieros y una capa de salida Softmax para determinar probabilidades de riesgo

Principales hallazgos:
El modelo alcanzó un Accuracy del 94.44%, demostrando una capacidad superior de generalización. Un hallazgo estratégico fue la precisión del 98% en Alertas Rojas, eliminando virtualmente los falsos positivos en casos críticos. Asimismo, la red neuronal superó en 17 puntos porcentuales a la Regresión Logística tradicional (77.7%), confirmando que los riesgos corporativos requieren modelos no lineales para una predicción precisa.

Impacto esperado:
La implementación de esta herramienta transforma la gestión de riesgos de una postura estática a una estrategia proactiva y continua. Se logra una reducción drástica en los tiempos de respuesta ante el envío de información trimestral, permitiendo la ejecución de planes de acción inmediatos y la optimización de las provisiones bancarias. Además de la mejora en la calidad de la cartera, el modelo dota al Banco ABC de una infraestructura de IA explicable y auditable, alineada con las exigencias regulatorias de la SBS y preparada para escalar hacia análisis transaccionales de alta frecuencia.

