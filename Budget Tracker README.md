# 📊 Personal Budget Tracker Dashboard (Excel)

A fully interactive and automated **Personal Budget Tracker Dashboard** built in Microsoft Excel to help manage income, expenses, savings, bills, and overall monthly financial planning in a structured and visual way.

This project was created to improve budgeting, analyze spending patterns, and practice advanced Excel dashboarding concepts using formulas, automation techniques, and data visualization.

---

# 🚀 Features

## 🔹 Budget Planning Dashboard
- Track monthly income, expenses, savings, and bills
- Monitor actual spending against planned budget
- Analyze financial health in a single dashboard

---

## 🔹 Automated Calculations

The dashboard updates automatically based on transaction entries and budget data.

### Automatically Calculates:
- Total Income
- Total Expenses
- Total Bills
- Total Savings
- Remaining Balance
- Highest Expenses
- Budget vs Actual comparisons
- Paid / Unpaid bills

---

## 🔹 Transaction Management

Easily record and organize transactions using categorized entries.

### Includes:
- Date tracking
- Category selection
- Sub-category tracking
- Amount recording
- Comments / Notes section

---

## 🔹 Bill Tracking System

Track all monthly bills and payment status.

### Features:
- Paid / Unpaid bill status
- Bill amount tracking
- Budget vs Actual bill comparison
- Bill payment summary visualization

---

## 🔹 Savings Management

Monitor savings goals and compare planned savings with actual savings.

### Savings Categories:
- Life
- Family
- Trip
- Custom categories

---

## 🔹 Dynamic Dashboard Visualizations

Interactive charts provide quick financial insights and trend analysis.

### Charts Used:
- Doughnut Charts
- Clustered Column Charts
- Line Charts

### Dashboard Insights:
- Allocation Summary
- Expense Summary
- Budget vs Actual Analysis
- Cash Flow Summary
- Bill Summary
- Income Source Analysis

---

# 🧠 Excel Concepts Used

## 🔹 Data Validation
Used to create dropdown-based category selection and improve data entry accuracy.

### Data Validation Source Logic:
- IFS function used dynamically

---

## 🔹 Conditional Formatting

Used for:
- Highlighting categories
- Visual bill status indicators
- Better readability
- Dashboard aesthetics

---

## 🔹 Functions Used

### SUMIF
Used for category-wise calculations and financial summaries.

```excel
=SUMIF()
```

### IFS + AND Combination
Used for logical conditions and dynamic categorization.

```excel
=IFS(AND(...))
```

### LARGE
Used to identify highest expense values dynamically.

```excel
=LARGE()
```

### INDEX + MATCH + LARGE
Used together to dynamically identify top expense categories instead of using XLOOKUP.

```excel
=INDEX(...MATCH(LARGE(...)))
```

---

# 📊 Dashboard Sections

## 🔹 Current Balance
Displays the remaining available balance after expenses, bills, and savings.

---

## 🔹 Income Summary

Tracks all income sources including:
- Salary
- Food Card
- Rent
- Side Income
- Freelance Income
- Passive Income

---

## 🔹 Expense Summary

Tracks spending across categories such as:
- Housing
- Food & Groceries
- Transportation
- Personal Care
- Healthcare
- Insurance
- Entertainment

---

## 🔹 Budget vs Actual Comparison
Compares planned budget with actual financial activity.

---

## 🔹 Cash Flow Summary
Visual representation of:
- Income
- Expenses
- Bills
- Savings

---

# ⚡ Automation Features

## 🔹 Automatic Dashboard Updates
The dashboard updates automatically when new transactions or budget values are entered.

---

## 🔹 Dynamic Calculations
No manual calculations required after setup.

---

## 🔹 Smart Categorization
Dropdown-based categorization minimizes errors and improves usability.

---

# 📁 Files Included

- Personal Budget Tracker Dashboard (.xlsx)
- Dashboard Preview Images

---

# 🎯 Purpose Of The Project

This project was built to:
- Practice Excel dashboard development
- Improve financial tracking and budgeting
- Learn automation using Excel formulas
- Understand data visualization techniques
- Build practical real-world Excel projects

---

# 💡 Key Learnings

- Combining multiple Excel functions can create powerful automated systems
- Dashboard design improves data understanding and analysis
- INDEX + MATCH combinations provide flexible alternatives to XLOOKUP
- Data visualization helps simplify financial insights

---

# 🔗 Usage

## Step 1
Open the Excel file.

## Step 2
Enter transactions in the Transactions List sheet.

## Step 3
Select categories using dropdown menus.

## Step 4
Dashboard updates automatically.

---

# 🙌 Feedback

Open to suggestions, improvements, and feedback!

---

# ⭐ Support

If you found this project useful, give this repository a ⭐
