# 📊 Omni Retail Multichannel Performance & Customer Insights

## 🎯 Objective / Problem Statement
The objective of this project is to perform a multichannel performance analysis for Omni Retail by integrating sales, customer, product, and marketing data. The goal is to identify profitable product categories, assess campaign effectiveness, understand customer behavior across different age groups and genders, and provide actionable insights to optimize revenue, profit margin, and customer loyalty.

## 🛠 Tools & Technologies Used
- **Python**: Data manipulation and analysis (Pandas, NumPy)
- **Seaborn & Matplotlib**: Visual analytics
- **Power BI**: Interactive dashboard visualization
- **Jupyter Notebook**: Analysis and reporting workflow

## 📂 Dataset Description

### Sales Data (CSV)
Contains transaction-level data for each sale made via online and offline channels.

| Column Name     | Description                         |
|----------------|-------------------------------------|
| Order_ID        | Unique identifier for each order    |
| Product_ID      | Product associated with the sale    |
| Store_ID        | Store making the sale               |
| Channel         | Online or Offline channel           |
| Date            | Date of transaction                 |
| Quantity_Sold   | Number of units sold                |
| Unit_Price      | Price per unit                      |
| Discount        | Discount applied                    |
| Customer_ID     | ID of the purchasing customer       |
| Revenue         | Final revenue after discount        |

### Customer Data (CSV)
Includes demographics and preferences of the customers.

| Column Name         | Description                        |
|---------------------|------------------------------------|
| Customer_ID         | Unique customer identifier         |
| Gender              | Gender of customer                 |
| Age                 | Age of customer                    |
| Location            | Customer location                  |
| Signup_Date         | Date customer signed up            |
| Preferred_Channel   | Online or Offline preference       |
| Loyalty_Status      | Loyal, At Risk, or New             |

### Product Data (CSV)
Information related to each product listed.

| Column Name     | Description                        |
|----------------|------------------------------------|
| Product_ID      | Unique product identifier          |
| Category        | Main category (e.g., Toys, Home)   |
| Sub_Category    | More detailed category             |
| Brand           | Brand name                         |
| Cost_Price      | Cost to company                    |
| Launch_Date     | Product launch date                |

### Marketing Campaign Data (CSV)
Campaign-level spending and outcome tracking.

| Column Name         | Description                         |
|---------------------|-------------------------------------|
| Campaign_ID         | Unique ID of the campaign           |
| Start_Date          | Campaign start date                 |
| End_Date            | Campaign end date                   |
| Channel             | Online or Offline                   |
| Spend               | Budget spent on campaign            |
| Targeted_Category   | Product category targeted           |
| Revenue_Attributed  | Revenue attributed to the campaign  |

## ▶️ How to Run the Project
1. **Clone the repository** using Git, or **download and unzip** the project folder to your local machine:
   ```bash
   git clone https://github.com/YugashiniS441/OmniRetail--Multichannel-Sales-Performance-Customer-Analytics.git

2. Launch the notebook:
   ```bash
   jupyter notebook omni_retail_analysis.ipynb
   ```

3. **Install the required Python libraries** by running:
   ```bash
   pip install -r requirements.txt

4. **To explore the Power BI Dashboard**:
   - Make sure **Power BI Desktop** is installed.
   - Open the file:
     ```
     Source_Code/PowerBI_Insights/retail_sales_dashboard.pbix
     ```
   - Interact with the visuals to explore insights by Campaign_ID,Age,Channel,Date.


## 📈 Results Summary

- **Total Revenue**: ₹355.47K
- **Average Profit Margin**: -52.87
- **Customer Lifetime Value (CLV)**: ₹973.89

### Key Insights:
- Online channel performs better than offline in both revenue and margin.
- Toys and Electronics are leading categories in profits.
- Home and Clothing generate significant losses, especially in offline sales.
- Younger and adult segments prefer online shopping, while old-aged customers are more inclined towards offline purchases.
- Only 33.5% of customers are loyal; over 30% are at risk.
- Campaigns 5088 and 5017 have high ROI, whereas 5004 and 5033 show poor performance.
