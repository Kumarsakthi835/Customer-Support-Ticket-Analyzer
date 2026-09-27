# Customer Support Ticket Analyzer

## 📌 Project Overview

The **Customer Support Ticket Analyzer** is a Python-based data analysis project developed as part of the **Data Analytics (DA) Module-End 4 Python Assignment**.

The project focuses on managing, cleaning, and analyzing customer support ticket data using Python. It demonstrates practical implementation of dictionaries, lists, loops, functions, conditional statements, string manipulation, sets, sorting, and basic data analysis techniques.

The main purpose of this project is to transform raw customer support ticket information into structured and meaningful insights.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Store customer support ticket information using a dictionary of lists.
* Display ticket information in a readable format.
* Add new customer support tickets dynamically.
* Automatically generate ticket numbers.
* Validate ticket priority values.
* Clean and standardize issue descriptions.
* Analyze selected keywords in customer issues.
* Calculate ticket counts based on priority.
* Identify the longest customer issue description.
* Extract unique words from the cleaned ticket descriptions.
* Generate a final customer support ticket analysis report.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                   |
| ---------------- | ----------------------------------------- |
| **Python**       | Data processing and analysis              |
| **Google Colab** | Development and execution environment     |
| **GitHub**       | Project documentation and version control |

---

## 🧠 Python Concepts Used

This project demonstrates the following Python concepts:

* Dictionary
* Lists
* For loop
* While loop
* Conditional statements
* Functions
* String manipulation
* Input validation
* Sets
* Sorting
* Word counting
* Basic data analysis

---

# 📂 Dataset Information

The project initially contains **10 customer support tickets**.

Three additional tickets are added during the analysis process, resulting in a final dataset of:

### **13 Customer Support Tickets**

Each ticket contains the following fields:

| Field                 | Description                         |
| --------------------- | ----------------------------------- |
| **Ticket_No**         | Unique ticket identification number |
| **Customer_Name**     | Name of the customer                |
| **Issue_Description** | Customer's support issue            |
| **Priority**          | Ticket priority level               |

The available priority levels are:

* **High**
* **Medium**
* **Low**

---

# 🔄 Project Workflow

The project follows the workflow below:

### 1. Load Initial Ticket Data

The project begins with 10 preloaded customer support tickets.

### 2. Display Ticket Information

The initial ticket data is displayed in a readable format.

### 3. Add New Tickets

Users can enter additional customer support tickets.

Ticket numbers are automatically assigned starting from **11**.

### 4. Validate Priority

The project validates the priority entered for each new ticket.

Accepted values are:

* High
* Medium
* Low

### 5. Clean Issue Descriptions

The issue descriptions are cleaned and standardized before analysis.

### 6. Perform Keyword Analysis

A reusable function is used to count tickets containing selected keywords.

### 7. Analyze Ticket Priority

The number of High, Medium, and Low priority tickets is calculated.

### 8. Identify the Longest Issue

The project identifies the ticket containing the longest issue description based on word count.

### 9. Extract Unique Words

Unique words are extracted from all cleaned issue descriptions and sorted alphabetically.

### 10. Generate Final Report

All important findings are combined into a final customer support ticket analysis report.

---

# 🧹 Data Cleaning

Data cleaning is an important part of the project because the original issue descriptions contain different text formats, punctuation, spaces, and capitalization.

The cleaning process includes:

* Converting text to lowercase
* Removing punctuation
* Removing unnecessary spaces
* Removing leading and trailing spaces
* Standardizing shorthand such as `ok` to `okay`
* Creating consistent text for further analysis

### Example

Original issue:

> `Internet not working!!!`

After cleaning:

> `internet not working`

This makes the data more suitable for keyword-based analysis.

---

# 📊 Keyword Analysis

The project analyzes the occurrence of selected keywords in the cleaned issue descriptions.

The following keywords were analyzed:

* **Poor**
* **Good**
* **Slow**
* **Excellent**

## Keyword Results

| Keyword   | Number of Tickets |
| --------- | ----------------: |
| Poor      |                 3 |
| Good      |                 3 |
| Slow      |                 3 |
| Excellent |                 2 |

These results were generated from the final cleaned dataset containing 13 tickets.

---

# 🚦 Priority Analysis

