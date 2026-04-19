# ✈️ Airline Loyalty Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive Power BI dashboard designed to analyze the performance of an airline loyalty program.
It focuses on customer growth, retention, and engagement using key metrics such as enrollments, cancellations, and flight bookings.

---

## ❓ Business Questions Answered

* How is the **loyalty member base growing over time**?
* Are **cancellations increasing**, indicating retention challenges?
* What are the **trends in customer enrollments**?
* How do **flight bookings compare year-over-year**?
* What impact do different **enrollment types (promotion vs standard)** have on bookings?

---

## 📊 Data Model

The dataset is structured using a **star-schema approach** with fact and dimension tables:

### 🗂️ Fact Tables

* **Customer Flight Activity**

  * Total Flights
  * Points Accumulated / Redeemed
  * Distance traveled

* **Customer Loyalty History**

  * Enrollment & Cancellation data
  * Customer demographics (city, country, education, salary)
  * Customer Lifetime Value (CLV)

---

### 📅 Dimension Table

* **Calendar**

  * Date
  * Start of Month / Quarter / Year
  * Enables time-based analysis and trend tracking

---

### 📐 Measure Table (Custom DAX)

* Flights Booked by Loyalty Members
* Flights Booked by LM (Previous Year)
* Total Flights Booked
* Total Enrollments
* Total Cancellations
* Net Loyalty Members
* Net Loyal Members (Running Total)

---

## 🧠 Data Modeling Approach

* Built relationships using **Loyalty Number and Date fields**
* Created a **dedicated measure table** for organization
* Implemented **time intelligence calculations** (YoY comparison, running totals)
* Enabled cross-filtering for interactive analysis

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query (Data Transformation)
* DAX (Measures & Time Intelligence)

---

## 📈 Dashboard Features

* Loyalty member growth tracking over time
* Enrollment trends with seasonal pattern identification
* Cancellation trend analysis (customer churn)
* Year-over-year comparison of flight bookings
* Booking distribution by enrollment type

---

## 📸 Dashboard Preview

![Dashboard Screenshot](images/dashboard.png)

---

## 💡 Key Insights

* Loyalty membership shows consistent growth over time
* Cancellations are increasing, indicating potential retention risks
* Enrollment spikes observed during promotional periods
* Flight bookings show strong year-over-year improvement
* Promotional enrollments contribute significantly to booking volume

---

## 📢 Conclusion

This project demonstrates the ability to design a structured data model, implement DAX-based calculations, and build an interactive dashboard that provides actionable insights into airline loyalty program performance.
