# Embroidery-Sales-Analytics-Project- With Power BI-Excel, and Python 


##  Project Overview

This is a comprehensive **end-to-end data analytics project** that analyzes regional sales data from 2014-2018. The project demonstrates the complete data analytics workflow from data collection and cleaning to exploratory data analysis and interactive dashboard creation.

##  Business Problem

Sales teams often lack clear, data-driven insights into regional performance, making it difficult to identify growth opportunities and optimize resources. This project aims to:

- Analyze regional sales data to uncover trends
- Evaluate profitability across different channels and products
- Support strategic decision-making with actionable insights
- Create an automated dashboard for ongoing monitoring

##  Key Business Questions Answered

1. **Revenue Trends:** What are the monthly and seasonal sales patterns?
2. **Product Performance:** Which products drive the highest revenue and profit?
3. **Channel Analysis:** How do different sales channels (wholesale, distributor, export) perform?
4. **Geographic Insights:** Which states and regions generate the most revenue?
5. **Customer Segmentation:** Who are our top-performing customers?
6. **Profitability:** What are the profit margins across different segments?

##  Dataset Information

**Data Sources:**
- Embroidery Sales Orders (primary transaction data)
- Customer Information
- Product Catalog
- Regional Data (states, demographics)
- 2017 Budget Data

**Data Period:** January 2014 - February 2018  
**Total Records:** 64,000+ sales transactions  
**Key Metrics:** Revenue, Profit, Order Quantity, Unit Price, Customer Data

**Dataset Structure:**
```
├── Sales Orders (main fact table)
├── Customers (customer demographics)
├── Products (product catalog)
├── Regions (geographic data)
├── State Regions (state-level data)
└── 2017 Budgets (budget comparison data)
```

## 🛠️ Technical Architecture

### Data Analytics Workflow
```
Business Understanding → Data Collection → Data Cleaning → 
Exploratory Data Analysis → Feature Engineering → Dashboard Creation
```

### Technologies Used
- **Python Libraries:** pandas, numpy, matplotlib, seaborn
- **Data Visualization:** Power BI Desktop
- **Data Storage:** Excel/CSV files
- **Development Environment:** Google Colab/Jupyter Notebook

##  Project Structure

```
Sales-Analytics-Project/
│
├── data/
│   ├── raw/
│   │   └── Regional_Sales_Data.xlsx
│   └── processed/
│       └── sales_data_processed.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_feature_engineering.ipynb
│
├── dashboards/
│   ├── Sales_Dashboard.pbix
│   └── dashboard_screenshots/
│
├── scripts/
│   └── data_processing.py
│
├── documentation/
│   ├── Entity_Relationship_Diagram.png
│   └── Key_Insights_Summary.md
│
└── README.md
```

## 🔍 Detailed Analysis Process

### 1. Data Understanding & Preparation
- **Entity Relationship Analysis:** Mapped relationships between sales orders, customers, products, and regions
- **Data Quality Assessment:** Identified and handled missing values, duplicates
- **Data Merging:** Combined multiple data sources using appropriate join operations
- **Feature Engineering:** Created calculated fields for profit, profit margin, and time-based features

### 2. Exploratory Data Analysis (EDA)

#### Key Analyses Performed:
- **Temporal Analysis:** Monthly revenue trends, seasonality patterns
- **Product Performance:** Top/bottom 10 products by revenue and profit
- **Channel Distribution:** Sales performance across wholesale, distributor, and export channels
- **Geographic Analysis:** State-wise and region-wise revenue distribution
- **Customer Segmentation:** Revenue and profit analysis by customer
- **Statistical Analysis:** Correlation matrix, distribution analysis

#### Major Findings:
- **Seasonal Trends:** May shows highest revenue ($102M), with consistent patterns across years
- **Channel Performance:** Wholesale dominates with 54% of total sales
- **Product Insights:** Products 26 and 25 are top performers ($118M and $110M respectively)
- **Geographic Concentration:** California leads in revenue generation
- **Order Value Distribution:** Right-skewed distribution with most orders between $20K-$100K

### 3. Dashboard Development

#### Dashboard Features:
- **Executive Overview:** Key KPIs and trend analysis
- **Product & Channel Performance:** Detailed performance metrics
- **Geographic & Customer Insights:** Regional and customer analysis
- **Interactive Filters:** Year, month, region, channel filtering
- **Navigation:** Multi-page dashboard with seamless navigation

