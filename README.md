# Power Bi data modeling project
# Introduction:
  The challenge of this project is to turn a truly complicated dataset of 23 files of an unclear structure taken from various source systems into a functioning star schema model in Power BI. The initial dataset was characterized by the inconsistencies in its structure, duplication of identifiers, presence of free text, as well as the different levels of granularity of various tables, and thus the cleansing and normalization were required first. The main effort was devoted to identifying which tables would be used as facts and which as dimensions and establishing their relations, and the final model included 6 fact tables and 7 dimension tables.

# Features:
Data Exploration & Understanding: Profiled 23 raw, unstructured source files to understand their structure, quality issues, and relationships before any modeling began.

Data Cleaning & Preparation: Cleaned and standardized inconsistent tables — resolving mismatched columns, duplicate/legacy identifiers, embedded free-text fields, and inconsistent geography — to ensure data quality and integrity for accurate analysis.

Data Modelling: Built a star-schema data model, identifying which tables belonged as fact tables versus dimensions and defining the relationships between them, resulting in 6 fact tables and 7 dimension tables supporting sales, inventory, campaigns, and order fulfillment.

Data Transformation: Applied Power Query transformations — filtering, grouping, and reshaping — to prepare the cleaned tables for the model.

This repository documents the process of turning a genuinely messy, real-world dataset into a clean, working star-schema data model in Power BI — from data exploration and cleaning to modeling and transformation. Visualization and dashboarding are planned as a next step.

# Data model:
  This is the final data model design of the project:
  
<img width="1226" height="700" alt="Screenshot 2026-08-30 121735" src="https://github.com/user-attachments/assets/feae7434-906d-4cb1-961b-b5bd668794e6" />
