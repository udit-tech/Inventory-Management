## 📦 Inventory Management System

This is a simple Inventory Management web application built using **HTML, CSS (Bootstrap)**, and **JavaScript**. It helps users to efficiently **add**, **view**, **filter**, and **delete** items from an inventory list using API integration.

---

### 🚀 Features

1. **Home Page**

   * Project introduction and navigation to other pages.

2. **Add Items**

   * Form to input:

     * Item Name
     * Quantity
     * Category (Perishable / Non-perishable)
   * Sends data via `POST` request to a backend API.
   * Shows loader and success message on submission.

3. **Item List**

   * Displays all inventory items fetched from an API.
   * Filter items by category.
   * Delete items using a "Delete" button for each list entry.

---

### 📂 Project Structure

| File            | Description                                          |
| --------------- | ---------------------------------------------------- |
| `index.html`    | Landing page with navigation                         |
| `addItems.html` | Form to add new inventory items                      |
| `itemList.html` | Lists inventory items with filter and delete options |

---

### 🌐 API Used

All data operations (create, read, delete) are performed using the following API:

```
https://inventory-management-student-neog-ca.replit.app/inventory
```

---

### 🛠️ Technologies Used

* HTML5
* Bootstrap 5
* Vanilla JavaScript
* REST API

---

### 📄 How to Use

1. Clone the repository.
2. Open `index.html` in your browser.
3. Navigate using the navbar:

   * Go to **Add Items** to add new inventory.
   * Go to **Item List** to view, filter, or delete items.

---

