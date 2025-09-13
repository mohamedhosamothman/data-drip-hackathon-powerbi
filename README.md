# 🚀 Data Drip 2025 --- Power BI Case Study

**Repository name (recommended):** `data-drip-2025-powerbi-dashboard`

**Short description:** Power BI dashboards and end-to-end analysis
produced for the *Data Drip 2025 Hackathon* (organized and supervised by
**Qafza**). The project demonstrates data preparation (ETL), modeling,
DAX measures, interactive dashboards, and a short presentation video
summarizing findings and recommendations.

**Quick facts** - **Event:** Data Drip 2025 Hackathon (supervised by
Qafza) - **Task:** Think like a data analyst --- analyze provided
banking datasets and deliver actionable BI deliverables -
**Deliverables:** Power BI dashboards (multi-page) + demo video (\~4
minutes) - **Datasets:** Three tables provided (merged and used to build
the model) - **Result:** 🏅 **Ranked among the Top 30 participants**

------------------------------------------------------------------------

## 📊 Data Summary

The hackathon dataset contained **three interconnected tables**
reflecting a comprehensive view of customers and their financial
behaviour.

### 1. Users Data (users_data.csv)

Contains customer demographics and socio-economic profile.

  Column              Description
  ------------------- ----------------------------------
  id                  Unique customer ID
  current_age         Current age of the client
  retirement_age      Planned retirement age
  birth_year          Year of birth
  birth_month         Month of birth
  gender              Gender (Male/Female)
  address             Home address
  latitude            Residence latitude
  longitude           Residence longitude
  per_capita_income   Avg. per capita income in region
  yearly_income       Client's yearly income
  total_debt          Client's total debt
  credit_score        Credit score
  num_credit_cards    Number of credit cards owned

------------------------------------------------------------------------

### 2. Cards Data (cards_data)

Describes issued cards and credit-related details.

  Column                  Description
  ----------------------- ----------------------------------
  id                      Unique card ID
  client_id               Customer ID (link to Users)
  card_brand              Brand (Visa, MasterCard, etc.)
  card_type               Debit, Credit, Prepaid
  card_number             Card number
  expires                 Expiration date
  cvv                     Security CVV
  has_chip                Whether card has EMV chip
  num_cards_issued        Number of cards issued to client
  credit_limit            Card's credit limit
  acct_open_date          Date account was opened
  year_pin_last_changed   Last PIN change year
  card_on_dark_web        Flag if card found on dark web

------------------------------------------------------------------------

### 3. Transactions Data (transactions.xlsx)

Captures all financial activity.

  Column           Description
  ---------------- --------------------------------------------------------
  id               Unique transaction ID
  date             Transaction date
  client_id        Customer ID (link to Users)
  card_id          Card ID (link to Cards)
  amount           Transaction amount
  use_chip         Whether card chip was used
  merchant_id      Merchant ID
  merchant_city    Merchant city
  merchant_state   Merchant state/province
  zip              Merchant ZIP code
  mcc              Merchant Category Code
  errors           Errors during transaction (decline, failed auth, etc.)

📌 **Conclusion:**\
- **Users Data** → Identity & demographics.\
- **Cards Data** → Financial products & credit profile.\
- **Transactions Data** → Spending behaviour & merchant activity.

By combining all three, we achieve a **holistic view** to analyze
spending patterns, assess risk, and support financial decision-making.

------------------------------------------------------------------------

## 🔧 What I Worked On

-   **Data Preparation (ETL):** Merged & cleaned banking datasets.
-   **Data Modeling:** Built robust relationships in Power BI.
-   **DAX Measures:** Created KPIs like Total Volume, Avg Ticket, Error
    Rates, and Risk Indicators.
-   **Dashboards:**
    -   Executive Overview
    -   Customers
    -   Cards
    -   Transactions
-   **Insights:** Customer spending, top MCC categories, operational
    risks (PIN age, error rates).
-   **Presentation:** Prepared a \~4-minute video highlighting insights
    and recommendations.

------------------------------------------------------------------------

## 🎯 Key Outcomes

-   Strengthened full analytics workflow skills (ETL → Modeling → DAX →
    Visualization).
-   Enhanced **Data Storytelling**: converting numbers into clear
    recommendations.
-   Delivered a real BI product under time constraints.
-   🏅 Ranked among the **Top 30 participants**.

------------------------------------------------------------------------

## 📷 Screenshots

![Executive
Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/1.png)\
![Customers
Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/2.png)\
![Cards
Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/3.png)\
![Transactions
Dashboard](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/4.png)

------------------------------------------------------------------------

## 🎓 Certificate

![Certificate](https://github.com/mohamedhosamothman/data-drip-hackathon-powerbi/blob/main/Mohamad%20Hosam%20Othman_1.png)

------------------------------------------------------------------------

## 🙏 Acknowledgments

Thanks to **Qafza** for organizing and supervising the hackathon, and to
the mentors for their guidance.

------------------------------------------------------------------------

## 🏷️ Tags

#DataDrip2025 #Qafza #PowerBI #DataAnalytics #BusinessIntelligence
#FinancialAnalytics #DataStorytelling
