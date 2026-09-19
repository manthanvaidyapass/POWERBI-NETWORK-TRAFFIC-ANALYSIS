# POWERBI-NETWORK-TRAFFIC-ANALYSIS
# Power BI Network Traffic & Security Log Analysis

## 📌 Project Overview
This project focuses on analyzing network security logs and HTTP traffic data using Microsoft Power BI Desktop. The objective was to build an interactive multi-table reporting dashboard to monitor system alerts and track network metrics across multiple log schemas.

## 📊 Technical Challenges & Solutions
- *Multi-Table Relational Schema:* Established structured relationships across three independent log tables (botsv1_fgt_event, botsv1_fgt_traffic, and botsv1_stream_http).
- *Memory Allocation Optimization:* Resolved complex cross-join memory allocation errors caused by Many-to-Many cardinality conflicts during multi-column aggregation.
- *Data Filtering:* Optimized report rendering performance by applying targeted level = alert filters to streamline large-scale log rendering.

## 🛠️ Data Fields & Metrics Analyzed
The report integrates 9 core network log fields:
1. Date - Event timestamp
2. devname - Device identifier
3. host - Server host details
4. level - Event alert severity level
5. dstip - Destination IP address
6. srcip - Source IP address
7. client_IP - Client HTTP connection IP
8. bytes_in - Inbound network traffic (Bytes)
9. bytes_out - Outbound network traffic (Bytes)

## 🛠️ Tools & Technologies Used
- *Business Intelligence Tool:* Microsoft Power BI Desktop
- *Core Skills:* Data Modeling, Relational Schemas, Data Transformation, Visual Filtering
- *Certification:* Power BI for Beginners - Simplilearn (Microsoft SkillUp)

## 📷 Report Showcase
- *Data Model Schema:* Visualizing the multi-table relational schema.
- *Interactive Report View:* Displays the 9-column security log reporting matrix with active level filters.
-
