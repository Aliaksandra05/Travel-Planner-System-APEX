<img width="1912" height="818" alt="APEX" src="https://github.com/user-attachments/assets/674dc1cc-f882-4785-8e6f-9264b860555c" />

![diagram_apex](https://github.com/user-attachments/assets/90c46ce6-fc7f-4a1c-aff9-ab2e403c3a89)


# <b>Travel Planner System (Oracle APEX)</b>

A comprehensive travel management system built with Oracle APEX 24.2. This application allows users to manage travel catalogs, including hotels, restaurants, attractions, and customer bookings.

## <b>Business Logic & Database Implementation</b>

This system is built on a robust relational database foundation, leveraging **PL/SQL** to ensure data integrity and automate complex workflows.

* **Relational Data Model:** Implemented a complex schema with relationships between `Customers`, `Bookings`, `Hotels`, `Restaurants`, and `Attractions`.
* **Dynamic Calculations:** Used **SQL Analytics** and **PL/SQL Functions** to calculate total trip costs (including currency handling) and real-time dashboard statistics.
* **Data Integrity:** Custom **Database Triggers** and **Validations** ensure that booking dates do not overlap and that all mandatory business fields are populated before processing.
* **Performance Optimization:** Optimized data retrieval for Interactive Reports using indexed columns and efficient Join operations.

## <b>Features</b>
- Dynamic Dashboards: Real-time stats on trips, customers, and cities.
- Catalog Management: Detailed forms for Restaurants, Hotels, and Attractions with complex database relationships.
- Data Integrity: Custom error handling and validations for business logic.
- User-Friendly Interface: Intuitive side navigation and responsive design.

## <b>Tech Stack</b>
- Platform: Oracle APEX
- Database: Oracle SQL & PL/SQL

## <b>Installation</b>
1. Import `database_schema.sql` into your Oracle SQL Workshop.
2. Import the application file `f127.sql` via the APEX App Builder.
