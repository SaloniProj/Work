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

---

## 🧰 Tools Used
- **Azure Blob Storage** (source & sink)
- **Azure Data Factory** (for Data Flow)

---
