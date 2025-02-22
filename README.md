# Retail Sales Data Analysis Project

## Overview
This project performs comprehensive Exploratory Data Analysis (EDA) on retail sales data to uncover patterns, trends, and actionable insights. The analysis includes time series patterns, promotion effectiveness, and store performance metrics.

## Features
- **Data Preprocessing**: Automated cleaning and validation of retail sales data
- **Time Series Analysis**: Daily and monthly sales trends with moving averages
- **Promotion Impact Analysis**: Evaluation of different promotion types and their effectiveness
- **Store Performance Metrics**: Analysis of store-level sales and inventory patterns
- **Visual Analytics**: Six different types of visualizations including:
  - Daily sales trends with moving averages
  - Day-of-week sales patterns
  - Price vs. sales relationships
  - Promotion impact analysis
  - Stock-sales heatmap
  - Monthly revenue trends

## Dataset Structure
The analysis expects a CSV file with the following columns:
- `product_id`: Unique identifier for products
- `store_id`: Unique identifier for stores
- `date`: Date of sales
- `sales`: Number of units sold
- `revenue`: Total revenue
- `stock`: Available inventory
- `price`: Product price
- `promo_type_1`: Primary promotion type
- `promo_bin_1`: Binary indicator for promotion 1
- `promo_type_2`: Secondary promotion type
- `promo_bin_2`: Binary indicator for promotion 2
- `promo_discount_2`: Discount percentage for promotion 2

## Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Place your retail sales data CSV file in the project directory
2. Update the filename in the script:
```python
df = pd.read_csv('your_file_name.csv')
```

3. Run the analysis:
```bash
python retail_analysis.py
```

## Output
The script generates:
1. Processed dataset (`processed_retail_data.csv`)
2. Visualization dashboard (`retail_analysis.png`)
3. Console output with key insights including:
   - Sales trends
   - Peak sales days
   - Promotion effectiveness
   - Stock-sales correlations
   - Store performance metrics

## Sample Insights
The analysis provides insights such as:
- Peak sales patterns by day of week
- Most effective promotion types
- Stock level optimization recommendations
- Store performance comparisons
- Price-sales relationships

## Contact
Your Name -AVINASH P @ paramanathamavinash@gmail.com

## Acknowledgments
- Data source: [Retail Dataset Source]
- Libraries used: pandas, numpy, matplotlib, seaborn, plotly
