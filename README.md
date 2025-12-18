# PowerBI-VI
Power BI Advanced Report Design

Overview
This project enhances the Sales Analysis report with advanced Power BI capabilities: a drillthrough page for product-level insights, conditional formatting for visual data interpretation and interactive bookmarks with buttons to toggle visual types. The report is finalized and published to the Power BI service for end-user interaction.

Key Enhancements
Drillthrough Page: Product Details
A hidden page that users access by right-clicking a category in visuals (e.g., Clothing → Drill Through > Product Details).
Displays a Card showing the selected product category and a Table with subcategory, color, quantity, sales, and profit margin.
Configured with a drillthrough field (Product | Category) and includes an automatic back-navigation arrow.
Conditional Formatting
Icon formatting on Profit Margin:
🔴 Red diamond if < 0%
🟢 Green circle if ≥ 0%
Color formatting on the Color column:
Background and font colors dynamically applied using values from the Formatting display folder (Background Color Format, Font Color Format), originally sourced from ColorFormats.csv.
Bookmarks & Buttons on My Performance Page
Two overlapping visuals (bar and column charts) showing monthly Sales vs. Target.
Two bookmarks (Bar Chart ON, Column Chart ON) control visual visibility—configured to ignore filter state to preserve slicer interactivity.
Two interactive buttons allow users to switch between chart types without editing the report.
Publishing & Validation
Report published to Power BI service under My Workspace.
Verified functionality:
Drillthrough from category visuals
Dynamic color and icon formatting
Button-driven visual toggling
Seamless navigation via the back arrow
Outcome
The report now delivers a professional, interactive, and user-guided analytics experience, combining contextual detail (drillthrough), visual clarity (conditional formatting), and user control (bookmarks/buttons)—all aligned with best practices in Power BI report design.

Prepared by: Pang Kah Hwee
December 2025
