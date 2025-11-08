# 🏥 Predicción de Coberturas Médicas Personalizadas

---

## 📋 Descripción
Este proyecto tiene como objetivo **predecir coberturas médicas personalizadas** para pacientes, optimizando la cobertura, costo y adecuación a sus necesidades médicas.  
Se utilizan **datos de historial médico, edad, enfermedades crónicas y frecuencia de consultas**, combinados con técnicas de **Machine Learning y Big Data**, para generar predicciones precisas y personalizadas.

El proyecto permite a las EPS y clínicas **mejorar la satisfacción del paciente**, optimizar la asignación de coberturas y aumentar la eficiencia operativa.

---

## 🏥 Industria
- **Sector Salud**: EPS, clínicas y aseguradoras.  
- **Aplicación**: personalización de coberturas médicas, reducción de costos y mejora en adherencia a tratamientos.

---

## 🛠 Tecnologías Utilizadas

- ✅ Python 3.x
- ✅ Pandas
- ✅ NumPy
- ✅ Scikit-learn
- ✅ PySpark
- ✅ SQL
- ✅ Plotly
- ✅ Matplotlib / Seaborn
- ✅ Google Colab / Jupyter Notebook
- ✅ ALS (Alternating Least Squares)
- ✅ KNN (K-Nearest Neighbors)
- ✅ Modelos basados en contenido

---

## 📊 Dataset 
- Historial médico de pacientes.  
- Edad y género.  
- Enfermedades crónicas y antecedentes médicos.  
- Frecuencia de consultas y tratamientos.  
- Coberturas médicas disponibles y características asociadas.  

> Nota: Los datos pueden ser simulados para pruebas o provistos por la institución según disponibilidad y normativas de privacidad.

---

## 📈 Métricas de Evaluación

| Métrica        | Qué muestra | Formato amigable |
|----------------|------------|----------------|
| **Precisión@3** | % de coberturas predichas correctamente entre las 3 principales | “66.67% de predicciones acertadas” |
| **Recall@3**   | % de coberturas relevantes recuperadas dentro de las 3 principales | “68.33% de coberturas relevantes predichas” |
| **RMSE**       | Error cuadrático medio de predicción de afinidad | “Error promedio de 0.02 en la predicción de afinidad” |


---

## 🌐 Visualizaciones

1. 📊 Distribución de pacientes por edad y enfermedades crónicas  
2. 🧩 Matriz de correlación entre variables médicas y coberturas elegidas  
3. 📈 Precisión@K y Recall@K por tipo de cobertura  
4. 🎯 Comparación de coberturas reales vs predichas  
5. 🏥 Número de coberturas predichas por frecuencia de consultas  
6. 🔢 Histograma de afinidad/puntuación de predicción  
7. 📦 Boxplots de coberturas predichas por segmento de pacientes  
8. 🌐 Mapa de cobertura médica por región   
9. 🔍 Análisis de pacientes con múltiples enfermedades crónicas  
10. ⚡ Métricas de desempeño del modelo ALS/KNN en distintos conjuntos de datos

<img width="691" height="471" alt="image" src="https://github.com/user-attachments/assets/32be9b39-e556-43bb-aae1-b2e2244be799" />

<img width="915" height="833" alt="image" src="https://github.com/user-attachments/assets/11c0db7e-e637-4454-8aba-21f2b95b85c8" />

<img width="846" height="471" alt="image" src="https://github.com/user-attachments/assets/4be05a69-c562-476e-8e55-2367e2d58a43" />

<img width="671" height="451" alt="image" src="https://github.com/user-attachments/assets/4233a50c-5adb-44d5-bcfe-edcd7eef5cc4" />

<img width="678" height="471" alt="image" src="https://github.com/user-attachments/assets/8543be95-2fa3-4166-a5ad-aec233226e8d" />

<img width="695" height="471" alt="image" src="https://github.com/user-attachments/assets/f0532ade-a72b-40f0-a815-a70c66cb19fc" />

<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/5e8a3b40-98c7-4d3c-8f7e-0bc169c12c4e" />

<img width="706" height="969" alt="image" src="https://github.com/user-attachments/assets/402f1d76-d38d-437d-9c34-2bfb5395ffc3" />

<img width="695" height="471" alt="image" src="https://github.com/user-attachments/assets/ab60f9aa-c79d-45b8-8f21-3b32eb7749cf" />

<img width="545" height="374" alt="image" src="https://github.com/user-attachments/assets/8c188927-31a7-415b-8fed-ab9e67e90b03" />

---

## 🚀 Resultados y Conclusiones Empresariales

Las predicciones generadas por el modelo permiten **personalizar coberturas médicas de manera precisa según el perfil de cada paciente**, considerando edad, historial médico, enfermedades crónicas y frecuencia de consultas. Las métricas obtenidas —**Precisión@3 de 83.87%, Recall@3 de 83.87% y RMSE de 0.09**— demuestran un modelo altamente confiable, capaz de identificar las coberturas más adecuadas dentro de las opciones disponibles, minimizando errores de predicción y aumentando la certeza en la toma de decisiones.

El análisis de las visualizaciones ofrece hallazgos clave:  
- La distribución de pacientes por edad y enfermedades crónicas permite identificar **segmentos prioritarios** para planes más completos.  
- La correlación entre frecuencia de consultas y tipo de cobertura revela oportunidades para **optimizar asignación de recursos y reducir sobrecostos**.  
- Comparaciones entre coberturas reales y predichas muestran que el modelo **acierta en la mayoría de los casos**, facilitando la planificación de la oferta y anticipando necesidades médicas.  
- El mapa de cobertura por departamentos permite visualizar geográficamente dónde se concentran las necesidades, ayudando a **optimizar rutas de atención y logística de servicios**.

**Impacto Empresarial:**  
La implementación de este sistema ofrece a las EPS y clínicas la capacidad de **optimizar tiempo y recursos**, reducir errores en asignación de coberturas y mejorar la satisfacción del paciente. Al anticipar necesidades de manera precisa, es posible **priorizar inversiones, planificar personal y distribuir servicios eficientemente**, lo que se traduce en un **incremento de ingresos y rentabilidad a mediano plazo**. Este enfoque permite a los empresarios tomar decisiones estratégicas basadas en datos confiables, asegurando que cada paciente reciba la cobertura adecuada, mientras se optimizan costos operativos y se minimizan pérdidas por planificación ineficiente.


---

## 📄 Licencia
Este proyecto se distribuye bajo la licencia **MIT**.

