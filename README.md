# House Debt & Rent Collection Management System

## 1. Project Information

| Field | Details |
|---|---|
| Student Name | Jean Claude Harerimana |
| Student ID | 20251SEN133 |
| Course | INSY 8311 – Database Development with PL/SQL |
| Academic Year | 2026–2027 |
| Project Area | Business and Entrepreneurship |
| Project Type | Database-driven Rental Management System |

## 2. Project Overview

The House Debt & Rent Collection Management System is a proposed database-driven solution designed to help landlords manage rental properties, tenants, rental agreements, monthly rent payments and outstanding rent balances.

The system will support landlords who own individual rental houses, multi-floor apartment buildings or multiple properties in different locations.

It will provide a centralized way to register properties and tenants, record rental agreements, monitor payment deadlines, track payment histories and manage overdue rent.

The system will also support payment extension requests and automated notifications to help landlords manage rent collection more efficiently.

## 3. Problem Statement

Managing rental properties and collecting monthly rent can become challenging, particularly for landlords who own multiple properties or manage many tenants.

Traditional record-keeping methods, such as notebooks, telephone calls and separate payment records, can make it difficult to monitor payment deadlines, identify overdue tenants, calculate outstanding balances and maintain accurate payment histories.

This project proposes a centralized database solution to improve rental information management, rent payment monitoring and overdue balance tracking.

The actual extent of these problems will be investigated through research and information collected from landlords.

## 4. Project Objectives

### Main Objective

To develop a database-driven system that improves rental property management and automates monthly rent payment monitoring and overdue debt tracking.

### Specific Objectives

1. To manage landlords, properties, buildings, floors and rental units.
2. To register tenants and maintain their rental agreements.
3. To record and monitor monthly rent payments.
4. To track upcoming payments, overdue rent and outstanding balances.
5. To manage tenant payment extension requests.
6. To generate automated payment reminders and overdue notices.

## 5. Data Source

**Proposed dataset:** Free Rental Management Dataset.

Source: https://databasesample.com/datasets/rental-management

Format: CSV, JSON

The dataset will be evaluated for its suitability, record count, licence, data quality and compatibility with the project's database requirements.

Additional real-world rental information will be investigated through landlord interviews and appropriately anonymized data collection.

## 6. Planned Database Entities

The initial database design will investigate the following entities:

- Landlords
- Properties
- Floors
- Rental Units
- Tenants
- Rental Agreements
- Rent Payments
- Payment Schedules
- Extension Requests
- Overdue Notices
- Maintenance Records

The final relational structure will be determined during the normalization and logical database design phase.

## 7. Planned PL/SQL Features

The project will use Oracle PL/SQL to implement business rules and database operations.

Planned features include:

- Stored procedures for registering properties, tenants and rental agreements.
- Procedures for recording and processing rent payments.
- Functions for calculating outstanding rent balances and payment status.
- Cursors for retrieving tenant payment histories and overdue accounts.
- Packages for organizing related rental management operations.
- Triggers for enforcing selected database rules and maintaining audit records.
- Exception handling for invalid transactions and business rule violations.
- DBMS_SCHEDULER for automated payment monitoring and reminder generation.

## 8. Innovation

**Selected innovation: Smart Automation**

The system will use Oracle DBMS_SCHEDULER and PL/SQL to automate rent payment monitoring.

The planned automation will:

- Identify upcoming rent payment deadlines.
- Identify tenants whose payments have become overdue.
- Generate payment reminders.
- Track approved payment extensions.
- Generate overdue notices when applicable.

An interactive application connected to the Oracle database will allow landlords to view rental information and payment statuses.

## 9. Repository Structure

The project is organized into research, documentation, data, database implementation, testing, innovation and screenshots directories.

## 10. References

Research papers, reports, existing rental management systems, datasets and technical documentation will be documented in `docs/research/research_log.md`.

