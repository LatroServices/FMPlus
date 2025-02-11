# Create Rules in FM+

## Table of Contents
- [Introduction](#introduction)
- [Basic Rules](#basic-rules)
- [Multi-Source Rules](#multi-source-rules)
- [Chain Rules](#chain-rules)
- [Viewing & Editing Existing Rules](#viewing--editing-existing-rules)
- [Detection Downloader](#detection-downloader)
- [Rules Reporting](#rules-reporting)

---

## Introduction
FM+ allows users to create and manage rules under the **Rule Engine** module. Users can define three types of rules: **Basic Rules**, **Multi-Source Rules**, and **Chain Rules**. 

---

## Basic Rules
1. Log in to the **FM+ portal**.
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select the **Basic Rules** tab.
4. Click on **Create Rule**.
5. Enter a **Rule Name**.
6. Select the **Rule Window** (aggregation period for rule conditions).
7. Choose the **Source**.
8. Add new conditions by clicking **+RULE**.
9. Group condition statements using **+GROUP**.
10. Apply **AND/OR** conditions using the main dropdown.
11. Enable **Off-Net Rules** if required.
12. Toggle **Include in Infection Rate Calculation** if needed.
13. Click **+ADD** (top-right corner) to save the rule.

---

## Multi-Source Rules
1. Log in to **FM+ portal**.
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select the **Multi-Source Rules** tab.
4. Click on **Create Rule**.
5. Enter a **Rule Name**.
6. Select the **Rule Window**.
7. Choose the **Source**.
8. Add conditions using **+RULE**.
9. Group conditions with **+GROUP**.
10. Apply **AND/OR** logic.
11. Add a **Second Data Source** using **+ ADD SOURCE**.
12. Toggle **Include in Infection Rate Calculation** if required.
13. Click **+ADD** to save the rule.

---

## Chain Rules
### Creating a Chain Rule
1. Log in to **FM+ portal**.
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select the **Chain Rules** tab.
4. Click on **Create Rule**.
5. Enter a **Rule Name**.
6. Select a **Chain Rule Category**:

#### **Infection Rate for Vouchers**
7. Choose **Rule Name**.
8. Set **Threshold** using operators (>=, >, <, <=) and a value.
9. Click **Add Conditions**.

#### **Voucher Batch**
10. Choose **Rule Name**.
11. Set **Voucher Block Size** (+ or - value).
12. Select input source (**FM Rules** or **Client Detections**).
13. If **FM Rules** is selected, choose from the **Input Source** dropdown.
14. Click **Add Conditions**.

#### **IMSI Batch**
15. Choose **Rule Name**.
16. Set **IMSI Block Size** (+ or - value).
17. Select input source (**FM Rules** or **Client Detections**).
18. If **FM Rules** is selected, choose from the **Input Source** dropdown.
19. Click **Add Conditions**.

#### **Shared IMEI**
20. Choose **Rule Name**.
21. Set **IMSIs to IMEIs Ratio** (>=, >, <, <= value).
22. Select input source (**FM Rules** or **Client Detections**).
23. Click **Add Conditions**.

#### **Chain Rule for Refining Suspects**
24. Choose **Rule Name**.
25. Select input source (**FM Rules** or **Client Detections**).
26. Click **Add Conditions**.

To save the rule, click **+ADD** (top-right corner).

---

## Viewing & Editing Existing Rules
1. Navigate to **SIM Box Module > Rule Summary**.
2. Select the desired rule type tab.
3. Click on an existing rule to view its configuration.
4. Modify the rule as needed.
5. Click **UPDATE** (top-right corner) to save changes.

---

## Detection Downloader
To download detections from rules:
- Navigate to the **Detection Downloader** section and select the required rules for download.

---

## Rules Reporting
To enable reporting for any rule:
- Toggle the **Reporting** option next to the rule in the **Rule Summary** page.

