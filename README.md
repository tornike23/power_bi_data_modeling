# Power Bi data modeling project
# Introduction:
  The challenge of this project is to turn a truly complicated dataset of 23 files of an unclear structure taken from various source systems into a functioning star schema model in Power BI. The initial dataset was characterized by the inconsistencies in its structure, duplication of identifiers, presence of free text, as well as the different levels of granularity of various tables, and thus the cleansing and normalization were required first. The main effort was devoted to identifying which tables would be used as facts and which as dimensions and establishing their relations, and the final model included 6 fact tables and 7 dimension tables.

# Features:
Data Exploration and Understanding: Profiled 23 raw, unstructured source files to gain an understanding of their structure, problems, and interrelationships prior to modelling.

Data Cleaning and Preparation: Cleaned and standardised inconsistent tables by fixing mismatched columns, duplicate/legacy keys, free-form text columns and inconsistent geography to make sure the quality and integrity of the data is up to the mark for meaningful analysis.

Data Modelling: Created a star-schema data model by determining which tables were to be used as fact tables and which were to be considered dimensions and how they would relate to each other, resulting in 6 fact tables and 7 dimension tables.

Data Transformation: Used Power Query transformations such as filtering, grouping and reshaping to prepare the cleaned tables for modelling.

Row Level Security: Dynamic RLS by regions of users. Done using DAX.

This repository showcases the journey of taking a real-world, messy data set and turning it into a clean, functional star-schema data model in Power BI through data exploration and cleaning, modelling and transformation. Visualization and dashboarding is planned next.

# Data model:
  This is the final data model design of the project:
  
<img width="1226" height="700" alt="Screenshot 2026-08-30 121735" src="https://github.com/user-attachments/assets/feae7434-906d-4cb1-961b-b5bd668794e6" />
