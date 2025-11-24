## 1. Problem Statement

In today's service-based economy, individuals often subscribe to multiple recurring services (streaming, software, fitness, etc.), leading to a complex and often hidden accumulation of monthly costs. Without a centralized, simple tracking mechanism, users risk overlooking their total financial commitment, potentially leading to budgetary strain or missed opportunities to cancel unused services.

The problem this project addresses is the need for a **simple, quick, and accurate utility** to aggregate and display an individual's total monthly subscription expenditure.

## 2. Scope of the Project

The scope of the Basic Subscription Manager is strictly limited to a **proof-of-concept command-line interface (CLI) application** built using core Python features.

**In Scope:**
* Collecting text and numeric data from the user via the terminal.
* Storing subscription name and cost using a Python List of Dictionaries.
* Implementing robust input validation for numeric cost values.
* Calculating the sum of all entered costs.
* Displaying a neatly formatted summary report of all entries and the final total.

**Out of Scope (Future Work/Beyond Basic Assignment):**
* Persistent data storage (e.g., saving to a file like CSV or JSON).
* Advanced features (e.g., tracking renewal dates, currency conversion, categorization).
* Graphical User Interface (GUI) development.
* External library dependencies (e.g., Pandas, requests).

## 3. Target Users

The primary target users are individuals seeking a **quick and straightforward tool** for personal finance tracking.

* **Students/Entry-Level Programmers:** Seeking a simple, self-contained Python script to manage personal expenses without needing complex software.
* **Individuals on a Budget:** Users who need to quickly calculate their recurring financial commitments to better manage their monthly cash flow.
* **Educators/Learners:** Anyone studying fundamental data structures and input validation in Python, as this project serves as an excellent, clear example.

## 4. High-Level Features

**Data Collection** Interactive prompts allow the user to easily input subscription names and their corresponding monthly costs until a 'done' command is entered. <br>
**Input Integrity** The system prevents application failure and incorrect data storage by validating that the cost entered is a non-negative numerical value. <br>
**Data Structuring** Each subscription entry is stored as a dictionary (`{'name': str, 'cost': float}`) within a master list, ensuring data records are descriptive and easy to reference.<br> 
**Summary Report**  Generates a final report listing every subscription and provides an accurate, aggregated total of the combined monthly cost. 
