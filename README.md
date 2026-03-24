📊 EverPeak Retail Analysis – Sprint 6
Este repositorio contiene el flujo de trabajo completo para el análisis de calidad y limpieza del caso EverPeak–SilverBasket. El proyecto se centra en transformar datos crudos y "sucios" en un dataset confiable para la toma de decisiones estratégicas.

🎯 Objetivo del Proyecto
El dataset everpeak_retail simula un entorno real de retail con 2,000 órdenes que presentan:

Problemas de Calidad: Valores faltantes, centinelas y duplicados.

Anomalías: Outliers estadísticos y lógicos.

Meta: Construir un pipeline de limpieza reproducible y generar insights accionables para el equipo de Estrategia e Integración.

🛠️ Stack Tecnológico
Lenguaje: Python 3.x

Librerías principales: Pandas, NumPy (limpieza), Matplotlib, Seaborn (visualización).

Entorno: Jupyter Notebooks / Google Colab.

📂 Estructura del Repositorio
Bash
├── data/                   # Dataset original y procesado
├── notebooks/
│   └── everpeak_analysis.ipynb  # Notebook principal de análisis
└── README.md               # Documentación del proyecto
🚀 Cómo Ejecutar el Análisis
Opción 1: Google Colab (Recomendado)
Puedes ejecutar el análisis directamente en la nube sin configurar un entorno local:

Opción 2: Entorno Local
Clona este repositorio:

Bash
git clone https://github.com/tu-usuario/nombre-repo.git
Instala las dependencias:

Bash
pip install pandas numpy matplotlib seaborn
Ejecuta el archivo en notebooks/everpeak_analysis.ipynb.

🧠 Metodología Aplicada
Exploración Inicial (EDA): Identificación de tipos de datos y estadísticas descriptivas.

Limpieza de Datos: Tratamiento de valores nulos y estandarización de columnas.

Análisis de Outliers: Uso de métodos estadísticos (IQR/Z-score) para detectar valores atípicos.

Visualización: Distribución de ventas, comportamiento de clientes y frecuencias.
