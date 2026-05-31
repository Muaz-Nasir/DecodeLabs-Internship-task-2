# 📊 Project 2: Exploratory Data Analysis (EDA)

---

## 📌 Project Overview
Welcome to my repository for **Project 2: Exploratory Data Analysis (EDA)**. Moving past simple static reporting, this project operates as a **forensic investigation of enterprise digital evidence** to uncover the true underlying business patterns, volume trends, and statistical center of gravity within our operational transactions. 

Following the strict guidelines of the **DecodeLabs Training Kit**, this phase acts as a foundational bridge to professional data intelligence. By building structural Python algorithms, this script ensures absolute data integrity before any predictive modeling or business dashboard compilation takes place.

---

## 🧠 Diagnostic Framework: The IPO Model
This analytical asset is architected strictly around the enterprise **Input-Process-Output (IPO)** engineering architecture:

1. **INPUT (The Evidence):** Ingestion of raw business logs (`Dataset for Data Analytics.xlsx`) containing 1,200 commercial transaction rows across 14 data pillars (including `OrderID`, `Date`, `Product`, `TotalPrice`, `Quantity`, and `CouponCode`).
2. **PROCESS (The Investigation):** Execution of data sanitization, date normalization, categorical frequency counts, and multi-point descriptive distributions (Five-Number Summaries).
3. **OUTPUT (The Verdict):** Generation of granular terminal data profiling logs and an independent production-ready dataset asset (`Cleaned_Data_Analytics_Dataset.xlsx`).

---

## 🛠️ Automated Processing Architecture

The script performs the following core structural tasks sequentially:
* **Missing Evidence Imputation:** Identifies blank strings (`NaN`) within promotional tracking arrays and fills them with a structural `"NO_COUPON"` flag to secure continuous catalog calculations.
* **Temporal Normalization:** Coerces messy date elements into a unified mathematical standard (`YYYY-MM-DD`). Corrupted or misaligned date entries are structurally trapped and safely logged as `NaT` (Not a Time) anomalies without crashing the operational runtime.
* **Primary Key Verification (Deduplication):** Validates that `OrderID` functions as a true unique identifier by scanning for double-entries and executing strict record deduplication.
* **Univariate Statistical Analysis:** Implements a comprehensive structural profile (`df.describe()`) evaluating global volume metrics, central tendency parameters, and outlier variance.

---

## 🚀 Execution & Implementation

### 1. Repository File Mapping
```text
├── Dataset for Data Analytics.xlsx          # Raw transaction data (1,200 records)
├── Cleaned_Data_Analytics_Dataset.xlsx      # Output asset (Sanitized, 100% complete)
├── exploratory_analysis.py                  # Humane Python EDA & Analysis Script
└── README.md                                # This structural project manual
