# ✈️ Airline Data Management and Analysis Using Power BI

This project focuses on managing and analyzing airline operations data using **Power BI** to derive insights that help improve operational efficiency and passenger satisfaction.

---

## 📌 Problem Statement

The airline industry operates with numerous complexities in handling flight schedules, passenger information, and ticketing systems. This project analyzes airline operations data to deliver actionable insights for improving service quality and resource allocation.

---

## 📊 Datasets Used

1. **Flight Information**  
   Includes: `FlightID`, `FlightNumber`, `Airline`, `Destination`, `Status`

2. **Passenger Information**  
   Includes: `PassengerID`, `FlightID`, `SeatNumber`

3. **Ticket Information**  
   Includes: `TicketID`, `FlightID`, `BookingStatus`

---

## 🔧 Tasks & Features

### 1. Data Preparation & Cleaning
- Extracted and cleaned data using Power Query
- Removed duplicates, handled missing values, and formatted fields

### 2. Data Modeling
- Created a relational model using `FlightID` as the primary key
- Configured correct cardinality between tables

### 3. Enhanced Data Insights
- Created a conditional column to classify flights as **“Best”** or **“To Be Improved”**
- Extracted components of flight numbers using “Column from Examples”

### 4. DAX Calculations
- Total passengers per flight
- Total tickets booked
- Filtered “Best” flights using calculated columns and measures

### 5. Visualizations & Interactions
- Interactive visuals for:
  - Passenger count by airline
  - Ticket booking status distribution
  - Flights by destination and airline
- Destination & airline filters
- Airline-specific pages for quick views

### 6. Final Dashboard & Power BI Service
- Designed a comprehensive dashboard with interactive filters
- Configured **Row-Level Security (RLS)** for Airline A
- Set up **scheduled data refresh at 5 PM daily**

---

## 📸 Key Dashboard Screenshots

> *(Add screenshots here or link to your Power BI report if published online)*

---

## 🚀 Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Excel (for initial data handling)

---

## 🎥 Video Walkthrough
 
[DRIVE_LINK](https://drive.google.com/file/d/180FBx5B5Hxp0MOFT4g0aPum9hCKOhkYX/view?usp=drive_link)

---

## ✅ Outcomes

- Improved understanding of operational bottlenecks
- Identified top-performing routes and airlines
- Enabled data-driven decision-making for passenger and ticket management

---

> “Data is the new fuel for the aviation industry.” 🚀
