# School_District_Analysis
Using Anaconda/Jupyter Notebook and Python to report/analyze public school test scores.

## Overview of Project
The purpose of this project was is to analyze 15 schools and their to asses previous year performanc metrics and support a School Board's funding allocation decisions. Throughout the analysis new information arose questioning the legitmacy of Thomas High School's 9th grade reading & math scores. To better understand the data, I calculated specific metrics  to better assist the School Board's decision making process.

Using the data provided, I have identified and calculated the following metrics:
- Average student Math/Reading Score by **District**
- Average student Math/Reading Score by **District**
- Percentage of students passing both Math & Reading by **District** (See "% Overall Passing")
- Average student Math/Reading Score at **Thomas High School**
- Percentage of students passing Math/Reading by **Thomas High School**
- Percentage of students passing both Math & Reading by **Thomas High School** (See "% Overall Passing")

For each metric listed above I have recalculated the metrics to nullify all math and reading scores for the 9th grade class of Thomas High School. Then I compared this recalculation to the original metrics to better understand the impact of the new information and provide more value to the School Board for their decision making process.

## Results

1. School District Results & Impact

  The School District showed a broad drop in all metrics once the new information was taken into account. (see data below)
  
  Original
  
  ![Original_District_Results](https://user-images.githubusercontent.com/107579508/178808751-3dd89947-8fed-49b2-8a86-6e48479628a2.png)
  
  Updated
  
  ![Updated_District_Metrics](https://user-images.githubusercontent.com/107579508/178808707-9e8acdc8-4936-4c8f-a4ce-36b7b30acb44.png)
  
  Both the Average Math and % of Passing Math score dropped. Leaving a negative impact on the % of Overall Passing for the school district.

2. Thomas High School Results & Impact

  Thomas High Schools metrics dropped significantly. Below you can see the affect of ommitting the 9th Grade's metrics.
  
  Original
  
  ![Original_THS_Results](https://user-images.githubusercontent.com/107579508/178809095-087310bb-d70f-42ed-be47-926d3b5a5f2f.png)
  
  Updated
  
  ![Updated_THS_Results](https://user-images.githubusercontent.com/107579508/178810607-e4e35810-98d8-4ee7-b5df-b1eedfadb852.png)
  
  ## Summary
  
  Accounting for and nullifying the math & reading scores of all the 9th Grade students of Thomas High School negatively impacted overall passing metrics which contributed to a district wide drop in scores. The School Board will have to further weigh this impact in their decision to provide future funding as well as determine a solution for more reliabile data for future analyses. 
