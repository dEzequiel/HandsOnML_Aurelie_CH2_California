# California Housing – Data Preparation & Feature Engineering  
Este proyecto forma parte de mi estudio del libro  
**"Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" de Aurélien Géron**.

El objetivo del notebook es reproducir y comprender los pasos del capítulo inicial de Machine Learning, centrándose en:

- Carga y exploración del *California Housing Dataset*
- División en conjuntos de entrenamiento y test (incluyendo *stratified sampling*)
- Limpieza de datos y manejo de valores faltantes
- Ingeniería de características y construcción de pipelines
- Transformación automática de atributos numéricos y categóricos
- Creación de atributos combinados personalizados usando `CombinedAttributesAdder`
- Preparación final de la matriz de características para modelos de Machine Learning

---

---

## 📑 Contenido del notebook
1. **Carga de datos**  
   Descarga y muestra del dataset California Housing.

2. **Análisis exploratorio básico (EDA)**  
   Estadísticas, histogramas y detección de valores atípicos.

3. **División del dataset**  
   Uso de:
   - `train_test_split`
   - Muestreo estratificado basado en los ingresos medianos.

4. **Preparación de los datos**  
   Uso de `Pipeline` y `ColumnTransformer`:
   - Imputación de valores faltantes
   - Escalado estandarizado
   - One-Hot Encoding

5. **Feature Engineering**  

6. **Transformación final**  

---

