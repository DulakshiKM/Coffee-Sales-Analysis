# Coffee Sales Analysis

This dashboard provides coffee shop owners with insights into sales patterns and trends within their establishments.

By leveraging this analysis, shop owners can efficiently pinpoint top-performing and underperforming products, discern sales patterns and future projections, monitor the growth trajectory of their businesses, identify peak hours and days of activity, and assess the performance of each store location.

With these insights, owners can make informed decisions regarding menu adjustments, introduce new products tailored to customer preferences, and proactively prepare for peak hours to minimize customer wait times.

## Steps Followed

1. Step 1: Identify dataset and check missing values using python.
2. Step 2: Load data into Power BI Desktop, dataset is a csv file.
3. Step 2: Open power query editor & in view tab under Data preview section.
4. Step 3: Then transform data types of the date and time columns and add new tables for the Product Details, Store details, Date and filter rows.
5. Step 4: Then load the data into Power BIby clicking "Apply & close" button.
6. Step 5: Add new columns and new measures to tables as follows.
   - Substep A: Transactions table
       - Add new column for the revenue.

        Revenue = Transactions[unit_price]*Transactions[transaction_qty]
   - 
8. Step 6:Following DAX expression was written for the same,
        
        Revenue = Transactions[unit_price]*Transactions[transaction_qty]
   - Substep A: Additional details if needed.
   - Substep B: Additional details if needed.

## Adding Power BI Dashboard

To add the Power BI dashboard to your project, follow these steps:

1. **Export your Power BI dashboard**: Export your Power BI dashboard as a web page. You can do this by selecting `File > Export > Power BI Service`.

2. **Upload the exported files**: Upload the exported files (usually an HTML file and a folder containing assets like JavaScript and CSS files) to your GitHub repository. Make sure to place them in a directory that makes sense within your repository structure.

3. **Embed the dashboard in README**: Once the files are uploaded, you can embed the dashboard directly into this README file using an iframe. Here's an example:

```html
<iframe width="800" height="600" src="path/to/your/dashboard.html" frameborder="0" allowFullScreen="true"></iframe>
