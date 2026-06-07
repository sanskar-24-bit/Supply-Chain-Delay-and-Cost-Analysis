📦 Samsung Electronic Gadgets — Supply Chain & Logistics Dashboard

An end-to-end Supply Chain and Logistics Dashboard built in Power BI, modeled around Samsung's Electronic Gadgets  product line. It tracks supplier performance, inventory health, production quality, shipment logistics, and customer-side revenue — all in one interactive report.


📸 Dashboard Preview
PagePreview🏠 HomeLanding page with navigation📊 OverviewHigh-level KPIs across all supply chain stages🏭 SupplierLead times, order quantities, unit costs by supplier⚙️ Inventory & ProductionDefect rates, inventory value, stock levels💰 Customer (Supply)Revenue, profit, platform performance, discounts🚚 ShipmentCarrier delays, shipment costs, delivery status

📌 Project Overview
This dashboard provides a 360° view of Samsung's supply chain for the Electronic Gadgets, enabling data-driven decisions across procurement, manufacturing, logistics, and sales. It is structured across 5 analytical pages navigable from a Home screen.

🗂️ Dashboard Pages
1. 🏠 Home
Clean landing page with the Samsung branding and Galaxy S25 Ultra visual. Provides navigation buttons to all 5 report pages.

2. 📊 Overview
High-level summary of the entire supply chain with cross-functional KPIs:
MetricValueSum of Gross Revenue186.86MTotal Revenue176.95MProfit48.56MProfit Margin %27%Perfect Order %75%Order Quantity129KInventory Value160KShipment Quantity3MDelivered Quantity187KTotal Shipments8K
Visuals include:

Supplier by Avg Lead Time (bar chart)
Inventory Stock by Product (bar chart)
Total Delay by Shipments — by Carrier (bar chart)
Total Revenue by Platform (bar chart)


3. 🏭 Supplier
Focuses on procurement and vendor performance:
MetricValueTotal Unit Cost78.13MOrder QTY129KAvg Lead Time11.53 daysAvg Quality Score96.63Avg Unit Cost880.71Count of Suppliers7
Visuals include:

Unit Cost & Order Quantity trend over months (line chart)
Avg Lead Time by Country — China, Japan, South Korea, Taiwan, India, Vietnam
Supplier by Avg Lead Time / Order QTY / Total Unit Cost / Avg Unit Cost (bar charts)


4. ⚙️ Inventory & Production (Manufacturer)
Tracks production quality and inventory health:
MetricValueQuantity Produced4MDefective Units24KDefect Rate0.6%Inventory Value160KSafety Stock89KTurnover Rate1.17
Visuals include:

Defective Units by Month (line chart)
Inventory Value by Month (line chart)
Defect Rate by Product (horizontal bar chart)
Current Stock, Safety Stock & Reorder Point by Product (grouped bar chart)


5. 💰 Customer / Supply
Analyzes revenue, profit, and discount patterns across channels and platforms:
MetricValueGross Revenue186.86MTotal Revenue176.95MProfit48.56MProfit Margin %27%Perfect Order %75%Discount Amount9.92M
Visuals include:

Total Revenue & Profit by Month with Growth % (combo chart)
Revenue & Profit by Platform: Amazon, Flipkart, Best Buy, MediaMarkt, Samsung Direct
Discount % by Product (bar chart)
Discount %, Quantity & Revenue by Category (bubble chart)
Revenue & Discount by Channel Type: Online, Retailer, Direct (donut charts)


6. 🚚 Shipment
Monitors logistics performance and carrier reliability:
MetricValueTotal Shipments8KShipment Cost19.42MTotal Delays573Shipment Quantity3MTotal Delivered6KDelivered %75.29%
Visuals include:

Total Delivered Shipments & Delays by Carrier (grouped bar chart)
Shipment Status — Delivered / In Transit / Delayed / Processing (donut chart)
Total Delay by Carrier (bar chart): Maersk Line leads with 87 delays
Shipment Cost by Month (line chart) — peaks in December at 2.07M
Delay Breakdown by Reason: Carrier Capacity, Documentation, Port Congestion, Customs, Weather, Mechanical, Security, Address Errors


🔑 Key Insights

Amazon.com is the highest revenue-generating platform at ~37M, closely followed by Flipkart and Best Buy at ~36M each.
Maersk Line has the highest shipment delay count (87), making it the carrier with the most reliability issues.
Galaxy S24 Ultra has the highest defect rate among all products.
Retailer channel accounts for the largest share of both revenue (41.39%) and discount (41.26%).
India and Vietnam have the best average supplier lead times (9.5 and 9.4 days), outperforming China, Japan, South Korea, and Taiwan (~12.4–12.5 days).
Inventory value peaks in December at 19.2K, reflecting holiday season stock build-up.
Shipment costs trend upward through the year, reaching a December high of 2.07M.


🛠️ Tools & Technologies
ToolPurposePower BI DesktopDashboard design and report authoringDAXCalculated measures and KPIsPower Query (M)Data transformation and cleaningExcel / CSVSource data

📁 Repository Structure
samsung-supply-chain-dashboard/
│
├── 📊 Samsung_SupplyChain_Dashboard.pbix   # Main Power BI report file
├── 📁 data/                                 # Raw / cleaned source data (CSV/Excel)
├── 📁 screenshots/                          # Dashboard page screenshots
│   ├── Home.png
│   ├── Overview.png
│   ├── Supplier.png
│   ├── Manufacturer.png
│   ├── Customer.png
│   └── Shipment.png
└── 📄 README.md

🚀 How to Use

Clone the repository

bash   git clone https://github.com/your-username/samsung-supply-chain-dashboard.git

Open the .pbix file in Power BI Desktop (free download).
If prompted, update the data source path to point to your local /data folder via:
Home → Transform Data → Data Source Settings
Click Refresh to reload all visuals.
Use the navigation buttons on the Home page to explore each section of the dashboard.
