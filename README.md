# Identifying Shopping Trends using Data Analysis

**AICTE Internship on AI** — Transformative Learning with TechSaksham, a joint CSR initiative of Microsoft & SAP, focusing on AI Technologies.

## Project Overview

Retail businesses accumulate vast amounts of shopping data from multiple channels (in-store, online, etc.) but often struggle to extract actionable insights. This project performs a comprehensive exploratory data analysis (EDA) on a dataset of **3,900 customers** to uncover shopping trends, customer preferences, and seasonal buying patterns — enabling data-driven business decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Key Insights and Findings](#key-insights-and-findings)
- [Visualization Highlights](#visualization-highlights)
- [Recommendations](#recommendations)
- [Tools and Libraries](#tools-and-libraries)
- [Project Structure](#project-structure)
- [Setup and Usage](#setup-and-usage)
- [Future Analysis Directions](#future-analysis-directions)
- [References](#references)
- [Acknowledgments](#acknowledgments)

## Dataset Description

The dataset (`shopping_trends_updated.csv`) contains **3,900 rows** and **19 columns** describing individual customer transactions:

| Column | Description |
|---|---|
| Customer ID | Unique identifier for each customer |
| Age | Age of the customer |
| Gender | Gender of the customer |
| Item Purchased | Name of the item purchased |
| Category | Product category (Clothing, Footwear, Accessories, Outerwear) |
| Purchase Amount (USD) | Amount spent in USD |
| Location | Customer's US state |
| Size | Size of the purchased item |
| Color | Color of the purchased item |
| Season | Season of purchase (Spring, Summer, Fall, Winter) |
| Review Rating | Customer rating (1–5 scale) |
| Subscription Status | Whether the customer has a subscription (Yes/No) |
| Payment Method | Payment method used (Credit Card, PayPal, Cash, etc.) |
| Shipping Type | Shipping method (Express, Free Shipping, etc.) |
| Discount Applied | Whether a discount was applied |
| Promo Code Used | Whether a promo code was used |
| Previous Purchases | Number of prior purchases |
| Preferred Payment Method | Customer's preferred payment method |
| Frequency of Purchases | How often the customer shops |

## Methodology

1. **Data Loading & Inspection** — Load CSV data and inspect shape, types, and missing values.
2. **Data Cleaning** — Handle missing values, correct data types, and remove duplicates.
3. **Feature Engineering** — Create age group categories (Teen, Young Adult, Middle-Aged, Senior) for demographic analysis.
4. **Exploratory Data Analysis (EDA)** — Statistical summaries and distribution analysis across all key variables.
5. **Visualization** — Use Matplotlib, Seaborn, and Plotly to build interactive and static charts revealing patterns.
6. **Insight Extraction** — Synthesize findings into actionable business recommendations.

## Key Insights and Findings

- **Gender Distribution**: Male customers account for a higher share of purchases; however, female customers show higher average spend per transaction.
- **Top Categories**: Clothing dominates purchases, followed by Accessories and Footwear.
- **Seasonal Trends**: Fall and Winter seasons record the highest purchase volumes, suggesting holiday and back-to-school demand spikes.
- **Age Demographics**: The 25–45 age group (Young Adult and Middle-Aged) constitutes the largest customer segment, driving the majority of revenue.
- **Payment Preferences**: Credit Card and PayPal are the most popular payment methods, together representing over 50% of transactions.
- **Subscription Impact**: Subscribed customers make significantly more frequent purchases and are more likely to use promo codes.
- **Review Ratings**: Average review ratings are consistently above 3.5, indicating general customer satisfaction.
- **Location Analysis**: Certain states show markedly higher purchase volumes, pointing to regional demand concentrations.

## Visualization Highlights

- **Age Distribution Histogram** — Shows the spread of customer ages across the dataset.
- **Purchase Amount by Category** — Bar/box plots comparing spending across product categories.
- **Seasonal Purchase Frequency** — Heatmaps and bar charts highlighting seasonal demand patterns.
- **Gender vs. Spend Analysis** — Comparative spending analysis segmented by gender.
- **Payment Method Distribution** — Pie/bar charts of payment method popularity.
- **Location–Item Heatmap** — Cross-tabulation of customer location and items purchased.
- **Word Cloud of Items** — Visual frequency map of the most purchased products.
- **Subscription vs. Purchase Frequency** — Side-by-side comparison of subscriber and non-subscriber behavior.

## Recommendations

1. **Target the 25–45 Age Group** — Develop personalized marketing campaigns for this high-value segment.
2. **Boost Seasonal Promotions** — Concentrate marketing budgets in Fall and Winter to capitalize on peak demand.
3. **Expand Subscription Programs** — Incentivize non-subscribers to join loyalty programs, given subscribers' higher frequency.
4. **Optimize Payment Options** — Prioritize Credit Card and PayPal checkout flows; consider BNPL (Buy Now Pay Later) to attract younger shoppers.
5. **Regional Targeting** — Allocate advertising spend to high-performing states and investigate underperforming regions for growth opportunities.
6. **Category Expansion** — Since Clothing dominates, explore upselling into Accessories and Outerwear for existing customers.

## Tools and Libraries

| Tool / Library | Version | Purpose |
|---|---|---|
| Python | 3.8+ | Core programming language |
| Jupyter Notebook | 6.x+ | Interactive analysis environment |
| pandas | 1.5.x | Data manipulation and analysis |
| numpy | 1.23.x | Numerical computing |
| matplotlib | 3.6.x | Static visualizations |
| seaborn | 0.12.x | Statistical data visualization |
| plotly | 5.x | Interactive visualizations |
| wordcloud | 1.9.x | Word cloud generation |

## Project Structure

```
Identifying-Shopping-Trends-using-Data-Analysis-P3/
├── Project-3 On Shopping Trends Analysis.ipynb   # Main analysis notebook
├── shopping_trends_updated.csv                    # Dataset (CSV format)
├── shopping_trends_updated.xlsx                   # Dataset (Excel format)
├── ANALYSIS_SUMMARY.md                            # Summary of key findings
├── requirements.txt                               # Python dependencies
├── .gitignore                                     # Git ignore rules
├── LICENSE                                        # MIT License
└── README.md                                      # Project documentation
```

## Setup and Usage

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/M4ban/Identifying-Shopping-Trends-using-Data-Analysis-P3.git
   cd Identifying-Shopping-Trends-using-Data-Analysis-P3
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the notebook**
   Open `Project-3 On Shopping Trends Analysis.ipynb` and run all cells sequentially.

## Future Analysis Directions

- **Predictive Modeling** — Build regression or classification models to predict purchase amount or churn.
- **Customer Segmentation** — Apply K-Means or DBSCAN clustering to identify distinct customer personas.
- **Time-Series Forecasting** — If timestamp data becomes available, forecast future demand by category and season.
- **Recommendation System** — Develop a product recommendation engine based on purchase history and demographics.
- **Sentiment Analysis** — Analyze review text (if available) to extract qualitative customer sentiment.
- **A/B Testing Framework** — Design experiments to test the effect of promotions and discount strategies.

## References

- Dataset: [Shopping Trends Dataset](https://www.kaggle.com/) (sourced via Kaggle)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Plotly Documentation](https://plotly.com/python/)

## Acknowledgments

Thanks to **Edunet Foundation** and **TechSaksham** (Microsoft & SAP CSR initiative) for providing the internship framework and dataset that made this analysis possible.