The final dataset contains 13 tickets distributed across three priority levels.

| Priority  | Number of Tickets |
| --------- | ----------------: |
| High      |                 5 |
| Medium    |                 4 |
| Low       |                 4 |
| **Total** |            **13** |

The priority analysis helps organize the tickets according to their assigned priority level.

---

# 📝 Longest Issue Description

The project identifies the longest issue description based on the number of words.

### Result

| Field             | Details                              |
| ----------------- | ------------------------------------ |
| **Ticket Number** | 11                                   |
| **Customer**      | Priya                                |
| **Issue**         | internet connection is slow and poor |
| **Word Count**    | 6                                    |

This analysis demonstrates how Python can be used to process text and calculate word counts.

---

# 🔤 Unique Word Analysis

The project extracts unique words from all cleaned issue descriptions.

The words are:

1. Stored using a Python set
2. Duplicates are automatically removed
3. Sorted alphabetically
4. Counted to determine the total number of unique words

The final unique-word count is available in the **Final Analysis Report** generated by the Python program.

---

# 📸 Project Screenshots

The following screenshots document the major stages of the project.

## 1. Preloaded Ticket Data

The initial dataset containing the 10 preloaded customer support tickets.

<img width="656" height="285" alt="image" src="https://github.com/user-attachments/assets/d6253335-6c38-4056-84f4-05824d05d354" />


---

## 2. Readable Initial Tickets

The initial ticket information displayed in a readable format.

<img width="593" height="278" alt="image" src="https://github.com/user-attachments/assets/91e3fc8d-834d-40a3-bd79-62aa1a7f7355" />


---

## 3. Add New Tickets and Validation

New customer tickets are added and the priority input is validated.

<img width="547" height="262" alt="image" src="https://github.com/user-attachments/assets/f1c73365-e25a-410a-a6d3-e6dc2a9f86bc" />


---

## 4. Updated Ticket Data

The ticket dataset after adding the new customer support tickets.

<img width="597" height="146" alt="image" src="https://github.com/user-attachments/assets/47e3e433-3a78-4106-9234-50a0a764f9fb" />


---

## 5. Cleaned Issue Descriptions

The issue descriptions after applying the data-cleaning process.

<img width="566" height="280" alt="image" src="https://github.com/user-attachments/assets/b6aa4a25-fa55-4ec6-94cf-6d1d7ca43e41" />

<img width="549" height="271" alt="image" src="https://github.com/user-attachments/assets/48d3d1ce-1837-4c53-81bf-57a8f335c29e" />

<img width="549" height="271" alt="image" src="https://github.com/user-attachments/assets/b881ba8d-dfe3-4d2a-b313-4f4717ac7f96" />

<img width="565" height="199" alt="image" src="https://github.com/user-attachments/assets/b39053cf-7241-41e3-924c-57ae70aad29b" />


## 6. Keyword-Based Ticket Analysis

The results of the keyword analysis for **poor, good, slow, and excellent**.

<img width="619" height="129" alt="image" src="https://github.com/user-attachments/assets/0971132e-3404-4406-ac1c-0858f1ef8e0b" />

<img width="524" height="186" alt="image" src="https://github.com/user-attachments/assets/de4c4d9a-3ea3-4079-9342-1efae746e547" />

<img width="499" height="191" alt="image" src="https://github.com/user-attachments/assets/7feac0d4-7f32-452a-8754-e2396ebcd1d4" />


## 7. Final Cleaned Ticket Data

The final cleaned dataset containing all 13 tickets.

<img width="854" height="283" alt="image" src="https://github.com/user-attachments/assets/d73719a1-7962-4fd5-a33b-5e78eb7d76a6" />

<img width="580" height="283" alt="image" src="https://github.com/user-attachments/assets/d3d4fa7a-f013-488d-a01e-750bb1e9db64" />

---

## 8. Priority Analysis

The final distribution of High, Medium, and Low priority tickets.

<img width="739" height="275" alt="image" src="https://github.com/user-attachments/assets/f05449d6-244d-456f-aa98-73db7f56738d" />

<img width="484" height="78" alt="image" src="https://github.com/user-attachments/assets/6dda9ab2-7825-4f34-a805-af75c6b5fbf3" />



