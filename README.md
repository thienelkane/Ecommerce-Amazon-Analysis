# 🛍️ Amazon Sales Analysis

This project presents a comprehensive exploratory analysis of Amazon sales data, focused on uncovering key revenue drivers, customer behaviors, and product performance.

---

## 📊 Project Objectives

- Analyze monthly revenue trends over time
- Identify best-performing products by revenue and quantity
- Understand the distribution of order statuses (delivered, cancelled, returned)
- Explore order channels and fulfillment performance
- Prepare the dataset for future modeling or dashboarding

---

## 🧾 Dataset Overview

The dataset contains over **128,000 orders**, including fields such as:
- Order ID, Date, Status, Fulfillment
- Product SKU, Category, Size
- Quantity and Amount
- Shipping details and channel

Data has been cleaned to remove duplicates, standardize formats, and handle missing values.

---

## 📈 Key Insights

- Most orders are low in value but high in frequency (B2C pattern)
- A few products (SKUs) contribute disproportionately to total revenue
- One sales channel (Amazon.in) dominates the activity
- Seasonal spikes in monthly revenue reveal potential peak sales periods

---

## 📁 Project Structure

```
ecommerce-amazon-analysis/
├── Dataset/                         # Raw or cleaned CSVs
├── Graph/                           # The graphics obtained in the notebook
├── profitability_analysis.ipynb  # The notebook file
├── requirements.txt              # Python environment setup
├── README.md                     # Project overview
```

---

## 🛠️ Tools Used

- Python · Pandas · Seaborn · Matplotlib
- Jupyter Notebook · IPython Kernel

---

## ▶️ Run this project locally

1. Clone the repository
2. Install the dependencies

```bash
pip install -r requirements.txt
```

3. Launch the notebook

```bash
jupyter notebook notebooks/profitability_analysis.ipynb
```

---

## 🔗 Author

**Thienel Kane**  
*Data Analyst in progress – passionate about Python, SQL and turning data into insights.*

📍 Also available on:
- [GitHub](https://github.com/thienelkane)
- [Kaggle](https://www.kaggle.com/thienelkane)

---

## 📜 License

This project is shared for educational purposes.