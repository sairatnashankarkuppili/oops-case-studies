# Hospital Management System Case Study

## Problem Statement
Design an object-oriented hospital management system that manages patient records, schedules appointments, tracks medical staff, manages hospital resources, and handles billing and insurance claims.

## System Requirements
1. **Patient Management**:
   - Store patient personal and medical information
   - Track patient visits and medical history
   - Manage patient appointments

2. **Staff Management**:
   - Different types of medical staff (doctors, nurses, etc.)
   - Staff scheduling and availability
   - Specialization and department assignments

3. **Hospital Resources**:
   - Room and bed management
   - Medical equipment tracking
   - Medication inventory

4. **Treatment and Procedures**:
   - Prescriptions and medication administration
   - Laboratory tests and results
   - Surgical procedures

5. **Billing and Insurance**:
   - Generate patient bills
   - Process insurance claims
   - Track payments and outstanding balances

## Classes and Relationships

**Person-related Classes:**

**Medical-related Classes:**

**Hospital Resource Classes:**

**Administrative Classes:**


## Key OOP Concepts to Identify

1. **Inheritance**: Person → Patient/Employee, Employee → Doctor/Nurse
2. **Encapsulation**: Private medical records with controlled access
3. **Polymorphism**: Different employee types have different scheduling rules
4. **Abstraction**: Base classes define common interfaces
5. **Composition**: Hospital contains Departments, Departments contain Rooms
6. **Aggregation**: Doctor has Appointments, Patient has MedicalRecords
