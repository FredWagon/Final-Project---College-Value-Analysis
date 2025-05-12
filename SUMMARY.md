# SUMMARY
### Final Project - College Value Analysis  
  
### Purpose  
To provide personalized insight into the financial value of U.S. colleges and universities.  
  
### Background
The US Department of Education collects statistics for all US-based post-secondary educational institutions that receive federal funding. This data is coalesced in the College Score Card and includes among other things: costs, median earnings after graduation, test scores and admission rates. The premise of this study is to use this data along with a student's personal information and college list, to provide insight into the financial value (cost vs. earnings) of institutions they are considering.   

### Tools Used
* JupyterLab (or Jupyter Notebook)
* Excel (for creating input, viewing and analyzing data)

### Questions:
The following questions are answered in this study:
1. How does the cost of a college affect such things as admission rate, test scores, region, locale or institutional control?
2. How does the median earnings of a college affect such things as admission rate, test scores, region, locale or institutional control?
3. How do colleges (considered, applied to or admitted to) compare based on cost vs. potential earnings?
4. What is the payback period for colleges (considered, applied to or admitted to)?
5. What are the projected earnings of a college (considered, applied to or  admitted to) after a 40-year career?

### Insights Discovered
#### General
Confirmed popular convention that the higher the cost of the institution:
* The lower the admission rate
* The higher the test scores
* The higher the median earnings

There is a very high correlation (>90%) between cost, median earnings, test scores and admission rates. Admission rates are negatively correlated.

New England is the highest cost region with barely the highest median earnings. Outlying Areas have both the lowest cost and lowest median earnings. U.S. Service Schools are unique in that they have NO costs, high and predictable earnings, high test scores and low admission rates. 

Private Non-Profit institutions have higher costs while their median earnings are NOT discernible from other institutional controls. Private For-Profit institutions have lower costs while earnings are NOT discernible from other institutional controls. Public institutions have the tightest range in earnings, while Private For-Profit has the largest range. 

Earnings over a 40-years are a much stronger consideration than 4-year costs.

#### For the Client Test Case:
For the student information used in our test case:
* All of the student’s considered schools are above average at their given cost point (good value)!
* The best value in terms of initial investment and payback period appears to be RPI for this student.
* The best long-term value (over a 40-year career) appears to be MIT.

### Future Work
* Include areas of Study in the analysis. The College Scorecard has this data, and I feel that the earnings of an institution may have been exaggerated or stifled based on the majors offered at a college. For example, the median earnings for primary engineering schools were noticeably higher than that of more balanced or liberal arts schools. I would like to perform this same study based on institution AND area of study, instead of just institution.
* Cluster analysis. While a cluster analysis was conducted on considered institutions, it only showed which of the considered colleges were 'closest' to one another. I would like to perform cluster analysis on the entire data set and be able to show a client alternatives to the schools they selected.
* Industrialize as a service. I would like to make this report more streamlined for a client to request a report for this kind of information.
