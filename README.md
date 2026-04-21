# AB_test_Premium_Subscription_Pricing_Experiment

Link Google Colab:
https://colab.research.google.com/drive/1md8Kk11n0b-DbLH1XCk_AhttRf8Mijes

# Business Task:

In a mobile application, users are offered a weekly premium subscription for $4.99 immediately after onboarding. 
The goal is to increase the conversion rate from onboarding to purchase. 
We decided to test an alternative paywall design where the subscription is still priced at $4.99, 
but it is presented as a "50% discount" offer to increase the perceived value.

# Hypothesis:

Using an alternative paywall design with a "50% discount" claim will increase the offer's perceived value, 
leading to a higher conversion rate compared to the standard price presentation.

# Implementation:

- Formulated Null and Alternative hypotheses.
- Defined user segmentation and exclusion criteria.
- Identified primary (Conversion Rate) and secondary metrics (ARPU, Churn).
- Calculated required sample size and test duration using a power calculator.
- Defined success criteria and significance levels.
- Used Student's t-test in Python for hypothesis testing and result evaluation.

# Results:

The difference between the groups is statistically significant. The Null hypothesis was rejected.   
The data convincingly proves that the "discounted subscription" variant outperforms the control group, and the result is not due to chance or sampling error.   
Users responded better to the alternative design, resulting in a higher purchase rate for the same price point.  
Visualized group means with 95% confidence intervals.  
The A/B test resulted in a 2.8pp conversion uplift, driving the purchase rate from 6.1% to 8.9% with statistical significance.  

# Next Steps:

Rollout: Implement the "discounted" variant as the default paywall for all users.  
Urgency Test: A/B test a countdown timer to create a sense of urgency.  
Free Trial Experiment: Test a "3-day Free Trial, then $4.99/week" model to lower the entry barrier and demonstrate premium value before the first charge.  


