# School_District_Analysis
Deliverable #3
1.	Overview of the school district analysis: Explain the purpose of this analysis. This analysis takes a python pandas solution to the education sector to analyze a set of city school’s district data. This project will help the school board and mayor make strategic budgeting decision to help the future of the schools and priorities. For this project there were 2 datasets that were used. Both were formatted as CSV files with information including Student ID, School Name, Type, size, budget, student name, gender, grade, reading score, and math score. Once the two data sets were merged the analysis was able to begin. To merge this data Jupyter Notebook was used. 
2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions.
o	How is the district summary affected?
There was a slight downward change in the district averages. 
o	How is the school summary affected?
	Overall, the ranking order changes due to Thomas High school taking out the 9th graders scores, which caused the school to drop from 2nd to 13th position. 
o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
	By replacing the 9th grade reading and math scores this dropped the school’s grades. Overall, the math and reading scores were helping the school’s grades improve. They were driving the total average up and placing the school in a higher position verse the other schools. 
o	How does replacing the ninth-grade scores affect the following:
	Math and reading scores by grade: The math and reading scores overall went down very slightly as a total once the THS 9th grade students were taken out. By adding them back in, the grades went up. 
	Scores by school spending: The schools spending per child was not a reflection in the passing scores. For example, Ford High School had a budget of $644 per student and had a 54.29% pass rate. While the Carbrera High School had a budget of $582 per student with a passing rate 91.33%. 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/91567484/140656085-d6607428-441a-4bd8-b586-d4b6d1edefd3.png">

	Scores by school size: Reducing the school size of THS slightly affected the 9th graders. Math and reading scores overall. 
	Scores by school type: Overall the Charter type schools had a much more successful pass rate for both reading and math scores. 
3.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 
o	The math overall school went down slightly when the 9th grade was replaced with NaNs. 
o	The reading overall school score went up slightly when the 9th grade was replaced with NaNs.
o	The percentage passed for Math went down when the 9th grade was replaced with NaNs. 
o	The percentage passed for reading scores went down whe the 9th grade was replaced with NaNs. 
