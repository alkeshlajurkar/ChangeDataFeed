# 🔄 Exploring Change Data Feed (CDF) in Delta Lake Using Databricks

## 📌 Overview
This project explores how to use **Change Data Feed (CDF)** — a feature in Delta Lake — to capture and query row-level changes (**INSERT**, **UPDATE**, **DELETE**) in a Delta table on **Databricks**. CDF enables you to access a complete trail of how your data has evolved over time, without requiring manual auditing or external tools.

The implementation was carried out in a Databricks notebook, and the complete code, outputs, and screenshots have been uploaded to this GitHub repository.

## 🎯 Purpose of the Project
- ✅ Demonstrate how to enable and utilize the **Change Data Feed (CDF)** in Delta Lake  
- ✅ Show how Delta versioning helps in managing and tracking changes  
- ✅ Illustrate the power of Delta Lake for building **incremental data pipelines**, **auditing**, and **change data capture (CDC)**  
- ✅ Provide a step-by-step example using SQL commands in a Databricks notebook  

## 🛠️ What is Delta Lake & CDF?
**Delta Lake** is an open-source storage layer that brings **ACID transactions** to Apache Spark and big data workloads.

**Change Data Feed (CDF)** is a feature of Delta Lake that lets users:

- Efficiently track data changes over time  
- Query only modified rows using `table_changes()`  
- Avoid complex joins or manual tracking for versioning or change detection  

### 📦 This is extremely useful in:
- Real-time streaming pipelines  
- ETL/ELT workflows  
- Data replication  
- Data auditing & lineage  

## 📌 Project Steps Implemented
1. Enable CDF on a Delta table during creation  
2. Insert initial data into the Delta table  
3. Perform the following operations:  
   - 🔁 **INSERT** (add new rows)  
   - 📝 **UPDATE** (modify existing rows)  
   - ❌ **DELETE** (remove rows)  
4. Use `table_changes()` function to extract changes:
   - `insert`, `update_preimage`, `update_postimage`, `delete`  
5. Query the Delta version history using `DESCRIBE HISTORY`  
6. Visualize and understand how data changes are captured across different versions  

## ⚙️ Technologies Used
- 🧠 **Databricks** (Notebook environment)  
- 💾 **Delta Lake**  
- 💻 **Apache Spark** (SQL + PySpark)  
- ☁️ **Cloud Storage** (optional)  

## 💼 Real-World Applications
- 🚀 Building incremental ETL pipelines  
- 🛡️ Audit logs for compliance and security  
- 🔄 Change Data Capture (CDC) for database replication  
- 📊 Data lineage for understanding how data evolves over time

## 🔗 Connect with Me 🤝
Feel free to connect with me for collaborations or any questions related to full-stack development, data management, or personal finance:

- **LinkedIn**: [alkeshlajurkar](https://www.linkedin.com/in/alkeshlajurkar)
- **Email**: alkeshlajurkar@gmail.com

💻 **GitHub Repository**  
Explore the complete source code of this project on GitHub:

[GitHub Repo Link](https://github.com/alkeshlajurkar/ChangeDataFeed.git)
