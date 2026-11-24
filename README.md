# Business Context
A consumer-goods distribution company sells food and beverage products through three channels: Retail, Distributor and Online. 
Management has seen sales change but cannot tell whether the team is delivering against expectations.
The Sales Director is concerned that headline revenue hides who is and is not hitting target.
Some managers think the budget is unrealistic, Others think problems sit with specific people, products or channels.
The Finance Director wants actual sales compared with budget, with the drivers of variance explained.
The Commercial Director wants to know where to investigate additional commercial resources, backed by data rather than assumptions.
Reporting period: January 2019 to 14 March 2021.
## Objectives
- Measure performance against budget. Compare actual sales with budget at company, salesperson and monthly level, so management can see whether the business is above or below plan and how that has changed from 2019 to March 2021.
- Explain the drivers of variance. Test whether gaps come from budget allocation, product mix or channel exposure, so that management can tell a genuine performance issue from an unrealistic target.
- Guide where to act next. Show which channels, product categories and groups drive revenue, and flag where management should investigate further, including where additional commercial resources may be justified.
## Business Questions
-	Is the company performing above or below budget, and how has that changed over time?
-	Which salespeople deliver against budget, and where are the largest gaps?
-	Are apparent salesperson problems caused by budget allocation, product mix or channel exposure?
-	Which channels drive revenue, and how has their contribution changed?
-	Which product categories and groups drive revenue?
-	What should management investigate next?
## Dataset Overview
a. Budget Fact Table 
- Description: contains information on Salesperson ID, Month, and Budget.
- Fields: Salesperson ID, Budget and Reporting Date.
- Purpose: Provides Context for analyzing Performance metrics by Salesperson ID, Budget and Reporting Date.

b. Fact Sales Table
- Description: Central Table containing Business detailed performance and business data.
- Fields: Order Date, Order No, Product Id, Salesperson Id, Supervisor, Manager, Channel, Quantity, Unit Price, Sales.
- Purpose: Provides detailed sales transaction data for analysing business Performance.

c. Dim Product product
- Description: Contains product related Information.
- Fields: Product ID, Product Name, Product Group and Product Category
- Purpose: Provides product classification and descriptive information for analyzing sales by product category.

c. Dim Salesperson Table
- Description: Contains Salesperson details and sales organizational information.
- Fields: Salesperson ID, Salesperson, Supervisor, Manager and Channel.
- Purpose: Supplies salesperson attributes for analysing sales performance across individual salesperson, Managers & Channels.
