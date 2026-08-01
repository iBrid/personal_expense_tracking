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
- **Categories**: editable source list used by the category dropdown.
- **Reports**: redesigned CAD dashboard with monthly expense/income separation, savings insights, and category-level monthly breakdown.

### Reporting
In the **Reports** sheet, set:
- **Report Year**
- **Selected Month (1-12)**
- **Selected Quarter (1-4)**

The report now:
- Separates each month into **Expense (CAD)** and **Income (CAD)** columns
- Calculates **Net Savings** and **Savings Rate** per month and yearly totals
- Generates key insights such as highest expense month, highest income month, and best savings month
- Includes a selected-month category breakdown with separate expense and income columns
- Uses color-coded sections to make data entry and reporting easier to read

### Currency
All amount fields are formatted as **Canadian dollars (CAD)**.
