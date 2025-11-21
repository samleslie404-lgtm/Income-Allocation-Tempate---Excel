This spreadsheet was created to track equity payouts for my small business. It demonstrates the use of relational formulas, structured sheet references, and conditional formatting to build a clean, reproducible workflow for project-based financial tracking and operational efficiency.

The TEMPLATE sheet can be duplicated for each project and is designed to calculate equity payouts, tip percentages, and other relevant amounts quickly and accurately.

The SUMMARY sheet aggregates financial information across all projects, displaying income, equity splits, and subcontracted payments in a clear and visually organized format.

Auto-Population Logic:

When total income is entered into a project sheet, labour splits are automatically populated based on the predefined percentage allocations. This behavior is shown in labour_split.png.

To feed project data into the SUMMARY sheet, simply enter the project’s sheet name into Column A. All relevant fields automatically reference that sheet by title, as shown in summary_input.png.

Conditional Formatting Rules

To support error checking and financial accuracy:

If total equity in a project sheet does not equal income minus expenses, the value highlights in red to indicate unaccounted funds (example in total_equity_conditional.png).

If the checkbox beside Collected in a project sheet is selected, the SUMMARY sheet marks that amount in green to indicate payment has been received (see summary_input.png)

