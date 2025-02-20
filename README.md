This project is designed that explains big-data processing and machine-learning models using a real-world dataset. 
I used the historical stock prices of Nvidia from July 1, 2022, to July 31, 2024. 
The dataset contains the following features: Date; Open price; Intraday high and low prices; Close price; Adjusted close price; Trading volume. You will apply data cleaning, preprocessing, visualization, and machine learning techniques such as clustering using KMeans.
Things that has been covered:

Part 1: Big Data Processing

Task 1: Data Cleaning and Exploration 
1. Load the dataset into a Pandas DataFrame and print the meta data of column information.
2. Check for missing values and handle them appropriately. 
3. Convert the date column to a different datetime format and print it.
4. Compute basic statistics (min, max, mean, median, standard deviation) for each numerical feature.
5. Plot the closing price over time using Matplotlib.
   
Task 2: Feature Engineering 
1. Create a new column for daily returns based on the adjusted closing price (0 for the first day) and
and print the top 10 dates with the highest daily return.
2. Create a new column for the 7-day moving average of the closing price and plot it with Matplotlib.
(any proper filling way of the first 6 days is acceptable)
3. Normalize Trading volume column using Min-Max Scaling and print the top 10 dates with the
highest volume.

Task 3: Data Visualization
1. Create a histogram of daily returns.
2. Generate a boxplot of the trading volume.
3. Display a correlation heatmap of all numerical features. 

Part 2: Machine Learning 
Task 1: Clustering with KMeans 
1. Select relevant features for clustering (e.g., normalized daily return, trading volume, and adjusted
close price).
2. Determine the optimal number of clusters using the elbow method.
3. Apply KMeans clustering and visualize the resulting clusters using a scatter plot.
4. Interpret the clusters and describe potential insights.
