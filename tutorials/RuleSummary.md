# Create Rules
in FM+ under rule engine you'll be able to create 3 types of rules:

## BASIC Rules

1. Go to the FM+ portal and log in to your account
2. Go to SIM Box Module > Rule Summery page
3. On the *Rule Summery page*, select the *Basic Rules* tab
4. click on *Create Rule* button.
5. Enter a Rule Name
6. Select the rule *Window* , window = The aggregation period in which the rule conditions will be applied to the selected data source."
7. Select the *Source*
8. Add new conditions by selecting *+RULE*
9. Group condition statements by selecting *+GROUP*
10. Apply the *AND* or *OR* statement by using the main drop-down.
11. click on *Off-Net Rules* toggle if you want to create an Off-Net rule.
12. click on *include in infection rate calculation* toggle if you want to include the rule in infection rate calculation.
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
11. add in second data sources, using *+ ADD SOURCE* button.
12. click on *include in infection rate calculation* toggle if you want to include the rule in infection rate calculation.
13. To save the rule, use the *+ADD* button in the upper right corner of the page.
    
## Chain Rules

1. Go to the FM+ portal and log in to your account
2. Go to SIM Box Module > Rule Summery page
3. On the *Rule Summery page*, select the *Chain Rules* tab
4. click on *Create Rule* button.
5. Enter a Rule Name
6. Select the  *Chain Rule Category*

+ *infection Rate for Vouchers*
7. choose *Rule name*
8. input *threshold * >=,>=,<,> *value*
9. choose *Rule name*
10. lick on *Add conditions* button to add conditions.
  
+ *Voucher Batch*
11. choose *Rule name*
12. input *Voucher Block Size * +,- *value*
13. choose input source *FM Rules* or *Client detections*.
14. if you chose *FM Rules* select rules from *Inout Source* drop down list.
15. click on *Add conditions* button to add conditions.
  
+ *IMSI Batch*
16. choose *Rule name*
17. input *IMSI Block Size * +,- *value*
18. choose input source *FM Rules* or *Client detections*.
19. if you chose *FM Rules* select rules from *Inout Source* drop down list.
20. click on *Add conditions* button to add conditions.
  
+ *Shared IMEI*
21. choose *Rule name*
22. input *IMSIs to IMEIs * >=,>=,<,> *value*
23. choose input source *FM Rules* or *Client detections*.
24. click on *Add conditions* button to add conditions.
  
+ *Chain Rule for Refining Suspects*
25. choose *Rule name*
26. choose input source *FM Rules* or *Client detections*.
27. click on *Add conditions* button to add conditions.

  
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

to enable any rule for reporting click on the toggle next to it from "Rule Summery" page.
