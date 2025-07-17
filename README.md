# GDP Per Capita Analysis – Python & Pandas Project

## 🎯 What I Built
In this Python project from my justIT Data Skills Bootcamp, I analyzed a dataset of nominal GDP per capita for countries worldwide. I used the pandas library to perform essential data cleaning and then used Matplotlib/Seaborn to visualize the top-performing countries.

#### The top 5 countries by World Bank estimates
<img width="883" height="461" alt="GDP-top5-countries-WorldBank-estimates" src="https://github.com/user-attachments/assets/7fa2dbd3-539a-411f-9c70-ad4b209ae1ca" />

## 💡 Key Things I Learnt
- **Data Cleaning**: The dataset used `0` to represent missing estimates. I learned how to replace these zeros with `NaN` (Not a Number) to ensure they were excluded from calculations, preventing incorrect results (like a `0` average).
- **Data Sorting and Ranking**: I practiced using `.sort_values()` to rank the countries and `.head(5)` to select the top 5 for my analysis.
- **Data Visualization**: I used Matplotlib and Seaborn to create a horizontal bar chart, which is an effective way to display and compare ranked data like this.
- **Handling Inconsistent Data**: I learned to work with a real-world dataset where different organizations (IMF, World Bank, UN) provide slightly different estimates for the same metric.

## 🔍 Top Insights
| Insight | Evidence | Economic Takeaway |
|---|---|---|
| European nations dominate the top rankings | The bar chart shows that a majority of the top 10 countries by GDP per capita are small, wealthy European nations like Monaco, Liechtenstein, Luxembourg, and Switzerland. | This highlights that high national wealth is often concentrated in smaller countries with specialized economies, such as finance or technology. |
| Data requires cleaning before analysis | An initial `.describe()` on the raw data would show a minimum value of 0 for GDP, which is impossible. This was caused by missing data being entered as `0`. | This reinforces a critical lesson in data analysis: always inspect and clean your data first. Trusting raw data without validation leads to flawed conclusions. |

#### Python code used to replace 0 values with NaN for accurate analysis
<img width="586" height="551" alt="GDP-data-cleaning-with-results" src="https://github.com/user-attachments/assets/22fc65aa-6120-4a72-b031-f9f6add8c3d9" />

## 🛠️ Python Skills Demonstrated
- **Libraries**: pandas, NumPy, Matplotlib, Seaborn
- **Data Cleaning**: `df.replace()`, handling `NaN` values
- **Data Manipulation**: `.sort_values()`, `.head()`
- **Data Visualization**: `seaborn.barplot()`, customizing chart titles and labels

## 🚀 How to Explore
1.  Ensure you have Python and the libraries listed above installed.
2.  Download the `GDP-dataset-notebook.ipynb` and the `GDP (nominal) per Capita.xlsx` file.
3.  Place them in the same directory.
4.  Open and run the Jupyter Notebook to follow the analysis from cleaning to visualization.

## 📁 Project Files
- `GDP-dataset-notebook.ipynb` - The Jupyter Notebook with all the Python code.
- `GDP (nominal) per Capita.xlsx` - The raw dataset.
- the project screenshots.
- `README.md` - This guide.

## 🎓 Part of My Bootcamp Journey

## 🤔 If I Had More Time
- I would calculate the average GDP per capita for each `UN_Region` to compare economic performance across different parts of the world.
- I would create a new column that calculates the average of the IMF, World Bank, and UN estimates to create a more robust, combined metric for each country.

---
*Week 7 of 8 – justIT Data Skills Bootcamp*
