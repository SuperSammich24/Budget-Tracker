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

## How to Download
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
This template will create a **personal editable copy** in your own Google Sheets account.  
All checkboxes, formatting, and formulas are preserved.

### 🔗 Direct Copy Link

https://docs.google.com/spreadsheets/d/1MX4Iuvjrk2uhIRapVr5MSTLsDdvkyJdPRCBPZd1ETiM/edit?usp=sharing

**How to use:**
1. Click the green button above.
2. Google Sheets will prompt you with *"Would you like to make a copy?"* — click **Make a copy**.
3. Your copy is now fully editable and saved in your Google Drive.
4. You can rename it and start entering your own bills and expenses.


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

## 📋 How to Use This Budget Tracker

---

### 1️⃣ Bills & Expenses Sections
- **Add bills/expenses manually** in their respective tables:  
  - **Description** → Type the bill or expense name (e.g., Rent, Car Payment, Groceries).  
  - **Date** → Enter the due date.  
  - **Amount** → Enter the amount due.  
  - **Check #** → Enter the paycheck number (`1` or `2`) that will cover this bill/expense.  
  - **Paid Checkbox** → Check this box when the bill or expense is paid.  
- These sections automatically update totals in the **Fixed** and **Live** summary areas.  

---

### 2️⃣ Fixed Totals (Auto-Calculated)
- You **do not** need to edit formulas in the Fixed Totals section.  
- This shows the total amount of all bills/expenses for each paycheck **before** they are marked as paid.  
- The only manual step here is entering new items into the **Bills** and **Extra Expenses** lists above.  

---

### 3️⃣ Fixed Database (Paycheck Data)
- In the **Fixed Database** section:  
  - **Paycheck Date** → Enter the actual date you receive the paycheck.  
  - **Pay** → Enter your paycheck amount.  
  - **Debt** → Enter any debt/advances that will be taken out of that paycheck.  
- **Everything else** in this section will update automatically based on your bills and expenses.  

---

### 4️⃣ Live Totals (Auto-Calculated)
- Live totals show **what’s still owed** for the current paycheck after marking items as paid.  
- These update automatically when you check the **Paid** box for any bill/expense.  

---

### 5️⃣ Manual Updates in the Live Totals Section
- **Balance (Checking Account)** → Enter your current checking account balance.  
- **Extra Funds** → If you have any extra money available (e.g., from savings, overtime, or other income), enter it here.  
- **Everything else** in the live totals is **automatic** — no manual entry needed.  

---

✅ **Tip:** As long as you keep your bills/expenses updated with amounts, dates, and paycheck numbers, and mark them as paid, this tracker will handle all the calculations for you.

---

## Additional Tips
- You can create **named ranges** in Google Sheets to make formulas future-proof
- To avoid breaking formulas, insert instruction rows **outside** the main data tables
- Customize categories and colors to fit your budgeting style

---

## License
This project is provided free for personal use.  
Please credit the creator if sharing publicly.
