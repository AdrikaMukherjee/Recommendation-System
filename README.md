The goal of this model was to recommend new products to customers of Santander Bank. This was done by comparing the products that a customer had in each month with the previous month. If a customer had a new product in a given month, that month's data would be used to train the model. In order to avoid recommending products that a customer already had, the month prior to the prediction, May 2016, would be compared to the prediction month, June 2016. Any products that a customer had in May 2016 would be removed from the prediction set.

As part of the requirements for the Kaggle competition, only seven products were needed to be recommended to each customer. The seven products that were most frequently recommended were (English translations are in paraeneses): ind_recibo_ult1 (Direct Debit), ind_nom_pens_ult1 (Pensions), ind_nomina_ult1 (Payroll), ind_cco_fin_ult1 (Current Accounts), ind_tjcr_fin_ult1 (Credit Card), ind_cno_fin_ult1 (Payroll Account), and ind_ecue_fin_ult1 (e-account).

The seven most common products that customers already had were: ind_cco_fin_ult1(Current Accounts), ind_recibo_ult1 (Direct Debit), ind_ctop_fin_ult1 (Particular Account), ind_ecue_fin_ult1 (e-account), ind_cno_fin_ult1 (Payroll Account), ind_nom_pens_ult1 (Pensions), and ind_nomina_ult1 (Payroll).

Kaggle Link: https://www.kaggle.com/c/santander-product-recommendation/data
