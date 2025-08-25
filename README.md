# 📊 Proyecto de Regresión Lineal II  

## 📌 Descripción del Proyecto  
Este proyecto tiene como objetivo aplicar **modelos de regresión lineal** para analizar la relación entre variables transformadas y originales de un conjunto de datos.  
Se busca comprender cómo las transformaciones afectan las relaciones entre variables y evaluar si mejoran la capacidad predictiva del modelo.  

## 🔍 Datos Analizados  
- **Fuente de datos:** archivo `dataset.csv`.  
- **Tipo de datos incluidos:**  
  - Variables numéricas originales.  
  - Variables transformadas aplicando técnicas estadísticas.  
- **A qué se refieren los datos:** a registros con diferentes características numéricas.  
- **Quiénes están representados:** observaciones de un dataset utilizado con fines de análisis y aprendizaje de modelos de regresión.  

## 🛠️ Tecnologías Utilizadas  
- **Entorno de desarrollo:** Google Colab.  
- **Lenguaje de programación:** Python 3.  
- **Formatos de datos:** CSV, notebooks Jupyter (`.ipynb`).  

## 📚 Librerías Usadas  
- **Pandas:** manipulación y limpieza de datos.  
- **NumPy:** operaciones numéricas y matriciales.  
- **Matplotlib:** visualización de gráficos.  
- **Seaborn:** visualización estadística.  
- **Scikit-learn:** construcción y evaluación de modelos de Machine Learning.  

## 📊 Visualizaciones Realizadas  

### 📌 Dispersión entre las variables transformadas  
![Dispersión entre variables transformadas](/img/dispersion%20entre%20las%20variables%20transformadas.png)  

👉 Este gráfico muestra cómo se distribuyen las variables luego de aplicar transformaciones. Permite identificar patrones más claros y relaciones lineales mejor definidas.  

---

### 📌 Dispersión entre las variables originales  
![Dispersión entre variables](/img/dispersion%20entre%20las%20variables.png)  

👉 Este gráfico muestra la relación original entre las variables antes de aplicar transformaciones, lo que sirve como comparación para evaluar la mejora en el modelo.  

---

## ⚠️ Problemas Encontrados y Soluciones  
- **Multicolinealidad en variables:** detectada al analizar correlaciones, se mitigó aplicando transformaciones.  
- **Falta de linealidad en algunas relaciones:** se resolvió aplicando logaritmos y otras transformaciones estadísticas.  
- **Visualización poco clara en datos originales:** se mejoró al generar gráficos de dispersión de variables transformadas.  

## 📈 Resumen del Análisis  
- Se aplicaron transformaciones a las variables para mejorar la relación lineal.  
- Los gráficos de dispersión confirmaron que las variables transformadas presentaron patrones más consistentes.  
- El modelo de regresión lineal mejoró su rendimiento al trabajar con variables transformadas frente a las originales.  

## ✅ Conclusión  
El análisis demostró que las **transformaciones de variables** pueden mejorar significativamente la calidad de los modelos de regresión.  
La comparación entre variables originales y transformadas permitió evidenciar una relación más lineal y clara, lo que contribuye a obtener predicciones más precisas.  
