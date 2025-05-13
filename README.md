# Sales_Dashboard
 # Interactive Sales Performance Dashboard

This is a responsive and interactive sales dashboard built using **HTML**, **JavaScript**, and **Plotly.js**. It allows users to upload a JSON file and instantly visualize key sales insights through dynamic charts.

> **Built with modern design (Glassmorphism) and no backend required — everything runs in your browser.**

---

## Features

- **Upload Feature:** Upload your own JSON sales file from your device.
- **Interactive Visualizations:** Charts auto-generate based on uploaded data.
- **Glassmorphism UI:** Clean, modern look with icy blue background and soft blur effects.
- **Visual Metrics Included:**
  - Total Spend by Product Category (Bar chart)
  - Customer Purchase Frequency Distribution (Pie chart)
  - Spend vs Transactions (Scatter plot)
  - Total Spend Over Time (Line chart)
  - Payment Method by Product Category (Stacked Bar)

---

## Technologies Used

- **HTML5**
- **Vanilla JavaScript**
- **[Plotly.js](https://cdn.plot.ly/plotly-latest.min.js)** for charting
- **CSS** (Glassmorphism styling)

---

## How to Use

1. Open the `index.html` file in your browser.
2. Click **Browse** to upload your JSON sales data.
3. Instantly view interactive visualizations based on your data.

---

## Sample Data Format

```json
[
  {
    "Customer_ID": "abc123",
    "Age": 45,
    "Gender": "Female",
    "Location": "City Name",
    "Total_Transactions": 15,
    "Total_Spend_USD": 1200.50,
    "Purchase_Frequency": "Medium",
    "Last_Purchase_Date": "2024-11-21",
    "Product_Category": "Electronics",
    "Payment_Method": "Credit Card"
  }
]
``

## License

This project is open-source and free to use.
