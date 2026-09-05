# Automated Salary and Performance Segmentation Tool

## 1. Business Problem
Human resource and finance departments frequently handle large, unorganized employee files containing inconsistent workforce compensation records. Manually sorting data rows to categorize employees into specific compensation tiers or performance bands takes hours weekly and introduces significant human typing errors.

The objective of this project was to engineer a clean, automated Python data pipeline that instantly imports raw operational files, executes programmatic data cleansing checks, and classifies workforce data segments without manual intervention.

---

## 2. Tech Stack and Libraries
* Programming Language: Python
* Data Manipulation Engine: Pandas for tabular calculations and structural joins
* Array Computations: NumPy for logical indexing routines
* Visual Analytics: Matplotlib and Seaborn for rendering corporate distribution charts

---

## 3. Tech Execution Breakdown

### Phase A: Programmatic Data Cleansing and Standardization
* Developed a ingestion script using Pandas to read raw internal CSV operational files.
* Programmed boundary validation routines to automatically identify and drop duplicate entries or null employee identification strings.
* Standardized text inputs across uniform capitalizations and removed leading spaces to maintain absolute data consistency.

### Phase B: Logic Automated Classification Pipelines
* Engineered structured conditional logic arrays using Pandas and NumPy methods to automatically assign employees into distinct compensation bands based on departmental metrics.
* Created standalone, reusable functions to instantly calculate bonus variables across varying departmental performance scores, completely eliminating manual spreadsheet typing calculations.

### Phase C: Exploratory Distribution Analytics
* Scripted visual plots to reveal total workforce salary distributions across organizational lines.
* Rendered customized horizontal bar charts isolating top revenue and sales performers to support leadership visibility meetings.

---

## 4. Business Value and Quantitative Outcomes
* Elimination of Manual Tasks: Replaced manual spreadsheet sorting processes with a single-click executable script, removing human data entry mistakes entirely.
* Strategic Efficiency: Automated complex multi-tier segmentation logic routines, cutting regular departmental processing intervals down to seconds.
* Structural Scale: Built the logic modules to accept changing data volumes seamlessly, allowing the corporate template to process growing operational registries without rewriting code.
