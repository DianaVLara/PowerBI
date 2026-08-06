# Transportation Logistics Dashboard

A Power BI project analyzing transportation and logistics operations across hubs, drivers, and vehicles.

## Overview

This project contains **4 interactive Power BI dashboards**:

| Dashboard | Description |
|---|---|
| **Main Overview** | High-level view capturing the 4 core KPIs across the entire operation |
| **Hubs Performance** | Detailed breakdown of hub-level operations and efficiency |
| **Driver Performance** | Individual and aggregate driver performance metrics |
| **Vehicle Status & Performance** | Fleet health, utilization, and performance tracking |

## Dashboards

### 1. Main Overview
The landing page of the report. Summarizes the 4 primary KPIs used to monitor overall business health.

### 2. Hubs
Analyzes hub-level operations, including throughput, capacity, and efficiency across locations.

### 3. Drivers
Tracks driver performance metrics such as on-time delivery, experience, and productivity.

### 4. Vehicles
Monitors fleet status, maintenance needs, and vehicle performance and utilization.

## Key KPIs

- Total Orders Per Month
- On time Delivery Rate
- Customer Satisfaction
- Average Delivery Time

## Data Model

- **Sources:** Local CSV files
  - `Drivers.csv` — driver profiles and performance records
  - `Hubs.csv` — hub locations and operational data
  - `Orders.csv` — delivery/order transactions
  - `Vehicles.csv` — fleet status and vehicle details
- **Refresh:** Data is loaded from CSV files; a Month/Year slicer on the report lets users filter and view performance for a specific period.
- **Key tables:** Drivers, Hubs, Orders, Vehicles

## Project Structure

This project uses the **Power BI Project (.pbip)** format for version control:

  PowerBI/
  ├── TransportationDashboard.pbip
  ├── TransportationDashboard.Report/
  │   └── ... (report layout, visuals, pages as JSON)
  ├── TransportationDashboard.SemanticModel/
  │   └── ... (data model, DAX measures, relationships)
  ├── .gitignore
  └── README.md

## Getting Started

1. Clone this repository:

   git clone https://github.com/DianaVLara/PowerBI.git

2. Open `Transport_Logistics_Dashboard.pbip` in **Power BI Desktop**
   (requires the .pbip preview feature enabled:
   *File → Options and settings → Options → Preview features → Power BI project (.pbip) save option*).
3. Update data source connections as needed under **Transform data → Data source settings**.
4. Refresh the data to populate the dashboards.

## Tech Stack

- Power BI Desktop
- DAX for measures and calculated columns
- Power Query (M) for data transformation

## Screenshots

*[Add screenshots or a short GIF/walkthrough of each dashboard here]*

## Author

Diana Lara

## License

*[Add a license if applicable, e.g. MIT, or leave as private/internal use]*