## 9. Longest Issue Description

The ticket with the longest issue description based on word count.

<img width="581" height="227" alt="image" src="https://github.com/user-attachments/assets/111b704c-fe75-48db-8d8d-d9dc3931b07c" />


---

## 10. Unique Word Analysis

The unique words extracted from the cleaned issue descriptions.

<img width="473" height="266" alt="image" src="https://github.com/user-attachments/assets/65948c04-fdd3-444e-a957-f93910a39027" />

<img width="478" height="277" alt="image" src="https://github.com/user-attachments/assets/535a48d8-a0f9-4e23-9603-22e973ee1655" />

<img width="587" height="257" alt="image" src="https://github.com/user-attachments/assets/d6813302-ef54-4c5b-abd4-910edfa50017" />

---

## 11. Final Analysis Report

The final consolidated customer support ticket analysis.

<img width="624" height="258" alt="image" src="https://github.com/user-attachments/assets/d0667f1f-8158-493a-8743-7ac7c8ab4961" />

<img width="451" height="188" alt="image" src="https://github.com/user-attachments/assets/7e056a94-b93b-4c27-8fe6-fa3e86ecf3a5" />

---

# 📁 Project Structure

The GitHub repository is organized as follows:

```text
Customer-Support-Ticket-Analyzer/
│
├── Python_Assignment_4_Customer_Support_Ticket_Analyzer.ipynb
│
├── Customer_Support_Ticket_Analysis_Summary.docx
│
├── README.md
│
└── Screenshots/
    ├── 01_Preloaded_Ticket_Data.png
    ├── 02_Readable_Initial_Tickets.png
    ├── 03_Add_New_Tickets_Validation.png
    ├── 04_Updated_Ticket_Data.png
    ├── 05_Cleaned_Issue_Descriptions.png
    ├── 06_Keyword_Based_Ticket_Analysis.png
    ├── 07_Final_Cleaned_Ticket_Data.png
    ├── 08_Priority_Analysis.png
    ├── 09_Longest_Issue_Description.png
    ├── 10_Unique_Word_Analysis.png
    └── 11_Final_Analysis_Report.png
```

---

# 📈 Final Project Results

The final analysis produced the following results:

| Analysis                     | Result |
| ---------------------------- | ------ |
| **Total Tickets**            | 13     |
| **High Priority**            | 5      |
| **Medium Priority**          | 4      |
| **Low Priority**             | 4      |
| **Poor Keyword**             | 3      |
| **Good Keyword**             | 3      |
| **Slow Keyword**             | 3      |
| **Excellent Keyword**        | 2      |
| **Longest Issue Ticket**     | 11     |
| **Longest Issue Customer**   | Priya  |
| **Longest Issue Word Count** | 6      |

The unique-word count is available in the final Python output.

---

# 🎓 Learning Outcomes

Through this project, the following practical skills were developed:

* Working with Python dictionaries and lists
* Managing structured ticket data
* Using loops for data processing
* Creating reusable Python functions
* Applying conditional statements
* Performing input validation
* Cleaning and standardizing text data
* Performing keyword-based analysis
* Using sets to identify unique values
* Sorting analytical results
* Calculating word counts
* Preparing structured analytical reports
* Documenting a Python project using GitHub

---

# 💡 Key Takeaways

This project demonstrates how basic Python programming concepts can be combined to solve a practical data-analysis problem.

The workflow covers the complete process from:

**Raw Ticket Data → Data Cleaning → Data Processing → Analysis → Final Report**

The project also demonstrates the importance of data cleaning before performing text-based analysis.

---

# 📌 Deliverables

The project includes the following deliverables:

* **Python Google Colab Notebook**
* **One-Page Project Summary**
* **GitHub README Documentation**
* **Project Screenshots**
* **Final Analysis Report**

---

# ✅ Conclusion

The **Customer Support Ticket Analyzer** provides a practical example of using Python for customer support data analysis.

The project successfully organizes customer ticket information, adds new records, cleans issue descriptions, validates priorities, analyzes keywords, calculates priority distribution, identifies the longest issue, extracts unique words, and generates a final analytical report.

This project demonstrates fundamental Python skills that are useful for further development in **Data Analytics and Data Analysis**.
