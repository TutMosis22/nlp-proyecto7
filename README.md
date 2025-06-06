# Proyecto 7 - Few-shot & In-Context Learning

Este proyecto explora mecanismos para que grandes modelos de lenguaje realicen tareas con pocos ejemplos (few-shot learning) o sin ajuste de parámetros, usando **prompts**. Implementamos una serie de experimentos con distintas estrategias de prompting, utilizando modelos generativos a nuestro alcance.

## Objetivos

- Diseñar prompts efectivos para clasificación de sentimientos y extracción de información.
- Evaluar cómo varía el desempeño del modelo al cambiar el número de ejemplos (0-shot, 1-shot, 5-shot).
- Explorar **Instruction Tuning** y calibración de polaridad.
- Evaluar la precisión y calibración de los resultados generados.

## Técnicas utilizadas

- **Prompting clásico**: Estructura tipo: Describe tarea || Ejemplos || Entrada nueva
- **PET (Pattern-Exploiting Training)**: Reformulación de tareas de clasificación.
- **Instruction Tuning**: Ajuste del modelo para responder a instrucciones en lenguaje natural.
- **Chain-of-thought**: Prompts con razonamiento paso a paso.

## Métricas

- **Accuracy**
- **F1-score**
- **Brier Score** (calibración de probabilidad)

## Actividades principales

1. Diseño de prompts para clasificación de sentimiento.
2. Comparación entre 0-shot, 1-shot y 5-shot.
3. Evaluación de razonamiento (chain-of-thought).
4. Medición de desempeño con distintas métricas.
5. Análisis del impacto del número de *shots* y calidad de los prompts.

## Requisitos

## Instalar las dependecias con

pip install -r requirements.txt