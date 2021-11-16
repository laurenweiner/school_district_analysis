# school_district_analysis

## Overview
The purpose of this analysis was to understand trends in student performance based on school size, type, and budget. Since we were working such a large sum of data, we paid special attention to ensuring the data was cleaned properly. Additionally, when dealing with highly sensitive data such as student's names and school spending, it is important to ensure the data is as accurate as possible.


## Results
Results: Using bulleted lists and images of DataFrames as support, address the following questions.

**District Summary** 

There was no difference between the district summary data once the Thomas High School data was edited.

Original:

<img width="422" alt="district summary 1" src="https://user-images.githubusercontent.com/92737670/141882205-be078beb-374b-443e-bf28-d6d98f9e28a1.png">

New:

<img width="434" alt="district summary" src="https://user-images.githubusercontent.com/92737670/141881502-22e00b17-0c43-4551-a6d5-c08a484e291d.png">

**School Summary**

Thomas High School's scores did not change once the ninth grade scores were dropped.

Original:

<img width="722" alt="school summary 1" src="https://user-images.githubusercontent.com/92737670/141882551-1b0cc484-bf92-472b-aa9a-693b923e1abf.png">

New:

<img width="725" alt="new new school summary" src="https://user-images.githubusercontent.com/92737670/141887155-25996618-c2a2-44ae-9da6-d495f48ad294.png">


**9th Grade Scores**

- Originally, Thomas High School was in the top 5 schools, performance wise. After the ninth grade scores were adjusted, they became one of the lower performing schools. 
- Replacing the ninth-grade scores has no affect on the other grade levels' scores in math in reading
- Replacing the ninth-grade scores had no affect on the grades for the spending group that Thomas High School fell in ($630 - $644)

Original Spending:

<img width="650" alt="spending old " src="https://user-images.githubusercontent.com/92737670/141885755-b0fd2a52-7a5f-489e-9e4e-7bb720dca1aa.png">

New Spending: 

<img width="643" alt="spending new" src="https://user-images.githubusercontent.com/92737670/141885772-ea04c2bc-4711-4abb-a560-60cd3c461b62.png">

- Replacing the ninth-grade scores had no affect on the grades for the medium sized schools

Original Size:

<img width="605" alt="size old" src="https://user-images.githubusercontent.com/92737670/141886113-a289fbad-1792-4386-9338-ba0743d98d93.png">

New Size: 

<img width="605" alt="size new" src="https://user-images.githubusercontent.com/92737670/141886106-61748a73-5830-4ed3-95e8-5b38b9c24df5.png">

- Replacing the ninth-grade scores had no affect on the grades for Charter schools.

Original Type: 

<img width="555" alt="type old" src="https://user-images.githubusercontent.com/92737670/141886358-45668f8c-8d0b-4833-872e-1ef23543cf54.png">

New Type: 

<img width="574" alt="new new type" src="https://user-images.githubusercontent.com/92737670/141887719-932f9e8e-5a6d-40e7-82b0-5510c0ba9ff6.png">


## Summary 
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are: 
- Percent of students in the district passing math dropped .1%
- Percent of students in the district passing reading dropped .1%
-  ... I'm sorry, I can't find any other differences :/ 
