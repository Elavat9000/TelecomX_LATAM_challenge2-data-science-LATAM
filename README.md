# TelecomX_LATAM_challenge2-data-science-LATAM
challenge2-data-science-LATAM


# 📊 Análisis de Cancelaciones de Clientes - Telecom

Este es un proyecto personal de análisis de datos realizado para identificar las principales causas de cancelación de clientes en una empresa de telecomunicaciones. Se trabajó con un conjunto de datos público que simula la información de clientes, servicios contratados, métodos de pago y comportamiento de permanencia.

## 📌 Objetivo

A partir de variables clave como tipo de contrato, servicios contratados, tipo de internet, método de pago y tiempo de permanencia, se buscó detectar los factores más influyentes en la decisión de cancelar el servicio y proponer recomendaciones para reducir la tasa de cancelación.

---

## 🧪 Análisis Incluido

✅ Distribución de cancelaciones totales  
✅ Cancelaciones por género  
✅ Cancelaciones según tipo de internet  
✅ Cancelaciones por tipo de contrato  
✅ Cancelaciones por método de pago  
✅ Análisis de tiempo de permanencia (tenure)  
✅ Relación entre cantidad de servicios contratados y cancelación  
✅ Relación entre tipo de internet y contrato

### 📈 Gráficos

- Distribución de cancelaciones
- Cancelaciones por tipo de internet
- Cancelaciones por contrato
- Cancelaciones por método de pago
- Histograma de tiempo de permanencia
- Relación entre servicios contratados y cancelación

---

## 📂 Estructura del Proyecto
```plaintext
/
├──/data/
    └── TelecomX_Data.json
├── TelecomX_LATAM.ipynb          # 📓 Notebook de Jupyter donde se realizo el análisis, gráficas y conclusiones.
├── README.md                     # 📖 Explicación del proyecto, contexto, objetivos, metodología, resultados clave.
└── Imagenes/                     # 📂 Carpeta con todas las gráficas y visualizaciones exportadas desde el notebook.
    ├── Contract (1).png
    ├── InternetService.png
    ├── cancelacion_porDias_gastos.png
    ├── cancelacion_por_cargos.png
    ├── cancelacion_por_meses (1).png
    ├── cancelacion_por_meses.png
    ├── cancelaciones_por_metodo.png
    ├── distribucion_cancelacion.png
    ├── gender.png
    ├── relacion_internet_contract_churn (1).png
    └── servicios_contratados_cancelados.png

```
---

## 📈 Insights Obtenidos

🔍 1. Percepción de Precio Alto vs. Competencia  
🔍 2. Contrato "Mes a Mes" = Mayor Predictor de Churn
🔍 3. "Electronic Check": Método de Pago Más Riesgoso  
🔍 4. Primeros 60 Días: Ventana Crítica  
🔍 5. Servicios Complementarios: Arma de Doble Filo

---


## 🧾 Conclusión del Estudio

Con base en los datos analizados se concluye que:

- Los contratos mes a mes, especialmente con Fibra Óptica, requieren estrategias de fidelización más sólidas.
- Se deben crear campañas de retención para clientes en sus primeros 2 meses.
- Es recomendable incentivar métodos de pago automáticos y paquetes de servicios múltiples.

---

## 🚀 Cómo Ejecutar el Notebook en Google Colab

Puedes abrir y ejecutar el análisis fácilmente desde Google Colab:

👉 [Abrir TelecomX_LATAM.ipynb](https://github.com/Elavat9000/TelecomX_LATAM_challenge2-data-science-LATAM/blob/main/TelecomX_LATAM.ipynb)

**Pasos:**
1. Haz clic en el enlace de arriba.
2. Haz clic en "Open in colab"
3. Inicia sesión con tu cuenta de Google (si no lo has hecho).
4. Ejecuta las celdas del notebook (una por una o con “Ejecutar todo Ctrl+F9”).
5. El dataset se carga desde una URL pública en GitHub, por lo que no necesitas subir nada.

---
## 🛠️ Tecnologías Usadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Markdown

---

**📌 Autor:** Francisco Cervantes  
**📅 Fecha:** Junio 2025  
