## Creating Chain Rules
1. Log in to **FM+ portal**.
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select the **Chain Rules** tab.
4. Click on **Create Rule**.
5. Enter a **Rule Name**.
6. Select the desired **Chain Rule Category** (see [definitions](../terminology/README.md)
   + Infection Rate for Vouchers 
   + Voucher Batch 
   + IMSI Batch 
   + Shared IMEI 
   + Chain Rule for Refining Suspects 
7. See corresponding steps for each category in sections below

#### **Infection Rate for Vouchers**
*Note: This category requires existing basic/multisource rules to be configured for **Infection Rate Calculation***
1. After selecing the **Chain Rule Category** of **Infection Rate for Vouchers**
2. Type the desired **Rule Name**.
3. Set **Threshold** using operators (>=, >, <, <=) and a value.
4. If desired to add in additional conditions to the rule, click **Add Conditions**, **Add Source**, and set the desired conditions.
5. Click **+ADD** (top-right corner)

#### **Voucher Batch**
1. After selecting the **Chain Rule Category** of **Voucher Batch**
2. Type the desired **Rule Name**.
3. Set **Voucher Block Size** (+ or - value).
4. Select input source (**FM Rules** or **Client Detections**).
5. If **FM Rules** is selected, choose from the **Input Source** dropdown.
6. If desired to add in additional conditions to the rule, click **Add Conditions**, **Add Source**, and set the desired conditions.
7. Click **+ADD** (top-right corner)

#### **IMSI Batch**
1. After selecting the **Chain Rule Category** of **IMSI Batch**
2. Type the desired **Rule Name**.
3. Set **IMSI Block Size** (+ or - value).
4. Select input source (**FM Rules** or **Client Detections**).
5. If **FM Rules** is selected, choose from the **Input Source** dropdown.
6. If desired to add in additional conditions to the rule, click **Add Conditions**, **Add Source**, and set the desired conditions.
7. Click **+ADD** (top-right corner)
   
#### **Shared IMEI**
1. After selecting the **Chain Rule Category** of **Shared IMEI**
2. Type the desired **Rule Name**.
3. Set **IMSIs to IMEIs Ratio** (>=, >, <, <= value).
4. Select input source (**FM Rules** or **Client Detections**).
6. If desired to add in additional conditions to the rule, click **Add Conditions**, **Add Source**, and set the desired conditions.
7. Click **+ADD** (top-right corner)

#### **Chain Rule for Refining Suspects**
1. After selecting the **Chain Rule Category** of **Chain Rule for Refining Suspects**
2. Type the desired **Rule Name**.
3. Select input source (**FM Rules** or **Client Detections**).
6. If desired to add in additional conditions to the rule, click **Add Conditions**, **Add Source**, and set the desired conditions.
7. Click **+ADD** (top-right corner)
