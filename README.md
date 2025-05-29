#  College Fee Management System

A simple web-based system to manage student fee payments, built using **Java (JSP + Servlets)**, **MySQL**, and **JDBC**.

---

## Technologies Used

* Frontend: HTML, CSS, JSP
* Backend: Java Servlets, JDBC
* Database: MySQL
* Tools: Eclipse IDE, Apache Tomcat

---

## How to Set Up the Project

### Step 1: Create Database

1. Open **phpMyAdmin** or MySQL CLI.
2. Create a database named:

```sql
CREATE DATABASE collegefeedb;
```

3. Import the schema using this SQL file:
   📌 [`mysqlcommand.sql`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/mysqlCommand.sql)

---

###  Step 2: Set Up the Project in Eclipse

1. Create a **Dynamic Web Project** in Eclipse (name it as you like).

2. Download the [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/) JAR file.

3. Paste the downloaded JAR into:

   ```
   WebContent/WEB-INF/lib/
   ```

---

## Project Structure

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

*  UTIL : [`DatabaseConnection.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/util/DatabaseConnection.java)
* Model :[`FeePayment.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/model/FeePayment.java)
*  DAO : [`FeePaymentDAO.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/dao/FeePaymentDAO.java)
* Servlets:

  * [`AddFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/AddFeePaymentServlet.java)
  * [`UpdateFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/UpdateFeePaymentServlet.java)
  * [`DeleteFeePaymentServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/DeleteFeePaymentServlet.java)
  * [`DisplayFeePaymentsServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/DisplayFeePaymentsServlet.java)
  * [`ReportServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/ReportServlet.java)
  * [`ReportCriteriaServlet.java`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/com/servlet/ReportCriteriaServlet.java)

---

###  Web Content

Place all your `.jsp` files and `styles.css` inside the `WebContent/` directory.
📌 [`webapp folder`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/tree/main/webapp)

---

##  Direct JSP URLs

* Add Product: [`productadd.jsp`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/webapp/feepaymentadd.jsp)
* Update Product: [`productupdate.jsp`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/webapp/feepaymentupdate.jsp)
* Delete Product: [`productdelete.jsp`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/webapp/feepaymentdelete.jsp)
* View Products: [`productdisplay.jsp`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/webapp/feepaymentdisplay.jsp)
* Reports: [`report_form.jsp`](https://github.com/Rajeshwari670/ADJ_CollageFeeManagmentSystem/blob/main/webapp/report_form.jsp)

---

##  Running the Project

1. Right-click the project > **Run As** > **Run on Server**.
2. Choose Apache Tomcat Server and start it.
3. Open your browser:
   `http://localhost:8080/ProductMangementSystem/`

---
## Features

*  Add New Fee Record
*  Update Existing Fee Record
*  Delete Student Fee Record
*  Display All Payments
*  Generate Report Based on Criteria (e.g., Overdue, Paid)


