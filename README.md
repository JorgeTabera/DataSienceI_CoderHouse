# Predicción de Diabetes Tipo 2  
**Proyecto Final - Coderhouse**  
**Alumno: JorgeTabera**

Hola! Este es mi proyecto final del curso de Data Science de Coderhouse.  
La idea fue aplicar todo lo aprendido para predecir si una persona tiene diabetes tipo 2, usando un dataset muy conocido: el **Pima Indians Diabetes Database**.  
Este conjunto de datos incluye información médica de mujeres de una comunidad indígena con alta prevalencia de esta enfermedad.

---

## ¿Qué quise lograr con este proyecto?

- Tratar correctamente los valores nulos del dataset.
- Visualizar cómo se relacionan las distintas variables entre sí.
- Detectar cuáles son las más importantes para predecir la diabetes.
- Entrenar un modelo de clasificación supervisado.
- Evaluar qué tan bien funciona el modelo con distintas métricas.

---

## ¿Qué pasos seguí?

1. Cargué el dataset y revisé que estuviera todo bien.
2. Reemplacé ceros en columnas médicas por valores nulos (`NaN`), porque en muchos casos no tenían sentido.
3. Imputé algunos valores usando el promedio de edad.
4. Hice gráficos para entender mejor el comportamiento de los datos.
5. Separé la variable objetivo (`Outcome`) de las variables predictoras.
6. Escalé los datos y los dividí en entrenamiento y prueba (80/20).
7. Entrené el modelo y generé predicciones.
8. Evalué el rendimiento con métricas como accuracy y matriz de confusión.

---

## Sobre el dataset

El **Pima Indians Diabetes Database** incluye variables como:

- `Pregnancies`: cantidad de embarazos  
- `Glucose`: nivel de glucosa en sangre  
- `BloodPressure`: presión arterial  
- `Insulin`, `BMI`, `Age`, entre otras  
- `Outcome`: 1 si tiene diabetes, 0 si no  

---

## Conclusión

Con este proyecto pude practicar todo el pipeline de trabajo de un modelo de Machine Learning: desde limpiar los datos hasta entrenar y evaluar un modelo.  

# DataScienceI_CoderHouse
