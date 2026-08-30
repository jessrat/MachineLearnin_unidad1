# MachineLearning_Unidad1

## Inteligencia Artificial y Aprendizaje Automático

**Alumno:** Jorge Salas  
**Semana:** 2  
**Institución:** IACC

---

## Descripción

Este repositorio contiene el desarrollo de la Actividad Evaluativa de la asignatura **Inteligencia Artificial y Aprendizaje Automático**, enfocada en la preparación, limpieza y análisis exploratorio de datos utilizando Python y Google Colab.

El trabajo se basa en el dataset de la empresa ficticia **EcoCartón Ltda.**, cuyo objetivo es analizar el comportamiento de la producción de envases de cartón a partir de información histórica relacionada con productos, costos, plantas productivas y turnos de trabajo.

---

## Objetivos del Proyecto

- Comprender la relación entre los datos y los procesos de Machine Learning.
- Identificar un enfoque de aprendizaje adecuado para el problema planteado.
- Aplicar técnicas de limpieza y preparación de datos.
- Realizar análisis exploratorio de datos (EDA).
- Crear nuevas variables que aporten valor al análisis.
- Utilizar herramientas de Python para automatizar la validación y control de calidad de los datos.

---

## Herramientas Utilizadas

- Python 3
- Google Colab
- Pandas
- Matplotlib

---

## Actividades Realizadas

### 1. Inspección Inicial del Dataset

- Revisión de estructura de datos.
- Identificación de columnas y tipos de datos.
- Detección de problemas de calidad.

### 2. Limpieza y Preparación de Datos

- Identificación de valores nulos.
- Revisión de registros duplicados.
- Corrección de formatos inconsistentes.
- Estandarización de nombres de productos.
- Normalización de textos en columnas de planta y turno.
- Validación de tipos de datos.

### 3. Análisis Exploratorio de Datos (EDA)

- Producción por año.
- Producción por mes.
- Producción por planta.
- Producción por producto.
- Estadísticas descriptivas.
- Detección de posibles anomalías.

### 4. Ingeniería de Características

Se creó la variable:

**Costo por Unidad**

```python
df["costo_por_unidad"] = (
    df["costo_usd"] / df["produccion_unidades"]
)
```
