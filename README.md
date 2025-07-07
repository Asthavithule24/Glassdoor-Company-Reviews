# Glassdoor-Company-Reviews
Report: Analysis of Glassdoor Companies Review Dataset
Introduction: The proliferation of online platforms like Glassdoor has revolutionized the way job seekers assess potential employers. This report presents an in-depth analysis of the Glassdoor company reviews dataset, obtained through web scraping techniques. We explore various aspects of the dataset, including overall ratings, factors affecting ratings, and top-rated companies across different industry sectors. The objective is to provide insights that can inform both job seekers and employers in their decision-making processes.
Methodology:

1.	Data Collection: The dataset used in this analysis was obtained through web scraping from Glassdoor. It includes various attributes such as company ratings, employee reviews, and company details.
2.	Data Processing:
•	The data was loaded from the provided CSV file using Pandas 'read_csv’ function.
•	Preprocessing steps were performed to clean the data, including dropping irrelevant columns, handling missing values, and categorizing variables.
3.	Data Analysis:
•	Summary statistics were calculated to understand the dataset's characteristics.
•	Visualizations were created to explore relationships and distributions within the data, including histograms, heatmaps, boxplots, and bar charts.
•	Top-performing companies were identified based on their overall ratings.
4.	Report Generation:
•	A report was generated summarizing the analysis findings, including insights into company ratings, factors influencing ratings, and top-performing companies.
Libraries Used:
•	NumPy (np): Used for numerical operations.
•	Pandas (pd): Utilized for data manipulation and analysis.
•	Seaborn (sb): Employed for statistical data visualization.
•	Matplotlib.pyplot (plt): Used for creating visualizations.

  

Data Processing:
•	The data was loaded from the provided CSV file using Pandas' read_csv function.
•	Preprocessing steps were performed to clean the data, including:
•	Dropping irrelevant columns containing 'url' or 'count'.
•	Dropping specific columns that were not needed for analysis.
•	Handling missing values by filling them with the mean.
•	Splitting the 'details_headquarters' column into 'headquarters' and 'headquarter_country'.
•	Converting timestamps to datetime format and calculating recency.
•	Applying custom functions to categorize rating, decision, difficulty, and company size.

Data Analysis:
•	Summary statistics were calculated to understand the dataset's characteristics.
•	Visualizations were created to explore relationships and distributions within the data, including:
•	Histogram of overall ratings distribution.
•	Heatmap showing correlations between different rating aspects.
•	Boxplot depicting the distribution of ratings across company types.
•	Bar charts displaying ratings distribution across different aspects for each company type.
•	Identification of top companies with the highest overall ratings.
•	Count of reviews for each company type.
•	Visualization of top companies in each category based on overall ratings.

1.	Histogram of overall ratings distribution:
 
![image](https://github.com/user-attachments/assets/df688da3-2e29-44a1-93d2-28f85c279a4f)


2.	Boxplot depicting the distribution of ratings across company types:
   
 ![image](https://github.com/user-attachments/assets/59b250ed-55fe-4504-bf03-58cbcc13bd5b)


3.	Bar chart displaying ratings distribution of work-life Balance:
   
 ![image](https://github.com/user-attachments/assets/0b0b86d7-6581-4af1-8df0-f2a77cc5e12f)


Conclusion: The analysis provides insights into the Glassdoor companies review dataset, highlighting key factors influencing ratings and identifying top-performing companies across different categories. Further exploration and analysis can be conducted to gain deeper insights into employee experiences and company performance.

