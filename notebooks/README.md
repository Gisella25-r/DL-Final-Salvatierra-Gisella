Sistema de Alerta Temprana (EWS) para Empresas de Banca Corporativa del Banco ABC
Estudiante: Salvatierra, Gisella

Institución: CENTRUM PUCP

Curso: Deep Learning - Aplicaciones Prácticas

Resumen Ejecutivo

Este proyecto implementa un Sistema de Alerta Temprana (Early Warning System - EWS) basado en Inteligencia Artificial para la gestión proactiva de riesgos de los clientes de Banca Corporativa del Banco ABC (empresas con ventas anuales de S/ 350 millones como mínimo). Mediante el uso de Redes Neuronales Artificiales (ANN), el sistema analiza indicadores financieros trimestrales para predecir y clasificar el nivel de deterioro de los clientes antes de que ocurra un evento de incumplimiento.

A) El Problema de Negocio
Actualmente, las evaluaciones de riesgo de los clientes de Banca Corporativa se basan en revisiones anuales estáticas que suelen ser reactivas y demoran un máximo de 45 días aproximadamente. Esta situación impide al banco tomar medidas de mitigación oportunas cuando detecta problemas de deterioro económico-financiero en las empresas. 

B) La Solución (Propuesta de Valor)

Monitoreo Dinámico: El modelo procesa información trimestral, eliminando la dependencia de la revisión anual.

Detección de Patrones No Lineales: Supera los límites del análisis tradicional de ratios al identificar interrelaciones complejas entre liquidez, endeudamiento y eficiencia operativa.

Clasificación Multiclase: Categoriza a los clientes en 4 niveles: Sin Alerta, Verde, Amarilla y Roja, permitiendo una intervención inmediata en los niveles preventivos (Verde/Amarilla).

C) Aspectos Técnicos del Modelo
Siguiendo los lineamientos de las sesiones de clase (Deep Learning), se desarrolló un pipeline completo:

Arquitectura: Red Neuronal Feed-Forward (Multilayer Perceptron) con capas densas.

Activaciones: ReLU en capas ocultas para gestionar la no linealidad y Softmax en la capa de salida para clasificación multiclase.

Optimización: Uso de Dropout (20%) para evitar el sobreajuste y optimizador Adam para una convergencia eficiente.

Dataset: Generación de 8,400 registros sintéticos (700 empresas por 12 trimestres) para garantizar la robustez del entrenamiento.

D) Resultados Clave
Accuracy: 99.88% en el set de prueba (1,680 registros independientes).

Recall (Sensibilidad): El modelo demostró una alta eficacia detectando el 100% de las alertas críticas (Rojas), cumpliendo su función primordial de prevención de default.

Impacto: El banco pasa de una revisión anual a una calificación predictiva instantánea apenas se recibe la información financiera trimestral.

E) Estructura del Repositorio
/notebooks: Contiene el archivo SALVATIERRA_GISELLA_Final_Project.ipynb con el código fuente y gráficos de desempeño.
El dataset se genera en el mismo Colab. La explicación del dataset se encuentra en el Colab.

NOTA: El detalle de todo el proyecto, incluyendo objetivos, preparación de la data, justificación del modelo, conclusiones y recomendaciones, se encuentra en el archivo SALVATIERRA_GISELLA_Final_Project.ipynb
