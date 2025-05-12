# Final Project - College Value Analysis  
  
### Pupose  
To provide personalized insight into the financial value of U.S. colleges and universities.  
  
### Background
The US Department of Education collects statistics for all US-based post-secondary educational institutions that receive government funding. This data is coalesced in the College Score Card and includes, among other things, costs, median earnings after graduation, test scores and admission rates. The premise of this study is to use this data along with a student's personal information and college list, to provide some insight on the financial value (cost vs. earnings) of institutions they are considering.  
  
### Code File(s)
* College Value.ipynb - Python Notebook file containing the code for this analysis.  

### Data File(s)
* Most-Recent_Cohorts-Institution.csv - The most recent College Scorecard Institutional data for all post-secondary educational institutions receiving funding from the U.S. Department of Education. Contained in the Most-Recent-Cohorts_Institution.zip file that must be downloaded and extracted. The source of this data is: https://collegescorecard.ed.gov/data/.
* Student Info.xlsx - An Excel spreadsheet template for inputting personal data to be analyzed with College Scorecard data. Pre-populated with the personal information (state of residence, housing preference, college list) of a test subject. 

### Supporting Document(s)
* README.md - This file, used to navigate the GitHub repository. Includes purpose, background, index and description of files, prerequisites, etc.  
* Summary.md - A single page summary overview of the findings of the  analysis. 
* Final Project - College Value.pptx - PowerPoint presentation of the study and its findings. Contained in a 'Final Project - College Value.zip' file which must be downloaded and extracted. 

### Prerequisites
This analysis is performed in either Jupyter Lab or Jupyter Notebook, which must be installed in your environment to run. The code uses the following libraries which must also be installed in your environment:  
* adjustText  
* gc  
* matplotlib  
* numpy  
* os  
* pandas  
* seaborn  
* scipy  
* sklearn  
* warnings

The following files must all be collocated in the same directory to execute the code:
* College Value.ipynb
* Most-Recent_Cohorts-Institution.csv
* Student Info.xlsx

To perform the analysis with your own personal data, you must fill in the 'Student Info.xlsx' with your data prior to executing.

### Questions:
The following questions are answered in this study:
1. How does the cost of a college affect such things as admission rate, test scores, region, locale or institutional control?
2. How does the median earnings of a college affect such things as admission rate, test scores, region, locale or institutional control?
3. How do colleges (considered, applied to or admitted to) compare based on cost vs. potential earnings?
4. What is the payback period for colleges (considered, applied to or admitted to)?
5. What are the projected earnings of a college (considered, applied to or  admitted to) after a 40-year career?

### Results

##### General
The Higher the Cost of the Institution:
* The Lower the Admission Rate
* The Higher the Test Scores
* The Higher the Median Earnings

New England is clearly the Highest Cost Region with barely the Highest Median Earnings.

Outlying Areas have the Lowest Cost and Lowest Median Earnings.

US Service Schools are Unique (NO costs, high and predictable earnings, high test scores and low admission rates). 

Private Non-Profit Institutions have Higher Costs while Earnings are NOT discernible from other Institutional Controls.

Private For-Profit Institutions have Lower Costs while Earnings are NOT discernible from other Institutional Controls.

Earnings over a 40-years are a Much Stronger Consideration than 4-year Costs.

##### Client Test Case:
For the student information used in our test case:
* All of the student’s considered schools are above average at their given cost point (good value)!
* The best value in terms of initial investment and payback period appears to be RPI for this student.
* The best long-term value (over a 40-year career) appears to be MIT.
