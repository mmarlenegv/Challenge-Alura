# Análisis Comparativo de Tiendas – Ventas, Satisfacción y Costes Operativos

Este repositorio contiene el análisis exploratorio y comparativo realizado sobre cuatro tiendas, utilizando Python, pandas y visualizaciones en Matplotlib. El objetivo es identificar cuál de ellas presenta el desempeño más equilibrado considerando ingresos, rotación de productos, satisfacción del cliente y costes operativos.

---

## 📊 1. Objetivo del Proyecto
Evaluar el rendimiento de cada tienda a partir de métricas comerciales y operativas con el fin de identificar la unidad con mejor desempeño integral y justificar su elección dentro del portafolio analizado.

---

## 🧩 2. Descripción del Dataset
El análisis se desarrolló a partir de información de ventas que incluye:

- Productos vendidos por tienda  
- Cantidades y frecuencia (value_counts)  
- Ingresos totales  
- Costes de envío  
- Calificaciones de satisfacción del cliente  
- Categorías de productos  
- Identificadores de tienda  

Formato utilizado: **CSV**.

---

## 🛠️ 3. Metodología
Se emplearon herramientas del ecosistema Python:

- **pandas** para limpieza, transformación y análisis  
- **value_counts()** para identificar productos más y menos vendidos  
- **Matplotlib** para construir gráficos comparativos  
- **Agrupación** por tienda y categoría  
- **Cálculo de promedios**, sumas y KPIs  

Se generaron:

- Top 10 de productos más vendidos por tienda  
- Bottom 10 de productos con menor rotación  
- Comparativas de ingresos  
- Comparativas de satisfacción  
- Comparativas de costes de envío  

---

## 📈 4. Resultados Principales

### 🔝 Productos Más Vendidos
Se identificaron los **Top 10 productos** para cada tienda usando:

```python
df['producto'].value_counts().head(10)
```

### **Ingresos y Costes**

La Tienda 1 lidera en facturación total.
La tienda seleccionada presenta el segundo mayor nivel de ingresos, con mejor eficiencia operativa.
Posee el menor coste de envío promedio (22,512.24).

⭐ Satisfacción del Cliente

La tienda seleccionada alcanza 4.04, valor cercano al mayor promedio observado.
La Tienda 1 tiene la puntuación más baja: 3.98.
La Tienda 3 destaca en satisfacción, pero presenta el mayor coste de envío.

---

## 📁 5. Estructura del Repositorio
Challenge Alura/
└── base-de-datos-challenge1-latam/
├── tienda_1.csv              # Datos de la Tienda 1
├── tienda_2.csv              # Datos de la Tienda 2
├── tienda_3.csv              # Datos de la Tienda 3
├── tienda_4.csv              # Datos de la Tienda 4
└── AluraStoreLatam.ipynb     # Notebook principal con todo el análisis

---
## **📝 6. Conclusiones**

Este repositorio contiene el desarrollo completo del challenge de Análisis de Datos de Alura LATAM.
Se realiza un análisis comparativo entre cuatro tiendas para identificar cuál presenta el mejor desempeño integral considerando ingresos, rotación de productos, satisfacción del cliente y costes de envío.

La tienda seleccionada destaca por un **equilibrio sólido** entre ingresos, rotación, eficiencia logística y satisfacción del cliente. Su rendimiento global supera al de las otras tres unidades al combinar:

1. **Ingresos altos y rotación fuerte** en categorías estratégicas.  
2. **Satisfacción elevada** (4.04), cercana al mejor resultado.  
3. **Coste de envío más bajo**, mejorando márgenes.  
4. Mejor balance general frente a Tienda 1 (baja satisfacción) y Tienda 3 (alto coste logístico).

Por ello, se determina que esta tienda es la alternativa más recomendable dentro del análisis.

---

## **📚 7. Tecnologías utilizadas**

Python 3
pandas
NumPy
Matplotlib
Jupyter Notebook

---

✨ Autora
Martha Marlene Gálvez Vásquez
Ingeniera de Sistemas
