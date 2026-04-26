# 🏭 Smart Factory Decision Simulator

<p align="center">
  <img src="images/gif.gif" alt="Smart Factory Decision Simulator Demo" width="100%">
</p>



> **Interactive Power BI dashboard that simulates how cost, demand, and defect rates impact production profitability in real time.**

---

## 🚀 Overview

The **Smart Factory Decision Simulator** is an advanced Power BI project designed to transform a traditional dashboard into a **decision-making tool**.

Instead of static reporting, this solution enables users to **simulate real-world operational scenarios** by adjusting key business drivers such as cost, demand, and defect rates — and instantly observe the impact on production, revenue, and profit.

---

## 🎯 Business Problem

Manufacturing environments constantly deal with:

- Rising operational costs  
- Fluctuating demand  
- Quality issues (defects & losses)  

Understanding how these factors affect profitability is often complex and delayed.

👉 This dashboard solves that by providing a **real-time simulation layer** that visually connects operations to outcomes.

---

## ⚙️ Key Features

### 🎛️ Scenario Simulation Controls
- Cost Change %
- Demand Change %
- Defect Change %

👉 Users can dynamically adjust inputs and instantly see results

---

### 📊 Dynamic KPI Cards
- Sales  
- Quantity  
- Cost  
- Discount / Defect Indicator  

👉 All KPIs recalculate in real time

---

### 🔁 Sankey Flow Visualization (Core Highlight)
- Raw Material → Production → Good Units / Defective Units  
- → Revenue / Loss → Profit  

👉 Converts complex operations into a **clear visual story**

---

### 📉 Cost Breakdown Panel
- Raw Material  
- Labor  
- Overhead  
- Energy  
- Maintenance  

👉 Understand cost composition instantly

---

### 📈 Profit Trend
- Quick trend analysis for scenario comparison

---

### 💡 Insight Engine
- Automatically generates a narrative like:

> *"Profit increased by 29.3% with stable defect levels and controlled costs."*

👉 Turns data into **business language**

---

## 🧠 Technical Implementation

### 🔹 Data Model
Star-schema inspired model:

- **Fact Table**
  - `fact_factory_daily`

- **Dimensions**
  - `dim_date`
  - `dim_plant`
  - `dim_product`
  - `dim_scenario`

- **Helper Tables**
  - `Cost Type`
  - `Sankey`

---

### 🔹 Advanced DAX Logic

Key measures include:

- `Adjusted Revenue`
- `Adjusted Units Sold`
- `Adjusted Total Cost`
- `Adjusted Defective Units`
- `Adjusted Profit`
- `Adjusted Defect Rate %`
- `Flow Value`
- `Adjusted Cost Value`
- `Insight Text`

👉 All visuals are driven by **parameter-controlled DAX calculations**

---

### 🔹 Simulation Flow

1. User adjusts sliders  
2. Parameters update DAX measures  
3. KPIs recalculate instantly  
4. Sankey updates production flow  
5. Insight text summarizes impact  

👉 Creates a **live simulation experience**

---

## 🖼️ Dashboard Preview

### Full Dashboard
![Dashboard Overview](images/dashboard-overview.PNG)

### Sankey Simulation Flow
![Sankey Focus](images/sankey-focus.PNG)

### Controls & Insight Engine
![Controls and Insight](images/controls-insight.PNG)

---

## 🛠️ Tools & Technologies

- Power BI  
- DAX (Advanced)  
- What-if Parameters  
- Data Modeling (Star Schema)  
- Custom UI/UX Design  
- Sankey Visual  

---

## 💼 Skills Demonstrated

- Scenario-based analytics  
- Advanced DAX modeling  
- Interactive dashboard design  
- Data storytelling  
- Business problem solving  
- UI/UX thinking in Power BI  

---

## ⭐ Why This Project Stands Out

Most dashboards describe what happened.

👉 This project **simulates what could happen**.

It demonstrates:

- Decision-focused design  
- Real-time business modeling  
- Visual storytelling with impact  
- Recruiter-ready presentation  

---

## 📂 Repository Structure

```text
smart-factory-decision-simulator/
│
├── data/
├── images/
├── pbix/
└── README.md
