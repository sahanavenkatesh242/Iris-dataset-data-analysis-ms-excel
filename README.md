# Iris-dataset-data-analysis-ms-excel

# Data Analysis using MS Excel
Different types of datasets are downloaded from the Google platform. The data analysis is performed with the help of MS Excel. 
_Reference_: https://hackernoon.com/15-excel-datasets-for-data-analytics-beginners 

Now I have performed the data analysis for **Iris Dataset**
 
Overview

This repository contains data analysis on the famous Iris dataset using Microsoft Excel. The Iris dataset comprises measurements of sepal length, sepal width, petal length, and petal width for 150 iris flowers, categorized into three species: setosa, versicolor, and virginica. The dataset is organized into a data frame with 150 rows and 5 columns, including a column indicating the species of each flower.

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/ab756306-e165-46ee-bcec-2d176b899878)


Analysis Performed

1. Species Distribution
   The distribution of each species within the dataset is visualized to understand the representation of setosa, versicolor, and virginica flowers.

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/19bf4b43-7b5e-476e-a0d5-196dbbed4c1f)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/9cee6092-d45b-4bb6-9598-ce1dced9c4a7)

By the pivot table and visualization, I can infer that there is an equal distribution of species (50 in numbers) for the given dataset.

2. Calculating petal and sepal area and check which species has the largest petal area
   To gain insights into the petal characteristics, the area of each species' petal is calculated using the formula:
   Petal Area = select ((petal length cell)*(petal width))

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/cae98b37-1cf8-4de4-8992-b9ed465fde4d)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/4eaddeb9-8268-4665-b914-5f52afdb3801)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/e1360d92-b955-4751-b96d-400623f6d66b)

    With the help of the pivot table and the pie chart, I could infer that virginica had the maximum petal length of 15.87 when compared to other species.

3. Transpose Function
  The transpose function in Excel is employed to switch the rows and columns of the dataset, providing an alternative view for analysis.
        Steps involved :
           - Select and copy the rows and columns which need to be interchanged.
           - select the new empty cell press CTRL + ALT + V (paste a special short key) and choose a transpose option.
     This can be useful in various situations such as Changing Data Layout, Linking Data Across Sheets, dynamic data arrangement etc.

  ![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/70cd1f7e-1d09-45a9-83da-26e4f6901b56)


4. Few data visualizations using pivot tables and charts 

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/c9bf4808-5458-438a-b62e-9670ed53e4d4)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/d3f8f76b-d2de-4049-b43a-1c2430202cd9)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/2af0c3f9-8d22-45b1-b9cf-90922f31476d)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/544f9b20-3a7b-495e-85f6-3cdb3f13366e)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/99c3b427-d5b5-4dc0-8307-7620580b5b73)

From the analysis, I can infer that virginica has the highest score for average petal area which is 11.29.

5. Descriptive Analysis
A comprehensive descriptive analysis is conducted, including mean, median, mode, standard deviation, minimum, and maximum values for sepal length, sepal width, petal length, and petal width across all species.
Here is the descriptive analysis conducted for sepal-length. 

Descriptive statistics of sepal-length	
	
Mean	5.848322148
Standard Error	0.06788107
Median	5.8
Mode	5
Standard Deviation	0.828594057
Sample Variance	0.686568112
Kurtosis	-0.553560349
Skewness	0.303098019
Range	3.6
Minimum	4.3
Maximum	7.9
Sum	871.4
Count	149
![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/1e92cce6-f730-42b6-938e-08482709907b)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/66bbfc06-2707-4676-8cc4-feddf9af7906)

6. Correlation between Petal Length and Petal Width
A correlation analysis is performed to determine the relationship between petal length and petal width, providing insights into their interdependence.
Correlation can be found by the pivot table or the basic formula from the data analysis toolpak

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/cb0f9a53-6898-48a9-bb89-5fddf6246797)

This analyzed a positive correlation (a relationship between two variables that move in tandem—that is, in the same direction.)
  
7. Which species has the lower petal area and sepal area?

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/910ea0de-f551-48a7-90c4-3f6b8a5b0af4)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/c5536762-8524-4b1b-ab6b-444a5ccce264)
  
![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/bcfed74f-0fd6-40b5-bf37-2ebfda866b8f)
 

8. Finding the maximum petal area of a specific species (ex: setosa)
Using maxifs, index, and match, I could infer that 0.96 was the maximum petal area of setosa species.

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/216317b2-ea25-4e61-922f-e2ebae7bdf11)

9. Distribution of sepal length with 2 kinds of species.

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/946c6476-6a56-4ab1-8294-c56bb6b47e32)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/4d646f17-34ab-440c-aa21-fef1aedb019d)

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/45e680b0-02b2-49bd-beca-664892cf4538)


The above images are the plots of the distribution of sepal length of setosa and versicolor species of iris. The bin range has been varied to have a clear visualization. 

10. Sepal length distribution with the cumulative %

![image](https://github.com/sahanavenkatesh242/Iris-dataset-data-analysis-ms-excel/assets/157820520/9e1ed1a9-00a9-4fd1-a3be-df94639f78a0)

For example to analyse the above plot
23 species of iris have a sepal length in a range of 4.9 to 5.2
From the 4th point of cumulative %, we can infer that 30% of iris species have a sepal length less than 5.2 mm 





  
This analysis is performed using Microsoft Excel; no additional libraries or tools are required. 
