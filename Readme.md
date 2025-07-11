📊 UPI Transactions Dashboard – Tableau Project

An interactive dashboard built using Tableau to analyze UPI transaction patterns across Indian cities, age groups, and payment methods. The project demonstrates strong skills in data cleaning, visualization, and insight extraction.

📌 Project Objective

To explore and visualize digital payment behavior through UPI by analyzing:
- Transaction volumes by city and merchant
- Usage patterns across age groups
- Preferred payment modes (Phone Number, QR Code, UPI ID)
- Device and purpose-based segmentation

Tools & Technologies Used

- Tableau Desktop Public Edition – Visualization and dashboarding
- Microsoft Excel – Data cleaning and formatting
- Python (Pandas) – Data preprocessing (optional enhancement)


Dataset Overview

| Column             | Description                                   |
|--------------------|-----------------------------------------------|
| `Bank Name`        | Bank receiving the transaction                |
| `Currency`         | Currency used in transaction                  |
| `Device Type`      | User’s device (Mobile/Desktop)                |
| `Payment Mode`     | Method used: Phone Number, QR Code, or UPI ID |
| `Purpose`          | Transaction category (e.g., Food, Travel)     |
| `Merchant`         | Vendor/platform (e.g., Amazon, Swiggy)        |
| `City`             | Location of user                              |
| `Age Group`        | Grouped by demographics                       |
| `Transaction Count`| Count of transactions                         |


Dataset was cleaned to fix inconsistent merchant names, missing fields, and format standardization using Excel and Pandas.

Tableau Link Dashboard- https://public.tableau.com/views/Book1_17499677884610/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link



Key Features
Dynamic filters** for Bank, Device Type, Payment Mode, and Purpose  
Age group segmentation** for transaction patterns  
Geo-mapping of top cities** by total transaction count  
Merchant-wise breakdown** by payment method  
User-friendly design** with KPIs and visual summaries

---
Sample Insights
Age Group had the highest transaction volume (12,000+)
Mumbai and Delhi lead with over 3 million transactions each
Amazon and Flipkart are top merchants across all methods
QR Code and UPI ID dominate digital payments

How to Run
1. Clone or download the repo  
2. Open the `.twbx` file in Tableau Public/Desktop  
3. Use interactive filters and explore each chart  
4. Refer to `UPI Transactions.xlsx` if reloading the dataset



