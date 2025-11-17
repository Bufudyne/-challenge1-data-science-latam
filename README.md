# 📊 Análisis de Ventas de Tiendas – Informe Resumido

Este proyecto realiza un análisis exploratorio de datos de cuatro tiendas, utilizando archivos CSV públicos. El objetivo es comparar su desempeño y obtener métricas clave como ingresos, ventas por categoría, calificaciones, costos de envío y productos más/menos vendidos.

---

## 📁 Datos utilizados

Se cargan cuatro bases de datos desde GitHub:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información como:

- Producto  
- Categoría  
- Precio  
- Costo de envío  
- Fecha de compra  
- Vendedor  
- Método de pago  
- Calificación  
- Coordenadas  

---

## 🔍 Análisis realizado

### 1. **Ingresos Totales**
Se suma el valor de las ventas de cada tienda.  
**Resultado general:** la **Tienda 1** es la que más factura.

### 2. **Ventas por Categoría**
Se agrupan los productos por categoría para identificar cuáles se venden más.  
Las categorías más fuertes en todas las tiendas: **Muebles** y **Electrónicos**.

### 3. **Calificación Promedio**
Se calcula el promedio de calificaciones por tienda.  
La tienda con mejor valoración: **Tienda 3**.

### 4. **Productos más y menos vendidos**
Se listan los 5 productos con mayor y menor frecuencia de venta por tienda.

### 5. **Costo de Envío Promedio**
Se calcula el costo de envío promedio por tienda.  
La tienda con envíos más económicos: **Tienda 4**.

### 6. **Visualizaciones**
Se generan gráficos simples (como un gráfico de barras de ingresos totales) para entender mejor los datos.

---

## 📝 Conclusión General

El análisis permite comparar el rendimiento de las cuatro tiendas y evaluar qué tan atractivas son para un posible vendedor, considerando ventas, satisfacción de clientes y costos operativos.

---

## 📌 Tecnologías utilizadas

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook

---
