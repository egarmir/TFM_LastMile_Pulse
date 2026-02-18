# 📦 TFM: LastMilePulse - Gestión de Entregas B2C

Este repositorio contiene el desarrollo íntegro del modelo predictivo para la optimización de última milla.

## 🚀 Instrucciones de Visualización
Debido a la complejidad de los metadatos del notebook, la vista previa de GitHub puede mostrar el código en formato JSON. **Para ver el proyecto correctamente (gráficas, explicaciones y resultados), utilice el siguiente enlace directo:**

👉 [**ABRIR PROYECTO EN GOOGLE COLAB**](https://colab.research.google.com/github/egarmir/TFM_LastMile_Pulse/blob/main/Modelado_LastMile_B2C)

## 📊 Origen de los Datos (Dataset LaDe)
El motor de este proyecto se basa en el dataset **LaDe (Last-mile Delivery Dataset)**, un benchmark de acceso abierto proporcionado por investigadores de **Baidu**.

* **Descripción:** Es el primer dataset de última milla a gran escala que incluye secuencias de eventos reales, coordenadas GPS y tiempos de entrega.
* **Fuente Original:** [GitHub - wenhaomin/LaDe](https://github.com/wenhaomin/LaDe)
* **Referencia Académica:** *LaDe: Last-mile Delivery Dataset from Baidu.*

---

## 🛠️ Funcionalidades del Proyecto
1. **Modelado Predictivo:** Pipeline dual que clasifica el riesgo de retraso y estima el tiempo exacto de latencia en minutos.
2. **Dashboard de Operaciones:** - **Heatmaps:** Visualización de zonas críticas de congestión por hora.
   - **Alertas Tempranas:** Identificación automática de los 10 pedidos con mayor riesgo de incumplimiento de SLA.
3. **Interfaz Gradio:** Herramienta diseñada para gestión de tráfico logístico.

📂 Estructura del Repositorio
* `/Notebooks`: Código fuente en formato `.ipynb` (limpio de resultados para asegurar compatibilidad).
* `/Data`: Archivo `ejemplos_LastMilePulse.csv` para probar la herramienta de forma inmediata.
* `LICENSE`: Licencia MIT.

