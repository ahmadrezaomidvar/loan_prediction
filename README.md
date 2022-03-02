# loan_prediction

Final assignment of [Machine Learning with Python](https://www.coursera.org/learn/machine-learning-with-python?specialization=ibm-data-science) course in [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science).

Dataset is about past loans includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |



The following algorithms are used to build differnet models: 
- k-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression. 

The results are reported as the accuracy of each classifier, using the following metrics when applicable: Jaccard index, F1-score, Log Loss.
