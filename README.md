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

spending_summary_df[["Average Math Score",
                    "Average Reading Score",
                    "% Passing Math",
                    "% Passing Reading",
                    "% Overall Passing Rate"]]

size_summary_df = per_school_summary.groupby(["School Size)"]).mean()

size_summary_df[["Average Math Score",
                "Average Reading Score",
                "% Passing Math",
                "% Passing Reading",
                "% Overall Passing Rate"]]

type_summary_df = per_school_summary.groupby(["School Type)"]).mean()

type_summary_df[["Average Math Score",
                "Average Reading Score",
                "% Passing Math",
                "% Passing Reading",
                "% Overall Passing Rate"]]
