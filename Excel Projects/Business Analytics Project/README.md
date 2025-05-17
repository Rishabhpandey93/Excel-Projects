# 📊 Minute Mapping System – Excel Template
## 🧾 Purpose
These files maps VoIP call data (CDRs) to carriers based on IP addresses. It calculates the total minutes done by each carrier, providing accurate data for billing and reporting. 
---
## 📂 Files Included
### 1. *IP File (Working File 1)*
- *Sheet 1:* List of carriers and their corresponding IPs.
- *Sheet 2:* Paste the raw CDR data.
- *Functionality:* Uses Excel formulas (such as `SUMIF`) to calculate total minutes per IP.
### 2. *Minute Mapping Dashboard (Working File 2)*
- *Sheet "H":* Displays daily totals, weekly summaries (W1–W5), and final comparison.
- *Sheets W1–W5:* Weekly summary sheets.
- *Sheets 1–31:* Daily data entry for each day of the month.
### 3. *Sample CDR File*
- A test file with dummy data to help you understand the workflow.
---
## 🔄 How It Works (Data Flow)
1. *Paste the CDR data* into *Sheet 2* of the *IP File*.
2. Based on the IP mapping, *total minutes per carrier* are calculated automatically.
3. *Copy the daily totals* into the corresponding *day sheet (1–31)* in the *Dashboard*.
4. The Dashboard automatically updates:
- ✅ Daily totals
- ✅ Weekly summaries
- ✅ Monthly comparison table to catch mismatches
---
## 🛠️ What You Need To Do
- *Step 1:* Paste CDR data → `IP File` (Sheet 2)
- *Step 2:* Copy mapped minutes → `Dashboard` (correct daily sheet)
---
## ✅ Final Output
- Total minutes per carrier (daily, weekly, and monthly)
- Final cross-check table for error detection
- Clean and structured dashboard for Finance, Operations, or Management review
---
> 📁 Designed for internal use in IPRN/VoIP call environments to streamline traffic analysis and billing accuracy.
