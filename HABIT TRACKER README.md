📊 Habit Tracker Dashboard (Excel)

A simple yet powerful Habit Tracker Dashboard built in Microsoft Excel to track daily habits, monitor consistency, and visualize progress over time.

🚀 Features

🔹 Tracks daily habits across a full month
🔹 Line chart to visualize consistency trends

🔹 Automatically identifies:
    ▫️ Best Habit
    ▫️ Worst Habit

🔹 Progress bars for total completion

🔹 Percentage-based tracking:
    ▫️ 0% Complete
    ▫️ 50% Complete
    ▫️ 100% Complete

🔹 Clean and structured dashboard layout

🧠 Concepts Used

🔹 INDEX + MATCH
🔹 MAX / MIN
🔹 COUNTIF
🔹 REPT (for progress bars)
🔹 Data Visualization (Line Chart)

📌 Formulas Used
🔹 Best Habit
=INDEX(C15:C24, MATCH(MAX(AJ15:AJ24), AJ15:AJ24, 0))

🔹 Worst Habit
=INDEX(C15:C24, MATCH(MIN(AJ15:AJ24), AJ15:AJ24, 0))

🔹 Task Completed
=COUNTIF(E15:E24, "X")

🔹 Total Completed (Progress Bar)
=REPT("|", AJ15*4)

🔹 0% Complete Count
=COUNTIF(E27:AI27, "0%")

🔹 50% Complete Count
=COUNTIF(E27:AI27, "50%")

🔹 100% Complete Count
=COUNTIF(E27:AI27, "100%")

📊 Dashboard Preview :
Preview :
Download Excel File: 

🎯 Purpose

🔹 Improve consistency tracking
🔹 Understand how Excel functions work together
🔹 Practice building real-world dashboards

💡 Key Learning

🔹 Combining simple functions creates powerful systems
🔹 INDEX + MATCH is more flexible than VLOOKUP
🔹 Visualization improves data understanding

🔗 Usage

🔹 Open the Excel file
🔹 Mark completed tasks with "X"
🔹 Dashboard updates automatically

