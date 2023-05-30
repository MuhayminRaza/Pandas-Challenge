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

district_summary_df = pd.DataFrame({
    "Total Schools": [totalSchools],
    "Total Students": [totalStudents],
    "Total Budget": [totalBudget],
    "Average Math Score": [averageMathScore],
    "Average Reading Score": [averageReadingScore],
    "% Passing Math": [percentagePassingMath],
    "% Passing Reading": [percentagePassingReading],
    "% Overall Passing Rate": [percentageOverallPassingRate]
# Combine the series into a dataframe
grade_summary_df = pd.DataFrame({"9th": grade9th_ds,
      "10th": grade10th_ds,
      "11th": grade11th_ds,
      "12th": grade12th_ds})

grade_summary_df[["9th", "10th", "11th", "12th"]]

spending_summary = spending_summary_df[["Average Math Score",
                    "Average Reading Score",
                    "% Passing Math",
                    "% Passing Reading",
                    "% Overall Passing",
                   
type_summary = type_summary_df[["Average Math Score",
                "Average Reading Score",
                "% Passing Math",
                "% Passing Reading",
                "% Overall Passing Rate"]] 

                    
