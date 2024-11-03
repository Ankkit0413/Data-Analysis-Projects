# Inventory Management and Sales Tracking System

A robust Inventory Management and Sales Tracking System built with AppSheet and integrated with Looker Studio. This project is designed to streamline the entire workflow from purchasing and allocation to sales, payment tracking, inventory management, and real-time reporting.

## 🌐 Project Links

- **App Link**: [Inventory Management App](https://www.appsheet.com/start/f3c86a4a-12ef-465b-925b-5f0d43aac116)
- **Live Dashboard**: [Looker Studio Dashboard](https://lookerstudio.google.com/s/irlW9vYwtG4)
- For a demonstration, use credentials—Admin (Pass: 98765) & Salesperson ( Rajesh, Pass: 1234).


---

## 📋 Project Overview

The Inventory Management and Sales Tracking System provides a full cycle solution for businesses, starting from purchase order creation to product allocation, sales, payment receipts, and inventory adjustments. This system streamlines processes, improves accuracy, and provides instant access to essential business data through a real-time dashboard.

## 🛠️ Key Features

- **Purchasing and Stock Replenishment**: Create and manage purchase orders to ensure optimal stock levels.
- **Product Allocation**: Allocate inventory to specific sales representatives or departments.
- **Sales Tracking**: Track sales by client, payment status, product category, and salesperson.
- **Inventory Management**: Monitor stock levels, quantities sold, and reorder points.
- **Payment and Receipts Tracking**: View total amounts, amount received, and remaining balances for each sale.
- **Automated Reporting Dashboard**: Real-time visualization of sales metrics, remaining balances, and payment statuses via Looker Studio.
- **Responsive and Mobile-Friendly Design**: User-friendly interface accessible on desktop and mobile devices.

---

## 🖥️ Tech Stack

- **AppSheet**: For building the Inventory Management app with seamless workflows and automation.
- **Google Looker Studio**: For real-time data visualization and reporting.
- **Google Sheets**: Backend data storage, enabling easy data management and integration.

---

## 🔄 Process Workflow

### 1. **Purchasing Process**
   - Create a new **Purchase Order** entry in the Purchase Orders Table.
   - Fill in details such as Supplier Name, Product Name, Quantity Ordered, and Unit Price.
   - Once the order is received, update the **Status** to "Received" and adjust the **Stock Quantity** in the Inventory Table.

### 2. **Product Allocation**
   - Allocate specific quantities from the inventory to sales representatives or departments.
   - Update the **Allocated Quantity** and calculate the **Available Quantity** based on remaining stock.

### 3. **Sales Entry**
   - Record each sale by creating an entry in the Sales Table.
   - Input details such as Client Name, Product, Quantity Sold, and Total Amount.
   - Track **Payment Status** and apply any discounts if applicable.

### 4. **Payment and Receipts**
   - Record payment receipts against each sale in the Receipts Table.
   - Input details such as Receipt ID, Amount Received, and Date.
   - Update the **Remaining Amount After Payment** in the Sales Table to reflect the outstanding balance.
   
### 5. **Inventory Adjustment**
   - Update **Stock Quantity** in the Inventory Table based on sales to ensure accurate stock levels.
   - Track when stock levels reach the **Reorder Level** to prompt a new purchase order.

### 6. **Automated Reporting and Dashboard Sync**
   - Data is synchronized with Looker Studio for real-time reporting.
   - Users can view metrics such as Total Sales, Gross Amount, Total Amount, and Remaining Amount, filtered by date, client, or product.

---

## 📊 Dashboard Overview (Looker Studio)

The Looker Studio dashboard offers an at-a-glance view of:

- **Total Sales and Revenue**:
    - **Quantity Sold**: Number of units sold.
    - **Gross Amount**: Sales before discount.
    - **Discount**: Total discount applied across all transactions.
    - **Total Amount**: Net sales after discounts.
    - **Amount Received**: Total payments collected.
    - **Remaining Amount**: Outstanding balances.
- **Client-wise Breakdown**: Sales and payment status by client.
- **Payment Status Indicators**: Color-coded indicators for quick reference (Green = Paid, Yellow = Partial, Red = Unpaid).
- **Inventory Overview**: Real-time stock levels and reorder alerts.
- **Filter Options**: Filter reports by date range, product type, or client.

---

## 🧩 How It Works

1. **Initiate Purchase Orders**: Place purchase orders for products, and update stock levels when received.
2. **Allocate Inventory**: Distribute products to sales teams based on demand.
3. **Track Sales and Payments**: Record each sale, including product details, quantities, and payment information.
4. **Receive Payments**: Record receipts for each sale and update the balance accordingly.
5. **Adjust Inventory**: Automatically deduct sold items from inventory, triggering reorder alerts as needed.
6. **View Reports**: Access real-time insights and reports via the Looker Studio dashboard.

---

## 📈 Example Use Case

Imagine a cold drink supplier managing a variety of beverages distributed to retail shops. This example demonstrates how the system is used to track and manage inventory, allocate products, and record sales and receipts.

- **Purchasing Stock**: The supplier orders various drinks, updating stock levels upon arrival. This ensures an accurate view of inventory for future orders.

- **Allocating to Sales Reps**: Inventory is allocated to sales reps for distribution to retail shops, with tracking for quantities and locations, ensuring efficient stock availability.

- **Recording Sales**: Sales reps log transactions with retail shops, capturing product details, quantities, and payment status. Inventory updates in real time, providing insights into high-demand items.

- **Logging Payments**: Payments from shops are recorded, tracking amounts received and outstanding balances. This supports cash flow management and timely follow-ups.

- **Real-Time Dashboard**: A Looker Studio dashboard tracks key metrics like sales volume, revenue, stock levels, and client payments, providing data for informed decision-making.

---

## 📝 Installation and Setup

1. **AppSheet App**: Open the [App Link](https://www.appsheet.com/start/f3c86a4a-12ef-465b-925b-5f0d43aac116) to access the app.
2. **Looker Studio Dashboard**: Visit the [Live Dashboard](https://lookerstudio.google.com/s/irlW9vYwtG4) for reporting.
3. **Google Sheets Integration**: Link Google Sheets as the backend for data storage.
4. **Permissions**: Grant necessary permissions in AppSheet and Looker Studio for data synchronization.

---

## 🙌 Acknowledgments

- **AppSheet**: No-code app development platform.
- **Google Looker Studio**: Data visualization and reporting.

---

## 🔍 Keywords
Inventory Management, Sales Tracking, AppSheet App Development, Google Looker Studio, Real-Time Reporting, Purchase Order Management, Payment Tracking
