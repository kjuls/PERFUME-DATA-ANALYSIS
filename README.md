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
1.	Type Column:

After filtering the type column had Eau de Parfum (EDP), Eau de Toilette (EDT), Extrait de Parfum, Concentrate, Extrait, Parfum, Cologne, Alcohol-free, Attar, and oil. 
After extensive research it was known that Alcohol-free and oil perfume where also called Attar perfumes, Cologne was known as Eau de Cologne (EDC), Extrait was same as Extrait de Parfum having 20 – 40% concentration and Concentrate which also refers to the highest concentration fragrance oil typically between 20-40% in product like Extrait de Parfum was also known to have the same percentage concentration of Parfum. 
Putting together all the information gathered Ctrl + F button was used after filter was applied to the dataset. To do that, click on Data in the tool-bar and click on filter. On the Type column click on the arrow filter to filter for every value that needed to be corrected by a single click at the top of the column head follow by using the Ctrl + F button to find and replace the values for correction for each filtered value.

2.	Target Audience: 

The same method was applied in the target audience column to make it consistent and error free. 

**I.	Filter:** click on Data in the tool-bar, then click on filter. It was found that the column had values consisting Men, Women, Male, Female, and Unisex. 

**II.	Ctrl + F:** This is applied by a single click on top of the target_audience to highlight the column after which the ctrl f button is used to find and replace the inconsistent values. So, wherever we find Men it will be replace with Male, and wherever find Women it will be replace with Female. 


### Data Analysis and Insight 
The primary aim of this analysis is to derive valuable insights from Perfume Dataset by conducting a comprehensive examination of key factors. This multifaceted exploration involves several pivotal objectives. 

Firstly, it seeks to know the total perfume by brand. Secondly, to know the total perfume distribution by type. Thirdly, the analysis aims to identify the top fragrance families. Furthermore, a detailed investigation into the popularity of perfumes between the target audience using a cross-analysis and the longevity & quality insights of each perfume by type. Lastly, to know the percentage perfume by target audience.

Key benefits include, Performance Insights: identify top-performing brands, Product Mix Understanding: Understand consumer preference trends, guide new product development, Longevity Insights: Evaluates how long each type typically lasts, Visual Decision Support.

#### 1.	What is the Total Perfume by Brand?

The primary objective of this analysis is to determine the total number of perfume’s made available by each brand and the total number of brands in the dataset. To achieve this, a pivot table was created. The brand column was placed in the row section, and perfume was placed in the values section to count the number of perfumes. The results were visualized using a bar chart.

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Total%20Perfumes%20by%20brand.png)

From the above analysis 
- Paris corner brand has the highest number of perfumes.
- Armaf brand has the second highest number of perfumes.
- There are 51 brands in total. 

#### 2.	What is the total perfume distribution by type? 

The primary aim of this question is to identify the total perfume distributed using the type method and to also find out which type had the highest distribution. 
To achieve this, a pivot table was created. The Type column was placed in the row section, and perfume was placed in the values section to count the number of perfumes. The results were visualized using a horizontal bar chart. 

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Total%20distribution%20by%20Type.png)

From the above analysis 
- EDP has the highest number of perfume distribution with a total of 740.
- EDT has the second highest number of perfume distribution with a total of 123.
- PARFUM has a total of 60 perfume distribution coming third.
- EDC has 10 perfume distribution, and Attar coming last with a total of 7 perfume distribution.

#### 3.	Which fragrance families dominate?

The question aims to understand the popularity and dominance of perfume in different category. By identifying top dominating fragrance and those driving more revenues, so the business can make informed decisions about inventory management, marketing strategies, and potentially introduce promotions or adjustments to product offerings.

To achieve this, a pivot table was created. The Category column was placed in the row section, and perfume was placed in the values section to count the number of perfumes. The results were visualized using a horizontal bar chart. 

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Top%208%20fragrance%20families.png)

From the above analysis 
- Woody spicy has the largest number of fragrance family and top dominating family.
- Floriental has a total of 119 fragrance family and the second dominating family.
- The analysis show that 38 fragrance families are not known to any category of perfumes and as such remains unknown.

#### 4.	How long each type typically lasts?

The aim of this question is to evaluate how long each type typically lasts, and identify gaps in product quality. To achieve this, a pivot table was created. Type column was placed in the row section, Longevity column was placed in the columns section as column labels, and perfume was placed in the values section to count the number of perfumes. The results were visualized using a stacked column chart.

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Longevity%20by%20Type.png)

