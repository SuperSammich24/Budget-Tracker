# Budget Tracker Template

A fully customizable personal budget tracker built in Google Sheets and Excel.  
This template helps you manage bills, extra expenses, income, and savings in one place — with live updates when you mark items as paid.

---

## Features
✅ Track bills and extra expenses separately  
✅ Mark items as paid/unpaid with checkboxes for live totals  
✅ Calculate remaining funds after bills, extras, and savings  
✅ Supports two paychecks per month format 
✅ Color coded balances for easy viewing 
✅ Works in both Google Sheets and Excel

---

## Images

# Budget Tracker Template
![Budget Tracker Template](Template_Image.png)

# Main Budget Tracker 
![Main Budget Tracker](Budget_Example-1.png)

# Live Update Example
![Live Update Example](Budget_Example-2.png)

---

## How to Use
1. **Download the file**:
   - [Excel Version (.xlsx)](./Budget_Tracker.xlsx)
   - Or upload to Google Sheets for online use
2. Fill in your **income** for each paycheck, also fill in paycheck dates in fixed database (this will auto populate in other databases)
3. Enter your **bills** and **extra expenses** with their amounts, due dates, and check numbers (1 or 2)
4. Use the **checkboxes** in the “Paid” column to mark items as paid
5. View live totals for:
   - Unpaid bills
   - Unpaid extra expenses
   - Remaining funds after all deductions
6. Adjust categories, labels, or formatting as needed

---

## 📌 Note on Checkboxes

If you view this file directly on GitHub, checkbox columns will show as **TRUE/FALSE** text.  
This happens because GitHub’s preview does not render interactive elements like Google Sheets checkboxes.

### ✅ Use the Interactive Google Sheets Version
<a href="https://docs.google.com/spreadsheets/d/1xqk1eQvG_oXtJ5ieQLGirnv9Bh6QHVfT/copy">
  <img src="https://img.shields.io/badge/Open%20in-Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white" alt="Open in Google Sheets">
</a>

*(Click the button above, then select **Make a copy** to save it to your own Google Drive.)*

---

### 💡 For Excel Users
1. **Download** the `.xlsx` file from this repository.
2. Open in Excel — checkboxes will appear as TRUE/FALSE text (normal).
3. To add native Excel checkboxes:
   - Go to the **Developer** tab  
     *(If hidden: File → Options → Customize Ribbon → check **Developer**.)*
   - In **Controls**, click **Insert** → **Form Controls** → **Checkbox**.
   - Draw the checkbox in the desired cell.
   - Right-click the checkbox → **Format Control…** → **Cell link** → select the TRUE/FALSE cell you want it to control (e.g., `D3`).
   - Copy/paste that checkbox down the column to reuse the linkage pattern (adjust cell links as needed).

> ℹ️ Tip: Keep the TRUE/FALSE cells (linked cells) hidden or off to the side and show a companion display column with a formula like `=IF(D3, "✅ Paid", "—")` so GitHub’s preview still looks clean.

---

### 🔗 Direct Copy Link (backup)
If the button above doesn’t work for any reason, use this link:
https://docs.google.com/spreadsheets/d/1xqk1eQvG_oXtJ5ieQLGirnv9Bh6QHVfT/copy

---

## Tips
- You can create **named ranges** in Google Sheets to make formulas future-proof
- To avoid breaking formulas, insert instruction rows **outside** the main data tables
- Customize categories and colors to fit your budgeting style

---

## License
This project is provided free for personal use.  
Please credit the creator if sharing publicly.
