# dp-700-lab-01
# Microsoft Fabric Lakehouse Lab

This project showcases a lab exercise demonstrating how to build a modern analytics solution using **Microsoft Fabric Lakehouse**.

## 🔍 Overview

In this lab, I explored the core components of Microsoft Fabric, including:

- Creating a Fabric workspace with lakehouse capabilities
- Uploading and storing data in OneLake
- Using **Delta Lake** format tables
- Querying data using SQL and Visual Queries
- Building Power BI reports directly from the lakehouse

## 📁 Files and Structure

- `sales.csv`: Source file containing sales order data
- `sales` table: Loaded Delta Lake table from CSV
- **Power BI Report**: Visualized item-level sales using a clustered bar chart
- SQL analytics endpoint: Used to run aggregate queries on revenue per item

## 🧪 Tools & Technologies

- **Microsoft Fabric**
- **OneLake / Lakehouse**
- **Delta Lake**
- **Power BI**
- **Apache Spark (under the hood)**
- **SQL Analytics Endpoint**

## 🧾 Sample SQL Query

sql
SELECT Item, SUM(Quantity * UnitPrice) AS Revenue
FROM sales
GROUP BY Item

ORDER BY Revenue DESC;
![Screenshot 2025-04-29 at 10 48 21](https://github.com/user-attachments/assets/fa79e45b-e6b5-4b00-b0ef-7df27efc6a95)
![Screenshot 2025-04-29 at 10 45 11](https://github.com/user-attachments/assets/15b2fe66-f8d9-472c-a480-bd928d86b1d1)
![Screenshot 2025-04-29 at 10 43 37](https://github.com/user-attachments/assets/5b5e5993-8629-4c6d-885f-adda8ae3fc1c)
![Screenshot 2025-04-29 at 10 39 11](https://github.com/user-attachments/assets/59d5647a-a907-4314-a1a1-554deaa2d0f7)
![Screenshot 2025-04-29 at 10 31 27](https://github.com/user-attachments/assets/26051d42-fe74-46ac-bfcd-eb03bbcaecdf)
![Screenshot 2025-04-29 at 10 28 19](https://github.com/user-attachments/assets/754fa5b2-626c-4fca-8dd8-c560c3639db8)
![Screenshot 2025-04-29 at 10 20 35](https://github.com/user-attachments/assets/f5266532-3304-4a22-9ef7-9debff2d3b73)
![Screenshot 2025-04-29 at 10 11 27](https://github.com/user-attachments/assets/7830cac2-e67c-49e8-91b5-502398b15bff)
![Screenshot 2025-04-29 at 10 11 19](https://github.com/user-attachments/assets/75a7c301-e07d-4151-8c1a-95b9eb3a9f2f)



