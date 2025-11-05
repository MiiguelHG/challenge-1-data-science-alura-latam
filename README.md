# Alura Store Latam - Análisis de Datos

## 📋 Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo de datos de ventas de cuatro tiendas de la cadena Alura Store con el objetivo de determinar cuál tienda presenta el menor rendimiento y debería ser vendida para iniciar un nuevo emprendimiento.

El análisis abarca múltiples aspectos del negocio, incluyendo facturación, categorías de productos, calificaciones de clientes, productos más vendidos y costos de envío, proporcionando insights valiosos para la toma de decisiones estratégicas.

## 🎯 Objetivo

Ayudar al Sr. Juan a identificar qué tienda de su cadena debe vender, basándose en un análisis detallado de:
- Ingresos totales por tienda
- Calificación promedio de clientes
- Ventas por categoría de productos
- Productos más y menos vendidos
- Costos de envío promedio
- Distribución geográfica de las tiendas

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **pandas**: Manipulación y análisis de datos
- **matplotlib**: Visualización de datos estática
- **numpy**: Operaciones numéricas
- **folium**: Creación de mapas interactivos

## 📦 Instalación

### Prerrequisitos

Asegúrate de tener Python 3.9 o superior instalado en tu sistema.

### Instalación de Dependencias

```bash
pip install pandas matplotlib numpy folium
```

## 🚀 Cómo Ejecutar el Proyecto

1. **Clona o descarga este repositorio**

```bash
git clone https://github.com/MiiguelHG/challenge-1-data-science-alura-latam.git
cd challenge-1-data-science-alura-latam
```

2. **Abre el notebook**

Puedes abrir el notebook `AluraStoreLatam.ipynb` usando:
- Jupyter Notebook
- JupyterLab
- Visual Studio Code con la extensión de Python y Jupyter
- Google Colab

3. **Ejecuta las celdas en orden**

El notebook está estructurado para ejecutarse secuencialmente. Ejecuta cada celda en orden desde la parte superior.

## 📊 Estructura del Proyecto

```
challenge1-data-science-latam/
│
├── AluraStoreLatam.ipynb    # Notebook principal con el análisis
├── mapa_tiendas.html        # Mapa interactivo generado
└── README.md                # Este archivo
```

## 📈 Análisis Realizados

### 1. Importación y Consolidación de Datos
- Carga de datos de 4 tiendas desde repositorios remotos
- Consolidación en un único DataFrame
- Verificación de valores nulos

### 2. Análisis de Facturación
- Cálculo de ingresos totales por tienda
- Identificación de la tienda con menor rendimiento

### 3. Ventas por Categoría
- Análisis de categorías más y menos populares
- Comparación entre tiendas

### 4. Calificación Promedio
- Evaluación de la satisfacción del cliente por tienda
- Relación entre calificaciones y rendimiento

### 5. Productos Más y Menos Vendidos
- Top 5 productos más vendidos por tienda
- Top 5 productos menos vendidos por tienda

### 6. Análisis de Costos de Envío
- Cálculo del costo promedio de envío por tienda
- Relación entre costos y calidad de productos

### 7. Visualizaciones
- **Gráfico de pastel**: Distribución de ingresos totales
- **Gráficos de barras horizontales**: Calificación y costos de envío
- **Mapa de calor**: Ventas por categoría y tienda
- **Mapa interactivo**: Ubicación geográfica de las tiendas

## 🔍 Principales Hallazgos

- **Tienda 4**: Presenta los ingresos totales más bajos (23.58% del total)
- La calificación promedio de la Tienda 4 está por debajo de 4 estrellas
- Existe una correlación entre costos de envío bajos y menores ingresos
- Las categorías de productos se distribuyen de manera similar entre tiendas
- Las Tiendas 2 y 3 muestran el mejor equilibrio entre ingresos, calificación y costos

## 📌 Conclusión

**Recomendación**: Se sugiere la venta de la **Tienda 4**, debido a:
- Menores ingresos totales
- Calificación promedio inferior a 4 estrellas
- Menor valor percibido en productos
- Impacto limitado en el rendimiento general de la cadena

## 📁 Fuentes de Datos

Los datos se obtienen de repositorios públicos de GitHub:
- [Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este análisis:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 👤 Autor

**Miguel Hernández**
- GitHub: [@MiiguelHG](https://github.com/MiiguelHG)

## 📝 Licencia

Este proyecto es parte del Challenge de Data Science de Alura Latam.

## 🙏 Agradecimientos

- Alura Latam por proporcionar el desafío y los datos
- ONE - Oracle Next Education

---

⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub
