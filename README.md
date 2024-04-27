# EV's Market Segmentation
This project aims to perform data segmentation using customer data of Vehicle Sold Data. By applying segmentation techniques, we can identify distinct customer segments based on various characteristics such as purchasing behavior, preferences, demographics, and more. The resulting segments can then be used to tailor marketing strategies, optimize product offerings, and enhance customer experiences.

## Data Preprocessing
The preprocessing of the dataset is a crucial step to ensure data quality and prepare it for analysis. In this project, the following steps were undertaken for data preprocessing:

1. **Dropping Entries with Missing Data**:
   - Entries with missing values in any of the selected features were dropped from the dataset to ensure data completeness.

2. **Postfix Removal from Columns**:
   - Columns containing postfixes (e.g., 'BHP', 'CC') were modified to remove the postfixes and convert the data to numerical format.

3. **Conversion of Float Columns to Integer**:
   - Columns such as mileage, engine, max_power, and seats were converted from float to integer data types for further analysis.

4. **Encoding Categorical Data**:
   - Categorical data, such as transmission and owner, were encoded using techniques such as one-hot encoding or label encoding to convert them into numerical format suitable for analysis.

5. **Feature Selection**:
   - Out of the original features, only a subset was selected based on relevance for segmentation analysis.

6. **Scaling of Features**:
   - The selected features were scaled using the StandardScaler method to ensure uniformity and comparability.

Used libraries - skikit-learn, matplotlib, pandas, numpy and seaborn. 

## Dataset
[Click here to download Dataset](https://drive.google.com/file/d/1bTryl8IpjWmJQ3RqujcnmfmvVKuGJnb9/view?usp=sharing) Contains data of 8128 customers and contains 13 variables.

## Feature Engineering
In this phase, Principal Component Analysis (PCA) was employed to effectively reduce dimensionality and extract essential features from the dataset. By condensing the original features into a smaller set of principal components, PCA facilitated a more efficient representation of the data while retaining its key characteristics.

 __Clustering__:

The k-means clustering algorithm was applied to segment customers based on their attributes. By iteratively assigning data points to clusters and optimizing cluster centroids, k-means grouped similar customers together, enabling the identification of distinct segments within the customer base.

 __Visualization__:

Various graphs and visualizations were generated to gain insights into the clustering results and interpret customer segments effectively. Visualization techniques played a crucial role in understanding the distribution of data points across clusters and assessing the coherence of the identified segments.

## Requirements
Python 3.x pandas numpy matplotlib seaborn scikit-learn 

## How to Run
-- Clone the repository to your local machine.

-- Install the necessary libraries using pip:

    (pip install pandas numpy matplotlib seaborn scikit-learn)
  
-- Run the code in google colab or desktop application.

-- Explore the clustering results and gain insights from the visualizations generated during the analysis.


## Results
[Click here to download Result_File](https://docs.google.com/spreadsheets/d/1HPnpXGiUDQy21IBZOU4rBpsksOyJFbXQ/edit?usp=sharing&ouid=113132853465074771254&rtpof=true&sd=true) Created a new variable, which gives each customer a specific segment.
