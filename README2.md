# Olist E-commerce Analytics Pipeline

## Download .csv: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Description

This project implements a comprehensive analytics pipeline for the **Olist** e-commerce platform. Using multiple public datasets, the pipeline segments customers, identifies buying patterns, visualizes geographic insights, analyzes customer reviews, and delivers actionable business recommendations.

## Objectives

- Segment customers based on purchasing behavior using the RFM model.
- Visualize and understand customer value and purchase frequency for each segment.
- Detect retention and reactivation opportunities.
- Analyze product associations via Market Basket Analysis.
- Visualize geographic insights with interactive heatmaps.
- Analyze sentiment and topics in customer reviews (WordCloud).
- Provide actionable business recommendations.

## Pipeline Structure

1. **Data loading and cleaning**
2. **RFM analysis and customer segmentation**
3. **Geographic enrichment and heatmaps**
4. **Market Basket Analysis (Apriori)**
5. **KPI visualization and segment migration**
6. **Repurchase frequency and CLV analysis**
7. **Review analysis (WordCloud)**
8. **Automatic business recommendations**

## Datasets Used

- `olist_orders_dataset.csv`: Orders data.
- `olist_customers_dataset.csv`: Customer information.
- `olist_order_payments_dataset.csv`: Payment details.
- `olist_order_items_dataset.csv`: Order items.
- `olist_products_dataset.csv`: Product information.
- `product_category_name_translation.csv`: Product category translation.
- `olist_geolocation_dataset.csv`: City and state geolocation.
- `olist_order_reviews_dataset.csv`: Customer reviews and comments.
- *(Optional: `olist_sellers_dataset.csv` for seller analysis)*

## Requirements

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

Install all dependencies with:

```bash
pip install pandas numpy matplotlib seaborn mlxtend networkx folium wordcloud
