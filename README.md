# CHALLENGE-ALURA-01-uwu

# Alura Store Latam — Análisis de Rendimiento de Tiendas

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-red)

## 📋 Descripción

Este proyecto forma parte del **Challenge 1 de Data Science de Alura Latam**. El objetivo es analizar el rendimiento de cuatro tiendas ficticias de comercio electrónico en Colombia, identificar patrones de ventas, comportamiento del cliente y oportunidades de mejora para apoyar una decisión de negocio estratégica.

> **Pregunta de negocio:** ¿Cuál tienda debería vender el Sr. João para invertir en un nuevo emprendimiento?

---

## 📁 Estructura del Proyecto

```
📦 alura-store-latam/
├── 📓 AluraStoreLatam_Mejorado.ipynb   # Notebook principal de análisis
├── 📄 README.md                         # Este archivo
└── 📊 datos/                            # (opcionales, cargados desde GitHub)
    ├── tienda_1.csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

---

## 📊 Dataset

Los datos provienen del repositorio oficial del challenge:

🔗 [challenge1-data-science-latam](https://github.com/alura-es-cursos/challenge1-data-science-latam)

Cada tienda contiene aproximadamente **2,359 registros** con las siguientes columnas:

| Columna | Descripción |
|--------|-------------|
| `Producto` | Nombre del producto vendido |
| `Categoría del Producto` | Categoría (Muebles, Electrónicos, etc.) |
| `Precio` | Precio de venta en COP |
| `Costo de envío` | Costo de envío en COP |
| `Fecha de Compra` | Fecha de la transacción |
| `Vendedor` | Nombre del vendedor |
| `Lugar de Compra` | Ciudad de la transacción |
| `Calificación` | Calificación del cliente (1–5) |
| `Método de pago` | Tarjeta, efectivo, cuotas, etc. |
| `Cantidad de cuotas` | Número de cuotas del pago |
| `lat` / `lon` | Coordenadas geográficas |

---

## 🔍 Análisis Realizados

El notebook cubre **12 secciones de análisis**:

1. **Exploración general** — forma del dataset, nulos, estadísticas descriptivas
2. **Facturación total** — ingresos por tienda con formato COP
3. **Ventas por categoría** — comparación entre tiendas por categoría de producto
4. **Calificación promedio** — rating promedio y distribución de calificaciones
5. **Productos más y menos vendidos** — top 10 y bottom 10 global
6. **Costo de envío** — promedio por tienda y por categoría
7. **Análisis temporal** — evolución anual y distribución mensual de ventas
8. **Métodos de pago** — preferencias por tienda (pie chart + barras apiladas)
9. **Distribución geográfica** — ciudades con mayor facturación y volumen
10. **Rendimiento por vendedor** — ranking de ingresos y calificación promedio
11. **Dashboard resumen** — panel de 6 gráficas integradas
12. **Conclusiones y recomendaciones** — tabla comparativa y decisión final

---

## 📈 Resultados Clave

| Métrica | 🥇 Mejor | 🔴 Peor |
|---------|----------|---------|
| Facturación total | Tienda 1 (~1.15B COP) | Tienda 4 (~1.04B COP) |
| Calificación promedio | Tienda 3 (4.05) | Tienda 1 (3.98) |
| Costo de envío | Tienda 4 (23,459 COP) | Tienda 1 (26,018 COP) |

### 💡 Recomendación Final

> **Se recomienda vender la Tienda 4.** Aunque tiene el menor costo de envío, presenta la facturación más baja y menor volumen de ventas. La Tienda 1 lidera en ingresos y tiene potencial de mejora en satisfacción del cliente.

---

## 🚀 Cómo Ejecutar

### Requisitos

```bash
pip install pandas matplotlib numpy jupyter
```

### Ejecución

```bash
# Clonar el repositorio
git clone https://github.com/alura-es-cursos/challenge1-data-science-latam

# Abrir el notebook
jupyter notebook AluraStoreLatam_Mejorado.ipynb
```

> ⚠️ Los datos se cargan directamente desde GitHub, por lo que se requiere conexión a internet.

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas** — manipulación y análisis de datos
- **Matplotlib** — visualizaciones y gráficas
- **Jupyter Notebook** — entorno de desarrollo interactivo

---

## 👤 Autor

Desarrollado como parte del **Challenge de Data Science — Alura Latam**.

---

## 📄 Licencia

Este proyecto es de uso educativo. Los datos pertenecen a [Alura Latam](https://www.aluracursos.com/).
