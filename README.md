# Clasificacion-Peliculas

## 👥 Integrantes
- **Licarayen Cona**  
- **Mary Huaiquin**  
- **Luis Veliz**

## 🧩 Descripción del Proyecto
Este notebook tiene como objetivo desarrollar un modelo de aprendizaje automático orientado al análisis e interpretación de datos, incorporando técnicas de explicabilidad con la librería **LIME** y manejo de texto con **Unidecode**.

A lo largo del notebook se implementan las etapas clásicas de un proyecto de Machine Learning, desde la preparación de los datos hasta la evaluación e interpretación de los resultados.

## 🧠 Objetivos
1. Preprocesar los datos eliminando caracteres especiales y normalizando texto.  
2. Entrenar un modelo de clasificación supervisada.  
3. Evaluar el rendimiento del modelo con métricas cuantitativas.  
4. Aplicar **LIME** para interpretar las decisiones del modelo y entender la relevancia de las variables en las predicciones.  


## 🛠️ Requerimientos

Instalar las librerías necesarias ejecutando:

```bash
pip install unidecode lime scikit-learn matplotlib numpy pandas
```

| Sección                             | Descripción                                                                                    |
| ----------------------------------- | ---------------------------------------------------------------------------------------------- |
| **1. Instalación de librerías**     | Instalación de dependencias requeridas (`unidecode`, `lime`, etc.).                            |
| **2. Carga y exploración de datos** | Lectura del dataset y análisis exploratorio inicial.                                           |
| **3. Limpieza y preprocesamiento**  | Normalización de texto, eliminación de caracteres y preparación de variables.                  |
| **4. Entrenamiento del modelo**     | Entrenamiento de un modelo supervisado (por ejemplo, regresión logística o árbol de decisión). |
| **5. Evaluación del modelo**        | Cálculo de métricas de desempeño como exactitud, recall o F1-score.                            |
| **6. Interpretabilidad con LIME**   | Visualización y análisis de la importancia de variables en predicciones individuales.          |

## 📊 Resultados Esperados

El notebook busca entregar una comprensión clara del rendimiento del modelo y su comportamiento ante distintos tipos de entradas, potenciando la transparencia en los resultados a través de técnicas de interpretabilidad

## 📁 Estructura del Repositorio
```bash
├── M9C2.ipynb        # Notebook principal con el desarrollo del proyecto
├── README.md         # Descripción general del proyecto
└── data/             # (Opcional) Conjunto de datos utilizado
```
## 📚 Referencias

LIME documentation

Unidecode documentation

Scikit-learn
