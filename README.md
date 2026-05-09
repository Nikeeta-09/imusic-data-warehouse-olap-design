# imusic-data-warehouse-olap-design
Star Schema based OLAP Data Warehouse design for global music sales analytics using dimensional modelling and SCD Type 2 concepts.
# iMusic Data Warehouse OLAP Design

## Overview
This project presents the design and implementation of an OLAP-based Data Warehouse solution for the iMusic company. The solution was developed using a Star Schema architecture to support analytical reporting and business intelligence operations on global music sales data.

The project focuses on dimensional modelling, Slowly Changing Dimensions (SCD Type 2), currency normalization, and data quality assurance principles.

---

## Key Features

- Star Schema dimensional modelling
- Fact and Dimension table design
- OLAP analytical architecture
- Revenue calculation and aggregation
- Currency conversion support
- SCD Type 2 implementation
- Data Quality Assurance (DQA)
- Historical customer tracking

---

## Technologies Used

- SQL
- Data Warehousing Concepts
- OLAP
- Star Schema
- Dimensional Modelling

---

## Data Warehouse Design

### Fact Table
- FactSales

### Dimension Tables
- DimCustomer
- DimArtist
- DimTrack
- DimAlbum
- DimMediaType
- DimDate
- DimCity

---

## Key Concepts Implemented

### Slowly Changing Dimension (SCD Type 2)
Customer historical changes such as address and city updates are preserved using SCD Type 2 implementation.

### Currency Standardization
All financial metrics are normalized into USD using exchange rate conversion logic.

### Data Quality Assurance
Implemented checks for:
- Data Accuracy
- Data Validity
- Data Consistency
- Data Completeness
- Data Uniformity

---

## Business Objectives

The solution supports:
- Revenue analysis
- Customer behaviour tracking
- Artist and album performance analysis
- Time-based sales analytics
- Regional sales comparison

---

## Learning Outcomes

This project helped strengthen practical understanding of:
- Data warehouse architecture
- OLAP schema design
- Fact and dimension modelling
- Historical data tracking
- Enterprise reporting concepts

---

## Author

Nikeeta Kumari
Unitec Institute of Technology
