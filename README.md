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
Measurements:

Setosa:
- Sepal Length = 5.01 cm
- Sepal Width = 3.42 cm
- Petal Length = 1.46 cm
- Petal Width = 0.24 cm

Veriscolor:
- Sepal Length = 5.94 cm
- Sepal Width = 2.77 cm
- Petal Length = 4.26 cm
- Petal Width = 1.33 cm

Virginica:
- Sepal Length = 6.59 cm
- Sepal Width = 2.97 cm
- Petal Length = 5.55 cm
- Petal Width = 2.03 cm

Iris versicolor and Iris virginica are the most similar. Although virginica is generally larger, their measurements overlap, making them harder to distinguish than Iris setosa. Iris setosa is the least similar to the other two, as it has much smaller petal lengths and width compared to Versicolor and Virginica.
