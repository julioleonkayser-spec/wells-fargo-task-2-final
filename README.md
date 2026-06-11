# Wells Fargo Portfolio Management System — JPA Implementation

Wells Fargo Forage Software Engineering Program, Task 2

## Overview
A relational data model and Java/JPA entity layer for a financial advisor portfolio management platform. 
Enables advisors to manage multiple client accounts, each with a unified portfolio of investment securities.

## Architecture
- **4 Entities:** Financial Advisor, Client, Portfolio, Security
- **Relationships:** 1:N (Advisor→Client), 1:1 (Client↔Portfolio), 1:N (Portfolio→Security)
- **Key Features:** UUID primary keys, auto-generated IDs, CASCADE deletes, timestamp tracking
- **Technology:** Java, Spring/JPA, PostgreSQL

## Files
- `Advisor.java` - Financial advisor entity
- `Client.java` - Client investor entity  
- `Portfolio.java` - Portfolio collection entity
- `Security.java` - Individual security holdings
- `Wells_Fargo_Portfolio_ERD_md.pdf` - Design documentation & ERD

## Design Highlights
See the PDF for:
- Entity-Relationship Diagram (Crow's Foot notation)
- PostgreSQL DDL schema
- Design rationale & cardinality decisions
- Quality checklist
