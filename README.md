# Olist E-commerce Analytics Pipeline

## Descargar la base de datos de: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Descripción

Este proyecto implementa un pipeline integral de análisis de datos para la plataforma de e-commerce **Olist**. Usando múltiples fuentes de datos públicas, el pipeline segmenta clientes, identifica patrones de compra, visualiza insights geográficos, analiza reviews y sugiere acciones de negocio concretas.

## Objetivos

- Segmentar clientes según su comportamiento de compra (modelo RFM).
- Visualizar y entender el valor y la frecuencia de compra de cada segmento.
- Detectar oportunidades de retención y recuperación de clientes.
- Analizar la asociación de productos mediante Market Basket Analysis.
- Visualizar insights geográficos con mapas de calor interactivos.
- Analizar el sentimiento y temas en los comentarios de clientes (WordCloud).
- Proveer recomendaciones de negocio accionables.

## Estructura del pipeline

1. **Carga y limpieza de datos**
2. **Análisis RFM y segmentación de clientes**
3. **Enriquecimiento geográfico y mapas de calor**
4. **Market Basket Analysis (Apriori)**
5. **Visualización de KPIs y migración de segmentos**
6. **Análisis de frecuencia de recompra y CLV**
7. **Análisis de reviews (WordCloud)**
8. **Generación de recomendaciones automáticas**

## Datasets utilizados

- `olist_orders_dataset.csv`: Datos de los pedidos.
- `olist_customers_dataset.csv`: Información de los clientes.
- `olist_order_payments_dataset.csv`: Detalles de los pagos.
- `olist_order_items_dataset.csv`: Ítems de cada pedido.
- `olist_products_dataset.csv`: Información de los productos.
- `product_category_name_translation.csv`: Traducción de categorías.
- `olist_geolocation_dataset.csv`: Geolocalización de ciudades y estados.
- `olist_order_reviews_dataset.csv`: Reseñas y comentarios de los clientes.
- *(Opcional: `olist_sellers_dataset.csv` para análisis por vendedor)*

## Requisitos

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- mlxtend
- networkx
- folium
- wordcloud
- Jupyter Notebook

Instalar dependencias con:

```bash
pip install pandas numpy matplotlib seaborn mlxtend networkx folium wordcloud
