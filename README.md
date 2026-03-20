# Receiving Profile Analysis for a Retail Distribution Warehouse

## Executive Summary
This project analyses the inbound operations of a recent Retail Distribution Warehouse during a 3-month transitional period. This warehouse is facing a **critical congestion in the Inbound Area**, the objective was to utilize Data Analytics and Site Situational Analysis to identify the bottlenecks, and design a turnaround strategy to stabilize the inbound operations.

## Key Achievements and Methodologies Used
* **Data Consolidation**: Aggregated raw inbound transaction logs to establish the **performance baseline**, revealing a **loose incoming pattern**.
*  **Process Simulation**: Modelled a transition from current situation to “full pallet order”, projecting a **low increment** on palletised items that are coming in.

## Business Context
The client recently took over operations of a Retail Distribution Warehouse. Due to limited internal familiarity with the outbound process control, the warehouse was struggling to resolve this operational challenge.
* **Problem**: Receiving loading dock congestion and inefficient receiving workflows led to escalated **labour costs** and a high **cost-to-serve**, threatening overall **margin health**.
* **Goal**: Conduct a root-cause analysis of throughput **bottleneck** and design **data-backed interventions** to stabilize the inbound flow.

## Data-Driven Insight and Bottleneck Identification
### 1. Overall inbound activity performance
* **Observation**: **98%** of inbound activity consists of **"Loose" flows** (3,389 cartons and 1,862 units) compared to only 89 pallets.
* **Bottleneck**: The facility is physically optimized for "Full Pallet" flows. Processing thousands of loose items manually has created a **disproportionate labour requirement** due to the **current infrastructure**.
* **Insight**: The **"Pallet-in"** design is fundamentally at odds with the **"Carton-in"** reality of the business.

### 2. Ordering Process Simulation: "Order by Requirement" vs "Order by Pallet"
* **Observation**: Rounding up pallet quantities to the nearest half-pallet yielded a negligible increase in total pallet count (from 89 to 96). This confirms that current inbound volumes are significantly **below full-pallet thresholds** across the majority of the SKU profile.
* **Bottleneck**: High-frequency handling of small units is the **primary labour driver**, not pallet storage.
* **Insight**: The high ratio of loose cartons or units indicates a mature **Just-In-Time (JIT) inventory strategy**.

### 3. Incoming Delivery Allocation
* **Observation**: The data reveals significant inbound volatility, with Monday acting as a peak inbound day. At an average 213 touches per day, this volume is nearly **185% higher than the daily average of 75**. This indicates a "front-loaded" supply chain schedule that exceeds current baseline capacity.
* **Bottleneck**: The Monday surge creates a throughput bottleneck at the loading dock. This high-volume arrival leads to dock congestion, which negatively **impacts turnaround time** and increases the **risk of safety incidents** and **detention fees for carriers**.
* **Insight**: There is a low capacity utilization rate on Wednesdays, Fridays, and Saturdays. This suggests **labour underutilization** and **fixed-cost leakage**, where overhead remains constant despite a drop in productive output.

## Recommendations
Based on the data analysis, I proposed the following turnaround strategy to the client:
**Facilily and Process Improvement**: The facility is physically designed for "Pallet-in", but the business model is actually "Carton-in / Unit-in". This is the root cause of the fulfilment gap.
**Quarterly Throughput Analysis**: A 3-month transitional operation faced throughput instability. To mitigate this, a quarterly operational audit must be implemented to ensure that handling processes and labour allocation stay synchronized with the inventory requirements and SKU profiles.
**Alignment with Suppliers**:The receiving workload could be leveled across the week by collaborating with Procurement and Logistics to pre-plan the incoming deliveries.

*Note: The data in this repository has been anonymized to protect client confidentiality.*
