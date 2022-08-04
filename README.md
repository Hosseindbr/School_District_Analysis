# School_District_Analysis
## Overview of the project
This project aimed to help school bar to understand the  extend of  academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. To this end, we analyze the data provide by the school bar to retrieve the desired information.

## Resources
schools_complete.csv
students_complete.csv
Python version 3.9.12
Conda version 4.13.0
anaconda Command line client version 1.10.0

## Analyze
We initially read the “schools_complete.csv” and “students_complete.csv” files into DataFrame followed by identifying row value of DataFrame. Next step was retrieving data from the particular columns by merging, filtering, slicing, and sorting the data within DataFrame. Final step was applying groupby function to the DataFrame and performing mathematical calculation.
## Results

**How is the district summary affected?**

The results showed that average math and average reading did not significantly affected and the numbers round to the same value

**How is the school summary affected?**

The ranking remained unchanged 

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s 
performance relative to the other schools?**

The update did affect Thomas High School's average math, reading, and overall scores, but it was not enough to affect the school's relative ranking compared to other schools. A change of less than one percentage point was made to each metric as a result of the changes.

**How does replacing the ninth-grade scores affect the following:**
- Math and reading scores by grade
Math grade decreased slightly while reading remained constant
- Scores by school spending
There was a slight, less than 0.1%, change was observed in the group that Thomos High School is.
- Scores by school size
Only medium sized school affected by around one percent
- Scores by school type
No change was observed in the District type while each metrics in the Charter type , where Thomas High school was categorized, impacted by 0.1%.
## Summary 

1. Number of students remained constant
2. Math grades were affected more than reading grades
3. School ranking, including Thomos High School remained untouched 
4. In the charter school type, scores was affected by the updating the scores
