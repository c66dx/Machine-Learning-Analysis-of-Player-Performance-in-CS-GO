# 🎮 Machine Learning Analysis of Player Performance in CS:GO

Este proyecto aplica técnicas de **Machine Learning** al videojuego **Counter-Strike: Global Offensive (CS:GO)** con el objetivo de analizar, modelar y predecir el rendimiento de los jugadores en partidas competitivas.

---

## 📌 Objetivos del Proyecto
- Realizar un **análisis exploratorio de datos (EDA)** para comprender las variables más relevantes en el rendimiento.
- Implementar **modelos supervisados** de regresión y clasificación para predecir resultados de los jugadores y equipos.
- Aplicar **clustering (KMeans)** para segmentar jugadores según estilos y desempeño.
- Detectar **comportamientos atípicos** en las partidas.
- Generar un **análisis estratégico** del rendimiento competitivo en CS:GO.

---

## 🛠️ Tecnologías y Librerías Utilizadas
- **Lenguaje**: Python 3  
- **Entorno**: Jupyter Notebook  
- **Librerías principales**:  
  - `pandas`, `numpy` → Manejo y procesamiento de datos  
  - `matplotlib`, `seaborn` → Visualización  
  - `scikit-learn` → Modelos de ML (regresión, clasificación, clustering)  
  - `scipy` → Análisis estadístico  

---

## 📊 Metodología
1. **Preprocesamiento de datos**  
   - Limpieza, normalización y codificación de variables.  

2. **Análisis exploratorio (EDA)**  
   - Distribuciones, correlaciones y patrones de rendimiento.  

3. **Modelamiento supervisado**  
   - Regresión para métricas continuas (ej: kills, rating).  
   - Clasificación para variables categóricas (ej: victoria/derrota).  

4. **Clustering de jugadores (KMeans)**  
   - Segmentación según estilos de juego y estadísticas.  

5. **Detección de outliers**  
   - Identificación de partidas o jugadores con comportamientos atípicos.  

---

## 📂 Estructura del Proyecto

📁 csgo-ml-analysis
│── CSGO.ipynb # Notebook principal con el análisis completo
│── data/ # Carpeta con dataset(s) utilizados
│── README.md # Este archivo


---

## 🚀 Cómo Ejecutar
1. Clonar el repositorio o descargar el proyecto.  
2. Instalar dependencias necesarias:  
   ```bash
   pip install -r requirements.txt
3. Abrir el notebook: jupyter notebook CSGO.ipynb

## 📈 Resultados Esperados

- Identificación de las variables que más influyen en el rendimiento.
- Modelos predictivos capaces de estimar desempeño individual y colectivo.
- Segmentación de jugadores por estilos de juego.
- Insights estratégicos aplicables a equipos competitivos.

## 👤 Autores

Proyecto desarrollado por @c66dx y @Pillaulo como parte de un estudio de Machine Learning aplicado a eSports.
