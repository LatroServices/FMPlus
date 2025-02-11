# Create Rules
In FM+ under rule engine you'll be able to create 3 types of rules:

## BASIC Rules

1. Go to the FM+ portal and log in to your account
2. Go to SIM Box Module > Rule Summery page
3. On the *Rule Summery page*, select the *Basic Rules* tab
4. Click on *Create Rule* button.
5. Enter a Rule Name
6. Select the rule *Window* , window = The aggregation period in which the rule conditions will be applied to the selected data source."
7. Select the *Source*
8. Add new conditions by selecting *+RULE*
9. Group condition statements by selecting *+GROUP*
10. Apply the *AND* or *OR* statement by using the main drop-down.
11. Click on *Off-Net Rules* toggle if you want to create an Off-Net rule.
12. Click on *include in infection rate calculation* toggle if you want to include the rule in infection rate calculation.
13. To save the rule, use the *+ADD* button in the upper right corner of the page.

## Multi Source Rules

1. Go to the FM+ portal and log in to your account
2. Go to SIM Box Module > Rule Summery page
3. On the *Rule Summery page*, select the *Multi Source Rules* tab
4. click on *Create Rule* button.
5. Enter a Rule Name
6. Select the rule *Window* , window = The aggregation period in which the rule conditions will be applied to the selected data source."
7. Select the *Source*
8. Add new conditions by selecting *+RULE*
9. Group condition statements by selecting *+GROUP*
10. Apply the *AND* or *OR* statement by using the main drop-down.
11. Add in second data sources, using *+ ADD SOURCE* button.
12. Click on *include in infection rate calculation* toggle if you want to include the rule in infection rate calculation.
13. To save the rule, use the *+ADD* button in the upper right corner of the page.
    
## Chain Rules

1. Go to the FM+ portal and log in to your account
2. Go to SIM Box Module > Rule Summery page
3. On the *Rule Summery page*, select the *Chain Rules* tab
4. Click on *Create Rule* button.
5. Enter a Rule Name
6. Select the  *Chain Rule Category*

+ *Infection Rate for Vouchers*
7. Choose *Rule name*
8. Input *threshold * >=,>=,<,> *value*
9. Choose *Rule name*
10.Click on *Add conditions* button to add conditions.
  
+ *Voucher Batch*
11. Choose *Rule name*
12. Input *Voucher Block Size * +,- *value*
13. Choose input source *FM Rules* or *Client detections*.
14. If you chose *FM Rules* select rules from *Inout Source* drop down list.
15. Click on *Add conditions* button to add conditions.
  
+ *IMSI Batch*
16. Choose *Rule name*
17. Input *IMSI Block Size * +,- *value*
18. Choose input source *FM Rules* or *Client detections*.
19. If you chose *FM Rules* select rules from *Inout Source* drop down list.
20. Click on *Add conditions* button to add conditions.
  
+ *Shared IMEI*
21. Choose *Rule name*
22. Input *IMSIs to IMEIs * >=,>=,<,> *value*
23. Choose input source *FM Rules* or *Client detections*.
24. Click on *Add conditions* button to add conditions.
  
+ *Chain Rule for Refining Suspects*
25. Choose *Rule name*
26. Choose input source *FM Rules* or *Client detections*.
27. Click on *Add conditions* button to add conditions.

  
To save the rule, use the *+ADD* button in the upper right corner of the page.

# Viewing & Editing Existing Rules
1. Go to SIM Box Module > Rule summary to view a complete list of all existing rules on the system.
2. Click on desired tab.
3. Click on an existing rule to view the configuration details.
4. Once viewing an existing rules config details you can directly make any updates to the rule.
5. To save the changes, use the *UPDATE* button inn the uppoer right corner of the page. 

## Detection Downloader

There are two methods of access the detections page. 

 Method 1:
-      Go to Rule Summary > choose a Rule and click *View Detections* button
  Method 2:
-     Go to SIM Box Module > Detection Downloader.

Once you are on the *Detection Downloader* page
1. Apply any desired filters to view the detection results.
2. Use the *Download Detections* button to export the filtered list of detections to a CSV file.

## Rules Reporting

To enable any rule for reporting click on the toggle next to it from "Rule Summery" page.
