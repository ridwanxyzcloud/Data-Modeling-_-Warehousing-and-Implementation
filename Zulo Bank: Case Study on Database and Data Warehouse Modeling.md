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

