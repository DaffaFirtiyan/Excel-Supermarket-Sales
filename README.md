# Excel Supermarket Sales
 Excel Dashboard of Supermarket Sales pulled from https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

Pipeline:
1. Dashboard overview
2. Datasheets overview
3. Prepare data
4. Analysis & prepare visuals
5. Design background
6. Design dashboard
7. Format visuals

Data pulled from: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

1. Dashboard overview (what we want to show on the dashboard)
This is based on a B2C data, mainly about sales.

Slicers:
- Yearly 
- Monthly
- Sales type (direct sales, online, wholesaler)
- Payment method (Cash, online)

Visualisations:
- Monthly sales
- Product sales
- Sale types
- Daily Sales
- Top selling products
- Top selling category

2. Data overview
- Invoice ID (Unique ID for each purchase)
- Branch (There are only 3 branches available: A, B, C)
- City (Location of the supermarkets)
- Customer Type (With or without membership)
- Gender
- Product Line (Category of goods sold)
- Unit Price
- Quantity
- Total (Total price including tax)
- Payment Type(Cash, credit card, e-wallet)
- CoGS (Cost of goods sold - Unit price * quantity)
- Gross income (for the company)
- Rating (Customer satisfication 0-10)

3. Prepare data
- Split date into day/month/year
- Named the months from numbers to text