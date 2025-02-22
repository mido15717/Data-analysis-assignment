# Google Play Store Data Analysis

## Project Overview
This project involves data analysis on the Google Play Store dataset using Python libraries such as Pandas, NumPy, and Seaborn. The analysis focuses on data cleaning, transformation, and visualization to extract meaningful insights about applications available on the Google Play Store.

## Dataset
The dataset used for this analysis is `googleplaystore.csv`, which contains information about various applications, including categories, ratings, reviews, size, price, and number of installs.

## Tools & Libraries Used
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For handling numerical data.
- **Seaborn**: For data visualization.
- **Matplotlib**: For additional plotting capabilities.

## Data Preprocessing
1. **Handling Missing Values**
   - Replaced missing and inconsistent values (`NaN`, `Varies with device`) with `NaN`.
   - Replaced outliers in columns such as `Size`, `Price`, `Rating`, and `Reviews`.
   
2. **Data Cleaning**
   - Processed the `Size` column by converting values from MB and KB to a standard format.
   - Cleaned the `Price` column by removing dollar signs and converting to float.
   - Converted `Last Updated` to a proper datetime format.
   - Converted `Reviews` and `Installs` to numerical values.
   
3. **Data Type Conversion**
   - Ensured numerical columns (`Size`, `Price`, `Reviews`, `Rating`, `Installs`) were in the correct data type for analysis.

## Data Visualization
Several visualizations were created to explore the dataset:

1. **Distribution of App Types**
   - A count plot showing the number of free vs. paid apps.

2. **Number of Installs vs. Size**
   - A scatter plot to visualize the relationship between app size and number of installs.

3. **Install Distribution**
   - A count plot showing the distribution of install numbers across apps.

4. **Total Installs per Category**
   - A bar plot displaying total installs for each app category.

5. **Total Reviews per Category**
   - A bar plot representing the total number of reviews for each app category.

## Insights Gained
- The majority of apps are free, with paid apps being significantly less in number.
- There is a trend between app size and installs, indicating user preferences for app sizes.
- Certain categories dominate the Play Store in terms of total installs and reviews.

## How to Run the Code
1. Install required libraries using:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
2. Place `googleplaystore.csv` in the project directory.
3. Run the Python script to clean data and generate visualizations.

## Conclusion
This analysis provides insights into app trends, pricing, and user engagement metrics in the Google Play Store. The results can be useful for app developers and businesses looking to optimize their presence on the platform.

---

### Author: Mohamed Salah

