# 🚀 Challenge ONE | Parte 2: Modelo Predictivo de Churn para Telecom X

![Estado del Proyecto](https://img.shields.io/badge/Estado-Finalizado-success)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Librería-Scikit--Learn-F7931E?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Librería-Pandas-150458.svg)
![Entorno](https://img.shields.io/badge/Entorno-Google_Colab-F9AB00?logo=googlecolab)

---

### **🔗 Un Proyecto Integral en Dos Fases: Del ETL al Machine Learning**

Este repositorio representa la **Parte 2** y la culminación de un proyecto de Data Science de extremo a extremo. El trabajo se divide en dos fases, demostrando un flujo de trabajo completo desde la obtención de datos hasta la predicción.

*   **📈 Parte 1: ETL y Análisis Exploratorio (EDA)**
    *   En la fase inicial, se construyó un pipeline de **Extracción, Transformación y Carga (ETL)** para procesar datos crudos desde una API JSON. El resultado fue un dataset limpio y estructurado, junto con un análisis exploratorio que identificó las causas raíz del Churn.
    *   ➡️ **[Ver el Repositorio de la Parte 1: ETL aquí]([https://github.com/roger55rebaza/challenge-etl-churn-telecomx])**

*   **🤖 Parte 2: Modelado Predictivo (Este Repositorio)**
    *   Utilizando el dataset limpio de la Parte 1, esta fase se enfoca en el **Machine Learning**. Se desarrolla, entrena y evalúa un modelo predictivo capaz de **anticipar** qué clientes tienen la mayor probabilidad de cancelar su servicio, permitiendo a la empresa actuar de forma proactiva.

---

### **🎯 El Desafío: Predecir el Futuro para Retener Clientes**

Tras un análisis inicial que reveló una **alarmante tasa de Churn del 26.58%**, mi rol evolucionó a Científico de Datos Junior. La misión: construir una herramienta predictiva que responda a la pregunta clave: ***"¿Qué clientes cancelarán a continuación?"***

El objetivo es pasar de una estrategia reactiva a una **estrategia de retención inteligente**, optimizando los recursos y enfocando los esfuerzos en los clientes con mayor riesgo.

---

### **⚙️ El Pipeline de Machine Learning: El Camino Hacia la Predicción**

Se implementó un pipeline de Machine Learning robusto y reproducible, siguiendo las mejores prácticas de la industria.

#### **✅ Fase 1: Preparación de Datos (Preprocessing)**
*   **[✔] Carga de Datos Limpios:** Se partió del dataset de **7,032 clientes** generado en la fase de ETL.
*   **[✔] Codificación (Encoding):** Se transformaron 17 variables categóricas a un formato 100% numérico usando One-Hot Encoding (`pd.get_dummies`).
*   **[✔] Estandarización de Datos:** Se escalaron todas las variables con `StandardScaler` para asegurar un entrenamiento justo y eficiente.

#### **✅ Fase 2: Modelado y Validación**
*   **[✔] Separación de Datos (Train/Test Split):** Se dividieron los datos en 70% para entrenamiento y 30% para una evaluación honesta del modelo.
*   **[✔] Entrenamiento de Modelos:** Se entrenaron dos algoritmos: `Regresión Logística` (lineal) y `Árbol de Decisión` (basado en reglas).
*   **[✔] Selección del Modelo Campeón:** La **Regresión Logística** fue seleccionada por su rendimiento superior en todas las métricas, especialmente en el **Recall**, crucial para el negocio.

---

### **🏆 El Resultado: Un Modelo Predictivo Confiable**

El modelo final de **Regresión Logística** demostró ser una herramienta de alta precisión, capaz de predecir el comportamiento de los clientes con los siguientes resultados en datos nunca antes vistos:

| Métrica Clave (para "Sí Churn") | 🏆 Rendimiento del Modelo | Descripción de Negocio                                       |
| :------------------------------ | :-----------------------: | :----------------------------------------------------------- |
| **🎯 Exactitud General**        |          **80%**          | El modelo acierta en 8 de cada 10 predicciones en general.   |
| **🎣 Recall (Sensibilidad)**    |          **57%**          | **Identifica a casi 6 de cada 10 clientes que realmente se van.** |
| **🔍 Precisión**                |          **64%**          | Cuando predice un Churn, acierta el 64% de las veces.     |
| **⚖️ F1-Score (Balance)**        |          **0.60**         | Un balance sólido entre identificar clientes en riesgo y no cometer "falsas alarmas". |

---

### **💡 Conclusión Estratégica: Factores Clave y Acciones Recomendadas**

El modelo no solo predice, sino que también nos dice **por qué**. Los factores más influyentes en la evasión de clientes son:
1.  **Antigüedad del Cliente (Tenure):** El factor de **protección** más fuerte. La lealtad se construye en los primeros meses.
2.  **Tipo de Contrato:** Contratos a largo plazo reducen drásticamente el riesgo.
3.  **Servicio de Internet:** La **Fibra Óptica** es el mayor impulsor de riesgo.

Basado en estos hallazgos, se recomienda a Telecom X enfocar sus estrategias de retención en **mejorar la experiencia de onboarding de los clientes de Fibra Óptica** y en **incentivar la migración a contratos de largo plazo**.

---

### **💻 Cómo Replicar este Análisis**

1.  Asegúrate de tener el archivo `telecom_x_datos_limpios.csv` de la Parte 1 de este proyecto.
2.  Abre el notebook `Challenge_ML_TelecomX_Solucion_Roger.ipynb` en [Google Colaboratory](https://colab.research.google.com/).
3.  Sube el archivo CSV al entorno de Colab.
4.  Ve a `Entorno de ejecución` > `Ejecutar todo`.

---

### **👨‍💻 Desarrollado por**

**[Roger Rodriguez Rebaza]**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rogerr3/)
