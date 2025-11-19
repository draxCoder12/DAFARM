# DAFARM: Profitability & Trend Monitoring System
A secure, data-driven web application built for **Doña Amparo Training and Assessment Center Inc.**  
DAFARM automates sales tracking, expense monitoring, inventory control, profitability analysis, and report generation—streamlining farm management and improving transparency.

---

## 📘 Table of Contents
- Introduction
- Core Features
- Technology Stack
- Installation & Setup
- Usage Guide
- User Roles
- Backup & Recovery
- Contribution Guidelines
- License

---

## 📌 Introduction
DAFARM is a web-based **Profitability and Trend Monitoring System** designed to replace manual farm record-keeping.  
It consolidates the center’s operational activities into one centralized platform, providing:

- Sales Tracking  
- Expense Logging  
- Inventory Management  
- Profitability Analysis  
- Trend Visualization  
- PDF Report Generation  
- Activity Logs  
- Backup & Recovery  

This system enhances accuracy, improves decision-making, and supports transparent agricultural operations.

---

## 🚀 Core Features

### **Dashboard**
- Real-time totals for Sales, Expenses, and Profit  
- Quick filters: Daily, Monthly, Annually  

### **Sales Management**
- Add and manage sales transactions  
- Filter and review complete sales history  

### **Expense Management**
- Track expenses with categories  
- View categorized totals and history  

### **Inventory Management**
- Add, update, and reduce stock  
- Automated inventory logs for transparency  

### **Profitability & Trend Analytics**
- Monthly profit chart  
- Annual trend overview  

### **Report Generation**
- Generate PDF reports for Sales, Expenses, and Inventory  
- Custom date-range filters  
- Includes “Prepared By” signature field  

### **User Management**
- Add, edit, and deactivate user accounts  
- Role-based access control  

### **Activity Logs**
- Records system actions automatically  
- Provides user accountability  

### **Backup & Recovery**
- Download database backups  
- Restore backups when needed  

---

## 🛠️ Technology Stack
- PHP Laravel Framework  
- Blade Template Engine  
- HTML, CSS, JavaScript  
- MySQL Database  
- Barryvdh DomPDF (PDF Generation)  
- Laravel Authentication  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
    ```bash
    git clone <your-repository-url>
    ```

2. **Enter the project directory**
    ```bash
    cd dafarm
    ```

3. **Install dependencies**
    ```bash
    composer install
    ```

4. **Copy the environment file**
    ```bash
    cp .env.example .env
    ```

5. **Configure your database settings** in `.env`
    ```
    DB_DATABASE=your_db_name
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
    ```

6. **Generate application key**
    ```bash
    php artisan key:generate
    ```

7. **Run database migrations**
    ```bash
    php artisan migrate
    ```

8. **Start the development server**
    ```bash
    php artisan serve
    ```

Access the application at:  
**http://localhost:8000**

---

## 📖 Usage Guide
- Log in using assigned credentials  
- Review profit summary on the Dashboard  
- Add Sales and Expenses  
- Manage Inventory levels  
- Generate PDF reports  
- Monitor Activity Logs  
- Manage user accounts based on roles  

---

## 👥 User Roles

### **Super Admin**
- Full access to all modules  
- Manages users, system data, and backups  

### **Admin**
- Manages Sales, Expenses, Inventory, and Reports  

### **Staff**
- Records sales, expenses, and inventory updates  

---

## 🗄️ Backup & Recovery
- Download full database backup  
- Restore a backup when needed  
- Ensures protection from data loss or corruption  

---

## 🤝 Contribution Guidelines
1. Fork the repository  
2. Create a new feature branch  
3. Commit changes  
4. Submit a pull request  

Follow Laravel and clean-code best practices.

---

## 📜 License
DAFARM is developed exclusively for **Doña Amparo Training and Assessment Center Inc.**  
Unauthorized duplication or redistribution is not permitted.
