# 📦 Azure ADF Mini Project: Pivot Data from Row to Column

---

## 🧾 Overview
This project demonstrates a **simple transformation** using **Azure Data Factory (ADF)** to convert data from **row format to column format** using:
- Azure Blob Storage (as source & destination)
- Azure Data Flow (for transformation logic)

---

## 🎯 Objective
- Read raw CSV data from Azure Blob Storage
- Use ADF Mapping Data Flow to **pivot row data to columns**
- Write transformed data back to Blob Storage

---

## 🧱 Architecture

```text
        +---------------------+
        | Raw CSV (Blob)      |
        +---------------------+
                  |
                  v
        +---------------------+
        | ADF Mapping Data    |
        |     Flow (Pivot)    |
        +---------------------+
                  |
                  v
        +---------------------+
        | Pivoted CSV (Blob)  |
        +---------------------+
```
![Sink_project1](https://github.com/user-attachments/assets/a913df26-1e45-4dad-8fad-1fdabf1e8e8b)
![Output_project1](https://github.com/user-attachments/assets/2de488d4-278e-4eeb-9152-bacdf982a324)
![Pivot1_project1](https://github.com/user-attachments/assets/900d2ab8-e97e-4f44-be61-2012e8936a2b)
![pivot2_project1](https://github.com/user-attachments/assets/7d2b9e38-253a-4cd2-a517-fba626bf97e8)
![pivot_3_project1](https://github.com/user-attachments/assets/19b388f1-4649-42a3-8473-1388e5addf32)
![Output_dataflow_project1](https://github.com/user-attachments/assets/23e6b2c0-1d98-4377-bd4e-ab5e9d0fea8a)
![ADF_project1](https://github.com/user-attachments/assets/72a18829-67d3-4da6-b5e9-6bab96d6c009)
![source1_dataflow_project1](https://github.com/user-attachments/assets/230cd5d8-57ff-430b-aaef-77a7e1f0a1c6)





---

## 🧰 Tools Used
- **Azure Blob Storage** (source & sink)
- **Azure Data Factory** (for Data Flow)

---
