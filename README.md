# Business-Case-LoanTap-Logistic-Regression
LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

1- What percentage of customers have fully paid their Loan Amount?
  
    Answer: Around 80.38% of customers have fully paid their Loan Amount.

2.  Comment about the correlation between Loan Amount and Installment features.

   Answer: There is very high co-relation between loan amount and installment. pearson co-efficient is ~ 0.95.  
                      This indicates high multi-collinearity between these two features.
                      Hence installment column is drop while creating model.

3.  The majority of people have home ownership as ?

   Answer:  Mortaged and then followed by rent.  With 50.07% and 40.35% in order.

4. People with grades â€˜Aâ€™ are more likely to fully pay their loan. (T/F)

   Answer: True. Out of all people with grade 'A',  ~ 92-93% got their loan approved.

5.  Name the top 2 afforded job titles.

    Answer: Teacher & Manager

6.  Thinking from a bank's perspective, which metric should our primary focus be on
ROC-AUC : Not good metric to consider as we have highly imbalanced data.
Precision: Consider when only want to reduce NPA
Recall: Consider when we do not want to miss good opportunity for providing loan to customer
F1-score: Good metric for us, because we want to consider both Precision and Recall.
        Answer: F1-Score

7.  How does the gap in precision and recall affect the bank?
 Recall score: 0.98 and Precision score: 0.81. which tells us that there are more false positives than the false negatives. 

If Recall value is low,  it means Bank is loosing in opportunity cost.

If Precision value is low, it means Bank's NPA (defaulters) may increase.
8. Which were the features that heavily affected the outcome?

Answer:  Few important features are 
* Loan sub-grade
* Annual Income
* Interest rate
* Mortgaged accounts
* Purpose
* Application Type
* Employment Length
* Home Ownership
* term : number of payments on the loan debt to income ratio
     
9. Will the results be affected by geographical location?
 
Answer:  Yes. Few states have high changes of getting loan compare to other states.
