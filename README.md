# 🚀 DataDrip 2025 Hackathon — Power BI Case Study (Top 30)

**Repository name (recommended):** `data-drip-2025-powerbi-dashboard`

**Short description:**  
This repository contains my full submission for the **Data Drip 2025 Hackathon** (organized and supervised by **Qafza**) where I was proud to be ranked among the **Top 30 participants**.  
The project demonstrates data preparation (ETL), data modeling, DAX measures, interactive dashboards, and a ~4-minute presentation video summarizing findings and recommendations.

---

## 📌 Quick Facts

| Item            | Details                                                                 |
|-----------------|-------------------------------------------------------------------------|
| **Event**       | Data Drip 2025 Hackathon (organized & supervised by Qafza)              |
| **Task**        | Think like a data analyst → analyze banking datasets and deliver BI dashboards |
| **Deliverables**| Multi-page Power BI dashboards + ~4-minute demo video                   |
| **Datasets**    | Three relational tables (Users, Cards, Transactions)                    |
| **Result**      | 🏅 Ranked among the **Top 30 participants**                             |

---

## 📊 Data Summary

The dataset contained **three interconnected tables** reflecting a holistic view of customers and their financial behavior.

### 1. Users Data (`users_data.csv`)

| Column             | Description                                  |
|--------------------|----------------------------------------------|
| id                 | Unique customer ID                           |
| current_age        | Current age of the client                    |
| retirement_age     | Planned retirement age                       |
| birth_year         | Year of birth                                |
| birth_month        | Month of birth                               |
| gender             | Gender (Male/Female)                         |
| address            | Home address                                 |
| latitude           | Residence latitude                           |
| longitude          | Residence longitude                          |
| per_capita_income  | Average per capita income in the region      |
| yearly_income      | Customer’s yearly income                     |
| total_debt         | Customer’s total debt                        |
| credit_score       | Credit score                                 |
| num_credit_cards   | Number of credit cards owned                 |

---

### 2. Cards Data (`cards_data`)

| Column                | Description                                 |
|-----------------------|---------------------------------------------|
| id                    | Unique card ID                              |
| client_id             | Customer ID (link to Users)                 |
| card_brand            | Card brand (Visa, MasterCard, etc.)         |
| card_type             | Debit, Credit, Prepaid                      |
| card_number           | Card number                                 |
| expires               | Expiration date                             |
| cvv                   | Security CVV                                |
| has_chip              | Whether the card has EMV chip               |
| num_cards_issued      | Number of cards issued to the customer      |
| credit_limit          | Credit limit                                |
| acct_open_date        | Account opening date                        |
| year_pin_last_changed | Last year the PIN was changed               |
| card_on_dark_web      | Flag if card was found on the dark web      |

---

### 3. Transactions Data (`transactions.xlsx`)

| Column           | Description                                    |
|------------------|------------------------------------------------|
| id               | Unique transaction ID                          |
| date             | Transaction date                               |
| client_id        | Customer ID (link to Users)                    |
| card_id          | Card ID (link to Cards)                        |
| amount           | Transaction amount                             |
| use_chip         | Whether card chip was used                     |
| merchant_id      | Merchant ID                                    |
| merchant_city    | Merchant city                                  |
| merchant_state   | Merchant state/province                        |
| zip              | Merchant ZIP code                              |
| mcc              | Merchant Category Code                         |
| errors           | Errors during transaction (decline, failed auth, etc.) |

📌 **Conclusion:**  
- **Users Data** → Identity & demographics.  
- **Cards Data** → Financial products & credit profile.  
- **Transactions Data** → Spending behavior & merchant activity.  

By combining all three, we obtain a **comprehensive view** for analyzing spending patterns, evaluating risks, and supporting financial decision-making.

---

## 🔧 What I Worked On

- **Data Preparation (ETL):** Merged and cleaned banking datasets.  
- **Data Modeling:** Built relationships and logical data model in Power BI.  
- **DAX Measures:** Created KPIs such as Total Volume, Average Ticket Size, Error Rates, Risk Indicators.  
- **Dashboards Designed:**
  - Executive Overview  
  - Customers  
  - Cards  
  - Transactions  
- **Insights Delivered:** Spending patterns, high-impact merchant categories, customer segmentation, operational risks (PIN age, error rates).  
- **Presentation:** Delivered a ~4-minute video summarizing findings and recommendations.  

---

## 🎯 Key Outcomes

- Strengthened end-to-end analytics workflow (ETL → Modeling → DAX → Visualization).  
- Enhanced **Data Storytelling**: turning raw data into clear recommendations for decision-makers.  
- Gained real-world experience in delivering BI solutions under time constraints.  
- 🏅 Achieved recognition as one of the **Top 30 participants** in the hackathon.  

---

## 📷 Screenshots

![Executive Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/1.png)  
![Customers Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/2.png)  
![Cards Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/3.png)  
![Transactions Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/4.png)  

---

## 🎓 Certificate

![Certificate](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/Mohamad%20Hosam%20Othman_1.png)

---

## 🙏 Acknowledgments

Special thanks to **Qafza** for organizing and supervising the hackathon, and to the mentors for their valuable guidance.
