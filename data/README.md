## Data Model

The data model was built from **8 separate raw Excel files**, each representing a distinct dimension or fact table. These were integrated in Power BI using a **star schema**, centered around the `Sales` fact table.

###  Source Files
- `Sales.xlsx`
- `Products.xlsx`
- `Product_Categories.xlsx`
- `Product_Subcategories.xlsx`
- `Customers_Age_Group.xlsx`
- `Customers_Gender.xlsx`
- `Regions.xlsx`
- `Calendar.xlsx`

###  Model Design
- The `Sales` table serves as the core fact table.
- Dimension tables (Products, Customers, Calendar, Regions) are linked via one-to-many relationships.
- Columns were cleaned and standardized using Power Query.

![Data Model](./screenshots/data_model.png)
