# People Analytics - Developer Salaries
<br><b>Objective:</b> What kind of developers are getting higher pay? and Identify those important parameters?
<br>

<b> Machine Learning Methodologies Used </b>- Clustering (K-Means), Decision Tree.
  <br>

<b>Technology:</b> Python: Numpy, Pandas, Scikit-Learn and Seborn libraries.
  <br>

<b>Dataset:</b><br>
In order to come up with the solution. We have choosen <a href='https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey'>'Stack Overflow 2018 Developer Survey'</a> dataset. Each year, Stack Overflow asks the developer community about everything from their favorite technologies, salaries to their job preferences. As 'Stack Overflow' is widely used by the developers, this dataset is most suitable to analyse salaries across various parameters.<br>
Datset consists of 98,855 responses in 129 columns. Each row represents a survey response by a developers. Though the dataset contains lots of columns, we are interested in the below columns -
<ul><li>Converted Salary - Annual Salary in $ (for each developer). 
<li>Education - Education level of the developer who filled this survey. 
<li>Years Coding Professionally - Number of years since coding professionally. 
<li>Last New Job - When was the last time that you took a job with a new employer? (in years) 
<li>Technical Skills Areas 
<li>DevType -Development Types. 
<li>Language Worked With - Which programming, scripting, and markup languages you worked in past. 
<li>Database Worked With - Database environments that you have worked in. 
<li>Platform Worked With - Platforms that you have worked in. 
<li>Framework Worked With - Libraries, frameworks, and tools that you have worked in. 
<li>IDE - Development environment(s) you use regularly. 
<li>Gender - Your gender. 
<li>Country - Your current resident country. (Data is from 189 countries)
  </ul>
  <br>
  
  <b>Conclusion:</b>
<br>  
Generally, It is believed that to be successfull in Software industry, one's degree and work experience does not matter. The only thing matter is his/her vast knowledge about various languages, databases, frameworks and platforms (i.e. technical knowledge and acumen). However, data does not show the same story. <br>
 
As first part of our analysis, data shows us that developer's salary is most dependent on higher education and experience (same old parameters the we know). Now the question arises- Is it beneficial to all the developers in same way? Shall highly experienced professional go for higher education? If yes, when? If no, what is the experience limit after which higher education does not matter.
<br>
<p align="center"><img src="https://github.com/kpratikin/developer_salary/blob/master/Conclusion_Sns.PNG">
 <br>Figure: Salary versus Coding Experience and higher education
 </p>
<br>
These questions are answered in our second part of analysis and following are the conslusions of the same:<br>
<ul><li>For freshers, if you do master's you can earn slightly higher than your colleagues at the start of your career. However, in long run your experience determines your salaries.
<li>For working professional with more than <b>9 years</b> of experience, there is no advantage in terms of salaries. So, for these people doing master's is not desirable (from salary point of view).
