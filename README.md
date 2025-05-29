# 🎓 ADJ\_College Fee Management System

A simple web-based system to manage student fee payments, built using **Java (JSP + Servlets)**, **MySQL**, and **JDBC**.

---

## Technologies Used

* Frontend: HTML, CSS, JSP
* Backend: Java Servlets, JDBC
* Database: MySQL
* Tools: Eclipse IDE, Apache Tomcat

---

## 📅How to Set Up the Project

### Step 1: Create Database

1. Open **phpMyAdmin** or MySQL CLI.
2. Create a database named:

```sql
CREATE DATABASE collegefeedb;
```

3. Import the schema using this SQL file:
   📌 [`mysqlcommand.sql`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/mysqlCommand.sql)

---

### ✅ Step 2: Set Up the Project in Eclipse

1. Create a **Dynamic Web Project** in Eclipse (name it as you like).

2. Download the [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/) JAR file.

3. Paste the downloaded JAR into:

   ```
   WebContent/WEB-INF/lib/
   ```

---

## 📦 Project Structure

### 📁 Package Setup (`src/`)

Create the following package structure:

```
com/
├── util/
│   └── DatabaseConnection.java
├── model/
│   └── FeePayment.java
├── dao/
│   └── FeePaymentDAO.java
└── servlet/
    ├── AddFeePaymentServlet.java
    ├── UpdateFeePaymentServlet.java
    ├── DeleteFeePaymentServlet.java
    ├── DisplayFeePaymentsServlet.java
    ├── ReportServlet.java
    └── ReportCriteriaServlet.java
```

###  File Links

*  UTIL : [`DatabaseConnection.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/util/DatabaseConnection.class)
* Model :[`FeePayment.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/model/FeePayment.class)
*  DAO : [`FeePaymentDAO.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/dao/FeePaymentDAO.class)
* Servlets:

  * [`AddFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/AddFeePaymentServlet.class)
  * [`UpdateFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/UpdateFeePaymentServlet.java)
  * [`DeleteFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/DeleteFeePaymentServlet.java)
  * [`DisplayFeePaymentsServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/DisplayFeePaymentsServlet.java)
  * [`ReportServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/ReportServlet.java)
  * [`ReportCriteriaServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/ReportCriteriaServlet.java)

---

###  Web Content

Place all your `.jsp` files and `styles.css` inside the `WebContent/` directory.
📌 [`webapp folder`](https://github.com/SrinivaS4321/CollegeFeeMangementSystem/tree/main/webapp)

---

## Features

* ✅ Add New Fee Record
* ✅ Update Existing Fee Record
* ✅ Delete Student Fee Record
* ✅ Display All Payments
* ✅ Generate Report Based on Criteria (e.g., Overdue, Paid)


