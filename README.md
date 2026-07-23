# 🦠 COVID-19 Analysis and Visualization using Plotly Express

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Visualization-3F4F75?logo=plotly)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** and interactive visualization of the **COVID-19 pandemic** using **Python** and **Plotly Express**. It analyzes worldwide COVID-19 data to identify trends in confirmed cases, deaths, recoveries, and active cases.

Interactive charts generated using Plotly Express provide an intuitive understanding of the spread of COVID-19 across different countries and regions.

This project is based on the GeeksforGeeks tutorial:

**COVID-19 Analysis and Visualization using Plotly Express**

---

## 🎯 Objectives

- Analyze worldwide COVID-19 data.
- Clean and preprocess the dataset.
- Perform exploratory data analysis.
- Visualize pandemic trends using interactive charts.
- Compare countries based on confirmed cases, deaths, and recoveries.
- Generate meaningful insights from the data.

---

## 📂 Project Structure

```
Covid-19-Analysis-and-Visualization-using-Plotly-Express/
│
├── covid.csv
├── covid_grouped.csv
├── coviddeath.csv
├── Covid_19_Analysis_and_Visualization_using_Plotly_Express.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset

This project uses three CSV datasets containing worldwide COVID-19 statistics. You can download them using the links below.

| Dataset | Description | Download Link |
|----------|-------------|---------------|
| **covid.csv** | Raw COVID-19 dataset containing country-wise statistics | https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210903231151/covid.csv |
| **covid_grouped.csv** | Grouped COVID-19 dataset used for trend analysis and visualizations | https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210903231231/covid_grouped.csv |
| **coviddeath.csv** | COVID-19 death statistics dataset | https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210903231305/coviddeath.csv |

### Dataset Features

The datasets include information such as:

- Country/Region
- Province/State
- Latitude & Longitude
- Observation Date
- Confirmed Cases
- Death Cases
- Recovered Cases
- Active Cases
- Daily Case Counts
- Country-wise Aggregated Statistics

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Plotly Express
- Plotly Graph Objects

---

## 📦 Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/COVID-19-Analysis-Visualization.git
```

Go inside the project folder.

```bash
cd Covid-19-Analysis-and-Visualization-using-Plotly-Express
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open:

```
Covid_19_Analysis_and_Visualization_using_Plotly_Express.ipynb
```

---

## 📈 Data Analysis Workflow

### 1. Import Libraries

- Pandas
- NumPy
- Plotly Express
- Plotly Graph Objects

---

### 2. Load Dataset

- Read CSV file
- Inspect data
- Check missing values

---

### 3. Data Cleaning

- Remove unnecessary columns
- Handle null values
- Convert date columns
- Aggregate country-wise statistics

---

### 4. Exploratory Data Analysis

- Total confirmed cases
- Total deaths
- Total recoveries
- Active cases
- Country-wise analysis
- Top affected countries

---

### 5. Interactive Visualizations

The notebook generates interactive visualizations such as:

- 📈 Line Charts
- 📊 Bar Charts
- 🥧 Pie Charts
- 🌍 Choropleth World Maps
- 📍 Scatter Geo Maps
- Bubble Charts

---

## 📌 Key Insights

- Countries with the highest confirmed COVID-19 cases.
- Countries reporting the highest number of deaths.
- Recovery trends across different regions.
- Active case distribution worldwide.
- Geographic visualization of pandemic spread.
- Comparative analysis of confirmed vs recovered cases.

---

## 📊 Libraries Used

```text
pandas
numpy
plotly
jupyter
```

---

## 🚀 Future Improvements

- Add vaccination data analysis.
- Build an interactive Streamlit dashboard.
- Integrate real-time COVID-19 APIs.
- Perform time-series forecasting.
- Add machine learning models for prediction.
- Include continent-wise comparisons.

---

## ▶️ Example Output

```
Total Confirmed Cases : XXXXXXXX

Total Death Cases : XXXXXXX

Total Recovered Cases : XXXXXXX

Top 10 Most Affected Countries
--------------------------------
1. USA
2. India
3. Brazil
4. Russia
...
```

---

## 📚 Learning Outcomes

After completing this project, you will understand:

- Data preprocessing using Pandas
- Exploratory Data Analysis
- Interactive visualization using Plotly Express
- Geographic visualization
- Dashboard creation
- Data storytelling
- Working with real-world datasets

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit changes.

```bash
git commit -m "Add feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is intended for educational and learning purposes.

MIT License.

---

## 👨‍💻 Author

**Ajinkya Dhatrak**

GitHub: https://github.com/ajinkya029