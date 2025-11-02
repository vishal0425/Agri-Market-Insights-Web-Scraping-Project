
🌾 Agri-Market Insights using Web Scraping (Agmarknet Data Analysis)
📖 Project Overview

Farmers often struggle to know which market offers better prices for their crops.
Due to lack of real-time price information, they end up selling to local vendors at low rates, missing better opportunities elsewhere.

This project uses web scraping to collect and analyze agricultural market data from the Agmarknet website.
The goal is to help farmers, vendors, and agricultural businesses make data-driven decisions about crop sales, production, and pricing.

🎯 Objectives

Collect crop price and arrival data using web scraping.

Analyze market-wise and district-wise price trends.

Identify profitable crops and markets for farmers.

Understand supply-demand relationships through data visualization.

Provide insights to help reduce farmer losses and improve income.

🧠 Problem Statement

Farmers work hard to grow crops but face difficulties when selling their vegitables.
They don’t know where or when to sell for the best price.
Without accurate data, most sell locally at lower prices and later regret missing better opportunities.

This project aims to bridge that gap by giving farmers access to real, data-backed insights.

🛠️ Tools & Technologies

Python (Data Collection & Analysis)

Libraries: pandas, numpy, matplotlib, seaborn, requests, BeautifulSoup

Data Source: Agmarknet.gov.in

Visualization: Charts, graphs, and heatmaps for better understanding

📊 Key Features

Extracted 45+ crop tables (varieties) from Agmarknet via web scraping.

Combined all into a single main dataframe for analysis.

Conducted Univariate, Bivariate, and Multivariate Analysis:

Price trends by district and market.

Arrival vs Price relationships.

Crop-wise and group-wise comparisons.

Built easy-to-understand visual insights for farmers.

🌍 Insights & Findings

Negative correlation between arrivals and prices — more supply, lower prices.

Garlic and Beans show highest prices but low production.

Cabbage, Tomato, and Brinjal are most widely produced but fetch moderate prices.

Nashik and Pune are top-performing markets; Chandrapur shows low activity due to lesser production.

Seasonal trends show high arrivals and prices between January–July.

💡 Farmer Impact

Helps farmers know which market gives better prices.

Guides crop selection based on profit and demand.

Encourages smart selling decisions to avoid price drops.

Reduces dependency on middlemen and guesswork.

📂 Project Structure
Agri-Market-Insights-Web-Scraping-Project/
│
├── data/                 # Raw and cleaned data files
├── notebooks/            # Jupyter notebooks for analysis
├── scripts/              # Web scraping and cleaning scripts
├── visuals/              # Charts, graphs, and visual outputs
├── README.md             # Project documentation
└── requirements.txt      # Required Python libraries

🚀 Future Scope

Build a real-time dashboard for farmers to track prices.

Include forecasting models to predict future crop prices.

Develop a mobile app to make insights easily accessible to farmers.

👨‍💻 Author

Vishal Chavanke
📍 Data Enthusiast | Python & SQL Learner | Passionate about solving real-world problems with data.
