# Amazon-Forest-Fires

# Tools Used:
 Python : The primary programming language used for data analysis and modeling.

 Pandas : For data manipulation and preprocessing.

 NumPy : For numerical operations on datasets.

 Deep Translator : For translation of the text.

 Matplotlib : For data visualization to understand patterns and trends.

 Jupyter Notebook : As the development environment for coding and documentation.


# Working Procedure:
 Data Import:
1. Imported dataset from "amazon.csv" using pandas.read_csv() with the given encoding.
   
 Basic Data Inspection:
1. Displayed the initial few rows of the dataset using df.head().
2. Shown the last few rows by executing df.tail().
3. Confirmed the shape of the dataset using df.shape.
   
 Descriptive Statistics:
1. Created statistical summaries by executing df.describe() for numerical data.
2. Confirmed missing values by executing df.isna().sum()
   
 Data Cleaning:
1. Replaced zeros with NaN in the number column.
2. Dropped rows with missing values from the number column to get a cleaned dataframe df2.
   
 Data Aggregation:
1. Sorted and aggregated data by month and counted forest fires with groupby.
2. Created a list of unique months for sequential occurrence in plots.
   
 Data Visualization:
1. Plotted a bar chart with Matplotlib to visualize forest fires by month.
2. Title assigned on the graph with fires count above the bars.


# Learning Outcomes:
 Data Manipulation and Cleaning:  
1. Gained proficiency in handling missing values and outliers using pandas.
2. Learned how to encode categorical variables for machine learning models.
   

 Exploratory Data Analysis:  
1. Developed skills in using matplotlib, seaborn, and plotly for data visualization.
2. Understood the importance of EDA in identifying patterns and insights in the data.
   

 Machine Learning:  
1. Learned how to prepare data for regression models.
2. Gained experience in training and evaluating regression models using scikit-learn.
3. Understood the significance of metrics like R² Score and Mean Squared Error in assessing model performance.
   

 Project Management:  
1. Practiced organizing a complete data science project, from data loading to model evaluation.
2. Improved skills in documenting and presenting findings using Jupyter Notebook.
         
     
