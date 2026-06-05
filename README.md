# Clinical Trial Quality Control & CAPA Dashboard

## 📌 Project Overview
During clinical trial operations, ensuring the compliance of **Informed Consent Forms (ICFs)** is critical for regulatory audits and patient safety. This project simulates a clinical trial quality control process, identifying non-compliance trends and proposing a structured **CAPA (Corrective and Preventive Action)** framework.

## 📊 The Problem & Clinical Context
In multi-national clinical trials, tracking protocol-to-ICF alignment often reveals critical issues that can delay research or breach GCP (Good Clinical Practice) guidelines. 

Based on clinical trial audits, three main non-compliance types were analyzed:
* **Version Non-Compliance:** Discrepancies between the approved protocol version and the ICF signed by the patient.
* **Samples Non-Compliance:** Issues related to biorepository tracking and biological sample utilization consent.
* **Results Sharing NC:** Lack of precise language and tracking regarding how genetic/pharmacogenetic results are shared with participants.

## 💡 Proposed CAPA Solutions
To resolve these issues, this project implements a data-driven approach:
1. **Version NC:** Introduction of a standardized *Tracking Tool* to monitor protocol amendments against active site logs.
2. **Samples NC:** Utilizing a *Uniform Source* (Biorepository Memo) to streamline baseline sample compliance.
3. **Results Sharing NC:** Enhancing specific language verification protocols within the PGx ICF workflow.

## 🔍 Key Insights from the Audit Data
By analyzing the uploaded dataset (`clinical_trials_deviation_data.xlsx`), several critical regulatory and operational insights were uncovered:

1. **Primary Compliance Risks:** **Version Non-Compliance** and **Samples Non-Compliance** represent 66% of all tracked deviations, showing that sites struggle most with protocol amendments and biorepository tracking.
2. **Site Specific Performance Issues:** *Ichilov Hospital* demonstrates the highest resolution time for deviations (averaging 10.5 days), specifically around biological samples consent. This indicates a clear need for targeted GCP (Good Clinical Practice) retraining at this site.
3. **Operational Efficiency:** *Rambam* and *Soroka* Medical Centers show the fastest CAPA (Corrective and Preventive Action) implementation, resolving issues in less than 3 days.

## 🛠️ Tools & Tech Stack
* **Excel / Python:** For generating and structuring the mock clinical trial audit dataset - [clinical_trials_deviation_data](clinical_trials_deviation_data.xlsx).).
* **Power BI (Coming Soon):** Interactive dashboard visualizing site performance, deviation types, and CAPA resolution times.