- EDP has levels of concentration that consist of 6 very strong, 271 strong, 445 medium, and 18 light perfumes by type.
- EDT has levels of concentration that consist of 6 strong, 84 medium, and 33 light perfumes by type.
- Parfum has levels of concentration consisting 23 very strong, 33 strong, and 4 medium perfumes by type.
- EDC has just 10 medium perfumes in level of longevity.
- Attar known as an oil base perfume has 7 strong perfumes by type in level of concentration.


#### 5.	What are the types of perfume more popular among the target audience?

The question aims to deliver more insight on the level of popularity among male, female, and unisex. 

**I.	What perfume types are more popular among females?**

The aim of the question above is to identify the most and least popular perfume type among the females.

The Type column was placed in the row section, target_audience column was placed in the columns section, and perfume was placed in the values section to count the number of perfumes. In the column label, only female was filtered as the target_audience. The results were visualized using a horizontal bar chart.

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Popular%20Perfume%20Type%20Among%20Females.png)

From the above analysis 
- Only Parfum, EDT, EDP, and EDC is known within the females alone.
- EDP has the most popular perfume type among the females with a total of 221.
- EDC is the least popular perfume type among the female category.

**II.	Are certain types more popular among male?**

The aim of the question above is to identify the popular perfume types among the male category only.

The type column was placed in the row section, target_audience column was placed in the columns section, and perfume was placed in the values section to count the number of perfumes. In the column label, only male was filtered as the target_audience. The results were visualized using a horizontal bar chart.

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Popular%20Perfume%20Type%20Among%20Males.png)

From the analysis above 
- EDP has the highest popularity by type among men with 208 in number.
- In second place is EDT.
- PARFUM has the least popular perfume type among men.

**III.	Is certain perfume type more popular within the unisex section in target_audience?**

The aim of the question above is to identify popular perfume type within unisex category only.

The type column was placed in the row section, target_audience column was placed in the columns section, and perfume was placed in the values section to count the number of perfumes. In the column label, only unisex was filtered as the target_audience. The results were visualized using a horizontal bar chart.

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Popular%20Perfume%20Type%20Among%20Both%20Male%20And%20Female.png)

From the analysis above
- All five (5) perfume type are present in the unisex category only.
- EDP has the highest perfume type in the unisex category with a total of 311.
- EDT with a total of 26 perfume type.
- Parfum has 25 perfume type.
- Attar, and EDC are the bottom perfume type in the unisex category.


#### 6.	What is the percentage % perfume by target_audience?

The question above gives us details on the number of percentage perfume by the target_audience.

The target_audience column was placed in the row section, and perfume was placed in the values section to count the number of perfumes. In the values field settings when click on the drop-down arrow of count perfume in values, click on show values as % of column total to display values in %. 

![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/%25%20Perfume%20By%20Target%20Aduience.png)

The analysis above clearly shows that female has a total of 29%, male has a total of 31%, and unisex with the highest percentage number of 40%.


### Data Visualization
![](https://github.com/kjuls/PERFUME-DATA-ANALYSIS/blob/main/Perfume%20Data%20Analysis%20Dashboard%20.png)


### Recommendation 
Based on the provided analysis, here are several recommendations for Perfume Data Analysis:
- Prioritize top-performing brands with the highest number of perfume listings.
- Evaluate brands with very low representation for possible expansion or removal.
- Strengthen partnerships and marketing for brands with high customer engagement.
- Rationalize slow-performing brand lines to optimize shelf space and inventory cost.
- Make Eau de parfum (EDP) the core product focus.
- Ensure consistent stock availability of EDT as a secondary but essential segment.
- Expand Parfum options slowly, especially for premium customers seeking high longevity.
- Minimize overstocking of EDC and Attar due to low demand in the dataset.
- Promote EDP to both male and female audiences as it shows the highest acceptance.
- Use EDT as an alternative option for budget-friendly or casual-wear customers.
- Highlight EDP and strong-long-lasting perfumes in marketing as they dominate longevity performance.
- Position EDT as a lighter, everyday option with moderate projection.
- Increase investment in the top 3-4 fragrance families.
- Promote unisex fragrances as versatile, modern options for everyday use.
- Ensure each target group has a well-distributed selection across core perfume types.

### Conclusion 

Use data-driven insights to guide inventory planning, enhance operational efficiency, increase revenue, and improve promotional campaigns. 

Thank you for reading. I’m interested in Analytics role in an organization where I can showcase my skills, take more responsibilities, continue to learn, an organization that I can grow with, where my work will be highly beneficial to the organization.

You can reach me on juliusokolawole@gmail.com
