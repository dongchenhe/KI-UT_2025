# "Assignment 2 - Haga-san Assignment Review by Dongchen He"

**1.a Is the assignment well structured?**

Yes,the assignment is well structured with a clear separation of the tasks.

**1.b Is the formatting appropriate?**

Yes, the formatting is appropriate using R markdown.

**2.a Are all the tasks addressed?**

Task 8 is missed out.

**3.a Are the given answers correct to the best of your understanding?**

- In Task 6 1/2, it is probably better to exclude the situation when the vector is not completely numeric or when median equals to 0 to avoid situations where the calculation cannot go smoothly. 

- In Task 7 2c, I personally did it with the understanding that the result should contain genes that have `>10%`/ `>20%`/ `>50% `missing values. But your code seems to show genes that have `>10% & <=20%`/ `>20% & <=50%`/ `>50%` missing values.

- In Task 7 2d, the provided code does not replace all the missing values since there are dozens of genes that are completely with missing values.

Otherwise the answers are correct to my understanding.

**4.a Do the provided analyses address the questions asked?**

Yes, the analyses address the questions asked.

**4.b Are the provided insights conclusive given the conducted analyses?**

Yes, given the conducted analyses, the provided insights are conclusive.

**5.a Is the provided R code well documented?**

Yes, the provided R code is well documented and easy to understand in general.Probably in Task 7 2b, the comment `#row is gene` could be more clarified as in `#make a new dataset using genes as rownames`. I misunderstood it in the first place thinking that the following code assumes that the rows represent genes in the original dataset, which would cause a major difference in the result.
