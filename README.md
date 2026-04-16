# Relational Database Design – Animal Management System

This project focuses on designing and implementing a fully normalized relational database for managing animal-related data, including species, habitats, diets, and locations.

## Overview

The goal of this project was to build a structured database that avoids redundancy, maintains data integrity, and supports real-world relationships between entities. The database was designed using normalization principles and implemented with primary and foreign key relationships.

The system organizes data across multiple related tables rather than storing everything in one place, improving accuracy, scalability, and maintainability.

## Database Design

The database includes the following core entities:

- Animal
- Species
- Class
- Habitat
- Diet
- Location
- AnimalDiet (junction table)

Each table serves a specific purpose and is connected through foreign key relationships to maintain consistency across the system.

As shown in the database diagram (page 4), the structure clearly defines how each entity relates to another, forming a well-organized relational model. :contentReference[oaicite:0]{index=0}

## Key Concepts Demonstrated

### Normalization
- Eliminated redundant data
- Used foreign keys instead of repeated values
- Ensured efficient updates and data consistency

### Relational Integrity
- Primary keys uniquely identify each record
- Foreign keys enforce valid relationships between tables

### Data Organization
- Separated data into logical entities (Animal, Habitat, Diet, etc.)
- Improved clarity and scalability of the database structure

### Data Population
- Populated all tables with real records
- Verified data using SELECT queries

As shown in the population screenshots (pages 5–9), each table contains meaningful data and demonstrates successful implementation of the schema. :contentReference[oaicite:1]{index=1}

Example row counts:
- Animal: 68 records
- Diet: 25 records
- Species: 16 records
- Habitat: 10 records

## Why This Project Matters

This project demonstrates the ability to design a database from the ground up, not just query existing data. It reflects an understanding of:

- Data modeling
- Database normalization
- Entity relationships
- Real-world data structuring

These are foundational skills for database engineering, data analytics, and backend development.

## Files

- `animal_database_design.pdf` – full documentation including schema, diagram, and population proof

## Tools Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Database design diagrams
