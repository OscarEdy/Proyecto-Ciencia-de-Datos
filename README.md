# 📊 ANALISIS DEL CUBO DE VENTAS DEL PERIODO 2025 DE UNA EMPRESA DISTRIBUIDORA DE LA MARCA NESTLE

## 📌 Descripción

Proyecto final de Ciencia de Datos enfocado en el análisis exploratorio del cubo de ventas del periodo 2025 de una empresa distribuidora de productos de la marca Nestlé.

El proyecto incluye procesos de:

- Limpieza de datos
- Transformación de datos
- Análisis exploratorio (EDA)
- Visualización de datos
- Interpretación comercial

El análisis fue desarrollado utilizando Python en Google Colab.

---

# 🎯 Objetivos

- Analizar el comportamiento de ventas durante el periodo 2025.
- Identificar productos y categorías con mayor volumen de ventas.
- Evaluar el desempeño de vendedores.
- Analizar ventas por provincias.
- Generar visualizaciones para la toma de decisiones.

---

# 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

# 🧹 Limpieza de Datos

Se realizaron los siguientes procesos:

- Eliminación de columnas innecesarias
- Conversión de tipos de datos
- Tratamiento de fechas
- Validación de datos nulos
- Eliminación de duplicados
- Conversión de variables binarias
- Encriptación de campos sensibles

---

# 📈 Análisis Realizados

## 📊 Evolución de ventas por mes

Análisis temporal de las ventas durante el año 2025.

---

## 🏆 Top 10 vendedores por volumen de ventas

Identificación de los vendedores con mejor desempeño comercial.

---

## 📉 Gráfico de dispersión entre Importe Total y Mes

Análisis visual del comportamiento de ventas por periodo.

---

## 📦 Productos más vendidos

Determinación de los productos con mayor cantidad comercializada.

---

## 🌎 Top 10 provincias con mayor volumen de ventas

Comparación geográfica del rendimiento comercial.

---

## 🥇 Categoría con mayor volumen de ventas

Análisis de la categoría dominante en ventas.

---

## 📅 Categoría más vendida por mes

Evaluación mensual de categorías líderes.

---

## 📍 Categorías más vendidas por mes en San Román

Análisis específico por provincia.

---

## 📍 Categorías más vendidas por mes en Puno

Comparación regional de comportamiento comercial.

---

# 📂 Estructura del Proyecto

```bash
📁 proyecto-ciencia-datos
│
├── 📄 README.md
├── 📄 ventas2025.csv
├── 📄 analisis.ipynb
├── 📁 graficos
├── 📁 dataset_limpio
└── 📁 resultados
```

---

# 📌 Variables Analizadas

- Año
- Mes
- Documento_Estado
- Cliente_Provincia
- Cliente_Departamento
- Categoria_detalle
- Producto_Detalle
- Producto_Cantidad
- Importe_Total
- Vendedor_Nombre
- Proveedor

---

# 📊 Resultados Esperados

- Identificación de tendencias comerciales
- Evaluación de desempeño de ventas
- Detección de categorías estratégicas
- Análisis regional de ventas
- Soporte para toma de decisiones

---

# 👨‍💻 Autor

**Edy Vilca**

Proyecto Final de Ciencia de Datos - 2026
# 📘 Diccionario de Datos

## 📊 Dataset: Cubo de Ventas 2025 - Empresa Distribuidora Nestlé

| Variable | Descripción | Tipo de Dato | Ejemplo |
|---|---|---|---|
| Año | Año correspondiente al registro de venta | int64 | 2025 |
| Mes | Mes correspondiente al registro de venta | int64 | 1 |
| Documento_Estado | Estado del documento (1 = Activo, 0 = Anulado) | int64 | 1 |
| Pedido | Número o referencia del pedido/comprobante | object | Pedido/ B301-0924174 |
| Documento_Fecha | Fecha del documento de venta | datetime64 | 2026-05-09 |
| Cliente_Codigo | Código único del cliente | object | 9690 |
| Cliente_Distrito | Distrito del cliente | object | JULIACA |
| Cliente_Categoria | Categoría comercial del cliente | object | MINORISTA |
| Cliente_Giro | Giro comercial del cliente | object | BODEGA |
| Almacen_Detalle | Nombre del almacén o línea comercial | object | NESTLE |
| Categoria_codigo | Código de la categoría del producto | int64 | 10 |
| Categoria_detalle | Nombre de la categoría del producto | object | CHOCOLATES |
| subcategoria_codigo | Código de la subcategoría del producto | int64 | 101 |
| subcategoria_detalle | Nombre de la subcategoría del producto | object | GALLETAS |
| Producto_Codigo | Código único del producto | object | 123456 |
| Producto_Detalle | Nombre o descripción del producto | object | MILO 200G |
| Producto_presentacion | Presentación del producto | object | UNIDAD |
| Producto_Cantidad | Cantidad vendida del producto | float64 | 18.000000 |
| Importe_Total | Importe total de la venta | float64 | 30.59 |
| Vendedor_Codigo | Código del vendedor | object | VN063 |
| Vendedor_Nombre | Nombre del vendedor | object | PRISCA ROJAS |
| Vendedor_Ciudad | Ciudad asignada al vendedor | object | JULIACA |
| Proveedor | Nombre del proveedor | object | NESTLE PERU S A |
| MotivoAnulacion | Motivo de anulación o error del documento | object | error |
| Importe_ValorVenta | Valor neto de la venta sin impuestos | float64 | 25.923729 |
| Cliente_Provincia | Provincia del cliente | object | SAN ROMAN |
| Cliente_Departamento | Departamento del cliente | object | PUNO |

---

# 📌 Tipos de Datos Utilizados

| Tipo | Descripción |
|---|---|
| int64 | Números enteros |
| float64 | Números decimales |
| object | Texto o cadenas de caracteres |
| datetime64 | Fechas y tiempo |

---

# 📊 Descripción General del Dataset

El dataset contiene información relacionada a las ventas realizadas durante el periodo 2025 por una empresa distribuidora de productos de la marca Nestlé.

Incluye información sobre:

- Ventas
- Clientes
- Productos
- Categorías
- Vendedores
- Ubicación geográfica
- Importes de venta
- Estado de documentos comerciales
