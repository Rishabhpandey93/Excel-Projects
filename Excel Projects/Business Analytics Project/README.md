# CDR Minutes Mapping System (Excel-Based)
## 📌 Purpose
This Excel tool maps VoIP call data (CDRs) to carriers using IP addresses. It helps calculate how many minutes each carrier handled—critical for accurate billing, reporting, and performance monitoring.
---
## 📂 Files Included
### 1. *IP File* (`Working File 1`)
- *Sheet 1:* List of carriers and their associated IP addresses.
- *Sheet 2:* Paste the raw CDR (Call Detail Records) here.
- *Functionality:* Uses Excel formulas (like `SUMIF`) to automatically calculate total minutes per IP.
### 2. *Minute Mapping Dashboard* (`Working File 2`)
- *Sheet "H":* Displays daily totals, weekly summaries (W1–W5), and final comparison.
- *Sheets W1–W5:* Weekly summaries (optional use).
- *Sheets 1–31:* Daily data entry for each calendar day.
### 3. *Sample CDR File*
- Contains dummy call data to demonstrate the workflow and test the system.
---
## 🔄 How It Works (Data Flow)
1. *Paste CDR data* into Sheet 2 of the *IP File*.
2. Based on the IP mapping, *total minutes per carrier* are automatically calculated.
3. Copy these totals into the appropriate *daily sheet (1–31)* in the *Dashboard* file.
4. The Dashboard auto-updates the following:
- Daily totals
- Weekly summaries
- Final monthly comparison table for error/mismatch checks
---
## 🧾 What You Need To Do
- *Step 1:* Paste CDR → `IP File` (Sheet 2)
- *Step 2:* Copy mapped minutes → `Dashboard` (corresponding daily sheet)
---
## 📊 Final Output
- Accurate total minutes per carrier
- Clean daily, weekly, and monthly summaries
- Final cross-check table for error detection
- User-friendly dashboard for Finance, Ops, and Management review
---
> ✅ Designed for internal IPRN call monitoring and billing efficiency.
