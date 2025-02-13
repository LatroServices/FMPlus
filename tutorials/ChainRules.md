
## Viewing & Editing Existing Rules
1. Log in to the **FM+ portal**
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select **Chain Rules** tab.
4. Click on an existing rule to view its configuration.
5. Modify the rule as needed.
6. Click **UPDATE** (top-right corner) to save changes.


## Create Rules

1. Log in to **FM+ portal**.
2. Navigate to **SIM Box Module > Rule Summary**.
3. Select the **Chain Rules** tab.
4. Click on **Create Rule**.
5. Enter a **Rule Name**.
6. Select a **Chain Rule Category**:

#### **Infection Rate for Vouchers**
+ Choose **Rule Name**.
+ Set **Threshold** using operators (>=, >, <, <=) and a value.
+ Click **Add Conditions**.

#### **Voucher Batch**
+ Choose **Rule Name**.
+ Set **Voucher Block Size** (+ or - value).
+ Select input source (**FM Rules** or **Client Detections**).
+ If **FM Rules** is selected, choose from the **Input Source** dropdown.
+ Click **Add Conditions**.

#### **IMSI Batch**
+ Choose **Rule Name**.
+ Set **IMSI Block Size** (+ or - value).
+ Select input source (**FM Rules** or **Client Detections**).
+ If **FM Rules** is selected, choose from the **Input Source** dropdown.
+ Click **Add Conditions**.

#### **Shared IMEI**
+ Choose **Rule Name**.
+ Set **IMSIs to IMEIs Ratio** (>=, >, <, <= value).
+ Select input source (**FM Rules** or **Client Detections**).
+ Click **Add Conditions**.

#### **Chain Rule for Refining Suspects**
+ Choose **Rule Name**.
+ Select input source (**FM Rules** or **Client Detections**).
+ Click **Add Conditions**.


7. To save the rule, click **+ADD** (top-right corner).

---

## Detection Downloader
To download detections from rules check:
[Detection Downloader](../tutorials/DetectionDownloader.md)

---

## Rules Reporting
To enable reporting for any rule:
- Toggle the **Reporting** option next to the rule in the **Rule Summary** page.
