SAP PP Plan-to-Produce Project (Furniture Manufacturing)

Project Overview:
This project demonstrates the Plan-to-Produce (P2P) cycle using SAP S/4HANA Production Planning (PP) module.

The project is based on a Furniture Manufacturing Company producing Wooden Tables. It covers the complete end-to-end manufacturing process including planning, production, and inventory management.

Industry:
Furniture Manufacturing (Wooden Table Production)

Tech Stack:
- SAP S/4HANA
- SAP GUI / SAP Fiori
- Windows OS

Process Flow:
Demand → MRP → Planned Order → Production Order → Execution → Goods Receipt

SAP Steps with T-Codes:

1. MM01 – Material Creation
   Keywords: Material Master, Raw Material, Finished Product

2. CS01 – Bill of Materials (BOM)
   Keywords: Components, Wood, Nails, Polish

3. CR01 – Work Center Creation
   Keywords: Machine, Production Unit

4. CA01 – Routing Creation
   Keywords: Operations, Cutting, Assembly, Finishing

5. MD61 – Demand Planning
   Keywords: PIR, Forecast, Demand

6. MD01 – MRP Run
   Keywords: Material Planning, Requirement Calculation

7. MD04 – Stock Overview
   Keywords: Stock, Planned Orders, Availability

8. CO01 – Production Order Creation
   Keywords: Manufacturing Order, Production

9. CO02 – Production Order Release
   Keywords: Status REL, Execution Start

10. MIGO (261) – Goods Issue
    Keywords: Raw Material Consumption

11. CO11N – Production Confirmation
    Keywords: Operation Confirmation, Progress Update

12. MIGO (101) – Goods Receipt
    Keywords: Finished Goods Entry, Inventory Update

Project Contents:
- Project Report (PDF)
- SAP Screenshots (with captions)
- End-to-End Process Flow

Key Features:
- Complete SAP PP manufacturing cycle
- Real-time MRP planning
- Integration with inventory (MM)
- Simple and practical workflow

Future Improvements:
- AI-based demand forecasting
- Cloud integration using SAP BTP
- Smart factory (Industry 4.0)

Conclusion:
This project shows how SAP S/4HANA PP helps improve production planning, inventory control, and manufacturing efficiency in a furniture company.

Author:
Prince Kumar
SAP PP Project
