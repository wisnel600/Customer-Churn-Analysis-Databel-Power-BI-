# Customer-Churn-Analysis-Databel-Power-BI-
Análisis del abandono de clientes (Churn)

📌 Presentación del proyecto

Para las empresas que ofrecen servicios por suscripción, la reducción del tasa de abandono de clientes (churn) es una prioridad estratégica clave. Comprender por qué los clientes dejan un servicio es fundamental para mejorar la retención y el desempeño global de la empresa.

Este proyecto, desarrollado con Power BI, analiza un conjunto de datos de una empresa ficticia de telecomunicaciones llamada Databel. El objetivo es estudiar el comportamiento de los clientes, identificar los factores asociados al abandono y transformar los resultados en insights accionables para la toma de decisiones.

El análisis del churn no se limita únicamente al cálculo de una tasa, sino que busca explicar por qué los clientes se dan de baja y qué acciones puede implementar la empresa para reducir este fenómeno.

🎯 Objetivos

Calcular y analizar la tasa de abandono de clientes

Identificar segmentos de clientes con alto riesgo de churn

Analizar el impacto del tipo de contrato, el consumo de datos y las características demográficas

Diseñar dashboards interactivos que faciliten la toma de decisiones

🛠 Herramientas y tecnologías

Power BI

DAX (Data Analysis Expressions)

Modelado de datos

Visualización y storytelling analítico

🧭 Estructura del análisis
1️⃣ Análisis exploratorio de datos

Exploración del conjunto de datos de Databel y creación de las primeras medidas (número de clientes, clientes dados de baja y tasa de churn) para comprender las principales tendencias del abandono.

2️⃣ Análisis de los patrones de abandono

Profundización del análisis mediante segmentaciones clave:

Tipo de contrato (anual vs mensual)

Grupos demográficos (edad)

Consumo promedio de datos móviles

Cargos adicionales e interacciones con el servicio al cliente

3️⃣ Visualización y storytelling

Creación de páginas tipo dashboard, organizadas de forma narrativa, para presentar los resultados de manera clara, sintética y orientada a la toma de decisiones.

📊 Principales medidas y columnas DAX
Medidas clave

Number of Customers

Number of Churned Customers

Churn Rate

Avg Customer Service Calls

Avg Extra Data Charges

Avg Extra International Charges

Columnas calculadas

Churned (cliente dado de baja o no)

Contract Category (Anual vs Mensual)

Demographics (Senior, Menor de 30, Otros)

Grouped Consumption (consumo de datos agrupado)

Las fórmulas DAX completas están documentadas en el directorio dax/.

📈 Principales insights

Los contratos mensuales presentan una tasa de churn significativamente más alta que los contratos anuales.

Los clientes con alto consumo de datos tienen mayor probabilidad de abandonar el servicio.

Los clientes con planes ilimitados muestran un mayor riesgo de churn.

Algunos grupos demográficos son más sensibles al abandono que otros.
