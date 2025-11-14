# PERFUME DATA ANALYSIS
An Excel project analyzing a collection of global perfume brands from a fictitious perfume dataset. The dataset encompasses details such as brand, perfume name, type and longevity. The goal is to derive actionable insights to inform strategic decisions.


#### Table of Contents 
- Project Overview 
- Project Scope 
- Project Objectives 
- Expected Outcome 
- Document Purpose  
- [Data Source](https://www.kaggle.com/datasets/ayushghawana/perfume-dataset) 
- Data Cleaning and Processing 
- Data Analysis 
- Data Visualization 
- Recommendation 
- Conclusion


### Project Overview 
This project involves an in-depth analysis of Global Perfume Brands from a fictitious perfume data. The analysis is performed using Excel, providing valuable insights to drive strategic decisions and optimize operational effectiveness. 


### Project Scope 
The project covers a comprehensive analysis of Perfume Brands, Name, Types, Category, and Longevity. Each row represents a specific perfume entry, with attributes describing its characteristics, usage, and performance. 


### Project Objectives 
The primary objectives of this analysis are:
- Brand insights: The number of labels that produces the perfume.
- Target audience analysis: The intended wearer of the perfume.
- Perfume type distribution: Identify level of concentration or formulation of the perfume.
- Category analysis: Classification of the fragrance based on scent family or style. 
- Longevity insights: Expected performance in terms of duration on the skin. 


### Expected Outcome 
The analysis aims to provide actionable insights, including: 
- Total perfume count
- Dominating fragrance families
- Perfume type by longevity
- Total perfume distribution by type
- Cross-analysis


### Document Purpose 
This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and other relevant information.


### Data Source 
The dataset for this project is sourced from [Kaggle website](https://www.kaggle.com/datasets/ayushghawana/perfume-dataset) designed specifically for practice purposes. It is presented in an Excel file comprising of 1,005 rows and 6 columns (Brand, Perfume, Type, Category, Target audience, and Longevity). Each row represents a single observation, and each column corresponds to a distinct attribute. Importantly, there are no missing values, which ensures that the dataset is complete and suitable for analysis.


### Data Cleaning and Processing
Having a clean data for analysis is essential because it ensures that the insights are accurate, reliable, and free from errors. Clean data makes the analysis process smoother, helping researchers, analysts, and decision-makers to draw meaningful conclusions and make informed decisions based on trustworthy information. 

After thoroughly checking the data for quality and suitability, including looking for errors, inconsistencies, missing values, and duplicates, I found that the dataset is well-organized except that the dataset had 63 duplicates, the perfume Type column and Target_audience column were inconsistent, and I had to replace first row as column heads which appeared twice in the data. 

**Additional Data Processing Steps:**

**1.  Type Column:**

After filtering the type column had Eau de Parfum (EDP), Eau de Toilette (EDT), Extrait de Parfum, Concentrate, Extrait, Parfum, Cologne, Alcohol-free, Attar, and oil. 

After extensive research it was known that Alcohol-free and oil perfume where also called Attar perfumes, Cologne was known as Eau de Cologne (EDC), Extrait was same as Extrait de Parfum having 20 – 40% concentration and Concentrate which also refers to the highest concentration fragrance oil typically between 20-40% in product like Extrait de Parfum was also known to have the same percentage concentration of Parfum. 

Putting together all the information gathered Ctrl + F button was used after filter was applied to the dataset. To do that, click on Data in the tool-bar and click on filter. On the Type column click on the arrow filter to filter for every value that needed to be corrected by a single click at the top of the column head follow by using the Ctrl + F button to find and replace the values for correction for each filtered value.

  **2.	Target Audience:** 

The same method was applied in the target audience column to make it consistent and error free. 

  I.	Filter: click on Data in the tool-bar, then click on filter. It was found that the column had values consisting Men, Women, Male, Female, and Unisex. 

  II.	Ctrl + F: This is applied by a single click on top of the target_audience to highlight the column after which the ctrl f button is used to find and replace the inconsistent values. So, wherever we find Men it will be replace with Male, and wherever find Women it will be replace with Female.


### Data Analysis and Insight 
The primary aim of this analysis is to derive valuable insights from Perfume Dataset by conducting a comprehensive examination of key factors. This multifaceted exploration involves several pivotal objectives. 

Firstly, it seeks to know the total perfume by brand. Secondly, to know the total perfume distribution by type. Thirdly, the analysis aims to identify the top fragrance families. Furthermore, a detailed investigation into the popularity of perfumes between the target audience using a cross-analysis and the longevity & quality insights of each perfume by type. Lastly, to know the percentage perfume by target audience.

Key benefits include, Performance Insights: identify top-performing brands, Product Mix Understanding: Understand consumer preference trends, guide new product development, Longevity Insights: Evaluates how long each type typically lasts, Visual Decision Support.

