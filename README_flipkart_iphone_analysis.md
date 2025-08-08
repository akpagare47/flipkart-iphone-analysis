# 📱 Flipkart iPhone Data Analysis (EDA)

This repository contains an end-to-end **Exploratory Data Analysis (EDA)** of Apple iPhones listed on **Flipkart**, performed using **Python, Pandas, and Plotly** in Jupyter Notebook.

## 🎯 Objectives
- Identify the most popular iPhone models (by ratings & reviews)
- Explore the relationship between **Sale Price**, **Discount**, and **Star Rating**
- Derive **business insights** for pricing, inventory, and marketing decisions

## 📂 Repository Contents
- `Flipkart_I Phone Sales - Completed Project.ipynb` – main analysis notebook (with charts visible on GitHub)
- (Optional) `Flipkart_I Phone Sales - Completed Project.html` – shareable HTML export of the notebook
- `data/` – place raw data here (e.g., `apple_products.csv`) *(do not commit sensitive data)*

## 🧰 Tools & Libraries
- Python, Jupyter Notebook
- pandas, numpy
- plotly.express, matplotlib

## 🔎 Data Overview
Columns include: `Product Name`, `Sale Price`, `Mrp`, `Discount Percentage`, `Number Of Ratings`, `Number Of Reviews`, `Star Rating`, `Ram`, `Product URL`, `Upc`.

- No missing values
- Prices & ratings are numeric and analysis-ready
- RAM is a categorical feature (e.g., "2 GB", "4 GB")

## 📊 Key Visuals (in the Notebook)
- **Distribution of Star Ratings**
- **Price vs. Number of Ratings** (trendline + bubble size = discount)
- **Top 10 Most Rated iPhones**
- **Discount vs. Star Rating**

> 💡 Tip: On GitHub, charts display as **static images**. For **interactive plots**, open the notebook locally or use the HTML export.

## 🧠 Insights (Highlights)
- Mid-range iPhones (₹50K–₹80K) tend to attract more ratings
- High discount ≠ guaranteed popularity — perceived value and trust matter
- Most devices maintain 4.5+ star ratings, indicating strong satisfaction

## 💼 Business Recommendations
1. Focus inventory & promotions on **mid-range** devices
2. Highlight models with **4.5★+ ratings** to build buyer confidence
3. Use **value bundles / EMI** for high-priced devices
4. Continue positioning older models (e.g., iPhone 8/XR) as **affordable premium**

## ▶️ Running the Notebook Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/flipkart-iphone-analysis.git
   cd flipkart-iphone-analysis
   ```
2. (Optional) Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open the notebook and **Run All**.

> If you don’t have a `requirements.txt`, typical libs are:
> `pandas numpy plotly matplotlib`

## 🚀 Next Steps (Roadmap)
- Build a **dashboard** (Power BI / Tableau / Plotly Dash / Streamlit)
- Add **SQL** analysis version
- Try **segmentation/clustering** of models by price & popularity
- Automate data refresh (web scraping or APIs)

## 📄 License
MIT License (or choose your own)

---

**Author:** Your Name  
**Contact:** LinkedIn / Email  
**Note:** This project is for learning/portfolio purposes.
