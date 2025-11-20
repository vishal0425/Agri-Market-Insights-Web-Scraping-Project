# 🌾 Agri-Market Insights using Web Scraping (Agmarknet Data Analysis)

## 📌 Project Overview  
Farmers often don’t know which market gives them the best price for their crops.  
Because of this, they sell their produce to local traders at low rates and regret it later.  

This project collects real-time data from the **Agmarknet website using web scraping**, analyzes it, and provides useful insights to help farmers, vendors, and agribusinesses make better decisions.

---

## 🎯 Objectives  
- Collect agricultural data (prices, arrivals, market details) using **web scraping**.  
- Combine all scraped tables into **one main dataframe for analysis**.  
- Analyze **market-wise, district-wise, and crop-wise** prices.  
- Study **supply vs price (arrival vs price)** trends.  
- Help farmers choose the **right market, right time, and right crop**.

---

## 🧠 Problem Statement  
Farmers work hard to grow vegetables, but when it's time to sell, they don’t know:  
✔ Where to sell?  
✔ Which market offers better price?  
✔ Is demand high or low?  

Due to this, they sell at lower rates and miss out on better income.  
This project helps solve this by using **real market data and visual insights**.

---

## 🛠️ Tools & Technologies  
| Task | Tools Used |
|------|------------|
| Web Scraping | Python, Requests, BeautifulSoup |
| Data Cleaning | Pandas, Numpy |
| Visualization | Matplotlib, Seaborn |
| Source | Agmarknet (Government Agricultural Market Portal) |

---

## 📂 How Web Scraping Was Used  
1. **Send request** to Agmarknet website.  
2. **Extract 45+ tables**, each for a different crop variety.  
3. All tables had columns: District, Market, Variety, State, Arrivals, Prices.  
4. **Combined all tables into one dataframe** using Pandas.  
5. Used this dataset for further analysis and visualization.

---

## 📊 Key Insights (Summary)  
- **More supply = lower price** (negative relationship).  
- **Garlic & Beans** have highest prices but low production.  
- **Cabbage, Tomato, Brinjal** are most commonly grown and traded.  
- **Nashik & Pune** are the most active markets.  
- **Chandrapur** shows fewer records as production and markets are limited.  
- **January–July** shows highest trading activity.

---

## 💡 Impact for Farmers  
✔ Helps farmers find which market gives **better price**.  
✔ Shows which crops are **profitable or risky**.  
✔ Helps avoid selling during **high supply – low price periods**.  
✔ Reduces dependency on **middlemen and guesswork**.

---


## 👨‍💻 Author  
**Vishal Chavanke**  
Data Analyst | Python & SQL Enthusiast  
Focused on turning confusion into clarity through analytical thinking.

