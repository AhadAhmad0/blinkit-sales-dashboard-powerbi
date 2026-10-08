# Blinkit Sales Dashboard (Power BI)

A Power BI dashboard built on a public grocery sales dataset labeled Blinkit. It shows sales by outlet type, city tier, outlet size, item category, fat content and outlet opening year, with filters to slice the data.

The data is a public sample dataset, not Blinkit's internal sales data.

## Dashboard preview

<img width="1282" height="731" alt="Blinkit sales dashboard with KPI cards, filters and charts" src="https://github.com/user-attachments/assets/1cc1e662-e55b-47fc-bcad-8481022f7ed7" />

## Questions I wanted to answer

- Which outlet types and city tiers bring in the most sales?
- Which item categories sell best?
- How do sales split by fat content and outlet size?

## What the dashboard shows

- **KPI cards:** Total Sales, Average Sales, Number of Items, Average Rating
- **Filters:** Outlet Location Type, Outlet Size, Item Type
- **Charts:** sales by Fat Content, Item Type, Outlet Size, Outlet Location, Outlet Type and Outlet Establishment Year

## Findings

Overall: $1.20M in total sales across about 9K items, with an average rating of 4.0.

- **City tier.** Tier 3 has the highest sales ($472K), ahead of Tier 1 ($336K). These are totals, so they do not show that demand is stronger in smaller cities. Tier 3 may simply have more outlets or items.
- **Item category.** Fruits and Vegetables and Snack Foods are the top categories at $0.18M each.
- **Outlet type.** Supermarket Type 1 has 5,577 items and $787.55K in sales, about two-thirds of the total. Again, this is a total, and this outlet type may have more outlets than the others.
- **Outlet opening year.** Outlets opened in 2018 account for the most sales ($205K). The data has no sales dates, so this shows which opening year produced the most sales, not how sales changed over time.
- **Fat content.** Low Fat items bring in $776K and Regular items $425K. Low Fat also covers more items, so this does not show that shoppers prefer low-fat products.

## What I would check next

- Sales per outlet and sales per item, to compare tiers and outlet types fairly.
- How many outlets sit in each tier, type and opening year.
- Whether non-food categories such as Household carry a fat content label, since that would distort the fat content split.

## Tools

- Power BI Desktop for the dashboard and DAX measures
- Blinkit grocery sales data (Excel)

## Open the dashboard

Open the `.pbix` file in Power BI Desktop (Windows). The preview image above shows what it looks like.

## Author

Ahad Ahmad
- GitHub: [@AhadAhmad0](https://github.com/AhadAhmad0)
- LinkedIn: [linkedin.com/in/ahadahmad7](https://linkedin.com/in/ahadahmad7/)
