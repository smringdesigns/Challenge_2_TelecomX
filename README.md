# Challenge_2_TelecomX
En este desafío, el enfoque está en el proceso de extracción de datos desde la API, limpieza y transformación. Después de esta etapa de procesamiento, deberás organizar los datos de manera que permitan análisis más profundos y visualizaciones.

# Proyecto Telecom X

## El propósito del análisis realizado

El propósito de este análisis es extraer información útil a partir de los datos obtenidos en el Challenge 2, con el objetivo de comprender los factores que influyen en la cancelación de servicios por parte de los clientes.

A través del uso de Python y sus principales bibliotecas de análisis de datos, se recopilará, procesará y explorará la información para:

- Identificar patrones y comportamientos asociados a la evasión.

- Detectar variables clave que influyen en la pérdida de clientes.

- Generar insights que permitan al equipo de Data Science construir modelos predictivos más efectivos.

- Brindar soporte en la toma de decisiones estratégicas para reducir la tasa de cancelación y optimizar los procesos de retención de clientes.

Este análisis representa un paso fundamental para transformar los datos en valor y orientar a la empresa hacia una gestión más eficiente, basada en evidencia y orientada al cliente.

## La estructura del proyecto y organización de los archivos.

churn-clientes-telecomx/
│
├── 📁 data/
│   ├── raw/                # Datos originales sin procesar (CSV, Excel, etc.)
│   ├── processed/          # Datos limpios y transformados listos para análisis
│   └── external/           # Archivos de fuentes externas (demos, benchmarks)
│
├── 📁 notebooks/
│   ├── 01_exploracion.ipynb     # Análisis exploratorio inicial (EDA)
│   ├── 02_preprocesamiento.ipynb # Limpieza y transformación de datos
│   └── 03_modelado.ipynb        # Modelos predictivos (si aplica más adelante)
│
├── 📁 src/
│   ├── data_processing.py       # Funciones para cargar y limpiar datos
│   ├── eda.py                   # Funciones para análisis exploratorio
│   └── utils.py                 # Funciones auxiliares o reutilizables
│
├── 📁 reports/
│   └── figures/                 # Gráficos e imágenes generadas durante el análisis
│
├── 📁 models/                   # (Opcional) Modelos entrenados o serializados (.pkl, .joblib)
│
├── README.md                   # Documentación general del proyecto
├── requirements.txt            # Bibliotecas necesarias para reproducir el entorno
└── main.py  

## Ejemplos de gráficos e insights obtenidos.

## Instrucciones para ejecutar el notebook.
