# Zomato Data Analysis Project

This project analyzes a Zomato restaurant dataset to uncover insights about customer preferences, restaurant ratings, spending habits, and trends in online and offline orders. The insights derived from this analysis can help improve business strategies and customer satisfaction on the Zomato platform.

---

## Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Analysis and Insights](#analysis-and-insights)
- [Results](#results)
- [How to Use](#how-to-use)
- [Contributors](#contributors)

---

## Overview

The Zomato Data Analysis Project is a comprehensive study of restaurant data from Zomato. It aims to answer key business questions, including:
- Which restaurant types are most popular?
- How do votes vary by restaurant type?
- What are the most common ratings given by customers?
- How much do couples typically spend on food?
- Do online orders receive higher ratings than offline orders?
- Which restaurant types receive more offline orders?

---

## Dataset Description

The dataset used in this project contains the following columns:

| **Column Name**     | **Description**                                       |
|----------------------|-------------------------------------------------------|
| `restaurant_name`    | Name of the restaurant                                |
| `rate`               | Customer rating (out of 5)                           |
| `votes`              | Number of customer votes                             |
| `cost_for_two`       | Approximate cost for two people (in local currency)  |
| `restaurant_type`    | Type of restaurant (e.g., Dining, Cafe, etc.)         |
| `online_order`       | Whether the restaurant accepts online orders (Yes/No)|

The data includes real-world inconsistencies such as missing values and invalid ratings, which are handled in the data cleaning process.

---

## Technologies Used

The project leverages the following tools and libraries:

- **Python**: Core programming language for analysis
- **Pandas**: Data cleaning and manipulation
- **NumPy**: Numerical computation
- **Matplotlib**: Visualization of data trends
- **Seaborn**: Enhanced and aesthetically pleasing visualizations
- **Jupyter Notebook**: Interactive environment for coding and visual analysis

---

## Setup and Installation

Follow these steps to set up and run the project on your local machine:

### Prerequisites
1. Install Python (preferably 3.8 or later).
2. Install a package manager like `conda` or `pip`.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Zomato-Data-Analysis.git
   cd Zomato-Data-Analysis
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `zomato_data_analysis.ipynb` file and run the cells sequentially.

---

## Analysis and Insights

The project performs the following key analyses:

1. **Restaurant Type Distribution**: Identifies the most common restaurant types using bar charts.
2. **Votes by Restaurant Type**: Summarizes customer engagement through a line graph of votes by type.
3. **Rating Distribution**: Visualizes the spread of customer ratings through histograms.
4. **Average Spending by Couples**: Examines spending trends and preferences of couples.
5. **Online vs Offline Ratings**: Compares customer ratings for online and offline orders using box plots.
6. **Offline Order Trends**: Highlights restaurant types receiving more offline orders through heatmaps.

---

## Results

The analysis revealed several actionable insights:

- **Dining restaurants** dominate the platform, receiving the highest votes and orders.
- The majority of restaurants are rated between **3.5 to 4** stars.
- Couples typically spend around **₹300** on average.
- **Online orders** tend to receive better ratings compared to offline orders.
- Offline orders are more prevalent in dining-type restaurants, suggesting an opportunity for targeted promotions.

---

## How to Use

1. Clone this repository and follow the installation steps.
2. Run the Jupyter Notebook to explore the dataset and visualizations.
3. Modify the analysis or visualizations as needed for custom insights.

---

## Contributors

Feel free to contribute to this project by submitting issues or pull requests.
