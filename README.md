# Vendor Management System with Performance Metrics

## Features

1. **Vendor Profile Management:**

   - Create, retrieve, update, and delete vendor profiles.
   - Track vendor information including name, contact details, address, and a unique vendor code.
2. **Purchase Order Tracking:**

   - Create, retrieve, update, and delete purchase orders.
   - Track purchase order details such as PO number, vendor reference, order date, items, quantity, and status.
3. **Vendor Performance Evaluation:**

   - Calculate vendor performance metrics, including on-time delivery rate, quality rating average, average response time, and fulfillment rate.
   - Retrieve performance metrics for a specific vendor.

4. **Swagger Documentation**

   - `http://localhost:8000/schema/doc/`


## Installation

1. Clone the repository:
2. Create a virtual environment and install dependencies:
3. Apply database migrations:

   ```bash
   python manage.py migrate
   ```
4. Run the development server:

   ```bash
   python manage.py runserver
   ```
5. Access the application at http://localhost:8000.

