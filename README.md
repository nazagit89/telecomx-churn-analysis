### **TelecomX LATAM - Análisis de Churn 📊**

Análisis de la evasión de clientes (Churn) para la empresa Telecom X en la región de LATAM, desarrollado íntegramente en un notebook de Python.

### **Objetivos**

  - **Identificar factores** que explican la cancelación de servicios por parte de los clientes.
  - **Limpiar y preparar el dataset** para el análisis, tratando valores nulos y normalizando datos.
  - **Generar nuevas features** (variables) a partir de los datos existentes para enriquecer el análisis, como `monthlycharges`, `cuentas_diarias`, `is_monthly` y `has_fiber`.
  - **Crear visualizaciones** y un informe final con conclusiones y recomendaciones estratégicas.
  - Establecer una **base para futuros modelos predictivos** y estrategias de retención de clientes.

### **Estructura del Notebook**

El análisis está organizado secuencialmente dentro de este notebook en las siguientes secciones:

1.  **📌 Extracción:** Carga de los datos en formato JSON directamente desde un repositorio en GitHub.
2.  **🔧 Transformación:** Procesos de limpieza de datos que incluyen:
      * Normalización de nombres de columnas y datos de tipo texto.
      * Eliminación de registros duplicados.
      * Manejo de valores nulos.
      * El dataset limpio se guarda en formato CSV en la carpeta `data/`.
3.  **📊 Carga y Análisis:** Creación de nuevas variables (feature engineering) y análisis exploratorio de los datos (EDA). Se incluye un análisis descriptivo y la visualización de la distribución de Churn.
4.  **📄 Informe Final:** Resumen de las conclusiones, insights y recomendaciones derivadas del análisis.

### **Cómo Ejecutar**

1.  **Instalar librerías:** Asegúrate de tener instaladas las librerías necesarias. Puedes hacerlo con el siguiente comando en tu terminal o en una celda del notebook:
    ```bash
    pip install pandas seaborn matplotlib
    ```
2.  **Ejecutar las celdas:** Simplemente ejecuta todas las celdas del notebook en orden, desde el principio hasta el final.
