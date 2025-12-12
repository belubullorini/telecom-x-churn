📊 Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del desafío Telecom X del programa ONE Oracle Next Education.
El objetivo principal es analizar el comportamiento de los clientes y detectar patrones asociados a la evasión (churn). El análisis incluye extracción de datos desde una API, proceso ETL, limpieza, análisis exploratorio (EDA), visualizaciones y generación de insights.

🎯 Propósito del análisis
El propósito de este proyecto es comprender qué factores influyen en que un cliente permanezca o abandone el servicio.
A través del análisis se busca:

* Detectar las variables más asociadas a la evasión.
* Visualizar comportamientos y tendencias clave.
* Generar insights que apoyen decisiones estratégicas.
* Proponer recomendaciones basadas en datos para reducir el churn.

📁 Estructura del Proyecto
telecom-x-churn/
│
├── data/  
│   └── telecom.json              # Datos obtenidos desde la API
│
├── images/                       # Gráficos generados durante el EDA
│   ├── evasion.png
│   ├── genero_evasion.png
│   ├── contrato_evasion.png
│   ├── metodopago_evasion.png
│   ├── serviciointernet_evasion.png
│   ├── antiguedad_evasion.png
│   ├── pagototal_evasion.png
│   ├── pago_mensual.png
│   ├── correlacion_numericas.png
│   ├── correlacion_servicios.png
│   └── relacion_diario_evasion.png
│
├── notebooks/
│   └── telecom_x_churn.ipynb     # Notebook principal con extracción, ETL y EDA
│
└── README.md                     # Documentación del proyecto

📌 Ejemplos de gráficos e insights obtenidos
✔️ Distribución general de Evasión
<img src="images/evasion.png" width="600">
✔️ Evasión por tipo de contrato

El contrato mes a mes muestra el mayor churn.
<img src="images/contrato_evasion.png" width="600">

✔️ Método de pago

El cheque electrónico tiene la tasa de abandono más alta.
<img src="images/metodopago_evasion.png" width="600">

✔️ Fibra óptica

Los clientes con fibra presentan mayor evasión que DSL.
<img src="images/serviciointernet_evasion.png" width="600">

✔️ Antigüedad

Los clientes que abandonan suelen llevar poco tiempo.
<img src="images/antiguedad_evasion.png" width="600">

✔️ Correlación entre variables numéricas
<img src="images/correlacion_numericas.png" width="600">
🧠 Principales descubrimientos

(Estos son los que ya escribiste, van acá tal cual los tenés).
✔ Tipo de contrato → predictor más fuerte
✔ Método de pago → cheque electrónico = alto riesgo
✔ Fibra óptica → mayores tasas de evasión
✔ Clientes nuevos → mayor abandono
✔ Género → no relevante

🚀 Instrucciones para ejecutar el proyecto

Clonar el repositorio:

git clone https://github.com/belubullorini/telecom-x-churn.git


Instalar las dependencias necesarias (Python 3.10+):

pip install pandas matplotlib seaborn requests


Ejecutar el notebook en Google Colab o Jupyter Notebook.

Si usás Colab:

Subir el archivo .ipynb

Asegurarte de tener internet habilitado para consultar la API

Correr el flujo completo:

Extracción de datos desde API

Limpieza

Transformación

EDA

Visualizaciones

Conclusiones

📝 Recomendaciones finales

(Agregás acá las recomendaciones que ya escribiste.)
✔ Incentivar contratos largos
✔ Promover pagos automáticos
✔ Revisar servicio de fibra
✔ Programa de retención primeros 3 meses
✔ Segmentar campañas según riesgo

🙌 Autoría

Proyecto realizado por Belu Bullorini, en el marco del programa ONE Oracle Next Education.
