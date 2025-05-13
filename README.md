# README
### Final Project - College Value Analysis  
  
### Purpose  
To provide personalized insight into the financial value of U.S. colleges and universities.  
  
### Background
The US Department of Education collects statistics for all US-based post-secondary educational institutions that receive government funding. This data is coalesced in the College Score Card and includes, among other things, costs, median earnings after graduation, test scores and admission rates. The premise of this study is to use this data along with a student's personal information and college list, to provide some insight on the financial value (cost vs. earnings) of institutions they are considering.  
  
### Code File(s)
* College Value.ipynb - Python Notebook file containing the code for this analysis.  

### Data File(s)
* Most-Recent_Cohorts-Institution.csv - The most recent College Scorecard Institutional data for all post-secondary educational institutions receiving funding from the U.S. Department of Education. Contained in the Most-Recent-Cohorts_Institution.zip file that must be downloaded and extracted. The source of this data is: https://collegescorecard.ed.gov/data/.
* Student Info.xlsx - An Excel spreadsheet template for inputting personal data to be analyzed with College Scorecard data. Pre-populated with the personal information (state of residence, housing preference, college list) of a test subject. 

### Supporting Document(s)
* README.md - Used to navigate the GitHub repository. Includes purpose, background, index and description of files, prerequisites, etc.  
* SUMMARY.md - A single page summary of analysis & findings. 
* Presentation - College Value.pptx - PowerPoint presentation detailing the study and its findings.  

### Prerequisites
This analysis is performed in either Jupyter Lab or Jupyter Notebook, which must be installed on your computer to run. The code uses the following libraries which must also be installed in your environment:  
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

