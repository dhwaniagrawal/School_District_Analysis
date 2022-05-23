# Pandas Module 4 Challenge #
## Overview of the school district analysis ##

The "students_complete.csv showed evidence of academic dishonesty in reading and math grades for Thomas High School  ninth grades appear to have been altered. Therefore Maria wants us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Also after replacing the scores Maria wants us to repeat teh school district analysis and write a report to describe how these changes affected the overall analysis.

## Results ##
- In district summary, we noticed that Thomas High School 9th graders were contributing towards increasing the passing percentage. Now that we are not including Thomas High School 9th graders the passing percentage dropped.
District Summary
![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/district%20summary.png)
District Summary without THS data.
![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/district%20summary%20without%20THS%20data.png)

- In School summary, we noticed that the number of per_school_passing_math and number of per_school_passing_reading dropped which affected their percentage as well.

School Summary per_school_passing math

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/school%20summary%20per%20school%20passing%20math.png) 

New School Summary per_school_passing math

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/new%20school%20summary%20per%20school%20passing%20math.png)

School Summary per_school_passing_reading

![thi is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/school%20summary%20pr%20school%20passing%20reading.png)

New School Summary per_school_passing_reading

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/new%20school%20summary%20per%20school%20passing%20reading.png)

Per School Summary

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/Per%20School%20Summary.png)

New Per School Summary

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/New%20Per%20School%20Summary.png)

- Replacing the ninth graders’ math and reading scores made the Thomas High School one of the top high school performers from one of the lowest performers.
Top Performers

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/First%20five%20top%20performers.png)

- Replacing ninth grade scores with NaN
1. Math and Reading scores were not available.

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/Replace%20Ninth%20grade%20scores%20with%20NaN.png)

2. The replacement did not matter as long as the budget is same the spending range will be same.
3. The school size was not affected by the replacement.
4. scores by school type got affected ad the ninth graders became NaN the % passing math and % passing reading will drop.

![this is an image](https://github.com/dhwaniagrawal/School_District_Analysis/blob/main/Scores%20by%20School%20type.png)

-Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. Passing percentage math dropped.
2. Passing percentage reading dropped.
3. Overall Percentage Math and Reading dropped.
4. Average readng and math score dropped.
