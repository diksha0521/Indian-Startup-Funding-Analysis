Here’s a clean, professional **README.md** for your `main.py` script:

---

# Startup Funding Analysis

This project analyzes a startup funding dataset to identify trends, top sectors, cities, startups, investors, and investment types. It also visualizes the funding trends over time and other key insights using `matplotlib` and `seaborn`.

## 📂 Project Structure

```
main.py                # Main analysis script
startup_funding.csv    # Dataset (replace with actual path in your environment)
```

## 🚀 Features

* **Data Cleaning & Preprocessing**

  * Standardizes date formats.
  * Removes or fills null values.
  * Normalizes text columns for consistent formatting.
  * Fixes typos in column names.
  * Converts funding amounts to numeric format.

* **Data Analysis**

  * Calculates **funding trends** over time (monthly).
  * Identifies **top sectors**, **top cities**, and **top startups** (by count and total funding).
  * Extracts **top investors** based on investment frequency.
  * Counts **investment types**.

* **Data Visualization**

  * Funding trend over time (monthly).
  * Top sectors bar chart.
  * Top investors bar chart.

## 🛠️ Requirements

Install dependencies using:

```bash
pip install pandas matplotlib seaborn
```

## 📊 Usage

1. Place the `startup_funding.csv` file in your working directory or update the path in `main.py`.
2. Run the script:

```bash
python main.py
```

3. The script will display:

   * Data previews.
   * Key metrics and top rankings.
   * Interactive visualizations.

## 📈 Example Visualizations

* **Funding Trend Over Time (Monthly)**
* **Top Sectors**
* **Top Investors**

## 📝 Notes

* Ensure the dataset contains the required columns:

  * `Date dd/mm/yyyy`
  * `Startup Name`
  * `City Location`
  * `Industry Vertical`
  * `Amount in USD`
  * `Investors Name`
  * `Investment Type`
* Missing or incorrect column names may require adjustments in the script.

---

Do you want me to also **add screenshots of the charts** in this README so it looks more professional? That could make it visually appealing.
# Indian-Startup-Funding-Analysis
