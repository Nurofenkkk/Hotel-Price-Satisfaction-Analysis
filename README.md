# Hotel-Price-Satisfaction-Analysis

Tools Used: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook, Power BI, Excel
Dataset: Combined hotel, weather, and currency exchange data (Excel format)
## 📌 Project Summary
This project analyzes the relationship between hotel accommodation prices and customer satisfaction, along with other factors such as weather and exchange rates. The workflow includes:


## Data Integration:

Merged three datasets: hotel information, meteorological data, and currency exchange rates.
Cleaned and standardized rating categories (e.g., replaced "průměr" with "nespokojen").



## Exploratory Data Analysis:

Scatter plots and boxplots of accommodation price vs. hotel rating.
Pivot tables showing average accommodation price by rating.
Segmentation of total price into three groups (Expensive, Medium, Cheap) using qcut.



## Statistical Analysis:

Chi-square test for independence between expensive stays and overall satisfaction.
Result: No significant dependence at p < .05. Interestingly, customers who paid more were slightly less satisfied.



## Visualization:

Power BI dashboard with:

Price by rating.
Service evaluation (personal, food, accommodation, fun).
Interactive filters (price range, date, accommodation type, age, persons count).
Geographic maps and temperature distribution.

