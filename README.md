# School District Analysis

### **Overview of School District Analysis**

* The purpose of this schoool district analysis was to re-evalute student reading and math scores as it relates to school size, school type, and spending per student assuming that all 9th grade scores from Thomas High School may be compromised. The analysis omits all Thomas High Schoool reading and maths scores as it calculates math and reading passing percentages and overall passing percentages for the district and each school. 

---
### **Results**

* As compared to the original district summary, omittimg the Thomas High School grades had a slight impact on all metrics by .1 interval. This is likely due to the fact that the average scores across all grades were relatively consistent however, omitting the 9th grades scores can account for a slight loss  in overall district performance as seen below between the two data sets:

###### Original School District Analysis
![District_Summaryv1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/District_Summaryv1.png)
###### New School District Analysis
![District_Summaryv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/District_Summaryv2.png)

* The school summary shows the greatest difference between the two analyses. As shown below, the Thomas High School performance is affected the greatest as the 9th grades scores now account for zeros in the calculations. After replacing the data to exclude Thomas High School 9th grades math and reading (only taking into account scores from 10th -12th grade, the Thomas High School data is more nominal. 

###### Original School District Analysis
![Per_Schoolv1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/Per_Schoolv1.png)
###### New School District Analysis
![Per_Schoolv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/Per_Schoolv2.png)

* You may find a more direct comparison of the Thomas High data below. The differences in the percentage of students passing either reading, math or both is dramatically reduced as the calculation takes into account all of the zeros now occupying the 9th grade scores:

###### Original School District Analysis
![ths_summaryv1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/ths_summaryv1.png)
###### New School District Analysis
![ths_summaryv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/ths_summaryv2.png)

* Overall Math and Reading scores are unchanged by grade as this data is indexed by school and the zero grades in the Thomas High School 9th grade scores only affect the Thomas High School data. See below:

###### New School District Analysis
![reading_scoresv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/reading_scoresv2.png)

* Scores by school spending saw a slight change (similar to that noticed in the district summary) when the 9th grades scores from Thomas High are omitted. Particularly in the $631 - $645 per capita spend range. It can be safely assumed that most of the 9th grade per capita spend landed within this range. See data highlights below:

###### Original School District Analysis
![school_spendingv1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/school_spendingv1.png)
###### New School District Analysis
![school_spendingv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/school_spendingv2.png)

* Similarly, scores by school size saw a slight change (~.1 interval) among Medium sized schools (those with student populations beetween 1000-1999):

###### Original School District Analysis
![school_sizev1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/school_sizev1.png)
###### New School District Analysis
![school_sizev2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/school_sizev2.png)

Finally, scores by school type saw a slight change, however, not as significant as other metrics (most likely because the 9th grade population is randomly distributed among charter and district schools). See data below:

###### Original School District Analysis
![type_summaryv1](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/type_summayv1.png)
###### New School District Analysis
![type_summaryv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/type_summayv2.png)

---
### **Summary**
Overall, there were four metrics significantly impacted by the omission of the Thomas High School 9th grade reading and math scores: 
1. **The Thomas High School Summary**
* It is clear that omitting the 9th grade scores, yet counting the 9th graders in the analysis had an adverse effect on the results for this                 school.
          
2. **The District Summary**
* Overall passing scores were slightly reduced (%65 vs 64.9%) as a result of the loss of 9th grade data from Thomas High School. 
 
3.**School Spending Per Student**
* It may be assumed that the 9th grade data accounted for a significant portion of the $631-$645 per capita spending range. As such, overall passsing math and reading percentages were slightly lower for this spend range (%62.85 prior to omitting the 9th grade data and %62.77 after). 

4.**Per School Reading and Math Scores**
* As demonstrated by the updated reading scores data below, replacing all Thomas High School reading and math scores with 'NaN' resulted in an overall loss of data for this analysis:

![reading_scoresv2](https://github.com/dpTuttle/School_District_Analysis/blob/main/Resources/reading_scoresv2.png)
