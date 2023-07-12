# Pandas-Challenge

In this challenge, we were given 2 datasets for students and schools and asked to make summaries based on the district and schools. We were asked to find the following for districts: 
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

and the following for schools: 
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

The data was sorted based on different factors such as top performing schools, bottom performing schools for easier anbalysis: 

Note: 
The following code was written with the help of a TA in office hours. 

spending_summary = pd.DataFrame({
        "Average Math Score": spending_math_scores,
        "Average Reading Score": spending_reading_scores,
        "% Passing Math": spending_passing_math,
        "% Passing Reading": spending_passing_reading,
        "% Overall Passing": overall_passing_spending})      

size_summary = pd.DataFrame({
        "Average Math Score": size_math_scores,
        "Average Reading Score": size_reading_scores,
        "% Passing Math": size_passing_math,
        "% Passing Reading": size_passing_reading,
        "% Overall Passing": size_overall_passing})    

type_summary = pd.DataFrame({
        "Average Math Score": average_math_score_by_type,
        "Average Reading Score": average_reading_score_by_type,
        "% Passing Math": average_percent_passing_math_by_type,
        "% Passing Reading": average_percent_passing_reading_by_type,
        "% Overall Passing": average_percent_overall_passing_by_type})      
