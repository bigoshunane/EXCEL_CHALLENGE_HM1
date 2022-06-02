# Kickstarter Analysis

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.


## Project objective

The main aim of this project is to organize and analyze a database of 4,000 past fund raising kickstarter projects to uncover hidden trends.

Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

## Results

### 1. Kickstar Table

-  Conditional formatting was implimented to fill in each cell in the "state" and "Percent Funded" column with different color, depending on  
   whether the associated campaign was successful, failed, or canceled, or is currently live. The "Percent Funded" also is newly created to 
   uncover how much money a campaign made to reach its initial goal.
  
 ![kickstart table](https://user-images.githubusercontent.com/84547558/168671178-f088e37d-9071-464b-be8b-b75732fe92da.png)

### 2. Category stats-outcomes based on category

-  Another column P called "Average Donation" was created that uses a formula to uncover how much each backer for the project paid on average.
-  Two new columns, one called "Category" at Q and another called "Sub-Category" at R, which uses formulas to split the "Category and 
    Sub-Category" column into two-part was created.
-  A pivotal table was analyzed, and implemented to see the initial worksheet to count how many campaigns were successful, failed, canceled, or
    are currently live per category. In addition to that, a stacked column pivot chart that can be filtered by country based on the table has 
    been created.
    
![catagory stats](https://user-images.githubusercontent.com/84547558/168671302-60af1d95-274f-4d32-8e2a-da453d70e5a2.png)

### 3. Sub category stats-Outcomes based on sub category-Pivot Table

 -  A new sheet with a pivot table was created and analyzed the initial sheet to count how many campaigns were successful, failed, or canceled, or 
 are currently live per sub-category. In addition to that, a stacked column pivot chart was created that can be filtered by country and
 parent-category.
    
![sub catagory stats](https://user-images.githubusercontent.com/84547558/168671407-79561d13-47dc-4db5-a12b-f0f5028418e9.png)

### 4. Outcomes based on launch date

- The format of dates stored within the "deadline" and "launched_at" columns was converted from Unix timestamps format into Excel's date format and
  new columns named "Date Created Conversion" and "Date Ended Conversion" was created respectively.
- A new sheet with a pivot table was created with a column of "state",rows of "Date Created Conversion", values based on the count of "state", 
  and filtered based on "parent category" and "Years". Subsequently, a pivot chart line graph that visualizes this new table was created. "Date 
  Created Conversion", values based on the count of "state", and filtered based on "parent category" and "Years". Subsequently, a pivot chart 
  line graph that visualizes this new table was created.
  
  ![outcomes based on launch dates](https://user-images.githubusercontent.com/84547558/168672718-46f80437-8fc2-4c1e-b076-233c13ddee4e.png)


## Conclusion

As observed under category people participated in the fund campaigns did not seem to be contributing to journalism, in my opinion most journalists today are not more relevant to communities due to many reasons such as technological advancement where citizens could easily get access to relevant information online and the credibility of journalists on not reporting true stories rather agenda driven skewed information. The number of backers who have contributed to the campaigns are from United States followed by United Kingdom and Canada respectively.
Plays have been successfully funded under sub-category among others by far amount followed by rocks and documentary which were slightly funded. The campaign hits its highest success between May and June, then slightly drops through December. The lists of the countries were not orderly set that to assign currency symbols it was tedious. Moreover, the zero values in the data set resulted in error calculations particularly with average calculation where denominator must be used. Given this data set we can also be able to create statistical table to characterize the quantitate metrics.


© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
