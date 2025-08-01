# Commercial Sensitivity & Store Segmentation

## A case study using Rossmann data

This project analyzes how stores respond to key commercial events, classifies them by sensitivity, and generates strategic recommendations for campaigns and operations.


### Sensibilidad Comercial y Segmentación de Tiendas  
**Un caso con datos Rossmann**  

---

Objetivo del proyecto  
Analizar cómo responden las tiendas a eventos comerciales clave (Navidad, Buen Fin, Día de la Madre, etc.), segmentarlas según sensibilidad dominante y generar recomendaciones estratégicas para campañas, surtido y decisiones operativas.

---

### Flujo de análisis

### 1. Preparación y limpieza  
- Carga de datasets  
- Validación de nulos y duplicados  
- Conversión de fechas y creación de variables temporales  

### 2. KPIs comerciales  
- Ticket promedio (`sales / customers`)  
- Tasa de conversión (`sales / customers`)  
- Segmentación por tipo de tienda, día de la semana y promociones  

### 3. Sensibilidad por evento  
- Cálculo de delta por tienda y evento  
- Clasificación: Alta, Baja, Negativa/Indiferente  
- Visualización ejecutiva por evento  

### 4. Recomendaciones por tienda  
- Sensibilidad dominante  
- Eventos efectivos  
- Recomendación estratégica:  
  - 🔵 Priorizar campañas agresivas  
  - 🟧 Aplicar campañas moderadas  
  - 🟩 Revisar estrategia o excluir campañas  

---

## 📈 Resultados clave

- **Navidad** y **Buen Fin** son los eventos con mayor impacto comercial.  
- La mayoría de tiendas muestran sensibilidad **Baja**, lo que sugiere segmentar campañas.  
- Se identificaron tiendas con sensibilidad **100% Alta**, ideales para pruebas piloto y benchmarking.  
- El análisis permite **optimizar inversión** y **focalizar esfuerzos** donde hay mayor retorno.

---

🗂️ Estructura del notebook

```text
├── 01_Carga_y_Limpieza.ipynb
├── 02_KPIs_Comerciales.ipynb
├── 03_Sensibilidad_Eventos.ipynb
├── 04_Recomendaciones_Tiendas.ipynb