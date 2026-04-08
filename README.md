# SISTEMA INTELIGENTE PARA PREDICCIÓN DE DIABETES - Proyecto elaborado por: The Two Powerpuff girls and Kevin

## Integrantes: Kevin Leonardo Baños Sánchez, Itzel Alejandra Lesama Aapolinar, Norma Inés Llergo Sánchez

<div align="center">

# SIPD

**Una solución tecnológica avanzada basada en Machine Learning para apoyar en la detección temprana del riesgo de diabetes.**

---
</div>
<p align="center">
  <img src="https://psiquiatria.com/galeria/ROBOT-HOSPITAL.jpg" alt="Texto alternativo" width="200">
</p>

## Sobre el Proyecto
Este sistema analiza variables clínicas críticas para identificar patrones de riesgo. Está diseñado para ser una herramienta de soporte que optimice los tiempos de respuesta en entornos de salud.

### Características Principales
* **Análisis Multivariable:** estudio de factores como edad, IMC, hipertensión, y nivel de hemoglobina A1c.
* **Modelos de Alta Precisión:** análisis con los modelos: regresión lineal, support vector machine, knn y xgboost; de los cuales tomamos la decisión de ensamblar (juntar los modelos para que sea más confiable nuestra predicción) el de regresión logística, support vector machine y xgboost.
* **Visualización de Datos:** interpretación descriptiva de resultados.

## Instalación y Uso
```bash
git clone [https://github.com/InesLlergo/Diabetes-prediction.git]

pip install -r requirements.txt
```
---

# El problema: Diabetes, una enfermedad silenciosa

---
### Un reto sanitario global
La diabetes afecta a millones de personas en todo el mundo, representando uno de los principales desafíos de salud pública.

### Diagnóstico tardío
En México desde el 2020, se estableció una cantidad de más de 150 000 fallecidos a causa de la diabetes, teniendo una tasa del 11.95 personas por cada 10 000 habitantes. Las defunciones por diabetes, registradas en 2020, se distribuyen en todos los grupos de edad aunque
se presenta un incremento conforme avanza la edad, afectando en mayor medida a las personas de 65 años y más (INEGI, 2021). 

### La detección temprana es clave
Dada la crisis con la conocida enfermedad COVID-19, se presentó la oportunidad de estudiar a pacientes con diabetes. 

En la página del gobierno mexicano se muestra claramente "una persona con diabetes descontrolada y que se contagia de SARS-CoV-2 tiene más probabilidad de requerir hospitalización, intubación, cuidados intensivos o incluso se encontraría en riesgo de fallecer. La tasa de mortalidad por COVID-19 en personas con diabetes es de siete por ciento y puede aumentar de acuerdo con la cantidad de comorbilidades que tenga el o la paciente.
El especialista destacó que la diabetes es una enfermedad silenciosa en su primera fase. 

Los síntomas se presentan cuando la cantidad de glucosa en sangre es superior a 126/mg/dl en ayunas, y mayor a 200 mg/dl dos horas después de ingerir alimentos.  La falta de control puede provocar que la enfermedad avance y produzca falla en los sistemas nervioso, ocular, cardíaco, renal y cerebral, principalmente" (Secretaría de Salud Gob.MX, 2020).

---

# La solución: Predicción Inteligente

---
### Machine Learning
Algoritmos avanzados que aprenden de datos médicos reales.

### Apoyo diagnóstico
Herramienta para ayudar a profesionales sanitarios en la toma de decisiones.

### Prevención activa
Identificación temprana del riesgo antes de que aparezcan síntomas

---
# Metodología del sistema

