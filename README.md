# -Airline-Data-Management-and-Analysis-using-Power-BI
Developed interactive Power BI dashboards to analyze flight, passenger, and ticket data. Implemented DAX calculations, Row-Level Security, and scheduled refresh to deliver actionable insights for airline operations.

----


## Overview  
This project focuses on **analyzing and managing airline data** to uncover operational and customer insights.  
Using **Power BI**, I performed end-to-end tasks including **data cleaning, modeling, DAX calculations, and dashboard creation**.  
The project demonstrates how raw airline data (flights, passengers, tickets) can be transformed into **actionable insights** that improve efficiency and decision-making.  

---

## Problem Statement  
The airline industry operates with high complexity, involving flight schedules, ticket bookings, and passenger details. Without proper analysis, it is challenging to identify inefficiencies or track performance.  
This project aims to solve these challenges by designing an interactive Power BI dashboard that provides clear insights into:  
- Flight performance  
- Passenger management  
- Ticket booking trends  

---

## Datasets Used  
The project uses **three interlinked datasets**:  

1. **Flight Information** – FlightID, FlightNumber, Airline, Destination, Status  
2. **Passenger Information** – PassengerID, FlightID, SeatNumber  
3. **Ticket Information** – TicketID, FlightID, BookingStatus  

These datasets were connected using **FlightID** as the key.  

---

## Project Workflow  

### 1. Data Preparation & Cleaning  
- Imported datasets into Power BI using **Power Query**.  
- Removed duplicates, handled missing values, and formatted columns for consistency.  
- Created calculated columns and transformed data for better reporting.  

### 2. Data Modeling  
- Established **relationships** across Flight, Passenger, and Ticket datasets using FlightID.  
- Configured cardinality and relationships to ensure accurate reporting.  

### 3. Enhanced Insights  
- Added a conditional column to classify flights as **“Best”** or **“To Be Improved”** based on flight status.  
- Used “Column from Examples” to extract details such as flight numbers.  

### 4. Calculations with DAX  
Developed custom measures to calculate KPIs such as:  
- Total passengers for a flight  
- Total tickets booked  
- List of flights with “Best” status only  

### 5. Visualization & Dashboard  
Built **interactive dashboards** with visuals including:  
- Passenger count by airline  
- Ticket booking status  
- Flights by airline and destination  
- Airline-specific drill-through pages  
- Slicers for destinations and airlines  

### 6. Power BI Service Integration  
- Published the dashboard to **Power BI Service**.  
- Implemented **Row-Level Security (RLS)** to restrict access for Airline A data.  
- Configured **daily scheduled refresh** at 5 PM for automated updates.  

---

## Key Insights  
- Identified **top-performing flights** and flagged those needing improvement.  
- Analyzed **passenger distribution** across airlines and destinations.  
- Gained visibility into **ticket booking statuses** (confirmed, pending, canceled).  
- Improved airline operational decision-making with real-time visual insights.  

---

## Tools & Technologies  
- **Power BI** – Data cleaning, modeling, visualization, DAX calculations  
- **Power Query** – ETL (Extract, Transform, Load) operations  
- **Power BI Service** – Dashboard publishing, Row-Level Security, scheduled refresh  

---

## Outcome  
The final deliverable is an **interactive Power BI dashboard** that:  
- Consolidates flight, passenger, and ticket information  
- Provides real-time, automated insights for decision-making  
- Ensures **data privacy and security** with RLS  
- Enables airlines to monitor performance and booking trends effectively  

---
