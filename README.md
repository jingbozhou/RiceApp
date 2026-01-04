# Rice Variety Phenotype Query System

## 1. Overview

The **Rice Variety Phenotype Query System** is a lightweight, Windows-based desktop application designed for **interactive querying and comparison of rice phenotypic traits**.
The software is developed using **Python** and distributed as a **standalone Windows executable (EXE)** together with its underlying phenotype dataset.

The system enables users to:

* Browse a large collection of rice varieties
* Select multiple varieties for comparison
* View **basic information** and **quantitative phenotypic traits** side by side
* Interactively explore large tables using scrollable and resizable windows

This tool is particularly suitable for **rice breeding, variety evaluation, and phenotypic data exploration**.

---

## 2. Repository Contents

This GitHub repository contains the following key components:

```text
                
rice_app.exe                 # Precompiled Windows executable
Supplementary_Table_S1.xlsx  # Phenotypic dataset used by the application
README                       # Documentation
```

* **rice_app.exe**: Ready-to-use Windows application (no Python installation required)
* **Supplementary_Table_S1.xlsx**: Original phenotype data table used by the software
* **rice_app.py**: Full source code for transparency, reproducibility, and further development

---

## 3. Target Users

This software is intended for two main groups:

### 3.1 End Users

* Rice breeders
* Crop scientists
* Students and researchers interested in rice phenotypic data

No programming background is required.

### 3.2 Data Users

* Users who want to **inspect, reuse, or analyze the original dataset**
* The Excel file can be opened independently using any spreadsheet software

---

## 4. Quick Start (For End Users)

### 4.1 System Requirements

* **Operating System**: Windows 10 / Windows 11
* No Python or additional libraries are required

### 4.2 Running the Software

1. Download `rice_app.zip`
2. Extract the zip file to any directory
3. Make sure the following two files are in the **same folder**:

   * `rice_app.exe`
   * `Supplementary_Table_S1.xlsx`
4. Double-click **rice_app.exe** to launch the application

---

## 5. User Interface and Operation Guide

### 5.1 Main Window

The main interface consists of:

* **Left list box**: All available rice varieties in the dataset
* **Right list box**: Selected varieties for comparison
* **Query button**: Executes the comparison

#### Selecting Varieties

1. Browse varieties in the **left list**
2. **Double-click** a variety name
3. The selected variety will be added to the **right list**
4. Repeat to select multiple varieties

The list supports a large number of varieties and includes a **vertical scrollbar**.

---

### 5.2 Query Execution

* Click the **“Query”** button after selecting at least one variety
* If no variety is selected, the system will display a warning message

---

### 5.3 Result Window

After clicking **Query**, a new result window opens automatically.

---

## 6. Result Tables

### 6.1 Table 1: Basic Information

This table displays core descriptors for each selected variety, including:

* Variety name
* Approval number
* Quality classification
* Disease resistance traits
* Stress resistance traits
* Cluster and breeding category information


---

### 6.2 Table 2: Phenotypic Trait Comparison

This table provides a detailed comparison of quantitative traits, including:

* Yield and yield components
* Plant architecture traits
* Growth period
* Grain quality traits
* Processing and appearance-related traits


---

## 7. Dataset Description

The file **Supplementary_Table_S1.xlsx** contains the complete phenotypic dataset used by the software.

* The dataset can be opened, filtered, and analyzed independently
* Column names in the software are mapped to user-friendly display names
* The application reads the Excel file dynamically at runtime

Researchers are encouraged to **inspect and reuse the dataset directly** for further analysis.

---

## 8. License and Usage

This software and dataset are provided for **academic and research use**.

* Users are free to use, modify, and extend the code
* Proper citation of the dataset and software is recommended when used in publications

---

## 9. Contact

For questions, suggestions, or collaboration inquiries, please contact the repository maintainer.

---



The phenotypic data used in this study, together with the corresponding windows application, are publicly available on GitHub.
