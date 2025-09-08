# ✅ Checklist Proyecto EDA – Campaña Marketing Banco

## 📂 Organización de carpetas
- ✅ /data → archivos originales (data raw)

- 🔲 archivos transformados.  (data processed)
- 🔲 /notebooks → todos los Jupyter Notebooks por fases.  
- 🔲 README.md → explicación del proyecto, pasos y resultados.  
- 🔲 Revisar los datos
- 🔲 Limpiar los datos
- 🔲 Crear visualizaciones

---

## 1️⃣ Notebook 01 – Carga y exploración inicial
- ✅ Importar librerías (pandas, numpy, matplotlib, seaborn).  
- ✅ Cargar `bank-additional.csv` y `customer-details.xlsx`.  
- ✅ Explorar dimensiones, columnas y tipos de datos.  
- ✅ Detectar valores nulos y duplicados.  
- ✅ Identificar posibles llaves de unión entre datasets (`id_` y `ID`).  

---

## 2️⃣ Notebook 02 – Limpieza y transformación de datos
- 🔲 Corregir tipos de datos (fechas, categóricas, numéricas).  
- 🔲 Manejar valores nulos (eliminación o imputación).  
- 🔲 Eliminar duplicados.  
- 🔲 Normalizar categorías (ej. “yes/no”, “1/0”).  
- 🔲 Crear nuevas columnas si es necesario (ej. año de cliente, ratio visitas/mes…).  
- 🔲 Guardar un dataset limpio en `/data/processed/`.  

---

## 3️⃣ Notebook 03 – Análisis descriptivo
- 🔲 Estadísticas descriptivas (media, mediana, desviación estándar).  
- 🔲 Distribución de variables numéricas (edad, ingresos, duración llamadas).  
- 🔲 Análisis de variables categóricas (ocupación, estado civil, educación).  
- 🔲 Estudio de correlaciones entre variables numéricas.  

---

## 4️⃣ Notebook 04 – Visualización de datos
- 🔲 Histogramas y distribuciones.  
- 🔲 Boxplots (ej. ingresos por estado civil, duración llamadas por edad).  
- 🔲 Gráficos de barras (ocupación, nivel educativo, respuesta campaña).  
- 🔲 Heatmap de correlaciones.  
- 🔲 Evolución temporal de contactos por año/mes.  

---

## 5️⃣ Notebook 05 – Insights y conclusiones
- 🔲 Resumir hallazgos más importantes.  
- 🔲 Identificar qué factores influyen en que un cliente acepte el producto.  
- 🔲 Relación entre datos demográficos (Excel) y respuesta a campañas (CSV).  
- 🔲 Detectar perfiles de clientes más propensos a aceptar campañas.  

---

## 6️⃣ Notebook 06 – Informe final
- 🔲 Redactar explicación clara de cada fase.  
- 🔲 Justificar las decisiones de limpieza y transformación.  
- 🔲 Incluir gráficos clave con interpretación.  
- 🔲 Redactar conclusiones y recomendaciones para el banco.  
- 🔲 Preparar contenido final para el **README.md**.  
