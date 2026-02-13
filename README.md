# B211_Assignment-3

Purpose of the Program:
- Analyzes Fisher's Iris dataset to understand the physical traits of 3 different species of irises to distinguish them..

Design and Implementation:
- A FlowerDataAnalyzer class was implemented to handle data loading, cleaning, and calculating the required statistics.
- Class Attributes = 'data_frame' (Pandas DataFrame that stores the combined Iris dataset).

Methods:
-  `load_data(csv_path)`= Loads and merges data.
- `calculate_correlation()`= Computes Pearson correlation between variables.
- `calculate_average()`= Returns mean values grouped by species.
- `calculate_median()`= Returns median values grouped by species.
- `calculate_std_dev()`= Returns standard deviation grouped by species.

Limitations:
- The dataset assumes only 50 samples per species.
- The analysis relies on linear assumptions (Pearson correlation).
- Data represents only three specific Iris species.

Results:
- There is a very strong positive correlation between petal length and petal width (> 0.95), and a strong positive correlation between petal length and sepal length.
- Petal Length & Petal Width: ~0.96
- Sepal Length & Petal Length: ~0.87
- Sepal Length & Petal Width: ~0.82
- Petal Length & Sepal Width: ~-0.43
- Sepal Length & Sepal Width: ~-0.11
- Petal Width & Sepal Width: ~-0.37

Measurements:

Average of Each Variable (All Species):
- Sepal Length: 5.84 cm
- Sepal Width: 3.06 cm
- Petal Length: 3.76 cm
- Petal Width: 1.20 cm

Median of Each Variable (All Species):
- Sepal Length: 5.80 cm
- Sepal Width: 3.00 cm
- Petal Length: 4.35 cm
- Petal Width: 1.30 cm

Standard Deviation of Each Variable (All Species):
- Sepal Length: 0.828 cm
- Sepal Width: 0.434 cm
- Petal Length: 1.765 cm
- Petal Width: 0.762 cm

Iris versicolor and Iris virginica are the most similar. Although virginica is generally larger, their measurements overlap, making them harder to distinguish than Iris setosa. Iris setosa is the least similar to the other two, as it has much smaller petal lengths and width compared to Versicolor and Virginica.
