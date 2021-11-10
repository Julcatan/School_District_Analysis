# School_District_Analysis

Overview of the school district analysis: Explain the purpose of this analysis.
The school board has discovered evidence for academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders seem affecteed   
The  purpose of the Analysis is to repeat the school district analysis, remove the affected grades as discussed with the school board and write up a report to describe how these changes affected the overall analysis.


## Results: 

 ### How is the district summary affected?

  - The grades of Thomas High School ninth graders were replaced with NaN. The replacement did not significantly affect the school district summary.
      

School district summary after update:

![image](https://user-images.githubusercontent.com/91682586/141134420-19ed6785-6978-4ce6-884a-1763e7bf39d6.png)

School district summary before:

![image](https://user-images.githubusercontent.com/91682586/141134551-9b646c46-dbee-4990-90fb-023e2a8a7608.png)


How is the school summary affected?

Per School summary before:

![image](https://user-images.githubusercontent.com/91682586/141133669-9feb2538-cea5-488e-8247-b34ffa41f747.png)

Replacing the scores of the ninth graders with NaN affects Thomas High School as follows: 

   - The Math Scores decreased by 0.07
   - The Reading Scores increased by 0.05
   - The % Passing Math for Thomas High School decreased from 93.3% to 66.9%
   - The % Passing Reading for Thomas High School decreased from 97.3% to 69.7% 
   - The Overall % Passing rate for Thomas High School decreased from 91% to 65.1%   

Per School summary after replacing 9th grade scores with NaN:

![image](https://user-images.githubusercontent.com/91682586/141134167-45fe98b2-dd67-4183-9080-32f8cf2a12dd.png)

When we removed the ninth grade from the calculation it affected Thomas High School as follows.

  - The math scores decreased by 0.7
  - The reading scores increased by 0.05
  - The % Passing Math decreased from 93.3% to 93.2%
  - The % Passing Reading decreased from 97.3% to 97%
  - The Overall Passing % decreased 90,9% to 90.6%
  
![image](https://user-images.githubusercontent.com/91682586/141144376-dff8fed1-0a2b-452f-a62d-49563f310502.png)


The other data in the summary was not affected.


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The changes did not affect the order of the Top Schools. Thomas High is still the 2nd best school.

Top Schools after update:

![image](https://user-images.githubusercontent.com/91682586/141137327-9b29d110-95bb-4fe5-b745-cfd037e92ca3.png)


Bottom Schools after update: 

![image](https://user-images.githubusercontent.com/91682586/141137404-035e65d0-e5cc-4c98-8e53-c41f2f221c15.png)


Top Schools before:

![image](https://user-images.githubusercontent.com/91682586/141136747-1f7b8ca8-3afa-4123-a8ba-d0594fa12952.png)


Bottom Schools before:

![image](https://user-images.githubusercontent.com/91682586/141136874-6ffb8107-bf99-4f6a-93cf-27eecbc8bae3.png)


### How does replacing the ninth-grade scores affect the following:

  #### Math and reading scores by grade
  
  The only change is that Thomas High 9th grade scores are not beeing counted.
  We will look at the total average to see what the influence of this update was.
___
  ###### Reading after update:
  
  ![image](https://user-images.githubusercontent.com/91682586/141183817-965dbaaa-3e1c-4808-999e-35bb3a72c1d6.png)


  
  ###### Math after updatee:
  
  ![image](https://user-images.githubusercontent.com/91682586/141183028-4f710864-73fb-4fbf-8383-a600d65bc35e.png)


  ###### Reading before: 
  
  ![image](https://user-images.githubusercontent.com/91682586/141182445-1fda642d-4336-4d09-aa85-c2367ade3bde.png)
  
  ######  Math before: 
  
  ![image](https://user-images.githubusercontent.com/91682586/141182525-08aa6802-b4b6-4543-97f2-3677d1acbe8a.png)

___
  
- Scores by school spending:
The scores by school spending did not change.


 ![image](https://user-images.githubusercontent.com/91682586/140995639-c2baea34-3738-4942-921d-2256124e3dbf.png)


before: ![image](https://user-images.githubusercontent.com/91682586/141182719-75317b0b-8d30-48ab-a440-f61fbf7fdc50.png)

___
 - Scores by school size:
 The scores by school size did not change.
 
![image](https://user-images.githubusercontent.com/91682586/140995815-51b05cd0-83ab-4876-a590-d8e6480d7204.png)

before:

![image](https://user-images.githubusercontent.com/91682586/141182089-f93f9576-b3bb-4fe3-b90b-4f2657ce92c7.png)
---
 - Scores by school type

after update:

![image](https://user-images.githubusercontent.com/91682586/140995899-da08c16a-f973-47ca-b69d-d9de991c71c3.png)

before: 

![image](https://user-images.githubusercontent.com/91682586/141182197-2f1ef6e8-a7ce-48eb-b277-d0987f4d7d82.png)
---
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

-The Overall % Passing rate for Thomas High School decreased from 91% to 65.1% 
-The changes did not affect the rranking of the Top Schools. 
-Math and reading scores by grade
-Thomas High 9th grade scores are not beeing counted in the Reading and Math by grade summary
-The changes affected all data points in the school summary at a small degree but the changes are not signifikantly altering the results.
