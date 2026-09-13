 # Task 3 - SQL Superstore Analysis

## 📌 Task Overview
Analyzed Superstore dataset using MySQL Workbench with CASE statements.

## 🔍 Queries Performed
1. Created Database `superstore_task3`
2. **Sales Category:** 
   ```sql
   CASE WHEN Sales < 100 THEN 'Low'
        WHEN Sales < 500 THEN 'Medium'
        ELSE 'High' END
   ## 🛠️ Tools Used
- MySQL Workbench
- MS Word
- GitHub
