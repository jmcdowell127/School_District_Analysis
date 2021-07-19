# School_District_Analysis

## Overview of the school district analysis
The file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School 9th graders appear to have been altered. In order to uphold the state-testing standards, the math and reading scores of 9th graders at Thomas High School need to be replaced with null values (NaNs) while keeping the rest of the data in tact. After replacing these grades, an analysis of the school district needs to be repeated to display how these changes affected the overall analysis.


## Results
### District Summary

* The district summary was not affected as shown by the images below
  * District summary from the module
  ![1mod](https://user-images.githubusercontent.com/85372441/126084889-82dab2d7-fe4c-460a-a3ae-9bcf35e2d351.png)

  * District summary from challenge 
  ![1challenge](https://user-images.githubusercontent.com/85372441/126084828-7f512ea7-33d7-49d7-8dd7-806800ce1f1c.png)

### School Summary
* The school summary was only slightly affected. Thomas High School was the only school affected, in the instances below:
  * The average math score changed by ~ -0.06
  * The average reading score change by ~ +0.05
  * The percentage of students passing math changed by ~ -0.9
  * The percentage of students passing reading change by ~ -0.3
  * The overall percentage of students passing changed by ~ -0.3
  *
  * This image shows the school summary from the module
  * <img width="722" alt="2mod" src="https://user-images.githubusercontent.com/85372441/126085304-ce62c061-11b3-4172-beea-62ab3aa8cff4.png">
  *
  * This image show the school summary from the challenge 
  * <img width="721" alt="2challenge" src="https://user-images.githubusercontent.com/85372441/126085323-5c074731-2667-495d-9a63-298bd4eed5dd.png">

### Replacing 9th Graders' Math and Reading Scores  
* Relative to other schools, the replacement of the 9th graders' reading and math scores slightly affected Thomas High School's performance. There are three schools who were affected.
  * Cabrera High School is now performing better than Thomas High School in percentage of students passing reading.
  * Griffin High School is now performing better than Thomas High School in both average math score and percentage of students passing reading.
  * Shelton High School is now performing better than Thomas High School in average math score.
  * <img width="721" alt="3challenge" src="https://user-images.githubusercontent.com/85372441/126086498-076fa02c-9b38-40d4-931e-f56d4a7bb62c.png">


* Replacing the 9th grade scores affected the following:
  * Math and reading scores by grade were only affected for Thomas High School 9th graders, which are now null.
  * <img width="240" alt="4challenge" src="https://user-images.githubusercontent.com/85372441/126087244-1c84c94d-14a3-4663-9f73-0132d3baf81b.png">
  * <img width="238" alt="42challenge" src="https://user-images.githubusercontent.com/85372441/126087258-a241f639-7f86-41f1-a045-8eccfdb0550f.png">

  * Scores by school spending per student were not affected.
  * <img width="627" alt="5challenge" src="https://user-images.githubusercontent.com/85372441/126087296-ff19bacb-10b0-4ba0-82ba-9c723c4472bf.png">

  * Scores by school size were not affected.
  * <img width="566" alt="6challenge" src="https://user-images.githubusercontent.com/85372441/126087308-499dfb57-0e5b-4d4f-ab87-dbbd535eb67a.png">

  * Scores by school type were not affected.
  * <img width="535" alt="7challenge" src="https://user-images.githubusercontent.com/85372441/126087315-2c6deabe-4f40-4859-91ea-5d8127fad48d.png">


## Summary
In conclusion, there were four changes in the updated school district analysis after both the reading and math scores for 9th graders at Thomas High School were replaced with null values (NaNs). First, the school summary for Thomas High School changed in a 5 columns, but mostly in the percentage of students passing math column, which changed by ~ -0.9. Second, Thomas High School had a positive change, their average math score increased by ~ 0.05. Third, Griffin High School is now performing better than Thomas High School in both average math score and percentage of students passing reading. Fourth and last, Cabrera High School is now performing better than Thomas High School in percentage of students passing reading.
