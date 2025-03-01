



To create a Google Sheets-based income and expenditure tracker for your short-term rental project, follow these steps to ensure effective tracking, collaboration, and receipt management:

1. Create a Google Sheet
- Open Google Sheets and create a new spreadsheet.
- Name it something like "Short-Term Rental Financial Tracker".

2. Set Up the Income & Expense Tracking Sheet
**Columns to Include:**
- Date (Automatic entry possible using =TODAY() or manual input)
- Category (Drop-down: Rent, Maintenance, Utilities, Cleaning, Supplies, Marketing, etc.)
- Description (Details of the transaction)
- Amount (Income or Expense amount)
- Type (Dropdown: "Income" or "Expense")
- Payment Method (Dropdown: Cash, Credit, Bank Transfer, etc.)
- Receipt Link (Hyperlink to the uploaded receipt)

**How to Link Scanned Receipts:**
1. Upload Receipts to Google Drive
- Create a folder in Google Drive called "Rental Receipts".
- Upload receipts as scanned PDFs or images.
- Right-click the file → Click "Get link" → Set sharing to "Anyone with the link can view".
- Copy the link and paste it in the "Receipt Link" column.

3. Automate Income & Expense Summaries
Create a separate summary sheet to automatically calculate:

- Total Income
- Total Expenses
- Profit/Loss (=SUMIF(Transactions!E:E, "Income", Transactions!D:D) - SUMIF(Transactions!E:E, "Expense", Transactions!D:D))

4. Enable Collaboration
- Click "Share" (top-right in Google Sheets).
- Add trusted persons’ emails (set permission to "Viewer" or "Editor" as needed).
- Enable commenting for accountability.

5. Add Data Validation for Accuracy
- Use dropdowns for Category, Type, and Payment Method (Data → Data Validation).
- Use conditional formatting to highlight negative balances
