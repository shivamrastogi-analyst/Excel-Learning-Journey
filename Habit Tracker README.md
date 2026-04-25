# 📊 Habit Tracker Dashboard (Excel)

A simple yet powerful **Habit Tracker Dashboard built in Microsoft Excel** to track daily habits, monitor consistency, and visualize progress over time.

---

## 🚀 Features

- Tracks daily habits across a full month  
- Line chart to visualize consistency trends  

- Automatically identifies:
  - Best Habit  
  - Worst Habit  

- Progress bars for total completion  

- Percentage-based tracking:
  - 0% Complete  
  - 50% Complete  
  - 100% Complete  

- Clean and structured dashboard layout  

---

## 🧠 Concepts Used

- INDEX + MATCH  
- MAX / MIN  
- COUNTIF  
- REPT (for progress bars)  
- Data Visualization (Line Chart)  

---

## 📌 Formulas Used

### 🔹 Best Habit
```excel
=INDEX(C15:C24, MATCH(MAX(AJ15:AJ24), AJ15:AJ24, 0))
