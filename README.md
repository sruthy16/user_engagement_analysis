# Project Overview:

This Python script analyzes user engagement data from a CSV file named 'showwcase_sessions.csv.' The analysis involves data preprocessing, exploration, and visualization using various libraries like Pandas, NumPy, Seaborn, Matplotlib, and Bokeh. The key tasks performed in the script include:

Data Preprocessing: Loading the CSV data into a Pandas DataFrame, handling missing values, and creating frequency distributions based on customer IDs.

User Engagement Assessment: Identifying and removing rows where users have only one recorded session to focus on recurring users for a better understanding of user engagement patterns.

Session Duration Analysis: Determining the range of session durations and calculating maximum, minimum, and Mean Absolute Deviation (MAD) values.

Correlation Analysis: Investigating the correlation between active session duration and the number of bugs occurred, visualized through a scatter plot.

Grouping Data: Grouping data by customer ID to analyze the total number of reactions (projects added) per customer.

Pie Charts: Creating pie charts to visualize the distribution of bugs in sessions and the number of projects added.

Date-wise Analysis: Counting the number of sessions per day and exploring trends in user logins over time through line plots.

3D Plot Experiment: Experimenting with an alternative way of modeling data using a 3D bar plot.

This script provides insights into user engagement patterns, session duration trends, and correlations between different metrics. The visualizations enhance the understanding of user behavior and help in making data-driven decisions.
