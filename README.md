# School_District_Analysis

## Overview

The purpose of this analysis is to review the changes to the school and district statistics now that we have removed the possibly altered test scores of the 9th graders from Thomas High School. We will be seeing how it affects the numbers, and if it changes the ranking of the schools. 

## Results

### District Summary

Original Data:

![1A](https://user-images.githubusercontent.com/100896787/165876085-c66df6f7-23e4-42b5-be30-1508fcaaf001.PNG)

Modified Data:

![1B](https://user-images.githubusercontent.com/100896787/165876096-82c63110-48bd-4267-8a5e-fe8a3a1a34e0.PNG)
* As expected, the numbers for the district summary decreased after removing the scores of the cheating students. 
* Since it was a small number of students removed, the numbers did not decrease dramatically.
* Average math score decreased while average reading score stayed the same. It is possible that the students were showing academic dishonesty in one subject rather than both. However, we did remove both subjects and overall scores from the students, which does affect the percentages. 

### School Summary

Original Data:

![2A](https://user-images.githubusercontent.com/100896787/165877052-2e6743bc-9069-4238-bdce-f35b029c4d6f.PNG)

Modified Data:

![2B](https://user-images.githubusercontent.com/100896787/165877055-0e7e297d-5365-4215-b92d-d814bc0c3620.PNG)

* Despite removing data of the 9th graders at Thomas High School, the average scores and percentage of students passing remains around the same. 
* It's important to note that we omitted the 9th grade data. If we were able to obtain their real scores, there is a chance that Thomas High School's overall numbers may fall. 

### Thomas High School Performance

Original Data:

![3A](https://user-images.githubusercontent.com/100896787/165877423-39de057c-ad48-41ed-9e5a-fef42bf748f0.PNG)

Modified Data:

![3B](https://user-images.githubusercontent.com/100896787/165877552-5c4e95ee-295f-4147-9293-53dc2f443cf0.PNG)

* Even without their 9th grade population, Thomas High School remains at second place in school rankings. This goes to show how succesful the students at the school are. 
* They are very close to losing out to Griffin High School who is currently in third place. Without their 9th grade data, the difference between the schools' overall passing percentage decreases from .349 to .031, making it a very close game. 

### Scores By:

* Grade: Replacing the ninth grade scores would not affect the reading/math scores by grade, as those are all based on individual schools and each grade. For example, the tenth, eleventh, and twelfth graders at Thomas High School would remain the same as the ninth grade scores are not calculated into their averages.
* Spending Size: Because spending ranges are calculated per student, this does not affect the scores by spending size. 
* School Size: Thomas High School remains in the same bin, so it does not affect the scores by school size. 
* School Type: Thomas High School remains a charter school, so it does not affect the scores by school type. 

## Summary
After changing the reading and math scores for the ninth graders at Thomas High School, we can see that it directly affects the following 4 items:
* Thomas High School's math and reading scores
* Thomas High School's percentage passing math, reading, and overall
* The district's math and reading scores
* The district's percentage passing math, reading, and overall

These items are affected due to the fact that the ninth graders had high scores, ultimately boosting up their school and district data. Items such as grade data, spending size, school size, and school type are not affected because the factors that affect those were not tampered with. 
