# personal_expense_tracking
An expense tracking template to keep track of your daily spending and generate insights.

## Excel template

Use `/home/runner/work/personal_expense_tracking/personal_expense_tracking/personal_expense_tracking_template.xlsx`.

### Included sheets
- **Transactions**: enter Date, Type, Category, Description, and Amount for each entry.
  - **Type** has a dropdown: `Expense` or `Income`
  - **Category** has pre-populated dropdown values including:
    - Gas
    - Groceries
    - Phone Bill
    - Power Bill
    - Life Insurance
    - Car Loan Payment
    - Rent/Mortgage
    - Internet
    - Dining Out
    - Medical
    - Entertainment
    - Miscellaneous
    - Salary, Bonus, Freelance, Investment, Refund, Other Income
  - Includes clickable quick buttons in cells `J2` and `J3`:
    - **Add 1 Row**: jumps to the next available entry row
    - **Add 10 Rows**: jumps 10 rows below the next available entry row
- **Categories**: editable source list used by the category dropdown.
- **Reports**: monthly, quarterly, and yearly spending summaries and highest-spend category.

### Reporting
In the **Reports** sheet, set:
- **Report Year**
- **Report Month (1-12)**
- **Report Quarter (1-4)**

The report automatically calculates spending totals by category and highlights the highest-spend category for monthly, quarterly, and yearly views.
