Hospital Management Database: Relational Analytics & MySQL Joins
A comprehensive data engineering and relational database analytics project. This repository demonstrates the migration of unstructured hospital data from Microsoft Excel into a fully normalized MySQL database schema to solve critical clinical and operational business intelligence queries.

.📌 Project Overview
Healthcare facilities generate massive volumes of interconnected operational data. This project converts flat-file patient, billing, diagnostic, and staffing data into a relational system. By executing advanced SQL optimization techniques—including multi-table joins, conditional aggregations, and subqueries—this analysis extracts actionable insights regarding patient medical profiles, hospital workloads, revenue generation, and resource allocation.

🛠️ Tech Stack & Architecture
Database Management System: 
MySQLData Ingestion & Extraction Tool:
Microsoft Excel (.xlsx / .csv)Core SQL Implementations: 
Multi-Way Inner Joins, Subqueries (Scalar & Correlated), Advanced Data Grouping (GROUP BY), Conditional Filtering (HAVING, WHERE).

📊 Relational Database Schema
The database architecture comprises 7 highly interconnected, normalized entities:

patient_details: Central entity containing patient demographic and contact metrics.
diagnosed: Tracks primary medical diagnoses, disease tracking, and chronicity records.
address: Stores structural geographic information for regional profiling.
medicine: Maps pharmaceutical prescriptions, inventory linkages, and unit prices.
doctors: Contains medical staff credentials and physician resource mappings.
rooms: Manages physical infrastructure parameters including room capacities, bed assignments, and floor layouts.
lab_test: Logs diagnostics data, medical screening procedures, and individual transaction values.

🚀 Key Business Analytics Solved
The analytical engine addresses three foundational categories of administrative business questions:

Operational Metrics (GROUP BY): Evaluates overall workload distribution across the clinical staff and classifies tracking metrics like disease frequencies or revenue by geographical territory.
System Connectivity (JOINS): Combines distributed tables to assemble comprehensive multi-dimensional clinical profiles, combining medical status with operational asset footprints (e.g., matching room allocations directly to active nursing staff).
Advanced Logic Filters (SUBQUERIES): Implements nested logical subsets to identify financial anomalies, track chronic disease trends, and perform statistical outlier tracking (such as identifying medical procedures priced above current institutional averages).
