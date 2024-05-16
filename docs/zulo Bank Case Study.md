### Executive Summary

This case study delves into the comprehensive process of database and data warehouse modeling for Zulo Bank, designed for beginner data engineers.

The study outlines the essential aspects of database design, including gathering business requirements and applying key principles like primary and foreign keys, normalization, and schema design. 

The focus then shifts to data warehouse modeling, emphasizing schema transformation and its practical application to address real-world banking data management challenges.

### Business Problem Statement

Zulo Bank aims to modernize its data management system to boost efficiency, improve data quality, and support advanced analytics. 

The current system struggles with data redundancy, inconsistency, and limited accessibility, creating obstacles for real-time decision-making and monthly reporting. 

The data engineering team has been tasked with designing a new system to resolve these issues, enabling seamless data integration, reporting, and analytics.

### Objectives

1. #### Understand Business Requirements

* Define the data needs of Zulo Bank, focusing on real-time access to customer information, efficient transaction processing, and advanced analytics capabilities.
  
2. #### Implement Database Design Principles

* Utilize primary and foreign keys to ensure data integrity, normalize the database schema to Third Normal Form (3NF) to eliminate redundancy, and selectively denormalize for efficient reporting.

3. #### Design and Develop Entity-Relationship Diagrams (ERDs)

* Create ERDs to visually represent the data model, showing the relationships and cardinalities between entities such as customers, accounts, and transactions.

4. #### Choose Appropriate Schema Types

* Decide on the optimal schema types for both the operational database and the data warehouse, balancing the trade-offs between normalization for transaction processing and denormalization for analytics.

5. #### Transform Database Schema to Data Warehouse Schema

* Transform the normalized operational database schema into a denormalized data warehouse schema to enhance analytics and reporting capabilities.


## Zulo Bank Dataset

![Zulo Bank Dataset](zulo_bank_dataset.csv)


## Database Columns and Data Types

Based on the given data and typical data types used in a database context. Below is a list of database columns with their corresponding suggested data types and descriptions:

1. **TransactionID** - Integer  
   A unique identifier for each transaction.

2. **TransactionType** - Text/Varchar  
   The type of transaction, such as "withdrawal" or "deposit".

3. **Amount** - Decimal/Numeric  
   The monetary amount involved in the transaction.

4. **TransactionDate** - Date  
   The date on which the transaction occurred.

5. **CustomerID** - Integer  
   A unique identifier for each customer.

6. **FullName** - Text/Varchar  
   The full name of the customer.

7. **Email** - Text/Varchar  
   The email address of the customer. This may require a unique constraint to avoid duplicates.

8. **Phone** - Text/Varchar  
   The phone number of the customer.

9. **AccountID** - Integer  
   A unique identifier for each account.

10. **AccountType** - Text/Varchar  
   The type of account, such as "Savings" or "Credit".

11. **Balance** - Decimal/Numeric  
   The current balance in the account.

12. **OpeningDate** - Date  
   The date when the account was opened.

13. **LoanID** - Integer  
   A unique identifier for each loan.

14. **LoanAmount** - Decimal/Numeric  
   The principal amount for the loan.

15. **LoanType** - Text/Varchar  
   The type of loan, such as "Mortgage" or "Personal".

16. **StartDate** - Date  
   The start date of the loan.

17. **EndDate** - Date/Interval  
   The end date or duration of the loan. It could be a specific date or a time interval.

18. **InterestRate** - Decimal/Numeric  
   The interest rate for the loan.



