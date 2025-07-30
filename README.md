# 📊 Google Play Store Apps Analysis

## 📚 Project Overview

Welcome to the **Google Play Store Apps Analysis** project!  
This repo dives deep into Play Store data using Python, unlocking insights about app popularity, pricing, ratings, and user sentiment. Whether you’re an **app developer, marketer, or data enthusiast**, discover what makes apps succeed!

## ✨ Features

- 🛠️ **Data Cleaning & Transformation** – Fixes missing values and standardizes formats for robust analysis.
- 📈 **Exploratory Data Analysis (EDA)** – Visualizes ratings, installs, prices, and categories with stunning plots.
- 💰 **Revenue & Popularity Metrics** – Calculates estimated revenue and a custom popularity score.
- 🗂️ **Category Analysis** – Compares ratings and pricing across app categories.
- 😊 **Sentiment Analysis** – Merges user reviews to analyze and score overall sentiment.
- 🎨 **Advanced Visualizations** – Beautiful charts: histograms, box plots, bar charts, and scatterplots.
- ⚙️ **Feature Engineering** – Adds metrics like days since last update and reviews-per-install ratio.

## 📁 Folder Structure

```
.
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
├── analysis.py
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

### 📂 Datasets

- `googleplaystore.csv` – Info about apps.
- `googleplaystore_user_reviews.csv` – User reviews & sentiment.

### ▶️ Usage

1. **Clone** the repo, add both CSVs and `analysis.py` to your directory.
2. Run the script:

    ```bash
    python analysis.py
    ```

3. Watch as the script:
    - Cleans/processes both datasets 🧹
    - Engineers new features 📏
    - Generates awesome visualizations 📊 (saved or interactive)
    - Prints insights and previews data 💡

## 📤 Outputs & Insights

- 🟪 **Histograms**: Price & ratings distributions.
- 🔵 **Scatter Plot**: Installs vs revenue.
- 🟧 **Box Plot**: Prices by category.
- 🟩 **Bar Charts**: Stacked sentiment per app.
- 🧾 **Tables**: Processed data, averages, and content analysis.

## 🌟 Example Key Findings

- Top categories by average rating 🏆
- Most common paid app price tags 💵
- Any relationship between installs & revenue 🔄
- Apps with the happiest (and least happy) users 🎭

## 🛠️ Customization

Super modular!  
Edit, expand, or add models—like regression or classification—for extra ML power. Make it your own!

## 🤝 Contributing

Pull requests welcome! For big changes, please open an issue for discussion.

