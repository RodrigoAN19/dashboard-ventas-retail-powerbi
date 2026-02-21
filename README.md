# 📊 Dashboard de Ventas Retail con Excel, SQL Server y Power BI

## 📌 Descripción
Análisis y visualización de ventas retail usando Excel, SQL Server y Power BI.
Dataset: Superstore Sales (9,994 pedidos | 4 regiones | 3 categorías)
Fuente: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## 🎯 Preguntas de Negocio Respondidas
- ¿Qué región genera más ventas e ingresos?
- ¿Qué categoría de producto es más rentable?
- ¿Cómo evolucionaron las ventas año a año?
- ¿Qué segmento de cliente compra más?

## 🛠️ Herramientas Utilizadas
- Excel — limpieza y preparación de datos
- SQL Server — carga y análisis con GROUP BY, SUM, AVG
- Power BI — dashboard interactivo con KPIs y filtros

## 📈 Hallazgos Principales
- **West** es la región más rentable con $725,457 en ventas
- **Technology** genera la mayor ganancia con $145,046
- Las ventas crecieron significativamente entre 2015 y 2016
- **Consumer** es el segmento con mayor volumen de compras

## 📊 Dashboard Interactivo
![Dashboard](imagenes/dashboard_superstore.png)

## 📂 Estructura del Proyecto
```
├── data/        # Dataset limpio en CSV
├── dashboard/   # Archivo Power BI (.pbix)
├── imagenes/    # Captura del dashboard
└── README.md
```

## 📥 Cómo Reproducir el Análisis
1. Descarga el dataset desde Kaggle (link arriba)
2. Limpia el Excel eliminando columnas innecesarias
3. Importa el CSV a SQL Server
4. Abre el archivo .pbix en Power BI Desktop
5. Actualiza la conexión a tu servidor SQL

## 👤 Autor
**Rodrigo Antonio Aniceto Nuñez**
Analista de Datos | Lima, Perú
[LinkedIn](https://linkedin.com/in/rodrigo-aniceto-nuñez) |
[GitHub](https://github.com/RodrigoAN19)