# FM+ Terminology
This section decribes definitions for terminology used across the FM+ system. 

## Types of Rules ##
| Term | Definition |
| --- | --- |
| Basic Rules | Simple rule-based conditions applied to a single data source to detect fraud based on predefined thresholds|
| Multi-Source Rules | Rules that involve multiple data sources for detecting more complicated fraud patterns|
| Chain Rule | Advanced rules that use the output of one rule as the input for another rule|
| Infection Rate Rules | Number of suspicious cards relative to the total cards in a recharge batch |
| Infection Rate Calculation | The process of determining the infection rate by analyzing recharge batches and identifying the proportion of suspicious cards among same batch |
| Voucher Batch | A group of scratch cards analyzed within a defined serial number range around a detected number, helping identify potential fraud or bulk activations |
| IMSI Batch | A group of IMSI numbers analyzed together to identify additional suspicious numbers within the same IMSI block |
| Shared IMEI |A group of IMSI numbers analyzed together to Identify additional suspicious IMSI numbers linked to the same device |
| Chain Rule for Refining Suspects | Method used to narrow down suspect lists from machine learning models or external feeds by applying additional filters |
| Machine Learning Rules | Data-driven rules that use ML models to detect patterns, anomalies, and fraud more accurately than static rule-based methods|
| Rule Window | The aggregation period in which the rule conditions will be applied to the selected data source |
