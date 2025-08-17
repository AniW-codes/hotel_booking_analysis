
# 🧾 Hotel Booking Analysis

Analyzing hotel booking efficiency to support strategic inventory and marketing decisions using Python and Tableau.

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project evaluates hotel bookings during the course of multiple years to drive strategic insights for location based inventory optimization and marketing campaigns to improve cancellation rates. 
Python was utlised for cleaning, EDA analysis and hypothesis testing, and Tableau for visualization.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective marketing, identification of holiday periods, and cost manipulation are critical in the hospitality sector. This project aims to explore:

1️⃣ Which factors influence hotel booking cancellations the most?

2️⃣ Do higher prices really lead to more cancellations?

3️⃣ Does waiting list length affect cancellation likelihood?

4️⃣ Which customer segments (OTA, travel agents, direct bookings) cancel more often?

5️⃣ How do seasonality and geography impact cancellations?

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Tableau (Interactive Visualizations)

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

1️⃣ Dropped null values in 100 plus rows.

2️⃣ Removed unwanted columns : agent,	company.

3️⃣ Manipulated data to create bins for customer bookings based on waiting list - Short, Medium, Long.

4️⃣ Extracted month from reservation_status_date to enable visualisation generation based on month in Tableau.

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

- 37% of clients who cancelled their reservation, which has a significant impact on the hotels' earnings.
- City hotels have larger cancellation rates than Resorts.
- Average daily rate (ADR) for a city hotel is less than that of a resort hotel.
- Number of approved reservations is largest in the month of August, whereas January is the month with the most cancelled reservations.
- The top country was found out to be Portugal with the highest number of cancellations (appx 70%).
- Around 47.4% of the clients come from online travel agencies, whereas 20.3% come from Offline travel agents. Only 10% of clients book hotels directly by visiting them and making reservations.

**Outliers Identified:**

- Large ADR values for one of the bookings, skewing the o/p - Ignored for better analysis

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>


✔️ Price sensitivity: Bookings with higher ADR (average daily rate) were significantly more likely to be cancelled.

✔️ Turns out, resorts are more expensive than city hotels, yet city hotels experienced more cancellations.

✔️ Waiting list myth busted: Contrary to expectation, short waitlist customers cancelled more often than those on longer waitlists—likely because long-wait customers are more committed, while short-wait bookings are opportunistic.

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

🔹 Refine pricing strategies—offer competitive discounts during peak cancellation months.

🔹 Incentivize direct bookings to reduce reliance on OTAs.

🔹 Target short-wait customers with retention strategies (flexible offers, loyalty perks).

🔹 Use seasonal promotions in low months (Dec–Jan) to reduce cancellation risks.

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Aniruddha Warang**  
Data Analyst  
📧 Email: waranganya@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/aniruddhawarang/)
