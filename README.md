# 🏋️‍♂️ Fitness Tracker – Data Analysis & Visualization

Este proyecto analiza y visualiza datos personales de salud y fitness, integrando análisis exploratorio de datos (EDA), visualizaciones interactivas con Plotly y algunos insights clave sobre actividad física, sueño, frecuencia cardíaca y más.

---

## 📂 Contenido del proyecto

- **Notebook principal**: `FitnessTracker.ipynb`
- **Fuente de datos**: CSV de seguimiento personal con métricas diarias
- **Lenguaje**: Python
- **Librerías principales**: `pandas`, `plotly`, `statsmodels`, `numpy`

---

## 📊 Dataset – Diccionario de datos

| Columna | Descripción |
|--------|-------------|
| `date` | Fecha de registro |
| `steps` | Número de pasos diarios |
| `weight` | Peso corporal en kg |
| `resting_heart_rate` | Frecuencia cardíaca en reposo |
| `sleep_hours` | Horas de sueño |
| `active_minutes` | Minutos activos totales |
| `total_calories_burned` | Calorías quemadas en el día |
| `fat_burn_minutes` | Minutos en zona de quema de grasa |
| `cardio_minutes` | Minutos en zona cardio |
| `peak_minutes` | Minutos en zona pico |
| `workout_type` | Tipo de entrenamiento |
| `workout_duration` | Duración del entrenamiento (min) |
| `workout_calories` | Calorías quemadas en el entrenamiento |
| `workout_avg_hr` | Frecuencia cardíaca promedio durante el entrenamiento |
| `workout_max_hr` | Frecuencia cardíaca máxima durante el entrenamiento |

---

## 🔍 Secciones del notebook

1. **Exploratory Data Analysis (EDA)**  
   - Estadísticas descriptivas  
   - Valores faltantes  
   - Limpieza de datos  

2. **Feature Engineering**  
   - Nuevas columnas como identificación de fines de semana, calorías netas, etc.

3. **Visualización de Datos**  
   - Histogramas de pasos  
   - Diagramas de dispersión (`scatter plots`) con línea de regresión  
   - Gráficos interactivos con Plotly

4. **Insights & Observaciones**  
   - Relaciones entre pasos y calorías  
   - Impacto del sueño y la frecuencia cardíaca  
   - Comparación entre tipos de ejercicio

---

## ▶️ Cómo correr el proyecto

1. Crear y activar un entorno virtual:

```bash
python -m venv venv
source venv/bin/activate  # o .\venv\Scripts\activate en Windows
