# python_zomato_analysis

This project analyzes the Zomato restaurants in India dataset

Overview This project analyzes the zomato_restaurants_in_India.csv dataset. The dataset includes various features of restaurants such as restaurant ID, name, establishment type, location, ratings, price range, and more. The analysis includes data cleaning, visualization, and statistical analysis to derive insights about the restaurants listed on Zomato in India.

Dataset The dataset zomato_restaurants_in_India.csv consists of the following key columns:

res_id: Restaurant ID name: Restaurant Name establishment: Type of establishment url: Zomato URL of the restaurant address: Address of the restaurant City: City where the restaurant is located locality: Locality of the restaurant latitude and longitude: Geographical coordinates aggregate_rating: Aggregate rating of the restaurant rating_text: Textual rating votes: Number of votes price_range: Price range of the restaurant highlights: Key features of the restaurant cuisines: Types of cuisines offered Key Analysis Steps Data Loading and Inspection: The script starts by uploading the dataset and inspecting the first few rows using Pandas.

Data Cleaning:

Outliers in aggregate_rating and price_range are removed using the Interquartile Range (IQR) method. Irrelevant columns like zipcode and timings are dropped.

Data Visualization:

Histograms and count plots are created to visualize the distribution of aggregate_rating and price_range. A count plot is used to show the distribution of the top 10 cuisines.

Statistical Analysis:

Descriptive statistics are calculated for numerical and categorical data. Further analysis includes calculating range, skewness, and kurtosis for select columns. A correlation heatmap is plotted to understand the relationships between different numerical features.

City-wise Analysis:

A detailed analysis of top cities is conducted, including the distribution of restaurant types, popular cuisines, average ratings, and customer engagement metrics.

Region-wise Visualization:

A bar plot is created to display the top 10 regions with the most restaurants.

Usage To use this script:

Ensure you have Python installed along with Pandas, Seaborn, and Matplotlib libraries. Load the dataset zomato_restaurants_in_India.csv. Run the script to perform the analysis and generate the visualizations.

Conclusion This project provides a thorough analysis of the Zomato restaurants dataset, offering valuable insights into various aspects of the restaurants listed on Zomato in India. The visualizations and statistical analysis are crucial for understanding the preferences and distribution of restaurants in different cities and regions.
