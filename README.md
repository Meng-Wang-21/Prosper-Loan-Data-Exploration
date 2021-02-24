# Prosper-Loan-Data-Exploration

## Dataset

> This dataset is related to loans during 2007-2014. There are 113937 loans and 81 variables including term, date, APR and information about the borrowers such as income range and available bank card credit when open the current loan. We'll pick up around 10 variables to do further analysis and see what's affecting borrower APR.


## Summary of Findings

> For every income range, it's clear that higher available bank card credit usually has a lower APR. And with higher bank card utilization, APR goes high across all of the income range.

> For 12 months loan, the APR level is a mix. There are a lot of borrowers who applied low APR and also there are a lot of them applied high APR. And it seems available bank card credit doesn't have a big influence on the change of APR for term=12. But for term=36/60, the APR is lower and more relavant to available bank card credit. With high available bank card credit, the APR is lower.
In terms of high income range, the BorrowerAPR didn't change much across different terms. But for low income range, shorter term tend to have higher APR.

> Low APR range(0.1-0.2) doesn't show a clear trend that higher income has lower borrowerAPR. While high APR range(0.3-0.4) shows a clear trend that higher income has lower borrowerAPR.



## Key Insights for Presentation

> It's interesting to see how term affects APR. Longer term tend to have a lower APR and available bank card credit makes a difference. Also, the most critical factor deciding APR is income range, which is understandable, high income can represent less risk. But for income > 25,000, the APR difference is not very obvious and available bank card credit plays a big role. Based on the observation of relationship between income range and Monthly loan payment, high income tend to have high monthly loan payment. Then if we dig deeper and plot income range, Monthly loan payment and available bank card credit, we could see high income people usually have high monthly loan payment. That can explain why income range didn't affect the APR when available bank card credit is the same. If a hoursehold has a high income but high monthly loan payment, the bank won't give it a very low APR.
