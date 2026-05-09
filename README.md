# 📊 ANALISIS DEL CUBO DE VENTAS DEL PERIODO 2025 DE UNA EMPRESA DISTRIBUIDORA DE LA MARCA NESTLE

## 📌 Descripción

Proyecto final de Ciencia de Datos enfocado en el análisis exploratorio del cubo de ventas del periodo 2025 de una empresa distribuidora de productos de la marca Nestlé.

El proyecto incluye procesos de:

- Limpieza de datos
- Transformación de datos
- Análisis exploratorio (EDA)
- Visualización de datos

El análisis fue desarrollado utilizando Python en Google Colab en el siguiente enlace.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10MPB9fch3A2Sn4knqRFuJkx9XxOZaMgI?usp=sharing)

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

---

# 📈 Análisis Realizados

## 📊 Evolución de ventas por mes

Análisis temporal de las ventas durante el año 2025.

<img width="948" height="456" alt="ventas_mes" src="https://github.com/user-attachments/assets/99971bbb-717c-43f1-b6c4-e0cb433363f2" />

---

## 🏆 Top 10 vendedores por volumen de ventas

Identificación de los vendedores con mejor desempeño comercial.

<img width="1107" height="532" alt="top_10" src="https://github.com/user-attachments/assets/4014effe-16f7-48d1-a463-45b502932a87" />

---

## 📉 Gráfico de dispersión entre Importe Total y Mes

Análisis visual del comportamiento de ventas por periodo.

<img width="946" height="463" alt="disper" src="https://github.com/user-attachments/assets/401991f9-ee42-409d-b246-d05f3aa7d5bb" />

---

## 📦 Productos más vendidos

Determinación de los productos con mayor cantidad comercializada.

<img width="1102" height="543" alt="image" src="https://github.com/user-attachments/assets/1471950c-d361-47c2-b69f-7cca1ccaf5b4" />


---

## 🌎 Top 10 provincias con mayor volumen de ventas

Comparación geográfica del rendimiento comercial.

<img width="1108" height="546" alt="prov" src="https://github.com/user-attachments/assets/d9473729-e3cb-4409-94e1-3faeb1c08857" />


---

## 🥇 Categoría con mayor volumen de ventas

Análisis de la categoría dominante en ventas.


---

## 📅 Categoría más vendida por mes

Evaluación mensual de categorías líderes.

<img width="700" height="644" alt="cate" src="https://github.com/user-attachments/assets/d48e9ad2-e6e0-4dee-8a2b-c6463049d4ff" />

---

## 📍 Categorías más vendidas por mes en San Román

Análisis específico por provincia.

<img width="1265" height="628" alt="juliaca" src="https://github.com/user-attachments/assets/4631b037-3379-4b3d-af07-9be0cfbae41b" />

---

## 📍 Categorías más vendidas por mes en Puno

Comparación regional de comportamiento comercial.

<img width="1254" height="626" alt="puno" src="https://github.com/user-attachments/assets/d4f071c1-b9eb-4cf6-9cfa-647d5572c93d" />

---

## 💡 Análisis de Pareto (Top 20 Productos)
Descripción: Aplicación de la Ley de Pareto (80/20) sobre el catálogo de productos. Este gráfico identifica los SKU críticos que representan la mayor concentración de ingresos, permitiendo optimizar políticas de inventario y priorización logística.

<img width="948" height="456" alt="Gráfico de Pareto Ventas por Producto Top 20" src="https://github.com/user-attachments/assets/d46aaa40-ee16-4091-a295-427fd9309075" />

---
## 💡 Jerarquía de Ingresos por Categoría
Descripción: Distribución del ingreso total acumulado segmentado por tipo de cliente. Revela el peso financiero de cada canal, destacando la paridad estratégica entre el sector Mayorista (valor) y el Minorista (capilaridad de mercado).

<img width="948" height="456" alt="jerarquia de clientes" src="https://github.com/user-attachments/assets/2bddc0fc-6b80-4c93-938f-954e926b6724" />

---
## 💡 Ticket Promedio vs. Carga Operativa (Volumen)
Descripción: Análisis comparativo entre el valor transaccional medio y la frecuencia de facturación. Se utiliza una escala logarítmica para normalizar la dispersión, evidenciando la dualidad entre la eficiencia del canal mayorista y la alta demanda de procesamiento del canal minorista (330k+ facturas).

<img width="948" height="465" alt="ticket_promedio_volumen" src="https://github.com/user-attachments/assets/e72a9022-49f7-4460-81c1-4c3ff15e9309" />

---
## 💡 Eficiencia Regional (Puno vs. San Román)
Descripción: Evaluación geográfica del ticket promedio comparado con la media regional ($S/. 81.34$). El análisis identifica a San Román como el hub de mayor eficiencia transaccional, superando el promedio general y marcando una pauta para la optimización de rutas logísticas.

<img width="948" height="456" alt="Comparativa Ticket Promedio por Provincia vs Promedio General" src="https://github.com/user-attachments/assets/b5fc7f67-944e-40f9-bd6e-c81ddf836d92" />

---
## 💡 Mapa de Comportamiento de Compra (Scatter Plot)
Descripción: Visualización de dispersión bi-logarítmica mediante feature engineering (Precio Unitario vs. Cantidad). Este modelo permite identificar clusters de comportamiento de compra, detectar outliers y auditar la integridad de los datos de facturación en tiempo real.

<img width="948" height="456" alt="mapa_de_comportamiento" src="https://github.com/user-attachments/assets/a9203859-c811-42d3-9a59-59b51ee45f61" />

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

# 👨‍💻 Autores

-Oscar Edy Vilca Quispe
-Rodrigo Bernardo Condori Gutierrez

Proyecto Final de Ciencia de Datos - 2026
