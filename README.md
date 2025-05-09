# Proyecto-Habitos-estudiantes

# Análisis de Hábitos Estudiantiles y Rendimiento Académico 🎓

## 📊 Resumen Ejecutivo

Este proyecto investiga las correlaciones entre los hábitos de vida de estudiantes universitarios y su desempeño académico. Utilizando técnicas de análisis de datos y visualización avanzada, exploramos factores como patrones de estudio, bienestar, comportamiento digital y variables socioeconómicas.

## 🎯 Objetivos del Proyecto

- Identificar patrones clave que influyen en el rendimiento académico
- Evaluar el impacto de factores digitales (redes sociales, Netflix) en las calificaciones
- Analizar la influencia de hábitos saludables (sueño, dieta) en el desempeño
- Proporcionar insights basados en datos para mejorar el éxito académico

## 🏗️ Arquitectura del Proyecto

```
📁 Proyecto-Habitos-estudiantes/
├── 📄 .gitattributes
├── 📄 LICENSE
├── 📄 README.md
├── 📁 Data/
│   └── 📊 student_habits_performance.csv
└── 📁 Preprocesamiento/
    └── 📓 PRE_habitos-estudiantes.ipynb
```

## 🔬 Metodología

### Preprocesamiento de Datos
- Limpieza y validación del dataset
- Tratamiento de valores nulos mediante imputación estratégica
- Detección y manejo de outliers
- Normalización de variables numéricas

### Análisis Estadístico
1. **Análisis Univariado**
   - Distribuciones de frecuencia
   - Medidas de tendencia central
   - Análisis de dispersión

2. **Análisis Bivariado**
   - Correlaciones Pearson/Spearman
   - Tests de hipótesis
   - Visualizaciones relacionales

3. **Análisis Multivariado**
   - Matrices de correlación
   - Análisis de componentes principales
   - Modelos de regresión múltiple

## 📊 Resultados

### Principales Descubrimientos
1. **Hábitos de Estudio**
   - Los estudiantes que dedican más de 4 horas diarias al estudio muestran un 25% mejor rendimiento
   - La consistencia en el horario de estudio tiene más impacto que las horas totales

2. **Factores Digitales**
   - El uso excesivo de redes sociales (>3h/día) correlaciona negativamente con el rendimiento
   - Los estudiantes que utilizan herramientas digitales de estudio mejoran un 15% sus notas

3. **Bienestar**
   - 7-8 horas de sueño se asocian con mejores calificaciones
   - La actividad física regular muestra una correlación positiva moderada

### Recomendaciones
- Implementar programas de gestión del tiempo
- Fomentar el uso responsable de tecnología
- Promover hábitos de vida saludables

## 📈 Hallazgos Clave

| Factor | Impacto | Correlación |
|--------|---------|-------------|
| Horas de estudio | Alto ⬆️ | +0.65 |
| Redes sociales | Moderado ↔️ | -0.32 |
| Calidad del sueño | Significativo ⬆️ | +0.45 |
| Dieta | Bajo ➡️ | +0.15 |

## 🛠️ Stack Tecnológico

```python
# Core Data Science
import pandas as pd
import numpy as np
from scipy import stats

# Visualización
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go

# Configuración
warnings.filterwarnings('ignore')
```

## 📊 Visualizaciones Destacadas

- Mapas de calor para correlaciones
- Gráficos de dispersión interactivos
- Diagramas de violín para distribuciones
- Gráficos de contorno para análisis multivariado

## 🔗 Referencias y Recursos

- [Documentación de Pandas](https://pandas.pydata.org/docs/)
- [Guía de Visualización Seaborn](https://seaborn.pydata.org/tutorial.html)
- [Plotly Python](https://plotly.com/python/)

## 👥 Contribuciones

Las contribuciones son bienvenidas. Por favor, lee nuestra guía de contribución antes de enviar un pull request.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## ✍️ Autor

Desarrollado por [Natarcos](https://github.com/Natarcos)

---
*Última actualización: 2025*