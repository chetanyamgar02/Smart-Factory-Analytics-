
# 🏭 Smart Factory Analytics 

## 📌 Project Overview
**NEXORA Industries – Manufacturing Analysis** is an interactive Power BI project designed for a fictional automotive components manufacturer producing **Brake, Gear, and Suspension components**.

This project analyzes manufacturing operations to monitor production performance, product quality, machine downtime, and maintenance activities through an interactive dashboard.

## 🎯 Project Objectives
- 📊 Monitor planned vs. actual production.
- ⚙️ Analyze production efficiency across production lines.
- 🛠️ Identify machine downtime and production losses.
- ✅ Track good quantity, rejected quantity, and defect rates.
- 💰 Analyze maintenance costs and maintenance activities.
- 📈 Support data-driven manufacturing decisions.

## 📑 Dashboard Pages

### 1. 📍 Executive Overview
Provides a high-level summary of factory performance using KPIs, production trends, category analysis, downtime reasons, and maintenance costs.

### 2. 🏗️ Production Analysis
Analyzes planned vs. actual production, production variance, product performance, production lines, and shift-wise output.

### 3. ⚙️ Machine & Downtime Analysis
Tracks machine performance, downtime hours, downtime reasons, and production loss to identify areas requiring attention.

### 4. ✅ Quality Analysis
Evaluates good quantity, rejected quantity, quality rate, and defect rate by product and category.

### 5. 🔧 Maintenance Analysis
Analyzes maintenance costs, maintenance activities, maintenance duration, and preventive maintenance percentage.

## 🗂️ Data Model
The project uses five tables:

- 🏢 `FactoriesTable` – Factory information
- ⚙️ `MachinesTable` – Machine and production-line information
- 🏭 `ProductionTable` – Production quantities and quality metrics
- ⏱️ `DowntimeTable` – Downtime incidents and production losses
- 🔩 `MaintenanceTable` – Maintenance activities, duration, and cost

The model uses relationships between factory, machine, and transaction data to support interactive analysis.

## 🛠️ Tools & Technologies
- 📊 Microsoft Power BI – Dashboard development and visualization
- 🧮 DAX – Measures and KPI calculations
- 📁 Microsoft Excel – Dataset preparation and data source

## 📈 Key KPIs
- Production Efficiency
- Production Variance
- Quality Rate
- Defect Rate
- Total Downtime
- Production Lost
- Total Maintenance Cost
- Preventive Maintenance %

## 💡 Business Value
This project demonstrates how raw manufacturing data can be transformed into meaningful insights to help identify production gaps, quality issues, downtime patterns, and maintenance requirements.

## 🚀 Future Scope
- Expand the model to support multiple factories.
- Integrate real-time production data.
- Explore predictive maintenance and advanced quality analytics.
