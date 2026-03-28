[📄 Click here to view Report](./Customer_service_compressed.pdf)
This project analyzes the NYC 311 service request dataset to identify major complaint patterns, understand city-wise distribution, and evaluate response time efficiency using Python, data visualization, and statistical techniques.
The objective is to extract meaningful insights that can help improve public service operations and decision-making.
Objectives
Identify major complaint types
Analyze complaint distribution across cities
Evaluate response time for different complaint categories
Detect geographical complaint hotspots
Perform statistical analysis to validate findings
 Tools & Technologies
Python
Pandas & NumPy
Matplotlib & Seaborn
SciPy (Statistical Analysis)
Jupyter Notebook
 Key Analysis Performed
🔹 Data Cleaning
Removed records with missing Closed Date
Handled missing values in City column
Converted date columns into proper datetime format
Removed incorrect records where Closed Date < Created Date
🔹 Exploratory Data Analysis (EDA)
Frequency distribution of complaint types
City-wise complaint analysis
Top 10 complaint categories
Bar charts and stacked visualizations
🔹 Response Time Analysis
Calculated time difference between Created and Closed Date
Converted response time into seconds
Identified complaint types with highest and lowest resolution time
🔹 Geographical Analysis
Scatter and hexbin plots used to identify complaint concentration
Highlighted high-density areas such as Brooklyn
🔹 Statistical Analysis
Applied ANOVA test to compare response times across complaint types
Used the Kruskal-Wallis H test for non-parametric validation
Determined statistical significance using p-values
Key Insights
A few complaint types dominate the dataset (e.g., noise, parking issues)
Complaint distribution varies significantly across cities
Response time differs across complaint types
High complaint density observed in specific locations
Statistical tests confirm that differences are significant
