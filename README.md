# School District Analysis
## Overview of Project

### Purpose
The purpose of this project is to import and manipulate the raw CSV files schools_complete.csv and students_complete.csv in the Jupyter Notebook framework. By doing so, we can remove errors in the data and generate useful logistics from the various schools in the district, including sets before and after alteration. The tools primarily used to accomplish these tasks come from the Pandas dataframe structure, allowing functions that can interact with the imported dataframe. 

## Results 

### How is the district summary affected?
The change isn't that significant, but the passing percent in reading, math, and overall have all dropped slightly. A before and after is listed below.

![image](https://user-images.githubusercontent.com/77989740/142297117-31b35d3f-12b6-49fe-ba75-c3652ac5d746.png)
![image](https://user-images.githubusercontent.com/77989740/142297198-317e93be-e40a-46c2-9608-96b0ef6d8535.png)

### How is the school summary affected?
We can see on the before and after summaries below, the percentage of students passing math, reading, and both still decreases. This shows the 9th graders of Thomas High School had a higher average score than the rest of the combined school, which supports the theory of academic dishonesty.

![image](https://user-images.githubusercontent.com/77989740/142297443-4e013fa1-8151-40ed-8b9a-6c822ccf8339.png)
![image](https://user-images.githubusercontent.com/77989740/142297496-c261b46f-a3f2-48a6-b9c1-555bb3f3ed90.png)


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In this before and after, we can see that Thomas High School's performance remains among the highest in the district regardless of the 9th graders' inclusion.

![image](https://user-images.githubusercontent.com/77989740/143947151-a9399804-3612-4afb-8237-45cc9ab83cf0.png)
![image](https://user-images.githubusercontent.com/77989740/143947208-cfac3ad0-8c31-44ac-89af-dcd1bc8d8107.png)

### How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade

The only change is the exclusion of Thomas High School's 9th grade class, listed as nan

![image](https://user-images.githubusercontent.com/77989740/143949074-a114f0c2-3b49-4f5e-be54-1f6c042c8b1b.png)

*Scores by school spending

The applicable spending category, $630-$644 per student, saw the overall passing percent drop by less than 0.1% across all categories.

*Scores by school size

The medium school size also saw the slightest decrease in individual and overall passing percentages.

*Scores by school type

The Charter school type likewise saw extremely marginal decreases in passing percentages.

## Summary
The overall school district analysis includes a large quantity of data across the 15 schools of the district. Each of these schools includes the four grades 9th-12th, making the single 9th grade class of Thomas High School only 1/60th of the total data considered before their removal. Their above average scores, even for the high ranking Thomas High School, left little impact in the final results. However, we can see the small effects found all showed a decrease in average math score, average reading score, average passing math percent, and average passing reading percent in the district.
