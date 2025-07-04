# Smart-Restaurant-Management-App-
Offline-capable restaurant management system built with C#, MSSQL, and OOP principles – includes reservations, orders, billing, and user-specific access.
## 🔗 Full Project Download
You can download the full project archive (50MB) from the following link:  
[Download from Google Drive](https://drive.google.com/drive/folders/1fR2MUlHl9GQbXTD5S0zQZ26aFTOlSHOY?usp=sharing)
# Smart-Restaurant-Management-App – Restaurant Management System

Smart-Restaurant-Management-App is a comprehensive and **offline-capable** restaurant management system developed using C#, MSSQL, and Object-Oriented Programming principles. The project eliminates the common shortcomings of popular internet-dependent solutions (e.g., SambaPOS) by providing a robust, responsive, and user-focused application that runs without requiring an internet connection

## 🎯 Project Objective

Most restaurant owners struggle with slow or unstable internet-based POS systems that crash or become unusable during outages. LINT was developed to solve this issue by working **fully offline**, while offering modern features like:

- Employee-specific UI panels based on user roles  
- Table management with dynamic color-coded status  
- Reservation handling with printable receipts  
- Detailed employee action logs  
- Sales reporting via interactive charts  
- Custom controls for better input validation  
- Support for adding/updating/deleting employees, customers, and products

## 👨‍💻 Contributor
- Tolga Ünlü 

## 🧱 Technologies Used

- **C# (.NET Framework)** – Backend logic and Windows Forms UI  
- **MSSQL** – Database management  
- **ADO.NET (via DAL/BLL layers)** – Query abstraction  
- **OOP Principles** – Encapsulation, modular structure  
- **Custom Controls** – Validated TextBox with Unicode checks  
- **WinForms Charts** – Sales statistics visualized  
- **Visual Studio** – Development environment

## 🧰 Project Structure

- `LintReservation.MODEL` – Class definitions (mapped to DB)
- `LintReservation.DAL` – Data Access Layer for queries
- `LintReservation.BLL` – Business Logic Layer
- `LintReservation.App` – WinForms UI
- `App.config` – Centralized connection string

## 🚀 How to Run

1. Install MSSQL and Visual Studio.
2. Attach the provided `.mdf` and `.ldf` files to your local SQL Server via **SSMS > Attach Database**.
3. Clone the project and open it in Visual Studio.
4. Ensure the `App.config` file has the correct SQL Server connection string.
5. Build and run the project.

## 💡 Key Features

- **🔐 Login & Role-Based Access**
  - Combobox-based login system
  - Boss-level users see additional admin panels
  - Custom TextBox controls for valid input

- **🍽 Table Management**
  - Dynamic table buttons with color-coded statuses:
    - Gray: Reserved, not seated
    - Red: Occupied
    - Light Red: Reserved & occupied
    - Yellow: Free
  - Live updates upon order or reservation actions

- **📋 Orders & Billing**
  - Order entry with calculator-style quantity selection
  - Product list by category (from database)
  - Bill generation with printable invoice
  - Discounts, VAT, and total calculations
  - Tables auto-reset after payment

- **📆 Reservations**
  - Assign tables to customers on selected dates
  - View, add, update customer info directly
  - Table color reflects reservation status

- **📊 Sales Reports**
  - Date-based filtering
  - Category-wise and product-wise sales charts

- **🧑‍🍳 Kitchen & Menu Management**
  - Add/update/delete products and categories
  - ListView and ComboBox synced with database

- **👥 Employee & User Management**
  - Add/update/delete employees
  - Role assignment through ComboBox
  - Secure login validation

## 🧪 Bonus Highlights

- Bing AI image assets for UI buttons
- Encapsulated class design with `ToString()` override
- Error messages and validation for user actions
- Full offline capability — no internet dependency

## 📦 Download & Assets

All related materials, including:
- Project files
- Videos (how to run + team presentation)
- Database files (`.mdf`, `.ldf`)
- ER Diagram & Mapping Table  
…are available in this [Google Drive folder](https://drive.google.com/drive/folders/1fR2MUlHl9GQbXTD5S0zQZ26aFTOlSHOY?usp=sharing).

---

Feel free to fork, improve, or learn from this project. If you’re building an offline-first POS system, LINT could be a great starting point.
