# Job Portal & Recruitment Database Management System

## Database Systems (IT301L) – Mini Project

A relational database management system designed to manage job seekers, companies, job vacancies, applications, skills, and interview schedules. The project demonstrates database design, ER modelling, relational schema conversion, normalization, and SQL implementation using Oracle Database.

## Project Overview

The Job Portal & Recruitment Database Management System aims to simplify and organize the recruitment process by maintaining structured information about employers, job seekers, available vacancies, and job applications.

The database facilitates efficient management of recruitment activities while maintaining data integrity, minimizing redundancy, and establishing relationships between different entities.

## Objectives

- Design an Entity-Relationship (ER) model for a job portal.
- Convert the ER model into a relational database schema.
- Apply database normalization up to Third Normal Form (3NF).
- Implement the database using Oracle SQL.
- Establish primary key and foreign key constraints.
- Maintain relationships between companies, job seekers, jobs, applications, skills, and interviews.
- Execute SQL queries to retrieve and manage recruitment-related information.

## Database Entities

The project consists of eight entities:

| Entity | Description |
|---|---|
| COMPANY | Stores company and employer information. |
| JOB | Maintains job vacancy details. |
| JOB_SEEKER | Stores candidate profiles and qualifications. |
| SKILL | Maintains a master list of skills. |
| SEEKER_SKILL | Maps job seekers to their respective skills. |
| JOB_SKILL | Stores the skills required for different jobs. |
| APPLICATION | Records job applications submitted by candidates. |
| INTERVIEW | Maintains interview schedules and feedback. |

## Database Design

The project incorporates:
- Entity-Relationship (ER) Modelling
- Relational Model Conversion
- Primary and Foreign Key Constraints
- One-to-Many (1:N) Relationships
- Many-to-Many (M:N) Relationships
- Composite Primary Keys
- Database Normalization (1NF, 2NF and 3NF)

## Technology Stack

- **Database:** Oracle Database
- **Query Language:** Oracle SQL
- **Development Environment:** [FreeSQL](https://freesql.com/)

## Project Structure

```text
DBS/
│
├── README.md
│
├── Convert_ER_Model_to_Relational_Model_and_Normalization.docx
│
└── Job_Portal_Database.sql
```

## Team Members

- Hifza Siddiqui
- Himalika Verma
- Bhavesh Yadav

## Project Deliverables

1. ER Model to Relational Model Conversion and Database Normalization – Word Document.
2. Final Oracle SQL Implementation – SQL Script.
3. Project Documentation – README.md.

## Learning Outcomes

Through this project, we aim to understand the practical implementation of relational database concepts, entity relationships, normalization techniques, integrity constraints, and SQL-based database operations.

---

**Course:** Database Systems (IT301L)  
**Project Type:** Mini Project  
**Repository:** DBS
