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
 Gained hands-on experience of working on data with Python libraries.

 Gained data pre-processing as well as data cleaning for analysis.

 Gained knowledge about strength of interpretation as well as data visualization using
   appropriate graphical representation.
   
 Gained practice of working on external libraries like Deep Translator for data translation.

 Improved understanding of environmental news and trends of Amazon rainforest forest fires.