#### Key Performance Indicators (KPIs):
- Total Revenue: $1.24 Billion
- Total Profit: $532 Million
- Profit Margin: 37%
- Total Orders: 64,000+
- Average Revenue per Order: $19,281


##  Key Business Insights

### Revenue & Profitability
- **Total Revenue:** $1.24 billion over the analysis period
- **Overall Profit Margin:** 37% across all channels
- **Revenue Growth:** Consistent performance with seasonal variations

### Channel Performance
| Channel | Revenue Share | Performance |
|---------|---------------|-------------|
| Wholesale | 54% | Primary revenue driver |
| Distributor | 31% | Strong secondary channel |
| Export | 15% | Emerging opportunity |

### Product Insights
- **Top Performers:** Products 26, 25, and 13 drive 25% of total revenue
- **Long Tail:** Bottom 50% of products contribute <10% of revenue
- **Profit Margins:** Consistent across product categories (~37%)

### Geographic Distribution
- **Top States:** California, Illinois, Florida lead in revenue
- **Regional Patterns:** West and Midwest regions show strongest performance
- **Growth Opportunities:** Identified underperforming states for expansion

### Customer Analysis
- **Top Customer:** Airbox Company ($12.5M revenue)
- **Customer Concentration:** Top 10 customers contribute 30% of revenue
- **Segmentation:** Clear distinction between high-value and volume customers

## 🚀 Business Recommendations

### Immediate Actions
1. **Channel Optimization:** Invest more in wholesale channel expansion
2. **Product Focus:** Prioritize marketing for top-performing products 26 and 25
3. **Geographic Expansion:** Develop strategies for underperforming states
4. **Customer Retention:** Implement VIP programs for top 10 customers

### Strategic Initiatives
1. **Seasonal Planning:** Prepare for May revenue peaks with inventory management
2. **Channel Development:** Explore export channel growth opportunities
3. **Product Portfolio:** Analyze bottom-performing products for discontinuation
4. **Regional Strategies:** Customize approaches for different geographic markets

## 🔧 Technical Implementation

### Data Processing Pipeline
```python
# Key processing steps
1. Data Loading and Validation
2. Entity Relationship Mapping
3. Data Cleaning and Transformation
4. Feature Engineering
5. Statistical Analysis
6. Visualization Creation
```

### Power BI Development
- **Data Model:** Star schema with fact and dimension tables
- **DAX Measures:** Custom calculations for KPIs and metrics
- **Interactive Features:** Slicers, drill-through, bookmarks
- **Design:** Professional layout with company branding

## 📈 Model Performance & Validation

### Data Quality Metrics
- **Completeness:** 98% of records have complete core fields
- **Accuracy:** Cross-validated against source systems
- **Consistency:** Standardized formats across all data sources

### Business Validation
- **Stakeholder Review:** Insights validated with business users
- **Historical Comparison:** Trends align with known business patterns
- **Actionability:** All insights tied to specific business recommendations

## 🔄 Future Enhancements

### Phase 2 Developments
- **Predictive Analytics:** Sales forecasting models
- **Real-time Updates:** Live data connection implementation
- **Advanced Segmentation:** Machine learning-based customer clustering
- **Mobile Optimization:** Responsive dashboard design

### Technical Improvements
- **Data Pipeline Automation:** ETL process automation
- **Performance Optimization:** Query performance tuning
- **Security Implementation:** Row-level security for different user roles
- **API Integration:** Direct connection to business systems

## 🚦 Getting Started

### Prerequisites
- Python 3.7+
- Power BI Desktop
- Excel 2016+
- Git

### Installation & Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/sales-analytics-project.git

# Navigate to project directory
cd sales-analytics-project

# Install required Python packages
pip install -r requirements.txt

# Open Jupyter notebooks
jupyter notebook notebooks/
```

### Running the Analysis
1. **Data Processing:** Run `01_data_cleaning.ipynb`
2. **EDA:** Execute `02_exploratory_analysis.ipynb`
3. **Dashboard:** Open `Sales_Dashboard.pbix` in Power BI Desktop

## About The Project 

**Project Author:** Sonal M. Khobragade  
**Role:** Business Analyst  
**LinkedIn:** http://www.linkedin.com/in/sonal-mk
**Email:** Ksonal055@gmai.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

##  Acknowledgments

- Dataset source: Public domain sales data
- Inspiration: Real-world business analytics challenges
- Tools: Thanks to the open-source community for Python libraries and Microsoft for Power BI

