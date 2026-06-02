# Dashboard de Desempeño Comercial 2024–2025 – Sprint 10

Este repositorio contiene el proyecto de visualización desarrollado durante el Sprint 10 para **Andes Retail Group**, empresa de retail con operaciones en Perú, Chile y Colombia.

El dataset `Andes_Retail_Group_2024_2025` incluye transacciones de ventas de los años 2024–2025 en cuatro categorías de producto (Electrónica, Ropa, Deportes y Hogar), con información de clientes, geografía y métricas financieras como ingresos, costo y margen bruto.

---

## 📂 Contenido del repositorio

- `notebooks/S10_Proyecto_Desempeno_Comercial.ipynb`
  → Notebook de planificación y documentación del proyecto: KPIs seleccionados, diseño del dashboard, narrativa SCQA y reflexiones del análisis.

- `Proyecto 9_juan_castelblanco.twbx`
  → Dashboard con los KPIs, graficos, tablas y dashboard Overview y Detalle    

- `data/Andes_Retail_Group_2024_2025.xlsx`
  → Dataset transaccional con pedidos individuales: fecha, país, región, segmento de cliente, categoría de producto, ingresos, costo y unidades vendidas.

- `assets`
  → Carpeta con capturas de pantalla de los Dashboard Overview y Detalle, con KPIs, graficos y tablas  

---

## 📊 Dashboard en Tableau Public

Accede al dashboard interactivo publicado en Tableau Public:

🔗 [Ver Dashboard — Andes Retail Group](https://public.tableau.com/views/Proyecto9_Andesretail/DetalleF)

o:

Abrir carpeta assets para ver dashboards

El dashboard está compuesto por dos vistas:

- **Vista General (Overview):** evolución temporal de ingresos, comparación por país, segmento de cliente y categoría de producto, acompañada de 4 KPIs ejecutivos.
- **Vista Detalle:** análisis estacional, relación precio–volumen en el tiempo y tabla de métricas filtrable por año, categoría, región y estación.

---

## 🧠 Objetivos

### Objetivo del análisis

Transformar los datos transaccionales de Andes Retail Group en información visual, clara y accionable que permita a la dirección ejecutiva entender la evolución del desempeño comercial 2024–2025, identificar los segmentos y categorías de mayor rentabilidad, detectar patrones temporales y detectar oportunidades de mejora comercial por país y región.

### Objetivos de aprendizaje

- Conectar y validar un dataset transaccional en Tableau
- Preparar y transformar datos: tipos, columnas calculadas y estandarización
- Diseñar dashboards aplicando principios de jerarquía visual y diseño profesional
- Construir visualizaciones claras que respondan preguntas de negocio concretas
- Implementar filtros e interacciones para exploración dinámica
- Construir una narrativa estratégica usando el modelo SCQA
- Comunicar hallazgos de forma ejecutiva de manera asincrónica

---

## 🛠️ Herramientas utilizadas

- Tableau Public
- Visualizaciones nativas (barras, líneas, mapas, tarjetas KPI)
- Modelo de narrativa SQCA
- Jupyter Notebook o Colab

---

## 📊 Etapas del proyecto

| Paso | Descripción |
|------|-------------|
| 1 | Conexión y exploración del dataset en Tableau |
| 2 | Preparación de datos: tipos, formatos y columna `Nivel_Venta` |
| 3 | Diseño y planificación del dashboard (KPIs, gráficos, jerarquía y filtros) |
| 4 | Construcción de Vista General y Vista Detalle |
| 5 | Configuración de filtros e interacciones entre vistas |
| 6 | Narrativa SCQA y mensaje ejecutivo para stakeholders |

---

## 💡 Principales hallazgos

- El negocio opera con un **margen bruto del 35%** sobre $5,5M en ventas totales, lo que confirma rentabilidad sostenida
- **El verano concentra el mayor volumen de ventas**, generando una dependencia estacional que representa un riesgo comercial
- **El precio unitario se mantiene estable** durante el año; la caída en ciertos períodos se explica por reducción de volumen, no por guerra de precios
- **El segmento Premium y Perú** explican una proporción significativa del ingreso total, lo que expone al negocio ante variaciones en ese segmento o país
- **Otoño y Primavera** presentan potencial de crecimiento sin depender del pico de verano; son las estaciones con mayor oportunidad de activación comercial
- **El segmento Económico está subdesarrollado** y podría activarse en períodos de baja demanda sin canibalizar el segmento Premium

---

👤 Autor Juan Castelblanco - Analista de Datos - Sprint 8 - Análisis de Factores de Comportamiento de Clientes 2024 NovaRetail

📝 Licencia Este proyecto es de uso educativo y forma parte del programa de análisis de datos.

*Análisis basado en datos transaccionales 2024–2025 | Andes Retail Group – Data Analytics Team*  
*Fecha de análisis: Febrero 2026*
