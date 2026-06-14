# 🔥 Indian Developer Burnout Analysis

## 📌 Project Overview

This project explores burnout trends among Indian developers using data analysis and visualization techniques. The objective is to identify patterns related to burnout levels across different demographics and provide meaningful insights into factors affecting developer well-being.

\---

## 🎯 Objectives

* 🧹 Clean and preprocess the dataset
* 📊 Analyze burnout levels among Indian developers
* 🏷️ Categorize burnout scores into meaningful groups
* 📈 Visualize key patterns and trends
* 💡 Generate actionable insights from the data

\---

## 📂 Dataset Information

The dataset contains information about Indian developers, including:

* Age
* Gender
* Burnout Score
* Work-related factors
* Lifestyle indicators
* Other demographic attributes

\---

## 🛠️ Technologies Used

|Tool|Purpose|
|-|-|
|Python|Core programming language|
|Pandas|Data manipulation \& cleaning|
|Matplotlib|Plotting \& visualization|
|Seaborn|Statistical data visualization|
|Jupyter Notebook|Interactive development environment|

\---

## 🗂️ Project Structure

```
Indian\\\_Developer\\\_Burnout\\\_Analysis/
│
├── Data/
│   └── indian\\\_developer\\\_burnout\\\_2026.csv
│
├── Outputs/
│   ├── Visualizations/
│   │   ├── burnout\\\_category.png
│   │   ├── age\\\_distribution.png
│   │   └── gender\\\_distribution.png
│   │
│   └── Processed\\\_Data/
│       └── cleaned\\\_burnout\\\_data.csv
│
├── Indian\\\_Developer\\\_Burnout\\\_Analysis.ipynb
├── burnout\\\_analysis.py
├── README.md
└── requirements.txt
```

\---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* ✅ Removed duplicate records
* ✅ Handled missing values in critical columns
* ✅ Cleaned and standardized text-based columns
* ✅ Filtered invalid age values (18–65 years)
* ✅ Filtered burnout scores outside the valid range (0–10)
* ✅ Created burnout categories:

  * 🟢 **Low Burnout** — Score 0–3
  * 🟡 **Moderate Burnout** — Score 4–6
  * 🔴 **High Burnout** — Score 7–10

\---

## 📊 Visualizations

The project includes the following visualizations:

1. **📊 Burnout Category Distribution**

   * Shows the number of developers in each burnout category (Low / Moderate / High)
2. **📈 Age Distribution of Indian Developers**

   * Displays the age spread using a histogram with a KDE curve
3. **👥 Gender Distribution of Indian Developers**

   * Illustrates the proportion of developers across gender groups

\---

## 💡 Key Insights

* 📌 Burnout levels vary significantly across different demographic groups
* 📌 A notable portion of developers fall in the **Moderate to High** burnout range
* 📌 Age and gender show distinct patterns in burnout distribution
* 📌 Understanding these trends can help organizations promote healthier work environments and improve employee well-being

\---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SriyaPatil/Indian\\\_Developer\\\_Burnout\\\_Analysis.git
cd Indian\\\_Developer\\\_Burnout\\\_Analysis
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

Open `Indian\\\_Developer\\\_Burnout\\\_Analysis.ipynb` in Jupyter and run all cells.

Or run the Python script directly:

```bash
python burnout\\\_analysis.py
```

\---

## 📤 Outputs

Generated outputs are saved in:

* 📁 `Outputs/Visualizations/` — All chart images
* 📁 `Outputs/Processed\\\_Data/` — Cleaned dataset CSV

\---

## 👩‍💻 Author

**Sriya Patil**

Linkedin: https://linkedin.com/in/sriya-patil-63240332a

