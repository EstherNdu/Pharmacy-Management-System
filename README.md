# Pharmacy-Management-System

# Executive Summary
I turned a 2-hour daily manual audit into a real-time automated system. This project was designed for small-to-medium pharmacies to eliminate manual stock counting, prevent "out-of-stock" scenarios, and provide stakeholders with instant financial visibility.

# Technical Architecture
1. The Entry UI (VBA-Powered Form)

* Purpose: Serves as a custom Point of Sale (POS) interface.
* Feature: A user-friendly form built with VBA to ensure data integrity.
* Benefit: Prevents manual entry errors and protects the underlying database structure from accidental changes.

2. The Data Pipeline (XLOOKUP & SUMIFS)
* Logic: Utilized XLOOKUP for dynamic data retrieval and SUMIFS to create a live bridge between the Transaction Table and the Inventory Table.
* Result: Real-time stock adjustment. As soon as a transaction is submitted via the VBA form, the inventory levels updates.

3. Automated Visual Alerts (Conditional Formatting)
* Logic: Implemented a visual "Stock Monitor" using Conditional Formatting.
* Action: Rows automatically flag in RED when stock levels fall below the defined critical reorder point, acting as an automated shopping list.

4. Stakeholder Dashboard
* Visualization: An interactive dashboard that refreshes with a single click.
* KPIs: Tracks total revenue and top-selling products using Pivot Tables and Slicers.

# Business Impact
1. 𝟭𝟬 𝗛𝗼𝘂𝗿𝘀 𝗦𝗮𝘃𝗲𝗱 𝗣𝗲𝗿 𝗪𝗲𝗲𝗸: Eliminated manual stock counting every week 
2. 𝗗𝗮𝘁𝗮 𝗜𝗻𝘁𝗲𝗴𝗿𝗶𝘁𝘆: Eliminated "garbage-in" data by using 𝗗𝗮𝘁𝗮 𝗩𝗮𝗹𝗶𝗱𝗮𝘁𝗶𝗼𝗻 and VBA entry controls. 
3. 𝗜𝗻𝘃𝗲𝗻𝘁𝗼𝗿𝘆 𝗧𝗿𝗮𝗻𝘀𝗽𝗮𝗿𝗲𝗻𝗰𝘆: Because the system tracks unit costs alongside live stock levels, it provides the foundation to see exactly how much capital is sitting on the shelves at any moment. This turns "counting boxes" into "managing assets.

   
https://github.com/user-attachments/assets/d64b142c-f7fa-41ec-91e1-98e062417622

