# Challenge-Alura-Store
# Análisis de Ventas — Alura Store Latam

## Descripción del Proyecto
Este proyecto forma parte del **Challenge de Data Science – Alura Latam**.  
El objetivo principal es **analizar los registros de ventas** de las cuatro tiendas del Sr. Juan, pertenecientes a la cadena **Alura Store**, con el fin de **determinar cuál de ellas debería vender** para financiar un nuevo emprendimiento.  

Los análisis incluyen métricas de ventas, categorías de productos, valoraciones de clientes y costos de envío.

---

## Conjunto de Datos
Los datos provienen de **cuatro archivos CSV** correspondientes a cada tienda, con un total de **2,359 registros** y **12 columnas** por archivo.

Cada dataset incluye información sobre:
- Nombre y categoría del producto  
- Precio de venta  
- Costo de envío  
- Calificación del cliente  
- Coordenadas geográficas (latitud y longitud)

---

## Tecnologías Utilizadas
- **Python 3**
- **Pandas** -> Limpieza y análisis de datos  
- **Matplotlib** -> Visualización de resultados  
- **Google Colab** -> Desarrollo y documentación del análisis  

---

## Análisis Realizados
1. **Importación y exploración de datos**  
   Se cargaron los archivos CSV y se revisó la estructura de cada dataset.  

2. **Cálculo del ingreso total por tienda**  
   Se sumaron los precios de venta para obtener los ingresos totales de cada tienda.  

3. **Ventas por categoría de producto**  
   Se identificaron las categorías más populares mediante conteo de registros.  

4. **Valoraciones promedio de clientes**  
   Se calcularon los promedios de calificaciones para medir la satisfacción general.  

5. **Costo de envío promedio**  
   Se analizaron los costos logísticos promedio de cada tienda.  

6. **Conclusión y recomendación**  
   Con base en los resultados, se determinó qué tienda presenta menor rendimiento global y se emitió una recomendación final.

---

## Conclusiones
- La **categoría de muebles** fue la de mayor impacto en tres de las cuatro tiendas.  
- La **tienda 1** tuvo la **menor valoración promedio** (3.9 puntos), aunque con una diferencia mínima respecto a las demás.  
- La **tienda 4** registró el **menor nivel de ventas** y, aunque tiene el **menor costo de envío**, este factor no representa una ventaja relevante, ya que el envío es pagado por el cliente.  

**Recomendación:**  
Se sugiere al Sr. Juan **vender la tienda 4** para financiar su nuevo emprendimiento, dado su bajo desempeño en ventas e ingresos.

---

## Estructura del Proyecto
Challenge/
│
├── AluraStoreLatam.ipynb # Notebook principal con el análisis completo
├── README.md # Descripción del proyecto
└── base-de-datos-challenge-1-latam/ # Carpeta con los archivos CSV de las tiendas
├── tienda_1.csv
├── tienda_2.csv
├── tienda_3.csv
└── tienda_4.csv
