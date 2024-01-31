# Iris-dataset-data-analysis-ms-excel

# Data Analysis using MS Excel
Different types of datasets are downloaded from the Google platform. The data analysis is performed with the help of MS Excel. 
_Reference_: https://hackernoon.com/15-excel-datasets-for-data-analytics-beginners 

 Now I have performed the data analysis for **Iris Dataset**
 
  Overview
  This repository contains data analysis performed on the famous Iris dataset using Microsoft Excel. The Iris dataset comprises measurements of sepal length, sepal width, petal length, and 
  petal width for 150 iris flowers, categorized into three different species: setosa, versicolor, and virginica. The dataset is organized into a data frame with 150 rows and 5 columns, 
  including a column indicating the species of each flower.

 ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/cbda31f1-5dda-4e80-9131-37c0484ed3a3)


   
    Analysis Performed
    
  1. Calculating petal and sepal area and check which species has the largest petal area 
  To gain insights into the petal characteristics, the area of each species' petal is calculated using the formula:
      Petal Area = select ((petal length cell)*(petal width))
    
    ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/41838b11-fa2b-40d3-ba5a-e0c75ebf3b44)


    ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/914d41a0-6ef5-4c96-bb11-2a9510f48fea)


    With the help of the pivot table and the pie chart, I could infer that virginica had the maximum petal length of 11.29 when compared to other species.
  
  2. Transpose Function
  The transpose function in Excel is employed to switch the rows and columns of the dataset, providing an alternative view for analysis.
        Steps involved :
           - Select and copy the rows and columns which need to be interchanged.
           - select the new empty cell press CTRL + ALT + V (paste a special short key) and choose a transpose option.
     This can be useful in various situations such as Changing Data Layout, Linking Data Across Sheets, dynamic data arrangement etc.
  
  3. Average Petal Area
  The average petal area for each species is calculated to understand the typical petal size within each category.

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/99e7f262-10fe-4c6a-98f6-65f67b2f40cc)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/fb991a63-1ff7-4c02-a086-315cbbccddc1)


  
  The analysis is performed with the help of a pivot table. This infers that virginica species has a higher average petal area when compared to other species.
  
  4. Descriptive Analysis
  A comprehensive descriptive analysis is conducted, including mean, median, mode, standard deviation, minimum, and maximum values for sepal length, sepal width, petal length, and petal width 
  across all species.
  Here the descriptive analysis is conducted for sepal-length. 
  
  5. Correlation between Petal Length and Petal Width
  A correlation analysis is performed to determine the relationship between petal length and petal width, providing insights into their interdependence.
  
  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/085064de-c1cb-4956-9bd0-c2e1aad13d07)

  
  This analyzed a positive correlation (a relationship between two variables that move in tandem—that is, in the same direction.)
  
  6. Species Distribution
  The distribution of each species within the dataset is visualized to understand the representation of setosa, versicolor, and virginica flowers.
  
 ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/025aeb1e-d43f-4375-97a3-29bd692e3d71)


  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/806bd7c7-ee41-4cfd-83fa-d25bdba0a454)


  This infers that the species distribution is equal to 50 each. 

  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/977b8669-033e-409b-8668-d06b37710a3a)
  
  The above image talks about the distribution of petal width in the histogram. 
  
  7. Finding the sum of sepal length, and average of petal width by using the Pivot table and visualizing by using charts (pie and bar charts)

   ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/02d887b8-13c9-4199-af21-80d3fb94a938)

  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/4c3cadbf-03e8-432f-9037-c477b417fe50)

  
  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/fac024a1-b431-4c4a-ac68-5b5dbcf1f7a7)

  
  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/8dcc8cfc-e25a-4f88-b700-cdb3560a7868)

  With the help of the pivot table and the visualization, I could infer that virginica and setosa had the highest value for average petal width and the sum of sepal width respectively. 
  
  8. Finding the maximum petal area of a specific species (ex: setosa)
  By using maxifs, index, and match, I could infer that 0.96 was the maximum petal area of setosa species.

  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/216317b2-ea25-4e61-922f-e2ebae7bdf11)

  

  
  This analysis is performed using Microsoft Excel, and no additional libraries or tools are required. 
