# Inteligencia Artificial para Estadística

**Curso electivo** – Licenciatura en Estadística  
**Basado en:** Sección de Machine Learning de CS188 (UC Berkeley) + Ingeniería de Prompts + Agentes Autónomos (OpenClaw)

## 📌 Descripción

Este curso introduce los fundamentos de inteligencia artificial desde una perspectiva práctica y computacional, con énfasis en aplicaciones para la ciencia de datos y la estadística. Los estudiantes aprenderán:

- Algoritmos clásicos de machine learning (Naive Bayes, perceptrón, regresión logística, redes neuronales básicas) usando el enfoque del curso CS188.
- Ingeniería de prompts para modelos de lenguaje grandes (LLMs): in-context learning, chain-of-thought, RAG y evaluación de prompts.
- Construcción de agentes autónomos con el framework **OpenClaw**, integrando modelos de lenguaje y herramientas para resolver tareas del mundo real.

El curso combina teoría, ejercicios prácticos en Python y un proyecto final integrador donde cada estudiante desarrolla un asistente estadístico autónomo.

## 🗂️ Estructura del repositorio

```
curso-ia-estadistica/
├── README.md                 # Este archivo
├── syllabus.md               # Temario, cronograma y evaluación
├── clases/
│   ├── 01_fundamentos_ml/    # Notebooks y slides de ML (CS188)
│   ├── 02_prompt_engineering/# Ejercicios de prompting
│   └── 03_agentes_openclaw/  # Guías de instalación y configuración de OpenClaw
├── proyectos/
│   ├── proyecto_parcial/     # Clasificador con Naive Bayes
│   └── proyecto_final/       # Agente autónomo con OpenClaw
├── datos/                    # Conjuntos de datos de ejemplo
└── recursos/                 # Enlaces, lecturas complementarias
```

## 🚀 Requisitos previos

- **Estadística básica** (probabilidad, inferencia, regresión lineal)
- **Programación en Python** (nivel intermedio: numpy, pandas, matplotlib)
- **Git** (opcional, pero recomendado para manejar el repositorio)

## 🛠️ Herramientas y librerías

- Python 3.9+
- Jupyter Notebook / Google Colab
- `scikit-learn`, `numpy`, `pandas`, `matplotlib`
- `deepseek` (para ingeniería de prompts)
- **OpenClaw** (se instalará durante el curso)

## 📚 Cómo usar este repositorio

1. **Clonar** el repositorio:
   ```bash
   git clone https://github.com/map0logo/est6047-ia.git
   ```
   (También disponible en Codeberg: `https://codeberg.org/map0logo/est6047-ia.git`)

2. **Instalar dependencias**:

- Instalar uv

- Crear entorno con uv

   ```bash
   pip install -r requirements.txt   # (si se provee)
   ```

3. **Explorar** las carpetas `clases/` y `proyectos/` en orden numérico.

4. **Ejecutar** los notebooks localmente o en Colab.

## 🤝 Contribuciones

Este repositorio es mantenido por el profesor. Si encuentras errores o deseas sugerir mejoras, por favor abre un *issue* o un *pull request*.

## 📄 Licencia

Material educativo de uso libre bajo licencia [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Los fragmentos de código pueden ser reutilizados con atribución.

## 🙏 Agradecimientos

- Curso CS188 de UC Berkeley (material original de Pieter Abbeel, John DeNero, Dan Klein)
- Comunidad de OpenClaw (antes ClawdBot)
- Learn Prompting y DeepLearning.AI por sus recursos educativos
